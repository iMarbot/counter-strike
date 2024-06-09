### Roster Details<br />
Team Name: XPERION NXT<br />
Roster: jansen, pxsl, Rhyzar, sheezy, tlx<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [244](../standings_global.md)<br />
Regional Rank: [161]( ../standings_europe.md)<br />
Final Rank Value:  692.1<br />
<br />
Final Rank Value (692.1) = Starting Rank Value (607.2) + Head To Head Adjustments (84.9)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.203[<sup>1</sup>](#table2)
- Bounty Collected: 0.195[<sup>2</sup>](#table1)
- Opponent Network: 0.010[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.102<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 607.2
- 400 + ( ( 0.102 - 0.000 ) / ( 0.787 - 0.000 ) ) * 1600 = 607.2


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent            | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                            |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           10 |      760 | 2024-05-19 | ALTERNATE aTTaX Evo | W   | 1.000      | 0.143        | 0.002 (0.000)    | 0.239 (0.034)    | 0 (0.000) |    15.01 | jansen, pxsl, Rhyzar, sheezy, tlx |
|            9 |      978 | 2024-05-17 | Entropy Future      | W   | 1.000      | 0.143        | 0.000 (0.000)    | 0.028 (0.004)    | 0 (0.000) |    10.19 | jansen, pxsl, Rhyzar, sheezy, tlx |
|            8 |     1515 | 2024-05-10 | AKA HERO            | W   | 1.000      | 0.143        | 0.001 (0.000)    | 0.100 (0.014)    | 0 (0.000) |    14.06 | jansen, pxsl, Rhyzar, sheezy, tlx |
|            7 |     2497 | 2024-04-22 | eSports Cologne     | W   | 0.951      | 0.143        | 0.000 (0.000)    | 0.101 (0.014)    | 0 (0.000) |     9.68 | jansen, pxsl, Rhyzar, sheezy, tlx |
|            6 |     2756 | 2024-04-19 | Team Solid          | W   | 0.930      | 0.143        | 0.002 (0.000)    | 0.091 (0.012)    | 0 (0.000) |    13.02 | jansen, pxsl, Rhyzar, sheezy, tlx |
|            5 |     3040 | 2024-04-14 | OTHERSCANTBEAT      | W   | 0.897      | 0.143        | 0.000 (0.000)    | 0.106 (0.014)    | 0 (0.000) |     9.79 | jansen, pxsl, Rhyzar, sheezy, tlx |
|            4 |     3235 | 2024-04-10 | Reveal              | W   | 0.871      | 0.143        | 0.000 (0.000)    | 0.055 (0.007)    | 0 (0.000) |    12.87 | jansen, pxsl, Rhyzar, sheezy, tlx |
|            3 |     8876 | 2023-12-16 | cs2Ctonjeu          | L   | 0.097      | -            | -                | -                | -         |    -1.55 | Jansen, pxsl, Rhyzar, sheezy, tlx |
|            2 |     9043 | 2023-12-14 | Carte Blanche       | W   | 0.085      | 0.284        | 0.000 (0.000)    | 0.002 (0.000)    | 0 (0.000) |     1.22 | Jansen, pxsl, Rhyzar, sheezy, tlx |
|            1 |     9092 | 2023-12-13 | Foxton              | W   | 0.078      | 0.284        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     0.58 | Jansen, pxsl, Rhyzar, sheezy, tlx |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($36.60)
- Divide that value by the 5th highest value among all rosters ($300,806.11)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
