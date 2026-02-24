## Python-DDoS-Script
---

This project is a Python-based UDP traffic generator intended **solely for learning, research, and controlled network‑stress testing**.  
It **must** be used on systems, servers, or networks **with** permission.

---

## Features
- Multi-threaded UDP packet sender  
- Three traffic modes:
  - `UPD-FLOOD` – Standard packet spammer  
  - `UPD-Power` – Higher‑amplification packet load  
  - `UDP-Mix` – Alternates between both packet sizes (375 and 750)  
- Customizable packet loop count  

---

## Requirements
- Python 3   

---

## Usage

1) Clone this repository:
```bash
git clone https://github.com/The-R34per/Python-DDoS-Script
```

2) Run the script:

```bash
python3 Python-DDoS-Script.py <host> <port> <method>
```
**Example:**
```bash
python3 Python-DDoS-Script.py 127.0.0.1 1234 UPD-FLOOD
```

---
## License

Python DDoS Script © 2026 by The-R34per is licensed under CC BY-NC-SA 4.0. To view a copy of this license, visit https://creativecommons.org/licenses/by-nc-sa/4.0/
