# Sanctuary Rwanda

Catholic property discovery and visit-enquiry website for Rwanda.

## Run locally

```sh
python3 -m http.server 8000 --directory dist
```

## Deploy

Vercel: Other framework, no build or install command, output directory `dist`.
Render: Static Site, build command `true`, publish directory `dist`.

68 listings and 232 separate parish records. 75 source-linked photographs across 47 properties; remaining photographs await verification. Near-me search uses 17 mapped institution locations, radius filtering and browser geolocation. District estimates can be enabled separately; a starting-district selector is available when geolocation fails. Distances are straight-line estimates. Location stays in browser memory.

Parish profiles show only documented locality matches, naming each place. Parishes without matches explicitly show no linked properties; a diocese-wide property total is never substituted.

Schools, healthcare, pilgrimage and hospitality listings use different actions. Enquiries are browser-local drafts with optional email-app handoff, not confirmed reservations. No live inventory, database or payments.

Images remain copyright of the cited original rights holders. No Church endorsement or operator partnership implied.
