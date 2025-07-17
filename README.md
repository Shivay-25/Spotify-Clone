# 🎵 Spotify Clone

A responsive Spotify-inspired music player built with HTML, CSS, and JavaScript. This web app mimics key features of Spotify, such as browsing albums, viewing song lists, and controlling playback.

## 🚀 Features

- 🔍 Browse albums and view their metadata
- 🎧 Dynamic song list loading via `fetch` API
- ▶️ Play, pause, next, and previous song controls
- ⏱️ Interactive seekbar and playback timer
- 🔊 Volume control and mute toggle
- 📱 Responsive design for desktop and mobile
- 🧑‍🎨 Custom styling with utility classes and modern fonts

## 📁 Project Structure

📦 spotify-clone
├── index.html
├── script.js
├── style.css
├── utility.css
├── /img
│ ├── logo.svg
│ ├── play.svg
│ ├── pause.svg
│ ├── prevsong.svg
│ ├── nextsong.svg
│ ├── volume.svg
│ ├── mute.svg
│ └── other UI assets
└── /songs
└── [album-folder]/
├── cover.jpeg
├── info.json
└── song files (.mp3)


## 🛠️ Setup Instructions

1. **Clone the repository:**
   ```bash
   git clone https://github.com/your-username/spotify-clone.git
   cd spotify-clone
2. Run a local server:
   You can use any static file server. For example, using Python:
   ```bash
   # Python 3
   python -m http.server
4. Access in your browser:
   Open http://127.0.0.1:8000 in your browser.

⚠️ The script.js expects a local backend serving music folders and JSON metadata (/songs/{album}/info.json). Make sure your server serves the appropriate structure and MIME types.

## 🧠 Technologies Used
HTML5

CSS3 (including custom utility classes)

JavaScript (ES6+)

Responsive design with media queries

## 📄 License
This project is for educational purposes and not affiliated with Spotify.
Feel free to fork and customize it for personal or academic use.
