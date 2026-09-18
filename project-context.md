# SIE Prep marketing site context

- Service: `GLB-0005` / SIE Securities Essentials Prep
- Website repo: `MCYJ/sie-prep-by-rushlabs-web`
- Canonical production URL: `https://mcyj.github.io/sie-prep-by-rushlabs-web/`
- Android package / iOS bundle: `app.mcyj.examprep.glb0005`
- Google Play: `https://play.google.com/store/apps/details?id=app.mcyj.examprep.glb0005`
- App Store candidate: `https://apps.apple.com/us/app/id6795572831`
- Store verification on 2026-09-18: exact Google Play page returned HTTP 200; exact App Store candidate returned HTTP 404. Only Google Play may have an active CTA.
- Language: English (`en-US`). The exam and authoritative FINRA outline are English; thin translations are not published.
- App/service source remains read-only. This repository owns only the static marketing website.
- Product claims are limited to the current listing and verified app evidence: 500 independently written questions, explanations, mock exams, saved items, progress, and optional Lock Quiz.
- Do not state a subscription price. Historical USD 30 evidence is retired and the current Store-backed localized price controls.
- Official sources: FINRA SIE page, 2025 SIE Content Outline, Qualification Exams table, enrollment page, and FINRA Rule 1210.
- Current facts checked 2026-09-18: 75 scored plus 5 unidentified unscored items, 105 minutes, scaled passing score 70, USD 100 fee, minimum age 18, self-enrollment permitted, and passing SIE alone does not authorize securities activity or registration.
- Current Rule 1210 text shows retake waits of 15 days after a failed attempt and 60 days after three or more successive failures within two years. Direct readers to current Rule 1210 before rescheduling.
- The site is independent and must not imply FINRA affiliation, endorsement, registration authority, or access to live exam questions.

## Work log

- 2026-09-18: Created the isolated website workspace, verified exact Store publication state, and locked official-source and pricing boundaries before implementation.
- 2026-09-18: Published an English landing, 14 original study guides, FAQ, privacy, terms, support, contact, sitemap, robots and 404 pages. Local build/check passed for 23 HTML files and 21 indexable routes.
- 2026-09-18: Created public repository `MCYJ/sie-prep-by-rushlabs-web`. GitHub Pages deployment run `35351139719` passed.
- 2026-09-18: Production QA confirmed all 21 sitemap routes and seven required assets return HTTP 200, an unknown route returns HTTP 404, Google Play is the only active Store CTA, and App Store remains Coming soon with no invented URL.
- 2026-09-18 design refinement: applied `word-break: keep-all` with safe overflow handling across body text and controls so Korean/localized copy does not split awkwardly; URLs and contact strings retain emergency wrapping.
- 2026-09-18 Store badge refinement: normalized marketplace controls to a shared 194×75 frame while preserving each official badge asset's aspect ratio; local build and check passed.
