### Roster Details<br />
Team Name: Myth e-Sports<br />
Roster: crownzera, Farw, MyRoN, nz1, zhoki<br />
Region: [Americas]( ../standings_americas.md)<br />
<br />
Global Rank: [356](../standings_global.md)<br />
Regional Rank: [88]( ../standings_americas.md)<br />
Final Rank Value:  604.3<br />
<br />
Final Rank Value (604.3) = Starting Rank Value (617.8) + Head To Head Adjustments (-13.5)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.212[<sup>1</sup>](#table2)
- Bounty Collected: 0.214[<sup>2</sup>](#table1)
- Opponent Network: 0.002[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.107<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 617.8
- 400 + ( ( 0.107 - 0.000 ) / ( 0.787 - 0.000 ) ) * 1600 = 617.8


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent            | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           12 |     5650 | 2024-02-24 | phantom troupe      | L   | 0.565      | -            | -                | -                | -         |    -8.68 | crownzera, Farw, MyRoN, nz1, zhoki    |
|           11 |     5662 | 2024-02-24 | Hawks               | L   | 0.565      | -            | -                | -                | -         |    -7.94 | crownzera, Farw, MyRoN, nz1, zhoki    |
|           10 |     5672 | 2024-02-24 | Fluxo Demons        | W   | 0.564      | 0.143        | 0.026 (0.002)    | 0.264 (0.021)    | 0 (0.000) |    14.13 | crownzera, Farw, MyRoN, nz1, zhoki    |
|            9 |     5679 | 2024-02-24 | Hazap Esports       | W   | 0.564      | 0.143        | 0.000 (0.000)    | 0.037 (0.003)    | 0 (0.000) |     7.88 | crownzera, Farw, MyRoN, nz1, zhoki    |
|            8 |     7143 | 2024-01-27 | Romanticos          | L   | 0.378      | -            | -                | -                | -         |    -5.25 | crownzera, Farw, hellzaoo, MyRoN, nz1 |
|            7 |     7156 | 2024-01-27 | 2Game Esports B     | W   | 0.378      | 0.143        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     2.85 | crownzera, Farw, hellzaoo, MyRoN, nz1 |
|            6 |     7164 | 2024-01-27 | anXi5tYs            | L   | 0.378      | -            | -                | -                | -         |    -8.07 | crownzera, Farw, hellzaoo, MyRoN, nz1 |
|            5 |     8236 | 2024-01-10 | 2Game Esports       | L   | 0.266      | -            | -                | -                | -         |    -3.25 | crownzera, Farw, hellzaoo, nz1, tpk   |
|            4 |     9002 | 2023-12-15 | TIMACETA            | L   | 0.091      | -            | -                | -                | -         |    -1.38 | Farw, hellzaoo, MyRoN, nz1, tpk       |
|            3 |     9035 | 2023-12-14 | Intense Game        | L   | 0.085      | -            | -                | -                | -         |    -1.37 | Farw, hellzaoo, MyRoN, nz1, tpk       |
|            2 |     9089 | 2023-12-13 | paiN Gaming Academy | L   | 0.078      | -            | -                | -                | -         |    -1.26 | Farw, hellzaoo, MyRoN, nz1, tpk       |
|            1 |     9127 | 2023-12-12 | Sharks Youngsters   | L   | 0.072      | -            | -                | -                | -         |    -1.20 | Farw, hellzaoo, MyRoN, nz1, tpk       |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($58.76)
- Divide that value by the 5th highest value among all rosters ($300,806.11)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
