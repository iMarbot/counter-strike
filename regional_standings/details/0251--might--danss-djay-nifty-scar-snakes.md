### Roster Details<br />
Team Name: MIGHT<br />
Roster: danss, djay, Nifty, scar, Snakes<br />
Region: [Americas]( ../standings_americas.md)<br />
<br />
Global Rank: [251](../standings_global.md)<br />
Regional Rank: [48]( ../standings_americas.md)<br />
Final Rank Value:  662.7<br />
<br />
Final Rank Value (662.7) = Starting Rank Value (719.6) + Head To Head Adjustments (-56.9)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.284[<sup>1</sup>](#table2)
- Bounty Collected: 0.274[<sup>2</sup>](#table1)
- Opponent Network: 0.068[<sup>2</sup>](#table1)
- LAN Wins: 0.017[<sup>2</sup>](#table1)

The average of these factors is 0.161<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 719.6
- 400 + ( ( 0.161 - 0.000 ) / ( 0.806 - 0.000 ) ) * 1600 = 719.6


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
|           38 |     1194 | 2024-04-10 | Take Flyte                 | W   | 1.000      | 0.477        | 0.004 (0.002)    | 0.279 (0.133)    | false (0.000) |    19.98 | danss, djay, Nifty, scar, Snakes   |
|           37 |     1198 | 2024-04-10 | Take Flyte                 | L   | 1.000      | -            | -                | -                | -             |   -11.17 | danss, djay, Nifty, scar, Snakes   |
|           36 |     1262 | 2024-04-09 | Nouns Esports              | L   | 1.000      | -            | -                | -                | -             |    -9.87 | danss, djay, Nifty, scar, Snakes   |
|           35 |     1266 | 2024-04-09 | Nouns Esports              | L   | 1.000      | -            | -                | -                | -             |   -10.66 | danss, djay, Nifty, scar, Snakes   |
|           34 |     1457 | 2024-04-04 | Party Astronauts           | L   | 0.994      | -            | -                | -                | -             |    -8.04 | danss, djay, Nifty, scar, Snakes   |
|           33 |     1461 | 2024-04-04 | Party Astronauts           | L   | 0.994      | -            | -                | -                | -             |    -8.61 | danss, djay, Nifty, scar, Snakes   |
|           32 |     1712 | 2024-03-27 | Limitless                  | L   | 0.941      | -            | -                | -                | -             |   -15.44 | danss, djay, Nifty, scar, Snakes   |
|           31 |     1715 | 2024-03-27 | Limitless                  | L   | 0.941      | -            | -                | -                | -             |   -16.77 | danss, djay, Nifty, scar, Snakes   |
|           30 |     1779 | 2024-03-26 | NRG                        | L   | 0.934      | -            | -                | -                | -             |   -17.10 | danss, djay, Nifty, scar, Snakes   |
|           29 |     1783 | 2024-03-26 | NRG                        | L   | 0.934      | -            | -                | -                | -             |   -18.51 | danss, djay, Nifty, scar, Snakes   |
|           28 |     2353 | 2024-03-12 | Carpe Diem                 | L   | 0.840      | -            | -                | -                | -             |   -15.56 | danss, djay, Nifty, scar, Snakes   |
|           27 |     2592 | 2024-03-06 | LAG Gaming (American team) | L   | 0.801      | -            | -                | -                | -             |    -9.11 | danss, djay, Nifty, scar, Snakes   |
|           26 |     2594 | 2024-03-06 | LAG Gaming (American team) | W   | 0.801      | 0.477        | 0.033 (0.013)    | 0.405 (0.155)    | false (0.000) |    16.53 | danss, djay, Nifty, scar, Snakes   |
|           25 |     2661 | 2024-03-05 | Mythic                     | W   | 0.794      | 0.477        | 0.003 (0.001)    | 0.380 (0.144)    | false (0.000) |    10.94 | danss, djay, Nifty, scar, Snakes   |
|           24 |     2664 | 2024-03-05 | Mythic                     | W   | 0.794      | 0.477        | 0.003 (0.001)    | 0.380 (0.144)    | false (0.000) |    11.73 | danss, djay, Nifty, scar, Snakes   |
|           23 |     3193 | 2024-02-23 | Wildcard Gaming            | L   | 0.721      | -            | -                | -                | -             |    -6.41 | danss, djay, Nifty, scar, Snakes   |
|           22 |     3228 | 2024-02-22 | Team Liquid                | L   | 0.714      | -            | -                | -                | -             |    -0.57 | danss, djay, Nifty, scar, Snakes   |
|           21 |     3231 | 2024-02-22 | Take Flyte                 | W   | 0.713      | 0.143        | 0.004 (0.000)    | 0.279 (0.028)    | false (0.000) |    10.42 | danss, djay, Nifty, scar, Snakes   |
|           20 |     3273 | 2024-02-21 | Carpe Diem                 | W   | 0.707      | 0.143        | 0.009 (0.001)    | 0.178 (0.018)    | false (0.000) |     9.38 | danss, djay, Nifty, scar, Snakes   |
|           19 |     3515 | 2024-02-16 | Rocket                     | L   | 0.673      | -            | -                | -                | -             |   -10.50 | danss, djay, Nifty, scar, Snakes   |
|           18 |     4413 | 2024-01-23 | Wildcard Gaming            | L   | 0.515      | -            | -                | -                | -             |    -4.90 | CLASIA, danss, djay, Nifty, scar   |
|           17 |     4414 | 2024-01-23 | LOS                        | W   | 0.514      | -            | -                | -                | false (0.000) |     3.70 | CLASIA, danss, djay, Nifty, scar   |
|           16 |     4639 | 2024-01-18 | Wildcard Gaming            | L   | 0.480      | -            | -                | -                | -             |    -4.98 | danss, djay, Louie, Nifty, scar    |
|           15 |     4684 | 2024-01-17 | Party Astronauts           | W   | 0.474      | 0.143        | 0.036 (0.002)    | 0.374 (0.025)    | false (0.000) |     8.69 | danss, djay, Louie, Nifty, scar    |
|           14 |     4825 | 2024-01-15 | Carpe Diem                 | W   | 0.460      | 0.143        | 0.009 (0.001)    | 0.178 (0.012)    | false (0.000) |     6.70 | danss, djay, Louie, Nifty, scar    |
|           13 |     5020 | 2024-01-10 | Zomblers                   | W   | 0.428      | 0.143        | 0.007 (0.000)    | -                | -             |     5.82 | danss, djay, Nifty, scar, stamina  |
|           12 |     5333 | 2023-12-17 | Rocket                     | W   | 0.268      | 0.143        | -                | 0.246 (0.009)    | -             |     3.62 | djay, Louie, Nifty, scar, stamina  |
|           11 |     5337 | 2023-12-17 | LAG Gaming (American team) | W   | 0.267      | 0.143        | 0.033 (0.001)    | 0.405 (0.015)    | -             |     6.68 | djay, Louie, Nifty, scar, stamina  |
|           10 |     5425 | 2023-12-16 | Pantsu                     | W   | 0.261      | -            | -                | -                | -             |     3.41 | djay, Louie, Nifty, scar, stamina  |
|            9 |     5562 | 2023-12-15 | Bad News Bears             | L   | 0.254      | -            | -                | -                | -             |    -6.30 | djay, Louie, Nifty, scar, stamina  |
|            8 |     5708 | 2023-12-10 | Revenge Nation             | L   | 0.221      | -            | -                | -                | -             |    -3.39 | djay, Louie, Nifty, scar, stamina  |
|            7 |     5751 | 2023-12-09 | Villainous                 | W   | 0.214      | -            | -                | -                | -             |     2.11 | djay, Louie, Nifty, scar, stamina  |
|            6 |     5860 | 2023-12-07 | Zero MarksMen              | W   | 0.201      | -            | -                | -                | -             |     0.89 | djay, Louie, Nifty, scar, stamina  |
|            5 |     5910 | 2023-12-06 | LAG Gaming (American team) | L   | 0.194      | -            | -                | -                | -             |    -1.23 | djay, Louie, Nifty, scar, stamina  |
|            4 |     5957 | 2023-12-05 | Spectre Tavius             | W   | 0.187      | -            | -                | -                | -             |     0.84 | djay, Louie, Nifty, scar, stamina  |
|            3 |     6180 | 2023-11-30 | Xmplfy                     | W   | 0.154      | -            | -                | -                | true (0.154)  |     0.69 | danss, djay, Nifty, scar, stamina  |
|            2 |     6905 | 2023-11-14 | M80                        | L   | 0.047      | -            | -                | -                | -             |    -0.06 | CLASIA, djay, Nifty, scar, stamina |
|            1 |     6944 | 2023-11-13 | Classless                  | W   | 0.041      | -            | -                | -                | -             |     0.18 | CLASIA, djay, Nifty, scar, stamina |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($481.85)
- Divide that value by the 5th highest value among all rosters ($158,437.64)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
