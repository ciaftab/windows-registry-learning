# Windows Registry Learning – Windows Defender Demo

![License](https://img.shields.io/badge/license-MIT-blue) ![Language](https://img.shields.io/badge/language-REG-lightgrey)

⚠️ **WARNING — EDUCATIONAL PURPOSES ONLY**  
This repository contains sample Windows Registry entries for **learning and lab environments only**.  
**Do NOT run these files on your personal or production machine.**

---

## 📖 About
This repository is intended for students and security enthusiasts to learn about Windows Registry configurations, specifically regarding Windows Defender policies.  
All files are **safe `.reg.txt` examples** to demonstrate how registry entries can be used to enable or disable certain features for educational purposes.

---

## 📂 Repository Structure
windows-registry-learning/
├─ README.md
├─ DISCLAIMER.md
├─ LICENSE
├─ docs/
│ └─ registry-defender-demo.md
└─ examples/
├─ example-defender-enable.reg.txt
└─ example-defender-disable.reg.txt


- `docs/` → explanations of registry keys  
- `examples/` → sample `.reg.txt` files (safe, not executable)  

---

## 🚀 How to Use
1. Open and **read the `.reg.txt` files** to understand the registry keys.  
2. If you want to experiment, **use a virtual machine** and rename `.reg.txt` → `.reg` before importing.  
3. Do **not** use these files on production devices.  

---

## 🔑 Key Concepts
- Windows stores many configuration options inside the registry.  
- Policies like Windows Defender can be controlled via registry entries.  
- Tamper Protection must be off for certain changes (for demo purposes only).  

---

## 🔗 References
- [Microsoft Docs – Set-MpPreference](https://learn.microsoft.com/powershell/module/defender/set-mppreference)  
- [Microsoft Docs – Tamper Protection](https://support.microsoft.com/help/4532313)  
