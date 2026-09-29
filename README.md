# 🚀 QuickSave

<p align="center">
  <b>Share. Choose. Download.</b>
</p>

<p align="center">
  <a href="README.md">🇬🇧 English</a> ·
  <a href="README.it.md">🇮🇹 Italiano</a> ·
  <a href="README.ar.md">🇸🇦 العربية</a>
</p>

QuickSave is a modern Android media downloader designed to make downloading supported online videos and audio fast, simple, and convenient.

Its main idea is simple: share a link to QuickSave, choose the options you need, and download.

## ✨ Features

### ⚡ Quick Share

- Share a supported link from another app directly to QuickSave.
- Open a lightweight Quick Share options sheet immediately.
- Prepare media information in the background while the user selects options.
- Disable the options sheet and use direct background downloading instead.

### 🎬 Video & Audio

- Video + audio downloads.
- Audio-only downloads.
- Quality selection:
  - Best available
  - 1080p
  - 720p
  - 480p
- Automatic media stream handling and processing.

### 📋 YouTube Playlists

- Detect supported YouTube playlist links.
- Preview playlist information and videos.
- Select individual videos.
- Select all / deselect all.
- Download selected videos as a batch.
- Show which videos have already been downloaded.
- Continue downloading remaining videos later.
- Organize playlist downloads into a dedicated folder.

### 📚 Playlist Library

QuickSave can keep a local library of previously opened or downloaded playlists.

The library can show:

- Playlist title
- Thumbnail
- Author
- Video count
- Downloaded / remaining progress

A saved playlist can be reopened later to continue with the remaining videos.

### ⏬ Download Queue

- Queue multiple downloads.
- Configure the maximum number of simultaneous downloads.
- Run several downloads in parallel when enabled.
- Control individual downloads.
- Control the whole queue.

### ⏸️ Pause & Resume

- Pause active downloads.
- Resume paused downloads.
- Preserve temporary download data so supported downloads can continue instead of unnecessarily restarting.
- Keep paused downloads visible in the Home screen.

### ⏯️ Pause All / Resume All

Pause or resume all active and queued downloads from the Home screen with a single action.

### ✂️ Trim / Clip

Download only a selected part of a supported media item.

Choose:

- Start time
- End time

Example:

`00:15 → 01:30`

### 🎵 Chapter Splitter

For supported media containing chapters, QuickSave can split the content into separate files.

Useful for long videos, podcasts, music collections, and other chapter-based media.

### 📁 Custom Download Folder

- Choose a custom destination folder.
- Use Android's Storage Access Framework.
- Support user-selected storage locations where Android permits access.
- Restore the default download location at any time.

### 📚 Download History

- View previous downloads.
- Filter by status.
- Open downloaded files.
- Share downloaded files.
- Delete files safely.
- Retry failed downloads.
- Resume paused downloads.

### 🔔 Background Downloads

QuickSave uses an Android foreground download service so downloads can continue while the user leaves the app and uses the device normally.

### 📊 Live Progress

Active downloads can show:

- Percentage
- Downloaded size
- Total size when available
- Download speed
- Current status
- Playlist progress where applicable

Each download uses its own notification state so multiple downloads can be tracked independently.

### 🔄 Retry & Recovery

- Automatic retry can be enabled from settings.
- Failed downloads can be retried manually.
- Cancelled and paused states are handled separately.
- Temporary job data is cleaned up when it is no longer needed.

### 🔐 Optional Login Sessions

Some content may require an authenticated session.

QuickSave provides an optional in-app browser flow for supported platforms and can also import supported `cookies.txt` files.

Users can:

- Sign in through the in-app browser.
- Save a session locally.
- Inspect supported session states.
- Disconnect a platform.
- Clear session data.
- Import cookie files.

### 🌍 Multilingual Interface

QuickSave currently supports:

- 🇬🇧 English
- 🇮🇹 Italiano
- 🇸🇦 العربية

Arabic includes native right-to-left (RTL) support.

The application language can be changed from the settings.

### 💾 Backup & Restore

QuickSave includes JSON backup and restore for application data such as:

- Download history
- Saved playlists
- Application preferences
- Supported session/cookie data

Backups are created and restored through Android's native file picker.

## 🧠 Performance & Smart Resolution

QuickSave includes several optimizations designed to reduce unnecessary waiting.

### ⚡ Background Prefetch

When Quick Share is opened, QuickSave can prepare media information in the background while the user configures the download.

Depending on the source, this may include:

- Title
- Thumbnail
- Duration
- Media information

### 🚀 Prefetch Cache

Resolved media information can be cached temporarily so the application does not need to repeat the same resolution step unnecessarily.

### 🔗 In-Flight Resolution

If the user starts downloading before background resolution has finished, QuickSave can reuse the active resolution task instead of starting the same work again.

### 🧹 Automatic Cache Cleanup

Temporary resolution cache files are cleaned automatically when they become old or are no longer needed.

## 🎯 Designed for a Simple Workflow

### Manual workflow

**Open QuickSave → Enter a URL → Choose options → Download**

### Fast Share workflow

**Share a link → Quick Share → Choose options → Download**

### Automatic workflow

**Share a link → QuickSave starts the download in the background**

## 🛠️ Technology

QuickSave is a native Android application built with modern Android technologies, including:

- Kotlin
- Jetpack Compose
- Material 3
- MVVM
- Clean Architecture
- Unidirectional Data Flow
- Room
- DataStore
- Foreground Services
- Storage Access Framework
- MediaStore
- WebView
- yt-dlp
- FFmpeg

## 📦 Releases

Official application builds are published through **GitHub Releases**.

A release may include:

- APK
- Release notes
- Changelog
- Bug fixes
- New features

See the **Releases** section of this repository for available builds.

## 🔒 Privacy

QuickSave has a dedicated Privacy Policy covering application data, download-related information, optional login sessions, advertising-related processing, and third-party services.

**Privacy Policy:**  
https://alraeeini.github.io/QuickSave/ 

## ⚠️ Disclaimer

QuickSave is a utility for downloading content that the user is legally allowed or authorized to access and download.

Users are responsible for complying with:

- Applicable laws
- Copyright and intellectual-property rights
- Platform terms of service
- Any permissions required for downloaded content

QuickSave does not grant ownership or redistribution rights for downloaded content.

## 🧪 Development Status

QuickSave is actively developed.

Features, compatibility, supported sources, and behavior may change between releases.

## 👨‍💻 Developer

**Abdulrahman Alraeeini**

GitHub: [@Alraeeini](https://github.com/Alraeeini)

Email: **raeeiniab@gmail.com**

## 📄 Quick Links

- 🌐 [Privacy Policy](https://alraeeini.github.io/QuickSave/)
- 📦 [Releases](https://github.com/Alraeeini/QuickSave/releases)
- 👨‍💻 [GitHub Profile](https://github.com/Alraeeini)

---

<p align="center">
  <b>QuickSave — Share. Choose. Download.</b>
</p>
