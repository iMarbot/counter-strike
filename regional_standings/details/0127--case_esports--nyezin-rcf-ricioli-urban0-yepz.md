### Roster Details<br />
Team Name: Case Esports<br />
Roster: nyezin, RCF, RICIOLI, urban0, yepz<br />
Region: [Americas]( ../standings_americas.md)<br />
<br />
Global Rank: [127](../standings_global.md)<br />
Regional Rank: [22]( ../standings_americas.md)<br />
Final Rank Value:  807.6<br />
<br />
Final Rank Value (807.6) = Starting Rank Value (829.5) + Head To Head Adjustments (-21.9)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.389[<sup>1</sup>](#table2)
- Bounty Collected: 0.358[<sup>2</sup>](#table1)
- Opponent Network: 0.119[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.216<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 829.5
- 400 + ( ( 0.216 - 0.000 ) / ( 0.806 - 0.000 ) ) * 1600 = 829.5


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent         | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                             |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           43 |        1 | 2024-05-05 | ODDIK            | L   | 1.000      | -            | -                | -                | -         |   -13.54 | nyezin, RCF, RICIOLI, urban0, yepz |
|           42 |      130 | 2024-05-02 | ODDIK            | W   | 1.000      | 0.450        | 0.015 (0.007)    | 0.402 (0.181)    | 0 (0.000) |    18.17 | nyezin, RCF, RICIOLI, urban0, yepz |
|           41 |      133 | 2024-05-02 | ODDIK            | L   | 1.000      | -            | -                | -                | -         |   -13.12 | nyezin, RCF, RICIOLI, urban0, yepz |
|           40 |      168 | 2024-05-01 | Dusty Roots      | W   | 1.000      | -            | -                | -                | 0 (0.000) |    10.00 | nyezin, RCF, RICIOLI, urban0, yepz |
|           39 |      174 | 2024-05-01 | 9z Team          | L   | 1.000      | -            | -                | -                | -         |    -6.85 | nyezin, RCF, RICIOLI, urban0, yepz |
|           38 |      179 | 2024-05-01 | 9z Team          | L   | 1.000      | -            | -                | -                | -         |    -7.28 | nyezin, RCF, RICIOLI, urban0, yepz |
|           37 |      920 | 2024-04-17 | MIBR             | L   | 1.000      | -            | -                | -                | -         |    -0.48 | RCF, RICIOLI, snow, urban0, yepz   |
|           36 |      993 | 2024-04-16 | Galorys          | W   | 1.000      | 0.143        | 0.048 (0.007)    | 0.598 (0.085)    | 0 (0.000) |    19.14 | RCF, RICIOLI, snow, urban0, yepz   |
|           35 |     1099 | 2024-04-13 | MIBR             | L   | 1.000      | -            | -                | -                | -         |    -0.47 | RCF, RICIOLI, snow, urban0, yepz   |
|           34 |     1182 | 2024-04-11 | FURIA Academy    | W   | 1.000      | 0.435        | -                | 0.189 (0.082)    | 0 (0.000) |     8.91 | RCF, RICIOLI, snow, urban0, yepz   |
|           33 |     2134 | 2024-03-17 | ODDIK            | L   | 0.872      | -            | -                | -                | -         |    -9.54 | RCF, RICIOLI, snow, urban0, yepz   |
|           32 |     2166 | 2024-03-16 | MIBR Academy     | W   | 0.865      | 0.303        | 0.011 (0.003)    | 0.455 (0.119)    | 0 (0.000) |    11.71 | RCF, RICIOLI, snow, urban0, yepz   |
|           31 |     2203 | 2024-03-15 | RED Canids       | L   | 0.859      | -            | -                | -                | -         |    -7.55 | RCF, RICIOLI, snow, urban0, yepz   |
|           30 |     2266 | 2024-03-14 | FURIA Academy    | W   | 0.852      | -            | -                | -                | 0 (0.000) |     6.33 | RCF, RICIOLI, snow, urban0, yepz   |
|           29 |     2300 | 2024-03-13 | RED Canids       | L   | 0.846      | -            | -                | -                | -         |    -7.21 | RCF, RICIOLI, snow, urban0, yepz   |
|           28 |     2306 | 2024-03-13 | Yawara E-Sports  | L   | 0.846      | -            | -                | -                | -         |   -17.25 | RCF, RICIOLI, snow, urban0, yepz   |
|           27 |     2324 | 2024-03-13 | ODDIK            | L   | 0.845      | -            | -                | -                | -         |   -10.16 | RCF, RICIOLI, snow, urban0, yepz   |
|           26 |     2378 | 2024-03-12 | LA RUGONETA      | W   | 0.837      | -            | -                | -                | 0 (0.000) |     5.97 | RCF, RICIOLI, snow, urban0, yepz   |
|           25 |     2445 | 2024-03-10 | FURIA Academy    | W   | 0.826      | -            | -                | -                | 0 (0.000) |     5.31 | RCF, RICIOLI, snow, urban0, yepz   |
|           24 |     2478 | 2024-03-09 | Sharks Esports   | W   | 0.819      | 0.435        | 0.063 (0.022)    | 0.343 (0.122)    | 0 (0.000) |    17.49 | RCF, RICIOLI, snow, urban0, yepz   |
|           23 |     2557 | 2024-03-07 | Fluxo            | W   | 0.806      | 0.435        | 0.153 (0.053)    | 0.484 (0.169)    | 0 (0.000) |    19.71 | RCF, RICIOLI, snow, urban0, yepz   |
|           22 |     2667 | 2024-03-05 | AdalYamigos      | L   | 0.794      | -            | -                | -                | -         |   -11.14 | RCF, RICIOLI, snow, urban0, yepz   |
|           21 |     2669 | 2024-03-05 | AdalYamigos      | L   | 0.793      | -            | -                | -                | -         |   -11.95 | RCF, RICIOLI, snow, urban0, yepz   |
|           20 |     2716 | 2024-03-04 | Fluxo            | L   | 0.787      | -            | -                | -                | -         |    -5.56 | RCF, RICIOLI, snow, urban0, yepz   |
|           19 |     2717 | 2024-03-04 | Fluxo            | L   | 0.787      | -            | -                | -                | -         |    -5.84 | RCF, RICIOLI, snow, urban0, yepz   |
|           18 |     3119 | 2024-02-24 | 2Game Esports    | W   | 0.727      | -            | -                | -                | -         |     5.38 | RCF, RICIOLI, snow, urban0, yepz   |
|           17 |     3126 | 2024-02-24 | 2Game Esports    | L   | 0.727      | -            | -                | -                | -         |   -17.93 | RCF, RICIOLI, snow, urban0, yepz   |
|           16 |     3271 | 2024-02-21 | Team Solid       | W   | 0.707      | 0.450        | 0.138 (0.044)    | 0.275 (0.088)    | -         |    11.72 | RCF, RICIOLI, snow, urban0, yepz   |
|           15 |     3278 | 2024-02-21 | Team Solid       | L   | 0.707      | -            | -                | -                | -         |   -10.73 | RCF, RICIOLI, snow, urban0, yepz   |
|           14 |     3285 | 2024-02-21 | Sharks Esports   | L   | 0.706      | -            | -                | -                | -         |    -8.79 | RCF, RICIOLI, snow, urban0, yepz   |
|           13 |     3336 | 2024-02-20 | 9z Team          | L   | 0.700      | -            | -                | -                | -         |    -6.90 | RCF, RICIOLI, snow, urban0, yepz   |
|           12 |     3356 | 2024-02-20 | Sharks Esports   | L   | 0.698      | -            | -                | -                | -         |    -9.13 | RCF, RICIOLI, snow, urban0, yepz   |
|           11 |     3389 | 2024-02-19 | LA RUGONETA      | W   | 0.694      | -            | -                | -                | -         |     4.15 | RCF, RICIOLI, snow, urban0, yepz   |
|           10 |     3438 | 2024-02-18 | Galorys          | L   | 0.686      | -            | -                | -                | -         |   -10.55 | RCF, RICIOLI, snow, urban0, yepz   |
|            9 |     3518 | 2024-02-16 | BESTIA           | W   | 0.673      | 0.435        | 0.026 (0.008)    | 0.423 (0.124)    | -         |    10.31 | RCF, RICIOLI, snow, urban0, yepz   |
|            8 |     3564 | 2024-02-15 | 9z Team          | L   | 0.666      | -            | -                | -                | -         |    -6.43 | RCF, RICIOLI, snow, urban0, yepz   |
|            7 |     3566 | 2024-02-15 | Sharks Esports   | W   | 0.666      | 0.143        | 0.063 (0.006)    | -                | -         |    12.09 | RCF, RICIOLI, snow, urban0, yepz   |
|            6 |     3589 | 2024-02-15 | Flamengo Esports | W   | 0.665      | -            | -                | -                | -         |     3.54 | RCF, RICIOLI, snow, urban0, yepz   |
|            5 |     3610 | 2024-02-14 | O PLANO C        | W   | 0.660      | -            | -                | -                | -         |     1.63 | RCF, RICIOLI, snow, urban0, yepz   |
|            4 |     3661 | 2024-02-13 | W7m esports      | W   | 0.654      | -            | -                | -                | -         |     4.75 | RCF, RICIOLI, snow, urban0, yepz   |
|            3 |     3664 | 2024-02-13 | W7m esports      | L   | 0.653      | -            | -                | -                | -         |   -16.20 | RCF, RICIOLI, snow, urban0, yepz   |
|            2 |     3671 | 2024-02-13 | Galorys          | W   | 0.652      | 0.303        | 0.048 (0.010)    | 0.598 (0.118)    | -         |    10.45 | RCF, RICIOLI, snow, urban0, yepz   |
|            1 |     3718 | 2024-02-12 | Dusty Roots      | W   | 0.645      | 0.435        | 0.005 (0.002)    | 0.352 (0.099)    | -         |     5.95 | RCF, RICIOLI, snow, urban0, yepz   |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($4,262.27)
- Divide that value by the 5th highest value among all rosters ($158,437.64)
- The final value (0.03) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
