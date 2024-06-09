### Roster Details<br />
Team Name: For Fun<br />
Roster: Cyrix, Lake, Momo, Pluto, Tender<br />
Region: [Americas]( ../standings_americas.md)<br />
<br />
Global Rank: [161](../standings_global.md)<br />
Regional Rank: [32]( ../standings_americas.md)<br />
Final Rank Value:  770.4<br />
<br />
Final Rank Value (770.4) = Starting Rank Value (772.2) + Head To Head Adjustments (-1.8)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.316[<sup>1</sup>](#table2)
- Bounty Collected: 0.211[<sup>2</sup>](#table1)
- Opponent Network: 0.005[<sup>2</sup>](#table1)
- LAN Wins: 0.200[<sup>2</sup>](#table1)

The average of these factors is 0.183<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 772.2
- 400 + ( ( 0.183 - 0.000 ) / ( 0.787 - 0.000 ) ) * 1600 = 772.2


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent              | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                             |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           13 |     2526 | 2024-04-21 | FLUFFY AIMERS         | L   | 0.946      | -            | -                | -                | -         |   -11.13 | Cyrix, Lake, Momo, Pluto, Tender   |
|           12 |     2528 | 2024-04-21 | Walmart Door Greeters | W   | 0.945      | 0.143        | 0.001 (0.000)    | 0.026 (0.004)    | 1 (0.945) |    10.92 | Cyrix, Lake, Momo, Pluto, Tender   |
|           11 |     2533 | 2024-04-21 | Strife Esports        | W   | 0.944      | 0.143        | 0.011 (0.001)    | 0.204 (0.028)    | 1 (0.944) |    12.57 | Cyrix, Lake, Momo, Pluto, Tender   |
|           10 |     8006 | 2024-01-14 | Elevate               | L   | 0.292      | -            | -                | -                | -         |    -3.59 | Momo, onter, Pluto, Tender, WOOHOO |
|            9 |     8014 | 2024-01-13 | vagrants              | W   | 0.286      | 0.143        | 0.000 (0.000)    | 0.021 (0.001)    | 0 (0.000) |     1.80 | Calix, Momo, onter, Pluto, Tender  |
|            8 |     8062 | 2024-01-12 | Rocket                | L   | 0.281      | -            | -                | -                | -         |    -6.76 | Calix, Momo, onter, Pluto, Tender  |
|            7 |     8069 | 2024-01-12 | BOSS                  | L   | 0.280      | -            | -                | -                | -         |    -3.38 | Calix, Momo, onter, Pluto, Tender  |
|            6 |     8131 | 2024-01-12 | Rocket                | L   | 0.275      | -            | -                | -                | -         |    -6.76 | Calix, Momo, onter, Pluto, Tender  |
|            5 |     8136 | 2024-01-11 | FLUFFY AIMERS         | W   | 0.274      | 0.143        | 0.001 (0.000)    | 0.026 (0.001)    | 0 (0.000) |     2.63 | Calix, Momo, onter, Pluto, Tender  |
|            4 |     8155 | 2024-01-11 | regain                | W   | 0.273      | 0.143        | 0.000 (0.000)    | 0.108 (0.004)    | 0 (0.000) |     2.63 | Calix, Momo, onter, Pluto, Tender  |
|            3 |     8163 | 2024-01-11 | Take Flyte            | W   | 0.273      | 0.143        | 0.006 (0.000)    | 0.354 (0.014)    | 0 (0.000) |     4.45 | Calix, Momo, onter, Pluto, Tender  |
|            2 |     8225 | 2024-01-10 | Team Lampa            | W   | 0.267      | 0.143        | 0.000 (0.000)    | 0.017 (0.001)    | 0 (0.000) |     1.46 | Calix, Momo, onter, Pluto, Tender  |
|            1 |     8397 | 2024-01-08 | MOLEGAN               | L   | 0.254      | -            | -                | -                | -         |    -6.62 | Calix, Momo, onter, Pluto, Tender  |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($2,057.19)
- Divide that value by the 5th highest value among all rosters ($300,806.11)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
