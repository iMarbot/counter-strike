### Roster Details<br />
Team Name: Sashi Esport<br />
Roster: Cabbi, IceBerg, kwezz, Lucky, MistR<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [30](../standings_global.md)<br />
Regional Rank: [22]( ../standings_europe.md)<br />
Final Rank Value:  1285.7<br />
<br />
Final Rank Value (1285.7) = Starting Rank Value (1094.4) + Head To Head Adjustments (191.3)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.583[<sup>1</sup>](#table2)
- Bounty Collected: 0.508[<sup>2</sup>](#table1)
- Opponent Network: 0.309[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.350<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1094.4
- 400 + ( ( 0.350 - 0.000 ) / ( 0.806 - 0.000 ) ) * 1600 = 1094.4


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent                    | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins      | H2H Adj. | Roster                                       |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|          117 |       10 | 2024-05-05 | Gaimin Gladiators           | L   | 1.000      | -            | -                | -                | -             |   -18.15 | Cabbi, IceBerg, kwezz, Lucky, MistR          |
|          116 |       20 | 2024-05-05 | Come on now dawg            | W   | 1.000      | -            | -                | -                | false (0.000) |     0.45 | Cabbi, IceBerg, kwezz, Lucky, MistR          |
|          115 |       32 | 2024-05-05 | MASONIC                     | W   | 1.000      | -            | -                | -                | false (0.000) |     3.00 | Cabbi, IceBerg, kwezz, Lucky, MistR          |
|          114 |      145 | 2024-05-02 | Fnatic                      | W   | 1.000      | 0.384        | 0.334 (0.128)    | -                | false (0.000) |    13.54 | Cabbi, IceBerg, kwezz, Lucky, MistR          |
|          113 |      218 | 2024-05-01 | 3DMAX                       | W   | 1.000      | -            | -                | -                | false (0.000) |     5.30 | Cabbi, IceBerg, kwezz, Lucky, MistR          |
|          112 |      245 | 2024-04-30 | OG                          | W   | 1.000      | 0.384        | 0.594 (0.228)    | -                | false (0.000) |    19.93 | Cabbi, IceBerg, kwezz, Lucky, MistR          |
|          111 |      263 | 2024-04-29 | Sashi Academy               | W   | 1.000      | -            | -                | -                | false (0.000) |     0.81 | Cabbi, IceBerg, kwezz, Lucky, MistR          |
|          110 |      267 | 2024-04-29 | Preasy Esport               | W   | 1.000      | -            | -                | -                | false (0.000) |     1.35 | Cabbi, IceBerg, kwezz, Lucky, MistR          |
|          109 |      278 | 2024-04-29 | WOPA Esport                 | W   | 1.000      | -            | -                | -                | false (0.000) |     1.75 | Cabbi, IceBerg, kwezz, Lucky, MistR          |
|          108 |      289 | 2024-04-29 | 500                         | W   | 1.000      | -            | -                | -                | false (0.000) |     3.58 | Cabbi, IceBerg, kwezz, Lucky, MistR          |
|          107 |      349 | 2024-04-27 | 777 Esports                 | W   | 1.000      | -            | -                | -                | false (0.000) |     1.76 | Cabbi, IceBerg, kwezz, Lucky, MistR          |
|          106 |      359 | 2024-04-27 | JANO Esports                | W   | 1.000      | -            | -                | -                | -             |     1.45 | Cabbi, IceBerg, kwezz, Lucky, MistR          |
|          105 |      402 | 2024-04-26 | JANO Esports                | W   | 1.000      | -            | -                | -                | -             |     1.59 | Cabbi, IceBerg, kwezz, Lucky, MistR          |
|          104 |      405 | 2024-04-26 | 777 Esports                 | W   | 1.000      | -            | -                | -                | -             |     1.69 | Cabbi, IceBerg, kwezz, Lucky, MistR          |
|          103 |      410 | 2024-04-26 | Preasy Esport               | W   | 1.000      | -            | -                | -                | -             |     1.45 | Cabbi, IceBerg, kwezz, Lucky, MistR          |
|          102 |      416 | 2024-04-26 | Esport Harte                | W   | 1.000      | -            | -                | -                | -             |     0.72 | Cabbi, IceBerg, kwezz, Lucky, MistR          |
|          101 |      424 | 2024-04-26 | Static                      | W   | 1.000      | -            | -                | -                | -             |     0.58 | Cabbi, IceBerg, kwezz, Lucky, MistR          |
|          100 |      491 | 2024-04-25 | Passion UA                  | W   | 1.000      | 0.384        | 0.114 (0.044)    | 0.980 (0.376)    | -             |     4.62 | Cabbi, IceBerg, kwezz, Lucky, MistR          |
|           99 |      583 | 2024-04-23 | Gaimin Gladiators           | W   | 1.000      | 0.384        | 0.194 (0.075)    | 0.989 (0.380)    | -             |    20.89 | Cabbi, IceBerg, kwezz, Lucky, MistR          |
|           98 |      590 | 2024-04-23 | BLEED Esports               | W   | 1.000      | 0.384        | 0.284 (0.109)    | -                | -             |    14.20 | Cabbi, IceBerg, kwezz, Lucky, MistR          |
|           97 |      705 | 2024-04-20 | Eternal Fire                | W   | 1.000      | 0.143        | 0.409 (0.058)    | -                | -             |    30.49 | Cabbi, IceBerg, kwezz, Lucky, MistR          |
|           96 |      735 | 2024-04-20 | Cloud9                      | W   | 1.000      | 0.143        | 0.487 (0.070)    | -                | -             |    29.99 | Cabbi, IceBerg, kwezz, Lucky, MistR          |
|           95 |      812 | 2024-04-19 | Eternal Fire                | L   | 1.000      | -            | -                | -                | -             |    -0.74 | Cabbi, IceBerg, kwezz, Lucky, MistR          |
|           94 |      835 | 2024-04-19 | Cloud9                      | W   | 1.000      | 0.143        | 0.487 (0.070)    | -                | -             |    30.37 | Cabbi, IceBerg, kwezz, Lucky, MistR          |
|           93 |      868 | 2024-04-18 | Guild Eagles                | W   | 1.000      | -            | -                | -                | -             |    12.46 | Cabbi, IceBerg, kwezz, Lucky, MistR          |
|           92 |      872 | 2024-04-18 | RUBY                        | W   | 1.000      | -            | -                | -                | -             |    10.85 | Cabbi, IceBerg, kwezz, Lucky, MistR          |
|           91 |      882 | 2024-04-18 | GamerLegion                 | W   | 1.000      | -            | -                | -                | -             |    27.95 | Cabbi, IceBerg, kwezz, Lucky, MistR          |
|           90 |      926 | 2024-04-17 | 9Pandas                     | W   | 1.000      | -            | -                | -                | -             |    16.70 | Cabbi, IceBerg, kwezz, Lucky, MistR          |
|           89 |      950 | 2024-04-17 | Passion UA                  | L   | 1.000      | -            | -                | -                | -             |   -20.98 | Cabbi, IceBerg, kwezz, Lucky, MistR          |
|           88 |     1014 | 2024-04-16 | Guild Eagles                | L   | 1.000      | -            | -                | -                | -             |   -18.50 | Cabbi, IceBerg, kwezz, Lucky, MistR          |
|           87 |     1033 | 2024-04-15 | IMMAPROBLEM                 | W   | 1.000      | -            | -                | -                | -             |     1.48 | Cabbi, IceBerg, kwezz, Lucky, MistR          |
|           86 |     1427 | 2024-04-06 | UNiTY esports (Slovak team) | W   | 1.000      | -            | -                | -                | -             |     8.19 | K1-FiDa, Levi, M1key, NIO, Pechyn            |
|           85 |     1505 | 2024-04-04 | UNiTY esports (Slovak team) | W   | 0.990      | -            | -                | -                | -             |     9.31 | K1-FiDa, Levi, M1key, NIO, Pechyn            |
|           84 |     1595 | 2024-04-02 | Permitta Esports            | W   | 0.976      | 0.333        | -                | 1.000 (0.325)    | -             |    10.61 | Cabbi, IceBerg, kwezz, Lucky, MistR          |
|           83 |     1647 | 2024-03-30 | Turów Zgorzelec Esport      | W   | 0.957      | -            | -                | -                | -             |     6.13 | darko, EXUS, kadziu, Markoś, Sobol           |
|           82 |     1741 | 2024-03-27 | Rebels Gaming               | L   | 0.939      | -            | -                | -                | -             |   -11.20 | Cabbi, IceBerg, kwezz, Lucky, MistR          |
|           81 |     1757 | 2024-03-27 | Pera Esports                | W   | 0.938      | -            | -                | -                | -             |     8.22 | Cabbi, IceBerg, kwezz, Lucky, MistR          |
|           80 |     1811 | 2024-03-26 | ARROW (German team)         | W   | 0.932      | -            | -                | -                | -             |     3.60 | Kre1N, Orbit, SnacKZ1, Tionix, Twiksar       |
|           79 |     1833 | 2024-03-26 | Dynamo Eclot                | L   | 0.930      | -            | -                | -                | -             |   -13.59 | Cabbi, IceBerg, kwezz, Lucky, MistR          |
|           78 |     1845 | 2024-03-25 | Nexus Gaming                | W   | 0.925      | 0.371        | -                | 0.772 (0.265)    | -             |    11.03 | Cabbi, IceBerg, kwezz, Lucky, MistR          |
|           77 |     1938 | 2024-03-22 | Nemiga Gaming               | W   | 0.905      | 0.371        | 0.680 (0.229)    | 0.910 (0.306)    | -             |    22.49 | Cabbi, IceBerg, kwezz, Lucky, MistR          |
|           76 |     1951 | 2024-03-22 | Viperio                     | W   | 0.903      | -            | -                | -                | -             |     3.27 | mAnGo, MMS, pandi7o, ReegaN, zodi            |
|           75 |     2056 | 2024-03-19 | RUBY                        | W   | 0.885      | 0.371        | -                | 0.882 (0.290)    | -             |    10.14 | Cabbi, IceBerg, kwezz, Lucky, MistR          |
|           74 |     2098 | 2024-03-18 | Insilio                     | W   | 0.877      | 0.371        | -                | 0.875 (0.285)    | -             |    13.17 | faydett, FpSSS, Pipw, Polt, sugaR            |
|           73 |     2429 | 2024-03-11 | Nemiga Gaming               | L   | 0.831      | -            | -                | -                | -             |    -4.12 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r         |
|           72 |     2471 | 2024-03-10 | Team Sampi                  | L   | 0.823      | -            | -                | -                | -             |   -13.78 | Cabbi, IceBerg, kwezz, Lucky, MistR          |
|           71 |     2515 | 2024-03-09 | Permitta Esports            | W   | 0.817      | 0.371        | -                | 1.000 (0.303)    | -             |    12.51 | bnox, maaryy, mASKED, morelz, Vegi           |
|           70 |     2545 | 2024-03-08 | ALTERNATE aTTaX             | L   | 0.809      | -            | -                | -                | -             |   -15.92 | ArroW, awzek, FreeZe, hyped, skyye           |
|           69 |     2565 | 2024-03-07 | Insilio                     | W   | 0.806      | -            | -                | -                | -             |    11.26 | faydett, FpSSS, Pipw, Polt, sugaR            |
|           68 |     2693 | 2024-03-05 | Johnny Speeds               | L   | 0.792      | -            | -                | -                | -             |   -17.91 | Cabbi, IceBerg, kwezz, Lucky, MistR          |
|           67 |     2744 | 2024-03-04 | Team QUAZAR                 | W   | 0.786      | -            | -                | -                | -             |     0.70 | Electro, KarmaN, kirito, LVF, xnkka          |
|           66 |     2774 | 2024-03-04 | Entropiq                    | L   | 0.783      | -            | -                | -                | -             |   -19.50 | c0llins, Marix, mwlky, Oxygen, tiziaN        |
|           65 |     2854 | 2024-03-02 | The Chosen Few              | L   | 0.772      | -            | -                | -                | -             |   -19.75 | choiv7, KalubeR, shaiK, Skrimo, SPELLAN      |
|           64 |     2888 | 2024-03-02 | Illuminar Gaming            | W   | 0.770      | -            | -                | -                | -             |     3.95 | Furlan, phr, POLO, Prism, Qlocuu             |
|           63 |     2938 | 2024-02-29 | MOUZ NXT                    | W   | 0.759      | 0.371        | 0.215 (0.061)    | 1.000 (0.282)    | -             |    13.38 | Cabbi, IceBerg, kwezz, Lucky, MistR          |
|           62 |     2947 | 2024-02-29 | Permitta Esports            | W   | 0.758      | 0.371        | -                | 1.000 (0.282)    | -             |    10.38 | bnox, maaryy, mASKED, morelz, Vegi           |
|           61 |     3030 | 2024-02-27 | V1dar Gaming                | L   | 0.745      | -            | -                | -                | -             |   -20.96 | Cabbi, IceBerg, kwezz, Lucky, MistR          |
|           60 |     3062 | 2024-02-26 | Betera Esports              | W   | 0.739      | -            | -                | -                | -             |     5.58 | alex666, lollipop21k, MaSvAl, nifee, sad     |
|           59 |     3094 | 2024-02-25 | Sangal Esports              | L   | 0.732      | -            | -                | -                | -             |   -20.18 | Cabbi, IceBerg, kwezz, Lucky, MistR          |
|           58 |     3110 | 2024-02-25 | Turów Zgorzelec Esport      | L   | 0.730      | -            | -                | -                | -             |   -18.50 | AxEcHo, darko, kadziu, Markoś, xKacpersky    |
|           57 |     3187 | 2024-02-24 | MOUZ NXT                    | L   | 0.723      | -            | -                | -                | -             |   -11.31 | Cabbi, IceBerg, kwezz, Lucky, MistR          |
|           56 |     3207 | 2024-02-23 | VP.Prodigy                  | W   | 0.719      | -            | -                | -                | -             |     4.29 | dwushka, KusMe, shady, Something, xdENiSZERA |
|           55 |     3212 | 2024-02-23 | BLESSED (Ukrainian team)    | W   | 0.718      | -            | -                | -                | -             |     3.48 | Cabbi, IceBerg, kwezz, Lucky, MistR          |
|           54 |     3324 | 2024-02-21 | Team Sampi                  | W   | 0.704      | -            | -                | -                | -             |     8.24 | Cabbi, IceBerg, kwezz, Lucky, MistR          |
|           53 |     3331 | 2024-02-21 | Verdant                     | W   | 0.703      | -            | -                | -                | -             |     7.70 | arTisT, Ducky, Girafffe, Vacancy, Zax1e      |
|           52 |     3409 | 2024-02-19 | Aurora Young Blud           | W   | 0.692      | -            | -                | -                | -             |     4.20 | Cabbi, IceBerg, kwezz, Lucky, MistR          |
|           51 |     3498 | 2024-02-17 | Zero Tenacity               | W   | 0.678      | -            | -                | -                | -             |     6.39 | Cabbi, IceBerg, kwezz, Lucky, MistR          |
|           50 |     3548 | 2024-02-16 | Permitta Esports            | W   | 0.670      | -            | -                | -                | -             |     8.07 | bnox, maaryy, mASKED, morelz, Vegi           |
|           49 |     3674 | 2024-02-13 | HOTU                        | W   | 0.652      | -            | -                | -                | -             |     3.74 | Cabbi, IceBerg, kwezz, Lucky, MistR          |
|           48 |     3737 | 2024-02-12 | Astralis Talent             | W   | 0.643      | -            | -                | -                | -             |     7.38 | ANSG1, JBOEN, kiR, kroK, tOPZ                |
|           47 |     3757 | 2024-02-11 | ARCRED                      | W   | 0.637      | -            | -                | -                | -             |     4.42 | Cabbi, IceBerg, kwezz, Lucky, MistR          |
|           46 |     3763 | 2024-02-10 | Nemiga Gaming               | L   | 0.632      | -            | -                | -                | -             |    -3.51 | Cabbi, IceBerg, kwezz, Lucky, MistR          |
|           45 |     3777 | 2024-02-10 | AMKAL ESPORTS               | W   | 0.631      | -            | -                | -                | -             |    14.81 | Cabbi, IceBerg, kwezz, Lucky, MistR          |
|           44 |     3798 | 2024-02-09 | Insilio                     | W   | 0.624      | -            | -                | -                | -             |     8.57 | faydett, FpSSS, Pipw, Polt, sugaR            |
|           43 |     3813 | 2024-02-08 | Nemiga Gaming               | L   | 0.619      | -            | -                | -                | -             |    -3.29 | Cabbi, IceBerg, kwezz, Lucky, MistR          |
|           42 |     3839 | 2024-02-07 | Team Spirit Academy         | W   | 0.612      | -            | -                | -                | -             |     4.67 | Cabbi, IceBerg, kwezz, Lucky, MistR          |
|           41 |     3845 | 2024-02-07 | Insilio                     | L   | 0.612      | -            | -                | -                | -             |   -11.32 | Cabbi, IceBerg, kwezz, Lucky, MistR          |
|           40 |     3849 | 2024-02-07 | BIG Academy                 | L   | 0.610      | -            | -                | -                | -             |   -14.74 | Cabbi, IceBerg, kwezz, Lucky, MistR          |
|           39 |     3898 | 2024-02-05 | L&G                         | W   | 0.598      | -            | -                | -                | -             |     1.09 | Cabbi, IceBerg, kwezz, Lucky, MistR          |
|           38 |     3926 | 2024-02-04 | TOOMUCHVIDEOGAMES           | L   | 0.591      | -            | -                | -                | -             |   -17.67 | Cabbi, IceBerg, kwezz, Lucky, MistR          |
|           37 |     3949 | 2024-02-03 | Gaimin Gladiators           | W   | 0.585      | -            | -                | -                | -             |    15.75 | Cabbi, IceBerg, kwezz, Lucky, MistR          |
|           36 |     3958 | 2024-02-03 | EYEBALLERS                  | W   | 0.585      | -            | -                | -                | -             |     6.58 | Cabbi, IceBerg, kwezz, Lucky, MistR          |
|           35 |     3975 | 2024-02-03 | Kappa Bar                   | W   | 0.585      | -            | -                | -                | -             |     1.96 | dezt, jayzaR, pupcake, TIM, upE              |
|           34 |     4001 | 2024-02-03 | Team Sampi                  | L   | 0.584      | -            | -                | -                | -             |   -10.74 | Cabbi, IceBerg, kwezz, Lucky, MistR          |
|           33 |     4017 | 2024-02-02 | EYEBALLERS                  | L   | 0.579      | -            | -                | -                | -             |   -12.08 | HEAP, JW, Peppzor, Sapec, SHiNE              |
|           32 |     4093 | 2024-02-01 | ENCE Academy                | W   | 0.570      | -            | -                | -                | -             |     4.16 | HENU, myltsi, podi, S1rva, teme              |
|           31 |     4132 | 2024-01-30 | Insilio                     | W   | 0.559      | -            | -                | -                | -             |     6.69 | faydett, FpSSS, Pipw, Polt, sugaR            |
|           30 |     4134 | 2024-01-30 | FORZE Esports               | W   | 0.559      | -            | -                | -                | -             |     3.99 | gokushima, r3salt, shalfey, sstiNiX, tN1R    |
|           29 |     4145 | 2024-01-30 | RUSH B (Russian team)       | W   | 0.558      | -            | -                | -                | -             |     3.03 | Cabbi, IceBerg, kwezz, Lucky, MistR          |
|           28 |     4162 | 2024-01-29 | Illuminar Gaming            | W   | 0.553      | -            | -                | -                | -             |     3.35 | Furlan, phr, POLO, Prism, Qlocuu             |
|           27 |     4191 | 2024-01-29 | Sangal Esports              | W   | 0.553      | -            | -                | -                | -             |     2.04 | Ganginho, LNZ, sausol, xfl0ud, yxngstxr      |
|           26 |     4461 | 2024-01-22 | RUBY                        | W   | 0.505      | -            | -                | -                | -             |     4.24 | dekz, Kaide, mo0n, Sowalio, w1nt3r           |
|           25 |     4471 | 2024-01-22 | FORZE Youngsters            | W   | 0.505      | -            | -                | -                | -             |     1.95 | Cabbi, IceBerg, kwezz, Lucky, MistR          |
|           24 |     4744 | 2024-01-17 | Natus Vincere Junior        | L   | 0.472      | -            | -                | -                | -             |   -11.64 | dem0n, fnl, Krabeni, Magic, makazze          |
|           23 |     4785 | 2024-01-16 | EYEBALLERS                  | L   | 0.466      | -            | -                | -                | -             |    -9.54 | Cabbi, IceBerg, kwezz, Lucky, MistR          |
|           22 |     4793 | 2024-01-16 | ARCRED                      | W   | 0.466      | -            | -                | -                | -             |     3.19 | Cabbi, IceBerg, kwezz, Lucky, MistR          |
|           21 |     4805 | 2024-01-16 | NoCryIfLose                 | W   | 0.465      | -            | -                | -                | -             |     0.36 | aidKiT, bibu, neiter, notaN, rilax           |
|           20 |     4945 | 2024-01-12 | BEZFORMbI                   | L   | 0.439      | -            | -                | -                | -             |   -13.17 | airscape, almazer, ANASTAZE, poka, SBolt     |
|           19 |     5056 | 2024-01-10 | Viperio                     | L   | 0.426      | -            | -                | -                | -             |   -12.59 | mAnGo, MMS, pandi7o, ReegaN, zodi            |
|           18 |     5087 | 2024-01-09 | Dynamo Eclot                | W   | 0.418      | -            | -                | -                | -             |     8.50 | Cabbi, IceBerg, kwezz, Lucky, MistR          |
|           17 |     5095 | 2024-01-09 | Pera Esports                | W   | 0.418      | -            | -                | -                | -             |     4.10 | Cabbi, IceBerg, kwezz, Lucky, MistR          |
|           16 |     5308 | 2023-12-20 | NOM Esports                 | L   | 0.283      | -            | -                | -                | -             |    -7.94 | AMSALEM, BluePho3nix, dan1, ultimate, Zax1e  |
|           15 |     5318 | 2023-12-19 | Ex-Anonymo Esports          | L   | 0.277      | -            | -                | -                | -             |    -7.34 | lunAtic, reiko, SaMey, Sobol, virtuoso       |
|           14 |     5382 | 2023-12-17 | Turów Zgorzelec Esport      | W   | 0.263      | -            | -                | -                | -             |     1.55 | b1elany, darko, gRuChA, kadziu, Markoś       |
|           13 |     5673 | 2023-12-12 | Zero Tenacity               | W   | 0.231      | -            | -                | -                | -             |     2.48 | Cabbi, IceBerg, kwezz, Lucky, MistR          |
|           12 |     5835 | 2023-12-08 | The Witchers                | W   | 0.205      | -            | -                | -                | -             |     1.03 | Dragon, fear, Sdaim, smooya, synyx           |
|           11 |     6000 | 2023-12-05 | EYEBALLERS                  | L   | 0.184      | -            | -                | -                | -             |    -3.97 | Cabbi, IceBerg, kwezz, Lucky, MistR          |
|           10 |     6271 | 2023-11-29 | Alliance                    | L   | 0.144      | -            | -                | -                | -             |    -3.44 | avid, b0denmaster, PlesseN, robiin, twist    |
|            9 |     6448 | 2023-11-25 | Preasy Esport               | L   | 0.116      | -            | -                | -                | -             |    -2.50 | Cabbi, IceBerg, kristou, kwezz, Lucky        |
|            8 |     6527 | 2023-11-23 | SAW                         | L   | 0.104      | -            | -                | -                | -             |    -0.33 | Anlelele, Cabbi, IceBerg, kwezz, Lucky       |
|            7 |     6643 | 2023-11-20 | Pera Esports                | L   | 0.085      | -            | -                | -                | -             |    -2.40 | Anlelele, Cabbi, IceBerg, kwezz, Lucky       |
|            6 |     6676 | 2023-11-19 | ARCRED                      | W   | 0.077      | -            | -                | -                | -             |     0.45 | 1NVISIBLEE, DSSj, hurtslxrd, Ryujin, shg     |
|            5 |     6733 | 2023-11-18 | MOUZ NXT                    | W   | 0.071      | -            | -                | -                | -             |     1.12 | Anlelele, Cabbi, IceBerg, kwezz, Lucky       |
|            4 |     6785 | 2023-11-17 | GenOne                      | W   | 0.064      | -            | -                | -                | -             |     0.14 | Anlelele, Cabbi, IceBerg, kwezz, Lucky       |
|            3 |     6842 | 2023-11-16 | Alliance                    | L   | 0.057      | -            | -                | -                | -             |    -1.36 | Anlelele, Cabbi, IceBerg, kwezz, Lucky       |
|            2 |     6932 | 2023-11-14 | Sprout                      | W   | 0.044      | -            | -                | -                | -             |     0.13 | Anlelele, Cabbi, IceBerg, kwezz, Lucky       |
|            1 |     7053 | 2023-11-11 | B8                          | L   | 0.025      | -            | -                | -                | -             |    -0.73 | amster, cptkurtka023, npl, OWNER, r1nkle     |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($30,532.78)
- Divide that value by the 5th highest value among all rosters ($158,437.64)
- The final value (0.19) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-05-02 |      1.000 | $12,500.00     | $12,500.00      |
| 2024-04-27 |      1.000 | $6,421.58      | $6,421.58       |
| 2024-04-06 |      1.000 | $5,000.00      | $5,000.00       |
| 2024-03-25 |      0.925 | $7,000.00      | $6,472.73       |
| 2023-11-21 |      0.092 | $1,500.00      | $138.47         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
