### Roster Details<br />
Team Name: Preasy Esport<br />
Roster: Beccie, Equip, Griller, Skejs, VireZ<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [168](../standings_global.md)<br />
Regional Rank: [113]( ../standings_europe.md)<br />
Final Rank Value:  756.0<br />
<br />
Final Rank Value (756.0) = Starting Rank Value (822.1) + Head To Head Adjustments (-66.1)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.316[<sup>1</sup>](#table2)
- Bounty Collected: 0.286[<sup>2</sup>](#table1)
- Opponent Network: 0.089[<sup>2</sup>](#table1)
- LAN Wins: 0.160[<sup>2</sup>](#table1)

The average of these factors is 0.213<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 822.1
- 400 + ( ( 0.213 - 0.000 ) / ( 0.806 - 0.000 ) ) * 1600 = 822.1


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent                 | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins      | H2H Adj. | Roster                                      |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           55 |       26 | 2024-05-05 | Verdant                  | L   | 1.000      | -            | -                | -                | -             |   -10.69 | Beccie, Equip, Griller, Skejs, VireZ        |
|           54 |      122 | 2024-05-03 | GamerLegion Academy      | W   | 1.000      | 0.333        | 0.043 (0.014)    | 0.567 (0.189)    | false (0.000) |    21.61 | Beccie, Equip, Griller, Skejs, VireZ        |
|           53 |      216 | 2024-05-01 | WOPA Esport              | W   | 1.000      | 0.333        | 0.009 (0.003)    | 0.485 (0.162)    | false (0.000) |    16.07 | Beccie, Equip, Griller, Skejs, VireZ        |
|           52 |      252 | 2024-04-30 | EXO Clan                 | W   | 1.000      | 0.333        | 0.019 (0.006)    | 0.418 (0.139)    | false (0.000) |    23.97 | Beccie, Equip, Griller, Skejs, VireZ        |
|           51 |      267 | 2024-04-29 | Sashi Esport             | L   | 1.000      | -            | -                | -                | -             |    -1.35 | Beccie, Equip, Griller, Skejs, VireZ        |
|           50 |      277 | 2024-04-29 | Astralis Talent          | L   | 1.000      | -            | -                | -                | -             |    -9.51 | Beccie, Equip, Griller, Skejs, VireZ        |
|           49 |      367 | 2024-04-27 | 777 Esports              | L   | 1.000      | -            | -                | -                | -             |   -14.91 | Beccie, Equip, Griller, Skejs, VireZ        |
|           48 |      403 | 2024-04-26 | Esport Harte             | W   | 1.000      | -            | -                | -                | false (0.000) |     9.47 | Beccie, Equip, Griller, Skejs, VireZ        |
|           47 |      406 | 2024-04-26 | JANO Esports             | W   | 1.000      | 0.143        | 0.006 (0.001)    | 0.407 (0.058)    | false (0.000) |    16.75 | Beccie, Equip, Griller, Skejs, VireZ        |
|           46 |      410 | 2024-04-26 | Sashi Esport             | L   | 1.000      | -            | -                | -                | -             |    -1.45 | Beccie, Equip, Griller, Skejs, VireZ        |
|           45 |      417 | 2024-04-26 | Static                   | W   | 1.000      | 0.143        | -                | 0.226 (0.032)    | false (0.000) |     8.77 | Beccie, Equip, Griller, Skejs, VireZ        |
|           44 |      426 | 2024-04-26 | 777 Esports              | W   | 1.000      | 0.143        | 0.032 (0.005)    | 0.550 (0.079)    | false (0.000) |    17.09 | Beccie, Equip, Griller, Skejs, VireZ        |
|           43 |      444 | 2024-04-26 | NOM Esports              | L   | 1.000      | -            | -                | -                | -             |   -15.66 | AcilioN, Beccie, Equip, Skejs, VireZ        |
|           42 |      598 | 2024-04-22 | IMMAPROBLEM              | W   | 1.000      | -            | -                | -                | false (0.000) |     9.37 | Beccie, Equip, Griller, Skejs, VireZ        |
|           41 |      602 | 2024-04-22 | XI Esport                | L   | 1.000      | -            | -                | -                | -             |   -17.43 | Beccie, Equip, Griller, Skejs, VireZ        |
|           40 |      669 | 2024-04-21 | Astralis Talent          | L   | 1.000      | -            | -                | -                | -             |   -10.01 | Beccie, Equip, Griller, Skejs, VireZ        |
|           39 |      695 | 2024-04-20 | Sashi Academy            | W   | 1.000      | 0.143        | 0.004 (0.001)    | -                | true (1.000)  |    11.96 | Beccie, Equip, Griller, Skejs, VireZ        |
|           38 |     1040 | 2024-04-15 | Copenhagen Wolves        | L   | 1.000      | -            | -                | -                | -             |   -19.22 | Beccie, Equip, Griller, Skejs, VireZ        |
|           37 |     1576 | 2024-04-02 | 777 Esports              | L   | 0.978      | -            | -                | -                | -             |   -13.05 | Beccie, Equip, Griller, Skejs, VireZ        |
|           36 |     2219 | 2024-03-15 | HyperSpirit              | L   | 0.858      | -            | -                | -                | -             |   -15.58 | ADRON, GEOHYPE, kritik, smekk, swiiffter    |
|           35 |     2267 | 2024-03-14 | XI Esport                | W   | 0.852      | 0.333        | 0.002 (0.001)    | 0.313 (0.089)    | -             |    10.81 | anber, Dengzoe, fez, foam, Scr0b            |
|           34 |     2399 | 2024-03-11 | Viperio                  | L   | 0.832      | -            | -                | -                | -             |   -15.87 | beccie, Equip, Griller, Skejs, VireZ        |
|           33 |     2413 | 2024-03-11 | Astralis Talent          | L   | 0.832      | -            | -                | -                | -             |    -8.57 | ANSG1, JBOEN, kiR, kroK, tOPZ               |
|           32 |     2422 | 2024-03-11 | Copenhagen Wolves        | W   | 0.832      | 0.143        | -                | 0.417 (0.050)    | -             |     9.29 | beccie, Equip, Griller, Skejs, VireZ        |
|           31 |     2558 | 2024-03-07 | Virtuoso Squad           | W   | 0.806      | -            | -                | -                | -             |     3.22 | hahanz0, Maha, N1ghtMan, sinkieee, V0R4yn   |
|           30 |     2607 | 2024-03-06 | IMMAPROBLEM              | W   | 0.799      | -            | -                | -                | -             |     6.79 | Damkilde, daxy, NoProblemGuy, notaN, vester |
|           29 |     2621 | 2024-03-06 | Team Atlantic            | W   | 0.799      | -            | -                | -                | -             |     6.49 | beccie, Equip, Griller, Skejs, VireZ        |
|           28 |     2702 | 2024-03-05 | BLESSED (Ukrainian team) | L   | 0.791      | -            | -                | -                | -             |    -7.75 | bondik, guthriee, j3kie, Smash, t3ns1on     |
|           27 |     2882 | 2024-03-02 | Begrip Gaming            | W   | 0.771      | 0.289        | -                | 0.196 (0.044)    | -             |     9.37 | beccie, Equip, Griller, Skejs, VireZ        |
|           26 |     2991 | 2024-02-28 | BRUTE                    | L   | 0.751      | -            | -                | -                | -             |   -18.14 | heikkoL, m0nsterr, realzen, SiKO, w4rden    |
|           25 |     3018 | 2024-02-27 | XI Esport                | L   | 0.746      | -            | -                | -                | -             |   -14.30 | anber, Dengzoe, fez, foam, Scr0b            |
|           24 |     3026 | 2024-02-27 | WOPA Esport              | W   | 0.745      | 0.143        | 0.009 (0.001)    | 0.485 (0.052)    | -             |    11.32 | brzer, Gnøffe, Leakz, LUMSEN, Pellyy        |
|           23 |     3059 | 2024-02-26 | Guild Eagles             | L   | 0.739      | -            | -                | -                | -             |    -3.30 | beccie, Equip, Griller, Skejs, VireZ        |
|           22 |     3884 | 2024-02-05 | IMMAPROBLEM              | W   | 0.599      | -            | -                | -                | -             |     4.33 | beccie, Equip, Griller, Skejs, VireZ        |
|           21 |     3889 | 2024-02-05 | Sashi Esport             | L   | 0.599      | -            | -                | -                | -             |    -8.12 | b0RUP, Fessor, niko, nut nut, PR1mE         |
|           20 |     3902 | 2024-02-05 | XI Esport                | W   | 0.598      | 0.143        | 0.002 (0.000)    | -                | -             |     7.57 | beccie, Equip, Griller, Skejs, VireZ        |
|           19 |     4066 | 2024-02-01 | Copenhagen Wolves        | L   | 0.572      | -            | -                | -                | -             |   -11.41 | Basso, smF, Svedjehed, szejn, vigg0         |
|           18 |     4075 | 2024-02-01 | EXO Clan                 | L   | 0.571      | -            | -                | -                | -             |    -6.15 | Adam9130, AwaykeN, bevve, dobbo, Duplicate  |
|           17 |     4117 | 2024-01-31 | Sashi Academy            | L   | 0.564      | -            | -                | -                | -             |   -11.45 | Few, G0op, Mol011, ReXx, Sukker             |
|           16 |     4218 | 2024-01-28 | Sashi Esport             | L   | 0.545      | -            | -                | -                | -             |   -14.00 | b0RUP, Fessor, n1Xen, niko, nut nut         |
|           15 |     4311 | 2024-01-26 | BLUEJAYS Lite            | W   | 0.532      | -            | -                | -                | -             |     4.31 | beccie, Equip, Griller, Skejs, VireZ        |
|           14 |     4465 | 2024-01-22 | Team Atlantic            | L   | 0.505      | -            | -                | -                | -             |   -13.12 | Folke, Inspire, logz, mupzG, zEden          |
|           13 |     4504 | 2024-01-21 | BRUTE                    | W   | 0.498      | -            | -                | -                | -             |     2.65 | heikkoL, m0nsterr, realzen, SiKO, w4rden    |
|           12 |     4747 | 2024-01-17 | Sashi Academy            | W   | 0.471      | 0.289        | 0.004 (0.000)    | -                | -             |     4.51 | Few, G0op, Mol011, ReXx, Sukker             |
|           11 |     4830 | 2024-01-15 | Astralis Talent          | L   | 0.459      | -            | -                | -                | -             |    -4.12 | beccie, Equip, Griller, Skejs, VireZ        |
|           10 |     4987 | 2024-01-11 | ALTERNATE aTTaX          | L   | 0.432      | -            | -                | -                | -             |    -2.68 | beccie, Equip, Griller, Skejs, VireZ        |
|            9 |     4995 | 2024-01-11 | Momenta                  | W   | 0.431      | -            | -                | -                | true (0.431)  |     1.28 | gazi, kaas, thomass1, willi, Woody          |
|            8 |     4999 | 2024-01-11 | ALTERNATE aTTaX          | L   | 0.431      | -            | -                | -                | -             |    -2.58 | beccie, Equip, Griller, Skejs, VireZ        |
|            7 |     5870 | 2023-12-07 | ROSOMAHA                 | L   | 0.199      | -            | -                | -                | -             |    -4.70 | D0nii, Maggent, rendY, skcH, Зippoch        |
|            6 |     5982 | 2023-12-05 | FALKE ESPORTS            | L   | 0.185      | -            | -                | -                | -             |    -4.99 | beccie, Equip, Griller, Skejs, tauy0y0      |
|            5 |     5993 | 2023-12-05 | XI Esport                | L   | 0.184      | -            | -                | -                | -             |    -3.92 | anber, Dengzoe, foam, Pellyy, Scr0b         |
|            4 |     6042 | 2023-12-03 | ROSOMAHA                 | W   | 0.171      | -            | -                | -                | -             |     1.33 | D0nii, Maggent, rendY, skcH, Зippoch        |
|            3 |     6116 | 2023-12-02 | GamerLegion Academy      | L   | 0.164      | -            | -                | -                | -             |    -2.21 | aNdu, Darber, leaf, nestee, rud             |
|            2 |     6376 | 2023-11-27 | SINNERS Academy          | W   | 0.131      | -            | -                | -                | -             |     1.32 | beccie, Equip, Griller, Skejs, tauy0y0      |
|            1 |     6507 | 2023-11-23 | Sampi NEXT               | W   | 0.105      | -            | -                | -                | -             |     0.46 | bestch, DALIEN, EMCOR, ramon, Verttzzz      |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($1,091.56)
- Divide that value by the 5th highest value among all rosters ($158,437.64)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-04-27 |      1.000 | $802.70        | $802.70         |
| 2024-02-02 |      0.578 | $500.00        | $288.87         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
