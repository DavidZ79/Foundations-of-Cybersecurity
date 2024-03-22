<h1>CompTIA Security+ Glossary</h1>
<h2>Domain 1.0 - Attacks, Threats, and Vulnerabilities - 24%</h2>

<h3>1.1 - Social Engineering</h3>
Phishing, Pharming, Spear phishing

Impersonation, Eliciting information, Identity fraud

Dumpster Diving

Shoulder Surfing

Hoaxes, De-hoaxing

Watering Hole Attacks: third party is watering hole, infect that

Spam, Mail gateways, identifying spam

Influence Campaigns, Hacking public opinion, Hybrid warfare

Other: Tailgating, invoice scams, Credential harvesting

Principles: Authority, Intimidation, Consensus / Social proof, Scarcity, Urgency, Familiarty / Liking, Trust


<h3>1.2 - Attack Types</h3>

Malware

Virus, Fileless virus: virus needs host file or program to spread, worms self-duplicate

Ransomware and Crypto-malware

Trojans and RATs, Potentially Unwanted Program (PUP), Backdoors

Rootkits, Kernel drivers: stealth malware

Spyware, Adware

Bots and Botnets

Logic Bombs

Password Attacks, hashing, spraying attack: very common passwords, dictionary attack, rainbow tables: precomputed look up tables for hashing, adding some salt

Physical Attacks, malicious USB cable / flash drive, skimming, card cloning

Adversarial AI, ML, poisoning training data, evasion attacks, secure learning algos

Supply Chain Attacks

Cloud-based vs. On-Premises Attacks

Cryptographic Attacks, birthday attack, collisions, downgrade attack



<h3>1.3 - Application Attacks</h3>

Privilege Escalation: normal user to gain elevated access

Cross-site Scripting (XSS), Non-persistent (reflected) / Persistent (stored) XSS attack, browser attack

Injection Attacks, code injection, SQL injection, XML injection, LDAP injection, DLL injection

Buffer Overflows: memory spill

Replay Attacks, header manipulation, prevent session hijacking, browser cookies and session IDs, sidejacking

Request Forgeries, cross-site requests, client and the server, forgeries, server-side request forgery (SSRF)

Driver Manipulation, malware hide-and-go-seek, shimming, refactoring

SSL Stripping, HTTP downgrade, SSL and TLS: attacker sits between client and server to intercept info

Race Conditions

Other: memory vulnerabilities, directory traversal, improper error handling, improper input handling, API attacks, resource exhaustion

<h3>1.4 - Network Attacks</h3>

Rogue Access Points and Evil Twins: wireless network access points without admin knowledge. rogue access point that mimics real access point

Bluejacking and Bluesnarfing: bluejacking is sending message via bluetooth. bluesnarfing is accessing information stored on a bluetooth device

Wireless Disassociation Attacks: type of dos attack

Wireless Jamming

RFID and NFC Attacks

Randomizin Cryptography

On-Path Attacks

MAC Flooding and Cloning

DNS Attacks

Denial of Service

Malicious Scripts

<h3>1.5 - Threat Actors and Vectors</h3>

Threat Actors

Attack Vectors

Threat Intelligence

Threat Research

<h3>1.6 - Vulnerabilities</h3>

Vulnerability Types

Third-party Risks

Vulnerability Impacts

<h3>1.7 - Security Assessments</h3>

Threat Hunting

Vulnerability Scans

Security Information and Event Management

<h3>Penetration Testing</h3>

Penetration Testing: rules of engagement, working knowledge, unknown / known environment. initial exploitation, lateral movement, persistence, pivot. Cleanup, bug bounty

Reconnaissance: digital footprint, security posture, minimize attack area, create network map. Wardriving / warflying: combine WIFI monitoring and GPS

Security Teams: red team, blue team does threat hunting, purple team, white team oversees both sides, puts results from pen test




<h2>Domain 2.0 - Architecture and Design - 21%</h2>

<h3>2.1 - Enterprise Security</h3>

Configuration Management

Protecting Data

Data Loss Prevention

Managing Security

Site Resiliency

Honeypots and Deception

<h3>2.2 Virtualization and Cloud Computing</h3>

Cloud Models

Edge and Fog Computing

Designing the Cloud

Infrastructure as Code

Virtualization Security

<h3>2.3 - Secure Application Development</h3>

Secure Deployments

Provisioning and Deprovisioning

Secure Coding Techniques

Software Diversity

Automation and Scripting

<h3>2.4 - Authentication and Authorization</h3>

Authentication Methods

Biometrics

