# 📘 AWS Config & Rules

AWS Config tracks resource configurations and can enforce compliance rules.

---

## ✅ Steps to Enable AWS Config

1. Go to **AWS Config**
2. Click **Set up AWS Config**
3. Choose:
   - Record **all resources**
   - Include **global resources**
4. Select an **S3 bucket** for logs
5. Set up **AWS Config Rules**

---

## 🧾 Recommended Rules

| Rule Name                  | Purpose                                 |
|---------------------------|-----------------------------------------|
| `root-account-mfa-enabled`| Enforces MFA for root account           |
| `iam-password-policy`     | Validates password policy strength      |
| `s3-bucket-public-read-prohibited` | Blocks public read on S3 buckets |
| `cloud-trail-enabled`     | Ensures CloudTrail is turned on         |
| `ec2-instance-no-public-ip` | Restricts public IP on EC2            |

---

## 📌 Notes

- Use **Conformance Packs** for bundled rules
- Integrate with **Security Hub** for visibility
- Evaluate resources regularly and act on non-compliance

