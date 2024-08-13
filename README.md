# Capstone-Project-CloudUploader-CLI

Overview
The Cloud File Uploader CLI is a Bash-based tool that allows users to upload files to cloud storage solutions quickly and easily. Currently, the tool supports AWS S3 and Google Cloud Storage. This tool provides a simple command-line interface to upload files, ensuring a smooth integration with popular cloud storage services.

**Prerequisites**
Before you use this tool, you need to ensure the following prerequisites are met:

Bash Environment: Ensure you have a Bash environment available. Most Unix-based systems, including Linux and macOS, come with Bash pre-installed.

**Cloud Storage CLI Tools:**

**AWS S3:** Install the AWS CLI tool. Follow AWS CLI Installation Instructions.
Google Cloud Storage: Install the Google Cloud SDK which includes gsutil. Follow Google Cloud SDK Installation Instructions.
API Credentials:

**AWS S3:** Configure your AWS credentials using aws configure. Ensure you have AWS_ACCESS_KEY_ID and AWS_SECRET_ACCESS_KEY.
Google Cloud Storage: Authenticate using gcloud auth login and ensure you have the appropriate permissions.
Setup

**Clone the Repository:**
If you have a repository, clone it to your local machine. If not, create a new directory and save the script files.

**Troubleshooting**
**Common Issues**
**File Not Found:**

**Error Message:** **File not found:** **<file-path>**
**Solution:** Ensure the file path is correct and the file exists at the specified location.
AWS CLI Configuration Issues:

**Error Message: Failed to upload file.**
**Solution:** Ensure AWS CLI is configured properly with aws configure and that you have the necessary permissions for the S3 bucket.
Google Cloud SDK Authentication Issues:

**Error Message:** **Failed to upload file.**
**Solution:** Make sure you are authenticated using gcloud auth login and have the appropriate permissions for the GCS bucket.
Command Not Found:

**Error Message:** **command not found**: **aws** or **command not found: gsutil**
**Solution:** Ensure the AWS CLI or Google Cloud SDK is installed and properly added to your system's PATH.
Permission Denied:

**Error Message: Permission denied**
**Solution:** Check file permissions and ensure that you have the appropriate access rights to the bucket and the file.


