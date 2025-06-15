# AWS IAM, Secure Storage, and Data Encryption

This project demonstrates how to:

- Implement IAM policies in AWS
- Enable secure storage using Amazon S3
- Enable data encryption (SSE-S3 or SSE-KMS)
- Access encrypted S3 files securely using Lambda

## Structure

- `lambda_function.py`: Python code to access encrypted S3 file
- `README.md`: Instructions
- `/screenshots`: Setup images

## Instructions

1. Create an encrypted S3 bucket.
2. Upload `sample.txt`.
3. Assign IAM role to Lambda with S3 read access.
4. Deploy `lambda_function.py` in AWS Lambda.

## License

Educational/demo use only.
