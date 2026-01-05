 # Network Pivoting & Lateral Movement using Metasploit

## Overview

This repository documents a controlled penetration testing exercise focused on
network pivoting and lateral movement. The assessment demonstrates how an
initially compromised system can be used as a pivot point to access and exploit
additional hosts within an internal network segment.

The project was conducted in a lab environment for educational and authorized
security testing purposes only.

---

## Summary of Actions

- Gained initial access to a UNIX-based system
- Configured Metasploit routing to pivot into an internal network
- Discovered additional hosts through the pivoted connection
- Identified an exposed FTP service on an internal system
- Exploited a vulnerable vsftpd service to compromise a second host

---

## Repository Structure

- /report — Detailed pivoting and lateral movement report  
- /screenshots — Step-by-step visual evidence  
- /notes — Commands and assessment references  

---

## Tools & Technologies

- Kali Linux  
- Metasploit Framework  
- UNIX-based target system (pivot host)  
- Internal vulnerable target (FTP service)  
- Virtualized lab environment  

---

## Purpose

This project highlights the security risks of weak internal segmentation and
unpatched services. It demonstrates how attackers can move laterally within a
network after an initial compromise and reinforces the importance of defense-in-depth controls.
