### Roster Details<br />
Team Name: MOUZ NXT<br />
Roster: Burmylov, Chr1zN, Neityu, PR, sirah<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [56](../standings_global.md)<br />
Regional Rank: [39]( ../standings_europe.md)<br />
Final Rank Value:  1024.7<br />
<br />
Final Rank Value (1024.7) = Starting Rank Value (1118.9) + Head To Head Adjustments (-94.2)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.554[<sup>1</sup>](#table2)
- Bounty Collected: 0.482[<sup>2</sup>](#table1)
- Opponent Network: 0.376[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.353<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1118.9
- 400 + ( ( 0.353 - 0.000 ) / ( 0.786 - 0.000 ) ) * 1600 = 1118.9


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
|          113 |      128 | 2024-05-28 | RUBY                      | W   | 1.000      | -            | -                | -                | 0 (0.000) |    12.96 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|          112 |      212 | 2024-05-26 | 9Pandas                   | L   | 1.000      | -            | -                | -                | -         |   -11.14 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|          111 |      230 | 2024-05-26 | B8                        | W   | 1.000      | 0.435        | 0.168 (0.073)    | 0.952 (0.414)    | 0 (0.000) |    23.32 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|          110 |      316 | 2024-05-25 | 3DMAX                     | W   | 1.000      | 0.435        | 0.106 (0.046)    | -                | 0 (0.000) |    14.12 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|          109 |      367 | 2024-05-24 | Illuminar Gaming          | W   | 1.000      | -            | -                | -                | 0 (0.000) |     6.57 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|          108 |      416 | 2024-05-23 | Rare Atom                 | W   | 1.000      | -            | -                | -                | 0 (0.000) |    10.69 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|          107 |      509 | 2024-05-22 | Rhyno Esports             | L   | 1.000      | -            | -                | -                | -         |   -18.21 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|          106 |      613 | 2024-05-21 | DMS                       | L   | 1.000      | -            | -                | -                | -         |   -19.09 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|          105 |      676 | 2024-05-20 | Rustec                    | L   | 1.000      | -            | -                | -                | -         |   -23.64 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|          104 |      806 | 2024-05-19 | BLEED Esports             | L   | 1.000      | -            | -                | -                | -         |   -10.19 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|          103 |     1013 | 2024-05-17 | DMS                       | W   | 1.000      | 0.500        | -                | 0.751 (0.375)    | 0 (0.000) |    10.22 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|          102 |     1204 | 2024-05-15 | BLEED Esports             | L   | 1.000      | -            | -                | -                | -         |    -9.48 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|          101 |     1292 | 2024-05-14 | B8                        | L   | 1.000      | -            | -                | -                | -         |   -11.84 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|          100 |     1335 | 2024-05-13 | Team Space                | W   | 1.000      | -            | -                | -                | 0 (0.000) |     7.67 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           99 |     1396 | 2024-05-12 | B8                        | L   | 1.000      | -            | -                | -                | -         |   -13.63 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           98 |     1413 | 2024-05-11 | Endpoint                  | W   | 1.000      | -            | -                | -                | 0 (0.000) |    11.66 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           97 |     1494 | 2024-05-10 | Aurora Gaming             | W   | 1.000      | 0.435        | 0.492 (0.214)    | -                | 0 (0.000) |    27.66 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           96 |     1563 | 2024-05-09 | Dynamo Eclot              | W   | 1.000      | 0.372        | -                | 0.936 (0.348)    | 0 (0.000) |    14.03 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           95 |     1567 | 2024-05-09 | ENTERPRISE esports        | L   | 1.000      | -            | -                | -                | -         |   -20.85 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           94 |     1681 | 2024-05-07 | HOTU                      | L   | 1.000      | -            | -                | -                | -         |   -23.22 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           93 |     1689 | 2024-05-07 | RUSH B                    | W   | 1.000      | -            | -                | -                | -         |     7.11 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           92 |     1718 | 2024-05-06 | los kogutos               | L   | 1.000      | -            | -                | -                | -         |   -21.65 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           91 |     1725 | 2024-05-06 | Nemiga Gaming             | W   | 1.000      | 0.372        | 0.366 (0.136)    | -                | -         |    22.09 | Chr1zN, Neityu, PR, sirah, TOBIZ       |
|           90 |     1787 | 2024-05-05 | GamerLegion Academy       | W   | 1.000      | -            | -                | -                | -         |     7.64 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           89 |     1804 | 2024-05-04 | ENTERPRISE esports        | L   | 1.000      | -            | -                | -                | -         |   -23.41 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           88 |     1881 | 2024-05-03 | Nemiga Gaming             | L   | 1.000      | -            | -                | -                | -         |    -9.73 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           87 |     1911 | 2024-05-02 | Endpoint                  | L   | 1.000      | -            | -                | -                | -         |   -20.32 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           86 |     1929 | 2024-05-02 | ALTERNATE aTTaX           | W   | 1.000      | 0.500        | -                | 0.679 (0.340)    | -         |    10.76 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           85 |     1939 | 2024-05-02 | 9Pandas                   | L   | 1.000      | -            | -                | -                | -         |   -17.47 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           84 |     1995 | 2024-05-01 | BLEED Esports             | W   | 1.000      | 0.500        | 0.248 (0.124)    | 0.677 (0.339)    | -         |    22.19 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           83 |     2020 | 2024-04-30 | Dynamo Eclot              | W   | 1.000      | 0.500        | 0.097 (0.048)    | 0.936 (0.468)    | -         |    12.55 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           82 |     2035 | 2024-04-30 | V1dar Gaming              | W   | 1.000      | -            | -                | -                | -         |     4.27 | Burmylov, Chr1zN, PR, sirah, TOBIZ     |
|           81 |     2055 | 2024-04-29 | Nemiga Gaming             | L   | 0.997      | -            | -                | -                | -         |   -10.67 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           80 |     2083 | 2024-04-29 | Grannys Knockers          | W   | 0.995      | -            | -                | -                | -         |     7.08 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           79 |     2172 | 2024-04-27 | Dynamo Eclot              | W   | 0.984      | 0.500        | 0.097 (0.048)    | 0.936 (0.460)    | -         |    12.33 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           78 |     2312 | 2024-04-25 | RUBY                      | W   | 0.970      | -            | -                | -                | -         |    11.55 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           77 |     2333 | 2024-04-25 | Insilio                   | L   | 0.968      | -            | -                | -                | -         |   -19.07 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           76 |     2382 | 2024-04-24 | PARIVISION                | L   | 0.963      | -            | -                | -                | -         |   -21.77 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           75 |     2461 | 2024-04-22 | EYEBALLERS                | W   | 0.949      | -            | -                | -                | -         |     9.15 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           74 |     2471 | 2024-04-22 | Nemiga Gaming             | L   | 0.948      | -            | -                | -                | -         |    -9.63 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           73 |     2500 | 2024-04-21 | ALTERNATE aTTaX           | W   | 0.943      | 0.500        | -                | 0.679 (0.320)    | -         |     8.36 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           72 |     2520 | 2024-04-21 | Dynamo Eclot              | L   | 0.942      | -            | -                | -                | -         |   -17.66 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           71 |     2583 | 2024-04-20 | BLEED Esports             | L   | 0.936      | -            | -                | -                | -         |    -9.44 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           70 |     2771 | 2024-04-18 | ENTERPRISE esports        | W   | 0.923      | 0.500        | -                | 0.809 (0.373)    | -         |     7.68 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           69 |     2786 | 2024-04-18 | ENCE Academy              | W   | 0.922      | -            | -                | -                | -         |     5.79 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           68 |     2882 | 2024-04-16 | JANO Esports              | W   | 0.914      | -            | -                | -                | -         |     3.97 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           67 |     2914 | 2024-04-16 | GamerLegion               | L   | 0.909      | -            | -                | -                | -         |    -9.01 | Anlelele, Burmylov, Neityu, PR, sirah  |
|           66 |     2952 | 2024-04-15 | JANO Esports              | W   | 0.903      | -            | -                | -                | -         |     3.58 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           65 |     2965 | 2024-04-15 | Alliance                  | W   | 0.901      | -            | -                | -                | -         |     6.79 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           64 |     3089 | 2024-04-12 | Permitta Esports          | L   | 0.882      | -            | -                | -                | -         |   -18.21 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           63 |     3251 | 2024-04-09 | Zero Tenacity             | W   | 0.863      | 0.371        | 0.147 (0.047)    | 1.000 (0.320)    | -         |    10.07 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           62 |     3308 | 2024-04-08 | B8                        | W   | 0.856      | 0.384        | 0.168 (0.055)    | -                | -         |    16.03 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           61 |     3543 | 2024-04-03 | PARIVISION                | W   | 0.824      | -            | -                | -                | -         |     8.35 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           60 |     4339 | 2024-03-16 | Team Sampi                | L   | 0.702      | -            | -                | -                | -         |   -14.04 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           59 |     4385 | 2024-03-15 | Entropiq                  | W   | 0.696      | -            | -                | -                | -         |     2.91 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           58 |     4474 | 2024-03-13 | Permitta Esports          | L   | 0.685      | -            | -                | -                | -         |   -13.19 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           57 |     4510 | 2024-03-13 | Alliance                  | W   | 0.682      | -            | -                | -                | -         |     5.15 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           56 |     4560 | 2024-03-12 | AURA                      | W   | 0.677      | -            | -                | -                | -         |     2.07 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           55 |     4574 | 2024-03-12 | Team Sampi                | L   | 0.675      | -            | -                | -                | -         |   -14.14 | Burmylov, Chr1zN, Neityu, sirah, xReal |
|           54 |     4630 | 2024-03-11 | Passion UA                | W   | 0.669      | -            | -                | -                | -         |     6.49 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           53 |     4636 | 2024-03-11 | NOM Esports               | W   | 0.668      | -            | -                | -                | -         |     2.03 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           52 |     4649 | 2024-03-10 | V1dar Gaming              | W   | 0.664      | -            | -                | -                | -         |     2.23 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           51 |     4672 | 2024-03-10 | Passion UA                | L   | 0.663      | -            | -                | -                | -         |   -14.73 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           50 |     4677 | 2024-03-10 | ALTERNATE aTTaX           | W   | 0.662      | -            | -                | -                | -         |     6.38 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           49 |     4754 | 2024-03-08 | ex-K10                    | W   | 0.650      | -            | -                | -                | -         |     3.72 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           48 |     4805 | 2024-03-07 | INGLORIOUS                | L   | 0.644      | -            | -                | -                | -         |   -17.05 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           47 |     4829 | 2024-03-07 | NOM Esports               | W   | 0.642      | -            | -                | -                | -         |     1.53 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           46 |     5057 | 2024-03-04 | ex-Turów Zgorzelec Esport | W   | 0.622      | -            | -                | -                | -         |     2.89 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           45 |     5068 | 2024-03-03 | Viperio                   | W   | 0.618      | -            | -                | -                | -         |     1.51 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           44 |     5113 | 2024-03-03 | ex-Preasy Esport          | W   | 0.615      | -            | -                | -                | -         |     6.17 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           43 |     5246 | 2024-03-01 | Natus Vincere Junior      | L   | 0.602      | -            | -                | -                | -         |   -15.88 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           42 |     5257 | 2024-02-29 | Sashi Esport              | L   | 0.598      | -            | -                | -                | -         |   -10.50 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           41 |     5380 | 2024-02-27 | Dynamo Eclot              | L   | 0.583      | -            | -                | -                | -         |    -9.93 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           40 |     5420 | 2024-02-26 | BLEED Esports             | W   | 0.576      | 0.384        | 0.248 (0.055)    | -                | -         |    11.23 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           39 |     5467 | 2024-02-25 | brazylijski luz           | W   | 0.568      | -            | -                | -                | -         |     2.46 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           38 |     5576 | 2024-02-24 | Sashi Esport              | W   | 0.562      | -            | -                | -                | -         |     8.84 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           37 |     5697 | 2024-02-21 | RUBY                      | W   | 0.544      | -            | -                | -                | -         |     4.98 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           36 |     5699 | 2024-02-21 | Permitta Esports          | L   | 0.544      | -            | -                | -                | -         |   -11.68 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           35 |     5738 | 2024-02-21 | Entropiq                  | W   | 0.542      | -            | -                | -                | -         |     1.65 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           34 |     5762 | 2024-02-20 | Verdant                   | W   | 0.537      | -            | -                | -                | -         |     6.08 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           33 |     5874 | 2024-02-18 | Passion UA                | W   | 0.524      | -            | -                | -                | -         |     4.86 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           32 |     6061 | 2024-02-15 | Dynamo Eclot              | W   | 0.502      | -            | -                | -                | -         |     7.96 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           31 |     6100 | 2024-02-14 | esmagaB                   | W   | 0.497      | -            | -                | -                | -         |     2.98 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           30 |     6211 | 2024-02-12 | AURA                      | W   | 0.484      | -            | -                | -                | -         |     1.12 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           29 |     6247 | 2024-02-11 | ex-K10                    | W   | 0.476      | -            | -                | -                | -         |     2.68 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           28 |     6405 | 2024-02-05 | LODIS                     | W   | 0.438      | -            | -                | -                | -         |     1.00 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           27 |     6478 | 2024-02-04 | Team Secret               | L   | 0.429      | -            | -                | -                | -         |   -12.58 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           26 |     6732 | 2024-01-31 | Monte Gen                 | L   | 0.403      | -            | -                | -                | -         |   -10.71 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           25 |     6769 | 2024-01-30 | L&G                       | W   | 0.396      | -            | -                | -                | -         |     0.46 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           24 |     6996 | 2024-01-27 | TSM                       | L   | 0.375      | -            | -                | -                | -         |   -10.52 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           23 |     7186 | 2024-01-23 | SINNERS Esports           | L   | 0.349      | -            | -                | -                | -         |    -7.30 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           22 |     7213 | 2024-01-22 | Grindas                   | W   | 0.344      | -            | -                | -                | -         |     0.31 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           21 |     7235 | 2024-01-22 | ILIN                      | W   | 0.344      | -            | -                | -                | -         |     0.41 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           20 |     7289 | 2024-01-21 | Astralis Talent           | W   | 0.335      | -            | -                | -                | -         |     2.84 | Chr1zN, kristou, Neityu, PR, sirah     |
|           19 |     7365 | 2024-01-20 | Monte Gen                 | W   | 0.328      | -            | -                | -                | -         |     1.48 | Chr1zN, kristou, Neityu, PR, sirah     |
|           18 |     7417 | 2024-01-19 | Astralis Talent           | W   | 0.322      | -            | -                | -                | -         |     2.75 | Chr1zN, kristou, Neityu, PR, sirah     |
|           17 |     7427 | 2024-01-19 | WOPA Esport               | W   | 0.322      | -            | -                | -                | -         |     1.53 | Chr1zN, kristou, Neityu, PR, sirah     |
|           16 |     7495 | 2024-01-18 | Passion UA                | W   | 0.315      | -            | -                | -                | -         |     3.45 | Chr1zN, kristou, Neityu, PR, sirah     |
|           15 |     7581 | 2024-01-17 | Natus Vincere Junior      | W   | 0.309      | -            | -                | -                | -         |     1.36 | Chr1zN, kristou, Neityu, PR, sirah     |
|           14 |     7591 | 2024-01-17 | Aurora Young Blud         | W   | 0.308      | -            | -                | -                | -         |     1.47 | Chr1zN, kristou, Neityu, PR, sirah     |
|           13 |     7712 | 2024-01-15 | lajtbitexe                | W   | 0.296      | -            | -                | -                | -         |     0.56 | Chr1zN, kristou, Neityu, PR, sirah     |
|           12 |     7794 | 2024-01-13 | The Prodigies             | L   | 0.283      | -            | -                | -                | -         |    -8.46 | Chr1zN, kristou, Neityu, PR, sirah     |
|           11 |     7877 | 2024-01-12 | Permitta Esports          | W   | 0.275      | -            | -                | -                | -         |     2.52 | Chr1zN, kristou, Neityu, PR, sirah     |
|           10 |     8032 | 2024-01-10 | Astralis Talent           | W   | 0.262      | -            | -                | -                | -         |     2.13 | Chr1zN, kristou, Neityu, PR, sirah     |
|            9 |     8142 | 2024-01-09 | Passion UA                | L   | 0.255      | -            | -                | -                | -         |    -5.19 | Chr1zN, kristou, Neityu, PR, sirah     |
|            8 |     8215 | 2024-01-06 | WOPA Esport               | W   | 0.235      | -            | -                | -                | -         |     1.19 | Chr1zN, kristou, Neityu, PR, sirah     |
|            7 |     8227 | 2024-01-05 | Astralis Talent           | W   | 0.228      | -            | -                | -                | -         |     1.85 | Chr1zN, kristou, Neityu, PR, sirah     |
|            6 |     8232 | 2024-01-04 | Betera Esports            | L   | 0.223      | -            | -                | -                | -         |    -5.98 | Chr1zN, kristou, Neityu, PR, sirah     |
|            5 |     8394 | 2023-12-19 | Nexus Gaming              | W   | 0.117      | -            | -                | -                | -         |     0.95 | Chr1zN, kristou, Neityu, PR, sirah     |
|            4 |     8412 | 2023-12-18 | Nexus Gaming              | L   | 0.110      | -            | -                | -                | -         |    -2.59 | Chr1zN, kristou, Neityu, PR, sirah     |
|            3 |     9151 | 2023-12-07 | Zero Tenacity             | L   | 0.038      | -            | -                | -                | -         |    -0.63 | Chr1zN, Neityu, Nexius, PR, sirah      |
|            2 |     9211 | 2023-12-06 | Endpoint                  | L   | 0.031      | -            | -                | -                | -         |    -0.71 | Chr1zN, Neityu, Nexius, PR, sirah      |
|            1 |     9234 | 2023-12-06 | Nemiga Gaming             | W   | 0.029      | -            | -                | -                | -         |     0.63 | Chr1zN, Neityu, Nexius, PR, sirah      |

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
