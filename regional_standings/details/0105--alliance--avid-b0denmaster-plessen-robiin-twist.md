### Roster Details<br />
Team Name: Alliance<br />
Roster: avid, b0denmaster, PlesseN, robiin, twist<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [105](../standings_global.md)<br />
Regional Rank: [77]( ../standings_europe.md)<br />
Final Rank Value:  851.2<br />
<br />
Final Rank Value (851.2) = Starting Rank Value (886.0) + Head To Head Adjustments (-34.7)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.361[<sup>1</sup>](#table2)
- Bounty Collected: 0.351[<sup>2</sup>](#table1)
- Opponent Network: 0.194[<sup>2</sup>](#table1)
- LAN Wins: 0.074[<sup>2</sup>](#table1)

The average of these factors is 0.245<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 886.0
- 400 + ( ( 0.245 - 0.000 ) / ( 0.806 - 0.000 ) ) * 1600 = 886.0


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent                    | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins      | H2H Adj. | Roster                                    |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           73 |      248 | 2024-04-30 | B8                          | L   | 1.000      | -            | -                | -                | -             |   -10.25 | avid, b0denmaster, PlesseN, robiin, twist |
|           72 |      291 | 2024-04-29 | Endpoint                    | W   | 1.000      | 0.384        | -                | 0.785 (0.302)    | false (0.000) |    17.59 | avid, b0denmaster, PlesseN, robiin, twist |
|           71 |      320 | 2024-04-28 | DMS                         | W   | 1.000      | 0.500        | -                | 0.504 (0.252)    | false (0.000) |    14.03 | avid, b0denmaster, PlesseN, robiin, twist |
|           70 |      513 | 2024-04-24 | BRANDMAN                    | L   | 1.000      | -            | -                | -                | -             |   -26.97 | avid, b0denmaster, PlesseN, robiin, twist |
|           69 |      584 | 2024-04-23 | Metizport                   | L   | 1.000      | -            | -                | -                | -             |    -6.17 | avid, b0denmaster, PlesseN, robiin, twist |
|           68 |      666 | 2024-04-21 | Sangal Esports              | L   | 1.000      | -            | -                | -                | -             |   -18.02 | avid, b0denmaster, PlesseN, robiin, twist |
|           67 |      852 | 2024-04-19 | 9Pandas                     | W   | 1.000      | 0.500        | 0.085 (0.043)    | 0.661 (0.330)    | false (0.000) |    23.37 | avid, b0denmaster, PlesseN, robiin, twist |
|           66 |      945 | 2024-04-17 | Nemiga Gaming               | L   | 1.000      | -            | -                | -                | -             |    -3.46 | avid, b0denmaster, PlesseN, robiin, twist |
|           65 |      963 | 2024-04-17 | Dynamo Eclot                | L   | 1.000      | -            | -                | -                | -             |   -10.19 | avid, b0denmaster, PlesseN, robiin, twist |
|           64 |     1054 | 2024-04-15 | HAVU Gaming                 | W   | 1.000      | 0.384        | 0.024 (0.009)    | 0.213 (0.082)    | false (0.000) |    12.46 | avid, b0denmaster, PlesseN, robiin, twist |
|           63 |     1058 | 2024-04-15 | MOUZ NXT                    | L   | 1.000      | -            | -                | -                | -             |    -8.13 | avid, b0denmaster, PlesseN, robiin, twist |
|           62 |     1121 | 2024-04-13 | ALTERNATE aTTaX             | L   | 1.000      | -            | -                | -                | -             |   -12.54 | avid, b0denmaster, PlesseN, robiin, twist |
|           61 |     1185 | 2024-04-11 | Zero Tenacity               | W   | 1.000      | 0.384        | 0.095 (0.036)    | 1.000 (0.384)    | false (0.000) |    17.70 | avid, b0denmaster, PlesseN, robiin, twist |
|           60 |     1289 | 2024-04-09 | BLEED Esports               | L   | 1.000      | -            | -                | -                | -             |    -7.28 | avid, b0denmaster, PlesseN, robiin, twist |
|           59 |     1313 | 2024-04-09 | Astralis Talent             | W   | 1.000      | 0.371        | 0.030 (0.011)    | 0.613 (0.227)    | false (0.000) |    16.79 | avid, b0denmaster, PlesseN, robiin, twist |
|           58 |     1365 | 2024-04-07 | Johnny Speeds               | L   | 1.000      | -            | -                | -                | -             |   -14.66 | avid, b0denmaster, PlesseN, robiin, twist |
|           57 |     1371 | 2024-04-07 | EYEBALLERS                  | L   | 1.000      | -            | -                | -                | -             |   -12.62 | avid, b0denmaster, PlesseN, robiin, twist |
|           56 |     1389 | 2024-04-06 | Lilmix                      | W   | 1.000      | 0.143        | -                | 0.604 (0.086)    | -             |     7.69 | avid, b0denmaster, PlesseN, robiin, twist |
|           55 |     1406 | 2024-04-06 | BetBoom Team                | L   | 1.000      | -            | -                | -                | -             |    -1.60 | avid, b0denmaster, PlesseN, robiin, twist |
|           54 |     1446 | 2024-04-05 | BLEED Esports               | L   | 0.997      | -            | -                | -                | -             |    -7.93 | avid, b0denmaster, PlesseN, robiin, twist |
|           53 |     1479 | 2024-04-04 | BetBoom Team                | L   | 0.992      | -            | -                | -                | -             |    -1.73 | avid, b0denmaster, PlesseN, robiin, twist |
|           52 |     1493 | 2024-04-04 | BenchedHeroes               | W   | 0.991      | -            | -                | -                | -             |     1.96 | avid, b0denmaster, PlesseN, robiin, twist |
|           51 |     1550 | 2024-04-03 | AMKAL ESPORTS               | L   | 0.983      | -            | -                | -                | -             |    -6.28 | avid, b0denmaster, PlesseN, robiin, twist |
|           50 |     2258 | 2024-03-14 | E-Town Gaming               | W   | 0.852      | -            | -                | -                | -             |     1.65 | avid, b0denmaster, PlesseN, robiin, twist |
|           49 |     2336 | 2024-03-13 | MOUZ NXT                    | L   | 0.843      | -            | -                | -                | -             |    -7.09 | avid, b0denmaster, PlesseN, robiin, twist |
|           48 |     2386 | 2024-03-12 | Passion UA                  | L   | 0.837      | -            | -                | -                | -             |   -11.70 | avid, b0denmaster, PlesseN, robiin, twist |
|           47 |     2465 | 2024-03-10 | EYEBALLERS                  | W   | 0.824      | 0.143        | 0.051 (0.006)    | -                | -             |    15.07 | avid, b0denmaster, PlesseN, robiin, twist |
|           46 |     2491 | 2024-03-09 | Kappa Borr                  | W   | 0.818      | -            | -                | -                | -             |     3.27 | avid, b0denmaster, PlesseN, robiin, twist |
|           45 |     2507 | 2024-03-09 | Johnny Speeds               | W   | 0.817      | 0.143        | 0.044 (0.005)    | 0.718 (0.084)    | -             |    12.68 | avid, b0denmaster, PlesseN, robiin, twist |
|           44 |     2509 | 2024-03-09 | Kappa Bar                   | W   | 0.817      | -            | -                | -                | -             |     3.03 | avid, b0denmaster, PlesseN, robiin, twist |
|           43 |     2519 | 2024-03-09 | Entropiq                    | W   | 0.817      | -            | -                | -                | -             |    10.41 | avid, b0denmaster, PlesseN, robiin, twist |
|           42 |     2584 | 2024-03-07 | Sprout                      | W   | 0.803      | -            | -                | -                | -             |     3.27 | avid, b0denmaster, PlesseN, robiin, twist |
|           41 |     2715 | 2024-03-05 | Viperio                     | W   | 0.789      | 0.371        | -                | 0.321 (0.094)    | -             |     6.55 | avid, b0denmaster, PlesseN, robiin, twist |
|           40 |     2749 | 2024-03-04 | B8                          | L   | 0.786      | -            | -                | -                | -             |    -9.15 | avid, b0denmaster, PlesseN, robiin, twist |
|           39 |     2925 | 2024-03-01 | 9INE                        | L   | 0.763      | -            | -                | -                | -             |   -19.53 | avid, b0denmaster, PlesseN, robiin, twist |
|           38 |     3004 | 2024-02-28 | Sangal Esports              | W   | 0.750      | 0.384        | -                | 0.350 (0.101)    | -             |     7.38 | avid, b0denmaster, PlesseN, robiin, twist |
|           37 |     3101 | 2024-02-25 | ALTERNATE aTTaX             | W   | 0.731      | 0.143        | 0.110 (0.011)    | -                | -             |    15.12 | avid, b0denmaster, PlesseN, robiin, twist |
|           36 |     3461 | 2024-02-18 | EsmagaB                     | W   | 0.684      | -            | -                | -                | -             |    10.31 | avid, b0denmaster, PlesseN, robiin, twist |
|           35 |     3870 | 2024-02-06 | 9INE                        | W   | 0.603      | -            | -                | -                | -             |     4.31 | avid, b0denmaster, PlesseN, robiin, twist |
|           34 |     3924 | 2024-02-04 | Team Secret                 | L   | 0.591      | -            | -                | -                | -             |   -13.62 | avid, b0denmaster, PlesseN, robiin, twist |
|           33 |     3962 | 2024-02-03 | Maknitude                   | W   | 0.585      | -            | -                | -                | -             |     2.53 | avid, b0denmaster, PlesseN, robiin, twist |
|           32 |     4019 | 2024-02-02 | Metizport                   | L   | 0.578      | -            | -                | -                | -             |    -5.52 | avid, b0denmaster, PlesseN, robiin, twist |
|           31 |     4198 | 2024-01-29 | Passion UA                  | L   | 0.551      | -            | -                | -                | -             |    -5.82 | avid, b0denmaster, PlesseN, robiin, twist |
|           30 |     4231 | 2024-01-28 | Team Spirit Academy         | L   | 0.543      | -            | -                | -                | -             |   -10.10 | avid, b0denmaster, PlesseN, robiin, twist |
|           29 |     4405 | 2024-01-24 | Gaimin Gladiators           | L   | 0.516      | -            | -                | -                | -             |    -0.85 | avid, b0denmaster, PlesseN, robiin, twist |
|           28 |     4716 | 2024-01-17 | UNiTY esports (Slovak team) | L   | 0.472      | -            | -                | -                | -             |    -5.54 | avid, b0denmaster, PlesseN, robiin, twist |
|           27 |     4796 | 2024-01-16 | Nexus Gaming                | L   | 0.466      | -            | -                | -                | -             |    -6.76 | avid, b0denmaster, PlesseN, robiin, twist |
|           26 |     4798 | 2024-01-16 | XGOD                        | W   | 0.465      | -            | -                | -                | -             |     1.50 | avid, b0denmaster, PlesseN, robiin, twist |
|           25 |     5009 | 2024-01-11 | Lazer Cats                  | W   | 0.430      | -            | -                | -                | -             |     1.46 | avid, b0denmaster, PlesseN, robiin, twist |
|           24 |     5247 | 2023-12-30 | The Witchers                | L   | 0.350      | -            | -                | -                | -             |    -7.01 | avid, b0denmaster, PlesseN, robiin, twist |
|           23 |     5251 | 2023-12-29 | Illuminar Gaming            | W   | 0.343      | -            | -                | -                | -             |     3.84 | avid, b0denmaster, PlesseN, robiin, twist |
|           22 |     5255 | 2023-12-28 | Rhyno Esports               | W   | 0.337      | 0.371        | 0.047 (0.006)    | -                | -             |     6.04 | avid, b0denmaster, PlesseN, robiin, twist |
|           21 |     5263 | 2023-12-26 | VP.Prodigy                  | L   | 0.324      | -            | -                | -                | -             |    -5.59 | avid, b0denmaster, PlesseN, robiin, twist |
|           20 |     5365 | 2023-12-17 | Lilmix                      | W   | 0.264      | -            | -                | -                | true (0.264)  |     2.17 | avid, b0denmaster, PlesseN, robiin, twist |
|           19 |     5700 | 2023-12-11 | Sprout                      | L   | 0.225      | -            | -                | -                | -             |    -5.29 | avid, b0denmaster, PlesseN, robiin, twist |
|           18 |     5784 | 2023-12-09 | Kappa Bar                   | W   | 0.210      | -            | -                | -                | true (0.210)  |     1.07 | avid, b0denmaster, PlesseN, robiin, twist |
|           17 |     5944 | 2023-12-06 | Sprout                      | W   | 0.190      | -            | -                | -                | -             |     1.49 | avid, b0denmaster, PlesseN, robiin, twist |
|           16 |     6118 | 2023-12-02 | EYEBALLERS                  | L   | 0.164      | -            | -                | -                | -             |    -2.22 | avid, b0denmaster, PlesseN, robiin, twist |
|           15 |     6156 | 2023-12-01 | Kappa Bar                   | W   | 0.159      | -            | -                | -                | true (0.159)  |     1.17 | avid, b0denmaster, PlesseN, robiin, twist |
|           14 |     6271 | 2023-11-29 | Sashi Esport                | W   | 0.144      | 0.384        | 0.193 (0.011)    | -                | -             |     3.44 | avid, b0denmaster, PlesseN, robiin, twist |
|           13 |     6591 | 2023-11-21 | Lemondogs                   | W   | 0.092      | -            | -                | -                | -             |     0.27 | avid, b0denmaster, PlesseN, robiin, twist |
|           12 |     6646 | 2023-11-20 | IKLA                        | W   | 0.084      | -            | -                | -                | -             |     0.67 | avid, b0denmaster, PlesseN, robiin, twist |
|           11 |     6715 | 2023-11-18 | ARCRED                      | L   | 0.072      | -            | -                | -                | -             |    -1.31 | avid, b0denmaster, PlesseN, robiin, twist |
|           10 |     6729 | 2023-11-18 | Begrip Gaming               | W   | 0.071      | -            | -                | -                | -             |     0.45 | avid, b0denmaster, PlesseN, robiin, twist |
|            9 |     6791 | 2023-11-17 | GODSENT                     | L   | 0.063      | -            | -                | -                | -             |    -1.23 | avid, b0denmaster, PlesseN, robiin, twist |
|            8 |     6842 | 2023-11-16 | Sashi Esport                | W   | 0.057      | 0.384        | 0.193 (0.004)    | -                | -             |     1.36 | avid, b0denmaster, PlesseN, robiin, twist |
|            7 |     6881 | 2023-11-15 | Pungrottorna                | W   | 0.052      | -            | -                | -                | -             |     0.16 | avid, b0denmaster, PlesseN, robiin, twist |
|            6 |     6936 | 2023-11-14 | 9Pandas                     | L   | 0.044      | -            | -                | -                | -             |    -0.28 | avid, b0denmaster, PlesseN, robiin, twist |
|            5 |     7040 | 2023-11-11 | Lilmix                      | W   | 0.027      | -            | -                | -                | true (0.027)  |     0.23 | avid, b0denmaster, PlesseN, robiin, twist |
|            4 |     7070 | 2023-11-11 | Soda Gaming                 | L   | 0.024      | -            | -                | -                | -             |    -0.51 | avid, b0denmaster, PlesseN, robiin, twist |
|            3 |     7134 | 2023-11-09 | Young Gods                  | L   | 0.012      | -            | -                | -                | -             |    -0.33 | avid, b0denmaster, PlesseN, robiin, twist |
|            2 |     7175 | 2023-11-08 | E-Town Gaming               | W   | 0.005      | -            | -                | -                | -             |     0.01 | avid, b0denmaster, PlesseN, robiin, twist |
|            1 |     7202 | 2023-11-08 | Ex-Anonymo Esports          | W   | 0.004      | -            | -                | -                | -             |     0.05 | avid, b0denmaster, PlesseN, robiin, twist |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($2,681.26)
- Divide that value by the 5th highest value among all rosters ($158,437.64)
- The final value (0.02) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2023-12-17 |      0.265 | $5,888.04      | $1,562.51       |
| 2023-12-13 |      0.239 | $500.00        | $119.29         |
| 2023-12-09 |      0.210 | $2,388.48      | $500.86         |
| 2023-12-03 |      0.172 | $2,396.52      | $412.29         |
| 2023-11-11 |      0.027 | $3,211.39      | $86.31          |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
