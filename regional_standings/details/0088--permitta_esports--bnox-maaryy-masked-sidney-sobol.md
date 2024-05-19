### Roster Details<br />
Team Name: Permitta Esports<br />
Roster: bnox, maaryy, mASKED, Sidney, Sobol<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [88](../standings_global.md)<br />
Regional Rank: [65]( ../standings_europe.md)<br />
Final Rank Value:  880.0<br />
<br />
Final Rank Value (880.0) = Starting Rank Value (1005.8) + Head To Head Adjustments (-125.7)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.454[<sup>1</sup>](#table2)
- Bounty Collected: 0.440[<sup>2</sup>](#table1)
- Opponent Network: 0.327[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.305<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1005.8
- 400 + ( ( 0.305 - 0.000 ) / ( 0.806 - 0.000 ) ) * 1600 = 1005.8


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
|          118 |      108 | 2024-05-03 | Insilio                     | L   | 1.000      | -            | -                | -                | -         |   -11.00 | bnox, maaryy, mASKED, Sidney, Sobol |
|          117 |      147 | 2024-05-02 | Team Sampi                  | L   | 1.000      | -            | -                | -                | -         |   -11.42 | bnox, maaryy, mASKED, Sidney, Sobol |
|          116 |      163 | 2024-05-02 | B8                          | L   | 1.000      | -            | -                | -                | -         |   -11.44 | bnox, maaryy, mASKED, morelz, Sobol |
|          115 |      238 | 2024-04-30 | BLESSED (Ukrainian team)    | W   | 1.000      | 0.371        | -                | 0.781 (0.290)    | 0 (0.000) |    17.27 | bnox, maaryy, mASKED, morelz, Vegi  |
|          114 |      257 | 2024-04-30 | BLEED Esports               | L   | 1.000      | -            | -                | -                | -         |    -5.24 | bnox, maaryy, mASKED, morelz, Vegi  |
|          113 |      283 | 2024-04-29 | AMKAL ESPORTS               | L   | 1.000      | -            | -                | -                | -         |    -5.00 | bnox, maaryy, mASKED, morelz, Vegi  |
|          112 |      372 | 2024-04-27 | Insilio                     | L   | 1.000      | -            | -                | -                | -         |   -13.94 | bnox, maaryy, mASKED, morelz, Vegi  |
|          111 |      390 | 2024-04-27 | ENTERPRISE esports          | W   | 1.000      | -            | -                | -                | 0 (0.000) |    14.43 | bnox, maaryy, mASKED, morelz, Vegi  |
|          110 |      445 | 2024-04-26 | ARCRED                      | L   | 1.000      | -            | -                | -                | -         |   -18.13 | bnox, maaryy, mASKED, morelz, Vegi  |
|          109 |      481 | 2024-04-25 | 1win                        | L   | 1.000      | -            | -                | -                | -         |   -20.72 | bnox, maaryy, mASKED, morelz, Vegi  |
|          108 |      528 | 2024-04-24 | BLEED Esports               | L   | 1.000      | -            | -                | -                | -         |    -7.11 | bnox, maaryy, mASKED, morelz, Vegi  |
|          107 |      542 | 2024-04-24 | Passion UA                  | W   | 1.000      | 0.384        | 0.114 (0.044)    | 0.980 (0.376)    | 0 (0.000) |    15.47 | bnox, maaryy, mASKED, morelz, Vegi  |
|          106 |      548 | 2024-04-24 | DMS                         | W   | 1.000      | -            | -                | -                | 0 (0.000) |    10.27 | bnox, maaryy, mASKED, morelz, Vegi  |
|          105 |      552 | 2024-04-24 | Team Sampi                  | L   | 1.000      | -            | -                | -                | -         |   -11.88 | bnox, maaryy, mASKED, morelz, Vegi  |
|          104 |      578 | 2024-04-23 | RoundsGG                    | W   | 1.000      | -            | -                | -                | 0 (0.000) |     5.92 | bnox, maaryy, mASKED, morelz, Vegi  |
|          103 |      585 | 2024-04-23 | RUBY                        | L   | 1.000      | -            | -                | -                | -         |   -13.86 | bnox, maaryy, mASKED, morelz, Vegi  |
|          102 |      594 | 2024-04-23 | ALTERNATE aTTaX             | W   | 1.000      | 0.371        | 0.110 (0.041)    | 0.723 (0.268)    | 0 (0.000) |    14.04 | bnox, maaryy, mASKED, morelz, Vegi  |
|          101 |      668 | 2024-04-21 | Insilio                     | W   | 1.000      | 0.435        | -                | 0.875 (0.380)    | 0 (0.000) |    15.83 | bnox, maaryy, mASKED, morelz, Vegi  |
|          100 |      711 | 2024-04-20 | ENTERPRISE esports          | L   | 1.000      | -            | -                | -                | -         |   -15.37 | bnox, maaryy, mASKED, morelz, Vegi  |
|           99 |      751 | 2024-04-20 | Nexus Gaming                | L   | 1.000      | -            | -                | -                | -         |   -16.54 | bnox, maaryy, mASKED, morelz, Vegi  |
|           98 |      778 | 2024-04-20 | Passion UA                  | W   | 1.000      | 0.371        | 0.114 (0.042)    | 0.980 (0.363)    | 0 (0.000) |    15.51 | bnox, maaryy, mASKED, morelz, Vegi  |
|           97 |      894 | 2024-04-18 | Passion UA                  | L   | 1.000      | -            | -                | -                | -         |   -15.21 | bnox, maaryy, mASKED, morelz, Vegi  |
|           96 |      909 | 2024-04-18 | Team Sampi                  | L   | 1.000      | -            | -                | -                | -         |   -12.55 | bnox, maaryy, mASKED, morelz, Vegi  |
|           95 |      947 | 2024-04-17 | PARIVISION                  | W   | 1.000      | -            | -                | -                | 0 (0.000) |    11.04 | bnox, maaryy, mASKED, morelz, Vegi  |
|           94 |     1019 | 2024-04-16 | Gaimin Gladiators           | L   | 1.000      | -            | -                | -                | -         |    -2.46 | bnox, maaryy, mASKED, morelz, Vegi  |
|           93 |     1137 | 2024-04-12 | 9INE Academy                | W   | 1.000      | -            | -                | -                | 0 (0.000) |     5.66 | bnox, maaryy, mASKED, morelz, Vegi  |
|           92 |     1152 | 2024-04-12 | MOUZ NXT                    | W   | 1.000      | 0.371        | 0.215 (0.080)    | 1.000 (0.371)    | -         |    20.93 | bnox, maaryy, mASKED, morelz, Vegi  |
|           91 |     1220 | 2024-04-10 | M1 Gaming                   | W   | 1.000      | -            | -                | -                | -         |     5.12 | bnox, maaryy, mASKED, morelz, Vegi  |
|           90 |     1251 | 2024-04-10 | EYEBALLERS                  | W   | 1.000      | -            | -                | -                | -         |    16.78 | bnox, maaryy, mASKED, morelz, Vegi  |
|           89 |     1277 | 2024-04-09 | AVEZ                        | W   | 1.000      | -            | -                | -                | -         |     6.42 | bnox, maaryy, mASKED, morelz, Vegi  |
|           88 |     1334 | 2024-04-08 | DEEZ NUTS                   | L   | 1.000      | -            | -                | -                | -         |   -24.23 | bnox, maaryy, mASKED, morelz, Vegi  |
|           87 |     1343 | 2024-04-08 | HAVU Gaming                 | W   | 1.000      | -            | -                | -                | -         |    11.08 | bnox, maaryy, mASKED, morelz, Vegi  |
|           86 |     1353 | 2024-04-08 | JANO Esports                | W   | 1.000      | -            | -                | -                | -         |     8.54 | bnox, maaryy, mASKED, morelz, Vegi  |
|           85 |     1536 | 2024-04-03 | ENTERPRISE esports          | L   | 0.985      | -            | -                | -                | -         |   -15.50 | bnox, maaryy, mASKED, morelz, Vegi  |
|           84 |     1552 | 2024-04-03 | Dynamo Eclot                | L   | 0.983      | -            | -                | -                | -         |   -10.48 | bnox, maaryy, mASKED, morelz, Vegi  |
|           83 |     1586 | 2024-04-02 | 3DMAX                       | L   | 0.977      | -            | -                | -                | -         |   -14.68 | bnox, maaryy, mASKED, morelz, Vegi  |
|           82 |     1595 | 2024-04-02 | Sashi Esport                | L   | 0.976      | -            | -                | -                | -         |   -10.61 | bnox, maaryy, mASKED, morelz, Vegi  |
|           81 |     1655 | 2024-03-30 | ROSOMAHA                    | W   | 0.956      | -            | -                | -                | -         |     3.57 | bnox, maaryy, mASKED, morelz, Vegi  |
|           80 |     1795 | 2024-03-26 | DMS                         | L   | 0.932      | -            | -                | -                | -         |   -23.35 | bnox, maaryy, mASKED, morelz, Vegi  |
|           79 |     1850 | 2024-03-25 | UNiTY esports (Slovak team) | L   | 0.923      | -            | -                | -                | -         |   -18.95 | bnox, maaryy, mASKED, morelz, Vegi  |
|           78 |     1866 | 2024-03-24 | Astralis Talent             | W   | 0.917      | -            | -                | -                | -         |    10.37 | bnox, maaryy, mASKED, morelz, Vegi  |
|           77 |     1868 | 2024-03-24 | GamerLegion Academy         | L   | 0.916      | -            | -                | -                | -         |   -20.11 | bnox, maaryy, mASKED, morelz, Vegi  |
|           76 |     1996 | 2024-03-21 | K10                         | W   | 0.897      | -            | -                | -                | -         |     7.83 | bnox, maaryy, mASKED, morelz, Vegi  |
|           75 |     2035 | 2024-03-20 | En av de lette              | W   | 0.889      | -            | -                | -                | -         |     5.82 | bnox, maaryy, mASKED, morelz, Vegi  |
|           74 |     2105 | 2024-03-18 | NOM Esports                 | W   | 0.877      | -            | -                | -                | -         |     0.98 | bnox, maaryy, mASKED, morelz, Vegi  |
|           73 |     2178 | 2024-03-16 | RUBY                        | L   | 0.864      | -            | -                | -                | -         |   -16.61 | bnox, maaryy, mASKED, morelz, Vegi  |
|           72 |     2222 | 2024-03-15 | The Chosen Few              | W   | 0.857      | -            | -                | -                | -         |     9.01 | bnox, maaryy, mASKED, morelz, Vegi  |
|           71 |     2233 | 2024-03-15 | Team Sampi                  | L   | 0.856      | -            | -                | -                | -         |   -13.29 | bnox, maaryy, mASKED, morelz, Vegi  |
|           70 |     2282 | 2024-03-14 | K10                         | L   | 0.850      | -            | -                | -                | -         |   -20.09 | bnox, maaryy, mASKED, morelz, Vegi  |
|           69 |     2305 | 2024-03-13 | MOUZ NXT                    | W   | 0.846      | 0.371        | 0.215 (0.068)    | 1.000 (0.314)    | -         |    15.13 | bnox, maaryy, mASKED, morelz, Vegi  |
|           68 |     2329 | 2024-03-13 | Dynamo Eclot                | W   | 0.844      | 0.384        | 0.189 (0.061)    | 0.953 (0.309)    | -         |    16.03 | bnox, maaryy, mASKED, morelz, Vegi  |
|           67 |     2347 | 2024-03-13 | Dynamo Eclot                | W   | 0.843      | 0.371        | 0.189 (0.059)    | 0.953 (0.298)    | -         |    17.17 | bnox, maaryy, mASKED, morelz, Vegi  |
|           66 |     2435 | 2024-03-11 | Grannys Knockers            | L   | 0.830      | -            | -                | -                | -         |   -17.33 | bnox, maaryy, mASKED, morelz, Vegi  |
|           65 |     2515 | 2024-03-09 | Sashi Esport                | L   | 0.817      | -            | -                | -                | -         |   -12.51 | bnox, maaryy, mASKED, morelz, Vegi  |
|           64 |     2573 | 2024-03-07 | VP.Prodigy                  | W   | 0.805      | -            | -                | -                | -         |     8.15 | bnox, maaryy, mASKED, morelz, Vegi  |
|           63 |     2635 | 2024-03-06 | Passion UA                  | W   | 0.797      | 0.384        | -                | 0.980 (0.300)    | -         |    10.55 | bnox, maaryy, mASKED, morelz, Vegi  |
|           62 |     2649 | 2024-03-06 | ENTERPRISE esports          | W   | 0.797      | -            | -                | -                | -         |    11.31 | bnox, maaryy, mASKED, morelz, Vegi  |
|           61 |     2706 | 2024-03-05 | Young Ninjas                | W   | 0.791      | -            | -                | -                | -         |    12.54 | bnox, maaryy, mASKED, morelz, Vegi  |
|           60 |     2714 | 2024-03-05 | Astralis Talent             | L   | 0.790      | -            | -                | -                | -         |   -13.90 | bnox, maaryy, mASKED, morelz, Vegi  |
|           59 |     2724 | 2024-03-04 | UGANDA (Finnish team)       | L   | 0.786      | -            | -                | -                | -         |   -23.03 | bnox, maaryy, mASKED, morelz, Vegi  |
|           58 |     2734 | 2024-03-04 | UNiTY esports (Slovak team) | W   | 0.786      | -            | -                | -                | -         |     7.19 | bnox, maaryy, mASKED, morelz, Vegi  |
|           57 |     2834 | 2024-03-02 | SINNERS Esports             | L   | 0.773      | -            | -                | -                | -         |   -12.55 | bnox, maaryy, mASKED, morelz, Vegi  |
|           56 |     2847 | 2024-03-02 | Astralis Talent             | W   | 0.772      | -            | -                | -                | -         |     9.83 | bnox, maaryy, mASKED, morelz, Vegi  |
|           55 |     2893 | 2024-03-02 | GODSENT                     | W   | 0.770      | -            | -                | -                | -         |     6.17 | bnox, maaryy, mASKED, morelz, Vegi  |
|           54 |     2947 | 2024-02-29 | Sashi Esport                | L   | 0.758      | -            | -                | -                | -         |   -10.38 | bnox, maaryy, mASKED, morelz, Vegi  |
|           53 |     2971 | 2024-02-29 | ENCE Academy                | W   | 0.756      | -            | -                | -                | -         |     7.81 | bnox, maaryy, mASKED, morelz, Vegi  |
|           52 |     2981 | 2024-02-28 | RUBY                        | W   | 0.752      | -            | -                | -                | -         |     9.97 | bnox, maaryy, mASKED, morelz, Vegi  |
|           51 |     3001 | 2024-02-28 | Team Secret                 | L   | 0.751      | -            | -                | -                | -         |   -19.97 | bnox, maaryy, mASKED, morelz, Vegi  |
|           50 |     3007 | 2024-02-28 | Dynamo Eclot                | L   | 0.749      | -            | -                | -                | -         |    -7.32 | bnox, maaryy, mASKED, morelz, Vegi  |
|           49 |     3045 | 2024-02-27 | Sprout                      | W   | 0.743      | -            | -                | -                | -         |     1.40 | bnox, maaryy, mASKED, morelz, Vegi  |
|           48 |     3080 | 2024-02-26 | Reason Gaming               | W   | 0.736      | -            | -                | -                | -         |     5.02 | bnox, maaryy, mASKED, morelz, Vegi  |
|           47 |     3100 | 2024-02-25 | Verdant                     | W   | 0.731      | -            | -                | -                | -         |     9.49 | bnox, maaryy, mASKED, morelz, Vegi  |
|           46 |     3174 | 2024-02-24 | Dynamo Eclot                | W   | 0.723      | 0.333        | 0.189 (0.046)    | -                | -         |    15.96 | bnox, maaryy, mASKED, morelz, Vegi  |
|           45 |     3250 | 2024-02-22 | ARCRED                      | L   | 0.712      | -            | -                | -                | -         |   -16.32 | bnox, maaryy, mASKED, morelz, Vegi  |
|           44 |     3257 | 2024-02-22 | The Chosen Few              | L   | 0.711      | -            | -                | -                | -         |   -17.26 | bnox, maaryy, mASKED, morelz, Vegi  |
|           43 |     3268 | 2024-02-22 | Turów Zgorzelec Esport      | W   | 0.709      | -            | -                | -                | -         |     5.76 | bnox, maaryy, mASKED, morelz, Vegi  |
|           42 |     3295 | 2024-02-21 | MOUZ NXT                    | W   | 0.705      | 0.371        | 0.215 (0.056)    | -                | -         |    14.29 | bnox, maaryy, mASKED, morelz, Vegi  |
|           41 |     3330 | 2024-02-21 | Dynamo Eclot                | L   | 0.703      | -            | -                | -                | -         |    -7.03 | bnox, maaryy, mASKED, morelz, Vegi  |
|           40 |     3357 | 2024-02-20 | GenOne                      | W   | 0.698      | -            | -                | -                | -         |     2.10 | bnox, maaryy, mASKED, morelz, Vegi  |
|           39 |     3374 | 2024-02-20 | Sangal Esports              | W   | 0.697      | -            | -                | -                | -         |     3.81 | bnox, maaryy, mASKED, morelz, Vegi  |
|           38 |     3425 | 2024-02-19 | Dynamo Eclot                | W   | 0.690      | 0.303        | 0.189 (0.040)    | -                | -         |    15.25 | bnox, maaryy, mASKED, morelz, Vegi  |
|           37 |     3504 | 2024-02-17 | Viperio                     | W   | 0.677      | -            | -                | -                | -         |     3.27 | bnox, maaryy, mASKED, morelz, Vegi  |
|           36 |     3548 | 2024-02-16 | Sashi Esport                | L   | 0.670      | -            | -                | -                | -         |    -8.07 | bnox, maaryy, mASKED, morelz, Vegi  |
|           35 |     3599 | 2024-02-15 | Sashi Esport                | W   | 0.664      | -            | -                | -                | -         |     5.79 | bnox, maaryy, mASKED, morelz, Vegi  |
|           34 |     3736 | 2024-02-12 | Sangal Esports              | W   | 0.643      | -            | -                | -                | -         |     3.64 | bnox, maaryy, mASKED, morelz, Vegi  |
|           33 |     3738 | 2024-02-12 | Lilmix                      | W   | 0.643      | -            | -                | -                | -         |     2.44 | bnox, maaryy, mASKED, morelz, Vegi  |
|           32 |     3848 | 2024-02-07 | Endpoint                    | L   | 0.610      | -            | -                | -                | -         |   -12.50 | bnox, maaryy, mASKED, morelz, Vegi  |
|           31 |     3932 | 2024-02-04 | Natus Vincere Junior        | L   | 0.590      | -            | -                | -                | -         |   -13.45 | bnox, maaryy, mASKED, morelz, Vegi  |
|           30 |     4105 | 2024-01-31 | Team Secret                 | W   | 0.565      | -            | -                | -                | -         |     2.19 | bnox, maaryy, mASKED, morelz, Vegi  |
|           29 |     4140 | 2024-01-30 | RUBY                        | L   | 0.559      | -            | -                | -                | -         |   -11.59 | bnox, maaryy, mASKED, morelz, Vegi  |
|           28 |     4144 | 2024-01-30 | 3DMAX                       | W   | 0.558      | -            | -                | -                | -         |     7.89 | bnox, maaryy, mASKED, morelz, Vegi  |
|           27 |     4160 | 2024-01-29 | GODSENT                     | W   | 0.553      | -            | -                | -                | -         |     4.15 | bnox, maaryy, mASKED, morelz, Vegi  |
|           26 |     4186 | 2024-01-29 | RAVAGERS                    | W   | 0.553      | -            | -                | -                | -         |     0.59 | bnox, maaryy, mASKED, morelz, Vegi  |
|           25 |     4317 | 2024-01-26 | Lausanne-Sport Esports      | W   | 0.531      | -            | -                | -                | -         |     3.38 | bnox, maaryy, mASKED, morelz, Vegi  |
|           24 |     4383 | 2024-01-24 | Lajtbitexe                  | W   | 0.518      | -            | -                | -                | -         |     1.33 | bnox, maaryy, mASKED, morelz, Vegi  |
|           23 |     4562 | 2024-01-20 | Gaimin Gladiators           | L   | 0.490      | -            | -                | -                | -         |    -1.42 | bnox, maaryy, mASKED, morelz, Vegi  |
|           22 |     4569 | 2024-01-20 | Astralis Talent             | L   | 0.489      | -            | -                | -                | -         |    -8.20 | bnox, maaryy, mASKED, morelz, Vegi  |
|           21 |     4598 | 2024-01-19 | JANO Esports                | W   | 0.486      | -            | -                | -                | -         |     3.59 | bnox, maaryy, mASKED, morelz, Vegi  |
|           20 |     4618 | 2024-01-19 | Aurora Young Blud           | W   | 0.483      | -            | -                | -                | -         |     4.53 | bnox, maaryy, mASKED, morelz, Vegi  |
|           19 |     4647 | 2024-01-18 | Zero Tenacity               | L   | 0.479      | -            | -                | -                | -         |    -8.89 | bnox, maaryy, mASKED, morelz, Vegi  |
|           18 |     4666 | 2024-01-18 | BIG                         | L   | 0.478      | -            | -                | -                | -         |    -1.13 | bnox, maaryy, mASKED, morelz, Vegi  |
|           17 |     4674 | 2024-01-18 | Team Spirit Academy         | W   | 0.477      | -            | -                | -                | -         |     3.98 | bnox, maaryy, mASKED, morelz, Vegi  |
|           16 |     4751 | 2024-01-17 | Astralis Talent             | L   | 0.470      | -            | -                | -                | -         |    -8.06 | bnox, maaryy, mASKED, morelz, Vegi  |
|           15 |     4869 | 2024-01-14 | Dynamo Eclot                | W   | 0.450      | -            | -                | -                | -         |    10.11 | bnox, maaryy, mASKED, morelz, Vegi  |
|           14 |     4884 | 2024-01-13 | OG                          | L   | 0.445      | -            | -                | -                | -         |    -1.90 | bnox, maaryy, mASKED, morelz, Vegi  |
|           13 |     4887 | 2024-01-13 | Insilio                     | W   | 0.445      | -            | -                | -                | -         |     5.79 | bnox, maaryy, mASKED, morelz, Vegi  |
|           12 |     4889 | 2024-01-13 | Infinite Gaming             | W   | 0.444      | -            | -                | -                | -         |     0.49 | bnox, maaryy, mASKED, morelz, Vegi  |
|           11 |     4919 | 2024-01-12 | Clownfiesta                 | W   | 0.440      | -            | -                | -                | -         |     0.52 | bnox, maaryy, mASKED, morelz, Vegi  |
|           10 |     4938 | 2024-01-12 | Lilmix                      | W   | 0.439      | -            | -                | -                | -         |     2.36 | bnox, maaryy, mASKED, morelz, Vegi  |
|            9 |     4949 | 2024-01-12 | Lilmix                      | W   | 0.437      | -            | -                | -                | -         |     2.40 | bnox, maaryy, mASKED, morelz, Vegi  |
|            8 |     4953 | 2024-01-12 | MOUZ NXT                    | L   | 0.436      | -            | -                | -                | -         |    -5.08 | bnox, maaryy, mASKED, morelz, Vegi  |
|            7 |     5006 | 2024-01-11 | Pera Esports                | L   | 0.431      | -            | -                | -                | -         |    -8.00 | bnox, maaryy, mASKED, morelz, Vegi  |
|            6 |     5012 | 2024-01-11 | Verdant                     | W   | 0.429      | -            | -                | -                | -         |     0.45 | bnox, maaryy, mASKED, morelz, Vegi  |
|            5 |     5035 | 2024-01-10 | ILLYRIANS                   | W   | 0.426      | -            | -                | -                | -         |     0.47 | bnox, maaryy, mASKED, morelz, Vegi  |
|            4 |     5052 | 2024-01-10 | K10                         | W   | 0.426      | -            | -                | -                | -         |     4.91 | bnox, maaryy, mASKED, morelz, Vegi  |
|            3 |     5127 | 2024-01-09 | Astralis Talent             | W   | 0.417      | -            | -                | -                | -         |     6.10 | bnox, maaryy, mASKED, morelz, Vegi  |
|            2 |     5167 | 2024-01-07 | Lilmix                      | L   | 0.403      | -            | -                | -                | -         |   -10.71 | bnox, maaryy, mASKED, morelz, Vegi  |
|            1 |     5187 | 2024-01-05 | Passion UA                  | L   | 0.390      | -            | -                | -                | -         |    -6.60 | bnox, maaryy, mASKED, morelz, Vegi  |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($9,934.54)
- Divide that value by the 5th highest value among all rosters ($158,437.64)
- The final value (0.06) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-05-02 |      1.000 | $500.00        | $500.00         |
| 2024-04-25 |      1.000 | $3,000.00      | $3,000.00       |
| 2024-04-21 |      1.000 | $1,232.30      | $1,232.30       |
| 2024-03-25 |      0.925 | $1,250.00      | $1,155.84       |
| 2024-02-28 |      0.749 | $3,000.00      | $2,248.19       |
| 2024-02-21 |      0.703 | $1,500.00      | $1,054.10       |
| 2024-01-21 |      0.496 | $1,500.00      | $744.10         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
