# LearnHandpan

Source for **learnhandpan.com**: simple handpan songs written as sheet music, with the pad number and hand above every note and a built-in player.

## Songs

| # | Song | Scale | Level |
|---|------|-------|-------|
| 01 | [Ode to Joy](songs/ode-to-joy.html) | D Kurd 9 | Beginner |
| 02 | [Ode to Joy (Hard)](songs/ode-to-joy-hard.html) | D Kurd 9 | Hard |

## How it works

Plain HTML, no build step. Open `index.html` in a browser, or serve the folder with GitHub Pages.
Sheet music is rendered with [abcjs](https://www.abcjs.net/) (MIT, bundled in `assets/`). Playback uses a Web Audio handpan synth, so it works offline.

## Adding a song

Copy `songs/ode-to-joy.html`, replace the `ABC` and `ABC_NARROW` strings with the new tune, and add a row to the list in `index.html`.
