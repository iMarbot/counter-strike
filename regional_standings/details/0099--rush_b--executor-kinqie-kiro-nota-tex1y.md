### Roster Details<br />
Team Name: RUSH B<br />
Roster: executoR, kinqie, Kiro, nota, tex1y<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [99](../standings_global.md)<br />
Regional Rank: [71]( ../standings_europe.md)<br />
Final Rank Value:  871.3<br />
<br />
Final Rank Value (871.3) = Starting Rank Value (759.8) + Head To Head Adjustments (111.6)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.253[<sup>1</sup>](#table2)
- Bounty Collected: 0.353[<sup>2</sup>](#table1)
- Opponent Network: 0.102[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.177<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 759.8
- 400 + ( ( 0.177 - 0.000 ) / ( 0.786 - 0.000 ) ) * 1600 = 759.8


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent               | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                              |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           47 |       75 | 2024-05-29 | VaselineWorms          | W   | 1.000      | 0.143        | -                | 0.424 (0.061)    | 0 (0.000) |    10.57 | executoR, kinqie, Kiro, nota, tex1y |
|           46 |       78 | 2024-05-29 | Team PeeP              | W   | 1.000      | -            | -                | -                | 0 (0.000) |     7.34 | executoR, kinqie, Kiro, nota, tex1y |
|           45 |     1097 | 2024-05-16 | ZEROvariant            | W   | 1.000      | -            | -                | -                | 0 (0.000) |     4.11 | executoR, kinqie, Kiro, nota, tex1y |
|           44 |     1194 | 2024-05-15 | Blue Lock              | W   | 1.000      | -            | -                | -                | 0 (0.000) |     2.31 | executoR, kinqie, Kiro, nota, tex1y |
|           43 |     1327 | 2024-05-13 | Nemiga Gaming          | W   | 1.000      | 0.143        | 0.366 (0.052)    | 0.830 (0.119)    | 0 (0.000) |    27.08 | executoR, kinqie, Kiro, nota, tex1y |
|           42 |     1689 | 2024-05-07 | MOUZ NXT               | L   | 1.000      | -            | -                | -                | -         |    -7.11 | executoR, kinqie, Kiro, nota, tex1y |
|           41 |     1762 | 2024-05-05 | Team Sampi             | L   | 1.000      | -            | -                | -                | -         |    -9.05 | executoR, kinqie, Kiro, nota, tex1y |
|           40 |     1818 | 2024-05-04 | HAVU Gaming            | W   | 1.000      | 0.435        | 0.004 (0.002)    | 0.135 (0.059)    | 0 (0.000) |    11.05 | executoR, kinqie, Kiro, nota, tex1y |
|           39 |     1928 | 2024-05-02 | EYEBALLERS             | L   | 1.000      | -            | -                | -                | -         |   -10.84 | executoR, kinqie, Kiro, nota, tex1y |
|           38 |     2052 | 2024-04-29 | ENCE Academy           | W   | 0.998      | 0.435        | 0.012 (0.005)    | 0.337 (0.146)    | 0 (0.000) |    14.54 | executoR, kinqie, Kiro, nota, tex1y |
|           37 |     2182 | 2024-04-27 | VP.Prodigy             | W   | 0.983      | 0.143        | 0.008 (0.001)    | 0.752 (0.106)    | 0 (0.000) |    13.91 | executoR, kinqie, Kiro, nota, tex1y |
|           36 |     2550 | 2024-04-20 | Grannys Knockers       | L   | 0.938      | -            | -                | -                | -         |   -16.18 | executoR, kinqie, Kiro, nota, tex1y |
|           35 |     2562 | 2024-04-20 | DMS                    | W   | 0.937      | 0.143        | -                | 0.751 (0.101)    | 0 (0.000) |    16.02 | executoR, kinqie, Kiro, nota, tex1y |
|           34 |     2640 | 2024-04-20 | GUN5 Esports           | L   | 0.935      | -            | -                | -                | -         |   -20.59 | executoR, kinqie, Kiro, nota, tex1y |
|           33 |     3020 | 2024-04-13 | Team PeeP              | W   | 0.890      | -            | -                | -                | 0 (0.000) |     5.94 | executoR, kinqie, Kiro, nota, tex1y |
|           32 |     3169 | 2024-04-10 | KOI                    | L   | 0.871      | -            | -                | -                | -         |    -6.08 | executoR, kinqie, Kiro, nota, tex1y |
|           31 |     3237 | 2024-04-09 | PARIVISION             | W   | 0.864      | 0.500        | 0.002 (0.001)    | 0.329 (0.142)    | -         |    17.23 | executoR, kinqie, Kiro, nota, tex1y |
|           30 |     3375 | 2024-04-06 | naChille               | W   | 0.844      | -            | -                | -                | -         |     7.68 | executoR, kinqie, Kiro, nota, tex1y |
|           29 |     3626 | 2024-04-01 | Pera Esports           | L   | 0.810      | -            | -                | -                | -         |   -10.44 | executoR, kinqie, Kiro, nota, tex1y |
|           28 |     3648 | 2024-03-31 | Monte                  | W   | 0.803      | 0.500        | 0.181 (0.073)    | 0.363 (0.146)    | -         |    23.52 | executoR, kinqie, Kiro, nota, tex1y |
|           27 |     3701 | 2024-03-29 | System5                | W   | 0.791      | 0.500        | 0.002 (0.001)    | -                | -         |     9.02 | executoR, kinqie, Kiro, nota, tex1y |
|           26 |     3863 | 2024-03-26 | B8                     | L   | 0.771      | -            | -                | -                | -         |    -2.93 | executoR, kinqie, Kiro, nota, tex1y |
|           25 |     4478 | 2024-03-13 | Betera Esports         | W   | 0.684      | 0.500        | 0.023 (0.008)    | 0.257 (0.088)    | -         |    12.86 | executoR, kinqie, Kiro, nota, tex1y |
|           24 |     4986 | 2024-03-04 | GUN5 Esports           | L   | 0.625      | -            | -                | -                | -         |   -12.99 | executoR, kinqie, Kiro, nota, tex1y |
|           23 |     5003 | 2024-03-04 | HOTU                   | W   | 0.625      | -            | -                | -                | -         |    10.92 | executoR, kinqie, Kiro, nota, tex1y |
|           22 |     5087 | 2024-03-03 | Metizport              | L   | 0.617      | -            | -                | -                | -         |    -3.84 | executoR, kinqie, Kiro, nota, tex1y |
|           21 |     5120 | 2024-03-02 | ex-Guild Eagles        | W   | 0.612      | 0.143        | 0.015 (0.001)    | -                | -         |    14.79 | executoR, kinqie, Kiro, nota, tex1y |
|           20 |     5156 | 2024-03-02 | fragmatic              | W   | 0.611      | -            | -                | -                | -         |     4.05 | executoR, kinqie, Kiro, nota, tex1y |
|           19 |     5410 | 2024-02-26 | SAW                    | L   | 0.578      | -            | -                | -                | -         |    -0.64 | executoR, kinqie, Kiro, nota, tex1y |
|           18 |     6761 | 2024-01-30 | Sashi Esport           | L   | 0.397      | -            | -                | -                | -         |    -1.95 | executoR, kinqie, Kiro, nota, tex1y |
|           17 |     6785 | 2024-01-29 | 1win                   | W   | 0.392      | 0.143        | 0.050 (0.003)    | 0.887 (0.050)    | -         |     9.61 | executoR, kinqie, Kiro, nota, tex1y |
|           16 |     6814 | 2024-01-29 | Jake Bube              | W   | 0.392      | -            | -                | -                | -         |     1.52 | executoR, kinqie, Kiro, nota, tex1y |
|           15 |     7549 | 2024-01-17 | Rebels Gaming          | L   | 0.311      | -            | -                | -                | -         |    -1.15 | executoR, kinqie, Kiro, nota, tex1y |
|           14 |     7677 | 2024-01-16 | LEON Esports           | L   | 0.304      | -            | -                | -                | -         |    -4.85 | executoR, kinqie, Kiro, nota, tex1y |
|           13 |     7855 | 2024-01-12 | BAKS Esports           | L   | 0.278      | -            | -                | -                | -         |    -5.93 | executoR, kinqie, Kiro, nota, tex1y |
|           12 |     7950 | 2024-01-11 | ILIN                   | L   | 0.270      | -            | -                | -                | -         |    -6.69 | executoR, kinqie, Kiro, nota, tex1y |
|           11 |     8012 | 2024-01-10 | TOR                    | W   | 0.265      | -            | -                | -                | -         |     4.70 | executoR, kinqie, Kiro, nota, tex1y |
|           10 |     8596 | 2023-12-16 | TSM                    | W   | 0.098      | -            | -                | -                | -         |     1.03 | executoR, kinqie, Kiro, nota, tex1y |
|            9 |     8742 | 2023-12-15 | IKLA                   | W   | 0.091      | -            | -                | -                | -         |     0.67 | executoR, kinqie, Kiro, nota, tex1y |
|            8 |     8844 | 2023-12-13 | ALTERNATE aTTaX        | L   | 0.077      | -            | -                | -                | -         |    -0.54 | executoR, kinqie, Kiro, nota, tex1y |
|            7 |     8920 | 2023-12-11 | TSM                    | W   | 0.064      | -            | -                | -                | -         |     0.68 | executoR, kinqie, Kiro, nota, tex1y |
|            6 |     8970 | 2023-12-10 | lajtbitexe             | W   | 0.057      | -            | -                | -                | -         |     0.54 | executoR, kinqie, Kiro, nota, tex1y |
|            5 |     9020 | 2023-12-09 | Endpoint               | W   | 0.051      | -            | -                | -                | -         |     1.18 | executoR, kinqie, Kiro, nota, tex1y |
|            4 |     9095 | 2023-12-08 | Lausanne-Sport Esports | W   | 0.045      | -            | -                | -                | -         |     0.40 | executoR, kinqie, Kiro, nota, tex1y |
|            3 |     9153 | 2023-12-07 | TY                     | W   | 0.038      | -            | -                | -                | -         |     0.43 | executoR, kinqie, Kiro, nota, tex1y |
|            2 |     9215 | 2023-12-06 | lajtbitexe             | L   | 0.031      | -            | -                | -                | -         |    -0.68 | executoR, kinqie, Kiro, nota, tex1y |
|            1 |     9301 | 2023-12-05 | The Witchers           | W   | 0.024      | -            | -                | -                | -         |     0.32 | executoR, kinqie, Kiro, nota, tex1y |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($330.86)
- Divide that value by the 5th highest value among all rosters ($300,806.11)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
