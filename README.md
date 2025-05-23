# Hi, I'm Hein 👋

## 🔐 Cybersecurity Student | Future Security Analyst

I'm a Computer Science student at Massey University (Top 10%) with a passion for cybersecurity. Currently building security tools and preparing for a career in security operations.

### 🎯 What I'm Working On
- 🔍 Building network security tools with Python
- 📚 Studying for CompTIA Security+ certification  
- 🛡️ Creating incident response automation scripts
- 💼 Seeking Security Analyst opportunities in Auckland

### 🏆 Certifications & Achievements
- **ISC2 Certified in Cybersecurity (CC)** - 2024
- **Cisco CCNA** - Network Security Fundamentals
- **Google Cybersecurity Professional Certificate**
- **Currently:** CompTIA Security+ (In Progress)

### 🛠️ Technical Skills
```python
security_skills = {
    'languages': ['Python', 'Bash', 'PowerShell'],
    'security_tools': ['Wireshark', 'Nmap', 'Metasploit', 'Kali Linux'],
    'networking': ['TCP/IP', 'VLANs', 'Routing Protocols', 'Firewalls'],
    'platforms': ['Windows Server', 'Linux', 'Active Directory']
}

# Network Security Toolkit 🔒

A collection of Python-based network security tools for ethical hacking and security assessments.

## 🚀 Features

### Port Scanner
- Multi-threaded for fast scanning
- Service detection
- Custom port range support
- Clean output format

## 📋 Requirements
- Python 3.6+
- Standard library only (no external dependencies)

## 🔧 Installation
```bash
git clone https://github.com/Hh-Zaw/network-security-toolkit.git
cd network-security-toolkit

# Scan default ports (1-1000)
python3 port_scanner.py example.com

# Scan specific port range
python3 port_scanner.py example.com -p 1-65535

# Adjust thread count for faster scanning
python3 port_scanner.py example.com -t 200
