### Roster Details<br />
Team Name: LOS<br />
Roster: history, JOTA, leo_drk, short, t9rnay<br />
Region: [Americas]( ../standings_americas.md)<br />
<br />
Global Rank: [338](../standings_global.md)<br />
Regional Rank: [77]( ../standings_americas.md)<br />
Final Rank Value:  517.7<br />
<br />
Final Rank Value (517.7) = Starting Rank Value (515.3) + Head To Head Adjustments (2.4)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.000[<sup>1</sup>](#table2)
- Bounty Collected: 0.230[<sup>2</sup>](#table1)
- Opponent Network: 0.003[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.058<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 515.3
- 400 + ( ( 0.058 - 0.000 ) / ( 0.806 - 0.000 ) ) * 1600 = 515.3


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent       | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins      | H2H Adj. | Roster                                |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           14 |     3561 | 2024-02-15 | E-Xolos LAZER  | L   | 0.667      | -            | -                | -                | -             |   -13.98 | history, JOTA, leo_drk, short, t9rnay |
|           13 |     4295 | 2024-01-26 | Carpe Diem     | L   | 0.534      | -            | -                | -                | -             |    -5.02 | history, JOTA, leo_drk, short, t9rnay |
|           12 |     4298 | 2024-01-26 | Revenge Nation | W   | 0.534      | 0.143        | 0.043 (0.003)    | 0.123 (0.009)    | false (0.000) |    12.46 | history, JOTA, leo_drk, short, t9rnay |
|           11 |     4414 | 2024-01-23 | MIGHT          | L   | 0.514      | -            | -                | -                | -             |    -3.70 | history, JOTA, leo_drk, short, t9rnay |
|           10 |     4687 | 2024-01-17 | Carpe Diem     | L   | 0.474      | -            | -                | -                | -             |    -4.12 | history, JOTA, leo_drk, short, t9rnay |
|            9 |     4821 | 2024-01-15 | Team Liquid    | L   | 0.461      | -            | -                | -                | -             |    -0.12 | history, JOTA, leo_drk, short, t9rnay |
|            8 |     4872 | 2024-01-13 | FLUFFY AIMERS  | W   | 0.448      | 0.143        | 0.004 (0.000)    | 0.103 (0.007)    | false (0.000) |    10.03 | history, JOTA, leo_drk, short, t9rnay |
|            7 |     4905 | 2024-01-12 | Elevate        | L   | 0.442      | -            | -                | -                | -             |    -2.62 | history, JOTA, leo_drk, short, t9rnay |
|            6 |     4913 | 2024-01-12 | Carpe Diem     | L   | 0.441      | -            | -                | -                | -             |    -3.42 | history, JOTA, leo_drk, short, t9rnay |
|            5 |     4963 | 2024-01-11 | Rocket         | L   | 0.435      | -            | -                | -                | -             |    -4.00 | history, JOTA, leo_drk, short, t9rnay |
|            4 |     4975 | 2024-01-11 | Xiaoma Gaming  | W   | 0.434      | 0.143        | 0.012 (0.001)    | 0.059 (0.004)    | false (0.000) |     8.57 | history, JOTA, leo_drk, short, t9rnay |
|            3 |     5064 | 2024-01-09 | Team Liquid    | L   | 0.421      | -            | -                | -                | -             |    -0.10 | history, JOTA, leo_drk, short, t9rnay |
|            2 |     5158 | 2024-01-07 | Limitless      | W   | 0.408      | 0.143        | 0.001 (0.000)    | 0.177 (0.010)    | false (0.000) |     9.10 | history, JOTA, leo_drk, short, t9rnay |
|            1 |     6290 | 2023-11-28 | BESTIA         | L   | 0.140      | -            | -                | -                | -             |    -0.69 | bt0, JOTA, short, steel, t9rnay       |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($0.00)
- Divide that value by the 5th highest value among all rosters ($158,437.64)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
