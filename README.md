# Softball Tracker

Single-file score and lineup tracker for slo-pitch / softball. No build step, no dependencies.

## Features
- Lineup of up to 12 players for one team (home or away)
- Current batter / on deck, auto-advances through the order
- Out / 1B / 2B / 3B / HR for both teams; hits move every runner up the same number of bases, and a HR clears the bases and scores everyone
- Diamond showing who's on base; tap a runner to advance, score, put out or remove them, or tap an empty base to move them there
- Runs are credited to the player who crosses home
- Outs auto-flip the half-inning at 3; manual "End half-inning" for run-limit innings
- Line score by inning, team HR totals, per-player R / HR / Outs / PA
- Undo, edit lineup mid-game, new game (keeps lineup)
- Saves to the browser (localStorage), so a refresh or closed tab won't lose the game

## Deploy to GitHub Pages
1. Create a repo and push `index.html` (and this README) to the `main` branch root.
2. Repo → **Settings → Pages** → Source: **Deploy from a branch** → `main` / `(root)` → Save.
3. After a minute it's live at `https://<username>.github.io/<repo>/`.

On your phone, open the URL and use **Add to Home Screen** for an app-like launcher.

Note: data lives on the device that's scoring — it doesn't sync between phones.
