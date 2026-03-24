# 🎧 Fluxify
> **Flux your Spotify. Remix live. Vibe together.**

Fluxify is a modern, responsive web application designed to manipulate audio in real-time. Built with a cross-platform architecture in mind, it provides users with powerful tools to remix, speed up, and add atmospheric effects to their favorite tracks directly within the browser.

## 🚀 The Architecture & Strategy
This project was engineered using an **Incremental Development Model** to ensure stability and continuous feature delivery. By utilizing a **Hybrid Engine Architecture**, Fluxify actively integrates the live Spotify Web API alongside a "Mock Data Sandbox" and Local File Uploads. This dual-system completely bypasses third-party DRM restrictions and Premium subscription lockouts, allowing for true, uninterrupted audio manipulation.

## 🛠️ Tech Stack & Design
* **Frontend:** React.js, Vite
* **Styling:** Tailwind CSS (Frosted-glass UI, Dynamic Mesh Gradients)
* **Branding:** Custom Typography (Embedded CSS from custom font generator for unique localized logo)
* **Audio Processing:** Web Audio API (Native Browser Engine)
* **Data Integration:** Spotify Web API (REST) + Local Mock DB
* **Offline Storage:** IndexedDB / LocalForage
* **Version Control:** Git & GitHub

## 🗺️ Incremental Version Roadmap

### ✅ Version 1.0: Foundation & Hybrid Engine (Current)
* React Vite engine deployment and cross-platform responsive UI architecture.
* Integration of custom brand typography and localized logo UI components.
* **Dual-Data Setup:** Connecting the live Spotify Web API (via Client ID/Secret) while simultaneously building the Mock Data Sandbox fallback.
* "Local MP3 Upload" feature, allowing users to import files directly from their device.

### 🚧 Version 1.5: The Audio Engine (In Progress)
* Connecting the browser's native Web Audio API to the React UI.
* Engineering the interactive manipulation dial.
* Implementing live audio filters: Nightcore (Pitch/Speed shift) and Slowed + Reverb.

### 🔜 Version 2.0: Offline Persistence
* Integration of `localforage` for browser-based IndexedDB storage.
* Background `MediaRecorder` implementation to capture live remixes.
* "Save to Device" functionality for legally exporting custom local remixes.

---
*Developed by Ejiro Rickson Emmanuel*