### Roster Details<br />
Team Name: Eternal Fire Academy<br />
Roster: cyber, Depact, hey, jottAAA, scolleN<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [212](../standings_global.md)<br />
Regional Rank: [141]( ../standings_europe.md)<br />
Final Rank Value:  702.2<br />
<br />
Final Rank Value (702.2) = Starting Rank Value (718.1) + Head To Head Adjustments (-15.9)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.345[<sup>1</sup>](#table2)
- Bounty Collected: 0.241[<sup>2</sup>](#table1)
- Opponent Network: 0.028[<sup>2</sup>](#table1)
- LAN Wins: 0.028[<sup>2</sup>](#table1)

The average of these factors is 0.160<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 718.1
- 400 + ( ( 0.160 - 0.000 ) / ( 0.806 - 0.000 ) ) * 1600 = 718.1


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent                    | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins      | H2H Adj. | Roster                                   |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           25 |     2956 | 2024-02-29 | ILIN                        | W   | 0.758      | 0.371        | 0.000 (0.000)    | 0.348 (0.098)    | false (0.000) |     9.54 | cyber, Depact, hey, jottAAA, scolleN     |
|           24 |     3024 | 2024-02-27 | ENTERPRISE esports          | L   | 0.745      | -            | -                | -                | -             |    -4.52 | cyber, Depact, hey, jottAAA, scolleN     |
|           23 |     3160 | 2024-02-24 | GenOne                      | L   | 0.724      | -            | -                | -                | -             |   -14.92 | cyber, Depact, hey, jottAAA, scolleN     |
|           22 |     3219 | 2024-02-23 | UNiTY esports (Slovak team) | L   | 0.718      | -            | -                | -                | -             |    -5.98 | cyber, Depact, hey, jottAAA, scolleN     |
|           21 |     3308 | 2024-02-21 | Ex-Anonymo Esports          | W   | 0.705      | 0.371        | 0.019 (0.005)    | 0.295 (0.077)    | false (0.000) |    13.03 | cyber, Depact, hey, jottAAA, scolleN     |
|           20 |     3486 | 2024-02-17 | Zero Tenacity               | L   | 0.679      | -            | -                | -                | -             |    -4.97 | cyber, Depact, hey, jottAAA, scolleN     |
|           19 |     3524 | 2024-02-16 | HOTU                        | L   | 0.672      | -            | -                | -                | -             |    -7.96 | cyber, Depact, hey, jottAAA, scolleN     |
|           18 |     3899 | 2024-02-05 | Aurora Young Blud           | L   | 0.598      | -            | -                | -                | -             |    -6.44 | cyber, Depact, hey, jottAAA, scolleN     |
|           17 |     4025 | 2024-02-02 | GenOne                      | L   | 0.578      | -            | -                | -                | -             |   -12.99 | cyber, Depact, hey, jottAAA, scolleN     |
|           16 |     4148 | 2024-01-30 | CYBERSHOKE Esports          | W   | 0.558      | 0.371        | 0.004 (0.001)    | 0.220 (0.046)    | false (0.000) |     8.46 | cyber, Depact, hey, jottAAA, scolleN     |
|           15 |     4211 | 2024-01-28 | Golden Sword                | W   | 0.545      | 0.371        | 0.000 (0.000)    | -                | false (0.000) |     2.33 | cyber, Depact, hey, jottAAA, scolleN     |
|           14 |     4312 | 2024-01-26 | Gbcxz                       | W   | 0.532      | 0.371        | 0.000 (0.000)    | -                | false (0.000) |     2.33 | cyber, Depact, hey, jottAAA, scolleN     |
|           13 |     5269 | 2023-12-23 | DEMONS (Turkish team)       | L   | 0.306      | -            | -                | -                | -             |    -5.53 | colorzz, cyber, EMSTAR, jottAAA, scolleN |
|           12 |     5360 | 2023-12-17 | PCIFIC Espor                | W   | 0.265      | 0.143        | 0.001 (0.000)    | 0.028 (0.001)    | false (0.000) |     2.05 | colorzz, cyber, EMSTAR, jottAAA, scolleN |
|           11 |     5387 | 2023-12-17 | WERSCHIEDEN                 | W   | 0.263      | 0.143        | -                | 0.019 (0.001)    | false (0.000) |     1.17 | colorzz, cyber, EMSTAR, jottAAA, scolleN |
|           10 |     5395 | 2023-12-17 | 5KARIS                      | W   | 0.263      | 0.143        | -                | 0.009 (0.000)    | false (0.000) |     1.15 | colorzz, cyber, EMSTAR, jottAAA, scolleN |
|            9 |     5594 | 2023-12-15 | THE SUSPECT                 | W   | 0.250      | 0.373        | 0.005 (0.000)    | 0.027 (0.003)    | true (0.250)  |     3.30 | colorzz, cyber, EMSTAR, jottAAA, scolleN |
|            8 |     5645 | 2023-12-13 | Passion UA                  | L   | 0.239      | -            | -                | -                | -             |    -1.25 | colorzz, cyber, EMSTAR, jottAAA, scolleN |
|            7 |     5670 | 2023-12-12 | XI Esport                   | W   | 0.232      | 0.333        | 0.002 (0.000)    | 0.313 (0.024)    | false (0.000) |     3.39 | colorzz, cyber, EMSTAR, jottAAA, scolleN |
|            6 |     5871 | 2023-12-07 | LEON Esports                | W   | 0.199      | 0.333        | 0.003 (0.000)    | 0.357 (0.024)    | -             |     2.95 | colorzz, cyber, EMSTAR, jottAAA, scolleN |
|            5 |     5966 | 2023-12-05 | Oxuji Esports               | W   | 0.186      | -            | -                | -                | -             |     0.85 | colorzz, cyber, EMSTAR, jottAAA, scolleN |
|            4 |     6038 | 2023-12-03 | DEMONS (Turkish team)       | W   | 0.171      | 0.242        | 0.007 (0.000)    | 0.045 (0.002)    | -             |     2.37 | colorzz, cyber, EMSTAR, jottAAA, scolleN |
|            3 |     6066 | 2023-12-03 | GANGSTERS (Turkish team)    | W   | 0.169      | -            | -                | -                | -             |     0.79 | colorzz, cyber, EMSTAR, jottAAA, scolleN |
|            2 |     6361 | 2023-11-27 | Sampi NEXT                  | L   | 0.132      | -            | -                | -                | -             |    -3.23 | colorzz, cyber, EMSTAR, jottAAA, scolleN |
|            1 |     6522 | 2023-11-23 | SINNERS Academy             | L   | 0.104      | -            | -                | -                | -             |    -1.79 | colorzz, cyber, EMSTAR, jottAAA, scolleN |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($2,012.42)
- Divide that value by the 5th highest value among all rosters ($158,437.64)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2023-12-23 |      0.306 | $1,375.03      | $420.08         |
| 2023-12-17 |      0.266 | $300.00        | $79.69          |
| 2023-12-15 |      0.252 | $6,000.00      | $1,512.64       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
