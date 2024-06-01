### Roster Details<br />
Team Name: Altered Edge<br />
Roster: Havoc, Mr Shark, Rahley, Scr1pt, Winnieeeee<br />
Region: [Asia]( ../standings_asia.md)<br />
<br />
Global Rank: [327](../standings_global.md)<br />
Regional Rank: [53]( ../standings_asia.md)<br />
Final Rank Value:  621.4<br />
<br />
Final Rank Value (621.4) = Starting Rank Value (640.0) + Head To Head Adjustments (-18.6)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.262[<sup>1</sup>](#table2)
- Bounty Collected: 0.204[<sup>2</sup>](#table1)
- Opponent Network: 0.006[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.118<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 640.0
- 400 + ( ( 0.118 - 0.000 ) / ( 0.786 - 0.000 ) ) * 1600 = 640.0


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent        | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                      |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           15 |     2880 | 2024-04-17 | KZG             | L   | 0.915      | -            | -                | -                | -         |   -11.39 | Havoc, Mr Shark, Rahley, Scr1pt, Winnieeeee |
|           14 |     3955 | 2024-03-24 | MANTRA          | L   | 0.755      | -            | -                | -                | -         |   -10.44 | Havoc, Mr Shark, Rahley, Scr1pt, Winnieeeee |
|           13 |     4104 | 2024-03-21 | Blitz           | W   | 0.735      | 0.270        | 0.000 (0.000)    | 0.089 (0.018)    | 0 (0.000) |     6.94 | Havoc, Mr Shark, Rahley, Scr1pt, Winnieeeee |
|           12 |     4338 | 2024-03-16 | MANTRA          | L   | 0.702      | -            | -                | -                | -         |   -10.14 | Havoc, Mr Shark, Rahley, Scr1pt, Winnieeeee |
|           11 |     4521 | 2024-03-13 | Arcade Esports  | W   | 0.682      | 0.270        | 0.000 (0.000)    | 0.018 (0.003)    | 0 (0.000) |     4.37 | Havoc, Mr Shark, Rahley, Scr1pt, Winnieeeee |
|           10 |     4827 | 2024-03-07 | CSTWO TEAM      | W   | 0.642      | 0.270        | 0.000 (0.000)    | 0.018 (0.003)    | 0 (0.000) |     4.17 | Havoc, Mr Shark, Rahley, Scr1pt, Winnieeeee |
|            9 |     5790 | 2024-02-20 | Arcade Esports  | L   | 0.535      | -            | -                | -                | -         |    -6.81 | BROJVHS, Havoc, luffy, Mr Shark, Winnieeeee |
|            8 |     5794 | 2024-02-20 | KZG             | W   | 0.535      | 0.143        | 0.011 (0.001)    | 0.223 (0.017)    | 0 (0.000) |    10.57 | BROJVHS, Havoc, luffy, Mr Shark, Winnieeeee |
|            7 |     5798 | 2024-02-20 | DXA Esports     | W   | 0.535      | 0.143        | 0.005 (0.000)    | 0.196 (0.015)    | 0 (0.000) |    10.13 | BROJVHS, Havoc, luffy, Mr Shark, Winnieeeee |
|            6 |     5904 | 2024-02-17 | FlyQuest        | L   | 0.521      | -            | -                | -                | -         |    -0.18 | Havoc, Mr Shark, Rahley, Scr1pt, Winnieeeee |
|            5 |     7594 | 2024-01-17 | sunday school   | L   | 0.308      | -            | -                | -                | -         |    -4.25 | ElephanT, Havoc, Rahley, Scr1pt, Winnieeeee |
|            4 |     7736 | 2024-01-14 | sunday school   | L   | 0.294      | -            | -                | -                | -         |    -4.17 | ElephanT, Havoc, Rahley, Scr1pt, Winnieeeee |
|            3 |     7887 | 2024-01-11 | Jehovah witness | L   | 0.274      | -            | -                | -                | -         |    -5.96 | ElephanT, Havoc, Rahley, Scr1pt, Winnieeeee |
|            2 |     9184 | 2023-12-07 | TEAM RKON       | L   | 0.035      | -            | -                | -                | -         |    -0.77 | ElephanT, Havoc, Rahley, Scr1pt, Winnieeeee |
|            1 |     9243 | 2023-12-06 | Golf Club       | L   | 0.029      | -            | -                | -                | -         |    -0.65 | ElephanT, Havoc, Rahley, Scr1pt, Winnieeeee |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($452.83)
- Divide that value by the 5th highest value among all rosters ($300,806.11)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
