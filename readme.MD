<div align="center">

<!-- Cyber Telemetry Dynamic Header Banner -->
<img src="https://capsule-render.vercel.app/api?type=waving&color=0:040d1a,35:0b2545,70:134e4a,100:10b981&height=220&section=header&text=Muhammad%20Syafiq&fontSize=42&fontColor=ffffff&fontAlignY=38&desc=SOC%20Analyst%20%C2%B7%20Defensive%20Security%20%C2%B7%20Detection%20Engineering&descFontSize=17&descAlignY=62&descColor=6ee7b7" width="100%" alt="Header Banner"/>

<!-- Dynamic Typing Subtitle -->
<a href="https://charming-squirrel-bcff68.netlify.app/">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=17&pause=1200&color=10B981&center=true&vCenter=true&width=680&lines=Tier-1+%2F+Tier-2+SOC+Analyst+Ready;High-Fidelity+SIEM+Correlation+(Splunk+SPL%2C+Wazuh%2C+KQL);Host+Telemetry+(Sysmon%2C+EVTX)+%26+PCAP+Deep+Inspection;Adversary+TTP+Mapping+via+MITRE+ATT%26CK;Detection+Engineering+(Sigma%2C+YARA%2C+Custom+Rules);Bridging+Defensive+Security+with+Full-Stack+Engineering" alt="Typing SVG" />
</a>

<p align="center">
  <a href="https://charming-squirrel-bcff68.netlify.app/">
    <img src="https://img.shields.io/badge/Live_Portfolio-10b981?style=for-the-badge&logo=google-chrome&logoColor=white" alt="Live Portfolio"/>
  </a>
  <a href="https://github.com/icebergf6">
    <img src="https://img.shields.io/badge/GitHub_Profile-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub Profile"/>
  </a>
  <a href="https://linkedin.com/">
    <img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn Profile"/>
  </a>
  <a href="mailto:analyst.leosyafiq.soc@proton.me">
    <img src="https://img.shields.io/badge/Proton_Mail-6D4AFF?style=for-the-badge&logo=protonmail&logoColor=white" alt="Proton Mail"/>
  </a>
  <a href="https://tryhackme.com">
    <img src="https://img.shields.io/badge/TryHackMe-Top_5%25_Global-C71A22?style=for-the-badge&logo=tryhackme&logoColor=white" alt="TryHackMe"/>
  </a>
</p>

<p align="center">
  <img src="https://komarev.com/ghpvc/?username=icebergf6&style=flat-square&color=10b981&label=TELEMETRY+PROFILE+VIEWS" alt="Profile Telemetry Views"/>
  <img src="https://img.shields.io/badge/Status-Operational%20%2F%20Ready%20for%20Hire-success?style=flat-square&logo=target" alt="Status"/>
  <img src="https://img.shields.io/badge/Location-Jakarta%20(UTC%2B7)-blue?style=flat-square&logo=googlemaps&logoColor=white" alt="Location"/>
</p>

</div>

---

## ⚡ Operational Status & Identity

```yaml
soc_operator:
  handle: icebergf6
  name: Muhammad Syafiq
  operational_role: "SOC Analyst (Tier-1 / Tier-2) · Detection & Incident Triage"
  time_zone: "Asia/Jakarta (UTC+7) [Open to Global / Remote Work]"
  primary_mission: "Drive down MTTD/MTTR by transforming raw multi-source telemetry into high-fidelity detections."
  
  core_frameworks:
    - "MITRE ATT&CK (Adversary TTP Mapping & Threat Hunting)"
    - "NIST SP 800-61 Rev. 2 (Computer Security Incident Handling)"
    - "Cyber Kill Chain (Lockheed Martin)"
    - "MITRE D3FEND (Countermeasure & Hardening Matrix)"
    
  tactical_competencies:
    - "Multi-Tenant SIEM/XDR Alert Engineering & False Positive Tuning"
    - "Endpoint Forensics: Sysmon, Windows EVTX (4624/4625/4688/4769), Linux auth.log"
    - "Network Protocol Dissection: Wireshark PCAP carving, Zeek conn/ssl/dns logs"
    - "Threat Intel & Defanging: VirusTotal API, AbuseIPDB, Any.Run Sandbox Analysis"
    - "AppSec Hardening: OWASP Top 10, Row-Level Security, BOLA/IDOR Mitigation"
```

---

