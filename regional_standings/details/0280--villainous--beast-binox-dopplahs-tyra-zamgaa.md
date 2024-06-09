### Roster Details<br />
Team Name: Villainous<br />
Roster: Beast, BiNoX, dopplahs, TyRa, Zamgaa<br />
Region: [Americas]( ../standings_americas.md)<br />
<br />
Global Rank: [280](../standings_global.md)<br />
Regional Rank: [59]( ../standings_americas.md)<br />
Final Rank Value:  661.1<br />
<br />
Final Rank Value (661.1) = Starting Rank Value (660.6) + Head To Head Adjustments (0.5)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.223[<sup>1</sup>](#table2)
- Bounty Collected: 0.212[<sup>2</sup>](#table1)
- Opponent Network: 0.003[<sup>2</sup>](#table1)
- LAN Wins: 0.075[<sup>2</sup>](#table1)

The average of these factors is 0.128<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 660.6
- 400 + ( ( 0.128 - 0.000 ) / ( 0.787 - 0.000 ) ) * 1600 = 660.6


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent          | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                  |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           15 |        1 | 2024-05-29 | Tribe             | W   | 1.000      | 0.372        | 0.005 (0.002)    | 0.055 (0.020)    | 0 (0.000) |    20.46 | Beast, BiNoX, dopplahs, TyRa, Zamgaa    |
|           14 |     4341 | 2024-03-17 | Akimbo Esports    | L   | 0.711      | -            | -                | -                | -         |    -7.54 | Beast, Cyrix, dopplahs, TyRa, Zamgaa    |
|           13 |     4387 | 2024-03-17 | Artemis Esports   | W   | 0.710      | 0.333        | 0.000 (0.000)    | 0.000 (0.000)    | 1 (0.710) |     4.46 | Beast, Cyrix, dopplahs, TyRa, Zamgaa    |
|           12 |     4569 | 2024-03-13 | Snakes Den Gaming | L   | 0.686      | -            | -                | -                | -         |   -11.43 | Beast, BiNoX, dopplahs, TyRa, Zamgaa    |
|           11 |     4699 | 2024-03-11 | huge sweaty       | W   | 0.673      | 0.371        | 0.000 (0.000)    | 0.019 (0.005)    | 0 (0.000) |     5.23 | Beast, BiNoX, dopplahs, TyRa, Zamgaa    |
|           10 |     4763 | 2024-03-10 | StandOnBusiness   | W   | 0.666      | 0.371        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     4.00 | Beast, BiNoX, dopplahs, TyRa, Zamgaa    |
|            9 |     4901 | 2024-03-07 | Revenge Nation    | L   | 0.647      | -            | -                | -                | -         |    -8.70 | Beast, BiNoX, dopplahs, TyRa, Zamgaa    |
|            8 |     8159 | 2024-01-11 | Rocket            | L   | 0.273      | -            | -                | -                | -         |    -5.74 | Beast, BiNoX, dopplahs, TyRa, Zamgaa    |
|            7 |     8212 | 2024-01-10 | 26 Rising         | W   | 0.267      | 0.143        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     1.60 | Beast, BiNoX, dopplahs, TyRa, Zamgaa    |
|            6 |     8805 | 2023-12-16 | Elevate           | L   | 0.099      | -            | -                | -                | -         |    -0.82 | Beast, BiNoX, dopplahs, jsfeltner, TyRa |
|            5 |     9070 | 2023-12-13 | LAG Gaming        | L   | 0.080      | -            | -                | -                | -         |    -0.41 | Beast, BiNoX, dopplahs, jsfeltner, TyRa |
|            4 |     9267 | 2023-12-09 | MIGHT             | L   | 0.053      | -            | -                | -                | -         |    -0.78 | Beast, BiNoX, dopplahs, jsfeltner, TyRa |
|            3 |     9404 | 2023-12-07 | One More Esports  | L   | 0.040      | -            | -                | -                | -         |    -0.47 | Beast, BiNoX, dopplahs, jsfeltner, TyRa |
|            2 |     9471 | 2023-12-06 | Team Steve        | W   | 0.033      | 0.371        | 0.000 (0.000)    | 0.001 (0.000)    | 0 (0.000) |     0.20 | Beast, BiNoX, dopplahs, jsfeltner, TyRa |
|            1 |     9533 | 2023-12-05 | Final Form        | W   | 0.027      | 0.371        | 0.008 (0.000)    | 0.074 (0.001)    | 0 (0.000) |     0.43 | Beast, BiNoX, dopplahs, jsfeltner, TyRa |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($99.83)
- Divide that value by the 5th highest value among all rosters ($300,806.11)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
