### Roster Details<br />
Team Name: Antic Esports<br />
Roster: InfrequeNt, James, kyson, Plam, RaZ<br />
Region: [Asia]( ../standings_asia.md)<br />
<br />
Global Rank: [318](../standings_global.md)<br />
Regional Rank: [52]( ../standings_asia.md)<br />
Final Rank Value:  586.5<br />
<br />
Final Rank Value (586.5) = Starting Rank Value (586.5) + Head To Head Adjustments (-0.1)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.213[<sup>1</sup>](#table2)
- Bounty Collected: 0.161[<sup>2</sup>](#table1)
- Opponent Network: 0.002[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.094<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 586.5
- 400 + ( ( 0.094 - 0.000 ) / ( 0.806 - 0.000 ) ) * 1600 = 586.5


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent                     | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                              |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           10 |     2348 | 2024-03-13 | MANTRA                       | L   | 0.843      | -            | -                | -                | -         |    -9.63 | InfrequeNt, James, kyson, Plam, RaZ |
|            9 |     2588 | 2024-03-07 | Underground Esports Club     | W   | 0.803      | 0.270        | 0.000 (0.000)    | 0.112 (0.024)    | 0 (0.000) |    11.54 | InfrequeNt, James, kyson, Plam, RaZ |
|            8 |     2659 | 2024-03-06 | Tuvalu Embassy               | W   | 0.796      | 0.270        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     6.54 | exe, InfrequeNt, James, kyson, RaZ  |
|            7 |     4407 | 2024-01-24 | Blitz (Australian team)      | L   | 0.516      | -            | -                | -                | -         |   -10.33 | James, jokes, kyson, Noisia, RaZ    |
|            6 |     6223 | 2023-11-30 | DXA Esports                  | L   | 0.149      | -            | -                | -                | -         |    -1.42 | James, jokes, kyson, Noisia, RaZ    |
|            5 |     6228 | 2023-11-30 | Dracula Flow                 | W   | 0.149      | 0.143        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     1.21 | James, jokes, kyson, Noisia, RaZ    |
|            4 |     6338 | 2023-11-28 | Balenciaga (Australian team) | W   | 0.136      | 0.143        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     1.11 | James, jokes, kyson, Noisia, RaZ    |
|            3 |     6903 | 2023-11-15 | KZG                          | W   | 0.049      | 0.143        | 0.000 (0.000)    | 0.001 (0.000)    | 0 (0.000) |     0.73 | James, jokes, Noisia, Plam, RaZ     |
|            2 |     7150 | 2023-11-09 | Golf Club                    | W   | 0.010      | 0.143        | 0.000 (0.000)    | 0.007 (0.000)    | 0 (0.000) |     0.15 | James, jokes, Noisia, Plam, RaZ     |
|            1 |     7212 | 2023-11-08 | MANTRA                       | W   | 0.003      | 0.143        | 0.000 (0.000)    | 0.005 (0.000)    | 0 (0.000) |     0.03 | James, jokes, Noisia, Plam, RaZ     |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($31.87)
- Divide that value by the 5th highest value among all rosters ($158,437.64)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
