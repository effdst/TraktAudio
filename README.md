# TRAKT⁄AUDIO

> Browser-native audio converter & batch processor. Single HTML file. Zero dependencies.  
> Drop files → choose format → render.

[🌐 Live Demo](https://effdst.github.io/TraktAudio/) | [⬇ Portable Build (Releases)](https://github.com/effdst/TraktAudio/releases)

---

## 📡 About

TRAKT⁄AUDIO is a desktop-grade audio converter that runs entirely in the browser on the Web Audio API. 
No installation, no accounts, no frameworks. Supports batch conversion, advanced processing, spectral noise reduction, and preset management — in one self-contained file. Works offline from a USB drive.

## ✂️ Features

- **Formats**: WAV · MP3 · FLAC · AIFF · M4A · AAC · ALAC · OGG · OPUS
- **Sample Rates**: Original · 8 kHz · 16 kHz · 22.05 kHz · 32 kHz · 44.1 kHz · 48 kHz · 88.2 kHz · 96 kHz · 192 kHz
- **Channels**: Original · Mono · Stereo
- **Bit Depth**: 16 / 24 / 32-bit (format-dependent)
- **Processing Chain**: Gain · Normalize · Fade In / Fade Out (Cosine / Linear / Square) · Reverse · Invert · DC-filter · Dithering
- **Noise Reduction**: Spectral subtraction · Auto-profile by silent frames · Manual profile training
- **Batch Conversion**: Process multiple files at once with progress tracking
- **Presets**: Save, load, and delete custom conversion presets
- **System**: Bilingual UI (EN / RU) · Drag & Drop · Offline processing

## ⚙️ System Requirements

- **Engine**: Web Audio API
- **Dependencies**: 0 (Zero)
- **Installation**: None (Single File)
- **Offline Mode**: Yes (runs from local disk or USB drive)
- **Browsers**: Chrome / Edge recommended (widest codec support) · Safari · Firefox

## 🖥 Portable Version

The portable build runs offline without a browser tab — launch it from a folder or USB drive. 
Downloads are published in [Releases](https://github.com/effdst/TraktAudio/releases).

## 📂 Repository Structure

```text
.
├── index.html          # Redirect to the converter
├── TraktAudio.html     # The converter (single file, EN/RU)
└── README.md