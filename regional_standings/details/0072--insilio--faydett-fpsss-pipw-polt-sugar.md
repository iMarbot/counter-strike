### Roster Details<br />
Team Name: Insilio<br />
Roster: faydett, FpSSS, Pipw, Polt, sugaR<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [72](../standings_global.md)<br />
Regional Rank: [50]( ../standings_europe.md)<br />
Final Rank Value:  932.9<br />
<br />
Final Rank Value (932.9) = Starting Rank Value (892.8) + Head To Head Adjustments (40.2)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.315[<sup>1</sup>](#table2)
- Bounty Collected: 0.391[<sup>2</sup>](#table1)
- Opponent Network: 0.264[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.242<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 892.8
- 400 + ( ( 0.242 - 0.000 ) / ( 0.787 - 0.000 ) ) * 1600 = 892.8


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
|           79 |      490 | 2024-05-22 | DMS                | L   | 1.000      | -            | -                | -                | -         |   -15.03 | faydett, FpSSS, Pipw, Polt, sugaR |
|           78 |      506 | 2024-05-22 | ThunderFlash       | L   | 1.000      | -            | -                | -                | -         |   -18.34 | faydett, FpSSS, Pipw, Polt, sugaR |
|           77 |      715 | 2024-05-20 | CYBERSHOKE Esports | W   | 1.000      | 0.372        | -                | 0.468 (0.174)    | 0 (0.000) |     6.71 | faydett, FpSSS, Pipw, Polt, sugaR |
|           76 |      723 | 2024-05-20 | V1dar Gaming       | W   | 1.000      | 0.372        | -                | 0.595 (0.221)    | 0 (0.000) |     8.74 | faydett, FpSSS, Pipw, Polt, sugaR |
|           75 |      776 | 2024-05-19 | ARCRED             | L   | 1.000      | -            | -                | -                | -         |   -17.89 | faydett, FpSSS, Pipw, Polt, sugaR |
|           74 |     1174 | 2024-05-15 | Young Gods         | W   | 1.000      | -            | -                | -                | 0 (0.000) |     2.60 | faydett, FpSSS, Pipw, Polt, sugaR |
|           73 |     1181 | 2024-05-15 | WOPA Esport        | W   | 1.000      | 0.372        | -                | 0.594 (0.221)    | 0 (0.000) |     8.03 | faydett, FpSSS, Pipw, Polt, sugaR |
|           72 |     1258 | 2024-05-14 | Young Ninjas       | W   | 1.000      | 0.372        | 0.043 (0.016)    | -                | 0 (0.000) |    12.98 | faydett, FpSSS, Pipw, Polt, sugaR |
|           71 |     1387 | 2024-05-12 | Team Space         | L   | 1.000      | -            | -                | -                | -         |   -20.74 | faydett, FpSSS, Pipw, Polt, sugaR |
|           70 |     1697 | 2024-05-07 | RUBY               | L   | 1.000      | -            | -                | -                | -         |   -17.00 | faydett, FpSSS, Pipw, Polt, sugaR |
|           69 |     1749 | 2024-05-06 | Zero Tenacity      | L   | 1.000      | -            | -                | -                | -         |   -13.79 | faydett, FpSSS, Pipw, Polt, sugaR |
|           68 |     1764 | 2024-05-06 | BLEED Esports      | L   | 1.000      | -            | -                | -                | -         |    -7.46 | faydett, FpSSS, Pipw, Polt, sugaR |
|           67 |     1905 | 2024-05-03 | Permitta Esports   | W   | 1.000      | 0.435        | 0.025 (0.011)    | 1.000 (0.435)    | 0 (0.000) |    12.22 | faydett, FpSSS, Pipw, Polt, sugaR |
|           66 |     1922 | 2024-05-03 | BetBoom Team       | L   | 1.000      | -            | -                | -                | -         |    -3.81 | faydett, FpSSS, Pipw, Polt, sugaR |
|           65 |     2004 | 2024-05-01 | OG                 | W   | 1.000      | 0.435        | 0.277 (0.120)    | -                | 0 (0.000) |    25.62 | faydett, FpSSS, Pipw, Polt, sugaR |
|           64 |     2024 | 2024-05-01 | Nexus Gaming       | W   | 1.000      | 0.435        | -                | 0.857 (0.373)    | 0 (0.000) |    11.44 | faydett, FpSSS, Pipw, Polt, sugaR |
|           63 |     2113 | 2024-04-29 | HAVU Gaming        | L   | 0.996      | -            | -                | -                | -         |   -25.85 | faydett, FpSSS, Pipw, Polt, sugaR |
|           62 |     2212 | 2024-04-27 | ex-Guild Eagles    | W   | 0.983      | 0.435        | 0.015 (0.006)    | 0.475 (0.203)    | 0 (0.000) |    15.77 | faydett, FpSSS, Pipw, Polt, sugaR |
|           61 |     2227 | 2024-04-27 | Permitta Esports   | W   | 0.982      | -            | -                | -                | 0 (0.000) |    15.05 | faydett, FpSSS, Pipw, Polt, sugaR |
|           60 |     2299 | 2024-04-26 | ARCRED             | L   | 0.976      | -            | -                | -                | -         |   -19.46 | faydett, FpSSS, Pipw, Polt, sugaR |
|           59 |     2311 | 2024-04-26 | ENTERPRISE esports | W   | 0.976      | -            | -                | -                | -         |    12.31 | faydett, FpSSS, Pipw, Polt, sugaR |
|           58 |     2374 | 2024-04-25 | MOUZ NXT           | W   | 0.968      | 0.435        | 0.157 (0.066)    | 0.977 (0.411)    | -         |    19.36 | faydett, FpSSS, Pipw, Polt, sugaR |
|           57 |     2459 | 2024-04-23 | EYEBALLERS         | W   | 0.957      | 0.435        | 0.012 (0.005)    | 0.508 (0.211)    | -         |    13.36 | faydett, FpSSS, Pipw, Polt, sugaR |
|           56 |     2575 | 2024-04-21 | FORZE Youngsters   | W   | 0.942      | -            | -                | -                | -         |     1.44 | faydett, FpSSS, Pipw, Polt, sugaR |
|           55 |     2580 | 2024-04-21 | Permitta Esports   | L   | 0.941      | -            | -                | -                | -         |   -13.83 | faydett, FpSSS, Pipw, Polt, sugaR |
|           54 |     2649 | 2024-04-20 | Passion UA         | L   | 0.936      | -            | -                | -                | -         |   -14.81 | faydett, FpSSS, Pipw, Polt, sugaR |
|           53 |     2874 | 2024-04-17 | Apeks              | L   | 0.918      | -            | -                | -                | -         |    -5.86 | faydett, FpSSS, Pipw, Polt, sugaR |
|           52 |     3049 | 2024-04-14 | LEON Esports       | W   | 0.896      | -            | -                | -                | -         |     6.40 | faydett, FpSSS, Pipw, Polt, sugaR |
|           51 |     3426 | 2024-04-07 | RUBY               | L   | 0.849      | -            | -                | -                | -         |   -14.96 | faydett, FpSSS, Pipw, Polt, sugaR |
|           50 |     3629 | 2024-04-03 | AMKAL ESPORTS      | L   | 0.824      | -            | -                | -                | -         |    -7.45 | faydett, FpSSS, Pipw, Polt, sugaR |
|           49 |     3679 | 2024-04-02 | ex-Guild Eagles    | W   | 0.817      | -            | -                | -                | -         |    12.24 | faydett, FpSSS, Pipw, Polt, sugaR |
|           48 |     3698 | 2024-04-02 | PARIVISION         | W   | 0.816      | -            | -                | -                | -         |    12.12 | faydett, FpSSS, Pipw, Polt, sugaR |
|           47 |     3964 | 2024-03-26 | 500                | L   | 0.771      | -            | -                | -                | -         |   -15.53 | faydett, FpSSS, Pipw, Polt, sugaR |
|           46 |     4320 | 2024-03-18 | Sashi Esport       | L   | 0.716      | -            | -                | -                | -         |    -9.40 | faydett, FpSSS, Pipw, Polt, sugaR |
|           45 |     4484 | 2024-03-15 | CYBERSHOKE Esports | W   | 0.698      | -            | -                | -                | -         |     3.46 | faydett, FpSSS, Pipw, Polt, sugaR |
|           44 |     4611 | 2024-03-13 | INGLORIOUS         | W   | 0.684      | -            | -                | -                | -         |     5.87 | faydett, FpSSS, Pipw, Polt, sugaR |
|           43 |     4741 | 2024-03-11 | 1win               | W   | 0.670      | 0.371        | 0.050 (0.013)    | 0.898 (0.223)    | -         |    10.10 | faydett, FpSSS, Pipw, Polt, sugaR |
|           42 |     4841 | 2024-03-09 | ex-K10             | W   | 0.657      | -            | -                | -                | -         |     6.45 | faydett, FpSSS, Pipw, Polt, sugaR |
|           41 |     4930 | 2024-03-07 | Sashi Esport       | L   | 0.645      | -            | -                | -                | -         |    -7.79 | faydett, FpSSS, Pipw, Polt, sugaR |
|           40 |     5002 | 2024-03-06 | The Chosen Few     | W   | 0.637      | -            | -                | -                | -         |     5.99 | faydett, FpSSS, Pipw, Polt, sugaR |
|           39 |     5091 | 2024-03-05 | Johnny Speeds      | L   | 0.631      | -            | -                | -                | -         |    -8.07 | faydett, FpSSS, Pipw, Polt, sugaR |
|           38 |     5099 | 2024-03-05 | Betera Esports     | W   | 0.631      | -            | -                | -                | -         |     7.25 | faydett, FpSSS, Pipw, Polt, sugaR |
|           37 |     5133 | 2024-03-04 | Pera Esports       | W   | 0.625      | -            | -                | -                | -         |     8.36 | faydett, FpSSS, Pipw, Polt, sugaR |
|           36 |     5165 | 2024-03-04 | kONO.ECF           | W   | 0.625      | -            | -                | -                | -         |    10.13 | faydett, FpSSS, Pipw, Polt, sugaR |
|           35 |     5290 | 2024-03-02 | brazylijski luz    | L   | 0.611      | -            | -                | -                | -         |   -13.85 | faydett, FpSSS, Pipw, Polt, sugaR |
|           34 |     5773 | 2024-02-23 | FORZE Youngsters   | W   | 0.557      | -            | -                | -                | -         |     3.47 | faydett, FpSSS, Pipw, Polt, sugaR |
|           33 |     5818 | 2024-02-22 | GenOne             | W   | 0.550      | -            | -                | -                | -         |     1.84 | faydett, FpSSS, Pipw, Polt, sugaR |
|           32 |     5826 | 2024-02-22 | Rhyno Esports      | W   | 0.550      | 0.371        | 0.029 (0.006)    | -                | -         |     9.61 | faydett, FpSSS, Pipw, Polt, sugaR |
|           31 |     5880 | 2024-02-21 | DMS                | L   | 0.543      | -            | -                | -                | -         |   -13.28 | faydett, FpSSS, Pipw, Polt, sugaR |
|           30 |     5895 | 2024-02-21 | Nemiga Gaming      | L   | 0.543      | -            | -                | -                | -         |    -2.66 | faydett, FpSSS, Pipw, Polt, sugaR |
|           29 |     6234 | 2024-02-15 | GUN5 Esports       | W   | 0.503      | -            | -                | -                | -         |     1.56 | faydett, FpSSS, Pipw, Polt, sugaR |
|           28 |     6271 | 2024-02-14 | esmagaB            | W   | 0.498      | -            | -                | -                | -         |     5.46 | faydett, FpSSS, Pipw, Polt, sugaR |
|           27 |     6341 | 2024-02-13 | Passion UA         | L   | 0.490      | -            | -                | -                | -         |    -7.38 | faydett, FpSSS, Pipw, Polt, sugaR |
|           26 |     6350 | 2024-02-13 | ILIN               | W   | 0.490      | -            | -                | -                | -         |     1.44 | faydett, FpSSS, Pipw, Polt, sugaR |
|           25 |     6494 | 2024-02-09 | Sashi Esport       | L   | 0.463      | -            | -                | -                | -         |    -5.55 | faydett, FpSSS, Pipw, Polt, sugaR |
|           24 |     6509 | 2024-02-08 | ex-Guild Eagles    | W   | 0.458      | -            | -                | -                | -         |     7.75 | faydett, FpSSS, Pipw, Polt, sugaR |
|           23 |     6526 | 2024-02-08 | AMKAL ESPORTS      | L   | 0.457      | -            | -                | -                | -         |    -2.63 | faydett, FpSSS, Pipw, Polt, sugaR |
|           22 |     6554 | 2024-02-07 | Sashi Esport       | W   | 0.451      | 0.371        | 0.154 (0.026)    | 1.000 (0.167)    | -         |     9.01 | faydett, FpSSS, Pipw, Polt, sugaR |
|           21 |     6628 | 2024-02-05 | Grannys Knockers   | W   | 0.437      | -            | -                | -                | -         |     4.17 | faydett, FpSSS, Pipw, Polt, sugaR |
|           20 |     6633 | 2024-02-05 | Gaimin Gladiators  | L   | 0.437      | -            | -                | -                | -         |    -2.03 | faydett, FpSSS, Pipw, Polt, sugaR |
|           19 |     6958 | 2024-01-30 | Sashi Esport       | L   | 0.398      | -            | -                | -                | -         |    -4.16 | faydett, FpSSS, Pipw, Polt, sugaR |
|           18 |     6967 | 2024-01-30 | Fnatic             | W   | 0.398      | 0.143        | 0.147 (0.008)    | -                | -         |     9.51 | faydett, FpSSS, Pipw, Polt, sugaR |
|           17 |     6979 | 2024-01-30 | EXO Clan           | W   | 0.397      | -            | -                | -                | -         |     7.43 | faydett, FpSSS, Pipw, Polt, sugaR |
|           16 |     7005 | 2024-01-29 | Team Sampi         | W   | 0.392      | -            | -                | -                | -         |     6.69 | faydett, FpSSS, Pipw, Polt, sugaR |
|           15 |     7007 | 2024-01-29 | kONO.ECF           | W   | 0.392      | -            | -                | -                | -         |     5.57 | faydett, FpSSS, Pipw, Polt, sugaR |
|           14 |     7741 | 2024-01-18 | AMKAL ESPORTS      | L   | 0.316      | -            | -                | -                | -         |    -1.66 | faydett, FpSSS, Pipw, Polt, sugaR |
|           13 |     7761 | 2024-01-17 | esmagaB            | W   | 0.312      | -            | -                | -                | -         |     4.23 | faydett, FpSSS, Pipw, Polt, sugaR |
|           12 |     7768 | 2024-01-17 | PARIVISION         | W   | 0.312      | -            | -                | -                | -         |     5.25 | faydett, FpSSS, Pipw, Polt, sugaR |
|           11 |     7778 | 2024-01-17 | Endpoint           | W   | 0.312      | -            | -                | -                | -         |     5.46 | faydett, FpSSS, Pipw, Polt, sugaR |
|           10 |     7801 | 2024-01-17 | ENTERPRISE esports | W   | 0.311      | -            | -                | -                | -         |     5.99 | faydett, FpSSS, Pipw, Polt, sugaR |
|            9 |     7904 | 2024-01-16 | Rebels Gaming      | L   | 0.304      | -            | -                | -                | -         |    -2.17 | faydett, FpSSS, Pipw, Polt, sugaR |
|            8 |     8037 | 2024-01-13 | Permitta Esports   | L   | 0.284      | -            | -                | -                | -         |    -3.73 | faydett, FpSSS, Pipw, Polt, sugaR |
|            7 |     8039 | 2024-01-13 | B8                 | W   | 0.283      | -            | -                | -                | -         |     0.94 | faydett, FpSSS, Pipw, Polt, sugaR |
|            6 |     8081 | 2024-01-12 | EYEBALLERS         | W   | 0.279      | -            | -                | -                | -         |     4.60 | faydett, FpSSS, Pipw, Polt, sugaR |
|            5 |     8114 | 2024-01-12 | Kappa Bar          | W   | 0.278      | -            | -                | -                | -         |     0.96 | faydett, FpSSS, Pipw, Polt, sugaR |
|            4 |     8769 | 2023-12-17 | ARCRED             | W   | 0.102      | -            | -                | -                | -         |     1.11 | faydett, FpSSS, Pipw, Polt, sugaR |
|            3 |     8863 | 2023-12-16 | Sangal Esports     | L   | 0.097      | -            | -                | -                | -         |    -0.70 | faydett, FpSSS, Pipw, Polt, sugaR |
|            2 |     8888 | 2023-12-16 | FORZE Youngsters   | W   | 0.096      | -            | -                | -                | -         |     0.64 | faydett, FpSSS, Pipw, Polt, sugaR |
|            1 |     8909 | 2023-12-16 | BebraFPL1          | W   | 0.095      | -            | -                | -                | -         |     0.32 | faydett, FpSSS, Pipw, Polt, sugaR |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($2,000.00)
- Divide that value by the 5th highest value among all rosters ($300,806.11)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
