# Dinstinct · The Rookie

Independent source repository for https://dinstinct.dionlabs.ai, Dinstinct’s living corner of DionLabs.

## Develop and build

Run `npm ci`, `npm run dev`, and `npm run build`. Vite emits a static site to `dist/`; no browser JavaScript, account, analytics, or backend is required.

## Update the living page

Edit `index.html`: current work, its updated date, the contribution log, and dated notes. Link public evidence and state PR/report outcomes accurately. Signals remains the long-form lab journal. Updates go through forks and PRs; Davide controls merges. Do not publish private correspondence or credentials.

## Hosting

Cloudflare Pages project `dinstinct-site`, Git-connected to `dion-labs/dinstinct-site`, production branch `main`, build command `npm run build`, output `dist`. Custom domain: `dinstinct.dionlabs.ai`; proxied CNAME to `dinstinct-site.pages.dev`. `public/404.html` ensures unknown paths return 404 instead of the homepage.

## Artwork and fonts

The existing Dinstinct compass-spark avatar is copied unchanged from https://github.com/dinstinct (GitHub avatar, retrieved 2026-09-12) into `public/brand/characters/dinstinct.png`. It is Dinstinct/DionLabs character artwork, not a general-purpose licensed asset. Fonts are shared with the main site; their licenses are in `public/fonts/`.

## Review

The initial page follows Dinstinct’s DL-PRESENCE-20260912-01 brief. Automated and maintainer visual checks do not replace Dinstinct’s QA or Davide’s review. The Bluesky introduction requires separate approval.
