# VSCode Settings

These are my personal **Visual Studio Code settings** to make the editor clean, distraction-free, and visually sharp.  
Instead of repeating defaults, this setup highlights unique tweaks that actually change the coding experience:

- Distraction-free editing (no noisy highlights, icons, or popups)  
- Calmer typography and page-like reading flow  
- Smart navigation and search tuned for real projects  
- Custom shell profiles and workflow optimizations  

> Works on **Linux, macOS, and Windows** — just copy the `settings.json` into your VSCode User folder.

---

## Screenshot

Here’s how my VSCode looks with these settings:  

![VSCode Screenshot](settings.json.png)

---

## Notable Tweaks

### 🎨 UI / Editor
- 🚫 **Noise-free editing**: disables squiggles, selection highlights, hover spam, color decorators, lightbulbs, and gutter icons  
- 📐 **Sidebar on the right** + Activity bar moved to the **top** for better wide-screen ergonomics  
- 🕒 **Delayed hover tooltips** (`1500ms`) → no more instant popups in your face  
- 🎯 **One-click “Goto”** navigation (skips menus, jumps straight to definition/refs/impl)  
- 🌳 **Explorer indentation widened** (`15px`) for more breathing room  
- ➕ **Extra editor padding** (`16px top`) and **line height 32** → makes code feel like reading text, not clutter  

### ✍️ Typography
- Fonts: **Geist Mono**, **JetBrains Mono**, **Fira Code**  
- Advanced ligatures enabled (`ss01–ss08`, `calt`, `dlig`) → refined aesthetics, not just “Fira Code ligatures on”  
- Font size `16`, with **solid cursor** (no blinking distraction)  

### 🔍 Search & File Management
- **Regex exclusions** to hide noisy `vendor`, `public`, `dist`, etc. but still allow important files (`/livewire`, `index.php`)  
- Auto-save after delay  
- Explorer sorting by **type**  

### 🌀 Git / SCM
- No gutter icons, no diff decorations → Git noise stays in Git, not your editor  

### 💻 Terminal
- Profiles for **bash, zsh, fish, tmux, pwsh, sh**  
- Default: **zsh**  
- Multi-line paste warning disabled → less interruptions  

### 🐘 PHP & Dev Workflow
- Disables basic PHP IntelliSense spam  
- `.php_cs` and `.php_cs.dist` properly mapped to PHP  
- Special integration for AI/chat instructions (`chat.instructionsFilesLocations`)  

---

## Installation

1. Backup your current `settings.json` (optional).  
2. Copy this file to your VSCode User settings folder:

**Linux:**  
```zsh
~/.config/Code/User/settings.json
```

**macOS:**  
```bash
~/Library/Application Support/Code/User/settings.json
```

**Windows:**  
```powershell
%APPDATA%\Code\User\settings.json
```
