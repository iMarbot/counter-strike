### Roster Details<br />
Team Name: NewHappy<br />
Roster: 2X2X, L1haNg, SPine, TiGeR, tutu<br />
Region: [Asia]( ../standings_asia.md)<br />
<br />
Global Rank: [157](../standings_global.md)<br />
Regional Rank: [25]( ../standings_asia.md)<br />
Final Rank Value:  769.5<br />
<br />
Final Rank Value (769.5) = Starting Rank Value (736.0) + Head To Head Adjustments (33.5)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.350[<sup>1</sup>](#table2)
- Bounty Collected: 0.305[<sup>2</sup>](#table1)
- Opponent Network: 0.023[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.169<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 736.0
- 400 + ( ( 0.169 - 0.000 ) / ( 0.806 - 0.000 ) ) * 1600 = 736.0


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent                     | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                           |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           39 |     4084 | 2024-02-01 | GR Gaming                    | L   | 0.571      | -            | -                | -                | -         |    -7.80 | 2X2X, L1haNg, SPine, TiGeR, tutu |
|           38 |     4091 | 2024-02-01 | TYLOO                        | L   | 0.570      | -            | -                | -                | -         |    -2.74 | 2X2X, L1haNg, SPine, TiGeR, tutu |
|           37 |     4096 | 2024-02-01 | Steel Helmet                 | W   | 0.569      | 0.143        | 0.025 (0.002)    | 0.174 (0.014)    | 0 (0.000) |     7.54 | 2X2X, L1haNg, SPine, TiGeR, tutu |
|           36 |     4363 | 2024-01-25 | Rare Atom                    | L   | 0.523      | -            | -                | -                | -         |    -8.11 | 2X2X, L1haNg, SPine, TiGeR, tutu |
|           35 |     4388 | 2024-01-24 | Noobs But Diligent           | W   | 0.517      | 0.143        | 0.027 (0.002)    | 0.174 (0.013)    | 0 (0.000) |     8.34 | 2X2X, L1haNg, SPine, TiGeR, tutu |
|           34 |     4390 | 2024-01-24 | Fort Arena                   | W   | 0.517      | -            | -                | -                | 0 (0.000) |     2.88 | 2X2X, L1haNg, SPine, TiGeR, tutu |
|           33 |     4480 | 2024-01-22 | Aravt                        | L   | 0.504      | -            | -                | -                | -         |   -11.94 | 2X2X, L1haNg, SPine, TiGeR, tutu |
|           32 |     4516 | 2024-01-21 | Rare Atom                    | L   | 0.496      | -            | -                | -                | -         |    -8.25 | 2X2X, L1haNg, SPine, TiGeR, tutu |
|           31 |     4576 | 2024-01-20 | Steel Helmet                 | W   | 0.489      | 0.143        | 0.025 (0.002)    | 0.174 (0.012)    | 0 (0.000) |     6.18 | 2X2X, L1haNg, SPine, TiGeR, tutu |
|           30 |     4626 | 2024-01-19 | TYLOO                        | L   | 0.482      | -            | -                | -                | -         |    -2.71 | 2X2X, L1haNg, SPine, TiGeR, tutu |
|           29 |     4629 | 2024-01-18 | Rare Atom                    | W   | 0.482      | 0.143        | 0.026 (0.002)    | 0.259 (0.018)    | 0 (0.000) |     7.00 | 2X2X, L1haNg, SPine, TiGeR, tutu |
|           28 |     5189 | 2024-01-05 | ATOX Esports                 | L   | 0.390      | -            | -                | -                | -         |    -1.85 | 2X2X, L1haNg, SPine, TiGeR, tutu |
|           27 |     5195 | 2024-01-04 | Wings Up Gaming              | L   | 0.384      | -            | -                | -                | -         |    -6.98 | 2X2X, L1haNg, SPine, TiGeR, tutu |
|           26 |     5221 | 2024-01-02 | MungYu Esports               | W   | 0.375      | -            | -                | -                | 0 (0.000) |     2.05 | 2X2X, L1haNg, SPine, TiGeR, tutu |
|           25 |     5245 | 2023-12-31 | TYLOO                        | W   | 0.362      | 0.143        | 0.131 (0.007)    | 0.592 (0.031)    | 0 (0.000) |     9.35 | 2X2X, L1haNg, SPine, TiGeR, tutu |
|           24 |     5260 | 2023-12-27 | TYLOO                        | W   | 0.330      | 0.143        | 0.131 (0.006)    | 0.592 (0.028)    | 0 (0.000) |     8.69 | 2X2X, L1haNg, SPine, TiGeR, tutu |
|           23 |     5262 | 2023-12-27 | Lynn Vision Gaming           | W   | 0.330      | 0.143        | 0.155 (0.007)    | 0.554 (0.026)    | 0 (0.000) |     9.85 | 2X2X, L1haNg, SPine, TiGeR, tutu |
|           22 |     5266 | 2023-12-24 | TYLOO                        | L   | 0.310      | -            | -                | -                | -         |    -1.55 | 2X2X, L1haNg, SPine, TiGeR, tutu |
|           21 |     5267 | 2023-12-24 | Steel Helmet                 | W   | 0.309      | 0.143        | 0.025 (0.001)    | -                | 0 (0.000) |     4.16 | 2X2X, L1haNg, SPine, TiGeR, tutu |
|           20 |     5276 | 2023-12-23 | Rare Atom                    | W   | 0.303      | 0.143        | 0.026 (0.001)    | 0.259 (0.011)    | -         |     4.83 | 2X2X, L1haNg, SPine, TiGeR, tutu |
|           19 |     5281 | 2023-12-23 | MungYu Esports               | W   | 0.302      | -            | -                | -                | -         |     1.94 | 2X2X, L1haNg, SPine, TiGeR, tutu |
|           18 |     5284 | 2023-12-22 | TYLOO                        | L   | 0.302      | -            | -                | -                | -         |    -1.44 | 2X2X, L1haNg, SPine, TiGeR, tutu |
|           17 |     5405 | 2023-12-16 | Secret (Chinese team)        | W   | 0.262      | -            | -                | -                | -         |     1.04 | 2X2X, L1haNg, SPine, TiGeR, tutu |
|           16 |     5410 | 2023-12-16 | 江浙五剑客                        | W   | 0.262      | -            | -                | -                | -         |     1.03 | 2X2X, L1haNg, SPine, TiGeR, tutu |
|           15 |     5744 | 2023-12-10 | Octagonal Disposition Gaming | W   | 0.216      | -            | -                | -                | -         |     2.18 | 2X2X, L1haNg, SPine, TiGeR, tutu |
|           14 |     5786 | 2023-12-09 | 以卵击石                         | W   | 0.210      | -            | -                | -                | -         |     0.83 | 2X2X, L1haNg, SPine, TiGeR, tutu |
|           13 |     5849 | 2023-12-08 | The MongolZ                  | L   | 0.204      | -            | -                | -                | -         |    -0.04 | 2X2X, L1haNg, SPine, TiGeR, tutu |
|           12 |     5898 | 2023-12-07 | -72C                         | W   | 0.197      | 0.417        | -                | 0.300 (0.025)    | -         |     3.56 | 2X2X, L1haNg, SPine, TiGeR, tutu |
|           11 |     5948 | 2023-12-06 | TYLOO                        | L   | 0.190      | -            | -                | -                | -         |    -0.90 | 2X2X, L1haNg, SPine, TiGeR, tutu |
|           10 |     6004 | 2023-12-05 | The MongolZ                  | W   | 0.184      | 0.417        | 0.292 (0.022)    | 0.663 (0.051)    | -         |     5.75 | 2X2X, L1haNg, SPine, TiGeR, tutu |
|            9 |     6137 | 2023-12-02 | MIRAI Gaming                 | L   | 0.163      | -            | -                | -                | -         |    -2.85 | 2X2X, L1haNg, SPine, TiGeR, tutu |
|            8 |     6142 | 2023-12-02 | SUBUTAI                      | W   | 0.162      | -            | -                | -                | -         |     0.67 | 2X2X, L1haNg, SPine, TiGeR, tutu |
|            7 |     6649 | 2023-11-20 | TYLOO                        | L   | 0.084      | -            | -                | -                | -         |    -0.39 | 2X2X, L1haNg, SPine, TiGeR, tutu |
|            6 |     6754 | 2023-11-17 | TYLOO                        | L   | 0.069      | -            | -                | -                | -         |    -0.32 | 2X2X, L1haNg, SPine, TiGeR, tutu |
|            5 |     6786 | 2023-11-17 | ATOX Esports                 | W   | 0.064      | -            | -                | -                | -         |     1.77 | 2X2X, L1haNg, SPine, TiGeR, tutu |
|            4 |     6794 | 2023-11-16 | The MongolZ                  | L   | 0.062      | -            | -                | -                | -         |    -0.01 | 2X2X, L1haNg, SPine, TiGeR, tutu |
|            3 |     6841 | 2023-11-16 | The Huns Esports             | W   | 0.057      | -            | -                | -                | -         |     1.32 | 2X2X, L1haNg, SPine, TiGeR, tutu |
|            2 |     6847 | 2023-11-16 | LYG Gaming                   | W   | 0.056      | -            | -                | -                | -         |     1.01 | 2X2X, L1haNg, SPine, TiGeR, tutu |
|            1 |     6937 | 2023-11-14 | LYG Gaming                   | L   | 0.044      | -            | -                | -                | -         |    -0.59 | 2X2X, L1haNg, SPine, TiGeR, tutu |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($2,189.72)
- Divide that value by the 5th highest value among all rosters ($158,437.64)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2023-12-27 |      0.330 | $4,199.68      | $1,387.45       |
| 2023-12-10 |      0.217 | $3,000.00      | $650.69         |
| 2023-12-10 |      0.216 | $700.61        | $151.57         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
