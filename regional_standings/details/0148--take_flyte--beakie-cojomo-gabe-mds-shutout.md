### Roster Details<br />
Team Name: Take Flyte<br />
Roster: BeaKie, CoJoMo, Gabe, mds, shutout<br />
Region: [Americas]( ../standings_americas.md)<br />
<br />
Global Rank: [148](../standings_global.md)<br />
Regional Rank: [28]( ../standings_americas.md)<br />
Final Rank Value:  781.3<br />
<br />
Final Rank Value (781.3) = Starting Rank Value (780.5) + Head To Head Adjustments (0.8)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.309[<sup>1</sup>](#table2)
- Bounty Collected: 0.301[<sup>2</sup>](#table1)
- Opponent Network: 0.139[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.187<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 780.5
- 400 + ( ( 0.187 - 0.000 ) / ( 0.787 - 0.000 ) ) * 1600 = 780.5


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent         | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                               |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           52 |      431 | 2024-05-22 | BOSS             | L   | 1.000      | -            | -                | -                | -         |   -15.22 | BeaKie, CoJoMo, Gabe, mds, shutout   |
|           51 |      436 | 2024-05-22 | BOSS             | W   | 1.000      | 0.477        | 0.016 (0.007)    | 0.315 (0.150)    | 0 (0.000) |    16.33 | BeaKie, CoJoMo, Gabe, mds, shutout   |
|           50 |      539 | 2024-05-21 | NRG              | W   | 1.000      | 0.477        | 0.010 (0.005)    | 0.555 (0.265)    | 0 (0.000) |    24.17 | BeaKie, CoJoMo, Gabe, mds, shutout   |
|           49 |      540 | 2024-05-21 | NRG              | L   | 1.000      | -            | -                | -                | -         |    -6.82 | BeaKie, CoJoMo, Gabe, mds, shutout   |
|           48 |      642 | 2024-05-20 | FLUFFY AIMERS    | L   | 1.000      | -            | -                | -                | -         |   -14.99 | BeaKie, CoJoMo, Gabe, mds, shutout   |
|           47 |      647 | 2024-05-20 | FLUFFY AIMERS    | W   | 1.000      | 0.477        | 0.030 (0.014)    | 0.384 (0.183)    | 0 (0.000) |    16.59 | BeaKie, CoJoMo, Gabe, mds, shutout   |
|           46 |     1035 | 2024-05-16 | regain           | L   | 1.000      | -            | -                | -                | -         |   -22.90 | BeaKie, CoJoMo, Gabe, mds, shutout   |
|           45 |     1045 | 2024-05-16 | The Nomads       | W   | 1.000      | -            | -                | -                | 0 (0.000) |     3.28 | BeaKie, CoJoMo, Gabe, mds, shutout   |
|           44 |     1125 | 2024-05-15 | Mythic           | L   | 1.000      | -            | -                | -                | -         |   -16.44 | BeaKie, CoJoMo, Gabe, mds, shutout   |
|           43 |     1131 | 2024-05-15 | Mythic           | W   | 1.000      | 0.477        | -                | 0.339 (0.162)    | 0 (0.000) |    15.00 | BeaKie, CoJoMo, Gabe, mds, shutout   |
|           42 |     1237 | 2024-05-14 | Elevate          | L   | 1.000      | -            | -                | -                | -         |    -9.51 | BeaKie, CoJoMo, Gabe, mds, shutout   |
|           41 |     1239 | 2024-05-14 | Elevate          | L   | 1.000      | -            | -                | -                | -         |   -10.26 | BeaKie, CoJoMo, Gabe, mds, shutout   |
|           40 |     1350 | 2024-05-12 | NRG              | L   | 1.000      | -            | -                | -                | -         |    -9.73 | BeaKie, CoJoMo, Gabe, louie, shutout |
|           39 |     1356 | 2024-05-12 | Mythic           | W   | 1.000      | 0.270        | -                | 0.339 (0.092)    | 0 (0.000) |    14.47 | BeaKie, CoJoMo, Gabe, mds, shutout   |
|           38 |     1416 | 2024-05-11 | BOSS             | W   | 1.000      | 0.270        | 0.016 (0.004)    | -                | 0 (0.000) |    18.32 | BeaKie, CoJoMo, Gabe, mds, shutout   |
|           37 |     1419 | 2024-05-11 | NRG              | L   | 1.000      | -            | -                | -                | -         |    -9.81 | BeaKie, CoJoMo, Gabe, mds, shutout   |
|           36 |     1423 | 2024-05-11 | Party Astronauts | W   | 1.000      | 0.270        | 0.031 (0.008)    | 0.545 (0.147)    | 0 (0.000) |    23.56 | BeaKie, CoJoMo, Gabe, mds, shutout   |
|           35 |     1604 | 2024-05-08 | Nouns Esports    | L   | 1.000      | -            | -                | -                | -         |    -7.54 | BeaKie, CoJoMo, Gabe, mds, shutout   |
|           34 |     1610 | 2024-05-08 | Nouns Esports    | L   | 1.000      | -            | -                | -                | -         |    -8.06 | BeaKie, CoJoMo, Gabe, mds, shutout   |
|           33 |     2864 | 2024-04-17 | Nouns Esports    | L   | 0.918      | -            | -                | -                | -         |    -6.78 | BeaKie, CoJoMo, Gabe, mds, shutout   |
|           32 |     2943 | 2024-04-16 | Strife Esports   | W   | 0.912      | 0.143        | 0.011 (0.001)    | -                | 0 (0.000) |    11.96 | BeaKie, CoJoMo, Gabe, mds, shutout   |
|           31 |     3209 | 2024-04-10 | MIGHT            | L   | 0.873      | -            | -                | -                | -         |   -18.59 | BeaKie, CoJoMo, Gabe, mds, shutout   |
|           30 |     3214 | 2024-04-10 | MIGHT            | W   | 0.873      | 0.477        | -                | 0.207 (0.086)    | 0 (0.000) |     8.69 | BeaKie, CoJoMo, Gabe, mds, shutout   |
|           29 |     3548 | 2024-04-04 | Carpe Diem       | W   | 0.833      | 0.477        | -                | 0.243 (0.096)    | -         |     8.26 | BeaKie, CoJoMo, Gabe, mds, shutout   |
|           28 |     3552 | 2024-04-04 | Carpe Diem       | W   | 0.833      | 0.477        | -                | 0.243 (0.096)    | -         |     8.81 | BeaKie, CoJoMo, Gabe, mds, shutout   |
|           27 |     3609 | 2024-04-03 | Limitless        | W   | 0.826      | 0.477        | 0.001 (0.001)    | -                | -         |    10.45 | BeaKie, CoJoMo, Gabe, mds, shutout   |
|           26 |     3611 | 2024-04-03 | Limitless        | W   | 0.826      | 0.477        | 0.001 (0.001)    | -                | -         |    11.22 | BeaKie, CoJoMo, Gabe, mds, shutout   |
|           25 |     3670 | 2024-04-02 | Party Astronauts | L   | 0.819      | -            | -                | -                | -         |    -6.21 | BeaKie, CoJoMo, Gabe, mds, shutout   |
|           24 |     3674 | 2024-04-02 | BOSS             | L   | 0.818      | -            | -                | -                | -         |   -10.34 | BeaKie, CoJoMo, Gabe, mds, shutout   |
|           23 |     3860 | 2024-03-27 | M80              | L   | 0.779      | -            | -                | -                | -         |    -1.53 | BeaKie, CoJoMo, Gabe, mds, shutout   |
|           22 |     3866 | 2024-03-27 | M80              | L   | 0.779      | -            | -                | -                | -         |    -1.55 | BeaKie, CoJoMo, Gabe, mds, shutout   |
|           21 |     4209 | 2024-03-20 | LAG Gaming       | W   | 0.733      | 0.477        | 0.013 (0.005)    | 0.335 (0.117)    | -         |    16.80 | BeaKie, CoJoMo, Gabe, mds, shutout   |
|           20 |     4215 | 2024-03-20 | LAG Gaming       | L   | 0.733      | -            | -                | -                | -         |    -6.18 | BeaKie, CoJoMo, Gabe, mds, shutout   |
|           19 |     4249 | 2024-03-19 | Party Astronauts | L   | 0.727      | -            | -                | -                | -         |    -5.48 | BeaKie, CoJoMo, Gabe, mds, shutout   |
|           18 |     4250 | 2024-03-19 | Party Astronauts | L   | 0.726      | -            | -                | -                | -         |    -5.75 | BeaKie, CoJoMo, Gabe, mds, shutout   |
|           17 |     4514 | 2024-03-14 | Wildcard Gaming  | L   | 0.693      | -            | -                | -                | -         |    -6.50 | BeaKie, CoJoMo, Gabe, mds, shutout   |
|           16 |     4517 | 2024-03-14 | Wildcard Gaming  | L   | 0.693      | -            | -                | -                | -         |    -6.84 | BeaKie, CoJoMo, Gabe, mds, shutout   |
|           15 |     4575 | 2024-03-13 | Mythic           | W   | 0.685      | -            | -                | -                | -         |    10.32 | BeaKie, CoJoMo, Gabe, mds, shutout   |
|           14 |     4646 | 2024-03-12 | bubibaby         | W   | 0.679      | -            | -                | -                | -         |     2.55 | BeaKie, CoJoMo, Gabe, mds, shutout   |
|           13 |     4657 | 2024-03-12 | MellstroyKICK    | W   | 0.679      | -            | -                | -                | -         |     2.43 | BeaKie, CoJoMo, Gabe, mds, shutout   |
|           12 |     5744 | 2024-02-23 | G3               | L   | 0.560      | -            | -                | -                | -         |    -8.23 | BeaKie, CoJoMo, Gabe, mds, shutout   |
|           11 |     5791 | 2024-02-22 | MIGHT            | L   | 0.552      | -            | -                | -                | -         |   -10.99 | BeaKie, CoJoMo, Gabe, mds, shutout   |
|           10 |     5837 | 2024-02-21 | G3               | W   | 0.546      | -            | -                | -                | -         |     9.12 | BeaKie, CoJoMo, Gabe, mds, shutout   |
|            9 |     6315 | 2024-02-13 | One More Esports | L   | 0.493      | -            | -                | -                | -         |    -8.47 | BeaKie, CoJoMo, Gabe, mds, shutout   |
|            8 |     6317 | 2024-02-13 | One More Esports | W   | 0.493      | 0.477        | 0.005 (0.001)    | -                | -         |     7.21 | BeaKie, CoJoMo, Gabe, mds, shutout   |
|            7 |     8163 | 2024-01-11 | For Fun          | L   | 0.273      | -            | -                | -                | -         |    -4.45 | CoJoMo, Gabe, mds, Sandman, xaler    |
|            6 |     8216 | 2024-01-10 | CrouchShoot      | W   | 0.267      | -            | -                | -                | -         |     0.89 | CoJoMo, Gabe, mds, Sandman, xaler    |
|            5 |     9536 | 2023-12-05 | FLUFFY AIMERS    | L   | 0.026      | -            | -                | -                | -         |    -0.60 | CoJoMo, Gabe, mds, Sandman, xaler    |
|            4 |     9629 | 2023-12-03 | M80              | L   | 0.013      | -            | -                | -                | -         |    -0.02 | CoJoMo, Gabe, mds, Sandman, xaler    |
|            3 |     9632 | 2023-12-03 | huge sweaty      | W   | 0.012      | -            | -                | -                | -         |     0.06 | CoJoMo, Gabe, mds, Sandman, xaler    |
|            2 |     9692 | 2023-12-02 | regain           | W   | 0.006      | -            | -                | -                | -         |     0.06 | CoJoMo, Gabe, mds, Sandman, xaler    |
|            1 |     9699 | 2023-12-02 | WICKED           | W   | 0.006      | -            | -                | -                | -         |     0.05 | CoJoMo, Gabe, mds, Sandman, xaler    |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($1,731.94)
- Divide that value by the 5th highest value among all rosters ($300,806.11)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-05-22 |      1.000 | $1,600.00      | $1,600.00       |
| 2023-12-10 |      0.059 | $2,000.00      | $118.89         |
| 2023-12-03 |      0.013 | $1,000.00      | $13.06          |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
