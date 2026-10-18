# VinylWave — Installation & Sideloading Guide

This guide covers installing **VinylWave v1.0.0-beta1** on an iPhone 5 or compatible legacy 32-bit iOS device (iOS 6.0–10.3.4).

---

## Prerequisites Checklist

1. **A compatible iOS device:** iPhone 5 (`iPhone5,1` / `iPhone5,2`), iPad 4, or iPod touch 5 running iOS 6.0 to 10.3.4.
2. **Jailbreak + AppSync Unified (Recommended):**
   - Sideloaded ad-hoc IPAs will fail or expire without AppSync Unified.
   - On jailbroken iOS, install **AppSync Unified** from `https://cydia.akemi.ai/`.
3. **TLSFix Tweak (Mandatory for Network Connectivity):**
   - Install **TLSFix** via Cydia / Zebra / Sileo.
   - Without TLSFix, legacy iOS cannot establish TLS 1.2+ HTTPS handshakes with YouTube streaming servers, causing stream requests to fail.

---

## Method 1: Sideloadly (Windows / macOS) — Recommended

1. Download and install **Sideloadly** on your computer (`https://sideloadly.io/`).
2. Connect your iPhone 5 to your computer via USB.
3. Download `VinylWave-iPhone5-armv7-v49-b14c.ipa` from the [GitHub Releases](https://github.com/ChopCho/VinylWave-Release/releases) page.
4. Drag and drop the `.ipa` file into Sideloadly.
5. Enter your Apple ID (used to generate a free developer certificate) or select **Ad-hoc sign** if your device has AppSync Unified installed.
6. Click **Start** to sign and install the app onto your iPhone 5.
7. If prompted on your device, navigate to **Settings > General > Device Management** and trust the certificate.

---

## Method 2: On-Device Installation via Filza File Manager (Jailbroken)

1. Open Safari on your jailbroken iPhone 5.
2. Navigate to `https://github.com/ChopCho/VinylWave-Release/releases/tag/v1.0.0-beta1`.
3. Tap on `VinylWave-iPhone5-armv7-v49-b14c.ipa` to download it.
4. When prompted, choose **Open in Filza**.
5. In Filza, tap the downloaded `.ipa` file and select **Install** from the top right.
6. Once the terminal displays `Result: 0`, respring or run `uicache` to refresh home screen icons.

---

## Method 3: AltStore / AltServer

1. Ensure **AltServer** is running on your computer.
2. Transfer the `.ipa` to your iPhone 5 via AirDrop, iCloud Drive, or web download.
3. Open **AltStore** on your device, navigate to the **My Apps** tab, tap the **+** button, and select `VinylWave-iPhone5-armv7-v49-b14c.ipa`.
4. Allow AltStore to complete installation.

---

## Troubleshooting

- **Crash immediately on launch:**  
  Verify that your device is jailbroken with **AppSync Unified** installed, or that you signed the IPA with a valid Apple ID profile.
- **Search or playback fails / Network Error:**  
  Ensure **TLSFix** is active. iOS 10.3.4 and earlier cannot connect to modern HTTPS endpoints without TLSFix.
- **No sound during background lock:**  
  Check that the device mute switch is not set to silent, and verify background audio permissions in Settings.
