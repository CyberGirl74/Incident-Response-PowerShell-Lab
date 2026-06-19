# Incident Response PowerShell Lab

## Overview

This hands-on lab demonstrates foundational PowerShell skills used in cybersecurity and IT operations.

The objective was to practice navigating directories, creating files, documenting findings, and managing evidence using only the command line.

## Skills Practiced

- PowerShell navigation
- Directory creation
- File creation
- File editing
- File verification
- Incident documentation
- Basic cybersecurity reporting

## Commands Used

```powershell
mkdir investigations
cd investigations
New-Item incident1.txt -ItemType File
New-Item incident2.txt -ItemType File
New-Item incident3.txt -ItemType File
ls
notepad incident1.txt
cat incident1.txt

## Investigation Scenario

During a Wireshark network traffic investigation, unusual mDNS broadcasts were observed originating from an LG Smart TV on the local network.

The device repeatedly advertised AirPlay services and broadcast information identifying its location as the living room. This activity was documented as part of a simulated incident response investigation.

## Findings

- LG Smart TV repeatedly announced itself using mDNS
- AirPlay services were advertised on the local network
- Device location information was visible in network broadcasts
- Evidence was documented using PowerShell-created incident files

## Lessons Learned

This lab reinforced several important cybersecurity concepts:

- Command-line proficiency is essential for cybersecurity professionals
- Documentation is a critical part of incident response
- Smart devices generate significant background network traffic
- PowerShell can be used to organize investigations and evidence
- Troubleshooting errors is a normal part of learning technical skills

## Author

Shauna "Storm" Davis

Cyber & Data Security Technology Student

Future CISO | Cybersecurity Enthusiast | Lifelong Learner
