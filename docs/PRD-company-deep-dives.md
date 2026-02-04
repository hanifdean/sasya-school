# PRD: MEDC & EMAS Company Deep Dives

## Summary
Create two new company deep dive pages in `investing/company-deep-dives/` for Medco Energi (MEDC) and Merdeka Gold Resources (EMAS), following the exact visual system used in `micron-mu.html`.

## Goals
- Publish two polished deep dive pages with the same design system, layout, and section navigation as the Micron reference page.
- Include: investment thesis card, key metrics, business segments, growth catalysts, risks, jargon decoder with inline linking, source credits, and navigation.
- Add MDKA cross-link on EMAS page.

## Non-Goals
- Updating the Study Hub index or adding new global navigation entries.
- Changing shared styles or global layout templates.

## Scope
- New files:
  - `investing/company-deep-dives/medc-medco.html`
  - `investing/company-deep-dives/emas-merdeka-gold.html`
- Localized content updates only; no shared CSS or JS changes.

## Content Requirements
### MEDC
- Integrated energy narrative: O&G output ramp, Medco Power growth, AMMN stake and earnings leverage.
- Key numbers: 156k → 165–170k mboepd, 4,371 → 4,550 GWh, 20.92% AMMN stake, 70% gas mix, $360M AMMN contribution (2026), Rp2,000 analyst target.

### EMAS
- Pre-production gold miner, MDKA subsidiary, IPO $281M (Sep 2025).
- Pani Gold Project: 19 Mtpa, first gold Q1 2026, 79k → 500k oz by 2032.
- Optionality thesis and MDKA cross-link.

## Design Constraints
- Match `micron-mu.html` visual system (fonts, colors, cards, tables, section nav, theme toggle).
- Preserve section navigation behavior and CSS/JS structure.

## Success Metrics
- Both pages render with consistent layout on desktop and mobile.
- Jargon links navigate correctly to the decoder section.
- Section navigation highlights active section on scroll.

## Open Decisions
- None.

## Checkpoints
1. Build MEDC deep dive page with required sections.
2. Build EMAS deep dive page with required sections and MDKA cross-link.
3. Update PRD/TODO/Project status logs and commit changes.
