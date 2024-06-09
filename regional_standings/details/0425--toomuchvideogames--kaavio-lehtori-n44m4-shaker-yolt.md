### Roster Details<br />
Team Name: TOOMUCHVIDEOGAMES<br />
Roster: kaavio, lehtori, N44M4, shaker, yolt<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [425](../standings_global.md)<br />
Regional Rank: [257]( ../standings_europe.md)<br />
Final Rank Value:  532.5<br />
<br />
Final Rank Value (532.5) = Starting Rank Value (503.0) + Head To Head Adjustments (29.5)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.000[<sup>1</sup>](#table2)
- Bounty Collected: 0.193[<sup>2</sup>](#table1)
- Opponent Network: 0.010[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.051<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 503.0
- 400 + ( ( 0.051 - 0.000 ) / ( 0.787 - 0.000 ) ) * 1600 = 503.0


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent      | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                   |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           18 |     1863 | 2024-05-04 | ENCE Academy  | L   | 1.000      | -            | -                | -                | -         |    -6.11 | kaavio, lehtori, N44M4, shaker, yolt     |
|           17 |     2148 | 2024-04-28 | jefet         | L   | 0.990      | -            | -                | -                | -         |    -9.53 | kaavio, lehtori, N44M4, shaker, yolt     |
|           16 |     2216 | 2024-04-27 | RoundsGG      | W   | 0.983      | 0.143        | 0.000 (0.000)    | 0.251 (0.035)    | 0 (0.000) |    19.72 | kaavio, lehtori, N44M4, shaker, yolt     |
|           15 |     2554 | 2024-04-21 | ENCE Academy  | L   | 0.943      | -            | -                | -                | -         |    -4.46 | kaavio, lehtori, N44M4, shaker, yolt     |
|           14 |     2742 | 2024-04-19 | Foxed Gaming  | L   | 0.930      | -            | -                | -                | -         |   -18.39 | kaavio, shaker, STOVVE, weaNd, yolt      |
|           13 |     3045 | 2024-04-14 | RoundsGG      | W   | 0.896      | 0.143        | 0.000 (0.000)    | 0.251 (0.032)    | 0 (0.000) |    17.52 | kaavio, lehtori, N44M4, shaker, yolt     |
|           12 |     3093 | 2024-04-13 | MASONIC       | L   | 0.890      | -            | -                | -                | -         |    -3.74 | kaavio, lehtori, shaker, Villeboe, yolt  |
|           11 |     3103 | 2024-04-13 | Center Gaming | W   | 0.890      | 0.143        | 0.000 (0.000)    | 0.018 (0.002)    | 0 (0.000) |     8.73 | kaavio, lehtori, shaker, Villeboe, yolt  |
|           10 |     3469 | 2024-04-06 | VELLAMO       | W   | 0.843      | 0.143        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     8.73 | kaavio, lehtori, N44M4, shaker, yolt     |
|            9 |     5163 | 2024-03-04 | ex-Sprout     | L   | 0.625      | -            | -                | -                | -         |    -6.48 | kaavio, lehtori, N44M4, shaker, VORMISTO |
|            8 |     6704 | 2024-02-03 | Heimo Esports | W   | 0.424      | 0.143        | 0.011 (0.001)    | 0.217 (0.013)    | 0 (0.000) |    10.18 | N44M4, shaker, STOVVE, ykis, yolt        |
|            7 |     6715 | 2024-02-03 | Split         | W   | 0.424      | 0.143        | 0.000 (0.000)    | 0.012 (0.001)    | 0 (0.000) |     4.77 | N44M4, shaker, STOVVE, ykis, yolt        |
|            6 |     6733 | 2024-02-03 | RoundsGG      | W   | 0.424      | 0.143        | 0.000 (0.000)    | 0.251 (0.015)    | 0 (0.000) |     8.76 | N44M4, shaker, STOVVE, ykis, yolt        |
|            5 |     8365 | 2024-01-09 | UNiTY esports | L   | 0.257      | -            | -                | -                | -         |    -0.70 | kaavio, lehtori, shaker, VORMISTO, yolt  |
|            4 |     9195 | 2023-12-11 | HyperSpirit   | L   | 0.064      | -            | -                | -                | -         |    -0.40 | kaavio, lehtori, N44M4, shaker, yolt     |
|            3 |     9228 | 2023-12-10 | Kolon 3       | W   | 0.057      | 0.333        | 0.000 (0.000)    | 0.001 (0.000)    | 0 (0.000) |     0.65 | kaavio, lehtori, N44M4, shaker, yolt     |
|            2 |     9378 | 2023-12-08 | Rhyno Esports | L   | 0.043      | -            | -                | -                | -         |    -0.06 | kaavio, lehtori, N44M4, shaker, yolt     |
|            1 |     9505 | 2023-12-06 | Team Raised   | W   | 0.031      | 0.333        | 0.000 (0.000)    | 0.001 (0.000)    | 0 (0.000) |     0.35 | kaavio, lehtori, N44M4, shaker, yolt     |

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
