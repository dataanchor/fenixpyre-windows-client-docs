# FedRAMP Authorization Levels

Overview of FedRAMP authorization levels for various cloud services, focusing on security and compliance (≤160 characters).


# FedRAMP Authorization Levels

## Why it Matters
Understanding FedRAMP levels ensures secure cloud services meet federal standards, protecting sensitive data and supporting compliance efforts.

This document outlines authorization levels for various cloud services.

### FedRAMP Authorization Level 1
- **Cloud Scheduler**: Not confirmed; used for scheduling tasks in Egnyte auto-encryption.

### FedRAMP Authorization Level 2
- **Stackdriver Monitoring**: Moderate; for latency, CPU, and memory metrics.
- **Amazon CloudWatch**: High; for storing logs and latency metrics.
- **AWS Amplify**: High; not currently in use.
- **AWS Lambda**: High; used in early versions.
- **AWS Glue**: High; for storing monitoring logs.
- **Amazon Simple Notification Service**: High; for notifying cloud run on new uploads.
- **Amazon S3**: High; for storing files.

### FedRAMP Authorization Level 3
- **Compute Engine**: High; for physical instances.
- **Kubernetes Engine**: High; for managing applications.
- **Cloud Logging**: Moderate; for logging.
- **Networking**: Moderate; for traffic management.
- **Google Click to Deploy InfluxDB**: Moderate; one-click deploy template.
- **Google Click to Deploy Grafana**: Moderate; one-click deploy template.
- **Cloud Tasks**: Not confirmed; for encryption/decryption in 3PS.
- **Cloud Pub/Sub**: High; for sending HTTP notifications.
- **Cloud CDN**: Moderate; for serving media files.
- **Cloud Build**: Moderate; for building and deploying container images.
- **Cloud Key Management Service (KMS)**: High; for storing master keys.
- **Cloud Run**: Moderate; hosts services and logic.
- **Cloud Storage**: High; for persistent data volumes.
- **Cloud Memorystore for Redis**: High; for caching.
- **Cloud Filestore**: Moderate; for storing files.

## Next Steps / Related Topics
Explore related security practices in [FenixPyre Cloud Guide](files/media/files/fenixpyre-cloud-guide.md).
