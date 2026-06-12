# TryHackMe Writeups

This repository contains my personal TryHackMe writeups, notes, and walkthroughs from completed rooms and learning paths.

The purpose of this repository is to document my methodology, commands, observations, mistakes, and final exploitation paths in a way that is useful for revision, portfolio building, and future reference.

## About This Repository

Each writeup is written from the perspective of a controlled lab environment. The rooms covered here are intentionally vulnerable systems provided by TryHackMe for cybersecurity training.

The IP addresses shown in these writeups were allocated during the TryHackMe labs, with the attack performed either from the TryHackMe AttackBox or from my own Kali Linux VM using OpenVPN connected to the TryHackMe VPN, including the Paris VPN server where noted.

## Repository Structure

Writeups may include:

- Room overview
- Target and attacker IP details
- Enumeration steps
- Initial access
- Privilege escalation path
- Flags recovered
- Key findings
- Lessons learned
- Remediation notes

## Completed Writeups

| Room | Path | Status |
|---|---|---|
| Jump | Jr Penetration Tester / Privilege Escalation | Completed |

## Tools Commonly Used

The tools used vary by room, but may include:

- Nmap / Rustscan
- FTP
- SSH
- Netcat
- Penelope
- LinPEAS
- pspy
- John the Ripper
- Hydra
- ffuf
- Feroxbuster
- Impacket
- Hashcat
- NetExec / nxc
- Evil-WinRM
- BloodHound
- Burp Suite
- sudo enumeration
- Linux manual enumeration
- Standard Kali Linux tooling

## Methodology

My general approach is:

1. Confirm the target IP and attacker VPN IP.
2. Run initial port and service enumeration.
3. Review accessible services and exposed files.
4. Identify an initial access route.
5. Stabilise the shell where possible.
6. Enumerate users, permissions, cron jobs, timers, services, scripts, and sudo rules.
7. Move laterally or escalate privileges one stage at a time.
8. Capture flags and document the exact path taken.
9. Record lessons learned and defensive remediation notes.

## Disclaimer

These writeups are for educational purposes only and are based on authorised TryHackMe lab environments.

Do not use these techniques against systems that you do not own or do not have explicit permission to test.

## Spoiler Warning

Writeups `MAY` contain spoilers, privilege escalation paths, and command output. If you are actively working through a room, consider attempting it yourself before reading the full walkthrough.
Writeups `WILL NEVER` contain passwords, cracked or otherwise, no hashes or flags.

## Author

Created by V4L1K4HN as part of my cybersecurity learning journey through TryHackMe.
