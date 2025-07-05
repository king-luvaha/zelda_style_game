# 🧝 Zelda-Inspired Pygame Adventure

🎮 A top-down action RPG game built using [Pygame](https://www.pygame.org/). This game features player combat, magic, a level system, enemies, particles, weapon switching, stat upgrades, and a dynamic camera system — inspired by classic Zelda games.

---

## 📸 Screenshots

> _You can add your screenshots here once available._  
> Example:

```bash
assets/screenshots/intro.png
assets/screenshots/combat.png
assets/screenshots/upgrades.png
````

---

## 🚀 Features

- 🧝 Player movement, combat, and magic (heal + flame)
- 🔁 Weapon and magic switching system
- 🧟 Enemy AI and health/damage system
- 🌱 Grass and object tile destruction with particle effects
- 🧠 Experience and stat upgrades via in-game menu
- 🎥 Smooth Y-axis camera and depth-sorted rendering
- 🎵 Background music and sound effects
- 🛡️ Collision system using hitboxes
- 🗺️ Tilemap system powered by CSV and spritesheets

---

## 📁 Folder Structure

```bash
zelda_style_game/
├── assets/
│   ├── audio/
│   ├── graphics/
│   └── map/
├── debug.py
├── enemy.py
├── entity.py
├── level.py
├── magic.py
├── main.py
├── particles.py
├── player.py
├── settings.py
├── support.py
├── tile.py
├── ui.py
├── upgrade.py
├── weapon.py
└── README.md
```

---

## 🛠️ Setup Instructions

### ✅ Prerequisites

Ensure you have **Python 3.7+** installed. Then install `pygame`:

```bash
pip install pygame
```

---

### 💻 Running the Game

1. Clone the repository:

```bash
git clone https://github.com/king-luvaha/zelda_style_game.git
cd zelda_style_game
```

2. Run the game:

```bash
python main.py
```

3. Use these controls:

|Key|Action|
|---|---|
|Arrow Keys|Move|
|`SPACE`|Attack|
|`Left Ctrl`|Use Magic|
|`Q`|Switch Weapon|
|`E`|Switch Magic|
|`M`|Toggle Upgrade Menu|

---

## 🧠 Tech Stack

- 🐍 Python 3.10
- 🎮 Pygame 2.0+
- 🖼️ Tiled-style map layout with CSV
- 🎨 Custom sprite animations and particle effects

---

## 🎯 Future Improvements

- Enemy wave spawns
- Level progression system
- Boss battles
- Save/load functionality
- Quest and inventory system

---

## 📝 License

MIT License. See `LICENSE` file for more info.

---

## 🙌 Credits

- Sound effects and music: [OpenGameArt](https://opengameart.org/)
- Sprites and tiles: Custom / Modified from public domain packs
- Inspired by: _Zelda_, _Hyper Light Drifter_, and [Clear Code's Pygame Tutorials](https://www.youtube.com/c/ClearCode)
