### Roster Details<br />
Team Name: VP.Prodigy<br />
Roster: dwushka, KusMe, shady, Something, xdENiSZERA<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [80](../standings_global.md)<br />
Regional Rank: [56]( ../standings_europe.md)<br />
Final Rank Value:  906.7<br />
<br />
Final Rank Value (906.7) = Starting Rank Value (833.0) + Head To Head Adjustments (73.7)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.322[<sup>1</sup>](#table2)
- Bounty Collected: 0.305[<sup>2</sup>](#table1)
- Opponent Network: 0.214[<sup>2</sup>](#table1)
- LAN Wins: 0.010[<sup>2</sup>](#table1)

The average of these factors is 0.213<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 833.0
- 400 + ( ( 0.213 - 0.000 ) / ( 0.786 - 0.000 ) ) * 1600 = 833.0


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent               | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                       |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           76 |       70 | 2024-05-29 | HOTU                   | L   | 1.000      | -            | -                | -                | -         |   -17.06 | dwushka, KusMe, shady, Something, xdENiSZERA |
|           75 |       88 | 2024-05-29 | Nexus Gaming           | W   | 1.000      | 0.354        | 0.014 (0.005)    | 0.825 (0.292)    | 0 (0.000) |    12.72 | dwushka, KusMe, shady, Something, xdENiSZERA |
|           74 |      130 | 2024-05-28 | Illuminar Gaming       | W   | 1.000      | -            | -                | -                | 0 (0.000) |     9.50 | dwushka, KusMe, shady, Something, xdENiSZERA |
|           73 |      181 | 2024-05-27 | Permitta Esports       | W   | 1.000      | 0.435        | 0.029 (0.012)    | 1.000 (0.435)    | 0 (0.000) |    10.87 | dwushka, KusMe, shady, Something, xdENiSZERA |
|           72 |      188 | 2024-05-27 | Astralis Talent        | W   | 1.000      | 0.143        | 0.012 (0.002)    | -                | 0 (0.000) |    10.70 | dwushka, KusMe, shady, Something, xdENiSZERA |
|           71 |      201 | 2024-05-26 | Denial                 | W   | 1.000      | -            | -                | -                | 0 (0.000) |     5.69 | dwushka, KusMe, shady, Something, xdENiSZERA |
|           70 |      351 | 2024-05-24 | DMS                    | W   | 1.000      | 0.435        | -                | 0.751 (0.326)    | 0 (0.000) |    18.15 | dwushka, KusMe, shady, Something, xdENiSZERA |
|           69 |      360 | 2024-05-24 | Nemiga Gaming          | L   | 1.000      | -            | -                | -                | -         |    -6.51 | dwushka, KusMe, shady, Something, xdENiSZERA |
|           68 |      458 | 2024-05-22 | ALTERNATE aTTaX        | W   | 1.000      | 0.435        | 0.052 (0.022)    | 0.679 (0.295)    | 0 (0.000) |    17.55 | dwushka, KusMe, shady, Something, xdENiSZERA |
|           67 |      673 | 2024-05-20 | los kogutos            | W   | 1.000      | 0.372        | 0.007 (0.002)    | 0.299 (0.111)    | 0 (0.000) |    17.94 | dwushka, KusMe, shady, Something, xdENiSZERA |
|           66 |      709 | 2024-05-20 | SINNERS Esports        | L   | 1.000      | -            | -                | -                | -         |    -9.85 | dwushka, KusMe, shady, Something, xdENiSZERA |
|           65 |      877 | 2024-05-18 | Copenhagen Wolves      | W   | 1.000      | 0.354        | -                | 0.330 (0.117)    | -         |     8.41 | dwushka, KusMe, shady, Something, xdENiSZERA |
|           64 |      907 | 2024-05-18 | Copenhagen Wolves      | W   | 1.000      | -            | -                | -                | -         |     9.03 | dwushka, KusMe, shady, Something, xdENiSZERA |
|           63 |      972 | 2024-05-17 | WOPA Esport            | W   | 1.000      | 0.354        | 0.003 (0.001)    | 0.594 (0.210)    | -         |    12.53 | dwushka, KusMe, shady, Something, xdENiSZERA |
|           62 |     1070 | 2024-05-16 | esmagaB                | L   | 1.000      | -            | -                | -                | -         |   -14.93 | dwushka, KusMe, shady, Something, xdENiSZERA |
|           61 |     1245 | 2024-05-14 | LEON Esports           | W   | 1.000      | -            | -                | -                | -         |    11.26 | dwushka, KusMe, shady, Something, xdENiSZERA |
|           60 |     1320 | 2024-05-13 | WOPA Esport            | W   | 1.000      | -            | -                | -                | -         |    12.93 | dwushka, KusMe, shady, Something, xdENiSZERA |
|           59 |     1332 | 2024-05-13 | Nemiga Gaming          | L   | 1.000      | -            | -                | -                | -         |    -3.56 | dwushka, KusMe, shady, Something, xdENiSZERA |
|           58 |     1715 | 2024-05-06 | Young Gods             | W   | 1.000      | 0.372        | -                | 0.240 (0.089)    | -         |     6.63 | dwushka, KusMe, shady, Something, xdENiSZERA |
|           57 |     1763 | 2024-05-05 | Nemiga Gaming          | L   | 1.000      | -            | -                | -                | -         |    -2.82 | dwushka, KusMe, shady, Something, xdENiSZERA |
|           56 |     1766 | 2024-05-05 | Eternal Fire Academy   | W   | 1.000      | -            | -                | -                | -         |     6.30 | dwushka, KusMe, shady, Something, xdENiSZERA |
|           55 |     1848 | 2024-05-04 | naChille               | W   | 1.000      | -            | -                | -                | -         |     8.87 | dwushka, KusMe, shady, Something, xdENiSZERA |
|           54 |     1987 | 2024-05-01 | Lausanne-Sport Esports | L   | 1.000      | -            | -                | -                | -         |   -17.81 | dwushka, KusMe, shady, Something, xdENiSZERA |
|           53 |     2054 | 2024-04-29 | LOADING                | W   | 0.997      | -            | -                | -                | -         |     6.70 | dwushka, KusMe, shady, Something, xdENiSZERA |
|           52 |     2077 | 2024-04-29 | Nexus Gaming           | W   | 0.996      | 0.143        | 0.014 (0.002)    | 0.825 (0.117)    | -         |    20.35 | dwushka, KusMe, shady, Something, xdENiSZERA |
|           51 |     2112 | 2024-04-28 | brazylijski luz        | L   | 0.990      | -            | -                | -                | -         |   -11.41 | dwushka, KusMe, shady, Something, xdENiSZERA |
|           50 |     2122 | 2024-04-28 | LEON Esports           | W   | 0.989      | -            | -                | -                | -         |    13.60 | dwushka, KusMe, shady, Something, xdENiSZERA |
|           49 |     2182 | 2024-04-27 | RUSH B                 | L   | 0.983      | -            | -                | -                | -         |   -13.91 | dwushka, KusMe, shady, Something, xdENiSZERA |
|           48 |     2265 | 2024-04-26 | V1dar Gaming           | L   | 0.976      | -            | -                | -                | -         |   -19.00 | dwushka, KusMe, shady, Something, xdENiSZERA |
|           47 |     2317 | 2024-04-25 | EXO Clan               | L   | 0.970      | -            | -                | -                | -         |    -6.71 | dwushka, KusMe, shady, Something, xdENiSZERA |
|           46 |     2361 | 2024-04-24 | LOG Esports            | W   | 0.964      | -            | -                | -                | -         |     5.20 | dwushka, KusMe, shady, Something, xdENiSZERA |
|           45 |     2393 | 2024-04-24 | V1dar Gaming           | W   | 0.961      | -            | -                | -                | -         |    10.74 | dwushka, KusMe, shady, Something, xdENiSZERA |
|           44 |     2706 | 2024-04-19 | HOTU                   | L   | 0.930      | -            | -                | -                | -         |   -12.72 | dwushka, KusMe, shady, Something, xdENiSZERA |
|           43 |     2777 | 2024-04-18 | Dynamo Eclot           | L   | 0.922      | -            | -                | -                | -         |    -7.50 | dwushka, KusMe, shady, Something, xdENiSZERA |
|           42 |     2944 | 2024-04-15 | JANO Esports           | L   | 0.904      | -            | -                | -                | -         |   -17.45 | dwushka, KusMe, shady, Something, xdENiSZERA |
|           41 |     2985 | 2024-04-14 | Lemondogs              | L   | 0.896      | -            | -                | -                | -         |   -22.34 | dwushka, KusMe, shady, Something, xdENiSZERA |
|           40 |     3125 | 2024-04-11 | Aurora Young Blud      | W   | 0.876      | 0.333        | 0.008 (0.002)    | 0.506 (0.148)    | -         |    10.82 | dwushka, KusMe, shady, Something, xdENiSZERA |
|           39 |     3283 | 2024-04-08 | Kappa Bar              | W   | 0.857      | -            | -                | -                | -         |     3.74 | dwushka, KusMe, shady, Something, xdENiSZERA |
|           38 |     3354 | 2024-04-07 | GUN5 Esports           | L   | 0.849      | -            | -                | -                | -         |   -19.79 | dwushka, KusMe, shady, Something, xdENiSZERA |
|           37 |     4007 | 2024-03-23 | FORZE Esports          | L   | 0.750      | -            | -                | -                | -         |    -6.02 | dwushka, KusMe, shady, Something, xdENiSZERA |
|           36 |     4047 | 2024-03-22 | ex-Guild Eagles        | W   | 0.742      | 0.143        | 0.015 (0.002)    | -                | -         |    14.62 | dwushka, KusMe, shady, Something, xdENiSZERA |
|           35 |     4142 | 2024-03-20 | TSM                    | W   | 0.729      | 0.143        | 0.011 (0.001)    | -                | -         |     8.62 | dwushka, KusMe, shady, Something, xdENiSZERA |
|           34 |     4666 | 2024-03-10 | 1win                   | L   | 0.663      | -            | -                | -                | -         |    -7.35 | dwushka, KusMe, shady, Something, xdENiSZERA |
|           33 |     4811 | 2024-03-07 | Permitta Esports       | L   | 0.644      | -            | -                | -                | -         |    -6.72 | dwushka, KusMe, shady, Something, xdENiSZERA |
|           32 |     4962 | 2024-03-05 | FORZE Youngsters       | W   | 0.631      | -            | -                | -                | -         |     4.83 | dwushka, KusMe, shady, Something, xdENiSZERA |
|           31 |     5089 | 2024-03-03 | SHIPACHI               | W   | 0.617      | -            | -                | -                | -         |     4.67 | dwushka, KusMe, shady, Something, xdENiSZERA |
|           30 |     5095 | 2024-03-03 | W43                    | W   | 0.617      | -            | -                | -                | -         |     4.19 | dwushka, KusMe, shady, Something, xdENiSZERA |
|           29 |     5101 | 2024-03-03 | BebraFPL1              | W   | 0.616      | -            | -                | -                | -         |     2.62 | dwushka, KusMe, shady, Something, xdENiSZERA |
|           28 |     5234 | 2024-03-01 | Entropiq               | W   | 0.604      | -            | -                | -                | -         |     6.70 | dwushka, KusMe, shady, Something, xdENiSZERA |
|           27 |     5375 | 2024-02-27 | The Chosen Few         | W   | 0.583      | -            | -                | -                | -         |     7.64 | dwushka, KusMe, shady, Something, xdENiSZERA |
|           26 |     5418 | 2024-02-26 | ARCRED                 | L   | 0.577      | -            | -                | -                | -         |   -10.30 | dwushka, KusMe, shady, Something, xdENiSZERA |
|           25 |     5602 | 2024-02-23 | Sashi Esport           | L   | 0.558      | -            | -                | -                | -         |    -3.24 | dwushka, KusMe, shady, Something, xdENiSZERA |
|           24 |     5644 | 2024-02-22 | Copenhagen Wolves      | W   | 0.551      | -            | -                | -                | -         |     3.76 | dwushka, KusMe, shady, Something, xdENiSZERA |
|           23 |     5695 | 2024-02-21 | DASH                   | W   | 0.544      | -            | -                | -                | -         |     5.88 | dwushka, KusMe, shady, Something, xdENiSZERA |
|           22 |     5859 | 2024-02-18 | L1ZUN4IKI              | L   | 0.525      | -            | -                | -                | -         |   -12.64 | dwushka, KusMe, shady, Something, xdENiSZERA |
|           21 |     6036 | 2024-02-15 | NOM Esports            | W   | 0.504      | -            | -                | -                | -         |     3.70 | dwushka, KusMe, shady, Something, xdENiSZERA |
|           20 |     6155 | 2024-02-13 | Rhyno Esports          | L   | 0.491      | -            | -                | -                | -         |    -4.45 | dwushka, KusMe, shady, Something, xdENiSZERA |
|           19 |     6329 | 2024-02-08 | GenOne                 | L   | 0.457      | -            | -                | -                | -         |   -12.31 | dwushka, KusMe, shady, Something, xdENiSZERA |
|           18 |     6406 | 2024-02-05 | Team Secret            | W   | 0.438      | -            | -                | -                | -         |     3.25 | dwushka, KusMe, shady, Something, xdENiSZERA |
|           17 |     6705 | 2024-01-31 | ex-Anonymo Esports     | W   | 0.404      | -            | -                | -                | -         |     4.66 | dwushka, KusMe, shady, Something, xdENiSZERA |
|           16 |     8301 | 2023-12-30 | Metizport              | L   | 0.189      | -            | -                | -                | -         |    -1.99 | dwushka, KusMe, shady, Something, xdENiSZERA |
|           15 |     8315 | 2023-12-28 | brazylijski luz        | W   | 0.175      | -            | -                | -                | -         |     2.53 | dwushka, KusMe, shady, Something, xdENiSZERA |
|           14 |     8322 | 2023-12-26 | Alliance               | W   | 0.163      | -            | -                | -                | -         |     2.73 | dwushka, KusMe, shady, Something, xdENiSZERA |
|           13 |     8406 | 2023-12-19 | ARCRED                 | W   | 0.115      | -            | -                | -                | -         |     1.48 | dwushka, KusMe, shady, Something, xdENiSZERA |
|           12 |     8444 | 2023-12-17 | UNiTY esports          | W   | 0.105      | -            | -                | -                | -         |     2.03 | dwushka, KusMe, shady, Something, xdENiSZERA |
|           11 |     8467 | 2023-12-17 | naChille               | W   | 0.103      | -            | -                | -                | -         |     0.85 | dwushka, KusMe, shady, Something, xdENiSZERA |
|           10 |     8482 | 2023-12-17 | 1win Academy           | W   | 0.103      | -            | -                | -                | -         |     0.71 | dwushka, KusMe, shady, Something, xdENiSZERA |
|            9 |     8623 | 2023-12-16 | Nemiga Gaming          | L   | 0.096      | -            | -                | -                | -         |    -0.27 | dwushka, KusMe, shady, Something, xdENiSZERA |
|            8 |     8644 | 2023-12-16 | VaselineWorms          | W   | 0.095      | -            | -                | -                | -         |     1.01 | dwushka, KusMe, shady, Something, xdENiSZERA |
|            7 |     8733 | 2023-12-15 | UNiTY esports          | W   | 0.091      | -            | -                | -                | -         |     1.78 | dwushka, KusMe, shady, Something, xdENiSZERA |
|            6 |     8830 | 2023-12-13 | ex-KRC Genk Esports    | W   | 0.078      | -            | -                | -                | -         |     0.62 | dwushka, KusMe, shady, Something, xdENiSZERA |
|            5 |     8886 | 2023-12-12 | Rhyno Esports          | W   | 0.070      | -            | -                | -                | -         |     1.68 | dwushka, KusMe, shady, Something, xdENiSZERA |
|            4 |     9034 | 2023-12-09 | LF0                    | W   | 0.049      | -            | -                | -                | 1 (0.049) |     0.35 | dwushka, KusMe, shady, Something, xdENiSZERA |
|            3 |     9121 | 2023-12-08 | HOTU                   | W   | 0.042      | -            | -                | -                | 1 (0.042) |     0.70 | dwushka, KusMe, shady, Something, xdENiSZERA |
|            2 |     9149 | 2023-12-07 | Donstu Esports         | W   | 0.038      | -            | -                | -                | -         |     0.18 | dwushka, KusMe, shady, Something, xdENiSZERA |
|            1 |     9276 | 2023-12-05 | Team LRP Poland        | W   | 0.025      | -            | -                | -                | -         |     0.28 | dwushka, KusMe, shady, Something, xdENiSZERA |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($2,364.48)
- Divide that value by the 5th highest value among all rosters ($300,806.11)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-03-03 |      0.617 | $2,500.00      | $1,542.94       |
| 2024-02-20 |      0.537 | $100.00        | $53.67          |
| 2023-12-17 |      0.105 | $3,500.00      | $366.04         |
| 2023-12-09 |      0.049 | $8,138.46      | $401.84         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
