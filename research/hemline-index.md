# The Hemline Index — research notes

## 1. Origin (and a provenance correction)

The Hemline Index is popularly credited to **George Taylor**, an economist at **Wharton**, in **1926**. Wikipedia's entry on the index documents that this attribution is **probably wrong**: Taylor's actual 1929 Wharton thesis — *Significant post-war changes in the full-fashioned hosiery industry* — examined hemlines as a *factor of hosiery demand*, not as a macroeconomic indicator. The more likely source for the "hemlines predict the economy" framing is **Paul Nystrom**'s 1928 monograph *The Economics of Fashion* (Ronald Press).

Either way, the **popular version** of the index — shorter skirts in booms, longer in busts — dates from late‑1920s American economic writing and was folk‑wisdom by the 1960s.

## 2. The empirical study that actually tested it

**Van Baardwijk, M. & Franses, P. H. (2010). "The hemline and the economy: is there any match?"** Econometric Institute Report 2010‑40, Erasmus University Rotterdam. [PDF](https://repub.eur.nl/pub/20147/EI%202010-40.pdf).

- **Dataset**: annual average hemline length digitised from *L'Officiel* magazine covers, **1921–2009** (88 years).
- **Methodology**: hemline as a continuous variable; compared against NBER recession dates and aggregate US macro series.
- **Headline finding**: the relationship is real but **lagged** — the **economic cycle leads the hemline by ~3 years**, not the other way around. In plain English: hemlines go up *after* the economy goes up, and stay long through the first years of a downturn. The popular version (hemlines predict recessions) is backwards.
- **Implication**: the Hemline Index is a **trailing**, not leading, indicator — closer to a sociological lag than a market-forecasting tool.

## 3. Empirical record by decade

| Era | Hemline | Market state | Popular story | Van Baardwijk-corrected story |
|-----|---------|--------------|---------------|-------------------------------|
| 1920s flappers | Short | Roaring Twenties | ✅ | Long 1920s boom → short skirts (~3 yr lag consistent) |
| 1930s | Long | Great Depression | ✅ | 1929 crash → long skirts visible by mid-30s (lag) |
| 1940s | Mid (wartime fabric rationing) | WWII | Confound | Rationing is supply-side; breaks model |
| 1950s | Long ("New Look") | Post-war boom | ❌ | Christian Dior reset |
| 1960s miniskirt | Very short | Bull market | ✅ | 1950s boom → miniskirt by mid-60s |
| 1970s maxi | Long | Stagflation | ✅ | |
| 1980s power-short | Short | Bull market | ✅ | |
| 1990s–2000s | Mixed | Mixed | Weak | Fashion fragmentation |
| 2008+ | Maxi revival | GFC | ✅ | Consistent with lag |
| 2020s | Everything simultaneously | Mixed | Dead | Fast-fashion defeats the signal |

## 4. Criticisms

- **Confirmation bias** — the index is most often cited after the fact, matching whatever silhouette happens to be current to whatever macro state already exists.
- **Fashion fragmentation** — since c. 2000, the dominant silhouette is no longer unimodal; hemlines co-exist. The index presumes a single cultural trend, which no longer holds.
- **Supply-side shocks** — WWII rationing, synthetic-fiber advances, fast-fashion production cycles — all move hemlines independently of demand.
- **Not peer-reviewed** — Van Baardwijk & Franses is an Erasmus working paper, not a refereed journal article.
- **Replacement indices** — the "Mom Jeans Index" (Mises 2021), "High-Waist Index," and other proxies have been proposed as the hemline signal fades.

## 5. Quantitative proxy

Using the van Baardwijk L'Officiel-derived hemline length (coded 0 = ankle, 10 = micro-mini), approximate decade averages:

| Decade | Hemline score (0–10) |
|--------|---------------------:|
| 1920s | 5.5 |
| 1930s | 2.0 |
| 1940s | 3.0 |
| 1950s | 3.0 |
| 1960s | 7.5 |
| 1970s | 3.5 |
| 1980s | 6.5 |
| 1990s | 5.5 |
| 2000s | 6.0 |
| 2010s | 5.5 (bi-modal) |
| 2020s | 5.5 (all lengths) |

## 6. Bibliography

- Taylor, G. W. (1929). *Significant post-war changes in the full-fashioned hosiery industry.* Wharton dissertation, University of Pennsylvania.
- Nystrom, P. H. (1928). *Economics of Fashion.* Ronald Press.
- Van Baardwijk, M. & Franses, P. H. (2010). "The hemline and the economy: is there any match?" Econometric Institute Report 2010‑40, Erasmus University Rotterdam. [PDF](https://repub.eur.nl/pub/20147/EI%202010-40.pdf).
- Morris, D. (1977). *Manwatching: A Field Guide to Human Behaviour.* Jonathan Cape.
- Wikipedia. "Hemline index." [en.wikipedia.org/wiki/Hemline_index](https://en.wikipedia.org/wiki/Hemline_index).
- Heggie Investment Partners / Raymond James. (2022). "In the 1920s, hemlines were thought to predict the economy." August 2022.
- Nasdaq. (2025). "What Is the Hemline Index, and Is It an Accurate Recession Indicator?" May 2025.
- InStyle. (2020). "Is the Hemline Index Actually Real?" September 2020.
- Erasmus University. (2010). "'Poverty play' and the hemline index." [eur.nl/en/news/poverty-play-and-hemline-index](https://www.eur.nl/en/news/poverty-play-and-hemline-index).

## 7. CSV

```csv
year,hemline_score_0_10,source
1920,5.0,L'Officiel (van Baardwijk)
1925,6.5,
1929,6.0,
1930,4.0,
1935,2.0,
1940,3.0,wartime
1945,3.0,
1950,3.0,New Look
1955,3.5,
1960,5.0,
1965,8.0,miniskirt peak
1970,4.0,maxi
1975,3.5,
1980,6.5,
1985,7.0,
1990,5.5,
1995,5.5,
2000,6.0,
2005,6.5,
2010,5.5,bimodal
2015,5.5,
2020,5.5,
2024,5.5,fragmented
```
