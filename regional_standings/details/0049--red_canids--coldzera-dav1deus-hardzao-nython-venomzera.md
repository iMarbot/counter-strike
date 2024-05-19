### Roster Details<br />
Team Name: RED Canids<br />
Roster: coldzera, dav1deuS, hardzao, nython, venomzera<br />
Region: [Americas]( ../standings_americas.md)<br />
<br />
Global Rank: [49](../standings_global.md)<br />
Regional Rank: [10]( ../standings_americas.md)<br />
Final Rank Value:  1028.8<br />
<br />
Final Rank Value (1028.8) = Starting Rank Value (919.2) + Head To Head Adjustments (109.6)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.509[<sup>1</sup>](#table2)
- Bounty Collected: 0.333[<sup>2</sup>](#table1)
- Opponent Network: 0.119[<sup>2</sup>](#table1)
- LAN Wins: 0.085[<sup>2</sup>](#table1)

The average of these factors is 0.262<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 919.2
- 400 + ( ( 0.262 - 0.000 ) / ( 0.806 - 0.000 ) ) * 1600 = 919.2


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent                  | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins      | H2H Adj. | Roster                                         |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           47 |      458 | 2024-04-25 | BESTIA                    | W   | 1.000      | 0.450        | 0.026 (0.012)    | 0.423 (0.191)    | false (0.000) |     6.45 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           46 |      459 | 2024-04-25 | BESTIA                    | W   | 1.000      | 0.450        | 0.026 (0.012)    | 0.423 (0.191)    | false (0.000) |     6.84 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           45 |      914 | 2024-04-17 | MIBR                      | L   | 1.000      | -            | -                | -                | -             |    -1.39 | dav1deuS, hardzao, nython, righi, venomzera    |
|           44 |      921 | 2024-04-17 | O Plano                   | W   | 1.000      | -            | -                | -                | false (0.000) |     2.05 | dav1deuS, hardzao, nython, righi, venomzera    |
|           43 |      992 | 2024-04-16 | LaChampionsLiga           | W   | 1.000      | -            | -                | -                | false (0.000) |     1.70 | dav1deuS, hardzao, nython, righi, venomzera    |
|           42 |     1087 | 2024-04-13 | Imperial Esports          | L   | 1.000      | -            | -                | -                | -             |    -2.19 | dav1deuS, hardzao, nython, righi, venomzera    |
|           41 |     1278 | 2024-04-09 | MIBR                      | L   | 1.000      | -            | -                | -                | -             |    -1.66 | dav1deuS, hardzao, nython, righi, venomzera    |
|           40 |     1317 | 2024-04-08 | BESTIA                    | W   | 1.000      | -            | -                | -                | false (0.000) |     8.52 | dav1deuS, hardzao, nython, righi, venomzera    |
|           39 |     1324 | 2024-04-08 | Bounty Hunters Esports    | W   | 1.000      | 0.435        | -                | 0.276 (0.120)    | false (0.000) |     2.78 | dav1deuS, hardzao, nython, righi, venomzera    |
|           38 |     1362 | 2024-04-07 | Imperial Esports          | L   | 1.000      | -            | -                | -                | -             |    -1.71 | dav1deuS, hardzao, nython, righi, venomzera    |
|           37 |     1491 | 2024-04-04 | Fluxo                     | W   | 0.991      | 0.143        | 0.153 (0.022)    | 0.484 (0.068)    | false (0.000) |    16.10 | dav1deuS, hardzao, nython, righi, venomzera    |
|           36 |     2086 | 2024-03-18 | ODDIK                     | W   | 0.879      | 0.303        | -                | 0.402 (0.107)    | false (0.000) |    11.03 | dav1deuS, DeStiNy, hardzao, nython, venomzera  |
|           35 |     2163 | 2024-03-16 | ODDIK                     | W   | 0.866      | 0.303        | -                | 0.402 (0.105)    | false (0.000) |    11.35 | dav1deuS, DeStiNy, hardzao, nython, venomzera  |
|           34 |     2203 | 2024-03-15 | Case Esports              | W   | 0.859      | 0.303        | 0.027 (0.007)    | 0.401 (0.104)    | -             |     7.55 | dav1deuS, DeStiNy, hardzao, nython, venomzera  |
|           33 |     2253 | 2024-03-14 | Team Solid                | L   | 0.852      | -            | -                | -                | -             |   -18.57 | dav1deuS, DeStiNy, hardzao, nython, venomzera  |
|           32 |     2271 | 2024-03-14 | Flamengo Esports          | W   | 0.851      | -            | -                | -                | -             |     2.55 | dav1deuS, DeStiNy, hardzao, nython, venomzera  |
|           31 |     2300 | 2024-03-13 | Case Esports              | W   | 0.846      | 0.435        | 0.027 (0.010)    | 0.401 (0.148)    | -             |     7.21 | dav1deuS, DeStiNy, hardzao, nython, venomzera  |
|           30 |     2314 | 2024-03-13 | Galorys                   | W   | 0.845      | 0.143        | 0.048 (0.006)    | 0.598 (0.072)    | -             |     7.80 | dav1deuS, DeStiNy, hardzao, nython, venomzera  |
|           29 |     2361 | 2024-03-12 | Full House Gaming         | W   | 0.840      | -            | -                | -                | -             |     3.98 | dav1deuS, DeStiNy, hardzao, nython, venomzera  |
|           28 |     2410 | 2024-03-11 | Corinthians Esports       | W   | 0.832      | 0.303        | -                | 0.346 (0.087)    | -             |     4.07 | dav1deuS, DeStiNy, hardzao, nython, venomzera  |
|           27 |     2552 | 2024-03-07 | VELOX Argentina           | W   | 0.807      | -            | -                | -                | -             |     3.49 | dav1deuS, DeStiNy, hardzao, nython, venomzera  |
|           26 |     2788 | 2024-03-03 | ODDIK                     | L   | 0.779      | -            | -                | -                | -             |   -13.63 | dav1deuS, DeStiNy, hardzao, nython, venomzera  |
|           25 |     2905 | 2024-03-01 | Wildcard Gaming           | W   | 0.766      | -            | -                | -                | true (0.766)  |    10.63 | dav1deuS, DeStiNy, hardzao, nython, venomzera  |
|           24 |     4304 | 2024-01-26 | Fluxo                     | W   | 0.532      | 0.143        | 0.153 (0.012)    | -                | -             |     9.70 | dav1deuS, DeStiNy, hardzao, nython, venomzera  |
|           23 |     4347 | 2024-01-25 | Intense Game              | W   | 0.527      | -            | -                | -                | -             |     3.31 | dav1deuS, DeStiNy, hardzao, nython, venomzera  |
|           22 |     4494 | 2024-01-21 | 9z Team                   | W   | 0.501      | 0.143        | 0.057 (0.004)    | -                | -             |     8.38 | dav1deuS, DeStiNy, hardzao, nython, venomzera  |
|           21 |     4495 | 2024-01-21 | Flamengo Esports          | W   | 0.500      | -            | -                | -                | -             |     2.02 | dav1deuS, DeStiNy, hardzao, nython, venomzera  |
|           20 |     4497 | 2024-01-21 | ODDIK                     | L   | 0.499      | -            | -                | -                | -             |    -8.26 | dav1deuS, DeStiNy, hardzao, nython, venomzera  |
|           19 |     4534 | 2024-01-20 | Legacy                    | L   | 0.492      | -            | -                | -                | -             |    -4.43 | dav1deuS, DeStiNy, hardzao, nython, venomzera  |
|           18 |     4587 | 2024-01-19 | Fluxo                     | W   | 0.487      | 0.143        | 0.153 (0.011)    | -                | -             |     9.65 | dav1deuS, DeStiNy, hardzao, nython, venomzera  |
|           17 |     4596 | 2024-01-19 | Case Esports              | W   | 0.486      | -            | -                | -                | -             |     3.69 | dav1deuS, DeStiNy, hardzao, nython, venomzera  |
|           16 |     4688 | 2024-01-17 | Sharks Esports            | L   | 0.473      | -            | -                | -                | -             |    -8.17 | dav1deuS, DeStiNy, hardzao, nython, venomzera  |
|           15 |     4719 | 2024-01-17 | 9z Team                   | L   | 0.472      | -            | -                | -                | -             |    -7.72 | dav1deuS, DeStiNy, hardzao, nython, venomzera  |
|           14 |     4770 | 2024-01-16 | Legacy                    | W   | 0.467      | -            | -                | -                | -             |    10.62 | dav1deuS, DeStiNy, hardzao, nython, venomzera  |
|           13 |     4775 | 2024-01-16 | Case Esports              | W   | 0.466      | -            | -                | -                | -             |     3.57 | dav1deuS, DeStiNy, hardzao, nython, venomzera  |
|           12 |     4829 | 2024-01-15 | Arena Jogue Fácil Esports | W   | 0.460      | -            | -                | -                | -             |     2.81 | dav1deuS, DeStiNy, hardzao, nython, venomzera  |
|           11 |     4866 | 2024-01-14 | Legacy                    | W   | 0.453      | -            | -                | -                | -             |    10.47 | dav1deuS, DeStiNy, hardzao, nython, venomzera  |
|           10 |     4878 | 2024-01-13 | E-Xolos LAZER             | W   | 0.447      | -            | -                | -                | -             |     0.74 | dav1deuS, DeStiNy, hardzao, nython, venomzera  |
|            9 |     6007 | 2023-12-05 | SAW                       | L   | 0.183      | -            | -                | -                | -             |    -0.23 | dav1deuS, DeStiNy, hardzao, nython, venomzera  |
|            8 |     6109 | 2023-12-02 | Legacy                    | W   | 0.165      | 0.589        | 0.061 (0.006)    | -                | -             |     3.95 | dav1deuS, DeStiNy, hardzao, nython, venomzera  |
|            7 |     6216 | 2023-11-30 | Into The Breach           | L   | 0.151      | -            | -                | -                | -             |    -3.07 | dav1deuS, DeStiNy, hardzao, nython, venomzera  |
|            6 |     6482 | 2023-11-24 | Case Esports              | L   | 0.111      | -            | -                | -                | -             |    -2.67 | dav1deuS, DeStiNy, hardzao, nython, venomzera  |
|            5 |     6506 | 2023-11-23 | 9z Team                   | L   | 0.105      | -            | -                | -                | -             |    -1.61 | dav1deuS, DeStiNy, hardzao, nython, venomzera  |
|            4 |     6629 | 2023-11-20 | Sharks Esports            | W   | 0.085      | -            | -                | -                | -             |     1.24 | dav1deuS, DeStiNy, hardzao, nython, venomzera  |
|            3 |     6706 | 2023-11-18 | Flamengo Esports          | W   | 0.072      | -            | -                | -                | -             |     0.23 | dav1deuS, DeStiNy, hardzao, nython, venomzera  |
|            2 |     6909 | 2023-11-14 | Flamengo Esports          | W   | 0.046      | -            | -                | -                | -             |     0.15 | dav1deuS, DeStiNy, hardzao, nython, venomzera  |
|            1 |     6996 | 2023-11-12 | Case Esports              | W   | 0.032      | -            | -                | -                | -             |     0.24 | dav1deuS, DeStiNy, hardzao, nython, venomzera  |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($17,154.19)
- Divide that value by the 5th highest value among all rosters ($158,437.64)
- The final value (0.11) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-03-18 |      0.879 | $3,500.00      | $3,074.98       |
| 2024-03-14 |      0.852 | $15,000.00     | $12,786.81      |
| 2023-12-07 |      0.199 | $5,000.00      | $994.10         |
| 2023-11-20 |      0.085 | $3,500.00      | $298.31         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
