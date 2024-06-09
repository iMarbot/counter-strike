### Roster Details<br />
Team Name: Preasy Esport<br />
Roster: Beccie, Equip, Griller, Skejs, VireZ<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [230](../standings_global.md)<br />
Regional Rank: [154]( ../standings_europe.md)<br />
Final Rank Value:  701.8<br />
<br />
Final Rank Value (701.8) = Starting Rank Value (893.1) + Head To Head Adjustments (-191.3)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.325[<sup>1</sup>](#table2)
- Bounty Collected: 0.333[<sup>2</sup>](#table1)
- Opponent Network: 0.185[<sup>2</sup>](#table1)
- LAN Wins: 0.128[<sup>2</sup>](#table1)

The average of these factors is 0.243<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 893.1
- 400 + ( ( 0.243 - 0.000 ) / ( 0.787 - 0.000 ) ) * 1600 = 893.1


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent             | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                      |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           94 |       70 | 2024-05-29 | Copenhagen Wolves    | L   | 1.000      | -            | -                | -                | -         |   -13.32 | Beccie, Equip, Griller, Skejs, VireZ        |
|           93 |       86 | 2024-05-29 | VOLT                 | W   | 1.000      | -            | -                | -                | 0 (0.000) |     4.83 | Beccie, Equip, Griller, Skejs, VireZ        |
|           92 |      131 | 2024-05-28 | Young Ninjas         | L   | 1.000      | -            | -                | -                | -         |    -9.12 | Beccie, Equip, Griller, Skejs, VireZ        |
|           91 |      143 | 2024-05-28 | Permitta Esports     | L   | 1.000      | -            | -                | -                | -         |   -11.95 | Beccie, Equip, Griller, Skejs, VireZ        |
|           90 |      146 | 2024-05-28 | Astralis Talent      | L   | 1.000      | -            | -                | -                | -         |   -15.02 | Beccie, Equip, Griller, Skejs, VireZ        |
|           89 |      180 | 2024-05-27 | Sashi Academy        | W   | 1.000      | -            | -                | -                | 0 (0.000) |     8.28 | Beccie, Equip, Griller, Skejs, VireZ        |
|           88 |      184 | 2024-05-27 | Sashi Esport         | W   | 1.000      | 0.143        | 0.154 (0.022)    | 1.000 (0.143)    | 0 (0.000) |    29.66 | Beccie, Equip, Griller, Skejs, VireZ        |
|           87 |      199 | 2024-05-27 | Illuminar Gaming     | L   | 1.000      | -            | -                | -                | -         |   -14.31 | Beccie, Equip, Griller, Skejs, VireZ        |
|           86 |      236 | 2024-05-26 | Johnny Speeds        | L   | 1.000      | -            | -                | -                | -         |    -4.65 | Beccie, Equip, Griller, Skejs, VireZ        |
|           85 |      274 | 2024-05-25 | Reason Gaming        | W   | 1.000      | 0.333        | 0.004 (0.001)    | -                | 0 (0.000) |    16.83 | Beccie, Equip, Griller, Skejs, VireZ        |
|           84 |      406 | 2024-05-23 | Monte Gen            | L   | 1.000      | -            | -                | -                | -         |   -11.04 | Beccie, Equip, Griller, Skejs, VireZ        |
|           83 |      420 | 2024-05-23 | Nexus Gaming         | L   | 1.000      | -            | -                | -                | -         |   -10.87 | Beccie, Equip, Griller, Skejs, VireZ        |
|           82 |      510 | 2024-05-22 | Denial               | L   | 1.000      | -            | -                | -                | -         |   -20.89 | Beccie, Equip, Griller, Skejs, VireZ        |
|           81 |      522 | 2024-05-22 | Dynamo Eclot         | W   | 1.000      | 0.371        | 0.097 (0.036)    | 0.940 (0.348)    | 0 (0.000) |    22.30 | Beccie, Equip, Griller, Skejs, VireZ        |
|           80 |      677 | 2024-05-20 | XI Esport            | L   | 1.000      | -            | -                | -                | -         |   -19.31 | Beccie, Equip, Griller, Skejs, VireZ        |
|           79 |      694 | 2024-05-20 | Astralis Talent      | L   | 1.000      | -            | -                | -                | -         |   -15.62 | Beccie, Equip, Griller, Skejs, VireZ        |
|           78 |      722 | 2024-05-20 | Denial               | L   | 1.000      | -            | -                | -                | -         |   -23.34 | Beccie, Equip, Griller, Skejs, VireZ        |
|           77 |      765 | 2024-05-19 | Lemoncats            | L   | 1.000      | -            | -                | -                | -         |   -26.46 | AcilioN, Beccie, Griller, Skejs, VireZ      |
|           76 |     1220 | 2024-05-15 | kONO.ECF             | L   | 1.000      | -            | -                | -                | -         |   -11.09 | Beccie, Equip, Griller, Skejs, VireZ        |
|           75 |     1410 | 2024-05-12 | Johnny Speeds        | W   | 1.000      | 0.333        | 0.056 (0.019)    | 0.683 (0.228)    | 0 (0.000) |    24.13 | Beccie, Equip, Griller, Skejs, VireZ        |
|           74 |     1495 | 2024-05-11 | Passion UA           | L   | 1.000      | -            | -                | -                | -         |    -9.60 | Beccie, Equip, Griller, Skejs, VireZ        |
|           73 |     1513 | 2024-05-10 | Illuminar Gaming     | W   | 1.000      | -            | -                | -                | 0 (0.000) |    15.81 | Beccie, Equip, Griller, Skejs, VireZ        |
|           72 |     1574 | 2024-05-09 | ENCE Academy         | W   | 1.000      | 0.143        | 0.012 (0.002)    | -                | 0 (0.000) |    14.14 | AcilioN, Beccie, Griller, Skejs, VireZ      |
|           71 |     1596 | 2024-05-09 | kONO.ECF             | W   | 1.000      | 0.333        | 0.013 (0.004)    | 0.853 (0.284)    | -         |    22.15 | AcilioN, Beccie, Griller, Skejs, VireZ      |
|           70 |     1658 | 2024-05-08 | Illuminar Gaming     | L   | 1.000      | -            | -                | -                | -         |   -13.18 | Beccie, Equip, Griller, Skejs, VireZ        |
|           69 |     1706 | 2024-05-07 | UNiTY esports        | L   | 1.000      | -            | -                | -                | -         |   -11.58 | Beccie, Equip, Griller, Skejs, VireZ        |
|           68 |     1719 | 2024-05-07 | Viperio              | W   | 1.000      | 0.333        | -                | 0.285 (0.095)    | -         |    14.80 | Equip, Griller, Skejs, tOPZ, VireZ          |
|           67 |     1727 | 2024-05-06 | Sashi Academy        | W   | 1.000      | -            | -                | -                | -         |     8.56 | Beccie, Equip, Griller, Skejs, VireZ        |
|           66 |     1731 | 2024-05-06 | WOPA Esport          | L   | 1.000      | -            | -                | -                | -         |   -15.57 | Beccie, Equip, Griller, Skejs, VireZ        |
|           65 |     1769 | 2024-05-06 | FAVBET Team          | L   | 1.000      | -            | -                | -                | -         |    -9.43 | Beccie, Equip, Griller, Skejs, VireZ        |
|           64 |     1802 | 2024-05-05 | Verdant              | L   | 1.000      | -            | -                | -                | -         |   -11.79 | Beccie, Equip, Griller, Skejs, VireZ        |
|           63 |     1919 | 2024-05-03 | GamerLegion Academy  | W   | 1.000      | 0.333        | 0.018 (0.006)    | 0.691 (0.230)    | -         |    17.81 | Beccie, Equip, Griller, Skejs, VireZ        |
|           62 |     2028 | 2024-05-01 | WOPA Esport          | W   | 1.000      | 0.333        | 0.003 (0.001)    | 0.594 (0.198)    | -         |    15.02 | Beccie, Equip, Griller, Skejs, VireZ        |
|           61 |     2074 | 2024-04-30 | EXO Clan             | W   | 1.000      | 0.333        | 0.013 (0.004)    | 0.579 (0.193)    | -         |    25.13 | Beccie, Equip, Griller, Skejs, VireZ        |
|           60 |     2091 | 2024-04-29 | Sashi Esport         | L   | 0.997      | -            | -                | -                | -         |    -1.85 | Beccie, Equip, Griller, Skejs, VireZ        |
|           59 |     2103 | 2024-04-29 | Astralis Talent      | L   | 0.997      | -            | -                | -                | -         |   -10.62 | Beccie, Equip, Griller, Skejs, VireZ        |
|           58 |     2220 | 2024-04-27 | 777 Esports          | L   | 0.983      | -            | -                | -                | -         |   -15.55 | Beccie, Equip, Griller, Skejs, VireZ        |
|           57 |     2273 | 2024-04-26 | Esport Harte         | W   | 0.978      | -            | -                | -                | -         |     7.62 | Beccie, Equip, Griller, Skejs, VireZ        |
|           56 |     2276 | 2024-04-26 | JANO Esports         | W   | 0.978      | -            | -                | -                | -         |    14.89 | Beccie, Equip, Griller, Skejs, VireZ        |
|           55 |     2280 | 2024-04-26 | Sashi Esport         | L   | 0.977      | -            | -                | -                | -         |    -2.02 | Beccie, Equip, Griller, Skejs, VireZ        |
|           54 |     2287 | 2024-04-26 | Static               | W   | 0.977      | -            | -                | -                | -         |     7.70 | Beccie, Equip, Griller, Skejs, VireZ        |
|           53 |     2295 | 2024-04-26 | 777 Esports          | W   | 0.977      | 0.143        | 0.029 (0.004)    | 0.463 (0.065)    | -         |    15.62 | Beccie, Equip, Griller, Skejs, VireZ        |
|           52 |     2317 | 2024-04-26 | NOM Esports          | L   | 0.975      | -            | -                | -                | -         |   -18.27 | AcilioN, Beccie, Equip, Skejs, VireZ        |
|           51 |     2492 | 2024-04-22 | IMMAPROBLEM          | W   | 0.951      | -            | -                | -                | -         |     7.29 | Beccie, Equip, Griller, Skejs, VireZ        |
|           50 |     2499 | 2024-04-22 | XI Esport            | L   | 0.950      | -            | -                | -                | -         |   -18.84 | Beccie, Equip, Griller, Skejs, VireZ        |
|           49 |     2581 | 2024-04-21 | Astralis Talent      | L   | 0.941      | -            | -                | -                | -         |   -11.07 | Beccie, Equip, Griller, Skejs, VireZ        |
|           48 |     2612 | 2024-04-20 | Sashi Academy        | W   | 0.937      | -            | -                | -                | 1 (0.937) |     9.05 | Beccie, Equip, Griller, Skejs, VireZ        |
|           47 |     3009 | 2024-04-15 | Copenhagen Wolves    | L   | 0.904      | -            | -                | -                | -         |   -18.34 | Beccie, Equip, Griller, Skejs, VireZ        |
|           46 |     3686 | 2024-04-02 | 777 Esports          | L   | 0.817      | -            | -                | -                | -         |   -12.63 | Beccie, Equip, Griller, Skejs, VireZ        |
|           45 |     3718 | 2024-04-01 | Natus Vincere Junior | L   | 0.809      | -            | -                | -                | -         |   -14.47 | Beccie, Equip, Griller, Skejs, VireZ        |
|           44 |     3794 | 2024-03-29 | EPIC DUDES           | W   | 0.791      | -            | -                | -                | -         |     2.68 | Beccie, Equip, Griller, Skejs, VireZ        |
|           43 |     4041 | 2024-03-24 | Illuminar Junior     | W   | 0.757      | -            | -                | -                | -         |     2.44 | Ki3lo, Klab, MeHow, Merdi, Niels            |
|           42 |     4238 | 2024-03-20 | SINNERS Academy      | W   | 0.730      | -            | -                | -                | -         |     6.28 | BORO, DALIEN, dreez, majky, vANO            |
|           41 |     4488 | 2024-03-15 | HyperSpirit          | L   | 0.697      | -            | -                | -                | -         |   -13.35 | ADRON, GEOHYPE, kritik, smekk, swiiffter    |
|           40 |     4541 | 2024-03-14 | XI Esport            | W   | 0.691      | 0.333        | -                | 0.277 (0.064)    | -         |     6.97 | anber, Dengzoe, fez, foam, Scr0b            |
|           39 |     4713 | 2024-03-11 | Viperio              | L   | 0.671      | -            | -                | -                | -         |   -14.49 | beccie, Equip, Griller, Skejs, VireZ        |
|           38 |     4730 | 2024-03-11 | Astralis Talent      | L   | 0.671      | -            | -                | -                | -         |    -8.26 | ANSG1, JBOEN, kiR, kroK, tOPZ               |
|           37 |     4740 | 2024-03-11 | Copenhagen Wolves    | W   | 0.671      | -            | -                | -                | -         |     6.19 | beccie, Equip, Griller, Skejs, VireZ        |
|           36 |     4921 | 2024-03-07 | Virtuoso Squad       | W   | 0.645      | -            | -                | -                | -         |     2.89 | hahanz0, Maha, N1ghtMan, sinkieee, V0R4yn   |
|           35 |     4978 | 2024-03-06 | Sashi Esport         | L   | 0.638      | -            | -                | -                | -         |   -11.29 | beccie, Equip, Griller, Skejs, VireZ        |
|           34 |     4990 | 2024-03-06 | IMMAPROBLEM          | W   | 0.638      | -            | -                | -                | -         |     3.76 | Damkilde, daxy, NoProblemGuy, notaN, vester |
|           33 |     5004 | 2024-03-06 | Team Atlantic        | W   | 0.637      | -            | -                | -                | -         |     3.37 | beccie, Equip, Griller, Skejs, VireZ        |
|           32 |     5108 | 2024-03-05 | FAVBET Team          | L   | 0.630      | -            | -                | -                | -         |    -8.10 | bondik, guthriee, j3kie, Smash, t3ns1on     |
|           31 |     5337 | 2024-03-02 | Begrip Gaming        | W   | 0.610      | -            | -                | -                | -         |     4.86 | beccie, Equip, Griller, Skejs, VireZ        |
|           30 |     5378 | 2024-03-01 | ex-AVEZ              | W   | 0.604      | -            | -                | -                | -         |     1.73 | dezz, FOKUSSS, KhanCzesio, Masi, mazdaaa    |
|           29 |     5473 | 2024-02-28 | BRUTE                | L   | 0.590      | -            | -                | -                | -         |   -15.14 | heikkoL, m0nsterr, realzen, SiKO, w4rden    |
|           28 |     5507 | 2024-02-27 | XI Esport            | L   | 0.584      | -            | -                | -                | -         |   -13.31 | anber, Dengzoe, fez, foam, Scr0b            |
|           27 |     5516 | 2024-02-27 | WOPA Esport          | W   | 0.584      | -            | -                | -                | -         |     7.87 | brzer, Gnøffe, Leakz, LUMSEN, Pellyy        |
|           26 |     5554 | 2024-02-26 | ex-Guild Eagles      | L   | 0.578      | -            | -                | -                | -         |    -5.41 | beccie, Equip, Griller, Skejs, VireZ        |
|           25 |     5701 | 2024-02-24 | ex-AVEZ              | W   | 0.563      | -            | -                | -                | -         |     1.35 | dezz, FOKUSSS, KhanCzesio, Masi, mazdaaa    |
|           24 |     6607 | 2024-02-05 | IMMAPROBLEM          | W   | 0.438      | -            | -                | -                | -         |     2.09 | beccie, Equip, Griller, Skejs, VireZ        |
|           23 |     6613 | 2024-02-05 | Sashi Esport         | L   | 0.438      | -            | -                | -                | -         |    -8.20 | b0RUP, Fessor, niko, nut nut, sL1m3         |
|           22 |     6630 | 2024-02-05 | XI Esport            | W   | 0.437      | -            | -                | -                | -         |     3.86 | beccie, Equip, Griller, Skejs, VireZ        |
|           21 |     6867 | 2024-02-01 | Copenhagen Wolves    | L   | 0.411      | -            | -                | -                | -         |    -9.47 | Basso, smF, Svedjehed, szejn, vigg0         |
|           20 |     6881 | 2024-02-01 | EXO Clan             | L   | 0.410      | -            | -                | -                | -         |    -4.04 | Adam9130, AwaykeN, bevve, dobbo, Duplicate  |
|           19 |     6939 | 2024-01-31 | Sashi Academy        | L   | 0.403      | -            | -                | -                | -         |    -9.54 | Few, G0op, Mol011, ReXx, Sukker             |
|           18 |     7051 | 2024-01-29 | ex-KRC Genk Esports  | W   | 0.390      | -            | -                | -                | -         |     3.78 | beccie, Equip, Griller, Skejs, VireZ        |
|           17 |     7088 | 2024-01-28 | Sashi Esport         | L   | 0.383      | -            | -                | -                | -         |   -10.33 | b0RUP, Fessor, n1Xen, niko, nut nut         |
|           16 |     7253 | 2024-01-26 | BLUEJAYS Lite        | W   | 0.371      | -            | -                | -                | -         |     1.14 | beccie, Equip, Griller, Skejs, VireZ        |
|           15 |     7460 | 2024-01-22 | WOPA Esport          | L   | 0.344      | -            | -                | -                | -         |    -6.49 | beccie, Equip, Griller, Skejs, VireZ        |
|           14 |     7466 | 2024-01-22 | Team Atlantic        | L   | 0.344      | -            | -                | -                | -         |    -9.62 | Folke, Inspire, logz, mupzG, Pellyy         |
|           13 |     7519 | 2024-01-21 | BRUTE                | W   | 0.337      | -            | -                | -                | -         |     1.43 | heikkoL, m0nsterr, realzen, SiKO, w4rden    |
|           12 |     7826 | 2024-01-17 | Sashi Academy        | W   | 0.310      | -            | -                | -                | -         |     2.05 | Few, G0op, Mol011, ReXx, Sukker             |
|           11 |     7955 | 2024-01-15 | Astralis Talent      | L   | 0.298      | -            | -                | -                | -         |    -4.14 | beccie, Equip, Griller, Skejs, VireZ        |
|           10 |     8175 | 2024-01-11 | ALTERNATE aTTaX      | L   | 0.271      | -            | -                | -                | -         |    -2.73 | beccie, Equip, Griller, Skejs, VireZ        |
|            9 |     8187 | 2024-01-11 | Momenta              | W   | 0.270      | -            | -                | -                | 1 (0.270) |     0.51 | gazi, kaas, thomass1, willi, Woody          |
|            8 |     8192 | 2024-01-11 | ALTERNATE aTTaX      | L   | 0.270      | -            | -                | -                | -         |    -2.69 | beccie, Equip, Griller, Skejs, VireZ        |
|            7 |     8502 | 2024-01-03 | SERA Esport          | W   | 0.218      | -            | -                | -                | -         |     0.62 | beccie, Equip, Griller, Skejs, VireZ        |
|            6 |     8520 | 2024-01-03 | XI Esport            | W   | 0.217      | -            | -                | -                | -         |     1.63 | Dengzoe, fez, foam, logz, Scr0b             |
|            5 |     9417 | 2023-12-07 | ROSOMAHA             | L   | 0.038      | -            | -                | -                | -         |    -0.99 | D0nii, Maggent, rendY, skcH, Зippoch        |
|            4 |     9570 | 2023-12-05 | Team LRP Poland      | L   | 0.024      | -            | -                | -                | -         |    -0.54 | beccie, Equip, Griller, Skejs, tauy0y0      |
|            3 |     9585 | 2023-12-05 | XI Esport            | L   | 0.023      | -            | -                | -                | -         |    -0.56 | anber, Dengzoe, foam, Pellyy, Scr0b         |
|            2 |     9653 | 2023-12-03 | ROSOMAHA             | W   | 0.010      | -            | -                | -                | -         |     0.05 | D0nii, Maggent, rendY, skcH, Зippoch        |
|            1 |     9766 | 2023-12-02 | GamerLegion Academy  | L   | 0.003      | -            | -                | -                | -         |    -0.06 | aNdu, Darber, leaf, nestee, rud             |

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
