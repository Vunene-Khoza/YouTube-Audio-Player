# YouTube-Audio-Player
# PyTune Player 🎵
A desktop music player application built with Python that combines local music playback with YouTube audio downloading capabilities. Create playlists by adding MP3 files from your computer or by directly downloading audio from YouTube videos, which are automatically converted to MP3 format.

# Features ✨
🎵 Local Music Playback: Play MP3 files from your computer
📺 YouTube Integration: Download and convert YouTube videos to MP3
📋 Playlist Management: Create and manage your music playlists
🎛️ Standard Controls: Play, pause, stop, skip, volume adjustment
⏯️ Progress Control: Seek through tracks with interactive slider
🖥️ Clean Interface: User-friendly GUI built with Tkinter
🔄 Auto-Conversion: Automatic audio conversion using FFmpeg

# Tech Stack 🛠️
Python - Core programming language
Tkinter - GUI framework
Pygame - Audio playback engine
yt-dlp - YouTube downloading and audio extraction
FFmpeg - Audio/video processing and conversion

# Prerequisites
Python 3.7 or higher
Windows, macOS, or Linux

# Installations 
# Step 1: Install Python Dependencies
```pip install pygame```
```pip install yt-dlp```

# Step 2: Install FFmpeg
Windows:
Download FFmpeg from BtbN FFmpeg Builds
Download: ffmpeg-master-latest-win64-gpl.zip
Extract to C:\ffmpeg

macOS:
```brew install ffmpeg```

Linux:
```sudo apt update```
```sudo apt install ffmpeg```

# Step 3: Copy FFmpeg Files to Project Folder
After installing FFmpeg, copy these 3 files from C:\ffmpeg\bin\ (Windows) or your FFmpeg installation directory:
ffmpeg.exe (or ffmpeg on macOS/Linux)
ffplay.exe (or ffplay on macOS/Linux)
ffprobe.exe (or ffprobe on macOS/Linux)
Paste them directly into your project folder (where your Python script is located).

Why Copy to Project Folder?
✅ No PATH issues - Python finds FFmpeg in the same folder
✅ Portable - You can move your project anywhere
✅ No system configuration needed
✅ Works immediately

# Project Structure 📁
YouTube_Audio_Player/
├── YouTube_Audio_Player.ipynb
├── ffmpeg.exe
├── ffplay.exe
├── ffprobe.exe
├── downloads/
├── Pictures/
│   ├── addmusicpic.PNG
│   ├── backpic.PNG
│   ├── forwardpic.PNG
│   ├── highvolumepic.PNG
│   ├── lowvolumepic.PNG
│   ├── novolumepic.PNG
│   ├── pausepic.PNG
│   ├── playpic.PNG
│   └── stoppic.PNG    
└── README.md

# Usage 🚀
Run the application:
```python pytune_player.ipynb```

Download from YouTube:
Paste a YouTube URL in the input field
Click "Download from YouTube"
Audio will be downloaded, converted to MP3, and added to playlist

Add Local Music:
Click the "Add Music" button
Select MP3 files from your computer
Files will be added to your playlist

Control Playback:
Select a song from the playlist to play
Use play, pause, stop, and skip buttons
Adjust volume with volume controls
Seek through tracks using the progress slider