# matthewr
my github repository

## Headstock guitar tuner

`tuner/index.html` is a self-contained guitar tuner that runs in the browser and listens through the microphone.

- Needle meter (±50 cents) with "tune up / tune down" hints
- Tunings: Standard, Drop D, Half/full step down, DADGAD, Open G/D/E, Chromatic
- Tap a string to hear a reference tone and lock the meter to that string
- Adjustable A4 pitch (415–466 Hz)

The microphone only works over https (or localhost). To try it locally: `cd tuner && python3 -m http.server`, then open http://localhost:8000. To use it on your phone, enable GitHub Pages for this repo.
