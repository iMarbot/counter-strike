### Roster Details<br />
Team Name: The Prodigies<br />
Roster: Chill, consss, KWERTZZ, Python, Wonderful_Y<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [270](../standings_global.md)<br />
Regional Rank: [169]( ../standings_europe.md)<br />
Final Rank Value:  643.6<br />
<br />
Final Rank Value (643.6) = Starting Rank Value (574.1) + Head To Head Adjustments (69.5)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.000[<sup>1</sup>](#table2)
- Bounty Collected: 0.308[<sup>2</sup>](#table1)
- Opponent Network: 0.043[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.088<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 574.1
- 400 + ( ( 0.088 - 0.000 ) / ( 0.806 - 0.000 ) ) * 1600 = 574.1


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
|           10 |     4894 | 2024-01-13 | MOUZ NXT             | W   | 0.444      | 0.303        | 0.215 (0.029)    | 1.000 (0.135)    | 0 (0.000) |    12.98 | Chill, consss, KWERTZZ, Python, Wonderful_Y |
|            9 |     4895 | 2024-01-13 | Natus Vincere Junior | W   | 0.443      | 0.333        | 0.025 (0.004)    | 0.492 (0.073)    | 0 (0.000) |    10.73 | Chill, consss, KWERTZZ, Python, Wonderful_Y |
|            8 |     5039 | 2024-01-10 | SINNERS Esports      | L   | 0.426      | -            | -                | -                | -         |    -1.48 | Chill, consss, KWERTZZ, Python, Wonderful_Y |
|            7 |     5047 | 2024-01-10 | Rebels Gaming        | W   | 0.426      | 0.143        | 0.121 (0.007)    | 0.376 (0.023)    | 0 (0.000) |    12.87 | Chill, consss, KWERTZZ, Python, Wonderful_Y |
|            6 |     5101 | 2024-01-09 | Zero Tenacity        | L   | 0.418      | -            | -                | -                | -         |    -1.63 | Chill, consss, KWERTZZ, Python, Wonderful_Y |
|            5 |     5119 | 2024-01-09 | SSX                  | W   | 0.418      | 0.143        | 0.001 (0.000)    | 0.017 (0.001)    | 0 (0.000) |     7.12 | Chill, consss, KWERTZZ, Python, Wonderful_Y |
|            4 |     5128 | 2024-01-09 | Zero Tenacity        | L   | 0.417      | -            | -                | -                | -         |    -1.60 | Chill, consss, KWERTZZ, Python, Wonderful_Y |
|            3 |     5157 | 2024-01-08 | Monte Gen            | W   | 0.409      | 0.303        | 0.019 (0.002)    | 0.155 (0.019)    | 0 (0.000) |     9.91 | Chill, consss, KWERTZZ, Python, Wonderful_Y |
|            2 |     5188 | 2024-01-05 | Natus Vincere Junior | W   | 0.390      | 0.333        | 0.025 (0.003)    | 0.492 (0.064)    | 0 (0.000) |     9.85 | Chill, consss, KWERTZZ, Python, Wonderful_Y |
|            1 |     5199 | 2024-01-04 | Zero Tenacity        | W   | 0.383      | 0.303        | 0.095 (0.011)    | 1.000 (0.116)    | 0 (0.000) |    10.77 | Chill, consss, KWERTZZ, Python, Wonderful_Y |

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
