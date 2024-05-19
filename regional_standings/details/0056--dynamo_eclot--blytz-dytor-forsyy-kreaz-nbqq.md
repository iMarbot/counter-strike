### Roster Details<br />
Team Name: Dynamo Eclot<br />
Roster: Blytz, Dytor, forsyy, kreaz, nbqq<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [56](../standings_global.md)<br />
Regional Rank: [41]( ../standings_europe.md)<br />
Final Rank Value:  978.1<br />
<br />
Final Rank Value (978.1) = Starting Rank Value (1180.5) + Head To Head Adjustments (-202.4)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.580[<sup>1</sup>](#table2)
- Bounty Collected: 0.419[<sup>2</sup>](#table1)
- Opponent Network: 0.285[<sup>2</sup>](#table1)
- LAN Wins: 0.289[<sup>2</sup>](#table1)

The average of these factors is 0.393<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1180.5
- 400 + ( ( 0.393 - 0.000 ) / ( 0.806 - 0.000 ) ) * 1600 = 1180.5


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent                    | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins      | H2H Adj. | Roster                            |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           80 |      233 | 2024-04-30 | MOUZ NXT                    | L   | 1.000      | -            | -                | -                | -             |   -13.12 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           79 |      282 | 2024-04-29 | 1win                        | W   | 1.000      | -            | -                | -                | false (0.000) |     8.56 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           78 |      328 | 2024-04-28 | Astralis Talent             | W   | 1.000      | -            | -                | -                | false (0.000) |    10.81 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           77 |      356 | 2024-04-27 | MOUZ NXT                    | L   | 1.000      | -            | -                | -                | -             |   -13.24 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           76 |      496 | 2024-04-25 | Team Sampi                  | W   | 1.000      | 0.371        | 0.108 (0.040)    | 0.709 (0.263)    | false (0.000) |    17.64 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           75 |      532 | 2024-04-24 | Team Spirit Academy         | L   | 1.000      | -            | -                | -                | -             |   -28.04 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           74 |      541 | 2024-04-24 | ARCRED                      | L   | 1.000      | -            | -                | -                | -             |   -22.60 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           73 |      591 | 2024-04-23 | Team Sampi                  | W   | 1.000      | 0.371        | 0.108 (0.040)    | 0.709 (0.263)    | false (0.000) |    16.39 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           72 |      652 | 2024-04-21 | Rhyno Esports               | L   | 1.000      | -            | -                | -                | -             |   -20.79 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           71 |      662 | 2024-04-21 | MOUZ NXT                    | W   | 1.000      | 0.371        | 0.215 (0.080)    | 1.000 (0.371)    | false (0.000) |    17.61 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           70 |      714 | 2024-04-20 | Aurora Young Blud           | L   | 1.000      | -            | -                | -                | -             |   -25.45 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           69 |      821 | 2024-04-19 | FLuffy Gangsters            | W   | 1.000      | -            | -                | -                | false (0.000) |     3.04 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           68 |      854 | 2024-04-19 | SINNERS Esports             | W   | 1.000      | -            | -                | -                | false (0.000) |    16.18 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           67 |      889 | 2024-04-18 | VP.Prodigy                  | W   | 1.000      | 0.333        | -                | 0.762 (0.254)    | -             |     8.12 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           66 |      963 | 2024-04-17 | Alliance                    | W   | 1.000      | 0.371        | -                | 0.729 (0.270)    | -             |    10.19 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           65 |      996 | 2024-04-16 | Raptors Esports Club        | L   | 1.000      | -            | -                | -                | -             |   -21.57 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           64 |     1059 | 2024-04-15 | Astralis Talent             | W   | 1.000      | -            | -                | -                | -             |     8.51 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           63 |     1147 | 2024-04-12 | DMS                         | W   | 1.000      | -            | -                | -                | -             |     7.17 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           62 |     1229 | 2024-04-10 | UNiTY esports (Slovak team) | W   | 1.000      | 0.333        | 0.055 (0.018)    | -                | -             |    11.13 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           61 |     1239 | 2024-04-10 | Rhyno Esports               | L   | 1.000      | -            | -                | -                | -             |   -20.87 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           60 |     1306 | 2024-04-09 | ALTERNATE aTTaX             | L   | 1.000      | -            | -                | -                | -             |   -19.53 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           59 |     1451 | 2024-04-05 | WOPA Esport                 | L   | 0.997      | -            | -                | -                | -             |   -26.04 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           58 |     1508 | 2024-04-04 | Turów Zgorzelec Esport      | W   | 0.989      | -            | -                | -                | -             |     6.29 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           57 |     1552 | 2024-04-03 | Permitta Esports            | W   | 0.983      | 0.333        | 0.063 (0.021)    | 1.000 (0.328)    | -             |    10.48 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           56 |     1607 | 2024-04-01 | Astralis Talent             | W   | 0.970      | -            | -                | -                | -             |     9.14 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           55 |     1609 | 2024-04-01 | Astralis Talent             | L   | 0.969      | -            | -                | -                | -             |   -21.90 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           54 |     1628 | 2024-03-31 | UNiTY esports (Slovak team) | L   | 0.962      | -            | -                | -                | -             |   -21.91 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           53 |     1818 | 2024-03-26 | Passion UA                  | L   | 0.932      | -            | -                | -                | -             |   -18.77 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           52 |     1833 | 2024-03-26 | Sashi Esport                | W   | 0.930      | 0.333        | 0.193 (0.060)    | 1.000 (0.310)    | -             |    13.59 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           51 |     1889 | 2024-03-23 | Raptors Esports Club        | W   | 0.912      | -            | -                | -                | -             |     6.17 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           50 |     1950 | 2024-03-22 | UNiTY esports (Slovak team) | L   | 0.904      | -            | -                | -                | -             |   -22.40 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           49 |     2017 | 2024-03-20 | Raptors Esports Club        | W   | 0.892      | -            | -                | -                | -             |     5.50 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           48 |     2031 | 2024-03-20 | Turów Zgorzelec Esport      | W   | 0.891      | -            | -                | -                | -             |     4.38 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           47 |     2062 | 2024-03-19 | LEON Esports                | W   | 0.885      | -            | -                | -                | -             |     3.16 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           46 |     2135 | 2024-03-17 | SINNERS Esports             | W   | 0.872      | -            | -                | -                | true (0.872)  |    11.51 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           45 |     2172 | 2024-03-16 | UNiTY esports (Slovak team) | W   | 0.865      | -            | -                | -                | true (0.865)  |     6.82 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           44 |     2184 | 2024-03-16 | UNiTY esports (Slovak team) | L   | 0.863      | -            | -                | -                | -             |   -20.88 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           43 |     2209 | 2024-03-15 | ARROW (German team)         | W   | 0.859      | -            | -                | -                | -             |     2.93 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           42 |     2221 | 2024-03-15 | Team Sampi                  | W   | 0.857      | -            | -                | -                | true (0.857)  |    11.13 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           41 |     2329 | 2024-03-13 | Permitta Esports            | L   | 0.844      | -            | -                | -                | -             |   -16.03 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           40 |     2347 | 2024-03-13 | Permitta Esports            | L   | 0.843      | -            | -                | -                | -             |   -17.17 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           39 |     2439 | 2024-03-11 | Entropiq                    | L   | 0.829      | -            | -                | -                | -             |   -22.02 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           38 |     2468 | 2024-03-10 | Zero Tenacity               | L   | 0.824      | -            | -                | -                | -             |   -19.01 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           37 |     2561 | 2024-03-07 | Wolves eSports              | W   | 0.806      | -            | -                | -                | -             |     1.48 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           36 |     2574 | 2024-03-07 | Team Universe               | W   | 0.805      | -            | -                | -                | -             |     1.34 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           35 |     2692 | 2024-03-05 | SINNERS Esports             | L   | 0.792      | -            | -                | -                | -             |   -17.22 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           34 |     2711 | 2024-03-05 | 9INE                        | W   | 0.790      | -            | -                | -                | -             |     1.38 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           33 |     2758 | 2024-03-04 | BRUTE                       | W   | 0.785      | -            | -                | -                | -             |     0.76 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           32 |     2816 | 2024-03-03 | Metizport                   | W   | 0.777      | 0.384        | 0.188 (0.056)    | 1.000 (0.299)    | -             |    10.58 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           31 |     2839 | 2024-03-02 | Metizport                   | L   | 0.772      | -            | -                | -                | -             |   -14.55 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           30 |     2927 | 2024-03-01 | Viperio                     | W   | 0.763      | -            | -                | -                | -             |     1.60 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           29 |     3007 | 2024-02-28 | Permitta Esports            | W   | 0.749      | 0.333        | 0.063 (0.016)    | 1.000 (0.250)    | -             |     7.32 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           28 |     3041 | 2024-02-27 | MOUZ NXT                    | W   | 0.744      | 0.333        | 0.215 (0.053)    | 1.000 (0.248)    | -             |    10.70 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           27 |     3081 | 2024-02-26 | Turów Zgorzelec Esport      | W   | 0.736      | -            | -                | -                | -             |     3.83 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           26 |     3114 | 2024-02-25 | Team Sampi                  | W   | 0.729      | 0.333        | 0.108 (0.026)    | -                | -             |     7.42 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           25 |     3174 | 2024-02-24 | Permitta Esports            | L   | 0.723      | -            | -                | -                | -             |   -15.96 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           24 |     3264 | 2024-02-22 | BIG Academy                 | W   | 0.710      | -            | -                | -                | -             |     4.07 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           23 |     3330 | 2024-02-21 | Permitta Esports            | W   | 0.703      | -            | -                | -                | -             |     7.03 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           22 |     3373 | 2024-02-20 | Natus Vincere Junior        | W   | 0.697      | -            | -                | -                | -             |     3.61 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           21 |     3379 | 2024-02-20 | Lilmix                      | W   | 0.696      | -            | -                | -                | -             |     1.39 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           20 |     3425 | 2024-02-19 | Permitta Esports            | L   | 0.690      | -            | -                | -                | -             |   -15.25 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           19 |     3494 | 2024-02-17 | Natus Vincere Junior        | W   | 0.678      | -            | -                | -                | -             |     3.13 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           18 |     3601 | 2024-02-15 | MOUZ NXT                    | L   | 0.663      | -            | -                | -                | -             |   -12.32 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           17 |     3646 | 2024-02-14 | K10                         | W   | 0.657      | -            | -                | -                | -             |     3.23 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           16 |     3760 | 2024-02-11 | Lilmix                      | W   | 0.636      | -            | -                | -                | -             |     0.97 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           15 |     3766 | 2024-02-10 | 0to100                      | W   | 0.632      | -            | -                | -                | -             |     0.59 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           14 |     3768 | 2024-02-10 | Virtuoso Squad              | W   | 0.632      | -            | -                | -                | -             |     0.29 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           13 |     3805 | 2024-02-09 | Illuminar Gaming            | W   | 0.623      | -            | -                | -                | -             |     2.43 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           12 |     4021 | 2024-02-02 | 9Pandas                     | L   | 0.578      | -            | -                | -                | -             |    -9.05 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           11 |     4037 | 2024-02-02 | UNiTY esports (Slovak team) | W   | 0.578      | -            | -                | -                | -             |     4.37 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           10 |     4169 | 2024-01-29 | Metizport                   | W   | 0.553      | -            | -                | -                | -             |     5.23 | Blytz, Dytor, forsyy, kreaz, nbqq |
|            9 |     4190 | 2024-01-29 | Ninjas in Pyjamas           | W   | 0.553      | -            | -                | -                | -             |     2.46 | Blytz, Dytor, forsyy, kreaz, nbqq |
|            8 |     4819 | 2024-01-16 | Zero Tenacity               | L   | 0.463      | -            | -                | -                | -             |   -11.36 | Blytz, Dytor, forsyy, kreaz, nbqq |
|            7 |     4869 | 2024-01-14 | Permitta Esports            | L   | 0.450      | -            | -                | -                | -             |   -10.11 | Blytz, Dytor, forsyy, kreaz, nbqq |
|            6 |     4923 | 2024-01-12 | Team Walkover               | L   | 0.439      | -            | -                | -                | -             |   -13.47 | Blytz, Dytor, forsyy, kreaz, nbqq |
|            5 |     5087 | 2024-01-09 | Sashi Esport                | L   | 0.418      | -            | -                | -                | -             |    -8.50 | Blytz, Dytor, forsyy, kreaz, nbqq |
|            4 |     5100 | 2024-01-09 | Rhyno Esports               | W   | 0.418      | -            | -                | -                | -             |     2.57 | Blytz, Dytor, forsyy, kreaz, nbqq |
|            3 |     5112 | 2024-01-09 | FALKE ESPORTS               | W   | 0.418      | -            | -                | -                | -             |     0.29 | Blytz, Dytor, forsyy, kreaz, nbqq |
|            2 |     5155 | 2024-01-08 | Aurora Young Blud           | W   | 0.410      | -            | -                | -                | -             |     1.54 | Blytz, Dytor, forsyy, kreaz, nbqq |
|            1 |     5198 | 2024-01-04 | SINNERS Academy             | W   | 0.383      | -            | -                | -                | -             |     0.71 | Blytz, Dytor, forsyy, kreaz, nbqq |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($29,943.11)
- Divide that value by the 5th highest value among all rosters ($158,437.64)
- The final value (0.19) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-04-25 |      1.000 | $11,000.00     | $11,000.00      |
| 2024-04-21 |      1.000 | $1,250.00      | $1,250.00       |
| 2024-04-06 |      1.000 | $1,500.00      | $1,500.00       |
| 2024-03-23 |      0.912 | $3,500.00      | $3,193.10       |
| 2024-03-17 |      0.872 | $7,792.81      | $6,793.46       |
| 2024-02-28 |      0.749 | $5,000.00      | $3,746.99       |
| 2024-02-21 |      0.703 | $3,500.00      | $2,459.56       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
