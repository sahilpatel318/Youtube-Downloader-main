# YouTube Downloader

A Python CLI tool to download **your own** YouTube content or content you have permission to download. Supports video/audio, playlists, resolution selection, and FFmpeg conversion.

> Use responsibly and comply with YouTube’s Terms of Service and copyright law.

## Features
- Download single videos or entire playlists
- Choose video resolution or extract audio (MP3/MP4)
- Progress bar + detailed errors
- Safe filenames and output directories
- Optional async batch mode

## Tech
Python • pytube/yt-dlp • FFmpeg

## Quick Start
# 1) Install dependencies
pip install -r requirements.txt
# 2) Ensure FFmpeg is on PATH
# 3) Run
python downloader.py https://youtube.com/watch?v=...

## Usage
python downloader.py <URL> --audio --bitrate 192k
python downloader.py <PLAYLIST_URL> --resolution 720p --out ./downloads

