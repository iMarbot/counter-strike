### Roster Details<br />
Team Name: ex-Preasy Esport<br />
Roster: Altekz, kristou, refrezh, roeJ, TMB<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [62](../standings_global.md)<br />
Regional Rank: [43]( ../standings_europe.md)<br />
Final Rank Value:  993.9<br />
<br />
Final Rank Value (993.9) = Starting Rank Value (913.1) + Head To Head Adjustments (80.8)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.437[<sup>1</sup>](#table2)
- Bounty Collected: 0.369[<sup>2</sup>](#table1)
- Opponent Network: 0.147[<sup>2</sup>](#table1)
- LAN Wins: 0.057[<sup>2</sup>](#table1)

The average of these factors is 0.252<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 913.1
- 400 + ( ( 0.252 - 0.000 ) / ( 0.787 - 0.000 ) ) * 1600 = 913.1


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
|           57 |     3111 | 2024-04-13 | 3DMAX                     | L   | 0.889      | -            | -                | -                | -         |   -15.81 | Altekz, kristou, refrezh, roeJ, TMB            |
|           56 |     3439 | 2024-04-07 | Zero Tenacity             | W   | 0.848      | 0.143        | 0.147 (0.018)    | 1.000 (0.121)    | 0 (0.000) |    13.02 | Altekz, kristou, refrezh, roeJ, TMB            |
|           55 |     3957 | 2024-03-26 | Raptors Esports Club      | L   | 0.771      | -            | -                | -                | -         |   -17.53 | BehinDx, Karrar, moz, PrimeOPI, wfn            |
|           54 |     4138 | 2024-03-22 | FORZE Esports             | L   | 0.743      | -            | -                | -                | -         |   -10.68 | gokushima, r3salt, SELLTER, shalfey, tN1R      |
|           53 |     4329 | 2024-03-18 | Team Sampi                | W   | 0.715      | 0.371        | 0.039 (0.010)    | 0.677 (0.179)    | 0 (0.000) |     9.95 | fino, manguss, sAvana1, The eLiVe, ZEDKO       |
|           52 |     4439 | 2024-03-16 | Passion UA                | W   | 0.703      | 0.371        | 0.057 (0.015)    | 1.000 (0.260)    | 0 (0.000) |     9.55 | fear, jackasmo, jambo, s-chilla, zeRRoFIX      |
|           51 |     4564 | 2024-03-14 | Entropiq                  | W   | 0.688      | -            | -                | -                | 0 (0.000) |     4.06 | Altekz, kristou, refrezh, roeJ, TMB            |
|           50 |     4722 | 2024-03-11 | Metizport                 | L   | 0.671      | -            | -                | -                | -         |    -8.91 | adamb, Jackinho, nilo, susp, ztr               |
|           49 |     4744 | 2024-03-11 | HEROIC                    | L   | 0.670      | -            | -                | -                | -         |    -0.40 | Altekz, dupreeh, refrezh, roeJ, TMB            |
|           48 |     4754 | 2024-03-11 | Permitta Esports          | W   | 0.669      | 0.371        | 0.025 (0.006)    | 1.000 (0.248)    | 0 (0.000) |    10.09 | Altekz, kristou, refrezh, roeJ, TMB            |
|           47 |     4867 | 2024-03-09 | ex-K10                    | W   | 0.655      | 0.371        | -                | 0.517 (0.126)    | 0 (0.000) |     5.55 | Altekz, kristou, refrezh, roeJ, TMB            |
|           46 |     4959 | 2024-03-07 | Team Secret               | W   | 0.642      | -            | -                | -                | 0 (0.000) |     2.40 | anarkez, innocent, Kind0, Maze, Tauson         |
|           45 |     5210 | 2024-03-03 | Gaimin Gladiators         | W   | 0.618      | 0.143        | 0.092 (0.008)    | -                | 0 (0.000) |    16.31 | kraghen, Nodios, Patti, Queenix, salazar       |
|           44 |     5219 | 2024-03-03 | BetBoom Team              | W   | 0.618      | 0.143        | 0.390 (0.034)    | -                | 0 (0.000) |    17.69 | Altekz, dupreeh, refrezh, roeJ, TMB            |
|           43 |     5227 | 2024-03-03 | kONO.ECF                  | W   | 0.617      | 0.143        | -                | 0.853 (0.075)    | -         |     9.94 | byr9, kensizor, munch, Polbandana, s4ltovsk1yy |
|           42 |     5253 | 2024-03-03 | Fnatic                    | L   | 0.616      | -            | -                | -                | -         |    -5.43 | afro, bodyy, KRIMZ, kyuubii, matys             |
|           41 |     5261 | 2024-03-03 | MOUZ NXT                  | L   | 0.615      | -            | -                | -                | -         |    -5.91 | Burmylov, Chr1zN, Neityu, PR, sirah            |
|           40 |     5273 | 2024-03-02 | brazylijski luz           | W   | 0.612      | -            | -                | -                | -         |     5.35 | POLO, Prism, Qlocuu, SaMey, virtuoso           |
|           39 |     5295 | 2024-03-02 | LEON Esports              | W   | 0.611      | -            | -                | -                | -         |     4.72 | eightz, facecrack, JIaYm, k0s, z1w0w           |
|           38 |     5374 | 2024-03-01 | BetBoom Team              | L   | 0.604      | -            | -                | -                | -         |    -1.59 | Altekz, dupreeh, refrezh, roeJ, TMB            |
|           37 |     5450 | 2024-02-28 | Fnatic                    | W   | 0.591      | 0.500        | 0.147 (0.044)    | 0.480 (0.142)    | -         |    13.40 | Altekz, dupreeh, refrezh, roeJ, TMB            |
|           36 |     5873 | 2024-02-21 | ex-Guild Eagles           | L   | 0.544      | -            | -                | -                | -         |    -7.74 | Altekz, dupreeh, refrezh, roeJ, TMB            |
|           35 |     5931 | 2024-02-20 | Pera Esports              | W   | 0.537      | -            | -                | -                | 1 (0.537) |     8.30 | Altekz, dupreeh, refrezh, roeJ, TMB            |
|           34 |     5997 | 2024-02-19 | OG                        | L   | 0.531      | -            | -                | -                | -         |    -3.41 | F1KU, HeavyGod, k1to, Nexius, regali           |
|           33 |     6012 | 2024-02-19 | HEROIC                    | L   | 0.530      | -            | -                | -                | -         |    -0.19 | kyxsan, NertZ, nicoodoz, sjuush, TeSeS         |
|           32 |     6503 | 2024-02-09 | Gaimin Gladiators         | W   | 0.462      | 0.371        | 0.092 (0.016)    | 0.727 (0.124)    | -         |    12.49 | Altekz, dupreeh, refrezh, roeJ, TMB            |
|           31 |     6537 | 2024-02-08 | TSM                       | W   | 0.455      | -            | -                | -                | -         |     4.37 | Altekz, dupreeh, refrezh, roeJ, TMB            |
|           30 |     6562 | 2024-02-07 | Into The Breach           | W   | 0.448      | -            | -                | -                | -         |     4.54 | Altekz, dupreeh, refrezh, roeJ, TMB            |
|           29 |     6585 | 2024-02-06 | Sangal Esports            | W   | 0.442      | 0.371        | 0.166 (0.027)    | 0.658 (0.108)    | -         |     9.99 | Ganginho, LNZ, sausol, xfl0ud, yxngstxr        |
|           28 |     6646 | 2024-02-05 | Gaimin Gladiators         | L   | 0.435      | -            | -                | -                | -         |    -1.78 | kraghen, Nodios, Patti, Queenix, salazar       |
|           27 |     6720 | 2024-02-03 | Sashi Esport              | L   | 0.424      | -            | -                | -                | -         |   -11.66 | b0RUP, Fessor, n1Xen, niko, nut nut            |
|           26 |     6736 | 2024-02-03 | Supermatch                | W   | 0.424      | -            | -                | -                | -         |     0.70 | filip, otto, P1ke, STYGGE, toshas              |
|           25 |     6793 | 2024-02-02 | Metizport                 | L   | 0.418      | -            | -                | -                | -         |    -5.63 | adamb, Jackinho, nilo, susp, ztr               |
|           24 |     6799 | 2024-02-02 | Sashi Esport              | W   | 0.417      | -            | -                | -                | -         |     1.56 | b0RUP, Fessor, n1Xen, niko, nut nut            |
|           23 |     6820 | 2024-02-02 | Maknitude                 | W   | 0.417      | -            | -                | -                | -         |     1.21 | Raven, sly, Smokey, Speedie, sSen              |
|           22 |     6848 | 2024-02-02 | SINNERS Esports           | W   | 0.415      | 0.371        | -                | 0.582 (0.090)    | -         |     8.28 | Altekz, dupreeh, refrezh, roeJ, TMB            |
|           21 |     6992 | 2024-01-30 | Entropiq                  | W   | 0.395      | -            | -                | -                | -         |     2.54 | c0llins, Marix, mwlky, Oxygen, tiziaN          |
|           20 |     7003 | 2024-01-29 | FORZE Esports             | L   | 0.392      | -            | -                | -                | -         |    -9.84 | gokushima, r3salt, shalfey, sstiNiX, tN1R      |
|           19 |     7044 | 2024-01-29 | ex-Turów Zgorzelec Esport | W   | 0.391      | -            | -                | -                | -         |     3.84 | byali, darko, kadziu, Markoś, xKacpersky       |
|           18 |     7289 | 2024-01-26 | Sprout                    | L   | 0.368      | -            | -                | -                | -         |   -10.07 | Anlelele, cej0t, raalz, Sdaim, sL1m3           |
|           17 |     7523 | 2024-01-21 | 3DMAX                     | W   | 0.336      | -            | -                | -                | -         |     5.63 | Altekz, dupreeh, refrezh, roeJ, TMB            |
|           16 |     7565 | 2024-01-20 | MOUZ                      | L   | 0.331      | -            | -                | -                | -         |    -0.03 | Altekz, dupreeh, refrezh, roeJ, TMB            |
|           15 |     7600 | 2024-01-20 | FORZE Esports             | W   | 0.329      | -            | -                | -                | -         |     2.78 | gokushima, kelieN, r3salt, shalfey, tN1R       |
|           14 |     7656 | 2024-01-19 | Team Spirit               | L   | 0.323      | -            | -                | -                | -         |    -0.04 | chopper, donk, magixx, sh1ro, zont1x           |
|           13 |     7720 | 2024-01-18 | Astralis                  | L   | 0.317      | -            | -                | -                | -         |    -0.15 | Altekz, dupreeh, refrezh, roeJ, TMB            |
|           12 |     7725 | 2024-01-18 | Entropiq                  | W   | 0.317      | -            | -                | -                | -         |     1.94 | c0llins, Marix, mwlky, Oxygen, tiziaN          |
|           11 |     7777 | 2024-01-17 | PARIVISION                | L   | 0.312      | -            | -                | -                | -         |    -4.85 | ArtFr0st, Jerry, Patsi, Qikert, X5G7V          |
|           10 |     7816 | 2024-01-17 | Nemiga Gaming             | W   | 0.311      | 0.143        | 0.358 (0.016)    | -                | -         |     8.44 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r           |
|            9 |     9151 | 2023-12-12 | ALTERNATE aTTaX           | W   | 0.070      | -            | -                | -                | -         |     1.45 | Altekz, nicoodoz, refrezh, roeJ, TMB           |
|            8 |     9156 | 2023-12-12 | BetBoom Team              | L   | 0.069      | -            | -                | -                | -         |    -0.11 | Altekz, nicoodoz, refrezh, roeJ, TMB           |
|            7 |     9191 | 2023-12-11 | 9Pandas                   | W   | 0.064      | -            | -                | -                | -         |     1.66 | clax, d1Ledez, glowiing, iDISBALANCE, seized   |
|            6 |     9206 | 2023-12-11 | GODSENT                   | W   | 0.062      | -            | -                | -                | -         |     0.39 | Altekz, nicoodoz, refrezh, roeJ, TMB           |
|            5 |     9262 | 2023-12-10 | TSM                       | W   | 0.055      | -            | -                | -                | -         |     0.31 | Altekz, nicoodoz, refrezh, roeJ, TMB           |
|            4 |     9309 | 2023-12-09 | Endpoint                  | W   | 0.049      | -            | -                | -                | -         |     0.86 | AZUWU, HeavyGod, MiGHTYMAX, sl3nd, Surreal     |
|            3 |     9398 | 2023-12-08 | GODSENT                   | L   | 0.042      | -            | -                | -                | -         |    -1.05 | bobeksde, eraa, Golden, Plopski, Ro1f          |
|            2 |     9584 | 2023-12-05 | FORZE Esports             | W   | 0.023      | -            | -                | -                | -         |     0.20 | gokushima, kelieN, r3salt, shalfey, tN1R       |
|            1 |     9605 | 2023-12-05 | IKLA                      | W   | 0.022      | -            | -                | -                | -         |     0.08 | forsyy, Kvem, MICHU, Topa, VLDN                |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($15,497.68)
- Divide that value by the 5th highest value among all rosters ($300,806.11)
- The final value (0.05) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-04-14 |      0.896 | $1,905.29      | $1,706.82       |
| 2024-03-18 |      0.715 | $11,000.00     | $7,865.00       |
| 2024-02-09 |      0.462 | $11,000.00     | $5,078.33       |
| 2023-12-13 |      0.078 | $1,000.00      | $77.52          |
| 2023-12-12 |      0.070 | $11,000.00     | $770.00         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
