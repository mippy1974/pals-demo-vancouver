# P.A.L.S. — Pet Awareness for Living Safely™

[![Patent Pending](https://img.shields.io/badge/Patent-Pending-gold?style=flat-square)](https://uspto.gov)
[![TM #99664426](https://img.shields.io/badge/TM-%2399664426-teal?style=flat-square)](https://uspto.gov)
[![Alexa Skill](https://img.shields.io/badge/Alexa-Pet%20Aware-blue?style=flat-square)](https://www.amazon.com/alexa-skills)
[![Live Demo](https://img.shields.io/badge/Demo-GitHub%20Pages-brightgreen?style=flat-square)](https://mippy1974.github.io/pals-demo)

> **LiDAR-powered fall prevention for older adults aging in place — with the pets they love.**

---

## 🐾 What is P.A.L.S.?

P.A.L.S. is a **patent-pending LiDAR-based safety system** that detects where a pet is located within the home and alerts caregivers and residents when a pet enters a high-risk fall zone — before a fall happens.

Pets are the most common in-home trip hazard for older adults. P.A.L.S. turns that risk into a dignity-centered safety solution that keeps both pets and people thriving.

**Core features:**
- 📡 **Real-time LiDAR detection** — RPLIDAR C1 + ESP32 hardware tracks pet location room-by-room
- 🗺️ **Risk-weighted floor plan** — zones are scored by fall probability and updated continuously
- 📲 **Caregiver alerts** — SMS/app notifications when a pet enters a high-risk zone
- 🔊 **Alexa voice integration** — residents can ask *"Alexa, ask Pet Aware where is Frida?"*
- 🔒 **Privacy-first** — no cameras, no images, no facial recognition

---

## 🖥️ Live Demo

👉 **[Launch Interactive Demo](https://mippy1974.github.io/pals-demo)**

The demo simulates a full P.A.L.S. caregiver dashboard with:
- Animated floor plan with real-time pet tracking (Frida 🐾)
- Live risk zone heat map
- Triggered alert scenarios — step through a full trip hazard event
- Alexa voice command simulation
- Pet Aware Alexa skill demonstration

---

## 📁 Repository Contents

| File | Description |
|------|-------------|
| `index.html` | **Main conference demo** — full interactive caregiver dashboard |
| `heatmap.html` | LiDAR heat map component — animated pet path tracking |
| `qr-card.html` | Printable QR business card for conference distribution |
| `pals-demo-v2.jsx` | React component version of the demo (for development) |
| `assets/pals_icon_512.png` | Official P.A.L.S. logo |

---

## 🚀 Deploy to GitHub Pages

1. Fork or clone this repo
2. Go to **Settings → Pages**
3. Set source to `Deploy from a branch` → `main` → `/ (root)`
4. Your demo will be live at `https://[username].github.io/pals-demo`

That's it — no build step, no dependencies. Pure HTML/CSS/JS.

---

## 🔧 Hardware

The working prototype runs on:
- **RPLIDAR C1** — 360° LiDAR sensor
- **ESP32** — WiFi-enabled microcontroller
- Firmware: `PALS_Frida_Detection_v1.ino` *(not included in public repo)*

---

## 📖 Background

P.A.L.S. was developed by **Dr. Melissa Mansfield, PhD, NAPG-C**, Founder & CEO of [The Gerontechnology Group](https://gerontechnologygroup.com).

Dr. Mansfield is a gerontologist and eldercare technology specialist with 15+ years of experience. P.A.L.S. is grounded in her research on pet companionship among older adults aging in place and evaluated using her proprietary **Dignity-Centered AI Evaluation Framework (DCAEF)**.

- 📄 Published: *Innovation in Aging* (2025)
- 🎤 Presented: ISG Gerontechnology Conference, Vancouver (March 2026)
- 🏠 Addressing the **$2.2B HCBS fall prevention market**

---

## 🤝 Connect

**Dr. Melissa Mansfield, PhD, NAPG-C**  
Founder & CEO, The Gerontechnology Group  
🌐 [gerontechnologygroup.com](https://gerontechnologygroup.com)  
💼 [LinkedIn](https://linkedin.com/in/melissamansfield)

> *"Technology should extend dignity, not compromise it."*

---

*P.A.L.S.™ is a trademark of The Gerontechnology Group. Patent Pending (Serial #99664426). All rights reserved.*
