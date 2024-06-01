### Roster Details<br />
Team Name: TSM<br />
Roster: CYPHER, interz, JACKZ, MoDo, valde<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [304](../standings_global.md)<br />
Regional Rank: [186]( ../standings_europe.md)<br />
Final Rank Value:  640.8<br />
<br />
Final Rank Value (640.8) = Starting Rank Value (637.9) + Head To Head Adjustments (2.9)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.250[<sup>1</sup>](#table2)
- Bounty Collected: 0.214[<sup>2</sup>](#table1)
- Opponent Network: 0.003[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.117<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 637.9
- 400 + ( ( 0.117 - 0.000 ) / ( 0.786 - 0.000 ) ) * 1600 = 637.9


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
|           12 |     8596 | 2023-12-16 | RUSH B                 | L   | 0.098      | -            | -                | -                | -         |    -1.03 | CYPHER, interz, JACKZ, MoDo, valde |
|           11 |     8739 | 2023-12-15 | Permitta Esports       | W   | 0.091      | 0.143        | 0.029 (0.000)    | 1.000 (0.013)    | 0 (0.000) |     2.46 | CYPHER, interz, JACKZ, MoDo, valde |
|           10 |     8920 | 2023-12-11 | RUSH B                 | L   | 0.064      | -            | -                | -                | -         |    -0.68 | CYPHER, interz, JACKZ, MoDo, valde |
|            9 |     8996 | 2023-12-10 | ex-Preasy Esport       | L   | 0.055      | -            | -                | -                | -         |    -0.31 | CYPHER, interz, JACKZ, MoDo, valde |
|            8 |     9051 | 2023-12-09 | Sprout                 | W   | 0.048      | 0.371        | 0.000 (0.000)    | 0.148 (0.003)    | 0 (0.000) |     0.61 | CYPHER, interz, JACKZ, MoDo, valde |
|            7 |     9094 | 2023-12-08 | ALTERNATE aTTaX        | L   | 0.045      | -            | -                | -                | -         |    -0.18 | CYPHER, interz, JACKZ, MoDo, valde |
|            6 |     9154 | 2023-12-07 | lajtbitexe             | W   | 0.038      | 0.371        | 0.001 (0.000)    | 0.069 (0.001)    | 0 (0.000) |     0.55 | CYPHER, interz, JACKZ, MoDo, valde |
|            5 |     9188 | 2023-12-07 | IKLA                   | W   | 0.035      | 0.371        | 0.000 (0.000)    | 0.066 (0.001)    | 0 (0.000) |     0.42 | CYPHER, interz, JACKZ, MoDo, valde |
|            4 |     9210 | 2023-12-06 | Lausanne-Sport Esports | W   | 0.031      | 0.371        | 0.000 (0.000)    | 0.009 (0.000)    | 0 (0.000) |     0.43 | CYPHER, interz, JACKZ, MoDo, valde |
|            3 |     9280 | 2023-12-05 | Zero Tenacity          | W   | 0.025      | 0.371        | 0.147 (0.001)    | 1.000 (0.009)    | 0 (0.000) |     0.72 | CYPHER, interz, JACKZ, MoDo, valde |
|            2 |     9317 | 2023-12-05 | GODSENT                | L   | 0.022      | -            | -                | -                | -         |    -0.33 | CYPHER, interz, JACKZ, MoDo, valde |
|            1 |     9402 | 2023-12-03 | Zero Tenacity          | W   | 0.008      | 0.371        | 0.147 (0.000)    | 1.000 (0.003)    | 0 (0.000) |     0.24 | CYPHER, interz, JACKZ, MoDo, valde |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($300.83)
- Divide that value by the 5th highest value among all rosters ($300,806.11)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2023-12-13 |      0.077 | $3,000.00      | $230.83         |
| 2023-12-12 |      0.070 | $1,000.00      | $70.00          |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
