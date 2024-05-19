### Roster Details<br />
Team Name: TYLOO<br />
Roster: advent, JamYoung, kaze, Mercury, zdr<br />
Region: [Asia]( ../standings_asia.md)<br />
<br />
Global Rank: [48](../standings_global.md)<br />
Regional Rank: [5]( ../standings_asia.md)<br />
Final Rank Value:  1029.2<br />
<br />
Final Rank Value (1029.2) = Starting Rank Value (1050.3) + Head To Head Adjustments (-21.1)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.531[<sup>1</sup>](#table2)
- Bounty Collected: 0.360[<sup>2</sup>](#table1)
- Opponent Network: 0.108[<sup>2</sup>](#table1)
- LAN Wins: 0.312[<sup>2</sup>](#table1)

The average of these factors is 0.328<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1050.3
- 400 + ( ( 0.328 - 0.000 ) / ( 0.806 - 0.000 ) ) * 1600 = 1050.3


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent                           | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                   |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           69 |      366 | 2024-04-27 | M80                                | L   | 1.000      | -            | -                | -                | -         |    -5.67 | advent, JamYoung, kaze, Mercury, zdr     |
|           68 |      415 | 2024-04-26 | Sharks Esports                     | W   | 1.000      | 0.889        | 0.063 (0.056)    | 0.343 (0.305)    | 1 (1.000) |    11.01 | advent, JamYoung, kaze, Mercury, zdr     |
|           67 |      489 | 2024-04-25 | Team Falcons                       | L   | 1.000      | -            | -                | -                | -         |    -4.70 | advent, JamYoung, kaze, Mercury, zdr     |
|           66 |      547 | 2024-04-24 | G2 Esports                         | L   | 1.000      | -            | -                | -                | -         |    -0.33 | advent, JamYoung, kaze, Mercury, zdr     |
|           65 |      850 | 2024-04-19 | Rare Atom                          | L   | 1.000      | -            | -                | -                | -         |   -21.24 | advent, JamYoung, kaze, Mercury, zdr     |
|           64 |      888 | 2024-04-18 | The MongolZ                        | L   | 1.000      | -            | -                | -                | -         |    -1.74 | advent, JamYoung, kaze, Mercury, zdr     |
|           63 |      903 | 2024-04-18 | Lynn Vision Gaming                 | W   | 1.000      | 0.143        | 0.155 (0.022)    | 0.554 (0.079)    | 0 (0.000) |    22.11 | advent, JamYoung, kaze, Mercury, zdr     |
|           62 |      956 | 2024-04-17 | Sheer Conquer                      | W   | 1.000      | 0.143        | 0.035 (0.005)    | -                | 0 (0.000) |     8.18 | advent, JamYoung, kaze, Mercury, zdr     |
|           61 |      961 | 2024-04-17 | The Huns Esports                   | W   | 1.000      | 0.143        | -                | 0.434 (0.062)    | 0 (0.000) |    10.21 | advent, JamYoung, kaze, Mercury, zdr     |
|           60 |     1016 | 2024-04-16 | Aravt                              | W   | 1.000      | -            | -                | -                | 0 (0.000) |     0.99 | advent, JamYoung, kaze, Mercury, zdr     |
|           59 |     1346 | 2024-04-08 | Lynn Vision Gaming                 | L   | 1.000      | -            | -                | -                | -         |    -7.27 | advent, JamYoung, kaze, Mercury, zdr     |
|           58 |     1357 | 2024-04-07 | MOUZ                               | L   | 1.000      | -            | -                | -                | -         |    -0.26 | advent, JamYoung, kaze, Mercury, zdr     |
|           57 |     1498 | 2024-04-04 | MIRAI Gaming                       | W   | 0.991      | 0.417        | -                | 0.246 (0.102)    | 0 (0.000) |     4.67 | JamYoung, k4Mi, Mercury, Moseyuh, zdr    |
|           56 |     1502 | 2024-04-04 | MIRAI Gaming                       | W   | 0.990      | 0.417        | -                | 0.246 (0.102)    | 0 (0.000) |     4.89 | JamYoung, k4Mi, Mercury, Moseyuh, zdr    |
|           55 |     1641 | 2024-03-30 | High Five (Chinese team)           | W   | 0.957      | 0.417        | 0.045 (0.018)    | 0.282 (0.112)    | -         |     7.45 | advent, JamYoung, kaze, Mercury, zdr     |
|           54 |     1642 | 2024-03-30 | High Five (Chinese team)           | W   | 0.957      | 0.417        | 0.045 (0.018)    | 0.282 (0.112)    | -         |     7.94 | advent, JamYoung, kaze, Mercury, zdr     |
|           53 |     1670 | 2024-03-29 | GR Gaming                          | L   | 0.950      | -            | -                | -                | -         |   -19.36 | advent, JamYoung, kaze, Mercury, zdr     |
|           52 |     1673 | 2024-03-29 | GR Gaming                          | L   | 0.950      | -            | -                | -                | -         |   -20.84 | advent, JamYoung, kaze, Mercury, zdr     |
|           51 |     1825 | 2024-03-26 | ZEUSGG                             | W   | 0.931      | -            | -                | -                | -         |     1.77 | advent, JamYoung, kaze, Mercury, zdr     |
|           50 |     1829 | 2024-03-26 | ZEUSGG                             | W   | 0.931      | -            | -                | -                | -         |     1.80 | advent, JamYoung, kaze, Mercury, zdr     |
|           49 |     2272 | 2024-03-14 | -72C                               | W   | 0.851      | 0.417        | -                | 0.300 (0.106)    | -         |     6.64 | advent, JamYoung, kaze, Mercury, zdr     |
|           48 |     2277 | 2024-03-14 | -72C                               | L   | 0.851      | -            | -                | -                | -         |   -20.66 | advent, JamYoung, kaze, Mercury, zdr     |
|           47 |     2337 | 2024-03-13 | LYG Gaming                         | L   | 0.843      | -            | -                | -                | -         |   -22.05 | advent, JamYoung, lyrics3, Mercury, zdr  |
|           46 |     2384 | 2024-03-12 | Noobs But Diligent                 | W   | 0.837      | 0.143        | 0.027 (0.003)    | -                | -         |     4.77 | advent, JamYoung, lyrics3, Mercury, zdr  |
|           45 |     2633 | 2024-03-06 | Born In Far East                   | W   | 0.797      | 0.417        | -                | 0.138 (0.046)    | -         |     2.56 | advent, JamYoung, kaze, Mercury, zdr     |
|           44 |     2638 | 2024-03-06 | Born In Far East                   | W   | 0.797      | -            | -                | -                | -         |     2.63 | advent, JamYoung, kaze, Mercury, zdr     |
|           43 |     3050 | 2024-02-26 | ATOX Esports                       | L   | 0.742      | -            | -                | -                | -         |   -11.39 | advent, aumaN, JamYoung, kaze, Mercury   |
|           42 |     3082 | 2024-02-25 | Lynn Vision Gaming                 | L   | 0.736      | -            | -                | -                | -         |    -6.49 | advent, aumaN, JamYoung, kaze, Mercury   |
|           41 |     3084 | 2024-02-25 | JiJieHao                           | W   | 0.735      | -            | -                | -                | 1 (0.735) |     1.39 | advent, aumaN, JamYoung, kaze, Mercury   |
|           40 |     4052 | 2024-02-02 | Rare Atom                          | L   | 0.576      | -            | -                | -                | -         |   -14.78 | advent, aumaN, JamYoung, kaze, Mercury   |
|           39 |     4091 | 2024-02-01 | NewHappy                           | W   | 0.570      | -            | -                | -                | -         |     2.74 | advent, aumaN, JamYoung, kaze, Mercury   |
|           38 |     4097 | 2024-02-01 | GR Gaming                          | W   | 0.569      | -            | -                | -                | -         |     3.30 | advent, aumaN, JamYoung, kaze, Mercury   |
|           37 |     4234 | 2024-01-27 | Lynn Vision Gaming                 | L   | 0.541      | -            | -                | -                | -         |    -4.27 | advent, aumaN, JamYoung, kaze, Mercury   |
|           36 |     4283 | 2024-01-27 | The MongolZ                        | W   | 0.537      | 0.143        | 0.292 (0.022)    | 0.663 (0.051)    | -         |    16.23 | advent, aumaN, JamYoung, kaze, Mercury   |
|           35 |     4291 | 2024-01-27 | The Huns Esports                   | W   | 0.536      | -            | -                | -                | -         |     5.19 | advent, aumaN, JamYoung, kaze, Mercury   |
|           34 |     4294 | 2024-01-26 | ACME                               | W   | 0.535      | -            | -                | -                | 1 (0.535) |     1.78 | advent, aumaN, JamYoung, kaze, Mercury   |
|           33 |     4332 | 2024-01-26 | The MongolZ                        | L   | 0.531      | -            | -                | -                | -         |    -0.64 | advent, aumaN, JamYoung, kaze, Mercury   |
|           32 |     4340 | 2024-01-26 | Wings Up Gaming                    | W   | 0.530      | -            | -                | -                | -         |     2.86 | advent, aumaN, JamYoung, kaze, Mercury   |
|           31 |     4342 | 2024-01-25 | The MongolZ                        | L   | 0.529      | -            | -                | -                | -         |    -0.63 | advent, aumaN, JamYoung, kaze, Mercury   |
|           30 |     4344 | 2024-01-25 | On Sla2ers                         | W   | 0.528      | -            | -                | -                | 1 (0.528) |     0.89 | advent, aumaN, JamYoung, kaze, Mercury   |
|           29 |     4511 | 2024-01-21 | Rare Atom                          | W   | 0.497      | -            | -                | -                | -         |     2.64 | advent, aumaN, JamYoung, kaze, Mercury   |
|           28 |     4522 | 2024-01-20 | Lynn Vision Gaming                 | L   | 0.495      | -            | -                | -                | -         |    -3.60 | advent, aumaN, JamYoung, kaze, Mercury   |
|           27 |     4626 | 2024-01-19 | NewHappy                           | W   | 0.482      | -            | -                | -                | -         |     2.71 | advent, aumaN, JamYoung, kaze, Mercury   |
|           26 |     4633 | 2024-01-18 | SHPL                               | W   | 0.482      | 0.143        | 0.044 (0.003)    | -                | -         |     4.34 | advent, aumaN, JamYoung, kaze, Mercury   |
|           25 |     5181 | 2024-01-06 | Wings Up Gaming                    | W   | 0.397      | -            | -                | -                | -         |     1.90 | advent, aumaN, JamYoung, kaze, Mercury   |
|           24 |     5193 | 2024-01-05 | Wings Up Gaming                    | W   | 0.389      | -            | -                | -                | -         |     1.80 | advent, aumaN, JamYoung, kaze, Mercury   |
|           23 |     5200 | 2024-01-04 | ATOX Esports                       | W   | 0.383      | 0.143        | 0.112 (0.006)    | -                | -         |     6.88 | advent, aumaN, JamYoung, kaze, Mercury   |
|           22 |     5217 | 2024-01-03 | MungYu Esports                     | W   | 0.377      | -            | -                | -                | -         |     0.56 | advent, aumaN, JamYoung, kaze, Mercury   |
|           21 |     5243 | 2024-01-01 | Jadeite                            | W   | 0.364      | -            | -                | -                | -         |     0.30 | advent, aumaN, JamYoung, kaze, Mercury   |
|           20 |     5245 | 2023-12-31 | NewHappy                           | L   | 0.362      | -            | -                | -                | -         |    -9.35 | advent, aumaN, JamYoung, kaze, Mercury   |
|           19 |     5260 | 2023-12-27 | NewHappy                           | L   | 0.330      | -            | -                | -                | -         |    -8.69 | advent, aumaN, JamYoung, kaze, Mercury   |
|           18 |     5264 | 2023-12-26 | Guangdong University of Technology | W   | 0.323      | -            | -                | -                | -         |     0.91 | advent, aumaN, JamYoung, kaze, Mercury   |
|           17 |     5266 | 2023-12-24 | NewHappy                           | W   | 0.310      | -            | -                | -                | -         |     1.55 | advent, aumaN, JamYoung, kaze, Mercury   |
|           16 |     5268 | 2023-12-23 | Lynn Vision Gaming                 | L   | 0.308      | -            | -                | -                | -         |    -2.18 | advent, aumaN, JamYoung, kaze, Mercury   |
|           15 |     5283 | 2023-12-22 | Wings Up Gaming                    | W   | 0.302      | -            | -                | -                | -         |     1.25 | advent, aumaN, JamYoung, kaze, Mercury   |
|           14 |     5284 | 2023-12-22 | NewHappy                           | W   | 0.302      | -            | -                | -                | -         |     1.44 | advent, aumaN, JamYoung, kaze, Mercury   |
|           13 |     5737 | 2023-12-10 | The MongolZ                        | L   | 0.217      | -            | -                | -                | -         |    -0.23 | advent, aumaN, JamYoung, kaze, Mercury   |
|           12 |     5900 | 2023-12-07 | Lynn Vision Gaming                 | W   | 0.197      | 0.417        | 0.155 (0.013)    | -                | -         |     4.87 | advent, aumaN, JamYoung, kaze, Mercury   |
|           11 |     5948 | 2023-12-06 | NewHappy                           | W   | 0.190      | -            | -                | -                | -         |     0.90 | advent, aumaN, JamYoung, kaze, Mercury   |
|           10 |     6449 | 2023-11-25 | Eternal Fire                       | L   | 0.116      | -            | -                | -                | -         |    -0.06 | advent, JamYoung, kaze, Mercury, Moseyuh |
|            9 |     6496 | 2023-11-24 | Monte                              | L   | 0.109      | -            | -                | -                | -         |    -0.50 | advent, JamYoung, kaze, Mercury, Moseyuh |
|            8 |     6649 | 2023-11-20 | NewHappy                           | W   | 0.084      | -            | -                | -                | -         |     0.39 | advent, JamYoung, kaze, Mercury, Moseyuh |
|            7 |     6737 | 2023-11-18 | The MongolZ                        | L   | 0.070      | -            | -                | -                | -         |    -0.07 | advent, JamYoung, kaze, Mercury, Moseyuh |
|            6 |     6754 | 2023-11-17 | NewHappy                           | W   | 0.069      | -            | -                | -                | -         |     0.32 | advent, JamYoung, kaze, Mercury, Moseyuh |
|            5 |     6787 | 2023-11-17 | The MongolZ                        | L   | 0.064      | -            | -                | -                | -         |    -0.06 | advent, JamYoung, kaze, Mercury, Moseyuh |
|            4 |     6795 | 2023-11-16 | ATOX Esports                       | W   | 0.062      | -            | -                | -                | -         |     1.11 | advent, JamYoung, kaze, Mercury, Moseyuh |
|            3 |     6942 | 2023-11-13 | Octagonal Disposition Gaming       | W   | 0.042      | -            | -                | -                | -         |     0.10 | advent, JamYoung, kaze, Mercury, Moseyuh |
|            2 |     7204 | 2023-11-08 | Lynn Vision Gaming                 | L   | 0.004      | -            | -                | -                | -         |    -0.02 | advent, JamYoung, kaze, Mercury, Moseyuh |
|            1 |     7218 | 2023-11-07 | Team Falcons                       | L   | 0.001      | -            | -                | -                | -         |    -0.01 | advent, JamYoung, kaze, Mercury, Moseyuh |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($20,812.15)
- Divide that value by the 5th highest value among all rosters ($158,437.64)
- The final value (0.13) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-05-05 |      1.000 | $7,000.00      | $7,000.00       |
| 2024-04-14 |      1.000 | $4,000.00      | $4,000.00       |
| 2024-01-28 |      0.543 | $4,000.00      | $2,173.15       |
| 2024-01-06 |      0.397 | $11,263.63     | $4,468.69       |
| 2023-12-27 |      0.330 | $2,799.79      | $924.97         |
| 2023-12-10 |      0.217 | $8,000.00      | $1,735.19       |
| 2023-11-26 |      0.125 | $2,000.00      | $250.05         |
| 2023-11-12 |      0.031 | $8,500.00      | $260.12         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
