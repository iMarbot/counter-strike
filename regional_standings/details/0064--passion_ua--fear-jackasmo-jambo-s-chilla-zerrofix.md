### Roster Details<br />
Team Name: Passion UA<br />
Roster: fear, jackasmo, jambo, s-chilla, zeRRoFIX<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [64](../standings_global.md)<br />
Regional Rank: [44]( ../standings_europe.md)<br />
Final Rank Value:  978.9<br />
<br />
Final Rank Value (978.9) = Starting Rank Value (1017.8) + Head To Head Adjustments (-39.0)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.445[<sup>1</sup>](#table2)
- Bounty Collected: 0.411[<sup>2</sup>](#table1)
- Opponent Network: 0.358[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.303<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1017.8
- 400 + ( ( 0.303 - 0.000 ) / ( 0.786 - 0.000 ) ) * 1600 = 1017.8


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
|          130 |       94 | 2024-05-29 | Illuminar Gaming     | W   | 1.000      | -            | -                | -                | 0 (0.000) |     6.89 | fear, jackasmo, jambo, s-chilla, zeRRoFIX      |
|          129 |      275 | 2024-05-25 | Team Sampi           | W   | 1.000      | 0.435        | 0.039 (0.017)    | 0.665 (0.289)    | 0 (0.000) |    16.15 | fear, jackasmo, jambo, s-chilla, zeRRoFIX      |
|          128 |      359 | 2024-05-24 | FURIA Esports        | L   | 1.000      | -            | -                | -                | -         |    -3.21 | fear, jackasmo, jambo, s-chilla, zeRRoFIX      |
|          127 |      368 | 2024-05-24 | ECSTATIC             | W   | 1.000      | -            | -                | -                | 0 (0.000) |     1.30 | fear, jackasmo, jambo, s-chilla, zeRRoFIX      |
|          126 |      397 | 2024-05-23 | JANO Esports         | W   | 1.000      | -            | -                | -                | 0 (0.000) |     6.86 | fear, jackasmo, jambo, s-chilla, zeRRoFIX      |
|          125 |      418 | 2024-05-23 | SINNERS Esports      | W   | 1.000      | -            | -                | -                | 0 (0.000) |    16.92 | fear, jackasmo, jambo, s-chilla, zeRRoFIX      |
|          124 |      463 | 2024-05-22 | Kappa Bar            | W   | 1.000      | -            | -                | -                | 0 (0.000) |     3.33 | fear, jackasmo, jambo, s-chilla, zeRRoFIX      |
|          123 |      583 | 2024-05-21 | Denial               | W   | 1.000      | -            | -                | -                | 0 (0.000) |     4.67 | fear, jackasmo, jambo, s-chilla, zeRRoFIX      |
|          122 |      719 | 2024-05-20 | Permitta Esports     | W   | 1.000      | 0.435        | 0.029 (0.012)    | 1.000 (0.435)    | 0 (0.000) |    11.51 | fear, jackasmo, jambo, s-chilla, zeRRoFIX      |
|          121 |      736 | 2024-05-19 | WOPA Esport          | L   | 1.000      | -            | -                | -                | -         |   -22.91 | fear, jackasmo, jambo, s-chilla, zeRRoFIX      |
|          120 |      751 | 2024-05-19 | Sashi Esport         | L   | 1.000      | -            | -                | -                | -         |    -4.96 | fear, jackasmo, jambo, s-chilla, zeRRoFIX      |
|          119 |      804 | 2024-05-19 | ALTERNATE aTTaX      | W   | 1.000      | 0.435        | 0.052 (0.022)    | 0.679 (0.295)    | 0 (0.000) |    14.68 | fear, jackasmo, jambo, s-chilla, zeRRoFIX      |
|          118 |      875 | 2024-05-18 | 9Pandas              | L   | 1.000      | -            | -                | -                | -         |    -9.01 | fear, jackasmo, jambo, s-chilla, zeRRoFIX      |
|          117 |     1009 | 2024-05-17 | Nexus Gaming         | W   | 1.000      | 0.435        | -                | 0.825 (0.358)    | 0 (0.000) |    12.30 | fear, jackasmo, jambo, s-chilla, zeRRoFIX      |
|          116 |     1104 | 2024-05-16 | Sashi Esport         | W   | 1.000      | 0.500        | 0.172 (0.086)    | 1.000 (0.500)    | -         |    27.30 | fear, jackasmo, jambo, s-chilla, zeRRoFIX      |
|          115 |     1170 | 2024-05-15 | Endpoint             | L   | 1.000      | -            | -                | -                | -         |   -14.68 | fear, jackasmo, jambo, s-chilla, zeRRoFIX      |
|          114 |     1254 | 2024-05-14 | SINNERS Esports      | L   | 1.000      | -            | -                | -                | -         |   -13.60 | fear, jackasmo, jambo, s-chilla, zeRRoFIX      |
|          113 |     1279 | 2024-05-14 | GUN5 Esports         | L   | 1.000      | -            | -                | -                | -         |   -24.44 | fear, jackasmo, jambo, s-chilla, zeRRoFIX      |
|          112 |     1482 | 2024-05-11 | Preasy Esport        | W   | 1.000      | -            | -                | -                | -         |     9.87 | fear, jackasmo, jambo, s-chilla, zeRRoFIX      |
|          111 |     1522 | 2024-05-10 | los kogutos          | W   | 1.000      | -            | -                | -                | -         |    14.60 | fear, jackasmo, jambo, s-chilla, zeRRoFIX      |
|          110 |     1556 | 2024-05-09 | ENTERPRISE esports   | L   | 1.000      | -            | -                | -                | -         |   -16.67 | fear, jackasmo, jambo, s-chilla, zeRRoFIX      |
|          109 |     1618 | 2024-05-08 | HOTU                 | W   | 1.000      | -            | -                | -                | -         |    11.81 | fear, jackasmo, jambo, s-chilla, zeRRoFIX      |
|          108 |     1637 | 2024-05-08 | Nexus Gaming         | L   | 1.000      | -            | -                | -                | -         |   -20.02 | fear, jackasmo, jambo, s-chilla, zeRRoFIX      |
|          107 |     1685 | 2024-05-07 | LEON Esports         | W   | 1.000      | -            | -                | -                | -         |     7.64 | fear, jackasmo, jambo, s-chilla, zeRRoFIX      |
|          106 |     1717 | 2024-05-06 | ARROW                | W   | 1.000      | -            | -                | -                | -         |     8.11 | fear, jackasmo, jambo, s-chilla, zeRRoFIX      |
|          105 |     1743 | 2024-05-06 | RoundsGG             | W   | 1.000      | -            | -                | -                | -         |     3.84 | fear, jackasmo, jambo, s-chilla, zeRRoFIX      |
|          104 |     1921 | 2024-05-02 | Nemiga Gaming        | L   | 1.000      | -            | -                | -                | -         |    -5.89 | fear, jackasmo, jambo, s-chilla, zeRRoFIX      |
|          103 |     1986 | 2024-05-01 | PARIVISION           | W   | 1.000      | -            | -                | -                | -         |    17.34 | fear, jackasmo, jambo, s-chilla, zeRRoFIX      |
|          102 |     2044 | 2024-04-30 | 9Pandas              | W   | 1.000      | 0.500        | 0.110 (0.055)    | 0.660 (0.330)    | -         |    21.57 | fear, jackasmo, jambo, s-chilla, zeRRoFIX      |
|          101 |     2063 | 2024-04-29 | 1win                 | L   | 0.997      | -            | -                | -                | -         |   -12.45 | fear, jackasmo, jambo, s-chilla, zeRRoFIX      |
|          100 |     2110 | 2024-04-28 | ALTERNATE aTTaX      | L   | 0.990      | -            | -                | -                | -         |   -15.43 | fear, jackasmo, jambo, s-chilla, zeRRoFIX      |
|           99 |     2264 | 2024-04-26 | 9Pandas              | W   | 0.976      | 0.500        | 0.110 (0.054)    | 0.660 (0.322)    | -         |    20.79 | fear, jackasmo, jambo, s-chilla, zeRRoFIX      |
|           98 |     2311 | 2024-04-25 | ThunderFlash         | L   | 0.970      | -            | -                | -                | -         |   -17.66 | fear, jackasmo, jambo, s-chilla, zeRRoFIX      |
|           97 |     2329 | 2024-04-25 | Sashi Esport         | L   | 0.969      | -            | -                | -                | -         |    -4.95 | fear, jackasmo, jambo, s-chilla, zeRRoFIX      |
|           96 |     2385 | 2024-04-24 | Permitta Esports     | L   | 0.963      | -            | -                | -                | -         |   -14.05 | fear, jackasmo, jambo, s-chilla, zeRRoFIX      |
|           95 |     2443 | 2024-04-22 | B8                   | L   | 0.951      | -            | -                | -                | -         |    -9.96 | fear, jackasmo, jambo, s-chilla, zeRRoFIX      |
|           94 |     2564 | 2024-04-20 | Young Ninjas         | W   | 0.937      | 0.500        | 0.043 (0.020)    | -                | -         |    15.00 | fear, jackasmo, jambo, s-chilla, zeRRoFIX      |
|           93 |     2595 | 2024-04-20 | Insilio              | W   | 0.936      | 0.372        | -                | 0.717 (0.250)    | -         |    15.63 | fear, jackasmo, jambo, s-chilla, zeRRoFIX      |
|           92 |     2650 | 2024-04-20 | Permitta Esports     | L   | 0.934      | -            | -                | -                | -         |   -13.12 | fear, jackasmo, jambo, s-chilla, zeRRoFIX      |
|           91 |     2710 | 2024-04-19 | ALTERNATE aTTaX      | L   | 0.929      | -            | -                | -                | -         |   -15.76 | fear, jackasmo, jambo, s-chilla, zeRRoFIX      |
|           90 |     2782 | 2024-04-18 | Permitta Esports     | W   | 0.922      | 0.500        | 0.029 (0.013)    | 1.000 (0.461)    | -         |    15.65 | fear, jackasmo, jambo, s-chilla, zeRRoFIX      |
|           89 |     2851 | 2024-04-17 | Sashi Esport         | W   | 0.916      | 0.371        | 0.172 (0.058)    | 1.000 (0.339)    | -         |    19.51 | fear, jackasmo, jambo, s-chilla, zeRRoFIX      |
|           88 |     2907 | 2024-04-16 | 500                  | L   | 0.910      | -            | -                | -                | -         |   -14.73 | fear, jackasmo, jambo, s-chilla, zeRRoFIX      |
|           87 |     2991 | 2024-04-14 | SINNERS Esports      | L   | 0.895      | -            | -                | -                | -         |    -9.54 | fear, jackasmo, jambo, s-chilla, zeRRoFIX      |
|           86 |     3078 | 2024-04-12 | Team PeeP            | W   | 0.883      | -            | -                | -                | -         |     3.58 | fear, jackasmo, jambo, s-chilla, zeRRoFIX      |
|           85 |     3512 | 2024-04-04 | HAVU Gaming          | W   | 0.829      | -            | -                | -                | -         |     6.83 | fear, jackasmo, jambo, s-chilla, zeRRoFIX      |
|           84 |     3600 | 2024-04-02 | BLEED Esports        | L   | 0.817      | -            | -                | -                | -         |    -4.84 | fear, jackasmo, jambo, s-chilla, zeRRoFIX      |
|           83 |     3654 | 2024-03-31 | FAVBET Team          | L   | 0.803      | -            | -                | -                | -         |   -13.26 | fear, jackasmo, jambo, s-chilla, zeRRoFIX      |
|           82 |     3686 | 2024-03-30 | Lazer Cats           | W   | 0.796      | -            | -                | -                | -         |     5.19 | fear, jackasmo, jambo, s-chilla, zeRRoFIX      |
|           81 |     3710 | 2024-03-29 | Natus Vincere Junior | L   | 0.789      | -            | -                | -                | -         |   -14.98 | fear, jackasmo, jambo, s-chilla, zeRRoFIX      |
|           80 |     3752 | 2024-03-28 | GamerLegion Academy  | L   | 0.782      | -            | -                | -                | -         |   -15.98 | fear, jackasmo, jambo, s-chilla, zeRRoFIX      |
|           79 |     3813 | 2024-03-27 | Rebels Gaming        | L   | 0.777      | -            | -                | -                | -         |    -8.30 | fear, jackasmo, jambo, s-chilla, zeRRoFIX      |
|           78 |     3885 | 2024-03-26 | Dynamo Eclot         | W   | 0.771      | -            | -                | -                | -         |    14.99 | fear, jackasmo, jambo, s-chilla, zeRRoFIX      |
|           77 |     3904 | 2024-03-26 | Natus Vincere Junior | W   | 0.768      | -            | -                | -                | -         |     7.52 | fear, jackasmo, jambo, s-chilla, zeRRoFIX      |
|           76 |     3948 | 2024-03-24 | ROSOMAHA             | W   | 0.756      | -            | -                | -                | -         |     2.55 | fear, jackasmo, jambo, s-chilla, zeRRoFIX      |
|           75 |     4011 | 2024-03-23 | Astralis Talent      | W   | 0.749      | -            | -                | -                | -         |    10.17 | fear, jackasmo, jambo, s-chilla, zeRRoFIX      |
|           74 |     4289 | 2024-03-17 | ex-K10               | W   | 0.709      | -            | -                | -                | -         |     7.39 | fear, jackasmo, jambo, s-chilla, zeRRoFIX      |
|           73 |     4297 | 2024-03-17 | Team Sampi           | L   | 0.708      | -            | -                | -                | -         |   -10.37 | fear, jackasmo, jambo, s-chilla, zeRRoFIX      |
|           72 |     4333 | 2024-03-16 | ex-Preasy Esport     | L   | 0.703      | -            | -                | -                | -         |    -9.53 | fear, jackasmo, jambo, s-chilla, zeRRoFIX      |
|           71 |     4443 | 2024-03-14 | Team Sampi           | W   | 0.689      | -            | -                | -                | -         |    11.38 | fear, jackasmo, jambo, s-chilla, zeRRoFIX      |
|           70 |     4449 | 2024-03-14 | NOM Esports          | W   | 0.688      | -            | -                | -                | -         |     1.69 | fear, jackasmo, jambo, s-chilla, zeRRoFIX      |
|           69 |     4572 | 2024-03-12 | Alliance             | W   | 0.676      | -            | -                | -                | -         |     8.91 | fear, jackasmo, jambo, s-chilla, zeRRoFIX      |
|           68 |     4630 | 2024-03-11 | MOUZ NXT             | L   | 0.669      | -            | -                | -                | -         |    -6.49 | fear, jackasmo, jambo, s-chilla, zeRRoFIX      |
|           67 |     4672 | 2024-03-10 | MOUZ NXT             | W   | 0.663      | 0.303        | 0.157 (0.032)    | -                | -         |    14.73 | fear, jackasmo, jambo, s-chilla, zeRRoFIX      |
|           66 |     4713 | 2024-03-09 | The Chosen Few       | L   | 0.657      | -            | -                | -                | -         |   -13.80 | fear, jackasmo, jambo, s-chilla, zeRRoFIX      |
|           65 |     4753 | 2024-03-08 | Team Spirit Academy  | L   | 0.650      | -            | -                | -                | -         |   -14.11 | fear, jackasmo, jambo, s-chilla, zeRRoFIX      |
|           64 |     4764 | 2024-03-08 | Entropiq             | W   | 0.649      | -            | -                | -                | -         |     4.27 | fear, jackasmo, jambo, s-chilla, zeRRoFIX      |
|           63 |     4814 | 2024-03-07 | AURA                 | W   | 0.644      | -            | -                | -                | -         |     3.69 | fear, jackasmo, jambo, s-chilla, zeRRoFIX      |
|           62 |     4824 | 2024-03-07 | Astralis Talent      | W   | 0.642      | -            | -                | -                | -         |     9.09 | fear, jackasmo, jambo, s-chilla, zeRRoFIX      |
|           61 |     4890 | 2024-03-06 | Permitta Esports     | L   | 0.636      | -            | -                | -                | -         |    -9.27 | fear, jackasmo, jambo, s-chilla, zeRRoFIX      |
|           60 |     4908 | 2024-03-06 | ex-K10               | W   | 0.636      | -            | -                | -                | -         |     6.72 | fear, jackasmo, jambo, s-chilla, zeRRoFIX      |
|           59 |     4947 | 2024-03-05 | B8                   | L   | 0.631      | -            | -                | -                | -         |    -5.39 | fear, jackasmo, jambo, s-chilla, zeRRoFIX      |
|           58 |     4971 | 2024-03-05 | Natus Vincere Junior | W   | 0.629      | -            | -                | -                | -         |     6.54 | fear, jackasmo, jambo, s-chilla, zeRRoFIX      |
|           57 |     4985 | 2024-03-04 | 9INE                 | W   | 0.625      | -            | -                | -                | -         |     2.73 | fear, jackasmo, jambo, s-chilla, zeRRoFIX      |
|           56 |     4998 | 2024-03-04 | ALTERNATE aTTaX      | W   | 0.625      | -            | -                | -                | -         |     9.91 | fear, jackasmo, jambo, s-chilla, zeRRoFIX      |
|           55 |     5051 | 2024-03-04 | ALTERNATE aTTaX      | W   | 0.622      | -            | -                | -                | -         |    10.43 | fear, jackasmo, jambo, s-chilla, zeRRoFIX      |
|           54 |     5197 | 2024-03-02 | Sashi Esport         | W   | 0.609      | -            | -                | -                | -         |     5.92 | fear, jackasmo, jambo, s-chilla, zeRRoFIX      |
|           53 |     5239 | 2024-03-01 | Nexus Gaming         | L   | 0.603      | -            | -                | -                | -         |    -9.76 | fear, jackasmo, jambo, s-chilla, zeRRoFIX      |
|           52 |     5273 | 2024-02-29 | L&G                  | W   | 0.597      | -            | -                | -                | -         |     1.56 | fear, jackasmo, jambo, s-chilla, zeRRoFIX      |
|           51 |     5340 | 2024-02-28 | NOM Esports          | L   | 0.588      | -            | -                | -                | -         |   -15.36 | fear, jackasmo, jambo, s-chilla, zeRRoFIX      |
|           50 |     5575 | 2024-02-24 | Sashi Esport         | W   | 0.562      | -            | -                | -                | -         |     5.03 | fear, jackasmo, jambo, s-chilla, zeRRoFIX      |
|           49 |     5663 | 2024-02-22 | Entropiq             | W   | 0.550      | -            | -                | -                | -         |     3.91 | fear, jackasmo, jambo, s-chilla, zeRRoFIX      |
|           48 |     5757 | 2024-02-20 | ARCRED               | L   | 0.537      | -            | -                | -                | -         |   -12.09 | fear, jackasmo, jambo, s-chilla, zeRRoFIX      |
|           47 |     5874 | 2024-02-18 | MOUZ NXT             | L   | 0.524      | -            | -                | -                | -         |    -4.86 | fear, jackasmo, jambo, s-chilla, zeRRoFIX      |
|           46 |     5899 | 2024-02-18 | Viperio              | L   | 0.522      | -            | -                | -                | -         |   -13.98 | fear, jackasmo, jambo, s-chilla, zeRRoFIX      |
|           45 |     6006 | 2024-02-16 | ex-K10               | W   | 0.508      | -            | -                | -                | -         |     4.95 | jackasmo, jambo, marat2k, s-chilla, zeRRoFIX   |
|           44 |     6049 | 2024-02-15 | Natus Vincere Junior | L   | 0.503      | -            | -                | -                | -         |   -11.29 | jackasmo, jambo, marat2k, s-chilla, zeRRoFIX   |
|           43 |     6156 | 2024-02-13 | Insilio              | W   | 0.490      | -            | -                | -                | -         |     7.61 | jackasmo, jambo, marat2k, s-chilla, zeRRoFIX   |
|           42 |     6196 | 2024-02-12 | Lemondogs            | W   | 0.484      | -            | -                | -                | -         |     1.78 | jackasmo, jambo, marat2k, s-chilla, zeRRoFIX   |
|           41 |     6232 | 2024-02-11 | V1dar Gaming         | W   | 0.477      | -            | -                | -                | -         |     2.50 | jackasmo, jambo, marat2k, s-chilla, zeRRoFIX   |
|           40 |     6248 | 2024-02-11 | Sashi Esport         | L   | 0.475      | -            | -                | -                | -         |   -13.27 | jackasmo, jambo, marat2k, s-chilla, zeRRoFIX   |
|           39 |     6312 | 2024-02-09 | BIG Academy          | L   | 0.462      | -            | -                | -                | -         |   -11.51 | jackasmo, jambo, marat2k, s-chilla, zeRRoFIX   |
|           38 |     6341 | 2024-02-08 | Monte Gen            | L   | 0.456      | -            | -                | -                | -         |   -10.32 | jackasmo, jambo, marat2k, s-chilla, zeRRoFIX   |
|           37 |     6342 | 2024-02-08 | BLEED Esports        | L   | 0.456      | -            | -                | -                | -         |    -3.31 | jackasmo, jambo, s-chilla, zeRRoFIX, Zinchenko |
|           36 |     6362 | 2024-02-07 | ROYALS               | W   | 0.450      | -            | -                | -                | -         |     1.11 | jackasmo, jambo, marat2k, s-chilla, zeRRoFIX   |
|           35 |     6458 | 2024-02-04 | DASH                 | L   | 0.431      | -            | -                | -                | -         |   -11.49 | jackasmo, jambo, marat2k, s-chilla, zeRRoFIX   |
|           34 |     6565 | 2024-02-03 | BIG Academy          | W   | 0.423      | -            | -                | -                | -         |     2.30 | jackasmo, jambo, marat2k, s-chilla, zeRRoFIX   |
|           33 |     6702 | 2024-01-31 | Kappa Bar            | W   | 0.404      | -            | -                | -                | -         |     0.84 | jackasmo, jambo, marat2k, s-chilla, zeRRoFIX   |
|           32 |     6800 | 2024-01-29 | 3DMAX                | L   | 0.392      | -            | -                | -                | -         |    -7.11 | jackasmo, jambo, marat2k, s-chilla, zeRRoFIX   |
|           31 |     6837 | 2024-01-29 | Alliance             | W   | 0.390      | -            | -                | -                | -         |     3.58 | jackasmo, jambo, s-chilla, zeRRoFIX, Zinchenko |
|           30 |     6888 | 2024-01-28 | Nexus Gaming         | W   | 0.382      | -            | -                | -                | -         |     5.14 | jackasmo, jambo, marat2k, s-chilla, zeRRoFIX   |
|           29 |     7265 | 2024-01-21 | ex-KRC Genk Esports  | W   | 0.338      | -            | -                | -                | -         |     1.35 | jackasmo, jambo, marat2k, s-chilla, zeRRoFIX   |
|           28 |     7495 | 2024-01-18 | MOUZ NXT             | L   | 0.315      | -            | -                | -                | -         |    -3.45 | jackasmo, jambo, marat2k, s-chilla, zeRRoFIX   |
|           27 |     7555 | 2024-01-17 | Into The Breach      | L   | 0.311      | -            | -                | -                | -         |    -8.12 | jackasmo, jambo, marat2k, s-chilla, zeRRoFIX   |
|           26 |     7612 | 2024-01-16 | Zero Tenacity        | L   | 0.306      | -            | -                | -                | -         |    -4.01 | jackasmo, jambo, marat2k, s-chilla, zeRRoFIX   |
|           25 |     7628 | 2024-01-16 | Rebels Gaming        | W   | 0.305      | -            | -                | -                | -         |     6.27 | jackasmo, jambo, marat2k, s-chilla, zeRRoFIX   |
|           24 |     7640 | 2024-01-16 | RUBY                 | W   | 0.305      | -            | -                | -                | -         |     3.59 | jackasmo, jambo, marat2k, s-chilla, zeRRoFIX   |
|           23 |     7657 | 2024-01-16 | happyend1            | W   | 0.304      | -            | -                | -                | -         |     0.32 | jackasmo, jambo, marat2k, s-chilla, zeRRoFIX   |
|           22 |     7718 | 2024-01-15 | ROSOMAHA             | W   | 0.295      | -            | -                | -                | -         |     0.92 | jackasmo, jambo, marat2k, s-chilla, zeRRoFIX   |
|           21 |     7758 | 2024-01-14 | Monte Gen            | L   | 0.288      | -            | -                | -                | -         |    -7.07 | jackasmo, jambo, marat2k, s-chilla, zeRRoFIX   |
|           20 |     7851 | 2024-01-12 | OG                   | L   | 0.278      | -            | -                | -                | -         |    -2.32 | jackasmo, jambo, marat2k, s-chilla, zeRRoFIX   |
|           19 |     7865 | 2024-01-12 | HAVU Gaming          | W   | 0.278      | -            | -                | -                | -         |     1.89 | jackasmo, jambo, marat2k, s-chilla, zeRRoFIX   |
|           18 |     8018 | 2024-01-10 | SINNERS Esports      | L   | 0.265      | -            | -                | -                | -         |    -4.30 | jackasmo, jambo, marat2k, s-chilla, zeRRoFIX   |
|           17 |     8142 | 2024-01-09 | MOUZ NXT             | W   | 0.255      | -            | -                | -                | -         |     5.19 | jackasmo, jambo, marat2k, s-chilla, zeRRoFIX   |
|           16 |     8222 | 2024-01-05 | Permitta Esports     | W   | 0.229      | -            | -                | -                | -         |     3.18 | jackasmo, jambo, marat2k, s-chilla, zeRRoFIX   |
|           15 |     8311 | 2023-12-28 | PSYCHOACTiVE         | L   | 0.177      | -            | -                | -                | -         |    -5.25 | jackasmo, jambo, marat2k, s-chilla, zeRRoFIX   |
|           14 |     8313 | 2023-12-28 | L&G                  | L   | 0.176      | -            | -                | -                | -         |    -5.21 | jackasmo, jambo, marat2k, s-chilla, zeRRoFIX   |
|           13 |     8318 | 2023-12-27 | PSYCHOACTiVE         | W   | 0.169      | -            | -                | -                | -         |     0.32 | jackasmo, jambo, marat2k, s-chilla, zeRRoFIX   |
|           12 |     8654 | 2023-12-16 | Astralis Talent      | L   | 0.095      | -            | -                | -                | -         |    -1.88 | jackasmo, jambo, marat2k, s-chilla, zeRRoFIX   |
|           11 |     8755 | 2023-12-15 | brazylijski luz      | L   | 0.089      | -            | -                | -                | -         |    -2.14 | jackasmo, jambo, marat2k, s-chilla, zeRRoFIX   |
|           10 |     8787 | 2023-12-14 | ex-KRC Genk Esports  | L   | 0.084      | -            | -                | -                | -         |    -2.37 | jackasmo, jambo, marat2k, s-chilla, zeRRoFIX   |
|            9 |     8835 | 2023-12-13 | Eternal Fire Academy | W   | 0.077      | -            | -                | -                | -         |     0.28 | jackasmo, jambo, marat2k, s-chilla, zeRRoFIX   |
|            8 |     8849 | 2023-12-13 | NOM Esports          | W   | 0.076      | -            | -                | -                | -         |     0.26 | jackasmo, jambo, marat2k, s-chilla, zeRRoFIX   |
|            7 |     8885 | 2023-12-12 | HyperSpirit          | W   | 0.070      | -            | -                | -                | -         |     0.42 | jackasmo, jambo, marat2k, s-chilla, zeRRoFIX   |
|            6 |     8922 | 2023-12-11 | UNiTY esports        | L   | 0.064      | -            | -                | -                | -         |    -1.28 | jackasmo, jambo, marat2k, s-chilla, zeRRoFIX   |
|            5 |     8983 | 2023-12-10 | The Witchers         | W   | 0.056      | -            | -                | -                | -         |     0.26 | jackasmo, jambo, marat2k, s-chilla, zeRRoFIX   |
|            4 |     9158 | 2023-12-07 | BLUEJAYS Lite        | W   | 0.038      | -            | -                | -                | -         |     0.05 | jackasmo, jambo, marat2k, s-chilla, zeRRoFIX   |
|            3 |     9235 | 2023-12-06 | M1X                  | W   | 0.029      | -            | -                | -                | -         |     0.08 | jackasmo, jambo, marat2k, s-chilla, zeRRoFIX   |
|            2 |     9295 | 2023-12-05 | WHYKICK Team         | W   | 0.024      | -            | -                | -                | -         |     0.02 | jackasmo, jambo, marat2k, s-chilla, zeRRoFIX   |
|            1 |     9498 | 2023-12-02 | detoks               | L   | 0.003      | -            | -                | -                | -         |    -0.07 | jackasmo, jambo, marat2k, s-chilla, zeRRoFIX   |

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
