### Roster Details<br />
Team Name: The Prodigies<br />
Roster: Chill, consss, KWERTZZ, Python, Wonderful_Y<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [364](../standings_global.md)<br />
Regional Rank: [217]( ../standings_europe.md)<br />
Final Rank Value:  599.0<br />
<br />
Final Rank Value (599.0) = Starting Rank Value (555.0) + Head To Head Adjustments (43.9)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.000[<sup>1</sup>](#table2)
- Bounty Collected: 0.281[<sup>2</sup>](#table1)
- Opponent Network: 0.024[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.076<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 555.0
- 400 + ( ( 0.076 - 0.000 ) / ( 0.787 - 0.000 ) ) * 1600 = 555.0


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent             | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                      |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           10 |     8047 | 2024-01-13 | MOUZ NXT             | W   | 0.283      | 0.303        | 0.157 (0.013)    | 0.977 (0.084)    | 0 (0.000) |     8.48 | Chill, consss, KWERTZZ, Python, Wonderful_Y |
|            9 |     8049 | 2024-01-13 | Natus Vincere Junior | W   | 0.282      | 0.333        | 0.010 (0.001)    | 0.290 (0.027)    | 0 (0.000) |     6.76 | Chill, consss, KWERTZZ, Python, Wonderful_Y |
|            8 |     8250 | 2024-01-10 | SINNERS Esports      | L   | 0.265      | -            | -                | -                | -         |    -0.65 | Chill, consss, KWERTZZ, Python, Wonderful_Y |
|            7 |     8261 | 2024-01-10 | Rebels Gaming        | W   | 0.265      | 0.143        | 0.062 (0.002)    | 0.411 (0.016)    | 0 (0.000) |     7.96 | Chill, consss, KWERTZZ, Python, Wonderful_Y |
|            6 |     8353 | 2024-01-09 | Zero Tenacity        | L   | 0.257      | -            | -                | -                | -         |    -0.43 | Chill, consss, KWERTZZ, Python, Wonderful_Y |
|            5 |     8379 | 2024-01-09 | SSX                  | W   | 0.257      | 0.143        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     3.92 | Chill, consss, KWERTZZ, Python, Wonderful_Y |
|            4 |     8394 | 2024-01-09 | Zero Tenacity        | L   | 0.256      | -            | -                | -                | -         |    -0.42 | Chill, consss, KWERTZZ, Python, Wonderful_Y |
|            3 |     8439 | 2024-01-08 | Monte Gen            | W   | 0.248      | 0.303        | 0.007 (0.000)    | 0.301 (0.023)    | 0 (0.000) |     5.98 | Chill, consss, KWERTZZ, Python, Wonderful_Y |
|            2 |     8478 | 2024-01-05 | Natus Vincere Junior | W   | 0.229      | 0.333        | 0.010 (0.001)    | 0.290 (0.022)    | 0 (0.000) |     5.64 | Chill, consss, KWERTZZ, Python, Wonderful_Y |
|            1 |     8493 | 2024-01-04 | Zero Tenacity        | W   | 0.222      | 0.303        | 0.147 (0.010)    | 1.000 (0.067)    | 0 (0.000) |     6.66 | Chill, consss, KWERTZZ, Python, Wonderful_Y |

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
