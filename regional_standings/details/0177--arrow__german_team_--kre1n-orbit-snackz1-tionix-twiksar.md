### Roster Details<br />
Team Name: ARROW (German team)<br />
Roster: Kre1N, Orbit, SnacKZ1, Tionix, Twiksar<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [177](../standings_global.md)<br />
Regional Rank: [120]( ../standings_europe.md)<br />
Final Rank Value:  749.2<br />
<br />
Final Rank Value (749.2) = Starting Rank Value (694.8) + Head To Head Adjustments (54.4)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.328[<sup>1</sup>](#table2)
- Bounty Collected: 0.226[<sup>2</sup>](#table1)
- Opponent Network: 0.040[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.149<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 694.8
- 400 + ( ( 0.149 - 0.000 ) / ( 0.806 - 0.000 ) ) * 1600 = 694.8


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent                     | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                      |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           21 |      107 | 2024-05-03 | ARCRED                       | L   | 1.000      | -            | -                | -                | -         |    -9.76 | Kre1N, Orbit, SnacKZ1, Tionix, Twiksar      |
|           20 |      178 | 2024-05-01 | SNOGARD Dragons              | W   | 1.000      | 0.143        | 0.009 (0.001)    | 0.117 (0.017)    | 0 (0.000) |    14.59 | Kre1N, Orbit, SnacKZ1, Tionix, Twiksar      |
|           19 |      825 | 2024-04-19 | GenOne                       | W   | 1.000      | 0.371        | 0.000 (0.000)    | 0.323 (0.120)    | 0 (0.000) |     9.98 | Kre1N, Orbit, SnacKZ1, Tionix, Twiksar      |
|           18 |     1212 | 2024-04-10 | Copenhagen Wolves            | W   | 1.000      | 0.371        | 0.000 (0.000)    | 0.417 (0.155)    | 0 (0.000) |    11.41 | Kre1N, Orbit, SnacKZ1, Tionix, Twiksar      |
|           17 |     1288 | 2024-04-09 | Rhyno Esports                | L   | 1.000      | -            | -                | -                | -         |   -10.09 | Kre1N, Orbit, SnacKZ1, Tionix, Twiksar      |
|           16 |     1329 | 2024-04-08 | TeamOrangeGaming             | W   | 1.000      | 0.143        | 0.007 (0.001)    | 0.140 (0.020)    | 0 (0.000) |    18.60 | Kre1N, Orbit, SnacKZ1, Tionix, Twiksar      |
|           15 |     1535 | 2024-04-03 | Sissi State Punks            | W   | 0.985      | 0.143        | 0.009 (0.001)    | 0.191 (0.027)    | 0 (0.000) |    15.95 | Kre1N, Orbit, SnacKZ1, Tionix, Twiksar      |
|           14 |     1811 | 2024-03-26 | Sashi Esport                 | L   | 0.932      | -            | -                | -                | -         |    -3.60 | Kre1N, Orbit, SnacKZ1, Tionix, Twiksar      |
|           13 |     2088 | 2024-03-18 | Turów Zgorzelec Esport       | L   | 0.878      | -            | -                | -                | -         |    -9.39 | AxEcHo, darko, kadziu, Markoś, xKacpersky   |
|           12 |     2121 | 2024-03-17 | TEAM MAX (European mix-team) | W   | 0.872      | 0.333        | 0.000 (0.000)    | 0.116 (0.034)    | 0 (0.000) |     8.21 | kL1o, Malkiss, tAk, tooizera, zecco         |
|           11 |     2209 | 2024-03-15 | Dynamo Eclot                 | L   | 0.859      | -            | -                | -                | -         |    -2.93 | j1NZO, Kre1N, Orbit, Tionix, Twiksar        |
|           10 |     2400 | 2024-03-11 | Team OWL                     | W   | 0.832      | 0.333        | -                | 0.036 (0.010)    | 0 (0.000) |     5.89 | j1NZO, Kre1N, Orbit, Tionix, Twiksar        |
|            9 |     2562 | 2024-03-07 | MST                          | W   | 0.806      | 0.333        | -                | 0.057 (0.015)    | 0 (0.000) |     4.32 | el_strongo, mikult, MQ666MQ, NerouK, wtfmen |
|            8 |     4734 | 2024-01-17 | Guild Eagles                 | L   | 0.472      | -            | -                | -                | -         |    -1.83 | Kre1N, Orbit, S1M, Tionix, Twiksar          |
|            7 |     6360 | 2023-11-27 | ALTERNATE aTTaX              | L   | 0.132      | -            | -                | -                | -         |    -0.44 | DreaM-, Kre1N, Orbit, Tionix, Twiksar       |
|            6 |     6390 | 2023-11-26 | Reveal (German team)         | W   | 0.125      | 0.143        | 0.005 (0.000)    | 0.003 (0.000)    | 0 (0.000) |     1.59 | doxors, j1NZO, janfy, Miku, OneLion         |
|            5 |     6400 | 2023-11-26 | ALTERNATE aTTaX              | L   | 0.124      | -            | -                | -                | -         |    -0.41 | DreaM-, Kre1N, Orbit, Tionix, Twiksar       |
|            4 |     6441 | 2023-11-25 | Reveal (German team)         | W   | 0.117      | 0.143        | 0.005 (0.000)    | -                | 0 (0.000) |     1.51 | doxors, j1NZO, janfy, Miku, OneLion         |
|            3 |     6624 | 2023-11-20 | RED (German team)            | W   | 0.086      | 0.143        | 0.003 (0.000)    | -                | -         |     1.04 | aerax, NaYz, syncD, w1doww, Yoshireax       |
|            2 |     6732 | 2023-11-18 | THE SUSPECT                  | L   | 0.071      | -            | -                | -                | -         |    -1.21 | DreaM-, Kre1N, Orbit, Tionix, Twiksar       |
|            1 |     6742 | 2023-11-18 | Wave Esports                 | W   | 0.070      | 0.242        | 0.004 (0.000)    | 0.113 (0.002)    | -         |     0.94 | DreaM-, Kre1N, Orbit, Tionix, Twiksar       |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($1,426.28)
- Divide that value by the 5th highest value among all rosters ($158,437.64)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-03-23 |      0.912 | $300.00        | $273.69         |
| 2023-12-16 |      0.258 | $4,472.06      | $1,152.59       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
