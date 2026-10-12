# 🎮 GameNexum

> **The Ultimate All-in-One Collection & Backlog Tracker for Gamers and Collectors.**

GameNexum is a powerful, privacy-first Flutter application designed to organize, track, and showcase your entire gaming ecosystem. From physical and digital game libraries to hardware collections, homebrews, and gaming literature—GameNexum covers it all with a sleek dark-themed UI, progress tracking, and Dark Souls-inspired leveling.

---

## ✨ Key Features

### 🎮 **Game Collection & Backlog Manager**
* **Comprehensive Stats:** Track platforms, regions, formats (physical vs. digital), CIB status, DLCs, and playtime.
* **Progress Tracking:** Categorize games by status (*Open, Playing, Finished, 100% Completed, 100% Completed + DLCs*).
* **Trophies & Gamerscore:** Full support for PlayStation Trophy percentages (including Platinum) and Xbox Gamerscore tracking.
* **Multi-Platform Linking:** Link trophy and progress stats across re-releases or multi-platform versions of the same title.
* **Game Wall & Highlights:** Showcase your 100% completed games and explore your collection in a visual grid view.

### 🕹️ **Hardware, Homebrew & Book Tracking**
* **Hardware Library:** Track consoles, handhelds, and retro gear with condition and custom notes.
* **Homebrews, Ports & Mods:** Keep a structured list of custom firmware titles, fan hacks, and modded ports.
* **Gaming Literature:** Track gaming books, artbooks, and guides with full status support (*Open, Reading, Paused, Dropped, Finished*) and a dedicated **Book Wall**.

### 🔥 **Gamification & Dark Souls System**
* **Progressive Souls Leveling:** Earn XP for every added game, physical item, finished book, or homebrew project. Level up based on an exponential Souls-style cost curve!
* **Seasonal Themes:** Unlock dynamic seasonal particle animations and color schemes (*Halloween, Christmas, New Year, Easter*) with a persistent state.

### 🔒 **Privacy & Data Backup**
* **Offline First:** Your data remains 100% local on your device.
* **Permanent Media Storage:** Cover images are stored permanently in local application storage to prevent cache loss.
* **Import / Export System:** Easily export and restore full backups (`JSON` format) including profile data, games, hardware, books, and wishlist items.
* **Multi-Language Support:** Full English and German localization (`en.json`, `de.json`).

---

## 🛠️ Tech Stack & Architecture

| Tech | Description |
| :--- | :--- |
| **Framework** | [Flutter](https://flutter.dev/) (Dart) |
| **State Management** | [Provider](https://pub.dev/packages/provider) |
| **Local Persistence** | `SharedPreferences` + Local File Storage |
| **Localization** | `easy_localization` (English & German) |
| **Media Handling** | `image_picker` + Permanent File Storage Service |

---

## 📜 Version History & Changelog

### 🚀 What's New in Version 1.0.5

* **🤖 AI Integration:** Smart assistant capabilities built directly into the app to help you manage your collection.
* **📔 Journal & Notes:** A dedicated space for your personal game journal entries, thoughts, and progress stories.
* **⏸️ Extended Progress Statuses:** New tracking options including *Paused* and *Cancelled* to keep your collection accurately organized.
* **📸 & 🎬 Advanced Media Management:** 
  * Separate, clean horizontal galleries for screenshots and videos.
  * Pick and save video files directly from your smartphone's media library.
  * Seamless external video playback using your device's native media player.
* **🔒 Comprehensive Backups:** Full support for backing up all your new journal entries, screenshots, and videos seamlessly.

### 🚀 **v1.0.4 – Categories & Persistence Refinement**
* **Dedicated Add Screens:** Restored full standalone creation screens (`AddHardwareScreen`, `AddHomebrewScreen`, `AddBookScreen`).
* **Interactive Detail Screens:** Added click-through detail views and editing capabilities for Hardware, Homebrews, and Books.
* **A-Z Auto Sorting:** Integrated automatic alphabetical sorting across all new categories.
* **Extended Book Statuses:** Added *"Paused"* and *"Dropped"* options with full translation support.
* **Seasonal Theme Persistence:** Theme toggles now save persistently across app restarts.
* **Book Wall:** Added a visual grid wall for gaming books, accessible from the Profile screen.

### 🛠️ **v1.0.3 – Cross-Platform Sync & Dark Souls Overhaul**
* **Linked Game Sync:** Two-way synchronization between primary games and linked multi-platform releases.
* **Updated Souls Leveling:** Added XP rewards for Hardware, Homebrews, and Gaming Books.
* **Image Persistence Fixes:** Enforced permanent local image storage to avoid missing cover art.
* **Archive & Sold Items:** Added support for archiving sold games, hardware, and books.

### 🌟 **v1.0.2 – Visual Expansion & Multi-Language**
* **Game Wall Screen:** Introduced a high-density grid view of all collected game covers.
* **Platform Stats:** Added platform distribution charts and breakdown metrics.
* **German & English Localization:** Full multi-language integration with easy language switching.

### 🐣 **v1.0.1 – Seasonal Themes & Wishlist**
* **Seasonal Particle Effects:** Introduced dynamic animations for Halloween, Christmas, New Year, and Easter.
* **Wishlist Manager:** Dedicated tab for tracking games you plan to buy.

### 🎉 **v1.0.0 – Initial Release**
* Core game tracking, local backup system, Dark Souls EXP system, and dark UI implementation.

---

---

## 📥 Download & Installation

You can download the latest official Android release (`.apk`) directly from the Releases page:

👉 **[Download Latest Release (v1.0.5)](https://github.com/Paxrisen/GameNexum/releases)**

---

## 🔒 License & Copyright

**Copyright © 2026 Paxrisen. All Rights Reserved.**

* **Proprietary Project:** GameNexum is a personal project. The source code is hosted publicly for portfolio and demonstration purposes only.
* **No License Granted:** Redistribution, modification, commercial use, or re-uploading of this codebase or its assets is strictly prohibited without explicit permission from the author.

---

Created with ❤️ for gamers and retro collectors by **[Paxrisen](https://github.com/Paxrisen)**.
