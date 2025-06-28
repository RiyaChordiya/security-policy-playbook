# Incident Response Playbook: Ransomware Attack

## 1. Description
Ransomware encrypts organizational data and demands payment for its release. Quick isolation is critical.

## 2. Detection
- Unusual CPU/disk activity on endpoints
- Inability to access files, file extensions changed
- Ransom note or splash screen appears

## 3. Containment
- Immediately isolate affected systems (network disconnect or shutdown)
- Disable shared drives
- Block C2 communication IPs and domains

## 4. Eradication
- Remove ransomware executables and scripts
- Restore from known clean backups
- Patch vulnerable systems

## 5. Recovery
- Validate system integrity before reconnecting to network
- Re-enable access gradually
- Monitor for reinfection

## 6. Lessons Learned
- Evaluate and harden endpoint protection
- Review backup/restore process
- Improve patch and software hygiene
