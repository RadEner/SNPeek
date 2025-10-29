# SNPeek
Educational network analysis tool built with Python ,designed for students and beginners to learn how networks work.

**SNPeek** — Simple Network Port Scanner & Banner Grabber (for educational and lab use only)

> **Notice:** Use SNPeek only on networks or hosts you own or have explicit permission to test.  
> Unauthorized scanning is illegal and unethical.

---

## Overview
**SNPeek** is a lightweight Python-based network port scanner with multithreading and banner grabbing support.  
It’s designed for educational, cybersecurity, and networking practice purposes on Linux environments such as **Ubuntu**.

---

## Features
- Scan single hosts, hostnames (DNS), or CIDR ranges  
- Supports port lists (e.g. `22,80,443`) and ranges (e.g. `1-1024`)  
- Multithreaded scanning for fast results  
- Banner grabbing for identifying running services  
- Optional CSV output for easy reporting  
- Interactive mode for beginners  
- CLI argument mode for advanced users  

---

## Requirements
- **Python 3.8+**
- Optional: `colorama` for colored terminal output  
  ```bash
  pip install colorama
