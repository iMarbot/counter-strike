### Roster Details<br />
Team Name: Insilio<br />
Roster: faydett, FpSSS, Pipw, Polt, sugaR<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [73](../standings_global.md)<br />
Regional Rank: [50]( ../standings_europe.md)<br />
Final Rank Value:  931.6<br />
<br />
Final Rank Value (931.6) = Starting Rank Value (901.3) + Head To Head Adjustments (30.3)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.332[<sup>1</sup>](#table2)
- Bounty Collected: 0.392[<sup>2</sup>](#table1)
- Opponent Network: 0.260[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.246<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 901.3
- 400 + ( ( 0.246 - 0.000 ) / ( 0.786 - 0.000 ) ) * 1600 = 901.3


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent           | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                            |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           79 |      484 | 2024-05-22 | DMS                | L   | 1.000      | -            | -                | -                | -         |   -15.22 | faydett, FpSSS, Pipw, Polt, sugaR |
|           78 |      499 | 2024-05-22 | ThunderFlash       | L   | 1.000      | -            | -                | -                | -         |   -18.09 | faydett, FpSSS, Pipw, Polt, sugaR |
|           77 |      703 | 2024-05-20 | CYBERSHOKE Esports | W   | 1.000      | 0.372        | -                | 0.468 (0.174)    | 0 (0.000) |     6.56 | faydett, FpSSS, Pipw, Polt, sugaR |
|           76 |      711 | 2024-05-20 | V1dar Gaming       | W   | 1.000      | 0.372        | -                | 0.567 (0.211)    | 0 (0.000) |     8.48 | faydett, FpSSS, Pipw, Polt, sugaR |
|           75 |      764 | 2024-05-19 | ARCRED             | L   | 1.000      | -            | -                | -                | -         |   -17.92 | faydett, FpSSS, Pipw, Polt, sugaR |
|           74 |     1164 | 2024-05-15 | Young Gods         | W   | 1.000      | -            | -                | -                | 0 (0.000) |     2.62 | faydett, FpSSS, Pipw, Polt, sugaR |
|           73 |     1171 | 2024-05-15 | WOPA Esport        | W   | 1.000      | 0.372        | -                | 0.594 (0.221)    | 0 (0.000) |     7.94 | faydett, FpSSS, Pipw, Polt, sugaR |
|           72 |     1248 | 2024-05-14 | Young Ninjas       | W   | 1.000      | 0.372        | 0.043 (0.016)    | -                | 0 (0.000) |    14.33 | faydett, FpSSS, Pipw, Polt, sugaR |
|           71 |     1374 | 2024-05-12 | Team Space         | L   | 1.000      | -            | -                | -                | -         |   -20.69 | faydett, FpSSS, Pipw, Polt, sugaR |
|           70 |     1679 | 2024-05-07 | RUBY               | L   | 1.000      | -            | -                | -                | -         |   -17.04 | faydett, FpSSS, Pipw, Polt, sugaR |
|           69 |     1727 | 2024-05-06 | Zero Tenacity      | L   | 1.000      | -            | -                | -                | -         |   -13.86 | faydett, FpSSS, Pipw, Polt, sugaR |
|           68 |     1741 | 2024-05-06 | BLEED Esports      | L   | 1.000      | -            | -                | -                | -         |    -7.33 | faydett, FpSSS, Pipw, Polt, sugaR |
|           67 |     1880 | 2024-05-03 | Permitta Esports   | W   | 1.000      | 0.435        | 0.029 (0.012)    | 1.000 (0.435)    | 0 (0.000) |    11.22 | faydett, FpSSS, Pipw, Polt, sugaR |
|           66 |     1897 | 2024-05-03 | BetBoom Team       | L   | 1.000      | -            | -                | -                | -         |    -3.76 | faydett, FpSSS, Pipw, Polt, sugaR |
|           65 |     1976 | 2024-05-01 | OG                 | W   | 1.000      | 0.435        | 0.277 (0.120)    | -                | 0 (0.000) |    25.72 | faydett, FpSSS, Pipw, Polt, sugaR |
|           64 |     1994 | 2024-05-01 | Nexus Gaming       | W   | 1.000      | 0.435        | 0.014 (0.006)    | 0.825 (0.358)    | 0 (0.000) |    11.23 | faydett, FpSSS, Pipw, Polt, sugaR |
|           63 |     2078 | 2024-04-29 | HAVU Gaming        | L   | 0.996      | -            | -                | -                | -         |   -25.83 | faydett, FpSSS, Pipw, Polt, sugaR |
|           62 |     2177 | 2024-04-27 | ex-Guild Eagles    | W   | 0.983      | 0.435        | 0.015 (0.006)    | 0.475 (0.203)    | 0 (0.000) |    15.60 | faydett, FpSSS, Pipw, Polt, sugaR |
|           61 |     2192 | 2024-04-27 | Permitta Esports   | W   | 0.982      | -            | -                | -                | 0 (0.000) |    14.41 | faydett, FpSSS, Pipw, Polt, sugaR |
|           60 |     2263 | 2024-04-26 | ARCRED             | L   | 0.976      | -            | -                | -                | -         |   -19.48 | faydett, FpSSS, Pipw, Polt, sugaR |
|           59 |     2274 | 2024-04-26 | ENTERPRISE esports | W   | 0.976      | -            | -                | -                | -         |    11.44 | faydett, FpSSS, Pipw, Polt, sugaR |
|           58 |     2333 | 2024-04-25 | MOUZ NXT           | W   | 0.968      | 0.435        | 0.157 (0.066)    | 0.950 (0.399)    | -         |    19.07 | faydett, FpSSS, Pipw, Polt, sugaR |
|           57 |     2412 | 2024-04-23 | EYEBALLERS         | W   | 0.957      | 0.435        | -                | 0.508 (0.211)    | -         |    14.07 | faydett, FpSSS, Pipw, Polt, sugaR |
|           56 |     2522 | 2024-04-21 | FORZE Youngsters   | W   | 0.942      | -            | -                | -                | -         |     1.44 | faydett, FpSSS, Pipw, Polt, sugaR |
|           55 |     2527 | 2024-04-21 | Permitta Esports   | L   | 0.941      | -            | -                | -                | -         |   -14.30 | faydett, FpSSS, Pipw, Polt, sugaR |
|           54 |     2595 | 2024-04-20 | Passion UA         | L   | 0.936      | -            | -                | -                | -         |   -15.63 | faydett, FpSSS, Pipw, Polt, sugaR |
|           53 |     2817 | 2024-04-17 | Apeks              | L   | 0.918      | -            | -                | -                | -         |    -5.82 | faydett, FpSSS, Pipw, Polt, sugaR |
|           52 |     2984 | 2024-04-14 | LEON Esports       | W   | 0.896      | -            | -                | -                | -         |     6.26 | faydett, FpSSS, Pipw, Polt, sugaR |
|           51 |     3345 | 2024-04-07 | RUBY               | L   | 0.849      | -            | -                | -                | -         |   -15.11 | faydett, FpSSS, Pipw, Polt, sugaR |
|           50 |     3542 | 2024-04-03 | AMKAL ESPORTS      | L   | 0.824      | -            | -                | -                | -         |    -7.54 | faydett, FpSSS, Pipw, Polt, sugaR |
|           49 |     3590 | 2024-04-02 | ex-Guild Eagles    | W   | 0.817      | -            | -                | -                | -         |    11.96 | faydett, FpSSS, Pipw, Polt, sugaR |
|           48 |     3608 | 2024-04-02 | PARIVISION         | W   | 0.816      | -            | -                | -                | -         |    12.36 | faydett, FpSSS, Pipw, Polt, sugaR |
|           47 |     3867 | 2024-03-26 | 500                | L   | 0.771      | -            | -                | -                | -         |   -15.74 | faydett, FpSSS, Pipw, Polt, sugaR |
|           46 |     4215 | 2024-03-18 | Sashi Esport       | L   | 0.716      | -            | -                | -                | -         |    -9.74 | faydett, FpSSS, Pipw, Polt, sugaR |
|           45 |     4376 | 2024-03-15 | CYBERSHOKE Esports | W   | 0.698      | -            | -                | -                | -         |     5.23 | faydett, FpSSS, Pipw, Polt, sugaR |
|           44 |     4496 | 2024-03-13 | INGLORIOUS         | W   | 0.684      | -            | -                | -                | -         |     5.74 | faydett, FpSSS, Pipw, Polt, sugaR |
|           43 |     4619 | 2024-03-11 | 1win               | W   | 0.670      | 0.371        | 0.050 (0.013)    | 0.887 (0.221)    | -         |    10.44 | faydett, FpSSS, Pipw, Polt, sugaR |
|           42 |     4716 | 2024-03-09 | ex-K10             | W   | 0.657      | -            | -                | -                | -         |     6.26 | faydett, FpSSS, Pipw, Polt, sugaR |
|           41 |     4801 | 2024-03-07 | Sashi Esport       | L   | 0.645      | -            | -                | -                | -         |    -7.88 | faydett, FpSSS, Pipw, Polt, sugaR |
|           40 |     4871 | 2024-03-06 | The Chosen Few     | W   | 0.637      | -            | -                | -                | -         |     6.21 | faydett, FpSSS, Pipw, Polt, sugaR |
|           39 |     4951 | 2024-03-05 | Johnny Speeds      | L   | 0.631      | -            | -                | -                | -         |    -8.13 | faydett, FpSSS, Pipw, Polt, sugaR |
|           38 |     4956 | 2024-03-05 | Betera Esports     | W   | 0.631      | -            | -                | -                | -         |     7.16 | faydett, FpSSS, Pipw, Polt, sugaR |
|           37 |     4987 | 2024-03-04 | Pera Esports       | W   | 0.625      | -            | -                | -                | -         |     8.33 | faydett, FpSSS, Pipw, Polt, sugaR |
|           36 |     5019 | 2024-03-04 | kONO.ECF           | W   | 0.625      | -            | -                | -                | -         |     9.69 | faydett, FpSSS, Pipw, Polt, sugaR |
|           35 |     5142 | 2024-03-02 | brazylijski luz    | L   | 0.611      | -            | -                | -                | -         |   -14.03 | faydett, FpSSS, Pipw, Polt, sugaR |
|           34 |     5613 | 2024-02-23 | FORZE Youngsters   | W   | 0.557      | -            | -                | -                | -         |     2.95 | faydett, FpSSS, Pipw, Polt, sugaR |
|           33 |     5658 | 2024-02-22 | GenOne             | W   | 0.550      | -            | -                | -                | -         |     1.79 | faydett, FpSSS, Pipw, Polt, sugaR |
|           32 |     5665 | 2024-02-22 | Rhyno Esports      | W   | 0.550      | 0.371        | 0.029 (0.006)    | -                | -         |     9.50 | faydett, FpSSS, Pipw, Polt, sugaR |
|           31 |     5717 | 2024-02-21 | DMS                | L   | 0.543      | -            | -                | -                | -         |   -13.51 | faydett, FpSSS, Pipw, Polt, sugaR |
|           30 |     5730 | 2024-02-21 | Nemiga Gaming      | L   | 0.543      | -            | -                | -                | -         |    -2.59 | faydett, FpSSS, Pipw, Polt, sugaR |
|           29 |     6053 | 2024-02-15 | GUN5 Esports       | W   | 0.503      | -            | -                | -                | -         |     1.55 | faydett, FpSSS, Pipw, Polt, sugaR |
|           28 |     6090 | 2024-02-14 | esmagaB            | W   | 0.498      | -            | -                | -                | -         |     5.22 | faydett, FpSSS, Pipw, Polt, sugaR |
|           27 |     6156 | 2024-02-13 | Passion UA         | L   | 0.490      | -            | -                | -                | -         |    -7.61 | faydett, FpSSS, Pipw, Polt, sugaR |
|           26 |     6165 | 2024-02-13 | ILIN               | W   | 0.490      | -            | -                | -                | -         |     1.41 | faydett, FpSSS, Pipw, Polt, sugaR |
|           25 |     6306 | 2024-02-09 | Sashi Esport       | L   | 0.463      | -            | -                | -                | -         |    -5.51 | faydett, FpSSS, Pipw, Polt, sugaR |
|           24 |     6321 | 2024-02-08 | ex-Guild Eagles    | W   | 0.458      | -            | -                | -                | -         |     7.55 | faydett, FpSSS, Pipw, Polt, sugaR |
|           23 |     6338 | 2024-02-08 | AMKAL ESPORTS      | L   | 0.457      | -            | -                | -                | -         |    -2.69 | faydett, FpSSS, Pipw, Polt, sugaR |
|           22 |     6360 | 2024-02-07 | Sashi Esport       | W   | 0.451      | 0.371        | 0.172 (0.029)    | 1.000 (0.167)    | -         |     9.05 | faydett, FpSSS, Pipw, Polt, sugaR |
|           21 |     6428 | 2024-02-05 | Grindas            | W   | 0.437      | -            | -                | -                | -         |     1.00 | faydett, FpSSS, Pipw, Polt, sugaR |
|           20 |     6433 | 2024-02-05 | Gaimin Gladiators  | L   | 0.437      | -            | -                | -                | -         |    -2.11 | faydett, FpSSS, Pipw, Polt, sugaR |
|           19 |     6745 | 2024-01-30 | Sashi Esport       | L   | 0.398      | -            | -                | -                | -         |    -4.27 | faydett, FpSSS, Pipw, Polt, sugaR |
|           18 |     6753 | 2024-01-30 | Fnatic             | W   | 0.398      | 0.143        | 0.147 (0.008)    | -                | -         |     9.41 | faydett, FpSSS, Pipw, Polt, sugaR |
|           17 |     6763 | 2024-01-30 | EXO Clan           | W   | 0.397      | -            | -                | -                | -         |     7.14 | faydett, FpSSS, Pipw, Polt, sugaR |
|           16 |     6789 | 2024-01-29 | Team Sampi         | W   | 0.392      | -            | -                | -                | -         |     6.49 | faydett, FpSSS, Pipw, Polt, sugaR |
|           15 |     6791 | 2024-01-29 | kONO.ECF           | W   | 0.392      | -            | -                | -                | -         |     5.09 | faydett, FpSSS, Pipw, Polt, sugaR |
|           14 |     7492 | 2024-01-18 | AMKAL ESPORTS      | L   | 0.316      | -            | -                | -                | -         |    -1.73 | faydett, FpSSS, Pipw, Polt, sugaR |
|           13 |     7512 | 2024-01-17 | esmagaB            | W   | 0.312      | -            | -                | -                | -         |     4.08 | faydett, FpSSS, Pipw, Polt, sugaR |
|           12 |     7519 | 2024-01-17 | PARIVISION         | W   | 0.312      | -            | -                | -                | -         |     5.14 | faydett, FpSSS, Pipw, Polt, sugaR |
|           11 |     7529 | 2024-01-17 | Endpoint           | W   | 0.312      | -            | -                | -                | -         |     5.30 | faydett, FpSSS, Pipw, Polt, sugaR |
|           10 |     7552 | 2024-01-17 | ENTERPRISE esports | W   | 0.311      | -            | -                | -                | -         |     5.66 | faydett, FpSSS, Pipw, Polt, sugaR |
|            9 |     7655 | 2024-01-16 | Rebels Gaming      | L   | 0.304      | -            | -                | -                | -         |    -2.26 | faydett, FpSSS, Pipw, Polt, sugaR |
|            8 |     7784 | 2024-01-13 | Permitta Esports   | L   | 0.284      | -            | -                | -                | -         |    -3.91 | faydett, FpSSS, Pipw, Polt, sugaR |
|            7 |     7786 | 2024-01-13 | B8                 | W   | 0.283      | -            | -                | -                | -         |     0.90 | faydett, FpSSS, Pipw, Polt, sugaR |
|            6 |     7828 | 2024-01-12 | EYEBALLERS         | W   | 0.279      | -            | -                | -                | -         |     4.48 | faydett, FpSSS, Pipw, Polt, sugaR |
|            5 |     7861 | 2024-01-12 | Kappa Bar          | W   | 0.278      | -            | -                | -                | -         |     0.92 | faydett, FpSSS, Pipw, Polt, sugaR |
|            4 |     8509 | 2023-12-17 | ARCRED             | W   | 0.102      | -            | -                | -                | -         |     1.07 | faydett, FpSSS, Pipw, Polt, sugaR |
|            3 |     8602 | 2023-12-16 | Sangal Esports     | L   | 0.097      | -            | -                | -                | -         |    -0.79 | faydett, FpSSS, Pipw, Polt, sugaR |
|            2 |     8627 | 2023-12-16 | FORZE Youngsters   | W   | 0.096      | -            | -                | -                | -         |     0.57 | faydett, FpSSS, Pipw, Polt, sugaR |
|            1 |     8648 | 2023-12-16 | BebraFPL1          | W   | 0.095      | -            | -                | -                | -         |     0.30 | faydett, FpSSS, Pipw, Polt, sugaR |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($2,954.51)
- Divide that value by the 5th highest value among all rosters ($300,806.11)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-05-04 |      1.000 | $2,000.00      | $2,000.00       |
| 2024-03-25 |      0.764 | $1,250.00      | $954.51         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
