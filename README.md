# Handrix
### Hand + Matrix — Real-time Hand Tracking AR Experience

<div align="center">

![Version](https://img.shields.io/badge/version-2.0.0-00ffcc?style=flat-square)
![License](https://img.shields.io/badge/license-MIT-ff7700?style=flat-square)
![Platform](https://img.shields.io/badge/platform-Web%20Browser-aa44ff?style=flat-square)
![No Backend](https://img.shields.io/badge/backend-none-00ff44?style=flat-square)

**Handrix** is a browser-based Augmented Reality experience that tracks your hands in real-time and overlays stunning neon visual effects — magic shields, lightning arcs, matrix rain, and spatial audio — all running locally in your browser with zero installation.

</div>

---

## What is Handrix?

Handrix turns your webcam into a portal of visual magic. Using Google's MediaPipe hand tracking AI, it detects your hands frame-by-frame and renders:

- **Doctor Strange–style magic shields** that follow your open palms
- **Lightning arcs** that crackle between your fingertips when two hands come close
- **Matrix rain** that reacts to your hand movement speed
- **Pinch gesture** that triggers shockwave ripples and zap sounds
- **7 visual themes** — each with a unique color palette

Everything runs **100% in your browser**. No server. No install. No data upload.

---

## Preview

```
┌─────────────────────────────────────────────┐
│                                             │
│   ✦ Magic Shield follows open palm          │
│   ⚡ Lightning between two hands            │
│   ◈ Matrix rain reacts to movement          │
│   ♫ Spatial audio hum between hands         │
│                                             │
└─────────────────────────────────────────────┘
```

---

## Features

| Feature | Description |
|---------|-------------|
| ✋ Hand Tracking | Detects up to 2 hands with 21 landmarks each |
| ✦ Magic Shield | Rotating geometric sigil rendered on open palm |
| ⚡ Lightning | Multi-segment electric arcs between fingertips |
| 🌧 Matrix Rain | Katakana character rain — speed tied to hand velocity |
| 💥 Pinch Gesture | Triggers shockwave + zap sound effect |
| 🎨 7 Themes | Sorcerer, Time Stone, Rainbow, Cyberpunk, Lava, Ocean, Galaxy |
| 🔊 Spatial Audio | Hum pitch & volume based on distance between hands |
| 🌑 Vignette + Scanlines | Cinematic AR overlay polish |
| 🖥 No Install | Pure HTML — runs in any modern browser |

---

## Tech Stack

| Technology | Purpose |
|-----------|---------|
| **MediaPipe Hands** | Real-time hand landmark detection (AI model) |
| **Web Audio API** | Procedural sound effects and spatial hum |
| **Canvas 2D API** | All visual rendering (particles, shields, ripples) |
| **HTML5 Video** | Webcam input stream |
| **Space Grotesk** | UI typography |
| **JetBrains Mono** | HUD monospace labels |

Zero npm packages. Zero frameworks. Zero backend.

---


## How to Use

```
1. Open the file in Chrome / Edge / Firefox
2. Click  "Enter Experience"
3. Allow camera permission when prompted
4. Show your hands to the webcam
5. Try these gestures:
```

| Gesture | Effect |
|---------|--------|
| ✋ Open palm | Magic shield appears on your hand |
| ✊ Fist | Shield disappears |
| 🤏 Pinch (thumb + index) | Shockwave ripple + zap sound |
| 🙌 Two hands close | Lightning arcs between fingertips + hum audio |
| 🤚 Move fast | Matrix rain speeds up |

---

## Visual Themes

| Theme | Color | Vibe |
|-------|-------|------|
| **Sorcerer** | 🟠 Orange | Doctor Strange magic |
| **Time Stone** | 🟢 Green | Infinity gauntlet |
| **Rainbow** | 🟣 Multi | Spectrum burst |
| **Cyberpunk** | 🔵 Cyan/Red | Neon dystopia |
| **Lava** | 🔴 Red-Orange | Volcanic energy |
| **Ocean** | 🔵 Blue | Deep sea bioluminescence |
| **Galaxy** | 🟣 Purple | Cosmic starfield |

---

## File Structure

```
handrix/
│
├── neon-aura-ar.html       ← Entire app (single file)
└── README.md               ← This file
```

That's it. The whole experience lives in **one HTML file**.

---



## Performance Tips

- Use in a **well-lit room** — MediaPipe works best with good lighting
- Keep your hands **within frame** — about 40–80cm from camera
- Close other **heavy browser tabs** for smoother FPS
- Use **1080p webcam** for sharper hand detection
- If FPS drops below 20, switch to a simpler theme like **Sorcerer**

---

## How It Works

```
Webcam Feed
    │
    ▼
MediaPipe Hands AI
    │  21 landmarks per hand (x, y, z)
    ▼
Gesture Detection
    │  Pinch / Open / Fist / Speed
    ▼
Canvas Render Pipeline
    ├── bgCanvas  →  Matrix rain (persistent ghosting)
    └── mainCanvas → Shields / Lightning / Particles
            │
            ▼
        Web Audio API
            └── Hum oscillator / Zap synth
```

---



<div align="center">

**Handrix** — Where your hands become the interface.

*Built with pure HTML · No install · No backend · Just magic.*

</div>
