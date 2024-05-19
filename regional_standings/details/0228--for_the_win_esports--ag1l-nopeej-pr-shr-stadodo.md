### Roster Details<br />
Team Name: For The Win Esports<br />
Roster: Ag1l, NOPEEj, pr, shr, stadodo<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [228](../standings_global.md)<br />
Regional Rank: [149]( ../standings_europe.md)<br />
Final Rank Value:  682.4<br />
<br />
Final Rank Value (682.4) = Starting Rank Value (672.4) + Head To Head Adjustments (9.9)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.274[<sup>1</sup>](#table2)
- Bounty Collected: 0.239[<sup>2</sup>](#table1)
- Opponent Network: 0.009[<sup>2</sup>](#table1)
- LAN Wins: 0.028[<sup>2</sup>](#table1)

The average of these factors is 0.137<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 672.4
- 400 + ( ( 0.137 - 0.000 ) / ( 0.806 - 0.000 ) ) * 1600 = 672.4


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent      | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins      | H2H Adj. | Roster                         |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           24 |     6212 | 2023-11-30 | BIG Academy   | L   | 0.151      | -            | -                | -                | -             |    -1.51 | Ag1l, NOPEEj, pr, shr, stadodo |
|           23 |     6320 | 2023-11-28 | L&G           | L   | 0.138      | -            | -                | -                | -             |    -3.26 | Ag1l, NOPEEj, pr, shr, stadodo |
|           22 |     6359 | 2023-11-27 | DMS           | W   | 0.132      | 0.371        | -                | 0.504 (0.025)    | false (0.000) |     1.85 | Ag1l, NOPEEj, pr, shr, stadodo |
|           21 |     6366 | 2023-11-27 | The Witchers  | W   | 0.132      | 0.371        | 0.035 (0.002)    | 0.158 (0.008)    | false (0.000) |     2.65 | Ag1l, NOPEEj, pr, shr, stadodo |
|           20 |     6494 | 2023-11-24 | Rhyno Esports | L   | 0.110      | -            | -                | -                | -             |    -0.66 | Ag1l, NOPEEj, pr, shr, stadodo |
|           19 |     6528 | 2023-11-23 | Rhyno Esports | W   | 0.104      | 0.143        | 0.047 (0.001)    | 0.446 (0.007)    | true (0.104)  |     2.68 | Ag1l, NOPEEj, pr, shr, stadodo |
|           18 |     6553 | 2023-11-22 | Verdant       | W   | 0.099      | 0.371        | 0.027 (0.001)    | 0.662 (0.024)    | false (0.000) |     2.67 | Ag1l, NOPEEj, pr, shr, stadodo |
|           17 |     6593 | 2023-11-21 | Lilmix        | W   | 0.092      | 0.371        | -                | 0.098 (0.003)    | false (0.000) |     1.58 | Ag1l, NOPEEj, pr, shr, stadodo |
|           16 |     6596 | 2023-11-21 | Underrated    | L   | 0.091      | -            | -                | -                | -             |    -2.16 | Ag1l, NOPEEj, pr, shr, stadodo |
|           15 |     6619 | 2023-11-20 | BAKS Esports  | W   | 0.086      | 0.371        | 0.003 (0.000)    | 0.084 (0.003)    | false (0.000) |     1.26 | Ag1l, NOPEEj, pr, shr, stadodo |
|           14 |     6639 | 2023-11-20 | Los Alpacas   | W   | 0.085      | 0.371        | 0.002 (0.000)    | -                | false (0.000) |     1.20 | Ag1l, NOPEEj, pr, shr, stadodo |
|           13 |     6668 | 2023-11-19 | Rhyno Esports | L   | 0.078      | -            | -                | -                | -             |    -0.45 | Ag1l, NOPEEj, pr, shr, stadodo |
|           12 |     6681 | 2023-11-19 | Pompa Team    | L   | 0.077      | -            | -                | -                | -             |    -1.73 | Ag1l, NOPEEj, pr, shr, stadodo |
|           11 |     6704 | 2023-11-18 | Rhyno Esports | W   | 0.072      | 0.143        | 0.047 (0.000)    | 0.446 (0.005)    | true (0.072)  |     1.86 | Ag1l, NOPEEj, pr, shr, stadodo |
|           10 |     6734 | 2023-11-18 | Los Alpacas   | W   | 0.070      | 0.143        | 0.002 (0.000)    | -                | true (0.070)  |     1.00 | Ag1l, NOPEEj, pr, shr, stadodo |
|            9 |     6764 | 2023-11-17 | FORZE Esports | L   | 0.066      | -            | -                | -                | -             |    -0.73 | Ag1l, NOPEEj, pr, shr, stadodo |
|            8 |     6832 | 2023-11-16 | Apeks         | W   | 0.058      | 0.143        | 0.253 (0.002)    | 0.459 (0.004)    | false (0.000) |     1.78 | Ag1l, NOPEEj, pr, shr, stadodo |
|            7 |     6865 | 2023-11-15 | INGLORIOUS    | W   | 0.052      | 0.143        | 0.005 (0.000)    | 0.358 (0.003)    | -             |     1.08 | Ag1l, NOPEEj, pr, shr, stadodo |
|            6 |     6866 | 2023-11-15 | PARTIZAN      | W   | 0.052      | -            | -                | -                | -             |     0.43 | Ag1l, NOPEEj, pr, shr, stadodo |
|            5 |     6875 | 2023-11-15 | 00 Nation     | W   | 0.052      | -            | -                | -                | -             |     0.46 | Ag1l, NOPEEj, pr, shr, stadodo |
|            4 |     6939 | 2023-11-14 | Verdant       | W   | 0.043      | 0.333        | 0.027 (0.000)    | 0.662 (0.010)    | -             |     1.18 | Ag1l, NOPEEj, pr, shr, stadodo |
|            3 |     6955 | 2023-11-13 | Pompa Team    | L   | 0.039      | -            | -                | -                | -             |    -0.87 | Ag1l, NOPEEj, pr, shr, stadodo |
|            2 |     7011 | 2023-11-12 | Pera Esports  | L   | 0.031      | -            | -                | -                | -             |    -0.45 | Ag1l, NOPEEj, pr, shr, stadodo |
|            1 |     7170 | 2023-11-08 | Viperio       | W   | 0.006      | -            | -                | -                | -             |     0.07 | Ag1l, NOPEEj, pr, shr, stadodo |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($352.21)
- Divide that value by the 5th highest value among all rosters ($158,437.64)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2023-11-25 |      0.118 | $1,368.66      | $160.94         |
| 2023-11-19 |      0.078 | $2,456.20      | $191.27         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
