### Roster Details<br />
Team Name: Carpe Diem<br />
Roster: arcade, Lake, micro, Seb, wiz<br />
Region: [Americas]( ../standings_americas.md)<br />
<br />
Global Rank: [274](../standings_global.md)<br />
Regional Rank: [56]( ../standings_americas.md)<br />
Final Rank Value:  638.2<br />
<br />
Final Rank Value (638.2) = Starting Rank Value (727.6) + Head To Head Adjustments (-89.4)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.328[<sup>1</sup>](#table2)
- Bounty Collected: 0.234[<sup>2</sup>](#table1)
- Opponent Network: 0.043[<sup>2</sup>](#table1)
- LAN Wins: 0.055[<sup>2</sup>](#table1)

The average of these factors is 0.165<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 727.6
- 400 + ( ( 0.165 - 0.000 ) / ( 0.806 - 0.000 ) ) * 1600 = 727.6


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
|           39 |     1158 | 2024-04-11 | Mythic                     | W   | 1.000      | 0.477        | 0.003 (0.001)    | 0.380 (0.181)    | false (0.000) |    19.02 | arcade, Lake, micro, Seb, wiz                    |
|           38 |     1161 | 2024-04-11 | Mythic                     | L   | 1.000      | -            | -                | -                | -             |   -12.20 | arcade, Lake, micro, Seb, wiz                    |
|           37 |     1265 | 2024-04-09 | NRG                        | L   | 1.000      | -            | -                | -                | -             |   -12.61 | arcade, Lake, micro, Seb, wiz                    |
|           36 |     1269 | 2024-04-09 | NRG                        | L   | 1.000      | -            | -                | -                | -             |   -13.74 | arcade, Lake, micro, Seb, wiz                    |
|           35 |     1458 | 2024-04-04 | Take Flyte                 | L   | 0.994      | -            | -                | -                | -             |   -12.23 | arcade, Lake, micro, Seb, wiz                    |
|           34 |     1462 | 2024-04-04 | Take Flyte                 | L   | 0.994      | -            | -                | -                | -             |   -13.31 | arcade, Lake, micro, Seb, wiz                    |
|           33 |     1711 | 2024-03-27 | Party Astronauts           | L   | 0.941      | -            | -                | -                | -             |    -9.30 | arcade, Lake, micro, Seb, wiz                    |
|           32 |     1714 | 2024-03-27 | Party Astronauts           | L   | 0.941      | -            | -                | -                | -             |   -10.00 | arcade, Lake, micro, Seb, wiz                    |
|           31 |     2194 | 2024-03-15 | Elevate                    | L   | 0.861      | -            | -                | -                | -             |   -10.08 | arcade, Lake, micro, Seb, wiz                    |
|           30 |     2196 | 2024-03-15 | Elevate                    | L   | 0.861      | -            | -                | -                | -             |   -10.83 | arcade, Lake, micro, Seb, wiz                    |
|           29 |     2349 | 2024-03-12 | NRG                        | W   | 0.841      | 0.143        | 0.000 (0.000)    | 0.303 (0.036)    | false (0.000) |     9.82 | arcade, Lake, micro, Seb, wiz                    |
|           28 |     2353 | 2024-03-12 | MIGHT                      | W   | 0.840      | 0.143        | 0.003 (0.000)    | 0.213 (0.026)    | false (0.000) |    15.56 | arcade, Lake, micro, Seb, wiz                    |
|           27 |     2591 | 2024-03-06 | Limitless                  | W   | 0.801      | 0.477        | 0.001 (0.000)    | 0.177 (0.067)    | false (0.000) |    12.68 | arcade, Lake, micro, Seb, wiz                    |
|           26 |     2593 | 2024-03-06 | Limitless                  | W   | 0.801      | 0.477        | 0.001 (0.000)    | 0.177 (0.067)    | false (0.000) |    13.61 | arcade, Lake, micro, Seb, wiz                    |
|           25 |     3273 | 2024-02-21 | MIGHT                      | L   | 0.707      | -            | -                | -                | -             |    -9.38 | arcade, DJF, Lake, micro, wiz                    |
|           24 |     4006 | 2024-02-02 | Party Astronauts           | L   | 0.580      | -            | -                | -                | -             |    -6.40 | arcade, Lake, Seb, Walco, wiz                    |
|           23 |     4009 | 2024-02-02 | Wildcard Gaming            | L   | 0.579      | -            | -                | -                | -             |    -4.24 | arcade, Lake, Seb, Walco, wiz                    |
|           22 |     4295 | 2024-01-26 | LOS                        | W   | 0.534      | 0.143        | -                | 0.064 (0.005)    | false (0.000) |     5.02 | arcade, Lake, Seb, Walco, wiz                    |
|           21 |     4419 | 2024-01-23 | Team Lampa                 | L   | 0.514      | -            | -                | -                | -             |   -12.18 | arcade, Lake, Seb, Walco, wiz                    |
|           20 |     4638 | 2024-01-18 | Rocket                     | L   | 0.480      | -            | -                | -                | -             |    -7.21 | Lake, Seb, Walco, wiz, Wolffe                    |
|           19 |     4687 | 2024-01-17 | LOS                        | W   | 0.474      | 0.143        | -                | 0.064 (0.004)    | false (0.000) |     4.12 | Lake, Seb, Walco, wiz, Wolffe                    |
|           18 |     4825 | 2024-01-15 | MIGHT                      | L   | 0.460      | -            | -                | -                | -             |    -6.70 | Lake, Seb, Walco, wiz, Wolffe                    |
|           17 |     4858 | 2024-01-14 | Nouns Esports              | L   | 0.455      | -            | -                | -                | -             |    -8.70 | Lake, Seb, Walco, wiz, Wolffe                    |
|           16 |     4877 | 2024-01-13 | Rocket                     | L   | 0.447      | -            | -                | -                | -             |    -7.29 | Lake, Seb, Walco, wiz, Wolffe                    |
|           15 |     4911 | 2024-01-12 | Party Astronauts           | L   | 0.442      | -            | -                | -                | -             |    -5.41 | Lake, Seb, Walco, wiz, Wolffe                    |
|           14 |     4913 | 2024-01-12 | LOS                        | W   | 0.441      | -            | -                | -                | -             |     3.42 | Lake, Seb, Walco, wiz, Wolffe                    |
|           13 |     5339 | 2023-12-17 | Nouns Esports              | L   | 0.267      | -            | -                | -                | -             |    -4.22 | Cyrix, Lake, micro, Seb, Wolffe                  |
|           12 |     5429 | 2023-12-16 | We Go Hard                 | W   | 0.260      | -            | -                | -                | -             |     1.11 | Dodge, goro, myth, Oczarka, Scorchyy             |
|           11 |     5862 | 2023-12-07 | Nouns Esports              | L   | 0.201      | -            | -                | -                | -             |    -3.24 | arcade, Cyrix, Lake, Seb, Wolffe                 |
|           10 |     5913 | 2023-12-06 | FLUFFY AIMERS              | W   | 0.194      | 0.500        | 0.004 (0.000)    | 0.103 (0.010)    | -             |     2.61 | dea, Jason, LEARSI, Peeping, sacrifice           |
|            9 |     5961 | 2023-12-05 | Party Astronauts           | L   | 0.187      | -            | -                | -                | -             |    -2.34 | ben1337, chop, cxzi, PwnAlone, viz               |
|            8 |     6028 | 2023-12-03 | LAG Gaming (American team) | W   | 0.173      | 0.333        | 0.033 (0.002)    | 0.405 (0.023)    | true (0.173)  |     4.33 | based, Experative, Nyyx, ogwizard, X-23          |
|            7 |     6080 | 2023-12-02 | Revel                      | W   | 0.167      | -            | -                | -                | true (0.167)  |     0.76 | BATSPEED, blessA, Jachro, KaJohnRay, P3nny       |
|            6 |     6181 | 2023-11-30 | The Worm Clan              | W   | 0.154      | -            | -                | -                | true (0.154)  |     0.67 | AlerT, JazzPimp, Reality, retrQ, Welshy          |
|            5 |     6540 | 2023-11-22 | Mythic                     | L   | 0.101      | -            | -                | -                | -             |    -1.61 | Cooper, fl0m, freakazoid, Stewie2K, Trucklover86 |
|            4 |     6855 | 2023-11-15 | Rocket                     | W   | 0.054      | 0.500        | 0.002 (0.000)    | 0.246 (0.007)    | -             |     0.71 | aleph, droid, Elk, nero, R2D2J                   |
|            3 |     6908 | 2023-11-14 | Wildcard Gaming            | L   | 0.047      | -            | -                | -                | -             |    -0.49 | arcade, Cyrix, Lake, Seb, Wolffe                 |
|            2 |     6945 | 2023-11-13 | Revenge Nation             | W   | 0.041      | 0.143        | 0.043 (0.000)    | -                | -             |     0.64 | HorizoN, NIGHT666LADE, Rulik, S0ph3R, TABEN      |
|            1 |     7111 | 2023-11-09 | Elevate                    | W   | 0.014      | 0.500        | 0.030 (0.000)    | -                | -             |     0.25 | consti, dare, Fr3nk1e, shane, snav               |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($1,424.81)
- Divide that value by the 5th highest value among all rosters ($158,437.64)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2023-12-10 |      0.221 | $4,500.00      | $992.29         |
| 2023-12-03 |      0.173 | $2,500.00      | $432.52         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
