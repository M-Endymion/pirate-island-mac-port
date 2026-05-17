<div align="center">
  <img src="https://raw.githubusercontent.com/M-Endymion/pirate-island-mac-port/main/thumbnail-pirate.png" alt="Pirate Island macOS Port" width="100%" />
</div>

<br>

# Pirate Island macOS Port

**Native macOS port of the classic 1989–1996 text adventure** by John H. Doolittle.

![macOS](https://img.shields.io/badge/macOS-000000?style=for-the-badge&logo=apple&logoColor=white)
![QB64](https://img.shields.io/badge/QB64-000000?style=for-the-badge&logo=visualbasic&logoColor=white)
![Retro](https://img.shields.io/badge/Retro%20Computing-FF6600?style=for-the-badge)

---

## Features

- Fully playable native `.app` (double-click to run)
- Proper macOS save location (`~/Library/Application Support/PirateIsland/`)
- Custom icon and window title
- Working Save / Restore Game
- Clean exit with credits screen
- Arrow key movement support

## How to Play
1. Download the latest `Pirate Island.app` from [Releases](https://github.com/M-Endymion/pirate-island-mac-port/releases)
2. Unzip it and move Pirate Island.app to your Applications folder (or anywhere you like).
3. Double-click to launch

**Classic commands:** `GO NORTH`, `GET FISH`, `REVEAL ORANGES`, `SAVE GAME`, etc.

### Commands are given in simple **VERB + OBJECT** format:
- GO NORTH (or just N)
- GET FISH
- REVEAL ORANGES
- WEAR CLOTHES
- SHARPEN BRANCH
- GIVE FISH (to the hermit)
- SAVE GAME / RESTORE GAME
- QUIT

### Tips from the original game:
Some objects appear as SOMETHING* or scrambled words (e.g. CNBAHR*). Use REVEAL to make them usable.
Pay attention to the parrot’s hints — they appear at specific turn counts.
You have 300 turns. Save often!

### Controls:
- Arrow keys or N/S/E/W/U/D for movement
- I or INVENTORY to check what you’re carrying
- Press any key to continue after messages



### Island Map

```ascii
                          PIRATE ISLAND
                               ▲
                               N
   ┌───────────────────────────┴─────────────────────────────────┐
   │                                                             │
   │   WOODS (11) ── EAST ── UPPER BEACH (10)                    │
   │      │                       │                              │
   │   HILLSIDE (12)         SANDY BEACH (7) ── NORTH ── SEA (5) │
   │      │                       │                              │
   │   HILLTOP (13)         ROCKY BEACH (8)                      │
   │      │                       │                              │
   │  PIRATE'S FORT (14) ── TIDE POOL (9)                        │
   │                                                             │
   └───────────────────────┬─────────────────────────────────────┘
                           │
                     MAIN DECK (3)
                           │
                    ┌──────┴──────┐
                    │             │
               FOOD LOCKER (1)  LAUNDRY (2)
                    │             │
               CODE ROOM (4)   ARMORY (6)
                    │
               PASSAGEWAY (18)
                    │
               SICK BAY (19) ── BRIG (20) ── TOOL ROOM (21)
```

### Room Quick Reference
```markdown
| Room # | Location              | Key Objects / Notes                  |
|--------|-----------------------|--------------------------------------|
| 1      | Food Locker           | Oranges (reveal)                     |
| 2      | Ship's Laundry        | Clothes (reveal)                     |
| 3      | Main Deck             | Cannon*                              |
| 4      | Code Room             | Secret messages                      |
| 5      | Open Sea              | —                                    |
| 6      | Armory                | Sword (reveal)                       |
| 7      | Sandy Beach           | —                                    |
| 8      | Rocky Beach           | —                                    |
| 9      | Tide Pool             | Fish                                 |
| 10     | Upper Beach           | —                                    |
| 11     | Woods                 | Branch (reveal) + Parrot             |
| 12     | Hillside              | —                                    |
| 13     | Hilltop               | Hermit                               |
| 14     | Pirate's Fort         | —                                    |
| 15     | Stockade              | Gunbox + Key (reveal)                |
| 16     | Campfire Area         | Pirates + Coals                      |
| 17     | Stockade Gate         | Prisoners + Lock                     |
| 18     | Passageway            | —                                    |
| 19     | Sick Bay              | Quinine (reveal)                     |
| 20     | Brig (start)          | Rat (reveal)                         |
| 21     | Tool Room             | Shovel (reveal)                      |
```


## Screenshots
![Title Screen](screenshots/title_screen.png) &nbsp;&nbsp;&nbsp;&nbsp; ![Gameplay](screenshots/gameplay.png)

---

## About the Project

This is a preservation port of a rare educational text adventure originally used in a university psychology class.

**Built with QB64** (Phoenix Edition) for native macOS performance.

---

## About the Author

**Jason Ray (M-Endymion)**

IT Professional by day • Retro computing & scripting enthusiast by night.

This project showcases my ability to:
- Port and modernize legacy code
- Build user-friendly applications
- Work with low-level tools and bundling

Great example of my attention to detail and passion for learning new tools.

- **LinkedIn**: [Jason Ray](https://www.linkedin.com/in/jason-ray-mecm/)
- **Open to opportunities**

**Last Updated:** May 17, 2026

**License:** Non-commercial preservation port. Original game credit to John H. Doolittle.

---

## Credits
**Original Game**  
Pirate Island by John H. Doolittle  
Used in his "Scientific Thinking in Psychology" class at California State University.  

---
