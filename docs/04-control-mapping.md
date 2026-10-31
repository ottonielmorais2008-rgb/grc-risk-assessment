# 4. Control mapping

Each risk is mapped to a **NIST CSF 2.0** category and to **ISO/IEC 27001:2022 Annex A** controls.

| Risk | Proposed control | NIST CSF 2.0 | ISO/IEC 27001:2022 Annex A |
|------|------------------|--------------|----------------------------|
| R01 Phishing | Short phishing awareness training every 6 months; report-phishing routine | PR.AT Awareness and Training | 6.3 Information security awareness, education and training |
| R02 Passwords / MFA | Individual accounts, password manager, MFA on email, ordering platform and POS admin | PR.AA Identity Management, Authentication and Access Control | 5.17 Authentication information; 8.5 Secure authentication |
| R03 Ransomware / backups | Automatic cloud backup plus offline copy (3-2-1 rule), restore test every quarter; antivirus | PR.DS Data Security; RC.RP Incident Recovery Plan Execution | 8.13 Information backup; 8.7 Protection against malware |
| R04 Shared Wi-Fi | Separate guest network (or VLAN) isolated from POS and office | PR.IR Technology Infrastructure Resilience | 8.20 Networks security; 8.22 Segregation of networks |
| R10 No incident plan | One-page incident response plan with contacts and first steps | RS.MA Incident Management | 5.24 Information security incident management planning and preparation |
| R05 Updates | Automatic updates on laptop and phones; check router and POS firmware monthly | PR.PS Platform Security | 8.8 Management of technical vulnerabilities |
| R06 Lost devices | Full-disk encryption (BitLocker), screen lock, remote wipe on phones | PR.DS Data Security | 8.1 User endpoint devices; 8.24 Use of cryptography |
| R08 Personal data | Keep only needed fields, delete inactive loyalty records after 24 months | PR.DS Data Security | 5.34 Privacy and protection of PII |
| R09 Leavers' access | Leaver checklist: remove accounts and change shared codes on the last day | PR.AA Identity Management, Authentication and Access Control | 5.18 Access rights |
| R07 Supplier | Check the provider's security terms and data processing agreement; keep an order export | GV.SC Cybersecurity Supply Chain Risk Management | 5.19 Information security in supplier relationships |
| R12 Outages | Mobile data backup connection for the POS; offline card reader mode if supported | PR.IR Technology Infrastructure Resilience | 5.30 ICT readiness for business continuity |
| R11 Inventory | Simple asset and account inventory, reviewed every quarter | ID.AM Asset Management | 5.9 Inventory of information and other associated assets |

Next: [Treatment plan](05-treatment-plan.md)
