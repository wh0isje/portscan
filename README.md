# Port Scanner with Vulnerability Check

![Python](https://img.shields.io/badge/python-3.7%2B-blue)
![License](https://img.shields.io/badge/license-MIT-green)

## 📖 About
A Python script for scanning common network ports and identifying known vulnerabilities. Optimized with multithreading and provides clear, color-coded output.

---

## 🚀 Features
- Fast scanning using multithreading.
- Identifies vulnerabilities on common ports.
- Colored output for better visibility.
- Easily extendable to custom port ranges.

---

## 🛠️ Requirements
- Python 3.7+
- Library: `termcolor`

---

## 📂 Usage
```bash
git clone https://github.com/wh0isje/portscan.git   # Clone the repository

cd portscan                                         # Navigate to the project folder

pip install termcolor                               # Install the required library

python portscan.py                                  # Run the script

# Enter the target IP or domain when prompted
```
---

## 📜 Example Output
```bash
Enter the IP address or domain to be scanned: 192.168.1.1

Starting scan...
[CLOSED] Port 21
[OPEN] Port 22: SSH - Brute force
[CLOSED] Port 23
[OPEN] Port 80: HTTP - XSS vulnerabilities

Scan completed.
```
---

## 📌 Known Vulnerabilities
```bash
| Port | Service | Vulnerability               |
|------|---------|-----------------------------|
| 21   | FTP     | Plaintext passwords         |
| 22   | SSH     | Brute-force attacks         |
| 80   | HTTP    | XSS vulnerabilities         |

```
