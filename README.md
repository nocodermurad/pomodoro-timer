# Notion-Style Pomodoro Timer Widget

A minimalist, monochrome, and clean Pomodoro Timer widget matching Notion's modern aesthetic. Perfect for standalone use or embedding in Notion workspaces, websites, and dashboards.

## Features

- **Timer Modes**: Three selectable modes to manage work and rest intervals:
  - **Pomodoro** (25 minutes)
  - **Short Break** (5 minutes)
  - **Long Break** (10 minutes)
- **Ambient Soundscapes**: Built-in 100% offline client-side synthesizers using the Web Audio API:
  - 🌧️ **Rain**: Soft, soothing pink noise rain patter.
  - 🐦 **Birds**: Randomized morning birds chirping in a quiet forest.
  - 🚂 **Train**: Relaxing low-frequency track rumble and rhythmic track chugs.
- **Responsive Embed Mode**: Automatically detects if it is embedded inside an `iframe` and adjusts its border radius and dimensions to adapt beautifully.
- **Fullscreen API Support**: A subtle fullscreen toggle button in the bottom-right corner.
- **System Themes**: Responsive Light and Dark mode that matches the user's system preferences.
- **Soothing Alert**: A beautiful bell chime sound (A5 + A6) synthesized using Web Audio API when a timer finishes.

## How to Embed in Notion

1. Copy the raw link of this widget (or host it on a platform like Vercel, Netlify, or GitHub Pages).
2. In Notion, type `/embed`.
3. Paste the URL.
4. Resize it to fit your layout. The widget automatically detects the embed state and styles itself accordingly!

## Tech Stack

- **HTML5 & CSS3** (Vanilla, Custom CSS Variables)
- **Vanilla Javascript** (Standard DOM & Web Audio API)
- **No external dependencies** (Entirely self-contained in a single file)
