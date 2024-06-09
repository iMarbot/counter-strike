### Roster Details<br />
Team Name: ALTERNATE aTTaX<br />
Roster: ArroW, awzek, FreeZe, hyped, PerX<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [85](../standings_global.md)<br />
Regional Rank: [60]( ../standings_europe.md)<br />
Final Rank Value:  903.0<br />
<br />
Final Rank Value (903.0) = Starting Rank Value (1032.2) + Head To Head Adjustments (-129.2)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.438[<sup>1</sup>](#table2)
- Bounty Collected: 0.400[<sup>2</sup>](#table1)
- Opponent Network: 0.339[<sup>2</sup>](#table1)
- LAN Wins: 0.067[<sup>2</sup>](#table1)

The average of these factors is 0.311<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1032.2
- 400 + ( ( 0.311 - 0.000 ) / ( 0.787 - 0.000 ) ) * 1600 = 1032.2


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent            | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                             |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|          109 |      271 | 2024-05-25 | TeamOrangeGaming    | W   | 1.000      | -            | -                | -                | 0 (0.000) |    11.74 | ArroW, awzek, FreeZe, hyped, PerX  |
|          108 |      373 | 2024-05-24 | Endpoint            | L   | 1.000      | -            | -                | -                | -         |   -16.34 | ArroW, awzek, FreeZe, hyped, PerX  |
|          107 |      410 | 2024-05-23 | ARROW               | W   | 1.000      | -            | -                | -                | 0 (0.000) |     9.25 | ArroW, awzek, FreeZe, hyped, PerX  |
|          106 |      425 | 2024-05-23 | Entropiq            | W   | 1.000      | -            | -                | -                | 0 (0.000) |     9.08 | ArroW, awzek, FreeZe, hyped, PerX  |
|          105 |      464 | 2024-05-22 | VP.Prodigy          | L   | 1.000      | -            | -                | -                | -         |   -16.73 | ArroW, awzek, FreeZe, hyped, PerX  |
|          104 |      816 | 2024-05-19 | Passion UA          | L   | 1.000      | -            | -                | -                | -         |   -14.39 | ArroW, awzek, FreeZe, hyped, PerX  |
|          103 |      941 | 2024-05-18 | Sashi Esport        | L   | 1.000      | -            | -                | -                | -         |    -4.59 | ArroW, awzek, FreeZe, hyped, PerX  |
|          102 |      976 | 2024-05-17 | EYEBALLERS          | L   | 1.000      | -            | -                | -                | -         |   -16.74 | ArroW, awzek, FreeZe, hyped, PerX  |
|          101 |     1092 | 2024-05-16 | 9Pandas             | L   | 1.000      | -            | -                | -                | -         |    -9.50 | ArroW, awzek, FreeZe, hyped, PerX  |
|          100 |     1116 | 2024-05-16 | SINNERS Esports     | L   | 1.000      | -            | -                | -                | -         |   -14.36 | ArroW, awzek, FreeZe, hyped, PerX  |
|           99 |     1261 | 2024-05-14 | Pera Esports        | L   | 1.000      | -            | -                | -                | -         |   -19.58 | ArroW, awzek, FreeZe, hyped, PerX  |
|           98 |     1302 | 2024-05-14 | Endpoint            | W   | 1.000      | 0.435        | -                | 0.770 (0.335)    | 0 (0.000) |    15.15 | ArroW, awzek, FreeZe, hyped, PerX  |
|           97 |     1333 | 2024-05-13 | EVOPLAY             | W   | 1.000      | -            | -                | -                | 0 (0.000) |     3.22 | ArroW, awzek, FreeZe, hyped, PerX  |
|           96 |     1358 | 2024-05-12 | SNOGARD Dragons     | W   | 1.000      | -            | -                | -                | 0 (0.000) |     7.16 | ArroW, awzek, FreeZe, hyped, PerX  |
|           95 |     1363 | 2024-05-12 | Sissi State Punks   | W   | 1.000      | -            | -                | -                | 0 (0.000) |     4.84 | ArroW, awzek, FreeZe, hyped, PerX  |
|           94 |     1748 | 2024-05-06 | Sashi Esport        | L   | 1.000      | -            | -                | -                | -         |    -4.91 | ArroW, awzek, FreeZe, hyped, PerX  |
|           93 |     1956 | 2024-05-02 | MOUZ NXT            | L   | 1.000      | -            | -                | -                | -         |   -10.65 | ArroW, awzek, FreeZe, hyped, PerX  |
|           92 |     2023 | 2024-05-01 | Team Sampi          | W   | 1.000      | 0.143        | 0.039 (0.006)    | -                | -         |    16.90 | ArroW, awzek, FreeZe, hyped, PerX  |
|           91 |     2035 | 2024-05-01 | Sangal Esports      | W   | 1.000      | 0.500        | 0.166 (0.083)    | 0.658 (0.329)    | -         |    21.07 | ArroW, awzek, FreeZe, hyped, PerX  |
|           90 |     2061 | 2024-04-30 | Endpoint            | L   | 1.000      | -            | -                | -                | -         |   -14.50 | ArroW, awzek, FreeZe, hyped, PerX  |
|           89 |     2076 | 2024-04-30 | Team Sampi          | W   | 1.000      | 0.143        | 0.039 (0.006)    | -                | -         |    17.97 | ArroW, awzek, FreeZe, hyped, PerX  |
|           88 |     2145 | 2024-04-28 | Passion UA          | W   | 0.990      | 0.500        | 0.057 (0.028)    | 1.000 (0.495)    | -         |    16.07 | ArroW, awzek, FreeZe, hyped, PerX  |
|           87 |     2289 | 2024-04-26 | Astralis Talent     | L   | 0.977      | -            | -                | -                | -         |   -17.84 | ArroW, awzek, FreeZe, hyped, skyye |
|           86 |     2319 | 2024-04-26 | Gaimin Gladiators   | W   | 0.975      | 0.500        | 0.092 (0.045)    | 0.727 (0.354)    | -         |    26.37 | ArroW, awzek, FreeZe, hyped, PerX  |
|           85 |     2365 | 2024-04-25 | Team Space          | W   | 0.969      | -            | -                | -                | -         |    11.29 | ArroW, awzek, FreeZe, hyped, PerX  |
|           84 |     2421 | 2024-04-24 | Astralis Talent     | L   | 0.963      | -            | -                | -                | -         |   -17.05 | ArroW, FreeZe, hyped, PerX, skyye  |
|           83 |     2483 | 2024-04-23 | ENTERPRISE esports  | W   | 0.955      | 0.384        | -                | 0.898 (0.329)    | -         |    15.32 | ArroW, FreeZe, hyped, PerX, skyye  |
|           82 |     2486 | 2024-04-22 | Permitta Esports    | L   | 0.954      | -            | -                | -                | -         |   -11.74 | ArroW, FreeZe, hyped, PerX, skyye  |
|           81 |     2520 | 2024-04-22 | ENCE Academy        | W   | 0.948      | -            | -                | -                | -         |    12.33 | ArroW, FreeZe, hyped, PerX, skyye  |
|           80 |     2553 | 2024-04-21 | MOUZ NXT            | L   | 0.943      | -            | -                | -                | -         |    -7.93 | ArroW, awzek, FreeZe, hyped, skyye |
|           79 |     2584 | 2024-04-21 | Team Sampi          | L   | 0.941      | -            | -                | -                | -         |   -10.65 | ArroW, FreeZe, hyped, PerX, skyye  |
|           78 |     2618 | 2024-04-20 | Team Space          | L   | 0.937      | -            | -                | -                | -         |   -19.42 | ArroW, awzek, FreeZe, hyped, PerX  |
|           77 |     2701 | 2024-04-20 | ENTERPRISE esports  | W   | 0.935      | 0.500        | -                | 0.898 (0.420)    | -         |    14.79 | ArroW, awzek, FreeZe, hyped, skyye |
|           76 |     2766 | 2024-04-19 | Passion UA          | W   | 0.929      | 0.371        | 0.057 (0.019)    | 1.000 (0.344)    | -         |    16.84 | ArroW, FreeZe, hyped, PerX, skyye  |
|           75 |     2781 | 2024-04-19 | Zero Tenacity       | L   | 0.929      | -            | -                | -                | -         |   -12.76 | ArroW, awzek, FreeZe, hyped, skyye |
|           74 |     2839 | 2024-04-18 | HAVU Gaming         | L   | 0.922      | -            | -                | -                | -         |   -22.35 | ArroW, awzek, FreeZe, hyped, skyye |
|           73 |     2850 | 2024-04-18 | BLEED Esports       | L   | 0.921      | -            | -                | -                | -         |    -5.37 | ArroW, awzek, FreeZe, hyped, skyye |
|           72 |     2986 | 2024-04-16 | Aurora Young Blud   | W   | 0.909      | -            | -                | -                | -         |     6.89 | ArroW, awzek, FreeZe, hyped, skyye |
|           71 |     3011 | 2024-04-15 | Zero Tenacity       | L   | 0.904      | -            | -                | -                | -         |   -13.85 | ArroW, awzek, FreeZe, hyped, skyye |
|           70 |     3116 | 2024-04-13 | Alliance            | W   | 0.888      | -            | -                | -                | -         |    11.54 | ArroW, FreeZe, hyped, PerX, skyye  |
|           69 |     3343 | 2024-04-09 | Dynamo Eclot        | W   | 0.862      | 0.371        | 0.097 (0.031)    | 0.940 (0.300)    | -         |    16.47 | ArroW, FreeZe, hyped, PerX, skyye  |
|           68 |     3393 | 2024-04-08 | SINNERS Esports     | L   | 0.855      | -            | -                | -                | -         |    -8.72 | ArroW, awzek, FreeZe, hyped, skyye |
|           67 |     3590 | 2024-04-04 | Rebels Gaming       | L   | 0.830      | -            | -                | -                | -         |    -7.37 | ArroW, awzek, FreeZe, hyped, PerX  |
|           66 |     3704 | 2024-04-02 | AMKAL ESPORTS       | L   | 0.815      | -            | -                | -                | -         |    -6.58 | ArroW, awzek, FreeZe, hyped, skyye |
|           65 |     3875 | 2024-03-27 | FAVBET Team         | L   | 0.778      | -            | -                | -                | -         |   -13.40 | ArroW, awzek, FreeZe, hyped, skyye |
|           64 |     3890 | 2024-03-27 | ex-Guild Eagles     | W   | 0.777      | -            | -                | -                | -         |    12.31 | ArroW, awzek, FreeZe, hyped, skyye |
|           63 |     3905 | 2024-03-27 | Heimo Esports       | W   | 0.777      | -            | -                | -                | -         |     5.85 | ArroW, awzek, FreeZe, hyped, skyye |
|           62 |     3969 | 2024-03-26 | ex-KRC Genk Esports | W   | 0.771      | -            | -                | -                | -         |     4.81 | ArroW, awzek, FreeZe, hyped, skyye |
|           61 |     4014 | 2024-03-25 | ex-Sprout           | W   | 0.764      | -            | -                | -                | -         |     4.42 | ArroW, awzek, FreeZe, hyped, PerX  |
|           60 |     4552 | 2024-03-14 | Metizport           | W   | 0.690      | 0.384        | 0.088 (0.023)    | -                | -         |    15.75 | ArroW, awzek, FreeZe, hyped, skyye |
|           59 |     4607 | 2024-03-13 | SINNERS Esports     | L   | 0.684      | -            | -                | -                | -         |    -8.21 | ArroW, awzek, FreeZe, hyped, PerX  |
|           58 |     4795 | 2024-03-10 | Entropiq            | L   | 0.663      | -            | -                | -                | -         |   -16.15 | ArroW, awzek, FreeZe, hyped, skyye |
|           57 |     4802 | 2024-03-10 | MOUZ NXT            | L   | 0.662      | -            | -                | -                | -         |    -5.99 | ArroW, awzek, FreeZe, hyped, skyye |
|           56 |     4896 | 2024-03-08 | Sashi Esport        | W   | 0.648      | 0.371        | 0.154 (0.037)    | 1.000 (0.240)    | -         |    13.22 | ArroW, awzek, FreeZe, hyped, skyye |
|           55 |     4987 | 2024-03-06 | brazylijski luz     | W   | 0.638      | -            | -                | -                | -         |     6.16 | ArroW, awzek, FreeZe, hyped, PerX  |
|           54 |     5123 | 2024-03-05 | Sashi Esport        | W   | 0.629      | 0.384        | 0.154 (0.037)    | 1.000 (0.242)    | -         |    13.50 | ArroW, awzek, FreeZe, hyped, skyye |
|           53 |     5144 | 2024-03-04 | Passion UA          | L   | 0.625      | -            | -                | -                | -         |    -9.30 | ArroW, awzek, FreeZe, hyped, skyye |
|           52 |     5197 | 2024-03-04 | Passion UA          | L   | 0.622      | -            | -                | -                | -         |    -9.79 | ArroW, awzek, FreeZe, hyped, skyye |
|           51 |     5335 | 2024-03-02 | 500                 | L   | 0.610      | -            | -                | -                | -         |   -12.73 | ArroW, awzek, FreeZe, hyped, skyye |
|           50 |     5391 | 2024-03-01 | Fnatic              | L   | 0.603      | -            | -                | -                | -         |    -5.58 | ArroW, awzek, FreeZe, hyped, skyye |
|           49 |     5485 | 2024-02-28 | BetBoom Team        | L   | 0.589      | -            | -                | -                | -         |    -1.55 | ArroW, awzek, FreeZe, hyped, skyye |
|           48 |     5523 | 2024-02-27 | RUBY                | L   | 0.584      | -            | -                | -                | -         |    -9.45 | ArroW, awzek, FreeZe, hyped, skyye |
|           47 |     5552 | 2024-02-26 | Johnny Speeds       | W   | 0.578      | -            | -                | -                | -         |    10.84 | ArroW, awzek, FreeZe, hyped, skyye |
|           46 |     5582 | 2024-02-26 | Endpoint            | W   | 0.575      | -            | -                | -                | -         |     8.49 | ArroW, awzek, FreeZe, hyped, skyye |
|           45 |     5610 | 2024-02-25 | Alliance            | L   | 0.570      | -            | -                | -                | -         |   -11.75 | ArroW, awzek, FreeZe, hyped, skyye |
|           44 |     5992 | 2024-02-19 | 1win                | L   | 0.531      | -            | -                | -                | -         |    -8.22 | ArroW, awzek, FreeZe, PANIX, PerX  |
|           43 |     6039 | 2024-02-18 | Young Ninjas        | L   | 0.524      | -            | -                | -                | -         |    -9.66 | ArroW, awzek, FreeZe, PANIX, PerX  |
|           42 |     6220 | 2024-02-15 | VaselineWorms       | W   | 0.504      | -            | -                | -                | -         |     3.15 | ArroW, awzek, FreeZe, PANIX, PerX  |
|           41 |     6231 | 2024-02-15 | Soda Gaming         | W   | 0.503      | -            | -                | -                | -         |     2.52 | ArroW, awzek, FreeZe, PANIX, PerX  |
|           40 |     6386 | 2024-02-12 | LODIS               | W   | 0.484      | -            | -                | -                | -         |     2.11 | ArroW, awzek, FreeZe, PANIX, PerX  |
|           39 |     6417 | 2024-02-11 | Entropiq            | W   | 0.478      | -            | -                | -                | -         |     2.58 | ArroW, awzek, FreeZe, PANIX, PerX  |
|           38 |     6580 | 2024-02-06 | 500                 | W   | 0.443      | -            | -                | -                | -         |     4.40 | awzek, FreeZe, Goody, PANIX, PerX  |
|           37 |     6659 | 2024-02-04 | brazylijski luz     | W   | 0.431      | -            | -                | -                | -         |     4.33 | awzek, FreeZe, Goody, PANIX, PerX  |
|           36 |     6669 | 2024-02-04 | V1dar Gaming        | L   | 0.430      | -            | -                | -                | -         |   -11.43 | awzek, FreeZe, Goody, PANIX, PerX  |
|           35 |     6683 | 2024-02-04 | Sangal Esports      | L   | 0.428      | -            | -                | -                | -         |    -4.70 | awzek, FreeZe, Goody, PANIX, PerX  |
|           34 |     6774 | 2024-02-03 | TSM                 | L   | 0.422      | -            | -                | -                | -         |   -10.20 | awzek, FreeZe, Goody, PANIX, PerX  |
|           33 |     6904 | 2024-02-01 | Sangal Esports      | L   | 0.408      | -            | -                | -                | -         |    -4.49 | awzek, FreeZe, Goody, PANIX, PerX  |
|           32 |     6917 | 2024-01-31 | GamerLegion Academy | L   | 0.404      | -            | -                | -                | -         |    -9.16 | awzek, FreeZe, Goody, PANIX, PerX  |
|           31 |     6930 | 2024-01-31 | Kappa Bar           | W   | 0.404      | -            | -                | -                | -         |     0.89 | awzek, FreeZe, Goody, PANIX, PerX  |
|           30 |     6938 | 2024-01-31 | Nexus Gaming        | L   | 0.403      | -            | -                | -                | -         |    -7.51 | awzek, FreeZe, Goody, PANIX, PerX  |
|           29 |     6988 | 2024-01-30 | Sprout              | W   | 0.396      | -            | -                | -                | -         |     1.61 | awzek, FreeZe, Goody, PANIX, PerX  |
|           28 |     7022 | 2024-01-29 | kONO.ECF            | L   | 0.392      | -            | -                | -                | -         |    -8.28 | awzek, FreeZe, Goody, PANIX, PerX  |
|           27 |     7283 | 2024-01-26 | Entropiq            | W   | 0.369      | -            | -                | -                | -         |     1.56 | awzek, FreeZe, Goody, PANIX, PerX  |
|           26 |     7354 | 2024-01-24 | ex-Guild Eagles     | L   | 0.357      | -            | -                | -                | -         |    -5.91 | awzek, FreeZe, Goody, PANIX, PerX  |
|           25 |     7416 | 2024-01-23 | Pera Esports        | L   | 0.351      | -            | -                | -                | -         |    -6.76 | awzek, FreeZe, Goody, PANIX, PerX  |
|           24 |     7422 | 2024-01-23 | ex-Guild Eagles     | L   | 0.350      | -            | -                | -                | -         |    -6.17 | awzek, FreeZe, Goody, PANIX, PerX  |
|           23 |     7452 | 2024-01-22 | Viperio             | W   | 0.344      | -            | -                | -                | -         |     0.85 | awzek, FreeZe, Goody, PANIX, PerX  |
|           22 |     7469 | 2024-01-22 | Rebels Gaming       | L   | 0.344      | -            | -                | -                | -         |    -4.28 | awzek, FreeZe, Goody, PANIX, PerX  |
|           21 |     7476 | 2024-01-22 | Team Sampi          | W   | 0.344      | -            | -                | -                | -         |     4.49 | awzek, FreeZe, Goody, PANIX, PerX  |
|           20 |     8121 | 2024-01-12 | showmakerz          | L   | 0.278      | -            | -                | -                | -         |    -8.20 | awzek, FreeZe, Goody, PANIX, PerX  |
|           19 |     8175 | 2024-01-11 | Preasy Esport       | W   | 0.271      | -            | -                | -                | 1 (0.271) |     2.73 | awzek, FreeZe, Goody, PANIX, PerX  |
|           18 |     8188 | 2024-01-11 | Lilmix              | L   | 0.270      | -            | -                | -                | -         |    -7.93 | awzek, FreeZe, Goody, PANIX, PerX  |
|           17 |     8192 | 2024-01-11 | Preasy Esport       | W   | 0.270      | -            | -                | -                | 1 (0.270) |     2.69 | awzek, FreeZe, Goody, PANIX, PerX  |
|           16 |     8509 | 2024-01-03 | THE SUSPECT         | W   | 0.218      | -            | -                | -                | -         |     0.60 | awzek, FreeZe, Goody, PANIX, PerX  |
|           15 |     8513 | 2024-01-03 | Ovoshi              | W   | 0.218      | -            | -                | -                | -         |     0.20 | awzek, FreeZe, Goody, PANIX, PerX  |
|           14 |     8879 | 2023-12-16 | BIG Academy         | W   | 0.097      | -            | -                | -                | 1 (0.097) |     0.51 | awzek, FreeZe, PANIX, PerX, Spiidi |
|           13 |     9151 | 2023-12-12 | ex-Preasy Esport    | L   | 0.070      | -            | -                | -                | -         |    -1.45 | awzek, FreeZe, PANIX, PerX, Spiidi |
|           12 |     9246 | 2023-12-10 | GODSENT             | W   | 0.056      | -            | -                | -                | -         |     0.20 | awzek, FreeZe, PANIX, PerX, Spiidi |
|           11 |     9298 | 2023-12-09 | lajtbitexe          | L   | 0.050      | -            | -                | -                | -         |    -1.42 | awzek, FreeZe, PANIX, PerX, Spiidi |
|           10 |     9367 | 2023-12-08 | Zero Tenacity       | W   | 0.044      | -            | -                | -                | -         |     0.83 | awzek, FreeZe, PANIX, PerX, Spiidi |
|            9 |     9388 | 2023-12-08 | Sprout              | W   | 0.042      | -            | -                | -                | -         |     0.10 | awzek, FreeZe, PANIX, PerX, Spiidi |
|            8 |     9425 | 2023-12-07 | TUSTE CHOPAKI       | W   | 0.038      | -            | -                | -                | -         |     0.05 | awzek, FreeZe, PANIX, PerX, Spiidi |
|            7 |     9445 | 2023-12-07 | ex-Anonymo Esports  | L   | 0.037      | -            | -                | -                | -         |    -1.00 | awzek, FreeZe, PANIX, PerX, Spiidi |
|            6 |     9503 | 2023-12-06 | The Witchers        | W   | 0.031      | -            | -                | -                | -         |     0.14 | awzek, FreeZe, PANIX, PerX, Spiidi |
|            5 |     9522 | 2023-12-06 | ex-sYnck            | W   | 0.029      | -            | -                | -                | -         |     0.14 | awzek, FreeZe, PANIX, PerX, Spiidi |
|            4 |     9574 | 2023-12-05 | lajtbitexe          | L   | 0.024      | -            | -                | -                | -         |    -0.69 | awzek, FreeZe, PANIX, PerX, Spiidi |
|            3 |     9622 | 2023-12-04 | Entropiq            | W   | 0.016      | -            | -                | -                | -         |     0.05 | awzek, FreeZe, PANIX, PerX, Spiidi |
|            2 |     9626 | 2023-12-04 | ex-Guild Eagles     | L   | 0.015      | -            | -                | -                | -         |    -0.29 | awzek, FreeZe, PANIX, PerX, Spiidi |
|            1 |     9773 | 2023-12-02 | Team Space          | W   | 0.003      | -            | -                | -                | -         |     0.03 | awzek, FreeZe, PANIX, PerX, Spiidi |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($15,704.75)
- Divide that value by the 5th highest value among all rosters ($300,806.11)
- The final value (0.05) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-05-22 |      1.000 | $1,000.00      | $1,000.00       |
| 2024-05-03 |      1.000 | $12,500.00     | $12,500.00      |
| 2024-04-25 |      0.968 | $1,000.00      | $967.78         |
| 2023-12-16 |      0.097 | $8,180.59      | $790.79         |
| 2023-12-13 |      0.077 | $1,250.00      | $96.18          |
| 2023-12-12 |      0.070 | $5,000.00      | $350.00         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
