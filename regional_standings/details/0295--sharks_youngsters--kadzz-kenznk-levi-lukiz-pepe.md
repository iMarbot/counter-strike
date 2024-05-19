### Roster Details<br />
Team Name: Sharks Youngsters<br />
Roster: Kadzz, kenznk, levi, lukiz, pepe<br />
Region: [Americas]( ../standings_americas.md)<br />
<br />
Global Rank: [295](../standings_global.md)<br />
Regional Rank: [64]( ../standings_americas.md)<br />
Final Rank Value:  619.7<br />
<br />
Final Rank Value (619.7) = Starting Rank Value (674.0) + Head To Head Adjustments (-54.3)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.292[<sup>1</sup>](#table2)
- Bounty Collected: 0.246[<sup>2</sup>](#table1)
- Opponent Network: 0.014[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.138<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 674.0
- 400 + ( ( 0.138 - 0.000 ) / ( 0.806 - 0.000 ) ) * 1600 = 674.0


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent                       | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins      | H2H Adj. | Roster                              |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           29 |      331 | 2024-04-27 | Sensei Team                    | L   | 1.000      | -            | -                | -                | -             |    -9.87 | Kadzz, kenznk, levi, lukiz, pepe    |
|           28 |      333 | 2024-04-27 | ODDIK Academy                  | W   | 1.000      | 0.143        | 0.002 (0.000)    | 0.160 (0.023)    | false (0.000) |    16.37 | Kadzz, kenznk, levi, lukiz, pepe    |
|           27 |      337 | 2024-04-27 | NIGERIA 96                     | W   | 1.000      | 0.143        | 0.002 (0.000)    | 0.095 (0.014)    | false (0.000) |    16.43 | Kadzz, kenznk, levi, lukiz, pepe    |
|           26 |      350 | 2024-04-27 | Smoke Gaming                   | L   | 1.000      | -            | -                | -                | -             |   -15.52 | Kadzz, kenznk, levi, lukiz, pepe    |
|           25 |      355 | 2024-04-27 | FURIA Esports Female           | W   | 1.000      | 0.143        | 0.048 (0.007)    | 0.205 (0.029)    | false (0.000) |    23.24 | Kadzz, kenznk, levi, lukiz, pepe    |
|           24 |      397 | 2024-04-26 | Hype E-Sports (Brazilian team) | L   | 1.000      | -            | -                | -                | -             |   -17.40 | Kadzz, kenznk, levi, lukiz, pepe    |
|           23 |      505 | 2024-04-24 | Intense Game                   | L   | 1.000      | -            | -                | -                | -             |   -10.75 | Kadzz, kenznk, levi, lukiz, pepe    |
|           22 |     1091 | 2024-04-13 | Dusty Roots                    | L   | 1.000      | -            | -                | -                | -             |   -15.29 | Kadzz, kenznk, levi, lukiz, pepe    |
|           21 |     1127 | 2024-04-12 | Looking4Org (Brazilian team)   | W   | 1.000      | 0.143        | 0.003 (0.000)    | 0.138 (0.020)    | false (0.000) |    17.43 | Kadzz, kenznk, levi, lukiz, pepe    |
|           20 |     1132 | 2024-04-12 | ODDIK Academy                  | L   | 1.000      | -            | -                | -                | -             |   -15.68 | Kadzz, kenznk, levi, lukiz, pepe    |
|           19 |     1975 | 2024-03-21 | MIBR Academy                   | L   | 0.899      | -            | -                | -                | -             |   -11.00 | Kadzz, kenznk, levi, lukiz, pepe    |
|           18 |     2018 | 2024-03-20 | Hawks (Argentinian team)       | L   | 0.892      | -            | -                | -                | -             |   -11.93 | Kadzz, kenznk, levi, lukiz, pepe    |
|           17 |     2051 | 2024-03-19 | Bombril 1001 Utilidades        | L   | 0.886      | -            | -                | -                | -             |   -12.85 | Kadzz, kenznk, levi, lukiz, pepe    |
|           16 |     2556 | 2024-03-07 | SoJoga Academy                 | W   | 0.806      | 0.143        | 0.001 (0.000)    | 0.109 (0.013)    | false (0.000) |    12.52 | Kadzz, kenznk, levi, lukiz, pepe    |
|           15 |     2936 | 2024-02-29 | Bombril 1001 Utilidades        | L   | 0.759      | -            | -                | -                | -             |   -12.30 | Kadzz, kenznk, levi, lukiz, pepe    |
|           14 |     2984 | 2024-02-28 | Yawara E-Sports                | L   | 0.752      | -            | -                | -                | -             |   -10.29 | Kadzz, kenznk, levi, lukiz, pepe    |
|           13 |     3012 | 2024-02-27 | Intense Game                   | L   | 0.746      | -            | -                | -                | -             |   -11.97 | Kadzz, kenznk, levi, lukiz, pepe    |
|           12 |     4426 | 2024-01-23 | MIBR Academy                   | L   | 0.512      | -            | -                | -                | -             |    -7.58 | Kadzz, ksloks, levi, lukiz, pepe    |
|           11 |     5301 | 2023-12-20 | TIMACETA                       | W   | 0.286      | 0.143        | 0.001 (0.000)    | 0.145 (0.006)    | false (0.000) |     4.18 | Kadzz, ksloks, levi, lukiz, pepe    |
|           10 |     5302 | 2023-12-20 | Intense Game                   | W   | 0.286      | 0.143        | 0.008 (0.000)    | 0.372 (0.015)    | false (0.000) |     4.79 | Kadzz, ksloks, levi, lukiz, pepe    |
|            9 |     5309 | 2023-12-19 | Hype E-Sports (Brazilian team) | W   | 0.280      | -            | -                | -                | false (0.000) |     3.13 | Kadzz, ksloks, levi, lukiz, pepe    |
|            8 |     5349 | 2023-12-17 | Intense Game                   | L   | 0.266      | -            | -                | -                | -             |    -3.87 | Kadzz, ksloks, levi, lukiz, pepe    |
|            7 |     5635 | 2023-12-13 | Intense Game                   | W   | 0.239      | 0.143        | 0.008 (0.000)    | 0.372 (0.013)    | false (0.000) |     4.10 | Kadzz, ksloks, levi, lukiz, pepe    |
|            6 |     5648 | 2023-12-13 | TIMACETA                       | W   | 0.238      | 0.143        | 0.001 (0.000)    | 0.145 (0.005)    | false (0.000) |     3.45 | Kadzz, ksloks, levi, lukiz, pepe    |
|            5 |     5663 | 2023-12-12 | Myth e-Sports                  | W   | 0.233      | -            | -                | -                | -             |     3.24 | Kadzz, ksloks, levi, lukiz, pepe    |
|            4 |     6692 | 2023-11-18 | TIMACETA                       | W   | 0.073      | -            | -                | -                | -             |     1.09 | kenznk, ksloks, lukiz, pepe, yangue |
|            3 |     6697 | 2023-11-18 | Yawara E-Sports                | W   | 0.072      | 0.233        | 0.005 (0.000)    | 0.361 (0.006)    | -             |     1.28 | kenznk, ksloks, lukiz, pepe, yangue |
|            2 |     7044 | 2023-11-11 | Yawara E-Sports                | W   | 0.026      | -            | -                | -                | -             |     0.47 | kenznk, lukiz, pepe, s1cko, yangue  |
|            1 |     7045 | 2023-11-11 | Vex Dragons                    | W   | 0.026      | -            | -                | -                | -             |     0.32 | kenznk, lukiz, pepe, s1cko, yangue  |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($590.32)
- Divide that value by the 5th highest value among all rosters ($158,437.64)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-05-01 |      1.000 | $115.49        | $115.49         |
| 2024-04-27 |      1.000 | $126.99        | $126.99         |
| 2023-12-20 |      0.286 | $1,027.05      | $294.23         |
| 2023-11-18 |      0.074 | $545.82        | $40.39          |
| 2023-11-11 |      0.026 | $500.00        | $13.22          |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
