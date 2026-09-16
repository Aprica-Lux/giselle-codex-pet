# Giselle

Giselle is a Codex v2 animated pet based on a gentle chibi guardian angel: chestnut-brown hair, floral halo, white feathered wings, a lotus motif, and warm peach-gold accents.

## Features

- 9 standard Codex animation states: idle, directional movement, waving, jumping, failed, waiting, running, and review
- 16 clockwise look directions with cardinal and diagonal gaze poses
- 8×11 v2 sprite atlas using 192×208 cells
- 1536×2288 RGBA WebP spritesheet
- Compact, transparent-background pet artwork designed for Codex pet rendering

## Technology

- Codex custom pet v2 manifest (`pet.json`)
- RGBA WebP sprite atlas (`spritesheet.webp`)
- No runtime library or external dependency

## Installation

Copy `pet.json` and `spritesheet.webp` into the Codex custom-pet directory:

```text
%USERPROFILE%\.codex\pets\angel\
```

Restart Codex or reload the pet selector if Giselle does not appear immediately. The internal package id remains `angel` to preserve the existing installation and animation behavior; the user-facing display name is `Giselle`.

## Configuration

No environment variables or API keys are required. This repository contains only the pet package assets and manifest.

## Preview

Add a screenshot or GIF here, for example `docs/preview.gif`, when publishing a preview capture.

## License

No license has been specified for this asset yet.
