### Roster Details<br />
Team Name: ATOX Esports<br />
Roster: ANNIHILATION, dobu, kabal, MiQ, Zesta<br />
Region: [Asia]( ../standings_asia.md)<br />
<br />
Global Rank: [44](../standings_global.md)<br />
Regional Rank: [4]( ../standings_asia.md)<br />
Final Rank Value:  1066.2<br />
<br />
Final Rank Value (1066.2) = Starting Rank Value (1097.6) + Head To Head Adjustments (-31.5)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.513[<sup>1</sup>](#table2)
- Bounty Collected: 0.346[<sup>2</sup>](#table1)
- Opponent Network: 0.108[<sup>2</sup>](#table1)
- LAN Wins: 0.440[<sup>2</sup>](#table1)

The average of these factors is 0.352<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1097.6
- 400 + ( ( 0.352 - 0.000 ) / ( 0.806 - 0.000 ) ) * 1600 = 1097.6


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent                     | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins      | H2H Adj. | Roster                                |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           75 |      656 | 2024-04-21 | Rare Atom                    | L   | 1.000      | -            | -                | -                | -             |   -21.57 | ANNIHILATION, dobu, kabal, MiQ, Zesta |
|           74 |      671 | 2024-04-21 | Lynn Vision Gaming           | W   | 1.000      | 0.143        | 0.155 (0.022)    | 0.554 (0.079)    | false (0.000) |    18.99 | ANNIHILATION, dobu, kabal, MiQ, Zesta |
|           73 |      743 | 2024-04-20 | Clutch Gaming                | W   | 1.000      | 0.417        | -                | 0.216 (0.090)    | false (0.000) |     5.52 | ANNIHILATION, dobu, kabal, MiQ, Zesta |
|           72 |      756 | 2024-04-20 | Clutch Gaming                | W   | 1.000      | 0.417        | -                | 0.216 (0.090)    | false (0.000) |     5.82 | ANNIHILATION, dobu, kabal, MiQ, Zesta |
|           71 |      839 | 2024-04-19 | Born In Far East             | W   | 1.000      | -            | -                | -                | -             |     4.03 | ANNIHILATION, dobu, kabal, MiQ, Zesta |
|           70 |      844 | 2024-04-19 | Born In Far East             | W   | 1.000      | -            | -                | -                | -             |     4.20 | ANNIHILATION, dobu, kabal, MiQ, Zesta |
|           69 |      893 | 2024-04-18 | Bigetron Fury                | W   | 1.000      | -            | -                | -                | -             |     1.77 | ANNIHILATION, dobu, kabal, MiQ, Zesta |
|           68 |      896 | 2024-04-18 | Steel Helmet                 | W   | 1.000      | 0.143        | 0.025 (0.004)    | -                | -             |     3.84 | ANNIHILATION, dobu, kabal, MiQ, Zesta |
|           67 |     1012 | 2024-04-16 | MIRAI Gaming                 | L   | 1.000      | -            | -                | -                | -             |   -27.45 | ANNIHILATION, dobu, kabal, MiQ, Zesta |
|           66 |     1075 | 2024-04-14 | The MongolZ                  | L   | 1.000      | -            | -                | -                | -             |    -1.98 | ANNIHILATION, dobu, kabal, MiQ, Zesta |
|           65 |     1083 | 2024-04-14 | IHC Esports                  | W   | 1.000      | -            | -                | -                | true (1.000)  |     7.04 | ANNIHILATION, dobu, kabal, MiQ, Zesta |
|           64 |     1235 | 2024-04-10 | The MongolZ                  | L   | 1.000      | -            | -                | -                | -             |    -1.95 | ANNIHILATION, dobu, kabal, MiQ, Zesta |
|           63 |     1240 | 2024-04-10 | The MongolZ                  | L   | 1.000      | -            | -                | -                | -             |    -1.99 | ANNIHILATION, dobu, kabal, MiQ, Zesta |
|           62 |     1299 | 2024-04-09 | High Five (Chinese team)     | L   | 1.000      | -            | -                | -                | -             |   -26.04 | ANNIHILATION, dobu, kabal, MiQ, Zesta |
|           61 |     1304 | 2024-04-09 | High Five (Chinese team)     | W   | 1.000      | 0.417        | 0.045 (0.019)    | 0.282 (0.117)    | -             |     4.98 | ANNIHILATION, dobu, kabal, MiQ, Zesta |
|           60 |     1347 | 2024-04-08 | The MongolZ                  | L   | 1.000      | -            | -                | -                | -             |    -2.28 | ANNIHILATION, dobu, kabal, MiQ, Zesta |
|           59 |     1380 | 2024-04-06 | The Huns Esports             | W   | 1.000      | -            | -                | -                | true (1.000)  |     8.47 | ANNIHILATION, dobu, kabal, MiQ, Zesta |
|           58 |     1448 | 2024-04-05 | DEWA United                  | W   | 0.997      | -            | -                | -                | -             |     1.60 | ANNIHILATION, dobu, kabal, MiQ, Zesta |
|           57 |     1449 | 2024-04-05 | DEWA United                  | W   | 0.997      | -            | -                | -                | -             |     1.62 | ANNIHILATION, dobu, kabal, MiQ, Zesta |
|           56 |     1587 | 2024-04-02 | The MongolZ                  | L   | 0.977      | -            | -                | -                | -             |    -2.21 | ANNIHILATION, dobu, kabal, MiQ, zesta |
|           55 |     1594 | 2024-04-02 | Lynn Vision Gaming           | L   | 0.976      | -            | -                | -                | -             |    -9.73 | ANNIHILATION, dobu, kabal, MiQ, zesta |
|           54 |     1765 | 2024-03-27 | The QUBE Esports             | W   | 0.937      | -            | -                | -                | -             |     4.74 | ANNIHILATION, dobu, kabal, MiQ, Zesta |
|           53 |     1769 | 2024-03-27 | The QUBE Esports             | W   | 0.937      | -            | -                | -                | -             |     4.96 | ANNIHILATION, dobu, kabal, MiQ, Zesta |
|           52 |     2273 | 2024-03-14 | LYG Gaming                   | W   | 0.851      | 0.417        | -                | 0.380 (0.135)    | -             |     4.75 | ANNIHILATION, dobu, kabal, MiQ, Zesta |
|           51 |     2278 | 2024-03-14 | LYG Gaming                   | L   | 0.851      | -            | -                | -                | -             |   -22.52 | ANNIHILATION, dobu, kabal, MiQ, Zesta |
|           50 |     2338 | 2024-03-13 | -72C                         | W   | 0.843      | -            | -                | -                | -             |     4.44 | dobu, flyNN, kabal, MiQ, zesta        |
|           49 |     2341 | 2024-03-13 | ROUX from hell               | W   | 0.843      | -            | -                | -                | -             |     0.96 | dobu, flyNN, kabal, MiQ, zesta        |
|           48 |     2385 | 2024-03-12 | Magadan                      | W   | 0.837      | -            | -                | -                | -             |     0.52 | dobu, flyNN, kabal, MiQ, zesta        |
|           47 |     2436 | 2024-03-11 | High Five (Chinese team)     | W   | 0.830      | 0.143        | 0.045 (0.005)    | -                | -             |     5.64 | AccuracyTG, dobu, kabal, MiQ, zesta   |
|           46 |     2475 | 2024-03-10 | E9 esports                   | W   | 0.822      | 0.143        | 0.021 (0.002)    | -                | -             |     4.28 | AccuracyTG, dobu, kabal, MiQ, zesta   |
|           45 |     2518 | 2024-03-09 | Myth Avenue Gaming           | W   | 0.817      | -            | -                | -                | -             |     3.65 | AccuracyTG, dobu, kabal, MiQ, zesta   |
|           44 |     2547 | 2024-03-08 | E9 esports                   | W   | 0.809      | 0.143        | 0.021 (0.002)    | -                | -             |     3.83 | AccuracyTG, dobu, kabal, MiQ, zesta   |
|           43 |     2590 | 2024-03-06 | Steel Helmet                 | W   | 0.802      | 0.143        | 0.025 (0.003)    | -                | -             |     2.79 | AccuracyTG, dobu, kabal, MiQ, zesta   |
|           42 |     3009 | 2024-02-27 | FlyQuest                     | L   | 0.748      | -            | -                | -                | -             |    -3.49 | AccuracyTG, dobu, kabal, MiQ, Zesta   |
|           41 |     3050 | 2024-02-26 | TYLOO                        | W   | 0.742      | 0.143        | 0.131 (0.014)    | -                | true (0.742)  |    11.39 | AccuracyTG, dobu, kabal, MiQ, Zesta   |
|           40 |     3053 | 2024-02-26 | Myth Avenue Gaming           | W   | 0.741      | -            | -                | -                | true (0.741)  |     0.54 | AccuracyTG, dobu, kabal, MiQ, Zesta   |
|           39 |     3086 | 2024-02-25 | FlyQuest                     | L   | 0.734      | -            | -                | -                | -             |    -3.27 | AccuracyTG, dobu, kabal, MiQ, Zesta   |
|           38 |     3313 | 2024-02-21 | Gods Reign                   | W   | 0.704      | 0.417        | 0.174 (0.051)    | 0.479 (0.141)    | -             |     5.12 | AccuracyTG, dobu, kabal, MiQ, Zesta   |
|           37 |     3321 | 2024-02-21 | Gods Reign                   | L   | 0.704      | -            | -                | -                | -             |   -17.46 | AccuracyTG, dobu, kabal, MiQ, Zesta   |
|           36 |     3360 | 2024-02-20 | GR Gaming                    | W   | 0.697      | 0.417        | -                | 0.495 (0.144)    | -             |     4.28 | AccuracyTG, dobu, kabal, MiQ, Zesta   |
|           35 |     3367 | 2024-02-20 | GR Gaming                    | W   | 0.697      | 0.417        | -                | 0.495 (0.144)    | -             |     4.45 | AccuracyTG, dobu, kabal, MiQ, Zesta   |
|           34 |     3543 | 2024-02-16 | MIRAI Gaming                 | W   | 0.671      | 0.417        | -                | 0.246 (0.069)    | -             |     2.01 | AccuracyTG, dobu, kabal, MiQ, Zesta   |
|           33 |     3545 | 2024-02-16 | MIRAI Gaming                 | W   | 0.671      | 0.417        | -                | 0.246 (0.069)    | -             |     2.05 | AccuracyTG, dobu, kabal, MiQ, Zesta   |
|           32 |     4057 | 2024-02-01 | GR Gaming                    | L   | 0.576      | -            | -                | -                | -             |   -14.51 | AccuracyTG, dobu, kabal, MiQ, Zesta   |
|           31 |     4125 | 2024-01-31 | Team NKT                     | W   | 0.563      | -            | -                | -                | -             |     3.29 | AccuracyTG, dobu, kabal, MiQ, Zesta   |
|           30 |     4128 | 2024-01-31 | Rare Atom                    | W   | 0.563      | -            | -                | -                | -             |     2.96 | AccuracyTG, dobu, kabal, MiQ, Zesta   |
|           29 |     4440 | 2024-01-23 | The Huns Esports             | L   | 0.510      | -            | -                | -                | -             |   -11.65 | AccuracyTG, dobu, kabal, MiQ, zesta   |
|           28 |     4482 | 2024-01-22 | Rare Atom                    | W   | 0.504      | -            | -                | -                | -             |     2.31 | AccuracyTG, dobu, kabal, MiQ, zesta   |
|           27 |     4509 | 2024-01-21 | The Huns Esports             | W   | 0.497      | -            | -                | -                | -             |     4.25 | AccuracyTG, dobu, kabal, MiQ, Zesta   |
|           26 |     4517 | 2024-01-20 | The MongolZ                  | L   | 0.495      | -            | -                | -                | -             |    -0.67 | AccuracyTG, dobu, kabal, MiQ, Zesta   |
|           25 |     4614 | 2024-01-19 | GR Gaming                    | W   | 0.483      | -            | -                | -                | -             |     2.84 | AccuracyTG, dobu, kabal, MiQ, Zesta   |
|           24 |     4621 | 2024-01-19 | Fort Arena                   | W   | 0.483      | -            | -                | -                | -             |     0.58 | AccuracyTG, dobu, kabal, MiQ, Zesta   |
|           23 |     5183 | 2024-01-06 | Wings Up Gaming              | L   | 0.396      | -            | -                | -                | -             |   -10.95 | AccuracyTG, dobu, kabal, MiQ, zesta   |
|           22 |     5189 | 2024-01-05 | NewHappy                     | W   | 0.390      | -            | -                | -                | -             |     1.85 | AccuracyTG, dobu, kabal, MiQ, zesta   |
|           21 |     5200 | 2024-01-04 | TYLOO                        | L   | 0.383      | -            | -                | -                | -             |    -6.88 | AccuracyTG, dobu, kabal, MiQ, zesta   |
|           20 |     5220 | 2024-01-03 | Wings Up Gaming              | W   | 0.376      | -            | -                | -                | -             |     1.31 | AccuracyTG, dobu, kabal, MiQ, zesta   |
|           19 |     5241 | 2024-01-02 | Team NKT                     | W   | 0.370      | -            | -                | -                | -             |     1.75 | AccuracyTG, dobu, kabal, MiQ, zesta   |
|           18 |     5402 | 2023-12-17 | LETUSWIN69                   | W   | 0.262      | -            | -                | -                | -             |     0.52 | AccuracyTG, dobu, kabal, MiQ, zesta   |
|           17 |     5497 | 2023-12-16 | MIRAI Gaming                 | W   | 0.256      | -            | -                | -                | -             |     0.84 | AccuracyTG, dobu, kabal, MiQ, zesta   |
|           16 |     5945 | 2023-12-06 | -72C                         | L   | 0.190      | -            | -                | -                | -             |    -5.08 | AccuracyTG, dobu, kabal, MiQ, zesta   |
|           15 |     6003 | 2023-12-05 | GR Gaming                    | L   | 0.184      | -            | -                | -                | -             |    -4.79 | AccuracyTG, dobu, kabal, MiQ, zesta   |
|           14 |     6136 | 2023-12-02 | The Huns Esports             | W   | 0.163      | -            | -                | -                | true (0.163)  |     1.38 | AccuracyTG, dobu, kabal, MiQ, zesta   |
|           13 |     6175 | 2023-11-30 | The Huns Esports             | W   | 0.155      | -            | -                | -                | true (0.155)  |     1.32 | AccuracyTG, dobu, kabal, MiQ, zesta   |
|           12 |     6231 | 2023-11-29 | Old School (Mongolian team)  | W   | 0.148      | -            | -                | -                | true (0.148)  |     0.17 | AccuracyTG, dobu, kabal, MiQ, zesta   |
|           11 |     6336 | 2023-11-28 | Aravt                        | W   | 0.136      | -            | -                | -                | -             |     0.19 | AccuracyTG, dobu, kabal, MiQ, zesta   |
|           10 |     6343 | 2023-11-27 | Chinggis Warriors            | W   | 0.135      | -            | -                | -                | -             |     0.08 | AccuracyTG, dobu, kabal, MiQ, zesta   |
|            9 |     6404 | 2023-11-26 | The MongolZ                  | L   | 0.123      | -            | -                | -                | -             |    -0.16 | AccuracyTG, dobu, kabal, MiQ, zesta   |
|            8 |     6453 | 2023-11-24 | The MongolZ                  | W   | 0.116      | 0.143        | 0.292 (0.005)    | -                | -             |     3.50 | AccuracyTG, dobu, kabal, MiQ, zesta   |
|            7 |     6457 | 2023-11-24 | Aravt                        | W   | 0.115      | -            | -                | -                | -             |     0.16 | AccuracyTG, dobu, kabal, MiQ, zesta   |
|            6 |     6606 | 2023-11-21 | Octagonal Disposition Gaming | W   | 0.090      | -            | -                | -                | -             |     0.18 | AccuracyTG, dobu, kabal, MiQ, zesta   |
|            5 |     6786 | 2023-11-17 | NewHappy                     | L   | 0.064      | -            | -                | -                | -             |    -1.77 | AccuracyTG, dobu, kabal, MiQ, zesta   |
|            4 |     6795 | 2023-11-16 | TYLOO                        | L   | 0.062      | -            | -                | -                | -             |    -1.11 | AccuracyTG, dobu, kabal, MiQ, zesta   |
|            3 |     6843 | 2023-11-16 | Aravt                        | W   | 0.057      | -            | -                | -                | -             |     0.08 | AccuracyTG, dobu, kabal, MiQ, zesta   |
|            2 |     6848 | 2023-11-16 | Hyper5                       | W   | 0.056      | -            | -                | -                | -             |     0.17 | AccuracyTG, dobu, kabal, MiQ, zesta   |
|            1 |     6895 | 2023-11-15 | The QUBE Esports             | W   | 0.050      | -            | -                | -                | -             |     0.03 | AccuracyTG, dobu, kabal, MiQ, zesta   |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($17,817.36)
- Divide that value by the 5th highest value among all rosters ($158,437.64)
- The final value (0.11) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-04-21 |      1.000 | $4,143.76      | $4,143.76       |
| 2024-04-14 |      1.000 | $2,318.84      | $2,318.84       |
| 2024-03-11 |      0.830 | $11,132.91     | $9,239.80       |
| 2024-01-06 |      0.397 | $2,815.91      | $1,117.17       |
| 2023-12-17 |      0.262 | $750.00        | $196.84         |
| 2023-12-10 |      0.217 | $1,300.00      | $281.97         |
| 2023-12-02 |      0.163 | $3,186.51      | $518.99         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
