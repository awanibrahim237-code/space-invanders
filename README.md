# 👾 Space Invaders — Muhammad Ibrahim

A fully playable **Space Invaders** game built with pure **JavaScript OOP** and HTML5 Canvas.
No frameworks. No libraries. Just clean Object-Oriented code.

---

## 🎮 How to Play

- **Arrow Keys / A D** — Move spaceship left and right
- **SPACE** — Shoot bullets
- **Mobile** — Use the on-screen LEFT / FIRE / RIGHT buttons
- Survive all **3 waves** of aliens to win

---

## 🚀 How to Run

1. Download or clone this repository
2. Open **index.html** in any browser
3. Press **SPACE** or tap **START** — that's it

No terminal. No npm. No setup needed.

---

## 🧱 OOP Classes Used

| # | Class | Purpose |
|---|-------|---------|
| 1 | `Vector2` | 2D math helper — stores x and y position |
| 2 | `GameObject` | Base class — gives collision detection to all objects |
| 3 | `Bullet` | Projectile fired by player or enemy |
| 4 | `Player` | Hero spaceship — movement, lives, shooting |
| 5 | `Enemy` | Alien fighter — 3 types (Crab, Squid, Bug) |
| 6 | `EnemySwarm` | Manages the alien grid, movement and direction |
| 7 | `Star` | Single scrolling background star |
| 8 | `Explosion` | Particle burst when something is destroyed |
| 9 | `GameEngine` | Master game loop — owns and controls everything |

---

## 👾 Enemy Types & Points

| Enemy | Points | Description |
|-------|--------|-------------|
| 🦀 Crab | 30 pts | Largest alien — top row — orange |
| 🦑 Squid | 20 pts | Medium alien — middle rows — purple |
| 🐛 Bug | 10 pts | Smallest alien — bottom rows — green |

---

## ⚙️ OOP Principles Applied

- **Encapsulation** — Each class owns its own data and behaviour
- **Inheritance** — Bullet, Player and Enemy all extend GameObject
- **Abstraction** — GameEngine calls simple methods without knowing internals
- **Polymorphism** — draw() works differently on each class

---

## 📁 Project Structure

```
space-invaders/
│
├── spaceinvander.html        ← Full game (HTML + CSS + JavaScript in one file)
├── README.md         ← This file
└── LICENSE           ← MIT License
```

---

## 🙏 Special Thanks

A very special thank you to **Sir Fahad Qureshi** for being an outstanding teacher.

- His **clear explanations** made OOP concepts easy to understand
- He taught not just code but how to **think like a developer**
- Every class in this project — inheritance, encapsulation, polymorphism — was learned under his guidance
- This project would not exist without his support and dedication

> *"The best teacher is the one who makes you believe you can build anything."*
> — Thank you Sir Fahad Qureshi

---

## 👨‍💻 Developer

**Muhammad Ibrahim**
Built with JavaScript · HTML5 Canvas · OOP Architecture

---

## 📄 License

This project is open source under the [MIT License](LICENSE).
