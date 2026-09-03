<div align="center">

<img src="https://raw.githubusercontent.com/Clash-Projects/LastWave-native/main/app/src/main/res/mipmap-xxxhdpi/ic_launcher.png" alt="LastWave Logo" width="120" height="120" style="border-radius: 50%;" />

# LastWave Website

### Official Web Portal & Interactive Documentation for LastWave

<p align="center">
  <a href="https://github.com/dekuiuto-code/LastWave-Website-">
    <img src="https://img.shields.io/badge/Platform-Web_/_HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white&labelColor=1a1a1a" alt="Platform" />
  </a>
  <a href="https://github.com/Clash-Projects/LastWave-native">
    <img src="https://img.shields.io/badge/App-LastWave_Native-00E5FF?style=for-the-badge&logo=android&logoColor=white&labelColor=1a1a1a" alt="LastWave Native" />
  </a>
  <a href="#">
    <img src="https://img.shields.io/badge/License-GPL_v3.0-3DDC84?style=for-the-badge&labelColor=1a1a1a" alt="License" />
  </a>
</p>

<p align="center">
  <a href="https://t.me/clashprojects">
    <img src="https://img.shields.io/badge/Telegram-Join_Community-24A1DE?style=flat-square&logo=telegram&logoColor=white" alt="Telegram Community" />
  </a>
  <a href="https://github.com/Clash-Projects/LastWave-native/releases">
    <img src="https://img.shields.io/badge/Download-Universal_APK-blue?style=flat-square" alt="Download APK" />
  </a>
</p>

</div>

<br/>

## Overview

Welcome to the official repository for the **LastWave Web Portal**. Designed and developed completely from scratch, this website serves as the landing page, release hub, and interactive technical documentation for **LastWave** — an open-source, high-resolution native music streaming client and player developed for Android 10+.

---

## Website Structure & Features

### 1. Landing Page (`/home`)
- **Hero Section:** High-resolution branding, taglines, and direct download links for the latest Android releases.
- **Core Feature Highlights:**
  - **Lossless & Bit-Perfect:** Native Kotlin audio engine with Studio Master FLAC playback up to 24-bit / 192kHz and parametric equalization.
  - **Kinetic Lyrics & Last.fm:** Real-time LRCLIB syllable synchronization, rich typography animations, and automatic Last.fm scrobbling.
  - **Free & Open Source:** GPL 3.0 license, zero ads, zero trackers, and offline autonomy.
- **Team & Credits:** Highlights for developers and community contributors.

### 2. Documentation Hub (`/documentation`)
- **Getting Started:**
  - *What is LastWave?* Overview of high-res streaming capabilities and app architecture.
  - *Installation & Setup:* Step-by-step guidance for installing direct APK releases on Android 10+ (API 29+).
  - *Lossless Audio Configuration:* Audio offload settings, 4096-frame buffer configurations for USB DACs, and ReplayGain setup.
- **Core Features:**
  - *Synchronized Lyrics (LRCLIB):* Full-screen lyrics canvas, millisecond timestamp seeking, and ±50ms delay offsetting.
  - *Last.fm Scrobbling:* Secure token-based authentication for tracking listening habits.
  - *Equalizer & Volume Boost:* Built-in 10-band parametric EQ with audiophile targets (Harman, Diffuse Field, Acoustic, Bass Boost).
  - *InnerTubeX Engine:* High-efficiency YouTube Music catalog streaming with local encrypted caching.
- **System & Optimization:**
  - *Background Playback & Battery:* Optimization guidelines for uninterrupted background playback.
  - *Frequently Asked Questions:* Common troubleshooting and setup queries.

---

## Project Structure

```text
LastWave-Website/
├── index.html       # Single-page web portal application layout
├── assets/          # Custom CSS, JS modules, dynamic themes, and UI assets
├── docs/            # Markdown documentation pages and core guides
├── README.md        # Repository overview
└── LICENSE          # GNU General Public License v3.0
