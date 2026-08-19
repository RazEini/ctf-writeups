# 🚩 CTF Writeups & Binary Exploitation

Welcome to my Cybersecurity & Reverse Engineering repository!  
This repository contains my personal writeups, exploit scripts, and analysis for various CTF (Capture The Flag) challenges, with a primary focus on **Binary Exploitation (Pwn)** and **Reverse Engineering**.

---

## 🛠️ Tools & Environment
* **OS:** Ubuntu (WSL2 / Linux)
* **Debugger:** GDB with [GEF](https://github.com/hugsy/gef) (GDB Enhanced Features)
* **Exploitation Framework:** Python 3 + [`pwntools`](https://github.com/Gallopsled/pwntools)
* **Disassemblers:** `objdump`, `nm`, `Ghidra`

---

## 📊 Solved Challenges

### 🔹 picoCTF

| Category | Challenge | Difficulty | Tech Stack / Concepts | Writeup Link |
| :--- | :--- | :--- | :--- | :--- |
| **Binary Exploitation** | Picker IV | Medium | Function Pointer Redirection, Symbol Lookup, `pwntools` | [View Writeup](./picoCTF/Binary_Exploitation/Picker_IV/) |
| **Binary Exploitation** | buffer overflow 0 | Easy | Stack Buffer Overflow, Unsafe `gets()`, SIGSEGV Handler | [View Writeup](./picoCTF/Binary_Exploitation/buffer%20overflow%200/) |
| **Binary Exploitation** | Local Target | Medium | Stack Variable Overwrite, Offset Analysis, `pwntools` | [View Writeup](./picoCTF/Binary_Exploitation/Local%20Target/) |

---

## 💡 Key Focus Areas
- Memory corruption vulnerabilities (Buffer Overflow, Format Strings)
- Bypassing security mitigations (NX, ASLR, Stack Canaries)
- Reverse engineering x86_64 ELF binaries
- Writing clean, automated exploits in Python
