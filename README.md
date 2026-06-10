SOC Multi-Threat Detection Dashboard | Splunk SIEM

Project Overview

This project demonstrates the design and implementation of a Security Operations Center (SOC) Multi-Threat Detection Dashboard using Splunk Enterprise. The dashboard centralizes security events from multiple simulated attack scenarios, enabling security analysts to quickly identify, investigate, and respond to potential threats.

The goal of this project is to showcase practical SIEM skills, log analysis, SPL (Search Processing Language), and cybersecurity monitoring techniques used in real-world SOC environments.

Features

Brute Force Detection
Detects repeated failed login attempts from the same IP address.
Displays
Source IP Address
Number of failed attempts
Helps identify password guessing and credential stuffing attacks.

DoS Detection
Monitors abnormal request volumes from a single source.
Displays
Source IP
Total request count
Assists in identifying traffic spikes that may indicate DoS attacks.

Phishing Detection
Tracks users who interact with suspicious or malicious URLs.
Displays
Username
URL clicked
User action
Enables analysts to identify compromised users and investigate phishing campaigns.

Technologies Used
Splunk Enterprise
SPL (Search Processing Language)
Log Analysis
SIEM Monitoring
Cybersecurity Event Correlation
Dashboard Visualization

Dashboard Components
Detection ModulePurposeBrute Force DetectionDetect repeated login failuresDoS DetectionIdentify excessive network requestsPhishing DetectionMonitor suspicious URL interactions

Skills Demonstrated
SIEM Administration
Splunk Dashboard Development
SPL Query Writing
Threat Detection
Security Monitoring
Log Correlation
Incident Analysis

SOC Operations
Blue Team Fundamentals

Dashboard Preview
Insert your dashboard screenshot here

Learning Outcomes
Through this project, I gained hands-on experience in
Building custom Splunk dashboards
Creating threat detection use cases
Investigating security logs
Visualizing attack patterns
Developing practical SOC analyst skills

Future Improvements
Add MITRE ATT&CK mapping
Integrate real firewall and Windows Event logs
Create email alerting for high-severity incidents
Include geo-location visualization of attacker IPs
Add ransomware and insider threat detection use cases

Author
Ibrahim Nasiru
Aspiring SOC Analyst | Cybersecurity Enthusiast | Python & SIEM Learner

Why This Project Matters
This project demonstrates the ability to build and customize a Splunk SIEM dashboard that detects multiple attack types from log data, providing a practical example of the monitoring and investigation skills expected in a Security Operations Center (SOC). It showcases experience with threat detection, SPL queries, dashboard creation, and incident analysis using industry-standard tools.
