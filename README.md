# Cosmoscope

An interactive 3D planetarium in a single HTML file. A night-sky instrument,
not a game: the sky fills the whole screen, with instruments at the edges —
search and guided tours across the top, a scale ladder down the left, an info
sheet on the right, and a clock along the bottom. Fly from Earth's orbit out
to the cosmic microwave background.

## Run it

Just open `index.html` in a browser. No build step, no server needed — the
only external dependencies are the three.js library and Google Fonts, both
loaded from a CDN, so it needs an internet connection.

## Tech

- [three.js](https://threejs.org/) (r147, via jsDelivr CDN) for the 3D sky
- Space Grotesk + Inter from Google Fonts
- Plain HTML, CSS and JavaScript — everything lives in `index.html`

## Publish

The site is published with GitHub Pages from the `main` branch:

`https://prachik2906.github.io/cosmoscope/`
