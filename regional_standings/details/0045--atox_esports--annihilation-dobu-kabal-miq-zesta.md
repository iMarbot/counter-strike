### Roster Details<br />
Team Name: ATOX Esports<br />
Roster: ANNIHILATION, dobu, kabal, MiQ, Zesta<br />
Region: [Asia]( ../standings_asia.md)<br />
<br />
Global Rank: [45](../standings_global.md)<br />
Regional Rank: [3]( ../standings_asia.md)<br />
Final Rank Value:  1077.2<br />
<br />
Final Rank Value (1077.2) = Starting Rank Value (1227.5) + Head To Head Adjustments (-150.3)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.430[<sup>1</sup>](#table2)
- Bounty Collected: 0.369[<sup>2</sup>](#table1)
- Opponent Network: 0.096[<sup>2</sup>](#table1)
- LAN Wins: 0.730[<sup>2</sup>](#table1)

The average of these factors is 0.406<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1227.5
- 400 + ( ( 0.406 - 0.000 ) / ( 0.786 - 0.000 ) ) * 1600 = 1227.5


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
|           73 |        0 | 2024-05-29 | BLEED Esports      | L   | 1.000      | -            | -                | -                | -         |   -11.89 | ANNIHILATION, dobu, kabal, MiQ, Zesta |
|           72 |       96 | 2024-05-28 | OG                 | W   | 1.000      | 0.500        | 0.277 (0.139)    | 0.257 (0.128)    | 1 (1.000) |    21.46 | ANNIHILATION, dobu, kabal, MiQ, Zesta |
|           71 |      508 | 2024-05-22 | TYLOO              | L   | 1.000      | -            | -                | -                | -         |   -18.82 | ANNIHILATION, dobu, kabal, MiQ, Zesta |
|           70 |      514 | 2024-05-22 | TYLOO              | W   | 1.000      | 0.417        | 0.035 (0.015)    | 0.433 (0.180)    | 0 (0.000) |    12.41 | ANNIHILATION, dobu, kabal, MiQ, Zesta |
|           69 |      612 | 2024-05-21 | -72C               | L   | 1.000      | -            | -                | -                | -         |   -25.25 | ANNIHILATION, dobu, kabal, MiQ, Zesta |
|           68 |      619 | 2024-05-21 | -72C               | L   | 1.000      | -            | -                | -                | -         |   -26.59 | ANNIHILATION, dobu, kabal, MiQ, Zesta |
|           67 |      931 | 2024-05-18 | The MongolZ        | L   | 1.000      | -            | -                | -                | -         |    -2.42 | ANNIHILATION, dobu, kabal, MiQ, Zesta |
|           66 |     1014 | 2024-05-17 | The Huns Esports   | W   | 1.000      | -            | -                | -                | 1 (1.000) |     5.55 | ANNIHILATION, dobu, kabal, MiQ, Zesta |
|           65 |     1198 | 2024-05-15 | Chinggis Warriors  | W   | 1.000      | -            | -                | -                | 1 (1.000) |     4.78 | ANNIHILATION, dobu, kabal, MiQ, Zesta |
|           64 |     1211 | 2024-05-14 | Eruption           | W   | 1.000      | -            | -                | -                | 1 (1.000) |     0.75 | ANNIHILATION, dobu, kabal, MiQ, Zesta |
|           63 |     2513 | 2024-04-21 | Rare Atom          | L   | 0.942      | -            | -                | -                | -         |   -23.65 | ANNIHILATION, dobu, kabal, MiQ, Zesta |
|           62 |     2530 | 2024-04-21 | Lynn Vision Gaming | W   | 0.941      | 0.143        | 0.063 (0.008)    | -                | -         |    11.34 | ANNIHILATION, dobu, kabal, MiQ, Zesta |
|           61 |     2611 | 2024-04-20 | Clutch Gaming      | W   | 0.936      | 0.417        | -                | 0.167 (0.065)    | -         |     3.19 | ANNIHILATION, dobu, kabal, MiQ, Zesta |
|           60 |     2626 | 2024-04-20 | Clutch Gaming      | W   | 0.936      | 0.417        | -                | 0.167 (0.065)    | -         |     3.30 | ANNIHILATION, dobu, kabal, MiQ, Zesta |
|           59 |     2718 | 2024-04-19 | Born In Far East   | W   | 0.929      | -            | -                | -                | -         |     2.33 | ANNIHILATION, dobu, kabal, MiQ, Zesta |
|           58 |     2723 | 2024-04-19 | Born In Far East   | W   | 0.929      | -            | -                | -                | -         |     2.39 | ANNIHILATION, dobu, kabal, MiQ, Zesta |
|           57 |     2781 | 2024-04-18 | Bigetron Fury      | W   | 0.922      | -            | -                | -                | -         |     1.07 | ANNIHILATION, dobu, kabal, MiQ, Zesta |
|           56 |     2784 | 2024-04-18 | Steel Helmet       | W   | 0.922      | 0.143        | 0.012 (0.002)    | -                | -         |     2.20 | ANNIHILATION, dobu, kabal, MiQ, Zesta |
|           55 |     2917 | 2024-04-16 | MIRAI Gaming       | L   | 0.909      | -            | -                | -                | -         |   -26.45 | ANNIHILATION, dobu, kabal, MiQ, Zesta |
|           54 |     2988 | 2024-04-14 | The MongolZ        | L   | 0.896      | -            | -                | -                | -         |    -2.66 | ANNIHILATION, dobu, kabal, MiQ, Zesta |
|           53 |     2997 | 2024-04-13 | IHC Esports        | W   | 0.894      | -            | -                | -                | 1 (0.894) |     3.76 | ANNIHILATION, dobu, kabal, MiQ, Zesta |
|           52 |     3188 | 2024-04-10 | The MongolZ        | L   | 0.869      | -            | -                | -                | -         |    -2.61 | ANNIHILATION, dobu, kabal, MiQ, Zesta |
|           51 |     3193 | 2024-04-10 | The MongolZ        | L   | 0.869      | -            | -                | -                | -         |    -2.68 | ANNIHILATION, dobu, kabal, MiQ, Zesta |
|           50 |     3257 | 2024-04-09 | NewHappy           | L   | 0.862      | -            | -                | -                | -         |   -24.48 | ANNIHILATION, dobu, kabal, MiQ, Zesta |
|           49 |     3262 | 2024-04-09 | NewHappy           | W   | 0.862      | 0.417        | 0.020 (0.007)    | 0.231 (0.083)    | -         |     2.46 | ANNIHILATION, dobu, kabal, MiQ, Zesta |
|           48 |     3309 | 2024-04-08 | The MongolZ        | L   | 0.855      | -            | -                | -                | -         |    -3.04 | ANNIHILATION, dobu, kabal, MiQ, Zesta |
|           47 |     3360 | 2024-04-06 | The Huns Esports   | W   | 0.847      | -            | -                | -                | 1 (0.847) |     4.51 | ANNIHILATION, dobu, kabal, MiQ, Zesta |
|           46 |     3451 | 2024-04-05 | DEWA United        | W   | 0.836      | 0.417        | -                | 0.185 (0.064)    | -         |     1.83 | ANNIHILATION, dobu, kabal, MiQ, Zesta |
|           45 |     3452 | 2024-04-05 | DEWA United        | W   | 0.836      | -            | -                | -                | -         |     1.86 | ANNIHILATION, dobu, kabal, MiQ, Zesta |
|           44 |     3609 | 2024-04-02 | The MongolZ        | L   | 0.816      | -            | -                | -                | -         |    -2.91 | ANNIHILATION, dobu, kabal, MiQ, zesta |
|           43 |     3616 | 2024-04-02 | Lynn Vision Gaming | L   | 0.815      | -            | -                | -                | -         |   -15.49 | ANNIHILATION, dobu, kabal, MiQ, zesta |
|           42 |     3824 | 2024-03-27 | The QUBE Esports   | W   | 0.776      | -            | -                | -                | -         |     2.01 | ANNIHILATION, dobu, kabal, MiQ, Zesta |
|           41 |     3828 | 2024-03-27 | The QUBE Esports   | W   | 0.776      | -            | -                | -                | -         |     2.05 | ANNIHILATION, dobu, kabal, MiQ, Zesta |
|           40 |     4435 | 2024-03-14 | LYG Gaming         | W   | 0.690      | 0.417        | -                | 0.275 (0.079)    | -         |     1.87 | ANNIHILATION, dobu, kabal, MiQ, Zesta |
|           39 |     4440 | 2024-03-14 | LYG Gaming         | L   | 0.689      | -            | -                | -                | -         |   -20.08 | ANNIHILATION, dobu, kabal, MiQ, Zesta |
|           38 |     4512 | 2024-03-13 | -72C               | W   | 0.682      | -            | -                | -                | -         |     1.90 | dobu, flyNN, kabal, MiQ, zesta        |
|           37 |     4516 | 2024-03-13 | ROUX from hell     | W   | 0.682      | -            | -                | -                | -         |     0.44 | dobu, flyNN, kabal, MiQ, zesta        |
|           36 |     4571 | 2024-03-12 | Magadan            | W   | 0.676      | -            | -                | -                | -         |     0.25 | dobu, flyNN, kabal, MiQ, zesta        |
|           35 |     4632 | 2024-03-11 | NewHappy           | W   | 0.669      | 0.143        | 0.020 (0.002)    | -                | -         |     2.25 | AccuracyTG, dobu, kabal, MiQ, zesta   |
|           34 |     4678 | 2024-03-10 | E9 esports         | W   | 0.661      | -            | -                | -                | -         |     1.64 | AccuracyTG, dobu, kabal, MiQ, zesta   |
|           33 |     4737 | 2024-03-09 | Myth Avenue Gaming | W   | 0.656      | -            | -                | -                | -         |     1.59 | AccuracyTG, dobu, kabal, MiQ, zesta   |
|           32 |     4770 | 2024-03-08 | E9 esports         | W   | 0.648      | -            | -                | -                | -         |     1.43 | AccuracyTG, dobu, kabal, MiQ, zesta   |
|           31 |     4833 | 2024-03-06 | Steel Helmet       | W   | 0.641      | -            | -                | -                | -         |     1.11 | AccuracyTG, dobu, kabal, MiQ, zesta   |
|           30 |     5343 | 2024-02-27 | FlyQuest           | L   | 0.587      | -            | -                | -                | -         |    -3.71 | AccuracyTG, dobu, kabal, MiQ, Zesta   |
|           29 |     5387 | 2024-02-26 | TYLOO              | W   | 0.581      | 0.143        | 0.017 (0.001)    | -                | 1 (0.581) |     2.33 | AccuracyTG, dobu, kabal, MiQ, Zesta   |
|           28 |     5390 | 2024-02-26 | Myth Avenue Gaming | W   | 0.580      | -            | -                | -                | 1 (0.580) |     0.22 | AccuracyTG, dobu, kabal, MiQ, Zesta   |
|           27 |     5431 | 2024-02-25 | FlyQuest           | L   | 0.573      | -            | -                | -                | -         |    -3.62 | AccuracyTG, dobu, kabal, MiQ, Zesta   |
|           26 |     5719 | 2024-02-21 | Gods Reign         | W   | 0.543      | 0.417        | 0.086 (0.019)    | 0.461 (0.104)    | -         |     2.71 | AccuracyTG, dobu, kabal, MiQ, Zesta   |
|           25 |     5728 | 2024-02-21 | Gods Reign         | L   | 0.543      | -            | -                | -                | -         |   -14.63 | AccuracyTG, dobu, kabal, MiQ, Zesta   |
|           24 |     5772 | 2024-02-20 | GR Gaming          | W   | 0.536      | 0.417        | 0.007 (0.001)    | 0.428 (0.096)    | -         |     1.57 | AccuracyTG, dobu, kabal, MiQ, Zesta   |
|           23 |     5779 | 2024-02-20 | GR Gaming          | W   | 0.536      | 0.417        | 0.007 (0.001)    | 0.428 (0.096)    | -         |     1.59 | AccuracyTG, dobu, kabal, MiQ, Zesta   |
|           22 |     5996 | 2024-02-16 | MIRAI Gaming       | W   | 0.510      | -            | -                | -                | -         |     0.83 | AccuracyTG, dobu, kabal, MiQ, Zesta   |
|           21 |     5998 | 2024-02-16 | MIRAI Gaming       | W   | 0.509      | -            | -                | -                | -         |     0.84 | AccuracyTG, dobu, kabal, MiQ, Zesta   |
|           20 |     6644 | 2024-02-01 | GR Gaming          | L   | 0.414      | -            | -                | -                | -         |   -11.90 | AccuracyTG, dobu, kabal, MiQ, Zesta   |
|           19 |     6736 | 2024-01-31 | Team NKT           | W   | 0.402      | -            | -                | -                | -         |     0.92 | AccuracyTG, dobu, kabal, MiQ, Zesta   |
|           18 |     6740 | 2024-01-31 | Rare Atom          | W   | 0.402      | -            | -                | -                | -         |     0.84 | AccuracyTG, dobu, kabal, MiQ, Zesta   |
|           17 |     7190 | 2024-01-23 | The Huns Esports   | L   | 0.349      | -            | -                | -                | -         |    -9.47 | AccuracyTG, dobu, kabal, MiQ, zesta   |
|           16 |     7241 | 2024-01-22 | Rare Atom          | W   | 0.343      | -            | -                | -                | -         |     0.63 | AccuracyTG, dobu, kabal, MiQ, zesta   |
|           15 |     7248 | 2024-01-22 | ZEUSGG             | W   | 0.343      | -            | -                | -                | -         |     0.20 | AccuracyTG, dobu, kabal, MiQ, zesta   |
|           14 |     7283 | 2024-01-21 | The Huns Esports   | W   | 0.336      | -            | -                | -                | -         |     1.44 | AccuracyTG, dobu, kabal, MiQ, Zesta   |
|           13 |     7292 | 2024-01-20 | The MongolZ        | L   | 0.334      | -            | -                | -                | -         |    -1.06 | AccuracyTG, dobu, kabal, MiQ, Zesta   |
|           12 |     7419 | 2024-01-19 | GR Gaming          | W   | 0.322      | -            | -                | -                | -         |     0.83 | AccuracyTG, dobu, kabal, MiQ, Zesta   |
|           11 |     7429 | 2024-01-19 | Fort Arena         | W   | 0.322      | -            | -                | -                | -         |     0.17 | AccuracyTG, dobu, kabal, MiQ, Zesta   |
|           10 |     8217 | 2024-01-06 | Wings Up Gaming    | L   | 0.235      | -            | -                | -                | -         |    -7.04 | AccuracyTG, dobu, kabal, MiQ, zesta   |
|            9 |     8224 | 2024-01-05 | NewHappy           | W   | 0.229      | -            | -                | -                | -         |     0.34 | AccuracyTG, dobu, kabal, MiQ, zesta   |
|            8 |     8238 | 2024-01-04 | TYLOO              | L   | 0.222      | -            | -                | -                | -         |    -6.41 | AccuracyTG, dobu, kabal, MiQ, zesta   |
|            7 |     8268 | 2024-01-03 | Wings Up Gaming    | W   | 0.215      | -            | -                | -                | -         |     0.30 | AccuracyTG, dobu, kabal, MiQ, zesta   |
|            6 |     8294 | 2024-01-02 | Team NKT           | W   | 0.209      | -            | -                | -                | -         |     0.38 | AccuracyTG, dobu, kabal, MiQ, zesta   |
|            5 |     8514 | 2023-12-17 | DEWA United        | W   | 0.101      | -            | -                | -                | -         |     0.10 | AccuracyTG, dobu, kabal, MiQ, zesta   |
|            4 |     8641 | 2023-12-16 | MIRAI Gaming       | W   | 0.095      | -            | -                | -                | -         |     0.16 | AccuracyTG, dobu, kabal, MiQ, zesta   |
|            3 |     9236 | 2023-12-06 | -72C               | L   | 0.029      | -            | -                | -                | -         |    -0.86 | AccuracyTG, dobu, kabal, MiQ, zesta   |
|            2 |     9314 | 2023-12-05 | GR Gaming          | L   | 0.022      | -            | -                | -                | -         |    -0.65 | AccuracyTG, dobu, kabal, MiQ, zesta   |
|            1 |     9510 | 2023-12-02 | The Huns Esports   | W   | 0.002      | -            | -                | -                | 1 (0.002) |     0.01 | AccuracyTG, dobu, kabal, MiQ, zesta   |

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