## 🎯 Certifications & Verified Credentials

<div align="center">

| Credential | Issuing Body | Specialization / Focus | Status |
| :--- | :--- | :--- | :---: |
| **Blue Team Level 1 (BTL1)** | Security Blue Team | Incident Response, Digital Forensics, SIEM, Phishing | **Active** |
| **CompTIA Security+ (SY0-701)** | CompTIA | Core Infosec, Threat Intelligence & Risk Mitigation | **Active** |
| **SC-200: Security Operations Analyst** | Microsoft | Microsoft Sentinel, KQL & Defender XDR Engineering | **Active** |
| **Splunk Core Certified Power User** | Splunk | Complex SPL Searches, Event Correlation & Alert Tuning | **Active** |
| **Top 5% Global Ranking** | TryHackMe | Practical Blue Team Labs, Threat Hunting & Windows Triage | **Verified** |
| **Sherlocks & Blue Track Labs** | Hack The Box | Memory Forensics, Compromised Linux/AD Investigations | **Verified** |

</div>

---

## 🔬 Incident Response & Triage Pipeline

Defensive workflow executing high-fidelity verification, forensic correlation, and rapid containment:

```mermaid
flowchart TD
    classDef alert fill:#1e293b,stroke:#0ea5e9,stroke-width:2px,color:#f8fafc;
    classDef triage fill:#1e293b,stroke:#f59e0b,stroke-width:2px,color:#f8fafc;
    classDef fp fill:#064e3b,stroke:#10b981,stroke-width:2px,color:#a7f3d0;
    classDef tp fill:#7f1d1d,stroke:#ef4444,stroke-width:2px,color:#fecaca;
    classDef forensic fill:#1e1b4b,stroke:#818cf8,stroke-width:2px,color:#e0e7ff;
    classDef contain fill:#581c87,stroke:#a855f7,stroke-width:2px,color:#f3e8ff;
    classDef report fill:#134e4a,stroke:#14b8a6,stroke-width:2px,color:#ccfbf1;

    A["🚨 Telemetry Ingestion & SIEM Alert<br/><i>(Wazuh / Splunk / Sentinel / Sysmon)</i>"]:::alert --> B{"🔍 Tier-1 Alert Triage<br/><i>(Scope, User Context & Reputation Check)</i>"}:::triage
    
    B -->|Benign Noise / Expected Behavior| C["✅ False Positive Resolution<br/><i>Tune Alert Thresholds & Whitelist Known Service</i>"]:::fp
    
    B -->|Verified Adversary Activity| D["⚠️ True Positive: Confirmed Incident<br/><i>Escalate to Incident Response (NIST SP 800-61)</i>"]:::tp
    
    D --> E["🔬 Deep Forensic & Telemetry Correlation<br/><i>Sysmon Process Trees · Wireshark PCAPs · Zeek Transcripts</i>"]:::forensic
    
    E --> F["🗺️ Adversary TTP Tagging<br/><i>Map IoCs & Behaviors against MITRE ATT&CK Matrix</i>"]:::forensic
    
    F --> G["🛡️ Active Containment & Eradication<br/><i>Host Network Isolation · Revoke Tokens · Block C2 Egress</i>"]:::contain
    
    G --> H["📝 Post-Mortem & Detection Engineering<br/><i>Author Sigma/YARA Rule · Defang IoCs · Apply Hardening GPO</i>"]:::report
```

---

## 🧰 Security Operations Stack & Technical Arsenal

### 🔍 SIEM, XDR & Log Management
<p>
  <img src="https://img.shields.io/badge/Wazuh-XDR_&_SIEM-007ACC?style=flat-square&logo=wazuh&logoColor=white" alt="Wazuh"/>
  <img src="https://img.shields.io/badge/Splunk-SPL_Correlation-FF8800?style=flat-square&logo=splunk&logoColor=white" alt="Splunk"/>
  <img src="https://img.shields.io/badge/Elasticsearch-ELK_Stack-005571?style=flat-square&logo=elastic&logoColor=white" alt="Elasticsearch"/>
  <img src="https://img.shields.io/badge/Microsoft_Sentinel-KQL_Threat_Hunt-0078D4?style=flat-square&logo=microsoftazure&logoColor=white" alt="Sentinel"/>
  <img src="https://img.shields.io/badge/Sysmon-Host_Telemetry_v15-2496ED?style=flat-square" alt="Sysmon"/>
  <img src="https://img.shields.io/badge/WinEvent-Security_Auditing-00A4EF?style=flat-square&logo=windows&logoColor=white" alt="Windows Events"/>
