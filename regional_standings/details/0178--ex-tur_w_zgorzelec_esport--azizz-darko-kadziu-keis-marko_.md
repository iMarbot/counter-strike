### Roster Details<br />
Team Name: ex-Turów Zgorzelec Esport<br />
Roster: azizz, darko, kadziu, keis, Markoś<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [178](../standings_global.md)<br />
Regional Rank: [122]( ../standings_europe.md)<br />
Final Rank Value:  749.0<br />
<br />
Final Rank Value (749.0) = Starting Rank Value (777.5) + Head To Head Adjustments (-28.6)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.307[<sup>1</sup>](#table2)
- Bounty Collected: 0.311[<sup>2</sup>](#table1)
- Opponent Network: 0.124[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.185<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 777.5
- 400 + ( ( 0.185 - 0.000 ) / ( 0.786 - 0.000 ) ) * 1600 = 777.5


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
|           62 |      592 | 2024-05-21 | Rustec               | L   | 1.000      | -            | -                | -                | -         |   -12.10 | azizz, darko, kadziu, keis, Markoś            |
|           61 |     1392 | 2024-05-12 | Permitta Esports     | L   | 1.000      | -            | -                | -                | -         |   -11.40 | azizz, darko, kadziu, keis, Markoś            |
|           60 |     1417 | 2024-05-11 | ENTERPRISE esports   | W   | 1.000      | 0.143        | 0.010 (0.001)    | 0.809 (0.116)    | 0 (0.000) |    22.34 | bajmi, Demho, Ex1st, fr3nd, Sobol             |
|           59 |     1434 | 2024-05-11 | ThunderFlash         | W   | 1.000      | 0.143        | 0.012 (0.002)    | 0.423 (0.060)    | 0 (0.000) |    21.67 | AdrieN, hfah, Klameczka, Melavi, sk1tt        |
|           58 |     1656 | 2024-05-08 | UNiTY esports        | L   | 1.000      | -            | -                | -                | -         |    -9.10 | azizz, darko, kadziu, Markoś, ToM223          |
|           57 |     1855 | 2024-05-04 | Astralis Talent      | W   | 1.000      | 0.333        | 0.012 (0.004)    | 0.452 (0.151)    | 0 (0.000) |    20.92 | ANSG1, kiR, kroK, sSen, suma                  |
|           56 |     2086 | 2024-04-29 | UNiTY esports        | L   | 0.994      | -            | -                | -                | -         |    -8.27 | azizz, darko, kadziu, Markoś, ToM223          |
|           55 |     2332 | 2024-04-25 | Verdant              | L   | 0.968      | -            | -                | -                | -         |    -9.48 | arTisT, Diviiii, Ducky, Girafffe, Vacancy     |
|           54 |     2963 | 2024-04-15 | Team Secret          | L   | 0.902      | -            | -                | -                | -         |   -17.25 | anarkez, Kind0, Maze, NOPEEj, Tauson          |
|           53 |     3134 | 2024-04-11 | Team Sampi           | L   | 0.874      | -            | -                | -                | -         |    -5.27 | azizz, darko, kadziu, Markoś, Sobol           |
|           52 |     3353 | 2024-04-07 | Viperio              | L   | 0.849      | -            | -                | -                | -         |   -15.43 | mAnGo, pandi7o, ReegaN, Skrimo, zodi          |
|           51 |     3459 | 2024-04-05 | SAW                  | L   | 0.835      | -            | -                | -                | -         |    -0.86 | azizz, darko, EXUS, kadziu, Markoś            |
|           50 |     3520 | 2024-04-04 | Dynamo Eclot         | L   | 0.828      | -            | -                | -                | -         |    -5.04 | Blytz, Dytor, forsyy, kreaz, nbqq             |
|           49 |     3560 | 2024-04-03 | Illuminar Gaming     | W   | 0.823      | 0.333        | -                | 0.403 (0.111)    | 0 (0.000) |    14.68 | darko, EXUS, kadziu, Markoś, Sobol            |
|           48 |     3580 | 2024-04-03 | Lilmix               | L   | 0.821      | -            | -                | -                | -         |   -13.57 | Brillo, dex, poiii, quix, zyyx                |
|           47 |     3635 | 2024-04-01 | ROSOMAHA             | W   | 0.808      | -            | -                | -                | 0 (0.000) |     6.46 | darko, EXUS, kadziu, Markoś, Sobol            |
|           46 |     3685 | 2024-03-30 | Sashi Esport         | L   | 0.796      | -            | -                | -                | -         |    -4.27 | darko, EXUS, kadziu, Markoś, Sobol            |
|           45 |     3929 | 2024-03-25 | Lilmix               | W   | 0.762      | 0.333        | 0.006 (0.002)    | 0.581 (0.148)    | 0 (0.000) |    11.70 | Brillo, dex, poiii, quix, zyyx                |
|           44 |     4023 | 2024-03-22 | Mikstura1234         | W   | 0.745      | -            | -                | -                | 0 (0.000) |     7.80 | AxEcHo, darko, kadziu, Markoś, xKacpersky     |
|           43 |     4087 | 2024-03-21 | LODIS                | L   | 0.738      | -            | -                | -                | -         |   -16.70 | aimy, asran, fugor, Mride, pawkoem            |
|           42 |     4105 | 2024-03-21 | UNiTY esports        | W   | 0.735      | 0.333        | 0.021 (0.005)    | 0.766 (0.188)    | 0 (0.000) |    13.82 | darko, EXUS, kadziu, Markoś, Sobol            |
|           41 |     4135 | 2024-03-20 | ENTERPRISE esports   | L   | 0.730      | -            | -                | -                | -         |    -7.00 | bajmi, Demho, Ex1st, fr3nd, TOAO              |
|           40 |     4139 | 2024-03-20 | Dynamo Eclot         | L   | 0.730      | -            | -                | -                | -         |    -3.84 | AxEcHo, darko, kadziu, Markoś, xKacpersky     |
|           39 |     4157 | 2024-03-19 | ThunderFlash         | W   | 0.725      | 0.143        | 0.012 (0.001)    | -                | 0 (0.000) |    12.93 | AxEcHo, darko, kadziu, Markoś, xKacpersky     |
|           38 |     4173 | 2024-03-19 | WOPA Esport          | L   | 0.724      | -            | -                | -                | -         |   -10.01 | AxEcHo, darko, kadziu, Markoś, xKacpersky     |
|           37 |     4191 | 2024-03-18 | Illuminar Gaming     | L   | 0.718      | -            | -                | -                | -         |   -11.81 | AxEcHo, darko, kadziu, Markoś, xKacpersky     |
|           36 |     4205 | 2024-03-18 | ARROW                | W   | 0.717      | 0.333        | -                | 0.344 (0.082)    | 0 (0.000) |     9.55 | AxEcHo, darko, kadziu, Markoś, xKacpersky     |
|           35 |     4244 | 2024-03-17 | Viperio              | W   | 0.711      | -            | -                | -                | -         |     8.24 | AxEcHo, darko, kadziu, Markoś, xKacpersky     |
|           34 |     4366 | 2024-03-15 | TopTab Club          | W   | 0.698      | -            | -                | -                | -         |     5.03 | ADntZ, keembo, maQuein, rezn9, SKYLLLER       |
|           33 |     4491 | 2024-03-13 | GameAgents           | W   | 0.684      | -            | -                | -                | -         |     4.92 | el_strongo, mikult, MQ666MQ, NerouK, wtfmen   |
|           32 |     4604 | 2024-03-11 | fragmatic            | L   | 0.671      | -            | -                | -                | -         |   -16.36 | bodik, Litovka, mattloo, shiny, smouf         |
|           31 |     4914 | 2024-03-06 | Natus Vincere Junior | L   | 0.635      | -            | -                | -                | -         |    -8.86 | alkarenn, dem0n, Krabeni, Magic, makazze      |
|           30 |     5026 | 2024-03-04 | ENTERPRISE esports   | L   | 0.625      | -            | -                | -                | -         |    -5.65 | AxEcHo, darko, kadziu, Markoś, xKacpersky     |
|           29 |     5057 | 2024-03-04 | MOUZ NXT             | L   | 0.622      | -            | -                | -                | -         |    -2.89 | Burmylov, Chr1zN, Neityu, PR, sirah           |
|           28 |     5150 | 2024-03-02 | AURA                 | L   | 0.611      | -            | -                | -                | -         |   -12.76 | AxEcHo, darko, kadziu, Markoś, xKacpersky     |
|           27 |     5386 | 2024-02-27 | Astralis Talent      | W   | 0.582      | 0.303        | 0.012 (0.002)    | 0.452 (0.080)    | -         |    12.48 | AxEcHo, darko, kadziu, Markoś, Sobol          |
|           26 |     5402 | 2024-02-26 | DMS                  | L   | 0.578      | -            | -                | -                | -         |   -10.88 | AW, H1te, kAlash, sFade8, sm3t                |
|           25 |     5426 | 2024-02-26 | Dynamo Eclot         | L   | 0.575      | -            | -                | -                | -         |    -2.99 | AxEcHo, darko, kadziu, Markoś, xKacpersky     |
|           24 |     5463 | 2024-02-25 | Sashi Esport         | W   | 0.569      | 0.333        | 0.172 (0.033)    | 1.000 (0.190)    | -         |    15.19 | AxEcHo, darko, kadziu, Markoś, xKacpersky     |
|           23 |     5516 | 2024-02-24 | agenty               | W   | 0.564      | -            | -                | -                | -         |     1.87 | AxEcHo, darko, kadziu, Markoś, xKacpersky     |
|           22 |     5619 | 2024-02-23 | Johnny Speeds        | W   | 0.556      | 0.303        | 0.056 (0.009)    | 0.683 (0.115)    | -         |    14.19 | AxEcHo, darko, kadziu, Markoś, Sobol          |
|           21 |     5672 | 2024-02-22 | Permitta Esports     | L   | 0.548      | -            | -                | -                | -         |    -4.08 | bnox, maaryy, mASKED, morelz, Vegi            |
|           20 |     5955 | 2024-02-17 | Entropiq             | W   | 0.516      | -            | -                | -                | -         |     5.97 | c0llins, Marix, mwlky, Oxygen, tiziaN         |
|           19 |     6169 | 2024-02-13 | Natus Vincere Junior | W   | 0.489      | 0.333        | 0.010 (0.002)    | -                | -         |     8.64 | alkarenn, dem0n, Krabeni, Magic, makazze      |
|           18 |     6828 | 2024-01-29 | ex-Preasy Esport     | L   | 0.391      | -            | -                | -                | -         |    -3.60 | byali, darko, kadziu, Markoś, xKacpersky      |
|           17 |     7533 | 2024-01-17 | AMKAL ESPORTS        | L   | 0.311      | -            | -                | -                | -         |    -0.78 | byali, darko, kadziu, Markoś, xKacpersky      |
|           16 |     7568 | 2024-01-17 | ILIN                 | W   | 0.311      | -            | -                | -                | -         |     2.28 | byali, darko, kadziu, Markoś, xKacpersky      |
|           15 |     7652 | 2024-01-16 | 00 Nation            | L   | 0.304      | -            | -                | -                | -         |    -7.85 | byali, darko, discoStar, kadziu, Markoś       |
|           14 |     7680 | 2024-01-16 | Virtuoso Squad       | W   | 0.304      | -            | -                | -                | -         |     1.65 | Maha, N1ghtMan, rifle, sinkieee, V0R4yn       |
|           13 |     7836 | 2024-01-12 | Betera Esports       | L   | 0.278      | -            | -                | -                | -         |    -3.77 | alex666, lollipop21k, MaSvAl, nifee, sad      |
|           12 |     7862 | 2024-01-12 | GODSENT              | W   | 0.278      | -            | -                | -                | -         |     3.04 | byali, darko, discoStar, kadziu, Markoś       |
|           11 |     8005 | 2024-01-10 | Betera Esports       | L   | 0.265      | -            | -                | -                | -         |    -3.63 | alex666, lollipop21k, MaSvAl, nifee, sad      |
|           10 |     8089 | 2024-01-09 | Fnatic               | L   | 0.257      | -            | -                | -                | -         |    -1.01 | darko, discoStar, gRuChA, kadziu, Markoś      |
|            9 |     8103 | 2024-01-09 | Verdant              | W   | 0.257      | -            | -                | -                | -         |     0.90 | cryths, Ducky, Dutchy, Girafffe, Wolfie       |
|            8 |     8141 | 2024-01-09 | Natus Vincere Junior | L   | 0.255      | -            | -                | -                | -         |    -3.86 | dem0n, fnl, Krabeni, Magic, makazze           |
|            7 |     8226 | 2024-01-05 | Zero Tenacity        | L   | 0.228      | -            | -                | -                | -         |    -1.07 | darko, discoStar, gRuChA, kadziu, Markoś      |
|            6 |     8386 | 2023-12-20 | Sashi Esport         | L   | 0.122      | -            | -                | -                | -         |    -3.01 | Fessor, n1Xen, nut nut, PR1mE, Speedy         |
|            5 |     8488 | 2023-12-17 | Sashi Esport         | L   | 0.102      | -            | -                | -                | -         |    -0.51 | b1elany, darko, gRuChA, kadziu, Markoś        |
|            4 |     8757 | 2023-12-15 | detoks               | W   | 0.089      | -            | -                | -                | -         |     0.49 | darchevile, hotd0g, KukuBambo, maaryy, tomiko |
|            3 |     8932 | 2023-12-11 | Team Spirit Academy  | L   | 0.063      | -            | -                | -                | -         |    -1.12 | alpha, baz, keegaN, Magnojez, notineki        |
|            2 |     9170 | 2023-12-07 | UNiTY esports        | W   | 0.037      | -            | -                | -                | -         |     0.80 | Levi, luko, M1key, NIO, Pechyn                |
|            1 |     9445 | 2023-12-02 | ENTERPRISE esports   | L   | 0.004      | -            | -                | -                | -         |    -0.04 | bajmi, Demho, Ex1st, fr3nd, Klameczka         |

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
