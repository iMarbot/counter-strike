### Roster Details<br />
Team Name: Zero Tenacity<br />
Roster: aVN, brutmonster, Cjoffo, nEMANHA, simke<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [46](../standings_global.md)<br />
Regional Rank: [34]( ../standings_europe.md)<br />
Final Rank Value:  1068.9<br />
<br />
Final Rank Value (1068.9) = Starting Rank Value (1097.8) + Head To Head Adjustments (-28.8)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.545[<sup>1</sup>](#table2)
- Bounty Collected: 0.440[<sup>2</sup>](#table1)
- Opponent Network: 0.386[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.343<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1097.8
- 400 + ( ( 0.343 - 0.000 ) / ( 0.786 - 0.000 ) ) * 1600 = 1097.8


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
|          129 |      226 | 2024-05-26 | RUBY                      | W   | 1.000      | -            | -                | -                | 0 (0.000) |    11.59 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|          128 |      260 | 2024-05-25 | ex-Guild Eagles           | W   | 1.000      | -            | -                | -                | 0 (0.000) |    11.98 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|          127 |      272 | 2024-05-25 | iNation                   | W   | 1.000      | -            | -                | -                | 0 (0.000) |     5.29 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|          126 |      309 | 2024-05-25 | Rhyno Esports             | W   | 1.000      | -            | -                | -                | 0 (0.000) |    10.22 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|          125 |      332 | 2024-05-24 | ex-Guild Eagles           | L   | 1.000      | -            | -                | -                | -         |   -19.51 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|          124 |      350 | 2024-05-24 | ILLYRIANS                 | W   | 1.000      | -            | -                | -                | 0 (0.000) |     5.47 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|          123 |      386 | 2024-05-23 | Permitta Esports          | L   | 1.000      | -            | -                | -                | -         |   -25.31 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|          122 |      391 | 2024-05-23 | ENTERPRISE esports        | W   | 1.000      | -            | -                | -                | 0 (0.000) |     7.61 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|          121 |      407 | 2024-05-23 | 3DMAX                     | L   | 1.000      | -            | -                | -                | -         |   -20.86 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|          120 |      419 | 2024-05-23 | brazylijski luz           | W   | 1.000      | -            | -                | -                | 0 (0.000) |     6.74 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|          119 |      452 | 2024-05-22 | 1win                      | W   | 1.000      | 0.372        | 0.050 (0.019)    | 0.887 (0.330)    | 0 (0.000) |    14.10 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|          118 |      492 | 2024-05-22 | Sangal Esports            | L   | 1.000      | -            | -                | -                | -         |   -14.64 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|          117 |      521 | 2024-05-22 | Illuminar Gaming          | W   | 1.000      | -            | -                | -                | 0 (0.000) |     4.40 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|          116 |      596 | 2024-05-21 | BLEED Esports             | W   | 1.000      | 0.500        | 0.248 (0.124)    | 0.677 (0.339)    | 0 (0.000) |    20.52 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|          115 |      622 | 2024-05-21 | Verdant                   | W   | 1.000      | 0.435        | -                | 1.000 (0.435)    | -         |    11.88 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|          114 |      663 | 2024-05-20 | Metizport                 | W   | 1.000      | 0.500        | 0.088 (0.044)    | 0.698 (0.349)    | -         |    18.23 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|          113 |      702 | 2024-05-20 | GUN5 Esports              | W   | 1.000      | -            | -                | -                | -         |     7.05 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|          112 |      796 | 2024-05-19 | B8                        | W   | 1.000      | 0.500        | 0.168 (0.084)    | 0.952 (0.476)    | -         |    22.56 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|          111 |      956 | 2024-05-17 | PARIVISION                | L   | 1.000      | -            | -                | -                | -         |   -18.84 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|          110 |      988 | 2024-05-17 | Endpoint                  | W   | 1.000      | -            | -                | -                | -         |    11.39 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|          109 |     1074 | 2024-05-16 | Team Spirit Academy       | L   | 1.000      | -            | -                | -                | -         |   -25.28 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|          108 |     1099 | 2024-05-16 | 1win                      | L   | 1.000      | -            | -                | -                | -         |   -16.85 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|          107 |     1107 | 2024-05-16 | kONO.ECF                  | W   | 1.000      | -            | -                | -                | -         |     9.44 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|          106 |     1186 | 2024-05-15 | 3DMAX                     | W   | 1.000      | 0.500        | 0.106 (0.053)    | -                | -         |    12.72 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|          105 |     1249 | 2024-05-14 | WOPA Esport               | L   | 1.000      | -            | -                | -                | -         |   -25.94 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|          104 |     1263 | 2024-05-14 | Lilmix                    | L   | 1.000      | -            | -                | -                | -         |   -25.46 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|          103 |     1323 | 2024-05-13 | EYEBALLERS                | W   | 1.000      | -            | -                | -                | -         |    10.96 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|          102 |     1390 | 2024-05-12 | Verdant                   | W   | 1.000      | 0.333        | -                | 1.000 (0.333)    | -         |     9.79 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|          101 |     1532 | 2024-05-10 | UNiTY esports             | W   | 1.000      | -            | -                | -                | -         |     8.97 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|          100 |     1566 | 2024-05-09 | Lausanne-Sport Esports    | W   | 1.000      | -            | -                | -                | -         |     5.03 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           99 |     1576 | 2024-05-09 | 9Pandas                   | L   | 1.000      | -            | -                | -                | -         |   -14.30 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           98 |     1628 | 2024-05-08 | Eternal Fire Academy      | W   | 1.000      | -            | -                | -                | -         |     1.90 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           97 |     1635 | 2024-05-08 | Young Ninjas              | W   | 1.000      | 0.372        | 0.043 (0.016)    | -                | -         |    10.55 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           96 |     1727 | 2024-05-06 | Insilio                   | W   | 1.000      | -            | -                | -                | -         |    13.86 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           95 |     1740 | 2024-05-06 | Johnny Speeds             | W   | 1.000      | 0.333        | 0.056 (0.019)    | -                | -         |    16.27 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           94 |     1871 | 2024-05-03 | EYEBALLERS                | L   | 1.000      | -            | -                | -                | -         |   -18.23 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           93 |     1895 | 2024-05-03 | Metizport                 | L   | 1.000      | -            | -                | -                | -         |   -13.75 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           92 |     1927 | 2024-05-02 | EXO Clan                  | W   | 1.000      | -            | -                | -                | -         |    12.85 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           91 |     1937 | 2024-05-02 | HAVU Gaming               | W   | 1.000      | -            | -                | -                | -         |     5.12 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           90 |     1999 | 2024-05-01 | KOI                       | W   | 1.000      | -            | -                | -                | -         |    16.80 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           89 |     2029 | 2024-04-30 | Sangal Esports            | L   | 1.000      | -            | -                | -                | -         |   -14.50 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           88 |     2043 | 2024-04-30 | B8                        | W   | 1.000      | 0.435        | 0.168 (0.073)    | 0.952 (0.414)    | -         |    17.88 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           87 |     2079 | 2024-04-29 | PARIVISION                | L   | 0.996      | -            | -                | -                | -         |   -17.35 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           86 |     2101 | 2024-04-28 | HOTU                      | L   | 0.990      | -            | -                | -                | -         |   -23.05 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           85 |     2120 | 2024-04-28 | SINNERS Esports           | W   | 0.989      | -            | -                | -                | -         |    12.86 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           84 |     2164 | 2024-04-27 | 500                       | W   | 0.984      | -            | -                | -                | -         |     8.28 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           83 |     2217 | 2024-04-27 | SINNERS Esports           | W   | 0.981      | -            | -                | -                | -         |    14.27 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           82 |     2285 | 2024-04-26 | Illuminar Gaming          | W   | 0.975      | -            | -                | -                | -         |     8.61 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           81 |     2299 | 2024-04-25 | Astralis Talent           | W   | 0.971      | -            | -                | -                | -         |     9.83 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           80 |     2325 | 2024-04-25 | EYEBALLERS                | L   | 0.969      | -            | -                | -                | -         |   -18.82 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           79 |     2357 | 2024-04-24 | Team Space                | W   | 0.964      | -            | -                | -                | -         |     7.80 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           78 |     2391 | 2024-04-24 | ex-Guild Eagles           | L   | 0.962      | -            | -                | -                | -         |   -15.33 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           77 |     2408 | 2024-04-23 | Verdant                   | W   | 0.957      | 0.372        | -                | 1.000 (0.356)    | -         |     9.56 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           76 |     2430 | 2024-04-23 | Nemiga Gaming             | L   | 0.956      | -            | -                | -                | -         |    -7.33 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           75 |     2448 | 2024-04-22 | Grannys Knockers          | W   | 0.950      | -            | -                | -                | -         |     7.41 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           74 |     2464 | 2024-04-22 | Nexus Gaming              | W   | 0.949      | 0.500        | -                | 0.825 (0.391)    | -         |    11.83 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           73 |     2594 | 2024-04-20 | RUBY                      | W   | 0.936      | -            | -                | -                | -         |    13.71 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           72 |     2683 | 2024-04-19 | PARIVISION                | W   | 0.931      | -            | -                | -                | -         |    11.02 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           71 |     2725 | 2024-04-19 | ALTERNATE aTTaX           | W   | 0.929      | -            | -                | -                | -         |    12.72 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           70 |     2795 | 2024-04-18 | B8                        | L   | 0.921      | -            | -                | -                | -         |   -10.11 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           69 |     2824 | 2024-04-17 | Fnatic                    | L   | 0.918      | -            | -                | -                | -         |    -7.85 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           68 |     2854 | 2024-04-17 | B8                        | W   | 0.916      | 0.500        | 0.168 (0.077)    | 0.952 (0.436)    | -         |    18.92 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           67 |     2903 | 2024-04-16 | Sangal Esports            | L   | 0.910      | -            | -                | -                | -         |   -13.62 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           66 |     2949 | 2024-04-15 | ALTERNATE aTTaX           | W   | 0.904      | -            | -                | -                | -         |    13.48 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           65 |     3077 | 2024-04-12 | Aurora Young Blud         | W   | 0.883      | -            | -                | -                | -         |     7.15 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           64 |     3091 | 2024-04-12 | JANO Esports              | L   | 0.881      | -            | -                | -                | -         |   -21.47 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           63 |     3129 | 2024-04-11 | Alliance                  | L   | 0.876      | -            | -                | -                | -         |   -17.68 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           62 |     3251 | 2024-04-09 | MOUZ NXT                  | L   | 0.863      | -            | -                | -                | -         |   -10.07 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           61 |     3356 | 2024-04-07 | ex-Preasy Esport          | L   | 0.848      | -            | -                | -                | -         |   -13.60 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           60 |     3632 | 2024-04-01 | Nemiga Gaming             | L   | 0.808      | -            | -                | -                | -         |    -6.99 | aVN, brutmonster, Cjoffo, kdaN, simke    |
|           59 |     3868 | 2024-03-26 | Ninjas in Pyjamas         | L   | 0.771      | -            | -                | -                | -         |   -10.07 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           58 |     4654 | 2024-03-10 | CYBERSHOKE Esports        | L   | 0.664      | -            | -                | -                | -         |   -17.56 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           57 |     4671 | 2024-03-10 | Dynamo Eclot              | W   | 0.663      | 0.384        | 0.097 (0.025)    | -                | -         |    11.99 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           56 |     4722 | 2024-03-09 | Sangal Esports            | W   | 0.656      | -            | -                | -                | -         |     9.04 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           55 |     4891 | 2024-03-06 | AURA                      | W   | 0.636      | -            | -                | -                | -         |     2.61 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           54 |     4960 | 2024-03-05 | AMKAL ESPORTS             | L   | 0.631      | -            | -                | -                | -         |    -6.08 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           53 |     5009 | 2024-03-04 | petardka                  | W   | 0.625      | -            | -                | -                | -         |     0.57 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           52 |     5069 | 2024-03-03 | Lilmix                    | W   | 0.618      | -            | -                | -                | -         |     4.36 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           51 |     5094 | 2024-03-03 | Nexus Gaming              | L   | 0.617      | -            | -                | -                | -         |   -12.45 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           50 |     5112 | 2024-03-03 | Team Secret               | W   | 0.615      | -            | -                | -                | -         |     2.10 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           49 |     5213 | 2024-03-02 | Team Secret               | W   | 0.609      | -            | -                | -                | -         |     2.12 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           48 |     5264 | 2024-02-29 | esmagaB                   | W   | 0.598      | -            | -                | -                | -         |     3.70 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           47 |     5290 | 2024-02-29 | Young Ninjas              | W   | 0.596      | -            | -                | -                | -         |     6.95 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           46 |     5335 | 2024-02-28 | Entropiq                  | L   | 0.589      | -            | -                | -                | -         |   -15.83 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           45 |     5376 | 2024-02-27 | DMS                       | W   | 0.583      | -            | -                | -                | -         |     2.82 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           44 |     5649 | 2024-02-22 | NOM Esports               | W   | 0.551      | -            | -                | -                | -         |     1.55 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           43 |     5931 | 2024-02-17 | Eternal Fire Academy      | W   | 0.518      | -            | -                | -                | -         |     1.77 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           42 |     5948 | 2024-02-17 | Sashi Esport              | L   | 0.517      | -            | -                | -                | -         |    -7.09 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           41 |     6038 | 2024-02-15 | Team Secret               | L   | 0.504      | -            | -                | -                | -         |   -14.24 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           40 |     6052 | 2024-02-15 | Copenhagen Wolves         | W   | 0.503      | -            | -                | -                | -         |     1.38 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           39 |     6089 | 2024-02-14 | BAKS Esports              | W   | 0.498      | -            | -                | -                | -         |     1.33 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           38 |     6262 | 2024-02-10 | Team Sampi                | L   | 0.471      | -            | -                | -                | -         |    -9.65 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           37 |     6373 | 2024-02-06 | ex-Hot Headed Gaming      | W   | 0.444      | -            | -                | -                | -         |     0.60 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           36 |     6468 | 2024-02-04 | 500                       | L   | 0.429      | -            | -                | -                | -         |   -11.06 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           35 |     6495 | 2024-02-03 | The Chosen Few            | W   | 0.425      | -            | -                | -                | -         |     2.11 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           34 |     6622 | 2024-02-02 | Natus Vincere Junior      | W   | 0.417      | -            | -                | -                | -         |     2.40 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           33 |     6635 | 2024-02-02 | Jake Bube                 | W   | 0.416      | -            | -                | -                | -         |     0.56 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           32 |     7174 | 2024-01-23 | Rhyno Esports             | W   | 0.351      | -            | -                | -                | -         |     5.05 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           31 |     7360 | 2024-01-20 | 3DMAX                     | L   | 0.329      | -            | -                | -                | -         |    -6.84 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           30 |     7413 | 2024-01-19 | SAW                       | L   | 0.323      | -            | -                | -                | -         |    -1.62 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           29 |     7459 | 2024-01-18 | Permitta Esports          | W   | 0.318      | -            | -                | -                | -         |     3.57 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           28 |     7479 | 2024-01-18 | BetBoom Team              | L   | 0.317      | -            | -                | -                | -         |    -1.14 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           27 |     7494 | 2024-01-18 | Aurora Young Blud         | L   | 0.315      | -            | -                | -                | -         |    -8.15 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           26 |     7612 | 2024-01-16 | Passion UA                | W   | 0.306      | -            | -                | -                | -         |     4.01 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           25 |     7620 | 2024-01-16 | samaloyod                 | W   | 0.305      | -            | -                | -                | -         |     0.50 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           24 |     7644 | 2024-01-16 | premghouls                | W   | 0.304      | -            | -                | -                | -         |     0.23 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           23 |     7661 | 2024-01-16 | nomatter                  | W   | 0.304      | -            | -                | -                | -         |     0.38 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           22 |     7688 | 2024-01-16 | Dynamo Eclot              | W   | 0.302      | -            | -                | -                | -         |     5.07 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           21 |     7759 | 2024-01-14 | Astralis Talent           | L   | 0.288      | -            | -                | -                | -         |    -6.29 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           20 |     7954 | 2024-01-11 | Monte Gen                 | L   | 0.269      | -            | -                | -                | -         |    -7.16 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           19 |     7988 | 2024-01-10 | Soda Gaming               | L   | 0.265      | -            | -                | -                | -         |    -7.75 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           18 |     8021 | 2024-01-10 | ex-FLuffy Gangsters       | W   | 0.265      | -            | -                | -                | -         |     0.32 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           17 |     8083 | 2024-01-09 | 9INE                      | L   | 0.257      | -            | -                | -                | -         |    -7.72 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           16 |     8099 | 2024-01-09 | The Prodigies             | W   | 0.257      | -            | -                | -                | -         |     0.43 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           15 |     8126 | 2024-01-09 | ILIN                      | W   | 0.257      | -            | -                | -                | -         |     0.34 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           14 |     8140 | 2024-01-09 | The Prodigies             | W   | 0.256      | -            | -                | -                | -         |     0.42 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           13 |     8181 | 2024-01-08 | Nexus Gaming              | W   | 0.249      | -            | -                | -                | -         |     2.16 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           12 |     8226 | 2024-01-05 | ex-Turów Zgorzelec Esport | W   | 0.228      | -            | -                | -                | -         |     1.07 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           11 |     8237 | 2024-01-04 | The Prodigies             | L   | 0.222      | -            | -                | -                | -         |    -6.65 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           10 |     8795 | 2023-12-14 | The Witchers              | L   | 0.082      | -            | -                | -                | -         |    -2.31 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|            9 |     8884 | 2023-12-12 | Sashi Esport              | L   | 0.070      | -            | -                | -                | -         |    -1.17 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|            8 |     9099 | 2023-12-08 | ALTERNATE aTTaX           | L   | 0.044      | -            | -                | -                | -         |    -1.25 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|            7 |     9110 | 2023-12-08 | brazylijski luz           | W   | 0.043      | -            | -                | -                | -         |     0.23 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|            6 |     9151 | 2023-12-07 | MOUZ NXT                  | W   | 0.038      | -            | -                | -                | -         |     0.63 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|            5 |     9229 | 2023-12-06 | GenOne                    | W   | 0.030      | -            | -                | -                | -         |     0.04 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|            4 |     9280 | 2023-12-05 | TSM                       | L   | 0.025      | -            | -                | -                | -         |    -0.72 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|            3 |     9339 | 2023-12-04 | SAW                       | L   | 0.016      | -            | -                | -                | -         |    -0.09 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|            2 |     9402 | 2023-12-03 | TSM                       | L   | 0.008      | -            | -                | -                | -         |    -0.24 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|            1 |     9439 | 2023-12-02 | Bad News Kangaroos        | W   | 0.005      | -            | -                | -                | -         |     0.04 | aVN, brutmonster, Cjoffo, nEMANHA, simke |

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
