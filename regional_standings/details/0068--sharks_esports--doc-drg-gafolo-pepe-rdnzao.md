### Roster Details<br />
Team Name: Sharks Esports<br />
Roster: doc, drg, gafolo, pepe, rdnzao<br />
Region: [Americas]( ../standings_americas.md)<br />
<br />
Global Rank: [68](../standings_global.md)<br />
Regional Rank: [17]( ../standings_americas.md)<br />
Final Rank Value:  949.2<br />
<br />
Final Rank Value (949.2) = Starting Rank Value (888.7) + Head To Head Adjustments (60.5)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.398[<sup>1</sup>](#table2)
- Bounty Collected: 0.394[<sup>2</sup>](#table1)
- Opponent Network: 0.168[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.240<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 888.7
- 400 + ( ( 0.240 - 0.000 ) / ( 0.786 - 0.000 ) ) * 1600 = 888.7


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent            | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                           |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           72 |      455 | 2024-05-22 | Imperial Esports    | W   | 1.000      | 0.450        | 0.372 (0.167)    | 0.582 (0.262)    | 0 (0.000) |    28.93 | doc, drg, gafolo, pepe, rdnzao   |
|           71 |      473 | 2024-05-22 | Imperial Esports    | L   | 1.000      | -            | -                | -                | -         |    -2.26 | doc, drg, gafolo, pepe, rdnzao   |
|           70 |      958 | 2024-05-17 | ODDIK               | L   | 1.000      | -            | -                | -                | -         |   -16.79 | doc, drg, gafolo, rdnzao, togs   |
|           69 |     1036 | 2024-05-16 | w7m esports         | W   | 1.000      | 0.450        | -                | 0.259 (0.117)    | 0 (0.000) |     8.09 | doc, drg, gafolo, rdnzao, togs   |
|           68 |     1039 | 2024-05-16 | w7m esports         | W   | 1.000      | 0.450        | -                | 0.259 (0.117)    | 0 (0.000) |     8.66 | doc, drg, gafolo, rdnzao, togs   |
|           67 |     1062 | 2024-05-16 | Hype Esports        | W   | 1.000      | -            | -                | -                | 0 (0.000) |     6.61 | doc, drg, gafolo, rdnzao, togs   |
|           66 |     1125 | 2024-05-15 | Vikings KR          | W   | 1.000      | -            | -                | -                | 0 (0.000) |     8.19 | doc, drg, gafolo, rdnzao, togs   |
|           65 |     1134 | 2024-05-15 | 9z Team             | L   | 1.000      | -            | -                | -                | -         |    -3.87 | doc, drg, gafolo, rdnzao, togs   |
|           64 |     1240 | 2024-05-14 | Fluxo               | L   | 1.000      | -            | -                | -                | -         |    -7.71 | doc, drg, gafolo, rdnzao, togs   |
|           63 |     1299 | 2024-05-13 | RED Canids          | W   | 1.000      | 0.384        | 0.076 (0.029)    | 0.508 (0.195)    | 0 (0.000) |    22.14 | doc, drg, gafolo, rdnzao, togs   |
|           62 |     1415 | 2024-05-11 | w7m esports         | W   | 1.000      | -            | -                | -                | 0 (0.000) |    10.37 | doc, drg, gafolo, rdnzao, togs   |
|           61 |     1547 | 2024-05-09 | BESTIA              | L   | 1.000      | -            | -                | -                | -         |   -16.27 | doc, drg, gafolo, rdnzao, togs   |
|           60 |     1597 | 2024-05-08 | 9z Team             | L   | 1.000      | -            | -                | -                | -         |    -4.04 | doc, drg, gafolo, rdnzao, togs   |
|           59 |     1703 | 2024-05-06 | BESTIA              | W   | 1.000      | 0.435        | 0.026 (0.011)    | 0.477 (0.207)    | 0 (0.000) |    14.53 | doc, drg, gafolo, rdnzao, togs   |
|           58 |     2249 | 2024-04-26 | TYLOO               | L   | 0.977      | -            | -                | -                | -         |   -13.84 | doc, drg, rdnzao, supLexN1, togs |
|           57 |     2316 | 2024-04-25 | M80                 | L   | 0.970      | -            | -                | -                | -         |    -3.37 | doc, drg, rdnzao, supLexN1, togs |
|           56 |     2423 | 2024-04-23 | Team Vitality       | L   | 0.956      | -            | -                | -                | -         |    -0.18 | doc, drg, rdnzao, supLexN1, togs |
|           55 |     2896 | 2024-04-16 | w7m esports         | L   | 0.912      | -            | -                | -                | -         |   -17.94 | doc, drg, rdnzao, supLexN1, togs |
|           54 |     3069 | 2024-04-12 | Galorys             | L   | 0.885      | -            | -                | -                | -         |   -16.68 | doc, drg, rdnzao, supLexN1, togs |
|           53 |     3106 | 2024-04-11 | paiN Gaming         | L   | 0.878      | -            | -                | -                | -         |    -0.82 | doc, drg, rdnzao, supLexN1, togs |
|           52 |     3146 | 2024-04-10 | ODDIK               | W   | 0.872      | 0.450        | 0.017 (0.007)    | 0.494 (0.194)    | 0 (0.000) |    12.50 | doc, drg, rdnzao, supLexN1, togs |
|           51 |     3150 | 2024-04-10 | ODDIK               | L   | 0.872      | -            | -                | -                | -         |   -15.21 | doc, drg, rdnzao, supLexN1, togs |
|           50 |     3281 | 2024-04-08 | paiN Gaming         | L   | 0.857      | -            | -                | -                | -         |    -0.81 | doc, drg, rdnzao, supLexN1, togs |
|           49 |     3344 | 2024-04-07 | BESTIA              | W   | 0.849      | 0.435        | 0.026 (0.010)    | 0.477 (0.176)    | 0 (0.000) |    13.21 | doc, drg, rdnzao, supLexN1, togs |
|           48 |     3369 | 2024-04-06 | ODDIK               | W   | 0.844      | -            | -                | -                | -         |    13.38 | doc, drg, rdnzao, supLexN1, togs |
|           47 |     3445 | 2024-04-05 | paiN Gaming         | L   | 0.837      | -            | -                | -                | -         |    -0.63 | doc, drg, rdnzao, supLexN1, togs |
|           46 |     3473 | 2024-04-04 | paiN Gaming         | L   | 0.832      | -            | -                | -                | -         |    -0.63 | doc, drg, rdnzao, supLexN1, togs |
|           45 |     3476 | 2024-04-04 | paiN Gaming         | L   | 0.832      | -            | -                | -                | -         |    -0.64 | doc, drg, rdnzao, supLexN1, togs |
|           44 |     3530 | 2024-04-03 | 2Game Esports       | W   | 0.825      | -            | -                | -                | -         |     5.04 | doc, drg, rdnzao, supLexN1, togs |
|           43 |     3531 | 2024-04-03 | 2Game Esports       | W   | 0.825      | -            | -                | -                | -         |     5.27 | doc, drg, rdnzao, supLexN1, togs |
|           42 |     3583 | 2024-04-02 | BESTIA              | L   | 0.819      | -            | -                | -                | -         |   -12.11 | doc, drg, rdnzao, supLexN1, togs |
|           41 |     3588 | 2024-04-02 | MIBR                | L   | 0.818      | -            | -                | -                | -         |    -0.85 | doc, drg, rdnzao, supLexN1, togs |
|           40 |     4460 | 2024-03-13 | Yawara E-Sports     | W   | 0.685      | -            | -                | -                | -         |     4.84 | doc, drg, gafolo, rdnzao, togs   |
|           39 |     4465 | 2024-03-13 | ODDIK               | W   | 0.685      | -            | -                | -                | -         |    11.58 | doc, drg, gafolo, rdnzao, togs   |
|           38 |     4541 | 2024-03-12 | 2Game Esports       | W   | 0.679      | -            | -                | -                | -         |     5.06 | doc, drg, gafolo, rdnzao, togs   |
|           37 |     4624 | 2024-03-11 | Fluxo               | L   | 0.670      | -            | -                | -                | -         |    -7.99 | doc, drg, gafolo, rdnzao, togs   |
|           36 |     4690 | 2024-03-09 | Case Esports        | L   | 0.658      | -            | -                | -                | -         |   -12.47 | doc, drg, gafolo, rdnzao, togs   |
|           35 |     4822 | 2024-03-07 | Corinthians Esports | W   | 0.643      | 0.435        | -                | 0.553 (0.154)    | -         |     4.17 | doc, drg, gafolo, rdnzao, togs   |
|           34 |     5505 | 2024-02-24 | Fluxo               | L   | 0.565      | -            | -                | -                | -         |    -7.55 | doc, drg, gafolo, rdnzao, togs   |
|           33 |     5689 | 2024-02-21 | Case Esports        | W   | 0.545      | 0.435        | 0.028 (0.007)    | -                | -         |     7.58 | doc, drg, gafolo, rdnzao, togs   |
|           32 |     5711 | 2024-02-21 | Galorys             | W   | 0.544      | -            | -                | -                | -         |     6.38 | doc, drg, gafolo, rdnzao, togs   |
|           31 |     5749 | 2024-02-20 | Flamengo Esports    | L   | 0.538      | -            | -                | -                | -         |   -15.16 | doc, drg, gafolo, rdnzao, togs   |
|           30 |     5768 | 2024-02-20 | Case Esports        | W   | 0.537      | -            | -                | -                | -         |     7.49 | doc, drg, gafolo, rdnzao, togs   |
|           29 |     5806 | 2024-02-19 | Yawara E-Sports     | W   | 0.533      | -            | -                | -                | -         |     3.87 | doc, drg, gafolo, rdnzao, togs   |
|           28 |     5828 | 2024-02-19 | Team Solid          | W   | 0.531      | 0.303        | 0.062 (0.010)    | -                | -         |     7.19 | doc, drg, gafolo, rdnzao, togs   |
|           27 |     5856 | 2024-02-18 | Galorys             | W   | 0.526      | 0.435        | 0.022 (0.005)    | 0.585 (0.134)    | -         |     6.85 | doc, drg, gafolo, rdnzao, togs   |
|           26 |     5919 | 2024-02-17 | w7m esports         | L   | 0.519      | -            | -                | -                | -         |   -10.11 | doc, drg, gafolo, rdnzao, togs   |
|           25 |     5926 | 2024-02-17 | Galorys             | L   | 0.518      | -            | -                | -                | -         |   -10.24 | doc, drg, gafolo, rdnzao, togs   |
|           24 |     5986 | 2024-02-16 | w7m esports         | W   | 0.510      | -            | -                | -                | -         |     5.99 | doc, drg, gafolo, rdnzao, togs   |
|           23 |     6023 | 2024-02-15 | Case Esports        | L   | 0.505      | -            | -                | -                | -         |    -9.02 | doc, drg, gafolo, rdnzao, togs   |
|           22 |     6082 | 2024-02-14 | Hype Esports        | W   | 0.499      | -            | -                | -                | -         |     1.36 | doc, drg, gafolo, rdnzao, togs   |
|           21 |     6098 | 2024-02-14 | Galorys             | W   | 0.497      | 0.435        | -                | 0.585 (0.127)    | -         |     5.77 | doc, drg, gafolo, rdnzao, togs   |
|           20 |     6847 | 2024-01-28 | w7m esports         | L   | 0.385      | -            | -                | -                | -         |    -8.27 | doc, drg, gafolo, rdnzao, togs   |
|           19 |     6853 | 2024-01-28 | Fluxo               | W   | 0.385      | -            | -                | -                | -         |     6.77 | doc, drg, gafolo, rdnzao, togs   |
|           18 |     6900 | 2024-01-27 | 2024                | W   | 0.379      | -            | -                | -                | -         |     0.59 | doc, drg, gafolo, rdnzao, togs   |
|           17 |     7069 | 2024-01-25 | Galorys             | L   | 0.366      | -            | -                | -                | -         |    -7.33 | doc, drg, gafolo, rdnzao, togs   |
|           16 |     7102 | 2024-01-24 | paiN Gaming         | W   | 0.359      | 0.143        | 0.463 (0.024)    | -                | -         |    11.06 | doc, drg, gafolo, rdnzao, togs   |
|           15 |     7167 | 2024-01-23 | adalYamigos         | W   | 0.352      | -            | -                | -                | -         |     2.19 | doc, drg, gafolo, rdnzao, togs   |
|           14 |     7204 | 2024-01-22 | Legacy              | W   | 0.346      | -            | -                | -                | -         |     7.26 | doc, drg, gafolo, rdnzao, togs   |
|           13 |     7269 | 2024-01-21 | 9z Team             | L   | 0.337      | -            | -                | -                | -         |    -1.26 | doc, drg, gafolo, rdnzao, togs   |
|           12 |     7318 | 2024-01-20 | paiN Gaming         | L   | 0.331      | -            | -                | -                | -         |    -0.20 | doc, drg, gafolo, rdnzao, togs   |
|           11 |     7382 | 2024-01-19 | Galorys             | W   | 0.326      | -            | -                | -                | -         |     4.17 | doc, drg, gafolo, rdnzao, togs   |
|           10 |     7389 | 2024-01-19 | TIMACETA            | L   | 0.325      | -            | -                | -                | -         |    -8.39 | doc, drg, gafolo, rdnzao, togs   |
|            9 |     7454 | 2024-01-18 | MIBR                | L   | 0.318      | -            | -                | -                | -         |    -0.21 | doc, drg, gafolo, rdnzao, togs   |
|            8 |     7507 | 2024-01-17 | RED Canids          | W   | 0.312      | -            | -                | -                | -         |     6.19 | doc, drg, gafolo, rdnzao, togs   |
|            7 |     7541 | 2024-01-17 | MIBR                | L   | 0.311      | -            | -                | -                | -         |    -0.19 | doc, drg, gafolo, rdnzao, togs   |
|            6 |     7744 | 2024-01-14 | paiN Gaming         | W   | 0.292      | 0.143        | 0.463 (0.019)    | -                | -         |     9.07 | doc, drg, gafolo, rdnzao, togs   |
|            5 |     7745 | 2024-01-14 | BESTIA              | W   | 0.292      | -            | -                | -                | -         |     5.36 | doc, drg, gafolo, rdnzao, togs   |
|            4 |     7748 | 2024-01-14 | Corinthians Esports | W   | 0.292      | -            | -                | -                | -         |     1.71 | doc, drg, gafolo, rdnzao, togs   |
|            3 |     7773 | 2024-01-13 | Galorys             | W   | 0.286      | -            | -                | -                | -         |     3.96 | doc, drg, gafolo, rdnzao, togs   |
|            2 |     9359 | 2023-12-03 | Case Esports        | W   | 0.011      | -            | -                | -                | -         |     0.08 | doc, drg, gafolo, rdnzao, togs   |
|            1 |     9430 | 2023-12-02 | w7m esports         | W   | 0.006      | -            | -                | -                | -         |     0.06 | doc, drg, gafolo, rdnzao, togs   |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($9,253.91)
- Divide that value by the 5th highest value among all rosters ($300,806.11)
- The final value (0.03) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-05-19 |      1.000 | $980.02        | $980.02         |
| 2024-05-12 |      1.000 | $3,500.00      | $3,500.00       |
| 2024-02-25 |      0.571 | $5,000.00      | $2,856.94       |
| 2024-02-21 |      0.544 | $3,500.00      | $1,902.64       |
| 2023-12-03 |      0.011 | $1,320.30      | $14.30          |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
