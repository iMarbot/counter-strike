### Roster Details<br />
Team Name: Twisted Minds<br />
Roster: D0cC, day0s, KD69z, m4tthi, REAL1ZE<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [387](../standings_global.md)<br />
Regional Rank: [233]( ../standings_europe.md)<br />
Final Rank Value:  576.2<br />
<br />
Final Rank Value (576.2) = Starting Rank Value (591.6) + Head To Head Adjustments (-15.4)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.212[<sup>1</sup>](#table2)
- Bounty Collected: 0.164[<sup>2</sup>](#table1)
- Opponent Network: 0.001[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.094<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 591.6
- 400 + ( ( 0.094 - 0.000 ) / ( 0.787 - 0.000 ) ) * 1600 = 591.6


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent           | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                        |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           11 |     5545 | 2024-02-26 | JiJieHao           | L   | 0.580      | -            | -                | -                | -         |   -10.08 | D0cC, day0s, KD69z, m4tthi, REAL1ZE           |
|           10 |     5588 | 2024-02-25 | Lynn Vision Gaming | L   | 0.574      | -            | -                | -                | -         |    -1.02 | D0cC, day0s, KD69z, m4tthi, REAL1ZE           |
|            9 |     7082 | 2024-01-28 | JiJieHao           | L   | 0.384      | -            | -                | -                | -         |    -7.04 | D0cC, day0s, KD69z, m4tthi, SpAwNnS           |
|            8 |     7170 | 2024-01-27 | Bravado Gaming     | W   | 0.378      | 0.143        | 0.000 (0.000)    | 0.024 (0.001)    | 0 (0.000) |     4.53 | D0cC, day0s, KD69z, m4tthi, SpAwNnS           |
|            7 |     7192 | 2024-01-27 | Nixuh              | W   | 0.377      | 0.143        | 0.001 (0.000)    | 0.080 (0.004)    | 0 (0.000) |     6.63 | D0cC, day0s, KD69z, m4tthi, SpAwNnS           |
|            6 |     7266 | 2024-01-26 | JiJieHao           | L   | 0.370      | -            | -                | -                | -         |    -6.85 | D0cC, day0s, KD69z, m4tthi, SpAwNnS           |
|            5 |     7802 | 2024-01-17 | RUBY               | L   | 0.311      | -            | -                | -                | -         |    -1.51 | D0cC, day0s, KD69z, m4tthi, SpAwNnS           |
|            4 |     8329 | 2024-01-09 | Major Abusers      | W   | 0.258      | 0.143        | 0.000 (0.000)    | 0.007 (0.000)    | 0 (0.000) |     2.10 | N0R1, REAL1ZE, Revol, Senpai, x1ron           |
|            3 |     8387 | 2024-01-09 | 15 Average Gaming  | L   | 0.257      | -            | -                | -                | -         |    -5.19 | Joker, Lambdacore, Maxwell, Qweall, Ruskovvvv |
|            2 |     8429 | 2024-01-08 | PLASMA RAPID       | W   | 0.251      | 0.143        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     2.00 | B1zaaD, Djme1ster, ShizzleS, SoLiD, Zinou     |
|            1 |     9010 | 2023-12-15 | Nevermind          | W   | 0.090      | 0.249        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     1.08 | D0cC, day0s, Fessor, KD69z, SpAwNnS           |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($58.41)
- Divide that value by the 5th highest value among all rosters ($300,806.11)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
