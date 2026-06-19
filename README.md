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

During a Wireshark network traffic investigation, unusual mDNS broadcasts were observed originating from my LG Smart TV on the local network.

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

### Errors Encountered

During this lab I attempted to open files by typing:

evidence.txt
notes.txt
suspicious.log

PowerShell returned CommandNotFound errors because it interpreted the filenames as commands.

### Resolution

I learned to use:

Get-Content filename.txt

to read file contents and

notepad filename.txt

to edit files.

This troubleshooting process helped reinforce how PowerShell handles commands versus files.

## Screenshots

### Creating Files and Evidence

![Creating Files](Screenshot%202026-06-19%20182714.png)

### Troubleshooting PowerShell Errors

![PowerShell Errors](Screenshot%202026-06-19%20182923.png)

### Reviewing Investigation Notes

![Investigation Notes](Screenshot%202026-06-19%20183229.png)

### Creating Incident Reports

![Incident Reports](Screenshot%202026-06-19%20183840.png)

### Final Investigation Findings

![Final Findings](Screenshot%202026-06-19%20184102.png)

## Author

Shauna "Storm" Davis

Cyber & Data Security Technology Student

Future CISO | Cybersecurity Enthusiast | Lifelong Learner
