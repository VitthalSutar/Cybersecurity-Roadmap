# 🛡️ Cybersecurity Roadmap: Deep Dive Guide

---

## 🎯 Capture The Flag (CTF) Platforms

CTFs simulate real-world hacking environments to solve challenges across multiple domains: web, crypto, reverse engineering, pwn (binary exploitation), and forensics.

| Platform         | Focus Areas |
|------------------|-------------|
| HackTheBox       | Realistic machines, pentest labs |
| TryHackMe        | Guided learning with rooms and tasks |
| VulnHub          | Offline vulnerable VMs |
| picoCTF          | Beginner-friendly with gamified approach |
| SANS Holiday Hack| Annual festive-themed CTF challenges |

---

## 📜 Certifications

### 🟢 Beginner Level
- **CompTIA A+**: Hardware, OS troubleshooting, basic networking.
- **Linux+**: Linux CLI, permissions, shell scripting.
- **Network+**: OSI model, routing, switching, protocols.
- **CCNA**: Cisco hardware, TCP/IP stack, subnetting, device configuration.
- **Security+**: Threats, vulnerabilities, access control, risk mitigation.

### 🔵 Advanced Level
- **CISSP**: High-level info security, governance, architecture.
- **CISA**: Auditing IT systems.
- **CISM**: Info security management strategies.
- **GSEC, GPEN, GWAPT (GIAC)**: In-depth technical pentesting and security expertise.
- **OSCP**: Hands-on pentest certification with real lab machines.
- **CREST**: Globally respected penetration testing cert.
- **CEH**: Ethical hacking and vulnerability assessment.

---

## 🧱 Virtualization and Network Architecture

### 💡 Concepts
- **VM, Hypervisor, VLAN, NAT, DMZ**  
  Simulate isolated environments for testing. DMZ adds an extra security layer between internal and external networks.

- **ARP, DNS, DHCP, NTP**  
  Network communication relies on these protocols for IP resolution, time sync, and connectivity.

---

## 🌐 Network Design & Topologies

| Topology | Features |
|----------|----------|
| Star     | Central node, easy to manage |
| Ring     | Each node connects in a loop |
| Mesh     | Redundant paths, fault-tolerant |
| Bus      | Simple single cable network |

---

## 🔐 Authentication Techniques

- **Kerberos**: Ticket-based authentication protocol.
- **LDAP**: Directory access for user credentials.
- **SSO**: Single sign-on across services.
- **SSH, RDP**: Remote secure access.
- **FTP/SFTP**: File transfer (SFTP is secure).
- **HTTP/HTTPS**: Web communication (HTTPS is encrypted).
- **SSL/TLS**: Secure sessions via certificates.

---

## 💣 Exploit Frameworks & Hacking Tools

- **Metasploit, Nmap, Burp Suite, Wireshark, John the Ripper**  
  Used for scanning, intercepting, cracking, and analyzing.

### 🎯 Defense Concepts
- **Defense in Depth**: Layered security (physical, network, host, application).
- **Runbooks**: Standard operational procedures during incidents.
- **Threat Hunting**: Proactive detection of threats inside the network.

---

## 🔓 Web Attacks (OWASP Top 10)
| Attack Type | Description |
|-------------|-------------|
| SQL Injection | Injecting SQL queries in input fields |
| XSS           | Injecting scripts into websites |
| CSRF          | Forging requests from authenticated users |
| Buffer Overflow | Overwriting memory boundaries |
| Directory Traversal | Accessing unauthorized directories |
| Privilege Escalation | Elevating access rights |
| Replay Attack | Resending captured data packets |

---

## 🧮 Cryptography Concepts

- **Salting/Hashing**: Prevent password rainbow table attacks.
- **Key Exchange (Diffie-Hellman, RSA)**: Secure key sharing.
- **PKI (Public Key Infrastructure)**: Manages keys and certificates.
- **Obfuscation**: Code or data masking to prevent analysis.

---

## ⚙️ Tools for Discovery & Incident Response

