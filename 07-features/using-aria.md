# Getting Started with ARIA

Discover how ARIA, powered by AI, simplifies report analysis for FenixPyre users, providing quick insights without manual effort.


## Why it matters
ARIA streamlines data analysis in FenixPyre by leveraging AI to deliver actionable insights from reports, saving time and reducing errors for teams managing encrypted data.

ARIA is your intelligent interface powered by AI models, designed to deliver insights on user and application reports. It helps you analyze complex analytics effortlessly, eliminating the need for manual tools like Excel.

> **Note:** ARIA is currently in its beta phase. Expect occasional inaccuracies, and provide feedback to improve it by contacting support@fenixpyre.com.

### Quick Guide to Use ARIA

#### Step 1: Access the Interface
- Navigate to the **FenixPyre Admin Dashboard** and select **Reports > Ask Me Anything**.

#### Step 2: Upload Your Report
- Upload your log report file from user or application logs. For help on downloading reports, see the [FenixPyre Reports Guide](https://docs.fenixpyre.com/03-setup-&-installation/prerequisites.md).

<!-- IMG:     ./media/using-aria/upload-demo.gif | Alt: ARIA file upload demonstration -->

> **Tip:** Ensure the file is in CSV format and does not exceed 10MB. Only use unaltered reports from FenixPyre logs for compatibility.

#### Step 3: Query Your Data
- After uploading, type your queries into the prompt to get insights.

<!-- IMG:     ./media/using-aria/chat-demo.gif | Alt: ARIA chat interface in action -->

### Sample Queries for ARIA
Here are some examples to get started:
1. Which file had the highest number of accesses?
2. Which application was used for accessing 'example.txt'?
3. Provide an action summary for the user 'example@email.com'.

#### Data Security and Privacy
FenixPyre ensures data security with ARIA by processing reports internally. All messages are encrypting and stored securely, with data at rest protected by AES-256 and in transit via TLS.

#### Limitations
- **File Size:** Limit uploads to 10MB.
- **Query Precision:** Structure queries for summaries; results depend on accurate prompting.
- **Accuracy:** Beta status may lead to errors—cross-check with original files.
- **Context:** ARIA might not retain context across messages; refine prompts for better results.

## Next Steps / Related Topics
For more on FenixPyre features, check out [FenixPyre Core Concepts](https://docs.fenixpyre.com/02-core-concepts/encryption-model.md) or explore [Troubleshooting & FAQ](https://docs.fenixpyre.com/09-troubleshooting-&-faq/index.md).