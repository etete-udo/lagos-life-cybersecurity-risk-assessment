Lagos Life Cybersecurity Risk Assessment
Project type: Desk-based cybersecurity risk assessment
Case study: Lagos Life online life-simulation game
Prepared by: Udo, Etete O.
Department: Cybersecurity
Date: October 2026
Overview
This project assesses potential cybersecurity risks associated with Lagos Life, using publicly available information and established cybersecurity guidance. It considers risks affecting player accounts, personal information, communication features, payment processing, game data, cloud infrastructure, and service availability.
The report identifies potential threats and proposes controls to reduce their likelihood or impact. It does not establish that Lagos Life has experienced a breach or that its systems contain exploitable vulnerabilities.
Project objectives
Identify potential cybersecurity threats affecting an online gaming platform.
Examine account hacking, phishing, data exposure, fraudulent transactions, insecure API authorization, denial-of-service attacks, malware, and insider threats.
Explain possible effects on players and the platform.
Prioritize scenarios using a qualitative likelihood-and-impact risk matrix.
Recommend preventive, detective, and corrective security controls.
Key findings
The report assigns preliminary High ratings to:
Account hacking — 16
Phishing and social engineering — 16
Unauthorized data exposure — 15
Fraudulent payment or top-up activity — 15
Insecure API authorization — 15
Denial-of-service attack — 12
Malware affecting players and insider misuse are rated Moderate at 9 and 8 respectively. These are preliminary planning estimates, not measured incident probabilities. Ratings should be revised if technical testing, incident records, architecture reviews, or control-verification evidence becomes available.
Recommended controls
The report recommends:
Strong authentication, protected sessions, login rate limits, and suspicious-login detection.
Player awareness guidance and reporting channels for phishing.
Least-privilege database access, secure configuration, encryption where appropriate, and audit logging.
Server-side payment verification, transaction validation, duplicate-processing prevention, and reconciliation.
Server-side authorization checks for sensitive API operations.
Traffic monitoring, rate limiting, and suitable denial-of-service protection.
Restricted administrative access and multifactor authentication for privileged accounts.
Security monitoring, incident-response procedures, backups, and regular authorized assessments.
Repository contents
.
├── README.md
├── documentation/
│   ├── methodology.md
│   ├── risk-assessment-matrix.md
│   ├── risk-assessment-matrix.csv
│   └── recommendations.md
├── report/
│   └── cybersecurity-project-report.docx
└── GITHUB_UPLOAD_GUIDE.md
Methodology summary
This is a desk-based assessment using publicly available information and established cybersecurity guidance. The report references the Lagos Life privacy policy and relevant cybersecurity guidance. No internal source code was examined, no administrative access was available, no penetration testing was conducted, and database permissions or cloud configurations were not independently verified.
See documentation/methodology.md for details.
Scope
The assessment considers registration and authentication, password management and recovery, player information, game progress and in-game balances, chat, payment verification, APIs, cloud infrastructure, availability, and incident response.
Limitations
No internal source code review.
No authenticated access to administrative systems.
No penetration testing.
No independent verification of database permissions or cloud configurations.
No review of internal incident logs or confirmed breach records.
Risk scores are preliminary estimates.
References
Federal Republic of Nigeria. (2023). Nigeria Data Protection Act, 2023. Nigeria Data Protection Commission. https://ndpc.gov.ng/
Lagos Life. (n.d.). Privacy policy. https://lagoslife.com.ng/privacy
National Institute of Standards and Technology. (2024). The NIST Cybersecurity Framework (CSF) 2.0 (NIST CSWP 29). https://doi.org/10.6028/NIST.CSWP.29
OWASP Foundation. (n.d.). Authentication Cheat Sheet. https://cheatsheetseries.owasp.org/cheatsheets/Authentication_Cheat_Sheet.html
OWASP Foundation. (n.d.). REST Security Cheat Sheet. https://cheatsheetseries.owasp.org/cheatsheets/REST_Security_Cheat_Sheet.html
OWASP Foundation. (n.d.). OWASP API Security Top 10. https://owasp.org/www-project-api-security/
Responsible-use note
This repository documents a risk assessment, not an authorization to test Lagos Life. Any technical testing should only be performed with explicit authorization and within an agreed scope.