### Roster Details<br />
Team Name: Fluxo<br />
Roster: chay, Lucaozy, PKL, v$m, zevy<br />
Region: [Americas]( ../standings_americas.md)<br />
<br />
Global Rank: [45](../standings_global.md)<br />
Regional Rank: [8]( ../standings_americas.md)<br />
Final Rank Value:  1066.1<br />
<br />
Final Rank Value (1066.1) = Starting Rank Value (1034.7) + Head To Head Adjustments (31.4)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.550[<sup>1</sup>](#table2)
- Bounty Collected: 0.527[<sup>2</sup>](#table1)
- Opponent Network: 0.202[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.320<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1034.7
- 400 + ( ( 0.320 - 0.000 ) / ( 0.806 - 0.000 ) ) * 1600 = 1034.7


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent                       | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                        |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           60 |      864 | 2024-04-18 | Imperial Esports               | L   | 1.000      | -            | -                | -                | -         |    -2.97 | chay, Lucaozy, PKL, v$m, zevy |
|           59 |      915 | 2024-04-17 | ODDIK                          | W   | 1.000      | -            | -                | -                | 0 (0.000) |     8.21 | chay, Lucaozy, PKL, v$m, zevy |
|           58 |      919 | 2024-04-17 | Team Solid                     | W   | 1.000      | -            | -                | -                | 0 (0.000) |     6.19 | chay, Lucaozy, PKL, v$m, zevy |
|           57 |      991 | 2024-04-16 | Hype E-Sports (Brazilian team) | W   | 1.000      | -            | -                | -                | 0 (0.000) |     1.47 | chay, Lucaozy, PKL, v$m, zevy |
|           56 |     1116 | 2024-04-13 | Galorys                        | L   | 1.000      | -            | -                | -                | -         |   -23.00 | chay, Lucaozy, PKL, v$m, zevy |
|           55 |     1204 | 2024-04-10 | Imperial Esports               | W   | 1.000      | 0.450        | 0.674 (0.303)    | 0.549 (0.247)    | 0 (0.000) |    28.91 | chay, Lucaozy, PKL, v$m, zevy |
|           54 |     1205 | 2024-04-10 | Imperial Esports               | L   | 1.000      | -            | -                | -                | -         |    -2.28 | chay, Lucaozy, PKL, v$m, zevy |
|           53 |     1272 | 2024-04-09 | ODDIK                          | W   | 1.000      | 0.450        | -                | 0.402 (0.181)    | 0 (0.000) |     8.53 | chay, Lucaozy, PKL, v$m, zevy |
|           52 |     1274 | 2024-04-09 | ODDIK                          | W   | 1.000      | 0.450        | -                | 0.402 (0.181)    | 0 (0.000) |     9.15 | chay, Lucaozy, PKL, v$m, zevy |
|           51 |     1318 | 2024-04-08 | ODDIK                          | W   | 1.000      | 0.435        | -                | 0.402 (0.175)    | 0 (0.000) |     9.86 | chay, Lucaozy, PKL, v$m, zevy |
|           50 |     1385 | 2024-04-06 | BESTIA                         | L   | 1.000      | -            | -                | -                | -         |   -23.59 | chay, Lucaozy, PKL, v$m, zevy |
|           49 |     1388 | 2024-04-06 | Team Solid                     | W   | 1.000      | 0.435        | 0.138 (0.060)    | -                | 0 (0.000) |     7.03 | chay, Lucaozy, PKL, v$m, zevy |
|           48 |     1433 | 2024-04-05 | MIBR                           | L   | 1.000      | -            | -                | -                | -         |    -1.89 | chay, Lucaozy, PKL, v$m, zevy |
|           47 |     1434 | 2024-04-05 | MIBR                           | W   | 1.000      | 0.450        | 0.654 (0.294)    | 0.616 (0.277)    | 0 (0.000) |    29.88 | chay, Lucaozy, PKL, v$m, zevy |
|           46 |     1466 | 2024-04-04 | Corinthians Esports            | W   | 0.993      | 0.450        | -                | 0.346 (0.155)    | 0 (0.000) |     3.98 | chay, Lucaozy, PKL, v$m, zevy |
|           45 |     1468 | 2024-04-04 | Corinthians Esports            | W   | 0.993      | 0.450        | -                | 0.346 (0.154)    | -         |     4.14 | chay, Lucaozy, PKL, v$m, zevy |
|           44 |     1491 | 2024-04-04 | RED Canids                     | L   | 0.991      | -            | -                | -                | -         |   -16.10 | chay, Lucaozy, PKL, v$m, zevy |
|           43 |     1514 | 2024-04-03 | MIBR                           | L   | 0.987      | -            | -                | -                | -         |    -1.45 | chay, Lucaozy, PKL, v$m, zevy |
|           42 |     1523 | 2024-04-03 | BESTIA                         | W   | 0.986      | -            | -                | -                | -         |     8.23 | chay, Lucaozy, PKL, v$m, zevy |
|           41 |     1566 | 2024-04-02 | MIBR                           | L   | 0.980      | -            | -                | -                | -         |    -1.40 | chay, Lucaozy, PKL, v$m, zevy |
|           40 |     1570 | 2024-04-02 | BESTIA                         | W   | 0.979      | -            | -                | -                | -         |     8.01 | chay, Lucaozy, PKL, v$m, zevy |
|           39 |     1719 | 2024-03-27 | Galorys                        | L   | 0.940      | -            | -                | -                | -         |   -21.96 | chay, Lucaozy, PKL, v$m, zevy |
|           38 |     1725 | 2024-03-27 | Galorys                        | W   | 0.940      | 0.450        | 0.048 (0.020)    | 0.598 (0.253)    | -         |     7.27 | chay, Lucaozy, PKL, v$m, zevy |
|           37 |     2299 | 2024-03-13 | Intense Game                   | W   | 0.846      | -            | -                | -                | -         |     5.29 | chay, Lucaozy, PKL, v$m, zevy |
|           36 |     2321 | 2024-03-13 | Team Solid                     | L   | 0.845      | -            | -                | -                | -         |   -20.57 | chay, Lucaozy, PKL, v$m, zevy |
|           35 |     2362 | 2024-03-12 | MIBR                           | W   | 0.839      | 0.435        | 0.654 (0.238)    | 0.616 (0.225)    | -         |    25.25 | chay, Lucaozy, PKL, v$m, zevy |
|           34 |     2428 | 2024-03-11 | Sharks Esports                 | W   | 0.831      | 0.435        | 0.063 (0.023)    | -                | -         |    10.18 | chay, Lucaozy, PKL, v$m, zevy |
|           33 |     2504 | 2024-03-09 | Corinthians Esports            | W   | 0.817      | -            | -                | -                | -         |     3.33 | chay, Lucaozy, PKL, v$m, zevy |
|           32 |     2557 | 2024-03-07 | Case Esports                   | L   | 0.806      | -            | -                | -                | -         |   -19.71 | chay, Lucaozy, PKL, v$m, zevy |
|           31 |     2597 | 2024-03-06 | Team Solid                     | L   | 0.800      | -            | -                | -                | -         |   -19.38 | chay, Lucaozy, PKL, v$m, zevy |
|           30 |     2598 | 2024-03-06 | Team Solid                     | W   | 0.800      | 0.450        | 0.138 (0.050)    | -                | -         |     5.61 | chay, Lucaozy, PKL, v$m, zevy |
|           29 |     2716 | 2024-03-04 | Case Esports                   | W   | 0.787      | -            | -                | -                | -         |     5.56 | chay, Lucaozy, PKL, v$m, zevy |
|           28 |     2717 | 2024-03-04 | Case Esports                   | W   | 0.787      | -            | -                | -                | -         |     5.84 | chay, Lucaozy, PKL, v$m, zevy |
|           27 |     3092 | 2024-02-25 | Imperial Esports               | W   | 0.732      | 0.435        | 0.674 (0.214)    | 0.549 (0.175)    | -         |    21.80 | chay, Lucaozy, PKL, v$m, zevy |
|           26 |     3138 | 2024-02-24 | Sharks Esports                 | W   | 0.726      | 0.435        | 0.063 (0.020)    | -                | -         |     8.98 | chay, Lucaozy, PKL, v$m, zevy |
|           25 |     3277 | 2024-02-21 | W7m esports                    | L   | 0.707      | -            | -                | -                | -         |   -19.93 | chay, Lucaozy, PKL, v$m, zevy |
|           24 |     3283 | 2024-02-21 | W7m esports                    | W   | 0.707      | -            | -                | -                | -         |     2.21 | chay, Lucaozy, PKL, v$m, zevy |
|           23 |     3298 | 2024-02-21 | Team Solid                     | W   | 0.705      | 0.435        | 0.138 (0.042)    | -                | -         |     6.24 | chay, Lucaozy, PKL, v$m, zevy |
|           22 |     3339 | 2024-02-20 | Team Solid                     | L   | 0.699      | -            | -                | -                | -         |   -16.18 | chay, Lucaozy, PKL, v$m, zevy |
|           21 |     3392 | 2024-02-19 | NIGERIA 96                     | W   | 0.694      | -            | -                | -                | -         |     2.34 | chay, Lucaozy, PKL, v$m, zevy |
|           20 |     3520 | 2024-02-16 | 9z Team                        | W   | 0.672      | -            | -                | -                | -         |    10.27 | chay, Lucaozy, PKL, v$m, zevy |
|           19 |     3565 | 2024-02-15 | Imperial Esports               | L   | 0.666      | -            | -                | -                | -         |    -0.95 | chay, Lucaozy, PKL, v$m, zevy |
|           18 |     3576 | 2024-02-15 | Sharks Esports                 | W   | 0.665      | -            | -                | -                | -         |     7.87 | chay, Lucaozy, PKL, v$m, zevy |
|           17 |     3579 | 2024-02-15 | Sharks Esports                 | W   | 0.665      | -            | -                | -                | -         |     8.32 | chay, Lucaozy, PKL, v$m, zevy |
|           16 |     3734 | 2024-02-12 | Flamengo Esports               | W   | 0.644      | -            | -                | -                | -         |     1.55 | chay, Lucaozy, PKL, v$m, zevy |
|           15 |     4208 | 2024-01-28 | Sharks Esports                 | L   | 0.546      | -            | -                | -                | -         |   -10.74 | chay, Lucaozy, PKL, v$m, zevy |
|           14 |     4243 | 2024-01-27 | ??? (Argentinian team)         | W   | 0.540      | -            | -                | -                | -         |     0.60 | chay, Lucaozy, PKL, v$m, zevy |
|           13 |     4304 | 2024-01-26 | RED Canids                     | L   | 0.532      | -            | -                | -                | -         |    -9.70 | chay, Lucaozy, PKL, v$m, zevy |
|           12 |     4421 | 2024-01-23 | 9z Team                        | L   | 0.513      | -            | -                | -                | -         |    -9.29 | chay, Lucaozy, PKL, v$m, zevy |
|           11 |     4448 | 2024-01-22 | ODDIK                          | W   | 0.507      | -            | -                | -                | -         |     6.07 | chay, Lucaozy, PKL, v$m, zevy |
|           10 |     4502 | 2024-01-21 | Case Esports                   | L   | 0.498      | -            | -                | -                | -         |   -13.14 | chay, Lucaozy, PKL, v$m, zevy |
|            9 |     4538 | 2024-01-20 | Imperial Esports               | L   | 0.492      | -            | -                | -                | -         |    -0.70 | chay, Lucaozy, PKL, v$m, zevy |
|            8 |     4587 | 2024-01-19 | RED Canids                     | L   | 0.487      | -            | -                | -                | -         |    -9.65 | chay, Lucaozy, PKL, v$m, zevy |
|            7 |     6130 | 2023-12-02 | Ex-Anonymo Esports             | L   | 0.163      | -            | -                | -                | -         |    -4.21 | chay, Lucaozy, PKL, v$m, zevy |
|            6 |     6222 | 2023-11-30 | G2 Esports                     | L   | 0.150      | -            | -                | -                | -         |    -0.04 | chay, Lucaozy, PKL, v$m, zevy |
|            5 |     6386 | 2023-11-26 | Imperial Esports               | L   | 0.125      | -            | -                | -                | -         |    -0.17 | chay, Lucaozy, PKL, v$m, zevy |
|            4 |     6414 | 2023-11-25 | BESTIA                         | W   | 0.120      | -            | -                | -                | -         |     0.85 | chay, Lucaozy, PKL, v$m, zevy |
|            3 |     6430 | 2023-11-25 | Sharks Esports                 | W   | 0.118      | -            | -                | -                | -         |     1.15 | chay, Lucaozy, PKL, v$m, zevy |
|            2 |     6460 | 2023-11-24 | Patins da Ferrari              | W   | 0.113      | -            | -                | -                | -         |     0.31 | chay, Lucaozy, PKL, v$m, zevy |
|            1 |     6498 | 2023-11-23 | Imperial Esports               | L   | 0.107      | -            | -                | -                | -         |    -0.14 | chay, Lucaozy, PKL, v$m, zevy |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($24,172.82)
- Divide that value by the 5th highest value among all rosters ($158,437.64)
- The final value (0.15) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-03-14 |      0.852 | $5,000.00      | $4,262.27       |
| 2024-02-25 |      0.732 | $25,000.00     | $18,311.34      |
| 2023-11-26 |      0.125 | $12,748.85     | $1,599.21       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
