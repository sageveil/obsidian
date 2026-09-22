<p align="center">
    <img src="https://raw.githubusercontent.com/sageveil/sageveil/refs/heads/main/assets/sageveil-logo.png" width="80" />
    <h2 align="center">@sageveil/obsidian</h2>
</p>

<p align="center">A minimalist low-contrast, green-tinted colorscheme 🌱</p>

<p align="center">
    <img src="https://raw.githubusercontent.com/sageveil/sageveil/refs/heads/main/packages/ports/obsidian/assets/screenshot.png" alt="Sageveil theme in Obsidian" />
</p>

# @sageveil/obsidian

## Overview

The sageveil Obsidian port provides a calm, low-contrast theme that matches the rest of the ecosystem.

## Get the theme

### Obsidian community themes

1. Open `Settings` -> `Appearance` in Obsidian.
2. Next to `Themes`, select `Manage`.
3. Search for `Sageveil`, then select `Install and use`.

Updates are available through Obsidian's community theme manager.

### Prebuilt releases

Download `manifest.json` and `theme.css` from [sageveil/obsidian releases](https://github.com/sageveil/obsidian/releases).

### Build from the monorepo

1. Install dependencies once: `pnpm install`
2. Render the theme: `pnpm nx run obsidian:generate`
3. The files land in `dist/ports/obsidian/`

## Generated files

- `manifest.json` – Obsidian theme metadata
- `theme.css` – Obsidian theme

## Apply sageveil manually

### From the generated artifact

1. Build the theme: `pnpm nx run obsidian:generate`
2. Create `<vault>/.obsidian/themes/Sageveil/`.
3. Copy `dist/ports/obsidian/manifest.json` and `dist/ports/obsidian/theme.css` into that directory.
4. Restart Obsidian, then select `Sageveil` under `Settings` -> `Appearance` -> `Themes`.

### From prebuilt releases

Download `manifest.json` and `theme.css` from [sageveil/obsidian releases](https://github.com/sageveil/obsidian/releases) and install them as described above.

## Development

[sageveil/sageveil](https://github.com/sageveil/sageveil) is the main project monorepo. All development happens there.

[sageveil/obsidian](https://github.com/sageveil/obsidian) is used only for easy distribution of the ready-to-use Obsidian colorscheme.
