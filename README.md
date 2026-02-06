# NEON SERPENT

### Ultimate Snake Game | Single HTML File | Zero Dependencies

<div align="center">

```
    ███╗   ██╗███████╗ ██████╗ ███╗   ██╗
    ████╗  ██║██╔════╝██╔═══██╗████╗  ██║
    ██╔██╗ ██║█████╗  ██║   ██║██╔██╗ ██║
    ██║╚██╗██║██╔══╝  ██║   ██║██║╚██╗██║
    ██║ ╚████║███████╗╚██████╔╝██║ ╚████║
    ╚═╝  ╚═══╝╚══════╝ ╚═════╝ ╚═╝  ╚═══╝
    ███████╗███████╗██████╗ ██████╗ ███████╗███╗   ██╗████████╗
    ██╔════╝██╔════╝██╔══██╗██╔══██╗██╔════╝████╗  ██║╚══██╔══╝
    ███████╗█████╗  ██████╔╝██████╔╝█████╗  ██╔██╗ ██║   ██║
    ╚════██║██╔══╝  ██╔══██╗██╔═══╝ ██╔══╝  ██║╚██╗██║   ██║
    ███████║███████╗██║  ██║██║     ███████╗██║ ╚████║   ██║
    ╚══════╝╚══════╝╚═╝  ╚═╝╚═╝     ╚══════╝╚═╝  ╚═══╝   ╚═╝
```

**A cyberpunk neon snake game with procedural audio, multiple game modes, achievements, and stunning visuals.**

**All in a single HTML file. No build tools. No dependencies. Just open and play.**

[Play Now](#how-to-play) | [Features](#features) | [Game Modes](#game-modes) | [Controls](#controls)

</div>

---

## Features

| Feature | Description |
|---------|-------------|
| **4 Game Modes** | Classic, Maze, Time Attack, Endless |
| **Procedural Audio** | Web Audio API synth sounds - eat, death, power-ups, level up, ambient music |
| **6 Power-ups** | Speed, Ghost, Double Points, Magnet, Shield, Freeze |
| **15 Achievements** | Trackable goals with toast notifications |
| **5 Snake Skins** | Neon, Fire, Ice, Galaxy, Matrix |
| **Portals** | Teleportation portals appear at higher levels |
| **Combo System** | Chain food pickups for score multipliers with milestone effects |
| **Poison Food** | Avoid the red danger zones or use Shield to survive |
| **Golden Apple** | Rare spawn - massive points + temporary shield |
| **Local Storage** | High scores, achievements, settings persist between sessions |
| **CRT Effect** | Optional retro scanline overlay |
| **Mobile Support** | Touch swipe controls + D-pad |
| **Zero Dependencies** | Single HTML file, works offline |

## Game Modes

### Classic
The original snake experience. Walls kill. Obstacles appear from level 3+. Portals from level 5+. How far can you go?

### Maze
Navigate through walls and corridors that change with each level. Tight spaces demand precise control.

### Time Attack
90 seconds on the clock. Wrap-around edges (no wall death). Collect as much food as possible before time runs out.

### Endless
No walls - the snake wraps around edges. Speed increases continuously. No level cap. Pure survival.

## Controls

| Key | Action |
|-----|--------|
| `W` `A` `S` `D` / `Arrow Keys` | Move |
| `Space` | Pause / Resume |
| `Escape` | Pause |
| `M` | Toggle music |

**Mobile:** Swipe on the game canvas or use the on-screen D-pad.

## Power-ups

| Icon | Name | Effect | Duration |
|------|------|--------|----------|
| ⚡ | **Speed** | Move 40% faster | 5s |
| 👻 | **Ghost** | Pass through walls and yourself | 6s |
| ×2 | **Double** | Double points | 8s |
| 🧲 | **Magnet** | Food moves toward you | 7s |
| 🛡 | **Shield** | Survive one collision | 10s |
| ❄ | **Freeze** | Slow down time | 6s |

## How to Play

1. **Download** `index.html` (or clone this repo)
2. **Open** the file in any modern browser
3. **Select** a game mode
4. **Play!**

```bash
# Or clone and open
git clone https://github.com/Lukedaca/neon-serpent.git
cd neon-serpent
# Open index.html in your browser
start index.html        # Windows
open index.html         # macOS
xdg-open index.html     # Linux
```

> No server needed. No npm install. No build step. Just a browser.

## Tech Stack

- **HTML5 Canvas** - Game rendering
- **Web Audio API** - Procedural sound synthesis
- **CSS3** - UI, animations, backdrop filters
- **localStorage** - Persistence
- **Vanilla JavaScript** - Zero frameworks

## Browser Support

Works in all modern browsers:
- Chrome / Edge / Brave
- Firefox
- Safari
- Opera

## Settings

Access settings from the main menu:
- **Sound FX** - Toggle on/off
- **Music** - Ambient synth drone
- **Volume** - Master volume control
- **Snake Skin** - 5 color themes
- **CRT Effect** - Retro scanline overlay

## Achievements

15 achievements to unlock:

| Achievement | Requirement |
|-------------|-------------|
| First Blood | Eat your first food |
| Hungry | Eat 50 in one game |
| Starving | Eat 100 in one game |
| Combo x5 | Reach x5 combo |
| Combo King | Reach x10 combo |
| Combo God | Reach x20 combo |
| Speed Demon | Reach level 5 |
| Veteran | Reach level 10 |
| Collector | Collect all 6 power-up types |
| Portal Master | Use portals 5 times |
| Centurion | Score 1000+ |
| Legend | Score 5000+ |
| Survivor | Survive 2 minutes |
| Endurance | Survive 5 minutes |
| Shield Hero | Shield saves you from death |

## Screenshots

*Open `index.html` to see the game in action!*

---

<div align="center">

**Made with Claude Code**

</div>
