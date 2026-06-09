# SportSpots — interactive prototype

A single-file, dependency-free clickable prototype of the SportSpots platform, built from
the 2018 master thesis *“A Business Plan Adapted for a Digital Startup.”* It turns the
paper's MVP feature list (Table 13) and the low-resolution wireframes (Annex VII) into a
working mobile interface.

## What it demonstrates
- **Discover / Search** — location header, #tag search, sport-type filter, nearby map with
  pins, recommended activities, and a "From your network" row (co-workers / company).
- **Activity detail** — capacity bar, host + rating, spot, level, equipment, participants,
  #tags, activity chat, and a working **Join** button (updates capacity live).
- **Create** — sport picker, details, spot selector, **Free / Split / Fixed** pricing,
  max attendees, and toggles for team invite, public, proximity check-in and Eventbrite.
- **Rewards** — rating ring, points & city rank, badges, trophies, vouchers (gamification engine).
- **Profile** — segment identity, stats, Strava link, favourite sports, connections
  (spots / teams / trainers / corporation).

## Run locally
Just open `index.html` in a browser. No build step.

## Deploy to Vercel
From this folder:

```bash
npm i -g vercel      # if you don't have the CLI
vercel               # preview deploy
vercel --prod        # production deploy
```

Or drag this folder onto https://vercel.com/new. It's a static site — no framework, no config needed.

## Notes
- Pure HTML/CSS/JS, fonts from Google Fonts. Emoji are used as sport/badge icons; swap for
  brand SVGs before a real launch.
- Sample data lives in the `ACT`, `SPORTS`, `NET` arrays at the bottom of `index.html`.
