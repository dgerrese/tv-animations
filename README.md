# th[is] TV

Animations to show on a TV, served with GitHub Pages: https://dgerrese.github.io/tv-animations/

Each animation is one self-contained `<name>/index.html` with no build step. To show one on a TV, open it in Chrome, cast the tab to a Chromecast, and go fullscreen. Or open it in Chromium kiosk mode on a Raspberry Pi.

| Animation | Notes |
|-----------|-------|
| [hearth](hearth/) | Christmas fireplace. URL params: `?n=` flame particles (default 220), `?scale=` render resolution (default 1). |
| [th[is] DVD Bounce](this-dvd/) | Logo bounces, new colour per bounce, confetti on a corner hit. `?speed=` 1–20 (default 5), `?size=` % of width (14). |
| [th[is] Weave](this-weave/) | Endless zoom into the logo's weave. `?speed=` s per 2x zoom (10), `?direction=1` zooms out, `?huecycle=` °/s (10), `?huestep=` ° per ring (10), `?colour=` hex without # (f58113). |
| [th[is] Snow](this-snow/) | Logos snowing in three layers. `?amount=` (80), `?speed=` (5), `?size=` % of width (5). |
| [th[is] Fireworks](this-fireworks/) | Rockets bursting into logos. `?rate=` per minute (30), `?sparks=` (60), `?size=` (2), `?crossette=` % (20), `?double=` % (20). |
| [th[is] Impossible](this-impossible/) | 3D logo sculpture that orbits, then snaps to the flat logo. `?rings=` 2–8 (2), `?orbit=` °/s (12), `?snap=` s per cycle (30), `?hold=` s (1), `?colour=` (f58113). |
