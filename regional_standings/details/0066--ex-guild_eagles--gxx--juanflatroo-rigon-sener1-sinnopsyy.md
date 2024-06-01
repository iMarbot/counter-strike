### Roster Details<br />
Team Name: ex-Guild Eagles<br />
Roster: gxx-, juanflatroo, rigoN, SENER1, sinnopsyy<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [66](../standings_global.md)<br />
Regional Rank: [46]( ../standings_europe.md)<br />
Final Rank Value:  958.4<br />
<br />
Final Rank Value (958.4) = Starting Rank Value (960.8) + Head To Head Adjustments (-2.4)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.354[<sup>1</sup>](#table2)
- Bounty Collected: 0.398[<sup>2</sup>](#table1)
- Opponent Network: 0.177[<sup>2</sup>](#table1)
- LAN Wins: 0.173[<sup>2</sup>](#table1)

The average of these factors is 0.275<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 960.8
- 400 + ( ( 0.275 - 0.000 ) / ( 0.786 - 0.000 ) ) * 1600 = 960.8


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
|           64 |      260 | 2024-05-25 | Zero Tenacity      | L   | 1.000      | -            | -                | -                | -         |   -11.98 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy   |
|           63 |      286 | 2024-05-25 | ILLYRIANS          | W   | 1.000      | -            | -                | -                | 0 (0.000) |     7.59 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy   |
|           62 |      332 | 2024-05-24 | Zero Tenacity      | W   | 1.000      | 0.143        | 0.147 (0.021)    | 1.000 (0.143)    | 0 (0.000) |    19.51 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy   |
|           61 |      363 | 2024-05-24 | iNation            | W   | 1.000      | -            | -                | -                | 0 (0.000) |     7.86 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy   |
|           60 |     1011 | 2024-05-17 | Sashi Esport       | L   | 1.000      | -            | -                | -                | -         |    -5.08 | Cabbi, IceBerg, kwezz, Lucky, MistR           |
|           59 |     1782 | 2024-05-05 | 1win               | L   | 1.000      | -            | -                | -                | -         |   -13.16 | buster, Jyo, lattykk, neaLaN, Ryujin          |
|           58 |     2067 | 2024-04-29 | EYEBALLERS         | L   | 0.997      | -            | -                | -                | -         |   -16.31 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy   |
|           57 |     2177 | 2024-04-27 | Insilio            | L   | 0.983      | -            | -                | -                | -         |   -15.60 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy   |
|           56 |     2254 | 2024-04-26 | BLEED Esports      | L   | 0.977      | -            | -                | -                | -         |    -6.08 | CeRq, CYPHER, faveN, hampus, VLDN             |
|           55 |     2323 | 2024-04-25 | PARIVISION         | L   | 0.969      | -            | -                | -                | -         |   -18.80 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy   |
|           54 |     2391 | 2024-04-24 | Zero Tenacity      | W   | 0.962      | 0.435        | 0.147 (0.061)    | 1.000 (0.418)    | 0 (0.000) |    15.33 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy   |
|           53 |     2472 | 2024-04-22 | Sangal Esports     | W   | 0.948      | 0.435        | 0.166 (0.068)    | 0.577 (0.238)    | 0 (0.000) |    15.74 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr         |
|           52 |     2749 | 2024-04-18 | Sashi Esport       | L   | 0.924      | -            | -                | -                | -         |   -10.20 | Cabbi, IceBerg, kwezz, Lucky, MistR           |
|           51 |     2753 | 2024-04-18 | KOI                | W   | 0.924      | 0.143        | -                | 0.430 (0.057)    | 0 (0.000) |    17.55 | adamS, dav1g, JUST, mopoz, stadodo            |
|           50 |     2764 | 2024-04-18 | fragmatic          | W   | 0.923      | -            | -                | -                | 0 (0.000) |     2.74 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy   |
|           49 |     2780 | 2024-04-18 | AMKAL ESPORTS      | L   | 0.922      | -            | -                | -                | -         |    -7.34 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy   |
|           48 |     2815 | 2024-04-17 | Heimo Esports      | W   | 0.918      | -            | -                | -                | -         |     6.27 | arvid, japE, oopee, Welho, ykis               |
|           47 |     2919 | 2024-04-16 | Sashi Esport       | W   | 0.909      | 0.384        | 0.172 (0.060)    | 1.000 (0.349)    | -         |    18.73 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy   |
|           46 |     3255 | 2024-04-09 | Metizport          | W   | 0.863      | 0.384        | 0.088 (0.029)    | 0.698 (0.231)    | -         |    18.96 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy   |
|           45 |     3555 | 2024-04-03 | AMKAL ESPORTS      | L   | 0.823      | -            | -                | -                | -         |    -6.61 | Forester, ICY, Krad, Sdaim, TRAVIS            |
|           44 |     3590 | 2024-04-02 | Insilio            | L   | 0.817      | -            | -                | -                | -         |   -11.96 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy   |
|           43 |     3602 | 2024-04-02 | AMKAL ESPORTS      | W   | 0.816      | 0.143        | 0.146 (0.017)    | 0.565 (0.066)    | -         |    18.96 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy   |
|           42 |     3613 | 2024-04-02 | 500                | L   | 0.815      | -            | -                | -                | -         |   -14.90 | dennyslaw, Grashog, Rainwaker, REDSTAR, SHiPZ |
|           41 |     3623 | 2024-04-01 | 500                | W   | 0.811      | 0.384        | -                | 0.479 (0.149)    | -         |    10.74 | dennyslaw, Grashog, Rainwaker, REDSTAR, SHiPZ |
|           40 |     3797 | 2024-03-27 | ALTERNATE aTTaX    | L   | 0.777      | -            | -                | -                | -         |   -12.15 | ArroW, awzek, FreeZe, hyped, skyye            |
|           39 |     3811 | 2024-03-27 | MANGANES           | W   | 0.777      | -            | -                | -                | -         |     2.20 | CamZ, DrqkoN, nonick, Polox, sOSEIREy         |
|           38 |     3870 | 2024-03-26 | Sashi Esport       | W   | 0.771      | -            | -                | -                | -         |     7.69 | b0RUP, niko, nut nut, PR1mE, sL1m3            |
|           37 |     4047 | 2024-03-22 | VP.Prodigy         | L   | 0.742      | -            | -                | -                | -         |   -14.62 | dwushka, KusMe, shady, Something, xdENiSZERA  |
|           36 |     5029 | 2024-03-04 | GUN5 Esports       | L   | 0.625      | -            | -                | -                | -         |   -16.85 | FinigaN, lov1kus, supra, tried, xiELO         |
|           35 |     5120 | 2024-03-02 | RUSH B             | L   | 0.612      | -            | -                | -                | -         |   -14.79 | executoR, kinqie, Kiro, nota, tex1y           |
|           34 |     5163 | 2024-03-02 | Astra Gaming       | W   | 0.611      | -            | -                | -                | -         |     0.70 | AquaRS, Fak1E, Meepff, s1nhron, SEMSYS        |
|           33 |     5357 | 2024-02-27 | Croatia            | L   | 0.584      | -            | -                | -                | -         |   -17.11 | Consume, Maki, rbfurious, ROGA, Šego          |
|           32 |     5364 | 2024-02-27 | Metizport          | W   | 0.584      | 0.143        | 0.088 (0.007)    | 0.698 (0.058)    | -         |     9.49 | adamb, Jackinho, nilo, susp, ztr              |
|           31 |     5397 | 2024-02-26 | Preasy Esport      | W   | 0.578      | -            | -                | -                | -         |     5.38 | beccie, Equip, Griller, Skejs, VireZ          |
|           30 |     5567 | 2024-02-24 | GamerLegion        | L   | 0.562      | -            | -                | -                | -         |    -3.14 | acoR, isak, Keoz, Snax, volt                  |
|           29 |     5617 | 2024-02-23 | BetBoom Team       | W   | 0.556      | 0.143        | 0.390 (0.031)    | -                | 1 (0.556) |    15.90 | danistzz, KaiR0N-, nafany, s1ren, zorte       |
|           28 |     5666 | 2024-02-22 | Gaimin Gladiators  | L   | 0.550      | -            | -                | -                | -         |    -3.05 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy   |
|           27 |     5710 | 2024-02-21 | ex-Preasy Esport   | W   | 0.544      | 0.143        | 0.052 (0.004)    | -                | 1 (0.544) |     7.82 | Altekz, dupreeh, refrezh, roeJ, TMB           |
|           26 |     5776 | 2024-02-20 | Nexus Gaming       | W   | 0.536      | 0.143        | -                | 0.825 (0.063)    | 1 (0.536) |     7.17 | BTN, ERSIN, ragga, s0und, XELLOW              |
|           25 |     5833 | 2024-02-19 | ENCE               | L   | 0.530      | -            | -                | -                | -         |    -1.04 | dycha, gla1ve, Goofy, hades, Kylar            |
|           24 |     5852 | 2024-02-19 | MOUZ               | L   | 0.529      | -            | -                | -                | -         |    -0.06 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy   |
|           23 |     6321 | 2024-02-08 | Insilio            | L   | 0.458      | -            | -                | -                | -         |    -7.55 | faydett, FpSSS, Pipw, Polt, sugaR             |
|           22 |     6337 | 2024-02-08 | RUBY               | L   | 0.457      | -            | -                | -                | -         |    -8.01 | dekz, Kaide, mo0n, Sowalio, w1nt3r            |
|           21 |     7076 | 2024-01-25 | Pera Esports       | L   | 0.364      | -            | -                | -                | -         |    -6.44 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy   |
|           20 |     7121 | 2024-01-24 | ALTERNATE aTTaX    | W   | 0.357      | -            | -                | -                | -         |     2.22 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy   |
|           19 |     7180 | 2024-01-23 | Team Sampi         | W   | 0.351      | -            | -                | -                | -         |     5.11 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy   |
|           18 |     7183 | 2024-01-23 | ALTERNATE aTTaX    | W   | 0.350      | -            | -                | -                | -         |     2.30 | awzek, FreeZe, Goody, PANIX, PerX             |
|           17 |     7209 | 2024-01-22 | Pera Esports       | L   | 0.344      | -            | -                | -                | -         |    -6.32 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy   |
|           16 |     7225 | 2024-01-22 | Viperio            | W   | 0.344      | -            | -                | -                | -         |     1.03 | mAnGo, MMS, pandi7o, ReegaN, zodi             |
|           15 |     7234 | 2024-01-22 | Rebels Gaming      | W   | 0.344      | -            | -                | -                | -         |     7.29 | casey, Flayy, kisserek, olimp, sNx            |
|           14 |     7493 | 2024-01-18 | Sprout             | W   | 0.316      | -            | -                | -                | -         |     1.04 | Anlelele, cej0t, raalz, sL1m3, Zyphon         |
|           13 |     7510 | 2024-01-17 | Into The Breach    | W   | 0.312      | -            | -                | -                | -         |     2.10 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy   |
|           12 |     7514 | 2024-01-17 | Capcarap           | W   | 0.312      | -            | -                | -                | -         |     0.74 | DARIEN, Maki, rbfurious, simon71, zeins       |
|           11 |     7521 | 2024-01-17 | Rebels Gaming      | W   | 0.312      | -            | -                | -                | -         |     6.83 | casey, Flayy, kisserek, olimp, sNx            |
|           10 |     7561 | 2024-01-17 | ARROW              | W   | 0.311      | -            | -                | -                | -         |     1.90 | Kre1N, Orbit, S1M, Tionix, Twiksar            |
|            9 |     8846 | 2023-12-13 | Recon 6            | L   | 0.076      | -            | -                | -                | -         |    -2.24 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy   |
|            8 |     8881 | 2023-12-12 | Aurora Gaming      | L   | 0.071      | -            | -                | -                | -         |    -0.11 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy   |
|            7 |     8938 | 2023-12-11 | ex-Anonymo Esports | W   | 0.062      | -            | -                | -                | -         |     0.36 | lunAtic, reiko, SaMey, Sobol, virtuoso        |
|            6 |     9171 | 2023-12-07 | Aurora Gaming      | L   | 0.037      | -            | -                | -                | -         |    -0.06 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy   |
|            5 |     9208 | 2023-12-06 | 9Pandas            | W   | 0.031      | -            | -                | -                | -         |     0.75 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|            4 |     9233 | 2023-12-06 | G2 Esports         | W   | 0.030      | 0.589        | 0.468 (0.008)    | -                | -         |     0.92 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy   |
|            3 |     9306 | 2023-12-05 | ex-Anonymo Esports | W   | 0.023      | -            | -                | -                | -         |     0.14 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy   |
|            2 |     9344 | 2023-12-04 | ALTERNATE aTTaX    | W   | 0.015      | -            | -                | -                | -         |     0.10 | awzek, FreeZe, PANIX, PerX, Spiidi            |
|            1 |     9362 | 2023-12-03 | BIG                | L   | 0.011      | -            | -                | -                | -         |    -0.02 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy   |

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