| Tool       | Use |
|------------|-----|
| VirusTotal | Scan URLs/files for malware |
| JoeSandbox | Deep sandbox analysis |
| any.run    | Interactive malware sandbox |
| WHOIS      | Domain registration details |
| netflow/syslog | Network and system logs |
| tcpdump, nmap, nslookup | Packet capture, scanning, name resolution |

---

## ☁️ Cloud & Virtualization Skills

### 🔧 Key Concepts
- **Public vs Private vs Hybrid Cloud**
- **Infrastructure as Code (Terraform, Ansible)**
- **Cloud Providers: AWS, Azure, GCP**
- **Dropbox, OneDrive, Google Drive** – Storage platforms with access controls
- **Serverless** – Functions without managing infrastructure
- **CDN** – Content delivery optimization

---

## 💻 Operating Systems & Networking

| System    | Tasks |
|-----------|-------|
| Windows   | ACLs, registry, PowerShell, patching |
| Linux     | Permissions, iptables, sudoers |
| MacOS     | GUI/CLI navigation, system logs |

### 🛠 Common Commands
- `ipconfig`, `netstat`, `arp`, `tracert`, `tcpdump`, `route`, `grep`, `head`, `memdump`

### 🔀 Subnetting & IP Basics
- `localhost`, `loopback`, `default gateway`, `subnet mask`, `CIDR blocks`, public/private IPs

---

## 🔐 Secure vs Insecure Protocols

| Secure | Insecure |
|--------|----------|
| SFTP   | FTP |
| TLS    | SSL |
| DNSSEC | DNS |
| IPSEC  | IP |
| LDAPS  | LDAP |
| S/MIME | Plain email |

---

## 🚨 Incident Response Stages
1. **Preparation**: Build team, runbooks, tools
2. **Detection/Identification**: Logging, alerting, user reports
3. **Containment**: Isolate affected systems
4. **Eradication**: Remove malware/rootkits
5. **Recovery**: Restore systems and services
6. **Lessons Learned**: Improve posture and documentation

---

## 🔍 Threat Intelligence & Attack Types

| Type         | Description |
|--------------|-------------|
| Phishing     | Fraudulent emails |
| Vishing      | Phone-based phishing |
| Smishing     | SMS-based phishing |
| Whaling      | Targeting high-profile individuals |
| Shoulder Surfing | Observing credentials visually |
| Tailgating   | Unauthorized physical entry |
| Dumpster Diving | Recovering data from trash |
| Drive-by Attack | Malicious code via web visit |
| Typo Squatting | URL impersonation |
| Password Spray | Using common passwords across users |

---

## 🔐 Compliance & Governance
- **HR, Legal, Compliance Teams**
- **Group Policy, ACLs, Patch Management**
- **Risk Frameworks: NIST, ISO, RMF, CSF**
- **SIEM (Security Info & Event Mgmt)**
- **SOAR (Security Orchestration)**

---

## 🔬 Reverse Engineering & Vulnerability Management
- **Malware Analysis**: Using WinHex, FTK Imager, autopsy
- **Sandboxing**: Isolating executables
- **Zero Day vs Known Vulnerabilities**
- **LOLBAS (Living Off the Land Binaries)**: Legit tools used for malicious purposes

---

## 🔁 Blue Team, Red Team, Purple Team
- **Blue Team**: Defense, monitoring, mitigation
- **Red Team**: Offense, exploitation, persistence
- **Purple Team**: Collaboration and feedback loop

---

## 🧠 Frameworks & Models
- **ATT&CK Framework**: MITRE-based techniques and tactics
- **Cyber Kill Chain**: Reconnaissance to exfiltration
- **Diamond Model**: Threat actor-centric analysis

---

## 🧪 Labs & Distros
- **Kali Linux, ParrotOS**: Penetration testing distributions
- **SIEM, IDS/IPS, Honeypots**: Monitoring and analysis infrastructure

---

> ✅ Keep exploring tools, stay updated with trends, and never stop hacking ethically.  
