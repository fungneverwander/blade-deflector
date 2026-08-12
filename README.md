# ⚡ BLADE DEFLECTOR: Shield Slash Arena

![Blade Deflector Banner](https://img.shields.io/badge/Game-Blade%20Deflector-00f0ff?style=for-the-badge&logo=gamepad)
![HTML5](https://img.shields.io/badge/HTML5-Canvas-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-ES6+-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![CSS3](https://img.shields.io/badge/CSS3-Vanilla%20UI-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![Web Audio](https://img.shields.io/badge/Web%20Audio-Procedural%20SFX-ff6600?style=for-the-badge)
![License](https://img.shields.io/badge/License-MIT-brightgreen?style=for-the-badge)

**BLADE DEFLECTOR** is a high-octane, action-packed top-down arcade arena web game built with pure HTML5 Canvas and Vanilla JavaScript. Deflect enemy bullets, slice through waves of attacking shapes, throw explosive bombs, unlock permanent mythic traits, and battle brutal multi-phase bosses!

---

## 🎮 Playable Character Classes

Choose your combat style from 4 unique playable classes, each with custom weapons, shields, and abilities:

| Class | Appearance | Primary Weapon | Defense & Ability Mechanics |
| :--- | :--- | :--- | :--- |
| **🛡️ Square Knight** | Cyan Square (`#00f0ff`) | **Glowing Energy Blade** (180° Half-Circle Slash Arc) | Hold **Spacebar** to raise a 180° Directional Shield Plate. Deflects incoming bullets! |
| **⚡ Sentinel Guardian** | Golden Square (`#ffe600`) | **Constant 180° Shield** (No Sword) | **Spacebar Tap**: Rocket Ramming Dash (22x speed) that crushes enemies and triggers 360° Shield Damage Bursts! |
| **💥 Shotgun Enforcer** | Crimson Square (`#ff5500`) | **5-Pellet Energy Buckshot** (High Spread) | Hold **Spacebar** to raise a Frontal Riot Shield. Fires Heavy Explosive Slug AOE bursts! |
| **🏹 Archer Ranger** | Emerald Square (`#00ff66`) | **Piercing Energy Arrows** & Recurve Bow Model | Hold **Spacebar** for Greatbow Shield. Releasing shield hurls a **Slow-Moving Thrown Emerald Bomb** (`speed = 7.5`) with a burning fuse trail! |

---

## 🏆 Difficulty Modes

Select your challenge before stepping into the arena:

- 🧪 **TEST Mode**: Unlimited Hearts (`IMMORTAL! 🛡️`). Perfect for trying out builds and classes. (0.0x Score Multiplier)
- 🟢 **Easy Mode**: 7 Hearts | 1.0X Multiplier | 1.0x Enemy Speed | 360° Protective Shield Dome.
- 🟡 **Normal Mode**: 6 Hearts | 1.5X Multiplier | 1.15x Enemy Speed | 180° Directional Shield Arc.
- 🔴 **Hard Mode**: 4 Hearts | 2.5X Multiplier | 1.35x Enemy Speed | 180° Directional Shield Arc.
- 💀 **Impossible Mode**: 1 Heart | 5.0X Multiplier | 1.7x Ultra Speed Enemies | 60° Precision Line Barrier.

---

## 👑 Boss Encounters & Mythic Reward Trait Choices

Every 5 waves features a major boss encounter with unique attack patterns and permanent mythic trait choices:

### 1. 🟣 Wave 5: Hexagon Boss (`PURPLE_BOSS`)
- **Attacks**: Multi-bullet spiral spreads, rotating orbiter satellites, and aggressive charge slams.
- **Reward Choices**:
  - 🌠 **Slash Beam / Heavy Slug**: Fires a center projectile or **Glowing Yellow Heavy Explosive Slug Arrow** (`#ffe600`) that triggers a 145px radial explosion upon impact!
  - ⚡ **Master Speed**: Permanent +40% movement speed boost across all future waves.

### 2. 🌙 Wave 10: Crescent Blade Boss (`CRESCENT_BOSS`)
- **Attacks**: Spinning crescent blade hands, fast blade cuts, and 3-bullet wall-bouncing projectiles.
- **Reward Choices**:
  - ❤️ **Extra Max Heart**: Grants +1 Permanent Max Heart container and fully restores health!
  - 🗡️ **Master Range**: Expands attack range (+70%), arrow speed (+60%), and bomb explosion radius (+50% to 220px)!

### 3. 🔺 Wave 15: Pyromancer Triangle Boss (`TRIANGLE_BOSS`)
- **Attacks**: Emergency perimeter teleports (`🔮 TELEPORT BLINK!`), burning DoT fireballs, and Flame Minion summons.
- **Reward Choices**:
  - 🔥 **Ignition**: All attacks ignite enemies for +6 bonus damage per tick!
  - 🤝 **Minion Pact**: Passively summons ally **Flame Knights** every second to fight by your side!

---

## 👾 Wave 16+ Mini Bosses

Starting at **Wave 16**, mini-bosses of each primary boss archetype begin spawning during regular wave loops:

- 🟣 **Mini Hexagon Boss** (`#bf00ff`, 48px): 3-bullet spread volleys (`MINI VOLLEY!`), multi-hit armor (+600 Score Slay Reward).
- 🌙 **Mini Crescent Boss** (`#00ffaa`, 46px): Rotating crescent blade aura, fast dash slashes (`MINI SLASH!`), multi-hit armor (+750 Score Slay Reward).
- 🔺 **Mini Pyromancer Triangle Boss** (`#ff3300`, 46px): Fireball DoT bursts (`MINI FIREBALL!`), emergency teleports (`MINI BLINK!`), multi-hit armor (+850 Score Slay Reward).

---

## 🛒 Shop & Buff System

Between waves, randomized shop pedestals spawn in the arena allowing players to buy temporary per-wave upgrades:

- ⚡ **Speed Boost**: +35% Movement Speed.
- 🌀 **360° Slash / Arrow Ring**: Converts attacks into an 8-Way 360° Radial Energy Blast or 8-Arrow Ring!
- 🗡️ **Range Upgrade**: Expands attack sweep reach and projectile speeds.

---

## ⌨️ Controls

- 🖱️ **Mouse**: Aim weapon & directional shield.
- ⌨️ **Spacebar**:
  - **Tap**: Attack (Slash / Dash / Buckshot / Arrow Shot).
  - **Hold**: Raise Directional Shield.
  - **Release (Archer)**: Launch Slow-Moving Thrown Emerald Bomb toward cursor destination!
- ⏸️ **P / ESC**: Pause Game & open options menu.
- 🔊 **Mute Button (Top Right)**: Toggle sound FX on/off.

---

## 🚀 How to Run Locally

No build tools, bundlers, or package installations are required!

1. Clone or download this repository:
   ```bash
   git clone https://github.com/your-username/blade-deflector.git
   ```
2. Open `index.html` directly in any modern web browser (Chrome, Firefox, Edge, Safari):
   ```bash
   # On Windows
   start index.html

   # On macOS
   open index.html
   ```

---

## 🛠️ Technology Stack

- **HTML5 Canvas**: Hardware-accelerated 60fps rendering pipeline.
- **Vanilla JavaScript (ES6+)**: Zero external frameworks or libraries.
- **Vanilla CSS3**: Modern glassmorphism UI, glowing neon aesthetic, CSS grid flex layouts.
- **Web Audio API**: Procedural, zero-dependency sound FX engine.

---

## 📜 License

Distributed under the **MIT License**. See `LICENSE` for more information.
