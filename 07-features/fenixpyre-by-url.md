---
title: "FenixPyre by URL Feature"
description: "How FenixPyre by URL automatically encrypts files downloaded from specified URLs to enhance security with minimal effort."
slug: /07-features/fenixpyre-by-url
keywords: [fenixpyre, encryption, url protection, features]
last_updated: 2023-10-01
---

## Why it matters
FenixPyre by URL ensures that files from trusted sources are automatically encrypted, reducing risks of data breaches during downloads.

FenixPyre by URL protects files downloaded from specified URLs. You can configure URLs to encrypt everything users download from those domains.

This feature works with both web and intranet URLs, encrypting files regardless of their extensions, even if they're not in your protected list. It provides maximum control with minimal setup.

### How to Activate FenixPyre by URL
To enable this feature, follow these high-level steps:

1. **Admin Configuration:** Specify URLs in the FenixPyre dashboard.
2. **User Setup:** Install the FenixPyre browser extension.
3. **Agent Compatibility:** Ensure the FenixPyre desktop app is version 5.1.0 or later.

#### Step 1: Specify URLs in the Dashboard
1. Log in to the FenixPyre admin dashboard.
2. Go to Settings > Global Policies > Browser Extension Settings.
3. Enter the URL patterns, separated by commas.
4. Click Update.

> **Note:** Use formats like <scheme>://<host>[:<port>], and support wildcards (e.g., https://*.contoso.com).

#### Step 2: Install the Browser Extension
1. Go to the Chrome Web Store and search for "FenixPyre: Secure File Platform".
2. Install the extension and restart your browser.

#### Step 3: Update the Desktop App
1. If not installed, download it from the FenixPyre portal.
2. Open the system tray, click the FenixPyre icon, and select Help > Check and Install Update.

Once set up, files from specified URLs will automatically move to the protected downloads folder and be encrypted.

## Next Steps / Related Topics
Learn about protected folders in [Protected Folders Guide](../05-user-guide/protected-folders.md).