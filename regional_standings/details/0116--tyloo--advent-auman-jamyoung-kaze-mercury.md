### Roster Details<br />
Team Name: TYLOO<br />
Roster: advent, aumaN, JamYoung, kaze, Mercury<br />
Region: [Asia]( ../standings_asia.md)<br />
<br />
Global Rank: [116](../standings_global.md)<br />
Regional Rank: [13]( ../standings_asia.md)<br />
Final Rank Value:  841.0<br />
<br />
Final Rank Value (841.0) = Starting Rank Value (794.7) + Head To Head Adjustments (46.3)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.361[<sup>1</sup>](#table2)
- Bounty Collected: 0.263[<sup>2</sup>](#table1)
- Opponent Network: 0.013[<sup>2</sup>](#table1)
- LAN Wins: 0.139[<sup>2</sup>](#table1)

The average of these factors is 0.194<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 794.7
- 400 + ( ( 0.194 - 0.000 ) / ( 0.786 - 0.000 ) ) * 1600 = 794.7


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent                           | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                 |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           33 |     5387 | 2024-02-26 | ATOX Esports                       | L   | 0.581      | -            | -                | -                | -         |    -2.33 | advent, aumaN, JamYoung, kaze, Mercury |
|           32 |     5427 | 2024-02-25 | Lynn Vision Gaming                 | L   | 0.574      | -            | -                | -                | -         |    -3.63 | advent, aumaN, JamYoung, kaze, Mercury |
|           31 |     5429 | 2024-02-25 | JiJieHao                           | W   | 0.574      | 0.143        | -                | 0.103 (0.008)    | 1 (0.574) |     2.85 | advent, aumaN, JamYoung, kaze, Mercury |
|           30 |     6639 | 2024-02-02 | Rare Atom                          | L   | 0.415      | -            | -                | -                | -         |    -8.30 | advent, aumaN, JamYoung, kaze, Mercury |
|           29 |     6690 | 2024-02-01 | NewHappy                           | W   | 0.409      | 0.143        | -                | 0.066 (0.004)    | 0 (0.000) |     3.77 | advent, aumaN, JamYoung, kaze, Mercury |
|           28 |     6697 | 2024-02-01 | GR Gaming                          | W   | 0.408      | 0.143        | 0.007 (0.000)    | 0.428 (0.025)    | 0 (0.000) |     5.29 | advent, aumaN, JamYoung, kaze, Mercury |
|           27 |     6892 | 2024-01-27 | Lynn Vision Gaming                 | L   | 0.380      | -            | -                | -                | -         |    -2.16 | advent, aumaN, JamYoung, kaze, Mercury |
|           26 |     6984 | 2024-01-27 | The MongolZ                        | W   | 0.376      | 0.143        | 0.192 (0.010)    | 0.619 (0.033)    | 0 (0.000) |    11.69 | advent, aumaN, JamYoung, kaze, Mercury |
|           25 |     6995 | 2024-01-27 | The Huns Esports                   | W   | 0.375      | 0.143        | -                | 0.292 (0.016)    | 0 (0.000) |     6.97 | advent, aumaN, JamYoung, kaze, Mercury |
|           24 |     7001 | 2024-01-26 | ACME                               | W   | 0.374      | 0.435        | 0.002 (0.000)    | -                | 1 (0.374) |     3.20 | advent, aumaN, JamYoung, kaze, Mercury |
|           23 |     7052 | 2024-01-26 | The MongolZ                        | L   | 0.370      | -            | -                | -                | -         |    -0.14 | advent, aumaN, JamYoung, kaze, Mercury |
|           22 |     7061 | 2024-01-26 | Wings Up Gaming                    | W   | 0.368      | 0.143        | 0.006 (0.000)    | 0.086 (0.005)    | 0 (0.000) |     4.13 | advent, aumaN, JamYoung, kaze, Mercury |
|           21 |     7065 | 2024-01-25 | The MongolZ                        | L   | 0.368      | -            | -                | -                | -         |    -0.14 | advent, aumaN, JamYoung, kaze, Mercury |
|           20 |     7067 | 2024-01-25 | On Sla2ers                         | W   | 0.367      | 0.435        | 0.002 (0.000)    | -                | 1 (0.367) |     1.95 | advent, aumaN, JamYoung, kaze, Mercury |
|           19 |     7285 | 2024-01-21 | Rare Atom                          | W   | 0.336      | 0.143        | 0.011 (0.001)    | 0.139 (0.007)    | 0 (0.000) |     3.90 | advent, aumaN, JamYoung, kaze, Mercury |
|           18 |     7298 | 2024-01-20 | Lynn Vision Gaming                 | L   | 0.334      | -            | -                | -                | -         |    -1.68 | advent, aumaN, JamYoung, kaze, Mercury |
|           17 |     7433 | 2024-01-19 | NewHappy                           | W   | 0.321      | -            | -                | -                | 0 (0.000) |     3.40 | advent, aumaN, JamYoung, kaze, Mercury |
|           16 |     7441 | 2024-01-18 | SHPL                               | W   | 0.321      | 0.143        | 0.022 (0.001)    | 0.100 (0.005)    | -         |     5.70 | advent, aumaN, JamYoung, kaze, Mercury |
|           15 |     8213 | 2024-01-06 | Wings Up Gaming                    | W   | 0.236      | 0.143        | 0.006 (0.000)    | -                | -         |     2.56 | advent, aumaN, JamYoung, kaze, Mercury |
|           14 |     8228 | 2024-01-05 | Wings Up Gaming                    | W   | 0.228      | -            | -                | -                | -         |     2.46 | advent, aumaN, JamYoung, kaze, Mercury |
|           13 |     8238 | 2024-01-04 | ATOX Esports                       | W   | 0.222      | 0.143        | 0.047 (0.001)    | 0.601 (0.019)    | -         |     6.41 | advent, aumaN, JamYoung, kaze, Mercury |
|           12 |     8265 | 2024-01-03 | MungYu Esports                     | W   | 0.216      | -            | -                | -                | -         |     1.07 | advent, aumaN, JamYoung, kaze, Mercury |
|           11 |     8296 | 2024-01-01 | Jadeite                            | W   | 0.203      | -            | -                | -                | -         |     0.63 | advent, aumaN, JamYoung, kaze, Mercury |
|           10 |     8298 | 2023-12-31 | NewHappy                           | L   | 0.201      | -            | -                | -                | -         |    -4.13 | advent, aumaN, JamYoung, kaze, Mercury |
|            9 |     8319 | 2023-12-27 | NewHappy                           | L   | 0.169      | -            | -                | -                | -         |    -3.53 | advent, aumaN, JamYoung, kaze, Mercury |
|            8 |     8323 | 2023-12-26 | Guangdong University of Technology | W   | 0.162      | -            | -                | -                | -         |     1.23 | advent, aumaN, JamYoung, kaze, Mercury |
|            7 |     8325 | 2023-12-24 | NewHappy                           | W   | 0.149      | -            | -                | -                | -         |     1.58 | advent, aumaN, JamYoung, kaze, Mercury |
|            6 |     8327 | 2023-12-23 | Lynn Vision Gaming                 | L   | 0.147      | -            | -                | -                | -         |    -0.68 | advent, aumaN, JamYoung, kaze, Mercury |
|            5 |     8342 | 2023-12-22 | Wings Up Gaming                    | W   | 0.141      | -            | -                | -                | -         |     1.50 | advent, aumaN, JamYoung, kaze, Mercury |
|            4 |     8343 | 2023-12-22 | NewHappy                           | W   | 0.141      | -            | -                | -                | -         |     1.48 | advent, aumaN, JamYoung, kaze, Mercury |
|            3 |     8985 | 2023-12-10 | The MongolZ                        | L   | 0.056      | -            | -                | -                | -         |    -0.02 | advent, aumaN, JamYoung, kaze, Mercury |
|            2 |     9182 | 2023-12-07 | Lynn Vision Gaming                 | W   | 0.036      | 0.417        | 0.063 (0.001)    | 0.414 (0.006)    | -         |     0.97 | advent, aumaN, JamYoung, kaze, Mercury |
|            1 |     9239 | 2023-12-06 | NewHappy                           | W   | 0.029      | -            | -                | -                | -         |     0.31 | advent, aumaN, JamYoung, kaze, Mercury |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($5,104.09)
- Divide that value by the 5th highest value among all rosters ($300,806.11)
- The final value (0.02) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-01-28 |      0.382 | $4,000.00      | $1,528.89       |
| 2024-01-06 |      0.236 | $11,263.63     | $2,654.52       |
| 2023-12-27 |      0.169 | $2,799.79      | $474.02         |
| 2023-12-10 |      0.056 | $8,000.00      | $446.67         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
