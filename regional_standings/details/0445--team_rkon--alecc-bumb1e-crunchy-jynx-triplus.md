### Roster Details<br />
Team Name: TEAM RKON<br />
Roster: alecc, Bumb1e, Crunchy, Jynx, TRIPLUS<br />
Region: [Asia]( ../standings_asia.md)<br />
<br />
Global Rank: [445](../standings_global.md)<br />
Regional Rank: [66]( ../standings_asia.md)<br />
Final Rank Value:  487.7<br />
<br />
Final Rank Value (487.7) = Starting Rank Value (490.8) + Head To Head Adjustments (-3.2)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.000[<sup>1</sup>](#table2)
- Bounty Collected: 0.178[<sup>2</sup>](#table1)
- Opponent Network: 0.001[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.045<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 490.8
- 400 + ( ( 0.045 - 0.000 ) / ( 0.787 - 0.000 ) ) * 1600 = 490.8


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent        | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           16 |     5966 | 2024-02-20 | Mindfreak       | L   | 0.535      | -            | -                | -                | -         |    -3.88 | alecc, Bumb1e, Crunchy, Jynx, TRIPLUS |
|           15 |     5972 | 2024-02-19 | Imports         | W   | 0.535      | 0.143        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     6.37 | alecc, Bumb1e, Crunchy, Jynx, TRIPLUS |
|           14 |     6360 | 2024-02-13 | KZG             | L   | 0.488      | -            | -                | -                | -         |    -3.27 | alecc, Bumb1e, Jynx, PixeL, TRIPLUS   |
|           13 |     6363 | 2024-02-13 | G1MPS           | W   | 0.488      | 0.143        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     5.88 | alecc, Bumb1e, Jynx, PixeL, TRIPLUS   |
|           12 |     7386 | 2024-01-23 | Jehovah witness | L   | 0.355      | -            | -                | -                | -         |    -5.25 | alecc, Bumb1e, Crunchy, Jynx, TRIPLUS |
|           11 |     7622 | 2024-01-19 | DXA Esports     | L   | 0.327      | -            | -                | -                | -         |    -6.46 | alecc, Crunchy, DINGUS, Jynx, TRIPLUS |
|           10 |     7690 | 2024-01-18 | FlyQuest        | L   | 0.321      | -            | -                | -                | -         |    -0.05 | alecc, Crunchy, DINGUS, Jynx, TRIPLUS |
|            9 |     7845 | 2024-01-17 | Arcade Esports  | L   | 0.308      | -            | -                | -                | -         |    -2.47 | alecc, Bumb1e, Crunchy, Jynx, TRIPLUS |
|            8 |     7980 | 2024-01-15 | DXA Esports     | L   | 0.295      | -            | -                | -                | -         |    -2.09 | alecc, Bumb1e, Crunchy, Jynx, TRIPLUS |
|            7 |     8052 | 2024-01-13 | Mindfreak       | L   | 0.282      | -            | -                | -                | -         |    -2.76 | alecc, Crunchy, DINGUS, Jynx, TRIPLUS |
|            6 |     8056 | 2024-01-13 | DXA Esports     | W   | 0.282      | 0.143        | 0.005 (0.000)    | 0.196 (0.008)    | 0 (0.000) |     6.93 | alecc, Crunchy, DINGUS, Jynx, TRIPLUS |
|            5 |     8143 | 2024-01-11 | Blingus         | W   | 0.274      | 0.143        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     3.23 | alecc, Crunchy, DINGUS, Jynx, TRIPLUS |
|            4 |     9157 | 2023-12-12 | Vantage Esports | L   | 0.068      | -            | -                | -                | -         |    -0.60 | alecc, Bumb1e, GYPSY, Jynx, versa     |
|            3 |     9393 | 2023-12-08 | Canon Event     | W   | 0.042      | 0.270        | 0.000 (0.000)    | 0.025 (0.000)    | 0 (0.000) |     0.70 | alecc, Bumb1e, GYPSY, Jynx, versa     |
|            2 |     9457 | 2023-12-07 | Altered Edge    | W   | 0.035      | 0.270        | 0.002 (0.000)    | 0.086 (0.001)    | 0 (0.000) |     0.77 | alecc, Bumb1e, GYPSY, Jynx, versa     |
|            1 |     9603 | 2023-12-05 | Mindfreak       | L   | 0.022      | -            | -                | -                | -         |    -0.21 | alecc, Bumb1e, GYPSY, Jynx, versa     |

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
