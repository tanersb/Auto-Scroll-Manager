# Auto Scroll Manager 🖱️

A modern, Tampermonkey-based auto-scroll tool designed to enhance your web reading and viewing experience. It features butter-smooth scrolling (60/144Hz support), smart element detection, and a dedicated timer mode for short-form content like Reels/Shorts.

## 🌟 Features

* **Butter Smooth Performance:** Uses `requestAnimationFrame` logic instead of standard intervals, ensuring stutter-free scrolling optimized for high refresh rate monitors.
* **Click-to-Focus (Smart Detection):** The script automatically detects which part of the page you want to scroll. Just click on a comment section, a sidebar, or the main content, and the script will lock onto that target.
* **Drag & Drop:** You can move the widget anywhere on the screen by dragging the header.
* **Smart Persistence:** The widget remembers its last position and state (collapsed/expanded) even after you refresh the page or open a new tab.
* **Timer Mode (Reels/Shorts):** Specifically designed for Instagram Reels, YouTube Shorts, or TikTok. Set a duration (e.g., 15 seconds), and it will automatically swipe to the next video when the time is up.
* **Collapsible UI:** Click the header to minimize the panel into a tiny floating icon to save screen space.
* **Live Debug HUD:** Displays real-time data including the active element being scrolled, current speed, timer countdown, and mouse coordinates.

## 🎮 Controls

### 1. Continuous Scrolling (Standard)
Use the large Arrow buttons for reading articles or browsing feeds.
* **Up/Down Arrows:** Starts scrolling. Pressing the button again increases the speed (Gas pedal logic).
* **Input Box:** You can manually type a speed value (e.g., `5`) and press an arrow to start at that speed immediately.
* **Stop (Red Square):** Instantly stops scrolling. **Note:** It does not reset your speed value, allowing you to resume at the same pace.

### 2. Timer Mode (For Reels/Shorts)
Use the smaller buttons located above the input box.
* **Set Time:** Enter a value in the input box (e.g., `10` for 10 seconds).
* **Timer Up/Down (Small Arrows):** Starts the countdown.
* **Behavior:** The script waits for the specified seconds, then performs a full-page scroll to the next video, and repeats the cycle.

## 🚀 Installation

1.  Install the [Tampermonkey](https://www.tampermonkey.net/) extension for your browser.
2.  Click the Tampermonkey icon and select **"Create a new script"**.
3.  Delete all existing code in the editor.
4.  Copy and paste the content of `script.js` from this project.
5.  Press **File > Save** (or Ctrl+S).

## 👨‍💻 Developer

Developed by **@tanersb**.
