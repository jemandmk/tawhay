# 🌸 Tawhay

**One day at a time.** Tawhay is a calm, single-page daily planner designed to feel
like a morning ritual rather than a productivity tool. As you complete your tasks, a
flower grows from seed to full bloom — a gentle, visual reward for showing up for yourself.

## Features

- **Progress flower** — a growing emoji inside a fill-to-% ring that blooms 🌱 → 🌹 as you
  complete the day's tasks.
- **Today's focus** — a simple task list with priorities and satisfying completion animations.
- **Age-adaptive interface** — the colors, typography, and tone adjust for teens, young
  adults, adults, and seniors.
- **Daily wisdom** — a rotating verse or quote to start the day.
- **Mood check-in** — log how you're feeling.
- **Calendar** — daily, weekly, and monthly views that reflect your real tasks.
- **Meal planner** — plan the week and explore global cuisines, including Filipino dishes.
- **Monthly moments** — capture the month's highlights and lowlights.

Everything is saved locally in your browser (`localStorage`) — no account, no server.

## Tech

A single, dependency-free `index.html` file: HTML, CSS, and vanilla JavaScript. That's it.
No build step, no framework.

## Run it locally

Because the app uses `localStorage`, open it through a local web server rather than the
`file://` protocol:

```bash
python3 -m http.server 8000
# then visit http://localhost:8000
```

## Deploy

It's a static site — any static host works. This project deploys to
[Vercel](https://vercel.com) with zero configuration.
