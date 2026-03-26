# SkyData.bond - Ultimate Device Performance Test

**Website:** [https://skydata.bond/](https://skydata.bond/)

## Overview
SkyData.bond is a simple yet powerful **browser-based benchmarking tool**. It allows you to test your device’s **CPU, GPU, RAM, Storage, and more** entirely locally — no data is sent to any server. Perfect for developers, gamers, engineers, or anyone wanting accurate performance metrics without installing software.

- **Fully Local:** 100% client-side, runs in your browser.
- **Privacy First:** 0% data sent, no tracking, no cookies.
- **Multiple Tests:** Over 80 individual tests across CPU, GPU, RAM, Storage, Network, System, Display, and Battery.
- **Bi-Lingual:** English main interface with some Arabic translations for certain tests.

## Features

### CPU Tests (15)
- Single-Core Math, Multi-Core Threading, Floating Point, Integer Math
- Prime Number Generation, AES Encryption, SHA-256 Hashing
- Physics Engine, Matrix Multiplication, Branch Prediction
- Cache Latency, Data Compression, Video Encoding, Instruction Fetch

### GPU Tests (16)
- WebGL Triangle, Texture Fill, Fragment/Vertex Shader
- Particles, Raymarching, VRAM Limit, Antialiasing
- Lighting & Shadows, High-Poly Mesh, WebGPU Support, FPS Pacing

### RAM Tests (14)
- Sequential/Random Read/Write, Memory Allocation
- Garbage Collection, Typed Array, JSON Parse, DOM Nodes
- Out-of-Memory Limit, others

### Storage Tests (10)
- IndexedDB, LocalStorage, Cache API, File System API
- SQLite WASM, Persistent Storage, others

### Network, System, Display & Battery Tests
- Network: Ping, WebSocket, WebRTC, DNS, Fetch API, HTTP/2, Concurrent Connections
- System: Screen Resolution, OS Detection, Hardware Concurrency, Sensors, Clipboard
- Display: Refresh Rate, HDR, Dead Pixel, Touch Responsiveness
- Battery: Battery Level API, Charging Status, Power Drain

> ⚠️ Some tests are marked WIP (Work In Progress) and may not be fully functional yet.

## How to Use
1. Open [SkyData.bond](https://skydata.bond/) in your browser.
2. Select a test (CPU, GPU, RAM, etc.).
3. Click **Start Benchmark**.
4. Wait for the performance score and telemetry data.
5. Optional: Open multiple tests in separate tabs to compare metrics.

## Technology
- Vanilla JavaScript
- Web APIs: WebGL, WebGPU, WebRTC, Battery Status API, IndexedDB, File System API
- Client-side only — no frameworks, no backend

## Privacy & Security
- **0% data sent**  
- No analytics, tracking, or login required  
- All computations happen locally in the browser  

## Target Audience
- Web developers  
- Gamers and tech enthusiasts  
- Engineers or anyone wanting accurate device benchmarks without external software  

## Contribution
- Some tests are WIP and contributions are welcome.
- Feel free to fork the repo, add tests, or improve translations.

## License
- MIT License (or specify your license if different)
