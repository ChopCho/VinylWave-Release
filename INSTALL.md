# VinylWave — Installation & Sideloading Guide

This guide covers installing **VinylWave v1.0.0-beta1** on an iPhone 5 or compatible legacy 32-bit iOS device (iOS 6.0–10.3.4).

---

## Prerequisites Checklist

1. **A compatible iOS device:** iPhone 5 (`iPhone5,1` / `iPhone5,2`), iPad 4, or iPod touch 5 running iOS 6.0 to 10.3.4.
2. **AppSync Unified (Jailbroken Devices):**
   - Required when installing ad-hoc signed IPAs without a personal developer certificate.
   - Install **AppSync Unified** (`ai.akemi.appsyncunified`) via Zebra or Cydia from Karen's Repo (`https://cydia.akemi.ai/`).
   - If sideloading with a personal Apple ID via Sideloadly or AltStore, AppSync Unified is optional.
3. **appinst (App Installer) — Recommended for On-Device Installation:**
   - Package `ai.akemi.appinst` (available via Zebra or Cydia from `https://cydia.akemi.ai/`).
   - A command-line utility by Karen/あけみ & Linus Yang that allows installing `.ipa` packages directly on-device via terminal or SSH (`appinst <path-to-ipa>`).

---

## Method 1: Sideloadly (Windows / macOS) — Computer Sideloading

1. Download and install **Sideloadly** on your computer (`https://sideloadly.io/`).
2. Connect your iPhone 5 to your computer via USB.
3. Download `VinylWave-iPhone5-armv7-v49-b14c.ipa` from the [GitHub Releases](https://github.com/ChopCho/VinylWave-Release/releases) page.
4. Drag and drop the `.ipa` file into Sideloadly.
5. Enter your Apple ID (used to generate a free developer certificate) or select **Ad-hoc sign** if your device has AppSync Unified installed.
6. Click **Start** to sign and install the app onto your iPhone 5.
7. If prompted on your device, navigate to **Settings > General > Device Management** and trust the certificate.

---

## Method 2: On-Device Installation via appinst (Zebra / Terminal / SSH) — Recommended

1. Open **Zebra** (or Cydia) on your jailbroken iPhone 5.
2. Add Karen's Repo: `https://cydia.akemi.ai/`.
3. Search for and install **appinst (App Installer)** (this will automatically pull `AppSync Unified` as a dependency if not already installed).
4. Download `VinylWave-iPhone5-armv7-v49-b14c.ipa` to your device (via Safari, Filza, curl, or SFTP to `/var/mobile/Downloads/` or `/tmp/`).
5. Open your device terminal (MobileTerminal, NewTerm) or connect via SSH, and run:
   ```bash
   appinst /var/mobile/Downloads/VinylWave-iPhone5-armv7-v49-b14c.ipa
   ```
6. The app will install cleanly into `/Applications/` and appear on your home screen.

---

## Method 3: On-Device Installation via Filza File Manager (Jailbroken)

1. Open Safari on your jailbroken iPhone 5.
2. Navigate to `https://github.com/ChopCho/VinylWave-Release/releases/tag/v1.0.0-beta1`.
3. Tap on `VinylWave-iPhone5-armv7-v49-b14c.ipa` to download it.
4. When prompted, choose **Open in Filza**.
5. In Filza, tap the downloaded `.ipa` file and select **Install** from the top right.
6. Once the terminal displays `Result: 0`, respring or run `uicache` to refresh home screen icons.

---

## Method 4: AltStore / AltServer

1. Ensure **AltServer** is running on your computer.
2. Transfer the `.ipa` to your iPhone 5 via AirDrop, iCloud Drive, or web download.
3. Open **AltStore** on your device, navigate to the **My Apps** tab, tap the **+** button, and select `VinylWave-iPhone5-armv7-v49-b14c.ipa`.
4. Allow AltStore to complete installation.


---

## Troubleshooting

- **Crash immediately on launch:**  
  Verify that your device is jailbroken with **AppSync Unified** installed, or that you signed the IPA with a valid Apple ID profile.
- **Search or playback fails / Network Error:**  
  Verify that the device has an active Wi-Fi or cellular data connection and can reach internet services.
- **No sound during background lock:**  
  Check that the device mute switch is not set to silent, and verify background audio permissions in Settings.
