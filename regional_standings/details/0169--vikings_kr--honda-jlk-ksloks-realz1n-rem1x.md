### Roster Details<br />
Team Name: Vikings KR<br />
Roster: honda, JLK, ksloks, realz1n, rem1x<br />
Region: [Americas]( ../standings_americas.md)<br />
<br />
Global Rank: [169](../standings_global.md)<br />
Regional Rank: [31]( ../standings_americas.md)<br />
Final Rank Value:  755.9<br />
<br />
Final Rank Value (755.9) = Starting Rank Value (701.5) + Head To Head Adjustments (54.3)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.327[<sup>1</sup>](#table2)
- Bounty Collected: 0.248[<sup>2</sup>](#table1)
- Opponent Network: 0.033[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.152<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 701.5
- 400 + ( ( 0.152 - 0.000 ) / ( 0.806 - 0.000 ) ) * 1600 = 701.5


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent               | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                             |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           11 |      413 | 2024-04-26 | Intense Game           | L   | 1.000      | -            | -                | -                | -         |   -15.74 | honda, JLK, ksloks, realz1n, rem1x |
|           10 |      500 | 2024-04-24 | Bounty Hunters Esports | W   | 1.000      | 0.143        | 0.000 (0.000)    | 0.276 (0.039)    | 0 (0.000) |    10.54 | honda, JLK, ksloks, realz1n, rem1x |
|            9 |      501 | 2024-04-24 | Seleção do BT          | W   | 1.000      | 0.143        | 0.000 (0.000)    | 0.035 (0.005)    | 0 (0.000) |     3.97 | honda, JLK, ksloks, realz1n, rem1x |
|            8 |      506 | 2024-04-24 | Dusty Roots            | W   | 1.000      | 0.143        | 0.005 (0.001)    | 0.352 (0.050)    | 0 (0.000) |    12.06 | honda, JLK, ksloks, realz1n, rem1x |
|            7 |     1164 | 2024-04-11 | Galorys                | W   | 1.000      | 0.143        | 0.048 (0.007)    | 0.598 (0.085)    | 0 (0.000) |    21.41 | honda, JLK, ksloks, realz1n, rem1x |
|            6 |     1276 | 2024-04-09 | Bounty Hunters Esports | W   | 1.000      | 0.143        | 0.000 (0.000)    | 0.276 (0.039)    | 0 (0.000) |    10.06 | honda, JLK, ksloks, realz1n, rem1x |
|            5 |     1475 | 2024-04-04 | Yawara E-Sports        | W   | 0.992      | 0.143        | 0.005 (0.001)    | 0.361 (0.051)    | 0 (0.000) |    16.34 | honda, JLK, ksloks, realz1n, rem1x |
|            4 |     1598 | 2024-04-01 | 2024                   | W   | 0.972      | 0.143        | 0.001 (0.000)    | 0.130 (0.018)    | 0 (0.000) |    12.04 | honda, JLK, ksloks, realz1n, rem1x |
|            3 |     1838 | 2024-03-25 | Intense Game           | L   | 0.926      | -            | -                | -                | -         |   -12.69 | honda, JLK, ksloks, realz1n, rem1x |
|            2 |     1961 | 2024-03-21 | Corinthians Esports    | L   | 0.899      | -            | -                | -                | -         |   -16.44 | honda, JLK, ksloks, realz1n, rem1x |
|            1 |     1971 | 2024-03-21 | Dusty Roots            | W   | 0.899      | 0.143        | 0.005 (0.001)    | 0.352 (0.045)    | 0 (0.000) |    12.78 | honda, JLK, ksloks, realz1n, rem1x |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($1,381.30)
- Divide that value by the 5th highest value among all rosters ($158,437.64)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
