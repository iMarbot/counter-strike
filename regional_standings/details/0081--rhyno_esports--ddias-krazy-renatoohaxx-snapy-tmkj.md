### Roster Details<br />
Team Name: Rhyno Esports<br />
Roster: DDias, krazy, renatoohaxx, snapy, TMKj<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [81](../standings_global.md)<br />
Regional Rank: [57]( ../standings_europe.md)<br />
Final Rank Value:  910.7<br />
<br />
Final Rank Value (910.7) = Starting Rank Value (1044.9) + Head To Head Adjustments (-134.2)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.394[<sup>1</sup>](#table2)
- Bounty Collected: 0.355[<sup>2</sup>](#table1)
- Opponent Network: 0.240[<sup>2</sup>](#table1)
- LAN Wins: 0.281[<sup>2</sup>](#table1)

The average of these factors is 0.317<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1044.9
- 400 + ( ( 0.317 - 0.000 ) / ( 0.787 - 0.000 ) ) * 1600 = 1044.9


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent               | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                 |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           64 |      140 | 2024-05-28 | Team Sampi             | L   | 1.000      | -            | -                | -                | -         |   -13.85 | DDias, krazy, renatoohaxx, snapy, TMKj |
|           63 |      195 | 2024-05-27 | Endpoint               | W   | 1.000      | 0.435        | 0.012 (0.005)    | 0.770 (0.335)    | 0 (0.000) |    15.44 | DDias, krazy, renatoohaxx, snapy, TMKj |
|           62 |      317 | 2024-05-25 | Zero Tenacity          | L   | 1.000      | -            | -                | -                | -         |   -10.42 | DDias, krazy, renatoohaxx, snapy, TMKj |
|           61 |      413 | 2024-05-23 | EXO Clan               | L   | 1.000      | -            | -                | -                | -         |   -21.27 | DDias, krazy, renatoohaxx, snapy, TMKj |
|           60 |      516 | 2024-05-22 | MOUZ NXT               | W   | 1.000      | 0.435        | 0.157 (0.068)    | 0.977 (0.424)    | 0 (0.000) |    18.12 | DDias, krazy, renatoohaxx, snapy, TMKj |
|           59 |      582 | 2024-05-21 | B8                     | L   | 1.000      | -            | -                | -                | -         |    -6.63 | DDias, krazy, renatoohaxx, snapy, TMKj |
|           58 |      602 | 2024-05-21 | Team PeeP              | L   | 1.000      | -            | -                | -                | -         |   -26.34 | DDias, krazy, renatoohaxx, snapy, TMKj |
|           57 |      619 | 2024-05-21 | Soda Gaming            | W   | 1.000      | -            | -                | -                | 0 (0.000) |     5.05 | DDias, krazy, renatoohaxx, snapy, TMKj |
|           56 |      713 | 2024-05-20 | kONO.ECF               | L   | 1.000      | -            | -                | -                | -         |   -18.64 | DDias, krazy, renatoohaxx, snapy, TMKj |
|           55 |      880 | 2024-05-18 | ABT Esports            | W   | 1.000      | -            | -                | -                | 0 (0.000) |     2.46 | DDias, krazy, renatoohaxx, snapy, TMKj |
|           54 |      910 | 2024-05-18 | SAW Youngsters         | W   | 1.000      | -            | -                | -                | 0 (0.000) |     1.26 | DDias, krazy, renatoohaxx, snapy, TMKj |
|           53 |      942 | 2024-05-18 | LEON Esports           | W   | 1.000      | -            | -                | -                | 0 (0.000) |     6.62 | DDias, krazy, renatoohaxx, snapy, TMKj |
|           52 |     1091 | 2024-05-16 | Copenhagen Wolves      | W   | 1.000      | -            | -                | -                | -         |     4.69 | DDias, krazy, renatoohaxx, snapy, TMKj |
|           51 |     1186 | 2024-05-15 | GUN5 Esports           | L   | 1.000      | -            | -                | -                | -         |   -24.59 | DDias, krazy, renatoohaxx, snapy, TMKj |
|           50 |     1215 | 2024-05-15 | EYEBALLERS             | W   | 1.000      | 0.143        | 0.012 (0.002)    | -                | -         |    13.09 | DDias, krazy, renatoohaxx, snapy, TMKj |
|           49 |     1289 | 2024-05-14 | Nexus Gaming           | L   | 1.000      | -            | -                | -                | -         |   -21.74 | DDias, krazy, renatoohaxx, snapy, TMKj |
|           48 |     1385 | 2024-05-12 | AL-QATRAO              | W   | 1.000      | -            | -                | -                | 1 (1.000) |     8.20 | DDias, krazy, renatoohaxx, snapy, TMKj |
|           47 |     1488 | 2024-05-11 | ALL-IN                 | W   | 1.000      | -            | -                | -                | 1 (1.000) |     2.46 | DDias, krazy, renatoohaxx, snapy, TMKj |
|           46 |     1654 | 2024-05-08 | Nemiga Gaming          | L   | 1.000      | -            | -                | -                | -         |    -7.70 | DDias, krazy, renatoohaxx, snapy, TMKj |
|           45 |     2547 | 2024-04-21 | Aurora Young Blud      | W   | 0.943      | 0.333        | 0.008 (0.003)    | 0.506 (0.159)    | -         |     7.01 | DDias, krazy, renatoohaxx, snapy, TMKj |
|           44 |     2561 | 2024-04-21 | Dynamo Eclot           | W   | 0.943      | 0.333        | 0.097 (0.030)    | 0.940 (0.295)    | -         |    16.55 | DDias, krazy, renatoohaxx, snapy, TMKj |
|           43 |     2693 | 2024-04-20 | HOTU                   | W   | 0.935      | 0.333        | -                | 0.580 (0.181)    | -         |    10.85 | DDias, krazy, renatoohaxx, snapy, TMKj |
|           42 |     2777 | 2024-04-19 | UNiTY esports          | W   | 0.929      | 0.333        | 0.021 (0.007)    | 0.766 (0.237)    | -         |    12.23 | DDias, krazy, renatoohaxx, snapy, TMKj |
|           41 |     2843 | 2024-04-18 | Aurora Young Blud      | L   | 0.922      | -            | -                | -                | -         |   -22.24 | DDias, krazy, renatoohaxx, snapy, TMKj |
|           40 |     2963 | 2024-04-16 | Denial                 | W   | 0.910      | -            | -                | -                | -         |     2.92 | DDias, krazy, renatoohaxx, snapy, TMKj |
|           39 |     2972 | 2024-04-16 | los kogutos            | L   | 0.910      | -            | -                | -                | -         |   -19.67 | DDias, krazy, renatoohaxx, snapy, TMKj |
|           38 |     3194 | 2024-04-11 | ADEPTS                 | W   | 0.876      | 0.372        | 0.005 (0.002)    | -                | -         |     7.83 | DDias, krazy, renatoohaxx, snapy, TMKj |
|           37 |     3201 | 2024-04-11 | UNiTY esports          | W   | 0.875      | 0.333        | 0.021 (0.006)    | 0.766 (0.224)    | -         |     9.94 | DDias, krazy, renatoohaxx, snapy, TMKj |
|           36 |     3267 | 2024-04-10 | Dynamo Eclot           | W   | 0.869      | 0.333        | 0.097 (0.028)    | 0.940 (0.272)    | -         |    15.13 | DDias, krazy, renatoohaxx, snapy, TMKj |
|           35 |     3323 | 2024-04-09 | ARROW                  | W   | 0.863      | -            | -                | -                | -         |     6.47 | DDias, krazy, renatoohaxx, snapy, TMKj |
|           34 |     3386 | 2024-04-08 | DMS                    | L   | 0.856      | -            | -                | -                | -         |   -17.81 | DDias, krazy, renatoohaxx, snapy, TMKj |
|           33 |     5251 | 2024-03-03 | esmagaB                | L   | 0.616      | -            | -                | -                | -         |   -14.07 | DDias, krazy, renatoohaxx, snapy, TMKj |
|           32 |     5331 | 2024-03-02 | AL-QATRAO              | W   | 0.610      | -            | -                | -                | 1 (0.610) |     4.64 | DDias, krazy, renatoohaxx, snapy, TMKj |
|           31 |     5512 | 2024-02-27 | Lemondogs              | W   | 0.584      | -            | -                | -                | -         |     2.04 | DDias, krazy, renatoohaxx, snapy, TMKj |
|           30 |     5526 | 2024-02-27 | Grannys Knockers       | W   | 0.584      | -            | -                | -                | -         |     5.00 | DDias, krazy, renatoohaxx, snapy, TMKj |
|           29 |     5531 | 2024-02-27 | FAVBET Team            | L   | 0.583      | -            | -                | -                | -         |   -12.34 | DDias, krazy, renatoohaxx, snapy, TMKj |
|           28 |     5826 | 2024-02-22 | Insilio                | L   | 0.550      | -            | -                | -                | -         |    -9.61 | DDias, krazy, renatoohaxx, snapy, TMKj |
|           27 |     5926 | 2024-02-20 | Lausanne-Sport Esports | W   | 0.537      | -            | -                | -                | -         |     3.62 | DDias, krazy, renatoohaxx, snapy, TMKj |
|           26 |     6119 | 2024-02-17 | UNiTY esports          | L   | 0.517      | -            | -                | -                | -         |   -10.37 | DDias, krazy, renatoohaxx, snapy, TMKj |
|           25 |     6162 | 2024-02-16 | HOTU                   | L   | 0.510      | -            | -                | -                | -         |   -11.06 | DDias, krazy, renatoohaxx, snapy, TMKj |
|           24 |     6236 | 2024-02-15 | Team Spirit Academy    | L   | 0.503      | -            | -                | -                | -         |   -12.55 | DDias, krazy, renatoohaxx, snapy, TMKj |
|           23 |     6340 | 2024-02-13 | VP.Prodigy             | W   | 0.491      | 0.371        | -                | 0.829 (0.151)    | -         |     4.74 | DDias, krazy, renatoohaxx, snapy, TMKj |
|           22 |     6522 | 2024-02-08 | GamerLegion Academy    | W   | 0.457      | 0.371        | 0.018 (0.003)    | 0.691 (0.117)    | -         |     3.77 | DDias, krazy, renatoohaxx, snapy, TMKj |
|           21 |     6541 | 2024-02-07 | GODSENT                | L   | 0.451      | -            | -                | -                | -         |   -12.35 | DDias, krazy, renatoohaxx, snapy, TMKj |
|           20 |     6668 | 2024-02-04 | SAW                    | L   | 0.430      | -            | -                | -                | -         |    -1.74 | DDias, krazy, renatoohaxx, snapy, TMKj |
|           19 |     6710 | 2024-02-03 | esmagaB                | W   | 0.424      | -            | -                | -                | -         |     3.94 | DDias, krazy, renatoohaxx, snapy, TMKj |
|           18 |     6794 | 2024-02-02 | ABT Esports            | W   | 0.418      | -            | -                | -                | -         |     0.72 | DDias, krazy, renatoohaxx, snapy, TMKj |
|           17 |     6810 | 2024-02-02 | KOI                    | L   | 0.417      | -            | -                | -                | -         |    -7.31 | DDias, krazy, renatoohaxx, snapy, TMKj |
|           16 |     6828 | 2024-02-02 | OVERFRAG               | W   | 0.417      | -            | -                | -                | -         |     1.32 | DDias, krazy, renatoohaxx, snapy, TMKj |
|           15 |     7268 | 2024-01-26 | INGLORIOUS             | L   | 0.370      | -            | -                | -                | -         |    -9.64 | DDias, krazy, renatoohaxx, snapy, TMKj |
|           14 |     7410 | 2024-01-23 | Zero Tenacity          | L   | 0.351      | -            | -                | -                | -         |    -5.18 | DDias, krazy, renatoohaxx, snapy, TMKj |
|           13 |     8352 | 2024-01-09 | Dynamo Eclot           | L   | 0.257      | -            | -                | -                | -         |    -3.24 | DDias, krazy, renatoohaxx, snapy, TMKj |
|           12 |     8367 | 2024-01-09 | Soda Gaming            | W   | 0.257      | -            | -                | -                | -         |     0.83 | DDias, krazy, renatoohaxx, snapy, TMKj |
|           11 |     8571 | 2023-12-28 | Alliance               | L   | 0.176      | -            | -                | -                | -         |    -3.99 | DDias, krazy, renatoohaxx, snapy, TMKj |
|           10 |     8577 | 2023-12-27 | brazylijski luz        | L   | 0.169      | -            | -                | -                | -         |    -4.14 | DDias, krazy, renatoohaxx, snapy, TMKj |
|            9 |     8836 | 2023-12-16 | UNiTY esports          | L   | 0.098      | -            | -                | -                | -         |    -2.04 | DDias, Icarus, krazy, snapy, TMKj      |
|            8 |     8988 | 2023-12-15 | ex-KRC Genk Esports    | W   | 0.091      | -            | -                | -                | -         |     0.39 | DDias, Icarus, krazy, snapy, TMKj      |
|            7 |     9048 | 2023-12-14 | gbcxz                  | W   | 0.085      | -            | -                | -                | -         |     0.20 | DDias, Icarus, krazy, snapy, TMKj      |
|            6 |     9078 | 2023-12-13 | NOM Esports            | W   | 0.078      | -            | -                | -                | -         |     0.23 | DDias, Icarus, krazy, snapy, TMKj      |
|            5 |     9136 | 2023-12-12 | BLUEJAYS Lite          | W   | 0.071      | -            | -                | -                | -         |     0.09 | DDias, Icarus, krazy, snapy, TMKj      |
|            4 |     9150 | 2023-12-12 | VP.Prodigy             | L   | 0.070      | -            | -                | -                | -         |    -1.67 | DDias, Icarus, krazy, snapy, TMKj      |
|            3 |     9378 | 2023-12-08 | TOOMUCHVIDEOGAMES      | W   | 0.043      | -            | -                | -                | -         |     0.06 | DDias, Icarus, krazy, snapy, TMKj      |
|            2 |     9389 | 2023-12-08 | FALKE ESPORTS          | W   | 0.042      | -            | -                | -                | 1 (0.042) |     0.08 | DDias, Icarus, krazy, snapy, TMKj      |
|            1 |     9559 | 2023-12-05 | Family                 | W   | 0.025      | -            | -                | -                | -         |     0.02 | DDias, Icarus, krazy, snapy, TMKj      |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($8,664.77)
- Divide that value by the 5th highest value among all rosters ($300,806.11)
- The final value (0.03) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-05-12 |      1.000 | $2,696.76      | $2,696.76       |
| 2024-04-21 |      0.943 | $5,000.00      | $4,716.67       |
| 2024-03-03 |      0.616 | $1,627.60      | $1,003.23       |
| 2023-12-17 |      0.105 | $1,500.00      | $156.88         |
| 2023-12-08 |      0.042 | $2,158.51      | $91.24          |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
