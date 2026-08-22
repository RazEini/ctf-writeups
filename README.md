# 🚩 CTF Writeups & Binary Exploitation

![Status](https://img.shields.io/badge/Status-Work_in_Progress-orange?style=flat-square)
![Next Platform](https://img.shields.io/badge/Next_Platform-ROP_Emporium-yellow?style=flat-square)

Welcome to my Cybersecurity & Reverse Engineering repository!  
This repository contains my personal writeups, exploit scripts, and analysis for various CTF (Capture The Flag) challenges, with a primary focus on **Binary Exploitation (Pwn)** and **Reverse Engineering**.

---

## 🛠️ Tools & Environment
* **OS:** Ubuntu (WSL2 / Linux)
* **Debugger:** GDB with [GEF](https://github.com/hugsy/gef) (GDB Enhanced Features)
* **Exploitation Framework:** Python 3 + [`pwntools`](https://github.com/Gallopsled/pwntools)
* **Disassemblers:** `objdump`, `Ghidra`

---

## 📊 Solved Challenges

### 🔹 picoCTF

| Category | Challenge | Difficulty | Tech Stack / Concepts | Writeup Link |
| :--- | :--- | :--- | :--- | :--- |
| **Binary Exploitation** | Picker IV | Medium | Function Pointer Redirection, Symbol Lookup, `pwntools` | [View Writeup](./picoCTF/Binary_Exploitation/Picker_IV/) |
| **Binary Exploitation** | Buffer Overflow 0 | Easy | Stack Buffer Overflow, Unsafe `strcpy()`, SIGSEGV Handler, `pwntools` | [View Writeup](./picoCTF/Binary_Exploitation/buffer%20overflow%200/) |
| **Binary Exploitation** | Local Target | Medium | Stack Variable Overwrite, Offset Analysis, `pwntools` | [View Writeup](./picoCTF/Binary_Exploitation/Local%20Target/) |
| **Binary Exploitation** | Buffer Overflow 1 | Medium | Control Flow Hijacking, 32-bit Architecture, EIP Overwrite, `pwntools` | [View Writeup](./picoCTF/Binary_Exploitation/buffer%20overflow%201/) |

---

## 💡 Key Focus Areas
- Stack-based memory corruption vulnerabilities (Buffer Overflows, Variable Overwriting)
- Dynamic memory & stack layout analysis via GDB/GEF (De Bruijn / Pattern Matching)
- Control flow hijacking & function pointer redirection
- Reverse engineering 32-bit & 64-bit ELF binaries
- Writing clean, automated exploits in Python (`pwntools`)

---

<p align="center"><strong>👨‍💻 Raz Eini (2026)</strong></p>
