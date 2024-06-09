### Roster Details<br />
Team Name: Nouns Esports<br />
Roster: cJ-dA-K1nG, Jeorge, junior, nosraC, RUSH<br />
Region: [Americas]( ../standings_americas.md)<br />
<br />
Global Rank: [55](../standings_global.md)<br />
Regional Rank: [13]( ../standings_americas.md)<br />
Final Rank Value:  1036.3<br />
<br />
Final Rank Value (1036.3) = Starting Rank Value (926.5) + Head To Head Adjustments (109.7)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.466[<sup>1</sup>](#table2)
- Bounty Collected: 0.363[<sup>2</sup>](#table1)
- Opponent Network: 0.207[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.259<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 926.5
- 400 + ( ( 0.259 - 0.000 ) / ( 0.787 - 0.000 ) ) * 1600 = 926.5


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent          | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                     |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           65 |      327 | 2024-05-24 | M80               | L   | 1.000      | -            | -                | -                | -         |    -6.39 | cJ-dA-K1nG, Jeorge, junior, nosraC, RUSH   |
|           64 |      379 | 2024-05-23 | NRG               | W   | 1.000      | 0.384        | -                | 0.555 (0.213)    | 0 (0.000) |    11.78 | cJ-dA-K1nG, Jeorge, junior, nosraC, RUSH   |
|           63 |      430 | 2024-05-22 | Party Astronauts  | W   | 1.000      | 0.384        | 0.031 (0.012)    | 0.545 (0.210)    | 0 (0.000) |    15.05 | cJ-dA-K1nG, Jeorge, junior, nosraC, RUSH   |
|           62 |      534 | 2024-05-21 | FLUFFY AIMERS     | W   | 1.000      | 0.477        | 0.030 (0.014)    | 0.384 (0.183)    | 0 (0.000) |     7.61 | cJ-dA-K1nG, Jeorge, junior, nosraC, RUSH   |
|           61 |      536 | 2024-05-21 | FLUFFY AIMERS     | W   | 1.000      | 0.477        | 0.030 (0.014)    | -                | 0 (0.000) |     8.13 | cJ-dA-K1nG, Jeorge, junior, nosraC, RUSH   |
|           60 |      543 | 2024-05-21 | Party Astronauts  | W   | 1.000      | 0.384        | 0.031 (0.012)    | 0.545 (0.210)    | 0 (0.000) |    15.80 | cJ-dA-K1nG, jeorge, junior, nosraC, RUSH   |
|           59 |      549 | 2024-05-21 | Rent Money        | W   | 1.000      | -            | -                | -                | 0 (0.000) |     7.78 | cJ-dA-K1nG, jeorge, junior, nosraC, RUSH   |
|           58 |      557 | 2024-05-21 | TSM Shimmer       | W   | 1.000      | -            | -                | -                | 0 (0.000) |     7.04 | cJ-dA-K1nG, jeorge, junior, nosraC, RUSH   |
|           57 |      561 | 2024-05-21 | Party Astronauts  | L   | 1.000      | -            | -                | -                | -         |   -15.51 | cJ-dA-K1nG, jeorge, junior, nosraC, RUSH   |
|           56 |      578 | 2024-05-21 | The Krubby Krabs  | W   | 1.000      | -            | -                | -                | 0 (0.000) |     2.26 | cJ-dA-K1nG, jeorge, junior, nosraC, RUSH   |
|           55 |      738 | 2024-05-19 | FLUFFY AIMERS     | W   | 1.000      | 0.384        | 0.030 (0.012)    | -                | 0 (0.000) |     8.51 | cJ-dA-K1nG, Jeorge, junior, nosraC, RUSH   |
|           54 |      824 | 2024-05-18 | NRG               | W   | 1.000      | -            | -                | -                | 0 (0.000) |    17.46 | cJ-dA-K1nG, Jeorge, junior, nosraC, RUSH   |
|           53 |      829 | 2024-05-18 | M80               | W   | 1.000      | 0.303        | 0.136 (0.041)    | -                | -         |    27.67 | cJ-dA-K1nG, Jeorge, junior, nosraC, RUSH   |
|           52 |      954 | 2024-05-17 | Wildcard Gaming   | W   | 1.000      | -            | -                | -                | -         |    17.32 | cJ-dA-K1nG, Jeorge, junior, nosraC, RUSH   |
|           51 |     1123 | 2024-05-15 | Carpe Diem        | L   | 1.000      | -            | -                | -                | -         |   -24.81 | cJ-dA-K1nG, Jeorge, junior, nosraC, RUSH   |
|           50 |     1129 | 2024-05-15 | Carpe Diem        | L   | 1.000      | -            | -                | -                | -         |   -26.20 | cJ-dA-K1nG, Jeorge, junior, nosraC, RUSH   |
|           49 |     1307 | 2024-05-13 | Wildcard Gaming   | L   | 1.000      | -            | -                | -                | -         |   -18.49 | cJ-dA-K1nG, CLASIA, Jeorge, junior, nosraC |
|           48 |     1308 | 2024-05-13 | Wildcard Gaming   | W   | 1.000      | 0.477        | -                | 0.525 (0.251)    | -         |    12.77 | cJ-dA-K1nG, CLASIA, Jeorge, junior, nosraC |
|           47 |     1411 | 2024-05-11 | Elevate           | L   | 1.000      | -            | -                | -                | -         |   -17.92 | cJ-dA-K1nG, CLASIA, Jeorge, junior, nosraC |
|           46 |     1412 | 2024-05-11 | Mythic            | L   | 1.000      | -            | -                | -                | -         |   -24.67 | cJ-dA-K1nG, CLASIA, Jeorge, junior, nosraC |
|           45 |     1415 | 2024-05-11 | Elevate           | W   | 1.000      | -            | -                | -                | -         |    11.59 | cJ-dA-K1nG, CLASIA, Jeorge, junior, nosraC |
|           44 |     1553 | 2024-05-09 | BOSS              | W   | 1.000      | 0.477        | 0.016 (0.007)    | -                | -         |     9.82 | cJ-dA-K1nG, CLASIA, Jeorge, junior, nosraC |
|           43 |     1556 | 2024-05-09 | BOSS              | W   | 1.000      | -            | -                | -                | -         |    10.61 | cJ-dA-K1nG, CLASIA, Jeorge, junior, nosraC |
|           42 |     1604 | 2024-05-08 | Take Flyte        | W   | 1.000      | -            | -                | -                | -         |     7.54 | cJ-dA-K1nG, CLASIA, Jeorge, junior, nosraC |
|           41 |     1610 | 2024-05-08 | Take Flyte        | W   | 1.000      | -            | -                | -                | -         |     8.06 | cJ-dA-K1nG, CLASIA, Jeorge, junior, nosraC |
|           40 |     2443 | 2024-04-23 | One More Esports  | L   | 0.959      | -            | -                | -                | -         |   -23.88 | cJ-dA-K1nG, CLASIA, Jeorge, junior, nosraC |
|           39 |     2448 | 2024-04-23 | One More Esports  | W   | 0.959      | -            | -                | -                | -         |     5.90 | cJ-dA-K1nG, CLASIA, Jeorge, junior, nosraC |
|           38 |     2857 | 2024-04-17 | Elevate           | L   | 0.919      | -            | -                | -                | -         |   -18.31 | cJ-dA-K1nG, CLASIA, Jeorge, junior, nosraC |
|           37 |     2864 | 2024-04-17 | Take Flyte        | W   | 0.918      | -            | -                | -                | -         |     6.78 | cJ-dA-K1nG, CLASIA, Jeorge, junior, nosraC |
|           36 |     2945 | 2024-04-16 | VitaPLUR          | W   | 0.912      | -            | -                | -                | -         |     1.83 | cJ-dA-K1nG, CLASIA, Jeorge, junior, nosraC |
|           35 |     2993 | 2024-04-15 | Limitless         | W   | 0.906      | -            | -                | -                | -         |     4.07 | cJ-dA-K1nG, Jeorge, junior, MarKE, nosraC  |
|           34 |     2994 | 2024-04-15 | Limitless         | W   | 0.906      | -            | -                | -                | -         |     4.23 | cJ-dA-K1nG, Jeorge, junior, MarKE, nosraC  |
|           33 |     3208 | 2024-04-10 | Elevate           | W   | 0.873      | 0.477        | -                | 0.480 (0.200)    | -         |     9.83 | cJ-dA-K1nG, Jeorge, junior, MarKE, nosraC  |
|           32 |     3213 | 2024-04-10 | Elevate           | W   | 0.873      | 0.477        | -                | 0.480 (0.200)    | -         |    10.57 | cJ-dA-K1nG, Jeorge, junior, MarKE, nosraC  |
|           31 |     3291 | 2024-04-09 | MIGHT             | W   | 0.866      | -            | -                | -                | -         |     4.25 | cJ-dA-K1nG, Jeorge, junior, MarKE, nosraC  |
|           30 |     3295 | 2024-04-09 | MIGHT             | W   | 0.866      | -            | -                | -                | -         |     4.42 | cJ-dA-K1nG, Jeorge, junior, MarKE, nosraC  |
|           29 |     3546 | 2024-04-04 | LAG Gaming        | L   | 0.833      | -            | -                | -                | -         |   -14.97 | cJ-dA-K1nG, Jeorge, junior, MarKE, nosraC  |
|           28 |     3550 | 2024-04-04 | LAG Gaming        | W   | 0.833      | -            | -                | -                | -         |    11.29 | cJ-dA-K1nG, Jeorge, junior, MarKE, nosraC  |
|           27 |     3608 | 2024-04-03 | Party Astronauts  | L   | 0.826      | -            | -                | -                | -         |   -12.73 | cJ-dA-K1nG, Jeorge, junior, MarKE, nosraC  |
|           26 |     3671 | 2024-04-02 | BOSS              | W   | 0.819      | -            | -                | -                | -         |     8.34 | cJ-dA-K1nG, Jeorge, junior, MarKE, nosraC  |
|           25 |     3675 | 2024-04-02 | Party Astronauts  | W   | 0.818      | -            | -                | -                | -         |    13.13 | cJ-dA-K1nG, Jeorge, junior, MarKE, nosraC  |
|           24 |     3852 | 2024-03-27 | NRG               | L   | 0.780      | -            | -                | -                | -         |   -15.00 | cJ-dA-K1nG, Jeorge, junior, MarKE, nosraC  |
|           23 |     3856 | 2024-03-27 | NRG               | W   | 0.780      | 0.477        | -                | 0.555 (0.206)    | -         |     9.56 | cJ-dA-K1nG, Jeorge, junior, MarKE, nosraC  |
|           22 |     3933 | 2024-03-26 | Party Astronauts  | W   | 0.773      | 0.477        | 0.031 (0.011)    | 0.545 (0.201)    | -         |    12.87 | cJ-dA-K1nG, Jeorge, junior, MarKE, nosraC  |
|           21 |     3938 | 2024-03-26 | Party Astronauts  | W   | 0.773      | 0.477        | 0.031 (0.011)    | 0.545 (0.201)    | -         |    13.78 | cJ-dA-K1nG, Jeorge, junior, MarKE, nosraC  |
|           20 |     4207 | 2024-03-20 | Mythic            | L   | 0.733      | -            | -                | -                | -         |   -16.57 | cJ-dA-K1nG, Jeorge, junior, MarKE, nosraC  |
|           19 |     4213 | 2024-03-20 | Mythic            | W   | 0.733      | -            | -                | -                | -         |     6.42 | cJ-dA-K1nG, Jeorge, junior, MarKE, nosraC  |
|           18 |     5280 | 2024-03-02 | Legacy            | L   | 0.611      | -            | -                | -                | -         |    -7.36 | cJ-dA-K1nG, Jeorge, junior, MarKE, nosraC  |
|           17 |     5372 | 2024-03-01 | FURIA Esports     | L   | 0.604      | -            | -                | -                | -         |    -1.32 | cJ-dA-K1nG, Jeorge, junior, MarKE, nosraC  |
|           16 |     5546 | 2024-02-26 | Team Liquid       | L   | 0.580      | -            | -                | -                | -         |    -0.37 | cJ-dA-K1nG, Jeorge, junior, MarKE, nosraC  |
|           15 |     5591 | 2024-02-25 | BOSS              | W   | 0.573      | -            | -                | -                | -         |     6.94 | cJ-dA-K1nG, Jeorge, junior, MarKE, nosraC  |
|           14 |     5595 | 2024-02-25 | Team Liquid       | W   | 0.572      | 0.143        | 0.493 (0.040)    | -                | -         |    17.71 | cJ-dA-K1nG, Jeorge, junior, MarKE, nosraC  |
|           13 |     6690 | 2024-02-03 | Wildcard Gaming   | L   | 0.426      | -            | -                | -                | -         |    -6.73 | cJ-dA-K1nG, Jeorge, junior, MarKE, nosraC  |
|           12 |     6850 | 2024-02-01 | BOSS              | W   | 0.413      | -            | -                | -                | -         |     5.21 | cJ-dA-K1nG, Jeorge, junior, MarKE, nosraC  |
|           11 |     6855 | 2024-02-01 | Elevate           | L   | 0.412      | -            | -                | -                | -         |    -7.61 | cJ-dA-K1nG, Jeorge, junior, MarKE, nosraC  |
|           10 |     6860 | 2024-02-01 | Rocket            | W   | 0.412      | -            | -                | -                | -         |     1.84 | cJ-dA-K1nG, Jeorge, junior, MarKE, nosraC  |
|            9 |     7691 | 2024-01-18 | Wildcard Gaming   | L   | 0.320      | -            | -                | -                | -         |    -5.54 | cJ-dA-K1nG, Jeorge, junior, MarKE, nosraC  |
|            8 |     7692 | 2024-01-18 | Rocket            | W   | 0.319      | -            | -                | -                | -         |     1.24 | cJ-dA-K1nG, Jeorge, junior, MarKE, nosraC  |
|            7 |     7695 | 2024-01-18 | Zomblers          | W   | 0.319      | -            | -                | -                | -         |     1.70 | cJ-dA-K1nG, Jeorge, junior, MarKE, nosraC  |
|            6 |     7754 | 2024-01-17 | Snakes Den Gaming | W   | 0.313      | -            | -                | -                | -         |     0.94 | cJ-dA-K1nG, Jeorge, junior, MarKE, nosraC  |
|            5 |     7990 | 2024-01-14 | Carpe Diem        | W   | 0.294      | -            | -                | -                | -         |     1.51 | cJ-dA-K1nG, Jeorge, junior, MarKE, nosraC  |
|            4 |     7994 | 2024-01-14 | M80               | L   | 0.293      | -            | -                | -                | -         |    -1.18 | cJ-dA-K1nG, Jeorge, junior, MarKE, nosraC  |
|            3 |     8020 | 2024-01-13 | NRG               | W   | 0.286      | -            | -                | -                | -         |     3.44 | cJ-dA-K1nG, Jeorge, junior, MarKE, nosraC  |
|            2 |     8059 | 2024-01-12 | vagrants          | W   | 0.281      | -            | -                | -                | -         |     0.80 | cJ-dA-K1nG, Jeorge, junior, MarKE, nosraC  |
|            1 |     8073 | 2024-01-12 | Team Liquid       | L   | 0.280      | -            | -                | -                | -         |    -0.14 | cJ-dA-K1nG, Jeorge, junior, MarKE, nosraC  |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($21,500.00)
- Divide that value by the 5th highest value among all rosters ($300,806.11)
- The final value (0.07) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-05-24 |      1.000 | $5,000.00      | $5,000.00       |
| 2024-05-21 |      1.000 | $12,500.00     | $12,500.00      |
| 2024-05-18 |      1.000 | $4,000.00      | $4,000.00       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
