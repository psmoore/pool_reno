# Reno Aquatics — Pool Relay embed preview

A seven-page replica of the City of Reno
[aquatics pages](https://www.reno.gov/parks-and-recreation/recreation/aquatics/index.php): the hub, one page
per indoor pool (Moana Springs, Northwest Pool, Evelyn Mount Northeast Community Center) and the Lap Swim,
Open Swim and Water Fitness pages, each with a live [Pool Relay](https://www.poolrelay.com) calendar scoped to
what that page is about.

Not an official City of Reno page. It says so in a ribbon across the top.

Built with `python3 build.py` (edit it, not the HTML) and served by GitHub Pages.

## The seven pages

| Page | Calendar | Scoped to |
|---|---|---|
| `index.html` — Aquatics hub | [`6EZG0Jhw…`](https://www.poolrelay.com/v/6EZG0JhwbcBnJQJ0BPuJGD) | all three indoor pools, lap/open/fitness/closures, **Facilities** menu |
| `moana-springs.html` | [`6FLgbChT…`](https://www.poolrelay.com/v/6FLgbChTvYJ9HIzrOvff6g) | Moana Springs, **Pools** menu, soaking-pool hours included |
| `northwest.html` | [`vNTbLJ8d…`](https://www.poolrelay.com/v/vNTbLJ8djEkrM2EFKiRA5l) | Northwest Pool, **Pools** menu, closures included |
| `emnecc.html` | [`1MJf54cf…`](https://www.poolrelay.com/v/1MJf54cfzT6C58wRnPNk76) | Evelyn Mount Northeast Community Center |
| `lap-swim.html` | [`2xIy3AuL…`](https://www.poolrelay.com/v/2xIy3AuLknYSLUIjcYrWRf) | Lap Swim, **Pools** menu |
| `open-swim.html` | [`78pCfMc1…`](https://www.poolrelay.com/v/78pCfMc1pHs0bJjP7O2Hj7) | Open Swim, **Facilities** menu |
| `water-fitness.html` | [`qcu3LZLA…`](https://www.poolrelay.com/v/qcu3LZLAAL4xRScATCQQrR) | Water Fitness, **Facilities** menu |

## Sources (read 2026-09-23)

The Fall–Spring [Lap Swim](https://www.reno.gov/Documents/Parks%20and%20Recreation/Recreation/Aquatics/2026-2027%20Fall-Spring%20Lap%20Swim%20Schedule.pdf)
and [Open Swim](https://www.reno.gov/Documents/Parks%20and%20Recreation/Recreation/Aquatics/2026-2027%20Fall-Spring%20Open%20Swim%20Schedule%208.10.pdf)
schedules (effective August 10, 2026), the Water Fitness page, each facility's "Expand Details" panel, and the
aquatics page's Notice of Pool Closures.

## What is ours

- **Lane ranges** ("8–10", "2–10") are entered at the minimum.
- **Moana Springs** competition pool is two configurations: 19 × 25 yd and 10 × 50 m; Friday 5:30–2:00 uses the 50 m.
  Water Walking / Water Fit (competition pool, lanes unnamed) are on lanes 16–19.
- **Evelyn Mount Saturday** "11:30–2:30 (2–4)" is split at 12:45, when open swim starts: 4 lanes, then 2.
- **Northwest Sunday open swim** is on the 4 main-pool lanes lap swim leaves; water fitness is in the main pool,
  shallow water fitness in the training pool, from the first week of September.
- **Where the PDF and a facility page disagree, the PDF wins** (three Moana weekend times); where the Water Fitness
  page and a facility panel disagree, the panel wins (Northwest Wed/Fri 11:30 vs 11:45).
- **Closures** (Northwest, Sep 23–25 and Oct 6) are all-day bookings, with that day's sessions removed. The
  Sep 27 swim clinic is on the calendar; that Sunday's main-pool sessions were dropped when the draft went live.
- Series run open-ended: the city gives "August 10, 2026 – June 2027" with no end day.
- Northwest's address is stored as **2925 Appollo Way** — OpenStreetMap's spelling, the only one that geocodes.
  The real address is Apollo Way.
