### Roster Details<br />
Team Name: Eternal Fire Academy<br />
Roster: cyber, Depact, hey, jottAAA, scolleN<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [284](../standings_global.md)<br />
Regional Rank: [176]( ../standings_europe.md)<br />
Final Rank Value:  652.6<br />
<br />
Final Rank Value (652.6) = Starting Rank Value (654.3) + Head To Head Adjustments (-1.6)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.280[<sup>1</sup>](#table2)
- Bounty Collected: 0.198[<sup>2</sup>](#table1)
- Opponent Network: 0.012[<sup>2</sup>](#table1)
- LAN Wins: 0.009[<sup>2</sup>](#table1)

The average of these factors is 0.125<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 654.3
- 400 + ( ( 0.125 - 0.000 ) / ( 0.786 - 0.000 ) ) * 1600 = 654.3


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent           | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                   |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           26 |     5276 | 2024-02-29 | ILIN               | W   | 0.597      | 0.371        | 0.000 (0.000)    | 0.196 (0.043)    | 0 (0.000) |     7.73 | cyber, Depact, hey, jottAAA, scolleN     |
|           25 |     5361 | 2024-02-27 | ENTERPRISE esports | L   | 0.584      | -            | -                | -                | -         |    -2.78 | cyber, Depact, hey, jottAAA, scolleN     |
|           24 |     5542 | 2024-02-24 | GenOne             | L   | 0.563      | -            | -                | -                | -         |   -11.13 | cyber, Depact, hey, jottAAA, scolleN     |
|           23 |     5616 | 2024-02-23 | UNiTY esports      | L   | 0.557      | -            | -                | -                | -         |    -4.02 | cyber, Depact, hey, jottAAA, scolleN     |
|           22 |     5714 | 2024-02-21 | ex-Anonymo Esports | W   | 0.544      | 0.371        | 0.002 (0.001)    | 0.204 (0.041)    | 0 (0.000) |    10.11 | cyber, Depact, hey, jottAAA, scolleN     |
|           21 |     5931 | 2024-02-17 | Zero Tenacity      | L   | 0.518      | -            | -                | -                | -         |    -1.77 | cyber, Depact, hey, jottAAA, scolleN     |
|           20 |     5976 | 2024-02-16 | HOTU               | L   | 0.511      | -            | -                | -                | -         |    -4.04 | cyber, Depact, hey, jottAAA, scolleN     |
|           19 |     6426 | 2024-02-05 | Aurora Young Blud  | L   | 0.437      | -            | -                | -                | -         |    -4.30 | cyber, Depact, hey, jottAAA, scolleN     |
|           18 |     6602 | 2024-02-02 | GenOne             | L   | 0.417      | -            | -                | -                | -         |    -7.20 | cyber, Depact, hey, jottAAA, scolleN     |
|           17 |     6765 | 2024-01-30 | CYBERSHOKE Esports | W   | 0.397      | 0.371        | 0.002 (0.000)    | 0.147 (0.022)    | 0 (0.000) |     7.28 | cyber, Depact, hey, jottAAA, scolleN     |
|           16 |     6860 | 2024-01-28 | Golden Sword       | W   | 0.384      | 0.371        | 0.000 (0.000)    | -                | 0 (0.000) |     2.25 | cyber, Depact, hey, jottAAA, scolleN     |
|           15 |     7031 | 2024-01-26 | gbcxz              | W   | 0.371      | 0.371        | 0.000 (0.000)    | 0.003 (0.000)    | 0 (0.000) |     4.83 | cyber, Depact, hey, jottAAA, scolleN     |
|           14 |     8328 | 2023-12-23 | DEMONS             | L   | 0.144      | -            | -                | -                | -         |    -2.48 | colorzz, cyber, EMSTAR, jottAAA, scolleN |
|           13 |     8460 | 2023-12-17 | L2W Esports        | W   | 0.104      | 0.143        | 0.000 (0.000)    | 0.009 (0.000)    | 0 (0.000) |     1.01 | colorzz, cyber, EMSTAR, jottAAA, scolleN |
|           12 |     8495 | 2023-12-17 | WERSCHIEDEN        | W   | 0.102      | 0.143        | -                | 0.006 (0.000)    | 0 (0.000) |     0.62 | colorzz, cyber, EMSTAR, jottAAA, scolleN |
|           11 |     8503 | 2023-12-17 | 5KARIS             | W   | 0.102      | 0.143        | -                | 0.003 (0.000)    | 0 (0.000) |     0.62 | colorzz, cyber, EMSTAR, jottAAA, scolleN |
|           10 |     8622 | 2023-12-16 | Endpoint           | L   | 0.096      | -            | -                | -                | -         |    -0.50 | colorzz, cyber, EMSTAR, jottAAA, scolleN |
|            9 |     8756 | 2023-12-15 | THE SUSPECT        | W   | 0.089      | 0.373        | 0.001 (0.000)    | 0.008 (0.000)    | 1 (0.089) |     1.23 | colorzz, cyber, EMSTAR, jottAAA, scolleN |
|            8 |     8835 | 2023-12-13 | Passion UA         | L   | 0.077      | -            | -                | -                | -         |    -0.28 | colorzz, cyber, EMSTAR, jottAAA, scolleN |
|            7 |     8880 | 2023-12-12 | XI Esport          | W   | 0.071      | 0.333        | 0.001 (0.000)    | 0.277 (0.007)    | 0 (0.000) |     1.23 | colorzz, cyber, EMSTAR, jottAAA, scolleN |
|            6 |     8914 | 2023-12-11 | gbcxz              | L   | 0.065      | -            | -                | -                | -         |    -1.19 | colorzz, cyber, EMSTAR, jottAAA, scolleN |
|            5 |     9146 | 2023-12-07 | LEON Esports       | W   | 0.038      | 0.333        | 0.001 (0.000)    | 0.564 (0.007)    | -         |     0.76 | colorzz, cyber, EMSTAR, jottAAA, scolleN |
|            4 |     9270 | 2023-12-05 | Oxuji Esports      | W   | 0.025      | -            | -                | -                | -         |     0.15 | colorzz, cyber, EMSTAR, jottAAA, scolleN |
|            3 |     9365 | 2023-12-03 | DEMONS             | W   | 0.010      | 0.242        | 0.002 (0.000)    | -                | -         |     0.14 | colorzz, cyber, EMSTAR, jottAAA, scolleN |
|            2 |     9382 | 2023-12-03 | dos Amigos         | W   | 0.009      | -            | -                | -                | -         |     0.06 | colorzz, cyber, EMSTAR, jottAAA, scolleN |
|            1 |     9401 | 2023-12-03 | GANGSTERS          | W   | 0.008      | -            | -                | -                | -         |     0.05 | colorzz, cyber, EMSTAR, jottAAA, scolleN |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($808.32)
- Divide that value by the 5th highest value among all rosters ($300,806.11)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2023-12-23 |      0.144 | $1,375.03      | $198.61         |
| 2023-12-17 |      0.105 | $300.00        | $31.38          |
| 2023-12-16 |      0.096 | $6,000.00      | $578.33         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
