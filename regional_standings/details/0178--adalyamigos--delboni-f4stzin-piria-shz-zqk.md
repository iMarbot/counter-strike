### Roster Details<br />
Team Name: adalYamigos<br />
Roster: delboNi, f4stzin, piria, shz, zqk<br />
Region: [Americas]( ../standings_americas.md)<br />
<br />
Global Rank: [178](../standings_global.md)<br />
Regional Rank: [36]( ../standings_americas.md)<br />
Final Rank Value:  750.1<br />
<br />
Final Rank Value (750.1) = Starting Rank Value (630.5) + Head To Head Adjustments (119.7)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.000[<sup>1</sup>](#table2)
- Bounty Collected: 0.318[<sup>2</sup>](#table1)
- Opponent Network: 0.135[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.113<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 630.5
- 400 + ( ( 0.113 - 0.000 ) / ( 0.787 - 0.000 ) ) * 1600 = 630.5


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
|           38 |     3126 | 2024-04-12 | Case Esports        | L   | 0.885      | -            | -                | -                | -         |   -11.20 | delboNi, f4stzin, piria, shz, zqk |
|           37 |     3168 | 2024-04-11 | Imperial Esports    | L   | 0.879      | -            | -                | -                | -         |    -0.53 | delboNi, f4stzin, piria, shz, zqk |
|           36 |     3299 | 2024-04-09 | MIBR                | L   | 0.865      | -            | -                | -                | -         |    -0.37 | delboNi, f4stzin, piria, shz, zqk |
|           35 |     3306 | 2024-04-09 | MIBR                | L   | 0.865      | -            | -                | -                | -         |    -0.37 | delboNi, f4stzin, piria, shz, zqk |
|           34 |     3406 | 2024-04-07 | Case Esports        | W   | 0.852      | 0.435        | 0.028 (0.011)    | 0.470 (0.174)    | 0 (0.000) |    16.10 | delboNi, f4stzin, piria, shz, zqk |
|           33 |     3517 | 2024-04-05 | 2Game Esports       | L   | 0.838      | -            | -                | -                | -         |   -16.71 | delboNi, f4stzin, piria, shz, zqk |
|           32 |     3519 | 2024-04-05 | 2Game Esports       | W   | 0.838      | 0.450        | 0.003 (0.001)    | 0.212 (0.080)    | 0 (0.000) |     9.60 | delboNi, f4stzin, piria, shz, zqk |
|           31 |     3554 | 2024-04-04 | BESTIA              | W   | 0.832      | 0.450        | 0.026 (0.010)    | 0.500 (0.187)    | 0 (0.000) |    19.41 | delboNi, f4stzin, piria, shz, zqk |
|           30 |     3564 | 2024-04-04 | BESTIA              | L   | 0.832      | -            | -                | -                | -         |    -6.58 | delboNi, f4stzin, piria, shz, zqk |
|           29 |     4664 | 2024-03-12 | Team Solid          | L   | 0.679      | -            | -                | -                | -         |    -7.93 | delboNi, f4stzin, piria, shz, zqk |
|           28 |     4764 | 2024-03-10 | BESTIA              | W   | 0.666      | 0.435        | 0.026 (0.008)    | 0.500 (0.145)    | 0 (0.000) |    16.17 | delboNi, f4stzin, piria, shz, zqk |
|           27 |     4875 | 2024-03-08 | Flamengo Esports    | W   | 0.651      | -            | -                | -                | 0 (0.000) |     5.50 | delboNi, f4stzin, piria, shz, zqk |
|           26 |     5069 | 2024-03-05 | Case Esports        | W   | 0.633      | 0.450        | 0.028 (0.008)    | 0.470 (0.134)    | 0 (0.000) |    13.18 | delboNi, f4stzin, piria, shz, zqk |
|           25 |     5070 | 2024-03-05 | Case Esports        | W   | 0.632      | 0.450        | 0.028 (0.008)    | 0.470 (0.134)    | 0 (0.000) |    13.84 | delboNi, f4stzin, piria, shz, zqk |
|           24 |     5848 | 2024-02-21 | Galorys             | W   | 0.546      | 0.450        | 0.022 (0.005)    | 0.600 (0.147)    | 0 (0.000) |    11.14 | delboNi, f4stzin, piria, shz, zqk |
|           23 |     5850 | 2024-02-21 | Galorys             | W   | 0.546      | 0.450        | 0.022 (0.005)    | 0.600 (0.147)    | 0 (0.000) |    11.63 | delboNi, f4stzin, piria, shz, zqk |
|           22 |     6033 | 2024-02-18 | Team Solid          | L   | 0.525      | -            | -                | -                | -         |    -4.37 | delboNi, f4stzin, piria, shz, zqk |
|           21 |     6097 | 2024-02-17 | Imperial Esports    | L   | 0.518      | -            | -                | -                | -         |    -0.15 | delboNi, f4stzin, piria, shz, zqk |
|           20 |     6258 | 2024-02-14 | Corinthians Esports | W   | 0.499      | 0.450        | -                | 0.458 (0.103)    | 0 (0.000) |     7.79 | delboNi, f4stzin, piria, shz, zqk |
|           19 |     6264 | 2024-02-14 | Corinthians Esports | W   | 0.499      | 0.450        | -                | 0.458 (0.103)    | -         |     8.13 | delboNi, f4stzin, piria, shz, zqk |
|           18 |     6349 | 2024-02-13 | inSanitY Sports     | W   | 0.490      | -            | -                | -                | -         |     4.46 | delboNi, f4stzin, piria, shz, zqk |
|           17 |     7071 | 2024-01-28 | w7m esports         | L   | 0.385      | -            | -                | -                | -         |    -4.12 | delboNi, f4stzin, piria, shz, zqk |
|           16 |     7129 | 2024-01-27 | inSanitY Sports     | W   | 0.379      | -            | -                | -                | -         |     3.40 | delboNi, f4stzin, piria, shz, zqk |
|           15 |     7247 | 2024-01-26 | Fluxo               | L   | 0.371      | -            | -                | -                | -         |    -1.79 | delboNi, f4stzin, piria, shz, zqk |
|           14 |     7403 | 2024-01-23 | Sharks Esports      | L   | 0.352      | -            | -                | -                | -         |    -2.17 | delboNi, f4stzin, piria, shz, zqk |
|           13 |     7447 | 2024-01-22 | MIBR                | W   | 0.346      | 0.143        | 0.307 (0.015)    | -                | -         |    10.83 | delboNi, f4stzin, piria, shz, zqk |
|           12 |     7548 | 2024-01-20 | Case Esports        | L   | 0.332      | -            | -                | -                | -         |    -4.76 | delboNi, f4stzin, piria, shz, zqk |
|           11 |     7625 | 2024-01-19 | 9z Team             | L   | 0.326      | -            | -                | -                | -         |    -0.32 | delboNi, f4stzin, piria, shz, zqk |
|           10 |     7639 | 2024-01-19 | Fluxo               | L   | 0.325      | -            | -                | -                | -         |    -1.49 | delboNi, f4stzin, piria, shz, zqk |
|            9 |     7876 | 2024-01-16 | RED Canids          | L   | 0.305      | -            | -                | -                | -         |    -1.29 | delboNi, f4stzin, piria, shz, zqk |
|            8 |     7895 | 2024-01-16 | ODDIK               | W   | 0.304      | -            | -                | -                | -         |     7.94 | delboNi, f4stzin, piria, shz, zqk |
|            7 |     8164 | 2024-01-11 | Galorys             | W   | 0.273      | 0.143        | 0.022 (0.001)    | -                | -         |     6.47 | delboNi, f4stzin, piria, shz, zqk |
|            6 |     8166 | 2024-01-11 | TIMACETA            | W   | 0.272      | -            | -                | -                | -         |     4.22 | delboNi, f4stzin, piria, shz, zqk |
|            5 |     8172 | 2024-01-11 | 2Game Esports       | W   | 0.271      | -            | -                | -                | -         |     4.97 | delboNi, f4stzin, piria, shz, zqk |
|            4 |     8183 | 2024-01-11 | ???                 | W   | 0.271      | -            | -                | -                | -         |     2.55 | delboNi, f4stzin, piria, shz, zqk |
|            3 |     8234 | 2024-01-10 | Hazap Esports       | W   | 0.266      | -            | -                | -                | -         |     3.46 | delboNi, f4stzin, piria, shz, zqk |
|            2 |     8324 | 2024-01-09 | Legacy              | L   | 0.258      | -            | -                | -                | -         |    -0.88 | delboNi, f4stzin, piria, shz, zqk |
|            1 |     8413 | 2024-01-08 | OneMore eSports     | W   | 0.253      | -            | -                | -                | -         |     3.88 | delboNi, f4stzin, piria, shz, zqk |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($0.00)
- Divide that value by the 5th highest value among all rosters ($300,806.11)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
