### Roster Details<br />
Team Name: ARROW<br />
Roster: DreaM-, Kre1N, Orbit, Tionix, Twiksar<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [201](../standings_global.md)<br />
Regional Rank: [135]( ../standings_europe.md)<br />
Final Rank Value:  724.3<br />
<br />
Final Rank Value (724.3) = Starting Rank Value (706.7) + Head To Head Adjustments (17.6)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.264[<sup>1</sup>](#table2)
- Bounty Collected: 0.248[<sup>2</sup>](#table1)
- Opponent Network: 0.090[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.151<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 706.7
- 400 + ( ( 0.151 - 0.000 ) / ( 0.786 - 0.000 ) ) * 1600 = 706.7


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
|           27 |      282 | 2024-05-25 | Sissi State Punks         | L   | 1.000      | -            | -                | -                | -         |   -18.36 | DreaM-, Kre1N, Orbit, Tionix, Twiksar       |
|           26 |      331 | 2024-05-24 | GamerLegion Academy       | L   | 1.000      | -            | -                | -                | -         |   -14.74 | Kre1N, MRC9, Orbit, Tionix, Twiksar         |
|           25 |      402 | 2024-05-23 | ALTERNATE aTTaX           | L   | 1.000      | -            | -                | -                | -         |    -9.97 | DreaM-, Kre1N, Orbit, Tionix, Twiksar       |
|           24 |      454 | 2024-05-22 | EVOPLAY                   | W   | 1.000      | 0.143        | 0.000 (0.000)    | -                | 0 (0.000) |     7.93 | DreaM-, Kre1N, Orbit, Tionix, Twiksar       |
|           23 |      582 | 2024-05-21 | ADEPTS                    | W   | 1.000      | 0.372        | 0.005 (0.002)    | 0.291 (0.108)    | 0 (0.000) |    15.70 | Kre1N, MRC9, Orbit, Tionix, Twiksar         |
|           22 |      657 | 2024-05-20 | Endpoint                  | W   | 1.000      | 0.372        | 0.012 (0.004)    | 0.718 (0.267)    | 0 (0.000) |    21.13 | Kre1N, MRC9, Orbit, Tionix, Twiksar         |
|           21 |      696 | 2024-05-20 | mYinsanity                | L   | 1.000      | -            | -                | -                | -         |   -20.31 | DreaM-, Kre1N, Orbit, Tionix, Twiksar       |
|           20 |     1087 | 2024-05-16 | Tropic                    | W   | 1.000      | 0.354        | 0.000 (0.000)    | -                | 0 (0.000) |     7.83 | Kre1N, Orbit, P4TriCK, Tionix, Twiksar      |
|           19 |     1138 | 2024-05-15 | VaselineWorms             | L   | 1.000      | -            | -                | -                | -         |   -16.93 | Kre1N, MRC9, Orbit, Tionix, Twiksar         |
|           18 |     1165 | 2024-05-15 | Wave Esports              | W   | 1.000      | 0.143        | 0.001 (0.000)    | 0.143 (0.020)    | 0 (0.000) |     8.63 | DreaM-, Kre1N, Orbit, Tionix, Twiksar       |
|           17 |     1173 | 2024-05-15 | JANO Esports              | W   | 1.000      | 0.354        | 0.003 (0.001)    | 0.392 (0.139)    | 0 (0.000) |    15.62 | Kre1N, Orbit, P4TriCK, Tionix, Twiksar      |
|           16 |     1315 | 2024-05-13 | GUN5 Esports              | L   | 1.000      | -            | -                | -                | -         |   -17.55 | Kre1N, MRC9, Orbit, Tionix, Twiksar         |
|           15 |     1717 | 2024-05-06 | Passion UA                | L   | 1.000      | -            | -                | -                | -         |    -8.11 | Kre1N, MRC9, Orbit, Tionix, Twiksar         |
|           14 |     1879 | 2024-05-03 | ARCRED                    | L   | 1.000      | -            | -                | -                | -         |    -9.94 | Kre1N, MRC9, Orbit, Tionix, Twiksar         |
|           13 |     1955 | 2024-05-01 | SNOGARD Dragons           | W   | 1.000      | 0.143        | 0.004 (0.001)    | 0.137 (0.020)    | 0 (0.000) |    16.02 | DreaM-, Kre1N, Orbit, Tionix, Twiksar       |
|           12 |     2705 | 2024-04-19 | GenOne                    | W   | 0.930      | 0.372        | 0.000 (0.000)    | 0.442 (0.153)    | 0 (0.000) |    10.80 | Kre1N, MRC9, Orbit, Tionix, Twiksar         |
|           11 |     3162 | 2024-04-10 | Copenhagen Wolves         | W   | 0.871      | 0.372        | -                | 0.309 (0.100)    | 0 (0.000) |     9.62 | Kre1N, MRC9, Orbit, Tionix, Twiksar         |
|           10 |     3244 | 2024-04-09 | Rhyno Esports             | L   | 0.863      | -            | -                | -                | -         |    -6.61 | Kre1N, MRC9, Orbit, Tionix, Twiksar         |
|            9 |     3290 | 2024-04-08 | TeamOrangeGaming          | W   | 0.857      | 0.143        | 0.006 (0.001)    | 0.235 (0.029)    | 0 (0.000) |    14.86 | DreaM-, Kre1N, Orbit, Tionix, Twiksar       |
|            8 |     3553 | 2024-04-03 | Sissi State Punks         | W   | 0.823      | 0.143        | 0.004 (0.000)    | 0.226 (0.027)    | -         |    11.57 | DreaM-, Kre1N, Orbit, Tionix, Twiksar       |
|            7 |     3876 | 2024-03-26 | Sashi Esport              | L   | 0.771      | -            | -                | -                | -         |    -3.03 | Kre1N, Orbit, SnacKZ1, Tionix, Twiksar      |
|            6 |     4205 | 2024-03-18 | ex-Turów Zgorzelec Esport | L   | 0.717      | -            | -                | -                | -         |    -9.55 | AxEcHo, darko, kadziu, Markoś, xKacpersky   |
|            5 |     4243 | 2024-03-17 | TEAM MAX                  | W   | 0.711      | -            | -                | -                | -         |     6.70 | kL1o, Malkiss, tAk, tooizera, zecco         |
|            4 |     4368 | 2024-03-15 | Dynamo Eclot              | L   | 0.698      | -            | -                | -                | -         |    -2.94 | j1NZO, Kre1N, Orbit, Tionix, Twiksar        |
|            3 |     4593 | 2024-03-11 | Donstu Esports            | W   | 0.671      | 0.333        | -                | 0.178 (0.040)    | -         |     5.94 | j1NZO, Kre1N, Orbit, Tionix, Twiksar        |
|            2 |     4798 | 2024-03-07 | GameAgents                | W   | 0.645      | -            | -                | -                | -         |     5.19 | el_strongo, mikult, MQ666MQ, NerouK, wtfmen |
|            1 |     7561 | 2024-01-17 | ex-Guild Eagles           | L   | 0.311      | -            | -                | -                | -         |    -1.90 | Kre1N, Orbit, S1M, Tionix, Twiksar          |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($496.79)
- Divide that value by the 5th highest value among all rosters ($300,806.11)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-05-25 |      1.000 | $271.41        | $271.41         |
| 2024-03-23 |      0.751 | $300.00        | $225.38         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
