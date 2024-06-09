### Roster Details<br />
Team Name: WOPA Esport<br />
Roster: brzer, Gnøffe, Leakz, LUMSEN, Vster<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [167](../standings_global.md)<br />
Regional Rank: [116]( ../standings_europe.md)<br />
Final Rank Value:  765.4<br />
<br />
Final Rank Value (765.4) = Starting Rank Value (822.9) + Head To Head Adjustments (-57.5)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.289[<sup>1</sup>](#table2)
- Bounty Collected: 0.352[<sup>2</sup>](#table1)
- Opponent Network: 0.191[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.208<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 822.9
- 400 + ( ( 0.208 - 0.000 ) / ( 0.787 - 0.000 ) ) * 1600 = 822.9


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent                  | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                         |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           88 |       78 | 2024-05-29 | 777 Esports               | W   | 1.000      | 0.143        | 0.029 (0.004)    | 0.463 (0.066)    | 0 (0.000) |    17.05 | brzer, Gnøffe, Leakz, LUMSEN, Vster            |
|           87 |      174 | 2024-05-27 | Sashi Esport              | W   | 1.000      | 0.143        | 0.154 (0.022)    | 1.000 (0.143)    | 0 (0.000) |    29.26 | brzer, Gnøffe, Leakz, LUMSEN, Vster            |
|           86 |      186 | 2024-05-27 | Copenhagen Wolves         | L   | 1.000      | -            | -                | -                | -         |   -16.14 | brzer, Gnøffe, Leakz, LUMSEN, Vster            |
|           85 |      397 | 2024-05-23 | ENRAGE                    | W   | 1.000      | -            | -                | -                | 0 (0.000) |     7.50 | brzer, Gnøffe, Leakz, LUMSEN, Vster            |
|           84 |      409 | 2024-05-23 | GamerLegion Academy       | W   | 1.000      | 0.372        | 0.018 (0.007)    | 0.691 (0.257)    | 0 (0.000) |    20.05 | brzer, Gnøffe, Leakz, LUMSEN, Vster            |
|           83 |      417 | 2024-05-23 | ARCRED                    | L   | 1.000      | -            | -                | -                | -         |    -8.09 | brzer, Gnøffe, Leakz, LUMSEN, Vster            |
|           82 |      423 | 2024-05-23 | FAVBET Team               | L   | 1.000      | -            | -                | -                | -         |    -5.61 | brzer, Gnøffe, Leakz, LUMSEN, Vster            |
|           81 |      475 | 2024-05-22 | VaselineWorms             | L   | 1.000      | -            | -                | -                | -         |   -15.06 | brzer, Gnøffe, Leakz, LUMSEN, Vster            |
|           80 |      504 | 2024-05-22 | Copenhagen Wolves         | L   | 1.000      | -            | -                | -                | -         |   -18.62 | brzer, Gnøffe, Leakz, LUMSEN, Vster            |
|           79 |      618 | 2024-05-21 | HyperSpirit               | L   | 1.000      | -            | -                | -                | -         |   -15.49 | brzer, Gnøffe, Leakz, LUMSEN, Vster            |
|           78 |      665 | 2024-05-20 | XI Esport                 | L   | 1.000      | -            | -                | -                | -         |   -20.14 | brzer, Gnøffe, Leakz, LUMSEN, Vster            |
|           77 |      695 | 2024-05-20 | IMMAPROBLEM               | W   | 1.000      | -            | -                | -                | 0 (0.000) |     8.12 | brzer, Gnøffe, Leakz, LUMSEN, Vster            |
|           76 |      700 | 2024-05-20 | Astralis Talent           | W   | 1.000      | 0.143        | 0.012 (0.002)    | -                | 0 (0.000) |    15.14 | brzer, Gnøffe, Leakz, LUMSEN, Vster            |
|           75 |      748 | 2024-05-19 | Passion UA                | W   | 1.000      | 0.372        | 0.057 (0.021)    | 1.000 (0.372)    | 0 (0.000) |    23.06 | brzer, Gnøffe, Leakz, LUMSEN, Vster            |
|           74 |      944 | 2024-05-18 | PSYCHOACTiVE              | W   | 1.000      | -            | -                | -                | 0 (0.000) |     6.68 | addi, brzer, Gnøffe, Leakz, LUMSEN             |
|           73 |      984 | 2024-05-17 | VP.Prodigy                | L   | 1.000      | -            | -                | -                | -         |   -11.66 | brzer, Gnøffe, Leakz, LUMSEN, Vster            |
|           72 |     1019 | 2024-05-17 | LEON Esports              | L   | 1.000      | -            | -                | -                | -         |   -17.41 | brzer, Gnøffe, Leakz, LUMSEN, Vster            |
|           71 |     1181 | 2024-05-15 | Insilio                   | L   | 1.000      | -            | -                | -                | -         |    -8.03 | brzer, Gnøffe, Leakz, LUMSEN, Vster            |
|           70 |     1259 | 2024-05-14 | Zero Tenacity             | W   | 1.000      | 0.372        | 0.147 (0.055)    | 1.000 (0.372)    | 0 (0.000) |    25.92 | brzer, Gnøffe, Leakz, LUMSEN, Vster            |
|           69 |     1297 | 2024-05-14 | Team Secret               | W   | 1.000      | -            | -                | -                | -         |    12.00 | brzer, Gnøffe, Leakz, LUMSEN, Vster            |
|           68 |     1332 | 2024-05-13 | VP.Prodigy                | L   | 1.000      | -            | -                | -                | -         |   -11.89 | brzer, Gnøffe, Leakz, LUMSEN, Vster            |
|           67 |     1650 | 2024-05-08 | Young Gods                | L   | 1.000      | -            | -                | -                | -         |   -23.52 | brzer, Gnøffe, Leakz, LUMSEN, Vster            |
|           66 |     1692 | 2024-05-07 | AscendX Esports           | W   | 1.000      | -            | -                | -                | -         |     3.18 | brzer, Gnøffe, Leakz, LUMSEN, Vster            |
|           65 |     1701 | 2024-05-07 | ThunderFlash              | L   | 1.000      | -            | -                | -                | -         |   -12.15 | brzer, Gnøffe, Leakz, LUMSEN, Vster            |
|           64 |     1731 | 2024-05-06 | Preasy Esport             | W   | 1.000      | 0.143        | -                | 0.705 (0.101)    | -         |    15.57 | brzer, Gnøffe, Leakz, LUMSEN, Vster            |
|           63 |     1746 | 2024-05-06 | Astralis Talent           | W   | 1.000      | 0.143        | 0.012 (0.002)    | -                | -         |    17.86 | brzer, Gnøffe, Leakz, LUMSEN, Vster            |
|           62 |     1751 | 2024-05-06 | IMMAPROBLEM               | L   | 1.000      | -            | -                | -                | -         |   -23.93 | brzer, Gnøffe, Leakz, LUMSEN, Vster            |
|           61 |     1852 | 2024-05-04 | Copenhagen Wolves         | W   | 1.000      | -            | -                | -                | -         |    13.00 | brzer, Gnøffe, Leakz, LUMSEN, Vster            |
|           60 |     1870 | 2024-05-04 | UNiTY esports             | L   | 1.000      | -            | -                | -                | -         |   -10.77 | brzer, Gnøffe, Leakz, LUMSEN, Vster            |
|           59 |     1961 | 2024-05-02 | Astralis Talent           | W   | 1.000      | 0.333        | 0.012 (0.004)    | 0.452 (0.151)    | -         |    20.52 | brzer, Gnøffe, Kragh, LUMSEN, Vster            |
|           58 |     2028 | 2024-05-01 | Preasy Esport             | L   | 1.000      | -            | -                | -                | -         |   -15.02 | brzer, Gnøffe, Leakz, LUMSEN, Vster            |
|           57 |     2104 | 2024-04-29 | Sashi Esport              | L   | 0.997      | -            | -                | -                | -         |    -2.11 | Boye, brzer, Gnøffe, LUMSEN, Vster             |
|           56 |     2162 | 2024-04-28 | UNiTY esports             | L   | 0.989      | -            | -                | -                | -         |   -10.85 | brzer, Gnøffe, Leakz, LUMSEN, Vster            |
|           55 |     2961 | 2024-04-16 | XI Esport                 | W   | 0.910      | -            | -                | -                | -         |     9.67 | brzer, Gnøffe, Leakz, LUMSEN, Vster            |
|           54 |     2969 | 2024-04-16 | Sashi Academy             | W   | 0.910      | -            | -                | -                | -         |     9.47 | brzer, Gnøffe, Leakz, LUMSEN, Vster            |
|           53 |     3092 | 2024-04-13 | Esport Harte              | L   | 0.890      | -            | -                | -                | -         |   -22.08 | brzer, Gnøffe, Leakz, LUMSEN, Vster            |
|           52 |     3102 | 2024-04-13 | Vendetta gaming           | W   | 0.890      | -            | -                | -                | -         |     2.99 | brzer, Gnøffe, Leakz, LUMSEN, Vster            |
|           51 |     3352 | 2024-04-09 | UNiTY esports             | L   | 0.861      | -            | -                | -                | -         |   -10.09 | brzer, Gnøffe, Leakz, LUMSEN, Vster            |
|           50 |     3538 | 2024-04-05 | Dynamo Eclot              | W   | 0.835      | 0.333        | 0.097 (0.027)    | 0.940 (0.262)    | -         |    21.09 | brzer, Gnøffe, Leakz, LUMSEN, Vster            |
|           49 |     3721 | 2024-04-01 | UNiTY esports             | L   | 0.809      | -            | -                | -                | -         |    -8.87 | K1-FiDa, Levi, M1key, NIO, Pechyn              |
|           48 |     3814 | 2024-03-29 | Astralis Talent           | L   | 0.788      | -            | -                | -                | -         |    -9.11 | brzer, Gnøffe, Leakz, LUMSEN, Pellyy           |
|           47 |     4018 | 2024-03-25 | Sashi Esport              | L   | 0.764      | -            | -                | -                | -         |   -11.72 | b0RUP, niko, nut nut, PR1mE, sL1m3             |
|           46 |     4106 | 2024-03-23 | K10                       | W   | 0.749      | -            | -                | -                | -         |     2.26 | brzer, Gnøffe, Leakz, LUMSEN, Pellyy           |
|           45 |     4237 | 2024-03-20 | HyperSpirit               | L   | 0.730      | -            | -                | -                | -         |   -12.64 | brzer, Gnøffe, Leakz, LUMSEN, Pellyy           |
|           44 |     4243 | 2024-03-20 | Astralis Talent           | L   | 0.729      | -            | -                | -                | -         |    -8.83 | brzer, Gnøffe, Leakz, LUMSEN, Pellyy           |
|           43 |     4276 | 2024-03-19 | ex-Turów Zgorzelec Esport | W   | 0.724      | 0.333        | 0.006 (0.001)    | 0.491 (0.118)    | -         |    10.20 | AxEcHo, darko, kadziu, Markoś, xKacpersky      |
|           42 |     4301 | 2024-03-18 | Raptors Esports Club      | L   | 0.718      | -            | -                | -                | -         |   -10.89 | brzer, Gnøffe, Leakz, LUMSEN, Pellyy           |
|           41 |     4410 | 2024-03-16 | ADEPTS                    | W   | 0.705      | 0.333        | -                | 0.291 (0.068)    | -         |    12.36 | cHeuuuuk, Chuckyy, Oxbrandd, prn, Tarkky       |
|           40 |     4716 | 2024-03-11 | TEAM MAX                  | W   | 0.671      | -            | -                | -                | -         |     3.92 | kL1o, Malkiss, tAk, tooizera, zecco            |
|           39 |     4739 | 2024-03-11 | Team Atlantic             | W   | 0.671      | -            | -                | -                | -         |     4.02 | brzer, Gnøffe, Leakz, LUMSEN, Pellyy           |
|           38 |     4937 | 2024-03-07 | Linx Legacy Madagaskar    | W   | 0.644      | -            | -                | -                | -         |     3.31 | dancer, fiction, kemi, masthead, Rezkiyy       |
|           37 |     4981 | 2024-03-06 | XI Esport                 | W   | 0.638      | -            | -                | -                | -         |     6.51 | anber, Dengzoe, fez, foam, Scr0b               |
|           36 |     4988 | 2024-03-06 | Astralis Talent           | L   | 0.638      | -            | -                | -                | -         |    -6.44 | brzer, Gnøffe, Leakz, LUMSEN, Pellyy           |
|           35 |     5003 | 2024-03-06 | Copenhagen Wolves         | W   | 0.637      | -            | -                | -                | -         |     6.37 | brzer, Gnøffe, Leakz, LUMSEN, Pellyy           |
|           34 |     5106 | 2024-03-05 | IMMAPROBLEM               | W   | 0.631      | -            | -                | -                | -         |     3.87 | Damkilde, daxy, NoProblemGuy, notaN, vester    |
|           33 |     5516 | 2024-02-27 | Preasy Esport             | L   | 0.584      | -            | -                | -                | -         |    -7.87 | brzer, Gnøffe, Leakz, LUMSEN, Pellyy           |
|           32 |     6405 | 2024-02-12 | brazylijski luz           | L   | 0.482      | -            | -                | -                | -         |    -7.16 | brzer, Gnøffe, Leakz, LUMSEN, Pellyy           |
|           31 |     6535 | 2024-02-08 | Copenhagen Wolves         | W   | 0.455      | -            | -                | -                | -         |     4.58 | Basso, mupzG, smF, Svedjehed, szejn            |
|           30 |     6572 | 2024-02-06 | Sashi Esport              | L   | 0.444      | -            | -                | -                | -         |    -7.56 | b0RUP, Fessor, niko, nut nut, sL1m3            |
|           29 |     6615 | 2024-02-05 | Team Atlantic             | W   | 0.438      | -            | -                | -                | -         |     2.44 | Folke, Inspire, logz, mupzG, Pellyy            |
|           28 |     6629 | 2024-02-05 | Astralis Talent           | L   | 0.437      | -            | -                | -                | -         |    -4.59 | ANSG1, JBOEN, kiR, kroK, tOPZ                  |
|           27 |     6645 | 2024-02-05 | Dynamo Eclot              | L   | 0.435      | -            | -                | -                | -         |    -2.39 | brzer, buNNy, Gnøffe, Leakz, LUMSEN            |
|           26 |     6821 | 2024-02-02 | Sashi Esport              | L   | 0.417      | -            | -                | -                | -         |    -2.48 | brzer, Gnøffe, Leakz, LUMSEN, Pellyy           |
|           25 |     6920 | 2024-01-31 | XI Esport                 | L   | 0.404      | -            | -                | -                | -         |    -8.63 | brzer, buNNy, Gnøffe, Leakz, LUMSEN            |
|           24 |     6972 | 2024-01-30 | Copenhagen Wolves         | W   | 0.398      | -            | -                | -                | -         |     3.98 | Basso, smF, Svedjehed, szejn, vigg0            |
|           23 |     7460 | 2024-01-22 | Preasy Esport             | W   | 0.344      | -            | -                | -                | -         |     6.49 | beccie, Equip, Griller, Skejs, VireZ           |
|           22 |     7473 | 2024-01-22 | IMMAPROBLEM               | W   | 0.344      | -            | -                | -                | -         |     1.90 | brzer, buNNy, Gnøffe, Leakz, LUMSEN            |
|           21 |     7674 | 2024-01-19 | MOUZ NXT                  | L   | 0.322      | -            | -                | -                | -         |    -1.50 | Chr1zN, kristou, Neityu, PR, sirah             |
|           20 |     7740 | 2024-01-18 | Monte Gen                 | L   | 0.316      | -            | -                | -                | -         |    -5.19 | Gizmy, leen, n0te, ryu, shield                 |
|           19 |     7812 | 2024-01-17 | 500                       | L   | 0.311      | -            | -                | -                | -         |    -5.46 | brzer, buNNy, Gnøffe, Leakz, LUMSEN            |
|           18 |     8055 | 2024-01-13 | ROSOMAHA                  | W   | 0.282      | -            | -                | -                | -         |     2.11 | D0nii, Maggent, rendY, skcH, Зippoch           |
|           17 |     8287 | 2024-01-10 | Nexus Gaming              | L   | 0.262      | -            | -                | -                | -         |    -3.23 | BTN, ERSIN, ragga, s0und, XELLOW               |
|           16 |     8358 | 2024-01-09 | Team Sampi                | L   | 0.257      | -            | -                | -                | -         |    -2.49 | brzer, buNNy, Gnøffe, Leakz, LUMSEN            |
|           15 |     8455 | 2024-01-07 | Lazer Cats                | W   | 0.242      | -            | -                | -                | -         |     1.04 | brzer, buNNy, Gnøffe, Leakz, LUMSEN            |
|           14 |     8470 | 2024-01-06 | MOUZ NXT                  | L   | 0.235      | -            | -                | -                | -         |    -1.17 | brzer, buNNy, Gnøffe, Leakz, LUMSEN            |
|           13 |     8522 | 2024-01-03 | Natus Vincere Junior      | W   | 0.216      | -            | -                | -                | -         |     3.19 | brzer, buNNy, Gnøffe, Leakz, LUMSEN            |
|           12 |     9042 | 2023-12-14 | latch gibb                | L   | 0.085      | -            | -                | -                | -         |    -2.31 | addi, brzer, Gnøffe, LUMSEN, tvs               |
|           11 |     9054 | 2023-12-14 | NOM Esports               | L   | 0.083      | -            | -                | -                | -         |    -1.91 | AMSALEM, BluePho3nix, dan1, ultimate, Zax1e    |
|           10 |     9155 | 2023-12-12 | Nexus Gaming              | L   | 0.069      | -            | -                | -                | -         |    -0.82 | brzer, buNNy, Gnøffe, Leakz, LUMSEN            |
|            9 |     9196 | 2023-12-11 | XI Esport                 | L   | 0.064      | -            | -                | -                | -         |    -1.36 | anber, Dengzoe, foam, Pellyy, Scr0b            |
|            8 |     9205 | 2023-12-11 | AGO esports               | W   | 0.062      | -            | -                | -                | -         |     0.17 | Dementor, DEPRESHN, sh3nanigan, Svedjehed, tAk |
|            7 |     9287 | 2023-12-09 | WHYKICK Team              | W   | 0.051      | -            | -                | -                | -         |     0.14 | CYXXX, Frothe, HEADBANGER, olymp1c, t3nzy      |
|            6 |     9397 | 2023-12-08 | Astralis Talent           | L   | 0.042      | -            | -                | -                | -         |    -0.48 | ANSG1, JBOEN, kiR, kroK, tOPZ                  |
|            5 |     9435 | 2023-12-07 | ex-KRC Genk Esports       | L   | 0.037      | -            | -                | -                | -         |    -0.77 | brzer, buNNy, Gnøffe, Leakz, LUMSEN            |
|            4 |     9582 | 2023-12-05 | ENTERPRISE esports        | W   | 0.024      | -            | -                | -                | -         |     0.12 | brzer, buNNy, Gnøffe, Leakz, LUMSEN            |
|            3 |     9627 | 2023-12-04 | AGO esports               | W   | 0.015      | -            | -                | -                | -         |     0.04 | brzer, buNNy, Gnøffe, Leakz, LUMSEN            |
|            2 |     9729 | 2023-12-02 | Sashi Esport              | L   | 0.004      | -            | -                | -                | -         |    -0.11 | brzer, buNNy, Gnøffe, Leakz, LUMSEN            |
|            1 |     9756 | 2023-12-02 | Team Atlantic             | W   | 0.004      | -            | -                | -                | 1 (0.004) |     0.01 | Basso, Inspire, smF, Vster, Zanto              |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($1,034.52)
- Divide that value by the 5th highest value among all rosters ($300,806.11)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-03-25 |      0.765 | $362.12        | $276.88         |
| 2024-03-23 |      0.751 | $1,000.00      | $751.25         |
| 2023-12-02 |      0.004 | $1,459.92      | $6.39           |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
