# 🃏 Crimson Fate

> A dark pixel-art roguelike deckbuilder built in Unity.

![Unity](https://img.shields.io/badge/Unity-6000.3.18f1-black?logo=unity)
![Language](https://img.shields.io/badge/Language-C%23-purple?logo=csharp)
![Status](https://img.shields.io/badge/Status-In%20Development-yellow)
![License](https://img.shields.io/badge/License-MIT-green)

---

## 🎮 About the Game

**Crimson Fate** is a card-based roguelike deckbuilder where you fight your way through procedurally generated dungeon encounters using a strategic deck of cards. Build your deck, survive each floor, and defeat the boss to claim victory.

Inspired by games like *Slay the Spire* and *Monster Train*.

---

## ✨ Features

- 🃏 **Deck-building system** — start with a basic deck and add powerful cards after each fight
- ⚔️ **15 unique cards** — Attack, Defense, and Magic/Power cards
- 👾 **Pixel art enemies** — Goblin, Skeleton, Orc, Vampire, and Dragon Boss
- 🌲 **Floor-based backgrounds** — visuals change as you descend deeper
- 🎵 **8-bit chiptune soundtrack** — original dungeon music for every situation
- 💥 **Visual effects** — screen shake, damage numbers, card glow effects
- 🔍 **Right-click card inspect** — read full card details mid-combat
- 💾 **Save & Load system** — continue your run anytime

---

## 🃏 Card List

### ⚔️ Attack Cards
| Card | Effect |
|---|---|
| Strike | Deal 6 damage |
| Heavy Blow | Deal 12 damage |
| Twin Strike | Deal 4 damage twice |
| Cleave | Deal 8 damage to ALL enemies |
| Piercing Stab | Deal 8 damage, ignores shield |

### 🛡️ Defense Cards
| Card | Effect |
|---|---|
| Defend | Gain 5 shield |
| Iron Wall | Gain 12 shield |
| Dual Guard | Gain 4 shield, draw 1 card |
| Fortify | Gain 8 shield, gain 2 strength |

### ✨ Magic / Power Cards
| Card | Effect |
|---|---|
| Fireball | Deal 10 damage, apply 2 Burn |
| Ritual Rune | Gain 3 Strength permanently |
| Weaken | Apply 3 Weak to enemy |
| Exploit | Apply 3 Vulnerable to enemy |
| Berserk | Deal 15 damage, take 3 damage |
| Quick Draw | Draw 3 cards |

---

## 👾 Enemies

| Enemy | Floor | Special |
|---|---|---|
| Goblin | 1–2 | Fast, applies Weak |
| Skeleton | 1–3 | Gains shield every turn |
| Orc | 2–4 | High damage attacks |
| Vampire | 3–5 | Heals on attack |
| Dragon 🐉 | Boss | Burns, high damage, multi-attack |

---

## 🎮 How to Play

1. **Start a New Run** — begin with a starter deck of 10 cards
2. **Fight enemies** — play cards each turn using your energy (3 per turn)
3. **Choose rewards** — pick a new card after every fight
4. **Survive 3 floors** — each floor ends with a boss fight
5. **Win** — defeat the Dragon to claim victory!

### Controls
| Input | Action |
|---|---|
| Left Click card | Play the card |
| Right Click card | Inspect card details |
| Enter | End your turn |

---

## 🛠️ Built With

- **Unity 6** (6000.3.18f1 LTS)
- **C#**
- **TextMeshPro** — UI text rendering
- **DOTween** — animations and tweening
- **Unity Audio System** — music and SFX

---

## 📁 Project Structure

```
Assets/
├── Scenes/
│   ├── MainMenu
│   ├── CombatScene
│   ├── RewardScene
│   ├── GameOverScene
│   └── VictoryScene
├── Scripts/
│   ├── Core/         → GameManager
│   ├── Combat/       → CombatManager
│   ├── Cards/        → CardUI, CardData, CardDatabase
│   ├── Enemies/      → EnemyInstance, EnemyData
│   ├── UI/           → HUD, Overlays, Effects
│   └── Audio/        → AudioManager
├── Prefabs/
├── Resources/
│   ├── Cards/        → CardData ScriptableObjects
│   ├── Enemies/      → EnemyData ScriptableObjects
│   └── Audio/        → Music and SFX files
└── Sprites/
    ├── Enemies/
    ├── Cards/
    └── UI/
```

---

## 🚀 Getting Started

### Prerequisites
- Unity Hub installed
- Unity 6 (6000.3.18f1 LTS) installed
- DOTween (free) imported

### Installation
```bash
# Clone the repository
git clone https://github.com/YOUR_USERNAME/crimson-fate.git

# Open in Unity Hub
# File → Open Project → select the cloned folder
```

### Running the Game
1. Open the project in Unity
2. Go to `Assets/Scenes/MainMenu`
3. Press **Play** in the Unity Editor

---

## 🗺️ Roadmap

- [x] Core combat system
- [x] Deck building
- [x] Save & Load
- [x] Screen shake & visual effects
- [x] Card inspect overlay
- [ ] More card variety (20+ cards)
- [ ] More enemy types
- [ ] Relics / passive items system
- [ ] Sound effects
- [ ] WebGL browser build
- [ ] Leaderboard

---

## 📸 Screenshots

> *(Add your screenshots here once the game is built)*

---

## 👤 Author

**Your Name**
- GitHub: [@YOUR_USERNAME](https://github.com/TakamoriSubaru)
- itch.io: [your-itch-page](https://takamorisubaru.itch.io/crimson-fate)

---

## 📄 License

This project is licensed under the MIT License.

---

## 🙏 Credits

- Music: *(your music credits here)*
- SFX: freesound.org contributors
- Pixel art: *(your art credits here)*
- Font: Cinzel — Google Fonts
