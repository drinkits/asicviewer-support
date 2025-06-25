# Data Security and Privacy Statement

**ASiC-E Signature Validator for Jira**

## Overview

The ASiC-E Signature Validator for Jira app is designed with security and privacy in mind. The app does not store, transmit, or process user data outside of your Jira instance. All operations are performed within the boundaries of your Jira environment.

## Data Usage

- The app accesses Jira attachments only for the purpose of validating ASiC-E (eDoc) digital signatures.
- No attachment data, user data, or validation results are sent to any external service or third party.
- All processing is performed in-memory and within your Jira server or Data Center environment.

## Data Storage

- The app does **not** persistently store any user data, attachment data, or validation results.
- No data is written to external databases, files, or cloud services.

## Data Transmission

- The app does **not** transmit any data outside your Jira instance.
- All REST API calls are made internally within Jira, using the current user's session and permissions.

## Permissions and Access

- The app uses the Jira REST API and enforces all standard Jira permission checks.
- Only users with permission to view an attachment in Jira can validate its signature.

## Security Practices

- All attachment access is authenticated and authorized using Jira's built-in mechanisms.
- The app does not introduce any new user accounts, roles, or external integrations.
- All streams and resources are properly closed to prevent resource leaks.

## Privacy

- The app does not collect, store, or share any personally identifiable information (PII).
- No analytics, tracking, or telemetry is included in the app.

## Contact

For questions or concerns about data security and privacy, please contact the app maintainer at:  
**support@drinkits.lv**