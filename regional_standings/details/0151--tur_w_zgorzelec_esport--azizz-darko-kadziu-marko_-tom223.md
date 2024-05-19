### Roster Details<br />
Team Name: Turów Zgorzelec Esport<br />
Roster: azizz, darko, kadziu, Markoś, ToM223<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [151](../standings_global.md)<br />
Regional Rank: [103]( ../standings_europe.md)<br />
Final Rank Value:  774.2<br />
<br />
Final Rank Value (774.2) = Starting Rank Value (830.0) + Head To Head Adjustments (-55.8)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.366[<sup>1</sup>](#table2)
- Bounty Collected: 0.339[<sup>2</sup>](#table1)
- Opponent Network: 0.161[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.217<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 830.0
- 400 + ( ( 0.217 - 0.000 ) / ( 0.806 - 0.000 ) ) * 1600 = 830.0


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
|           70 |       87 | 2024-05-04 | Astralis Talent             | W   | 1.000      | 0.333        | 0.030 (0.010)    | 0.613 (0.204)    | false (0.000) |    19.18 | azizz, darko, kadziu, Markoś, ToM223      |
|           69 |      292 | 2024-04-29 | UNiTY esports (Slovak team) | L   | 1.000      | -            | -                | -                | -             |    -9.86 | azizz, darko, kadziu, Markoś, ToM223      |
|           68 |      476 | 2024-04-25 | JANO Esports                | L   | 1.000      | -            | -                | -                | -             |   -16.97 | azizz, darko, kadziu, keis, Markoś        |
|           67 |      485 | 2024-04-25 | GenOne                      | W   | 1.000      | 0.371        | -                | 0.323 (0.120)    | false (0.000) |     9.06 | azizz, darko, kadziu, keis, Markoś        |
|           66 |      494 | 2024-04-25 | Verdant                     | L   | 1.000      | -            | -                | -                | -             |   -11.02 | azizz, darko, kadziu, Markoś, Sobol       |
|           65 |      523 | 2024-04-24 | Los kogutos                 | W   | 1.000      | -            | -                | -                | false (0.000) |     7.43 | azizz, darko, kadziu, keis, Markoś        |
|           64 |      533 | 2024-04-24 | ThunderFlash                | W   | 1.000      | 0.371        | 0.023 (0.009)    | 0.274 (0.102)    | false (0.000) |    18.18 | azizz, darko, kadziu, keis, Markoś        |
|           63 |     1056 | 2024-04-15 | Team Secret                 | L   | 1.000      | -            | -                | -                | -             |   -18.81 | azizz, darko, kadziu, Markoś, Sobol       |
|           62 |     1190 | 2024-04-11 | Team Sampi                  | L   | 1.000      | -            | -                | -                | -             |    -5.97 | azizz, darko, kadziu, Markoś, Sobol       |
|           61 |     1375 | 2024-04-07 | Viperio                     | L   | 1.000      | -            | -                | -                | -             |   -18.50 | azizz, darko, EXUS, kadziu, Markoś        |
|           60 |     1454 | 2024-04-05 | SAW                         | L   | 0.996      | -            | -                | -                | -             |    -0.74 | azizz, darko, EXUS, kadziu, Markoś        |
|           59 |     1508 | 2024-04-04 | Dynamo Eclot                | L   | 0.989      | -            | -                | -                | -             |    -6.29 | darko, EXUS, kadziu, Markoś, Sobol        |
|           58 |     1542 | 2024-04-03 | Illuminar Gaming            | W   | 0.984      | 0.333        | 0.008 (0.003)    | 0.433 (0.142)    | false (0.000) |    17.67 | darko, EXUS, kadziu, Markoś, Sobol        |
|           57 |     1562 | 2024-04-03 | Lilmix                      | L   | 0.982      | -            | -                | -                | -             |   -22.71 | azizz, darko, EXUS, kadziu, Markoś        |
|           56 |     1611 | 2024-04-01 | ROSOMAHA                    | W   | 0.969      | -            | -                | -                | false (0.000) |     6.83 | darko, EXUS, kadziu, Markoś, Sobol        |
|           55 |     1647 | 2024-03-30 | Sashi Esport                | L   | 0.957      | -            | -                | -                | -             |    -6.13 | darko, EXUS, kadziu, Markoś, Sobol        |
|           54 |     1849 | 2024-03-25 | Lilmix                      | W   | 0.923      | 0.333        | -                | 0.604 (0.186)    | false (0.000) |     7.22 | darko, EXUS, kadziu, Markoś, Sobol        |
|           53 |     1930 | 2024-03-22 | Mikstura1234                | W   | 0.906      | -            | -                | -                | false (0.000) |     8.65 | AxEcHo, darko, kadziu, Markoś, xKacpersky |
|           52 |     1981 | 2024-03-21 | LODIS                       | W   | 0.899      | -            | -                | -                | false (0.000) |     7.01 | AxEcHo, darko, kadziu, Markoś, xKacpersky |
|           51 |     1999 | 2024-03-21 | UNiTY esports (Slovak team) | W   | 0.896      | 0.333        | 0.055 (0.017)    | 0.727 (0.217)    | false (0.000) |    16.80 | darko, EXUS, kadziu, Markoś, Sobol        |
|           50 |     2027 | 2024-03-20 | ENTERPRISE esports          | L   | 0.891      | -            | -                | -                | -             |    -8.45 | AxEcHo, darko, kadziu, Markoś, xKacpersky |
|           49 |     2031 | 2024-03-20 | Dynamo Eclot                | L   | 0.891      | -            | -                | -                | -             |    -4.38 | AxEcHo, darko, kadziu, Markoś, xKacpersky |
|           48 |     2046 | 2024-03-19 | ThunderFlash                | L   | 0.886      | -            | -                | -                | -             |   -14.83 | AxEcHo, darko, kadziu, Markoś, xKacpersky |
|           47 |     2061 | 2024-03-19 | WOPA Esport                 | L   | 0.885      | -            | -                | -                | -             |   -15.51 | AxEcHo, darko, kadziu, Markoś, xKacpersky |
|           46 |     2076 | 2024-03-18 | Illuminar Gaming            | L   | 0.879      | -            | -                | -                | -             |   -15.28 | AxEcHo, darko, kadziu, Markoś, xKacpersky |
|           45 |     2088 | 2024-03-18 | ARROW (German team)         | W   | 0.878      | 0.333        | 0.009 (0.003)    | -                | -             |     9.39 | AxEcHo, darko, kadziu, Markoś, xKacpersky |
|           44 |     2122 | 2024-03-17 | Viperio                     | W   | 0.872      | -            | -                | -                | -             |     8.86 | AxEcHo, darko, kadziu, Markoś, xKacpersky |
|           43 |     2207 | 2024-03-15 | TopTab Club                 | W   | 0.859      | -            | -                | -                | -             |     4.62 | AxEcHo, darko, kadziu, Markoś, xKacpersky |
|           42 |     2319 | 2024-03-13 | MST                         | W   | 0.845      | -            | -                | -                | -             |     2.77 | AxEcHo, darko, kadziu, Markoś, xKacpersky |
|           41 |     2657 | 2024-03-06 | Natus Vincere Junior        | L   | 0.796      | -            | -                | -                | -             |   -11.31 | AxEcHo, darko, kadziu, Markoś, Sobol      |
|           40 |     2748 | 2024-03-04 | ENTERPRISE esports          | L   | 0.786      | -            | -                | -                | -             |    -8.09 | AxEcHo, darko, kadziu, Markoś, xKacpersky |
|           39 |     2775 | 2024-03-04 | MOUZ NXT                    | L   | 0.783      | -            | -                | -                | -             |    -4.78 | AxEcHo, darko, kadziu, Markoś, Sobol      |
|           38 |     2852 | 2024-03-02 | GODSENT                     | L   | 0.772      | -            | -                | -                | -             |   -13.31 | AxEcHo, darko, kadziu, Markoś, xKacpersky |
|           37 |     3048 | 2024-02-27 | Astralis Talent             | W   | 0.743      | 0.303        | 0.030 (0.007)    | 0.613 (0.138)    | -             |    14.90 | AxEcHo, darko, kadziu, Markoś, Sobol      |
|           36 |     3063 | 2024-02-26 | DMS                         | L   | 0.739      | -            | -                | -                | -             |   -16.87 | AxEcHo, darko, kadziu, Markoś, xKacpersky |
|           35 |     3081 | 2024-02-26 | Dynamo Eclot                | L   | 0.736      | -            | -                | -                | -             |    -3.83 | AxEcHo, darko, kadziu, Markoś, xKacpersky |
|           34 |     3110 | 2024-02-25 | Sashi Esport                | W   | 0.730      | 0.333        | 0.193 (0.047)    | 1.000 (0.243)    | -             |    18.50 | AxEcHo, darko, kadziu, Markoś, xKacpersky |
|           33 |     3221 | 2024-02-23 | Johnny Speeds               | W   | 0.717      | 0.303        | 0.044 (0.010)    | 0.718 (0.156)    | -             |    12.21 | AxEcHo, darko, kadziu, Markoś, Sobol      |
|           32 |     3268 | 2024-02-22 | Permitta Esports            | L   | 0.709      | -            | -                | -                | -             |    -5.76 | AxEcHo, darko, kadziu, Markoś, xKacpersky |
|           31 |     3503 | 2024-02-17 | Entropiq                    | W   | 0.677      | -            | -                | -                | -             |     9.71 | AxEcHo, darko, kadziu, Markoś, xKacpersky |
|           30 |     3690 | 2024-02-13 | Natus Vincere Junior        | W   | 0.650      | 0.333        | 0.025 (0.005)    | 0.492 (0.107)    | -             |    11.01 | AxEcHo, darko, kadziu, Markoś, xKacpersky |
|           29 |     4193 | 2024-01-29 | Preasy Esport               | L   | 0.552      | -            | -                | -                | -             |    -4.59 | byali, darko, kadziu, Markoś, xKacpersky  |
|           28 |     4712 | 2024-01-17 | AMKAL ESPORTS               | L   | 0.472      | -            | -                | -                | -             |    -1.37 | byali, darko, kadziu, Markoś, xKacpersky  |
|           27 |     4741 | 2024-01-17 | ILIN                        | W   | 0.472      | -            | -                | -                | -             |     3.19 | byali, darko, kadziu, Markoś, xKacpersky  |
|           26 |     4797 | 2024-01-16 | 00 Nation                   | L   | 0.466      | -            | -                | -                | -             |   -12.42 | byali, darko, discoStar, kadziu, Markoś   |
|           25 |     4815 | 2024-01-16 | Virtuoso Squad              | W   | 0.465      | -            | -                | -                | -             |     1.27 | byali, darko, discoStar, kadziu, Markoś   |
|           24 |     4941 | 2024-01-12 | GODSENT                     | W   | 0.439      | -            | -                | -                | -             |     6.63 | byali, darko, discoStar, kadziu, Markoś   |
|           23 |     5093 | 2024-01-09 | Fnatic                      | L   | 0.418      | -            | -                | -                | -             |    -1.35 | darko, discoStar, gRuChA, kadziu, Markoś  |
|           22 |     5104 | 2024-01-09 | Verdant                     | W   | 0.418      | -            | -                | -                | -             |     1.19 | darko, discoStar, gRuChA, kadziu, Markoś  |
|           21 |     5129 | 2024-01-09 | Natus Vincere Junior        | L   | 0.416      | -            | -                | -                | -             |    -6.26 | darko, discoStar, gRuChA, kadziu, Markoś  |
|           20 |     5191 | 2024-01-05 | Zero Tenacity               | L   | 0.389      | -            | -                | -                | -             |    -4.05 | darko, discoStar, gRuChA, kadziu, Markoś  |
|           19 |     5382 | 2023-12-17 | Sashi Esport                | L   | 0.263      | -            | -                | -                | -             |    -1.55 | b1elany, darko, gRuChA, kadziu, Markoś    |
|           18 |     5701 | 2023-12-11 | Team Spirit Academy         | L   | 0.224      | -            | -                | -                | -             |    -3.78 | b1elany, darko, gRuChA, kadziu, Markoś    |
|           17 |     5890 | 2023-12-07 | UNiTY esports (Slovak team) | W   | 0.198      | 0.333        | 0.055 (0.004)    | -                | -             |     4.38 | b1elany, darko, gRuChA, kadziu, Markoś    |
|           16 |     6092 | 2023-12-02 | ENTERPRISE esports          | L   | 0.166      | -            | -                | -                | -             |    -1.70 | b1elany, darko, gRuChA, kadziu, Markoś    |
|           15 |     6241 | 2023-11-29 | XGOD                        | W   | 0.146      | -            | -                | -                | -             |     0.65 | b1elany, darko, gRuChA, kadziu, Markoś    |
|           14 |     6255 | 2023-11-29 | Soda Gaming                 | L   | 0.145      | -            | -                | -                | -             |    -2.67 | b1elany, darko, gRuChA, kadziu, Markoś    |
|           13 |     6315 | 2023-11-28 | Lajtbitexe                  | W   | 0.138      | -            | -                | -                | -             |     0.79 | b1elany, darko, gRuChA, kadziu, Markoś    |
|           12 |     6321 | 2023-11-28 | Kappa Bar                   | L   | 0.138      | -            | -                | -                | -             |    -3.04 | b1elany, darko, gRuChA, kadziu, Markoś    |
|           11 |     6512 | 2023-11-23 | Rebels Gaming               | L   | 0.105      | -            | -                | -                | -             |    -0.41 | b1elany, darko, gRuChA, kadziu, Markoś    |
|           10 |     6542 | 2023-11-22 | ENCE                        | L   | 0.099      | -            | -                | -                | -             |    -0.05 | b1elany, darko, gRuChA, kadziu, Markoś    |
|            9 |     6554 | 2023-11-22 | Bleiz                       | W   | 0.099      | -            | -                | -                | -             |     0.36 | b1elany, darko, gRuChA, kadziu, Markoś    |
|            8 |     6614 | 2023-11-20 | TUSTE CHOPAKI               | W   | 0.086      | -            | -                | -                | -             |     0.35 | b1elany, darko, gRuChA, kadziu, Markoś    |
|            7 |     6723 | 2023-11-18 | Illuminar Gaming            | W   | 0.071      | -            | -                | -                | -             |     0.91 | b1elany, darko, gRuChA, kadziu, Markoś    |
|            6 |     6778 | 2023-11-17 | The Witchers                | L   | 0.064      | -            | -                | -                | -             |    -1.15 | b1elany, darko, gRuChA, kadziu, Markoś    |
|            5 |     6888 | 2023-11-15 | Ex-Anonymo Esports          | W   | 0.051      | -            | -                | -                | -             |     0.68 | b1elany, darko, gRuChA, kadziu, Markoś    |
|            4 |     6928 | 2023-11-14 | Ex-Hot Headed Gaming        | L   | 0.045      | -            | -                | -                | -             |    -1.20 | b1elany, darko, gRuChA, kadziu, Markoś    |
|            3 |     6931 | 2023-11-14 | L&G                         | L   | 0.044      | -            | -                | -                | -             |    -1.17 | b1elany, darko, gRuChA, kadziu, Markoś    |
|            2 |     7166 | 2023-11-08 | Underrated                  | W   | 0.006      | -            | -                | -                | -             |     0.02 | b1elany, darko, gRuChA, kadziu, Markoś    |
|            1 |     7178 | 2023-11-08 | HOTU                        | L   | 0.005      | -            | -                | -                | -             |    -0.09 | b1elany, darko, gRuChA, kadziu, Markoś    |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($2,956.20)
- Divide that value by the 5th highest value among all rosters ($158,437.64)
- The final value (0.02) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-04-21 |      1.000 | $492.92        | $492.92         |
| 2024-04-06 |      1.000 | $500.00        | $500.00         |
| 2024-03-23 |      0.912 | $600.00        | $547.39         |
| 2024-02-28 |      0.749 | $500.00        | $374.70         |
| 2023-12-02 |      0.166 | $6,290.86      | $1,041.20       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
