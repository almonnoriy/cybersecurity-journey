# Module 02: The Cyber Kill Chain

**Learning Path:** Hackviser Core – Cybersecurity Fundamentals  

**Framework:** Lockheed Martin Cyber Kill Chain

---

## Table of Contents

1. Introduction to the Cyber Kill Chain
2. The Seven Stages of the Cyber Kill Chain
   - Reconnaissance
   - Weaponization
   - Delivery
   - Exploitation
   - Installation
   - Command and Control
   - Actions on Objectives
3. Summary of the Seven Stages
4. Importance to Cybersecurity Professionals
5. Application to Penetration Testing
6. Limitations of the Framework
7. Conclusion

---

## 1. Introduction to the Cyber Kill Chain

The Cyber Kill Chain is a cybersecurity framework developed by Lockheed Martin to explain the different stages that may occur during a cyberattack.

The framework provides a structured way to understand how attackers approach their targets, from gathering initial information to attempting to achieve their final objectives.

It is useful to cybersecurity professionals because it helps them identify suspicious activities, understand potential attack patterns and determine where defensive measures can interrupt an attack.

The original Cyber Kill Chain consists of seven stages:

1. Reconnaissance
2. Weaponization
3. Delivery
4. Exploitation
5. Installation
6. Command and Control (C2)
7. Actions on Objectives

Each stage represents a different part of a potential attack. However, not every cyberattack follows all seven stages in exactly the same order.

## 2. The Seven Stages of the Cyber Kill Chain

### 2.1 Reconnaissance

**Definition**

Reconnaissance is the information-gathering stage of the Cyber Kill Chain. During this stage, an attacker attempts to learn about a potential target before proceeding with other activities.

The information gathered may help identify the target's digital environment, technologies, publicly exposed resources and possible security weaknesses.

**Types of Reconnaissance**

Reconnaissance is commonly divided into two categories:

**Passive Reconnaissance**

Passive reconnaissance involves collecting information from publicly available sources without directly interacting with the target's systems.

Common sources include:

- Search engines.
- Public DNS records.
- WHOIS records.
- Company websites.
- Social media platforms.
- Public security reports.
- Online information databases.

Two tools associated with reconnaissance include:

**theHarvester**

theHarvester is an open-source tool used to collect publicly available information about an organisation's digital footprint. Depending on its supported sources, it can help identify email addresses, subdomains, hostnames and related information.

**Shodan**

Shodan is a search engine for internet-connected devices and services. It provides information about exposed systems, service banners, ports and technologies.

Organisations can use Shodan to review their own internet-facing infrastructure and identify unnecessary exposure.

**Active Reconnaissance**

Active reconnaissance involves directly interacting with a target's systems or network infrastructure to gather technical information.

Activities associated with this category include:

- Network discovery.
- Port and service identification.
- Operating system identification.
- Web resource discovery.
- Network security assessment.

Examples of tools used by security professionals include:

**Nmap**

Nmap, also known as Network Mapper, is an open-source network discovery and security auditing tool. It helps identify active hosts, network services and other technical characteristics of systems.

**Gobuster**

Gobuster is a command-line tool used in authorised security assessments to identify directories and files that may be accessible on a web server.

**Passive and Active Reconnaissance: Key Difference**

Passive reconnaissance relies on information gathered indirectly from available sources, while active reconnaissance involves direct interaction with the target environment.

**Security Consideration:** Active reconnaissance should only be conducted against systems that you own or have explicit permission to assess.

### 2.2 Weaponization

**Definition**

Weaponization is the stage where an attacker prepares a malicious component by combining an exploit with a payload for a particular attack scenario.

Information collected during reconnaissance may influence the attacker's choice of approach.

The purpose of this stage is to prepare the component that may later be delivered to the target.

**Important Terminology**

**Exploit**

An exploit is a technique, method or piece of code that takes advantage of a vulnerability in software, hardware or a system.

**Payload**

A payload is the component designed to perform a particular action after an exploit has been successful. Its intended behaviour depends on the nature of the attack.

**Vulnerability**

A vulnerability is a weakness in software, hardware, system configuration or design that could affect the security of a system.

