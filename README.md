# VSCode Settings

These are my personal **Visual Studio Code settings** to make your editor clean, fast, and visually appealing. This `settings.json` focuses on:

- Minimal distractions  
- Smooth coding experience  
- Improved typography and readability  
- Efficient workspace navigation  

> Works on Linux, macOS, and Windows (just copy the file to your VSCode User settings folder).

---

## Features

### UI / Editor
- No unnecessary UI clutter: breadcrumbs, tips, hover popups reduced, minimap off  
- Sidebar on the right for better workflow  
- Clean line highlighting and no overview ruler border  
- Sticky scroll disabled for a smooth editor feel  

### Typography
- Fonts: `Geist Mono`, `JetBrains Mono`, `Fira Code`  
- Font size: 16, line height: 32 for comfortable reading  
- Terminal font size: 16 with 1.5 line height  
- Font ligatures enabled for coding aesthetics  

### Coding Enhancements
- Format on save for JS, TSX, Vue, Tailwind, HTML, CSS  
- Word selection includes `-` for faster navigation  
- Snippet suggestions appear on top  
- Auto-trimming trailing whitespace and final newline on save  

### Git / SCM
- Git decorations minimized for less distraction  
- SCM diff decorations hidden  
- Avoid opening repos in parent folders automatically  

### Terminal
- Multiple profiles supported: bash, zsh, fish, tmux, powershell, sh  
- Default: zsh  
- Multi-line paste warning disabled  

### Search / File Management
- Ignores `node_modules`, `vendor`, `dist`, `storage`, lock files, and temp files  
- Explorer sort order by type  

---

## Installation

1. Backup your current `settings.json` (optional).  
2. Copy this file to your VSCode User settings folder:

**Linux:**  
```bash
~/.config/Code/User/settings.json
