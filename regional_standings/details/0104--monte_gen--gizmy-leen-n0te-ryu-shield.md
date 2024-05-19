### Roster Details<br />
Team Name: Monte Gen<br />
Roster: Gizmy, leen, n0te, ryu, shield<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [104](../standings_global.md)<br />
Regional Rank: [76]( ../standings_europe.md)<br />
Final Rank Value:  854.2<br />
<br />
Final Rank Value (854.2) = Starting Rank Value (798.1) + Head To Head Adjustments (56.2)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.368[<sup>1</sup>](#table2)
- Bounty Collected: 0.335[<sup>2</sup>](#table1)
- Opponent Network: 0.100[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.201<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 798.1
- 400 + ( ( 0.201 - 0.000 ) / ( 0.806 - 0.000 ) ) * 1600 = 798.1


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent             | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                         |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           18 |     3800 | 2024-02-09 | Betera Esports       | L   | 0.624      | -            | -                | -                | -         |   -10.37 | Gizmy, leen, n0te, ryu, shield |
|           17 |     3830 | 2024-02-08 | Passion UA           | W   | 0.617      | 0.333        | 0.114 (0.024)    | 0.980 (0.202)    | 0 (0.000) |    12.69 | Gizmy, leen, n0te, ryu, shield |
|           16 |     4122 | 2024-01-31 | MOUZ NXT             | W   | 0.564      | 0.333        | 0.215 (0.040)    | 1.000 (0.188)    | 0 (0.000) |    14.27 | Gizmy, leen, n0te, ryu, shield |
|           15 |     4203 | 2024-01-29 | Team Secret          | W   | 0.550      | 0.333        | -                | 0.368 (0.067)    | 0 (0.000) |     4.32 | Gizmy, leen, n0te, ryu, shield |
|           14 |     4570 | 2024-01-20 | MOUZ NXT             | L   | 0.489      | -            | -                | -                | -         |    -2.90 | Gizmy, leen, n0te, ryu, shield |
|           13 |     4675 | 2024-01-18 | WOPA Esport          | W   | 0.477      | 0.303        | 0.009 (0.001)    | 0.485 (0.070)    | 0 (0.000) |     6.06 | Gizmy, leen, n0te, ryu, shield |
|           12 |     4817 | 2024-01-16 | Natus Vincere Junior | W   | 0.464      | 0.303        | 0.025 (0.003)    | 0.492 (0.069)    | 0 (0.000) |     7.34 | Gizmy, leen, n0te, ryu, shield |
|           11 |     4870 | 2024-01-14 | Passion UA           | W   | 0.450      | 0.303        | 0.114 (0.016)    | 0.980 (0.133)    | 0 (0.000) |    10.23 | Gizmy, leen, n0te, ryu, shield |
|           10 |     5011 | 2024-01-11 | Zero Tenacity        | W   | 0.430      | 0.303        | 0.095 (0.012)    | 1.000 (0.130)    | 0 (0.000) |     9.16 | Gizmy, leen, n0te, ryu, shield |
|            9 |     5157 | 2024-01-08 | The Prodigies        | L   | 0.409      | -            | -                | -                | -         |    -9.91 | Gizmy, leen, n0te, ryu, shield |
|            8 |     5185 | 2024-01-05 | Nexus Gaming         | W   | 0.391      | 0.303        | 0.031 (0.004)    | 0.772 (0.091)    | 0 (0.000) |     8.08 | Gizmy, leen, n0te, ryu, shield |
|            7 |     5832 | 2023-12-08 | GamerLegion Academy  | W   | 0.205      | 0.289        | 0.043 (0.003)    | 0.567 (0.034)    | 0 (0.000) |     3.91 | Gizmy, leen, n0te, ryu, shield |
|            6 |     5883 | 2023-12-07 | Begrip Gaming        | W   | 0.199      | -            | -                | -                | 0 (0.000) |     1.85 | Gizmy, leen, n0te, ryu, shield |
|            5 |     5926 | 2023-12-06 | FALKE ESPORTS        | W   | 0.192      | -            | -                | -                | -         |     0.98 | Gizmy, leen, n0te, ryu, shield |
|            4 |     5994 | 2023-12-05 | SINNERS Academy      | W   | 0.184      | 0.289        | 0.003 (0.000)    | 0.296 (0.016)    | -         |     2.05 | Gizmy, leen, n0te, ryu, shield |
|            3 |     6018 | 2023-12-04 | Begrip Gaming        | L   | 0.178      | -            | -                | -                | -         |    -3.97 | Gizmy, leen, n0te, ryu, shield |
|            2 |     6157 | 2023-12-01 | SINNERS Academy      | W   | 0.159      | 0.289        | 0.003 (0.000)    | -                | -         |     1.74 | Gizmy, leen, n0te, ryu, shield |
|            1 |     6398 | 2023-11-26 | Team 7AM             | W   | 0.124      | -            | -                | -                | -         |     0.60 | Gizmy, leen, n0te, ryu, shield |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($3,016.09)
- Divide that value by the 5th highest value among all rosters ($158,437.64)
- The final value (0.02) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-02-09 |      0.624 | $3,000.00      | $1,871.53       |
| 2024-01-20 |      0.489 | $1,500.00      | $734.10         |
| 2023-12-08 |      0.205 | $2,000.00      | $410.46         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
