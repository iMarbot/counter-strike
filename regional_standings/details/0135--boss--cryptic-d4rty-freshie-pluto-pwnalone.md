### Roster Details<br />
Team Name: BOSS<br />
Roster: Cryptic, d4rty, freshie, Pluto, PwnAlone<br />
Region: [Americas]( ../standings_americas.md)<br />
<br />
Global Rank: [135](../standings_global.md)<br />
Regional Rank: [26]( ../standings_americas.md)<br />
Final Rank Value:  808.5<br />
<br />
Final Rank Value (808.5) = Starting Rank Value (854.0) + Head To Head Adjustments (-45.5)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.356[<sup>1</sup>](#table2)
- Bounty Collected: 0.323[<sup>2</sup>](#table1)
- Opponent Network: 0.150[<sup>2</sup>](#table1)
- LAN Wins: 0.065[<sup>2</sup>](#table1)

The average of these factors is 0.223<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 854.0
- 400 + ( ( 0.223 - 0.000 ) / ( 0.787 - 0.000 ) ) * 1600 = 854.0


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
|           61 |      431 | 2024-05-22 | Take Flyte        | W   | 1.000      | 0.477        | 0.006 (0.003)    | 0.354 (0.169)    | 0 (0.000) |    15.22 | Cryptic, d4rty, freshie, Pluto, PwnAlone |
|           60 |      436 | 2024-05-22 | Take Flyte        | L   | 1.000      | -            | -                | -                | -         |   -16.33 | Cryptic, d4rty, freshie, Pluto, PwnAlone |
|           59 |      641 | 2024-05-20 | Carpe Diem        | L   | 1.000      | -            | -                | -                | -         |   -19.49 | Cryptic, d4rty, freshie, Pluto, PwnAlone |
|           58 |      646 | 2024-05-20 | Carpe Diem        | W   | 1.000      | 0.477        | -                | 0.243 (0.116)    | 0 (0.000) |    11.69 | Cryptic, d4rty, freshie, Pluto, PwnAlone |
|           57 |      735 | 2024-05-19 | M80               | L   | 1.000      | -            | -                | -                | -         |    -2.16 | Cryptic, d4rty, freshie, Pluto, PwnAlone |
|           56 |      736 | 2024-05-19 | M80               | L   | 1.000      | -            | -                | -                | -         |    -2.21 | Cryptic, d4rty, freshie, Pluto, PwnAlone |
|           55 |      956 | 2024-05-17 | NRG               | L   | 1.000      | -            | -                | -                | -         |    -8.82 | Cryptic, d4rty, FaNg, freshie, PwnAlone  |
|           54 |     1122 | 2024-05-15 | Wildcard Gaming   | L   | 1.000      | -            | -                | -                | -         |   -10.50 | brett, Cryptic, d4rty, freshie, PwnAlone |
|           53 |     1128 | 2024-05-15 | Wildcard Gaming   | L   | 1.000      | -            | -                | -                | -         |   -11.38 | brett, Cryptic, d4rty, freshie, PwnAlone |
|           52 |     1228 | 2024-05-14 | MIGHT             | W   | 1.000      | 0.477        | -                | 0.207 (0.099)    | 0 (0.000) |     7.20 | brett, Cryptic, d4rty, freshie, PwnAlone |
|           51 |     1235 | 2024-05-14 | MIGHT             | W   | 1.000      | -            | -                | -                | 0 (0.000) |     7.67 | brett, Cryptic, d4rty, freshie, PwnAlone |
|           50 |     1416 | 2024-05-11 | Take Flyte        | L   | 1.000      | -            | -                | -                | -         |   -18.32 | Cryptic, d4rty, FaNg, freshie, PwnAlone  |
|           49 |     1420 | 2024-05-11 | Party Astronauts  | W   | 1.000      | 0.270        | 0.031 (0.008)    | 0.545 (0.147)    | 0 (0.000) |    20.18 | Cryptic, d4rty, FaNg, freshie, PwnAlone  |
|           48 |     1424 | 2024-05-11 | NRG               | L   | 1.000      | -            | -                | -                | -         |   -12.60 | Cryptic, d4rty, FaNg, freshie, PwnAlone  |
|           47 |     1553 | 2024-05-09 | Nouns Esports     | L   | 1.000      | -            | -                | -                | -         |    -9.82 | brett, Cryptic, d4rty, freshie, PwnAlone |
|           46 |     1556 | 2024-05-09 | Nouns Esports     | L   | 1.000      | -            | -                | -                | -         |   -10.61 | brett, Cryptic, d4rty, freshie, PwnAlone |
|           45 |     1898 | 2024-05-03 | Ninjas in Pyjamas | L   | 1.000      | -            | -                | -                | -         |    -7.71 | Cryptic, d4rty, FaNg, freshie, PwnAlone  |
|           44 |     1958 | 2024-05-02 | FlyQuest          | L   | 1.000      | -            | -                | -                | -         |    -1.26 | Cryptic, d4rty, FaNg, freshie, PwnAlone  |
|           43 |     2026 | 2024-05-01 | BIG               | L   | 1.000      | -            | -                | -                | -         |    -2.28 | Cryptic, d4rty, FaNg, freshie, PwnAlone  |
|           42 |     2376 | 2024-04-24 | Mythic            | L   | 0.966      | -            | -                | -                | -         |   -21.91 | brett, Cryptic, d4rty, freshie, PwnAlone |
|           41 |     2377 | 2024-04-24 | Mythic            | W   | 0.966      | 0.477        | -                | 0.339 (0.156)    | 0 (0.000) |     8.10 | brett, Cryptic, d4rty, freshie, PwnAlone |
|           40 |     3160 | 2024-04-11 | Limitless         | W   | 0.879      | -            | -                | -                | 0 (0.000) |     6.47 | brett, Cryptic, d4rty, freshie, PwnAlone |
|           39 |     3163 | 2024-04-11 | Limitless         | W   | 0.879      | -            | -                | -                | 0 (0.000) |     6.85 | brett, Cryptic, d4rty, freshie, PwnAlone |
|           38 |     3207 | 2024-04-10 | NRG               | L   | 0.873      | -            | -                | -                | -         |   -13.71 | brett, Cryptic, d4rty, freshie, PwnAlone |
|           37 |     3212 | 2024-04-10 | NRG               | W   | 0.873      | 0.477        | 0.010 (0.004)    | 0.555 (0.231)    | -         |    13.92 | brett, Cryptic, d4rty, freshie, PwnAlone |
|           36 |     3292 | 2024-04-09 | LAG Gaming        | W   | 0.866      | 0.477        | 0.013 (0.006)    | 0.335 (0.139)    | -         |    14.65 | brett, Cryptic, d4rty, freshie, PwnAlone |
|           35 |     3296 | 2024-04-09 | LAG Gaming        | W   | 0.866      | 0.477        | 0.013 (0.006)    | 0.335 (0.138)    | -         |    15.80 | brett, Cryptic, d4rty, freshie, PwnAlone |
|           34 |     3553 | 2024-04-04 | FLUFFY AIMERS     | W   | 0.833      | 0.477        | 0.030 (0.012)    | 0.384 (0.152)    | -         |    14.34 | brett, Cryptic, d4rty, freshie, PwnAlone |
|           33 |     3555 | 2024-04-04 | FLUFFY AIMERS     | W   | 0.832      | 0.477        | 0.030 (0.012)    | 0.384 (0.152)    | -         |    15.42 | brett, Cryptic, d4rty, freshie, PwnAlone |
|           32 |     3620 | 2024-04-03 | Party Astronauts  | L   | 0.825      | -            | -                | -                | -         |    -8.21 | Cryptic, d4rty, FaNg, freshie, PwnAlone  |
|           31 |     3671 | 2024-04-02 | Nouns Esports     | L   | 0.819      | -            | -                | -                | -         |    -8.34 | Cryptic, d4rty, FaNg, freshie, PwnAlone  |
|           30 |     3674 | 2024-04-02 | Take Flyte        | W   | 0.818      | -            | -                | -                | -         |    10.34 | Cryptic, d4rty, FaNg, freshie, PwnAlone  |
|           29 |     3851 | 2024-03-27 | One More Esports  | W   | 0.780      | 0.477        | 0.005 (0.002)    | -                | -         |     9.64 | brett, Cryptic, d4rty, freshie, PwnAlone |
|           28 |     3855 | 2024-03-27 | One More Esports  | L   | 0.780      | -            | -                | -                | -         |   -15.29 | brett, Cryptic, d4rty, freshie, PwnAlone |
|           27 |     3932 | 2024-03-26 | Elevate           | L   | 0.773      | -            | -                | -                | -         |   -10.85 | brett, Cryptic, d4rty, freshie, PwnAlone |
|           26 |     3937 | 2024-03-26 | Elevate           | L   | 0.773      | -            | -                | -                | -         |   -11.62 | brett, Cryptic, d4rty, freshie, PwnAlone |
|           25 |     4206 | 2024-03-20 | Party Astronauts  | L   | 0.733      | -            | -                | -                | -         |    -7.78 | brett, Cryptic, d4rty, freshie, PwnAlone |
|           24 |     4208 | 2024-03-20 | Party Astronauts  | L   | 0.733      | -            | -                | -                | -         |    -8.25 | brett, Cryptic, d4rty, freshie, PwnAlone |
|           23 |     5237 | 2024-03-03 | Team Liquid       | L   | 0.617      | -            | -                | -                | -         |    -0.28 | brett, Cryptic, d4rty, freshie, PwnAlone |
|           22 |     5332 | 2024-03-02 | Complexity Gaming | L   | 0.610      | -            | -                | -                | -         |    -0.44 | brett, Cryptic, d4rty, freshie, PwnAlone |
|           21 |     5370 | 2024-03-01 | MIBR              | W   | 0.605      | 0.143        | 0.307 (0.027)    | -                | 1 (0.605) |    18.71 | brett, Cryptic, d4rty, freshie, PwnAlone |
|           20 |     5549 | 2024-02-26 | Team Liquid       | L   | 0.579      | -            | -                | -                | -         |    -0.22 | brett, Cryptic, d4rty, freshie, PwnAlone |
|           19 |     5591 | 2024-02-25 | Nouns Esports     | L   | 0.573      | -            | -                | -                | -         |    -6.94 | brett, Cryptic, d4rty, freshie, PwnAlone |
|           18 |     5594 | 2024-02-25 | Wildcard Gaming   | W   | 0.572      | 0.143        | 0.012 (0.001)    | -                | -         |    11.14 | brett, Cryptic, d4rty, freshie, PwnAlone |
|           17 |     6850 | 2024-02-01 | Nouns Esports     | L   | 0.413      | -            | -                | -                | -         |    -5.21 | brett, Cryptic, d4rty, freshie, PwnAlone |
|           16 |     6852 | 2024-02-01 | Rocket            | W   | 0.413      | -            | -                | -                | -         |     2.63 | brett, Cryptic, d4rty, freshie, PwnAlone |
|           15 |     6857 | 2024-02-01 | Elevate           | L   | 0.412      | -            | -                | -                | -         |    -6.40 | brett, Cryptic, d4rty, freshie, PwnAlone |
|           14 |     7623 | 2024-01-19 | M80               | L   | 0.327      | -            | -                | -                | -         |    -0.96 | brett, Cryptic, cynic, d4rty, freshie    |
|           13 |     7635 | 2024-01-19 | Team Liquid       | L   | 0.325      | -            | -                | -                | -         |    -0.11 | brett, Cryptic, cynic, d4rty, freshie    |
|           12 |     7995 | 2024-01-14 | Rocket            | W   | 0.293      | -            | -                | -                | -         |     1.51 | brett, Cryptic, cynic, d4rty, freshie    |
|           11 |     8021 | 2024-01-13 | Akimbo Esports    | W   | 0.286      | -            | -                | -                | -         |     3.47 | brett, Cryptic, cynic, d4rty, freshie    |
|           10 |     8067 | 2024-01-12 | Wildcard Gaming   | L   | 0.281      | -            | -                | -                | -         |    -4.21 | brett, Cryptic, cynic, d4rty, freshie    |
|            9 |     8069 | 2024-01-12 | For Fun           | W   | 0.280      | -            | -                | -                | -         |     3.38 | brett, Cryptic, cynic, d4rty, freshie    |
|            8 |     9122 | 2023-12-12 | M80               | L   | 0.073      | -            | -                | -                | -         |    -0.20 | brett, Cryptic, d4rty, freshie, WolfY    |
|            7 |     9160 | 2023-12-11 | Party Astronauts  | W   | 0.067      | -            | -                | -                | -         |     0.46 | brett, Cryptic, d4rty, freshie, WolfY    |
|            6 |     9215 | 2023-12-10 | M80               | L   | 0.059      | -            | -                | -                | -         |    -0.16 | brett, Cryptic, d4rty, freshie, WolfY    |
|            5 |     9272 | 2023-12-09 | Party Astronauts  | W   | 0.053      | -            | -                | -                | -         |     0.36 | brett, Cryptic, d4rty, freshie, WolfY    |
|            4 |     9407 | 2023-12-07 | M80               | L   | 0.039      | -            | -                | -                | -         |    -0.11 | brett, Cryptic, d4rty, freshie, WolfY    |
|            3 |     9476 | 2023-12-06 | Nouns Esports     | W   | 0.033      | -            | -                | -                | -         |     0.23 | brett, Cryptic, d4rty, freshie, WolfY    |
|            2 |     9639 | 2023-12-03 | Elevate           | L   | 0.011      | -            | -                | -                | -         |    -0.17 | brett, Cryptic, d4rty, dea, freshie      |
|            1 |     9706 | 2023-12-02 | Supernova         | W   | 0.006      | -            | -                | -                | 1 (0.006) |     0.01 | brett, Cryptic, d4rty, dea, freshie      |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($4,701.81)
- Divide that value by the 5th highest value among all rosters ($300,806.11)
- The final value (0.02) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-05-12 |      1.000 | $3,500.00      | $3,500.00       |
| 2023-12-10 |      0.059 | $20,000.00     | $1,188.89       |
| 2023-12-03 |      0.013 | $1,000.00      | $12.92          |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
