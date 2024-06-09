### Roster Details<br />
Team Name: Eternal Fire<br />
Roster: Calyx, MAJ3R, Wicadia, woxic, XANTARES<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [6](../standings_global.md)<br />
Regional Rank: [6]( ../standings_europe.md)<br />
Final Rank Value:  1780.7<br />
<br />
Final Rank Value (1780.7) = Starting Rank Value (1843.9) + Head To Head Adjustments (-63.1)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 1.000[<sup>1</sup>](#table2)
- Bounty Collected: 0.673[<sup>2</sup>](#table1)
- Opponent Network: 0.394[<sup>2</sup>](#table1)
- LAN Wins: 0.775[<sup>2</sup>](#table1)

The average of these factors is 0.710<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1843.9
- 400 + ( ( 0.710 - 0.000 ) / ( 0.787 - 0.000 ) ) * 1600 = 1843.9


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent          | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                 |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           35 |      419 | 2024-05-23 | Team Liquid       | W   | 1.000      | 0.769        | 0.493 (0.379)    | 0.621 (0.477)    | -         |     9.81 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           34 |      505 | 2024-05-22 | GamerLegion       | W   | 1.000      | 0.769        | 0.224 (0.172)    | -                | -         |     1.99 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           33 |      605 | 2024-05-21 | BetBoom Team      | W   | 1.000      | 0.769        | 0.390 (0.299)    | 0.712 (0.547)    | -         |     2.72 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           32 |     1076 | 2024-05-16 | SAW               | W   | 1.000      | 0.769        | -                | 0.388 (0.298)    | -         |     3.72 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           31 |     1102 | 2024-05-16 | PARIVISION        | W   | 1.000      | 0.769        | -                | 0.329 (0.253)    | -         |     0.28 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           30 |     2209 | 2024-04-27 | SAW               | L   | 0.984      | -            | -                | -                | -         |   -27.88 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           29 |     2296 | 2024-04-26 | FaZe Clan         | L   | 0.977      | -            | -                | -                | -         |    -9.08 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           28 |     2338 | 2024-04-25 | Fnatic            | W   | 0.971      | 0.889        | -                | 0.480 (0.414)    | 1 (0.971) |     0.84 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           27 |     2412 | 2024-04-24 | Imperial Esports  | W   | 0.964      | 0.889        | 0.372 (0.319)    | 0.582 (0.498)    | 1 (0.964) |     4.13 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           26 |     2465 | 2024-04-23 | Astralis          | L   | 0.956      | -            | -                | -                | -         |   -20.77 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           25 |     2625 | 2024-04-20 | Sashi Esport      | L   | 0.937      | -            | -                | -                | -         |   -28.84 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           24 |     2746 | 2024-04-19 | Sashi Esport      | W   | 0.930      | -            | -                | -                | -         |     0.51 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           23 |     2771 | 2024-04-19 | BetBoom Team      | W   | 0.929      | -            | -                | -                | -         |     1.65 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           22 |     3798 | 2024-03-29 | Natus Vincere     | L   | 0.790      | -            | -                | -                | -         |   -12.53 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           21 |     4108 | 2024-03-23 | Virtus.pro        | W   | 0.749      | 1.000        | 0.271 (0.203)    | -                | 1 (0.749) |     7.36 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           20 |     4139 | 2024-03-22 | FaZe Clan         | W   | 0.743      | 1.000        | 1.000 (0.743)    | 0.457 (0.339)    | 1 (0.743) |    15.65 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           19 |     4187 | 2024-03-21 | MOUZ              | L   | 0.737      | -            | -                | -                | -         |    -7.38 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           18 |     4196 | 2024-03-21 | Team Vitality     | W   | 0.736      | 1.000        | 0.696 (0.512)    | -                | 1 (0.736) |    11.09 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           17 |     4284 | 2024-03-19 | GamerLegion       | W   | 0.723      | -            | -                | -                | 1 (0.723) |     0.89 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           16 |     4321 | 2024-03-18 | HEROIC            | L   | 0.716      | -            | -                | -                | -         |   -14.78 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           15 |     4358 | 2024-03-17 | paiN Gaming       | W   | 0.711      | 1.000        | 0.463 (0.329)    | 0.547 (0.389)    | 1 (0.711) |     4.08 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           14 |     4393 | 2024-03-17 | The MongolZ       | W   | 0.709      | 1.000        | -                | 0.619 (0.439)    | 1 (0.709) |     4.58 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           13 |     6115 | 2024-02-17 | BetBoom Team      | W   | 0.517      | -            | -                | -                | 1 (0.517) |     1.29 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           12 |     6170 | 2024-02-16 | FaZe Clan         | L   | 0.510      | -            | -                | -                | -         |    -4.90 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           11 |     6243 | 2024-02-15 | Team Falcons      | W   | 0.502      | -            | -                | -                | 1 (0.502) |     2.13 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           10 |     6272 | 2024-02-14 | G2 Esports        | L   | 0.498      | -            | -                | -                | -         |    -8.81 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|            9 |     6293 | 2024-02-14 | Ninjas in Pyjamas | W   | 0.496      | -            | -                | -                | -         |     0.04 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|            8 |     6608 | 2024-02-05 | Natus Vincere     | L   | 0.438      | -            | -                | -                | -         |    -6.46 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|            7 |     6652 | 2024-02-04 | FaZe Clan         | L   | 0.431      | -            | -                | -                | -         |    -4.21 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|            6 |     6771 | 2024-02-03 | Team Falcons      | W   | 0.423      | 1.000        | 0.355 (0.150)    | -                | -         |     1.46 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|            5 |     6908 | 2024-01-31 | Rebels Gaming     | W   | 0.405      | -            | -                | -                | -         |     0.17 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|            4 |     6940 | 2024-01-31 | BetBoom Team      | W   | 0.403      | 1.000        | 0.390 (0.157)    | 0.712 (0.287)    | -         |     1.14 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|            3 |     7651 | 2024-01-19 | MOUZ              | W   | 0.324      | -            | -                | -                | -         |     6.91 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|            2 |     7718 | 2024-01-18 | IKLA              | W   | 0.317      | -            | -                | -                | -         |     0.01 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|            1 |     7733 | 2024-01-18 | Pera Esports      | W   | 0.317      | -            | -                | -                | -         |     0.06 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($300,806.11)
- Divide that value by the 5th highest value among all rosters ($300,806.11)
- The final value (1.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-05-23 |      1.000 | $250,000.00    | $250,000.00     |
| 2024-05-12 |      1.000 | $7,000.00      | $7,000.00       |
| 2024-03-31 |      0.804 | $45,000.00     | $36,175.00      |
| 2024-02-11 |      0.477 | $16,000.00     | $7,631.11       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
