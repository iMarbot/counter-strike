### Roster Details<br />
Team Name: The Prodigies<br />
Roster: Chill, consss, KWERTZZ, Python, Wonderful_Y<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [356](../standings_global.md)<br />
Regional Rank: [212]( ../standings_europe.md)<br />
Final Rank Value:  599.0<br />
<br />
Final Rank Value (599.0) = Starting Rank Value (555.2) + Head To Head Adjustments (43.8)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.000[<sup>1</sup>](#table2)
- Bounty Collected: 0.281[<sup>2</sup>](#table1)
- Opponent Network: 0.024[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.076<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 555.2
- 400 + ( ( 0.076 - 0.000 ) / ( 0.786 - 0.000 ) ) * 1600 = 555.2


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
|           10 |     7794 | 2024-01-13 | MOUZ NXT             | W   | 0.283      | 0.303        | 0.157 (0.013)    | 0.950 (0.082)    | 0 (0.000) |     8.46 | Chill, consss, KWERTZZ, Python, Wonderful_Y |
|            9 |     7796 | 2024-01-13 | Natus Vincere Junior | W   | 0.282      | 0.333        | 0.010 (0.001)    | 0.290 (0.027)    | 0 (0.000) |     6.76 | Chill, consss, KWERTZZ, Python, Wonderful_Y |
|            8 |     7996 | 2024-01-10 | SINNERS Esports      | L   | 0.265      | -            | -                | -                | -         |    -0.74 | Chill, consss, KWERTZZ, Python, Wonderful_Y |
|            7 |     8007 | 2024-01-10 | Rebels Gaming        | W   | 0.265      | 0.143        | 0.062 (0.002)    | 0.418 (0.016)    | 0 (0.000) |     7.96 | Chill, consss, KWERTZZ, Python, Wonderful_Y |
|            6 |     8099 | 2024-01-09 | Zero Tenacity        | L   | 0.257      | -            | -                | -                | -         |    -0.43 | Chill, consss, KWERTZZ, Python, Wonderful_Y |
|            5 |     8125 | 2024-01-09 | SSX                  | W   | 0.257      | 0.143        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     3.92 | Chill, consss, KWERTZZ, Python, Wonderful_Y |
|            4 |     8140 | 2024-01-09 | Zero Tenacity        | L   | 0.256      | -            | -                | -                | -         |    -0.42 | Chill, consss, KWERTZZ, Python, Wonderful_Y |
|            3 |     8184 | 2024-01-08 | Monte Gen            | W   | 0.248      | 0.303        | 0.007 (0.000)    | 0.301 (0.023)    | 0 (0.000) |     5.97 | Chill, consss, KWERTZZ, Python, Wonderful_Y |
|            2 |     8223 | 2024-01-05 | Natus Vincere Junior | W   | 0.229      | 0.333        | 0.010 (0.001)    | 0.290 (0.022)    | 0 (0.000) |     5.64 | Chill, consss, KWERTZZ, Python, Wonderful_Y |
|            1 |     8237 | 2024-01-04 | Zero Tenacity        | W   | 0.222      | 0.303        | 0.147 (0.010)    | 1.000 (0.067)    | 0 (0.000) |     6.65 | Chill, consss, KWERTZZ, Python, Wonderful_Y |

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
