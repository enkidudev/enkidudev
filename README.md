# hey, i'm enkidu.

> the wild man learned to enumerate.

Security researcher focused on web, API, network, and Active Directory security.

**PJPT Certified · CPTS Certified · Top 2% on TryHackMe**

Currently pursuing a **BCA in Cyber Security at Lovely Professional University**, expected to graduate in 2028.

I spend most of my time breaking things, building labs, hunting vulnerabilities, developing security tools, and figuring out why stuff works the way it does.

I believe enumeration is an art form. Some people disagree. Those people probably haven't enumerated enough.

---

## security

My primary areas of interest and hands-on experience:

- **Web & API Security:** Vulnerability discovery, authentication flaws, injection attacks, and application security testing.
- **Network Security:** Network enumeration, service exploitation, pivoting, and infrastructure assessments.
- **Active Directory:** Domain enumeration, Kerberos attacks, NTLM relay, ACL abuse, privilege escalation, and domain compromise.
- **Vulnerability Research:** Independent bug bounty hunting, vulnerability analysis, responsible disclosures, and understanding exploit mechanics.
- **Windows Security:** Windows internals, privilege escalation, credential abuse, and post-exploitation.
- **CTFs & Homelabs:** Building environments, developing challenges, breaking them, and occasionally fixing what I broke.

### Active Directory

`BloodHound` · `LDAP` · `Kerberoasting` · `AS-REP Roasting`

`NTLM Relay` · `Pass-the-Hash` · `Pass-the-Ticket` · `ACL Abuse`

`DCSync` · `AD CS` · `Domain Compromise` · `Windows Internals`

I've built custom Active Directory environments and explored complete attack paths, from initial domain enumeration to privilege escalation and domain-level compromise.

---

## things i've built

### [Shredder](https://github.com/enkidudev/shredder)

**Automated reconnaissance and service enumeration.**

A personal security tool developed during my CPTS preparation. Shredder is designed to make reconnaissance faster, more organized, and evidence-driven.

- Fast port discovery using RustScan.
- Nmap-based service fingerprinting and enumeration.
- Evidence-based triage with a customizable rulebook.
- Multiple scanning profiles and organized output.
- Designed to identify meaningful leads without drowning the operator in scan results.

Because apparently, running Nmap manually wasn't enough.

### Ink

**A personal credential notebook for penetration testing engagements.**

Built to organize credentials and authentication discoveries during security assessments.

- Store multiple users and credentials.
- Track credential reuse across hosts and services.
- Append contextual notes to existing records.
- Edit and manage captured entries.
- Export engagement records when needed.

The idea is simple: stop losing useful credentials and the context behind them.

---

## independent security research

I actively explore vulnerability discovery through independent bug bounty research and vulnerability hunting.

- **2 paid bounty outcomes.**
- Approximately **5–6 total reported findings**, including 3–4 validated findings.
- Independent vulnerability disclosures.
- Participation in independent vigilante-style vulnerability hunts.
- Hands-on investigation of web application and infrastructure vulnerabilities.

I enjoy understanding not just that something is vulnerable, but why it happens, how it can be reproduced, and what the actual impact is.

---

## CTF achievements & challenge development

### Competition achievements

- **9 CTF victories.**
- **5 national CTF victories.**
- Top 2% on TryHackMe.

### Challenge development

Created CTF challenges and boot2root environments for **GCS (Ginius Cyber Security Council)**.

My contributions included:

- **Forensics:** Medium, Hard, and Extreme difficulty challenges.
- **Boot2Root:** Easy, Medium, and Hard machines.
- Challenges covering web exploitation and network attack paths.
- Building challenge environments and designing intended exploitation routes.

Received an appreciation letter for contributions to GCS.

---

## home labs & practical experience

### Active Directory attack lab

Designed and maintained a custom Active Directory environment consisting of:

| Host | Role |
|---|---|
| RA01 | Domain Controller |
| Horus01 | Domain workstation |
| Osiris01 | Domain workstation |

The environment included four domain users and multiple deliberately configured attack paths.

Techniques explored and validated included:

- Windows Credential Manager credential discovery.
- LNK file abuse.
- Kerberoasting.
- LLMNR poisoning.
- NTLM relay.
- Credential reuse and lateral movement.
- Privilege escalation and domain compromise.

### Hands-on penetration testing labs

Extensive practical work through Hack The Box, TryHackMe, and custom environments.

Selected Hack The Box machines include:

`Trick` · `Jeeves` · `Fluffy` · `Administrator` · `POV` · `TombWatcher` · `Media` · `Authority` · `Craft` · `Redelegate` · `Snoopy` · `Ghost`

My approach is heavily focused on enumeration, evidence collection, understanding attack paths, and validating impact rather than blindly following exploitation steps.

---

## certifications

| Certification | Status |
|---|---|
| HTB Certified Penetration Testing Specialist (CPTS) | Certified |
| Practical Junior Penetration Tester (PJPT) | Certified |

