# Rodin Development

<p align="center">
  <img src="https://raw.githubusercontent.com/Rodin-Development/.github/main/profile/assets/rodin.png" width="140" />
</p>

<h3 align="center">Android Development for Xiaomi POCO X7 Pro</h3>

<p align="center">
  Device Trees • Kernel • Vendor • Hardware • Development
</p>

<p align="center">
  <a href="https://github.com/Rodin-Development">
    <img src="https://img.shields.io/badge/GitHub-Rodin--Development-181717?style=for-the-badge&logo=github" />
  </a>
  <img src="https://img.shields.io/badge/Device-POCO%20X7%20Pro-ff6900?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Codename-Rodin-5865F2?style=for-the-badge" />
  <img src="https://img.shields.io/badge/SoC-MediaTek%20Dimensity%208400--Ultra-009688?style=for-the-badge" />
</p>

---

## About

**Rodin Development** is a community-driven organization dedicated to Android development for the **POCO X7 Pro (`rodin`)**.

This organization hosts the core repositories required for building custom ROMs and other Android-based projects for the device, including:

- Device Trees
- Kernel Sources
- Proprietary Vendor Blobs
- MediaTek Hardware Components
- Xiaomi Hardware Components
- SELinux Policies
- Device-specific development

The goal is to keep the development resources organized, maintainable, and accessible to ROM developers and the wider Android community.

---

## Device

| | Details |
|---|---|
| **Device** | POCO X7 Pro |
| **Codename** | `rodin` |
| **SoC** | MediaTek Dimensity 8400-Ultra |
| **Architecture** | ARM64 |
| **Android** | Android 16+ |
| **OEM** | Xiaomi |
| **Device Type** | Smartphone |

---

## Repositories

### Device Tree

The main device configuration and hardware integration for `rodin`.

**Repository:**  
[`android_device_xiaomi_rodin`](https://github.com/Rodin-Development/android_device_xiaomi_rodin)

Contains:

- Board configuration
- Product configuration
- Device overlays
- Init configuration
- SELinux policies
- Hardware configuration
- ROM-specific integration

---

### Kernel

Kernel sources and device-specific kernel configuration.

**Repository:**  
[`android_device_xiaomi_rodin-kernel`](https://github.com/Rodin-Development/android_device_xiaomi_rodin-kernel)

Includes:

- Pre Built Kernel 
- Device configuration
- DTS / DTSI
- Kernel modules
- Defconfig
- Device-specific kernel changes

---

### Vendor

Proprietary blobs and vendor configuration required by `rodin`.

**Repository:**  
[`android_proprietary_vendor_xiaomi_rodin`](https://github.com/Rodin-Development/android_proprietary_vendor_xiaomi_rodin)

Contains:

- Proprietary Xiaomi blobs
- MediaTek blobs
- Vendor HALs
- Firmware interfaces
- Camera components
- Audio components
- Display components
- Device-specific vendor configuration

---

### MediaTek Hardware

Hardware abstraction and MediaTek-specific components.

**Repository:**  
[`android_hardware_mediatek`](https://github.com/Rodin-Development/android_hardware_mediatek)

---

### Xiaomi Hardware

Xiaomi-specific hardware components and integrations.

**Repository:**  
[`android_hardware_xiaomi`](https://github.com/Rodin-Development/android_hardware_xiaomi)

---

### Vendor SELinux

MediaTek vendor SELinux policies used by the device tree.

**Repository:**  
[`android_device_mediatek_sepolicy_vndr`](https://github.com/Rodin-Development/android_device_mediatek_sepolicy_vndr)

---

## Repository Structure

```text
Rodin-Development/
│
├── android_device_xiaomi_rodin
│   └── Device Tree
│
├── android_device_xiaomi_rodin-kernel
│   └── Kernel
│
├── android_proprietary_vendor_xiaomi_rodin
│   └── Vendor Blobs
│
├── android_hardware_mediatek
│   └── MediaTek Hardware
│
├── android_hardware_xiaomi
│   └── Xiaomi Hardware
│
└── android_device_mediatek_sepolicy_vndr
    └── Vendor SELinux Policies
