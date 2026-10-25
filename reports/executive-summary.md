# Executive Risk Brief

**Client:** HarborPoint Health Services (fictional)  
**Audience:** Executive leadership and IT management  
**Assessment type:** Simulated portfolio case study  
**Assessment date:** October 2026

## Decision requested
Approve a 90-day risk-reduction plan focused first on identity security and recoverability, followed by endpoint hygiene, vendor oversight, and incident readiness. Assign accountable owners and require evidence of completion.

## Overall assessment
The fictional organization has six illustrative risks: **two Critical** and **four High** under the scoring method in [the methodology](../assessment/methodology.md). These ratings reflect assumed conditions, not verified findings.

| Immediate priority | Business rationale | Recommended action |
| --- | --- | --- |
| R-01: Account takeover | Compromised accounts could expose sensitive information and disrupt operations | Expand MFA and strengthen privileged authentication |
| R-02: Ransomware recovery | Untested restoration procedures could extend a critical outage | Test isolated/immutable backups and recovery runbooks |
| R-04: Endpoint exposure | Delayed patching increases the window of exposure | Establish centralized patch tracking and remediation targets |

## Recommended 90-day roadmap

**Days 0–30: Stabilize**
- IT Director: establish MFA rollout plan and track coverage.
- Infrastructure Lead: run a documented restoration exercise with recovery objectives.
- Executive sponsor: approve owners and reporting cadence.

**Days 31–60: Reduce exposure**
- Endpoint Administrator: produce asset/patch coverage metrics and remediate highest-risk overdue devices.
- Security Operations Lead: prioritize identity and critical-system log sources.
- Procurement/Security: create critical vendor inventory.

**Days 61–90: Validate**
- Run an incident-response tabletop exercise.
- Complete reviews of highest-criticality vendors.
- Deliver targeted staff awareness exercises.
- Re-score the register based on implementation evidence.

## Measures leadership should request
- Percentage of active accounts protected by MFA, segmented by privilege.
- Date, success criteria, and measured duration of the most recent restore test.
- Percentage of managed endpoints meeting patch timelines.
- Percentage of critical vendors with current risk reviews.
- Coverage of high-priority logs and completion of response exercises.

## Key trade-offs
- MFA rollout can increase support requests; phase deployment and plan account recovery.
- Backup resilience may require storage and testing costs, but reduces outage uncertainty.
- Vendor reviews and log onboarding require cross-functional coordination, not only IT effort.

## Limitations
This is not a real audit, penetration test, legal opinion, or evidence-based evaluation of any actual healthcare provider. No sensitive or patient data was accessed. Ratings and recommendations should be validated against real business requirements before use.

## Reference
National Institute of Standards and Technology, *The NIST Cybersecurity Framework (CSF) 2.0*: https://doi.org/10.6028/NIST.CSWP.29
