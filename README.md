# FormatFactory - Fast Batch Media Converter for Desktop

<p align="center">
  <img width="200" height="200" src="https://github.com/keshavbhatt/formatfactory-packaging/blob/main/icons/icon-256.png?raw=true">
</p>

FormatFactory is a fast desktop media converter that wraps FFmpeg with a clean
batch workflow for video, audio, and image files.

## Features

- Batch conversion queue with live progress, ETA, and estimated output size
- Ready-to-use presets for common devices, sites, and workflows
- Custom conversion profile builder (codecs, bitrate, resolution, and more)
- Hardware-accelerated (GPU) encoding for faster conversions
- Automatic GPU-assisted decoding where supported, with safe software fallback
- Metadata, tag, and cover-art editing
- Media inspection with detailed format information
- Drag-and-drop file adding
- Dark and light themes (follows the system theme)

## Screenshots

![FormatFactory home screen](https://github.com/keshavbhatt/formatfactory-packaging/blob/main/screenshots/01-home.png?raw=true)
![Preset selection](https://github.com/keshavbhatt/formatfactory-packaging/blob/main/screenshots/02-presets.png?raw=true)
![Batch conversion queue](https://github.com/keshavbhatt/formatfactory-packaging/blob/main/screenshots/03-queue.png?raw=true)
![Metadata editor](https://github.com/keshavbhatt/formatfactory-packaging/blob/main/screenshots/04-metadata-editor.png?raw=true)

## Install via Snap

```bash
snap install formatfactory
```

[![Get it from the Snap Store](https://snapcraft.io/static/images/badges/en/snap-store-black.svg)](https://snapcraft.io/formatfactory)

## Install via Flathub

```bash
flatpak install flathub com.ktechpit.formatfactory
```

[![Download on Flathub](https://flathub.org/api/badge?locale=en)](https://flathub.org/en/apps/com.ktechpit.formatfactory)

## Requirements

FormatFactory uses the system `ffmpeg` and `ffprobe` binaries. The Snap and
Flatpak builds bundle them; for a source build install them from your distro and
ensure they are on `PATH` (or set their paths in **Settings → Tools**).
