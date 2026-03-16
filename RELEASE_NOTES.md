## 🚀 Stealth AI Suite v4.0.0

> **The first unified Tauri release of Stealth AI — rebuilt from the ground up for performance, stability, and true stealth.**

---

### ✨ What's New

**🤖 AI App (ai-app)**
- Completely rewritten in **Tauri** — native performance, drastically smaller memory footprint
- **Absolute stealth mode** — window never steals focus, invisible in Alt+Tab and taskbar
- **System tray** integration — Show/Hide, Pause/Resume, and Exit from the tray
- **Transparent screenshot passthrough** — underlying apps visible even when AI overlay is present
- Smart **pause/resume** — pressing `Alt+P` stops key listening so you can type normally in other apps
- Faster **auto-typing** with improved reliability for long AI responses
- Responsive layout — compact mode hides UI elements when window is small

**🔐 Auth Manager (auth-manager)**
- Rebuilt in **Tauri** for native window performance
- Fully unified database — same `%AppData%\Stealth AI` folder shared with the AI App

**🔗 Shared Suite**
- **Single shared database** — login once in Auth Manager, AI App instantly picks up your session, API keys, and subscription
- **GitHub Auto-Updater** — both apps silently check for updates on startup with a 3-day grace period before mandatory update
- Custom **app icon** across tray, taskbar, and installers

---

### 📦 Downloads

| File | Description |
|------|-------------|
| `StealthAI-Setup-4.0.0.exe` | **Recommended** — Full installer for both apps |
| `ai-app-portable-4.0.0.exe` | AI App — portable, no install needed |
| `auth-manager-portable-4.0.0.exe` | Auth Manager — portable, no install needed |

---

### ⌨️ Keyboard Shortcuts

| Shortcut | Action |
|----------|--------|
| `Alt+M` | Show / Hide window |
| `Alt+P` | Pause / Resume key capture |
| `Alt+S` | Screenshot & attach to chat |
| `Alt+T` | Auto-type AI response |
| `Alt+C` | Copy last AI response |
| `Alt+V` | Submit clipboard content |

---

> **Note:** This is a **major milestone release**. The Electron version is no longer maintained. All future updates will be Tauri-based.
