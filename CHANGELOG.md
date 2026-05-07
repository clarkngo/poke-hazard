# Changelog

All notable changes to PokéHazard are documented here.
Format: [Keep a Changelog](https://keepachangelog.com/en/1.0.0/)

---

## [Unreleased]

### Added
- Animated node network background in hero section — 55 drifting nodes connected by proximity edges, with glowing packets traveling along edges in green, red (viral), and purple (mutation)

---

## [0.2.0] — 2026-05-07 — Homepage & Plan

### Added
- `docs/index.html`: full landing page with dark toxic-green aesthetic
  - Glitch title animation (POKÉHAZARD)
  - Typewriter tagline cycling through three phrases
  - 9 feature cards with phase badges and per-card color accents (Viral Dex, T-Evolution, Mutation Monsters, Viral Core Extraction, Bio-Containerization, Living Weapons, Bio-Armor, Sentient Accessories, Viral Load)
  - Systems section with three interactive diagrams (Living Weapon loop, Bio-Pod slot visualizer, Viral Load meter)
  - Monster archetype → gear table with viral strain badges
  - 8-phase roadmap cards; Phase 1 marked IN PROGRESS
  - Scroll reveal animations via IntersectionObserver
  - Sticky nav with blur backdrop and scroll tint
- `PLAN.md`: full development plan covering data models, all 8 systems, and per-phase task checklists

### Infrastructure
- `docs/` folder established as the GitHub Pages root
- Phase snapshot workflow documented: each completed phase build is frozen to `docs/phaseN/`

---

## [0.1.0] — 2026-05-07 — Initial Commit

### Added
- Repository initialized with README
