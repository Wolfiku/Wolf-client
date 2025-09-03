# 🐺 Wolf Client

Wolf Client is a clean, colorful, and easy-to-use **web app** designed for iPads.  
It focuses on **tools, features, and fun** – not cheating.  
The app comes with a wolf-themed design, daily background images, and a modular tool system.

---

## ✨ Features
- **Daily Wolf Background**  
  A new wolf image every day via an API, cached for offline use.  
  (Fallback to a default image when offline)

- **Homescreen**  
  - Central logo and search bar for tools  
  - Tool list (button bottom-left)  
  - Settings (button bottom-right)  
  - Loading animation until everything is ready  

- **Tools**  
  - Stored as individual HTML files in `system/programms/`  
  - Managed via `system/list/tools.json`  
  - Organized by type (e.g., AI, Web) with default icons  

- **Caching & Offline Support**  
  - LocalStorage/IndexedDB for images and daily start screen  
  - Lazy loading for faster performance  

- **Error Handling**  
  - Friendly error screen if files or APIs fail to load  

---

## 📂 Project Structure
wolf-client/ ├── index.html               # Start screen (once per day message) ├── homescreen.html          # Main screen with background and tools ├── system/ │   ├── programms/           # Tools as HTML files │   └── list/tools.json      # Tool list with names, files, and types ├── assets/ │   ├── default-bg.jpg       # Fallback background │   └── icons/               # Standard icons (settings, list, ai, web, ...) └── style.css           

## 🚀 Hosting
Wolf Client is hosted via **GitHub Pages**.  
Custom domain support is planned (budget: ~10€/year).

---

## 🛠️ Roadmap
- [ ] Implement `index.html` with daily splash screen  
- [ ] Implement `homescreen.html` with wolf background and tool system  
- [ ] Add settings for choosing other APIs (dogs, cats, or preset images)  
- [ ] Add more tools (AI, utilities, fun apps)  
- [ ] Optimize performance on iPads  

---

## 📜 License
MIT License – free to use, modify, and share.  

---

## 🙌 Credits
- Developed by **@wolfikuproduction**  
- Powered by Limbo  
- Wolf images provided via Unsplash API
