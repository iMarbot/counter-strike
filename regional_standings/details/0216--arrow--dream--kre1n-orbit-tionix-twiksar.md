### Roster Details<br />
Team Name: ARROW<br />
Roster: DreaM-, Kre1N, Orbit, Tionix, Twiksar<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [216](../standings_global.md)<br />
Regional Rank: [145]( ../standings_europe.md)<br />
Final Rank Value:  709.7<br />
<br />
Final Rank Value (709.7) = Starting Rank Value (709.0) + Head To Head Adjustments (0.7)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.264[<sup>1</sup>](#table2)
- Bounty Collected: 0.248[<sup>2</sup>](#table1)
- Opponent Network: 0.096[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.152<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 709.0
- 400 + ( ( 0.152 - 0.000 ) / ( 0.787 - 0.000 ) ) * 1600 = 709.0


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent                  | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                      |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           29 |      290 | 2024-05-25 | Sissi State Punks         | L   | 1.000      | -            | -                | -                | -         |   -17.74 | DreaM-, Kre1N, Orbit, Tionix, Twiksar       |
|           28 |      340 | 2024-05-24 | GamerLegion Academy       | L   | 1.000      | -            | -                | -                | -         |   -14.33 | Kre1N, MRC9, Orbit, Tionix, Twiksar         |
|           27 |      410 | 2024-05-23 | ALTERNATE aTTaX           | L   | 1.000      | -            | -                | -                | -         |    -9.25 | DreaM-, Kre1N, Orbit, Tionix, Twiksar       |
|           26 |      460 | 2024-05-22 | EVOPLAY                   | W   | 1.000      | 0.143        | 0.000 (0.000)    | -                | 0 (0.000) |     8.46 | DreaM-, Kre1N, Orbit, Tionix, Twiksar       |
|           25 |      593 | 2024-05-21 | ADEPTS                    | W   | 1.000      | 0.372        | 0.005 (0.002)    | 0.291 (0.108)    | 0 (0.000) |    15.63 | Kre1N, MRC9, Orbit, Tionix, Twiksar         |
|           24 |      668 | 2024-05-20 | Endpoint                  | W   | 1.000      | 0.372        | 0.012 (0.004)    | 0.770 (0.287)    | 0 (0.000) |    22.39 | Kre1N, MRC9, Orbit, Tionix, Twiksar         |
|           23 |      707 | 2024-05-20 | mYinsanity                | L   | 1.000      | -            | -                | -                | -         |   -19.61 | DreaM-, Kre1N, Orbit, Tionix, Twiksar       |
|           22 |     1097 | 2024-05-16 | Tropic                    | W   | 1.000      | 0.354        | 0.000 (0.000)    | -                | 0 (0.000) |     8.48 | Kre1N, Orbit, P4TriCK, Tionix, Twiksar      |
|           21 |     1147 | 2024-05-15 | VaselineWorms             | L   | 1.000      | -            | -                | -                | -         |   -16.10 | Kre1N, MRC9, Orbit, Tionix, Twiksar         |
|           20 |     1175 | 2024-05-15 | Wave Esports              | W   | 1.000      | 0.143        | 0.001 (0.000)    | 0.143 (0.020)    | 0 (0.000) |     9.27 | DreaM-, Kre1N, Orbit, Tionix, Twiksar       |
|           19 |     1183 | 2024-05-15 | JANO Esports              | W   | 1.000      | 0.354        | 0.003 (0.001)    | 0.419 (0.148)    | 0 (0.000) |    17.06 | Kre1N, Orbit, P4TriCK, Tionix, Twiksar      |
|           18 |     1327 | 2024-05-13 | GUN5 Esports              | L   | 1.000      | -            | -                | -                | -         |   -16.20 | Kre1N, MRC9, Orbit, Tionix, Twiksar         |
|           17 |     1634 | 2024-05-08 | ex-Turów Zgorzelec Esport | L   | 1.000      | -            | -                | -                | -         |   -14.37 | Kre1N, MRC9, Orbit, Tionix, Twiksar         |
|           16 |     1739 | 2024-05-06 | Passion UA                | L   | 1.000      | -            | -                | -                | -         |    -7.40 | Kre1N, MRC9, Orbit, Tionix, Twiksar         |
|           15 |     1904 | 2024-05-03 | ARCRED                    | L   | 1.000      | -            | -                | -                | -         |    -9.52 | Kre1N, MRC9, Orbit, Tionix, Twiksar         |
|           14 |     1982 | 2024-05-01 | SNOGARD Dragons           | W   | 1.000      | 0.143        | 0.004 (0.001)    | 0.137 (0.020)    | 0 (0.000) |    16.26 | DreaM-, Kre1N, Orbit, Tionix, Twiksar       |
|           13 |     2017 | 2024-05-01 | ex-K10                    | L   | 1.000      | -            | -                | -                | -         |   -13.94 | Kre1N, MRC9, Orbit, Tionix, Twiksar         |
|           12 |     2761 | 2024-04-19 | GenOne                    | W   | 0.930      | 0.372        | 0.000 (0.000)    | 0.442 (0.153)    | 0 (0.000) |    10.82 | Kre1N, MRC9, Orbit, Tionix, Twiksar         |
|           11 |     3234 | 2024-04-10 | Copenhagen Wolves         | W   | 0.871      | 0.372        | -                | 0.387 (0.125)    | 0 (0.000) |    10.87 | Kre1N, MRC9, Orbit, Tionix, Twiksar         |
|           10 |     3323 | 2024-04-09 | Rhyno Esports             | L   | 0.863      | -            | -                | -                | -         |    -6.47 | Kre1N, MRC9, Orbit, Tionix, Twiksar         |
|            9 |     3371 | 2024-04-08 | TeamOrangeGaming          | W   | 0.857      | 0.143        | 0.006 (0.001)    | 0.235 (0.029)    | 0 (0.000) |    14.53 | DreaM-, Kre1N, Orbit, Tionix, Twiksar       |
|            8 |     3640 | 2024-04-03 | Sissi State Punks         | W   | 0.823      | 0.143        | 0.004 (0.000)    | 0.226 (0.027)    | -         |    11.48 | DreaM-, Kre1N, Orbit, Tionix, Twiksar       |
|            7 |     3973 | 2024-03-26 | Sashi Esport              | L   | 0.771      | -            | -                | -                | -         |    -2.96 | Kre1N, Orbit, SnacKZ1, Tionix, Twiksar      |
|            6 |     4310 | 2024-03-18 | ex-Turów Zgorzelec Esport | L   | 0.717      | -            | -                | -                | -         |    -9.36 | AxEcHo, darko, kadziu, Markoś, xKacpersky   |
|            5 |     4348 | 2024-03-17 | TEAM MAX                  | W   | 0.711      | -            | -                | -                | -         |     6.68 | kL1o, Malkiss, tAk, tooizera, zecco         |
|            4 |     4476 | 2024-03-15 | Dynamo Eclot              | L   | 0.698      | -            | -                | -                | -         |    -3.03 | j1NZO, Kre1N, Orbit, Tionix, Twiksar        |
|            3 |     4715 | 2024-03-11 | Donstu Esports            | W   | 0.671      | 0.333        | -                | 0.178 (0.040)    | -         |     5.88 | j1NZO, Kre1N, Orbit, Tionix, Twiksar        |
|            2 |     4927 | 2024-03-07 | GameAgents                | W   | 0.645      | -            | -                | -                | -         |     5.14 | el_strongo, mikult, MQ666MQ, NerouK, wtfmen |
|            1 |     7810 | 2024-01-17 | ex-Guild Eagles           | L   | 0.311      | -            | -                | -                | -         |    -1.91 | Kre1N, Orbit, S1M, Tionix, Twiksar          |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($497.31)
- Divide that value by the 5th highest value among all rosters ($300,806.11)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-05-25 |      1.000 | $271.94        | $271.94         |
| 2024-03-23 |      0.751 | $300.00        | $225.38         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
