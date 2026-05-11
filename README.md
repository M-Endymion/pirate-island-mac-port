# Pirate Island macOS Port

**A native macOS port of the classic 1989–1996 text adventure** by John H. Doolittle.

![Game Screenshot](screenshots/title_screen.png)

## Features
- Fully playable native macOS `.app` (double-click to run)
- Proper macOS save folder (`~/Library/Application Support/PirateIsland/`)
- Custom icon and window title
- Working Save / Restore Game
- Clean exit with credits screen

## How to Play
1. Download the latest `Pirate Island.app` from [Releases](https://github.com/M-Endymion/pirate-island-mac-port/releases)
2. Unzip it and move Pirate Island.app to your Applications folder (or anywhere you like).
3. Double-click to launch
4. Type commands like `GO NORTH`, `GET FISH`, `REVEAL ORANGES`, `SAVE GAME`, etc.

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
### Room Quick Reference

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

## Credits
**Original Game**  
Pirate Island by John H. Doolittle  
Used in his "Scientific Thinking in Psychology" class at California State University.  
Source code released in 2023 to the [IF Archive](https://www.ifarchive.org/).

**macOS Port**  
Created by [M-Endymion](https://github.com/M-Endymion) using QB64.

## Building from Source
- Open `pirate_island_qb64.bas` in QB64 (Phoenix Edition recommended)
- Compile → Make EXE / .app only
- Create the `.app` bundle structure (see `BUILD.md` if added)

## License
This is a non-commercial historical/educational port. The original source was publicly released for preservation. Please credit John H. Doolittle when sharing.

## Links
- Original source: [IF Archive](https://www.ifarchive.org/indexes/if-archive/games/source/basic/)
- QB64: https://qb64phoenix.com/

---

**Made with ❤️ for retro computing preservation**
