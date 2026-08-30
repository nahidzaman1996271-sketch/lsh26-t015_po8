# Third-Party Material and AI Disclosure

| Name | Version or source URL | Licence | Used for |
|---|---|---|---|
| Source Serif 4 | fonts.googleapis.com / fonts.gstatic.com (Google Fonts CDN) | SIL OFL 1.1 | Headings |
| IBM Plex Mono | fonts.googleapis.com / fonts.gstatic.com (Google Fonts CDN) | SIL OFL 1.1 | Marks, grade points, data |
| Inter | fonts.googleapis.com / fonts.gstatic.com (Google Fonts CDN) | SIL OFL 1.1 | UI labels, buttons |
| Kalam | fonts.googleapis.com / fonts.gstatic.com (Google Fonts CDN) | SIL OFL 1.1 | Red-pen trace annotations |
| P08_school_results_public.json | Supplied by event organizers (participant pack) | N/A — organizer-provided fixture data, not authored by the team | Input dataset the tool operates on |
| Puppeteer (dev only) | devDependency in `package.json`, used for `smoke_test.js` headless-browser smoke test | Apache-2.0 | Verifying the page renders correctly during development; not loaded by `index.html` or required to run the app |

No frontend framework, starter kit, or template was used — `index.html`,
`engine.js`, `app.js`, and `styles.css` were written from scratch for this
submission. No icon or asset library is used; the "circled fail" annotation
on the trace screen is a hand-authored inline SVG path (`app.js`,
`PEN_CIRCLE_SVG`).

## AI tools

- **Claude** — Used for drafting and iterating on the grading engine (`engine.js`) and report UI (`app.js`/`data.js`) logic against the brief's rules and clarifications (R-10 through R-29). Verified by manually recomputing GPA and grade points by hand for representative students covering all four required hard-edge cases, and by cross-checking the on-screen checking lists against the fixture data directly.

## Original-work statement

Everything not declared in this file or `EVENT.md` was created by the
registered team during the event window.
