### Roster Details<br />
Team Name: Mythic<br />
Roster: Cooper, fl0m, freakazoid, hate, Trucklover86<br />
Region: [Americas]( ../standings_americas.md)<br />
<br />
Global Rank: [136](../standings_global.md)<br />
Regional Rank: [27]( ../standings_americas.md)<br />
Final Rank Value:  799.4<br />
<br />
Final Rank Value (799.4) = Starting Rank Value (759.5) + Head To Head Adjustments (39.9)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.227[<sup>1</sup>](#table2)
- Bounty Collected: 0.330[<sup>2</sup>](#table1)
- Opponent Network: 0.149[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.177<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 759.5
- 400 + ( ( 0.177 - 0.000 ) / ( 0.786 - 0.000 ) ) * 1600 = 759.5


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent          | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                           |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           49 |      445 | 2024-05-22 | M80               | L   | 1.000      | -            | -                | -                | -         |    -1.77 | Cooper, fl0m, freakazoid, hate, Trucklover86     |
|           48 |      638 | 2024-05-20 | Elevate           | W   | 1.000      | 0.384        | 0.012 (0.005)    | 0.475 (0.183)    | 0 (0.000) |    21.96 | Cooper, fl0m, freakazoid, hate, Trucklover86     |
|           47 |     1115 | 2024-05-15 | Take Flyte        | W   | 1.000      | 0.477        | 0.006 (0.003)    | 0.354 (0.169)    | 0 (0.000) |    16.78 | Cooper, fl0m, freakazoid, hate, Trucklover86     |
|           46 |     1121 | 2024-05-15 | Take Flyte        | L   | 1.000      | -            | -                | -                | -         |   -14.62 | Cooper, fl0m, freakazoid, hate, Trucklover86     |
|           45 |     1214 | 2024-05-14 | Party Astronauts  | L   | 1.000      | -            | -                | -                | -         |    -9.89 | Cooper, fl0m, freakazoid, hate, Trucklover86     |
|           44 |     1220 | 2024-05-14 | Party Astronauts  | W   | 1.000      | 0.477        | 0.031 (0.015)    | 0.545 (0.260)    | 0 (0.000) |    22.08 | Cooper, fl0m, freakazoid, hate, Trucklover86     |
|           43 |     1344 | 2024-05-12 | Take Flyte        | L   | 1.000      | -            | -                | -                | -         |   -14.03 | Cooper, fl0m, freakazoid, hate, Trucklover86     |
|           42 |     1399 | 2024-05-11 | Nouns Esports     | W   | 1.000      | 0.270        | 0.071 (0.019)    | 0.507 (0.137)    | 0 (0.000) |    24.82 | Cooper, fl0m, freakazoid, hate, Trucklover86     |
|           41 |     1401 | 2024-05-11 | Wildcard Gaming   | W   | 1.000      | 0.270        | 0.012 (0.003)    | 0.506 (0.137)    | 0 (0.000) |    23.48 | Cooper, fl0m, freakazoid, hate, Trucklover86     |
|           40 |     2335 | 2024-04-24 | BOSS              | W   | 0.966      | 0.477        | 0.016 (0.007)    | 0.315 (0.145)    | 0 (0.000) |    22.07 | Cooper, fl0m, freakazoid, hate, Trucklover86     |
|           39 |     2336 | 2024-04-24 | BOSS              | L   | 0.966      | -            | -                | -                | -         |    -7.93 | Cooper, fl0m, freakazoid, hate, Trucklover86     |
|           38 |     2934 | 2024-04-15 | NRG               | L   | 0.906      | -            | -                | -                | -         |    -7.39 | Cooper, fl0m, freakazoid, hate, Trucklover86     |
|           37 |     2935 | 2024-04-15 | NRG               | L   | 0.906      | -            | -                | -                | -         |    -7.87 | Cooper, fl0m, freakazoid, hate, Trucklover86     |
|           36 |     3095 | 2024-04-11 | Carpe Diem        | L   | 0.879      | -            | -                | -                | -         |   -18.18 | Cooper, fl0m, freakazoid, hate, Trucklover86     |
|           35 |     3098 | 2024-04-11 | Carpe Diem        | W   | 0.879      | 0.477        | -                | 0.243 (0.102)    | 0 (0.000) |     9.33 | Cooper, fl0m, freakazoid, hate, Trucklover86     |
|           34 |     3140 | 2024-04-10 | LAG Gaming        | L   | 0.873      | -            | -                | -                | -         |    -8.07 | Cooper, fl0m, freakazoid, hate, Trucklover86     |
|           33 |     3145 | 2024-04-10 | LAG Gaming        | L   | 0.873      | -            | -                | -                | -         |    -8.61 | Cooper, fl0m, freakazoid, hate, Trucklover86     |
|           32 |     3766 | 2024-03-27 | Wildcard Gaming   | L   | 0.779      | -            | -                | -                | -         |    -6.96 | Cooper, fl0m, freakazoid, hate, Trucklover86     |
|           31 |     3772 | 2024-03-27 | Wildcard Gaming   | L   | 0.779      | -            | -                | -                | -         |    -7.37 | Cooper, fl0m, freakazoid, hate, Trucklover86     |
|           30 |     3838 | 2024-03-26 | Limitless         | W   | 0.773      | -            | -                | -                | 0 (0.000) |     9.58 | Cooper, fl0m, freakazoid, hate, Trucklover86     |
|           29 |     3843 | 2024-03-26 | Limitless         | L   | 0.773      | -            | -                | -                | -         |   -15.14 | Cooper, fl0m, freakazoid, hate, Trucklover86     |
|           28 |     4107 | 2024-03-20 | Nouns Esports     | W   | 0.733      | 0.477        | 0.071 (0.025)    | 0.507 (0.177)    | 0 (0.000) |    16.71 | Cooper, fl0m, freakazoid, hate, Trucklover86     |
|           27 |     4113 | 2024-03-20 | Nouns Esports     | L   | 0.733      | -            | -                | -                | -         |    -6.27 | Cooper, fl0m, freakazoid, hate, Trucklover86     |
|           26 |     4400 | 2024-03-14 | One More Esports  | W   | 0.693      | -            | -                | -                | 0 (0.000) |    10.23 | Cooper, fl0m, freakazoid, hate, Trucklover86     |
|           25 |     4402 | 2024-03-14 | One More Esports  | W   | 0.693      | -            | -                | -                | -         |    10.88 | Cooper, fl0m, freakazoid, hate, Trucklover86     |
|           24 |     4461 | 2024-03-13 | Take Flyte        | L   | 0.685      | -            | -                | -                | -         |   -10.18 | Cooper, fl0m, freakazoid, hate, Trucklover86     |
|           23 |     4530 | 2024-03-12 | Wildcard Gaming   | W   | 0.679      | -            | -                | -                | -         |    15.70 | Cooper, fl0m, freakazoid, hate, Trucklover86     |
|           22 |     4536 | 2024-03-12 | Bad News Bears    | W   | 0.679      | -            | -                | -                | -         |     2.78 | Cooper, fl0m, freakazoid, hate, Trucklover86     |
|           21 |     4919 | 2024-03-05 | MIGHT             | L   | 0.633      | -            | -                | -                | -         |   -11.10 | Cooper, fl0m, freakazoid, hate, Trucklover86     |
|           20 |     4927 | 2024-03-05 | MIGHT             | L   | 0.633      | -            | -                | -                | -         |   -11.72 | Cooper, fl0m, freakazoid, hate, Trucklover86     |
|           19 |     5483 | 2024-02-24 | NRG               | L   | 0.566      | -            | -                | -                | -         |    -6.44 | Cooper, fl0m, freakazoid, hate, Trucklover86     |
|           18 |     5579 | 2024-02-23 | Timbermen Black   | W   | 0.560      | -            | -                | -                | -         |     2.02 | Cooper, fl0m, freakazoid, hate, Trucklover86     |
|           17 |     5677 | 2024-02-21 | ex-CatEvil        | L   | 0.546      | -            | -                | -                | -         |   -12.23 | Cooper, fl0m, freakazoid, hate, Trucklover86     |
|           16 |     5744 | 2024-02-20 | Party Astronauts  | L   | 0.539      | -            | -                | -                | -         |    -5.54 | Cooper, fl0m, freakazoid, hate, Trucklover86     |
|           15 |     5804 | 2024-02-19 | G3                | W   | 0.533      | -            | -                | -                | -         |     8.34 | Cooper, fl0m, freakazoid, hate, Trucklover86     |
|           14 |     5815 | 2024-02-19 | NRG               | L   | 0.532      | -            | -                | -                | -         |    -6.70 | Cooper, fl0m, freakazoid, hate, Trucklover86     |
|           13 |     5965 | 2024-02-16 | FLUFFY AIMERS     | W   | 0.513      | 0.143        | 0.030 (0.002)    | -                | -         |    11.49 | Cooper, fl0m, freakazoid, hate, Trucklover86     |
|           12 |     5969 | 2024-02-16 | E-Xolos LAZER     | W   | 0.512      | -            | -                | -                | -         |     1.92 | Cooper, fl0m, freakazoid, hate, Trucklover86     |
|           11 |     6014 | 2024-02-15 | Pryde             | W   | 0.506      | -            | -                | -                | -         |     2.70 | Cooper, fl0m, freakazoid, hate, Trucklover86     |
|           10 |     6072 | 2024-02-14 | FLUFFY AIMERS     | W   | 0.500      | 0.477        | 0.030 (0.007)    | 0.384 (0.091)    | -         |    11.50 | Cooper, fl0m, freakazoid, hate, Trucklover86     |
|            9 |     6073 | 2024-02-14 | FLUFFY AIMERS     | W   | 0.500      | 0.477        | 0.030 (0.007)    | 0.384 (0.091)    | -         |    11.89 | Cooper, fl0m, freakazoid, hate, Trucklover86     |
|            8 |     7101 | 2024-01-24 | NRG               | L   | 0.359      | -            | -                | -                | -         |    -4.14 | Cooper, fl0m, freakazoid, hate, Trucklover86     |
|            7 |     7158 | 2024-01-23 | Team Lampa        | W   | 0.353      | -            | -                | -                | -         |     2.20 | Cooper, fl0m, freakazoid, hate, Trucklover86     |
|            6 |     7165 | 2024-01-23 | Snakes Den Gaming | W   | 0.353      | -            | -                | -                | -         |     2.60 | Cooper, fl0m, freakazoid, hate, Trucklover86     |
|            5 |     7503 | 2024-01-17 | Wildcard Gaming   | L   | 0.313      | -            | -                | -                | -         |    -3.02 | Cooper, fl0m, freakazoid, hate, Trucklover86     |
|            4 |     7697 | 2024-01-15 | Elevate           | L   | 0.299      | -            | -                | -                | -         |    -3.38 | Cooper, fl0m, freakazoid, hate, Trucklover86     |
|            3 |     7964 | 2024-01-10 | FN Esports        | L   | 0.267      | -            | -                | -                | -         |    -5.78 | Cooper, fl0m, freakazoid, hate, Trucklover86     |
|            2 |     8152 | 2024-01-08 | vagrants          | L   | 0.254      | -            | -                | -                | -         |    -6.49 | Cooper, fl0m, freakazoid, hate, trucklover86     |
|            1 |     9257 | 2023-12-05 | Elevate           | L   | 0.026      | -            | -                | -                | -         |    -0.31 | Cooper, fl0m, freakazoid, Stewie2K, Trucklover86 |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($118.89)
- Divide that value by the 5th highest value among all rosters ($300,806.11)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
