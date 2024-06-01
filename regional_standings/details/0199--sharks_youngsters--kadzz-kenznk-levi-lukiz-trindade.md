### Roster Details<br />
Team Name: Sharks Youngsters<br />
Roster: Kadzz, kenznk, levi, lukiz, trindade<br />
Region: [Americas]( ../standings_americas.md)<br />
<br />
Global Rank: [199](../standings_global.md)<br />
Regional Rank: [42]( ../standings_americas.md)<br />
Final Rank Value:  724.4<br />
<br />
Final Rank Value (724.4) = Starting Rank Value (679.9) + Head To Head Adjustments (44.5)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.286[<sup>1</sup>](#table2)
- Bounty Collected: 0.234[<sup>2</sup>](#table1)
- Opponent Network: 0.030[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.137<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 679.9
- 400 + ( ( 0.137 - 0.000 ) / ( 0.786 - 0.000 ) ) * 1600 = 679.9


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent                | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                               |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           44 |      385 | 2024-05-23 | paiN Gaming Academy     | W   | 1.000      | 0.143        | 0.005 (0.001)    | 0.374 (0.053)    | 0 (0.000) |    14.91 | Kadzz, kenznk, levi, lukiz, trindade |
|           43 |      643 | 2024-05-20 | MIBR Academy            | W   | 1.000      | 0.143        | 0.003 (0.000)    | 0.220 (0.031)    | 0 (0.000) |    16.80 | Kadzz, kenznk, levi, lukiz, trindade |
|           42 |      733 | 2024-05-19 | Peak Academy            | W   | 1.000      | -            | -                | -                | 0 (0.000) |    13.41 | Kadzz, kenznk, levi, lukiz, pepe     |
|           41 |      813 | 2024-05-18 | Hawks                   | W   | 1.000      | 0.143        | -                | 0.220 (0.031)    | 0 (0.000) |    14.16 | Kadzz, kenznk, levi, lukiz, pepe     |
|           40 |      814 | 2024-05-18 | MX Team                 | W   | 1.000      | -            | -                | -                | 0 (0.000) |    12.45 | Kadzz, kenznk, levi, lukiz, pepe     |
|           39 |      820 | 2024-05-18 | Angels                  | W   | 1.000      | -            | -                | -                | 0 (0.000) |    10.69 | Kadzz, kenznk, levi, lukiz, pepe     |
|           38 |      826 | 2024-05-18 | COBRAMOS POCO           | W   | 1.000      | -            | -                | -                | 0 (0.000) |     6.55 | Kadzz, kenznk, levi, lukiz, pepe     |
|           37 |      834 | 2024-05-18 | Peak Academy            | L   | 1.000      | -            | -                | -                | -         |   -16.26 | Kadzz, kenznk, levi, lukiz, pepe     |
|           36 |      847 | 2024-05-18 | NIGERIA 96              | W   | 1.000      | 0.143        | 0.001 (0.000)    | 0.140 (0.020)    | 0 (0.000) |    13.65 | Kadzz, kenznk, levi, lukiz, pepe     |
|           35 |     1042 | 2024-05-16 | Vikings KR              | L   | 1.000      | -            | -                | -                | -         |   -11.75 | Kadzz, kenznk, levi, lukiz, trindade |
|           34 |     1058 | 2024-05-16 | 2Game Esports           | W   | 1.000      | 0.143        | 0.003 (0.000)    | 0.212 (0.030)    | 0 (0.000) |    16.23 | Kadzz, kenznk, levi, lukiz, trindade |
|           33 |     1601 | 2024-05-08 | Romanticos              | L   | 1.000      | -            | -                | -                | -         |   -16.97 | Kadzz, kenznk, levi, lukiz, pepe     |
|           32 |     2137 | 2024-04-27 | Sensei Team             | L   | 0.986      | -            | -                | -                | -         |   -11.32 | Kadzz, kenznk, levi, lukiz, pepe     |
|           31 |     2139 | 2024-04-27 | ODDIK Academy           | W   | 0.985      | 0.143        | 0.001 (0.000)    | 0.134 (0.019)    | 0 (0.000) |    14.22 | Kadzz, kenznk, levi, lukiz, pepe     |
|           30 |     2144 | 2024-04-27 | NIGERIA 96              | W   | 0.985      | 0.143        | 0.001 (0.000)    | 0.140 (0.020)    | -         |    14.24 | Kadzz, kenznk, levi, lukiz, pepe     |
|           29 |     2153 | 2024-04-27 | pugdesonesto            | W   | 0.985      | 0.143        | 0.001 (0.000)    | 0.146 (0.021)    | -         |    13.55 | Kadzz, kenznk, levi, lukiz, pepe     |
|           28 |     2163 | 2024-04-27 | Smoke Gaming            | L   | 0.984      | -            | -                | -                | -         |   -16.68 | Kadzz, kenznk, levi, lukiz, pepe     |
|           27 |     2171 | 2024-04-27 | FURIA Esports Female    | W   | 0.984      | 0.143        | 0.018 (0.003)    | 0.159 (0.022)    | -         |    21.88 | Kadzz, kenznk, levi, lukiz, pepe     |
|           26 |     2225 | 2024-04-26 | Hype Esports            | L   | 0.979      | -            | -                | -                | -         |   -15.66 | Kadzz, kenznk, levi, lukiz, pepe     |
|           25 |     2235 | 2024-04-26 | fear of god             | W   | 0.978      | -            | -                | -                | -         |     6.42 | Kadzz, kenznk, levi, lukiz, pepe     |
|           24 |     2345 | 2024-04-24 | Intense Game            | L   | 0.965      | -            | -                | -                | -         |   -11.42 | Kadzz, kenznk, levi, lukiz, pepe     |
|           23 |     3008 | 2024-04-13 | Dusty Roots             | L   | 0.891      | -            | -                | -                | -         |   -13.64 | Kadzz, kenznk, levi, lukiz, pepe     |
|           22 |     3012 | 2024-04-13 | paiN Gaming Academy     | W   | 0.891      | 0.143        | 0.005 (0.001)    | 0.374 (0.048)    | -         |    17.46 | Kadzz, kenznk, levi, lukiz, pepe     |
|           21 |     3057 | 2024-04-12 | bebidarosa              | W   | 0.885      | 0.143        | 0.001 (0.000)    | -                | -         |    14.96 | Kadzz, kenznk, levi, lukiz, pepe     |
|           20 |     3067 | 2024-04-12 | ODDIK Academy           | L   | 0.885      | -            | -                | -                | -         |   -14.73 | Kadzz, kenznk, levi, lukiz, pepe     |
|           19 |     4080 | 2024-03-21 | MIBR Academy            | L   | 0.738      | -            | -                | -                | -         |    -9.64 | Kadzz, kenznk, levi, lukiz, pepe     |
|           18 |     4126 | 2024-03-20 | Hawks                   | L   | 0.731      | -            | -                | -                | -         |   -10.61 | Kadzz, kenznk, levi, lukiz, pepe     |
|           17 |     4163 | 2024-03-19 | Bombril 1001 Utilidades | L   | 0.724      | -            | -                | -                | -         |   -11.23 | Kadzz, kenznk, levi, lukiz, pepe     |
|           16 |     4789 | 2024-03-07 | SoJoga                  | W   | 0.645      | -            | -                | -                | -         |    10.09 | Kadzz, kenznk, levi, lukiz, pepe     |
|           15 |     5254 | 2024-02-29 | Bombril 1001 Utilidades | L   | 0.598      | -            | -                | -                | -         |    -9.74 | Kadzz, kenznk, levi, lukiz, pepe     |
|           14 |     5312 | 2024-02-28 | Yawara E-Sports         | L   | 0.591      | -            | -                | -                | -         |    -8.64 | Kadzz, kenznk, levi, lukiz, pepe     |
|           13 |     5347 | 2024-02-27 | Intense Game            | L   | 0.585      | -            | -                | -                | -         |    -8.79 | Kadzz, kenznk, levi, lukiz, pepe     |
|           12 |     6396 | 2024-02-05 | THE FINALS              | W   | 0.439      | -            | -                | -                | -         |     2.40 | Kadzz, kenznk, levi, lukiz, pepe     |
|           11 |     7104 | 2024-01-24 | pugdesonesto            | W   | 0.358      | -            | -                | -                | -         |     5.10 | Kadzz, kenznk, levi, lukiz, pepe     |
|           10 |     7166 | 2024-01-23 | Bombril 1001 Utilidades | L   | 0.352      | -            | -                | -                | -         |    -6.55 | Kadzz, kenznk, levi, lukiz, pepe     |
|            9 |     7175 | 2024-01-23 | MIBR Academy            | L   | 0.351      | -            | -                | -                | -         |    -5.30 | Kadzz, kenznk, levi, lukiz, pepe     |
|            8 |     8377 | 2023-12-20 | TIMACETA                | W   | 0.125      | -            | -                | -                | -         |     1.71 | Kadzz, ksloks, levi, lukiz, pepe     |
|            7 |     8379 | 2023-12-20 | Intense Game            | W   | 0.124      | -            | -                | -                | -         |     1.59 | Kadzz, ksloks, levi, lukiz, pepe     |
|            6 |     8391 | 2023-12-19 | Bombril 1001 Utilidades | W   | 0.119      | -            | -                | -                | -         |     1.55 | Kadzz, ksloks, levi, lukiz, pepe     |
|            5 |     8448 | 2023-12-17 | Intense Game            | L   | 0.104      | -            | -                | -                | -         |    -1.96 | Kadzz, ksloks, levi, lukiz, pepe     |
|            4 |     8786 | 2023-12-14 | paiN Gaming Academy     | L   | 0.084      | -            | -                | -                | -         |    -1.60 | Kadzz, ksloks, levi, lukiz, pepe     |
|            3 |     8817 | 2023-12-13 | Intense Game            | W   | 0.078      | -            | -                | -                | -         |     0.99 | Kadzz, ksloks, levi, lukiz, pepe     |
|            2 |     8842 | 2023-12-13 | TIMACETA                | W   | 0.077      | -            | -                | -                | -         |     1.03 | Kadzz, ksloks, levi, lukiz, pepe     |
|            1 |     8863 | 2023-12-12 | Myth e-Sports           | W   | 0.072      | -            | -                | -                | -         |     0.94 | Kadzz, ksloks, levi, lukiz, pepe     |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($959.00)
- Divide that value by the 5th highest value among all rosters ($300,806.11)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-05-19 |      1.000 | $587.71        | $587.71         |
| 2024-05-01 |      1.000 | $115.49        | $115.49         |
| 2024-04-30 |      1.000 | $126.99        | $126.99         |
| 2023-12-20 |      0.125 | $1,027.05      | $128.81         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
