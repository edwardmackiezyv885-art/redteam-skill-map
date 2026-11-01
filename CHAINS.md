# 17 条链的阶段总览

按执行顺序排列。每条链的阶段在 `chains/` 下有详细表格。

## 1. Recon Chain

- 目录名：`探测类-侦察信息收集`
- 阶段数：17
- 详解：[chains/recon.md](chains/recon.md)

1. CMS Fingerprinting
2. GitHub & Code Leak Search
3. JS Source & API Extraction
4. WAF & CDN Detection
5. Cloud Asset Discovery
6. 内容与目录发现
7. Parameter & Endpoint Discovery
8. Employee & Supply Chain Intel
9. Subdomain Takeover Detect
10. Subdomain Enumeration
11. Tech Stack Fingerprinting
12. Service Version Fingerprint
13. Directory Discovery
14. Port & Service Scan
15. Passive Recon & OSINT
16. CT Log Enumeration
17. Asset Screenshot & Archive

## 2. Web Attack Chain

- 目录名：`Web攻击类`
- 阶段数：25
- 详解：[chains/web-attack.md](chains/web-attack.md)

1. API Attacks
2. CORS Misconfig
3. CRLF Injection
4. CSRF
5. GraphQL Attacks
6. JWT Attack
7. NoSQL Injection
8. OAuth & SSO Attacks
9. SQL Injection
10. SSRF
11. WebSocket Attacks
12. Web Vulnerability Scanners
13. XSS & Front-End Attacks
14. XXE
15. Command Injection
16. 子域名接管
17. File Upload Attack
18. File Inclusion LFI/RFI
19. SSTI
20. Source Leak & Version Control
21. Clickjacking
22. Directory Discovery
23. Cache Poisoning & Host Header
24. Auth & Session Attacks
25. Business Logic Flaws

## 3. Linux PrivEsc Chain

- 目录名：`Linux提权类`
- 阶段数：10
- 详解：[chains/linux-privesc.md](chains/linux-privesc.md)

1. Capabilities & Permissions
2. Docker & Container Escape
3. NFS & Shared Dir
4. PATH & Env Hijack
5. SUID & Privileged Binaries
6. Sudo Abuse
7. Kernel Exploitation
8. Writable Files & Config
9. Cron Job Hijacking
10. PrivEsc Enumeration

## 4. Domain Infiltration Chain

- 目录名：`Windows-AD攻击类`
- 阶段数：14
- 详解：[chains/domain-infiltration.md](chains/domain-infiltration.md)

1. AD Reconnaissance
2. AS-REP Roasting
3. BloodHound Domain Analysis
4. GPP & Group Policy Attacks
5. Kerberoasting
6. LDAP Query & Enumeration
7. NTLM Relay Attacks
8. SMB Attacks
9. Credential Theft
10. Pass-the-Hash/Ticket
11. Domain Persistence
12. Lateral Movement
13. Email & Exchange Attacks
14. Golden & Silver Tickets

## 5. Cloud Attack Chain

- 目录名：`云平台攻击类`
- 阶段数：10
- 详解：[chains/cloud-attack.md](chains/cloud-attack.md)

1. AWS Attacks
2. Azure Attacks
3. GCP Attacks
4. IAM & Privilege Escalation
5. Serverless Attacks
6. Cloud Metadata & SSRF
7. Cloud Storage Bucket Attack
8. Cloud Key & Credential Attacks
9. Cloud Config Audit
10. Container & K8s Attacks

## 6. Credential Breach Chain

- 目录名：`爆破类-口令哈希破解`
- 阶段数：14
- 详解：[chains/credential-breach.md](chains/credential-breach.md)

1. FTP/SMB/Mail Brute Force
2. GPU & Distributed Cracking
3. SSH/RDP Brute Force
4. Web Login Brute Force
5. Credential Spraying
6. Archive & Document Password
7. Hash ID & Conversion
8. Online Brute Force
9. Wordlist & Rule Generation
10. Database Brute Force
11. Wireless Brute Force
12. Special Format Cracking
13. Offline Hash Cracking
14. 线下哈希破解

## 7. Exploit Chain

- 目录名：`利用类-漏洞利用`
- 阶段数：12
- 详解：[chains/exploit.md](chains/exploit.md)

