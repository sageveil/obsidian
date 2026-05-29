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

The sageveil Obsidian port provides a calm terminal palette that matches the rest of the ecosystem.

## Get the theme

### Prebuilt releases

Download the theme from the dedicated repository: <https://github.com/sageveil/obsidian>.

### Build from the monorepo

1. Install dependencies once: `pnpm install`
2. Render the theme: `pnpm nx run obsidian:generate`
3. The files land in `dist/ports/obsidian/`

## Generated files

- `sageveil` – Obsidian theme file

## Apply sageveil

### From the generated artifact

1. Build the file: `pnpm nx run obsidian:generate`
2. Copy `dist/ports/obsidian/sageveil.css` to your vault snippets directory:
   - macOS: `<vault>/.obsidian/snippets/sageveil.css`
   - Linux: `<vault>/.obsidian/snippets/sageveil.css`
   - Windows: `<vault>\\.obsidian\\snippets\\sageveil.css`
3. In Obsidian, open `Settings` -> `Appearance` -> `CSS snippets`.
4. Reload snippets (if needed) and enable `sageveil`.

### From prebuilt releases

If you install from [sageveil/obsidian](https://github.com/sageveil/obsidian), follow that repository's release instructions.

## Development

[sageveil/sageveil](https://github.com/sageveil/sageveil) is the main project monorepo. All development happens there.

[sageveil/obsidian](https://github.com/sageveil/obsidian) is used only for easy distribution of the ready-to-use Obsidian colorscheme.
