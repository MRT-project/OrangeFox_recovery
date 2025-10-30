# 🦊 OrangeFox Recovery for  SM6115 (chime)

<div align="center">

![OrangeFox](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcSKQkL6PDlh_yc0uuf_zfIhuuUsBikUf6A5JZbwQ-tX6w&s=10)

**Unofficial Build - 20251030**

[![Build Status](https://img.shields.io/badge/Build-Success-brightgreen)]()
[![OrangeFox](https://img.shields.io/badge/OrangeFox-12.1-orange)]()
[![Android](https://img.shields.io/badge/Android-12.1-blue)]()
[![Maintained](https://img.shields.io/badge/Maintained-Yes-green)]()

</div>

## 📋 Device Information

- **Device**:  SM6115
- **Codename**: chime
- **OrangeFox Branch**: 12.1
- **Build Date**: 20251030
- **Build Time**: 20:19 
- **Top Commit**: drop UEFI

## 📥 Download

### Latest Release
- **Filename**: `OrangeFox-*.zip`
- **Size**: 68M
- **Download**: [GitHub Releases](https://github.com/MRT-project/OrangeFox_recovery/releases/tag/4943175510392832)

### File Verification
| Type | Hash |
|------|------|
| **MD5** | `8d99e5313e05fba64aa40b467f6c7da4` |
| **SHA1** | `d55cd72b27c8b71e49e58ff7a9f8bb3a73ac4696` |

## ⚡ Features

- **Latest OrangeFox Recovery** with all standard features
- **Full touch interface** with intuitive gestures
- **ADB support** for debugging and file transfer
- **Custom theme** and maintainer branding
- **Comprehensive backup/restore** functionality
- **File manager** for easy file operations
- **Terminal emulator** for advanced users
- **Support for custom ROMs** and modifications

## 🛠️ Installation

### Prerequisites
- Unlocked bootloader
- Custom recovery compatible with your device
- Basic knowledge of ADB and Fastboot

### Method 1: Via Existing Recovery
1. Download the OrangeFox ZIP file
2. Boot into your current recovery
3. Flash the OrangeFox ZIP file
4. Reboot to recovery

### Method 2: Via Fastboot
```bash
fastboot flash recovery recovery.img
fastboot reboot recovery
