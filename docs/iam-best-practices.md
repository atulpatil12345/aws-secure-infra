# 🔐 IAM Best Practices

IAM defines **who can access what** in your AWS account. Misconfigurations can lead to serious breaches.

---

## ✅ Key Best Practices

### 1. Use Groups, Not Individuals
- Assign permissions to IAM groups
- Attach policies to groups

### 2. Enforce MFA
- Enable **MFA** for all IAM users
- Especially for users with console access

### 3. Strong Password Policy
Go to **IAM → Account Settings** and configure:
- Min. length: 14 characters
- Require uppercase, number, symbol
- Password expiration: 90 days
- Prevent password reuse

### 4. Least Privilege Access
- Grant minimum required permissions
- Use **AWS Managed Policies** or **custom JSON**

### 5. Monitor Access
- Enable **CloudTrail**
- Use **IAM Access Analyzer**
- Regularly review **Access Advisor**

---

## 🚫 What to Avoid

- Root user for daily operations
- Hardcoded access keys
- Overly permissive policies (e.g., `*:*`)
