### Roster Details<br />
Team Name: Team Vitality<br />
Roster: apEX, flameZ, mezii, Spinx, ZywOo<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [5](../standings_global.md)<br />
Regional Rank: [5]( ../standings_europe.md)<br />
Final Rank Value:  1876.6<br />
<br />
Final Rank Value (1876.6) = Starting Rank Value (1898.7) + Head To Head Adjustments (-22.1)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 1.000[<sup>1</sup>](#table2)
- Bounty Collected: 0.674[<sup>2</sup>](#table1)
- Opponent Network: 0.373[<sup>2</sup>](#table1)
- LAN Wins: 0.975[<sup>2</sup>](#table1)

The average of these factors is 0.755<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1898.7
- 400 + ( ( 0.755 - 0.000 ) / ( 0.806 - 0.000 ) ) * 1600 = 1898.7


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent          | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins     | H2H Adj. | Roster                            |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           27 |      322 | 2024-04-28 | The MongolZ       | W   | 1.000      | 0.889        | 0.292 (0.260)    | 0.663 (0.589)    | true (1.000) |     5.31 | apEX, flameZ, mezii, Spinx, ZywOo |
|           26 |      483 | 2024-04-25 | BetBoom Team      | W   | 1.000      | 0.889        | 0.571 (0.508)    | 0.824 (0.732)    | true (1.000) |     2.07 | apEX, flameZ, mezii, Spinx, ZywOo |
|           25 |      580 | 2024-04-23 | Sharks Esports    | W   | 1.000      | 0.889        | -                | 0.343 (0.305)    | true (1.000) |     0.16 | apEX, flameZ, mezii, Spinx, ZywOo |
|           24 |     1633 | 2024-03-30 | FaZe Clan         | L   | 0.958      | -            | -                | -                | -            |   -11.70 | apEX, flameZ, mezii, Spinx, ZywOo |
|           23 |     1696 | 2024-03-28 | Cloud9            | W   | 0.945      | 1.000        | 0.487 (0.460)    | 0.419 (0.396)    | true (0.945) |    10.74 | apEX, flameZ, mezii, Spinx, ZywOo |
|           22 |     1909 | 2024-03-23 | Complexity Gaming | W   | 0.911      | 1.000        | 0.271 (0.247)    | 0.274 (0.250)    | true (0.911) |     3.32 | apEX, flameZ, mezii, Spinx, ZywOo |
|           21 |     1947 | 2024-03-22 | Imperial Esports  | W   | 0.904      | 1.000        | 0.674 (0.609)    | 0.549 (0.496)    | true (0.904) |     3.56 | apEX, flameZ, mezii, Spinx, ZywOo |
|           20 |     1983 | 2024-03-21 | The MongolZ       | W   | 0.898      | 1.000        | 0.292 (0.262)    | 0.663 (0.595)    | true (0.898) |     5.31 | apEX, flameZ, mezii, Spinx, ZywOo |
|           19 |     1991 | 2024-03-21 | Eternal Fire      | L   | 0.897      | -            | -                | -                | -            |   -17.19 | apEX, flameZ, mezii, Spinx, ZywOo |
|           18 |     3312 | 2024-02-21 | ENCE              | W   | 0.704      | -            | -                | -                | true (0.704) |     3.26 | apEX, flameZ, mezii, Spinx, ZywOo |
|           17 |     3365 | 2024-02-20 | Cloud9            | L   | 0.697      | -            | -                | -                | -            |   -14.93 | apEX, flameZ, mezii, Spinx, ZywOo |
|           16 |     3396 | 2024-02-19 | HEROIC            | W   | 0.692      | -            | -                | -                | true (0.692) |     5.56 | apEX, flameZ, mezii, Spinx, ZywOo |
|           15 |     3428 | 2024-02-19 | GamerLegion       | W   | 0.690      | -            | -                | -                | true (0.690) |     3.52 | apEX, flameZ, mezii, Spinx, ZywOo |
|           14 |     3906 | 2024-02-05 | HEROIC            | L   | 0.597      | -            | -                | -                | -            |   -14.30 | apEX, flameZ, mezii, Spinx, ZywOo |
|           13 |     3943 | 2024-02-03 | ENCE              | L   | 0.586      | -            | -                | -                | -            |   -16.33 | apEX, flameZ, mezii, Spinx, ZywOo |
|           12 |     4288 | 2024-01-27 | Astralis          | W   | 0.537      | -            | -                | -                | -            |     1.98 | apEX, flameZ, mezii, Spinx, ZywOo |
|           11 |     4337 | 2024-01-26 | Team Falcons      | W   | 0.530      | -            | -                | -                | -            |     0.76 | apEX, flameZ, mezii, Spinx, ZywOo |
|           10 |     4431 | 2024-01-23 | Astralis          | L   | 0.512      | -            | -                | -                | -            |   -14.41 | apEX, flameZ, mezii, Spinx, ZywOo |
|            9 |     4477 | 2024-01-22 | OG                | W   | 0.505      | 0.581        | 0.594 (0.174)    | 0.390 (0.114)    | -            |     0.55 | apEX, flameZ, mezii, Spinx, ZywOo |
|            8 |     5370 | 2023-12-17 | FaZe Clan         | W   | 0.264      | 1.000        | 1.000 (0.264)    | 0.566 (0.150)    | -            |     5.14 | apEX, flameZ, mezii, Spinx, ZywOo |
|            7 |     5481 | 2023-12-16 | Natus Vincere     | W   | 0.258      | 1.000        | 1.000 (0.258)    | 0.406 (0.105)    | -            |     4.54 | apEX, flameZ, mezii, Spinx, ZywOo |
|            6 |     5617 | 2023-12-14 | Cloud9            | W   | 0.243      | -            | -                | -                | -            |     2.57 | apEX, flameZ, mezii, Spinx, ZywOo |
|            5 |     5656 | 2023-12-13 | Natus Vincere     | W   | 0.236      | 1.000        | 1.000 (0.236)    | -                | -            |     4.24 | apEX, flameZ, mezii, Spinx, ZywOo |
|            4 |     6391 | 2023-11-26 | FaZe Clan         | W   | 0.125      | -            | -                | -                | -            |     2.50 | apEX, flameZ, mezii, Spinx, ZywOo |
|            3 |     6435 | 2023-11-25 | Cloud9            | W   | 0.118      | -            | -                | -                | -            |     1.33 | apEX, flameZ, mezii, Spinx, ZywOo |
|            2 |     6511 | 2023-11-23 | Complexity Gaming | W   | 0.105      | -            | -                | -                | -            |     0.38 | apEX, flameZ, mezii, Spinx, ZywOo |
|            1 |     6571 | 2023-11-22 | HEROIC            | W   | 0.098      | -            | -                | -                | -            |     0.00 | apEX, flameZ, mezii, Spinx, ZywOo |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($252,858.56)
- Divide that value by the 5th highest value among all rosters ($158,437.64)
- The final value (1.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-03-31 |      0.965 | $80,000.00     | $77,218.52      |
| 2024-02-11 |      0.638 | $10,000.00     | $6,380.09       |
| 2024-01-28 |      0.545 | $22,500.00     | $12,264.58      |
| 2023-12-17 |      0.264 | $500,000.00    | $132,060.19     |
| 2023-11-26 |      0.125 | $200,000.00    | $24,935.19      |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
