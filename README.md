# SkillLink — Local Skill/Service Exchange Board

A full-stack college project (PHP + MySQL + vanilla JS) where users post local
skills/services, browse and search listings, and admins moderate submissions.

## Status: Practicals 1–3 complete
- ✅ Practical 1 — Requirements, sitemap, wireframes, repo setup (see `01-requirements.md`, `02-sitemap.md`, `03-wireframes.md`)
- ✅ Practical 2 — Semantic HTML5 pages, accessibility-ready
- ✅ Practical 3 — Responsive CSS (Grid + Flexbox), mobile-first

## Pages (10)
`index.html` · `listing-detail.html` · `post-listing.html` · `login.html` ·
`register.html` · `dashboard.html` · `admin-dashboard.html` ·
`admin-categories.html` · `search-results.html` · `404.html`

## How to view
Just open `index.html` in a browser — no build step, no server needed yet
(PHP/MySQL wiring starts at Practical 7–8). Resize the browser or use dev
tools device mode to check responsiveness; nav collapses to a hamburger
under 720px, cards reflow from 3 → 2 → 1 columns, and tables become stacked
cards under 640px.

## Folder structure
```
skilllink/
├── index.html
├── listing-detail.html
├── post-listing.html
├── login.html
├── register.html
├── dashboard.html
├── admin-dashboard.html
├── admin-categories.html
├── search-results.html
├── 404.html
├── css/style.css
├── js/            (JS logic lands in Practical 4+)
├── 01-requirements.md
├── 02-sitemap.md
└── 03-wireframes.md
```

## Design system
- Colors: ink `#1F2B24`, paper `#F6F3EC`, teal `#1F6F63`, ochre `#C68A2E`
- Type: Fraunces (headings), Public Sans (body), JetBrains Mono (prices/tags)
- Signature: listing cards styled as tear-tab community-board flyers

## Next up
Practical 4 (DOM/localStorage), 5 (form validation), 6 (Fetch + JSON) — then
PHP/MySQL backend from Practical 7 onward.
