### Roster Details<br />
Team Name: Astralis Talent<br />
Roster: ANSG1, kiR, kroK, sSen, suma<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [179](../standings_global.md)<br />
Regional Rank: [124]( ../standings_europe.md)<br />
Final Rank Value:  749.5<br />
<br />
Final Rank Value (749.5) = Starting Rank Value (922.2) + Head To Head Adjustments (-172.7)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.343[<sup>1</sup>](#table2)
- Bounty Collected: 0.325[<sup>2</sup>](#table1)
- Opponent Network: 0.161[<sup>2</sup>](#table1)
- LAN Wins: 0.199[<sup>2</sup>](#table1)

The average of these factors is 0.257<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 922.2
- 400 + ( ( 0.257 - 0.000 ) / ( 0.787 - 0.000 ) ) * 1600 = 922.2


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent                  | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                              |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           91 |      100 | 2024-05-29 | GamerLegion Academy       | L   | 1.000      | -            | -                | -                | -         |   -13.43 | ANSG1, kiR, kroK, sSen, suma        |
|           90 |      146 | 2024-05-28 | Preasy Esport             | W   | 1.000      | -            | -                | -                | 0 (0.000) |    15.02 | ANSG1, kiR, kroK, sSen, suma        |
|           89 |      168 | 2024-05-27 | Copenhagen Wolves         | L   | 1.000      | -            | -                | -                | -         |   -16.08 | ANSG1, kiR, kroK, sSen, suma        |
|           88 |      179 | 2024-05-27 | Sashi Esport              | L   | 1.000      | -            | -                | -                | -         |    -2.49 | ANSG1, kiR, kroK, sSen, suma        |
|           87 |      196 | 2024-05-27 | VP.Prodigy                | L   | 1.000      | -            | -                | -                | -         |   -10.14 | ANSG1, kiR, kroK, sSen, suma        |
|           86 |      676 | 2024-05-20 | Sashi Academy             | W   | 1.000      | -            | -                | -                | 0 (0.000) |     7.56 | ANSG1, kiR, kroK, sSen, suma        |
|           85 |      694 | 2024-05-20 | Preasy Esport             | W   | 1.000      | -            | -                | -                | 0 (0.000) |    15.62 | ANSG1, kiR, kroK, sSen, suma        |
|           84 |      700 | 2024-05-20 | WOPA Esport               | L   | 1.000      | -            | -                | -                | -         |   -15.14 | ANSG1, kiR, kroK, sSen, suma        |
|           83 |     1549 | 2024-05-10 | DMS                       | L   | 1.000      | -            | -                | -                | -         |   -12.07 | ANSG1, kiR, kroK, sSen, suma        |
|           82 |     1598 | 2024-05-09 | MASONIC                   | W   | 1.000      | 0.143        | 0.018 (0.003)    | -                | 0 (0.000) |    18.99 | ANSG1, kiR, kroK, sSen, suma        |
|           81 |     1666 | 2024-05-08 | DMS                       | L   | 1.000      | -            | -                | -                | -         |   -11.91 | ANSG1, kiR, kroK, sSen, suma        |
|           80 |     1685 | 2024-05-07 | Sashi Esport              | L   | 1.000      | -            | -                | -                | -         |    -1.84 | ANSG1, kiR, kroK, sSen, suma        |
|           79 |     1732 | 2024-05-06 | Copenhagen Wolves         | L   | 1.000      | -            | -                | -                | -         |   -20.46 | ANSG1, kiR, kroK, sSen, suma        |
|           78 |     1746 | 2024-05-06 | WOPA Esport               | L   | 1.000      | -            | -                | -                | -         |   -17.86 | ANSG1, kiR, kroK, sSen, suma        |
|           77 |     1808 | 2024-05-05 | Come on now dawg          | L   | 1.000      | -            | -                | -                | -         |   -26.73 | ANSG1, kiR, kroK, sSen, suma        |
|           76 |     1878 | 2024-05-04 | ex-Turów Zgorzelec Esport | L   | 1.000      | -            | -                | -                | -         |   -19.63 | ANSG1, kiR, kroK, sSen, suma        |
|           75 |     1961 | 2024-05-02 | WOPA Esport               | L   | 1.000      | -            | -                | -                | -         |   -20.52 | ANSG1, kiR, kroK, sSen, suma        |
|           74 |     2100 | 2024-04-29 | XI Esport                 | W   | 0.997      | -            | -                | -                | 0 (0.000) |     7.89 | ANSG1, JBOEN, kiR, kroK, tOPZ       |
|           73 |     2103 | 2024-04-29 | Preasy Esport             | W   | 0.997      | -            | -                | -                | 0 (0.000) |    10.62 | ANSG1, JBOEN, kiR, kroK, tOPZ       |
|           72 |     2169 | 2024-04-28 | Dynamo Eclot              | L   | 0.988      | -            | -                | -                | -         |   -11.79 | ANSG1, JBOEN, kiR, kroK, tOPZ       |
|           71 |     2289 | 2024-04-26 | ALTERNATE aTTaX           | W   | 0.977      | 0.143        | 0.052 (0.007)    | 0.735 (0.103)    | 0 (0.000) |    17.84 | ANSG1, JBOEN, kiR, kroK, tOPZ       |
|           70 |     2336 | 2024-04-25 | Zero Tenacity             | L   | 0.971      | -            | -                | -                | -         |   -10.10 | ANSG1, JBOEN, kiR, kroK, tOPZ       |
|           69 |     2421 | 2024-04-24 | ALTERNATE aTTaX           | W   | 0.963      | 0.143        | 0.052 (0.007)    | -                | 0 (0.000) |    17.05 | ANSG1, JBOEN, kiR, kroK, tOPZ       |
|           68 |     2502 | 2024-04-22 | IMMAPROBLEM               | W   | 0.950      | -            | -                | -                | -         |     4.61 | ANSG1, JBOEN, kiR, kroK, tOPZ       |
|           67 |     2562 | 2024-04-21 | MASONIC                   | L   | 0.942      | -            | -                | -                | -         |   -14.08 | ANSG1, JBOEN, kiR, kroK, tOPZ       |
|           66 |     2581 | 2024-04-21 | Preasy Esport             | W   | 0.941      | -            | -                | -                | 1 (0.941) |    11.07 | ANSG1, JBOEN, kiR, kroK, tOPZ       |
|           65 |     2611 | 2024-04-20 | Kronjyllands Esport       | W   | 0.937      | -            | -                | -                | 1 (0.937) |     3.26 | ANSG1, JBOEN, kiR, kroK, tOPZ       |
|           64 |     3010 | 2024-04-15 | Sashi Academy             | W   | 0.904      | -            | -                | -                | -         |     7.11 | ANSG1, JBOEN, kiR, kroK, tOPZ       |
|           63 |     3032 | 2024-04-15 | Dynamo Eclot              | L   | 0.901      | -            | -                | -                | -         |    -8.25 | ANSG1, JBOEN, kiR, kroK, tOPZ       |
|           62 |     3119 | 2024-04-13 | Lilmix                    | L   | 0.888      | -            | -                | -                | -         |   -15.94 | ANSG1, JBOEN, kiR, kroK, sSen       |
|           61 |     3206 | 2024-04-11 | Illuminar Gaming          | L   | 0.874      | -            | -                | -                | -         |   -15.54 | ANSG1, JBOEN, kiR, kroK, tOPZ       |
|           60 |     3351 | 2024-04-09 | Alliance                  | L   | 0.861      | -            | -                | -                | -         |   -14.44 | ANSG1, JBOEN, kiR, kroK, tOPZ       |
|           59 |     3534 | 2024-04-05 | UNiTY esports             | W   | 0.836      | 0.333        | 0.021 (0.006)    | 0.766 (0.214)    | -         |    13.26 | ANSG1, JBOEN, kiR, kroK, tOPZ       |
|           58 |     3723 | 2024-04-01 | Dynamo Eclot              | L   | 0.808      | -            | -                | -                | -         |    -8.32 | ANSG1, JBOEN, kiR, kroK, tOPZ       |
|           57 |     3726 | 2024-04-01 | Dynamo Eclot              | W   | 0.808      | 0.333        | 0.097 (0.026)    | 0.940 (0.253)    | -         |    17.58 | ANSG1, JBOEN, kiR, kroK, tOPZ       |
|           56 |     3770 | 2024-03-30 | Illuminar Gaming          | L   | 0.796      | -            | -                | -                | -         |   -14.34 | ANSG1, JBOEN, kiR, kroK, tOPZ       |
|           55 |     3814 | 2024-03-29 | WOPA Esport               | W   | 0.788      | 0.333        | -                | 0.594 (0.156)    | -         |     9.11 | ANSG1, JBOEN, kiR, kroK, tOPZ       |
|           54 |     3920 | 2024-03-27 | Natus Vincere Junior      | L   | 0.776      | -            | -                | -                | -         |   -13.79 | ANSG1, JBOEN, kiR, kroK, tOPZ       |
|           53 |     3950 | 2024-03-26 | Aurora Gaming             | L   | 0.771      | -            | -                | -                | -         |    -1.25 | ANSG1, JBOEN, kiR, kroK, tOPZ       |
|           52 |     4007 | 2024-03-25 | Sashi Esport              | L   | 0.765      | -            | -                | -                | -         |   -14.86 | ANSG1, JBOEN, kiR, kroK, tOPZ       |
|           51 |     4017 | 2024-03-25 | XI Esport                 | W   | 0.764      | -            | -                | -                | -         |     4.93 | ANSG1, JBOEN, kiR, kroK, tOPZ       |
|           50 |     4024 | 2024-03-25 | FAVBET Team               | W   | 0.762      | 0.333        | -                | 0.845 (0.215)    | -         |    11.88 | ANSG1, JBOEN, kiR, kroK, tOPZ       |
|           49 |     4048 | 2024-03-24 | Permitta Esports          | L   | 0.756      | -            | -                | -                | -         |    -9.02 | ANSG1, JBOEN, kiR, kroK, tOPZ       |
|           48 |     4109 | 2024-03-23 | Passion UA                | L   | 0.749      | -            | -                | -                | -         |   -10.10 | ANSG1, JBOEN, kiR, kroK, tOPZ       |
|           47 |     4146 | 2024-03-22 | Viperio                   | W   | 0.742      | -            | -                | -                | -         |     4.93 | alexsomfan, ANSG1, JBOEN, kiR, kroK |
|           46 |     4243 | 2024-03-20 | WOPA Esport               | W   | 0.729      | 0.333        | -                | 0.594 (0.144)    | -         |     8.83 | alexsomfan, ANSG1, JBOEN, kiR, kroK |
|           45 |     4285 | 2024-03-19 | ROSOMAHA                  | W   | 0.723      | -            | -                | -                | -         |     3.43 | alexsomfan, ANSG1, JBOEN, kiR, kroK |
|           44 |     4503 | 2024-03-15 | Viperio                   | L   | 0.695      | -            | -                | -                | -         |   -16.89 | ANSG1, JBOEN, kiR, kroK, tOPZ       |
|           43 |     4707 | 2024-03-11 | XI Esport                 | W   | 0.671      | -            | -                | -                | -         |     4.40 | ANSG1, JBOEN, kiR, kroK, tOPZ       |
|           42 |     4730 | 2024-03-11 | Preasy Esport             | W   | 0.671      | -            | -                | -                | -         |     8.26 | ANSG1, JBOEN, kiR, kroK, tOPZ       |
|           41 |     4860 | 2024-03-09 | NOM Esports               | L   | 0.656      | -            | -                | -                | -         |   -16.23 | ANSG1, JBOEN, kiR, kroK, tOPZ       |
|           40 |     4891 | 2024-03-08 | ENCE Academy              | W   | 0.649      | -            | -                | -                | -         |     8.35 | ANSG1, JBOEN, kiR, kroK, tOPZ       |
|           39 |     4954 | 2024-03-07 | Passion UA                | L   | 0.642      | -            | -                | -                | -         |    -9.00 | ANSG1, JBOEN, kiR, kroK, tOPZ       |
|           38 |     4979 | 2024-03-06 | Team Atlantic             | L   | 0.638      | -            | -                | -                | -         |   -18.13 | ANSG1, JBOEN, kiR, kroK, tOPZ       |
|           37 |     4988 | 2024-03-06 | WOPA Esport               | W   | 0.638      | -            | -                | -                | -         |     6.44 | ANSG1, JBOEN, kiR, kroK, tOPZ       |
|           36 |     5009 | 2024-03-06 | IMMAPROBLEM               | L   | 0.637      | -            | -                | -                | -         |   -18.02 | ANSG1, JBOEN, kiR, kroK, tOPZ       |
|           35 |     5124 | 2024-03-05 | Permitta Esports          | W   | 0.629      | 0.303        | 0.025 (0.005)    | 1.000 (0.190)    | -         |    10.79 | ANSG1, JBOEN, kiR, kroK, tOPZ       |
|           34 |     5293 | 2024-03-02 | Permitta Esports          | L   | 0.611      | -            | -                | -                | -         |    -8.32 | ANSG1, JBOEN, kiR, kroK, tOPZ       |
|           33 |     5364 | 2024-03-02 | Johnny Speeds             | W   | 0.608      | 0.303        | 0.056 (0.010)    | 0.683 (0.126)    | -         |    11.80 | ANSG1, JBOEN, kiR, kroK, tOPZ       |
|           32 |     5459 | 2024-02-28 | Sashi Esport              | W   | 0.591      | -            | -                | -                | -         |     5.75 | ANSG1, JBOEN, kiR, kroK, tOPZ       |
|           31 |     5467 | 2024-02-28 | Copenhagen Wolves         | W   | 0.591      | -            | -                | -                | -         |     3.12 | ANSG1, JBOEN, kiR, kroK, tOPZ       |
|           30 |     5542 | 2024-02-27 | ex-Turów Zgorzelec Esport | L   | 0.582      | -            | -                | -                | -         |   -12.12 | ANSG1, JBOEN, kiR, kroK, tOPZ       |
|           29 |     5782 | 2024-02-23 | Lilmix                    | W   | 0.555      | -            | -                | -                | -         |     6.57 | ANSG1, JBOEN, kiR, kroK, tOPZ       |
|           28 |     6181 | 2024-02-16 | Sangal Esports            | L   | 0.508      | -            | -                | -                | -         |    -5.36 | ANSG1, JBOEN, kiR, kroK, tOPZ       |
|           27 |     6408 | 2024-02-12 | Sashi Esport              | L   | 0.482      | -            | -                | -                | -         |    -4.93 | ANSG1, JBOEN, kiR, kroK, tOPZ       |
|           26 |     6606 | 2024-02-05 | Sashi Esport              | W   | 0.438      | -            | -                | -                | -         |     4.20 | ANSG1, JBOEN, kiR, kroK, tOPZ       |
|           25 |     6629 | 2024-02-05 | WOPA Esport               | W   | 0.437      | -            | -                | -                | -         |     4.59 | ANSG1, JBOEN, kiR, kroK, tOPZ       |
|           24 |     6925 | 2024-01-31 | Team Atlantic             | W   | 0.404      | -            | -                | -                | -         |     1.24 | ANSG1, JBOEN, kiR, kroK, tOPZ       |
|           23 |     6961 | 2024-01-30 | Copenhagen Wolves         | W   | 0.398      | -            | -                | -                | -         |     2.50 | ANSG1, JBOEN, kiR, kroK, tOPZ       |
|           22 |     7448 | 2024-01-22 | IMMAPROBLEM               | L   | 0.345      | -            | -                | -                | -         |    -9.83 | ANSG1, JBOEN, kiR, kroK, tOPZ       |
|           21 |     7458 | 2024-01-22 | XI Esport                 | L   | 0.344      | -            | -                | -                | -         |    -8.80 | ANSG1, JBOEN, kiR, kroK, tOPZ       |
|           20 |     7532 | 2024-01-21 | MOUZ NXT                  | L   | 0.335      | -            | -                | -                | -         |    -2.80 | ANSG1, JBOEN, kiR, kroK, tOPZ       |
|           19 |     7608 | 2024-01-20 | Permitta Esports          | W   | 0.328      | 0.333        | 0.025 (0.003)    | 1.000 (0.109)    | -         |     5.58 | ANSG1, JBOEN, kiR, kroK, tOPZ       |
|           18 |     7664 | 2024-01-19 | MOUZ NXT                  | L   | 0.322      | -            | -                | -                | -         |    -2.71 | ANSG1, JBOEN, kiR, kroK, tOPZ       |
|           17 |     7832 | 2024-01-17 | Permitta Esports          | W   | 0.309      | 0.333        | 0.025 (0.003)    | 1.000 (0.103)    | -         |     5.34 | ANSG1, JBOEN, kiR, kroK, tOPZ       |
|           16 |     7955 | 2024-01-15 | Preasy Esport             | W   | 0.298      | -            | -                | -                | -         |     4.14 | ANSG1, JBOEN, kiR, kroK, tOPZ       |
|           15 |     8012 | 2024-01-14 | Zero Tenacity             | W   | 0.288      | 0.333        | 0.147 (0.014)    | -                | -         |     6.30 | ANSG1, JBOEN, kiR, kroK, tOPZ       |
|           14 |     8129 | 2024-01-12 | Nexus Gaming              | W   | 0.275      | -            | -                | -                | -         |     4.05 | ANSG1, JBOEN, kiR, kroK, tOPZ       |
|           13 |     8286 | 2024-01-10 | MOUZ NXT                  | L   | 0.262      | -            | -                | -                | -         |    -2.09 | ANSG1, JBOEN, kiR, kroK, tOPZ       |
|           12 |     8393 | 2024-01-09 | Permitta Esports          | L   | 0.256      | -            | -                | -                | -         |    -3.66 | ANSG1, JBOEN, kiR, kroK, tOPZ       |
|           11 |     8467 | 2024-01-06 | Nexus Gaming              | W   | 0.236      | -            | -                | -                | -         |     3.48 | ANSG1, JBOEN, kiR, kroK, tOPZ       |
|           10 |     8482 | 2024-01-05 | MOUZ NXT                  | L   | 0.228      | -            | -                | -                | -         |    -1.82 | ANSG1, JBOEN, kiR, kroK, tOPZ       |
|            9 |     8664 | 2023-12-19 | brazylijski luz           | L   | 0.115      | -            | -                | -                | -         |    -2.35 | ANSG1, JBOEN, kiR, kroK, tOPZ       |
|            8 |     8679 | 2023-12-18 | Nexus Gaming              | W   | 0.109      | -            | -                | -                | -         |     1.63 | ANSG1, JBOEN, kiR, kroK, tOPZ       |
|            7 |     8773 | 2023-12-17 | detoks                    | W   | 0.102      | -            | -                | -                | -         |     0.28 | ANSG1, JBOEN, kiR, kroK, tOPZ       |
|            6 |     8915 | 2023-12-16 | Passion UA                | W   | 0.095      | -            | -                | -                | -         |     1.91 | ANSG1, JBOEN, kiR, kroK, tOPZ       |
|            5 |     9059 | 2023-12-14 | Kappa Bar                 | W   | 0.082      | -            | -                | -                | -         |     0.26 | ANSG1, JBOEN, kiR, kroK, tOPZ       |
|            4 |     9118 | 2023-12-13 | brazylijski luz           | L   | 0.075      | -            | -                | -                | -         |    -1.54 | ANSG1, JBOEN, kiR, kroK, tOPZ       |
|            3 |     9397 | 2023-12-08 | WOPA Esport               | W   | 0.042      | -            | -                | -                | -         |     0.48 | ANSG1, JBOEN, kiR, kroK, tOPZ       |
|            2 |     9624 | 2023-12-04 | Sprout Academy            | W   | 0.016      | -            | -                | -                | -         |     0.03 | ANSG1, JBOEN, kiR, kroK, tOPZ       |
|            1 |     9774 | 2023-12-02 | Sashi Esport              | L   | 0.003      | -            | -                | -                | -         |    -0.08 | ANSG1, JBOEN, kiR, kroK, tOPZ       |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($3,632.82)
- Divide that value by the 5th highest value among all rosters ($300,806.11)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-04-21 |      0.942 | $1,428.20      | $1,345.78       |
| 2024-03-25 |      0.765 | $1,448.49      | $1,107.52       |
| 2024-01-21 |      0.335 | $3,000.00      | $1,005.00       |
| 2023-12-19 |      0.115 | $1,500.00      | $172.92         |
| 2023-12-02 |      0.004 | $364.98        | $1.60           |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
