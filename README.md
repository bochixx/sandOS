# sandsOS  
**Like sand through your fingers, your data remains your own.**

**sandsOS** is a privacy-focused, Debian-based Linux distribution built for users who demand security, minimalism, and freedom from surveillance.

---

### ⚠️ Current Status: v0.1-alpha (Pre-release)

This is the very first alpha build of sandsOS. It is intended for testing and development purposes only.

#### Known Issues:
- **Critical**: The graphical user interface (XFCE Desktop) does not load automatically on boot. The system currently boots to a command-line terminal. This is the top priority for the next release.

---

## About The Project

In an era of pervasive tracking and data collection, **sandsOS** is an experiment in digital sovereignty. The guiding principle is simple: the user should be in absolute control of their system and their data. We achieve this through a curated selection of open-source privacy tools, system-level hardening, and a commitment to transparency.

---

## Key Features in v0.1-alpha

Even in this early stage, sandsOS includes several core privacy enhancements:

- **Default Firewall (UFW)**: All incoming connections are blocked by default to reduce attack surface.
- **MAC Address Randomization**: `macchanger` anonymizes your hardware address to prevent local network tracking.
- **Secure File Deletion**: `BleachBit` is included to securely clean up unnecessary system files and sensitive user data.
- **Metadata Stripping**: `MAT2` (Metadata Anonymization Toolkit) is available to strip identifying metadata from documents, images, and files before sharing.
- **Hardened Web Browser**: Firefox ESR is installed with the [Arkenfox user.js](https://github.com/arkenfox/user.js) project for advanced tracking, fingerprinting, and telemetry resistance.

---

## Getting Started (For Testers)

**1. Download the ISO**  
Go to the **[Releases](https://github.com/bochixx/sandOS/releases)** page and download the `sandsOS.v0.1.iso` file.

**2. Verify the Download (Important!)**  
Before using the ISO, verify its integrity. The SHA256 hash for the file is listed on the release page.

- On Linux: _sha256sum sandsOS.v0.1.iso_
- On Windows (PowerShell): _Get-FileHash sandsOS.v0.1.iso_

**3. Create a Virtual Machine**
It is highly recommended to test this release in a virtual machine (like VirtualBox or VMware) rather than on bare metal.


© 2025 sandOS – Privacy is not optional.
