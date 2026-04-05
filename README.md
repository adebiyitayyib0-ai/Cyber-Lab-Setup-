# Cyber-Lab-Setup
This repository documents my journey in building a professional cybersecurity home lab from scratch.

## Phase 1: Environment Setup
To practice real-world offensive and defensive techniques safely, I am building a virtualized environment.

### Achievements:
*   **Virtualization Platform**: Installed Oracle VirtualBox 7.x on a Windows 11 Host.
*   **Troubleshooting**: Successfully resolved a missing dependency for 'Microsoft Visual C++ 2019 Redistributable' that was preventing the installation.
*   **Next Steps**: Importing the Kali Linux Attacker Machine and setting up an isolated virtual network.

[Files.pdf](https://github.com/user-attachments/files/26487942/Files.pdf)
---

## Phase 2: Attacker Node Configuration

**Action**: Deployed a pre-configured Kali Linux 2026.1 Virtual Appliance (OVA) to serve as the primary offensive workstation.

### **Key Technical Hurdles & Resolutions:**
*   **Storage Configuration**: Initially encountered a 'VDI Inaccessible' error. 
*   **Root Cause**: Attempting to index files from within a compressed (.zip) archive.
*   **Resolution**: Performed a full 15GB filesystem extraction to local storage and re-mapped the VirtualBox machine definition (.vbox) to the virtual disk.
*   **Snapshot Management**: Successfully created a 'Base_Install' restore point to ensure lab stability during future exploit testing.
### **Visual Verification:**
