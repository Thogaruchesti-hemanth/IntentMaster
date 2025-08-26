# 🚀 Mastering Intents - Android Playground App

![Android](https://img.shields.io/badge/Android-Intents-green?logo=android)
![Java](https://img.shields.io/badge/Language-Java-blue?logo=java)
![Status](https://img.shields.io/badge/Status-Active-brightgreen)
![Contributions](https://img.shields.io/badge/Contributions-Welcome-orange)

> 📱 A **practical playground app** to learn, practice, and master **Intents & Intent Filters** in Android.  
> Designed with multiple sections (via **ViewPager** + **BottomSheet Navigation**) that cover **Explicit Intents, Implicit Intents, Common Intent Filters, and Deep Links**.

---

## 📖 Table of Contents
- [Introduction](#-introduction)
- [Features](#-features)
- [App Structure](#-app-structure)
- [Pages Overview](#-pages-overview)
  - [Page 1: Implicit Intents Playground](#page-1-implicit-intents-playground)
  - [Page 2: Explicit Intents](#page-2-explicit-intents)
  - [Page 3: Common Intent Filters](#page-3-common-intent-filters)
  - [Page 4: Deep Links](#page-4-deep-links)
- [Learning Outcomes](#-learning-outcomes)
- [Future Enhancements](#-future-enhancements)
- [Screenshots](#-screenshots)
- [Installation & Setup](#-installation--setup)
- [Contributing](#-contributing)
- [License](#-license)

---

## 📌 Introduction
This app is designed as a **final destination to master Intents in Android**.  
It is **beginner-friendly** but comprehensive enough for **intermediate developers** who want to:  
- Understand **how Intents work**.  
- Explore **real-world intent use cases**.  
- Learn **deep linking** and **common intent filters**.  

---

## ✨ Features
✔️ 20+ real-world **Implicit Intents**  
✔️ Clear examples of **Explicit Intents**  
✔️ Fully functional **Common Intent Filters list**  
✔️ Deep Link tester (paste URL → open app/browser)  
✔️ **BottomSheet Navigation + ViewPager** for modern UI  
✔️ Intent safety handling with `resolveActivity()`  
✔️ Intent Chooser dialogs for user-friendly app selection  

---

## 🏗️ App Structure
- **MainMenuActivity**
  - Hosts a `ViewPager` (multiple pages).
  - Controlled by a `BottomSheet` navigation menu.

- **Pages**:
  1. Implicit Intents Playground  
  2. Explicit Intents  
  3. Common Intent Filters  
  4. Deep Links  

---

## 📑 Pages Overview

### 📍 Page 1: Implicit Intents Playground
- A **grid of ~20 apps/tasks**, each demonstrating a different implicit intent.  
- Examples:  
  - Open Browser (`ACTION_VIEW`)  
  - Open Dialer (`ACTION_DIAL`)  
  - Make Call (`ACTION_CALL`)  
  - Open Camera (`ACTION_IMAGE_CAPTURE`)  
  - Send Email (`ACTION_SENDTO`)  
  - Open Maps (`geo:` URI)  
  - Share text (`ACTION_SEND`)  
  - Pick image/file (`ACTION_GET_CONTENT`)  
  - Open Settings (`ACTION_SETTINGS`)  
  - Set Alarm / Timer  
  - …and more!  

---

### 📍 Page 2: Explicit Intents
- Demonstrates **navigating to another Activity** within the app.  
- Covers:
  - `startActivity()`  
  - Passing data with `putExtra()` / `getExtra()`  
  - Returning results (`ActivityResultLauncher`)  

---

### 📍 Page 3: Common Intent Filters
- A **list of common intent filters** with working examples.  
- Each example shows how different apps can respond to the same intent.  
- Examples:  
  - `ACTION_VIEW` → open link in Chrome / Firefox / Edge.  
  - `ACTION_SEND` → share to Gmail / WhatsApp / Messenger.  
  - `ACTION_DIAL` → different dialer apps.  

---

### 📍 Page 4: Deep Links
- UI with an **input field** to paste a URL.  
- Opens the target app if installed (e.g., YouTube, Instagram).  
- Fallback: open in browser.  

---

## 🎯 Learning Outcomes
By completing this project, you will:  
- ✅ Understand **Explicit vs Implicit Intents**.  
- ✅ Practice **data passing** between Activities.  
- ✅ Explore **20+ real-world intent use cases**.  
- ✅ Learn how **Intent Filters** enable multiple apps to respond.  
- ✅ Work with **Deep Links & Chooser dialogs**.  
- ✅ Safely handle intents with `resolveActivity()`.

---

## 🚀 Future Enhancements
- 🔔 Add **Broadcast Intent examples** (Battery, Connectivity).  
- ⏰ Add **PendingIntent examples** (Alarms, Notifications).  
- 📚 Add **Launch Modes & Task Affinity demo**.  
- 🔗 Add **Verified App Links (Digital Asset Links JSON)**.  
- 🛠️ Add an **Intent Debugger logger** (show which apps can handle an intent).  

---

## 🖼️ Screenshots
| Main Menu | Implicit Intents | Explicit Intents | Deep Links |
|-----------|-----------------|------------------|------------|
| ![MainMenu](docs/screenshots/mainmenu.png) | ![Implicit](docs/screenshots/implicit.png) | ![Explicit](docs/screenshots/explicit.png) | ![DeepLink](docs/screenshots/deeplink.png) |

*(Screenshots to be added after UI implementation)*  

---

## ⚙️ Installation & Setup
1. Clone this repo:
   ```bash
   git clone https://github.com/your-username/mastering-intents.git
   ```

2. Open in **Android Studio**.
3. Sync Gradle and run on an emulator/physical device (API 24+ recommended).

---

## 🤝 Contributing

Contributions are welcome! 🎉

1. **Fork** the repo.
2. Create a new branch:

   ```bash
   git checkout -b feature-new-intent
   ```
3. Commit your changes:

   ```bash
   git commit -m "Added new implicit intent example"
   ```
4. Push and open a **Pull Request**.

---

## 📜 License

This project is licensed under the **MIT License**.
You are free to use, modify, and distribute it.

---

## 👨‍💻 Author

**Sai Hemanth**
📧 Reach me at: \[[saihemanth225@gmail.com](mailto:saihemanth225@gmail.com)]

