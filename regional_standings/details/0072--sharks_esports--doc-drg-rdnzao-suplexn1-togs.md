### Roster Details<br />
Team Name: Sharks Esports<br />
Roster: doc, drg, rdnzao, supLexN1, togs<br />
Region: [Americas]( ../standings_americas.md)<br />
<br />
Global Rank: [72](../standings_global.md)<br />
Regional Rank: [12]( ../standings_americas.md)<br />
Final Rank Value:  913.1<br />
<br />
Final Rank Value (913.1) = Starting Rank Value (890.9) + Head To Head Adjustments (22.2)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.454[<sup>1</sup>](#table2)
- Bounty Collected: 0.377[<sup>2</sup>](#table1)
- Opponent Network: 0.159[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.247<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 890.9
- 400 + ( ( 0.247 - 0.000 ) / ( 0.806 - 0.000 ) ) * 1600 = 890.9


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent            | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins      | H2H Adj. | Roster                           |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           61 |      415 | 2024-04-26 | TYLOO               | L   | 1.000      | -            | -                | -                | -             |   -11.01 | doc, drg, rdnzao, supLexN1, togs |
|           60 |      478 | 2024-04-25 | M80                 | L   | 1.000      | -            | -                | -                | -             |    -3.83 | doc, drg, rdnzao, supLexN1, togs |
|           59 |      580 | 2024-04-23 | Team Vitality       | L   | 1.000      | -            | -                | -                | -             |    -0.16 | doc, drg, rdnzao, supLexN1, togs |
|           58 |     1134 | 2024-04-12 | Galorys             | L   | 1.000      | -            | -                | -                | -             |   -18.84 | doc, drg, rdnzao, supLexN1, togs |
|           57 |     1200 | 2024-04-10 | ODDIK               | W   | 1.000      | 0.450        | -                | 0.402 (0.181)    | false (0.000) |    12.95 | doc, drg, gafolo, rdnzao, togs   |
|           56 |     1203 | 2024-04-10 | ODDIK               | L   | 1.000      | -            | -                | -                | -             |   -18.80 | doc, drg, gafolo, rdnzao, togs   |
|           55 |     1368 | 2024-04-07 | BESTIA              | W   | 1.000      | 0.435        | 0.026 (0.011)    | 0.423 (0.184)    | false (0.000) |    11.39 | doc, drg, rdnzao, supLexN1, togs |
|           54 |     1390 | 2024-04-06 | ODDIK               | W   | 1.000      | -            | -                | -                | false (0.000) |    14.19 | doc, drg, rdnzao, supLexN1, togs |
|           53 |     1517 | 2024-04-03 | 2Game Esports       | W   | 0.987      | -            | -                | -                | false (0.000) |     4.60 | doc, drg, gafolo, rdnzao, togs   |
|           52 |     1518 | 2024-04-03 | 2Game Esports       | W   | 0.986      | -            | -                | -                | false (0.000) |     4.81 | doc, drg, gafolo, rdnzao, togs   |
|           51 |     1565 | 2024-04-02 | BESTIA              | L   | 0.980      | -            | -                | -                | -             |   -19.67 | doc, drg, rdnzao, supLexN1, togs |
|           50 |     1569 | 2024-04-02 | MIBR                | L   | 0.979      | -            | -                | -                | -             |    -0.94 | doc, drg, rdnzao, supLexN1, togs |
|           49 |     2243 | 2024-03-14 | MIBR                | L   | 0.854      | -            | -                | -                | -             |    -0.84 | doc, drg, gafolo, rdnzao, togs   |
|           48 |     2245 | 2024-03-14 | MIBR                | L   | 0.853      | -            | -                | -                | -             |    -0.84 | doc, drg, gafolo, rdnzao, togs   |
|           47 |     2294 | 2024-03-13 | Yawara E-Sports     | W   | 0.846      | -            | -                | -                | false (0.000) |     5.80 | doc, drg, gafolo, rdnzao, togs   |
|           46 |     2298 | 2024-03-13 | ODDIK               | W   | 0.846      | -            | -                | -                | false (0.000) |    12.65 | doc, drg, gafolo, rdnzao, togs   |
|           45 |     2358 | 2024-03-12 | 2Game Esports       | W   | 0.840      | -            | -                | -                | false (0.000) |     4.19 | doc, drg, gafolo, rdnzao, togs   |
|           44 |     2428 | 2024-03-11 | Fluxo               | L   | 0.831      | -            | -                | -                | -             |   -10.18 | doc, drg, gafolo, rdnzao, togs   |
|           43 |     2478 | 2024-03-09 | Case Esports        | L   | 0.819      | -            | -                | -                | -             |   -17.49 | doc, drg, gafolo, rdnzao, togs   |
|           42 |     2580 | 2024-03-07 | Corinthians Esports | W   | 0.804      | 0.435        | -                | 0.346 (0.121)    | false (0.000) |     4.35 | doc, drg, gafolo, rdnzao, togs   |
|           41 |     2680 | 2024-03-05 | Team Solid          | W   | 0.792      | 0.450        | 0.138 (0.049)    | -                | false (0.000) |     8.46 | doc, drg, gafolo, rdnzao, togs   |
|           40 |     2689 | 2024-03-05 | Team Solid          | W   | 0.792      | 0.450        | 0.138 (0.049)    | -                | -             |     9.01 | doc, drg, gafolo, rdnzao, togs   |
|           39 |     3118 | 2024-02-24 | Galorys             | W   | 0.727      | 0.450        | 0.048 (0.016)    | 0.598 (0.196)    | -             |     7.66 | doc, drg, gafolo, rdnzao, togs   |
|           38 |     3125 | 2024-02-24 | Galorys             | W   | 0.727      | 0.450        | 0.048 (0.016)    | 0.598 (0.195)    | -             |     8.12 | doc, drg, gafolo, rdnzao, togs   |
|           37 |     3138 | 2024-02-24 | Fluxo               | L   | 0.726      | -            | -                | -                | -             |    -8.98 | doc, drg, gafolo, rdnzao, togs   |
|           36 |     3280 | 2024-02-21 | Corinthians Esports | W   | 0.707      | 0.450        | -                | 0.346 (0.110)    | -             |     4.81 | doc, drg, gafolo, rdnzao, togs   |
|           35 |     3285 | 2024-02-21 | Case Esports        | W   | 0.706      | 0.435        | -                | 0.401 (0.123)    | -             |     8.79 | doc, drg, gafolo, rdnzao, togs   |
|           34 |     3305 | 2024-02-21 | Galorys             | W   | 0.705      | 0.303        | 0.048 (0.010)    | 0.598 (0.128)    | -             |     9.20 | doc, drg, gafolo, rdnzao, togs   |
|           33 |     3338 | 2024-02-20 | Flamengo Esports    | L   | 0.699      | -            | -                | -                | -             |   -19.23 | doc, drg, gafolo, rdnzao, togs   |
|           32 |     3356 | 2024-02-20 | Case Esports        | W   | 0.698      | -            | -                | -                | -             |     9.13 | doc, drg, gafolo, rdnzao, togs   |
|           31 |     3387 | 2024-02-19 | Yawara E-Sports     | W   | 0.694      | -            | -                | -                | -             |     6.19 | doc, drg, gafolo, rdnzao, togs   |
|           30 |     3406 | 2024-02-19 | Team Solid          | W   | 0.692      | 0.303        | 0.138 (0.029)    | -                | -             |     8.81 | doc, drg, gafolo, rdnzao, togs   |
|           29 |     3433 | 2024-02-18 | Galorys             | W   | 0.687      | 0.435        | 0.048 (0.014)    | 0.598 (0.178)    | -             |    10.26 | doc, drg, gafolo, rdnzao, togs   |
|           28 |     3482 | 2024-02-17 | Galorys             | L   | 0.679      | -            | -                | -                | -             |   -11.82 | doc, drg, gafolo, rdnzao, togs   |
|           27 |     3566 | 2024-02-15 | Case Esports        | L   | 0.666      | -            | -                | -                | -             |   -12.09 | doc, drg, gafolo, rdnzao, togs   |
|           26 |     3576 | 2024-02-15 | Fluxo               | L   | 0.665      | -            | -                | -                | -             |    -7.87 | doc, drg, gafolo, rdnzao, togs   |
|           25 |     3579 | 2024-02-15 | Fluxo               | L   | 0.665      | -            | -                | -                | -             |    -8.32 | doc, drg, gafolo, rdnzao, togs   |
|           24 |     3626 | 2024-02-14 | Galorys             | W   | 0.658      | 0.435        | 0.048 (0.014)    | 0.598 (0.171)    | -             |     8.14 | doc, drg, gafolo, rdnzao, togs   |
|           23 |     4208 | 2024-01-28 | Fluxo               | W   | 0.546      | 0.143        | 0.153 (0.012)    | -                | -             |    10.74 | doc, drg, gafolo, rdnzao, togs   |
|           22 |     4239 | 2024-01-27 | 2024                | W   | 0.540      | -            | -                | -                | -             |     0.97 | doc, drg, gafolo, rdnzao, togs   |
|           21 |     4346 | 2024-01-25 | Galorys             | L   | 0.527      | -            | -                | -                | -             |    -9.66 | doc, drg, gafolo, rdnzao, togs   |
|           20 |     4451 | 2024-01-22 | Legacy              | W   | 0.507      | -            | -                | -                | -             |    12.15 | doc, drg, gafolo, rdnzao, togs   |
|           19 |     4501 | 2024-01-21 | 9z Team             | L   | 0.498      | -            | -                | -                | -             |    -6.70 | doc, drg, gafolo, rdnzao, togs   |
|           18 |     4584 | 2024-01-19 | Galorys             | W   | 0.487      | -            | -                | -                | -             |     7.02 | doc, drg, gafolo, rdnzao, togs   |
|           17 |     4589 | 2024-01-19 | TIMACETA            | L   | 0.487      | -            | -                | -                | -             |   -11.79 | doc, drg, gafolo, rdnzao, togs   |
|           16 |     4642 | 2024-01-18 | MIBR                | L   | 0.479      | -            | -                | -                | -             |    -0.23 | doc, drg, gafolo, rdnzao, togs   |
|           15 |     4688 | 2024-01-17 | RED Canids          | W   | 0.473      | -            | -                | -                | -             |     8.17 | doc, drg, gafolo, rdnzao, togs   |
|           14 |     4718 | 2024-01-17 | MIBR                | L   | 0.472      | -            | -                | -                | -             |    -0.20 | doc, drg, gafolo, rdnzao, togs   |
|           13 |     4864 | 2024-01-14 | BESTIA              | W   | 0.453      | -            | -                | -                | -             |     5.64 | doc, drg, gafolo, rdnzao, togs   |
|           12 |     4865 | 2024-01-14 | Patins da Ferrari   | W   | 0.453      | -            | -                | -                | -             |     2.57 | doc, drg, gafolo, rdnzao, togs   |
|           11 |     4879 | 2024-01-13 | Galorys             | W   | 0.447      | -            | -                | -                | -             |     6.86 | doc, drg, gafolo, rdnzao, togs   |
|           10 |     6033 | 2023-12-03 | Case Esports        | W   | 0.172      | -            | -                | -                | -             |     1.56 | doc, drg, gafolo, rdnzao, togs   |
|            9 |     6188 | 2023-11-30 | 9z Academy          | L   | 0.153      | -            | -                | -                | -             |    -3.76 | doc, drg, gafolo, rdnzao, togs   |
|            8 |     6235 | 2023-11-29 | Corinthians Esports | L   | 0.146      | -            | -                | -                | -             |    -3.76 | doc, drg, gafolo, rdnzao, togs   |
|            7 |     6308 | 2023-11-28 | Corinthians Esports | W   | 0.139      | -            | -                | -                | -             |     0.79 | doc, drg, gafolo, rdnzao, togs   |
|            6 |     6430 | 2023-11-25 | Fluxo               | L   | 0.118      | -            | -                | -                | -             |    -1.15 | doc, drg, gafolo, rdnzao, togs   |
|            5 |     6466 | 2023-11-24 | Imperial Esports    | L   | 0.112      | -            | -                | -                | -             |    -0.07 | doc, drg, gafolo, rdnzao, togs   |
|            4 |     6521 | 2023-11-23 | Patins da Ferrari   | W   | 0.104      | -            | -                | -                | -             |     0.58 | doc, drg, gafolo, rdnzao, togs   |
|            3 |     6629 | 2023-11-20 | RED Canids          | L   | 0.085      | -            | -                | -                | -             |    -1.24 | doc, drg, gafolo, rdnzao, togs   |
|            2 |     6759 | 2023-11-17 | Flamengo Esports    | W   | 0.066      | -            | -                | -                | -             |     0.25 | doc, drg, gafolo, rdnzao, togs   |
|            1 |     6861 | 2023-11-15 | Team Solid          | W   | 0.053      | -            | -                | -                | -             |     0.83 | doc, drg, gafolo, rdnzao, togs   |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($9,983.44)
- Divide that value by the 5th highest value among all rosters ($158,437.64)
- The final value (0.06) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-05-05 |      1.000 | $3,500.00      | $3,500.00       |
| 2024-02-25 |      0.732 | $5,000.00      | $3,662.27       |
| 2024-02-21 |      0.705 | $3,500.00      | $2,466.37       |
| 2023-12-03 |      0.172 | $1,320.30      | $226.96         |
| 2023-11-20 |      0.085 | $1,500.00      | $127.85         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
