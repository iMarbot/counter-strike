### Roster Details<br />
Team Name: ENTERPRISE esports<br />
Roster: bajmi, Demho, Ex1st, fr3nd, Sobol<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [87](../standings_global.md)<br />
Regional Rank: [62]( ../standings_europe.md)<br />
Final Rank Value:  898.5<br />
<br />
Final Rank Value (898.5) = Starting Rank Value (956.9) + Head To Head Adjustments (-58.4)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.332[<sup>1</sup>](#table2)
- Bounty Collected: 0.412[<sup>2</sup>](#table1)
- Opponent Network: 0.299[<sup>2</sup>](#table1)
- LAN Wins: 0.053[<sup>2</sup>](#table1)

The average of these factors is 0.274<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 956.9
- 400 + ( ( 0.274 - 0.000 ) / ( 0.787 - 0.000 ) ) * 1600 = 956.9


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent                  | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                  |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           99 |       64 | 2024-05-29 | FLuffy Gangsters          | W   | 1.000      | -            | -                | -                | 0 (0.000) |     7.13 | bajmi, Demho, Ex1st, fr3nd, Sobol       |
|           98 |      134 | 2024-05-28 | Team Sampi                | W   | 1.000      | -            | -                | -                | 0 (0.000) |    19.08 | bajmi, Demho, Ex1st, fr3nd, Sobol       |
|           97 |      302 | 2024-05-25 | GUN5 Esports              | W   | 1.000      | -            | -                | -                | 0 (0.000) |    13.11 | bajmi, Demho, Ex1st, fr3nd, Sobol       |
|           96 |      358 | 2024-05-24 | CYBERSHOKE Esports        | L   | 1.000      | -            | -                | -                | -         |   -20.29 | bajmi, Demho, Ex1st, fr3nd, Sobol       |
|           95 |      375 | 2024-05-24 | Illuminar Gaming          | W   | 1.000      | -            | -                | -                | 0 (0.000) |    10.00 | bajmi, Demho, Ex1st, fr3nd, Sobol       |
|           94 |      399 | 2024-05-23 | Zero Tenacity             | L   | 1.000      | -            | -                | -                | -         |    -7.86 | bajmi, Demho, Ex1st, fr3nd, Sobol       |
|           93 |      414 | 2024-05-23 | 1win                      | L   | 1.000      | -            | -                | -                | -         |    -9.58 | bajmi, Demho, Ex1st, fr3nd, Sobol       |
|           92 |      496 | 2024-05-22 | Entropiq                  | W   | 1.000      | -            | -                | -                | 0 (0.000) |     9.87 | bajmi, Demho, Ex1st, fr3nd, Sobol       |
|           91 |      508 | 2024-05-22 | V1dar Gaming              | L   | 1.000      | -            | -                | -                | -         |   -20.13 | bajmi, Demho, Ex1st, fr3nd, Sobol       |
|           90 |      609 | 2024-05-21 | Team Spirit Academy       | L   | 1.000      | -            | -                | -                | -         |   -20.23 | bajmi, Demho, Ex1st, fr3nd, Sobol       |
|           89 |      696 | 2024-05-20 | Rustec                    | W   | 1.000      | -            | -                | -                | 0 (0.000) |    12.41 | bajmi, Demho, Ex1st, fr3nd, Sobol       |
|           88 |      712 | 2024-05-20 | RoundsGG                  | W   | 1.000      | -            | -                | -                | 0 (0.000) |     4.39 | bajmi, Demho, Ex1st, fr3nd, Sobol       |
|           87 |      728 | 2024-05-20 | ECSTATIC                  | W   | 1.000      | -            | -                | -                | 0 (0.000) |     1.80 | bajmi, Demho, Ex1st, fr3nd, Sobol       |
|           86 |      772 | 2024-05-19 | L&G                       | L   | 1.000      | -            | -                | -                | -         |   -20.49 | bajmi, Demho, Ex1st, fr3nd, Sobol       |
|           85 |      789 | 2024-05-19 | Aqua Academy              | W   | 1.000      | -            | -                | -                | -         |     1.63 | bajmi, Demho, Ex1st, fr3nd, Sobol       |
|           84 |      873 | 2024-05-18 | Quixal                    | L   | 1.000      | -            | -                | -                | -         |   -24.09 | bajmi, Demho, Ex1st, fr3nd, Sobol       |
|           83 |      892 | 2024-05-18 | CYBERSHOKE Esports        | W   | 1.000      | -            | -                | -                | -         |     7.97 | bajmi, Demho, Ex1st, fr3nd, Sobol       |
|           82 |      900 | 2024-05-18 | 5W Gaming                 | W   | 1.000      | -            | -                | -                | -         |     2.98 | bajmi, Demho, Ex1st, fr3nd, Sobol       |
|           81 |      907 | 2024-05-18 | MANGANES                  | W   | 1.000      | -            | -                | -                | -         |     3.34 | bajmi, Demho, Ex1st, fr3nd, Sobol       |
|           80 |      990 | 2024-05-17 | 1win                      | L   | 1.000      | -            | -                | -                | -         |   -11.46 | bajmi, Demho, Ex1st, fr3nd, Sobol       |
|           79 |     1002 | 2024-05-17 | VOLT                      | W   | 1.000      | -            | -                | -                | -         |     1.57 | bajmi, Demho, Ex1st, fr3nd, Sobol       |
|           78 |     1012 | 2024-05-17 | CYBERSHOKE Esports        | W   | 1.000      | -            | -                | -                | -         |     7.63 | bajmi, Demho, Ex1st, fr3nd, Sobol       |
|           77 |     1093 | 2024-05-16 | ENRAGE                    | W   | 1.000      | -            | -                | -                | -         |     2.93 | bajmi, Demho, Ex1st, fr3nd, Sobol       |
|           76 |     1169 | 2024-05-15 | los kogutos               | W   | 1.000      | -            | -                | -                | -         |    14.95 | bajmi, Demho, Ex1st, fr3nd, Sobol       |
|           75 |     1179 | 2024-05-15 | EXO Clan                  | W   | 1.000      | 0.372        | -                | 0.579 (0.216)    | -         |    15.06 | bajmi, Demho, Ex1st, fr3nd, Sobol       |
|           74 |     1391 | 2024-05-12 | M1X                       | L   | 1.000      | -            | -                | -                | -         |   -28.73 | bajmi, Demho, Ex1st, fr3nd, Sobol       |
|           73 |     1430 | 2024-05-11 | ex-Turów Zgorzelec Esport | L   | 1.000      | -            | -                | -                | -         |   -21.59 | bajmi, Demho, Ex1st, fr3nd, Sobol       |
|           72 |     1453 | 2024-05-11 | brazylijski luz           | W   | 1.000      | -            | -                | -                | -         |    12.41 | bajmi, Demho, Ex1st, fr3nd, Sobol       |
|           71 |     1544 | 2024-05-10 | BetBoom Team              | L   | 1.000      | -            | -                | -                | -         |    -3.20 | bajmi, Demho, Ex1st, fr3nd, TOAO        |
|           70 |     1571 | 2024-05-09 | Passion UA                | W   | 1.000      | 0.372        | 0.057 (0.021)    | 1.000 (0.372)    | -         |    16.39 | bajmi, Demho, Ex1st, fr3nd, Sobol       |
|           69 |     1583 | 2024-05-09 | MOUZ NXT                  | W   | 1.000      | 0.372        | 0.157 (0.058)    | 0.977 (0.364)    | -         |    20.35 | bajmi, Demho, Ex1st, fr3nd, Sobol       |
|           68 |     1662 | 2024-05-08 | DASH                      | W   | 1.000      | -            | -                | -                | -         |     8.31 | bajmi, Demho, Ex1st, fr3nd, Sobol       |
|           67 |     1716 | 2024-05-07 | Permitta Esports          | W   | 1.000      | 0.435        | 0.025 (0.011)    | 1.000 (0.435)    | -         |    16.98 | bajmi, Demho, Ex1st, fr3nd, TOAO        |
|           66 |     1760 | 2024-05-06 | B8                        | L   | 1.000      | -            | -                | -                | -         |    -8.02 | bajmi, Demho, Ex1st, fr3nd, TOAO        |
|           65 |     1827 | 2024-05-04 | MOUZ NXT                  | W   | 1.000      | 0.435        | 0.157 (0.068)    | 0.977 (0.424)    | -         |    22.99 | bajmi, Demho, Ex1st, fr3nd, kadziu      |
|           64 |     1991 | 2024-05-01 | ENCE Academy              | W   | 1.000      | -            | -                | -                | -         |    12.28 | bajmi, Demho, Ex1st, fr3nd, kadziu      |
|           63 |     2060 | 2024-04-30 | EYEBALLERS                | L   | 1.000      | -            | -                | -                | -         |   -12.74 | bajmi, Demho, Ex1st, fr3nd, TOAO        |
|           62 |     2122 | 2024-04-29 | Nexus Gaming              | L   | 0.994      | -            | -                | -                | -         |   -14.63 | bajmi, Demho, Ex1st, fr3nd, TOAO        |
|           61 |     2251 | 2024-04-27 | Permitta Esports          | L   | 0.981      | -            | -                | -                | -         |   -12.46 | bajmi, Demho, Ex1st, fr3nd, TOAO        |
|           60 |     2311 | 2024-04-26 | Insilio                   | L   | 0.976      | -            | -                | -                | -         |   -12.31 | bajmi, Demho, Ex1st, fr3nd, TOAO        |
|           59 |     2483 | 2024-04-23 | ALTERNATE aTTaX           | L   | 0.955      | -            | -                | -                | -         |   -15.32 | bajmi, Demho, Ex1st, fr3nd, TOAO        |
|           58 |     2548 | 2024-04-21 | ThunderFlash              | L   | 0.943      | -            | -                | -                | -         |   -18.18 | bajmi, Demho, Ex1st, fr3nd, TOAO        |
|           57 |     2631 | 2024-04-20 | Permitta Esports          | W   | 0.937      | -            | -                | -                | -         |    16.17 | bajmi, Demho, Ex1st, fr3nd, TOAO        |
|           56 |     2701 | 2024-04-20 | ALTERNATE aTTaX           | L   | 0.935      | -            | -                | -                | -         |   -14.79 | bajmi, Demho, Ex1st, fr3nd, TOAO        |
|           55 |     2757 | 2024-04-19 | 9INE                      | W   | 0.930      | -            | -                | -                | -         |     5.18 | bajmi, Demho, Ex1st, fr3nd, TOAO        |
|           54 |     2827 | 2024-04-18 | MOUZ NXT                  | L   | 0.923      | -            | -                | -                | -         |    -8.21 | bajmi, Demho, Ex1st, fr3nd, TOAO        |
|           53 |     2845 | 2024-04-18 | Nexus Gaming              | W   | 0.922      | 0.384        | -                | 0.857 (0.304)    | -         |    15.09 | bajmi, Demho, Ex1st, fr3nd, TOAO        |
|           52 |     2910 | 2024-04-17 | ENCE                      | L   | 0.916      | -            | -                | -                | -         |    -2.10 | bajmi, Demho, Ex1st, fr3nd, TOAO        |
|           51 |     3204 | 2024-04-11 | Sashi Esport              | L   | 0.875      | -            | -                | -                | -         |    -8.95 | bajmi, Demho, Ex1st, fr3nd, TOAO        |
|           50 |     3279 | 2024-04-10 | AMKAL ESPORTS             | W   | 0.868      | 0.384        | 0.146 (0.049)    | 0.565 (0.189)    | -         |    20.96 | bajmi, Demho, Ex1st, fr3nd, TOAO        |
|           49 |     3494 | 2024-04-06 | Team Sampi                | L   | 0.842      | -            | -                | -                | -         |    -9.92 | bajmi, Demho, Ex1st, fr3nd, TOAO        |
|           48 |     3641 | 2024-04-03 | Permitta Esports          | W   | 0.823      | 0.384        | -                | 1.000 (0.316)    | -         |    13.59 | bajmi, Demho, Ex1st, fr3nd, TOAO        |
|           47 |     3719 | 2024-04-01 | BLEED Esports             | W   | 0.809      | 0.384        | 0.248 (0.077)    | 0.714 (0.222)    | -         |    21.49 | bajmi, Demho, Ex1st, fr3nd, TOAO        |
|           46 |     3968 | 2024-03-26 | Heimo Esports             | L   | 0.771      | -            | -                | -                | -         |   -17.58 | bajmi, Demho, Ex1st, fr3nd, TOAO        |
|           45 |     4128 | 2024-03-22 | ThunderFlash              | L   | 0.744      | -            | -                | -                | -         |   -15.19 | bajmi, Demho, Ex1st, fr3nd, TOAO        |
|           44 |     4165 | 2024-03-21 | Illuminar Gaming          | L   | 0.738      | -            | -                | -                | -         |   -15.89 | bajmi, Demho, Ex1st, fr3nd, TOAO        |
|           43 |     4236 | 2024-03-20 | ex-Turów Zgorzelec Esport | W   | 0.730      | -            | -                | -                | -         |     6.67 | bajmi, Demho, Ex1st, fr3nd, TOAO        |
|           42 |     4275 | 2024-03-19 | LODIS                     | W   | 0.724      | -            | -                | -                | -         |     3.12 | bajmi, Demho, Ex1st, fr3nd, TOAO        |
|           41 |     4304 | 2024-03-18 | Mikstura1234              | W   | 0.718      | -            | -                | -                | -         |     4.41 | bajmi, Demho, Ex1st, fr3nd, TOAO        |
|           40 |     4842 | 2024-03-09 | kONO.ECF                  | L   | 0.657      | -            | -                | -                | -         |   -10.35 | bajmi, Demho, Ex1st, fr3nd, TOAO        |
|           39 |     4862 | 2024-03-09 | Team Sampi                | L   | 0.656      | -            | -                | -                | -         |   -10.25 | bajmi, Demho, Ex1st, fr3nd, TOAO        |
|           38 |     5013 | 2024-03-06 | INGLORIOUS                | L   | 0.637      | -            | -                | -                | -         |   -14.30 | bajmi, Demho, Ex1st, fr3nd, TOAO        |
|           37 |     5038 | 2024-03-06 | Permitta Esports          | L   | 0.636      | -            | -                | -                | -         |    -9.78 | bajmi, Demho, Ex1st, fr3nd, TOAO        |
|           36 |     5146 | 2024-03-04 | Nemiga Gaming             | L   | 0.625      | -            | -                | -                | -         |    -3.51 | bajmi, Demho, Ex1st, fr3nd, TOAO        |
|           35 |     5172 | 2024-03-04 | ex-Turów Zgorzelec Esport | W   | 0.625      | -            | -                | -                | -         |     5.53 | bajmi, Demho, Ex1st, fr3nd, TOAO        |
|           34 |     5275 | 2024-03-02 | kONO.ECF                  | L   | 0.612      | -            | -                | -                | -         |   -10.01 | bajmi, Demho, Ex1st, fr3nd, TOAO        |
|           33 |     5305 | 2024-03-02 | Sashi Esport              | W   | 0.611      | -            | -                | -                | -         |     4.67 | bajmi, Demho, Ex1st, fr3nd, TOAO        |
|           32 |     5363 | 2024-03-02 | Team Sampi                | W   | 0.608      | 0.371        | 0.039 (0.009)    | 0.677 (0.153)    | -         |     8.93 | bajmi, Demho, Ex1st, fr3nd, TOAO        |
|           31 |     5456 | 2024-02-28 | FAVBET Team               | L   | 0.591      | -            | -                | -                | -         |   -12.05 | bajmi, Demho, Ex1st, fr3nd, TOAO        |
|           30 |     5470 | 2024-02-28 | RUBY                      | L   | 0.591      | -            | -                | -                | -         |   -10.23 | bajmi, Demho, Ex1st, fr3nd, TOAO        |
|           29 |     5514 | 2024-02-27 | Eternal Fire Academy      | W   | 0.584      | -            | -                | -                | -         |     2.42 | bajmi, Demho, Ex1st, fr3nd, TOAO        |
|           28 |     5553 | 2024-02-26 | kONO.ECF                  | L   | 0.578      | -            | -                | -                | -         |   -10.26 | bajmi, Demho, Ex1st, fr3nd, TOAO        |
|           27 |     5606 | 2024-02-25 | DASH                      | W   | 0.571      | -            | -                | -                | -         |     3.29 | bajmi, Demho, Ex1st, fr3nd, TOAO        |
|           26 |     6150 | 2024-02-16 | SAW                       | L   | 0.511      | -            | -                | -                | -         |    -1.90 | bajmi, Demho, Ex1st, fr3nd, TOAO        |
|           25 |     6239 | 2024-02-15 | BetBoom Team              | L   | 0.503      | -            | -                | -                | -         |    -1.49 | bajmi, Demho, Ex1st, fr3nd, TOAO        |
|           24 |     6268 | 2024-02-14 | Natus Vincere             | L   | 0.498      | -            | -                | -                | -         |    -0.12 | bajmi, Demho, Ex1st, fr3nd, TOAO        |
|           23 |     6292 | 2024-02-14 | AMKAL ESPORTS             | W   | 0.496      | 0.143        | 0.146 (0.010)    | -                | 1 (0.496) |    12.12 | bajmi, Demho, Ex1st, fr3nd, TOAO        |
|           22 |     6483 | 2024-02-09 | HOTU                      | L   | 0.464      | -            | -                | -                | -         |    -9.97 | bajmi, Demho, Ex1st, fr3nd, TOAO        |
|           21 |     6660 | 2024-02-04 | Team Spirit Academy       | L   | 0.431      | -            | -                | -                | -         |   -10.82 | bajmi, Demho, Ex1st, fr3nd, TOAO        |
|           20 |     6923 | 2024-01-31 | MOUZ NXT                  | L   | 0.404      | -            | -                | -                | -         |    -4.65 | bajmi, Demho, Ex1st, fr3nd, TOAO        |
|           19 |     7260 | 2024-01-26 | BAKS Esports              | W   | 0.370      | -            | -                | -                | -         |     1.29 | bajmi, Demho, Ex1st, fr3nd, TOAO        |
|           18 |     7305 | 2024-01-25 | ex-K10                    | W   | 0.364      | -            | -                | -                | -         |     3.72 | bajmi, Demho, Ex1st, fr3nd, TOAO        |
|           17 |     7346 | 2024-01-24 | los kogutos               | W   | 0.357      | -            | -                | -                | -         |     0.80 | bajmi, Demho, Ex1st, fr3nd, TOAO        |
|           16 |     7356 | 2024-01-24 | Nemiga Gaming             | W   | 0.357      | 0.371        | 0.358 (0.047)    | -                | -         |     8.98 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r    |
|           15 |     7588 | 2024-01-20 | KOI                       | W   | 0.330      | -            | -                | -                | -         |     5.13 | bajmi, Demho, Ex1st, fr3nd, TOAO        |
|           14 |     7658 | 2024-01-19 | ex-sYnck                  | W   | 0.323      | -            | -                | -                | -         |     2.26 | bajmi, Demho, Ex1st, fr3nd, TOAO        |
|           13 |     7709 | 2024-01-18 | Aurora Gaming             | W   | 0.318      | 0.143        | 0.492 (0.022)    | -                | -         |     9.43 | bajmi, Demho, Ex1st, fr3nd, TOAO        |
|           12 |     7724 | 2024-01-18 | Astralis                  | L   | 0.317      | -            | -                | -                | -         |    -0.20 | bajmi, Demho, Ex1st, fr3nd, TOAO        |
|           11 |     7801 | 2024-01-17 | Insilio                   | L   | 0.311      | -            | -                | -                | -         |    -5.99 | faydett, FpSSS, Pipw, Polt, sugaR       |
|           10 |     8304 | 2024-01-09 | KOI                       | W   | 0.259      | -            | -                | -                | -         |     4.06 | adamS, dav1g, JUST, mopoz, stadodo      |
|            9 |     8309 | 2024-01-09 | Fnatic                    | W   | 0.259      | -            | -                | -                | -         |     5.76 | bajmi, Demho, Ex1st, fr3nd, TOAO        |
|            8 |     8317 | 2024-01-09 | Sashi Esport              | W   | 0.258      | -            | -                | -                | -         |     5.31 | Cabbi, IceBerg, kwezz, Lucky, MistR     |
|            7 |     8331 | 2024-01-09 | Johnny Speeds             | W   | 0.258      | -            | -                | -                | -         |     5.02 | Chawzyyy, draken, HugoXD, RuStY, spooke |
|            6 |     8345 | 2024-01-09 | underrated                | W   | 0.257      | -            | -                | -                | -         |     0.54 | bajmi, Demho, Ex1st, fr3nd, TOAO        |
|            5 |     8364 | 2024-01-09 | JANO Esports              | W   | 0.257      | -            | -                | -                | -         |     0.58 | Aerial, allu, doto, jelo, Sm1llee       |
|            4 |     9428 | 2023-12-07 | Lausanne-Sport Esports    | L   | 0.038      | -            | -                | -                | -         |    -1.05 | bajmi, Demho, Ex1st, fr3nd, Klameczka   |
|            3 |     9495 | 2023-12-06 | Nemiga Gaming             | W   | 0.031      | -            | -                | -                | -         |     0.82 | bajmi, Demho, Ex1st, fr3nd, Klameczka   |
|            2 |     9563 | 2023-12-05 | Endpoint                  | L   | 0.025      | -            | -                | -                | -         |    -0.39 | bajmi, Demho, Ex1st, fr3nd, Klameczka   |
|            1 |     9727 | 2023-12-02 | ex-Turów Zgorzelec Esport | W   | 0.004      | -            | -                | -                | 1 (0.004) |     0.04 | bajmi, Demho, Ex1st, fr3nd, Klameczka   |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($2,908.82)
- Divide that value by the 5th highest value among all rosters ($300,806.11)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-05-02 |      1.000 | $500.00        | $500.00         |
| 2024-04-21 |      0.943 | $2,464.60      | $2,324.94       |
| 2023-12-02 |      0.004 | $18,872.57     | $83.88          |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
