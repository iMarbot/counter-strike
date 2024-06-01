### Roster Details<br />
Team Name: Case Esports<br />
Roster: nyezin, RCF, RICIOLI, urban0, yepz<br />
Region: [Americas]( ../standings_americas.md)<br />
<br />
Global Rank: [82](../standings_global.md)<br />
Regional Rank: [21]( ../standings_americas.md)<br />
Final Rank Value:  903.3<br />
<br />
Final Rank Value (903.3) = Starting Rank Value (861.8) + Head To Head Adjustments (41.5)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.393[<sup>1</sup>](#table2)
- Bounty Collected: 0.333[<sup>2</sup>](#table1)
- Opponent Network: 0.182[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.227<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 861.8
- 400 + ( ( 0.227 - 0.000 ) / ( 0.786 - 0.000 ) ) * 1600 = 861.8


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent            | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                             |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           75 |       23 | 2024-05-29 | Galorys             | W   | 1.000      | -            | -                | -                | 0 (0.000) |    13.41 | nyezin, RCF, RICIOLI, urban0, yepz |
|           74 |       37 | 2024-05-29 | Dusty Roots         | W   | 1.000      | 0.384        | -                | 0.425 (0.163)    | 0 (0.000) |     7.71 | nyezin, RCF, RICIOLI, urban0, yepz |
|           73 |      169 | 2024-05-27 | Hawks               | L   | 1.000      | -            | -                | -                | -         |   -25.39 | nyezin, RCF, RICIOLI, urban0, yepz |
|           72 |      432 | 2024-05-22 | Corinthians Esports | W   | 1.000      | -            | -                | -                | 0 (0.000) |    10.09 | nyezin, RCF, RICIOLI, urban0, yepz |
|           71 |      437 | 2024-05-22 | BESTIA              | L   | 1.000      | -            | -                | -                | -         |    -8.99 | nyezin, RCF, RICIOLI, urban0, yepz |
|           70 |      441 | 2024-05-22 | BESTIA              | L   | 1.000      | -            | -                | -                | -         |    -9.68 | nyezin, RCF, RICIOLI, urban0, yepz |
|           69 |      443 | 2024-05-22 | inSanitY Sports     | W   | 1.000      | -            | -                | -                | 0 (0.000) |     8.21 | nyezin, RCF, RICIOLI, urban0, yepz |
|           68 |      573 | 2024-05-21 | ODDIK               | W   | 1.000      | 0.303        | 0.017 (0.005)    | 0.494 (0.150)    | 0 (0.000) |    17.10 | nyezin, RCF, RICIOLI, urban0, yepz |
|           67 |      664 | 2024-05-20 | Galorys             | W   | 1.000      | 0.303        | 0.022 (0.007)    | 0.585 (0.177)    | 0 (0.000) |    14.19 | nyezin, RCF, RICIOLI, urban0, yepz |
|           66 |      725 | 2024-05-19 | ODDIK               | L   | 1.000      | -            | -                | -                | -         |   -13.63 | nyezin, RCF, RICIOLI, urban0, yepz |
|           65 |      828 | 2024-05-18 | Team Solid          | W   | 1.000      | 0.303        | 0.062 (0.019)    | -                | 0 (0.000) |    15.29 | nyezin, RCF, RICIOLI, urban0, yepz |
|           64 |      947 | 2024-05-17 | Fluxo               | L   | 1.000      | -            | -                | -                | -         |    -6.85 | nyezin, RCF, RICIOLI, urban0, yepz |
|           63 |      957 | 2024-05-17 | Hype Esports        | W   | 1.000      | -            | -                | -                | 0 (0.000) |     7.66 | nyezin, RCF, RICIOLI, urban0, yepz |
|           62 |     1061 | 2024-05-16 | KRÜ Esports         | W   | 1.000      | -            | -                | -                | 0 (0.000) |    15.28 | nyezin, RCF, RICIOLI, urban0, yepz |
|           61 |     1131 | 2024-05-15 | Corinthians Esports | W   | 1.000      | 0.450        | -                | 0.553 (0.249)    | 0 (0.000) |     9.43 | nyezin, RCF, RICIOLI, urban0, yepz |
|           60 |     1135 | 2024-05-15 | Corinthians Esports | W   | 1.000      | 0.450        | -                | 0.553 (0.249)    | -         |    10.17 | nyezin, RCF, RICIOLI, urban0, yepz |
|           59 |     1153 | 2024-05-15 | Galorys             | W   | 1.000      | -            | -                | -                | -         |    16.62 | nyezin, RCF, RICIOLI, urban0, yepz |
|           58 |     1228 | 2024-05-14 | Galorys             | W   | 1.000      | 0.450        | 0.022 (0.010)    | 0.585 (0.263)    | -         |    18.14 | nyezin, RCF, RICIOLI, urban0, yepz |
|           57 |     1235 | 2024-05-14 | Galorys             | L   | 1.000      | -            | -                | -                | -         |   -13.15 | nyezin, RCF, RICIOLI, urban0, yepz |
|           56 |     1266 | 2024-05-14 | Hype Esports        | L   | 1.000      | -            | -                | -                | -         |   -23.01 | nyezin, RCF, RICIOLI, urban0, yepz |
|           55 |     1302 | 2024-05-13 | Intense Game        | W   | 1.000      | -            | -                | -                | -         |    12.15 | nyezin, RCF, RICIOLI, urban0, yepz |
|           54 |     1442 | 2024-05-11 | Galorys             | L   | 1.000      | -            | -                | -                | -         |   -15.62 | nyezin, RCF, RICIOLI, urban0, yepz |
|           53 |     1602 | 2024-05-08 | Galorys             | W   | 1.000      | -            | -                | -                | -         |    16.85 | nyezin, RCF, RICIOLI, urban0, yepz |
|           52 |     1670 | 2024-05-07 | inSanitY Sports     | L   | 1.000      | -            | -                | -                | -         |   -22.22 | nyezin, RCF, RICIOLI, urban0, yepz |
|           51 |     1748 | 2024-05-05 | ODDIK               | L   | 1.000      | -            | -                | -                | -         |   -11.98 | nyezin, RCF, RICIOLI, urban0, yepz |
|           50 |     1902 | 2024-05-02 | ODDIK               | W   | 1.000      | 0.450        | 0.017 (0.008)    | 0.494 (0.222)    | -         |    19.86 | nyezin, RCF, RICIOLI, urban0, yepz |
|           49 |     1905 | 2024-05-02 | ODDIK               | L   | 1.000      | -            | -                | -                | -         |   -11.30 | nyezin, RCF, RICIOLI, urban0, yepz |
|           48 |     1944 | 2024-05-01 | Dusty Roots         | W   | 1.000      | -            | -                | -                | -         |     9.57 | nyezin, RCF, RICIOLI, urban0, yepz |
|           47 |     1951 | 2024-05-01 | 9z Team             | L   | 1.000      | -            | -                | -                | -         |    -3.08 | nyezin, RCF, RICIOLI, urban0, yepz |
|           46 |     1956 | 2024-05-01 | 9z Team             | L   | 1.000      | -            | -                | -                | -         |    -3.17 | nyezin, RCF, RICIOLI, urban0, yepz |
|           45 |     2812 | 2024-04-17 | MIBR                | L   | 0.918      | -            | -                | -                | -         |    -0.51 | RCF, RICIOLI, snow, urban0, yepz   |
|           44 |     2895 | 2024-04-16 | Galorys             | W   | 0.912      | -            | -                | -                | -         |    16.23 | RCF, RICIOLI, snow, urban0, yepz   |
|           43 |     3019 | 2024-04-13 | MIBR                | L   | 0.890      | -            | -                | -                | -         |    -0.48 | RCF, RICIOLI, snow, urban0, yepz   |
|           42 |     3060 | 2024-04-12 | adalYamigos         | W   | 0.885      | -            | -                | -                | -         |    11.26 | RCF, RICIOLI, snow, urban0, yepz   |
|           41 |     3127 | 2024-04-11 | FURIA Academy       | W   | 0.876      | -            | -                | -                | -         |     7.28 | RCF, RICIOLI, snow, urban0, yepz   |
|           40 |     3222 | 2024-04-09 | paiN Gaming         | L   | 0.865      | -            | -                | -                | -         |    -0.43 | RCF, RICIOLI, snow, urban0, yepz   |
|           39 |     3227 | 2024-04-09 | paiN Gaming         | L   | 0.865      | -            | -                | -                | -         |    -0.43 | RCF, RICIOLI, snow, urban0, yepz   |
|           38 |     3325 | 2024-04-07 | adalYamigos         | L   | 0.852      | -            | -                | -                | -         |   -16.03 | RCF, RICIOLI, snow, urban0, yepz   |
|           37 |     3529 | 2024-04-03 | Imperial Esports    | L   | 0.825      | -            | -                | -                | -         |    -0.64 | RCF, RICIOLI, snow, urban0, yepz   |
|           36 |     3532 | 2024-04-03 | Imperial Esports    | L   | 0.825      | -            | -                | -                | -         |    -0.64 | RCF, RICIOLI, snow, urban0, yepz   |
|           35 |     3771 | 2024-03-27 | MIBR                | L   | 0.779      | -            | -                | -                | -         |    -0.49 | RCF, RICIOLI, snow, urban0, yepz   |
|           34 |     3775 | 2024-03-27 | MIBR                | L   | 0.779      | -            | -                | -                | -         |    -0.50 | RCF, RICIOLI, snow, urban0, yepz   |
|           33 |     4258 | 2024-03-17 | ODDIK               | L   | 0.711      | -            | -                | -                | -         |    -8.11 | RCF, RICIOLI, snow, urban0, yepz   |
|           32 |     4310 | 2024-03-16 | MIBR Academy        | W   | 0.704      | -            | -                | -                | -         |     7.57 | RCF, RICIOLI, snow, urban0, yepz   |
|           31 |     4362 | 2024-03-15 | RED Canids          | L   | 0.698      | -            | -                | -                | -         |    -6.01 | RCF, RICIOLI, snow, urban0, yepz   |
|           30 |     4426 | 2024-03-14 | FURIA Academy       | W   | 0.691      | -            | -                | -                | -         |     4.44 | RCF, RICIOLI, snow, urban0, yepz   |
|           29 |     4467 | 2024-03-13 | RED Canids          | L   | 0.685      | -            | -                | -                | -         |    -5.75 | RCF, RICIOLI, snow, urban0, yepz   |
|           28 |     4475 | 2024-03-13 | Yawara E-Sports     | L   | 0.684      | -            | -                | -                | -         |   -15.29 | RCF, RICIOLI, snow, urban0, yepz   |
|           27 |     4497 | 2024-03-13 | ODDIK               | L   | 0.683      | -            | -                | -                | -         |    -8.53 | RCF, RICIOLI, snow, urban0, yepz   |
|           26 |     4537 | 2024-03-12 | inSanitY Sports     | W   | 0.679      | -            | -                | -                | -         |     2.38 | RCF, RICIOLI, snow, urban0, yepz   |
|           25 |     4563 | 2024-03-12 | LA RUGONETA         | W   | 0.676      | -            | -                | -                | -         |     4.03 | RCF, RICIOLI, snow, urban0, yepz   |
|           24 |     4643 | 2024-03-10 | FURIA Academy       | W   | 0.665      | -            | -                | -                | -         |     3.72 | RCF, RICIOLI, snow, urban0, yepz   |
|           23 |     4690 | 2024-03-09 | Sharks Esports      | W   | 0.658      | 0.435        | 0.031 (0.009)    | 0.365 (0.104)    | -         |    12.47 | RCF, RICIOLI, snow, urban0, yepz   |
|           22 |     4790 | 2024-03-07 | Fluxo               | W   | 0.645      | 0.435        | 0.065 (0.018)    | 0.474 (0.133)    | -         |    14.63 | RCF, RICIOLI, snow, urban0, yepz   |
|           21 |     4930 | 2024-03-05 | adalYamigos         | L   | 0.633      | -            | -                | -                | -         |   -13.16 | RCF, RICIOLI, snow, urban0, yepz   |
|           20 |     4931 | 2024-03-05 | adalYamigos         | L   | 0.632      | -            | -                | -                | -         |   -13.82 | RCF, RICIOLI, snow, urban0, yepz   |
|           19 |     4980 | 2024-03-04 | Fluxo               | L   | 0.626      | -            | -                | -                | -         |    -5.91 | RCF, RICIOLI, snow, urban0, yepz   |
|           18 |     4981 | 2024-03-04 | Fluxo               | L   | 0.626      | -            | -                | -                | -         |    -6.19 | RCF, RICIOLI, snow, urban0, yepz   |
|           17 |     5479 | 2024-02-24 | 2Game Esports       | W   | 0.566      | -            | -                | -                | -         |     5.13 | RCF, RICIOLI, snow, urban0, yepz   |
|           16 |     5487 | 2024-02-24 | 2Game Esports       | L   | 0.566      | -            | -                | -                | -         |   -13.00 | RCF, RICIOLI, snow, urban0, yepz   |
|           15 |     5675 | 2024-02-21 | Team Solid          | W   | 0.546      | 0.450        | 0.062 (0.015)    | -                | -         |     8.68 | RCF, RICIOLI, snow, urban0, yepz   |
|           14 |     5684 | 2024-02-21 | Team Solid          | L   | 0.546      | -            | -                | -                | -         |    -8.71 | RCF, RICIOLI, snow, urban0, yepz   |
|           13 |     5689 | 2024-02-21 | Sharks Esports      | L   | 0.545      | -            | -                | -                | -         |    -7.58 | RCF, RICIOLI, snow, urban0, yepz   |
|           12 |     5746 | 2024-02-20 | 9z Team             | L   | 0.539      | -            | -                | -                | -         |    -2.00 | RCF, RICIOLI, snow, urban0, yepz   |
|           11 |     5748 | 2024-02-20 | w7m esports         | W   | 0.538      | -            | -                | -                | -         |     7.45 | RCF, RICIOLI, snow, urban0, yepz   |
|           10 |     5768 | 2024-02-20 | Sharks Esports      | L   | 0.537      | -            | -                | -                | -         |    -7.49 | RCF, RICIOLI, snow, urban0, yepz   |
|            9 |     5808 | 2024-02-19 | LA RUGONETA         | W   | 0.533      | -            | -                | -                | -         |     2.67 | RCF, RICIOLI, snow, urban0, yepz   |
|            8 |     5863 | 2024-02-18 | Galorys             | L   | 0.525      | -            | -                | -                | -         |    -9.43 | RCF, RICIOLI, snow, urban0, yepz   |
|            7 |     5970 | 2024-02-16 | BESTIA              | W   | 0.512      | 0.435        | 0.026 (0.006)    | 0.477 (0.106)    | -         |     9.75 | RCF, RICIOLI, snow, urban0, yepz   |
|            6 |     6020 | 2024-02-15 | 9z Team             | L   | 0.505      | -            | -                | -                | -         |    -1.61 | RCF, RICIOLI, snow, urban0, yepz   |
|            5 |     6023 | 2024-02-15 | Sharks Esports      | W   | 0.505      | -            | -                | -                | -         |     9.02 | RCF, RICIOLI, snow, urban0, yepz   |
|            4 |     6048 | 2024-02-15 | Flamengo Esports    | W   | 0.503      | -            | -                | -                | -         |     2.10 | RCF, RICIOLI, snow, urban0, yepz   |
|            3 |     6074 | 2024-02-14 | O PLANO C           | W   | 0.499      | -            | -                | -                | -         |     1.02 | RCF, RICIOLI, snow, urban0, yepz   |
|            2 |     6148 | 2024-02-13 | Galorys             | W   | 0.491      | 0.303        | 0.022 (0.003)    | -                | -         |     7.00 | RCF, RICIOLI, snow, urban0, yepz   |
|            1 |     6200 | 2024-02-12 | Dusty Roots         | W   | 0.484      | -            | -                | -                | -         |     3.72 | RCF, RICIOLI, snow, urban0, yepz   |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($8,536.97)
- Divide that value by the 5th highest value among all rosters ($300,806.11)
- The final value (0.03) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-05-22 |      1.000 | $600.00        | $600.00         |
| 2024-05-21 |      1.000 | $3,500.00      | $3,500.00       |
| 2024-05-19 |      1.000 | $980.02        | $980.02         |
| 2024-03-14 |      0.691 | $5,000.00      | $3,456.94       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
