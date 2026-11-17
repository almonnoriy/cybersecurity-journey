# The CIA Triad

## 1. Introduction

The CIA Triad is a fundamental information security model consisting of three core principles: Confidentiality, Integrity, and Availability.

These principles provide a framework for protecting information and ensuring that information systems remain secure and reliable.

The three principles are:

- **Confidentiality:** Protecting information from unauthorised access.
- **Integrity:** Maintaining the accuracy and consistency of information.
- **Availability:** Ensuring information and systems remain accessible when required.

## 2. Confidentiality

### Definition

Confidentiality ensures that sensitive information is accessible only to authorised individuals, systems, or entities.

Its purpose is to prevent unauthorised access, disclosure, or exposure of information.

### Common Threats

- **Phishing:** Deceptive attempts to obtain sensitive information by impersonating trusted sources.
- **Data Breaches:** Incidents involving unauthorised access to or exposure of confidential information.
- **Insider Threats:** Risks caused by individuals within an organisation who misuse their access privileges.
- **Eavesdropping:** Unauthorised interception of private communications.
- **Weak Passwords:** Poor password practices that increase the risk of unauthorised access.

### Security Controls

- **Encryption:** Converts readable information into an encoded format to prevent unauthorised access.
- **Authentication:** Verifies the identity of a user or system.
- **Multi-Factor Authentication (MFA):** Requires multiple verification factors before granting access.
- **Access Control:** Restricts access to resources based on assigned permissions.
- **Principle of Least Privilege:** Ensures users receive only the minimum permissions required to perform their responsibilities.

### Practical Example

A university restricts access to students' personal records so that only authorised administrative staff can view sensitive information. This prevents unauthorised disclosure and protects confidentiality.

## 3. Integrity

### Definition

Integrity ensures that information remains accurate, consistent, and complete throughout its lifecycle.

It protects information against unauthorised modification, deletion, or manipulation.

### Common Threats

- **Unauthorised Modification:** Changes made to information without permission.
- **Malware:** Malicious software capable of altering or damaging information.
- **Human Error:** Accidental modification, deletion, or incorrect data entry.
- **Software Vulnerabilities:** Weaknesses that may allow unauthorised changes to information.
- **Data Corruption:** Damage to information that affects its accuracy or reliability.

### Security Controls

- **Hashing:** Generates a fixed-length value that can be used to verify whether information has changed.
- **Digital Signatures:** Help verify the authenticity and integrity of digital information.
- **Access Control:** Restricts modification permissions to authorised users.
- **Audit Logs:** Maintain records of activities and changes within a system.
- **Version Control:** Tracks changes to files and allows previous versions to be reviewed or restored.

### Practical Example

A university restricts examination-result modification permissions to authorised examination officers and maintains audit logs of changes. This helps prevent unauthorised alterations and preserves the accuracy of academic records.

## 4. Availability

### Definition

Availability ensures that information, applications, and systems remain accessible to authorised users whenever required.

It focuses on maintaining system reliability, operational continuity, and timely access to information.

### Common Threats

- **Denial-of-Service (DoS):** An attack designed to disrupt access to a system or service.
- **Distributed Denial-of-Service (DDoS):** An attack involving multiple sources to overwhelm a target service.
- **Hardware Failure:** Equipment malfunction that interrupts system operations.
- **Power Outages:** Electrical interruptions that affect system availability.
- **Ransomware:** Malicious software that can prevent users from accessing their information.
- **Natural Disasters:** Events that may damage infrastructure and interrupt operations.

### Security Controls

- **Regular Backups:** Maintain copies of important information for recovery.
- **Redundancy:** Provides alternative systems or components when primary resources fail.
- **Disaster Recovery Planning:** Establishes procedures for restoring systems and information after disruptions.
- **System Monitoring:** Helps identify failures and service interruptions.
- **Uninterruptible Power Supply (UPS):** Provides temporary electrical power during power interruptions.
- **Business Continuity Planning:** Helps organisations maintain essential operations during disruptions.

### Practical Example

A university maintains backup copies of student records and alternative systems to support the restoration of essential academic services during technical failures. This helps maintain availability.

## 5. Application of the CIA Triad

The CIA Triad can be applied to different information assets within an organisation.

| Information Asset | Confidentiality | Integrity | Availability |
|---|---|---|---|
| Student Records | Restrict access to authorised staff | Prevent unauthorised modifications | Ensure records are accessible when required |
| Examination Results | Limit access to authorised personnel | Protect grades from manipulation | Make results accessible when officially released |
| Financial Records | Restrict access to authorised finance personnel | Maintain accurate transaction records | Ensure authorised access to financial systems |
| Learning Management System | Protect user accounts and credentials | Preserve academic records and course materials | Maintain platform accessibility |
| University Network | Prevent unauthorised network access | Protect network configurations | Maintain reliable connectivity |

The three principles work together to protect organisational information assets. A weakness in one area can affect the overall security of a system.

## 6. Important Technical Terminology

| Term | Description |
|---|---|
| Encryption | Converts readable information into an encoded format. |
| Hashing | Generates a fixed-length value used to verify data integrity. |
| Authentication | Verifies the identity of a user or system. |
| Authorisation | Determines what an authenticated user is permitted to access. |
| Multi-Factor Authentication (MFA) | Uses multiple verification factors to establish identity. |
| Access Control | Regulates access to information and resources. |
| Audit Logs | Record activities and events within a system. |
| Redundancy | Provides alternative components to support continuity. |
| Backup | A copy of information maintained for recovery. |
| Disaster Recovery | Procedures for restoring systems after disruptions. |
| DoS | Denial-of-Service. |
| DDoS | Distributed Denial-of-Service. |

## 7. Key Takeaways

- Confidentiality protects information against unauthorised access and disclosure.
- Integrity ensures information remains accurate, complete, and trustworthy.
- Availability ensures authorised users can access information and services when needed.
- Encryption, authentication, and access control help maintain confidentiality.
- Hashing, digital signatures, and audit logs help maintain integrity.
- Backups, redundancy, and disaster recovery planning support availability.
- Effective information security requires balancing all three principles.

## 8. Conclusion

The CIA Triad provides a foundation for understanding information security and protecting organisational information assets.

Confidentiality, Integrity, and Availability address different security requirements but work together to maintain the protection, reliability, and accessibility of information systems.
