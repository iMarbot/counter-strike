### Roster Details<br />
Team Name: Zero Tenacity<br />
Roster: aVN, brutmonster, Cjoffo, nEMANHA, simke<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [55](../standings_global.md)<br />
Regional Rank: [40]( ../standings_europe.md)<br />
Final Rank Value:  992.0<br />
<br />
Final Rank Value (992.0) = Starting Rank Value (968.8) + Head To Head Adjustments (23.2)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.494[<sup>1</sup>](#table2)
- Bounty Collected: 0.394[<sup>2</sup>](#table1)
- Opponent Network: 0.259[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.287<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 968.8
- 400 + ( ( 0.287 - 0.000 ) / ( 0.806 - 0.000 ) ) * 1600 = 968.8


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent               | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                   |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|          105 |       98 | 2024-05-03 | EYEBALLERS             | L   | 1.000      | -            | -                | -                | -         |   -17.42 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|          104 |      123 | 2024-05-03 | Metizport              | L   | 1.000      | -            | -                | -                | -         |   -12.20 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|          103 |      152 | 2024-05-02 | EXO Clan               | W   | 1.000      | -            | -                | -                | 0 (0.000) |    11.08 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|          102 |      162 | 2024-05-02 | HAVU Gaming            | W   | 1.000      | -            | -                | -                | 0 (0.000) |     6.58 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|          101 |      217 | 2024-05-01 | KOI                    | W   | 1.000      | 0.435        | 0.066 (0.029)    | 0.537 (0.234)    | 0 (0.000) |    19.74 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|          100 |      255 | 2024-04-30 | B8                     | W   | 1.000      | 0.435        | 0.088 (0.038)    | 0.589 (0.256)    | 0 (0.000) |    16.35 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           99 |      287 | 2024-04-29 | PARIVISION             | L   | 1.000      | -            | -                | -                | -         |   -18.14 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           98 |      305 | 2024-04-28 | HOTU                   | L   | 1.000      | -            | -                | -                | -         |   -24.03 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           97 |      317 | 2024-04-28 | SINNERS Esports        | W   | 1.000      | 0.435        | 0.038 (0.016)    | 0.534 (0.232)    | 0 (0.000) |    13.14 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           96 |      351 | 2024-04-27 | 500                    | W   | 1.000      | -            | -                | -                | 0 (0.000) |    11.69 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           95 |      391 | 2024-04-27 | SINNERS Esports        | W   | 1.000      | 0.500        | 0.038 (0.019)    | 0.534 (0.267)    | 0 (0.000) |    14.87 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           94 |      448 | 2024-04-26 | Illuminar Gaming       | W   | 1.000      | 0.435        | -                | 0.433 (0.188)    | 0 (0.000) |    10.82 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           93 |      461 | 2024-04-25 | Astralis Talent        | W   | 1.000      | -            | -                | -                | 0 (0.000) |    11.46 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           92 |      488 | 2024-04-25 | EYEBALLERS             | L   | 1.000      | -            | -                | -                | -         |   -17.78 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           91 |      514 | 2024-04-24 | Team Space             | W   | 1.000      | -            | -                | -                | 0 (0.000) |     7.41 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           90 |      549 | 2024-04-24 | Guild Eagles           | L   | 1.000      | -            | -                | -                | -         |   -13.54 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           89 |      564 | 2024-04-23 | Verdant                | W   | 1.000      | 0.371        | -                | 0.662 (0.246)    | -         |    12.44 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           88 |      587 | 2024-04-23 | Nemiga Gaming          | L   | 1.000      | -            | -                | -                | -         |    -5.43 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           87 |      617 | 2024-04-22 | Nexus Gaming           | W   | 1.000      | 0.500        | -                | 0.772 (0.386)    | -         |    14.13 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           86 |      727 | 2024-04-20 | RUBY                   | W   | 1.000      | -            | -                | -                | -         |    17.38 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           85 |      806 | 2024-04-19 | PARIVISION             | W   | 1.000      | 0.500        | -                | 0.374 (0.187)    | -         |    12.23 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           84 |      846 | 2024-04-19 | ALTERNATE aTTaX        | W   | 1.000      | 0.143        | 0.110 (0.016)    | -                | -         |    15.72 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           83 |      930 | 2024-04-17 | Fnatic                 | L   | 1.000      | -            | -                | -                | -         |    -4.69 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           82 |      953 | 2024-04-17 | B8                     | W   | 1.000      | 0.500        | 0.088 (0.044)    | 0.589 (0.294)    | -         |    19.42 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           81 |      998 | 2024-04-16 | Sangal Esports         | L   | 1.000      | -            | -                | -                | -         |   -21.58 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           80 |     1042 | 2024-04-15 | ALTERNATE aTTaX        | W   | 1.000      | -            | -                | -                | -         |    17.56 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           79 |     1140 | 2024-04-12 | Aurora Young Blud      | W   | 1.000      | -            | -                | -                | -         |    11.03 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           78 |     1154 | 2024-04-12 | JANO Esports           | L   | 1.000      | -            | -                | -                | -         |   -22.34 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           77 |     1185 | 2024-04-11 | Alliance               | L   | 1.000      | -            | -                | -                | -         |   -17.70 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           76 |     1293 | 2024-04-09 | MOUZ NXT               | L   | 1.000      | -            | -                | -                | -         |   -10.09 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           75 |     1608 | 2024-04-01 | Nemiga Gaming          | L   | 0.970      | -            | -                | -                | -         |    -4.79 | aVN, brutmonster, Cjoffo, kdaN, simke    |
|           74 |     1805 | 2024-03-26 | Ninjas in Pyjamas      | L   | 0.932      | -            | -                | -                | -         |    -7.95 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           73 |     2452 | 2024-03-10 | CYBERSHOKE Esports     | L   | 0.825      | -            | -                | -                | -         |   -19.98 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           72 |     2468 | 2024-03-10 | Dynamo Eclot           | W   | 0.824      | 0.384        | 0.189 (0.060)    | 0.953 (0.302)    | -         |    19.01 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           71 |     2506 | 2024-03-09 | Sangal Esports         | W   | 0.817      | -            | -                | -                | -         |     6.21 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           70 |     2636 | 2024-03-06 | GODSENT                | W   | 0.797      | -            | -                | -                | -         |     8.04 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           69 |     2697 | 2024-03-05 | AMKAL ESPORTS          | L   | 0.792      | -            | -                | -                | -         |    -5.11 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           68 |     2786 | 2024-03-03 | Lilmix                 | W   | 0.779      | -            | -                | -                | -         |     3.79 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           67 |     2807 | 2024-03-03 | Nexus Gaming           | L   | 0.778      | -            | -                | -                | -         |   -12.53 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           66 |     2820 | 2024-03-03 | Team Secret            | W   | 0.776      | -            | -                | -                | -         |     4.86 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           65 |     2901 | 2024-03-02 | Team Secret            | W   | 0.770      | -            | -                | -                | -         |     4.68 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           64 |     2944 | 2024-02-29 | EsmagaB                | W   | 0.759      | -            | -                | -                | -         |     7.26 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           63 |     2968 | 2024-02-29 | Young Ninjas           | W   | 0.757      | 0.384        | 0.074 (0.022)    | -                | -         |    12.52 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           62 |     3002 | 2024-02-28 | Entropiq               | L   | 0.751      | -            | -                | -                | -         |   -15.06 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           61 |     3037 | 2024-02-27 | DMS                    | W   | 0.744      | -            | -                | -                | -         |     4.55 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           60 |     3246 | 2024-02-22 | NOM Esports            | W   | 0.712      | -            | -                | -                | -         |     3.54 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           59 |     3486 | 2024-02-17 | Eternal Fire Academy   | W   | 0.679      | -            | -                | -                | -         |     4.97 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           58 |     3498 | 2024-02-17 | Sashi Esport           | L   | 0.678      | -            | -                | -                | -         |    -6.39 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           57 |     3581 | 2024-02-15 | Team Secret            | L   | 0.665      | -            | -                | -                | -         |   -16.74 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           56 |     3593 | 2024-02-15 | Copenhagen Wolves      | W   | 0.664      | -            | -                | -                | -         |     3.28 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           55 |     3618 | 2024-02-14 | BAKS Esports           | W   | 0.659      | -            | -                | -                | -         |     3.51 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           54 |     3767 | 2024-02-10 | Team Sampi             | L   | 0.632      | -            | -                | -                | -         |    -8.23 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           53 |     3855 | 2024-02-06 | Ex-Hot Headed Gaming   | W   | 0.606      | -            | -                | -                | -         |     1.50 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           52 |     3927 | 2024-02-04 | 500                    | L   | 0.591      | -            | -                | -                | -         |   -12.16 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           51 |     3944 | 2024-02-03 | The Chosen Few         | W   | 0.586      | -            | -                | -                | -         |     5.58 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           50 |     4038 | 2024-02-02 | Natus Vincere Junior   | W   | 0.578      | -            | -                | -                | -         |     6.43 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           49 |     4049 | 2024-02-02 | Jake Bube              | W   | 0.577      | -            | -                | -                | -         |     1.58 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           48 |     4425 | 2024-01-23 | Rhyno Esports          | W   | 0.512      | -            | -                | -                | -         |     7.86 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           47 |     4564 | 2024-01-20 | 3DMAX                  | L   | 0.490      | -            | -                | -                | -         |    -7.24 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           46 |     4605 | 2024-01-19 | SAW                    | L   | 0.484      | -            | -                | -                | -         |    -0.73 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           45 |     4647 | 2024-01-18 | Permitta Esports       | W   | 0.479      | -            | -                | -                | -         |     8.89 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           44 |     4661 | 2024-01-18 | BetBoom Team           | L   | 0.478      | -            | -                | -                | -         |    -0.66 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           43 |     4678 | 2024-01-18 | Aurora Young Blud      | L   | 0.476      | -            | -                | -                | -         |    -9.66 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           42 |     4771 | 2024-01-16 | Passion UA             | W   | 0.467      | -            | -                | -                | -         |     8.51 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           41 |     4819 | 2024-01-16 | Dynamo Eclot           | W   | 0.463      | 0.333        | 0.189 (0.029)    | -                | -         |    11.36 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           40 |     4871 | 2024-01-14 | Astralis Talent        | L   | 0.449      | -            | -                | -                | -         |    -6.40 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           39 |     5011 | 2024-01-11 | Monte Gen              | L   | 0.430      | -            | -                | -                | -         |    -9.16 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           38 |     5032 | 2024-01-10 | Soda Gaming            | L   | 0.426      | -            | -                | -                | -         |    -9.87 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           37 |     5088 | 2024-01-09 | 9INE                   | L   | 0.418      | -            | -                | -                | -         |   -11.76 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           36 |     5101 | 2024-01-09 | The Prodigies          | W   | 0.418      | -            | -                | -                | -         |     1.63 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           35 |     5120 | 2024-01-09 | ILIN                   | W   | 0.418      | -            | -                | -                | -         |     1.23 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           34 |     5128 | 2024-01-09 | The Prodigies          | W   | 0.417      | -            | -                | -                | -         |     1.60 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           33 |     5154 | 2024-01-08 | Nexus Gaming           | W   | 0.410      | -            | -                | -                | -         |     5.70 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           32 |     5191 | 2024-01-05 | Turów Zgorzelec Esport | W   | 0.389      | -            | -                | -                | -         |     4.05 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           31 |     5199 | 2024-01-04 | The Prodigies          | L   | 0.383      | -            | -                | -                | -         |   -10.77 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           30 |     5618 | 2023-12-14 | The Witchers           | L   | 0.243      | -            | -                | -                | -         |    -5.57 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           29 |     5673 | 2023-12-12 | Sashi Esport           | L   | 0.231      | -            | -                | -                | -         |    -2.48 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           28 |     5831 | 2023-12-08 | ALTERNATE aTTaX        | L   | 0.206      | -            | -                | -                | -         |    -2.35 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           27 |     5841 | 2023-12-08 | Illuminar Gaming       | W   | 0.204      | -            | -                | -                | -         |     1.52 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           26 |     5874 | 2023-12-07 | MOUZ NXT               | W   | 0.199      | 0.371        | 0.215 (0.016)    | -                | -         |     4.22 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           25 |     5937 | 2023-12-06 | GenOne                 | W   | 0.191      | -            | -                | -                | -         |     0.81 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           24 |     5974 | 2023-12-05 | TSM                    | L   | 0.186      | -            | -                | -                | -         |    -4.69 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           23 |     6019 | 2023-12-04 | SAW                    | L   | 0.177      | -            | -                | -                | -         |    -0.29 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           22 |     6067 | 2023-12-03 | TSM                    | L   | 0.169      | -            | -                | -                | -         |    -4.31 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           21 |     6087 | 2023-12-02 | Bad News Kangaroos     | W   | 0.166      | -            | -                | -                | -         |     2.48 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           20 |     6207 | 2023-11-30 | BIG                    | L   | 0.151      | -            | -                | -                | -         |    -0.33 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           19 |     6248 | 2023-11-29 | Verdant                | L   | 0.146      | -            | -                | -                | -         |    -2.11 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           18 |     6363 | 2023-11-27 | BAKS Esports           | W   | 0.132      | -            | -                | -                | -         |     0.61 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           17 |     6381 | 2023-11-27 | Legacy                 | W   | 0.130      | -            | -                | -                | -         |     2.93 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           16 |     6385 | 2023-11-26 | Guild Eagles           | L   | 0.126      | -            | -                | -                | -         |    -1.66 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           15 |     6392 | 2023-11-26 | M1X                    | W   | 0.125      | -            | -                | -                | -         |     0.56 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           14 |     6418 | 2023-11-25 | Guild Eagles           | L   | 0.119      | -            | -                | -                | -         |    -1.58 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           13 |     6519 | 2023-11-23 | Amigosi                | W   | 0.105      | -            | -                | -                | -         |     0.19 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           12 |     6533 | 2023-11-23 | Lazer Cats             | W   | 0.103      | -            | -                | -                | -         |     0.41 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           11 |     6607 | 2023-11-21 | Pompa Team             | W   | 0.090      | -            | -                | -                | -         |     0.21 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           10 |     6615 | 2023-11-20 | M1X                    | W   | 0.086      | -            | -                | -                | -         |     0.37 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|            9 |     6642 | 2023-11-20 | Underrated             | W   | 0.085      | -            | -                | -                | -         |     0.17 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|            8 |     6782 | 2023-11-17 | ENCE Academy           | W   | 0.064      | -            | -                | -                | -         |     0.70 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|            7 |     6818 | 2023-11-16 | L&G                    | W   | 0.058      | -            | -                | -                | -         |     0.12 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|            6 |     6884 | 2023-11-15 | Los Alpacas            | L   | 0.052      | -            | -                | -                | -         |    -1.41 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|            5 |     6961 | 2023-11-13 | Lilmix                 | W   | 0.039      | -            | -                | -                | -         |     0.23 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|            4 |     7010 | 2023-11-12 | Sangal Esports         | L   | 0.031      | -            | -                | -                | -         |    -0.86 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|            3 |     7014 | 2023-11-12 | Astralis Talent        | W   | 0.030      | -            | -                | -                | -         |     0.49 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|            2 |     7127 | 2023-11-09 | FORZE Esports          | L   | 0.012      | -            | -                | -                | -         |    -0.28 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|            1 |     7213 | 2023-11-08 | Lazer Cats             | W   | 0.003      | -            | -                | -                | -         |     0.01 | aVN, brutmonster, Cjoffo, nEMANHA, simke |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($14,987.05)
- Divide that value by the 5th highest value among all rosters ($158,437.64)
- The final value (0.09) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-05-04 |      1.000 | $2,000.00      | $2,000.00       |
| 2024-04-24 |      1.000 | $12,500.00     | $12,500.00      |
| 2023-12-13 |      0.238 | $750.00        | $178.51         |
| 2023-11-23 |      0.103 | $3,000.00      | $308.54         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
