### Roster Details<br />
Team Name: VP.Prodigy<br />
Roster: dwushka, KusMe, shady, Something, xdENiSZERA<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [73](../standings_global.md)<br />
Regional Rank: [51]( ../standings_europe.md)<br />
Final Rank Value:  931.7<br />
<br />
Final Rank Value (931.7) = Starting Rank Value (841.6) + Head To Head Adjustments (90.1)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.322[<sup>1</sup>](#table2)
- Bounty Collected: 0.301[<sup>2</sup>](#table1)
- Opponent Network: 0.236[<sup>2</sup>](#table1)
- LAN Wins: 0.010[<sup>2</sup>](#table1)

The average of these factors is 0.217<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 841.6
- 400 + ( ( 0.217 - 0.000 ) / ( 0.787 - 0.000 ) ) * 1600 = 841.6


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
|           81 |       75 | 2024-05-29 | HOTU                   | L   | 1.000      | -            | -                | -                | -         |   -17.71 | dwushka, KusMe, shady, Something, xdENiSZERA |
|           80 |       95 | 2024-05-29 | Nexus Gaming           | W   | 1.000      | 0.354        | 0.003 (0.001)    | 0.857 (0.304)    | 0 (0.000) |    10.45 | dwushka, KusMe, shady, Something, xdENiSZERA |
|           79 |      118 | 2024-05-28 | CYBERSHOKE Esports     | W   | 1.000      | 0.372        | -                | 0.468 (0.174)    | 0 (0.000) |     9.73 | dwushka, KusMe, shady, Something, xdENiSZERA |
|           78 |      137 | 2024-05-28 | Illuminar Gaming       | W   | 1.000      | -            | -                | -                | 0 (0.000) |     8.92 | dwushka, KusMe, shady, Something, xdENiSZERA |
|           77 |      189 | 2024-05-27 | Permitta Esports       | W   | 1.000      | 0.435        | 0.025 (0.011)    | 1.000 (0.435)    | 0 (0.000) |    10.70 | dwushka, KusMe, shady, Something, xdENiSZERA |
|           76 |      196 | 2024-05-27 | Astralis Talent        | W   | 1.000      | 0.143        | 0.012 (0.002)    | -                | 0 (0.000) |    10.14 | dwushka, KusMe, shady, Something, xdENiSZERA |
|           75 |      209 | 2024-05-26 | Denial                 | W   | 1.000      | -            | -                | -                | 0 (0.000) |     5.17 | dwushka, KusMe, shady, Something, xdENiSZERA |
|           74 |      360 | 2024-05-24 | DMS                    | W   | 1.000      | 0.435        | -                | 0.754 (0.327)    | 0 (0.000) |    17.52 | dwushka, KusMe, shady, Something, xdENiSZERA |
|           73 |      369 | 2024-05-24 | Nemiga Gaming          | L   | 1.000      | -            | -                | -                | -         |    -7.00 | dwushka, KusMe, shady, Something, xdENiSZERA |
|           72 |      464 | 2024-05-22 | ALTERNATE aTTaX        | W   | 1.000      | 0.435        | 0.052 (0.023)    | 0.735 (0.319)    | 0 (0.000) |    16.73 | dwushka, KusMe, shady, Something, xdENiSZERA |
|           71 |      684 | 2024-05-20 | los kogutos            | W   | 1.000      | 0.372        | 0.007 (0.002)    | -                | -         |    16.92 | dwushka, KusMe, shady, Something, xdENiSZERA |
|           70 |      721 | 2024-05-20 | SINNERS Esports        | L   | 1.000      | -            | -                | -                | -         |   -10.44 | dwushka, KusMe, shady, Something, xdENiSZERA |
|           69 |      889 | 2024-05-18 | Copenhagen Wolves      | W   | 1.000      | 0.354        | -                | 0.358 (0.127)    | -         |     7.94 | dwushka, KusMe, shady, Something, xdENiSZERA |
|           68 |      919 | 2024-05-18 | Copenhagen Wolves      | W   | 1.000      | -            | -                | -                | -         |     8.50 | dwushka, KusMe, shady, Something, xdENiSZERA |
|           67 |      984 | 2024-05-17 | WOPA Esport            | W   | 1.000      | 0.354        | 0.003 (0.001)    | 0.594 (0.210)    | -         |    11.66 | dwushka, KusMe, shady, Something, xdENiSZERA |
|           66 |     1080 | 2024-05-16 | esmagaB                | L   | 1.000      | -            | -                | -                | -         |   -15.89 | dwushka, KusMe, shady, Something, xdENiSZERA |
|           65 |     1255 | 2024-05-14 | LEON Esports           | W   | 1.000      | -            | -                | -                | -         |    10.40 | dwushka, KusMe, shady, Something, xdENiSZERA |
|           64 |     1332 | 2024-05-13 | WOPA Esport            | W   | 1.000      | -            | -                | -                | -         |    11.89 | dwushka, KusMe, shady, Something, xdENiSZERA |
|           63 |     1344 | 2024-05-13 | Nemiga Gaming          | L   | 1.000      | -            | -                | -                | -         |    -4.02 | dwushka, KusMe, shady, Something, xdENiSZERA |
|           62 |     1631 | 2024-05-08 | Grannys Knockers       | W   | 1.000      | 0.372        | 0.006 (0.002)    | 0.517 (0.192)    | -         |    15.90 | dwushka, KusMe, shady, Something, xdENiSZERA |
|           61 |     1737 | 2024-05-06 | Young Gods             | W   | 1.000      | -            | -                | -                | -         |     6.18 | dwushka, KusMe, shady, Something, xdENiSZERA |
|           60 |     1786 | 2024-05-05 | Nemiga Gaming          | L   | 1.000      | -            | -                | -                | -         |    -3.02 | dwushka, KusMe, shady, Something, xdENiSZERA |
|           59 |     1789 | 2024-05-05 | Eternal Fire Academy   | W   | 1.000      | -            | -                | -                | -         |     5.93 | dwushka, KusMe, shady, Something, xdENiSZERA |
|           58 |     1871 | 2024-05-04 | naChille               | W   | 1.000      | -            | -                | -                | -         |     8.37 | dwushka, KusMe, shady, Something, xdENiSZERA |
|           57 |     2016 | 2024-05-01 | Lausanne-Sport Esports | L   | 1.000      | -            | -                | -                | -         |   -16.49 | dwushka, KusMe, shady, Something, xdENiSZERA |
|           56 |     2088 | 2024-04-29 | LOADING                | W   | 0.997      | -            | -                | -                | -         |     6.06 | dwushka, KusMe, shady, Something, xdENiSZERA |
|           55 |     2112 | 2024-04-29 | Nexus Gaming           | W   | 0.996      | 0.143        | -                | 0.857 (0.122)    | -         |    20.02 | dwushka, KusMe, shady, Something, xdENiSZERA |
|           54 |     2147 | 2024-04-28 | brazylijski luz        | L   | 0.990      | -            | -                | -                | -         |   -11.81 | dwushka, KusMe, shady, Something, xdENiSZERA |
|           53 |     2157 | 2024-04-28 | LEON Esports           | W   | 0.989      | -            | -                | -                | -         |    13.12 | dwushka, KusMe, shady, Something, xdENiSZERA |
|           52 |     2217 | 2024-04-27 | RUSH B                 | L   | 0.983      | -            | -                | -                | -         |   -14.15 | dwushka, KusMe, shady, Something, xdENiSZERA |
|           51 |     2301 | 2024-04-26 | V1dar Gaming           | L   | 0.976      | -            | -                | -                | -         |   -19.10 | dwushka, KusMe, shady, Something, xdENiSZERA |
|           50 |     2357 | 2024-04-25 | EXO Clan               | L   | 0.970      | -            | -                | -                | -         |    -6.63 | dwushka, KusMe, shady, Something, xdENiSZERA |
|           49 |     2402 | 2024-04-24 | LOG Esports            | W   | 0.964      | -            | -                | -                | -         |     4.57 | dwushka, KusMe, shady, Something, xdENiSZERA |
|           48 |     2438 | 2024-04-24 | V1dar Gaming           | W   | 0.961      | -            | -                | -                | -         |    10.63 | dwushka, KusMe, shady, Something, xdENiSZERA |
|           47 |     2762 | 2024-04-19 | HOTU                   | L   | 0.930      | -            | -                | -                | -         |   -13.04 | dwushka, KusMe, shady, Something, xdENiSZERA |
|           46 |     2833 | 2024-04-18 | Dynamo Eclot           | L   | 0.922      | -            | -                | -                | -         |    -8.04 | dwushka, KusMe, shady, Something, xdENiSZERA |
|           45 |     3005 | 2024-04-15 | JANO Esports           | L   | 0.904      | -            | -                | -                | -         |   -18.10 | dwushka, KusMe, shady, Something, xdENiSZERA |
|           44 |     3050 | 2024-04-14 | Lemondogs              | L   | 0.896      | -            | -                | -                | -         |   -22.95 | dwushka, KusMe, shady, Something, xdENiSZERA |
|           43 |     3195 | 2024-04-11 | Aurora Young Blud      | W   | 0.876      | 0.333        | 0.008 (0.002)    | 0.506 (0.148)    | -         |    10.28 | dwushka, KusMe, shady, Something, xdENiSZERA |
|           42 |     3259 | 2024-04-10 | Denial                 | W   | 0.869      | -            | -                | -                | -         |     4.63 | dwushka, KusMe, shady, Something, xdENiSZERA |
|           41 |     3363 | 2024-04-08 | Kappa Bar              | W   | 0.857      | -            | -                | -                | -         |     3.52 | dwushka, KusMe, shady, Something, xdENiSZERA |
|           40 |     3437 | 2024-04-07 | GUN5 Esports           | L   | 0.849      | -            | -                | -                | -         |   -19.96 | dwushka, KusMe, shady, Something, xdENiSZERA |
|           39 |     4105 | 2024-03-23 | FORZE Esports          | L   | 0.750      | -            | -                | -                | -         |    -6.23 | dwushka, KusMe, shady, Something, xdENiSZERA |
|           38 |     4145 | 2024-03-22 | ex-Guild Eagles        | W   | 0.742      | 0.143        | 0.015 (0.002)    | -                | -         |    14.37 | dwushka, KusMe, shady, Something, xdENiSZERA |
|           37 |     4244 | 2024-03-20 | TSM                    | W   | 0.729      | -            | -                | -                | -         |     8.68 | dwushka, KusMe, shady, Something, xdENiSZERA |
|           36 |     4791 | 2024-03-10 | 1win                   | L   | 0.663      | -            | -                | -                | -         |    -8.10 | dwushka, KusMe, shady, Something, xdENiSZERA |
|           35 |     4940 | 2024-03-07 | Permitta Esports       | L   | 0.644      | -            | -                | -                | -         |    -6.69 | dwushka, KusMe, shady, Something, xdENiSZERA |
|           34 |     5105 | 2024-03-05 | FORZE Youngsters       | W   | 0.631      | -            | -                | -                | -         |     5.19 | dwushka, KusMe, shady, Something, xdENiSZERA |
|           33 |     5235 | 2024-03-03 | SHIPACHI               | W   | 0.617      | -            | -                | -                | -         |     4.37 | dwushka, KusMe, shady, Something, xdENiSZERA |
|           32 |     5242 | 2024-03-03 | W43                    | W   | 0.617      | -            | -                | -                | -         |     3.91 | dwushka, KusMe, shady, Something, xdENiSZERA |
|           31 |     5249 | 2024-03-03 | BebraFPL1              | W   | 0.616      | -            | -                | -                | -         |     2.42 | dwushka, KusMe, shady, Something, xdENiSZERA |
|           30 |     5383 | 2024-03-01 | Entropiq               | W   | 0.604      | -            | -                | -                | -         |     6.35 | dwushka, KusMe, shady, Something, xdENiSZERA |
|           29 |     5528 | 2024-02-27 | The Chosen Few         | W   | 0.583      | -            | -                | -                | -         |     6.91 | dwushka, KusMe, shady, Something, xdENiSZERA |
|           28 |     5576 | 2024-02-26 | ARCRED                 | L   | 0.577      | -            | -                | -                | -         |   -10.73 | dwushka, KusMe, shady, Something, xdENiSZERA |
|           27 |     5762 | 2024-02-23 | Sashi Esport           | L   | 0.558      | -            | -                | -                | -         |    -3.57 | dwushka, KusMe, shady, Something, xdENiSZERA |
|           26 |     5804 | 2024-02-22 | Copenhagen Wolves      | W   | 0.551      | -            | -                | -                | -         |     3.83 | dwushka, KusMe, shady, Something, xdENiSZERA |
|           25 |     5858 | 2024-02-21 | DASH                   | W   | 0.544      | -            | -                | -                | -         |     5.75 | dwushka, KusMe, shady, Something, xdENiSZERA |
|           24 |     6031 | 2024-02-18 | L1ZUN4IKI              | L   | 0.525      | -            | -                | -                | -         |   -12.93 | dwushka, KusMe, shady, Something, xdENiSZERA |
|           23 |     6215 | 2024-02-15 | NOM Esports            | W   | 0.504      | -            | -                | -                | -         |     3.46 | dwushka, KusMe, shady, Something, xdENiSZERA |
|           22 |     6340 | 2024-02-13 | Rhyno Esports          | L   | 0.491      | -            | -                | -                | -         |    -4.74 | dwushka, KusMe, shady, Something, xdENiSZERA |
|           21 |     6517 | 2024-02-08 | GenOne                 | L   | 0.457      | -            | -                | -                | -         |   -12.45 | dwushka, KusMe, shady, Something, xdENiSZERA |
|           20 |     6552 | 2024-02-07 | ex-sYnck               | W   | 0.451      | -            | -                | -                | -         |     4.99 | dwushka, KusMe, shady, Something, xdENiSZERA |
|           19 |     6604 | 2024-02-05 | Team Secret            | W   | 0.438      | -            | -                | -                | -         |     3.10 | dwushka, KusMe, shady, Something, xdENiSZERA |
|           18 |     6916 | 2024-01-31 | ex-Anonymo Esports     | W   | 0.404      | -            | -                | -                | -         |     4.39 | dwushka, KusMe, shady, Something, xdENiSZERA |
|           17 |     7419 | 2024-01-23 | kONO.ECF               | W   | 0.351      | 0.371        | 0.013 (0.002)    | -                | -         |     5.84 | dwushka, KusMe, shady, Something, xdENiSZERA |
|           16 |     8557 | 2023-12-30 | Metizport              | L   | 0.189      | -            | -                | -                | -         |    -2.04 | dwushka, KusMe, shady, Something, xdENiSZERA |
|           15 |     8572 | 2023-12-28 | brazylijski luz        | W   | 0.175      | -            | -                | -                | -         |     2.50 | dwushka, KusMe, shady, Something, xdENiSZERA |
|           14 |     8579 | 2023-12-26 | Alliance               | W   | 0.163      | -            | -                | -                | -         |     2.69 | dwushka, KusMe, shady, Something, xdENiSZERA |
|           13 |     8663 | 2023-12-19 | ARCRED                 | W   | 0.115      | -            | -                | -                | -         |     1.44 | dwushka, KusMe, shady, Something, xdENiSZERA |
|           12 |     8702 | 2023-12-17 | UNiTY esports          | W   | 0.105      | -            | -                | -                | -         |     1.99 | dwushka, KusMe, shady, Something, xdENiSZERA |
|           11 |     8727 | 2023-12-17 | naChille               | W   | 0.103      | -            | -                | -                | -         |     0.82 | dwushka, KusMe, shady, Something, xdENiSZERA |
|           10 |     8742 | 2023-12-17 | 1win Academy           | W   | 0.103      | -            | -                | -                | -         |     0.69 | dwushka, KusMe, shady, Something, xdENiSZERA |
|            9 |     8884 | 2023-12-16 | Nemiga Gaming          | L   | 0.096      | -            | -                | -                | -         |    -0.28 | dwushka, KusMe, shady, Something, xdENiSZERA |
|            8 |     8905 | 2023-12-16 | VaselineWorms          | W   | 0.095      | -            | -                | -                | -         |     0.99 | dwushka, KusMe, shady, Something, xdENiSZERA |
|            7 |     8994 | 2023-12-15 | UNiTY esports          | W   | 0.091      | -            | -                | -                | -         |     1.75 | dwushka, KusMe, shady, Something, xdENiSZERA |
|            6 |     9094 | 2023-12-13 | ex-KRC Genk Esports    | W   | 0.078      | -            | -                | -                | -         |     0.78 | dwushka, KusMe, shady, Something, xdENiSZERA |
|            5 |     9150 | 2023-12-12 | Rhyno Esports          | W   | 0.070      | -            | -                | -                | -         |     1.67 | dwushka, KusMe, shady, Something, xdENiSZERA |
|            4 |     9300 | 2023-12-09 | LF0                    | W   | 0.049      | -            | -                | -                | 1 (0.049) |     0.34 | dwushka, KusMe, shady, Something, xdENiSZERA |
|            3 |     9390 | 2023-12-08 | HOTU                   | W   | 0.042      | -            | -                | -                | 1 (0.042) |     0.70 | dwushka, KusMe, shady, Something, xdENiSZERA |
|            2 |     9422 | 2023-12-07 | Donstu Esports         | W   | 0.038      | -            | -                | -                | -         |     0.18 | dwushka, KusMe, shady, Something, xdENiSZERA |
|            1 |     9558 | 2023-12-05 | Team LRP Poland        | W   | 0.025      | -            | -                | -                | -         |     0.27 | dwushka, KusMe, shady, Something, xdENiSZERA |

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
