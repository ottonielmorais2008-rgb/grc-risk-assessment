# 3. Risk register

L = Likelihood, I = Impact, Score = L x I (inherent risk, before new controls).

| ID | Risk | Assets | L | I | Score | Level | Treatment |
|----|------|--------|---|---|-------|-------|-----------|
| R01 | A phishing email steals the shared email password | A03, A04 | 4 | 4 | 16 | High | Mitigate |
| R02 | Shared and weak passwords, no multi-factor authentication (MFA) | A04, A05, A01 | 4 | 4 | 16 | High | Mitigate |
| R03 | Ransomware encrypts the office laptop and there is no tested backup | A02, A09, A10 | 3 | 5 | 15 | High | Mitigate |
| R04 | Guests on the same Wi-Fi as the POS and the office laptop | A01, A02, A08 | 3 | 4 | 12 | High | Mitigate |
| R10 | No incident response plan: staff don't know what to do after a breach | All | 3 | 4 | 12 | High | Mitigate |
| R05 | Router, laptop and POS not updated | A01, A02, A07 | 3 | 3 | 9 | Medium | Mitigate |
| R06 | Lost or stolen laptop or phone without encryption | A02, A03 | 3 | 3 | 9 | Medium | Mitigate |
| R08 | Customer personal data kept longer than needed (GDPR) | A06 | 3 | 3 | 9 | Medium | Mitigate |
| R09 | Former employees still have access to accounts | A04, A05 | 3 | 3 | 9 | Medium | Mitigate |
| R07 | Online ordering provider has an outage or a data breach | A05 | 2 | 4 | 8 | Medium | Transfer / Mitigate |
| R12 | POS or internet outage stops card payments | A01, A07 | 2 | 4 | 8 | Medium | Mitigate |
| R11 | No up-to-date list of devices and accounts | All | 3 | 2 | 6 | Medium | Mitigate |

The same data is available as [risk-register.csv](https://github.com/ottonielmorais2008-rgb/grc-risk-assessment/blob/main/risk-register.csv) for spreadsheets.

Next: [Control mapping](04-control-mapping.md)