Multi-factor Authentication

<h3>2.5 - Resilience</h3>

Disk Redundancy

Network Redundancy

Power Redundancy

Replication

Backup Types

Resiliency

<h3>2.6 - Embedded Systems</h3>

Embedded Systems

Embedded Systems Communication

Embedded Systems Constraints

<h3>2.7 - Physical Security Controls</h3>

Physical Security Controls

Secure Areas

Secure Data Destruction

<h3>2.8 - Cryptographic Concepts</h3>

Cryptography Concepts

Symmetric and Assymetric Cryptography

Hashing and Digital Signatures

Cryptographic Keys

Steganography

Quantum Computing

Stream and Block Ciphers

Blockchain Technology

Cryptography Use Cases

Cryptography Limitations



<h2>Domain 3.0 - Implementation - 25%</h2>

<h3>3.1 - Secure Protocols</h3>

Secure Protocols: SRTP: Secure real time transport protocol: AES is encryption used, NTP has no security features, NTPsec. Email: SMIME: secure multipurpose internet mail extensions, POP ... IPsec: internet protocol security. FTPS: file transfer over SSL. SFTP: SSH file transfer protocol. LDAP / DAP is a protocol for reading and writing. SSH for remote access. DNSSEC validate original server. SNMPv3 for routing and switching. DHCP...

<h3>3.2 - Host and Application Security</h3>

Endpoint Protection, HIDS, HIPS

Boot Integrity: TPM, UEFI BIOS

Database Security: hashing a password. salt is random stuff after a pw

Application Security: SAST: static application security testing, tests for injections

Application Hardening

<h3>3.3 - Secure Network Designs</h3>

Load Balancing

Network Segmentation

Virtual Private Networks

Port Security

Secure Networking

Firewalls

Network Access Control

Proxy Servers

Intrusion Prevention

Other Network Appliances

<h3>3.4 - Wireless Security</h3>

Wireless Cryptography

Wireless Authentication Methods

Wireless Authentication Protocols

Installing Wireless Networks

<h3>3.5 - Mobile Security</h3>

Mobile Networks

Mobile Device Management

Mobile Device Security

Mobile Device Enforcement

Mobile Deployment Models

<h3>3.6 - Cloud Security</h3>

Cloud Security Controls

Securing Cloud Storage

Securing Cloud Networks

Securing Compute Clouds

Cloud Security Solutions

<h3>3.7 - Identity and Account Management</h3>

Identity Controls

Account Types

Account Pliicies

<h3>3.8 - Authentication and Authorization Services</h3>

Authentication Management

PAP and CHAP

Identity and Access Services

Federated Identities

Access Control


<h3>3.9 - Public Key Infrastructures</h3>

Public Key Infrastructure

Certificates

Certificate Formats

Certificate Concepts





<h2>Domain 4.0 - Operations and Incident Response - 16%</h2>

<h3>4.1 - Security Tools</h3>

Reconnaissance Tools - Part 1

Reconnaissance Tools - Part 2

Fire Manupulation Tools

Shell and Script Environments

Packet Tools

Forensic Tools

<h3>4.2 - Incident Response</h3>

Incident Response Process

Incident Response Planning

Attack Frameworks

<h3>4.3 - Investigations</h3>

Vulnerability Scan Output

SIEM Dashboards

Log Files

Log Management

<h3>4.4 - Securing an Environment</h3>

Endpoint Security Configuration

Security Configurations

<h3>4.5 - Digital Forensics</h3>

Digital Forensics

Forensics Data Acquisition

On-Premises vs. Cloud Forensics

Managing Evidence


<h2>Domain 5.0 Governance, Risk, and Compliance - 14%</h2>

<h3>5.1 - Security Controls</h3>

Security Controls: Categories: managerial, operational, technical. Types: preventative, detective, corrective, deterrent, compensating, physical

<h3>5.2 - Regulations, Standards, and Frameworks</h3>

Security Regulations and Standards: GDPR: general data protection regulation EU. PCI DSS: payment card industry data security standard, six control objectives

Security Frameworks: CIS: written by it professionals, NIST is government

Secure Configurations

<h3>5.3 - Organizational Security Policies</h3>

Personnel Security

Third-party Risk Management

Managing Data

Credential Policies

Organizational Policies

<h3>5.4 - Risk Management</h3>

Risk Management Types

Risk Analysis

Business Impact Analysis



<h3>5.5 - Data Privacy</h3>

Privacy and Data Breaches

Data Classifications

Enhancing Privacy

Data Roles and Responsibilities


