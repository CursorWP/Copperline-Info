# 🧠 CopperlineOS Architecture

CopperlineOS is built on a modular, deterministic foundation inspired by the Amiga’s clarity and responsiveness. Each daemon is isolated, composable, and designed for reproducibility.

## Core Daemons

| Daemon         | Role & Functionality                                     |
|----------------|----------------------------------------------------------|
| `copperd`      | Timeline engine that orchestrates deterministic flow     |
| `compositord`  | Vulkan/KMS-based compositor for window rendering         |
| `blitterd`     | Handles 2D graphics operations and pixel manipulation    |
| `audiomixerd`  | Low-latency audio graph for real-time sound processing   |
| `arexx-next`   | Modern shell and scripting language with expressive syntax |
| `sdk-rs` / `sdk-c` | Developer SDKs for building apps in Rust or C       |

## System Traits

- **Deterministic**: No hidden state. Every process is reproducible.
- **Modular**: Daemons are isolated and replaceable.
- **Expressive**: Designed for clarity, responsiveness, and creative tooling.

## Timeline Engine (`copperd`)

`copperd` coordinates system events with precision. Ideal for media tools, real-time apps, and low-latency workflows.

## Compositor (`compositord`)

Built on Vulkan/KMS, `compositord` handles rendering with minimal overhead. It’s designed for speed, clarity, and deterministic redraws.

## Audio Graph (`audiomixerd`)

A real-time audio engine with deterministic routing and latency guarantees. Perfect for music tools, voice pipelines, and reactive sound design.

---

For deeper specs, see each daemon’s `/docs` folder.
