### Roster Details<br />
Team Name: -72C<br />
Roster: 1nhuman, borosto, forzetsky, m3wsu, shandarez<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [109](../standings_global.md)<br />
Regional Rank: [80]( ../standings_europe.md)<br />
Final Rank Value:  841.2<br />
<br />
Final Rank Value (841.2) = Starting Rank Value (789.2) + Head To Head Adjustments (52.0)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.281[<sup>1</sup>](#table2)
- Bounty Collected: 0.382[<sup>2</sup>](#table1)
- Opponent Network: 0.122[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.196<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 789.2
- 400 + ( ( 0.196 - 0.000 ) / ( 0.806 - 0.000 ) ) * 1600 = 789.2


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent                     | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins      | H2H Adj. | Roster                                        |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           33 |      838 | 2024-04-19 | Gods Reign                   | W   | 1.000      | 0.417        | 0.174 (0.073)    | 0.479 (0.200)    | false (0.000) |    15.93 | 1nhuman, borosto, forzetsky, m3wsu, shandarez |
|           32 |      843 | 2024-04-19 | Gods Reign                   | W   | 1.000      | 0.417        | 0.174 (0.073)    | 0.479 (0.200)    | false (0.000) |    17.40 | 1nhuman, borosto, forzetsky, m3wsu, shandarez |
|           31 |     1296 | 2024-04-09 | GR Gaming                    | L   | 1.000      | -            | -                | -                | -             |   -10.22 | 1nhuman, borosto, forzetsky, m3wsu, shandarez |
|           30 |     1303 | 2024-04-09 | GR Gaming                    | L   | 1.000      | -            | -                | -                | -             |   -11.06 | 1nhuman, borosto, forzetsky, m3wsu, shandarez |
|           29 |     1666 | 2024-03-29 | High Five (Chinese team)     | W   | 0.951      | 0.417        | 0.045 (0.018)    | 0.282 (0.112)    | false (0.000) |    15.12 | 1nhuman, borosto, forzetsky, m3wsu, shandarez |
|           28 |     1668 | 2024-03-29 | High Five (Chinese team)     | W   | 0.951      | 0.417        | 0.045 (0.018)    | 0.282 (0.112)    | false (0.000) |    16.44 | 1nhuman, borosto, forzetsky, m3wsu, shandarez |
|           27 |     1761 | 2024-03-27 | MIRAI Gaming                 | W   | 0.937      | 0.417        | -                | 0.246 (0.096)    | false (0.000) |    11.81 | 1nhuman, borosto, forzetsky, m3wsu, shandarez |
|           26 |     1764 | 2024-03-27 | MIRAI Gaming                 | L   | 0.937      | -            | -                | -                | -             |   -18.04 | 1nhuman, borosto, forzetsky, m3wsu, shandarez |
|           25 |     1847 | 2024-03-25 | ZEUSGG                       | L   | 0.924      | -            | -                | -                | -             |   -24.24 | 1nhuman, borosto, forzetsky, m3wsu, shandarez |
|           24 |     1848 | 2024-03-25 | ZEUSGG                       | W   | 0.924      | -            | -                | -                | false (0.000) |     4.50 | 1nhuman, borosto, forzetsky, m3wsu, shandarez |
|           23 |     2272 | 2024-03-14 | TYLOO                        | L   | 0.851      | -            | -                | -                | -             |    -6.64 | 1nhuman, borosto, forzetsky, m3wsu, shandarez |
|           22 |     2277 | 2024-03-14 | TYLOO                        | W   | 0.851      | 0.417        | 0.131 (0.047)    | 0.592 (0.210)    | false (0.000) |    20.66 | 1nhuman, borosto, forzetsky, m3wsu, shandarez |
|           21 |     2338 | 2024-03-13 | ATOX Esports                 | L   | 0.843      | -            | -                | -                | -             |    -4.44 | 1nhuman, borosto, forzetsky, m3wsu, shandarez |
|           20 |     2342 | 2024-03-13 | ZEUSGG                       | W   | 0.843      | -            | -                | -                | false (0.000) |     4.49 | 1nhuman, borosto, forzetsky, m3wsu, shandarez |
|           19 |     2383 | 2024-03-12 | Myth Avenue Gaming           | W   | 0.837      | 0.143        | 0.012 (0.001)    | -                | false (0.000) |    11.07 | 1nhuman, borosto, forzetsky, m3wsu, shandarez |
|           18 |     2632 | 2024-03-06 | Lynn Vision Gaming           | L   | 0.797      | -            | -                | -                | -             |    -1.77 | 1nhuman, borosto, forzetsky, m3wsu, shandarez |
|           17 |     2637 | 2024-03-06 | Lynn Vision Gaming           | L   | 0.797      | -            | -                | -                | -             |    -1.80 | 1nhuman, borosto, forzetsky, m3wsu, shandarez |
|           16 |     2704 | 2024-03-05 | Born In Far East             | W   | 0.791      | 0.417        | 0.003 (0.001)    | -                | false (0.000) |     8.50 | 1nhuman, borosto, forzetsky, m3wsu, shandarez |
|           15 |     2708 | 2024-03-05 | Born In Far East             | W   | 0.791      | 0.417        | 0.003 (0.001)    | -                | -             |     9.06 | 1nhuman, borosto, forzetsky, m3wsu, shandarez |
|           14 |     3361 | 2024-02-20 | Clutch Gaming                | W   | 0.697      | 0.417        | -                | 0.216 (0.063)    | -             |     9.35 | 1nhuman, borosto, forzetsky, m3wsu, shandarez |
|           13 |     3368 | 2024-02-20 | Clutch Gaming                | W   | 0.697      | 0.417        | -                | 0.216 (0.063)    | -             |     9.94 | 1nhuman, borosto, forzetsky, m3wsu, shandarez |
|           12 |     3643 | 2024-02-14 | Myth Avenue Gaming           | L   | 0.657      | -            | -                | -                | -             |   -10.93 | 1nhuman, eistar, forzetsky, m3wsu, shandarez  |
|           11 |     3683 | 2024-02-13 | LYG Gaming                   | W   | 0.651      | 0.417        | -                | 0.380 (0.103)    | -             |    10.57 | 1nhuman, borosto, forzetsky, m3wsu, shandarez |
|           10 |     3689 | 2024-02-13 | LYG Gaming                   | L   | 0.651      | -            | -                | -                | -             |   -10.12 | 1nhuman, borosto, forzetsky, m3wsu, shandarez |
|            9 |     4387 | 2024-01-24 | GR Gaming                    | L   | 0.518      | -            | -                | -                | -             |    -7.24 | 1nhuman, borosto, m3wsu, serrakura, shandarez |
|            8 |     4391 | 2024-01-24 | Steel Helmet                 | W   | 0.517      | 0.143        | 0.025 (0.002)    | -                | -             |     6.94 | 1nhuman, borosto, m3wsu, serrakura, shandarez |
|            7 |     4487 | 2024-01-22 | Wings Up Gaming              | L   | 0.504      | -            | -                | -                | -             |    -8.78 | 1nhuman, borosto, m3wsu, serrakura, shandarez |
|            6 |     4851 | 2024-01-15 | GR Gaming                    | L   | 0.456      | -            | -                | -                | -             |    -6.56 | 1nhuman, borosto, forzetsky, m3wsu, shandarez |
|            5 |     5898 | 2023-12-07 | NewHappy                     | L   | 0.197      | -            | -                | -                | -             |    -3.56 | 1nhuman, borosto, forzetsky, m3wsu, shandarez |
|            4 |     5945 | 2023-12-06 | ATOX Esports                 | W   | 0.190      | 0.417        | 0.112 (0.009)    | 0.769 (0.061)    | -             |     5.08 | 1nhuman, borosto, forzetsky, m3wsu, shandarez |
|            3 |     6001 | 2023-12-05 | Octagonal Disposition Gaming | W   | 0.184      | -            | -                | -                | -             |     1.57 | 1nhuman, borosto, forzetsky, m3wsu, shandarez |
|            2 |     6574 | 2023-11-22 | LYG Gaming                   | L   | 0.097      | -            | -                | -                | -             |    -1.54 | 1nhuman, borosto, forzetsky, m3wsu, shandarez |
|            1 |     6985 | 2023-11-13 | Born In Far East             | W   | 0.037      | -            | -                | -                | -             |     0.50 | 1nhuman, borosto, forzetsky, m3wsu, shandarez |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($433.80)
- Divide that value by the 5th highest value among all rosters ($158,437.64)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
