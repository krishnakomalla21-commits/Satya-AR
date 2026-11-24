# Satya — WebAR Poster (MC3101 Module 05)

Point a phone at the *Satya (1998)* poster in the Film Noir section. When the poster is detected, glass cracks spread from the title, the red title bleeds, the skyline windows flicker, a noir drone fades in, and 7 tappable points open info cards.

**Stack:** MindAR 1.2.5 (image tracking) + A-Frame 1.5.0

## Files
- `index.html`: the whole experience
- `assets/targets.mind`: compiled tracking data for the poster
- `assets/satya-target.jpg`: the image the tracking file was made from
- `assets/theme.mp3` (optional): add your own track and it replaces the synth drone

## Deploy (GitHub Pages)
1. Create a public repo, e.g. `satya-ar`, and upload `index.html`, `README.md` and the `assets/` folder.
2. Repo → Settings → Pages → Source: *Deploy from a branch*, Branch: `main` / `(root)` → Save.
3. After about a minute it's live at `https://<username>.github.io/satya-ar/`. HTTPS is needed for camera access.

## Test without the wall
Open `assets/satya-target.jpg` full-screen on a laptop and point the phone at the screen.
