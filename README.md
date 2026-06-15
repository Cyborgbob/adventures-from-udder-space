# Adventures from Udder Space

**Adventures from Udder Space** is a free-play, arcade-style browser game from **Technically Not a Technician**.

You are a UFO flying over a rural farm. Beam up cows before the timer runs out, avoid the farmer's gunfire, survive harder rounds, and chase the high score table.

This upload package is built for **GitHub Pages** and does **not** require npm, Node.js, Vite, or a build step.

## Quick GitHub Pages Setup

1. Create a public GitHub repository named:

   ```text
   adventures-from-udder-space
   ```

2. Upload all files from this folder into the repository root.

3. In GitHub, go to:

   ```text
   Settings > Pages
   ```

4. Set:

   ```text
   Source: Deploy from a branch
   Branch: main
   Folder: /root
   ```

5. Save.

6. Wait a minute or two, then open the GitHub Pages URL. It should look like:

   ```text
   https://cyborgbob.github.io/adventures-from-udder-space/
   ```

## Controls

| Function | Key |
|---|---|
| 1 Player Start | `1` |
| 2 Player Start | `2` |
| Move UFO | Arrow Keys |
| Backup movement | `WASD` |
| Tractor Beam | Hold `Spacebar` |
| Save initials | `Enter` |

## Current Features

- Arcade-style free play
- Attract/demo loop
- One-player mode
- Two-player alternating turns
- Third-person UFO movement
- Tractor beam cow abduction
- Farmer enemy fire
- Farmer radar HUD
- Additional farmers after Round 5
- Three lives
- Round timer
- Increasing difficulty
- Local browser high scores with initials
- Vintage black-and-white CRT-style presentation
- Cow moo sound effects
- Background music cycling

## Squarespace Embed Code

After GitHub Pages is working, create a TNT Squarespace page and add a Code Block with this iframe.

Replace `cyborgbob` if your GitHub username or repo URL is different.

```html
<iframe
  src="https://cyborgbob.github.io/adventures-from-udder-space/"
  width="100%"
  height="780"
  style="border:0; max-width:100%; background:#000;"
  allow="autoplay; fullscreen; gamepad"
  title="Adventures from Udder Space">
</iframe>
```

## File Structure

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

## License

The game code and project documentation created for this repository are released under the MIT License. See `LICENSE`.

Audio files may have separate licensing requirements. See `THIRD_PARTY_NOTICES.md` before publishing publicly.
