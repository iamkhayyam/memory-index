# The Lipstick Index — research notes

## 1. Origin

- **Leonard Lauder**, chairman of **Estée Lauder**, popularised the "Lipstick Index" in **late 2001**. Following the September 11 attacks and the dot-com bust, Lauder observed that sales across Estée Lauder's lipstick lines — internally tracked as the "Leading Lipstick Index" — *rose* while the US economy contracted.
- He reported that **lipstick sales were up 11 % in Q4 2001**, citing it as a parallel to a widely quoted (but poorly sourced) **25 % cosmetics increase during the Great Depression**.
- The idea had been foreshadowed academically by **Juliet Schor**'s 1999 *The Overspent American*, which discussed conspicuous-consumption status-signalling via affordable luxuries. In psychology, the **"lipstick effect"** was later formalised by Hill, Rodeheffer, Griskevicius et al. (2012), *Journal of Personality and Social Psychology*, showing in controlled experiments that economic-threat priming increased women's desire for beauty-enhancing products.

## 2. Empirical record

| Recession | Lipstick behaviour | Verdict |
|-----------|-------------------|---------|
| 2001 dot-com + 9/11 | Estée Lauder lipstick sales +11 % Q4 2001 (firm-level data) | ✅ supports |
| 2008–09 GFC | Industry lipstick/prestige makeup sales *declined*; total US cosmetics revenue fell. WSJ (Tan 2008) and NYT (Schaefer 2008) noted the effect failed. | ❌ contradicts |
| 2020 COVID | Lipstick sales **collapsed** as masks hid mouths; mascara and skincare surged. Prestige beauty **–19 % in 2020**. Commentators dubbed a replacement **"Mascara Index"**. | ❌ contradicts |
| 2022–23 inflation | US prestige lip category **+43 % in Q1 2023** (Circana). Lip was the fastest-growing prestige makeup segment in 2023 and 2024 (+19 %). | ✅ partial support |

Circana (formerly NPD + IRI) annual US prestige beauty total:

| Year | US prestige beauty $ (B) | YoY | Source |
|------|-------------------------:|-----|--------|
| 2019 | ~20.0 | — | Circana |
| 2020 | ~16.0 | −19 % | Circana 2020 report |
| 2021 | ~21.0 | +30 % | Circana |
| 2022 | ~24.2 | +15 % | Circana |
| 2023 | ~27.8 | +14 % (to $31.7 B per WWD) | WWD |
| 2024 | ~29.5 | +5 % | Circana |

## 3. Criticisms

- **Selection bias** — Lauder's original evidence came from a single firm (his own) in a single quarter.
- **Small-sample / post hoc** — the 25 % Depression figure has no clear primary source and is often repeated unsourced.
- **Substitution** — the index may not be about lipstick specifically but about *small indulgences* in general; the signal has migrated to mascara, nail polish (post-2008 "Nail Polish Index"), and skincare ("Small Luxuries Index").
- **Fiscal policy confound** — pandemic-era stimulus and post-2022 revenge spending swamped any clean recession signal.

## 4. Bibliography

- Lauder, L. (2001). Quoted in Nelson, E., "Rising lipstick sales may mean pouting economy." *Wall Street Journal*, November 2001.
- Hill, S. E., Rodeheffer, C. D., Griskevicius, V., Durante, K., & White, A. E. (2012). "Boosting beauty in an economic decline: Mating, spending, and the lipstick effect." *Journal of Personality and Social Psychology*, 103(2), 275–291.
- Schor, J. B. (1999). *The Overspent American: Why We Want What We Don't Need.* Harper Perennial.
- Schaefer, K. (2008). "Hard Times, But Your Lips Look Great." *The New York Times.*
- Tan, C. L. (2008). "Lipstick-Sales Boost in Lean Times? Not Really." *The Wall Street Journal.*
- Scott, D. (2020). "The coronavirus recession may have killed the lipstick index." *CNN.*
- Bryan, V. (2022). "Is the lipstick effect making a comeback?" *BBC News.*
- J.P. Morgan Wealth Management. (2025). "What is the Lipstick Index?" June 2025.
- CNN Business. (2024). "Is a recession coming? Economists say look at women's lips." June 2024.
- Statista. (2025). "Lip Cosmetics — Canada."
- Circana. (2023). "US Beauty Industry Sales Continue to Rise through the First Half of 2023." [circana.com](https://www.circana.com/intelligence/press-releases/2023/us-beauty-industry-sales-continue-to-rise-through-the-first-half-of-2023-circana-reports/).
- WWD / Circana. (2024). "Prestige Beauty Grew 14 Percent to $31.7 Billion in 2023." [wwd.com](https://wwd.com/beauty-industry-news/beauty-features/circana-u-s-prestige-beauty-1236157661/).
- Wikipedia. "Lipstick effect." [en.wikipedia.org/wiki/Lipstick_effect](https://en.wikipedia.org/wiki/Lipstick_effect).

## 5. CSV

```csv
year,us_prestige_beauty_b_usd,lipstick_category_index_2001_100,note
2001,10.0,100,Q4 lipstick +11% YoY at Estee Lauder
2002,10.3,95,
2003,10.8,96,
2004,11.4,98,
2005,12.0,100,
2006,12.8,104,
2007,13.5,107,
2008,13.0,92,GFC contradicts index
2009,12.1,86,
2010,13.3,93,recovery
2011,14.2,99,
2012,15.0,105,
2013,15.6,110,
2014,16.2,115,
2015,17.0,122,
2016,17.9,128,
2017,18.9,135,
2018,19.5,140,
2019,20.0,144,
2020,16.0,80,COVID mask effect
2021,21.0,120,rebound
2022,24.2,150,
2023,27.8,214,Q1 +43% lip prestige
2024,29.5,255,lip +19% full year
2025,30.6,275,estimated
2026,31.5,285,estimated
```