**Common Vulnerability Categories**

- **Operating System and Service Vulnerabilities:** Weaknesses affecting operating systems or network services.
- **Web Application Vulnerabilities:** Weaknesses in web applications, including improper input handling and broken access controls.
- **Network Vulnerabilities:** Weaknesses in network architecture, configurations or communication protocols.
- **Memory Corruption Vulnerabilities:** Programming errors that affect how applications manage memory.
- **Input Validation Vulnerabilities:** Weaknesses that occur when applications fail to handle user-supplied information safely.

**Security Importance**

Understanding weaponization helps defenders recognise how information about vulnerabilities may be used to prepare an attack. It also highlights the importance of vulnerability management, secure development and timely security updates.

### 2.3 Delivery

**Definition**

Delivery is the stage in which an attacker attempts to introduce a prepared malicious component into the target environment.

It represents the point at which the attack reaches its intended recipient or system.

**Common Delivery Methods**

- **Email Phishing:** Deceptive messages may be used to persuade recipients to interact with malicious links or attachments.
- **Compromised Websites:** Websites that have been compromised may expose visitors to malicious content.
- **Removable Media:** Untrusted USB drives and other removable storage devices may introduce malicious files into an organisation.

File formats that may be abused during delivery include office documents, PDF files, executable files and scripts.

**Security Importance**

Organisations can reduce delivery-related risks through:

- Email security and filtering.
- Endpoint protection.
- User awareness training.
- Application control policies.
- Restrictions on untrusted removable media.

### 2.4 Exploitation

**Definition**

Exploitation is the stage in which an attacker attempts to take advantage of a vulnerability in the target system.

If successful, exploitation may result in unauthorised access, unexpected application behaviour or the execution of unauthorised code.

The outcome depends on the vulnerability involved, the system configuration and the security controls in place.

**Common Areas of Exploitation**

- Operating system vulnerabilities.
- Web application vulnerabilities.
- Network service vulnerabilities.
- Memory corruption vulnerabilities.
- Improper input validation.

**Security Importance**

Defensive measures that help reduce exploitation risks include:

- Regular security patching.
- Vulnerability assessments.
- Secure software development.
- Appropriate system configurations.
- Endpoint and network monitoring.

### 2.5 Installation

**Definition**

Installation is the stage where an attacker attempts to establish a presence within a compromised system.

This may involve introducing malicious software or creating mechanisms that allow unauthorised access to continue.

One important concept associated with this stage is persistence.

**What Is Persistence?**

Persistence refers to methods that allow unauthorised access or activity to remain available within a system over time, including after certain events such as a restart or user logout.

**Examples of Areas That Require Monitoring**

- Windows startup locations and registry settings.
- Scheduled tasks.
- System services.
- Unexpected changes to web server directories.
- Unusual software installations.

These system components have legitimate administrative purposes, but unauthorised changes to them may indicate suspicious activity.

**Security Importance**

Security teams can monitor system configurations, startup activities, scheduled tasks and unexpected software changes to identify possible persistence attempts.

### 2.6 Command and Control (C2)

**Definition**

Command and Control, commonly abbreviated as C2, is the stage where an attacker establishes communication with a compromised system to send instructions or receive information.

This communication may allow an attacker to manage activities involving the compromised system.

**Common Communication Channels**

**HTTP and HTTPS**

Web communication protocols may be abused to exchange information between compromised systems and external infrastructure.

**DNS Tunneling**

DNS tunneling is a technique that uses DNS queries and responses to carry information. It can also be abused to conceal unauthorised communication within DNS traffic.

**Security Importance**

Monitoring network communication can help organisations identify suspicious connections and unusual traffic patterns.

Defensive measures include:

- Network traffic monitoring.
- DNS monitoring.
- Firewall rules.
- Intrusion Detection Systems (IDS).
- Intrusion Prevention Systems (IPS).
- Endpoint Detection and Response (EDR).

### 2.7 Actions on Objectives

**Definition**

Actions on Objectives is the final named stage of the original Cyber Kill Chain.

At this point, the attacker attempts to achieve the intended goal of the operation. The objective may vary depending on the attacker's motivation and the target environment.

