<h2>Understanding network traffic</h2>

Network traffic vs network data

Indicators of Compromise, data exfiltration attack

lateral movement / pivoting

<h2>Capture and view network traffic</h2>

packets: header, payload, footer

packet sniffer, packet capture (P-cap)

---
IPv4 is the most commonly used version of IP. There are thirteen fields in the header:

Version: This field indicates the IP version. For an IPv4 header, IPv4 is used. 

Internet Header Length (IHL): This field specifies the length of the IPv4 header including any Options.

Type of Service (ToS): This field provides information about packet priority for delivery.

Total Length: This field specifies the total length of the entire IP packet including the header and the data.

Identification: Packets that are too large to send are fragmented into smaller pieces. This field specifies a unique identifier for fragments of an original IP packet so that they can be reassembled once they reach their destination.

Flags: This field provides information about packet fragmentation including whether the original packet has been fragmented and if there are more fragments in transit.

Fragment Offset: This field is used to identify the correct sequence of fragments.

Time to Live (TTL): This field limits how long a packet can be circulated in a network, preventing packets from being forwarded by routers indefinitely.

Protocol: This field specifies the protocol used for the data portion of the packet.

Header Checksum: This field specifies a checksum value which is used for error-checking the header.

Source Address: This field specifies the source address of the sender.

Destination Address: This field specifies the destination address of the receiver.

Options: This field is optional and can be used to apply security options to a packet.

---
IPv6 adoption has been increasing because of its large address space. There are eight fields in the header:

Version: This field indicates the IP version. For an IPv6 header, IPv6 is used.

Traffic Class: This field is similar to the IPv4 Type of Service field. The Traffic Class field provides information about the packet's priority or class to help with packet delivery.

Flow Label: This field identifies the packets of a flow. A flow is the sequence of packets sent from a specific source. 

Payload Length: This field specifies the length of the data portion of the packet.

Next Header: This field indicates the type of header that follows the IPv6 header such as TCP.

Hop Limit: This field is similar to the IPv4 Time to Live field. The Hop Limit limits how long a packet can travel in a network before being discarded.

Source Address: This field specifies the source address of the sender.

Destination Address: This field specifies the destination address of the receiver.

WIRESHARK is an open source packet sniffer

<h2>Packet Inspection</h2>

tcpdump: command line tool network analyzer


A network protocol analyzer (packet sniffer) is a tool designed to capture and analyze data traffic within a network.

Packet sniffing is the practice of capturing and inspecting data packets across a network. 
<h2>Glossary</h2>

Terms and definitions from Course 6, Module 2
Command and control (C2): The techniques used by malicious actors to maintain communications with compromised systems

Command-line interface (CLI): A text-based user interface that uses commands to interact with the computer

Data exfiltration: Unauthorized transmission of data from a system

Data packet: A basic unit of information that travels from one device to another within a network

Indicators of compromise (IoC): Observable evidence that suggests signs of a potential security incident

Internet Protocol (IP): A set of standards used for routing and addressing data packets as they travel between devices on a network

Intrusion detection systems (IDS): An application that monitors system activity and alerts on possible intrusions

Media Access Control (MAC) Address: A unique alphanumeric identifier that is assigned to each physical device on a network

National Institute of Standards and Technology (NIST) Incident Response Lifecycle: A framework for incident response consisting of four phases: Preparation; Detection and Analysis; Containment, Eradication and Recovery; and Post-incident activity

Network data: The data that’s transmitted between devices on a network 

Network protocol analyzer (packet sniffer): A tool designed to capture and analyze data traffic within a network

Network traffic: The amount of data that moves across a network 

Network Interface Card (NIC): Hardware that connects computers to a network

Packet capture (p-cap): A file containing data packets intercepted from an interface or network

Packet sniffing: The practice of capturing and inspecting data packets across a network

Playbook: A manual that provides details about any operational action

Root user (or superuser): A user with elevated privileges to modify the system

Sudo: A command that temporarily grants elevated permissions to specific users

tcpdump: A command-line network protocol analyzer

Wireshark: An open-source network protocol analyzer