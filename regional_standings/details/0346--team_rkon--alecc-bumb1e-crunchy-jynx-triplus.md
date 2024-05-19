### Roster Details<br />
Team Name: TEAM RKON<br />
Roster: alecc, Bumb1e, Crunchy, Jynx, TRIPLUS<br />
Region: [Asia]( ../standings_asia.md)<br />
<br />
Global Rank: [346](../standings_global.md)<br />
Regional Rank: [55]( ../standings_asia.md)<br />
Final Rank Value:  497.4<br />
<br />
Final Rank Value (497.4) = Starting Rank Value (499.1) + Head To Head Adjustments (-1.6)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.000[<sup>1</sup>](#table2)
- Bounty Collected: 0.197[<sup>2</sup>](#table1)
- Opponent Network: 0.003[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.050<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 499.1
- 400 + ( ( 0.050 - 0.000 ) / ( 0.806 - 0.000 ) ) * 1600 = 499.1


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent                    | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           15 |     3380 | 2024-02-20 | Mindfreak (Australian team) | L   | 0.696      | -            | -                | -                | -         |    -5.36 | alecc, Bumb1e, Crunchy, Jynx, TRIPLUS |
|           14 |     3385 | 2024-02-19 | Imports                     | W   | 0.696      | 0.143        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     7.96 | alecc, Bumb1e, Crunchy, Jynx, TRIPLUS |
|           13 |     3696 | 2024-02-13 | KZG                         | L   | 0.649      | -            | -                | -                | -         |    -4.54 | alecc, Bumb1e, Jynx, PixeL, TRIPLUS   |
|           12 |     3699 | 2024-02-13 | G1MPS                       | W   | 0.649      | 0.143        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     7.52 | alecc, Bumb1e, Jynx, PixeL, TRIPLUS   |
|           11 |     4411 | 2024-01-23 | Jehovah witness             | L   | 0.516      | -            | -                | -                | -         |    -7.79 | alecc, Bumb1e, Crunchy, Jynx, TRIPLUS |
|           10 |     4579 | 2024-01-19 | DXA Esports                 | L   | 0.488      | -            | -                | -                | -         |    -9.92 | alecc, Crunchy, DINGUS, Jynx, TRIPLUS |
|            9 |     4631 | 2024-01-18 | FlyQuest                    | L   | 0.482      | -            | -                | -                | -         |    -0.12 | alecc, Crunchy, DINGUS, Jynx, TRIPLUS |
|            8 |     4760 | 2024-01-17 | VexX Gaming                 | L   | 0.469      | -            | -                | -                | -         |    -3.88 | alecc, Bumb1e, Crunchy, Jynx, TRIPLUS |
|            7 |     4850 | 2024-01-15 | DXA Esports                 | L   | 0.456      | -            | -                | -                | -         |    -3.29 | alecc, Bumb1e, Crunchy, Jynx, TRIPLUS |
|            6 |     4899 | 2024-01-13 | Mindfreak (Australian team) | L   | 0.443      | -            | -                | -                | -         |    -4.07 | alecc, Crunchy, DINGUS, Jynx, TRIPLUS |
|            5 |     4902 | 2024-01-13 | DXA Esports                 | W   | 0.443      | 0.143        | 0.010 (0.001)    | 0.266 (0.017)    | 0 (0.000) |    10.86 | alecc, Crunchy, DINGUS, Jynx, TRIPLUS |
|            4 |     4965 | 2024-01-11 | Blingus                     | W   | 0.435      | 0.143        | 0.000 (0.000)    | 0.005 (0.000)    | 0 (0.000) |     6.00 | alecc, Crunchy, DINGUS, Jynx, TRIPLUS |
|            3 |     5852 | 2023-12-08 | Canon Event                 | W   | 0.203      | 0.270        | 0.000 (0.000)    | 0.035 (0.002)    | 0 (0.000) |     2.30 | alecc, Bumb1e, GYPSY, Jynx, versa     |
|            2 |     5901 | 2023-12-07 | Altered Edge                | W   | 0.196      | 0.270        | 0.003 (0.000)    | 0.138 (0.007)    | 0 (0.000) |     4.34 | alecc, Bumb1e, GYPSY, Jynx, versa     |
|            1 |     6009 | 2023-12-05 | Mindfreak (Australian team) | L   | 0.183      | -            | -                | -                | -         |    -1.66 | alecc, Bumb1e, GYPSY, Jynx, versa     |

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
