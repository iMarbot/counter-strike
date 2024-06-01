### Roster Details<br />
Team Name: 9Pandas<br />
Roster: clax, d1Ledez, glowiing, iDISBALANCE, seized<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [38](../standings_global.md)<br />
Regional Rank: [28]( ../standings_europe.md)<br />
Final Rank Value:  1130.5<br />
<br />
Final Rank Value (1130.5) = Starting Rank Value (1172.7) + Head To Head Adjustments (-42.2)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.511[<sup>1</sup>](#table2)
- Bounty Collected: 0.422[<sup>2</sup>](#table1)
- Opponent Network: 0.361[<sup>2</sup>](#table1)
- LAN Wins: 0.225[<sup>2</sup>](#table1)

The average of these factors is 0.380<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1172.7
- 400 + ( ( 0.380 - 0.000 ) / ( 0.786 - 0.000 ) ) * 1600 = 1172.7


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
|           71 |      212 | 2024-05-26 | MOUZ NXT             | W   | 1.000      | 0.435        | 0.157 (0.068)    | 0.950 (0.413)    | 0 (0.000) |    11.14 | clax, d1Ledez, glowiing, iDISBALANCE, seized |
|           70 |      224 | 2024-05-26 | 1win                 | W   | 1.000      | 0.435        | 0.050 (0.022)    | 0.887 (0.386)    | 0 (0.000) |    13.17 | clax, d1Ledez, glowiing, iDISBALANCE, seized |
|           69 |      259 | 2024-05-25 | Team Space           | W   | 1.000      | -            | -                | -                | 0 (0.000) |     8.09 | clax, d1Ledez, glowiing, iDISBALANCE, seized |
|           68 |      365 | 2024-05-24 | SINNERS Esports      | W   | 1.000      | 0.435        | -                | 0.560 (0.243)    | 0 (0.000) |    10.44 | clax, d1Ledez, glowiing, iDISBALANCE, seized |
|           67 |      698 | 2024-05-20 | BLEED Esports        | L   | 1.000      | -            | -                | -                | -         |   -12.14 | clax, d1Ledez, glowiing, iDISBALANCE, seized |
|           66 |      875 | 2024-05-18 | Passion UA           | W   | 1.000      | 0.500        | 0.057 (0.028)    | 1.000 (0.500)    | 0 (0.000) |     9.01 | clax, d1Ledez, glowiing, iDISBALANCE, seized |
|           65 |     1082 | 2024-05-16 | ALTERNATE aTTaX      | W   | 1.000      | 0.500        | 0.052 (0.026)    | 0.679 (0.340)    | 0 (0.000) |     9.79 | clax, d1Ledez, glowiing, iDISBALANCE, seized |
|           64 |     1381 | 2024-05-12 | BetBoom Team         | L   | 1.000      | -            | -                | -                | -         |    -6.15 | clax, d1Ledez, glowiing, iDISBALANCE, seized |
|           63 |     1441 | 2024-05-11 | RUBY                 | W   | 1.000      | 0.435        | -                | 0.728 (0.316)    | -         |    11.20 | clax, d1Ledez, glowiing, iDISBALANCE, seized |
|           62 |     1499 | 2024-05-10 | Sangal Esports       | L   | 1.000      | -            | -                | -                | -         |   -17.07 | clax, d1Ledez, glowiing, iDISBALANCE, seized |
|           61 |     1504 | 2024-05-10 | HyperSpirit          | W   | 1.000      | -            | -                | -                | -         |     4.73 | clax, d1Ledez, glowiing, iDISBALANCE, seized |
|           60 |     1525 | 2024-05-10 | Monte Gen            | W   | 1.000      | -            | -                | -                | -         |     5.42 | clax, d1Ledez, glowiing, iDISBALANCE, seized |
|           59 |     1576 | 2024-05-09 | Zero Tenacity        | W   | 1.000      | 0.435        | 0.147 (0.064)    | 1.000 (0.435)    | -         |    14.30 | clax, d1Ledez, glowiing, iDISBALANCE, seized |
|           58 |     1690 | 2024-05-07 | Sashi Esport         | L   | 1.000      | -            | -                | -                | -         |    -7.98 | clax, d1Ledez, glowiing, iDISBALANCE, seized |
|           57 |     1789 | 2024-05-05 | ARCRED               | W   | 1.000      | -            | -                | -                | -         |     8.60 | clax, d1Ledez, glowiing, iDISBALANCE, seized |
|           56 |     1833 | 2024-05-04 | BetBoom Team         | L   | 1.000      | -            | -                | -                | -         |    -5.36 | clax, d1Ledez, glowiing, iDISBALANCE, seized |
|           55 |     1867 | 2024-05-03 | Fnatic               | W   | 1.000      | 0.435        | 0.147 (0.064)    | -                | -         |    20.13 | clax, d1Ledez, glowiing, iDISBALANCE, seized |
|           54 |     1939 | 2024-05-02 | MOUZ NXT             | W   | 1.000      | 0.435        | 0.157 (0.068)    | 0.950 (0.413)    | -         |    17.47 | clax, d1Ledez, glowiing, iDISBALANCE, seized |
|           53 |     2044 | 2024-04-30 | Passion UA           | L   | 1.000      | -            | -                | -                | -         |   -21.57 | clax, d1Ledez, glowiing, iDISBALANCE, seized |
|           52 |     2133 | 2024-04-28 | Gaimin Gladiators    | W   | 0.988      | 0.500        | 0.092 (0.045)    | 0.711 (0.351)    | -         |    22.27 | clax, d1Ledez, glowiing, iDISBALANCE, seized |
|           51 |     2264 | 2024-04-26 | Passion UA           | L   | 0.976      | -            | -                | -                | -         |   -20.79 | clax, d1Ledez, glowiing, iDISBALANCE, seized |
|           50 |     2731 | 2024-04-19 | Alliance             | L   | 0.928      | -            | -                | -                | -         |   -21.93 | clax, d1Ledez, glowiing, iDISBALANCE, seized |
|           49 |     2819 | 2024-04-17 | Sashi Esport         | L   | 0.918      | -            | -                | -                | -         |   -15.87 | clax, d1Ledez, glowiing, iDISBALANCE, seized |
|           48 |     2875 | 2024-04-17 | Sangal Esports       | L   | 0.915      | -            | -                | -                | -         |   -18.65 | clax, d1Ledez, glowiing, iDISBALANCE, seized |
|           47 |     3168 | 2024-04-10 | SAW                  | L   | 0.871      | -            | -                | -                | -         |    -5.07 | clax, d1Ledez, glowiing, iDISBALANCE, seized |
|           46 |     3238 | 2024-04-09 | SINNERS Esports      | L   | 0.864      | -            | -                | -                | -         |   -17.14 | clax, d1Ledez, glowiing, iDISBALANCE, seized |
|           45 |     3267 | 2024-04-09 | Aurora Gaming        | L   | 0.862      | -            | -                | -                | -         |    -4.37 | clax, d1Ledez, glowiing, iDISBALANCE, seized |
|           44 |     3285 | 2024-04-08 | 1win                 | L   | 0.857      | -            | -                | -                | -         |   -19.35 | clax, d1Ledez, glowiing, iDISBALANCE, seized |
|           43 |     3299 | 2024-04-08 | Metizport            | W   | 0.856      | 0.143        | 0.088 (0.011)    | -                | -         |    11.87 | clax, d1Ledez, glowiing, iDISBALANCE, seized |
|           42 |     3453 | 2024-04-05 | Team Secret          | L   | 0.836      | -            | -                | -                | -         |   -24.89 | clax, d1Ledez, glowiing, iDISBALANCE, seized |
|           41 |     3491 | 2024-04-04 | TSM                  | W   | 0.831      | -            | -                | -                | -         |     2.46 | clax, d1Ledez, glowiing, iDISBALANCE, seized |
|           40 |     3552 | 2024-04-03 | EYEBALLERS           | W   | 0.824      | 0.500        | -                | 0.508 (0.209)    | -         |     5.19 | clax, d1Ledez, glowiing, iDISBALANCE, seized |
|           39 |     3561 | 2024-04-03 | 9INE                 | W   | 0.823      | -            | -                | -                | -         |     1.45 | clax, d1Ledez, glowiing, iDISBALANCE, seized |
|           38 |     4853 | 2024-03-06 | KOI                  | L   | 0.638      | -            | -                | -                | -         |   -13.34 | clax, d1Ledez, glowiing, iDISBALANCE, seized |
|           37 |     5240 | 2024-03-01 | Aurora Gaming        | L   | 0.603      | -            | -                | -                | -         |    -3.81 | clax, d1Ledez, glowiing, iDISBALANCE, seized |
|           36 |     5261 | 2024-02-29 | FORZE Esports        | L   | 0.598      | -            | -                | -                | -         |   -13.20 | clax, d1Ledez, glowiing, iDISBALANCE, seized |
|           35 |     5311 | 2024-02-28 | Team Spirit Academy  | W   | 0.591      | -            | -                | -                | -         |     1.93 | clax, d1Ledez, glowiing, iDISBALANCE, seized |
|           34 |     5330 | 2024-02-28 | Lotus                | W   | 0.590      | -            | -                | -                | -         |     0.22 | clax, d1Ledez, glowiing, iDISBALANCE, seized |
|           33 |     5545 | 2024-02-24 | GamerLegion          | W   | 0.563      | -            | -                | -                | 1 (0.563) |    10.81 | clax, d1Ledez, glowiing, iDISBALANCE, seized |
|           32 |     5620 | 2024-02-23 | Astralis             | W   | 0.556      | 0.143        | 0.395 (0.031)    | -                | 1 (0.556) |    16.31 | clax, d1Ledez, glowiing, iDISBALANCE, seized |
|           31 |     5959 | 2024-02-17 | AMKAL ESPORTS        | L   | 0.516      | -            | -                | -                | -         |    -7.47 | clax, d1Ledez, glowiing, iDISBALANCE, seized |
|           30 |     5991 | 2024-02-16 | 3DMAX                | W   | 0.510      | -            | -                | -                | 1 (0.510) |     3.65 | clax, d1Ledez, glowiing, iDISBALANCE, seized |
|           29 |     6063 | 2024-02-15 | KOI                  | L   | 0.502      | -            | -                | -                | -         |   -11.76 | clax, d1Ledez, glowiing, iDISBALANCE, seized |
|           28 |     6105 | 2024-02-14 | SAW                  | W   | 0.497      | -            | -                | -                | 1 (0.497) |    11.53 | clax, d1Ledez, glowiing, iDISBALANCE, seized |
|           27 |     6129 | 2024-02-14 | FaZe Clan            | L   | 0.496      | -            | -                | -                | -         |    -0.15 | clax, d1Ledez, glowiing, iDISBALANCE, seized |
|           26 |     6510 | 2024-02-03 | kONO.ECF             | L   | 0.424      | -            | -                | -                | -         |   -11.42 | clax, d1Ledez, glowiing, iDISBALANCE, seized |
|           25 |     6526 | 2024-02-03 | Clownfiesta          | W   | 0.424      | -            | -                | -                | -         |     0.18 | clax, d1Ledez, glowiing, iDISBALANCE, seized |
|           24 |     6548 | 2024-02-03 | Natus Vincere Junior | W   | 0.423      | -            | -                | -                | -         |     1.35 | clax, d1Ledez, glowiing, iDISBALANCE, seized |
|           23 |     6592 | 2024-02-02 | B8                   | L   | 0.418      | -            | -                | -                | -         |    -7.75 | clax, d1Ledez, glowiing, iDISBALANCE, seized |
|           22 |     6597 | 2024-02-02 | Dynamo Eclot         | W   | 0.417      | -            | -                | -                | -         |     4.77 | clax, d1Ledez, glowiing, iDISBALANCE, seized |
|           21 |     6612 | 2024-02-02 | FAVBET Team          | W   | 0.417      | -            | -                | -                | -         |     1.68 | clax, d1Ledez, glowiing, iDISBALANCE, seized |
|           20 |     6628 | 2024-02-02 | INGLORIOUS           | W   | 0.417      | -            | -                | -                | -         |     1.11 | clax, d1Ledez, glowiing, iDISBALANCE, seized |
|           19 |     6758 | 2024-01-30 | Nemiga Gaming        | L   | 0.397      | -            | -                | -                | -         |    -5.07 | clax, d1Ledez, glowiing, iDISBALANCE, seized |
|           18 |     6794 | 2024-01-29 | ex-Anonymo Esports   | W   | 0.392      | -            | -                | -                | -         |     0.96 | clax, d1Ledez, glowiing, iDISBALANCE, seized |
|           17 |     6816 | 2024-01-29 | JANO Esports         | W   | 0.392      | -            | -                | -                | -         |     1.16 | clax, d1Ledez, glowiing, iDISBALANCE, seized |
|           16 |     6868 | 2024-01-28 | Rebels Gaming        | W   | 0.384      | -            | -                | -                | -         |     4.34 | clax, d1Ledez, glowiing, iDISBALANCE, seized |
|           15 |     7028 | 2024-01-26 | ex-FLuffy Gangsters  | W   | 0.371      | -            | -                | -                | -         |     0.27 | clax, d1Ledez, glowiing, iDISBALANCE, seized |
|           14 |     7038 | 2024-01-26 | UNiTY esports        | W   | 0.370      | -            | -                | -                | -         |     2.23 | clax, d1Ledez, glowiing, iDISBALANCE, seized |
|           13 |     7325 | 2024-01-20 | 3DMAX                | W   | 0.331      | -            | -                | -                | -         |     2.35 | clax, d1Ledez, glowiing, iDISBALANCE, seized |
|           12 |     7348 | 2024-01-20 | SAW                  | L   | 0.330      | -            | -                | -                | -         |    -2.64 | clax, d1Ledez, glowiing, iDISBALANCE, seized |
|           11 |     7416 | 2024-01-19 | Gaimin Gladiators    | W   | 0.323      | -            | -                | -                | -         |     6.66 | clax, d1Ledez, glowiing, iDISBALANCE, seized |
|           10 |     7466 | 2024-01-18 | Natus Vincere        | L   | 0.317      | -            | -                | -                | -         |    -0.20 | clax, d1Ledez, glowiing, iDISBALANCE, seized |
|            9 |     7473 | 2024-01-18 | Nexus Gaming         | W   | 0.317      | -            | -                | -                | -         |     2.07 | clax, d1Ledez, glowiing, iDISBALANCE, seized |
|            8 |     8453 | 2023-12-17 | IKLA                 | L   | 0.104      | -            | -                | -                | -         |    -3.18 | clax, d1Ledez, glowiing, iDISBALANCE, seized |
|            7 |     8595 | 2023-12-16 | B8                   | L   | 0.098      | -            | -                | -                | -         |    -3.00 | clax, d1Ledez, glowiing, iDISBALANCE, seized |
|            6 |     8925 | 2023-12-11 | ex-Preasy Esport     | L   | 0.064      | -            | -                | -                | -         |    -1.64 | clax, d1Ledez, glowiing, iDISBALANCE, seized |
|            5 |     9208 | 2023-12-06 | ex-Guild Eagles      | L   | 0.031      | -            | -                | -                | -         |    -0.75 | clax, d1Ledez, glowiing, iDISBALANCE, seized |
|            4 |     9228 | 2023-12-06 | Gaimin Gladiators    | W   | 0.030      | -            | -                | -                | -         |     0.63 | clax, d1Ledez, glowiing, iDISBALANCE, seized |
|            3 |     9242 | 2023-12-06 | SAW                  | W   | 0.029      | -            | -                | -                | -         |     0.68 | clax, d1Ledez, glowiing, iDISBALANCE, seized |
|            2 |     9278 | 2023-12-05 | BIG                  | L   | 0.025      | -            | -                | -                | -         |    -0.15 | clax, d1Ledez, glowiing, iDISBALANCE, seized |
|            1 |     9353 | 2023-12-03 | Into The Breach      | W   | 0.011      | -            | -                | -                | -         |     0.03 | clax, d1Ledez, glowiing, iDISBALANCE, seized |

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
