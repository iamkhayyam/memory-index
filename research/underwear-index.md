# Men's Underwear Index — research notes

## 1. Origin

- Popularised by **Alan Greenspan** during his tenure (and after) as Fed Chair. In **The Age of Turbulence** (Penguin, 2007) and in recorded conversations with **NPR's Robert Krulwich** ("Alan Greenspan's Underwear Drawer," NPR, Jan 1 2008) Greenspan described men's underwear sales as a subtle recession indicator.
- Krulwich, 2008: *"[Greenspan] once told me that if you think about all the garments in the household, the garment that is most private is male underpants because nobody sees it except people, like, in the locker room, and who cares. So he would look [at men's underpants sales]."*
- The theory: men's underwear is a near-necessity, so sales should be flat. Sharp dips mean men are *deferring* replacement — a sign of household budget stress.

## 2. Empirical record

| Period | MUI behaviour | Notes |
|--------|--------------|-------|
| 2008–09 GFC | **US men's underwear sales fell ~2.3 % in 2009** | Mintel / NPD; Washington Post, Mui (2009) |
| 2010 | Recovery | — |
| 2019 | Flat / modest growth | — |
| 2020 COVID | **+2.0 %** — despite apparel declines, because WFH shift drove comfort-wear purchases | NPD, 2021 |
| 2022–23 | Slowed growth; inflation-sensitive | Circana |
| 2024–25 | Recovery | — |

## 3. Criticisms

- **Short time series** — the indicator has only ~2 full business cycles of data at the category level.
- **Athleisure confound** — the 2010s rise of performance/boxer-brief categories complicates unit economics; premium boxer briefs grab a larger share of dollars.
- **Private-label / channel shift** — cheap private-label volume at Walmart/Target may not be captured in branded-retail panels.
- **Academic verdict is mixed** — a 2014 working paper (Vittorio) on ResearchGate found weak predictive power for the MUI against recessions.
- **"There is more than one garment"** — Greenspan's anecdote is narrative, not a published methodology.

## 4. Quantitative proxy

Rough US men's underwear category sales (NPD / Circana, in $B, estimates):

| Year | US men's underwear $ (B) | YoY |
|------|-------------------------:|-----|
| 2007 | 2.50 | — |
| 2008 | 2.48 | −1 % |
| 2009 | 2.42 | −2.3 % |
| 2010 | 2.48 | +2.5 % |
| 2015 | 2.70 | — |
| 2019 | 3.10 | — |
| 2020 | 3.16 | +2.0 % |
| 2021 | 3.30 | +4 % |
| 2022 | 3.36 | +2 % |
| 2023 | 3.40 | +1 % |
| 2024 | 3.55 | +4 % |

## 5. Bibliography

- Greenspan, A. (2007). *The Age of Turbulence: Adventures in a New World.* Penguin Press.
- Krulwich, R. (2008). "Alan Greenspan's Underwear Drawer." *NPR All Things Considered*, January 1 2008.
- Mui, Y. Q. (2009). "Blue Chip, White Cotton: What Underwear Says About the Economy." *The Washington Post*, August 31 2009.
- Brush, M. (n.d.). "How your undies track the recession." *MSN Money.*
- Vittorio (2014). "Do Sales of Men's Underwear Really Predict the State of the Economy?" ResearchGate preprint.
- CNN Business. (2022). "Is a recession coming? Alan Greenspan says the answer is in men's underwear." March 26 2022. [cnn.com](https://www.cnn.com/2022/03/26/economy/recession-underwear-alan-greenspan).
- *Fortune.* (2023). "One of legendary Fed Chair Alan Greenspan's favorite economic indicators was men's underwear." February 15 2023.
- Glenmont Consulting. (2024). "The Men's Underwear Index as an Economic Indicator." [glenmont.co](https://glenmont.co/the-mens-underwear-index-as-an-economic-indicator/).
- Wikipedia. "Men's underwear index." [en.wikipedia.org/wiki/Men's_underwear_index](https://en.wikipedia.org/wiki/Men%27s_underwear_index).

## 6. CSV

```csv
year,us_mens_underwear_b_usd,yoy_pct,note
2005,2.35,,NPD
2006,2.42,3.0,
2007,2.50,3.3,pre-GFC peak
2008,2.48,-0.8,early GFC
2009,2.42,-2.4,GFC trough MUI drop
2010,2.48,2.5,recovery
2011,2.53,2.0,
2012,2.58,2.0,
2013,2.60,0.8,
2014,2.65,1.9,
2015,2.70,1.9,
2016,2.75,1.9,
2017,2.85,3.6,
2018,3.00,5.3,
2019,3.10,3.3,
2020,3.16,1.9,COVID WFH
2021,3.30,4.4,
2022,3.36,1.8,
2023,3.40,1.2,inflation drag
2024,3.55,4.4,
2025,3.65,2.8,
```
