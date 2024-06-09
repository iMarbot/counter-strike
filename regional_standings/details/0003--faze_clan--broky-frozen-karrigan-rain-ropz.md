### Roster Details<br />
Team Name: FaZe Clan<br />
Roster: broky, frozen, karrigan, rain, ropz<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [3](../standings_global.md)<br />
Regional Rank: [3]( ../standings_europe.md)<br />
Final Rank Value:  1935.3<br />
<br />
Final Rank Value (1935.3) = Starting Rank Value (2000.0) + Head To Head Adjustments (-64.7)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 1.000[<sup>1</sup>](#table2)
- Bounty Collected: 0.790[<sup>2</sup>](#table1)
- Opponent Network: 0.359[<sup>2</sup>](#table1)
- LAN Wins: 1.000[<sup>2</sup>](#table1)

The average of these factors is 0.787<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 2000.0
- 400 + ( ( 0.787 - 0.000 ) / ( 0.787 - 0.000 ) ) * 1600 = 2000.0


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent          | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                              |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           43 |       40 | 2024-05-29 | Team Spirit       | L   | 1.000      | -            | -                | -                | -         |   -15.89 | broky, frozen, karrigan, rain, ropz |
|           42 |      117 | 2024-05-28 | Virtus.pro        | W   | 1.000      | -            | -                | -                | 1 (1.000) |     4.77 | broky, frozen, karrigan, rain, ropz |
|           41 |      162 | 2024-05-27 | M80               | W   | 1.000      | 0.624        | -                | 0.525 (0.327)    | 1 (1.000) |     0.77 | broky, frozen, karrigan, rain, ropz |
|           40 |     1511 | 2024-05-10 | Team Vitality     | L   | 1.000      | -            | -                | -                | -         |   -20.83 | broky, frozen, karrigan, rain, ropz |
|           39 |     1626 | 2024-05-08 | Natus Vincere     | W   | 1.000      | 0.889        | 1.000 (0.889)    | -                | 1 (1.000) |    11.14 | broky, frozen, karrigan, rain, ropz |
|           38 |     1686 | 2024-05-07 | Monte             | W   | 1.000      | 0.889        | -                | 0.387 (0.344)    | 1 (1.000) |     0.62 | broky, frozen, karrigan, rain, ropz |
|           37 |     2296 | 2024-04-26 | Eternal Fire      | W   | 0.977      | 0.889        | 1.000 (0.868)    | 0.402 (0.349)    | 1 (0.977) |     9.08 | broky, frozen, karrigan, rain, ropz |
|           36 |     2344 | 2024-04-25 | Virtus.pro        | W   | 0.970      | 0.889        | -                | 0.331 (0.286)    | 1 (0.970) |     4.95 | broky, frozen, karrigan, rain, ropz |
|           35 |     2413 | 2024-04-24 | Astralis          | L   | 0.964      | -            | -                | -                | -         |   -24.84 | broky, frozen, karrigan, rain, ropz |
|           34 |     2458 | 2024-04-23 | Imperial Esports  | W   | 0.957      | 0.889        | 0.372 (0.317)    | 0.582 (0.495)    | 1 (0.957) |     1.77 | broky, frozen, karrigan, rain, ropz |
|           33 |     3057 | 2024-04-14 | MOUZ              | W   | 0.895      | 0.624        | 1.000 (0.559)    | -                | 1 (0.895) |    14.55 | broky, frozen, karrigan, rain, ropz |
|           32 |     3115 | 2024-04-13 | Astralis          | W   | 0.889      | -            | -                | -                | 1 (0.889) |     4.59 | broky, frozen, karrigan, rain, ropz |
|           31 |     3156 | 2024-04-12 | Team Liquid       | W   | 0.882      | 0.624        | 0.493 (0.271)    | 0.621 (0.342)    | 1 (0.882) |     4.06 | broky, frozen, karrigan, rain, ropz |
|           30 |     3271 | 2024-04-10 | FlyQuest          | W   | 0.869      | -            | -                | -                | -         |     1.61 | broky, frozen, karrigan, rain, ropz |
|           29 |     3290 | 2024-04-09 | Cloud9            | W   | 0.867      | -            | -                | -                | -         |     2.54 | broky, frozen, karrigan, rain, ropz |
|           28 |     3348 | 2024-04-09 | Astralis          | L   | 0.861      | -            | -                | -                | -         |   -23.28 | broky, frozen, karrigan, rain, ropz |
|           27 |     3394 | 2024-04-08 | Nemiga Gaming     | W   | 0.855      | 0.624        | -                | 0.895 (0.478)    | -         |     0.35 | broky, frozen, karrigan, rain, ropz |
|           26 |     3734 | 2024-03-31 | Natus Vincere     | L   | 0.804      | -            | -                | -                | -         |   -16.03 | broky, frozen, karrigan, rain, ropz |
|           25 |     3763 | 2024-03-30 | Team Vitality     | W   | 0.797      | 1.000        | 0.696 (0.554)    | 0.320 (0.255)    | -         |     7.62 | broky, frozen, karrigan, rain, ropz |
|           24 |     3829 | 2024-03-28 | Team Spirit       | W   | 0.784      | 1.000        | 1.000 (0.784)    | 0.354 (0.278)    | -         |    11.28 | broky, frozen, karrigan, rain, ropz |
|           23 |     4046 | 2024-03-24 | Complexity Gaming | W   | 0.756      | -            | -                | -                | -         |     2.20 | broky, frozen, karrigan, rain, ropz |
|           22 |     4107 | 2024-03-23 | Imperial Esports  | W   | 0.749      | 1.000        | 0.372 (0.279)    | 0.582 (0.436)    | -         |     1.64 | broky, frozen, karrigan, rain, ropz |
|           21 |     4139 | 2024-03-22 | Eternal Fire      | L   | 0.743      | -            | -                | -                | -         |   -15.65 | broky, frozen, karrigan, rain, ropz |
|           20 |     4163 | 2024-03-21 | FURIA Esports     | W   | 0.738      | -            | -                | -                | -         |     1.05 | broky, frozen, karrigan, rain, ropz |
|           19 |     4193 | 2024-03-21 | HEROIC            | L   | 0.737      | -            | -                | -                | -         |   -18.43 | broky, frozen, karrigan, rain, ropz |
|           18 |     6170 | 2024-02-16 | Eternal Fire      | W   | 0.510      | -            | -                | -                | -         |     4.90 | broky, frozen, karrigan, rain, ropz |
|           17 |     6238 | 2024-02-15 | G2 Esports        | L   | 0.503      | -            | -                | -                | -         |   -11.66 | broky, frozen, karrigan, rain, ropz |
|           16 |     6274 | 2024-02-14 | Team Falcons      | W   | 0.497      | -            | -                | -                | -         |     0.96 | broky, frozen, karrigan, rain, ropz |
|           15 |     6310 | 2024-02-14 | 9Pandas           | W   | 0.496      | -            | -                | -                | -         |     0.16 | broky, frozen, karrigan, rain, ropz |
|           14 |     6432 | 2024-02-11 | Team Spirit       | L   | 0.477      | -            | -                | -                | -         |    -9.32 | broky, frozen, karrigan, rain, ropz |
|           13 |     6461 | 2024-02-10 | MOUZ              | W   | 0.470      | 1.000        | 1.000 (0.470)    | -                | -         |     6.80 | broky, frozen, karrigan, rain, ropz |
|           12 |     6489 | 2024-02-09 | G2 Esports        | W   | 0.463      | -            | -                | -                | -         |     3.68 | broky, frozen, karrigan, rain, ropz |
|           11 |     6576 | 2024-02-06 | Team Spirit       | L   | 0.443      | -            | -                | -                | -         |    -8.83 | broky, frozen, karrigan, rain, ropz |
|           10 |     6652 | 2024-02-04 | Eternal Fire      | W   | 0.431      | 1.000        | 1.000 (0.431)    | -                | -         |     4.21 | broky, frozen, karrigan, rain, ropz |
|            9 |     6742 | 2024-02-03 | Rebels Gaming     | W   | 0.423      | -            | -                | -                | -         |     0.09 | broky, frozen, karrigan, rain, ropz |
|            8 |     7181 | 2024-01-27 | Team Liquid       | W   | 0.377      | -            | -                | -                | -         |     1.59 | broky, frozen, karrigan, rain, ropz |
|            7 |     7257 | 2024-01-26 | GamerLegion       | W   | 0.370      | -            | -                | -                | -         |     0.16 | broky, frozen, karrigan, rain, ropz |
|            6 |     7314 | 2024-01-25 | Team Spirit       | W   | 0.363      | -            | -                | -                | -         |     4.18 | broky, frozen, karrigan, rain, ropz |
|            5 |     7375 | 2024-01-24 | GamerLegion       | L   | 0.356      | -            | -                | -                | -         |   -11.06 | broky, frozen, karrigan, rain, ropz |
|            4 |     8734 | 2023-12-17 | Team Vitality     | L   | 0.103      | -            | -                | -                | -         |    -2.28 | broky, frozen, karrigan, rain, ropz |
|            3 |     8897 | 2023-12-16 | MOUZ              | W   | 0.096      | -            | -                | -                | -         |     1.41 | broky, frozen, karrigan, rain, ropz |
|            2 |     9055 | 2023-12-14 | G2 Esports        | W   | 0.083      | -            | -                | -                | -         |     0.66 | broky, frozen, karrigan, rain, ropz |
|            1 |     9116 | 2023-12-13 | Heroic            | W   | 0.075      | -            | -                | -                | -         |     0.00 | broky, frozen, karrigan, rain, ropz |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($378,431.83)
- Divide that value by the 5th highest value among all rosters ($300,806.11)
- The final value (1.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-05-12 |      1.000 | $32,000.00     | $32,000.00      |
| 2024-04-14 |      0.895 | $100,000.00    | $89,516.20      |
| 2024-03-31 |      0.804 | $170,000.00    | $136,661.11     |
| 2024-02-11 |      0.477 | $180,000.00    | $85,850.00      |
| 2024-01-28 |      0.384 | $22,500.00     | $8,640.63       |
| 2023-12-17 |      0.103 | $250,000.00    | $25,763.89      |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
