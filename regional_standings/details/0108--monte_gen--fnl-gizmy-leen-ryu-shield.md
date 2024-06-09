### Roster Details<br />
Team Name: Monte Gen<br />
Roster: fnl, Gizmy, leen, ryu, shield<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [108](../standings_global.md)<br />
Regional Rank: [78]( ../standings_europe.md)<br />
Final Rank Value:  859.5<br />
<br />
Final Rank Value (859.5) = Starting Rank Value (772.8) + Head To Head Adjustments (86.7)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.314[<sup>1</sup>](#table2)
- Bounty Collected: 0.315[<sup>2</sup>](#table1)
- Opponent Network: 0.105[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.183<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 772.8
- 400 + ( ( 0.183 - 0.000 ) / ( 0.787 - 0.000 ) ) * 1600 = 772.8


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent             | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                          |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           28 |      183 | 2024-05-27 | Young Ninjas         | W   | 1.000      | 0.333        | 0.043 (0.014)    | 0.372 (0.124)    | 0 (0.000) |    16.99 | fnl, Gizmy, leen, ryu, shield   |
|           27 |      231 | 2024-05-26 | Reason Gaming        | W   | 1.000      | 0.333        | 0.004 (0.001)    | 0.133 (0.044)    | 0 (0.000) |    10.72 | fnl, Gizmy, leen, ryu, shield   |
|           26 |      406 | 2024-05-23 | Preasy Esport        | W   | 1.000      | 0.333        | 0.008 (0.003)    | 0.705 (0.235)    | 0 (0.000) |    11.04 | fnl, Gizmy, leen, ryu, shield   |
|           25 |      598 | 2024-05-21 | Nexus Gaming         | L   | 1.000      | -            | -                | -                | -         |   -15.00 | fnl, Gizmy, leen, ryu, shield   |
|           24 |      752 | 2024-05-19 | WinX                 | W   | 1.000      | -            | -                | -                | 0 (0.000) |     3.32 | fnl, Gizmy, leen, ryu, shield   |
|           23 |      771 | 2024-05-19 | Grannys Knockers     | W   | 1.000      | 0.143        | 0.006 (0.001)    | 0.517 (0.074)    | 0 (0.000) |    15.02 | fnl, Gizmy, leen, ryu, shield   |
|           22 |      779 | 2024-05-19 | REDPack Esports      | W   | 1.000      | -            | -                | -                | 0 (0.000) |     4.91 | fnl, Gizmy, leen, ryu, shield   |
|           21 |      803 | 2024-05-19 | Virtuoso Squad       | W   | 1.000      | -            | -                | -                | 0 (0.000) |     5.17 | fnl, Gizmy, leen, ryu, shield   |
|           20 |      916 | 2024-05-18 | VOLT                 | W   | 1.000      | -            | -                | -                | 0 (0.000) |     3.08 | fnl, Gizmy, leen, ryu, shield   |
|           19 |     1539 | 2024-05-10 | 9Pandas              | L   | 1.000      | -            | -                | -                | -         |    -5.22 | AiyvaN, leen, n0te, ryu, shield |
|           18 |     5565 | 2024-02-26 | brazylijski luz      | L   | 0.578      | -            | -                | -                | -         |    -9.74 | Gizmy, leen, n0te, ryu, shield  |
|           17 |     6497 | 2024-02-09 | Betera Esports       | L   | 0.463      | -            | -                | -                | -         |    -7.03 | Gizmy, leen, n0te, ryu, shield  |
|           16 |     6529 | 2024-02-08 | Passion UA           | W   | 0.456      | 0.333        | 0.057 (0.009)    | 1.000 (0.152)    | 0 (0.000) |    10.43 | Gizmy, leen, n0te, ryu, shield  |
|           15 |     6589 | 2024-02-06 | ex-Anonymo Esports   | W   | 0.442      | 0.333        | 0.002 (0.000)    | -                | 0 (0.000) |     5.75 | Gizmy, leen, n0te, ryu, shield  |
|           14 |     6945 | 2024-01-31 | MOUZ NXT             | W   | 0.403      | 0.333        | 0.157 (0.021)    | 0.977 (0.131)    | -         |    10.76 | Gizmy, leen, n0te, ryu, shield  |
|           13 |     7060 | 2024-01-29 | Team Secret          | W   | 0.389      | -            | -                | -                | -         |     3.34 | Gizmy, leen, n0te, ryu, shield  |
|           12 |     7609 | 2024-01-20 | MOUZ NXT             | L   | 0.328      | -            | -                | -                | -         |    -1.45 | Gizmy, leen, n0te, ryu, shield  |
|           11 |     7740 | 2024-01-18 | WOPA Esport          | W   | 0.316      | 0.303        | -                | 0.594 (0.057)    | -         |     5.19 | Gizmy, leen, n0te, ryu, shield  |
|           10 |     7935 | 2024-01-16 | Natus Vincere Junior | W   | 0.302      | 0.303        | 0.010 (0.001)    | -                | -         |     4.75 | Gizmy, leen, n0te, ryu, shield  |
|            9 |     8011 | 2024-01-14 | Passion UA           | W   | 0.288      | 0.303        | 0.057 (0.005)    | 1.000 (0.087)    | -         |     7.14 | Gizmy, leen, n0te, ryu, shield  |
|            8 |     8207 | 2024-01-11 | Zero Tenacity        | W   | 0.269      | 0.303        | 0.147 (0.012)    | 1.000 (0.082)    | -         |     7.16 | Gizmy, leen, n0te, ryu, shield  |
|            7 |     8439 | 2024-01-08 | The Prodigies        | L   | 0.248      | -            | -                | -                | -         |    -5.98 | Gizmy, leen, n0te, ryu, shield  |
|            6 |     8475 | 2024-01-05 | Nexus Gaming         | W   | 0.230      | 0.303        | -                | 0.857 (0.060)    | -         |     4.88 | Gizmy, leen, n0te, ryu, shield  |
|            5 |     9368 | 2023-12-08 | GamerLegion Academy  | W   | 0.044      | -            | -                | -                | -         |     0.83 | Gizmy, leen, n0te, ryu, shield  |
|            4 |     9436 | 2023-12-07 | Begrip Gaming        | W   | 0.037      | -            | -                | -                | -         |     0.34 | Gizmy, leen, n0te, ryu, shield  |
|            3 |     9498 | 2023-12-06 | Team LRP Poland      | W   | 0.031      | -            | -                | -                | -         |     0.43 | Gizmy, leen, n0te, ryu, shield  |
|            2 |     9586 | 2023-12-05 | SINNERS Academy      | W   | 0.023      | -            | -                | -                | -         |     0.26 | Gizmy, leen, n0te, ryu, shield  |
|            1 |     9620 | 2023-12-04 | Begrip Gaming        | L   | 0.017      | -            | -                | -                | -         |    -0.37 | Gizmy, leen, n0te, ryu, shield  |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($1,969.17)
- Divide that value by the 5th highest value among all rosters ($300,806.11)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-02-09 |      0.463 | $3,000.00      | $1,388.33       |
| 2024-01-20 |      0.328 | $1,500.00      | $492.50         |
| 2023-12-08 |      0.044 | $2,000.00      | $88.33          |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
