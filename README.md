# netexec_0.0.0_amd64

# NetExec (NXC) – Standalone Binary Edition

This repository provides a **fully standalone distribution of the well-known NetExec (NXC) framework**, packaged as a **single self-contained binary**, built for stability, portability, and operational efficiency during red team engagements.

Unlike the traditional NetExec setup, this build does **not** require a Python environment or external dependencies.

---

## 🔹 Key Features

### ✅ Single Standalone Binary
- One executable file only
- No Python, no pip, no virtualenv
- Works out of the box

### ✅ Custom Zsh Auto-Completion
- Includes a **custom-built Zsh tab-completion**
- Designed specifically for this NetExec binary
- Improves speed, accuracy, and usability during command execution

### ✅ Debian Package (.deb)
- Distributed as a **`.deb` package**
- Clean installation on Kali Linux using standard package management
- No pollution of the system Python environment

### ✅ Kali Linux Compatibility
- Fully tested on **Kali Linux 2020.2**
- Expected to work on **all modern Kali Linux releases**
- Kali maintains strong backward compatibility across versions

### ✅ x64 Portability
- On **non-Kali or non-Debian x64 systems**:
  - Simply extract the package
  - Run the binary directly
  - No installation required

---

## 📦 Installation

### Kali Linux (Recommended)

```bash
wget https://github.com/pashamasr01287654800/netexec_0.0.0_amd64/releases/download/0.0.0/netexec_0.0.0_amd64.deb
```
```bash
sudo dpkg -i netexec_0.0.0_amd64.deb
```

⚠ Notes
This build is intended for authorized security testing only
Ensure you have proper permission before use
The project focuses on portability and operational stability
⭐ Final Words
If you are looking for a lean, fast, and dependency-free NetExec experience, this standalone binary edition delivers exactly that — with native Zsh auto-completion and proven Kali
