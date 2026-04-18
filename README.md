<p align="center">
  <img src="GitHub%20assets/App%20Icon%20complete.png" width="120" alt="Drawgether icon" />
</p>

<h1 align="center">Drawgether</h1>
<p align="center"><em>Real-time collaborative drawing for Apple Vision Pro</em></p>

<p align="center">
  <img src="https://img.shields.io/badge/Platform-visionOS%202.0%2B-blue?style=flat-square" />
  <img src="https://img.shields.io/badge/Swift-6.0-orange?style=flat-square&logo=swift" />
  <img src="https://img.shields.io/badge/Status-In%20Development-green?style=flat-square" />
</p>

---

## About

**Drawgether** is a visionOS app that lets you and your friends draw together in real time — both in a shared 3D immersive space and on traditional 2D canvases — all at the same time.

Paint with your fingers directly in your environment using hand tracking, open flat canvases that float in your room, and watch your collaborators' strokes appear live as they draw. No accounts, no servers, no friction — just pick up your hand and start creating together.

---

## Screenshots

> Screenshots coming soon.

<!-- Replace the placeholders below with your actual screenshots -->
<!--
<p align="center">
  <img src="assets/screenshot1.png" width="32%" />
  <img src="assets/screenshot2.png" width="32%" />
  <img src="assets/screenshot3.png" width="32%" />
</p>
-->

---

## Key Features

- **Dual drawing modes** — paint 3D strokes that float in your environment, and open 2D canvas windows at the same time
- **Real-time collaboration** — powered by SharePlay, strokes sync point-by-point so collaborators see your drawing unfold live
- **Hand tracking input** — use your index finger as a brush; no controller required
- **Three brush materials** — matte, metallic, and glowing finishes
- **Flexible canvases** — choose between small, medium, and large 2D canvas sizes
- **Synchronized clear** — clear the board for all participants at once
- **Spatial personas** — designed for side-by-side collaboration in a shared immersive space
- **Playful design system** — a custom cartoon visual language with rounded typography, hand-drawn shadows, and an expressive color palette

---

## Technology

| Area | Stack |
|---|---|
| Language | Swift 6.0 |
| UI | SwiftUI |
| 3D Rendering | RealityKit + custom tube-mesh geometry |
| Hand Tracking | ARKit |
| Collaboration | SharePlay (GroupActivities) |
| Platform | visionOS 2.0+ |

---

## Privacy

Drawgether is built with privacy in mind:

- **No account required** — the app uses your existing Apple ID and FaceTime infrastructure
- **No external servers** — drawings are never sent to third-party servers; collaboration runs entirely through Apple's SharePlay framework
- **Invite-only sessions** — only participants you explicitly invite via FaceTime can join your drawing session
- **Local storage** — strokes exist only on your device and in the active session; nothing is persisted to the cloud
- **Clear at any time** — you can wipe the canvas and exit the session whenever you want

---

## Requirements

| | |
|---|---|
| Device | Apple Vision Pro |
| OS | visionOS 2.0 or later |
| Xcode | 16.0+ (to build) |
| SharePlay | Requires an active FaceTime call between participants |

---

## License

This project is released under the **MIT License**.

---

<p align="center">
  <sub>
    The source code for this project is private and maintained by the developer.<br />
    This repository serves as a public portfolio showcase.
  </sub>
</p>
