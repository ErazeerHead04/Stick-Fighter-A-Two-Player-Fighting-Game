# Stick Fighter – A Two-Player Fighting Game

**Stick Fighter** is a two-player 2D fighting game inspired by *Shadow Fight 2*, built using **Processing**. The game features smooth combat mechanics, keyboard-based controls, dynamic health bars, animations, and sound effects to create a fun and interactive gameplay experience.

---

##  Gameplay Overview

Two players face off in a best-of-three combat match. Each player controls a stick fighter character and can perform moves like punching, kicking, jumping, and blocking. The round ends when one fighter's health drops to zero. The player who wins two out of three rounds is declared the winner.

---

##  Controls

| Action    | Player 1         | Player 2  |
|-----------|------------------|-----------|
| Move Left | Left Arrow       | `A`       |
| Move Right| Right Arrow      | `D`       |
| Jump      | Up Arrow         | `Space`   |
| Block     | Down Arrow       | `S`       |
| Punch     | `,` (comma)      | `W`       |
| Kick      | `.` (period)     | `E`       |

---

## Combat Mechanics

- **Punch**: Reduces 1 point from opponent’s health
- **Kick**: Reduces 2 points from opponent’s health
- **Block**: Prevents any damage while held
- **Jump**: Avoid incoming attacks or create space

Each fighter starts with **100 health points**. Damage is visually tracked using a health bar displayed at the top corners of the screen.

---

## Game Structure

- 3 rounds per match
- Win condition: First to win 2 rounds
- Restart option available after a match ends

---

## Graphics & Animations

- Character animations for punch, kick, block, and jump
- Smooth transitions between actions
- Environmental background and scenes

---

## Sound Effects

- Unique sounds for each action (punch, kick, jump)
- Background music to enhance atmosphere

---

## Technical Implementation

- Built in **Processing**
- Object-oriented design with `Player` and `Game` classes
- Keyboard input handling and state management
- Health bar rendering and round tracking

---
## Prerequisites

- Download and install the **Processing** application to run this game.

---

## How to Run

1. Open the project in **Processing**.
2. Run the sketch.
3. Play the game using the keyboard controls listed above.

---

## Additional Features

- Best-of-three rounds system
- Blocking and real-time damage detection
- Visual feedback for health and game outcome

Enjoy fighting it out with a friend in this minimalist yet strategic 2D combat game!
