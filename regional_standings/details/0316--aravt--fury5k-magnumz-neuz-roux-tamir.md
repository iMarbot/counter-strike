### Roster Details<br />
Team Name: Aravt<br />
Roster: fury5k, MagnumZ, NEUZ, ROUX, tamir<br />
Region: [Asia]( ../standings_asia.md)<br />
<br />
Global Rank: [316](../standings_global.md)<br />
Regional Rank: [51]( ../standings_asia.md)<br />
Final Rank Value:  592.5<br />
<br />
Final Rank Value (592.5) = Starting Rank Value (543.8) + Head To Head Adjustments (48.7)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.000[<sup>1</sup>](#table2)
- Bounty Collected: 0.263[<sup>2</sup>](#table1)
- Opponent Network: 0.011[<sup>2</sup>](#table1)
- LAN Wins: 0.017[<sup>2</sup>](#table1)

The average of these factors is 0.072<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 543.8
- 400 + ( ( 0.072 - 0.000 ) / ( 0.806 - 0.000 ) ) * 1600 = 543.8


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent                    | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                               |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           27 |     4130 | 2024-01-30 | Gods Reign                  | W   | 0.562      | 0.143        | 0.174 (0.014)    | 0.479 (0.038)    | 0 (0.000) |    15.19 | fury5k, MagnumZ, NEUZ, ROUX, tamir   |
|           26 |     4370 | 2024-01-24 | The Huns Esports            | L   | 0.522      | -            | -                | -                | -         |    -2.05 | fury5k, MagnumZ, NEUZ, ROUX, tamir   |
|           25 |     4392 | 2024-01-24 | Rare Atom                   | L   | 0.517      | -            | -                | -                | -         |    -4.17 | fury5k, MagnumZ, NEUZ, ROUX, tamir   |
|           24 |     4400 | 2024-01-24 | SR Nacague                  | W   | 0.517      | 0.143        | 0.000 (0.000)    | 0.022 (0.002)    | 0 (0.000) |     4.29 | fury5k, MagnumZ, NEUZ, ROUX, tamir   |
|           23 |     4439 | 2024-01-23 | Steel Helmet                | L   | 0.510      | -            | -                | -                | -         |    -4.96 | fury5k, MagnumZ, NEUZ, ROUX, tamir   |
|           22 |     4446 | 2024-01-22 | Myth Avenue Gaming          | L   | 0.509      | -            | -                | -                | -         |    -5.06 | fury5k, MagnumZ, NEUZ, ROUX, tamir   |
|           21 |     4480 | 2024-01-22 | NewHappy                    | W   | 0.504      | 0.143        | 0.014 (0.001)    | 0.170 (0.012)    | 0 (0.000) |    11.94 | fury5k, MagnumZ, NEUZ, ROUX, tamir   |
|           20 |     4489 | 2024-01-22 | LYG Gaming                  | W   | 0.504      | 0.143        | 0.004 (0.000)    | 0.380 (0.027)    | 0 (0.000) |    12.15 | fury5k, MagnumZ, NEUZ, ROUX, tamir   |
|           19 |     4513 | 2024-01-21 | The Huns Esports            | L   | 0.496      | -            | -                | -                | -         |    -2.02 | fury5k, MagnumZ, NEUZ, ROUX, tamir   |
|           18 |     4568 | 2024-01-20 | MungYu Esports              | W   | 0.490      | 0.143        | 0.000 (0.000)    | 0.080 (0.006)    | 0 (0.000) |     7.52 | fury5k, MagnumZ, NEUZ, ROUX, tamir   |
|           17 |     4573 | 2024-01-20 | Fort Arena                  | W   | 0.489      | 0.143        | -                | 0.032 (0.002)    | 0 (0.000) |     6.55 | fury5k, MagnumZ, NEUZ, ROUX, tamir   |
|           16 |     4617 | 2024-01-19 | GR Gaming                   | L   | 0.483      | -            | -                | -                | -         |    -2.85 | fury5k, MagnumZ, NEUZ, ROUX, tamir   |
|           15 |     5379 | 2023-12-17 | The QUBE Esports            | L   | 0.264      | -            | -                | -                | -         |    -1.76 | fury5k, MagnumZ, NEUZ, ROUX, tamir   |
|           14 |     5592 | 2023-12-15 | MIRAI Gaming                | L   | 0.250      | -            | -                | -                | -         |    -2.42 | fury5k, MagnumZ, NEUZ, ROUX, tamir   |
|           13 |     5732 | 2023-12-10 | The QUBE Esports            | W   | 0.217      | 0.250        | 0.004 (0.000)    | 0.168 (0.009)    | 0 (0.000) |     5.45 | ariucle, fury5k, MagnumZ, NEUZ, ROUX |
|           12 |     5894 | 2023-12-07 | Hyper5                      | W   | 0.197      | 0.250        | 0.002 (0.000)    | 0.065 (0.003)    | 0 (0.000) |     4.29 | ariucle, fury5k, MagnumZ, NEUZ, ROUX |
|           11 |     6172 | 2023-12-01 | The Huns Esports            | L   | 0.156      | -            | -                | -                | -         |    -0.55 | ariucle, fury5k, MagnumZ, NEUZ, ROUX |
|           10 |     6221 | 2023-11-30 | Old School (Mongolian team) | W   | 0.150      | 0.143        | 0.000 (0.000)    | -                | 1 (0.150) |     2.12 | ariucle, fury5k, MagnumZ, NEUZ, ROUX |
|            9 |     6230 | 2023-11-29 | The Huns Esports            | L   | 0.149      | -            | -                | -                | -         |    -0.52 | ariucle, fury5k, MagnumZ, NEUZ, ROUX |
|            8 |     6333 | 2023-11-28 | Chinggis Warriors           | W   | 0.136      | -            | -                | -                | 0 (0.000) |     1.31 | ariucle, fury5k, MagnumZ, NEUZ, ROUX |
|            7 |     6336 | 2023-11-28 | ATOX Esports                | L   | 0.136      | -            | -                | -                | -         |    -0.19 | ariucle, fury5k, MagnumZ, NEUZ, ROUX |
|            6 |     6344 | 2023-11-27 | Angel Cops                  | W   | 0.135      | -            | -                | -                | -         |     1.30 | ariucle, fury5k, MagnumZ, NEUZ, ROUX |
|            5 |     6452 | 2023-11-25 | The Huns Esports            | L   | 0.116      | -            | -                | -                | -         |    -0.40 | ariucle, fury5k, MagnumZ, NEUZ, ROUX |
|            4 |     6457 | 2023-11-24 | ATOX Esports                | L   | 0.115      | -            | -                | -                | -         |    -0.16 | ariucle, fury5k, MagnumZ, NEUZ, ROUX |
|            3 |     6497 | 2023-11-24 | Clutch Gaming               | W   | 0.109      | 0.143        | 0.001 (0.000)    | 0.216 (0.003)    | -         |     2.55 | ariucle, fury5k, MagnumZ, NEUZ, ROUX |
|            2 |     6843 | 2023-11-16 | ATOX Esports                | L   | 0.057      | -            | -                | -                | -         |    -0.08 | ariucle, fury5k, MagnumZ, NEUZ, ROUX |
|            1 |     6849 | 2023-11-16 | MIRAI Gaming                | W   | 0.056      | 0.143        | 0.000 (0.000)    | 0.246 (0.002)    | -         |     1.26 | ariucle, fury5k, MagnumZ, NEUZ, ROUX |

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
