### Roster Details<br />
Team Name: ex-Preasy Esport<br />
Roster: Altekz, kristou, refrezh, roeJ, TMB<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [62](../standings_global.md)<br />
Regional Rank: [43]( ../standings_europe.md)<br />
Final Rank Value:  989.6<br />
<br />
Final Rank Value (989.6) = Starting Rank Value (911.0) + Head To Head Adjustments (78.7)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.437[<sup>1</sup>](#table2)
- Bounty Collected: 0.369[<sup>2</sup>](#table1)
- Opponent Network: 0.141[<sup>2</sup>](#table1)
- LAN Wins: 0.057[<sup>2</sup>](#table1)

The average of these factors is 0.251<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 911.0
- 400 + ( ( 0.251 - 0.000 ) / ( 0.786 - 0.000 ) ) * 1600 = 911.0


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
|           57 |     3045 | 2024-04-13 | 3DMAX                     | L   | 0.889      | -            | -                | -                | -         |   -16.24 | Altekz, kristou, refrezh, roeJ, TMB            |
|           56 |     3356 | 2024-04-07 | Zero Tenacity             | W   | 0.848      | 0.143        | 0.147 (0.018)    | 1.000 (0.121)    | 0 (0.000) |    13.60 | Altekz, kristou, refrezh, roeJ, TMB            |
|           55 |     3860 | 2024-03-26 | Raptors Esports Club      | L   | 0.771      | -            | -                | -                | -         |   -17.25 | BehinDx, Karrar, moz, PrimeOPI, wfn            |
|           54 |     4040 | 2024-03-22 | FORZE Esports             | L   | 0.743      | -            | -                | -                | -         |   -10.72 | gokushima, r3salt, SELLTER, shalfey, tN1R      |
|           53 |     4224 | 2024-03-18 | Team Sampi                | W   | 0.715      | 0.371        | 0.039 (0.010)    | 0.665 (0.176)    | 0 (0.000) |     9.97 | fino, manguss, sAvana1, The eLiVe, ZEDKO       |
|           52 |     4333 | 2024-03-16 | Passion UA                | W   | 0.703      | 0.371        | 0.057 (0.015)    | 1.000 (0.260)    | 0 (0.000) |     9.53 | fear, jackasmo, jambo, s-chilla, zeRRoFIX      |
|           51 |     4450 | 2024-03-14 | Entropiq                  | W   | 0.688      | -            | -                | -                | 0 (0.000) |     4.11 | Altekz, kristou, refrezh, roeJ, TMB            |
|           50 |     4600 | 2024-03-11 | Metizport                 | L   | 0.671      | -            | -                | -                | -         |    -8.85 | adamb, Jackinho, nilo, susp, ztr               |
|           49 |     4622 | 2024-03-11 | HEROIC                    | L   | 0.670      | -            | -                | -                | -         |    -0.39 | Altekz, dupreeh, refrezh, roeJ, TMB            |
|           48 |     4631 | 2024-03-11 | Permitta Esports          | W   | 0.669      | 0.371        | 0.029 (0.007)    | 1.000 (0.248)    | 0 (0.000) |     9.74 | Altekz, kristou, refrezh, roeJ, TMB            |
|           47 |     4740 | 2024-03-09 | ex-K10                    | W   | 0.655      | 0.371        | -                | 0.382 (0.093)    | 0 (0.000) |     5.48 | Altekz, kristou, refrezh, roeJ, TMB            |
|           46 |     4828 | 2024-03-07 | Team Secret               | W   | 0.642      | -            | -                | -                | 0 (0.000) |     2.43 | anarkez, innocent, Kind0, Maze, Tauson         |
|           45 |     5064 | 2024-03-03 | Gaimin Gladiators         | W   | 0.618      | 0.143        | 0.092 (0.008)    | -                | 0 (0.000) |    16.34 | kraghen, Nodios, Patti, Queenix, salazar       |
|           44 |     5073 | 2024-03-03 | BetBoom Team              | W   | 0.618      | 0.143        | 0.390 (0.034)    | -                | 0 (0.000) |    17.70 | Altekz, dupreeh, refrezh, roeJ, TMB            |
|           43 |     5081 | 2024-03-03 | kONO.ECF                  | W   | 0.617      | 0.143        | -                | 0.778 (0.069)    | -         |     9.63 | byr9, kensizor, munch, Polbandana, s4ltovsk1yy |
|           42 |     5105 | 2024-03-03 | Fnatic                    | L   | 0.616      | -            | -                | -                | -         |    -5.37 | afro, bodyy, KRIMZ, kyuubii, matys             |
|           41 |     5113 | 2024-03-03 | MOUZ NXT                  | L   | 0.615      | -            | -                | -                | -         |    -6.17 | Burmylov, Chr1zN, Neityu, PR, sirah            |
|           40 |     5125 | 2024-03-02 | brazylijski luz           | W   | 0.612      | -            | -                | -                | -         |     5.28 | POLO, Prism, Qlocuu, SaMey, virtuoso           |
|           39 |     5147 | 2024-03-02 | LEON Esports              | W   | 0.611      | -            | -                | -                | -         |     4.75 | eightz, facecrack, JIaYm, k0s, z1w0w           |
|           38 |     5225 | 2024-03-01 | BetBoom Team              | L   | 0.604      | -            | -                | -                | -         |    -1.58 | Altekz, dupreeh, refrezh, roeJ, TMB            |
|           37 |     5299 | 2024-02-28 | Fnatic                    | W   | 0.591      | 0.500        | 0.147 (0.044)    | 0.480 (0.142)    | -         |    13.45 | Altekz, dupreeh, refrezh, roeJ, TMB            |
|           36 |     5710 | 2024-02-21 | ex-Guild Eagles           | L   | 0.544      | -            | -                | -                | -         |    -7.82 | Altekz, dupreeh, refrezh, roeJ, TMB            |
|           35 |     5763 | 2024-02-20 | Pera Esports              | W   | 0.537      | -            | -                | -                | 1 (0.537) |     8.37 | Altekz, dupreeh, refrezh, roeJ, TMB            |
|           34 |     5826 | 2024-02-19 | OG                        | L   | 0.531      | -            | -                | -                | -         |    -3.33 | F1KU, HeavyGod, k1to, Nexius, regali           |
|           33 |     5840 | 2024-02-19 | HEROIC                    | L   | 0.530      | -            | -                | -                | -         |    -0.19 | kyxsan, NertZ, nicoodoz, sjuush, TeSeS         |
|           32 |     6315 | 2024-02-09 | Gaimin Gladiators         | W   | 0.462      | 0.371        | 0.092 (0.016)    | 0.711 (0.122)    | -         |    12.51 | Altekz, dupreeh, refrezh, roeJ, TMB            |
|           31 |     6349 | 2024-02-08 | TSM                       | W   | 0.455      | -            | -                | -                | -         |     4.11 | Altekz, dupreeh, refrezh, roeJ, TMB            |
|           30 |     6368 | 2024-02-07 | Into The Breach           | W   | 0.448      | -            | -                | -                | -         |     4.58 | Altekz, dupreeh, refrezh, roeJ, TMB            |
|           29 |     6389 | 2024-02-06 | Sangal Esports            | W   | 0.442      | 0.371        | 0.166 (0.027)    | 0.577 (0.095)    | -         |     9.65 | Ganginho, LNZ, sausol, xfl0ud, yxngstxr        |
|           28 |     6444 | 2024-02-05 | Gaimin Gladiators         | L   | 0.435      | -            | -                | -                | -         |    -1.77 | kraghen, Nodios, Patti, Queenix, salazar       |
|           27 |     6517 | 2024-02-03 | Sashi Esport              | L   | 0.424      | -            | -                | -                | -         |   -11.64 | b0RUP, Fessor, n1Xen, niko, nut nut            |
|           26 |     6533 | 2024-02-03 | Supermatch                | W   | 0.424      | -            | -                | -                | -         |     0.72 | filip, otto, P1ke, STYGGE, toshas              |
|           25 |     6590 | 2024-02-02 | Metizport                 | L   | 0.418      | -            | -                | -                | -         |    -5.61 | adamb, Jackinho, nilo, susp, ztr               |
|           24 |     6596 | 2024-02-02 | Sashi Esport              | W   | 0.417      | -            | -                | -                | -         |     1.58 | b0RUP, Fessor, n1Xen, niko, nut nut            |
|           23 |     6616 | 2024-02-02 | Maknitude                 | W   | 0.417      | -            | -                | -                | -         |     1.23 | Raven, sly, Smokey, Speedie, sSen              |
|           22 |     6643 | 2024-02-02 | SINNERS Esports           | W   | 0.415      | 0.371        | -                | 0.560 (0.086)    | -         |     7.93 | Altekz, dupreeh, refrezh, roeJ, TMB            |
|           21 |     6776 | 2024-01-30 | Entropiq                  | W   | 0.395      | -            | -                | -                | -         |     2.51 | c0llins, Marix, mwlky, Oxygen, tiziaN          |
|           20 |     6787 | 2024-01-29 | FORZE Esports             | L   | 0.392      | -            | -                | -                | -         |    -9.40 | gokushima, r3salt, shalfey, sstiNiX, tN1R      |
|           19 |     6828 | 2024-01-29 | ex-Turów Zgorzelec Esport | W   | 0.391      | -            | -                | -                | -         |     3.60 | byali, darko, kadziu, Markoś, xKacpersky       |
|           18 |     7063 | 2024-01-26 | Sprout                    | L   | 0.368      | -            | -                | -                | -         |   -10.07 | Anlelele, cej0t, raalz, Sdaim, sL1m3           |
|           17 |     7280 | 2024-01-21 | 3DMAX                     | W   | 0.336      | -            | -                | -                | -         |     5.67 | Altekz, dupreeh, refrezh, roeJ, TMB            |
|           16 |     7322 | 2024-01-20 | MOUZ                      | L   | 0.331      | -            | -                | -                | -         |    -0.03 | Altekz, dupreeh, refrezh, roeJ, TMB            |
|           15 |     7356 | 2024-01-20 | FORZE Esports             | W   | 0.329      | -            | -                | -                | -         |     2.40 | gokushima, kelieN, r3salt, shalfey, tN1R       |
|           14 |     7410 | 2024-01-19 | Team Spirit               | L   | 0.323      | -            | -                | -                | -         |    -0.04 | chopper, donk, magixx, sh1ro, zont1x           |
|           13 |     7472 | 2024-01-18 | Astralis                  | L   | 0.317      | -            | -                | -                | -         |    -0.14 | Altekz, dupreeh, refrezh, roeJ, TMB            |
|           12 |     7476 | 2024-01-18 | Entropiq                  | W   | 0.317      | -            | -                | -                | -         |     1.96 | c0llins, Marix, mwlky, Oxygen, tiziaN          |
|           11 |     7528 | 2024-01-17 | PARIVISION                | L   | 0.312      | -            | -                | -                | -         |    -4.82 | ArtFr0st, Jerry, Patsi, Qikert, X5G7V          |
|           10 |     7567 | 2024-01-17 | Nemiga Gaming             | W   | 0.311      | 0.143        | 0.366 (0.016)    | -                | -         |     8.46 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r           |
|            9 |     8887 | 2023-12-12 | ALTERNATE aTTaX           | W   | 0.070      | -            | -                | -                | -         |     0.56 | Altekz, nicoodoz, refrezh, roeJ, TMB           |
|            8 |     8892 | 2023-12-12 | BetBoom Team              | L   | 0.069      | -            | -                | -                | -         |    -0.11 | Altekz, nicoodoz, refrezh, roeJ, TMB           |
|            7 |     8925 | 2023-12-11 | 9Pandas                   | W   | 0.064      | -            | -                | -                | -         |     1.64 | clax, d1Ledez, glowiing, iDISBALANCE, seized   |
|            6 |     8940 | 2023-12-11 | GODSENT                   | W   | 0.062      | -            | -                | -                | -         |     0.39 | Altekz, nicoodoz, refrezh, roeJ, TMB           |
|            5 |     8996 | 2023-12-10 | TSM                       | W   | 0.055      | -            | -                | -                | -         |     0.31 | Altekz, nicoodoz, refrezh, roeJ, TMB           |
|            4 |     9042 | 2023-12-09 | Endpoint                  | W   | 0.049      | -            | -                | -                | -         |     0.85 | AZUWU, HeavyGod, MiGHTYMAX, sl3nd, Surreal     |
|            3 |     9128 | 2023-12-08 | GODSENT                   | L   | 0.042      | -            | -                | -                | -         |    -1.05 | bobeksde, eraa, Golden, Plopski, Ro1f          |
|            2 |     9302 | 2023-12-05 | FORZE Esports             | W   | 0.023      | -            | -                | -                | -         |     0.17 | gokushima, kelieN, r3salt, shalfey, tN1R       |
|            1 |     9323 | 2023-12-05 | IKLA                      | W   | 0.022      | -            | -                | -                | -         |     0.08 | forsyy, Kvem, MICHU, Topa, VLDN                |

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
