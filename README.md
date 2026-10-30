# Flappy Plane

A bilingual **English / 繁體中文** product site built around a fully playable one-button arcade game. Pilot a 303-liveried twinjet through a skyline of glass skyscrapers, chase medals and try to beat your personal best.

**Live site:** https://s20260002-rgb.github.io/flappy_plane/

## Highlights

- **The original game is still fully playable** — keyboard, mouse and touch controls, pause, mute, medals, local high scores and building explosions.
- **English and Traditional Chinese** — switch language anywhere on the page, including during a flight. The choice is remembered.
- **Responsive product site** — hero, features, flight manual, technical notes, team, FAQ and calls to action.
- **Local scores only** — personal bests are stored in the browser with `localStorage`; nothing is uploaded.
- **Single-file build** — no framework, no external images, no build step and no tracking.
- **Off-screen safety** — the game pauses automatically when it leaves the viewport.
- **Fullscreen mode** — expand the game on desktop or mobile where the Fullscreen API is available.

## Controls

| Action | Input |
| --- | --- |
| Boost | Click / tap / `Space` / `↑` |
| Pause | `P` or `Esc` |
| Mute | `M` |

## Authors

**1C Paco Au Yeung** and **1C Max Chan**

## Built with

- HTML Canvas 2D
- Web Audio API
- `localStorage`
- Vanilla JavaScript, HTML and CSS

## Project structure

```text
.
├── index.html
├── README.md
└── .github/
    └── workflows/
        └── deploy-pages.yml
```

## Run locally

Open `index.html` in any modern browser. No server or install step is required.

## Deployment

Every push or merge to `main` triggers the **Deploy to GitHub Pages** workflow in `.github/workflows/deploy-pages.yml`. The workflow packages `index.html` as a static site and publishes it through GitHub Pages. A manual deployment can also be started with `workflow_dispatch`.

## Notes

“Boeing 303” is a playful, fictional livery created for this game. The 303 twinjet is hand-drawn and is not a real production aircraft.

This is a student project created by 1C Paco Au Yeung and 1C Max Chan.
