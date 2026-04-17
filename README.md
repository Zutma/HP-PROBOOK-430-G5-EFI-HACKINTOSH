# 💻 HP ProBook 430 G5 Hackintosh (macOS Sequoia)

![macOS Version](https://img.shields.io/badge/macOS-Sequoia-blue?style=for-the-badge&logo=apple)
![OpenCore](https://img.shields.io/badge/OpenCore-0.9.9-green?style=for-the-badge&logo=opencore)

OpenCore EFI configuration to run macOS Sequoia on HP ProBook 430 G5. 

---

### 🛠️ Laptop Specifications
| Component | Details |
| :--- | :--- |
| **Processor** | Intel Core i5-8250U (Kaby Lake-R) |
| **Graphics** | Intel UHD Graphics 620 |
| **RAM** | 16GB DDR4 2400MHz |
| **Storage** | 500GB HDD ST500LM030-1RK17D |
| **Display** | 13.3" Full HD IPS |
| **Touchpad** | Synaptics I2C |
| **Wi-Fi/BT** | Intel® Dual Band Wireless-AC 8265 |
| **BIOS Version** | 01.09.10 |

---

### ⚙️ BIOS Setup

#### **Advanced / Security**
- [x] **Disable** Intel SGX
- [x] **Disable** Secure Boot
- [x] **Disable** MS UEFI CA key
- [x] **Disable** Fast Boot

#### **System Configuration**
- [x] **Enable** UEFI Boot Order (Disable Legacy)
- [x] **Enable** Virtualization Technology (VTx)
- [x] **Disable** VTd (Virtualization for Directed I/O)
- [x] **Set** Video memory size to **512MB**
- [x] **Disable** Wake on LAN/WLAN
- [x] **Disable** Intel Optane

---

### 📡 Wireless Connectivity
> [!IMPORTANT]
> **Wi-Fi Note:** Because using Intel Wi-Fi card on macOS Sequoia, Wi-Fi network using `itlwm.kext`.
> 
> **How to use:**
> 1. Download and install [HeliPort](https://github.com/OpenIntelWireless/HeliPort/releases).
> 2. Run HeliPort for Wi-Fi network.

---

### ✅ What's Working?
- [x] QE/CI Graphics Acceleration (Intel UHD 620)
- [x] Audio, Speakers, & Mic
- [x] USB Ports (Type-A & Type-C)
- [x] Keyboard & Trackpad (Gestures)
- [x] Battery Indicator
- [x] Integrated Camera
- [x] Sleep & Wake

---
