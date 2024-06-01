### Roster Details<br />
Team Name: Underground Esports Club<br />
Roster: beep, cl0ver, coops, Mechanical, Prime7<br />
Region: [Asia]( ../standings_asia.md)<br />
<br />
Global Rank: [408](../standings_global.md)<br />
Regional Rank: [59]( ../standings_asia.md)<br />
Final Rank Value:  544.2<br />
<br />
Final Rank Value (544.2) = Starting Rank Value (579.9) + Head To Head Adjustments (-35.7)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.203[<sup>1</sup>](#table2)
- Bounty Collected: 0.151[<sup>2</sup>](#table1)
- Opponent Network: 0.000[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.088<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 579.9
- 400 + ( ( 0.088 - 0.000 ) / ( 0.786 - 0.000 ) ) * 1600 = 579.9


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent       | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                  |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           13 |     4392 | 2024-03-15 | LE-LUX Esports | L   | 0.695      | -            | -                | -                | -         |    -9.50 | beep, cl0ver, coops, Mechanical, Prime7 |
|           12 |     4396 | 2024-03-15 | Invictus       | W   | 0.694      | 0.143        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     9.24 | beep, cl0ver, coops, Mechanical, Prime7 |
|           11 |     4447 | 2024-03-14 | Arcade Esports | L   | 0.688      | -            | -                | -                | -         |    -6.25 | beep, cl0ver, coops, Mechanical, Prime7 |
|           10 |     4452 | 2024-03-14 | 500x           | W   | 0.688      | 0.143        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     9.44 | beep, cl0ver, coops, Mechanical, Prime7 |
|            9 |     4519 | 2024-03-13 | Blitz          | L   | 0.682      | -            | -                | -                | -         |   -13.29 | beeb, cl0ver, coops, Mechanical, Prime7 |
|            8 |     4633 | 2024-03-11 | Abyss          | W   | 0.668      | 0.270        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     6.01 | beeb, cl0ver, coops, Mechanical, Prime7 |
|            7 |     4830 | 2024-03-07 | Antic Esports  | L   | 0.642      | -            | -                | -                | -         |   -12.17 | beeb, cl0ver, coops, Mechanical, Prime7 |
|            6 |     5800 | 2024-02-19 | KZG            | L   | 0.535      | -            | -                | -                | -         |    -4.79 | beeb, cl0ver, coops, Mechanical, Prime7 |
|            5 |     5910 | 2024-02-17 | MANTRA         | L   | 0.521      | -            | -                | -                | -         |    -6.42 | beeb, cl0ver, coops, Mechanical, Prime7 |
|            4 |     6176 | 2024-02-13 | DXA Esports    | L   | 0.488      | -            | -                | -                | -         |    -4.92 | beeb, cl0ver, coops, Poccket, Prime7    |
|            3 |     6183 | 2024-02-12 | Dropout        | W   | 0.488      | 0.143        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     4.20 | beeb, cl0ver, coops, Poccket, Prime7    |
|            2 |     7148 | 2024-01-24 | DXA Esports    | L   | 0.355      | -            | -                | -                | -         |    -3.46 | beeb, cl0ver, coops, Mechanical, Prime7 |
|            1 |     7732 | 2024-01-15 | Mindfreak      | L   | 0.295      | -            | -                | -                | -         |    -3.78 | beeb, cl0ver, coops, Mechanical, Prime7 |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($35.15)
- Divide that value by the 5th highest value among all rosters ($300,806.11)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
