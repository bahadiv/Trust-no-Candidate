# 🏛️ Trust No Candidate

> *"Everyone is a candidate. No one can be trusted."*

**Trust No Candidate** is a real-time multiplayer political social deduction game supporting up to 11 players. Each player starts with a secret ideology card and must survive through agenda voting, lobbying mechanics, and political pressure.

---

## 🎮 About the Game

Inspired by Town of Salem but built on entirely original mechanics, Trust No Candidate brings real political dynamics into a game format. Players hide their ideologies while voting on agendas, forming alliances, defending against lobbyists, and trying to survive before their public pressure reaches 100.

### Core Mechanics

- **11 Unique Ideologies** — Communist, Liberal, Fascist, Anarchist, Technocrat and more
- **9 Political Axes** — Democratic/Authoritarian, Secular/Religious, Globalist/Isolationist, etc.
- **100+ Agendas** — A different political issue is voted on each round
- **Public Pressure System** — The candidate whose pressure reaches 100 is eliminated
- **Lobbyist Mechanic** — Eliminated players receive lobby cards and continue influencing the game
- **Power Cards** — Immunity, Provocation, Propaganda and more

### Lobby System
Every eliminated player receives a lobby card matching their ideology:

| Lobbyists | Lobby Name | Power |
|---|---|---|
| 1–2 | Small Interest Group | 5 pts/vote |
| 3–4 | Political Elite Lobby | 5 pts/vote |
| 5+ | Deep State | 5 pts/vote |

Lobbyists vote each round to apply pressure on active candidates. If they coordinate, they can eliminate anyone. If they split, their impact is reduced — creating a strategic layer that keeps eliminated players engaged until the very end.

---

## 🛠️ Tech Stack

### Current (HTML Version)
- Vanilla HTML / CSS / JavaScript
- Single file, runs in browser
- Local multiplayer (hot-seat mode)

### In Development (Online Version)
- **Frontend:** HTML/CSS/JavaScript + Pixel Art (Pixellab)
- **Backend:** Node.js + Socket.io
- **Voice Communication:** WebRTC
- **Desktop App:** Electron
- **Map:** Isometric parliament design (Pixel Art)

---

## 🎨 Design

The game takes place on an isometric pixel art parliament map. 11 player avatars stand around a circular floor divided into equal segments, with a speech podium at the center and a packed spectator gallery in the upper balcony.

---

## 📁 Project Structure

```
trust-no-candidate/
├── game_coalition.html        # Main game file (HTML version)
├── game_coalition_old.html    # Previous version (archived)
├── online/                    # Online version (in development)
│   ├── server/                # Node.js + Socket.io
│   ├── client/                # Frontend
│   └── assets/                # Pixel art assets
└── docs/                      # Design notes and changelogs
```

---

## 🚀 How to Play

### HTML Version
1. Open `game_coalition.html` in your browser
2. Select number of players (min 6, max 11)
3. Distribute cards, keep ideologies secret
4. Vote on agendas, manage lobbyists, survive

### Online Version (Coming Soon)
```bash
cd online/server
npm install
node server.js
```

---

## 📊 Development Process

This project was built using **vibecoding** — an AI-assisted development approach using tools like Claude Code, Lovable, and Pixellab. Game mechanics, ideology balance, and user experience were shaped through iterative playtesting with real players.

---

## 📅 Roadmap

- [x] HTML prototype
- [x] Core game mechanics (agendas, public pressure, power cards)
- [x] Lobbyist system design
- [x] Pixel art map concept
- [ ] Online multiplayer (Node.js + Socket.io)
- [ ] Voice communication (WebRTC)
- [ ] Electron desktop app
- [ ] Character avatars (Pixel Art)
- [ ] iOS / Android release

---

## 👤 Developer

**Bahadır Demir**  
Marmara University — Political Science & International Relations  
[bahadiv@gmail.com](mailto:bahadiv@gmail.com)

---

*This repository is private. Unauthorized copying or distribution is prohibited.*
