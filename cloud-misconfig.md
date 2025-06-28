# Incident Response Playbook: Cloud Misconfiguration

## 1. Description
A cloud misconfiguration incident occurs when cloud infrastructure is improperly set up, exposing sensitive data or services to unauthorized access (e.g., open S3 buckets, overly permissive IAM roles).

## 2. Detection
- Security tools (e.g., ScoutSuite, Prowler, AWS Config) flag misconfigurations
- Logs show access from unknown IPs or anonymous access
- Public exposure discovered via external scans or bug bounty reports

## 3. Containment
- Revoke public access immediately (e.g., restrict S3 bucket policy)
- Disable or limit exposed IAM roles or API keys
- Lock down misconfigured services

## 4. Eradication
- Identify the root cause (IaC errors, manual changes, default settings)
- Apply correct configurations with validated change controls
- Rotate all exposed credentials or secrets

## 5. Recovery
- Re-deploy secure infrastructure if necessary
- Enable config rules, alerts, and scanning tools
- Validate compliance with cloud security baselines

## 6. Lessons Learned
- Audit IaC templates and CI/CD processes
- Integrate cloud security checks into DevOps pipeline
- Train engineers on least privilege and secure-by-default principles
