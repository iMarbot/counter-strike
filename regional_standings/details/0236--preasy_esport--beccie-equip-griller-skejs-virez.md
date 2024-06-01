### Roster Details<br />
Team Name: Preasy Esport<br />
Roster: Beccie, Equip, Griller, Skejs, VireZ<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [236](../standings_global.md)<br />
Regional Rank: [156]( ../standings_europe.md)<br />
Final Rank Value:  699.0<br />
<br />
Final Rank Value (699.0) = Starting Rank Value (892.0) + Head To Head Adjustments (-193.0)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.325[<sup>1</sup>](#table2)
- Bounty Collected: 0.335[<sup>2</sup>](#table1)
- Opponent Network: 0.180[<sup>2</sup>](#table1)
- LAN Wins: 0.128[<sup>2</sup>](#table1)

The average of these factors is 0.242<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 892.0
- 400 + ( ( 0.242 - 0.000 ) / ( 0.786 - 0.000 ) ) * 1600 = 892.0


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent            | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                      |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           90 |       66 | 2024-05-29 | Copenhagen Wolves   | L   | 1.000      | -            | -                | -                | -         |   -14.47 | Beccie, Equip, Griller, Skejs, VireZ        |
|           89 |       79 | 2024-05-29 | VOLT                | W   | 1.000      | -            | -                | -                | 0 (0.000) |     4.86 | Beccie, Equip, Griller, Skejs, VireZ        |
|           88 |      124 | 2024-05-28 | Young Ninjas        | L   | 1.000      | -            | -                | -                | -         |    -8.17 | Beccie, Equip, Griller, Skejs, VireZ        |
|           87 |      136 | 2024-05-28 | Permitta Esports    | L   | 1.000      | -            | -                | -                | -         |   -12.46 | Beccie, Equip, Griller, Skejs, VireZ        |
|           86 |      139 | 2024-05-28 | Astralis Talent     | L   | 1.000      | -            | -                | -                | -         |   -15.20 | Beccie, Equip, Griller, Skejs, VireZ        |
|           85 |      172 | 2024-05-27 | Sashi Academy       | W   | 1.000      | -            | -                | -                | 0 (0.000) |     8.20 | Beccie, Equip, Griller, Skejs, VireZ        |
|           84 |      176 | 2024-05-27 | Sashi Esport        | W   | 1.000      | 0.143        | 0.172 (0.025)    | 1.000 (0.143)    | 0 (0.000) |    29.66 | Beccie, Equip, Griller, Skejs, VireZ        |
|           83 |      191 | 2024-05-27 | Illuminar Gaming    | L   | 1.000      | -            | -                | -                | -         |   -14.33 | Beccie, Equip, Griller, Skejs, VireZ        |
|           82 |      228 | 2024-05-26 | Johnny Speeds       | L   | 1.000      | -            | -                | -                | -         |    -4.64 | Beccie, Equip, Griller, Skejs, VireZ        |
|           81 |      266 | 2024-05-25 | Reason Gaming       | W   | 1.000      | 0.333        | 0.004 (0.001)    | -                | 0 (0.000) |    16.97 | Beccie, Equip, Griller, Skejs, VireZ        |
|           80 |      398 | 2024-05-23 | Monte Gen           | L   | 1.000      | -            | -                | -                | -         |   -11.04 | Beccie, Equip, Griller, Skejs, VireZ        |
|           79 |      412 | 2024-05-23 | Nexus Gaming        | L   | 1.000      | -            | -                | -                | -         |   -10.66 | Beccie, Equip, Griller, Skejs, VireZ        |
|           78 |      503 | 2024-05-22 | Denial              | L   | 1.000      | -            | -                | -                | -         |   -20.73 | Beccie, Equip, Griller, Skejs, VireZ        |
|           77 |      515 | 2024-05-22 | Dynamo Eclot        | W   | 1.000      | 0.371        | 0.097 (0.036)    | 0.936 (0.347)    | 0 (0.000) |    22.76 | Beccie, Equip, Griller, Skejs, VireZ        |
|           76 |      666 | 2024-05-20 | XI Esport           | L   | 1.000      | -            | -                | -                | -         |   -19.32 | Beccie, Equip, Griller, Skejs, VireZ        |
|           75 |      683 | 2024-05-20 | Astralis Talent     | L   | 1.000      | -            | -                | -                | -         |   -15.69 | Beccie, Equip, Griller, Skejs, VireZ        |
|           74 |      710 | 2024-05-20 | Denial              | L   | 1.000      | -            | -                | -                | -         |   -23.12 | Beccie, Equip, Griller, Skejs, VireZ        |
|           73 |      753 | 2024-05-19 | Lemoncats           | L   | 1.000      | -            | -                | -                | -         |   -26.40 | AcilioN, Beccie, Griller, Skejs, VireZ      |
|           72 |     1210 | 2024-05-15 | kONO.ECF            | L   | 1.000      | -            | -                | -                | -         |   -11.30 | Beccie, Equip, Griller, Skejs, VireZ        |
|           71 |     1397 | 2024-05-12 | Johnny Speeds       | W   | 1.000      | 0.333        | 0.056 (0.019)    | 0.683 (0.228)    | 0 (0.000) |    24.18 | Beccie, Equip, Griller, Skejs, VireZ        |
|           70 |     1482 | 2024-05-11 | Passion UA          | L   | 1.000      | -            | -                | -                | -         |    -9.87 | Beccie, Equip, Griller, Skejs, VireZ        |
|           69 |     1500 | 2024-05-10 | Illuminar Gaming    | W   | 1.000      | -            | -                | -                | 0 (0.000) |    15.87 | Beccie, Equip, Griller, Skejs, VireZ        |
|           68 |     1559 | 2024-05-09 | ENCE Academy        | W   | 1.000      | 0.143        | 0.012 (0.002)    | -                | 0 (0.000) |    14.04 | AcilioN, Beccie, Griller, Skejs, VireZ      |
|           67 |     1580 | 2024-05-09 | kONO.ECF            | W   | 1.000      | 0.333        | 0.013 (0.004)    | 0.778 (0.259)    | -         |    21.98 | AcilioN, Beccie, Griller, Skejs, VireZ      |
|           66 |     1640 | 2024-05-08 | Illuminar Gaming    | L   | 1.000      | -            | -                | -                | -         |   -13.11 | Beccie, Equip, Griller, Skejs, VireZ        |
|           65 |     1687 | 2024-05-07 | UNiTY esports       | L   | 1.000      | -            | -                | -                | -         |   -11.16 | Beccie, Equip, Griller, Skejs, VireZ        |
|           64 |     1699 | 2024-05-07 | Viperio             | W   | 1.000      | 0.333        | -                | 0.285 (0.095)    | -         |    14.83 | Equip, Griller, Skejs, tOPZ, VireZ          |
|           63 |     1707 | 2024-05-06 | Sashi Academy       | W   | 1.000      | -            | -                | -                | -         |     8.51 | Beccie, Equip, Griller, Skejs, VireZ        |
|           62 |     1711 | 2024-05-06 | WOPA Esport         | L   | 1.000      | -            | -                | -                | -         |   -15.61 | Beccie, Equip, Griller, Skejs, VireZ        |
|           61 |     1746 | 2024-05-06 | FAVBET Team         | L   | 1.000      | -            | -                | -                | -         |    -8.31 | Beccie, Equip, Griller, Skejs, VireZ        |
|           60 |     1779 | 2024-05-05 | Verdant             | L   | 1.000      | -            | -                | -                | -         |   -12.08 | Beccie, Equip, Griller, Skejs, VireZ        |
|           59 |     1894 | 2024-05-03 | GamerLegion Academy | W   | 1.000      | 0.333        | 0.018 (0.006)    | 0.691 (0.230)    | -         |    18.66 | Beccie, Equip, Griller, Skejs, VireZ        |
|           58 |     1998 | 2024-05-01 | WOPA Esport         | W   | 1.000      | 0.333        | 0.003 (0.001)    | 0.594 (0.198)    | -         |    15.15 | Beccie, Equip, Griller, Skejs, VireZ        |
|           57 |     2040 | 2024-04-30 | EXO Clan            | W   | 1.000      | 0.333        | 0.013 (0.004)    | 0.510 (0.170)    | -         |    24.78 | Beccie, Equip, Griller, Skejs, VireZ        |
|           56 |     2057 | 2024-04-29 | Sashi Esport        | L   | 0.997      | -            | -                | -                | -         |    -1.80 | Beccie, Equip, Griller, Skejs, VireZ        |
|           55 |     2068 | 2024-04-29 | Astralis Talent     | L   | 0.997      | -            | -                | -                | -         |   -10.49 | Beccie, Equip, Griller, Skejs, VireZ        |
|           54 |     2185 | 2024-04-27 | 777 Esports         | L   | 0.983      | -            | -                | -                | -         |   -15.43 | Beccie, Equip, Griller, Skejs, VireZ        |
|           53 |     2237 | 2024-04-26 | Esport Harte        | W   | 0.978      | -            | -                | -                | -         |     7.75 | Beccie, Equip, Griller, Skejs, VireZ        |
|           52 |     2240 | 2024-04-26 | JANO Esports        | W   | 0.978      | -            | -                | -                | -         |    14.44 | Beccie, Equip, Griller, Skejs, VireZ        |
|           51 |     2244 | 2024-04-26 | Sashi Esport        | L   | 0.977      | -            | -                | -                | -         |    -1.96 | Beccie, Equip, Griller, Skejs, VireZ        |
|           50 |     2251 | 2024-04-26 | Static              | W   | 0.977      | -            | -                | -                | -         |     7.84 | Beccie, Equip, Griller, Skejs, VireZ        |
|           49 |     2259 | 2024-04-26 | 777 Esports         | W   | 0.977      | 0.143        | 0.029 (0.004)    | 0.463 (0.065)    | -         |    15.77 | Beccie, Equip, Griller, Skejs, VireZ        |
|           48 |     2280 | 2024-04-26 | NOM Esports         | L   | 0.975      | -            | -                | -                | -         |   -18.16 | AcilioN, Beccie, Equip, Skejs, VireZ        |
|           47 |     2444 | 2024-04-22 | IMMAPROBLEM         | W   | 0.951      | -            | -                | -                | -         |     7.39 | Beccie, Equip, Griller, Skejs, VireZ        |
|           46 |     2449 | 2024-04-22 | XI Esport           | L   | 0.950      | -            | -                | -                | -         |   -18.73 | Beccie, Equip, Griller, Skejs, VireZ        |
|           45 |     2528 | 2024-04-21 | Astralis Talent     | L   | 0.941      | -            | -                | -                | -         |   -10.97 | Beccie, Equip, Griller, Skejs, VireZ        |
|           44 |     2559 | 2024-04-20 | Sashi Academy       | W   | 0.937      | -            | -                | -                | 1 (0.937) |     9.15 | Beccie, Equip, Griller, Skejs, VireZ        |
|           43 |     2947 | 2024-04-15 | Copenhagen Wolves   | L   | 0.904      | -            | -                | -                | -         |   -19.47 | Beccie, Equip, Griller, Skejs, VireZ        |
|           42 |     3597 | 2024-04-02 | 777 Esports         | L   | 0.817      | -            | -                | -                | -         |   -12.53 | Beccie, Equip, Griller, Skejs, VireZ        |
|           41 |     4380 | 2024-03-15 | HyperSpirit         | L   | 0.697      | -            | -                | -                | -         |   -13.13 | ADRON, GEOHYPE, kritik, smekk, swiiffter    |
|           40 |     4427 | 2024-03-14 | XI Esport           | W   | 0.691      | 0.333        | -                | 0.277 (0.064)    | -         |     7.10 | anber, Dengzoe, fez, foam, Scr0b            |
|           39 |     4591 | 2024-03-11 | Viperio             | L   | 0.671      | -            | -                | -                | -         |   -14.72 | beccie, Equip, Griller, Skejs, VireZ        |
|           38 |     4608 | 2024-03-11 | Astralis Talent     | L   | 0.671      | -            | -                | -                | -         |    -8.13 | ANSG1, JBOEN, kiR, kroK, tOPZ               |
|           37 |     4618 | 2024-03-11 | Copenhagen Wolves   | W   | 0.671      | -            | -                | -                | -         |     5.90 | beccie, Equip, Griller, Skejs, VireZ        |
|           36 |     4792 | 2024-03-07 | Virtuoso Squad      | W   | 0.645      | -            | -                | -                | -         |     2.98 | hahanz0, Maha, N1ghtMan, sinkieee, V0R4yn   |
|           35 |     4847 | 2024-03-06 | Sashi Esport        | L   | 0.638      | -            | -                | -                | -         |   -11.20 | beccie, Equip, Griller, Skejs, VireZ        |
|           34 |     4859 | 2024-03-06 | IMMAPROBLEM         | W   | 0.638      | -            | -                | -                | -         |     3.87 | Damkilde, daxy, NoProblemGuy, notaN, vester |
|           33 |     4873 | 2024-03-06 | Team Atlantic       | W   | 0.637      | -            | -                | -                | -         |     3.48 | beccie, Equip, Griller, Skejs, VireZ        |
|           32 |     4965 | 2024-03-05 | FAVBET Team         | L   | 0.630      | -            | -                | -                | -         |    -8.20 | bondik, guthriee, j3kie, Smash, t3ns1on     |
|           31 |     5189 | 2024-03-02 | Begrip Gaming       | W   | 0.610      | -            | -                | -                | -         |     4.99 | beccie, Equip, Griller, Skejs, VireZ        |
|           30 |     5229 | 2024-03-01 | ex-AVEZ             | W   | 0.604      | -            | -                | -                | -         |     1.80 | dezz, FOKUSSS, KhanCzesio, Masi, mazdaaa    |
|           29 |     5322 | 2024-02-28 | BRUTE               | L   | 0.590      | -            | -                | -                | -         |   -15.03 | heikkoL, m0nsterr, realzen, SiKO, w4rden    |
|           28 |     5354 | 2024-02-27 | XI Esport           | L   | 0.584      | -            | -                | -                | -         |   -13.19 | anber, Dengzoe, fez, foam, Scr0b            |
|           27 |     5363 | 2024-02-27 | WOPA Esport         | W   | 0.584      | -            | -                | -                | -         |     8.03 | brzer, Gnøffe, Leakz, LUMSEN, Pellyy        |
|           26 |     5397 | 2024-02-26 | ex-Guild Eagles     | L   | 0.578      | -            | -                | -                | -         |    -5.38 | beccie, Equip, Griller, Skejs, VireZ        |
|           25 |     5541 | 2024-02-24 | ex-AVEZ             | W   | 0.563      | -            | -                | -                | -         |     1.41 | dezz, FOKUSSS, KhanCzesio, Masi, mazdaaa    |
|           24 |     6409 | 2024-02-05 | IMMAPROBLEM         | W   | 0.438      | -            | -                | -                | -         |     2.17 | beccie, Equip, Griller, Skejs, VireZ        |
|           23 |     6415 | 2024-02-05 | Sashi Esport        | L   | 0.438      | -            | -                | -                | -         |    -8.10 | b0RUP, Fessor, niko, nut nut, sL1m3         |
|           22 |     6430 | 2024-02-05 | XI Esport           | W   | 0.437      | -            | -                | -                | -         |     3.96 | beccie, Equip, Griller, Skejs, VireZ        |
|           21 |     6662 | 2024-02-01 | Copenhagen Wolves   | L   | 0.411      | -            | -                | -                | -         |    -9.71 | Basso, smF, Svedjehed, szejn, vigg0         |
|           20 |     6672 | 2024-02-01 | EXO Clan            | L   | 0.410      | -            | -                | -                | -         |    -4.11 | Adam9130, AwaykeN, bevve, dobbo, Duplicate  |
|           19 |     6727 | 2024-01-31 | Sashi Academy       | L   | 0.403      | -            | -                | -                | -         |    -9.46 | Few, G0op, Mol011, ReXx, Sukker             |
|           18 |     6835 | 2024-01-29 | ex-KRC Genk Esports | W   | 0.390      | -            | -                | -                | -         |     3.02 | beccie, Equip, Griller, Skejs, VireZ        |
|           17 |     6870 | 2024-01-28 | Sashi Esport        | L   | 0.383      | -            | -                | -                | -         |   -10.27 | b0RUP, Fessor, n1Xen, niko, nut nut         |
|           16 |     7030 | 2024-01-26 | BLUEJAYS Lite       | W   | 0.371      | -            | -                | -                | -         |     1.18 | beccie, Equip, Griller, Skejs, VireZ        |
|           15 |     7218 | 2024-01-22 | WOPA Esport         | L   | 0.344      | -            | -                | -                | -         |    -6.39 | beccie, Equip, Griller, Skejs, VireZ        |
|           14 |     7223 | 2024-01-22 | Team Atlantic       | L   | 0.344      | -            | -                | -                | -         |    -9.58 | Folke, Inspire, logz, mupzG, Pellyy         |
|           13 |     7276 | 2024-01-21 | BRUTE               | W   | 0.337      | -            | -                | -                | -         |     1.49 | heikkoL, m0nsterr, realzen, SiKO, w4rden    |
|           12 |     7577 | 2024-01-17 | Sashi Academy       | W   | 0.310      | -            | -                | -                | -         |     2.10 | Few, G0op, Mol011, ReXx, Sukker             |
|           11 |     7706 | 2024-01-15 | Astralis Talent     | L   | 0.298      | -            | -                | -                | -         |    -4.05 | beccie, Equip, Griller, Skejs, VireZ        |
|           10 |     7922 | 2024-01-11 | ALTERNATE aTTaX     | L   | 0.271      | -            | -                | -                | -         |    -6.04 | beccie, Equip, Griller, Skejs, VireZ        |
|            9 |     7934 | 2024-01-11 | Momenta             | W   | 0.270      | -            | -                | -                | 1 (0.270) |     0.53 | gazi, kaas, thomass1, willi, Woody          |
|            8 |     7939 | 2024-01-11 | ALTERNATE aTTaX     | L   | 0.270      | -            | -                | -                | -         |    -6.06 | beccie, Equip, Griller, Skejs, VireZ        |
|            7 |     8246 | 2024-01-03 | SERA Esport         | W   | 0.218      | -            | -                | -                | -         |     0.62 | beccie, Equip, Griller, Skejs, VireZ        |
|            6 |     8264 | 2024-01-03 | XI Esport           | W   | 0.217      | -            | -                | -                | -         |     1.63 | Dengzoe, fez, foam, logz, Scr0b             |
|            5 |     9144 | 2023-12-07 | ROSOMAHA            | L   | 0.038      | -            | -                | -                | -         |    -0.99 | D0nii, Maggent, rendY, skcH, Зippoch        |
|            4 |     9288 | 2023-12-05 | Team LRP Poland     | L   | 0.024      | -            | -                | -                | -         |    -0.54 | beccie, Equip, Griller, Skejs, tauy0y0      |
|            3 |     9303 | 2023-12-05 | XI Esport           | L   | 0.023      | -            | -                | -                | -         |    -0.56 | anber, Dengzoe, foam, Pellyy, Scr0b         |
|            2 |     9371 | 2023-12-03 | ROSOMAHA            | W   | 0.010      | -            | -                | -                | -         |     0.05 | D0nii, Maggent, rendY, skcH, Зippoch        |
|            1 |     9484 | 2023-12-02 | GamerLegion Academy | L   | 0.003      | -            | -                | -                | -         |    -0.06 | aNdu, Darber, leaf, nestee, rud             |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($2,498.32)
- Divide that value by the 5th highest value among all rosters ($300,806.11)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-05-16 |      1.000 | $1,500.00      | $1,500.00       |
| 2024-04-27 |      0.984 | $802.70        | $789.99         |
| 2024-02-02 |      0.417 | $500.00        | $208.33         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
