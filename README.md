# TryHackMe Writeups

This repository contains my personal [TryHackMe](https://tryhackme.com/) writeups, notes, and walkthroughs from completed rooms and learning paths.

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

- [Nmap](https://nmap.org/) / [Rustscan](https://github.com/RustScan/RustScan)
- [vsFTP](https://security.appspot.com/vsftpd.html)
- [SSH / OpenSSH](https://www.kali.org/tools/openssh/)
- [Netcat / nc](https://www.kali.org/tools/netcat/)
- [Penelope](https://www.kali.org/tools/penelope)
- [Peass-ng](https://www.kali.org/tools/peass-ng/)
- [Pspy](https://www.kali.org/tools/pspy/)
- [John](https://www.kali.org/tools/john/)
- [Hydra](https://www.kali.org/tools/hydra/)
- [Ffuf](https://www.kali.org/tools/ffuf/)
- [Feroxbuster](https://www.kali.org/tools/feroxbuster/)
- [Impacket-Scripts](https://www.kali.org/tools/impacket-scripts/)
- [Hashcat](https://www.kali.org/tools/hashcat/)
- [NetExec / nxc](https://www.kali.org/tools/netexec/)
- [Evil-WinRM](https://www.kali.org/tools/evil-winrm/)
- [Evilginx2](https://www.kali.org/tools/evilginx2/)
- [Responder](https://www.kali.org/tools/responder/)
- [PowerShell](https://www.kali.org/tools/powershell/)
- [Scapy](https://www.kali.org/tools/scapy/)
- [Enum4linux](https://www.kali.org/tools/enum4linux/)
- [Kerberoasting](https://github.com/nidem/kerberoast)
- [CeWL](https://www.kali.org/tools/cewl/)
- [BloodHound](https://www.kali.org/tools/bloodhound/)
- [Burpsuite](https://www.kali.org/tools/burpsuite/)
- [Metasploit Framework](https://www.kali.org/tools/metasploit-framework/)
- [Sshuttle](https://www.kali.org/tools/sshuttle/)
- [Rpivot](https://github.com/klsecservices/rpivot)
- [Zaproxy](https://www.kali.org/tools/zaproxy/)
- [Chisel](https://www.kali.org/tools/chisel/)
- [sudo privilege enumeration](https://man7.org/linux/man-pages/man5/sudoers.5.html) / [GTFOBins](https://gtfobins.github.io/)
- [Manual Linux privilege escalation enumeration](https://hacktricks.wiki/en/linux-hardening/linux-privilege-escalation-checklist.html)

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

All tools, commands, techniques, and methodologies referenced in these writeups were used within controlled training environments where permission was provided by the owner and/or operator of the lab platform. The systems discussed are intentionally vulnerable machines designed for cybersecurity learning, practice, and assessment.

Do not use these techniques, tools, or methods against systems, networks, applications, or services that you do not own or do not have explicit written permission to test. Unauthorised access, scanning, exploitation, or disruption of systems is illegal and unethical.

The tools and methods listed in this repository are examples of approaches used during specific rooms or learning exercises. They are not the only possible solutions, and other tools, techniques, or workflows may be used depending on the target environment, room design, and individual methodology.

## Not Spoiler Warning

Writeups `MAY` contain spoilers, privilege escalation paths, and command output. If you are actively working through a room, consider attempting it yourself before reading the full walkthrough.
Writeups `WILL NEVER` contain passwords, cracked or otherwise, no hashes or flags.

## Connect With Me

Thanks for checking out my TryHackMe writeups. These notes are part of my ongoing cybersecurity learning journey, where I document rooms, techniques, tools, mistakes, and lessons learned as I work through different challenges.

You can view my TryHackMe profile here:

[TryHackMe Profile - V4L1K4HN](https://tryhackme.com/p/V4L1K4HN)

I am also active in cybersecurity learning communities, including Discord, where I discuss labs, tools, methodology, and general security topics with other learners and practitioners.

Feel free to follow my progress, compare approaches, or reach out if you are working through similar rooms.

Created by V4L1K4HN as part of my cybersecurity learning journey through TryHackMe.

## Licence

Unless otherwise stated, the original written content in this repository is licensed under the Creative Commons Attribution 4.0 International Licence.

Copyright © 2026 V4L1K4HN.

You may share and adapt the licensed material for any purpose, including commercially, provided that:

appropriate credit is given to V4L1K4HN;
a link to the licence is provided; and
any changes made to the original material are clearly indicated.

This licence applies only to original material created by the repository author. TryHackMe content, branding, room materials, screenshots, third-party software, trademarks, command output, externally sourced material, and other third-party intellectual property remain subject to their respective owners' terms and licences.

See the LICENSE file for the complete legal terms.
