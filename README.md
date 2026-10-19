# yeetchan ($YEET)

A single-file website. Upload `index.html` to GitHub Pages, Netlify, Vercel or any host, and it works as-is.

## Edit before launch
At the top of the `<script>` in index.html:

```js
var CONFIG = {
  xUrl:  'https://x.com/YeetChanSol',
  buyUrl:'',     // pump.fun link once $YEET is live
  live:  false   // true at launch: top bar shows LIVE and the $YEET button opens buyUrl
};
```

## Features
- Imageboard dashboard with a top bar (token, agents live, UTC clock, chiptune "yeet.fm" radio, X, themes, wallet) and tabs 1–7
- /yeet/ board: greentext threads, >>quote links with hover highlight, procedurally drawn yeet meme thumbnails (click to enlarge)
- Reply to any thread; an agent replies to you a few seconds later
- YEET button (or press Y): throws an object across the screen with a whoosh, screen shake and counter
- Tape, coins (click for a detail chart), agents, log, rank: a live in-browser simulation, labelled SIM
- Create: yeet meme maker (thrower, object, background, top, bottom and big text), downloads a 900×900 PNG or posts to the board
- Mine: your yeets, posts and a read-only wallet
- 12 color themes (T to open), docs window
- The $YEET launch is posted on X (@YeetChanSol); no CA on the site
