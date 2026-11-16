# Urbanism Tool Trophy Case

A repository for urbanism tools, apps, and services that are useful to the broader movement of building and improving our neighborhoods and cities. Curated by [College Towns](https://www.collegetowns.org). Part of the [App Locker](https://applocker.collegetowns.org) · Urbanism Wing.

Live site: https://urbanismtools.collegetowns.org

## Adding or changing a tool

Everything is in `index.html`. Search for `const TOOLS` and add an entry:

```js
{case:'maps', name:'My Tool', kw:'extra search words', maker:'Who made it', icon:'zone',
 url:'https://example.com',
 desc:'One or two sentences about what it does.',
 for:['Advocates','Planners'], price:'FREE'},
```

- `case`: `housing`, `maps`, `games` or `community` (this picks the trophy case)
- `kw`: hidden words that help the directory search find it
- `icon`: one of the keys in `ICONS` (just above `TOOLS`)
- `price`: `FREE` or `SERVICE`
- `ct:true` adds the "Made by College Towns" plate

## Urbanism Tool of the Month

1. Add a line to the top of `WINNERS` (newest first), e.g. `{month:'Dec 2026', name:'Pre-Approved ADU Plans'}`. The name must match the tool's `name`. Every winner gets a small dated trophy on its plaque, and older winners are listed under "Past winners" automatically.
2. Update the featured case near the top of the page (search for `Urbanism Tool of the Month`): the title, "Created by", the blurb, the brass plate month, and the "Up next" line.

## Other files

- `CNAME`: the web address (urbanismtools.collegetowns.org)
- `og.png`: the preview image shown when the link is shared
- `apple-touch-icon.png`: the icon for phone home screens

## Submissions

The "Submit Your Own" form opens the visitor's Gmail or email app with the submission filled in, addressed to the App Locker inbox.

## Visitor counter

Visits are counted privately with [GoatCounter](https://collegetowns.goatcounter.com) (sign in to see them). Pages are recorded with the site name in front, e.g. `urbanismtools.collegetowns.org/`.

## Credits

Header type: Versa by James Lewis. Tools listed are made by their respective creators.
