# Data Recovery Plan for FenixPyre

A comprehensive guide to data recovery services using FenixPyre, including strategies for outages and decryption processes.


# Data Recovery Plan for FenixPyre

## Why it Matters
In an era of frequent service disruptions, this plan ensures secure data access and recovery, minimizing downtime and protecting sensitive information through robust encryption.

### Key Personnel
This section outlines the team responsible for recovery efforts.

| Name            | Title                       | Contact Information          |
|-----------------|-----------------------------|------------------------------|
| Jay Patel      | Customer Success Engineer   | Email: jay@fenixpyre.com     |
| Ryan Boder     | VP of Marketing and Customer Experience | Email: ryan.boder@fenixpyre.com |
| Eric Flecher   | Head of Product             | Email: eric@fenixpyre.com    |
| Harihara Varma Indukuri | Chief Technology Officer    | Email: hari@fenixpyre.com, Mobile: +1 (614)-779-3748 |

### Plan Overview
This document details FenixPyre's approach to data recovery during short-term and long-term outages, as well as full decryption for customers exiting the service.

#### Plan Updation
The recovery plan is reviewed and updated with any system changes, involving testing and formalized procedures under the CTO's oversight.

#### FenixPyre Database Backup Strategy
FenixPyre uses cloud services with NoSQL databases for backups. Key events like schedule changes are notified to customers.

| Frequency     | Unit       | Retention Time      |
|---------------|------------|---------------------|
| Hourly Snapshot | Every 2 hours | 7 days              |
| Daily Snapshot  | Day        | 7 days              |
| Weekly Snapshot | Friday     | 4 weeks             |
| Monthly Snapshot| Last day of month | 12 months           |

Customers are notified of:
1. Changes to backup schedules.
2. Downtime during migrations.
3. Downtime during upgrades.

### Plan Details
#### On-Boarding
##### Short Term Outages
Short-term outages occur when FenixPyre agents can't communicate with cloud services, blocking file decryption. FenixPyre mitigates this with cloud redundancy and regional failover, typically resolving in hours.

##### Long Term Outages
For extended outages, FenixPyre provides tools to decrypt files offline. Key components include:
1. Client Master Key: Used to decrypt data encryption keys.
2. Exported Data Encryption Keys file: Contains encrypted keys.
3. Client application: A Windows executable for decryption.

**Recovery Process (Step-by-Step)**
1. Place the Client Master Key, exported keys file, and executable in one folder.
2. Run the command in PowerShell: `FenixPyreDec.exe Decrypt <inputFolderPath>`.
3. The application decrypts all files, including sub-folders.

> **Note:** For a 444 GB dataset on network drives, decryption took about 12 hours.

#### Off-Boarding FenixPyre Platform
When discontinuing FenixPyre, decrypt files as follows:

##### Decrypt on End-Points
Admins enable decryption via the admin portal.

**Steps to Enable Decryption for All Users:**
1. Log in to the Admin Portal and select User Roles.
2. Click "Add New User Role".
3. In Right-Click Settings, enable decryption and assign to all users.

Once enabled, users can right-click protected folders to decrypt files.

##### Decrypt on Windows Server (2012 and above)
Use the client application in online mode.

**Instructions:**
1. Unzip the FenixPyreServer.zip file.
2. Ensure Microsoft Visual C++ 2015-2019 Redistributable (x64) is installed.
3. Open PowerShell as admin, navigate to the folder, and run `.\FenixPyreServerInstall.ps1`.
4. Enter the organization ID and proceed.
5. Right-click folders to decrypt.

##### Decrypt on Cloud Stores
Sync files to a Windows machine, then use the right-click menu to decrypt, and sync back.

##### Decrypt on Linux
For Linux servers using FenixPyre SDKs:

**Pre-requisites:** Ubuntu, Python 3+, FenixPyre Python SDK.

**Instructions:**
1. Update and install dependencies: `sudo apt-get update`, etc.
2. Install the SDK and use sample code to decrypt files.

Sample code snippet:
```python
import os
from fenixpyre import cryptoEngine  # Assuming SDK import

engine = cryptoEngine.FenixPyreCryptoEngine()
for root, dirs, files in os.walk(inputDir, topdown=False):
    for name in files:
        inputFile = os.path.join(inputDir, name)
        outputFile = os.path.join(outputDir, name)
        response = engine.DecryptFile(inputFile, outputFile)
```

## Next Steps / Related Topics
For more on FenixPyre encryption, see [FenixPyre Cloud Overview](/files/media/files/anchor-deck-fy22-cmmc-2-0-20221113/index.md).
