### Roster Details<br />
Team Name: Team Vitality<br />
Roster: apEX, flameZ, mezii, Spinx, ZywOo<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [4](../standings_global.md)<br />
Regional Rank: [4]( ../standings_europe.md)<br />
Final Rank Value:  1828.7<br />
<br />
Final Rank Value (1828.7) = Starting Rank Value (1844.3) + Head To Head Adjustments (-15.6)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.864[<sup>1</sup>](#table2)
- Bounty Collected: 0.651[<sup>2</sup>](#table1)
- Opponent Network: 0.355[<sup>2</sup>](#table1)
- LAN Wins: 0.972[<sup>2</sup>](#table1)

The average of these factors is 0.711<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1844.3
- 400 + ( ( 0.711 - 0.000 ) / ( 0.787 - 0.000 ) ) * 1600 = 1844.3


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent          | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                            |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           29 |       38 | 2024-05-29 | 9z Team           | L   | 1.000      | -            | -                | -                | -         |   -30.28 | apEX, flameZ, mezii, Spinx, ZywOo |
|           28 |      157 | 2024-05-27 | G2 Esports        | W   | 1.000      | 0.624        | 0.468 (0.292)    | 0.392 (0.244)    | 1 (1.000) |    11.23 | apEX, flameZ, mezii, Spinx, ZywOo |
|           27 |      176 | 2024-05-27 | Monte             | W   | 1.000      | 0.624        | 0.181 (0.113)    | 0.387 (0.242)    | 1 (1.000) |     1.08 | apEX, flameZ, mezii, Spinx, ZywOo |
|           26 |     1378 | 2024-05-12 | MOUZ              | L   | 1.000      | -            | -                | -                | -         |   -10.33 | apEX, flameZ, mezii, Spinx, ZywOo |
|           25 |     1461 | 2024-05-11 | Astralis          | W   | 1.000      | 0.889        | 0.395 (0.351)    | 0.286 (0.254)    | 1 (1.000) |     9.64 | apEX, flameZ, mezii, Spinx, ZywOo |
|           24 |     1511 | 2024-05-10 | FaZe Clan         | W   | 1.000      | 0.889        | 1.000 (0.889)    | 0.457 (0.406)    | 1 (1.000) |    20.83 | apEX, flameZ, mezii, Spinx, ZywOo |
|           23 |     2161 | 2024-04-28 | The MongolZ       | W   | 0.989      | 0.889        | 0.192 (0.169)    | 0.619 (0.544)    | 1 (0.989) |     6.42 | apEX, flameZ, mezii, Spinx, ZywOo |
|           22 |     2361 | 2024-04-25 | BetBoom Team      | W   | 0.970      | 0.889        | 0.390 (0.336)    | 0.712 (0.613)    | 1 (0.970) |     1.97 | apEX, flameZ, mezii, Spinx, ZywOo |
|           21 |     2471 | 2024-04-23 | Sharks Esports    | W   | 0.956      | -            | -                | -                | 1 (0.956) |     0.07 | apEX, flameZ, mezii, Spinx, ZywOo |
|           20 |     3763 | 2024-03-30 | FaZe Clan         | L   | 0.797      | -            | -                | -                | -         |    -7.62 | apEX, flameZ, mezii, Spinx, ZywOo |
|           19 |     3836 | 2024-03-28 | Cloud9            | W   | 0.784      | 1.000        | 0.187 (0.147)    | 0.253 (0.198)    | 1 (0.784) |     4.41 | apEX, flameZ, mezii, Spinx, ZywOo |
|           18 |     4097 | 2024-03-23 | Complexity Gaming | W   | 0.750      | 1.000        | 0.260 (0.195)    | 0.219 (0.164)    | 1 (0.750) |     4.31 | apEX, flameZ, mezii, Spinx, ZywOo |
|           17 |     4140 | 2024-03-22 | Imperial Esports  | W   | 0.743      | 1.000        | 0.372 (0.276)    | 0.582 (0.432)    | 1 (0.743) |     3.31 | apEX, flameZ, mezii, Spinx, ZywOo |
|           16 |     4188 | 2024-03-21 | The MongolZ       | W   | 0.737      | 1.000        | 0.192 (0.141)    | 0.619 (0.456)    | -         |     4.78 | apEX, flameZ, mezii, Spinx, ZywOo |
|           15 |     4196 | 2024-03-21 | Eternal Fire      | L   | 0.736      | -            | -                | -                | -         |   -11.09 | apEX, flameZ, mezii, Spinx, ZywOo |
|           14 |     5881 | 2024-02-21 | ENCE              | W   | 0.543      | -            | -                | -                | -         |     1.96 | apEX, flameZ, mezii, Spinx, ZywOo |
|           13 |     5946 | 2024-02-20 | Cloud9            | L   | 0.536      | -            | -                | -                | -         |   -14.59 | apEX, flameZ, mezii, Spinx, ZywOo |
|           12 |     5988 | 2024-02-19 | HEROIC            | W   | 0.531      | -            | -                | -                | -         |     6.30 | apEX, flameZ, mezii, Spinx, ZywOo |
|           11 |     6023 | 2024-02-19 | GamerLegion       | W   | 0.529      | -            | -                | -                | -         |     0.64 | apEX, flameZ, mezii, Spinx, ZywOo |
|           10 |     6636 | 2024-02-05 | HEROIC            | L   | 0.436      | -            | -                | -                | -         |    -8.65 | apEX, flameZ, mezii, Spinx, ZywOo |
|            9 |     6697 | 2024-02-03 | ENCE              | L   | 0.425      | -            | -                | -                | -         |   -12.14 | apEX, flameZ, mezii, Spinx, ZywOo |
|            8 |     7211 | 2024-01-27 | Astralis          | W   | 0.376      | -            | -                | -                | -         |     3.26 | apEX, flameZ, mezii, Spinx, ZywOo |
|            7 |     7284 | 2024-01-26 | Team Falcons      | W   | 0.369      | -            | -                | -                | -         |     1.35 | apEX, flameZ, mezii, Spinx, ZywOo |
|            6 |     7420 | 2024-01-23 | Astralis          | L   | 0.350      | -            | -                | -                | -         |    -8.13 | apEX, flameZ, mezii, Spinx, ZywOo |
|            5 |     7479 | 2024-01-22 | OG                | W   | 0.343      | -            | -                | -                | -         |     0.27 | apEX, flameZ, mezii, Spinx, ZywOo |
|            4 |     8734 | 2023-12-17 | FaZe Clan         | W   | 0.103      | -            | -                | -                | -         |     2.28 | apEX, flameZ, mezii, Spinx, ZywOo |
|            3 |     8881 | 2023-12-16 | Natus Vincere     | W   | 0.097      | -            | -                | -                | -         |     1.59 | apEX, flameZ, mezii, Spinx, ZywOo |
|            2 |     9057 | 2023-12-14 | Cloud9            | W   | 0.082      | -            | -                | -                | -         |     0.32 | apEX, flameZ, mezii, Spinx, ZywOo |
|            1 |     9119 | 2023-12-13 | Natus Vincere     | W   | 0.075      | -            | -                | -                | -         |     1.24 | apEX, flameZ, mezii, Spinx, ZywOo |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($209,248.96)
- Divide that value by the 5th highest value among all rosters ($300,806.11)
- The final value (0.70) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-05-12 |      1.000 | $80,000.00     | $80,000.00      |
| 2024-03-31 |      0.804 | $80,000.00     | $64,311.11      |
| 2024-02-11 |      0.477 | $10,000.00     | $4,769.44       |
| 2024-01-28 |      0.384 | $22,500.00     | $8,640.63       |
| 2023-12-17 |      0.103 | $500,000.00    | $51,527.78      |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
