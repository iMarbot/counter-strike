### Roster Details<br />
Team Name: RED Canids<br />
Roster: coldzera, dav1deuS, hardzao, nython, venomzera<br />
Region: [Americas]( ../standings_americas.md)<br />
<br />
Global Rank: [41](../standings_global.md)<br />
Regional Rank: [9]( ../standings_americas.md)<br />
Final Rank Value:  1108.7<br />
<br />
Final Rank Value (1108.7) = Starting Rank Value (989.8) + Head To Head Adjustments (118.9)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.472[<sup>1</sup>](#table2)
- Bounty Collected: 0.423[<sup>2</sup>](#table1)
- Opponent Network: 0.202[<sup>2</sup>](#table1)
- LAN Wins: 0.064[<sup>2</sup>](#table1)

The average of these factors is 0.290<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 989.8
- 400 + ( ( 0.290 - 0.000 ) / ( 0.787 - 0.000 ) ) * 1600 = 989.8


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
|           74 |      551 | 2024-05-21 | Sharks Esports            | L   | 1.000      | -            | -                | -                | -         |   -22.40 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           73 |      554 | 2024-05-21 | Sharks Esports            | W   | 1.000      | 0.450        | 0.019 (0.009)    | 0.381 (0.172)    | 0 (0.000) |     8.63 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           72 |      648 | 2024-05-20 | Fluxo                     | L   | 1.000      | -            | -                | -                | -         |   -17.26 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           71 |      652 | 2024-05-20 | Fluxo                     | W   | 1.000      | 0.450        | 0.065 (0.029)    | 0.474 (0.213)    | 0 (0.000) |    14.11 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           70 |      747 | 2024-05-19 | 9z Team                   | W   | 1.000      | 0.143        | 0.107 (0.015)    | -                | 0 (0.000) |    21.26 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           69 |      833 | 2024-05-18 | ODDIK                     | W   | 1.000      | -            | -                | -                | 0 (0.000) |     8.60 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           68 |     1052 | 2024-05-16 | Fluxo                     | W   | 1.000      | 0.143        | 0.065 (0.009)    | -                | 0 (0.000) |    16.93 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           67 |     1134 | 2024-05-15 | 9z Team                   | L   | 1.000      | -            | -                | -                | -         |    -9.04 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           66 |     1136 | 2024-05-15 | 9z Team                   | W   | 1.000      | 0.450        | 0.107 (0.048)    | 0.547 (0.246)    | 0 (0.000) |    22.98 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           65 |     1240 | 2024-05-14 | Corinthians Esports       | W   | 1.000      | 0.450        | -                | 0.458 (0.206)    | 0 (0.000) |     3.19 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           64 |     1244 | 2024-05-14 | Corinthians Esports       | W   | 1.000      | 0.450        | -                | 0.458 (0.206)    | 0 (0.000) |     3.29 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           63 |     1265 | 2024-05-14 | BESTIA                    | W   | 1.000      | -            | -                | -                | 0 (0.000) |     9.86 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           62 |     1310 | 2024-05-13 | Sharks Esports            | L   | 1.000      | -            | -                | -                | -         |   -20.29 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           61 |     1351 | 2024-05-12 | Vikings KR                | W   | 1.000      | -            | -                | -                | -         |     3.96 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           60 |     1359 | 2024-05-12 | FURIA Academy             | W   | 1.000      | -            | -                | -                | -         |     2.54 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           59 |     1535 | 2024-05-10 | paiN Gaming               | L   | 1.000      | -            | -                | -                | -         |    -2.79 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           58 |     1563 | 2024-05-09 | Intense Game              | W   | 1.000      | 0.435        | -                | 0.334 (0.145)    | -         |     5.05 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           57 |     1611 | 2024-05-08 | paiN Gaming               | L   | 1.000      | -            | -                | -                | -         |    -2.44 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           56 |     1613 | 2024-05-08 | paiN Gaming               | W   | 1.000      | 0.450        | 0.463 (0.209)    | 0.547 (0.246)    | -         |    29.40 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           55 |     1618 | 2024-05-08 | Team Solid                | L   | 1.000      | -            | -                | -                | -         |   -22.50 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           54 |     1757 | 2024-05-06 | Intense Game              | W   | 1.000      | 0.435        | -                | 0.334 (0.145)    | -         |     5.13 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           53 |     2333 | 2024-04-25 | BESTIA                    | W   | 0.972      | 0.450        | 0.026 (0.011)    | 0.500 (0.219)    | -         |     7.60 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           52 |     2334 | 2024-04-25 | BESTIA                    | W   | 0.972      | 0.450        | 0.026 (0.011)    | 0.500 (0.219)    | -         |     8.11 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           51 |     2859 | 2024-04-17 | MIBR                      | L   | 0.918      | -            | -                | -                | -         |    -1.39 | dav1deuS, hardzao, nython, righi, venomzera    |
|           50 |     2870 | 2024-04-17 | O Plano                   | W   | 0.918      | -            | -                | -                | -         |     1.77 | dav1deuS, hardzao, nython, righi, venomzera    |
|           49 |     2952 | 2024-04-16 | LaChampionsLiga           | W   | 0.912      | -            | -                | -                | -         |     1.69 | dav1deuS, hardzao, nython, righi, venomzera    |
|           48 |     3069 | 2024-04-13 | Imperial Esports          | L   | 0.892      | -            | -                | -                | -         |    -2.29 | dav1deuS, hardzao, nython, righi, venomzera    |
|           47 |     3139 | 2024-04-12 | w7m esports               | W   | 0.884      | -            | -                | -                | -         |     6.53 | dav1deuS, hardzao, nython, righi, venomzera    |
|           46 |     3231 | 2024-04-10 | paiN Gaming               | L   | 0.871      | -            | -                | -                | -         |    -1.37 | dav1deuS, hardzao, nython, righi, venomzera    |
|           45 |     3309 | 2024-04-09 | MIBR                      | L   | 0.864      | -            | -                | -                | -         |    -1.61 | dav1deuS, hardzao, nython, righi, venomzera    |
|           44 |     3356 | 2024-04-08 | BESTIA                    | W   | 0.858      | -            | -                | -                | -         |     9.32 | dav1deuS, hardzao, nython, righi, venomzera    |
|           43 |     3407 | 2024-04-07 | Imperial Esports          | L   | 0.852      | -            | -                | -                | -         |    -1.79 | dav1deuS, hardzao, nython, righi, venomzera    |
|           42 |     3456 | 2024-04-06 | w7m esports               | L   | 0.844      | -            | -                | -                | -         |   -20.69 | dav1deuS, hardzao, nython, righi, venomzera    |
|           41 |     3589 | 2024-04-04 | Fluxo                     | W   | 0.830      | -            | -                | -                | -         |    12.50 | dav1deuS, hardzao, nython, righi, venomzera    |
|           40 |     4308 | 2024-03-18 | ODDIK                     | W   | 0.718      | -            | -                | -                | -         |     8.67 | dav1deuS, DeStiNy, hardzao, nython, venomzera  |
|           39 |     4408 | 2024-03-16 | ODDIK                     | W   | 0.705      | -            | -                | -                | -         |     8.80 | dav1deuS, DeStiNy, hardzao, nython, venomzera  |
|           38 |     4469 | 2024-03-15 | Case Esports              | W   | 0.698      | -            | -                | -                | -         |     6.09 | dav1deuS, DeStiNy, hardzao, nython, venomzera  |
|           37 |     4528 | 2024-03-14 | Team Solid                | L   | 0.691      | -            | -                | -                | -         |   -15.26 | dav1deuS, DeStiNy, hardzao, nython, venomzera  |
|           36 |     4547 | 2024-03-14 | Flamengo Esports          | W   | 0.690      | -            | -                | -                | -         |     1.45 | dav1deuS, DeStiNy, hardzao, nython, venomzera  |
|           35 |     4581 | 2024-03-13 | Case Esports              | W   | 0.685      | 0.435        | 0.028 (0.008)    | -                | -         |     5.82 | dav1deuS, DeStiNy, hardzao, nython, venomzera  |
|           34 |     4600 | 2024-03-13 | Galorys                   | W   | 0.684      | -            | -                | -                | -         |     4.96 | dav1deuS, DeStiNy, hardzao, nython, venomzera  |
|           33 |     4663 | 2024-03-12 | Full House Gaming         | W   | 0.679      | -            | -                | -                | -         |     2.51 | dav1deuS, DeStiNy, hardzao, nython, venomzera  |
|           32 |     4725 | 2024-03-11 | Corinthians Esports       | W   | 0.671      | -            | -                | -                | -         |     2.62 | dav1deuS, DeStiNy, hardzao, nython, venomzera  |
|           31 |     4814 | 2024-03-09 | w7m esports               | W   | 0.659      | -            | -                | -                | -         |     5.75 | dav1deuS, DeStiNy, hardzao, nython, venomzera  |
|           30 |     4913 | 2024-03-07 | VELOX Argentina           | W   | 0.646      | -            | -                | -                | -         |     1.69 | dav1deuS, DeStiNy, hardzao, nython, venomzera  |
|           29 |     5217 | 2024-03-03 | ODDIK                     | L   | 0.618      | -            | -                | -                | -         |   -11.32 | dav1deuS, DeStiNy, hardzao, nython, venomzera  |
|           28 |     5333 | 2024-03-02 | paiN Gaming               | L   | 0.610      | -            | -                | -                | -         |    -0.76 | dav1deuS, DeStiNy, hardzao, nython, venomzera  |
|           27 |     5369 | 2024-03-01 | Wildcard Gaming           | W   | 0.605      | -            | -                | -                | 1 (0.605) |     7.47 | dav1deuS, DeStiNy, hardzao, nython, venomzera  |
|           26 |     6319 | 2024-02-13 | Imperial Esports          | L   | 0.493      | -            | -                | -                | -         |    -0.83 | dav1deuS, DeStiNy, hardzao, nython, venomzera  |
|           25 |     6320 | 2024-02-13 | Imperial Esports          | W   | 0.492      | 0.450        | 0.372 (0.082)    | -                | -         |    14.77 | dav1deuS, DeStiNy, hardzao, nython, venomzera  |
|           24 |     6853 | 2024-02-01 | w7m esports               | L   | 0.413      | -            | -                | -                | -         |    -9.81 | dav1deuS, DeStiNy, hardzao, nython, venomzera  |
|           23 |     6856 | 2024-02-01 | paiN Gaming               | L   | 0.412      | -            | -                | -                | -         |    -0.44 | dav1deuS, DeStiNy, hardzao, nython, venomzera  |
|           22 |     7239 | 2024-01-26 | FURIA Academy             | W   | 0.372      | -            | -                | -                | -         |     0.98 | dav1deuS, DeStiNy, hardzao, nython, venomzera  |
|           21 |     7241 | 2024-01-26 | Fluxo                     | W   | 0.371      | -            | -                | -                | -         |     5.43 | dav1deuS, DeStiNy, hardzao, nython, venomzera  |
|           20 |     7296 | 2024-01-25 | Intense Game              | W   | 0.366      | -            | -                | -                | -         |     1.20 | dav1deuS, DeStiNy, hardzao, nython, venomzera  |
|           19 |     7444 | 2024-01-22 | w7m esports               | L   | 0.346      | -            | -                | -                | -         |    -8.46 | dav1deuS, DeStiNy, hardzao, nython, venomzera  |
|           18 |     7499 | 2024-01-21 | 9z Team                   | W   | 0.340      | -            | -                | -                | -         |     8.82 | dav1deuS, DeStiNy, hardzao, nython, venomzera  |
|           17 |     7501 | 2024-01-21 | Flamengo Esports          | W   | 0.339      | -            | -                | -                | -         |     0.87 | dav1deuS, DeStiNy, hardzao, nython, venomzera  |
|           16 |     7506 | 2024-01-21 | ODDIK                     | L   | 0.338      | -            | -                | -                | -         |    -6.13 | dav1deuS, DeStiNy, hardzao, nython, venomzera  |
|           15 |     7556 | 2024-01-20 | Legacy                    | L   | 0.331      | -            | -                | -                | -         |    -4.79 | dav1deuS, DeStiNy, hardzao, nython, venomzera  |
|           14 |     7631 | 2024-01-19 | Fluxo                     | W   | 0.326      | -            | -                | -                | -         |     4.84 | dav1deuS, DeStiNy, hardzao, nython, venomzera  |
|           13 |     7643 | 2024-01-19 | Case Esports              | W   | 0.324      | -            | -                | -                | -         |     1.61 | dav1deuS, DeStiNy, hardzao, nython, venomzera  |
|           12 |     7756 | 2024-01-17 | Sharks Esports            | L   | 0.312      | -            | -                | -                | -         |    -6.13 | dav1deuS, DeStiNy, hardzao, nython, venomzera  |
|           11 |     7791 | 2024-01-17 | 9z Team                   | L   | 0.311      | -            | -                | -                | -         |    -1.83 | dav1deuS, DeStiNy, hardzao, nython, venomzera  |
|           10 |     7860 | 2024-01-16 | Legacy                    | W   | 0.306      | -            | -                | -                | -         |     5.04 | dav1deuS, DeStiNy, hardzao, nython, venomzera  |
|            9 |     7868 | 2024-01-16 | Case Esports              | W   | 0.305      | -            | -                | -                | -         |     1.52 | dav1deuS, DeStiNy, hardzao, nython, venomzera  |
|            8 |     7876 | 2024-01-16 | adalYamigos               | W   | 0.305      | -            | -                | -                | -         |     1.29 | dav1deuS, DeStiNy, hardzao, nython, venomzera  |
|            7 |     7954 | 2024-01-15 | Arena Jogue Fácil Esports | W   | 0.299      | -            | -                | -                | -         |     0.97 | dav1deuS, DeStiNy, hardzao, nython, venomzera  |
|            6 |     7999 | 2024-01-14 | paiN Gaming               | L   | 0.292      | -            | -                | -                | -         |    -0.24 | dav1deuS, DeStiNy, hardzao, nython, venomzera  |
|            5 |     8003 | 2024-01-14 | Legacy                    | W   | 0.292      | -            | -                | -                | -         |     4.80 | dav1deuS, DeStiNy, hardzao, nython, venomzera  |
|            4 |     8024 | 2024-01-13 | E-Xolos LAZER             | W   | 0.286      | -            | -                | -                | -         |     0.32 | dav1deuS, DeStiNy, hardzao, nython, venomzera  |
|            3 |     9601 | 2023-12-05 | SAW                       | L   | 0.022      | -            | -                | -                | -         |    -0.08 | dav1deuS, DeStiNy, hardzao, nython, venomzera  |
|            2 |     9618 | 2023-12-04 | Sprout                    | W   | 0.017      | -            | -                | -                | -         |     0.05 | dav1deuS, DeStiNy, hardzao, nython, venomzera  |
|            1 |     9755 | 2023-12-02 | Legacy                    | W   | 0.004      | -            | -                | -                | -         |     0.06 | dav1deuS, DeStiNy, hardzao, nython, venomzera  |

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
