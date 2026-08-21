# 🔍 picoCTF - Reverse Engineering

This directory is dedicated to **Reverse Engineering** challenges from [picoCTF](https://picoctf.org/). 

The primary objective of these challenges is analyzing compiled binaries (ELF/PE), decompiling bytecode, and understanding underlying application logic to reconstruct hidden keys, flags, or validation algorithms.

---

## 🛠️ Tools & Analysis Workflow

* **Static Analysis:** `Ghidra`, `objdump`, `strings`, `readelf`
* **Dynamic Analysis & Debugging:** `GDB` with `GEF`, `ltrace`, `strace`
* **Decompilation & Scripting:** Python 3 (`z3-solver`, `pwntools`), Java Decompilers (`cfr`, `jadx`)

---

## 📌 Target Concepts & Knowledge Areas

* **Control Flow Dissection:** Tracing execution paths, conditional branching, and assembly logic (x86_64, ARM).
* **Key & Flag Reconstruction:** Reversing string obfuscation, XOR operations, array mutations, and mathematical checks.
* **Dynamic Inspection:** Utilizing breakpoints, registers inspection, and patch points during binary runtime.

---

> **Note:** Advanced Reverse Engineering research—including anti-debugging bypasses, custom unpackers, and complex binary protections—is documented in the higher-tier platform repositories.
