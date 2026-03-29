# Link Downloader & Transcriber (UI)

A clean, elegant, dark-mode user interface acting as the frontend for the Link Downloader API. Easily download videos and generate transcripts from various social media platforms directly from your localhost environment.

## Features
- **Modern UI**: Lightweight, responsive dark-themed interface built with standard web technologies.
- **Custom Save Locations**: Seamlessly pick where your media files download using the "Browse..." functionality, which connects to your host PC's native directory picker.
- **Direct Folder Access**: Instantly jump to your downloaded media with the dynamically rendered "Open Output Folder" button.
- **Live Transcription**: Generate transcripts of media and view them instantly in the built-in reader area.

## Usage
Ensure that the [Backend API](https://github.com/brytebee/link-downloader-private) is active and running on `localhost:5000`.

To use the interface, simply open `index.html` in your web browser, or serve it locally:
```bash
python -m http.server 8000
```
Navigate to `http://localhost:8000` to start downloading!

## Configuration
By default, the UI connects to `http://localhost:5000/api`. If your backend API runs on a different port or server, edit the `API_BASE` constant in `index.html`. 
