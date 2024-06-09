### Roster Details<br />
Team Name: Fluxo<br />
Roster: arT, chay, Lucaozy, nicks, zevy<br />
Region: [Americas]( ../standings_americas.md)<br />
<br />
Global Rank: [47](../standings_global.md)<br />
Regional Rank: [10]( ../standings_americas.md)<br />
Final Rank Value:  1068.9<br />
<br />
Final Rank Value (1068.9) = Starting Rank Value (977.3) + Head To Head Adjustments (91.6)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.458[<sup>1</sup>](#table2)
- Bounty Collected: 0.473[<sup>2</sup>](#table1)
- Opponent Network: 0.206[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.284<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 977.3
- 400 + ( ( 0.284 - 0.000 ) / ( 0.787 - 0.000 ) ) * 1600 = 977.3


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent                | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                          |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           74 |      453 | 2024-05-22 | BESTIA                  | L   | 1.000      | -            | -                | -                | -         |   -17.51 | arT, chay, Lucaozy, nicks, zevy |
|           73 |      463 | 2024-05-22 | BESTIA                  | L   | 1.000      | -            | -                | -                | -         |   -19.09 | arT, chay, Lucaozy, nicks, zevy |
|           72 |      648 | 2024-05-20 | RED Canids              | W   | 1.000      | 0.450        | 0.076 (0.034)    | 0.536 (0.241)    | 0 (0.000) |    17.26 | arT, chay, Lucaozy, nicks, zevy |
|           71 |      652 | 2024-05-20 | RED Canids              | L   | 1.000      | -            | -                | -                | -         |   -14.11 | arT, chay, Lucaozy, nicks, zevy |
|           70 |      867 | 2024-05-18 | 9z Team                 | L   | 1.000      | -            | -                | -                | -         |    -9.73 | arT, chay, Lucaozy, nicks, zevy |
|           69 |      959 | 2024-05-17 | Case Esports            | W   | 1.000      | -            | -                | -                | 0 (0.000) |     6.68 | arT, chay, Lucaozy, nicks, zevy |
|           68 |     1052 | 2024-05-16 | RED Canids              | L   | 1.000      | -            | -                | -                | -         |   -16.93 | arT, chay, Lucaozy, nicks, zevy |
|           67 |     1137 | 2024-05-15 | 2Game Esports           | W   | 1.000      | -            | -                | -                | 0 (0.000) |     2.21 | arT, chay, Lucaozy, nicks, zevy |
|           66 |     1139 | 2024-05-15 | 2Game Esports           | W   | 1.000      | -            | -                | -                | 0 (0.000) |     2.26 | arT, chay, Lucaozy, nicks, zevy |
|           65 |     1164 | 2024-05-15 | Imperial Esports        | L   | 1.000      | -            | -                | -                | -         |    -4.87 | arT, chay, Lucaozy, nicks, zevy |
|           64 |     1250 | 2024-05-14 | Sharks Esports          | W   | 1.000      | -            | -                | -                | 0 (0.000) |     9.15 | arT, chay, Lucaozy, nicks, zevy |
|           63 |     1279 | 2024-05-14 | ODDIK                   | W   | 1.000      | 0.384        | -                | 0.494 (0.190)    | 0 (0.000) |     8.84 | arT, chay, Lucaozy, nicks, zevy |
|           62 |     1330 | 2024-05-13 | Hype Esports            | W   | 1.000      | -            | -                | -                | 0 (0.000) |     2.17 | arT, chay, Lucaozy, nicks, zevy |
|           61 |     1377 | 2024-05-12 | Vikings KR              | W   | 1.000      | -            | -                | -                | 0 (0.000) |     3.41 | arT, chay, Lucaozy, nicks, zevy |
|           60 |     1555 | 2024-05-09 | paiN Gaming             | W   | 1.000      | 0.450        | 0.463 (0.209)    | 0.547 (0.246)    | 0 (0.000) |    28.62 | arT, chay, Lucaozy, nicks, zevy |
|           59 |     1561 | 2024-05-09 | paiN Gaming             | L   | 1.000      | -            | -                | -                | -         |    -2.54 | arT, chay, Lucaozy, nicks, zevy |
|           58 |     2793 | 2024-04-18 | paiN Gaming             | L   | 0.926      | -            | -                | -                | -         |    -2.12 | chay, Lucaozy, PKL, v$m, zevy   |
|           57 |     2801 | 2024-04-18 | Imperial Esports        | L   | 0.925      | -            | -                | -                | -         |    -2.79 | chay, Lucaozy, PKL, v$m, zevy   |
|           56 |     2860 | 2024-04-17 | ODDIK                   | W   | 0.918      | -            | -                | -                | 0 (0.000) |     8.52 | chay, Lucaozy, PKL, v$m, zevy   |
|           55 |     2868 | 2024-04-17 | Team Solid              | W   | 0.918      | -            | -                | -                | -         |     7.13 | chay, Lucaozy, PKL, v$m, zevy   |
|           54 |     2951 | 2024-04-16 | Hype Esports            | W   | 0.912      | -            | -                | -                | -         |     1.74 | chay, Lucaozy, PKL, v$m, zevy   |
|           53 |     3109 | 2024-04-13 | Galorys                 | L   | 0.889      | -            | -                | -                | -         |   -21.30 | chay, Lucaozy, PKL, v$m, zevy   |
|           52 |     3222 | 2024-04-10 | Imperial Esports        | W   | 0.872      | 0.450        | 0.372 (0.146)    | 0.582 (0.228)    | -         |    25.12 | chay, Lucaozy, PKL, v$m, zevy   |
|           51 |     3223 | 2024-04-10 | Imperial Esports        | L   | 0.872      | -            | -                | -                | -         |    -2.14 | chay, Lucaozy, PKL, v$m, zevy   |
|           50 |     3302 | 2024-04-09 | ODDIK                   | W   | 0.865      | 0.450        | -                | 0.494 (0.192)    | -         |     7.88 | chay, Lucaozy, PKL, v$m, zevy   |
|           49 |     3304 | 2024-04-09 | ODDIK                   | W   | 0.865      | 0.450        | -                | 0.494 (0.192)    | -         |     8.40 | chay, Lucaozy, PKL, v$m, zevy   |
|           48 |     3357 | 2024-04-08 | ODDIK                   | W   | 0.858      | 0.435        | -                | 0.494 (0.184)    | -         |     8.90 | chay, Lucaozy, PKL, v$m, zevy   |
|           47 |     3447 | 2024-04-06 | BESTIA                  | L   | 0.845      | -            | -                | -                | -         |   -17.59 | chay, Lucaozy, PKL, v$m, zevy   |
|           46 |     3450 | 2024-04-06 | Team Solid              | W   | 0.844      | 0.435        | 0.062 (0.023)    | -                | -         |     7.30 | chay, Lucaozy, PKL, v$m, zevy   |
|           45 |     3515 | 2024-04-05 | MIBR                    | L   | 0.839      | -            | -                | -                | -         |    -1.85 | chay, Lucaozy, PKL, v$m, zevy   |
|           44 |     3516 | 2024-04-05 | MIBR                    | W   | 0.838      | 0.450        | 0.307 (0.116)    | 0.531 (0.200)    | -         |    24.82 | chay, Lucaozy, PKL, v$m, zevy   |
|           43 |     3560 | 2024-04-04 | Corinthians Esports     | W   | 0.832      | 0.450        | -                | 0.458 (0.171)    | -         |     3.31 | chay, Lucaozy, PKL, v$m, zevy   |
|           42 |     3563 | 2024-04-04 | Corinthians Esports     | W   | 0.832      | -            | -                | -                | -         |     3.42 | chay, Lucaozy, PKL, v$m, zevy   |
|           41 |     3589 | 2024-04-04 | RED Canids              | L   | 0.830      | -            | -                | -                | -         |   -12.50 | chay, Lucaozy, PKL, v$m, zevy   |
|           40 |     3613 | 2024-04-03 | MIBR                    | L   | 0.825      | -            | -                | -                | -         |    -1.48 | chay, Lucaozy, PKL, v$m, zevy   |
|           39 |     3625 | 2024-04-03 | BESTIA                  | W   | 0.824      | -            | -                | -                | -         |     9.95 | chay, Lucaozy, PKL, v$m, zevy   |
|           38 |     3673 | 2024-04-02 | MIBR                    | L   | 0.819      | -            | -                | -                | -         |    -1.41 | chay, Lucaozy, PKL, v$m, zevy   |
|           37 |     3678 | 2024-04-02 | BESTIA                  | W   | 0.818      | -            | -                | -                | -         |    10.32 | chay, Lucaozy, PKL, v$m, zevy   |
|           36 |     3863 | 2024-03-27 | Galorys                 | L   | 0.779      | -            | -                | -                | -         |   -18.76 | chay, Lucaozy, PKL, v$m, zevy   |
|           35 |     3869 | 2024-03-27 | Galorys                 | W   | 0.779      | 0.450        | -                | 0.600 (0.210)    | -         |     5.60 | chay, Lucaozy, PKL, v$m, zevy   |
|           34 |     4580 | 2024-03-13 | Intense Game            | W   | 0.685      | -            | -                | -                | -         |     3.75 | chay, Lucaozy, PKL, v$m, zevy   |
|           33 |     4609 | 2024-03-13 | Team Solid              | L   | 0.684      | -            | -                | -                | -         |   -15.74 | chay, Lucaozy, PKL, v$m, zevy   |
|           32 |     4647 | 2024-03-12 | parece um barco andando | W   | 0.679      | -            | -                | -                | -         |     1.60 | chay, Lucaozy, PKL, v$m, zevy   |
|           31 |     4665 | 2024-03-12 | MIBR                    | W   | 0.678      | 0.435        | 0.307 (0.091)    | -                | -         |    20.24 | chay, Lucaozy, PKL, v$m, zevy   |
|           30 |     4746 | 2024-03-11 | Sharks Esports          | W   | 0.670      | -            | -                | -                | -         |     8.29 | chay, Lucaozy, PKL, v$m, zevy   |
|           29 |     4845 | 2024-03-09 | Corinthians Esports     | W   | 0.656      | -            | -                | -                | -         |     2.66 | chay, Lucaozy, PKL, v$m, zevy   |
|           28 |     4918 | 2024-03-07 | Case Esports            | L   | 0.645      | -            | -                | -                | -         |   -14.85 | chay, Lucaozy, PKL, v$m, zevy   |
|           27 |     4971 | 2024-03-06 | Team Solid              | L   | 0.639      | -            | -                | -                | -         |   -14.65 | chay, Lucaozy, PKL, v$m, zevy   |
|           26 |     4972 | 2024-03-06 | Team Solid              | W   | 0.639      | 0.450        | 0.062 (0.018)    | -                | -         |     5.44 | chay, Lucaozy, PKL, v$m, zevy   |
|           25 |     5126 | 2024-03-04 | Case Esports            | W   | 0.626      | -            | -                | -                | -         |     5.66 | chay, Lucaozy, PKL, v$m, zevy   |
|           24 |     5127 | 2024-03-04 | Case Esports            | W   | 0.626      | -            | -                | -                | -         |     5.92 | chay, Lucaozy, PKL, v$m, zevy   |
|           23 |     5598 | 2024-02-25 | Imperial Esports        | W   | 0.571      | 0.435        | 0.372 (0.092)    | -                | -         |    16.90 | chay, Lucaozy, PKL, v$m, zevy   |
|           22 |     5665 | 2024-02-24 | Sharks Esports          | W   | 0.565      | -            | -                | -                | -         |     7.11 | chay, Lucaozy, PKL, v$m, zevy   |
|           21 |     5865 | 2024-02-21 | Team Solid              | W   | 0.544      | 0.435        | 0.062 (0.015)    | -                | -         |     5.93 | chay, Lucaozy, PKL, v$m, zevy   |
|           20 |     5917 | 2024-02-20 | Team Solid              | L   | 0.538      | -            | -                | -                | -         |   -11.39 | chay, Lucaozy, PKL, v$m, zevy   |
|           19 |     5981 | 2024-02-19 | NIGERIA 96              | W   | 0.533      | -            | -                | -                | -         |     1.82 | chay, Lucaozy, PKL, v$m, zevy   |
|           18 |     6145 | 2024-02-16 | 9z Team                 | W   | 0.511      | 0.435        | 0.107 (0.024)    | -                | -         |    13.40 | chay, Lucaozy, PKL, v$m, zevy   |
|           17 |     6197 | 2024-02-15 | Imperial Esports        | L   | 0.505      | -            | -                | -                | -         |    -0.75 | chay, Lucaozy, PKL, v$m, zevy   |
|           16 |     6201 | 2024-02-15 | w7m esports             | W   | 0.505      | -            | -                | -                | -         |     4.83 | chay, Lucaozy, PKL, v$m, zevy   |
|           15 |     6212 | 2024-02-15 | Sharks Esports          | W   | 0.504      | -            | -                | -                | -         |     6.81 | chay, Lucaozy, PKL, v$m, zevy   |
|           14 |     6216 | 2024-02-15 | Sharks Esports          | W   | 0.504      | -            | -                | -                | -         |     7.11 | chay, Lucaozy, PKL, v$m, zevy   |
|           13 |     6257 | 2024-02-14 | Intense Game            | W   | 0.499      | -            | -                | -                | -         |     2.86 | chay, Lucaozy, PKL, v$m, zevy   |
|           12 |     6404 | 2024-02-12 | Flamengo Esports        | W   | 0.483      | -            | -                | -                | -         |     1.25 | chay, Lucaozy, PKL, v$m, zevy   |
|           11 |     7070 | 2024-01-28 | Sharks Esports          | L   | 0.385      | -            | -                | -                | -         |    -6.72 | chay, Lucaozy, PKL, v$m, zevy   |
|           10 |     7127 | 2024-01-27 | ???                     | W   | 0.379      | -            | -                | -                | -         |     0.75 | chay, Lucaozy, PKL, v$m, zevy   |
|            9 |     7241 | 2024-01-26 | RED Canids              | L   | 0.371      | -            | -                | -                | -         |    -5.43 | chay, Lucaozy, PKL, v$m, zevy   |
|            8 |     7247 | 2024-01-26 | adalYamigos             | W   | 0.371      | -            | -                | -                | -         |     1.79 | chay, Lucaozy, PKL, v$m, zevy   |
|            7 |     7405 | 2024-01-23 | 9z Team                 | L   | 0.352      | -            | -                | -                | -         |    -1.80 | chay, Lucaozy, PKL, v$m, zevy   |
|            6 |     7440 | 2024-01-22 | ODDIK                   | W   | 0.346      | -            | -                | -                | -         |     5.15 | chay, Lucaozy, PKL, v$m, zevy   |
|            5 |     7513 | 2024-01-21 | Case Esports            | L   | 0.337      | -            | -                | -                | -         |    -8.74 | chay, Lucaozy, PKL, v$m, zevy   |
|            4 |     7563 | 2024-01-20 | Imperial Esports        | L   | 0.331      | -            | -                | -                | -         |    -0.44 | chay, Lucaozy, PKL, v$m, zevy   |
|            3 |     7631 | 2024-01-19 | RED Canids              | L   | 0.326      | -            | -                | -                | -         |    -4.84 | chay, Lucaozy, PKL, v$m, zevy   |
|            2 |     7639 | 2024-01-19 | adalYamigos             | W   | 0.325      | -            | -                | -                | -         |     1.49 | chay, Lucaozy, PKL, v$m, zevy   |
|            1 |     9786 | 2023-12-02 | ex-Anonymo Esports      | L   | 0.002      | -            | -                | -                | -         |    -0.05 | chay, Lucaozy, PKL, v$m, zevy   |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($19,701.71)
- Divide that value by the 5th highest value among all rosters ($300,806.11)
- The final value (0.07) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-05-19 |      1.000 | $1,960.05      | $1,960.05       |
| 2024-03-14 |      0.691 | $5,000.00      | $3,456.94       |
| 2024-02-25 |      0.571 | $25,000.00     | $14,284.72      |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
