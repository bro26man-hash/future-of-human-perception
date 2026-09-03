# AR & Spatial Computing Repositories — Research Notes

## Tier 1: Core Specification & Standards

### [immersive-web/webxr](https://github.com/immersive-web/webxr) — 3,151★
**The WebXR Device API Specification.** The definitive standard for AR/VR on the web.
- *Language:* Bikeshed / Specification
- *Last updated:* 2026-09-03
- **Active Issues:**
  - #1420 — Dynamic Foveation: eye-tracked rendering optimization without exposing gaze data
  - #1423 — Better haptics support: standardizing force feedback for immersive devices
  - #1414 — WebXR integration with HTML-in-canvas: bidirectional interaction between DOM and 3D
  - #1400 — Missing tasks in parallel steps in WebXR Device API: event-loop and task-queuing correctness
  - #1428 — Expose where buttons and other components are located on controllers

### [immersive-web/webxr-samples](https://github.com/immersive-web/webxr-samples) — 1,161★
**Sample implementations demonstrating the WebXR Device API.**
- *Language:* HTML / JavaScript
- *Last updated:* 2026-08-26
- **Active Issues:**
  - #241 — VR 6DoF: missing demo for 6-degrees-of-freedom 
  - #240 — demos for the visibilitymaskchange event
  - #235 — XRGPUBinding.getPreferredColorFormat not used for pipelines
  - #228 — XRGPUBinding Projection-Layer scale factor causing cut off
  - #227 — GL_INVALID_ENUM on projection layers with texture-array

## Tier 2: Frameworks & SDKs

### [Unity-Technologies/arfoundation-samples](https://github.com/Unity-Technologies/arfoundation-samples) — 3,434★
**Example content for Unity projects based on AR Foundation.**
- *Language:* C#
- *Last updated:* 2026-09-02
- **Active Issues:**
  - #1221 — Version typo in README
  - #1220 — AR Foundation Image Tracking Offset / Drift for Large-Scale Models
  - #1218 — VisionOSReferenceObjectEntry export bug
  - #1213 — Meta Quest 3 TryRequestSceneCapture black background
  - #1206 — Camera feed extreme lag after AR Foundation upgrade
  - #1199 — Tracked images not removed from mutable reference image library
  - #1181 — Raycasts flicker against ARMesh on Quest 3

### [hiukim/mind-ar-js](https://github.com/hiukim/mind-ar-js) — 2,720★
**Web Augmented Reality: Image Tracking, Face Tracking via TensorFlow.js.**
- *Language:* JavaScript
- *Last updated:* 2026-09-01
- **Active Issues:**
  - #581 — Fails on iOS 27.0 (iPhone 16 Pro Max): shader linking failure
  - #580 — How to increase the detection distance of faces
  - #572 — Suggestions to optimize loading speed of MindAR-based experiences
  - #571 — How to Perform Load Testing for WebAR Sites?

## Tier 3: Engines & Platforms

### [playcanvas/engine](https://github.com/playcanvas/engine) — 16,612★
**Powerful web graphics runtime built on WebGL, WebGPU, WebXR and glTF.**
- *Language:* JavaScript
- *Last updated:* 2026-09-03

### [Hubs-Foundation/hubs](https://github.com/Hubs-Foundation/hubs) — 2,214★
**Duck-themed multi-user virtual spaces in WebVR. Built with A-Frame.**
- *Language:* JavaScript
- *Last updated:* 2026-08-24

### [De-Panther/unity-webxr-export](https://github.com/De-Panther/unity-webxr-export) — 1,257★
**Develop and export WebXR experiences using Unity WebGL.**
- *Language:* JavaScript
- *Last updated:* 2026-09-01

### [tentone/nunuStudio](https://github.com/tentone/nunuStudio) — 2,228★
**Web powered cross-platform 3D, WebXR game engine.**
- *Language:* JavaScript
- *Last updated:* 2026-09-01

## Tier 4: Specialized & Experimental

### [alextawes19/SYNC-MR](https://github.com/alextawes19/SYNC-MR)
**Mixed reality percussion and audio-visual experience featuring spatialized sound, real-time effects, and interactive instrument mechanics.**
- *Language:* C#
- *Last updated:* 2026-02-27
- *Relevance:* Spatial audio research, MR instrument design

### [Angelos-Kard/thesis-project](https://github.com/Angelos-Kard/thesis-project)
**Mixed reality app for Microsoft HoloLens 2 that helps visually impaired users navigate unfamiliar spaces safely. Features obstacle detection and spatial audio.**
- *Language:* ShaderLab
- *Relevance:* Accessibility + spatial audio in MR

### [Caraveo/ZiaXR](https://github.com/Caraveo/ZiaXR)
**The Open Platform for Spatial Computing (Augmented Reality).**
- *Relevance:* Open hardware/software platform vision for AR
- *Key concept:* XTP:// Extensible Transfer Protocol, Expo Apps, Open License

### [autodesk-platform-services/data-exchange-immersive-demo](https://github.com/autodesk-platform-services/data-exchange-immersive-demo)
**Experimental project exploring Data Exchanges in AR and spatial computing applications.**
- *Language:* C# / TypeScript / Swift
- *Relevance:* Cross-platform data exchange for immersive experiences (glTF, USDZ, OBJ)