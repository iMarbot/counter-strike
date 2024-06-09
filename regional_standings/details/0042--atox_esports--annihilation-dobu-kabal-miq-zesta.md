### Roster Details<br />
Team Name: ATOX Esports<br />
Roster: ANNIHILATION, dobu, kabal, MiQ, Zesta<br />
Region: [Asia]( ../standings_asia.md)<br />
<br />
Global Rank: [42](../standings_global.md)<br />
Regional Rank: [3]( ../standings_asia.md)<br />
Final Rank Value:  1097.1<br />
<br />
Final Rank Value (1097.1) = Starting Rank Value (1270.9) + Head To Head Adjustments (-173.8)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.430[<sup>1</sup>](#table2)
- Bounty Collected: 0.369[<sup>2</sup>](#table1)
- Opponent Network: 0.096[<sup>2</sup>](#table1)
- LAN Wins: 0.819[<sup>2</sup>](#table1)

The average of these factors is 0.428<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1270.9
- 400 + ( ( 0.428 - 0.000 ) / ( 0.787 - 0.000 ) ) * 1600 = 1270.9


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent           | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           76 |        0 | 2024-05-29 | BLEED Esports      | L   | 1.000      | -            | -                | -                | -         |   -12.72 | ANNIHILATION, dobu, kabal, MiQ, Zesta |
|           75 |      103 | 2024-05-28 | OG                 | W   | 1.000      | 0.500        | 0.277 (0.139)    | 0.257 (0.128)    | 1 (1.000) |    20.56 | ANNIHILATION, dobu, kabal, MiQ, Zesta |
|           74 |      515 | 2024-05-22 | TYLOO              | L   | 1.000      | -            | -                | -                | -         |   -20.30 | ANNIHILATION, dobu, kabal, MiQ, Zesta |
|           73 |      521 | 2024-05-22 | TYLOO              | W   | 1.000      | 0.417        | 0.035 (0.015)    | 0.433 (0.180)    | -         |    10.83 | ANNIHILATION, dobu, kabal, MiQ, Zesta |
|           72 |      623 | 2024-05-21 | -72C               | L   | 1.000      | -            | -                | -                | -         |   -26.02 | ANNIHILATION, dobu, kabal, MiQ, Zesta |
|           71 |      630 | 2024-05-21 | -72C               | L   | 1.000      | -            | -                | -                | -         |   -27.25 | ANNIHILATION, dobu, kabal, MiQ, Zesta |
|           70 |      943 | 2024-05-18 | The MongolZ        | L   | 1.000      | -            | -                | -                | -         |    -2.76 | ANNIHILATION, dobu, kabal, MiQ, Zesta |
|           69 |     1026 | 2024-05-17 | The Huns Esports   | W   | 1.000      | -            | -                | -                | 1 (1.000) |     4.54 | ANNIHILATION, dobu, kabal, MiQ, Zesta |
|           68 |     1208 | 2024-05-15 | Chinggis Warriors  | W   | 1.000      | -            | -                | -                | 1 (1.000) |     4.32 | ANNIHILATION, dobu, kabal, MiQ, Zesta |
|           67 |     1221 | 2024-05-14 | Eruption           | W   | 1.000      | -            | -                | -                | 1 (1.000) |     0.65 | ANNIHILATION, dobu, kabal, MiQ, Zesta |
|           66 |     2566 | 2024-04-21 | Rare Atom          | L   | 0.942      | -            | -                | -                | -         |   -24.37 | ANNIHILATION, dobu, kabal, MiQ, Zesta |
|           65 |     2583 | 2024-04-21 | Lynn Vision Gaming | W   | 0.941      | 0.143        | 0.063 (0.008)    | -                | -         |    10.18 | ANNIHILATION, dobu, kabal, MiQ, Zesta |
|           64 |     2665 | 2024-04-20 | Clutch Gaming      | W   | 0.936      | 0.417        | -                | 0.167 (0.065)    | -         |     2.75 | ANNIHILATION, dobu, kabal, MiQ, Zesta |
|           63 |     2680 | 2024-04-20 | Clutch Gaming      | W   | 0.936      | 0.417        | -                | 0.167 (0.065)    | -         |     2.82 | ANNIHILATION, dobu, kabal, MiQ, Zesta |
|           62 |     2774 | 2024-04-19 | Born In Far East   | W   | 0.929      | -            | -                | -                | -         |     2.00 | ANNIHILATION, dobu, kabal, MiQ, Zesta |
|           61 |     2779 | 2024-04-19 | Born In Far East   | W   | 0.929      | -            | -                | -                | -         |     2.04 | ANNIHILATION, dobu, kabal, MiQ, Zesta |
|           60 |     2837 | 2024-04-18 | Bigetron Fury      | W   | 0.922      | -            | -                | -                | -         |     0.90 | ANNIHILATION, dobu, kabal, MiQ, Zesta |
|           59 |     2840 | 2024-04-18 | Steel Helmet       | W   | 0.922      | 0.143        | 0.012 (0.002)    | -                | -         |     1.86 | ANNIHILATION, dobu, kabal, MiQ, Zesta |
|           58 |     2978 | 2024-04-16 | MIRAI Gaming       | L   | 0.909      | -            | -                | -                | -         |   -26.82 | ANNIHILATION, dobu, kabal, MiQ, Zesta |
|           57 |     3053 | 2024-04-14 | The MongolZ        | L   | 0.896      | -            | -                | -                | -         |    -3.12 | ANNIHILATION, dobu, kabal, MiQ, Zesta |
|           56 |     3063 | 2024-04-13 | IHC Esports        | W   | 0.894      | -            | -                | -                | 1 (0.894) |     4.84 | ANNIHILATION, dobu, kabal, MiQ, Zesta |
|           55 |     3263 | 2024-04-10 | The MongolZ        | L   | 0.869      | -            | -                | -                | -         |    -3.06 | ANNIHILATION, dobu, kabal, MiQ, Zesta |
|           54 |     3268 | 2024-04-10 | The MongolZ        | L   | 0.869      | -            | -                | -                | -         |    -3.15 | ANNIHILATION, dobu, kabal, MiQ, Zesta |
|           53 |     3336 | 2024-04-09 | NewHappy           | L   | 0.862      | -            | -                | -                | -         |   -24.95 | ANNIHILATION, dobu, kabal, MiQ, Zesta |
|           52 |     3341 | 2024-04-09 | NewHappy           | W   | 0.862      | 0.417        | 0.020 (0.007)    | 0.231 (0.083)    | -         |     2.02 | ANNIHILATION, dobu, kabal, MiQ, Zesta |
|           51 |     3390 | 2024-04-08 | The MongolZ        | L   | 0.855      | -            | -                | -                | -         |    -3.60 | ANNIHILATION, dobu, kabal, MiQ, Zesta |
|           50 |     3443 | 2024-04-06 | The Huns Esports   | W   | 0.847      | -            | -                | -                | 1 (0.847) |     3.23 | ANNIHILATION, dobu, kabal, MiQ, Zesta |
|           49 |     3535 | 2024-04-05 | DEWA United        | W   | 0.836      | 0.417        | -                | 0.176 (0.061)    | -         |     1.50 | ANNIHILATION, dobu, kabal, MiQ, Zesta |
|           48 |     3536 | 2024-04-05 | DEWA United        | W   | 0.836      | -            | -                | -                | -         |     1.52 | ANNIHILATION, dobu, kabal, MiQ, Zesta |
|           47 |     3541 | 2024-04-05 | IHC Esports        | W   | 0.835      | -            | -                | -                | 1 (0.835) |     3.86 | ANNIHILATION, dobu, kabal, MiQ, Zesta |
|           46 |     3699 | 2024-04-02 | The MongolZ        | L   | 0.816      | -            | -                | -                | -         |    -3.43 | ANNIHILATION, dobu, kabal, MiQ, zesta |
|           45 |     3706 | 2024-04-02 | Lynn Vision Gaming | L   | 0.815      | -            | -                | -                | -         |   -16.58 | ANNIHILATION, dobu, kabal, MiQ, zesta |
|           44 |     3917 | 2024-03-27 | The QUBE Esports   | W   | 0.776      | -            | -                | -                | -         |     1.11 | ANNIHILATION, dobu, kabal, MiQ, Zesta |
|           43 |     3921 | 2024-03-27 | The QUBE Esports   | W   | 0.776      | -            | -                | -                | -         |     1.13 | ANNIHILATION, dobu, kabal, MiQ, Zesta |
|           42 |     4549 | 2024-03-14 | LYG Gaming         | W   | 0.690      | 0.417        | -                | 0.275 (0.079)    | -         |     1.54 | ANNIHILATION, dobu, kabal, MiQ, Zesta |
|           41 |     4554 | 2024-03-14 | LYG Gaming         | L   | 0.689      | -            | -                | -                | -         |   -20.37 | ANNIHILATION, dobu, kabal, MiQ, Zesta |
|           40 |     4628 | 2024-03-13 | -72C               | W   | 0.682      | -            | -                | -                | -         |     1.60 | dobu, flyNN, kabal, MiQ, zesta        |
|           39 |     4633 | 2024-03-13 | ROUX from hell     | W   | 0.682      | -            | -                | -                | -         |     0.36 | dobu, flyNN, kabal, MiQ, zesta        |
|           38 |     4692 | 2024-03-12 | Magadan            | W   | 0.676      | -            | -                | -                | -         |     0.20 | dobu, flyNN, kabal, MiQ, zesta        |
|           37 |     4755 | 2024-03-11 | NewHappy           | W   | 0.669      | 0.143        | 0.020 (0.002)    | -                | -         |     1.86 | AccuracyTG, dobu, kabal, MiQ, zesta   |
|           36 |     4803 | 2024-03-10 | E9 esports         | W   | 0.661      | -            | -                | -                | -         |     1.35 | AccuracyTG, dobu, kabal, MiQ, zesta   |
|           35 |     4863 | 2024-03-09 | Myth Avenue Gaming | W   | 0.656      | -            | -                | -                | -         |     1.30 | AccuracyTG, dobu, kabal, MiQ, zesta   |
|           34 |     4898 | 2024-03-08 | E9 esports         | W   | 0.648      | -            | -                | -                | -         |     1.17 | AccuracyTG, dobu, kabal, MiQ, zesta   |
|           33 |     4964 | 2024-03-06 | Steel Helmet       | W   | 0.641      | -            | -                | -                | -         |     0.91 | AccuracyTG, dobu, kabal, MiQ, zesta   |
|           32 |     5018 | 2024-03-06 | ZEUSGG             | W   | 0.636      | -            | -                | -                | -         |     0.50 | AccuracyTG, dobu, kabal, MiQ, Zesta   |
|           31 |     5025 | 2024-03-06 | ZEUSGG             | W   | 0.636      | -            | -                | -                | -         |     0.50 | AccuracyTG, dobu, kabal, MiQ, Zesta   |
|           30 |     5495 | 2024-02-27 | FlyQuest           | L   | 0.587      | -            | -                | -                | -         |    -4.32 | AccuracyTG, dobu, kabal, MiQ, Zesta   |
|           29 |     5544 | 2024-02-26 | TYLOO              | W   | 0.581      | 0.143        | 0.017 (0.001)    | -                | 1 (0.581) |     1.93 | AccuracyTG, dobu, kabal, MiQ, Zesta   |
|           28 |     5547 | 2024-02-26 | Myth Avenue Gaming | W   | 0.580      | -            | -                | -                | 1 (0.580) |     0.18 | AccuracyTG, dobu, kabal, MiQ, Zesta   |
|           27 |     5589 | 2024-02-25 | FlyQuest           | L   | 0.573      | -            | -                | -                | -         |    -4.24 | AccuracyTG, dobu, kabal, MiQ, Zesta   |
|           26 |     5882 | 2024-02-21 | Gods Reign         | W   | 0.543      | 0.417        | 0.086 (0.019)    | 0.461 (0.104)    | -         |     1.94 | AccuracyTG, dobu, kabal, MiQ, Zesta   |
|           25 |     5893 | 2024-02-21 | Gods Reign         | L   | 0.543      | -            | -                | -                | -         |   -15.36 | AccuracyTG, dobu, kabal, MiQ, Zesta   |
|           24 |     5941 | 2024-02-20 | GR Gaming          | W   | 0.536      | 0.417        | 0.007 (0.001)    | 0.428 (0.096)    | -         |     1.28 | AccuracyTG, dobu, kabal, MiQ, Zesta   |
|           23 |     5949 | 2024-02-20 | GR Gaming          | W   | 0.536      | 0.417        | 0.007 (0.001)    | 0.428 (0.096)    | -         |     1.30 | AccuracyTG, dobu, kabal, MiQ, Zesta   |
|           22 |     6171 | 2024-02-16 | MIRAI Gaming       | W   | 0.510      | -            | -                | -                | -         |     0.65 | AccuracyTG, dobu, kabal, MiQ, Zesta   |
|           21 |     6174 | 2024-02-16 | MIRAI Gaming       | W   | 0.509      | -            | -                | -                | -         |     0.65 | AccuracyTG, dobu, kabal, MiQ, Zesta   |
|           20 |     6849 | 2024-02-01 | GR Gaming          | L   | 0.414      | -            | -                | -                | -         |   -12.13 | AccuracyTG, dobu, kabal, MiQ, Zesta   |
|           19 |     6949 | 2024-01-31 | Team NKT           | W   | 0.402      | -            | -                | -                | -         |     0.75 | AccuracyTG, dobu, kabal, MiQ, Zesta   |
|           18 |     6953 | 2024-01-31 | Rare Atom          | W   | 0.402      | -            | -                | -                | -         |     0.67 | AccuracyTG, dobu, kabal, MiQ, Zesta   |
|           17 |     7430 | 2024-01-23 | The Huns Esports   | L   | 0.349      | -            | -                | -                | -         |    -9.74 | AccuracyTG, dobu, kabal, MiQ, zesta   |
|           16 |     7484 | 2024-01-22 | Rare Atom          | W   | 0.343      | -            | -                | -                | -         |     0.50 | AccuracyTG, dobu, kabal, MiQ, zesta   |
|           15 |     7491 | 2024-01-22 | ZEUSGG             | W   | 0.343      | -            | -                | -                | -         |     0.22 | AccuracyTG, dobu, kabal, MiQ, zesta   |
|           14 |     7526 | 2024-01-21 | The Huns Esports   | W   | 0.336      | -            | -                | -                | -         |     1.17 | AccuracyTG, dobu, kabal, MiQ, Zesta   |
|           13 |     7535 | 2024-01-20 | The MongolZ        | L   | 0.334      | -            | -                | -                | -         |    -1.32 | AccuracyTG, dobu, kabal, MiQ, Zesta   |
|           12 |     7666 | 2024-01-19 | GR Gaming          | W   | 0.322      | -            | -                | -                | -         |     0.67 | AccuracyTG, dobu, kabal, MiQ, Zesta   |
|           11 |     7676 | 2024-01-19 | Fort Arena         | W   | 0.322      | -            | -                | -                | -         |     0.14 | AccuracyTG, dobu, kabal, MiQ, Zesta   |
|           10 |     8472 | 2024-01-06 | Wings Up Gaming    | L   | 0.235      | -            | -                | -                | -         |    -7.12 | AccuracyTG, dobu, kabal, MiQ, zesta   |
|            9 |     8479 | 2024-01-05 | NewHappy           | W   | 0.229      | -            | -                | -                | -         |     0.27 | AccuracyTG, dobu, kabal, MiQ, zesta   |
|            8 |     8494 | 2024-01-04 | TYLOO              | L   | 0.222      | -            | -                | -                | -         |    -6.52 | AccuracyTG, dobu, kabal, MiQ, zesta   |
|            7 |     8524 | 2024-01-03 | Wings Up Gaming    | W   | 0.215      | -            | -                | -                | -         |     0.24 | AccuracyTG, dobu, kabal, MiQ, zesta   |
|            6 |     8550 | 2024-01-02 | Team NKT           | W   | 0.209      | -            | -                | -                | -         |     0.30 | AccuracyTG, dobu, kabal, MiQ, zesta   |
|            5 |     8774 | 2023-12-17 | DEWA United        | W   | 0.101      | -            | -                | -                | -         |     0.08 | AccuracyTG, dobu, kabal, MiQ, zesta   |
|            4 |     8902 | 2023-12-16 | MIRAI Gaming       | W   | 0.095      | -            | -                | -                | -         |     0.13 | AccuracyTG, dobu, kabal, MiQ, zesta   |
|            3 |     9517 | 2023-12-06 | -72C               | L   | 0.029      | -            | -                | -                | -         |    -0.87 | AccuracyTG, dobu, kabal, MiQ, zesta   |
|            2 |     9596 | 2023-12-05 | GR Gaming          | L   | 0.022      | -            | -                | -                | -         |    -0.67 | AccuracyTG, dobu, kabal, MiQ, zesta   |
|            1 |     9792 | 2023-12-02 | The Huns Esports   | W   | 0.002      | -            | -                | -                | 1 (0.002) |     0.01 | AccuracyTG, dobu, kabal, MiQ, zesta   |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($14,245.89)
- Divide that value by the 5th highest value among all rosters ($300,806.11)
- The final value (0.05) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-04-21 |      0.942 | $4,143.76      | $3,904.34       |
| 2024-04-14 |      0.896 | $2,318.84      | $2,076.87       |
| 2024-03-11 |      0.669 | $11,132.91     | $7,446.68       |
| 2024-01-06 |      0.236 | $2,815.91      | $663.63         |
| 2023-12-17 |      0.101 | $750.00        | $76.04          |
| 2023-12-10 |      0.056 | $1,300.00      | $72.58          |
| 2023-12-02 |      0.002 | $3,186.51      | $5.75           |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
