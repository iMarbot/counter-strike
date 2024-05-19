### Roster Details<br />
Team Name: Underground Esports Club<br />
Roster: beep, cl0ver, coops, Mechanical, Prime7<br />
Region: [Asia]( ../standings_asia.md)<br />
<br />
Global Rank: [330](../standings_global.md)<br />
Regional Rank: [53]( ../standings_asia.md)<br />
Final Rank Value:  548.7<br />
<br />
Final Rank Value (548.7) = Starting Rank Value (588.9) + Head To Head Adjustments (-40.2)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.219[<sup>1</sup>](#table2)
- Bounty Collected: 0.162[<sup>2</sup>](#table1)
- Opponent Network: 0.000[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.095<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 588.9
- 400 + ( ( 0.095 - 0.000 ) / ( 0.806 - 0.000 ) ) * 1600 = 588.9


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent                    | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                     |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           14 |     2231 | 2024-03-15 | LE-LUX Esports              | L   | 0.856      | -            | -                | -                | -         |   -11.14 | beep, cl0ver, coops, Mechanical, Prime7    |
|           13 |     2235 | 2024-03-15 | Invictus (Australian team)  | W   | 0.856      | 0.143        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |    11.26 | beep, cl0ver, coops, Mechanical, Prime7    |
|           12 |     2285 | 2024-03-14 | VexX Gaming                 | L   | 0.849      | -            | -                | -                | -         |    -6.27 | beep, cl0ver, coops, Mechanical, Prime7    |
|           11 |     2290 | 2024-03-14 | 500x                        | W   | 0.849      | 0.143        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |    11.63 | beep, cl0ver, coops, Mechanical, Prime7    |
|           10 |     2344 | 2024-03-13 | Blitz (Australian team)     | L   | 0.843      | -            | -                | -                | -         |   -15.54 | beeb, cl0ver, coops, Mechanical, Prime7    |
|            9 |     2437 | 2024-03-11 | Abyss (Australian team)     | W   | 0.830      | 0.270        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     7.60 | beeb, cl0ver, coops, Mechanical, Prime7    |
|            8 |     2588 | 2024-03-07 | Antic Esports               | L   | 0.803      | -            | -                | -                | -         |   -11.54 | beeb, cl0ver, coops, Mechanical, Prime7    |
|            7 |     3384 | 2024-02-19 | KZG                         | L   | 0.696      | -            | -                | -                | -         |    -6.22 | beeb, cl0ver, coops, Mechanical, Prime7    |
|            6 |     3473 | 2024-02-17 | MANTRA                      | L   | 0.682      | -            | -                | -                | -         |    -7.84 | beeb, cl0ver, coops, Mechanical, Prime7    |
|            5 |     3697 | 2024-02-13 | DXA Esports                 | L   | 0.649      | -            | -                | -                | -         |    -6.20 | beeb, cl0ver, coops, Poccket, Prime7       |
|            4 |     3703 | 2024-02-12 | Dropout                     | W   | 0.649      | 0.143        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     5.44 | beeb, cl0ver, coops, Poccket, Prime7       |
|            3 |     4408 | 2024-01-24 | DXA Esports                 | L   | 0.516      | -            | -                | -                | -         |    -4.72 | beeb, cl0ver, coops, Mechanical, Prime7    |
|            2 |     4854 | 2024-01-15 | Mindfreak (Australian team) | L   | 0.456      | -            | -                | -                | -         |    -5.29 | beeb, cl0ver, coops, Mechanical, Prime7    |
|            1 |     6229 | 2023-11-29 | DXA Esports                 | L   | 0.149      | -            | -                | -                | -         |    -1.42 | cl0ver, coops, Mechanical, Michael, Prime7 |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($43.07)
- Divide that value by the 5th highest value among all rosters ($158,437.64)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
