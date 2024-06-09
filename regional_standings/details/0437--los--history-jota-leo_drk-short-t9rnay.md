### Roster Details<br />
Team Name: LOS<br />
Roster: history, JOTA, leo_drk, short, t9rnay<br />
Region: [Americas]( ../standings_americas.md)<br />
<br />
Global Rank: [437](../standings_global.md)<br />
Regional Rank: [109]( ../standings_americas.md)<br />
Final Rank Value:  512.5<br />
<br />
Final Rank Value (512.5) = Starting Rank Value (507.3) + Head To Head Adjustments (5.2)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.000[<sup>1</sup>](#table2)
- Bounty Collected: 0.209[<sup>2</sup>](#table1)
- Opponent Network: 0.002[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.053<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 507.3
- 400 + ( ( 0.053 - 0.000 ) / ( 0.787 - 0.000 ) ) * 1600 = 507.3


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent       | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           16 |     6193 | 2024-02-15 | E-Xolos LAZER  | L   | 0.506      | -            | -                | -                | -         |   -10.51 | history, JOTA, leo_drk, short, t9rnay |
|           15 |     7222 | 2024-01-26 | Carpe Diem     | L   | 0.373      | -            | -                | -                | -         |    -4.26 | history, JOTA, leo_drk, short, t9rnay |
|           14 |     7227 | 2024-01-26 | Revenge Nation | W   | 0.373      | 0.143        | 0.019 (0.001)    | 0.186 (0.010)    | 0 (0.000) |     8.71 | history, JOTA, leo_drk, short, t9rnay |
|           13 |     7390 | 2024-01-23 | MIGHT          | L   | 0.353      | -            | -                | -                | -         |    -3.16 | history, JOTA, leo_drk, short, t9rnay |
|           12 |     7755 | 2024-01-17 | Carpe Diem     | L   | 0.313      | -            | -                | -                | -         |    -3.47 | history, JOTA, leo_drk, short, t9rnay |
|           11 |     7941 | 2024-01-15 | Team Liquid    | L   | 0.300      | -            | -                | -                | -         |    -0.02 | history, JOTA, leo_drk, short, t9rnay |
|           10 |     8004 | 2024-01-14 | NRG            | L   | 0.292      | -            | -                | -                | -         |    -1.36 | history, JOTA, leo_drk, short, t9rnay |
|            9 |     8013 | 2024-01-13 | FLUFFY AIMERS  | W   | 0.286      | 0.143        | 0.001 (0.000)    | 0.026 (0.001)    | 0 (0.000) |     5.74 | history, JOTA, leo_drk, short, t9rnay |
|            8 |     8060 | 2024-01-12 | Elevate        | L   | 0.281      | -            | -                | -                | -         |    -1.28 | history, JOTA, leo_drk, short, t9rnay |
|            7 |     8072 | 2024-01-12 | Carpe Diem     | L   | 0.280      | -            | -                | -                | -         |    -3.07 | history, JOTA, leo_drk, short, t9rnay |
|            6 |     8141 | 2024-01-11 | Rocket         | L   | 0.274      | -            | -                | -                | -         |    -4.13 | history, JOTA, leo_drk, short, t9rnay |
|            5 |     8153 | 2024-01-11 | WICKED         | W   | 0.273      | 0.143        | 0.009 (0.000)    | 0.129 (0.005)    | 0 (0.000) |     6.48 | history, JOTA, leo_drk, short, t9rnay |
|            4 |     8157 | 2024-01-11 | Xiaoma Gaming  | W   | 0.273      | 0.143        | 0.005 (0.000)    | 0.082 (0.003)    | 0 (0.000) |     6.77 | history, JOTA, leo_drk, short, t9rnay |
|            3 |     8219 | 2024-01-10 | bubibabu       | W   | 0.267      | 0.143        | 0.000 (0.000)    | 0.007 (0.000)    | 0 (0.000) |     2.95 | history, JOTA, leo_drk, short, t9rnay |
|            2 |     8294 | 2024-01-09 | Team Liquid    | L   | 0.260      | -            | -                | -                | -         |    -0.01 | history, JOTA, leo_drk, short, t9rnay |
|            1 |     8440 | 2024-01-07 | Limitless      | W   | 0.247      | 0.143        | 0.001 (0.000)    | 0.123 (0.004)    | 0 (0.000) |     5.79 | history, JOTA, leo_drk, short, t9rnay |

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
