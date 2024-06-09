### Roster Details<br />
Team Name: CSGONET<br />
Roster: futoi, ianzin, Markz, Tineu, vhs<br />
Region: [Americas]( ../standings_americas.md)<br />
<br />
Global Rank: [452](../standings_global.md)<br />
Regional Rank: [112]( ../standings_americas.md)<br />
Final Rank Value:  469.0<br />
<br />
Final Rank Value (469.0) = Starting Rank Value (478.9) + Head To Head Adjustments (-9.9)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.000[<sup>1</sup>](#table2)
- Bounty Collected: 0.154[<sup>2</sup>](#table1)
- Opponent Network: 0.001[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.039<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 478.9
- 400 + ( ( 0.039 - 0.000 ) / ( 0.787 - 0.000 ) ) * 1600 = 478.9


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
|           11 |      837 | 2024-05-18 | SoJoga                  | L   | 1.000      | -            | -                | -                | -         |   -10.20 | futoi, ianzin, Markz, Tineu, vhs |
|           10 |      851 | 2024-05-18 | MX Team                 | L   | 1.000      | -            | -                | -                | -         |   -10.89 | futoi, ianzin, Markz, Tineu, vhs |
|            9 |      861 | 2024-05-18 | COBRAMOS POCO           | W   | 1.000      | 0.143        | 0.000 (0.000)    | 0.028 (0.004)    | 0 (0.000) |    11.86 | futoi, ianzin, Markz, Tineu, vhs |
|            8 |     2193 | 2024-04-27 | Floripa Stars           | L   | 0.984      | -            | -                | -                | -         |    -8.99 | futoi, ianzin, Markz, ritz, vhs  |
|            7 |     2204 | 2024-04-27 | eSports Recife          | L   | 0.984      | -            | -                | -                | -         |    -8.53 | futoi, ianzin, Markz, ritz, vhs  |
|            6 |     4068 | 2024-03-23 | eSports Recife          | L   | 0.752      | -            | -                | -                | -         |    -6.77 | davi, futoi, ianzin, Markz, vhs  |
|            5 |     4071 | 2024-03-23 | parece um barco andando | W   | 0.751      | 0.143        | 0.000 (0.000)    | 0.031 (0.003)    | 0 (0.000) |    14.32 | davi, futoi, ianzin, Markz, vhs  |
|            4 |     4091 | 2024-03-23 | INTERDIT                | W   | 0.751      | 0.143        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |    12.00 | davi, futoi, ianzin, Markz, vhs  |
|            3 |     5659 | 2024-02-24 | Hazap Esports           | L   | 0.565      | -            | -                | -                | -         |    -6.81 | davi, futoi, ianzin, Markz, vhs  |
|            2 |     5673 | 2024-02-24 | Salão do Corte          | L   | 0.564      | -            | -                | -                | -         |    -5.30 | davi, futoi, ianzin, Markz, vhs  |
|            1 |     5683 | 2024-02-24 | spotlight               | W   | 0.564      | 0.143        | 0.000 (0.000)    | 0.016 (0.001)    | 0 (0.000) |     9.42 | davi, futoi, ianzin, Markz, vhs  |

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
