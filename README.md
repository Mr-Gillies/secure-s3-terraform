# Secure AWS S3 Bucket with Terraform

This project uses Terraform to create a secure AWS S3 bucket. It includes versioning, encryption, and blocks public access by default. The goal is to follow best practices in cloud security while learning how to build infrastructure as code.

---

## What It Does

- Creates an S3 bucket with a unique name
- Enables versioning for file change history
- Enforces AES-256 server-side encryption
- Blocks all forms of public access
- Adds tags and supports easy teardown

---

## Tools Used

- **Terraform** – used for defining and deploying AWS infrastructure
- **AWS S3** – object storage used here with secure settings
- **IAM credentials** – used to authenticate your Terraform access to AWS

---

## How to Use

1. Make sure you have Terraform installed
2. Set your AWS credentials in the terminal:
   ```bash
   set AWS_ACCESS_KEY_ID=your-key
   set AWS_SECRET_ACCESS_KEY=your-secret

