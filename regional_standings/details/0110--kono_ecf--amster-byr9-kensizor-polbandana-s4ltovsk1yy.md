### Roster Details<br />
Team Name: kONO.ECF<br />
Roster: amster, byr9, kensizor, Polbandana, s4ltovsk1yy<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [110](../standings_global.md)<br />
Regional Rank: [77]( ../standings_europe.md)<br />
Final Rank Value:  853.1<br />
<br />
Final Rank Value (853.1) = Starting Rank Value (864.8) + Head To Head Adjustments (-11.7)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.348[<sup>1</sup>](#table2)
- Bounty Collected: 0.349[<sup>2</sup>](#table1)
- Opponent Network: 0.217[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.228<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 864.8
- 400 + ( ( 0.228 - 0.000 ) / ( 0.786 - 0.000 ) ) * 1600 = 864.8


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent               | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                          |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           73 |      315 | 2024-05-25 | Rebels Gaming          | L   | 1.000      | -            | -                | -                | -         |    -7.79 | amster, byr9, kensizor, Polbandana, s4ltovsk1yy |
|           72 |      600 | 2024-05-21 | Denial                 | L   | 1.000      | -            | -                | -                | -         |   -25.80 | amster, byr9, kensizor, Polbandana, s4ltovsk1yy |
|           71 |      620 | 2024-05-21 | iNation                | L   | 1.000      | -            | -                | -                | -         |   -22.48 | amster, byr9, kensizor, Polbandana, s4ltovsk1yy |
|           70 |      691 | 2024-05-20 | GamerLegion Academy    | W   | 1.000      | 0.372        | 0.018 (0.007)    | 0.691 (0.257)    | 0 (0.000) |    13.64 | amster, byr9, kensizor, Polbandana, s4ltovsk1yy |
|           69 |      701 | 2024-05-20 | Rhyno Esports          | W   | 1.000      | 0.372        | 0.029 (0.011)    | 0.518 (0.193)    | 0 (0.000) |    18.51 | amster, byr9, kensizor, Polbandana, s4ltovsk1yy |
|           68 |     1089 | 2024-05-16 | Monte                  | L   | 1.000      | -            | -                | -                | -         |    -3.38 | amster, byr9, kensizor, Polbandana, s4ltovsk1yy |
|           67 |     1107 | 2024-05-16 | Zero Tenacity          | L   | 1.000      | -            | -                | -                | -         |    -9.44 | amster, byr9, kensizor, Polbandana, s4ltovsk1yy |
|           66 |     1148 | 2024-05-15 | HOTU                   | L   | 1.000      | -            | -                | -                | -         |   -19.07 | amster, byr9, kensizor, Polbandana, s4ltovsk1yy |
|           65 |     1163 | 2024-05-15 | Nexus Gaming           | L   | 1.000      | -            | -                | -                | -         |   -18.83 | amster, byr9, kensizor, Polbandana, s4ltovsk1yy |
|           64 |     1210 | 2024-05-15 | Preasy Esport          | W   | 1.000      | 0.333        | 0.008 (0.003)    | 0.642 (0.214)    | 0 (0.000) |    11.30 | amster, byr9, kensizor, Polbandana, s4ltovsk1yy |
|           63 |     1264 | 2024-05-14 | Rustec                 | L   | 1.000      | -            | -                | -                | -         |   -21.05 | amster, byr9, kensizor, Polbandana, s4ltovsk1yy |
|           62 |     1280 | 2024-05-14 | Alliance               | W   | 1.000      | 0.384        | -                | 0.529 (0.203)    | 0 (0.000) |    13.44 | amster, byr9, kensizor, Polbandana, s4ltovsk1yy |
|           61 |     1295 | 2024-05-14 | Johnny Speeds          | W   | 1.000      | 0.333        | 0.056 (0.019)    | 0.683 (0.228)    | 0 (0.000) |    20.93 | amster, byr9, kensizor, Polbandana, s4ltovsk1yy |
|           60 |     1311 | 2024-05-13 | JANO Esports           | L   | 1.000      | -            | -                | -                | -         |   -23.31 | amster, byr9, kensizor, Polbandana, s4ltovsk1yy |
|           59 |     1333 | 2024-05-13 | Verdant                | W   | 1.000      | 0.333        | 0.014 (0.005)    | 1.000 (0.333)    | 0 (0.000) |    14.44 | amster, byr9, kensizor, Polbandana, s4ltovsk1yy |
|           58 |     1375 | 2024-05-12 | ILLYRIANS              | L   | 1.000      | -            | -                | -                | -         |   -22.20 | amster, byr9, kensizor, Polbandana, s4ltovsk1yy |
|           57 |     1439 | 2024-05-11 | FAVBET Team            | L   | 1.000      | -            | -                | -                | -         |   -14.07 | amster, byr9, kensizor, Polbandana, s4ltovsk1yy |
|           56 |     1447 | 2024-05-11 | Grannys Knockers       | W   | 1.000      | -            | -                | -                | 0 (0.000) |     8.61 | amster, byr9, kensizor, Polbandana, s4ltovsk1yy |
|           55 |     1455 | 2024-05-11 | Permitta Esports       | W   | 1.000      | 0.143        | 0.029 (0.004)    | 1.000 (0.143)    | 0 (0.000) |    12.93 | amster, byr9, kensizor, Polbandana, s4ltovsk1yy |
|           54 |     1481 | 2024-05-11 | NOM Esports            | W   | 1.000      | -            | -                | -                | 0 (0.000) |     6.50 | amster, byr9, kensizor, Polbandana, s4ltovsk1yy |
|           53 |     1503 | 2024-05-10 | Sangal Esports         | L   | 1.000      | -            | -                | -                | -         |   -10.84 | amster, byr9, kensizor, Polbandana, s4ltovsk1yy |
|           52 |     1510 | 2024-05-10 | ILLYRIANS              | W   | 1.000      | -            | -                | -                | 0 (0.000) |     8.95 | BledarD, Caleyy, Dementor, HYPERI1, vAloN       |
|           51 |     1519 | 2024-05-10 | Entropiq               | W   | 1.000      | -            | -                | -                | -         |     6.20 | Buzz, FASHR, Marix, regali, tiziaN              |
|           50 |     1574 | 2024-05-09 | Lausanne-Sport Esports | W   | 1.000      | -            | -                | -                | -         |     9.04 | berzerk, msn2k, SBT, SeBreeZe, xReal            |
|           49 |     1580 | 2024-05-09 | Preasy Esport          | L   | 1.000      | -            | -                | -                | -         |   -21.98 | amster, byr9, kensizor, Polbandana, s4ltovsk1yy |
|           48 |     1849 | 2024-05-04 | ex-K10                 | W   | 1.000      | -            | -                | -                | -         |     1.55 | Askan, AyeZ, Rezst, sense, Tree                 |
|           47 |     1973 | 2024-05-01 | ThunderFlash           | L   | 1.000      | -            | -                | -                | -         |   -18.40 | amster, byr9, kensizor, Polbandana, s4ltovsk1yy |
|           46 |     2046 | 2024-04-30 | Copenhagen Wolves      | W   | 1.000      | -            | -                | -                | -         |     5.03 | Basso, Fessor, smF, Svedjehed, szejn            |
|           45 |     2080 | 2024-04-29 | Gaimin Gladiators      | W   | 0.996      | 0.384        | 0.092 (0.035)    | 0.711 (0.272)    | -         |    25.42 | amster, byr9, kensizor, Polbandana, s4ltovsk1yy |
|           44 |     2331 | 2024-04-25 | HAVU Gaming            | W   | 0.968      | -            | -                | -                | -         |     6.94 | amster, byr9, kensizor, Polbandana, s4ltovsk1yy |
|           43 |     2366 | 2024-04-24 | Nemiga Gaming          | L   | 0.964      | -            | -                | -                | -         |    -4.76 | amster, byr9, kensizor, Polbandana, s4ltovsk1yy |
|           42 |     2373 | 2024-04-24 | Eternal Fire Academy   | W   | 0.963      | -            | -                | -                | -         |     3.12 | amster, byr9, kensizor, Polbandana, s4ltovsk1yy |
|           41 |     2910 | 2024-04-16 | Young Ninjas           | W   | 0.910      | 0.372        | 0.043 (0.014)    | 0.372 (0.126)    | -         |    16.35 | jocab, MisteM, Silence, sprayxd, xKacpersky     |
|           40 |     3861 | 2024-03-26 | TSM                    | L   | 0.771      | -            | -                | -                | -         |   -16.92 | amster, byr9, kensizor, Polbandana, s4ltovsk1yy |
|           39 |     4225 | 2024-03-18 | DASH                   | W   | 0.715      | -            | -                | -                | -         |     5.79 | amster, byr9, kensizor, Polbandana, s4ltovsk1yy |
|           38 |     4261 | 2024-03-17 | L&G                    | W   | 0.711      | -            | -                | -                | -         |     6.10 | crickey, kr1vda, marat2k, OneUn1que, somnium    |
|           37 |     4283 | 2024-03-17 | DASH                   | L   | 0.710      | -            | -                | -                | -         |   -16.88 | cairne, Flierax, kRyTouS, Merl, onic            |
|           36 |     4319 | 2024-03-16 | ROSOMAHA               | W   | 0.704      | -            | -                | -                | -         |     3.02 | amster, byr9, kensizor, Polbandana, s4ltovsk1yy |
|           35 |     4606 | 2024-03-11 | CYBERSHOKE Esports     | L   | 0.671      | -            | -                | -                | -         |   -15.06 | byr9, kensizor, munch, Polbandana, s4ltovsk1yy  |
|           34 |     4717 | 2024-03-09 | ENTERPRISE esports     | W   | 0.657      | 0.371        | -                | 0.809 (0.197)    | -         |     9.93 | bajmi, Demho, Ex1st, fr3nd, TOAO                |
|           33 |     4812 | 2024-03-07 | Endpoint               | L   | 0.644      | -            | -                | -                | -         |   -10.09 | AZUWU, MiGHTYMAX, sl3nd, Surreal, swicher       |
|           32 |     5019 | 2024-03-04 | Insilio                | L   | 0.625      | -            | -                | -                | -         |    -9.69 | byr9, kensizor, munch, Polbandana, s4ltovsk1yy  |
|           31 |     5081 | 2024-03-03 | ex-Preasy Esport       | L   | 0.617      | -            | -                | -                | -         |    -9.63 | byr9, kensizor, munch, Polbandana, s4ltovsk1yy  |
|           30 |     5127 | 2024-03-02 | ENTERPRISE esports     | W   | 0.612      | -            | -                | -                | -         |     9.82 | byr9, kensizor, munch, Polbandana, s4ltovsk1yy  |
|           29 |     5158 | 2024-03-02 | Nemiga Gaming          | W   | 0.611      | 0.143        | 0.366 (0.032)    | -                | -         |    16.64 | byr9, kensizor, munch, Polbandana, s4ltovsk1yy  |
|           28 |     5231 | 2024-03-01 | Endpoint               | L   | 0.604      | -            | -                | -                | -         |    -9.88 | AZUWU, MiGHTYMAX, sl3nd, Surreal, swicher       |
|           27 |     5309 | 2024-02-28 | Aurora Gaming          | L   | 0.591      | -            | -                | -                | -         |    -1.13 | BELCHONOKK, deko, KENSI, Lack1, Norwi           |
|           26 |     5327 | 2024-02-28 | KOI                    | L   | 0.590      | -            | -                | -                | -         |    -7.47 | byr9, kensizor, munch, Polbandana, s4ltovsk1yy  |
|           25 |     5356 | 2024-02-27 | DMS                    | W   | 0.584      | -            | -                | -                | -         |     4.65 | AW, H1te, kAlash, sFade8, sm3t                  |
|           24 |     5368 | 2024-02-27 | INGLORIOUS             | W   | 0.584      | -            | -                | -                | -         |     5.79 | Drobnyy, Esphirion, Jad0R1x, LAYM, V1           |
|           23 |     5396 | 2024-02-26 | ENTERPRISE esports     | W   | 0.578      | -            | -                | -                | -         |    10.12 | byr9, kensizor, munch, Polbandana, s4ltovsk1yy  |
|           22 |     5651 | 2024-02-22 | DASH                   | W   | 0.551      | -            | -                | -                | -         |     4.17 | byr9, kensizor, munch, Polbandana, s4ltovsk1yy  |
|           21 |     5704 | 2024-02-21 | CYBERSHOKE Esports     | W   | 0.544      | -            | -                | -                | -         |     4.47 | byr9, kensizor, munch, Polbandana, s4ltovsk1yy  |
|           20 |     5760 | 2024-02-20 | ex-Anonymo Esports     | W   | 0.537      | -            | -                | -                | -         |     4.54 | byr9, kensizor, munch, Polbandana, s4ltovsk1yy  |
|           19 |     5937 | 2024-02-17 | Aurora Gaming          | L   | 0.517      | -            | -                | -                | -         |    -0.76 | byr9, kensizor, munch, Polbandana, s4ltovsk1yy  |
|           18 |     5940 | 2024-02-17 | The Chosen Few         | W   | 0.517      | -            | -                | -                | -         |     5.34 | byr9, kensizor, munch, Polbandana, s4ltovsk1yy  |
|           17 |     5950 | 2024-02-17 | Aurora Gaming          | L   | 0.516      | -            | -                | -                | -         |    -0.70 | byr9, kensizor, munch, Polbandana, s4ltovsk1yy  |
|           16 |     5981 | 2024-02-16 | Team Spirit Academy    | W   | 0.511      | -            | -                | -                | -         |     5.45 | byr9, kensizor, munch, Polbandana, s4ltovsk1yy  |
|           15 |     6255 | 2024-02-10 | Betera Esports         | W   | 0.471      | -            | -                | -                | -         |     6.46 | byr9, kensizor, munch, Polbandana, s4ltovsk1yy  |
|           14 |     6261 | 2024-02-10 | ILLYRIANS              | W   | 0.471      | -            | -                | -                | -         |     4.47 | byr9, kensizor, munch, Polbandana, s4ltovsk1yy  |
|           13 |     6270 | 2024-02-10 | ex-K10                 | W   | 0.470      | -            | -                | -                | -         |     6.06 | Rezst, shyyne, SLY, Tree, yz0                   |
|           12 |     6327 | 2024-02-08 | GenOne                 | W   | 0.457      | -            | -                | -                | -         |     3.12 | devoduvek, drac, Revol, SIXER, unshaark         |
|           11 |     6498 | 2024-02-03 | UNiTY esports          | W   | 0.424      | -            | -                | -                | -         |     7.43 | byr9, kensizor, munch, Polbandana, s4ltovsk1yy  |
|           10 |     6510 | 2024-02-03 | 9Pandas                | W   | 0.424      | 0.143        | 0.110 (0.007)    | -                | -         |    11.42 | clax, d1Ledez, glowiing, iDISBALANCE, seized    |
|            9 |     6540 | 2024-02-03 | team amster333         | W   | 0.423      | -            | -                | -                | -         |     1.55 | amster, h1glaiN, miL4nNNNNNN, muR, uQlutzavr    |
|            8 |     6549 | 2024-02-03 | HIMARSpeek             | W   | 0.423      | -            | -                | -                | -         |     0.97 | 2kEloLover, darky, GeT FiGhT, OG_JOY, steffe    |
|            7 |     6791 | 2024-01-29 | Insilio                | L   | 0.392      | -            | -                | -                | -         |    -5.09 | faydett, FpSSS, Pipw, Polt, sugaR               |
|            6 |     6806 | 2024-01-29 | ALTERNATE aTTaX        | W   | 0.392      | -            | -                | -                | -         |     4.15 | amster, byr9, munch, Polbandana, s4ltovsk1yy    |
|            5 |     7551 | 2024-01-17 | PARIVISION             | L   | 0.311      | -            | -                | -                | -         |    -4.02 | byr9, kensizor, munch, Polbandana, s4ltovsk1yy  |
|            4 |     7667 | 2024-01-16 | Verdant                | L   | 0.304      | -            | -                | -                | -         |    -2.54 | byr9, kensizor, munch, Polbandana, s4ltovsk1yy  |
|            3 |     8080 | 2024-01-09 | Entropiq               | L   | 0.258      | -            | -                | -                | -         |    -6.23 | byr9, kensizor, munch, Polbandana, s4ltovsk1yy  |
|            2 |     8085 | 2024-01-09 | ex-Anonymo Esports     | W   | 0.257      | -            | -                | -                | -         |     2.37 | byr9, kensizor, munch, Polbandana, s4ltovsk1yy  |
|            1 |     8120 | 2024-01-09 | TEAM MAX               | W   | 0.257      | -            | -                | -                | -         |     1.02 | byr9, kensizor, munch, Polbandana, s4ltovsk1yy  |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($4,000.00)
- Divide that value by the 5th highest value among all rosters ($300,806.11)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-05-18 |      1.000 | $1,000.00      | $1,000.00       |
| 2024-05-16 |      1.000 | $3,000.00      | $3,000.00       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
