# subway-surfers-mod-fixes
# Subway Surfers Android Client — Common Error Resolutions & Run Guide

Comprehensive diagnostic documentation for resolving package conflicts, asset path drops, and runtime freezes when installing the modified Subway Surfers client.

## ⚠️ Common Installation & Runtime Errors

| Error Symptom | Root Cause | Immediate Fix |
| :--- | :--- | :--- |
| **"App Not Installed"** | Signature mismatch (`INSTALL_FAILED_UPDATE_INCOMPATIBLE`) | Completely uninstall official Play Store build (including Secure Folder / Dual Apps) |
| **Grayed-out Toggle** | Android Restricted Settings barrier | Enable "Allow restricted settings" in App Info three-dot menu |
| **Black Screen on Launch** | Missing OBB directory / corrupt shader buffer | Place `.obb` inside `Android/obb/com.kiloo.subwaysurf/` and clear cache |
| **Parse Error** | Corrupt package or Android OS below 6.0 | Verify SHA-256 integrity and check minimum OS version |
| **Insufficient Storage** | Lack of unpacking space during decompression | Free at least 500 MB–1 GB on internal system partition |
| **Random App Freezes** | Aggressive OEM background killers | Set Battery Usage profile to "Unrestricted" |

## 🔧 Step-by-Step Fixes

### 1. Clearing Cryptographic Signature Mismatches
1. Uninstall any existing version of Subway Surfers from the primary app drawer.
2. Check Samsung Secure Folder, Xiaomi Dual Apps, or Parallel Space for duplicate packages.
3. Restart the device to flush cached certificate tokens.
4. Re-run the installation package.

### 2. Manual OBB Asset Routing
If running an asset-split package, route the expansion directory manually:
- Ensure the destination path exists: `Internal Storage/Android/obb/com.kiloo.subwaysurf/`
- Move the expansion file into that directory prior to initial application startup.

For direct package downloads, validated SHA-256 checksums, and the complete installation suite:
👉 **[Download Verified Subway Surfers Mod](https://subwaysurfersmod.org/)**
