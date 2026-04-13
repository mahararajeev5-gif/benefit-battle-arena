# ⚡ Benefit Battle Arena

> 🎮 Real-time multiplayer HR Benefits Game — teams compete to build the best employee benefits package within budget. Admin Panel + Live Leaderboard + Firebase sync, all in a **Single HTML File**.

---

## 🚀 Live Link

| Role | Link |
|------|------|
| 🛠 Admin + 🎮 Player | [mahararajeev5-gif.github.io/benefit-battle-arena](https://mahararajeev5-gif.github.io/benefit-battle-arena/) |

> 💡 **Admin** apne laptop pe link khole aur **Players** ko same link WhatsApp pe bheje — sab ek hi file mein hai!

---

## 🎯 What is This?

**Benefit Battle Arena** is an interactive game designed for corporate HR events. Teams compete against each other to build the best employee benefits package — while staying within a fixed budget and maximizing happiness points!

The admin controls the game, sets the timer, and watches teams compete in real-time on a live leaderboard.

---

## ✨ Features

### 🛠 Admin Panel *(Password Protected)*
- 🔐 Secure login — only admin can access
- ✅ Full Benefit Library Management (Add, Edit, Delete)
- ✅ Event Configuration (Budget, Timer, Max Teams)
- ✅ Start Game / Round Reset / Full Reset controls
- ✅ Live Dashboard — see all teams in real-time
- ✅ Live Leaderboard with rankings
- ✅ Change admin password anytime

### 🎮 Player Game Screen
- ✅ Team Login with waiting screen
- ✅ Game starts only when Admin clicks Start
- ✅ Live Countdown Timer (browser-independent)
- ✅ Budget Bar & Happiness Points Meter
- ✅ Benefits Catalog (categorized)
- ✅ Visual Benefits Grid
- ✅ Remove benefits with instant refund
- ✅ Submit Package when ready

### 🔥 Firebase Powered
- ✅ Real-time sync across all devices
- ✅ Timer runs server-side — no browser dependency
- ✅ Live leaderboard updates instantly
- ✅ Data persists across sessions

---

## 🎮 How to Play

**Admin Side:**
1. Open the link and **triple-click the logo** to open Admin Login
2. Enter password → access Admin Panel
3. Add/Edit benefits in the Benefit Library
4. Set Event Config (Budget, Timer, Max Teams)
5. Click **▶ Start Game**
6. Watch teams on the Live Dashboard

**Player Side:**
1. Open the same link on phone/laptop
2. Enter your Team Name → Join Game
3. Wait for admin to start the game
4. Select benefits from the catalog
5. Stay within budget to submit!
6. Highest Happiness Points wins 🏆

---

## 🔄 Reset Options

| Option | What it does |
|--------|-------------|
| 🔄 Same Teams – New Round | Keeps team names, resets budget & selections for a new round |
| 🗑 Full Reset | Deletes all teams — fresh start with new players |

---

## 🏆 Scoring System

| Rule | Details |
|------|---------|
| Budget | Fixed amount per team |
| Happiness Points | Earned by selecting benefits |
| Win Condition | Highest HP within budget |
| Tie Breaker | Higher remaining budget wins |
| Over Budget | Cannot submit ❌ |

---

## 📦 Tech Stack

| Technology | Purpose |
|-----------|---------|
| HTML5 | Structure & layout |
| CSS3 | Styling & animations |
| Vanilla JavaScript | Game logic |
| Firebase Realtime DB | Real-time data sync via `onValue` listeners |
| Firebase Hosting Config | `databaseURL` + `apiKey` based connection |
| Google Fonts | Typography (Syne + DM Sans) |
| GitHub Pages | Free hosting |

---

## 🗂 Project Structure

```
benefit-battle-arena/
│
├── index.html     → Full game (Admin + Player in one file)
└── README.md      → Documentation
```

---

## 🔥 Firebase Database Structure

```
benefit-builder-default-rtdb
├── 📁 game          → Game state, timer & startedAt timestamp
├── 📁 benefits      → Benefit library
├── 📁 teams         → All team data
└── 📁 adminConfig   → Admin password (hashed)
```

---

## 📸 Sample Benefits

| Benefit | Cost | Happiness Points |
|---------|------|-----------------|
| Medical Cover | $50 | 60 HP |
| Gym Membership | $30 | 30 HP |
| Annual Bonus | $40 | 50 HP |
| Paid Vacation | $20 | 25 HP |
| Insurance Plus | $60 | 70 HP |
| Free Snacks | $10 | 10 HP |
| Mental Health | $35 | 45 HP |
| Stock Options | $55 | 65 HP |

---

## 👨‍💻 Developer

**Rajeev Mahara**
- GitHub: [@mahararajeev5-gif](https://github.com/mahararajeev5-gif)

---

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

---

⚡ Built with AI ❤️ using HTML, CSS, JavaScript & Firebase Realtime Database
