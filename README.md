# knowaboutme

Personal website of Ambuj Singh, built like a solar system. Eight planets, eight pages:
work and certificates, style, about me, what I'm doing now, hobbies, NDA journey,
favourite players and playlist.

It is a single static file (`index.html`) with no build step and no dependencies.

## Deploy on Vercel

1. Push this repository to GitHub.
2. Go to https://vercel.com/new and import the repository.
3. Framework Preset: **Other**. Leave Build Command and Output Directory empty.
4. Click **Deploy**. Your site goes live at a `*.vercel.app` address.
5. Optional: in Project Settings, then Domains, add your own domain.

Every time you push a change to `index.html`, Vercel redeploys automatically.

## Edit your content

Open `index.html` and find the `SITE` object near the top of the `<script>` tag.
All text, links, players, tracks and NDA details live there. Text in [square brackets]
is a placeholder to replace.

## Run locally

Open `index.html` in a browser, or run `npx serve .` in this folder.
