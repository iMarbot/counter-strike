### Roster Details<br />
Team Name: Take Flyte<br />
Roster: BeaKie, CoJoMo, Gabe, mds, shutout<br />
Region: [Americas]( ../standings_americas.md)<br />
<br />
Global Rank: [194](../standings_global.md)<br />
Regional Rank: [35]( ../standings_americas.md)<br />
Final Rank Value:  733.9<br />
<br />
Final Rank Value (733.9) = Starting Rank Value (722.3) + Head To Head Adjustments (11.6)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.293[<sup>1</sup>](#table2)
- Bounty Collected: 0.284[<sup>2</sup>](#table1)
- Opponent Network: 0.072[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.162<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 722.3
- 400 + ( ( 0.162 - 0.000 ) / ( 0.806 - 0.000 ) ) * 1600 = 722.3


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent                   | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins      | H2H Adj. | Roster                             |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           30 |      918 | 2024-04-17 | Nouns Esports              | L   | 1.000      | -            | -                | -                | -             |   -10.73 | BeaKie, CoJoMo, Gabe, mds, shutout |
|           29 |      985 | 2024-04-16 | Strife Esports             | W   | 1.000      | 0.143        | 0.000 (0.000)    | 0.035 (0.005)    | false (0.000) |     3.97 | BeaKie, CoJoMo, Gabe, mds, shutout |
|           28 |     1194 | 2024-04-10 | MIGHT                      | L   | 1.000      | -            | -                | -                | -             |   -19.98 | BeaKie, CoJoMo, Gabe, mds, shutout |
|           27 |     1198 | 2024-04-10 | MIGHT                      | W   | 1.000      | 0.477        | 0.003 (0.001)    | 0.213 (0.101)    | false (0.000) |    11.17 | BeaKie, CoJoMo, Gabe, mds, shutout |
|           26 |     1458 | 2024-04-04 | Carpe Diem                 | W   | 0.994      | 0.477        | 0.009 (0.004)    | 0.178 (0.085)    | false (0.000) |    12.23 | BeaKie, CoJoMo, Gabe, mds, shutout |
|           25 |     1462 | 2024-04-04 | Carpe Diem                 | W   | 0.994      | 0.477        | 0.009 (0.004)    | 0.178 (0.085)    | false (0.000) |    13.31 | BeaKie, CoJoMo, Gabe, mds, shutout |
|           24 |     1510 | 2024-04-03 | Limitless                  | W   | 0.987      | 0.477        | 0.001 (0.001)    | 0.177 (0.083)    | false (0.000) |    13.56 | BeaKie, CoJoMo, Gabe, mds, shutout |
|           23 |     1512 | 2024-04-03 | Limitless                  | W   | 0.987      | 0.477        | 0.001 (0.001)    | 0.177 (0.083)    | false (0.000) |    14.78 | BeaKie, CoJoMo, Gabe, mds, shutout |
|           22 |     1563 | 2024-04-02 | Party Astronauts           | L   | 0.981      | -            | -                | -                | -             |   -10.49 | BeaKie, CoJoMo, Gabe, mds, shutout |
|           21 |     1567 | 2024-04-02 | BOSS                       | L   | 0.980      | -            | -                | -                | -             |    -7.58 | BeaKie, CoJoMo, Gabe, mds, shutout |
|           20 |     1717 | 2024-03-27 | M80                        | L   | 0.941      | -            | -                | -                | -             |    -1.33 | BeaKie, CoJoMo, Gabe, mds, shutout |
|           19 |     1721 | 2024-03-27 | M80                        | L   | 0.940      | -            | -                | -                | -             |    -1.35 | BeaKie, CoJoMo, Gabe, mds, shutout |
|           18 |     2001 | 2024-03-20 | LAG Gaming (American team) | W   | 0.894      | 0.477        | 0.033 (0.014)    | 0.405 (0.173)    | false (0.000) |    21.38 | BeaKie, CoJoMo, Gabe, mds, shutout |
|           17 |     2007 | 2024-03-20 | LAG Gaming (American team) | L   | 0.894      | -            | -                | -                | -             |    -6.45 | BeaKie, CoJoMo, Gabe, mds, shutout |
|           16 |     2038 | 2024-03-19 | Party Astronauts           | L   | 0.888      | -            | -                | -                | -             |    -8.78 | BeaKie, CoJoMo, Gabe, mds, shutout |
|           15 |     2039 | 2024-03-19 | Party Astronauts           | L   | 0.887      | -            | -                | -                | -             |    -9.41 | BeaKie, CoJoMo, Gabe, mds, shutout |
|           14 |     2295 | 2024-03-13 | Mythic                     | W   | 0.846      | 0.143        | 0.003 (0.000)    | 0.380 (0.046)    | false (0.000) |    13.88 | BeaKie, CoJoMo, Gabe, mds, shutout |
|           13 |     2355 | 2024-03-12 | MellstroyKICK              | W   | 0.840      | -            | -                | -                | false (0.000) |     4.06 | BeaKie, CoJoMo, Gabe, mds, shutout |
|           12 |     3192 | 2024-02-23 | G3 (Asian team)            | L   | 0.721      | -            | -                | -                | -             |   -10.45 | BeaKie, CoJoMo, Gabe, mds, shutout |
|           11 |     3231 | 2024-02-22 | MIGHT                      | L   | 0.713      | -            | -                | -                | -             |   -10.42 | BeaKie, CoJoMo, Gabe, mds, shutout |
|           10 |     3272 | 2024-02-21 | G3 (Asian team)            | W   | 0.707      | 0.143        | 0.014 (0.001)    | 0.173 (0.018)    | false (0.000) |    11.95 | BeaKie, CoJoMo, Gabe, mds, shutout |
|            9 |     3658 | 2024-02-13 | One More Esports           | L   | 0.654      | -            | -                | -                | -             |   -10.43 | BeaKie, CoJoMo, Gabe, mds, shutout |
|            8 |     3659 | 2024-02-13 | One More Esports           | W   | 0.654      | 0.477        | 0.011 (0.003)    | 0.147 (0.046)    | -             |    10.39 | BeaKie, CoJoMo, Gabe, mds, shutout |
|            7 |     4979 | 2024-01-11 | For Fun                    | L   | 0.434      | -            | -                | -                | -             |    -5.68 | CoJoMo, Gabe, mds, Sandman, xaler  |
|            6 |     5958 | 2023-12-05 | FLUFFY AIMERS              | L   | 0.187      | -            | -                | -                | -             |    -3.31 | CoJoMo, Gabe, mds, Sandman, xaler  |
|            5 |     6026 | 2023-12-03 | M80                        | L   | 0.174      | -            | -                | -                | -             |    -0.20 | CoJoMo, Gabe, mds, Sandman, xaler  |
|            4 |     6539 | 2023-11-22 | Elevate                    | L   | 0.101      | -            | -                | -                | -             |    -1.30 | CoJoMo, Gabe, mds, Sandman, xaler  |
|            3 |     6756 | 2023-11-17 | BOSS                       | L   | 0.067      | -            | -                | -                | -             |    -0.58 | CoJoMo, Gabe, mds, Sandman, xaler  |
|            2 |     6949 | 2023-11-13 | Party Astronauts           | L   | 0.041      | -            | -                | -                | -             |    -0.49 | CoJoMo, Gabe, mds, Sandman, xaler  |
|            1 |     7156 | 2023-11-08 | Evil Geniuses              | L   | 0.007      | -            | -                | -                | -             |    -0.13 | CoJoMo, Gabe, mds, Sandman, xaler  |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($615.14)
- Divide that value by the 5th highest value among all rosters ($158,437.64)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2023-12-10 |      0.221 | $2,000.00      | $441.02         |
| 2023-12-03 |      0.174 | $1,000.00      | $174.12         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
