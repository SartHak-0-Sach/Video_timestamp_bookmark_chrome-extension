# 📌 Video Timestamp Bookmark Chrome Extension

## 📋 Table of Contents
1. [🤖 Introduction](#-introduction)
2. [⚙️ Tech Stack](#%EF%B8%8F-tech-stack)
3. [📂 File Structure](#-file-structure)
4. [🔋 Features](#-features)
5. [🤸 Quick Start](#-quick-start)
   - [Installation](#installation)
   - [Usage](#usage)
7. [🔗 Author](#-author)
8. [🚀 More](#-more)

## 🤖 Introduction
The **Video Timestamp Bookmark Chrome Extension** allows users to add and save timestamps from YouTube videos for future reference. This solves the challenge of remembering or manually noting down timestamps, making it highly useful for students, professionals, and anyone who frequently references specific moments in videos.

## ⚙️ Tech Stack
| Technology        | Purpose                                      |
|-------------------|----------------------------------------------|
| **HTML, CSS, JS** | Core development of the extension interface  |
| **Chrome APIs**   | Integration with Chrome for bookmarks, storage, and popup functionality |

## 📂 File Structure
The project follows this file structure for clarity and maintainability:

```
assets
├── bookmark.png      # Icon for saving timestamps
├── delete.png        # Icon for deleting bookmarks
├── ext-icon.png      # Extension logo
├── play.png          # Icon for playing bookmarked timestamps
├── save.png          # Icon for saving
background.js         # Manages background tasks for the extension
contentScript.js      # Injected script for interacting with YouTube
manifest.json         # Chrome extension configuration file
popup.css             # Styling for the popup UI
popup.html            # Extension's popup interface
popup.js              # Handles functionality of popup
utils.js              # Helper functions for the extension
LICENSE
README.md
```

## 🔋 Features
- **📌 Bookmark Timestamps**: Save specific timestamps from YouTube videos for later.
- **📂 Organized Storage**: Keep bookmarks structured and easily accessible.
- **🎬 Play From Bookmark**: Resume watching from any saved timestamp with one click.
- **🗑️ Delete Bookmarks**: Remove unwanted bookmarks quickly.
- **🛠️ User-Friendly Popup**: Intuitive and minimalistic interface.

## 🤸 Quick Start

### Installation
1. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/video-timestamp-bookmark.git
   cd video-timestamp-bookmark
   ```
2. Open Chrome and navigate to `chrome://extensions/`.
3. Enable **Developer Mode** in the top right corner.
4. Click **Load Unpacked** and select the project folder.

### Usage
1. Navigate to any YouTube video.
2. Click on the extension icon in the Chrome toolbar.
3. Use the popup interface to:
   - Save the current timestamp.
   - View, play, or delete saved bookmarks.

## 🔗 Author

<b><strong>Sarthak Sachdev</strong></b>
- Website - [Sarthak Sachdev](https://itsmesarthak.netlify.app/)
- LinkedIn - [Sarthak Sachdev](https://www.linkedin.com/in/sarthak2004/)
- Twitter - [@sarthak_sach69](https://www.twitter.com/sarthak_sach69)

## 🚀 More
Contributions are welcome! Feel free to submit a pull request or suggest features for the next version.
