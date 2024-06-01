### Roster Details<br />
Team Name: RED Canids<br />
Roster: coldzera, dav1deuS, hardzao, nython, venomzera<br />
Region: [Americas]( ../standings_americas.md)<br />
<br />
Global Rank: [40](../standings_global.md)<br />
Regional Rank: [9]( ../standings_americas.md)<br />
Final Rank Value:  1124.9<br />
<br />
Final Rank Value (1124.9) = Starting Rank Value (992.9) + Head To Head Adjustments (132.0)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.472[<sup>1</sup>](#table2)
- Bounty Collected: 0.423[<sup>2</sup>](#table1)
- Opponent Network: 0.206[<sup>2</sup>](#table1)
- LAN Wins: 0.064[<sup>2</sup>](#table1)

The average of these factors is 0.291<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 992.9
- 400 + ( ( 0.291 - 0.000 ) / ( 0.786 - 0.000 ) ) * 1600 = 992.9


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent                  | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                         |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           72 |      637 | 2024-05-20 | Fluxo                     | L   | 1.000      | -            | -                | -                | -         |   -17.43 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           71 |      641 | 2024-05-20 | Fluxo                     | W   | 1.000      | 0.450        | 0.065 (0.029)    | 0.474 (0.213)    | 0 (0.000) |    13.92 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           70 |      735 | 2024-05-19 | 9z Team                   | W   | 1.000      | 0.143        | 0.107 (0.015)    | -                | 0 (0.000) |    21.10 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           69 |      821 | 2024-05-18 | ODDIK                     | W   | 1.000      | -            | -                | -                | 0 (0.000) |     8.63 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           68 |     1040 | 2024-05-16 | Fluxo                     | W   | 1.000      | 0.143        | 0.065 (0.009)    | -                | 0 (0.000) |    16.70 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           67 |     1124 | 2024-05-15 | 9z Team                   | L   | 1.000      | -            | -                | -                | -         |    -9.21 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           66 |     1126 | 2024-05-15 | 9z Team                   | W   | 1.000      | 0.450        | 0.107 (0.048)    | 0.547 (0.246)    | 0 (0.000) |    22.79 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           65 |     1230 | 2024-05-14 | Corinthians Esports       | W   | 1.000      | 0.450        | -                | 0.553 (0.249)    | 0 (0.000) |     3.94 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           64 |     1234 | 2024-05-14 | Corinthians Esports       | W   | 1.000      | 0.450        | -                | 0.553 (0.249)    | 0 (0.000) |     4.10 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           63 |     1255 | 2024-05-14 | BESTIA                    | W   | 1.000      | -            | -                | -                | 0 (0.000) |     9.98 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           62 |     1299 | 2024-05-13 | Sharks Esports            | L   | 1.000      | -            | -                | -                | -         |   -22.14 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           61 |     1339 | 2024-05-12 | Vikings KR                | W   | 1.000      | -            | -                | -                | 0 (0.000) |     3.93 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           60 |     1347 | 2024-05-12 | FURIA Academy             | W   | 1.000      | -            | -                | -                | -         |     2.51 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           59 |     1521 | 2024-05-10 | paiN Gaming               | L   | 1.000      | -            | -                | -                | -         |    -2.82 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           58 |     1548 | 2024-05-09 | Intense Game              | W   | 1.000      | 0.435        | -                | 0.362 (0.157)    | -         |     5.00 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           57 |     1595 | 2024-05-08 | paiN Gaming               | L   | 1.000      | -            | -                | -                | -         |    -2.47 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           56 |     1598 | 2024-05-08 | paiN Gaming               | W   | 1.000      | 0.450        | 0.463 (0.209)    | 0.524 (0.236)    | -         |    29.38 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           55 |     1604 | 2024-05-08 | Team Solid                | L   | 1.000      | -            | -                | -                | -         |   -22.29 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           54 |     1734 | 2024-05-06 | Intense Game              | W   | 1.000      | 0.435        | -                | 0.362 (0.157)    | -         |     5.09 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           53 |     2296 | 2024-04-25 | BESTIA                    | W   | 0.972      | 0.450        | 0.026 (0.011)    | 0.477 (0.209)    | -         |     7.89 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           52 |     2297 | 2024-04-25 | BESTIA                    | W   | 0.972      | 0.450        | 0.026 (0.011)    | 0.477 (0.209)    | -         |     8.44 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           51 |     2803 | 2024-04-17 | MIBR                      | L   | 0.918      | -            | -                | -                | -         |    -1.40 | dav1deuS, hardzao, nython, righi, venomzera    |
|           50 |     2813 | 2024-04-17 | O Plano                   | W   | 0.918      | -            | -                | -                | -         |     1.75 | dav1deuS, hardzao, nython, righi, venomzera    |
|           49 |     2894 | 2024-04-16 | LaChampionsLiga           | W   | 0.912      | -            | -                | -                | -         |     1.66 | dav1deuS, hardzao, nython, righi, venomzera    |
|           48 |     3003 | 2024-04-13 | Imperial Esports          | L   | 0.892      | -            | -                | -                | -         |    -2.31 | dav1deuS, hardzao, nython, righi, venomzera    |
|           47 |     3073 | 2024-04-12 | w7m esports               | W   | 0.884      | -            | -                | -                | -         |     6.56 | dav1deuS, hardzao, nython, righi, venomzera    |
|           46 |     3160 | 2024-04-10 | paiN Gaming               | L   | 0.871      | -            | -                | -                | -         |    -1.38 | dav1deuS, hardzao, nython, righi, venomzera    |
|           45 |     3231 | 2024-04-09 | MIBR                      | L   | 0.864      | -            | -                | -                | -         |    -1.62 | dav1deuS, hardzao, nython, righi, venomzera    |
|           44 |     3276 | 2024-04-08 | BESTIA                    | W   | 0.858      | -            | -                | -                | -         |     9.68 | dav1deuS, hardzao, nython, righi, venomzera    |
|           43 |     3326 | 2024-04-07 | Imperial Esports          | L   | 0.852      | -            | -                | -                | -         |    -1.81 | dav1deuS, hardzao, nython, righi, venomzera    |
|           42 |     3373 | 2024-04-06 | w7m esports               | L   | 0.844      | -            | -                | -                | -         |   -20.65 | dav1deuS, hardzao, nython, righi, venomzera    |
|           41 |     3503 | 2024-04-04 | Fluxo                     | W   | 0.830      | 0.143        | 0.065 (0.008)    | -                | -         |    12.18 | dav1deuS, hardzao, nython, righi, venomzera    |
|           40 |     4203 | 2024-03-18 | ODDIK                     | W   | 0.718      | -            | -                | -                | -         |     8.62 | dav1deuS, DeStiNy, hardzao, nython, venomzera  |
|           39 |     4302 | 2024-03-16 | ODDIK                     | W   | 0.705      | -            | -                | -                | -         |     8.74 | dav1deuS, DeStiNy, hardzao, nython, venomzera  |
|           38 |     4362 | 2024-03-15 | Case Esports              | W   | 0.698      | -            | -                | -                | -         |     6.01 | dav1deuS, DeStiNy, hardzao, nython, venomzera  |
|           37 |     4414 | 2024-03-14 | Team Solid                | L   | 0.691      | -            | -                | -                | -         |   -15.04 | dav1deuS, DeStiNy, hardzao, nython, venomzera  |
|           36 |     4433 | 2024-03-14 | Flamengo Esports          | W   | 0.690      | -            | -                | -                | -         |     1.44 | dav1deuS, DeStiNy, hardzao, nython, venomzera  |
|           35 |     4467 | 2024-03-13 | Case Esports              | W   | 0.685      | 0.435        | 0.028 (0.008)    | 0.461 (0.137)    | -         |     5.75 | dav1deuS, DeStiNy, hardzao, nython, venomzera  |
|           34 |     4485 | 2024-03-13 | Galorys                   | W   | 0.684      | -            | -                | -                | -         |     5.21 | dav1deuS, DeStiNy, hardzao, nython, venomzera  |
|           33 |     4544 | 2024-03-12 | Full House Gaming         | W   | 0.679      | -            | -                | -                | -         |     2.52 | dav1deuS, DeStiNy, hardzao, nython, venomzera  |
|           32 |     4603 | 2024-03-11 | Corinthians Esports       | W   | 0.671      | -            | -                | -                | -         |     2.81 | dav1deuS, DeStiNy, hardzao, nython, venomzera  |
|           31 |     4689 | 2024-03-09 | w7m esports               | W   | 0.659      | -            | -                | -                | -         |     5.78 | dav1deuS, DeStiNy, hardzao, nython, venomzera  |
|           30 |     4785 | 2024-03-07 | VELOX Argentina           | W   | 0.646      | -            | -                | -                | -         |     1.67 | dav1deuS, DeStiNy, hardzao, nython, venomzera  |
|           29 |     5071 | 2024-03-03 | ODDIK                     | L   | 0.618      | -            | -                | -                | -         |   -11.36 | dav1deuS, DeStiNy, hardzao, nython, venomzera  |
|           28 |     5185 | 2024-03-02 | paiN Gaming               | L   | 0.610      | -            | -                | -                | -         |    -0.77 | dav1deuS, DeStiNy, hardzao, nython, venomzera  |
|           27 |     5220 | 2024-03-01 | Wildcard Gaming           | W   | 0.605      | -            | -                | -                | 1 (0.605) |     7.40 | dav1deuS, DeStiNy, hardzao, nython, venomzera  |
|           26 |     6136 | 2024-02-13 | Imperial Esports          | L   | 0.493      | -            | -                | -                | -         |    -0.84 | dav1deuS, DeStiNy, hardzao, nython, venomzera  |
|           25 |     6137 | 2024-02-13 | Imperial Esports          | W   | 0.492      | 0.450        | 0.372 (0.082)    | -                | -         |    14.76 | dav1deuS, DeStiNy, hardzao, nython, venomzera  |
|           24 |     6648 | 2024-02-01 | w7m esports               | L   | 0.413      | -            | -                | -                | -         |    -9.80 | dav1deuS, DeStiNy, hardzao, nython, venomzera  |
|           23 |     6651 | 2024-02-01 | paiN Gaming               | L   | 0.412      | -            | -                | -                | -         |    -0.45 | dav1deuS, DeStiNy, hardzao, nython, venomzera  |
|           22 |     7017 | 2024-01-26 | FURIA Academy             | W   | 0.372      | -            | -                | -                | -         |     0.97 | dav1deuS, DeStiNy, hardzao, nython, venomzera  |
|           21 |     7019 | 2024-01-26 | Fluxo                     | W   | 0.371      | -            | -                | -                | -         |     5.42 | dav1deuS, DeStiNy, hardzao, nython, venomzera  |
|           20 |     7070 | 2024-01-25 | Intense Game              | W   | 0.366      | -            | -                | -                | -         |     1.21 | dav1deuS, DeStiNy, hardzao, nython, venomzera  |
|           19 |     7203 | 2024-01-22 | w7m esports               | L   | 0.346      | -            | -                | -                | -         |    -8.45 | dav1deuS, DeStiNy, hardzao, nython, venomzera  |
|           18 |     7256 | 2024-01-21 | 9z Team                   | W   | 0.340      | -            | -                | -                | -         |     8.79 | dav1deuS, DeStiNy, hardzao, nython, venomzera  |
|           17 |     7258 | 2024-01-21 | Flamengo Esports          | W   | 0.339      | -            | -                | -                | -         |     0.86 | dav1deuS, DeStiNy, hardzao, nython, venomzera  |
|           16 |     7263 | 2024-01-21 | ODDIK                     | L   | 0.338      | -            | -                | -                | -         |    -6.16 | dav1deuS, DeStiNy, hardzao, nython, venomzera  |
|           15 |     7313 | 2024-01-20 | Legacy                    | L   | 0.331      | -            | -                | -                | -         |    -4.82 | dav1deuS, DeStiNy, hardzao, nython, venomzera  |
|           14 |     7387 | 2024-01-19 | Fluxo                     | W   | 0.326      | -            | -                | -                | -         |     4.83 | dav1deuS, DeStiNy, hardzao, nython, venomzera  |
|           13 |     7399 | 2024-01-19 | Case Esports              | W   | 0.324      | -            | -                | -                | -         |     1.59 | dav1deuS, DeStiNy, hardzao, nython, venomzera  |
|           12 |     7507 | 2024-01-17 | Sharks Esports            | L   | 0.312      | -            | -                | -                | -         |    -6.19 | dav1deuS, DeStiNy, hardzao, nython, venomzera  |
|           11 |     7542 | 2024-01-17 | 9z Team                   | L   | 0.311      | -            | -                | -                | -         |    -1.86 | dav1deuS, DeStiNy, hardzao, nython, venomzera  |
|           10 |     7611 | 2024-01-16 | Legacy                    | W   | 0.306      | -            | -                | -                | -         |     5.01 | dav1deuS, DeStiNy, hardzao, nython, venomzera  |
|            9 |     7619 | 2024-01-16 | Case Esports              | W   | 0.305      | -            | -                | -                | -         |     1.50 | dav1deuS, DeStiNy, hardzao, nython, venomzera  |
|            8 |     7627 | 2024-01-16 | adalYamigos               | W   | 0.305      | -            | -                | -                | -         |     1.28 | dav1deuS, DeStiNy, hardzao, nython, venomzera  |
|            7 |     7705 | 2024-01-15 | Arena Jogue Fácil Esports | W   | 0.299      | -            | -                | -                | -         |     0.96 | dav1deuS, DeStiNy, hardzao, nython, venomzera  |
|            6 |     7746 | 2024-01-14 | paiN Gaming               | L   | 0.292      | -            | -                | -                | -         |    -0.24 | dav1deuS, DeStiNy, hardzao, nython, venomzera  |
|            5 |     7750 | 2024-01-14 | Legacy                    | W   | 0.292      | -            | -                | -                | -         |     4.77 | dav1deuS, DeStiNy, hardzao, nython, venomzera  |
|            4 |     7771 | 2024-01-13 | E-Xolos LAZER             | W   | 0.286      | -            | -                | -                | -         |     0.31 | dav1deuS, DeStiNy, hardzao, nython, venomzera  |
|            3 |     9319 | 2023-12-05 | SAW                       | L   | 0.022      | -            | -                | -                | -         |    -0.08 | dav1deuS, DeStiNy, hardzao, nython, venomzera  |
|            2 |     9336 | 2023-12-04 | Sprout                    | W   | 0.017      | -            | -                | -                | -         |     0.05 | dav1deuS, DeStiNy, hardzao, nython, venomzera  |
|            1 |     9473 | 2023-12-02 | Legacy                    | W   | 0.004      | -            | -                | -                | -         |     0.06 | dav1deuS, DeStiNy, hardzao, nython, venomzera  |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($22,871.08)
- Divide that value by the 5th highest value among all rosters ($300,806.11)
- The final value (0.08) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-05-19 |      1.000 | $9,800.23      | $9,800.23       |
| 2024-03-18 |      0.718 | $3,500.00      | $2,511.25       |
| 2024-03-14 |      0.691 | $15,000.00     | $10,370.83      |
| 2023-12-07 |      0.038 | $5,000.00      | $188.77         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
