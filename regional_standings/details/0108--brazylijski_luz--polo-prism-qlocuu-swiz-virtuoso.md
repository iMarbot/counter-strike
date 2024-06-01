### Roster Details<br />
Team Name: brazylijski luz<br />
Roster: POLO, Prism, Qlocuu, swiz, virtuoso<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [108](../standings_global.md)<br />
Regional Rank: [76]( ../standings_europe.md)<br />
Final Rank Value:  856.3<br />
<br />
Final Rank Value (856.3) = Starting Rank Value (808.2) + Head To Head Adjustments (48.2)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.346[<sup>1</sup>](#table2)
- Bounty Collected: 0.342[<sup>2</sup>](#table1)
- Opponent Network: 0.114[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.201<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 808.2
- 400 + ( ( 0.201 - 0.000 ) / ( 0.786 - 0.000 ) ) * 1600 = 808.2


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
|           69 |       77 | 2024-05-29 | SINNERS Esports      | L   | 1.000      | -            | -                | -                | -         |   -10.27 | POLO, Prism, Qlocuu, swiz, virtuoso          |
|           68 |      192 | 2024-05-27 | Entropiq             | W   | 1.000      | 0.371        | -                | 0.220 (0.082)    | 0 (0.000) |     9.19 | POLO, Prism, Qlocuu, swiz, virtuoso          |
|           67 |      390 | 2024-05-23 | GamerLegion Academy  | W   | 1.000      | 0.143        | 0.018 (0.003)    | 0.691 (0.099)    | 0 (0.000) |    13.86 | POLO, Prism, Qlocuu, swiz, virtuoso          |
|           66 |      419 | 2024-05-23 | Zero Tenacity        | L   | 1.000      | -            | -                | -                | -         |    -6.74 | POLO, Prism, Qlocuu, swiz, virtuoso          |
|           65 |      774 | 2024-05-19 | Pera Esports         | L   | 1.000      | -            | -                | -                | -         |   -12.77 | POLO, Prism, Qlocuu, swiz, virtuoso          |
|           64 |     1360 | 2024-05-12 | DMS                  | L   | 1.000      | -            | -                | -                | -         |   -15.26 | POLO, Prism, Qlocuu, swiz, virtuoso          |
|           63 |     1367 | 2024-05-12 | 5W Gaming            | W   | 1.000      | -            | -                | -                | 0 (0.000) |     3.80 | POLO, Prism, Qlocuu, swiz, virtuoso          |
|           62 |     1377 | 2024-05-12 | 1win                 | W   | 1.000      | 0.143        | 0.050 (0.007)    | 0.887 (0.127)    | 0 (0.000) |    22.27 | POLO, Prism, Qlocuu, swiz, virtuoso          |
|           61 |     1440 | 2024-05-11 | ENTERPRISE esports   | L   | 1.000      | -            | -                | -                | -         |   -12.87 | POLO, Prism, Qlocuu, swiz, virtuoso          |
|           60 |     1745 | 2024-05-06 | Grannys Knockers     | L   | 1.000      | -            | -                | -                | -         |   -17.46 | POLO, Prism, Qlocuu, swiz, virtuoso          |
|           59 |     2112 | 2024-04-28 | VP.Prodigy           | W   | 0.990      | 0.143        | -                | 0.752 (0.106)    | 0 (0.000) |    11.41 | POLO, Prism, Qlocuu, swiz, virtuoso          |
|           58 |     2129 | 2024-04-28 | Nexus Gaming         | W   | 0.988      | 0.143        | 0.014 (0.002)    | 0.825 (0.116)    | 0 (0.000) |    16.70 | POLO, Prism, Qlocuu, swiz, virtuoso          |
|           57 |     2684 | 2024-04-19 | Rebels Gaming        | W   | 0.931      | 0.500        | 0.062 (0.029)    | 0.418 (0.195)    | 0 (0.000) |    22.90 | POLO, Prism, Qlocuu, swiz, virtuoso          |
|           56 |     2751 | 2024-04-18 | BetBoom Team         | L   | 0.924      | -            | -                | -                | -         |    -1.70 | POLO, Prism, Qlocuu, swiz, virtuoso          |
|           55 |     2760 | 2024-04-18 | Ninjas in Pyjamas    | W   | 0.923      | 0.143        | 0.118 (0.016)    | -                | 0 (0.000) |    24.27 | POLO, Prism, Qlocuu, swiz, virtuoso          |
|           54 |     2825 | 2024-04-17 | HEROIC               | W   | 0.918      | 0.143        | 0.322 (0.042)    | -                | 0 (0.000) |    28.70 | POLO, Prism, Qlocuu, swiz, virtuoso          |
|           53 |     3070 | 2024-04-12 | AVEZ                 | L   | 0.884      | -            | -                | -                | -         |   -12.98 | POLO, Prism, Qlocuu, swiz, virtuoso          |
|           52 |     3107 | 2024-04-11 | DEEZ NUTS            | W   | 0.878      | -            | -                | -                | 0 (0.000) |     7.91 | POLO, Prism, Qlocuu, swiz, virtuoso          |
|           51 |     3124 | 2024-04-11 | Permitta Esports     | L   | 0.876      | -            | -                | -                | -         |    -7.76 | POLO, Prism, Qlocuu, swiz, virtuoso          |
|           50 |     3234 | 2024-04-09 | FORZE Esports        | L   | 0.864      | -            | -                | -                | -         |    -4.55 | POLO, Prism, Qlocuu, swiz, virtuoso          |
|           49 |     3249 | 2024-04-09 | M1 Gaming            | W   | 0.863      | -            | -                | -                | -         |     7.42 | POLO, Prism, Qlocuu, swiz, virtuoso          |
|           48 |     3286 | 2024-04-08 | 9INE                 | L   | 0.857      | -            | -                | -                | -         |   -18.49 | POLO, Prism, Qlocuu, swiz, virtuoso          |
|           47 |     3742 | 2024-03-28 | Aurora Gaming        | L   | 0.784      | -            | -                | -                | -         |    -0.75 | POLO, Prism, Qlocuu, swiz, virtuoso          |
|           46 |     3809 | 2024-03-27 | BetBoom Team         | L   | 0.777      | -            | -                | -                | -         |    -1.17 | POLO, Prism, Qlocuu, swiz, virtuoso          |
|           45 |     3862 | 2024-03-26 | RUBY                 | W   | 0.771      | 0.143        | -                | 0.728 (0.080)    | -         |    16.13 | POLO, Prism, Qlocuu, swiz, virtuoso          |
|           44 |     4611 | 2024-03-11 | SINNERS Esports      | W   | 0.671      | 0.500        | 0.011 (0.004)    | 0.560 (0.188)    | -         |    16.13 | POLO, Prism, Qlocuu, swiz, virtuoso          |
|           43 |     4645 | 2024-03-10 | DEEZ NUTS            | W   | 0.665      | -            | -                | -                | -         |     7.10 | POLO, Prism, Qlocuu, swiz, virtuoso          |
|           42 |     4648 | 2024-03-10 | Swell                | W   | 0.664      | -            | -                | -                | -         |     2.33 | POLO, Prism, Qlocuu, swiz, virtuoso          |
|           41 |     4856 | 2024-03-06 | ALTERNATE aTTaX      | L   | 0.638      | -            | -                | -                | -         |    -5.95 | POLO, Prism, Qlocuu, swiz, virtuoso          |
|           40 |     5125 | 2024-03-02 | ex-Preasy Esport     | L   | 0.612      | -            | -                | -                | -         |    -5.28 | POLO, Prism, Qlocuu, SaMey, virtuoso         |
|           39 |     5142 | 2024-03-02 | Insilio              | W   | 0.611      | 0.143        | -                | 0.717 (0.063)    | -         |    14.03 | POLO, Prism, Qlocuu, SaMey, virtuoso         |
|           38 |     5198 | 2024-03-02 | Sashi Esport         | L   | 0.609      | -            | -                | -                | -         |    -2.88 | Furlan, phr, POLO, Prism, Qlocuu             |
|           37 |     5291 | 2024-02-29 | Viperio              | L   | 0.596      | -            | -                | -                | -         |   -12.53 | mAnGo, MMS, pandi7o, ReegaN, zodi            |
|           36 |     5371 | 2024-02-27 | Team Spirit Academy  | L   | 0.584      | -            | -                | -                | -         |    -9.44 | POLO, Prism, Qlocuu, swiz, virtuoso          |
|           35 |     5408 | 2024-02-26 | Monte Gen            | W   | 0.578      | -            | -                | -                | -         |     9.88 | POLO, Prism, Qlocuu, swiz, virtuoso          |
|           34 |     5467 | 2024-02-25 | MOUZ NXT             | L   | 0.568      | -            | -                | -                | -         |    -2.46 | Burmylov, Chr1zN, Neityu, PR, sirah          |
|           33 |     5517 | 2024-02-24 | DEEZ NUTS            | L   | 0.564      | -            | -                | -                | -         |   -12.30 | nestee, POLO, Prism, swiz, virtuoso          |
|           32 |     5557 | 2024-02-24 | The Chosen Few       | W   | 0.563      | -            | -                | -                | -         |     8.52 | Furlan, phr, POLO, Prism, Qlocuu             |
|           31 |     5853 | 2024-02-19 | Entropiq             | L   | 0.528      | -            | -                | -                | -         |   -10.95 | Furlan, phr, POLO, Prism, Qlocuu             |
|           30 |     5877 | 2024-02-18 | ARCRED               | W   | 0.523      | -            | -                | -                | -         |     7.79 | Furlan, phr, POLO, Prism, Qlocuu             |
|           29 |     5961 | 2024-02-17 | Natus Vincere Junior | W   | 0.515      | 0.333        | 0.010 (0.002)    | -                | -         |     8.57 | Furlan, phr, POLO, Prism, Qlocuu             |
|           28 |     6000 | 2024-02-16 | Sashi Esport         | L   | 0.509      | -            | -                | -                | -         |    -8.33 | b0RUP, n1Xen, niko, nut nut, PR1mE           |
|           27 |     6069 | 2024-02-15 | Viperio              | L   | 0.502      | -            | -                | -                | -         |   -11.27 | Furlan, phr, POLO, Prism, Qlocuu             |
|           26 |     6109 | 2024-02-14 | Entropiq             | L   | 0.496      | -            | -                | -                | -         |   -10.62 | Furlan, phr, POLO, Prism, Qlocuu             |
|           25 |     6217 | 2024-02-12 | WOPA Esport          | W   | 0.482      | 0.303        | -                | 0.594 (0.087)    | -         |     7.32 | brzer, Gnøffe, Leakz, LUMSEN, Pellyy         |
|           24 |     6314 | 2024-02-09 | Dynamo Eclot         | L   | 0.462      | -            | -                | -                | -         |    -2.59 | Furlan, m4tthi, Prism, Qlocuu, virtuoso      |
|           23 |     6438 | 2024-02-05 | Copenhagen Wolves    | W   | 0.436      | -            | -                | -                | -         |     4.13 | Basso, mupzG, smF, Svedjehed, szejn          |
|           22 |     6456 | 2024-02-04 | ALTERNATE aTTaX      | L   | 0.431      | -            | -                | -                | -         |    -8.55 | Furlan, phr, POLO, Prism, Qlocuu             |
|           21 |     6786 | 2024-01-29 | Sashi Esport         | L   | 0.392      | -            | -                | -                | -         |    -2.48 | Furlan, phr, POLO, Prism, Qlocuu             |
|           20 |     6803 | 2024-01-29 | GenOne               | W   | 0.392      | -            | -                | -                | -         |     3.35 | Furlan, phr, POLO, Prism, Qlocuu             |
|           19 |     7547 | 2024-01-17 | ex-sYnck             | L   | 0.311      | -            | -                | -                | -         |    -6.22 | Furlan, phr, POLO, Prism, Qlocuu             |
|           18 |     8076 | 2024-01-09 | Gaimin Gladiators    | L   | 0.258      | -            | -                | -                | -         |    -0.54 | kraghen, Nodios, Patti, Queenix, salazar     |
|           17 |     8090 | 2024-01-09 | Nemiga Gaming        | W   | 0.257      | 0.143        | 0.366 (0.013)    | -                | -         |     7.49 | Furlan, phr, POLO, Prism, Qlocuu             |
|           16 |     8106 | 2024-01-09 | Team Secret          | W   | 0.257      | -            | -                | -                | -         |     2.16 | anarkez, innocent, Kind0, Maze, Tauson       |
|           15 |     8235 | 2024-01-04 | ex-Anonymo Esports   | L   | 0.222      | -            | -                | -                | -         |    -4.50 | Furlan, phr, POLO, Prism, Qlocuu             |
|           14 |     8310 | 2023-12-29 | Alliance             | L   | 0.182      | -            | -                | -                | -         |    -2.42 | avid, b0denmaster, PlesseN, robiin, twist    |
|           13 |     8315 | 2023-12-28 | VP.Prodigy           | L   | 0.175      | -            | -                | -                | -         |    -2.53 | Furlan, phr, POLO, Qlocuu, swiz              |
|           12 |     8320 | 2023-12-27 | Rhyno Esports        | W   | 0.169      | 0.371        | 0.029 (0.002)    | -                | -         |     4.15 | Furlan, phr, POLO, Qlocuu, swiz              |
|           11 |     8369 | 2023-12-21 | Viperio              | W   | 0.130      | -            | -                | -                | -         |     0.91 | mAnGo, MMS, pandi7o, ReegaN, zodi            |
|           10 |     8372 | 2023-12-21 | Betera Esports       | L   | 0.129      | -            | -                | -                | -         |    -2.11 | Furlan, phr, POLO, Prism, Qlocuu             |
|            9 |     8407 | 2023-12-19 | Astralis Talent      | W   | 0.115      | -            | -                | -                | -         |     2.36 | ANSG1, JBOEN, kiR, kroK, tOPZ                |
|            8 |     8485 | 2023-12-17 | Nexus Gaming         | W   | 0.102      | -            | -                | -                | -         |     2.13 | Furlan, phr, POLO, Prism, Qlocuu             |
|            7 |     8755 | 2023-12-15 | Passion UA           | W   | 0.089      | -            | -                | -                | -         |     2.14 | jackasmo, jambo, marat2k, s-chilla, zeRRoFIX |
|            6 |     8854 | 2023-12-13 | Astralis Talent      | W   | 0.075      | -            | -                | -                | -         |     1.55 | Furlan, phr, POLO, Prism, Qlocuu             |
|            5 |     8889 | 2023-12-12 | The Witchers         | L   | 0.070      | -            | -                | -                | -         |    -1.40 | Dragon, fear, Sdaim, smooya, synyx           |
|            4 |     8995 | 2023-12-10 | Pompa Team           | W   | 0.055      | -            | -                | -                | -         |     0.24 | Furlan, phr, POLO, Prism, Qlocuu             |
|            3 |     9110 | 2023-12-08 | Zero Tenacity        | L   | 0.043      | -            | -                | -                | -         |    -0.23 | aVN, brutmonster, Cjoffo, nEMANHA, simke     |
|            2 |     9178 | 2023-12-07 | Lazer Cats           | W   | 0.036      | -            | -                | -                | -         |     0.10 | Furlan, phr, POLO, Prism, Qlocuu             |
|            1 |     9337 | 2023-12-04 | Pompa Team           | L   | 0.017      | -            | -                | -                | -         |    -0.45 | Furlan, phr, POLO, Prism, Qlocuu             |

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
