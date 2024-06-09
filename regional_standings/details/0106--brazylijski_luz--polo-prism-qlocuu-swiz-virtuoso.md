### Roster Details<br />
Team Name: brazylijski luz<br />
Roster: POLO, Prism, Qlocuu, swiz, virtuoso<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [106](../standings_global.md)<br />
Regional Rank: [76]( ../standings_europe.md)<br />
Final Rank Value:  860.8<br />
<br />
Final Rank Value (860.8) = Starting Rank Value (812.8) + Head To Head Adjustments (48.0)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.346[<sup>1</sup>](#table2)
- Bounty Collected: 0.345[<sup>2</sup>](#table1)
- Opponent Network: 0.121[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.203<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 812.8
- 400 + ( ( 0.203 - 0.000 ) / ( 0.787 - 0.000 ) ) * 1600 = 812.8


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent             | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                       |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           70 |       82 | 2024-05-29 | SINNERS Esports      | L   | 1.000      | -            | -                | -                | -         |   -10.12 | POLO, Prism, Qlocuu, swiz, virtuoso          |
|           69 |      200 | 2024-05-27 | Entropiq             | W   | 1.000      | 0.371        | -                | 0.220 (0.082)    | 0 (0.000) |     9.19 | POLO, Prism, Qlocuu, swiz, virtuoso          |
|           68 |      398 | 2024-05-23 | GamerLegion Academy  | W   | 1.000      | 0.143        | 0.018 (0.003)    | 0.691 (0.099)    | 0 (0.000) |    13.37 | POLO, Prism, Qlocuu, swiz, virtuoso          |
|           67 |      427 | 2024-05-23 | Zero Tenacity        | L   | 1.000      | -            | -                | -                | -         |    -6.76 | POLO, Prism, Qlocuu, swiz, virtuoso          |
|           66 |      786 | 2024-05-19 | Pera Esports         | L   | 1.000      | -            | -                | -                | -         |   -13.29 | POLO, Prism, Qlocuu, swiz, virtuoso          |
|           65 |     1373 | 2024-05-12 | DMS                  | L   | 1.000      | -            | -                | -                | -         |   -15.18 | POLO, Prism, Qlocuu, swiz, virtuoso          |
|           64 |     1380 | 2024-05-12 | 5W Gaming            | W   | 1.000      | -            | -                | -                | 0 (0.000) |     3.70 | POLO, Prism, Qlocuu, swiz, virtuoso          |
|           63 |     1390 | 2024-05-12 | 1win                 | W   | 1.000      | 0.143        | 0.050 (0.007)    | 0.898 (0.128)    | 0 (0.000) |    21.95 | POLO, Prism, Qlocuu, swiz, virtuoso          |
|           62 |     1453 | 2024-05-11 | ENTERPRISE esports   | L   | 1.000      | -            | -                | -                | -         |   -12.41 | POLO, Prism, Qlocuu, swiz, virtuoso          |
|           61 |     1768 | 2024-05-06 | Grannys Knockers     | L   | 1.000      | -            | -                | -                | -         |   -17.00 | POLO, Prism, Qlocuu, swiz, virtuoso          |
|           60 |     2147 | 2024-04-28 | VP.Prodigy           | W   | 0.990      | 0.143        | -                | 0.829 (0.117)    | 0 (0.000) |    11.81 | POLO, Prism, Qlocuu, swiz, virtuoso          |
|           59 |     2164 | 2024-04-28 | Nexus Gaming         | W   | 0.988      | 0.143        | -                | 0.857 (0.121)    | 0 (0.000) |    16.72 | POLO, Prism, Qlocuu, swiz, virtuoso          |
|           58 |     2635 | 2024-04-20 | Sangal Esports       | L   | 0.937      | -            | -                | -                | -         |    -7.90 | POLO, Prism, Qlocuu, swiz, virtuoso          |
|           57 |     2739 | 2024-04-19 | Rebels Gaming        | W   | 0.931      | 0.500        | 0.062 (0.029)    | 0.411 (0.191)    | 0 (0.000) |    22.77 | POLO, Prism, Qlocuu, swiz, virtuoso          |
|           56 |     2807 | 2024-04-18 | BetBoom Team         | L   | 0.924      | -            | -                | -                | -         |    -1.82 | POLO, Prism, Qlocuu, swiz, virtuoso          |
|           55 |     2816 | 2024-04-18 | Ninjas in Pyjamas    | W   | 0.923      | 0.143        | 0.118 (0.016)    | -                | 0 (0.000) |    23.98 | POLO, Prism, Qlocuu, swiz, virtuoso          |
|           54 |     2882 | 2024-04-17 | HEROIC               | W   | 0.918      | 0.143        | 0.322 (0.042)    | -                | 0 (0.000) |    28.68 | POLO, Prism, Qlocuu, swiz, virtuoso          |
|           53 |     3136 | 2024-04-12 | AVEZ                 | L   | 0.884      | -            | -                | -                | -         |   -12.13 | POLO, Prism, Qlocuu, swiz, virtuoso          |
|           52 |     3173 | 2024-04-11 | DEEZ NUTS            | W   | 0.878      | -            | -                | -                | 0 (0.000) |     7.59 | POLO, Prism, Qlocuu, swiz, virtuoso          |
|           51 |     3193 | 2024-04-11 | Permitta Esports     | L   | 0.876      | -            | -                | -                | -         |    -7.80 | POLO, Prism, Qlocuu, swiz, virtuoso          |
|           50 |     3238 | 2024-04-10 | Betera Esports       | W   | 0.871      | 0.500        | 0.023 (0.010)    | 0.257 (0.112)    | -         |    16.16 | POLO, Prism, Qlocuu, swiz, virtuoso          |
|           49 |     3313 | 2024-04-09 | FORZE Esports        | L   | 0.864      | -            | -                | -                | -         |   -15.48 | POLO, Prism, Qlocuu, swiz, virtuoso          |
|           48 |     3328 | 2024-04-09 | M1 Gaming            | W   | 0.863      | -            | -                | -                | -         |     7.20 | POLO, Prism, Qlocuu, swiz, virtuoso          |
|           47 |     3367 | 2024-04-08 | 9INE                 | L   | 0.857      | -            | -                | -                | -         |   -18.72 | POLO, Prism, Qlocuu, swiz, virtuoso          |
|           46 |     3902 | 2024-03-27 | BetBoom Team         | L   | 0.777      | -            | -                | -                | -         |    -1.19 | POLO, Prism, Qlocuu, swiz, virtuoso          |
|           45 |     3959 | 2024-03-26 | RUBY                 | W   | 0.771      | 0.143        | -                | 0.738 (0.081)    | -         |    15.99 | POLO, Prism, Qlocuu, swiz, virtuoso          |
|           44 |     4733 | 2024-03-11 | SINNERS Esports      | W   | 0.671      | 0.500        | 0.011 (0.004)    | 0.582 (0.195)    | -         |    16.40 | POLO, Prism, Qlocuu, swiz, virtuoso          |
|           43 |     4769 | 2024-03-10 | DEEZ NUTS            | W   | 0.665      | -            | -                | -                | -         |     6.93 | POLO, Prism, Qlocuu, swiz, virtuoso          |
|           42 |     4773 | 2024-03-10 | Swell                | W   | 0.664      | -            | -                | -                | -         |     2.25 | POLO, Prism, Qlocuu, swiz, virtuoso          |
|           41 |     4987 | 2024-03-06 | ALTERNATE aTTaX      | L   | 0.638      | -            | -                | -                | -         |    -6.16 | POLO, Prism, Qlocuu, swiz, virtuoso          |
|           40 |     5273 | 2024-03-02 | ex-Preasy Esport     | L   | 0.612      | -            | -                | -                | -         |    -5.35 | POLO, Prism, Qlocuu, SaMey, virtuoso         |
|           39 |     5290 | 2024-03-02 | Insilio              | W   | 0.611      | -            | -                | -                | -         |    13.85 | POLO, Prism, Qlocuu, SaMey, virtuoso         |
|           38 |     5347 | 2024-03-02 | Sashi Esport         | L   | 0.609      | -            | -                | -                | -         |    -2.87 | Furlan, phr, POLO, Prism, Qlocuu             |
|           37 |     5441 | 2024-02-29 | Viperio              | L   | 0.596      | -            | -                | -                | -         |   -12.45 | mAnGo, MMS, pandi7o, ReegaN, zodi            |
|           36 |     5524 | 2024-02-27 | Team Spirit Academy  | L   | 0.584      | -            | -                | -                | -         |    -9.54 | POLO, Prism, Qlocuu, swiz, virtuoso          |
|           35 |     5565 | 2024-02-26 | Monte Gen            | W   | 0.578      | -            | -                | -                | -         |     9.74 | POLO, Prism, Qlocuu, swiz, virtuoso          |
|           34 |     5625 | 2024-02-25 | MOUZ NXT             | L   | 0.568      | -            | -                | -                | -         |    -2.42 | Burmylov, Chr1zN, Neityu, PR, sirah          |
|           33 |     5677 | 2024-02-24 | DEEZ NUTS            | L   | 0.564      | -            | -                | -                | -         |   -12.47 | nestee, POLO, Prism, swiz, virtuoso          |
|           32 |     5717 | 2024-02-24 | The Chosen Few       | W   | 0.563      | -            | -                | -                | -         |     7.99 | Furlan, phr, POLO, Prism, Qlocuu             |
|           31 |     6025 | 2024-02-19 | Entropiq             | L   | 0.528      | -            | -                | -                | -         |   -11.09 | Furlan, phr, POLO, Prism, Qlocuu             |
|           30 |     6050 | 2024-02-18 | ARCRED               | W   | 0.523      | -            | -                | -                | -         |     7.58 | Furlan, phr, POLO, Prism, Qlocuu             |
|           29 |     6134 | 2024-02-17 | Natus Vincere Junior | W   | 0.515      | 0.333        | 0.010 (0.002)    | -                | -         |     8.39 | Furlan, phr, POLO, Prism, Qlocuu             |
|           28 |     6176 | 2024-02-16 | Sashi Esport         | L   | 0.509      | -            | -                | -                | -         |    -8.46 | b0RUP, n1Xen, niko, nut nut, PR1mE           |
|           27 |     6250 | 2024-02-15 | Viperio              | L   | 0.502      | -            | -                | -                | -         |   -11.21 | Furlan, phr, POLO, Prism, Qlocuu             |
|           26 |     6290 | 2024-02-14 | Entropiq             | L   | 0.496      | -            | -                | -                | -         |   -10.71 | Furlan, phr, POLO, Prism, Qlocuu             |
|           25 |     6405 | 2024-02-12 | WOPA Esport          | W   | 0.482      | 0.303        | -                | 0.594 (0.087)    | -         |     7.16 | brzer, Gnøffe, Leakz, LUMSEN, Pellyy         |
|           24 |     6502 | 2024-02-09 | Dynamo Eclot         | L   | 0.462      | -            | -                | -                | -         |    -2.66 | Furlan, m4tthi, Prism, Qlocuu, virtuoso      |
|           23 |     6639 | 2024-02-05 | Copenhagen Wolves    | W   | 0.436      | -            | -                | -                | -         |     4.40 | Basso, mupzG, smF, Svedjehed, szejn          |
|           22 |     6659 | 2024-02-04 | ALTERNATE aTTaX      | L   | 0.431      | -            | -                | -                | -         |    -4.33 | Furlan, phr, POLO, Prism, Qlocuu             |
|           21 |     7002 | 2024-01-29 | Sashi Esport         | L   | 0.392      | -            | -                | -                | -         |    -2.52 | Furlan, phr, POLO, Prism, Qlocuu             |
|           20 |     7019 | 2024-01-29 | GenOne               | W   | 0.392      | -            | -                | -                | -         |     3.33 | Furlan, phr, POLO, Prism, Qlocuu             |
|           19 |     7796 | 2024-01-17 | ex-sYnck             | L   | 0.311      | -            | -                | -                | -         |    -5.89 | Furlan, phr, POLO, Prism, Qlocuu             |
|           18 |     8330 | 2024-01-09 | Gaimin Gladiators    | L   | 0.258      | -            | -                | -                | -         |    -0.55 | kraghen, Nodios, Patti, Queenix, salazar     |
|           17 |     8344 | 2024-01-09 | Nemiga Gaming        | W   | 0.257      | 0.143        | 0.358 (0.013)    | -                | -         |     7.48 | Furlan, phr, POLO, Prism, Qlocuu             |
|           16 |     8360 | 2024-01-09 | Team Secret          | W   | 0.257      | -            | -                | -                | -         |     2.14 | anarkez, innocent, Kind0, Maze, Tauson       |
|           15 |     8491 | 2024-01-04 | ex-Anonymo Esports   | L   | 0.222      | -            | -                | -                | -         |    -4.53 | Furlan, phr, POLO, Prism, Qlocuu             |
|           14 |     8567 | 2023-12-29 | Alliance             | L   | 0.182      | -            | -                | -                | -         |    -2.43 | avid, b0denmaster, PlesseN, robiin, twist    |
|           13 |     8572 | 2023-12-28 | VP.Prodigy           | L   | 0.175      | -            | -                | -                | -         |    -2.50 | Furlan, phr, POLO, Qlocuu, swiz              |
|           12 |     8577 | 2023-12-27 | Rhyno Esports        | W   | 0.169      | 0.371        | 0.029 (0.002)    | -                | -         |     4.14 | Furlan, phr, POLO, Qlocuu, swiz              |
|           11 |     8626 | 2023-12-21 | Viperio              | W   | 0.130      | -            | -                | -                | -         |     0.90 | mAnGo, MMS, pandi7o, ReegaN, zodi            |
|           10 |     8629 | 2023-12-21 | Betera Esports       | L   | 0.129      | -            | -                | -                | -         |    -2.13 | Furlan, phr, POLO, Prism, Qlocuu             |
|            9 |     8664 | 2023-12-19 | Astralis Talent      | W   | 0.115      | -            | -                | -                | -         |     2.35 | ANSG1, JBOEN, kiR, kroK, tOPZ                |
|            8 |     8745 | 2023-12-17 | Nexus Gaming         | W   | 0.102      | -            | -                | -                | -         |     2.03 | Furlan, phr, POLO, Prism, Qlocuu             |
|            7 |     9017 | 2023-12-15 | Passion UA           | W   | 0.089      | -            | -                | -                | -         |     2.15 | jackasmo, jambo, marat2k, s-chilla, zeRRoFIX |
|            6 |     9118 | 2023-12-13 | Astralis Talent      | W   | 0.075      | -            | -                | -                | -         |     1.54 | Furlan, phr, POLO, Prism, Qlocuu             |
|            5 |     9153 | 2023-12-12 | The Witchers         | L   | 0.070      | -            | -                | -                | -         |    -1.41 | Dragon, fear, Sdaim, smooya, synyx           |
|            4 |     9261 | 2023-12-10 | Pompa Team           | W   | 0.055      | -            | -                | -                | -         |     0.24 | Furlan, phr, POLO, Prism, Qlocuu             |
|            3 |     9379 | 2023-12-08 | Zero Tenacity        | L   | 0.043      | -            | -                | -                | -         |    -0.23 | aVN, brutmonster, Cjoffo, nEMANHA, simke     |
|            2 |     9451 | 2023-12-07 | Lazer Cats           | W   | 0.036      | -            | -                | -                | -         |     0.10 | Furlan, phr, POLO, Prism, Qlocuu             |
|            1 |     9619 | 2023-12-04 | Pompa Team           | L   | 0.017      | -            | -                | -                | -         |    -0.45 | Furlan, phr, POLO, Prism, Qlocuu             |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($3,868.46)
- Divide that value by the 5th highest value among all rosters ($300,806.11)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-05-22 |      1.000 | $3,000.00      | $3,000.00       |
| 2024-04-21 |      0.943 | $492.92        | $464.99         |
| 2023-12-19 |      0.115 | $3,500.00      | $403.47         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
