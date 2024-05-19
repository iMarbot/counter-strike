### Roster Details<br />
Team Name: 2Game Esports<br />
Roster: Alisson, beg0d, dok, dzt, vhz<br />
Region: [Americas]( ../standings_americas.md)<br />
<br />
Global Rank: [296](../standings_global.md)<br />
Regional Rank: [65]( ../standings_americas.md)<br />
Final Rank Value:  616.9<br />
<br />
Final Rank Value (616.9) = Starting Rank Value (584.9) + Head To Head Adjustments (32.0)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.000[<sup>1</sup>](#table2)
- Bounty Collected: 0.315[<sup>2</sup>](#table1)
- Opponent Network: 0.058[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.093<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 584.9
- 400 + ( ( 0.093 - 0.000 ) / ( 0.806 - 0.000 ) ) * 1600 = 584.9


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent                     | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                        |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           23 |      396 | 2024-04-26 | Corinthians Esports          | L   | 1.000      | -            | -                | -                | -         |   -14.68 | Alisson, beg0d, dok, dzt, vhz |
|           22 |      678 | 2024-04-20 | MIBR Academy                 | L   | 1.000      | -            | -                | -                | -         |   -12.00 | beg0d, dok, dzt, jz, vhz      |
|           21 |      683 | 2024-04-20 | Looking4Org (Brazilian team) | W   | 1.000      | 0.143        | 0.003 (0.000)    | 0.138 (0.020)    | 0 (0.000) |    16.18 | beg0d, dok, dzt, jz, vhz      |
|           20 |     1435 | 2024-04-05 | AdalYamigos                  | W   | 1.000      | 0.450        | 0.000 (0.000)    | 0.174 (0.078)    | 0 (0.000) |    24.13 | beg0d, dok, dzt, santos, vhz  |
|           19 |     1437 | 2024-04-05 | AdalYamigos                  | L   | 0.999      | -            | -                | -                | -         |    -6.85 | beg0d, dok, dzt, santos, vhz  |
|           18 |     1517 | 2024-04-03 | Sharks Esports               | L   | 0.987      | -            | -                | -                | -         |    -4.60 | beg0d, dok, dzt, santos, vhz  |
|           17 |     1518 | 2024-04-03 | Sharks Esports               | L   | 0.986      | -            | -                | -                | -         |    -4.81 | beg0d, dok, dzt, santos, vhz  |
|           16 |     1722 | 2024-03-27 | Corinthians Esports          | W   | 0.940      | 0.450        | 0.005 (0.002)    | 0.346 (0.146)    | 0 (0.000) |    18.75 | beg0d, dok, dzt, santos, vhz  |
|           15 |     1726 | 2024-03-27 | Corinthians Esports          | L   | 0.940      | -            | -                | -                | -         |   -10.63 | beg0d, dok, dzt, santos, vhz  |
|           14 |     1786 | 2024-03-26 | Galorys                      | L   | 0.934      | -            | -                | -                | -         |    -7.01 | beg0d, dok, dzt, santos, vhz  |
|           13 |     1790 | 2024-03-26 | Galorys                      | L   | 0.933      | -            | -                | -                | -         |    -7.45 | beg0d, dok, dzt, santos, vhz  |
|           12 |     2010 | 2024-03-20 | Team Solid                   | W   | 0.893      | 0.450        | 0.138 (0.056)    | 0.275 (0.110)    | 0 (0.000) |    21.82 | beg0d, dok, dzt, santos, vhz  |
|           11 |     2014 | 2024-03-20 | Team Solid                   | L   | 0.893      | -            | -                | -                | -         |    -5.97 | beg0d, dok, dzt, santos, vhz  |
|           10 |     2201 | 2024-03-15 | ODDIK                        | L   | 0.860      | -            | -                | -                | -         |    -4.19 | beg0d, dok, dzt, santos, vhz  |
|            9 |     2202 | 2024-03-15 | ODDIK                        | L   | 0.860      | -            | -                | -                | -         |    -4.36 | beg0d, dok, dzt, santos, vhz  |
|            8 |     2358 | 2024-03-12 | Sharks Esports               | L   | 0.840      | -            | -                | -                | -         |    -4.19 | beg0d, dok, dzt, santos, vhz  |
|            7 |     2668 | 2024-03-05 | W7m esports                  | W   | 0.794      | 0.450        | 0.000 (0.000)    | 0.127 (0.046)    | 0 (0.000) |    13.26 | beg0d, dok, dzt, santos, vhz  |
|            6 |     2670 | 2024-03-05 | W7m esports                  | W   | 0.793      | 0.450        | 0.000 (0.000)    | 0.127 (0.046)    | 0 (0.000) |    14.21 | beg0d, dok, dzt, santos, vhz  |
|            5 |     3119 | 2024-02-24 | Case Esports                 | L   | 0.727      | -            | -                | -                | -         |    -5.38 | beg0d, dok, dzt, santos, vhz  |
|            4 |     3126 | 2024-02-24 | Case Esports                 | W   | 0.727      | 0.450        | 0.027 (0.009)    | 0.401 (0.131)    | 0 (0.000) |    17.93 | beg0d, dok, dzt, santos, vhz  |
|            3 |     3279 | 2024-02-21 | Imperial Esports             | L   | 0.707      | -            | -                | -                | -         |    -0.10 | beg0d, dok, dzt, santos, vhz  |
|            2 |     3282 | 2024-02-21 | Imperial Esports             | L   | 0.707      | -            | -                | -                | -         |    -0.10 | beg0d, dok, dzt, santos, vhz  |
|            1 |     3611 | 2024-02-14 | 9z Team                      | L   | 0.660      | -            | -                | -                | -         |    -1.92 | beg0d, dok, dzt, santos, vhz  |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($0.00)
- Divide that value by the 5th highest value among all rosters ($158,437.64)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
