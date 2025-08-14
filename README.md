# Security Hardening Guides & How-Tos

This repository contains a collection of original, practical cybersecurity and IT hardening guides created by **N4vx0-2**. Each guide includes actionable steps, code snippets, and scripts to help professionals secure their environments.

---

## 📂 Contents

### 1. [Stopping Lateral Movement BitLocker Attacks](Stopping%20Bitlocker%20Attacks.pdf)
Learn how attackers exploit BitLocker via COM/DCOM hijacking and bootloader memory extraction — and how to defend against these vectors. Includes:
- Detailed technical background on attack methods
- Hardening recommendations for COM, SMB, PXE, and bootloader protections
- Custom PowerShell scripts for:
  - Enumerating vulnerable BitLocker-related COM CLSIDs
  - Removing dangerous LaunchPermission settings
  - Hardening SMB shares
  - Checking and enabling Secure Boot / Kernel DMA Protection
  - Applying BitLocker & Secure Boot updates

---

## 🛠️ Usage

1. Open a guide (PDF format).
2. Follow the steps provided — most guides include code examples or scripts.
3. Always test changes in a lab environment before applying to production systems.

---

## 🧾 License & Attribution

All content is © N4vx0-2 unless otherwise stated.  
You are free to reference these materials, but please **credit the original author**.  
Do **not** claim these guides or scripts as your own.

---

## 💡 Contributions

If you have feedback, suggestions, or additional security tips, open an Issue or submit a Pull Request.

---

## 🔗 Related Projects

- [PulseOps: PowerShell Task Automation](https://github.com/N4vx0-2/pulseops-powershell-automation)
- [Project Aiden: Security Middleware](https://github.com/N4vx0-2/aiden-security-middleware)
