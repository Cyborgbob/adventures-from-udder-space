# Adventures from Udder Space — Game Design Spec v0.1

## Elevator Pitch

**Adventures from Udder Space** is a free-play, arcade-style, third-person 3D browser game where one or two players take turns piloting a UFO over a rural farm, abducting cows before the timer expires while avoiding a farmer's gunfire.

## Core Fantasy

The player is the UFO. The farm is the arena. Cows are the prize. The farmer is the threat.

The game should feel like a strange lost cabinet game: funny, black-and-white, rural, spooky, and fast enough to be replayable.

## Arcade Flow

When idle, the game loops:

1. Title Screen
2. Story Card
3. Demo Gameplay
4. High Scores
5. Controls Screen
6. Title Screen

The game is always in **Free Play**.

## Start Rules

- Press `1` to start one-player mode.
- Press `2` to start two-player mode.
- Two-player mode is alternating turns.
- Both players use the same controls.

## Controls

| Action | Primary Key | Dev/Web Backup |
|---|---|---|
| Start 1P | `1` | none |
| Start 2P | `2` | none |
| Move Up | `ArrowUp` | `W` |
| Move Down | `ArrowDown` | `S` |
| Move Left | `ArrowLeft` | `A` |
| Move Right | `ArrowRight` | `D` |
| Tractor Beam | Hold `Spacebar` | same |

## Player Rules

- Each player starts with 3 lives.
- One hit from the farmer costs one life.
- Timer expiration costs one life.
- In two-player mode, losing one life ends that player's current turn.
- If the player clears the round, the player continues to the next round.
- Game ends when all active players have no lives remaining.

## Cow Abduction Rules

1. Player moves UFO over a cow.
2. Player holds `Spacebar`.
3. Tractor beam appears.
4. Cow rises into the UFO while the player stays positioned over the cow.
5. When the cow reaches full abduction progress, the cow is collected.
6. Score increases.
7. Round cow counter increases.

## Round Scaling

| Round | Cow Goal | Time | Farmer Difficulty |
|---|---:|---:|---|
| 1 | 5 | 60 sec | Bad shot |
| 2 | 7 | 50 sec | Better shot |
| 3 | 10 | 45 sec | Faster aim |
| 4 | 12 | 40 sec | Faster fire |
| 5+ | Increasing | Shrinking | Mean old farmer |

## High Scores

- Top 10 scores.
- Browser `localStorage` persistence.
- Initial entry after game over when score qualifies.
- High score table appears during attract mode.

## Visual Direction

- Black-and-white vintage cartoon/noir arcade feel.
- Rural American farm.
- UFO, cows, farmer, barn, fences, trees, old truck.
- Film grain, scanlines, vignette, grayscale contrast.
- Do not copy MOUSE: P.I. For Hire directly; use broader 1930s rubber-hose and 1950s UFO inspiration.

## Technical Direction

- Three.js + Vite.
- Static browser game.
- No backend required for v0.1.
- Local high scores only.
- Later versions can add asset files, sound/music, cabinet overlays, and optional online leaderboard.
