### Roster Details<br />
Team Name: ex-K10<br />
Roster: cryths, Rezst, shyyne, Tree, yz0<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [157](../standings_global.md)<br />
Regional Rank: [110]( ../standings_europe.md)<br />
Final Rank Value:  774.7<br />
<br />
Final Rank Value (774.7) = Starting Rank Value (873.4) + Head To Head Adjustments (-98.8)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.306[<sup>1</sup>](#table2)
- Bounty Collected: 0.279[<sup>2</sup>](#table1)
- Opponent Network: 0.151[<sup>2</sup>](#table1)
- LAN Wins: 0.196[<sup>2</sup>](#table1)

The average of these factors is 0.233<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 873.4
- 400 + ( ( 0.233 - 0.000 ) / ( 0.787 - 0.000 ) ) * 1600 = 873.4


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent             | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                        |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           80 |      571 | 2024-05-21 | Verdant              | W   | 1.000      | 0.143        | 0.014 (0.002)    | 1.000 (0.143)    | 0 (0.000) |    23.15 | cryths, Rezst, shyyne, Tree, yz0              |
|           79 |      664 | 2024-05-20 | FearFerox            | W   | 1.000      | -            | -                | -                | 0 (0.000) |    11.03 | cryths, Rezst, shyyne, Tree, yz0              |
|           78 |     1065 | 2024-05-16 | Team Invictum        | L   | 1.000      | -            | -                | -                | -         |   -19.23 | cryths, Rezst, shyyne, Tree, yz0              |
|           77 |     1252 | 2024-05-14 | Halal5               | W   | 1.000      | -            | -                | -                | 0 (0.000) |    11.39 | cryths, Geckeos, Rezst, Tree, yz0             |
|           76 |     1254 | 2024-05-14 | Dynamo Eclot         | L   | 1.000      | -            | -                | -                | -         |    -7.96 | Philong, Rezst, shyyne, SLY, yz0              |
|           75 |     1271 | 2024-05-14 | VaselineWorms        | L   | 1.000      | -            | -                | -                | -         |   -18.69 | Philong, Rezst, shyyne, SLY, yz0              |
|           74 |     1318 | 2024-05-13 | LOG Esports          | W   | 1.000      | -            | -                | -                | 0 (0.000) |     5.12 | Philong, Rezst, shyyne, SLY, yz0              |
|           73 |     1667 | 2024-05-08 | GamerLegion Academy  | L   | 1.000      | -            | -                | -                | -         |   -13.37 | Askan, AyeZ, Rezst, Tree, yz0                 |
|           72 |     1691 | 2024-05-07 | ex-KRC Genk Esports  | W   | 1.000      | -            | -                | -                | -         |    12.35 | Philong, Rezst, shyyne, SLY, yz0              |
|           71 |     1730 | 2024-05-06 | The Last Resort      | L   | 1.000      | -            | -                | -                | -         |   -19.51 | cryths, Rezst, shyyne, Tree, yz0              |
|           70 |     2000 | 2024-05-01 | DASH                 | L   | 1.000      | -            | -                | -                | -         |   -19.74 | cairne, Dawy, Flierax, Merl, Psycho           |
|           69 |     2008 | 2024-05-01 | Raptors Esports Club | W   | 1.000      | 0.143        | 0.007 (0.001)    | -                | -         |    18.24 | BehinDx, Karrar, moz, PrimeOPI, wfn           |
|           68 |     2017 | 2024-05-01 | ARROW                | W   | 1.000      | 0.372        | -                | 0.344 (0.128)    | -         |    13.94 | Philong, Rezst, shyyne, SLY, yz0              |
|           67 |     2029 | 2024-05-01 | Copenhagen Wolves    | L   | 1.000      | -            | -                | -                | -         |   -19.39 | Basso, Fessor, Svedjehed, szejn, vigg0        |
|           66 |     2055 | 2024-04-30 | ROYALS               | W   | 1.000      | -            | -                | -                | -         |    11.53 | cryths, Rezst, shyyne, Tree, yz0              |
|           65 |     2073 | 2024-04-30 | GamerLegion Academy  | W   | 1.000      | 0.333        | 0.018 (0.006)    | 0.691 (0.230)    | -         |    18.68 | Askan, AyeZ, Rezst, Tree, yz0                 |
|           64 |     2097 | 2024-04-29 | Zero Tenacity        | L   | 0.997      | -            | -                | -                | -         |    -6.75 | aVN, brutmonster, Cjoffo, nEMANHA, simke      |
|           63 |     2254 | 2024-04-27 | FAVBET Team          | L   | 0.981      | -            | -                | -                | -         |    -9.77 | Rezst, shyyne, SLY, Tree, yz0                 |
|           62 |     2451 | 2024-04-23 | Part Timers          | W   | 0.958      | -            | -                | -                | -         |    12.42 | cryths, Rezst, shyyne, Tree, yz0              |
|           61 |     2461 | 2024-04-23 | EXO Clan             | L   | 0.957      | -            | -                | -                | -         |    -6.05 | Adam9130, bevve, dobbo, MMS, shushan          |
|           60 |     2500 | 2024-04-22 | Lilmix               | L   | 0.950      | -            | -                | -                | -         |   -13.22 | Philong, Rezst, shyyne, SLY, yz0              |
|           59 |     2511 | 2024-04-22 | RoundsGG             | L   | 0.950      | -            | -                | -                | -         |   -21.75 | Kollo, m0n0xx, p12, p3kko, sLowi              |
|           58 |     3015 | 2024-04-15 | Young Gods           | W   | 0.903      | 0.372        | -                | 0.240 (0.081)    | -         |     5.56 | Cham, Focus, MaiL09, viz, Wonder              |
|           57 |     3114 | 2024-04-13 | UNiTY esports        | L   | 0.889      | -            | -                | -                | -         |   -12.46 | K1-FiDa, Levi, M1key, NIO, Pechyn             |
|           56 |     3203 | 2024-04-11 | Viperio              | L   | 0.875      | -            | -                | -                | -         |   -17.13 | Rezst, shyyne, SLY, Tree, yz0                 |
|           55 |     3507 | 2024-04-06 | ROSOMAHA             | W   | 0.841      | -            | -                | -                | -         |     5.56 | Rezst, shyyne, SLY, Tree, yz0                 |
|           54 |     3592 | 2024-04-04 | Verdant              | W   | 0.829      | 0.333        | 0.014 (0.004)    | 1.000 (0.276)    | -         |    17.79 | Rezst, shyyne, SLY, Tree, yz0                 |
|           53 |     3790 | 2024-03-29 | EXO Clan             | L   | 0.791      | -            | -                | -                | -         |    -6.29 | Adam9130, bevve, dobbo, eraa, Thomas          |
|           52 |     4202 | 2024-03-21 | Permitta Esports     | L   | 0.736      | -            | -                | -                | -         |    -6.54 | bnox, maaryy, mASKED, morelz, Vegi            |
|           51 |     4260 | 2024-03-19 | Part Timers          | W   | 0.725      | -            | -                | -                | -         |     8.43 | eMy, ifan, Rhys, Yoshwa, Ziimzey              |
|           50 |     4395 | 2024-03-17 | Passion UA           | L   | 0.709      | -            | -                | -                | -         |    -7.45 | Rezst, shyyne, SLY, Tree, yz0                 |
|           49 |     4558 | 2024-03-14 | Permitta Esports     | W   | 0.689      | 0.333        | 0.025 (0.006)    | 1.000 (0.230)    | -         |    16.39 | Rezst, shyyne, SLY, Tree, yz0                 |
|           48 |     4841 | 2024-03-09 | Insilio              | L   | 0.657      | -            | -                | -                | -         |    -6.45 | Rezst, shyyne, SLY, Tree, yz0                 |
|           47 |     4867 | 2024-03-09 | ex-Preasy Esport     | L   | 0.655      | -            | -                | -                | -         |    -5.55 | Altekz, kristou, refrezh, roeJ, TMB           |
|           46 |     4881 | 2024-03-08 | MOUZ NXT             | L   | 0.650      | -            | -                | -                | -         |    -3.59 | Rezst, shyyne, SLY, Tree, yz0                 |
|           45 |     5045 | 2024-03-06 | Passion UA           | L   | 0.636      | -            | -                | -                | -         |    -6.76 | Rezst, shyyne, SLY, Tree, yz0                 |
|           44 |     5193 | 2024-03-04 | Team Secret          | W   | 0.623      | -            | -                | -                | -         |     5.44 | Rezst, shyyne, SLY, Tree, yz0                 |
|           43 |     5255 | 2024-03-03 | ENCE Academy         | L   | 0.616      | -            | -                | -                | -         |    -9.25 | Rezst, shyyne, SLY, Tree, yz0                 |
|           42 |     5381 | 2024-03-01 | HOTU                 | W   | 0.604      | 0.371        | 0.004 (0.001)    | 0.580 (0.130)    | -         |     9.81 | Rezst, shyyne, SLY, Tree, yz0                 |
|           41 |     5385 | 2024-03-01 | CYBERSHOKE Esports   | L   | 0.603      | -            | -                | -                | -         |   -14.26 | Rezst, shyyne, SLY, Tree, yz0                 |
|           40 |     5399 | 2024-02-29 | Verdant              | W   | 0.598      | 0.143        | 0.014 (0.001)    | 1.000 (0.085)    | -         |    11.88 | arTisT, Ducky, Girafffe, Vacancy, Zax1e       |
|           39 |     5438 | 2024-02-29 | Aurora Young Blud    | L   | 0.596      | -            | -                | -                | -         |   -11.04 | Rezst, shyyne, SLY, Tree, yz0                 |
|           38 |     5527 | 2024-02-27 | ENCE Academy         | L   | 0.583      | -            | -                | -                | -         |    -9.18 | Rezst, shyyne, SLY, Tree, yz0                 |
|           37 |     5617 | 2024-02-25 | EXO Clan             | L   | 0.570      | -            | -                | -                | -         |    -5.68 | Adam9130, bevve, dobbo, Extinct, smooya       |
|           36 |     5690 | 2024-02-24 | EXO Clan             | W   | 0.564      | 0.143        | 0.013 (0.001)    | -                | 1 (0.564) |    12.34 | Rezst, shyyne, SLY, Tree, yz0                 |
|           35 |     5715 | 2024-02-24 | Raptors Esports Club | W   | 0.563      | -            | -                | -                | 1 (0.563) |     8.62 | Rezst, shyyne, SLY, Tree, yz0                 |
|           34 |     5757 | 2024-02-23 | Part Timers          | W   | 0.558      | -            | -                | -                | 1 (0.558) |     6.89 | CYPHER, ifan, JackB, JAUSTERE, Yoshwa         |
|           33 |     5919 | 2024-02-20 | Raptors Esports Club | W   | 0.538      | -            | -                | -                | -         |     8.96 | Kisynergy, Rezst, shyyne, Tree, yz0           |
|           32 |     6182 | 2024-02-16 | Passion UA           | L   | 0.508      | -            | -                | -                | -         |    -5.00 | Rezst, shyyne, SLY, Tree, yz0                 |
|           31 |     6206 | 2024-02-15 | Souls-Land           | W   | 0.505      | -            | -                | -                | -         |     2.36 | Deg1l, EthanChen, Harborboy, SundanceK1d, xrt |
|           30 |     6213 | 2024-02-15 | The Neighbours       | W   | 0.504      | -            | -                | -                | -         |     4.55 | Kisynergy, Rezst, shyyne, Tree, yz0           |
|           29 |     6232 | 2024-02-15 | GamerLegion Academy  | W   | 0.503      | 0.371        | 0.018 (0.003)    | 0.691 (0.129)    | -         |     7.76 | Rezst, shyyne, SLY, Tree, yz0                 |
|           28 |     6249 | 2024-02-15 | Lilmix               | L   | 0.502      | -            | -                | -                | -         |    -7.54 | Rezst, shyyne, SLY, Tree, yz0                 |
|           27 |     6300 | 2024-02-14 | Dynamo Eclot         | L   | 0.496      | -            | -                | -                | -         |    -2.70 | Blytz, Dytor, forsyy, kreaz, nbqq             |
|           26 |     6338 | 2024-02-13 | ILIN                 | L   | 0.491      | -            | -                | -                | -         |   -12.79 | Rezst, shyyne, SLY, Tree, yz0                 |
|           25 |     6344 | 2024-02-13 | lajtbitexe           | W   | 0.490      | -            | -                | -                | -         |     3.68 | Rezst, shyyne, SLY, Tree, yz0                 |
|           24 |     6358 | 2024-02-13 | ROSOMAHA             | W   | 0.488      | -            | -                | -                | -         |     3.42 | D0nii, Maggent, rendY, skcH, Зippoch          |
|           23 |     6379 | 2024-02-12 | LODIS                | W   | 0.484      | -            | -                | -                | -         |     3.97 | Rezst, shyyne, SLY, Tree, yz0                 |
|           22 |     6395 | 2024-02-12 | RoundsGG             | W   | 0.484      | -            | -                | -                | -         |     3.88 | Kollo, LYNXi, m0n0xx, p12, Welho              |
|           21 |     6435 | 2024-02-11 | MOUZ NXT             | L   | 0.476      | -            | -                | -                | -         |    -2.63 | Rezst, shyyne, SLY, Tree, yz0                 |
|           20 |     6458 | 2024-02-10 | kONO.ECF             | L   | 0.470      | -            | -                | -                | -         |    -5.47 | Rezst, shyyne, SLY, Tree, yz0                 |
|           19 |     6468 | 2024-02-10 | Viperio              | L   | 0.468      | -            | -                | -                | -         |   -11.08 | Rezst, shyyne, SLY, Tree, yz0                 |
|           18 |     6540 | 2024-02-07 | Part Timers          | L   | 0.451      | -            | -                | -                | -         |    -9.32 | eMy, ifan, Rhys, Yoshwa, Ziimzey              |
|           17 |     6747 | 2024-02-03 | Viperio              | L   | 0.423      | -            | -                | -                | -         |   -10.67 | mAnGo, MMS, pandi7o, ReegaN, zodi             |
|           16 |     6757 | 2024-02-03 | The Last Resort      | W   | 0.423      | -            | -                | -                | -         |     3.48 | AdamJC, Bigun, Fizzy, Flicky, ve1nzo          |
|           15 |     6910 | 2024-01-31 | Grannys Knockers     | W   | 0.404      | 0.371        | 0.006 (0.001)    | 0.517 (0.078)    | -         |     5.46 | dox, Rezst, shyyne, Tree, yz0                 |
|           14 |     7011 | 2024-01-29 | Sprout               | L   | 0.392      | -            | -                | -                | -         |    -9.48 | MAGILA, Rezst, shyyne, Tree, yz0              |
|           13 |     7182 | 2024-01-27 | 9INE                 | L   | 0.377      | -            | -                | -                | -         |    -9.96 | dox, Rezst, shyyne, Tree, yz0                 |
|           12 |     7305 | 2024-01-25 | ENTERPRISE esports   | L   | 0.364      | -            | -                | -                | -         |    -3.72 | bajmi, Demho, Ex1st, fr3nd, TOAO              |
|           11 |     7350 | 2024-01-24 | GODSENT              | W   | 0.357      | -            | -                | -                | -         |     2.68 | dox, Rezst, shyyne, Tree, yz0                 |
|           10 |     7456 | 2024-01-22 | ex-Hot Headed Gaming | L   | 0.344      | -            | -                | -                | -         |    -9.63 | dox, Rezst, shyyne, Tree, yz0                 |
|            9 |     7567 | 2024-01-20 | 0to100               | W   | 0.331      | -            | -                | -                | -         |     1.03 | juliustbe, kerogi, krea6on, uQlutzavr, v1ze   |
|            8 |     8268 | 2024-01-10 | Permitta Esports     | L   | 0.265      | -            | -                | -                | -         |    -3.21 | dox, Rezst, shyyne, Tree, yz0                 |
|            7 |     8333 | 2024-01-09 | KOI                  | L   | 0.258      | -            | -                | -                | -         |    -3.08 | dox, Rezst, shyyne, Tree, yz0                 |
|            6 |     8355 | 2024-01-09 | Nexus Gaming         | W   | 0.257      | -            | -                | -                | -         |     4.28 | BTN, ERSIN, ragga, s0und, XELLOW              |
|            5 |     8385 | 2024-01-09 | Sashi Esport         | W   | 0.257      | -            | -                | -                | -         |     1.15 | dox, Rezst, shyyne, Tree, yz0                 |
|            4 |     9221 | 2023-12-10 | Verdant              | W   | 0.058      | -            | -                | -                | 1 (0.058) |     1.32 | dox, Rezst, shyyne, Tree, yz0                 |
|            3 |     9238 | 2023-12-10 | DuckDuckGOOSE        | W   | 0.056      | -            | -                | -                | 1 (0.056) |     0.20 | BehinDx, Fizzy, Karrar, luccs, moz            |
|            2 |     9253 | 2023-12-10 | Verdant              | L   | 0.056      | -            | -                | -                | -         |    -0.48 | dox, Rezst, shyyne, Tree, yz0                 |
|            1 |     9297 | 2023-12-09 | Viperio              | W   | 0.050      | -            | -                | -                | 1 (0.050) |     0.27 | dox, Rezst, shyyne, Tree, yz0                 |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($1,608.39)
- Divide that value by the 5th highest value among all rosters ($300,806.11)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-03-29 |      0.791 | $946.43        | $749.00         |
| 2024-02-25 |      0.570 | $1,204.50      | $686.23         |
| 2023-12-10 |      0.058 | $3,011.52      | $173.16         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
