### Roster Details<br />
Team Name: BOSS<br />
Roster: Cryptic, d4rty, freshie, Pluto, PwnAlone<br />
Region: [Americas]( ../standings_americas.md)<br />
<br />
Global Rank: [131](../standings_global.md)<br />
Regional Rank: [26]( ../standings_americas.md)<br />
Final Rank Value:  809.2<br />
<br />
Final Rank Value (809.2) = Starting Rank Value (854.7) + Head To Head Adjustments (-45.5)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.356[<sup>1</sup>](#table2)
- Bounty Collected: 0.323[<sup>2</sup>](#table1)
- Opponent Network: 0.150[<sup>2</sup>](#table1)
- LAN Wins: 0.065[<sup>2</sup>](#table1)

The average of these factors is 0.223<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 854.7
- 400 + ( ( 0.223 - 0.000 ) / ( 0.786 - 0.000 ) ) * 1600 = 854.7


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
|           61 |      423 | 2024-05-22 | Take Flyte        | W   | 1.000      | 0.477        | 0.006 (0.003)    | 0.354 (0.169)    | 0 (0.000) |    15.36 | Cryptic, d4rty, freshie, Pluto, PwnAlone |
|           60 |      428 | 2024-05-22 | Take Flyte        | L   | 1.000      | -            | -                | -                | -         |   -16.18 | Cryptic, d4rty, freshie, Pluto, PwnAlone |
|           59 |      630 | 2024-05-20 | Carpe Diem        | L   | 1.000      | -            | -                | -                | -         |   -19.49 | Cryptic, d4rty, freshie, Pluto, PwnAlone |
|           58 |      635 | 2024-05-20 | Carpe Diem        | W   | 1.000      | 0.477        | -                | 0.243 (0.116)    | 0 (0.000) |    11.70 | Cryptic, d4rty, freshie, Pluto, PwnAlone |
|           57 |      723 | 2024-05-19 | M80               | L   | 1.000      | -            | -                | -                | -         |    -2.07 | Cryptic, d4rty, freshie, Pluto, PwnAlone |
|           56 |      724 | 2024-05-19 | M80               | L   | 1.000      | -            | -                | -                | -         |    -2.12 | Cryptic, d4rty, freshie, Pluto, PwnAlone |
|           55 |      944 | 2024-05-17 | NRG               | L   | 1.000      | -            | -                | -                | -         |    -8.86 | Cryptic, d4rty, FaNg, freshie, PwnAlone  |
|           54 |     1112 | 2024-05-15 | Wildcard Gaming   | L   | 1.000      | -            | -                | -                | -         |   -10.74 | Cryptic, d4rty, FaNg, freshie, PwnAlone  |
|           53 |     1118 | 2024-05-15 | Wildcard Gaming   | L   | 1.000      | -            | -                | -                | -         |   -11.64 | Cryptic, d4rty, FaNg, freshie, PwnAlone  |
|           52 |     1218 | 2024-05-14 | MIGHT             | W   | 1.000      | 0.477        | -                | 0.207 (0.099)    | 0 (0.000) |     7.19 | Cryptic, d4rty, FaNg, freshie, PwnAlone  |
|           51 |     1225 | 2024-05-14 | MIGHT             | W   | 1.000      | -            | -                | -                | 0 (0.000) |     7.66 | Cryptic, d4rty, FaNg, freshie, PwnAlone  |
|           50 |     1403 | 2024-05-11 | Take Flyte        | L   | 1.000      | -            | -                | -                | -         |   -18.05 | Cryptic, d4rty, FaNg, freshie, PwnAlone  |
|           49 |     1407 | 2024-05-11 | Party Astronauts  | W   | 1.000      | 0.270        | 0.031 (0.008)    | 0.545 (0.147)    | 0 (0.000) |    20.15 | Cryptic, d4rty, FaNg, freshie, PwnAlone  |
|           48 |     1411 | 2024-05-11 | NRG               | L   | 1.000      | -            | -                | -                | -         |   -12.71 | Cryptic, d4rty, FaNg, freshie, PwnAlone  |
|           47 |     1538 | 2024-05-09 | Nouns Esports     | L   | 1.000      | -            | -                | -                | -         |    -9.80 | Cryptic, d4rty, FaNg, freshie, PwnAlone  |
|           46 |     1541 | 2024-05-09 | Nouns Esports     | L   | 1.000      | -            | -                | -                | -         |   -10.59 | Cryptic, d4rty, FaNg, freshie, PwnAlone  |
|           45 |     1874 | 2024-05-03 | Ninjas in Pyjamas | L   | 1.000      | -            | -                | -                | -         |    -7.73 | Cryptic, d4rty, FaNg, freshie, PwnAlone  |
|           44 |     1931 | 2024-05-02 | FlyQuest          | L   | 1.000      | -            | -                | -                | -         |    -1.31 | Cryptic, d4rty, FaNg, freshie, PwnAlone  |
|           43 |     1996 | 2024-05-01 | BIG               | L   | 1.000      | -            | -                | -                | -         |    -2.19 | Cryptic, d4rty, FaNg, freshie, PwnAlone  |
|           42 |     2335 | 2024-04-24 | Mythic            | L   | 0.966      | -            | -                | -                | -         |   -22.07 | Cryptic, d4rty, FaNg, freshie, PwnAlone  |
|           41 |     2336 | 2024-04-24 | Mythic            | W   | 0.966      | 0.477        | -                | 0.339 (0.156)    | 0 (0.000) |     7.93 | Cryptic, d4rty, FaNg, freshie, PwnAlone  |
|           40 |     3094 | 2024-04-11 | Limitless         | W   | 0.879      | -            | -                | -                | 0 (0.000) |     6.45 | Cryptic, d4rty, FaNg, freshie, PwnAlone  |
|           39 |     3097 | 2024-04-11 | Limitless         | W   | 0.879      | -            | -                | -                | 0 (0.000) |     6.83 | Cryptic, d4rty, FaNg, freshie, PwnAlone  |
|           38 |     3136 | 2024-04-10 | NRG               | L   | 0.873      | -            | -                | -                | -         |   -13.75 | Cryptic, d4rty, FaNg, freshie, PwnAlone  |
|           37 |     3141 | 2024-04-10 | NRG               | W   | 0.873      | 0.477        | 0.010 (0.004)    | 0.555 (0.231)    | -         |    13.88 | Cryptic, d4rty, FaNg, freshie, PwnAlone  |
|           36 |     3214 | 2024-04-09 | LAG Gaming        | W   | 0.866      | 0.477        | 0.013 (0.006)    | 0.335 (0.139)    | -         |    14.60 | Cryptic, d4rty, FaNg, freshie, PwnAlone  |
|           35 |     3218 | 2024-04-09 | LAG Gaming        | W   | 0.866      | 0.477        | 0.013 (0.006)    | 0.335 (0.138)    | -         |    15.74 | Cryptic, d4rty, FaNg, freshie, PwnAlone  |
|           34 |     3468 | 2024-04-04 | FLUFFY AIMERS     | W   | 0.833      | 0.477        | 0.030 (0.012)    | 0.384 (0.152)    | -         |    14.31 | Cryptic, d4rty, FaNg, freshie, PwnAlone  |
|           33 |     3470 | 2024-04-04 | FLUFFY AIMERS     | W   | 0.832      | 0.477        | 0.030 (0.012)    | 0.384 (0.152)    | -         |    15.39 | Cryptic, d4rty, FaNg, freshie, PwnAlone  |
|           32 |     3533 | 2024-04-03 | Party Astronauts  | L   | 0.825      | -            | -                | -                | -         |    -8.23 | Cryptic, d4rty, FaNg, freshie, PwnAlone  |
|           31 |     3582 | 2024-04-02 | Nouns Esports     | L   | 0.819      | -            | -                | -                | -         |    -8.37 | Cryptic, d4rty, FaNg, freshie, PwnAlone  |
|           30 |     3585 | 2024-04-02 | Take Flyte        | W   | 0.818      | -            | -                | -                | -         |    10.69 | Cryptic, d4rty, FaNg, freshie, PwnAlone  |
|           29 |     3758 | 2024-03-27 | One More Esports  | W   | 0.780      | 0.477        | 0.005 (0.002)    | -                | -         |     9.61 | brett, Cryptic, d4rty, freshie, PwnAlone |
|           28 |     3762 | 2024-03-27 | One More Esports  | L   | 0.780      | -            | -                | -                | -         |   -15.32 | brett, Cryptic, d4rty, freshie, PwnAlone |
|           27 |     3835 | 2024-03-26 | Elevate           | L   | 0.773      | -            | -                | -                | -         |   -10.73 | brett, Cryptic, d4rty, freshie, PwnAlone |
|           26 |     3840 | 2024-03-26 | Elevate           | L   | 0.773      | -            | -                | -                | -         |   -11.49 | brett, Cryptic, d4rty, freshie, PwnAlone |
|           25 |     4106 | 2024-03-20 | Party Astronauts  | L   | 0.733      | -            | -                | -                | -         |    -7.79 | brett, Cryptic, d4rty, freshie, PwnAlone |
|           24 |     4108 | 2024-03-20 | Party Astronauts  | L   | 0.733      | -            | -                | -                | -         |    -8.26 | brett, Cryptic, d4rty, freshie, PwnAlone |
|           23 |     5091 | 2024-03-03 | Team Liquid       | L   | 0.617      | -            | -                | -                | -         |    -0.28 | brett, Cryptic, d4rty, freshie, PwnAlone |
|           22 |     5184 | 2024-03-02 | Complexity Gaming | L   | 0.610      | -            | -                | -                | -         |    -0.44 | brett, Cryptic, d4rty, freshie, PwnAlone |
|           21 |     5221 | 2024-03-01 | MIBR              | W   | 0.605      | 0.143        | 0.307 (0.027)    | -                | 1 (0.605) |    18.72 | brett, Cryptic, d4rty, freshie, PwnAlone |
|           20 |     5392 | 2024-02-26 | Team Liquid       | L   | 0.579      | -            | -                | -                | -         |    -0.22 | brett, Cryptic, d4rty, freshie, PwnAlone |
|           19 |     5433 | 2024-02-25 | Nouns Esports     | L   | 0.573      | -            | -                | -                | -         |    -6.95 | brett, Cryptic, d4rty, freshie, PwnAlone |
|           18 |     5436 | 2024-02-25 | Wildcard Gaming   | W   | 0.572      | 0.143        | 0.012 (0.001)    | -                | -         |    11.13 | brett, Cryptic, d4rty, freshie, PwnAlone |
|           17 |     6645 | 2024-02-01 | Nouns Esports     | L   | 0.413      | -            | -                | -                | -         |    -5.22 | brett, Cryptic, d4rty, freshie, PwnAlone |
|           16 |     6647 | 2024-02-01 | Rocket            | W   | 0.413      | -            | -                | -                | -         |     2.62 | brett, Cryptic, d4rty, freshie, PwnAlone |
|           15 |     6652 | 2024-02-01 | Elevate           | L   | 0.412      | -            | -                | -                | -         |    -6.41 | brett, Cryptic, d4rty, freshie, PwnAlone |
|           14 |     7379 | 2024-01-19 | M80               | L   | 0.327      | -            | -                | -                | -         |    -0.92 | brett, Cryptic, cynic, d4rty, freshie    |
|           13 |     7391 | 2024-01-19 | Team Liquid       | L   | 0.325      | -            | -                | -                | -         |    -0.11 | brett, Cryptic, cynic, d4rty, freshie    |
|           12 |     7742 | 2024-01-14 | Rocket            | W   | 0.293      | -            | -                | -                | -         |     1.51 | brett, Cryptic, cynic, d4rty, freshie    |
|           11 |     7768 | 2024-01-13 | Akimbo Esports    | W   | 0.286      | -            | -                | -                | -         |     3.46 | brett, Cryptic, cynic, d4rty, freshie    |
|           10 |     7814 | 2024-01-12 | Wildcard Gaming   | L   | 0.281      | -            | -                | -                | -         |    -4.21 | brett, Cryptic, cynic, d4rty, freshie    |
|            9 |     7816 | 2024-01-12 | For Fun           | W   | 0.280      | -            | -                | -                | -         |     3.38 | brett, Cryptic, cynic, d4rty, freshie    |
|            8 |     8858 | 2023-12-12 | M80               | L   | 0.073      | -            | -                | -                | -         |    -0.19 | brett, Cryptic, d4rty, freshie, WolfY    |
|            7 |     8896 | 2023-12-11 | Party Astronauts  | W   | 0.067      | -            | -                | -                | -         |     0.46 | brett, Cryptic, d4rty, freshie, WolfY    |
|            6 |     8949 | 2023-12-10 | M80               | L   | 0.059      | -            | -                | -                | -         |    -0.15 | brett, Cryptic, d4rty, freshie, WolfY    |
|            5 |     9006 | 2023-12-09 | Party Astronauts  | W   | 0.053      | -            | -                | -                | -         |     0.36 | brett, Cryptic, d4rty, freshie, WolfY    |
|            4 |     9137 | 2023-12-07 | M80               | L   | 0.039      | -            | -                | -                | -         |    -0.10 | brett, Cryptic, d4rty, freshie, WolfY    |
|            3 |     9203 | 2023-12-06 | Nouns Esports     | W   | 0.033      | -            | -                | -                | -         |     0.23 | brett, Cryptic, d4rty, freshie, WolfY    |
|            2 |     9357 | 2023-12-03 | Elevate           | L   | 0.011      | -            | -                | -                | -         |    -0.17 | brett, Cryptic, d4rty, dea, freshie      |
|            1 |     9424 | 2023-12-02 | Supernova         | W   | 0.006      | -            | -                | -                | 1 (0.006) |     0.01 | brett, Cryptic, d4rty, dea, freshie      |

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
