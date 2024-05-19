### Roster Details<br />
Team Name: Team Secret<br />
Roster: anarkez, Kind0, Maze, NOPEEj, Tauson<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [208](../standings_global.md)<br />
Regional Rank: [139]( ../standings_europe.md)<br />
Final Rank Value:  704.4<br />
<br />
Final Rank Value (704.4) = Starting Rank Value (654.7) + Head To Head Adjustments (49.7)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.000[<sup>1</sup>](#table2)
- Bounty Collected: 0.348[<sup>2</sup>](#table1)
- Opponent Network: 0.166[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.128<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 654.7
- 400 + ( ( 0.128 - 0.000 ) / ( 0.806 - 0.000 ) ) * 1600 = 654.7


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent                     | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                 |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           40 |      819 | 2024-04-19 | EsmagaB                      | L   | 1.000      | -            | -                | -                | -         |   -10.53 | anarkez, Kind0, Maze, NOPEEj, Tauson   |
|           39 |      884 | 2024-04-18 | Nemiga Gaming                | L   | 1.000      | -            | -                | -                | -         |    -1.63 | anarkez, Kind0, Maze, NOPEEj, Tauson   |
|           38 |      897 | 2024-04-18 | 500                          | W   | 1.000      | 0.143        | -                | 0.660 (0.094)    | 0 (0.000) |    24.57 | anarkez, Kind0, Maze, NOPEEj, Tauson   |
|           37 |      937 | 2024-04-17 | Illuminar Gaming             | L   | 1.000      | -            | -                | -                | -         |   -10.30 | anarkez, Kind0, Maze, NOPEEj, Tauson   |
|           36 |     1025 | 2024-04-16 | Team Sampi                   | L   | 1.000      | -            | -                | -                | -         |    -4.64 | anarkez, Kind0, Maze, NOPEEj, Tauson   |
|           35 |     1056 | 2024-04-15 | Turów Zgorzelec Esport       | W   | 1.000      | 0.371        | 0.019 (0.007)    | 0.640 (0.237)    | 0 (0.000) |    18.81 | anarkez, Kind0, Maze, NOPEEj, Tauson   |
|           34 |     1188 | 2024-04-11 | ENCE Academy                 | L   | 1.000      | -            | -                | -                | -         |   -10.52 | anarkez, Kind0, Maze, NOPEEj, Tauson   |
|           33 |     1450 | 2024-04-05 | 9Pandas                      | W   | 0.997      | 0.384        | 0.085 (0.033)    | 0.661 (0.253)    | 0 (0.000) |    29.23 | anarkez, Kind0, Maze, NOPEEj, Tauson   |
|           32 |     1750 | 2024-03-27 | FORZE Esports                | L   | 0.938      | -            | -                | -                | -         |    -1.97 | anarkez, Kind0, Maze, NOPEEj, Tauson   |
|           31 |     1798 | 2024-03-26 | ARCRED                       | W   | 0.932      | 0.143        | 0.004 (0.001)    | 0.825 (0.110)    | 0 (0.000) |    20.88 | anarkez, Kind0, Maze, NOPEEj, Tauson   |
|           30 |     2387 | 2024-03-12 | Endpoint                     | L   | 0.836      | -            | -                | -                | -         |    -6.06 | anarkez, Kind0, Maze, NOPEEj, Tauson   |
|           29 |     2536 | 2024-03-08 | Metizport                    | L   | 0.811      | -            | -                | -                | -         |    -1.73 | anarkez, innocent, Kind0, Maze, Tauson |
|           28 |     2586 | 2024-03-07 | Grannys Knockers             | L   | 0.803      | -            | -                | -                | -         |    -6.65 | anarkez, innocent, Kind0, Maze, Tauson |
|           27 |     2729 | 2024-03-04 | NAMELESS (European mix-team) | L   | 0.786      | -            | -                | -                | -         |   -20.24 | anarkez, innocent, Kind0, Maze, Tauson |
|           26 |     2766 | 2024-03-04 | K10                          | L   | 0.784      | -            | -                | -                | -         |    -7.29 | anarkez, innocent, Kind0, Maze, Tauson |
|           25 |     2820 | 2024-03-03 | Zero Tenacity                | L   | 0.776      | -            | -                | -                | -         |    -4.86 | anarkez, innocent, Kind0, Maze, Tauson |
|           24 |     2841 | 2024-03-02 | Entropiq                     | W   | 0.772      | -            | -                | -                | 0 (0.000) |    16.13 | anarkez, innocent, Kind0, Maze, Tauson |
|           23 |     2901 | 2024-03-02 | Zero Tenacity                | L   | 0.770      | -            | -                | -                | -         |    -4.68 | anarkez, innocent, Kind0, Maze, Tauson |
|           22 |     2959 | 2024-02-29 | UNiTY esports (Slovak team)  | L   | 0.758      | -            | -                | -                | -         |    -6.70 | anarkez, innocent, Kind0, Maze, Tauson |
|           21 |     2966 | 2024-02-29 | Ex-sYnck                     | L   | 0.757      | -            | -                | -                | -         |   -16.20 | anarkez, innocent, Kind0, Maze, Tauson |
|           20 |     3001 | 2024-02-28 | Permitta Esports             | W   | 0.751      | 0.384        | 0.063 (0.018)    | 1.000 (0.288)    | 0 (0.000) |    19.97 | anarkez, innocent, Kind0, Maze, Tauson |
|           19 |     3108 | 2024-02-25 | Entropiq                     | L   | 0.731      | -            | -                | -                | -         |    -7.87 | anarkez, innocent, Kind0, Maze, Tauson |
|           18 |     3289 | 2024-02-21 | FLuffy Gangsters             | L   | 0.706      | -            | -                | -                | -         |   -13.73 | anarkez, innocent, Kind0, Maze, Tauson |
|           17 |     3301 | 2024-02-21 | GenOne                       | W   | 0.705      | -            | -                | -                | 0 (0.000) |     7.78 | anarkez, innocent, Kind0, Maze, Tauson |
|           16 |     3410 | 2024-02-19 | CYBERSHOKE Esports           | W   | 0.692      | 0.371        | 0.004 (0.001)    | -                | 0 (0.000) |    11.94 | anarkez, innocent, Kind0, Maze, Tauson |
|           15 |     3416 | 2024-02-19 | GODSENT                      | L   | 0.691      | -            | -                | -                | -         |    -8.19 | anarkez, innocent, Kind0, Maze, Tauson |
|           14 |     3505 | 2024-02-17 | Team Sampi                   | L   | 0.677      | -            | -                | -                | -         |    -3.16 | anarkez, innocent, Kind0, Maze, Tauson |
|           13 |     3581 | 2024-02-15 | Zero Tenacity                | W   | 0.665      | 0.371        | 0.095 (0.023)    | 1.000 (0.247)    | 0 (0.000) |    16.74 | anarkez, innocent, Kind0, Maze, Tauson |
|           12 |     3727 | 2024-02-12 | Nemiga Gaming                | L   | 0.645      | -            | -                | -                | -         |    -0.53 | anarkez, innocent, Kind0, Maze, Tauson |
|           11 |     3731 | 2024-02-12 | Team Spirit Academy          | W   | 0.645      | 0.371        | 0.021 (0.005)    | 0.422 (0.101)    | 0 (0.000) |    14.30 | anarkez, innocent, Kind0, Maze, Tauson |
|           10 |     3865 | 2024-02-06 | Betera Esports               | L   | 0.604      | -            | -                | -                | -         |    -5.77 | anarkez, innocent, Kind0, Maze, Tauson |
|            9 |     3881 | 2024-02-05 | VP.Prodigy                   | L   | 0.599      | -            | -                | -                | -         |    -4.93 | anarkez, innocent, Kind0, Maze, Tauson |
|            8 |     3924 | 2024-02-04 | Alliance                     | W   | 0.591      | 0.143        | 0.017 (0.001)    | 0.729 (0.062)    | -         |    13.62 | anarkez, innocent, Kind0, Maze, Tauson |
|            7 |     3937 | 2024-02-04 | MOUZ NXT                     | W   | 0.590      | 0.333        | 0.215 (0.042)    | 1.000 (0.197)    | -         |    16.97 | anarkez, innocent, Kind0, Maze, Tauson |
|            6 |     4055 | 2024-02-02 | L&G                          | W   | 0.576      | -            | -                | -                | -         |     6.62 | anarkez, innocent, Kind0, Maze, Tauson |
|            5 |     4105 | 2024-01-31 | Permitta Esports             | L   | 0.565      | -            | -                | -                | -         |    -2.19 | anarkez, innocent, Kind0, Maze, Tauson |
|            4 |     4141 | 2024-01-30 | HOTU                         | W   | 0.559      | 0.371        | 0.011 (0.002)    | 0.323 (0.067)    | -         |    12.34 | anarkez, innocent, Kind0, Maze, Tauson |
|            3 |     4203 | 2024-01-29 | Monte Gen                    | L   | 0.550      | -            | -                | -                | -         |    -4.32 | anarkez, innocent, Kind0, Maze, Tauson |
|            2 |     4926 | 2024-01-12 | Clownfiesta                  | L   | 0.439      | -            | -                | -                | -         |   -11.03 | anarkez, innocent, Kind0, Maze, Tauson |
|            1 |     5107 | 2024-01-09 | Illuminar Gaming             | L   | 0.418      | -            | -                | -                | -         |    -4.44 | anarkez, innocent, Kind0, Maze, Tauson |

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
