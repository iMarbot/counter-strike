### Roster Details<br />
Team Name: AdalYamigos<br />
Roster: delboNi, f4stzin, piria, shz, zqk<br />
Region: [Americas]( ../standings_americas.md)<br />
<br />
Global Rank: [122](../standings_global.md)<br />
Regional Rank: [21]( ../standings_americas.md)<br />
Final Rank Value:  813.4<br />
<br />
Final Rank Value (813.4) = Starting Rank Value (740.2) + Head To Head Adjustments (73.1)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.202[<sup>1</sup>](#table2)
- Bounty Collected: 0.353[<sup>2</sup>](#table1)
- Opponent Network: 0.131[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.171<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 740.2
- 400 + ( ( 0.171 - 0.000 ) / ( 0.806 - 0.000 ) ) * 1600 = 740.2


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent            | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins      | H2H Adj. | Roster                                |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           16 |     1270 | 2024-04-09 | MIBR                | L   | 1.000      | -            | -                | -                | -             |    -0.55 | delboNi, f4stzin, piria, shz, zqk     |
|           15 |     1275 | 2024-04-09 | MIBR                | L   | 1.000      | -            | -                | -                | -             |    -0.55 | delboNi, f4stzin, piria, shz, zqk     |
|           14 |     1435 | 2024-04-05 | 2Game Esports       | L   | 1.000      | -            | -                | -                | -             |   -24.13 | delboNi, f4stzin, piria, shz, zqk     |
|           13 |     1437 | 2024-04-05 | 2Game Esports       | W   | 0.999      | 0.450        | -                | 0.188 (0.085)    | false (0.000) |     6.85 | delboNi, f4stzin, piria, shz, zqk     |
|           12 |     1463 | 2024-04-04 | BESTIA              | W   | 0.994      | 0.450        | 0.026 (0.012)    | 0.423 (0.189)    | false (0.000) |    16.19 | delboNi, f4stzin, piria, shz, zqk     |
|           11 |     1469 | 2024-04-04 | BESTIA              | L   | 0.993      | -            | -                | -                | -             |   -15.06 | delboNi, f4stzin, piria, shz, zqk     |
|           10 |     2667 | 2024-03-05 | Case Esports        | W   | 0.794      | 0.450        | 0.027 (0.010)    | 0.401 (0.143)    | false (0.000) |    11.14 | delboNi, f4stzin, piria, shz, zqk     |
|            9 |     2669 | 2024-03-05 | Case Esports        | W   | 0.793      | 0.450        | 0.027 (0.010)    | 0.401 (0.143)    | false (0.000) |    11.95 | delboNi, f4stzin, piria, shz, zqk     |
|            8 |     3281 | 2024-02-21 | Galorys             | W   | 0.707      | 0.450        | 0.048 (0.015)    | 0.598 (0.190)    | false (0.000) |    11.53 | delboNi, f4stzin, piria, shz, zqk     |
|            7 |     3284 | 2024-02-21 | Galorys             | W   | 0.707      | 0.450        | 0.048 (0.015)    | 0.598 (0.190)    | false (0.000) |    12.27 | delboNi, f4stzin, piria, shz, zqk     |
|            6 |     3612 | 2024-02-14 | Corinthians Esports | W   | 0.660      | 0.450        | 0.005 (0.002)    | 0.346 (0.103)    | false (0.000) |     8.06 | delboNi, f4stzin, piria, shz, zqk     |
|            5 |     3614 | 2024-02-14 | Corinthians Esports | W   | 0.660      | 0.450        | 0.005 (0.002)    | 0.346 (0.103)    | false (0.000) |     8.52 | delboNi, f4stzin, piria, shz, zqk     |
|            4 |     3660 | 2024-02-13 | Team Solid          | W   | 0.654      | 0.450        | 0.138 (0.041)    | 0.275 (0.081)    | false (0.000) |    12.44 | delboNi, f4stzin, piria, shz, zqk     |
|            3 |     3662 | 2024-02-13 | Team Solid          | W   | 0.653      | 0.450        | 0.138 (0.041)    | 0.275 (0.081)    | false (0.000) |    13.13 | delboNi, f4stzin, piria, shz, zqk     |
|            2 |     6688 | 2023-11-18 | TIMACETA            | W   | 0.074      | 0.143        | 0.001 (0.000)    | -                | -             |     0.89 | bnc, farias, leleo, nyezin, will1ZERA |
|            1 |     6690 | 2023-11-18 | AREA53              | W   | 0.074      | -            | -                | -                | -             |     0.46 | freitas, JMS, KLR, kxr, sickboyrare   |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($18.18)
- Divide that value by the 5th highest value among all rosters ($158,437.64)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
