# John C. Argue Swim Stadium — Pool Relay embed preview

A replica of the City of Los Angeles facility page for the **Expo Center / LA84 Foundation /
John C. Argue Swim Stadium**, with the typed "Hours of Operation" block replaced by a live
[Pool Relay](https://www.poolrelay.com) calendar.

Not the official City of Los Angeles website. The official page is
<https://recreation.parks.lacity.gov/aquatic/year-round/john-c-argue-swim-stadium>. This is a
working preview of one proposed change to it, and the page says so in a ribbon across the
top — a disclaimer only in the source is one nobody opening the page can see.

## Read this before showing it to anyone

**The calendar opens empty, on purpose.** This pool is different from the other replicas, and
the difference is the whole point.

The only hours published anywhere for it are headed *"Summer Operational Hours: June 14, 2026
— August 8, 2026"*. That season has ended. The pool is year-round, the city's own Year-Round
Pools list shows it **OPEN, HEATED** today, and no current hours are published on the facility
page, on the year-round list, or in the Summer 2026 brochure. The Citywide Aquatics page says
year-round hours "vary per facility" and points at the year-round list; that list carries
statuses and addresses and no hours.

So the calendar is empty for the current month because that is exactly what the site tells a
swimmer today. **Press the month arrow back twice, to July 2026, and it fills up** with every
session the page lists.

Nothing has been invented. If the facility sends its fall hours, this page is current the same
day.

## The schedule that is in it

Modeled from the facility page on **11 September 2026**, as six standing series dated
14 June – 8 August 2026, all on the Family Pool:

| Session | Days | Time |
|---|---|---|
| Lap Swim | Monday | 7:00–9:00 am |
| Lap Swim | Tuesday–Friday | 6:00–9:00 am |
| Lap Swim (evening) | Mon, Wed, Fri | 7:30–8:30 pm |
| Lap Swim | Sat, Sun | 12:00–1:00 pm |
| Rec Swim | Monday–Friday | 1:00–4:00 pm |
| Rec Swim | Sat, Sun | 1:00–4:30 pm |

**No lane allocation is published, so none is invented.** Every session sits on the Family Pool
as a whole. The Competition Pool exists in the model with no sessions, because the page says it
"remains closed for maintenance".

The holiday closures the page lists (December 24, 25, 31, January 1, and "MLKD/Juneteenth
(January 19)") are **not** in the calendar. They fall outside the only season the page gives
hours for, and the page contradicts itself on December 31, listing it as closed and also as a
half day open 1pm–5pm. Picking one silently would be inventing an answer.

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
