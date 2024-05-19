### Roster Details<br />
Team Name: Endpoint<br />
Roster: AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [63](../standings_global.md)<br />
Regional Rank: [47]( ../standings_europe.md)<br />
Final Rank Value:  946.8<br />
<br />
Final Rank Value (946.8) = Starting Rank Value (846.4) + Head To Head Adjustments (100.3)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.301[<sup>1</sup>](#table2)
- Bounty Collected: 0.379[<sup>2</sup>](#table1)
- Opponent Network: 0.220[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.225<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 846.4
- 400 + ( ( 0.225 - 0.000 ) / ( 0.806 - 0.000 ) ) * 1600 = 846.4


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent                    | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins      | H2H Adj. | Roster                                     |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           68 |       23 | 2024-05-05 | SINNERS Esports             | L   | 1.000      | -            | -                | -                | -             |   -16.50 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal  |
|           67 |      138 | 2024-05-02 | MOUZ NXT                    | W   | 1.000      | 0.435        | 0.215 (0.094)    | 1.000 (0.435)    | false (0.000) |    20.17 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal  |
|           66 |      155 | 2024-05-02 | Grannys Knockers            | W   | 1.000      | 0.384        | 0.061 (0.023)    | -                | false (0.000) |    13.82 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal  |
|           65 |      241 | 2024-04-30 | ALTERNATE aTTaX             | W   | 1.000      | 0.143        | 0.110 (0.016)    | -                | false (0.000) |    16.48 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal  |
|           64 |      246 | 2024-04-30 | ENCE Academy                | W   | 1.000      | -            | -                | -                | false (0.000) |    10.86 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal  |
|           63 |      275 | 2024-04-29 | Nexus Gaming                | W   | 1.000      | 0.435        | 0.031 (0.014)    | 0.772 (0.335)    | false (0.000) |    16.27 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal  |
|           62 |      291 | 2024-04-29 | Alliance                    | L   | 1.000      | -            | -                | -                | -             |   -17.59 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal  |
|           61 |      544 | 2024-04-24 | SINNERS Esports             | W   | 1.000      | 0.384        | 0.038 (0.014)    | 0.534 (0.205)    | false (0.000) |    20.10 | AZUWU, HS, MiGHTYMAX, Surreal, swicher     |
|           60 |      977 | 2024-04-17 | EYEBALLERS                  | W   | 1.000      | 0.384        | 0.051 (0.020)    | 0.533 (0.205)    | false (0.000) |    17.68 | AZUWU, HS, MiGHTYMAX, Surreal, swicher     |
|           59 |     2223 | 2024-03-15 | Ex-sYnck                    | W   | 0.857      | -            | -                | -                | false (0.000) |     5.39 | AZUWU, HS, MiGHTYMAX, sl3nd, Surreal       |
|           58 |     2269 | 2024-03-14 | The Chosen Few              | L   | 0.852      | -            | -                | -                | -             |   -13.28 | AZUWU, MiGHTYMAX, sl3nd, Surreal, swicher  |
|           57 |     2387 | 2024-03-12 | Team Secret                 | W   | 0.836      | -            | -                | -                | false (0.000) |     6.06 | AZUWU, HS, MiGHTYMAX, sl3nd, Surreal       |
|           56 |     2461 | 2024-03-10 | Nemiga Gaming               | L   | 0.825      | -            | -                | -                | -             |    -2.10 | AZUWU, MiGHTYMAX, sl3nd, Surreal, swicher  |
|           55 |     2628 | 2024-03-06 | V1dar Gaming                | W   | 0.798      | -            | -                | -                | false (0.000) |     6.34 | AZUWU, MiGHTYMAX, sl3nd, Surreal, swicher  |
|           54 |     2705 | 2024-03-05 | GODSENT                     | W   | 0.791      | 0.384        | 0.026 (0.008)    | 0.423 (0.129)    | -             |    11.16 | AZUWU, MiGHTYMAX, sl3nd, Surreal, swicher  |
|           53 |     2767 | 2024-03-04 | JANO Esports                | W   | 0.784      | -            | -                | -                | -             |     9.86 | AZUWU, HS, MiGHTYMAX, sl3nd, Surreal       |
|           52 |     2845 | 2024-03-02 | GUN5 Esports                | L   | 0.772      | -            | -                | -                | -             |   -18.37 | AZUWU, MiGHTYMAX, sl3nd, Surreal, swicher  |
|           51 |     2911 | 2024-03-01 | NOM Esports                 | W   | 0.766      | -            | -                | -                | -             |     6.80 | AZUWU, MiGHTYMAX, sl3nd, Surreal, swicher  |
|           50 |     2914 | 2024-03-01 | TBA.ECF                     | W   | 0.765      | 0.371        | -                | 0.460 (0.131)    | -             |     8.57 | AZUWU, MiGHTYMAX, sl3nd, Surreal, swicher  |
|           49 |     2965 | 2024-02-29 | Metizport                   | L   | 0.757      | -            | -                | -                | -             |    -5.26 | AZUWU, MiGHTYMAX, sl3nd, Surreal, swicher  |
|           48 |     2980 | 2024-02-28 | ARCRED                      | W   | 0.752      | 0.371        | -                | 0.825 (0.230)    | -             |    11.75 | AZUWU, MiGHTYMAX, sl3nd, Surreal, swicher  |
|           47 |     3079 | 2024-02-26 | ALTERNATE aTTaX             | L   | 0.736      | -            | -                | -                | -             |    -7.63 | AZUWU, HS, MiGHTYMAX, sl3nd, Surreal       |
|           46 |     3290 | 2024-02-21 | Aurora Young Blud           | L   | 0.706      | -            | -                | -                | -             |   -12.39 | AZUWU, MiGHTYMAX, sl3nd, Surreal, swicher  |
|           45 |     3413 | 2024-02-19 | Nemiga Gaming               | L   | 0.691      | -            | -                | -                | -             |    -1.61 | AZUWU, MiGHTYMAX, sl3nd, Surreal, swicher  |
|           44 |     3530 | 2024-02-16 | CYBERSHOKE Esports          | W   | 0.672      | -            | -                | -                | -             |     6.85 | AZUWU, MiGHTYMAX, sl3nd, Surreal, swicher  |
|           43 |     3574 | 2024-02-15 | Golden Sword                | W   | 0.666      | -            | -                | -                | -             |     1.48 | AZUWU, MiGHTYMAX, sl3nd, Surreal, swicher  |
|           42 |     3725 | 2024-02-12 | The Chosen Few              | L   | 0.645      | -            | -                | -                | -             |   -11.93 | AZUWU, MiGHTYMAX, sl3nd, Surreal, swicher  |
|           41 |     3794 | 2024-02-09 | 3DMAX                       | L   | 0.625      | -            | -                | -                | -             |    -7.30 | AZUWU, MiGHTYMAX, sl3nd, Surreal, swicher  |
|           40 |     3799 | 2024-02-09 | Fnatic                      | L   | 0.624      | -            | -                | -                | -             |    -2.37 | AZUWU, MiGHTYMAX, sl3nd, Surreal, swicher  |
|           39 |     3819 | 2024-02-08 | EsmagaB                     | W   | 0.618      | 0.371        | -                | 0.559 (0.128)    | -             |     9.65 | AZUWU, MiGHTYMAX, sl3nd, Surreal, swicher  |
|           38 |     3840 | 2024-02-07 | GenOne                      | L   | 0.612      | -            | -                | -                | -             |   -16.17 | AZUWU, MiGHTYMAX, sl3nd, Surreal, swicher  |
|           37 |     3848 | 2024-02-07 | Permitta Esports            | W   | 0.610      | 0.384        | 0.063 (0.015)    | 1.000 (0.234)    | -             |    12.50 | AZUWU, MiGHTYMAX, sl3nd, Surreal, swicher  |
|           36 |     3860 | 2024-02-06 | UNiTY esports (Slovak team) | W   | 0.605      | 0.371        | 0.055 (0.012)    | 0.727 (0.163)    | -             |    11.46 | AZUWU, MiGHTYMAX, sl3nd, Surreal, swicher  |
|           35 |     3969 | 2024-02-03 | Viperio                     | W   | 0.585      | -            | -                | -                | -             |     4.29 | AZUWU, MiGHTYMAX, sl3nd, Surreal, swicher  |
|           34 |     3984 | 2024-02-03 | XD (British team)           | W   | 0.584      | -            | -                | -                | -             |     1.36 | AZUWU, MiGHTYMAX, sl3nd, Surreal, swicher  |
|           33 |     4024 | 2024-02-02 | FLuffy Gangsters            | W   | 0.578      | -            | -                | -                | -             |     3.15 | AZUWU, MiGHTYMAX, sl3nd, Surreal, swicher  |
|           32 |     4151 | 2024-01-30 | Entropiq                    | W   | 0.557      | -            | -                | -                | -             |     7.88 | AZUWU, MiGHTYMAX, sl3nd, Surreal, swicher  |
|           31 |     4178 | 2024-01-29 | Nemiga Gaming               | L   | 0.553      | -            | -                | -                | -             |    -1.25 | AZUWU, MiGHTYMAX, sl3nd, Surreal, swicher  |
|           30 |     4708 | 2024-01-17 | Insilio                     | L   | 0.473      | -            | -                | -                | -             |    -5.79 | AZUWU, MiGHTYMAX, sl3nd, Surreal, swicher  |
|           29 |     4731 | 2024-01-17 | Sashi Esport                | W   | 0.472      | -            | -                | -                | -             |     2.15 | AZUWU, MiGHTYMAX, sl3nd, Surreal, swicher  |
|           28 |     4777 | 2024-01-16 | Nexus Gaming                | L   | 0.466      | -            | -                | -                | -             |    -5.78 | AZUWU, MiGHTYMAX, sl3nd, Surreal, swicher  |
|           27 |     4781 | 2024-01-16 | 00 Nation                   | W   | 0.466      | -            | -                | -                | -             |     2.01 | AZUWU, MiGHTYMAX, sl3nd, Surreal, swicher  |
|           26 |     4789 | 2024-01-16 | GUN5 Esports                | W   | 0.466      | -            | -                | -                | -             |     3.95 | AZUWU, MiGHTYMAX, sl3nd, Surreal, swicher  |
|           25 |     4813 | 2024-01-16 | XI Esport                   | W   | 0.465      | -            | -                | -                | -             |     4.54 | AZUWU, MiGHTYMAX, sl3nd, Surreal, swicher  |
|           24 |     5005 | 2024-01-11 | ILIN                        | L   | 0.431      | -            | -                | -                | -             |   -11.23 | AZUWU, MiGHTYMAX, sl3nd, Surreal, swicher  |
|           23 |     5034 | 2024-01-10 | GRGECHI                     | W   | 0.426      | -            | -                | -                | -             |     2.20 | AZUWU, MiGHTYMAX, sl3nd, Surreal, swicher  |
|           22 |     5763 | 2023-12-09 | RUSH B (Russian team)       | L   | 0.212      | -            | -                | -                | -             |    -3.92 | AZUWU, HeavyGod, MiGHTYMAX, sl3nd, Surreal |
|           21 |     5781 | 2023-12-09 | Preasy Esport               | L   | 0.210      | -            | -                | -                | -             |    -2.40 | AZUWU, HeavyGod, MiGHTYMAX, sl3nd, Surreal |
|           20 |     5884 | 2023-12-07 | BIG Academy                 | L   | 0.199      | -            | -                | -                | -             |    -3.36 | AZUWU, HeavyGod, MiGHTYMAX, sl3nd, Surreal |
|           19 |     5921 | 2023-12-06 | MOUZ NXT                    | W   | 0.192      | 0.371        | 0.215 (0.015)    | -                | -             |     4.82 | AZUWU, HeavyGod, MiGHTYMAX, sl3nd, Surreal |
|           18 |     5975 | 2023-12-05 | ENTERPRISE esports          | W   | 0.186      | -            | -                | -                | -             |     3.75 | AZUWU, HeavyGod, MiGHTYMAX, sl3nd, Surreal |
|           17 |     6023 | 2023-12-04 | The Witchers                | W   | 0.177      | -            | -                | -                | -             |     2.35 | AZUWU, HeavyGod, MiGHTYMAX, sl3nd, Surreal |
|           16 |     6219 | 2023-11-30 | GODSENT                     | L   | 0.150      | -            | -                | -                | -             |    -2.67 | AZUWU, HeavyGod, MiGHTYMAX, sl3nd, Surreal |
|           15 |     6316 | 2023-11-28 | LF0                         | L   | 0.138      | -            | -                | -                | -             |    -3.32 | AZUWU, HeavyGod, MiGHTYMAX, sl3nd, Surreal |
|           14 |     6325 | 2023-11-28 | GenOne                      | W   | 0.138      | -            | -                | -                | -             |     0.96 | AZUWU, HeavyGod, MiGHTYMAX, sl3nd, Surreal |
|           13 |     6353 | 2023-11-27 | L&G                         | W   | 0.132      | -            | -                | -                | -             |     0.48 | AZUWU, HeavyGod, MiGHTYMAX, sl3nd, Surreal |
|           12 |     6407 | 2023-11-26 | Into The Breach             | W   | 0.123      | -            | -                | -                | -             |     1.73 | AZUWU, HeavyGod, MiGHTYMAX, sl3nd, Surreal |
|           11 |     6471 | 2023-11-24 | Underrated                  | W   | 0.112      | -            | -                | -                | -             |     0.40 | AZUWU, HeavyGod, MiGHTYMAX, sl3nd, Surreal |
|           10 |     6583 | 2023-11-21 | Pera Esports                | L   | 0.092      | -            | -                | -                | -             |    -1.16 | AZUWU, HeavyGod, MiGHTYMAX, sl3nd, Surreal |
|            9 |     6622 | 2023-11-20 | Los Alpacas                 | W   | 0.086      | -            | -                | -                | -             |     0.63 | AZUWU, HeavyGod, MiGHTYMAX, sl3nd, Surreal |
|            8 |     6637 | 2023-11-20 | L&G                         | W   | 0.085      | -            | -                | -                | -             |     0.41 | AZUWU, HeavyGod, MiGHTYMAX, sl3nd, Surreal |
|            7 |     6720 | 2023-11-18 | Verdant                     | W   | 0.071      | -            | -                | -                | -             |     1.57 | AZUWU, HeavyGod, MiGHTYMAX, sl3nd, Surreal |
|            6 |     6743 | 2023-11-18 | Raptors Esports Club        | W   | 0.070      | -            | -                | -                | -             |     1.17 | AZUWU, HeavyGod, MiGHTYMAX, sl3nd, Surreal |
|            5 |     6926 | 2023-11-14 | Legacy                      | L   | 0.045      | -            | -                | -                | -             |    -0.24 | AZUWU, HeavyGod, MiGHTYMAX, sl3nd, Surreal |
|            4 |     6989 | 2023-11-13 | Entropiq                    | W   | 0.036      | -            | -                | -                | -             |     0.49 | AZUWU, HeavyGod, MiGHTYMAX, sl3nd, Surreal |
|            3 |     6994 | 2023-11-12 | Preasy Esport               | L   | 0.032      | -            | -                | -                | -             |    -0.37 | AZUWU, HeavyGod, MiGHTYMAX, sl3nd, Surreal |
|            2 |     7007 | 2023-11-12 | Legacy                      | W   | 0.031      | -            | -                | -                | -             |     0.81 | AZUWU, HeavyGod, MiGHTYMAX, sl3nd, Surreal |
|            1 |     7162 | 2023-11-08 | XGOD                        | W   | 0.006      | -            | -                | -                | -             |     0.02 | AZUWU, HeavyGod, MiGHTYMAX, sl3nd, Surreal |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($759.09)
- Divide that value by the 5th highest value among all rosters ($158,437.64)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2023-12-13 |      0.238 | $1,250.00      | $297.51         |
| 2023-11-21 |      0.092 | $5,000.00      | $461.57         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
