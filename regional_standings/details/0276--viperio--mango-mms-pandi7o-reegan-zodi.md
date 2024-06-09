### Roster Details<br />
Team Name: Viperio<br />
Roster: mAnGo, MMS, pandi7o, ReegaN, zodi<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [276](../standings_global.md)<br />
Regional Rank: [178]( ../standings_europe.md)<br />
Final Rank Value:  662.1<br />
<br />
Final Rank Value (662.1) = Starting Rank Value (591.6) + Head To Head Adjustments (70.6)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.000[<sup>1</sup>](#table2)
- Bounty Collected: 0.293[<sup>2</sup>](#table1)
- Opponent Network: 0.084[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.094<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 591.6
- 400 + ( ( 0.094 - 0.000 ) / ( 0.787 - 0.000 ) ) * 1600 = 591.6


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent                  | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                            |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           51 |     4144 | 2024-03-22 | Sashi Esport              | L   | 0.742      | -            | -                | -                | -         |    -2.42 | mAnGo, MMS, pandi7o, ReegaN, zodi |
|           50 |     4146 | 2024-03-22 | Astralis Talent           | L   | 0.742      | -            | -                | -                | -         |    -4.93 | mAnGo, MMS, pandi7o, ReegaN, zodi |
|           49 |     4287 | 2024-03-19 | GamerLegion Academy       | L   | 0.722      | -            | -                | -                | -         |    -7.10 | mAnGo, MMS, pandi7o, ReegaN, zodi |
|           48 |     4349 | 2024-03-17 | ex-Turów Zgorzelec Esport | L   | 0.711      | -            | -                | -                | -         |    -8.45 | mAnGo, MMS, pandi7o, ReegaN, zodi |
|           47 |     4475 | 2024-03-15 | LEON Esports              | L   | 0.698      | -            | -                | -                | -         |    -9.06 | mAnGo, MMS, pandi7o, ReegaN, zodi |
|           46 |     4503 | 2024-03-15 | Astralis Talent           | W   | 0.695      | 0.333        | 0.012 (0.003)    | 0.452 (0.105)    | 0 (0.000) |    16.89 | mAnGo, MMS, pandi7o, ReegaN, zodi |
|           45 |     4713 | 2024-03-11 | Preasy Esport             | W   | 0.671      | 0.333        | 0.008 (0.002)    | 0.705 (0.158)    | 0 (0.000) |    14.49 | mAnGo, MMS, pandi7o, ReegaN, zodi |
|           44 |     4920 | 2024-03-07 | Phantom Troupe            | W   | 0.645      | -            | -                | -                | 0 (0.000) |     6.83 | mAnGo, MMS, pandi7o, ReegaN, zodi |
|           43 |     5125 | 2024-03-05 | Alliance                  | L   | 0.628      | -            | -                | -                | -         |    -5.32 | mAnGo, MMS, pandi7o, ReegaN, zodi |
|           42 |     5214 | 2024-03-03 | MOUZ NXT                  | L   | 0.618      | -            | -                | -                | -         |    -1.47 | mAnGo, MMS, pandi7o, ReegaN, zodi |
|           41 |     5234 | 2024-03-03 | The Neighbours            | L   | 0.617      | -            | -                | -                | -         |    -9.86 | cryths, mAnGo, MMS, ReegaN, zodi  |
|           40 |     5394 | 2024-03-01 | Dynamo Eclot              | L   | 0.602      | -            | -                | -                | -         |    -1.49 | mAnGo, MMS, pandi7o, ReegaN, zodi |
|           39 |     5397 | 2024-02-29 | Verdant                   | L   | 0.598      | -            | -                | -                | -         |    -3.86 | cryths, mAnGo, MMS, ReegaN, zodi  |
|           38 |     5398 | 2024-02-29 | Dreams To Legends         | W   | 0.598      | -            | -                | -                | 0 (0.000) |     4.78 | cryths, mAnGo, MMS, ReegaN, zodi  |
|           37 |     5441 | 2024-02-29 | brazylijski luz           | W   | 0.596      | 0.303        | 0.013 (0.002)    | 0.514 (0.093)    | 0 (0.000) |    12.45 | mAnGo, MMS, pandi7o, ReegaN, zodi |
|           36 |     5620 | 2024-02-25 | Natus Vincere Junior      | L   | 0.569      | -            | -                | -                | -         |    -5.54 | mAnGo, MMS, pandi7o, ReegaN, zodi |
|           35 |     6022 | 2024-02-19 | Team Sampi                | L   | 0.529      | -            | -                | -                | -         |    -2.82 | mAnGo, MMS, pandi7o, ReegaN, zodi |
|           34 |     6026 | 2024-02-19 | Natus Vincere Junior      | L   | 0.528      | -            | -                | -                | -         |    -5.36 | mAnGo, MMS, pandi7o, ReegaN, zodi |
|           33 |     6049 | 2024-02-18 | Sashi Esport              | W   | 0.523      | 0.333        | 0.024 (0.004)    | 0.210 (0.037)    | 0 (0.000) |    10.63 | mAnGo, MMS, pandi7o, ReegaN, zodi |
|           32 |     6072 | 2024-02-18 | Passion UA                | W   | 0.522      | 0.303        | 0.057 (0.009)    | 1.000 (0.158)    | 0 (0.000) |    13.94 | mAnGo, MMS, pandi7o, ReegaN, zodi |
|           31 |     6129 | 2024-02-17 | Permitta Esports          | L   | 0.516      | -            | -                | -                | -         |    -2.48 | mAnGo, MMS, pandi7o, ReegaN, zodi |
|           30 |     6204 | 2024-02-15 | Raptors Esports Club      | L   | 0.505      | -            | -                | -                | -         |    -4.20 | cryths, mAnGo, MMS, ReegaN, zodi  |
|           29 |     6250 | 2024-02-15 | brazylijski luz           | W   | 0.502      | 0.303        | 0.013 (0.002)    | 0.514 (0.078)    | 0 (0.000) |    11.21 | mAnGo, MMS, pandi7o, ReegaN, zodi |
|           28 |     6312 | 2024-02-14 | Team Sampi                | L   | 0.495      | -            | -                | -                | -         |    -2.31 | mAnGo, MMS, pandi7o, ReegaN, zodi |
|           27 |     6327 | 2024-02-13 | Souls-Land                | W   | 0.491      | -            | -                | -                | 0 (0.000) |     5.00 | cryths, mAnGo, MMS, ReegaN, zodi  |
|           26 |     6429 | 2024-02-11 | NOM Esports               | L   | 0.477      | -            | -                | -                | -         |    -8.09 | mAnGo, MMS, pandi7o, ReegaN, zodi |
|           25 |     6446 | 2024-02-10 | Betera Esports            | L   | 0.471      | -            | -                | -                | -         |    -3.78 | mAnGo, MMS, pandi7o, ReegaN, zodi |
|           24 |     6454 | 2024-02-10 | UNiTY esports             | W   | 0.470      | 0.143        | -                | 0.766 (0.051)    | 0 (0.000) |    11.81 | mAnGo, MMS, pandi7o, ReegaN, zodi |
|           23 |     6468 | 2024-02-10 | ex-K10                    | W   | 0.468      | 0.303        | -                | 0.517 (0.073)    | -         |    11.08 | mAnGo, MMS, pandi7o, ReegaN, zodi |
|           22 |     6565 | 2024-02-06 | Part Timers               | W   | 0.445      | -            | -                | -                | -         |     9.04 | cryths, mAnGo, MMS, ReegaN, zodi  |
|           21 |     6591 | 2024-02-06 | Young Ninjas              | W   | 0.442      | 0.303        | 0.043 (0.006)    | 0.372 (0.050)    | -         |    11.64 | mAnGo, MMS, pandi7o, ReegaN, zodi |
|           20 |     6731 | 2024-02-03 | Endpoint                  | L   | 0.424      | -            | -                | -                | -         |    -1.76 | mAnGo, MMS, pandi7o, ReegaN, zodi |
|           19 |     6747 | 2024-02-03 | ex-K10                    | W   | 0.423      | -            | -                | -                | -         |    10.67 | mAnGo, MMS, pandi7o, ReegaN, zodi |
|           18 |     6761 | 2024-02-03 | Raptors Esports Club      | W   | 0.423      | -            | -                | -                | -         |    10.75 | mAnGo, MMS, pandi7o, ReegaN, zodi |
|           17 |     6952 | 2024-01-31 | esmagaB                   | L   | 0.402      | -            | -                | -                | -         |    -2.44 | mAnGo, MMS, pandi7o, ReegaN, zodi |
|           16 |     6991 | 2024-01-30 | ex-Anonymo Esports        | L   | 0.395      | -            | -                | -                | -         |    -3.85 | mAnGo, MMS, pandi7o, ReegaN, zodi |
|           15 |     7336 | 2024-01-24 | Pera Esports              | L   | 0.358      | -            | -                | -                | -         |    -1.47 | mAnGo, MMS, pandi7o, ReegaN, zodi |
|           14 |     7417 | 2024-01-23 | Rebels Gaming             | W   | 0.351      | 0.143        | 0.062 (0.003)    | -                | -         |    10.40 | mAnGo, MMS, pandi7o, ReegaN, zodi |
|           13 |     7423 | 2024-01-23 | Team Sampi                | W   | 0.350      | 0.143        | 0.039 (0.002)    | -                | -         |     9.89 | mAnGo, MMS, pandi7o, ReegaN, zodi |
|           12 |     7452 | 2024-01-22 | ALTERNATE aTTaX           | L   | 0.344      | -            | -                | -                | -         |    -0.85 | mAnGo, MMS, pandi7o, ReegaN, zodi |
|           11 |     7468 | 2024-01-22 | ex-Guild Eagles           | L   | 0.344      | -            | -                | -                | -         |    -1.04 | mAnGo, MMS, pandi7o, ReegaN, zodi |
|           10 |     7475 | 2024-01-22 | Pera Esports              | L   | 0.344      | -            | -                | -                | -         |    -1.42 | mAnGo, MMS, pandi7o, ReegaN, zodi |
|            9 |     8105 | 2024-01-12 | The Witchers              | L   | 0.278      | -            | -                | -                | -         |    -2.87 | mAnGo, MMS, pandi7o, ReegaN, zodi |
|            8 |     8254 | 2024-01-10 | 00 Nation                 | L   | 0.265      | -            | -                | -                | -         |    -5.28 | mAnGo, MMS, pandi7o, ReegaN, zodi |
|            7 |     8274 | 2024-01-10 | Sashi Esport              | W   | 0.265      | 0.143        | 0.154 (0.006)    | 1.000 (0.038)    | -         |     7.83 | mAnGo, MMS, pandi7o, ReegaN, zodi |
|            6 |     8449 | 2024-01-07 | Natus Vincere Junior      | L   | 0.242      | -            | -                | -                | -         |    -1.87 | mAnGo, MMS, pandi7o, ReegaN, zodi |
|            5 |     8523 | 2024-01-03 | Lazer Cats                | L   | 0.215      | -            | -                | -                | -         |    -4.33 | mAnGo, MMS, pandi7o, ReegaN, zodi |
|            4 |     8626 | 2023-12-21 | brazylijski luz           | L   | 0.130      | -            | -                | -                | -         |    -0.90 | mAnGo, MMS, pandi7o, ReegaN, zodi |
|            3 |     8644 | 2023-12-20 | Betera Esports            | L   | 0.122      | -            | -                | -                | -         |    -0.90 | mAnGo, MMS, pandi7o, ReegaN, zodi |
|            2 |     9283 | 2023-12-09 | DuckDuckGOOSE             | L   | 0.051      | -            | -                | -                | -         |    -0.99 | JAUSTERE, MMS, papp, ReegaN, zodi |
|            1 |     9297 | 2023-12-09 | ex-K10                    | L   | 0.050      | -            | -                | -                | -         |    -0.27 | JAUSTERE, MMS, papp, ReegaN, zodi |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($0.00)
- Divide that value by the 5th highest value among all rosters ($300,806.11)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