</p>

### 📡 Network Forensics & Deep Packet Inspection
<p>
  <img src="https://img.shields.io/badge/Wireshark-PCAP_Dissection-1679A7?style=flat-square&logo=wireshark&logoColor=white" alt="Wireshark"/>
  <img src="https://img.shields.io/badge/Zeek_(Bro)-Network_Security_Monitor-654FF0?style=flat-square" alt="Zeek"/>
  <img src="https://img.shields.io/badge/tcpdump-CLI_Packet_Capture-000000?style=flat-square" alt="tcpdump"/>
  <img src="https://img.shields.io/badge/Snort%20%2F%20Suricata-IDS_IPS_Signatures-E53935?style=flat-square" alt="IDS"/>
  <img src="https://img.shields.io/badge/Nmap-Port_&_Service_Audit-222222?style=flat-square" alt="Nmap"/>
</p>

### ⚔️ Threat Intelligence, DFIR & Detection Rules
<p>
  <img src="https://img.shields.io/badge/Velociraptor-Endpoint_DFIR_(VQL)-333333?style=flat-square" alt="Velociraptor"/>
  <img src="https://img.shields.io/badge/Sigma_Rules-Generic_Signatures-008080?style=flat-square" alt="Sigma"/>
  <img src="https://img.shields.io/badge/YARA-Pattern_Matching-5C6BC0?style=flat-square" alt="YARA"/>
  <img src="https://img.shields.io/badge/VirusTotal-API_Threat_Intel-3949AB?style=flat-square&logo=virustotal&logoColor=white" alt="VirusTotal"/>
  <img src="https://img.shields.io/badge/Any.Run-Interactive_Sandbox-0288D1?style=flat-square" alt="Any.Run"/>
  <img src="https://img.shields.io/badge/Burp_Suite-Web_Vulnerability_Triage-FF6633?style=flat-square&logo=burpsuite&logoColor=white" alt="Burp Suite"/>
</p>

### 💻 Automation, Scripting & Secure Engineering
<p>
  <img src="https://skillicons.dev/icons?i=python,powershell,bash,linux,kali,docker,git,nextjs,react,ts,supabase" alt="Engineering Stack"/>
</p>

---

## 🏠 Defensive Homelab Architecture & Threat Range

A virtualized enterprise environment deployed to simulate real-world attacks via **Atomic Red Team** and validate detection coverage:

```text
 ┌──────────────────────────────────────────────────────────────────────────┐
 │                        WAN / INTERNET SIMULATION                         │
 └────────────────────────────────────┬─────────────────────────────────────┘
                                      │
                         ┌────────────▼────────────┐
                         │   pfSense CE 2.7.2 FW   │  (VLAN Isolation, Suricata IDS,
                         │   Perimeter Inspection  │   Filterlog Syslog Export)
                         └──────┬────────────┬─────┘
                                │            │
            ┌───────────────────┘            └────────────────────┐
            ▼                                                     ▼
┌───────────────────────┐                             ┌───────────────────────┐
│  DMZ / ATTACK TARGET  │                             │  ENTERPRISE LAN (AD)  │
│  - Ubuntu Jump Host   │                             │  - Win Server 2022 DC │
│  - Nginx Reverse Prox │                             │  - Win 11 Pro Client  │
│  - Wazuh Agent        │                             │  - Sysmon 15 + Winlog │
└───────────┬───────────┘                             └───────────┬───────────┘
            │                                                     │
            └─────────────────────────┬───────────────────────────┘
                                      ▼
                        ┌───────────────────────────┐
                        │   SECURITY OPS / SIEM     │
                        │   - Wazuh Manager 4.x     │
                        │   - Splunk Enterprise     │
                        │   - Zeek Sensor (TAP)     │
                        │   - Elasticsearch + Kibana│
                        └───────────────────────────┘
```

---

## 📁 Key Technical Repositories & Security Projects

