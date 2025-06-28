# Data Classification Policy

## 1. Purpose
This policy ensures that all ACME Corp data is identified, labeled, and protected based on its sensitivity, value, and potential impact if compromised. By classifying data, we reduce the risk of unauthorized access, data loss, and non-compliance with privacy laws.

## 2. Scope
This policy applies to:
- All ACME Corp employees, contractors, vendors, and partners.
- All forms of data (structured and unstructured) across internal systems, cloud services, and third-party platforms.

## 3. Definitions
- **Data Classification**: The process of categorizing information according to its sensitivity and the level of protection required.
- **Sensitive Data**: Any data that, if disclosed, could cause harm to individuals or the organization.
- **Data Owner**: The individual or team responsible for the integrity and security of a specific data set.

## 4. Classification Levels

| Level | Description | Examples | Controls |
|-------|-------------|----------|----------|
| **Public** | Openly shareable, no damage if exposed | Website content, press releases | No restrictions |
| **Internal Use Only** | Non-public, limited access | Org charts, internal memos | Access control, no public sharing |
| **Confidential** | Can cause moderate harm if exposed | Financial reports, employee records | Encryption, role-based access |
| **Restricted** | High-risk, legally/contractually protected | PII, PHI, credentials, legal docs | Strong encryption, audit logs, MFA |

## 5. Handling Requirements
- **Storage**: Confidential and Restricted data must be stored in encrypted repositories.
- **Transmission**: Must use encrypted channels (e.g., HTTPS, SFTP, VPN).
- **Access**: Based on the principle of least privilege; only those who "need-to-know" get access.
- **Disposal**: Data must be securely deleted (using DoD-standard wipe or equivalent) when no longer needed.

## 6. Roles & Responsibilities
- **Employees**: Understand and apply the correct classification during data creation and sharing.
- **Managers/Data Owners**: Label data appropriately and enforce protection controls.
- **IT & Security Team**: Enforce access rules, monitor logs, and audit compliance.

## 7. Exceptions
All exceptions must be formally requested, documented, and approved by the Security Governance Team.

## 8. References
- **NIST SP 800-53 Rev. 5**: PL-2, MP-3, SC-12  
- **ISO/IEC 27001:2013**: Control A.8.2 – Information Classification  
- **ACME Corp Acceptable Use Policy**

## 9. Review & Approval
- **Owner**: Security Governance Team  
- **Effective Date**: June 28, 2025  
- **Next Review**: December 2025  
- **Approved By**: Riya Chordiya, Security Governance Lead
