### Roster Details<br />
Team Name: Mythic<br />
Roster: Cooper, fl0m, freakazoid, hate, Trucklover86<br />
Region: [Americas]( ../standings_americas.md)<br />
<br />
Global Rank: [227](../standings_global.md)<br />
Regional Rank: [41]( ../standings_americas.md)<br />
Final Rank Value:  686.4<br />
<br />
Final Rank Value (686.4) = Starting Rank Value (722.6) + Head To Head Adjustments (-36.2)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.281[<sup>1</sup>](#table2)
- Bounty Collected: 0.297[<sup>2</sup>](#table1)
- Opponent Network: 0.072[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.163<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 722.6
- 400 + ( ( 0.163 - 0.000 ) / ( 0.806 - 0.000 ) ) * 1600 = 722.6


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent                   | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins      | H2H Adj. | Roster                                           |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           35 |      497 | 2024-04-24 | BOSS                       | W   | 1.000      | 0.477        | 0.051 (0.024)    | 0.293 (0.140)    | false (0.000) |    24.50 | Cooper, fl0m, freakazoid, hate, Trucklover86     |
|           34 |      498 | 2024-04-24 | BOSS                       | L   | 1.000      | -            | -                | -                | -             |    -6.49 | Cooper, fl0m, freakazoid, hate, Trucklover86     |
|           33 |     1028 | 2024-04-15 | NRG                        | L   | 1.000      | -            | -                | -                | -             |   -12.42 | Cooper, fl0m, freakazoid, hate, Trucklover86     |
|           32 |     1029 | 2024-04-15 | NRG                        | L   | 1.000      | -            | -                | -                | -             |   -13.53 | Cooper, fl0m, freakazoid, hate, Trucklover86     |
|           31 |     1158 | 2024-04-11 | Carpe Diem                 | L   | 1.000      | -            | -                | -                | -             |   -19.02 | Cooper, fl0m, freakazoid, hate, Trucklover86     |
|           30 |     1161 | 2024-04-11 | Carpe Diem                 | W   | 1.000      | 0.477        | 0.009 (0.004)    | 0.178 (0.085)    | false (0.000) |    12.20 | Cooper, fl0m, freakazoid, hate, Trucklover86     |
|           29 |     1195 | 2024-04-10 | LAG Gaming (American team) | L   | 1.000      | -            | -                | -                | -             |    -9.13 | Cooper, fl0m, freakazoid, hate, Trucklover86     |
|           28 |     1199 | 2024-04-10 | LAG Gaming (American team) | L   | 1.000      | -            | -                | -                | -             |    -9.84 | Cooper, fl0m, freakazoid, hate, Trucklover86     |
|           27 |     1716 | 2024-03-27 | Wildcard Gaming            | L   | 0.941      | -            | -                | -                | -             |    -7.72 | Cooper, fl0m, freakazoid, hate, Trucklover86     |
|           26 |     1720 | 2024-03-27 | Wildcard Gaming            | L   | 0.940      | -            | -                | -                | -             |    -8.24 | Cooper, fl0m, freakazoid, hate, Trucklover86     |
|           25 |     1780 | 2024-03-26 | Limitless                  | W   | 0.934      | 0.477        | 0.001 (0.001)    | 0.177 (0.079)    | false (0.000) |    12.15 | Cooper, fl0m, freakazoid, hate, Trucklover86     |
|           24 |     1784 | 2024-03-26 | Limitless                  | L   | 0.934      | -            | -                | -                | -             |   -17.57 | Cooper, fl0m, freakazoid, hate, Trucklover86     |
|           23 |     2000 | 2024-03-20 | Nouns Esports              | W   | 0.894      | 0.477        | 0.000 (0.000)    | 0.475 (0.202)    | false (0.000) |    13.79 | Cooper, fl0m, freakazoid, hate, Trucklover86     |
|           22 |     2005 | 2024-03-20 | Nouns Esports              | L   | 0.894      | -            | -                | -                | -             |   -14.52 | Cooper, fl0m, freakazoid, hate, Trucklover86     |
|           21 |     2239 | 2024-03-14 | One More Esports           | W   | 0.854      | 0.477        | 0.011 (0.004)    | 0.147 (0.060)    | false (0.000) |    11.46 | Cooper, fl0m, freakazoid, hate, Trucklover86     |
|           20 |     2241 | 2024-03-14 | One More Esports           | W   | 0.854      | 0.477        | 0.011 (0.004)    | 0.147 (0.060)    | false (0.000) |    12.34 | Cooper, fl0m, freakazoid, hate, Trucklover86     |
|           19 |     2295 | 2024-03-13 | Take Flyte                 | L   | 0.846      | -            | -                | -                | -             |   -13.88 | Cooper, fl0m, freakazoid, hate, Trucklover86     |
|           18 |     2351 | 2024-03-12 | Wildcard Gaming            | W   | 0.840      | 0.143        | 0.025 (0.003)    | 0.483 (0.058)    | false (0.000) |    19.63 | Cooper, fl0m, freakazoid, hate, Trucklover86     |
|           17 |     2354 | 2024-03-12 | Bad News Bears             | W   | 0.840      | -            | -                | -                | false (0.000) |     3.93 | Cooper, fl0m, freakazoid, hate, Trucklover86     |
|           16 |     2661 | 2024-03-05 | MIGHT                      | L   | 0.794      | -            | -                | -                | -             |   -10.94 | Cooper, fl0m, freakazoid, hate, Trucklover86     |
|           15 |     2664 | 2024-03-05 | MIGHT                      | L   | 0.794      | -            | -                | -                | -             |   -11.73 | Cooper, fl0m, freakazoid, hate, Trucklover86     |
|           14 |     3189 | 2024-02-23 | Timbermen Black            | W   | 0.721      | -            | -                | -                | false (0.000) |     3.08 | Cooper, fl0m, freakazoid, hate, Trucklover86     |
|           13 |     3334 | 2024-02-20 | Party Astronauts           | L   | 0.700      | -            | -                | -                | -             |    -8.61 | Cooper, fl0m, freakazoid, hate, Trucklover86     |
|           12 |     3386 | 2024-02-19 | G3 (Asian team)            | W   | 0.694      | 0.143        | 0.014 (0.001)    | 0.173 (0.017)    | false (0.000) |    11.64 | Cooper, fl0m, freakazoid, hate, Trucklover86     |
|           11 |     3513 | 2024-02-16 | FLUFFY AIMERS              | W   | 0.674      | 0.143        | 0.004 (0.000)    | 0.103 (0.010)    | -             |     9.92 | Cooper, fl0m, freakazoid, hate, Trucklover86     |
|           10 |     3517 | 2024-02-16 | E-Xolos LAZER              | W   | 0.673      | -            | -                | -                | -             |     3.32 | Cooper, fl0m, freakazoid, hate, Trucklover86     |
|            9 |     3559 | 2024-02-15 | Pryde                      | W   | 0.667      | -            | -                | -                | -             |     3.23 | Cooper, fl0m, freakazoid, hate, Trucklover86     |
|            8 |     4415 | 2024-01-23 | Team Lampa                 | W   | 0.514      | -            | -                | -                | -             |     3.97 | Cooper, fl0m, freakazoid, hate, Trucklover86     |
|            7 |     4420 | 2024-01-23 | Legacy (American team)     | W   | 0.514      | -            | -                | -                | -             |     2.46 | Cooper, fl0m, freakazoid, hate, Trucklover86     |
|            6 |     4685 | 2024-01-17 | Wildcard Gaming            | L   | 0.474      | -            | -                | -                | -             |    -4.26 | Cooper, fl0m, freakazoid, hate, Trucklover86     |
|            5 |     4823 | 2024-01-15 | Elevate                    | L   | 0.461      | -            | -                | -                | -             |    -5.43 | Cooper, fl0m, freakazoid, hate, Trucklover86     |
|            4 |     5018 | 2024-01-10 | FN Esports                 | L   | 0.428      | -            | -                | -                | -             |    -8.51 | Cooper, fl0m, freakazoid, hate, Trucklover86     |
|            3 |     5960 | 2023-12-05 | Elevate                    | L   | 0.187      | -            | -                | -                | -             |    -2.43 | Cooper, fl0m, freakazoid, Stewie2K, Trucklover86 |
|            2 |     6540 | 2023-11-22 | Carpe Diem                 | W   | 0.101      | 0.500        | 0.009 (0.000)    | 0.178 (0.009)    | -             |     1.61 | Cooper, fl0m, freakazoid, Stewie2K, Trucklover86 |
|            1 |     6577 | 2023-11-21 | Party Astronauts           | L   | 0.094      | -            | -                | -                | -             |    -1.15 | Cooper, fl0m, freakazoid, Stewie2K, Trucklover86 |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($441.02)
- Divide that value by the 5th highest value among all rosters ($158,437.64)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
