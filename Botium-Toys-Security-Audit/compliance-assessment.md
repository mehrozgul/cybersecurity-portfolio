# Botium Toys Compliance Assessment

## Assessment Objective

The purpose of this assessment is to determine whether Botium Toys currently follows relevant compliance best practices.

The assessment covers:

- Payment Card Industry Data Security Standard (PCI DSS)
- General Data Protection Regulation (GDPR)
- System and Organization Controls (SOC 1 / SOC 2)

---

## PCI DSS

| Best Practice | Status | Reason |
|---|---|---|
| Only authorized users have access to customers' credit card information. | ❌ No | All Botium Toys employees currently have access to internally stored data and may be able to access cardholder data. |
| Credit card information is stored, accepted, processed, and transmitted internally in a secure environment. | ❌ No | Encryption is not currently used to protect customers' credit card information. |
| Implement data encryption procedures to secure credit card transaction touchpoints and data. | ❌ No | Encryption is not currently implemented. |
| Adopt secure password management policies. | ❌ No | The existing password requirements are weak and there is no centralized password management system. |

### PCI DSS Assessment

Botium Toys does not currently meet several important PCI DSS best practices, particularly those related to access control, encryption, and password management.

---

## GDPR

| Best Practice | Status | Reason |
|---|---|---|
| E.U. customers' data is kept private and secure. | ❌ No | Employees may have access to customers' PII/SPII, and important access controls have not been implemented. |
| There is a plan to notify E.U. customers within 72 hours if their data is compromised. | ✅ Yes | Botium Toys has established a plan to notify E.U. customers within 72 hours of a security breach. |
| Ensure data is properly classified and inventoried. | ❌ No | The IT department does not have adequate management and classification of assets and data. |
| Enforce privacy policies, procedures, and processes to properly document and maintain data. | ✅ Yes | Privacy policies, procedures, and processes have been developed and are enforced. |

### GDPR Assessment

Botium Toys has some GDPR-related practices in place, including breach notification and privacy procedures. However, data privacy and data classification require improvement.

---

## SOC 1 / SOC 2

| Best Practice | Status | Reason |
|---|---|---|
| User access policies are established. | ❌ No | Access controls related to least privilege have not been implemented. |
| Sensitive data (PII/SPII) is confidential/private. | ❌ No | All employees may have access to internally stored data, including customers' PII/SPII. |
| Data integrity ensures data is consistent, complete, accurate, and validated. | ✅ Yes | The IT department has implemented controls to ensure data integrity. |
| Data is available to individuals authorized to access it. | ❌ No | Access controls and least privilege have not been implemented. |

### SOC 1 / SOC 2 Assessment

Botium Toys has controls supporting data integrity, but access control and protection of sensitive information need significant improvement.

---

## Overall Compliance Findings

The assessment identified several compliance gaps:

- Excessive access to sensitive information
- Lack of encryption for credit card information
- Weak password requirements
- No centralized password management
- Lack of least privilege
- Inadequate data classification and inventory

## Conclusion

Botium Toys should prioritize access control, encryption, password management, and data classification improvements.

Implementing these controls would help the organization improve its compliance posture and reduce the risk associated with sensitive customer and business data.
