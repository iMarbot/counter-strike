### Roster Details<br />
Team Name: UNiTY esports<br />
Roster: K1-FiDa, Levi, M1key, NIO, Pechyn<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [110](../standings_global.md)<br />
Regional Rank: [79]( ../standings_europe.md)<br />
Final Rank Value:  856.5<br />
<br />
Final Rank Value (856.5) = Starting Rank Value (925.9) + Head To Head Adjustments (-69.4)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.375[<sup>1</sup>](#table2)
- Bounty Collected: 0.352[<sup>2</sup>](#table1)
- Opponent Network: 0.235[<sup>2</sup>](#table1)
- LAN Wins: 0.074[<sup>2</sup>](#table1)

The average of these factors is 0.259<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 925.9
- 400 + ( ( 0.259 - 0.000 ) / ( 0.787 - 0.000 ) ) * 1600 = 925.9


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
|          101 |       96 | 2024-05-29 | Rebels Gaming             | W   | 1.000      | 0.371        | 0.062 (0.023)    | -                | 0 (0.000) |    24.10 | K1-FiDa, Levi, M1key, NIO, Pechyn |
|          100 |      121 | 2024-05-28 | GamerLegion Academy       | L   | 1.000      | -            | -                | -                | -         |   -17.85 | K1-FiDa, Levi, M1key, NIO, Pechyn |
|           99 |      133 | 2024-05-28 | Necrotic Esports          | W   | 1.000      | -            | -                | -                | 0 (0.000) |     5.12 | K1-FiDa, Levi, M1key, NIO, Pechyn |
|           98 |      193 | 2024-05-27 | 9INE                      | W   | 1.000      | -            | -                | -                | 0 (0.000) |     4.10 | K1-FiDa, Levi, M1key, NIO, Pechyn |
|           97 |      218 | 2024-05-26 | ghoulsW                   | L   | 1.000      | -            | -                | -                | -         |   -26.57 | K1-FiDa, Levi, M1key, NIO, Pechyn |
|           96 |      264 | 2024-05-25 | MASONIC                   | W   | 1.000      | -            | -                | -                | 0 (0.000) |    12.07 | K1-FiDa, Levi, M1key, NIO, Pechyn |
|           95 |      303 | 2024-05-25 | iNation                   | L   | 1.000      | -            | -                | -                | -         |   -20.66 | K1-FiDa, Levi, M1key, NIO, Pechyn |
|           94 |      411 | 2024-05-23 | SINNERS Esports           | L   | 1.000      | -            | -                | -                | -         |   -11.74 | K1-FiDa, Levi, M1key, NIO, Pechyn |
|           93 |      487 | 2024-05-22 | Grannys Knockers          | W   | 1.000      | -            | -                | -                | 0 (0.000) |    13.28 | K1-FiDa, Levi, M1key, NIO, Pechyn |
|           92 |      589 | 2024-05-21 | ThunderFlash              | W   | 1.000      | -            | -                | -                | 0 (0.000) |    17.14 | K1-FiDa, Levi, M1key, Mix, Pechyn |
|           91 |      637 | 2024-05-21 | Rebels Gaming             | W   | 1.000      | 0.371        | 0.062 (0.023)    | -                | 0 (0.000) |    24.59 | K1-FiDa, Levi, M1key, NIO, Pechyn |
|           90 |      778 | 2024-05-19 | MANGANES                  | L   | 1.000      | -            | -                | -                | -         |   -26.25 | K1-FiDa, Levi, M1key, NIO, Pechyn |
|           89 |      788 | 2024-05-19 | ghoulsW                   | L   | 1.000      | -            | -                | -                | -         |   -27.25 | K1-FiDa, Levi, M1key, NIO, Pechyn |
|           88 |      801 | 2024-05-19 | Infinite Gaming           | W   | 1.000      | -            | -                | -                | 0 (0.000) |     3.31 | K1-FiDa, Levi, M1key, NIO, Pechyn |
|           87 |     1009 | 2024-05-17 | BRUTE                     | W   | 1.000      | -            | -                | -                | 0 (0.000) |     4.27 | K1-FiDa, Levi, M1key, NIO, Pechyn |
|           86 |     1094 | 2024-05-16 | Team Flow                 | W   | 1.000      | -            | -                | -                | -         |     4.45 | K1-FiDa, Levi, M1key, NIO, Pechyn |
|           85 |     1340 | 2024-05-13 | Johnny Speeds             | L   | 1.000      | -            | -                | -                | -         |    -9.02 | K1-FiDa, Levi, M1key, NIO, Pechyn |
|           84 |     1489 | 2024-05-11 | GamerLegion Academy       | W   | 1.000      | 0.333        | 0.018 (0.006)    | 0.691 (0.230)    | -         |    13.22 | K1-FiDa, Levi, M1key, NIO, Pechyn |
|           83 |     1547 | 2024-05-10 | Zero Tenacity             | L   | 1.000      | -            | -                | -                | -         |    -8.63 | K1-FiDa, Levi, M1key, NIO, Pechyn |
|           82 |     1600 | 2024-05-09 | FAVBET Team               | L   | 1.000      | -            | -                | -                | -         |   -13.42 | K1-FiDa, Levi, M1key, NIO, Pechyn |
|           81 |     1674 | 2024-05-08 | ex-Turów Zgorzelec Esport | W   | 1.000      | -            | -                | -                | -         |    10.40 | K1-FiDa, Levi, M1key, NIO, Pechyn |
|           80 |     1706 | 2024-05-07 | Preasy Esport             | W   | 1.000      | 0.333        | -                | 0.705 (0.235)    | -         |    11.58 | K1-FiDa, Levi, M1key, NIO, Pechyn |
|           79 |     1813 | 2024-05-05 | Verdant                   | L   | 1.000      | -            | -                | -                | -         |   -16.10 | K1-FiDa, Levi, M1key, NIO, Pechyn |
|           78 |     1870 | 2024-05-04 | WOPA Esport               | W   | 1.000      | 0.333        | -                | 0.594 (0.198)    | -         |    10.77 | K1-FiDa, Levi, M1key, NIO, Pechyn |
|           77 |     1918 | 2024-05-03 | NOM Esports               | L   | 1.000      | -            | -                | -                | -         |   -23.02 | K1-FiDa, Levi, M1key, NIO, Pechyn |
|           76 |     2121 | 2024-04-29 | ex-Turów Zgorzelec Esport | W   | 0.994      | -            | -                | -                | -         |     9.91 | K1-FiDa, Levi, M1key, NIO, Pechyn |
|           75 |     2162 | 2024-04-28 | WOPA Esport               | W   | 0.989      | 0.333        | -                | 0.594 (0.196)    | -         |    10.85 | K1-FiDa, Levi, M1key, NIO, Pechyn |
|           74 |     2777 | 2024-04-19 | Rhyno Esports             | L   | 0.929      | -            | -                | -                | -         |   -12.23 | K1-FiDa, Levi, M1key, NIO, Pechyn |
|           73 |     2844 | 2024-04-18 | Johnny Speeds             | L   | 0.922      | -            | -                | -                | -         |    -9.22 | K1-FiDa, Levi, M1key, NIO, Pechyn |
|           72 |     2865 | 2024-04-17 | KOI                       | L   | 0.918      | -            | -                | -                | -         |    -8.80 | K1-FiDa, Levi, M1key, NIO, Pechyn |
|           71 |     2907 | 2024-04-17 | Lemondogs                 | W   | 0.916      | -            | -                | -                | -         |     4.65 | K1-FiDa, Levi, M1key, NIO, Pechyn |
|           70 |     2939 | 2024-04-17 | Viperio                   | W   | 0.914      | -            | -                | -                | -         |     8.99 | K1-FiDa, Levi, M1key, NIO, Pechyn |
|           69 |     2974 | 2024-04-16 | DMS                       | W   | 0.909      | 0.333        | -                | 0.754 (0.228)    | -         |    12.49 | K1-FiDa, Levi, M1key, NIO, Pechyn |
|           68 |     2990 | 2024-04-16 | Lilmix                    | W   | 0.908      | -            | -                | -                | -         |    12.36 | K1-FiDa, Levi, M1key, NIO, Pechyn |
|           67 |     3029 | 2024-04-15 | Verdant                   | W   | 0.902      | 0.333        | 0.014 (0.004)    | 1.000 (0.301)    | -         |    16.34 | K1-FiDa, Levi, M1key, NIO, Pechyn |
|           66 |     3060 | 2024-04-14 | Sashi Esport              | L   | 0.894      | -            | -                | -                | -         |    -6.65 | K1-FiDa, Levi, M1key, NIO, Pechyn |
|           65 |     3114 | 2024-04-13 | ex-K10                    | W   | 0.889      | -            | -                | -                | -         |    12.46 | K1-FiDa, Levi, M1key, NIO, Pechyn |
|           64 |     3153 | 2024-04-12 | Johnny Speeds             | L   | 0.882      | -            | -                | -                | -         |    -8.23 | K1-FiDa, Levi, M1key, NIO, Pechyn |
|           63 |     3201 | 2024-04-11 | Rhyno Esports             | L   | 0.875      | -            | -                | -                | -         |    -9.94 | K1-FiDa, Levi, M1key, NIO, Pechyn |
|           62 |     3256 | 2024-04-10 | Dynamo Eclot              | L   | 0.870      | -            | -                | -                | -         |    -9.51 | K1-FiDa, Levi, M1key, NIO, Pechyn |
|           61 |     3287 | 2024-04-10 | SINNERS Esports           | L   | 0.868      | -            | -                | -                | -         |    -6.68 | K1-FiDa, Levi, M1key, NIO, Pechyn |
|           60 |     3352 | 2024-04-09 | WOPA Esport               | W   | 0.861      | -            | -                | -                | -         |    10.09 | K1-FiDa, Levi, M1key, NIO, Pechyn |
|           59 |     3508 | 2024-04-06 | Sashi Esport              | L   | 0.841      | -            | -                | -                | -         |    -6.71 | K1-FiDa, Levi, M1key, NIO, Pechyn |
|           58 |     3534 | 2024-04-05 | Astralis Talent           | L   | 0.836      | -            | -                | -                | -         |   -13.26 | K1-FiDa, Levi, M1key, NIO, Pechyn |
|           57 |     3603 | 2024-04-04 | Sashi Esport              | L   | 0.829      | -            | -                | -                | -         |    -7.40 | K1-FiDa, Levi, M1key, NIO, Pechyn |
|           56 |     3702 | 2024-04-02 | Illuminar Gaming          | W   | 0.815      | -            | -                | -                | -         |    10.62 | K1-FiDa, Levi, M1key, NIO, Pechyn |
|           55 |     3721 | 2024-04-01 | WOPA Esport               | W   | 0.809      | -            | -                | -                | -         |     8.87 | K1-FiDa, Levi, M1key, NIO, Pechyn |
|           54 |     3754 | 2024-03-31 | Dynamo Eclot              | W   | 0.801      | 0.333        | 0.097 (0.026)    | 0.940 (0.251)    | -         |    18.17 | K1-FiDa, Levi, M1key, NIO, Pechyn |
|           53 |     3806 | 2024-03-29 | Lilmix                    | W   | 0.789      | -            | -                | -                | -         |     8.37 | K1-FiDa, Levi, M1key, NIO, Pechyn |
|           52 |     3840 | 2024-03-28 | Entropiq                  | W   | 0.783      | -            | -                | -                | -         |     8.13 | K1-FiDa, Levi, M1key, NIO, Pechyn |
|           51 |     3931 | 2024-03-27 | Sashi Esport              | L   | 0.775      | -            | -                | -                | -         |   -13.72 | K1-FiDa, Levi, M1key, NIO, Pechyn |
|           50 |     4026 | 2024-03-25 | Permitta Esports          | W   | 0.762      | 0.333        | 0.025 (0.006)    | 1.000 (0.254)    | -         |    16.23 | K1-FiDa, Levi, M1key, NIO, Pechyn |
|           49 |     4143 | 2024-03-22 | Dynamo Eclot              | W   | 0.743      | 0.333        | 0.097 (0.024)    | 0.940 (0.233)    | -         |    18.14 | K1-FiDa, Levi, M1key, NIO, Pechyn |
|           48 |     4205 | 2024-03-21 | ex-Turów Zgorzelec Esport | L   | 0.735      | -            | -                | -                | -         |   -13.56 | K1-FiDa, Levi, M1key, NIO, Pechyn |
|           47 |     4246 | 2024-03-20 | FAVBET Team               | L   | 0.728      | -            | -                | -                | -         |    -9.75 | K1-FiDa, Levi, M1key, NIO, Pechyn |
|           46 |     4383 | 2024-03-17 | SINNERS Esports           | L   | 0.710      | -            | -                | -                | -         |    -6.60 | K1-FiDa, Levi, M1key, NIO, Pechyn |
|           45 |     4424 | 2024-03-16 | Dynamo Eclot              | L   | 0.704      | -            | -                | -                | -         |    -6.08 | K1-FiDa, Levi, M1key, NIO, Pechyn |
|           44 |     4444 | 2024-03-16 | Dynamo Eclot              | W   | 0.702      | 0.333        | 0.097 (0.023)    | 0.940 (0.220)    | -         |    16.46 | K1-FiDa, Levi, M1key, NIO, Pechyn |
|           43 |     4482 | 2024-03-15 | SINNERS Esports           | W   | 0.698      | -            | -                | -                | 1 (0.698) |    15.89 | K1-FiDa, Levi, M1key, NIO, Pechyn |
|           42 |     4952 | 2024-03-07 | EP Genesis                | W   | 0.643      | -            | -                | -                | -         |     3.69 | K1-FiDa, Levi, M1key, NIO, Pechyn |
|           41 |     5109 | 2024-03-05 | Team Sampi                | L   | 0.630      | -            | -                | -                | -         |    -7.25 | K1-FiDa, Levi, M1key, NIO, Pechyn |
|           40 |     5148 | 2024-03-04 | Permitta Esports          | L   | 0.625      | -            | -                | -                | -         |    -6.02 | K1-FiDa, Levi, M1key, NIO, Pechyn |
|           39 |     5190 | 2024-03-04 | EP Genesis                | W   | 0.623      | -            | -                | -                | -         |     3.19 | K1-FiDa, Levi, M1key, NIO, Pechyn |
|           38 |     5272 | 2024-03-02 | AURA                      | L   | 0.612      | -            | -                | -                | -         |   -13.52 | K1-FiDa, Levi, M1key, NIO, Pechyn |
|           37 |     5288 | 2024-03-02 | Team Space                | W   | 0.611      | -            | -                | -                | -         |     9.25 | K1-FiDa, Levi, M1key, NIO, Pechyn |
|           36 |     5424 | 2024-02-29 | Copenhagen Wolves         | L   | 0.597      | -            | -                | -                | -         |   -14.30 | Levi, luko, M1key, NIO, Pechyn    |
|           35 |     5429 | 2024-02-29 | Team Secret               | W   | 0.597      | -            | -                | -                | -         |     4.93 | Levi, luko, M1key, NIO, Pechyn    |
|           34 |     5469 | 2024-02-28 | 1win                      | L   | 0.591      | -            | -                | -                | -         |    -6.59 | Levi, luko, M1key, NIO, Pechyn    |
|           33 |     5477 | 2024-02-28 | DMS                       | L   | 0.590      | -            | -                | -                | -         |   -12.05 | Levi, luko, M1key, NIO, Pechyn    |
|           32 |     5535 | 2024-02-27 | FAVBET Team               | L   | 0.583      | -            | -                | -                | -         |   -10.36 | Levi, luko, M1key, NIO, Pechyn    |
|           31 |     5776 | 2024-02-23 | Eternal Fire Academy      | W   | 0.557      | -            | -                | -                | -         |     4.01 | Levi, luko, M1key, NIO, Pechyn    |
|           30 |     5878 | 2024-02-21 | Lausanne-Sport Esports    | L   | 0.544      | -            | -                | -                | -         |   -11.68 | Levi, luko, M1key, NIO, Pechyn    |
|           29 |     5934 | 2024-02-20 | Entropiq                  | L   | 0.537      | -            | -                | -                | -         |   -12.63 | Levi, luko, M1key, NIO, Pechyn    |
|           28 |     6009 | 2024-02-19 | GamerLegion Academy       | W   | 0.530      | 0.371        | 0.018 (0.004)    | -                | -         |     6.18 | Levi, luko, M1key, NIO, Pechyn    |
|           27 |     6119 | 2024-02-17 | Rhyno Esports             | W   | 0.517      | 0.371        | 0.029 (0.006)    | -                | -         |    10.37 | Levi, luko, M1key, NIO, Pechyn    |
|           26 |     6454 | 2024-02-10 | Viperio                   | L   | 0.470      | -            | -                | -                | -         |   -11.81 | desty, Levi, M1key, NIO, Pechyn   |
|           25 |     6544 | 2024-02-07 | kONO.ECF                  | L   | 0.451      | -            | -                | -                | -         |    -6.91 | Levi, luko, M1key, NIO, Pechyn    |
|           24 |     6575 | 2024-02-06 | Endpoint                  | L   | 0.444      | -            | -                | -                | -         |    -6.07 | Levi, luko, M1key, NIO, Pechyn    |
|           23 |     6701 | 2024-02-03 | kONO.ECF                  | L   | 0.424      | -            | -                | -                | -         |    -6.87 | Levi, luko, M1key, NIO, Pechyn    |
|           22 |     6721 | 2024-02-03 | ex-sYnck                  | W   | 0.424      | -            | -                | -                | -         |     4.13 | Levi, luko, M1key, NIO, Pechyn    |
|           21 |     6739 | 2024-02-03 | Team Pigeons              | W   | 0.424      | -            | -                | -                | -         |     4.17 | Levi, luko, M1key, NIO, Pechyn    |
|           20 |     6756 | 2024-02-03 | RUR Esports               | W   | 0.423      | -            | -                | -                | -         |     1.12 | Levi, luko, M1key, NIO, Pechyn    |
|           19 |     6826 | 2024-02-02 | Dynamo Eclot              | L   | 0.417      | -            | -                | -                | -         |    -3.59 | Levi, luko, M1key, NIO, Pechyn    |
|           18 |     6937 | 2024-01-31 | ARCRED                    | L   | 0.403      | -            | -                | -                | -         |    -8.62 | Levi, luko, M1key, NIO, Pechyn    |
|           17 |     7262 | 2024-01-26 | 9Pandas                   | L   | 0.370      | -            | -                | -                | -         |    -2.12 | Levi, luko, M1key, NIO, Pechyn    |
|           16 |     7772 | 2024-01-17 | Capcarap                  | L   | 0.312      | -            | -                | -                | -         |    -8.92 | Levi, luko, M1key, NIO, Pechyn    |
|           15 |     7788 | 2024-01-17 | Alliance                  | W   | 0.311      | -            | -                | -                | -         |     4.01 | Levi, luko, M1key, NIO, Pechyn    |
|           14 |     8044 | 2024-01-13 | Gaimin Gladiators         | L   | 0.283      | -            | -                | -                | -         |    -1.07 | Levi, luko, M1key, NIO, Pechyn    |
|           13 |     8090 | 2024-01-12 | BAKS Esports              | W   | 0.278      | -            | -                | -                | -         |     1.45 | Levi, luko, M1key, NIO, Pechyn    |
|           12 |     8102 | 2024-01-12 | MEHED                     | W   | 0.278      | -            | -                | -                | -         |     0.45 | Levi, luko, M1key, NIO, Pechyn    |
|           11 |     8351 | 2024-01-09 | Johnny Speeds             | L   | 0.257      | -            | -                | -                | -         |    -2.75 | Levi, luko, M1key, NIO, Pechyn    |
|           10 |     8365 | 2024-01-09 | TOOMUCHVIDEOGAMES         | W   | 0.257      | -            | -                | -                | -         |     0.70 | Levi, luko, M1key, NIO, Pechyn    |
|            9 |     8702 | 2023-12-17 | VP.Prodigy                | L   | 0.105      | -            | -                | -                | -         |    -1.99 | Levi, luko, M1key, NIO, Pechyn    |
|            8 |     8836 | 2023-12-16 | Rhyno Esports             | W   | 0.098      | -            | -                | -                | -         |     2.04 | Levi, luko, M1key, NIO, Pechyn    |
|            7 |     8994 | 2023-12-15 | VP.Prodigy                | L   | 0.091      | -            | -                | -                | -         |    -1.75 | Levi, luko, M1key, NIO, Pechyn    |
|            6 |     9088 | 2023-12-13 | gbcxz                     | W   | 0.078      | -            | -                | -                | -         |     0.33 | Levi, luko, M1key, NIO, Pechyn    |
|            5 |     9188 | 2023-12-11 | Passion UA                | W   | 0.064      | -            | -                | -                | -         |     1.30 | Levi, luko, M1key, NIO, Pechyn    |
|            4 |     9200 | 2023-12-11 | detoks                    | L   | 0.063      | -            | -                | -                | -         |    -1.80 | Levi, luko, M1key, NIO, Pechyn    |
|            3 |     9421 | 2023-12-07 | The Dice                  | W   | 0.038      | -            | -                | -                | -         |     0.06 | Levi, luko, M1key, NIO, Pechyn    |
|            2 |     9443 | 2023-12-07 | ex-Turów Zgorzelec Esport | L   | 0.037      | -            | -                | -                | -         |    -0.77 | Levi, luko, M1key, NIO, Pechyn    |
|            1 |     9555 | 2023-12-05 | BebraFPL1                 | W   | 0.025      | -            | -                | -                | -         |     0.07 | Levi, luko, M1key, NIO, Pechyn    |

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
