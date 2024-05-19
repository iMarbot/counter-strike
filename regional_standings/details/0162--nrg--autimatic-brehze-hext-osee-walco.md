### Roster Details<br />
Team Name: NRG<br />
Roster: autimatic, Brehze, HexT, oSee, Walco<br />
Region: [Americas]( ../standings_americas.md)<br />
<br />
Global Rank: [162](../standings_global.md)<br />
Regional Rank: [29]( ../standings_americas.md)<br />
Final Rank Value:  763.0<br />
<br />
Final Rank Value (763.0) = Starting Rank Value (619.3) + Head To Head Adjustments (143.7)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.000[<sup>1</sup>](#table2)
- Bounty Collected: 0.304[<sup>2</sup>](#table1)
- Opponent Network: 0.138[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.111<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 619.3
- 400 + ( ( 0.111 - 0.000 ) / ( 0.806 - 0.000 ) ) * 1600 = 619.3


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent         | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                 |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           21 |      455 | 2024-04-25 | Wildcard Gaming  | L   | 1.000      | -            | -                | -                | -         |   -11.18 | autimatic, Brehze, HexT, oSee, Walco   |
|           20 |      457 | 2024-04-25 | Wildcard Gaming  | W   | 1.000      | 0.477        | 0.025 (0.012)    | 0.483 (0.230)    | 0 (0.000) |    20.72 | autimatic, Brehze, HexT, oSee, Walco   |
|           19 |      916 | 2024-04-17 | G3 (Asian team)  | L   | 1.000      | -            | -                | -                | -         |   -15.46 | autimatic, Brehze, HexT, oSee, Walco   |
|           18 |      983 | 2024-04-16 | Zomblers         | W   | 1.000      | 0.143        | 0.007 (0.001)    | -                | 0 (0.000) |    11.44 | autimatic, Brehze, HexT, oSee, Walco   |
|           17 |     1028 | 2024-04-15 | Mythic           | W   | 1.000      | 0.477        | 0.003 (0.001)    | 0.380 (0.181)    | 0 (0.000) |    12.42 | autimatic, Brehze, HexT, oSee, Walco   |
|           16 |     1029 | 2024-04-15 | Mythic           | W   | 1.000      | 0.477        | 0.003 (0.001)    | 0.380 (0.181)    | 0 (0.000) |    13.53 | autimatic, Brehze, HexT, oSee, Walco   |
|           15 |     1192 | 2024-04-10 | BOSS             | W   | 1.000      | 0.477        | 0.051 (0.024)    | 0.293 (0.140)    | 0 (0.000) |    23.15 | autimatic, Brehze, HexT, oSee, Walco   |
|           14 |     1196 | 2024-04-10 | BOSS             | L   | 1.000      | -            | -                | -                | -         |    -7.86 | autimatic, Brehze, HexT, oSee, Walco   |
|           13 |     1265 | 2024-04-09 | Carpe Diem       | W   | 1.000      | 0.477        | 0.009 (0.004)    | 0.178 (0.085)    | 0 (0.000) |    12.61 | autimatic, Brehze, HexT, oSee, Walco   |
|           12 |     1269 | 2024-04-09 | Carpe Diem       | W   | 1.000      | 0.477        | 0.009 (0.004)    | 0.178 (0.085)    | 0 (0.000) |    13.74 | autimatic, Brehze, HexT, oSee, Walco   |
|           11 |     1710 | 2024-03-27 | Nouns Esports    | W   | 0.941      | 0.477        | -                | 0.475 (0.213)    | 0 (0.000) |    18.04 | autimatic, Brehze, HexT, oSee, Walco   |
|           10 |     1713 | 2024-03-27 | Nouns Esports    | L   | 0.941      | -            | -                | -                | -         |   -11.41 | autimatic, Brehze, HexT, oSee, Walco   |
|            9 |     1779 | 2024-03-26 | MIGHT            | W   | 0.934      | 0.477        | 0.003 (0.001)    | 0.213 (0.095)    | 0 (0.000) |    17.10 | autimatic, Brehze, HexT, oSee, Walco   |
|            8 |     1783 | 2024-03-26 | MIGHT            | W   | 0.934      | 0.477        | 0.003 (0.001)    | 0.213 (0.095)    | 0 (0.000) |    18.51 | autimatic, Brehze, HexT, oSee, Walco   |
|            7 |     2238 | 2024-03-14 | Limitless        | W   | 0.854      | 0.477        | 0.001 (0.000)    | 0.177 (0.072)    | -         |    14.35 | autimatic, Brehze, HexT, oSee, Walco   |
|            6 |     2240 | 2024-03-14 | Limitless        | W   | 0.854      | -            | -                | -                | -         |    15.46 | autimatic, Brehze, HexT, oSee, Walco   |
|            5 |     2349 | 2024-03-12 | Carpe Diem       | L   | 0.841      | -            | -                | -                | -         |    -9.82 | autimatic, Brehze, HexT, oSee, Walco   |
|            4 |     2352 | 2024-03-12 | Synergy Esports  | W   | 0.840      | -            | -                | -                | -         |     5.80 | autimatic, Brehze, HexT, oSee, Walco   |
|            3 |     6796 | 2023-11-16 | M80              | L   | 0.061      | -            | -                | -                | -         |    -0.04 | malbsMd, maNkz, reck, slaxz-, Swisher  |
|            2 |     6854 | 2023-11-15 | Party Astronauts | W   | 0.054      | -            | -                | -                | -         |     1.25 | autimatic, HexT, Jeorge, junior, Walco |
|            1 |     6860 | 2023-11-15 | BOSS             | W   | 0.053      | -            | -                | -                | -         |     1.37 | autimatic, HexT, Jeorge, junior, Walco |

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
