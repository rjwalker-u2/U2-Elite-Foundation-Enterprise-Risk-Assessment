# U2 Elite Foundation — Enterprise Cybersecurity Risk Assessment
**Framework:** NIST Cybersecurity Framework (CSF) | **Scope:** Nonprofit Organization | **Status:** Completed

## Executive Summary
This project simulates a full enterprise cybersecurity risk assessment for the U2 Elite Foundation, 
a nonprofit organization managing youth athletics programs, community initiatives, and digital operations. 
The assessment identifies critical organizational assets, evaluates threats and vulnerabilities, 
scores risks using a standardized Likelihood x Impact model, and maps recommended controls to the 
NIST Cybersecurity Framework (CSF). The findings highlight significant exposure in cloud storage 
configuration, staff endpoint security, and third-party payment systems — with prioritized 
remediation recommendations provided for each.


U2 Elite Foundation — Enterprise Cybersecurity Risk Assessment (NIST CSF Framework)
Overview

This project is a simulated enterprise risk assessment conducted for the U2 Elite Foundation, a nonprofit organization focused on youth athletics, community programs, and digital operations.
The purpose of this assessment is to identify key cyber risks, evaluate their impact and likelihood, and recommend controls aligned with the NIST Cybersecurity Framework (CSF).

## Objectives
- Identify and inventory critical organizational assets
- Analyze threats and vulnerabilities relevant to a nonprofit operating environment
- Score risks using a standardized Likelihood x Impact model (1–5 scale)
- Provide actionable mitigation recommendations
- Map all controls and findings to the NIST CSF (Identify, Protect, Detect, Respond, Recover)

## Deliverables
| Document | Description |
|---|---|
| Full Risk Assessment Report | Comprehensive findings, analysis, and recommendations |
| Risk Register (CSV) | Scored risk inventory with controls and ownership |
| Risk Heat Map | Visual representation of risk distribution by severity |
| NIST CSF Mapping Table | Control alignment across all five CSF functions |
| System Overview Diagram | Network and asset architecture of the simulated org |
| Acceptable Use Policy | Governing policy for staff and volunteer device usage |
| Access Control Policy | Role-based access standards and enforcement guidelines |
| Incident Response Plan | Documented procedures for detecting and responding to incidents |

## Framework
- **Primary:** NIST Cybersecurity Framework (CSF) — Identify, Protect, Detect, Respond, Recover
- **Risk Scoring:** Likelihood x Impact (1–5 scale); scores 15–25 = Critical, 8–14 = High, 4–7 = Medium, 1–3 = Low

## Key Findings
The assessment identified 6 priority risks requiring immediate or near-term remediation:

| Risk | Likelihood | Impact | Score | Priority |
|---|---|---|---|---|
| Phishing leading to account compromise | 4 | 5 | 20 | Critical |
| Misconfigured cloud storage (Google Workspace) | 3 | 5 | 15 | Critical |
| Unpatched staff and volunteer endpoints | 4 | 4 | 16 | Critical |
| Weak password hygiene / no MFA enforcement | 4 | 4 | 16 | Critical |
| Social media account takeover | 3 | 3 | 9 | High |
| Third-party payment vendor breach (Stripe/QuickBooks) | 2 | 5 | 10 | High |

---

## What I Learned
This project gave me hands-on experience applying a real enterprise GRC methodology from start to finish. 
Key takeaways include:

- **Framework application:** Translating NIST CSF theory into a practical control mapping exercise 
  revealed how many nonprofit organizations have significant gaps in the *Protect* and *Detect* functions.
- **Risk prioritization:** Scoring risks objectively using Likelihood x Impact helped me understand 
  how GRC analysts communicate urgency to leadership without overstating every finding.
- **Policy writing:** Drafting the Acceptable Use and Access Control policies required balancing 
  technical accuracy with language accessible to non-technical staff and volunteers.
- **Thinking like an attacker:** Identifying threats specific to a nonprofit — donor data, volunteer 
  onboarding, event registration portals — reinforced that risk context is always industry-specific.
- **Documentation discipline:** Producing a full deliverable set (report, register, heat map, policies, 
  diagrams) mirrors real GRC project work and showed me how interconnected each artifact is.

---

## Author
**RJ Walker** | Aspiring GRC Analyst | [Ronald Walker](https://www.linkedin.com/in/ronald-walker-ms-866a261b0?utm_source=share_via&utm_content=profile&utm_medium=member_ios)

*This is a portfolio project simulating a real-world GRC engagement. The U2 Elite Foundation 
scenario is fictional and created for educational and career development purposes.*
