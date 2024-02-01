<h2>Introduction to security hardening</h2>

Hardening: strengthening a system, minimize attack surface.

Pen testing!!!

<h2>OS hardening</h2>

Patch update: update to patch security vulnerability.

Baseline configuration

Assessing vulnerabilities
Before a brute force attack or other cybersecurity incident occurs, companies can run a series of tests on their network or web applications to assess vulnerabilities. Analysts can use virtual machines and sandboxes to test suspicious files, check for vulnerabilities before an event occurs, or to simulate a cybersecurity incident.

Virtual machines (VMs) are software versions of physical computers. VMs provide an additional layer of security for an organization because they can be used to run code in an isolated environment, preventing malicious code from affecting the rest of the computer or system. VMs can also be deleted and replaced by a pristine image after testing malware. 

VMs are useful when investigating potentially infected machines or running malware in a constrained environment. Using a VM may prevent damage to your system in the event its tools are used improperly. VMs also give you the ability to revert to a previous state. However, there are still some risks involved with VMs. There’s still a small risk that a malicious program can escape virtualization and access the host machine. 

You can test and explore applications easily with VMs, and it’s easy to switch between different VMs from your computer. This can also help in streamlining many security tasks.

Sandbox environments: 
A sandbox is a type of testing environment that allows you to execute software or programs separate from your network. They are commonly used for testing patches, identifying and addressing bugs, or detecting cybersecurity vulnerabilities. Sandboxes can also be used to evaluate suspicious software, evaluate files containing malicious code, and simulate attack scenarios. 

Sandboxes can be stand-alone physical computers that are not connected to a network; however, it is often more time- and cost-effective to use software or cloud-based virtual machines as sandbox environments. Note that some malware authors know how to write code to detect if the malware is executed in a VM or sandbox environment. Attackers can program their malware to behave as harmless software when run inside these types of  testing environments. 

<h2>Network hardening</h2>

Network segmentation, port filtering

<h2>Cloud hardening</h2>

Server baseline images

Shared responsibility model
A commonly accepted cloud security principle is the shared responsibility model. The shared responsibility model states that the CSP must take responsibility for security involving the cloud infrastructure, including physical data centers, hypervisors, and host operating systems. The company using the cloud service is responsible for the assets and processes that they store or operate in the cloud.

The shared responsibility model ensures that both the CSP and the users agree about where their responsibility for security begins and ends. A problem occurs when organizations assume that the CSP is taking care of security that they have not taken responsibility for. One example of this is cloud applications and configurations. The CSP takes responsibility for securing the cloud, but it is the organization’s responsibility to ensure that services are configured properly according to the security requirements of their organization. 

<h2>Glossary</h2>

Terms and definitions from Course 3, Module 4
Baseline configuration (baseline image): A documented set of specifications within a system that is used as a basis for future builds, releases, and updates

Hardware: The physical components of a computer

Multi-factor authentication (MFA): A security measure which requires a user to verify their identity in two or more ways to access a system or network

Network log analysis: The process of examining network logs to identify events of interest 

Operating system (OS): The interface between computer hardware and the user

Patch update: A software and operating system update that addresses security vulnerabilities within a program or product
Penetration testing (pen test): A simulated attack that helps identify vulnerabilities in systems, networks, websites, applications, and processes 

Security hardening: The process of strengthening a system to reduce its vulnerabilities and attack surface

Security information and event management (SIEM): An application that collects and analyzes log data to monitor critical activities for an organization

World-writable file: A file that can be altered by anyone in the world