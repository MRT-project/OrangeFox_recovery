# 🦊 OrangeFox Recovery for {{DEVICE}} ({{DEVICE_NAME}})

<div align="center">

![OrangeFox](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcSKQkL6PDlh_yc0uuf_zfIhuuUsBikUf6A5JZbwQ-tX6w&s=10)

**Unofficial Build - {{BUILD_DATE}}**

[![Build Status](https://img.shields.io/badge/Build-Success-brightgreen)]()
[![OrangeFox](https://img.shields.io/badge/OrangeFox-{{FOX_SYNC_BRANCH}}-orange)]()
[![Android](https://img.shields.io/badge/Android-12.1-blue)]()
[![Maintained](https://img.shields.io/badge/Maintained-Yes-green)]()

</div>

## 📋 Device Information

- **Device**: {{DEVICE}}
- **Codename**: {{DEVICE_NAME}}
- **OrangeFox Branch**: {{FOX_SYNC_BRANCH}}
- **Build Date**: {{BUILD_DATE}}
- **Build Time**: {{ORF_TIME}}
- **Top Commit**: {{DT_COMMIT}}

## 📥 Download

### Latest Release
- **Filename**: `OrangeFox-*.zip`
- **Size**: {{ORF_SIZE}}
- **Download**: [GitHub Releases](https://github.com/{{REPO_PUBLISH}}/releases/tag/{{ORF_ID}})

### File Verification
| Type | Hash |
|------|------|
| **MD5** | `{{ORF_MD5}}` |
| **SHA1** | `{{ORF_SHA1}}` |

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
