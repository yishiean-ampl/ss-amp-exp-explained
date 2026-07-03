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
| `amplitude-mechanics.html` | Amplitude Experiment mechanics — bucketing to p-values, animated (reference) |
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
| v1.10 | 2026-07-03 | QA pass: unbolded course 3 & 4 hero badges, added missing AI disclaimer to concept-map, standardised all page titles with "· Learn Statsig" suffix |
| v1.11 | 2026-07-03 | ELI labels standardised to 🧒 ELI6 across all pages (stats-models ELI5→ELI6 x9, emoji position aligned on courses 1-3) |
| v1.12 | 2026-07-04 | "Last updated" date stamp added to the footer of every page |
| v1.13 | 2026-07-04 | Folded in Amplitude Experiment Mechanics page (amplitude-mechanics.html): house hero + pill nav + scrollspy + 🧒 ELI6 x13 + full footer kit; navbar rebuilt across all 8 pages |
| v1.14 | 2026-07-04 | Removed duplicate hero concept pills on stats-models + amplitude-mechanics; section nav now wraps (no hidden horizontal scroll) |
| v1.15 | 2026-07-04 | Purple-infused hero gradients, unique per page (angles 115-160deg, varied violet midpoints); analytics-session-replay kept as the reference favourite |
| v1.16 | 2026-07-04 | One-line hero titles: stats-models reworded to "Statsig & Amplitude Experiment's Stats Models, Explained"; amp-mechanics trimmed to "Bucketing to P-Values" |
| v1.17 | 2026-07-04 | stats-models hero subtext reframed: confidence-building, not an obligation list |
