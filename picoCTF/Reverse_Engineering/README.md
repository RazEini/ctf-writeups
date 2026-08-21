# 🔍 picoCTF - Reverse Engineering

This directory contains my writeups, static/dynamic analysis notes, and scripts for various **Reverse Engineering** challenges from [picoCTF](https://picoctf.org/).

The focus of these challenges is dissecting compiled binaries, understanding control flow, and extracting embedded secrets or cryptographic logic.

---

## 🛠️ Tools & Methodology

For analyzing these binaries, I utilize both static and dynamic engineering workflows:

* **Static Analysis:** `Ghidra`, `objdump`, `strings`, `readelf`
* **Dynamic Analysis & Debugging:** `GDB` with `GEF`, `ltrace`, `strace`
* **Scripting & Automation:** Python 3 (z3-solver, pwntools)

---

## 📌 Core Concepts Covered

* **Control Flow Analysis:** Tracing logic, branches, and conditional jumps in x86_64 and ARM assembly.
* **Key/Flag Validation Logic:** Reversing custom string obfuscation, XOR encoding, and basic mathematical transformations.
* **Anti-Debugging & Patching:** Modifying binary behavior in GDB to bypass checks.
* **Symbol & String Extraction:** Leveraging unstripped binaries and embedded resources for rapid identification.

---

## 📝 Challenges Summary

| Challenge | Difficulty | Primary Focus / Techniques |
| :--- | :--- | :--- |
| *Vault-Door Series* | Easy / Medium | String manipulation, Java bytecode analysis, regex logic |
| *ARMssembly* | Medium | ARM Architecture, registers, branch instructions |
| *GDB Test Drive* | Easy | Dynamic debugging, breakpoints, register inspection |

> **Note:** As foundational concepts from picoCTF are consolidated here, further advanced Reverse Engineering writeups (focused on complex obfuscation, unpacking, and malware analysis) are available in the higher-level platform directories.
