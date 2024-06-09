### Roster Details<br />
Team Name: kONO.ECF<br />
Roster: amster, byr9, kensizor, Polbandana, s4ltovsk1yy<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [107](../standings_global.md)<br />
Regional Rank: [77]( ../standings_europe.md)<br />
Final Rank Value:  859.6<br />
<br />
Final Rank Value (859.6) = Starting Rank Value (877.3) + Head To Head Adjustments (-17.6)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.348[<sup>1</sup>](#table2)
- Bounty Collected: 0.361[<sup>2</sup>](#table1)
- Opponent Network: 0.230[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.235<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 877.3
- 400 + ( ( 0.235 - 0.000 ) / ( 0.787 - 0.000 ) ) * 1600 = 877.3


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
|           86 |      323 | 2024-05-25 | Rebels Gaming          | L   | 1.000      | -            | -                | -                | -         |    -7.78 | amster, byr9, kensizor, Polbandana, s4ltovsk1yy |
|           85 |      611 | 2024-05-21 | Denial                 | L   | 1.000      | -            | -                | -                | -         |   -26.02 | amster, byr9, kensizor, Polbandana, s4ltovsk1yy |
|           84 |      631 | 2024-05-21 | iNation                | L   | 1.000      | -            | -                | -                | -         |   -22.67 | amster, byr9, kensizor, Polbandana, s4ltovsk1yy |
|           83 |      702 | 2024-05-20 | GamerLegion Academy    | W   | 1.000      | 0.372        | 0.018 (0.007)    | 0.691 (0.257)    | 0 (0.000) |    12.89 | amster, byr9, kensizor, Polbandana, s4ltovsk1yy |
|           82 |      713 | 2024-05-20 | Rhyno Esports          | W   | 1.000      | 0.372        | 0.029 (0.011)    | 0.567 (0.211)    | 0 (0.000) |    18.64 | amster, byr9, kensizor, Polbandana, s4ltovsk1yy |
|           81 |     1099 | 2024-05-16 | Monte                  | L   | 1.000      | -            | -                | -                | -         |    -3.40 | amster, byr9, kensizor, Polbandana, s4ltovsk1yy |
|           80 |     1117 | 2024-05-16 | Zero Tenacity          | L   | 1.000      | -            | -                | -                | -         |    -9.60 | amster, byr9, kensizor, Polbandana, s4ltovsk1yy |
|           79 |     1157 | 2024-05-15 | HOTU                   | L   | 1.000      | -            | -                | -                | -         |   -18.86 | amster, byr9, kensizor, Polbandana, s4ltovsk1yy |
|           78 |     1173 | 2024-05-15 | Nexus Gaming           | L   | 1.000      | -            | -                | -                | -         |   -19.48 | amster, byr9, kensizor, Polbandana, s4ltovsk1yy |
|           77 |     1220 | 2024-05-15 | Preasy Esport          | W   | 1.000      | 0.333        | -                | 0.705 (0.235)    | 0 (0.000) |    11.09 | amster, byr9, kensizor, Polbandana, s4ltovsk1yy |
|           76 |     1275 | 2024-05-14 | Rustec                 | L   | 1.000      | -            | -                | -                | -         |   -20.51 | amster, byr9, kensizor, Polbandana, s4ltovsk1yy |
|           75 |     1291 | 2024-05-14 | Alliance               | W   | 1.000      | 0.384        | -                | 0.529 (0.203)    | 0 (0.000) |    13.13 | amster, byr9, kensizor, Polbandana, s4ltovsk1yy |
|           74 |     1306 | 2024-05-14 | Johnny Speeds          | W   | 1.000      | 0.333        | 0.056 (0.019)    | 0.683 (0.228)    | 0 (0.000) |    20.64 | amster, byr9, kensizor, Polbandana, s4ltovsk1yy |
|           73 |     1322 | 2024-05-13 | JANO Esports           | L   | 1.000      | -            | -                | -                | -         |   -23.19 | amster, byr9, kensizor, Polbandana, s4ltovsk1yy |
|           72 |     1345 | 2024-05-13 | Verdant                | W   | 1.000      | 0.333        | 0.014 (0.005)    | 1.000 (0.333)    | 0 (0.000) |    14.40 | amster, byr9, kensizor, Polbandana, s4ltovsk1yy |
|           71 |     1388 | 2024-05-12 | ILLYRIANS              | L   | 1.000      | -            | -                | -                | -         |   -22.39 | amster, byr9, kensizor, Polbandana, s4ltovsk1yy |
|           70 |     1452 | 2024-05-11 | FAVBET Team            | L   | 1.000      | -            | -                | -                | -         |   -15.18 | amster, byr9, kensizor, Polbandana, s4ltovsk1yy |
|           69 |     1460 | 2024-05-11 | Grannys Knockers       | W   | 1.000      | -            | -                | -                | 0 (0.000) |     9.31 | amster, byr9, kensizor, Polbandana, s4ltovsk1yy |
|           68 |     1468 | 2024-05-11 | Permitta Esports       | W   | 1.000      | -            | -                | -                | 0 (0.000) |    13.58 | amster, byr9, kensizor, Polbandana, s4ltovsk1yy |
|           67 |     1494 | 2024-05-11 | NOM Esports            | W   | 1.000      | -            | -                | -                | 0 (0.000) |     6.28 | amster, byr9, kensizor, Polbandana, s4ltovsk1yy |
|           66 |     1516 | 2024-05-10 | Sangal Esports         | L   | 1.000      | -            | -                | -                | -         |   -10.12 | amster, byr9, kensizor, Polbandana, s4ltovsk1yy |
|           65 |     1523 | 2024-05-10 | ILLYRIANS              | W   | 1.000      | -            | -                | -                | 0 (0.000) |     8.78 | BledarD, Caleyy, Dementor, HYPERI1, vAloN       |
|           64 |     1533 | 2024-05-10 | Entropiq               | W   | 1.000      | -            | -                | -                | -         |     6.07 | Buzz, FASHR, Marix, regali, tiziaN              |
|           63 |     1590 | 2024-05-09 | Lausanne-Sport Esports | W   | 1.000      | -            | -                | -                | -         |    10.35 | berzerk, msn2k, SBT, SeBreeZe, xReal            |
|           62 |     1596 | 2024-05-09 | Preasy Esport          | L   | 1.000      | -            | -                | -                | -         |   -22.15 | amster, byr9, kensizor, Polbandana, s4ltovsk1yy |
|           61 |     1872 | 2024-05-04 | ex-K10                 | W   | 1.000      | -            | -                | -                | -         |     1.49 | Askan, AyeZ, Rezst, sense, Tree                 |
|           60 |     2001 | 2024-05-01 | ThunderFlash           | L   | 1.000      | -            | -                | -                | -         |   -19.24 | amster, byr9, kensizor, Polbandana, s4ltovsk1yy |
|           59 |     2080 | 2024-04-30 | Copenhagen Wolves      | W   | 1.000      | -            | -                | -                | -         |     6.13 | Basso, Fessor, smF, Svedjehed, szejn            |
|           58 |     2115 | 2024-04-29 | Gaimin Gladiators      | W   | 0.996      | 0.384        | 0.092 (0.035)    | 0.727 (0.278)    | -         |    25.33 | amster, byr9, kensizor, Polbandana, s4ltovsk1yy |
|           57 |     2372 | 2024-04-25 | HAVU Gaming            | W   | 0.968      | -            | -                | -                | -         |     6.76 | amster, byr9, kensizor, Polbandana, s4ltovsk1yy |
|           56 |     2408 | 2024-04-24 | Nemiga Gaming          | L   | 0.964      | -            | -                | -                | -         |    -4.96 | amster, byr9, kensizor, Polbandana, s4ltovsk1yy |
|           55 |     2416 | 2024-04-24 | Eternal Fire Academy   | W   | 0.963      | -            | -                | -                | -         |     3.02 | amster, byr9, kensizor, Polbandana, s4ltovsk1yy |
|           54 |     2971 | 2024-04-16 | Young Ninjas           | W   | 0.910      | 0.372        | 0.043 (0.014)    | -                | -         |    15.55 | jocab, MisteM, Silence, sprayxd, xKacpersky     |
|           53 |     3349 | 2024-04-09 | Grannys Knockers       | L   | 0.861      | -            | -                | -                | -         |   -16.39 | amster, byr9, kensizor, Polbandana, s4ltovsk1yy |
|           52 |     3958 | 2024-03-26 | TSM                    | L   | 0.771      | -            | -                | -                | -         |   -17.15 | amster, byr9, kensizor, Polbandana, s4ltovsk1yy |
|           51 |     4330 | 2024-03-18 | DASH                   | W   | 0.715      | -            | -                | -                | -         |     5.46 | amster, byr9, kensizor, Polbandana, s4ltovsk1yy |
|           50 |     4366 | 2024-03-17 | L&G                    | W   | 0.711      | -            | -                | -                | -         |     5.53 | crickey, kr1vda, marat2k, OneUn1que, somnium    |
|           49 |     4389 | 2024-03-17 | DASH                   | L   | 0.710      | -            | -                | -                | -         |   -17.22 | cairne, Flierax, kRyTouS, Merl, onic            |
|           48 |     4425 | 2024-03-16 | ROSOMAHA               | W   | 0.704      | -            | -                | -                | -         |     2.67 | amster, byr9, kensizor, Polbandana, s4ltovsk1yy |
|           47 |     4490 | 2024-03-15 | Metizport              | W   | 0.697      | 0.384        | 0.088 (0.024)    | 0.698 (0.187)    | -         |    15.26 | byr9, kensizor, munch, Polbandana, s4ltovsk1yy  |
|           46 |     4684 | 2024-03-12 | JANO Esports           | W   | 0.676      | -            | -                | -                | -         |     6.74 | byr9, kensizor, munch, Polbandana, s4ltovsk1yy  |
|           45 |     4728 | 2024-03-11 | CYBERSHOKE Esports     | L   | 0.671      | -            | -                | -                | -         |   -17.18 | byr9, kensizor, munch, Polbandana, s4ltovsk1yy  |
|           44 |     4842 | 2024-03-09 | ENTERPRISE esports     | W   | 0.657      | 0.371        | -                | 0.898 (0.219)    | -         |    10.35 | bajmi, Demho, Ex1st, fr3nd, TOAO                |
|           43 |     4941 | 2024-03-07 | Endpoint               | L   | 0.644      | -            | -                | -                | -         |   -10.18 | AZUWU, MiGHTYMAX, sl3nd, Surreal, swicher       |
|           42 |     4957 | 2024-03-07 | Permitta Esports       | L   | 0.642      | -            | -                | -                | -         |    -8.73 | byr9, kensizor, munch, Polbandana, s4ltovsk1yy  |
|           41 |     5165 | 2024-03-04 | Insilio                | L   | 0.625      | -            | -                | -                | -         |   -10.13 | byr9, kensizor, munch, Polbandana, s4ltovsk1yy  |
|           40 |     5227 | 2024-03-03 | ex-Preasy Esport       | L   | 0.617      | -            | -                | -                | -         |    -9.94 | byr9, kensizor, munch, Polbandana, s4ltovsk1yy  |
|           39 |     5275 | 2024-03-02 | ENTERPRISE esports     | W   | 0.612      | -            | -                | -                | -         |    10.01 | byr9, kensizor, munch, Polbandana, s4ltovsk1yy  |
|           38 |     5306 | 2024-03-02 | Nemiga Gaming          | W   | 0.611      | 0.143        | 0.358 (0.031)    | -                | -         |    16.34 | byr9, kensizor, munch, Polbandana, s4ltovsk1yy  |
|           37 |     5345 | 2024-03-02 | MOUZ NXT               | L   | 0.609      | -            | -                | -                | -         |    -5.58 | byr9, kensizor, munch, Polbandana, s4ltovsk1yy  |
|           36 |     5380 | 2024-03-01 | Endpoint               | L   | 0.604      | -            | -                | -                | -         |   -10.40 | AZUWU, MiGHTYMAX, sl3nd, Surreal, swicher       |
|           35 |     5460 | 2024-02-28 | Aurora Gaming          | L   | 0.591      | -            | -                | -                | -         |    -1.33 | BELCHONOKK, deko, KENSI, Lack1, Norwi           |
|           34 |     5478 | 2024-02-28 | KOI                    | L   | 0.590      | -            | -                | -                | -         |    -7.91 | byr9, kensizor, munch, Polbandana, s4ltovsk1yy  |
|           33 |     5509 | 2024-02-27 | DMS                    | W   | 0.584      | -            | -                | -                | -         |     4.43 | AW, H1te, kAlash, sFade8, sm3t                  |
|           32 |     5521 | 2024-02-27 | INGLORIOUS             | W   | 0.584      | -            | -                | -                | -         |     5.38 | Drobnyy, Esphirion, Jad0R1x, LAYM, V1           |
|           31 |     5532 | 2024-02-27 | AURA                   | W   | 0.583      | -            | -                | -                | -         |     3.22 | byr9, kensizor, munch, Polbandana, s4ltovsk1yy  |
|           30 |     5553 | 2024-02-26 | ENTERPRISE esports     | W   | 0.578      | -            | -                | -                | -         |    10.26 | byr9, kensizor, munch, Polbandana, s4ltovsk1yy  |
|           29 |     5811 | 2024-02-22 | DASH                   | W   | 0.551      | -            | -                | -                | -         |     4.02 | byr9, kensizor, munch, Polbandana, s4ltovsk1yy  |
|           28 |     5867 | 2024-02-21 | CYBERSHOKE Esports     | W   | 0.544      | -            | -                | -                | -         |     2.48 | byr9, kensizor, munch, Polbandana, s4ltovsk1yy  |
|           27 |     5928 | 2024-02-20 | ex-Anonymo Esports     | W   | 0.537      | -            | -                | -                | -         |     4.10 | byr9, kensizor, munch, Polbandana, s4ltovsk1yy  |
|           26 |     6110 | 2024-02-17 | Aurora Gaming          | L   | 0.517      | -            | -                | -                | -         |    -0.90 | byr9, kensizor, munch, Polbandana, s4ltovsk1yy  |
|           25 |     6113 | 2024-02-17 | The Chosen Few         | W   | 0.517      | -            | -                | -                | -         |     4.58 | byr9, kensizor, munch, Polbandana, s4ltovsk1yy  |
|           24 |     6123 | 2024-02-17 | Aurora Gaming          | L   | 0.516      | -            | -                | -                | -         |    -0.84 | byr9, kensizor, munch, Polbandana, s4ltovsk1yy  |
|           23 |     6154 | 2024-02-16 | Team Spirit Academy    | W   | 0.511      | -            | -                | -                | -         |     5.05 | byr9, kensizor, munch, Polbandana, s4ltovsk1yy  |
|           22 |     6380 | 2024-02-12 | ex-sYnck               | L   | 0.484      | -            | -                | -                | -         |   -11.20 | eku, fejtZ, Jyo, Wahtzz, xezr                   |
|           21 |     6443 | 2024-02-10 | Betera Esports         | W   | 0.471      | -            | -                | -                | -         |     5.79 | byr9, kensizor, munch, Polbandana, s4ltovsk1yy  |
|           20 |     6449 | 2024-02-10 | ILLYRIANS              | W   | 0.471      | -            | -                | -                | -         |     3.90 | byr9, kensizor, munch, Polbandana, s4ltovsk1yy  |
|           19 |     6458 | 2024-02-10 | ex-K10                 | W   | 0.470      | -            | -                | -                | -         |     5.47 | Rezst, shyyne, SLY, Tree, yz0                   |
|           18 |     6515 | 2024-02-08 | GenOne                 | W   | 0.457      | -            | -                | -                | -         |     2.67 | devoduvek, drac, Revol, SIXER, unshaark         |
|           17 |     6544 | 2024-02-07 | UNiTY esports          | W   | 0.451      | -            | -                | -                | -         |     6.91 | Levi, luko, M1key, NIO, Pechyn                  |
|           16 |     6701 | 2024-02-03 | UNiTY esports          | W   | 0.424      | -            | -                | -                | -         |     6.87 | byr9, kensizor, munch, Polbandana, s4ltovsk1yy  |
|           15 |     6713 | 2024-02-03 | 9Pandas                | W   | 0.424      | 0.143        | 0.110 (0.007)    | -                | -         |    11.22 | clax, d1Ledez, glowiing, iDISBALANCE, seized    |
|           14 |     6743 | 2024-02-03 | team amster333         | W   | 0.423      | -            | -                | -                | -         |     1.32 | amster, h1glaiN, miL4nNNNNNN, muR, uQlutzavr    |
|           13 |     6752 | 2024-02-03 | HIMARSpeek             | W   | 0.423      | -            | -                | -                | -         |     0.82 | 2kEloLover, darky, GeT FiGhT, OG_JOY, steffe    |
|           12 |     6871 | 2024-02-01 | BAKS Esports           | W   | 0.411      | -            | -                | -                | -         |     2.49 | byr9, kensizor, munch, Polbandana, s4ltovsk1yy  |
|           11 |     6915 | 2024-01-31 | Permitta Esports       | W   | 0.404      | 0.371        | -                | 1.000 (0.150)    | -         |     7.90 | bnox, maaryy, mASKED, morelz, Vegi              |
|           10 |     7007 | 2024-01-29 | Insilio                | L   | 0.392      | -            | -                | -                | -         |    -5.57 | faydett, FpSSS, Pipw, Polt, sugaR               |
|            9 |     7022 | 2024-01-29 | ALTERNATE aTTaX        | W   | 0.392      | -            | -                | -                | -         |     8.28 | amster, byr9, munch, Polbandana, s4ltovsk1yy    |
|            8 |     7419 | 2024-01-23 | VP.Prodigy             | L   | 0.351      | -            | -                | -                | -         |    -5.84 | byr9, kensizor, munch, Polbandana, s4ltovsk1yy  |
|            7 |     7457 | 2024-01-22 | Zero Tenacity          | W   | 0.344      | 0.371        | 0.147 (0.019)    | -                | -         |     8.03 | byr9, kensizor, munch, Polbandana, s4ltovsk1yy  |
|            6 |     7700 | 2024-01-18 | INGLORIOUS             | W   | 0.318      | -            | -                | -                | -         |     3.30 | byr9, kensizor, munch, Polbandana, s4ltovsk1yy  |
|            5 |     7800 | 2024-01-17 | PARIVISION             | L   | 0.311      | -            | -                | -                | -         |    -4.18 | byr9, kensizor, munch, Polbandana, s4ltovsk1yy  |
|            4 |     7916 | 2024-01-16 | Verdant                | L   | 0.304      | -            | -                | -                | -         |    -2.63 | byr9, kensizor, munch, Polbandana, s4ltovsk1yy  |
|            3 |     8334 | 2024-01-09 | Entropiq               | L   | 0.258      | -            | -                | -                | -         |    -6.32 | byr9, kensizor, munch, Polbandana, s4ltovsk1yy  |
|            2 |     8339 | 2024-01-09 | ex-Anonymo Esports     | W   | 0.257      | -            | -                | -                | -         |     2.26 | byr9, kensizor, munch, Polbandana, s4ltovsk1yy  |
|            1 |     8374 | 2024-01-09 | TEAM MAX               | W   | 0.257      | -            | -                | -                | -         |     0.96 | byr9, kensizor, munch, Polbandana, s4ltovsk1yy  |

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
