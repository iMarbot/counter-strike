### Roster Details<br />
Team Name: 9Pandas<br />
Roster: clax, d1Ledez, glowiing, iDISBALANCE, seized<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [43](../standings_global.md)<br />
Regional Rank: [33]( ../standings_europe.md)<br />
Final Rank Value:  1072.7<br />
<br />
Final Rank Value (1072.7) = Starting Rank Value (1130.4) + Head To Head Adjustments (-57.7)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.483[<sup>1</sup>](#table2)
- Bounty Collected: 0.435[<sup>2</sup>](#table1)
- Opponent Network: 0.215[<sup>2</sup>](#table1)
- LAN Wins: 0.340[<sup>2</sup>](#table1)

The average of these factors is 0.368<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1130.4
- 400 + ( ( 0.368 - 0.000 ) / ( 0.806 - 0.000 ) ) * 1600 = 1130.4


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent                    | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins      | H2H Adj. | Roster                                       |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           79 |       35 | 2024-05-05 | ARCRED                      | W   | 1.000      | 0.143        | -                | 0.825 (0.118)    | false (0.000) |     8.74 | clax, d1Ledez, glowiing, iDISBALANCE, seized |
|           78 |       70 | 2024-05-04 | BetBoom Team                | L   | 1.000      | -            | -                | -                | -             |    -4.25 | clax, d1Ledez, glowiing, iDISBALANCE, seized |
|           77 |       94 | 2024-05-03 | Fnatic                      | W   | 1.000      | 0.435        | 0.334 (0.145)    | 0.683 (0.297)    | false (0.000) |    22.68 | clax, d1Ledez, glowiing, iDISBALANCE, seized |
|           76 |      164 | 2024-05-02 | MOUZ NXT                    | W   | 1.000      | 0.435        | 0.215 (0.094)    | 1.000 (0.435)    | -             |    16.92 | clax, d1Ledez, glowiing, iDISBALANCE, seized |
|           75 |      256 | 2024-04-30 | Passion UA                  | L   | 1.000      | -            | -                | -                | -             |   -21.53 | clax, d1Ledez, glowiing, iDISBALANCE, seized |
|           74 |      327 | 2024-04-28 | Gaimin Gladiators           | W   | 1.000      | 0.500        | 0.194 (0.097)    | 0.989 (0.494)    | -             |    25.61 | clax, d1Ledez, glowiing, iDISBALANCE, seized |
|           73 |      431 | 2024-04-26 | Passion UA                  | L   | 1.000      | -            | -                | -                | -             |   -20.81 | clax, d1Ledez, glowiing, iDISBALANCE, seized |
|           72 |      852 | 2024-04-19 | Alliance                    | L   | 1.000      | -            | -                | -                | -             |   -23.37 | clax, d1Ledez, glowiing, iDISBALANCE, seized |
|           71 |      926 | 2024-04-17 | Sashi Esport                | L   | 1.000      | -            | -                | -                | -             |   -16.70 | clax, d1Ledez, glowiing, iDISBALANCE, seized |
|           70 |      975 | 2024-04-17 | Sangal Esports              | L   | 1.000      | -            | -                | -                | -             |   -26.84 | clax, d1Ledez, glowiing, iDISBALANCE, seized |
|           69 |     1217 | 2024-04-10 | SAW                         | L   | 1.000      | -            | -                | -                | -             |    -3.80 | clax, d1Ledez, glowiing, iDISBALANCE, seized |
|           68 |     1309 | 2024-04-09 | Aurora Gaming               | L   | 1.000      | -            | -                | -                | -             |    -3.04 | clax, d1Ledez, glowiing, iDISBALANCE, seized |
|           67 |     1325 | 2024-04-08 | 1win                        | L   | 1.000      | -            | -                | -                | -             |   -28.59 | clax, d1Ledez, glowiing, iDISBALANCE, seized |
|           66 |     1338 | 2024-04-08 | Metizport                   | W   | 1.000      | 0.143        | 0.188 (0.027)    | 1.000 (0.143)    | -             |    16.15 | clax, d1Ledez, glowiing, iDISBALANCE, seized |
|           65 |     1450 | 2024-04-05 | Team Secret                 | L   | 0.997      | -            | -                | -                | -             |   -29.23 | clax, d1Ledez, glowiing, iDISBALANCE, seized |
|           64 |     1480 | 2024-04-04 | TSM                         | W   | 0.992      | 0.500        | -                | 0.183 (0.091)    | -             |     2.83 | clax, d1Ledez, glowiing, iDISBALANCE, seized |
|           63 |     1534 | 2024-04-03 | EYEBALLERS                  | W   | 0.985      | 0.500        | 0.051 (0.025)    | 0.533 (0.263)    | -             |     7.25 | clax, d1Ledez, glowiing, iDISBALANCE, seized |
|           62 |     1543 | 2024-04-03 | 9INE Academy                | W   | 0.984      | 0.500        | -                | 0.171 (0.084)    | -             |     1.99 | clax, d1Ledez, glowiing, iDISBALANCE, seized |
|           61 |     2604 | 2024-03-06 | KOI                         | L   | 0.799      | -            | -                | -                | -             |   -13.71 | clax, d1Ledez, glowiing, iDISBALANCE, seized |
|           60 |     2922 | 2024-03-01 | Aurora Gaming               | L   | 0.764      | -            | -                | -                | -             |    -2.85 | clax, d1Ledez, glowiing, iDISBALANCE, seized |
|           59 |     2942 | 2024-02-29 | FORZE Esports               | L   | 0.759      | -            | -                | -                | -             |   -14.35 | clax, d1Ledez, glowiing, iDISBALANCE, seized |
|           58 |     2983 | 2024-02-28 | Team Spirit Academy         | W   | 0.752      | -            | -                | -                | -             |     3.45 | clax, d1Ledez, glowiing, iDISBALANCE, seized |
|           57 |     2998 | 2024-02-28 | Lotus (Croatian team)       | W   | 0.751      | -            | -                | -                | -             |     0.30 | clax, d1Ledez, glowiing, iDISBALANCE, seized |
|           56 |     3162 | 2024-02-24 | GamerLegion                 | W   | 0.724      | 0.143        | 0.194 (0.020)    | -                | true (0.724)  |    20.65 | clax, d1Ledez, glowiing, iDISBALANCE, seized |
|           55 |     3222 | 2024-02-23 | Astralis                    | W   | 0.717      | 0.143        | 0.179 (0.018)    | -                | true (0.717)  |    20.10 | clax, d1Ledez, glowiing, iDISBALANCE, seized |
|           54 |     3507 | 2024-02-17 | AMKAL ESPORTS               | L   | 0.677      | -            | -                | -                | -             |    -8.36 | clax, d1Ledez, glowiing, iDISBALANCE, seized |
|           53 |     3538 | 2024-02-16 | 3DMAX                       | W   | 0.671      | -            | -                | -                | true (0.671)  |     6.10 | clax, d1Ledez, glowiing, iDISBALANCE, seized |
|           52 |     3603 | 2024-02-15 | KOI                         | L   | 0.663      | -            | -                | -                | -             |   -12.17 | clax, d1Ledez, glowiing, iDISBALANCE, seized |
|           51 |     3633 | 2024-02-14 | SAW                         | W   | 0.658      | 0.143        | 0.263 (0.025)    | -                | true (0.658)  |    17.69 | clax, d1Ledez, glowiing, iDISBALANCE, seized |
|           50 |     3654 | 2024-02-14 | FaZe Clan                   | L   | 0.657      | -            | -                | -                | -             |    -0.18 | clax, d1Ledez, glowiing, iDISBALANCE, seized |
|           49 |     3954 | 2024-02-03 | TBA.ECF                     | L   | 0.585      | -            | -                | -                | -             |   -17.28 | clax, d1Ledez, glowiing, iDISBALANCE, seized |
|           48 |     3967 | 2024-02-03 | Clownfiesta                 | W   | 0.585      | -            | -                | -                | -             |     0.31 | clax, d1Ledez, glowiing, iDISBALANCE, seized |
|           47 |     3982 | 2024-02-03 | Natus Vincere Junior        | W   | 0.584      | -            | -                | -                | -             |     2.56 | clax, d1Ledez, glowiing, iDISBALANCE, seized |
|           46 |     4016 | 2024-02-02 | B8                          | L   | 0.579      | -            | -                | -                | -             |   -13.87 | clax, d1Ledez, glowiing, iDISBALANCE, seized |
|           45 |     4021 | 2024-02-02 | Dynamo Eclot                | W   | 0.578      | 0.143        | -                | 0.953 (0.079)    | -             |     9.05 | clax, d1Ledez, glowiing, iDISBALANCE, seized |
|           44 |     4030 | 2024-02-02 | BLESSED (Ukrainian team)    | W   | 0.578      | -            | -                | -                | -             |     2.34 | clax, d1Ledez, glowiing, iDISBALANCE, seized |
|           43 |     4044 | 2024-02-02 | INGLORIOUS                  | W   | 0.578      | -            | -                | -                | -             |     2.27 | clax, d1Ledez, glowiing, iDISBALANCE, seized |
|           42 |     4142 | 2024-01-30 | Nemiga Gaming               | L   | 0.558      | -            | -                | -                | -             |    -5.04 | clax, d1Ledez, glowiing, iDISBALANCE, seized |
|           41 |     4185 | 2024-01-29 | JANO Esports                | W   | 0.553      | -            | -                | -                | -             |     1.98 | clax, d1Ledez, glowiing, iDISBALANCE, seized |
|           40 |     4216 | 2024-01-28 | Rebels Gaming               | W   | 0.545      | -            | -                | -                | -             |     7.81 | clax, d1Ledez, glowiing, iDISBALANCE, seized |
|           39 |     4310 | 2024-01-26 | FLuffy Gangsters            | W   | 0.532      | -            | -                | -                | -             |     0.60 | clax, d1Ledez, glowiing, iDISBALANCE, seized |
|           38 |     4318 | 2024-01-26 | UNiTY esports (Slovak team) | W   | 0.531      | 0.371        | -                | 0.727 (0.143)    | -             |     4.55 | clax, d1Ledez, glowiing, iDISBALANCE, seized |
|           37 |     4542 | 2024-01-20 | 3DMAX                       | W   | 0.492      | -            | -                | -                | -             |     4.35 | clax, d1Ledez, glowiing, iDISBALANCE, seized |
|           36 |     4556 | 2024-01-20 | SAW                         | L   | 0.491      | -            | -                | -                | -             |    -1.99 | clax, d1Ledez, glowiing, iDISBALANCE, seized |
|           35 |     4608 | 2024-01-19 | Gaimin Gladiators           | W   | 0.484      | -            | -                | -                | -             |    12.71 | clax, d1Ledez, glowiing, iDISBALANCE, seized |
|           34 |     4652 | 2024-01-18 | Natus Vincere               | L   | 0.478      | -            | -                | -                | -             |    -0.14 | clax, d1Ledez, glowiing, iDISBALANCE, seized |
|           33 |     4659 | 2024-01-18 | Nexus Gaming                | W   | 0.478      | -            | -                | -                | -             |     3.87 | clax, d1Ledez, glowiing, iDISBALANCE, seized |
|           32 |     5353 | 2023-12-17 | IKLA                        | L   | 0.265      | -            | -                | -                | -             |    -7.69 | clax, d1Ledez, glowiing, iDISBALANCE, seized |
|           31 |     5464 | 2023-12-16 | B8                          | L   | 0.259      | -            | -                | -                | -             |    -7.65 | clax, d1Ledez, glowiing, iDISBALANCE, seized |
|           30 |     5694 | 2023-12-11 | Preasy Esport               | L   | 0.225      | -            | -                | -                | -             |    -5.17 | clax, d1Ledez, glowiing, iDISBALANCE, seized |
|           29 |     5920 | 2023-12-06 | Guild Eagles                | L   | 0.192      | -            | -                | -                | -             |    -3.84 | clax, d1Ledez, glowiing, iDISBALANCE, seized |
|           28 |     5936 | 2023-12-06 | Gaimin Gladiators           | W   | 0.191      | -            | -                | -                | -             |     5.09 | clax, d1Ledez, glowiing, iDISBALANCE, seized |
|           27 |     5949 | 2023-12-06 | SAW                         | W   | 0.190      | 0.589        | 0.263 (0.029)    | -                | -             |     5.25 | clax, d1Ledez, glowiing, iDISBALANCE, seized |
|           26 |     5973 | 2023-12-05 | BIG                         | L   | 0.186      | -            | -                | -                | -             |    -0.93 | clax, d1Ledez, glowiing, iDISBALANCE, seized |
|           25 |     6029 | 2023-12-03 | Into The Breach             | W   | 0.172      | -            | -                | -                | -             |     0.77 | clax, d1Ledez, glowiing, iDISBALANCE, seized |
|           24 |     6168 | 2023-12-01 | Insilio                     | L   | 0.157      | -            | -                | -                | -             |    -3.83 | clax, d1Ledez, glowiing, iDISBALANCE, seized |
|           23 |     6194 | 2023-11-30 | Legacy                      | W   | 0.152      | -            | -                | -                | -             |     2.35 | clax, d1Ledez, glowiing, iDISBALANCE, seized |
|           22 |     6218 | 2023-11-30 | SAW                         | L   | 0.150      | -            | -                | -                | -             |    -0.57 | clax, d1Ledez, glowiing, iDISBALANCE, seized |
|           21 |     6264 | 2023-11-29 | RoundsGG                    | L   | 0.145      | -            | -                | -                | -             |    -4.14 | clax, d1Ledez, glowiing, iDISBALANCE, seized |
|           20 |     6354 | 2023-11-27 | Verdant                     | L   | 0.132      | -            | -                | -                | -             |    -2.89 | clax, d1Ledez, glowiing, iDISBALANCE, seized |
|           19 |     6573 | 2023-11-22 | ALTERNATE aTTaX             | W   | 0.097      | -            | -                | -                | -             |     1.29 | clax, d1Ledez, glowiing, iDISBALANCE, seized |
|           18 |     6599 | 2023-11-21 | Underrated                  | W   | 0.091      | -            | -                | -                | -             |     0.07 | clax, d1Ledez, glowiing, iDISBALANCE, seized |
|           17 |     6641 | 2023-11-20 | Eternal Fire                | W   | 0.085      | -            | -                | -                | true (0.085)  |     2.60 | clax, d1Ledez, glowiing, iDISBALANCE, seized |
|           16 |     6674 | 2023-11-19 | FURIA Esports               | W   | 0.077      | -            | -                | -                | true (0.077)  |     2.32 | clax, d1Ledez, glowiing, iDISBALANCE, seized |
|           15 |     6775 | 2023-11-17 | Gaimin Gladiators           | L   | 0.064      | -            | -                | -                | -             |    -0.28 | clax, d1Ledez, glowiing, iDISBALANCE, seized |
|           14 |     6790 | 2023-11-17 | MIBR                        | W   | 0.063      | 0.500        | 0.654 (0.021)    | -                | true (0.063)  |     1.89 | clax, d1Ledez, glowiing, iDISBALANCE, seized |
|           13 |     6812 | 2023-11-16 | Legacy                      | W   | 0.059      | -            | -                | -                | -             |     0.92 | clax, d1Ledez, glowiing, iDISBALANCE, seized |
|           12 |     6833 | 2023-11-16 | BetBoom Team                | W   | 0.058      | -            | -                | -                | true (0.058)  |     1.59 | clax, d1Ledez, glowiing, iDISBALANCE, seized |
|           11 |     6890 | 2023-11-15 | Entropiq                    | W   | 0.051      | -            | -                | -                | -             |     0.21 | clax, d1Ledez, glowiing, iDISBALANCE, seized |
|           10 |     6901 | 2023-11-15 | Dynamo Eclot                | W   | 0.050      | -            | -                | -                | -             |     0.12 | clax, d1Ledez, glowiing, iDISBALANCE, seized |
|            9 |     6936 | 2023-11-14 | Alliance                    | W   | 0.044      | -            | -                | -                | -             |     0.28 | clax, d1Ledez, glowiing, iDISBALANCE, seized |
|            8 |     6983 | 2023-11-13 | Legacy                      | W   | 0.037      | -            | -                | -                | -             |     0.59 | clax, d1Ledez, glowiing, iDISBALANCE, seized |
|            7 |     7001 | 2023-11-12 | Pompa Team                  | W   | 0.032      | -            | -                | -                | -             |     0.03 | clax, d1Ledez, glowiing, iDISBALANCE, seized |
|            6 |     7019 | 2023-11-12 | Entropiq                    | L   | 0.030      | -            | -                | -                | -             |    -0.81 | clax, d1Ledez, glowiing, iDISBALANCE, seized |
|            5 |     7090 | 2023-11-10 | K10                         | W   | 0.019      | -            | -                | -                | -             |     0.12 | clax, d1Ledez, glowiing, iDISBALANCE, seized |
|            4 |     7107 | 2023-11-10 | Team Space                  | W   | 0.017      | -            | -                | -                | -             |     0.05 | clax, d1Ledez, glowiing, iDISBALANCE, seized |
|            3 |     7149 | 2023-11-09 | SINNERS Esports             | L   | 0.010      | -            | -                | -                | -             |    -0.22 | clax, d1Ledez, glowiing, iDISBALANCE, seized |
|            2 |     7203 | 2023-11-08 | Aurora Gaming               | W   | 0.004      | -            | -                | -                | -             |     0.11 | clax, d1Ledez, glowiing, iDISBALANCE, seized |
|            1 |     7214 | 2023-11-08 | MOUZ NXT                    | L   | 0.003      | -            | -                | -                | -             |    -0.05 | clax, d1Ledez, glowiing, iDISBALANCE, seized |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($13,472.84)
- Divide that value by the 5th highest value among all rosters ($158,437.64)
- The final value (0.09) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-05-04 |      1.000 | $5,000.00      | $5,000.00       |
| 2023-12-13 |      0.239 | $500.00        | $119.29         |
| 2023-12-07 |      0.199 | $15,000.00     | $2,982.29       |
| 2023-11-21 |      0.092 | $1,000.00      | $92.31          |
| 2023-11-20 |      0.085 | $60,000.00     | $5,080.56       |
| 2023-11-18 |      0.070 | $2,000.00      | $139.35         |
| 2023-11-09 |      0.012 | $5,000.00      | $59.03          |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
