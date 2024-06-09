### Roster Details<br />
Team Name: Team Secret<br />
Roster: anarkez, Juve, Kind0, NOPEEj, Tauson<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [292](../standings_global.md)<br />
Regional Rank: [184]( ../standings_europe.md)<br />
Final Rank Value:  650.3<br />
<br />
Final Rank Value (650.3) = Starting Rank Value (630.9) + Head To Head Adjustments (19.3)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.000[<sup>1</sup>](#table2)
- Bounty Collected: 0.331[<sup>2</sup>](#table1)
- Opponent Network: 0.124[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.114<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 630.9
- 400 + ( ( 0.114 - 0.000 ) / ( 0.787 - 0.000 ) ) * 1600 = 630.9


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent                  | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                 |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           45 |     1297 | 2024-05-14 | WOPA Esport               | L   | 1.000      | -            | -                | -                | -         |   -12.00 | anarkez, Juve, Kind0, NOPEEj, Tauson   |
|           44 |     1312 | 2024-05-13 | LEON Esports              | L   | 1.000      | -            | -                | -                | -         |   -13.72 | anarkez, Juve, Kind0, NOPEEj, Tauson   |
|           43 |     2753 | 2024-04-19 | esmagaB                   | L   | 0.930      | -            | -                | -                | -         |    -9.04 | anarkez, Kind0, Maze, NOPEEj, Tauson   |
|           42 |     2825 | 2024-04-18 | Nemiga Gaming             | L   | 0.923      | -            | -                | -                | -         |    -1.66 | anarkez, Kind0, Maze, NOPEEj, Tauson   |
|           41 |     2841 | 2024-04-18 | 500                       | W   | 0.922      | 0.143        | 0.002 (0.000)    | 0.479 (0.063)    | 0 (0.000) |    21.84 | anarkez, Kind0, Maze, NOPEEj, Tauson   |
|           40 |     2894 | 2024-04-17 | Illuminar Gaming          | L   | 0.917      | -            | -                | -                | -         |    -9.16 | anarkez, Kind0, Maze, NOPEEj, Tauson   |
|           39 |     2992 | 2024-04-16 | Team Sampi                | L   | 0.908      | -            | -                | -                | -         |    -4.07 | anarkez, Kind0, Maze, NOPEEj, Tauson   |
|           38 |     3028 | 2024-04-15 | ex-Turów Zgorzelec Esport | W   | 0.902      | 0.371        | 0.006 (0.002)    | 0.491 (0.164)    | 0 (0.000) |    17.38 | anarkez, Kind0, Maze, NOPEEj, Tauson   |
|           37 |     3202 | 2024-04-11 | ENCE Academy              | L   | 0.875      | -            | -                | -                | -         |    -8.64 | anarkez, Kind0, Maze, NOPEEj, Tauson   |
|           36 |     3537 | 2024-04-05 | 9Pandas                   | W   | 0.836      | 0.384        | 0.110 (0.035)    | 0.710 (0.228)    | 0 (0.000) |    24.98 | anarkez, Kind0, Maze, NOPEEj, Tauson   |
|           35 |     3899 | 2024-03-27 | FORZE Esports             | L   | 0.777      | -            | -                | -                | -         |    -1.90 | anarkez, Kind0, Maze, NOPEEj, Tauson   |
|           34 |     3956 | 2024-03-26 | ARCRED                    | W   | 0.771      | 0.143        | -                | 0.630 (0.069)    | 0 (0.000) |    17.19 | anarkez, Kind0, Maze, NOPEEj, Tauson   |
|           33 |     4694 | 2024-03-12 | Endpoint                  | L   | 0.675      | -            | -                | -                | -         |    -3.35 | anarkez, Kind0, Maze, NOPEEj, Tauson   |
|           32 |     4885 | 2024-03-08 | Metizport                 | L   | 0.649      | -            | -                | -                | -         |    -1.75 | anarkez, innocent, Kind0, Maze, Tauson |
|           31 |     4959 | 2024-03-07 | ex-Preasy Esport          | L   | 0.642      | -            | -                | -                | -         |    -2.40 | anarkez, innocent, Kind0, Maze, Tauson |
|           30 |     5143 | 2024-03-04 | NAMELESS                  | L   | 0.625      | -            | -                | -                | -         |   -15.64 | anarkez, innocent, Kind0, Maze, Tauson |
|           29 |     5193 | 2024-03-04 | ex-K10                    | L   | 0.623      | -            | -                | -                | -         |    -5.44 | anarkez, innocent, Kind0, Maze, Tauson |
|           28 |     5260 | 2024-03-03 | Zero Tenacity             | L   | 0.615      | -            | -                | -                | -         |    -2.27 | anarkez, innocent, Kind0, Maze, Tauson |
|           27 |     5267 | 2024-03-02 | ex-Sprout                 | L   | 0.612      | -            | -                | -                | -         |   -10.29 | anarkez, innocent, Kind0, Maze, Tauson |
|           26 |     5285 | 2024-03-02 | Entropiq                  | W   | 0.611      | -            | -                | -                | 0 (0.000) |    11.05 | anarkez, innocent, Kind0, Maze, Tauson |
|           25 |     5362 | 2024-03-02 | Zero Tenacity             | L   | 0.609      | -            | -                | -                | -         |    -2.29 | anarkez, innocent, Kind0, Maze, Tauson |
|           24 |     5429 | 2024-02-29 | UNiTY esports             | L   | 0.597      | -            | -                | -                | -         |    -4.93 | anarkez, innocent, Kind0, Maze, Tauson |
|           23 |     5437 | 2024-02-29 | ex-sYnck                  | L   | 0.596      | -            | -                | -                | -         |    -7.18 | anarkez, innocent, Kind0, Maze, Tauson |
|           22 |     5486 | 2024-02-28 | Permitta Esports          | W   | 0.589      | 0.384        | 0.025 (0.006)    | 1.000 (0.227)    | 0 (0.000) |    15.91 | anarkez, innocent, Kind0, Maze, Tauson |
|           21 |     5619 | 2024-02-25 | Entropiq                  | L   | 0.569      | -            | -                | -                | -         |    -7.96 | anarkez, innocent, Kind0, Maze, Tauson |
|           20 |     5856 | 2024-02-21 | FLuffy Gangsters          | L   | 0.544      | -            | -                | -                | -         |    -9.75 | anarkez, innocent, Kind0, Maze, Tauson |
|           19 |     5870 | 2024-02-21 | GenOne                    | W   | 0.544      | -            | -                | -                | 0 (0.000) |     6.20 | anarkez, innocent, Kind0, Maze, Tauson |
|           18 |     6003 | 2024-02-19 | CYBERSHOKE Esports        | W   | 0.531      | -            | -                | -                | 0 (0.000) |     7.22 | anarkez, innocent, Kind0, Maze, Tauson |
|           17 |     6010 | 2024-02-19 | AURA                      | L   | 0.530      | -            | -                | -                | -         |    -9.17 | anarkez, innocent, Kind0, Maze, Tauson |
|           16 |     6130 | 2024-02-17 | Team Sampi                | L   | 0.516      | -            | -                | -                | -         |    -2.69 | anarkez, innocent, Kind0, Maze, Tauson |
|           15 |     6218 | 2024-02-15 | Zero Tenacity             | W   | 0.504      | 0.371        | 0.147 (0.027)    | 1.000 (0.187)    | 0 (0.000) |    14.09 | anarkez, innocent, Kind0, Maze, Tauson |
|           14 |     6396 | 2024-02-12 | Nemiga Gaming             | L   | 0.484      | -            | -                | -                | -         |    -0.51 | anarkez, innocent, Kind0, Maze, Tauson |
|           13 |     6401 | 2024-02-12 | Team Spirit Academy       | W   | 0.484      | 0.371        | 0.004 (0.001)    | 0.229 (0.041)    | 0 (0.000) |     9.97 | anarkez, innocent, Kind0, Maze, Tauson |
|           12 |     6466 | 2024-02-10 | 500                       | W   | 0.469      | 0.143        | 0.002 (0.000)    | -                | -         |    10.64 | anarkez, innocent, Kind0, Maze, Tauson |
|           11 |     6581 | 2024-02-06 | Betera Esports            | L   | 0.443      | -            | -                | -                | -         |    -3.66 | anarkez, innocent, Kind0, Maze, Tauson |
|           10 |     6604 | 2024-02-05 | VP.Prodigy                | L   | 0.438      | -            | -                | -                | -         |    -3.10 | anarkez, innocent, Kind0, Maze, Tauson |
|            9 |     6665 | 2024-02-04 | Alliance                  | W   | 0.430      | 0.143        | 0.004 (0.000)    | 0.529 (0.033)    | -         |    10.05 | anarkez, innocent, Kind0, Maze, Tauson |
|            8 |     6681 | 2024-02-04 | MOUZ NXT                  | W   | 0.429      | 0.333        | 0.157 (0.022)    | 0.977 (0.140)    | -         |    12.62 | anarkez, innocent, Kind0, Maze, Tauson |
|            7 |     6847 | 2024-02-02 | L&G                       | W   | 0.415      | -            | -                | -                | -         |     4.86 | anarkez, innocent, Kind0, Maze, Tauson |
|            6 |     6875 | 2024-02-01 | los kogutos               | L   | 0.411      | -            | -                | -                | -         |    -8.00 | anarkez, innocent, Kind0, Maze, Tauson |
|            5 |     6924 | 2024-01-31 | Permitta Esports          | L   | 0.404      | -            | -                | -                | -         |    -1.68 | anarkez, innocent, Kind0, Maze, Tauson |
|            4 |     6971 | 2024-01-30 | HOTU                      | W   | 0.398      | 0.371        | 0.004 (0.001)    | 0.580 (0.086)    | -         |     9.92 | anarkez, innocent, Kind0, Maze, Tauson |
|            3 |     7060 | 2024-01-29 | Monte Gen                 | L   | 0.389      | -            | -                | -                | -         |    -3.34 | anarkez, innocent, Kind0, Maze, Tauson |
|            2 |     8091 | 2024-01-12 | Clownfiesta               | L   | 0.278      | -            | -                | -                | -         |    -6.84 | anarkez, innocent, Kind0, Maze, Tauson |
|            1 |     8360 | 2024-01-09 | brazylijski luz           | L   | 0.257      | -            | -                | -                | -         |    -2.14 | anarkez, innocent, Kind0, Maze, Tauson |

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
