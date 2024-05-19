### Roster Details<br />
Team Name: Lemondogs<br />
Roster: dZ, hechtikal, siz, xelos, zeak<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [327](../standings_global.md)<br />
Regional Rank: [199]( ../standings_europe.md)<br />
Final Rank Value:  562.3<br />
<br />
Final Rank Value (562.3) = Starting Rank Value (578.8) + Head To Head Adjustments (-16.5)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.000[<sup>1</sup>](#table2)
- Bounty Collected: 0.271[<sup>2</sup>](#table1)
- Opponent Network: 0.089[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.090<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 578.8
- 400 + ( ( 0.090 - 0.000 ) / ( 0.806 - 0.000 ) ) * 1600 = 578.8


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent                    | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                   |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           38 |        8 | 2024-05-05 | LODIS                       | L   | 1.000      | -            | -                | -                | -         |   -15.59 | dZ, hechtikal, siz, xelos, zeak          |
|           37 |       93 | 2024-05-03 | Supermatch                  | L   | 1.000      | -            | -                | -                | -         |   -22.85 | dZ, hechtikal, siz, xelos, zeak          |
|           36 |      464 | 2024-04-25 | Verdant                     | W   | 1.000      | 0.371        | 0.027 (0.010)    | 0.662 (0.246)    | 0 (0.000) |    26.43 | dZ, hechtikal, siz, xelos, zeak          |
|           35 |      474 | 2024-04-25 | VaselineWorms               | W   | 1.000      | 0.371        | 0.001 (0.000)    | 0.164 (0.061)    | 0 (0.000) |    17.72 | dZ, hechtikal, siz, xelos, zeak          |
|           34 |      599 | 2024-04-22 | TopTab Club                 | L   | 1.000      | -            | -                | -                | -         |   -17.86 | dalito, dZ, hechtikal, xelos, zeak       |
|           33 |      949 | 2024-04-17 | UNiTY esports (Slovak team) | L   | 1.000      | -            | -                | -                | -         |    -4.14 | dZ, hechtikal, siz, xelos, zeak          |
|           32 |     1072 | 2024-04-14 | VP.Prodigy                  | W   | 1.000      | 0.333        | 0.029 (0.010)    | 0.762 (0.254)    | 0 (0.000) |    26.34 | dZ, hechtikal, siz, xelos, zeak          |
|           31 |     1169 | 2024-04-11 | Kario Mart                  | W   | 1.000      | 0.143        | 0.000 (0.000)    | 0.068 (0.010)    | 0 (0.000) |    10.11 | dZ, hechtikal, LNZ, xelos, zeak          |
|           30 |     1211 | 2024-04-10 | BLESSED (Ukrainian team)    | L   | 1.000      | -            | -                | -                | -         |    -2.61 | dZ, hechtikal, siz, xelos, zeak          |
|           29 |     1225 | 2024-04-10 | Grindas                     | L   | 1.000      | -            | -                | -                | -         |    -9.78 | dZ, hechtikal, siz, xelos, zeak          |
|           28 |     1290 | 2024-04-09 | Aurora Young Blud           | L   | 1.000      | -            | -                | -                | -         |    -6.63 | dZ, hechtikal, siz, xelos, zeak          |
|           27 |     1488 | 2024-04-04 | Lilmix                      | L   | 0.991      | -            | -                | -                | -         |   -11.13 | dZ, hechtikal, LNZ, xelos, zeak          |
|           26 |     1522 | 2024-04-03 | Podwars                     | L   | 0.986      | -            | -                | -                | -         |   -19.22 | dZ, hechtikal, siz, xelos, zeak          |
|           25 |     2054 | 2024-03-19 | Kappa Borr                  | L   | 0.885      | -            | -                | -                | -         |   -15.34 | dZ, hechtikal, LNZ, xelos, zeak          |
|           24 |     2262 | 2024-03-14 | Young Gods                  | W   | 0.852      | 0.143        | 0.000 (0.000)    | 0.204 (0.025)    | 0 (0.000) |     8.66 | dZ, hechtikal, LNZ, xelos, zeak          |
|           23 |     2508 | 2024-03-09 | Metizport                   | L   | 0.817      | -            | -                | -                | -         |    -1.27 | dZ, hechtikal, khobra, xelos, zeak       |
|           22 |     2512 | 2024-03-09 | Lilmix                      | W   | 0.817      | 0.143        | 0.000 (0.000)    | 0.604 (0.070)    | 0 (0.000) |    13.66 | dZ, hechtikal, khobra, xelos, zeak       |
|           21 |     2940 | 2024-02-29 | Lilmix                      | W   | 0.759      | 0.371        | 0.000 (0.000)    | 0.604 (0.170)    | 0 (0.000) |    14.41 | dZ, hechtikal, hemzk9, xelos, zeak       |
|           20 |     2950 | 2024-02-29 | Ex-KRC Genk Esports         | L   | 0.758      | -            | -                | -                | -         |    -6.61 | dZ, hechtikal, hemzk9, xelos, zeak       |
|           19 |     2977 | 2024-02-28 | Lajtbitexe                  | W   | 0.752      | 0.371        | 0.000 (0.000)    | 0.033 (0.009)    | 0 (0.000) |    10.54 | dZ, hechtikal, hemzk9, xelos, zeak       |
|           18 |     3022 | 2024-02-27 | Rhyno Esports               | L   | 0.745      | -            | -                | -                | -         |    -3.45 | dZ, hechtikal, hemzk9, xelos, zeak       |
|           17 |     3582 | 2024-02-15 | 1win                        | L   | 0.665      | -            | -                | -                | -         |    -6.06 | dZ, hechtikal, hemzk9, xelos, zeak       |
|           16 |     3715 | 2024-02-12 | Passion UA                  | L   | 0.645      | -            | -                | -                | -         |    -2.41 | dZ, hechtikal, hemzk9, xelos, zeak       |
|           15 |     4795 | 2024-01-16 | Aurora Young Blud           | L   | 0.466      | -            | -                | -                | -         |    -2.87 | bl1x1, bluewh1te, Easy, sh1geo, VILBy    |
|           14 |     4807 | 2024-01-16 | MIREA                       | W   | 0.465      | 0.143        | 0.000 (0.000)    | -                | 0 (0.000) |     3.92 | Ban4ik, k3x, s1leNceRr, SanZirro, YarNik |
|           13 |     6166 | 2023-12-01 | The Chosen Few              | W   | 0.158      | 0.371        | 0.007 (0.000)    | 0.457 (0.027)    | 0 (0.000) |     3.92 | hybrid, Libido, shaiK, Skrimo, SPELLAN   |
|           12 |     6215 | 2023-11-30 | Ex-Anonymo Esports          | L   | 0.151      | -            | -                | -                | -         |    -1.22 | lunAtic, reiko, SaMey, Sobol, virtuoso   |
|           11 |     6394 | 2023-11-26 | Ex-sYnck                    | L   | 0.125      | -            | -                | -                | -         |    -2.07 | eku, fejtZ, Jyo, Wahtzz, xezr            |
|           10 |     6504 | 2023-11-23 | TY                          | L   | 0.106      | -            | -                | -                | -         |    -1.14 | fierre, maty, spardaus, tooizera, yakuza |
|            9 |     6510 | 2023-11-23 | DMS                         | W   | 0.105      | 0.371        | -                | 0.504 (0.020)    | -         |     1.99 | AW, H1te, kAlash, sFade8, sm3t           |
|            8 |     6667 | 2023-11-19 | Lilmix                      | L   | 0.078      | -            | -                | -                | -         |    -0.80 | Brillo, dZ, hechtikal, treckiz, zeak     |
|            7 |     6953 | 2023-11-13 | BLESSED (Ukrainian team)    | L   | 0.039      | -            | -                | -                | -         |    -0.23 | bondik, Edward, MUV, Smash, t3ns1on      |
|            6 |     6971 | 2023-11-13 | Lemondogs                   | L   | 0.038      | -            | -                | -                | -         |    -0.78 | flaw, hemzk9, pyth, Radifaction, xelos   |
|            5 |     7005 | 2023-11-12 | BIG Academy                 | L   | 0.031      | -            | -                | -                | -         |    -0.21 | ArroW, hyped, MRC9, pr1metapz, skyye     |
|            4 |     7086 | 2023-11-10 | ENTERPRISE esports          | L   | 0.019      | -            | -                | -                | -         |    -0.06 | bajmi, Demho, Ex1st, fr3nd, Klameczka    |
|            3 |     7092 | 2023-11-10 | Gaimin Gladiators           | L   | 0.018      | -            | -                | -                | -         |    -0.00 | kraghen, Nodios, Patti, Queenix, salazar |
|            2 |     7129 | 2023-11-09 | Curlews                     | W   | 0.012      | -            | -                | -                | -         |     0.10 | Eken, king666, lindeen, Malte, poiii     |
|            1 |     7184 | 2023-11-08 | Full Kareta                 | W   | 0.005      | -            | -                | -                | -         |     0.04 | Brillo, dZ, hechtikal, treckiz, zeak     |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($0.00)
- Divide that value by the 5th highest value among all rosters ($158,437.64)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
