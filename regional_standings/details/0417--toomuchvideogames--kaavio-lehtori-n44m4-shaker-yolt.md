### Roster Details<br />
Team Name: TOOMUCHVIDEOGAMES<br />
Roster: kaavio, lehtori, N44M4, shaker, yolt<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [417](../standings_global.md)<br />
Regional Rank: [252]( ../standings_europe.md)<br />
Final Rank Value:  529.6<br />
<br />
Final Rank Value (529.6) = Starting Rank Value (502.3) + Head To Head Adjustments (27.3)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.000[<sup>1</sup>](#table2)
- Bounty Collected: 0.193[<sup>2</sup>](#table1)
- Opponent Network: 0.008[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.050<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 502.3
- 400 + ( ( 0.050 - 0.000 ) / ( 0.786 - 0.000 ) ) * 1600 = 502.3


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
|           18 |     1840 | 2024-05-04 | ENCE Academy  | L   | 1.000      | -            | -                | -                | -         |    -6.15 | kaavio, lehtori, N44M4, shaker, yolt     |
|           17 |     2113 | 2024-04-28 | jefet         | L   | 0.990      | -            | -                | -                | -         |    -9.41 | kaavio, lehtori, N44M4, shaker, yolt     |
|           16 |     2181 | 2024-04-27 | RoundsGG      | W   | 0.983      | 0.143        | 0.000 (0.000)    | 0.202 (0.028)    | 0 (0.000) |    18.25 | kaavio, lehtori, N44M4, shaker, yolt     |
|           15 |     2501 | 2024-04-21 | ENCE Academy  | L   | 0.943      | -            | -                | -                | -         |    -4.48 | kaavio, lehtori, N44M4, shaker, yolt     |
|           14 |     2686 | 2024-04-19 | Foxed Gaming  | L   | 0.930      | -            | -                | -                | -         |   -18.32 | kaavio, shaker, STOVVE, weaNd, yolt      |
|           13 |     2980 | 2024-04-14 | RoundsGG      | W   | 0.896      | 0.143        | 0.000 (0.000)    | 0.202 (0.026)    | 0 (0.000) |    16.80 | kaavio, lehtori, N44M4, shaker, yolt     |
|           12 |     3027 | 2024-04-13 | MASONIC       | L   | 0.890      | -            | -                | -                | -         |    -3.72 | kaavio, lehtori, shaker, Villeboe, yolt  |
|           11 |     3037 | 2024-04-13 | Center Gaming | W   | 0.890      | 0.143        | 0.000 (0.000)    | 0.018 (0.002)    | 0 (0.000) |     8.76 | kaavio, lehtori, shaker, Villeboe, yolt  |
|           10 |     3386 | 2024-04-06 | VELLAMO       | W   | 0.843      | 0.143        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     8.76 | kaavio, lehtori, N44M4, shaker, yolt     |
|            9 |     5017 | 2024-03-04 | ex-Sprout     | L   | 0.625      | -            | -                | -                | -         |    -6.45 | kaavio, lehtori, N44M4, shaker, VORMISTO |
|            8 |     6501 | 2024-02-03 | Heimo Esports | W   | 0.424      | 0.143        | 0.011 (0.001)    | 0.217 (0.013)    | 0 (0.000) |    10.19 | N44M4, shaker, STOVVE, ykis, yolt        |
|            7 |     6512 | 2024-02-03 | Split         | W   | 0.424      | 0.143        | 0.000 (0.000)    | 0.012 (0.001)    | 0 (0.000) |     4.78 | N44M4, shaker, STOVVE, ykis, yolt        |
|            6 |     6530 | 2024-02-03 | RoundsGG      | W   | 0.424      | 0.143        | 0.000 (0.000)    | 0.202 (0.012)    | 0 (0.000) |     8.40 | N44M4, shaker, STOVVE, ykis, yolt        |
|            5 |     8111 | 2024-01-09 | UNiTY esports | L   | 0.257      | -            | -                | -                | -         |    -0.70 | kaavio, lehtori, shaker, VORMISTO, yolt  |
|            4 |     8929 | 2023-12-11 | HyperSpirit   | L   | 0.064      | -            | -                | -                | -         |    -0.39 | kaavio, lehtori, N44M4, shaker, yolt     |
|            3 |     8962 | 2023-12-10 | Kolon 3       | W   | 0.057      | 0.333        | 0.000 (0.000)    | 0.001 (0.000)    | 0 (0.000) |     0.65 | kaavio, lehtori, N44M4, shaker, yolt     |
|            2 |     9109 | 2023-12-08 | Rhyno Esports | L   | 0.043      | -            | -                | -                | -         |    -0.06 | kaavio, lehtori, N44M4, shaker, yolt     |
|            1 |     9224 | 2023-12-06 | Team Raised   | W   | 0.031      | 0.333        | 0.000 (0.000)    | 0.001 (0.000)    | 0 (0.000) |     0.35 | kaavio, lehtori, N44M4, shaker, yolt     |

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
