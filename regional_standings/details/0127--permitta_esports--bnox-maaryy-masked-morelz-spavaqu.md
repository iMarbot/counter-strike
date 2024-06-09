### Roster Details<br />
Team Name: Permitta Esports<br />
Roster: bnox, maaryy, mASKED, morelz, SpavaQu<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [127](../standings_global.md)<br />
Regional Rank: [87]( ../standings_europe.md)<br />
Final Rank Value:  819.1<br />
<br />
Final Rank Value (819.1) = Starting Rank Value (966.1) + Head To Head Adjustments (-147.0)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.385[<sup>1</sup>](#table2)
- Bounty Collected: 0.406[<sup>2</sup>](#table1)
- Opponent Network: 0.323[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.279<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 966.1
- 400 + ( ( 0.279 - 0.000 ) / ( 0.787 - 0.000 ) ) * 1600 = 966.1


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent                  | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|          161 |      143 | 2024-05-28 | Preasy Esport             | W   | 1.000      | 0.371        | -                | 0.705 (0.261)    | 0 (0.000) |    11.95 | bnox, maaryy, mASKED, morelz, SpavaQu |
|          160 |      145 | 2024-05-28 | GUN5 Esports              | W   | 1.000      | -            | -                | -                | 0 (0.000) |    16.27 | bnox, maaryy, mASKED, morelz, Vegi    |
|          159 |      189 | 2024-05-27 | VP.Prodigy                | L   | 1.000      | -            | -                | -                | -         |   -10.70 | bnox, maaryy, mASKED, morelz, Vegi    |
|          158 |      197 | 2024-05-27 | Copenhagen Wolves         | L   | 1.000      | -            | -                | -                | -         |   -20.47 | bnox, maaryy, mASKED, morelz, Vegi    |
|          157 |      244 | 2024-05-26 | Dynamo Eclot              | W   | 1.000      | 0.371        | 0.097 (0.036)    | 0.940 (0.348)    | 0 (0.000) |    19.13 | bnox, maaryy, mASKED, morelz, SpavaQu |
|          156 |      270 | 2024-05-25 | Rustec                    | L   | 1.000      | -            | -                | -                | -         |   -15.23 | bnox, maaryy, mASKED, morelz, Vegi    |
|          155 |      309 | 2024-05-25 | The Agency Clan           | L   | 1.000      | -            | -                | -                | -         |   -27.06 | bnox, maaryy, mASKED, morelz, Vegi    |
|          154 |      371 | 2024-05-24 | LEON Esports              | W   | 1.000      | -            | -                | -                | 0 (0.000) |    11.43 | bnox, maaryy, mASKED, morelz, Vegi    |
|          153 |      394 | 2024-05-23 | Zero Tenacity             | W   | 1.000      | 0.372        | 0.147 (0.055)    | 1.000 (0.372)    | 0 (0.000) |    25.02 | bnox, maaryy, mASKED, morelz, Vegi    |
|          152 |      418 | 2024-05-23 | Endpoint                  | L   | 1.000      | -            | -                | -                | -         |   -13.31 | bnox, maaryy, mASKED, morelz, Vegi    |
|          151 |      497 | 2024-05-22 | Endpoint                  | W   | 1.000      | 0.435        | -                | 0.770 (0.335)    | 0 (0.000) |    17.50 | bnox, maaryy, mASKED, morelz, tomiko  |
|          150 |      509 | 2024-05-22 | Natus Vincere Junior      | L   | 1.000      | -            | -                | -                | -         |   -16.43 | bnox, maaryy, mASKED, morelz, Vegi    |
|          149 |      517 | 2024-05-22 | CYBERSHOKE Esports        | L   | 1.000      | -            | -                | -                | -         |   -19.29 | bnox, maaryy, mASKED, morelz, Vegi    |
|          148 |      533 | 2024-05-22 | Johnny Speeds             | L   | 1.000      | -            | -                | -                | -         |    -8.23 | bnox, maaryy, mASKED, morelz, SpavaQu |
|          147 |      581 | 2024-05-21 | Infinite Gaming           | W   | 1.000      | -            | -                | -                | 0 (0.000) |     3.93 | bnox, maaryy, mASKED, morelz, Vegi    |
|          146 |      717 | 2024-05-20 | ENCE Academy              | W   | 1.000      | -            | -                | -                | 0 (0.000) |    11.49 | bnox, maaryy, mASKED, morelz, Vegi    |
|          145 |      731 | 2024-05-20 | Passion UA                | L   | 1.000      | -            | -                | -                | -         |   -11.86 | bnox, maaryy, mASKED, morelz, Vegi    |
|          144 |      750 | 2024-05-19 | Pera Esports              | L   | 1.000      | -            | -                | -                | -         |   -11.89 | bnox, maaryy, mASKED, morelz, Vegi    |
|          143 |      754 | 2024-05-19 | L&G                       | W   | 1.000      | -            | -                | -                | 0 (0.000) |    13.64 | bnox, maaryy, mASKED, morelz, Vegi    |
|          142 |      766 | 2024-05-19 | CYBERSHOKE Esports        | W   | 1.000      | -            | -                | -                | 0 (0.000) |    11.50 | bnox, maaryy, mASKED, morelz, Vegi    |
|          141 |      783 | 2024-05-19 | GameAgents                | W   | 1.000      | -            | -                | -                | -         |     4.94 | bnox, maaryy, mASKED, morelz, Vegi    |
|          140 |     1028 | 2024-05-17 | Sangal Esports            | L   | 1.000      | -            | -                | -                | -         |    -7.58 | bnox, maaryy, mASKED, morelz, Vegi    |
|          139 |     1161 | 2024-05-15 | EYEBALLERS                | L   | 1.000      | -            | -                | -                | -         |   -12.45 | bnox, maaryy, mASKED, morelz, Vegi    |
|          138 |     1182 | 2024-05-15 | ENRAGE                    | W   | 1.000      | -            | -                | -                | -         |     3.97 | bnox, maaryy, mASKED, morelz, Vegi    |
|          137 |     1280 | 2024-05-14 | Team Spirit Academy       | L   | 1.000      | -            | -                | -                | -         |   -19.91 | bnox, maaryy, mASKED, morelz, Vegi    |
|          136 |     1287 | 2024-05-14 | Entropiq                  | L   | 1.000      | -            | -                | -                | -         |   -23.73 | bnox, maaryy, mASKED, morelz, Vegi    |
|          135 |     1328 | 2024-05-13 | 1win                      | L   | 1.000      | -            | -                | -                | -         |   -10.51 | bnox, maaryy, mASKED, morelz, Vegi    |
|          134 |     1337 | 2024-05-13 | DASH                      | W   | 1.000      | -            | -                | -                | -         |     8.06 | bnox, maaryy, mASKED, morelz, Vegi    |
|          133 |     1384 | 2024-05-12 | Rebels Gaming             | L   | 1.000      | -            | -                | -                | -         |    -8.46 | bnox, maaryy, mASKED, morelz, Vegi    |
|          132 |     1405 | 2024-05-12 | ex-Turów Zgorzelec Esport | W   | 1.000      | -            | -                | -                | -         |    11.91 | bnox, maaryy, mASKED, morelz, Vegi    |
|          131 |     1468 | 2024-05-11 | kONO.ECF                  | L   | 1.000      | -            | -                | -                | -         |   -13.58 | bnox, maaryy, mASKED, morelz, Vegi    |
|          130 |     1528 | 2024-05-10 | Sangal Esports            | L   | 1.000      | -            | -                | -                | -         |    -9.35 | bnox, maaryy, mASKED, morelz, Vegi    |
|          129 |     1541 | 2024-05-10 | Wolves eSports            | W   | 1.000      | -            | -                | -                | -         |     4.70 | bnox, maaryy, mASKED, morelz, Vegi    |
|          128 |     1716 | 2024-05-07 | ENTERPRISE esports        | L   | 1.000      | -            | -                | -                | -         |   -16.98 | bnox, maaryy, mASKED, morelz, Sobol   |
|          127 |     1765 | 2024-05-06 | ENCE Academy              | W   | 1.000      | -            | -                | -                | -         |    10.10 | bnox, maaryy, mASKED, morelz, Sobol   |
|          126 |     1905 | 2024-05-03 | Insilio                   | L   | 1.000      | -            | -                | -                | -         |   -12.22 | bnox, maaryy, mASKED, Sidney, Sobol   |
|          125 |     1947 | 2024-05-02 | Team Sampi                | L   | 1.000      | -            | -                | -                | -         |   -13.27 | bnox, maaryy, mASKED, Sidney, Sobol   |
|          124 |     1965 | 2024-05-02 | B8                        | L   | 1.000      | -            | -                | -                | -         |   -10.88 | bnox, maaryy, mASKED, morelz, Sobol   |
|          123 |     2058 | 2024-04-30 | FAVBET Team               | W   | 1.000      | 0.372        | -                | 0.845 (0.315)    | -         |    14.63 | bnox, maaryy, mASKED, morelz, Vegi    |
|          122 |     2079 | 2024-04-30 | BLEED Esports             | L   | 1.000      | -            | -                | -                | -         |    -4.78 | bnox, maaryy, mASKED, morelz, Vegi    |
|          121 |     2110 | 2024-04-29 | AMKAL ESPORTS             | L   | 0.996      | -            | -                | -                | -         |    -6.53 | bnox, maaryy, mASKED, morelz, Vegi    |
|          120 |     2227 | 2024-04-27 | Insilio                   | L   | 0.982      | -            | -                | -                | -         |   -15.05 | bnox, maaryy, mASKED, morelz, Vegi    |
|          119 |     2251 | 2024-04-27 | ENTERPRISE esports        | W   | 0.981      | -            | -                | -                | -         |    12.46 | bnox, maaryy, mASKED, morelz, Vegi    |
|          118 |     2318 | 2024-04-26 | ARCRED                    | L   | 0.975      | -            | -                | -                | -         |   -19.93 | bnox, maaryy, mASKED, morelz, Vegi    |
|          117 |     2359 | 2024-04-25 | 1win                      | L   | 0.970      | -            | -                | -                | -         |   -13.50 | bnox, maaryy, mASKED, morelz, Vegi    |
|          116 |     2414 | 2024-04-24 | BLEED Esports             | L   | 0.964      | -            | -                | -                | -         |    -6.17 | bnox, maaryy, mASKED, morelz, Vegi    |
|          115 |     2429 | 2024-04-24 | Passion UA                | W   | 0.963      | 0.384        | -                | 1.000 (0.370)    | -         |    13.97 | bnox, maaryy, mASKED, morelz, Vegi    |
|          114 |     2435 | 2024-04-24 | DMS                       | W   | 0.962      | 0.372        | -                | 0.754 (0.270)    | -         |    10.51 | bnox, maaryy, mASKED, morelz, Vegi    |
|          113 |     2439 | 2024-04-24 | Team Sampi                | L   | 0.961      | -            | -                | -                | -         |   -13.46 | bnox, maaryy, mASKED, morelz, Vegi    |
|          112 |     2469 | 2024-04-23 | RoundsGG                  | W   | 0.956      | -            | -                | -                | -         |     3.99 | bnox, maaryy, mASKED, morelz, Vegi    |
|          111 |     2476 | 2024-04-23 | RUBY                      | L   | 0.956      | -            | -                | -                | -         |   -15.57 | bnox, maaryy, mASKED, morelz, Vegi    |
|          110 |     2486 | 2024-04-22 | ALTERNATE aTTaX           | W   | 0.954      | -            | -                | -                | -         |    11.74 | bnox, maaryy, mASKED, morelz, Vegi    |
|          109 |     2524 | 2024-04-22 | Grannys Knockers          | W   | 0.948      | -            | -                | -                | -         |     9.53 | bnox, maaryy, mASKED, morelz, Vegi    |
|          108 |     2580 | 2024-04-21 | Insilio                   | W   | 0.941      | 0.435        | -                | 0.717 (0.293)    | -         |    13.83 | bnox, maaryy, mASKED, morelz, Vegi    |
|          107 |     2631 | 2024-04-20 | ENTERPRISE esports        | L   | 0.937      | -            | -                | -                | -         |   -16.17 | bnox, maaryy, mASKED, morelz, Vegi    |
|          106 |     2674 | 2024-04-20 | Nexus Gaming              | L   | 0.936      | -            | -                | -                | -         |   -16.74 | bnox, maaryy, mASKED, morelz, Vegi    |
|          105 |     2704 | 2024-04-20 | Passion UA                | W   | 0.934      | 0.371        | -                | 1.000 (0.346)    | -         |    13.48 | bnox, maaryy, mASKED, morelz, Vegi    |
|          104 |     2838 | 2024-04-18 | Passion UA                | L   | 0.922      | -            | -                | -                | -         |   -15.22 | bnox, maaryy, mASKED, morelz, Vegi    |
|          103 |     2854 | 2024-04-18 | Team Sampi                | L   | 0.921      | -            | -                | -                | -         |   -14.02 | bnox, maaryy, mASKED, morelz, Vegi    |
|          102 |     2904 | 2024-04-17 | PARIVISION                | W   | 0.916      | -            | -                | -                | -         |     9.94 | bnox, maaryy, mASKED, morelz, Vegi    |
|          101 |     2985 | 2024-04-16 | Gaimin Gladiators         | L   | 0.909      | -            | -                | -                | -         |    -4.78 | bnox, maaryy, mASKED, morelz, Vegi    |
|          100 |     3140 | 2024-04-12 | 9INE                      | W   | 0.884      | -            | -                | -                | -         |     3.74 | bnox, maaryy, mASKED, morelz, Vegi    |
|           99 |     3155 | 2024-04-12 | MOUZ NXT                  | W   | 0.882      | 0.371        | 0.157 (0.051)    | 0.977 (0.319)    | -         |    18.19 | bnox, maaryy, mASKED, morelz, Vegi    |
|           98 |     3193 | 2024-04-11 | brazylijski luz           | W   | 0.876      | -            | -                | -                | -         |     7.80 | bnox, maaryy, mASKED, morelz, Vegi    |
|           97 |     3246 | 2024-04-10 | M1 Gaming                 | W   | 0.870      | -            | -                | -                | -         |     3.38 | bnox, maaryy, mASKED, morelz, Vegi    |
|           96 |     3280 | 2024-04-10 | EYEBALLERS                | W   | 0.868      | -            | -                | -                | -         |    11.95 | bnox, maaryy, mASKED, morelz, Vegi    |
|           95 |     3308 | 2024-04-09 | AVEZ                      | W   | 0.864      | -            | -                | -                | -         |     9.45 | bnox, maaryy, mASKED, morelz, Vegi    |
|           94 |     3376 | 2024-04-08 | DEEZ NUTS                 | W   | 0.856      | -            | -                | -                | -         |     4.55 | bnox, maaryy, mASKED, morelz, Vegi    |
|           93 |     3385 | 2024-04-08 | HAVU Gaming               | W   | 0.856      | -            | -                | -                | -         |     6.85 | bnox, maaryy, mASKED, morelz, Vegi    |
|           92 |     3396 | 2024-04-08 | JANO Esports              | W   | 0.854      | -            | -                | -                | -         |     6.90 | bnox, maaryy, mASKED, morelz, Vegi    |
|           91 |     3641 | 2024-04-03 | ENTERPRISE esports        | L   | 0.823      | -            | -                | -                | -         |   -13.59 | bnox, maaryy, mASKED, morelz, Vegi    |
|           90 |     3658 | 2024-04-03 | Dynamo Eclot              | L   | 0.822      | -            | -                | -                | -         |   -10.10 | bnox, maaryy, mASKED, morelz, Vegi    |
|           89 |     3707 | 2024-04-02 | Sashi Esport              | L   | 0.814      | -            | -                | -                | -         |    -9.27 | bnox, maaryy, mASKED, morelz, Vegi    |
|           88 |     3788 | 2024-03-30 | ROSOMAHA                  | W   | 0.795      | -            | -                | -                | -         |     2.98 | bnox, maaryy, mASKED, morelz, Vegi    |
|           87 |     3953 | 2024-03-26 | DMS                       | L   | 0.771      | -            | -                | -                | -         |   -18.17 | bnox, maaryy, mASKED, morelz, Vegi    |
|           86 |     4026 | 2024-03-25 | UNiTY esports             | L   | 0.762      | -            | -                | -                | -         |   -16.23 | bnox, maaryy, mASKED, morelz, Vegi    |
|           85 |     4048 | 2024-03-24 | Astralis Talent           | W   | 0.756      | -            | -                | -                | -         |     9.02 | bnox, maaryy, mASKED, morelz, Vegi    |
|           84 |     4052 | 2024-03-24 | GamerLegion Academy       | L   | 0.755      | -            | -                | -                | -         |   -16.95 | bnox, maaryy, mASKED, morelz, Vegi    |
|           83 |     4202 | 2024-03-21 | ex-K10                    | W   | 0.736      | -            | -                | -                | -         |     6.54 | bnox, maaryy, mASKED, morelz, Vegi    |
|           82 |     4245 | 2024-03-20 | K10                       | W   | 0.728      | -            | -                | -                | -         |     0.80 | bnox, maaryy, mASKED, morelz, Vegi    |
|           81 |     4327 | 2024-03-18 | NOM Esports               | W   | 0.716      | -            | -                | -                | -         |     1.41 | bnox, maaryy, mASKED, morelz, Vegi    |
|           80 |     4437 | 2024-03-16 | RUBY                      | L   | 0.703      | -            | -                | -                | -         |   -13.03 | bnox, maaryy, mASKED, morelz, Vegi    |
|           79 |     4492 | 2024-03-15 | The Chosen Few            | W   | 0.696      | -            | -                | -                | -         |     6.37 | bnox, maaryy, mASKED, morelz, Vegi    |
|           78 |     4504 | 2024-03-15 | Team Sampi                | L   | 0.695      | -            | -                | -                | -         |   -11.95 | bnox, maaryy, mASKED, morelz, Vegi    |
|           77 |     4558 | 2024-03-14 | ex-K10                    | L   | 0.689      | -            | -                | -                | -         |   -16.39 | bnox, maaryy, mASKED, morelz, Vegi    |
|           76 |     4588 | 2024-03-13 | MOUZ NXT                  | W   | 0.685      | 0.371        | 0.157 (0.040)    | -                | -         |    13.13 | bnox, maaryy, mASKED, morelz, Vegi    |
|           75 |     4618 | 2024-03-13 | Dynamo Eclot              | W   | 0.683      | 0.384        | 0.097 (0.025)    | -                | -         |    12.39 | bnox, maaryy, mASKED, morelz, Vegi    |
|           74 |     4641 | 2024-03-13 | Dynamo Eclot              | W   | 0.682      | 0.371        | 0.097 (0.024)    | -                | -         |    13.11 | bnox, maaryy, mASKED, morelz, Vegi    |
|           73 |     4754 | 2024-03-11 | ex-Preasy Esport          | L   | 0.669      | -            | -                | -                | -         |   -10.09 | bnox, maaryy, mASKED, morelz, Vegi    |
|           72 |     4859 | 2024-03-09 | Sashi Esport              | L   | 0.656      | -            | -                | -                | -         |    -9.22 | bnox, maaryy, mASKED, morelz, Vegi    |
|           71 |     4940 | 2024-03-07 | VP.Prodigy                | W   | 0.644      | -            | -                | -                | -         |     6.69 | bnox, maaryy, mASKED, morelz, Vegi    |
|           70 |     4957 | 2024-03-07 | kONO.ECF                  | W   | 0.642      | -            | -                | -                | -         |     8.73 | bnox, maaryy, mASKED, morelz, Vegi    |
|           69 |     5022 | 2024-03-06 | Passion UA                | W   | 0.636      | -            | -                | -                | -         |     9.21 | bnox, maaryy, mASKED, morelz, Vegi    |
|           68 |     5038 | 2024-03-06 | ENTERPRISE esports        | W   | 0.636      | -            | -                | -                | -         |     9.78 | bnox, maaryy, mASKED, morelz, Vegi    |
|           67 |     5114 | 2024-03-05 | Young Ninjas              | W   | 0.629      | -            | -                | -                | -         |     9.66 | bnox, maaryy, mASKED, morelz, Vegi    |
|           66 |     5124 | 2024-03-05 | Astralis Talent           | L   | 0.629      | -            | -                | -                | -         |   -10.79 | bnox, maaryy, mASKED, morelz, Vegi    |
|           65 |     5136 | 2024-03-04 | UGANDA                    | L   | 0.625      | -            | -                | -                | -         |   -18.23 | bnox, maaryy, mASKED, morelz, Vegi    |
|           64 |     5148 | 2024-03-04 | UNiTY esports             | W   | 0.625      | -            | -                | -                | -         |     6.02 | bnox, maaryy, mASKED, morelz, Vegi    |
|           63 |     5278 | 2024-03-02 | SINNERS Esports           | L   | 0.612      | -            | -                | -                | -         |    -9.22 | bnox, maaryy, mASKED, morelz, Vegi    |
|           62 |     5293 | 2024-03-02 | Astralis Talent           | W   | 0.611      | -            | -                | -                | -         |     8.32 | bnox, maaryy, mASKED, morelz, Vegi    |
|           61 |     5352 | 2024-03-02 | AURA                      | W   | 0.609      | -            | -                | -                | -         |     2.97 | bnox, maaryy, mASKED, morelz, Vegi    |
|           60 |     5417 | 2024-02-29 | Sashi Esport              | L   | 0.597      | -            | -                | -                | -         |    -7.18 | bnox, maaryy, mASKED, morelz, Vegi    |
|           59 |     5445 | 2024-02-29 | ENCE Academy              | W   | 0.595      | -            | -                | -                | -         |     6.08 | bnox, maaryy, mASKED, morelz, Vegi    |
|           58 |     5458 | 2024-02-28 | RUBY                      | W   | 0.591      | -            | -                | -                | -         |     8.64 | bnox, maaryy, mASKED, morelz, Vegi    |
|           57 |     5486 | 2024-02-28 | Team Secret               | L   | 0.589      | -            | -                | -                | -         |   -15.91 | bnox, maaryy, mASKED, morelz, Vegi    |
|           56 |     5493 | 2024-02-28 | Dynamo Eclot              | L   | 0.588      | -            | -                | -                | -         |    -6.34 | bnox, maaryy, mASKED, morelz, Vegi    |
|           55 |     5538 | 2024-02-27 | Sprout                    | W   | 0.582      | -            | -                | -                | -         |     2.80 | bnox, maaryy, mASKED, morelz, Vegi    |
|           54 |     5583 | 2024-02-26 | Reason Gaming             | W   | 0.575      | -            | -                | -                | -         |     4.40 | bnox, maaryy, mASKED, morelz, Vegi    |
|           53 |     5609 | 2024-02-25 | Verdant                   | W   | 0.570      | -            | -                | -                | -         |     8.58 | bnox, maaryy, mASKED, morelz, Vegi    |
|           52 |     5719 | 2024-02-24 | Dynamo Eclot              | W   | 0.562      | -            | -                | -                | -         |    11.82 | bnox, maaryy, mASKED, morelz, Vegi    |
|           51 |     5813 | 2024-02-22 | ARCRED                    | L   | 0.551      | -            | -                | -                | -         |   -13.12 | bnox, maaryy, mASKED, morelz, Vegi    |
|           50 |     5821 | 2024-02-22 | The Chosen Few            | L   | 0.550      | -            | -                | -                | -         |   -13.76 | bnox, maaryy, mASKED, morelz, Vegi    |
|           49 |     5833 | 2024-02-22 | ex-Turów Zgorzelec Esport | W   | 0.548      | -            | -                | -                | -         |     4.25 | bnox, maaryy, mASKED, morelz, Vegi    |
|           48 |     5862 | 2024-02-21 | MOUZ NXT                  | W   | 0.544      | 0.371        | 0.157 (0.032)    | -                | -         |    11.70 | bnox, maaryy, mASKED, morelz, Vegi    |
|           47 |     5906 | 2024-02-21 | Dynamo Eclot              | L   | 0.542      | -            | -                | -                | -         |    -6.01 | bnox, maaryy, mASKED, morelz, Vegi    |
|           46 |     5937 | 2024-02-20 | GenOne                    | W   | 0.537      | -            | -                | -                | -         |     1.56 | bnox, maaryy, mASKED, morelz, Vegi    |
|           45 |     5956 | 2024-02-20 | Sangal Esports            | W   | 0.536      | 0.333        | 0.166 (0.030)    | -                | -         |    10.30 | bnox, maaryy, mASKED, morelz, Vegi    |
|           44 |     6020 | 2024-02-19 | Dynamo Eclot              | W   | 0.529      | -            | -                | -                | -         |    11.19 | bnox, maaryy, mASKED, morelz, Vegi    |
|           43 |     6129 | 2024-02-17 | Viperio                   | W   | 0.516      | -            | -                | -                | -         |     2.48 | bnox, maaryy, mASKED, morelz, Vegi    |
|           42 |     6177 | 2024-02-16 | Sashi Esport              | L   | 0.509      | -            | -                | -                | -         |    -5.62 | bnox, maaryy, mASKED, morelz, Vegi    |
|           41 |     6240 | 2024-02-15 | Sashi Esport              | W   | 0.502      | -            | -                | -                | -         |     1.83 | bnox, maaryy, mASKED, morelz, Vegi    |
|           40 |     6399 | 2024-02-12 | ex-sYnck                  | W   | 0.484      | -            | -                | -                | -         |     3.58 | bnox, maaryy, mASKED, morelz, Vegi    |
|           39 |     6406 | 2024-02-12 | Sangal Esports            | W   | 0.482      | 0.333        | 0.166 (0.027)    | -                | -         |     9.77 | bnox, maaryy, mASKED, morelz, Vegi    |
|           38 |     6409 | 2024-02-12 | Lilmix                    | W   | 0.482      | -            | -                | -                | -         |     5.36 | bnox, maaryy, mASKED, morelz, Vegi    |
|           37 |     6560 | 2024-02-07 | Endpoint                  | L   | 0.449      | -            | -                | -                | -         |    -6.87 | bnox, maaryy, mASKED, morelz, Vegi    |
|           36 |     6676 | 2024-02-04 | Natus Vincere Junior      | L   | 0.429      | -            | -                | -                | -         |    -9.72 | bnox, maaryy, mASKED, morelz, Vegi    |
|           35 |     6915 | 2024-01-31 | kONO.ECF                  | L   | 0.404      | -            | -                | -                | -         |    -7.90 | bnox, maaryy, mASKED, morelz, Vegi    |
|           34 |     6924 | 2024-01-31 | Team Secret               | W   | 0.404      | -            | -                | -                | -         |     1.68 | bnox, maaryy, mASKED, morelz, Vegi    |
|           33 |     6943 | 2024-01-31 | Sashi Esport              | W   | 0.403      | 0.384        | 0.154 (0.024)    | -                | -         |     8.27 | bnox, maaryy, mASKED, morelz, Vegi    |
|           32 |     6968 | 2024-01-30 | RUBY                      | L   | 0.398      | -            | -                | -                | -         |    -6.99 | bnox, maaryy, mASKED, morelz, Vegi    |
|           31 |     6976 | 2024-01-30 | 3DMAX                     | W   | 0.397      | -            | -                | -                | -         |     6.24 | bnox, maaryy, mASKED, morelz, Vegi    |
|           30 |     6999 | 2024-01-29 | GODSENT                   | W   | 0.392      | -            | -                | -                | -         |     2.05 | bnox, maaryy, mASKED, morelz, Vegi    |
|           29 |     7033 | 2024-01-29 | RAVAGERS                  | W   | 0.392      | -            | -                | -                | -         |     0.53 | bnox, maaryy, mASKED, morelz, Vegi    |
|           28 |     7083 | 2024-01-28 | ex-Anonymo Esports        | L   | 0.384      | -            | -                | -                | -         |    -9.60 | bnox, maaryy, mASKED, morelz, Vegi    |
|           27 |     7089 | 2024-01-28 | showmakerz                | W   | 0.383      | -            | -                | -                | -         |     1.07 | bnox, maaryy, mASKED, morelz, Vegi    |
|           26 |     7261 | 2024-01-26 | Lausanne-Sport Esports    | W   | 0.370      | -            | -                | -                | -         |     2.90 | bnox, maaryy, mASKED, morelz, Vegi    |
|           25 |     7352 | 2024-01-24 | lajtbitexe                | W   | 0.357      | -            | -                | -                | -         |     1.56 | bnox, maaryy, mASKED, morelz, Vegi    |
|           24 |     7602 | 2024-01-20 | Gaimin Gladiators         | L   | 0.329      | -            | -                | -                | -         |    -1.49 | bnox, maaryy, mASKED, morelz, Vegi    |
|           23 |     7608 | 2024-01-20 | Astralis Talent           | L   | 0.328      | -            | -                | -                | -         |    -5.58 | bnox, maaryy, mASKED, morelz, Vegi    |
|           22 |     7647 | 2024-01-19 | JANO Esports              | W   | 0.324      | -            | -                | -                | -         |     0.80 | bnox, maaryy, mASKED, morelz, Vegi    |
|           21 |     7673 | 2024-01-19 | Aurora Young Blud         | W   | 0.322      | -            | -                | -                | -         |     3.01 | bnox, maaryy, mASKED, morelz, Vegi    |
|           20 |     7707 | 2024-01-18 | Zero Tenacity             | L   | 0.318      | -            | -                | -                | -         |    -3.63 | bnox, maaryy, mASKED, morelz, Vegi    |
|           19 |     7730 | 2024-01-18 | BIG                       | L   | 0.317      | -            | -                | -                | -         |    -0.71 | bnox, maaryy, mASKED, morelz, Vegi    |
|           18 |     7739 | 2024-01-18 | Team Spirit Academy       | W   | 0.316      | -            | -                | -                | -         |     2.21 | bnox, maaryy, mASKED, morelz, Vegi    |
|           17 |     7832 | 2024-01-17 | Astralis Talent           | L   | 0.309      | -            | -                | -                | -         |    -5.34 | bnox, maaryy, mASKED, morelz, Vegi    |
|           16 |     8009 | 2024-01-14 | Dynamo Eclot              | W   | 0.289      | -            | -                | -                | -         |     6.17 | bnox, maaryy, mASKED, morelz, Vegi    |
|           15 |     8030 | 2024-01-13 | ex-sYnck                  | W   | 0.285      | -            | -                | -                | -         |     2.09 | bnox, maaryy, mASKED, morelz, Vegi    |
|           14 |     8034 | 2024-01-13 | OG                        | L   | 0.284      | -            | -                | -                | -         |    -1.94 | bnox, maaryy, mASKED, morelz, Vegi    |
|           13 |     8037 | 2024-01-13 | Insilio                   | W   | 0.284      | -            | -                | -                | -         |     3.73 | bnox, maaryy, mASKED, morelz, Vegi    |
|           12 |     8040 | 2024-01-13 | Infinite Gaming           | W   | 0.283      | -            | -                | -                | -         |     0.67 | bnox, maaryy, mASKED, morelz, Vegi    |
|           11 |     8079 | 2024-01-12 | Clownfiesta               | W   | 0.279      | -            | -                | -                | -         |     0.38 | bnox, maaryy, mASKED, morelz, Vegi    |
|           10 |     8110 | 2024-01-12 | Lilmix                    | W   | 0.278      | -            | -                | -                | -         |     0.90 | bnox, maaryy, mASKED, morelz, Vegi    |
|            9 |     8126 | 2024-01-12 | Lilmix                    | W   | 0.276      | -            | -                | -                | -         |     0.91 | bnox, maaryy, mASKED, morelz, Vegi    |
|            8 |     8130 | 2024-01-12 | MOUZ NXT                  | L   | 0.275      | -            | -                | -                | -         |    -2.53 | bnox, maaryy, mASKED, morelz, Vegi    |
|            7 |     8201 | 2024-01-11 | Pera Esports              | L   | 0.270      | -            | -                | -                | -         |    -4.76 | bnox, maaryy, mASKED, morelz, Vegi    |
|            6 |     8208 | 2024-01-11 | Verdant                   | W   | 0.268      | -            | -                | -                | -         |     0.34 | bnox, maaryy, mASKED, morelz, Vegi    |
|            5 |     8245 | 2024-01-10 | ILLYRIANS                 | W   | 0.265      | -            | -                | -                | -         |     0.35 | bnox, maaryy, mASKED, morelz, Vegi    |
|            4 |     8268 | 2024-01-10 | ex-K10                    | W   | 0.265      | -            | -                | -                | -         |     3.21 | bnox, maaryy, mASKED, morelz, Vegi    |
|            3 |     8393 | 2024-01-09 | Astralis Talent           | W   | 0.256      | -            | -                | -                | -         |     3.66 | bnox, maaryy, mASKED, morelz, Vegi    |
|            2 |     8450 | 2024-01-07 | Lilmix                    | L   | 0.242      | -            | -                | -                | -         |    -6.91 | bnox, maaryy, mASKED, morelz, Vegi    |
|            1 |     8477 | 2024-01-05 | Passion UA                | L   | 0.229      | -            | -                | -                | -         |    -3.15 | bnox, maaryy, mASKED, morelz, Vegi    |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($7,645.80)
- Divide that value by the 5th highest value among all rosters ($300,806.11)
- The final value (0.03) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-05-02 |      1.000 | $500.00        | $500.00         |
| 2024-04-25 |      0.968 | $3,000.00      | $2,903.33       |
| 2024-04-21 |      0.943 | $1,232.30      | $1,162.47       |
| 2024-02-28 |      0.588 | $3,000.00      | $1,765.00       |
| 2024-02-21 |      0.542 | $1,500.00      | $812.50         |
| 2024-01-21 |      0.335 | $1,500.00      | $502.50         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
