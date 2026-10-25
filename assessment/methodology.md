# Risk Assessment Methodology

## Approach
This portfolio exercise uses fictional assumptions from [the company profile](../scenario/company-profile.md). The assessment is inspired by the NIST Cybersecurity Framework (CSF) 2.0 and a simplified qualitative risk model. It is **not** a formal NIST certification or an implementation of every CSF outcome.

## Likelihood (L)
| Score | Definition |
| --- | --- |
| 1 | Rare under assumed conditions |
| 2 | Unlikely |
| 3 | Plausible |
| 4 | Likely |
| 5 | Very likely |

## Business impact (I)
| Score | Definition |
| --- | --- |
| 1 | Minimal operational disruption |
| 2 | Limited disruption or recoverable cost |
| 3 | Material operational or financial disruption |
| 4 | Major interruption, sensitive-data exposure, or significant cost |
| 5 | Severe or sustained impact on critical operations and trust |

## Priority score
**Score = L × I** (range 1–25).

- **Critical:** 20–25
- **High:** 12–19
- **Moderate:** 6–11
- **Low:** 1–5

Scores are **ordinal prioritization aids**, not probabilities or dollar-loss estimates. Equal scores may still warrant different treatment based on dependencies and business priorities.

## Process
1. Define critical services, assets, and assumed control gaps.
2. Identify plausible threat events and their business consequences.
3. Assign illustrative likelihood and impact scores.
4. Record current controls and proposed improvements.
5. Map each recommendation to relevant NIST CSF 2.0 functions/outcomes.
6. Assign accountable owners, target dates, and verification evidence.
7. Reassess after controls are implemented.

## Framework reference
NIST Cybersecurity Framework 2.0: https://doi.org/10.6028/NIST.CSWP.29

Mappings in the risk register are illustrative. The framework is guidance for organizing cybersecurity outcomes, not a guarantee of security or compliance.
