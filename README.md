# Tag Picker

A sleek, dark-themed web tool for visualizing and picking custom Minecraft Bedrock glyphs (specifically `glyph_E1`).

## Features

- **Visual Grid**: Displays all 256 sprites from your `glyph_E1.png` file.
- **Click to Copy**: Click any icon to copy the corresponding Unicode character to your clipboard for use in-game.
- **Code Reference**: Shows the Hex code (e.g., `E102`) in a toast notification when copied.
- **Smart Design**:
  - Dark mode interface.
  - Hover effects that dynamically match the dominant color of each tag.
  - Pixel-perfect rendering for retro/pixel art styles.

## Usage

1. Replace `glyph_E1.png` with your own spritesheet if desired (must be a standard Bedrock glyph grid).
2. Open `index.html` in your browser.
3. Click a tag to copy it!

## Customization

The site automatically detects the 16x16 grid structure of standard Bedrock glyph files.
