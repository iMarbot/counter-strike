### Roster Details<br />
Team Name: Permitta Esports<br />
Roster: bnox, maaryy, mASKED, morelz, Vegi<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [133](../standings_global.md)<br />
Regional Rank: [93]( ../standings_europe.md)<br />
Final Rank Value:  804.9<br />
<br />
Final Rank Value (804.9) = Starting Rank Value (964.6) + Head To Head Adjustments (-159.7)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.393[<sup>1</sup>](#table2)
- Bounty Collected: 0.405[<sup>2</sup>](#table1)
- Opponent Network: 0.311[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.277<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 964.6
- 400 + ( ( 0.277 - 0.000 ) / ( 0.786 - 0.000 ) ) * 1600 = 964.6


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent                  | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                               |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|          157 |      136 | 2024-05-28 | Preasy Esport             | W   | 1.000      | -            | -                | -                | 0 (0.000) |    12.46 | bnox, maaryy, mASKED, morelz, Vegi   |
|          156 |      138 | 2024-05-28 | GUN5 Esports              | W   | 1.000      | -            | -                | -                | 0 (0.000) |    16.09 | bnox, maaryy, mASKED, morelz, Vegi   |
|          155 |      181 | 2024-05-27 | VP.Prodigy                | L   | 1.000      | -            | -                | -                | -         |   -10.87 | bnox, maaryy, mASKED, morelz, Vegi   |
|          154 |      189 | 2024-05-27 | Copenhagen Wolves         | L   | 1.000      | -            | -                | -                | -         |   -21.43 | bnox, maaryy, mASKED, morelz, Vegi   |
|          153 |      236 | 2024-05-26 | Dynamo Eclot              | W   | 1.000      | 0.371        | 0.097 (0.036)    | 0.936 (0.347)    | 0 (0.000) |    20.08 | bnox, maaryy, mASKED, morelz, Vegi   |
|          152 |      262 | 2024-05-25 | Rustec                    | L   | 1.000      | -            | -                | -                | -         |   -15.40 | bnox, maaryy, mASKED, morelz, Vegi   |
|          151 |      301 | 2024-05-25 | The Agency Clan           | L   | 1.000      | -            | -                | -                | -         |   -26.72 | bnox, maaryy, mASKED, morelz, Vegi   |
|          150 |      362 | 2024-05-24 | LEON Esports              | W   | 1.000      | -            | -                | -                | 0 (0.000) |    11.82 | bnox, maaryy, mASKED, morelz, Vegi   |
|          149 |      386 | 2024-05-23 | Zero Tenacity             | W   | 1.000      | 0.372        | 0.147 (0.055)    | 1.000 (0.372)    | 0 (0.000) |    25.31 | bnox, maaryy, mASKED, morelz, Vegi   |
|          148 |      410 | 2024-05-23 | Endpoint                  | L   | 1.000      | -            | -                | -                | -         |   -13.22 | bnox, maaryy, mASKED, morelz, Vegi   |
|          147 |      491 | 2024-05-22 | Endpoint                  | W   | 1.000      | 0.435        | -                | 0.718 (0.312)    | 0 (0.000) |    17.59 | bnox, maaryy, mASKED, morelz, tomiko |
|          146 |      502 | 2024-05-22 | Natus Vincere Junior      | L   | 1.000      | -            | -                | -                | -         |   -16.37 | bnox, maaryy, mASKED, morelz, Vegi   |
|          145 |      510 | 2024-05-22 | CYBERSHOKE Esports        | L   | 1.000      | -            | -                | -                | -         |   -18.90 | bnox, maaryy, mASKED, morelz, Vegi   |
|          144 |      526 | 2024-05-22 | Johnny Speeds             | L   | 1.000      | -            | -                | -                | -         |    -7.74 | bnox, maaryy, mASKED, morelz, Vegi   |
|          143 |      570 | 2024-05-21 | Infinite Gaming           | W   | 1.000      | -            | -                | -                | 0 (0.000) |     4.25 | bnox, maaryy, mASKED, morelz, Vegi   |
|          142 |      705 | 2024-05-20 | ENCE Academy              | W   | 1.000      | -            | -                | -                | 0 (0.000) |    11.98 | bnox, maaryy, mASKED, morelz, Vegi   |
|          141 |      719 | 2024-05-20 | Passion UA                | L   | 1.000      | -            | -                | -                | -         |   -11.51 | bnox, maaryy, mASKED, morelz, Vegi   |
|          140 |      738 | 2024-05-19 | Pera Esports              | L   | 1.000      | -            | -                | -                | -         |   -10.94 | bnox, maaryy, mASKED, morelz, Vegi   |
|          139 |      742 | 2024-05-19 | L&G                       | W   | 1.000      | -            | -                | -                | 0 (0.000) |    14.35 | bnox, maaryy, mASKED, morelz, Vegi   |
|          138 |      754 | 2024-05-19 | CYBERSHOKE Esports        | W   | 1.000      | -            | -                | -                | 0 (0.000) |    12.05 | bnox, maaryy, mASKED, morelz, Vegi   |
|          137 |      771 | 2024-05-19 | GameAgents                | W   | 1.000      | -            | -                | -                | -         |     5.42 | bnox, maaryy, mASKED, morelz, Vegi   |
|          136 |     1016 | 2024-05-17 | Sangal Esports            | L   | 1.000      | -            | -                | -                | -         |    -7.68 | bnox, maaryy, mASKED, morelz, Vegi   |
|          135 |     1152 | 2024-05-15 | EYEBALLERS                | L   | 1.000      | -            | -                | -                | -         |   -11.26 | bnox, maaryy, mASKED, morelz, Vegi   |
|          134 |     1172 | 2024-05-15 | ENRAGE                    | W   | 1.000      | -            | -                | -                | -         |     4.97 | bnox, maaryy, mASKED, morelz, Vegi   |
|          133 |     1269 | 2024-05-14 | Team Spirit Academy       | L   | 1.000      | -            | -                | -                | -         |   -20.29 | bnox, maaryy, mASKED, morelz, Vegi   |
|          132 |     1276 | 2024-05-14 | Entropiq                  | L   | 1.000      | -            | -                | -                | -         |   -23.10 | bnox, maaryy, mASKED, morelz, Vegi   |
|          131 |     1316 | 2024-05-13 | 1win                      | L   | 1.000      | -            | -                | -                | -         |    -9.53 | bnox, maaryy, mASKED, morelz, Vegi   |
|          130 |     1325 | 2024-05-13 | DASH                      | W   | 1.000      | -            | -                | -                | -         |     7.82 | bnox, maaryy, mASKED, morelz, Vegi   |
|          129 |     1371 | 2024-05-12 | Rebels Gaming             | L   | 1.000      | -            | -                | -                | -         |    -7.91 | bnox, maaryy, mASKED, morelz, Vegi   |
|          128 |     1392 | 2024-05-12 | ex-Turów Zgorzelec Esport | W   | 1.000      | -            | -                | -                | -         |    11.40 | bnox, maaryy, mASKED, morelz, Vegi   |
|          127 |     1455 | 2024-05-11 | kONO.ECF                  | L   | 1.000      | -            | -                | -                | -         |   -12.93 | bnox, maaryy, mASKED, morelz, Vegi   |
|          126 |     1514 | 2024-05-10 | Sangal Esports            | L   | 1.000      | -            | -                | -                | -         |    -9.47 | bnox, maaryy, mASKED, morelz, Vegi   |
|          125 |     1526 | 2024-05-10 | Wolves eSports            | W   | 1.000      | -            | -                | -                | -         |     5.26 | bnox, maaryy, mASKED, morelz, Vegi   |
|          124 |     1696 | 2024-05-07 | ENTERPRISE esports        | L   | 1.000      | -            | -                | -                | -         |   -16.64 | bnox, maaryy, mASKED, morelz, Sobol  |
|          123 |     1742 | 2024-05-06 | ENCE Academy              | W   | 1.000      | -            | -                | -                | -         |    10.92 | bnox, maaryy, mASKED, morelz, Sobol  |
|          122 |     1880 | 2024-05-03 | Insilio                   | L   | 1.000      | -            | -                | -                | -         |   -11.22 | bnox, maaryy, mASKED, Sidney, Sobol  |
|          121 |     1920 | 2024-05-02 | Team Sampi                | L   | 1.000      | -            | -                | -                | -         |   -12.25 | bnox, maaryy, mASKED, Sidney, Sobol  |
|          120 |     1938 | 2024-05-02 | B8                        | L   | 1.000      | -            | -                | -                | -         |    -9.32 | bnox, maaryy, mASKED, morelz, Sobol  |
|          119 |     2045 | 2024-04-30 | BLEED Esports             | L   | 1.000      | -            | -                | -                | -         |    -4.41 | bnox, maaryy, mASKED, morelz, Vegi   |
|          118 |     2075 | 2024-04-29 | AMKAL ESPORTS             | L   | 0.996      | -            | -                | -                | -         |    -6.13 | bnox, maaryy, mASKED, morelz, Vegi   |
|          117 |     2192 | 2024-04-27 | Insilio                   | L   | 0.982      | -            | -                | -                | -         |   -14.41 | bnox, maaryy, mASKED, morelz, Vegi   |
|          116 |     2216 | 2024-04-27 | ENTERPRISE esports        | W   | 0.981      | -            | -                | -                | -         |    12.26 | bnox, maaryy, mASKED, morelz, Vegi   |
|          115 |     2281 | 2024-04-26 | ARCRED                    | L   | 0.975      | -            | -                | -                | -         |   -19.32 | bnox, maaryy, mASKED, morelz, Vegi   |
|          114 |     2319 | 2024-04-25 | 1win                      | L   | 0.970      | -            | -                | -                | -         |   -12.45 | bnox, maaryy, mASKED, morelz, Vegi   |
|          113 |     2371 | 2024-04-24 | BLEED Esports             | L   | 0.964      | -            | -                | -                | -         |    -5.61 | bnox, maaryy, mASKED, morelz, Vegi   |
|          112 |     2385 | 2024-04-24 | Passion UA                | W   | 0.963      | 0.384        | 0.057 (0.021)    | 1.000 (0.370)    | -         |    14.05 | bnox, maaryy, mASKED, morelz, Vegi   |
|          111 |     2390 | 2024-04-24 | DMS                       | W   | 0.962      | 0.372        | -                | 0.751 (0.269)    | -         |    10.89 | bnox, maaryy, mASKED, morelz, Vegi   |
|          110 |     2394 | 2024-04-24 | Team Sampi                | L   | 0.961      | -            | -                | -                | -         |   -12.86 | bnox, maaryy, mASKED, morelz, Vegi   |
|          109 |     2421 | 2024-04-23 | RoundsGG                  | W   | 0.956      | -            | -                | -                | -         |     3.61 | bnox, maaryy, mASKED, morelz, Vegi   |
|          108 |     2428 | 2024-04-23 | RUBY                      | L   | 0.956      | -            | -                | -                | -         |   -14.85 | bnox, maaryy, mASKED, morelz, Vegi   |
|          107 |     2438 | 2024-04-22 | ALTERNATE aTTaX           | W   | 0.954      | -            | -                | -                | -         |    12.67 | bnox, maaryy, mASKED, morelz, Vegi   |
|          106 |     2527 | 2024-04-21 | Insilio                   | W   | 0.941      | 0.435        | -                | 0.717 (0.293)    | -         |    14.30 | bnox, maaryy, mASKED, morelz, Vegi   |
|          105 |     2578 | 2024-04-20 | ENTERPRISE esports        | L   | 0.937      | -            | -                | -                | -         |   -16.70 | bnox, maaryy, mASKED, morelz, Vegi   |
|          104 |     2620 | 2024-04-20 | Nexus Gaming              | L   | 0.936      | -            | -                | -                | -         |   -16.58 | bnox, maaryy, mASKED, morelz, Vegi   |
|          103 |     2650 | 2024-04-20 | Passion UA                | W   | 0.934      | 0.371        | -                | 1.000 (0.346)    | -         |    13.12 | bnox, maaryy, mASKED, morelz, Vegi   |
|          102 |     2782 | 2024-04-18 | Passion UA                | L   | 0.922      | -            | -                | -                | -         |   -15.65 | bnox, maaryy, mASKED, morelz, Vegi   |
|          101 |     2798 | 2024-04-18 | Team Sampi                | L   | 0.921      | -            | -                | -                | -         |   -13.78 | bnox, maaryy, mASKED, morelz, Vegi   |
|          100 |     2848 | 2024-04-17 | PARIVISION                | W   | 0.916      | -            | -                | -                | -         |    10.56 | bnox, maaryy, mASKED, morelz, Vegi   |
|           99 |     2924 | 2024-04-16 | Gaimin Gladiators         | L   | 0.909      | -            | -                | -                | -         |    -4.61 | bnox, maaryy, mASKED, morelz, Vegi   |
|           98 |     3074 | 2024-04-12 | 9INE                      | W   | 0.884      | -            | -                | -                | -         |     3.92 | bnox, maaryy, mASKED, morelz, Vegi   |
|           97 |     3089 | 2024-04-12 | MOUZ NXT                  | W   | 0.882      | 0.371        | 0.157 (0.051)    | 0.950 (0.310)    | -         |    18.21 | bnox, maaryy, mASKED, morelz, Vegi   |
|           96 |     3124 | 2024-04-11 | brazylijski luz           | W   | 0.876      | -            | -                | -                | -         |     7.76 | bnox, maaryy, mASKED, morelz, Vegi   |
|           95 |     3173 | 2024-04-10 | M1 Gaming                 | W   | 0.870      | -            | -                | -                | -         |     3.57 | bnox, maaryy, mASKED, morelz, Vegi   |
|           94 |     3203 | 2024-04-10 | EYEBALLERS                | W   | 0.868      | -            | -                | -                | -         |    12.71 | bnox, maaryy, mASKED, morelz, Vegi   |
|           93 |     3230 | 2024-04-09 | AVEZ                      | W   | 0.864      | -            | -                | -                | -         |     8.58 | bnox, maaryy, mASKED, morelz, Vegi   |
|           92 |     3295 | 2024-04-08 | DEEZ NUTS                 | W   | 0.856      | -            | -                | -                | -         |     4.78 | bnox, maaryy, mASKED, morelz, Vegi   |
|           91 |     3304 | 2024-04-08 | HAVU Gaming               | W   | 0.856      | -            | -                | -                | -         |     7.16 | bnox, maaryy, mASKED, morelz, Vegi   |
|           90 |     3315 | 2024-04-08 | JANO Esports              | W   | 0.854      | -            | -                | -                | -         |     7.26 | bnox, maaryy, mASKED, morelz, Vegi   |
|           89 |     3554 | 2024-04-03 | ENTERPRISE esports        | L   | 0.823      | -            | -                | -                | -         |   -14.58 | bnox, maaryy, mASKED, morelz, Vegi   |
|           88 |     3571 | 2024-04-03 | Dynamo Eclot              | L   | 0.822      | -            | -                | -                | -         |    -9.64 | bnox, maaryy, mASKED, morelz, Vegi   |
|           87 |     3617 | 2024-04-02 | Sashi Esport              | L   | 0.814      | -            | -                | -                | -         |    -8.57 | bnox, maaryy, mASKED, morelz, Vegi   |
|           86 |     3695 | 2024-03-30 | ROSOMAHA                  | W   | 0.795      | -            | -                | -                | -         |     3.01 | bnox, maaryy, mASKED, morelz, Vegi   |
|           85 |     3856 | 2024-03-26 | DMS                       | L   | 0.771      | -            | -                | -                | -         |   -18.14 | bnox, maaryy, mASKED, morelz, Vegi   |
|           84 |     3930 | 2024-03-25 | UNiTY esports             | L   | 0.762      | -            | -                | -                | -         |   -15.84 | bnox, maaryy, mASKED, morelz, Vegi   |
|           83 |     3951 | 2024-03-24 | Astralis Talent           | W   | 0.756      | -            | -                | -                | -         |     9.33 | bnox, maaryy, mASKED, morelz, Vegi   |
|           82 |     3954 | 2024-03-24 | GamerLegion Academy       | L   | 0.755      | -            | -                | -                | -         |   -16.49 | bnox, maaryy, mASKED, morelz, Vegi   |
|           81 |     4102 | 2024-03-21 | ex-K10                    | W   | 0.736      | -            | -                | -                | -         |     6.68 | bnox, maaryy, mASKED, morelz, Vegi   |
|           80 |     4143 | 2024-03-20 | K10                       | W   | 0.728      | -            | -                | -                | -         |     0.86 | bnox, maaryy, mASKED, morelz, Vegi   |
|           79 |     4222 | 2024-03-18 | NOM Esports               | W   | 0.716      | -            | -                | -                | -         |     1.51 | bnox, maaryy, mASKED, morelz, Vegi   |
|           78 |     4331 | 2024-03-16 | RUBY                      | L   | 0.703      | -            | -                | -                | -         |   -12.67 | bnox, maaryy, mASKED, morelz, Vegi   |
|           77 |     4383 | 2024-03-15 | The Chosen Few            | W   | 0.696      | -            | -                | -                | -         |     6.97 | bnox, maaryy, mASKED, morelz, Vegi   |
|           76 |     4394 | 2024-03-15 | Team Sampi                | L   | 0.695      | -            | -                | -                | -         |   -11.58 | bnox, maaryy, mASKED, morelz, Vegi   |
|           75 |     4444 | 2024-03-14 | ex-K10                    | L   | 0.689      | -            | -                | -                | -         |   -16.21 | bnox, maaryy, mASKED, morelz, Vegi   |
|           74 |     4474 | 2024-03-13 | MOUZ NXT                  | W   | 0.685      | 0.371        | 0.157 (0.040)    | -                | -         |    13.19 | bnox, maaryy, mASKED, morelz, Vegi   |
|           73 |     4503 | 2024-03-13 | Dynamo Eclot              | W   | 0.683      | 0.384        | 0.097 (0.025)    | 0.936 (0.246)    | -         |    12.65 | bnox, maaryy, mASKED, morelz, Vegi   |
|           72 |     4522 | 2024-03-13 | Dynamo Eclot              | W   | 0.682      | 0.371        | 0.097 (0.024)    | -                | -         |    13.39 | bnox, maaryy, mASKED, morelz, Vegi   |
|           71 |     4631 | 2024-03-11 | ex-Preasy Esport          | L   | 0.669      | -            | -                | -                | -         |    -9.74 | bnox, maaryy, mASKED, morelz, Vegi   |
|           70 |     4734 | 2024-03-09 | Sashi Esport              | L   | 0.656      | -            | -                | -                | -         |    -8.82 | bnox, maaryy, mASKED, morelz, Vegi   |
|           69 |     4811 | 2024-03-07 | VP.Prodigy                | W   | 0.644      | -            | -                | -                | -         |     6.72 | bnox, maaryy, mASKED, morelz, Vegi   |
|           68 |     4890 | 2024-03-06 | Passion UA                | W   | 0.636      | 0.384        | -                | 1.000 (0.245)    | -         |     9.27 | bnox, maaryy, mASKED, morelz, Vegi   |
|           67 |     4904 | 2024-03-06 | ENTERPRISE esports        | W   | 0.636      | -            | -                | -                | -         |     9.39 | bnox, maaryy, mASKED, morelz, Vegi   |
|           66 |     4970 | 2024-03-05 | Young Ninjas              | W   | 0.629      | -            | -                | -                | -         |     9.91 | bnox, maaryy, mASKED, morelz, Vegi   |
|           65 |     4978 | 2024-03-05 | Astralis Talent           | L   | 0.629      | -            | -                | -                | -         |   -10.63 | bnox, maaryy, mASKED, morelz, Vegi   |
|           64 |     4990 | 2024-03-04 | UGANDA                    | L   | 0.625      | -            | -                | -                | -         |   -18.16 | bnox, maaryy, mASKED, morelz, Vegi   |
|           63 |     5002 | 2024-03-04 | UNiTY esports             | W   | 0.625      | -            | -                | -                | -         |     6.28 | bnox, maaryy, mASKED, morelz, Vegi   |
|           62 |     5130 | 2024-03-02 | SINNERS Esports           | L   | 0.612      | -            | -                | -                | -         |    -9.57 | bnox, maaryy, mASKED, morelz, Vegi   |
|           61 |     5145 | 2024-03-02 | Astralis Talent           | W   | 0.611      | -            | -                | -                | -         |     8.48 | bnox, maaryy, mASKED, morelz, Vegi   |
|           60 |     5203 | 2024-03-02 | AURA                      | W   | 0.609      | -            | -                | -                | -         |     3.01 | bnox, maaryy, mASKED, morelz, Vegi   |
|           59 |     5267 | 2024-02-29 | Sashi Esport              | L   | 0.597      | -            | -                | -                | -         |    -7.17 | bnox, maaryy, mASKED, morelz, Vegi   |
|           58 |     5294 | 2024-02-29 | ENCE Academy              | W   | 0.595      | -            | -                | -                | -         |     6.23 | bnox, maaryy, mASKED, morelz, Vegi   |
|           57 |     5307 | 2024-02-28 | RUBY                      | W   | 0.591      | -            | -                | -                | -         |     8.81 | bnox, maaryy, mASKED, morelz, Vegi   |
|           56 |     5334 | 2024-02-28 | Team Secret               | L   | 0.589      | -            | -                | -                | -         |   -15.82 | bnox, maaryy, mASKED, morelz, Vegi   |
|           55 |     5341 | 2024-02-28 | Dynamo Eclot              | L   | 0.588      | -            | -                | -                | -         |    -6.29 | bnox, maaryy, mASKED, morelz, Vegi   |
|           54 |     5384 | 2024-02-27 | Sprout                    | W   | 0.582      | -            | -                | -                | -         |     2.73 | bnox, maaryy, mASKED, morelz, Vegi   |
|           53 |     5425 | 2024-02-26 | Reason Gaming             | W   | 0.575      | -            | -                | -                | -         |     4.58 | bnox, maaryy, mASKED, morelz, Vegi   |
|           52 |     5451 | 2024-02-25 | Verdant                   | W   | 0.570      | -            | -                | -                | -         |     8.72 | bnox, maaryy, mASKED, morelz, Vegi   |
|           51 |     5559 | 2024-02-24 | Dynamo Eclot              | W   | 0.562      | -            | -                | -                | -         |    11.94 | bnox, maaryy, mASKED, morelz, Vegi   |
|           50 |     5653 | 2024-02-22 | ARCRED                    | L   | 0.551      | -            | -                | -                | -         |   -12.95 | bnox, maaryy, mASKED, morelz, Vegi   |
|           49 |     5661 | 2024-02-22 | The Chosen Few            | L   | 0.550      | -            | -                | -                | -         |   -13.34 | bnox, maaryy, mASKED, morelz, Vegi   |
|           48 |     5672 | 2024-02-22 | ex-Turów Zgorzelec Esport | W   | 0.548      | -            | -                | -                | -         |     4.08 | bnox, maaryy, mASKED, morelz, Vegi   |
|           47 |     5699 | 2024-02-21 | MOUZ NXT                  | W   | 0.544      | 0.371        | 0.157 (0.032)    | -                | -         |    11.68 | bnox, maaryy, mASKED, morelz, Vegi   |
|           46 |     5739 | 2024-02-21 | Dynamo Eclot              | L   | 0.542      | -            | -                | -                | -         |    -5.88 | bnox, maaryy, mASKED, morelz, Vegi   |
|           45 |     5769 | 2024-02-20 | GenOne                    | W   | 0.537      | -            | -                | -                | -         |     1.61 | bnox, maaryy, mASKED, morelz, Vegi   |
|           44 |     5786 | 2024-02-20 | Sangal Esports            | W   | 0.536      | 0.333        | 0.166 (0.030)    | -                | -         |     9.99 | bnox, maaryy, mASKED, morelz, Vegi   |
|           43 |     5848 | 2024-02-19 | Dynamo Eclot              | W   | 0.529      | -            | -                | -                | -         |    11.31 | bnox, maaryy, mASKED, morelz, Vegi   |
|           42 |     5956 | 2024-02-17 | Viperio                   | W   | 0.516      | -            | -                | -                | -         |     2.46 | bnox, maaryy, mASKED, morelz, Vegi   |
|           41 |     6001 | 2024-02-16 | Sashi Esport              | L   | 0.509      | -            | -                | -                | -         |    -5.34 | bnox, maaryy, mASKED, morelz, Vegi   |
|           40 |     6059 | 2024-02-15 | Sashi Esport              | W   | 0.502      | -            | -                | -                | -         |     1.91 | bnox, maaryy, mASKED, morelz, Vegi   |
|           39 |     6218 | 2024-02-12 | Sangal Esports            | W   | 0.482      | 0.333        | 0.166 (0.027)    | -                | -         |     9.41 | bnox, maaryy, mASKED, morelz, Vegi   |
|           38 |     6221 | 2024-02-12 | Lilmix                    | W   | 0.482      | -            | -                | -                | -         |     5.74 | bnox, maaryy, mASKED, morelz, Vegi   |
|           37 |     6366 | 2024-02-07 | Endpoint                  | L   | 0.449      | -            | -                | -                | -         |    -6.83 | bnox, maaryy, mASKED, morelz, Vegi   |
|           36 |     6473 | 2024-02-04 | Natus Vincere Junior      | L   | 0.429      | -            | -                | -                | -         |    -9.63 | bnox, maaryy, mASKED, morelz, Vegi   |
|           35 |     6712 | 2024-01-31 | Team Secret               | W   | 0.404      | -            | -                | -                | -         |     1.77 | bnox, maaryy, mASKED, morelz, Vegi   |
|           34 |     6754 | 2024-01-30 | RUBY                      | L   | 0.398      | -            | -                | -                | -         |    -6.84 | bnox, maaryy, mASKED, morelz, Vegi   |
|           33 |     6760 | 2024-01-30 | 3DMAX                     | W   | 0.397      | -            | -                | -                | -         |     6.33 | bnox, maaryy, mASKED, morelz, Vegi   |
|           32 |     6783 | 2024-01-29 | GODSENT                   | W   | 0.392      | -            | -                | -                | -         |     2.03 | bnox, maaryy, mASKED, morelz, Vegi   |
|           31 |     6817 | 2024-01-29 | RAVAGERS                  | W   | 0.392      | -            | -                | -                | -         |     0.55 | bnox, maaryy, mASKED, morelz, Vegi   |
|           30 |     6865 | 2024-01-28 | ex-Anonymo Esports        | L   | 0.384      | -            | -                | -                | -         |    -9.51 | bnox, maaryy, mASKED, morelz, Vegi   |
|           29 |     6871 | 2024-01-28 | showmakerz                | W   | 0.383      | -            | -                | -                | -         |     1.07 | bnox, maaryy, mASKED, morelz, Vegi   |
|           28 |     7037 | 2024-01-26 | Lausanne-Sport Esports    | W   | 0.370      | -            | -                | -                | -         |     2.67 | bnox, maaryy, mASKED, morelz, Vegi   |
|           27 |     7119 | 2024-01-24 | lajtbitexe                | W   | 0.357      | -            | -                | -                | -         |     1.47 | bnox, maaryy, mASKED, morelz, Vegi   |
|           26 |     7358 | 2024-01-20 | Gaimin Gladiators         | L   | 0.329      | -            | -                | -                | -         |    -1.46 | bnox, maaryy, mASKED, morelz, Vegi   |
|           25 |     7364 | 2024-01-20 | Astralis Talent           | L   | 0.328      | -            | -                | -                | -         |    -5.50 | bnox, maaryy, mASKED, morelz, Vegi   |
|           24 |     7403 | 2024-01-19 | JANO Esports              | W   | 0.324      | -            | -                | -                | -         |     0.83 | bnox, maaryy, mASKED, morelz, Vegi   |
|           23 |     7426 | 2024-01-19 | Aurora Young Blud         | W   | 0.322      | -            | -                | -                | -         |     3.04 | bnox, maaryy, mASKED, morelz, Vegi   |
|           22 |     7459 | 2024-01-18 | Zero Tenacity             | L   | 0.318      | -            | -                | -                | -         |    -3.57 | bnox, maaryy, mASKED, morelz, Vegi   |
|           21 |     7481 | 2024-01-18 | BIG                       | L   | 0.317      | -            | -                | -                | -         |    -0.65 | bnox, maaryy, mASKED, morelz, Vegi   |
|           20 |     7490 | 2024-01-18 | Team Spirit Academy       | W   | 0.316      | -            | -                | -                | -         |     2.26 | bnox, maaryy, mASKED, morelz, Vegi   |
|           19 |     7583 | 2024-01-17 | Astralis Talent           | L   | 0.309      | -            | -                | -                | -         |    -5.27 | bnox, maaryy, mASKED, morelz, Vegi   |
|           18 |     7756 | 2024-01-14 | Dynamo Eclot              | W   | 0.289      | -            | -                | -                | -         |     6.20 | bnox, maaryy, mASKED, morelz, Vegi   |
|           17 |     7777 | 2024-01-13 | ex-sYnck                  | W   | 0.285      | -            | -                | -                | -         |     1.89 | bnox, maaryy, mASKED, morelz, Vegi   |
|           16 |     7781 | 2024-01-13 | OG                        | L   | 0.284      | -            | -                | -                | -         |    -1.87 | bnox, maaryy, mASKED, morelz, Vegi   |
|           15 |     7784 | 2024-01-13 | Insilio                   | W   | 0.284      | -            | -                | -                | -         |     3.91 | bnox, maaryy, mASKED, morelz, Vegi   |
|           14 |     7787 | 2024-01-13 | Infinite Gaming           | W   | 0.283      | -            | -                | -                | -         |     0.69 | bnox, maaryy, mASKED, morelz, Vegi   |
|           13 |     7826 | 2024-01-12 | Clownfiesta               | W   | 0.279      | -            | -                | -                | -         |     0.40 | bnox, maaryy, mASKED, morelz, Vegi   |
|           12 |     7857 | 2024-01-12 | Lilmix                    | W   | 0.278      | -            | -                | -                | -         |     0.90 | bnox, maaryy, mASKED, morelz, Vegi   |
|           11 |     7873 | 2024-01-12 | Lilmix                    | W   | 0.276      | -            | -                | -                | -         |     0.90 | bnox, maaryy, mASKED, morelz, Vegi   |
|           10 |     7877 | 2024-01-12 | MOUZ NXT                  | L   | 0.275      | -            | -                | -                | -         |    -2.52 | bnox, maaryy, mASKED, morelz, Vegi   |
|            9 |     7948 | 2024-01-11 | Pera Esports              | L   | 0.270      | -            | -                | -                | -         |    -4.62 | bnox, maaryy, mASKED, morelz, Vegi   |
|            8 |     7955 | 2024-01-11 | Verdant                   | W   | 0.268      | -            | -                | -                | -         |     0.35 | bnox, maaryy, mASKED, morelz, Vegi   |
|            7 |     7991 | 2024-01-10 | ILLYRIANS                 | W   | 0.265      | -            | -                | -                | -         |     0.36 | bnox, maaryy, mASKED, morelz, Vegi   |
|            6 |     8014 | 2024-01-10 | ex-K10                    | W   | 0.265      | -            | -                | -                | -         |     3.07 | bnox, maaryy, mASKED, morelz, Vegi   |
|            5 |     8139 | 2024-01-09 | Astralis Talent           | W   | 0.256      | -            | -                | -                | -         |     3.73 | bnox, maaryy, mASKED, morelz, Vegi   |
|            4 |     8195 | 2024-01-07 | Lilmix                    | L   | 0.242      | -            | -                | -                | -         |    -6.90 | bnox, maaryy, mASKED, morelz, Vegi   |
|            3 |     8222 | 2024-01-05 | Passion UA                | L   | 0.229      | -            | -                | -                | -         |    -3.18 | bnox, maaryy, mASKED, morelz, Vegi   |
|            2 |     8594 | 2023-12-16 | IKLA                      | L   | 0.098      | -            | -                | -                | -         |    -2.79 | bnox, h4rn, imd, morelz, Vegi        |
|            1 |     8739 | 2023-12-15 | TSM                       | L   | 0.091      | -            | -                | -                | -         |    -2.46 | bnox, h4rn, imd, morelz, Vegi        |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($8,600.32)
- Divide that value by the 5th highest value among all rosters ($300,806.11)
- The final value (0.03) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-05-02 |      1.000 | $500.00        | $500.00         |
| 2024-04-25 |      0.968 | $3,000.00      | $2,903.33       |
| 2024-04-21 |      0.943 | $1,232.30      | $1,162.47       |
| 2024-03-25 |      0.764 | $1,250.00      | $954.51         |
| 2024-02-28 |      0.588 | $3,000.00      | $1,765.00       |
| 2024-02-21 |      0.542 | $1,500.00      | $812.50         |
| 2024-01-21 |      0.335 | $1,500.00      | $502.50         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
