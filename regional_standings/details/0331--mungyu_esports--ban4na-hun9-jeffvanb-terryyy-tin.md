### Roster Details<br />
Team Name: MungYu Esports<br />
Roster: BaN4na, Hun9, JeffVanB, Terryyy, Tin<br />
Region: [Asia]( ../standings_asia.md)<br />
<br />
Global Rank: [331](../standings_global.md)<br />
Regional Rank: [54]( ../standings_asia.md)<br />
Final Rank Value:  546.9<br />
<br />
Final Rank Value (546.9) = Starting Rank Value (501.6) + Head To Head Adjustments (45.3)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.000[<sup>1</sup>](#table2)
- Bounty Collected: 0.194[<sup>2</sup>](#table1)
- Opponent Network: 0.011[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.051<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 501.6
- 400 + ( ( 0.051 - 0.000 ) / ( 0.806 - 0.000 ) ) * 1600 = 501.6


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent           | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins      | H2H Adj. | Roster                               |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           14 |     4568 | 2024-01-20 | Aravt              | L   | 0.490      | -            | -                | -                | -             |    -7.52 | BaN4na, Hun9, JeffVanB, Terryyy, Tin |
|           13 |     4613 | 2024-01-19 | The MongolZ        | L   | 0.483      | -            | -                | -                | -             |    -0.04 | BaN4na, Hun9, JeffVanB, Terryyy, Tin |
|           12 |     4616 | 2024-01-19 | The Huns Esports   | W   | 0.483      | 0.143        | 0.002 (0.000)    | 0.434 (0.030)    | false (0.000) |    13.44 | BaN4na, Hun9, JeffVanB, Terryyy, Tin |
|           11 |     4832 | 2024-01-15 | The Huns Esports   | W   | 0.457      | 0.143        | 0.002 (0.000)    | 0.434 (0.028)    | false (0.000) |    12.94 | BaN4na, Hun9, JeffVanB, Terryyy, Tin |
|           10 |     4833 | 2024-01-15 | GR Gaming          | W   | 0.457      | 0.143        | 0.006 (0.000)    | 0.495 (0.032)    | false (0.000) |    12.19 | BaN4na, Hun9, JeffVanB, Terryyy, Tin |
|            9 |     4847 | 2024-01-15 | Clutch Gaming      | W   | 0.456      | 0.143        | 0.001 (0.000)    | 0.216 (0.014)    | false (0.000) |    11.09 | BaN4na, Hun9, JeffVanB, Terryyy, Tin |
|            8 |     5217 | 2024-01-03 | TYLOO              | L   | 0.377      | -            | -                | -                | -             |    -0.56 | BaN4na, Hun9, JeffVanB, Terryyy, Tin |
|            7 |     5221 | 2024-01-02 | NewHappy           | L   | 0.375      | -            | -                | -                | -             |    -2.05 | BaN4na, Hun9, JeffVanB, Terryyy, Tin |
|            6 |     5244 | 2024-01-01 | Jadeite            | W   | 0.363      | 0.143        | 0.000 (0.000)    | 0.000 (0.000)    | false (0.000) |     4.07 | BaN4na, Hun9, JeffVanB, Terryyy, Tin |
|            5 |     5281 | 2023-12-23 | NewHappy           | L   | 0.302      | -            | -                | -                | -             |    -1.94 | BaN4na, Hun9, JeffVanB, Terryyy, Tin |
|            4 |     5285 | 2023-12-22 | Wings Up Gaming    | L   | 0.302      | -            | -                | -                | -             |    -2.23 | BaN4na, Hun9, JeffVanB, Terryyy, Tin |
|            3 |     5406 | 2023-12-16 | Talented Ynufe     | W   | 0.262      | 0.143        | 0.000 (0.000)    | 0.009 (0.000)    | false (0.000) |     2.99 | h1mz, Hun9, sunshinez, Terryyy, Tin  |
|            2 |     5411 | 2023-12-16 | AP Gaming          | W   | 0.262      | 0.143        | 0.000 (0.000)    | 0.000 (0.000)    | false (0.000) |     2.97 | h1mz, Hun9, sunshinez, Terryyy, Tin  |
|            1 |     6893 | 2023-11-15 | Lynn Vision Gaming | L   | 0.050      | -            | -                | -                | -             |    -0.02 | H1mz, Hun9, sunshinez, Terryyy, Tin  |

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
