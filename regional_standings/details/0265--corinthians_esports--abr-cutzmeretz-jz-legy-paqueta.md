### Roster Details<br />
Team Name: Corinthians Esports<br />
Roster: abr, CutzMeretz, jz, legy, paqueta<br />
Region: [Americas]( ../standings_americas.md)<br />
<br />
Global Rank: [265](../standings_global.md)<br />
Regional Rank: [54]( ../standings_americas.md)<br />
Final Rank Value:  651.1<br />
<br />
Final Rank Value (651.1) = Starting Rank Value (705.1) + Head To Head Adjustments (-54.0)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.304[<sup>1</sup>](#table2)
- Bounty Collected: 0.268[<sup>2</sup>](#table1)
- Opponent Network: 0.044[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.154<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 705.1
- 400 + ( ( 0.154 - 0.000 ) / ( 0.806 - 0.000 ) ) * 1600 = 705.1


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent                       | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins      | H2H Adj. | Roster                                  |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           33 |      169 | 2024-05-01 | Martians                       | W   | 1.000      | 0.143        | 0.001 (0.000)    | 0.108 (0.015)    | false (0.000) |    13.90 | abr, CutzMeretz, jz, legy, paqueta      |
|           32 |      395 | 2024-04-26 | Hype E-Sports (Brazilian team) | L   | 1.000      | -            | -                | -                | -             |   -18.74 | abr, CutzMeretz, jz, legy, paqueta      |
|           31 |      396 | 2024-04-26 | 2Game Esports                  | W   | 1.000      | 0.143        | 0.000 (0.000)    | 0.188 (0.027)    | false (0.000) |    14.68 | abr, CutzMeretz, jz, legy, paqueta      |
|           30 |      504 | 2024-04-24 | Bounty Hunters Esports         | L   | 1.000      | -            | -                | -                | -             |   -16.13 | abr, CutzMeretz, legy, nacho, paqueta   |
|           29 |      555 | 2024-04-23 | Projeto KinGui                 | W   | 1.000      | 0.143        | 0.000 (0.000)    | -                | false (0.000) |     6.03 | abr, CutzMeretz, legy, nacho, paqueta   |
|           28 |     1093 | 2024-04-13 | ODDIK Academy                  | L   | 1.000      | -            | -                | -                | -             |   -17.11 | abr, CutzMeretz, desh, legy, Leomonster |
|           27 |     1128 | 2024-04-12 | Vex Dragons                    | W   | 1.000      | -            | -                | -                | false (0.000) |     5.56 | abr, CutzMeretz, desh, legy, Leomonster |
|           26 |     1466 | 2024-04-04 | Fluxo                          | L   | 0.993      | -            | -                | -                | -             |    -3.98 | abr, CutzMeretz, desh, legy, Leomonster |
|           25 |     1468 | 2024-04-04 | Fluxo                          | L   | 0.993      | -            | -                | -                | -             |    -4.14 | abr, CutzMeretz, desh, legy, Leomonster |
|           24 |     1597 | 2024-04-01 | Dusty Roots                    | L   | 0.972      | -            | -                | -                | -             |   -16.84 | abr, CutzMeretz, desh, legy, Leomonster |
|           23 |     1690 | 2024-03-28 | Galorys                        | L   | 0.945      | -            | -                | -                | -             |    -8.89 | abr, CutzMeretz, desh, legy, Leomonster |
|           22 |     1722 | 2024-03-27 | 2Game Esports                  | L   | 0.940      | -            | -                | -                | -             |   -18.75 | abr, CutzMeretz, desh, legy, Leomonster |
|           21 |     1726 | 2024-03-27 | 2Game Esports                  | W   | 0.940      | 0.450        | -                | 0.188 (0.080)    | false (0.000) |    10.63 | abr, CutzMeretz, desh, legy, Leomonster |
|           20 |     1787 | 2024-03-26 | Looking4Org (Brazilian team)   | W   | 0.934      | 0.143        | 0.003 (0.000)    | 0.138 (0.018)    | false (0.000) |    13.28 | abr, CutzMeretz, desh, legy, Leomonster |
|           19 |     1840 | 2024-03-25 | FURIA Academy                  | L   | 0.926      | -            | -                | -                | -             |   -17.94 | abr, CutzMeretz, desh, legy, Leomonster |
|           18 |     1880 | 2024-03-23 | Full House Gaming              | W   | 0.913      | 0.143        | 0.003 (0.000)    | 0.153 (0.020)    | false (0.000) |    13.00 | abr, CutzMeretz, desh, legy, Leomonster |
|           17 |     1887 | 2024-03-23 | Martians                       | W   | 0.913      | 0.143        | 0.001 (0.000)    | 0.108 (0.014)    | false (0.000) |    11.28 | abr, CutzMeretz, desh, legy, Leomonster |
|           16 |     1894 | 2024-03-23 | Floripa Stars                  | W   | 0.912      | 0.143        | 0.001 (0.000)    | 0.181 (0.024)    | false (0.000) |    13.60 | abr, CutzMeretz, desh, legy, Leomonster |
|           15 |     1900 | 2024-03-23 | ODDIK Academy                  | W   | 0.912      | 0.143        | 0.002 (0.000)    | 0.160 (0.021)    | false (0.000) |    13.53 | abr, CutzMeretz, desh, legy, Leomonster |
|           14 |     1961 | 2024-03-21 | Vikings KR                     | W   | 0.899      | 0.143        | 0.009 (0.001)    | 0.210 (0.027)    | -             |    16.44 | abr, CutzMeretz, desh, legy, Leomonster |
|           13 |     2310 | 2024-03-13 | MIBR Academy                   | L   | 0.845      | -            | -                | -                | -             |    -9.72 | abr, CutzMeretz, desh, legy, Leomonster |
|           12 |     2410 | 2024-03-11 | RED Canids                     | L   | 0.832      | -            | -                | -                | -             |    -4.07 | abr, CutzMeretz, desh, legy, Leomonster |
|           11 |     2504 | 2024-03-09 | Fluxo                          | L   | 0.817      | -            | -                | -                | -             |    -3.33 | abr, CutzMeretz, desh, legy, Leomonster |
|           10 |     2580 | 2024-03-07 | Sharks Esports                 | L   | 0.804      | -            | -                | -                | -             |    -4.35 | abr, CutzMeretz, desh, legy, Leomonster |
|            9 |     3120 | 2024-02-24 | W7m esports                    | L   | 0.727      | -            | -                | -                | -             |   -12.17 | abr, CutzMeretz, desh, legy, Leomonster |
|            8 |     3127 | 2024-02-24 | W7m esports                    | L   | 0.727      | -            | -                | -                | -             |   -12.97 | abr, CutzMeretz, desh, legy, Leomonster |
|            7 |     3195 | 2024-02-23 | Galorys                        | W   | 0.720      | 0.450        | 0.048 (0.016)    | 0.598 (0.194)    | -             |    15.52 | abr, CutzMeretz, desh, legy, Leomonster |
|            6 |     3200 | 2024-02-23 | Galorys                        | L   | 0.720      | -            | -                | -                | -             |    -7.10 | abr, CutzMeretz, desh, legy, Leomonster |
|            5 |     3280 | 2024-02-21 | Sharks Esports                 | L   | 0.707      | -            | -                | -                | -             |    -4.81 | abr, CutzMeretz, desh, legy, Leomonster |
|            4 |     3490 | 2024-02-17 | Galorys                        | L   | 0.678      | -            | -                | -                | -             |    -6.40 | abr, CutzMeretz, desh, legy, Leomonster |
|            3 |     3612 | 2024-02-14 | AdalYamigos                    | L   | 0.660      | -            | -                | -                | -             |    -8.06 | abr, CutzMeretz, desh, legy, Leomonster |
|            2 |     3614 | 2024-02-14 | AdalYamigos                    | L   | 0.660      | -            | -                | -                | -             |    -8.52 | abr, CutzMeretz, desh, legy, Leomonster |
|            1 |     4241 | 2024-01-27 | BAD MANNERS                    | W   | 0.540      | -            | -                | -                | -             |     2.59 | abr, CutzMeretz, desh, legy, Leomonster |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($806.61)
- Divide that value by the 5th highest value among all rosters ($158,437.64)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-05-05 |      1.000 | $128.04        | $128.04         |
| 2024-05-01 |      1.000 | $115.49        | $115.49         |
| 2024-03-26 |      0.934 | $603.15        | $563.08         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
