# ⚡ Level Up

**Small Steps. Real Progress.**

Level Up is a simple, offline-friendly habit tracker that helps you build routines, organize tasks, and track your personal progress through XP and levels.

## ✨ Features

- **Daily overview** — see your tasks and completion progress for today.
- **Custom categories** — organize habits and tasks by topic.
- **Flexible schedules** — set tasks to repeat daily, on selected days, or just once.
- **Progress tracking** — view your XP, level, streak, weekly completion rate, and recent history.
- **Dark and light themes** — switch the app's appearance in Settings.
- **Local data storage** — your data is saved in the browser on your device.
- **Import and export** — back up your progress as a JSON file and restore it later.
- **Offline support** — the app includes a web app manifest and service worker for caching app files.

## 🚀 Getting Started

### Run locally

1. Download or clone this repository.
2. Open `index.html` in a browser to preview the interface.

> Note: Service workers and installable Progressive Web App (PWA) features generally require a secure context, such as HTTPS or localhost. For offline installation, deploy the project over HTTPS first.

### Deploy with GitHub Pages

1. Push the project files to the root of a GitHub repository.
2. Open **Settings → Pages**.
3. Under **Build and deployment**, choose **Deploy from a branch**.
4. Select the `main` branch and the `/ (root)` folder, then save.
5. Open the published GitHub Pages URL in your browser.

For a project repository named `level-up`, the URL typically looks like:

`https://YOUR-USERNAME.github.io/level-up/`

Replace `YOUR-USERNAME` with your GitHub username.

## 📲 Install on Android

1. Open the deployed HTTPS site in Chrome.
2. Allow the page to finish loading while online.
3. Open Chrome's menu and select **Install app** or **Add to Home screen**, if available.
4. Open Level Up from its home-screen icon.

To test offline mode, open the app once while online, then enable airplane mode and launch it again.

## 🗂️ Project Structure

```text
level-up/
├── index.html
├── manifest.webmanifest
├── sw.js
├── icon-192.png
├── icon-512.png
└── README.md
```

The icon files must exist at the paths referenced by the HTML, manifest, and service worker.

## 💾 Your Data

Level Up stores tasks and progress in the browser's local storage on the current device/browser. Data is **not automatically synced** between devices.

- Use **Settings → Export data (JSON)** to create a backup.
- Use **Settings → Import data (JSON)** to restore a backup.
- Avoid clearing browser/app storage unless you have a backup.

## 🧰 Built With

- HTML
- CSS
- JavaScript
- Browser Local Storage
- Web App Manifest
- Service Worker API

## ⚠️ Notes

- Offline availability depends on the service worker successfully caching the required files while the app is online.
- If the app files change, the service worker cache may need to update before the newest version appears.
- This project does not include cloud sync or an account system.

## 📄 License

No license has been added yet. Unless you add a license file, others should not assume they have permission to reuse, modify, or distribute this project.

---

Made with ⚡ and small steps.
