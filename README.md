# AIG Cybersecurity Simulation

A small cybersecurity case study completed as part of the **AIG Shields Up: Cybersecurity Job Simulation on Forage**.

The simulation focused on two areas: communicating the impact of a critical software vulnerability and using Python to automate password recovery in a ransomware-response training scenario.

## What I Worked On

- Identified the affected infrastructure and team in a simulated Apache Log4j vulnerability scenario.
- Drafted a technical security advisory explaining the risk, exploitation method, and remediation steps.
- Wrote a Python script that iterates through a provided password wordlist and attempts to recover access to an encrypted ZIP archive.
- Used exception handling to detect failed extraction attempts and stop once the correct password was found.

## Skills Practiced

- Python scripting
- File and ZIP handling
- Exception handling
- Wordlist-based password recovery
- Vulnerability communication
- Ransomware-response concepts
- Technical security documentation

## Repository Structure

```
.
├── bruteforce.py
├── docs/
│   └── log4j-advisory.md
└── README.md
```

## Password-Recovery Script

The script expects two training files supplied separately by the simulation:

- `enc.zip` — the encrypted archive
- `rockyou.txt` — a small provided subset of common passwords

It reads each candidate password, attempts to extract the archive, catches failed password attempts, and stops when extraction succeeds.

The simulation files and password list are **not included in this repository**.

## Ethical Use

This code was written for an authorized educational exercise using files provided by the AIG/Forage simulation. It is intended only to demonstrate Python automation and password-recovery concepts in a controlled training environment.

## Context

This repository documents work from a job simulation and does **not** represent employment at AIG.
