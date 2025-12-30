# Botium Toys: Internal IT Audit Project

Completion of the Botium Toys internal audit case study from the **Google Cybersecurity Professional Certificate** (Coursera).

## Project Summary
Botium Toys is a fictional U.S. toy retailer with a physical store/warehouse and growing online sales. The goal was to perform an internal IT audit to:
- Assess current controls
- Identify risks and vulnerabilities
- Evaluate compliance with PCI DSS, GDPR, and SOC 1/SOC 2
- Recommend improvements to strengthen security posture

The audit followed the **NIST Cybersecurity Framework** (focus on *Identify* function).

## Key Findings
- High risk score (8/10) due to missing critical controls
- Major gaps: Least privilege, encryption, disaster recovery, backups, IDS, strong password management
- Strengths: Firewall, antivirus, physical security (locks, CCTV, fire systems)

## Files in This Repository
- `Control categories.pdf` – Reference for control categories and types
- `Botium Toys_ Scope, goals, and risk assessment report.pdf` – Official scope, assets, and risk assessment
- `Botium Toys_ Audit_WaiLinOo` – **My completed audit checklist** with explanations and recommendations

## Controls Assessment Summary
| Control                        | Status    | Notes |
|-------------------------------|-----------|-------|
| Least Privilege               | No        | All employees access sensitive data |
| Disaster Recovery Plans       | No        | None exist |
| Password Policies             | Partial   | Weak complexity requirements |
| Separation of Duties          | No        | CEO handles operations + payroll |
| Firewall                      | Yes       | Properly configured |
| IDS                           | No        | Not installed |
| Backups                       | No        | No critical data backups |
| Encryption                    | No        | Not used for PII/credit cards |
| Physical Security (Locks/CCTV/Fire) | Yes | Adequate |

## Compliance Gaps
- **PCI DSS**: Missing access controls, encryption, strong passwords
- **GDPR**: Good breach notification plan, but data not fully secured/classified
- **SOC 1/2**: Weak user access and data confidentiality controls

## My Recommendations
Implement least privilege, separation of duties, encryption, disaster recovery plans, backups, IDS, stronger password policies + management system, and regular legacy system maintenance.

## Skills Demonstrated
- Control classification (administrative, technical, physical)
- Risk assessment
- Compliance auditing (PCI DSS, GDPR, SOC)
- Security recommendations

Thanks for visiting! Feel free to connect or ask questions.
