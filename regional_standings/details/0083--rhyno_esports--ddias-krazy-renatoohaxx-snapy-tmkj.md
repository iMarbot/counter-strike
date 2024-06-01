### Roster Details<br />
Team Name: Rhyno Esports<br />
Roster: DDias, krazy, renatoohaxx, snapy, TMKj<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [83](../standings_global.md)<br />
Regional Rank: [57]( ../standings_europe.md)<br />
Final Rank Value:  900.7<br />
<br />
Final Rank Value (900.7) = Starting Rank Value (1042.4) + Head To Head Adjustments (-141.8)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.394[<sup>1</sup>](#table2)
- Bounty Collected: 0.355[<sup>2</sup>](#table1)
- Opponent Network: 0.233[<sup>2</sup>](#table1)
- LAN Wins: 0.281[<sup>2</sup>](#table1)

The average of these factors is 0.316<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1042.4
- 400 + ( ( 0.316 - 0.000 ) / ( 0.786 - 0.000 ) ) * 1600 = 1042.4


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
|           62 |      133 | 2024-05-28 | Team Sampi             | L   | 1.000      | -            | -                | -                | -         |   -13.58 | DDias, krazy, renatoohaxx, snapy, TMKj |
|           61 |      187 | 2024-05-27 | Endpoint               | W   | 1.000      | 0.435        | 0.012 (0.005)    | 0.718 (0.312)    | 0 (0.000) |    15.34 | DDias, krazy, renatoohaxx, snapy, TMKj |
|           60 |      309 | 2024-05-25 | Zero Tenacity          | L   | 1.000      | -            | -                | -                | -         |   -10.22 | DDias, krazy, renatoohaxx, snapy, TMKj |
|           59 |      405 | 2024-05-23 | EXO Clan               | L   | 1.000      | -            | -                | -                | -         |   -21.18 | DDias, krazy, renatoohaxx, snapy, TMKj |
|           58 |      509 | 2024-05-22 | MOUZ NXT               | W   | 1.000      | 0.435        | 0.157 (0.068)    | 0.950 (0.413)    | 0 (0.000) |    18.21 | DDias, krazy, renatoohaxx, snapy, TMKj |
|           57 |      571 | 2024-05-21 | B8                     | L   | 1.000      | -            | -                | -                | -         |    -6.21 | DDias, krazy, renatoohaxx, snapy, TMKj |
|           56 |      591 | 2024-05-21 | Team PeeP              | L   | 1.000      | -            | -                | -                | -         |   -26.08 | DDias, krazy, renatoohaxx, snapy, TMKj |
|           55 |      608 | 2024-05-21 | Soda Gaming            | W   | 1.000      | -            | -                | -                | 0 (0.000) |     4.47 | DDias, krazy, renatoohaxx, snapy, TMKj |
|           54 |      701 | 2024-05-20 | kONO.ECF               | L   | 1.000      | -            | -                | -                | -         |   -18.51 | DDias, krazy, renatoohaxx, snapy, TMKj |
|           53 |      868 | 2024-05-18 | ABT Esports            | W   | 1.000      | -            | -                | -                | 0 (0.000) |     2.61 | DDias, krazy, renatoohaxx, snapy, TMKj |
|           52 |      898 | 2024-05-18 | SAW Youngsters         | W   | 1.000      | -            | -                | -                | 0 (0.000) |     1.33 | DDias, krazy, renatoohaxx, snapy, TMKj |
|           51 |      930 | 2024-05-18 | LEON Esports           | W   | 1.000      | -            | -                | -                | 0 (0.000) |     6.78 | DDias, krazy, renatoohaxx, snapy, TMKj |
|           50 |     1081 | 2024-05-16 | Copenhagen Wolves      | W   | 1.000      | -            | -                | -                | -         |     4.72 | DDias, krazy, renatoohaxx, snapy, TMKj |
|           49 |     1176 | 2024-05-15 | GUN5 Esports           | L   | 1.000      | -            | -                | -                | -         |   -24.47 | DDias, krazy, renatoohaxx, snapy, TMKj |
|           48 |     1205 | 2024-05-15 | EYEBALLERS             | W   | 1.000      | 0.143        | 0.012 (0.002)    | -                | -         |    14.01 | DDias, krazy, renatoohaxx, snapy, TMKj |
|           47 |     1278 | 2024-05-14 | Nexus Gaming           | L   | 1.000      | -            | -                | -                | -         |   -20.92 | DDias, krazy, renatoohaxx, snapy, TMKj |
|           46 |     1372 | 2024-05-12 | AL-QATRAO              | W   | 1.000      | -            | -                | -                | 1 (1.000) |     8.64 | DDias, krazy, renatoohaxx, snapy, TMKj |
|           45 |     1475 | 2024-05-11 | ALL-IN                 | W   | 1.000      | -            | -                | -                | 1 (1.000) |     2.64 | DDias, krazy, renatoohaxx, snapy, TMKj |
|           44 |     1636 | 2024-05-08 | Nemiga Gaming          | L   | 1.000      | -            | -                | -                | -         |    -7.29 | DDias, krazy, renatoohaxx, snapy, TMKj |
|           43 |     2494 | 2024-04-21 | Aurora Young Blud      | W   | 0.943      | 0.333        | 0.008 (0.003)    | 0.506 (0.159)    | -         |     7.29 | DDias, krazy, renatoohaxx, snapy, TMKj |
|           42 |     2508 | 2024-04-21 | Dynamo Eclot           | W   | 0.943      | 0.333        | 0.097 (0.030)    | 0.936 (0.294)    | -         |    17.07 | DDias, krazy, renatoohaxx, snapy, TMKj |
|           41 |     2639 | 2024-04-20 | HOTU                   | W   | 0.935      | 0.333        | -                | 0.524 (0.163)    | -         |    11.10 | DDias, krazy, renatoohaxx, snapy, TMKj |
|           40 |     2721 | 2024-04-19 | UNiTY esports          | W   | 0.929      | 0.333        | 0.021 (0.007)    | 0.766 (0.237)    | -         |    13.35 | DDias, krazy, renatoohaxx, snapy, TMKj |
|           39 |     2787 | 2024-04-18 | Aurora Young Blud      | L   | 0.922      | -            | -                | -                | -         |   -21.90 | DDias, krazy, renatoohaxx, snapy, TMKj |
|           38 |     2911 | 2024-04-16 | los kogutos            | L   | 0.910      | -            | -                | -                | -         |   -19.35 | DDias, krazy, renatoohaxx, snapy, TMKj |
|           37 |     3131 | 2024-04-11 | UNiTY esports          | W   | 0.875      | 0.333        | 0.021 (0.006)    | 0.766 (0.224)    | -         |    10.15 | DDias, krazy, renatoohaxx, snapy, TMKj |
|           36 |     3192 | 2024-04-10 | Dynamo Eclot           | W   | 0.869      | 0.333        | 0.097 (0.028)    | 0.936 (0.271)    | -         |    15.43 | DDias, krazy, renatoohaxx, snapy, TMKj |
|           35 |     3244 | 2024-04-09 | ARROW                  | W   | 0.863      | -            | -                | -                | -         |     6.61 | DDias, krazy, renatoohaxx, snapy, TMKj |
|           34 |     3305 | 2024-04-08 | DMS                    | L   | 0.856      | -            | -                | -                | -         |   -17.93 | DDias, krazy, renatoohaxx, snapy, TMKj |
|           33 |     5103 | 2024-03-03 | esmagaB                | L   | 0.616      | -            | -                | -                | -         |   -14.11 | DDias, krazy, renatoohaxx, snapy, TMKj |
|           32 |     5183 | 2024-03-02 | AL-QATRAO              | W   | 0.610      | -            | -                | -                | 1 (0.610) |     4.78 | DDias, krazy, renatoohaxx, snapy, TMKj |
|           31 |     5359 | 2024-02-27 | Lemondogs              | W   | 0.584      | -            | -                | -                | -         |     2.08 | DDias, krazy, renatoohaxx, snapy, TMKj |
|           30 |     5373 | 2024-02-27 | Grindas                | W   | 0.584      | -            | -                | -                | -         |     1.37 | DDias, krazy, renatoohaxx, snapy, TMKj |
|           29 |     5378 | 2024-02-27 | FAVBET Team            | L   | 0.583      | -            | -                | -                | -         |   -12.57 | DDias, krazy, renatoohaxx, snapy, TMKj |
|           28 |     5665 | 2024-02-22 | Insilio                | L   | 0.550      | -            | -                | -                | -         |    -9.50 | DDias, krazy, renatoohaxx, snapy, TMKj |
|           27 |     5758 | 2024-02-20 | Lausanne-Sport Esports | W   | 0.537      | -            | -                | -                | -         |     3.30 | DDias, krazy, renatoohaxx, snapy, TMKj |
|           26 |     5946 | 2024-02-17 | UNiTY esports          | L   | 0.517      | -            | -                | -                | -         |   -10.19 | DDias, krazy, renatoohaxx, snapy, TMKj |
|           25 |     5988 | 2024-02-16 | HOTU                   | L   | 0.510      | -            | -                | -                | -         |   -11.19 | DDias, krazy, renatoohaxx, snapy, TMKj |
|           24 |     6055 | 2024-02-15 | Team Spirit Academy    | L   | 0.503      | -            | -                | -                | -         |   -12.55 | DDias, krazy, renatoohaxx, snapy, TMKj |
|           23 |     6155 | 2024-02-13 | VP.Prodigy             | W   | 0.491      | 0.371        | 0.008 (0.001)    | 0.752 (0.137)    | -         |     4.45 | DDias, krazy, renatoohaxx, snapy, TMKj |
|           22 |     6334 | 2024-02-08 | GamerLegion Academy    | W   | 0.457      | 0.371        | 0.018 (0.003)    | 0.691 (0.117)    | -         |     3.81 | DDias, krazy, renatoohaxx, snapy, TMKj |
|           21 |     6352 | 2024-02-07 | GODSENT                | L   | 0.451      | -            | -                | -                | -         |   -12.39 | DDias, krazy, renatoohaxx, snapy, TMKj |
|           20 |     6465 | 2024-02-04 | SAW                    | L   | 0.430      | -            | -                | -                | -         |    -1.72 | DDias, krazy, renatoohaxx, snapy, TMKj |
|           19 |     6507 | 2024-02-03 | esmagaB                | W   | 0.424      | -            | -                | -                | -         |     3.92 | DDias, krazy, renatoohaxx, snapy, TMKj |
|           18 |     6591 | 2024-02-02 | ABT Esports            | W   | 0.418      | -            | -                | -                | -         |     0.73 | DDias, krazy, renatoohaxx, snapy, TMKj |
|           17 |     6607 | 2024-02-02 | KOI                    | L   | 0.417      | -            | -                | -                | -         |    -7.35 | DDias, krazy, renatoohaxx, snapy, TMKj |
|           16 |     6623 | 2024-02-02 | OVERFRAG               | W   | 0.417      | -            | -                | -                | -         |     1.34 | DDias, krazy, renatoohaxx, snapy, TMKj |
|           15 |     7044 | 2024-01-26 | INGLORIOUS             | L   | 0.370      | -            | -                | -                | -         |    -9.65 | DDias, krazy, renatoohaxx, snapy, TMKj |
|           14 |     7174 | 2024-01-23 | Zero Tenacity          | L   | 0.351      | -            | -                | -                | -         |    -5.05 | DDias, krazy, renatoohaxx, snapy, TMKj |
|           13 |     8098 | 2024-01-09 | Dynamo Eclot           | L   | 0.257      | -            | -                | -                | -         |    -3.25 | DDias, krazy, renatoohaxx, snapy, TMKj |
|           12 |     8113 | 2024-01-09 | Soda Gaming            | W   | 0.257      | -            | -                | -                | -         |     0.75 | DDias, krazy, renatoohaxx, snapy, TMKj |
|           11 |     8314 | 2023-12-28 | Alliance               | L   | 0.176      | -            | -                | -                | -         |    -3.99 | DDias, krazy, renatoohaxx, snapy, TMKj |
|           10 |     8320 | 2023-12-27 | brazylijski luz        | L   | 0.169      | -            | -                | -                | -         |    -4.15 | DDias, krazy, renatoohaxx, snapy, TMKj |
|            9 |     8576 | 2023-12-16 | UNiTY esports          | L   | 0.098      | -            | -                | -                | -         |    -2.04 | DDias, Icarus, krazy, snapy, TMKj      |
|            8 |     8727 | 2023-12-15 | ex-KRC Genk Esports    | W   | 0.091      | -            | -                | -                | -         |     0.28 | DDias, Icarus, krazy, snapy, TMKj      |
|            7 |     8785 | 2023-12-14 | gbcxz                  | W   | 0.085      | -            | -                | -                | -         |     0.20 | DDias, Icarus, krazy, snapy, TMKj      |
|            6 |     8815 | 2023-12-13 | NOM Esports            | W   | 0.078      | -            | -                | -                | -         |     0.24 | DDias, Icarus, krazy, snapy, TMKj      |
|            5 |     8872 | 2023-12-12 | BLUEJAYS Lite          | W   | 0.071      | -            | -                | -                | -         |     0.09 | DDias, Icarus, krazy, snapy, TMKj      |
|            4 |     8886 | 2023-12-12 | VP.Prodigy             | L   | 0.070      | -            | -                | -                | -         |    -1.68 | DDias, Icarus, krazy, snapy, TMKj      |
|            3 |     9109 | 2023-12-08 | TOOMUCHVIDEOGAMES      | W   | 0.043      | -            | -                | -                | -         |     0.06 | DDias, Icarus, krazy, snapy, TMKj      |
|            2 |     9120 | 2023-12-08 | FALKE ESPORTS          | W   | 0.042      | -            | -                | -                | 1 (0.042) |     0.08 | DDias, Icarus, krazy, snapy, TMKj      |
|            1 |     9277 | 2023-12-05 | Family                 | W   | 0.025      | -            | -                | -                | -         |     0.02 | DDias, Icarus, krazy, snapy, TMKj      |

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
