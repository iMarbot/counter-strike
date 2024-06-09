### Roster Details<br />
Team Name: MOUZ NXT<br />
Roster: Burmylov, Chr1zN, Neityu, PR, sirah<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [56](../standings_global.md)<br />
Regional Rank: [39]( ../standings_europe.md)<br />
Final Rank Value:  1032.5<br />
<br />
Final Rank Value (1032.5) = Starting Rank Value (1124.8) + Head To Head Adjustments (-92.3)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.554[<sup>1</sup>](#table2)
- Bounty Collected: 0.482[<sup>2</sup>](#table1)
- Opponent Network: 0.390[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.357<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1124.8
- 400 + ( ( 0.357 - 0.000 ) / ( 0.787 - 0.000 ) ) * 1600 = 1124.8


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent                  | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                 |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|          116 |      135 | 2024-05-28 | RUBY                      | W   | 1.000      | -            | -                | -                | 0 (0.000) |    12.76 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|          115 |      220 | 2024-05-26 | 9Pandas                   | L   | 1.000      | -            | -                | -                | -         |   -11.09 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|          114 |      238 | 2024-05-26 | B8                        | W   | 1.000      | 0.435        | 0.168 (0.073)    | 0.963 (0.419)    | 0 (0.000) |    22.93 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|          113 |      324 | 2024-05-25 | 3DMAX                     | W   | 1.000      | 0.435        | 0.106 (0.046)    | -                | 0 (0.000) |    14.30 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|          112 |      376 | 2024-05-24 | Illuminar Gaming          | W   | 1.000      | -            | -                | -                | 0 (0.000) |     6.39 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|          111 |      424 | 2024-05-23 | Rare Atom                 | W   | 1.000      | -            | -                | -                | 0 (0.000) |    10.43 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|          110 |      516 | 2024-05-22 | Rhyno Esports             | L   | 1.000      | -            | -                | -                | -         |   -18.12 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|          109 |      624 | 2024-05-21 | DMS                       | L   | 1.000      | -            | -                | -                | -         |   -19.18 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|          108 |      687 | 2024-05-20 | Rustec                    | L   | 1.000      | -            | -                | -                | -         |   -23.30 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|          107 |      818 | 2024-05-19 | BLEED Esports             | L   | 1.000      | -            | -                | -                | -         |   -10.55 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|          106 |     1025 | 2024-05-17 | DMS                       | W   | 1.000      | 0.500        | -                | 0.754 (0.377)    | 0 (0.000) |    10.15 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|          105 |     1214 | 2024-05-15 | BLEED Esports             | L   | 1.000      | -            | -                | -                | -         |    -9.88 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|          104 |     1303 | 2024-05-14 | B8                        | L   | 1.000      | -            | -                | -                | -         |   -12.56 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|          103 |     1323 | 2024-05-13 | ex-Turów Zgorzelec Esport | W   | 1.000      | -            | -                | -                | 0 (0.000) |     5.86 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|          102 |     1347 | 2024-05-13 | Team Space                | W   | 1.000      | -            | -                | -                | 0 (0.000) |     7.57 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|          101 |     1409 | 2024-05-12 | B8                        | L   | 1.000      | -            | -                | -                | -         |   -14.19 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|          100 |     1426 | 2024-05-11 | Endpoint                  | W   | 1.000      | 0.435        | -                | 0.770 (0.335)    | 0 (0.000) |    12.40 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           99 |     1507 | 2024-05-10 | Aurora Gaming             | W   | 1.000      | 0.435        | 0.492 (0.214)    | -                | 0 (0.000) |    27.15 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           98 |     1579 | 2024-05-09 | Dynamo Eclot              | W   | 1.000      | 0.372        | -                | 0.940 (0.350)    | -         |    13.12 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           97 |     1583 | 2024-05-09 | ENTERPRISE esports        | L   | 1.000      | -            | -                | -                | -         |   -20.35 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           96 |     1700 | 2024-05-07 | HOTU                      | L   | 1.000      | -            | -                | -                | -         |   -23.07 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           95 |     1709 | 2024-05-07 | RUSH B                    | W   | 1.000      | -            | -                | -                | -         |     7.21 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           94 |     1740 | 2024-05-06 | los kogutos               | L   | 1.000      | -            | -                | -                | -         |   -22.16 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           93 |     1747 | 2024-05-06 | Nemiga Gaming             | W   | 1.000      | 0.372        | 0.358 (0.133)    | -                | -         |    21.92 | Chr1zN, Neityu, PR, sirah, TOBIZ       |
|           92 |     1810 | 2024-05-05 | GamerLegion Academy       | W   | 1.000      | -            | -                | -                | -         |     7.00 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           91 |     1827 | 2024-05-04 | ENTERPRISE esports        | L   | 1.000      | -            | -                | -                | -         |   -22.99 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           90 |     1906 | 2024-05-03 | Nemiga Gaming             | L   | 1.000      | -            | -                | -                | -         |    -9.94 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           89 |     1937 | 2024-05-02 | Endpoint                  | L   | 1.000      | -            | -                | -                | -         |   -19.45 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           88 |     1956 | 2024-05-02 | ALTERNATE aTTaX           | W   | 1.000      | 0.500        | -                | 0.735 (0.368)    | -         |    10.65 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           87 |     1966 | 2024-05-02 | 9Pandas                   | L   | 1.000      | -            | -                | -                | -         |   -17.15 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           86 |     2025 | 2024-05-01 | BLEED Esports             | W   | 1.000      | 0.500        | 0.248 (0.124)    | 0.714 (0.357)    | -         |    21.94 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           85 |     2051 | 2024-04-30 | Dynamo Eclot              | W   | 1.000      | 0.500        | 0.097 (0.048)    | 0.940 (0.470)    | -         |    11.59 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           84 |     2068 | 2024-04-30 | V1dar Gaming              | W   | 1.000      | -            | -                | -                | -         |     4.39 | Burmylov, Chr1zN, PR, sirah, TOBIZ     |
|           83 |     2089 | 2024-04-29 | Nemiga Gaming             | L   | 0.997      | -            | -                | -                | -         |   -10.90 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           82 |     2118 | 2024-04-29 | Grannys Knockers          | W   | 0.995      | -            | -                | -                | -         |     7.38 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           81 |     2207 | 2024-04-27 | Dynamo Eclot              | W   | 0.984      | 0.500        | 0.097 (0.048)    | 0.940 (0.463)    | -         |    11.25 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           80 |     2351 | 2024-04-25 | RUBY                      | W   | 0.970      | -            | -                | -                | -         |    11.40 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           79 |     2374 | 2024-04-25 | Insilio                   | L   | 0.968      | -            | -                | -                | -         |   -19.36 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           78 |     2426 | 2024-04-24 | PARIVISION                | L   | 0.963      | -            | -                | -                | -         |   -22.20 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           77 |     2513 | 2024-04-22 | EYEBALLERS                | W   | 0.949      | -            | -                | -                | -         |     8.25 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           76 |     2523 | 2024-04-22 | Nemiga Gaming             | L   | 0.948      | -            | -                | -                | -         |   -10.04 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           75 |     2553 | 2024-04-21 | ALTERNATE aTTaX           | W   | 0.943      | 0.500        | -                | 0.735 (0.347)    | -         |     7.93 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           74 |     2573 | 2024-04-21 | Dynamo Eclot              | L   | 0.942      | -            | -                | -                | -         |   -17.96 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           73 |     2637 | 2024-04-20 | BLEED Esports             | L   | 0.936      | -            | -                | -                | -         |    -9.98 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           72 |     2827 | 2024-04-18 | ENTERPRISE esports        | W   | 0.923      | 0.500        | -                | 0.898 (0.414)    | -         |     8.21 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           71 |     2842 | 2024-04-18 | ENCE Academy              | W   | 0.922      | -            | -                | -                | -         |     5.59 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           70 |     2940 | 2024-04-16 | JANO Esports              | W   | 0.914      | -            | -                | -                | -         |     3.80 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           69 |     2975 | 2024-04-16 | GamerLegion               | L   | 0.909      | -            | -                | -                | -         |    -9.46 | Anlelele, Burmylov, Neityu, PR, sirah  |
|           68 |     3016 | 2024-04-15 | JANO Esports              | W   | 0.903      | -            | -                | -                | -         |     3.40 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           67 |     3030 | 2024-04-15 | Alliance                  | W   | 0.901      | -            | -                | -                | -         |     6.45 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           66 |     3155 | 2024-04-12 | Permitta Esports          | L   | 0.882      | -            | -                | -                | -         |   -18.19 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           65 |     3330 | 2024-04-09 | Zero Tenacity             | W   | 0.863      | 0.371        | 0.147 (0.047)    | -                | -         |     9.31 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           64 |     3389 | 2024-04-08 | B8                        | W   | 0.856      | 0.384        | 0.168 (0.055)    | -                | -         |    15.41 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           63 |     3630 | 2024-04-03 | PARIVISION                | W   | 0.824      | -            | -                | -                | -         |     7.72 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           62 |     4446 | 2024-03-16 | Team Sampi                | L   | 0.702      | -            | -                | -                | -         |   -14.32 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           61 |     4494 | 2024-03-15 | Entropiq                  | W   | 0.696      | -            | -                | -                | -         |     2.76 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           60 |     4588 | 2024-03-13 | Permitta Esports          | L   | 0.685      | -            | -                | -                | -         |   -13.13 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           59 |     4626 | 2024-03-13 | Alliance                  | W   | 0.682      | -            | -                | -                | -         |     4.83 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           58 |     4680 | 2024-03-12 | AURA                      | W   | 0.677      | -            | -                | -                | -         |     1.98 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           57 |     4695 | 2024-03-12 | Team Sampi                | L   | 0.675      | -            | -                | -                | -         |   -14.43 | Burmylov, Chr1zN, Neityu, sirah, xReal |
|           56 |     4753 | 2024-03-11 | Passion UA                | W   | 0.669      | -            | -                | -                | -         |     6.27 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           55 |     4759 | 2024-03-11 | NOM Esports               | W   | 0.668      | -            | -                | -                | -         |     1.90 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           54 |     4774 | 2024-03-10 | V1dar Gaming              | W   | 0.664      | -            | -                | -                | -         |     2.22 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           53 |     4797 | 2024-03-10 | Passion UA                | L   | 0.663      | -            | -                | -                | -         |   -14.95 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           52 |     4802 | 2024-03-10 | ALTERNATE aTTaX           | W   | 0.662      | -            | -                | -                | -         |     5.99 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           51 |     4881 | 2024-03-08 | ex-K10                    | W   | 0.650      | -            | -                | -                | -         |     3.59 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           50 |     4934 | 2024-03-07 | INGLORIOUS                | L   | 0.644      | -            | -                | -                | -         |   -17.20 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           49 |     4960 | 2024-03-07 | NOM Esports               | W   | 0.642      | -            | -                | -                | -         |     1.42 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           48 |     5203 | 2024-03-04 | ex-Turów Zgorzelec Esport | W   | 0.622      | -            | -                | -                | -         |     2.92 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           47 |     5214 | 2024-03-03 | Viperio                   | W   | 0.618      | -            | -                | -                | -         |     1.47 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           46 |     5261 | 2024-03-03 | ex-Preasy Esport          | W   | 0.615      | -            | -                | -                | -         |     5.91 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           45 |     5345 | 2024-03-02 | kONO.ECF                  | W   | 0.609      | -            | -                | -                | -         |     5.58 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           44 |     5395 | 2024-03-01 | Natus Vincere Junior      | L   | 0.602      | -            | -                | -                | -         |   -16.00 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           43 |     5406 | 2024-02-29 | Sashi Esport              | L   | 0.598      | -            | -                | -                | -         |   -10.56 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           42 |     5534 | 2024-02-27 | Dynamo Eclot              | L   | 0.583      | -            | -                | -                | -         |   -10.02 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           41 |     5578 | 2024-02-26 | BLEED Esports             | W   | 0.576      | 0.384        | 0.248 (0.055)    | -                | -         |    11.08 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           40 |     5625 | 2024-02-25 | brazylijski luz           | W   | 0.568      | -            | -                | -                | -         |     2.42 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           39 |     5736 | 2024-02-24 | Sashi Esport              | W   | 0.562      | -            | -                | -                | -         |     8.49 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           38 |     5860 | 2024-02-21 | RUBY                      | W   | 0.544      | -            | -                | -                | -         |     4.80 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           37 |     5862 | 2024-02-21 | Permitta Esports          | L   | 0.544      | -            | -                | -                | -         |   -11.70 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           36 |     5905 | 2024-02-21 | Entropiq                  | W   | 0.542      | -            | -                | -                | -         |     1.57 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           35 |     5930 | 2024-02-20 | Verdant                   | W   | 0.537      | -            | -                | -                | -         |     5.91 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           34 |     6047 | 2024-02-18 | Passion UA                | W   | 0.524      | -            | -                | -                | -         |     4.80 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           33 |     6242 | 2024-02-15 | Dynamo Eclot              | W   | 0.502      | -            | -                | -                | -         |     7.79 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           32 |     6281 | 2024-02-14 | esmagaB                   | W   | 0.497      | -            | -                | -                | -         |     2.96 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           31 |     6398 | 2024-02-12 | AURA                      | W   | 0.484      | -            | -                | -                | -         |     1.09 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           30 |     6435 | 2024-02-11 | ex-K10                    | W   | 0.476      | -            | -                | -                | -         |     2.63 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           29 |     6603 | 2024-02-05 | LODIS                     | W   | 0.438      | -            | -                | -                | -         |     0.99 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           28 |     6681 | 2024-02-04 | Team Secret               | L   | 0.429      | -            | -                | -                | -         |   -12.62 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           27 |     6923 | 2024-01-31 | ENTERPRISE esports        | W   | 0.404      | -            | -                | -                | -         |     4.65 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           26 |     6945 | 2024-01-31 | Monte Gen                 | L   | 0.403      | -            | -                | -                | -         |   -10.76 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           25 |     6985 | 2024-01-30 | L&G                       | W   | 0.396      | -            | -                | -                | -         |     0.46 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           24 |     7216 | 2024-01-27 | TSM                       | L   | 0.375      | -            | -                | -                | -         |   -10.46 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           23 |     7426 | 2024-01-23 | SINNERS Esports           | L   | 0.349      | -            | -                | -                | -         |    -7.06 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           22 |     7454 | 2024-01-22 | Grannys Knockers          | W   | 0.344      | -            | -                | -                | -         |     1.55 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           21 |     7478 | 2024-01-22 | ILIN                      | W   | 0.344      | -            | -                | -                | -         |     0.41 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           20 |     7532 | 2024-01-21 | Astralis Talent           | W   | 0.335      | -            | -                | -                | -         |     2.80 | Chr1zN, kristou, Neityu, PR, sirah     |
|           19 |     7609 | 2024-01-20 | Monte Gen                 | W   | 0.328      | -            | -                | -                | -         |     1.45 | Chr1zN, kristou, Neityu, PR, sirah     |
|           18 |     7664 | 2024-01-19 | Astralis Talent           | W   | 0.322      | -            | -                | -                | -         |     2.71 | Chr1zN, kristou, Neityu, PR, sirah     |
|           17 |     7674 | 2024-01-19 | WOPA Esport               | W   | 0.322      | -            | -                | -                | -         |     1.50 | Chr1zN, kristou, Neityu, PR, sirah     |
|           16 |     7744 | 2024-01-18 | Passion UA                | W   | 0.315      | -            | -                | -                | -         |     3.49 | Chr1zN, kristou, Neityu, PR, sirah     |
|           15 |     7830 | 2024-01-17 | Natus Vincere Junior      | W   | 0.309      | -            | -                | -                | -         |     1.33 | Chr1zN, kristou, Neityu, PR, sirah     |
|           14 |     7840 | 2024-01-17 | Aurora Young Blud         | W   | 0.308      | -            | -                | -                | -         |     1.46 | Chr1zN, kristou, Neityu, PR, sirah     |
|           13 |     7963 | 2024-01-15 | lajtbitexe                | W   | 0.296      | -            | -                | -                | -         |     0.60 | Chr1zN, kristou, Neityu, PR, sirah     |
|           12 |     8047 | 2024-01-13 | The Prodigies             | L   | 0.283      | -            | -                | -                | -         |    -8.48 | Chr1zN, kristou, Neityu, PR, sirah     |
|           11 |     8130 | 2024-01-12 | Permitta Esports          | W   | 0.275      | -            | -                | -                | -         |     2.53 | Chr1zN, kristou, Neityu, PR, sirah     |
|           10 |     8286 | 2024-01-10 | Astralis Talent           | W   | 0.262      | -            | -                | -                | -         |     2.09 | Chr1zN, kristou, Neityu, PR, sirah     |
|            9 |     8396 | 2024-01-09 | Passion UA                | L   | 0.255      | -            | -                | -                | -         |    -5.15 | Chr1zN, kristou, Neityu, PR, sirah     |
|            8 |     8470 | 2024-01-06 | WOPA Esport               | W   | 0.235      | -            | -                | -                | -         |     1.17 | Chr1zN, kristou, Neityu, PR, sirah     |
|            7 |     8482 | 2024-01-05 | Astralis Talent           | W   | 0.228      | -            | -                | -                | -         |     1.82 | Chr1zN, kristou, Neityu, PR, sirah     |
|            6 |     8488 | 2024-01-04 | Betera Esports            | L   | 0.223      | -            | -                | -                | -         |    -6.00 | Chr1zN, kristou, Neityu, PR, sirah     |
|            5 |     8651 | 2023-12-19 | Nexus Gaming              | W   | 0.117      | -            | -                | -                | -         |     0.85 | Chr1zN, kristou, Neityu, PR, sirah     |
|            4 |     8669 | 2023-12-18 | Nexus Gaming              | L   | 0.110      | -            | -                | -                | -         |    -2.68 | Chr1zN, kristou, Neityu, PR, sirah     |
|            3 |     9424 | 2023-12-07 | Zero Tenacity             | L   | 0.038      | -            | -                | -                | -         |    -0.64 | Chr1zN, Neityu, Nexius, PR, sirah      |
|            2 |     9491 | 2023-12-06 | Endpoint                  | L   | 0.031      | -            | -                | -                | -         |    -0.71 | Chr1zN, Neityu, Nexius, PR, sirah      |
|            1 |     9515 | 2023-12-06 | Nemiga Gaming             | W   | 0.029      | -            | -                | -                | -         |     0.63 | Chr1zN, Neityu, Nexius, PR, sirah      |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($47,263.75)
- Divide that value by the 5th highest value among all rosters ($300,806.11)
- The final value (0.16) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-05-26 |      1.000 | $10,000.00     | $10,000.00      |
| 2024-05-18 |      1.000 | $500.00        | $500.00         |
| 2024-05-12 |      1.000 | $5,000.00      | $5,000.00       |
| 2024-05-03 |      1.000 | $25,000.00     | $25,000.00      |
| 2024-03-18 |      0.715 | $1,000.00      | $715.00         |
| 2024-03-11 |      0.669 | $3,500.00      | $2,342.08       |
| 2024-02-28 |      0.588 | $1,500.00      | $882.50         |
| 2024-01-21 |      0.335 | $5,000.00      | $1,675.00       |
| 2024-01-20 |      0.328 | $3,500.00      | $1,149.17       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
