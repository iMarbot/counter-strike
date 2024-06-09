### Roster Details<br />
Team Name: Sharks Esports<br />
Roster: doc, gafolo, koala, pepe, rdnzao<br />
Region: [Americas]( ../standings_americas.md)<br />
<br />
Global Rank: [63](../standings_global.md)<br />
Regional Rank: [15]( ../standings_americas.md)<br />
Final Rank Value:  989.8<br />
<br />
Final Rank Value (989.8) = Starting Rank Value (889.8) + Head To Head Adjustments (100.0)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.368[<sup>1</sup>](#table2)
- Bounty Collected: 0.406[<sup>2</sup>](#table1)
- Opponent Network: 0.190[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.241<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 889.8
- 400 + ( ( 0.241 - 0.000 ) / ( 0.787 - 0.000 ) ) * 1600 = 889.8


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent            | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                            |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           73 |      461 | 2024-05-22 | Imperial Esports    | W   | 1.000      | 0.450        | 0.372 (0.167)    | 0.582 (0.262)    | 0 (0.000) |    28.33 | doc, gafolo, koala, pepe, rdnzao  |
|           72 |      479 | 2024-05-22 | Imperial Esports    | L   | 1.000      | -            | -                | -                | -         |    -2.81 | doc, gafolo, koala, pepe, rdnzao  |
|           71 |      542 | 2024-05-21 | Case Esports        | L   | 1.000      | -            | -                | -                | -         |   -18.91 | doc, gafolo, koala, pepe, rdnzao  |
|           70 |      545 | 2024-05-21 | Case Esports        | W   | 1.000      | 0.450        | 0.028 (0.013)    | 0.470 (0.212)    | 0 (0.000) |    12.32 | doc, gafolo, koala, pepe, rdnzao  |
|           69 |      551 | 2024-05-21 | RED Canids          | W   | 1.000      | 0.450        | 0.076 (0.034)    | 0.536 (0.241)    | 0 (0.000) |    22.40 | doc, gafolo, koala, pepe, rdnzao  |
|           68 |      554 | 2024-05-21 | RED Canids          | L   | 1.000      | -            | -                | -                | -         |    -8.63 | doc, gafolo, koala, pepe, rdnzao  |
|           67 |      970 | 2024-05-17 | ODDIK               | L   | 1.000      | -            | -                | -                | -         |   -18.57 | doc, drg, gafolo, rdnzao, togs    |
|           66 |     1048 | 2024-05-16 | w7m esports         | W   | 1.000      | -            | -                | -                | 0 (0.000) |     6.72 | doc, gafolo, pepe, rdnzao, togs   |
|           65 |     1051 | 2024-05-16 | w7m esports         | W   | 1.000      | -            | -                | -                | 0 (0.000) |     7.14 | doc, gafolo, pepe, rdnzao, togs   |
|           64 |     1072 | 2024-05-16 | Hype Esports        | W   | 1.000      | -            | -                | -                | 0 (0.000) |     5.47 | doc, drg, gafolo, rdnzao, togs    |
|           63 |     1135 | 2024-05-15 | Vikings KR          | W   | 1.000      | -            | -                | -                | 0 (0.000) |     6.83 | doc, drg, gafolo, rdnzao, togs    |
|           62 |     1143 | 2024-05-15 | 9z Team             | L   | 1.000      | -            | -                | -                | -         |    -4.72 | doc, drg, gafolo, rdnzao, togs    |
|           61 |     1250 | 2024-05-14 | Fluxo               | L   | 1.000      | -            | -                | -                | -         |    -9.15 | doc, drg, gafolo, rdnzao, togs    |
|           60 |     1310 | 2024-05-13 | RED Canids          | W   | 1.000      | 0.384        | 0.076 (0.029)    | 0.536 (0.206)    | 0 (0.000) |    20.29 | doc, drg, gafolo, rdnzao, togs    |
|           59 |     1428 | 2024-05-11 | w7m esports         | W   | 1.000      | -            | -                | -                | 0 (0.000) |     8.31 | doc, drg, gafolo, rdnzao, togs    |
|           58 |     1562 | 2024-05-09 | BESTIA              | L   | 1.000      | -            | -                | -                | -         |   -18.71 | doc, drg, gafolo, rdnzao, togs    |
|           57 |     1612 | 2024-05-08 | 9z Team             | L   | 1.000      | -            | -                | -                | -         |    -5.14 | doc, drg, gafolo, rdnzao, togs    |
|           56 |     1723 | 2024-05-06 | BESTIA              | W   | 1.000      | 0.435        | 0.026 (0.011)    | 0.500 (0.217)    | 0 (0.000) |    11.87 | doc, drg, gafolo, rdnzao, togs    |
|           55 |     3217 | 2024-04-10 | ODDIK               | W   | 0.872      | 0.450        | -                | 0.494 (0.194)    | -         |    12.19 | doc, pepe, rdnzao, supLexN1, togs |
|           54 |     3221 | 2024-04-10 | ODDIK               | L   | 0.872      | -            | -                | -                | -         |   -15.54 | doc, pepe, rdnzao, supLexN1, togs |
|           53 |     3558 | 2024-04-04 | paiN Gaming         | L   | 0.832      | -            | -                | -                | -         |    -0.73 | doc, pepe, rdnzao, supLexN1, togs |
|           52 |     3561 | 2024-04-04 | paiN Gaming         | L   | 0.832      | -            | -                | -                | -         |    -0.74 | doc, pepe, rdnzao, supLexN1, togs |
|           51 |     3617 | 2024-04-03 | 2Game Esports       | W   | 0.825      | -            | -                | -                | -         |     4.39 | doc, pepe, rdnzao, supLexN1, togs |
|           50 |     3618 | 2024-04-03 | 2Game Esports       | W   | 0.825      | -            | -                | -                | -         |     4.57 | doc, pepe, rdnzao, supLexN1, togs |
|           49 |     4518 | 2024-03-14 | MIBR                | L   | 0.693      | -            | -                | -                | -         |    -0.81 | doc, drg, pepe, rdnzao, togs      |
|           48 |     4519 | 2024-03-14 | MIBR                | L   | 0.692      | -            | -                | -                | -         |    -0.82 | doc, drg, pepe, rdnzao, togs      |
|           47 |     4574 | 2024-03-13 | Yawara E-Sports     | W   | 0.685      | -            | -                | -                | -         |     4.47 | doc, drg, gafolo, rdnzao, togs    |
|           46 |     4579 | 2024-03-13 | ODDIK               | W   | 0.685      | -            | -                | -                | -         |    10.99 | doc, drg, gafolo, rdnzao, togs    |
|           45 |     4660 | 2024-03-12 | 2Game Esports       | W   | 0.679      | -            | -                | -                | -         |     4.62 | doc, drg, gafolo, rdnzao, togs    |
|           44 |     4746 | 2024-03-11 | Fluxo               | L   | 0.670      | -            | -                | -                | -         |    -8.29 | doc, drg, gafolo, rdnzao, togs    |
|           43 |     4815 | 2024-03-09 | Case Esports        | L   | 0.658      | -            | -                | -                | -         |   -13.02 | doc, drg, gafolo, rdnzao, togs    |
|           42 |     4951 | 2024-03-07 | Corinthians Esports | W   | 0.643      | -            | -                | -                | -         |     3.51 | doc, drg, gafolo, rdnzao, togs    |
|           41 |     5083 | 2024-03-05 | Team Solid          | W   | 0.631      | 0.450        | 0.062 (0.018)    | -                | -         |     7.77 | doc, drg, pepe, rdnzao, togs      |
|           40 |     5093 | 2024-03-05 | Team Solid          | W   | 0.631      | 0.450        | 0.062 (0.018)    | -                | -         |     8.19 | doc, drg, pepe, rdnzao, togs      |
|           39 |     5637 | 2024-02-24 | Galorys             | W   | 0.566      | 0.450        | -                | 0.600 (0.153)    | -         |     5.66 | doc, drg, pepe, rdnzao, togs      |
|           38 |     5646 | 2024-02-24 | Galorys             | W   | 0.566      | 0.450        | -                | 0.600 (0.153)    | -         |     5.92 | doc, drg, pepe, rdnzao, togs      |
|           37 |     5665 | 2024-02-24 | Fluxo               | L   | 0.565      | -            | -                | -                | -         |    -7.11 | doc, drg, gafolo, rdnzao, togs    |
|           36 |     5847 | 2024-02-21 | Corinthians Esports | W   | 0.546      | -            | -                | -                | -         |     3.28 | doc, drg, pepe, rdnzao, togs      |
|           35 |     5851 | 2024-02-21 | Case Esports        | W   | 0.545      | -            | -                | -                | -         |     7.82 | doc, drg, gafolo, rdnzao, togs    |
|           34 |     5874 | 2024-02-21 | Galorys             | W   | 0.544      | -            | -                | -                | -         |     6.55 | doc, drg, gafolo, rdnzao, togs    |
|           33 |     5916 | 2024-02-20 | Flamengo Esports    | L   | 0.538      | -            | -                | -                | -         |   -15.08 | doc, drg, gafolo, rdnzao, togs    |
|           32 |     5936 | 2024-02-20 | Case Esports        | W   | 0.537      | -            | -                | -                | -         |     7.74 | doc, drg, gafolo, rdnzao, togs    |
|           31 |     5976 | 2024-02-19 | Yawara E-Sports     | W   | 0.533      | -            | -                | -                | -         |     4.07 | doc, drg, gafolo, rdnzao, togs    |
|           30 |     5999 | 2024-02-19 | Team Solid          | W   | 0.531      | 0.303        | 0.062 (0.010)    | -                | -         |     7.50 | doc, drg, gafolo, rdnzao, togs    |
|           29 |     6028 | 2024-02-18 | Galorys             | W   | 0.526      | 0.435        | -                | 0.600 (0.137)    | -         |     7.06 | doc, drg, gafolo, rdnzao, togs    |
|           28 |     6092 | 2024-02-17 | w7m esports         | L   | 0.519      | -            | -                | -                | -         |    -9.92 | doc, drg, gafolo, rdnzao, togs    |
|           27 |     6099 | 2024-02-17 | Galorys             | L   | 0.518      | -            | -                | -                | -         |   -10.03 | doc, drg, gafolo, rdnzao, togs    |
|           26 |     6159 | 2024-02-16 | w7m esports         | W   | 0.510      | -            | -                | -                | -         |     6.19 | doc, drg, gafolo, rdnzao, togs    |
|           25 |     6199 | 2024-02-15 | Case Esports        | L   | 0.505      | -            | -                | -                | -         |    -8.74 | doc, drg, gafolo, rdnzao, togs    |
|           24 |     6212 | 2024-02-15 | Fluxo               | L   | 0.504      | -            | -                | -                | -         |    -6.81 | doc, drg, pepe, rdnzao, togs      |
|           23 |     6216 | 2024-02-15 | Fluxo               | L   | 0.504      | -            | -                | -                | -         |    -7.11 | doc, drg, pepe, rdnzao, togs      |
|           22 |     6263 | 2024-02-14 | Hype Esports        | W   | 0.499      | -            | -                | -                | -         |     1.35 | doc, drg, gafolo, rdnzao, togs    |
|           21 |     6279 | 2024-02-14 | Galorys             | W   | 0.497      | 0.435        | -                | 0.600 (0.130)    | -         |     5.70 | doc, drg, gafolo, rdnzao, togs    |
|           20 |     7064 | 2024-01-28 | w7m esports         | L   | 0.385      | -            | -                | -                | -         |    -8.33 | doc, drg, gafolo, rdnzao, togs    |
|           19 |     7070 | 2024-01-28 | Fluxo               | W   | 0.385      | -            | -                | -                | -         |     6.72 | doc, drg, gafolo, rdnzao, togs    |
|           18 |     7118 | 2024-01-27 | 2024                | W   | 0.379      | -            | -                | -                | -         |     0.59 | doc, drg, gafolo, rdnzao, togs    |
|           17 |     7295 | 2024-01-25 | Galorys             | L   | 0.366      | -            | -                | -                | -         |    -7.40 | doc, drg, gafolo, rdnzao, togs    |
|           16 |     7331 | 2024-01-24 | paiN Gaming         | W   | 0.359      | 0.143        | 0.463 (0.024)    | -                | -         |    11.06 | doc, drg, gafolo, rdnzao, togs    |
|           15 |     7403 | 2024-01-23 | adalYamigos         | W   | 0.352      | -            | -                | -                | -         |     2.17 | doc, drg, gafolo, rdnzao, togs    |
|           14 |     7445 | 2024-01-22 | Legacy              | W   | 0.346      | -            | -                | -                | -         |     7.24 | doc, drg, gafolo, rdnzao, togs    |
|           13 |     7512 | 2024-01-21 | 9z Team             | L   | 0.337      | -            | -                | -                | -         |    -1.27 | doc, drg, gafolo, rdnzao, togs    |
|           12 |     7561 | 2024-01-20 | paiN Gaming         | L   | 0.331      | -            | -                | -                | -         |    -0.20 | doc, drg, gafolo, rdnzao, togs    |
|           11 |     7626 | 2024-01-19 | Galorys             | W   | 0.326      | -            | -                | -                | -         |     4.10 | doc, drg, gafolo, rdnzao, togs    |
|           10 |     7633 | 2024-01-19 | TIMACETA            | L   | 0.325      | -            | -                | -                | -         |    -8.41 | doc, drg, gafolo, rdnzao, togs    |
|            9 |     7702 | 2024-01-18 | MIBR                | L   | 0.318      | -            | -                | -                | -         |    -0.21 | doc, drg, gafolo, rdnzao, togs    |
|            8 |     7756 | 2024-01-17 | RED Canids          | W   | 0.312      | -            | -                | -                | -         |     6.13 | doc, drg, gafolo, rdnzao, togs    |
|            7 |     7790 | 2024-01-17 | MIBR                | L   | 0.311      | -            | -                | -                | -         |    -0.19 | doc, drg, gafolo, rdnzao, togs    |
|            6 |     7997 | 2024-01-14 | paiN Gaming         | W   | 0.292      | 0.143        | 0.463 (0.019)    | -                | -         |     9.07 | doc, drg, gafolo, rdnzao, togs    |
|            5 |     7998 | 2024-01-14 | BESTIA              | W   | 0.292      | -            | -                | -                | -         |     5.32 | doc, drg, gafolo, rdnzao, togs    |
|            4 |     8001 | 2024-01-14 | Corinthians Esports | W   | 0.292      | -            | -                | -                | -         |     1.70 | doc, drg, gafolo, rdnzao, togs    |
|            3 |     8026 | 2024-01-13 | Galorys             | W   | 0.286      | -            | -                | -                | -         |     3.89 | doc, drg, gafolo, rdnzao, togs    |
|            2 |     9641 | 2023-12-03 | Case Esports        | W   | 0.011      | -            | -                | -                | -         |     0.08 | doc, drg, gafolo, rdnzao, togs    |
|            1 |     9712 | 2023-12-02 | w7m esports         | W   | 0.006      | -            | -                | -                | -         |     0.06 | doc, drg, gafolo, rdnzao, togs    |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($5,753.91)
- Divide that value by the 5th highest value among all rosters ($300,806.11)
- The final value (0.02) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-05-19 |      1.000 | $980.02        | $980.02         |
| 2024-02-25 |      0.571 | $5,000.00      | $2,856.94       |
| 2024-02-21 |      0.544 | $3,500.00      | $1,902.64       |
| 2023-12-03 |      0.011 | $1,320.30      | $14.30          |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
