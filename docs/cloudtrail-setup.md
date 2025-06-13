# 📜 CloudTrail Setup Guide

CloudTrail is an essential logging service that records all AWS API calls and actions.

## ✅ Goals

- Enable multi-region trails
- Log management & data events
- Deliver logs to a secure S3 bucket
- Optional: Integrate with CloudWatch

---

## 🧭 Steps

1. Go to **CloudTrail Console**
2. Click **Create Trail**
3. Name your trail (e.g., `org-trail`)
4. Select:
   - Enable for **all regions**
   - Enable **management events**
   - Enable **data events** (S3, Lambda)
5. Create or select an **S3 bucket**:
   - Enable encryption
   - Enable log file validation
6. (Optional) Enable **CloudWatch Logs**
7. Click **Create trail**

---

## 🔐 Security Tips

- Use a dedicated logging account
- Restrict S3 bucket access using bucket policy
- Enable CloudTrail log file validation
- Deny delete access using bucket policy

