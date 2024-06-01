### Roster Details<br />
Team Name: MIRAI Gaming<br />
Roster: 7nation, aisu, ameno, Geneka, WallneR<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [196](../standings_global.md)<br />
Regional Rank: [132]( ../standings_europe.md)<br />
Final Rank Value:  728.2<br />
<br />
Final Rank Value (728.2) = Starting Rank Value (708.7) + Head To Head Adjustments (19.5)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.220[<sup>1</sup>](#table2)
- Bounty Collected: 0.304[<sup>2</sup>](#table1)
- Opponent Network: 0.082[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.152<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 708.7
- 400 + ( ( 0.152 - 0.000 ) / ( 0.786 - 0.000 ) ) * 1600 = 708.7


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent           | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                    |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           44 |      507 | 2024-05-22 | Gods Reign         | L   | 1.000      | -            | -                | -                | -         |   -10.98 | 7nation, aisu, ameno, Geneka, WallneR     |
|           43 |      513 | 2024-05-22 | Gods Reign         | W   | 1.000      | 0.417        | 0.086 (0.036)    | 0.461 (0.192)    | 0 (0.000) |    20.93 | 7nation, aisu, ameno, Geneka, WallneR     |
|           42 |     1178 | 2024-05-15 | GR Gaming          | L   | 1.000      | -            | -                | -                | -         |    -9.35 | 7nation, aisu, ameno, Geneka, WallneR     |
|           41 |     1189 | 2024-05-15 | GR Gaming          | W   | 1.000      | 0.417        | 0.007 (0.003)    | 0.428 (0.178)    | 0 (0.000) |    22.65 | 7nation, aisu, ameno, Geneka, WallneR     |
|           40 |     1284 | 2024-05-14 | The MongolZ        | L   | 1.000      | -            | -                | -                | -         |    -0.25 | 7nation, aisu, ameno, Geneka, WallneR     |
|           39 |     1290 | 2024-05-14 | The MongolZ        | L   | 1.000      | -            | -                | -                | -         |    -0.25 | 7nation, aisu, ameno, Geneka, WallneR     |
|           38 |     2608 | 2024-04-20 | ZEUSGG             | W   | 0.936      | 0.417        | -                | 0.076 (0.030)    | 0 (0.000) |     7.94 | 7nation, aisu, ameno, Geneka, WallneR     |
|           37 |     2623 | 2024-04-20 | ZEUSGG             | W   | 0.936      | -            | -                | -                | 0 (0.000) |     8.48 | 7nation, aisu, ameno, Geneka, WallneR     |
|           36 |     2866 | 2024-04-17 | Rare Atom          | L   | 0.915      | -            | -                | -                | -         |   -11.26 | 7nation, aisu, ameno, Geneka, neffeD      |
|           35 |     2917 | 2024-04-16 | ATOX Esports       | W   | 0.909      | 0.143        | 0.047 (0.006)    | 0.601 (0.078)    | 0 (0.000) |    26.45 | 7nation, aisu, ameno, Geneka, neffeD      |
|           34 |     3510 | 2024-04-04 | TYLOO              | L   | 0.829      | -            | -                | -                | -         |    -5.58 | 7nation, aisu, ameno, Geneka, WallneR     |
|           33 |     3514 | 2024-04-04 | TYLOO              | L   | 0.829      | -            | -                | -                | -         |    -5.87 | 7nation, aisu, ameno, Geneka, WallneR     |
|           32 |     3663 | 2024-03-30 | pomawnim           | L   | 0.800      | -            | -                | -                | -         |   -15.66 | 7nation, aisu, ameno, Geneka, WallneR     |
|           31 |     3820 | 2024-03-27 | -72C               | L   | 0.776      | -            | -                | -                | -         |   -10.51 | 7nation, aisu, ameno, Geneka, WallneR     |
|           30 |     3823 | 2024-03-27 | -72C               | W   | 0.776      | 0.417        | 0.000 (0.000)    | 0.252 (0.082)    | 0 (0.000) |    14.26 | 7nation, aisu, ameno, Geneka, WallneR     |
|           29 |     3894 | 2024-03-26 | Lynn Vision Gaming | L   | 0.770      | -            | -                | -                | -         |    -2.01 | 7nation, aisu, ameno, Geneka, WallneR     |
|           28 |     3898 | 2024-03-26 | Lynn Vision Gaming | L   | 0.769      | -            | -                | -                | -         |    -2.06 | 7nation, aisu, ameno, Geneka, WallneR     |
|           27 |     4436 | 2024-03-14 | Born In Far East   | W   | 0.690      | 0.417        | 0.001 (0.000)    | 0.121 (0.035)    | 0 (0.000) |     8.47 | 7nation, aisu, ameno, Geneka, WallneR     |
|           26 |     4441 | 2024-03-14 | Born In Far East   | W   | 0.689      | 0.417        | 0.001 (0.000)    | 0.121 (0.035)    | 0 (0.000) |     8.98 | 7nation, aisu, ameno, Geneka, WallneR     |
|           25 |     4500 | 2024-03-13 | NewHappy           | W   | 0.683      | 0.417        | 0.020 (0.006)    | 0.231 (0.066)    | 0 (0.000) |    14.71 | 7nation, aisu, ameno, Geneka, WallneR     |
|           24 |     4505 | 2024-03-13 | NewHappy           | L   | 0.683      | -            | -                | -                | -         |    -6.78 | 7nation, aisu, ameno, Geneka, WallneR     |
|           23 |     4889 | 2024-03-06 | Clutch Gaming      | L   | 0.636      | -            | -                | -                | -         |    -9.75 | 7nation, aisu, ameno, Geneka, WallneR     |
|           22 |     4894 | 2024-03-06 | Clutch Gaming      | L   | 0.636      | -            | -                | -                | -         |   -10.32 | 7nation, aisu, ameno, Geneka, WallneR     |
|           21 |     5723 | 2024-02-21 | LYG Gaming         | W   | 0.543      | 0.417        | 0.001 (0.000)    | 0.275 (0.062)    | 0 (0.000) |     9.01 | 7nation, aisu, ameno, Geneka, WallneR     |
|           20 |     5729 | 2024-02-21 | LYG Gaming         | W   | 0.543      | 0.417        | 0.001 (0.000)    | 0.275 (0.062)    | -         |     9.45 | 7nation, aisu, ameno, Geneka, WallneR     |
|           19 |     5996 | 2024-02-16 | ATOX Esports       | L   | 0.510      | -            | -                | -                | -         |    -0.83 | 7nation, aisu, ameno, Geneka, WallneR     |
|           18 |     5998 | 2024-02-16 | ATOX Esports       | L   | 0.509      | -            | -                | -                | -         |    -0.84 | 7nation, aisu, ameno, Geneka, WallneR     |
|           17 |     6114 | 2024-02-14 | SEAW               | L   | 0.496      | -            | -                | -                | -         |   -11.86 | 7nation, aisu, Geneka, MemorizeW, WallneR |
|           16 |     6125 | 2024-02-14 | MOLEGAN            | W   | 0.496      | -            | -                | -                | -         |     2.58 | 7nation, aisu, Geneka, MemorizeW, WallneR |
|           15 |     6163 | 2024-02-13 | The QUBE Esports   | L   | 0.490      | -            | -                | -                | -         |    -6.53 | 7nation, aisu, ameno, Geneka, WallneR     |
|           14 |     6167 | 2024-02-13 | The QUBE Esports   | L   | 0.489      | -            | -                | -                | -         |    -6.81 | 7nation, aisu, ameno, Geneka, WallneR     |
|           13 |     7139 | 2024-01-24 | Wings Up Gaming    | L   | 0.356      | -            | -                | -                | -         |    -5.84 | 7nation, aisu, ameno, Geneka, WallneR     |
|           12 |     8418 | 2023-12-18 | The QUBE Esports   | L   | 0.109      | -            | -                | -                | -         |    -1.58 | 7nation, ameno, Geneka, M4G1C, WallneR    |
|           11 |     8483 | 2023-12-17 | Gods Reign         | W   | 0.102      | 0.143        | 0.004 (0.000)    | -                | -         |     1.58 | 7nation, ameno, Geneka, M4G1C, WallneR    |
|           10 |     8632 | 2023-12-16 | Rare Atom          | L   | 0.096      | -            | -                | -                | -         |    -1.53 | 7nation, ameno, Geneka, M4G1C, WallneR    |
|            9 |     8641 | 2023-12-16 | ATOX Esports       | L   | 0.095      | -            | -                | -                | -         |    -0.16 | 7nation, ameno, Geneka, M4G1C, WallneR    |
|            8 |     8753 | 2023-12-15 | Eruption           | W   | 0.089      | -            | -                | -                | -         |     0.99 | 7nation, ameno, Geneka, M4G1C, WallneR    |
|            7 |     8977 | 2023-12-10 | DEWA United        | L   | 0.056      | -            | -                | -                | -         |    -0.88 | 7nation, ameno, Geneka, M4G1C, WallneR    |
|            6 |     9035 | 2023-12-09 | Gods Reign         | W   | 0.049      | -            | -                | -                | -         |     0.77 | 7nation, ameno, Geneka, M4G1C, WallneR    |
|            5 |     9116 | 2023-12-08 | Jadeite            | W   | 0.043      | -            | -                | -                | -         |     0.20 | 7nation, ameno, Geneka, M4G1C, WallneR    |
|            4 |     9176 | 2023-12-07 | The QUBE Esports   | L   | 0.036      | -            | -                | -                | -         |    -0.52 | 7nation, ameno, Geneka, M4G1C, WallneR    |
|            3 |     9502 | 2023-12-02 | GR Gaming          | L   | 0.002      | -            | -                | -                | -         |    -0.03 | 7nation, ameno, Geneka, M4G1C, WallneR    |
|            2 |     9511 | 2023-12-02 | NewHappy           | W   | 0.002      | -            | -                | -                | -         |     0.03 | 7nation, ameno, Geneka, M4G1C, WallneR    |
|            1 |     9517 | 2023-12-02 | ZEUSGG             | W   | 0.001      | -            | -                | -                | -         |     0.01 | 7nation, ameno, Geneka, M4G1C, WallneR    |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($86.96)
- Divide that value by the 5th highest value among all rosters ($300,806.11)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-03-30 |      0.800 | $108.01        | $86.38          |
| 2023-12-02 |      0.002 | $250.00        | $0.58           |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
