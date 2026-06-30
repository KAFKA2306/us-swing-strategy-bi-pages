# US Swing Strategy BI Dashboard

Static GitHub Pages bundle for the reconstructed US stock swing strategy audit dashboard.

- Published page: https://kafka2306.github.io/us-swing-strategy-bi-pages/
- Source snapshot: `10_projects/Kabu_Swing_Strategy` artifacts from 2026-06-22.
- Data model: TOP3 buy-now candidates, backtest matrix, Stage1 fundamentals, raw score outliers, cache coverage, and audit gaps.
- Runtime: no backend and no external browser dependencies; the dashboard embeds static JSON generated from the vault build.
- Evidence boundary: OOS counts, delisted-stock coverage, moomoo execution logs, and full production run history remain visible as unresolved gaps.

This repository is intentionally separate from the Obsidian vault so GitHub Pages can publish a minimal static site from the `main` branch root.
