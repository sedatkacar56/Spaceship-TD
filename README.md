# 🚀 STELLAR DEFENSE — README

A browser-based spaceship tower defense game. No installation required — just open `spaceship-tower-defense.html` in any modern web browser.

---

## How to Play

### Starting the Game

1. Open `spaceship-tower-defense.html` in your browser.
2. On the **Main Menu**, pick a difficulty mode (Easy, Medium, or Hard).
3. Click **LAUNCH MISSION** to begin.

### The Goal

Enemy spaceships follow a glowing path across the screen from **IN** to **END**. Your job is to place friendly defense ships alongside the path to destroy the enemies before they reach the end. If too many enemies break through, you lose lives. Lose all your lives and it's game over.

---

## Difficulty Modes

| Mode   | Starting Cash | Lives | Waves |
|--------|--------------|-------|-------|
| Easy   | 1,000        | 200   | 30    |
| Medium | 700          | 150   | 60    |
| Hard   | 500          | 100   | 80    |

---

## Controls

| Action | How |
|--------|-----|
| Select a ship to buy | Click a card in the right-hand shop panel |
| Place a ship | Click anywhere off the path on the map |
| Cancel placement | Right-click |
| Select a placed ship | Click directly on it |
| Sell a placed ship | Select it, then click **SELL UNIT** |
| Send the next wave | Click **▶ SEND WAVE** |
| Toggle game speed | Click **⏩** to switch between 1x and 2x speed |
| Return to menu | Click **⬅ MENU** |

---

## Defense Ships (Shop)

| Ship | Cost | Damage | Range | Fire Rate | Notes |
|------|------|--------|-------|-----------|-------|
| Scout Fighter | 75 | 8 | 110 | 1.2/s | Cheap, fast interceptor — great starter |
| Laser Cruiser | 175 | 22 | 140 | 0.7/s | Precision strikes, good range |
| Plasma Cannon | 320 | 55 | 120 | 0.4/s | Heavy burst damage |
| Missile Frigate | 480 | 90 | 170 | 0.3/s | Longest range in the fleet |
| Tesla Destroyer | 750 | 35 | 100 | 2.5/s | Chain-fire rapid shots |
| Dreadnought | 1,200 | 200 | 200 | 0.18/s | Massive power, slow to fire |

Ships can be sold at any time for **60% of their total cost**.

---

## Enemy Ships

Enemies grow stronger as waves progress. Later waves introduce tougher ship types.

| Enemy | Shape | Threat Level | Lives Damage on Breakthrough |
|-------|-------|-------------|------------------------------|
| Fighter | Triangle | Low | 1 |
| Cruiser | Diamond | Medium | 2 |
| Bomber | Hexagon | High | 4 |
| Warship | Square | Very High | 8 |
| Titan | Star | Extreme | 15 |

Each enemy has a health bar displayed above it. Color shifts from green → yellow → red as HP drops.

---

## Economy

- You earn **credits** by destroying enemies — harder enemies pay more.
- At the end of each wave you receive a **bonus payout** that scales with your wave number.
- Credits earned mid-game are **session-only** — if you quit to the main menu, they are lost.
- The **Credits** shown on the main menu are persistent and can only be added to by winning games (a bonus is calculated from your final score).

---

## Placement Rules

- Ships **cannot** be placed on or too close to the enemy path (the lane is highlighted in blue).
- Ships **cannot** overlap each other.
- You can keep placing the same ship type repeatedly as long as you can afford it.
- A translucent preview and range circle appear while placing — it turns **red** if the spot is invalid.

---

## Tips

- **Scout Fighters early** — at just 75 credits they let you cover the path quickly while you save for bigger ships.
- **Choke points matter** — place ships near the corners of the path where enemies slow their effective movement.
- **Mix ranges** — pair long-range Missile Frigates with fast-firing Tesla Destroyers for good coverage.
- **Don't ignore the wave bonus** — sometimes it's worth letting a wave end before spending all your credits.
- **Sell and upgrade** — selling a Scout and buying a Laser Cruiser mid-game is often worth the switch.
- On **Hard mode**, enemies arrive faster and are tougher. Prioritize damage-per-second over raw damage.

---

## Technical Notes

- Built entirely in a single HTML file — no dependencies, no server needed.
- Works in Chrome, Firefox, Edge, and Safari (modern versions).
- Resize your browser window freely; the game canvas adapts automatically.
- Game speed can be doubled at any time using the ⏩ button.

---

*Good luck, Commander. The galaxy is counting on you.*
