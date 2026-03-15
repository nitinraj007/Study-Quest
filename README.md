# 🔐 StudyQuest — Gamified Life & Study Tracker

> Built by a cybersecurity student who was juggling too many things at once and needed a system — so I built one.

![StudyQuest Banner](https://img.shields.io/badge/StudyQuest-Live-C8FF00?style=for-the-badge&labelColor=0E0E0E)
![JavaScript](https://img.shields.io/badge/JavaScript-Pure%20JS-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![Firebase](https://img.shields.io/badge/Firebase-Firestore-FFCA28?style=for-the-badge&logo=firebase&logoColor=black)
![Status](https://img.shields.io/badge/Status-Active%20%26%20In%20Use-00FF88?style=for-the-badge)

---

## 🎯 What is StudyQuest?

StudyQuest is a **personal gamified dashboard** that helps me track everything I'm working on — academics, cybersecurity learning, content creation, my dev agency (Delvrixo Studios), and GitHub/LinkedIn growth — all in one place with XP, levels, and rewards.

The problem I had: everything was happening but nothing was being tracked. Tasks slipped. Priorities blurred. Momentum died.

So I did what any cybersecurity student would do — I identified the vulnerability in my own system and patched it. 🔒

---

## ✨ Features

| Feature | Description |
|---|---|
| 📅 **Daily Task Board** | Time-blocked tasks for every day of the week |
| ♾️ **Lifetime Navigation** | Prev/Next week arrows — go to any date, forever |
| 🗓️ **Mini Calendar** | Click any day of any month to jump to it |
| ⚡ **XP System** | Earn XP for every task you complete |
| 🎮 **Coins & Emeralds** | Dual currency with 15% random emerald drop |
| 🏆 **Level Progression** | 8 levels from Beginner → Legend |
| 🔥 **Streak Tracker** | Daily & weekly streak system |
| 🛍️ **Reward Shop** | Spend earned coins & emeralds on items |
| 🔗 **Firebase Real-Time Sync** | One sync code — works across all your devices |
| ➕ **Custom Tasks** | Add one-time or weekly repeating tasks |
| 📥 **Offline Fallback** | Saves locally if internet drops, re-syncs when back |
| 🎊 **Animations** | Confetti bursts, float animations, level-up overlay |

---

## 🛠️ Tech Stack

```
Frontend   → Pure HTML + CSS + JavaScript (zero frameworks)
Backend    → Firebase Firestore (real-time NoSQL database)
Auth       → Code-based sync system (no login required)
Hosting    → Single HTML file — open locally or host anywhere
```

---

## 🚀 How to Use

### Option 1 — Run locally
1. Download `StudyQuest.html`
2. Open it in any browser
3. Choose **"New Account"** → save your 8-character sync code
4. Start ticking tasks and earning XP

### Option 2 — Cross-device sync
1. Open on your main device → save your sync code
2. Open on any other device (phone, laptop, etc.)
3. Choose **"I have a code"** → enter your code
4. Everything syncs in real-time via Firebase ✅

### Firebase Setup (one-time, 2 minutes)
To enable sync, go to your Firebase Console → Firestore → Rules and set:

```
rules_version = '2';
service cloud.firestore {
  match /databases/{database}/documents {
    match /users/{syncCode} {
      allow read, write: if true;
    }
  }
}
```

---

## 📊 My 5 Domains Tracked

```
📚 Academics    →  DS, OOP, DBMS, Discrete Math, Web Dev
🛡️ Cybersecurity →  TryHackMe, OverTheWire, HackTheBox, CTFs
🎬 Content      →  Trendhive Academy (Hindi + English YouTube)
🏢 Delvrixo     →  My dev agency — MVPs, SaaS, client work
🚀 Growth       →  LinkedIn, GitHub tools, Instagram
```

---

## 🎮 Level System

| Level | Name | XP Required |
|---|---|---|
| 1 | Beginner 🧑‍💻 | 0 |
| 2 | Student 📚 | 250 |
| 3 | Hacker 🛡️ | 500 |
| 4 | Builder ⚙️ | 1,000 |
| 5 | Creator 🎬 | 2,000 |
| 6 | Founder 🏢 | 4,000 |
| 7 | Elite 🚀 | 8,000 |
| 8 | Legend 👑 | — |

---

## 🏗️ Project Structure

```
StudyQuest.html          ← Entire app (HTML + CSS + JS in one file)
```

That's it. No node_modules. No build process. No dependencies to install. Just open and use.

---

## 💡 Why I Built This

I'm a **Cybersecurity student** managing:
- 🎓 Full college workload
- 🔐 TryHackMe → HackTheBox → CTF roadmap
- 📹 Two YouTube channels (Trendhive Academy)
- 🏢 Delvrixo Studios — my own dev agency
- 🌐 LinkedIn + GitHub presence

Standard to-do apps weren't cutting it. I needed something that tracked every domain, rewarded consistency, and synced across my phone and laptop.

So I built it in a single HTML file using Firebase for the backend. No frameworks. No tutorials. Just problem-solving — which is exactly what cybersecurity trains you to do.

---

## 🔮 Roadmap

- [ ] Mobile responsive layout
- [ ] Push notifications for task reminders  
- [ ] Weekly analytics / progress report
- [ ] Import/export full data as JSON
- [ ] Multiple profiles per sync code (team mode for Delvrixo Syndicate)
- [ ] Dark/light theme toggle

---

## 👤 About Me

**Nitin Raj** — Cybersecurity Student | Content Creator | Founder @ Delvrixo Studios

- 🔐 Learning: TryHackMe → HackTheBox → CTF competitions
- 📹 YouTube: [Trend Hive Academy](https://www.youtube.com/@TrendHiveAcademy)
- 🏢 Agency: [Delvrixo Studios](#)
- 💼 LinkedIn: [Nitin Raj](https://www.linkedin.com/in/nitin-raj-451ba5314/)

---

## 📄 License

MIT License — use it, fork it, build on it. Just give credit. 🤝

---

<div align="center">

**Built with 🔥 by a cybersecurity student who refuses to let anything fall through the cracks.**

⭐ Star this repo if it helped you | 🍴 Fork it and make it yours

</div>
