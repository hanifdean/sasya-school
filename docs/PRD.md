# PRD: Polymarket Arbitrage Study Page

## Summary
Create a new study page in `investing/polymarket-arbitrage.html` summarizing “The Math Needed for Trading on Polymarket” by @RohOnChain, and update the Study Hub index to include the page under Investing & Markets.

## Goals
- Publish a polished, readable page that matches the Study Hub visual system (teal accent, light/dark themes, CSS variables, default light).
- Capture the five-part structure and key numbers with scannable sections, callouts, and a stats row.
- Keep navigation consistent with other study pages (sidebar nav + mobile pill bar).

## Non-Goals
- Reproducing the full original thread verbatim.
- Changing shared global styling or layout in `index.html` beyond adding the new page entry.

## Scope
- New HTML page in `investing/`.
- Update `index.html` `PAGES` array.
- Add footer source link to the tweet.

## Content Requirements
- Five sections with `h2` headings (Parts I–V) and key bullets.
- Stats/metrics row with: `$40M extracted`, `17,218 conditions`, `41% mispriced`, `$496 avg profit`.
- “Key Takeaway” box at the end of each part.
- Math-styled callout boxes (monospace, accent border) for formulas.
- Resources list for paper/theory/solver/LLM.

## Design Constraints
- Match existing Study Hub style; default to light theme.
- Use the section navigator pattern from `finance/broken-promise.html`.
- Use teal accent color and CSS variables.

## Success Metrics
- Page renders without layout regressions on desktop and mobile.
- Section nav highlights active section.
- Index entry appears under Investing & Markets and page count reflects new entry.

## Open Decisions
- None.

## Checkpoints
1. Create `investing/polymarket-arbitrage.html` with layout + content.
2. Add page entry to `index.html`.
3. Quick self-review for layout and required elements.
