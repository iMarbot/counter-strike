### Roster Details<br />
Team Name: ex-K10<br />
Roster: cryths, Rezst, shyyne, Tree, yz0<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [148](../standings_global.md)<br />
Regional Rank: [102]( ../standings_europe.md)<br />
Final Rank Value:  778.9<br />
<br />
Final Rank Value (778.9) = Starting Rank Value (853.3) + Head To Head Adjustments (-74.4)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.306[<sup>1</sup>](#table2)
- Bounty Collected: 0.272[<sup>2</sup>](#table1)
- Opponent Network: 0.117[<sup>2</sup>](#table1)
- LAN Wins: 0.196[<sup>2</sup>](#table1)

The average of these factors is 0.223<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 853.3
- 400 + ( ( 0.223 - 0.000 ) / ( 0.786 - 0.000 ) ) * 1600 = 853.3


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
|           63 |      560 | 2024-05-21 | Verdant              | W   | 1.000      | 0.143        | 0.014 (0.002)    | 1.000 (0.143)    | 0 (0.000) |    22.78 | cryths, Rezst, shyyne, Tree, yz0              |
|           62 |      654 | 2024-05-20 | FearFerox            | W   | 1.000      | -            | -                | -                | 0 (0.000) |    10.82 | cryths, Rezst, shyyne, Tree, yz0              |
|           61 |     1055 | 2024-05-16 | Team Invictum        | L   | 1.000      | -            | -                | -                | -         |   -19.51 | cryths, Rezst, shyyne, Tree, yz0              |
|           60 |     1242 | 2024-05-14 | Halal5               | W   | 1.000      | -            | -                | -                | 0 (0.000) |    11.18 | cryths, Geckeos, Rezst, Tree, yz0             |
|           59 |     1244 | 2024-05-14 | Dynamo Eclot         | L   | 1.000      | -            | -                | -                | -         |    -7.69 | Philong, Rezst, shyyne, SLY, yz0              |
|           58 |     1261 | 2024-05-14 | VaselineWorms        | L   | 1.000      | -            | -                | -                | -         |   -18.89 | Philong, Rezst, shyyne, SLY, yz0              |
|           57 |     1307 | 2024-05-13 | LOG Esports          | W   | 1.000      | -            | -                | -                | 0 (0.000) |     5.24 | Philong, Rezst, shyyne, SLY, yz0              |
|           56 |     1649 | 2024-05-08 | GamerLegion Academy  | L   | 1.000      | -            | -                | -                | -         |   -13.08 | Askan, AyeZ, Rezst, Tree, yz0                 |
|           55 |     1673 | 2024-05-07 | ex-KRC Genk Esports  | W   | 1.000      | 0.372        | -                | 0.120 (0.045)    | -         |     9.22 | Philong, Rezst, shyyne, SLY, yz0              |
|           54 |     1710 | 2024-05-06 | The Last Resort      | L   | 1.000      | -            | -                | -                | -         |   -19.91 | cryths, Rezst, shyyne, Tree, yz0              |
|           53 |     3048 | 2024-04-13 | UNiTY esports        | L   | 0.889      | -            | -                | -                | -         |   -12.17 | K1-FiDa, Levi, M1key, NIO, Pechyn             |
|           52 |     3133 | 2024-04-11 | Viperio              | L   | 0.875      | -            | -                | -                | -         |   -16.94 | Rezst, shyyne, SLY, Tree, yz0                 |
|           51 |     3423 | 2024-04-06 | ROSOMAHA             | W   | 0.841      | -            | -                | -                | -         |     5.52 | Rezst, shyyne, SLY, Tree, yz0                 |
|           50 |     3506 | 2024-04-04 | Verdant              | W   | 0.829      | 0.333        | 0.014 (0.004)    | 1.000 (0.276)    | -         |    17.94 | Rezst, shyyne, SLY, Tree, yz0                 |
|           49 |     3697 | 2024-03-29 | EXO Clan             | L   | 0.791      | -            | -                | -                | -         |    -6.36 | Adam9130, bevve, dobbo, eraa, Thomas          |
|           48 |     4102 | 2024-03-21 | Permitta Esports     | L   | 0.736      | -            | -                | -                | -         |    -6.68 | bnox, maaryy, mASKED, morelz, Vegi            |
|           47 |     4158 | 2024-03-19 | Part Timers          | W   | 0.725      | -            | -                | -                | -         |     7.72 | eMy, ifan, Rhys, Yoshwa, Ziimzey              |
|           46 |     4289 | 2024-03-17 | Passion UA           | L   | 0.709      | -            | -                | -                | -         |    -7.39 | Rezst, shyyne, SLY, Tree, yz0                 |
|           45 |     4444 | 2024-03-14 | Permitta Esports     | W   | 0.689      | 0.333        | 0.029 (0.007)    | 1.000 (0.230)    | -         |    16.21 | Rezst, shyyne, SLY, Tree, yz0                 |
|           44 |     4716 | 2024-03-09 | Insilio              | L   | 0.657      | -            | -                | -                | -         |    -6.26 | Rezst, shyyne, SLY, Tree, yz0                 |
|           43 |     4740 | 2024-03-09 | ex-Preasy Esport     | L   | 0.655      | -            | -                | -                | -         |    -5.48 | Altekz, kristou, refrezh, roeJ, TMB           |
|           42 |     4754 | 2024-03-08 | MOUZ NXT             | L   | 0.650      | -            | -                | -                | -         |    -3.72 | Rezst, shyyne, SLY, Tree, yz0                 |
|           41 |     4908 | 2024-03-06 | Passion UA           | L   | 0.636      | -            | -                | -                | -         |    -6.72 | Rezst, shyyne, SLY, Tree, yz0                 |
|           40 |     5047 | 2024-03-04 | Team Secret          | W   | 0.623      | 0.371        | -                | 0.230 (0.053)    | -         |     5.57 | Rezst, shyyne, SLY, Tree, yz0                 |
|           39 |     5107 | 2024-03-03 | ENCE Academy         | L   | 0.616      | -            | -                | -                | -         |    -9.09 | Rezst, shyyne, SLY, Tree, yz0                 |
|           38 |     5232 | 2024-03-01 | HOTU                 | W   | 0.604      | 0.371        | 0.004 (0.001)    | 0.524 (0.117)    | -         |     9.77 | Rezst, shyyne, SLY, Tree, yz0                 |
|           37 |     5236 | 2024-03-01 | CYBERSHOKE Esports   | L   | 0.603      | -            | -                | -                | -         |   -11.72 | Rezst, shyyne, SLY, Tree, yz0                 |
|           36 |     5250 | 2024-02-29 | Verdant              | W   | 0.598      | 0.143        | 0.014 (0.001)    | 1.000 (0.085)    | -         |    12.06 | arTisT, Ducky, Girafffe, Vacancy, Zax1e       |
|           35 |     5288 | 2024-02-29 | Aurora Young Blud    | L   | 0.596      | -            | -                | -                | -         |   -10.86 | Rezst, shyyne, SLY, Tree, yz0                 |
|           34 |     5374 | 2024-02-27 | ENCE Academy         | L   | 0.583      | -            | -                | -                | -         |    -8.94 | Rezst, shyyne, SLY, Tree, yz0                 |
|           33 |     5459 | 2024-02-25 | EXO Clan             | L   | 0.570      | -            | -                | -                | -         |    -5.69 | Adam9130, bevve, dobbo, Extinct, smooya       |
|           32 |     5530 | 2024-02-24 | EXO Clan             | W   | 0.564      | 0.143        | 0.013 (0.001)    | 0.510 (0.041)    | 1 (0.564) |    12.32 | Rezst, shyyne, SLY, Tree, yz0                 |
|           31 |     5555 | 2024-02-24 | Raptors Esports Club | W   | 0.563      | 0.143        | 0.007 (0.001)    | -                | 1 (0.563) |     9.13 | Rezst, shyyne, SLY, Tree, yz0                 |
|           30 |     5597 | 2024-02-23 | Part Timers          | W   | 0.558      | -            | -                | -                | 1 (0.558) |     6.28 | CYPHER, ifan, JackB, JAUSTERE, Yoshwa         |
|           29 |     5752 | 2024-02-20 | Raptors Esports Club | W   | 0.538      | 0.143        | 0.007 (0.001)    | -                | -         |     9.20 | Kisynergy, Rezst, shyyne, Tree, yz0           |
|           28 |     6006 | 2024-02-16 | Passion UA           | L   | 0.508      | -            | -                | -                | -         |    -4.95 | Rezst, shyyne, SLY, Tree, yz0                 |
|           27 |     6030 | 2024-02-15 | Souls-Land           | W   | 0.505      | -            | -                | -                | -         |     2.48 | Deg1l, EthanChen, Harborboy, SundanceK1d, xrt |
|           26 |     6051 | 2024-02-15 | GamerLegion Academy  | W   | 0.503      | 0.371        | 0.018 (0.003)    | 0.691 (0.129)    | -         |     7.90 | Rezst, shyyne, SLY, Tree, yz0                 |
|           25 |     6068 | 2024-02-15 | Lilmix               | L   | 0.502      | -            | -                | -                | -         |    -6.93 | Rezst, shyyne, SLY, Tree, yz0                 |
|           24 |     6119 | 2024-02-14 | Dynamo Eclot         | L   | 0.496      | -            | -                | -                | -         |    -2.65 | Blytz, Dytor, forsyy, kreaz, nbqq             |
|           23 |     6153 | 2024-02-13 | ILIN                 | L   | 0.491      | -            | -                | -                | -         |   -12.72 | Rezst, shyyne, SLY, Tree, yz0                 |
|           22 |     6159 | 2024-02-13 | lajtbitexe           | W   | 0.490      | -            | -                | -                | -         |     3.38 | Rezst, shyyne, SLY, Tree, yz0                 |
|           21 |     6173 | 2024-02-13 | ROSOMAHA             | W   | 0.488      | -            | -                | -                | -         |     3.52 | D0nii, Maggent, rendY, skcH, Зippoch          |
|           20 |     6193 | 2024-02-12 | LODIS                | W   | 0.484      | -            | -                | -                | -         |     3.92 | Rezst, shyyne, SLY, Tree, yz0                 |
|           19 |     6208 | 2024-02-12 | RoundsGG             | W   | 0.484      | -            | -                | -                | -         |     3.60 | Kollo, LYNXi, m0n0xx, p12, Welho              |
|           18 |     6247 | 2024-02-11 | MOUZ NXT             | L   | 0.476      | -            | -                | -                | -         |    -2.68 | Rezst, shyyne, SLY, Tree, yz0                 |
|           17 |     6270 | 2024-02-10 | kONO.ECF             | L   | 0.470      | -            | -                | -                | -         |    -6.06 | Rezst, shyyne, SLY, Tree, yz0                 |
|           16 |     6280 | 2024-02-10 | Viperio              | L   | 0.468      | -            | -                | -                | -         |   -11.18 | Rezst, shyyne, SLY, Tree, yz0                 |
|           15 |     6544 | 2024-02-03 | Viperio              | L   | 0.423      | -            | -                | -                | -         |   -10.52 | mAnGo, MMS, pandi7o, ReegaN, zodi             |
|           14 |     6554 | 2024-02-03 | The Last Resort      | W   | 0.423      | -            | -                | -                | -         |     3.70 | AdamJC, Bigun, Fizzy, Flicky, ve1nzo          |
|           13 |     6701 | 2024-01-31 | Grannys Knockers     | W   | 0.404      | 0.371        | 0.006 (0.001)    | 0.355 (0.053)    | -         |     5.36 | dox, Rezst, shyyne, Tree, yz0                 |
|           12 |     6795 | 2024-01-29 | Sprout               | L   | 0.392      | -            | -                | -                | -         |    -9.42 | MAGILA, Rezst, shyyne, Tree, yz0              |
|           11 |     6962 | 2024-01-27 | 9INE                 | L   | 0.377      | -            | -                | -                | -         |    -9.81 | dox, Rezst, shyyne, Tree, yz0                 |
|           10 |     7117 | 2024-01-24 | GODSENT              | W   | 0.357      | -            | -                | -                | -         |     2.89 | dox, Rezst, shyyne, Tree, yz0                 |
|            9 |     7215 | 2024-01-22 | ex-Hot Headed Gaming | L   | 0.344      | -            | -                | -                | -         |    -9.49 | dox, Rezst, shyyne, Tree, yz0                 |
|            8 |     8014 | 2024-01-10 | Permitta Esports     | L   | 0.265      | -            | -                | -                | -         |    -3.07 | dox, Rezst, shyyne, Tree, yz0                 |
|            7 |     8079 | 2024-01-09 | KOI                  | L   | 0.258      | -            | -                | -                | -         |    -2.92 | dox, Rezst, shyyne, Tree, yz0                 |
|            6 |     8101 | 2024-01-09 | Nexus Gaming         | W   | 0.257      | -            | -                | -                | -         |     4.71 | BTN, ERSIN, ragga, s0und, XELLOW              |
|            5 |     8131 | 2024-01-09 | Sashi Esport         | W   | 0.257      | -            | -                | -                | -         |     1.26 | dox, Rezst, shyyne, Tree, yz0                 |
|            4 |     8955 | 2023-12-10 | Verdant              | W   | 0.058      | -            | -                | -                | 1 (0.058) |     1.35 | dox, Rezst, shyyne, Tree, yz0                 |
|            3 |     8972 | 2023-12-10 | DuckDuckGOOSE        | W   | 0.056      | -            | -                | -                | 1 (0.056) |     0.22 | BehinDx, Fizzy, Karrar, luccs, moz            |
|            2 |     8987 | 2023-12-10 | Verdant              | L   | 0.056      | -            | -                | -                | -         |    -0.45 | dox, Rezst, shyyne, Tree, yz0                 |
|            1 |     9031 | 2023-12-09 | Viperio              | W   | 0.050      | -            | -                | -                | 1 (0.050) |     0.29 | dox, Rezst, shyyne, Tree, yz0                 |

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
