# Module 05: Types of Cyberattacks

---

## Table of Contents

1. Introduction
2. Common Types of Cyberattacks
3. Relationship Between Cyberattacks and the CIA Triad
4. Security Measures Against Cyberattacks
5. Practical Case Study: Phishing Attack Against a University
6. Important Technical Terminology
7. Conclusion

---

## 1. Introduction

A cyberattack is a deliberate attempt to gain unauthorised access to, disrupt, damage, manipulate, or steal information from computer systems, networks, applications, or digital devices.

These attacks affect individuals, businesses, educational institutions, government organisations, and critical infrastructure. Their consequences may include financial losses, exposure of sensitive information, service disruption, and damage to an organisation's reputation.

Cyberattacks can take different forms. Some target technical weaknesses in software and networks, while others exploit human behaviour, trust, and poor security practices.

Understanding common attack methods is important for recognising security threats, identifying weaknesses, and selecting appropriate defensive measures.

## 2. Common Types of Cyberattacks

### 2.1 Phishing Attacks

**Definition**

Phishing is a social engineering technique in which an attacker impersonates a trusted individual or organisation to deceive someone into revealing sensitive information or performing an action that could compromise security.

**Common Characteristics**

- Fraudulent emails, text messages, or other communications.
- Impersonation of legitimate organisations.
- Suspicious links and attachments.
- Requests for passwords or personal information.
- Urgent messages designed to influence decision-making.

**Example**

A university student receives an email that appears to come from the university's IT department. The message asks the student to verify their account through an unfamiliar website.

**Potential Impact**

- Credential theft.
- Unauthorised account access.
- Identity theft.
- Exposure of confidential information.

**Defensive Measures**

- Verify the identity of senders before responding.
- Avoid suspicious links and attachments.
- Enable Multi-Factor Authentication (MFA).
- Use appropriate email security controls.
- Report suspicious messages.

### 2.2 Malware Attacks

**Definition**

Malware, short for malicious software, refers to software intentionally designed to damage systems, disrupt operations, steal information, or perform unauthorised activities.

**Major Types of Malware**

| Malware Type | Description |
|---|---|
| Virus | Malicious code that attaches itself to files or programs and spreads when they are executed. |
| Worm | Malware capable of spreading between systems without requiring a host file. |
| Trojan Horse | Malicious software disguised as legitimate software. |
| Spyware | Software designed to secretly monitor activities or collect information. |
| Adware | Software that displays unwanted advertisements; some forms also track user activity. |
| Rootkit | Software designed to conceal malicious activity and maintain privileged access. |
| Keylogger | Software or hardware that records keyboard input. |
| Ransomware | Malware that restricts access to information or systems and demands payment. |

**Potential Impact**

- Data theft.
- System damage.
- Unauthorised access.
- Loss of productivity.
- Disruption of organisational operations.

**Defensive Measures**

- Install reputable endpoint protection software.
- Keep operating systems and applications updated.
- Download software from trusted sources.
- Maintain regular backups.
- Apply appropriate access controls.

### 2.3 Ransomware Attacks

**Definition**

Ransomware is a type of malware that prevents users from accessing their information or systems, commonly through encryption, and demands payment for restoration.

Some ransomware operations also involve stealing information and threatening to disclose it.

**Potential Impact**

- Loss of access to important files.
- Business interruption.
- Financial losses.
- Exposure of confidential information.
- Reputational damage.

**Defensive Measures**

- Maintain regular and protected backups.
- Apply security updates.
- Use endpoint detection and protection solutions.
- Train employees to recognise suspicious communications.
- Establish an incident response plan.

### 2.4 Denial-of-Service (DoS) Attacks

**Definition**

A Denial-of-Service attack is an attempt to make a computer system, website, or network service unavailable to legitimate users.

It commonly involves overwhelming a service or exploiting a weakness that prevents the service from responding normally.

**Example**

An online university registration portal becomes unavailable because it is receiving an unusually high volume of malicious requests.

**Primary Security Impact**

Availability.

**Defensive Measures**

- Network traffic monitoring.
- Rate limiting.
- Traffic filtering.
- DDoS protection services.
- Incident response procedures.

### 2.5 Distributed Denial-of-Service (DDoS) Attacks

**Definition**

A Distributed Denial-of-Service attack is a form of DoS attack in which multiple sources target a system or service simultaneously, potentially overwhelming its available resources.

**Difference Between DoS and DDoS**

