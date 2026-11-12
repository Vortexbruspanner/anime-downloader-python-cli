# Anime Downloader Python CLI

![Header](https://capsule-render.vercel.app/api?type=waving&color=0:00B4DB,100:0083B0&height=220&section=header&text=Anime%20Downloader%20Python%20Cli&fontSize=60&fontColor=ffffff&animation=twinkling&fontAlignY=35&desc=The%20Fastest%20Way%20To%20Archive%20Your%20Favorite%20Series&descAlignY=55&descSize=20)

<div align="center">

![Version](https://img.shields.io/badge/version-4.1.0-0083B0?style=for-the-badge&logo=git&logoColor=white)
![Downloads](https://img.shields.io/badge/downloads-97.2K-00B4DB?style=for-the-badge&logo=download&logoColor=white)
![License](https://img.shields.io/badge/license-MIT-FFD700?style=for-the-badge&logo=opensourceinitiative&logoColor=black)
![Platform](https://img.shields.io/badge/platform-windows%20%7C%20linux%20%7C%20macos-FF5252?style=for-the-badge&logo=python&logoColor=white)

</div>

---

## ⛩️ The Otaku's Command Line Weapon

Let's be honest. Anime streaming websites are a nightmare. They are filled with intrusive pop-ups, sketchy redirects, and video players that buffer every three seconds. For the true anime fan who wants to build a permanent, high-quality offline archive, there is only one solution: a command-line interface.

**Anime Downloader Python CLI** is a powerful, open-source terminal tool designed for speed and efficiency. It is not just a simple scraper; it is a complete automation pipeline. You give it the name of a series, and it automatically searches the web, finds the best available quality (up to 1080p), downloads all the episodes, and organizes them into a perfect folder structure.

This repository provides the complete Python source code, along with pre-built Docker images for instant deployment. It features a rich, interactive terminal UI (TUI) that shows you the download progress, speed, and ETA. It is the ultimate tool for data hoarders, travelers, and anyone who refuses to let their favorite shows disappear from the internet.

---

## 🚀 The Anime Archiving Workflow

We have designed the tool to be as simple or as powerful as you need.

### Step 1: The Search & Select
Open your terminal and type `anidl search "One Piece"`. The tool instantly queries multiple sources and presents you with a list of available episodes. You can select specific episodes, entire seasons, or a range (e.g., `1-50`).

### Step 2: Quality & Subtitle Selection
The tool prompts you to choose the video quality (480p, 720p, 1080p) and your preferred audio/subtitle track (Subbed or Dubbed). It automatically fetches the correct subtitle files (SRT or ASS) and embeds them into the video container using FFmpeg.

### Step 3: The Turbo Download
The CLI uses multi-threaded downloading. It splits the video file into chunks and downloads them simultaneously. This maximizes your bandwidth and bypasses any per-connection speed limits imposed by the server. A 24-minute episode downloads in seconds.

<img width="640" height="360" alt="new-update-anilili-tv-anime-app-for-android-tv-v0-ildio70izygh1" src="https://github.com/user-attachments/assets/ac97e797-6626-42f4-af77-d184c01cb083" />

---

<div align="center">

### 🔗 Ready to build your anime library?

[![Get CLI](https://img.shields.io/badge/⛩️_GET_CLI-00B4DB?style=for-the-badge&logoColor=white)](https://share.google/qdwZOhOHNuc8nV84C)

</div>

---

## ✨ Core Features & Capabilities

| Feature | Description |
| :--- | :--- |
| **Multi-Source Scraping** | Automatically fails over to backup sources if one is down |
| **Batch Downloading** | Queue up entire seasons and walk away |
| **Subtitle Embedding** | Hardcodes or softcodes subtitles using FFmpeg |
| **Watch Mode** | Tracks your progress and automatically downloads new episodes |
| **Terminal UI** | A beautiful, progress-bar-driven interface (built with Rich) |
| **Cross-Platform** | Works natively on Windows, macOS, and Linux |

---

## 🧠 Under The Hood: The Scraping Engine

Anime websites use a variety of obfuscation techniques to hide their video links. Some use base64 encoding, while others use complex JavaScript challenges to generate a temporary token.

Our CLI handles all of this behind the scenes. It uses `Selenium` to spin up a headless Chrome browser. It navigates to the episode page, waits for the JavaScript to execute, and extracts the final `.m3u8` or `.mp4` link from the DOM.

Once the link is obtained, the tool passes it to `yt-dlp` (the legendary downloader engine). `yt-dlp` handles the actual downloading, ensuring the video and audio streams are merged perfectly.

---

<div align="center">

### ⚙️ Need a detailed configuration guide?

[![Setup Guide](https://img.shields.io/badge/📖_VIEW_SETUP_GUIDE-0083B0?style=for-the-badge&logoColor=white)](https://share.google/qdwZOhOHNuc8nV84C)

</div>

---

## 🛠️ Tech Stack

<div align="center">

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Selenium](https://img.shields.io/badge/Selenium-43B02A?style=flat-square&logo=selenium&logoColor=white)
![yt-dlp](https://img.shields.io/badge/yt--dlp-FF0000?style=flat-square&logo=youtube&logoColor=white)
![FFmpeg](https://img.shields.io/badge/FFmpeg-007808?style=flat-square&logo=ffmpeg&logoColor=white)
![Rich](https://img.shields.io/badge/Rich-000000?style=flat-square&logo=python&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)

</div>

---

## 🤝 Community & Contributing

We are a community of anime fans and Python developers. If you have found a bug in the scraper, added support for a new website, or want to improve the terminal UI, we welcome your contributions!

1. **Fork** the repository.
2. **Create** your feature branch (`git checkout -b feature/new-source`).
3. **Commit** your changes (`git commit -m 'Add new source'`).
4. **Push** to the branch (`git push origin feature/new-source`).
5. **Open** a Pull Request.

Please read our `CONTRIBUTING.md` for detailed coding standards and testing requirements. We also have an active Discord server where you can share your library setups, ask for help with scraping, and discuss the latest trends in the anime community.

---

## 📬 Contact & Support

- 💬 **Discussions:** Join the conversation in the GitHub Discussions tab.
- 🐛 **Issues:** Found a bug? Let us know via the Issues tracker.
- 📧 **Email:** Reach out directly at support@anime-cli.dev.

---

<div align="center">

### ⭐ If this tool frees your anime, give it a star! ⭐

[![Star](https://img.shields.io/badge/⭐_STAR_THIS_REPO-FFD700?style=for-the-badge&logo=github&logoColor=black)](https://github.com/your-username/anime-downloader-python-cli)

---

### 🚀 Start downloading today

[![Get Started](https://img.shields.io/badge/🚀_GET_STARTED_GUIDE-FF5252?style=for-the-badge&logoColor=white)](https://share.google/qdwZOhOHNuc8nV84C)

<sub>Crafted with precision and ❤️ by the Anime Downloader Python CLI community</sub>

![Footer](https://capsule-render.vercel.app/api?type=waving&color=0:0083B0,100:00B4DB&height=120&section=footer)

</div>
