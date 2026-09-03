# The Future of Human Perception — Podcast Project

## Overview
A collaborative podcast series exploring how emerging technologies in augmented reality, spatial computing, and sensory interface design are reshaping human perception.

---

## Planned Episodes

### Episode 1: "The Rendering Gap — Perceptual Latency & the Quest for Immersion"
**Status:** Research & Outline  
**Target Release:** Q4 2026

**Core Question:** *Why does AR/VR still feel "not quite real," and how close are we to closing the perceptual gap?*

**Topics:**
- Motion-to-photon latency: the 20ms threshold and why it matters for presence
- Frame timing, judder, and the perceptual consequences of dropped frames
- **Dynamic Foveation** — using eye tracking to render only where you look (webxr #1420)
- The event-loop race conditions in composable XR runtimes (webxr #1400)
- How cutting GPUs and foveated rendering are reshaping the headset landscape
- Camera feed lag in AR platforms (arfoundation-samples #1206)

**Potential Guests:**
- **AdaRoseCannon** — Google; WebXR spec member, Dynamic Foveation champion (webxr #1420)
- **Rik Cabanier** — Immersive Web Inc.; inline stereo & haptics work
- **chrisdavidmills** — WebXR spec editor; visibility mask & session lifecycle
- **magcius** — WebXR contributor; EXT_clip_control and rendering pipelines

**Key Repos to Reference:**
- [immersive-web/webxr](https://github.com/immersive-web/webxr) — 3.1k★, the WebXR Device API spec
- [Unity-Technologies/arfoundation-samples](https://github.com/Unity-Technologies/arfoundation-samples) — 3.4k★, AR Foundation examples
- [hiukim/mind-ar-js](https://github.com/hiukim/mind-ar-js) — 2.7k★, Web-based face/image tracking

---

### Episode 2: "Beyond the Screen — Mixed Reality Interfaces & Spatial UI"
**Status:** Research & Outline  
**Target Release:** Q1 2027

**Core Question:** *If the interface is the entire room, what does UX design even mean?*

**Topics:**
- HTML-in-canvas inside WebXR: rendering DOM content as 3D textures (webxr #1414)
- Bidirectional interaction: raycasting from controllers back into HTML content
- Spatial haptics: can we standardize force feedback beyond gamepads? (webxr #1423)
- Defining hit-test regions and input forwarding for immersive content
- Controller component mapping — exposing button locations spatially (webxr #1428)
- The A-Frame & Three.js bridge: rendering AR content on the web (ar.js, mind-ar-js)
- HoloLens 2 spatial navigation for accessibility (Angelos-Kard/thesis-project)

**Potential Guests:**
- **AdaRoseCannon** — Google; HTML-in-canvas in immersive sessions
- **Rik Cabanier** — WebXR haptics & Gamepads module policy
- **s0i37** — 6DoF VR sample author (webxr-samples #241)
- **himorin** — WebXR samples maintainer; UI/UX for immersive galleries

**Key Repos to Reference:**
- [immersive-web/webxr-samples](https://github.com/immersive-web/webxr-samples) — 1.2k★, demo gallery
- [AR-js-org/AR.js](https://github.com/AR-js-org/AR.js) — 6.0k★, web marker tracking
- [hiukim/mind-ar-js](https://github.com/hiukim/mind-ar-js) — 2.7k★, face tracking
- [Hubs-Foundation/hubs](https://github.com/Hubs-Foundation/hubs) — 2.2k★, spatial social VR

---

### Episode 3: "Sounds in Space — Spatial Audio & the Illusion of Presence"
**Status:** Research & Outline  
**Target Release:** Q2 2027

**Core Question:** *If vision is half the battle, hearing is the whole war — how does spatial audio create (or break) presence?*

**Topics:**
- The missing standard: spatial audio APIs for the open web
- Mixed reality percussion & audio-visual synchronization (SYNCMR)
- Haptic-audio synchronization: the cross-sensory binding problem
- Soundscape APIs on visionOS and spatialized rendering pipelines
- Streaming spatial audio to WebXR: latency, interpolation, and perceptual coherence
- Obstacle detection audio for accessibility in MR (Angelos-Kard/thesis-project)
- Visually impaired navigation through spatial sound — a new paradigm?

**Potential Guests:**
- **alextawes19** — Creator of SYNCMR: mixed reality percussion & spatialized audio
- **AdaRoseCannon** — Cross-sensory perception in XR interfaces
- **Angelos-Kard** — HoloLens 2 spatial audio for accessible navigation

**Key Repos to Reference:**
- [alextawes19/SYNC-MR](https://github.com/alextawes19/SYNC-MR) — Mixed reality percussion with spatialized sound
- [Angelos-Kard/thesis-project](https://github.com/Angelos-Kard/thesis-project) — MR spatial audio for accessibility