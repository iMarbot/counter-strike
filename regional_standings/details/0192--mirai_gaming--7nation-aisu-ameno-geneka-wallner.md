### Roster Details<br />
Team Name: MIRAI Gaming<br />
Roster: 7nation, aisu, ameno, Geneka, WallneR<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [192](../standings_global.md)<br />
Regional Rank: [127]( ../standings_europe.md)<br />
Final Rank Value:  735.9<br />
<br />
Final Rank Value (735.9) = Starting Rank Value (701.2) + Head To Head Adjustments (34.7)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.226[<sup>1</sup>](#table2)
- Bounty Collected: 0.306[<sup>2</sup>](#table1)
- Opponent Network: 0.075[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.152<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 701.2
- 400 + ( ( 0.152 - 0.000 ) / ( 0.806 - 0.000 ) ) * 1600 = 701.2


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent                     | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins      | H2H Adj. | Roster                                    |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           39 |      740 | 2024-04-20 | ZEUSGG                       | W   | 1.000      | 0.417        | -                | 0.095 (0.040)    | false (0.000) |     8.22 | 7nation, aisu, ameno, Geneka, WallneR     |
|           38 |      753 | 2024-04-20 | ZEUSGG                       | W   | 1.000      | 0.417        | -                | 0.095 (0.040)    | false (0.000) |     8.82 | 7nation, aisu, ameno, Geneka, WallneR     |
|           37 |      965 | 2024-04-17 | Rare Atom                    | L   | 1.000      | -            | -                | -                | -             |   -11.79 | 7nation, aisu, ameno, Geneka, neffeD      |
|           36 |     1012 | 2024-04-16 | ATOX Esports                 | W   | 1.000      | 0.143        | 0.112 (0.016)    | 0.769 (0.110)    | false (0.000) |    27.45 | 7nation, aisu, ameno, Geneka, neffeD      |
|           35 |     1498 | 2024-04-04 | TYLOO                        | L   | 0.991      | -            | -                | -                | -             |    -4.67 | 7nation, aisu, ameno, Geneka, WallneR     |
|           34 |     1502 | 2024-04-04 | TYLOO                        | L   | 0.990      | -            | -                | -                | -             |    -4.89 | 7nation, aisu, ameno, Geneka, WallneR     |
|           33 |     1761 | 2024-03-27 | -72C                         | L   | 0.937      | -            | -                | -                | -             |   -11.81 | 7nation, aisu, ameno, Geneka, WallneR     |
|           32 |     1764 | 2024-03-27 | -72C                         | W   | 0.937      | 0.417        | 0.003 (0.001)    | 0.300 (0.117)    | false (0.000) |    18.04 | 7nation, aisu, ameno, Geneka, WallneR     |
|           31 |     1826 | 2024-03-26 | Lynn Vision Gaming           | L   | 0.931      | -            | -                | -                | -             |    -1.21 | 7nation, aisu, ameno, Geneka, WallneR     |
|           30 |     1830 | 2024-03-26 | Lynn Vision Gaming           | L   | 0.931      | -            | -                | -                | -             |    -1.23 | 7nation, aisu, ameno, Geneka, WallneR     |
|           29 |     2274 | 2024-03-14 | Born In Far East             | W   | 0.851      | 0.417        | 0.003 (0.001)    | 0.138 (0.049)    | false (0.000) |    10.85 | 7nation, aisu, ameno, Geneka, WallneR     |
|           28 |     2279 | 2024-03-14 | Born In Far East             | W   | 0.851      | 0.417        | 0.003 (0.001)    | 0.138 (0.049)    | false (0.000) |    11.68 | 7nation, aisu, ameno, Geneka, WallneR     |
|           27 |     2326 | 2024-03-13 | High Five (Chinese team)     | W   | 0.844      | 0.417        | 0.045 (0.016)    | 0.282 (0.099)    | false (0.000) |    19.55 | 7nation, aisu, ameno, Geneka, WallneR     |
|           26 |     2331 | 2024-03-13 | High Five (Chinese team)     | L   | 0.844      | -            | -                | -                | -             |    -6.80 | 7nation, aisu, ameno, Geneka, WallneR     |
|           25 |     2634 | 2024-03-06 | Clutch Gaming                | L   | 0.797      | -            | -                | -                | -             |   -10.66 | 7nation, aisu, ameno, Geneka, WallneR     |
|           24 |     2639 | 2024-03-06 | Clutch Gaming                | L   | 0.797      | -            | -                | -                | -             |   -11.43 | 7nation, aisu, ameno, Geneka, WallneR     |
|           23 |     3317 | 2024-02-21 | LYG Gaming                   | W   | 0.704      | 0.417        | 0.004 (0.001)    | 0.380 (0.112)    | false (0.000) |    13.04 | 7nation, aisu, ameno, Geneka, WallneR     |
|           22 |     3322 | 2024-02-21 | LYG Gaming                   | W   | 0.704      | 0.417        | 0.004 (0.001)    | 0.380 (0.112)    | false (0.000) |    13.84 | 7nation, aisu, ameno, Geneka, WallneR     |
|           21 |     3543 | 2024-02-16 | ATOX Esports                 | L   | 0.671      | -            | -                | -                | -             |    -2.01 | 7nation, aisu, ameno, Geneka, WallneR     |
|           20 |     3545 | 2024-02-16 | ATOX Esports                 | L   | 0.671      | -            | -                | -                | -             |    -2.05 | 7nation, aisu, ameno, Geneka, WallneR     |
|           19 |     3642 | 2024-02-14 | SEAW                         | L   | 0.657      | -            | -                | -                | -             |   -15.37 | 7nation, aisu, Geneka, MemorizeW, WallneR |
|           18 |     3652 | 2024-02-14 | MOLEGAN                      | W   | 0.657      | -            | -                | -                | false (0.000) |     3.45 | 7nation, aisu, Geneka, MemorizeW, WallneR |
|           17 |     3685 | 2024-02-13 | The QUBE Esports             | L   | 0.651      | -            | -                | -                | -             |    -6.96 | 7nation, aisu, ameno, Geneka, WallneR     |
|           16 |     3688 | 2024-02-13 | The QUBE Esports             | L   | 0.651      | -            | -                | -                | -             |    -7.33 | 7nation, aisu, ameno, Geneka, WallneR     |
|           15 |     4401 | 2024-01-24 | Wings Up Gaming              | L   | 0.517      | -            | -                | -                | -             |    -7.15 | 7nation, aisu, ameno, Geneka, WallneR     |
|           14 |     5329 | 2023-12-18 | The QUBE Esports             | L   | 0.270      | -            | -                | -                | -             |    -3.26 | 7nation, ameno, Geneka, M4G1C, WallneR    |
|           13 |     5378 | 2023-12-17 | Gods Reign                   | W   | 0.264      | 0.143        | 0.174 (0.007)    | -                | -             |     6.66 | 7nation, ameno, Geneka, M4G1C, WallneR    |
|           12 |     5490 | 2023-12-16 | Rare Atom                    | L   | 0.257      | -            | -                | -                | -             |    -3.56 | 7nation, ameno, Geneka, M4G1C, WallneR    |
|           11 |     5497 | 2023-12-16 | ATOX Esports                 | L   | 0.256      | -            | -                | -                | -             |    -0.84 | 7nation, ameno, Geneka, M4G1C, WallneR    |
|           10 |     5592 | 2023-12-15 | Aravt                        | W   | 0.250      | -            | -                | -                | -             |     2.42 | 7nation, ameno, Geneka, M4G1C, WallneR    |
|            9 |     5776 | 2023-12-09 | Gods Reign                   | W   | 0.210      | 0.250        | 0.174 (0.009)    | 0.479 (0.025)    | -             |     5.43 | 7nation, ameno, Geneka, M4G1C, WallneR    |
|            8 |     5847 | 2023-12-08 | Jadeite                      | W   | 0.204      | -            | -                | -                | -             |     1.01 | 7nation, ameno, Geneka, M4G1C, WallneR    |
|            7 |     5895 | 2023-12-07 | The QUBE Esports             | L   | 0.197      | -            | -                | -                | -             |    -2.28 | 7nation, ameno, Geneka, M4G1C, WallneR    |
|            6 |     6128 | 2023-12-02 | GR Gaming                    | L   | 0.163      | -            | -                | -                | -             |    -1.76 | 7nation, ameno, Geneka, M4G1C, WallneR    |
|            5 |     6137 | 2023-12-02 | NewHappy                     | W   | 0.163      | 0.250        | 0.014 (0.001)    | -                | -             |     2.85 | 7nation, ameno, Geneka, M4G1C, WallneR    |
|            4 |     6686 | 2023-11-19 | Octagonal Disposition Gaming | L   | 0.076      | -            | -                | -                | -             |    -1.49 | 7nation, ameno, Geneka, M4G1C, WallneR    |
|            3 |     6749 | 2023-11-18 | EZPZ                         | W   | 0.069      | -            | -                | -                | -             |     0.34 | 7nation, ameno, Geneka, M4G1C, WallneR    |
|            2 |     6849 | 2023-11-16 | Aravt                        | L   | 0.056      | -            | -                | -                | -             |    -1.26 | 7nation, ameno, Geneka, M4G1C, WallneR    |
|            1 |     6892 | 2023-11-15 | Steel Helmet                 | W   | 0.050      | -            | -                | -                | -             |     0.80 | 7nation, ameno, Geneka, M4G1C, WallneR    |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($59.80)
- Divide that value by the 5th highest value among all rosters ($158,437.64)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2023-12-02 |      0.163 | $250.00        | $40.85          |
| 2023-11-19 |      0.076 | $250.00        | $18.95          |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
