### Roster Details<br />
Team Name: MOUZ NXT<br />
Roster: Burmylov, Chr1zN, Neityu, PR, sirah<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [50](../standings_global.md)<br />
Regional Rank: [35]( ../standings_europe.md)<br />
Final Rank Value:  1025.9<br />
<br />
Final Rank Value (1025.9) = Starting Rank Value (1096.3) + Head To Head Adjustments (-70.5)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.600[<sup>1</sup>](#table2)
- Bounty Collected: 0.457[<sup>2</sup>](#table1)
- Opponent Network: 0.347[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.351<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1096.3
- 400 + ( ( 0.351 - 0.000 ) / ( 0.806 - 0.000 ) ) * 1600 = 1096.3


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent                 | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                 |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|          102 |       33 | 2024-05-05 | GamerLegion Academy      | W   | 1.000      | -            | -                | -                | 0 (0.000) |     9.44 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|          101 |       44 | 2024-05-04 | ENTERPRISE esports       | L   | 1.000      | -            | -                | -                | -         |   -22.15 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|          100 |      109 | 2024-05-03 | Nemiga Gaming            | L   | 1.000      | -            | -                | -                | -         |    -7.19 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           99 |      138 | 2024-05-02 | Endpoint                 | L   | 1.000      | -            | -                | -                | -         |   -20.17 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           98 |      154 | 2024-05-02 | ALTERNATE aTTaX          | W   | 1.000      | 0.500        | 0.110 (0.055)    | 0.723 (0.362)    | 0 (0.000) |    10.71 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           97 |      164 | 2024-05-02 | 9Pandas                  | L   | 1.000      | -            | -                | -                | -         |   -16.92 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           96 |      213 | 2024-05-01 | BLEED Esports            | W   | 1.000      | 0.500        | 0.284 (0.142)    | 0.644 (0.322)    | 0 (0.000) |    20.77 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           95 |      233 | 2024-04-30 | Dynamo Eclot             | W   | 1.000      | 0.500        | 0.189 (0.094)    | 0.953 (0.477)    | 0 (0.000) |    13.12 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           94 |      247 | 2024-04-30 | V1dar Gaming             | W   | 1.000      | -            | -                | -                | 0 (0.000) |     3.56 | Burmylov, Chr1zN, PR, sirah, TOBIZ     |
|           93 |      265 | 2024-04-29 | Nemiga Gaming            | L   | 1.000      | -            | -                | -                | -         |    -7.66 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           92 |      356 | 2024-04-27 | Dynamo Eclot             | W   | 1.000      | 0.500        | 0.189 (0.094)    | 0.953 (0.477)    | 0 (0.000) |    13.24 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           91 |      473 | 2024-04-25 | RUBY                     | W   | 1.000      | 0.371        | -                | 0.882 (0.327)    | 0 (0.000) |    13.34 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           90 |      495 | 2024-04-25 | Insilio                  | L   | 1.000      | -            | -                | -                | -         |   -19.27 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           89 |      539 | 2024-04-24 | PARIVISION               | L   | 1.000      | -            | -                | -                | -         |   -23.28 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           88 |      614 | 2024-04-22 | EYEBALLERS               | W   | 1.000      | -            | -                | -                | 0 (0.000) |    10.21 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           87 |      623 | 2024-04-22 | Nemiga Gaming            | L   | 1.000      | -            | -                | -                | -         |    -8.30 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           86 |      644 | 2024-04-21 | ALTERNATE aTTaX          | W   | 1.000      | 0.500        | 0.110 (0.055)    | 0.723 (0.362)    | 0 (0.000) |     9.41 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           85 |      662 | 2024-04-21 | Dynamo Eclot             | L   | 1.000      | -            | -                | -                | -         |   -17.61 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           84 |      716 | 2024-04-20 | BLEED Esports            | L   | 1.000      | -            | -                | -                | -         |   -13.63 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           83 |      885 | 2024-04-18 | ENTERPRISE esports       | W   | 1.000      | -            | -                | -                | 0 (0.000) |    10.14 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           82 |      898 | 2024-04-18 | ENCE Academy             | W   | 1.000      | -            | -                | -                | -         |     6.85 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           81 |      982 | 2024-04-17 | JANO Esports             | W   | 1.000      | -            | -                | -                | -         |     4.64 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           80 |     1009 | 2024-04-16 | GamerLegion              | L   | 1.000      | -            | -                | -                | -         |    -3.05 | Anlelele, Burmylov, Neityu, PR, sirah  |
|           79 |     1045 | 2024-04-15 | JANO Esports             | W   | 1.000      | -            | -                | -                | -         |     4.34 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           78 |     1058 | 2024-04-15 | Alliance                 | W   | 1.000      | 0.384        | -                | 0.729 (0.280)    | -         |     8.13 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           77 |     1152 | 2024-04-12 | Permitta Esports         | L   | 1.000      | -            | -                | -                | -         |   -20.93 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           76 |     1293 | 2024-04-09 | Zero Tenacity            | W   | 1.000      | 0.371        | 0.095 (0.035)    | 1.000 (0.371)    | -         |    10.09 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           75 |     1527 | 2024-04-03 | PARIVISION               | W   | 0.985      | -            | -                | -                | -         |     8.71 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           74 |     2186 | 2024-03-16 | Team Sampi               | L   | 0.863      | -            | -                | -                | -         |   -15.39 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           73 |     2224 | 2024-03-15 | Entropiq                 | W   | 0.857      | -            | -                | -                | -         |     5.43 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           72 |     2305 | 2024-03-13 | Permitta Esports         | L   | 0.846      | -            | -                | -                | -         |   -15.13 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           71 |     2336 | 2024-03-13 | Alliance                 | W   | 0.843      | -            | -                | -                | -         |     7.09 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           70 |     2375 | 2024-03-12 | GODSENT                  | W   | 0.838      | -            | -                | -                | -         |     4.40 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           69 |     2388 | 2024-03-12 | Team Sampi               | L   | 0.836      | -            | -                | -                | -         |   -15.50 | Burmylov, Chr1zN, Neityu, sirah, xReal |
|           68 |     2434 | 2024-03-11 | Passion UA               | W   | 0.830      | 0.303        | -                | 0.980 (0.246)    | -         |     8.41 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           67 |     2440 | 2024-03-11 | NOM Esports              | W   | 0.829      | -            | -                | -                | -         |     3.51 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           66 |     2449 | 2024-03-10 | V1dar Gaming             | W   | 0.825      | -            | -                | -                | -         |     2.52 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           65 |     2469 | 2024-03-10 | Passion UA               | L   | 0.824      | -            | -                | -                | -         |   -17.87 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           64 |     2474 | 2024-03-10 | ALTERNATE aTTaX          | W   | 0.823      | 0.384        | 0.110 (0.035)    | -                | -         |     8.04 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           63 |     2532 | 2024-03-08 | K10                      | W   | 0.811      | -            | -                | -                | -         |     5.45 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           62 |     2569 | 2024-03-07 | INGLORIOUS               | L   | 0.805      | -            | -                | -                | -         |   -19.96 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           61 |     2587 | 2024-03-07 | NOM Esports              | W   | 0.803      | -            | -                | -                | -         |     2.63 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           60 |     2775 | 2024-03-04 | Turów Zgorzelec Esport   | W   | 0.783      | -            | -                | -                | -         |     4.78 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           59 |     2785 | 2024-03-03 | Viperio                  | W   | 0.779      | -            | -                | -                | -         |     2.29 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           58 |     2821 | 2024-03-03 | Grannys Knockers         | W   | 0.776      | -            | -                | -                | -         |     5.32 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           57 |     2928 | 2024-03-01 | Natus Vincere Junior     | L   | 0.763      | -            | -                | -                | -         |   -19.16 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           56 |     2938 | 2024-02-29 | Sashi Esport             | L   | 0.759      | -            | -                | -                | -         |   -13.38 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           55 |     3041 | 2024-02-27 | Dynamo Eclot             | L   | 0.744      | -            | -                | -                | -         |   -10.70 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           54 |     3113 | 2024-02-25 | Illuminar Gaming         | W   | 0.729      | -            | -                | -                | -         |     3.28 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           53 |     3187 | 2024-02-24 | Sashi Esport             | W   | 0.723      | 0.333        | 0.193 (0.046)    | -                | -         |    11.31 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           52 |     3293 | 2024-02-21 | RUBY                     | W   | 0.706      | -            | -                | -                | -         |     6.22 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           51 |     3295 | 2024-02-21 | Permitta Esports         | L   | 0.705      | -            | -                | -                | -         |   -14.29 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           50 |     3329 | 2024-02-21 | Entropiq                 | W   | 0.703      | -            | -                | -                | -         |     3.77 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           49 |     3351 | 2024-02-20 | Verdant                  | W   | 0.698      | -            | -                | -                | -         |     8.00 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           48 |     3447 | 2024-02-18 | Passion UA               | W   | 0.685      | 0.371        | -                | 0.980 (0.249)    | -         |     6.01 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           47 |     3601 | 2024-02-15 | Dynamo Eclot             | W   | 0.663      | 0.333        | 0.189 (0.042)    | -                | -         |    12.32 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           46 |     3628 | 2024-02-14 | EsmagaB                  | W   | 0.658      | -            | -                | -                | -         |     4.50 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           45 |     3729 | 2024-02-12 | GODSENT                  | W   | 0.645      | -            | -                | -                | -         |     3.60 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           44 |     3758 | 2024-02-11 | K10                      | W   | 0.637      | -            | -                | -                | -         |     4.61 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           43 |     3880 | 2024-02-05 | LODIS                    | W   | 0.599      | -            | -                | -                | -         |     1.55 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           42 |     3937 | 2024-02-04 | Team Secret              | L   | 0.590      | -            | -                | -                | -         |   -16.97 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           41 |     4122 | 2024-01-31 | Monte Gen                | L   | 0.564      | -            | -                | -                | -         |   -14.27 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           40 |     4152 | 2024-01-30 | L&G                      | W   | 0.557      | -            | -                | -                | -         |     0.79 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           39 |     4436 | 2024-01-23 | SINNERS Esports          | L   | 0.510      | -            | -                | -                | -         |   -10.46 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           38 |     4458 | 2024-01-22 | Grindas                  | W   | 0.506      | -            | -                | -                | -         |     1.50 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           37 |     4476 | 2024-01-22 | ILIN                     | W   | 0.505      | -            | -                | -                | -         |     0.77 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           36 |     4514 | 2024-01-21 | Astralis Talent          | W   | 0.496      | -            | -                | -                | -         |     5.30 | Chr1zN, kristou, Neityu, PR, sirah     |
|           35 |     4570 | 2024-01-20 | Monte Gen                | W   | 0.489      | -            | -                | -                | -         |     2.90 | Chr1zN, kristou, Neityu, PR, sirah     |
|           34 |     4612 | 2024-01-19 | Astralis Talent          | W   | 0.483      | -            | -                | -                | -         |     5.27 | Chr1zN, kristou, Neityu, PR, sirah     |
|           33 |     4619 | 2024-01-19 | WOPA Esport              | W   | 0.483      | -            | -                | -                | -         |     2.04 | Chr1zN, kristou, Neityu, PR, sirah     |
|           32 |     4679 | 2024-01-18 | Passion UA               | W   | 0.476      | -            | -                | -                | -         |     5.26 | Chr1zN, kristou, Neityu, PR, sirah     |
|           31 |     4750 | 2024-01-17 | Natus Vincere Junior     | W   | 0.471      | -            | -                | -                | -         |     2.78 | Chr1zN, kristou, Neityu, PR, sirah     |
|           30 |     4757 | 2024-01-17 | Aurora Young Blud        | W   | 0.469      | -            | -                | -                | -         |     3.01 | Chr1zN, kristou, Neityu, PR, sirah     |
|           29 |     4894 | 2024-01-13 | The Prodigies            | L   | 0.444      | -            | -                | -                | -         |   -12.98 | Chr1zN, kristou, Neityu, PR, sirah     |
|           28 |     4953 | 2024-01-12 | Permitta Esports         | W   | 0.436      | -            | -                | -                | -         |     5.08 | Chr1zN, kristou, Neityu, PR, sirah     |
|           27 |     5062 | 2024-01-10 | Astralis Talent          | W   | 0.423      | -            | -                | -                | -         |     4.45 | Chr1zN, kristou, Neityu, PR, sirah     |
|           26 |     5130 | 2024-01-09 | Passion UA               | L   | 0.416      | -            | -                | -                | -         |    -8.39 | Chr1zN, kristou, Neityu, PR, sirah     |
|           25 |     5182 | 2024-01-06 | WOPA Esport              | W   | 0.396      | -            | -                | -                | -         |     1.81 | Chr1zN, kristou, Neityu, PR, sirah     |
|           24 |     5192 | 2024-01-05 | Astralis Talent          | W   | 0.389      | -            | -                | -                | -         |     4.14 | Chr1zN, kristou, Neityu, PR, sirah     |
|           23 |     5312 | 2023-12-19 | Nexus Gaming             | W   | 0.279      | -            | -                | -                | -         |     2.59 | Chr1zN, kristou, Neityu, PR, sirah     |
|           22 |     5327 | 2023-12-18 | Nexus Gaming             | L   | 0.271      | -            | -                | -                | -         |    -6.06 | Chr1zN, kristou, Neityu, PR, sirah     |
|           21 |     5874 | 2023-12-07 | Zero Tenacity            | L   | 0.199      | -            | -                | -                | -         |    -4.22 | Chr1zN, Neityu, Nexius, PR, sirah      |
|           20 |     5921 | 2023-12-06 | Endpoint                 | L   | 0.192      | -            | -                | -                | -         |    -4.82 | Chr1zN, Neityu, Nexius, PR, sirah      |
|           19 |     5942 | 2023-12-06 | Nemiga Gaming            | W   | 0.191      | 0.371        | 0.680 (0.048)    | -                | -         |     4.68 | Chr1zN, Neityu, Nexius, PR, sirah      |
|           18 |     6206 | 2023-11-30 | BAKS Esports             | W   | 0.152      | -            | -                | -                | -         |     0.39 | Chr1zN, Neityu, Nexius, PR, sirah      |
|           17 |     6253 | 2023-11-29 | Lajtbitexe               | L   | 0.145      | -            | -                | -                | -         |    -4.36 | Chr1zN, Neityu, Nexius, PR, sirah      |
|           16 |     6262 | 2023-11-29 | Gaimin Gladiators        | W   | 0.145      | -            | -                | -                | -         |     4.02 | Chr1zN, Neityu, Nexius, PR, sirah      |
|           15 |     6330 | 2023-11-28 | Ex-Anonymo Esports       | W   | 0.137      | -            | -                | -                | -         |     0.61 | Chr1zN, Neityu, Nexius, PR, sirah      |
|           14 |     6358 | 2023-11-27 | EHawks                   | L   | 0.132      | -            | -                | -                | -         |    -3.98 | Chr1zN, Neityu, Nexius, PR, sirah      |
|           13 |     6617 | 2023-11-20 | BLESSED (Ukrainian team) | W   | 0.086      | -            | -                | -                | -         |     0.53 | Chr1zN, Neityu, Nexius, PR, sirah      |
|           12 |     6733 | 2023-11-18 | Sashi Esport             | L   | 0.071      | -            | -                | -                | -         |    -1.12 | Chr1zN, Neityu, Nexius, PR, sirah      |
|           11 |     6836 | 2023-11-16 | ARCRED                   | W   | 0.057      | -            | -                | -                | -         |     0.33 | Chr1zN, Neityu, Nexius, PR, sirah      |
|           10 |     6933 | 2023-11-14 | Team Spirit Academy      | W   | 0.044      | -            | -                | -                | -         |     0.22 | Chr1zN, Neityu, Nexius, PR, sirah      |
|            9 |     6940 | 2023-11-14 | Into The Breach          | L   | 0.043      | -            | -                | -                | -         |    -1.14 | Chr1zN, Neityu, Nexius, PR, sirah      |
|            8 |     6960 | 2023-11-13 | Verdant                  | W   | 0.039      | -            | -                | -                | -         |     0.46 | Chr1zN, Neityu, Nexius, PR, sirah      |
|            7 |     6988 | 2023-11-13 | Ex-Anonymo Esports       | L   | 0.036      | -            | -                | -                | -         |    -0.99 | Chr1zN, Neityu, Nexius, PR, sirah      |
|            6 |     7018 | 2023-11-12 | Team Sampi               | W   | 0.030      | -            | -                | -                | -         |     0.40 | Chr1zN, Neityu, Nexius, PR, sirah      |
|            5 |     7095 | 2023-11-10 | Metizport                | L   | 0.018      | -            | -                | -                | -         |    -0.35 | Chr1zN, Neityu, Nexius, PR, sirah      |
|            4 |     7137 | 2023-11-09 | Grindas                  | W   | 0.012      | -            | -                | -                | -         |     0.04 | Chr1zN, Neityu, Nexius, PR, sirah      |
|            3 |     7164 | 2023-11-08 | TY                       | W   | 0.006      | -            | -                | -                | -         |     0.02 | Chr1zN, Neityu, Nexius, PR, sirah      |
|            2 |     7192 | 2023-11-08 | SHIPACHI                 | W   | 0.005      | -            | -                | -                | -         |     0.01 | Chr1zN, Neityu, Nexius, PR, sirah      |
|            1 |     7214 | 2023-11-08 | 9Pandas                  | W   | 0.003      | -            | -                | -                | -         |     0.05 | Chr1zN, Neityu, Nexius, PR, sirah      |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($34,099.19)
- Divide that value by the 5th highest value among all rosters ($158,437.64)
- The final value (0.22) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-05-03 |      1.000 | $25,000.00     | $25,000.00      |
| 2024-03-18 |      0.876 | $1,000.00      | $876.06         |
| 2024-03-11 |      0.830 | $3,500.00      | $2,905.81       |
| 2024-02-28 |      0.749 | $1,500.00      | $1,124.10       |
| 2024-01-21 |      0.496 | $5,000.00      | $2,480.32       |
| 2024-01-20 |      0.489 | $3,500.00      | $1,712.89       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
