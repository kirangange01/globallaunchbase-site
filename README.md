# globallaunchbase-site

Static site for **globallaunchbase.com**. Hosted on Netlify (project: `globallaunchbase`).

## Structure
- Root `.html` files are the pages. No build step — edit HTML directly.
- `resources/` holds the article library; `resources/index.html` is its listing page.
- Internal links are extensionless (`/about`, `/resources/slug`) — Netlify resolves these to the matching `.html` file.

## Deploy
Push to `main`. Once linked to the Netlify project, every push publishes.
Until linked: drag-and-drop the folder into Netlify -> Deploys.

## Baseline
Initial commit = the live Netlify deploy as of August 2026.
