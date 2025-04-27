
# Game Plan

A simple **team management** web application built for Football Clubs.

---

## 🌟 Main Features

- **Authentication**  
  - Player and Coach can sign up and log in using **Firebase Authentication**.

- **Coach Dashboard**  
  - Coach can create **new match polls** (date, time, opponent, and tournament link).
  - View list of **all upcoming matches**.

- **Player Dashboard**  
  - Players can see **upcoming matches**.
  - Players can submit their **availability** (In / Out / Injured) for each match.

- **Match Polls**
  - Coaches create match events.
  - Players respond with their availability.
  - Coaches can track responses easily.

---

## 💂️ Project Structure

```
Game_Plan/
├── public/
│   └── index.html
├── src/
│   ├── assets/
│   ├── components/
│   │   ├── MatchPoll.vue        # Form for players to submit In/Out/Injured
│   │   ├── MatchList.vue         # List of upcoming matches
│   │   └── Navbar.vue            # Navigation bar
│   ├── views/
│   │   ├── Login.vue             # Login page
│   │   ├── CoachDashboard.vue    # Coach’s dashboard page
│   │   ├── PlayerDashboard.vue   # Player’s dashboard page
│   │   └── CreatePoll.vue        # Coach creates match/tournament poll
│   ├── router/
│   │   └── index.js              # Routes (Coach/Player dashboards, Login)
│   ├── store/
│   │   └── index.js              # Vuex store for managing login state, polls
│   ├── firebase-config.js        # Firebase setup file
│   ├── App.vue
│   ├── main.js
├── package.json
├── README.md
└── vue.config.js
```

---

## ⚙️ Tech Stack

- **Vue 3** (Frontend Framework)
- **Firebase** (Authentication and Database)
- **Vue Router** (Page Navigation)
- **Vuex** (State Management)

---

## 📆 Development Timeline

| Week | Focus |
|-----|------|
| Week 1 | Setup, Authentication basics (~23 hours) |
| Week 2 | Dashboards and Polls (~28 hours) |
| Week 3 | Testing, UI Polishing (~28 hours) |
| Week 4 | Documentation, Presentation (~9 hours) |

**Total Development Time:** ~88 hours

---

## 📌 Future Improvements

- Add **real-time chat** between players and coaches.
- Push **notifications** for new polls and changes.
- Performance statistics tracking for players.

---

## 🚀 Getting Started

1. Clone the repository
   ```
   git clone https://github.com/MajeedBabatundeNITS22K/inter_kokkola_booking_system.git
   ```

2. Install dependencies
   ```
   npm install
   ```

3. Run the application
   ```
   npm run serve
   ```

4. Open in browser
   ```
   http://localhost:8080
   ```

---

✅ Project supervised under **Capstone 2025** course, Central University of Applied Sciences.

# Developer

- Majeed Babatunde

