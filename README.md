# ZenIDE
An IDE that's something truly special: **an IDE that respects attention**. The gradients will just make that respect feel *alive*. 💫
# 🧘 ZenIDE – Breathe Easy, Code Focused

A clutter-free, tab-based web IDE that runs entirely in your browser. No installs, no signups, no distractions.

[![Live Demo](https://img.shields.io/badge/Demo-GitHub_Pages-1e1e1e?logo=github)](https://your-username.github.io/zenide)
[![PWA](https://img.shields.io/badge/PWA-Installable-4d7fff)](#installation)

![ZenIDE Preview](https://placehold.co/800x400/1e1e1e/2d2d30?text=ZenIDE+-+Tab-Based+Web+IDE&font=montserrat)

## ✨ Why ZenIDE?
- **Tab-per-context**: Editor, Terminal, AI Chat, Problems — each in its own tab
- **Real-time error detection**: Catches syntax mistakes as you type (Python & JavaScript)
- **Native file handling**: Save/open directly to your device (Chrome/Edge)
- **Zero bloat**: Single HTML file, <500KB, works offline
- **Android-ready**: Install like a native app via "Add to Home Screen"

## 🛠️ Features
| Tab | Function |
|-----|----------|
| **Editor** | Monaco-powered (VS Code engine) with live linting |
| **Terminal** | Simulated CLI with run suggestions (`python file.py`) |
| **AI Chat** | Contextual help when errors appear |
| **Problems** | List of all errors/warnings with line numbers |

## ▶️ Try It Now
1. Open in **Chrome, Edge, or Brave**:  
   👉 [Live Demo](https://your-username.github.io/zenide)
2. **On Android**: Tap **⋮ → Add to Home screen** to install

## 💾 File Support
- **Open/Save**: `.py`, `.js`, `.txt` (via File System Access API)
- **Fallback**: Other browsers download files on save

## 🔍 Debugging Capabilities
- **Syntax errors**: Highlighted instantly in red
- **Warnings**: Shown in orange (e.g., unused variables)
- **No runtime debugger**, but catches 90% of common coding mistakes before execution

## 📲 Installation (PWA)
Works on **Android, iOS, Windows, macOS**:
1. Open in a modern browser
2. Choose **"Install"** or **"Add to Home Screen"**
3. Launch from your app drawer — no internet required after first load!

## 🌐 Privacy First
- **100% client-side**: Your code never leaves your device
- **No analytics**, no tracking, no cookies

---

> Built with [Monaco Editor](https://microsoft.github.io/monaco-editor/) • [Xterm.js](https://xtermjs.org/) • [Shoelace](https://shoelace.style/)
![ZenIDE Preview](assets/preview.png)
> ![ZenIDE Preview](https://svgviewer.dev/#data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSI4MDAiIGhlaWdodD0iNDAwIiB2aWV3Qm94PSIwIDAgODAwIDQwMCI+CiAgPGJhY2tncm91bmQgZmlsbD0iIzFlMWUxZSIvPgogIDwhLS0gVG9wIFRvb2xiYXIgLS0+CiAgPHJlY3QgeD0iMCIgeT0iMCIgd2lkdGg9IjgwMCIgaGVpZ2h0PSI0MCIgZmlsbD0iIzI1MjUyNiIvPgogIDx0ZXh0IHg9IjIwIiB5PSIyNyIgZm9udC1mYW1pbHk9InN5c3RlbS11aSIgZm9udC1zaXplPSIxNCIgZmlsbD0iI2Q0ZDRkNCI+Zm9sZGVyOiBPcGVuIC8gU2F2ZSAvIE5ldzwvdGV4dD4KCiAgPCEtLSBUYWIgQmFyIC0tPgogIDxyZWN0IHg9IjAiIHk9IjQwIiB3aWR0aD0iODAwIiBoZWlnaHQ9IjMwIiBmaWxsPSIjMjUyNTI2Ii8+CiAgPHRleHQgeD0iMjAiIHk9IjYwIiBmb250LWZhbWlseT0ic3lzdGVtLXVpIiBmb250LXNpemU9IjE0IiBmaWxsPSIjNDQ0NDQ0Ij5UZXJtaW5hbDwvdGV4dD4KICA8dGV4dCB4PSIxMTAiIHk9IjYwIiBmb250LWZhbWlseT0ic3lzdGVtLXVpIiBmb250LXNpemU9IjE0IiBmaWxsPSIjZGRkZGRkIj5NYWluLnB5PC90ZXh0PgogIDx0ZXh0IHg9IjIwMCIgeT0iNjAiIGZvbnQtZmFtaWx5PSJzeXN0ZW0tdWkiIGZvbnQtc2l6ZT0iMTQiIGZpbGw9IiM0NDQ0NDQiPkFJIENoYXQ8L3RleHQ+CiAgPHRleHQgeDIwMCIgeT0iNjAiIGZvbnQtZmFtaWx5PSJzeXN0ZW0tdWkiIGZvbnQtc2l6ZT0iMTQiIGZpbGw9IiM0NDQ0NDQiPlByb2JsZW1zPC90ZXh0PgoKICA8IS0tIEVkZXRvciBQYW5lIC0tPgogIDxyZWN0IHg9IjIwIiB5PSI4MCIgd2lkdGg9Ijc2MCIgaGVpZ2h0PSIyNjAiIGZpbGw9IiMyZDJkMzAiIHN0cm9rZT0iIzMzMzMzMyIgc3Ryb2tlLXdpZHRoPSIxIiByeD0iNSIvPgogIDx0ZXh0IHg9IjQwIiB5PSIxMDUiIGZvbnQtZmFtaWx5PSJtb25vc3BhY2UiIGZvbnQtc2l6ZT0iMTQiIGZpbGw9IiNmZmZmZmYiPiMgV2VsY29tZSB0byBaZW5JREU8L3RleHQ+CiAgPHRleHQgeD0iNDAiIHk9IjEzNSIgZm9udC1mYW1pbHk9Im1vbm9zcGFjZSIgZm9udC1zaXplPSIxNCIgZmlsbD0iI2YxNGM0YyI+ZXJyb3I6IHByaW50IGlzIHVuZGVmaW5lZDwvdGV4dD4KICA8dGV4dCB4PSI0MCIgeT0iMTY1IiBmb250LWZhbWlseT0ibW9ub3NwYWNlIiBmb250LXNpemU9IjE0IiBmaWxsPSIjZmZmZmZmIj5wcmludCgiSGVsbG8sIGZvY3VzZWQgY29kaW5nISIpPC90ZXh0PgoKICA8IS0tIEFjdGl2aXR5IFN0cmlwIC0tPgogIDxyZWN0IHg9IjAiIHk9IjM1MCIgd2lkdGg9IjgwMCIgaGVpZ2h0PSI1MCIgZmlsbD0iIzAwMDAwMCIvPgogIDx0ZXh0IHg9IjIwIiB5PSIzNzUiIGZvbnQtZmFtaWx5PSJzeXN0ZW0tdWkiIGZvbnQtc2l6ZT0iMTIiIGZpbGw9IiNkZGRkZGQiPlRlcm1pbmFsOiBSdW46IHB5dGhvbiBtYWluLnB5PC90ZXh0PgogIDx0ZXh0IHg9IjM1MCIgeT0iMzc1IiBmb250LWZhbWlseT0ic3lzdGVtLXVpIiBmb250LXNpemU9IjEyIiBmaWxsPSIjZmY2NjY2Ij5Qcm9ibGVtczogMSBlcnJvcjwvdGV4dD4KCiAgPCEtLSBBY2NlbnQgRG90IC0tPgogIDxjaXJjbGUgY3g9Ijc4MCIgY3k9IjIwIiByPSI2IiBmaWxsPSIjNGQ3ZmZmIi8+Cjwvc3ZnPg==)
> [![Live Demo](https://img.shields.io/badge/Demo-GitHub_Pages-1e1e1e?logo=github&logoColor=white)](https://mandarab.github.io/zenide)
[![PWA](https://img.shields.io/badge/PWA-Installable-4d7fff?logo=pwa)](https://mandarab.github.io/zenide)
