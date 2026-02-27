# 🧬 SOMA — Your Body Operating System

> A futuristic personal health dashboard that visualizes your body as an operating system. Track nutrition, sleep, fitness, hydration, and mental health in real-time with a stunning sci-fi interface.

![SOMA Dashboard](https://img.shields.io/badge/SOMA-v2.4.1-00ffb4?style=for-the-badge&labelColor=020408&color=00ffb4)
![HTML](https://img.shields.io/badge/HTML-Pure-00c8ff?style=for-the-badge&labelColor=020408)
![License](https://img.shields.io/badge/License-MIT-ff3e6c?style=for-the-badge&labelColor=020408)

---

## ✨ Features

- **🔐 Personal Profile** — Register and login with your own account, fully private
- **🧠 Onboarding System** — Smart questionnaire to calibrate your Body OS on first launch
- **📊 Real-time System Status** — 7 key body metrics visualized as animated progress bars
- **🫀 Body Wireframe** — Interactive 3D-style body visualization with glowing health nodes
- **📝 Multi-category Logging** — Log nutrition, sleep, fitness, hydration, mental state, and social activity
- **⚡ Quick Log** — One-tap logging for the most common entries
- **🤖 AI Advice** — Personalized recommendations based on your data
- **📈 Evolution Tracking** — Weekly progress chart with milestone system
- **🌍 6 Languages** — English, Italian, Spanish, French, German, Portuguese
- **💾 Local Storage** — All data stored privately on your device, no server needed
- **🎨 Futuristic UI** — Sci-fi aesthetic with particle background, glowing effects, and scanlines

---

## 🚀 Quick Start

### Option 1 — Open directly (no install needed)
```bash
# Just open index.html in your browser
open index.html
```

### Option 2 — Local server (recommended)
```bash
# Using Python
python3 -m http.server 8080

# Using Node.js
npx serve .

# Then open http://localhost:8080
```

---

## 📁 Project Structure

```
soma/
│
├── index.html          # Complete app — single file, zero dependencies
└── README.md           # This file
```

> SOMA is intentionally built as a **single HTML file** — zero dependencies, zero build steps, works offline.

---

## 🐙 How to Upload to GitHub

Follow these steps exactly:

### Step 1 — Create a GitHub account
Go to [github.com](https://github.com) and sign up if you don't have an account.

### Step 2 — Create a new repository
1. Click the **"+"** button (top right) → **"New repository"**
2. Name it: `soma-body-os`
3. Set it to **Public**
4. Check **"Add a README file"** → NO (we have ours)
5. Click **"Create repository"**

### Step 3 — Install Git (if you don't have it)
```bash
# macOS
brew install git

# Windows — download from https://git-scm.com

# Linux
sudo apt install git
```

### Step 4 — Configure Git
```bash
git config --global user.name "Your Name"
git config --global user.email "your@email.com"
```

### Step 5 — Upload SOMA
```bash
# Navigate to your soma folder
cd path/to/soma

# Initialize git
git init

# Add all files
git add .

# First commit
git commit -m "🧬 Initial commit — SOMA Body OS v2.4.1"

# Connect to your GitHub repo (replace YOUR_USERNAME)
git remote add origin https://github.com/YOUR_USERNAME/soma-body-os.git

# Push to GitHub
git branch -M main
git push -u origin main
```

### Step 6 — Enable GitHub Pages (make it live online, FREE)
1. Go to your repo on GitHub
2. Click **Settings** tab
3. Scroll to **"Pages"** (left sidebar)
4. Under **"Source"** → select **"Deploy from a branch"**
5. Branch: **main** / Folder: **/ (root)**
6. Click **Save**
7. Wait 2-3 minutes → your app is live at:
   `https://YOUR_USERNAME.github.io/soma-body-os`

---

## 🎮 How to Use SOMA

### First Launch
1. Click **REGISTER**
2. Enter your name, email, password, and choose your language
3. Complete the **4-step onboarding** questionnaire (physical profile, lifestyle, habits, goals)
4. Your Body OS is now calibrated!

### Daily Use
- **Dashboard** — Overview of all your body systems
- **Log tab** — Add daily entries (food, sleep, workouts, water, mood)
- **Quick Log** (right panel) — One-tap for most common entries
- **Advice tab** — AI-generated recommendations
- **Evolution tab** — Weekly progress and milestones

### Logging Example
1. Go to **LOG** tab
2. Select category (e.g., **SLEEP**)
3. Enter hours slept → **ADD ENTRY**
4. Watch your body metrics update in real-time!

---

## 🛠 Tech Stack

| Technology | Purpose |
|---|---|
| HTML5 / CSS3 | Structure & styling |
| Vanilla JavaScript | Logic & interactivity |
| Canvas API | Body wireframe & particle background |
| LocalStorage | Private data persistence |
| Google Fonts (Orbitron + Space Mono) | Futuristic typography |

**Zero frameworks. Zero dependencies. Zero cost.**

---

## 🌍 Supported Languages

| Language | Code |
|---|---|
| 🇬🇧 English | `en` |
| 🇮🇹 Italiano | `it` |
| 🇪🇸 Español | `es` |
| 🇫🇷 Français | `fr` |
| 🇩🇪 Deutsch | `de` |
| 🇧🇷 Português | `pt` |

---

## 🔮 Roadmap

- [ ] Data export (JSON / CSV)
- [ ] Charts with historical data (Chart.js)
- [ ] Real AI integration (OpenAI API)
- [ ] PWA support (installable on mobile)
- [ ] Dark/Light theme toggle
- [ ] Wearable device sync
- [ ] Three.js 3D body model

---

## 📄 License

MIT — free to use, modify, and distribute.

---

<div align="center">
  <strong>SOMA — Know your body. Optimize your life.</strong><br>
  Built with ❤️ and zero dependencies
</div>
