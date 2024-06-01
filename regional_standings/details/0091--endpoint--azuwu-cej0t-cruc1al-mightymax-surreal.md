### Roster Details<br />
Team Name: Endpoint<br />
Roster: AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [91](../standings_global.md)<br />
Regional Rank: [64]( ../standings_europe.md)<br />
Final Rank Value:  889.7<br />
<br />
Final Rank Value (889.7) = Starting Rank Value (946.7) + Head To Head Adjustments (-57.0)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.342[<sup>1</sup>](#table2)
- Bounty Collected: 0.398[<sup>2</sup>](#table1)
- Opponent Network: 0.315[<sup>2</sup>](#table1)
- LAN Wins: 0.020[<sup>2</sup>](#table1)

The average of these factors is 0.269<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 946.7
- 400 + ( ( 0.269 - 0.000 ) / ( 0.786 - 0.000 ) ) * 1600 = 946.7


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
|           83 |      187 | 2024-05-27 | Rhyno Esports        | L   | 1.000      | -            | -                | -                | -         |   -15.34 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal  |
|           82 |      352 | 2024-05-24 | Nemiga Gaming        | W   | 1.000      | 0.372        | 0.366 (0.136)    | 0.830 (0.309)    | 0 (0.000) |    23.70 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal  |
|           81 |      364 | 2024-05-24 | ALTERNATE aTTaX      | W   | 1.000      | 0.435        | 0.052 (0.022)    | 0.679 (0.295)    | 0 (0.000) |    16.79 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal  |
|           80 |      410 | 2024-05-23 | Permitta Esports     | W   | 1.000      | 0.372        | 0.029 (0.011)    | 1.000 (0.372)    | 0 (0.000) |    13.22 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal  |
|           79 |      467 | 2024-05-22 | DMS                  | W   | 1.000      | 0.372        | -                | 0.751 (0.280)    | 0 (0.000) |    20.36 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal  |
|           78 |      491 | 2024-05-22 | Permitta Esports     | L   | 1.000      | -            | -                | -                | -         |   -17.59 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal  |
|           77 |      599 | 2024-05-21 | 1win                 | W   | 1.000      | 0.372        | 0.050 (0.019)    | 0.887 (0.330)    | 0 (0.000) |    23.84 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal  |
|           76 |      609 | 2024-05-21 | Nexus Gaming         | L   | 1.000      | -            | -                | -                | -         |   -14.66 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal  |
|           75 |      624 | 2024-05-21 | RUBY                 | L   | 1.000      | -            | -                | -                | -         |    -9.87 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal  |
|           74 |      657 | 2024-05-20 | ARROW                | L   | 1.000      | -            | -                | -                | -         |   -21.13 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal  |
|           73 |      674 | 2024-05-20 | Lilmix               | L   | 1.000      | -            | -                | -                | -         |   -20.80 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal  |
|           72 |      695 | 2024-05-20 | Team PeeP            | W   | 1.000      | -            | -                | -                | 0 (0.000) |     5.71 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal  |
|           71 |      770 | 2024-05-19 | Sangal Esports       | L   | 1.000      | -            | -                | -                | -         |    -9.87 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal  |
|           70 |      858 | 2024-05-18 | Verdant              | L   | 1.000      | -            | -                | -                | -         |   -14.17 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal  |
|           69 |      862 | 2024-05-18 | Viperio              | W   | 1.000      | -            | -                | -                | 0 (0.000) |     9.94 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal  |
|           68 |      871 | 2024-05-18 | TYREECESIMPSON       | W   | 1.000      | -            | -                | -                | 0 (0.000) |     1.81 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal  |
|           67 |      988 | 2024-05-17 | Zero Tenacity        | L   | 1.000      | -            | -                | -                | -         |   -11.39 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal  |
|           66 |     1065 | 2024-05-16 | Soda Gaming          | L   | 1.000      | -            | -                | -                | -         |   -26.87 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal  |
|           65 |     1170 | 2024-05-15 | Passion UA           | W   | 1.000      | 0.435        | 0.057 (0.025)    | 1.000 (0.435)    | -         |    14.68 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal  |
|           64 |     1200 | 2024-05-15 | Sashi Esport         | L   | 1.000      | -            | -                | -                | -         |    -4.26 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal  |
|           63 |     1257 | 2024-05-14 | GUN5 Esports         | W   | 1.000      | -            | -                | -                | -         |     7.86 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal  |
|           62 |     1262 | 2024-05-14 | ThunderFlash         | L   | 1.000      | -            | -                | -                | -         |   -17.89 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal  |
|           61 |     1291 | 2024-05-14 | ALTERNATE aTTaX      | L   | 1.000      | -            | -                | -                | -         |   -14.32 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal  |
|           60 |     1413 | 2024-05-11 | MOUZ NXT             | L   | 1.000      | -            | -                | -                | -         |   -11.66 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal  |
|           59 |     1569 | 2024-05-09 | PARIVISION           | W   | 1.000      | -            | -                | -                | -         |    15.47 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal  |
|           58 |     1676 | 2024-05-07 | los kogutos          | L   | 1.000      | -            | -                | -                | -         |   -16.84 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal  |
|           57 |     1775 | 2024-05-05 | SINNERS Esports      | L   | 1.000      | -            | -                | -                | -         |   -16.27 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal  |
|           56 |     1911 | 2024-05-02 | MOUZ NXT             | W   | 1.000      | 0.435        | 0.157 (0.068)    | 0.950 (0.413)    | -         |    20.32 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal  |
|           55 |     1930 | 2024-05-02 | Grannys Knockers     | W   | 1.000      | 0.384        | 0.017 (0.006)    | -                | -         |    10.57 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal  |
|           54 |     2028 | 2024-04-30 | ALTERNATE aTTaX      | W   | 1.000      | 0.143        | 0.052 (0.007)    | -                | -         |    15.70 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal  |
|           53 |     2034 | 2024-04-30 | ENCE Academy         | W   | 1.000      | -            | -                | -                | -         |     9.95 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal  |
|           52 |     2066 | 2024-04-29 | Nexus Gaming         | W   | 0.997      | 0.435        | 0.014 (0.006)    | 0.825 (0.357)    | -         |    13.93 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal  |
|           51 |     2085 | 2024-04-29 | Alliance             | L   | 0.995      | -            | -                | -                | -         |   -17.09 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal  |
|           50 |     4384 | 2024-03-15 | ex-sYnck             | W   | 0.696      | -            | -                | -                | -         |     6.18 | AZUWU, HS, MiGHTYMAX, sl3nd, Surreal       |
|           49 |     4431 | 2024-03-14 | The Chosen Few       | L   | 0.691      | -            | -                | -                | -         |   -13.61 | AZUWU, MiGHTYMAX, sl3nd, Surreal, swicher  |
|           48 |     4573 | 2024-03-12 | Team Secret          | W   | 0.675      | -            | -                | -                | -         |     3.31 | AZUWU, HS, MiGHTYMAX, sl3nd, Surreal       |
|           47 |     4664 | 2024-03-10 | Nemiga Gaming        | L   | 0.664      | -            | -                | -                | -         |    -3.23 | AZUWU, MiGHTYMAX, sl3nd, Surreal, swicher  |
|           46 |     4812 | 2024-03-07 | kONO.ECF             | W   | 0.644      | 0.371        | -                | 0.778 (0.186)    | -         |    10.09 | AZUWU, MiGHTYMAX, sl3nd, Surreal, swicher  |
|           45 |     4883 | 2024-03-06 | V1dar Gaming         | W   | 0.637      | -            | -                | -                | -         |     4.60 | AZUWU, MiGHTYMAX, sl3nd, Surreal, swicher  |
|           44 |     4968 | 2024-03-05 | AURA                 | W   | 0.630      | -            | -                | -                | -         |     4.39 | AZUWU, MiGHTYMAX, sl3nd, Surreal, swicher  |
|           43 |     5048 | 2024-03-04 | JANO Esports         | W   | 0.623      | -            | -                | -                | -         |     6.14 | AZUWU, HS, MiGHTYMAX, sl3nd, Surreal       |
|           42 |     5143 | 2024-03-02 | GUN5 Esports         | L   | 0.611      | -            | -                | -                | -         |   -16.03 | AZUWU, MiGHTYMAX, sl3nd, Surreal, swicher  |
|           41 |     5226 | 2024-03-01 | NOM Esports          | W   | 0.604      | -            | -                | -                | -         |     3.69 | AZUWU, MiGHTYMAX, sl3nd, Surreal, swicher  |
|           40 |     5231 | 2024-03-01 | kONO.ECF             | W   | 0.604      | 0.371        | -                | 0.778 (0.174)    | -         |     9.88 | AZUWU, MiGHTYMAX, sl3nd, Surreal, swicher  |
|           39 |     5286 | 2024-02-29 | Metizport            | L   | 0.596      | -            | -                | -                | -         |    -7.06 | AZUWU, MiGHTYMAX, sl3nd, Surreal, swicher  |
|           38 |     5306 | 2024-02-28 | ARCRED               | W   | 0.591      | -            | -                | -                | -         |     6.35 | AZUWU, MiGHTYMAX, sl3nd, Surreal, swicher  |
|           37 |     5424 | 2024-02-26 | ALTERNATE aTTaX      | L   | 0.575      | -            | -                | -                | -         |    -7.94 | AZUWU, HS, MiGHTYMAX, sl3nd, Surreal       |
|           36 |     5694 | 2024-02-21 | Aurora Young Blud    | L   | 0.544      | -            | -                | -                | -         |   -11.92 | AZUWU, MiGHTYMAX, sl3nd, Surreal, swicher  |
|           35 |     5835 | 2024-02-19 | Nemiga Gaming        | L   | 0.530      | -            | -                | -                | -         |    -2.35 | AZUWU, MiGHTYMAX, sl3nd, Surreal, swicher  |
|           34 |     5982 | 2024-02-16 | CYBERSHOKE Esports   | W   | 0.511      | -            | -                | -                | -         |     3.87 | AZUWU, MiGHTYMAX, sl3nd, Surreal, swicher  |
|           33 |     6033 | 2024-02-15 | Golden Sword         | W   | 0.504      | -            | -                | -                | -         |     0.75 | AZUWU, MiGHTYMAX, sl3nd, Surreal, swicher  |
|           32 |     6207 | 2024-02-12 | The Chosen Few       | L   | 0.484      | -            | -                | -                | -         |   -10.93 | AZUWU, MiGHTYMAX, sl3nd, Surreal, swicher  |
|           31 |     6299 | 2024-02-09 | 3DMAX                | L   | 0.464      | -            | -                | -                | -         |    -7.41 | AZUWU, MiGHTYMAX, sl3nd, Surreal, swicher  |
|           30 |     6308 | 2024-02-09 | Fnatic               | L   | 0.463      | -            | -                | -                | -         |    -3.86 | AZUWU, MiGHTYMAX, sl3nd, Surreal, swicher  |
|           29 |     6328 | 2024-02-08 | esmagaB              | W   | 0.457      | -            | -                | -                | -         |     5.14 | AZUWU, MiGHTYMAX, sl3nd, Surreal, swicher  |
|           28 |     6355 | 2024-02-07 | GenOne               | L   | 0.451      | -            | -                | -                | -         |   -12.15 | AZUWU, MiGHTYMAX, sl3nd, Surreal, swicher  |
|           27 |     6366 | 2024-02-07 | Permitta Esports     | W   | 0.449      | 0.384        | 0.029 (0.005)    | -                | -         |     6.83 | AZUWU, MiGHTYMAX, sl3nd, Surreal, swicher  |
|           26 |     6379 | 2024-02-06 | UNiTY esports        | W   | 0.444      | -            | -                | -                | -         |     6.14 | AZUWU, MiGHTYMAX, sl3nd, Surreal, swicher  |
|           25 |     6528 | 2024-02-03 | Viperio              | W   | 0.424      | -            | -                | -                | -         |     1.77 | AZUWU, MiGHTYMAX, sl3nd, Surreal, swicher  |
|           24 |     6543 | 2024-02-03 | Verdant              | W   | 0.423      | -            | -                | -                | -         |     7.80 | AZUWU, MiGHTYMAX, sl3nd, Surreal, swicher  |
|           23 |     6552 | 2024-02-03 | XD                   | W   | 0.423      | -            | -                | -                | -         |     0.64 | AZUWU, MiGHTYMAX, sl3nd, Surreal, swicher  |
|           22 |     6601 | 2024-02-02 | ex-FLuffy Gangsters  | W   | 0.417      | -            | -                | -                | -         |     1.14 | AZUWU, MiGHTYMAX, sl3nd, Surreal, swicher  |
|           21 |     6768 | 2024-01-30 | Entropiq             | W   | 0.396      | -            | -                | -                | -         |     2.27 | AZUWU, MiGHTYMAX, sl3nd, Surreal, swicher  |
|           20 |     6805 | 2024-01-29 | Nemiga Gaming        | L   | 0.392      | -            | -                | -                | -         |    -1.89 | AZUWU, MiGHTYMAX, sl3nd, Surreal, swicher  |
|           19 |     7529 | 2024-01-17 | Insilio              | L   | 0.312      | -            | -                | -                | -         |    -5.30 | AZUWU, MiGHTYMAX, sl3nd, Surreal, swicher  |
|           18 |     7557 | 2024-01-17 | Sashi Esport         | W   | 0.311      | -            | -                | -                | -         |     1.01 | AZUWU, MiGHTYMAX, sl3nd, Surreal, swicher  |
|           17 |     7622 | 2024-01-16 | Nexus Gaming         | L   | 0.305      | -            | -                | -                | -         |    -5.07 | AZUWU, MiGHTYMAX, sl3nd, Surreal, swicher  |
|           16 |     7629 | 2024-01-16 | 00 Nation            | W   | 0.305      | -            | -                | -                | -         |     0.76 | AZUWU, MiGHTYMAX, sl3nd, Surreal, swicher  |
|           15 |     7637 | 2024-01-16 | GUN5 Esports         | W   | 0.305      | -            | -                | -                | -         |     0.92 | AZUWU, MiGHTYMAX, sl3nd, Surreal, swicher  |
|           14 |     7678 | 2024-01-16 | XI Esport            | W   | 0.304      | -            | -                | -                | -         |     1.81 | AZUWU, MiGHTYMAX, sl3nd, Surreal, swicher  |
|           13 |     7946 | 2024-01-11 | ILIN                 | L   | 0.270      | -            | -                | -                | -         |    -7.71 | AZUWU, MiGHTYMAX, sl3nd, Surreal, swicher  |
|           12 |     7990 | 2024-01-10 | GRGECHI              | W   | 0.265      | -            | -                | -                | -         |     0.77 | AZUWU, MiGHTYMAX, sl3nd, Surreal, swicher  |
|           11 |     8022 | 2024-01-10 | zveri666             | W   | 0.265      | -            | -                | -                | -         |     0.38 | AZUWU, MiGHTYMAX, sl3nd, Surreal, swicher  |
|           10 |     8622 | 2023-12-16 | Eternal Fire Academy | W   | 0.096      | -            | -                | -                | 1 (0.096) |     0.50 | AZUWU, MiGHTYMAX, sl3nd, Surreal, swicher  |
|            9 |     8745 | 2023-12-15 | Onyx Ravens          | W   | 0.090      | -            | -                | -                | 1 (0.090) |     0.41 | AZUWU, MiGHTYMAX, sl3nd, Surreal, swicher  |
|            8 |     9020 | 2023-12-09 | RUSH B               | L   | 0.051      | -            | -                | -                | -         |    -1.18 | AZUWU, HeavyGod, MiGHTYMAX, sl3nd, Surreal |
|            7 |     9042 | 2023-12-09 | ex-Preasy Esport     | L   | 0.049      | -            | -                | -                | -         |    -0.85 | AZUWU, HeavyGod, MiGHTYMAX, sl3nd, Surreal |
|            6 |     9167 | 2023-12-07 | ALTERNATE aTTaX      | L   | 0.037      | -            | -                | -                | -         |    -0.53 | AZUWU, HeavyGod, MiGHTYMAX, sl3nd, Surreal |
|            5 |     9179 | 2023-12-07 | ex-sYnck             | W   | 0.036      | -            | -                | -                | -         |     0.23 | AZUWU, HeavyGod, MiGHTYMAX, sl3nd, Surreal |
|            4 |     9211 | 2023-12-06 | MOUZ NXT             | W   | 0.031      | -            | -                | -                | -         |     0.71 | AZUWU, HeavyGod, MiGHTYMAX, sl3nd, Surreal |
|            3 |     9247 | 2023-12-06 | Sprout               | L   | 0.028      | -            | -                | -                | -         |    -0.80 | AZUWU, HeavyGod, MiGHTYMAX, sl3nd, Surreal |
|            2 |     9281 | 2023-12-05 | ENTERPRISE esports   | W   | 0.025      | -            | -                | -                | -         |     0.38 | AZUWU, HeavyGod, MiGHTYMAX, sl3nd, Surreal |
|            1 |     9343 | 2023-12-04 | The Witchers         | W   | 0.016      | -            | -                | -                | -         |     0.10 | AZUWU, HeavyGod, MiGHTYMAX, sl3nd, Surreal |

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
