### Roster Details<br />
Team Name: Mythic<br />
Roster: Cooper, fl0m, freakazoid, hate, Trucklover86<br />
Region: [Americas]( ../standings_americas.md)<br />
<br />
Global Rank: [138](../standings_global.md)<br />
Regional Rank: [27]( ../standings_americas.md)<br />
Final Rank Value:  801.7<br />
<br />
Final Rank Value (801.7) = Starting Rank Value (760.5) + Head To Head Adjustments (41.2)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.227[<sup>1</sup>](#table2)
- Bounty Collected: 0.330[<sup>2</sup>](#table1)
- Opponent Network: 0.152[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.177<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 760.5
- 400 + ( ( 0.177 - 0.000 ) / ( 0.787 - 0.000 ) ) * 1600 = 760.5


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
|           51 |      451 | 2024-05-22 | M80               | L   | 1.000      | -            | -                | -                | -         |    -1.87 | Cooper, fl0m, freakazoid, hate, Trucklover86     |
|           50 |      649 | 2024-05-20 | Elevate           | W   | 1.000      | 0.384        | 0.012 (0.005)    | 0.480 (0.185)    | 0 (0.000) |    21.86 | Cooper, fl0m, freakazoid, hate, Trucklover86     |
|           49 |     1125 | 2024-05-15 | Take Flyte        | W   | 1.000      | 0.477        | 0.006 (0.003)    | 0.354 (0.169)    | 0 (0.000) |    16.44 | Cooper, fl0m, freakazoid, hate, Trucklover86     |
|           48 |     1131 | 2024-05-15 | Take Flyte        | L   | 1.000      | -            | -                | -                | -         |   -15.00 | Cooper, fl0m, freakazoid, hate, Trucklover86     |
|           47 |     1224 | 2024-05-14 | Party Astronauts  | L   | 1.000      | -            | -                | -                | -         |   -10.01 | Cooper, fl0m, freakazoid, hate, Trucklover86     |
|           46 |     1230 | 2024-05-14 | Party Astronauts  | W   | 1.000      | 0.477        | 0.031 (0.015)    | 0.545 (0.260)    | 0 (0.000) |    21.96 | Cooper, fl0m, freakazoid, hate, Trucklover86     |
|           45 |     1356 | 2024-05-12 | Take Flyte        | L   | 1.000      | -            | -                | -                | -         |   -14.47 | Cooper, fl0m, freakazoid, hate, Trucklover86     |
|           44 |     1412 | 2024-05-11 | Nouns Esports     | W   | 1.000      | 0.270        | 0.071 (0.019)    | 0.507 (0.137)    | 0 (0.000) |    24.67 | Cooper, fl0m, freakazoid, hate, Trucklover86     |
|           43 |     1414 | 2024-05-11 | Wildcard Gaming   | W   | 1.000      | 0.270        | 0.012 (0.003)    | 0.525 (0.142)    | 0 (0.000) |    23.60 | Cooper, fl0m, freakazoid, hate, Trucklover86     |
|           42 |     2376 | 2024-04-24 | BOSS              | W   | 0.966      | 0.477        | 0.016 (0.007)    | 0.315 (0.145)    | 0 (0.000) |    21.91 | Cooper, fl0m, freakazoid, hate, Trucklover86     |
|           41 |     2377 | 2024-04-24 | BOSS              | L   | 0.966      | -            | -                | -                | -         |    -8.10 | Cooper, fl0m, freakazoid, hate, Trucklover86     |
|           40 |     2995 | 2024-04-15 | NRG               | L   | 0.906      | -            | -                | -                | -         |    -7.52 | Cooper, fl0m, freakazoid, hate, Trucklover86     |
|           39 |     2996 | 2024-04-15 | NRG               | L   | 0.906      | -            | -                | -                | -         |    -8.01 | Cooper, fl0m, freakazoid, hate, Trucklover86     |
|           38 |     3161 | 2024-04-11 | Carpe Diem        | L   | 0.879      | -            | -                | -                | -         |   -18.37 | Cooper, fl0m, freakazoid, hate, Trucklover86     |
|           37 |     3164 | 2024-04-11 | Carpe Diem        | W   | 0.879      | 0.477        | -                | 0.243 (0.102)    | 0 (0.000) |     9.13 | Cooper, fl0m, freakazoid, hate, Trucklover86     |
|           36 |     3211 | 2024-04-10 | LAG Gaming        | L   | 0.873      | -            | -                | -                | -         |    -8.21 | Cooper, fl0m, freakazoid, hate, Trucklover86     |
|           35 |     3216 | 2024-04-10 | LAG Gaming        | L   | 0.873      | -            | -                | -                | -         |    -8.77 | Cooper, fl0m, freakazoid, hate, Trucklover86     |
|           34 |     3859 | 2024-03-27 | Wildcard Gaming   | L   | 0.779      | -            | -                | -                | -         |    -6.77 | Cooper, fl0m, freakazoid, hate, Trucklover86     |
|           33 |     3865 | 2024-03-27 | Wildcard Gaming   | L   | 0.779      | -            | -                | -                | -         |    -7.16 | Cooper, fl0m, freakazoid, hate, Trucklover86     |
|           32 |     3935 | 2024-03-26 | Limitless         | W   | 0.773      | -            | -                | -                | 0 (0.000) |     9.43 | Cooper, fl0m, freakazoid, hate, Trucklover86     |
|           31 |     3940 | 2024-03-26 | Limitless         | L   | 0.773      | -            | -                | -                | -         |   -15.29 | Cooper, fl0m, freakazoid, hate, Trucklover86     |
|           30 |     4207 | 2024-03-20 | Nouns Esports     | W   | 0.733      | 0.477        | 0.071 (0.025)    | 0.507 (0.177)    | 0 (0.000) |    16.57 | Cooper, fl0m, freakazoid, hate, Trucklover86     |
|           29 |     4213 | 2024-03-20 | Nouns Esports     | L   | 0.733      | -            | -                | -                | -         |    -6.42 | Cooper, fl0m, freakazoid, hate, Trucklover86     |
|           28 |     4510 | 2024-03-14 | One More Esports  | W   | 0.693      | -            | -                | -                | 0 (0.000) |    10.06 | Cooper, fl0m, freakazoid, hate, Trucklover86     |
|           27 |     4512 | 2024-03-14 | One More Esports  | W   | 0.693      | -            | -                | -                | -         |    10.69 | Cooper, fl0m, freakazoid, hate, Trucklover86     |
|           26 |     4575 | 2024-03-13 | Take Flyte        | L   | 0.685      | -            | -                | -                | -         |   -10.32 | Cooper, fl0m, freakazoid, hate, Trucklover86     |
|           25 |     4649 | 2024-03-12 | Wildcard Gaming   | W   | 0.679      | -            | -                | -                | -         |    15.55 | Cooper, fl0m, freakazoid, hate, Trucklover86     |
|           24 |     4655 | 2024-03-12 | Bad News Bears    | W   | 0.679      | -            | -                | -                | -         |     2.70 | Cooper, fl0m, freakazoid, hate, Trucklover86     |
|           23 |     5058 | 2024-03-05 | MIGHT             | L   | 0.633      | -            | -                | -                | -         |   -11.27 | Cooper, fl0m, freakazoid, hate, Trucklover86     |
|           22 |     5066 | 2024-03-05 | MIGHT             | L   | 0.633      | -            | -                | -                | -         |   -11.90 | Cooper, fl0m, freakazoid, hate, Trucklover86     |
|           21 |     5642 | 2024-02-24 | NRG               | L   | 0.566      | -            | -                | -                | -         |    -6.59 | Cooper, fl0m, freakazoid, hate, Trucklover86     |
|           20 |     5739 | 2024-02-23 | Timbermen Black   | W   | 0.560      | -            | -                | -                | -         |     1.95 | Cooper, fl0m, freakazoid, hate, Trucklover86     |
|           19 |     5838 | 2024-02-21 | ex-CatEvil        | L   | 0.546      | -            | -                | -                | -         |   -12.38 | Cooper, fl0m, freakazoid, hate, Trucklover86     |
|           18 |     5911 | 2024-02-20 | Party Astronauts  | L   | 0.539      | -            | -                | -                | -         |    -5.67 | Cooper, fl0m, freakazoid, hate, Trucklover86     |
|           17 |     5974 | 2024-02-19 | G3                | W   | 0.533      | -            | -                | -                | -         |     9.00 | Cooper, fl0m, freakazoid, hate, Trucklover86     |
|           16 |     5985 | 2024-02-19 | NRG               | L   | 0.532      | -            | -                | -                | -         |    -6.85 | Cooper, fl0m, freakazoid, hate, Trucklover86     |
|           15 |     6138 | 2024-02-16 | FLUFFY AIMERS     | W   | 0.513      | -            | -                | -                | -         |    11.36 | Cooper, fl0m, freakazoid, hate, Trucklover86     |
|           14 |     6142 | 2024-02-16 | E-Xolos LAZER     | W   | 0.512      | -            | -                | -                | -         |     1.85 | Cooper, fl0m, freakazoid, hate, Trucklover86     |
|           13 |     6190 | 2024-02-15 | Pryde             | W   | 0.506      | -            | -                | -                | -         |     2.62 | Cooper, fl0m, freakazoid, hate, Trucklover86     |
|           12 |     6253 | 2024-02-14 | FLUFFY AIMERS     | W   | 0.500      | 0.477        | 0.030 (0.007)    | 0.384 (0.091)    | -         |    11.37 | Cooper, fl0m, freakazoid, hate, Trucklover86     |
|           11 |     6254 | 2024-02-14 | FLUFFY AIMERS     | W   | 0.500      | 0.477        | 0.030 (0.007)    | -                | -         |    11.76 | Cooper, fl0m, freakazoid, hate, Trucklover86     |
|           10 |     6316 | 2024-02-13 | Elevate           | W   | 0.493      | 0.477        | 0.012 (0.003)    | 0.480 (0.113)    | -         |    10.85 | Cooper, fl0m, freakazoid, hate, Trucklover86     |
|            9 |     6318 | 2024-02-13 | Elevate           | L   | 0.493      | -            | -                | -                | -         |    -4.72 | Cooper, fl0m, freakazoid, hate, Trucklover86     |
|            8 |     7330 | 2024-01-24 | NRG               | L   | 0.359      | -            | -                | -                | -         |    -4.16 | Cooper, fl0m, freakazoid, hate, Trucklover86     |
|            7 |     7393 | 2024-01-23 | Team Lampa        | W   | 0.353      | -            | -                | -                | -         |     2.19 | Cooper, fl0m, freakazoid, hate, Trucklover86     |
|            6 |     7400 | 2024-01-23 | Snakes Den Gaming | W   | 0.353      | -            | -                | -                | -         |     2.58 | Cooper, fl0m, freakazoid, hate, Trucklover86     |
|            5 |     7752 | 2024-01-17 | Wildcard Gaming   | L   | 0.313      | -            | -                | -                | -         |    -3.04 | Cooper, fl0m, freakazoid, hate, Trucklover86     |
|            4 |     7946 | 2024-01-15 | Elevate           | L   | 0.299      | -            | -                | -                | -         |    -3.40 | Cooper, fl0m, freakazoid, hate, Trucklover86     |
|            3 |     8217 | 2024-01-10 | FN Esports        | L   | 0.267      | -            | -                | -                | -         |    -5.79 | Cooper, fl0m, freakazoid, hate, Trucklover86     |
|            2 |     8406 | 2024-01-08 | vagrants          | L   | 0.254      | -            | -                | -                | -         |    -6.50 | Cooper, fl0m, freakazoid, hate, trucklover86     |
|            1 |     9538 | 2023-12-05 | Elevate           | L   | 0.026      | -            | -                | -                | -         |    -0.31 | Cooper, fl0m, freakazoid, Stewie2K, Trucklover86 |

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
