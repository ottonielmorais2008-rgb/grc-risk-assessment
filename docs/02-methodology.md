# 2. Methodology

Each risk is scored as **Risk = Likelihood x Impact**, both on a 1 to 5 scale.

| Score | Likelihood | Impact |
|-------|------------|--------|
| 1 | Rare | Negligible: no real effect |
| 2 | Unlikely | Minor: a few hours of disruption |
| 3 | Possible | Moderate: a day of disruption or a small data leak |
| 4 | Likely | Major: several days down, customer data exposed |
| 5 | Almost certain | Severe: business cannot operate, legal penalties |

## Risk levels

| Score | Level | Action |
|-------|-------|--------|
| 1-5 | Low | Accept and monitor |
| 6-11 | Medium | Treat within 3 months |
| 12-25 | High | Treat within 1 month |

## Risk matrix

| Likelihood \ Impact | 1 | 2 | 3 | 4 | 5 |
|---|---|---|---|---|---|
| **5** | 5 | 10 | 15 | 20 | 25 |
| **4** | 4 | 8 | 12 | **16 (R01, R02)** | 20 |
| **3** | 3 | 6 (R11) | 9 (R05, R06, R08, R09) | **12 (R04, R10)** | **15 (R03)** |
| **2** | 2 | 4 | 6 | 8 (R07, R12) | 10 |
| **1** | 1 | 2 | 3 | 4 | 5 |

Treatment options: **Mitigate** (add controls), **Transfer** (insurance, supplier), **Avoid** (stop the activity) or **Accept**.

Next: [Risk register](03-risk-register.md)
