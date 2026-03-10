# Telepromptly — Professional Floating Teleprompter for Android

<div align="center">

![Version](https://img.shields.io/badge/version-1.0.1-blue)
![Android](https://img.shields.io/badge/Android-8.0%2B-brightgreen)
![Kotlin](https://img.shields.io/badge/Kotlin-1.9-purple)
![Status](https://img.shields.io/badge/Status-Production-success)
![License](https://img.shields.io/badge/License-Proprietary-red)

**A professional floating teleprompter app for Android — helps content creators, presenters, and public speakers read scripts naturally while recording or presenting.**

</div>

---

## Overview

Telepromptly provides a floating overlay window that displays your scripts while you record or present, letting you maintain natural eye contact with your camera. Works with any camera app — Instagram, TikTok, YouTube, native camera, and more.

---

## Key Features

### Floating Overlay System
- Persistent overlay that stays on top of all apps
- Draggable — move the teleprompter anywhere on screen
- Resizable modes: Full screen (100%), Half screen (50%), Compact (30%)
- Semi-transparent background with adjustable opacity
- Always-accessible controls: play/pause, speed, close

### Auto-Scroll Engine
- Fractional speed control: 0.25x to 10x
- Smooth scrolling with precise speed increments
- Play/Pause with visual feedback
- Progress indicator showing current position
- Resume from last position — never lose your place

### Script Management
- Create unlimited scripts with rich text editor
- Organize with folders
- Search by title or content
- Recent scripts for quick access
- Import from .txt files or clipboard
- Sample templates included

### Appearance Customization
- Font size adjustment (12sp to 72sp)
- Text alignment: Left, Center, Right
- Mirror mode for teleprompter glass setups
- Custom text and background colors
- Line spacing control

### Additional Features
- Script templates for different use cases
- Word count and estimated read-time
- Completely free — no ads, no subscriptions
- All data stored locally — no cloud sync

---

## Tech Stack

| Layer | Technology |
|---|---|
| Language | Kotlin |
| UI | Jetpack Compose + Material 3 |
| Architecture | MVVM + Clean Architecture |
| Overlay | Android WindowManager (TYPE_APPLICATION_OVERLAY) |
| Local DB | Room |
| Preferences | DataStore |
| DI | Hilt |
| Navigation | Jetpack Navigation Compose |

---

## Requirements

- **Minimum SDK:** Android 8.0 (API 26)
- **Target SDK:** Android 14 (API 34)
- **Permission required:** Display over other apps (SYSTEM_ALERT_WINDOW)

---

## Source Code

This is a showcase repository. The full source code is private and proprietary.  
For collaboration or code review inquiries, please reach out directly.

---

## Developer

**Ajith Prasad PV**  
Android Developer  
[GitHub](https://github.com/ajithprasadpv)
