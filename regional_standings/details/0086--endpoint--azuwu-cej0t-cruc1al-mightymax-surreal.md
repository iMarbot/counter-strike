### Roster Details<br />
Team Name: Endpoint<br />
Roster: AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [86](../standings_global.md)<br />
Regional Rank: [61]( ../standings_europe.md)<br />
Final Rank Value:  902.2<br />
<br />
Final Rank Value (902.2) = Starting Rank Value (952.2) + Head To Head Adjustments (-50.0)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.342[<sup>1</sup>](#table2)
- Bounty Collected: 0.396[<sup>2</sup>](#table1)
- Opponent Network: 0.329[<sup>2</sup>](#table1)
- LAN Wins: 0.020[<sup>2</sup>](#table1)

The average of these factors is 0.272<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 952.2
- 400 + ( ( 0.272 - 0.000 ) / ( 0.787 - 0.000 ) ) * 1600 = 952.2


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent             | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                     |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           86 |      195 | 2024-05-27 | Rhyno Esports        | L   | 1.000      | -            | -                | -                | -         |   -15.44 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal  |
|           85 |      361 | 2024-05-24 | Nemiga Gaming        | W   | 1.000      | 0.372        | 0.358 (0.133)    | 0.895 (0.333)    | 0 (0.000) |    23.44 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal  |
|           84 |      373 | 2024-05-24 | ALTERNATE aTTaX      | W   | 1.000      | 0.435        | 0.052 (0.023)    | 0.735 (0.319)    | 0 (0.000) |    16.34 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal  |
|           83 |      418 | 2024-05-23 | Permitta Esports     | W   | 1.000      | 0.372        | 0.025 (0.009)    | 1.000 (0.372)    | 0 (0.000) |    13.31 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal  |
|           82 |      473 | 2024-05-22 | DMS                  | W   | 1.000      | 0.372        | -                | 0.754 (0.281)    | 0 (0.000) |    20.06 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal  |
|           81 |      497 | 2024-05-22 | Permitta Esports     | L   | 1.000      | -            | -                | -                | -         |   -17.50 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal  |
|           80 |      610 | 2024-05-21 | 1win                 | W   | 1.000      | 0.372        | 0.050 (0.019)    | 0.898 (0.334)    | 0 (0.000) |    23.38 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal  |
|           79 |      620 | 2024-05-21 | Nexus Gaming         | L   | 1.000      | -            | -                | -                | -         |   -15.53 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal  |
|           78 |      635 | 2024-05-21 | RUBY                 | L   | 1.000      | -            | -                | -                | -         |   -10.30 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal  |
|           77 |      668 | 2024-05-20 | ARROW                | L   | 1.000      | -            | -                | -                | -         |   -22.39 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal  |
|           76 |      685 | 2024-05-20 | Lilmix               | L   | 1.000      | -            | -                | -                | -         |   -21.20 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal  |
|           75 |      706 | 2024-05-20 | Team PeeP            | W   | 1.000      | -            | -                | -                | 0 (0.000) |     5.31 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal  |
|           74 |      782 | 2024-05-19 | Sangal Esports       | L   | 1.000      | -            | -                | -                | -         |    -9.67 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal  |
|           73 |      870 | 2024-05-18 | Verdant              | L   | 1.000      | -            | -                | -                | -         |   -14.67 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal  |
|           72 |      874 | 2024-05-18 | Viperio              | W   | 1.000      | -            | -                | -                | 0 (0.000) |     9.33 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal  |
|           71 |      883 | 2024-05-18 | TYREECESIMPSON       | W   | 1.000      | -            | -                | -                | 0 (0.000) |     1.64 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal  |
|           70 |     1000 | 2024-05-17 | Zero Tenacity        | L   | 1.000      | -            | -                | -                | -         |   -11.98 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal  |
|           69 |     1075 | 2024-05-16 | Soda Gaming          | L   | 1.000      | -            | -                | -                | -         |   -26.45 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal  |
|           68 |     1180 | 2024-05-15 | Passion UA           | W   | 1.000      | 0.435        | 0.057 (0.025)    | 1.000 (0.435)    | -         |    14.30 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal  |
|           67 |     1210 | 2024-05-15 | Sashi Esport         | L   | 1.000      | -            | -                | -                | -         |    -4.65 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal  |
|           66 |     1267 | 2024-05-14 | GUN5 Esports         | W   | 1.000      | -            | -                | -                | -         |     7.46 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal  |
|           65 |     1273 | 2024-05-14 | ThunderFlash         | L   | 1.000      | -            | -                | -                | -         |   -19.06 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal  |
|           64 |     1302 | 2024-05-14 | ALTERNATE aTTaX      | L   | 1.000      | -            | -                | -                | -         |   -15.15 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal  |
|           63 |     1426 | 2024-05-11 | MOUZ NXT             | L   | 1.000      | -            | -                | -                | -         |   -12.40 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal  |
|           62 |     1585 | 2024-05-09 | PARIVISION           | W   | 1.000      | -            | -                | -                | -         |    14.41 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal  |
|           61 |     1694 | 2024-05-07 | los kogutos          | L   | 1.000      | -            | -                | -                | -         |   -18.24 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal  |
|           60 |     1798 | 2024-05-05 | SINNERS Esports      | L   | 1.000      | -            | -                | -                | -         |   -17.01 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal  |
|           59 |     1937 | 2024-05-02 | MOUZ NXT             | W   | 1.000      | 0.435        | 0.157 (0.068)    | 0.977 (0.424)    | -         |    19.45 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal  |
|           58 |     1957 | 2024-05-02 | Grannys Knockers     | W   | 1.000      | 0.384        | 0.017 (0.006)    | -                | -         |    10.13 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal  |
|           57 |     2061 | 2024-04-30 | ALTERNATE aTTaX      | W   | 1.000      | 0.143        | 0.052 (0.007)    | -                | -         |    14.50 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal  |
|           56 |     2067 | 2024-04-30 | ENCE Academy         | W   | 1.000      | -            | -                | -                | -         |     9.01 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal  |
|           55 |     2101 | 2024-04-29 | Nexus Gaming         | W   | 0.997      | 0.435        | -                | 0.857 (0.371)    | -         |    12.93 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal  |
|           54 |     2120 | 2024-04-29 | Alliance             | L   | 0.995      | -            | -                | -                | -         |   -18.38 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal  |
|           53 |     2431 | 2024-04-24 | SINNERS Esports      | W   | 0.963      | 0.384        | -                | 0.582 (0.215)    | -         |    18.66 | AZUWU, HS, MiGHTYMAX, sl3nd, Surreal       |
|           52 |     2934 | 2024-04-17 | EYEBALLERS           | W   | 0.915      | 0.384        | 0.012 (0.004)    | -                | -         |    13.02 | AZUWU, HS, MiGHTYMAX, sl3nd, Surreal       |
|           51 |     4493 | 2024-03-15 | ex-sYnck             | W   | 0.696      | -            | -                | -                | -         |     6.61 | AZUWU, HS, MiGHTYMAX, sl3nd, Surreal       |
|           50 |     4545 | 2024-03-14 | The Chosen Few       | L   | 0.691      | -            | -                | -                | -         |   -13.85 | AZUWU, MiGHTYMAX, sl3nd, Surreal, swicher  |
|           49 |     4694 | 2024-03-12 | Team Secret          | W   | 0.675      | -            | -                | -                | -         |     3.35 | AZUWU, HS, MiGHTYMAX, sl3nd, Surreal       |
|           48 |     4789 | 2024-03-10 | Nemiga Gaming        | L   | 0.664      | -            | -                | -                | -         |    -3.32 | AZUWU, MiGHTYMAX, sl3nd, Surreal, swicher  |
|           47 |     4866 | 2024-03-09 | BLEED Esports        | L   | 0.655      | -            | -                | -                | -         |    -3.58 | AZUWU, HS, MiGHTYMAX, sl3nd, Surreal       |
|           46 |     4941 | 2024-03-07 | kONO.ECF             | W   | 0.644      | 0.371        | -                | 0.853 (0.204)    | -         |    10.18 | AZUWU, MiGHTYMAX, sl3nd, Surreal, swicher  |
|           45 |     5014 | 2024-03-06 | V1dar Gaming         | W   | 0.637      | -            | -                | -                | -         |     4.80 | AZUWU, MiGHTYMAX, sl3nd, Surreal, swicher  |
|           44 |     5112 | 2024-03-05 | AURA                 | W   | 0.630      | -            | -                | -                | -         |     4.44 | AZUWU, MiGHTYMAX, sl3nd, Surreal, swicher  |
|           43 |     5194 | 2024-03-04 | JANO Esports         | W   | 0.623      | -            | -                | -                | -         |     6.25 | AZUWU, HS, MiGHTYMAX, sl3nd, Surreal       |
|           42 |     5291 | 2024-03-02 | GUN5 Esports         | L   | 0.611      | -            | -                | -                | -         |   -15.93 | AZUWU, MiGHTYMAX, sl3nd, Surreal, swicher  |
|           41 |     5375 | 2024-03-01 | NOM Esports          | W   | 0.604      | -            | -                | -                | -         |     3.67 | AZUWU, MiGHTYMAX, sl3nd, Surreal, swicher  |
|           40 |     5380 | 2024-03-01 | kONO.ECF             | W   | 0.604      | -            | -                | -                | -         |    10.40 | AZUWU, MiGHTYMAX, sl3nd, Surreal, swicher  |
|           39 |     5436 | 2024-02-29 | Metizport            | L   | 0.596      | -            | -                | -                | -         |    -7.04 | AZUWU, MiGHTYMAX, sl3nd, Surreal, swicher  |
|           38 |     5457 | 2024-02-28 | ARCRED               | W   | 0.591      | -            | -                | -                | -         |     6.30 | AZUWU, MiGHTYMAX, sl3nd, Surreal, swicher  |
|           37 |     5582 | 2024-02-26 | ALTERNATE aTTaX      | L   | 0.575      | -            | -                | -                | -         |    -8.49 | AZUWU, HS, MiGHTYMAX, sl3nd, Surreal       |
|           36 |     5857 | 2024-02-21 | Aurora Young Blud    | L   | 0.544      | -            | -                | -                | -         |   -11.88 | AZUWU, MiGHTYMAX, sl3nd, Surreal, swicher  |
|           35 |     6007 | 2024-02-19 | Nemiga Gaming        | L   | 0.530      | -            | -                | -                | -         |    -2.47 | AZUWU, MiGHTYMAX, sl3nd, Surreal, swicher  |
|           34 |     6155 | 2024-02-16 | CYBERSHOKE Esports   | W   | 0.511      | -            | -                | -                | -         |     2.21 | AZUWU, MiGHTYMAX, sl3nd, Surreal, swicher  |
|           33 |     6210 | 2024-02-15 | Golden Sword         | W   | 0.504      | -            | -                | -                | -         |     0.73 | AZUWU, MiGHTYMAX, sl3nd, Surreal, swicher  |
|           32 |     6394 | 2024-02-12 | The Chosen Few       | L   | 0.484      | -            | -                | -                | -         |   -11.31 | AZUWU, MiGHTYMAX, sl3nd, Surreal, swicher  |
|           31 |     6487 | 2024-02-09 | 3DMAX                | L   | 0.464      | -            | -                | -                | -         |    -7.47 | AZUWU, MiGHTYMAX, sl3nd, Surreal, swicher  |
|           30 |     6496 | 2024-02-09 | Fnatic               | L   | 0.463      | -            | -                | -                | -         |    -3.91 | AZUWU, MiGHTYMAX, sl3nd, Surreal, swicher  |
|           29 |     6516 | 2024-02-08 | esmagaB              | W   | 0.457      | -            | -                | -                | -         |     5.25 | AZUWU, MiGHTYMAX, sl3nd, Surreal, swicher  |
|           28 |     6547 | 2024-02-07 | GenOne               | L   | 0.451      | -            | -                | -                | -         |   -12.18 | AZUWU, MiGHTYMAX, sl3nd, Surreal, swicher  |
|           27 |     6560 | 2024-02-07 | Permitta Esports     | W   | 0.449      | 0.384        | 0.025 (0.004)    | -                | -         |     6.87 | AZUWU, MiGHTYMAX, sl3nd, Surreal, swicher  |
|           26 |     6575 | 2024-02-06 | UNiTY esports        | W   | 0.444      | -            | -                | -                | -         |     6.07 | AZUWU, MiGHTYMAX, sl3nd, Surreal, swicher  |
|           25 |     6731 | 2024-02-03 | Viperio              | W   | 0.424      | -            | -                | -                | -         |     1.76 | AZUWU, MiGHTYMAX, sl3nd, Surreal, swicher  |
|           24 |     6746 | 2024-02-03 | Verdant              | W   | 0.423      | -            | -                | -                | -         |     7.78 | AZUWU, MiGHTYMAX, sl3nd, Surreal, swicher  |
|           23 |     6755 | 2024-02-03 | XD                   | W   | 0.423      | -            | -                | -                | -         |     0.62 | AZUWU, MiGHTYMAX, sl3nd, Surreal, swicher  |
|           22 |     6804 | 2024-02-02 | FLuffy Gangsters     | W   | 0.417      | -            | -                | -                | -         |     1.59 | AZUWU, MiGHTYMAX, sl3nd, Surreal, swicher  |
|           21 |     6984 | 2024-01-30 | Entropiq             | W   | 0.396      | -            | -                | -                | -         |     2.29 | AZUWU, MiGHTYMAX, sl3nd, Surreal, swicher  |
|           20 |     7021 | 2024-01-29 | Nemiga Gaming        | L   | 0.392      | -            | -                | -                | -         |    -2.02 | AZUWU, MiGHTYMAX, sl3nd, Surreal, swicher  |
|           19 |     7778 | 2024-01-17 | Insilio              | L   | 0.312      | -            | -                | -                | -         |    -5.46 | AZUWU, MiGHTYMAX, sl3nd, Surreal, swicher  |
|           18 |     7806 | 2024-01-17 | Sashi Esport         | W   | 0.311      | -            | -                | -                | -         |     0.99 | AZUWU, MiGHTYMAX, sl3nd, Surreal, swicher  |
|           17 |     7871 | 2024-01-16 | Nexus Gaming         | L   | 0.305      | -            | -                | -                | -         |    -5.35 | AZUWU, MiGHTYMAX, sl3nd, Surreal, swicher  |
|           16 |     7878 | 2024-01-16 | 00 Nation            | W   | 0.305      | -            | -                | -                | -         |     0.74 | AZUWU, MiGHTYMAX, sl3nd, Surreal, swicher  |
|           15 |     7886 | 2024-01-16 | GUN5 Esports         | W   | 0.305      | -            | -                | -                | -         |     0.91 | AZUWU, MiGHTYMAX, sl3nd, Surreal, swicher  |
|           14 |     7927 | 2024-01-16 | XI Esport            | W   | 0.304      | -            | -                | -                | -         |     1.79 | AZUWU, MiGHTYMAX, sl3nd, Surreal, swicher  |
|           13 |     8199 | 2024-01-11 | ILIN                 | L   | 0.270      | -            | -                | -                | -         |    -7.72 | AZUWU, MiGHTYMAX, sl3nd, Surreal, swicher  |
|           12 |     8244 | 2024-01-10 | GRGECHI              | W   | 0.265      | -            | -                | -                | -         |     0.74 | AZUWU, MiGHTYMAX, sl3nd, Surreal, swicher  |
|           11 |     8276 | 2024-01-10 | zveri666             | W   | 0.265      | -            | -                | -                | -         |     0.36 | AZUWU, MiGHTYMAX, sl3nd, Surreal, swicher  |
|           10 |     8883 | 2023-12-16 | Eternal Fire Academy | W   | 0.096      | -            | -                | -                | 1 (0.096) |     0.48 | AZUWU, MiGHTYMAX, sl3nd, Surreal, swicher  |
|            9 |     9007 | 2023-12-15 | Onyx Ravens          | W   | 0.090      | -            | -                | -                | 1 (0.090) |     0.40 | AZUWU, MiGHTYMAX, sl3nd, Surreal, swicher  |
|            8 |     9286 | 2023-12-09 | RUSH B               | L   | 0.051      | -            | -                | -                | -         |    -1.19 | AZUWU, HeavyGod, MiGHTYMAX, sl3nd, Surreal |
|            7 |     9309 | 2023-12-09 | ex-Preasy Esport     | L   | 0.049      | -            | -                | -                | -         |    -0.86 | AZUWU, HeavyGod, MiGHTYMAX, sl3nd, Surreal |
|            6 |     9440 | 2023-12-07 | BIG Academy          | L   | 0.037      | -            | -                | -                | -         |    -0.91 | AZUWU, HeavyGod, MiGHTYMAX, sl3nd, Surreal |
|            5 |     9452 | 2023-12-07 | ex-sYnck             | W   | 0.036      | -            | -                | -                | -         |     0.26 | AZUWU, HeavyGod, MiGHTYMAX, sl3nd, Surreal |
|            4 |     9491 | 2023-12-06 | MOUZ NXT             | W   | 0.031      | -            | -                | -                | -         |     0.71 | AZUWU, HeavyGod, MiGHTYMAX, sl3nd, Surreal |
|            3 |     9528 | 2023-12-06 | Sprout               | L   | 0.028      | -            | -                | -                | -         |    -0.80 | AZUWU, HeavyGod, MiGHTYMAX, sl3nd, Surreal |
|            2 |     9563 | 2023-12-05 | ENTERPRISE esports   | W   | 0.025      | -            | -                | -                | -         |     0.39 | AZUWU, HeavyGod, MiGHTYMAX, sl3nd, Surreal |
|            1 |     9625 | 2023-12-04 | The Witchers         | W   | 0.016      | -            | -                | -                | -         |     0.10 | AZUWU, HeavyGod, MiGHTYMAX, sl3nd, Surreal |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($3,560.07)
- Divide that value by the 5th highest value among all rosters ($300,806.11)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-05-18 |      1.000 | $500.00        | $500.00         |
| 2024-05-12 |      1.000 | $2,000.00      | $2,000.00       |
| 2023-12-16 |      0.096 | $10,000.00     | $963.89         |
| 2023-12-13 |      0.077 | $1,250.00      | $96.18          |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
