# Investigation-and-Research-Report LifeLabs Data Breach 

##  Project Overview

In this project, I conducted a comprehensive investigation and research analysis of the LifeLabs data breach, one of Canada’s most significant cybersecurity incidents. The breach, which occurred in late 2019, compromised the personal and medical information of approximately 15 million individuals. The objective of this project was to identify the root causes of the attack, assess the damage, evaluate the technologies exploited, and recommend effective mitigation strategies and security controls.

---

## Project Summary

- **Project Type:** Cybersecurity Research & Threat Analysis
- **Subject:** LifeLabs 2019 Data Breach
- **Industry:** Healthcare / Medical Diagnostics
- **Key Focus:** Risk Analysis, Incident Timeline, Threat Actors, Control Gaps, Remediation
- **Compliance Context:** ISO/IEC 27001, NIST SP 800-53, CISA Awareness Standards

This report aims to draw lessons from real-world security failures and identify how future threats can be mitigated through improved security posture and governance.

---

##  Methodology

1. **Incident Review:**
   - Researched public disclosures and privacy commissioner investigations.
   - Analyzed official statements and timeline data.
   
2. **Threat Vector Analysis:**
   - Identified tools, techniques, and procedures (TTPs) used by the attackers.
   - Mapped them to standard attack frameworks and incident stages.

3. **System Review:**
   - Evaluated targeted systems and data exposure.
   - Assessed weaknesses in access control, monitoring, and response.

4. **Control Recommendations:**
   - Proposed proactive security measures aligned with best practices.
   - Recommended preventive and detective technical safeguards.

---

##  Table of Attack Components

| Component                    | Description                                                                 |
|-----------------------------|-----------------------------------------------------------------------------|
| **Attack Entry Point**      | Phishing email used to steal employee credentials                          |
| **Lateral Movement**        | Internal credential use allowed access to databases and sensitive systems  |
| **Data Exfiltration**       | Lab results, health numbers, emails, personal info stolen                   |
| **Detection Delay**         | Several weeks between breach and detection                                 |
| **Disclosure Delay**        | Public informed nearly 2 months after breach                               |
| **Outcome**                 | Legal consequences, fines, reputational damage                             |

---

##  Key Findings

- Personal data of ~15 million Canadians was exposed.
- Lab results of 85,000 individuals were specifically targeted.
- LifeLabs paid ransom to the attackers to prevent data publication.
- Lack of basic controls like MFA, phishing defenses, and SIEM led to delayed detection.
- Legal investigations revealed major non-compliance with privacy legislation.

---

##  Recommended Security Controls

| Control                        | Purpose                                                                 |
|-------------------------------|-------------------------------------------------------------------------|
| Multi-Factor Authentication    | Prevent unauthorized access through stolen credentials                  |
| Endpoint Detection & Response  | Detect lateral movement and unauthorized access                         |
| Intrusion Detection/Prevention | Alert on network anomalies and breach attempts                          |
| Data Loss Prevention           | Monitor and restrict data exfiltration attempts                         |
| Security Awareness Training    | Mitigate phishing and human-factor risks                               |
| SIEM (e.g., Splunk)            | Enable real-time log aggregation and incident detection                  |
| Encryption                     | Ensure confidentiality even if data is exfiltrated                      |

---

##  Outcomes

- Identified technical and human-layer vulnerabilities.
- Proposed an action-oriented mitigation roadmap.
- Used standards like ISO 27001 and NIST SP 800-53 to structure responses.
- Delivered real-world incident handling experience.

---

##  Skills Gained

- Conducted real-world breach investigation and documentation.
- Applied ISO/IEC and NIST frameworks in a reporting context.
- Developed post-breach recommendations with technical depth.
- Strengthened knowledge of ransomware and healthcare sector threats.
- Improved writing skills for technical audiences and stakeholders.

---

##  Project file



---

##  References

- [CTV News – LifeLabs pays ransom](https://www.ctvnews.ca/business/lifelabs-pays-ransom-after-cyberattack-exposes-personal-information-of-15-million-canadians-1.4731520)
- [CBC – LifeLabs cyberattack](https://www.cbc.ca/news/canada/british-columbia/lifelabs-hacked-cyberattack-1.5399577)
- [CISA Security Awareness](https://us-cert.cisa.gov/ncas/tips/ST04-003)
- [ISO/IEC 27001](https://www.iso.org/standard/54534.html)
- [NIST SP 800-53 Rev. 5](https://csrc.nist.gov/publications/detail/sp/800-53/rev-5/final)
- [LifeLabs Joint Investigation Report](https://www.ipc.on.ca/wp-content/uploads/2020/06/LifeLabs-Joint-Investigation-Report.pdf)

---

##  Disclaimer

> This is a **simulated academic project** intended for cybersecurity education and portfolio development. The content reflects real incident research and analysis for learning purposes.
