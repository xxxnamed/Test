<div align="center">
    <img src="./app/src/main/ic_launcher-playstore.png" width="128" height="128" style="display: block; margin: 0 auto"/>
    <h1>ViChord</h1>
    <p>An Android application for seamless music streaming</p>

    <p>
      <img alt="GitHub tag (latest SemVer)" src="https://img.shields.io/github/v/tag/25huizengek1/ViChord?style=flat-square&color=28B463&label=Latest%20Release">
      <img alt="Build Status" src="https://github.com/25huizengek1/ViChord/actions/workflows/android-build.yml/badge.svg"> 
      <img alt="License" src="https://img.shields.io/github/license/25huizengek1/ViChord?style=flat-square&color=764BA2">
      <img alt="F-Droid" src="https://img.shields.io/badge/Get%20it%20on-F--Droid-4696c7?style=flat-square">
    </p>
</div>

---

<p align="center">
  <img src="./fastlane/metadata/android/en-US/images/phoneScreenshots/1.png" width="30%" />
  <img src="./fastlane/metadata/android/en-US/images/phoneScreenshots/2.png" width="30%" />
  <img src="./fastlane/metadata/android/en-US/images/phoneScreenshots/3.png" width="30%" />

  <img src="./fastlane/metadata/android/en-US/images/phoneScreenshots/4.png" width="30%" />
  <img src="./fastlane/metadata/android/en-US/images/phoneScreenshots/5.png" width="30%" />
  <img src="./fastlane/metadata/android/en-US/images/phoneScreenshots/6.png" width="30%" />
</p>

## 🚀 Key Features

### Core Experience
* 🎶 **Multi-Source Playback:** Play (almost) any audio from multiple sources, primarily **YouTube**.
* 📥 **Offline & Background:** Keep listening in the background or even **offline** with cached songs.
* 🔎 **Comprehensive Search:** Search through songs, albums, artists, videos, and playlists.

### Quality & Customization
* 🎤 **Lyrics Support:** View, edit, and even **sync lyrics** for your tracks.
* 🎚️ **Audio Optimization:** Enjoy an optimized listening experience with built-in **audio normalization**.

### Seamless Integration
* ☁️ **Cloud Sync:** Seamlessly sync your playlists across devices.
* 🔗 **Deep Links:** Open any YouTube or YouTube Music link (videos, playlists, channels, etc.) right in ViChord.
* 🚗 **Android Auto Ready:** Take your music on the road.
* 📤 **YouTube Import:** Import your existing playlists straight from YouTube.

## ⬇️ Installation

You can get ViChord from the following sources:

| Source | Link |
| :--- | :--- |
| **Latest Release** | [Download from GitHub Releases](https://github.com/25huizengek1/ViChord/releases/latest) |
| **F-Droid Repo** | [Add the ViChord F-Droid Repository](https://repo.vichord.app/) |
| **Obtainium** | [Add to Obtainium](https://apps.obtainium.imranr.dev/redirect?r=obtainium://add/https://github.com/25huizengek1/ViChord/) |

## Acknowledgments

- [**YouTube-Internal-Clients**](https://github.com/zerodytrash/YouTube-Internal-Clients): A Python script that discovers hidden YouTube API clients. Research project only.
- [**ionicons**](https://github.com/ionic-team/ionicons): Premium hand-crafted icons for Ionic apps and web apps.
- [**Flaticon: Ilham Fitrotul Hayat**](https://www.flaticon.com/authors/ilham-fitrotul-hayat): The app's logo uses a music note icon.

---

## 🛠️ Developer / Technical Guide

### Rust Integration Guide

#### Installing NDK
Install the Android Native Development Kit (NDK) via [Android Studio SDK Manager](https://developer.android.com/ndk/downloads) or using SDK tools.

#### Adding Rustup Targets
