# photographer-website

One-page personal website for Serena Lee, a freelance wedding and portrait photographer. It is a static site with no build step.

## Structure

- `public/index.html`: the whole site (HTML and CSS).
- `public/images/`: portfolio photos. Swap the remaining "Photo to come" blocks in `index.html` for `<img>` tags like the first one.
- `vercel.json`: Vercel config. Serves `public/`, no build, with caching and security headers.

## Run locally

```
npm run dev
```

## Deploy on Vercel

1. Import this repo at vercel.com/new.
2. Leave the framework preset as "Other". No build or install command is needed; `vercel.json` sets the output folder to `public`.
3. Deploy. Every push to `main` redeploys.

## To update

- Replace the placeholder email `hello@serenalee.com` in `public/index.html`.
