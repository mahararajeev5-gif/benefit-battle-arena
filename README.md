# ⚡ Benefit Battle Arena

> 🎮 Real-time multiplayer HR Benefits Game where teams compete to build the best employee benefits package within budget. Features Admin Panel, Live Leaderboard, Timer & Firebase Realtime sync — built in a Single HTML File.

![HTML](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![Firebase](https://img.shields.io/badge/Firebase-FFCA28?style=for-the-badge&logo=firebase&logoColor=black)

---

## 🎯 What is This?

**Benefit Battle Arena** is an interactive game designed for **corporate HR events**. Teams compete against each other to build the best employee benefits package — while staying within a fixed budget and maximizing happiness points!

The admin controls the game, sets the timer, and watches teams compete in real-time on a live leaderboard.

---

## ✨ Features

### 🛠 Admin Panel
- ✅ Full Benefit Library Management (Add, Edit, Delete)
- ✅ Event Configuration (Budget, Timer, Max Teams)
- ✅ Start / Reset Game Controls
- ✅ Live Dashboard — see all teams in real-time
- ✅ Live Leaderboard with rankings

### 🎮 Player Game Screen
- ✅ Team Login
- ✅ Waiting Screen before game starts
- ✅ Live Countdown Timer
- ✅ Budget Bar (decreases on selection)
- ✅ Happiness Points Meter
- ✅ Benefits Catalog (categorized)
- ✅ Visual Benefits Grid
- ✅ Remove benefits (instant refund)
- ✅ Submit Package

### 🔥 Firebase Powered
- ✅ Real-time sync across all devices
- ✅ Live leaderboard updates
- ✅ Data persists across sessions
- ✅ Multiple teams on different devices

---

## 🚀 How to Run

### Option 1 — Direct Browser (Easiest)
```
1. Download benefit-builder-firebase.html
2. Double-click the file
3. Opens in your browser — done!
```

### Option 2 — VS Code Live Server
```
1. Open folder in VS Code
2. Install "Live Server" extension
3. Click "Go Live" at bottom right
4. Opens in browser automatically
```

---

## 🎮 How to Play

### Admin Side:
1. Open the file → Go to **Admin Panel**
2. Add/Edit benefits in the **Benefit Library**
3. Set **Event Config** (Budget, Timer, Max Teams)
4. Click **▶ Start Game**
5. Watch teams on the **Live Dashboard**

### Player Side:
1. Open the same file → Go to **Player Screen**
2. Enter your **Team Name** → Join Game
3. Wait for admin to start
4. Select benefits from the catalog
5. Stay within budget to submit!
6. Highest **Happiness Points** wins 🏆

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
| Firebase Realtime DB | Real-time data sync |
| Google Fonts | Typography (Syne + DM Sans) |

---

## 🗂 Project Structure

```
benefit-battle-arena/
│
└── benefit-builder-firebase.html   ← Entire app in ONE file!
    ├── <style>     → All CSS
    ├── <div>       → All HTML
    └── <script>    → All JavaScript + Firebase
```

> 💡 No separate frontend/backend folders needed — Firebase handles the backend!

---

## 🔥 Firebase Setup (Already Done!)

This project uses **Firebase Realtime Database** for:
- Real-time team sync
- Live leaderboard
- Game state management

Database structure:
```
benefit-builder-default-rtdb
├── 📁 game          → Game state & timer
├── 📁 benefits      → Benefit library
└── 📁 teams         → All team data
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

> ⚡ Built with ❤️ using HTML, CSS, JavaScript & Firebase
