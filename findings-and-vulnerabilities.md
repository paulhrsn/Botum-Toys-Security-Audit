# Findings and Vulnerabilities – Botium Toys

This file outlines weaknesses discovered during the internal audit of Botium Toys' IT infrastructure and compliance posture.

## Missing or Weak Controls

- **Least Privilege & Access Control**
  - All employees have comprehensive access to sensitive data such customer credit card info. This creates unnecessary exposure.
  
- **Disaster Recovery**
  - No disaster recovery plan exists. This makes Botium very vulnerable in the event of a breach or major outage.

- **Password Security**
  - While a basic password policy exists, it lacks important, modern requirements like complexity and length. There is also no centralized password management system in place to enforce any kind of policy.

- **Separation of Duties**
  - Important roles and responsibilities aren't distributed across personnel, which increases the risk of internal fraud or misuse.

- **Intrusion Detection System (IDS)**
  - There is no IDS in place to flag unusual or potentially malicious activity on the network.

- **Backups**
  - No backup process is implemented for critical business data, meaning operations are at risk of significant or even total data loss.

- **Legacy System Oversight**
  - Legacy systems are being monitored but without a defined schedule or outlined intervention procedures, potentially leading to overlooked vulnerabilities.

- **Encryption**
  - Customer data such as payment information is stored and transmitted without any encryption. This is a very serious compliance and confidentiality issue.

## Compliance Gaps

- **PCI DSS Noncompliance**
  - Credit card data is not encrypted and access is not restricted to authorized staff.
  - Secure password policies and management tools are not fully implemented.

- **GDPR Weaknesses**
  - E.U. customer data is not fully secured.
  - Data classification is not in place, making it hard to enforce data handling standards.

- **SOC 2 Weaknesses**
  - User access policies are not defined, and sensitive data is not properly protected or limited to authorized personnel.


