### Roster Details<br />
Team Name: Gaimin Gladiators<br />
Roster: kraghen, Nodios, Patti, Queenix, salazar<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [33](../standings_global.md)<br />
Regional Rank: [25]( ../standings_europe.md)<br />
Final Rank Value:  1249.1<br />
<br />
Final Rank Value (1249.1) = Starting Rank Value (1462.4) + Head To Head Adjustments (-213.3)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.584[<sup>1</sup>](#table2)
- Bounty Collected: 0.576[<sup>2</sup>](#table1)
- Opponent Network: 0.353[<sup>2</sup>](#table1)
- LAN Wins: 0.628[<sup>2</sup>](#table1)

The average of these factors is 0.536<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1462.4
- 400 + ( ( 0.536 - 0.000 ) / ( 0.806 - 0.000 ) ) * 1600 = 1462.4


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent                     | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                        |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           93 |       10 | 2024-05-05 | Sashi Esport                 | W   | 1.000      | 0.143        | 0.193 (0.028)    | -                | 0 (0.000) |    18.15 | kraghen, Nodios, Patti, Queenix, salazar      |
|           92 |       21 | 2024-05-05 | Kronjyllands Esport          | W   | 1.000      | -            | -                | -                | 0 (0.000) |     0.50 | kraghen, Nodios, Patti, Queenix, salazar      |
|           91 |       29 | 2024-05-05 | Esport Harte                 | W   | 1.000      | -            | -                | -                | 0 (0.000) |     0.76 | kraghen, Nodios, Patti, Queenix, salazar      |
|           90 |      112 | 2024-05-03 | AMKAL ESPORTS                | L   | 1.000      | -            | -                | -                | -         |   -16.15 | kraghen, Nodios, Patti, Queenix, salazar      |
|           89 |      146 | 2024-05-02 | HAVU Gaming                  | W   | 1.000      | -            | -                | -                | -         |     2.01 | kraghen, Nodios, Patti, Queenix, salazar      |
|           88 |      160 | 2024-05-02 | SINNERS Esports              | W   | 1.000      | 0.435        | -                | 0.534 (0.232)    | -         |     4.73 | kraghen, Nodios, Patti, Queenix, salazar      |
|           87 |      236 | 2024-04-30 | AMKAL ESPORTS                | L   | 1.000      | -            | -                | -                | -         |   -17.27 | kraghen, Nodios, Patti, Queenix, salazar      |
|           86 |      288 | 2024-04-29 | TBA.ECF                      | L   | 1.000      | -            | -                | -                | -         |   -29.42 | kraghen, Nodios, Patti, Queenix, salazar      |
|           85 |      327 | 2024-04-28 | 9Pandas                      | L   | 1.000      | -            | -                | -                | -         |   -25.61 | kraghen, Nodios, Patti, Queenix, salazar      |
|           84 |      446 | 2024-04-26 | ALTERNATE aTTaX              | L   | 1.000      | -            | -                | -                | -         |   -28.65 | kraghen, Nodios, Patti, Queenix, salazar      |
|           83 |      583 | 2024-04-23 | Sashi Esport                 | L   | 1.000      | -            | -                | -                | -         |   -20.89 | kraghen, Nodios, Patti, Queenix, salazar      |
|           82 |      615 | 2024-04-22 | BLEED Esports                | L   | 1.000      | -            | -                | -                | -         |   -23.92 | kraghen, Nodios, Patti, Queenix, salazar      |
|           81 |      649 | 2024-04-21 | AMKAL ESPORTS                | W   | 1.000      | 0.384        | 0.209 (0.080)    | 0.756 (0.291)    | -         |     8.36 | kraghen, Nodios, Patti, Queenix, salazar      |
|           80 |      770 | 2024-04-20 | Nemiga Gaming                | W   | 1.000      | 0.384        | 0.680 (0.261)    | 0.910 (0.350)    | -         |     9.95 | kraghen, Nodios, Patti, Queenix, salazar      |
|           79 |      923 | 2024-04-17 | DMS                          | L   | 1.000      | -            | -                | -                | -         |   -30.52 | kraghen, Nodios, Patti, Queenix, salazar      |
|           78 |      971 | 2024-04-17 | SINNERS Esports              | W   | 1.000      | 0.384        | -                | 0.534 (0.205)    | -         |     3.77 | kraghen, Nodios, Patti, Queenix, salazar      |
|           77 |     1019 | 2024-04-16 | Permitta Esports             | W   | 1.000      | 0.384        | -                | 1.000 (0.384)    | -         |     2.46 | kraghen, Nodios, Patti, Queenix, salazar      |
|           76 |     1792 | 2024-03-26 | Onyx Ravens                  | W   | 0.933      | -            | -                | -                | -         |     0.52 | 0SAMAS, 0scar, Ejram, PokemoN, TTyke          |
|           75 |     1913 | 2024-03-23 | G2 Esports                   | L   | 0.911      | -            | -                | -                | -         |    -1.98 | HooXi, huNter-, m0NESY, nexa, NiKo            |
|           74 |     1934 | 2024-03-22 | FURIA Esports                | W   | 0.905      | 1.000        | 0.384 (0.348)    | 0.361 (0.327)    | 1 (0.905) |    20.88 | arT, chelo, FalleN, KSCERATO, yuurih          |
|           73 |     1967 | 2024-03-21 | Cloud9                       | L   | 0.899      | -            | -                | -                | -         |    -3.26 | kraghen, Nodios, Patti, Queenix, salazar      |
|           72 |     1994 | 2024-03-21 | MOUZ                         | L   | 0.897      | -            | -                | -                | -         |    -1.66 | kraghen, Nodios, Patti, Queenix, salazar      |
|           71 |     2058 | 2024-03-19 | Imperial Esports             | W   | 0.885      | 1.000        | 0.674 (0.596)    | 0.549 (0.486)    | 1 (0.885) |    18.80 | decenty, felps, HEN1, noway, VINI             |
|           70 |     2102 | 2024-03-18 | Lynn Vision Gaming           | W   | 0.877      | 1.000        | 0.155 (0.136)    | 0.554 (0.486)    | 1 (0.877) |    10.97 | EmiliaQAQ, Jee, Starry, westmelon, z4KR       |
|           69 |     2131 | 2024-03-17 | The MongolZ                  | W   | 0.872      | 1.000        | 0.292 (0.255)    | 0.663 (0.578)    | 1 (0.872) |    22.65 | 910, bLitz, mzinho, Senzu, Techno4K           |
|           68 |     2150 | 2024-03-17 | Cloud9                       | L   | 0.870      | -            | -                | -                | -         |    -2.49 | kraghen, Nodios, Patti, Queenix, salazar      |
|           67 |     2723 | 2024-03-04 | B8                           | L   | 0.786      | -            | -                | -                | -         |   -22.06 | cptkurtka023, esenthial, npl, OWNER, r1nkle   |
|           66 |     2736 | 2024-03-04 | LEON Esports                 | W   | 0.786      | -            | -                | -                | -         |     0.60 | eightz, facecrack, JIaYm, k0s, z1w0w          |
|           65 |     2773 | 2024-03-04 | BetBoom Team                 | L   | 0.783      | -            | -                | -                | -         |   -10.09 | kraghen, Nodios, Patti, Queenix, salazar      |
|           64 |     2782 | 2024-03-03 | Preasy Esport                | L   | 0.779      | -            | -                | -                | -         |   -21.20 | kraghen, Nodios, Patti, Queenix, salazar      |
|           63 |     2792 | 2024-03-03 | Fnatic                       | W   | 0.779      | 0.143        | 0.334 (0.037)    | -                | -         |     7.13 | kraghen, Nodios, Patti, Queenix, salazar      |
|           62 |     2796 | 2024-03-03 | SINNERS Esports              | W   | 0.778      | -            | -                | -                | -         |     2.73 | AJTT, beastik, NEOFRAG, oskar, SHOCK          |
|           61 |     2831 | 2024-03-02 | JANO Esports                 | W   | 0.773      | -            | -                | -                | -         |     0.86 | allu, doto, jelo, Jerppa, Sm1llee             |
|           60 |     2844 | 2024-03-02 | TEAM MAX (European mix-team) | W   | 0.772      | -            | -                | -                | -         |     0.20 | kL1o, Malkiss, tooizera, treckiz, zecco       |
|           59 |     2886 | 2024-03-02 | PARIVISION                   | W   | 0.771      | -            | -                | -                | -         |     1.48 | kraghen, Nodios, Patti, Queenix, salazar      |
|           58 |     3262 | 2024-02-22 | Guild Eagles                 | W   | 0.711      | -            | -                | -                | 1 (0.711) |     3.49 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy   |
|           57 |     3327 | 2024-02-21 | Apeks                        | L   | 0.703      | -            | -                | -                | -         |    -9.64 | kraghen, Nodios, Patti, Queenix, salazar      |
|           56 |     3376 | 2024-02-20 | OG                           | W   | 0.697      | 0.143        | 0.594 (0.059)    | -                | 1 (0.697) |     9.18 | F1KU, HeavyGod, k1to, Nexius, regali          |
|           55 |     3403 | 2024-02-19 | MOUZ                         | L   | 0.692      | -            | -                | -                | -         |    -1.29 | kraghen, Nodios, Patti, Queenix, salazar      |
|           54 |     3423 | 2024-02-19 | Monte                        | W   | 0.690      | -            | -                | -                | 1 (0.690) |    12.52 | kraghen, Nodios, Patti, Queenix, salazar      |
|           53 |     3806 | 2024-02-09 | Preasy Esport                | L   | 0.623      | -            | -                | -                | -         |   -17.49 | Altekz, dupreeh, refrezh, roeJ, TMB           |
|           52 |     3879 | 2024-02-05 | L&G                          | W   | 0.599      | -            | -                | -                | -         |     0.20 | kraghen, Nodios, Patti, Queenix, salazar      |
|           51 |     3900 | 2024-02-05 | Nexus Gaming                 | W   | 0.598      | -            | -                | -                | -         |     1.32 | BTN, ERSIN, ragga, s0und, XELLOW              |
|           50 |     3905 | 2024-02-05 | Insilio                      | W   | 0.598      | 0.371        | -                | 0.875 (0.194)    | -         |     1.82 | kraghen, Nodios, Patti, Queenix, salazar      |
|           49 |     3911 | 2024-02-05 | Preasy Esport                | W   | 0.596      | -            | -                | -                | -         |     1.88 | kraghen, Nodios, Patti, Queenix, salazar      |
|           48 |     3949 | 2024-02-03 | Sashi Esport                 | L   | 0.585      | -            | -                | -                | -         |   -15.75 | Cabbi, IceBerg, kwezz, Lucky, MistR           |
|           47 |     3957 | 2024-02-03 | Lilmix                       | W   | 0.585      | -            | -                | -                | -         |     0.24 | Brillo, dex, poiii, quix, zyyx                |
|           46 |     3965 | 2024-02-03 | Johnny Speeds                | W   | 0.585      | -            | -                | -                | -         |     0.94 | chawzyyy, L00m1, Lekr0, spooke, truth         |
|           45 |     4051 | 2024-02-02 | Into The Breach              | W   | 0.577      | -            | -                | -                | -         |     0.92 | Bymas, CRUC1AL, misutaaa, rallen, Thomas      |
|           44 |     4070 | 2024-02-01 | Kappa Bar                    | W   | 0.572      | -            | -                | -                | -         |     0.33 | kraghen, Nodios, Patti, Queenix, salazar      |
|           43 |     4159 | 2024-01-29 | 500                          | L   | 0.553      | -            | -                | -                | -         |   -16.71 | dennyslaw, Patrick, Rainwaker, REDSTAR, SHiPZ |
|           42 |     4228 | 2024-01-28 | Sangal Esports               | W   | 0.543      | -            | -                | -                | -         |     0.32 | Ganginho, LNZ, sausol, xfl0ud, yxngstxr       |
|           41 |     4376 | 2024-01-24 | Ex-KRC Genk Esports          | W   | 0.519      | -            | -                | -                | -         |     0.55 | CrePoW, MAGILA, Philong, Wumbo, yOOm          |
|           40 |     4405 | 2024-01-24 | Alliance                     | W   | 0.516      | -            | -                | -                | -         |     0.85 | avid, b0denmaster, PlesseN, robiin, twist     |
|           39 |     4506 | 2024-01-21 | Pera Esports                 | W   | 0.497      | -            | -                | -                | -         |     1.13 | Aaron, DGL, Kamion, msN, Porya                |
|           38 |     4544 | 2024-01-20 | Fnatic                       | L   | 0.492      | -            | -                | -                | -         |   -11.22 | afro, bodyy, KRIMZ, kyuubii, matys            |
|           37 |     4562 | 2024-01-20 | Permitta Esports             | W   | 0.490      | -            | -                | -                | -         |     1.42 | bnox, maaryy, mASKED, morelz, Vegi            |
|           36 |     4608 | 2024-01-19 | 9Pandas                      | L   | 0.484      | -            | -                | -                | -         |   -12.71 | kraghen, Nodios, Patti, Queenix, salazar      |
|           35 |     4645 | 2024-01-18 | Nexus Gaming                 | W   | 0.479      | -            | -                | -                | -         |     0.92 | BTN, ERSIN, ragga, s0und, XELLOW              |
|           34 |     4668 | 2024-01-18 | Natus Vincere                | L   | 0.478      | -            | -                | -                | -         |    -0.72 | kraghen, Nodios, Patti, Queenix, salazar      |
|           33 |     4882 | 2024-01-13 | OG                           | W   | 0.446      | 0.143        | 0.594 (0.038)    | -                | -         |     5.48 | kraghen, Nodios, Patti, Queenix, salazar      |
|           32 |     4885 | 2024-01-13 | 500                          | W   | 0.445      | -            | -                | -                | -         |     0.46 | kraghen, Nodios, Patti, Queenix, salazar      |
|           31 |     4893 | 2024-01-13 | UNiTY esports (Slovak team)  | W   | 0.444      | -            | -                | -                | -         |     1.13 | Levi, luko, M1key, NIO, Pechyn                |
|           30 |     4924 | 2024-01-12 | The Witchers                 | W   | 0.439      | -            | -                | -                | -         |     0.43 | Dragon, fear, Sdaim, smooya, synyx            |
|           29 |     5059 | 2024-01-10 | PrizyvaNet                   | L   | 0.426      | -            | -                | -                | -         |   -13.31 | Brilliance, la3euka, SasukeQO, sunshine, z1k4 |
|           28 |     5074 | 2024-01-09 | Fnatic                       | L   | 0.419      | -            | -                | -                | -         |   -10.27 | kraghen, Nodios, Patti, Queenix, salazar      |
|           27 |     5082 | 2024-01-09 | Illuminar Gaming             | W   | 0.419      | -            | -                | -                | -         |     0.36 | kraghen, Nodios, Patti, Queenix, salazar      |
|           26 |     5099 | 2024-01-09 | Untouchabless                | W   | 0.418      | -            | -                | -                | -         |     0.08 | datyx, kjuK, Kokaina, MahaR, onStyle          |
|           25 |     5108 | 2024-01-09 | TEAM ZOO BAR                 | W   | 0.418      | -            | -                | -                | -         |     0.07 | AMANEK, devoduvek, drac, Kyojin, SIXER        |
|           24 |     5885 | 2023-12-07 | Sprout                       | L   | 0.199      | -            | -                | -                | -         |    -6.16 | cej0t, fNk, raalz, spooke, Tauson             |
|           23 |     5936 | 2023-12-06 | 9Pandas                      | L   | 0.191      | -            | -                | -                | -         |    -5.09 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           22 |     6213 | 2023-11-30 | Guild Eagles                 | L   | 0.151      | -            | -                | -                | -         |    -4.34 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy   |
|           21 |     6262 | 2023-11-29 | MOUZ NXT                     | L   | 0.145      | -            | -                | -                | -         |    -4.02 | kraghen, Nodios, Patti, Queenix, salazar      |
|           20 |     6277 | 2023-11-29 | Insilio                      | W   | 0.144      | -            | -                | -                | -         |     0.22 | kraghen, Nodios, Patti, Queenix, salazar      |
|           19 |     6310 | 2023-11-28 | Nemiga Gaming                | L   | 0.139      | -            | -                | -                | -         |    -2.98 | kraghen, Nodios, Patti, Queenix, salazar      |
|           18 |     6531 | 2023-11-23 | Preasy Esport                | W   | 0.104      | -            | -                | -                | -         |     0.19 | kraghen, Nodios, Patti, Queenix, salazar      |
|           17 |     6600 | 2023-11-21 | L&G                          | W   | 0.091      | -            | -                | -                | -         |     0.02 | kraghen, Nodios, Patti, Queenix, salazar      |
|           16 |     6616 | 2023-11-20 | Lajtbitexe                   | L   | 0.086      | -            | -                | -                | -         |    -2.68 | kraghen, Nodios, Patti, Queenix, salazar      |
|           15 |     6748 | 2023-11-18 | Into The Breach              | L   | 0.070      | -            | -                | -                | -         |    -2.14 | kraghen, Nodios, Patti, Queenix, salazar      |
|           14 |     6766 | 2023-11-17 | EHawks                       | L   | 0.066      | -            | -                | -                | -         |    -2.05 | kraghen, Nodios, Patti, Queenix, salazar      |
|           13 |     6775 | 2023-11-17 | 9Pandas                      | W   | 0.064      | -            | -                | -                | -         |     0.28 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           12 |     6809 | 2023-11-16 | Kappa Bar                    | L   | 0.059      | -            | -                | -                | -         |    -1.83 | kraghen, Nodios, Patti, Queenix, salazar      |
|           11 |     6827 | 2023-11-16 | EYEBALLERS                   | W   | 0.058      | -            | -                | -                | -         |     0.10 | kraghen, Nodios, Patti, Queenix, salazar      |
|           10 |     6867 | 2023-11-15 | ARCRED                       | L   | 0.052      | -            | -                | -                | -         |    -1.59 | 1NVISIBLEE, DSSj, hurtslxrd, Ryujin, shg      |
|            9 |     6873 | 2023-11-15 | Team Spirit Academy          | W   | 0.052      | -            | -                | -                | -         |     0.04 | alpha, baz, keegaN, Magnojez, notineki        |
|            8 |     6968 | 2023-11-13 | Aurora Young Blud            | W   | 0.038      | -            | -                | -                | -         |     0.03 | bl1x1, bluewh1te, Easy, malinov, sh1geo       |
|            7 |     6984 | 2023-11-13 | FORZE Esports                | W   | 0.037      | -            | -                | -                | -         |     0.03 | kraghen, Nodios, Patti, Queenix, salazar      |
|            6 |     7074 | 2023-11-11 | Turów Zgorzelec Esport       | W   | 0.023      | -            | -                | -                | -         |     0.00 | b1elany, darko, gRuChA, kadziu, snatchie      |
|            5 |     7092 | 2023-11-10 | Lemondogs                    | W   | 0.018      | -            | -                | -                | -         |     0.00 | kraghen, Nodios, Patti, Queenix, salazar      |
|            4 |     7139 | 2023-11-09 | The Witchers                 | L   | 0.011      | -            | -                | -                | -         |    -0.35 | fear, Sdaim, smooya, soulfly, synyx           |
|            3 |     7146 | 2023-11-09 | Dynamo Eclot                 | W   | 0.010      | -            | -                | -                | -         |     0.00 | anarkez, Dytor, K1-FiDa, NEOFRAG, Valencio    |
|            2 |     7161 | 2023-11-08 | Project G                    | L   | 0.006      | -            | -                | -                | -         |    -0.17 | Dragon, Lekr0, mwlky, xfl0ud, ztr             |
|            1 |     7211 | 2023-11-08 | SINNERS Esports              | L   | 0.003      | -            | -                | -                | -         |    -0.08 | beastik, KWERTZZ, oskar, SHOCK, ZEDKO         |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($30,790.28)
- Divide that value by the 5th highest value among all rosters ($158,437.64)
- The final value (0.19) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-05-04 |      1.000 | $2,000.00      | $2,000.00       |
| 2024-05-02 |      1.000 | $1,000.00      | $1,000.00       |
| 2024-04-22 |      1.000 | $5,000.00      | $5,000.00       |
| 2024-03-31 |      0.965 | $20,000.00     | $19,304.63      |
| 2024-02-09 |      0.623 | $5,000.00      | $3,113.66       |
| 2023-11-18 |      0.070 | $5,000.00      | $348.38         |
| 2023-11-09 |      0.012 | $2,000.00      | $23.61          |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
