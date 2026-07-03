# 🧭 Statsig Enablement Hub

Interactive, animated learning site for the **Learn Statsig** track — built for Amplitude field teams.

**Live site:** https://yishiean.github.io/statsig-enablement/

## 📚 Contents

| Page | What it covers |
| --- | --- |
| `index.html` | Hub landing page with the learning path |
| `statsig-101.html` | Statsig 101 Foundational — build/ship/measure/learn loop, gates vs experiments, Pulse basics |
| `reading-results.html` | Reading Experiment Results — scorecard, lift, SRM, ship decisions (animated stats) |
| `feature-gates.html` | Feature Gates Deep Dive — rule fall-through, rollout hashing, gate metrics, safe ops |
| `analytics-session-replay.html` | Analytics + Session Replay — Metrics Explorer, funnel split, replay triggers |
| `stats-models.html` | Statsig vs Amplitude — statistical models, animated (sequential testing, Bayesian/frequentist, CUPED) |
| `concept-map.html` | Statsig ↔ Amplitude concept map (reference) |

Each course includes interactive simulators for statistical concepts, ELI6 explanations, Amplitude equivalents, and per-unit + cumulative quizzes. Quiz progress is stored in browser localStorage.

## ⚠️ Notes

- AI-generated learning aids sourced from the internal learn-statsig validated corpus. Validate specific claims against [docs.statsig.com](https://docs.statsig.com) before external use.
- Self-contained static HTML — no build step, no dependencies. Hosted on GitHub Pages.

## 📝 Changelog

| Version | Date | Change |
| --- | --- | --- |
| v1.0 | 2026-07-03 | Initial site: 5 artifacts unified with shared nav + hub page, published to GitHub Pages |
| v1.1 | 2026-07-03 | Added Statsig vs Amplitude statistical models page (stats-models.html), nav updated across all pages |
| v1.2 | 2026-07-03 | Hub split into two sections: /learn-statsig Courses (4-course track) and Reference Library (stats models + concept map) |
| v1.3 | 2026-07-03 | Removed hero learning-path strip — hub is growing beyond a fixed 5-page path |
| v1.4 | 2026-07-03 | Scroll-to-top button on all pages (appears after 350px scroll, smooth scroll, hover state) |
| v1.5 | 2026-07-03 | stats-models.html hero standardised to match other pages (rounded gradient card, left-aligned) — CSS only, content and animations untouched |
| v1.6 | 2026-07-03 | stats-models.html section nav restyled as concept-map-style pill tabs (content-width, card pills, blue lead pill) — CSS only |
| v1.7 | 2026-07-03 | Hero unit-pill rows added to statsig-101.html and reading-results.html, matching courses 3 & 4 |
| v1.8 | 2026-07-03 | "Course N of 4" hero badges on courses 1, 3, 4 (course 1 badge text updated; badges added to 3 & 4) |
| v1.9 | 2026-07-03 | stats-models nav: fixed stuck highlight — replaced static first-pill styling with a scrollspy (.active follows the section in view and on click) |
