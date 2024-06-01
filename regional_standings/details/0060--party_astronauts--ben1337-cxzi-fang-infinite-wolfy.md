### Roster Details<br />
Team Name: Party Astronauts<br />
Roster: ben1337, cxzi, FaNg, Infinite, WolfY<br />
Region: [Americas]( ../standings_americas.md)<br />
<br />
Global Rank: [60](../standings_global.md)<br />
Regional Rank: [14]( ../standings_americas.md)<br />
Final Rank Value:  999.4<br />
<br />
Final Rank Value (999.4) = Starting Rank Value (941.8) + Head To Head Adjustments (57.7)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.398[<sup>1</sup>](#table2)
- Bounty Collected: 0.361[<sup>2</sup>](#table1)
- Opponent Network: 0.203[<sup>2</sup>](#table1)
- LAN Wins: 0.104[<sup>2</sup>](#table1)

The average of these factors is 0.266<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 941.8
- 400 + ( ( 0.266 - 0.000 ) / ( 0.786 - 0.000 ) ) * 1600 = 941.8


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
|           72 |      422 | 2024-05-22 | Nouns Esports     | L   | 1.000      | -            | -                | -                | -         |   -15.02 | ben1337, cxzi, FaNg, Infinite, WolfY |
|           71 |      433 | 2024-05-22 | M80               | W   | 1.000      | 0.477        | 0.136 (0.065)    | 0.525 (0.250)    | 0 (0.000) |    26.47 | ben1337, cxzi, FaNg, Infinite, WolfY |
|           70 |      435 | 2024-05-22 | M80               | L   | 1.000      | -            | -                | -                | -         |    -4.56 | ben1337, cxzi, FaNg, Infinite, WolfY |
|           69 |      528 | 2024-05-21 | Limitless         | W   | 1.000      | -            | -                | -                | 0 (0.000) |     4.00 | ben1337, cxzi, FaNg, Infinite, WolfY |
|           68 |      530 | 2024-05-21 | Limitless         | W   | 1.000      | -            | -                | -                | 0 (0.000) |     4.16 | ben1337, cxzi, FaNg, Infinite, WolfY |
|           67 |      535 | 2024-05-21 | Nouns Esports     | L   | 1.000      | -            | -                | -                | -         |   -15.74 | ben1337, cxzi, FaNg, Infinite, WolfY |
|           66 |      539 | 2024-05-21 | FLUFFY AIMERS     | W   | 1.000      | 0.384        | 0.030 (0.012)    | -                | 0 (0.000) |     8.22 | ben1337, cxzi, FaNg, Infinite, WolfY |
|           65 |      545 | 2024-05-21 | The Krubby Krabs  | W   | 1.000      | -            | -                | -                | 0 (0.000) |     2.46 | ben1337, cxzi, FaNg, Infinite, WolfY |
|           64 |      550 | 2024-05-21 | Nouns Esports     | W   | 1.000      | 0.384        | 0.071 (0.027)    | 0.507 (0.195)    | 0 (0.000) |    15.56 | ben1337, cxzi, FaNg, Infinite, WolfY |
|           63 |      566 | 2024-05-21 | TSM Shimmer       | W   | 1.000      | 0.384        | 0.017 (0.007)    | -                | 0 (0.000) |     8.20 | ben1337, cxzi, FaNg, Infinite, WolfY |
|           62 |      627 | 2024-05-20 | G3                | W   | 1.000      | -            | -                | -                | 0 (0.000) |     9.34 | ben1337, cxzi, FaNg, Infinite, WolfY |
|           61 |      842 | 2024-05-18 | NRG               | L   | 1.000      | -            | -                | -                | -         |   -13.91 | ben1337, chop, cxzi, Infinite, WolfY |
|           60 |      945 | 2024-05-17 | Legacy            | W   | 1.000      | 0.303        | 0.027 (0.008)    | -                | 0 (0.000) |    21.07 | ben1337, chop, cxzi, Infinite, WolfY |
|           59 |     1019 | 2024-05-16 | FLUFFY AIMERS     | W   | 1.000      | 0.477        | 0.030 (0.014)    | 0.384 (0.183)    | -         |    10.96 | ben1337, chop, cxzi, Infinite, WolfY |
|           58 |     1024 | 2024-05-16 | FLUFFY AIMERS     | W   | 1.000      | 0.477        | 0.030 (0.014)    | 0.384 (0.183)    | -         |    11.89 | ben1337, chop, cxzi, Infinite, WolfY |
|           57 |     1214 | 2024-05-14 | Mythic            | W   | 1.000      | 0.477        | -                | 0.339 (0.162)    | -         |     9.89 | ben1337, chop, cxzi, RUSH, WolfY     |
|           56 |     1220 | 2024-05-14 | Mythic            | L   | 1.000      | -            | -                | -                | -         |   -22.08 | ben1337, chop, cxzi, RUSH, WolfY     |
|           55 |     1407 | 2024-05-11 | BOSS              | L   | 1.000      | -            | -                | -                | -         |   -20.15 | ben1337, chop, cxzi, RUSH, WolfY     |
|           54 |     1410 | 2024-05-11 | Take Flyte        | L   | 1.000      | -            | -                | -                | -         |   -23.30 | ben1337, chop, cxzi, RUSH, WolfY     |
|           53 |     1585 | 2024-05-08 | LAG Gaming        | W   | 1.000      | 0.477        | 0.013 (0.006)    | 0.335 (0.160)    | -         |    11.91 | ben1337, chop, cxzi, RUSH, WolfY     |
|           52 |     1589 | 2024-05-08 | LAG Gaming        | W   | 1.000      | 0.477        | 0.013 (0.006)    | 0.335 (0.160)    | -         |    12.95 | ben1337, chop, cxzi, RUSH, WolfY     |
|           51 |     1658 | 2024-05-07 | Elevate           | L   | 1.000      | -            | -                | -                | -         |   -18.90 | ben1337, chop, cxzi, RUSH, WolfY     |
|           50 |     1659 | 2024-05-07 | Elevate           | W   | 1.000      | 0.477        | -                | 0.475 (0.226)    | -         |    12.33 | ben1337, chop, cxzi, RUSH, WolfY     |
|           49 |     1701 | 2024-05-06 | NRG               | L   | 1.000      | -            | -                | -                | -         |   -19.09 | ben1337, chop, cxzi, RUSH, WolfY     |
|           48 |     1702 | 2024-05-06 | NRG               | W   | 1.000      | 0.477        | -                | 0.555 (0.265)    | -         |    12.13 | ben1337, chop, cxzi, RUSH, WolfY     |
|           47 |     1900 | 2024-05-02 | Wildcard Gaming   | L   | 1.000      | -            | -                | -                | -         |   -18.64 | ben1337, chop, cxzi, RUSH, WolfY     |
|           46 |     1901 | 2024-05-02 | Wildcard Gaming   | W   | 1.000      | 0.477        | -                | 0.506 (0.241)    | -         |    12.61 | ben1337, chop, cxzi, RUSH, WolfY     |
|           45 |     2219 | 2024-04-26 | Aurora Gaming     | L   | 0.981      | -            | -                | -                | -         |    -2.68 | ben1337, chop, cxzi, RUSH, WolfY     |
|           44 |     2221 | 2024-04-26 | sunday school     | W   | 0.980      | -            | -                | -                | 1 (0.980) |     4.98 | ben1337, chop, cxzi, RUSH, WolfY     |
|           43 |     2293 | 2024-04-25 | Aurora Gaming     | L   | 0.973      | -            | -                | -                | -         |    -2.37 | ben1337, chop, cxzi, RUSH, WolfY     |
|           42 |     2889 | 2024-04-16 | G3                | L   | 0.912      | -            | -                | -                | -         |   -21.89 | ben1337, chop, cxzi, RUSH, WolfY     |
|           41 |     3215 | 2024-04-09 | One More Esports  | W   | 0.866      | -            | -                | -                | -         |     4.95 | ben1337, chop, cxzi, RUSH, WolfY     |
|           40 |     3219 | 2024-04-09 | One More Esports  | W   | 0.866      | -            | -                | -                | -         |     5.18 | ben1337, chop, cxzi, RUSH, WolfY     |
|           39 |     3462 | 2024-04-04 | MIGHT             | W   | 0.833      | -            | -                | -                | -         |     3.75 | ben1337, chop, cxzi, RUSH, WolfY     |
|           38 |     3466 | 2024-04-04 | MIGHT             | W   | 0.833      | -            | -                | -                | -         |     3.89 | ben1337, chop, cxzi, RUSH, WolfY     |
|           37 |     3521 | 2024-04-03 | Nouns Esports     | W   | 0.826      | 0.143        | 0.071 (0.008)    | -                | -         |    12.71 | ben1337, chop, cxzi, RUSH, WolfY     |
|           36 |     3533 | 2024-04-03 | BOSS              | W   | 0.825      | -            | -                | -                | -         |     8.23 | ben1337, chop, cxzi, RUSH, WolfY     |
|           35 |     3581 | 2024-04-02 | Take Flyte        | W   | 0.819      | -            | -                | -                | -         |     6.49 | ben1337, chop, cxzi, RUSH, WolfY     |
|           34 |     3586 | 2024-04-02 | Nouns Esports     | L   | 0.818      | -            | -                | -                | -         |   -13.14 | ben1337, chop, cxzi, RUSH, WolfY     |
|           33 |     3760 | 2024-03-27 | Carpe Diem        | W   | 0.780      | -            | -                | -                | -         |     3.73 | ben1337, chop, cxzi, RUSH, WolfY     |
|           32 |     3764 | 2024-03-27 | Carpe Diem        | W   | 0.780      | -            | -                | -                | -         |     3.87 | ben1337, chop, cxzi, RUSH, WolfY     |
|           31 |     3836 | 2024-03-26 | Nouns Esports     | L   | 0.773      | -            | -                | -                | -         |   -12.88 | ben1337, chop, cxzi, RUSH, WolfY     |
|           30 |     3841 | 2024-03-26 | Nouns Esports     | L   | 0.773      | -            | -                | -                | -         |   -13.78 | ben1337, chop, cxzi, RUSH, WolfY     |
|           29 |     4106 | 2024-03-20 | BOSS              | W   | 0.733      | -            | -                | -                | -         |     7.79 | ben1337, chop, cxzi, RUSH, WolfY     |
|           28 |     4108 | 2024-03-20 | BOSS              | W   | 0.733      | -            | -                | -                | -         |     8.26 | ben1337, chop, cxzi, RUSH, WolfY     |
|           27 |     4147 | 2024-03-19 | Take Flyte        | W   | 0.727      | -            | -                | -                | -         |     5.76 | ben1337, chop, cxzi, RUSH, WolfY     |
|           26 |     4148 | 2024-03-19 | Take Flyte        | W   | 0.726      | -            | -                | -                | -         |     6.05 | ben1337, chop, cxzi, RUSH, WolfY     |
|           25 |     4462 | 2024-03-13 | Carpe Diem        | W   | 0.685      | -            | -                | -                | -         |     3.74 | ben1337, chop, cxzi, RUSH, WolfY     |
|           24 |     4526 | 2024-03-12 | Elevate           | W   | 0.679      | -            | -                | -                | -         |     8.12 | ben1337, chop, cxzi, RUSH, WolfY     |
|           23 |     4534 | 2024-03-12 | LAG Gaming        | W   | 0.679      | -            | -                | -                | -         |     9.82 | ben1337, chop, cxzi, RUSH, WolfY     |
|           22 |     5478 | 2024-02-24 | Wildcard Gaming   | L   | 0.566      | -            | -                | -                | -         |    -9.31 | ben1337, chop, cxzi, Walco, WolfY    |
|           21 |     5485 | 2024-02-24 | ex-CatEvil        | W   | 0.566      | -            | -                | -                | -         |     2.56 | ben1337, chop, cxzi, Walco, WolfY    |
|           20 |     5580 | 2024-02-23 | E-Xolos LAZER     | W   | 0.560      | -            | -                | -                | -         |     0.84 | ben1337, chop, cxzi, Walco, WolfY    |
|           19 |     5625 | 2024-02-22 | Team Liquid       | L   | 0.553      | -            | -                | -                | -         |    -0.31 | ben1337, chop, cxzi, Walco, WolfY    |
|           18 |     5627 | 2024-02-22 | NRG               | W   | 0.553      | -            | -                | -                | -         |     7.04 | ben1337, chop, cxzi, Walco, WolfY    |
|           17 |     5633 | 2024-02-22 | One More Esports  | W   | 0.552      | -            | -                | -                | -         |     4.96 | ben1337, chop, cxzi, Walco, WolfY    |
|           16 |     5680 | 2024-02-21 | LAG Gaming        | W   | 0.546      | -            | -                | -                | -         |     8.61 | ben1337, chop, cxzi, Walco, WolfY    |
|           15 |     5742 | 2024-02-20 | NRG               | W   | 0.540      | -            | -                | -                | -         |     7.27 | ben1337, chop, cxzi, Walco, WolfY    |
|           14 |     5744 | 2024-02-20 | Mythic            | W   | 0.539      | -            | -                | -                | -         |     5.54 | ben1337, chop, cxzi, Walco, WolfY    |
|           13 |     5805 | 2024-02-19 | NRG               | L   | 0.533      | -            | -                | -                | -         |    -9.73 | ben1337, chop, cxzi, Walco, WolfY    |
|           12 |     5814 | 2024-02-19 | G3                | W   | 0.532      | -            | -                | -                | -         |     5.36 | ben1337, chop, cxzi, Walco, WolfY    |
|           11 |     6578 | 2024-02-02 | NRG               | L   | 0.420      | -            | -                | -                | -         |    -7.88 | ben1337, chop, cxzi, viz, WolfY      |
|           10 |     6580 | 2024-02-02 | Carpe Diem        | W   | 0.419      | -            | -                | -                | -         |     2.22 | ben1337, chop, cxzi, viz, WolfY      |
|            9 |     6584 | 2024-02-02 | NRG               | L   | 0.419      | -            | -                | -                | -         |    -8.01 | ben1337, chop, cxzi, viz, WolfY      |
|            8 |     7502 | 2024-01-17 | MIGHT             | L   | 0.313      | -            | -                | -                | -         |    -7.92 | ben1337, chop, cxzi, viz, WolfY      |
|            7 |     7615 | 2024-01-16 | Elevate           | L   | 0.306      | -            | -                | -                | -         |    -5.95 | ben1337, chop, cxzi, viz, WolfY      |
|            6 |     7696 | 2024-01-15 | Zomblers          | W   | 0.299      | -            | -                | -                | -         |     1.52 | ben1337, chop, cxzi, viz, WolfY      |
|            5 |     7738 | 2024-01-14 | Elevate           | L   | 0.293      | -            | -                | -                | -         |    -5.88 | ben1337, chop, cxzi, viz, WolfY      |
|            4 |     7743 | 2024-01-14 | Team Liquid       | L   | 0.293      | -            | -                | -                | -         |    -0.16 | ben1337, chop, cxzi, viz, WolfY      |
|            3 |     7763 | 2024-01-13 | Complexity Gaming | L   | 0.286      | -            | -                | -                | -         |    -0.28 | ben1337, chop, cxzi, viz, WolfY      |
|            2 |     7815 | 2024-01-12 | Carpe Diem        | W   | 0.281      | -            | -                | -                | -         |     1.36 | ben1337, chop, cxzi, viz, WolfY      |
|            1 |     7817 | 2024-01-12 | Akimbo Esports    | W   | 0.280      | -            | -                | -                | -         |     2.44 | ben1337, chop, cxzi, viz, WolfY      |

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
