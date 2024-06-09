### Roster Details<br />
Team Name: Party Astronauts<br />
Roster: ben1337, cxzi, FaNg, Infinite, WolfY<br />
Region: [Americas]( ../standings_americas.md)<br />
<br />
Global Rank: [61](../standings_global.md)<br />
Regional Rank: [14]( ../standings_americas.md)<br />
Final Rank Value:  999.9<br />
<br />
Final Rank Value (999.9) = Starting Rank Value (941.5) + Head To Head Adjustments (58.5)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.398[<sup>1</sup>](#table2)
- Bounty Collected: 0.361[<sup>2</sup>](#table1)
- Opponent Network: 0.204[<sup>2</sup>](#table1)
- LAN Wins: 0.104[<sup>2</sup>](#table1)

The average of these factors is 0.266<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 941.5
- 400 + ( ( 0.266 - 0.000 ) / ( 0.787 - 0.000 ) ) * 1600 = 941.5


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent          | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                               |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           72 |      430 | 2024-05-22 | Nouns Esports     | L   | 1.000      | -            | -                | -                | -         |   -15.05 | ben1337, cxzi, FaNg, Infinite, WolfY |
|           71 |      440 | 2024-05-22 | M80               | W   | 1.000      | 0.477        | 0.136 (0.065)    | 0.525 (0.250)    | 0 (0.000) |    26.27 | ben1337, cxzi, FaNg, Infinite, WolfY |
|           70 |      442 | 2024-05-22 | M80               | L   | 1.000      | -            | -                | -                | -         |    -4.75 | ben1337, cxzi, FaNg, Infinite, WolfY |
|           69 |      535 | 2024-05-21 | Limitless         | W   | 1.000      | -            | -                | -                | 0 (0.000) |     3.98 | ben1337, cxzi, FaNg, Infinite, WolfY |
|           68 |      537 | 2024-05-21 | Limitless         | W   | 1.000      | -            | -                | -                | 0 (0.000) |     4.14 | ben1337, cxzi, FaNg, Infinite, WolfY |
|           67 |      543 | 2024-05-21 | Nouns Esports     | L   | 1.000      | -            | -                | -                | -         |   -15.80 | ben1337, cxzi, FaNg, Infinite, WolfY |
|           66 |      548 | 2024-05-21 | FLUFFY AIMERS     | W   | 1.000      | 0.384        | 0.030 (0.012)    | -                | 0 (0.000) |     8.18 | ben1337, cxzi, FaNg, Infinite, WolfY |
|           65 |      556 | 2024-05-21 | The Krubby Krabs  | W   | 1.000      | -            | -                | -                | 0 (0.000) |     2.44 | ben1337, cxzi, FaNg, Infinite, WolfY |
|           64 |      561 | 2024-05-21 | Nouns Esports     | W   | 1.000      | 0.384        | 0.071 (0.027)    | 0.507 (0.195)    | 0 (0.000) |    15.51 | ben1337, cxzi, FaNg, Infinite, WolfY |
|           63 |      577 | 2024-05-21 | TSM Shimmer       | W   | 1.000      | 0.384        | 0.017 (0.007)    | -                | 0 (0.000) |     8.14 | ben1337, cxzi, FaNg, Infinite, WolfY |
|           62 |      638 | 2024-05-20 | G3                | W   | 1.000      | -            | -                | -                | 0 (0.000) |    10.31 | ben1337, cxzi, FaNg, Infinite, WolfY |
|           61 |      854 | 2024-05-18 | NRG               | L   | 1.000      | -            | -                | -                | -         |   -13.88 | ben1337, chop, cxzi, Infinite, WolfY |
|           60 |      957 | 2024-05-17 | Legacy            | W   | 1.000      | 0.303        | 0.027 (0.008)    | -                | 0 (0.000) |    21.01 | ben1337, chop, cxzi, Infinite, WolfY |
|           59 |     1031 | 2024-05-16 | FLUFFY AIMERS     | W   | 1.000      | 0.477        | 0.030 (0.014)    | 0.384 (0.183)    | -         |    10.96 | ben1337, cxzi, Infinite, RUSH, WolfY |
|           58 |     1036 | 2024-05-16 | FLUFFY AIMERS     | W   | 1.000      | 0.477        | 0.030 (0.014)    | 0.384 (0.183)    | -         |    11.89 | ben1337, cxzi, Infinite, RUSH, WolfY |
|           57 |     1224 | 2024-05-14 | Mythic            | W   | 1.000      | 0.477        | -                | 0.339 (0.162)    | -         |    10.01 | ben1337, chop, cxzi, RUSH, WolfY     |
|           56 |     1230 | 2024-05-14 | Mythic            | L   | 1.000      | -            | -                | -                | -         |   -21.96 | ben1337, chop, cxzi, RUSH, WolfY     |
|           55 |     1420 | 2024-05-11 | BOSS              | L   | 1.000      | -            | -                | -                | -         |   -20.18 | ben1337, chop, cxzi, RUSH, WolfY     |
|           54 |     1423 | 2024-05-11 | Take Flyte        | L   | 1.000      | -            | -                | -                | -         |   -23.56 | ben1337, chop, cxzi, RUSH, WolfY     |
|           53 |     1601 | 2024-05-08 | LAG Gaming        | W   | 1.000      | 0.477        | 0.013 (0.006)    | 0.335 (0.160)    | -         |    11.91 | ben1337, chop, cxzi, RUSH, WolfY     |
|           52 |     1605 | 2024-05-08 | LAG Gaming        | W   | 1.000      | 0.477        | 0.013 (0.006)    | 0.335 (0.160)    | -         |    12.96 | ben1337, chop, cxzi, RUSH, WolfY     |
|           51 |     1676 | 2024-05-07 | Elevate           | L   | 1.000      | -            | -                | -                | -         |   -19.00 | ben1337, chop, cxzi, RUSH, WolfY     |
|           50 |     1677 | 2024-05-07 | Elevate           | W   | 1.000      | 0.477        | -                | 0.480 (0.229)    | -         |    12.22 | ben1337, chop, cxzi, RUSH, WolfY     |
|           49 |     1721 | 2024-05-06 | NRG               | L   | 1.000      | -            | -                | -                | -         |   -19.03 | ben1337, chop, cxzi, RUSH, WolfY     |
|           48 |     1722 | 2024-05-06 | NRG               | W   | 1.000      | 0.477        | -                | 0.555 (0.265)    | -         |    12.19 | ben1337, chop, cxzi, RUSH, WolfY     |
|           47 |     1925 | 2024-05-02 | Wildcard Gaming   | L   | 1.000      | -            | -                | -                | -         |   -18.27 | ben1337, chop, cxzi, RUSH, WolfY     |
|           46 |     1926 | 2024-05-02 | Wildcard Gaming   | W   | 1.000      | 0.477        | -                | 0.525 (0.251)    | -         |    13.01 | ben1337, chop, cxzi, RUSH, WolfY     |
|           45 |     2255 | 2024-04-26 | Aurora Gaming     | L   | 0.981      | -            | -                | -                | -         |    -3.01 | ben1337, chop, cxzi, RUSH, WolfY     |
|           44 |     2257 | 2024-04-26 | sunday school     | W   | 0.980      | -            | -                | -                | 1 (0.980) |     4.88 | ben1337, chop, cxzi, RUSH, WolfY     |
|           43 |     2330 | 2024-04-25 | Aurora Gaming     | L   | 0.973      | -            | -                | -                | -         |    -2.69 | ben1337, chop, cxzi, RUSH, WolfY     |
|           42 |     2947 | 2024-04-16 | G3                | L   | 0.912      | -            | -                | -                | -         |   -20.94 | ben1337, chop, cxzi, RUSH, WolfY     |
|           41 |     3293 | 2024-04-09 | One More Esports  | W   | 0.866      | -            | -                | -                | -         |     4.96 | ben1337, chop, cxzi, RUSH, WolfY     |
|           40 |     3297 | 2024-04-09 | One More Esports  | W   | 0.866      | -            | -                | -                | -         |     5.19 | ben1337, chop, cxzi, RUSH, WolfY     |
|           39 |     3547 | 2024-04-04 | MIGHT             | W   | 0.833      | -            | -                | -                | -         |     3.76 | ben1337, chop, cxzi, RUSH, WolfY     |
|           38 |     3551 | 2024-04-04 | MIGHT             | W   | 0.833      | -            | -                | -                | -         |     3.90 | ben1337, chop, cxzi, RUSH, WolfY     |
|           37 |     3608 | 2024-04-03 | Nouns Esports     | W   | 0.826      | 0.143        | 0.071 (0.008)    | -                | -         |    12.73 | ben1337, chop, cxzi, RUSH, WolfY     |
|           36 |     3620 | 2024-04-03 | BOSS              | W   | 0.825      | -            | -                | -                | -         |     8.21 | ben1337, chop, cxzi, RUSH, WolfY     |
|           35 |     3670 | 2024-04-02 | Take Flyte        | W   | 0.819      | -            | -                | -                | -         |     6.21 | ben1337, chop, cxzi, RUSH, WolfY     |
|           34 |     3675 | 2024-04-02 | Nouns Esports     | L   | 0.818      | -            | -                | -                | -         |   -13.13 | ben1337, chop, cxzi, RUSH, WolfY     |
|           33 |     3853 | 2024-03-27 | Carpe Diem        | W   | 0.780      | -            | -                | -                | -         |     3.73 | ben1337, chop, cxzi, RUSH, WolfY     |
|           32 |     3857 | 2024-03-27 | Carpe Diem        | W   | 0.780      | -            | -                | -                | -         |     3.86 | ben1337, chop, cxzi, RUSH, WolfY     |
|           31 |     3933 | 2024-03-26 | Nouns Esports     | L   | 0.773      | -            | -                | -                | -         |   -12.87 | ben1337, chop, cxzi, RUSH, WolfY     |
|           30 |     3938 | 2024-03-26 | Nouns Esports     | L   | 0.773      | -            | -                | -                | -         |   -13.78 | ben1337, chop, cxzi, RUSH, WolfY     |
|           29 |     4206 | 2024-03-20 | BOSS              | W   | 0.733      | -            | -                | -                | -         |     7.78 | ben1337, chop, cxzi, RUSH, WolfY     |
|           28 |     4208 | 2024-03-20 | BOSS              | W   | 0.733      | -            | -                | -                | -         |     8.25 | ben1337, chop, cxzi, RUSH, WolfY     |
|           27 |     4249 | 2024-03-19 | Take Flyte        | W   | 0.727      | -            | -                | -                | -         |     5.48 | ben1337, chop, cxzi, RUSH, WolfY     |
|           26 |     4250 | 2024-03-19 | Take Flyte        | W   | 0.726      | -            | -                | -                | -         |     5.75 | ben1337, chop, cxzi, RUSH, WolfY     |
|           25 |     4576 | 2024-03-13 | Carpe Diem        | W   | 0.685      | -            | -                | -                | -         |     3.73 | ben1337, chop, cxzi, RUSH, WolfY     |
|           24 |     4645 | 2024-03-12 | Elevate           | W   | 0.679      | -            | -                | -                | -         |     7.96 | ben1337, chop, cxzi, RUSH, WolfY     |
|           23 |     4653 | 2024-03-12 | LAG Gaming        | W   | 0.679      | -            | -                | -                | -         |     9.79 | ben1337, chop, cxzi, RUSH, WolfY     |
|           22 |     5636 | 2024-02-24 | Wildcard Gaming   | L   | 0.566      | -            | -                | -                | -         |    -9.32 | ben1337, chop, cxzi, Walco, WolfY    |
|           21 |     5644 | 2024-02-24 | ex-CatEvil        | W   | 0.566      | -            | -                | -                | -         |     2.55 | ben1337, chop, cxzi, Walco, WolfY    |
|           20 |     5740 | 2024-02-23 | E-Xolos LAZER     | W   | 0.560      | -            | -                | -                | -         |     0.84 | ben1337, chop, cxzi, Walco, WolfY    |
|           19 |     5785 | 2024-02-22 | Team Liquid       | L   | 0.553      | -            | -                | -                | -         |    -0.32 | ben1337, chop, cxzi, Walco, WolfY    |
|           18 |     5787 | 2024-02-22 | NRG               | W   | 0.553      | -            | -                | -                | -         |     7.03 | ben1337, chop, cxzi, Walco, WolfY    |
|           17 |     5793 | 2024-02-22 | One More Esports  | W   | 0.552      | -            | -                | -                | -         |     4.93 | ben1337, chop, cxzi, Walco, WolfY    |
|           16 |     5841 | 2024-02-21 | LAG Gaming        | W   | 0.546      | -            | -                | -                | -         |     8.58 | ben1337, chop, cxzi, Walco, WolfY    |
|           15 |     5909 | 2024-02-20 | NRG               | W   | 0.540      | -            | -                | -                | -         |     7.25 | ben1337, chop, cxzi, Walco, WolfY    |
|           14 |     5911 | 2024-02-20 | Mythic            | W   | 0.539      | -            | -                | -                | -         |     5.67 | ben1337, chop, cxzi, Walco, WolfY    |
|           13 |     5975 | 2024-02-19 | NRG               | L   | 0.533      | -            | -                | -                | -         |    -9.74 | ben1337, chop, cxzi, Walco, WolfY    |
|           12 |     5984 | 2024-02-19 | G3                | W   | 0.532      | -            | -                | -                | -         |     6.11 | ben1337, chop, cxzi, Walco, WolfY    |
|           11 |     6781 | 2024-02-02 | NRG               | L   | 0.420      | -            | -                | -                | -         |    -7.88 | ben1337, chop, cxzi, viz, WolfY      |
|           10 |     6783 | 2024-02-02 | Carpe Diem        | W   | 0.419      | -            | -                | -                | -         |     2.22 | ben1337, chop, cxzi, viz, WolfY      |
|            9 |     6787 | 2024-02-02 | NRG               | L   | 0.419      | -            | -                | -                | -         |    -8.01 | ben1337, chop, cxzi, viz, WolfY      |
|            8 |     7751 | 2024-01-17 | MIGHT             | L   | 0.313      | -            | -                | -                | -         |    -7.92 | ben1337, chop, cxzi, viz, WolfY      |
|            7 |     7864 | 2024-01-16 | Elevate           | L   | 0.306      | -            | -                | -                | -         |    -5.95 | ben1337, chop, cxzi, viz, WolfY      |
|            6 |     7945 | 2024-01-15 | Zomblers          | W   | 0.299      | -            | -                | -                | -         |     1.52 | ben1337, chop, cxzi, viz, WolfY      |
|            5 |     7991 | 2024-01-14 | Elevate           | L   | 0.293      | -            | -                | -                | -         |    -5.88 | ben1337, chop, cxzi, viz, WolfY      |
|            4 |     7996 | 2024-01-14 | Team Liquid       | L   | 0.293      | -            | -                | -                | -         |    -0.17 | ben1337, chop, cxzi, viz, WolfY      |
|            3 |     8016 | 2024-01-13 | Complexity Gaming | L   | 0.286      | -            | -                | -                | -         |    -0.28 | ben1337, chop, cxzi, viz, WolfY      |
|            2 |     8068 | 2024-01-12 | Carpe Diem        | W   | 0.281      | -            | -                | -                | -         |     1.36 | ben1337, chop, cxzi, viz, WolfY      |
|            1 |     8070 | 2024-01-12 | Akimbo Esports    | W   | 0.280      | -            | -                | -                | -         |     2.44 | ben1337, chop, cxzi, viz, WolfY      |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($9,214.31)
- Divide that value by the 5th highest value among all rosters ($300,806.11)
- The final value (0.03) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-05-21 |      1.000 | $6,250.00      | $6,250.00       |
| 2024-04-28 |      0.988 | $3,000.00      | $2,964.31       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