- [Verify CPTS on Credly](https://www.credly.com/badges/42d1f8ac-4481-4d7f-9eb0-e23ea241822c/public_url)
- [Verify PJPT](https://certified.tcm-sec.com/46c7b3fe-52e3-43b5-a6c5-ea89bf292ccb?key=fcabe8ae0bf92ca6dbe77dd2a6c43e98461ed0745e698c32e0cc78facbf94e60#acc.JEde5BY2)

---

## languages

| Proficiency | Languages |
|---|---|
| **Strong** | C · C++ |
| **Comfortable** | Python · Bash · SQL |
| **Currently learning** | Go · JavaScript |

I primarily use C and C++ for DSA, general programming, and CTF challenges. Python and Bash are my go-to choices for automation and security tooling.

---

## tools & technologies

**Reconnaissance & Enumeration**

Nmap · RustScan · Masscan · NetExec · ffuf · Feroxbuster · Gobuster · enum4linux-ng

**Web & Application Security**

Burp Suite · SQLmap · Nuclei · Nikto

**Active Directory & Windows**

BloodHound · Impacket · Certipy · Kerbrute · Responder · Evil-WinRM · PowerShell

**Exploitation & Post-Exploitation**

Metasploit · Hashcat · John the Ripper · Hydra · Ligolo-ng

**Network Analysis**

Wireshark · TCP/IP · DNS · SMB · LDAP · Kerberos

**Development**

Python · C · C++ · Bash · SQL · Go · JavaScript

---

## writing & research

I document technical investigations, exploitation chains, lessons learned, and security research.

- [Security Writeups](https://github.com/enkidudev/security-writeups)
- [Personal Portfolio](https://enkidudev.github.io/)
- [Shredder on GitHub](https://github.com/enkidudev/shredder)

The writeup repository is connected to my portfolio through GitHub Actions. New published articles are automatically built and deployed to the website.

---

## currently

Exploring vulnerability research, offensive security, exploit development, and building better security tools.

My long-term goal is to grow into a capable Red Team Operator and eventually a security researcher who builds tools, discovers vulnerabilities, and contributes something useful to the community.

If it has an attack surface, I'll probably enumerate it.

---

> still learning. still breaking things. still enumerating.

---

## 🌐 Socials

[![Instagram](https://img.shields.io/badge/Instagram-%23E4405F.svg?logo=Instagram&logoColor=white)](https://instagram.com/enkidu.dev)

[![LinkedIn](https://img.shields.io/badge/LinkedIn-%230077B5.svg?logo=linkedin&logoColor=white)](https://www.linkedin.com/in/arman-cybersec/)

## 💻 Tech Stack

![C](https://img.shields.io/badge/c-%2300599C.svg?style=for-the-badge&logo=c&logoColor=white)
![C++](https://img.shields.io/badge/c++-%2300599C.svg?style=for-the-badge&logo=c%2B%2B&logoColor=white)
![Go](https://img.shields.io/badge/go-%2300ADD8.svg?style=for-the-badge&logo=go&logoColor=white)
![HTML5](https://img.shields.io/badge/html5-%23E34F26.svg?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/css3-%231572B6.svg?style=for-the-badge&logo=css3&logoColor=white)
![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)
![PowerShell](https://img.shields.io/badge/PowerShell-%235391FE.svg?style=for-the-badge&logo=powershell&logoColor=white)
![Bash](https://img.shields.io/badge/bash_script-%23121011.svg?style=for-the-badge&logo=gnu-bash&logoColor=white)
![Windows Terminal](https://img.shields.io/badge/Windows%20Terminal-%234D4D4D.svg?style=for-the-badge&logo=windows-terminal&logoColor=white)
![Apache](https://img.shields.io/badge/apache-%23D42029.svg?style=for-the-badge&logo=apache&logoColor=white)
![Nginx](https://img.shields.io/badge/nginx-%23009639.svg?style=for-the-badge&logo=nginx&logoColor=white)
![SQLite](https://img.shields.io/badge/sqlite-%2307405e.svg?style=for-the-badge&logo=sqlite&logoColor=white)
![MySQL](https://img.shields.io/badge/mysql-4479A1.svg?style=for-the-badge&logo=mysql&logoColor=white)

![Nmap](https://img.shields.io/badge/Nmap-214478?style=for-the-badge&logo=nmap&logoColor=white)
![Burp Suite](https://img.shields.io/badge/Burp%20Suite-FF6633?style=for-the-badge&logo=burpsuite&logoColor=white)
![Wireshark](https://img.shields.io/badge/Wireshark-1679A7?style=for-the-badge&logo=wireshark&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)

## 📊 GitHub Stats

![](https://github-readme-stats.shion.dev/api?username=enkidudev&theme=dark&hide_border=false&include_all_commits=false&count_private=false)

![](https://streak-stats.demolab.com/?user=enkidudev&theme=dark&hide_border=false)

![](https://github-readme-stats.shion.dev/api/top-langs/?username=enkidudev&theme=dark&hide_border=false&include_all_commits=false&count_private=false&layout=compact)

### ✍️ Random Dev Quote

![](https://quotes-github-readme.vercel.app/api?type=horizontal&theme=merko)
