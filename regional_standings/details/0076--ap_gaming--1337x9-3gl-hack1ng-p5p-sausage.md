### Roster Details<br />
Team Name: AP Gaming<br />
Roster: 1337x9, 3gl, Hack1ng, p5p, sausage<br />
Region: [Asia]( ../standings_asia.md)<br />
<br />
Global Rank: [76](../standings_global.md)<br />
Regional Rank: [8]( ../standings_asia.md)<br />
Final Rank Value:  901.5<br />
<br />
Final Rank Value (901.5) = Starting Rank Value (941.9) + Head To Head Adjustments (-40.4)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.479[<sup>1</sup>](#table2)
- Bounty Collected: 0.272[<sup>2</sup>](#table1)
- Opponent Network: 0.007[<sup>2</sup>](#table1)
- LAN Wins: 0.334[<sup>2</sup>](#table1)

The average of these factors is 0.273<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 941.9
- 400 + ( ( 0.273 - 0.000 ) / ( 0.806 - 0.000 ) ) * 1600 = 941.9


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent      | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                 |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           12 |       24 | 2024-05-05 | E9 esports    | W   | 1.000      | 0.143        | 0.035 (0.005)    | 0.035 (0.005)    | 1 (1.000) |    13.39 | 1337x9, 3gl, Hack1ng, p5p, sausage     |
|           11 |       37 | 2024-05-04 | E9 esports    | W   | 1.000      | 0.143        | 0.035 (0.005)    | 0.035 (0.005)    | 1 (1.000) |    14.01 | 1337x9, 3gl, Hack1ng, p5p, sausage     |
|           10 |       86 | 2024-05-04 | Sheer Conquer | W   | 1.000      | 0.143        | 0.035 (0.005)    | 0.211 (0.030)    | 1 (1.000) |    14.82 | 1337x9, 3gl, Hack1ng, p5p, sausage     |
|            9 |     1125 | 2024-04-13 | Sheer Conquer | L   | 1.000      | -            | -                | -                | -         |   -18.92 | 1337x9, 3gl, chengking, p5p, sausage   |
|            8 |     1425 | 2024-04-06 | Team Remember | W   | 1.000      | 0.143        | 0.022 (0.003)    | 0.067 (0.010)    | 0 (0.000) |     8.81 | 1337x9, 3gl, chengking, p5p, sausage   |
|            7 |     1429 | 2024-04-06 | Sheer Conquer | L   | 1.000      | -            | -                | -                | -         |   -20.70 | 1337x9, 3gl, chengking, p5p, sausage   |
|            6 |     2522 | 2024-03-08 | E9 esports    | L   | 0.815      | -            | -                | -                | -         |   -17.17 | 1337x9, 3gl, hack1ng, p5p, PAN1K       |
|            5 |     2583 | 2024-03-07 | Steel Helmet  | W   | 0.803      | 0.143        | 0.025 (0.003)    | 0.174 (0.020)    | 0 (0.000) |     6.14 | 1337x9, 3gl, hack1ng, p5p, PAN1K       |
|            4 |     2589 | 2024-03-07 | E9 esports    | L   | 0.803      | -            | -                | -                | -         |   -17.68 | 1337x9, 3gl, hack1ng, p5p, PAN1K       |
|            3 |     4357 | 2024-01-25 | Rare Atom     | L   | 0.524      | -            | -                | -                | -         |   -11.39 | 1337x9, chengking, hack1ng, p5p, PAN1K |
|            2 |     4367 | 2024-01-24 | Bromo Esport  | W   | 0.522      | 0.143        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     0.81 | 1337x9, chengking, hack1ng, p5p, PAN1K |
|            1 |     4967 | 2024-01-11 | WDNMD         | L   | 0.435      | -            | -                | -                | -         |   -12.51 | 1337x9, chengking, hack1ng, p5p, PAN1K |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($12,988.89)
- Divide that value by the 5th highest value among all rosters ($158,437.64)
- The final value (0.08) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-05-05 |      1.000 | $11,053.84     | $11,053.84      |
| 2024-04-13 |      1.000 | $967.25        | $967.25         |
| 2024-04-06 |      1.000 | $967.80        | $967.80         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
