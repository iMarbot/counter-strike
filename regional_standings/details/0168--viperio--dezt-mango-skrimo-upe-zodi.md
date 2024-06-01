### Roster Details<br />
Team Name: Viperio<br />
Roster: dezt, mAnGo, Skrimo, upE, zodi<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [168](../standings_global.md)<br />
Regional Rank: [115]( ../standings_europe.md)<br />
Final Rank Value:  761.5<br />
<br />
Final Rank Value (761.5) = Starting Rank Value (723.3) + Head To Head Adjustments (38.2)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.285[<sup>1</sup>](#table2)
- Bounty Collected: 0.256[<sup>2</sup>](#table1)
- Opponent Network: 0.094[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.159<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 723.3
- 400 + ( ( 0.159 - 0.000 ) / ( 0.786 - 0.000 ) ) * 1600 = 723.3


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent                  | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                               |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           24 |      862 | 2024-05-18 | Endpoint                  | L   | 1.000      | -            | -                | -                | -         |    -9.94 | dezt, mAnGo, Skrimo, upE, zodi       |
|           23 |      878 | 2024-05-18 | Raptors Esports Club      | W   | 1.000      | 0.143        | 0.007 (0.001)    | 0.406 (0.058)    | 0 (0.000) |    18.41 | dezt, mAnGo, Skrimo, upE, zodi       |
|           22 |     1187 | 2024-05-15 | Tropic                    | L   | 1.000      | -            | -                | -                | -         |   -24.79 | dezt, mAnGo, Skrimo, upE, zodi       |
|           21 |     1473 | 2024-05-11 | Team Space                | L   | 1.000      | -            | -                | -                | -         |   -14.20 | dezt, mAnGo, Skrimo, upE, zodi       |
|           20 |     1572 | 2024-05-09 | DMS                       | W   | 1.000      | 0.143        | 0.000 (0.000)    | 0.751 (0.107)    | 0 (0.000) |    18.94 | dezt, mAnGo, Skrimo, upE, zodi       |
|           19 |     1579 | 2024-05-09 | Johnny Speeds             | L   | 1.000      | -            | -                | -                | -         |    -6.71 | dezt, mAnGo, Skrimo, upE, zodi       |
|           18 |     1655 | 2024-05-08 | MASONIC                   | W   | 1.000      | 0.143        | 0.018 (0.003)    | -                | 0 (0.000) |    19.81 | dezt, mAnGo, Skrimo, upE, zodi       |
|           17 |     1693 | 2024-05-07 | NOM Esports               | W   | 1.000      | 0.333        | -                | 0.360 (0.120)    | 0 (0.000) |    13.55 | dezt, mAnGo, Skrimo, upE, zodi       |
|           16 |     1699 | 2024-05-07 | Preasy Esport             | L   | 1.000      | -            | -                | -                | -         |   -14.83 | dezt, mAnGo, Skrimo, upE, zodi       |
|           15 |     1739 | 2024-05-06 | Dynamo Eclot              | L   | 1.000      | -            | -                | -                | -         |    -7.03 | dezt, mAnGo, Skrimo, upE, zodi       |
|           14 |     2200 | 2024-04-27 | V1dar Gaming              | L   | 0.982      | -            | -                | -                | -         |   -17.62 | dezt, mAnGo, Skrimo, upE, zodi       |
|           13 |     2406 | 2024-04-23 | GamerLegion Academy       | W   | 0.957      | 0.143        | 0.018 (0.002)    | 0.691 (0.095)    | 0 (0.000) |    17.27 | dezt, mAnGo, Skrimo, upE, zodi       |
|           12 |     2458 | 2024-04-22 | LEON Esports              | W   | 0.950      | 0.143        | 0.001 (0.000)    | 0.564 (0.076)    | 0 (0.000) |    13.30 | dezt, mAnGo, Skrimo, upE, zodi       |
|           11 |     2638 | 2024-04-20 | Illuminar Gaming          | L   | 0.935      | -            | -                | -                | -         |   -11.91 | dezt, mAnGo, Skrimo, upE, zodi       |
|           10 |     2732 | 2024-04-19 | ENCE Academy              | W   | 0.928      | 0.143        | 0.012 (0.002)    | 0.337 (0.045)    | 0 (0.000) |    17.25 | mAnGo, pandi7o, Skrimo, upE, zodi    |
|            9 |     2881 | 2024-04-17 | UNiTY esports             | L   | 0.914      | -            | -                | -                | -         |    -8.74 | mAnGo, pandi7o, ReegaN, Skrimo, zodi |
|            8 |     2923 | 2024-04-16 | Johnny Speeds             | L   | 0.909      | -            | -                | -                | -         |    -5.38 | mAnGo, pandi7o, ReegaN, Skrimo, zodi |
|            7 |     2930 | 2024-04-16 | Lazer Cats                | W   | 0.908      | 0.143        | 0.003 (0.000)    | -                | 0 (0.000) |    12.17 | dezt, mAnGo, pandi7o, Skrimo, zodi   |
|            6 |     2962 | 2024-04-15 | ENCE Academy              | L   | 0.902      | -            | -                | -                | -         |   -11.87 | dezt, mAnGo, pandi7o, Skrimo, zodi   |
|            5 |     2995 | 2024-04-14 | Illuminar Gaming          | W   | 0.894      | 0.333        | 0.004 (0.001)    | 0.403 (0.120)    | 0 (0.000) |    16.81 | mAnGo, pandi7o, Skrimo, upE, zodi    |
|            4 |     3133 | 2024-04-11 | ex-K10                    | W   | 0.875      | 0.333        | 0.005 (0.002)    | 0.382 (0.112)    | 0 (0.000) |    16.94 | mAnGo, pandi7o, Skrimo, upE, zodi    |
|            3 |     3210 | 2024-04-10 | NOM Esports               | W   | 0.868      | 0.333        | -                | 0.360 (0.104)    | -         |    10.96 | mAnGo, ReegaN, Skrimo, upE, zodi     |
|            2 |     3353 | 2024-04-07 | ex-Turów Zgorzelec Esport | W   | 0.849      | 0.333        | 0.006 (0.002)    | 0.375 (0.106)    | -         |    15.43 | mAnGo, pandi7o, ReegaN, Skrimo, zodi |
|            1 |     3568 | 2024-04-03 | NOM Esports               | L   | 0.822      | -            | -                | -                | -         |   -19.70 | mAnGo, pandi7o, ReegaN, upE, zodi    |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($921.67)
- Divide that value by the 5th highest value among all rosters ($300,806.11)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
