### Roster Details<br />
Team Name: Zero Tenacity<br />
Roster: aVN, brutmonster, Cjoffo, nEMANHA, simke<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [46](../standings_global.md)<br />
Regional Rank: [34]( ../standings_europe.md)<br />
Final Rank Value:  1077.9<br />
<br />
Final Rank Value (1077.9) = Starting Rank Value (1099.4) + Head To Head Adjustments (-21.5)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.545[<sup>1</sup>](#table2)
- Bounty Collected: 0.440[<sup>2</sup>](#table1)
- Opponent Network: 0.391[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.344<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1099.4
- 400 + ( ( 0.344 - 0.000 ) / ( 0.787 - 0.000 ) ) * 1600 = 1099.4


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent                  | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                   |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|          133 |       45 | 2024-05-29 | JANO Esports              | W   | 1.000      | -            | -                | -                | 0 (0.000) |     3.95 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|          132 |      234 | 2024-05-26 | RUBY                      | W   | 1.000      | -            | -                | -                | 0 (0.000) |    11.51 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|          131 |      268 | 2024-05-25 | ex-Guild Eagles           | W   | 1.000      | -            | -                | -                | 0 (0.000) |    11.92 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|          130 |      280 | 2024-05-25 | iNation                   | W   | 1.000      | -            | -                | -                | 0 (0.000) |     5.21 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|          129 |      317 | 2024-05-25 | Rhyno Esports             | W   | 1.000      | -            | -                | -                | 0 (0.000) |    10.42 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|          128 |      341 | 2024-05-24 | ex-Guild Eagles           | L   | 1.000      | -            | -                | -                | -         |   -19.57 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|          127 |      359 | 2024-05-24 | ILLYRIANS                 | W   | 1.000      | -            | -                | -                | 0 (0.000) |     5.43 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|          126 |      394 | 2024-05-23 | Permitta Esports          | L   | 1.000      | -            | -                | -                | -         |   -25.02 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|          125 |      399 | 2024-05-23 | ENTERPRISE esports        | W   | 1.000      | 0.372        | -                | 0.898 (0.334)    | 0 (0.000) |     7.86 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|          124 |      415 | 2024-05-23 | 3DMAX                     | L   | 1.000      | -            | -                | -                | -         |   -20.54 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|          123 |      427 | 2024-05-23 | brazylijski luz           | W   | 1.000      | -            | -                | -                | 0 (0.000) |     6.76 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|          122 |      458 | 2024-05-22 | 1win                      | W   | 1.000      | 0.372        | 0.050 (0.019)    | -                | 0 (0.000) |    13.95 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|          121 |      498 | 2024-05-22 | Sangal Esports            | L   | 1.000      | -            | -                | -                | -         |   -13.96 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|          120 |      528 | 2024-05-22 | Illuminar Gaming          | W   | 1.000      | -            | -                | -                | 0 (0.000) |     4.36 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|          119 |      607 | 2024-05-21 | BLEED Esports             | W   | 1.000      | 0.500        | 0.248 (0.124)    | 0.714 (0.357)    | -         |    20.36 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|          118 |      633 | 2024-05-21 | Verdant                   | W   | 1.000      | 0.435        | -                | 1.000 (0.435)    | -         |    11.97 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|          117 |      674 | 2024-05-20 | Metizport                 | W   | 1.000      | 0.500        | 0.088 (0.044)    | 0.698 (0.349)    | -         |    17.84 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|          116 |      714 | 2024-05-20 | GUN5 Esports              | W   | 1.000      | -            | -                | -                | -         |     7.12 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|          115 |      808 | 2024-05-19 | B8                        | W   | 1.000      | 0.500        | 0.168 (0.084)    | 0.963 (0.482)    | -         |    22.24 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|          114 |      968 | 2024-05-17 | PARIVISION                | L   | 1.000      | -            | -                | -                | -         |   -19.04 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|          113 |     1000 | 2024-05-17 | Endpoint                  | W   | 1.000      | 0.435        | -                | 0.770 (0.335)    | -         |    11.98 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|          112 |     1084 | 2024-05-16 | Team Spirit Academy       | L   | 1.000      | -            | -                | -                | -         |   -24.52 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|          111 |     1109 | 2024-05-16 | 1win                      | L   | 1.000      | -            | -                | -                | -         |   -17.06 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|          110 |     1117 | 2024-05-16 | kONO.ECF                  | W   | 1.000      | -            | -                | -                | -         |     9.60 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|          109 |     1196 | 2024-05-15 | 3DMAX                     | W   | 1.000      | 0.500        | 0.106 (0.053)    | -                | -         |    13.16 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|          108 |     1259 | 2024-05-14 | WOPA Esport               | L   | 1.000      | -            | -                | -                | -         |   -25.92 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|          107 |     1274 | 2024-05-14 | Lilmix                    | L   | 1.000      | -            | -                | -                | -         |   -25.36 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|          106 |     1335 | 2024-05-13 | EYEBALLERS                | W   | 1.000      | -            | -                | -                | -         |    10.42 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|          105 |     1403 | 2024-05-12 | Verdant                   | W   | 1.000      | -            | -                | -                | -         |     9.96 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|          104 |     1547 | 2024-05-10 | UNiTY esports             | W   | 1.000      | -            | -                | -                | -         |     8.63 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|          103 |     1582 | 2024-05-09 | Lausanne-Sport Esports    | W   | 1.000      | -            | -                | -                | -         |     6.01 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|          102 |     1592 | 2024-05-09 | 9Pandas                   | L   | 1.000      | -            | -                | -                | -         |   -13.96 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|          101 |     1645 | 2024-05-08 | Eternal Fire Academy      | W   | 1.000      | -            | -                | -                | -         |     1.85 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|          100 |     1653 | 2024-05-08 | Young Ninjas              | W   | 1.000      | 0.372        | 0.043 (0.016)    | -                | -         |     9.21 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           99 |     1749 | 2024-05-06 | Insilio                   | W   | 1.000      | -            | -                | -                | -         |    13.79 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           98 |     1763 | 2024-05-06 | Johnny Speeds             | W   | 1.000      | 0.333        | 0.056 (0.019)    | -                | -         |    16.17 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           97 |     1895 | 2024-05-03 | EYEBALLERS                | L   | 1.000      | -            | -                | -                | -         |   -18.89 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           96 |     1920 | 2024-05-03 | Metizport                 | L   | 1.000      | -            | -                | -                | -         |   -14.21 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           95 |     1954 | 2024-05-02 | EXO Clan                  | W   | 1.000      | -            | -                | -                | -         |    13.32 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           94 |     1964 | 2024-05-02 | HAVU Gaming               | W   | 1.000      | -            | -                | -                | -         |     5.01 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           93 |     2030 | 2024-05-01 | KOI                       | W   | 1.000      | -            | -                | -                | -         |    17.09 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           92 |     2062 | 2024-04-30 | Sangal Esports            | L   | 1.000      | -            | -                | -                | -         |   -13.29 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           91 |     2077 | 2024-04-30 | B8                        | W   | 1.000      | 0.435        | 0.168 (0.073)    | 0.963 (0.419)    | -         |    17.02 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           90 |     2097 | 2024-04-29 | ex-K10                    | W   | 0.997      | -            | -                | -                | -         |     6.75 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           89 |     2114 | 2024-04-29 | PARIVISION                | L   | 0.996      | -            | -                | -                | -         |   -17.33 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           88 |     2136 | 2024-04-28 | HOTU                      | L   | 0.990      | -            | -                | -                | -         |   -22.65 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           87 |     2155 | 2024-04-28 | SINNERS Esports           | W   | 0.989      | -            | -                | -                | -         |    13.40 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           86 |     2199 | 2024-04-27 | 500                       | W   | 0.984      | -            | -                | -                | -         |     8.59 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           85 |     2252 | 2024-04-27 | SINNERS Esports           | W   | 0.981      | -            | -                | -                | -         |    14.88 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           84 |     2322 | 2024-04-26 | Illuminar Gaming          | W   | 0.975      | -            | -                | -                | -         |     8.83 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           83 |     2336 | 2024-04-25 | Astralis Talent           | W   | 0.971      | -            | -                | -                | -         |    10.10 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           82 |     2366 | 2024-04-25 | EYEBALLERS                | L   | 0.969      | -            | -                | -                | -         |   -19.29 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           81 |     2398 | 2024-04-24 | Team Space                | W   | 0.964      | -            | -                | -                | -         |     7.96 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           80 |     2436 | 2024-04-24 | ex-Guild Eagles           | L   | 0.962      | -            | -                | -                | -         |   -14.86 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           79 |     2455 | 2024-04-23 | Verdant                   | W   | 0.957      | 0.372        | -                | 1.000 (0.356)    | -         |    10.24 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           78 |     2478 | 2024-04-23 | Nemiga Gaming             | L   | 0.956      | -            | -                | -                | -         |    -7.22 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           77 |     2498 | 2024-04-22 | Grannys Knockers          | W   | 0.950      | -            | -                | -                | -         |     8.13 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           76 |     2516 | 2024-04-22 | Nexus Gaming              | W   | 0.949      | 0.500        | -                | 0.857 (0.407)    | -         |    12.34 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           75 |     2648 | 2024-04-20 | RUBY                      | W   | 0.936      | -            | -                | -                | -         |    14.09 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           74 |     2737 | 2024-04-19 | PARIVISION                | W   | 0.931      | -            | -                | -                | -         |    11.11 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           73 |     2781 | 2024-04-19 | ALTERNATE aTTaX           | W   | 0.929      | -            | -                | -                | -         |    12.76 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           72 |     2851 | 2024-04-18 | B8                        | L   | 0.921      | -            | -                | -                | -         |   -10.57 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           71 |     2881 | 2024-04-17 | Fnatic                    | L   | 0.918      | -            | -                | -                | -         |    -7.57 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           70 |     2911 | 2024-04-17 | B8                        | W   | 0.916      | 0.500        | 0.168 (0.077)    | 0.963 (0.441)    | -         |    18.45 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           69 |     2962 | 2024-04-16 | Sangal Esports            | L   | 0.910      | -            | -                | -                | -         |   -12.00 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           68 |     3011 | 2024-04-15 | ALTERNATE aTTaX           | W   | 0.904      | -            | -                | -                | -         |    13.85 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           67 |     3142 | 2024-04-12 | Aurora Young Blud         | W   | 0.883      | -            | -                | -                | -         |     7.55 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           66 |     3157 | 2024-04-12 | JANO Esports              | L   | 0.881      | -            | -                | -                | -         |   -21.21 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           65 |     3199 | 2024-04-11 | Alliance                  | L   | 0.876      | -            | -                | -                | -         |   -17.38 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           64 |     3330 | 2024-04-09 | MOUZ NXT                  | L   | 0.863      | -            | -                | -                | -         |    -9.31 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           63 |     3439 | 2024-04-07 | ex-Preasy Esport          | L   | 0.848      | -            | -                | -                | -         |   -13.02 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           62 |     3725 | 2024-04-01 | Nemiga Gaming             | L   | 0.808      | -            | -                | -                | -         |    -6.82 | aVN, brutmonster, Cjoffo, kdaN, simke    |
|           61 |     3965 | 2024-03-26 | Ninjas in Pyjamas         | L   | 0.771      | -            | -                | -                | -         |    -9.62 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           60 |     4779 | 2024-03-10 | CYBERSHOKE Esports        | L   | 0.664      | -            | -                | -                | -         |   -18.70 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           59 |     4796 | 2024-03-10 | Dynamo Eclot              | W   | 0.663      | 0.384        | 0.097 (0.025)    | -                | -         |    12.50 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           58 |     4847 | 2024-03-09 | Sangal Esports            | W   | 0.656      | -            | -                | -                | -         |     9.91 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           57 |     5023 | 2024-03-06 | AURA                      | W   | 0.636      | -            | -                | -                | -         |     2.85 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           56 |     5103 | 2024-03-05 | AMKAL ESPORTS             | L   | 0.631      | -            | -                | -                | -         |    -5.72 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           55 |     5155 | 2024-03-04 | petardka                  | W   | 0.625      | -            | -                | -                | -         |     0.61 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           54 |     5215 | 2024-03-03 | Lilmix                    | W   | 0.618      | -            | -                | -                | -         |     4.32 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           53 |     5240 | 2024-03-03 | Nexus Gaming              | L   | 0.617      | -            | -                | -                | -         |   -12.46 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           52 |     5260 | 2024-03-03 | Team Secret               | W   | 0.615      | -            | -                | -                | -         |     2.27 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           51 |     5362 | 2024-03-02 | Team Secret               | W   | 0.609      | -            | -                | -                | -         |     2.29 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           50 |     5414 | 2024-02-29 | esmagaB                   | W   | 0.598      | -            | -                | -                | -         |     4.09 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           49 |     5440 | 2024-02-29 | Young Ninjas              | W   | 0.596      | -            | -                | -                | -         |     7.27 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           48 |     5487 | 2024-02-28 | Entropiq                  | L   | 0.589      | -            | -                | -                | -         |   -15.61 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           47 |     5529 | 2024-02-27 | DMS                       | W   | 0.583      | -            | -                | -                | -         |     3.19 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           46 |     5809 | 2024-02-22 | NOM Esports               | W   | 0.551      | -            | -                | -                | -         |     1.67 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           45 |     6104 | 2024-02-17 | Eternal Fire Academy      | W   | 0.518      | -            | -                | -                | -         |     1.86 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           44 |     6121 | 2024-02-17 | Sashi Esport              | L   | 0.517      | -            | -                | -                | -         |    -6.84 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           43 |     6218 | 2024-02-15 | Team Secret               | L   | 0.504      | -            | -                | -                | -         |   -14.09 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           42 |     6233 | 2024-02-15 | Copenhagen Wolves         | W   | 0.503      | -            | -                | -                | -         |     1.69 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           41 |     6270 | 2024-02-14 | BAKS Esports              | W   | 0.498      | -            | -                | -                | -         |     1.40 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           40 |     6450 | 2024-02-10 | Team Sampi                | L   | 0.471      | -            | -                | -                | -         |    -9.19 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           39 |     6568 | 2024-02-06 | ex-Hot Headed Gaming      | W   | 0.444      | -            | -                | -                | -         |     0.66 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           38 |     6671 | 2024-02-04 | 500                       | L   | 0.429      | -            | -                | -                | -         |   -10.86 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           37 |     6698 | 2024-02-03 | The Chosen Few            | W   | 0.425      | -            | -                | -                | -         |     2.08 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           36 |     6827 | 2024-02-02 | Natus Vincere Junior      | W   | 0.417      | -            | -                | -                | -         |     2.59 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           35 |     6840 | 2024-02-02 | Jake Bube                 | W   | 0.416      | -            | -                | -                | -         |     0.61 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           34 |     6876 | 2024-02-01 | ex-sYnck                  | L   | 0.411      | -            | -                | -                | -         |   -10.94 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           33 |     7410 | 2024-01-23 | Rhyno Esports             | W   | 0.351      | -            | -                | -                | -         |     5.18 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           32 |     7457 | 2024-01-22 | kONO.ECF                  | L   | 0.344      | -            | -                | -                | -         |    -8.03 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           31 |     7604 | 2024-01-20 | 3DMAX                     | L   | 0.329      | -            | -                | -                | -         |    -6.86 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           30 |     7659 | 2024-01-19 | SAW                       | L   | 0.323      | -            | -                | -                | -         |    -1.64 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           29 |     7707 | 2024-01-18 | Permitta Esports          | W   | 0.318      | -            | -                | -                | -         |     3.63 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           28 |     7728 | 2024-01-18 | BetBoom Team              | L   | 0.317      | -            | -                | -                | -         |    -1.13 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           27 |     7743 | 2024-01-18 | Aurora Young Blud         | L   | 0.315      | -            | -                | -                | -         |    -8.14 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           26 |     7861 | 2024-01-16 | Passion UA                | W   | 0.306      | -            | -                | -                | -         |     4.09 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           25 |     7869 | 2024-01-16 | samaloyod                 | W   | 0.305      | -            | -                | -                | -         |     0.49 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           24 |     7893 | 2024-01-16 | premghouls                | W   | 0.304      | -            | -                | -                | -         |     0.23 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           23 |     7910 | 2024-01-16 | nomatter                  | W   | 0.304      | -            | -                | -                | -         |     0.38 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           22 |     7937 | 2024-01-16 | Dynamo Eclot              | W   | 0.302      | -            | -                | -                | -         |     5.08 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           21 |     8012 | 2024-01-14 | Astralis Talent           | L   | 0.288      | -            | -                | -                | -         |    -6.30 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           20 |     8207 | 2024-01-11 | Monte Gen                 | L   | 0.269      | -            | -                | -                | -         |    -7.16 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           19 |     8242 | 2024-01-10 | Soda Gaming               | L   | 0.265      | -            | -                | -                | -         |    -7.68 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           18 |     8275 | 2024-01-10 | FLuffy Gangsters          | W   | 0.265      | -            | -                | -                | -         |     0.47 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           17 |     8337 | 2024-01-09 | 9INE                      | L   | 0.257      | -            | -                | -                | -         |    -7.72 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           16 |     8353 | 2024-01-09 | The Prodigies             | W   | 0.257      | -            | -                | -                | -         |     0.43 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           15 |     8380 | 2024-01-09 | ILIN                      | W   | 0.257      | -            | -                | -                | -         |     0.34 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           14 |     8394 | 2024-01-09 | The Prodigies             | W   | 0.256      | -            | -                | -                | -         |     0.42 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           13 |     8436 | 2024-01-08 | Nexus Gaming              | W   | 0.249      | -            | -                | -                | -         |     1.98 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           12 |     8481 | 2024-01-05 | ex-Turów Zgorzelec Esport | W   | 0.228      | -            | -                | -                | -         |     1.17 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           11 |     8493 | 2024-01-04 | The Prodigies             | L   | 0.222      | -            | -                | -                | -         |    -6.66 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           10 |     9058 | 2023-12-14 | The Witchers              | L   | 0.082      | -            | -                | -                | -         |    -2.31 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|            9 |     9148 | 2023-12-12 | Sashi Esport              | L   | 0.070      | -            | -                | -                | -         |    -1.18 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|            8 |     9367 | 2023-12-08 | ALTERNATE aTTaX           | L   | 0.044      | -            | -                | -                | -         |    -0.83 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|            7 |     9379 | 2023-12-08 | brazylijski luz           | W   | 0.043      | -            | -                | -                | -         |     0.23 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|            6 |     9424 | 2023-12-07 | MOUZ NXT                  | W   | 0.038      | -            | -                | -                | -         |     0.64 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|            5 |     9510 | 2023-12-06 | GenOne                    | W   | 0.030      | -            | -                | -                | -         |     0.04 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|            4 |     9562 | 2023-12-05 | TSM                       | L   | 0.025      | -            | -                | -                | -         |    -0.72 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|            3 |     9621 | 2023-12-04 | SAW                       | L   | 0.016      | -            | -                | -                | -         |    -0.10 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|            2 |     9684 | 2023-12-03 | TSM                       | L   | 0.008      | -            | -                | -                | -         |    -0.24 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|            1 |     9721 | 2023-12-02 | Bad News Kangaroos        | W   | 0.005      | -            | -                | -                | -         |     0.04 | aVN, brutmonster, Cjoffo, nEMANHA, simke |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($44,095.90)
- Divide that value by the 5th highest value among all rosters ($300,806.11)
- The final value (0.15) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-05-22 |      1.000 | $25,000.00     | $25,000.00      |
| 2024-05-16 |      1.000 | $5,000.00      | $5,000.00       |
| 2024-05-04 |      1.000 | $2,000.00      | $2,000.00       |
| 2024-04-24 |      0.963 | $12,500.00     | $12,038.19      |
| 2023-12-13 |      0.077 | $750.00        | $57.71          |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
