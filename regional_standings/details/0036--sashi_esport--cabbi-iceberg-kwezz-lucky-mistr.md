### Roster Details<br />
Team Name: Sashi Esport<br />
Roster: Cabbi, IceBerg, kwezz, Lucky, MistR<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [36](../standings_global.md)<br />
Regional Rank: [26]( ../standings_europe.md)<br />
Final Rank Value:  1175.2<br />
<br />
Final Rank Value (1175.2) = Starting Rank Value (1075.7) + Head To Head Adjustments (99.5)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.566[<sup>1</sup>](#table2)
- Bounty Collected: 0.464[<sup>2</sup>](#table1)
- Opponent Network: 0.298[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.332<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1075.7
- 400 + ( ( 0.332 - 0.000 ) / ( 0.786 - 0.000 ) ) * 1600 = 1075.7


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent                  | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                       |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|          137 |      160 | 2024-05-27 | IMMAPROBLEM               | W   | 1.000      | -            | -                | -                | 0 (0.000) |     1.07 | Cabbi, IceBerg, kwezz, Lucky, MistR          |
|          136 |      166 | 2024-05-27 | WOPA Esport               | L   | 1.000      | -            | -                | -                | -         |   -29.11 | Cabbi, IceBerg, kwezz, Lucky, MistR          |
|          135 |      171 | 2024-05-27 | Astralis Talent           | W   | 1.000      | -            | -                | -                | 0 (0.000) |     2.45 | Cabbi, IceBerg, kwezz, Lucky, MistR          |
|          134 |      176 | 2024-05-27 | Preasy Esport             | L   | 1.000      | -            | -                | -                | -         |   -29.66 | Cabbi, IceBerg, kwezz, Lucky, MistR          |
|          133 |      182 | 2024-05-27 | Copenhagen Wolves         | W   | 1.000      | -            | -                | -                | 0 (0.000) |     1.34 | Cabbi, IceBerg, kwezz, Lucky, MistR          |
|          132 |      581 | 2024-05-21 | XI Esport                 | W   | 1.000      | -            | -                | -                | 0 (0.000) |     1.43 | Cabbi, IceBerg, kwezz, Lucky, MistR          |
|          131 |      656 | 2024-05-20 | Sashi Academy             | W   | 1.000      | -            | -                | -                | 0 (0.000) |     0.73 | Cabbi, IceBerg, kwezz, Lucky, MistR          |
|          130 |      721 | 2024-05-20 | Monte                     | L   | 1.000      | -            | -                | -                | -         |   -14.57 | Cabbi, IceBerg, kwezz, Lucky, MistR          |
|          129 |      751 | 2024-05-19 | Passion UA                | W   | 1.000      | 0.500        | -                | 1.000 (0.500)    | 0 (0.000) |     4.96 | Cabbi, IceBerg, kwezz, Lucky, MistR          |
|          128 |      859 | 2024-05-18 | B8                        | L   | 1.000      | -            | -                | -                | -         |   -19.10 | Cabbi, IceBerg, kwezz, Lucky, MistR          |
|          127 |      901 | 2024-05-18 | Monte                     | W   | 1.000      | 0.384        | 0.181 (0.069)    | -                | 0 (0.000) |    16.39 | Cabbi, IceBerg, kwezz, Lucky, MistR          |
|          126 |      929 | 2024-05-18 | ALTERNATE aTTaX           | W   | 1.000      | 0.500        | -                | 0.679 (0.340)    | 0 (0.000) |     4.57 | Cabbi, IceBerg, kwezz, Lucky, MistR          |
|          125 |     1011 | 2024-05-17 | ex-Guild Eagles           | W   | 1.000      | -            | -                | -                | 0 (0.000) |     5.08 | Cabbi, IceBerg, kwezz, Lucky, MistR          |
|          124 |     1104 | 2024-05-16 | Passion UA                | L   | 1.000      | -            | -                | -                | -         |   -27.30 | Cabbi, IceBerg, kwezz, Lucky, MistR          |
|          123 |     1200 | 2024-05-15 | Endpoint                  | W   | 1.000      | 0.384        | -                | 0.718 (0.276)    | 0 (0.000) |     4.26 | Cabbi, IceBerg, kwezz, Lucky, MistR          |
|          122 |     1577 | 2024-05-09 | 1win                      | W   | 1.000      | -            | -                | -                | -         |     8.24 | Cabbi, IceBerg, kwezz, Lucky, MistR          |
|          121 |     1629 | 2024-05-08 | Copenhagen Wolves         | L   | 1.000      | -            | -                | -                | -         |   -30.63 | Cabbi, IceBerg, kwezz, Lucky, MistR          |
|          120 |     1646 | 2024-05-08 | Grannys Knockers          | W   | 1.000      | -            | -                | -                | -         |     2.96 | Cabbi, IceBerg, kwezz, Lucky, MistR          |
|          119 |     1667 | 2024-05-07 | Astralis Talent           | W   | 1.000      | -            | -                | -                | -         |     1.79 | Cabbi, IceBerg, kwezz, Lucky, MistR          |
|          118 |     1672 | 2024-05-07 | XI Esport                 | W   | 1.000      | -            | -                | -                | -         |     0.93 | Cabbi, IceBerg, kwezz, Lucky, MistR          |
|          117 |     1690 | 2024-05-07 | 9Pandas                   | W   | 1.000      | -            | -                | -                | -         |     7.98 | Cabbi, IceBerg, kwezz, Lucky, MistR          |
|          116 |     1726 | 2024-05-06 | ALTERNATE aTTaX           | W   | 1.000      | -            | -                | -                | -         |     4.86 | Cabbi, IceBerg, kwezz, Lucky, MistR          |
|          115 |     1761 | 2024-05-05 | Gaimin Gladiators         | L   | 1.000      | -            | -                | -                | -         |   -20.08 | Cabbi, IceBerg, kwezz, Lucky, MistR          |
|          114 |     1772 | 2024-05-05 | Come on now dawg          | W   | 1.000      | -            | -                | -                | -         |     0.48 | Cabbi, IceBerg, kwezz, Lucky, MistR          |
|          113 |     1786 | 2024-05-05 | MASONIC                   | W   | 1.000      | -            | -                | -                | -         |     3.04 | Cabbi, IceBerg, kwezz, Lucky, MistR          |
|          112 |     1918 | 2024-05-02 | Fnatic                    | W   | 1.000      | 0.384        | 0.147 (0.057)    | -                | -         |    12.02 | Cabbi, IceBerg, kwezz, Lucky, MistR          |
|          111 |     2000 | 2024-05-01 | 3DMAX                     | W   | 1.000      | 0.384        | 0.106 (0.041)    | -                | -         |     5.11 | Cabbi, IceBerg, kwezz, Lucky, MistR          |
|          110 |     2033 | 2024-04-30 | OG                        | W   | 1.000      | 0.384        | 0.277 (0.106)    | -                | -         |    16.65 | Cabbi, IceBerg, kwezz, Lucky, MistR          |
|          109 |     2053 | 2024-04-29 | Sashi Academy             | W   | 0.998      | -            | -                | -                | -         |     0.87 | Cabbi, IceBerg, kwezz, Lucky, MistR          |
|          108 |     2057 | 2024-04-29 | Preasy Esport             | W   | 0.997      | -            | -                | -                | -         |     1.80 | Cabbi, IceBerg, kwezz, Lucky, MistR          |
|          107 |     2069 | 2024-04-29 | WOPA Esport               | W   | 0.997      | -            | -                | -                | -         |     2.09 | Cabbi, IceBerg, kwezz, Lucky, MistR          |
|          106 |     2081 | 2024-04-29 | 500                       | W   | 0.995      | -            | -                | -                | -         |     3.10 | Cabbi, IceBerg, kwezz, Lucky, MistR          |
|          105 |     2162 | 2024-04-27 | 777 Esports               | W   | 0.984      | -            | -                | -                | -         |     2.12 | Cabbi, IceBerg, kwezz, Lucky, MistR          |
|          104 |     2175 | 2024-04-27 | JANO Esports              | W   | 0.984      | -            | -                | -                | -         |     1.54 | Cabbi, IceBerg, kwezz, Lucky, MistR          |
|          103 |     2236 | 2024-04-26 | JANO Esports              | W   | 0.978      | -            | -                | -                | -         |     1.69 | Cabbi, IceBerg, kwezz, Lucky, MistR          |
|          102 |     2239 | 2024-04-26 | 777 Esports               | W   | 0.978      | -            | -                | -                | -         |     2.02 | Cabbi, IceBerg, kwezz, Lucky, MistR          |
|          101 |     2244 | 2024-04-26 | Preasy Esport             | W   | 0.977      | -            | -                | -                | -         |     1.96 | Cabbi, IceBerg, kwezz, Lucky, MistR          |
|          100 |     2250 | 2024-04-26 | Esport Harte              | W   | 0.977      | -            | -                | -                | -         |     0.75 | Cabbi, IceBerg, kwezz, Lucky, MistR          |
|           99 |     2257 | 2024-04-26 | Static                    | W   | 0.977      | -            | -                | -                | -         |     0.71 | Cabbi, IceBerg, kwezz, Lucky, MistR          |
|           98 |     2329 | 2024-04-25 | Passion UA                | W   | 0.969      | 0.384        | -                | 1.000 (0.372)    | -         |     4.95 | Cabbi, IceBerg, kwezz, Lucky, MistR          |
|           97 |     2426 | 2024-04-23 | Gaimin Gladiators         | W   | 0.956      | 0.384        | 0.092 (0.034)    | 0.711 (0.261)    | -         |    17.14 | Cabbi, IceBerg, kwezz, Lucky, MistR          |
|           96 |     2433 | 2024-04-23 | BLEED Esports             | W   | 0.955      | 0.384        | 0.248 (0.091)    | 0.677 (0.249)    | -         |    17.35 | Cabbi, IceBerg, kwezz, Lucky, MistR          |
|           95 |     2572 | 2024-04-20 | Eternal Fire              | W   | 0.937      | 0.143        | 1.000 (0.134)    | -                | -         |    28.83 | Cabbi, IceBerg, kwezz, Lucky, MistR          |
|           94 |     2602 | 2024-04-20 | Cloud9                    | W   | 0.936      | -            | -                | -                | -         |    26.04 | Cabbi, IceBerg, kwezz, Lucky, MistR          |
|           93 |     2690 | 2024-04-19 | Eternal Fire              | L   | 0.930      | -            | -                | -                | -         |    -0.52 | Cabbi, IceBerg, kwezz, Lucky, MistR          |
|           92 |     2714 | 2024-04-19 | Cloud9                    | W   | 0.929      | -            | -                | -                | -         |    26.53 | Cabbi, IceBerg, kwezz, Lucky, MistR          |
|           91 |     2749 | 2024-04-18 | ex-Guild Eagles           | W   | 0.924      | -            | -                | -                | -         |    10.20 | Cabbi, IceBerg, kwezz, Lucky, MistR          |
|           90 |     2754 | 2024-04-18 | RUBY                      | W   | 0.924      | -            | -                | -                | -         |    10.11 | Cabbi, IceBerg, kwezz, Lucky, MistR          |
|           89 |     2767 | 2024-04-18 | GamerLegion               | W   | 0.923      | 0.143        | 0.224 (0.030)    | -                | -         |    20.22 | Cabbi, IceBerg, kwezz, Lucky, MistR          |
|           88 |     2819 | 2024-04-17 | 9Pandas                   | W   | 0.918      | -            | -                | -                | -         |    15.87 | Cabbi, IceBerg, kwezz, Lucky, MistR          |
|           87 |     2851 | 2024-04-17 | Passion UA                | L   | 0.916      | -            | -                | -                | -         |   -19.51 | Cabbi, IceBerg, kwezz, Lucky, MistR          |
|           86 |     2919 | 2024-04-16 | ex-Guild Eagles           | L   | 0.909      | -            | -                | -                | -         |   -18.73 | Cabbi, IceBerg, kwezz, Lucky, MistR          |
|           85 |     2939 | 2024-04-15 | IMMAPROBLEM               | W   | 0.904      | -            | -                | -                | -         |     1.34 | Cabbi, IceBerg, kwezz, Lucky, MistR          |
|           84 |     3424 | 2024-04-06 | UNiTY esports             | W   | 0.841      | -            | -                | -                | -         |     6.49 | K1-FiDa, Levi, M1key, NIO, Pechyn            |
|           83 |     3517 | 2024-04-04 | UNiTY esports             | W   | 0.829      | -            | -                | -                | -         |     7.16 | K1-FiDa, Levi, M1key, NIO, Pechyn            |
|           82 |     3617 | 2024-04-02 | Permitta Esports          | W   | 0.814      | 0.333        | -                | 1.000 (0.271)    | -         |     8.57 | Cabbi, IceBerg, kwezz, Lucky, MistR          |
|           81 |     3685 | 2024-03-30 | ex-Turów Zgorzelec Esport | W   | 0.796      | -            | -                | -                | -         |     4.27 | darko, EXUS, kadziu, Markoś, Sobol           |
|           80 |     3796 | 2024-03-27 | Rebels Gaming             | L   | 0.778      | -            | -                | -                | -         |   -10.72 | Cabbi, IceBerg, kwezz, Lucky, MistR          |
|           79 |     3814 | 2024-03-27 | Pera Esports              | W   | 0.777      | -            | -                | -                | -         |     6.38 | Cabbi, IceBerg, kwezz, Lucky, MistR          |
|           78 |     3876 | 2024-03-26 | ARROW                     | W   | 0.771      | -            | -                | -                | -         |     3.03 | Kre1N, Orbit, SnacKZ1, Tionix, Twiksar       |
|           77 |     3901 | 2024-03-26 | Dynamo Eclot              | L   | 0.769      | -            | -                | -                | -         |   -12.41 | Cabbi, IceBerg, kwezz, Lucky, MistR          |
|           76 |     3924 | 2024-03-25 | Nexus Gaming              | W   | 0.764      | 0.371        | -                | 0.825 (0.234)    | -         |     8.66 | Cabbi, IceBerg, kwezz, Lucky, MistR          |
|           75 |     4032 | 2024-03-22 | Nemiga Gaming             | W   | 0.744      | 0.371        | 0.366 (0.101)    | 0.830 (0.230)    | -         |    16.91 | Cabbi, IceBerg, kwezz, Lucky, MistR          |
|           74 |     4046 | 2024-03-22 | Viperio                   | W   | 0.742      | -            | -                | -                | -         |     2.34 | mAnGo, MMS, pandi7o, ReegaN, zodi            |
|           73 |     4168 | 2024-03-19 | RUBY                      | W   | 0.724      | -            | -                | -                | -         |     8.25 | Cabbi, IceBerg, kwezz, Lucky, MistR          |
|           72 |     4215 | 2024-03-18 | Insilio                   | W   | 0.716      | -            | -                | -                | -         |     9.74 | faydett, FpSSS, Pipw, Polt, sugaR            |
|           71 |     4625 | 2024-03-11 | Nemiga Gaming             | L   | 0.670      | -            | -                | -                | -         |    -4.89 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r         |
|           70 |     4674 | 2024-03-10 | Team Sampi                | L   | 0.662      | -            | -                | -                | -         |   -12.92 | Cabbi, IceBerg, kwezz, Lucky, MistR          |
|           69 |     4734 | 2024-03-09 | Permitta Esports          | W   | 0.656      | 0.371        | -                | 1.000 (0.244)    | -         |     8.82 | bnox, maaryy, mASKED, morelz, Vegi           |
|           68 |     4768 | 2024-03-08 | ALTERNATE aTTaX           | L   | 0.648      | -            | -                | -                | -         |   -13.11 | ArroW, awzek, FreeZe, hyped, skyye           |
|           67 |     4801 | 2024-03-07 | Insilio                   | W   | 0.645      | -            | -                | -                | -         |     7.88 | faydett, FpSSS, Pipw, Polt, sugaR            |
|           66 |     4955 | 2024-03-05 | Johnny Speeds             | L   | 0.631      | -            | -                | -                | -         |   -10.72 | Cabbi, IceBerg, kwezz, Lucky, MistR          |
|           65 |     5018 | 2024-03-04 | Team QUAZAR               | W   | 0.625      | -            | -                | -                | -         |     0.51 | Electro, KarmaN, kirito, LVF, xnkka          |
|           64 |     5056 | 2024-03-04 | Entropiq                  | L   | 0.622      | -            | -                | -                | -         |   -17.14 | c0llins, Marix, mwlky, Oxygen, tiziaN        |
|           63 |     5152 | 2024-03-02 | The Chosen Few            | L   | 0.611      | -            | -                | -                | -         |   -16.25 | choiv7, KalubeR, shaiK, Skrimo, SPELLAN      |
|           62 |     5198 | 2024-03-02 | brazylijski luz           | W   | 0.609      | -            | -                | -                | -         |     2.88 | Furlan, phr, POLO, Prism, Qlocuu             |
|           61 |     5257 | 2024-02-29 | MOUZ NXT                  | W   | 0.598      | 0.371        | 0.157 (0.035)    | -                | -         |    10.50 | Cabbi, IceBerg, kwezz, Lucky, MistR          |
|           60 |     5267 | 2024-02-29 | Permitta Esports          | W   | 0.597      | -            | -                | -                | -         |     7.17 | bnox, maaryy, mASKED, morelz, Vegi           |
|           59 |     5367 | 2024-02-27 | V1dar Gaming              | L   | 0.584      | -            | -                | -                | -         |   -16.32 | Cabbi, IceBerg, kwezz, Lucky, MistR          |
|           58 |     5401 | 2024-02-26 | Betera Esports            | W   | 0.578      | -            | -                | -                | -         |     3.86 | alex666, lollipop21k, MaSvAl, nifee, sad     |
|           57 |     5443 | 2024-02-25 | Sangal Esports            | L   | 0.571      | -            | -                | -                | -         |   -10.34 | Cabbi, IceBerg, kwezz, Lucky, MistR          |
|           56 |     5463 | 2024-02-25 | ex-Turów Zgorzelec Esport | L   | 0.569      | -            | -                | -                | -         |   -15.19 | AxEcHo, darko, kadziu, Markoś, xKacpersky    |
|           55 |     5576 | 2024-02-24 | MOUZ NXT                  | L   | 0.562      | -            | -                | -                | -         |    -8.84 | Cabbi, IceBerg, kwezz, Lucky, MistR          |
|           54 |     5602 | 2024-02-23 | VP.Prodigy                | W   | 0.558      | -            | -                | -                | -         |     3.24 | dwushka, KusMe, shady, Something, xdENiSZERA |
|           53 |     5607 | 2024-02-23 | FAVBET Team               | W   | 0.557      | -            | -                | -                | -         |     2.91 | Cabbi, IceBerg, kwezz, Lucky, MistR          |
|           52 |     5731 | 2024-02-21 | Team Sampi                | W   | 0.543      | -            | -                | -                | -         |     5.13 | Cabbi, IceBerg, kwezz, Lucky, MistR          |
|           51 |     5740 | 2024-02-21 | Verdant                   | W   | 0.542      | -            | -                | -                | -         |     6.26 | arTisT, Ducky, Girafffe, Vacancy, Zax1e      |
|           50 |     5831 | 2024-02-19 | Aurora Young Blud         | W   | 0.531      | -            | -                | -                | -         |     2.67 | Cabbi, IceBerg, kwezz, Lucky, MistR          |
|           49 |     5948 | 2024-02-17 | Zero Tenacity             | W   | 0.517      | -            | -                | -                | -         |     7.09 | Cabbi, IceBerg, kwezz, Lucky, MistR          |
|           48 |     6001 | 2024-02-16 | Permitta Esports          | W   | 0.509      | -            | -                | -                | -         |     5.34 | bnox, maaryy, mASKED, morelz, Vegi           |
|           47 |     6152 | 2024-02-13 | HOTU                      | W   | 0.491      | -            | -                | -                | -         |     3.46 | Cabbi, IceBerg, kwezz, Lucky, MistR          |
|           46 |     6220 | 2024-02-12 | Astralis Talent           | W   | 0.482      | -            | -                | -                | -         |     4.81 | ANSG1, JBOEN, kiR, kroK, tOPZ                |
|           45 |     6246 | 2024-02-11 | ARCRED                    | W   | 0.476      | -            | -                | -                | -         |     2.51 | Cabbi, IceBerg, kwezz, Lucky, MistR          |
|           44 |     6253 | 2024-02-10 | Nemiga Gaming             | L   | 0.471      | -            | -                | -                | -         |    -3.66 | Cabbi, IceBerg, kwezz, Lucky, MistR          |
|           43 |     6275 | 2024-02-10 | AMKAL ESPORTS             | W   | 0.470      | -            | -                | -                | -         |    10.37 | Cabbi, IceBerg, kwezz, Lucky, MistR          |
|           42 |     6292 | 2024-02-09 | FORZE Esports             | W   | 0.464      | -            | -                | -                | -         |     6.13 | Cabbi, IceBerg, kwezz, Lucky, MistR          |
|           41 |     6306 | 2024-02-09 | Insilio                   | W   | 0.463      | -            | -                | -                | -         |     5.51 | faydett, FpSSS, Pipw, Polt, sugaR            |
|           40 |     6322 | 2024-02-08 | Nemiga Gaming             | L   | 0.458      | -            | -                | -                | -         |    -3.42 | Cabbi, IceBerg, kwezz, Lucky, MistR          |
|           39 |     6336 | 2024-02-08 | FORZE Esports             | W   | 0.457      | -            | -                | -                | -         |     5.93 | gokushima, r3salt, SELLTER, shalfey, tN1R    |
|           38 |     6354 | 2024-02-07 | Team Spirit Academy       | W   | 0.451      | -            | -                | -                | -         |     2.41 | Cabbi, IceBerg, kwezz, Lucky, MistR          |
|           37 |     6360 | 2024-02-07 | Insilio                   | L   | 0.451      | -            | -                | -                | -         |    -9.05 | Cabbi, IceBerg, kwezz, Lucky, MistR          |
|           36 |     6367 | 2024-02-07 | BIG Academy               | L   | 0.449      | -            | -                | -                | -         |   -12.21 | Cabbi, IceBerg, kwezz, Lucky, MistR          |
|           35 |     6425 | 2024-02-05 | L&G                       | W   | 0.437      | -            | -                | -                | -         |     0.65 | Cabbi, IceBerg, kwezz, Lucky, MistR          |
|           34 |     6467 | 2024-02-04 | TOOMUCHVIDEOGAMES         | L   | 0.429      | -            | -                | -                | -         |   -12.89 | Cabbi, IceBerg, kwezz, Lucky, MistR          |
|           33 |     6496 | 2024-02-03 | showmakerz                | W   | 0.424      | -            | -                | -                | -         |     0.79 | Cabbi, IceBerg, kwezz, Lucky, MistR          |
|           32 |     6502 | 2024-02-03 | Gaimin Gladiators         | W   | 0.424      | -            | -                | -                | -         |     9.95 | Cabbi, IceBerg, kwezz, Lucky, MistR          |
|           31 |     6515 | 2024-02-03 | EYEBALLERS                | W   | 0.424      | -            | -                | -                | -         |     4.14 | Cabbi, IceBerg, kwezz, Lucky, MistR          |
|           30 |     6538 | 2024-02-03 | Kappa Bar                 | W   | 0.424      | -            | -                | -                | -         |     0.63 | dezt, jayzaR, pupcake, TIM, upE              |
|           29 |     6570 | 2024-02-03 | Team Sampi                | L   | 0.422      | -            | -                | -                | -         |    -8.98 | Cabbi, IceBerg, kwezz, Lucky, MistR          |
|           28 |     6593 | 2024-02-02 | EYEBALLERS                | L   | 0.417      | -            | -                | -                | -         |    -9.34 | HEAP, JW, Peppzor, Sapec, SHiNE              |
|           27 |     6598 | 2024-02-02 | showmakerz                | W   | 0.417      | -            | -                | -                | -         |     0.67 | Cabbi, IceBerg, kwezz, Lucky, MistR          |
|           26 |     6617 | 2024-02-02 | WOPA Esport               | W   | 0.417      | -            | -                | -                | -         |     2.39 | brzer, Gnøffe, Leakz, LUMSEN, Pellyy         |
|           25 |     6693 | 2024-02-01 | ENCE Academy              | W   | 0.409      | -            | -                | -                | -         |     2.78 | HENU, myltsi, podi, S1rva, teme              |
|           24 |     6745 | 2024-01-30 | Insilio                   | W   | 0.398      | -            | -                | -                | -         |     4.27 | faydett, FpSSS, Pipw, Polt, sugaR            |
|           23 |     6747 | 2024-01-30 | FORZE Esports             | W   | 0.398      | -            | -                | -                | -         |     1.62 | gokushima, r3salt, shalfey, sstiNiX, tN1R    |
|           22 |     6761 | 2024-01-30 | RUSH B                    | W   | 0.397      | -            | -                | -                | -         |     1.95 | Cabbi, IceBerg, kwezz, Lucky, MistR          |
|           21 |     6786 | 2024-01-29 | brazylijski luz           | W   | 0.392      | -            | -                | -                | -         |     2.48 | Furlan, phr, POLO, Prism, Qlocuu             |
|           20 |     6825 | 2024-01-29 | Sangal Esports            | W   | 0.392      | -            | -                | -                | -         |     6.53 | Ganginho, LNZ, sausol, xfl0ud, yxngstxr      |
|           19 |     6993 | 2024-01-27 | Verdant                   | W   | 0.375      | -            | -                | -                | -         |     5.55 | Cabbi, IceBerg, kwezz, Lucky, MistR          |
|           18 |     7219 | 2024-01-22 | RUBY                      | W   | 0.344      | -            | -                | -                | -         |     3.40 | dekz, Kaide, mo0n, Sowalio, w1nt3r           |
|           17 |     7229 | 2024-01-22 | FORZE Youngsters          | W   | 0.344      | -            | -                | -                | -         |     1.03 | Cabbi, IceBerg, kwezz, Lucky, MistR          |
|           16 |     7572 | 2024-01-17 | Natus Vincere Junior      | L   | 0.311      | -            | -                | -                | -         |    -8.01 | dem0n, fnl, Krabeni, Magic, makazze          |
|           15 |     7633 | 2024-01-16 | EYEBALLERS                | L   | 0.305      | -            | -                | -                | -         |    -6.62 | Cabbi, IceBerg, kwezz, Lucky, MistR          |
|           14 |     7647 | 2024-01-16 | ARCRED                    | W   | 0.304      | -            | -                | -                | -         |     1.67 | Cabbi, IceBerg, kwezz, Lucky, MistR          |
|           13 |     7665 | 2024-01-16 | NoCryIfLose               | W   | 0.304      | -            | -                | -                | -         |     0.24 | aidKiT, bibu, neiter, notaN, rilax           |
|           12 |     7869 | 2024-01-12 | BEZFORMbI                 | L   | 0.278      | -            | -                | -                | -         |    -8.34 | airscape, almazer, ANASTAZE, poka, SBolt     |
|           11 |     8020 | 2024-01-10 | Viperio                   | L   | 0.265      | -            | -                | -                | -         |    -7.83 | mAnGo, MMS, pandi7o, ReegaN, zodi            |
|           10 |     8063 | 2024-01-09 | ENTERPRISE esports        | L   | 0.258      | -            | -                | -                | -         |    -5.49 | Cabbi, IceBerg, kwezz, Lucky, MistR          |
|            9 |     8082 | 2024-01-09 | Dynamo Eclot              | W   | 0.257      | -            | -                | -                | -         |     4.41 | Cabbi, IceBerg, kwezz, Lucky, MistR          |
|            8 |     8092 | 2024-01-09 | Pera Esports              | W   | 0.257      | -            | -                | -                | -         |     2.46 | Cabbi, IceBerg, kwezz, Lucky, MistR          |
|            7 |     8116 | 2024-01-09 | showmakerz                | W   | 0.257      | -            | -                | -                | -         |     0.40 | bsover, Doobs, julle, Leon1das, majkn        |
|            6 |     8390 | 2023-12-20 | NOM Esports               | L   | 0.122      | -            | -                | -                | -         |    -3.52 | AMSALEM, BluePho3nix, dan1, ultimate, Zax1e  |
|            5 |     8402 | 2023-12-19 | ex-Anonymo Esports        | L   | 0.116      | -            | -                | -                | -         |    -3.25 | lunAtic, reiko, SaMey, Sobol, virtuoso       |
|            4 |     8488 | 2023-12-17 | ex-Turów Zgorzelec Esport | W   | 0.102      | -            | -                | -                | -         |     0.51 | b1elany, darko, gRuChA, kadziu, Markoś       |
|            3 |     8884 | 2023-12-12 | Zero Tenacity             | W   | 0.070      | -            | -                | -                | -         |     1.17 | Cabbi, IceBerg, kwezz, Lucky, MistR          |
|            2 |     9103 | 2023-12-08 | The Witchers              | W   | 0.044      | -            | -                | -                | -         |     0.16 | Dragon, fear, Sdaim, smooya, synyx           |
|            1 |     9316 | 2023-12-05 | EYEBALLERS                | L   | 0.022      | -            | -                | -                | -         |    -0.51 | Cabbi, IceBerg, kwezz, Lucky, MistR          |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($51,627.17)
- Divide that value by the 5th highest value among all rosters ($300,806.11)
- The final value (0.17) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-05-18 |      1.000 | $5,000.00      | $5,000.00       |
| 2024-05-09 |      1.000 | $18,256.44     | $18,256.44      |
| 2024-05-02 |      1.000 | $12,500.00     | $12,500.00      |
| 2024-04-27 |      0.984 | $6,421.58      | $6,319.90       |
| 2024-04-06 |      0.841 | $5,000.00      | $4,205.56       |
| 2024-03-25 |      0.764 | $7,000.00      | $5,345.28       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
