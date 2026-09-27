# 🌤️ Nimbus Weather (Standard Edition)

> A lightweight, privacy-focused, and ad-free weather application for Android featuring a clean Leaflet rain radar, dynamic canvas animations, and smart daily briefings.

---

## ✨ Features

### 🌧️ Clean & Fluid Leaflet Rain Radar
- **Interactive Map:** High-performance Leaflet.js map with responsive zoom and pan.
- **Player Controls:** Play/pause past and current precipitation radar frames (2-hour timeline).
- **Fast & Lightweight:** Smooth tile loading without intrusive ads or bloated tracking scripts.

### 🎨 Dynamic Background Animations
- **Condition-Aware Canvas:** Real-time HTML5 particle rendering for Rain, Snow, Thunderstorms, and Sunbeams.
- **Battery-Optimized:** Built with `requestAnimationFrame()` and automatic pause handling when the app goes into the background or the screen locks.
- **Toggle Support:** Disable background animations anytime via settings for maximum performance.

### 🔔 Smart Push Notifications
- **Morning Briefing:** Get your daily forecast (e.g., max temperature & rain warnings) right at 07:00 AM.
- **Evening Preview:** A quick outlook for the next day around 08:00 PM.
- **Severe Weather Alerts:** Real-time notifications for sudden weather changes powered by native Android `WorkManager`.

### 🛡️ Privacy First & Performance
- **Zero Ads & Trackers:** No third-party ad networks or user tracking.
- **Fast Launch:** Instant startup time and low memory footprint.
- **Standard Widget:** Clean pre-styled homescreen widget for quick weather checks.

---

## 📱 Coming Soon: Nimbus Weather Pro

I am currently finalizing **Nimbus Weather Pro**, which will be released on the Google Play Store! 

**Pro Features will include:**
- 🎛️ **Full Widget Customizer:** Real-time opacity/transparency sliders & scale controls.
- 🧩 **Custom Data Slots:** Choose custom metrics (UV index, AQI, air pressure, wind speeds) for your widgets.
- 🎯 **Smart Tap Zones:** Quick shortcuts to click directly into your Alarm Clock, Calendar, or App from the widget.
- 🎨 **Icon Color Protection & Badges:** Adaptive text and icon visibility for any wallpaper setup.

---

## 📥 Installation

1. Go to the Releases section.
2. Download the latest `Nimbus-Weather-v1.0.0.apk`.
3. Open the file on your Android device and confirm the installation.

---

## 🛠️ Tech Stack
- **Frontend:** HTML5 Canvas, CSS3, JavaScript
- **Map Engine:** Leaflet.js + RainViewer Radar Tiles
- **Android Native Bridge:** Capacitor JS
- **Native Android:** Kotlin, `WorkManager`, `NotificationChannels`

---

## 💬 Feedback & Bug Reports
If you encounter any bugs, have device-specific rendering issues, or want to suggest features, please open an issue under **[GitHub Issues](https://github.com/DEIN_USERNAME/DEIN_REPO_NAME/issues)** or reach out on Reddit!
