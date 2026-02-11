# TryHackMe Beginner Roadmap — Curated & Updated

**Maintainer: Dynamo2k1**
**Last updated: February 11, 2026**

This is my curated, hands-on roadmap for beginners who want to become job-ready Junior Security Analysts or Junior Penetration Testers. I built and updated this guide to reflect the 2025–2026 landscape; new emphasis is: Cloud Security, API exploitation, and identity-first defenses for Active Directory environments. Use this as a day-to-day learning plan; one room per day is a realistic pace for steady progress.

---

## How I expect you to use this

1. Start with Pre-Security Fundamentals and the core Foundations so you build a reliable base.
2. Learn Linux, Windows and Networking together; these are the tools you will use constantly.
3. Pick a specialization: Red Team, Blue Team or Reverse Engineering; focus deeply after you finish the fundamentals.
4. For each room: read the description, open the link, finish the lab, write a short note or paste your commands into the repo. Share useful rooms with juniors and keep walkthrough notes here.

---

## Learning strategy (short and practical)

* Do one room per day, take notes, and push a short log to the repo.
* Use the AttackBox or a disposable VM: mistakes are expected; learn from them.
* When stuck, search, read official docs, and try smaller steps; debugging is the skill.
* Practice consistently, not in binges; consistent small wins beat infrequent marathons.

---

## Quick note about formatting

I removed the Status column from the original table; everything else is preserved: Room Name, Difficulty, Link, Description. Links use the canonical `https://tryhackme.com/room/<slug>` format. Verify any critical links before sharing externally.

---

## 🏗️ Pre-Security Fundamentals

### Purpose

This is where everything begins. Skip this and you will struggle later. Here you learn how systems normally behave; that understanding is required to know why something breaks or can be exploited.

### Outcomes

You will gain: OSI and TCP/IP clarity, basic Linux and Windows navigation, virtualization and cloud basics, plus research techniques.

