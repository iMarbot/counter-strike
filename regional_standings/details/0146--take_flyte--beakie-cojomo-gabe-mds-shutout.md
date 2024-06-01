### Roster Details<br />
Team Name: Take Flyte<br />
Roster: BeaKie, CoJoMo, Gabe, mds, shutout<br />
Region: [Americas]( ../standings_americas.md)<br />
<br />
Global Rank: [146](../standings_global.md)<br />
Regional Rank: [29]( ../standings_americas.md)<br />
Final Rank Value:  785.1<br />
<br />
Final Rank Value (785.1) = Starting Rank Value (781.1) + Head To Head Adjustments (3.9)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.309[<sup>1</sup>](#table2)
- Bounty Collected: 0.301[<sup>2</sup>](#table1)
- Opponent Network: 0.139[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.187<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 781.1
- 400 + ( ( 0.187 - 0.000 ) / ( 0.786 - 0.000 ) ) * 1600 = 781.1


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
|           50 |      423 | 2024-05-22 | BOSS             | L   | 1.000      | -            | -                | -                | -         |   -15.36 | BeaKie, CoJoMo, Gabe, mds, shutout   |
|           49 |      428 | 2024-05-22 | BOSS             | W   | 1.000      | 0.477        | 0.016 (0.007)    | 0.315 (0.150)    | 0 (0.000) |    16.18 | BeaKie, CoJoMo, Gabe, mds, shutout   |
|           48 |      532 | 2024-05-21 | NRG              | W   | 1.000      | 0.477        | 0.010 (0.005)    | 0.555 (0.265)    | 0 (0.000) |    24.04 | BeaKie, CoJoMo, Gabe, mds, shutout   |
|           47 |      533 | 2024-05-21 | NRG              | L   | 1.000      | -            | -                | -                | -         |    -6.96 | BeaKie, CoJoMo, Gabe, mds, shutout   |
|           46 |      631 | 2024-05-20 | FLUFFY AIMERS    | L   | 1.000      | -            | -                | -                | -         |   -15.17 | BeaKie, CoJoMo, Gabe, mds, shutout   |
|           45 |      636 | 2024-05-20 | FLUFFY AIMERS    | W   | 1.000      | 0.477        | 0.030 (0.014)    | 0.384 (0.183)    | 0 (0.000) |    16.39 | BeaKie, CoJoMo, Gabe, mds, shutout   |
|           44 |     1023 | 2024-05-16 | regain           | L   | 1.000      | -            | -                | -                | -         |   -23.05 | BeaKie, CoJoMo, Gabe, mds, shutout   |
|           43 |     1033 | 2024-05-16 | The Nomads       | W   | 1.000      | -            | -                | -                | 0 (0.000) |     3.20 | BeaKie, CoJoMo, Gabe, mds, shutout   |
|           42 |     1115 | 2024-05-15 | Mythic           | L   | 1.000      | -            | -                | -                | -         |   -16.78 | BeaKie, CoJoMo, Gabe, mds, shutout   |
|           41 |     1121 | 2024-05-15 | Mythic           | W   | 1.000      | 0.477        | -                | 0.339 (0.162)    | 0 (0.000) |    14.62 | BeaKie, CoJoMo, Gabe, mds, shutout   |
|           40 |     1227 | 2024-05-14 | Elevate          | L   | 1.000      | -            | -                | -                | -         |    -9.67 | BeaKie, CoJoMo, Gabe, mds, shutout   |
|           39 |     1229 | 2024-05-14 | Elevate          | L   | 1.000      | -            | -                | -                | -         |   -10.44 | BeaKie, CoJoMo, Gabe, mds, shutout   |
|           38 |     1338 | 2024-05-12 | NRG              | L   | 1.000      | -            | -                | -                | -         |   -10.01 | BeaKie, CoJoMo, Gabe, louie, shutout |
|           37 |     1344 | 2024-05-12 | Mythic           | W   | 1.000      | 0.270        | -                | 0.339 (0.092)    | 0 (0.000) |    14.03 | BeaKie, CoJoMo, Gabe, mds, shutout   |
|           36 |     1403 | 2024-05-11 | BOSS             | W   | 1.000      | 0.270        | 0.016 (0.004)    | -                | 0 (0.000) |    18.05 | BeaKie, CoJoMo, Gabe, mds, shutout   |
|           35 |     1406 | 2024-05-11 | NRG              | L   | 1.000      | -            | -                | -                | -         |   -10.14 | BeaKie, CoJoMo, Gabe, mds, shutout   |
|           34 |     1410 | 2024-05-11 | Party Astronauts | W   | 1.000      | 0.270        | 0.031 (0.008)    | 0.545 (0.147)    | 0 (0.000) |    23.30 | BeaKie, CoJoMo, Gabe, mds, shutout   |
|           33 |     1588 | 2024-05-08 | Nouns Esports    | L   | 1.000      | -            | -                | -                | -         |    -7.76 | BeaKie, CoJoMo, Gabe, mds, shutout   |
|           32 |     1594 | 2024-05-08 | Nouns Esports    | L   | 1.000      | -            | -                | -                | -         |    -8.30 | BeaKie, CoJoMo, Gabe, mds, shutout   |
|           31 |     2808 | 2024-04-17 | Nouns Esports    | L   | 0.918      | -            | -                | -                | -         |    -7.00 | BeaKie, CoJoMo, Gabe, mds, shutout   |
|           30 |     2885 | 2024-04-16 | Strife Esports   | W   | 0.912      | 0.143        | 0.011 (0.001)    | -                | 0 (0.000) |    11.65 | BeaKie, CoJoMo, Gabe, mds, shutout   |
|           29 |     3138 | 2024-04-10 | MIGHT            | L   | 0.873      | -            | -                | -                | -         |   -18.86 | BeaKie, CoJoMo, Gabe, mds, shutout   |
|           28 |     3143 | 2024-04-10 | MIGHT            | W   | 0.873      | 0.477        | -                | 0.207 (0.086)    | 0 (0.000) |     8.40 | BeaKie, CoJoMo, Gabe, mds, shutout   |
|           27 |     3463 | 2024-04-04 | Carpe Diem       | W   | 0.833      | 0.477        | -                | 0.243 (0.096)    | -         |     8.00 | BeaKie, CoJoMo, Gabe, mds, shutout   |
|           26 |     3467 | 2024-04-04 | Carpe Diem       | W   | 0.833      | 0.477        | -                | 0.243 (0.096)    | -         |     8.52 | BeaKie, CoJoMo, Gabe, mds, shutout   |
|           25 |     3522 | 2024-04-03 | Limitless        | W   | 0.826      | 0.477        | 0.001 (0.001)    | -                | -         |    10.11 | BeaKie, CoJoMo, Gabe, mds, shutout   |
|           24 |     3524 | 2024-04-03 | Limitless        | W   | 0.826      | 0.477        | 0.001 (0.001)    | -                | -         |    10.85 | BeaKie, CoJoMo, Gabe, mds, shutout   |
|           23 |     3581 | 2024-04-02 | Party Astronauts | L   | 0.819      | -            | -                | -                | -         |    -6.49 | BeaKie, CoJoMo, Gabe, mds, shutout   |
|           22 |     3585 | 2024-04-02 | BOSS             | L   | 0.818      | -            | -                | -                | -         |   -10.69 | BeaKie, CoJoMo, Gabe, mds, shutout   |
|           21 |     3767 | 2024-03-27 | M80              | L   | 0.779      | -            | -                | -                | -         |    -1.55 | BeaKie, CoJoMo, Gabe, mds, shutout   |
|           20 |     3773 | 2024-03-27 | M80              | L   | 0.779      | -            | -                | -                | -         |    -1.57 | BeaKie, CoJoMo, Gabe, mds, shutout   |
|           19 |     4109 | 2024-03-20 | LAG Gaming       | W   | 0.733      | 0.477        | 0.013 (0.005)    | 0.335 (0.117)    | -         |    16.50 | BeaKie, CoJoMo, Gabe, mds, shutout   |
|           18 |     4115 | 2024-03-20 | LAG Gaming       | L   | 0.733      | -            | -                | -                | -         |    -6.49 | BeaKie, CoJoMo, Gabe, mds, shutout   |
|           17 |     4147 | 2024-03-19 | Party Astronauts | L   | 0.727      | -            | -                | -                | -         |    -5.76 | BeaKie, CoJoMo, Gabe, mds, shutout   |
|           16 |     4148 | 2024-03-19 | Party Astronauts | L   | 0.726      | -            | -                | -                | -         |    -6.05 | BeaKie, CoJoMo, Gabe, mds, shutout   |
|           15 |     4461 | 2024-03-13 | Mythic           | W   | 0.685      | -            | -                | -                | -         |    10.18 | BeaKie, CoJoMo, Gabe, mds, shutout   |
|           14 |     4527 | 2024-03-12 | bubibaby         | W   | 0.679      | -            | -                | -                | -         |     2.56 | BeaKie, CoJoMo, Gabe, mds, shutout   |
|           13 |     4538 | 2024-03-12 | MellstroyKICK    | W   | 0.679      | -            | -                | -                | -         |     2.44 | BeaKie, CoJoMo, Gabe, mds, shutout   |
|           12 |     5584 | 2024-02-23 | G3               | L   | 0.560      | -            | -                | -                | -         |    -9.03 | BeaKie, CoJoMo, Gabe, mds, shutout   |
|           11 |     5631 | 2024-02-22 | MIGHT            | L   | 0.552      | -            | -                | -                | -         |   -10.97 | BeaKie, CoJoMo, Gabe, mds, shutout   |
|           10 |     5676 | 2024-02-21 | G3               | W   | 0.546      | -            | -                | -                | -         |     8.30 | BeaKie, CoJoMo, Gabe, mds, shutout   |
|            9 |     6134 | 2024-02-13 | One More Esports | L   | 0.493      | -            | -                | -                | -         |    -8.47 | BeaKie, CoJoMo, Gabe, mds, shutout   |
|            8 |     6135 | 2024-02-13 | One More Esports | W   | 0.493      | 0.477        | 0.005 (0.001)    | -                | -         |     7.21 | BeaKie, CoJoMo, Gabe, mds, shutout   |
|            7 |     7910 | 2024-01-11 | For Fun          | L   | 0.273      | -            | -                | -                | -         |    -4.45 | CoJoMo, Gabe, mds, Sandman, xaler    |
|            6 |     7963 | 2024-01-10 | CrouchShoot      | W   | 0.267      | -            | -                | -                | -         |     0.89 | CoJoMo, Gabe, mds, Sandman, xaler    |
|            5 |     9255 | 2023-12-05 | FLUFFY AIMERS    | L   | 0.026      | -            | -                | -                | -         |    -0.60 | CoJoMo, Gabe, mds, Sandman, xaler    |
|            4 |     9347 | 2023-12-03 | M80              | L   | 0.013      | -            | -                | -                | -         |    -0.02 | CoJoMo, Gabe, mds, Sandman, xaler    |
|            3 |     9350 | 2023-12-03 | huge sweaty      | W   | 0.012      | -            | -                | -                | -         |     0.06 | CoJoMo, Gabe, mds, Sandman, xaler    |
|            2 |     9410 | 2023-12-02 | regain           | W   | 0.006      | -            | -                | -                | -         |     0.06 | CoJoMo, Gabe, mds, Sandman, xaler    |
|            1 |     9417 | 2023-12-02 | WICKED           | W   | 0.006      | -            | -                | -                | -         |     0.05 | CoJoMo, Gabe, mds, Sandman, xaler    |

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
