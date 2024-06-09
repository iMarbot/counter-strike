### Roster Details<br />
Team Name: AL-QATRAO<br />
Roster: drext, hdstr, Icarus, nesto, shr<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [143](../standings_global.md)<br />
Regional Rank: [100]( ../standings_europe.md)<br />
Final Rank Value:  793.0<br />
<br />
Final Rank Value (793.0) = Starting Rank Value (747.2) + Head To Head Adjustments (45.8)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.317[<sup>1</sup>](#table2)
- Bounty Collected: 0.245[<sup>2</sup>](#table1)
- Opponent Network: 0.016[<sup>2</sup>](#table1)
- LAN Wins: 0.106[<sup>2</sup>](#table1)

The average of these factors is 0.171<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 747.2
- 400 + ( ( 0.171 - 0.000 ) / ( 0.787 - 0.000 ) ) * 1600 = 747.2


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent        | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                 |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           20 |     1385 | 2024-05-12 | Rhyno Esports   | L   | 1.000      | -            | -                | -                | -         |    -8.20 | drext, hdstr, Icarus, nesto, shr       |
|           19 |     1456 | 2024-05-11 | esmagaB         | W   | 1.000      | 0.143        | 0.008 (0.001)    | 0.564 (0.081)    | 1 (1.000) |    17.09 | drext, hdstr, Icarus, nesto, shr       |
|           18 |     1833 | 2024-05-04 | GTZ.ESPORTS     | W   | 1.000      | 0.143        | 0.000 (0.000)    | 0.070 (0.010)    | 0 (0.000) |     3.51 | drext, hdstr, Icarus, nesto, shr       |
|           17 |     1875 | 2024-05-04 | SAW Youngsters  | W   | 1.000      | 0.143        | 0.000 (0.000)    | 0.028 (0.004)    | 0 (0.000) |     3.12 | drext, hdstr, Icarus, nesto, shr       |
|           16 |     1903 | 2024-05-03 | NeverPlay       | W   | 1.000      | 0.143        | 0.000 (0.000)    | -                | 0 (0.000) |     3.39 | drext, hdstr, Icarus, nesto, shr       |
|           15 |     2632 | 2024-04-20 | ALL-IN          | W   | 0.937      | 0.143        | 0.002 (0.000)    | 0.026 (0.003)    | 0 (0.000) |     6.41 | drext, hdstr, Icarus, nesto, shr       |
|           14 |     2640 | 2024-04-20 | ABT Esports     | W   | 0.936      | 0.143        | 0.000 (0.000)    | 0.153 (0.020)    | 0 (0.000) |     5.72 | drext, hdstr, Icarus, nesto, shr       |
|           13 |     2652 | 2024-04-20 | Lx Soldiers     | W   | 0.936      | 0.143        | 0.000 (0.000)    | -                | 0 (0.000) |     3.26 | drext, hdstr, Icarus, nesto, shr       |
|           12 |     5331 | 2024-03-02 | Rhyno Esports   | L   | 0.610      | -            | -                | -                | -         |    -4.64 | drext, hdstr, Icarus, nesto, shr       |
|           11 |     5810 | 2024-02-22 | OVERFRAG        | W   | 0.551      | 0.143        | 0.002 (0.000)    | 0.046 (0.004)    | 0 (0.000) |     5.46 | drext, hdstr, Icarus, nesto, shr       |
|           10 |     5922 | 2024-02-20 | The Agency Clan | W   | 0.538      | 0.143        | 0.000 (0.000)    | -                | 0 (0.000) |     3.35 | drext, hdstr, Icarus, nesto, shr       |
|            9 |     5924 | 2024-02-20 | GTZ.ESPORTS     | W   | 0.537      | 0.143        | -                | 0.070 (0.005)    | 0 (0.000) |     1.99 | drext, hdstr, Icarus, nesto, shr       |
|            8 |     6106 | 2024-02-17 | Enigma Esports  | W   | 0.518      | 0.143        | -                | 0.045 (0.003)    | -         |     2.79 | drext, frozzen, hdstr, shr, snowiee    |
|            7 |     6870 | 2024-02-01 | SAW             | L   | 0.411      | -            | -                | -                | -         |    -0.42 | drext, frozzen, hdstr, nesto, shr      |
|            6 |     6879 | 2024-02-01 | esmagaB         | L   | 0.410      | -            | -                | -                | -         |    -4.70 | drext, frozzen, hdstr, nesto, shr      |
|            5 |     6883 | 2024-02-01 | SAW             | W   | 0.410      | 0.143        | 0.112 (0.007)    | 0.388 (0.023)    | -         |    12.53 | drext, frozzen, hdstr, nesto, shr      |
|            4 |     7084 | 2024-01-28 | camarinha       | W   | 0.384      | -            | -                | -                | -         |     1.60 | drext, frozzen, Icarus, nesto, snowiee |
|            3 |     7098 | 2024-01-28 | ARMARIOS        | W   | 0.383      | -            | -                | -                | -         |     1.57 | drext, frozzen, Icarus, nesto, snowiee |
|            2 |     7187 | 2024-01-27 | The Agency Clan | L   | 0.377      | -            | -                | -                | -         |    -9.48 | frozzen, hdstr, nesto, shr, snowiee    |
|            1 |     7198 | 2024-01-27 | GTZ.ESPORTS     | W   | 0.377      | 0.143        | -                | 0.070 (0.004)    | -         |     1.49 | frozzen, hdstr, nesto, shr, snowiee    |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($2,119.67)
- Divide that value by the 5th highest value among all rosters ($300,806.11)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-05-12 |      1.000 | $1,618.05      | $1,618.05       |
| 2024-03-03 |      0.616 | $813.80        | $501.62         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
