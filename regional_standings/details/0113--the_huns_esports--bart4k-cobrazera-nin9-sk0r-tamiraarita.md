### Roster Details<br />
Team Name: The Huns Esports<br />
Roster: Bart4k, cobrazera, nin9, sk0R, Tamiraarita<br />
Region: [Asia]( ../standings_asia.md)<br />
<br />
Global Rank: [113](../standings_global.md)<br />
Regional Rank: [12]( ../standings_asia.md)<br />
Final Rank Value:  847.3<br />
<br />
Final Rank Value (847.3) = Starting Rank Value (890.9) + Head To Head Adjustments (-43.6)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.217[<sup>1</sup>](#table2)
- Bounty Collected: 0.237[<sup>2</sup>](#table1)
- Opponent Network: 0.015[<sup>2</sup>](#table1)
- LAN Wins: 0.495[<sup>2</sup>](#table1)

The average of these factors is 0.241<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 890.9
- 400 + ( ( 0.241 - 0.000 ) / ( 0.786 - 0.000 ) ) * 1600 = 890.9


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent         | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                     |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           39 |     1014 | 2024-05-17 | ATOX Esports     | L   | 1.000      | -            | -                | -                | -         |    -5.55 | Bart4k, cobrazera, nin9, sk0R, Tamiraarita |
|           38 |     1100 | 2024-05-16 | IHC Esports      | W   | 1.000      | 0.143        | 0.004 (0.001)    | 0.077 (0.011)    | 1 (1.000) |    12.32 | Bart4k, cobrazera, nin9, sk0R, Tamiraarita |
|           37 |     1109 | 2024-05-15 | The MongolZ      | L   | 1.000      | -            | -                | -                | -         |    -0.53 | Bart4k, cobrazera, nin9, sk0R, Tamiraarita |
|           36 |     1898 | 2024-05-02 | IHC Esports      | L   | 1.000      | -            | -                | -                | -         |   -18.85 | Bart4k, cobrazera, nin9, sk0R, Tamiraarita |
|           35 |     1933 | 2024-05-02 | Eruption         | W   | 1.000      | -            | -                | -                | 1 (1.000) |     3.14 | Bart4k, cobrazera, nin9, sk0R, Tamiraarita |
|           34 |     1940 | 2024-05-01 | FAD3D Gaming     | W   | 1.000      | -            | -                | -                | 1 (1.000) |     2.12 | Bart4k, cobrazera, nin9, sk0R, Tamiraarita |
|           33 |     2862 | 2024-04-17 | TYLOO            | L   | 0.915      | -            | -                | -                | -         |   -12.32 | Bart4k, cobrazera, H4wK, ncl, nin9         |
|           32 |     3301 | 2024-04-08 | IHC Esports      | L   | 0.856      | -            | -                | -                | -         |   -16.29 | Bart4k, cobrazera, H4wK, nin9, sk0R        |
|           31 |     3357 | 2024-04-07 | The QUBE Esports | W   | 0.848      | -            | -                | -                | 1 (0.848) |     2.11 | Bart4k, cobrazera, H4wK, nin9, sk0R        |
|           30 |     3360 | 2024-04-06 | ATOX Esports     | L   | 0.847      | -            | -                | -                | -         |    -4.51 | Bart4k, cobrazera, H4wK, nin9, sk0R        |
|           29 |     3448 | 2024-04-05 | KnowHow          | W   | 0.836      | -            | -                | -                | 1 (0.836) |     1.74 | Bart4k, cobrazera, H4wK, nin9, sk0R        |
|           28 |     4179 | 2024-03-19 | TyPuCTbl         | W   | 0.723      | 0.250        | -                | 0.106 (0.019)    | 0 (0.000) |     4.72 | Bart4k, ncl, nin9, sk0R, Tsogoo            |
|           27 |     4386 | 2024-03-15 | Team NKT         | W   | 0.696      | 0.250        | 0.006 (0.001)    | 0.150 (0.026)    | 0 (0.000) |     7.08 | Bart4k, ncl, nin9, sk0R, Tsogoo            |
|           26 |     4515 | 2024-03-13 | LYG Gaming       | L   | 0.682      | -            | -                | -                | -         |   -15.61 | Bart4k, ncl, nin9, sk0R, tsogoo            |
|           25 |     4564 | 2024-03-12 | KalekiXer        | W   | 0.676      | -            | -                | -                | 0 (0.000) |     1.31 | Bart4k, ncl, nin9, sk0R, tsogoo            |
|           24 |     4896 | 2024-03-06 | Gotham Mafia     | W   | 0.636      | -            | -                | -                | 0 (0.000) |     1.24 | Bart4k, ncl, nin9, sk0R, Tsogoo            |
|           23 |     6065 | 2024-02-15 | GR Gaming        | L   | 0.502      | -            | -                | -                | -         |    -9.78 | Bart4k, nin9, sk0R, Tsogoo, yAmi           |
|           22 |     6113 | 2024-02-14 | TyPuCTbl         | W   | 0.496      | 0.143        | -                | 0.106 (0.008)    | 0 (0.000) |     2.73 | Bart4k, nin9, sk0R, Tsogoo, yAmi           |
|           21 |     6117 | 2024-02-14 | The QUBE Esports | W   | 0.496      | 0.143        | 0.001 (0.000)    | 0.120 (0.009)    | -         |     4.97 | Bart4k, nin9, sk0R, Tsogoo, yAmi           |
|           20 |     6995 | 2024-01-27 | TYLOO            | L   | 0.375      | -            | -                | -                | -         |    -6.97 | Bart4k, nin9, sk0R, tsogoo, yAmi           |
|           19 |     7054 | 2024-01-26 | Wings Up Gaming  | W   | 0.370      | 0.143        | 0.006 (0.000)    | -                | -         |     3.10 | Bart4k, nin9, sk0R, tsogoo, yAmi           |
|           18 |     7060 | 2024-01-26 | The MongolZ      | L   | 0.368      | -            | -                | -                | -         |    -0.21 | Bart4k, nin9, sk0R, tsogoo, yAmi           |
|           17 |     7097 | 2024-01-24 | Team NKT         | L   | 0.361      | -            | -                | -                | -         |    -8.24 | Bart4k, nin9, sk0R, tsogoo, yAmi           |
|           16 |     7098 | 2024-01-24 | Eruption         | W   | 0.361      | -            | -                | -                | -         |     1.84 | Bart4k, nin9, sk0R, tsogoo, yAmi           |
|           15 |     7187 | 2024-01-23 | Steel Helmet     | W   | 0.349      | 0.143        | 0.012 (0.001)    | -                | -         |     2.71 | Bart4k, nin9, sk0R, tsogoo, yAmi           |
|           14 |     7190 | 2024-01-23 | ATOX Esports     | W   | 0.349      | 0.143        | 0.047 (0.002)    | 0.601 (0.030)    | -         |     9.47 | Bart4k, nin9, sk0R, tsogoo, yAmi           |
|           13 |     7238 | 2024-01-22 | Wings Up Gaming  | W   | 0.343      | 0.143        | 0.006 (0.000)    | -                | -         |     2.76 | Bart4k, nin9, sk0R, tsogoo, yAmi           |
|           12 |     7247 | 2024-01-22 | Secret           | W   | 0.343      | -            | -                | -                | -         |     0.69 | Bart4k, nin9, sk0R, tsogoo, yAmi           |
|           11 |     7283 | 2024-01-21 | ATOX Esports     | L   | 0.336      | -            | -                | -                | -         |    -1.44 | Bart4k, nin9, sk0R, tsogoo, yAmi           |
|           10 |     7287 | 2024-01-21 | Eruption         | W   | 0.335      | -            | -                | -                | -         |     1.83 | Bart4k, nin9, sk0R, tsogoo, yAmi           |
|            9 |     7354 | 2024-01-20 | GR Gaming        | W   | 0.329      | 0.143        | 0.007 (0.000)    | 0.428 (0.020)    | -         |     3.81 | Bart4k, nin9, sk0R, tsogoo, yAmi           |
|            8 |     7367 | 2024-01-20 | Team NKT         | W   | 0.328      | 0.143        | 0.006 (0.000)    | 0.150 (0.007)    | -         |     3.07 | Bart4k, nin9, sk0R, tsogoo, yAmi           |
|            7 |     7423 | 2024-01-19 | MungYu Esports   | L   | 0.322      | -            | -                | -                | -         |    -8.96 | Bart4k, nin9, sk0R, tsogoo, yAmi           |
|            6 |     7707 | 2024-01-15 | MungYu Esports   | L   | 0.296      | -            | -                | -                | -         |    -8.35 | Bart4k, nin9, sk0R, tsogoo, yAmi           |
|            5 |     7710 | 2024-01-15 | Fort Arena       | W   | 0.296      | -            | -                | -                | -         |     0.90 | Bart4k, nin9, sk0R, tsogoo, yAmi           |
|            4 |     7716 | 2024-01-15 | Team NKT         | W   | 0.295      | 0.143        | 0.006 (0.000)    | 0.150 (0.006)    | -         |     2.63 | Bart4k, nin9, sk0R, tsogoo, yAmi           |
|            3 |     7722 | 2024-01-15 | LYG Gaming       | W   | 0.295      | 0.143        | -                | 0.275 (0.012)    | -         |     2.74 | Bart4k, nin9, sk0R, tsogoo, yAmi           |
|            2 |     8295 | 2024-01-01 | Wings Up Gaming  | L   | 0.208      | -            | -                | -                | -         |    -5.04 | Bart4k, nin9, sk0R, Tsogoo, yAmi           |
|            1 |     9510 | 2023-12-02 | ATOX Esports     | L   | 0.002      | -            | -                | -                | -         |    -0.01 | Bart4k, ncl, nin9, sk0R, yAmi              |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($74.88)
- Divide that value by the 5th highest value among all rosters ($300,806.11)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-03-19 |      0.723 | $100.00        | $72.26          |
| 2023-12-02 |      0.002 | $1,448.41      | $2.62           |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
