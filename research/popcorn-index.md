# Buttered Popcorn Index — research notes

## 1. Origin

There is no single coiner; the Buttered Popcorn Index is a **folk indicator** popularised by entertainment-trade journalism (Variety, The Hollywood Reporter) and cited repeatedly by the **National Association of Theatre Owners (NATO)**. Its canonical frame:

> *In recessions people trade down from pricey leisure to cheap leisure; cinema attendance (and concessions) therefore rises.*

Historical roots: Hollywood's **1930s golden age**. During the Great Depression, **~60–80 million Americans per week** attended the cinema, out of a population of ~125 million — the highest weekly penetration ever recorded. *Gone with the Wind* (1939) remains the all-time inflation-adjusted #1 domestic release.

## 2. Empirical record

| Period | Box office behaviour | Verdict |
|--------|---------------------|---------|
| 1930s | Attendance explodes despite Depression | ✅ founding evidence |
| 1973–74 bear market | Attendance uptick; NYT (Jan 1975) notes **$1.9 B record box office in '74** | ✅ |
| 1981–82 recession | Attendance rises; *E.T.* (1982) | ✅ |
| 2001 (dot-com + 9/11) | Admissions rose 4.8 %; *Shrek*, *LOTR* | ✅ |
| **2008–09 GFC** | **Box office +17.5 % to $1.7 B in early 2009**; attendance +16 %; *Paul Blart: Mall Cop*, *Bride Wars* the era's unlikely hits (New Yorker "Recession-Proof" 2009; Rolling Stone 2009; Guardian "Moviegoers set US box office record in effort to escape recessionary gloom" Feb 2009) | ✅ cleanest modern test |
| **2020 COVID** | **Domestic box office collapsed from $11.4 B (2019) → $2.1 B** as theatres closed. Streaming replaced cinema entirely. | ❌ structural break |
| 2021 | $4.5 B rebound | — |
| 2022 | $7.4 B — *Top Gun: Maverick* | Recovery |
| 2023 | $8.9 B — *Barbie*/*Oppenheimer* "Barbenheimer" | No longer recession-correlated |

## 3. Why concessions matter

Theatres earn most of their profit from concessions, not tickets. NATO reports **per-cap concessions** as the real margin line. Popcorn in particular has **~85 % gross margin** and is cited by NATO as the "keystone" of theatre economics.

## 4. Criticisms

- **Trailing, not leading** — box office moves *in response to* a recession, not ahead of it.
- **Streaming break** — post-2020 the indicator is structurally compromised; Netflix/Disney+ subscription behaviour is now the better proxy ("Streaming Index").
- **Content dependence** — a single tentpole (Barbie, Avatar) can swamp macro signal.
- **No peer-reviewed validation** — there is one recent serious academic treatment: Oz, S. (2023), "Is it time for popcorn? Daily box office earnings and aggregate stock returns," *Financial Management* 52(3). It finds limited predictive value after controlling for seasonality.

## 5. Quantitative series — US domestic box office

From **Box Office Mojo** ([boxofficemojo.com/year](https://www.boxofficemojo.com/year/)):

| Year | Total Gross ($B) | #1 Release |
|------|-----------------:|-----------|
| 2008 | 9.65 | The Dark Knight |
| 2009 | 10.62 | Transformers: ROTF |
| 2010 | 10.59 | Avatar |
| 2011 | 10.16 | Harry Potter 7.2 |
| 2012 | 10.84 | The Avengers |
| 2013 | 10.96 | Iron Man 3 |
| 2014 | 10.37 | Guardians |
| 2015 | 11.15 | Jurassic World |
| 2016 | 11.38 | Finding Dory |
| 2017 | 11.08 | Last Jedi |
| 2018 | 11.89 | Black Panther |
| 2019 | 11.36 | Endgame |
| 2020 | 2.11 | Bad Boys for Life |
| 2021 | 4.48 | Spider-Man: NWH |
| 2022 | 7.37 | Top Gun: Maverick |
| 2023 | 8.91 | Barbie |
| 2024 | 8.57 | Inside Out 2 |
| 2025 | 8.66 | A Minecraft Movie |

## 6. Bibliography

- Oz, S. (2023). "Is it time for popcorn? Daily box office earnings and aggregate stock returns." *Financial Management*, 52(3). [Wiley Online Library](https://onlinelibrary.wiley.com/doi/10.1111/fima.12408).
- National Association of Theatre Owners (NATO). *State of the Industry* annual reports. [natoonline.org](https://natoonline.org).
- MPAA / MPA THEME Reports (annual).
- Box Office Mojo (IMDbPro). [boxofficemojo.com/year/](https://www.boxofficemojo.com/year/).
- The Numbers. *Movie Market Summary 1995–2026.* [the-numbers.com/market](https://www.the-numbers.com/market/).
- *The New York Times* (January 1975). "Film Box-Office Receipts in '74 a Record $1.9 Billion."
- *The New Yorker* (January 2009). "Recession-Proof: Paul Blart Edition."
- *Rolling Stone* (January 2009). "Bride Wars."
- *The Guardian* (February 2009). "Moviegoers set US box office record in effort to escape recessionary gloom."
- RBC Direct Investing. "The Lipstick Index and Other Weird Economic Indicators." [rbcdirectinvesting.com](https://www.rbcdirectinvesting.com/learn/en/di/hubs/level-up/article/lipstick-index/mhe2qyih).
- *The Ringer* (November 2018). "Box Office Bomb: The Short Life of Popcorn Prediction Markets."

## 7. CSV

```csv
year,us_domestic_box_office_b_usd,note
1980,1.64,Empire Strikes Back
1985,3.75,Back to the Future
1990,5.02,
1995,5.29,
2000,7.48,
2001,8.35,post-9/11 uptick
2002,9.16,
2003,9.24,
2004,9.38,
2005,8.84,
2006,9.21,
2007,9.63,
2008,9.65,early GFC
2009,10.62,GFC peak +10%
2010,10.59,
2011,10.16,
2012,10.84,
2013,10.96,
2014,10.37,
2015,11.15,
2016,11.38,
2017,11.08,
2018,11.89,all-time high
2019,11.36,
2020,2.11,COVID collapse
2021,4.48,
2022,7.37,recovery
2023,8.91,Barbenheimer
2024,8.57,
2025,8.66,
2026,2.31,YTD partial
```
