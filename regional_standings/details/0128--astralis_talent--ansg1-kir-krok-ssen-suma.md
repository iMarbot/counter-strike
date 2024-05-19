### Roster Details<br />
Team Name: Astralis Talent<br />
Roster: ANSG1, kiR, kroK, sSen, suma<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [128](../standings_global.md)<br />
Regional Rank: [91]( ../standings_europe.md)<br />
Final Rank Value:  807.5<br />
<br />
Final Rank Value (807.5) = Starting Rank Value (979.5) + Head To Head Adjustments (-172.1)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.396[<sup>1</sup>](#table2)
- Bounty Collected: 0.364[<sup>2</sup>](#table1)
- Opponent Network: 0.185[<sup>2</sup>](#table1)
- LAN Wins: 0.223[<sup>2</sup>](#table1)

The average of these factors is 0.292<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 979.5
- 400 + ( ( 0.292 - 0.000 ) / ( 0.806 - 0.000 ) ) * 1600 = 979.5


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent                    | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                              |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           84 |       31 | 2024-05-05 | Come on now dawg            | L   | 1.000      | -            | -                | -                | -         |   -26.28 | ANSG1, kiR, kroK, sSen, suma        |
|           83 |       87 | 2024-05-04 | Turów Zgorzelec Esport      | L   | 1.000      | -            | -                | -                | -         |   -19.18 | ANSG1, kiR, kroK, sSen, suma        |
|           82 |      159 | 2024-05-02 | WOPA Esport                 | L   | 1.000      | -            | -                | -                | -         |   -20.74 | ANSG1, kiR, kroK, sSen, suma        |
|           81 |      274 | 2024-04-29 | XI Esport                   | W   | 1.000      | -            | -                | -                | 0 (0.000) |     8.21 | ANSG1, JBOEN, kiR, kroK, tOPZ       |
|           80 |      277 | 2024-04-29 | Preasy Esport               | W   | 1.000      | -            | -                | -                | 0 (0.000) |     9.51 | ANSG1, JBOEN, kiR, kroK, tOPZ       |
|           79 |      328 | 2024-04-28 | Dynamo Eclot                | L   | 1.000      | -            | -                | -                | -         |   -10.81 | ANSG1, JBOEN, kiR, kroK, tOPZ       |
|           78 |      419 | 2024-04-26 | ALTERNATE aTTaX             | W   | 1.000      | 0.143        | 0.110 (0.016)    | -                | 0 (0.000) |    18.51 | ANSG1, JBOEN, kiR, kroK, tOPZ       |
|           77 |      461 | 2024-04-25 | Zero Tenacity               | L   | 1.000      | -            | -                | -                | -         |   -11.46 | ANSG1, JBOEN, kiR, kroK, tOPZ       |
|           76 |      534 | 2024-04-24 | ALTERNATE aTTaX             | W   | 1.000      | 0.143        | 0.110 (0.016)    | -                | 0 (0.000) |    17.95 | ANSG1, JBOEN, kiR, kroK, tOPZ       |
|           75 |      604 | 2024-04-22 | IMMAPROBLEM                 | W   | 1.000      | -            | -                | -                | 0 (0.000) |     5.08 | ANSG1, JBOEN, kiR, kroK, tOPZ       |
|           74 |      653 | 2024-04-21 | MASONIC                     | L   | 1.000      | -            | -                | -                | -         |   -13.51 | ANSG1, JBOEN, kiR, kroK, tOPZ       |
|           73 |      669 | 2024-04-21 | Preasy Esport               | W   | 1.000      | -            | -                | -                | 1 (1.000) |    10.01 | ANSG1, JBOEN, kiR, kroK, tOPZ       |
|           72 |      694 | 2024-04-20 | Kronjyllands Esport         | W   | 1.000      | -            | -                | -                | 1 (1.000) |     3.63 | ANSG1, JBOEN, kiR, kroK, tOPZ       |
|           71 |     1041 | 2024-04-15 | Sashi Academy               | W   | 1.000      | -            | -                | -                | 0 (0.000) |     8.03 | ANSG1, JBOEN, kiR, kroK, tOPZ       |
|           70 |     1059 | 2024-04-15 | Dynamo Eclot                | L   | 1.000      | -            | -                | -                | -         |    -8.51 | ANSG1, JBOEN, kiR, kroK, tOPZ       |
|           69 |     1124 | 2024-04-13 | Lilmix                      | L   | 1.000      | -            | -                | -                | -         |   -22.28 | ANSG1, JBOEN, kiR, kroK, sSen       |
|           68 |     1191 | 2024-04-11 | Illuminar Gaming            | L   | 1.000      | -            | -                | -                | -         |   -16.44 | ANSG1, JBOEN, kiR, kroK, tOPZ       |
|           67 |     1313 | 2024-04-09 | Alliance                    | L   | 1.000      | -            | -                | -                | -         |   -16.79 | ANSG1, JBOEN, kiR, kroK, tOPZ       |
|           66 |     1447 | 2024-04-05 | UNiTY esports (Slovak team) | W   | 0.997      | 0.333        | 0.055 (0.018)    | 0.727 (0.242)    | 0 (0.000) |    16.71 | ANSG1, JBOEN, kiR, kroK, tOPZ       |
|           65 |     1607 | 2024-04-01 | Dynamo Eclot                | L   | 0.970      | -            | -                | -                | -         |    -9.14 | ANSG1, JBOEN, kiR, kroK, tOPZ       |
|           64 |     1609 | 2024-04-01 | Dynamo Eclot                | W   | 0.969      | 0.333        | 0.189 (0.061)    | 0.953 (0.308)    | 0 (0.000) |    21.90 | ANSG1, JBOEN, kiR, kroK, tOPZ       |
|           63 |     1639 | 2024-03-30 | Illuminar Gaming            | L   | 0.957      | -            | -                | -                | -         |   -15.40 | ANSG1, JBOEN, kiR, kroK, tOPZ       |
|           62 |     1678 | 2024-03-29 | WOPA Esport                 | W   | 0.949      | 0.333        | -                | 0.485 (0.154)    | -         |    10.43 | ANSG1, JBOEN, kiR, kroK, tOPZ       |
|           61 |     1768 | 2024-03-27 | Natus Vincere Junior        | L   | 0.937      | -            | -                | -                | -         |   -14.95 | ANSG1, JBOEN, kiR, kroK, tOPZ       |
|           60 |     1793 | 2024-03-26 | Aurora Gaming               | L   | 0.932      | -            | -                | -                | -         |    -0.84 | ANSG1, JBOEN, kiR, kroK, tOPZ       |
|           59 |     1844 | 2024-03-25 | XI Esport                   | W   | 0.925      | -            | -                | -                | -         |     6.68 | ANSG1, JBOEN, kiR, kroK, tOPZ       |
|           58 |     1866 | 2024-03-24 | Permitta Esports            | L   | 0.917      | -            | -                | -                | -         |   -10.37 | ANSG1, JBOEN, kiR, kroK, tOPZ       |
|           57 |     1919 | 2024-03-23 | Passion UA                  | L   | 0.910      | -            | -                | -                | -         |   -12.04 | ANSG1, JBOEN, kiR, kroK, tOPZ       |
|           56 |     1953 | 2024-03-22 | Viperio                     | W   | 0.903      | -            | -                | -                | -         |     6.21 | alexsomfan, ANSG1, JBOEN, kiR, kroK |
|           55 |     2033 | 2024-03-20 | WOPA Esport                 | W   | 0.890      | 0.333        | -                | 0.485 (0.144)    | -         |     9.67 | alexsomfan, ANSG1, JBOEN, kiR, kroK |
|           54 |     2070 | 2024-03-19 | ROSOMAHA                    | W   | 0.884      | -            | -                | -                | -         |     4.47 | alexsomfan, ANSG1, JBOEN, kiR, kroK |
|           53 |     2232 | 2024-03-15 | Viperio                     | L   | 0.856      | -            | -                | -                | -         |   -20.37 | ANSG1, JBOEN, kiR, kroK, tOPZ       |
|           52 |     2396 | 2024-03-11 | XI Esport                   | W   | 0.832      | -            | -                | -                | -         |     5.88 | ANSG1, JBOEN, kiR, kroK, tOPZ       |
|           51 |     2413 | 2024-03-11 | Preasy Esport               | W   | 0.832      | -            | -                | -                | -         |     8.57 | ANSG1, JBOEN, kiR, kroK, tOPZ       |
|           50 |     2516 | 2024-03-09 | NOM Esports                 | L   | 0.817      | -            | -                | -                | -         |   -18.58 | ANSG1, JBOEN, kiR, kroK, tOPZ       |
|           49 |     2541 | 2024-03-08 | ENCE Academy                | W   | 0.810      | -            | -                | -                | -         |    11.25 | ANSG1, JBOEN, kiR, kroK, tOPZ       |
|           48 |     2582 | 2024-03-07 | Passion UA                  | L   | 0.804      | -            | -                | -                | -         |   -11.38 | ANSG1, JBOEN, kiR, kroK, tOPZ       |
|           47 |     2600 | 2024-03-06 | Team Atlantic               | L   | 0.799      | -            | -                | -                | -         |   -22.36 | ANSG1, JBOEN, kiR, kroK, tOPZ       |
|           46 |     2606 | 2024-03-06 | WOPA Esport                 | W   | 0.799      | -            | -                | -                | -         |     7.05 | ANSG1, JBOEN, kiR, kroK, tOPZ       |
|           45 |     2625 | 2024-03-06 | IMMAPROBLEM                 | L   | 0.798      | -            | -                | -                | -         |   -22.40 | ANSG1, JBOEN, kiR, kroK, tOPZ       |
|           44 |     2714 | 2024-03-05 | Permitta Esports            | W   | 0.790      | 0.303        | 0.063 (0.015)    | 1.000 (0.239)    | -         |    13.90 | ANSG1, JBOEN, kiR, kroK, tOPZ       |
|           43 |     2847 | 2024-03-02 | Permitta Esports            | L   | 0.772      | -            | -                | -                | -         |    -9.83 | ANSG1, JBOEN, kiR, kroK, tOPZ       |
|           42 |     2903 | 2024-03-02 | Johnny Speeds               | W   | 0.769      | 0.303        | 0.044 (0.010)    | 0.718 (0.167)    | -         |     9.05 | ANSG1, JBOEN, kiR, kroK, tOPZ       |
|           41 |     2986 | 2024-02-28 | Copenhagen Wolves           | W   | 0.752      | -            | -                | -                | -         |     3.56 | ANSG1, JBOEN, kiR, kroK, tOPZ       |
|           40 |     3048 | 2024-02-27 | Turów Zgorzelec Esport      | L   | 0.743      | -            | -                | -                | -         |   -14.90 | ANSG1, JBOEN, kiR, kroK, tOPZ       |
|           39 |     3224 | 2024-02-23 | Lilmix                      | W   | 0.716      | 0.303        | -                | 0.604 (0.131)    | -         |     3.84 | ANSG1, JBOEN, kiR, kroK, tOPZ       |
|           38 |     3551 | 2024-02-16 | Sangal Esports              | L   | 0.669      | -            | -                | -                | -         |   -16.70 | ANSG1, JBOEN, kiR, kroK, tOPZ       |
|           37 |     3737 | 2024-02-12 | Sashi Esport                | L   | 0.643      | -            | -                | -                | -         |    -7.38 | ANSG1, JBOEN, kiR, kroK, tOPZ       |
|           36 |     3883 | 2024-02-05 | Sashi Esport                | W   | 0.599      | -            | -                | -                | -         |     5.90 | ANSG1, JBOEN, kiR, kroK, tOPZ       |
|           35 |     4106 | 2024-01-31 | Team Atlantic               | W   | 0.565      | -            | -                | -                | -         |     1.59 | ANSG1, JBOEN, kiR, kroK, tOPZ       |
|           34 |     4135 | 2024-01-30 | Copenhagen Wolves           | W   | 0.559      | -            | -                | -                | -         |     2.98 | ANSG1, JBOEN, kiR, kroK, tOPZ       |
|           33 |     4452 | 2024-01-22 | IMMAPROBLEM                 | L   | 0.506      | -            | -                | -                | -         |   -14.61 | ANSG1, JBOEN, kiR, kroK, tOPZ       |
|           32 |     4459 | 2024-01-22 | XI Esport                   | L   | 0.506      | -            | -                | -                | -         |   -13.21 | ANSG1, JBOEN, kiR, kroK, tOPZ       |
|           31 |     4514 | 2024-01-21 | MOUZ NXT                    | L   | 0.496      | -            | -                | -                | -         |    -5.30 | ANSG1, JBOEN, kiR, kroK, tOPZ       |
|           30 |     4569 | 2024-01-20 | Permitta Esports            | W   | 0.489      | 0.333        | 0.063 (0.010)    | 1.000 (0.163)    | -         |     8.20 | ANSG1, JBOEN, kiR, kroK, tOPZ       |
|           29 |     4612 | 2024-01-19 | MOUZ NXT                    | L   | 0.483      | -            | -                | -                | -         |    -5.27 | ANSG1, JBOEN, kiR, kroK, tOPZ       |
|           28 |     4751 | 2024-01-17 | Permitta Esports            | W   | 0.470      | 0.333        | 0.063 (0.010)    | 1.000 (0.157)    | -         |     8.06 | ANSG1, JBOEN, kiR, kroK, tOPZ       |
|           27 |     4830 | 2024-01-15 | Preasy Esport               | W   | 0.459      | -            | -                | -                | -         |     4.12 | ANSG1, JBOEN, kiR, kroK, tOPZ       |
|           26 |     4871 | 2024-01-14 | Zero Tenacity               | W   | 0.449      | 0.333        | 0.095 (0.014)    | 1.000 (0.150)    | -         |     6.40 | ANSG1, JBOEN, kiR, kroK, tOPZ       |
|           25 |     4952 | 2024-01-12 | Nexus Gaming                | W   | 0.436      | -            | -                | -                | -         |     5.87 | ANSG1, JBOEN, kiR, kroK, tOPZ       |
|           24 |     5062 | 2024-01-10 | MOUZ NXT                    | L   | 0.423      | -            | -                | -                | -         |    -4.45 | ANSG1, JBOEN, kiR, kroK, tOPZ       |
|           23 |     5127 | 2024-01-09 | Permitta Esports            | L   | 0.417      | -            | -                | -                | -         |    -6.10 | ANSG1, JBOEN, kiR, kroK, tOPZ       |
|           22 |     5180 | 2024-01-06 | Nexus Gaming                | W   | 0.397      | -            | -                | -                | -         |     5.43 | ANSG1, JBOEN, kiR, kroK, tOPZ       |
|           21 |     5192 | 2024-01-05 | MOUZ NXT                    | L   | 0.389      | -            | -                | -                | -         |    -4.14 | ANSG1, JBOEN, kiR, kroK, tOPZ       |
|           20 |     5323 | 2023-12-19 | Illuminar Gaming            | L   | 0.276      | -            | -                | -                | -         |    -6.55 | ANSG1, JBOEN, kiR, kroK, tOPZ       |
|           19 |     5331 | 2023-12-18 | Nexus Gaming                | W   | 0.270      | -            | -                | -                | -         |     3.79 | ANSG1, JBOEN, kiR, kroK, tOPZ       |
|           18 |     5509 | 2023-12-16 | Passion UA                  | W   | 0.256      | 0.303        | 0.114 (0.009)    | -                | -         |     4.44 | ANSG1, JBOEN, kiR, kroK, tOPZ       |
|           17 |     5619 | 2023-12-14 | Kappa Bar                   | W   | 0.243      | -            | -                | -                | -         |     1.33 | ANSG1, JBOEN, kiR, kroK, tOPZ       |
|           16 |     5655 | 2023-12-13 | Illuminar Gaming            | L   | 0.236      | -            | -                | -                | -         |    -5.71 | ANSG1, JBOEN, kiR, kroK, tOPZ       |
|           15 |     5856 | 2023-12-08 | WOPA Esport                 | W   | 0.203      | -            | -                | -                | -         |     1.63 | ANSG1, JBOEN, kiR, kroK, tOPZ       |
|           14 |     6022 | 2023-12-04 | Sprout Academy              | W   | 0.177      | -            | -                | -                | -         |     0.36 | ANSG1, JBOEN, kiR, kroK, tOPZ       |
|           13 |     6123 | 2023-12-02 | Sashi Esport                | L   | 0.164      | -            | -                | -                | -         |    -4.13 | ANSG1, JBOEN, kiR, kroK, tOPZ       |
|           12 |     6401 | 2023-11-26 | Illuminar Gaming            | L   | 0.124      | -            | -                | -                | -         |    -3.00 | ANSG1, JBOEN, kiR, kroK, MistR      |
|           11 |     6450 | 2023-11-25 | Lazer Cats                  | W   | 0.116      | -            | -                | -                | -         |     0.46 | ANSG1, JBOEN, kiR, kroK, MistR      |
|           10 |     6530 | 2023-11-23 | NOM Esports                 | L   | 0.104      | -            | -                | -                | -         |    -2.71 | ANSG1, JBOEN, kiR, kroK, MistR      |
|            9 |     6595 | 2023-11-21 | Nexus Gaming                | W   | 0.091      | -            | -                | -                | -         |     1.36 | ANSG1, JBOEN, kiR, kroK, MistR      |
|            8 |     6610 | 2023-11-21 | AGO esports                 | L   | 0.089      | -            | -                | -                | -         |    -2.42 | ANSG1, JBOEN, kiR, kroK, MistR      |
|            7 |     6840 | 2023-11-16 | Lazer Cats                  | L   | 0.057      | -            | -                | -                | -         |    -1.57 | ANSG1, JBOEN, kiR, kroK, MistR      |
|            6 |     6876 | 2023-11-15 | PARTIZAN                    | L   | 0.052      | -            | -                | -                | -         |    -1.53 | ANSG1, JBOEN, kiR, kroK, MistR      |
|            5 |     6935 | 2023-11-14 | Nexus Gaming                | W   | 0.044      | -            | -                | -                | -         |     0.64 | ANSG1, JBOEN, kiR, kroK, MistR      |
|            4 |     6957 | 2023-11-13 | MASONIC Academy             | W   | 0.039      | -            | -                | -                | -         |     0.05 | ANSG1, JBOEN, kiR, kroK, MistR      |
|            3 |     6966 | 2023-11-13 | Sashi Esport                | L   | 0.039      | -            | -                | -                | -         |    -0.98 | ANSG1, JBOEN, kiR, kroK, MistR      |
|            2 |     7014 | 2023-11-12 | Zero Tenacity               | L   | 0.030      | -            | -                | -                | -         |    -0.49 | ANSG1, JBOEN, kiR, kroK, MistR      |
|            1 |     7206 | 2023-11-08 | AGO esports                 | W   | 0.004      | -            | -                | -                | -         |     0.01 | ANSG1, JBOEN, kiR, kroK, MistR      |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($4,730.88)
- Divide that value by the 5th highest value among all rosters ($158,437.64)
- The final value (0.03) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-04-21 |      1.000 | $1,428.20      | $1,428.20       |
| 2024-03-25 |      0.925 | $1,448.49      | $1,339.58       |
| 2024-01-21 |      0.496 | $3,000.00      | $1,488.19       |
| 2023-12-19 |      0.276 | $1,500.00      | $414.51         |
| 2023-12-02 |      0.165 | $364.98        | $60.38          |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
