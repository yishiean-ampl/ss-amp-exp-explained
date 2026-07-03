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
