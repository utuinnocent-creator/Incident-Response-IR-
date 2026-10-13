# Incident Response Lab Report

## Overview
I conducted a simulated ransomware incident response exercise for SecureHealth. The lab applied the full IR lifecycle—preparation, detection, containment, eradication, and recovery—to strengthen healthcare cybersecurity resilience and HIPAA compliance.

## Preparation
- Roles: IR team, IT security, compliance, system admins, executive leadership
- Tools: CrowdStrike EDR, Recorded Future, Veeam backups, SIEM, MFA
- Strengths: strong endpoint monitoring, reliable backups, compliance alignment
- Weaknesses: limited phishing awareness, incomplete automation, vendor monitoring gaps

## Detection & Identification
- IoCs: phishing emails, abnormal PowerShell activity, failed logins, unauthorized remote sessions, encrypted files
- Logs revealed credential compromise, lateral movement, and attempts to disable endpoint protection

## Containment
- Isolated infected systems
- Disabled compromised accounts
- Blocked malicious IPs/domains
- Preserved forensic evidence
- Long-term strategies: network segmentation, phishing protection, patch management, Zero Trust

## Eradication
- Removed malicious files and persistence mechanisms
- Reset credentials and reimaged systems
- Applied patches and restored endpoint security

## Recovery
- Restored EMR and telehealth systems from secure backups
- Verified with antivirus scans, authentication tests, and SIEM monitoring
- Continuous post-recovery monitoring and threat hunting

## Post-Incident Review
- Successes: rapid isolation, effective backups, strong communication
- Gaps: delayed phishing detection, limited automation, weak vendor monitoring
- Recommendations: phishing simulations, tabletop IR exercises, expanded automation, stronger vendor risk management

## Continuous Improvement
- Quarterly IR drills and updated playbooks
- Zero Trust architecture
- Advanced email filtering and behavioral analytics
- MFA enforcement
- Employee and security team training

## Conclusion
This lab demonstrated a structured incident response process that improved detection, containment, and recovery from ransomware. By addressing gaps in phishing awareness, automation, and vendor monitoring
