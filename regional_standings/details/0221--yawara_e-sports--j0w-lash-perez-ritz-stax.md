### Roster Details<br />
Team Name: Yawara E-Sports<br />
Roster: j0w, lash, perez, ritz, stAx<br />
Region: [Americas]( ../standings_americas.md)<br />
<br />
Global Rank: [221](../standings_global.md)<br />
Regional Rank: [39]( ../standings_americas.md)<br />
Final Rank Value:  695.1<br />
<br />
Final Rank Value (695.1) = Starting Rank Value (719.8) + Head To Head Adjustments (-24.7)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.304[<sup>1</sup>](#table2)
- Bounty Collected: 0.309[<sup>2</sup>](#table1)
- Opponent Network: 0.032[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.161<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 719.8
- 400 + ( ( 0.161 - 0.000 ) / ( 0.806 - 0.000 ) ) * 1600 = 719.8


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent                       | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins      | H2H Adj. | Roster                         |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           42 |        2 | 2024-05-05 | Looking4Org (Brazilian team)   | L   | 1.000      | -            | -                | -                | -             |   -18.04 | j0w, lash, perez, ritz, stAx   |
|           41 |       41 | 2024-05-04 | MIBR Academy                   | L   | 1.000      | -            | -                | -                | -             |   -15.20 | j0w, lash, perez, ritz, stAx   |
|           40 |      172 | 2024-05-01 | Looking4Org (Brazilian team)   | W   | 1.000      | 0.143        | 0.003 (0.000)    | 0.138 (0.020)    | false (0.000) |    12.58 | j0w, lash, perez, ritz, stAx   |
|           39 |      229 | 2024-04-30 | Bombril 1001 Utilidades        | W   | 1.000      | 0.143        | 0.007 (0.001)    | 0.157 (0.022)    | false (0.000) |    16.47 | j0w, lash, perez, ritz, stAx   |
|           38 |      680 | 2024-04-20 | Sensei Team                    | L   | 1.000      | -            | -                | -                | -             |   -14.07 | j0w, lash, perez, stAx, watts  |
|           37 |     1475 | 2024-04-04 | Vikings KR                     | L   | 0.992      | -            | -                | -                | -             |   -16.34 | j0w, lash, perez, stAx, watts  |
|           36 |     1629 | 2024-03-30 | MIBR Academy                   | L   | 0.960      | -            | -                | -                | -             |   -15.69 | j0w, lash, leleo, perez, stAx  |
|           35 |     1660 | 2024-03-29 | Romanticos                     | W   | 0.952      | 0.143        | 0.003 (0.000)    | 0.185 (0.025)    | false (0.000) |    11.41 | j0w, lash, leleo, perez, stAx  |
|           34 |     1684 | 2024-03-28 | Bombril 1001 Utilidades        | L   | 0.946      | -            | -                | -                | -             |   -15.33 | j0w, lash, leleo, perez, stAx  |
|           33 |     1837 | 2024-03-25 | 9z Academy                     | W   | 0.926      | 0.143        | 0.003 (0.000)    | 0.237 (0.031)    | false (0.000) |    10.03 | j0w, lash, leleo, perez, stAx  |
|           32 |     1841 | 2024-03-25 | Sensei Team                    | W   | 0.925      | 0.143        | 0.006 (0.001)    | 0.409 (0.054)    | false (0.000) |    14.70 | j0w, lash, perez, stAx, watts  |
|           31 |     1851 | 2024-03-24 | NIGERIA 96                     | W   | 0.919      | -            | -                | -                | false (0.000) |    10.43 | j0w, lash, leleo, perez, stAx  |
|           30 |     1933 | 2024-03-22 | Romanticos                     | W   | 0.906      | 0.143        | -                | 0.185 (0.024)    | false (0.000) |    12.54 | j0w, lash, leleo, perez, stAx  |
|           29 |     1970 | 2024-03-21 | 9z Academy                     | W   | 0.899      | 0.143        | 0.003 (0.000)    | 0.237 (0.030)    | false (0.000) |    11.98 | j0w, lash, perez, stAx, watts  |
|           28 |     2249 | 2024-03-14 | Dusty Roots                    | L   | 0.853      | -            | -                | -                | -             |   -15.16 | j0w, lash, leleo, perez, stAx  |
|           27 |     2294 | 2024-03-13 | Sharks Esports                 | L   | 0.846      | -            | -                | -                | -             |    -5.80 | j0w, lash, leleo, perez, stAx  |
|           26 |     2306 | 2024-03-13 | Case Esports                   | W   | 0.846      | 0.143        | 0.027 (0.003)    | 0.401 (0.048)    | false (0.000) |    17.25 | j0w, lash, leleo, perez, stAx  |
|           25 |     2405 | 2024-03-11 | Intense Game                   | L   | 0.832      | -            | -                | -                | -             |   -11.59 | j0w, lash, leleo, perez, stAx  |
|           24 |     2671 | 2024-03-05 | MIBR Academy                   | L   | 0.793      | -            | -                | -                | -             |   -10.20 | j0w, lash, leleo, perez, stAx  |
|           23 |     2752 | 2024-03-04 | Bombril 1001 Utilidades        | W   | 0.786      | 0.143        | 0.007 (0.001)    | -                | false (0.000) |    11.76 | j0w, lash, leleo, perez, stAx  |
|           22 |     2824 | 2024-03-02 | MIBR Academy                   | L   | 0.773      | -            | -                | -                | -             |   -10.05 | j0w, lash, leleo, perez, stAx  |
|           21 |     2935 | 2024-02-29 | Intense Game                   | L   | 0.759      | -            | -                | -                | -             |   -12.65 | j0w, lash, leleo, perez, stAx  |
|           20 |     2984 | 2024-02-28 | Sharks Youngsters              | W   | 0.752      | 0.143        | 0.004 (0.000)    | 0.211 (0.023)    | -             |    10.29 | j0w, lash, leleo, perez, stAx  |
|           19 |     3015 | 2024-02-27 | Bombril 1001 Utilidades        | L   | 0.746      | -            | -                | -                | -             |   -14.22 | j0w, lash, leleo, perez, stAx  |
|           18 |     3387 | 2024-02-19 | Sharks Esports                 | L   | 0.694      | -            | -                | -                | -             |    -6.19 | j0w, lash, leleo, perez, stAx  |
|           17 |     3613 | 2024-02-14 | Imperial Esports               | L   | 0.660      | -            | -                | -                | -             |    -0.22 | j0w, lash, leleo, perez, stAx  |
|           16 |     4131 | 2024-01-30 | Romanticos                     | W   | 0.560      | -            | -                | -                | -             |     7.79 | j0w, lash, PremiuM, ritz, stAx |
|           15 |     4181 | 2024-01-29 | 9z Academy                     | L   | 0.553      | -            | -                | -                | -             |   -10.19 | j0w, lash, PremiuM, ritz, stAx |
|           14 |     4245 | 2024-01-27 | ODDIK Academy                  | W   | 0.540      | -            | -                | -                | -             |     6.83 | j0w, lash, PremiuM, ritz, stAx |
|           13 |     4252 | 2024-01-27 | TEAM ORUGA                     | W   | 0.539      | -            | -                | -                | -             |     5.52 | j0w, lash, PremiuM, ritz, stAx |
|           12 |     4254 | 2024-01-27 | Romanticos                     | W   | 0.539      | -            | -                | -                | -             |     7.39 | j0w, lash, PremiuM, ritz, stAx |
|           11 |     4262 | 2024-01-27 | SOLOVE                         | W   | 0.539      | -            | -                | -                | -             |     6.28 | j0w, lash, PremiuM, ritz, stAx |
|           10 |     4305 | 2024-01-26 | Flamengo Esports               | L   | 0.532      | -            | -                | -                | -             |   -11.12 | j0w, lash, PremiuM, ritz, stAx |
|            9 |     4348 | 2024-01-25 | Imperial Esports               | W   | 0.527      | 0.143        | 0.674 (0.051)    | 0.549 (0.041)    | -             |    16.46 | j0w, lash, PremiuM, ritz, stAx |
|            8 |     5078 | 2024-01-09 | Case Esports                   | L   | 0.419      | -            | -                | -                | -             |    -6.20 | j0w, lash, ritz, stAx, syncmau |
|            7 |     5141 | 2024-01-08 | Formiguinhas                   | W   | 0.414      | -            | -                | -                | -             |     1.93 | j0w, lash, ritz, stAx, syncmau |
|            6 |     5582 | 2023-12-15 | SOLOVE                         | L   | 0.252      | -            | -                | -                | -             |    -5.04 | j0w, lash, ritz, stAx, syncmau |
|            5 |     5613 | 2023-12-14 | Arena Jogue Fácil Esports      | L   | 0.245      | -            | -                | -                | -             |    -4.32 | j0w, lash, ritz, stAx, syncmau |
|            4 |     5640 | 2023-12-13 | Hype E-Sports (Brazilian team) | W   | 0.239      | -            | -                | -                | -             |     2.35 | j0w, lash, ritz, stAx, syncmau |
|            3 |     6236 | 2023-11-29 | SEN Mouz                       | W   | 0.146      | -            | -                | -                | -             |     0.66 | j0w, lash, ritz, stAx, syncmau |
|            2 |     6697 | 2023-11-18 | Sharks Youngsters              | L   | 0.072      | -            | -                | -                | -             |    -1.28 | j0w, lcf, ritz, stAx, syncmau  |
|            1 |     7044 | 2023-11-11 | Sharks Youngsters              | L   | 0.026      | -            | -                | -                | -             |    -0.47 | j0w, lash, ritz, stAx, syncmau |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($804.41)
- Divide that value by the 5th highest value among all rosters ($158,437.64)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-05-05 |      1.000 | $128.04        | $128.04         |
| 2024-03-31 |      0.967 | $190.56        | $184.23         |
| 2024-03-06 |      0.799 | $191.59        | $153.05         |
| 2024-01-30 |      0.560 | $605.86        | $339.09         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
