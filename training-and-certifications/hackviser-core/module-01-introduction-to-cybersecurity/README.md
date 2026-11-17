# Module 1: Introduction to Cybersecurity

> Study notes from Module 1 of the Hackviser cybersecurity course.

> *"To be a hacker is to bring the impossible within reach through unexpected behavior."*

---

## Table of Contents

1. [Information Security](#1-information-security)
2. [The CIA Triad](#2-the-cia-triad)
3. [Reverse Engineering](#3-reverse-engineering)
4. [Cloud Security and IAM](#4-cloud-security-and-iam)
5. [Security Frameworks and Methodologies](#5-security-frameworks-and-methodologies)
6. [Ports](#6-ports)
7. [Vulnerability Terminology](#7-vulnerability-terminology)
8. [Shells](#8-shells)
9. [IP Addressing: IPv4 and IPv6](#9-ip-addressing-ipv4-and-ipv6)
10. [Quick Reference](#10-quick-reference)

---

## 1. Information Security

**Information Security** is the practice of protecting information against unauthorised use, disclosure, destruction, damage and access.

It covers the protection of both physical documents and electronic data.

---

## 2. The CIA Triad

The CIA Triad represents three fundamental principles of information security.

| Principle | Meaning |
|---|---|
| **Confidentiality** | Ensures information is accessible only to authorised individuals. |
| **Integrity** | Ensures information remains accurate and protected against unauthorised or accidental alteration. |
| **Availability** | Ensures information is accessible to authorised users whenever it is needed. |

---

## 3. Reverse Engineering

**Reverse Engineering** involves analysing software, devices or systems to understand how they work.

One application of reverse engineering is malware analysis, where security professionals examine suspicious software to understand its behaviour.

---

## 4. Cloud Security and IAM

**Cloud Security** involves protecting cloud-based infrastructure, applications, services and data.

**IAM (Identity and Access Management)** is used to manage digital identities and control who can access specific systems and resources.

---

## 5. Security Frameworks and Methodologies

Security frameworks and methodologies provide structured approaches to identifying, assessing and managing security risks.

### 5.1 OWASP

**OWASP (Open Web Application Security Project)** provides resources and guidance for identifying, assessing and mitigating security risks in web applications and services.

### 5.2 OSSTMM

**OSSTMM (Open Source Security Testing Methodology Manual)** provides a methodology for conducting information security testing.

### 5.3 NIST

**NIST (National Institute of Standards and Technology)** is a standards organisation that publishes widely used cybersecurity standards, guidelines and recommendations.

---

## 6. Ports

**Ports** are communication endpoints used by applications and services to exchange data between computers and other devices.

### 6.1 Physical Ports

Physical ports are hardware connection points found on computers and other devices.

Example: USB ports.

### 6.2 Virtual (Logical) Ports

Logical ports are numbered communication endpoints used by network applications and services.

Port numbers range from **0 to 65535**.

### 6.3 Common Ports and Services

| Port | Service / Protocol |
|---|---|
| 21 | FTP |
| 22 | SSH |
| 23 | Telnet |
| 25 | SMTP |
| 53 | DNS |
| 80 | HTTP |
| 443 | HTTPS |
| 3306 | MySQL |
| 3389 | RDP |
| 5432 | PostgreSQL |

---

## 7. Vulnerability Terminology

### 7.1 OWASP Top 10

The OWASP Top 10 is a widely recognised awareness document highlighting major security risks affecting web applications.

### 7.2 CVE

**CVE (Common Vulnerabilities and Exposures)** is a system used to identify and catalogue publicly known cybersecurity vulnerabilities.

### 7.3 CVSS

**CVSS (Common Vulnerability Scoring System)** is a framework used to assess and communicate the severity of security vulnerabilities.

### 7.4 PoC

**PoC (Proof of Concept)** is a demonstration that shows whether a particular idea, weakness or vulnerability can be reproduced.

### 7.5 Zero-Day

A **Zero-Day Vulnerability** is a security vulnerability for which a fix or patch is not yet available when it is discovered or exploited.

---

## 8. Shells

A **Shell** is a computer program that provides an interface through which users can interact with an operating system and access its services.

### 8.1 Types of Shells

| Type | Description |
|---|---|
| **Bind Shell** | A shell in which a target system listens for an incoming connection. |
| **Reverse Shell** | A shell in which the target system initiates a connection back to another system. |
| **Web Shell** | A script placed on a web server that can provide remote command execution capabilities. |

### 8.2 Basic Shell Communication Concepts

```text
Bind Shell:     Attacker  ───────►  Target (listening port)

Reverse Shell:  Attacker  ◄───────  Target (connects back)
```

---

## 9. IP Addressing: IPv4 and IPv6

IP addressing allows devices to be identified and communicate across networks.

### 9.1 IPv4

**IPv4 (Internet Protocol Version 4)** uses 32-bit addresses and supports approximately 4.3 billion unique addresses.

### 9.2 IPv6

**IPv6 (Internet Protocol Version 6)** was developed to address the limitations of IPv4 address availability by providing a much larger address space.

| Version | Details |
|---|---|
| **IPv4** | Uses 32-bit addresses and provides approximately 4.3 billion unique addresses. |
| **IPv6** | Provides a significantly larger address space than IPv4. |

---

## 10. Quick Reference

| Term | Definition |
|---|---|
| CIA Triad | Confidentiality, Integrity and Availability. |
| IAM | Identity and Access Management. |
| OWASP | Open Web Application Security Project. |
| OSSTMM | Open Source Security Testing Methodology Manual. |
| NIST | National Institute of Standards and Technology. |
| CVE | Common Vulnerabilities and Exposures. |
| CVSS | Common Vulnerability Scoring System. |
| PoC | Proof of Concept. |
| Zero-Day | A vulnerability for which a fix or patch is not yet available. |
| Bind Shell | A shell that listens for an incoming connection. |
| Reverse Shell | A shell that initiates a connection back to another system. |
| Web Shell | A web-server script that can provide remote command execution. |

---

*Training reference: Hackviser – Module 1: Introduction to Cybersecurity.*
