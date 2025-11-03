# 🖌️ blitterd — 2D Graphics Engine

`blitterd` is CopperlineOS’s 2D graphics daemon, responsible for pixel-level operations and fast, deterministic rendering.

## Purpose

- Handles image manipulation and drawing
- Supports UI elements, sprites, and overlays
- Optimized for speed and reproducibility

## Features

- Pixel blitting and region copying
- Alpha blending and masking
- Timeline-aware rendering via `copperd`

## Developer Notes

- Keep operations stateless and reproducible
- Use modular drawing routines
- Integrate with `compositord` for layered visuals

## Example Use Cases

- UI button rendering
- Badge overlays and sticker sheets
- Shell visual effects

---

`blitterd` is the brush. CopperlineOS is the canvas.
