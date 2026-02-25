# AWS S3 Mastery with Node.js (AWS SDK v3)

A deep-dive, production-focused project designed to master Amazon S3 using the AWS SDK for Node.js (v3).

This repository is not a simple CRUD example.
It is a structured engineering lab covering:

* S3 architecture fundamentals
* Security models and access control strategies
* Encryption and KMS integration
* Performance optimization techniques
* Storage class and lifecycle cost optimization
* Versioning and object lock strategies
* Event-driven integrations
* Infrastructure as Code (Terraform / CDK)
* Production-grade Node.js SDK patterns

---

## 🎯 Project Goal

To achieve professional-level mastery of Amazon S3 by:

* Understanding how S3 works internally
* Implementing secure-by-default bucket strategies
* Handling real-world edge cases
* Writing scalable and production-ready Node.js code
* Designing architectures that follow AWS best practices

---

## 🧠 Learning Structure

This project is divided into progressive modules:

### Phase 1 – S3 Fundamentals

* Bucket creation (secure configuration)
* Versioning
* Default encryption
* Block public access
* Object metadata

### Phase 2 – Secure File Manager

* Secure uploads with SSE-KMS
* Presigned URLs
* Streaming downloads
* Multipart uploads
* Pagination handling

### Phase 3 – Advanced Security

* IAM vs Bucket Policies
* Cross-account access
* VPC endpoint restrictions
* KMS key policies
* Access Points

### Phase 4 – Performance Engineering

* Multipart optimization
* Parallel uploads
* S3 request patterns
* Transfer Acceleration
* CloudFront integration

### Phase 5 – Cost & Storage Optimization

* Storage classes
* Lifecycle rules
* Intelligent tiering
* Glacier strategies
* Replication (CRR / SRR)

### Phase 6 – Production Patterns

* Event-driven architecture (S3 → SQS → Lambda)
* Logging & auditing
* Monitoring with CloudWatch
* Multi-region access patterns

---

## 🛠 Tech Stack

* Node.js
* AWS SDK v3
* Amazon S3
* AWS KMS
* IAM
* Terraform / AWS CDK
* Docker (optional)

---

## 🔐 Security Philosophy

All resources in this project are:

* Private by default
* Encrypted by default
* Access controlled via least privilege
* Designed for production environments

---

## 🚀 How to Use This Repository

Each folder represents a focused exercise.

Start from:

```
/exercises/01-secure-bucket-setup
```

Progress sequentially.

---

## 📚 Why This Project Exists

Most tutorials show how to upload a file.

This project teaches you how to engineer S3 systems professionally.

---

## 🧑‍💻 Author

Built as part of a structured AWS Engineering Mastery path.
