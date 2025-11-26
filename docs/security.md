# Security Overview

Security posture of the **Computer Vision Pipeline**.

## Data Protection

- **Encryption**: S3 SSE-KMS for all media
- **Transit**: TLS for all video streams
- **PII handling**: Face data anonymization options
- **Retention**: Configurable deletion policies

## Access Controls

- **IAM roles**: Per-function least privilege
- **VPC**: Private subnets for processing
- **API Gateway**: Throttling and authentication

## Privacy Compliance

- GDPR-ready with consent management
- Face data can be excluded from storage
- Audit logging for all access

> See `SECURITY.md` for detailed configurations.
