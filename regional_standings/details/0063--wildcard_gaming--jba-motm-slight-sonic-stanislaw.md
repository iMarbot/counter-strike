### Roster Details<br />
Team Name: Wildcard Gaming<br />
Roster: JBa, motm, SLIGHT, Sonic, stanislaw<br />
Region: [Americas]( ../standings_americas.md)<br />
<br />
Global Rank: [63](../standings_global.md)<br />
Regional Rank: [15]( ../standings_americas.md)<br />
Final Rank Value:  983.8<br />
<br />
Final Rank Value (983.8) = Starting Rank Value (876.6) + Head To Head Adjustments (107.2)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.342[<sup>1</sup>](#table2)
- Bounty Collected: 0.340[<sup>2</sup>](#table1)
- Opponent Network: 0.190[<sup>2</sup>](#table1)
- LAN Wins: 0.065[<sup>2</sup>](#table1)

The average of these factors is 0.234<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 876.6
- 400 + ( ( 0.234 - 0.000 ) / ( 0.786 - 0.000 ) ) * 1600 = 876.6


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent          | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                   |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           73 |       22 | 2024-05-29 | Team Karma        | W   | 1.000      | -            | -                | -                | 0 (0.000) |     5.60 | JBa, motm, SLIGHT, Sonic, stanislaw      |
|           72 |       28 | 2024-05-29 | NuTorious         | W   | 1.000      | -            | -                | -                | 0 (0.000) |     1.19 | JBa, motm, SLIGHT, Sonic, stanislaw      |
|           71 |      378 | 2024-05-23 | M80               | L   | 1.000      | -            | -                | -                | -         |    -4.80 | Grizz, JBa, SLIGHT, Sonic, stanislaw     |
|           70 |      421 | 2024-05-22 | One More Esports  | W   | 1.000      | -            | -                | -                | 0 (0.000) |     4.88 | Grizz, JBa, SLIGHT, Sonic, stanislaw     |
|           69 |      426 | 2024-05-22 | One More Esports  | W   | 1.000      | -            | -                | -                | 0 (0.000) |     5.11 | Grizz, JBa, SLIGHT, Sonic, stanislaw     |
|           68 |      434 | 2024-05-22 | LAG Gaming        | W   | 1.000      | 0.384        | 0.013 (0.005)    | 0.335 (0.129)    | 0 (0.000) |    10.14 | Grizz, JBa, SLIGHT, Sonic, stanislaw     |
|           67 |      541 | 2024-05-21 | Carpe Diem        | W   | 1.000      | -            | -                | -                | 0 (0.000) |     6.94 | Grizz, JBa, SLIGHT, Sonic, stanislaw     |
|           66 |      543 | 2024-05-21 | Carpe Diem        | W   | 1.000      | -            | -                | -                | 0 (0.000) |     7.38 | Grizz, JBa, SLIGHT, Sonic, stanislaw     |
|           65 |      722 | 2024-05-19 | Limitless         | W   | 1.000      | -            | -                | -                | 0 (0.000) |     5.19 | Grizz, JBa, SLIGHT, Sonic, stanislaw     |
|           64 |      942 | 2024-05-17 | Nouns Esports     | L   | 1.000      | -            | -                | -                | -         |   -17.07 | Grizz, JBa, motm, SLIGHT, stanislaw      |
|           63 |     1112 | 2024-05-15 | BOSS              | W   | 1.000      | 0.477        | 0.016 (0.007)    | 0.315 (0.150)    | 0 (0.000) |    10.74 | Grizz, JBa, SLIGHT, Sonic, stanislaw     |
|           62 |     1118 | 2024-05-15 | BOSS              | W   | 1.000      | 0.477        | 0.016 (0.007)    | 0.315 (0.150)    | -         |    11.64 | Grizz, JBa, SLIGHT, Sonic, stanislaw     |
|           61 |     1217 | 2024-05-14 | FLUFFY AIMERS     | W   | 1.000      | 0.477        | 0.030 (0.014)    | 0.384 (0.183)    | -         |    11.85 | Grizz, JBa, SLIGHT, Sonic, stanislaw     |
|           60 |     1223 | 2024-05-14 | FLUFFY AIMERS     | W   | 1.000      | 0.477        | 0.030 (0.014)    | 0.384 (0.183)    | -         |    12.89 | Grizz, JBa, SLIGHT, Sonic, stanislaw     |
|           59 |     1296 | 2024-05-13 | Nouns Esports     | W   | 1.000      | 0.477        | 0.071 (0.034)    | 0.507 (0.242)    | -         |    18.80 | Grizz, JBa, SLIGHT, Sonic, stanislaw     |
|           58 |     1297 | 2024-05-13 | Nouns Esports     | L   | 1.000      | -            | -                | -                | -         |   -12.44 | Grizz, JBa, SLIGHT, Sonic, stanislaw     |
|           57 |     1400 | 2024-05-11 | Elevate           | L   | 1.000      | -            | -                | -                | -         |   -15.80 | Grizz, JBa, SLIGHT, Sonic, stanislaw     |
|           56 |     1401 | 2024-05-11 | Mythic            | L   | 1.000      | -            | -                | -                | -         |   -23.48 | Grizz, JBa, SLIGHT, Sonic, stanislaw     |
|           55 |     1544 | 2024-05-09 | MIGHT             | W   | 1.000      | -            | -                | -                | -         |     5.03 | Grizz, JBa, SLIGHT, Sonic, stanislaw     |
|           54 |     1545 | 2024-05-09 | MIGHT             | W   | 1.000      | -            | -                | -                | -         |     5.28 | Grizz, JBa, SLIGHT, Sonic, stanislaw     |
|           53 |     1586 | 2024-05-08 | Limitless         | W   | 1.000      | -            | -                | -                | -         |     5.58 | Grizz, JBa, SLIGHT, Sonic, stanislaw     |
|           52 |     1590 | 2024-05-08 | Limitless         | W   | 1.000      | -            | -                | -                | -         |     5.88 | Grizz, JBa, SLIGHT, Sonic, stanislaw     |
|           51 |     1900 | 2024-05-02 | Party Astronauts  | W   | 1.000      | 0.477        | 0.031 (0.015)    | 0.545 (0.260)    | -         |    18.64 | C4LLM3SU3, JBa, SLIGHT, Sonic, stanislaw |
|           50 |     1901 | 2024-05-02 | Party Astronauts  | L   | 1.000      | -            | -                | -                | -         |   -12.61 | C4LLM3SU3, JBa, SLIGHT, Sonic, stanislaw |
|           49 |     2292 | 2024-04-25 | NRG               | W   | 0.973      | 0.477        | -                | 0.555 (0.257)    | -         |    15.22 | C4LLM3SU3, JBa, SLIGHT, Sonic, stanislaw |
|           48 |     2294 | 2024-04-25 | NRG               | L   | 0.973      | -            | -                | -                | -         |   -15.47 | C4LLM3SU3, JBa, SLIGHT, Sonic, stanislaw |
|           47 |     2395 | 2024-04-23 | Elevate           | W   | 0.960      | 0.477        | 0.012 (0.005)    | 0.475 (0.217)    | -         |    14.91 | C4LLM3SU3, JBa, SLIGHT, Sonic, stanislaw |
|           46 |     2402 | 2024-04-23 | Elevate           | L   | 0.959      | -            | -                | -                | -         |   -15.38 | C4LLM3SU3, JBa, SLIGHT, Sonic, stanislaw |
|           45 |     2807 | 2024-04-17 | Elevate           | L   | 0.918      | -            | -                | -                | -         |   -16.33 | C4LLM3SU3, JBa, SLIGHT, Sonic, stanislaw |
|           44 |     2890 | 2024-04-16 | Snakes Den Gaming | W   | 0.912      | -            | -                | -                | -         |     4.39 | C4LLM3SU3, JBa, SLIGHT, Sonic, stanislaw |
|           43 |     3273 | 2024-04-08 | Cloud9            | L   | 0.860      | -            | -                | -                | -         |    -0.91 | horvy, motm, SLIGHT, Sonic, stanislaw    |
|           42 |     3317 | 2024-04-07 | Virtus.pro        | L   | 0.854      | -            | -                | -                | -         |    -0.37 | horvy, motm, SLIGHT, Sonic, stanislaw    |
|           41 |     3766 | 2024-03-27 | Mythic            | W   | 0.779      | 0.477        | -                | 0.339 (0.126)    | -         |     6.96 | C4LLM3SU3, JBa, SLIGHT, Sonic, stanislaw |
|           40 |     3772 | 2024-03-27 | Mythic            | W   | 0.779      | -            | -                | -                | -         |     7.37 | C4LLM3SU3, JBa, SLIGHT, Sonic, stanislaw |
|           39 |     3839 | 2024-03-26 | LAG Gaming        | W   | 0.773      | -            | -                | -                | -         |    12.80 | C4LLM3SU3, JBa, SLIGHT, Sonic, stanislaw |
|           38 |     3844 | 2024-03-26 | LAG Gaming        | L   | 0.773      | -            | -                | -                | -         |   -11.70 | C4LLM3SU3, JBa, SLIGHT, Sonic, stanislaw |
|           37 |     4530 | 2024-03-12 | Mythic            | L   | 0.679      | -            | -                | -                | -         |   -15.70 | Infinite, JBa, SLIGHT, Sonic, stanislaw  |
|           36 |     4540 | 2024-03-12 | FPL Friends       | W   | 0.679      | -            | -                | -                | -         |     1.04 | Infinite, JBa, SLIGHT, Sonic, stanislaw  |
|           35 |     5090 | 2024-03-03 | M80               | L   | 0.617      | -            | -                | -                | -         |    -2.57 | Infinite, JBa, SLIGHT, Sonic, stanislaw  |
|           34 |     5173 | 2024-03-02 | BESTIA            | W   | 0.611      | -            | -                | -                | 1 (0.611) |    10.75 | Infinite, JBa, SLIGHT, Sonic, stanislaw  |
|           33 |     5220 | 2024-03-01 | RED Canids        | L   | 0.605      | -            | -                | -                | -         |    -7.40 | Infinite, JBa, SLIGHT, Sonic, stanislaw  |
|           32 |     5432 | 2024-02-25 | Team Liquid       | L   | 0.573      | -            | -                | -                | -         |    -0.33 | Infinite, JBa, SLIGHT, Sonic, stanislaw  |
|           31 |     5436 | 2024-02-25 | BOSS              | L   | 0.572      | -            | -                | -                | -         |   -11.13 | Infinite, JBa, SLIGHT, Sonic, stanislaw  |
|           30 |     5473 | 2024-02-24 | NRG               | W   | 0.566      | -            | -                | -                | -         |     7.39 | Infinite, JBa, SLIGHT, Sonic, stanislaw  |
|           29 |     5478 | 2024-02-24 | Party Astronauts  | W   | 0.566      | -            | -                | -                | -         |     9.31 | Infinite, JBa, SLIGHT, Sonic, stanislaw  |
|           28 |     5486 | 2024-02-24 | G3                | W   | 0.566      | -            | -                | -                | -         |     5.29 | Infinite, JBa, SLIGHT, Sonic, stanislaw  |
|           27 |     5585 | 2024-02-23 | MIGHT             | W   | 0.560      | -            | -                | -                | -         |     3.91 | Infinite, JBa, SLIGHT, Sonic, stanislaw  |
|           26 |     5632 | 2024-02-22 | NRG               | L   | 0.552      | -            | -                | -                | -         |   -10.14 | Infinite, JBa, motm, SLIGHT, stanislaw   |
|           25 |     5679 | 2024-02-21 | Xmplfy            | W   | 0.546      | -            | -                | -                | -         |     0.86 | Infinite, JBa, motm, SLIGHT, stanislaw   |
|           24 |     6446 | 2024-02-04 | Elevate           | L   | 0.432      | -            | -                | -                | -         |    -7.73 | Infinite, JBa, SLIGHT, Sonic, stanislaw  |
|           23 |     6487 | 2024-02-03 | Nouns Esports     | W   | 0.426      | -            | -                | -                | -         |     6.73 | Infinite, JBa, motm, SLIGHT, stanislaw   |
|           22 |     6582 | 2024-02-02 | NRG               | W   | 0.419      | -            | -                | -                | -         |     5.34 | Infinite, JBa, SLIGHT, Sonic, stanislaw  |
|           21 |     6586 | 2024-02-02 | Carpe Diem        | W   | 0.418      | -            | -                | -                | -         |     2.25 | Infinite, JBa, SLIGHT, Sonic, stanislaw  |
|           20 |     7100 | 2024-01-24 | One More Esports  | W   | 0.359      | -            | -                | -                | -         |     3.31 | Infinite, JBa, SLIGHT, Sonic, stanislaw  |
|           19 |     7154 | 2024-01-23 | MIGHT             | W   | 0.353      | -            | -                | -                | -         |     2.48 | Infinite, JBa, SLIGHT, Sonic, stanislaw  |
|           18 |     7163 | 2024-01-23 | The Nomads        | W   | 0.353      | -            | -                | -                | -         |     0.92 | Infinite, JBa, SLIGHT, Sonic, stanislaw  |
|           17 |     7308 | 2024-01-20 | M80               | L   | 0.332      | -            | -                | -                | -         |    -1.21 | Infinite, JBa, SLIGHT, Sonic, stanislaw  |
|           16 |     7380 | 2024-01-19 | Team Liquid       | L   | 0.327      | -            | -                | -                | -         |    -0.15 | Infinite, JBa, SLIGHT, Sonic, stanislaw  |
|           15 |     7390 | 2024-01-19 | M80               | W   | 0.325      | 0.143        | 0.136 (0.006)    | -                | -         |     9.14 | Infinite, JBa, SLIGHT, Sonic, stanislaw  |
|           14 |     7444 | 2024-01-18 | Nouns Esports     | W   | 0.320      | -            | -                | -                | -         |     5.54 | Infinite, JBa, SLIGHT, Sonic, stanislaw  |
|           13 |     7446 | 2024-01-18 | NRG               | W   | 0.319      | -            | -                | -                | -         |     4.26 | Infinite, JBa, SLIGHT, Sonic, stanislaw  |
|           12 |     7450 | 2024-01-18 | MIGHT             | W   | 0.319      | -            | -                | -                | -         |     2.44 | Infinite, JBa, SLIGHT, Sonic, stanislaw  |
|           11 |     7503 | 2024-01-17 | Mythic            | W   | 0.313      | -            | -                | -                | -         |     3.02 | Infinite, JBa, SLIGHT, Sonic, stanislaw  |
|           10 |     7613 | 2024-01-16 | Team Liquid       | L   | 0.306      | -            | -                | -                | -         |    -0.12 | Infinite, JBa, SLIGHT, Sonic, stanislaw  |
|            9 |     7698 | 2024-01-15 | ex-CatEvil        | W   | 0.299      | -            | -                | -                | -         |     1.60 | Infinite, JBa, SLIGHT, Sonic, stanislaw  |
|            8 |     7762 | 2024-01-13 | M80               | W   | 0.286      | 0.143        | 0.136 (0.006)    | -                | -         |     8.19 | Infinite, JBa, SLIGHT, Sonic, stanislaw  |
|            7 |     7814 | 2024-01-12 | BOSS              | W   | 0.281      | -            | -                | -                | -         |     4.21 | Infinite, JBa, SLIGHT, Sonic, stanislaw  |
|            6 |     7818 | 2024-01-12 | vagrants          | W   | 0.280      | -            | -                | -                | -         |     1.04 | Infinite, JBa, SLIGHT, Sonic, stanislaw  |
|            5 |     8538 | 2023-12-16 | FPL Friends       | L   | 0.100      | -            | -                | -                | -         |    -2.50 | Infinite, JBa, SLIGHT, Sonic, stanislaw  |
|            4 |     8546 | 2023-12-16 | Tsunami Esports   | W   | 0.099      | -            | -                | -                | -         |     0.20 | Infinite, JBa, SLIGHT, Sonic, stanislaw  |
|            3 |     8901 | 2023-12-11 | NRG               | L   | 0.066      | -            | -                | -                | -         |    -1.17 | Infinite, JBa, SLIGHT, Sonic, stanislaw  |
|            2 |     9412 | 2023-12-02 | M80               | L   | 0.006      | -            | -                | -                | -         |    -0.02 | CLASIA, Infinite, JBa, SLIGHT, stanislaw |
|            1 |     9422 | 2023-12-02 | Gifted Moments    | W   | 0.006      | -            | -                | -                | -         |     0.01 | CLASIA, Infinite, JBa, SLIGHT, stanislaw |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($3,580.65)
- Divide that value by the 5th highest value among all rosters ($300,806.11)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
