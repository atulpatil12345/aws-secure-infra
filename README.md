# 🔐 AWS Secure Infrastructure

This project provides a secure and compliant baseline to be used when starting a new AWS environment manually.

## 📦 Key Components

| Component         | Description                                    |
|------------------|------------------------------------------------|
| Default VPC Removal | Remove insecure default networks            |
| CloudTrail        | API-level logging for auditing                 |
| IAM Security      | Best practices for identity & access           |
| AWS Config Rules  | Continuous compliance monitoring               |

---

## 📁 Documentation

- [CloudTrail Setup](docs/cloudtrail-setup.md)
- [IAM Best Practices](docs/iam-best-practices.md)
- [AWS Config Rules](docs/aws-config-rules.md)

---

## 🛠️ Setup Guide

1. **Delete Default VPCs** in all AWS regions
2. **Enable CloudTrail** in multi-region mode
3. **Apply IAM Security Baseline**
4. **Enable AWS Config & Add Rules**
5. **Enable GuardDuty (Optional)**
6. **Set up centralized logging (Optional)**
7. **Monitor with CloudWatch and Alerts**
8. **Set Budgets and Cost Alerts**

Refer to the docs for detailed steps.
