# Star Explorers

A learning web game for kids aged 4–8, in Hebrew and English.

- 7 worlds, 77 stages: numbers, letters and words, shapes and patterns, memory, thinking games, telling the time, animals and nature
- Stars unlock worlds; coins buy heroes, pets, hats, rides, toys and home scenes
- Questions are read aloud (browser speech synthesis)
- Progress is saved in the browser (localStorage), on one device only
- No accounts, no tracking, no personal data collected

## Run locally

It is a single static file. Open `index.html` in a browser, or serve the folder:

```sh
npx serve .
```

## Deploy

Any static host works. For example:

- **Cloudflare Pages:** connect this repo, no build command, output directory `/`
- **Netlify:** connect this repo, no build command, publish directory `/`
- **GitHub Pages:** Settings → Pages → deploy from branch `main`, folder `/` (needs a public repo on the free plan)
