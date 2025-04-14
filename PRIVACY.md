Privacy Policy for botos3 Plugin

Last Updated: March 21, 2025

### What This Plugin Does

The **botos3** plugin enables users to interact with S3-compatible services via the boto library. This includes operations such as uploading files, managing buckets, and accessing public URLs.

### Data Processed

The following data is processed during normal plugin operation:

- Files provided by the user for upload
- Metadata associated with the uploaded files (e.g., file names, sizes)
- S3-related configurations entered in the plugin credentials (e.g., endpoints, bucket names)

### Not Collected

The **botos3** plugin does not collect or store any personal information, including:

- Names or contact details
- Login credentials (credentials are used dynamically and not permanently stored locally or on a server)
- Device information
- Location data

### Data Handling

- All credentials and data provided are only used during the active session and processed securely in-memory.
- User files are uploaded directly to the specified S3-compatible endpoint and are not retained by the plugin.
- The plugin relies on the **boto3** library to interact with S3 services, processing everything locally on the user's environment.
- No files or data are stored on intermediary servers or shared with third parties.

### Your Control

You retain full control over your data. The plugin operates based on the configuration provided by you, and you can stop using the plugin at any time. Removing your plugin credentials will effectively stop all interactions with your S3 service.