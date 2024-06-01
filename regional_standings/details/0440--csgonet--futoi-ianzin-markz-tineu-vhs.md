### Roster Details<br />
Team Name: CSGONET<br />
Roster: futoi, ianzin, Markz, Tineu, vhs<br />
Region: [Americas]( ../standings_americas.md)<br />
<br />
Global Rank: [440](../standings_global.md)<br />
Regional Rank: [110]( ../standings_americas.md)<br />
Final Rank Value:  469.3<br />
<br />
Final Rank Value (469.3) = Starting Rank Value (479.0) + Head To Head Adjustments (-9.8)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.000[<sup>1</sup>](#table2)
- Bounty Collected: 0.154[<sup>2</sup>](#table1)
- Opponent Network: 0.001[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.039<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 479.0
- 400 + ( ( 0.039 - 0.000 ) / ( 0.786 - 0.000 ) ) * 1600 = 479.0


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent                | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                           |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           11 |      825 | 2024-05-18 | SoJoga                  | L   | 1.000      | -            | -                | -                | -         |   -10.17 | futoi, ianzin, Markz, Tineu, vhs |
|           10 |      839 | 2024-05-18 | MX Team                 | L   | 1.000      | -            | -                | -                | -         |   -10.89 | futoi, ianzin, Markz, Tineu, vhs |
|            9 |      849 | 2024-05-18 | COBRAMOS POCO           | W   | 1.000      | 0.143        | 0.000 (0.000)    | 0.028 (0.004)    | 0 (0.000) |    11.85 | futoi, ianzin, Markz, Tineu, vhs |
|            8 |     2158 | 2024-04-27 | Floripa Stars           | L   | 0.984      | -            | -                | -                | -         |    -8.97 | futoi, ianzin, Markz, ritz, vhs  |
|            7 |     2169 | 2024-04-27 | eSports Recife          | L   | 0.984      | -            | -                | -                | -         |    -8.48 | futoi, ianzin, Markz, ritz, vhs  |
|            6 |     3970 | 2024-03-23 | eSports Recife          | L   | 0.752      | -            | -                | -                | -         |    -6.75 | davi, futoi, ianzin, Markz, vhs  |
|            5 |     3973 | 2024-03-23 | parece um barco andando | W   | 0.751      | 0.143        | 0.000 (0.000)    | 0.031 (0.003)    | 0 (0.000) |    14.32 | davi, futoi, ianzin, Markz, vhs  |
|            4 |     3994 | 2024-03-23 | INTERDIT                | W   | 0.751      | 0.143        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |    12.00 | davi, futoi, ianzin, Markz, vhs  |
|            3 |     5499 | 2024-02-24 | Hazap Esports           | L   | 0.565      | -            | -                | -                | -         |    -6.80 | davi, futoi, ianzin, Markz, vhs  |
|            2 |     5513 | 2024-02-24 | Salão do Corte          | L   | 0.564      | -            | -                | -                | -         |    -5.30 | davi, futoi, ianzin, Markz, vhs  |
|            1 |     5523 | 2024-02-24 | spotlight               | W   | 0.564      | 0.143        | 0.000 (0.000)    | 0.016 (0.001)    | 0 (0.000) |     9.42 | davi, futoi, ianzin, Markz, vhs  |

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
