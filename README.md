# Sanctuary Rwanda

Catholic property discovery and visit-enquiry website for Rwanda.

## Run locally

```sh
python3 -m http.server 8000 --directory dist
```

## Deploy

Vercel: Other framework, no build or install command, output directory `dist`.
Render: Static Site, build command `true`, publish directory `dist`.

68 listings and 232 separate parish records. 51 source-linked photographs across 27 properties; remaining photographs await verification. Near-me sorting uses approximate district centres, not verified entrances. Location stays in browser memory.

Schools, healthcare, pilgrimage and hospitality listings use different actions. Enquiries are browser-local drafts with optional email-app handoff, not confirmed reservations. No live inventory, database or payments.

Images remain copyright of the cited original rights holders. No Church endorsement or operator partnership implied.
