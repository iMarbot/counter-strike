### Roster Details<br />
Team Name: ex-Guild Eagles<br />
Roster: gxx-, juanflatroo, rigoN, SENER1, sinnopsyy<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [67](../standings_global.md)<br />
Regional Rank: [46]( ../standings_europe.md)<br />
Final Rank Value:  962.1<br />
<br />
Final Rank Value (962.1) = Starting Rank Value (961.2) + Head To Head Adjustments (0.9)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.354[<sup>1</sup>](#table2)
- Bounty Collected: 0.397[<sup>2</sup>](#table1)
- Opponent Network: 0.181[<sup>2</sup>](#table1)
- LAN Wins: 0.173[<sup>2</sup>](#table1)

The average of these factors is 0.276<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 961.2
- 400 + ( ( 0.276 - 0.000 ) / ( 0.787 - 0.000 ) ) * 1600 = 961.2


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent           | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                        |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           64 |      268 | 2024-05-25 | Zero Tenacity      | L   | 1.000      | -            | -                | -                | -         |   -11.92 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy   |
|           63 |      294 | 2024-05-25 | ILLYRIANS          | W   | 1.000      | -            | -                | -                | 0 (0.000) |     7.58 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy   |
|           62 |      341 | 2024-05-24 | Zero Tenacity      | W   | 1.000      | 0.143        | 0.147 (0.021)    | 1.000 (0.143)    | 0 (0.000) |    19.57 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy   |
|           61 |      372 | 2024-05-24 | iNation            | W   | 1.000      | -            | -                | -                | 0 (0.000) |     7.80 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy   |
|           60 |     1023 | 2024-05-17 | Sashi Esport       | L   | 1.000      | -            | -                | -                | -         |    -5.14 | Cabbi, IceBerg, kwezz, Lucky, MistR           |
|           59 |     1805 | 2024-05-05 | 1win               | L   | 1.000      | -            | -                | -                | -         |   -13.50 | buster, Jyo, lattykk, neaLaN, Ryujin          |
|           58 |     2102 | 2024-04-29 | EYEBALLERS         | L   | 0.997      | -            | -                | -                | -         |   -17.16 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy   |
|           57 |     2212 | 2024-04-27 | Insilio            | L   | 0.983      | -            | -                | -                | -         |   -15.77 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy   |
|           56 |     2290 | 2024-04-26 | BLEED Esports      | L   | 0.977      | -            | -                | -                | -         |    -6.29 | CeRq, CYPHER, faveN, hampus, VLDN             |
|           55 |     2364 | 2024-04-25 | PARIVISION         | L   | 0.969      | -            | -                | -                | -         |   -19.22 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy   |
|           54 |     2436 | 2024-04-24 | Zero Tenacity      | W   | 0.962      | 0.435        | 0.147 (0.061)    | 1.000 (0.418)    | 0 (0.000) |    14.86 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy   |
|           53 |     2525 | 2024-04-22 | Sangal Esports     | W   | 0.948      | 0.435        | 0.166 (0.068)    | 0.658 (0.271)    | 0 (0.000) |    17.20 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr         |
|           52 |     2805 | 2024-04-18 | Sashi Esport       | L   | 0.924      | -            | -                | -                | -         |   -10.47 | Cabbi, IceBerg, kwezz, Lucky, MistR           |
|           51 |     2809 | 2024-04-18 | KOI                | W   | 0.924      | 0.143        | -                | 0.455 (0.060)    | 0 (0.000) |    17.80 | adamS, dav1g, JUST, mopoz, stadodo            |
|           50 |     2820 | 2024-04-18 | fragmatic          | W   | 0.923      | -            | -                | -                | 0 (0.000) |     2.70 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy   |
|           49 |     2836 | 2024-04-18 | AMKAL ESPORTS      | L   | 0.922      | -            | -                | -                | -         |    -7.47 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy   |
|           48 |     2872 | 2024-04-17 | Heimo Esports      | W   | 0.918      | -            | -                | -                | -         |     6.16 | arvid, japE, oopee, Welho, ykis               |
|           47 |     2980 | 2024-04-16 | Sashi Esport       | W   | 0.909      | 0.384        | 0.154 (0.054)    | 1.000 (0.349)    | -         |    18.38 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy   |
|           46 |     3334 | 2024-04-09 | Metizport          | W   | 0.863      | 0.384        | 0.088 (0.029)    | 0.698 (0.231)    | -         |    18.48 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy   |
|           45 |     3642 | 2024-04-03 | AMKAL ESPORTS      | L   | 0.823      | -            | -                | -                | -         |    -6.73 | Forester, ICY, Krad, Sdaim, TRAVIS            |
|           44 |     3679 | 2024-04-02 | Insilio            | L   | 0.817      | -            | -                | -                | -         |   -12.24 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy   |
|           43 |     3692 | 2024-04-02 | AMKAL ESPORTS      | W   | 0.816      | 0.143        | 0.146 (0.017)    | 0.565 (0.066)    | -         |    18.84 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy   |
|           42 |     3703 | 2024-04-02 | 500                | L   | 0.815      | -            | -                | -                | -         |   -14.95 | dennyslaw, Grashog, Rainwaker, REDSTAR, SHiPZ |
|           41 |     3713 | 2024-04-01 | 500                | W   | 0.811      | 0.384        | -                | 0.479 (0.149)    | -         |    10.69 | dennyslaw, Grashog, Rainwaker, REDSTAR, SHiPZ |
|           40 |     3890 | 2024-03-27 | ALTERNATE aTTaX    | L   | 0.777      | -            | -                | -                | -         |   -12.31 | ArroW, awzek, FreeZe, hyped, skyye            |
|           39 |     3904 | 2024-03-27 | MANGANES           | W   | 0.777      | -            | -                | -                | -         |     2.12 | CamZ, DrqkoN, nonick, Polox, sOSEIREy         |
|           38 |     3967 | 2024-03-26 | Sashi Esport       | W   | 0.771      | -            | -                | -                | -         |     7.61 | b0RUP, niko, nut nut, PR1mE, sL1m3            |
|           37 |     4145 | 2024-03-22 | VP.Prodigy         | L   | 0.742      | -            | -                | -                | -         |   -14.37 | dwushka, KusMe, shady, Something, xdENiSZERA  |
|           36 |     5175 | 2024-03-04 | GUN5 Esports       | L   | 0.625      | -            | -                | -                | -         |   -16.83 | FinigaN, lov1kus, supra, tried, xiELO         |
|           35 |     5268 | 2024-03-02 | RUSH B             | L   | 0.612      | -            | -                | -                | -         |   -14.91 | executoR, kinqie, Kiro, nota, tex1y           |
|           34 |     5311 | 2024-03-02 | Astra Gaming       | W   | 0.611      | -            | -                | -                | -         |     0.68 | AquaRS, Fak1E, Meepff, s1nhron, SEMSYS        |
|           33 |     5510 | 2024-02-27 | Croatia            | L   | 0.584      | -            | -                | -                | -         |   -17.15 | Consume, Maki, rbfurious, ROGA, Šego          |
|           32 |     5517 | 2024-02-27 | Metizport          | W   | 0.584      | 0.143        | 0.088 (0.007)    | -                | -         |     9.40 | adamb, Jackinho, nilo, susp, ztr              |
|           31 |     5554 | 2024-02-26 | Preasy Esport      | W   | 0.578      | 0.143        | -                | 0.705 (0.058)    | -         |     5.41 | beccie, Equip, Griller, Skejs, VireZ          |
|           30 |     5727 | 2024-02-24 | GamerLegion        | L   | 0.562      | -            | -                | -                | -         |    -3.25 | acoR, isak, Keoz, Snax, volt                  |
|           29 |     5777 | 2024-02-23 | BetBoom Team       | W   | 0.556      | 0.143        | 0.390 (0.031)    | -                | 1 (0.556) |    15.86 | danistzz, KaiR0N-, nafany, s1ren, zorte       |
|           28 |     5827 | 2024-02-22 | Gaimin Gladiators  | L   | 0.550      | -            | -                | -                | -         |    -3.12 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy   |
|           27 |     5873 | 2024-02-21 | ex-Preasy Esport   | W   | 0.544      | 0.143        | 0.052 (0.004)    | -                | 1 (0.544) |     7.74 | Altekz, dupreeh, refrezh, roeJ, TMB           |
|           26 |     5945 | 2024-02-20 | Nexus Gaming       | W   | 0.536      | 0.143        | -                | 0.857 (0.066)    | 1 (0.536) |     6.60 | BTN, ERSIN, ragga, s0und, XELLOW              |
|           25 |     6004 | 2024-02-19 | ENCE               | L   | 0.530      | -            | -                | -                | -         |    -1.07 | dycha, gla1ve, Goofy, hades, Kylar            |
|           24 |     6024 | 2024-02-19 | MOUZ               | L   | 0.529      | -            | -                | -                | -         |    -0.07 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy   |
|           23 |     6509 | 2024-02-08 | Insilio            | L   | 0.458      | -            | -                | -                | -         |    -7.75 | faydett, FpSSS, Pipw, Polt, sugaR             |
|           22 |     6525 | 2024-02-08 | RUBY               | L   | 0.457      | -            | -                | -                | -         |    -8.13 | dekz, Kaide, mo0n, Sowalio, w1nt3r            |
|           21 |     7302 | 2024-01-25 | Pera Esports       | L   | 0.364      | -            | -                | -                | -         |    -6.57 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy   |
|           20 |     7354 | 2024-01-24 | ALTERNATE aTTaX    | W   | 0.357      | -            | -                | -                | -         |     5.91 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy   |
|           19 |     7418 | 2024-01-23 | Team Sampi         | W   | 0.351      | -            | -                | -                | -         |     5.12 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy   |
|           18 |     7422 | 2024-01-23 | ALTERNATE aTTaX    | W   | 0.350      | -            | -                | -                | -         |     6.17 | awzek, FreeZe, Goody, PANIX, PerX             |
|           17 |     7450 | 2024-01-22 | Pera Esports       | L   | 0.344      | -            | -                | -                | -         |    -6.38 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy   |
|           16 |     7468 | 2024-01-22 | Viperio            | W   | 0.344      | -            | -                | -                | -         |     1.04 | mAnGo, MMS, pandi7o, ReegaN, zodi             |
|           15 |     7477 | 2024-01-22 | Rebels Gaming      | W   | 0.344      | -            | -                | -                | -         |     7.29 | casey, Flayy, kisserek, olimp, sNx            |
|           14 |     7742 | 2024-01-18 | Sprout             | W   | 0.316      | -            | -                | -                | -         |     1.05 | Anlelele, cej0t, raalz, sL1m3, Zyphon         |
|           13 |     7759 | 2024-01-17 | Into The Breach    | W   | 0.312      | -            | -                | -                | -         |     2.10 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy   |
|           12 |     7763 | 2024-01-17 | Capcarap           | W   | 0.312      | -            | -                | -                | -         |     0.73 | DARIEN, Maki, rbfurious, simon71, zeins       |
|           11 |     7770 | 2024-01-17 | Rebels Gaming      | W   | 0.312      | -            | -                | -                | -         |     6.83 | casey, Flayy, kisserek, olimp, sNx            |
|           10 |     7810 | 2024-01-17 | ARROW              | W   | 0.311      | -            | -                | -                | -         |     1.91 | Kre1N, Orbit, S1M, Tionix, Twiksar            |
|            9 |     9110 | 2023-12-13 | Recon 6            | L   | 0.076      | -            | -                | -                | -         |    -2.24 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy   |
|            8 |     9145 | 2023-12-12 | Aurora Gaming      | L   | 0.071      | -            | -                | -                | -         |    -0.11 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy   |
|            7 |     9204 | 2023-12-11 | ex-Anonymo Esports | W   | 0.062      | -            | -                | -                | -         |     0.36 | lunAtic, reiko, SaMey, Sobol, virtuoso        |
|            6 |     9444 | 2023-12-07 | Aurora Gaming      | L   | 0.037      | -            | -                | -                | -         |    -0.06 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy   |
|            5 |     9488 | 2023-12-06 | 9Pandas            | W   | 0.031      | -            | -                | -                | -         |     0.76 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|            4 |     9514 | 2023-12-06 | G2 Esports         | W   | 0.030      | 0.589        | 0.468 (0.008)    | -                | -         |     0.92 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy   |
|            3 |     9588 | 2023-12-05 | ex-Anonymo Esports | W   | 0.023      | -            | -                | -                | -         |     0.14 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy   |
|            2 |     9626 | 2023-12-04 | ALTERNATE aTTaX    | W   | 0.015      | -            | -                | -                | -         |     0.29 | awzek, FreeZe, PANIX, PerX, Spiidi            |
|            1 |     9644 | 2023-12-03 | BIG                | L   | 0.011      | -            | -                | -                | -         |    -0.02 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy   |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($4,469.46)
- Divide that value by the 5th highest value among all rosters ($300,806.11)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-05-24 |      1.000 | $2,161.61      | $2,161.61       |
| 2024-05-18 |      1.000 | $1,000.00      | $1,000.00       |
| 2023-12-13 |      0.078 | $1,000.00      | $77.52          |
| 2023-12-13 |      0.076 | $3,750.00      | $286.46         |
| 2023-12-07 |      0.038 | $25,000.00     | $943.87         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
