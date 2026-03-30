## 🎓 Certifications

**SANS Cyber Academy** - Scholarship Recipient `08/2025 – 05/2026`

| Certification | Status |
|---|---|
| GIAC GCIH | 🔄 Expected May 2026 |
| GIAC GSEC | ✅ Feb 2026 |
| GIAC GFACT | ✅ Nov 2025 |

---
## 🛠️ Skills & Tools
**API:** NIST NVD · Microsoft MSRC · Shodan · VulnDB
**Security Operations:** Incident response · Alert triage · Log analysis · Threat detection  
**Security Tools:** Splunk · Wazuh · theHive · Tenable · Caldera · Ansible · Burp Suite · Metasploit  
**Cloud & Infra:** AWS (EC2) · Oracle Cloud (OCI) · Azure Active Directory · Cloud SIEM pipelines  
**Networking:** TCP/IP · DNS · DHCP · Packet analysis · Network hardening · Firewall concepts  
**OS:** Linux · macOS · Windows  
**Programming:** JavaScript · Python · Bash · Rust · Swift

---
## 🏆 CTFs & Competitions

| Event | Date | Result |
|---|---|---|
| AWS × SANS CTF | March 2026 | 🥈 32nd / 600+ |
| Snyk Annual CTF | February 2026 | 🥈 68th / 1,608 |
| SANS Holiday Hack Challenge | December 2025 | ✅ 19 / 25 challenges completed |

---
## 📅 Conferences & Community

- BSides Baltimore - April 2026
- SANS Community Night, MD - Feb 2026
- SANS Community Night, DC - Dec 2025

---
## 🔬 Projects

### 🟣 Adversary Emulation & Detection Lab *(Purple Team Home Lab - In Progress)*
Building an end-to-end purple team environment with automated red team scenario generation and LLM-powered detection-as-code. Details coming soon.

---
### ⌚ Cryptographic Network Security: Apple Watch Audio Streaming AI Assistant
[![Watch the Apple Watch Demo](https://raw.githubusercontent.com/hiCozyty/blog/github-compat-post/static/blogImages/blog2/applewatchblog.png)](https://github.com/hiCozyty/blog/blob/github-compat-post/src/lib/posts/2.md)

[Github .md post](https://github.com/hiCozyty/blog/blob/github-compat-post/src/lib/posts/2.md)


Designed and implemented a defense-in-depth security stack for real-time audio streaming between an Apple Watch and a home server.

- Custom **X.509 PKI enrollment workflow** with mutual TLS (mTLS) - LAN-only enrollment tied to physical proximity
- **AES-128-GCM** encrypted UDP transport with cryptographic nonce derivation and replay protection via sequence numbers
- Certificate-based identity using the Apple Watch **Secure Enclave** (private key never leaves hardware)
- Three-port architecture separating enrollment, session auth, and media transport
- Integrated **LangGraph** AI assistant as the application layer

`BunJS` `watchOS` `X.509 / mTLS` `AES-128-GCM` `UDP` `LangGraph`

---
### 📊 SIEM Lab: Splunk on Oracle Cloud Infrastructure
[![SIEM Lab](https://raw.githubusercontent.com/hiCozyty/blog/github-compat-post/static/blogImages/blog1/oracle_lab.jpg)](https://github.com/hiCozyty/blog/blob/github-compat-post/src/lib/posts/1.md)

[Github .md post](https://github.com/hiCozyty/blog/blob/github-compat-post/src/lib/posts/1.md)


Deployed a cloud-based SIEM pipeline with secure log forwarding and automated rate-limit enforcement.

- Provisioned OCI free-tier instances with **Tailscale ACL** network segmentation
- Automated log collection pipeline: `rsyslog` → `rsync` → `logrotate` → **Splunk Universal Forwarder**
- Built an **OCI SDK shell script** that monitors log volume and enforces API-based ingress lockdown to stay within Splunk's 500 MB/day free-tier limit
- Built **SPL dashboards** to visualize live SSH brute-force trends by source IP, geolocation, and daily occurrence rate

`Splunk` `OCI` `Tailscale` `rsync` `rsyslog` `Bash` `OCI CLI`

---
