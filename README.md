# 🏛️ Trust No Candidate

> *"Everyone is a candidate. No one can be trusted."*

**Trust No Candidate** is a political social deduction party game for **3 to 11 players**. It currently plays as a **hot-seat game** (one phone passed around the table), with an online real-time version in development. Each player starts with a secret ideology card and must survive through agenda voting, coalitions, lobbying, and political pressure — until only one candidate is left standing.

---

## 🎮 About the Game

Built on entirely original mechanics, Trust No Candidate turns real political dynamics into a game of hidden roles, shifting alliances, and betrayal. Players hide their ideologies while voting on agendas, striking coalitions, fending off lobbyists, and trying to keep their public pressure below 100. Stay true to your ideology, read the room, and trust no one.

Available in **4 languages**: English, Turkish, Spanish and French.

### Core Mechanics

- **11 Unique Ideologies** — Socialist, Communist, Anarchist, Liberal, Conservative, Nationalist, Fascist, Technocrat, Radical Theocrat, Activist, Imperialist
- **9 Political Axes** — Democratic/Authoritarian, Globalist/Isolationist, Militarist/Pacifist, Security/Liberty, Equality/Market, Secular/Religious, Traditional/Progressive, Assimilationist/Multicultural, Collectivist/Individualist
- **121 Agendas** — A different political issue is voted on each round, each tied to one of the 9 axes
- **50 Scandals** — Random scandals strike candidates and pile on extra pressure
- **Public Pressure System** — A candidate whose pressure reaches 100 is eliminated
- **Coalition System** — Two players can secretly ally, share pressure, and even win together (see below)
- **Lobbyist Mechanic** — Eliminated players become lobbyists and keep influencing the game from the shadows
- **Power Cards** — Media, Veto, Immunity, Expose, Double Vote, Pardon, Provoke, Propaganda, and the legendary Dictatorship
- **Snake Voting Order** — The voting order reverses each round, so no one is always first or last

### Coalition System

The coalition is the heart of the game. Two players shake hands and agree to vote the same way for one round, sharing the risk:

- **Form** — Offer an alliance on your coalition card; the other player accepts or declines on their turn
- **Two ballots** — In a coalition you cast a shared *coalition vote* (the agreed direction) and your real *secret vote*
- **Loyalty vs. betrayal** — Keep your word and you share the pressure; betray your partner and you save yourself while they burn (but the alliance breaks and others can sense it)
- **Leaving** — You can *abandon* a partner for a new offer, *dissolve* the coalition, or go into *mourning* for a round if your partner is eliminated
- **Coalition victory** — If the last two candidates are coalition partners, they win together

### Lobby System

When a candidate's public pressure hits 100, they're eliminated — but they're not out of the game. They become a **lobbyist** and keep pressuring active candidates from behind the scenes:

- Each lobbyist secretly targets one candidate per round, adding pressure to them
- **Who targets whom is hidden** — lobbyists keep switching targets, so no one can be sure
- If lobbyists coordinate, they can topple a leader; if they split, their impact fades

This keeps eliminated players engaged and dangerous right up to the end.

---

## 🛠️ Tech Stack

### Current (HTML Version)

- Vanilla HTML / CSS / JavaScript
- Single file, runs in any browser
- Local multiplayer (hot-seat mode)
- 4-language localization (EN / TR / ES / FR)

### In Development (Online Version)

- **Frontend:** HTML/CSS/JavaScript + Pixel Art (Pixellab)
- **Backend:** Node.js + Socket.io
- **Voice Communication:** WebRTC
- **Desktop App:** Electron
- **Map:** Isometric parliament design (Pixel Art)

---

## 🎨 Design

The game takes place on an isometric pixel art parliament map. Up to 11 player avatars stand around a circular floor divided into equal segments, with a speech podium at the center and a packed spectator gallery in the upper balcony.

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
2. Select number of players (min 3, max 11)
3. Distribute cards, keep ideologies secret
4. Each round: view your card, propose or answer coalitions, debate the agenda, vote, and watch the pressure
5. Manage lobbyists, betray or stay loyal, and survive until you're the last one standing

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
- [x] Lobbyist system
- [x] Coalition system (offers, betrayal, dissolution, mourning, coalition victory)
- [x] 121 agendas + 50 scandals across 9 axes
- [x] 4-language localization (EN / TR / ES / FR)
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
