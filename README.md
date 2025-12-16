# XTOOLS - Professional Security Toolkit v2.3

**By XeyyzuV2** | **Forum**: [https://forum.html-5.me](https://forum.html-5.me)

**61 Attack Modules** | Login Protected | Premium Interface

---

## ⚠️ Disclaimer

**FOR EDUCATIONAL & AUTHORIZED TESTING ONLY.**

---

## 🚀 Installation

```bash
# Linux
./release/xtools

# Windows (Coming Soon)
xtools.exe

# Manual (Development)
pip install -r requirements.txt
```

**Login:** `xeyyzu` / `xey2025`

---

## 📊 Complete Module Reference (61 Modules)

### 🎯 Bug Bounty (21)
| Module | Description |
|--------|-------------|
| `xss` | XSS Scanner (DOM, Reflected, WAF bypass) |
| `ssrf` | SSRF (cloud metadata, internal) |
| `ssti` | Template Injection |
| `sqli` | **SQL Injection Scanner** |
| `xxe` | XXE (7 payloads, OOB) |
| `lfi` | Local File Inclusion |
| `idor` | **IDOR Scanner** |
| `cors` | CORS Misconfiguration |
| `jwt` | JWT Analyzer + Cracker |
| `redirect` | Open Redirect |
| `crlf` | CRLF Injection |
| `clickjack` | Clickjacking + PoC |
| `headers` | Security Headers |
| `params` | Hidden Parameter Discovery |
| `takeover` | Subdomain Takeover |
| `smuggling` | HTTP Request Smuggling |
| `cachepoisoning` | Web Cache Poisoning |
| `racecondition` | Race Condition |
| `deserialize` | Insecure Deserialization |
| `hosthead` | **Host Header Injection** |

### 🔍 Advanced (11)
| Module | Description |
|--------|-------------|
| `graphql` | GraphQL Introspection & DoS |
| `nosql` | NoSQL Injection (MongoDB) |
| `cmdi` | Command Injection |
| `prototype` | Prototype Pollution |
| `websocket` | WebSocket Security |
| `vulnscan` | CVE Scanner (50+ CVEs) |
| `wafdetect` | WAF Fingerprinting |
| `sslscan` | SSL/TLS Analysis |
| `apifuzz` | API Fuzzer |
| `bruteforce` | **Login Bruteforce** |
| `masscan` | **Mass Target Scanner** |

### 💀 Exploit Tools (3)
| Module | Description |
|--------|-------------|
| `revshell` | **Reverse Shell Generator** (12+ types) |
| `obfuscate` | **Payload Obfuscator** (10 encodings) |
| `genpayload` | Payload Generator |

### 🌐 Web Scanners (6)
| Module | Description |
|--------|-------------|
| `portscan` | TCP Port Scanner |
| `subnum` | Subdomain Enumeration |
| `dirscan` | Directory Bruteforce |
| `apiscan` | API Endpoint Discovery |
| `techscan` | Technology Fingerprint |
| `report` | Report Generator (HTML/JSON/MD) |

### ⚡ DDoS (9)
| Module | Description |
|--------|-------------|
| `http` | HTTP Flood (WAF bypass, 7 methods) |
| `http2` | HTTP/2 Rapid Reset |
| `slowloris` | Slowloris |
| `rudy` | R-U-Dead-Yet |
| `udp` | UDP Flood |
| `syn` | SYN Flood |
| `tcp_ack` | TCP ACK Flood |
| `icmp` | ICMP Flood |
| `samp` | SA:MP Query Flood |

### 📡 Amplification (7)
| Module | Amplification |
|--------|---------------|
| `dns` | 54x |
| `ntp` | 556x |
| `memcached` | 51,000x |
| `ssdp` | 30x |
| `snmp` | 6x |
| `ldap` | 70x |
| `chargen` | Variable |

### 🔧 Recon (4)
| Module | Description |
|--------|-------------|
| `whois` | WHOIS Lookup |
| `ipinfo` | IP Geolocation |
| `dnsrecon` | DNS Enumeration |
| `proxyfetch` | Proxy List Fetcher |

---

## 🔥 New in v2.3

### � Tier System
- **Guest Tier** - Basic reconnaissance & info gathering modules
- **User Tier** - Full access to scanning & bug bounty modules
- **Root Tier** - Complete access including DDoS, exploits & amplification
- **Tier-based Access Control** - Modules locked based on license tier
- **Dynamic Menu** - Only shows accessible modules for your tier

### �📦 Pre-built Binaries
- **Linux Binary** - Just run `./release/xtools` - no Python required!
- **Windows Binary** - `xtools.exe` (Coming Soon)
- **Simplified Installation** - No more dependency hell

### 🛠️ Improvements
- **Faster startup** - Optimized module loading
- **Better error handling** - More descriptive error messages
- **Code cleanup** - Refactored core modules

---

## 🔥 New in v2.2

### 🔐 HWID License System (VIP Protection)
- **Hardware-based authentication** - Key locked to device
- **Vercel API** - Serverless license validation
- **Discord Bot** - `!genkey @user` for admins
- **Anti-sharing** - HWID mismatch = access denied

### 🎯 Bug Bounty Modules
- **Cloud Bucket Scanner** (`bucketscan`) - AWS S3, GCS, Azure, DO Spaces
- **JS Secret Hunter** (`jssecrets`) - Extract API keys, tokens from JS files
- **WordPress Scanner** (`wpscan`) - Version detect, user enum, plugin CVE check
- **Wordlist Generator** (`wordgen`) - CeWL-like context-aware wordlists

### ⚡ Enhanced Load Testing
- **Aggressive Mode** - 3x threads, no delays
- **Flood Mode** - 500 max threads, minimal timeout
- **Turbo Option** - Bypass all safety limits
- **HEAD/OPTIONS** - Additional HTTP methods

### 🕵️ Stealth Mode
- **Random Delays** - 2-15 seconds between requests
- **UA Rotation** - 25+ browser User-Agents
- **Log Evasion** - Avoid detection by admin log analysis

### 🔧 Improvements
- **Auto-Fetch Proxy** - Automatic proxy loading when enabled
- **Version bump** - v2.2 across all files

---

## 🔥 New in v2.1

- **Login Protection** with animated intro
- **SQLi Scanner** - Error/Union/Blind/Time-based
- **IDOR Scanner** - Access control testing
- **Bruteforce** - Multi-threaded login attack
- **Reverse Shell Generator** - 12+ shell types
- **Payload Obfuscator** - 10 encoding methods
- **Mass Scanner** - Multi-target scanning
- **Host Header Injection** - Password reset poisoning

---

```
██╗  ██╗████████╗ ██████╗  ██████╗ ██╗     ███████╗
╚██╗██╔╝╚══██╔══╝██╔═══██╗██╔═══██╗██║     ██╔════╝
 ╚███╔╝    ██║   ██║   ██║██║   ██║██║     ███████╗
 ██╔██╗    ██║   ██║   ██║██║   ██║██║     ╚════██║
██╔╝ ██╗   ██║   ╚██████╔╝╚██████╔╝███████╗███████║
╚═╝  ╚═╝   ╚═╝    ╚═════╝  ╚═════╝ ╚══════╝╚══════╝
                v2.3 By XeyyzuV2
```

**65+ Modules | HWID Protected | Premium Security Toolkit**

