### Roster Details<br />
Team Name: RUBY<br />
Roster: dekz, Kaide, mo0n, Sowalio, w1nt3r<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [62](../standings_global.md)<br />
Regional Rank: [46]( ../standings_europe.md)<br />
Final Rank Value:  948.3<br />
<br />
Final Rank Value (948.3) = Starting Rank Value (866.1) + Head To Head Adjustments (82.2)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.341[<sup>1</sup>](#table2)
- Bounty Collected: 0.403[<sup>2</sup>](#table1)
- Opponent Network: 0.196[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.235<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 866.1
- 400 + ( ( 0.235 - 0.000 ) / ( 0.806 - 0.000 ) ) * 1600 = 866.1


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent            | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                       |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           54 |        9 | 2024-05-05 | LEON Esports        | W   | 1.000      | -            | -                | -                | 0 (0.000) |     6.41 | dekz, Kaide, mo0n, Sowalio, w1nt3r           |
|           53 |       22 | 2024-05-05 | HAVU Gaming         | W   | 1.000      | 0.435        | 0.024 (0.010)    | -                | 0 (0.000) |     8.11 | dekz, Kaide, mo0n, Sowalio, w1nt3r           |
|           52 |       65 | 2024-05-04 | FORZE Youngsters    | W   | 1.000      | -            | -                | -                | 0 (0.000) |     1.41 | dekz, Kaide, mo0n, Sowalio, w1nt3r           |
|           51 |      115 | 2024-05-03 | V1dar Gaming        | W   | 1.000      | 0.435        | -                | 0.345 (0.150)    | 0 (0.000) |     6.08 | dekz, Kaide, mo0n, Sowalio, w1nt3r           |
|           50 |      193 | 2024-05-01 | DMS                 | L   | 1.000      | -            | -                | -                | -         |   -22.22 | dekz, Kaide, mo0n, Sowalio, w1nt3r           |
|           49 |      221 | 2024-05-01 | GamerLegion Academy | L   | 1.000      | -            | -                | -                | -         |   -18.43 | dekz, Kaide, mo0n, Sowalio, w1nt3r           |
|           48 |      270 | 2024-04-29 | RoundsGG            | W   | 1.000      | -            | -                | -                | 0 (0.000) |     4.96 | dekz, Kaide, mo0n, Sowalio, w1nt3r           |
|           47 |      362 | 2024-04-27 | Astralis Talent     | W   | 1.000      | -            | -                | -                | 0 (0.000) |     1.30 | dekz, Kaide, mo0n, Sowalio, w1nt3r           |
|           46 |      473 | 2024-04-25 | MOUZ NXT            | L   | 1.000      | -            | -                | -                | -         |   -13.34 | dekz, Kaide, mo0n, Sowalio, w1nt3r           |
|           45 |      521 | 2024-04-24 | EsmagaB             | L   | 1.000      | -            | -                | -                | -         |   -22.75 | dekz, Kaide, mo0n, Sowalio, w1nt3r           |
|           44 |      529 | 2024-04-24 | Copenhagen Wolves   | W   | 1.000      | 0.371        | -                | 0.417 (0.155)    | 0 (0.000) |     3.78 | dekz, Kaide, mo0n, Sowalio, w1nt3r           |
|           43 |      575 | 2024-04-23 | GenOne              | W   | 1.000      | -            | -                | -                | 0 (0.000) |     3.54 | dekz, Kaide, mo0n, Sowalio, w1nt3r           |
|           42 |      585 | 2024-04-23 | Permitta Esports    | W   | 1.000      | 0.371        | 0.063 (0.023)    | 1.000 (0.371)    | 0 (0.000) |    13.86 | dekz, Kaide, mo0n, Sowalio, w1nt3r           |
|           41 |      622 | 2024-04-22 | GUN5 Esports        | W   | 1.000      | -            | -                | -                | 0 (0.000) |     5.08 | dekz, Kaide, mo0n, Sowalio, w1nt3r           |
|           40 |      727 | 2024-04-20 | Zero Tenacity       | L   | 1.000      | -            | -                | -                | -         |   -17.38 | dekz, kaide, mo0n, Sowalio, w1nt3r           |
|           39 |      820 | 2024-04-19 | GamerLegion Academy | W   | 1.000      | 0.371        | 0.043 (0.016)    | 0.567 (0.211)    | -         |    11.03 | dekz, Kaide, mo0n, Sowalio, w1nt3r           |
|           38 |      872 | 2024-04-18 | Sashi Esport        | L   | 1.000      | -            | -                | -                | -         |   -10.85 | dekz, Kaide, mo0n, Sowalio, w1nt3r           |
|           37 |      881 | 2024-04-18 | Aurora Gaming       | W   | 1.000      | 0.143        | 1.000 (0.143)    | -                | -         |    30.02 | dekz, Kaide, mo0n, Sowalio, w1nt3r           |
|           36 |      886 | 2024-04-18 | NOM Esports         | W   | 1.000      | -            | -                | -                | -         |     6.06 | dekz, kaide, mo0n, Sowalio, w1nt3r           |
|           35 |      933 | 2024-04-17 | Team Falcons        | W   | 1.000      | 0.143        | 0.431 (0.062)    | -                | -         |    28.77 | dekz, Kaide, mo0n, Sowalio, w1nt3r           |
|           34 |      970 | 2024-04-17 | JANO Esports        | W   | 1.000      | -            | -                | -                | -         |     8.43 | dekz, kaide, mo0n, Sowalio, w1nt3r           |
|           33 |     1117 | 2024-04-13 | ARCRED              | L   | 1.000      | -            | -                | -                | -         |   -19.56 | dekz, Kaide, mo0n, Sowalio, w1nt3r           |
|           32 |     1369 | 2024-04-07 | Insilio             | W   | 1.000      | 0.143        | -                | 0.875 (0.125)    | -         |    18.06 | dekz, Kaide, mo0n, Sowalio, w1nt3r           |
|           31 |     2056 | 2024-03-19 | Sashi Esport        | L   | 0.885      | -            | -                | -                | -         |   -10.14 | dekz, Kaide, mo0n, Sowalio, w1nt3r           |
|           30 |     2178 | 2024-03-16 | Permitta Esports    | W   | 0.864      | 0.371        | 0.063 (0.020)    | 1.000 (0.321)    | -         |    16.61 | dekz, Kaide, mo0n, Sowalio, w1nt3r           |
|           29 |     2419 | 2024-03-11 | Nexus Gaming        | L   | 0.832      | -            | -                | -                | -         |   -12.07 | dekz, Kaide, mo0n, Sowalio, w1nt3r           |
|           28 |     2495 | 2024-03-09 | Team Spirit Academy | W   | 0.818      | 0.371        | -                | 0.422 (0.128)    | -         |    11.27 | dekz, Kaide, mo0n, Sowalio, w1nt3r           |
|           27 |     2528 | 2024-03-08 | ARCRED              | W   | 0.812      | 0.371        | -                | 0.825 (0.249)    | -         |    10.24 | dekz, Kaide, mo0n, Sowalio, w1nt3r           |
|           26 |     2746 | 2024-03-04 | Johnny Speeds       | L   | 0.786      | -            | -                | -                | -         |   -14.75 | dekz, Kaide, mo0n, Sowalio, w1nt3r           |
|           25 |     2864 | 2024-03-02 | ILIN                | L   | 0.772      | -            | -                | -                | -         |   -20.46 | dekz, Kaide, mo0n, Sowalio, w1nt3r           |
|           24 |     2962 | 2024-02-29 | INGLORIOUS          | W   | 0.758      | -            | -                | -                | -         |     8.80 | dekz, Kaide, mo0n, Sowalio, w1nt3r           |
|           23 |     2981 | 2024-02-28 | Permitta Esports    | L   | 0.752      | -            | -                | -                | -         |    -9.97 | dekz, Kaide, mo0n, Sowalio, w1nt3r           |
|           22 |     2988 | 2024-02-28 | ENTERPRISE esports  | W   | 0.752      | 0.371        | 0.039 (0.011)    | 0.476 (0.133)    | -         |    12.54 | dekz, Kaide, mo0n, Sowalio, w1nt3r           |
|           21 |     3021 | 2024-02-27 | Team Spirit Academy | L   | 0.745      | -            | -                | -                | -         |   -14.68 | dekz, Kaide, mo0n, Sowalio, w1nt3r           |
|           20 |     3032 | 2024-02-27 | ALTERNATE aTTaX     | W   | 0.745      | 0.143        | 0.110 (0.012)    | -                | -         |    13.30 | dekz, Kaide, mo0n, Sowalio, w1nt3r           |
|           19 |     3293 | 2024-02-21 | MOUZ NXT            | L   | 0.706      | -            | -                | -                | -         |    -6.22 | dekz, Kaide, mo0n, Sowalio, w1nt3r           |
|           18 |     3495 | 2024-02-17 | GenOne              | W   | 0.678      | -            | -                | -                | -         |     2.94 | dekz, Kaide, mo0n, Sowalio, w1nt3r           |
|           17 |     3670 | 2024-02-13 | Kappa Bar           | W   | 0.652      | -            | -                | -                | -         |     4.11 | dekz, Kaide, mo0n, Sowalio, w1nt3r           |
|           16 |     3724 | 2024-02-12 | DASH                | W   | 0.645      | -            | -                | -                | -         |     5.79 | dekz, Kaide, mo0n, Sowalio, w1nt3r           |
|           15 |     3814 | 2024-02-08 | AMKAL ESPORTS       | L   | 0.619      | -            | -                | -                | -         |    -2.71 | dekz, Kaide, mo0n, Sowalio, w1nt3r           |
|           14 |     3827 | 2024-02-08 | Guild Eagles        | W   | 0.618      | -            | -                | -                | -         |    13.80 | dekz, Kaide, mo0n, Sowalio, w1nt3r           |
|           13 |     4068 | 2024-02-01 | RoundsGG            | W   | 0.572      | -            | -                | -                | -         |     4.69 | dekz, Kaide, mo0n, Sowalio, w1nt3r           |
|           12 |     4109 | 2024-01-31 | GamerLegion Academy | W   | 0.565      | 0.371        | 0.043 (0.009)    | 0.567 (0.119)    | -         |     7.72 | dekz, Kaide, mo0n, Sowalio, w1nt3r           |
|           11 |     4136 | 2024-01-30 | Nemiga Gaming       | L   | 0.559      | -            | -                | -                | -         |    -1.52 | dekz, Kaide, mo0n, Sowalio, w1nt3r           |
|           10 |     4140 | 2024-01-30 | Permitta Esports    | W   | 0.559      | -            | -                | -                | -         |    11.59 | dekz, Kaide, mo0n, Sowalio, w1nt3r           |
|            9 |     4143 | 2024-01-30 | ILLYRIANS           | W   | 0.558      | -            | -                | -                | -         |     5.28 | dekz, Kaide, mo0n, Sowalio, w1nt3r           |
|            8 |     4158 | 2024-01-29 | The Chosen Few      | W   | 0.553      | -            | -                | -                | -         |     6.80 | dekz, Kaide, mo0n, Sowalio, w1nt3r           |
|            7 |     4189 | 2024-01-29 | BLEED Esports       | W   | 0.553      | 0.143        | 0.284 (0.022)    | -                | -         |    13.51 | dekz, Kaide, mo0n, Sowalio, w1nt3r           |
|            6 |     4461 | 2024-01-22 | Sashi Esport        | L   | 0.505      | -            | -                | -                | -         |    -4.24 | dekz, Kaide, mo0n, Sowalio, w1nt3r           |
|            5 |     4700 | 2024-01-17 | AMKAL ESPORTS       | L   | 0.473      | -            | -                | -                | -         |    -1.80 | dekz, Kaide, m1racle, Sowalio, w1nt3r        |
|            4 |     4727 | 2024-01-17 | Twisted Minds       | W   | 0.472      | -            | -                | -                | -         |     3.00 | D0cC, day0s, KD69z, m4tthi, SpAwNnS          |
|            3 |     4790 | 2024-01-16 | Passion UA          | L   | 0.466      | -            | -                | -                | -         |    -5.06 | jackasmo, jambo, marat2k, s-chilla, zeRRoFIX |
|            2 |     4801 | 2024-01-16 | TSM                 | W   | 0.465      | -            | -                | -                | -         |     4.56 | dekz, Kaide, m1racle, Sowalio, w1nt3r        |
|            1 |     5460 | 2023-12-16 | EYEBALLERS          | L   | 0.259      | -            | -                | -                | -         |    -3.13 | Ao-, dekz, Kaide, Sowalio, YumsaN            |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($1,849.35)
- Divide that value by the 5th highest value among all rosters ($158,437.64)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
