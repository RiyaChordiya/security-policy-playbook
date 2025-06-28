# security-policy-playbook
# Security Policy & Incident Response Playbook

This project demonstrates my ability to create and manage foundational cybersecurity documentation aligned with real-world standards such as NIST 800-53, ISO 27001, and CIS Controls. It includes:

- Core organizational security policies
- Four detailed incident response (IR) playbooks
- Real-world incident scenarios
- Visual IR process flowchart
- Structured in a way that's usable in GRC, InfoSec, or audit settings

---

## Project Contents

### Policies

| Policy | Description |
|--------|-------------|
| [`acceptable-use-policy.md`](./policies/acceptable-use-policy.md) | Defines responsible use of company systems |
| [`data-classification-policy.md`](./policies/data-classification-policy.md) | Classifies and protects sensitive data |
| [`remote-access-policy.md`](./policies/remote-access-policy.md) | Secures remote access via VPN, MFA, and device hygiene |

---

### Incident Response Playbooks

| Playbook | Scenario |
|----------|----------|
| [`phishing-incident.md`](./playbooks/phishing-incident.md) | Detect and respond to social engineering email attacks |
| [`ransomware-incident.md`](./playbooks/ransomware-incident.md) | Contain and recover from data encryption/extortion |
| [`insider-threat.md`](./playbooks/insider-threat.md) | Investigate and mitigate misuse of internal access |
| [`cloud-misconfig.md`](./playbooks/cloud-misconfig.md) | Respond to public exposure due to misconfigured cloud services |

---

### Real-World Simulations

View four short scenarios in [`incident-scenarios.md`](./incident-scenarios.md), including:

- A phishing attempt caught via user report  
- A ransomware infection traced to a malicious Excel file  
- A developer abusing access after resignation  
- A misconfigured S3 bucket exposing internal reports

---

### IR Process Flowchart

This diagram shows the generic response lifecycle followed in each playbook:

![Incident Response Process](./assets/incident_response_flow.png)

---

## Key Frameworks & Sources

This project references:
- NIST SP 800-53 Rev. 5 (AC, IR, SC families)
- ISO/IEC 27001:2013 (Annex A.6, A.8, A.16)
- OWASP, CIS Controls v8, and internal SOC 2 practices

---

## Author

**Riya Chordiya**  
https://www.linkedin.com/in/riyachordiya/

---

## License

This project is licensed under the [MIT License](./LICENSE).  
You may use and adapt these templates for educational or organizational purposes. Attribution is appreciated.
