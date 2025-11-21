# Detecting Driver Scanner

![Driver Scanner](https://img.shields.io/badge/status-beta-orange)

**Detecting Driver Scanner** is a Windows-based PowerShell GUI tool for scanning system drivers, detecting suspicious files, and identifying potential DMA (Direct Memory Access) devices that could be used for malicious purposes or hardware-based cheats.  

---

## Features

- **Driver Scanning**
  - Lists all Windows system drivers.
  - Checks if driver files exist.
  - Detects drivers with high entropy or suspicious number of sections.
  - Flags drivers with invalid digital signatures.
  - Assigns a **Suspicious Score** for quick analysis.

- **DMA Detection**
  - Detects PCI devices that match known DMA cheat/hardware patterns.
  - Highlights potential hardware exploits such as PCILeech, FPGA boards, and other DMA devices.

- **Logs**
  - Real-time logs of the scanning process.
  - Filter logs by keyword or driver name.
