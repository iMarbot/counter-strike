### Roster Details<br />
Team Name: Virtus.pro<br />
Roster: electroNic, fame, FL1T, Jame, n0rb3r7<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [9](../standings_global.md)<br />
Regional Rank: [9]( ../standings_europe.md)<br />
Final Rank Value:  1671.2<br />
<br />
Final Rank Value (1671.2) = Starting Rank Value (1702.6) + Head To Head Adjustments (-31.4)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.745[<sup>1</sup>](#table2)
- Bounty Collected: 0.567[<sup>2</sup>](#table1)
- Opponent Network: 0.335[<sup>2</sup>](#table1)
- LAN Wins: 0.979[<sup>2</sup>](#table1)

The average of these factors is 0.657<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1702.6
- 400 + ( ( 0.657 - 0.000 ) / ( 0.806 - 0.000 ) ) * 1600 = 1702.6


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent         | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           42 |      315 | 2024-04-28 | SAW              | W   | 1.000      | 0.889        | 0.263 (0.234)    | 0.590 (0.525)    | 1 (1.000) |     7.94 | electroNic, fame, FL1T, Jame, n0rb3r7 |
|           41 |      381 | 2024-04-27 | Fnatic           | W   | 1.000      | 0.889        | 0.334 (0.297)    | 0.683 (0.607)    | 1 (1.000) |     2.54 | electroNic, fame, FL1T, Jame, n0rb3r7 |
|           40 |      467 | 2024-04-25 | FaZe Clan        | L   | 1.000      | -            | -                | -                | -         |    -5.94 | electroNic, fame, FL1T, Jame, n0rb3r7 |
|           39 |      538 | 2024-04-24 | SAW              | W   | 1.000      | 0.889        | 0.263 (0.234)    | 0.590 (0.525)    | 1 (1.000) |     6.96 | electroNic, fame, FL1T, Jame, n0rb3r7 |
|           38 |      588 | 2024-04-23 | Fnatic           | L   | 1.000      | -            | -                | -                | -         |   -29.28 | electroNic, fame, FL1T, Jame, n0rb3r7 |
|           37 |     1156 | 2024-04-12 | G2 Esports       | L   | 1.000      | -            | -                | -                | -         |    -9.15 | fame, FL1T, Jame, mir, n0rb3r7        |
|           36 |     1256 | 2024-04-10 | Astralis         | L   | 1.000      | -            | -                | -                | -         |   -22.62 | fame, FL1T, Jame, mir, n0rb3r7        |
|           35 |     1316 | 2024-04-08 | FlyQuest         | W   | 1.000      | 0.624        | -                | 0.547 (0.341)    | 1 (1.000) |     4.60 | fame, FL1T, Jame, mir, n0rb3r7        |
|           34 |     1355 | 2024-04-08 | Wildcard Gaming  | W   | 1.000      | 0.624        | -                | 0.483 (0.302)    | 1 (1.000) |     0.35 | fame, FL1T, Jame, mir, n0rb3r7        |
|           33 |     1863 | 2024-03-24 | G2 Esports       | L   | 0.917      | -            | -                | -                | -         |    -9.03 | fame, FL1T, Jame, mir, n0rb3r7        |
|           32 |     1918 | 2024-03-23 | Eternal Fire     | L   | 0.910      | -            | -                | -                | -         |   -11.11 | fame, FL1T, Jame, mir, n0rb3r7        |
|           31 |     1948 | 2024-03-22 | HEROIC           | W   | 0.904      | 1.000        | 0.243 (0.220)    | 0.537 (0.485)    | 1 (0.904) |    12.91 | fame, FL1T, Jame, mir, n0rb3r7        |
|           30 |     1979 | 2024-03-21 | PaiN Gaming      | W   | 0.899      | 1.000        | -                | 0.156 (0.141)    | 1 (0.899) |     0.81 | fame, FL1T, Jame, mir, n0rb3r7        |
|           29 |     1992 | 2024-03-21 | Imperial Esports | L   | 0.897      | -            | -                | -                | -         |   -22.02 | fame, FL1T, Jame, mir, n0rb3r7        |
|           28 |     2366 | 2024-03-12 | HEROIC           | W   | 0.839      | -            | -                | -                | -         |    11.02 | fame, FL1T, Jame, mir, n0rb3r7        |
|           27 |     2404 | 2024-03-11 | Apeks            | W   | 0.832      | -            | -                | -                | -         |     4.00 | fame, FL1T, Jame, mir, n0rb3r7        |
|           26 |     2424 | 2024-03-11 | B8               | W   | 0.831      | -            | -                | -                | -         |     0.43 | fame, FL1T, Jame, mir, n0rb3r7        |
|           25 |     3588 | 2024-02-15 | Natus Vincere    | W   | 0.665      | 0.143        | 1.000 (0.095)    | -                | 1 (0.665) |    16.20 | fame, FL1T, Jame, mir, n0rb3r7        |
|           24 |     3617 | 2024-02-14 | Fnatic           | W   | 0.659      | -            | -                | -                | 1 (0.659) |     1.30 | fame, FL1T, Jame, mir, n0rb3r7        |
|           23 |     3655 | 2024-02-14 | SAW              | W   | 0.657      | -            | -                | -                | 1 (0.657) |     4.14 | fame, FL1T, Jame, mir, n0rb3r7        |
|           22 |     4035 | 2024-02-02 | Cloud9           | L   | 0.578      | -            | -                | -                | -         |    -7.99 | fame, FL1T, Jame, mir, n0rb3r7        |
|           21 |     4087 | 2024-02-01 | GamerLegion      | L   | 0.570      | -            | -                | -                | -         |   -12.33 | fame, FL1T, Jame, mir, n0rb3r7        |
|           20 |     4104 | 2024-01-31 | Rooster          | W   | 0.565      | 1.000        | -                | 0.312 (0.177)    | -         |     0.12 | fame, FL1T, Jame, mir, n0rb3r7        |
|           19 |     4258 | 2024-01-27 | BIG              | W   | 0.539      | 0.581        | 0.470 (0.147)    | 0.400 (0.125)    | -         |     2.91 | fame, FL1T, Jame, mir, n0rb3r7        |
|           18 |     4356 | 2024-01-25 | Cloud9           | W   | 0.525      | 0.581        | 0.487 (0.149)    | 0.419 (0.128)    | -         |     9.94 | fame, FL1T, Jame, mir, n0rb3r7        |
|           17 |     4381 | 2024-01-24 | BIG              | W   | 0.518      | 0.581        | 0.470 (0.142)    | -                | -         |     2.64 | fame, FL1T, Jame, mir, n0rb3r7        |
|           16 |     4554 | 2024-01-20 | Fnatic           | W   | 0.491      | -            | -                | -                | -         |     0.96 | fame, FL1T, Jame, mir, n0rb3r7        |
|           15 |     4601 | 2024-01-19 | Natus Vincere    | L   | 0.485      | -            | -                | -                | -         |    -3.20 | fame, FL1T, Jame, mir, n0rb3r7        |
|           14 |     4651 | 2024-01-18 | SAW              | W   | 0.478      | -            | -                | -                | -         |     3.19 | fame, FL1T, Jame, mir, n0rb3r7        |
|           13 |     4667 | 2024-01-18 | SINNERS Esports  | W   | 0.478      | -            | -                | -                | -         |     0.28 | fame, FL1T, Jame, mir, n0rb3r7        |
|           12 |     5341 | 2023-12-17 | Apeks            | W   | 0.266      | -            | -                | -                | -         |     1.32 | fame, FL1T, Jame, mir, n0rb3r7        |
|           11 |     5369 | 2023-12-17 | The MongolZ      | W   | 0.264      | -            | -                | -                | -         |     3.55 | fame, FL1T, Jame, mir, n0rb3r7        |
|           10 |     5566 | 2023-12-15 | Monte            | W   | 0.253      | -            | -                | -                | -         |     1.09 | fame, FL1T, Jame, mir, n0rb3r7        |
|            9 |     5584 | 2023-12-15 | M80              | W   | 0.252      | -            | -                | -                | -         |     0.76 | fame, FL1T, Jame, mir, n0rb3r7        |
|            8 |     5740 | 2023-12-10 | Team Spirit      | L   | 0.217      | -            | -                | -                | -         |    -2.19 | fame, FL1T, Jame, mir, n0rb3r7        |
|            7 |     5787 | 2023-12-09 | BetBoom Team     | W   | 0.210      | 0.657        | 0.571 (0.079)    | -                | -         |     1.49 | fame, FL1T, Jame, mir, n0rb3r7        |
|            6 |     5905 | 2023-12-07 | Team Spirit      | W   | 0.196      | 0.657        | 1.000 (0.129)    | -                | -         |     4.23 | fame, FL1T, Jame, mir, n0rb3r7        |
|            5 |     5952 | 2023-12-06 | Astralis         | W   | 0.190      | -            | -                | -                | -         |     1.76 | fame, FL1T, Jame, mir, n0rb3r7        |
|            4 |     6410 | 2023-11-26 | Monte            | L   | 0.122      | -            | -                | -                | -         |    -3.34 | fame, FL1T, Jame, mir, n0rb3r7        |
|            3 |     6445 | 2023-11-25 | GamerLegion      | W   | 0.117      | -            | -                | -                | -         |     1.30 | fame, FL1T, Jame, mir, n0rb3r7        |
|            2 |     6474 | 2023-11-24 | MIBR             | L   | 0.112      | -            | -                | -                | -         |    -1.97 | fame, FL1T, Jame, mir, n0rb3r7        |
|            1 |     6492 | 2023-11-24 | 3DMAX            | W   | 0.110      | -            | -                | -                | -         |     0.05 | fame, FL1T, Jame, mir, n0rb3r7        |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($71,995.35)
- Divide that value by the 5th highest value among all rosters ($158,437.64)
- The final value (0.45) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-04-14 |      1.000 | $10,000.00     | $10,000.00      |
| 2024-03-31 |      0.965 | $20,000.00     | $19,304.63      |
| 2024-02-11 |      0.638 | $4,500.00      | $2,871.04       |
| 2024-01-28 |      0.545 | $22,500.00     | $12,264.58      |
| 2023-12-17 |      0.266 | $50,000.00     | $13,309.03      |
| 2023-12-10 |      0.217 | $60,000.00     | $12,995.83      |
| 2023-11-26 |      0.125 | $10,000.00     | $1,250.23       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
