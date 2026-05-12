# 🏎️ TrackForce

**The Ultimate Force Touch Productivity Suite for macOS.**

TrackForce is a high-performance utility that transforms your Mac's trackpad into a multi-dimensional automation interface. By leveraging the trackpad's pressure sensitivity, TrackForce allows you to trigger complex workflows, launch apps, and interact with your Mac in ways never before possible.

---

## 🚀 Getting Started

### 📥 1. Download & Installation (Pre-built)
1.  **Download** the latest `TrackForce.zip` from the [Releases](https://github.com/Rushil-19-blr/Trackforce/releases) page.
2.  **Unzip** the file and move `TrackForce.app` to your `/Applications` folder.

### 🛡️ 2. Security & Gatekeeper (Important)
Since TrackForce is an independent utility, macOS might block it initially because it is not from a "Registered Developer."
1.  **Right-click** (or Control-click) `TrackForce.app` and choose **Open**.
2.  In the dialog that appears, click **Open**.
3.  If you still see a warning, go to **System Settings > Privacy & Security**, scroll down to the bottom, and click **"Open Anyway"** for TrackForce.

### 🔑 3. Permissions
TrackForce requires two system permissions to function:
*   **Accessibility**: To monitor trackpad input and trigger shortcuts globally.
*   **Input Monitoring**: To read high-resolution raw pressure data from the hardware.
*   *The app will guide you through these during the first launch onboarding.*

---

## ✨ Features

### 🤖 Shortcuts Assistant (AI-Powered)
The "Shortcuts Assistant" tab is powered by Google's Gemini AI. You no longer need to manually configure complex triggers—just ask.
*   **Natural Language**: "When I force-click S, open Safari and Google Docs."
*   **Automatic Scripting**: The AI automatically writes and installs the AppleScripts needed to perform your request.

### ⛓️ Multi-Step Workflows
Create complex sequences that run with a single gesture.
*   **Chain Actions**: Launch an app ➔ Wait 2 seconds ➔ Open a specific URL ➔ Paste template text ➔ Run AppleScript.
*   **Robust Engine**: Uses a dedicated background runner with support for `osascript` (AppleScript) and native macOS Shortcuts.

### 🛠️ Force Shortcuts
*   **Pressure-Triggered Actions**: Apply force to the trackpad while hitting any key (A-Z) to trigger an action.
*   **Force Corners**: Swipe inward from the corners of your trackpad with a force-press to trigger system actions like Mission Control or App Switching.

### ✍️ Force Gestures
*   **Scribble to Launch**: Draw shapes (Circles, Squares, Hearts) with force on your trackpad to trigger custom automations.

### 🎯 Pro Calibration
TrackForce allows you to set the **exact pressure threshold** (in grams) required for a trigger. This ensures that your normal trackpad usage never accidentally triggers a shortcut.

---

## 🏗️ Building From Source

If you prefer to build the app yourself:
1.  Open `Trackforce.xcodeproj` in Xcode 16+.
2.  Select the **TrackForce** scheme.
3.  Ensure your Team/Signing settings are configured.
4.  Build and Run (**⌘R**).

---

## ⚖️ License & Credits

**Developer:** Rushil Sunder

Built upon the `OpenMultitouchSupport` framework. Special thanks to the reverse-engineering community (mhuusko5, calftrail) for making private multitouch drivers accessible.

---
*Created with ❤️ for the macOS Power User.*
