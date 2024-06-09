### Roster Details<br />
Team Name: Nexus Gaming<br />
Roster: BTN, Ciocardau, ERSIN, ragga, XELLOW<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [129](../standings_global.md)<br />
Regional Rank: [89]( ../standings_europe.md)<br />
Final Rank Value:  814.0<br />
<br />
Final Rank Value (814.0) = Starting Rank Value (911.3) + Head To Head Adjustments (-97.3)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.287[<sup>1</sup>](#table2)
- Bounty Collected: 0.404[<sup>2</sup>](#table1)
- Opponent Network: 0.314[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.252<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 911.3
- 400 + ( ( 0.252 - 0.000 ) / ( 0.787 - 0.000 ) ) * 1600 = 911.3


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent                  | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                               |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|          111 |       95 | 2024-05-29 | VP.Prodigy                | L   | 1.000      | -            | -                | -                | -         |   -10.45 | BTN, Ciocardau, ERSIN, ragga, XELLOW |
|          110 |      172 | 2024-05-27 | The Prodigies             | L   | 1.000      | -            | -                | -                | -         |   -27.12 | BTN, Ciocardau, ERSIN, ragga, XELLOW |
|          109 |      219 | 2024-05-26 | Young Ninjas              | L   | 1.000      | -            | -                | -                | -         |   -14.81 | BTN, Ed1m, ERSIN, ragga, XELLOW      |
|          108 |      228 | 2024-05-26 | Copenhagen Wolves         | W   | 1.000      | -            | -                | -                | 0 (0.000) |     8.91 | BTN, Ciocardau, ERSIN, ragga, XELLOW |
|          107 |      235 | 2024-05-26 | Reason Gaming             | W   | 1.000      | -            | -                | -                | 0 (0.000) |    10.55 | BTN, Ed1m, ERSIN, ragga, XELLOW      |
|          106 |      420 | 2024-05-23 | Preasy Esport             | W   | 1.000      | 0.333        | -                | 0.705 (0.235)    | 0 (0.000) |    10.87 | BTN, Ed1m, ERSIN, ragga, XELLOW      |
|          105 |      502 | 2024-05-22 | GUN5 Esports              | L   | 1.000      | -            | -                | -                | -         |   -16.73 | BTN, ERSIN, ragga, s0und, XELLOW     |
|          104 |      598 | 2024-05-21 | Monte Gen                 | W   | 1.000      | -            | -                | -                | 0 (0.000) |    15.00 | BTN, Ed1m, ERSIN, ragga, XELLOW      |
|          103 |      608 | 2024-05-21 | Entropiq                  | L   | 1.000      | -            | -                | -                | -         |   -21.40 | BTN, ERSIN, ragga, s0und, XELLOW     |
|          102 |      620 | 2024-05-21 | Endpoint                  | W   | 1.000      | 0.372        | -                | 0.770 (0.287)    | 0 (0.000) |    15.53 | BTN, ERSIN, ragga, s0und, XELLOW     |
|          101 |      657 | 2024-05-20 | Lemoncats                 | W   | 1.000      | -            | -                | -                | 0 (0.000) |     4.44 | BTN, Ciocardau, ERSIN, ragga, XELLOW |
|          100 |      758 | 2024-05-19 | VaselineWorms             | L   | 1.000      | -            | -                | -                | -         |   -21.46 | BTN, ERSIN, ragga, s0und, XELLOW     |
|           99 |      764 | 2024-05-19 | Denial                    | W   | 1.000      | -            | -                | -                | 0 (0.000) |     5.53 | BTN, Ciocardau, ERSIN, ragga, XELLOW |
|           98 |      975 | 2024-05-17 | varcolacu1996             | W   | 1.000      | -            | -                | -                | 0 (0.000) |     3.91 | BTN, Ciocardau, ERSIN, ragga, XELLOW |
|           97 |      994 | 2024-05-17 | HyperSpirit               | W   | 1.000      | -            | -                | -                | 0 (0.000) |    12.90 | BTN, Ciocardau, ERSIN, ragga, XELLOW |
|           96 |     1021 | 2024-05-17 | Passion UA                | L   | 1.000      | -            | -                | -                | -         |   -11.62 | BTN, Ciocardau, ERSIN, ragga, XELLOW |
|           95 |     1173 | 2024-05-15 | kONO.ECF                  | W   | 1.000      | 0.372        | -                | 0.853 (0.318)    | 0 (0.000) |    19.48 | BTN, ERSIN, ragga, s0und, XELLOW     |
|           94 |     1219 | 2024-05-15 | Team Space                | L   | 1.000      | -            | -                | -                | -         |   -14.43 | BTN, Ciocardau, ERSIN, ragga, XELLOW |
|           93 |     1289 | 2024-05-14 | Rhyno Esports             | W   | 1.000      | 0.372        | 0.029 (0.011)    | -                | -         |    21.74 | BTN, ERSIN, ragga, s0und, XELLOW     |
|           92 |     1343 | 2024-05-13 | Team Sampi                | L   | 1.000      | -            | -                | -                | -         |    -8.74 | BTN, Ciocardau, ERSIN, ragga, XELLOW |
|           91 |     1386 | 2024-05-12 | V1dar Gaming              | L   | 1.000      | -            | -                | -                | -         |   -18.82 | BTN, ERSIN, ragga, s0und, XELLOW     |
|           90 |     1508 | 2024-05-10 | LEON Esports              | W   | 1.000      | -            | -                | -                | -         |    10.48 | BTN, ERSIN, ragga, s0und, XELLOW     |
|           89 |     1655 | 2024-05-08 | Passion UA                | W   | 1.000      | 0.372        | 0.057 (0.021)    | 1.000 (0.372)    | -         |    20.92 | BTN, ERSIN, ragga, s0und, XELLOW     |
|           88 |     1699 | 2024-05-07 | ADEPTS                    | W   | 1.000      | -            | -                | -                | -         |    10.71 | BTN, ERSIN, fnl, ragga, XELLOW       |
|           87 |     1708 | 2024-05-07 | ex-Turów Zgorzelec Esport | L   | 1.000      | -            | -                | -                | -         |   -17.42 | BTN, ERSIN, fnl, ragga, XELLOW       |
|           86 |     1921 | 2024-05-03 | ENCE Academy              | L   | 1.000      | -            | -                | -                | -         |   -18.27 | BTN, ERSIN, ragga, s0und, XELLOW     |
|           85 |     2006 | 2024-05-01 | ARCRED                    | L   | 1.000      | -            | -                | -                | -         |   -14.24 | BTN, ERSIN, ragga, s0und, XELLOW     |
|           84 |     2024 | 2024-05-01 | Insilio                   | L   | 1.000      | -            | -                | -                | -         |   -11.44 | BTN, ERSIN, ragga, s0und, XELLOW     |
|           83 |     2082 | 2024-04-30 | Fnatic                    | L   | 1.000      | -            | -                | -                | -         |    -5.20 | BTN, ERSIN, ragga, s0und, XELLOW     |
|           82 |     2101 | 2024-04-29 | Endpoint                  | L   | 0.997      | -            | -                | -                | -         |   -12.93 | BTN, ERSIN, ragga, s0und, XELLOW     |
|           81 |     2112 | 2024-04-29 | VP.Prodigy                | L   | 0.996      | -            | -                | -                | -         |   -20.02 | BTN, ERSIN, ragga, s0und, XELLOW     |
|           80 |     2117 | 2024-04-29 | LEON Esports              | W   | 0.995      | -            | -                | -                | -         |     8.41 | BTN, ERSIN, ragga, s0und, XELLOW     |
|           79 |     2122 | 2024-04-29 | ENTERPRISE esports        | W   | 0.994      | 0.384        | -                | 0.898 (0.343)    | -         |    14.63 | BTN, ERSIN, ragga, s0und, XELLOW     |
|           78 |     2164 | 2024-04-28 | brazylijski luz           | L   | 0.988      | -            | -                | -                | -         |   -16.72 | BTN, ERSIN, ragga, s0und, XELLOW     |
|           77 |     2348 | 2024-04-25 | Metizport                 | W   | 0.970      | 0.384        | 0.088 (0.033)    | 0.698 (0.260)    | -         |    22.09 | BTN, ERSIN, ragga, s0und, XELLOW     |
|           76 |     2369 | 2024-04-25 | Grannys Knockers          | L   | 0.969      | -            | -                | -                | -         |   -18.05 | BTN, ERSIN, ragga, s0und, XELLOW     |
|           75 |     2437 | 2024-04-24 | AMKAL ESPORTS             | L   | 0.962      | -            | -                | -                | -         |    -5.41 | BTN, ERSIN, ragga, s0und, XELLOW     |
|           74 |     2480 | 2024-04-23 | Illuminar Gaming          | L   | 0.955      | -            | -                | -                | -         |   -18.50 | BTN, ERSIN, ragga, s0und, XELLOW     |
|           73 |     2516 | 2024-04-22 | Zero Tenacity             | L   | 0.949      | -            | -                | -                | -         |   -12.34 | BTN, ERSIN, ragga, s0und, XELLOW     |
|           72 |     2538 | 2024-04-21 | Young Ninjas              | W   | 0.944      | 0.500        | 0.043 (0.020)    | -                | -         |    14.78 | BTN, ERSIN, ragga, s0und, XELLOW     |
|           71 |     2555 | 2024-04-21 | PARIVISION                | L   | 0.943      | -            | -                | -                | -         |   -17.18 | BTN, ERSIN, ragga, s0und, XELLOW     |
|           70 |     2674 | 2024-04-20 | Permitta Esports          | W   | 0.936      | 0.500        | 0.025 (0.012)    | 1.000 (0.468)    | -         |    16.74 | BTN, ERSIN, ragga, s0und, XELLOW     |
|           69 |     2806 | 2024-04-18 | Young Ninjas              | L   | 0.924      | -            | -                | -                | -         |   -14.15 | BTN, ERSIN, ragga, s0und, XELLOW     |
|           68 |     2845 | 2024-04-18 | ENTERPRISE esports        | L   | 0.922      | -            | -                | -                | -         |   -15.09 | BTN, ERSIN, ragga, s0und, XELLOW     |
|           67 |     3146 | 2024-04-12 | HyperSpirit               | L   | 0.883      | -            | -                | -                | -         |   -20.94 | BTN, ERSIN, ragga, s0und, XELLOW     |
|           66 |     3266 | 2024-04-10 | B8                        | W   | 0.869      | 0.384        | 0.168 (0.056)    | 0.963 (0.322)    | -         |    19.02 | BTN, ERSIN, ragga, s0und, XELLOW     |
|           65 |     3530 | 2024-04-05 | SINNERS Esports           | L   | 0.837      | -            | -                | -                | -         |    -9.91 | BTN, ERSIN, ragga, s0und, XELLOW     |
|           64 |     3724 | 2024-04-01 | Sashi Esport              | W   | 0.808      | 0.384        | 0.154 (0.048)    | 1.000 (0.311)    | -         |    16.48 | BTN, ERSIN, ragga, s0und, XELLOW     |
|           63 |     4020 | 2024-03-25 | Sashi Esport              | L   | 0.764      | -            | -                | -                | -         |    -8.09 | BTN, ERSIN, ragga, s0und, XELLOW     |
|           62 |     4677 | 2024-03-12 | Nemiga Gaming             | W   | 0.677      | 0.371        | 0.358 (0.090)    | -                | -         |    17.83 | BTN, ERSIN, ragga, s0und, XELLOW     |
|           61 |     4738 | 2024-03-11 | RUBY                      | W   | 0.671      | -            | -                | -                | -         |    10.72 | BTN, ERSIN, ragga, s0und, XELLOW     |
|           60 |     4835 | 2024-03-09 | INGLORIOUS                | W   | 0.657      | -            | -                | -                | -         |     7.07 | BTN, ERSIN, ragga, s0und, XELLOW     |
|           59 |     4877 | 2024-03-08 | FAVBET Team               | W   | 0.651      | -            | -                | -                | -         |    10.01 | BTN, ERSIN, ragga, s0und, XELLOW     |
|           58 |     5141 | 2024-03-04 | FORZE Esports             | L   | 0.625      | -            | -                | -                | -         |    -6.76 | BTN, ERSIN, ragga, s0und, XELLOW     |
|           57 |     5160 | 2024-03-04 | KOMNATA                   | W   | 0.625      | -            | -                | -                | -         |     4.21 | BTN, ERSIN, ragga, s0und, XELLOW     |
|           56 |     5231 | 2024-03-03 | TSM                       | L   | 0.617      | -            | -                | -                | -         |   -13.34 | BTN, ERSIN, ragga, s0und, XELLOW     |
|           55 |     5240 | 2024-03-03 | Zero Tenacity             | W   | 0.617      | 0.371        | 0.147 (0.034)    | 1.000 (0.229)    | -         |    12.46 | BTN, ERSIN, ragga, s0und, XELLOW     |
|           54 |     5276 | 2024-03-02 | GUN5 Esports              | W   | 0.612      | -            | -                | -                | -         |     3.71 | BTN, ERSIN, ragga, s0und, XELLOW     |
|           53 |     5303 | 2024-03-02 | Aurora Young Blud         | W   | 0.611      | -            | -                | -                | -         |     6.40 | BTN, ERSIN, ragga, s0und, XELLOW     |
|           52 |     5388 | 2024-03-01 | Passion UA                | W   | 0.603      | 0.371        | 0.057 (0.013)    | -                | -         |    10.37 | BTN, ERSIN, ragga, s0und, XELLOW     |
|           51 |     5422 | 2024-02-29 | INGLORIOUS                | L   | 0.597      | -            | -                | -                | -         |   -12.28 | BTN, ERSIN, ragga, s0und, XELLOW     |
|           50 |     5474 | 2024-02-28 | Aurora Young Blud         | W   | 0.590      | -            | -                | -                | -         |     6.17 | BTN, ERSIN, ragga, s0und, XELLOW     |
|           49 |     5573 | 2024-02-26 | esmagaB                   | W   | 0.577      | -            | -                | -                | -         |     6.81 | BTN, ERSIN, ragga, s0und, XELLOW     |
|           48 |     5707 | 2024-02-24 | L&G                       | W   | 0.563      | -            | -                | -                | -         |     1.92 | BTN, ERSIN, ragga, s0und, XELLOW     |
|           47 |     5945 | 2024-02-20 | ex-Guild Eagles           | L   | 0.536      | -            | -                | -                | -         |    -6.60 | BTN, ERSIN, ragga, s0und, XELLOW     |
|           46 |     5998 | 2024-02-19 | Monte                     | L   | 0.531      | -            | -                | -                | -         |    -1.32 | BTN, ERSIN, ragga, s0und, XELLOW     |
|           45 |     6015 | 2024-02-19 | Astralis                  | L   | 0.530      | -            | -                | -                | -         |    -0.23 | BTN, ERSIN, ragga, s0und, XELLOW     |
|           44 |     6553 | 2024-02-07 | V1dar Gaming              | W   | 0.451      | -            | -                | -                | -         |     3.25 | BTN, ERSIN, ragga, s0und, XELLOW     |
|           43 |     6601 | 2024-02-05 | Lemondogs                 | L   | 0.438      | -            | -                | -                | -         |   -11.70 | BTN, ERSIN, ragga, s0und, XELLOW     |
|           42 |     6627 | 2024-02-05 | Gaimin Gladiators         | L   | 0.437      | -            | -                | -                | -         |    -1.71 | BTN, ERSIN, ragga, s0und, XELLOW     |
|           41 |     6672 | 2024-02-04 | BIG Academy               | L   | 0.429      | -            | -                | -                | -         |    -9.85 | BTN, ERSIN, ragga, s0und, XELLOW     |
|           40 |     6708 | 2024-02-03 | 500                       | L   | 0.424      | -            | -                | -                | -         |    -9.05 | BTN, ERSIN, ragga, s0und, XELLOW     |
|           39 |     6726 | 2024-02-03 | Jake Bube                 | W   | 0.424      | -            | -                | -                | -         |     0.66 | BTN, ERSIN, ragga, s0und, XELLOW     |
|           38 |     6767 | 2024-02-03 | AIRLYA                    | L   | 0.423      | -            | -                | -                | -         |   -12.10 | BTN, ERSIN, ragga, s0und, XELLOW     |
|           37 |     6837 | 2024-02-02 | Royalty                   | W   | 0.416      | -            | -                | -                | -         |     0.62 | BTN, ERSIN, ragga, s0und, XELLOW     |
|           36 |     6938 | 2024-01-31 | ALTERNATE aTTaX           | W   | 0.403      | -            | -                | -                | -         |     7.51 | BTN, ERSIN, ragga, s0und, XELLOW     |
|           35 |     7106 | 2024-01-28 | Passion UA                | L   | 0.382      | -            | -                | -                | -         |    -4.80 | BTN, ERSIN, ragga, s0und, XELLOW     |
|           34 |     7263 | 2024-01-26 | GamerLegion Academy       | W   | 0.370      | -            | -                | -                | -         |     4.20 | BTN, ERSIN, ragga, s0und, XELLOW     |
|           33 |     7276 | 2024-01-26 | VaselineWorms             | W   | 0.370      | -            | -                | -                | -         |     2.86 | BTN, ERSIN, ragga, s0und, XELLOW     |
|           32 |     7522 | 2024-01-21 | ex-sYnck                  | W   | 0.336      | -            | -                | -                | -         |     3.02 | BTN, ERSIN, ragga, s0und, XELLOW     |
|           31 |     7570 | 2024-01-20 | OG                        | L   | 0.331      | -            | -                | -                | -         |    -1.92 | BTN, ERSIN, ragga, s0und, XELLOW     |
|           30 |     7603 | 2024-01-20 | BIG                       | W   | 0.329      | -            | -                | -                | -         |     9.76 | BTN, ERSIN, ragga, s0und, XELLOW     |
|           29 |     7646 | 2024-01-19 | SINNERS Esports           | W   | 0.324      | -            | -                | -                | -         |     6.74 | BTN, ERSIN, ragga, s0und, XELLOW     |
|           28 |     7705 | 2024-01-18 | Gaimin Gladiators         | L   | 0.318      | -            | -                | -                | -         |    -1.09 | BTN, ERSIN, ragga, s0und, XELLOW     |
|           27 |     7721 | 2024-01-18 | 9Pandas                   | L   | 0.317      | -            | -                | -                | -         |    -1.83 | BTN, ERSIN, ragga, s0und, XELLOW     |
|           26 |     7871 | 2024-01-16 | Endpoint                  | W   | 0.305      | -            | -                | -                | -         |     5.35 | BTN, ERSIN, ragga, s0und, XELLOW     |
|           25 |     7880 | 2024-01-16 | FAVBET Team               | W   | 0.305      | -            | -                | -                | -         |     4.06 | BTN, ERSIN, ragga, s0und, XELLOW     |
|           24 |     7900 | 2024-01-16 | Alliance                  | W   | 0.304      | -            | -                | -                | -         |     4.32 | BTN, ERSIN, ragga, s0und, XELLOW     |
|           23 |     7908 | 2024-01-16 | The Chosen Few            | W   | 0.304      | -            | -                | -                | -         |     2.88 | BTN, ERSIN, ragga, s0und, XELLOW     |
|           22 |     8041 | 2024-01-13 | OG                        | L   | 0.283      | -            | -                | -                | -         |    -1.43 | BTN, ERSIN, ragga, s0und, XELLOW     |
|           21 |     8085 | 2024-01-12 | Soda Gaming               | W   | 0.278      | -            | -                | -                | -         |     1.85 | BTN, ERSIN, ragga, s0und, XELLOW     |
|           20 |     8099 | 2024-01-12 | JANO Esports              | W   | 0.278      | -            | -                | -                | -         |     0.86 | BTN, ERSIN, ragga, s0und, XELLOW     |
|           19 |     8129 | 2024-01-12 | Astralis Talent           | L   | 0.275      | -            | -                | -                | -         |    -4.05 | BTN, ERSIN, ragga, s0und, XELLOW     |
|           18 |     8287 | 2024-01-10 | WOPA Esport               | W   | 0.262      | -            | -                | -                | -         |     3.23 | BTN, ERSIN, ragga, s0und, XELLOW     |
|           17 |     8355 | 2024-01-09 | ex-K10                    | L   | 0.257      | -            | -                | -                | -         |    -4.28 | BTN, ERSIN, ragga, s0und, XELLOW     |
|           16 |     8386 | 2024-01-09 | Team Space                | W   | 0.257      | -            | -                | -                | -         |     3.54 | BTN, ERSIN, ragga, s0und, XELLOW     |
|           15 |     8436 | 2024-01-08 | Zero Tenacity             | L   | 0.249      | -            | -                | -                | -         |    -1.98 | BTN, CHANKY, ERSIN, ragga, XELLOW    |
|           14 |     8467 | 2024-01-06 | Astralis Talent           | L   | 0.236      | -            | -                | -                | -         |    -3.48 | BTN, ERSIN, ragga, s0und, XELLOW     |
|           13 |     8475 | 2024-01-05 | Monte Gen                 | L   | 0.230      | -            | -                | -                | -         |    -4.88 | BTN, CHANKY, ERSIN, ragga, XELLOW    |
|           12 |     8651 | 2023-12-19 | MOUZ NXT                  | L   | 0.117      | -            | -                | -                | -         |    -0.85 | BTN, ragga, s0und, smekk, XELLOW     |
|           11 |     8653 | 2023-12-19 | ex-Anonymo Esports        | L   | 0.117      | -            | -                | -                | -         |    -2.78 | BTN, ragga, s0und, smekk, XELLOW     |
|           10 |     8669 | 2023-12-18 | MOUZ NXT                  | W   | 0.110      | -            | -                | -                | -         |     2.68 | BTN, ragga, s0und, smekk, XELLOW     |
|            9 |     8679 | 2023-12-18 | Astralis Talent           | L   | 0.109      | -            | -                | -                | -         |    -1.63 | BTN, ragga, s0und, smekk, XELLOW     |
|            8 |     8745 | 2023-12-17 | brazylijski luz           | L   | 0.102      | -            | -                | -                | -         |    -2.03 | BTN, ragga, s0und, smekk, XELLOW     |
|            7 |     9009 | 2023-12-15 | detoks                    | W   | 0.090      | -            | -                | -                | -         |     0.26 | BTN, ragga, s0und, smekk, XELLOW     |
|            6 |     9023 | 2023-12-15 | Sashi Esport              | L   | 0.088      | -            | -                | -                | -         |    -2.45 | BTN, ragga, s0und, smekk, XELLOW     |
|            5 |     9155 | 2023-12-12 | WOPA Esport               | W   | 0.069      | -            | -                | -                | -         |     0.82 | BTN, ragga, s0und, smekk, XELLOW     |
|            4 |     9225 | 2023-12-10 | Natus Vincere Junior      | L   | 0.057      | -            | -                | -                | -         |    -1.18 | BTN, ragga, s0und, smekk, XELLOW     |
|            3 |     9460 | 2023-12-07 | Pompa Team                | W   | 0.035      | -            | -                | -                | -         |     0.09 | BTN, ragga, s0und, smekk, XELLOW     |
|            2 |     9497 | 2023-12-06 | GamerLegion Academy       | W   | 0.031      | -            | -                | -                | -         |     0.40 | BTN, ragga, s0und, smekk, XELLOW     |
|            1 |     9665 | 2023-12-03 | Lazer Cats                | W   | 0.009      | -            | -                | -                | -         |     0.02 | BTN, ragga, s0und, smekk, XELLOW     |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($1,000.00)
- Divide that value by the 5th highest value among all rosters ($300,806.11)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
