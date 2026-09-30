# John C. Argue Swim Stadium — Pool Relay embed preview

A replica of the City of Los Angeles facility page for the **Expo Center / LA84 Foundation /
John C. Argue Swim Stadium**, with the typed "Hours of Operation" block replaced by a live
[Pool Relay](https://www.poolrelay.com) calendar.

Not the official City of Los Angeles website. The official page is
<https://recreation.parks.lacity.gov/aquatic/year-round/john-c-argue-swim-stadium>. This is a
working preview of one proposed change to it, and the page says so in a ribbon across the
top — a disclaimer only in the source is one nobody opening the page can see.

## Read this before showing it to anyone

**The fall hours went up late, and the calendar now has them.** When this replica was built on
11 September 2026, the only hours published for the pool were headed *"Summer Operational Hours:
June 14, 2026 — August 8, 2026"*, three days into a fall season that starts September 8. The
calendar opened empty for weeks, because that was exactly what the site told a swimmer. The fall
hours appeared later and were entered on **29 September 2026**. Page back to July and the summer
is still there as it ran.

## The schedule that is in it

**Fall 2026** (September 8 – November 12), on the Family Pool's 5 lanes (40 m, D-shaped; lane
count from places2swim.com):

| Session | Days | Time | Lanes |
|---|---|---|---|
| Lap Swim | Monday–Friday | 7:00 am–1:00 pm | 1–5 |
| Lap Swim ("limited lanes") | Monday–Friday | 1:00–4:00 pm | 1–2 |
| Rec Swim | Monday–Friday | 1:00–4:00 pm | 3–5 |
| Rec Swim | Monday–Friday | 4:00–5:00 pm | 1–5 |
| Lap Swim (evening, "limited lanes") | Monday–Friday | 7:30–8:30 pm | 1–2 |
| Lap Swim ("limited lanes") | Saturday | 1:00–4:30 pm | 1–2 |
| Rec Swim | Saturday | 1:00–4:30 pm | 3–5 |

**The lane split is our estimate.** The page says "limited lanes" and never how many; 2 of 5 is
written into each session's description as an estimate. It also doesn't say lap swim has every
lane before 1pm; that is our reading of "limited lanes until 4:00 p.m." while Rec Swim runs.

**Closed for maintenance, November 13 – December 25**, as one all-day booking on the whole
facility. The page gives the fall hours as "September 8 – November 13" and the closure as
"November 13 – December 25"; the calendar treats the 13th as closed.

**Summer 2026** (June 14 – August 8) stays as it was modeled: six series on the Family Pool as a
whole, from before its lanes were added.

The Competition Pool has no sessions, because the page says it "remains closed for maintenance".
The holiday closures the page lists (December 24, 25, 31, January 1, and "MLKD/Juneteenth
(January 19)") are not modeled separately. December 24 and 25 fall inside the maintenance
closure, and no hours are published after it. The page also contradicts itself on December 31,
listing it as closed and as a half day open 1pm–5pm.

## Notes

- Hand-written HTML and CSS. It will not drop into their Drupal theme as-is.
- The department logo and the facility photo are hotlinked from recreation.parks.lacity.gov.
  Fonts come from Google Fonts.
- Navigation and sidebar links are inert placeholders.

## Local preview

```
python3 -m http.server 8796
```

Then open <http://localhost:8796/>.
