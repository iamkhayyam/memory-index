# The Ramification Index

[![Site](https://img.shields.io/badge/site-live-brightgreen?style=flat-square&labelColor=20232d)](https://iamkhayyam.github.io/memory-index/)
[![Status](https://img.shields.io/badge/status-working%20paper-orange?style=flat-square&labelColor=20232d)]()
[![Last Commit](https://img.shields.io/github/last-commit/iamkhayyam/memory-index?style=flat-square&labelColor=20232d&color=6ed3ff)](https://github.com/iamkhayyam/memory-index/commits/main)
[![Data](https://img.shields.io/badge/data-1980–2026-4a7cc7?style=flat-square&labelColor=20232d)]()
[![License](https://img.shields.io/badge/license-CC%20BY%204.0-lightgrey?style=flat-square&labelColor=20232d)](https://creativecommons.org/licenses/by/4.0/)

> RAM prices, oligopoly cycles, and the downstream consequences of semiconductor pricing as an economic signal — a supply-side alternative to the Lipstick, Hemline, Men's Underwear, and Buttered Popcorn indices.

This project proposes **the RAM Index** — year-on-year change in the three-firm DRAM oligopoly's average selling price per gigabyte — as a cleaner, earlier, structurally grounded substitute for the consumer-behaviour folk indices that financial journalism has used for a century. We reconstruct the series annually for 1980–2026, compare it against the four incumbent indices across all six NBER-dated US recessions, and package the whole thing three ways: two LaTeX manuscripts and one interactive dashboard.

## Layout

```
memory-index/
├── README.md                  ← this file
├── research/                  ← one markdown file per series with data + bibliography
│   ├── ram-prices.md
│   ├── lipstick-index.md
│   ├── hemline-index.md
│   ├── underwear-index.md
│   ├── popcorn-index.md
│   └── macro-baseline.md
├── data/
│   └── indices-wide.csv       ← consolidated annual series, 1980–2026
├── paper-arxiv/               ← arXiv-submittable manuscript
│   ├── main.tex
│   └── references.bib
├── paper-nature/              ← Nature/SpringerNature-style manuscript
│   ├── main.tex               (uses sn-jnl.cls; falls back to article)
│   └── references.bib
└── dashboard/
    └── index.html             ← living comparison dashboard (Chart.js, single file)
```

## The argument in one paragraph

Informal economic indicators — lipstick, hemlines, underwear, popcorn — exist because real macro data used to be slow. Each is anchored in consumer folk-psychology and each has failed at least one of the last two cycles: the Lipstick Index collapsed under COVID-era mask mandates, the Hemline Index lags the economy by three years (van Baardwijk & Franses 2010), the Men's Underwear Index has a 2-cycle track record, and the Buttered Popcorn Index was structurally broken by streaming. DRAM is the opposite kind of signal: an oligopoly-priced commodity whose ASP swings by orders of magnitude each cycle, whose decisions are made 18 months ahead of shipment, and whose macro weight is *rising* as AI capex eclipses consumer PC demand. The RAM Index catches all six NBER recessions since 1980; no folk index catches more than three.

## Quickstart

### 1. View the living dashboard

```bash
open memory-index/dashboard/index.html
```

Zero dependencies. Pure HTML + Chart.js via CDN. Toggle series, toggle recession shading, live Pearson correlations.

### 2. Build the arXiv paper

```bash
cd memory-index/paper-arxiv
pdflatex main && bibtex main && pdflatex main && pdflatex main
```

### 3. Build the Nature-style paper

```bash
cd memory-index/paper-nature
pdflatex main && bibtex main && pdflatex main && pdflatex main
```

The Nature file uses Springer Nature's `sn-jnl.cls`. If the class isn't installed, uncomment the two fallback lines at the top of `main.tex` to compile as a plain `article`.

## Key data sources

| Series | Source |
|--------|--------|
| DRAM $/MB, 1957–present | [John C. McCallum](https://jcmit.net/memoryprice.htm); [AI Impacts](https://aiimpacts.org/trends-in-dram-price-per-gigabyte/); [TrendForce](https://www.trendforce.com/price/dram/dram_spot); Federal Reserve FEDS 2006-44 |
| Lipstick / prestige beauty | Circana (formerly NPD+IRI), WWD, Leonard Lauder (Estée Lauder) |
| Hemline | van Baardwijk & Franses (2010) from *L'Officiel* magazine 1921–2009 |
| Men's Underwear | Mintel, NPD, Washington Post (Mui 2009); Greenspan, *The Age of Turbulence* |
| Box office | Box Office Mojo, The Numbers, NATO |
| Macro baseline | FRED, BLS, BEA, NBER |

Each `research/*.md` file carries its own full bibliography and a CSV block.

## Contributing / extending

- Update `data/indices-wide.csv` with new quarters as they become available.
- The dashboard reads the data inline from the bottom of `dashboard/index.html`; keep the two in sync.
- A natural next step is a **Memory Complex Index** that blends DRAM, NAND, and HBM in capacity-weighted shares — the HBM share is now the most AI-sensitive sub-signal.
