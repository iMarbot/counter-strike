### Roster Details<br />
Team Name: UNiTY esports<br />
Roster: K1-FiDa, Levi, M1key, NIO, Pechyn<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [104](../standings_global.md)<br />
Regional Rank: [74]( ../standings_europe.md)<br />
Final Rank Value:  859.8<br />
<br />
Final Rank Value (859.8) = Starting Rank Value (925.7) + Head To Head Adjustments (-65.8)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.375[<sup>1</sup>](#table2)
- Bounty Collected: 0.352[<sup>2</sup>](#table1)
- Opponent Network: 0.232[<sup>2</sup>](#table1)
- LAN Wins: 0.074[<sup>2</sup>](#table1)

The average of these factors is 0.258<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 925.7
- 400 + ( ( 0.258 - 0.000 ) / ( 0.786 - 0.000 ) ) * 1600 = 925.7


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent                  | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                            |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           98 |       89 | 2024-05-29 | Rebels Gaming             | W   | 1.000      | 0.371        | 0.062 (0.023)    | -                | 0 (0.000) |    23.77 | K1-FiDa, Levi, M1key, NIO, Pechyn |
|           97 |      113 | 2024-05-28 | GamerLegion Academy       | L   | 1.000      | -            | -                | -                | -         |   -17.76 | K1-FiDa, Levi, M1key, NIO, Pechyn |
|           96 |      126 | 2024-05-28 | Necrotic Esports          | W   | 1.000      | -            | -                | -                | 0 (0.000) |     5.03 | K1-FiDa, Levi, M1key, NIO, Pechyn |
|           95 |      185 | 2024-05-27 | 9INE                      | W   | 1.000      | -            | -                | -                | 0 (0.000) |     3.75 | K1-FiDa, Levi, M1key, NIO, Pechyn |
|           94 |      210 | 2024-05-26 | ghoulsW                   | L   | 1.000      | -            | -                | -                | -         |   -26.66 | K1-FiDa, Levi, M1key, NIO, Pechyn |
|           93 |      256 | 2024-05-25 | MASONIC                   | W   | 1.000      | -            | -                | -                | 0 (0.000) |    11.83 | K1-FiDa, Levi, M1key, NIO, Pechyn |
|           92 |      295 | 2024-05-25 | iNation                   | L   | 1.000      | -            | -                | -                | -         |   -20.90 | K1-FiDa, Levi, M1key, NIO, Pechyn |
|           91 |      403 | 2024-05-23 | SINNERS Esports           | L   | 1.000      | -            | -                | -                | -         |   -12.29 | K1-FiDa, Levi, M1key, NIO, Pechyn |
|           90 |      481 | 2024-05-22 | Grannys Knockers          | W   | 1.000      | -            | -                | -                | 0 (0.000) |    13.34 | K1-FiDa, Levi, M1key, NIO, Pechyn |
|           89 |      578 | 2024-05-21 | ThunderFlash              | W   | 1.000      | -            | -                | -                | 0 (0.000) |    17.11 | K1-FiDa, Levi, M1key, Mix, Pechyn |
|           88 |      626 | 2024-05-21 | Rebels Gaming             | W   | 1.000      | 0.371        | 0.062 (0.023)    | -                | 0 (0.000) |    24.21 | K1-FiDa, Levi, M1key, NIO, Pechyn |
|           87 |      766 | 2024-05-19 | MANGANES                  | L   | 1.000      | -            | -                | -                | -         |   -26.39 | K1-FiDa, Levi, M1key, NIO, Pechyn |
|           86 |      776 | 2024-05-19 | ghoulsW                   | L   | 1.000      | -            | -                | -                | -         |   -27.37 | K1-FiDa, Levi, M1key, NIO, Pechyn |
|           85 |      789 | 2024-05-19 | Infinite Gaming           | W   | 1.000      | -            | -                | -                | 0 (0.000) |     3.21 | K1-FiDa, Levi, M1key, NIO, Pechyn |
|           84 |      997 | 2024-05-17 | BRUTE                     | W   | 1.000      | -            | -                | -                | 0 (0.000) |     4.14 | K1-FiDa, Levi, M1key, NIO, Pechyn |
|           83 |     1084 | 2024-05-16 | Team Flow                 | W   | 1.000      | -            | -                | -                | -         |     4.30 | K1-FiDa, Levi, M1key, NIO, Pechyn |
|           82 |     1328 | 2024-05-13 | Johnny Speeds             | L   | 1.000      | -            | -                | -                | -         |    -9.28 | K1-FiDa, Levi, M1key, NIO, Pechyn |
|           81 |     1476 | 2024-05-11 | GamerLegion Academy       | W   | 1.000      | 0.333        | 0.018 (0.006)    | 0.691 (0.230)    | -         |    13.40 | K1-FiDa, Levi, M1key, NIO, Pechyn |
|           80 |     1532 | 2024-05-10 | Zero Tenacity             | L   | 1.000      | -            | -                | -                | -         |    -8.97 | K1-FiDa, Levi, M1key, NIO, Pechyn |
|           79 |     1584 | 2024-05-09 | FAVBET Team               | L   | 1.000      | -            | -                | -                | -         |   -12.89 | K1-FiDa, Levi, M1key, NIO, Pechyn |
|           78 |     1656 | 2024-05-08 | ex-Turów Zgorzelec Esport | W   | 1.000      | -            | -                | -                | -         |     9.10 | K1-FiDa, Levi, M1key, NIO, Pechyn |
|           77 |     1687 | 2024-05-07 | Preasy Esport             | W   | 1.000      | 0.333        | -                | 0.642 (0.214)    | -         |    11.16 | K1-FiDa, Levi, M1key, NIO, Pechyn |
|           76 |     1790 | 2024-05-05 | Verdant                   | L   | 1.000      | -            | -                | -                | -         |   -16.97 | K1-FiDa, Levi, M1key, NIO, Pechyn |
|           75 |     1847 | 2024-05-04 | WOPA Esport               | W   | 1.000      | 0.333        | -                | 0.594 (0.198)    | -         |    10.38 | K1-FiDa, Levi, M1key, NIO, Pechyn |
|           74 |     1893 | 2024-05-03 | NOM Esports               | L   | 1.000      | -            | -                | -                | -         |   -23.39 | K1-FiDa, Levi, M1key, NIO, Pechyn |
|           73 |     2086 | 2024-04-29 | ex-Turów Zgorzelec Esport | W   | 0.994      | -            | -                | -                | -         |     8.27 | K1-FiDa, Levi, M1key, NIO, Pechyn |
|           72 |     2127 | 2024-04-28 | WOPA Esport               | W   | 0.989      | 0.333        | -                | 0.594 (0.196)    | -         |    10.35 | K1-FiDa, Levi, M1key, NIO, Pechyn |
|           71 |     2721 | 2024-04-19 | Rhyno Esports             | L   | 0.929      | -            | -                | -                | -         |   -13.35 | K1-FiDa, Levi, M1key, NIO, Pechyn |
|           70 |     2788 | 2024-04-18 | Johnny Speeds             | L   | 0.922      | -            | -                | -                | -         |    -9.72 | K1-FiDa, Levi, M1key, NIO, Pechyn |
|           69 |     2850 | 2024-04-17 | Lemondogs                 | W   | 0.916      | -            | -                | -                | -         |     4.69 | K1-FiDa, Levi, M1key, NIO, Pechyn |
|           68 |     2881 | 2024-04-17 | Viperio                   | W   | 0.914      | -            | -                | -                | -         |     8.74 | K1-FiDa, Levi, M1key, NIO, Pechyn |
|           67 |     2913 | 2024-04-16 | DMS                       | W   | 0.909      | 0.333        | -                | 0.751 (0.228)    | -         |    11.92 | K1-FiDa, Levi, M1key, NIO, Pechyn |
|           66 |     2929 | 2024-04-16 | Lilmix                    | W   | 0.908      | -            | -                | -                | -         |    12.44 | K1-FiDa, Levi, M1key, NIO, Pechyn |
|           65 |     2964 | 2024-04-15 | Verdant                   | W   | 0.902      | 0.333        | 0.014 (0.004)    | 1.000 (0.301)    | -         |    15.59 | K1-FiDa, Levi, M1key, NIO, Pechyn |
|           64 |     3048 | 2024-04-13 | ex-K10                    | W   | 0.889      | -            | -                | -                | -         |    12.17 | K1-FiDa, Levi, M1key, NIO, Pechyn |
|           63 |     3087 | 2024-04-12 | Johnny Speeds             | L   | 0.882      | -            | -                | -                | -         |    -8.23 | K1-FiDa, Levi, M1key, NIO, Pechyn |
|           62 |     3131 | 2024-04-11 | Rhyno Esports             | L   | 0.875      | -            | -                | -                | -         |   -10.15 | K1-FiDa, Levi, M1key, NIO, Pechyn |
|           61 |     3182 | 2024-04-10 | Dynamo Eclot              | L   | 0.870      | -            | -                | -                | -         |    -9.46 | K1-FiDa, Levi, M1key, NIO, Pechyn |
|           60 |     3209 | 2024-04-10 | SINNERS Esports           | L   | 0.868      | -            | -                | -                | -         |    -7.72 | K1-FiDa, Levi, M1key, NIO, Pechyn |
|           59 |     3272 | 2024-04-09 | WOPA Esport               | W   | 0.861      | -            | -                | -                | -         |    10.00 | K1-FiDa, Levi, M1key, NIO, Pechyn |
|           58 |     3424 | 2024-04-06 | Sashi Esport              | L   | 0.841      | -            | -                | -                | -         |    -6.49 | K1-FiDa, Levi, M1key, NIO, Pechyn |
|           57 |     3450 | 2024-04-05 | Astralis Talent           | L   | 0.836      | -            | -                | -                | -         |   -13.40 | K1-FiDa, Levi, M1key, NIO, Pechyn |
|           56 |     3517 | 2024-04-04 | Sashi Esport              | L   | 0.829      | -            | -                | -                | -         |    -7.16 | K1-FiDa, Levi, M1key, NIO, Pechyn |
|           55 |     3612 | 2024-04-02 | Illuminar Gaming          | W   | 0.815      | -            | -                | -                | -         |    10.57 | K1-FiDa, Levi, M1key, NIO, Pechyn |
|           54 |     3629 | 2024-04-01 | WOPA Esport               | W   | 0.809      | -            | -                | -                | -         |     8.79 | K1-FiDa, Levi, M1key, NIO, Pechyn |
|           53 |     3661 | 2024-03-31 | Dynamo Eclot              | W   | 0.801      | 0.333        | 0.097 (0.026)    | 0.936 (0.250)    | -         |    18.24 | K1-FiDa, Levi, M1key, NIO, Pechyn |
|           52 |     3712 | 2024-03-29 | Lilmix                    | W   | 0.789      | -            | -                | -                | -         |     8.75 | K1-FiDa, Levi, M1key, NIO, Pechyn |
|           51 |     3747 | 2024-03-28 | Entropiq                  | W   | 0.783      | -            | -                | -                | -         |     8.07 | K1-FiDa, Levi, M1key, NIO, Pechyn |
|           50 |     3834 | 2024-03-27 | Sashi Esport              | L   | 0.775      | -            | -                | -                | -         |   -13.86 | K1-FiDa, Levi, M1key, NIO, Pechyn |
|           49 |     3930 | 2024-03-25 | Permitta Esports          | W   | 0.762      | 0.333        | 0.029 (0.007)    | 1.000 (0.254)    | -         |    15.84 | K1-FiDa, Levi, M1key, NIO, Pechyn |
|           48 |     4045 | 2024-03-22 | Dynamo Eclot              | W   | 0.743      | 0.333        | 0.097 (0.024)    | 0.936 (0.232)    | -         |    18.20 | K1-FiDa, Levi, M1key, NIO, Pechyn |
|           47 |     4105 | 2024-03-21 | ex-Turów Zgorzelec Esport | L   | 0.735      | -            | -                | -                | -         |   -13.82 | K1-FiDa, Levi, M1key, NIO, Pechyn |
|           46 |     4144 | 2024-03-20 | FAVBET Team               | L   | 0.728      | -            | -                | -                | -         |   -10.29 | K1-FiDa, Levi, M1key, NIO, Pechyn |
|           45 |     4278 | 2024-03-17 | SINNERS Esports           | L   | 0.710      | -            | -                | -                | -         |    -7.13 | K1-FiDa, Levi, M1key, NIO, Pechyn |
|           44 |     4318 | 2024-03-16 | Dynamo Eclot              | L   | 0.704      | -            | -                | -                | -         |    -6.02 | K1-FiDa, Levi, M1key, NIO, Pechyn |
|           43 |     4337 | 2024-03-16 | Dynamo Eclot              | W   | 0.702      | 0.333        | 0.097 (0.023)    | 0.936 (0.219)    | -         |    16.52 | K1-FiDa, Levi, M1key, NIO, Pechyn |
|           42 |     4374 | 2024-03-15 | SINNERS Esports           | W   | 0.698      | -            | -                | -                | 1 (0.698) |    15.35 | K1-FiDa, Levi, M1key, NIO, Pechyn |
|           41 |     4823 | 2024-03-07 | EP Genesis                | W   | 0.643      | -            | -                | -                | -         |     3.64 | K1-FiDa, Levi, M1key, NIO, Pechyn |
|           40 |     4966 | 2024-03-05 | Team Sampi                | L   | 0.630      | -            | -                | -                | -         |    -7.37 | K1-FiDa, Levi, M1key, NIO, Pechyn |
|           39 |     5002 | 2024-03-04 | Permitta Esports          | L   | 0.625      | -            | -                | -                | -         |    -6.28 | K1-FiDa, Levi, M1key, NIO, Pechyn |
|           38 |     5044 | 2024-03-04 | EP Genesis                | W   | 0.623      | -            | -                | -                | -         |     3.15 | K1-FiDa, Levi, M1key, NIO, Pechyn |
|           37 |     5124 | 2024-03-02 | AURA                      | L   | 0.612      | -            | -                | -                | -         |   -13.71 | K1-FiDa, Levi, M1key, NIO, Pechyn |
|           36 |     5140 | 2024-03-02 | Team Space                | W   | 0.611      | -            | -                | -                | -         |     9.15 | K1-FiDa, Levi, M1key, NIO, Pechyn |
|           35 |     5274 | 2024-02-29 | Copenhagen Wolves         | L   | 0.597      | -            | -                | -                | -         |   -14.75 | Levi, luko, M1key, NIO, Pechyn    |
|           34 |     5279 | 2024-02-29 | Team Secret               | W   | 0.597      | -            | -                | -                | -         |     4.81 | Levi, luko, M1key, NIO, Pechyn    |
|           33 |     5318 | 2024-02-28 | 1win                      | L   | 0.591      | -            | -                | -                | -         |    -6.38 | Levi, luko, M1key, NIO, Pechyn    |
|           32 |     5326 | 2024-02-28 | DMS                       | L   | 0.590      | -            | -                | -                | -         |   -12.40 | Levi, luko, M1key, NIO, Pechyn    |
|           31 |     5381 | 2024-02-27 | FAVBET Team               | L   | 0.583      | -            | -                | -                | -         |   -10.81 | Levi, luko, M1key, NIO, Pechyn    |
|           30 |     5616 | 2024-02-23 | Eternal Fire Academy      | W   | 0.557      | -            | -                | -                | -         |     4.02 | Levi, luko, M1key, NIO, Pechyn    |
|           29 |     5715 | 2024-02-21 | Lausanne-Sport Esports    | L   | 0.544      | -            | -                | -                | -         |   -12.25 | Levi, luko, M1key, NIO, Pechyn    |
|           28 |     5766 | 2024-02-20 | Entropiq                  | L   | 0.537      | -            | -                | -                | -         |   -12.74 | Levi, luko, M1key, NIO, Pechyn    |
|           27 |     5837 | 2024-02-19 | GamerLegion Academy       | W   | 0.530      | 0.371        | 0.018 (0.004)    | -                | -         |     6.06 | Levi, luko, M1key, NIO, Pechyn    |
|           26 |     5946 | 2024-02-17 | Rhyno Esports             | W   | 0.517      | 0.371        | 0.029 (0.006)    | -                | -         |    10.19 | Levi, luko, M1key, NIO, Pechyn    |
|           25 |     6266 | 2024-02-10 | Viperio                   | L   | 0.470      | -            | -                | -                | -         |   -12.05 | desty, Levi, M1key, NIO, Pechyn   |
|           24 |     6379 | 2024-02-06 | Endpoint                  | L   | 0.444      | -            | -                | -                | -         |    -6.14 | Levi, luko, M1key, NIO, Pechyn    |
|           23 |     6498 | 2024-02-03 | kONO.ECF                  | L   | 0.424      | -            | -                | -                | -         |    -7.43 | Levi, luko, M1key, NIO, Pechyn    |
|           22 |     6518 | 2024-02-03 | ex-sYnck                  | W   | 0.424      | -            | -                | -                | -         |     3.59 | Levi, luko, M1key, NIO, Pechyn    |
|           21 |     6536 | 2024-02-03 | Team Pigeons              | W   | 0.424      | -            | -                | -                | -         |     4.46 | Levi, luko, M1key, NIO, Pechyn    |
|           20 |     6553 | 2024-02-03 | RUR Esports               | W   | 0.423      | -            | -                | -                | -         |     1.12 | Levi, luko, M1key, NIO, Pechyn    |
|           19 |     6621 | 2024-02-02 | Dynamo Eclot              | L   | 0.417      | -            | -                | -                | -         |    -3.63 | Levi, luko, M1key, NIO, Pechyn    |
|           18 |     6725 | 2024-01-31 | ARCRED                    | L   | 0.403      | -            | -                | -                | -         |    -8.63 | Levi, luko, M1key, NIO, Pechyn    |
|           17 |     7038 | 2024-01-26 | 9Pandas                   | L   | 0.370      | -            | -                | -                | -         |    -2.23 | Levi, luko, M1key, NIO, Pechyn    |
|           16 |     7523 | 2024-01-17 | Capcarap                  | L   | 0.312      | -            | -                | -                | -         |    -8.92 | Levi, luko, M1key, NIO, Pechyn    |
|           15 |     7539 | 2024-01-17 | Alliance                  | W   | 0.311      | -            | -                | -                | -         |     3.99 | Levi, luko, M1key, NIO, Pechyn    |
|           14 |     7791 | 2024-01-13 | Gaimin Gladiators         | L   | 0.283      | -            | -                | -                | -         |    -1.08 | Levi, luko, M1key, NIO, Pechyn    |
|           13 |     7837 | 2024-01-12 | BAKS Esports              | W   | 0.278      | -            | -                | -                | -         |     1.45 | Levi, luko, M1key, NIO, Pechyn    |
|           12 |     7849 | 2024-01-12 | MEHED                     | W   | 0.278      | -            | -                | -                | -         |     0.45 | Levi, luko, M1key, NIO, Pechyn    |
|           11 |     8097 | 2024-01-09 | Johnny Speeds             | L   | 0.257      | -            | -                | -                | -         |    -2.77 | Levi, luko, M1key, NIO, Pechyn    |
|           10 |     8111 | 2024-01-09 | TOOMUCHVIDEOGAMES         | W   | 0.257      | -            | -                | -                | -         |     0.70 | Levi, luko, M1key, NIO, Pechyn    |
|            9 |     8444 | 2023-12-17 | VP.Prodigy                | L   | 0.105      | -            | -                | -                | -         |    -2.03 | Levi, luko, M1key, NIO, Pechyn    |
|            8 |     8576 | 2023-12-16 | Rhyno Esports             | W   | 0.098      | -            | -                | -                | -         |     2.04 | Levi, luko, M1key, NIO, Pechyn    |
|            7 |     8733 | 2023-12-15 | VP.Prodigy                | L   | 0.091      | -            | -                | -                | -         |    -1.78 | Levi, luko, M1key, NIO, Pechyn    |
|            6 |     8824 | 2023-12-13 | gbcxz                     | W   | 0.078      | -            | -                | -                | -         |     0.34 | Levi, luko, M1key, NIO, Pechyn    |
|            5 |     8922 | 2023-12-11 | Passion UA                | W   | 0.064      | -            | -                | -                | -         |     1.28 | Levi, luko, M1key, NIO, Pechyn    |
|            4 |     8934 | 2023-12-11 | detoks                    | L   | 0.063      | -            | -                | -                | -         |    -1.80 | Levi, luko, M1key, NIO, Pechyn    |
|            3 |     9148 | 2023-12-07 | The Dice                  | W   | 0.038      | -            | -                | -                | -         |     0.06 | Levi, luko, M1key, NIO, Pechyn    |
|            2 |     9170 | 2023-12-07 | ex-Turów Zgorzelec Esport | L   | 0.037      | -            | -                | -                | -         |    -0.80 | Levi, luko, M1key, NIO, Pechyn    |
|            1 |     9273 | 2023-12-05 | BebraFPL1                 | W   | 0.025      | -            | -                | -                | -         |     0.07 | Levi, luko, M1key, NIO, Pechyn    |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($6,441.47)
- Divide that value by the 5th highest value among all rosters ($300,806.11)
- The final value (0.02) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-04-18 |      0.922 | $3,000.00      | $2,765.00       |
| 2024-04-06 |      0.841 | $3,000.00      | $2,523.33       |
| 2024-03-17 |      0.711 | $1,298.80      | $923.05         |
| 2023-12-17 |      0.105 | $2,200.00      | $230.08         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
