### Roster Details<br />
Team Name: Team Space<br />
Roster: danistzz, fozil, TruNiQ, Vert, X5G7V<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [78](../standings_global.md)<br />
Regional Rank: [54]( ../standings_europe.md)<br />
Final Rank Value:  908.3<br />
<br />
Final Rank Value (908.3) = Starting Rank Value (851.0) + Head To Head Adjustments (57.3)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.330[<sup>1</sup>](#table2)
- Bounty Collected: 0.327[<sup>2</sup>](#table1)
- Opponent Network: 0.229[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.222<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 851.0
- 400 + ( ( 0.222 - 0.000 ) / ( 0.786 - 0.000 ) ) * 1600 = 851.0


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent           | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                  |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           41 |      259 | 2024-05-25 | 9Pandas            | L   | 1.000      | -            | -                | -                | -         |    -8.09 | danistzz, fozil, TruNiQ, Vert, X5G7V    |
|           40 |      420 | 2024-05-23 | Metizport          | W   | 1.000      | 0.435        | 0.088 (0.038)    | 0.698 (0.303)    | 0 (0.000) |    22.44 | danistzz, fozil, TruNiQ, Vert, X5G7V    |
|           39 |      577 | 2024-05-21 | System5            | W   | 1.000      | 0.500        | 0.002 (0.001)    | -                | 0 (0.000) |     7.95 | danistzz, fozil, TruNiQ, Vert, X5G7V    |
|           38 |      743 | 2024-05-19 | DMS                | W   | 1.000      | 0.435        | -                | 0.751 (0.326)    | 0 (0.000) |    17.57 | danistzz, fozil, TruNiQ, Vert, X5G7V    |
|           37 |      803 | 2024-05-19 | LEON Esports       | W   | 1.000      | 0.143        | -                | 0.564 (0.081)    | 0 (0.000) |     9.43 | danistzz, fozil, TruNiQ, Vert, X5G7V    |
|           36 |      933 | 2024-05-18 | Verdant            | W   | 1.000      | 0.435        | 0.014 (0.006)    | 1.000 (0.435)    | 0 (0.000) |    19.14 | danistzz, fozil, TruNiQ, Vert, X5G7V    |
|           35 |     1015 | 2024-05-17 | 777 Esports        | L   | 1.000      | -            | -                | -                | -         |   -18.78 | danistzz, fozil, TruNiQ, Vert, X5G7V    |
|           34 |     1060 | 2024-05-16 | GUN5 Esports       | L   | 1.000      | -            | -                | -                | -         |   -20.62 | danistzz, fozil, TruNiQ, Vert, X5G7V    |
|           33 |     1167 | 2024-05-15 | RoundsGG           | W   | 1.000      | -            | -                | -                | 0 (0.000) |     4.59 | danistzz, fozil, TruNiQ, Vert, X5G7V    |
|           32 |     1209 | 2024-05-15 | Nexus Gaming       | W   | 1.000      | 0.435        | 0.014 (0.006)    | 0.825 (0.358)    | 0 (0.000) |    14.80 | danistzz, fozil, TruNiQ, Vert, X5G7V    |
|           31 |     1253 | 2024-05-14 | EYEBALLERS         | W   | 1.000      | 0.500        | 0.012 (0.006)    | 0.508 (0.254)    | 0 (0.000) |    19.54 | danistzz, fozil, TruNiQ, Vert, X5G7V    |
|           30 |     1335 | 2024-05-13 | MOUZ NXT           | L   | 1.000      | -            | -                | -                | -         |    -7.67 | danistzz, fozil, TruNiQ, Vert, X5G7V    |
|           29 |     1374 | 2024-05-12 | Insilio            | W   | 1.000      | 0.143        | 0.010 (0.001)    | 0.717 (0.102)    | 0 (0.000) |    20.69 | danistzz, fozil, TruNiQ, Vert, X5G7V    |
|           28 |     1473 | 2024-05-11 | Viperio            | W   | 1.000      | 0.143        | -                | 0.285 (0.041)    | 0 (0.000) |    14.20 | danistzz, fozil, TruNiQ, Vert, X5G7V    |
|           27 |     1530 | 2024-05-10 | EXO Clan           | W   | 1.000      | 0.143        | 0.013 (0.002)    | 0.510 (0.073)    | -         |    19.64 | danistzz, fozil, TruNiQ, Vert, X5G7V    |
|           26 |     1692 | 2024-05-07 | Heimo Esports      | W   | 1.000      | 0.143        | 0.011 (0.002)    | -                | -         |    14.76 | danistzz, fozil, TruNiQ, Vert, X5G7V    |
|           25 |     1733 | 2024-05-06 | CYBERSHOKE Esports | L   | 1.000      | -            | -                | -                | -         |   -21.71 | danistzz, fozil, TruNiQ, Vert, X5G7V    |
|           24 |     2212 | 2024-04-27 | FORZE Youngsters   | W   | 0.982      | -            | -                | -                | -         |     2.89 | danistzz, fozil, TruNiQ, Vert, X5G7V    |
|           23 |     2324 | 2024-04-25 | ALTERNATE aTTaX    | L   | 0.969      | -            | -                | -                | -         |   -11.23 | danistzz, fozil, TruNiQ, Vert, X5G7V    |
|           22 |     2357 | 2024-04-24 | Zero Tenacity      | L   | 0.964      | -            | -                | -                | -         |    -7.80 | danistzz, fozil, TruNiQ, Vert, X5G7V    |
|           21 |     2565 | 2024-04-20 | ALTERNATE aTTaX    | W   | 0.937      | 0.500        | 0.052 (0.024)    | 0.679 (0.318)    | -         |    19.61 | danistzz, fozil, TruNiQ, Vert, X5G7V    |
|           20 |     3395 | 2024-04-06 | ARCRED             | L   | 0.843      | -            | -                | -                | -         |   -13.91 | danistzz, fluffy, fozil, TruNiQ, Vert   |
|           19 |     4982 | 2024-03-04 | ex-Sprout          | L   | 0.625      | -            | -                | -                | -         |   -13.99 | enzero, fozil, TruNiQ, Vert, waterfaLLZ |
|           18 |     5006 | 2024-03-04 | 1win Academy       | W   | 0.625      | -            | -                | -                | -         |     4.64 | enzero, fozil, TruNiQ, Vert, waterfaLLZ |
|           17 |     5140 | 2024-03-02 | UNiTY esports      | L   | 0.611      | -            | -                | -                | -         |    -9.15 | enzero, fozil, TruNiQ, Vert, waterfaLLZ |
|           16 |     5404 | 2024-02-26 | INGLORIOUS         | L   | 0.578      | -            | -                | -                | -         |   -10.40 | enzero, fozil, TruNiQ, Vert, waterfaLLZ |
|           15 |     6780 | 2024-01-29 | 3DMAX              | L   | 0.392      | -            | -                | -                | -         |    -4.33 | enzero, fozil, leri511, TruNiQ, Vert    |
|           14 |     6792 | 2024-01-29 | K10                | W   | 0.392      | -            | -                | -                | -         |     0.93 | enzero, fozil, leri511, TruNiQ, Vert    |
|           13 |     7530 | 2024-01-17 | 500                | L   | 0.311      | -            | -                | -                | -         |    -5.86 | enzero, fozil, leri511, TruNiQ, Vert    |
|           12 |     7545 | 2024-01-17 | Astra Gaming       | W   | 0.311      | -            | -                | -                | -         |     0.74 | enzero, fozil, leri511, TruNiQ, Vert    |
|           11 |     7790 | 2024-01-13 | 500                | L   | 0.283      | -            | -                | -                | -         |    -5.46 | enzero, fozil, leri511, TruNiQ, Vert    |
|           10 |     7824 | 2024-01-12 | ARCRED             | W   | 0.279      | -            | -                | -                | -         |     3.53 | enzero, fozil, leri511, TruNiQ, Vert    |
|            9 |     7830 | 2024-01-12 | HyperSpirit        | W   | 0.278      | -            | -                | -                | -         |     3.25 | enzero, fozil, leri511, TruNiQ, Vert    |
|            8 |     7933 | 2024-01-11 | IKLA               | L   | 0.270      | -            | -                | -                | -         |    -6.97 | enzero, fozil, leri511, TruNiQ, Vert    |
|            7 |     7944 | 2024-01-11 | Soda Gaming        | W   | 0.270      | -            | -                | -                | -         |     1.94 | enzero, fozil, leri511, TruNiQ, Vert    |
|            6 |     7993 | 2024-01-10 | ThunderFlash       | W   | 0.265      | 0.143        | 0.012 (0.000)    | -                | -         |     4.02 | enzero, fozil, leri511, TruNiQ, Vert    |
|            5 |     8017 | 2024-01-10 | GenOne             | W   | 0.265      | -            | -                | -                | -         |     1.17 | enzero, fozil, leri511, TruNiQ, Vert    |
|            4 |     8132 | 2024-01-09 | Nexus Gaming       | L   | 0.257      | -            | -                | -                | -         |    -3.33 | enzero, fozil, leri511, TruNiQ, Vert    |
|            3 |     9219 | 2023-12-06 | FORZE Esports      | L   | 0.031      | -            | -                | -                | -         |    -0.69 | enzero, fozil, leri511, TruNiQ, Vert    |
|            2 |     9290 | 2023-12-05 | Apeks              | L   | 0.024      | -            | -                | -                | -         |    -0.08 | enzero, fozil, leri511, TruNiQ, Vert    |
|            1 |     9491 | 2023-12-02 | ALTERNATE aTTaX    | L   | 0.003      | -            | -                | -                | -         |    -0.06 | enzero, fozil, leri511, TruNiQ, Vert    |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($2,816.25)
- Divide that value by the 5th highest value among all rosters ($300,806.11)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-05-26 |      1.000 | $2,000.00      | $2,000.00       |
| 2024-05-22 |      1.000 | $500.00        | $500.00         |
| 2023-12-10 |      0.058 | $5,500.00      | $316.25         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
