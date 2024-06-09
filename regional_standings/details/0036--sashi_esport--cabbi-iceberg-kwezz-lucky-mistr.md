### Roster Details<br />
Team Name: Sashi Esport<br />
Roster: Cabbi, IceBerg, kwezz, Lucky, MistR<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [36](../standings_global.md)<br />
Regional Rank: [26]( ../standings_europe.md)<br />
Final Rank Value:  1177.0<br />
<br />
Final Rank Value (1177.0) = Starting Rank Value (1075.5) + Head To Head Adjustments (101.5)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.552[<sup>1</sup>](#table2)
- Bounty Collected: 0.463[<sup>2</sup>](#table1)
- Opponent Network: 0.314[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.332<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1075.5
- 400 + ( ( 0.332 - 0.000 ) / ( 0.787 - 0.000 ) ) * 1600 = 1075.5


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
|          152 |      167 | 2024-05-27 | IMMAPROBLEM               | W   | 1.000      | -            | -                | -                | 0 (0.000) |     1.02 | Cabbi, IceBerg, kwezz, Lucky, MistR          |
|          151 |      174 | 2024-05-27 | WOPA Esport               | L   | 1.000      | -            | -                | -                | -         |   -29.26 | Cabbi, IceBerg, kwezz, Lucky, MistR          |
|          150 |      179 | 2024-05-27 | Astralis Talent           | W   | 1.000      | -            | -                | -                | 0 (0.000) |     2.49 | Cabbi, IceBerg, kwezz, Lucky, MistR          |
|          149 |      184 | 2024-05-27 | Preasy Esport             | L   | 1.000      | -            | -                | -                | -         |   -29.66 | Cabbi, IceBerg, kwezz, Lucky, MistR          |
|          148 |      190 | 2024-05-27 | Copenhagen Wolves         | W   | 1.000      | -            | -                | -                | 0 (0.000) |     1.62 | Cabbi, IceBerg, kwezz, Lucky, MistR          |
|          147 |      592 | 2024-05-21 | XI Esport                 | W   | 1.000      | -            | -                | -                | 0 (0.000) |     1.45 | Cabbi, IceBerg, kwezz, Lucky, MistR          |
|          146 |      667 | 2024-05-20 | Sashi Academy             | W   | 1.000      | -            | -                | -                | 0 (0.000) |     0.74 | Cabbi, IceBerg, kwezz, Lucky, MistR          |
|          145 |      733 | 2024-05-20 | Monte                     | L   | 1.000      | -            | -                | -                | -         |   -14.38 | Cabbi, IceBerg, kwezz, Lucky, MistR          |
|          144 |      763 | 2024-05-19 | Passion UA                | W   | 1.000      | 0.500        | -                | 1.000 (0.500)    | 0 (0.000) |     5.15 | Cabbi, IceBerg, kwezz, Lucky, MistR          |
|          143 |      871 | 2024-05-18 | B8                        | L   | 1.000      | -            | -                | -                | -         |   -19.35 | Cabbi, IceBerg, kwezz, Lucky, MistR          |
|          142 |      913 | 2024-05-18 | Monte                     | W   | 1.000      | 0.384        | 0.181 (0.069)    | -                | 0 (0.000) |    16.60 | Cabbi, IceBerg, kwezz, Lucky, MistR          |
|          141 |      941 | 2024-05-18 | ALTERNATE aTTaX           | W   | 1.000      | 0.500        | -                | 0.735 (0.368)    | 0 (0.000) |     4.59 | Cabbi, IceBerg, kwezz, Lucky, MistR          |
|          140 |     1023 | 2024-05-17 | ex-Guild Eagles           | W   | 1.000      | -            | -                | -                | 0 (0.000) |     5.14 | Cabbi, IceBerg, kwezz, Lucky, MistR          |
|          139 |     1114 | 2024-05-16 | Passion UA                | L   | 1.000      | -            | -                | -                | -         |   -27.11 | Cabbi, IceBerg, kwezz, Lucky, MistR          |
|          138 |     1210 | 2024-05-15 | Endpoint                  | W   | 1.000      | 0.384        | -                | 0.770 (0.296)    | 0 (0.000) |     4.65 | Cabbi, IceBerg, kwezz, Lucky, MistR          |
|          137 |     1593 | 2024-05-09 | 1win                      | W   | 1.000      | -            | -                | -                | -         |     8.13 | Cabbi, IceBerg, kwezz, Lucky, MistR          |
|          136 |     1646 | 2024-05-08 | Copenhagen Wolves         | L   | 1.000      | -            | -                | -                | -         |   -30.33 | Cabbi, IceBerg, kwezz, Lucky, MistR          |
|          135 |     1664 | 2024-05-08 | Grannys Knockers          | W   | 1.000      | -            | -                | -                | -         |     3.19 | Cabbi, IceBerg, kwezz, Lucky, MistR          |
|          134 |     1685 | 2024-05-07 | Astralis Talent           | W   | 1.000      | -            | -                | -                | -         |     1.84 | Cabbi, IceBerg, kwezz, Lucky, MistR          |
|          133 |     1690 | 2024-05-07 | XI Esport                 | W   | 1.000      | -            | -                | -                | -         |     0.95 | Cabbi, IceBerg, kwezz, Lucky, MistR          |
|          132 |     1710 | 2024-05-07 | 9Pandas                   | W   | 1.000      | -            | -                | -                | -         |     8.34 | Cabbi, IceBerg, kwezz, Lucky, MistR          |
|          131 |     1748 | 2024-05-06 | ALTERNATE aTTaX           | W   | 1.000      | -            | -                | -                | -         |     4.91 | Cabbi, IceBerg, kwezz, Lucky, MistR          |
|          130 |     1784 | 2024-05-05 | Gaimin Gladiators         | L   | 1.000      | -            | -                | -                | -         |   -19.93 | Cabbi, IceBerg, kwezz, Lucky, MistR          |
|          129 |     1795 | 2024-05-05 | Come on now dawg          | W   | 1.000      | -            | -                | -                | -         |     0.49 | Cabbi, IceBerg, kwezz, Lucky, MistR          |
|          128 |     1809 | 2024-05-05 | MASONIC                   | W   | 1.000      | -            | -                | -                | -         |     3.06 | Cabbi, IceBerg, kwezz, Lucky, MistR          |
|          127 |     1945 | 2024-05-02 | Fnatic                    | W   | 1.000      | 0.384        | 0.147 (0.057)    | -                | -         |    12.10 | Cabbi, IceBerg, kwezz, Lucky, MistR          |
|          126 |     2031 | 2024-05-01 | 3DMAX                     | W   | 1.000      | 0.384        | 0.106 (0.041)    | -                | -         |     5.47 | Cabbi, IceBerg, kwezz, Lucky, MistR          |
|          125 |     2066 | 2024-04-30 | OG                        | W   | 1.000      | 0.384        | 0.277 (0.106)    | -                | -         |    16.59 | Cabbi, IceBerg, kwezz, Lucky, MistR          |
|          124 |     2087 | 2024-04-29 | Sashi Academy             | W   | 0.998      | -            | -                | -                | -         |     0.90 | Cabbi, IceBerg, kwezz, Lucky, MistR          |
|          123 |     2091 | 2024-04-29 | Preasy Esport             | W   | 0.997      | -            | -                | -                | -         |     1.85 | Cabbi, IceBerg, kwezz, Lucky, MistR          |
|          122 |     2104 | 2024-04-29 | WOPA Esport               | W   | 0.997      | -            | -                | -                | -         |     2.11 | Cabbi, IceBerg, kwezz, Lucky, MistR          |
|          121 |     2116 | 2024-04-29 | 500                       | W   | 0.995      | -            | -                | -                | -         |     3.20 | Cabbi, IceBerg, kwezz, Lucky, MistR          |
|          120 |     2197 | 2024-04-27 | 777 Esports               | W   | 0.984      | -            | -                | -                | -         |     2.16 | Cabbi, IceBerg, kwezz, Lucky, MistR          |
|          119 |     2210 | 2024-04-27 | JANO Esports              | W   | 0.984      | -            | -                | -                | -         |     1.67 | Cabbi, IceBerg, kwezz, Lucky, MistR          |
|          118 |     2272 | 2024-04-26 | JANO Esports              | W   | 0.978      | -            | -                | -                | -         |     1.83 | Cabbi, IceBerg, kwezz, Lucky, MistR          |
|          117 |     2275 | 2024-04-26 | 777 Esports               | W   | 0.978      | -            | -                | -                | -         |     2.06 | Cabbi, IceBerg, kwezz, Lucky, MistR          |
|          116 |     2280 | 2024-04-26 | Preasy Esport             | W   | 0.977      | -            | -                | -                | -         |     2.02 | Cabbi, IceBerg, kwezz, Lucky, MistR          |
|          115 |     2286 | 2024-04-26 | Esport Harte              | W   | 0.977      | -            | -                | -                | -         |     0.76 | Cabbi, IceBerg, kwezz, Lucky, MistR          |
|          114 |     2293 | 2024-04-26 | Static                    | W   | 0.977      | -            | -                | -                | -         |     0.72 | Cabbi, IceBerg, kwezz, Lucky, MistR          |
|          113 |     2370 | 2024-04-25 | Passion UA                | W   | 0.969      | 0.384        | -                | 1.000 (0.372)    | -         |     5.36 | Cabbi, IceBerg, kwezz, Lucky, MistR          |
|          112 |     2474 | 2024-04-23 | Gaimin Gladiators         | W   | 0.956      | 0.384        | 0.092 (0.034)    | 0.727 (0.267)    | -         |    17.37 | Cabbi, IceBerg, kwezz, Lucky, MistR          |
|          111 |     2481 | 2024-04-23 | BLEED Esports             | W   | 0.955      | 0.384        | 0.248 (0.091)    | 0.714 (0.262)    | -         |    17.31 | Cabbi, IceBerg, kwezz, Lucky, MistR          |
|          110 |     2625 | 2024-04-20 | Eternal Fire              | W   | 0.937      | 0.143        | 1.000 (0.134)    | -                | -         |    28.84 | Cabbi, IceBerg, kwezz, Lucky, MistR          |
|          109 |     2656 | 2024-04-20 | Cloud9                    | W   | 0.936      | -            | -                | -                | -         |    26.07 | Cabbi, IceBerg, kwezz, Lucky, MistR          |
|          108 |     2746 | 2024-04-19 | Eternal Fire              | L   | 0.930      | -            | -                | -                | -         |    -0.51 | Cabbi, IceBerg, kwezz, Lucky, MistR          |
|          107 |     2770 | 2024-04-19 | Cloud9                    | W   | 0.929      | -            | -                | -                | -         |    26.56 | Cabbi, IceBerg, kwezz, Lucky, MistR          |
|          106 |     2805 | 2024-04-18 | ex-Guild Eagles           | W   | 0.924      | -            | -                | -                | -         |    10.47 | Cabbi, IceBerg, kwezz, Lucky, MistR          |
|          105 |     2810 | 2024-04-18 | RUBY                      | W   | 0.924      | -            | -                | -                | -         |    10.27 | Cabbi, IceBerg, kwezz, Lucky, MistR          |
|          104 |     2823 | 2024-04-18 | GamerLegion               | W   | 0.923      | 0.143        | 0.224 (0.030)    | -                | -         |    20.24 | Cabbi, IceBerg, kwezz, Lucky, MistR          |
|          103 |     2876 | 2024-04-17 | 9Pandas                   | W   | 0.918      | -            | -                | -                | -         |    16.51 | Cabbi, IceBerg, kwezz, Lucky, MistR          |
|          102 |     2908 | 2024-04-17 | Passion UA                | L   | 0.916      | -            | -                | -                | -         |   -18.59 | Cabbi, IceBerg, kwezz, Lucky, MistR          |
|          101 |     2980 | 2024-04-16 | ex-Guild Eagles           | L   | 0.909      | -            | -                | -                | -         |   -18.38 | Cabbi, IceBerg, kwezz, Lucky, MistR          |
|          100 |     3000 | 2024-04-15 | IMMAPROBLEM               | W   | 0.904      | -            | -                | -                | -         |     1.38 | Cabbi, IceBerg, kwezz, Lucky, MistR          |
|           99 |     3026 | 2024-04-15 | Grannys Knockers          | W   | 0.902      | -            | -                | -                | -         |     6.13 | Cabbi, IceBerg, kwezz, Lucky, MistR          |
|           98 |     3060 | 2024-04-14 | UNiTY esports             | W   | 0.894      | 0.371        | -                | 0.766 (0.254)    | -         |     6.65 | Cabbi, IceBerg, kwezz, Lucky, MistR          |
|           97 |     3204 | 2024-04-11 | ENTERPRISE esports        | W   | 0.875      | 0.384        | -                | 0.898 (0.302)    | -         |     8.95 | Cabbi, IceBerg, kwezz, Lucky, MistR          |
|           96 |     3273 | 2024-04-10 | Passion UA                | L   | 0.869      | -            | -                | -                | -         |   -18.03 | fear, jackasmo, jambo, s-chilla, zeRRoFIX    |
|           95 |     3508 | 2024-04-06 | UNiTY esports             | W   | 0.841      | -            | -                | -                | -         |     6.71 | K1-FiDa, Levi, M1key, NIO, Pechyn            |
|           94 |     3603 | 2024-04-04 | UNiTY esports             | W   | 0.829      | -            | -                | -                | -         |     7.40 | K1-FiDa, Levi, M1key, NIO, Pechyn            |
|           93 |     3707 | 2024-04-02 | Permitta Esports          | W   | 0.814      | 0.333        | -                | 1.000 (0.271)    | -         |     9.27 | Cabbi, IceBerg, kwezz, Lucky, MistR          |
|           92 |     3724 | 2024-04-01 | Nexus Gaming              | L   | 0.808      | -            | -                | -                | -         |   -16.48 | Cabbi, IceBerg, kwezz, Lucky, MistR          |
|           91 |     3778 | 2024-03-30 | ex-Turów Zgorzelec Esport | W   | 0.796      | -            | -                | -                | -         |     4.26 | darko, EXUS, kadziu, Markoś, Sobol           |
|           90 |     3889 | 2024-03-27 | Rebels Gaming             | L   | 0.778      | -            | -                | -                | -         |   -10.66 | Cabbi, IceBerg, kwezz, Lucky, MistR          |
|           89 |     3907 | 2024-03-27 | Pera Esports              | W   | 0.777      | -            | -                | -                | -         |     6.21 | Cabbi, IceBerg, kwezz, Lucky, MistR          |
|           88 |     3973 | 2024-03-26 | ARROW                     | W   | 0.771      | -            | -                | -                | -         |     2.96 | Kre1N, Orbit, SnacKZ1, Tionix, Twiksar       |
|           87 |     3998 | 2024-03-26 | Dynamo Eclot              | L   | 0.769      | -            | -                | -                | -         |   -12.77 | Cabbi, IceBerg, kwezz, Lucky, MistR          |
|           86 |     4020 | 2024-03-25 | Nexus Gaming              | W   | 0.764      | -            | -                | -                | -         |     8.09 | Cabbi, IceBerg, kwezz, Lucky, MistR          |
|           85 |     4130 | 2024-03-22 | Nemiga Gaming             | W   | 0.744      | 0.371        | 0.358 (0.099)    | -                | -         |    16.52 | Cabbi, IceBerg, kwezz, Lucky, MistR          |
|           84 |     4144 | 2024-03-22 | Viperio                   | W   | 0.742      | -            | -                | -                | -         |     2.42 | mAnGo, MMS, pandi7o, ReegaN, zodi            |
|           83 |     4271 | 2024-03-19 | RUBY                      | W   | 0.724      | -            | -                | -                | -         |     8.07 | Cabbi, IceBerg, kwezz, Lucky, MistR          |
|           82 |     4320 | 2024-03-18 | Insilio                   | W   | 0.716      | -            | -                | -                | -         |     9.40 | faydett, FpSSS, Pipw, Polt, sugaR            |
|           81 |     4499 | 2024-03-15 | Dynamo Eclot              | W   | 0.695      | 0.384        | -                | 0.940 (0.251)    | -         |    11.51 | Blytz, Dytor, forsyy, kreaz, nbqq            |
|           80 |     4635 | 2024-03-13 | BLEED Esports             | L   | 0.682      | -            | -                | -                | -         |    -5.40 | Cabbi, IceBerg, kwezz, Lucky, MistR          |
|           79 |     4747 | 2024-03-11 | Nemiga Gaming             | L   | 0.670      | -            | -                | -                | -         |    -5.09 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r         |
|           78 |     4799 | 2024-03-10 | Team Sampi                | L   | 0.662      | -            | -                | -                | -         |   -12.94 | Cabbi, IceBerg, kwezz, Lucky, MistR          |
|           77 |     4859 | 2024-03-09 | Permitta Esports          | W   | 0.656      | -            | -                | -                | -         |     9.22 | bnox, maaryy, mASKED, morelz, Vegi           |
|           76 |     4896 | 2024-03-08 | ALTERNATE aTTaX           | L   | 0.648      | -            | -                | -                | -         |   -13.22 | ArroW, awzek, FreeZe, hyped, skyye           |
|           75 |     4930 | 2024-03-07 | Insilio                   | W   | 0.645      | -            | -                | -                | -         |     7.79 | faydett, FpSSS, Pipw, Polt, sugaR            |
|           74 |     4953 | 2024-03-07 | ex-sYnck                  | W   | 0.643      | -            | -                | -                | -         |     3.54 | Cabbi, IceBerg, kwezz, Lucky, MistR          |
|           73 |     5044 | 2024-03-06 | Alliance                  | W   | 0.636      | -            | -                | -                | -         |     5.10 | avid, b0denmaster, PlesseN, robiin, twist    |
|           72 |     5098 | 2024-03-05 | Johnny Speeds             | L   | 0.631      | -            | -                | -                | -         |   -10.50 | Cabbi, IceBerg, kwezz, Lucky, MistR          |
|           71 |     5123 | 2024-03-05 | ALTERNATE aTTaX           | L   | 0.629      | -            | -                | -                | -         |   -13.50 | ArroW, awzek, FreeZe, hyped, skyye           |
|           70 |     5164 | 2024-03-04 | Team QUAZAR               | W   | 0.625      | -            | -                | -                | -         |     0.49 | Electro, KarmaN, kirito, LVF, xnkka          |
|           69 |     5202 | 2024-03-04 | Entropiq                  | L   | 0.622      | -            | -                | -                | -         |   -17.20 | c0llins, Marix, mwlky, Oxygen, tiziaN        |
|           68 |     5300 | 2024-03-02 | The Chosen Few            | L   | 0.611      | -            | -                | -                | -         |   -16.52 | choiv7, KalubeR, shaiK, Skrimo, SPELLAN      |
|           67 |     5347 | 2024-03-02 | brazylijski luz           | W   | 0.609      | -            | -                | -                | -         |     2.87 | Furlan, phr, POLO, Prism, Qlocuu             |
|           66 |     5406 | 2024-02-29 | MOUZ NXT                  | W   | 0.598      | 0.371        | 0.157 (0.035)    | -                | -         |    10.56 | Cabbi, IceBerg, kwezz, Lucky, MistR          |
|           65 |     5417 | 2024-02-29 | Permitta Esports          | W   | 0.597      | -            | -                | -                | -         |     7.18 | bnox, maaryy, mASKED, morelz, Vegi           |
|           64 |     5444 | 2024-02-29 | JANO Esports              | W   | 0.595      | -            | -                | -                | -         |     3.14 | Cabbi, IceBerg, kwezz, Lucky, MistR          |
|           63 |     5483 | 2024-02-28 | Team Sampi                | W   | 0.590      | -            | -                | -                | -         |     6.41 | Cabbi, IceBerg, kwezz, Lucky, MistR          |
|           62 |     5520 | 2024-02-27 | V1dar Gaming              | L   | 0.584      | -            | -                | -                | -         |   -16.15 | Cabbi, IceBerg, kwezz, Lucky, MistR          |
|           61 |     5558 | 2024-02-26 | Betera Esports            | W   | 0.578      | -            | -                | -                | -         |     3.94 | alex666, lollipop21k, MaSvAl, nifee, sad     |
|           60 |     5601 | 2024-02-25 | Sangal Esports            | L   | 0.571      | -            | -                | -                | -         |    -9.71 | Cabbi, IceBerg, kwezz, Lucky, MistR          |
|           59 |     5621 | 2024-02-25 | ex-Turów Zgorzelec Esport | L   | 0.569      | -            | -                | -                | -         |   -14.90 | AxEcHo, darko, kadziu, Markoś, xKacpersky    |
|           58 |     5736 | 2024-02-24 | MOUZ NXT                  | L   | 0.562      | -            | -                | -                | -         |    -8.49 | Cabbi, IceBerg, kwezz, Lucky, MistR          |
|           57 |     5762 | 2024-02-23 | VP.Prodigy                | W   | 0.558      | -            | -                | -                | -         |     3.57 | dwushka, KusMe, shady, Something, xdENiSZERA |
|           56 |     5767 | 2024-02-23 | FAVBET Team               | W   | 0.557      | -            | -                | -                | -         |     3.02 | Cabbi, IceBerg, kwezz, Lucky, MistR          |
|           55 |     5896 | 2024-02-21 | Team Sampi                | W   | 0.543      | -            | -                | -                | -         |     5.37 | Cabbi, IceBerg, kwezz, Lucky, MistR          |
|           54 |     5907 | 2024-02-21 | Verdant                   | W   | 0.542      | -            | -                | -                | -         |     6.43 | arTisT, Ducky, Girafffe, Vacancy, Zax1e      |
|           53 |     6002 | 2024-02-19 | Aurora Young Blud         | W   | 0.531      | -            | -                | -                | -         |     2.78 | Cabbi, IceBerg, kwezz, Lucky, MistR          |
|           52 |     6121 | 2024-02-17 | Zero Tenacity             | W   | 0.517      | -            | -                | -                | -         |     6.84 | Cabbi, IceBerg, kwezz, Lucky, MistR          |
|           51 |     6177 | 2024-02-16 | Permitta Esports          | W   | 0.509      | -            | -                | -                | -         |     5.62 | bnox, maaryy, mASKED, morelz, Vegi           |
|           50 |     6337 | 2024-02-13 | HOTU                      | W   | 0.491      | -            | -                | -                | -         |     3.68 | Cabbi, IceBerg, kwezz, Lucky, MistR          |
|           49 |     6408 | 2024-02-12 | Astralis Talent           | W   | 0.482      | -            | -                | -                | -         |     4.93 | ANSG1, JBOEN, kiR, kroK, tOPZ                |
|           48 |     6434 | 2024-02-11 | ARCRED                    | W   | 0.476      | -            | -                | -                | -         |     2.59 | Cabbi, IceBerg, kwezz, Lucky, MistR          |
|           47 |     6441 | 2024-02-10 | Nemiga Gaming             | L   | 0.471      | -            | -                | -                | -         |    -3.71 | Cabbi, IceBerg, kwezz, Lucky, MistR          |
|           46 |     6463 | 2024-02-10 | AMKAL ESPORTS             | W   | 0.470      | -            | -                | -                | -         |    10.49 | Cabbi, IceBerg, kwezz, Lucky, MistR          |
|           45 |     6480 | 2024-02-09 | FORZE Esports             | W   | 0.464      | -            | -                | -                | -         |     5.96 | Cabbi, IceBerg, kwezz, Lucky, MistR          |
|           44 |     6494 | 2024-02-09 | Insilio                   | W   | 0.463      | -            | -                | -                | -         |     5.55 | faydett, FpSSS, Pipw, Polt, sugaR            |
|           43 |     6510 | 2024-02-08 | Nemiga Gaming             | L   | 0.458      | -            | -                | -                | -         |    -3.47 | Cabbi, IceBerg, kwezz, Lucky, MistR          |
|           42 |     6524 | 2024-02-08 | FORZE Esports             | W   | 0.457      | -            | -                | -                | -         |     5.74 | gokushima, r3salt, SELLTER, shalfey, tN1R    |
|           41 |     6546 | 2024-02-07 | Team Spirit Academy       | W   | 0.451      | -            | -                | -                | -         |     2.49 | Cabbi, IceBerg, kwezz, Lucky, MistR          |
|           40 |     6554 | 2024-02-07 | Insilio                   | L   | 0.451      | -            | -                | -                | -         |    -9.01 | Cabbi, IceBerg, kwezz, Lucky, MistR          |
|           39 |     6561 | 2024-02-07 | BIG Academy               | L   | 0.449      | -            | -                | -                | -         |   -11.98 | Cabbi, IceBerg, kwezz, Lucky, MistR          |
|           38 |     6624 | 2024-02-05 | L&G                       | W   | 0.437      | -            | -                | -                | -         |     0.69 | Cabbi, IceBerg, kwezz, Lucky, MistR          |
|           37 |     6641 | 2024-02-05 | Entropiq                  | W   | 0.436      | -            | -                | -                | -         |     1.50 | c0llins, Marix, mwlky, Oxygen, tiziaN        |
|           36 |     6670 | 2024-02-04 | TOOMUCHVIDEOGAMES         | L   | 0.429      | -            | -                | -                | -         |   -12.88 | Cabbi, IceBerg, kwezz, Lucky, MistR          |
|           35 |     6699 | 2024-02-03 | showmakerz                | W   | 0.424      | -            | -                | -                | -         |     0.84 | Cabbi, IceBerg, kwezz, Lucky, MistR          |
|           34 |     6705 | 2024-02-03 | Gaimin Gladiators         | W   | 0.424      | -            | -                | -                | -         |    10.07 | Cabbi, IceBerg, kwezz, Lucky, MistR          |
|           33 |     6718 | 2024-02-03 | EYEBALLERS                | W   | 0.424      | -            | -                | -                | -         |     4.26 | Cabbi, IceBerg, kwezz, Lucky, MistR          |
|           32 |     6741 | 2024-02-03 | Kappa Bar                 | W   | 0.424      | -            | -                | -                | -         |     0.67 | dezt, jayzaR, pupcake, TIM, upE              |
|           31 |     6773 | 2024-02-03 | Team Sampi                | L   | 0.422      | -            | -                | -                | -         |    -8.79 | Cabbi, IceBerg, kwezz, Lucky, MistR          |
|           30 |     6796 | 2024-02-02 | EYEBALLERS                | L   | 0.417      | -            | -                | -                | -         |    -9.21 | HEAP, JW, Peppzor, Sapec, SHiNE              |
|           29 |     6801 | 2024-02-02 | showmakerz                | W   | 0.417      | -            | -                | -                | -         |     0.72 | Cabbi, IceBerg, kwezz, Lucky, MistR          |
|           28 |     6821 | 2024-02-02 | WOPA Esport               | W   | 0.417      | -            | -                | -                | -         |     2.48 | brzer, Gnøffe, Leakz, LUMSEN, Pellyy         |
|           27 |     6902 | 2024-02-01 | ENCE Academy              | W   | 0.409      | -            | -                | -                | -         |     2.88 | HENU, myltsi, podi, S1rva, teme              |
|           26 |     6943 | 2024-01-31 | Permitta Esports          | L   | 0.403      | -            | -                | -                | -         |    -8.27 | Cabbi, IceBerg, kwezz, Lucky, MistR          |
|           25 |     6958 | 2024-01-30 | Insilio                   | W   | 0.398      | -            | -                | -                | -         |     4.16 | faydett, FpSSS, Pipw, Polt, sugaR            |
|           24 |     6960 | 2024-01-30 | FORZE Esports             | W   | 0.398      | -            | -                | -                | -         |     1.37 | gokushima, r3salt, shalfey, sstiNiX, tN1R    |
|           23 |     6977 | 2024-01-30 | RUSH B                    | W   | 0.397      | -            | -                | -                | -         |     1.93 | Cabbi, IceBerg, kwezz, Lucky, MistR          |
|           22 |     7002 | 2024-01-29 | brazylijski luz           | W   | 0.392      | -            | -                | -                | -         |     2.52 | Furlan, phr, POLO, Prism, Qlocuu             |
|           21 |     7041 | 2024-01-29 | Sangal Esports            | W   | 0.392      | -            | -                | -                | -         |     6.86 | Ganginho, LNZ, sausol, xfl0ud, yxngstxr      |
|           20 |     7213 | 2024-01-27 | Verdant                   | W   | 0.375      | -            | -                | -                | -         |     5.59 | Cabbi, IceBerg, kwezz, Lucky, MistR          |
|           19 |     7341 | 2024-01-24 | Soda Gaming               | W   | 0.358      | -            | -                | -                | -         |     1.19 | 2high, aidKiT, Ciocardau, shadiy, soulfly    |
|           18 |     7461 | 2024-01-22 | RUBY                      | W   | 0.344      | -            | -                | -                | -         |     3.28 | dekz, Kaide, mo0n, Sowalio, w1nt3r           |
|           17 |     7472 | 2024-01-22 | FORZE Youngsters          | W   | 0.344      | -            | -                | -                | -         |     1.13 | Cabbi, IceBerg, kwezz, Lucky, MistR          |
|           16 |     7821 | 2024-01-17 | Natus Vincere Junior      | L   | 0.311      | -            | -                | -                | -         |    -8.00 | dem0n, fnl, Krabeni, Magic, makazze          |
|           15 |     7882 | 2024-01-16 | EYEBALLERS                | L   | 0.305      | -            | -                | -                | -         |    -6.60 | Cabbi, IceBerg, kwezz, Lucky, MistR          |
|           14 |     7896 | 2024-01-16 | ARCRED                    | W   | 0.304      | -            | -                | -                | -         |     1.67 | Cabbi, IceBerg, kwezz, Lucky, MistR          |
|           13 |     7914 | 2024-01-16 | NoCryIfLose               | W   | 0.304      | -            | -                | -                | -         |     0.24 | aidKiT, bibu, neiter, notaN, rilax           |
|           12 |     8122 | 2024-01-12 | BEZFORMbI                 | L   | 0.278      | -            | -                | -                | -         |    -8.34 | airscape, almazer, ANASTAZE, poka, SBolt     |
|           11 |     8274 | 2024-01-10 | Viperio                   | L   | 0.265      | -            | -                | -                | -         |    -7.83 | mAnGo, MMS, pandi7o, ReegaN, zodi            |
|           10 |     8317 | 2024-01-09 | ENTERPRISE esports        | L   | 0.258      | -            | -                | -                | -         |    -5.31 | Cabbi, IceBerg, kwezz, Lucky, MistR          |
|            9 |     8336 | 2024-01-09 | Dynamo Eclot              | W   | 0.257      | -            | -                | -                | -         |     4.46 | Cabbi, IceBerg, kwezz, Lucky, MistR          |
|            8 |     8346 | 2024-01-09 | Pera Esports              | W   | 0.257      | -            | -                | -                | -         |     2.41 | Cabbi, IceBerg, kwezz, Lucky, MistR          |
|            7 |     8370 | 2024-01-09 | showmakerz                | W   | 0.257      | -            | -                | -                | -         |     0.40 | bsover, Doobs, julle, Leon1das, majkn        |
|            6 |     8647 | 2023-12-20 | NOM Esports               | L   | 0.122      | -            | -                | -                | -         |    -3.52 | AMSALEM, BluePho3nix, dan1, ultimate, Zax1e  |
|            5 |     8659 | 2023-12-19 | ex-Anonymo Esports        | L   | 0.116      | -            | -                | -                | -         |    -3.25 | lunAtic, reiko, SaMey, Sobol, virtuoso       |
|            4 |     8748 | 2023-12-17 | ex-Turów Zgorzelec Esport | W   | 0.102      | -            | -                | -                | -         |     0.56 | b1elany, darko, gRuChA, kadziu, Markoś       |
|            3 |     9148 | 2023-12-12 | Zero Tenacity             | W   | 0.070      | -            | -                | -                | -         |     1.18 | Cabbi, IceBerg, kwezz, Lucky, MistR          |
|            2 |     9371 | 2023-12-08 | The Witchers              | W   | 0.044      | -            | -                | -                | -         |     0.16 | Dragon, fear, Sdaim, smooya, synyx           |
|            1 |     9598 | 2023-12-05 | EYEBALLERS                | L   | 0.022      | -            | -                | -                | -         |    -0.50 | Cabbi, IceBerg, kwezz, Lucky, MistR          |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($46,281.90)
- Divide that value by the 5th highest value among all rosters ($300,806.11)
- The final value (0.15) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-05-18 |      1.000 | $5,000.00      | $5,000.00       |
| 2024-05-09 |      1.000 | $18,256.44     | $18,256.44      |
| 2024-05-02 |      1.000 | $12,500.00     | $12,500.00      |
| 2024-04-27 |      0.984 | $6,421.58      | $6,319.90       |
| 2024-04-06 |      0.841 | $5,000.00      | $4,205.56       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