**Common Actions on Objectives**

**Data Exfiltration**

Data exfiltration refers to the unauthorised transfer of information from a system or organisation to an external destination.

**Data Encryption**

An attacker may encrypt an organisation's files to prevent legitimate users from accessing them. This behaviour is commonly associated with ransomware incidents.

**Data Destruction and Sabotage**

This involves attempts to destroy, modify or disrupt information, applications or computer systems.

**Resource Hijacking**

An attacker may misuse compromised computing resources for unauthorised activities, including cryptocurrency mining.

**Lateral Movement**

Lateral movement refers to activity in which an attacker moves from one compromised system to another within an environment.

It is a post-compromise activity that may help an attacker reach additional systems or valuable resources. It is not one of the seven named stages of the original Cyber Kill Chain.

**Security Importance**

Organisations can reduce the impact of these activities through:

- Data Loss Prevention (DLP).
- Regular and protected backups.
- Encryption.
- Access controls.
- Network segmentation.
- Security monitoring.
- Incident response procedures.

## 3. Summary of the Seven Cyber Kill Chain Stages

| Stage | Main Activity |
|---|---|
| 1. Reconnaissance | Gathering information about a potential target. |
| 2. Weaponization | Preparing an exploit and payload. |
| 3. Delivery | Introducing the prepared component to the target. |
| 4. Exploitation | Attempting to take advantage of a vulnerability. |
| 5. Installation | Establishing a presence or persistence within a system. |
| 6. Command and Control | Communicating with compromised systems. |
| 7. Actions on Objectives | Attempting to achieve the attacker's intended goal. |

## 4. Importance of the Cyber Kill Chain to Cybersecurity Professionals

The Cyber Kill Chain gives cybersecurity professionals a structured way to examine how an attack may develop.

Its practical value includes:

1. **Understanding attack progression:** It helps explain how different activities may be connected during a cyberattack.
2. **Threat identification:** It provides a framework for recognising suspicious activities at different stages.
3. **Security monitoring:** It helps security teams determine where monitoring and detection controls may be useful.
4. **Defensive planning:** It supports the selection of security measures designed to prevent or disrupt attacks.
5. **Incident response:** It can help analysts organise their understanding of an incident and its possible progression.
6. **Risk reduction:** It highlights opportunities to address weaknesses before they lead to serious security incidents.

## 5. Application to Penetration Testing

The Cyber Kill Chain is also relevant to penetration testing because it provides a way to understand the relationship between different stages of an attack.

For example, a penetration tester conducting an authorised assessment may examine publicly exposed information, identify potential weaknesses and evaluate the effectiveness of an organisation's security controls.

The framework helps provide context for these activities and explains how different security weaknesses may relate to one another.

All penetration-testing activities must remain within an agreed and authorised scope.

## 6. Limitations of the Cyber Kill Chain

Although the Cyber Kill Chain is useful, it does not represent every possible cyberattack.

Some of its limitations include:

- Not every attack follows all seven stages.
- Some attacks may skip certain stages.
- Modern attacks may involve several techniques at the same time.
- Activities may occur repeatedly or overlap.
- The framework does not describe every detail of modern attacker behaviour.

For these reasons, the Cyber Kill Chain is best used alongside other cybersecurity frameworks and analysis methods.

## 7. Conclusion

The Cyber Kill Chain provides a structured way to understand how cyberattacks may progress, from initial information gathering to the attempt to achieve an attacker's objectives.

Understanding its seven stages helps cybersecurity professionals recognise suspicious activities, examine potential weaknesses and identify opportunities to prevent or disrupt malicious operations.

The framework also highlights the importance of combining technical safeguards, security monitoring, vulnerability management and incident response.

A good understanding of the Cyber Kill Chain provides a foundation for further learning in threat intelligence, penetration testing, vulnerability management and incident response.

---

**Reference Framework:** Lockheed Martin Cyber Kill Chain  
**Learning Area:** Cybersecurity Fundamentals  
**Primary Focus:** Understanding the stages of cyberattacks  
**Practical Focus:** Security analysis and defensive monitoring in authorised environments