| Room Name                       | Difficulty | Link                                                                                                               | Description                                                         |
| ------------------------------- | ---------: | ------------------------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------- |
| Introductory Researching        |       Easy | [https://tryhackme.com/room/introtoresearch](https://tryhackme.com/room/introtoresearch)                           | Essential Google dorking and research methodologies for hackers.    |
| OpenVPN                         |       Info | [https://tryhackme.com/room/openvpn](https://tryhackme.com/room/openvpn)                                           | Guide to connecting to the THM network using local VPN tools.       |
| Operating Systems: Introduction |       Easy | [https://tryhackme.com/room/operatingsystemsintroduction](https://tryhackme.com/room/operatingsystemsintroduction) | Explore kernels, memory management, and process scheduling.         |
| Virtualisation Basics           |       Easy | [https://tryhackme.com/room/virtualisationbasics](https://tryhackme.com/room/virtualisationbasics)                 | Understand hypervisors, VMs, and container isolation.               |
| Cloud Computing Fundamentals    |       Easy | [https://tryhackme.com/room/cloudcomputingfundamentals](https://tryhackme.com/room/cloudcomputingfundamentals)     | Intro to IaaS, PaaS, SaaS, and cloud security responsibilities.     |
| Starting Out In Cyber Sec       |       Info | [https://tryhackme.com/room/startingoutincybersec](https://tryhackme.com/room/startingoutincybersec)               | Career path overview: Red Team, Blue Team, Incident Response.       |
| Introductory Networking         |       Easy | [https://tryhackme.com/room/introductorynetworking](https://tryhackme.com/room/introtonetworking)             | OSI model, TCP/IP, and common protocols; foundational networking.   |
| Tutorial                        |       Easy | [https://tryhackme.com/room/tutorial](https://tryhackme.com/room/tutorial)                                         | Hands-on guide to using the AttackBox and answering room questions. |
| Search Skills                   |       Easy | [https://tryhackme.com/room/searchskills](https://tryhackme.com/room/searchskills)                                 | Advanced search operator techniques for finding vulnerabilities.    |

---

## 🐧 Linux Fundamentals

### Purpose

Linux runs a huge portion of server infrastructure and many security tools. You must be comfortable in the terminal, not in GUIs.

### Outcomes

You will gain: command-line fluency, permissions, process management, text processing and SSH skills.

| Room Name                 | Difficulty | Link                                                                                                   | Description                                                |
| ------------------------- | ---------: | ------------------------------------------------------------------------------------------------------ | ---------------------------------------------------------- |
| Linux Fundamentals Part 1 |       Easy | [https://tryhackme.com/room/linuxfundamentalspart1](https://tryhackme.com/room/linuxfundamentalspart1) | Terminal basics: ls, cd, files, file operators.            |
| Linux Fundamentals Part 2 |       Easy | [https://tryhackme.com/room/linuxfundamentalspart2](https://tryhackme.com/room/linuxfundamentalspart2) | Flags, arguments, SSH access and file system interactions. |
| Linux Fundamentals Part 3 |       Easy | [https://tryhackme.com/room/linuxfundamentalspart3](https://tryhackme.com/room/linuxfundamentalspart3) | Text editors, wget, scp, process management.               |
| The find command          |       Easy | [https://tryhackme.com/room/thefindcommand](https://tryhackme.com/room/thefindcommand)                 | Deep dive into find; essential for CTFs and privesc.       |
| Bash Scripting            |       Easy | [https://tryhackme.com/room/bashscripting](https://tryhackme.com/room/bashscripting)                   | Automating tasks using Bash scripts and loops.             |
| Linux Modules             |       Easy | [https://tryhackme.com/room/linuxmodules](https://tryhackme.com/room/linuxmodules)                     | Kernel modules and how Linux extends functionality.        |
| Linux Strength Training   |       Easy | [https://tryhackme.com/room/linuxstrengthtraining](https://tryhackme.com/room/linuxstrengthtraining)   | Practice routine to reinforce command proficiency.         |
| Linux CLI Basics          |       Easy | [https://tryhackme.com/room/linuxclibasics](https://tryhackme.com/room/linuxclibasics)                 | Premium walkthrough for deeper CLI comfort and shortcuts.  |

---

## 🪟 Windows Fundamentals

### Purpose

Windows is the primary desktop OS in enterprises. Real-world breaches often begin on Windows endpoints; you must know how Windows works.

### Outcomes

You will gain: NTFS familiarity, Registry basics, UAC and Defender understanding, PowerShell fundamentals.

| Room Name              | Difficulty | Link                                                                                                     | Description                                                |
| ---------------------- | ---------: | -------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------- |
| Windows Fundamentals 1 |       Easy | [https://tryhackme.com/room/windowsfundamentals1xbx](https://tryhackme.com/room/windowsfundamentals1xbx) | Desktop, NTFS, user accounts, Task Manager.                |
| Windows Fundamentals 2 |       Easy | [https://tryhackme.com/room/windowsfundamentals2](https://tryhackme.com/room/windowsfundamentals2)       | System config, UAC, Resource Monitor, Registry intro.      |
| Windows Fundamentals 3 |       Easy | [https://tryhackme.com/room/windowsfundamentals3](https://tryhackme.com/room/windowsfundamentals3)       | Security management, Windows Updates, BitLocker, Defender. |
| Windows Basics         |       Easy | [https://tryhackme.com/room/windowsbasics](https://tryhackme.com/room/windowsbasics)                     | Walkthrough for modern Windows 11 environments.            |
| Windows CLI Basics     |       Easy | [https://tryhackme.com/room/windowsclibasics](https://tryhackme.com/room/windowsclibasics)               | Interacting with the file system using cmd.exe.            |
| PowerShell             |       Easy | [https://tryhackme.com/room/powershell](https://tryhackme.com/room/powershell)                           | Object-oriented shell used for administration and attacks. |

---

## 🌐 Networking

### Purpose

Networking is the highway all attacks and defenses travel on. If you cannot visualize packets, you are guessing.

### Outcomes

You will gain: packet literacy, subnetting, Wireshark/Tcpdump skills, DNS and HTTP understanding.

| Room Name               | Difficulty | Link                                                                                                   | Description                                                 |
| ----------------------- | ---------: | ------------------------------------------------------------------------------------------------------ | ----------------------------------------------------------- |
| Networking              |       Easy | [https://tryhackme.com/room/networking](https://tryhackme.com/room/networking)                         | OSI model, TCP/IP and core services.                        |
| Intro to LAN            |       Easy | [https://tryhackme.com/room/introtolan](https://tryhackme.com/room/introtolan)                         | LAN topologies, ARP, DHCP and local traffic.                |
| HTTP in detail          |       Easy | [https://tryhackme.com/room/httpindetail](https://tryhackme.com/room/httpindetail)                     | Headers, verbs, status codes and request anatomy.           |
| DNS in detail           |       Easy | [https://tryhackme.com/room/dnsindetail](https://tryhackme.com/room/dnsindetail)                       | How domains resolve to IPs, record types and behavior.      |
| Network Traffic Basics  |       Easy | [https://tryhackme.com/room/networktrafficbasics](https://tryhackme.com/room/networktrafficbasics)     | Network Traffic Analysis and log collection fundamentals.   |
| Introductory Networking |       Easy | [https://tryhackme.com/room/introductorynetworking](https://tryhackme.com/room/introductorynetworking) | Core networking concepts and tools overview.                |
| What is Networking?     |       Easy | [https://tryhackme.com/room/whatisnetworking](https://tryhackme.com/room/whatisnetworking)             | Visual basics of packets and routers.                       |
| Dumping Router Firmware |     Medium | [https://tryhackme.com/room/dumpingrouterfirmware](https://tryhackme.com/room/dumpingrouterfirmware)   | Extracting and analyzing firmware from networking hardware. |

---

## 🧠 Web Exploitation

### Purpose

Web applications are the largest public attack surface. Learn how input validation fails and how to abuse it.

### Outcomes

You will gain: SQLi, XSS, IDOR, SSRF basics, Burp Suite workflow and vulnerability chaining.

| Room Name                 | Difficulty | Link                                                                                                 | Description                                            |
| ------------------------- | ---------: | ---------------------------------------------------------------------------------------------------- | ------------------------------------------------------ |
| Django: CVE-2025-64459    |       Easy | [https://tryhackme.com/room/djangocve202564459](https://tryhackme.com/room/djangocve202564459)       | Exploiting ORM leakage in Django.                      |
| Roundcube: CVE-2025-49113 |       Easy | [https://tryhackme.com/room/roundcubecve202549113](https://tryhackme.com/room/roundcubecve202549113) | Webmail vulnerability analysis and exploitation.       |
| OWASP Top 10 (2021/2025)  |       Easy | [https://tryhackme.com/room/owasptopten2025three](https://tryhackme.com/room/owasptopten2025three)   | Core reading: common web risks and mitigation.         |
| OWASP Juice Shop          |       Easy | [https://tryhackme.com/room/owaspjuiceshop](https://tryhackme.com/room/owaspjuiceshop)               | Full-spectrum vulnerable e-commerce app for practice.  |
| Pickle Rick               |       Easy | [https://tryhackme.com/room/picklerick](https://tryhackme.com/room/picklerick)                       | CTF focusing on web enumeration and command injection. |
| Vulnversity               |       Easy | [https://tryhackme.com/room/vulnversity](https://tryhackme.com/room/vulnversity)                     | File upload bypass to reverse shell and privesc.       |
| SQL Injection Lab         |       Easy | [https://tryhackme.com/room/sqlinjectionlab](https://tryhackme.com/room/sqlinjectionlab)             | Dedicated environment for mastering SQLi.              |
| Basic Pentesting          |       Easy | [https://tryhackme.com/room/basicpentesting](https://tryhackme.com/room/basicpentesting)             | Web hacking paired with Linux privilege escalation.    |
| Bolt                      |       Easy | [https://tryhackme.com/room/bolt](https://tryhackme.com/room/bolt)                                   | Authenticated Remote Code Execution on a CMS.          |
| Upload Vulnerabilities    |       Easy | [https://tryhackme.com/room/uploadvulnerabilities](https://tryhackme.com/room/uploadvulnerabilities) | Bypass filters to upload web shells.                   |
| Ignite                    |       Easy | [https://tryhackme.com/room/ignite](https://tryhackme.com/room/ignite)                               | Exploiting Fuel CMS for RCE.                           |
| Walking An Application    |       Info | [https://tryhackme.com/room/walkinganapplication](https://tryhackme.com/room/walkinganapplication)   | Manual review of page source and dev tools.            |

---

## 🛠️ Tooling & Weaponization

### Purpose

Tools are amplifiers; understanding them is what separates beginners from practitioners.

### Outcomes

You will gain: advanced Nmap use, Metasploit basics, brute force techniques, fuzzing, packet inspection.

| Room Name                | Difficulty | Link                                                                                                 | Description                                          |
| ------------------------ | ---------: | ---------------------------------------------------------------------------------------------------- | ---------------------------------------------------- |
| Nmap Live Host Discovery |       Easy | [https://tryhackme.com/room/nmaplivehostdiscovery](https://tryhackme.com/room/nmaplivehostdiscovery) | Using ARP, ICMP and TCP to find live systems.        |
| Nmap                     |       Easy | [https://tryhackme.com/room/nmap](https://tryhackme.com/room/nmap)                                   | NSE scripts, timing templates and firewall evasion.  |
| Metasploit: Introduction |       Easy | [https://tryhackme.com/room/metasploitintro](https://tryhackme.com/room/metasploitintro)             | Framework architecture: modules, payloads and usage. |
| Hydra                    |       Easy | [https://tryhackme.com/room/hydra](https://tryhackme.com/room/hydra)                                 | Parallel login cracker for SSH, FTP and HTTP forms.  |
| Burp Suite: The Basics   |       Easy | [https://tryhackme.com/room/burpsuitebasics](https://tryhackme.com/room/burpsuitebasics)             | Intercepting, modifying and replaying HTTP requests. |
| Wireshark: The Basics    |       Easy | [https://tryhackme.com/room/wiresharkbasics](https://tryhackme.com/room/wiresharkbasics)             | Packet capture basics and filtering.                 |
| RustScan                 |       Easy | [https://tryhackme.com/room/rustscan](https://tryhackme.com/room/rustscan)                           | High-speed port scanning alternative.                |
| ffuf                     |       Easy | [https://tryhackme.com/room/ffuf](https://tryhackme.com/room/ffuf)                                   | Fast web fuzzer for directories and virtual hosts.   |
| TShark                   |       Easy | [https://tryhackme.com/room/tshark](https://tryhackme.com/room/tshark)                               | Command-line Wireshark for automation.               |
| Google Dorking           |       Easy | [https://tryhackme.com/room/googledorking](https://tryhackme.com/room/googledorking)                 | Search techniques to find exposed sensitive data.    |

---

## 🔐 Cryptography & Hashes

### Purpose

If you cannot tell encoding from hashing from encryption, you will misinterpret evidence and mistakes often.

### Outcomes

You will gain: hash identification, cracking practice, encryption basics, and PKI awareness.

| Room Name                  | Difficulty | Link                                                                                                     | Description                                      |
| -------------------------- | ---------: | -------------------------------------------------------------------------------------------------------- | ------------------------------------------------ |
| Crack the hash             |       Easy | [https://tryhackme.com/room/crackthehash](https://tryhackme.com/room/crackthehash)                       | Identifying and cracking MD5, SHA and similar.   |
| Crack The Hash Level 2     |     Medium | [https://tryhackme.com/room/crackthehashlevel2](https://tryhackme.com/room/crackthehashlevel2)           | Advanced formats and Hashcat workflows.          |
| Cryptography for Dummies   |       Info | [https://tryhackme.com/room/cryptographyfordummies](https://tryhackme.com/room/cryptographyfordummies)   | Symmetric vs asymmetric and basic theory.        |
| Agent Sudo                 |       Easy | [https://tryhackme.com/room/agentsudo](https://tryhackme.com/room/agentsudo)                             | CTF: steganalysis and archive password cracking. |
| Brute It                   |       Easy | [https://tryhackme.com/room/bruteit](https://tryhackme.com/room/bruteit)                                 | Automated brute-force against web login forms.   |
| Attacks on Encrypted Files |       Easy | [https://tryhackme.com/room/attacksonencryptedfiles](https://tryhackme.com/room/attacksonencryptedfiles) | Cracking password-protected archives and PDFs.   |
| Encryption - Crypto 101    |       Info | [https://tryhackme.com/room/encryptioncrypto101](https://tryhackme.com/room/encryptioncrypto101)         | SSH keys, GPG and basic PKI concepts.            |

---

## ⏫ Privilege Escalation

### Purpose

Initial access is only the start; privilege escalation is how you gain authority and control inside a system.

### Outcomes

You will gain: systematic enumeration, SUID and service abuse, scheduled tasks exploitation and kernel exploit awareness.

| Room Name            | Difficulty | Link                                                                                           | Description                                       |
| -------------------- | ---------: | ---------------------------------------------------------------------------------------------- | ------------------------------------------------- |
| Linux PrivEsc        |     Medium | [https://tryhackme.com/room/linuxprivesc](https://tryhackme.com/room/linuxprivesc)             | Comprehensive Linux escalation techniques.        |
| Windows PrivEsc      |     Medium | [https://tryhackme.com/room/windowsprivesc](https://tryhackme.com/room/windowsprivesc)         | Services, Registry and DLL abuse on Windows.      |
| Blaster              |       Easy | [https://tryhackme.com/room/blaster](https://tryhackme.com/room/blaster)                       | Windows privesc focusing on persistence.          |
| Ignite               |       Easy | [https://tryhackme.com/room/ignite](https://tryhackme.com/room/ignite)                         | Rooting CentOS via misconfiguration and exploits. |
| Kenobi               |       Easy | [https://tryhackme.com/room/kenobi](https://tryhackme.com/room/kenobi)                         | Samba enumeration, SUID and path hijacking.       |
| Sudo Security Bypass |       Easy | [https://tryhackme.com/room/sudosecuritybypass](https://tryhackme.com/room/sudosecuritybypass) | Sudo logic flaws and CVE-based techniques.        |
| Common Linux Privesc |     Medium | [https://tryhackme.com/room/commonlinuxprivesc](https://tryhackme.com/room/commonlinuxprivesc) | Hands-on misconfiguration exploitation practice.  |

---

## 🏛️ Active Directory

### Purpose

Active Directory controls identity at scale; compromising it compromises the organization.

### Outcomes

You will gain: AD enumeration, Kerberos attack techniques, lateral movement and BloodHound usage.

| Room Name                | Difficulty | Link                                                                                                   | Description                                                   |
| ------------------------ | ---------: | ------------------------------------------------------------------------------------------------------ | ------------------------------------------------------------- |
| Attacktive Directory     |     Medium | [https://tryhackme.com/room/attacktivedirectory](https://tryhackme.com/room/attacktivedirectory)       | Complete AD enumeration and exploitation guide.               |
| Post-Exploitation Basics |       Easy | [https://tryhackme.com/room/postexploitationbasics](https://tryhackme.com/room/postexploitationbasics) | Maintaining access and pivoting methodologies.                |
| Blue                     |       Easy | [https://tryhackme.com/room/blue](https://tryhackme.com/room/blue)                                     | Exploiting EternalBlue and SMB weaknesses.                    |
| Ice                      |       Easy | [https://tryhackme.com/room/ice](https://tryhackme.com/room/ice)                                       | Legacy media server exploitation and RCE concepts.            |
| CVE-2022-26923           |     Medium | [https://tryhackme.com/room/cve202226923](https://tryhackme.com/room/cve202226923)                     | Active Directory Certificate Services exploitation.           |
| Enterprise               |     Medium | [https://tryhackme.com/room/enterprise](https://tryhackme.com/room/enterprise)                         | Corporate network simulation with lateral movement scenarios. |

---

## 🔍 Blue Team / Forensics

### Purpose

Knowing how attacks are detected will make you a stronger operator on either side; Blue Team skills are highly demanded.

### Outcomes

You will gain: log analysis, SIEM queries, disk and memory forensics, and incident response workflows.

| Room Name             | Difficulty | Link                                                                                               | Description                                     |
| --------------------- | ---------: | -------------------------------------------------------------------------------------------------- | ----------------------------------------------- |
| First Shift CTF       |       Easy | [https://tryhackme.com/room/first-shift-ctf](https://tryhackme.com/room/first-shift-ctf)           | Blue team scenarios simulating a SOC shift.     |
| Digital Footprint     |       Easy | [https://tryhackme.com/room/digitalfootprint](https://tryhackme.com/room/digitalfootprint)         | OSINT challenge for tracking online presence.   |
| The Phishing Pond     |       Easy | [https://tryhackme.com/room/thephishingpond](https://tryhackme.com/room/thephishingpond)           | Analyzing email headers and malicious links.    |
| Splunk: The Basics    |       Easy | [https://tryhackme.com/room/splunkbasics](https://tryhackme.com/room/splunkbasics)                 | Searching and visualizing data in Splunk.       |
| Investigating Windows |       Easy | [https://tryhackme.com/room/investigatingwindows](https://tryhackme.com/room/investigatingwindows) | Identifying artifacts of compromise on Windows. |
| Forensics             |     Medium | [https://tryhackme.com/room/forensics](https://tryhackme.com/room/forensics)                       | Disk forensics and file analysis methodology.   |
| Autopsy               |     Medium | [https://tryhackme.com/room/autopsy](https://tryhackme.com/room/autopsy)                           | Using Autopsy for drive analysis.               |
| Volatility            |     Medium | [https://tryhackme.com/room/volatility](https://tryhackme.com/room/volatility)                     | Memory forensics: analyzing raw memory images.  |

---

## 🔬 Reverse Engineering & Malware

### Purpose

Reverse engineering deepens your understanding of how software behaves and how malware is built.

### Outcomes

You will gain: assembly basics, static and dynamic analysis, Ghidra and Radare2 usage, and binary patching skills.

| Room Name            | Difficulty | Link                                                                                             | Description                                           |
| -------------------- | ---------: | ------------------------------------------------------------------------------------------------ | ----------------------------------------------------- |
| Intro to x86-64      |       Easy | [https://tryhackme.com/room/introtox8664](https://tryhackme.com/room/introtox8664)               | CPU registers, instructions and memory layout basics. |
| CC: Ghidra           |     Medium | [https://tryhackme.com/room/ccghidra](https://tryhackme.com/room/ccghidra)                       | Introduction to Ghidra for static analysis.           |
| CC: Radare2          |     Medium | [https://tryhackme.com/room/ccradare2](https://tryhackme.com/room/ccradare2)                     | Command-line reverse engineering basics.              |
| Reverse Engineering  |     Medium | [https://tryhackme.com/room/reverseengineering](https://tryhackme.com/room/reverseengineering)   | Practice cracking protections on binaries.            |
| Malware Introductory |       Easy | [https://tryhackme.com/room/malwareintroductory](https://tryhackme.com/room/malwareintroductory) | Safe methodology for malware analysis.                |
| Reversing ELF        |       Easy | [https://tryhackme.com/room/reversingelf](https://tryhackme.com/room/reversingelf)               | Cracking Linux executables, CTF style.                |

---

## 🚩 CTF Practice

### Purpose

CTFs force you to apply your knowledge in the wild; they build resilience and problem solving under pressure.

### Outcomes

You will gain: structured attack methodology, troubleshooting, and the ability to pivot strategies.

| Room Name                 | Difficulty | Link                                                                                                   | Description                                          |
| ------------------------- | ---------: | ------------------------------------------------------------------------------------------------------ | ---------------------------------------------------- |
| RootMe                    |       Easy | [https://tryhackme.com/room/rootme](https://tryhackme.com/room/rootme)                                 | Classic web exploitation and Linux privesc practice. |
| Simple CTF                |       Easy | [https://tryhackme.com/room/simplectf](https://tryhackme.com/room/simplectf)                           | CMS exploit, SSH login and Vim privesc.              |
| Bounty Hacker             |       Easy | [https://tryhackme.com/room/bountyhacker](https://tryhackme.com/room/bountyhacker)                     | FTP enumeration and brute force practice.            |
| Love at First Breach 2026 |     Medium | [https://tryhackme.com/room/loveatfirstbreach2026](https://tryhackme.com/room/loveatfirstbreach2026)   | Advanced track CTF challenge.                        |
| Wgel CTF                  |       Easy | [https://tryhackme.com/room/wgelctf](https://tryhackme.com/room/wgelctf)                               | Exfiltration via wget and sudo abuse.                |
| LazyAdmin                 |       Easy | [https://tryhackme.com/room/lazyadmin](https://tryhackme.com/room/lazyadmin)                           | CMS enumeration and backup script exploitation.      |
| Advent of Cyber 2025 Prep |       Easy | [https://tryhackme.com/room/adventofcyberpreptrack](https://tryhackme.com/room/adventofcyberpreptrack) | Warm-up tasks across domains.                        |
| Mr Robot CTF              |     Medium | [https://tryhackme.com/room/mrrobotctf](https://tryhackme.com/room/mrrobotctf)                         | Wordpress exploitation and hash cracking.            |
| Agent Sudo                |       Easy | [https://tryhackme.com/room/agentsudo](https://tryhackme.com/room/agentsudo)                           | User-Agent tricks and zip cracking.                  |

---

## 🗓️ Special Events & Misc

### Purpose

Events give fast, mixed-topic exposure and help you adapt quickly.

### Outcomes

You will gain: breadth, seasonal challenge experience, and quick problem-solving.

| Room Name            | Difficulty | Link                                                                                         | Description                                    |
| -------------------- | ---------: | -------------------------------------------------------------------------------------------- | ---------------------------------------------- |
| Advent of Cyber 2024 |       Easy | [https://tryhackme.com/room/adventofcyber2024](https://tryhackme.com/room/adventofcyber2024) | 24 daily challenges covering all domains.      |
| Advent of Cyber 2023 |       Easy | [https://tryhackme.com/room/adventofcyber2023](https://tryhackme.com/room/adventofcyber2023) | Archive of daily beginner challenges.          |
| Android Hacking 101  |     Medium | [https://tryhackme.com/room/androidhacking101](https://tryhackme.com/room/androidhacking101) | Exploiting ADB, APKs and Android basics.       |
| Git Happens          |     Medium | [https://tryhackme.com/room/githappens](https://tryhackme.com/room/githappens)               | Finding exposed .git repositories and secrets. |
| OhSINT               |       Easy | [https://tryhackme.com/room/ohsint](https://tryhackme.com/room/ohsint)                       | OSINT challenge using images and metadata.     |

---

## Contributing

Found a broken link, or want to suggest a room: open a PR, add the room under the relevant domain, and mention `@Dynamo2k1`. I will review and merge updates that keep the roadmap clear and beginner-friendly.

