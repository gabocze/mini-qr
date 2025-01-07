# Mini QR Code Generator

[![License: GPL v3](https://img.shields.io/badge/License-GPLv3-blue.svg)](https://www.gnu.org/licenses/gpl-3.0)

A customizable QR code generator to create beautiful and unique QR codes.

<div style="display:flex; flex-direction:row; flex-wrap:wrap; justify-content:center; gap:8px;">
    <a href="https://esteetey.dev"><img width="100" src="public/presets/lyqht.svg" /></a>
    <a href="https://www.padlet.com"><img width="100" src="public/presets/padlet.svg" /></a>
    <a href="https://www.uilicious.com">
    <img width="100" src="public/presets/uilicious.svg" />
    </a>
    <a href="https://www.supabase.com"><img width="100" src="public/presets/supabase-green.svg" /></a>
    <a href="https://www.vercel.com"><img width="100" src="public/presets/vercel-dark.svg" /></a>
    <a href="https://viteconf.org/"><img width="100" src="public/presets/viteconf2023.svg" /></a>
</div>

## Features

- ✅ Accessible: minimally WCAG A compliant
- 🎨 Customizable colors and styles
- 🖼️ Export to SVG and PNG
- 📋 Copy to clipboard
- 🌓 Light/dark/system-preference mode toggle
- 🎲 Randomize style button
- 🌐 Available in 29+ languages thanks to [deepl-translate-github-action](https://github.com/lyqht/deepl-translate-github-action)
- 💾 Save & Load QR Code config
- 🖼️ Upload custom image for logo
- 🎭 Presets: Pre-crafted QR code styles
- 🛡️ Error correction level: affects the size of the QR code and logo within. Use lower correction levels for bigger pieces of data to ensure that it can be read.
- 📦 Batch data export: Import a CSV file with multiple data strings and export QR codes for them all at once.

## Demo

Try it out [here](https://mini-qr.vercel.app/) ✨

https://github.com/lyqht/mini-qr/assets/35736525/991b2d7e-f168-4354-9091-1678d2c1bddb

Batch data export is also now supported.

https://github.com/user-attachments/assets/fef17e6a-c226-4136-9501-8d3e951671e0

## Starting with Docker on Windows 🐋

1. Clone with Git.
2. `cd` to the directory of the cloned repo.
3. Run `mini-qr.cmd` (script supplied by the cloned repo).

### Schedule the Script
Use Task Scheduler in Windows to run the script at system startup.
1. Open Task Scheduler from the Start menu.
2. Create a new task and set the trigger to “At startup”.
3. In the “Actions” tab, create a new action to start a program.
4. Set the program/script to _PATH and SCRIPT NAME_ of `mini-qr.cmd` (script supplied by the cloned repo).

## Contributing

See [CONTRIBUTING.md](CONTRIBUTING.md) for more details.
