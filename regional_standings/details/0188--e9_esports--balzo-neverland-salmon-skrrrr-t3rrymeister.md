### Roster Details<br />
Team Name: E9 esports<br />
Roster: Balzo, neverland, salmon, skrrrr, T3rrymeister<br />
Region: [Asia]( ../standings_asia.md)<br />
<br />
Global Rank: [188](../standings_global.md)<br />
Regional Rank: [23]( ../standings_asia.md)<br />
Final Rank Value:  739.6<br />
<br />
Final Rank Value (739.6) = Starting Rank Value (715.0) + Head To Head Adjustments (24.6)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.325[<sup>1</sup>](#table2)
- Bounty Collected: 0.251[<sup>2</sup>](#table1)
- Opponent Network: 0.004[<sup>2</sup>](#table1)
- LAN Wins: 0.040[<sup>2</sup>](#table1)

The average of these factors is 0.155<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 715.0
- 400 + ( ( 0.155 - 0.000 ) / ( 0.787 - 0.000 ) ) * 1600 = 715.0


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent                  | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                         |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           14 |     4761 | 2024-03-11 | NewHappy                  | L   | 0.668      | -            | -                | -                | -         |    -8.75 | Balzo, neverland, salmon, skrrrr, T3rrymeister |
|           13 |     4803 | 2024-03-10 | ATOX Esports              | L   | 0.661      | -            | -                | -                | -         |    -1.35 | Balzo, neverland, salmon, skrrrr, T3rrymeister |
|           12 |     4868 | 2024-03-09 | NewHappy                  | W   | 0.655      | 0.143        | 0.020 (0.002)    | 0.231 (0.022)    | 0 (0.000) |    12.05 | Balzo, neverland, salmon, skrrrr, T3rrymeister |
|           11 |     4869 | 2024-03-08 | AP Gaming                 | W   | 0.654      | 0.143        | 0.042 (0.004)    | 0.106 (0.010)    | 0 (0.000) |    14.31 | Balzo, neverland, salmon, skrrrr, T3rrymeister |
|           10 |     4898 | 2024-03-08 | ATOX Esports              | L   | 0.648      | -            | -                | -                | -         |    -1.17 | Balzo, neverland, salmon, skrrrr, T3rrymeister |
|            9 |     4962 | 2024-03-07 | AP Gaming                 | W   | 0.642      | 0.143        | 0.042 (0.004)    | 0.106 (0.010)    | 0 (0.000) |    14.58 | Balzo, neverland, salmon, skrrrr, T3rrymeister |
|            8 |     7214 | 2024-01-27 | Team NKT                  | L   | 0.375      | -            | -                | -                | -         |    -5.48 | N1nE, neverland, salmon, T3rrymeister, Tikkkk  |
|            7 |     7218 | 2024-01-26 | Những Chàng Trai Đeo Kính | W   | 0.374      | 0.435        | 0.002 (0.000)    | 0.011 (0.002)    | 1 (0.374) |     4.71 | N1nE, neverland, salmon, T3rrymeister, Tikkkk  |
|            6 |     7285 | 2024-01-26 | Team NKT                  | L   | 0.369      | -            | -                | -                | -         |    -5.47 | N1nE, neverland, salmon, T3rrymeister, Tikkkk  |
|            5 |     8050 | 2024-01-13 | Change The Game           | L   | 0.282      | -            | -                | -                | -         |    -5.58 | kylin, N1nE, salmon, T3rrymeister, Tikkkk      |
|            4 |     8057 | 2024-01-13 | TigerMan Esports          | W   | 0.281      | 0.143        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     2.11 | kylin, N1nE, salmon, T3rrymeister, Tikkkk      |
|            3 |     8435 | 2024-01-08 | PA Esports                | W   | 0.249      | 0.143        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     1.87 | kylin, N1nE, salmon, T3rrymeister, Tikkkk      |
|            2 |     8880 | 2023-12-16 | 川渝一棵松                     | W   | 0.097      | 0.143        | 0.000 (0.000)    | 0.003 (0.000)    | 0 (0.000) |     0.97 | kylin, N1nE, salmon, T3rrymeister, Tikkkk      |
|            1 |     8899 | 2023-12-16 | Nalakuvara                | W   | 0.096      | 0.143        | 0.013 (0.000)    | 0.051 (0.001)    | 0 (0.000) |     1.80 | kylin, N1nE, salmon, T3rrymeister, Tikkkk      |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($2,537.90)
- Divide that value by the 5th highest value among all rosters ($300,806.11)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-03-11 |      0.669 | $2,783.23      | $1,861.67       |
| 2024-01-28 |      0.382 | $1,250.00      | $477.78         |
| 2024-01-13 |      0.282 | $703.18        | $198.45         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
