### Roster Details<br />
Team Name: Altered Edge<br />
Roster: Havoc, Mr Shark, Rahley, Scr1pt, Winnieeeee<br />
Region: [Asia]( ../standings_asia.md)<br />
<br />
Global Rank: [271](../standings_global.md)<br />
Regional Rank: [47]( ../standings_asia.md)<br />
Final Rank Value:  643.1<br />
<br />
Final Rank Value (643.1) = Starting Rank Value (657.3) + Head To Head Adjustments (-14.2)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.289[<sup>1</sup>](#table2)
- Bounty Collected: 0.221[<sup>2</sup>](#table1)
- Opponent Network: 0.008[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.130<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 657.3
- 400 + ( ( 0.130 - 0.000 ) / ( 0.806 - 0.000 ) ) * 1600 = 657.3


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent                         | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                      |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           13 |      980 | 2024-04-17 | KZG                              | L   | 1.000      | -            | -                | -                | -         |   -13.69 | Havoc, Mr Shark, Rahley, Scr1pt, Winnieeeee |
|           12 |     1869 | 2024-03-24 | MANTRA                           | L   | 0.916      | -            | -                | -                | -         |   -12.31 | Havoc, Mr Shark, Rahley, Scr1pt, Winnieeeee |
|           11 |     1998 | 2024-03-21 | Blitz (Australian team)          | W   | 0.896      | 0.270        | 0.000 (0.000)    | 0.109 (0.026)    | 0 (0.000) |     8.20 | Havoc, Mr Shark, Rahley, Scr1pt, Winnieeeee |
|           10 |     2185 | 2024-03-16 | MANTRA                           | L   | 0.863      | -            | -                | -                | -         |   -12.24 | Havoc, Mr Shark, Rahley, Scr1pt, Winnieeeee |
|            9 |     2346 | 2024-03-13 | Arcade Esports (Australian team) | W   | 0.843      | 0.270        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     4.50 | Havoc, Mr Shark, Rahley, Scr1pt, Winnieeeee |
|            8 |     2585 | 2024-03-07 | CSTWO TEAM                       | W   | 0.803      | 0.270        | 0.000 (0.000)    | 0.029 (0.006)    | 0 (0.000) |     4.61 | Havoc, Mr Shark, Rahley, Scr1pt, Winnieeeee |
|            7 |     3377 | 2024-02-20 | VexX Gaming                      | L   | 0.696      | -            | -                | -                | -         |    -8.78 | BROJVHS, Havoc, luffy, Mr Shark, Winnieeeee |
|            6 |     3378 | 2024-02-20 | KZG                              | W   | 0.696      | 0.143        | 0.020 (0.002)    | 0.249 (0.025)    | 0 (0.000) |    13.00 | BROJVHS, Havoc, luffy, Mr Shark, Winnieeeee |
|            5 |     3382 | 2024-02-20 | DXA Esports                      | W   | 0.696      | 0.143        | 0.010 (0.001)    | 0.266 (0.026)    | 0 (0.000) |    13.16 | BROJVHS, Havoc, luffy, Mr Shark, Winnieeeee |
|            4 |     3471 | 2024-02-17 | FlyQuest                         | L   | 0.682      | -            | -                | -                | -         |    -0.34 | Havoc, Mr Shark, Rahley, Scr1pt, Winnieeeee |
|            3 |     5901 | 2023-12-07 | TEAM RKON                        | L   | 0.196      | -            | -                | -                | -         |    -4.34 | ElephanT, Havoc, Rahley, Scr1pt, Winnieeeee |
|            2 |     5950 | 2023-12-06 | Golf Club                        | L   | 0.190      | -            | -                | -                | -         |    -3.60 | ElephanT, Havoc, Rahley, Scr1pt, Winnieeeee |
|            1 |     6227 | 2023-11-30 | Mindfreak (Australian team)      | L   | 0.149      | -            | -                | -                | -         |    -2.32 | ElephanT, Havoc, Rahley, Scr1pt, Winnieeeee |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($549.47)
- Divide that value by the 5th highest value among all rosters ($158,437.64)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
