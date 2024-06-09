### Roster Details<br />
Team Name: NewHappy<br />
Roster: 2X2X, L1haNg, SPine, TiGeR, tutu<br />
Region: [Asia]( ../standings_asia.md)<br />
<br />
Global Rank: [252](../standings_global.md)<br />
Regional Rank: [35]( ../standings_asia.md)<br />
Final Rank Value:  683.9<br />
<br />
Final Rank Value (683.9) = Starting Rank Value (669.7) + Head To Head Adjustments (14.1)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.284[<sup>1</sup>](#table2)
- Bounty Collected: 0.241[<sup>2</sup>](#table1)
- Opponent Network: 0.005[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.133<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 669.7
- 400 + ( ( 0.133 - 0.000 ) / ( 0.787 - 0.000 ) ) * 1600 = 669.7


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
|           32 |     6891 | 2024-02-01 | GR Gaming                    | L   | 0.409      | -            | -                | -                | -         |    -4.78 | 2X2X, L1haNg, SPine, TiGeR, tutu |
|           31 |     6899 | 2024-02-01 | TYLOO                        | L   | 0.409      | -            | -                | -                | -         |    -3.77 | 2X2X, L1haNg, SPine, TiGeR, tutu |
|           30 |     6905 | 2024-02-01 | Steel Helmet                 | W   | 0.408      | 0.143        | 0.012 (0.001)    | 0.087 (0.005)    | 0 (0.000) |     6.44 | 2X2X, L1haNg, SPine, TiGeR, tutu |
|           29 |     7319 | 2024-01-25 | Rare Atom                    | L   | 0.362      | -            | -                | -                | -         |    -5.11 | 2X2X, L1haNg, SPine, TiGeR, tutu |
|           28 |     7361 | 2024-01-24 | Noobs But Diligent           | W   | 0.356      | 0.143        | 0.014 (0.001)    | 0.138 (0.007)    | 0 (0.000) |     6.70 | 2X2X, L1haNg, SPine, TiGeR, tutu |
|           27 |     7363 | 2024-01-24 | Fort Arena                   | W   | 0.356      | -            | -                | -                | 0 (0.000) |     2.79 | 2X2X, L1haNg, SPine, TiGeR, tutu |
|           26 |     7482 | 2024-01-22 | Eruption                     | L   | 0.343      | -            | -                | -                | -         |    -6.59 | 2X2X, L1haNg, SPine, TiGeR, tutu |
|           25 |     7534 | 2024-01-21 | Rare Atom                    | L   | 0.335      | -            | -                | -                | -         |    -4.93 | 2X2X, L1haNg, SPine, TiGeR, tutu |
|           24 |     7615 | 2024-01-20 | Steel Helmet                 | W   | 0.328      | 0.143        | 0.012 (0.001)    | 0.087 (0.004)    | 0 (0.000) |     5.10 | 2X2X, L1haNg, SPine, TiGeR, tutu |
|           23 |     7680 | 2024-01-19 | TYLOO                        | L   | 0.321      | -            | -                | -                | -         |    -3.40 | 2X2X, L1haNg, SPine, TiGeR, tutu |
|           22 |     7684 | 2024-01-18 | Rare Atom                    | W   | 0.321      | 0.143        | 0.011 (0.001)    | 0.139 (0.006)    | 0 (0.000) |     5.34 | 2X2X, L1haNg, SPine, TiGeR, tutu |
|           21 |     8479 | 2024-01-05 | ATOX Esports                 | L   | 0.229      | -            | -                | -                | -         |    -0.27 | 2X2X, L1haNg, SPine, TiGeR, tutu |
|           20 |     8489 | 2024-01-04 | Wings Up Gaming              | L   | 0.223      | -            | -                | -                | -         |    -3.58 | 2X2X, L1haNg, SPine, TiGeR, tutu |
|           19 |     8525 | 2024-01-02 | MungYu Esports               | W   | 0.214      | -            | -                | -                | 0 (0.000) |     1.72 | 2X2X, L1haNg, SPine, TiGeR, tutu |
|           18 |     8554 | 2023-12-31 | TYLOO                        | W   | 0.201      | 0.143        | 0.017 (0.000)    | 0.131 (0.004)    | 0 (0.000) |     4.12 | 2X2X, L1haNg, SPine, TiGeR, tutu |
|           17 |     8576 | 2023-12-27 | TYLOO                        | W   | 0.169      | 0.143        | 0.017 (0.000)    | 0.131 (0.003)    | 0 (0.000) |     3.52 | 2X2X, L1haNg, SPine, TiGeR, tutu |
|           16 |     8578 | 2023-12-27 | Lynn Vision Gaming           | W   | 0.169      | 0.143        | 0.063 (0.002)    | 0.431 (0.010)    | 0 (0.000) |     4.89 | 2X2X, L1haNg, SPine, TiGeR, tutu |
|           15 |     8582 | 2023-12-24 | TYLOO                        | L   | 0.149      | -            | -                | -                | -         |    -1.58 | 2X2X, L1haNg, SPine, TiGeR, tutu |
|           14 |     8583 | 2023-12-24 | Steel Helmet                 | W   | 0.148      | 0.143        | 0.012 (0.000)    | -                | 0 (0.000) |     2.35 | 2X2X, L1haNg, SPine, TiGeR, tutu |
|           13 |     8592 | 2023-12-23 | Rare Atom                    | W   | 0.142      | 0.143        | 0.011 (0.000)    | 0.139 (0.003)    | -         |     2.46 | 2X2X, L1haNg, SPine, TiGeR, tutu |
|           12 |     8597 | 2023-12-23 | MungYu Esports               | W   | 0.141      | -            | -                | -                | -         |     1.22 | 2X2X, L1haNg, SPine, TiGeR, tutu |
|           11 |     8600 | 2023-12-22 | TYLOO                        | L   | 0.141      | -            | -                | -                | -         |    -1.48 | 2X2X, L1haNg, SPine, TiGeR, tutu |
|           10 |     8777 | 2023-12-16 | Secret                       | W   | 0.101      | -            | -                | -                | -         |     0.57 | 2X2X, L1haNg, SPine, TiGeR, tutu |
|            9 |     8782 | 2023-12-16 | 江浙五剑客                        | W   | 0.101      | -            | -                | -                | -         |     0.57 | 2X2X, L1haNg, SPine, TiGeR, tutu |
|            8 |     9259 | 2023-12-10 | Octagonal Disposition Gaming | W   | 0.055      | -            | -                | -                | -         |     0.52 | 2X2X, L1haNg, SPine, TiGeR, tutu |
|            7 |     9314 | 2023-12-09 | 以卵击石                         | W   | 0.049      | -            | -                | -                | -         |     0.28 | 2X2X, L1haNg, SPine, TiGeR, tutu |
|            6 |     9387 | 2023-12-08 | The MongolZ                  | L   | 0.043      | -            | -                | -                | -         |    -0.01 | 2X2X, L1haNg, SPine, TiGeR, tutu |
|            5 |     9453 | 2023-12-07 | -72C                         | W   | 0.036      | 0.417        | -                | 0.252 (0.004)    | -         |     0.70 | 2X2X, L1haNg, SPine, TiGeR, tutu |
|            4 |     9520 | 2023-12-06 | TYLOO                        | L   | 0.029      | -            | -                | -                | -         |    -0.31 | 2X2X, L1haNg, SPine, TiGeR, tutu |
|            3 |     9597 | 2023-12-05 | The MongolZ                  | W   | 0.022      | 0.417        | 0.192 (0.002)    | 0.619 (0.006)    | -         |     0.70 | 2X2X, L1haNg, SPine, TiGeR, tutu |
|            2 |     9793 | 2023-12-02 | MIRAI Gaming                 | L   | 0.002      | -            | -                | -                | -         |    -0.03 | 2X2X, L1haNg, SPine, TiGeR, tutu |
|            1 |     9798 | 2023-12-02 | SUBUTAI                      | W   | 0.001      | -            | -                | -                | -         |     0.01 | 2X2X, L1haNg, SPine, TiGeR, tutu |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($917.26)
- Divide that value by the 5th highest value among all rosters ($300,806.11)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2023-12-27 |      0.169 | $4,199.68      | $711.03         |
| 2023-12-10 |      0.056 | $3,000.00      | $167.50         |
| 2023-12-10 |      0.055 | $700.61        | $38.73          |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
