### Roster Details<br />
Team Name: IMMAPROBLEM<br />
Roster: Damkilde, J3nsyy, NoProblemGuy, notaN, vester<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [394](../standings_global.md)<br />
Regional Rank: [236]( ../standings_europe.md)<br />
Final Rank Value:  569.7<br />
<br />
Final Rank Value (569.7) = Starting Rank Value (526.7) + Head To Head Adjustments (42.9)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.000[<sup>1</sup>](#table2)
- Bounty Collected: 0.218[<sup>2</sup>](#table1)
- Opponent Network: 0.031[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.062<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 526.7
- 400 + ( ( 0.062 - 0.000 ) / ( 0.787 - 0.000 ) ) * 1600 = 526.7


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent            | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                        |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           29 |      167 | 2024-05-27 | Sashi Esport        | L   | 1.000      | -            | -                | -                | -         |    -1.02 | Damkilde, J3nsyy, NoProblemGuy, notaN, vester |
|           28 |      185 | 2024-05-27 | XI Esport           | L   | 1.000      | -            | -                | -                | -         |   -10.78 | Damkilde, J3nsyy, NoProblemGuy, notaN, vester |
|           27 |      666 | 2024-05-20 | Copenhagen Wolves   | L   | 1.000      | -            | -                | -                | -         |   -12.40 | Damkilde, J3nsyy, NoProblemGuy, notaN, vester |
|           26 |      695 | 2024-05-20 | WOPA Esport         | L   | 1.000      | -            | -                | -                | -         |    -8.12 | Damkilde, J3nsyy, NoProblemGuy, notaN, vester |
|           25 |      699 | 2024-05-20 | Sashi Academy       | W   | 1.000      | 0.143        | 0.001 (0.000)    | 0.090 (0.013)    | 0 (0.000) |    15.04 | Damkilde, J3nsyy, NoProblemGuy, notaN, vester |
|           24 |     1745 | 2024-05-06 | Copenhagen Wolves   | W   | 1.000      | 0.143        | 0.000 (0.000)    | 0.387 (0.055)    | 0 (0.000) |    20.01 | Damkilde, J3nsyy, NoProblemGuy, notaN, vester |
|           23 |     1751 | 2024-05-06 | WOPA Esport         | W   | 1.000      | 0.143        | 0.003 (0.000)    | 0.594 (0.085)    | 0 (0.000) |    23.93 | Damkilde, J3nsyy, NoProblemGuy, notaN, vester |
|           22 |     2092 | 2024-04-29 | XI Esport           | W   | 0.997      | 0.143        | 0.001 (0.000)    | 0.277 (0.039)    | 0 (0.000) |    21.39 | Damkilde, J3nsyy, NoProblemGuy, notaN, vester |
|           21 |     2488 | 2024-04-22 | Sashi Academy       | L   | 0.951      | -            | -                | -                | -         |   -11.35 | Damkilde, J3nsyy, NoProblemGuy, notaN, vester |
|           20 |     2492 | 2024-04-22 | Preasy Esport       | L   | 0.951      | -            | -                | -                | -         |    -7.29 | Damkilde, J3nsyy, NoProblemGuy, notaN, vester |
|           19 |     2502 | 2024-04-22 | Astralis Talent     | L   | 0.950      | -            | -                | -                | -         |    -4.61 | Damkilde, J3nsyy, NoProblemGuy, notaN, vester |
|           18 |     3000 | 2024-04-15 | Sashi Esport        | L   | 0.904      | -            | -                | -                | -         |    -1.38 | Damkilde, J3nsyy, NoProblemGuy, notaN, vester |
|           17 |     4302 | 2024-03-18 | Kronjyllands Esport | W   | 0.718      | 0.143        | 0.000 (0.000)    | 0.028 (0.003)    | 0 (0.000) |     9.54 | daxy, J3nsyy, NoProblemGuy, notaN, vester     |
|           16 |     4729 | 2024-03-11 | Team Atlantic       | L   | 0.671      | -            | -                | -                | -         |   -10.72 | Damkilde, daxy, NoProblemGuy, notaN, vester   |
|           15 |     4980 | 2024-03-06 | Copenhagen Wolves   | L   | 0.638      | -            | -                | -                | -         |    -7.23 | Damkilde, daxy, NoProblemGuy, notaN, vester   |
|           14 |     4990 | 2024-03-06 | Preasy Esport       | L   | 0.638      | -            | -                | -                | -         |    -3.76 | Damkilde, daxy, NoProblemGuy, notaN, vester   |
|           13 |     5009 | 2024-03-06 | Astralis Talent     | W   | 0.637      | 0.143        | 0.012 (0.001)    | 0.452 (0.041)    | 0 (0.000) |    18.02 | Damkilde, daxy, NoProblemGuy, notaN, vester   |
|           12 |     5095 | 2024-03-05 | XI Esport           | W   | 0.631      | 0.143        | 0.001 (0.000)    | 0.277 (0.025)    | 0 (0.000) |    13.74 | Damkilde, daxy, NoProblemGuy, notaN, vester   |
|           11 |     5106 | 2024-03-05 | WOPA Esport         | L   | 0.631      | -            | -                | -                | -         |    -3.87 | Damkilde, daxy, NoProblemGuy, notaN, vester   |
|           10 |     5145 | 2024-03-04 | Pera Esports        | L   | 0.625      | -            | -                | -                | -         |    -2.27 | Damkilde, daxy, NoProblemGuy, notaN, vester   |
|            9 |     5279 | 2024-03-02 | Lilmix              | L   | 0.611      | -            | -                | -                | -         |    -3.40 | Brillo, dex, poiii, quix, zyyx                |
|            8 |     5560 | 2024-02-26 | AURA                | L   | 0.578      | -            | -                | -                | -         |    -5.95 | Damkilde, daxy, J3nsyy, notaN, vester         |
|            7 |     6571 | 2024-02-06 | XI Esport           | L   | 0.444      | -            | -                | -                | -         |    -4.41 | Damkilde, daxy, NoProblemGuy, notaN, vester   |
|            6 |     6574 | 2024-02-06 | Team Atlantic       | W   | 0.444      | 0.143        | 0.000 (0.000)    | 0.074 (0.005)    | 0 (0.000) |     6.72 | Damkilde, daxy, NoProblemGuy, notaN, vester   |
|            5 |     6597 | 2024-02-05 | Copenhagen Wolves   | W   | 0.438      | 0.143        | 0.000 (0.000)    | 0.387 (0.024)    | 0 (0.000) |     9.37 | Damkilde, daxy, NoProblemGuy, notaN, vester   |
|            4 |     6607 | 2024-02-05 | Preasy Esport       | L   | 0.438      | -            | -                | -                | -         |    -2.09 | Damkilde, daxy, NoProblemGuy, notaN, vester   |
|            3 |     7448 | 2024-01-22 | Astralis Talent     | W   | 0.345      | 0.143        | 0.012 (0.001)    | 0.452 (0.022)    | 0 (0.000) |     9.83 | Damkilde, daxy, NoProblemGuy, notaN, vester   |
|            2 |     7459 | 2024-01-22 | Sashi Esport        | L   | 0.344      | -            | -                | -                | -         |    -2.09 | Damkilde, daxy, NoProblemGuy, notaN, vester   |
|            1 |     7473 | 2024-01-22 | WOPA Esport         | L   | 0.344      | -            | -                | -                | -         |    -1.90 | Damkilde, daxy, NoProblemGuy, notaN, vester   |

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
