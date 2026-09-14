# snort-ids-traffic-detection-lab

## Overview

This project documents a controlled university cybersecurity lab focused on detecting network activity with the Snort Intrusion Detection System (IDS).

The experiments generated ICMP, HTTP, SSH and Telnet traffic in an isolated virtual network. Snort monitored the traffic and produced alerts when packets matched the configured detection rules. The final exercise examined how firewall configuration could be used to interrupt an unauthorized connection.

The purpose of this lab was to understand how network traffic is detected, interpreted and controlled from a defensive security perspective.

> **Ethical Scope:** All traffic generation, monitoring and firewall testing were performed in an isolated and authorized university lab environment. This repository is presented strictly for educational and defensive purposes.

## Lab Objectives

- Configure and operate Snort as a network intrusion detection system.
- Detect ICMP packets moving across the lab network.
- Generate and identify HTTP web-access requests.
- Detect an ICMP Source Quench message.
- Monitor SSH connection attempts.
- Identify new Telnet connections.
- Examine Snort alert information and network indicators.
- Apply firewall controls and verify the resulting connection behavior.

## Tools and Environment 

- Snort IDS
- Linux virtual machines
- VMware
- PuTTY
- Juniper Junos firewall
- Telnet
- SSH
- HTTP utilities
- ICMP utilities


