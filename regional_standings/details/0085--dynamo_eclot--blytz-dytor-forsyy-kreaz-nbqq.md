### Roster Details<br />
Team Name: Dynamo Eclot<br />
Roster: Blytz, Dytor, forsyy, kreaz, nbqq<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [85](../standings_global.md)<br />
Regional Rank: [59]( ../standings_europe.md)<br />
Final Rank Value:  895.3<br />
<br />
Final Rank Value (895.3) = Starting Rank Value (1100.1) + Head To Head Adjustments (-204.9)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.496[<sup>1</sup>](#table2)
- Bounty Collected: 0.377[<sup>2</sup>](#table1)
- Opponent Network: 0.279[<sup>2</sup>](#table1)
- LAN Wins: 0.223[<sup>2</sup>](#table1)

The average of these factors is 0.344<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1100.1
- 400 + ( ( 0.344 - 0.000 ) / ( 0.786 - 0.000 ) ) * 1600 = 1100.1


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent                  | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                            |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|          104 |      221 | 2024-05-26 | NOM Esports               | W   | 1.000      | -            | -                | -                | 0 (0.000) |     6.26 | Blytz, Dytor, forsyy, kreaz, nbqq |
|          103 |      236 | 2024-05-26 | Permitta Esports          | L   | 1.000      | -            | -                | -                | -         |   -20.08 | Blytz, Dytor, forsyy, kreaz, nbqq |
|          102 |      346 | 2024-05-24 | HyperSpirit               | W   | 1.000      | -            | -                | -                | 0 (0.000) |    10.58 | Blytz, Dytor, forsyy, kreaz, nbqq |
|          101 |      515 | 2024-05-22 | Preasy Esport             | L   | 1.000      | -            | -                | -                | -         |   -22.76 | Blytz, Dytor, forsyy, kreaz, nbqq |
|          100 |      589 | 2024-05-21 | DASH                      | W   | 1.000      | -            | -                | -                | 0 (0.000) |     6.00 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           99 |      694 | 2024-05-20 | LEON Esports              | L   | 1.000      | -            | -                | -                | -         |   -24.03 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           98 |      779 | 2024-05-19 | BRUTE                     | W   | 1.000      | -            | -                | -                | 0 (0.000) |     3.16 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           97 |      899 | 2024-05-18 | Team Flow                 | W   | 1.000      | -            | -                | -                | 0 (0.000) |     3.27 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           96 |      991 | 2024-05-17 | Pera Esports              | L   | 1.000      | -            | -                | -                | -         |   -16.28 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           95 |      995 | 2024-05-17 | LODIS                     | W   | 1.000      | -            | -                | -                | 0 (0.000) |     3.56 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           94 |     1088 | 2024-05-16 | BRUTE                     | L   | 1.000      | -            | -                | -                | -         |   -28.83 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           93 |     1244 | 2024-05-14 | ex-K10                    | W   | 1.000      | -            | -                | -                | 0 (0.000) |     7.69 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           92 |     1319 | 2024-05-13 | RoundsGG                  | W   | 1.000      | -            | -                | -                | -         |     3.03 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           91 |     1336 | 2024-05-13 | Johnny Speeds             | L   | 1.000      | -            | -                | -                | -         |   -13.15 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           90 |     1531 | 2024-05-10 | Verdant                   | W   | 1.000      | 0.333        | -                | 1.000 (0.333)    | -         |    12.94 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           89 |     1563 | 2024-05-09 | MOUZ NXT                  | L   | 1.000      | -            | -                | -                | -         |   -14.03 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           88 |     1647 | 2024-05-08 | FAVBET Team               | W   | 1.000      | 0.333        | -                | 0.666 (0.222)    | -         |    15.23 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           87 |     1713 | 2024-05-06 | LOADING                   | L   | 1.000      | -            | -                | -                | -         |   -28.28 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           86 |     1739 | 2024-05-06 | Viperio                   | W   | 1.000      | -            | -                | -                | -         |     7.03 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           85 |     2020 | 2024-04-30 | MOUZ NXT                  | L   | 1.000      | -            | -                | -                | -         |   -12.55 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           84 |     2073 | 2024-04-29 | 1win                      | W   | 0.996      | 0.500        | 0.050 (0.025)    | 0.887 (0.442)    | -         |    15.32 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           83 |     2134 | 2024-04-28 | Astralis Talent           | W   | 0.988      | -            | -                | -                | -         |    10.95 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           82 |     2172 | 2024-04-27 | MOUZ NXT                  | L   | 0.984      | -            | -                | -                | -         |   -12.33 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           81 |     2334 | 2024-04-25 | Team Sampi                | W   | 0.968      | 0.371        | 0.039 (0.014)    | 0.665 (0.238)    | -         |    16.46 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           80 |     2375 | 2024-04-24 | Team Spirit Academy       | L   | 0.963      | -            | -                | -                | -         |   -25.55 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           79 |     2384 | 2024-04-24 | ARCRED                    | L   | 0.963      | -            | -                | -                | -         |   -22.16 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           78 |     2434 | 2024-04-23 | Team Sampi                | W   | 0.955      | 0.371        | 0.039 (0.014)    | 0.665 (0.235)    | -         |    15.02 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           77 |     2508 | 2024-04-21 | Rhyno Esports             | L   | 0.943      | -            | -                | -                | -         |   -17.07 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           76 |     2520 | 2024-04-21 | MOUZ NXT                  | W   | 0.942      | 0.371        | 0.157 (0.055)    | 0.950 (0.331)    | -         |    17.66 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           75 |     2581 | 2024-04-20 | Aurora Young Blud         | L   | 0.937      | -            | -                | -                | -         |   -23.80 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           74 |     2699 | 2024-04-19 | FLuffy Gangsters          | W   | 0.930      | -            | -                | -                | -         |     2.45 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           73 |     2733 | 2024-04-19 | SINNERS Esports           | W   | 0.928      | -            | -                | -                | -         |    15.67 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           72 |     2777 | 2024-04-18 | VP.Prodigy                | W   | 0.922      | 0.333        | -                | 0.752 (0.231)    | -         |     7.50 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           71 |     2864 | 2024-04-17 | Alliance                  | W   | 0.915      | -            | -                | -                | -         |     9.73 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           70 |     2900 | 2024-04-16 | Raptors Esports Club      | L   | 0.911      | -            | -                | -                | -         |   -19.55 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           69 |     2967 | 2024-04-15 | Astralis Talent           | W   | 0.901      | -            | -                | -                | -         |     8.15 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           68 |     3084 | 2024-04-12 | DMS                       | W   | 0.882      | -            | -                | -                | -         |     7.79 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           67 |     3182 | 2024-04-10 | UNiTY esports             | W   | 0.870      | 0.333        | 0.021 (0.006)    | 0.766 (0.222)    | -         |     9.46 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           66 |     3192 | 2024-04-10 | Rhyno Esports             | L   | 0.869      | -            | -                | -                | -         |   -15.43 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           65 |     3264 | 2024-04-09 | ALTERNATE aTTaX           | L   | 0.862      | -            | -                | -                | -         |   -16.66 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           64 |     3454 | 2024-04-05 | WOPA Esport               | L   | 0.835      | -            | -                | -                | -         |   -21.18 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           63 |     3520 | 2024-04-04 | ex-Turów Zgorzelec Esport | W   | 0.828      | -            | -                | -                | -         |     5.04 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           62 |     3571 | 2024-04-03 | Permitta Esports          | W   | 0.822      | 0.333        | 0.029 (0.008)    | 1.000 (0.274)    | -         |     9.64 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           61 |     3631 | 2024-04-01 | Astralis Talent           | W   | 0.808      | -            | -                | -                | -         |     8.14 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           60 |     3633 | 2024-04-01 | Astralis Talent           | L   | 0.808      | -            | -                | -                | -         |   -17.76 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           59 |     3661 | 2024-03-31 | UNiTY esports             | L   | 0.801      | -            | -                | -                | -         |   -18.24 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           58 |     3885 | 2024-03-26 | Passion UA                | L   | 0.771      | -            | -                | -                | -         |   -14.99 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           57 |     3901 | 2024-03-26 | Sashi Esport              | W   | 0.769      | 0.333        | 0.172 (0.044)    | 1.000 (0.256)    | -         |    12.41 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           56 |     3979 | 2024-03-23 | Raptors Esports Club      | W   | 0.751      | -            | -                | -                | -         |     5.67 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           55 |     4045 | 2024-03-22 | UNiTY esports             | L   | 0.743      | -            | -                | -                | -         |   -18.20 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           54 |     4125 | 2024-03-20 | Raptors Esports Club      | W   | 0.731      | -            | -                | -                | -         |     5.13 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           53 |     4139 | 2024-03-20 | ex-Turów Zgorzelec Esport | W   | 0.730      | -            | -                | -                | -         |     3.84 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           52 |     4174 | 2024-03-19 | LEON Esports              | W   | 0.723      | -            | -                | -                | -         |     3.68 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           51 |     4260 | 2024-03-17 | SINNERS Esports           | W   | 0.711      | -            | -                | -                | 1 (0.711) |     9.53 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           50 |     4318 | 2024-03-16 | UNiTY esports             | W   | 0.704      | -            | -                | -                | 1 (0.704) |     6.02 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           49 |     4337 | 2024-03-16 | UNiTY esports             | L   | 0.702      | -            | -                | -                | -         |   -16.52 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           48 |     4368 | 2024-03-15 | ARROW                     | W   | 0.698      | -            | -                | -                | -         |     2.94 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           47 |     4382 | 2024-03-15 | Team Sampi                | W   | 0.696      | -            | -                | -                | 1 (0.696) |     8.74 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           46 |     4503 | 2024-03-13 | Permitta Esports          | L   | 0.683      | -            | -                | -                | -         |   -12.65 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           45 |     4522 | 2024-03-13 | Permitta Esports          | L   | 0.682      | -            | -                | -                | -         |   -13.39 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           44 |     4592 | 2024-03-11 | Gorillas                  | W   | 0.671      | -            | -                | -                | -         |     1.35 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           43 |     4635 | 2024-03-11 | Entropiq                  | L   | 0.668      | -            | -                | -                | -         |   -18.44 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           42 |     4671 | 2024-03-10 | Zero Tenacity             | L   | 0.663      | -            | -                | -                | -         |   -11.99 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           41 |     4795 | 2024-03-07 | Wolves eSports            | W   | 0.645      | -            | -                | -                | -         |     1.38 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           40 |     4813 | 2024-03-07 | Team Universe             | W   | 0.644      | -            | -                | -                | -         |     0.74 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           39 |     4954 | 2024-03-05 | SINNERS Esports           | L   | 0.631      | -            | -                | -                | -         |   -12.94 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           38 |     4975 | 2024-03-05 | 9INE                      | W   | 0.629      | -            | -                | -                | -         |     1.17 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           37 |     5038 | 2024-03-04 | BRUTE                     | W   | 0.624      | -            | -                | -                | -         |     0.97 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           36 |     5106 | 2024-03-03 | Metizport                 | W   | 0.616      | 0.384        | 0.088 (0.021)    | -                | -         |     7.91 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           35 |     5135 | 2024-03-02 | Metizport                 | L   | 0.611      | -            | -                | -                | -         |   -11.97 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           34 |     5245 | 2024-03-01 | Viperio                   | W   | 0.602      | -            | -                | -                | -         |     1.47 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           33 |     5341 | 2024-02-28 | Permitta Esports          | W   | 0.588      | -            | -                | -                | -         |     6.29 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           32 |     5380 | 2024-02-27 | MOUZ NXT                  | W   | 0.583      | 0.333        | 0.157 (0.031)    | -                | -         |     9.93 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           31 |     5426 | 2024-02-26 | ex-Turów Zgorzelec Esport | W   | 0.575      | -            | -                | -                | -         |     2.99 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           30 |     5468 | 2024-02-25 | Team Sampi                | W   | 0.568      | 0.333        | 0.039 (0.007)    | -                | -         |     5.64 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           29 |     5559 | 2024-02-24 | Permitta Esports          | L   | 0.562      | -            | -                | -                | -         |   -11.94 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           28 |     5668 | 2024-02-22 | BIG Academy               | W   | 0.549      | -            | -                | -                | -         |     2.36 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           27 |     5739 | 2024-02-21 | Permitta Esports          | W   | 0.542      | -            | -                | -                | -         |     5.88 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           26 |     5785 | 2024-02-20 | Natus Vincere Junior      | W   | 0.536      | -            | -                | -                | -         |     2.99 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           25 |     5795 | 2024-02-20 | Lilmix                    | W   | 0.535      | -            | -                | -                | -         |     3.72 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           24 |     5848 | 2024-02-19 | Permitta Esports          | L   | 0.529      | -            | -                | -                | -         |   -11.31 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           23 |     5944 | 2024-02-17 | Natus Vincere Junior      | W   | 0.517      | -            | -                | -                | -         |     2.69 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           22 |     6061 | 2024-02-15 | MOUZ NXT                  | L   | 0.502      | -            | -                | -                | -         |    -7.96 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           21 |     6119 | 2024-02-14 | ex-K10                    | W   | 0.496      | -            | -                | -                | -         |     2.65 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           20 |     6249 | 2024-02-11 | Lilmix                    | W   | 0.475      | -            | -                | -                | -         |     3.15 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           19 |     6256 | 2024-02-10 | Verdant                   | W   | 0.471      | -            | -                | -                | -         |     5.71 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           18 |     6259 | 2024-02-10 | 0to100                    | W   | 0.471      | -            | -                | -                | -         |     0.34 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           17 |     6263 | 2024-02-10 | Virtuoso Squad            | W   | 0.471      | -            | -                | -                | -         |     0.50 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           16 |     6314 | 2024-02-09 | brazylijski luz           | W   | 0.462      | -            | -                | -                | -         |     2.59 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           15 |     6443 | 2024-02-05 | WOPA Esport               | W   | 0.435      | -            | -                | -                | -         |     2.42 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           14 |     6597 | 2024-02-02 | 9Pandas                   | L   | 0.417      | -            | -                | -                | -         |    -4.77 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           13 |     6609 | 2024-02-02 | ex-sYnck                  | W   | 0.417      | -            | -                | -                | -         |     1.58 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           12 |     6621 | 2024-02-02 | UNiTY esports             | W   | 0.417      | -            | -                | -                | -         |     3.63 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           11 |     6757 | 2024-01-30 | Sprout                    | L   | 0.397      | -            | -                | -                | -         |   -11.56 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           10 |     6793 | 2024-01-29 | Metizport                 | W   | 0.392      | -            | -                | -                | -         |     4.19 | Blytz, Dytor, forsyy, kreaz, nbqq |
|            9 |     6824 | 2024-01-29 | Ninjas in Pyjamas         | W   | 0.392      | -            | -                | -                | -         |     1.79 | Blytz, Dytor, forsyy, kreaz, nbqq |
|            8 |     7688 | 2024-01-16 | Zero Tenacity             | L   | 0.302      | -            | -                | -                | -         |    -5.07 | Blytz, Dytor, forsyy, kreaz, nbqq |
|            7 |     7756 | 2024-01-14 | Permitta Esports          | L   | 0.289      | -            | -                | -                | -         |    -6.20 | Blytz, Dytor, forsyy, kreaz, nbqq |
|            6 |     7834 | 2024-01-12 | Team Walkover             | L   | 0.278      | -            | -                | -                | -         |    -8.45 | Blytz, Dytor, forsyy, kreaz, nbqq |
|            5 |     8082 | 2024-01-09 | Sashi Esport              | L   | 0.257      | -            | -                | -                | -         |    -4.41 | Blytz, Dytor, forsyy, kreaz, nbqq |
|            4 |     8098 | 2024-01-09 | Rhyno Esports             | W   | 0.257      | -            | -                | -                | -         |     3.25 | Blytz, Dytor, forsyy, kreaz, nbqq |
|            3 |     8114 | 2024-01-09 | Team LRP Poland           | W   | 0.257      | -            | -                | -                | -         |     0.89 | Blytz, Dytor, forsyy, kreaz, nbqq |
|            2 |     8182 | 2024-01-08 | Aurora Young Blud         | W   | 0.249      | -            | -                | -                | -         |     1.19 | Blytz, Dytor, forsyy, kreaz, nbqq |
|            1 |     8236 | 2024-01-04 | SINNERS Academy           | W   | 0.222      | -            | -                | -                | -         |     0.55 | Blytz, Dytor, forsyy, kreaz, nbqq |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($29,091.57)
- Divide that value by the 5th highest value among all rosters ($300,806.11)
- The final value (0.10) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-05-13 |      1.000 | $3,000.00      | $3,000.00       |
| 2024-04-25 |      0.968 | $11,000.00     | $10,645.56      |
| 2024-04-21 |      0.943 | $1,250.00      | $1,179.17       |
| 2024-04-06 |      0.841 | $1,500.00      | $1,261.67       |
| 2024-03-23 |      0.751 | $3,500.00      | $2,629.38       |
| 2024-03-17 |      0.711 | $7,792.81      | $5,538.31       |
| 2024-02-28 |      0.588 | $5,000.00      | $2,941.67       |
| 2024-02-21 |      0.542 | $3,500.00      | $1,895.83       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
