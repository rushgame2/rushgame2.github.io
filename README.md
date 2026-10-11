# Orb Rush

A free browser game. Eat glowing dots, swallow smaller orbs, dodge bigger ones and climb the leaderboard.

- Single player against bots, no server needed
- Mouse or touch controls, Space or the ⚡ button to boost
- One file (`index.html`), no libraries, no tracking

## Play locally

Double-click `index.html`.

## Publish with GitHub Pages (free)

1. Create a public repository on GitHub.
2. Upload `index.html` and `README.md`, then commit.
3. Open **Settings → Pages**, choose Branch `main` and folder `/ (root)`, then Save.
4. After a minute or two the game is live at `https://<your-username>.github.io/<repo-name>/`.

## Ideas to extend it

- Change `W`, `H`, `N_PELLETS`, `N_BOTS` at the top of the script to tune difficulty.
- Add new colors or bot names in `COLORS` and `NAMES`.
- Real online multiplayer needs a server (for example Node.js with WebSockets).
