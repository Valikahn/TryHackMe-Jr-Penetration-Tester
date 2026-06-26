# TryHackMe - Jr Penetration Tester Writeups
![Alt text](https://github.com/Valikahn/TryHackMe-Jr-Penetration-Tester/blob/main/IMAGES/v4l1k4hn.png?raw=true)
This repository contains my personal [TryHackMe](https://tryhackme.com/) writeups, notes, and walkthroughs from completed rooms and learning paths.

The purpose of this repository is to document my methodology, commands, observations, mistakes, and final exploitation paths in a way that is useful for revision, portfolio building, and future reference.

## About This Repository

Each writeup is written from the perspective of a controlled lab environment. The rooms covered here are intentionally vulnerable systems provided by TryHackMe for cybersecurity training.

The IP addresses shown in these writeups were allocated during the TryHackMe labs, with the attack performed either from the TryHackMe AttackBox or from my own Kali Linux VM using OpenVPN connected to the TryHackMe VPN, including the Paris VPN server where noted.

**PLEASE NOTE:** This repository will **NOT** contain anything from the Jr Penetration Tester (PT1) certification exam! If you are looking for any assistance, answers, guides, walkthroughs you will **NOT** find any of those here, help/assistance is limited, but available via the [TryHackMe Discord](https://discord.com/invite/tryhackme).

## Repository Structure

Writeups may include:

- Room overview
- Target and attacker IP details
- Enumeration steps
- Initial access
- Privilege escalation path
- Flags recovered <REDACTED>
- Key findings <REDACTED>
- Lessons learned
- Remediation notes

## Completed Writeups

**Pathway:** [*Jr Penetration Tester*](https://tryhackme.com/path/outline/jrpenetrationtester)

| Section | Challenge | Status |
|---|---|---|
| Web Application Vulnerabilities I | [Recruit](https://tryhackme.com/room/recruitwebchallenge) | [Complete](https://github.com/Valikahn/TryHackMe-Jr-Penetration-Tester/blob/main/WRITEUPS/recruit_challenge.md) |
| Web Application Vulnerabilities II | [Support](https://tryhackme.com/room/support) | [Complete](https://github.com/Valikahn/TryHackMe-Jr-Penetration-Tester/blob/main/WRITEUPS/support_challenge.md) |
| Password Attacks | [Checkmate](https://tryhackme.com/room/checkmate) | [Complete](https://github.com/Valikahn/TryHackMe-Jr-Penetration-Tester/blob/main/WRITEUPS/checkmate_challenge.md) |
| Privilege Escalation | [Jump](https://tryhackme.com/room/jump) | [Complete](https://github.com/Valikahn/TryHackMe-Jr-Penetration-Tester/blob/main/WRITEUPS/jump_challenge.md) |
| Privilege Escalation | [Windows Jump](https://tryhackme.com/room/windowsjump) | [Complete](https://github.com/Valikahn/TryHackMe-Jr-Penetration-Tester/blob/main/WRITEUPS/windows_jump_challenge.md) |
| Active Directory Security Testing Basics | [Proxy](https://tryhackme.com/room/proxychallenge) | Work in Progress |
| Active Directory Security Testing Basics | [Forward](https://tryhackme.com/room/forwardchallenge) | Work in Progress |
| Jr Pentester Challenges | [Domino](https://tryhackme.com/room/domino) | Work in Progress |
| Jr Pentester Challenges | [Silent Monitor](https://tryhackme.com/room/silent-monitor) | Work in Progress |
| Jr Pentester Challenges | [Dead Drop](https://tryhackme.com/room/dead-drop) | Work in Progress |
| Jr Pentester Challenges | [Operation Promotion](https://tryhackme.com/room/operationpromotion) | Work in Progress |
| Jr Pentester Challenges | [Operation Coldstart](https://tryhackme.com/room/operationcoldstart) | Work in Progress |
| Jr Pentester Challenges | [Net Sec Challenge](https://tryhackme.com/room/netsecchallenge) | Work in Progress |
| Jr Pentester Challenges | [Interceptor](https://tryhackme.com/room/interceptor) | Work in Progress |

**Requests**

| Section | Challenge | Status |
|---|---|---|
| Metasploit: Payload Generation | Capstone Challenge | [Completed](https://github.com/Valikahn/TryHackMe-Jr-Penetration-Tester/blob/main/WRITEUPS/capstone_challenge.md) |

## Tools Commonly Used

The tools used vary by room, but may include:

| -Kali- | -Linux- | -Tool- | -Set- |
| --- | --- | --- | --- |
| [Nmap](https://nmap.org/) | [Rustscan](https://github.com/RustScan/RustScan) | [Zaproxy](https://www.kali.org/tools/zaproxy/) | [Chisel](https://www.kali.org/tools/chisel/) |
| [vsFTP](https://security.appspot.com/vsftpd.html) | [Enumerating Active Directory](https://tryhackme.com/room/adenumeration) | [Sshuttle](https://www.kali.org/tools/sshuttle/) | [Rpivot](https://github.com/klsecservices/rpivot) |
| [SSH / OpenSSH](https://www.kali.org/tools/openssh/) | [Netcat / nc](https://www.kali.org/tools/netcat/) | [Burpsuite](https://www.kali.org/tools/burpsuite/) | [Metasploit Framework](https://www.kali.org/tools/metasploit-framework/) |
| [Penelope](https://www.kali.org/tools/penelope) | [Nmap Post Port Scans](https://tryhackme.com/room/nmap04) | [CeWL](https://www.kali.org/tools/cewl/) | [BloodHound](https://www.kali.org/tools/bloodhound/) |
| [Pspy](https://www.kali.org/tools/pspy/) | [Peass-ng](https://www.kali.org/tools/peass-ng/) | [Enum4linux](https://www.kali.org/tools/enum4linux/) | [Kerberoasting](https://github.com/nidem/kerberoast) |
| [John](https://www.kali.org/tools/john/) | [Impacket-Scripts](https://www.kali.org/tools/impacket-scripts/) | [Gobuster](https://www.kali.org/tools/gobuster/) | [Scapy](https://www.kali.org/tools/scapy/) |
| [Hydra](https://www.kali.org/tools/hydra/) | [Hashcat](https://www.kali.org/tools/hashcat/) | [PowerShell](https://www.kali.org/tools/powershell/) | [Dig](https://www.kali.org/tools/bind9/#dig) |
| [Ffuf](https://www.kali.org/tools/ffuf/) | [NetExec / nxc](https://www.kali.org/tools/netexec/) | [Evilginx2](https://www.kali.org/tools/evilginx2/) | [Responder](https://www.kali.org/tools/responder/) |
| [Feroxbuster](https://www.kali.org/tools/feroxbuster/) | [Evil-WinRM](https://www.kali.org/tools/evil-winrm/) | [Hacktricks Wiki](https://hacktricks.wiki/en/linux-hardening/linux-privilege-escalation-checklist.html) | [GTFOBins](https://gtfobins.github.io/) |
| [Cupp](https://github.com/Mebus/cupp) | [Freerdp3](https://www.kali.org/tools/freerdp3/#xfreerdp3) |  |  |

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

Writeups `MAY` contain spoilers, privilege escalation paths, and command output, sometimes this will be deliberate but other times this will be by mistake, if this is the case please let me know in the [Discussions](https://github.com/Valikahn/TryHackMe-Jr-Penetration-Tester/discussions). If you are actively working through a room, consider attempting it yourself before reading the full walkthrough.
Writeups `WILL NEVER` contain passwords, cracked or otherwise, no hashes or flags.

## Connect With Me

Thanks for checking out my TryHackMe writeups. These notes form part of my ongoing cybersecurity learning journey, where I document rooms, techniques, tools, mistakes and lessons learned while working through different challenges.

You can view my TryHackMe profile here:

[TryHackMe Profile - V4L1K4HN](https://tryhackme.com/p/V4L1K4HN)

I am also active within cybersecurity learning communities, including Discord, where I discuss labs, tools, methodologies and general security topics with other learners and practitioners.

Feel free to follow my progress, compare approaches or get in touch if you are working through similar rooms.

Walkthrough requests are always welcome, although publication will depend on my availability and whether sharing the content complies with the platform's rules.

Created by V4L1K4HN as part of my cybersecurity learning journey through TryHackMe.

## Licence

Unless otherwise stated, the original written content in this repository is licensed under the [Creative Commons Attribution 4.0 International Licence](https://creativecommons.org/licenses/by/4.0/legalcode.en).

Copyright © 2026 V4L1K4HN.

You may share and adapt the licensed material for any purpose, including commercially, provided that:

- appropriate credit is given to V4L1K4HN;
- a link to the licence is provided; and
- any changes made to the original material are clearly indicated.

This licence applies only to original material created by the repository author. TryHackMe content, branding, room materials, third-party software, trademarks, externally sourced material, and any other third-party intellectual property remain subject to their respective owners' terms and licences.

See the [LICENSE](https://github.com/Valikahn/TryHackMe-Writeups/blob/main/LICENSE) file for the complete legal terms.

---
___
__
____
**Made with ❤️ by [V4L1K4HN](https://github.com/Valikahn)**   
⭐ If this project is useful, consider starring it on GitHub.
