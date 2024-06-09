### Roster Details<br />
Team Name: Case Esports<br />
Roster: nyezin, RCF, RICIOLI, urban0, yepz<br />
Region: [Americas]( ../standings_americas.md)<br />
<br />
Global Rank: [88](../standings_global.md)<br />
Regional Rank: [21]( ../standings_americas.md)<br />
Final Rank Value:  897.2<br />
<br />
Final Rank Value (897.2) = Starting Rank Value (861.5) + Head To Head Adjustments (35.8)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.393[<sup>1</sup>](#table2)
- Bounty Collected: 0.334[<sup>2</sup>](#table1)
- Opponent Network: 0.181[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.227<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 861.5
- 400 + ( ( 0.227 - 0.000 ) / ( 0.787 - 0.000 ) ) * 1600 = 861.5


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
|           76 |       23 | 2024-05-29 | Galorys             | W   | 1.000      | -            | -                | -                | 0 (0.000) |    13.83 | nyezin, RCF, RICIOLI, urban0, yepz |
|           75 |       37 | 2024-05-29 | Dusty Roots         | W   | 1.000      | 0.384        | -                | 0.425 (0.163)    | 0 (0.000) |     8.30 | nyezin, RCF, RICIOLI, urban0, yepz |
|           74 |      177 | 2024-05-27 | Hawks               | L   | 1.000      | -            | -                | -                | -         |   -25.21 | nyezin, RCF, RICIOLI, urban0, yepz |
|           73 |      444 | 2024-05-22 | BESTIA              | L   | 1.000      | -            | -                | -                | -         |    -9.27 | nyezin, RCF, RICIOLI, urban0, yepz |
|           72 |      448 | 2024-05-22 | BESTIA              | L   | 1.000      | -            | -                | -                | -         |    -9.99 | nyezin, RCF, RICIOLI, urban0, yepz |
|           71 |      450 | 2024-05-22 | inSanitY Sports     | W   | 1.000      | -            | -                | -                | 0 (0.000) |     8.67 | nyezin, RCF, RICIOLI, urban0, yepz |
|           70 |      542 | 2024-05-21 | Sharks Esports      | W   | 1.000      | 0.450        | 0.019 (0.009)    | 0.381 (0.172)    | 0 (0.000) |    18.91 | nyezin, RCF, RICIOLI, urban0, yepz |
|           69 |      545 | 2024-05-21 | Sharks Esports      | L   | 1.000      | -            | -                | -                | -         |   -12.32 | nyezin, RCF, RICIOLI, urban0, yepz |
|           68 |      584 | 2024-05-21 | ODDIK               | W   | 1.000      | 0.303        | 0.017 (0.005)    | 0.494 (0.150)    | 0 (0.000) |    17.08 | nyezin, RCF, RICIOLI, urban0, yepz |
|           67 |      675 | 2024-05-20 | Galorys             | W   | 1.000      | 0.303        | 0.022 (0.007)    | 0.600 (0.182)    | 0 (0.000) |    14.51 | nyezin, RCF, RICIOLI, urban0, yepz |
|           66 |      737 | 2024-05-19 | ODDIK               | L   | 1.000      | -            | -                | -                | -         |   -13.64 | nyezin, RCF, RICIOLI, urban0, yepz |
|           65 |      840 | 2024-05-18 | Team Solid          | W   | 1.000      | 0.303        | 0.062 (0.019)    | -                | 0 (0.000) |    15.09 | nyezin, RCF, RICIOLI, urban0, yepz |
|           64 |      959 | 2024-05-17 | Fluxo               | L   | 1.000      | -            | -                | -                | -         |    -6.68 | nyezin, RCF, RICIOLI, urban0, yepz |
|           63 |      969 | 2024-05-17 | Hype Esports        | W   | 1.000      | -            | -                | -                | 0 (0.000) |     7.74 | nyezin, RCF, RICIOLI, urban0, yepz |
|           62 |     1071 | 2024-05-16 | KRÜ Esports         | W   | 1.000      | -            | -                | -                | 0 (0.000) |    15.34 | nyezin, RCF, RICIOLI, urban0, yepz |
|           61 |     1140 | 2024-05-15 | Corinthians Esports | W   | 1.000      | 0.450        | -                | 0.458 (0.206)    | 0 (0.000) |     8.02 | nyezin, RCF, RICIOLI, urban0, yepz |
|           60 |     1144 | 2024-05-15 | Corinthians Esports | W   | 1.000      | 0.450        | -                | 0.458 (0.206)    | -         |     8.58 | nyezin, RCF, RICIOLI, urban0, yepz |
|           59 |     1162 | 2024-05-15 | Galorys             | W   | 1.000      | -            | -                | -                | -         |    16.89 | nyezin, RCF, RICIOLI, urban0, yepz |
|           58 |     1238 | 2024-05-14 | Galorys             | W   | 1.000      | 0.450        | 0.022 (0.010)    | 0.600 (0.270)    | -         |    18.43 | nyezin, RCF, RICIOLI, urban0, yepz |
|           57 |     1245 | 2024-05-14 | Galorys             | L   | 1.000      | -            | -                | -                | -         |   -12.84 | nyezin, RCF, RICIOLI, urban0, yepz |
|           56 |     1277 | 2024-05-14 | Hype Esports        | L   | 1.000      | -            | -                | -                | -         |   -23.05 | nyezin, RCF, RICIOLI, urban0, yepz |
|           55 |     1313 | 2024-05-13 | Intense Game        | W   | 1.000      | -            | -                | -                | -         |    12.14 | nyezin, RCF, RICIOLI, urban0, yepz |
|           54 |     1455 | 2024-05-11 | Galorys             | L   | 1.000      | -            | -                | -                | -         |   -15.24 | nyezin, RCF, RICIOLI, urban0, yepz |
|           53 |     1616 | 2024-05-08 | Galorys             | W   | 1.000      | -            | -                | -                | -         |    16.31 | nyezin, RCF, RICIOLI, urban0, yepz |
|           52 |     1688 | 2024-05-07 | inSanitY Sports     | L   | 1.000      | -            | -                | -                | -         |   -22.18 | nyezin, RCF, RICIOLI, urban0, yepz |
|           51 |     1771 | 2024-05-05 | ODDIK               | L   | 1.000      | -            | -                | -                | -         |   -12.16 | nyezin, RCF, RICIOLI, urban0, yepz |
|           50 |     1927 | 2024-05-02 | ODDIK               | W   | 1.000      | 0.450        | 0.017 (0.008)    | 0.494 (0.222)    | -         |    19.66 | nyezin, RCF, RICIOLI, urban0, yepz |
|           49 |     1930 | 2024-05-02 | ODDIK               | L   | 1.000      | -            | -                | -                | -         |   -11.51 | nyezin, RCF, RICIOLI, urban0, yepz |
|           48 |     1971 | 2024-05-01 | Dusty Roots         | W   | 1.000      | -            | -                | -                | -         |     9.54 | nyezin, RCF, RICIOLI, urban0, yepz |
|           47 |     1978 | 2024-05-01 | 9z Team             | L   | 1.000      | -            | -                | -                | -         |    -3.06 | nyezin, RCF, RICIOLI, urban0, yepz |
|           46 |     1983 | 2024-05-01 | 9z Team             | L   | 1.000      | -            | -                | -                | -         |    -3.15 | nyezin, RCF, RICIOLI, urban0, yepz |
|           45 |     2869 | 2024-04-17 | MIBR                | L   | 0.918      | -            | -                | -                | -         |    -0.51 | RCF, RICIOLI, snow, urban0, yepz   |
|           44 |     2953 | 2024-04-16 | Galorys             | W   | 0.912      | -            | -                | -                | -         |    15.59 | RCF, RICIOLI, snow, urban0, yepz   |
|           43 |     3085 | 2024-04-13 | MIBR                | L   | 0.890      | -            | -                | -                | -         |    -0.48 | RCF, RICIOLI, snow, urban0, yepz   |
|           42 |     3126 | 2024-04-12 | adalYamigos         | W   | 0.885      | -            | -                | -                | -         |    11.20 | RCF, RICIOLI, snow, urban0, yepz   |
|           41 |     3197 | 2024-04-11 | FURIA Academy       | W   | 0.876      | -            | -                | -                | -         |     7.24 | RCF, RICIOLI, snow, urban0, yepz   |
|           40 |     3300 | 2024-04-09 | paiN Gaming         | L   | 0.865      | -            | -                | -                | -         |    -0.43 | RCF, RICIOLI, snow, urban0, yepz   |
|           39 |     3305 | 2024-04-09 | paiN Gaming         | L   | 0.865      | -            | -                | -                | -         |    -0.43 | RCF, RICIOLI, snow, urban0, yepz   |
|           38 |     3406 | 2024-04-07 | adalYamigos         | L   | 0.852      | -            | -                | -                | -         |   -16.10 | RCF, RICIOLI, snow, urban0, yepz   |
|           37 |     3616 | 2024-04-03 | Imperial Esports    | L   | 0.825      | -            | -                | -                | -         |    -0.64 | RCF, RICIOLI, snow, urban0, yepz   |
|           36 |     3619 | 2024-04-03 | Imperial Esports    | L   | 0.825      | -            | -                | -                | -         |    -0.64 | RCF, RICIOLI, snow, urban0, yepz   |
|           35 |     3864 | 2024-03-27 | MIBR                | L   | 0.779      | -            | -                | -                | -         |    -0.50 | RCF, RICIOLI, snow, urban0, yepz   |
|           34 |     3868 | 2024-03-27 | MIBR                | L   | 0.779      | -            | -                | -                | -         |    -0.50 | RCF, RICIOLI, snow, urban0, yepz   |
|           33 |     4363 | 2024-03-17 | ODDIK               | L   | 0.711      | -            | -                | -                | -         |    -8.14 | RCF, RICIOLI, snow, urban0, yepz   |
|           32 |     4416 | 2024-03-16 | MIBR Academy        | W   | 0.704      | -            | -                | -                | -         |     7.57 | RCF, RICIOLI, snow, urban0, yepz   |
|           31 |     4469 | 2024-03-15 | RED Canids          | L   | 0.698      | -            | -                | -                | -         |    -6.09 | RCF, RICIOLI, snow, urban0, yepz   |
|           30 |     4540 | 2024-03-14 | FURIA Academy       | W   | 0.691      | -            | -                | -                | -         |     4.42 | RCF, RICIOLI, snow, urban0, yepz   |
|           29 |     4581 | 2024-03-13 | RED Canids          | L   | 0.685      | -            | -                | -                | -         |    -5.82 | RCF, RICIOLI, snow, urban0, yepz   |
|           28 |     4589 | 2024-03-13 | Yawara E-Sports     | L   | 0.684      | -            | -                | -                | -         |   -15.31 | RCF, RICIOLI, snow, urban0, yepz   |
|           27 |     4612 | 2024-03-13 | ODDIK               | L   | 0.683      | -            | -                | -                | -         |    -8.58 | RCF, RICIOLI, snow, urban0, yepz   |
|           26 |     4656 | 2024-03-12 | inSanitY Sports     | W   | 0.679      | -            | -                | -                | -         |     2.38 | RCF, RICIOLI, snow, urban0, yepz   |
|           25 |     4683 | 2024-03-12 | LA RUGONETA         | W   | 0.676      | -            | -                | -                | -         |     4.02 | RCF, RICIOLI, snow, urban0, yepz   |
|           24 |     4766 | 2024-03-10 | FURIA Academy       | W   | 0.665      | -            | -                | -                | -         |     3.71 | RCF, RICIOLI, snow, urban0, yepz   |
|           23 |     4815 | 2024-03-09 | Sharks Esports      | W   | 0.658      | 0.435        | 0.019 (0.005)    | -                | -         |    13.02 | RCF, RICIOLI, snow, urban0, yepz   |
|           22 |     4918 | 2024-03-07 | Fluxo               | W   | 0.645      | 0.435        | 0.065 (0.018)    | 0.474 (0.133)    | -         |    14.85 | RCF, RICIOLI, snow, urban0, yepz   |
|           21 |     5069 | 2024-03-05 | adalYamigos         | L   | 0.633      | -            | -                | -                | -         |   -13.18 | RCF, RICIOLI, snow, urban0, yepz   |
|           20 |     5070 | 2024-03-05 | adalYamigos         | L   | 0.632      | -            | -                | -                | -         |   -13.84 | RCF, RICIOLI, snow, urban0, yepz   |
|           19 |     5126 | 2024-03-04 | Fluxo               | L   | 0.626      | -            | -                | -                | -         |    -5.66 | RCF, RICIOLI, snow, urban0, yepz   |
|           18 |     5127 | 2024-03-04 | Fluxo               | L   | 0.626      | -            | -                | -                | -         |    -5.92 | RCF, RICIOLI, snow, urban0, yepz   |
|           17 |     5638 | 2024-02-24 | 2Game Esports       | W   | 0.566      | -            | -                | -                | -         |     5.11 | RCF, RICIOLI, snow, urban0, yepz   |
|           16 |     5647 | 2024-02-24 | 2Game Esports       | L   | 0.566      | -            | -                | -                | -         |   -13.03 | RCF, RICIOLI, snow, urban0, yepz   |
|           15 |     5836 | 2024-02-21 | Team Solid          | W   | 0.546      | 0.450        | 0.062 (0.015)    | -                | -         |     8.73 | RCF, RICIOLI, snow, urban0, yepz   |
|           14 |     5845 | 2024-02-21 | Team Solid          | L   | 0.546      | -            | -                | -                | -         |    -8.65 | RCF, RICIOLI, snow, urban0, yepz   |
|           13 |     5851 | 2024-02-21 | Sharks Esports      | L   | 0.545      | -            | -                | -                | -         |    -7.82 | RCF, RICIOLI, snow, urban0, yepz   |
|           12 |     5913 | 2024-02-20 | 9z Team             | L   | 0.539      | -            | -                | -                | -         |    -1.99 | RCF, RICIOLI, snow, urban0, yepz   |
|           11 |     5915 | 2024-02-20 | w7m esports         | W   | 0.538      | -            | -                | -                | -         |     7.38 | RCF, RICIOLI, snow, urban0, yepz   |
|           10 |     5936 | 2024-02-20 | Sharks Esports      | L   | 0.537      | -            | -                | -                | -         |    -7.74 | RCF, RICIOLI, snow, urban0, yepz   |
|            9 |     5978 | 2024-02-19 | LA RUGONETA         | W   | 0.533      | -            | -                | -                | -         |     2.68 | RCF, RICIOLI, snow, urban0, yepz   |
|            8 |     6035 | 2024-02-18 | Galorys             | L   | 0.525      | -            | -                | -                | -         |    -9.49 | RCF, RICIOLI, snow, urban0, yepz   |
|            7 |     6143 | 2024-02-16 | BESTIA              | W   | 0.512      | 0.435        | 0.026 (0.006)    | 0.500 (0.111)    | -         |     9.72 | RCF, RICIOLI, snow, urban0, yepz   |
|            6 |     6196 | 2024-02-15 | 9z Team             | L   | 0.505      | -            | -                | -                | -         |    -1.60 | RCF, RICIOLI, snow, urban0, yepz   |
|            5 |     6199 | 2024-02-15 | Sharks Esports      | W   | 0.505      | -            | -                | -                | -         |     8.74 | RCF, RICIOLI, snow, urban0, yepz   |
|            4 |     6229 | 2024-02-15 | Flamengo Esports    | W   | 0.503      | -            | -                | -                | -         |     2.08 | RCF, RICIOLI, snow, urban0, yepz   |
|            3 |     6255 | 2024-02-14 | O PLANO C           | W   | 0.499      | -            | -                | -                | -         |     1.02 | RCF, RICIOLI, snow, urban0, yepz   |
|            2 |     6332 | 2024-02-13 | Galorys             | W   | 0.491      | -            | -                | -                | -         |     6.94 | RCF, RICIOLI, snow, urban0, yepz   |
|            1 |     6387 | 2024-02-12 | Dusty Roots         | W   | 0.484      | -            | -                | -                | -         |     3.70 | RCF, RICIOLI, snow, urban0, yepz   |

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
