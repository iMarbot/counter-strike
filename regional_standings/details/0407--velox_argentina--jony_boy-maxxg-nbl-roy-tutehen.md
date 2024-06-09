### Roster Details<br />
Team Name: VELOX Argentina<br />
Roster: JonY BoY, maxxg, nbl, roy, tutehen<br />
Region: [Americas]( ../standings_americas.md)<br />
<br />
Global Rank: [407](../standings_global.md)<br />
Regional Rank: [102]( ../standings_americas.md)<br />
Final Rank Value:  553.7<br />
<br />
Final Rank Value (553.7) = Starting Rank Value (580.5) + Head To Head Adjustments (-26.8)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.181[<sup>1</sup>](#table2)
- Bounty Collected: 0.171[<sup>2</sup>](#table1)
- Opponent Network: 0.003[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.089<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 580.5
- 400 + ( ( 0.089 - 0.000 ) / ( 0.787 - 0.000 ) ) * 1600 = 580.5


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent           | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                             |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           11 |       32 | 2024-05-29 | LA RUGONETA        | L   | 1.000      | -            | -                | -                | -         |   -18.10 | JonY BoY, maxxg, nbl, roy, tutehen |
|           10 |      113 | 2024-05-28 | Dusty Roots        | L   | 1.000      | -            | -                | -                | -         |   -10.75 | JonY BoY, maxxg, nbl, roy, tutehen |
|            9 |      156 | 2024-05-27 | TEAM ORUGA         | W   | 1.000      | 0.284        | 0.000 (0.000)    | 0.094 (0.027)    | 0 (0.000) |    16.01 | JonY BoY, maxxg, nbl, roy, tutehen |
|            8 |     4831 | 2024-03-09 | Team Solid         | L   | 0.657      | -            | -                | -                | -         |    -3.53 | JonY BoY, MRN1, nbl, roy, tutehen  |
|            7 |     4913 | 2024-03-07 | RED Canids         | L   | 0.646      | -            | -                | -                | -         |    -1.69 | JonY BoY, MRN1, nbl, roy, tutehen  |
|            6 |     5980 | 2024-02-19 | Team Solid         | L   | 0.533      | -            | -                | -                | -         |    -2.81 | JonY BoY, MRN1, nbl, roy, tutehen  |
|            5 |     8420 | 2024-01-08 | TIMACETA           | L   | 0.253      | -            | -                | -                | -         |    -3.40 | JonY BoY, MRN1, nbl, roy, tutehen  |
|            4 |     8652 | 2023-12-19 | Flamengo Esports   | L   | 0.117      | -            | -                | -                | -         |    -2.17 | JonY BoY, MRN1, nbl, roy, tutehen  |
|            3 |     8698 | 2023-12-17 | Case Esports       | L   | 0.105      | -            | -                | -                | -         |    -1.19 | JonY BoY, MRN1, nbl, roy, tutehen  |
|            2 |     8985 | 2023-12-15 | 9z Academy         | W   | 0.092      | 0.303        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     0.77 | JonY BoY, MRN1, nbl, roy, tutehen  |
|            1 |     9722 | 2023-12-02 | River Plate Gaming | W   | 0.005      | 0.284        | 0.000 (0.000)    | 0.000 (0.000)    | 1 (0.005) |     0.05 | JonY BoY, MRN1, nbl, roy, tutehen  |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($9.17)
- Divide that value by the 5th highest value among all rosters ($300,806.11)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
