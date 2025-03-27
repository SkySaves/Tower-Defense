# 🔫 Tower Defense Game - Enhanced

A modern, customizable tower defense game built with vanilla JavaScript, HTML5 Canvas, and CSS. Packed with features like multiple tower types, enemy variants, sound effects, map editing, and rich UI feedback.

## 🎮 Features

- **6 Unique Towers**: Cannon, Laser, Frost, Sniper, Fire, Chain Lightning — each with upgrade paths and custom abilities.
- **7 Enemy Types**: Including shielded units, flying enemies, teleporters, and a massive boss.
- **Two Branching Paths**: Enemies can spawn and travel along different map routes.
- **Power-Ups**: Collect bonuses like coin boosts mid-game.
- **Responsive UI**: Live coin, round, and health displays. Upgrade and sell options for each tower.
- **Audio Integration**: Background music, attack, upgrade, and explosion sounds.
- **Map Editor Mode**: Toggle tile terrain to design your own paths and strategies.
- **Game Over & Restart**: View final round, high score, and restart at any time.
- **Visual Effects**: On tower placement, upgrades, damage, explosions, and more.

## 🧱 Technologies

- Vanilla **JavaScript**
- **HTML5 Canvas** for rendering
- **CSS** with custom fonts and animations
- Local storage used to track **high scores**

## 🧪 How to Play

1. Clone this repo or open the `index.html` in your browser.
2. Use the UI to select and place towers on grass tiles.
3. Press "Start Round" to begin the wave.
4. Upgrade or sell towers strategically during gameplay.
5. Survive as many rounds as you can!

## ⚙️ Controls

| Button           | Function                             |
|------------------|--------------------------------------|
| **Start Round**  | Launch the next wave of enemies      |
| **Pause**        | Pause or resume the game             |
| **Fast Forward** | Speeds up gameplay                   |
| **Map Editor**   | Enter terrain editing mode           |
| **Upgrade**      | Boost tower stats (if enough coins)  |
| **Sell**         | Remove tower and gain partial refund |

## 🗺️ Map Editor

- Toggle tiles between grass and path by clicking while in Map Editor mode.
- Exiting the editor regenerates the map procedurally.

## 📦 Assets

All sound effects and background music are loaded from the `assets/audio/` directory.

## 📈 High Score

Your best round is saved using browser local storage and shown after game over.

## 🚀 Future Enhancements

- More tower upgrade levels and types
- Advanced enemy AI with buffs/debuffs
- Mobile support & improved responsive layout
- Leaderboard or save/load features

## 🛠️ Setup

No installation needed. Simply clone and open:

```bash
git clone https://github.com/your-username/tower-defense-game.git
cd tower-defense-game
open index.html