| DoS | DDoS |
|---|---|
| Typically originates from one source. | Involves multiple sources. |
| More centralised. | Distributed across multiple systems. |
| May be easier to isolate by source. | Requires broader traffic analysis and mitigation. |

**Potential Impact**

- Website unavailability.
- Service interruptions.
- Financial losses.
- Operational disruption.

**Defensive Measures**

- DDoS mitigation services.
- Network monitoring.
- Traffic filtering.
- Rate limiting.
- Infrastructure redundancy.

### 2.6 Man-in-the-Middle (MitM) Attacks

**Definition**

A Man-in-the-Middle attack occurs when an attacker secretly intercepts or potentially alters communication between two parties who believe they are communicating directly.

**Example**

A user connects to an untrusted network and communicates through an inadequately protected connection. An attacker may be able to intercept that communication.

**Potential Impact**

- Exposure of sensitive information.
- Theft of authentication information.
- Communication manipulation.
- Loss of confidentiality and integrity.

**Defensive Measures**

- Use HTTPS.
- Apply strong encryption.
- Avoid untrusted networks for sensitive activities.
- Verify secure connections.
- Use properly configured network security controls.

### 2.7 SQL Injection (SQLi)

**Definition**

SQL Injection is an attack technique that takes advantage of a web application vulnerability where untrusted input is improperly handled and becomes part of a database query.

Depending on the vulnerability and database permissions, this may allow unauthorised database access, modification, or deletion.

**Example**

An online application fails to handle user input securely in its database queries, potentially exposing information stored in the database.

**Potential Impact**

- Unauthorised database access.
- Exposure of sensitive records.
- Data manipulation.
- Data deletion.

**Defensive Measures**

- Use parameterised queries.
- Validate input appropriately.
- Apply least-privilege database permissions.
- Follow secure coding practices.
- Conduct authorised application security testing.

### 2.8 Cross-Site Scripting (XSS)

**Definition**

Cross-Site Scripting is a web application vulnerability that allows malicious scripts to execute in another user's browser because the application handles untrusted content insecurely.

**Major Types of XSS**

| Type | Description |
|---|---|
| Stored XSS | Malicious content is stored by an application and later delivered to users. |
| Reflected XSS | Malicious input is reflected in an immediate server response. |
| DOM-Based XSS | Unsafe client-side JavaScript handling causes malicious content to execute in the browser. |

**Potential Impact**

- Unauthorised actions within a user's browser context.
- Exposure of sensitive information.
- Session-related security risks.
- Compromised user experience.

**Defensive Measures**

- Context-aware output encoding.
- Input validation.
- Content Security Policy (CSP).
- Secure JavaScript practices.
- Appropriate security testing.

### 2.9 Password-Based Attacks

**Definition**

Password-based attacks target passwords or authentication mechanisms in an attempt to gain unauthorised access to user accounts or systems.

**Common Types**

| Attack | Description |
|---|---|
| Brute Force | Attempts multiple possible passwords. |
| Dictionary Attack | Uses commonly known words and passwords as guesses. |
| Credential Stuffing | Attempts previously exposed username and password combinations on other services. |
| Password Spraying | Attempts a small number of common passwords across multiple accounts. |
| Shoulder Surfing | Obtains authentication information by observing someone entering it. |

**Defensive Measures**

- Use strong and unique passwords.
- Enable Multi-Factor Authentication.
- Apply login attempt monitoring and throttling.
- Use password managers.
- Avoid password reuse.

### 2.10 Social Engineering Attacks

**Definition**

Social engineering is the manipulation of individuals into revealing sensitive information, granting access, or performing actions that compromise security.

Unlike attacks that rely primarily on technical weaknesses, social engineering exploits human trust, behaviour, and decision-making.

**Common Techniques**

| Technique | Description |
|---|---|
| Pretexting | Creating a fabricated situation to gain someone's trust. |
| Baiting | Using an attractive offer or object to encourage unsafe behaviour. |
| Tailgating | Following an authorised individual into a restricted physical area without permission. |
| Quid Pro Quo | Offering a supposed benefit in exchange for information or access. |
| Impersonation | Pretending to be a trusted individual or authority. |

**Defensive Measures**

- Cybersecurity awareness training.
- Identity verification procedures.
- Physical access controls.
- Reporting suspicious requests.
- Clear organisational security policies.

---

## 3. Relationship Between Cyberattacks and the CIA Triad

