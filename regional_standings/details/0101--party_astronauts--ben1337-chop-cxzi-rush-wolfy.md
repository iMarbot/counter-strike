### Roster Details<br />
Team Name: Party Astronauts<br />
Roster: ben1337, chop, cxzi, RUSH, WolfY<br />
Region: [Americas]( ../standings_americas.md)<br />
<br />
Global Rank: [101](../standings_global.md)<br />
Regional Rank: [17]( ../standings_americas.md)<br />
Final Rank Value:  863.9<br />
<br />
Final Rank Value (863.9) = Starting Rank Value (803.6) + Head To Head Adjustments (60.4)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.410[<sup>1</sup>](#table2)
- Bounty Collected: 0.300[<sup>2</sup>](#table1)
- Opponent Network: 0.104[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.203<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 803.6
- 400 + ( ( 0.203 - 0.000 ) / ( 0.806 - 0.000 ) ) * 1600 = 803.6


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent                   | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins      | H2H Adj. | Roster                             |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           46 |      128 | 2024-05-02 | Wildcard Gaming            | L   | 1.000      | -            | -                | -                | -             |   -15.70 | ben1337, chop, cxzi, RUSH, WolfY   |
|           45 |      129 | 2024-05-02 | Wildcard Gaming            | W   | 1.000      | 0.477        | 0.025 (0.012)    | 0.483 (0.230)    | false (0.000) |    15.80 | ben1337, chop, cxzi, RUSH, WolfY   |
|           44 |      393 | 2024-04-27 | Aurora Gaming              | L   | 1.000      | -            | -                | -                | -             |    -1.01 | ben1337, chop, cxzi, RUSH, WolfY   |
|           43 |      456 | 2024-04-25 | Aurora Gaming              | L   | 1.000      | -            | -                | -                | -             |    -0.91 | ben1337, chop, cxzi, RUSH, WolfY   |
|           42 |      988 | 2024-04-16 | G3 (Asian team)            | L   | 1.000      | -            | -                | -                | -             |   -21.14 | ben1337, chop, cxzi, RUSH, WolfY   |
|           41 |     1264 | 2024-04-09 | One More Esports           | W   | 1.000      | 0.477        | 0.011 (0.005)    | 0.147 (0.070)    | false (0.000) |     7.16 | ben1337, chop, cxzi, RUSH, WolfY   |
|           40 |     1268 | 2024-04-09 | One More Esports           | W   | 1.000      | 0.477        | 0.011 (0.005)    | 0.147 (0.070)    | false (0.000) |     7.62 | ben1337, chop, cxzi, RUSH, WolfY   |
|           39 |     1457 | 2024-04-04 | MIGHT                      | W   | 0.994      | 0.477        | -                | 0.213 (0.101)    | false (0.000) |     8.04 | ben1337, chop, cxzi, RUSH, WolfY   |
|           38 |     1461 | 2024-04-04 | MIGHT                      | W   | 0.994      | 0.477        | -                | 0.213 (0.101)    | false (0.000) |     8.61 | ben1337, chop, cxzi, RUSH, WolfY   |
|           37 |     1509 | 2024-04-03 | Nouns Esports              | W   | 0.988      | 0.143        | -                | 0.475 (0.067)    | false (0.000) |    12.67 | ben1337, chop, cxzi, RUSH, WolfY   |
|           36 |     1519 | 2024-04-03 | BOSS                       | W   | 0.986      | 0.143        | 0.051 (0.007)    | -                | false (0.000) |    17.74 | ben1337, chop, cxzi, RUSH, WolfY   |
|           35 |     1563 | 2024-04-02 | Take Flyte                 | W   | 0.981      | -            | -                | -                | false (0.000) |    10.49 | ben1337, chop, cxzi, RUSH, WolfY   |
|           34 |     1568 | 2024-04-02 | Nouns Esports              | L   | 0.980      | -            | -                | -                | -             |   -18.24 | ben1337, chop, cxzi, RUSH, WolfY   |
|           33 |     1711 | 2024-03-27 | Carpe Diem                 | W   | 0.941      | 0.477        | 0.009 (0.004)    | 0.178 (0.080)    | false (0.000) |     9.30 | ben1337, chop, cxzi, RUSH, WolfY   |
|           32 |     1714 | 2024-03-27 | Carpe Diem                 | W   | 0.941      | 0.477        | 0.009 (0.004)    | 0.178 (0.080)    | false (0.000) |    10.00 | ben1337, chop, cxzi, RUSH, WolfY   |
|           31 |     1778 | 2024-03-26 | Nouns Esports              | L   | 0.934      | -            | -                | -                | -             |   -17.83 | ben1337, chop, cxzi, RUSH, WolfY   |
|           30 |     1782 | 2024-03-26 | Nouns Esports              | L   | 0.934      | -            | -                | -                | -             |   -19.26 | ben1337, chop, cxzi, RUSH, WolfY   |
|           29 |     2038 | 2024-03-19 | Take Flyte                 | W   | 0.888      | 0.477        | 0.004 (0.002)    | 0.279 (0.118)    | -             |     8.78 | ben1337, chop, cxzi, RUSH, WolfY   |
|           28 |     2039 | 2024-03-19 | Take Flyte                 | W   | 0.887      | 0.477        | -                | 0.279 (0.118)    | -             |     9.41 | ben1337, chop, cxzi, RUSH, WolfY   |
|           27 |     3117 | 2024-02-24 | Wildcard Gaming            | L   | 0.727      | -            | -                | -                | -             |    -8.61 | ben1337, chop, cxzi, Walco, WolfY  |
|           26 |     3190 | 2024-02-23 | E-Xolos LAZER              | W   | 0.721      | -            | -                | -                | -             |     1.87 | ben1337, chop, cxzi, Walco, WolfY  |
|           25 |     3227 | 2024-02-22 | Team Liquid                | L   | 0.714      | -            | -                | -                | -             |    -0.93 | ben1337, chop, cxzi, Walco, WolfY  |
|           24 |     3232 | 2024-02-22 | One More Esports           | W   | 0.713      | -            | -                | -                | -             |     7.67 | ben1337, chop, cxzi, Walco, WolfY  |
|           23 |     3275 | 2024-02-21 | LAG Gaming (American team) | W   | 0.707      | 0.143        | 0.033 (0.003)    | -                | -             |    13.45 | ben1337, chop, cxzi, Walco, WolfY  |
|           22 |     3334 | 2024-02-20 | Mythic                     | W   | 0.700      | -            | -                | -                | -             |     8.61 | ben1337, chop, cxzi, Walco, WolfY  |
|           21 |     3394 | 2024-02-19 | G3 (Asian team)            | W   | 0.693      | -            | -                | -                | -             |     9.67 | ben1337, chop, cxzi, Walco, WolfY  |
|           20 |     4006 | 2024-02-02 | Carpe Diem                 | W   | 0.580      | -            | -                | -                | -             |     6.40 | ben1337, chop, cxzi, viz, WolfY    |
|           19 |     4684 | 2024-01-17 | MIGHT                      | L   | 0.474      | -            | -                | -                | -             |    -8.69 | ben1337, chop, cxzi, viz, WolfY    |
|           18 |     4773 | 2024-01-16 | Elevate                    | L   | 0.467      | -            | -                | -                | -             |    -7.36 | ben1337, chop, cxzi, viz, WolfY    |
|           17 |     4822 | 2024-01-15 | Zomblers                   | W   | 0.461      | -            | -                | -                | -             |     4.66 | ben1337, chop, cxzi, viz, WolfY    |
|           16 |     4859 | 2024-01-14 | Elevate                    | L   | 0.454      | -            | -                | -                | -             |    -7.48 | ben1337, chop, cxzi, viz, WolfY    |
|           15 |     4863 | 2024-01-14 | Team Liquid                | L   | 0.454      | -            | -                | -                | -             |    -0.57 | ben1337, chop, cxzi, viz, WolfY    |
|           14 |     4874 | 2024-01-13 | Complexity Gaming          | L   | 0.447      | -            | -                | -                | -             |    -0.25 | ben1337, chop, cxzi, viz, WolfY    |
|           13 |     4911 | 2024-01-12 | Carpe Diem                 | W   | 0.442      | -            | -                | -                | -             |     5.41 | ben1337, chop, cxzi, viz, WolfY    |
|           12 |     5681 | 2023-12-11 | BOSS                       | L   | 0.228      | -            | -                | -                | -             |    -2.70 | ben1337, chop, cxzi, PwnAlone, viz |
|           11 |     5756 | 2023-12-09 | BOSS                       | L   | 0.214      | -            | -                | -                | -             |    -2.58 | ben1337, chop, cxzi, PwnAlone, viz |
|           10 |     5825 | 2023-12-08 | Nouns Esports              | W   | 0.207      | 0.500        | 0.016 (0.002)    | -                | -             |     2.50 | ben1337, chop, cxzi, PwnAlone, viz |
|            9 |     5863 | 2023-12-07 | Evil Geniuses              | W   | 0.201      | -            | -                | -                | -             |     1.97 | ben1337, chop, cxzi, PwnAlone, viz |
|            8 |     5915 | 2023-12-06 | M80                        | L   | 0.194      | -            | -                | -                | -             |    -0.37 | ben1337, chop, cxzi, PwnAlone, viz |
|            7 |     5961 | 2023-12-05 | Carpe Diem                 | W   | 0.187      | -            | -                | -                | -             |     2.34 | ben1337, chop, cxzi, PwnAlone, viz |
|            6 |     6536 | 2023-11-22 | BOSS                       | W   | 0.101      | 0.500        | 0.051 (0.003)    | -                | -             |     2.00 | ben1337, chop, cxzi, PwnAlone, viz |
|            5 |     6577 | 2023-11-21 | Mythic                     | W   | 0.094      | -            | -                | -                | -             |     1.15 | ben1337, chop, cxzi, PwnAlone, viz |
|            4 |     6800 | 2023-11-16 | M80                        | L   | 0.059      | -            | -                | -                | -             |    -0.11 | ben1337, chop, cxzi, PwnAlone, viz |
|            3 |     6854 | 2023-11-15 | NRG                        | L   | 0.054      | -            | -                | -                | -             |    -1.25 | ben1337, chop, cxzi, PwnAlone, viz |
|            2 |     6859 | 2023-11-15 | M80                        | W   | 0.053      | -            | -                | -                | -             |     1.56 | ben1337, chop, cxzi, PwnAlone, viz |
|            1 |     6949 | 2023-11-13 | Take Flyte                 | W   | 0.041      | -            | -                | -                | -             |     0.49 | ben1337, chop, cxzi, PwnAlone, viz |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($5,756.37)
- Divide that value by the 5th highest value among all rosters ($158,437.64)
- The final value (0.04) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-04-28 |      1.000 | $3,000.00      | $3,000.00       |
| 2023-12-10 |      0.221 | $12,500.00     | $2,756.37       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
