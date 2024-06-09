### Roster Details<br />
Team Name: MOUZ<br />
Roster: Brollan, Jimpphat, siuhy, torzsi, xertioN<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [1](../standings_global.md)<br />
Regional Rank: [1]( ../standings_europe.md)<br />
Final Rank Value:  1953.7<br />
<br />
Final Rank Value (1953.7) = Starting Rank Value (1979.8) + Head To Head Adjustments (-26.1)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 1.000[<sup>1</sup>](#table2)
- Bounty Collected: 0.731[<sup>2</sup>](#table1)
- Opponent Network: 0.378[<sup>2</sup>](#table1)
- LAN Wins: 1.000[<sup>2</sup>](#table1)

The average of these factors is 0.777<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1979.8
- 400 + ( ( 0.777 - 0.000 ) / ( 0.787 - 0.000 ) ) * 1600 = 1979.8


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent           | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                    |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           38 |      106 | 2024-05-28 | G2 Esports         | L   | 1.000      | -            | -                | -                | -         |   -24.14 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|           37 |      149 | 2024-05-27 | Complexity Gaming  | W   | 1.000      | -            | -                | -                | 1 (1.000) |     3.27 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|           36 |      165 | 2024-05-27 | 9z Team            | L   | 1.000      | -            | -                | -                | -         |   -31.10 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|           35 |      793 | 2024-05-19 | Team Spirit        | W   | 1.000      | 0.769        | 1.000 (0.769)    | 0.354 (0.272)    | 1 (1.000) |    12.47 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|           34 |      888 | 2024-05-18 | HEROIC             | W   | 1.000      | 0.769        | 0.322 (0.247)    | 0.463 (0.356)    | 1 (1.000) |     3.33 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|           33 |     1111 | 2024-05-16 | Virtus.pro         | W   | 1.000      | 0.769        | -                | 0.331 (0.255)    | 1 (1.000) |     4.24 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|           32 |     1296 | 2024-05-14 | BetBoom Team       | W   | 1.000      | 0.769        | 0.390 (0.299)    | 0.712 (0.547)    | 1 (1.000) |     0.72 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|           31 |     1378 | 2024-05-12 | Team Vitality      | W   | 1.000      | 0.889        | 0.696 (0.618)    | 0.320 (0.284)    | 1 (1.000) |    10.33 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|           30 |     1427 | 2024-05-11 | Complexity Gaming  | W   | 1.000      | 0.889        | 0.260 (0.231)    | -                | 1 (1.000) |     3.63 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|           29 |     1570 | 2024-05-09 | G2 Esports         | W   | 1.000      | 0.889        | 0.468 (0.416)    | 0.392 (0.348)    | 1 (1.000) |     7.28 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|           28 |     1828 | 2024-05-04 | Team Liquid        | W   | 1.000      | 0.889        | 0.493 (0.438)    | 0.621 (0.552)    | 1 (1.000) |     3.91 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|           27 |     2019 | 2024-05-01 | GamerLegion        | W   | 1.000      | -            | -                | -                | 1 (1.000) |     0.50 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|           26 |     2072 | 2024-04-30 | Bad News Kangaroos | W   | 1.000      | -            | -                | -                | -         |     0.09 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|           25 |     3057 | 2024-04-14 | FaZe Clan          | L   | 0.895      | -            | -                | -                | -         |   -14.55 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|           24 |     3121 | 2024-04-12 | G2 Esports         | W   | 0.887      | 0.624        | 0.468 (0.259)    | -                | -         |     7.89 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|           23 |     3286 | 2024-04-10 | Team Liquid        | W   | 0.868      | 0.624        | 0.493 (0.267)    | 0.621 (0.336)    | -         |     3.67 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|           22 |     3387 | 2024-04-08 | FURIA Esports      | W   | 0.856      | -            | -                | -                | -         |     1.17 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|           21 |     3400 | 2024-04-07 | TYLOO              | W   | 0.854      | -            | -                | -                | -         |     0.07 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|           20 |     3791 | 2024-03-29 | G2 Esports         | L   | 0.791      | -            | -                | -                | -         |   -17.90 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|           19 |     4137 | 2024-03-22 | Complexity Gaming  | W   | 0.743      | -            | -                | -                | -         |     1.99 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|           18 |     4187 | 2024-03-21 | Eternal Fire       | W   | 0.737      | 1.000        | 1.000 (0.737)    | 0.402 (0.296)    | -         |     7.38 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|           17 |     4200 | 2024-03-21 | Gaimin Gladiators  | W   | 0.736      | 1.000        | -                | 0.727 (0.535)    | -         |     0.49 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|           16 |     5933 | 2024-02-20 | Team Spirit        | W   | 0.537      | -            | -                | -                | -         |     7.44 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|           15 |     5995 | 2024-02-19 | Gaimin Gladiators  | W   | 0.531      | -            | -                | -                | -         |     0.31 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|           14 |     6024 | 2024-02-19 | ex-Guild Eagles    | W   | 0.529      | -            | -                | -                | -         |     0.07 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|           13 |     6461 | 2024-02-10 | FaZe Clan          | L   | 0.470      | -            | -                | -                | -         |    -6.80 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|           12 |     6569 | 2024-02-06 | ENCE               | W   | 0.444      | -            | -                | -                | -         |     0.76 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|           11 |     6632 | 2024-02-05 | GamerLegion        | W   | 0.437      | -            | -                | -                | -         |     0.25 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|           10 |     6675 | 2024-02-04 | Cloud9             | W   | 0.429      | -            | -                | -                | -         |     0.93 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|            9 |     7565 | 2024-01-20 | ex-Preasy Esport   | W   | 0.331      | -            | -                | -                | -         |     0.03 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|            8 |     7589 | 2024-01-20 | Team Spirit        | L   | 0.330      | -            | -                | -                | -         |    -6.28 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|            7 |     7651 | 2024-01-19 | Eternal Fire       | L   | 0.324      | -            | -                | -                | -         |    -6.91 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|            6 |     7717 | 2024-01-18 | HEROIC             | W   | 0.317      | -            | -                | -                | -         |     2.34 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|            5 |     7731 | 2024-01-18 | EYEBALLERS         | W   | 0.317      | -            | -                | -                | -         |     0.03 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|            4 |     8897 | 2023-12-16 | FaZe Clan          | L   | 0.096      | -            | -                | -                | -         |    -1.41 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|            3 |     9022 | 2023-12-15 | Cloud9             | W   | 0.088      | -            | -                | -                | -         |     0.17 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|            2 |     9056 | 2023-12-14 | Heroic             | W   | 0.082      | -            | -                | -                | -         |     0.00 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|            1 |     9111 | 2023-12-13 | G2 Esports         | L   | 0.076      | -            | -                | -                | -         |    -1.75 | Brollan, Jimpphat, siuhy, torzsi, xertioN |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($595,687.08)
- Divide that value by the 5th highest value among all rosters ($300,806.11)
- The final value (1.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-05-29 |      1.000 | $5,000.00      | $5,000.00       |
| 2024-05-19 |      1.000 | $300,000.00    | $300,000.00     |
| 2024-05-12 |      1.000 | $170,000.00    | $170,000.00     |
| 2024-04-14 |      0.895 | $42,000.00     | $37,596.81      |
| 2024-03-31 |      0.804 | $45,000.00     | $36,175.00      |
| 2024-02-11 |      0.477 | $80,000.00     | $38,155.56      |
| 2023-12-17 |      0.103 | $85,000.00     | $8,759.72       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
