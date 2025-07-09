# OVERVIEW
- This project implements an SSH/Telnet Medium Interaction Honeypot to capture and analyze unauthorized login attempts and malicious behavior patterns. It emulates a fake Linux shell and file system to deceive attackers, providing valuable insights into modern attack vectors and brute-force techniques.

##  What is Honeypot

A Honeypot is a network-attached system used as a trap for cyber-attackers to detect and study the tricks and types of attacks used by hackers. It acts as a potential target on the internet and informs the defenders about any unauthorized attempt at the information system. Honeypots are mostly used by large companies and organizations involved in cybersecurity. It helps cybersecurity researchers learn about the different types of attacks used by attackers. It is suspected that even cybercriminals use these honeypots to decoy researchers and spread wrong information. The cost of a honeypot is generally high because it requires specialized skills and resources to implement a system such that it appears to provide an organization’s resources while still preventing attacks at the backend and access to any production system.

## Tools And Technologies

| Tools             | Purpose                       | Setup Link            |
| :---------------- | :---------------------------- | :-------------------: |
| Cowrie            | SSH/Telnet Honeypot emulation | [Download Cowrie]()   |
| A Server(Ubuntu)  | Host environment              | [Ubuntu Setup]()      |
| Fail2Ban          | Protecting real ssh access    | [Fail2Ban Setup]()    |

# Disclaimer & Warning
This honeypot is intentionally exposed to the public internet. Make sure it is isolated from production or personal data. Never run a honeypot on your personal or office network without proper network segmentation and firewalls.
# Honeypot-server
