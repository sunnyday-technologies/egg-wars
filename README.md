# EGG WARS 3D

**A 3D browser-based educational game where you solve math and spelling challenges to power up, build bridges, and destroy the enemy egg!**

Created by **J_ware** — Junior Developer & Test Engineer

## [Play Now](https://sunnyday-technologies.github.io/egg-wars/)

Works on desktop (Chrome, Firefox, Edge) and mobile (iOS Safari, Android Chrome).

## What Is Egg Wars?

Two teams on floating islands, each with an Egg to protect. Solve challenges at Power Cores to earn resources, buy gear at the Shop, build a bridge across the void, and destroy the enemy egg. Beat Jerry the AI opponent — if you can!

## Features

**Educational Challenges:**
- Power Core (easy), Energy Forge (medium), Crystal Nexus (hard)
- Grade-scaled content: Kindergarten through 5th grade
- Math: counting, addition, subtraction, multiplication, division
- Spelling: grade-appropriate words with missing letters
- 30/25/20 second timers by difficulty

**Gameplay:**
- 3D first-person voxel world (WebGL)
- Build bridges with cement blocks across the void
- Shop system: swords, pickaxes, armor, bows, TNT
- Combat with melee, ranged, and explosives
- Random power-ups: Speed Boost, Extra Hearts, Resource Rush
- Jerry the AI opponent with trash talk and scaling difficulty

**Multiplayer:**
- WebRTC peer-to-peer (no server needed for gameplay)
- Room codes: CREATE a game, share 4-letter code, friend JOINs
- Works on same WiFi or across the internet
- Kid-safe: no accounts, no chat, no data collection

**Progression:**
- 8 character skins: Tiger, Axolotl, Panda, Bee, Frog, Dragon, Robot
- Win streak tracking with special messages
- Local leaderboard (top 10 scores)
- Victory confetti and fanfare
- Difficulty auto-scales with grade and win streak

**Mobile:**
- Virtual joystick for movement
- Touch-drag to look around
- On-screen buttons: ATK, BLD, JUMP, interact
- Optional gyroscope look controls
- Works on phones and tablets

## Controls

### Desktop
| Action | Key |
|--------|-----|
| Move | WASD |
| Look | Mouse |
| Jump | Space |
| Sprint | Shift |
| Attack / Mine | Left Click |
| Place Block | Right Click |
| Interact | E (aim at station or shop) |
| Hotbar | 1-9 or Scroll |
| Use Apple | Q |

### Mobile
| Action | Control |
|--------|---------|
| Move | Left joystick |
| Look | Drag right side of screen |
| Jump | JUMP button |
| Attack | ATK button (red) |
| Place | BLD button (blue) |
| Interact | E button (gold) |
| Gyro Look | 🔄 button (optional) |

## Tech

- Single HTML file — zero server dependencies
- WebGL 3D voxel engine from scratch
- Per-vertex ambient occlusion
- Procedural sky with twinkling stars and shooting stars
- Procedural audio via Web Audio API (all sounds generated)
- WebRTC multiplayer via PeerJS
- ~1,900 lines of vanilla JavaScript

## Build Stats

This game was built from scratch in a single conversation session with Claude Code:

- **21 git commits** from first line to v1.0
- **~1,950 lines** of hand-crafted JavaScript (105 KB)
- **~800K–1M tokens** used across the full session
- **0 external assets** — every pixel, sound, and texture is procedurally generated
- **1 HTML file** — the entire game, engine, and UI

## Version

**v1.0.0** — First full release

## License

MIT License — See [LICENSE](LICENSE) for details.

---

*a sunnyday technologies project*
