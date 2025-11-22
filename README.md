# ComfyUI TikTok Downloader

A simple and robust ComfyUI node to download TikTok videos directly into your workflow.

## Features
- **Download by URL**: Paste any TikTok video link.
- **FPS Control**: Keep original FPS or force a custom frame rate.
- **Frame Limiter**: Download the whole video or just the first X frames (useful for testing).
- **Resizing**: Custom width/height output with aspect ratio preservation.
- **Audio Support**: Outputs the audio track for use with other nodes.
- **Safe & Clean**: Handles temporary files automatically and uses a robust audio loader (no external codecs required).

## Installation

1. Clone this repository into your ComfyUI custom_nodes folder:
   ```bash
   cd ComfyUI/custom_nodes
   git clone https://github.com/DEIN_USERNAME/ComfyUI-TikTok-Downloader.git
  ```
