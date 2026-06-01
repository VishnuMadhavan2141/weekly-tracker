# Luck Surface Area — Weekly Tracker

A single-file weekly tracker for a remote-work job search, built on one idea:

> Luck = how much you **make** × how many people **see it**.

Run the same five moves every week. Building feeds the posting, posting feeds the
inbound, inbound feeds the interviews. Consistency over 8–12 weeks is what moves the needle.

**Live:** https://vishnumadhavan2141.github.io/weekly-tracker/

## What it does

- **Foundation** — one-time setup items to get the inbound channels working.
- **Daily habits** — tap a dot per day, Mon–Sun. The current day is highlighted.
- **Weekly goals** — the weekly batch of moves, plus a reflection note per week.
- **Progress** — overall completion, "full days" (days where every habit is done),
  and a consecutive **full-day streak** that carries across weeks.
- **Edit mode** — rename, reorder, add, or remove any item; edit the headline.
  The plan adapts as your search evolves.

## Notes

- One file. No build, no dependencies. Just open `index.html`.
- Progress is saved per-device in `localStorage`, namespaced under `lsa:` so it can
  share an origin with sibling tools without collisions. Nothing leaves the browser.
- Dates are handled in local time, so weeks and streaks stay correct in any timezone.
