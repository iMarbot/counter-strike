### Roster Details<br />
Team Name: Team Sampi<br />
Roster: fino, manguss, sAvana1, The eLiVe, ZEDKO<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [71](../standings_global.md)<br />
Regional Rank: [49]( ../standings_europe.md)<br />
Final Rank Value:  944.2<br />
<br />
Final Rank Value (944.2) = Starting Rank Value (961.7) + Head To Head Adjustments (-17.5)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.414[<sup>1</sup>](#table2)
- Bounty Collected: 0.386[<sup>2</sup>](#table1)
- Opponent Network: 0.303[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.276<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 961.7
- 400 + ( ( 0.276 - 0.000 ) / ( 0.786 - 0.000 ) ) * 1600 = 961.7


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent                  | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                   |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           73 |      127 | 2024-05-28 | ENTERPRISE esports        | L   | 1.000      | -            | -                | -                | -         |   -19.39 | fino, manguss, sAvana1, The eLiVe, ZEDKO |
|           72 |      133 | 2024-05-28 | Rhyno Esports             | W   | 1.000      | 0.435        | 0.029 (0.013)    | -                | 0 (0.000) |    13.58 | fino, manguss, sAvana1, The eLiVe, ZEDKO |
|           71 |      216 | 2024-05-26 | SINNERS Esports           | L   | 1.000      | -            | -                | -                | -         |   -14.82 | fino, manguss, sAvana1, The eLiVe, ZEDKO |
|           70 |      275 | 2024-05-25 | Passion UA                | L   | 1.000      | -            | -                | -                | -         |   -16.15 | fino, manguss, sAvana1, The eLiVe, ZEDKO |
|           69 |      388 | 2024-05-23 | GUN5 Esports              | W   | 1.000      | -            | -                | -                | 0 (0.000) |     8.73 | fino, manguss, sAvana1, The eLiVe, ZEDKO |
|           68 |      448 | 2024-05-22 | VENI VIDI VICI            | W   | 1.000      | -            | -                | -                | 0 (0.000) |     3.91 | fino, manguss, sAvana1, The eLiVe, ZEDKO |
|           67 |      697 | 2024-05-20 | Illuminar Gaming          | W   | 1.000      | -            | -                | -                | 0 (0.000) |     7.99 | fino, manguss, sAvana1, The eLiVe, ZEDKO |
|           66 |      718 | 2024-05-20 | Verdant                   | L   | 1.000      | -            | -                | -                | -         |   -16.42 | fino, manguss, sAvana1, The eLiVe, ZEDKO |
|           65 |      922 | 2024-05-18 | DMS                       | L   | 1.000      | -            | -                | -                | -         |   -19.17 | fino, manguss, sAvana1, The eLiVe, ZEDKO |
|           64 |      977 | 2024-05-17 | EP Genesis                | W   | 1.000      | -            | -                | -                | 0 (0.000) |     2.76 | fino, manguss, sAvana1, The eLiVe, ZEDKO |
|           63 |     1069 | 2024-05-16 | VENI VIDI VICI            | W   | 1.000      | -            | -                | -                | 0 (0.000) |     3.66 | fino, manguss, sAvana1, The eLiVe, ZEDKO |
|           62 |     1102 | 2024-05-16 | B8                        | L   | 1.000      | -            | -                | -                | -         |   -10.15 | fino, manguss, sAvana1, The eLiVe, ZEDKO |
|           61 |     1331 | 2024-05-13 | Nexus Gaming              | W   | 1.000      | 0.435        | -                | 0.825 (0.358)    | 0 (0.000) |     9.19 | fino, manguss, sAvana1, The eLiVe, ZEDKO |
|           60 |     1552 | 2024-05-09 | BLEED Esports             | L   | 1.000      | -            | -                | -                | -         |    -7.71 | fino, manguss, sAvana1, The eLiVe, ZEDKO |
|           59 |     1762 | 2024-05-05 | RUSH B                    | W   | 1.000      | -            | -                | -                | 0 (0.000) |     9.05 | fino, manguss, sAvana1, The eLiVe, ZEDKO |
|           58 |     1920 | 2024-05-02 | Permitta Esports          | W   | 1.000      | 0.435        | 0.029 (0.012)    | 1.000 (0.435)    | 0 (0.000) |    12.25 | fino, manguss, sAvana1, The eLiVe, ZEDKO |
|           57 |     1993 | 2024-05-01 | ALTERNATE aTTaX           | L   | 1.000      | -            | -                | -                | -         |   -16.88 | fino, manguss, sAvana1, The eLiVe, ZEDKO |
|           56 |     2002 | 2024-05-01 | ENCE Academy              | W   | 1.000      | -            | -                | -                | 0 (0.000) |     7.45 | fino, manguss, sAvana1, The eLiVe, ZEDKO |
|           55 |     2013 | 2024-04-30 | GamerLegion Academy       | W   | 1.000      | 0.435        | -                | 0.691 (0.300)    | -         |    10.09 | fino, manguss, sAvana1, The eLiVe, ZEDKO |
|           54 |     2042 | 2024-04-30 | ALTERNATE aTTaX           | L   | 1.000      | -            | -                | -                | -         |   -17.81 | fino, manguss, sAvana1, The eLiVe, ZEDKO |
|           53 |     2334 | 2024-04-25 | Dynamo Eclot              | L   | 0.968      | -            | -                | -                | -         |   -16.46 | fino, manguss, sAvana1, The eLiVe, ZEDKO |
|           52 |     2394 | 2024-04-24 | Permitta Esports          | W   | 0.961      | 0.371        | -                | 1.000 (0.356)    | -         |    12.86 | fino, manguss, sAvana1, The eLiVe, ZEDKO |
|           51 |     2434 | 2024-04-23 | Dynamo Eclot              | L   | 0.955      | -            | -                | -                | -         |   -15.02 | fino, manguss, sAvana1, The eLiVe, ZEDKO |
|           50 |     2531 | 2024-04-21 | ALTERNATE aTTaX           | W   | 0.941      | 0.371        | 0.052 (0.018)    | 0.679 (0.237)    | -         |    10.97 | fino, manguss, sAvana1, The eLiVe, ZEDKO |
|           49 |     2728 | 2024-04-19 | BLEED Esports             | L   | 0.928      | -            | -                | -                | -         |    -6.91 | fino, manguss, sAvana1, The eLiVe, ZEDKO |
|           48 |     2798 | 2024-04-18 | Permitta Esports          | W   | 0.921      | 0.371        | -                | 1.000 (0.341)    | -         |    13.78 | fino, manguss, sAvana1, The eLiVe, ZEDKO |
|           47 |     2855 | 2024-04-17 | NOM Esports               | L   | 0.916      | -            | -                | -                | -         |   -25.31 | fino, manguss, sAvana1, The eLiVe, ZEDKO |
|           46 |     2926 | 2024-04-16 | SAW                       | W   | 0.909      | 0.384        | 0.112 (0.039)    | -                | -         |    25.36 | fino, manguss, sAvana1, The eLiVe, ZEDKO |
|           45 |     2931 | 2024-04-16 | Team Secret               | W   | 0.908      | -            | -                | -                | -         |     4.11 | fino, manguss, sAvana1, The eLiVe, ZEDKO |
|           44 |     2958 | 2024-04-15 | ENCE Academy              | L   | 0.903      | -            | -                | -                | -         |   -20.48 | fino, manguss, sAvana1, The eLiVe, ZEDKO |
|           43 |     3051 | 2024-04-13 | BetBoom Team              | L   | 0.888      | -            | -                | -                | -         |    -3.72 | fino, manguss, sAvana1, The eLiVe, ZEDKO |
|           42 |     3134 | 2024-04-11 | ex-Turów Zgorzelec Esport | W   | 0.874      | -            | -                | -                | -         |     5.27 | fino, manguss, sAvana1, The eLiVe, ZEDKO |
|           41 |     3411 | 2024-04-06 | ENTERPRISE esports        | W   | 0.842      | -            | -                | -                | -         |     8.77 | fino, manguss, sAvana1, The eLiVe, ZEDKO |
|           40 |     3575 | 2024-04-03 | Ninjas in Pyjamas         | W   | 0.822      | 0.384        | 0.118 (0.037)    | -                | -         |    17.63 | fino, manguss, sAvana1, The eLiVe, ZEDKO |
|           39 |     3798 | 2024-03-27 | B8                        | L   | 0.777      | -            | -                | -                | -         |    -6.77 | fino, manguss, sAvana1, The eLiVe, ZEDKO |
|           38 |     3816 | 2024-03-27 | BLEED Esports             | W   | 0.777      | 0.143        | 0.248 (0.028)    | -                | -         |    19.04 | fino, manguss, sAvana1, The eLiVe, ZEDKO |
|           37 |     3873 | 2024-03-26 | DUSTY                     | W   | 0.771      | -            | -                | -                | -         |     4.50 | fino, manguss, sAvana1, The eLiVe, ZEDKO |
|           36 |     4224 | 2024-03-18 | ex-Preasy Esport          | L   | 0.715      | -            | -                | -                | -         |    -9.97 | fino, manguss, sAvana1, The eLiVe, ZEDKO |
|           35 |     4297 | 2024-03-17 | Passion UA                | W   | 0.708      | 0.371        | 0.057 (0.015)    | 1.000 (0.262)    | -         |    10.37 | fino, manguss, sAvana1, The eLiVe, ZEDKO |
|           34 |     4332 | 2024-03-16 | SINNERS Esports           | L   | 0.703      | -            | -                | -                | -         |   -10.88 | fino, manguss, sAvana1, The eLiVe, ZEDKO |
|           33 |     4339 | 2024-03-16 | MOUZ NXT                  | W   | 0.702      | 0.371        | 0.157 (0.041)    | 0.950 (0.247)    | -         |    14.04 | fino, manguss, sAvana1, The eLiVe, ZEDKO |
|           32 |     4382 | 2024-03-15 | Dynamo Eclot              | L   | 0.696      | -            | -                | -                | -         |    -8.74 | fino, manguss, sAvana1, The eLiVe, ZEDKO |
|           31 |     4394 | 2024-03-15 | Permitta Esports          | W   | 0.695      | 0.371        | -                | 1.000 (0.258)    | -         |    11.58 | fino, manguss, sAvana1, The eLiVe, ZEDKO |
|           30 |     4443 | 2024-03-14 | Passion UA                | L   | 0.689      | -            | -                | -                | -         |   -11.38 | fino, manguss, sAvana1, The eLiVe, ZEDKO |
|           29 |     4574 | 2024-03-12 | MOUZ NXT                  | W   | 0.675      | 0.371        | 0.157 (0.039)    | 0.950 (0.237)    | -         |    14.14 | fino, manguss, sAvana1, The eLiVe, ZEDKO |
|           28 |     4674 | 2024-03-10 | Sashi Esport              | W   | 0.662      | 0.143        | 0.172 (0.016)    | -                | -         |    12.92 | fino, manguss, sAvana1, The eLiVe, ZEDKO |
|           27 |     4736 | 2024-03-09 | ENTERPRISE esports        | W   | 0.656      | -            | -                | -                | -         |     9.71 | fino, manguss, sAvana1, The eLiVe, ZEDKO |
|           26 |     4913 | 2024-03-06 | AURA                      | W   | 0.635      | -            | -                | -                | -         |     4.04 | fino, manguss, sAvana1, The eLiVe, ZEDKO |
|           25 |     4966 | 2024-03-05 | UNiTY esports             | W   | 0.630      | -            | -                | -                | -         |     7.37 | fino, manguss, sAvana1, The eLiVe, ZEDKO |
|           24 |     5046 | 2024-03-04 | Lan Party Hotel           | W   | 0.623      | -            | -                | -                | -         |     1.06 | fino, manguss, sAvana1, The eLiVe, ZEDKO |
|           23 |     5052 | 2024-03-04 | Sangal Esports            | L   | 0.622      | -            | -                | -                | -         |    -7.76 | fino, manguss, sAvana1, The eLiVe, ZEDKO |
|           22 |     5214 | 2024-03-02 | ENTERPRISE esports        | L   | 0.608      | -            | -                | -                | -         |    -9.54 | fino, manguss, sAvana1, The eLiVe, ZEDKO |
|           21 |     5468 | 2024-02-25 | Dynamo Eclot              | L   | 0.568      | -            | -                | -                | -         |    -5.64 | fino, manguss, sAvana1, The eLiVe, ZEDKO |
|           20 |     5623 | 2024-02-23 | Entropiq                  | W   | 0.555      | -            | -                | -                | -         |     3.61 | fino, manguss, sAvana1, The eLiVe, ZEDKO |
|           19 |     5731 | 2024-02-21 | Sashi Esport              | L   | 0.543      | -            | -                | -                | -         |    -5.13 | fino, manguss, sAvana1, The eLiVe, ZEDKO |
|           18 |     5850 | 2024-02-19 | Viperio                   | W   | 0.529      | -            | -                | -                | -         |     2.78 | fino, manguss, sAvana1, The eLiVe, ZEDKO |
|           17 |     5892 | 2024-02-18 | BIG Academy               | L   | 0.522      | -            | -                | -                | -         |   -12.42 | fino, manguss, sAvana1, The eLiVe, ZEDKO |
|           16 |     5957 | 2024-02-17 | Team Secret               | W   | 0.516      | -            | -                | -                | -         |     2.75 | fino, manguss, sAvana1, The eLiVe, ZEDKO |
|           15 |     6131 | 2024-02-14 | Viperio                   | W   | 0.495      | -            | -                | -                | -         |     2.26 | fino, manguss, sAvana1, The eLiVe, ZEDKO |
|           14 |     6262 | 2024-02-10 | Zero Tenacity             | W   | 0.471      | -            | -                | -                | -         |     9.65 | fino, sAvana1, T4gg3D, The eLiVe, ZEDKO  |
|           13 |     6570 | 2024-02-03 | Sashi Esport              | W   | 0.422      | -            | -                | -                | -         |     8.98 | fino, sAvana1, T4gg3D, The eLiVe, ZEDKO  |
|           12 |     6600 | 2024-02-02 | B8                        | L   | 0.417      | -            | -                | -                | -         |    -3.53 | fino, sAvana1, T4gg3D, The eLiVe, ZEDKO  |
|           11 |     6618 | 2024-02-02 | ghoulsW                   | W   | 0.417      | -            | -                | -                | -         |     0.96 | fino, sAvana1, T4gg3D, The eLiVe, ZEDKO  |
|           10 |     6629 | 2024-02-02 | ZOTIX                     | W   | 0.417      | -            | -                | -                | -         |     0.63 | fino, sAvana1, T4gg3D, The eLiVe, ZEDKO  |
|            9 |     6683 | 2024-02-01 | Metizport                 | L   | 0.409      | -            | -                | -                | -         |    -6.02 | fino, sAvana1, T4gg3D, The eLiVe, ZEDKO  |
|            8 |     6789 | 2024-01-29 | Insilio                   | L   | 0.392      | -            | -                | -                | -         |    -6.49 | fino, sAvana1, T4gg3D, The eLiVe, ZEDKO  |
|            7 |     7180 | 2024-01-23 | ex-Guild Eagles           | L   | 0.351      | -            | -                | -                | -         |    -5.11 | fino, sAvana1, T4gg3D, The eLiVe, ZEDKO  |
|            6 |     7184 | 2024-01-23 | Viperio                   | L   | 0.350      | -            | -                | -                | -         |    -9.88 | fino, sAvana1, T4gg3D, The eLiVe, ZEDKO  |
|            5 |     7210 | 2024-01-22 | Rebels Gaming             | W   | 0.344      | -            | -                | -                | -         |     7.47 | fino, sAvana1, T4gg3D, The eLiVe, ZEDKO  |
|            4 |     7224 | 2024-01-22 | Pera Esports              | W   | 0.344      | -            | -                | -                | -         |     5.02 | fino, sAvana1, T4gg3D, The eLiVe, ZEDKO  |
|            3 |     7233 | 2024-01-22 | ALTERNATE aTTaX           | L   | 0.344      | -            | -                | -                | -         |    -8.46 | fino, sAvana1, T4gg3D, The eLiVe, ZEDKO  |
|            2 |     8095 | 2024-01-09 | HAVU Gaming               | L   | 0.257      | -            | -                | -                | -         |    -6.10 | fino, sAvana1, T4gg3D, The eLiVe, ZEDKO  |
|            1 |     8104 | 2024-01-09 | WOPA Esport               | W   | 0.257      | -            | -                | -                | -         |     2.49 | fino, sAvana1, T4gg3D, The eLiVe, ZEDKO  |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($11,582.24)
- Divide that value by the 5th highest value among all rosters ($300,806.11)
- The final value (0.04) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-05-18 |      1.000 | $1,000.00      | $1,000.00       |
| 2024-04-25 |      0.968 | $5,000.00      | $4,838.89       |
| 2024-04-14 |      0.896 | $1,905.29      | $1,706.82       |
| 2024-03-18 |      0.715 | $5,000.00      | $3,575.00       |
| 2024-03-17 |      0.711 | $649.40        | $461.53         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
