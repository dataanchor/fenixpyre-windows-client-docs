
## Why it matters
Resolving PDF signing problems ensures secure and reliable document encryption in FenixPyre, preventing disruptions in workflows.

This guide addresses a known issue where users encounter errors when signing PDF files with uploaded images in various Adobe software versions. PNG files offer the highest success rate, so try them first for better results.

### Steps to Attempt Signing

1. **Open the PDF and Select Signing Tool**  
   Open your PDF in Adobe and click the "sign document" icon.
   
   <!-- IMG: ./media/09-troubleshooting-&-faq/sign-document-icon.png | Alt: Adobe sign document icon highlighted -->

2. **Add Initials**  
   Choose **Add Initials** from the options.
   
   <!-- IMG: ./media/09-troubleshooting-&-faq/add-initials.png | Alt: Adobe add initials interface -->

3. **Select an Image**  
   Browse and select an image file, prioritizing PNG for compatibility.
   
   <!-- IMG: ./media/09-troubleshooting-&-faq/select-image.png | Alt: Adobe image selection dialog -->
   
   If an error like "Error attempting to read from file" appears, verify your image type.
   
   <!-- IMG: ./media/09-troubleshooting-&-faq/error-message.png | Alt: Adobe error message for file read issue -->

### Compatibility Table
The following table summarizes PNG and JPG support across Adobe versions with FenixPyre:

| Adobe Software              | Image Type | FenixPyre 2.7.1 | FenixPyre 3.0 | FenixPyre 3.1 |
|-----------------------------|------------|-----------------|---------------|---------------|
| Reader DC (2021.011.20039) | .jpg      | Not supported  | Not supported | Not supported |
|                             | .png      | Supported      | Supported     | Supported     |
| Reader DC (2021.011.20117) | .jpg      | Not supported  | Not supported | Not supported |
|                             | .png      | Supported      | Supported     | Supported     |
| Standard DC (2021.011.20039) | .jpg    | Not supported  | Not supported | Not supported |
|                             | .png      | Supported      | Supported     | Supported     |
| Standard DC (2021.011.20117) | .jpg   | Supported      | Not supported | Not supported |
|                             | .png      | Supported      | Supported     | Supported     |
| Standard DC (2022.001.20142) | .jpg   | Supported      | Not supported | Not supported |
|                             | .png      | Supported      | Not supported | Not supported |
| Reader Pro (2021.011.20039) | .jpg     | Supported      | Not supported | Not supported |
|                             | .png      | Supported      | Supported     | Supported     |
| Reader Pro (2021.011.20117) | .jpg     | Not supported  | Not supported | Not supported |
|                             | .png      | Not supported  | Supported     | Supported     |

> **Tip:** Always test with the latest Adobe updates for improved compatibility.

## Next Steps / Related Topics  
For more general troubleshooting tips, refer to the [Troubleshooting Index](/09-troubleshooting-&-faq/index.md).