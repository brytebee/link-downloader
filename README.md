# Link Downloader & Transcriber - UI

A premium, intent-driven frontend for downloading media and generating AI transcripts.

## ✨ Features
- **Intent-Driven UI**: Switch between "Download" and "Transcribe" modes with a sleek sliding pill switcher.
- **Glassmorphic Design**: Modern, translucent interface with background blurs and smooth transitions.
- **Real-Time Progress**: Polling-based progress bar for both downloads and AI transcription.
- **Smart Analysis**: Automatic video format analysis (only triggered in Download mode).
- **One-Click Folder Access**: Open your download destination directly from the UI.

## 🚀 Getting Started
1. Ensure the **Private API** server is running (see `private-api` README).
2. Open `index.html` in your browser.
3. Choose your mode (Download or Transcribe) at the top.
4. Paste your link and enjoy the seamless extraction!

## 🛠️ Configuration
The frontend communicates with the backend via the `API_BASE` constant in the script section (default: `http://localhost:5000/api`).