### 🛡️ [soc-analyst-portfolio](https://github.com/icebergf6/soc-analyst-portfolio)
**Enterprise Defensive Security Showcase, SIEM Sandbox & Homelab Documentation**
- **Live Demo**: [charming-squirrel-bcff68.netlify.app](https://charming-squirrel-bcff68.netlify.app/)
- **Core Highlights**:
  - Interactive browser-based SIEM sandbox testing real queries across Windows EVTX, Sysmon, and Linux logs.
  - Full incident reconstructions with real queries: Wazuh Rule `100055`, Splunk SPL correlation, and Sentinel KQL.
  - Network packet dissector analyzing extracted Cobalt Strike beaconing streams with timing delta & jitter calculations.
- **Tech Stack**: `Next.js`, `TypeScript`, `Tailwind CSS`, `Splunk SPL`, `Wazuh XML`, `Wireshark DPI`.

### 💬 [TelegramKW](https://github.com/icebergf6/TelegramKW)
**Ephemeral Real-Time Messaging Platform with Zero-Trace Architecture**
- **Security Highlights**:
  - Engineered for ephemeral communication with no persistent message retention.
  - Strict input sanitization preventing Stored XSS and SQL injection payloads.
  - Database-enforced **Row-Level Security (RLS)** via Supabase preventing unauthorized data traversal.
- **Tech Stack**: `Next.js`, `React`, `Supabase`, `WebSockets`, `Secure Authentication`.

### 📊 [TrustFlow_Biz](https://github.com/icebergf6/TrustFlow_Biz)
**Secured Financial & Credit Ledger System (BOLA/IDOR Hardened)**
- **Security Highlights**:
  - Multi-tenant data segregation with rigorous cryptographic session validation.
  - Full mitigation against **Broken Object Level Authorization (OWASP API1:2023)**.
  - Append-only financial audit trails for fraud tracking and tamper-evident accounting.
- **Tech Stack**: `React`, `TypeScript`, `Tailwind CSS`, `Supabase Auth & PostgreSQL`.

---

## 📝 Documented Incident Investigations & Case Studies

| Incident Title | Vector / Technique | Primary Telemetry | Key Findings & Remediation |
| :--- | :--- | :--- | :--- |
| **Cobalt Strike C2 Beaconing** | `T1071.001` (Web C2) | Wireshark PCAP · Zeek `conn.log` | Discovered low-and-slow HTTPS beaconing disguised with 60s interval (+/-10% jitter). Blocked C2 IP and revoked compromised session tokens. |
| **SSH Brute-Force & Lateral Pivot** | `T1110` (Brute Force) · `T1021.004` (SSH) | Wazuh Alert `5710` · Linux `auth.log` | 4,200+ failed SSH authentications followed by successful login and lateral movement attempt. Implemented IP fail2ban and key-only PAM policy. |
| **Malicious Macro & LOLBins Execution** | `T1204.002` (Malicious File) · `T1059.001` (PowerShell) | Sysmon EID 1 · WinEvent 4104 | Detected `WINWORD.EXE` spawning obfuscated `powershell.exe` download cradle. Deployed ASR rules blocking Office child process spawns. |
| **HTB Sherlocks: Brutus Forensics** | `T1078` (Valid Accounts) · `T1070` (Indicator Removal) | Linux `auth.log` · `wtmp` · `btmp` | Reconstructed attacker timeline on compromised Linux host, pinpointed unauthorized user addition, and restored tampered logs. |

---

## 📈 Activity, Telemetry & Code Metrics

<div align="center">

<img src="https://github-readme-stats.vercel.app/api?username=icebergf6&show_icons=true&theme=tokyonight&hide_border=true&rank_icon=github&include_all_commits=true&count_private=true" alt="GitHub Metrics" width="48%"/>
<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=icebergf6&layout=compact&theme=tokyonight&hide_border=true&langs_count=8" alt="Top Languages" width="48%"/>

</div>

<div align="center">

<img src="https://github-readme-activity-graph.vercel.app/graph?username=icebergf6&theme=tokyo-night&hide_border=true&area=true" alt="Activity Graph" width="98%"/>

</div>

---

<div align="center">

### 🔒 Verify · Monitor · Analyze · Contain · Harden
<sub>Ethical security practitioner operating strictly within isolated cyber ranges, authorized engagements, and RFC-compliant environments.</sub>

<br/>

```bash
# Import PGP Public Key for Encrypted Communications
curl -s https://charming-squirrel-bcff68.netlify.app/pgp.asc | gpg --import
```

<p>
  <sub>© Muhammad Syafiq (<code>icebergf6</code>) — All rights reserved.</sub>
</p>

</div>
