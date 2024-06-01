### Roster Details<br />
Team Name: Monte Gen<br />
Roster: fnl, Gizmy, leen, ryu, shield<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [106](../standings_global.md)<br />
Regional Rank: [75]( ../standings_europe.md)<br />
Final Rank Value:  858.7<br />
<br />
Final Rank Value (858.7) = Starting Rank Value (771.1) + Head To Head Adjustments (87.6)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.314[<sup>1</sup>](#table2)
- Bounty Collected: 0.315[<sup>2</sup>](#table1)
- Opponent Network: 0.100[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.182<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 771.1
- 400 + ( ( 0.182 - 0.000 ) / ( 0.786 - 0.000 ) ) * 1600 = 771.1


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
|           28 |      175 | 2024-05-27 | Young Ninjas         | W   | 1.000      | 0.333        | 0.043 (0.014)    | 0.372 (0.124)    | 0 (0.000) |    18.18 | fnl, Gizmy, leen, ryu, shield   |
|           27 |      223 | 2024-05-26 | Reason Gaming        | W   | 1.000      | 0.333        | 0.004 (0.001)    | 0.133 (0.044)    | 0 (0.000) |    10.86 | fnl, Gizmy, leen, ryu, shield   |
|           26 |      398 | 2024-05-23 | Preasy Esport        | W   | 1.000      | 0.333        | 0.008 (0.003)    | 0.642 (0.214)    | 0 (0.000) |    11.04 | fnl, Gizmy, leen, ryu, shield   |
|           25 |      587 | 2024-05-21 | Nexus Gaming         | L   | 1.000      | -            | -                | -                | -         |   -14.70 | fnl, Gizmy, leen, ryu, shield   |
|           24 |      740 | 2024-05-19 | WinX                 | W   | 1.000      | -            | -                | -                | 0 (0.000) |     3.36 | fnl, Gizmy, leen, ryu, shield   |
|           23 |      759 | 2024-05-19 | Grannys Knockers     | W   | 1.000      | 0.143        | 0.006 (0.001)    | 0.355 (0.051)    | 0 (0.000) |    14.73 | fnl, Gizmy, leen, ryu, shield   |
|           22 |      767 | 2024-05-19 | REDPack Esports      | W   | 1.000      | -            | -                | -                | 0 (0.000) |     4.97 | fnl, Gizmy, leen, ryu, shield   |
|           21 |      791 | 2024-05-19 | Virtuoso Squad       | W   | 1.000      | -            | -                | -                | 0 (0.000) |     4.94 | fnl, Gizmy, leen, ryu, shield   |
|           20 |      904 | 2024-05-18 | VOLT                 | W   | 1.000      | -            | -                | -                | 0 (0.000) |     3.10 | fnl, Gizmy, leen, ryu, shield   |
|           19 |     1525 | 2024-05-10 | 9Pandas              | L   | 1.000      | -            | -                | -                | -         |    -5.42 | AiyvaN, leen, n0te, ryu, shield |
|           18 |     5408 | 2024-02-26 | brazylijski luz      | L   | 0.578      | -            | -                | -                | -         |    -9.88 | Gizmy, leen, n0te, ryu, shield  |
|           17 |     6309 | 2024-02-09 | Betera Esports       | L   | 0.463      | -            | -                | -                | -         |    -7.03 | Gizmy, leen, n0te, ryu, shield  |
|           16 |     6341 | 2024-02-08 | Passion UA           | W   | 0.456      | 0.333        | 0.057 (0.009)    | 1.000 (0.152)    | 0 (0.000) |    10.32 | Gizmy, leen, n0te, ryu, shield  |
|           15 |     6393 | 2024-02-06 | ex-Anonymo Esports   | W   | 0.442      | -            | -                | -                | 0 (0.000) |     5.82 | Gizmy, leen, n0te, ryu, shield  |
|           14 |     6732 | 2024-01-31 | MOUZ NXT             | W   | 0.403      | 0.333        | 0.157 (0.021)    | 0.950 (0.127)    | -         |    10.71 | Gizmy, leen, n0te, ryu, shield  |
|           13 |     6843 | 2024-01-29 | Team Secret          | W   | 0.389      | -            | -                | -                | -         |     3.32 | Gizmy, leen, n0te, ryu, shield  |
|           12 |     7365 | 2024-01-20 | MOUZ NXT             | L   | 0.328      | -            | -                | -                | -         |    -1.48 | Gizmy, leen, n0te, ryu, shield  |
|           11 |     7491 | 2024-01-18 | WOPA Esport          | W   | 0.316      | 0.303        | -                | 0.594 (0.057)    | -         |     5.21 | Gizmy, leen, n0te, ryu, shield  |
|           10 |     7686 | 2024-01-16 | Natus Vincere Junior | W   | 0.302      | 0.303        | 0.010 (0.001)    | -                | -         |     4.76 | Gizmy, leen, n0te, ryu, shield  |
|            9 |     7758 | 2024-01-14 | Passion UA           | W   | 0.288      | 0.303        | 0.057 (0.005)    | 1.000 (0.087)    | -         |     7.07 | Gizmy, leen, n0te, ryu, shield  |
|            8 |     7954 | 2024-01-11 | Zero Tenacity        | W   | 0.269      | 0.303        | 0.147 (0.012)    | 1.000 (0.082)    | -         |     7.16 | Gizmy, leen, n0te, ryu, shield  |
|            7 |     8184 | 2024-01-08 | The Prodigies        | L   | 0.248      | -            | -                | -                | -         |    -5.97 | Gizmy, leen, n0te, ryu, shield  |
|            6 |     8220 | 2024-01-05 | Nexus Gaming         | W   | 0.230      | 0.303        | 0.014 (0.001)    | 0.825 (0.057)    | -         |     5.06 | Gizmy, leen, n0te, ryu, shield  |
|            5 |     9100 | 2023-12-08 | GamerLegion Academy  | W   | 0.044      | -            | -                | -                | -         |     0.82 | Gizmy, leen, n0te, ryu, shield  |
|            4 |     9163 | 2023-12-07 | Begrip Gaming        | W   | 0.037      | -            | -                | -                | -         |     0.34 | Gizmy, leen, n0te, ryu, shield  |
|            3 |     9217 | 2023-12-06 | Team LRP Poland      | W   | 0.031      | -            | -                | -                | -         |     0.43 | Gizmy, leen, n0te, ryu, shield  |
|            2 |     9304 | 2023-12-05 | SINNERS Academy      | W   | 0.023      | -            | -                | -                | -         |     0.26 | Gizmy, leen, n0te, ryu, shield  |
|            1 |     9338 | 2023-12-04 | Begrip Gaming        | L   | 0.017      | -            | -                | -                | -         |    -0.37 | Gizmy, leen, n0te, ryu, shield  |

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
