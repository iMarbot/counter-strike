### Roster Details<br />
Team Name: Imperial Esports<br />
Roster: decenty, felps, HEN1, noway, VINI<br />
Region: [Americas]( ../standings_americas.md)<br />
<br />
Global Rank: [19](../standings_global.md)<br />
Regional Rank: [4]( ../standings_americas.md)<br />
Final Rank Value:  1441.6<br />
<br />
Final Rank Value (1441.6) = Starting Rank Value (1595.1) + Head To Head Adjustments (-153.5)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.854[<sup>1</sup>](#table2)
- Bounty Collected: 0.545[<sup>2</sup>](#table1)
- Opponent Network: 0.308[<sup>2</sup>](#table1)
- LAN Wins: 0.703[<sup>2</sup>](#table1)

The average of these factors is 0.602<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1595.1
- 400 + ( ( 0.602 - 0.000 ) / ( 0.806 - 0.000 ) ) * 1600 = 1595.1


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
|           60 |      433 | 2024-04-26 | SAW                 | L   | 1.000      | -            | -                | -                | -         |   -16.05 | decenty, felps, HEN1, noway, VINI |
|           59 |      526 | 2024-04-24 | Eternal Fire        | L   | 1.000      | -            | -                | -                | -         |    -4.97 | decenty, felps, HEN1, noway, VINI |
|           58 |      567 | 2024-04-23 | FaZe Clan           | L   | 1.000      | -            | -                | -                | -         |    -1.96 | decenty, felps, HEN1, noway, VINI |
|           57 |      857 | 2024-04-18 | MIBR                | L   | 1.000      | -            | -                | -                | -         |   -11.09 | decenty, felps, HEN1, noway, VINI |
|           56 |      860 | 2024-04-18 | 9z Team             | W   | 1.000      | 0.589        | 0.057 (0.033)    | 0.376 (0.221)    | 1 (1.000) |     2.45 | decenty, felps, HEN1, noway, VINI |
|           55 |      864 | 2024-04-18 | Fluxo               | W   | 1.000      | 0.143        | 0.153 (0.022)    | -                | 0 (0.000) |     2.97 | decenty, felps, HEN1, noway, VINI |
|           54 |      873 | 2024-04-18 | Metizport           | W   | 1.000      | 0.589        | 0.188 (0.111)    | 1.000 (0.589)    | 1 (1.000) |     3.80 | decenty, felps, HEN1, noway, VINI |
|           53 |     1031 | 2024-04-15 | MIBR                | L   | 1.000      | -            | -                | -                | -         |   -12.07 | decenty, felps, HEN1, noway, VINI |
|           52 |     1087 | 2024-04-13 | RED Canids          | W   | 1.000      | 0.435        | 0.108 (0.047)    | 0.532 (0.231)    | 0 (0.000) |     2.19 | decenty, felps, HEN1, noway, VINI |
|           51 |     1204 | 2024-04-10 | Fluxo               | L   | 1.000      | -            | -                | -                | -         |   -28.91 | decenty, felps, HEN1, noway, VINI |
|           50 |     1205 | 2024-04-10 | Fluxo               | W   | 1.000      | 0.450        | 0.153 (0.069)    | 0.484 (0.218)    | 0 (0.000) |     2.28 | decenty, felps, HEN1, noway, VINI |
|           49 |     1228 | 2024-04-10 | MIBR                | L   | 1.000      | -            | -                | -                | -         |   -14.36 | decenty, felps, HEN1, noway, VINI |
|           48 |     1362 | 2024-04-07 | RED Canids          | W   | 1.000      | -            | -                | -                | -         |     1.71 | decenty, felps, HEN1, noway, VINI |
|           47 |     1363 | 2024-04-07 | FURIA Academy       | W   | 1.000      | -            | -                | -                | -         |     0.24 | decenty, felps, HEN1, noway, VINI |
|           46 |     1465 | 2024-04-04 | ODDIK               | W   | 0.993      | -            | -                | -                | -         |     0.98 | decenty, felps, HEN1, noway, VINI |
|           45 |     1467 | 2024-04-04 | ODDIK               | W   | 0.993      | -            | -                | -                | -         |     0.99 | decenty, felps, HEN1, noway, VINI |
|           44 |     1477 | 2024-04-04 | BESTIA              | W   | 0.992      | -            | -                | -                | -         |     0.66 | decenty, felps, HEN1, noway, VINI |
|           43 |     1917 | 2024-03-23 | FaZe Clan           | L   | 0.910      | -            | -                | -                | -         |    -2.48 | decenty, felps, HEN1, noway, VINI |
|           42 |     1947 | 2024-03-22 | Team Vitality       | L   | 0.904      | -            | -                | -                | -         |    -3.56 | decenty, felps, HEN1, noway, VINI |
|           41 |     1959 | 2024-03-21 | Team Spirit         | L   | 0.899      | -            | -                | -                | -         |    -3.35 | decenty, felps, HEN1, noway, VINI |
|           40 |     1992 | 2024-03-21 | Virtus.pro          | W   | 0.897      | 1.000        | 0.454 (0.408)    | 0.416 (0.373)    | 1 (0.897) |    22.02 | decenty, felps, HEN1, noway, VINI |
|           39 |     2030 | 2024-03-20 | GamerLegion         | W   | 0.891      | 1.000        | 0.194 (0.173)    | 0.419 (0.373)    | 1 (0.891) |    14.90 | decenty, felps, HEN1, noway, VINI |
|           38 |     2058 | 2024-03-19 | Gaimin Gladiators   | L   | 0.885      | -            | -                | -                | -         |   -18.80 | decenty, felps, HEN1, noway, VINI |
|           37 |     2103 | 2024-03-18 | Apeks               | W   | 0.877      | 1.000        | 0.253 (0.222)    | 0.459 (0.403)    | 1 (0.877) |     9.34 | decenty, felps, HEN1, noway, VINI |
|           36 |     2127 | 2024-03-17 | HEROIC              | L   | 0.872      | -            | -                | -                | -         |    -7.34 | decenty, felps, HEN1, noway, VINI |
|           35 |     2148 | 2024-03-17 | ENCE                | W   | 0.871      | 1.000        | 0.377 (0.329)    | 0.352 (0.306)    | 1 (0.871) |    15.05 | decenty, felps, HEN1, noway, VINI |
|           34 |     2553 | 2024-03-07 | Monte               | L   | 0.806      | -            | -                | -                | -         |   -16.28 | decenty, felps, HEN1, noway, VINI |
|           33 |     2872 | 2024-03-02 | M80                 | W   | 0.772      | -            | -                | -                | 1 (0.772) |     5.39 | decenty, felps, HEN1, noway, VINI |
|           32 |     3092 | 2024-02-25 | Fluxo               | L   | 0.732      | -            | -                | -                | -         |   -21.80 | decenty, felps, HEN1, noway, VINI |
|           31 |     3152 | 2024-02-24 | BESTIA              | W   | 0.725      | -            | -                | -                | -         |     0.51 | decenty, felps, HEN1, noway, VINI |
|           30 |     3229 | 2024-02-22 | BESTIA              | L   | 0.713      | -            | -                | -                | -         |   -22.03 | decenty, felps, HEN1, noway, VINI |
|           29 |     3237 | 2024-02-22 | FURIA Esports       | L   | 0.712      | -            | -                | -                | -         |    -9.52 | decenty, felps, HEN1, noway, VINI |
|           28 |     3279 | 2024-02-21 | 2Game Esports       | W   | 0.707      | -            | -                | -                | -         |     0.10 | decenty, felps, HEN1, noway, VINI |
|           27 |     3282 | 2024-02-21 | 2Game Esports       | W   | 0.707      | -            | -                | -                | -         |     0.10 | decenty, felps, HEN1, noway, VINI |
|           26 |     3318 | 2024-02-21 | LA RUGONETA         | W   | 0.704      | -            | -                | -                | -         |     0.10 | decenty, felps, HEN1, noway, VINI |
|           25 |     3523 | 2024-02-16 | Galorys             | W   | 0.672      | 0.450        | -                | 0.598 (0.181)    | -         |     0.38 | decenty, felps, HEN1, noway, VINI |
|           24 |     3528 | 2024-02-16 | Galorys             | W   | 0.672      | 0.450        | -                | 0.598 (0.181)    | -         |     0.38 | decenty, felps, HEN1, noway, VINI |
|           23 |     3563 | 2024-02-15 | 9z Team             | W   | 0.667      | -            | -                | -                | -         |     0.93 | decenty, felps, HEN1, noway, VINI |
|           22 |     3565 | 2024-02-15 | Fluxo               | W   | 0.666      | -            | -                | -                | -         |     0.95 | decenty, felps, HEN1, noway, VINI |
|           21 |     3613 | 2024-02-14 | Yawara E-Sports     | W   | 0.660      | -            | -                | -                | -         |     0.22 | decenty, felps, HEN1, noway, VINI |
|           20 |     3913 | 2024-02-04 | 9z Team             | W   | 0.593      | -            | -                | -                | -         |     0.79 | decenty, felps, HEN1, noway, VINI |
|           19 |     3942 | 2024-02-03 | MIBR                | W   | 0.586      | 0.143        | 0.654 (0.055)    | -                | -         |    11.58 | decenty, felps, HEN1, noway, VINI |
|           18 |     4004 | 2024-02-02 | BESTIA              | W   | 0.581      | -            | -                | -                | -         |     0.36 | decenty, felps, HEN1, noway, VINI |
|           17 |     4007 | 2024-02-02 | 9z Team             | L   | 0.580      | -            | -                | -                | -         |   -17.55 | decenty, felps, HEN1, noway, VINI |
|           16 |     4008 | 2024-02-02 | BESTIA              | W   | 0.580      | -            | -                | -                | -         |     0.31 | decenty, felps, HEN1, noway, VINI |
|           15 |     4207 | 2024-01-28 | LA RUGONETA         | W   | 0.546      | -            | -                | -                | -         |     0.07 | decenty, felps, HEN1, noway, VINI |
|           14 |     4348 | 2024-01-25 | Yawara E-Sports     | L   | 0.527      | -            | -                | -                | -         |   -16.46 | decenty, felps, HEN1, noway, VINI |
|           13 |     4373 | 2024-01-24 | 9z Team             | W   | 0.520      | -            | -                | -                | -         |     0.54 | decenty, felps, HEN1, noway, VINI |
|           12 |     4422 | 2024-01-23 | BESTIA              | W   | 0.513      | -            | -                | -                | -         |     0.25 | decenty, felps, HEN1, noway, VINI |
|           11 |     4538 | 2024-01-20 | Fluxo               | W   | 0.492      | -            | -                | -                | -         |     0.70 | decenty, felps, HEN1, noway, VINI |
|           10 |     4588 | 2024-01-19 | BESTIA              | L   | 0.487      | -            | -                | -                | -         |   -15.13 | decenty, felps, HEN1, noway, VINI |
|            9 |     4593 | 2024-01-19 | Galorys             | W   | 0.486      | -            | -                | -                | -         |     0.28 | decenty, felps, HEN1, noway, VINI |
|            8 |     4779 | 2024-01-16 | Legacy              | L   | 0.466      | -            | -                | -                | -         |   -13.81 | decenty, felps, HEN1, noway, VINI |
|            7 |     4827 | 2024-01-15 | Patins da Ferrari   | W   | 0.460      | -            | -                | -                | -         |     0.06 | decenty, felps, HEN1, noway, VINI |
|            6 |     6234 | 2023-11-29 | Corinthians Esports | W   | 0.146      | -            | -                | -                | -         |     0.02 | decenty, felps, HEN1, noway, VINI |
|            5 |     6295 | 2023-11-28 | Age Sports          | W   | 0.140      | -            | -                | -                | -         |     0.01 | decenty, felps, HEN1, noway, VINI |
|            4 |     6386 | 2023-11-26 | Fluxo               | W   | 0.125      | -            | -                | -                | -         |     0.17 | decenty, felps, HEN1, noway, VINI |
|            3 |     6413 | 2023-11-25 | Case Esports        | W   | 0.120      | -            | -                | -                | -         |     0.03 | decenty, felps, HEN1, noway, VINI |
|            2 |     6466 | 2023-11-24 | Sharks Esports      | W   | 0.112      | -            | -                | -                | -         |     0.07 | decenty, felps, HEN1, noway, VINI |
|            1 |     6498 | 2023-11-23 | Fluxo               | W   | 0.107      | -            | -                | -                | -         |     0.14 | decenty, felps, HEN1, noway, VINI |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($106,757.44)
- Divide that value by the 5th highest value among all rosters ($158,437.64)
- The final value (0.67) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-05-05 |      1.000 | $3,500.00      | $3,500.00       |
| 2024-04-20 |      1.000 | $50,000.00     | $50,000.00      |
| 2024-04-15 |      1.000 | $15,000.00     | $15,000.00      |
| 2024-03-31 |      0.965 | $20,000.00     | $19,304.63      |
| 2024-03-10 |      0.826 | $5,000.00      | $4,127.89       |
| 2024-02-25 |      0.732 | $15,000.00     | $10,986.81      |
| 2023-11-26 |      0.125 | $30,597.23     | $3,838.11       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
