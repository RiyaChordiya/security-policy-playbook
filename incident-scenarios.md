🎣 Phishing Scenario
On April 18, a staff member reported a suspicious email appearing to come from HR. The email contained a fake DocuSign link that led to a credential harvesting site. Logs showed the user clicked the link but did not submit credentials. The security team quarantined the email from all mailboxes and blocked the sender domain. No compromise confirmed.

🦠 Ransomware Scenario
On May 9, several employees noticed their files were renamed with a .lockr extension and a ransom note appeared on-screen. Security isolated the affected machines from the network and began restoring data from backups. Infection was traced to a macro-enabled Excel file from a spoofed vendor email.

🧑‍💻 Insider Threat Scenario
A developer with access to production attempted to download customer data after receiving a termination notice. DLP alerts flagged large data exports to a personal email. Access was immediately revoked, and HR/legal were engaged. No data was exfiltrated.

☁️ Cloud Misconfiguration Scenario
On June 15, an AWS Config rule flagged that an S3 bucket containing internal reports was publicly accessible. Investigation confirmed anonymous users could list and download contents. Bucket policy was updated, access logs were reviewed (no unauthorized access), and the IaC template was patched.

