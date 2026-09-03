# Daily

A personal life dashboard for Thomas — college student + business owner.

Open it on your phone every morning. Three tabs:

- **Today** — daily rituals (Gym, Read Bible, Run, Prayer) with fire-streaks, plus a
  task list where each task can have a time. Add for today or tomorrow.
- **Money** — log what you spend and what you earn. See spent today, spent/earned/net
  this month, and progress toward your monthly earning goal.
- **Me** — your name, earning goal, edit your rituals, streak records, and
  export/import a backup.

## How it works

- One static page. No accounts, no server. All data lives in this browser
  (`localStorage`) on the device you use it on.
- Installable: on iPhone Safari → Share → **Add to Home Screen**. It then opens
  full-screen like an app and works offline.
- **Back up regularly** from the Me tab — clearing Safari data wipes it.

## Run locally

```bash
python3 -m http.server 8000
# open http://localhost:8000
```

## Deploy

**Live:** https://tcudii5.github.io/daily-dashboard/

Hosted on GitHub Pages from `main` (repo root, no build step). Every push to
`main` redeploys automatically — usually live within a minute.

`netlify.toml` is kept for the connected `daily-thomas` Netlify project, which
is a dormant backup (Netlify build credits were exhausted at setup time; it
will deploy again once the billing cycle resets).
