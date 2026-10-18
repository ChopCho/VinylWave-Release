# VinylWave (v1.0.0-beta1)

> **Retro vinyl-themed YouTube Music client for legacy 32-bit iOS (iPhone 5, iOS 6.0–10.3.4)**

VinylWave is a lightweight, retro-styled music player custom-built for legacy 32-bit iOS hardware. Powered by a responsive native audio engine, VinylWave brings modern music streaming to vintage Apple devices with a tactile turntable interface, background audio playback, and classic iPod navigation.

---

## Supported Devices & Compatibility

- **Target Device:** iPhone 5 (`iPhone5,1`, `iPhone5,2`), iPad (4th generation), iPod touch (5th generation).
- **Target Architecture:** Apple A6 / 32-bit ARMv7 (`armv7`).
- **Supported iOS Versions:** iOS 6.0 through iOS 10.3.4 (Optimized for iOS 10.3.4).

---

## Essential Prerequisites

Before installing VinylWave on legacy iOS, two runtime components are required:

1. **AppSync Unified (Jailbroken Devices):**  
   Required to install and run ad-hoc signed `.ipa` packages without signature expiration or revokes. Install via Cydia/Zebra from `https://cydia.akemi.ai/`.
2. **TLSFix Tweak (Mandatory for Network Connectivity):**  
   Legacy iOS (iOS 6.0–10.3.4) does not natively support modern TLS 1.2/1.3 cipher suites required by HTTPS streaming endpoints. You **must** install the **TLSFix** tweak (by `@nfzerox`) via Cydia or your package manager to allow VinylWave to connect to streaming servers.

---

## Download & Installation

The official distribution format is a standalone sideloadable `.ipa` application package.

- **Direct Download:** Download `VinylWave-iPhone5-armv7-v49-b14c.ipa` from the [Releases](https://github.com/ChopCho/VinylWave-Release/releases) tab.
- **Installation Guide:** See [INSTALL.md](INSTALL.md) for detailed sideloading instructions via Sideloadly, AltStore, Apple Configurator, or Filza.

### Integrity Verification

Always verify the SHA-256 checksum of your downloaded binary before installation:

```bash
sha256sum VinylWave-iPhone5-armv7-v49-b14c.ipa
```

**Expected Checksum:**
```text
A8EF56196788B4DE698B528411E9721EC724BF3DF1BA9E49B807780EB807DCC0  VinylWave-iPhone5-armv7-v49-b14c.ipa
```

---

## Features

- **Retro Vinyl Turntable UI:** Authentic animated spinning vinyl record with interactive tonearm and album artwork grooves.
- **Native Audio Streaming:** Low-latency playback optimized for Apple A6 processors with hardware-accelerated decoding.
- **Background Playback & Lock Screen Controls:** Full lock screen artwork, playback scrub controls, and remote command center integration.
- **Search & Trending Music:** Search catalog, browse trending releases, and organize local favorite playlists.
- **Classic iPod Mode:** An optional nostalgic interface mirroring the classic iPod click-wheel navigation layout.
- **Low Memory Footprint:** Tuned specifically for devices with 1 GB or less of RAM.

---

## Legal & Disclaimers

- VinylWave is an independent client and is not affiliated with, endorsed by, or sponsored by Google LLC, YouTube, or Apple Inc.
- For complete terms and disclaimers, please consult [DISCLAIMER.md](DISCLAIMER.md).
- For third-party font, icon, and component acknowledgments, please refer to [THIRD_PARTY_NOTICES.md](THIRD_PARTY_NOTICES.md).
- End-user distribution terms are detailed in [LICENSE](LICENSE).
