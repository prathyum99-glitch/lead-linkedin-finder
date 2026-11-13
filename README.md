# Lead LinkedIn Finder

A single-page helper for sales teams: enter a lead's name and whatever else the lead form captured (email, company, job title, college, city) and it builds LinkedIn-only searches on Google, Bing and LinkedIn, most precise first.

- One static file, `index.html`. No server, no API, no login.
- Nothing is stored or sent. Fields clear on the Clear button, on closing the tab, or after 2 minutes idle.
- Results are a shortlist to confirm, not a verified match.

## Deploy

Pushes to `main` publish to GitHub Pages through `.github/workflows/pages.yml`.
One-time setup: repo Settings > Pages > Source: GitHub Actions.
