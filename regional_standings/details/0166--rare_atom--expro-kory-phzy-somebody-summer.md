### Roster Details<br />
Team Name: Rare Atom<br />
Roster: EXPRO, kory, phzy, somebody, Summer<br />
Region: [Asia]( ../standings_asia.md)<br />
<br />
Global Rank: [166](../standings_global.md)<br />
Regional Rank: [18]( ../standings_asia.md)<br />
Final Rank Value:  766.0<br />
<br />
Final Rank Value (766.0) = Starting Rank Value (703.6) + Head To Head Adjustments (62.4)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.338[<sup>1</sup>](#table2)
- Bounty Collected: 0.250[<sup>2</sup>](#table1)
- Opponent Network: 0.009[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.149<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 703.6
- 400 + ( ( 0.149 - 0.000 ) / ( 0.787 - 0.000 ) ) * 1600 = 703.6


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent           | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                              |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           27 |     5015 | 2024-03-06 | Cloud9             | L   | 0.637      | -            | -                | -                | -         |    -0.31 | EXPRO, kory, phzy, somebody, Summer |
|           26 |     6841 | 2024-02-02 | GR Gaming          | W   | 0.416      | 0.143        | 0.007 (0.000)    | 0.428 (0.025)    | 0 (0.000) |     7.21 | EXPRO, kory, phzy, somebody, Summer |
|           25 |     6844 | 2024-02-02 | TYLOO              | W   | 0.415      | 0.143        | 0.017 (0.001)    | 0.131 (0.008)    | 0 (0.000) |     8.29 | EXPRO, kory, phzy, somebody, Summer |
|           24 |     6944 | 2024-01-31 | Team NKT           | W   | 0.403      | 0.143        | 0.006 (0.000)    | 0.158 (0.009)    | 0 (0.000) |     6.49 | EXPRO, kory, phzy, somebody, Summer |
|           23 |     6947 | 2024-01-31 | Lynn Vision Gaming | W   | 0.403      | 0.143        | 0.063 (0.004)    | 0.431 (0.025)    | 0 (0.000) |    11.23 | EXPRO, kory, phzy, somebody, Summer |
|           22 |     6953 | 2024-01-31 | ATOX Esports       | L   | 0.402      | -            | -                | -                | -         |    -0.67 | EXPRO, kory, phzy, somebody, Summer |
|           21 |     7313 | 2024-01-25 | AP Gaming          | W   | 0.363      | 0.143        | 0.042 (0.002)    | 0.106 (0.005)    | 0 (0.000) |     8.24 | EXPRO, kory, phzy, somebody, Summer |
|           20 |     7317 | 2024-01-25 | Wings Up Gaming    | L   | 0.362      | -            | -                | -                | -         |    -6.03 | EXPRO, kory, phzy, somebody, Summer |
|           19 |     7319 | 2024-01-25 | NewHappy           | W   | 0.362      | 0.143        | 0.003 (0.000)    | 0.066 (0.003)    | 0 (0.000) |     5.11 | EXPRO, kory, phzy, somebody, Summer |
|           18 |     7325 | 2024-01-24 | Change The Game    | W   | 0.361      | -            | -                | -                | 0 (0.000) |     4.24 | EXPRO, kory, phzy, somebody, Summer |
|           17 |     7365 | 2024-01-24 | Eruption           | W   | 0.356      | 0.143        | -                | 0.064 (0.003)    | 0 (0.000) |     3.89 | EXPRO, kory, phzy, somebody, Summer |
|           16 |     7368 | 2024-01-24 | Drippy Lab         | W   | 0.356      | -            | -                | -                | 0 (0.000) |     1.63 | EXPRO, kory, phzy, somebody, Summer |
|           15 |     7484 | 2024-01-22 | ATOX Esports       | L   | 0.343      | -            | -                | -                | -         |    -0.50 | EXPRO, kory, phzy, somebody, Summer |
|           14 |     7487 | 2024-01-22 | NOBackstab         | W   | 0.343      | -            | -                | -                | 0 (0.000) |     1.57 | EXPRO, kory, phzy, somebody, Summer |
|           13 |     7528 | 2024-01-21 | TYLOO              | L   | 0.336      | -            | -                | -                | -         |    -3.91 | EXPRO, kory, phzy, somebody, Summer |
|           12 |     7534 | 2024-01-21 | NewHappy           | W   | 0.335      | -            | -                | -                | -         |     4.93 | EXPRO, kory, phzy, somebody, Summer |
|           11 |     7616 | 2024-01-20 | Wings Up Gaming    | W   | 0.328      | 0.143        | 0.006 (0.000)    | 0.086 (0.004)    | -         |     4.88 | EXPRO, kory, phzy, somebody, Summer |
|           10 |     7620 | 2024-01-19 | SHPL               | W   | 0.327      | 0.143        | 0.022 (0.001)    | 0.100 (0.005)    | -         |     7.12 | EXPRO, kory, phzy, somebody, Summer |
|            9 |     7684 | 2024-01-18 | NewHappy           | L   | 0.321      | -            | -                | -                | -         |    -5.34 | EXPRO, kory, phzy, somebody, Summer |
|            8 |     8123 | 2024-01-12 | Steel Helmet       | L   | 0.276      | -            | -                | -                | -         |    -4.68 | EXPRO, kory, phzy, somebody, Summer |
|            7 |     8128 | 2024-01-12 | SHPL               | W   | 0.276      | 0.143        | 0.022 (0.001)    | 0.100 (0.004)    | -         |     6.07 | EXPRO, kory, phzy, somebody, Summer |
|            6 |     8149 | 2024-01-11 | 侧面男孩               | W   | 0.274      | -            | -                | -                | -         |     1.32 | EXPRO, kory, phzy, somebody, Summer |
|            5 |     8592 | 2023-12-23 | NewHappy           | L   | 0.142      | -            | -                | -                | -         |    -2.46 | EXPRO, kory, phzy, somebody, Summer |
|            4 |     8598 | 2023-12-22 | Lynn Vision Gaming | L   | 0.141      | -            | -                | -                | -         |    -0.42 | EXPRO, kory, phzy, somebody, Summer |
|            3 |     8603 | 2023-12-22 | Steel Helmet       | W   | 0.141      | 0.143        | 0.012 (0.000)    | -                | -         |     2.03 | EXPRO, kory, phzy, somebody, Summer |
|            2 |     8893 | 2023-12-16 | MIRAI Gaming       | W   | 0.096      | -            | -                | -                | -         |     1.53 | EXPRO, kory, phzy, somebody, Summer |
|            1 |     9016 | 2023-12-15 | ZEUSGG             | W   | 0.089      | -            | -                | -                | -         |     0.89 | EXPRO, kory, phzy, somebody, Summer |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($3,322.57)
- Divide that value by the 5th highest value among all rosters ($300,806.11)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
