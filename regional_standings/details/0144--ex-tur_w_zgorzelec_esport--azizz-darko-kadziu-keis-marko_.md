### Roster Details<br />
Team Name: ex-Turów Zgorzelec Esport<br />
Roster: azizz, darko, kadziu, keis, Markoś<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [144](../standings_global.md)<br />
Regional Rank: [101]( ../standings_europe.md)<br />
Final Rank Value:  792.4<br />
<br />
Final Rank Value (792.4) = Starting Rank Value (799.7) + Head To Head Adjustments (-7.3)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.307[<sup>1</sup>](#table2)
- Bounty Collected: 0.312[<sup>2</sup>](#table1)
- Opponent Network: 0.168[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.197<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 799.7
- 400 + ( ( 0.197 - 0.000 ) / ( 0.787 - 0.000 ) ) * 1600 = 799.7


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent               | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                        |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           73 |      603 | 2024-05-21 | Rustec                 | L   | 1.000      | -            | -                | -                | -         |   -13.17 | azizz, darko, kadziu, keis, Markoś            |
|           72 |     1272 | 2024-05-14 | Lausanne-Sport Esports | W   | 1.000      | -            | -                | -                | 0 (0.000) |    14.63 | berzerk, msn2k, SBT, SeBreeZe, xReal          |
|           71 |     1323 | 2024-05-13 | MOUZ NXT               | L   | 1.000      | -            | -                | -                | -         |    -5.86 | azizz, darko, kadziu, keis, Markoś            |
|           70 |     1405 | 2024-05-12 | Permitta Esports       | L   | 1.000      | -            | -                | -                | -         |   -11.91 | azizz, darko, kadziu, keis, Markoś            |
|           69 |     1430 | 2024-05-11 | ENTERPRISE esports     | W   | 1.000      | 0.143        | -                | 0.898 (0.128)    | 0 (0.000) |    21.59 | bajmi, Demho, Ex1st, fr3nd, Sobol             |
|           68 |     1447 | 2024-05-11 | ThunderFlash           | W   | 1.000      | 0.143        | 0.012 (0.002)    | -                | 0 (0.000) |    19.81 | AdrieN, hfah, Klameczka, Melavi, sk1tt        |
|           67 |     1634 | 2024-05-08 | ARROW                  | W   | 1.000      | 0.372        | -                | 0.344 (0.128)    | 0 (0.000) |    14.37 | Kre1N, MRC9, Orbit, Tionix, Twiksar           |
|           66 |     1648 | 2024-05-08 | Nemiga Gaming          | L   | 1.000      | -            | -                | -                | -         |    -2.56 | 1eeR, boX, khaN, riskyb0b, Xant3r             |
|           65 |     1674 | 2024-05-08 | UNiTY esports          | L   | 1.000      | -            | -                | -                | -         |   -10.40 | azizz, darko, kadziu, Markoś, ToM223          |
|           64 |     1698 | 2024-05-07 | Soda Gaming            | L   | 1.000      | -            | -                | -                | -         |   -22.20 | azizz, darko, kadziu, keis, Markoś            |
|           63 |     1708 | 2024-05-07 | Nexus Gaming           | W   | 1.000      | 0.372        | -                | 0.857 (0.319)    | 0 (0.000) |    17.42 | BTN, ERSIN, fnl, ragga, XELLOW                |
|           62 |     1878 | 2024-05-04 | Astralis Talent        | W   | 1.000      | 0.333        | 0.012 (0.004)    | 0.452 (0.151)    | 0 (0.000) |    19.63 | ANSG1, kiR, kroK, sSen, suma                  |
|           61 |     2121 | 2024-04-29 | UNiTY esports          | L   | 0.994      | -            | -                | -                | -         |    -9.91 | azizz, darko, kadziu, Markoś, ToM223          |
|           60 |     2354 | 2024-04-25 | JANO Esports           | L   | 0.970      | -            | -                | -                | -         |   -16.00 | allu, Cliqq, doto, Jerppa, Sm1llee            |
|           59 |     2363 | 2024-04-25 | GenOne                 | W   | 0.969      | 0.372        | -                | 0.442 (0.160)    | 0 (0.000) |    10.51 | azizz, darko, kadziu, keis, Markoś            |
|           58 |     2373 | 2024-04-25 | Verdant                | L   | 0.968      | -            | -                | -                | -         |   -10.59 | arTisT, Diviiii, Ducky, Girafffe, Vacancy     |
|           57 |     2409 | 2024-04-24 | los kogutos            | W   | 0.964      | 0.372        | 0.007 (0.002)    | 0.327 (0.117)    | 0 (0.000) |    17.82 | chudy2k, darchevile, Enzo, Nami, yvro         |
|           56 |     2419 | 2024-04-24 | ThunderFlash           | W   | 0.963      | 0.372        | 0.012 (0.004)    | 0.423 (0.152)    | 0 (0.000) |    19.16 | azizz, darko, kadziu, keis, Markoś            |
|           55 |     3028 | 2024-04-15 | Team Secret            | L   | 0.902      | -            | -                | -                | -         |   -17.38 | anarkez, Kind0, Maze, NOPEEj, Tauson          |
|           54 |     3205 | 2024-04-11 | Team Sampi             | L   | 0.874      | -            | -                | -                | -         |    -5.30 | azizz, darko, kadziu, Markoś, Sobol           |
|           53 |     3436 | 2024-04-07 | Viperio                | L   | 0.849      | -            | -                | -                | -         |   -15.54 | mAnGo, pandi7o, ReegaN, Skrimo, zodi          |
|           52 |     3544 | 2024-04-05 | SAW                    | L   | 0.835      | -            | -                | -                | -         |    -0.89 | azizz, darko, EXUS, kadziu, Markoś            |
|           51 |     3607 | 2024-04-04 | Dynamo Eclot           | L   | 0.828      | -            | -                | -                | -         |    -5.22 | Blytz, Dytor, forsyy, kreaz, nbqq             |
|           50 |     3647 | 2024-04-03 | Illuminar Gaming       | W   | 0.823      | -            | -                | -                | 0 (0.000) |    14.48 | darko, EXUS, kadziu, Markoś, Sobol            |
|           49 |     3669 | 2024-04-03 | Lilmix                 | L   | 0.821      | -            | -                | -                | -         |   -14.23 | Brillo, dex, poiii, quix, zyyx                |
|           48 |     3728 | 2024-04-01 | ROSOMAHA               | W   | 0.808      | -            | -                | -                | -         |     6.55 | darko, EXUS, kadziu, Markoś, Sobol            |
|           47 |     3778 | 2024-03-30 | Sashi Esport           | L   | 0.796      | -            | -                | -                | -         |    -4.26 | darko, EXUS, kadziu, Markoś, Sobol            |
|           46 |     4025 | 2024-03-25 | Lilmix                 | W   | 0.762      | 0.333        | 0.006 (0.002)    | 0.593 (0.151)    | -         |    11.02 | Brillo, dex, poiii, quix, zyyx                |
|           45 |     4121 | 2024-03-22 | Mikstura1234           | W   | 0.745      | -            | -                | -                | -         |     7.60 | AxEcHo, darko, kadziu, Markoś, xKacpersky     |
|           44 |     4186 | 2024-03-21 | LODIS                  | L   | 0.738      | -            | -                | -                | -         |   -16.49 | aimy, asran, fugor, Mride, pawkoem            |
|           43 |     4205 | 2024-03-21 | UNiTY esports          | W   | 0.735      | 0.333        | 0.021 (0.005)    | 0.766 (0.188)    | -         |    13.56 | darko, EXUS, kadziu, Markoś, Sobol            |
|           42 |     4236 | 2024-03-20 | ENTERPRISE esports     | L   | 0.730      | -            | -                | -                | -         |    -6.67 | bajmi, Demho, Ex1st, fr3nd, TOAO              |
|           41 |     4241 | 2024-03-20 | Dynamo Eclot           | L   | 0.730      | -            | -                | -                | -         |    -4.04 | AxEcHo, darko, kadziu, Markoś, xKacpersky     |
|           40 |     4259 | 2024-03-19 | ThunderFlash           | W   | 0.725      | -            | -                | -                | -         |    12.79 | AxEcHo, darko, kadziu, Markoś, xKacpersky     |
|           39 |     4276 | 2024-03-19 | WOPA Esport            | L   | 0.724      | -            | -                | -                | -         |   -10.20 | AxEcHo, darko, kadziu, Markoś, xKacpersky     |
|           38 |     4295 | 2024-03-18 | Illuminar Gaming       | L   | 0.718      | -            | -                | -                | -         |   -12.09 | AxEcHo, darko, kadziu, Markoś, xKacpersky     |
|           37 |     4310 | 2024-03-18 | ARROW                  | W   | 0.717      | -            | -                | -                | -         |     9.36 | AxEcHo, darko, kadziu, Markoś, xKacpersky     |
|           36 |     4349 | 2024-03-17 | Viperio                | W   | 0.711      | -            | -                | -                | -         |     8.45 | AxEcHo, darko, kadziu, Markoś, xKacpersky     |
|           35 |     4441 | 2024-03-16 | FAVBET Team            | L   | 0.703      | -            | -                | -                | -         |    -7.59 | bondik, guthriee, j3kie, Smash, t3ns1on       |
|           34 |     4474 | 2024-03-15 | TopTab Club            | W   | 0.698      | -            | -                | -                | -         |     4.70 | ADntZ, keembo, maQuein, rezn9, SKYLLLER       |
|           33 |     4606 | 2024-03-13 | GameAgents             | W   | 0.684      | -            | -                | -                | -         |     4.58 | el_strongo, mikult, MQ666MQ, NerouK, wtfmen   |
|           32 |     4726 | 2024-03-11 | fragmatic              | L   | 0.671      | -            | -                | -                | -         |   -16.67 | bodik, Litovka, mattloo, shiny, smouf         |
|           31 |     5053 | 2024-03-06 | Natus Vincere Junior   | L   | 0.635      | -            | -                | -                | -         |    -9.29 | alkarenn, dem0n, Krabeni, Magic, makazze      |
|           30 |     5172 | 2024-03-04 | ENTERPRISE esports     | L   | 0.625      | -            | -                | -                | -         |    -5.53 | AxEcHo, darko, kadziu, Markoś, xKacpersky     |
|           29 |     5203 | 2024-03-04 | MOUZ NXT               | L   | 0.622      | -            | -                | -                | -         |    -2.92 | Burmylov, Chr1zN, Neityu, PR, sirah           |
|           28 |     5298 | 2024-03-02 | AURA                   | L   | 0.611      | -            | -                | -                | -         |   -13.05 | AxEcHo, darko, kadziu, Markoś, xKacpersky     |
|           27 |     5542 | 2024-02-27 | Astralis Talent        | W   | 0.582      | 0.303        | 0.012 (0.002)    | -                | -         |    12.12 | AxEcHo, darko, kadziu, Markoś, Sobol          |
|           26 |     5559 | 2024-02-26 | DMS                    | L   | 0.578      | -            | -                | -                | -         |   -11.03 | AW, H1te, kAlash, sFade8, sm3t                |
|           25 |     5584 | 2024-02-26 | Dynamo Eclot           | L   | 0.575      | -            | -                | -                | -         |    -3.19 | AxEcHo, darko, kadziu, Markoś, xKacpersky     |
|           24 |     5621 | 2024-02-25 | Sashi Esport           | W   | 0.569      | 0.333        | 0.154 (0.029)    | 1.000 (0.190)    | -         |    14.90 | AxEcHo, darko, kadziu, Markoś, xKacpersky     |
|           23 |     5676 | 2024-02-24 | agenty                 | W   | 0.564      | -            | -                | -                | -         |     1.70 | AxEcHo, darko, kadziu, Markoś, xKacpersky     |
|           22 |     5779 | 2024-02-23 | Johnny Speeds          | W   | 0.556      | 0.303        | 0.056 (0.009)    | -                | -         |    13.94 | AxEcHo, darko, kadziu, Markoś, Sobol          |
|           21 |     5833 | 2024-02-22 | Permitta Esports       | L   | 0.548      | -            | -                | -                | -         |    -4.25 | bnox, maaryy, mASKED, morelz, Vegi            |
|           20 |     6128 | 2024-02-17 | Entropiq               | W   | 0.516      | -            | -                | -                | -         |     5.60 | c0llins, Marix, mwlky, Oxygen, tiziaN         |
|           19 |     6354 | 2024-02-13 | Natus Vincere Junior   | W   | 0.489      | 0.333        | 0.010 (0.002)    | -                | -         |     8.22 | alkarenn, dem0n, Krabeni, Magic, makazze      |
|           18 |     7044 | 2024-01-29 | ex-Preasy Esport       | L   | 0.391      | -            | -                | -                | -         |    -3.84 | byali, darko, kadziu, Markoś, xKacpersky      |
|           17 |     7782 | 2024-01-17 | AMKAL ESPORTS          | L   | 0.311      | -            | -                | -                | -         |    -0.86 | byali, darko, kadziu, Markoś, xKacpersky      |
|           16 |     7817 | 2024-01-17 | ILIN                   | W   | 0.311      | -            | -                | -                | -         |     2.10 | byali, darko, kadziu, Markoś, xKacpersky      |
|           15 |     7901 | 2024-01-16 | 00 Nation              | L   | 0.304      | -            | -                | -                | -         |    -8.00 | byali, darko, discoStar, kadziu, Markoś       |
|           14 |     7929 | 2024-01-16 | Virtuoso Squad         | W   | 0.304      | -            | -                | -                | -         |     1.51 | Maha, N1ghtMan, rifle, sinkieee, V0R4yn       |
|           13 |     8089 | 2024-01-12 | Betera Esports         | L   | 0.278      | -            | -                | -                | -         |    -4.01 | alex666, lollipop21k, MaSvAl, nifee, sad      |
|           12 |     8115 | 2024-01-12 | GODSENT                | W   | 0.278      | -            | -                | -                | -         |     2.83 | byali, darko, discoStar, kadziu, Markoś       |
|           11 |     8259 | 2024-01-10 | Betera Esports         | L   | 0.265      | -            | -                | -                | -         |    -3.87 | alex666, lollipop21k, MaSvAl, nifee, sad      |
|           10 |     8343 | 2024-01-09 | Fnatic                 | L   | 0.257      | -            | -                | -                | -         |    -1.12 | darko, discoStar, gRuChA, kadziu, Markoś      |
|            9 |     8357 | 2024-01-09 | Verdant                | W   | 0.257      | -            | -                | -                | -         |     0.81 | cryths, Ducky, Dutchy, Girafffe, Wolfie       |
|            8 |     8395 | 2024-01-09 | Natus Vincere Junior   | L   | 0.255      | -            | -                | -                | -         |    -4.10 | dem0n, fnl, Krabeni, Magic, makazze           |
|            7 |     8481 | 2024-01-05 | Zero Tenacity          | L   | 0.228      | -            | -                | -                | -         |    -1.17 | darko, discoStar, gRuChA, kadziu, Markoś      |
|            6 |     8643 | 2023-12-20 | Sashi Esport           | L   | 0.122      | -            | -                | -                | -         |    -3.08 | Fessor, n1Xen, nut nut, PR1mE, Speedy         |
|            5 |     8748 | 2023-12-17 | Sashi Esport           | L   | 0.102      | -            | -                | -                | -         |    -0.56 | b1elany, darko, gRuChA, kadziu, Markoś        |
|            4 |     9019 | 2023-12-15 | detoks                 | W   | 0.089      | -            | -                | -                | -         |     0.45 | darchevile, hotd0g, KukuBambo, maaryy, tomiko |
|            3 |     9198 | 2023-12-11 | Team Spirit Academy    | L   | 0.063      | -            | -                | -                | -         |    -1.18 | alpha, baz, keegaN, Magnojez, notineki        |
|            2 |     9443 | 2023-12-07 | UNiTY esports          | W   | 0.037      | -            | -                | -                | -         |     0.77 | Levi, luko, M1key, NIO, Pechyn                |
|            1 |     9727 | 2023-12-02 | ENTERPRISE esports     | L   | 0.004      | -            | -                | -                | -         |    -0.04 | bajmi, Demho, Ex1st, fr3nd, Klameczka         |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($1,658.42)
- Divide that value by the 5th highest value among all rosters ($300,806.11)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-04-21 |      0.943 | $492.92        | $464.99         |
| 2024-04-06 |      0.841 | $500.00        | $420.56         |
| 2024-03-23 |      0.751 | $600.00        | $450.75         |
| 2024-02-28 |      0.588 | $500.00        | $294.17         |
| 2023-12-02 |      0.004 | $6,290.86      | $27.96          |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
