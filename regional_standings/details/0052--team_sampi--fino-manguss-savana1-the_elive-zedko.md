### Roster Details<br />
Team Name: Team Sampi<br />
Roster: fino, manguss, sAvana1, The eLiVe, ZEDKO<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [52](../standings_global.md)<br />
Regional Rank: [37]( ../standings_europe.md)<br />
Final Rank Value:  1012.4<br />
<br />
Final Rank Value (1012.4) = Starting Rank Value (1040.1) + Head To Head Adjustments (-27.7)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.509[<sup>1</sup>](#table2)
- Bounty Collected: 0.435[<sup>2</sup>](#table1)
- Opponent Network: 0.319[<sup>2</sup>](#table1)
- LAN Wins: 0.028[<sup>2</sup>](#table1)

The average of these factors is 0.323<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1040.1
- 400 + ( ( 0.323 - 0.000 ) / ( 0.806 - 0.000 ) ) * 1600 = 1040.1


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent                    | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                   |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           63 |       11 | 2024-05-05 | RUSH B (Russian team)       | W   | 1.000      | -            | -                | -                | 0 (0.000) |     9.35 | fino, manguss, sAvana1, The eLiVe, ZEDKO |
|           62 |      147 | 2024-05-02 | Permitta Esports            | W   | 1.000      | 0.435        | 0.063 (0.027)    | 1.000 (0.435)    | 0 (0.000) |    11.42 | fino, manguss, sAvana1, The eLiVe, ZEDKO |
|           61 |      211 | 2024-05-01 | ALTERNATE aTTaX             | L   | 1.000      | -            | -                | -                | -         |   -18.48 | fino, manguss, sAvana1, The eLiVe, ZEDKO |
|           60 |      220 | 2024-05-01 | ENCE Academy                | W   | 1.000      | -            | -                | -                | 0 (0.000) |     7.02 | fino, manguss, sAvana1, The eLiVe, ZEDKO |
|           59 |      228 | 2024-04-30 | GamerLegion Academy         | W   | 1.000      | 0.435        | -                | 0.567 (0.246)    | 0 (0.000) |    11.27 | fino, manguss, sAvana1, The eLiVe, ZEDKO |
|           58 |      254 | 2024-04-30 | ALTERNATE aTTaX             | L   | 1.000      | -            | -                | -                | -         |   -18.58 | fino, manguss, sAvana1, The eLiVe, ZEDKO |
|           57 |      496 | 2024-04-25 | Dynamo Eclot                | L   | 1.000      | -            | -                | -                | -         |   -17.64 | fino, manguss, sAvana1, The eLiVe, ZEDKO |
|           56 |      552 | 2024-04-24 | Permitta Esports            | W   | 1.000      | 0.371        | 0.063 (0.023)    | 1.000 (0.371)    | 0 (0.000) |    11.88 | fino, manguss, sAvana1, The eLiVe, ZEDKO |
|           55 |      591 | 2024-04-23 | Dynamo Eclot                | L   | 1.000      | -            | -                | -                | -         |   -16.39 | fino, manguss, sAvana1, The eLiVe, ZEDKO |
|           54 |      672 | 2024-04-21 | ALTERNATE aTTaX             | W   | 1.000      | 0.371        | 0.110 (0.041)    | 0.723 (0.268)    | 0 (0.000) |    10.74 | fino, manguss, sAvana1, The eLiVe, ZEDKO |
|           53 |      849 | 2024-04-19 | BLEED Esports               | L   | 1.000      | -            | -                | -                | -         |   -12.33 | fino, manguss, sAvana1, The eLiVe, ZEDKO |
|           52 |      909 | 2024-04-18 | Permitta Esports            | W   | 1.000      | 0.371        | 0.063 (0.023)    | 1.000 (0.371)    | -         |    12.55 | fino, manguss, sAvana1, The eLiVe, ZEDKO |
|           51 |      954 | 2024-04-17 | NOM Esports                 | L   | 1.000      | -            | -                | -                | -         |   -27.59 | fino, manguss, sAvana1, The eLiVe, ZEDKO |
|           50 |     1021 | 2024-04-16 | SAW                         | W   | 1.000      | 0.384        | 0.263 (0.101)    | -                | -         |    28.81 | fino, manguss, sAvana1, The eLiVe, ZEDKO |
|           49 |     1025 | 2024-04-16 | Team Secret                 | W   | 1.000      | -            | -                | -                | -         |     4.64 | fino, manguss, sAvana1, The eLiVe, ZEDKO |
|           48 |     1051 | 2024-04-15 | ENCE Academy                | L   | 1.000      | -            | -                | -                | -         |   -23.11 | fino, manguss, sAvana1, The eLiVe, ZEDKO |
|           47 |     1122 | 2024-04-13 | BetBoom Team                | L   | 1.000      | -            | -                | -                | -         |    -3.69 | fino, manguss, sAvana1, The eLiVe, ZEDKO |
|           46 |     1190 | 2024-04-11 | Turów Zgorzelec Esport      | W   | 1.000      | 0.371        | -                | 0.640 (0.237)    | -         |     5.97 | fino, manguss, sAvana1, The eLiVe, ZEDKO |
|           45 |     1417 | 2024-04-06 | ENTERPRISE esports          | W   | 1.000      | -            | -                | -                | -         |    10.69 | fino, manguss, sAvana1, The eLiVe, ZEDKO |
|           44 |     1556 | 2024-04-03 | Ninjas in Pyjamas           | W   | 0.983      | 0.384        | 0.241 (0.091)    | -                | -         |    21.56 | fino, manguss, sAvana1, The eLiVe, ZEDKO |
|           43 |     1809 | 2024-03-26 | DUSTY                       | W   | 0.932      | -            | -                | -                | -         |     5.25 | fino, manguss, sAvana1, The eLiVe, ZEDKO |
|           42 |     2107 | 2024-03-18 | Grannys Knockers            | L   | 0.876      | -            | -                | -                | -         |   -17.38 | fino, manguss, sAvana1, The eLiVe, ZEDKO |
|           41 |     2160 | 2024-03-17 | Passion UA                  | W   | 0.869      | 0.371        | 0.114 (0.037)    | 0.980 (0.316)    | -         |    11.14 | fino, manguss, sAvana1, The eLiVe, ZEDKO |
|           40 |     2179 | 2024-03-16 | SINNERS Esports             | L   | 0.864      | -            | -                | -                | -         |   -13.95 | fino, manguss, sAvana1, The eLiVe, ZEDKO |
|           39 |     2186 | 2024-03-16 | MOUZ NXT                    | W   | 0.863      | 0.371        | 0.215 (0.069)    | 1.000 (0.320)    | -         |    15.39 | fino, manguss, sAvana1, The eLiVe, ZEDKO |
|           38 |     2221 | 2024-03-15 | Dynamo Eclot                | L   | 0.857      | -            | -                | -                | -         |   -11.13 | fino, manguss, sAvana1, The eLiVe, ZEDKO |
|           37 |     2233 | 2024-03-15 | Permitta Esports            | W   | 0.856      | 0.371        | -                | 1.000 (0.317)    | -         |    13.29 | fino, manguss, sAvana1, The eLiVe, ZEDKO |
|           36 |     2281 | 2024-03-14 | Passion UA                  | L   | 0.850      | -            | -                | -                | -         |   -15.47 | fino, manguss, sAvana1, The eLiVe, ZEDKO |
|           35 |     2388 | 2024-03-12 | MOUZ NXT                    | W   | 0.836      | 0.371        | 0.215 (0.067)    | 1.000 (0.310)    | -         |    15.50 | fino, manguss, sAvana1, The eLiVe, ZEDKO |
|           34 |     2471 | 2024-03-10 | Sashi Esport                | W   | 0.823      | 0.143        | 0.193 (0.023)    | -                | -         |    13.78 | fino, manguss, sAvana1, The eLiVe, ZEDKO |
|           33 |     2517 | 2024-03-09 | ENTERPRISE esports          | W   | 0.817      | -            | -                | -                | -         |    10.71 | fino, manguss, sAvana1, The eLiVe, ZEDKO |
|           32 |     2656 | 2024-03-06 | GODSENT                     | W   | 0.796      | -            | -                | -                | -         |     7.17 | fino, manguss, sAvana1, The eLiVe, ZEDKO |
|           31 |     2703 | 2024-03-05 | UNiTY esports (Slovak team) | W   | 0.791      | -            | -                | -                | -         |     8.02 | fino, manguss, sAvana1, The eLiVe, ZEDKO |
|           30 |     2765 | 2024-03-04 | Lan Party Hotel             | W   | 0.784      | -            | -                | -                | -         |     0.99 | fino, manguss, sAvana1, The eLiVe, ZEDKO |
|           29 |     2771 | 2024-03-04 | Sangal Esports              | L   | 0.783      | -            | -                | -                | -         |   -19.24 | fino, manguss, sAvana1, The eLiVe, ZEDKO |
|           28 |     2902 | 2024-03-02 | ENTERPRISE esports          | L   | 0.769      | -            | -                | -                | -         |   -14.03 | fino, manguss, sAvana1, The eLiVe, ZEDKO |
|           27 |     3114 | 2024-02-25 | Dynamo Eclot                | L   | 0.729      | -            | -                | -                | -         |    -7.42 | fino, manguss, sAvana1, The eLiVe, ZEDKO |
|           26 |     3225 | 2024-02-23 | Entropiq                    | W   | 0.716      | -            | -                | -                | -         |     5.88 | fino, manguss, sAvana1, The eLiVe, ZEDKO |
|           25 |     3324 | 2024-02-21 | Sashi Esport                | L   | 0.704      | -            | -                | -                | -         |    -8.24 | fino, manguss, sAvana1, The eLiVe, ZEDKO |
|           24 |     3427 | 2024-02-19 | Viperio                     | W   | 0.690      | -            | -                | -                | -         |     3.30 | fino, manguss, sAvana1, The eLiVe, ZEDKO |
|           23 |     3464 | 2024-02-18 | BIG Academy                 | L   | 0.683      | -            | -                | -                | -         |   -14.93 | fino, manguss, sAvana1, The eLiVe, ZEDKO |
|           22 |     3505 | 2024-02-17 | Team Secret                 | W   | 0.677      | -            | -                | -                | -         |     3.16 | fino, manguss, sAvana1, The eLiVe, ZEDKO |
|           21 |     3656 | 2024-02-14 | Viperio                     | W   | 0.656      | -            | -                | -                | -         |     2.65 | fino, manguss, sAvana1, The eLiVe, ZEDKO |
|           20 |     3767 | 2024-02-10 | Zero Tenacity               | W   | 0.632      | -            | -                | -                | -         |     8.23 | fino, sAvana1, T4gg3D, The eLiVe, ZEDKO  |
|           19 |     4001 | 2024-02-03 | Sashi Esport                | W   | 0.584      | -            | -                | -                | -         |    10.74 | fino, sAvana1, T4gg3D, The eLiVe, ZEDKO  |
|           18 |     4023 | 2024-02-02 | B8                          | L   | 0.578      | -            | -                | -                | -         |   -10.63 | fino, sAvana1, T4gg3D, The eLiVe, ZEDKO  |
|           17 |     4045 | 2024-02-02 | ZOTIX                       | W   | 0.578      | -            | -                | -                | -         |     0.61 | fino, sAvana1, T4gg3D, The eLiVe, ZEDKO  |
|           16 |     4085 | 2024-02-01 | Metizport                   | L   | 0.571      | -            | -                | -                | -         |    -9.33 | fino, sAvana1, T4gg3D, The eLiVe, ZEDKO  |
|           15 |     4165 | 2024-01-29 | Insilio                     | L   | 0.553      | -            | -                | -                | -         |   -10.44 | fino, sAvana1, T4gg3D, The eLiVe, ZEDKO  |
|           14 |     4430 | 2024-01-23 | Guild Eagles                | L   | 0.512      | -            | -                | -                | -         |    -6.99 | fino, sAvana1, T4gg3D, The eLiVe, ZEDKO  |
|           13 |     4434 | 2024-01-23 | Viperio                     | L   | 0.511      | -            | -                | -                | -         |   -14.89 | fino, sAvana1, T4gg3D, The eLiVe, ZEDKO  |
|           12 |     4455 | 2024-01-22 | Rebels Gaming               | W   | 0.506      | -            | -                | -                | -         |    10.38 | fino, sAvana1, T4gg3D, The eLiVe, ZEDKO  |
|           11 |     4466 | 2024-01-22 | Pera Esports                | W   | 0.505      | -            | -                | -                | -         |     5.93 | fino, sAvana1, T4gg3D, The eLiVe, ZEDKO  |
|           10 |     4474 | 2024-01-22 | ALTERNATE aTTaX             | L   | 0.505      | -            | -                | -                | -         |    -7.26 | fino, sAvana1, T4gg3D, The eLiVe, ZEDKO  |
|            9 |     5098 | 2024-01-09 | HAVU Gaming                 | L   | 0.418      | -            | -                | -                | -         |    -9.55 | fino, sAvana1, T4gg3D, The eLiVe, ZEDKO  |
|            8 |     5105 | 2024-01-09 | WOPA Esport                 | W   | 0.418      | -            | -                | -                | -         |     2.38 | fino, sAvana1, T4gg3D, The eLiVe, ZEDKO  |
|            7 |     6423 | 2023-11-25 | Dynamo Eclot                | W   | 0.118      | -            | -                | -                | 1 (0.118) |     0.44 | fino, matys, sAvana1, T4gg3D, The eLiVe  |
|            6 |     6489 | 2023-11-24 | SINNERS Esports             | W   | 0.111      | -            | -                | -                | 1 (0.111) |     1.51 | fino, matys, sAvana1, T4gg3D, The eLiVe  |
|            5 |     6981 | 2023-11-13 | Pompa Team                  | L   | 0.037      | -            | -                | -                | -         |    -1.12 | fino, matys, sAvana1, T4gg3D, The eLiVe  |
|            4 |     7018 | 2023-11-12 | MOUZ NXT                    | L   | 0.030      | -            | -                | -                | -         |    -0.40 | fino, matys, sAvana1, T4gg3D, The eLiVe  |
|            3 |     7110 | 2023-11-10 | Ex-Anonymo Esports          | W   | 0.016      | -            | -                | -                | -         |     0.09 | fino, matys, sAvana1, T4gg3D, The eLiVe  |
|            2 |     7123 | 2023-11-09 | SINNERS Academy             | W   | 0.012      | -            | -                | -                | 1 (0.012) |     0.05 | fino, matys, sAvana1, T4gg3D, The eLiVe  |
|            1 |     7145 | 2023-11-09 | ENTERPRISE esports          | W   | 0.011      | -            | -                | -                | 1 (0.011) |     0.02 | fino, matys, sAvana1, T4gg3D, The eLiVe  |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($17,148.52)
- Divide that value by the 5th highest value among all rosters ($158,437.64)
- The final value (0.11) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-04-25 |      1.000 | $5,000.00      | $5,000.00       |
| 2024-04-14 |      1.000 | $1,905.29      | $1,905.29       |
| 2024-03-18 |      0.876 | $5,000.00      | $4,380.32       |
| 2024-03-17 |      0.872 | $649.40        | $566.12         |
| 2023-11-25 |      0.118 | $44,849.28     | $5,296.78       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