1. ROP Chain Construction
2. Shellcode Crafting
3. Targeted Web Exploitation
4. Memory Shell Injection
5. Backdoors & Webshells
6. Client-Side Attacks
7. Stack & Heap Exploitation
8. Format String Exploitation
9. Exploit Development
10. Exploit Frameworks
11. Vuln Reproduction & POC
12. Device & Protocol Exploitation

## 8. Network Control Chain

- 目录名：`网络中间人类`
- 阶段数：10
- 详解：[chains/network-control.md](chains/network-control.md)

1. ARP/DNS Spoofing
2. DHCP Attacks
3. TLS/SSH Auditing
4. VLAN Hopping & L2
5. Protocol Exploitation
6. Slow DoS & Flooding
7. Packet Capture & Protocol Analysis
8. Wireless Attacks
9. Traffic Replay & Editing
10. Bluetooth & NFC Attacks

## 9. Reverse Engineering Chain

- 目录名：`逆向分析类`
- 阶段数：11
- 详解：[chains/reverse-engineering.md](chains/reverse-engineering.md)

1. .NET & Java Reverse Engineering
2. ELF File Analysis
3. PE File Analysis
4. Packing & Unpacking
5. Dynamic Debugging
6. Firmware Analysis
7. Cryptographic Algorithm Identification
8. Malware Sample Analysis
9. Obfuscation Deobfuscation
10. Runtime Hook & Injection
11. Static Analysis

## 10. Mobile Attack Chain

- 目录名：`移动端攻击类`
- 阶段数：7
- 详解：[chains/mobile-attack.md](chains/mobile-attack.md)

1. APK Static Analysis
2. App Dynamic Debugging
3. Frida Hook & Injection
4. Mobile Data Storage Leak
5. Mobile Traffic Analysis & Capture
6. Mobile Pentesting Frameworks
7. Mobile Network Layer Attack

## 11. Intelligence Chain

- 目录名：`漏洞数据库类`
- 阶段数：6
- 详解：[chains/intelligence.md](chains/intelligence.md)

1. Zero-Day & Wild Exploitation
2. CVE / NVD Official
3. Vendor Security Advisories
4. Exploit Code Repositories
5. Threat Intelligence & Alerts
6. Vulnerability Aggregators

## 12. Framework Chain

- 目录名：`综合框架类`
- 阶段数：5
- 详解：[chains/framework.md](chains/framework.md)

1. C2 Frameworks
2. Collaboration & Reporting
3. Multi-Purpose Attack Frameworks
4. Pentesting Distributions
5. Vulnerability Management

## 13. Methodology Chain

- 目录名：`方法论框架类`
- 阶段数：7
- 详解：[chains/methodology.md](chains/methodology.md)

1. Threat Modeling & Tactics
2. Report Template & Writing
3. Testing Standards
4. Pentesting Workflow
5. CVSS Scoring
6. Bug Bounty & SRC
7. Red Team Operations

## 14. Lab & Training Chain

- 目录名：`靶场漏洞环境类`
- 阶段数：7
- 详解：[chains/lab-training.md](chains/lab-training.md)

1. Active Directory Labs
2. CTF Platforms
3. Web Vulnerability Labs
4. Binary & PWN Labs
5. Cloud Security Labs
6. Red vs Blue Platforms
7. Vulnerability Reproduction

## 15. Evasion Chain

- 目录名：`免杀规避类`
- 阶段数：7
- 详解：[chains/evasion.md](chains/evasion.md)
- ⚠️ 仅公开目录，内容不展开

阶段名（不展开）：DLL Hijacking & Sideloading、Shellcode Encryption & Encoding、Sandbox & EDR Evasion、Living Off The Land、Signature & Pattern Bypass 等

## 16. Social Engineering Chain

- 目录名：`社工钓鱼类`
- 阶段数：13
- 详解：[chains/social-engineering.md](chains/social-engineering.md)
- ⚠️ 仅公开目录，内容不展开

阶段名（不展开）：OAuth Phishing、QR Code Phishing、Smishing / SMS Phishing、USB Drop / Rubber Ducky、Vishing / Voice Phishing 等

## 17. Exfiltration Chain

- 目录名：`数据渗出类`
- 阶段数：6
- 详解：[chains/exfiltration.md](chains/exfiltration.md)
- ⚠️ 仅公开目录，内容不展开

阶段名（不展开）：C2 Channel Establishment、DNS Tunneling、HTTP/HTTPS Tunneling、ICMP Tunneling、Stego Exfiltration 等
