### Roster Details<br />
Team Name: Elevate<br />
Roster: dare, dea, Peeping, shane, snav<br />
Region: [Americas]( ../standings_americas.md)<br />
<br />
Global Rank: [118](../standings_global.md)<br />
Regional Rank: [20]( ../standings_americas.md)<br />
Final Rank Value:  825.4<br />
<br />
Final Rank Value (825.4) = Starting Rank Value (785.4) + Head To Head Adjustments (40.1)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.397[<sup>1</sup>](#table2)
- Bounty Collected: 0.299[<sup>2</sup>](#table1)
- Opponent Network: 0.081[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.194<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 785.4
- 400 + ( ( 0.194 - 0.000 ) / ( 0.806 - 0.000 ) ) * 1600 = 785.4


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent                   | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                           |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           33 |      553 | 2024-04-23 | Wildcard Gaming            | L   | 1.000      | -            | -                | -                | -         |   -13.49 | dare, dea, Peeping, shane, snav                  |
|           32 |      558 | 2024-04-23 | Wildcard Gaming            | W   | 1.000      | 0.477        | 0.025 (0.012)    | 0.483 (0.230)    | 0 (0.000) |    18.22 | dare, dea, Peeping, shane, snav                  |
|           31 |      858 | 2024-04-18 | Legacy                     | L   | 1.000      | -            | -                | -                | -         |    -3.85 | dare, dea, Peeping, shane, snav                  |
|           30 |      862 | 2024-04-18 | M80                        | L   | 1.000      | -            | -                | -                | -         |    -2.51 | dare, dea, Peeping, shane, snav                  |
|           29 |      912 | 2024-04-17 | Nouns Esports              | W   | 1.000      | 0.143        | -                | 0.475 (0.068)    | 0 (0.000) |    17.30 | dare, dea, Peeping, shane, snav                  |
|           28 |      917 | 2024-04-17 | Wildcard Gaming            | W   | 1.000      | 0.143        | 0.025 (0.004)    | 0.483 (0.069)    | 0 (0.000) |    20.29 | dare, dea, Peeping, shane, snav                  |
|           27 |      984 | 2024-04-16 | E-Xolos LAZER              | W   | 1.000      | -            | -                | -                | 0 (0.000) |     3.33 | dare, dea, Peeping, shane, snav                  |
|           26 |     1193 | 2024-04-10 | Nouns Esports              | L   | 1.000      | -            | -                | -                | -         |   -14.29 | dare, dea, Peeping, shane, snav                  |
|           25 |     1197 | 2024-04-10 | Nouns Esports              | L   | 1.000      | -            | -                | -                | -         |   -15.60 | dare, dea, Peeping, shane, snav                  |
|           24 |     1511 | 2024-04-03 | LAG Gaming (American team) | W   | 0.987      | 0.477        | 0.033 (0.016)    | 0.405 (0.191)    | 0 (0.000) |    19.47 | dare, dea, Peeping, shane, snav                  |
|           23 |     1513 | 2024-04-03 | LAG Gaming (American team) | L   | 0.987      | -            | -                | -                | -         |   -11.32 | dare, dea, Peeping, shane, snav                  |
|           22 |     2194 | 2024-03-15 | Carpe Diem                 | W   | 0.861      | 0.477        | 0.009 (0.004)    | 0.178 (0.073)    | 0 (0.000) |    10.08 | dare, dea, Peeping, shane, snav                  |
|           21 |     2196 | 2024-03-15 | Carpe Diem                 | W   | 0.861      | 0.477        | 0.009 (0.004)    | 0.178 (0.073)    | 0 (0.000) |    10.83 | dare, dea, Peeping, shane, snav                  |
|           20 |     2350 | 2024-03-12 | Clockwork                  | W   | 0.840      | -            | -                | -                | 0 (0.000) |     2.73 | dare, dea, Peeping, shane, snav                  |
|           19 |     2534 | 2024-03-08 | Team Spirit                | L   | 0.811      | -            | -                | -                | -         |    -0.06 | dare, MRC9, Peeping, shane, snav                 |
|           18 |     2842 | 2024-03-02 | ODDIK                      | L   | 0.772      | -            | -                | -                | -         |    -8.23 | dare, nbgee12, Peeping, shane, snav              |
|           17 |     2909 | 2024-03-01 | Complexity Gaming          | L   | 0.766      | -            | -                | -                | -         |    -0.44 | dare, nbgee12, Peeping, shane, snav              |
|           16 |     3188 | 2024-02-23 | LAG Gaming (American team) | L   | 0.721      | -            | -                | -                | -         |    -8.41 | dare, dea, Peeping, shane, snav                  |
|           15 |     3556 | 2024-02-15 | G3 (Asian team)            | L   | 0.667      | -            | -                | -                | -         |   -11.91 | dare, dea, Peeping, shane, snav                  |
|           14 |     4769 | 2024-01-16 | Team Liquid                | L   | 0.467      | -            | -                | -                | -         |    -0.58 | dare, dea, Peeping, shane, snav                  |
|           13 |     4773 | 2024-01-16 | Party Astronauts           | W   | 0.467      | 0.143        | 0.036 (0.002)    | 0.374 (0.025)    | 0 (0.000) |     7.36 | dare, dea, Peeping, shane, snav                  |
|           12 |     4823 | 2024-01-15 | Mythic                     | W   | 0.461      | 0.143        | -                | 0.380 (0.025)    | 0 (0.000) |     5.43 | Cooper, fl0m, freakazoid, hate, Trucklover86     |
|           11 |     4859 | 2024-01-14 | Party Astronauts           | W   | 0.454      | 0.143        | 0.036 (0.002)    | 0.374 (0.024)    | -         |     7.48 | dare, dea, Peeping, shane, snav                  |
|           10 |     4867 | 2024-01-14 | For Fun                    | W   | 0.453      | 0.143        | 0.014 (0.001)    | -                | -         |     6.62 | Momo, onter, Pluto, Tender, WOOHOO               |
|            9 |     4876 | 2024-01-13 | Team Liquid                | L   | 0.447      | -            | -                | -                | -         |    -0.49 | dare, dea, Peeping, shane, snav                  |
|            8 |     4905 | 2024-01-12 | LOS                        | W   | 0.442      | -            | -                | -                | -         |     2.62 | history, JOTA, leo_drk, short, t9rnay            |
|            7 |     5914 | 2023-12-06 | Evil Geniuses              | L   | 0.194      | -            | -                | -                | -         |    -4.08 | consti, dare, Fr3nk1e, shane, snav               |
|            6 |     5960 | 2023-12-05 | Mythic                     | W   | 0.187      | 0.500        | 0.003 (0.000)    | 0.380 (0.036)    | -         |     2.43 | Cooper, fl0m, freakazoid, Stewie2K, Trucklover86 |
|            5 |     6539 | 2023-11-22 | Take Flyte                 | W   | 0.101      | 0.500        | 0.004 (0.000)    | -                | -         |     1.30 | consti, dare, Fr3nk1e, shane, snav               |
|            4 |     7081 | 2023-11-10 | Nouns Esports              | W   | 0.020      | -            | -                | -                | -         |     0.26 | consti, dare, Fr3nk1e, shane, snav               |
|            3 |     7111 | 2023-11-09 | Carpe Diem                 | L   | 0.014      | -            | -                | -                | -         |    -0.25 | consti, dare, Fr3nk1e, shane, snav               |
|            2 |     7157 | 2023-11-08 | FLUFFY AIMERS              | L   | 0.007      | -            | -                | -                | -         |    -0.15 | consti, dare, Fr3nk1e, shane, snav               |
|            1 |     7220 | 2023-11-07 | Party Astronauts           | L   | 0.001      | -            | -                | -                | -         |    -0.01 | ben1337, chop, Grizz, PwnAlone, spek             |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($4,789.42)
- Divide that value by the 5th highest value among all rosters ($158,437.64)
- The final value (0.03) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-03-10 |      0.826 | $5,000.00      | $4,127.89       |
| 2023-12-10 |      0.221 | $3,000.00      | $661.53         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
