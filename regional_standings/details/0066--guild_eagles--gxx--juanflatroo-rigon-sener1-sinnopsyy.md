### Roster Details<br />
Team Name: Guild Eagles<br />
Roster: gxx-, juanflatroo, rigoN, SENER1, sinnopsyy<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [66](../standings_global.md)<br />
Regional Rank: [49]( ../standings_europe.md)<br />
Final Rank Value:  940.2<br />
<br />
Final Rank Value (940.2) = Starting Rank Value (1028.0) + Head To Head Adjustments (-87.8)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.411[<sup>1</sup>](#table2)
- Bounty Collected: 0.422[<sup>2</sup>](#table1)
- Opponent Network: 0.197[<sup>2</sup>](#table1)
- LAN Wins: 0.236[<sup>2</sup>](#table1)

The average of these factors is 0.317<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1028.0
- 400 + ( ( 0.317 - 0.000 ) / ( 0.806 - 0.000 ) ) * 1600 = 1028.0


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent                | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins      | H2H Adj. | Roster                                      |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           68 |       28 | 2024-05-05 | 1win                    | L   | 1.000      | -            | -                | -                | -             |   -19.60 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|           67 |      276 | 2024-04-29 | EYEBALLERS              | L   | 1.000      | -            | -                | -                | -             |   -16.66 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|           66 |      361 | 2024-04-27 | Insilio                 | L   | 1.000      | -            | -                | -                | -             |   -16.39 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|           65 |      420 | 2024-04-26 | BLEED Esports           | L   | 1.000      | -            | -                | -                | -             |    -8.31 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|           64 |      486 | 2024-04-25 | PARIVISION              | L   | 1.000      | -            | -                | -                | -             |   -21.18 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|           63 |      549 | 2024-04-24 | Zero Tenacity           | W   | 1.000      | 0.435        | 0.095 (0.041)    | 1.000 (0.435)    | false (0.000) |    13.54 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|           62 |      611 | 2024-04-22 | 3DMAX                   | L   | 1.000      | -            | -                | -                | -             |   -18.12 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|           61 |      868 | 2024-04-18 | Sashi Esport            | L   | 1.000      | -            | -                | -                | -             |   -12.46 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|           60 |      871 | 2024-04-18 | KOI                     | W   | 1.000      | 0.143        | -                | 0.537 (0.077)    | false (0.000) |    19.05 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|           59 |      892 | 2024-04-18 | AMKAL ESPORTS           | L   | 1.000      | -            | -                | -                | -             |    -9.16 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|           58 |      922 | 2024-04-17 | Heimo Esports           | W   | 1.000      | -            | -                | -                | false (0.000) |     5.61 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|           57 |     1014 | 2024-04-16 | Sashi Esport            | W   | 1.000      | 0.384        | 0.193 (0.074)    | 1.000 (0.384)    | false (0.000) |    18.50 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|           56 |     1297 | 2024-04-09 | Metizport               | W   | 1.000      | 0.384        | 0.188 (0.072)    | 1.000 (0.384)    | false (0.000) |    21.33 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|           55 |     1537 | 2024-04-03 | AMKAL ESPORTS           | L   | 0.984      | -            | -                | -                | -             |    -9.42 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|           54 |     1571 | 2024-04-02 | Insilio                 | L   | 0.979      | -            | -                | -                | -             |   -16.02 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|           53 |     1580 | 2024-04-02 | AMKAL ESPORTS           | W   | 0.977      | 0.143        | 0.209 (0.029)    | 0.756 (0.106)    | false (0.000) |    20.82 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|           52 |     1591 | 2024-04-02 | 500                     | L   | 0.976      | -            | -                | -                | -             |   -18.44 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|           51 |     1599 | 2024-04-01 | 500                     | W   | 0.972      | 0.384        | -                | 0.660 (0.247)    | false (0.000) |    12.03 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|           50 |     1742 | 2024-03-27 | ALTERNATE aTTaX         | L   | 0.939      | -            | -                | -                | -             |   -16.82 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|           49 |     1754 | 2024-03-27 | MANGANES                | W   | 0.938      | -            | -                | -                | -             |     1.69 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|           48 |     1952 | 2024-03-22 | VP.Prodigy              | L   | 0.903      | -            | -                | -                | -             |   -19.97 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|           47 |     2750 | 2024-03-04 | GUN5 Esports            | L   | 0.786      | -            | -                | -                | -             |   -22.07 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|           46 |     2826 | 2024-03-02 | RUSH B (Russian team)   | L   | 0.773      | -            | -                | -                | -             |   -20.29 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|           45 |     2862 | 2024-03-02 | Astra Gaming            | W   | 0.772      | -            | -                | -                | -             |     0.55 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|           44 |     3020 | 2024-02-27 | Croatia (Croatian team) | L   | 0.745      | -            | -                | -                | -             |   -22.26 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|           43 |     3027 | 2024-02-27 | Metizport               | W   | 0.745      | 0.143        | 0.188 (0.020)    | 1.000 (0.106)    | -             |    11.29 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|           42 |     3059 | 2024-02-26 | Preasy Esport           | W   | 0.739      | -            | -                | -                | -             |     3.30 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|           41 |     3182 | 2024-02-24 | GamerLegion             | L   | 0.723      | -            | -                | -                | -             |    -1.37 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|           40 |     3220 | 2024-02-23 | BetBoom Team            | W   | 0.717      | 0.143        | 0.571 (0.059)    | 0.824 (0.084)    | true (0.717)  |    20.18 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|           39 |     3262 | 2024-02-22 | Gaimin Gladiators       | L   | 0.711      | -            | -                | -                | -             |    -3.49 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|           38 |     3304 | 2024-02-21 | Preasy Esport           | W   | 0.705      | 0.143        | 0.106 (0.011)    | -                | true (0.705)  |     9.40 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|           37 |     3364 | 2024-02-20 | Nexus Gaming            | W   | 0.697      | 0.143        | -                | 0.772 (0.077)    | true (0.697)  |     6.74 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|           36 |     3411 | 2024-02-19 | ENCE                    | L   | 0.691      | -            | -                | -                | -             |    -1.26 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|           35 |     3429 | 2024-02-19 | MOUZ                    | L   | 0.690      | -            | -                | -                | -             |    -0.23 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|           34 |     3812 | 2024-02-08 | Insilio                 | L   | 0.619      | -            | -                | -                | -             |   -11.81 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|           33 |     3827 | 2024-02-08 | RUBY                    | L   | 0.618      | -            | -                | -                | -             |   -13.80 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|           32 |     4350 | 2024-01-25 | Pera Esports            | L   | 0.526      | -            | -                | -                | -             |   -10.85 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|           31 |     4385 | 2024-01-24 | ALTERNATE aTTaX         | W   | 0.518      | -            | -                | -                | -             |     7.30 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|           30 |     4430 | 2024-01-23 | Team Sampi              | W   | 0.512      | -            | -                | -                | -             |     6.99 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|           29 |     4433 | 2024-01-23 | ALTERNATE aTTaX         | W   | 0.511      | -            | -                | -                | -             |     7.94 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|           28 |     4454 | 2024-01-22 | Pera Esports            | L   | 0.506      | -            | -                | -                | -             |   -10.91 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|           27 |     4467 | 2024-01-22 | Viperio                 | W   | 0.505      | -            | -                | -                | -             |     0.99 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|           26 |     4475 | 2024-01-22 | Rebels Gaming           | W   | 0.505      | -            | -                | -                | -             |     9.78 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|           25 |     4677 | 2024-01-18 | Sprout                  | W   | 0.477      | -            | -                | -                | -             |     0.70 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|           24 |     4691 | 2024-01-17 | Into The Breach         | W   | 0.473      | -            | -                | -                | -             |     3.22 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|           23 |     4695 | 2024-01-17 | Capcarap                | W   | 0.473      | -            | -                | -                | -             |     0.79 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|           22 |     4701 | 2024-01-17 | Rebels Gaming           | W   | 0.473      | -            | -                | -                | -             |     9.64 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|           21 |     4734 | 2024-01-17 | ARROW (German team)     | W   | 0.472      | -            | -                | -                | -             |     1.83 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|           20 |     5671 | 2023-12-12 | Aurora Gaming           | L   | 0.232      | -            | -                | -                | -             |    -0.29 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|           19 |     5705 | 2023-12-11 | Ex-Anonymo Esports      | W   | 0.223      | -            | -                | -                | -             |     1.31 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|           18 |     5891 | 2023-12-07 | Aurora Gaming           | L   | 0.198      | -            | -                | -                | -             |    -0.24 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|           17 |     5920 | 2023-12-06 | 9Pandas                 | W   | 0.192      | -            | -                | -                | -             |     3.84 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|           16 |     5941 | 2023-12-06 | G2 Esports              | W   | 0.191      | 0.589        | 0.866 (0.097)    | -                | -             |     5.96 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|           15 |     5996 | 2023-12-05 | Ex-Anonymo Esports      | W   | 0.184      | -            | -                | -                | -             |     1.09 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|           14 |     6024 | 2023-12-04 | ALTERNATE aTTaX         | W   | 0.176      | 0.589        | 0.110 (0.011)    | 0.723 (0.075)    | -             |     3.08 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|           13 |     6036 | 2023-12-03 | BIG                     | L   | 0.172      | -            | -                | -                | -             |    -0.53 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|           12 |     6170 | 2023-12-01 | Bad News Kangaroos      | W   | 0.156      | -            | -                | -                | -             |     1.93 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|           11 |     6213 | 2023-11-30 | Gaimin Gladiators       | W   | 0.151      | 0.384        | 0.194 (0.011)    | -                | -             |     4.34 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|           10 |     6385 | 2023-11-26 | Zero Tenacity           | W   | 0.126      | -            | -                | -                | -             |     1.66 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|            9 |     6418 | 2023-11-25 | Zero Tenacity           | W   | 0.119      | -            | -                | -                | -             |     1.58 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|            8 |     6502 | 2023-11-23 | ILLYRIANS               | W   | 0.106      | -            | -                | -                | -             |     0.54 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|            7 |     6569 | 2023-11-22 | GODSENT                 | W   | 0.098      | -            | -                | -                | -             |     0.69 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|            6 |     6584 | 2023-11-21 | Miracles                | W   | 0.092      | -            | -                | -                | -             |     0.09 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|            5 |     6724 | 2023-11-18 | Soda Gaming             | L   | 0.071      | -            | -                | -                | -             |    -1.83 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|            4 |     6804 | 2023-11-16 | ALTERNATE aTTaX         | L   | 0.059      | -            | -                | -                | -             |    -0.77 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|            3 |     6852 | 2023-11-16 | Team Space              | L   | 0.056      | -            | -                | -                | -             |    -1.47 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|            2 |     6886 | 2023-11-15 | Preasy Esport           | L   | 0.051      | -            | -                | -                | -             |    -0.98 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|            1 |     7174 | 2023-11-08 | ARCRED                  | L   | 0.005      | -            | -                | -                | -             |    -0.13 | 1NVISIBLEE, DSSj, hurtslxrd, Ryujin, shg    |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($5,819.12)
- Divide that value by the 5th highest value among all rosters ($158,437.64)
- The final value (0.04) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2023-12-13 |      0.239 | $1,000.00      | $238.59         |
| 2023-12-07 |      0.199 | $25,000.00     | $4,970.49       |
| 2023-11-26 |      0.126 | $4,672.43      | $586.43         |
| 2023-11-09 |      0.012 | $2,000.00      | $23.61          |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
