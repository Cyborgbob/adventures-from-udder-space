# Adventures from Udder Space

**Adventures from Udder Space** is a free-play, arcade-style browser game from **Technically Not a Technician**.

Fly a UFO over a haunted little farm, beam up cows, dodge angry farmers, and chase the high score table before the clock runs out.

> **Status:** Early playable prototype / arcade polish build  
> **Mode:** 1-player or 2-player alternating turns  
> **Runs in:** Modern desktop web browsers  
> **Build step:** None required

## Play the Game

Once GitHub Pages is enabled, the game should be playable here:

```text
https://cyborgbob.github.io/adventures-from-udder-space/
```

If this project is embedded on the TNT website, the public-facing page will be linked here once available.

## The Premise

The cows are out. The farmers are armed. The saucer is hungry.

Your mission is simple: abduct the required number of cows before time expires. Each round gets harder. The timer shrinks, the quota rises, and after Round 5, more farmers join the hunt.

Clear rounds, survive as long as possible, and earn a spot on the high score board.

## Controls

| Function | Key |
|---|---|
| 1 Player Start | `1` |
| 2 Player Start | `2` |
| Move UFO | Arrow Keys |
| Backup Movement | `WASD` |
| Tractor Beam | Hold `Spacebar` |
| Save Initials | `Enter` |

## Current Features

- Free-play arcade flow
- Attract/demo mode
- One-player mode
- Two-player alternating turns
- Third-person UFO movement
- Tractor beam cow abduction
- Farmer enemy fire
- Farmer radar HUD
- Additional farmers after Round 5
- Three lives per player
- Round timer and cow quota
- Increasing difficulty
- Local browser high scores with initials
- Vintage black-and-white CRT-style presentation
- Cow moo sound effects
- Background music cycling

## How the Game Plays

1. Press `1` for a one-player game or `2` for a two-player game.
2. Fly over a cow.
3. Hold `Spacebar` to activate the tractor beam.
4. Keep the cow in the beam until it is pulled into the UFO.
5. Avoid farmer gunfire.
6. Meet the cow quota before the timer runs out.
7. Survive harder rounds and chase the high score table.

## About the Project

This started as a small experiment: could a simple browser game feel like a real little arcade cabinet?

The answer is yes.

The goal is not to make a giant modern game. The goal is to make a fun, weird, playable arcade-style web game that fits the Technically Not a Technician universe: practical, strange, funny, and built from scratch.

## Project Structure

```text
adventures-from-udder-space/
├─ index.html
├─ assets/
│  └─ audio/
├─ docs/
│  └─ game_design_spec_v0_1.md
├─ LICENSE
├─ README.md
├─ THIRD_PARTY_NOTICES.md
├─ SQUARESPACE_EMBED.html
└─ .nojekyll
```

## Hosting

This version is designed to run as a static website. It does not require npm, Node.js, Vite, a backend server, or a build process.

Recommended hosting options:

- GitHub Pages
- Cloudflare Pages
- Netlify
- A static web host

For GitHub Pages, upload the files to the repository root and enable:

```text
Settings > Pages > Deploy from a branch > main > /root
```

## Squarespace / TNT Website Embed

The game can be embedded into a Squarespace page using an iframe. See:

```text
SQUARESPACE_EMBED.html
```

Recommended public page idea:

```text
technicallynotatechnician.com/games/adventures-from-udder-space
```

The Squarespace page can present the game as part of the TNT website while the game files are hosted separately as a static web app.

## Roadmap Ideas

Possible future improvements:

- Better farm props and environmental polish
- More cow animations
- More farmer behavior
- Cabinet-style bezel or frame
- Fullscreen button
- Mobile/touch controls
- More sound effects and music options
- Screenshot or shareable score card
- Online leaderboard, if we decide it is worth the maintenance

## License

The game code and project documentation created for this repository are released under the MIT License. See `LICENSE`.

Audio files may have separate licensing requirements. See `THIRD_PARTY_NOTICES.md` before publishing publicly.

## Credits

Created by **Technically Not a Technician**.

Built with help from ChatGPT as a collaborative design and coding assistant.
