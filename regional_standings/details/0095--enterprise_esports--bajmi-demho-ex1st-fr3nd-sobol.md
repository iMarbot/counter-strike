### Roster Details<br />
Team Name: ENTERPRISE esports<br />
Roster: bajmi, Demho, Ex1st, fr3nd, Sobol<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [95](../standings_global.md)<br />
Regional Rank: [68]( ../standings_europe.md)<br />
Final Rank Value:  879.8<br />
<br />
Final Rank Value (879.8) = Starting Rank Value (938.9) + Head To Head Adjustments (-59.1)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.332[<sup>1</sup>](#table2)
- Bounty Collected: 0.388[<sup>2</sup>](#table1)
- Opponent Network: 0.286[<sup>2</sup>](#table1)
- LAN Wins: 0.053[<sup>2</sup>](#table1)

The average of these factors is 0.265<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 938.9
- 400 + ( ( 0.265 - 0.000 ) / ( 0.786 - 0.000 ) ) * 1600 = 938.9


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
|           91 |      127 | 2024-05-28 | Team Sampi                | W   | 1.000      | -            | -                | -                | 0 (0.000) |    19.39 | bajmi, Demho, Ex1st, fr3nd, Sobol       |
|           90 |      294 | 2024-05-25 | GUN5 Esports              | W   | 1.000      | -            | -                | -                | 0 (0.000) |    12.79 | bajmi, Demho, Ex1st, fr3nd, Sobol       |
|           89 |      349 | 2024-05-24 | CYBERSHOKE Esports        | L   | 1.000      | -            | -                | -                | -         |   -20.09 | bajmi, Demho, Ex1st, fr3nd, Sobol       |
|           88 |      366 | 2024-05-24 | Illuminar Gaming          | W   | 1.000      | 0.371        | -                | 0.403 (0.149)    | 0 (0.000) |    10.37 | bajmi, Demho, Ex1st, fr3nd, Sobol       |
|           87 |      391 | 2024-05-23 | Zero Tenacity             | L   | 1.000      | -            | -                | -                | -         |    -7.61 | bajmi, Demho, Ex1st, fr3nd, Sobol       |
|           86 |      406 | 2024-05-23 | 1win                      | L   | 1.000      | -            | -                | -                | -         |    -9.16 | bajmi, Demho, Ex1st, fr3nd, Sobol       |
|           85 |      490 | 2024-05-22 | Entropiq                  | W   | 1.000      | -            | -                | -                | 0 (0.000) |    10.22 | bajmi, Demho, Ex1st, fr3nd, Sobol       |
|           84 |      501 | 2024-05-22 | V1dar Gaming              | L   | 1.000      | -            | -                | -                | -         |   -19.93 | bajmi, Demho, Ex1st, fr3nd, Sobol       |
|           83 |      598 | 2024-05-21 | Team Spirit Academy       | L   | 1.000      | -            | -                | -                | -         |   -20.82 | bajmi, Demho, Ex1st, fr3nd, Sobol       |
|           82 |      685 | 2024-05-20 | Rustec                    | W   | 1.000      | -            | -                | -                | 0 (0.000) |    12.15 | bajmi, Demho, Ex1st, fr3nd, Sobol       |
|           81 |      700 | 2024-05-20 | RoundsGG                  | W   | 1.000      | -            | -                | -                | 0 (0.000) |     4.07 | bajmi, Demho, Ex1st, fr3nd, Sobol       |
|           80 |      716 | 2024-05-20 | ECSTATIC                  | W   | 1.000      | -            | -                | -                | 0 (0.000) |     1.92 | bajmi, Demho, Ex1st, fr3nd, Sobol       |
|           79 |      760 | 2024-05-19 | L&G                       | L   | 1.000      | -            | -                | -                | -         |   -20.06 | bajmi, Demho, Ex1st, fr3nd, Sobol       |
|           78 |      777 | 2024-05-19 | Aqua Academy              | W   | 1.000      | -            | -                | -                | 0 (0.000) |     1.74 | bajmi, Demho, Ex1st, fr3nd, Sobol       |
|           77 |      861 | 2024-05-18 | Quixal                    | L   | 1.000      | -            | -                | -                | -         |   -23.72 | bajmi, Demho, Ex1st, fr3nd, Sobol       |
|           76 |      880 | 2024-05-18 | CYBERSHOKE Esports        | W   | 1.000      | -            | -                | -                | -         |     8.22 | bajmi, Demho, Ex1st, fr3nd, Sobol       |
|           75 |      888 | 2024-05-18 | 5W Gaming                 | W   | 1.000      | -            | -                | -                | -         |     3.19 | bajmi, Demho, Ex1st, fr3nd, Sobol       |
|           74 |      895 | 2024-05-18 | MANGANES                  | W   | 1.000      | -            | -                | -                | -         |     3.58 | bajmi, Demho, Ex1st, fr3nd, Sobol       |
|           73 |      978 | 2024-05-17 | 1win                      | L   | 1.000      | -            | -                | -                | -         |   -10.86 | bajmi, Demho, Ex1st, fr3nd, Sobol       |
|           72 |      990 | 2024-05-17 | VOLT                      | W   | 1.000      | -            | -                | -                | -         |     1.69 | bajmi, Demho, Ex1st, fr3nd, Sobol       |
|           71 |     1000 | 2024-05-17 | CYBERSHOKE Esports        | W   | 1.000      | -            | -                | -                | -         |     7.93 | bajmi, Demho, Ex1st, fr3nd, Sobol       |
|           70 |     1083 | 2024-05-16 | ENRAGE                    | W   | 1.000      | -            | -                | -                | -         |     3.56 | bajmi, Demho, Ex1st, fr3nd, Sobol       |
|           69 |     1160 | 2024-05-15 | los kogutos               | W   | 1.000      | -            | -                | -                | -         |    15.73 | bajmi, Demho, Ex1st, fr3nd, Sobol       |
|           68 |     1169 | 2024-05-15 | EXO Clan                  | W   | 1.000      | 0.372        | -                | 0.510 (0.190)    | -         |    15.22 | bajmi, Demho, Ex1st, fr3nd, Sobol       |
|           67 |     1378 | 2024-05-12 | M1X                       | L   | 1.000      | -            | -                | -                | -         |   -28.48 | bajmi, Demho, Ex1st, fr3nd, Sobol       |
|           66 |     1417 | 2024-05-11 | ex-Turów Zgorzelec Esport | L   | 1.000      | -            | -                | -                | -         |   -22.34 | bajmi, Demho, Ex1st, fr3nd, Sobol       |
|           65 |     1440 | 2024-05-11 | brazylijski luz           | W   | 1.000      | -            | -                | -                | -         |    12.87 | bajmi, Demho, Ex1st, fr3nd, Sobol       |
|           64 |     1529 | 2024-05-10 | BetBoom Team              | L   | 1.000      | -            | -                | -                | -         |    -2.93 | bajmi, Demho, Ex1st, fr3nd, TOAO        |
|           63 |     1556 | 2024-05-09 | Passion UA                | W   | 1.000      | 0.372        | 0.057 (0.021)    | 1.000 (0.372)    | -         |    16.67 | bajmi, Demho, Ex1st, fr3nd, Sobol       |
|           62 |     1567 | 2024-05-09 | MOUZ NXT                  | W   | 1.000      | 0.372        | 0.157 (0.058)    | 0.950 (0.353)    | -         |    20.85 | bajmi, Demho, Ex1st, fr3nd, Sobol       |
|           61 |     1644 | 2024-05-08 | DASH                      | W   | 1.000      | -            | -                | -                | -         |     7.83 | bajmi, Demho, Ex1st, fr3nd, Sobol       |
|           60 |     1696 | 2024-05-07 | Permitta Esports          | W   | 1.000      | 0.435        | 0.029 (0.012)    | 1.000 (0.435)    | -         |    16.64 | bajmi, Demho, Ex1st, fr3nd, TOAO        |
|           59 |     1737 | 2024-05-06 | B8                        | L   | 1.000      | -            | -                | -                | -         |    -7.11 | bajmi, Demho, Ex1st, fr3nd, TOAO        |
|           58 |     1804 | 2024-05-04 | MOUZ NXT                  | W   | 1.000      | 0.435        | 0.157 (0.068)    | 0.950 (0.413)    | -         |    23.41 | bajmi, Demho, Ex1st, fr3nd, kadziu      |
|           57 |     1964 | 2024-05-01 | ENCE Academy              | W   | 1.000      | -            | -                | -                | -         |    12.89 | bajmi, Demho, Ex1st, fr3nd, kadziu      |
|           56 |     2027 | 2024-04-30 | EYEBALLERS                | L   | 1.000      | -            | -                | -                | -         |   -11.38 | bajmi, Demho, Ex1st, fr3nd, TOAO        |
|           55 |     2087 | 2024-04-29 | Nexus Gaming              | L   | 0.994      | -            | -                | -                | -         |   -13.96 | bajmi, Demho, Ex1st, fr3nd, TOAO        |
|           54 |     2216 | 2024-04-27 | Permitta Esports          | L   | 0.981      | -            | -                | -                | -         |   -12.26 | bajmi, Demho, Ex1st, fr3nd, TOAO        |
|           53 |     2274 | 2024-04-26 | Insilio                   | L   | 0.976      | -            | -                | -                | -         |   -11.44 | bajmi, Demho, Ex1st, fr3nd, TOAO        |
|           52 |     2435 | 2024-04-23 | ALTERNATE aTTaX           | L   | 0.955      | -            | -                | -                | -         |   -14.29 | bajmi, Demho, Ex1st, fr3nd, TOAO        |
|           51 |     2495 | 2024-04-21 | ThunderFlash              | L   | 0.943      | -            | -                | -                | -         |   -17.44 | bajmi, Demho, Ex1st, fr3nd, TOAO        |
|           50 |     2578 | 2024-04-20 | Permitta Esports          | W   | 0.937      | -            | -                | -                | -         |    16.70 | bajmi, Demho, Ex1st, fr3nd, TOAO        |
|           49 |     2647 | 2024-04-20 | ALTERNATE aTTaX           | L   | 0.935      | -            | -                | -                | -         |   -13.55 | bajmi, Demho, Ex1st, fr3nd, TOAO        |
|           48 |     2701 | 2024-04-19 | 9INE                      | W   | 0.930      | -            | -                | -                | -         |     5.77 | bajmi, Demho, Ex1st, fr3nd, TOAO        |
|           47 |     2771 | 2024-04-18 | MOUZ NXT                  | L   | 0.923      | -            | -                | -                | -         |    -7.68 | bajmi, Demho, Ex1st, fr3nd, TOAO        |
|           46 |     2789 | 2024-04-18 | Nexus Gaming              | W   | 0.922      | 0.384        | -                | 0.825 (0.292)    | -         |    15.90 | bajmi, Demho, Ex1st, fr3nd, TOAO        |
|           45 |     2853 | 2024-04-17 | ENCE                      | L   | 0.916      | -            | -                | -                | -         |    -1.84 | bajmi, Demho, Ex1st, fr3nd, TOAO        |
|           44 |     3202 | 2024-04-10 | AMKAL ESPORTS             | W   | 0.868      | 0.384        | 0.146 (0.049)    | 0.565 (0.189)    | -         |    21.88 | bajmi, Demho, Ex1st, fr3nd, TOAO        |
|           43 |     3411 | 2024-04-06 | Team Sampi                | L   | 0.842      | -            | -                | -                | -         |    -8.77 | bajmi, Demho, Ex1st, fr3nd, TOAO        |
|           42 |     3554 | 2024-04-03 | Permitta Esports          | W   | 0.823      | 0.384        | 0.029 (0.009)    | 1.000 (0.316)    | -         |    14.58 | bajmi, Demho, Ex1st, fr3nd, TOAO        |
|           41 |     3871 | 2024-03-26 | Heimo Esports             | L   | 0.771      | -            | -                | -                | -         |   -17.09 | bajmi, Demho, Ex1st, fr3nd, TOAO        |
|           40 |     4030 | 2024-03-22 | ThunderFlash              | L   | 0.744      | -            | -                | -                | -         |   -14.72 | bajmi, Demho, Ex1st, fr3nd, TOAO        |
|           39 |     4067 | 2024-03-21 | Illuminar Gaming          | L   | 0.738      | -            | -                | -                | -         |   -15.33 | bajmi, Demho, Ex1st, fr3nd, TOAO        |
|           38 |     4135 | 2024-03-20 | ex-Turów Zgorzelec Esport | W   | 0.730      | -            | -                | -                | -         |     7.00 | bajmi, Demho, Ex1st, fr3nd, TOAO        |
|           37 |     4172 | 2024-03-19 | LODIS                     | W   | 0.724      | -            | -                | -                | -         |     3.18 | bajmi, Demho, Ex1st, fr3nd, TOAO        |
|           36 |     4199 | 2024-03-18 | Mikstura1234              | W   | 0.718      | -            | -                | -                | -         |     4.83 | bajmi, Demho, Ex1st, fr3nd, TOAO        |
|           35 |     4717 | 2024-03-09 | kONO.ECF                  | L   | 0.657      | -            | -                | -                | -         |    -9.93 | bajmi, Demho, Ex1st, fr3nd, TOAO        |
|           34 |     4736 | 2024-03-09 | Team Sampi                | L   | 0.656      | -            | -                | -                | -         |    -9.71 | bajmi, Demho, Ex1st, fr3nd, TOAO        |
|           33 |     4882 | 2024-03-06 | INGLORIOUS                | L   | 0.637      | -            | -                | -                | -         |   -13.91 | bajmi, Demho, Ex1st, fr3nd, TOAO        |
|           32 |     4904 | 2024-03-06 | Permitta Esports          | L   | 0.636      | -            | -                | -                | -         |    -9.39 | bajmi, Demho, Ex1st, fr3nd, TOAO        |
|           31 |     5000 | 2024-03-04 | Nemiga Gaming             | L   | 0.625      | -            | -                | -                | -         |    -3.06 | bajmi, Demho, Ex1st, fr3nd, TOAO        |
|           30 |     5026 | 2024-03-04 | ex-Turów Zgorzelec Esport | W   | 0.625      | -            | -                | -                | -         |     5.65 | bajmi, Demho, Ex1st, fr3nd, TOAO        |
|           29 |     5127 | 2024-03-02 | kONO.ECF                  | L   | 0.612      | -            | -                | -                | -         |    -9.82 | bajmi, Demho, Ex1st, fr3nd, TOAO        |
|           28 |     5157 | 2024-03-02 | Sashi Esport              | W   | 0.611      | -            | -                | -                | -         |     5.07 | bajmi, Demho, Ex1st, fr3nd, TOAO        |
|           27 |     5214 | 2024-03-02 | Team Sampi                | W   | 0.608      | 0.371        | 0.039 (0.009)    | 0.665 (0.150)    | -         |     9.54 | bajmi, Demho, Ex1st, fr3nd, TOAO        |
|           26 |     5305 | 2024-02-28 | FAVBET Team               | L   | 0.591      | -            | -                | -                | -         |   -11.78 | bajmi, Demho, Ex1st, fr3nd, TOAO        |
|           25 |     5319 | 2024-02-28 | RUBY                      | L   | 0.591      | -            | -                | -                | -         |    -9.63 | bajmi, Demho, Ex1st, fr3nd, TOAO        |
|           24 |     5361 | 2024-02-27 | Eternal Fire Academy      | W   | 0.584      | -            | -                | -                | -         |     2.78 | bajmi, Demho, Ex1st, fr3nd, TOAO        |
|           23 |     5396 | 2024-02-26 | kONO.ECF                  | L   | 0.578      | -            | -                | -                | -         |   -10.12 | bajmi, Demho, Ex1st, fr3nd, TOAO        |
|           22 |     5448 | 2024-02-25 | DASH                      | W   | 0.571      | -            | -                | -                | -         |     3.51 | bajmi, Demho, Ex1st, fr3nd, TOAO        |
|           21 |     5977 | 2024-02-16 | SAW                       | L   | 0.511      | -            | -                | -                | -         |    -1.68 | bajmi, Demho, Ex1st, fr3nd, TOAO        |
|           20 |     6058 | 2024-02-15 | BetBoom Team              | L   | 0.503      | -            | -                | -                | -         |    -1.32 | bajmi, Demho, Ex1st, fr3nd, TOAO        |
|           19 |     6087 | 2024-02-14 | Natus Vincere             | L   | 0.498      | -            | -                | -                | -         |    -0.10 | bajmi, Demho, Ex1st, fr3nd, TOAO        |
|           18 |     6111 | 2024-02-14 | AMKAL ESPORTS             | W   | 0.496      | 0.143        | 0.146 (0.010)    | -                | 1 (0.496) |    12.47 | bajmi, Demho, Ex1st, fr3nd, TOAO        |
|           17 |     6295 | 2024-02-09 | HOTU                      | L   | 0.464      | -            | -                | -                | -         |    -9.68 | bajmi, Demho, Ex1st, fr3nd, TOAO        |
|           16 |     6457 | 2024-02-04 | Team Spirit Academy       | L   | 0.431      | -            | -                | -                | -         |   -10.51 | bajmi, Demho, Ex1st, fr3nd, TOAO        |
|           15 |     7344 | 2024-01-20 | KOI                       | W   | 0.330      | -            | -                | -                | -         |     5.31 | bajmi, Demho, Ex1st, fr3nd, TOAO        |
|           14 |     7412 | 2024-01-19 | ex-sYnck                  | W   | 0.323      | -            | -                | -                | -         |     2.14 | bajmi, Demho, Ex1st, fr3nd, TOAO        |
|           13 |     7461 | 2024-01-18 | Aurora Gaming             | W   | 0.318      | 0.143        | 0.492 (0.022)    | -                | -         |     9.51 | bajmi, Demho, Ex1st, fr3nd, TOAO        |
|           12 |     7475 | 2024-01-18 | Astralis                  | L   | 0.317      | -            | -                | -                | -         |    -0.17 | bajmi, Demho, Ex1st, fr3nd, TOAO        |
|           11 |     7552 | 2024-01-17 | Insilio                   | L   | 0.311      | -            | -                | -                | -         |    -5.66 | faydett, FpSSS, Pipw, Polt, sugaR       |
|           10 |     8050 | 2024-01-09 | KOI                       | W   | 0.259      | -            | -                | -                | -         |     4.21 | adamS, dav1g, JUST, mopoz, stadodo      |
|            9 |     8055 | 2024-01-09 | Fnatic                    | W   | 0.259      | -            | -                | -                | -         |     5.91 | bajmi, Demho, Ex1st, fr3nd, TOAO        |
|            8 |     8063 | 2024-01-09 | Sashi Esport              | W   | 0.258      | 0.143        | 0.172 (0.006)    | -                | -         |     5.49 | Cabbi, IceBerg, kwezz, Lucky, MistR     |
|            7 |     8077 | 2024-01-09 | Johnny Speeds             | W   | 0.258      | -            | -                | -                | -         |     5.18 | Chawzyyy, draken, HugoXD, RuStY, spooke |
|            6 |     8091 | 2024-01-09 | underrated                | W   | 0.257      | -            | -                | -                | -         |     0.59 | bajmi, Demho, Ex1st, fr3nd, TOAO        |
|            5 |     8110 | 2024-01-09 | JANO Esports              | W   | 0.257      | -            | -                | -                | -         |     0.63 | Aerial, allu, doto, jelo, Sm1llee       |
|            4 |     9155 | 2023-12-07 | Lausanne-Sport Esports    | L   | 0.038      | -            | -                | -                | -         |    -1.04 | bajmi, Demho, Ex1st, fr3nd, Klameczka   |
|            3 |     9214 | 2023-12-06 | Nemiga Gaming             | W   | 0.031      | -            | -                | -                | -         |     0.84 | bajmi, Demho, Ex1st, fr3nd, Klameczka   |
|            2 |     9281 | 2023-12-05 | Endpoint                  | L   | 0.025      | -            | -                | -                | -         |    -0.38 | bajmi, Demho, Ex1st, fr3nd, Klameczka   |
|            1 |     9445 | 2023-12-02 | ex-Turów Zgorzelec Esport | W   | 0.004      | -            | -                | -                | 1 (0.004) |     0.04 | bajmi, Demho, Ex1st, fr3nd, Klameczka   |

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
