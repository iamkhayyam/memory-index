# The RAM Index: DRAM Price History, 1980–2026

## 1. Canonical data sources

- **John C. McCallum** — the reference time series for DRAM price per unit capacity (1957–present), based on published retailer and wholesale quotes. Hosted at [jcmit.net/memoryprice.htm](https://jcmit.net/memoryprice.htm). McCallum's series is the de facto standard used by Hennessy & Patterson (*Computer Architecture: A Quantitative Approach*) and by AI Impacts' semiconductor trend work.
- **AI Impacts** mirrors and extends the McCallum series in 2020 dollars: [Trends in DRAM price per gigabyte](https://aiimpacts.org/trends-in-dram-price-per-gigabyte/). Headline result: **~36 %/yr decline 1957–2020** (factor of 10 every 5.1 years), slowing to **~15 %/yr since 2010** (factor of 10 every 14 years).
- **hblok.net** maintains a machine-readable CSV of memory, HDD, SSD and flash prices sampled from NewEgg 2000–2017: [hblok.net/blog/storage/](https://hblok.net/blog/storage/).
- **TrendForce / DRAMeXchange** — contract and spot ASP reports from 2000 onward: [trendforce.com/price/dram/dram_spot](https://www.trendforce.com/price/dram/dram_spot).
- **Federal Reserve FEDS 2006‑44**, "Shifting Trends in Semiconductor Prices and the Pace of Technological Progress," Aizcorbe, Oliner, Sichel: [federalreserve.gov/pubs/feds/2006/200644](https://www.federalreserve.gov/pubs/feds/2006/200644/index.html). Documents constant-quality DRAM price decline ≈ 15 %/yr in 1990–95; steeper thereafter.

## 2. Nominal $/MB headline series (annual)

Values below are mid-year average retail for a typical mainstream module, rounded. Sources: McCallum (jcmit), hblok.net, TrendForce. Pre‑1995 figures are for the then‑current generation (1 kb → 64 kb → 1 Mb → 16 Mb DRAM); 1995+ figures are SIMM/DIMM retail.

| Year | US $/MB | Module context |
|------|---------|----------------|
| 1980 | 6,480 | 16 kb DRAM, NMOS |
| 1981 | 4,479 | 16 kb / 64 kb transition |
| 1982 | 2,027 | 64 kb DRAM |
| 1983 | 685 | 64 kb DRAM |
| 1984 | 451 | 64 kb / 256 kb |
| 1985 | 385 | 256 kb; Japanese dumping episode |
| 1986 | 178 | post-dumping crash |
| 1987 | 133 | US–Japan trade sanctions lifted late year |
| 1988 | 107 | "RAM drought" — shortage year |
| 1989 | 73  | 1 Mb DRAM dominant |
| 1990 | 47  | — |
| 1991 | 42  | — |
| 1992 | 39  | — |
| 1993 | 34  | — |
| 1994 | 32  | — |
| 1995 | 30  | 4–16 Mb modules |
| 1996 | 6.9 | capacity oversupply crash begins |
| 1997 | 4.1 | — |
| 1998 | 1.38 | — |
| 1999 | 1.13 | — |
| 2000 | 1.05 | DDR1 emerging |
| 2001 | 0.23 | dot-com bust / spot-price collapse |
| 2002 | 0.16 | DDR1 |
| 2003 | 0.19 | — |
| 2004 | 0.19 | DDR2 transition |
| 2005 | 0.13 | — |
| 2006 | 0.16 | — |
| 2007 | 0.11 | oversupply; DDR3 launch |
| 2008 | 0.039 | GFC-era crash |
| 2009 | 0.024 | — |
| 2010 | 0.012 | — |
| 2011 | 0.0078| Elpida bankruptcy year |
| 2012 | 0.0044| Elpida into Micron; "Big Three" consolidation essentially complete |
| 2013 | 0.0055| supercycle begins |
| 2014 | 0.0069| — |
| 2015 | 0.0047| — |
| 2016 | 0.0030| — |
| 2017 | 0.0053| supercycle peak |
| 2018 | 0.0082| — |
| 2019 | 0.0035| post-supercycle crash |
| 2020 | 0.0035| COVID demand surge |
| 2021 | 0.0036| — |
| 2022 | 0.0030| server glut; crash |
| 2023 | 0.0018| bottom of cycle |
| 2024 | 0.0029| AI / HBM-driven recovery |
| 2025 | 0.0041| AI memory supercycle, DDR5 & HBM3e |
| 2026 (Q1) | 0.0052| DDR4 16 Gb back at all-time highs |

**Converted to $/GB (more convenient for modern years):** 1980 ≈ $6.6 M, 1990 ≈ $48 k, 2000 ≈ $1,050, 2010 ≈ $12, 2020 ≈ $3.50, 2025 ≈ $4.10.

## 3. Market events and inflection points

| Period | Event | Price impact |
|--------|-------|--------------|
| 1985–86 | SIA files trade complaint; US–Japan Semiconductor Agreement; accusations of Japanese dumping of 64 kb / 256 kb DRAM | Prices collapsed 60–70 % then stabilized under trade enforcement |
| 1988 | "The Year of the RAM Drought" ([Tedium](https://tedium.co/2016/11/24/1988-ram-shortage-history/)) — post-dumping capacity underinvestment | Prices spiked ~60 % YoY |
| 1995–96 | Capacity addition cycle completes; Asian fabs ramp | First large modern oversupply crash: $30→$7/MB |
| 1997 | Asian Financial Crisis triggers LG / Hyundai → Hynix merger | Consolidation begins |
| 1999 | NEC + Hitachi DRAM operations → Elpida | — |
| 2001 | Dot-com bust, PC demand collapse | $1.05 → $0.23 /MB in a single year |
| 2007–08 | Oversupply + GFC | ASP fell ~70 % 2007→2009 |
| 2011–13 | Elpida bankruptcy (2012); Micron acquires Elpida (2013); industry consolidates to Big Three | Floor + recovery |
| 2016–18 | First true oligopoly supercycle: tight supply, PC + server + mobile demand | $0.003 → $0.008/MB |
| 2018–19 | EU/US/China antitrust probes into Samsung, SK Hynix, Micron for alleged price coordination | Cycle tops; sharp correction |
| 2020–21 | COVID WFH surge | Moderate tightening |
| 2022–23 | Server glut + weakening PC demand | Worst crash since 2008; prices at cycle lows |
| 2024–26 | AI / HBM driven demand; HBM allocation crowds out commodity DDR | DRAM ASP recovers to near all-time highs in nominal terms |

## 4. Industry consolidation: from a crowd to an oligopoly

> "The top three corporations had around 35 % of the market in the 1990s but controlled almost 95 % by 2022." — [NoobFeed, "How Samsung, Micron, and SK Hynix Built Dominance"](https://www.noobfeed.com/articles/samsung-micron-hynix-dram-cartel)

Approximate count of major DRAM makers by year:

| Year | Notable producers | N |
|------|-------------------|---|
| 1985 | Intel, Motorola, Mostek, TI, AMD, National, Micron, IBM, NEC, Toshiba, Hitachi, Fujitsu, Mitsubishi, OKI, Matsushita, Samsung, LG/Goldstar, Hyundai, Siemens/Infineon | ≈20 |
| 1995 | US (Micron, TI, IBM), Japan (NEC, Hitachi, Toshiba, Fujitsu, Mitsubishi, OKI), Korea (Samsung, Hyundai, LG), Europe (Siemens), Taiwan (Nanya, Winbond, Powerchip) | ≈15 |
| 2005 | Samsung, Hynix, Micron, Elpida, Qimonda, Nanya, Powerchip, ProMOS, Winbond | 9 |
| 2010 | Samsung, Hynix, Micron, Elpida, Nanya, Powerchip | 6 |
| 2013 | Samsung, SK Hynix, Micron (Elpida acquired by Micron; Qimonda bankrupt 2009) | 3 + Taiwan fringe |
| 2020 | Samsung, SK Hynix, Micron (~95 % share) | 3 |
| 2025 | Samsung, SK Hynix, Micron + emerging CXMT (China) | 3 + 1 |

As of Q1 2025, [SK Hynix holds 36 % share, Samsung 34 %, Micron 25 %](https://marklapedus.substack.com/p/sk-hynix-surpasses-samsung-in-dram) — SK Hynix overtook Samsung for the first time, driven by HBM leadership.

## 5. Why RAM price is a candidate economic indicator

- **Structural:** DRAM is a near-pure commodity with elastic pricing set by a 3-firm oligopoly operating 18–24 month capex cycles. Price transmits capex decisions (a strategic signal) and aggregate IT demand (a cyclical signal) in near-real-time.
- **Observed correlations:** Each major US recession since 1990 is visible in the DRAM ASP series — 1990–91 (mild dip), 2001 (collapse), 2008–09 (collapse), 2020 (brief wobble followed by surge), and the 2022–23 crash which preceded the disinflation cycle.
- **Lead/lag properties:** DRAM spot pricing is widely used by sell-side analysts as a *leading* indicator of enterprise IT capex and a *coincident* indicator of consumer electronics demand. Because capex decisions at Samsung / SK Hynix / Micron are made 12–18 months before shipment, price inflection points precede visible demand changes.
- **Measurement caveats:** (1) contract ≠ spot pricing; spot is noisier but more responsive. (2) Generation transitions (DDR3→4→5, HBM) create compositional breaks. (3) Quality-adjusted (constant-performance) series differ materially from nominal $/GB — the Fed FEDS 2006‑44 paper argues constant-quality declines are steeper than nominal.

## 6. Bibliography (selected)

1. McCallum, J. C. *Memory Prices 1957‑2024.* [jcmit.net/memoryprice.htm](https://jcmit.net/memoryprice.htm).
2. Hennessy, J. & Patterson, D. *Computer Architecture: A Quantitative Approach*, 6e. Morgan Kaufmann, 2019. (Tables B.1–B.5 reproduce McCallum.)
3. AI Impacts. "Trends in DRAM price per gigabyte." [aiimpacts.org/trends-in-dram-price-per-gigabyte](https://aiimpacts.org/trends-in-dram-price-per-gigabyte/). 2020, updated 2023.
4. Aizcorbe, A., Oliner, S. D., Sichel, D. E. "Shifting Trends in Semiconductor Prices and the Pace of Technological Progress." FEDS 2006‑44, Board of Governors of the Federal Reserve System. [federalreserve.gov/pubs/feds/2006/200644](https://www.federalreserve.gov/pubs/feds/2006/200644/index.html).
5. U.S. Department of Commerce / SIA. "Findings: Japanese DRAM Dumping." 1986.
6. Flamm, K. *Mismanaged Trade? Strategic Policy and the Semiconductor Industry.* Brookings, 1996.
7. TrendForce / DRAMeXchange. *DRAM Price Trends*, 2000–2026. [trendforce.com/price/dram](https://www.trendforce.com/price/dram/dram_spot).
8. Tedium. "1988: The Year of the RAM Drought." [tedium.co/2016/11/24/1988-ram-shortage-history](https://tedium.co/2016/11/24/1988-ram-shortage-history/).
9. NoobFeed. "How Samsung, Micron, and SK Hynix Built Dominance After the DRAM Cartel Scandal." [noobfeed.com/articles/samsung-micron-hynix-dram-cartel](https://www.noobfeed.com/articles/samsung-micron-hynix-dram-cartel).
10. Lapedus, M. "SK Hynix Surpasses Samsung in DRAM Share." Semiecosystem, 2025. [marklapedus.substack.com/p/sk-hynix-surpasses-samsung-in-dram](https://marklapedus.substack.com/p/sk-hynix-surpasses-samsung-in-dram).
11. hblok.net. *Historical cost of computer memory and storage.* [hblok.net/blog/storage](https://hblok.net/blog/storage/).

## 7. CSV (for dashboard)

```csv
year,usd_per_mb,usd_per_gb,note
1980,6480,6635520,16kb DRAM NMOS
1981,4479,4586496,16/64kb transition
1982,2027,2075648,64kb DRAM
1983,685,701440,64kb DRAM
1984,451,461824,64/256kb
1985,385,394240,256kb Japanese dumping
1986,178,182272,post-dumping crash
1987,133,136192,sanctions lifted late year
1988,107,109568,RAM drought
1989,73,74752,1Mb DRAM
1990,47,48128,
1991,42,43008,
1992,39,39936,
1993,34,34816,
1994,32,32768,
1995,30,30720,4-16Mb modules
1996,6.9,7065.6,oversupply crash
1997,4.1,4198.4,
1998,1.38,1413.12,
1999,1.13,1157.12,
2000,1.05,1075.2,DDR1 emerging
2001,0.23,235.52,dot-com bust
2002,0.16,163.84,
2003,0.19,194.56,
2004,0.19,194.56,DDR2
2005,0.13,133.12,
2006,0.16,163.84,
2007,0.11,112.64,DDR3 launch
2008,0.039,39.936,GFC crash
2009,0.024,24.576,
2010,0.012,12.288,
2011,0.0078,7.9872,Elpida bankruptcy
2012,0.0044,4.5056,Big Three complete
2013,0.0055,5.632,supercycle begins
2014,0.0069,7.0656,
2015,0.0047,4.8128,
2016,0.0030,3.072,
2017,0.0053,5.4272,supercycle peak
2018,0.0082,8.3968,
2019,0.0035,3.584,post-supercycle crash
2020,0.0035,3.584,COVID demand surge
2021,0.0036,3.6864,
2022,0.0030,3.072,server glut crash
2023,0.0018,1.8432,cycle bottom
2024,0.0029,2.9696,AI/HBM recovery
2025,0.0041,4.1984,AI memory supercycle
2026,0.0052,5.3248,DDR4 all-time-high Q1
```
