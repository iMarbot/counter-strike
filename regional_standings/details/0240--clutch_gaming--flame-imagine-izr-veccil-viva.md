### Roster Details<br />
Team Name: Clutch Gaming<br />
Roster: flame, IMAGINE, IZR, Veccil, viva<br />
Region: [Asia]( ../standings_asia.md)<br />
<br />
Global Rank: [240](../standings_global.md)<br />
Regional Rank: [32]( ../standings_asia.md)<br />
Final Rank Value:  694.4<br />
<br />
Final Rank Value (694.4) = Starting Rank Value (683.9) + Head To Head Adjustments (10.6)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.207[<sup>1</sup>](#table2)
- Bounty Collected: 0.277[<sup>2</sup>](#table1)
- Opponent Network: 0.075[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.140<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 683.9
- 400 + ( ( 0.140 - 0.000 ) / ( 0.787 - 0.000 ) ) * 1600 = 683.9


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent           | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           27 |      513 | 2024-05-22 | NewHappy           | L   | 1.000      | -            | -                | -                | -         |   -15.47 | flame, IMAGINE, IZR, Veccil, viva     |
|           26 |      519 | 2024-05-22 | NewHappy           | L   | 1.000      | -            | -                | -                | -         |   -16.89 | flame, IMAGINE, IZR, Veccil, viva     |
|           25 |      794 | 2024-05-19 | Gods Reign         | L   | 1.000      | -            | -                | -                | -         |   -11.38 | flame, IMAGINE, IZR, Veccil, viva     |
|           24 |      809 | 2024-05-19 | Gods Reign         | L   | 1.000      | -            | -                | -                | -         |   -12.37 | flame, IMAGINE, IZR, Veccil, viva     |
|           23 |     1100 | 2024-05-16 | TYLOO              | L   | 1.000      | -            | -                | -                | -         |    -7.25 | flame, IMAGINE, IZR, Veccil, viva     |
|           22 |     1108 | 2024-05-16 | TYLOO              | L   | 1.000      | -            | -                | -                | -         |    -7.73 | flame, IMAGINE, IZR, Veccil, viva     |
|           21 |     1185 | 2024-05-15 | ZEUSGG             | W   | 1.000      | 0.417        | 0.000 (0.000)    | 0.090 (0.038)    | 0 (0.000) |     7.45 | flame, IMAGINE, IZR, Veccil, viva     |
|           20 |     1198 | 2024-05-15 | ZEUSGG             | W   | 1.000      | 0.417        | -                | 0.090 (0.038)    | 0 (0.000) |     7.95 | flame, IMAGINE, IZR, Veccil, viva     |
|           19 |     2665 | 2024-04-20 | ATOX Esports       | L   | 0.936      | -            | -                | -                | -         |    -2.75 | flame, IMAGINE, IZR, Veccil, viva     |
|           18 |     2680 | 2024-04-20 | ATOX Esports       | L   | 0.936      | -            | -                | -                | -         |    -2.82 | flame, IMAGINE, IZR, Veccil, viva     |
|           17 |     3264 | 2024-04-10 | LYG Gaming         | W   | 0.869      | 0.417        | 0.001 (0.000)    | 0.275 (0.100)    | 0 (0.000) |    14.10 | flame, IMAGINE, IZR, Veccil, viva     |
|           16 |     3269 | 2024-04-10 | LYG Gaming         | W   | 0.869      | 0.417        | 0.001 (0.000)    | 0.275 (0.100)    | 0 (0.000) |    15.22 | flame, IMAGINE, IZR, Veccil, viva     |
|           15 |     3597 | 2024-04-04 | DEWA United        | L   | 0.829      | -            | -                | -                | -         |   -14.59 | flame, IMAGINE, IZR, Veccil, viva     |
|           14 |     3601 | 2024-04-04 | DEWA United        | W   | 0.829      | 0.417        | 0.002 (0.001)    | 0.176 (0.061)    | 0 (0.000) |    11.58 | flame, IMAGINE, IZR, Veccil, viva     |
|           13 |     3912 | 2024-03-27 | Lynn Vision Gaming | W   | 0.776      | 0.417        | 0.063 (0.020)    | 0.431 (0.140)    | 0 (0.000) |    22.19 | flame, IMAGINE, IZR, Veccil, viva     |
|           12 |     3915 | 2024-03-27 | Lynn Vision Gaming | L   | 0.776      | -            | -                | -                | -         |    -2.11 | flame, IMAGINE, IZR, Veccil, viva     |
|           11 |     3992 | 2024-03-26 | The QUBE Esports   | W   | 0.770      | 0.417        | -                | 0.138 (0.044)    | 0 (0.000) |    11.34 | flame, IMAGINE, IZR, Veccil, viva     |
|           10 |     3996 | 2024-03-26 | The QUBE Esports   | L   | 0.769      | -            | -                | -                | -         |   -13.15 | flame, IMAGINE, IZR, Veccil, viva     |
|            9 |     4616 | 2024-03-13 | GR Gaming          | L   | 0.683      | -            | -                | -                | -         |    -7.75 | flame, IMAGINE, IZR, Veccil, viva     |
|            8 |     4621 | 2024-03-13 | GR Gaming          | W   | 0.683      | 0.417        | 0.007 (0.002)    | 0.428 (0.122)    | 0 (0.000) |    14.13 | flame, IMAGINE, IZR, Veccil, viva     |
|            7 |     5021 | 2024-03-06 | MIRAI Gaming       | W   | 0.636      | 0.417        | 0.000 (0.000)    | 0.200 (0.053)    | 0 (0.000) |     9.46 | flame, IMAGINE, IZR, Veccil, viva     |
|            6 |     5028 | 2024-03-06 | MIRAI Gaming       | W   | 0.636      | 0.417        | 0.000 (0.000)    | 0.200 (0.053)    | 0 (0.000) |    10.00 | flame, IMAGINE, IZR, Veccil, viva     |
|            5 |     5942 | 2024-02-20 | -72C               | L   | 0.536      | -            | -                | -                | -         |    -7.03 | flame, IMAGINE, IZR, Veccil, viva     |
|            4 |     5950 | 2024-02-20 | -72C               | L   | 0.536      | -            | -                | -                | -         |    -7.37 | flame, IMAGINE, IZR, Veccil, viva     |
|            3 |     6347 | 2024-02-13 | Born In Far East   | W   | 0.490      | 0.417        | 0.001 (0.000)    | -                | -         |     7.88 | flame, IMAGINE, IZR, Veccil, viva     |
|            2 |     6351 | 2024-02-13 | Born In Far East   | W   | 0.489      | 0.417        | 0.001 (0.000)    | -                | -         |     8.23 | flame, IMAGINE, IZR, Veccil, viva     |
|            1 |     9595 | 2023-12-05 | LYG Gaming         | L   | 0.022      | -            | -                | -                | -         |    -0.31 | clouden, flame, hasteka, IMAGINE, IZR |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($44.67)
- Divide that value by the 5th highest value among all rosters ($300,806.11)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
