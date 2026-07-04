# TryHackMe - Jr Penetration Tester Writeups ![PathwayCompleted](https://img.shields.io/badge/pathway-passed-brightgreen?style=for-the-badge)
![Banner](./IMAGES/jrpt_img.png?raw=true)
![License](https://img.shields.io/badge/license-CC_BY_4.0-green) ![Writeups](https://img.shields.io/badge/completed_writeup-6/15-blue) [![Buy Me a Coffee](https://img.shields.io/badge/Buy%20Me%20a%20Coffee-FFDD00?logo=buy-me-a-coffee&logoColor=black)](https://www.buymeacoffee.com/v4l1k4hn) ![GitHub User's stars](https://img.shields.io/github/stars/valikahn?style=flat&logo=github) ![Discord](https://img.shields.io/discord/521382216299839518?style=flat&logo=discord&color=purple)

This repository contains my personal [TryHackMe](https://tryhackme.com/) writeups, notes, and walkthroughs from completed rooms and learning paths.

The purpose of this repository is to document my methodology, commands, observations, mistakes, and final exploitation paths in a way that is useful for revision, portfolio building, and future reference.

## About This Repository

Each writeup is written from the perspective of a controlled lab environment. The rooms covered here are intentionally vulnerable systems provided by TryHackMe for cybersecurity training.

The IP addresses shown in these writeups were allocated during the TryHackMe labs, with the attack performed either from the TryHackMe AttackBox or from my own Kali Linux VM using OpenVPN connected to the TryHackMe VPN, including the Paris VPN server where noted.

**PLEASE NOTE:** This repository may cover both offensive and defensive learning rooms but is for the Jr Penetration Tester path. The format of each entry will therefore vary according to the subject. For example, an offensive room may focus on enumeration and exploitation, while a defensive room may focus on alert analysis, investigation, detection logic or remediation.

> [!IMPORTANT]
> This repository will **NEVER** contain material taken from TryHackMe professional certification examinations or other restricted assessments. It will **NOT*** provide any flags, passwords, cracked credentials or confidential material that will slow the rate of learning.
> 
> If you are looking for any assistance, answers, guides, specific walkthroughs you will **NOT** find any of those here, help/assistance is limited, but available via the [TryHackMe Discord](https://discord.com/invite/tryhackme).


## What a Write-up May Include

Depending on the room, challenge and learning objective, a write-up may include:

* Room overview and learning objectives
* Scope and authorised target information
* Attacker and target IP address details
* Penetration testing methodology
* Passive and active reconnaissance
* Host, port and service enumeration
* Web application enumeration and testing
* Network service assessment
* Vulnerability identification and research
* Exploit selection and validation
* Initial access methodology
* Shell stabilisation and session management
* Linux or Windows privilege escalation
* Active Directory enumeration and attack techniques
* Credential harvesting and authentication testing
* Lateral movement and pivoting
* Post-exploitation enumeration
* Evidence and sanitised command output
* Flags, credentials and sensitive values marked as `<REDACTED>`
* Technical findings and their potential impact
* Challenges, mistakes and troubleshooting steps
* Lessons learned
* Defensive recommendations and remediation notes
* References and supporting documentation

The level of detail will vary between guided rooms and practical challenges. Write-ups are intended to document the methodology, decision-making process and lessons learned rather than provide a simple list of answers.

No content from the TryHackMe Jr Penetration Tester (PT1) certification examination will be published in this repository.

## Learning Path

Learning Pathway: [Jr Penetration Tester](https://tryhackme.com/path/outline/jrpenetrationtester)

This learning path covers the fundamental skills that will allow you to succeed as a junior penetration tester. Upon completing this path, you will have the practical skills required to perform security assessments against web applications, enterprise networks and active directory.

Learn the essential skills to break into penetration testing.

- Pentesting fundamentals, methodologies and tactics
- Full lifecycle from recon to reporting
- Hands-on web, network and AD hacking
- Learn core tools used in cybersecurity

## Published Writeups

| Section | Challenge | Difficulty | Status |
|---|---|---|---|
| Web Application Vulnerabilities I | [Recruit](https://tryhackme.com/room/recruitwebchallenge) | ![Medium](https://img.shields.io/badge/Medium-orange) | [![Complete](https://img.shields.io/badge/Complete-brightgreen)](https://github.com/Valikahn/TryHackMe-Jr-Penetration-Tester/blob/main/WRITEUPS/recruit_challenge.md) |
| Web Application Vulnerabilities II | [Support](https://tryhackme.com/room/support) | ![Medium](https://img.shields.io/badge/Medium-orange) | [![Complete](https://img.shields.io/badge/Complete-brightgreen)](https://github.com/Valikahn/TryHackMe-Jr-Penetration-Tester/blob/main/WRITEUPS/support_challenge.md) |
| Password Attacks | [Checkmate](https://tryhackme.com/room/checkmate) | ![Easy](https://img.shields.io/badge/Easy-brightgreen) | [![Complete](https://img.shields.io/badge/Complete-brightgreen)](https://github.com/Valikahn/TryHackMe-Jr-Penetration-Tester/blob/main/WRITEUPS/checkmate_challenge.md) |
| Privilege Escalation | [Jump](https://tryhackme.com/room/jump) | ![Easy](https://img.shields.io/badge/Easy-brightgreen) | [![Complete](https://img.shields.io/badge/Complete-brightgreen)](https://github.com/Valikahn/TryHackMe-Jr-Penetration-Tester/blob/main/WRITEUPS/jump_challenge.md) |
| Privilege Escalation | [Windows Jump](https://tryhackme.com/room/windowsjump) | ![Medium](https://img.shields.io/badge/Medium-orange) | [![Complete](https://img.shields.io/badge/Complete-brightgreen)](https://github.com/Valikahn/TryHackMe-Jr-Penetration-Tester/blob/main/WRITEUPS/windows_jump_challenge.md) |
| Active Directory Security Testing Basics | [Proxy](https://tryhackme.com/room/proxychallenge) | ![Easy](https://img.shields.io/badge/Easy-brightgreen) | ![Planned](https://img.shields.io/badge/Planned-lightgrey) |
| Active Directory Security Testing Basics | [Forward](https://tryhackme.com/room/forwardchallenge) | ![Medium](https://img.shields.io/badge/Medium-orange) | ![Planned](https://img.shields.io/badge/Planned-lightgrey) |
| Jr Pentester Challenges | [Domino](https://tryhackme.com/room/domino) | ![Medium](https://img.shields.io/badge/Medium-orange) | ![Planned](https://img.shields.io/badge/Planned-lightgrey) |
| Jr Pentester Challenges | [Silent Monitor](https://tryhackme.com/room/silent-monitor) | ![Medium](https://img.shields.io/badge/Medium-orange) | ![Planned](https://img.shields.io/badge/Planned-lightgrey) |
| Jr Pentester Challenges | [Dead Drop](https://tryhackme.com/room/dead-drop) | ![Medium](https://img.shields.io/badge/Medium-orange) | ![Planned](https://img.shields.io/badge/Planned-lightgrey) |
| Jr Pentester Challenges | [Operation Promotion](https://tryhackme.com/room/operationpromotion) | ![Easy](https://img.shields.io/badge/Easy-brightgreen) | ![Planned](https://img.shields.io/badge/Planned-lightgrey) |
| Jr Pentester Challenges | [Operation Coldstart](https://tryhackme.com/room/operationcoldstart) | ![Easy](https://img.shields.io/badge/Easy-brightgreen) | ![Planned](https://img.shields.io/badge/Planned-lightgrey) |
| Jr Pentester Challenges | [Net Sec Challenge](https://tryhackme.com/room/netsecchallenge) | ![Easy](https://img.shields.io/badge/Easy-brightgreen) | ![Planned](https://img.shields.io/badge/Planned-lightgrey) |
| Jr Pentester Challenges | [Interceptor](https://tryhackme.com/room/interceptor) | ![Medium](https://img.shields.io/badge/Medium-orange) | ![Planned](https://img.shields.io/badge/Planned-lightgrey) |

**Requests**

| Section | Challenge | Status |
|---|---|---|
| Metasploit: Payload Generation | Capstone Challenge | [![Complete](https://img.shields.io/badge/Complete-brightgreen)](https://github.com/Valikahn/TryHackMe-Jr-Penetration-Tester/blob/main/WRITEUPS/capstone_challenge.md) |

### Status Key

| Status | Meaning |
| --- | --- |
| ![Planned](https://img.shields.io/badge/Planned-lightgrey) | The path has been selected but documentation has not started. |
| ![In Progress](https://img.shields.io/badge/In%20Progress-yellow) | Rooms or modules are currently being completed and documented. |
| ![Complete](https://img.shields.io/badge/Complete-brightgreen) | All intended write-ups for the path have been published. |
| ![Archived](https://img.shields.io/badge/Archived-red) | The path or its documentation is no longer actively maintained. |
| ![Host Error](https://img.shields.io/badge/Host_Error-Reported-orange) | A lab or room issue has been encountered and reported. |

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

## Content and Spoiler Policy

These notes may contain spoilers, command output, vulnerability details and complete attack or investigation paths. Anyone actively completing a room should attempt it independently before reading the associated write-up.

This repository will **`NOT`** intentionally publish any of the following:

- TryHackMe flags or answer strings.
- Passwords or cracked credentials.
- Reusable session tokens.
- Private keys or sensitive certificates.
- Certification examination content.
- Copied room instructions or substantial portions of TryHackMe material.
- Material that TryHackMe or a room author has asked learners not to share.

Where a value is necessary to explain the methodology, it will be represented using a placeholder such as `<TARGET_IP>`, `<USERNAME>`, `<EMAIL_ADDRESS>`, `<SESSION_VALUE_REDACTED>`, or `<REDACTED>`.

If restricted or sensitive information is included accidentally, please report it through the repository's GitHub [Discussions](https://github.com/Valikahn/TryHackMe-Jr-Penetration-Tester/discussions) or [Issues](https://github.com/Valikahn/TryHackMe-Jr-Penetration-Tester/issues) area so it can be reviewed and removed.

## Ethical Use Disclaimer

These writeups are for educational purposes only and are based on authorised TryHackMe lab environments.

All tools, commands, techniques, and methodologies referenced in these writeups were used within controlled training environments where permission was provided by the owner and/or operator of the lab platform. The systems discussed are intentionally vulnerable machines designed for cybersecurity learning, practice, and assessment.

Do not use these techniques, tools, or methods against systems, networks, applications, or services that you do not own or do not have explicit written permission to test. Unauthorised access, scanning, exploitation, or disruption of systems is illegal and unethical.

The tools and methods listed in this repository are examples of approaches used during specific rooms or learning exercises. They are not the only possible solutions, and other tools, techniques, or workflows may be used depending on the target environment, room design, and individual methodology.

## Accuracy and Maintenance

TryHackMe periodically updates, replaces or retires rooms and learning paths. Links, room sequences and path content may therefore change after a write-up is published.

Each write-up should be treated as a record of the room as it appeared on the date documented. Where a material change is identified, the relevant page may be updated or marked as archived.

If you notice a broken link, outdated instruction, formatting problem, technical error or any other noticeable issue within a write-up, please report it through the GitHub repository's **[Issues](https://github.com/Valikahn/TryHackMe-Jr-Penetration-Tester/issues)** tab. When raising an issue, include the name of the affected writeup, a brief description of the problem and, where possible, the relevant section or line.

Constructive corrections are welcome and help keep the repository accurate, useful and maintainable.

## Connect With Me

Thanks for checking out my TryHackMe writeups. These notes form part of my ongoing cybersecurity learning journey, where I document rooms, techniques, tools, mistakes and lessons learned while working through different challenges.

You can view my TryHackMe profile here:

[TryHackMe Profile - V4L1K4HN](https://tryhackme.com/p/V4L1K4HN)

I am also active within cybersecurity learning communities, including Discord, where I discuss labs, tools, methodologies and general security topics with other learners and practitioners.

Feel free to follow my progress, compare approaches or get in touch if you are working through similar rooms.

Walkthrough requests are always welcome, although publication will depend on my availability and whether sharing the content complies with the platform's rules.

Created by V4L1K4HN as part of my cybersecurity learning journey through TryHackMe.

## License

Unless otherwise stated, the original written content in this repository is licensed under the [Creative Commons Attribution 4.0 International Licence](https://creativecommons.org/licenses/by/4.0/legalcode.en).

Copyright © 2026 V4L1K4HN.

You may share and adapt the licensed material for any purpose, including commercially, provided that:

- appropriate credit is given to V4L1K4HN;
- a link to the licence is provided; and
- any changes made to the original material are clearly indicated.

This licence applies only to original material created by the repository author. TryHackMe content, branding, room materials, third-party software, trademarks, externally sourced material, and any other third-party intellectual property remain subject to their respective owners' terms and licences.

See the [LICENSE](https://github.com/Valikahn/TryHackMe-Writeups/blob/main/LICENSE) file for the complete legal terms.

---
[!["Buy Me A Coffee"](https://www.buymeacoffee.com/assets/img/custom_images/orange_img.png)](https://buymeacoffee.com/v4l1k4hn)  

**Powered on ☕ made with ❤️ by [V4L1K4HN](https://tryhackme.com/p/V4L1K4HN)**  
⭐ If this project is useful, consider starring it on GitHub.
