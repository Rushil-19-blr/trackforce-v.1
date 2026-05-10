# 🏎️ TrackForce

Unlock the Hidden Power of your Mac's Force Touch Trackpad.

TrackForce is a high-performance macOS utility that turns your trackpad into a multi-dimensional productivity tool. It combines deep hardware integration with haptic feedback, custom gestures, and "Force Shortcuts" to streamline your workflow.

***

## 🌟 Key Features

### 🛠️ Force Shortcuts
   Pressure-Triggered Actions: Launch any application or paste custom text by applying force to the trackpad while hitting a key (e.g., Force + M ➔ Music).
   Custom Thresholds: Calibrate your trackpad to your touch. Set the exact pressure (in grams) required to trigger shortcuts to avoid accidental activations.

### 📐 Force Corners
   Hot Corners for Trackpads: Assign custom actions to the four corners of your trackpad. Trigger them by swiping inward from the corner with a force-press.
   App Switching & System Controls: Quickly toggle Mission Control, Launchpad, or custom app launches.

### ✍️ Force Gestures
   Scribble to Launch: Draw custom shapes on your trackpad with force to trigger actions.
   Unistroke Recognition: Uses the $1 Recognizer to identify your drawings (circles, squares, hearts, etc.) and map them to productivity tasks.

### 🔔 Haptic Notifications
   Tactile Alerts: Intercept system notifications and translate them into custom haptic patterns on your trackpad.
   App-Specific Haptics: Customize the "vibration" pattern for specific apps, allowing you to know which app is notifying you without looking at the screen.

### 🎨 Visualisation & Testing
   Live Touch Previews: Watch your trackpad transform into a flexible 3D grid that physically bends as you apply pressure.
   Pressure Heatmaps: Dynamic color-shifting (Cyan ➔ Purple) based on intensity.
   Experimental Canvas: A pressure-sensitive drawing mode for testing gesture recognition.

***

## 🚀 Getting Started

### 1. Installation
1.  Clone & Build: Open the `Demo/OMSDemo.xcodeproj` in Xcode 16+.
2.  Run: Build and run the `TrackForce` scheme.
3.  Permissions: On first launch, the TrackForce Onboarding will guide you through enabling the necessary macOS permissions:
       Accessibility: Required to monitor trackpad input globally and handle shortcuts.
       Input Monitoring: Required to read raw pressure data from the hardware.

### 2. Usage
Look for the Hand Icon in your Menu Bar. From there, you can:
   Open the main configuration window.
   Pause/Start monitoring.
   Check your calibration status.

***

## 🏗️ Developer Framework (`OpenMultitouchSupport`)

TrackForce is built upon the `OpenMultitouchSupport` framework, which provides raw access to Apple's private Multitouch drivers.

   Raw Data: Access X/Y coordinates, pressure, axis major/minor, and capacitance density.
   Haptic Engine: Programmatically trigger the trackpad's haptic Taptic Engine with custom actuation IDs.
   Device Management: Support for built-in and external Magic Trackpads.

***

## ⚖️ License & Credits

Developer: Rushil Sunder

TrackForce is built upon the `OpenMultitouchSupport` library, a fork of [Kyome22/OpenMultitouchSupport](https://github.com/Kyome22/OpenMultitouchSupport).

***
Created with ❤️ for the macOS Power User.
