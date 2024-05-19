### Roster Details<br />
Team Name: Mindfreak (Australian team)<br />
Roster: gump, pain, Sliimey, supar, tucks<br />
Region: [Asia]( ../standings_asia.md)<br />
<br />
Global Rank: [133](../standings_global.md)<br />
Regional Rank: [17]( ../standings_asia.md)<br />
Final Rank Value:  796.8<br />
<br />
Final Rank Value (796.8) = Starting Rank Value (694.8) + Head To Head Adjustments (102.0)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.252[<sup>1</sup>](#table2)
- Bounty Collected: 0.290[<sup>2</sup>](#table1)
- Opponent Network: 0.053[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.149<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 694.8
- 400 + ( ( 0.149 - 0.000 ) / ( 0.806 - 0.000 ) ) * 1600 = 694.8


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent                         | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                               |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           21 |      619 | 2024-04-22 | Vantage Esports                  | W   | 1.000      | 0.333        | 0.000 (0.000)    | 0.236 (0.079)    | 0 (0.000) |    10.27 | gump, pain, Sliimey, supar, tucks    |
|           20 |      621 | 2024-04-22 | Vantage Esports                  | W   | 1.000      | 0.333        | 0.000 (0.000)    | 0.236 (0.079)    | 0 (0.000) |    11.12 | gump, pain, Sliimey, supar, tucks    |
|           19 |      847 | 2024-04-19 | Bad News Kangaroos               | L   | 1.000      | -            | -                | -                | -         |    -9.49 | gump, pain, Sliimey, supar, tucks    |
|           18 |      855 | 2024-04-18 | FlyQuest                         | L   | 1.000      | -            | -                | -                | -         |    -0.93 | gump, pain, Sliimey, supar, tucks    |
|           17 |      908 | 2024-04-18 | DXA Esports                      | W   | 1.000      | 0.143        | 0.010 (0.001)    | 0.266 (0.038)    | 0 (0.000) |    11.19 | gump, pain, Sliimey, supar, tucks    |
|           16 |      959 | 2024-04-17 | KZG                              | W   | 1.000      | 0.143        | 0.020 (0.003)    | 0.249 (0.036)    | 0 (0.000) |    12.66 | gump, pain, Sliimey, supar, tucks    |
|           15 |      972 | 2024-04-17 | 500x                             | W   | 1.000      | 0.143        | 0.000 (0.000)    | -                | 0 (0.000) |     5.52 | gump, pain, Sliimey, supar, tucks    |
|           14 |     1246 | 2024-04-10 | DXA Esports                      | W   | 1.000      | 0.333        | 0.010 (0.003)    | 0.266 (0.089)    | 0 (0.000) |    12.33 | gump, pain, Sliimey, supar, tucks    |
|           13 |     1252 | 2024-04-10 | DXA Esports                      | W   | 1.000      | 0.333        | 0.010 (0.003)    | 0.266 (0.089)    | 0 (0.000) |    13.43 | gump, pain, Sliimey, supar, tucks    |
|           12 |     1553 | 2024-04-03 | Canon Event                      | W   | 0.983      | 0.333        | 0.000 (0.000)    | 0.035 (0.012)    | 0 (0.000) |     3.66 | gump, pain, Sliimey, supar, tucks    |
|           11 |     1557 | 2024-04-03 | Canon Event                      | W   | 0.983      | 0.333        | -                | 0.035 (0.012)    | 0 (0.000) |     3.79 | gump, pain, Sliimey, supar, tucks    |
|           10 |     1773 | 2024-03-27 | Bad News Kangaroos               | W   | 0.937      | 0.333        | 0.071 (0.022)    | 0.238 (0.074)    | 0 (0.000) |    23.29 | gump, pain, Sliimey, supar, tucks    |
|            9 |     1774 | 2024-03-27 | Bad News Kangaroos               | L   | 0.936      | -            | -                | -                | -         |    -5.81 | gump, pain, Sliimey, supar, tucks    |
|            8 |     3380 | 2024-02-20 | TEAM RKON                        | W   | 0.696      | -            | -                | -                | -         |     5.36 | gump, Rickeh, Sliimey, supar, tucks  |
|            7 |     3432 | 2024-02-18 | FlyQuest                         | L   | 0.689      | -            | -                | -                | -         |    -0.46 | gump, Rickeh, Sliimey, supar, tucks  |
|            6 |     3657 | 2024-02-13 | KZG                              | L   | 0.656      | -            | -                | -                | -         |    -9.73 | deStiny, gump, Sliimey, supar, tucks |
|            5 |     3693 | 2024-02-13 | DEMESIS                          | W   | 0.649      | -            | -                | -                | -         |     3.07 | deStiny, gump, Sliimey, supar, tucks |
|            4 |     3698 | 2024-02-13 | Arcade Esports (Australian team) | W   | 0.649      | -            | -                | -                | -         |     3.12 | deStiny, gump, Sliimey, supar, tucks |
|            3 |     3740 | 2024-02-11 | Bad News Kangaroos               | L   | 0.642      | -            | -                | -                | -         |    -4.05 | dangeR, gump, Sliimey, supar, tucks  |
|            2 |     3761 | 2024-02-11 | KZG                              | W   | 0.636      | 0.143        | 0.020 (0.002)    | 0.249 (0.023)    | -         |    10.57 | dangeR, gump, Sliimey, supar, tucks  |
|            1 |     3871 | 2024-02-06 | Chinggis Warriors                | W   | 0.603      | -            | -                | -                | -         |     3.13 | dangeR, gump, Sliimey, supar, tucks  |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($170.13)
- Divide that value by the 5th highest value among all rosters ($158,437.64)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
