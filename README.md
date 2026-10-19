# Northstar-health-risk-register
Cybersecurity risk assessment and 20-risk register using NIST CSF 2.0 for a fictional healthcare organization.

## Project Overview

This project demonstrates a practical Governance, Risk, and Compliance (GRC) cybersecurity risk assessment using the NIST Cybersecurity Framework (CSF) 2.0.

The project identifies, evaluates, prioritizes, and documents 20 cybersecurity and operational risks across five healthcare scenarios.

## Organization Scenario

Northstar Health Network is a fictional U.S. healthcare organization operating four hospitals and one regional clinic.

The initial assessment scenarios involve:
- Unpatched medical IoT devices
- Inconsistent password policies
- Lack of an incident response plan
- Excessive privileged access
- Paper-based patient consent forms

## Role

**GRC Analyst — Portfolio Simulation**

Responsibilities include identifying risks, documenting assets and vulnerabilities, evaluating likelihood and impact, recording known controls, estimating residual risk, assigning risk owners, recommending treatment plans, and mapping risks to NIST CSF 2.0.

## Project Objectives

- Identify exactly 20 distinct risks, with four risks per scenario.
- Develop a structured risk register with 15 columns.
- Apply a consistent risk scoring methodology.
- Identify control gaps and recommend practical remediation.
- Map risks to relevant NIST CSF 2.0 categories and subcategories.
- Demonstrate risk documentation skills for a GRC portfolio.

## Risk Assessment Methodology

1. Review the scenario and identify assets requiring protection.
2. Identify relevant threats and vulnerabilities.
3. Write risk statements explaining the cause, event, and consequence.
4. Assign likelihood and impact scores from 1 to 5.
5. Calculate inherent risk scores.
6. Document existing controls and identify evidence gaps.
7. Estimate residual risk and assign risk owners.
8. Recommend risk treatment actions.
9. Map each risk to relevant NIST CSF 2.0 references.

## Risk Scoring

Likelihood:
- 1 — Rare
- 2 — Unlikely
- 3 — Possible
- 4 — Likely
- 5 — Almost Certain

Impact:
- 1 — Insignificant
- 2 — Minor
- 3 — Moderate
- 4 — Major
- 5 — Severe

**Inherent Risk Score = Likelihood × Impact**

| Score | Rating |
|---|---|
| 1–4 | Low |
| 5–9 | Moderate |
| 10–16 | High |
| 17–25 | Critical |

Scores are preliminary estimates based on the supplied scenarios, not measured incident probabilities.

Residual scores initially equal inherent scores because the scenarios do not establish consistently effective risk-reducing controls for these risks. These estimates must be reassessed after controls are verified and tested.

## Risk Register Columns

The register contains the following 15 columns:

1. Risk ID
2. Asset
3. Threat
4. Vulnerability
5. Risk Description
6. Category
7. Likelihood
8. Impact
9. Inherent Risk Score
10. Existing Controls
11. Residual Risk Score
12. Risk Owner
13. Treatment Plan
14. NIST CSF 2.0 Reference
15. Status

## NIST CSF 2.0 Mapping

Each risk is mapped to relevant outcomes within the six CSF functions:

- Govern (GV)
- Identify (ID)
- Protect (PR)
- Detect (DE)
- Respond (RS)
- Recover (RC)

References are proposed mappings and should be validated against the official framework before operational use.

Official reference: https://www.nist.gov/cyberframework

## Project Deliverables

- `README.md` — project overview and methodology.
- `risk_register.csv` — the 20-risk register in spreadsheet-compatible CSV format.
- `risk_register.xlsx` — a formatted Excel workbook with formulas, filters, conditional formatting, and a scoring guide.

## Assumptions and Limitations

- Northstar Health Network and the scenarios are fictional.
- No real audit, technical scan, interviews, or control testing was performed.
- Risk scores are illustrative and require validation.
- Controls not explicitly confirmed in the scenarios are identified as requiring verification.
- Proposed treatment plans are recommendations, not evidence of completed remediation.
- Risk owners are suggested organizational roles.

## Disclaimer

This is an educational GRC portfolio project. It does not represent an actual assessment of a real healthcare organization and does not claim compliance or certification.
