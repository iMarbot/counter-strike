### Roster Details<br />
Team Name: Corinthians Esports<br />
Roster: abr, CutzMeretz, legy, Lich, MITHPUTTINI<br />
Region: [Americas]( ../standings_americas.md)<br />
<br />
Global Rank: [200](../standings_global.md)<br />
Regional Rank: [41]( ../standings_americas.md)<br />
Final Rank Value:  722.9<br />
<br />
Final Rank Value (722.9) = Starting Rank Value (699.8) + Head To Head Adjustments (23.1)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.276[<sup>1</sup>](#table2)
- Bounty Collected: 0.250[<sup>2</sup>](#table1)
- Opponent Network: 0.064[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.147<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 699.8
- 400 + ( ( 0.147 - 0.000 ) / ( 0.787 - 0.000 ) ) * 1600 = 699.8


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent               | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                   |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           55 |       35 | 2024-05-29 | Full House Gaming      | W   | 1.000      | 0.143        | 0.002 (0.000)    | -                | 0 (0.000) |    12.99 | abr, CutzMeretz, legy, Lich, MITHPUTTINI |
|           54 |       87 | 2024-05-29 | 9z Academy             | W   | 1.000      | 0.384        | 0.002 (0.001)    | 0.311 (0.120)    | 0 (0.000) |    13.22 | abr, CutzMeretz, legy, Lich, MITHPUTTINI |
|           53 |      112 | 2024-05-28 | 9z Academy             | L   | 1.000      | -            | -                | -                | -         |   -18.51 | abr, CutzMeretz, legy, Lich, MITHPUTTINI |
|           52 |      124 | 2024-05-28 | Hype Esports           | L   | 1.000      | -            | -                | -                | -         |   -17.63 | abr, CutzMeretz, legy, Lich, MITHPUTTINI |
|           51 |      338 | 2024-05-24 | Romanticos             | W   | 1.000      | -            | -                | -                | 0 (0.000) |     9.53 | abr, CutzMeretz, legy, Lich, MITHPUTTINI |
|           50 |      392 | 2024-05-23 | MIBR Academy           | W   | 1.000      | 0.143        | 0.003 (0.000)    | 0.220 (0.031)    | 0 (0.000) |    14.86 | abr, CutzMeretz, legy, Lich, MITHPUTTINI |
|           49 |      466 | 2024-05-22 | Hype Esports           | W   | 1.000      | 0.143        | -                | 0.218 (0.031)    | 0 (0.000) |    14.82 | abr, CutzMeretz, legy, Lich, MITHPUTTINI |
|           48 |      583 | 2024-05-21 | bebidarosa             | W   | 1.000      | -            | -                | -                | 0 (0.000) |    10.64 | abr, CutzMeretz, legy, Lich, MITHPUTTINI |
|           47 |      653 | 2024-05-20 | BESTIA                 | L   | 1.000      | -            | -                | -                | -         |    -6.08 | abr, CutzMeretz, desh, legy, Leomonster  |
|           46 |      663 | 2024-05-20 | Vikings KR             | L   | 1.000      | -            | -                | -                | -         |   -13.47 | abr, CutzMeretz, legy, Lich, MITHPUTTINI |
|           45 |      958 | 2024-05-17 | Full House Gaming      | W   | 1.000      | -            | -                | -                | 0 (0.000) |    14.73 | abr, CutzMeretz, legy, Lich, MITHPUTTINI |
|           44 |     1055 | 2024-05-16 | Yawara E-Sports        | W   | 1.000      | 0.143        | 0.002 (0.000)    | 0.319 (0.046)    | 0 (0.000) |    14.38 | abr, CutzMeretz, legy, Lich, MITHPUTTINI |
|           43 |     1060 | 2024-05-16 | Sensei Team            | W   | 1.000      | 0.143        | 0.003 (0.000)    | 0.482 (0.069)    | 0 (0.000) |    18.38 | abr, CutzMeretz, legy, Lich, MITHPUTTINI |
|           42 |     1140 | 2024-05-15 | Case Esports           | L   | 1.000      | -            | -                | -                | -         |    -8.02 | abr, CutzMeretz, desh, legy, Leomonster  |
|           41 |     1144 | 2024-05-15 | Case Esports           | L   | 1.000      | -            | -                | -                | -         |    -8.58 | abr, CutzMeretz, desh, legy, Leomonster  |
|           40 |     1240 | 2024-05-14 | RED Canids             | L   | 1.000      | -            | -                | -                | -         |    -3.19 | abr, CutzMeretz, desh, legy, Leomonster  |
|           39 |     1244 | 2024-05-14 | RED Canids             | L   | 1.000      | -            | -                | -                | -         |    -3.29 | abr, CutzMeretz, desh, legy, Leomonster  |
|           38 |     1418 | 2024-05-11 | ODDIK                  | L   | 1.000      | -            | -                | -                | -         |    -6.53 | abr, CutzMeretz, legy, Lich, MITHPUTTINI |
|           37 |     1972 | 2024-05-01 | ex-Martians            | W   | 1.000      | -            | -                | -                | 0 (0.000) |    12.22 | abr, CutzMeretz, jz, legy, paqueta       |
|           36 |     2043 | 2024-04-30 | Romanticos             | W   | 1.000      | -            | -                | -                | -         |     9.85 | abr, CutzMeretz, jz, legy, paqueta       |
|           35 |     2258 | 2024-04-26 | Hype Esports           | L   | 0.979      | -            | -                | -                | -         |   -17.17 | abr, CutzMeretz, jz, legy, paqueta       |
|           34 |     2259 | 2024-04-26 | 2Game Esports          | W   | 0.979      | 0.143        | 0.003 (0.000)    | 0.212 (0.030)    | -         |    15.47 | abr, CutzMeretz, jz, legy, paqueta       |
|           33 |     2384 | 2024-04-24 | Bounty Hunters Esports | L   | 0.965      | -            | -                | -                | -         |   -17.16 | abr, CutzMeretz, legy, nacho, paqueta    |
|           32 |     2444 | 2024-04-23 | Projeto KinGui         | W   | 0.959      | -            | -                | -                | -         |     7.85 | abr, CutzMeretz, legy, nacho, paqueta    |
|           31 |     3076 | 2024-04-13 | ODDIK Academy          | L   | 0.891      | -            | -                | -                | -         |   -16.91 | abr, CutzMeretz, desh, legy, Leomonster  |
|           30 |     3079 | 2024-04-13 | eSports Recife         | W   | 0.891      | 0.143        | 0.002 (0.000)    | 0.441 (0.056)    | -         |    13.67 | abr, CutzMeretz, desh, legy, Leomonster  |
|           29 |     3124 | 2024-04-12 | Vex Dragons            | W   | 0.885      | -            | -                | -                | -         |     4.78 | abr, CutzMeretz, desh, legy, Leomonster  |
|           28 |     3560 | 2024-04-04 | Fluxo                  | L   | 0.832      | -            | -                | -                | -         |    -3.31 | abr, CutzMeretz, desh, legy, Leomonster  |
|           27 |     3563 | 2024-04-04 | Fluxo                  | L   | 0.832      | -            | -                | -                | -         |    -3.42 | abr, CutzMeretz, desh, legy, Leomonster  |
|           26 |     3711 | 2024-04-01 | Dusty Roots            | L   | 0.811      | -            | -                | -                | -         |   -13.69 | abr, CutzMeretz, desh, legy, Leomonster  |
|           25 |     3827 | 2024-03-28 | Galorys                | L   | 0.784      | -            | -                | -                | -         |    -8.09 | abr, CutzMeretz, desh, legy, Leomonster  |
|           24 |     3867 | 2024-03-27 | 2Game Esports          | L   | 0.779      | -            | -                | -                | -         |   -13.87 | abr, CutzMeretz, desh, legy, Leomonster  |
|           23 |     3870 | 2024-03-27 | 2Game Esports          | W   | 0.779      | 0.450        | 0.003 (0.001)    | 0.212 (0.074)    | -         |    10.74 | abr, CutzMeretz, desh, legy, Leomonster  |
|           22 |     3943 | 2024-03-26 | bebidarosa             | W   | 0.772      | -            | -                | -                | -         |    10.49 | abr, CutzMeretz, desh, legy, Leomonster  |
|           21 |     4011 | 2024-03-25 | FURIA Academy          | L   | 0.764      | -            | -                | -                | -         |   -14.74 | abr, CutzMeretz, desh, legy, Leomonster  |
|           20 |     4067 | 2024-03-23 | Full House Gaming      | W   | 0.752      | -            | -                | -                | -         |    10.71 | abr, CutzMeretz, desh, legy, Leomonster  |
|           19 |     4075 | 2024-03-23 | ex-Martians            | W   | 0.751      | -            | -                | -                | -         |     9.79 | abr, CutzMeretz, desh, legy, Leomonster  |
|           18 |     4082 | 2024-03-23 | Floripa Stars          | W   | 0.751      | -            | -                | -                | -         |    10.38 | abr, CutzMeretz, desh, legy, Leomonster  |
|           17 |     4088 | 2024-03-23 | ODDIK Academy          | W   | 0.751      | -            | -                | -                | -         |     9.96 | abr, CutzMeretz, desh, legy, Leomonster  |
|           16 |     4160 | 2024-03-21 | Vikings KR             | W   | 0.738      | 0.143        | 0.004 (0.000)    | 0.313 (0.033)    | -         |    13.01 | abr, CutzMeretz, desh, legy, Leomonster  |
|           15 |     4174 | 2024-03-21 | TIME DE PESO           | W   | 0.738      | -            | -                | -                | -         |     6.43 | abr, CutzMeretz, desh, legy, Leomonster  |
|           14 |     4594 | 2024-03-13 | MIBR Academy           | L   | 0.684      | -            | -                | -                | -         |    -8.89 | abr, CutzMeretz, desh, legy, Leomonster  |
|           13 |     4725 | 2024-03-11 | RED Canids             | L   | 0.671      | -            | -                | -                | -         |    -2.62 | abr, CutzMeretz, desh, legy, Leomonster  |
|           12 |     4845 | 2024-03-09 | Fluxo                  | L   | 0.656      | -            | -                | -                | -         |    -2.66 | abr, CutzMeretz, desh, legy, Leomonster  |
|           11 |     4951 | 2024-03-07 | Sharks Esports         | L   | 0.643      | -            | -                | -                | -         |    -3.51 | abr, CutzMeretz, desh, legy, Leomonster  |
|           10 |     5748 | 2024-02-23 | Galorys                | W   | 0.559      | 0.450        | 0.022 (0.006)    | 0.600 (0.151)    | -         |    12.20 | abr, CutzMeretz, desh, legy, Leomonster  |
|            9 |     5753 | 2024-02-23 | Galorys                | L   | 0.559      | -            | -                | -                | -         |    -5.43 | abr, CutzMeretz, desh, legy, Leomonster  |
|            8 |     5847 | 2024-02-21 | Sharks Esports         | L   | 0.546      | -            | -                | -                | -         |    -3.28 | abr, CutzMeretz, desh, legy, Leomonster  |
|            7 |     6111 | 2024-02-17 | Galorys                | L   | 0.517      | -            | -                | -                | -         |    -4.82 | abr, CutzMeretz, desh, legy, Leomonster  |
|            6 |     6258 | 2024-02-14 | adalYamigos            | L   | 0.499      | -            | -                | -                | -         |    -7.79 | abr, CutzMeretz, desh, legy, Leomonster  |
|            5 |     6264 | 2024-02-14 | adalYamigos            | L   | 0.499      | -            | -                | -                | -         |    -8.13 | abr, CutzMeretz, desh, legy, Leomonster  |
|            4 |     6335 | 2024-02-13 | w7m esports            | L   | 0.491      | -            | -                | -                | -         |    -4.91 | abr, CutzMeretz, desh, legy, Leomonster  |
|            3 |     6384 | 2024-02-12 | w7m esports            | L   | 0.484      | -            | -                | -                | -         |    -5.03 | abr, CutzMeretz, desh, legy, Leomonster  |
|            2 |     7069 | 2024-01-28 | Hype Esports           | L   | 0.385      | -            | -                | -                | -         |    -9.14 | abr, CutzMeretz, desh, legy, Leomonster  |
|            1 |     7123 | 2024-01-27 | BAD MANNERS            | W   | 0.379      | -            | -                | -                | -         |     1.87 | abr, CutzMeretz, desh, legy, Leomonster  |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($709.46)
- Divide that value by the 5th highest value among all rosters ($300,806.11)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-05-07 |      1.000 | $128.04        | $128.04         |
| 2024-05-01 |      1.000 | $115.49        | $115.49         |
| 2024-03-26 |      0.772 | $603.15        | $465.93         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
