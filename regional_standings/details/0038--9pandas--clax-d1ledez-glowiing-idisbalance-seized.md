### Roster Details<br />
Team Name: 9Pandas<br />
Roster: clax, d1Ledez, glowiing, iDISBALANCE, seized<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [38](../standings_global.md)<br />
Regional Rank: [28]( ../standings_europe.md)<br />
Final Rank Value:  1139.7<br />
<br />
Final Rank Value (1139.7) = Starting Rank Value (1183.5) + Head To Head Adjustments (-43.8)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.511[<sup>1</sup>](#table2)
- Bounty Collected: 0.432[<sup>2</sup>](#table1)
- Opponent Network: 0.374[<sup>2</sup>](#table1)
- LAN Wins: 0.225[<sup>2</sup>](#table1)

The average of these factors is 0.386<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1183.5
- 400 + ( ( 0.386 - 0.000 ) / ( 0.787 - 0.000 ) ) * 1600 = 1183.5


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent             | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                       |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           74 |      220 | 2024-05-26 | MOUZ NXT             | W   | 1.000      | 0.435        | 0.157 (0.068)    | 0.977 (0.424)    | 0 (0.000) |    11.09 | clax, d1Ledez, glowiing, iDISBALANCE, seized |
|           73 |      232 | 2024-05-26 | 1win                 | W   | 1.000      | 0.435        | 0.050 (0.022)    | 0.898 (0.390)    | 0 (0.000) |    12.84 | clax, d1Ledez, glowiing, iDISBALANCE, seized |
|           72 |      267 | 2024-05-25 | Team Space           | W   | 1.000      | -            | -                | -                | 0 (0.000) |     7.82 | clax, d1Ledez, glowiing, iDISBALANCE, seized |
|           71 |      374 | 2024-05-24 | SINNERS Esports      | W   | 1.000      | 0.435        | -                | 0.582 (0.253)    | 0 (0.000) |    10.36 | clax, d1Ledez, glowiing, iDISBALANCE, seized |
|           70 |      710 | 2024-05-20 | BLEED Esports        | L   | 1.000      | -            | -                | -                | -         |   -12.58 | clax, d1Ledez, glowiing, iDISBALANCE, seized |
|           69 |      887 | 2024-05-18 | Passion UA           | W   | 1.000      | 0.500        | 0.057 (0.028)    | 1.000 (0.500)    | 0 (0.000) |     8.97 | clax, d1Ledez, glowiing, iDISBALANCE, seized |
|           68 |     1092 | 2024-05-16 | ALTERNATE aTTaX      | W   | 1.000      | 0.500        | 0.052 (0.026)    | 0.735 (0.368)    | 0 (0.000) |     9.50 | clax, d1Ledez, glowiing, iDISBALANCE, seized |
|           67 |     1394 | 2024-05-12 | BetBoom Team         | L   | 1.000      | -            | -                | -                | -         |    -6.47 | clax, d1Ledez, glowiing, iDISBALANCE, seized |
|           66 |     1454 | 2024-05-11 | RUBY                 | W   | 1.000      | 0.435        | -                | 0.738 (0.321)    | -         |    10.88 | clax, d1Ledez, glowiing, iDISBALANCE, seized |
|           65 |     1512 | 2024-05-10 | Sangal Esports       | L   | 1.000      | -            | -                | -                | -         |   -16.41 | clax, d1Ledez, glowiing, iDISBALANCE, seized |
|           64 |     1517 | 2024-05-10 | HyperSpirit          | W   | 1.000      | -            | -                | -                | -         |     4.50 | clax, d1Ledez, glowiing, iDISBALANCE, seized |
|           63 |     1527 | 2024-05-10 | 9INE                 | W   | 1.000      | -            | -                | -                | -         |     1.11 | clax, d1Ledez, glowiing, iDISBALANCE, seized |
|           62 |     1539 | 2024-05-10 | Monte Gen            | W   | 1.000      | -            | -                | -                | -         |     5.22 | clax, d1Ledez, glowiing, iDISBALANCE, seized |
|           61 |     1592 | 2024-05-09 | Zero Tenacity        | W   | 1.000      | 0.435        | 0.147 (0.064)    | 1.000 (0.435)    | -         |    13.96 | clax, d1Ledez, glowiing, iDISBALANCE, seized |
|           60 |     1710 | 2024-05-07 | Sashi Esport         | L   | 1.000      | -            | -                | -                | -         |    -8.34 | clax, d1Ledez, glowiing, iDISBALANCE, seized |
|           59 |     1812 | 2024-05-05 | ARCRED               | W   | 1.000      | -            | -                | -                | -         |     8.25 | clax, d1Ledez, glowiing, iDISBALANCE, seized |
|           58 |     1856 | 2024-05-04 | BetBoom Team         | L   | 1.000      | -            | -                | -                | -         |    -5.67 | clax, d1Ledez, glowiing, iDISBALANCE, seized |
|           57 |     1891 | 2024-05-03 | Fnatic               | W   | 1.000      | 0.435        | 0.147 (0.064)    | -                | -         |    19.72 | clax, d1Ledez, glowiing, iDISBALANCE, seized |
|           56 |     1966 | 2024-05-02 | MOUZ NXT             | W   | 1.000      | 0.435        | 0.157 (0.068)    | 0.977 (0.424)    | -         |    17.15 | clax, d1Ledez, glowiing, iDISBALANCE, seized |
|           55 |     2078 | 2024-04-30 | Passion UA           | L   | 1.000      | -            | -                | -                | -         |   -21.55 | clax, d1Ledez, glowiing, iDISBALANCE, seized |
|           54 |     2168 | 2024-04-28 | Gaimin Gladiators    | W   | 0.988      | 0.500        | 0.092 (0.045)    | 0.727 (0.359)    | -         |    21.95 | clax, d1Ledez, glowiing, iDISBALANCE, seized |
|           53 |     2300 | 2024-04-26 | Passion UA           | L   | 0.976      | -            | -                | -                | -         |   -20.71 | clax, d1Ledez, glowiing, iDISBALANCE, seized |
|           52 |     2787 | 2024-04-19 | Alliance             | L   | 0.928      | -            | -                | -                | -         |   -22.35 | clax, d1Ledez, glowiing, iDISBALANCE, seized |
|           51 |     2876 | 2024-04-17 | Sashi Esport         | L   | 0.918      | -            | -                | -                | -         |   -16.51 | clax, d1Ledez, glowiing, iDISBALANCE, seized |
|           50 |     2932 | 2024-04-17 | Sangal Esports       | L   | 0.915      | -            | -                | -                | -         |   -17.96 | clax, d1Ledez, glowiing, iDISBALANCE, seized |
|           49 |     3241 | 2024-04-10 | SAW                  | L   | 0.871      | -            | -                | -                | -         |    -5.36 | clax, d1Ledez, glowiing, iDISBALANCE, seized |
|           48 |     3317 | 2024-04-09 | SINNERS Esports      | L   | 0.864      | -            | -                | -                | -         |   -16.28 | clax, d1Ledez, glowiing, iDISBALANCE, seized |
|           47 |     3346 | 2024-04-09 | Aurora Gaming        | L   | 0.862      | -            | -                | -                | -         |    -5.38 | clax, d1Ledez, glowiing, iDISBALANCE, seized |
|           46 |     3366 | 2024-04-08 | 1win                 | L   | 0.857      | -            | -                | -                | -         |   -20.09 | clax, d1Ledez, glowiing, iDISBALANCE, seized |
|           45 |     3380 | 2024-04-08 | Metizport            | W   | 0.856      | -            | -                | -                | -         |    11.01 | clax, d1Ledez, glowiing, iDISBALANCE, seized |
|           44 |     3537 | 2024-04-05 | Team Secret          | L   | 0.836      | -            | -                | -                | -         |   -24.98 | clax, d1Ledez, glowiing, iDISBALANCE, seized |
|           43 |     3576 | 2024-04-04 | TSM                  | W   | 0.831      | -            | -                | -                | -         |     2.47 | clax, d1Ledez, glowiing, iDISBALANCE, seized |
|           42 |     3639 | 2024-04-03 | EYEBALLERS           | W   | 0.824      | -            | -                | -                | -         |     4.88 | clax, d1Ledez, glowiing, iDISBALANCE, seized |
|           41 |     3648 | 2024-04-03 | 9INE                 | W   | 0.823      | -            | -                | -                | -         |     1.34 | clax, d1Ledez, glowiing, iDISBALANCE, seized |
|           40 |     3688 | 2024-04-02 | Sangal Esports       | W   | 0.817      | 0.500        | 0.166 (0.068)    | 0.658 (0.269)    | -         |     6.55 | clax, d1Ledez, glowiing, iDISBALANCE, seized |
|           39 |     4984 | 2024-03-06 | KOI                  | L   | 0.638      | -            | -                | -                | -         |   -13.47 | clax, d1Ledez, glowiing, iDISBALANCE, seized |
|           38 |     5389 | 2024-03-01 | Aurora Gaming        | L   | 0.603      | -            | -                | -                | -         |    -4.13 | clax, d1Ledez, glowiing, iDISBALANCE, seized |
|           37 |     5410 | 2024-02-29 | FORZE Esports        | L   | 0.598      | -            | -                | -                | -         |   -13.65 | clax, d1Ledez, glowiing, iDISBALANCE, seized |
|           36 |     5462 | 2024-02-28 | Team Spirit Academy  | W   | 0.591      | -            | -                | -                | -         |     1.88 | clax, d1Ledez, glowiing, iDISBALANCE, seized |
|           35 |     5481 | 2024-02-28 | Lotus                | W   | 0.590      | -            | -                | -                | -         |     0.21 | clax, d1Ledez, glowiing, iDISBALANCE, seized |
|           34 |     5705 | 2024-02-24 | GamerLegion          | W   | 0.563      | -            | -                | -                | 1 (0.563) |    10.56 | clax, d1Ledez, glowiing, iDISBALANCE, seized |
|           33 |     5780 | 2024-02-23 | Astralis             | W   | 0.556      | 0.143        | 0.395 (0.031)    | -                | 1 (0.556) |    16.22 | clax, d1Ledez, glowiing, iDISBALANCE, seized |
|           32 |     6132 | 2024-02-17 | AMKAL ESPORTS        | L   | 0.516      | -            | -                | -                | -         |    -7.64 | clax, d1Ledez, glowiing, iDISBALANCE, seized |
|           31 |     6166 | 2024-02-16 | 3DMAX                | W   | 0.510      | -            | -                | -                | 1 (0.510) |     3.52 | clax, d1Ledez, glowiing, iDISBALANCE, seized |
|           30 |     6244 | 2024-02-15 | KOI                  | L   | 0.502      | -            | -                | -                | -         |   -11.86 | clax, d1Ledez, glowiing, iDISBALANCE, seized |
|           29 |     6286 | 2024-02-14 | SAW                  | W   | 0.497      | -            | -                | -                | 1 (0.497) |    11.35 | clax, d1Ledez, glowiing, iDISBALANCE, seized |
|           28 |     6310 | 2024-02-14 | FaZe Clan            | L   | 0.496      | -            | -                | -                | -         |    -0.16 | clax, d1Ledez, glowiing, iDISBALANCE, seized |
|           27 |     6713 | 2024-02-03 | kONO.ECF             | L   | 0.424      | -            | -                | -                | -         |   -11.22 | clax, d1Ledez, glowiing, iDISBALANCE, seized |
|           26 |     6729 | 2024-02-03 | Clownfiesta          | W   | 0.424      | -            | -                | -                | -         |     0.17 | clax, d1Ledez, glowiing, iDISBALANCE, seized |
|           25 |     6751 | 2024-02-03 | Natus Vincere Junior | W   | 0.423      | -            | -                | -                | -         |     1.28 | clax, d1Ledez, glowiing, iDISBALANCE, seized |
|           24 |     6795 | 2024-02-02 | B8                   | L   | 0.418      | -            | -                | -                | -         |    -7.91 | clax, d1Ledez, glowiing, iDISBALANCE, seized |
|           23 |     6800 | 2024-02-02 | Dynamo Eclot         | W   | 0.417      | -            | -                | -                | -         |     4.65 | clax, d1Ledez, glowiing, iDISBALANCE, seized |
|           22 |     6816 | 2024-02-02 | FAVBET Team          | W   | 0.417      | -            | -                | -                | -         |     1.62 | clax, d1Ledez, glowiing, iDISBALANCE, seized |
|           21 |     6833 | 2024-02-02 | INGLORIOUS           | W   | 0.417      | -            | -                | -                | -         |     1.07 | clax, d1Ledez, glowiing, iDISBALANCE, seized |
|           20 |     6974 | 2024-01-30 | Nemiga Gaming        | L   | 0.397      | -            | -                | -                | -         |    -5.41 | clax, d1Ledez, glowiing, iDISBALANCE, seized |
|           19 |     7010 | 2024-01-29 | ex-Anonymo Esports   | W   | 0.392      | -            | -                | -                | -         |     0.91 | clax, d1Ledez, glowiing, iDISBALANCE, seized |
|           18 |     7032 | 2024-01-29 | JANO Esports         | W   | 0.392      | -            | -                | -                | -         |     1.16 | clax, d1Ledez, glowiing, iDISBALANCE, seized |
|           17 |     7086 | 2024-01-28 | Rebels Gaming        | W   | 0.384      | -            | -                | -                | -         |     4.25 | clax, d1Ledez, glowiing, iDISBALANCE, seized |
|           16 |     7251 | 2024-01-26 | FLuffy Gangsters     | W   | 0.371      | -            | -                | -                | -         |     0.37 | clax, d1Ledez, glowiing, iDISBALANCE, seized |
|           15 |     7262 | 2024-01-26 | UNiTY esports        | W   | 0.370      | -            | -                | -                | -         |     2.12 | clax, d1Ledez, glowiing, iDISBALANCE, seized |
|           14 |     7569 | 2024-01-20 | 3DMAX                | W   | 0.331      | -            | -                | -                | -         |     2.24 | clax, d1Ledez, glowiing, iDISBALANCE, seized |
|           13 |     7592 | 2024-01-20 | SAW                  | L   | 0.330      | -            | -                | -                | -         |    -2.77 | clax, d1Ledez, glowiing, iDISBALANCE, seized |
|           12 |     7662 | 2024-01-19 | Gaimin Gladiators    | W   | 0.323      | -            | -                | -                | -         |     6.53 | clax, d1Ledez, glowiing, iDISBALANCE, seized |
|           11 |     7714 | 2024-01-18 | Natus Vincere        | L   | 0.317      | -            | -                | -                | -         |    -0.21 | clax, d1Ledez, glowiing, iDISBALANCE, seized |
|           10 |     7721 | 2024-01-18 | Nexus Gaming         | W   | 0.317      | -            | -                | -                | -         |     1.83 | clax, d1Ledez, glowiing, iDISBALANCE, seized |
|            9 |     8712 | 2023-12-17 | IKLA                 | L   | 0.104      | -            | -                | -                | -         |    -3.19 | clax, d1Ledez, glowiing, iDISBALANCE, seized |
|            8 |     8856 | 2023-12-16 | B8                   | L   | 0.098      | -            | -                | -                | -         |    -3.00 | clax, d1Ledez, glowiing, iDISBALANCE, seized |
|            7 |     9000 | 2023-12-15 | Rebels Gaming        | W   | 0.091      | -            | -                | -                | -         |     1.21 | clax, d1Ledez, glowiing, iDISBALANCE, seized |
|            6 |     9191 | 2023-12-11 | ex-Preasy Esport     | L   | 0.064      | -            | -                | -                | -         |    -1.66 | clax, d1Ledez, glowiing, iDISBALANCE, seized |
|            5 |     9488 | 2023-12-06 | ex-Guild Eagles      | L   | 0.031      | -            | -                | -                | -         |    -0.76 | clax, d1Ledez, glowiing, iDISBALANCE, seized |
|            4 |     9509 | 2023-12-06 | Gaimin Gladiators    | W   | 0.030      | -            | -                | -                | -         |     0.61 | clax, d1Ledez, glowiing, iDISBALANCE, seized |
|            3 |     9523 | 2023-12-06 | SAW                  | W   | 0.029      | -            | -                | -                | -         |     0.67 | clax, d1Ledez, glowiing, iDISBALANCE, seized |
|            2 |     9560 | 2023-12-05 | BIG                  | L   | 0.025      | -            | -                | -                | -         |    -0.16 | clax, d1Ledez, glowiing, iDISBALANCE, seized |
|            1 |     9635 | 2023-12-03 | Into The Breach      | W   | 0.011      | -            | -                | -                | -         |     0.03 | clax, d1Ledez, glowiing, iDISBALANCE, seized |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($33,137.14)
- Divide that value by the 5th highest value among all rosters ($300,806.11)
- The final value (0.11) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-05-26 |      1.000 | $22,000.00     | $22,000.00      |
| 2024-05-12 |      1.000 | $5,000.00      | $5,000.00       |
| 2024-05-09 |      1.000 | $532.06        | $532.06         |
| 2024-05-04 |      1.000 | $5,000.00      | $5,000.00       |
| 2023-12-13 |      0.078 | $500.00        | $38.76          |
| 2023-12-07 |      0.038 | $15,000.00     | $566.32         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
