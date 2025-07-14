Cybersecurity News Summary: July 7-14, 2025

Based on your RSS feeds, here are the most significant cybersecurity developments from the past week:

### 🚨 Critical Vulnerabilities

**CVE-2025-47812 - Wing FTP Server (CVSS: 10.0)**
- **Impact**: Critical remote code execution vulnerability 
- **Details**: Null byte injection in web interface allows arbitrary Lua code execution
- **Status**: **Actively exploited in the wild**
- **EPSS Score**: 57.30% (Top 98.01% - very high exploitation probability)
- **Fix**: Update to version 7.4.4
- **Link**: [Original Article](https://thehackernews.com/2025/07/critical-wing-ftp-server-vulnerability.html)

**CVE-2025-5777 - Citrix NetScaler "CitrixBleed 2" (CVSS: 7.5)**
- **Impact**: Memory overread vulnerability in NetScaler ADC/Gateway
- **Status**: **Added to CISA KEV catalog** - confirmed active exploitation
- **EPSS Score**: 16.57% (Top 94.60%)
- **Affected**: VPN virtual servers, ICA Proxy, CVPN, RDP Proxy configurations
- **Link**: [Original Article](https://thehackernews.com/2025/07/cisa-adds-citrix-netscaler-cve-2025.html)

### 🚗 Automotive Security Alert

**PerfektBlue Bluetooth Attack (CVE-2024-45434 & others)**
- **Impact**: Affects **millions of vehicles** from Mercedes-Benz, Volkswagen, and Skoda
- **Attack Vector**: Bluetooth vulnerabilities in OpenSynergy BlueSDK
- **Capabilities**: 
  - GPS tracking and location monitoring
  - Audio recording through infotainment systems
  - Access to phonebook data
  - Potential lateral movement to critical vehicle functions
- **User Interaction**: Requires "at most 1-click" from user
- **CVE Details**:
  - CVE-2024-45434: Use-after-free in AVRCP service (CVSS 8.0)
  - CVE-2024-45431: L2CAP validation flaw (CVSS 3.5)
  - CVE-2024-45433: RFCOMM termination issue (CVSS 5.7)
  - CVE-2024-45432: RFCOMM parameter error (CVSS 5.7)
- **Links**: [SecurityWeek](https://www.securityweek.com/350m-cars-1b-devices-1-click-bluetooth-rce/) | [BleepingComputer](https://www.bleepingcomputer.com/news/security/perfektblue-bluetooth-flaws-impact-mercedes-volkswagen-skoda-cars/)

### 📱 Mobile & IoT Security

**eSIM Vulnerability in Kigen eUICC Cards**
- **Scale**: Affects over **2 billion** IoT devices with Kigen-enabled SIMs
- **Root Cause**: Oracle Javacard bytecode verification flaws (originally from 2019)
- **Attack Vector**: Over-the-air exploitation via SMS-PP protocol
- **Impact**: Malicious code execution on eSIM-enabled devices
- **Architectural Issue**: Fundamental problem in GSMA eSIM implementation
- **Link**: [Original Article](https://thehackernews.com/2025/07/esim-vulnerability-in-kigens-euicc.html)

### 💻 Web Application Security

**Laravel APP_KEY Mass Exposure**
- **Scale**: Over 600 Laravel applications vulnerable
- **Cause**: APP_KEYs leaked on GitHub enabling deserialization attacks
- **Impact**: Complete remote code execution when APP_KEY is known
- **Related**: Builds on CVE-2018-15133 Laravel deserialization vulnerability
- **Link**: [Original Article](https://thehackernews.com/2025/07/over-600-laravel-apps-exposed-to-remote.html)

### 🎯 Notable Attacks & Incidents

**Scattered Spider Arrests**
- **Action**: UK arrested 4 alleged members of prolific ransomware group
- **Recent Victims**: Airlines, Marks & Spencer retail chain
- **Significance**: Major law enforcement action against high-profile cybercriminal group
- **Link**: [Krebs on Security](https://krebsonsecurity.com/2025/07/uk-charges-four-in-scattered-spider-ransom-group/)

**Supply Chain Attack on WordPress**
- **Target**: Gravity Forms plugin (popular WordPress plugin)
- **Method**: Malware injected into official plugin versions
- **Impact**: Demonstrates vulnerability of software supply chains
- **Link**: [Original Article](https://www.securityweek.com/hackers-inject-malware-into-gravity-forms-wordpress-plugin/)

### 🔬 Emerging Attack Techniques

**GPUHammer - AI Model Degradation**
- **Target**: NVIDIA GPUs running AI models
- **Method**: RowHammer variant attack
- **Impact**: Can degrade AI model performance
- **Mitigation**: NVIDIA recommends enabling System-level ECC
- **Link**: [Original Article](https://thehackernews.com/2025/07/gpuhammer-new-rowhammer-attack-variant.html)

### 🎯 Geopolitical Cyber Activity

**Pay2Key Ransomware Resurgence**
- **Attribution**: Iranian-backed, linked to Fox Kitten/Lemon Sandstorm APT
- **Targeting**: US and Israeli organizations
- **Business Model**: 80% profit share for affiliates (increased incentive)
- **Context**: Resurged amid regional tensions
- **Link**: [Original Article](https://thehackernews.com/2025/07/iranian-backed-pay2key-ransomware.html)

### 📊 Data Breaches

**McDonald's Recruitment Platform**
- **Scale**: 64 million job applications exposed
- **Cause**: Two API vulnerabilities allowing unauthorized access
- **Data**: Contact information and chat logs
- **Impact**: Highlights risks in AI-powered recruitment systems
- **Link**: [Original Article](https://www.securityweek.com/mcdonalds-chatbot-recruitment-platform-leaked-64-million-job-applications/)

**Louis Vuitton Customer Data**
- **Scope**: Customers in UK, South Korea, Turkey, and potentially other countries
- **Details**: Limited information available about breach scope
- **Link**: [Original Article](https://www.securityweek.com/louis-vuitton-data-breach-hits-customers-in-several-countries/)

---

**Key Takeaways for Security Teams:**
1. **Immediate Action Required**: Patch Wing FTP Server and Citrix NetScaler if in use
2. **Automotive Security**: Organizations with vehicle fleets should assess Bluetooth security
3. **Supply Chain Risk**: Increased vigilance needed for third-party components
4. **Mobile/IoT**: eSIM vulnerabilities highlight broader IoT security challenges
5. **Geopolitical Tensions**: Expect continued state-sponsored activity

All summaries have been stored in your knowledge base and Chroma collection for future reference.