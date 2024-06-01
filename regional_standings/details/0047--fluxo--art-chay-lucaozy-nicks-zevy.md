### Roster Details<br />
Team Name: Fluxo<br />
Roster: arT, chay, Lucaozy, nicks, zevy<br />
Region: [Americas]( ../standings_americas.md)<br />
<br />
Global Rank: [47](../standings_global.md)<br />
Regional Rank: [10]( ../standings_americas.md)<br />
Final Rank Value:  1068.1<br />
<br />
Final Rank Value (1068.1) = Starting Rank Value (979.5) + Head To Head Adjustments (88.7)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.458[<sup>1</sup>](#table2)
- Bounty Collected: 0.473[<sup>2</sup>](#table1)
- Opponent Network: 0.208[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.285<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 979.5
- 400 + ( ( 0.285 - 0.000 ) / ( 0.786 - 0.000 ) ) * 1600 = 979.5


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
|           72 |      447 | 2024-05-22 | BESTIA                  | L   | 1.000      | -            | -                | -                | -         |   -17.24 | arT, chay, Lucaozy, nicks, zevy |
|           71 |      457 | 2024-05-22 | BESTIA                  | L   | 1.000      | -            | -                | -                | -         |   -18.80 | arT, chay, Lucaozy, nicks, zevy |
|           70 |      637 | 2024-05-20 | RED Canids              | W   | 1.000      | 0.450        | 0.076 (0.034)    | 0.508 (0.229)    | 0 (0.000) |    17.43 | arT, chay, Lucaozy, nicks, zevy |
|           69 |      641 | 2024-05-20 | RED Canids              | L   | 1.000      | -            | -                | -                | -         |   -13.92 | arT, chay, Lucaozy, nicks, zevy |
|           68 |      855 | 2024-05-18 | 9z Team                 | L   | 1.000      | -            | -                | -                | -         |    -9.72 | arT, chay, Lucaozy, nicks, zevy |
|           67 |      947 | 2024-05-17 | Case Esports            | W   | 1.000      | -            | -                | -                | 0 (0.000) |     6.85 | arT, chay, Lucaozy, nicks, zevy |
|           66 |     1040 | 2024-05-16 | RED Canids              | L   | 1.000      | -            | -                | -                | -         |   -16.70 | arT, chay, Lucaozy, nicks, zevy |
|           65 |     1127 | 2024-05-15 | 2Game Esports           | W   | 1.000      | -            | -                | -                | 0 (0.000) |     2.26 | arT, chay, Lucaozy, nicks, zevy |
|           64 |     1130 | 2024-05-15 | 2Game Esports           | W   | 1.000      | -            | -                | -                | 0 (0.000) |     2.31 | arT, chay, Lucaozy, nicks, zevy |
|           63 |     1155 | 2024-05-15 | Imperial Esports        | L   | 1.000      | -            | -                | -                | -         |    -4.79 | arT, chay, Lucaozy, nicks, zevy |
|           62 |     1240 | 2024-05-14 | Sharks Esports          | W   | 1.000      | -            | -                | -                | 0 (0.000) |     7.71 | arT, chay, Lucaozy, nicks, zevy |
|           61 |     1268 | 2024-05-14 | ODDIK                   | W   | 1.000      | 0.384        | -                | 0.494 (0.190)    | 0 (0.000) |     9.12 | arT, chay, Lucaozy, nicks, zevy |
|           60 |     1318 | 2024-05-13 | Hype Esports            | W   | 1.000      | -            | -                | -                | 0 (0.000) |     2.21 | arT, chay, Lucaozy, nicks, zevy |
|           59 |     1364 | 2024-05-12 | Vikings KR              | W   | 1.000      | -            | -                | -                | 0 (0.000) |     3.47 | arT, chay, Lucaozy, nicks, zevy |
|           58 |     1540 | 2024-05-09 | paiN Gaming             | W   | 1.000      | 0.450        | 0.463 (0.209)    | 0.524 (0.236)    | 0 (0.000) |    28.66 | arT, chay, Lucaozy, nicks, zevy |
|           57 |     1546 | 2024-05-09 | paiN Gaming             | L   | 1.000      | -            | -                | -                | -         |    -2.50 | arT, chay, Lucaozy, nicks, zevy |
|           56 |     2737 | 2024-04-18 | paiN Gaming             | L   | 0.926      | -            | -                | -                | -         |    -2.08 | chay, Lucaozy, PKL, v$m, zevy   |
|           55 |     2745 | 2024-04-18 | Imperial Esports        | L   | 0.925      | -            | -                | -                | -         |    -2.75 | chay, Lucaozy, PKL, v$m, zevy   |
|           54 |     2804 | 2024-04-17 | ODDIK                   | W   | 0.918      | -            | -                | -                | 0 (0.000) |     8.79 | chay, Lucaozy, PKL, v$m, zevy   |
|           53 |     2811 | 2024-04-17 | Team Solid              | W   | 0.918      | -            | -                | -                | -         |     7.50 | chay, Lucaozy, PKL, v$m, zevy   |
|           52 |     2893 | 2024-04-16 | Hype Esports            | W   | 0.912      | -            | -                | -                | -         |     1.78 | chay, Lucaozy, PKL, v$m, zevy   |
|           51 |     3043 | 2024-04-13 | Galorys                 | L   | 0.889      | -            | -                | -                | -         |   -20.71 | chay, Lucaozy, PKL, v$m, zevy   |
|           50 |     3151 | 2024-04-10 | Imperial Esports        | W   | 0.872      | 0.450        | 0.372 (0.146)    | 0.582 (0.228)    | -         |    25.16 | chay, Lucaozy, PKL, v$m, zevy   |
|           49 |     3152 | 2024-04-10 | Imperial Esports        | L   | 0.872      | -            | -                | -                | -         |    -2.10 | chay, Lucaozy, PKL, v$m, zevy   |
|           48 |     3224 | 2024-04-09 | ODDIK                   | W   | 0.865      | 0.450        | -                | 0.494 (0.192)    | -         |     8.20 | chay, Lucaozy, PKL, v$m, zevy   |
|           47 |     3226 | 2024-04-09 | ODDIK                   | W   | 0.865      | 0.450        | -                | 0.494 (0.192)    | -         |     8.76 | chay, Lucaozy, PKL, v$m, zevy   |
|           46 |     3277 | 2024-04-08 | ODDIK                   | W   | 0.858      | -            | -                | -                | -         |     9.29 | chay, Lucaozy, PKL, v$m, zevy   |
|           45 |     3364 | 2024-04-06 | BESTIA                  | L   | 0.845      | -            | -                | -                | -         |   -17.20 | chay, Lucaozy, PKL, v$m, zevy   |
|           44 |     3367 | 2024-04-06 | Team Solid              | W   | 0.844      | 0.435        | 0.062 (0.023)    | -                | -         |     7.78 | chay, Lucaozy, PKL, v$m, zevy   |
|           43 |     3431 | 2024-04-05 | MIBR                    | L   | 0.839      | -            | -                | -                | -         |    -1.79 | chay, Lucaozy, PKL, v$m, zevy   |
|           42 |     3432 | 2024-04-05 | MIBR                    | W   | 0.838      | 0.450        | 0.307 (0.116)    | 0.512 (0.193)    | -         |    24.87 | chay, Lucaozy, PKL, v$m, zevy   |
|           41 |     3475 | 2024-04-04 | Corinthians Esports     | W   | 0.832      | 0.450        | -                | 0.553 (0.207)    | -         |     3.59 | chay, Lucaozy, PKL, v$m, zevy   |
|           40 |     3478 | 2024-04-04 | Corinthians Esports     | W   | 0.832      | 0.450        | -                | 0.553 (0.207)    | -         |     3.72 | chay, Lucaozy, PKL, v$m, zevy   |
|           39 |     3503 | 2024-04-04 | RED Canids              | L   | 0.830      | -            | -                | -                | -         |   -12.18 | chay, Lucaozy, PKL, v$m, zevy   |
|           38 |     3526 | 2024-04-03 | MIBR                    | L   | 0.825      | -            | -                | -                | -         |    -1.42 | chay, Lucaozy, PKL, v$m, zevy   |
|           37 |     3538 | 2024-04-03 | BESTIA                  | W   | 0.824      | -            | -                | -                | -         |    10.44 | chay, Lucaozy, PKL, v$m, zevy   |
|           36 |     3584 | 2024-04-02 | MIBR                    | L   | 0.819      | -            | -                | -                | -         |    -1.35 | chay, Lucaozy, PKL, v$m, zevy   |
|           35 |     3589 | 2024-04-02 | BESTIA                  | W   | 0.818      | -            | -                | -                | -         |    10.63 | chay, Lucaozy, PKL, v$m, zevy   |
|           34 |     3770 | 2024-03-27 | Galorys                 | L   | 0.779      | -            | -                | -                | -         |   -18.27 | chay, Lucaozy, PKL, v$m, zevy   |
|           33 |     3776 | 2024-03-27 | Galorys                 | W   | 0.779      | 0.450        | -                | 0.585 (0.205)    | -         |     6.11 | chay, Lucaozy, PKL, v$m, zevy   |
|           32 |     4466 | 2024-03-13 | Intense Game            | W   | 0.685      | -            | -                | -                | -         |     3.91 | chay, Lucaozy, PKL, v$m, zevy   |
|           31 |     4494 | 2024-03-13 | Team Solid              | L   | 0.684      | -            | -                | -                | -         |   -15.25 | chay, Lucaozy, PKL, v$m, zevy   |
|           30 |     4528 | 2024-03-12 | parece um barco andando | W   | 0.679      | -            | -                | -                | -         |     1.67 | chay, Lucaozy, PKL, v$m, zevy   |
|           29 |     4546 | 2024-03-12 | MIBR                    | W   | 0.678      | 0.435        | 0.307 (0.091)    | -                | -         |    20.30 | chay, Lucaozy, PKL, v$m, zevy   |
|           28 |     4624 | 2024-03-11 | Sharks Esports          | W   | 0.670      | -            | -                | -                | -         |     7.99 | chay, Lucaozy, PKL, v$m, zevy   |
|           27 |     4720 | 2024-03-09 | Corinthians Esports     | W   | 0.656      | -            | -                | -                | -         |     3.01 | chay, Lucaozy, PKL, v$m, zevy   |
|           26 |     4790 | 2024-03-07 | Case Esports            | L   | 0.645      | -            | -                | -                | -         |   -14.63 | chay, Lucaozy, PKL, v$m, zevy   |
|           25 |     4840 | 2024-03-06 | Team Solid              | L   | 0.639      | -            | -                | -                | -         |   -14.12 | chay, Lucaozy, PKL, v$m, zevy   |
|           24 |     4841 | 2024-03-06 | Team Solid              | W   | 0.639      | 0.450        | 0.062 (0.018)    | -                | -         |     6.00 | chay, Lucaozy, PKL, v$m, zevy   |
|           23 |     4980 | 2024-03-04 | Case Esports            | W   | 0.626      | -            | -                | -                | -         |     5.91 | chay, Lucaozy, PKL, v$m, zevy   |
|           22 |     4981 | 2024-03-04 | Case Esports            | W   | 0.626      | -            | -                | -                | -         |     6.19 | chay, Lucaozy, PKL, v$m, zevy   |
|           21 |     5440 | 2024-02-25 | Imperial Esports        | W   | 0.571      | 0.435        | 0.372 (0.092)    | -                | -         |    16.97 | chay, Lucaozy, PKL, v$m, zevy   |
|           20 |     5505 | 2024-02-24 | Sharks Esports          | W   | 0.565      | -            | -                | -                | -         |     7.55 | chay, Lucaozy, PKL, v$m, zevy   |
|           19 |     5702 | 2024-02-21 | Team Solid              | W   | 0.544      | 0.435        | 0.062 (0.015)    | -                | -         |     6.15 | chay, Lucaozy, PKL, v$m, zevy   |
|           18 |     5750 | 2024-02-20 | Team Solid              | L   | 0.538      | -            | -                | -                | -         |   -11.17 | chay, Lucaozy, PKL, v$m, zevy   |
|           17 |     5811 | 2024-02-19 | NIGERIA 96              | W   | 0.533      | -            | -                | -                | -         |     1.94 | chay, Lucaozy, PKL, v$m, zevy   |
|           16 |     5972 | 2024-02-16 | 9z Team                 | W   | 0.511      | 0.435        | 0.107 (0.024)    | -                | -         |    13.54 | chay, Lucaozy, PKL, v$m, zevy   |
|           15 |     6021 | 2024-02-15 | Imperial Esports        | L   | 0.505      | -            | -                | -                | -         |    -0.70 | chay, Lucaozy, PKL, v$m, zevy   |
|           14 |     6025 | 2024-02-15 | w7m esports             | W   | 0.505      | -            | -                | -                | -         |     5.13 | chay, Lucaozy, PKL, v$m, zevy   |
|           13 |     6076 | 2024-02-14 | Intense Game            | W   | 0.499      | -            | -                | -                | -         |     2.85 | chay, Lucaozy, PKL, v$m, zevy   |
|           12 |     6216 | 2024-02-12 | Flamengo Esports        | W   | 0.483      | -            | -                | -                | -         |     1.25 | chay, Lucaozy, PKL, v$m, zevy   |
|           11 |     6853 | 2024-01-28 | Sharks Esports          | L   | 0.385      | -            | -                | -                | -         |    -6.77 | chay, Lucaozy, PKL, v$m, zevy   |
|           10 |     6909 | 2024-01-27 | ???                     | W   | 0.379      | -            | -                | -                | -         |     0.74 | chay, Lucaozy, PKL, v$m, zevy   |
|            9 |     7019 | 2024-01-26 | RED Canids              | L   | 0.371      | -            | -                | -                | -         |    -5.42 | chay, Lucaozy, PKL, v$m, zevy   |
|            8 |     7025 | 2024-01-26 | adalYamigos             | W   | 0.371      | -            | -                | -                | -         |     1.79 | chay, Lucaozy, PKL, v$m, zevy   |
|            7 |     7169 | 2024-01-23 | 9z Team                 | L   | 0.352      | -            | -                | -                | -         |    -1.82 | chay, Lucaozy, PKL, v$m, zevy   |
|            6 |     7199 | 2024-01-22 | ODDIK                   | W   | 0.346      | -            | -                | -                | -         |     5.13 | chay, Lucaozy, PKL, v$m, zevy   |
|            5 |     7270 | 2024-01-21 | Case Esports            | L   | 0.337      | -            | -                | -                | -         |    -8.76 | chay, Lucaozy, PKL, v$m, zevy   |
|            4 |     7320 | 2024-01-20 | Imperial Esports        | L   | 0.331      | -            | -                | -                | -         |    -0.44 | chay, Lucaozy, PKL, v$m, zevy   |
|            3 |     7387 | 2024-01-19 | RED Canids              | L   | 0.326      | -            | -                | -                | -         |    -4.83 | chay, Lucaozy, PKL, v$m, zevy   |
|            2 |     7395 | 2024-01-19 | adalYamigos             | W   | 0.325      | -            | -                | -                | -         |     1.48 | chay, Lucaozy, PKL, v$m, zevy   |
|            1 |     9504 | 2023-12-02 | ex-Anonymo Esports      | L   | 0.002      | -            | -                | -                | -         |    -0.05 | chay, Lucaozy, PKL, v$m, zevy   |

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
