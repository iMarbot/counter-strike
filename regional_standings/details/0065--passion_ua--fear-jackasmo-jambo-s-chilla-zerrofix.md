### Roster Details<br />
Team Name: Passion UA<br />
Roster: fear, jackasmo, jambo, s-chilla, zeRRoFIX<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [65](../standings_global.md)<br />
Regional Rank: [44]( ../standings_europe.md)<br />
Final Rank Value:  987.0<br />
<br />
Final Rank Value (987.0) = Starting Rank Value (1027.3) + Head To Head Adjustments (-40.4)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.445[<sup>1</sup>](#table2)
- Bounty Collected: 0.415[<sup>2</sup>](#table1)
- Opponent Network: 0.374[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.309<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1027.3
- 400 + ( ( 0.309 - 0.000 ) / ( 0.787 - 0.000 ) ) * 1600 = 1027.3


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent             | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                         |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|          131 |      101 | 2024-05-29 | Illuminar Gaming     | W   | 1.000      | -            | -                | -                | 0 (0.000) |     6.74 | fear, jackasmo, jambo, s-chilla, zeRRoFIX      |
|          130 |      283 | 2024-05-25 | Team Sampi           | W   | 1.000      | 0.435        | 0.039 (0.017)    | 0.677 (0.294)    | 0 (0.000) |    15.94 | fear, jackasmo, jambo, s-chilla, zeRRoFIX      |
|          129 |      368 | 2024-05-24 | FURIA Esports        | L   | 1.000      | -            | -                | -                | -         |    -3.35 | fear, jackasmo, jambo, s-chilla, zeRRoFIX      |
|          128 |      377 | 2024-05-24 | ECSTATIC             | W   | 1.000      | -            | -                | -                | 0 (0.000) |     1.24 | fear, jackasmo, jambo, s-chilla, zeRRoFIX      |
|          127 |      405 | 2024-05-23 | JANO Esports         | W   | 1.000      | -            | -                | -                | 0 (0.000) |     6.86 | fear, jackasmo, jambo, s-chilla, zeRRoFIX      |
|          126 |      426 | 2024-05-23 | SINNERS Esports      | W   | 1.000      | -            | -                | -                | 0 (0.000) |    16.91 | fear, jackasmo, jambo, s-chilla, zeRRoFIX      |
|          125 |      469 | 2024-05-22 | Kappa Bar            | W   | 1.000      | -            | -                | -                | 0 (0.000) |     3.26 | fear, jackasmo, jambo, s-chilla, zeRRoFIX      |
|          124 |      594 | 2024-05-21 | Denial               | W   | 1.000      | -            | -                | -                | 0 (0.000) |     4.43 | fear, jackasmo, jambo, s-chilla, zeRRoFIX      |
|          123 |      731 | 2024-05-20 | Permitta Esports     | W   | 1.000      | 0.435        | -                | 1.000 (0.435)    | 0 (0.000) |    11.86 | fear, jackasmo, jambo, s-chilla, zeRRoFIX      |
|          122 |      748 | 2024-05-19 | WOPA Esport          | L   | 1.000      | -            | -                | -                | -         |   -23.06 | fear, jackasmo, jambo, s-chilla, zeRRoFIX      |
|          121 |      763 | 2024-05-19 | Sashi Esport         | L   | 1.000      | -            | -                | -                | -         |    -5.15 | fear, jackasmo, jambo, s-chilla, zeRRoFIX      |
|          120 |      816 | 2024-05-19 | ALTERNATE aTTaX      | W   | 1.000      | 0.435        | 0.052 (0.023)    | 0.735 (0.319)    | 0 (0.000) |    14.39 | fear, jackasmo, jambo, s-chilla, zeRRoFIX      |
|          119 |      887 | 2024-05-18 | 9Pandas              | L   | 1.000      | -            | -                | -                | -         |    -8.97 | fear, jackasmo, jambo, s-chilla, zeRRoFIX      |
|          118 |     1021 | 2024-05-17 | Nexus Gaming         | W   | 1.000      | 0.435        | -                | 0.857 (0.373)    | 0 (0.000) |    11.62 | fear, jackasmo, jambo, s-chilla, zeRRoFIX      |
|          117 |     1114 | 2024-05-16 | Sashi Esport         | W   | 1.000      | 0.500        | 0.154 (0.077)    | 1.000 (0.500)    | -         |    27.11 | fear, jackasmo, jambo, s-chilla, zeRRoFIX      |
|          116 |     1180 | 2024-05-15 | Endpoint             | L   | 1.000      | -            | -                | -                | -         |   -14.30 | fear, jackasmo, jambo, s-chilla, zeRRoFIX      |
|          115 |     1264 | 2024-05-14 | SINNERS Esports      | L   | 1.000      | -            | -                | -                | -         |   -13.65 | fear, jackasmo, jambo, s-chilla, zeRRoFIX      |
|          114 |     1290 | 2024-05-14 | GUN5 Esports         | L   | 1.000      | -            | -                | -                | -         |   -24.52 | fear, jackasmo, jambo, s-chilla, zeRRoFIX      |
|          113 |     1495 | 2024-05-11 | Preasy Esport        | W   | 1.000      | -            | -                | -                | -         |     9.60 | fear, jackasmo, jambo, s-chilla, zeRRoFIX      |
|          112 |     1536 | 2024-05-10 | los kogutos          | W   | 1.000      | -            | -                | -                | -         |    13.99 | fear, jackasmo, jambo, s-chilla, zeRRoFIX      |
|          111 |     1571 | 2024-05-09 | ENTERPRISE esports   | L   | 1.000      | -            | -                | -                | -         |   -16.39 | fear, jackasmo, jambo, s-chilla, zeRRoFIX      |
|          110 |     1633 | 2024-05-08 | HOTU                 | W   | 1.000      | -            | -                | -                | -         |    11.77 | fear, jackasmo, jambo, s-chilla, zeRRoFIX      |
|          109 |     1655 | 2024-05-08 | Nexus Gaming         | L   | 1.000      | -            | -                | -                | -         |   -20.92 | fear, jackasmo, jambo, s-chilla, zeRRoFIX      |
|          108 |     1704 | 2024-05-07 | LEON Esports         | W   | 1.000      | -            | -                | -                | -         |     7.46 | fear, jackasmo, jambo, s-chilla, zeRRoFIX      |
|          107 |     1739 | 2024-05-06 | ARROW                | W   | 1.000      | -            | -                | -                | -         |     7.40 | fear, jackasmo, jambo, s-chilla, zeRRoFIX      |
|          106 |     1766 | 2024-05-06 | RoundsGG             | W   | 1.000      | -            | -                | -                | -         |     4.30 | fear, jackasmo, jambo, s-chilla, zeRRoFIX      |
|          105 |     1948 | 2024-05-02 | Nemiga Gaming        | L   | 1.000      | -            | -                | -                | -         |    -6.22 | fear, jackasmo, jambo, s-chilla, zeRRoFIX      |
|          104 |     2015 | 2024-05-01 | PARIVISION           | W   | 1.000      | -            | -                | -                | -         |    16.70 | fear, jackasmo, jambo, s-chilla, zeRRoFIX      |
|          103 |     2078 | 2024-04-30 | 9Pandas              | W   | 1.000      | 0.500        | 0.110 (0.055)    | 0.710 (0.355)    | -         |    21.55 | fear, jackasmo, jambo, s-chilla, zeRRoFIX      |
|          102 |     2098 | 2024-04-29 | 1win                 | L   | 0.997      | -            | -                | -                | -         |   -13.24 | fear, jackasmo, jambo, s-chilla, zeRRoFIX      |
|          101 |     2145 | 2024-04-28 | ALTERNATE aTTaX      | L   | 0.990      | -            | -                | -                | -         |   -16.07 | fear, jackasmo, jambo, s-chilla, zeRRoFIX      |
|          100 |     2300 | 2024-04-26 | 9Pandas              | W   | 0.976      | 0.500        | 0.110 (0.054)    | 0.710 (0.347)    | -         |    20.71 | fear, jackasmo, jambo, s-chilla, zeRRoFIX      |
|           99 |     2350 | 2024-04-25 | ThunderFlash         | L   | 0.970      | -            | -                | -                | -         |   -18.83 | fear, jackasmo, jambo, s-chilla, zeRRoFIX      |
|           98 |     2370 | 2024-04-25 | Sashi Esport         | L   | 0.969      | -            | -                | -                | -         |    -5.36 | fear, jackasmo, jambo, s-chilla, zeRRoFIX      |
|           97 |     2429 | 2024-04-24 | Permitta Esports     | L   | 0.963      | -            | -                | -                | -         |   -13.97 | fear, jackasmo, jambo, s-chilla, zeRRoFIX      |
|           96 |     2491 | 2024-04-22 | B8                   | L   | 0.951      | -            | -                | -                | -         |   -11.27 | fear, jackasmo, jambo, s-chilla, zeRRoFIX      |
|           95 |     2617 | 2024-04-20 | Young Ninjas         | W   | 0.937      | 0.500        | 0.043 (0.020)    | -                | -         |    13.82 | fear, jackasmo, jambo, s-chilla, zeRRoFIX      |
|           94 |     2649 | 2024-04-20 | Insilio              | W   | 0.936      | -            | -                | -                | -         |    14.81 | fear, jackasmo, jambo, s-chilla, zeRRoFIX      |
|           93 |     2704 | 2024-04-20 | Permitta Esports     | L   | 0.934      | -            | -                | -                | -         |   -13.48 | fear, jackasmo, jambo, s-chilla, zeRRoFIX      |
|           92 |     2766 | 2024-04-19 | ALTERNATE aTTaX      | L   | 0.929      | -            | -                | -                | -         |   -16.84 | fear, jackasmo, jambo, s-chilla, zeRRoFIX      |
|           91 |     2838 | 2024-04-18 | Permitta Esports     | W   | 0.922      | 0.500        | -                | 1.000 (0.461)    | -         |    15.22 | fear, jackasmo, jambo, s-chilla, zeRRoFIX      |
|           90 |     2908 | 2024-04-17 | Sashi Esport         | W   | 0.916      | 0.371        | 0.154 (0.052)    | 1.000 (0.339)    | -         |    18.59 | fear, jackasmo, jambo, s-chilla, zeRRoFIX      |
|           89 |     2967 | 2024-04-16 | 500                  | L   | 0.910      | -            | -                | -                | -         |   -15.43 | fear, jackasmo, jambo, s-chilla, zeRRoFIX      |
|           88 |     3056 | 2024-04-14 | SINNERS Esports      | L   | 0.895      | -            | -                | -                | -         |    -9.12 | fear, jackasmo, jambo, s-chilla, zeRRoFIX      |
|           87 |     3143 | 2024-04-12 | Team PeeP            | W   | 0.883      | -            | -                | -                | -         |     3.23 | fear, jackasmo, jambo, s-chilla, zeRRoFIX      |
|           86 |     3273 | 2024-04-10 | Sashi Esport         | W   | 0.869      | 0.371        | 0.154 (0.050)    | 1.000 (0.322)    | -         |    18.03 | fear, jackasmo, jambo, s-chilla, zeRRoFIX      |
|           85 |     3598 | 2024-04-04 | HAVU Gaming          | W   | 0.829      | -            | -                | -                | -         |     6.72 | fear, jackasmo, jambo, s-chilla, zeRRoFIX      |
|           84 |     3690 | 2024-04-02 | BLEED Esports        | L   | 0.817      | -            | -                | -                | -         |    -5.14 | fear, jackasmo, jambo, s-chilla, zeRRoFIX      |
|           83 |     3747 | 2024-03-31 | FAVBET Team          | L   | 0.803      | -            | -                | -                | -         |   -12.96 | fear, jackasmo, jambo, s-chilla, zeRRoFIX      |
|           82 |     3779 | 2024-03-30 | Lazer Cats           | W   | 0.796      | -            | -                | -                | -         |     5.07 | fear, jackasmo, jambo, s-chilla, zeRRoFIX      |
|           81 |     3804 | 2024-03-29 | Natus Vincere Junior | L   | 0.789      | -            | -                | -                | -         |   -15.08 | fear, jackasmo, jambo, s-chilla, zeRRoFIX      |
|           80 |     3845 | 2024-03-28 | GamerLegion Academy  | L   | 0.782      | -            | -                | -                | -         |   -16.21 | fear, jackasmo, jambo, s-chilla, zeRRoFIX      |
|           79 |     3906 | 2024-03-27 | Rebels Gaming        | L   | 0.777      | -            | -                | -                | -         |    -8.18 | fear, jackasmo, jambo, s-chilla, zeRRoFIX      |
|           78 |     3982 | 2024-03-26 | Dynamo Eclot         | W   | 0.771      | -            | -                | -                | -         |    14.74 | fear, jackasmo, jambo, s-chilla, zeRRoFIX      |
|           77 |     4001 | 2024-03-26 | Natus Vincere Junior | W   | 0.768      | -            | -                | -                | -         |     7.42 | fear, jackasmo, jambo, s-chilla, zeRRoFIX      |
|           76 |     4045 | 2024-03-24 | ROSOMAHA             | W   | 0.756      | -            | -                | -                | -         |     2.62 | fear, jackasmo, jambo, s-chilla, zeRRoFIX      |
|           75 |     4109 | 2024-03-23 | Astralis Talent      | W   | 0.749      | -            | -                | -                | -         |    10.10 | fear, jackasmo, jambo, s-chilla, zeRRoFIX      |
|           74 |     4395 | 2024-03-17 | ex-K10               | W   | 0.709      | -            | -                | -                | -         |     7.45 | fear, jackasmo, jambo, s-chilla, zeRRoFIX      |
|           73 |     4403 | 2024-03-17 | Team Sampi           | L   | 0.708      | -            | -                | -                | -         |   -10.41 | fear, jackasmo, jambo, s-chilla, zeRRoFIX      |
|           72 |     4439 | 2024-03-16 | ex-Preasy Esport     | L   | 0.703      | -            | -                | -                | -         |    -9.55 | fear, jackasmo, jambo, s-chilla, zeRRoFIX      |
|           71 |     4557 | 2024-03-14 | Team Sampi           | W   | 0.689      | -            | -                | -                | -         |    11.31 | fear, jackasmo, jambo, s-chilla, zeRRoFIX      |
|           70 |     4563 | 2024-03-14 | NOM Esports          | W   | 0.688      | -            | -                | -                | -         |     1.64 | fear, jackasmo, jambo, s-chilla, zeRRoFIX      |
|           69 |     4693 | 2024-03-12 | Alliance             | W   | 0.676      | -            | -                | -                | -         |     8.71 | fear, jackasmo, jambo, s-chilla, zeRRoFIX      |
|           68 |     4753 | 2024-03-11 | MOUZ NXT             | L   | 0.669      | -            | -                | -                | -         |    -6.27 | fear, jackasmo, jambo, s-chilla, zeRRoFIX      |
|           67 |     4797 | 2024-03-10 | MOUZ NXT             | W   | 0.663      | 0.303        | 0.157 (0.032)    | -                | -         |    14.95 | fear, jackasmo, jambo, s-chilla, zeRRoFIX      |
|           66 |     4838 | 2024-03-09 | The Chosen Few       | L   | 0.657      | -            | -                | -                | -         |   -14.18 | fear, jackasmo, jambo, s-chilla, zeRRoFIX      |
|           65 |     4880 | 2024-03-08 | Team Spirit Academy  | L   | 0.650      | -            | -                | -                | -         |   -14.16 | fear, jackasmo, jambo, s-chilla, zeRRoFIX      |
|           64 |     4892 | 2024-03-08 | Entropiq             | W   | 0.649      | -            | -                | -                | -         |     4.20 | fear, jackasmo, jambo, s-chilla, zeRRoFIX      |
|           63 |     4943 | 2024-03-07 | AURA                 | W   | 0.644      | -            | -                | -                | -         |     3.68 | fear, jackasmo, jambo, s-chilla, zeRRoFIX      |
|           62 |     4954 | 2024-03-07 | Astralis Talent      | W   | 0.642      | -            | -                | -                | -         |     9.00 | fear, jackasmo, jambo, s-chilla, zeRRoFIX      |
|           61 |     5022 | 2024-03-06 | Permitta Esports     | L   | 0.636      | -            | -                | -                | -         |    -9.21 | fear, jackasmo, jambo, s-chilla, zeRRoFIX      |
|           60 |     5045 | 2024-03-06 | ex-K10               | W   | 0.636      | -            | -                | -                | -         |     6.76 | fear, jackasmo, jambo, s-chilla, zeRRoFIX      |
|           59 |     5087 | 2024-03-05 | B8                   | L   | 0.631      | -            | -                | -                | -         |    -5.48 | fear, jackasmo, jambo, s-chilla, zeRRoFIX      |
|           58 |     5115 | 2024-03-05 | Natus Vincere Junior | W   | 0.629      | -            | -                | -                | -         |     6.43 | fear, jackasmo, jambo, s-chilla, zeRRoFIX      |
|           57 |     5131 | 2024-03-04 | 9INE                 | W   | 0.625      | -            | -                | -                | -         |     2.65 | fear, jackasmo, jambo, s-chilla, zeRRoFIX      |
|           56 |     5144 | 2024-03-04 | ALTERNATE aTTaX      | W   | 0.625      | -            | -                | -                | -         |     9.30 | fear, jackasmo, jambo, s-chilla, zeRRoFIX      |
|           55 |     5197 | 2024-03-04 | ALTERNATE aTTaX      | W   | 0.622      | -            | -                | -                | -         |     9.79 | fear, jackasmo, jambo, s-chilla, zeRRoFIX      |
|           54 |     5346 | 2024-03-02 | Sashi Esport         | W   | 0.609      | -            | -                | -                | -         |     5.84 | fear, jackasmo, jambo, s-chilla, zeRRoFIX      |
|           53 |     5388 | 2024-03-01 | Nexus Gaming         | L   | 0.603      | -            | -                | -                | -         |   -10.37 | fear, jackasmo, jambo, s-chilla, zeRRoFIX      |
|           52 |     5423 | 2024-02-29 | L&G                  | W   | 0.597      | -            | -                | -                | -         |     1.59 | fear, jackasmo, jambo, s-chilla, zeRRoFIX      |
|           51 |     5492 | 2024-02-28 | NOM Esports          | L   | 0.588      | -            | -                | -                | -         |   -15.47 | fear, jackasmo, jambo, s-chilla, zeRRoFIX      |
|           50 |     5735 | 2024-02-24 | Sashi Esport         | W   | 0.562      | -            | -                | -                | -         |     4.94 | fear, jackasmo, jambo, s-chilla, zeRRoFIX      |
|           49 |     5824 | 2024-02-22 | Entropiq             | W   | 0.550      | -            | -                | -                | -         |     3.80 | fear, jackasmo, jambo, s-chilla, zeRRoFIX      |
|           48 |     5925 | 2024-02-20 | ARCRED               | L   | 0.537      | -            | -                | -                | -         |   -12.26 | fear, jackasmo, jambo, s-chilla, zeRRoFIX      |
|           47 |     6047 | 2024-02-18 | MOUZ NXT             | L   | 0.524      | -            | -                | -                | -         |    -4.80 | fear, jackasmo, jambo, s-chilla, zeRRoFIX      |
|           46 |     6072 | 2024-02-18 | Viperio              | L   | 0.522      | -            | -                | -                | -         |   -13.94 | fear, jackasmo, jambo, s-chilla, zeRRoFIX      |
|           45 |     6182 | 2024-02-16 | ex-K10               | W   | 0.508      | -            | -                | -                | -         |     5.00 | jackasmo, jambo, marat2k, s-chilla, zeRRoFIX   |
|           44 |     6230 | 2024-02-15 | Natus Vincere Junior | L   | 0.503      | -            | -                | -                | -         |   -11.43 | jackasmo, jambo, marat2k, s-chilla, zeRRoFIX   |
|           43 |     6341 | 2024-02-13 | Insilio              | W   | 0.490      | -            | -                | -                | -         |     7.38 | jackasmo, jambo, marat2k, s-chilla, zeRRoFIX   |
|           42 |     6383 | 2024-02-12 | Lemondogs            | W   | 0.484      | -            | -                | -                | -         |     1.77 | jackasmo, jambo, marat2k, s-chilla, zeRRoFIX   |
|           41 |     6420 | 2024-02-11 | V1dar Gaming         | W   | 0.477      | -            | -                | -                | -         |     2.59 | jackasmo, jambo, marat2k, s-chilla, zeRRoFIX   |
|           40 |     6436 | 2024-02-11 | Sashi Esport         | L   | 0.475      | -            | -                | -                | -         |   -13.34 | jackasmo, jambo, marat2k, s-chilla, zeRRoFIX   |
|           39 |     6500 | 2024-02-09 | BIG Academy          | L   | 0.462      | -            | -                | -                | -         |   -11.37 | jackasmo, jambo, marat2k, s-chilla, zeRRoFIX   |
|           38 |     6529 | 2024-02-08 | Monte Gen            | L   | 0.456      | -            | -                | -                | -         |   -10.43 | jackasmo, jambo, marat2k, s-chilla, zeRRoFIX   |
|           37 |     6530 | 2024-02-08 | BLEED Esports        | L   | 0.456      | -            | -                | -                | -         |    -3.37 | jackasmo, jambo, s-chilla, zeRRoFIX, Zinchenko |
|           36 |     6556 | 2024-02-07 | ROYALS               | W   | 0.450      | -            | -                | -                | -         |     1.06 | jackasmo, jambo, marat2k, s-chilla, zeRRoFIX   |
|           35 |     6661 | 2024-02-04 | DASH                 | L   | 0.431      | -            | -                | -                | -         |   -11.47 | jackasmo, jambo, marat2k, s-chilla, zeRRoFIX   |
|           34 |     6768 | 2024-02-03 | BIG Academy          | W   | 0.423      | -            | -                | -                | -         |     2.41 | jackasmo, jambo, marat2k, s-chilla, zeRRoFIX   |
|           33 |     6911 | 2024-01-31 | Kappa Bar            | W   | 0.404      | -            | -                | -                | -         |     0.82 | jackasmo, jambo, marat2k, s-chilla, zeRRoFIX   |
|           32 |     7016 | 2024-01-29 | 3DMAX                | L   | 0.392      | -            | -                | -                | -         |    -7.24 | jackasmo, jambo, marat2k, s-chilla, zeRRoFIX   |
|           31 |     7053 | 2024-01-29 | Alliance             | W   | 0.390      | -            | -                | -                | -         |     3.49 | jackasmo, jambo, s-chilla, zeRRoFIX, Zinchenko |
|           30 |     7106 | 2024-01-28 | Nexus Gaming         | W   | 0.382      | -            | -                | -                | -         |     4.80 | jackasmo, jambo, marat2k, s-chilla, zeRRoFIX   |
|           29 |     7508 | 2024-01-21 | ex-KRC Genk Esports  | W   | 0.338      | -            | -                | -                | -         |     1.77 | jackasmo, jambo, marat2k, s-chilla, zeRRoFIX   |
|           28 |     7744 | 2024-01-18 | MOUZ NXT             | L   | 0.315      | -            | -                | -                | -         |    -3.49 | jackasmo, jambo, marat2k, s-chilla, zeRRoFIX   |
|           27 |     7804 | 2024-01-17 | Into The Breach      | L   | 0.311      | -            | -                | -                | -         |    -8.18 | jackasmo, jambo, marat2k, s-chilla, zeRRoFIX   |
|           26 |     7861 | 2024-01-16 | Zero Tenacity        | L   | 0.306      | -            | -                | -                | -         |    -4.09 | jackasmo, jambo, marat2k, s-chilla, zeRRoFIX   |
|           25 |     7877 | 2024-01-16 | Rebels Gaming        | W   | 0.305      | -            | -                | -                | -         |     6.17 | jackasmo, jambo, marat2k, s-chilla, zeRRoFIX   |
|           24 |     7889 | 2024-01-16 | RUBY                 | W   | 0.305      | -            | -                | -                | -         |     3.35 | jackasmo, jambo, marat2k, s-chilla, zeRRoFIX   |
|           23 |     7906 | 2024-01-16 | happyend1            | W   | 0.304      | -            | -                | -                | -         |     0.31 | jackasmo, jambo, marat2k, s-chilla, zeRRoFIX   |
|           22 |     7970 | 2024-01-15 | ROSOMAHA             | W   | 0.295      | -            | -                | -                | -         |     0.88 | jackasmo, jambo, marat2k, s-chilla, zeRRoFIX   |
|           21 |     8011 | 2024-01-14 | Monte Gen            | L   | 0.288      | -            | -                | -                | -         |    -7.14 | jackasmo, jambo, marat2k, s-chilla, zeRRoFIX   |
|           20 |     8104 | 2024-01-12 | OG                   | L   | 0.278      | -            | -                | -                | -         |    -2.42 | jackasmo, jambo, marat2k, s-chilla, zeRRoFIX   |
|           19 |     8118 | 2024-01-12 | HAVU Gaming          | W   | 0.278      | -            | -                | -                | -         |     1.82 | jackasmo, jambo, marat2k, s-chilla, zeRRoFIX   |
|           18 |     8272 | 2024-01-10 | SINNERS Esports      | L   | 0.265      | -            | -                | -                | -         |    -4.12 | jackasmo, jambo, marat2k, s-chilla, zeRRoFIX   |
|           17 |     8396 | 2024-01-09 | MOUZ NXT             | W   | 0.255      | 0.303        | 0.157 (0.012)    | -                | -         |     5.15 | jackasmo, jambo, marat2k, s-chilla, zeRRoFIX   |
|           16 |     8477 | 2024-01-05 | Permitta Esports     | W   | 0.229      | -            | -                | -                | -         |     3.15 | jackasmo, jambo, marat2k, s-chilla, zeRRoFIX   |
|           15 |     8568 | 2023-12-28 | PSYCHOACTiVE         | L   | 0.177      | -            | -                | -                | -         |    -5.27 | jackasmo, jambo, marat2k, s-chilla, zeRRoFIX   |
|           14 |     8570 | 2023-12-28 | L&G                  | L   | 0.176      | -            | -                | -                | -         |    -5.22 | jackasmo, jambo, marat2k, s-chilla, zeRRoFIX   |
|           13 |     8575 | 2023-12-27 | PSYCHOACTiVE         | W   | 0.169      | -            | -                | -                | -         |     0.30 | jackasmo, jambo, marat2k, s-chilla, zeRRoFIX   |
|           12 |     8915 | 2023-12-16 | Astralis Talent      | L   | 0.095      | -            | -                | -                | -         |    -1.91 | jackasmo, jambo, marat2k, s-chilla, zeRRoFIX   |
|           11 |     9017 | 2023-12-15 | brazylijski luz      | L   | 0.089      | -            | -                | -                | -         |    -2.15 | jackasmo, jambo, marat2k, s-chilla, zeRRoFIX   |
|           10 |     9050 | 2023-12-14 | ex-KRC Genk Esports  | L   | 0.084      | -            | -                | -                | -         |    -2.27 | jackasmo, jambo, marat2k, s-chilla, zeRRoFIX   |
|            9 |     9099 | 2023-12-13 | Eternal Fire Academy | W   | 0.077      | -            | -                | -                | -         |     0.27 | jackasmo, jambo, marat2k, s-chilla, zeRRoFIX   |
|            8 |     9113 | 2023-12-13 | NOM Esports          | W   | 0.076      | -            | -                | -                | -         |     0.25 | jackasmo, jambo, marat2k, s-chilla, zeRRoFIX   |
|            7 |     9149 | 2023-12-12 | HyperSpirit          | W   | 0.070      | -            | -                | -                | -         |     0.40 | jackasmo, jambo, marat2k, s-chilla, zeRRoFIX   |
|            6 |     9188 | 2023-12-11 | UNiTY esports        | L   | 0.064      | -            | -                | -                | -         |    -1.30 | jackasmo, jambo, marat2k, s-chilla, zeRRoFIX   |
|            5 |     9249 | 2023-12-10 | The Witchers         | W   | 0.056      | -            | -                | -                | -         |     0.25 | jackasmo, jambo, marat2k, s-chilla, zeRRoFIX   |
|            4 |     9431 | 2023-12-07 | BLUEJAYS Lite        | W   | 0.038      | -            | -                | -                | -         |     0.05 | jackasmo, jambo, marat2k, s-chilla, zeRRoFIX   |
|            3 |     9516 | 2023-12-06 | M1X                  | W   | 0.029      | -            | -                | -                | -         |     0.08 | jackasmo, jambo, marat2k, s-chilla, zeRRoFIX   |
|            2 |     9577 | 2023-12-05 | WHYKICK Team         | W   | 0.024      | -            | -                | -                | -         |     0.02 | jackasmo, jambo, marat2k, s-chilla, zeRRoFIX   |
|            1 |     9780 | 2023-12-02 | detoks               | L   | 0.003      | -            | -                | -                | -         |    -0.07 | jackasmo, jambo, marat2k, s-chilla, zeRRoFIX   |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($17,019.56)
- Divide that value by the 5th highest value among all rosters ($300,806.11)
- The final value (0.06) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-05-03 |      1.000 | $12,500.00     | $12,500.00      |
| 2024-03-31 |      0.803 | $638.18        | $512.23         |
| 2024-03-30 |      0.796 | $1,000.00      | $795.83         |
| 2024-03-18 |      0.715 | $3,000.00      | $2,145.00       |
| 2024-03-11 |      0.669 | $1,500.00      | $1,003.75       |
| 2023-12-17 |      0.105 | $600.00        | $62.75          |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
