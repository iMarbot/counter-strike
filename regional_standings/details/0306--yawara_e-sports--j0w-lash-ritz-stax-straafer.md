### Roster Details<br />
Team Name: Yawara E-Sports<br />
Roster: j0w, lash, ritz, stAx, Straafer<br />
Region: [Americas]( ../standings_americas.md)<br />
<br />
Global Rank: [306](../standings_global.md)<br />
Regional Rank: [70]( ../standings_americas.md)<br />
Final Rank Value:  639.3<br />
<br />
Final Rank Value (639.3) = Starting Rank Value (699.2) + Head To Head Adjustments (-59.9)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.273[<sup>1</sup>](#table2)
- Bounty Collected: 0.277[<sup>2</sup>](#table1)
- Opponent Network: 0.038[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.147<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 699.2
- 400 + ( ( 0.147 - 0.000 ) / ( 0.786 - 0.000 ) ) * 1600 = 699.2


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent                  | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                          |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           54 |       12 | 2024-05-29 | Vikings KR                | L   | 1.000      | -            | -                | -                | -         |   -11.66 | j0w, lash, ritz, stAx, Straafer |
|           53 |      108 | 2024-05-28 | w7m esports               | L   | 1.000      | -            | -                | -                | -         |   -12.93 | j0w, lash, ritz, stAx, Straafer |
|           52 |      651 | 2024-05-20 | eSports Recife            | W   | 1.000      | 0.143        | 0.002 (0.000)    | 0.441 (0.063)    | 0 (0.000) |    18.16 | j0w, lash, perez, ritz, stAx    |
|           51 |     1044 | 2024-05-16 | Corinthians Esports       | L   | 1.000      | -            | -                | -                | -         |   -12.06 | j0w, lash, perez, ritz, stAx    |
|           50 |     1048 | 2024-05-16 | OneMore eSports           | W   | 1.000      | -            | -                | -                | 0 (0.000) |    13.80 | j0w, lash, perez, ritz, stAx    |
|           49 |     1306 | 2024-05-13 | Galorys                   | L   | 1.000      | -            | -                | -                | -         |    -7.13 | j0w, lash, perez, ritz, stAx    |
|           48 |     1641 | 2024-05-08 | Intense Game              | L   | 1.000      | -            | -                | -                | -         |   -11.07 | j0w, lash, perez, ritz, stAx    |
|           47 |     1705 | 2024-05-06 | Team Solid                | L   | 1.000      | -            | -                | -                | -         |    -7.42 | j0w, lash, perez, ritz, stAx    |
|           46 |     1749 | 2024-05-05 | bebidarosa                | L   | 1.000      | -            | -                | -                | -         |   -18.58 | j0w, lash, perez, ritz, stAx    |
|           45 |     1796 | 2024-05-04 | MIBR Academy              | L   | 1.000      | -            | -                | -                | -         |   -14.76 | j0w, lash, perez, ritz, stAx    |
|           44 |     1949 | 2024-05-01 | bebidarosa                | W   | 1.000      | -            | -                | -                | 0 (0.000) |    13.20 | j0w, lash, perez, ritz, stAx    |
|           43 |     2014 | 2024-04-30 | Bombril 1001 Utilidades   | W   | 1.000      | 0.143        | 0.003 (0.000)    | 0.144 (0.021)    | 0 (0.000) |    15.81 | j0w, lash, perez, ritz, stAx    |
|           42 |     2050 | 2024-04-29 | 9z Academy                | L   | 0.998      | -            | -                | -                | -         |   -18.40 | j0w, lash, perez, ritz, stAx    |
|           41 |     2543 | 2024-04-20 | Sensei Team               | L   | 0.938      | -            | -                | -                | -         |   -12.60 | j0w, lash, perez, stAx, watts   |
|           40 |     3486 | 2024-04-04 | Vikings KR                | L   | 0.831      | -            | -                | -                | -         |   -13.06 | j0w, lash, perez, stAx, watts   |
|           39 |     3664 | 2024-03-30 | MIBR Academy              | L   | 0.799      | -            | -                | -                | -         |   -13.44 | j0w, lash, leleo, perez, stAx   |
|           38 |     3700 | 2024-03-29 | Romanticos                | W   | 0.791      | -            | -                | -                | 0 (0.000) |     9.36 | j0w, lash, leleo, perez, stAx   |
|           37 |     3726 | 2024-03-28 | Bombril 1001 Utilidades   | L   | 0.785      | -            | -                | -                | -         |   -14.34 | j0w, lash, leleo, perez, stAx   |
|           36 |     3886 | 2024-03-26 | paiN Gaming Academy       | L   | 0.771      | -            | -                | -                | -         |   -11.69 | j0w, lash, leleo, perez, stAx   |
|           35 |     3906 | 2024-03-25 | 9z Academy                | W   | 0.765      | 0.143        | 0.002 (0.000)    | 0.311 (0.034)    | 0 (0.000) |     8.06 | j0w, lash, leleo, perez, stAx   |
|           34 |     3916 | 2024-03-25 | Sensei Team               | W   | 0.764      | 0.143        | 0.003 (0.000)    | 0.482 (0.053)    | 0 (0.000) |    12.03 | j0w, lash, perez, stAx, watts   |
|           33 |     3932 | 2024-03-24 | NIGERIA 96                | W   | 0.758      | -            | -                | -                | 0 (0.000) |     8.12 | j0w, lash, leleo, perez, stAx   |
|           32 |     4026 | 2024-03-22 | Romanticos                | W   | 0.744      | -            | -                | -                | 0 (0.000) |     9.72 | j0w, lash, leleo, perez, stAx   |
|           31 |     4061 | 2024-03-21 | paiN Gaming Academy       | W   | 0.738      | 0.143        | 0.005 (0.000)    | 0.374 (0.039)    | 0 (0.000) |    12.70 | j0w, lash, perez, stAx, watts   |
|           30 |     4073 | 2024-03-21 | 9z Academy                | W   | 0.738      | 0.143        | -                | 0.311 (0.033)    | -         |    10.84 | j0w, lash, perez, stAx, watts   |
|           29 |     4410 | 2024-03-14 | Dusty Roots               | L   | 0.692      | -            | -                | -                | -         |   -12.45 | j0w, lash, leleo, perez, stAx   |
|           28 |     4460 | 2024-03-13 | Sharks Esports            | L   | 0.685      | -            | -                | -                | -         |    -4.84 | j0w, lash, leleo, perez, stAx   |
|           27 |     4475 | 2024-03-13 | Case Esports              | W   | 0.684      | 0.143        | 0.028 (0.003)    | 0.461 (0.045)    | -         |    15.29 | j0w, lash, leleo, perez, stAx   |
|           26 |     4535 | 2024-03-12 | w7m esports               | W   | 0.679      | 0.143        | 0.003 (0.000)    | 0.259 (0.025)    | -         |    14.64 | j0w, lash, leleo, perez, stAx   |
|           25 |     4598 | 2024-03-11 | Intense Game              | L   | 0.671      | -            | -                | -                | -         |    -9.38 | j0w, lash, leleo, perez, stAx   |
|           24 |     4932 | 2024-03-05 | MIBR Academy              | L   | 0.632      | -            | -                | -                | -         |    -8.57 | j0w, lash, leleo, perez, stAx   |
|           23 |     5032 | 2024-03-04 | Bombril 1001 Utilidades   | W   | 0.624      | 0.143        | 0.003 (0.000)    | -                | -         |     9.31 | j0w, lash, leleo, perez, stAx   |
|           22 |     5116 | 2024-03-02 | MIBR Academy              | L   | 0.612      | -            | -                | -                | -         |    -8.45 | j0w, lash, leleo, perez, stAx   |
|           21 |     5253 | 2024-02-29 | Intense Game              | L   | 0.598      | -            | -                | -                | -         |    -9.07 | j0w, lash, leleo, perez, stAx   |
|           20 |     5312 | 2024-02-28 | Sharks Youngsters         | W   | 0.591      | 0.143        | 0.003 (0.000)    | 0.422 (0.036)    | -         |     8.64 | j0w, lash, leleo, perez, stAx   |
|           19 |     5349 | 2024-02-27 | Bombril 1001 Utilidades   | L   | 0.584      | -            | -                | -                | -         |   -10.59 | j0w, lash, leleo, perez, stAx   |
|           18 |     5806 | 2024-02-19 | Sharks Esports            | L   | 0.533      | -            | -                | -                | -         |    -3.87 | j0w, lash, leleo, perez, stAx   |
|           17 |     6079 | 2024-02-14 | Imperial Esports          | L   | 0.499      | -            | -                | -                | -         |    -0.17 | j0w, lash, leleo, perez, stAx   |
|           16 |     6744 | 2024-01-30 | Romanticos                | W   | 0.399      | -            | -                | -                | -         |     5.73 | j0w, lash, PremiuM, ritz, stAx  |
|           15 |     6808 | 2024-01-29 | 9z Academy                | L   | 0.392      | -            | -                | -                | -         |    -6.82 | j0w, lash, PremiuM, ritz, stAx  |
|           14 |     6915 | 2024-01-27 | ODDIK Academy             | W   | 0.379      | -            | -                | -                | -         |     5.28 | j0w, lash, PremiuM, ritz, stAx  |
|           13 |     6927 | 2024-01-27 | TEAM ORUGA                | W   | 0.378      | -            | -                | -                | -         |     4.50 | j0w, lash, PremiuM, ritz, stAx  |
|           12 |     6933 | 2024-01-27 | Romanticos                | W   | 0.378      | -            | -                | -                | -         |     5.22 | j0w, lash, PremiuM, ritz, stAx  |
|           11 |     6948 | 2024-01-27 | SOLOVE                    | W   | 0.378      | -            | -                | -                | -         |     4.59 | j0w, lash, PremiuM, ritz, stAx  |
|           10 |     7021 | 2024-01-26 | Flamengo Esports          | L   | 0.371      | -            | -                | -                | -         |    -7.85 | j0w, lash, PremiuM, ritz, stAx  |
|            9 |     7072 | 2024-01-25 | Imperial Esports          | W   | 0.366      | 0.143        | 0.372 (0.019)    | 0.582 (0.030)    | -         |    11.43 | j0w, lash, PremiuM, ritz, stAx  |
|            8 |     7113 | 2024-01-24 | Projeto KinGui            | L   | 0.358      | -            | -                | -                | -         |    -8.55 | j0w, lash, PremiuM, ritz, stAx  |
|            7 |     8068 | 2024-01-09 | Case Esports              | L   | 0.258      | -            | -                | -                | -         |    -4.15 | j0w, lash, ritz, stAx, syncmau  |
|            6 |     8160 | 2024-01-08 | Formiguinhas              | W   | 0.253      | -            | -                | -                | -         |     1.28 | j0w, lash, ritz, stAx, syncmau  |
|            5 |     8741 | 2023-12-15 | SOLOVE                    | L   | 0.091      | -            | -                | -                | -         |    -1.78 | j0w, lash, ritz, stAx, syncmau  |
|            4 |     8789 | 2023-12-14 | Arena Jogue Fácil Esports | L   | 0.084      | -            | -                | -                | -         |    -1.67 | j0w, lash, ritz, stAx, syncmau  |
|            3 |     8826 | 2023-12-13 | Bombril 1001 Utilidades   | W   | 0.078      | -            | -                | -                | -         |     0.96 | j0w, lash, ritz, stAx, syncmau  |
|            2 |     8868 | 2023-12-12 | MIBR Academy              | L   | 0.071      | -            | -                | -                | -         |    -1.15 | j0w, lash, ritz, stAx, syncmau  |
|            1 |     9436 | 2023-12-02 | w7m esports               | L   | 0.005      | -            | -                | -                | -         |    -0.11 | j0w, lash, ritz, stAx, syncmau  |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($645.42)
- Divide that value by the 5th highest value among all rosters ($300,806.11)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-05-07 |      1.000 | $128.04        | $128.04         |
| 2024-03-31 |      0.805 | $190.56        | $153.48         |
| 2024-03-06 |      0.639 | $191.59        | $122.39         |
| 2024-01-30 |      0.399 | $605.86        | $241.50         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
