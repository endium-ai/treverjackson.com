# treverjackson.com

Personal site. Static HTML served from Cloudflare Workers using the static assets binding.

## Stack

- Cloudflare Workers + Static Assets
- No build step, no framework — just HTML/CSS

## Deploy

```bash
wrangler deploy
```

## Local preview

Open `public/index.html` directly in a browser, or use wrangler's local dev server:

```bash
wrangler dev
```