Cyberattacks can affect one or more principles of the CIA Triad: Confidentiality, Integrity, and Availability.

| Cyberattack | Confidentiality | Integrity | Availability |
|---|---|---|---|
| Phishing | May be affected | May be affected | May be affected |
| Malware | May be affected | May be affected | May be affected |
| Ransomware | May be affected | May be affected | Frequently affected |
| DoS | Usually indirect | Usually indirect | Frequently affected |
| DDoS | Usually indirect | Usually indirect | Frequently affected |
| MitM | May be affected | May be affected | May be affected |
| SQL Injection | May be affected | May be affected | May be affected |
| XSS | May be affected | May be affected | May be affected |
| Password Attacks | May be affected | May be affected | May be affected |

The actual impact depends on the attack method, the target system, the attacker's access, and the security controls in place.

## 4. Security Measures Against Cyberattacks

Organisations use multiple layers of security to prevent, detect, and respond to cyberattacks. These measures work together to protect information systems and reduce the likelihood and impact of security incidents.

### 4.1 Firewalls

Firewalls monitor and control network traffic according to established security rules.

### 4.2 Antivirus and Endpoint Protection

These solutions help identify, prevent, and respond to malicious software and suspicious activities on devices.

### 4.3 Encryption

Encryption protects information by converting readable data into an encoded format that requires the appropriate key for access.

### 4.4 Multi-Factor Authentication (MFA)

MFA strengthens account security by requiring multiple verification factors before access is granted.

### 4.5 Security Awareness Training

Security awareness training educates employees and users about phishing, social engineering, password security, and other common threats.

### 4.6 Patch Management

Patch management ensures that operating systems, applications, and other software receive relevant security updates.

### 4.7 Data Backups

Backups maintain recoverable copies of important information in case of data loss, system failure, or security incidents.

### 4.8 Intrusion Detection Systems (IDS)

IDS solutions monitor network or system activities to identify suspicious behaviour and possible security incidents.

### 4.9 Intrusion Prevention Systems (IPS)

IPS solutions monitor activities and can attempt to block detected malicious traffic or behaviour.

### 4.10 Access Control

Access control restricts access to information and resources according to assigned permissions and responsibilities.

---

## 5. Practical Case Study: Phishing Attack Against a University

### Scenario

A university receives reports of students losing access to their online accounts.

An investigation reveals that several students received fraudulent messages impersonating the university's IT department. The messages requested account verification through an unauthorised website.

### Security Analysis

| Element | Finding |
|---|---|
| Attack Type | Phishing |
| Threat Actor | An individual attempting to obtain student credentials |
| Vulnerability | Insufficient security awareness and compromised credentials |
| Target | Student accounts |
| Potential Impact | Unauthorised access to academic information |
| CIA Principle | Primarily Confidentiality |
| Recommended Controls | MFA, security awareness training, account monitoring, and phishing reporting |

### Analysis

This scenario demonstrates how human behaviour can become a significant security weakness. Even when an organisation has technical security controls, users who are deceived into disclosing their credentials may expose organisational systems to additional risks.

It also highlights the importance of combining user awareness with technical protections such as MFA, access controls, and account monitoring.

---

## 6. Important Technical Terminology

| Term | Meaning |
|---|---|
| Malware | Malicious software. |
| Phishing | Deceptive communication intended to obtain information or influence actions. |
| Ransomware | Malware that restricts access to information or systems and demands payment. |
| DoS | Denial-of-Service. |
| DDoS | Distributed Denial-of-Service. |
| MitM | Man-in-the-Middle. |
| SQLi | SQL Injection. |
| XSS | Cross-Site Scripting. |
| IDS | Intrusion Detection System. |
| IPS | Intrusion Prevention System. |
| MFA | Multi-Factor Authentication. |
| CSP | Content Security Policy. |
| Social Engineering | Manipulation of people to compromise security. |

---

## 7. Conclusion

Understanding the different types of cyberattacks is an important part of cybersecurity. Each attack method has its own characteristics, targets, and potential consequences.

Cybersecurity professionals need to recognise how these attacks occur, understand the weaknesses they take advantage of, and identify suitable measures for reducing their impact.

Effective protection requires more than a single security solution. It involves technical safeguards, secure configurations, organisational policies, user awareness, and continuous monitoring.

Knowledge of these attacks provides a foundation for further studies in vulnerability assessment, penetration testing, web application security, network defence, and incident response.
