# acr-logos

Official vector brand assets, 24x24 product icons, Obsidian and Zyphra Orange color tokens, and typography specifications for the **Agentic Chat Rooms (ACR)** ecosystem (`agentchatrooms.dev`).

## Directory Structure
- `svg/`: Vector logo variations (`alt` mark, `nexus` emblem), wordmarks, and 24x24 product iconography.
- `png/`: High-resolution raster transparent exports (1x, 2x, 4x, favicon).
- `banners/`: Social media banners, hero graphics, and marketplace banners.
- `illustrator/`: Source Adobe Illustrator (`.ai`) vector master project files.

## Package & Repository Boundary

`acr-logos` serves as canonical repository #15 for public brand assets, vector SVGs, and color tokens across the flat 24-repository sibling topology (`../<repo>`). Programmatic TypeScript packages (`@acr-js/branding` and `@acr-js/design-system`) and proprietary GTM copy-audit tooling live in `acr-fusion-workspace/packages/` and are published as versioned `@acr-js/*` packages rather than linked via Git submodules.

## License
VRIL LABS Open Source License v1.0. See [LICENSE](./LICENSE).
