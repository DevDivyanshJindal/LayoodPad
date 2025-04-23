# 🌐 LayoodPad

> The world's simplest yet powerful **realtime note-sharing platform** — built for speed, privacy, and code lovers.

![Banner](https://dummyimage.com/1200x400/000/fff&text=LayoodPad+Note+Sharing+Made+Simple)

---

## 🚀 What is LayoodPad?

**LayoodPad** is a no-frills, high-speed, collaborative text-sharing platform that offers:

- 🔐 **Password protection**
- ⚡ **Instant saving** (every keystroke is saved with debounce)
- 🧠 **Intelligent code mode** for developers
- 🔄 **Real-time updates** using AJAX
- 🖤 **Minimalist dark theme** with Tailwind

Perfect for sharing quick notes, code snippets, and scratchpads — without any bloat.

---

## 🧠 Key Features

| Feature                        | Description                                                                 |
|-------------------------------|-----------------------------------------------------------------------------|
| 🔐 Password Protection        | Secure any note with a passkey                                              |
| ⚡ Instant Auto-Save          | Debounced input saves without refresh                                       |
| 💾 Offline Cache Support      | Reopen your latest notes even without internet                              |
| 🔄 Real-Time Sync (AJAX)      | Notes update live between sessions                                          |
| 🧱 Code Mode                  | Enable monospaced input for dev-style notes                                 |
| 🌑 Dark UI                    | A beautiful iOS-like dark mode, by default                                  |
| ✨ No Word Limits             | Write as much as you want — no paywall, no cuts                             |
| 🔎 Public Note Search (WIP)  | (Upcoming) Explore popular public notes                                     |

---

## ⚙️ Tech Stack

LayoodPad is a full-stack modern web application, architected for speed and simplicity:

### 🧩 Frontend
- **TailwindCSS** — Utility-first styling for pixel-perfect design
- **Vanilla JS + AJAX** — Smooth interaction with backend (no heavy framework)
- **HTMX** (planned) — For lightweight reactive interactions without full SPA overhead

### 🧠 Backend
- **Python + FastAPI** — Blazingly fast async API framework
- **MongoDB** — Flexible, document-based note storage
- **Jinja2** — Lightweight server-side rendering for performance

### 🛡️ Security
- Rate-limiting and abuse tracking
- Password hashing using `passlib`
- IP/domain monitoring (admin only)

### 🛠️ DevOps
- Dockerized for easy deployment
- Offline-first support using `service workers`
- Hosted on **Render / Vercel / Fly.io** (choose your stack)

---

## 📊 Screenshots

| Home Page                      | Note View                          |
|-------------------------------|------------------------------------|
| ![home](https://dummyimage.com/600x400/222/fff&text=LayoodPad+Home) | ![note](https://dummyimage.com/600x400/333/fff&text=Live+Note+View) |

---

## 📦 Folder Structure
```bash
layoodpad/
├── app/                      # FastAPI backend
│   ├── main.py               # Entrypoint
│   ├── models.py             # DB models
│   ├── routes/               # API endpoints
│   └── templates/            # Jinja2 HTML templates
├── static/                   # JS, CSS, assets
├── .env                      # Secrets
├── Dockerfile                # Container setup
└── README.md                 # You're reading it 👋
```

---

## 💬 Why LayoodPad?

LayoodPad was born out of a need for a **frictionless**, **fast**, and **secure** way to share ephemeral notes and code — something that just works.

Unlike Google Docs or Pastebin:
- No login
- No bloat
- No ads
- No trackers

Just you and your pad.

---

## 🧪 Upcoming Features
- 🧵 Threaded discussions per note
- 📜 Note versioning
- 🔗 Shareable note links (w/ view limits)
- 🧑‍💻 Live code collaboration (Monaco editor)
- 🔍 Full-text search

---

## 🧠 Ideal Use Cases
- Sharing TODOs across teams
- Saving quick code fixes
- Bookmarking ideas
- Collaborative drafting

---

## 🙌 Contributing
Pull requests are welcome! If you have suggestions for improvements, open an issue or fork and PR.

---

## 📜 License
MIT License — free for personal and commercial use.

---

## 💎 Created with passion by [You](https://github.com/yourusername)

> "LayoodPad isn't just a tool — it's the minimal notepad your workflow has been missing."

