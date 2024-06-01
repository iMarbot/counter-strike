### Roster Details<br />
Team Name: Viperio<br />
Roster: mAnGo, MMS, pandi7o, ReegaN, zodi<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [291](../standings_global.md)<br />
Regional Rank: [177]( ../standings_europe.md)<br />
Final Rank Value:  647.6<br />
<br />
Final Rank Value (647.6) = Starting Rank Value (590.1) + Head To Head Adjustments (57.5)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.000[<sup>1</sup>](#table2)
- Bounty Collected: 0.294[<sup>2</sup>](#table1)
- Opponent Network: 0.080[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.093<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 590.1
- 400 + ( ( 0.093 - 0.000 ) / ( 0.786 - 0.000 ) ) * 1600 = 590.1


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
|           49 |     4046 | 2024-03-22 | Sashi Esport              | L   | 0.742      | -            | -                | -                | -         |    -2.34 | mAnGo, MMS, pandi7o, ReegaN, zodi |
|           48 |     4048 | 2024-03-22 | Astralis Talent           | L   | 0.742      | -            | -                | -                | -         |    -4.68 | mAnGo, MMS, pandi7o, ReegaN, zodi |
|           47 |     4184 | 2024-03-19 | GamerLegion Academy       | L   | 0.722      | -            | -                | -                | -         |    -6.60 | mAnGo, MMS, pandi7o, ReegaN, zodi |
|           46 |     4244 | 2024-03-17 | ex-Turów Zgorzelec Esport | L   | 0.711      | -            | -                | -                | -         |    -8.24 | mAnGo, MMS, pandi7o, ReegaN, zodi |
|           45 |     4367 | 2024-03-15 | LEON Esports              | L   | 0.698      | -            | -                | -                | -         |    -8.65 | mAnGo, MMS, pandi7o, ReegaN, zodi |
|           44 |     4393 | 2024-03-15 | Astralis Talent           | W   | 0.695      | 0.333        | 0.012 (0.003)    | 0.452 (0.105)    | 0 (0.000) |    17.17 | mAnGo, MMS, pandi7o, ReegaN, zodi |
|           43 |     4591 | 2024-03-11 | Preasy Esport             | W   | 0.671      | 0.333        | 0.008 (0.002)    | 0.642 (0.144)    | 0 (0.000) |    14.72 | mAnGo, MMS, pandi7o, ReegaN, zodi |
|           42 |     4979 | 2024-03-05 | Alliance                  | L   | 0.628      | -            | -                | -                | -         |    -5.16 | mAnGo, MMS, pandi7o, ReegaN, zodi |
|           41 |     5068 | 2024-03-03 | MOUZ NXT                  | L   | 0.618      | -            | -                | -                | -         |    -1.51 | mAnGo, MMS, pandi7o, ReegaN, zodi |
|           40 |     5088 | 2024-03-03 | The Neighbours            | L   | 0.617      | -            | -                | -                | -         |    -9.29 | cryths, mAnGo, MMS, ReegaN, zodi  |
|           39 |     5245 | 2024-03-01 | Dynamo Eclot              | L   | 0.602      | -            | -                | -                | -         |    -1.47 | mAnGo, MMS, pandi7o, ReegaN, zodi |
|           38 |     5248 | 2024-02-29 | Verdant                   | L   | 0.598      | -            | -                | -                | -         |    -3.74 | cryths, mAnGo, MMS, ReegaN, zodi  |
|           37 |     5249 | 2024-02-29 | Dreams To Legends         | W   | 0.598      | -            | -                | -                | 0 (0.000) |     5.07 | cryths, mAnGo, MMS, ReegaN, zodi  |
|           36 |     5291 | 2024-02-29 | brazylijski luz           | W   | 0.596      | 0.303        | 0.013 (0.002)    | 0.490 (0.089)    | 0 (0.000) |    12.53 | mAnGo, MMS, pandi7o, ReegaN, zodi |
|           35 |     5462 | 2024-02-25 | Natus Vincere Junior      | L   | 0.569      | -            | -                | -                | -         |    -5.33 | mAnGo, MMS, pandi7o, ReegaN, zodi |
|           34 |     5850 | 2024-02-19 | Team Sampi                | L   | 0.529      | -            | -                | -                | -         |    -2.78 | mAnGo, MMS, pandi7o, ReegaN, zodi |
|           33 |     5854 | 2024-02-19 | Natus Vincere Junior      | L   | 0.528      | -            | -                | -                | -         |    -5.16 | mAnGo, MMS, pandi7o, ReegaN, zodi |
|           32 |     5876 | 2024-02-18 | Sashi Esport              | W   | 0.523      | 0.333        | 0.024 (0.004)    | 0.210 (0.037)    | 0 (0.000) |    10.81 | mAnGo, MMS, pandi7o, ReegaN, zodi |
|           31 |     5899 | 2024-02-18 | Passion UA                | W   | 0.522      | 0.303        | 0.057 (0.009)    | 1.000 (0.158)    | 0 (0.000) |    13.98 | mAnGo, MMS, pandi7o, ReegaN, zodi |
|           30 |     5956 | 2024-02-17 | Permitta Esports          | L   | 0.516      | -            | -                | -                | -         |    -2.46 | mAnGo, MMS, pandi7o, ReegaN, zodi |
|           29 |     6028 | 2024-02-15 | Raptors Esports Club      | L   | 0.505      | -            | -                | -                | -         |    -4.02 | cryths, mAnGo, MMS, ReegaN, zodi  |
|           28 |     6069 | 2024-02-15 | brazylijski luz           | W   | 0.502      | 0.303        | 0.013 (0.002)    | 0.490 (0.075)    | 0 (0.000) |    11.27 | mAnGo, MMS, pandi7o, ReegaN, zodi |
|           27 |     6131 | 2024-02-14 | Team Sampi                | L   | 0.495      | -            | -                | -                | -         |    -2.26 | mAnGo, MMS, pandi7o, ReegaN, zodi |
|           26 |     6144 | 2024-02-13 | Souls-Land                | W   | 0.491      | -            | -                | -                | 0 (0.000) |     5.23 | cryths, mAnGo, MMS, ReegaN, zodi  |
|           25 |     6241 | 2024-02-11 | NOM Esports               | L   | 0.477      | -            | -                | -                | -         |    -7.88 | mAnGo, MMS, pandi7o, ReegaN, zodi |
|           24 |     6258 | 2024-02-10 | Betera Esports            | L   | 0.471      | -            | -                | -                | -         |    -3.61 | mAnGo, MMS, pandi7o, ReegaN, zodi |
|           23 |     6266 | 2024-02-10 | UNiTY esports             | W   | 0.470      | 0.143        | -                | 0.766 (0.051)    | 0 (0.000) |    12.05 | mAnGo, MMS, pandi7o, ReegaN, zodi |
|           22 |     6280 | 2024-02-10 | ex-K10                    | W   | 0.468      | 0.303        | -                | 0.382 (0.054)    | 0 (0.000) |    11.18 | mAnGo, MMS, pandi7o, ReegaN, zodi |
|           21 |     6395 | 2024-02-06 | Young Ninjas              | W   | 0.442      | 0.303        | 0.043 (0.006)    | 0.372 (0.050)    | -         |    11.69 | mAnGo, MMS, pandi7o, ReegaN, zodi |
|           20 |     6528 | 2024-02-03 | Endpoint                  | L   | 0.424      | -            | -                | -                | -         |    -1.77 | mAnGo, MMS, pandi7o, ReegaN, zodi |
|           19 |     6544 | 2024-02-03 | ex-K10                    | W   | 0.423      | -            | -                | -                | -         |    10.52 | mAnGo, MMS, pandi7o, ReegaN, zodi |
|           18 |     6558 | 2024-02-03 | Raptors Esports Club      | W   | 0.423      | -            | -                | -                | -         |    10.78 | mAnGo, MMS, pandi7o, ReegaN, zodi |
|           17 |     6739 | 2024-01-31 | esmagaB                   | L   | 0.402      | -            | -                | -                | -         |    -2.44 | mAnGo, MMS, pandi7o, ReegaN, zodi |
|           16 |     6775 | 2024-01-30 | ex-Anonymo Esports        | L   | 0.395      | -            | -                | -                | -         |    -3.78 | mAnGo, MMS, pandi7o, ReegaN, zodi |
|           15 |     7106 | 2024-01-24 | Pera Esports              | L   | 0.358      | -            | -                | -                | -         |    -1.45 | mAnGo, MMS, pandi7o, ReegaN, zodi |
|           14 |     7179 | 2024-01-23 | Rebels Gaming             | W   | 0.351      | 0.143        | 0.062 (0.003)    | -                | -         |    10.40 | mAnGo, MMS, pandi7o, ReegaN, zodi |
|           13 |     7184 | 2024-01-23 | Team Sampi                | W   | 0.350      | 0.143        | 0.039 (0.002)    | -                | -         |     9.88 | mAnGo, MMS, pandi7o, ReegaN, zodi |
|           12 |     7211 | 2024-01-22 | ALTERNATE aTTaX           | L   | 0.344      | -            | -                | -                | -         |    -3.17 | mAnGo, MMS, pandi7o, ReegaN, zodi |
|           11 |     7225 | 2024-01-22 | ex-Guild Eagles           | L   | 0.344      | -            | -                | -                | -         |    -1.03 | mAnGo, MMS, pandi7o, ReegaN, zodi |
|           10 |     7232 | 2024-01-22 | Pera Esports              | L   | 0.344      | -            | -                | -                | -         |    -1.38 | mAnGo, MMS, pandi7o, ReegaN, zodi |
|            9 |     7852 | 2024-01-12 | The Witchers              | L   | 0.278      | -            | -                | -                | -         |    -2.86 | mAnGo, MMS, pandi7o, ReegaN, zodi |
|            8 |     8000 | 2024-01-10 | 00 Nation                 | L   | 0.265      | -            | -                | -                | -         |    -5.27 | mAnGo, MMS, pandi7o, ReegaN, zodi |
|            7 |     8020 | 2024-01-10 | Sashi Esport              | W   | 0.265      | 0.143        | 0.172 (0.006)    | 1.000 (0.038)    | -         |     7.83 | mAnGo, MMS, pandi7o, ReegaN, zodi |
|            6 |     8194 | 2024-01-07 | Natus Vincere Junior      | L   | 0.242      | -            | -                | -                | -         |    -1.86 | mAnGo, MMS, pandi7o, ReegaN, zodi |
|            5 |     8267 | 2024-01-03 | Lazer Cats                | L   | 0.215      | -            | -                | -                | -         |    -4.32 | mAnGo, MMS, pandi7o, ReegaN, zodi |
|            4 |     8369 | 2023-12-21 | brazylijski luz           | L   | 0.130      | -            | -                | -                | -         |    -0.91 | mAnGo, MMS, pandi7o, ReegaN, zodi |
|            3 |     8387 | 2023-12-20 | Betera Esports            | L   | 0.122      | -            | -                | -                | -         |    -0.90 | mAnGo, MMS, pandi7o, ReegaN, zodi |
|            2 |     9017 | 2023-12-09 | DuckDuckGOOSE             | L   | 0.051      | -            | -                | -                | -         |    -0.99 | JAUSTERE, MMS, papp, ReegaN, zodi |
|            1 |     9031 | 2023-12-09 | ex-K10                    | L   | 0.050      | -            | -                | -                | -         |    -0.29 | JAUSTERE, MMS, papp, ReegaN, zodi |

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
