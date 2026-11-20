# Mosasaur: Lost in the Deep

A deep-sea browser game for kids. Steer your mosasaur with your finger and use SONAR and DASH to find your way through the deep. Built for phones and tablets.

**Play it:** [https://mosasaur-game.hckshr.workers.dev/](https://mosasaur-game.hckshr.workers.dev/)

The whole thing is one self-contained `index.html` (no build step, no dependencies). It's served by a tiny Cloudflare Worker.

## Run locally

Open `index.html` in a browser.

## Deploy

```sh
node build.mjs        # regenerate worker.js from index.html
npx wrangler deploy   # publish to Cloudflare Workers
```
