# 🛡️ Advanced Phishing URL Scanner (Python)

A powerful command-line tool that detects malicious, suspicious, and fake URLs using **heuristic analysis** and **brand impersonation detection**.

## 🚀 Features

### 🔍 Detection Capabilities
- **Brand Impersonation** (50+ variants like `faceb00k`, `paypa1`, `g00gle`)  
- **Suspicious TLDs** (`.buzz`, `.tk`, `.gq`, and more)  
- **Dangerous Patterns**:
  - IP addresses in URLs (`http://192.168.1.1/login`)  
  - Sensitive paths (`/login`, `/verify`, `/password`)  
  - High-entropy domains (random-looking strings)  
- **Security Checks**:
  - Missing HTTPS encryption  
  - Unusually long URLs  

### 📊 Threat Classification
- ✅ **Clean** (Legitimate sites like `https://www.google.com`)  
- ⚠ **Suspicious** (Unusual but not confirmed malicious)  
- 🚨 **Malicious** (Confirmed phishing/scam links)  

---

## 🛠️ Installation

1. **Clone the repository**:
   ```bash
   git clone https://github.com/Cyber574r/phishing-scanner.git
   cd phishing-scanner
