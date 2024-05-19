### Roster Details<br />
Team Name: Galorys<br />
Roster: detr0ittJ, happ, hoax, koala, ninjaZ<br />
Region: [Americas]( ../standings_americas.md)<br />
<br />
Global Rank: [75](../standings_global.md)<br />
Regional Rank: [13]( ../standings_americas.md)<br />
Final Rank Value:  902.4<br />
<br />
Final Rank Value (902.4) = Starting Rank Value (872.0) + Head To Head Adjustments (30.4)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.432[<sup>1</sup>](#table2)
- Bounty Collected: 0.374[<sup>2</sup>](#table1)
- Opponent Network: 0.146[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.238<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 872.0
- 400 + ( ( 0.238 - 0.000 ) / ( 0.806 - 0.000 ) ) * 1600 = 872.0


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent                       | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins      | H2H Adj. | Roster                                  |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           65 |      170 | 2024-05-01 | W7m esports                    | W   | 1.000      | -            | -                | -                | false (0.000) |     5.32 | detr0ittJ, happ, hoax, koala, ninjaZ    |
|           64 |      629 | 2024-04-21 | MIBR Academy                   | W   | 1.000      | -            | -                | -                | false (0.000) |     8.88 | detr0ittJ, happ, hoax, koala, ninjaZ    |
|           63 |      676 | 2024-04-20 | LaChampionsLiga                | W   | 1.000      | -            | -                | -                | false (0.000) |     3.66 | detr0ittJ, happ, hoax, koala, ninjaZ    |
|           62 |      681 | 2024-04-20 | TEAM ORUGA                     | W   | 1.000      | -            | -                | -                | false (0.000) |     5.22 | detr0ittJ, happ, hoax, koala, ninjaZ    |
|           61 |      993 | 2024-04-16 | Case Esports                   | L   | 1.000      | -            | -                | -                | -             |   -19.14 | detr0ittJ, happ, hoax, koala, ninjaZ    |
|           60 |     1062 | 2024-04-14 | MIBR                           | L   | 1.000      | -            | -                | -                | -             |    -0.80 | detr0ittJ, happ, hoax, koala, ninjaZ    |
|           59 |     1116 | 2024-04-13 | Fluxo                          | W   | 1.000      | 0.435        | 0.153 (0.066)    | 0.484 (0.210)    | false (0.000) |    23.00 | detr0ittJ, happ, hoax, koala, ninjaZ    |
|           58 |     1134 | 2024-04-12 | Sharks Esports                 | W   | 1.000      | 0.435        | 0.063 (0.027)    | 0.343 (0.149)    | false (0.000) |    18.84 | detr0ittJ, happ, hoax, koala, ninjaZ    |
|           57 |     1164 | 2024-04-11 | Vikings KR                     | L   | 1.000      | -            | -                | -                | -             |   -21.41 | detr0ittJ, happ, hoax, koala, ninjaZ    |
|           56 |     1173 | 2024-04-11 | BESTIA                         | W   | 1.000      | 0.435        | 0.026 (0.011)    | 0.423 (0.184)    | false (0.000) |    13.74 | detr0ittJ, happ, hoax, koala, ninjaZ    |
|           55 |     1202 | 2024-04-10 | MIBR                           | L   | 1.000      | -            | -                | -                | -             |    -0.67 | detr0ittJ, happ, hoax, koala, ninjaZ    |
|           54 |     1206 | 2024-04-10 | MIBR                           | L   | 1.000      | -            | -                | -                | -             |    -0.67 | detr0ittJ, happ, hoax, koala, ninjaZ    |
|           53 |     1271 | 2024-04-09 | BESTIA                         | W   | 1.000      | 0.450        | 0.026 (0.012)    | 0.423 (0.191)    | false (0.000) |    14.94 | detr0ittJ, happ, hoax, koala, ninjaZ    |
|           52 |     1273 | 2024-04-09 | BESTIA                         | L   | 1.000      | -            | -                | -                | -             |   -16.64 | detr0ittJ, happ, hoax, koala, ninjaZ    |
|           51 |     1321 | 2024-04-08 | FURIA Academy                  | W   | 1.000      | -            | -                | -                | false (0.000) |     6.95 | detr0ittJ, happ, hoax, koala, ninjaZ    |
|           50 |     1474 | 2024-04-04 | Intense Game                   | W   | 0.992      | -            | -                | -                | false (0.000) |    11.29 | detr0ittJ, happ, hoax, koala, ninjaZ    |
|           49 |     1690 | 2024-03-28 | Corinthians Esports            | W   | 0.945      | -            | -                | -                | -             |     8.89 | detr0ittJ, happ, hoax, koala, ninjaZ    |
|           48 |     1719 | 2024-03-27 | Fluxo                          | W   | 0.940      | 0.450        | 0.153 (0.065)    | 0.484 (0.205)    | -             |    21.96 | detr0ittJ, happ, hoax, koala, ninjaZ    |
|           47 |     1725 | 2024-03-27 | Fluxo                          | L   | 0.940      | -            | -                | -                | -             |    -7.27 | detr0ittJ, happ, hoax, koala, ninjaZ    |
|           46 |     1786 | 2024-03-26 | 2Game Esports                  | W   | 0.934      | 0.450        | -                | 0.188 (0.079)    | -             |     7.01 | detr0ittJ, happ, hoax, koala, ninjaZ    |
|           45 |     1790 | 2024-03-26 | 2Game Esports                  | W   | 0.933      | -            | -                | -                | -             |     7.45 | detr0ittJ, happ, hoax, koala, ninjaZ    |
|           44 |     1796 | 2024-03-26 | MIBR Academy                   | W   | 0.932      | -            | -                | -                | -             |    11.65 | detr0ittJ, happ, hoax, koala, ninjaZ    |
|           43 |     1963 | 2024-03-21 | Sensei Team                    | L   | 0.899      | -            | -                | -                | -             |   -17.46 | detr0ittJ, happ, hoax, koala, ninjaZ    |
|           42 |     2244 | 2024-03-14 | W7m esports                    | W   | 0.854      | -            | -                | -                | -             |     6.75 | detr0ittJ, happ, hoax, koala, ninjaZ    |
|           41 |     2246 | 2024-03-14 | W7m esports                    | W   | 0.853      | -            | -                | -                | -             |     7.15 | detr0ittJ, happ, hoax, koala, ninjaZ    |
|           40 |     2314 | 2024-03-13 | RED Canids                     | L   | 0.845      | -            | -                | -                | -             |    -7.80 | detr0ittJ, happ, hoax, koala, ninjaZ    |
|           39 |     2360 | 2024-03-12 | Hype E-Sports (Brazilian team) | W   | 0.840      | -            | -                | -                | -             |     4.16 | detr0ittJ, happ, hoax, koala, ninjaZ    |
|           38 |     2444 | 2024-03-10 | MIBR                           | L   | 0.826      | -            | -                | -                | -             |    -0.35 | detr0ittJ, happ, hoax, koala, ninjaZ    |
|           37 |     2535 | 2024-03-08 | ODDIK                          | W   | 0.811      | 0.435        | 0.015 (0.005)    | 0.402 (0.142)    | -             |    17.01 | detr0ittJ, happ, hoax, koala, ninjaZ    |
|           36 |     3118 | 2024-02-24 | Sharks Esports                 | L   | 0.727      | -            | -                | -                | -             |    -7.66 | detr0ittJ, happ, hoax, koala, ninjaZ    |
|           35 |     3125 | 2024-02-24 | Sharks Esports                 | L   | 0.727      | -            | -                | -                | -             |    -8.12 | detr0ittJ, happ, hoax, koala, ninjaZ    |
|           34 |     3195 | 2024-02-23 | Corinthians Esports            | L   | 0.720      | -            | -                | -                | -             |   -15.52 | detr0ittJ, happ, hoax, koala, ninjaZ    |
|           33 |     3200 | 2024-02-23 | Corinthians Esports            | W   | 0.720      | 0.450        | 0.005 (0.002)    | 0.346 (0.112)    | -             |     7.10 | detr0ittJ, happ, hoax, koala, ninjaZ    |
|           32 |     3233 | 2024-02-22 | MIBR Academy                   | W   | 0.713      | -            | -                | -                | -             |     9.61 | detr0ittJ, happ, hoax, koala, ninjaZ    |
|           31 |     3281 | 2024-02-21 | AdalYamigos                    | L   | 0.707      | -            | -                | -                | -             |   -11.53 | detr0ittJ, happ, hoax, koala, ninjaZ    |
|           30 |     3284 | 2024-02-21 | AdalYamigos                    | L   | 0.707      | -            | -                | -                | -             |   -12.27 | detr0ittJ, happ, hoax, koala, ninjaZ    |
|           29 |     3305 | 2024-02-21 | Sharks Esports                 | L   | 0.705      | -            | -                | -                | -             |    -9.20 | detr0ittJ, happ, hoax, koala, ninjaZ    |
|           28 |     3390 | 2024-02-19 | Flamengo Esports               | L   | 0.694      | -            | -                | -                | -             |   -18.53 | detr0ittJ, happ, hoax, koala, ninjaZ    |
|           27 |     3433 | 2024-02-18 | Sharks Esports                 | L   | 0.687      | -            | -                | -                | -             |   -10.26 | detr0ittJ, happ, hoax, koala, ninjaZ    |
|           26 |     3438 | 2024-02-18 | Case Esports                   | W   | 0.686      | 0.303        | 0.027 (0.006)    | 0.401 (0.083)    | -             |    10.55 | detr0ittJ, happ, hoax, koala, ninjaZ    |
|           25 |     3482 | 2024-02-17 | Sharks Esports                 | W   | 0.679      | 0.303        | 0.063 (0.013)    | -                | -             |    11.82 | detr0ittJ, happ, hoax, koala, ninjaZ    |
|           24 |     3490 | 2024-02-17 | Corinthians Esports            | W   | 0.678      | 0.435        | -                | 0.346 (0.102)    | -             |     6.40 | detr0ittJ, happ, hoax, koala, ninjaZ    |
|           23 |     3519 | 2024-02-16 | Flamengo Esports               | W   | 0.673      | -            | -                | -                | -             |     3.38 | detr0ittJ, happ, hoax, koala, ninjaZ    |
|           22 |     3523 | 2024-02-16 | Imperial Esports               | L   | 0.672      | -            | -                | -                | -             |    -0.38 | detr0ittJ, happ, hoax, koala, ninjaZ    |
|           21 |     3528 | 2024-02-16 | Imperial Esports               | L   | 0.672      | -            | -                | -                | -             |    -0.38 | detr0ittJ, happ, hoax, koala, ninjaZ    |
|           20 |     3575 | 2024-02-15 | 9z Academy                     | W   | 0.665      | -            | -                | -                | -             |     5.76 | detr0ittJ, happ, hoax, koala, ninjaZ    |
|           19 |     3626 | 2024-02-14 | Sharks Esports                 | L   | 0.658      | -            | -                | -                | -             |    -8.14 | detr0ittJ, happ, hoax, koala, ninjaZ    |
|           18 |     3671 | 2024-02-13 | Case Esports                   | L   | 0.652      | -            | -                | -                | -             |   -10.45 | detr0ittJ, happ, hoax, koala, ninjaZ    |
|           17 |     4195 | 2024-01-29 | Formiguinhas                   | W   | 0.552      | -            | -                | -                | -             |     1.30 | detr0ittJ, happ, hoax, koala, ninjaZ    |
|           16 |     4306 | 2024-01-26 | ODDIK                          | L   | 0.532      | -            | -                | -                | -             |    -6.80 | detr0ittJ, happ, hoax, koala, ninjaZ    |
|           15 |     4346 | 2024-01-25 | Sharks Esports                 | W   | 0.527      | 0.143        | 0.063 (0.005)    | -                | -             |     9.66 | detr0ittJ, happ, hoax, koala, ninjaZ    |
|           14 |     4353 | 2024-01-25 | 2024                           | W   | 0.525      | -            | -                | -                | -             |     1.27 | detr0ittJ, happ, hoax, koala, ninjaZ    |
|           13 |     4450 | 2024-01-22 | 9z Team                        | L   | 0.507      | -            | -                | -                | -             |    -5.71 | detr0ittJ, happ, hoax, koala, ninjaZ    |
|           12 |     4527 | 2024-01-20 | Flamengo Esports               | L   | 0.493      | -            | -                | -                | -             |   -12.98 | detr0ittJ, happ, hoax, koala, ninjaZ    |
|           11 |     4584 | 2024-01-19 | Sharks Esports                 | L   | 0.487      | -            | -                | -                | -             |    -7.02 | detr0ittJ, happ, hoax, koala, ninjaZ    |
|           10 |     4593 | 2024-01-19 | Imperial Esports               | L   | 0.486      | -            | -                | -                | -             |    -0.28 | detr0ittJ, happ, hoax, koala, ninjaZ    |
|            9 |     4826 | 2024-01-15 | Legacy                         | L   | 0.460      | -            | -                | -                | -             |    -3.24 | detr0ittJ, happ, hoax, koala, ninjaZ    |
|            8 |     4879 | 2024-01-13 | Sharks Esports                 | L   | 0.447      | -            | -                | -                | -             |    -6.86 | detr0ittJ, happ, hoax, koala, ninjaZ    |
|            7 |     4980 | 2024-01-11 | Case Esports                   | W   | 0.433      | -            | -                | -                | -             |     4.25 | detr0ittJ, happ, hoax, koala, ninjaZ    |
|            6 |     4991 | 2024-01-11 | Vex Dragons                    | W   | 0.432      | -            | -                | -                | -             |     0.92 | duzzy, marcin, pac, spider, Tineu       |
|            5 |     5029 | 2024-01-10 | Rocket.GG                      | W   | 0.427      | -            | -                | -                | -             |     2.72 | arthur, gbr1, MrD, patu, Tatuujey       |
|            4 |     6694 | 2023-11-18 | Team Solid                     | L   | 0.073      | -            | -                | -                | -             |    -1.09 | detr0ittJ, koala, ninjaZ, voltera, xns  |
|            3 |     7029 | 2023-11-11 | United E-sports                | W   | 0.027      | -            | -                | -                | -             |     0.17 | ALENNNCARrx, Buddy, Fvn, Kadzz, neskk   |
|            2 |     7039 | 2023-11-11 | TIMACETA                       | W   | 0.027      | -            | -                | -                | -             |     0.19 | detr0ittJ, koala, ninjaZ, voltera, xns  |
|            1 |     7041 | 2023-11-11 | NewProject                     | W   | 0.027      | -            | -                | -                | -             |     0.09 | B_sakamoto, emut1, Patoz1k, thurp, Tron |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($7,674.24)
- Divide that value by the 5th highest value among all rosters ($158,437.64)
- The final value (0.05) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-04-15 |      1.000 | $5,000.00      | $5,000.00       |
| 2024-04-11 |      1.000 | $591.98        | $591.98         |
| 2024-02-22 |      0.713 | $1,418.01      | $1,010.66       |
| 2024-02-21 |      0.705 | $1,500.00      | $1,057.01       |
| 2023-11-11 |      0.027 | $535.73        | $14.58          |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
