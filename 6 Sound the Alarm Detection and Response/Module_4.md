<h2>Overview of logs</h2>

logslogslogs: record of events within a system

Log details
Generally, logs contain a date, time, location, action, and author of the action. Here is an example of an authentication log:

Login Event [05:45:15] User1 Authenticated successfully

Logs contain information and can be adjusted to contain even more information. Verbose logging records additional, detailed information beyond the default log recording. Here is an example of the same log above but logged as verbose.

Login Event [2022/11/16 05:45:15.892673] auth_performer.cc:470 User1 Authenticated successfully from device1 (192.168.1.2)

log formats:

JSON

Syslog

XML

CSV

CEF

<h2>Overview of intrusion detection systems (IDS)</h2>

telemetry: collection and transmission of data for analysis

host-based intrusion detection system

Suricata
 is an open-source intrusion detection system, intrusion prevention system, and network analysis tool.

Suricata features
There are three main ways Suricata can be used:

Intrusion detection system (IDS): As a network-based IDS, Suricata can monitor network traffic and alert on suspicious activities and intrusions. Suricata can also be set up as a host-based IDS to monitor the system and network activities of a single host like a computer.

Intrusion prevention system (IPS): Suricata can also function as an intrusion prevention system (IPS) to detect and block malicious activity and traffic. Running Suricata in IPS mode requires additional configuration such as enabling IPS mode. 

Network security monitoring (NSM): In this mode, Suricata helps keep networks safe by producing and saving relevant network logs. Suricata can analyze live network traffic, existing packet capture files, and create and save full or conditional packet captures. This can be useful for forensics, incident response, and for testing signatures. For example, you can trigger an alert and capture the live network traffic to generate traffic logs, which you can then analyze to refine detection signatures.

<h2>Overview of security information event management (SIEM) tools</h2>

Splunk and chronicle search activities

<h2>Glossary</h2>
Terms and definitions from Course 6, Module 4
Anomaly-based analysis: A detection method that identifies abnormal behavior 

Array: A data type that stores data in a comma-separated ordered list

Common Event Format (CEF): A log format that uses key-value pairs to structure data and identify fields and their corresponding values

Configuration file: A file used to configure the settings of an application

Endpoint: Any device connected on a network

Endpoint detection and response (EDR): An application that monitors an endpoint for malicious activity

False positive: An alert that incorrectly detects the presence of a threat

Host-based intrusion detection system (HIDS): An application that monitors the activity of the host on which it’s installed 

Intrusion detection systems (IDS): An application that monitors system activity and alerts on possible intrusions

Key-value pair: A set of data that represents two linked items: a key, and its corresponding value

Log: A record of events that occur within an organization’s systems

Log analysis: The process of examining logs to identify events of interest 

Log management: The process of collecting, storing, analyzing, and disposing of log data

Logging: The recording of events occurring on computer systems and networks

Network-based intrusion detection system (NIDS): An application that collects and monitors network traffic and network data

Object: A data type that stores data in a comma-separated list of key-value pairs

Search Processing Language (SPL): Splunk’s query language

Security information and event management (SIEM): An application that collects and analyzes log data to monitor critical activities in an organization 

Signature: A pattern that is associated with malicious activity

Signature analysis: A detection method used to find events interest

Suricata: An open-source intrusion detection system, intrusion prevention system, and network analysis tool

Telemetry: The collection and transmission of data for analysis

Wildcard: A special character that can be substituted with any other character

YARA-L: A computer language used to create rules for searching through ingested log data

Zero-day: An exploit that was previously unknown