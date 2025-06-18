
# Recommendations for Botium Toys

Based on the audit findings, here are curated recommendations to strengthen Botium Toys’ cybersecurity posture and compliance with both national and international standards.

## Controls to Implement or Improve

- **Limit Access to employees (Least Privilege)**
  - Review & reduce unnecessary employee access to sensitive systems and customer data.
  - Enforce role-based permissions - employees should have the least amount of priveleges needed to complete their duties. 

- **Build a Disaster Recovery Plan**
  - Outline how operations should recover from major incidents.
  - Involve data backups, timelines, and in-depth testing procedures.

- **Strengthen Password Practices**
  - Update the password policy to require longer and more complex passwords.
  - Implement a password manager to enforce and automate these standards.

- **Separate Duties**
  - Assign critical responsibilities such as finance, HR, system admin, etc. to different individuals to reduce insider risks.

- **Deploy an IDS**
  - Install and configure an intrusion detection system to monitor traffic and alert IT to suspicious behavior.

- **Implement Regular Backups**
  - Back up critical data to an offsite (or potentially cloud) location regularly.

- **Formalize Legacy System Maintenance**
  - Create a maintenance and response plan for older systems to make sure they don’t become entry points for attackers.

- **Use Encryption**
  - Encrypt customer data at all points, especially financial information or sensitive information like PII/SPII.

## 📋 Compliance Improvements

- **PCI DSS**
  - Encrypt all cardholder data.
  - Limit credit card data access to authorized staff only (see Limit Access to employees (Least Privilege).
  - Make sure password policies meet PCI standards.

- **GDPR**
  - Classify or encrypt customer data and apply handling rules.
  - Conduct regular training and reviews to ensure ongoing data protection.

- **SOC 2**
  - Document and enforce access policies.
  - Improve safeguards for sensitive data integrity and availability.
