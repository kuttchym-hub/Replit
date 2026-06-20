# ⚡ QUICK START GUIDE - Android Development
## 5-Minute Setup for Android Developers

---

## 📱 INSTALL THESE 3 APPS

1. **Termux** (F-Droid or Google Play) - Terminal
2. **Acode** (Google Play) - Code Editor
3. **Firefox Mobile** (Google Play) - Browser for Testing

---

## ⏱️ 5-MINUTE SETUP

### In Termux (1 minute):
```bash
apt update && apt install git curl nodejs npm python
git clone https://github.com/kuttchym-hub/Replit.git
cd Replit
```

### Copy Website Files (2 minutes):
Create these files in **Acode**:

**File 1: `website/index.html`** - [Full content in ANDROID_SETUP_GUIDE.md](ANDROID_SETUP_GUIDE.md#step-2-create-html-file)

**File 2: `website/css/style.css`** - [Full content in ANDROID_SETUP_GUIDE.md](ANDROID_SETUP_GUIDE.md#step-3-create-css-file)

**File 3: `website/js/script.js`** - [Full content in ANDROID_SETUP_GUIDE.md](ANDROID_SETUP_GUIDE.md#step-4-create-javascript-file)

### Run & Test (2 minutes):

In **Termux**:
```bash
cd website
python -m http.server 8000
```

In **Firefox Mobile**:
- Visit: `localhost:8000`
- See your website! 🎉

---

## 🔥 COMMON COMMANDS

```bash
# Start website
python -m http.server 8000

# Start Node.js API
node server.js

# Start Python Flask
python app.py

# Stop any server
Ctrl + C

# Save to GitHub
git add .
git commit -m "Your message"
git push origin main

# Check what changed
git status
```

---

## 📂 PROJECT STRUCTURE

```
Replit/
├── website/               ← Your first website
│   ├── index.html
│   ├── css/style.css
│   └── js/script.js
├── api/                   ← Node.js API
│   ├── server.js
│   └── package.json
├── python-app/            ← Python Flask
│   └── app.py
├── ANDROID_SETUP_GUIDE.md ← Full guide
└── QUICK_START.md         ← This file
```

---

## 🌐 TEST URLS

After starting each server, visit:

| Project | Command | Test URL |
|---------|---------|----------|
| Website | `python -m http.server 8000` | `http://localhost:8000` |
| API | `node server.js` | `http://localhost:3000/api/info` |
| Python | `python app.py` | `http://localhost:5000` |

---

## ❓ QUICK TROUBLESHOOTING

| Problem | Solution |
|---------|----------|
| "command not found" | `apt install [package-name]` |
| Can't access localhost | Ensure server is running in Termux |
| Port in use | Use different port: `python -m http.server 9000` |
| Firefox won't load | Try `127.0.0.1:8000` instead |
| Need to stop server | Press `Ctrl + C` in Termux |

---

## 📖 FULL GUIDE

For detailed instructions: [→ Read ANDROID_SETUP_GUIDE.md](ANDROID_SETUP_GUIDE.md)

---

## 🚀 NEXT: Git & GitHub

```bash
# Check changes
git status

# Add all files
git add .

# Create commit
git commit -m "Initial website and API"

# Upload to GitHub
git push origin main
```

**View on GitHub:** https://github.com/kuttchym-hub/Replit

---

**You're ready! Build something awesome! 💪**
