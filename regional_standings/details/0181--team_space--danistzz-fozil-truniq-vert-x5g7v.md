### Roster Details<br />
Team Name: Team Space<br />
Roster: danistzz, fozil, TruNiQ, Vert, X5G7V<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [181](../standings_global.md)<br />
Regional Rank: [123]( ../standings_europe.md)<br />
Final Rank Value:  742.5<br />
<br />
Final Rank Value (742.5) = Starting Rank Value (740.2) + Head To Head Adjustments (2.3)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.325[<sup>1</sup>](#table2)
- Bounty Collected: 0.310[<sup>2</sup>](#table1)
- Opponent Network: 0.050[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.171<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 740.2
- 400 + ( ( 0.171 - 0.000 ) / ( 0.806 - 0.000 ) ) * 1600 = 740.2


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent                    | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins      | H2H Adj. | Roster                                  |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           35 |      387 | 2024-04-27 | FORZE Youngsters            | W   | 1.000      | -            | -                | -                | false (0.000) |     3.91 | danistzz, fozil, TruNiQ, Vert, X5G7V    |
|           34 |      487 | 2024-04-25 | ALTERNATE aTTaX             | L   | 1.000      | -            | -                | -                | -             |    -9.38 | danistzz, fozil, TruNiQ, Vert, X5G7V    |
|           33 |      514 | 2024-04-24 | Zero Tenacity               | L   | 1.000      | -            | -                | -                | -             |    -7.41 | danistzz, fozil, TruNiQ, Vert, X5G7V    |
|           32 |      700 | 2024-04-20 | ALTERNATE aTTaX             | W   | 1.000      | 0.500        | 0.110 (0.055)    | 0.723 (0.362)    | false (0.000) |    23.19 | danistzz, fozil, TruNiQ, Vert, X5G7V    |
|           31 |     1403 | 2024-04-06 | ARCRED                      | L   | 1.000      | -            | -                | -                | -             |   -12.40 | danistzz, fluffy, fozil, TruNiQ, Vert   |
|           30 |     2738 | 2024-03-04 | 1win                        | W   | 0.786      | 0.143        | 0.002 (0.000)    | 0.264 (0.030)    | false (0.000) |    14.05 | enzero, fozil, TruNiQ, Vert, waterfaLLZ |
|           29 |     2843 | 2024-03-02 | UNiTY esports (Slovak team) | L   | 0.772      | -            | -                | -                | -             |    -8.49 | enzero, fozil, TruNiQ, Vert, waterfaLLZ |
|           28 |     3065 | 2024-02-26 | INGLORIOUS                  | L   | 0.739      | -            | -                | -                | -             |    -8.71 | enzero, fozil, TruNiQ, Vert, waterfaLLZ |
|           27 |     4157 | 2024-01-29 | 3DMAX                       | L   | 0.553      | -            | -                | -                | -             |    -4.02 | enzero, fozil, leri511, TruNiQ, Vert    |
|           26 |     4168 | 2024-01-29 | En av de lette              | W   | 0.553      | 0.143        | 0.020 (0.002)    | 0.129 (0.010)    | false (0.000) |     8.92 | enzero, fozil, leri511, TruNiQ, Vert    |
|           25 |     4709 | 2024-01-17 | 500                         | L   | 0.473      | -            | -                | -                | -             |    -6.26 | enzero, fozil, leri511, TruNiQ, Vert    |
|           24 |     4722 | 2024-01-17 | Astra Gaming                | W   | 0.472      | -            | -                | -                | false (0.000) |     1.85 | enzero, fozil, leri511, TruNiQ, Vert    |
|           23 |     4892 | 2024-01-13 | 500                         | L   | 0.444      | -            | -                | -                | -             |    -6.08 | enzero, fozil, leri511, TruNiQ, Vert    |
|           22 |     4917 | 2024-01-12 | ARCRED                      | W   | 0.440      | 0.143        | 0.004 (0.000)    | 0.825 (0.052)    | false (0.000) |     8.66 | enzero, fozil, leri511, TruNiQ, Vert    |
|           21 |     4921 | 2024-01-12 | HyperSpirit                 | W   | 0.439      | 0.143        | 0.009 (0.001)    | 0.293 (0.018)    | false (0.000) |     6.79 | enzero, fozil, leri511, TruNiQ, Vert    |
|           20 |     4994 | 2024-01-11 | IKLA                        | L   | 0.432      | -            | -                | -                | -             |    -7.14 | enzero, fozil, leri511, TruNiQ, Vert    |
|           19 |     5003 | 2024-01-11 | Soda Gaming                 | W   | 0.431      | 0.143        | 0.009 (0.001)    | 0.182 (0.011)    | false (0.000) |     7.39 | enzero, fozil, leri511, TruNiQ, Vert    |
|           18 |     5053 | 2024-01-10 | GenOne                      | W   | 0.426      | 0.143        | 0.000 (0.000)    | 0.035 (0.002)    | false (0.000) |     4.88 | enzero, fozil, leri511, TruNiQ, Vert    |
|           17 |     5123 | 2024-01-09 | Nexus Gaming                | L   | 0.418      | -            | -                | -                | -             |    -3.67 | enzero, fozil, leri511, TruNiQ, Vert    |
|           16 |     5929 | 2023-12-06 | FORZE Esports               | L   | 0.192      | -            | -                | -                | -             |    -2.59 | enzero, fozil, leri511, TruNiQ, Vert    |
|           15 |     5986 | 2023-12-05 | Apeks                       | L   | 0.185      | -            | -                | -                | -             |    -0.13 | enzero, fozil, leri511, TruNiQ, Vert    |
|           14 |     6122 | 2023-12-02 | ALTERNATE aTTaX             | L   | 0.164      | -            | -                | -                | -             |    -0.69 | enzero, fozil, leri511, TruNiQ, Vert    |
|           13 |     6162 | 2023-12-01 | SAW                         | L   | 0.158      | -            | -                | -                | -             |    -0.07 | enzero, fozil, leri511, TruNiQ, Vert    |
|           12 |     6768 | 2023-11-17 | Into The Breach             | L   | 0.065      | -            | -                | -                | -             |    -0.84 | enzero, fozil, leri511, TruNiQ, Vert    |
|           11 |     6806 | 2023-11-16 | KOI                         | L   | 0.059      | -            | -                | -                | -             |    -0.28 | enzero, fozil, leri511, TruNiQ, Vert    |
|           10 |     6830 | 2023-11-16 | FORZE Esports               | L   | 0.058      | -            | -                | -                | -             |    -0.81 | enzero, fozil, leri511, TruNiQ, Vert    |
|            9 |     6852 | 2023-11-16 | Guild Eagles                | W   | 0.056      | 0.435        | 0.037 (0.001)    | 0.586 (0.014)    | false (0.000) |     1.47 | enzero, fozil, leri511, TruNiQ, Vert    |
|            8 |     6863 | 2023-11-15 | FORZE Esports               | L   | 0.052      | -            | -                | -                | -             |    -0.73 | enzero, fozil, leri511, TruNiQ, Vert    |
|            7 |     6878 | 2023-11-15 | TEAM ZOO BAR                | W   | 0.052      | -            | -                | -                | -             |     0.34 | enzero, fozil, leri511, TruNiQ, Vert    |
|            6 |     6987 | 2023-11-13 | The Witchers                | W   | 0.037      | 0.435        | 0.035 (0.001)    | 0.158 (0.003)    | -             |     0.64 | enzero, fozil, leri511, TruNiQ, Vert    |
|            5 |     7082 | 2023-11-10 | ODDIK                       | L   | 0.020      | -            | -                | -                | -             |    -0.18 | enzero, fozil, leri511, TruNiQ, Vert    |
|            4 |     7085 | 2023-11-10 | ARCRED                      | L   | 0.019      | -            | -                | -                | -             |    -0.23 | enzero, fozil, leri511, TruNiQ, Vert    |
|            3 |     7087 | 2023-11-10 | ODDIK                       | W   | 0.019      | 0.143        | 0.015 (0.000)    | 0.402 (0.001)    | -             |     0.42 | enzero, fozil, leri511, TruNiQ, Vert    |
|            2 |     7107 | 2023-11-10 | 9Pandas                     | L   | 0.017      | -            | -                | -                | -             |    -0.05 | enzero, fozil, leri511, TruNiQ, Vert    |
|            1 |     7195 | 2023-11-08 | Metizport                   | L   | 0.005      | -            | -                | -                | -             |    -0.03 | enzero, fozil, leri511, TruNiQ, Vert    |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($1,341.46)
- Divide that value by the 5th highest value among all rosters ($158,437.64)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2023-12-10 |      0.219 | $5,500.00      | $1,202.11       |
| 2023-11-18 |      0.070 | $2,000.00      | $139.35         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
