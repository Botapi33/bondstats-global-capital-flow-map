# BondStats Global Capital Flow Map

Institutional cross-border portfolio-flow visualization for BondStats.

## Design principle
`Capital Never Sleeps.` is the editorial line. The tool deliberately does **not** claim to show real-time bank transfers. It separates observed portfolio-investment data, market-session context and BondStats-derived directional pressure.

## Rights / copyright posture
- No third-party map tiles, map artwork, logos, trademarks, screenshots or copied interface elements.
- The abstract world silhouette and all UI/CSS/SVG are original code in this repository.
- Underlying data: World Bank Open Data indicator `BN.KLT.PTXL.CD`, shown by the World Bank as CC BY 4.0.
- Attribution and transformation disclosure are visible in the interface.
- No FRED dependency.
- No commercial market-data dependency.

## Refresh
GitHub Actions runs the updater on weekdays. The source itself is annual/periodic, so the tool never labels the observed portfolio-flow data as real-time. The session layer updates in-browser from time zones.

## GitHub Pages
Enable Pages from the repository root / main branch after upload.
