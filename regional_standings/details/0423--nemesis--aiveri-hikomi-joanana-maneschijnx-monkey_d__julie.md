### Roster Details<br />
Team Name: Nemesis<br />
Roster: aiveri, Hikomi, Joanana, ManeschijnX, Monkey D. Julie<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [423](../standings_global.md)<br />
Regional Rank: [257]( ../standings_europe.md)<br />
Final Rank Value:  515.9<br />
<br />
Final Rank Value (515.9) = Starting Rank Value (507.3) + Head To Head Adjustments (8.7)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.000[<sup>1</sup>](#table2)
- Bounty Collected: 0.204[<sup>2</sup>](#table1)
- Opponent Network: 0.007[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.053<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 507.3
- 400 + ( ( 0.053 - 0.000 ) / ( 0.786 - 0.000 ) ) * 1600 = 507.3


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent        | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                                |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           10 |      268 | 2024-05-25 | ex-FORZE Ladies | L   | 1.000      | -            | -                | -                | -         |    -8.94 | aiveri, Hikomi, Joanana, ManeschijnX, Monkey D. Julie |
|            9 |      883 | 2024-05-18 | BIG EQUIPA      | L   | 1.000      | -            | -                | -                | -         |    -6.44 | aiveri, f6tal, Hikomi, Monkey D. Julie, victoria      |
|            8 |      919 | 2024-05-18 | ENCE Athena     | W   | 1.000      | 0.281        | 0.004 (0.001)    | 0.215 (0.061)    | 0 (0.000) |    22.06 | aiveri, f6tal, Hikomi, Monkey D. Julie, victoria      |
|            7 |     2197 | 2024-04-27 | ENCE Athena     | L   | 0.982      | -            | -                | -                | -         |    -8.32 | aiveri, Emmy, Hikomi, Joanana, Monkey D. Julie        |
|            6 |     2210 | 2024-04-27 | raregodz        | W   | 0.982      | 0.143        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |    10.55 | aiveri, Emmy, Hikomi, Joanana, Monkey D. Julie        |
|            5 |     3024 | 2024-04-13 | ex-FORZE Ladies | L   | 0.890      | -            | -                | -                | -         |    -7.83 | aiveri, Emmy, Hikomi, Lowlita, Monkey D. Julie        |
|            4 |     3029 | 2024-04-13 | wwaves          | W   | 0.890      | 0.250        | 0.000 (0.000)    | 0.051 (0.011)    | 0 (0.000) |    13.19 | aiveri, Emmy, Hikomi, Lowlita, Monkey D. Julie        |
|            3 |     3343 | 2024-04-07 | ex-FORZE Ladies | L   | 0.849      | -            | -                | -                | -         |    -8.15 | aiveri, Emmy, Hikomi, Lowlita, Monkey D. Julie        |
|            2 |     3388 | 2024-04-06 | 5bites          | W   | 0.843      | 0.250        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     9.37 | aiveri, Emmy, Hikomi, Lowlita, Monkey D. Julie        |
|            1 |     3419 | 2024-04-06 | NIP Impact      | L   | 0.841      | -            | -                | -                | -         |    -6.85 | aiveri, Emmy, Hikomi, Lowlita, Monkey D. Julie        |

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
