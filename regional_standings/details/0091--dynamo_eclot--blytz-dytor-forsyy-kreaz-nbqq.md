### Roster Details<br />
Team Name: Dynamo Eclot<br />
Roster: Blytz, Dytor, forsyy, kreaz, nbqq<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [91](../standings_global.md)<br />
Regional Rank: [64]( ../standings_europe.md)<br />
Final Rank Value:  887.0<br />
<br />
Final Rank Value (887.0) = Starting Rank Value (1103.6) + Head To Head Adjustments (-216.6)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.496[<sup>1</sup>](#table2)
- Bounty Collected: 0.376[<sup>2</sup>](#table1)
- Opponent Network: 0.289[<sup>2</sup>](#table1)
- LAN Wins: 0.223[<sup>2</sup>](#table1)

The average of these factors is 0.346<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1103.6
- 400 + ( ( 0.346 - 0.000 ) / ( 0.787 - 0.000 ) ) * 1600 = 1103.6


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
|          107 |      229 | 2024-05-26 | NOM Esports               | W   | 1.000      | -            | -                | -                | 0 (0.000) |     6.57 | Blytz, Dytor, forsyy, kreaz, nbqq |
|          106 |      244 | 2024-05-26 | Permitta Esports          | L   | 1.000      | -            | -                | -                | -         |   -19.13 | Blytz, Dytor, forsyy, kreaz, nbqq |
|          105 |      355 | 2024-05-24 | HyperSpirit               | W   | 1.000      | -            | -                | -                | 0 (0.000) |    10.96 | Blytz, Dytor, forsyy, kreaz, nbqq |
|          104 |      522 | 2024-05-22 | Preasy Esport             | L   | 1.000      | -            | -                | -                | -         |   -22.30 | Blytz, Dytor, forsyy, kreaz, nbqq |
|          103 |      600 | 2024-05-21 | DASH                      | W   | 1.000      | -            | -                | -                | 0 (0.000) |     6.96 | Blytz, Dytor, forsyy, kreaz, nbqq |
|          102 |      705 | 2024-05-20 | LEON Esports              | L   | 1.000      | -            | -                | -                | -         |   -23.48 | Blytz, Dytor, forsyy, kreaz, nbqq |
|          101 |      791 | 2024-05-19 | BRUTE                     | W   | 1.000      | -            | -                | -                | 0 (0.000) |     3.36 | Blytz, Dytor, forsyy, kreaz, nbqq |
|          100 |      911 | 2024-05-18 | Team Flow                 | W   | 1.000      | -            | -                | -                | 0 (0.000) |     3.48 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           99 |     1003 | 2024-05-17 | Pera Esports              | L   | 1.000      | -            | -                | -                | -         |   -16.11 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           98 |     1007 | 2024-05-17 | LODIS                     | W   | 1.000      | -            | -                | -                | 0 (0.000) |     4.04 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           97 |     1098 | 2024-05-16 | BRUTE                     | L   | 1.000      | -            | -                | -                | -         |   -28.63 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           96 |     1254 | 2024-05-14 | ex-K10                    | W   | 1.000      | -            | -                | -                | 0 (0.000) |     7.96 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           95 |     1331 | 2024-05-13 | RoundsGG                  | W   | 1.000      | -            | -                | -                | -         |     3.77 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           94 |     1348 | 2024-05-13 | Johnny Speeds             | L   | 1.000      | -            | -                | -                | -         |   -12.48 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           93 |     1546 | 2024-05-10 | Verdant                   | W   | 1.000      | 0.333        | -                | 1.000 (0.333)    | -         |    13.96 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           92 |     1579 | 2024-05-09 | MOUZ NXT                  | L   | 1.000      | -            | -                | -                | -         |   -13.12 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           91 |     1665 | 2024-05-08 | FAVBET Team               | W   | 1.000      | 0.333        | -                | 0.845 (0.282)    | -         |    15.13 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           90 |     1733 | 2024-05-06 | LOADING                   | L   | 1.000      | -            | -                | -                | -         |   -28.15 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           89 |     1762 | 2024-05-06 | Viperio                   | W   | 1.000      | -            | -                | -                | -         |     7.65 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           88 |     2051 | 2024-04-30 | MOUZ NXT                  | L   | 1.000      | -            | -                | -                | -         |   -11.59 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           87 |     2108 | 2024-04-29 | 1win                      | W   | 0.996      | 0.500        | 0.050 (0.025)    | 0.898 (0.447)    | -         |    15.90 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           86 |     2169 | 2024-04-28 | Astralis Talent           | W   | 0.988      | -            | -                | -                | -         |    11.79 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           85 |     2207 | 2024-04-27 | MOUZ NXT                  | L   | 0.984      | -            | -                | -                | -         |   -11.25 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           84 |     2375 | 2024-04-25 | Team Sampi                | W   | 0.968      | 0.371        | 0.039 (0.014)    | 0.677 (0.243)    | -         |    17.53 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           83 |     2407 | 2024-04-24 | ex-KRC Genk Esports       | L   | 0.964      | -            | -                | -                | -         |   -24.62 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           82 |     2418 | 2024-04-24 | Team Spirit Academy       | L   | 0.963      | -            | -                | -                | -         |   -25.28 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           81 |     2428 | 2024-04-24 | ARCRED                    | L   | 0.963      | -            | -                | -                | -         |   -22.23 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           80 |     2482 | 2024-04-23 | Team Sampi                | W   | 0.955      | 0.371        | 0.039 (0.014)    | 0.677 (0.239)    | -         |    15.08 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           79 |     2561 | 2024-04-21 | Rhyno Esports             | L   | 0.943      | -            | -                | -                | -         |   -16.55 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           78 |     2573 | 2024-04-21 | MOUZ NXT                  | W   | 0.942      | 0.371        | 0.157 (0.055)    | 0.977 (0.341)    | -         |    17.96 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           77 |     2634 | 2024-04-20 | Aurora Young Blud         | L   | 0.937      | -            | -                | -                | -         |   -23.71 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           76 |     2755 | 2024-04-19 | FLuffy Gangsters          | W   | 0.930      | -            | -                | -                | -         |     2.96 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           75 |     2789 | 2024-04-19 | SINNERS Esports           | W   | 0.928      | -            | -                | -                | -         |    16.92 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           74 |     2833 | 2024-04-18 | VP.Prodigy                | W   | 0.922      | 0.333        | -                | 0.829 (0.255)    | -         |     8.04 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           73 |     2921 | 2024-04-17 | Alliance                  | W   | 0.915      | -            | -                | -                | -         |     9.71 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           72 |     2958 | 2024-04-16 | Raptors Esports Club      | L   | 0.911      | -            | -                | -                | -         |   -19.70 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           71 |     3032 | 2024-04-15 | Astralis Talent           | W   | 0.901      | -            | -                | -                | -         |     8.25 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           70 |     3150 | 2024-04-12 | DMS                       | W   | 0.882      | -            | -                | -                | -         |     8.14 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           69 |     3256 | 2024-04-10 | UNiTY esports             | W   | 0.870      | 0.333        | 0.021 (0.006)    | 0.766 (0.222)    | -         |     9.51 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           68 |     3267 | 2024-04-10 | Rhyno Esports             | L   | 0.869      | -            | -                | -                | -         |   -15.13 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           67 |     3343 | 2024-04-09 | ALTERNATE aTTaX           | L   | 0.862      | -            | -                | -                | -         |   -16.47 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           66 |     3538 | 2024-04-05 | WOPA Esport               | L   | 0.835      | -            | -                | -                | -         |   -21.09 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           65 |     3607 | 2024-04-04 | ex-Turów Zgorzelec Esport | W   | 0.828      | -            | -                | -                | -         |     5.22 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           64 |     3658 | 2024-04-03 | Permitta Esports          | W   | 0.822      | 0.333        | 0.025 (0.007)    | 1.000 (0.274)    | -         |    10.10 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           63 |     3723 | 2024-04-01 | Astralis Talent           | W   | 0.808      | -            | -                | -                | -         |     8.32 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           62 |     3726 | 2024-04-01 | Astralis Talent           | L   | 0.808      | -            | -                | -                | -         |   -17.58 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           61 |     3754 | 2024-03-31 | UNiTY esports             | L   | 0.801      | -            | -                | -                | -         |   -18.17 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           60 |     3982 | 2024-03-26 | Passion UA                | L   | 0.771      | -            | -                | -                | -         |   -14.74 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           59 |     3998 | 2024-03-26 | Sashi Esport              | W   | 0.769      | 0.333        | 0.154 (0.039)    | 1.000 (0.256)    | -         |    12.77 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           58 |     4077 | 2024-03-23 | Raptors Esports Club      | W   | 0.751      | -            | -                | -                | -         |     5.61 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           57 |     4143 | 2024-03-22 | UNiTY esports             | L   | 0.743      | -            | -                | -                | -         |   -18.14 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           56 |     4225 | 2024-03-20 | Raptors Esports Club      | W   | 0.731      | -            | -                | -                | -         |     5.07 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           55 |     4241 | 2024-03-20 | ex-Turów Zgorzelec Esport | W   | 0.730      | -            | -                | -                | -         |     4.04 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           54 |     4277 | 2024-03-19 | LEON Esports              | W   | 0.723      | -            | -                | -                | -         |     3.78 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           53 |     4365 | 2024-03-17 | SINNERS Esports           | W   | 0.711      | -            | -                | -                | 1 (0.711) |    10.20 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           52 |     4424 | 2024-03-16 | UNiTY esports             | W   | 0.704      | -            | -                | -                | 1 (0.704) |     6.08 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           51 |     4444 | 2024-03-16 | UNiTY esports             | L   | 0.702      | -            | -                | -                | -         |   -16.46 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           50 |     4476 | 2024-03-15 | ARROW                     | W   | 0.698      | -            | -                | -                | -         |     3.03 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           49 |     4491 | 2024-03-15 | Team Sampi                | W   | 0.696      | -            | -                | -                | 1 (0.696) |     8.98 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           48 |     4499 | 2024-03-15 | Sashi Esport              | L   | 0.695      | -            | -                | -                | -         |   -11.51 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           47 |     4618 | 2024-03-13 | Permitta Esports          | L   | 0.683      | -            | -                | -                | -         |   -12.39 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           46 |     4641 | 2024-03-13 | Permitta Esports          | L   | 0.682      | -            | -                | -                | -         |   -13.11 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           45 |     4714 | 2024-03-11 | Gorillas                  | W   | 0.671      | -            | -                | -                | -         |     1.27 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           44 |     4758 | 2024-03-11 | Entropiq                  | L   | 0.668      | -            | -                | -                | -         |   -18.49 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           43 |     4796 | 2024-03-10 | Zero Tenacity             | L   | 0.663      | -            | -                | -                | -         |   -12.50 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           42 |     4924 | 2024-03-07 | Wolves eSports            | W   | 0.645      | -            | -                | -                | -         |     1.33 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           41 |     4942 | 2024-03-07 | Phantom Troupe            | W   | 0.644      | -            | -                | -                | -         |     0.85 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           40 |     5096 | 2024-03-05 | SINNERS Esports           | L   | 0.631      | -            | -                | -                | -         |   -12.59 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           39 |     5120 | 2024-03-05 | 9INE                      | W   | 0.629      | -            | -                | -                | -         |     1.13 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           38 |     5184 | 2024-03-04 | BRUTE                     | W   | 0.624      | -            | -                | -                | -         |     0.94 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           37 |     5254 | 2024-03-03 | Metizport                 | W   | 0.616      | 0.384        | 0.088 (0.021)    | -                | -         |     7.81 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           36 |     5283 | 2024-03-02 | Metizport                 | L   | 0.611      | -            | -                | -                | -         |   -12.07 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           35 |     5394 | 2024-03-01 | Viperio                   | W   | 0.602      | -            | -                | -                | -         |     1.49 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           34 |     5493 | 2024-02-28 | Permitta Esports          | W   | 0.588      | -            | -                | -                | -         |     6.34 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           33 |     5534 | 2024-02-27 | MOUZ NXT                  | W   | 0.583      | 0.333        | 0.157 (0.031)    | -                | -         |    10.02 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           32 |     5539 | 2024-02-27 | ex-sYnck                  | W   | 0.582      | -            | -                | -                | -         |     2.41 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           31 |     5584 | 2024-02-26 | ex-Turów Zgorzelec Esport | W   | 0.575      | -            | -                | -                | -         |     3.19 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           30 |     5626 | 2024-02-25 | Team Sampi                | W   | 0.568      | 0.333        | 0.039 (0.007)    | -                | -         |     5.72 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           29 |     5719 | 2024-02-24 | Permitta Esports          | L   | 0.562      | -            | -                | -                | -         |   -11.82 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           28 |     5829 | 2024-02-22 | BIG Academy               | W   | 0.549      | -            | -                | -                | -         |     2.52 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           27 |     5906 | 2024-02-21 | Permitta Esports          | W   | 0.542      | -            | -                | -                | -         |     6.01 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           26 |     5955 | 2024-02-20 | Natus Vincere Junior      | W   | 0.536      | -            | -                | -                | -         |     2.96 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           25 |     5965 | 2024-02-20 | Lilmix                    | W   | 0.535      | -            | -                | -                | -         |     3.35 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           24 |     6020 | 2024-02-19 | Permitta Esports          | L   | 0.529      | -            | -                | -                | -         |   -11.19 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           23 |     6117 | 2024-02-17 | Natus Vincere Junior      | W   | 0.517      | -            | -                | -                | -         |     2.65 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           22 |     6242 | 2024-02-15 | MOUZ NXT                  | L   | 0.502      | -            | -                | -                | -         |    -7.79 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           21 |     6300 | 2024-02-14 | ex-K10                    | W   | 0.496      | -            | -                | -                | -         |     2.70 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           20 |     6437 | 2024-02-11 | Lilmix                    | W   | 0.475      | -            | -                | -                | -         |     2.91 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           19 |     6444 | 2024-02-10 | Verdant                   | W   | 0.471      | -            | -                | -                | -         |     5.70 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           18 |     6447 | 2024-02-10 | 0to100                    | W   | 0.471      | -            | -                | -                | -         |     0.33 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           17 |     6451 | 2024-02-10 | Virtuoso Squad            | W   | 0.471      | -            | -                | -                | -         |     0.49 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           16 |     6502 | 2024-02-09 | brazylijski luz           | W   | 0.462      | -            | -                | -                | -         |     2.66 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           15 |     6645 | 2024-02-05 | WOPA Esport               | W   | 0.435      | -            | -                | -                | -         |     2.39 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           14 |     6800 | 2024-02-02 | 9Pandas                   | L   | 0.417      | -            | -                | -                | -         |    -4.65 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           13 |     6813 | 2024-02-02 | ex-sYnck                  | W   | 0.417      | -            | -                | -                | -         |     1.86 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           12 |     6826 | 2024-02-02 | UNiTY esports             | W   | 0.417      | -            | -                | -                | -         |     3.59 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           11 |     6973 | 2024-01-30 | Sprout                    | L   | 0.397      | -            | -                | -                | -         |   -11.50 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           10 |     7009 | 2024-01-29 | Metizport                 | W   | 0.392      | -            | -                | -                | -         |     4.17 | Blytz, Dytor, forsyy, kreaz, nbqq |
|            9 |     7040 | 2024-01-29 | Ninjas in Pyjamas         | W   | 0.392      | -            | -                | -                | -         |     1.74 | Blytz, Dytor, forsyy, kreaz, nbqq |
|            8 |     7937 | 2024-01-16 | Zero Tenacity             | L   | 0.302      | -            | -                | -                | -         |    -5.08 | Blytz, Dytor, forsyy, kreaz, nbqq |
|            7 |     8009 | 2024-01-14 | Permitta Esports          | L   | 0.289      | -            | -                | -                | -         |    -6.17 | Blytz, Dytor, forsyy, kreaz, nbqq |
|            6 |     8087 | 2024-01-12 | Team Walkover             | L   | 0.278      | -            | -                | -                | -         |    -8.45 | Blytz, Dytor, forsyy, kreaz, nbqq |
|            5 |     8336 | 2024-01-09 | Sashi Esport              | L   | 0.257      | -            | -                | -                | -         |    -4.46 | Blytz, Dytor, forsyy, kreaz, nbqq |
|            4 |     8352 | 2024-01-09 | Rhyno Esports             | W   | 0.257      | -            | -                | -                | -         |     3.24 | Blytz, Dytor, forsyy, kreaz, nbqq |
|            3 |     8368 | 2024-01-09 | Team LRP Poland           | W   | 0.257      | -            | -                | -                | -         |     0.87 | Blytz, Dytor, forsyy, kreaz, nbqq |
|            2 |     8437 | 2024-01-08 | Aurora Young Blud         | W   | 0.249      | -            | -                | -                | -         |     1.19 | Blytz, Dytor, forsyy, kreaz, nbqq |
|            1 |     8492 | 2024-01-04 | SINNERS Academy           | W   | 0.222      | -            | -                | -                | -         |     0.54 | Blytz, Dytor, forsyy, kreaz, nbqq |

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
