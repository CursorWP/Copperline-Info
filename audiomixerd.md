# 🔊 audiomixerd — Low-Latency Audio Graph

`audiomixerd` powers CopperlineOS’s sound — a deterministic audio engine built for real-time responsiveness and modular routing.

## Purpose

- Mixes and routes audio streams
- Supports reactive sound design
- Guarantees latency bounds and reproducibility

## Features

- Node-based audio graph
- Timeline sync via `copperd`
- Shell-triggered sound events

## Developer Notes

- Avoid dynamic state — use declarative audio graphs
- Profile latency across devices
- Integrate with shell and UI for feedback loops

## Example Use Cases

- System sounds and alerts
- Real-time music tools
- Audio-reactive UI elements

---

`audiomixerd` doesn’t just play sound — it orchestrates experience.
