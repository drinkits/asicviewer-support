# ASiC-E Signature Validator for Jira

Welcome to the support page for the ASiC-E Signature Validator plugin for Jira!

This plugin allows you to easily validate digital signatures on ASiC-E (eDoc) container files attached to your Jira issues. You can check the authenticity and details of signatures directly from Jira, making it simple to ensure the integrity of your important documents.

## Key Features
- Validate digital signatures on supported attachment types (.edoc, .asice, .bdoc, etc.) directly within Jira
- View signer information, signature validity, and certificate details
- Works with multiple ASiC-E file formats
- Secure: Only users with permission can validate attachments
- Compatible with Jira 9 (Data Center) and Jira 10+

## How to Use
1. **Install the Plugin:**
   - Your Jira administrator can install the plugin using the Universal Plugin Manager.
2. **Validate Attachments:**
   - After installation, you’ll see a signature validation button next to supported attachments in Jira issues.
   - Click the button to validate the signature and view signer details instantly.

## File Size Limits
- There is a maximum file size for validation, set by your Jira administrator. If you try to validate a file that is too large, you’ll see a message letting you know.

**How to Change the File Size Limit (for Jira Administrators):**
1. Open your Jira startup script (e.g., `setenv.sh` for Linux or the Windows service parameters).
2. Add or update the following JVM parameter:
   ```
   -Dasic.validator.max.file.size.mb=200
   ```
   (Replace `200` with your desired limit in megabytes.)
3. Restart Jira for the change to take effect.

The default limit is 100 MB if not set. The allowed range is 1 MB to 1024 MB.

## Need Help?
For problems or feature requests, contact support@drinkits.lv directly or create an issue in this GitHub repository.
