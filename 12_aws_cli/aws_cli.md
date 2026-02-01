# AWS CLI Commands

The AWS CLI allows you to manage AWS services directly from the terminal.  
Before using, make sure you have the AWS CLI installed and configured with your **access key, secret key, and region**.

---

## **1. Configure AWS CLI**
Set your credentials and default region:
```bash
aws configure
# Prompts for:
# AWS Access Key ID
# AWS Secret Access Key
# Default region name (e.g., us-east-1)

- `aws configure` → Set credentials
- `aws sts get-caller-identity` → Current identity
- `aws ec2 describe-instances` → List instances
- `aws s3 mb s3://bucket-name` → Make S3 bucket
- `aws s3 ls` → List buckets
