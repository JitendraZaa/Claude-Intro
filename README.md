# Claude-Intro

Materials for an introductory, one-day "Getting started with AI assistants" workshop, plus a small dataset of recent AI model launches. All names, emails and figures are invented sample data.

## Contents

- `workshop/` - planning notes for the workshop: session outline, speakers, room notes, rough costs and a registrations export.
  - `workshop-materials/` - the materials set: flyer (PDF), room check spreadsheet, and a static `event-site/` page.
  - `old drafts/` - earlier drafts of the invite email and flyer.
- `ai-launches/launches.csv` - AI model launches by company and month, with per-million-token pricing.
- `.claude/launch.json` - preview configuration that serves the event site locally.

## Viewing the event site

```bash
python3 -m http.server 8765 --bind 127.0.0.1 --directory workshop/workshop-materials/event-site
```

Then open http://127.0.0.1:8765.
