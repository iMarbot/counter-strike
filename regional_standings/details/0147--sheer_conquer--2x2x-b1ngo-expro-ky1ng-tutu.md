### Roster Details<br />
Team Name: Sheer Conquer<br />
Roster: 2X2X, B1NGO, EXPRO, Ky1ng, tutu<br />
Region: [Asia]( ../standings_asia.md)<br />
<br />
Global Rank: [147](../standings_global.md)<br />
Regional Rank: [17]( ../standings_asia.md)<br />
Final Rank Value:  786.0<br />
<br />
Final Rank Value (786.0) = Starting Rank Value (723.9) + Head To Head Adjustments (62.1)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.361[<sup>1</sup>](#table2)
- Bounty Collected: 0.263[<sup>2</sup>](#table1)
- Opponent Network: 0.013[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.159<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 723.9
- 400 + ( ( 0.159 - 0.000 ) / ( 0.787 - 0.000 ) ) * 1600 = 723.9


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent           | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                          |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           11 |     1859 | 2024-05-04 | Noobs But Diligent | L   | 1.000      | -            | -                | -                | -         |   -17.20 | 2X2X, B1NGO, EXPRO, Ky1ng, tutu |
|           10 |     1877 | 2024-05-04 | AP Gaming          | L   | 1.000      | -            | -                | -                | -         |   -14.24 | 2X2X, B1NGO, EXPRO, Ky1ng, tutu |
|            9 |     2698 | 2024-04-20 | Noobs But Diligent | W   | 0.935      | 0.143        | 0.014 (0.002)    | 0.138 (0.018)    | 0 (0.000) |    13.21 | 2X2X, B1NGO, EXPRO, Ky1ng, tutu |
|            8 |     2708 | 2024-04-19 | XNL Gaming         | W   | 0.934      | 0.143        | 0.003 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     5.57 | 2X2X, B1NGO, EXPRO, Ky1ng, tutu |
|            7 |     2914 | 2024-04-17 | TYLOO              | L   | 0.915      | -            | -                | -                | -         |   -10.11 | 2X2X, B1NGO, EXPRO, Ky1ng, tutu |
|            6 |     2922 | 2024-04-17 | DEWA United        | W   | 0.915      | 0.143        | 0.002 (0.000)    | 0.176 (0.023)    | 0 (0.000) |    10.91 | 2X2X, B1NGO, EXPRO, Ky1ng, tutu |
|            5 |     2981 | 2024-04-16 | GR Gaming          | W   | 0.909      | 0.143        | 0.007 (0.001)    | 0.428 (0.056)    | 0 (0.000) |    18.26 | 2X2X, B1NGO, EXPRO, Ky1ng, tutu |
|            4 |     3118 | 2024-04-13 | StudFarm Esport    | W   | 0.888      | 0.143        | 0.009 (0.001)    | 0.045 (0.006)    | 0 (0.000) |     9.90 | 2X2X, B1NGO, EXPRO, Ky1ng, tutu |
|            3 |     3120 | 2024-04-12 | AP Gaming          | W   | 0.887      | 0.143        | 0.042 (0.005)    | 0.106 (0.013)    | 0 (0.000) |    17.33 | 2X2X, B1NGO, EXPRO, Ky1ng, tutu |
|            2 |     3503 | 2024-04-06 | StudFarm Esport    | W   | 0.841      | 0.143        | 0.009 (0.001)    | 0.045 (0.005)    | 0 (0.000) |    10.73 | 2X2X, B1NGO, EXPRO, Ky1ng, tutu |
|            1 |     3510 | 2024-04-05 | AP Gaming          | W   | 0.841      | 0.143        | 0.042 (0.005)    | 0.106 (0.013)    | 0 (0.000) |    17.75 | 2X2X, B1NGO, EXPRO, Ky1ng, tutu |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($5,062.81)
- Divide that value by the 5th highest value among all rosters ($300,806.11)
- The final value (0.02) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-05-05 |      1.000 | $1,381.73      | $1,381.73       |
| 2024-04-20 |      0.935 | $1,381.25      | $1,291.09       |
| 2024-04-13 |      0.888 | $1,381.78      | $1,226.71       |
| 2024-04-06 |      0.841 | $1,382.57      | $1,163.28       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
