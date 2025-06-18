Please note: Recommendations & outlined vulnerabiltiies are not found in this file, but rather in "recommendations.md" and "findings-and-vulnerabilities.md" respectively.

##Summarized additional information

-Scope: Entire security program @ Botium Tyos. Assets, equipment, devices, internal network, systems.

-Goals: Assess these assets & complete checklists to determine practices that need to be implemented
to improve security posture.

-List of current assets (comprehensive, but potentially non-exhaustive): 

On-premises office equipment, employee end-user devices (desktops, laptops, smartphones, headsets, cables, keyboards, mice, docking stations, surveillance cameras), storefront and warehouse products, systems and software for accounting, telecom, databases, security, e-commerce, inventory management, internet access, internal network, data retention and storage, legacy system maintenance.

For all tables below, where applicable, a "*" marks that there is a relevant note for that row,
and the corresponding note can be found the table which that row belongs to.

### ✅ Controls Assessment Checklist

| Control                                                                 | Yes ✅ | No ❌ |
|-------------------------------------------------------------------------|--------|-------|
| Least Privilege                                                         |        |  ❌   |
| Disaster Recovery Plans                                                 |        |  ❌   |
| Password Policies*                                                      |        |  ❌   |
| Separation of Duties                                                    |        |  ❌   |
| Firewall                                                                |  ✅    |       |
| Intrusion Detection System (IDS)                                        |        |  ❌   |
| Backups                                                                 |        |  ❌   |
| Antivirus Software                                                      |  ✅    |       |
| Manual Monitoring, Maintenance, and Intervention for Legacy Systems*    |        |  ❌    |
| Encryption                                                              |        |  ❌   |
| Password Management System                                              |        |  ❌   |
| Locks (offices, storefront, warehouse)                                  |  ✅    |       |
| Closed-Circuit Television (CCTV) Surveillance                           |  ✅    |       |
| Fire Detection/Prevention (e.g. fire alarm, sprinkler system, etc.)     |  ✅    |       |
-------------------------------------------------------------------------------------------
Important notes:

*While password policies are in place, they are insufficient and must me ameliorated.

*While Legacy systems are being maintained, they lack a formal schedule or clear intervention
protocol, which is likely to result in delays and/or oversight.




### 📋 Compliance Checklists

#### 📦 Payment Card Industry Data Security Standard (PCI DSS)

| Best Practice                                                                 | Yes ✅ | No ❌ |
|------------------------------------------------------------------------------|--------|-------|
| Only authorized users have access to customers’ credit card info             |        |  ❌   |
| Credit card data is securely stored, accepted, processed, and transmitted    |        |  ❌   |
| Data encryption procedures are implemented                                   |        |  ❌   |
| Secure password management policies are adopted*                             |        |  ❌   |
-------------------------------------------------------------------------------------------------
Important note:

*Again: there *are some* password policies in place, but they are relatively insecure and the management system is non-existent.


#### 🇪🇺 General Data Protection Regulation (GDPR)

| Best Practice                                                                | Yes ✅ | No ❌ |
|-----------------------------------------------------------------------------|--------|-------|
| E.U. customer data is kept private/secured                                  |   ✅   |       |
| There is a breach notification plan for E.U. customers (within 72 hours)    |   ✅   |       |
| Data is properly classified and inventoried*                                |        |  ❌   |
| Privacy policies/procedures are enforced                                    |   ✅   |       |

#### 🏢 System and Organization Controls (SOC 1 / SOC 2)

| Best Practice                                                                | Yes ✅ | No ❌ |
|-----------------------------------------------------------------------------|--------|-------|
| User access policies are established                                        |        |  ❌   |
| Sensitive data (PII/SPII) is protected and private                          |        |  ❌   |
| Data integrity is ensured (complete, accurate, validated)                   |   ✅   |       |
| Data availability is guaranteed to authorized individuals*                  |        |  ❌   |
-------------------------------------------------------------------------------------------------
Important note:

*While data is available to *all* employees, authorization has to now be limited to only individuals
who need access to perform their duties.


