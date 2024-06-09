### Roster Details<br />
Team Name: Infinite Gaming<br />
Roster: d1maje, mhN1, starplajerz, waZz, zewts<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [432](../standings_global.md)<br />
Regional Rank: [261]( ../standings_europe.md)<br />
Final Rank Value:  521.7<br />
<br />
Final Rank Value (521.7) = Starting Rank Value (500.0) + Head To Head Adjustments (21.7)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.000[<sup>1</sup>](#table2)
- Bounty Collected: 0.190[<sup>2</sup>](#table1)
- Opponent Network: 0.007[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.049<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 500.0
- 400 + ( ( 0.049 - 0.000 ) / ( 0.787 - 0.000 ) ) * 1600 = 500.0


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent         | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                     |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           10 |       69 | 2024-05-29 | Illuminar Gaming | W   | 1.000      | 0.143        | 0.004 (0.001)    | 0.403 (0.058)    | 0 (0.000) |    24.78 | d1maje, mhN1, starplajerz, waZz, zewts     |
|            9 |      581 | 2024-05-21 | Permitta Esports | L   | 1.000      | -            | -                | -                | -         |    -3.93 | d1maje, mhN1, starplajerz, waZz, zewts     |
|            8 |      801 | 2024-05-19 | UNiTY esports    | L   | 1.000      | -            | -                | -                | -         |    -3.31 | d1maje, mhN1, starplajerz, waZz, zewts     |
|            7 |     3981 | 2024-03-26 | BetBoom Team     | L   | 0.771      | -            | -                | -                | -         |    -0.21 | d1maje, mhN1, starplajerz, waZz, zewts     |
|            6 |     5287 | 2024-03-02 | B8               | L   | 0.611      | -            | -                | -                | -         |    -0.62 | d1maje, FREELOOK, mhN1, starplajerz, zewts |
|            5 |     6836 | 2024-02-02 | ex-sYnck         | L   | 0.417      | -            | -                | -                | -         |    -2.56 | d1maje, H4rder, mhN1, SAVAGE, starplajerz  |
|            4 |     7809 | 2024-01-17 | esmagaB          | L   | 0.311      | -            | -                | -                | -         |    -1.27 | d1maje, H4rder, mhN1, SAVAGE, starplajerz  |
|            3 |     8040 | 2024-01-13 | Permitta Esports | L   | 0.283      | -            | -                | -                | -         |    -0.67 | d1maje, H4rder, mhN1, SAVAGE, starplajerz  |
|            2 |     8084 | 2024-01-12 | showmakerz       | W   | 0.278      | 0.143        | 0.000 (0.000)    | 0.201 (0.008)    | 0 (0.000) |     4.95 | d1maje, H4rder, mhN1, SAVAGE, starplajerz  |
|            1 |     8097 | 2024-01-12 | M1X              | W   | 0.278      | 0.143        | 0.000 (0.000)    | 0.028 (0.001)    | 0 (0.000) |     4.50 | d1maje, H4rder, mhN1, SAVAGE, starplajerz  |

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
