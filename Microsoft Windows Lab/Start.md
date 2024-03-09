<h2>Lab 1: Windows Defender Antivirus </h2>

Review Windows Security Virus and threat protection.
Update threat definitions.
Run Windows Defender Antivirus quick scan.

Windows -> Settings -> Update Security -> Virus and threat protection

Here you can scan individual folders.

<h2>Lab 2: Windows Defender Firewall</h2>

Windows Defender Firewall is a host-based software firewall that is included with the Windows operating system. In this lesson we will learn to configure firewall rules using Windows Defender Firewall and Windows Defender Firewall with Advanced Security.

Configure Firewall Rules Using Windows Defender Firewall
Configure Firewall Rules Using Windows Defender Firewall with Advanced Security

Windows -> Windows Security -> Firewall & network protection

**Domain network:** Domain networks are workplace networks. A computer must be a part of the domain in order to communicate with other computers on that network. 

**Private network:** Private networks are discoverable networks, meaning that only devices on that network can see or discover other devices on that same network. Home networks are a good example of a private network. 

**Public network:** Public networks are non-discoverable networks. A non-discoverable network is a network where your device cannot be discovered by other devices on your network. A coffee shop or a library would be a good example of a public network. You do not want other individuals to be able to discover your device.

Here you can temporarily stop all incoming connections, and allow an app through the firewall.

Advanced Security: 

All Windows Firewall rules, and their details, are stored here, allowing you to edit configurations for each rule or exception.

For this lab, we want to use Windows Defender Firewall with Advanced Security to edit an existing firewall rule. We want to enforce the following rules:

Allow the connection for Key Management Service on the Domain and Private network.
Deny the connection for Key Management Service on the Public network.

Here you will see an Overview in the center panel. Make special note of the two rule types listed on the left panel:

Inbound rules: Inbound rules determine what traffic is allowed to the computer.
Outbound rules: Outbound rules determine what traffic is allowed to leave the computer.
Connection security rules
Monitoring
Each of these rules can be configured to filter traffic based on computers, users, applications, ports, protocols, and so on.

Double click a rule -> Advanced tab -> then you can access the rule profiles here. You can copy-paste similar rules.
