### Roster Details<br />
Team Name: AP Gaming<br />
Roster: 1337x9, 3gl, Hack1ng, p5p, sausage<br />
Region: [Asia]( ../standings_asia.md)<br />
<br />
Global Rank: [95](../standings_global.md)<br />
Regional Rank: [7]( ../standings_asia.md)<br />
Final Rank Value:  879.0<br />
<br />
Final Rank Value (879.0) = Starting Rank Value (904.5) + Head To Head Adjustments (-25.5)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.421[<sup>1</sup>](#table2)
- Bounty Collected: 0.250[<sup>2</sup>](#table1)
- Opponent Network: 0.004[<sup>2</sup>](#table1)
- LAN Wins: 0.317[<sup>2</sup>](#table1)

The average of these factors is 0.248<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 904.5
- 400 + ( ( 0.248 - 0.000 ) / ( 0.787 - 0.000 ) ) * 1600 = 904.5


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
|           12 |     1800 | 2024-05-05 | E9 esports    | W   | 1.000      | 0.143        | 0.018 (0.003)    | 0.028 (0.004)    | 1 (1.000) |    13.32 | 1337x9, 3gl, Hack1ng, p5p, sausage     |
|           11 |     1814 | 2024-05-04 | E9 esports    | W   | 1.000      | 0.143        | 0.018 (0.003)    | 0.028 (0.004)    | 1 (1.000) |    13.91 | 1337x9, 3gl, Hack1ng, p5p, sausage     |
|           10 |     1877 | 2024-05-04 | Sheer Conquer | W   | 1.000      | 0.143        | 0.017 (0.002)    | 0.151 (0.022)    | 1 (1.000) |    14.24 | 1337x9, 3gl, Hack1ng, p5p, sausage     |
|            9 |     3120 | 2024-04-12 | Sheer Conquer | L   | 0.887      | -            | -                | -                | -         |   -17.33 | 1337x9, 3gl, chengking, p5p, sausage   |
|            8 |     3505 | 2024-04-06 | Team Remember | W   | 0.841      | 0.143        | 0.010 (0.001)    | 0.044 (0.005)    | 0 (0.000) |     7.37 | 1337x9, 3gl, chengking, p5p, sausage   |
|            7 |     3510 | 2024-04-05 | Sheer Conquer | L   | 0.841      | -            | -                | -                | -         |   -17.75 | 1337x9, 3gl, chengking, p5p, sausage   |
|            6 |     4869 | 2024-03-08 | E9 esports    | L   | 0.654      | -            | -                | -                | -         |   -14.31 | 1337x9, 3gl, hack1ng, p5p, PAN1K       |
|            5 |     4955 | 2024-03-07 | Steel Helmet  | W   | 0.642      | 0.143        | 0.012 (0.001)    | 0.087 (0.008)    | 0 (0.000) |     4.96 | 1337x9, 3gl, hack1ng, p5p, PAN1K       |
|            4 |     4962 | 2024-03-07 | E9 esports    | L   | 0.642      | -            | -                | -                | -         |   -14.58 | 1337x9, 3gl, hack1ng, p5p, PAN1K       |
|            3 |     7313 | 2024-01-25 | Rare Atom     | L   | 0.363      | -            | -                | -                | -         |    -8.24 | 1337x9, chengking, hack1ng, p5p, PAN1K |
|            2 |     7324 | 2024-01-24 | Bromo Esport  | W   | 0.361      | 0.143        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     0.66 | 1337x9, chengking, hack1ng, p5p, PAN1K |
|            1 |     8145 | 2024-01-11 | WDNMD         | L   | 0.274      | -            | -                | -                | -         |    -7.78 | 1337x9, chengking, hack1ng, p5p, PAN1K |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($12,726.84)
- Divide that value by the 5th highest value among all rosters ($300,806.11)
- The final value (0.04) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-05-05 |      1.000 | $11,053.84     | $11,053.84      |
| 2024-04-13 |      0.888 | $967.25        | $858.70         |
| 2024-04-06 |      0.841 | $967.80        | $814.30         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
