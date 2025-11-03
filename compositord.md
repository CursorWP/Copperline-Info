# 🖼️ compositord — Vulkan/KMS Compositor

`compositord` handles all visual rendering in CopperlineOS using Vulkan and KMS for speed, clarity, and deterministic redraws.

## Purpose

- Renders windows and UI elements
- Manages display layers and transitions
- Ensures low-latency, reproducible visuals

## Features

- Vulkan-based rendering pipeline
- KMS integration for direct hardware access
- Modular layer management

## Developer Notes

- Avoid non-deterministic animations
- Use timeline sync via `copperd`
- Test redraw consistency across resolutions

## Example Use Cases

- UI compositing for shell and apps
- Visual onboarding flows
- Real-time media overlays

---

`compositord` makes CopperlineOS feel alive — with clarity and control.
