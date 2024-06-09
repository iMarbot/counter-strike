### Roster Details<br />
Team Name: MIGHT<br />
Roster: djay, Fr3nk1e, Nifty, scar, Snakes<br />
Region: [Americas]( ../standings_americas.md)<br />
<br />
Global Rank: [331](../standings_global.md)<br />
Regional Rank: [78]( ../standings_americas.md)<br />
Final Rank Value:  620.7<br />
<br />
Final Rank Value (620.7) = Starting Rank Value (683.0) + Head To Head Adjustments (-62.3)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.234[<sup>1</sup>](#table2)
- Bounty Collected: 0.259[<sup>2</sup>](#table1)
- Opponent Network: 0.064[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.139<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 683.0
- 400 + ( ( 0.139 - 0.000 ) / ( 0.787 - 0.000 ) ) * 1600 = 683.0


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent            | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                             |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           56 |      435 | 2024-05-22 | Carpe Diem          | L   | 1.000      | -            | -                | -                | -         |   -10.80 | djay, Fr3nk1e, Nifty, scar, Snakes |
|           55 |      438 | 2024-05-22 | Carpe Diem          | L   | 1.000      | -            | -                | -                | -         |   -11.72 | djay, Fr3nk1e, Nifty, scar, Snakes |
|           54 |      640 | 2024-05-20 | One More Esports    | L   | 1.000      | -            | -                | -                | -         |   -13.86 | djay, Fr3nk1e, Nifty, scar, Snakes |
|           53 |      644 | 2024-05-20 | One More Esports    | W   | 1.000      | 0.477        | 0.005 (0.002)    | 0.166 (0.079)    | 0 (0.000) |    17.81 | djay, Fr3nk1e, Nifty, scar, Snakes |
|           52 |     1033 | 2024-05-16 | Legacy              | L   | 1.000      | -            | -                | -                | -         |    -2.32 | djay, Fr3nk1e, Nifty, scar, Snakes |
|           51 |     1040 | 2024-05-16 | Revenge Nation      | W   | 1.000      | 0.143        | 0.019 (0.003)    | 0.186 (0.027)    | 0 (0.000) |    20.45 | djay, Fr3nk1e, Nifty, scar, Snakes |
|           50 |     1047 | 2024-05-16 | Perseverance Gaming | W   | 1.000      | -            | -                | -                | 0 (0.000) |     7.08 | djay, Fr3nk1e, Nifty, scar, Snakes |
|           49 |     1120 | 2024-05-15 | FLUFFY AIMERS       | L   | 1.000      | -            | -                | -                | -         |    -6.86 | djay, Fr3nk1e, Nifty, scar, Snakes |
|           48 |     1133 | 2024-05-15 | FLUFFY AIMERS       | L   | 1.000      | -            | -                | -                | -         |    -7.29 | djay, Fr3nk1e, Nifty, scar, Snakes |
|           47 |     1228 | 2024-05-14 | BOSS                | L   | 1.000      | -            | -                | -                | -         |    -7.20 | djay, Fr3nk1e, Nifty, scar, Snakes |
|           46 |     1235 | 2024-05-14 | BOSS                | L   | 1.000      | -            | -                | -                | -         |    -7.67 | djay, Fr3nk1e, Nifty, scar, Snakes |
|           45 |     1559 | 2024-05-09 | Wildcard Gaming     | L   | 1.000      | -            | -                | -                | -         |    -4.84 | djay, Fr3nk1e, Nifty, scar, Snakes |
|           44 |     1560 | 2024-05-09 | Wildcard Gaming     | L   | 1.000      | -            | -                | -                | -         |    -5.07 | djay, Fr3nk1e, Nifty, scar, Snakes |
|           43 |     1603 | 2024-05-08 | Elevate             | L   | 1.000      | -            | -                | -                | -         |    -6.08 | djay, Fr3nk1e, Nifty, scar, Snakes |
|           42 |     1607 | 2024-05-08 | Elevate             | L   | 1.000      | -            | -                | -                | -         |    -6.43 | djay, Fr3nk1e, Nifty, scar, Snakes |
|           41 |     3209 | 2024-04-10 | Take Flyte          | W   | 0.873      | 0.477        | 0.006 (0.002)    | 0.354 (0.147)    | 0 (0.000) |    18.59 | danss, djay, Nifty, scar, Snakes   |
|           40 |     3214 | 2024-04-10 | Take Flyte          | L   | 0.873      | -            | -                | -                | -         |    -8.69 | danss, djay, Nifty, scar, Snakes   |
|           39 |     3291 | 2024-04-09 | Nouns Esports       | L   | 0.866      | -            | -                | -                | -         |    -4.25 | danss, djay, Nifty, scar, Snakes   |
|           38 |     3295 | 2024-04-09 | Nouns Esports       | L   | 0.866      | -            | -                | -                | -         |    -4.42 | danss, djay, Nifty, scar, Snakes   |
|           37 |     3547 | 2024-04-04 | Party Astronauts    | L   | 0.833      | -            | -                | -                | -         |    -3.76 | danss, djay, Nifty, scar, Snakes   |
|           36 |     3551 | 2024-04-04 | Party Astronauts    | L   | 0.833      | -            | -                | -                | -         |    -3.90 | danss, djay, Nifty, scar, Snakes   |
|           35 |     3854 | 2024-03-27 | Limitless           | L   | 0.780      | -            | -                | -                | -         |   -11.57 | danss, djay, Nifty, scar, Snakes   |
|           34 |     3858 | 2024-03-27 | Limitless           | L   | 0.780      | -            | -                | -                | -         |   -12.40 | danss, djay, Nifty, scar, Snakes   |
|           33 |     3934 | 2024-03-26 | NRG                 | L   | 0.773      | -            | -                | -                | -         |    -6.58 | danss, djay, Nifty, scar, Snakes   |
|           32 |     3939 | 2024-03-26 | NRG                 | L   | 0.773      | -            | -                | -                | -         |    -6.95 | danss, djay, Nifty, scar, Snakes   |
|           31 |     4651 | 2024-03-12 | Carpe Diem          | L   | 0.679      | -            | -                | -                | -         |   -12.63 | danss, djay, Nifty, scar, Snakes   |
|           30 |     4966 | 2024-03-06 | LAG Gaming          | L   | 0.640      | -            | -                | -                | -         |    -5.30 | danss, djay, Nifty, scar, Snakes   |
|           29 |     4968 | 2024-03-06 | LAG Gaming          | W   | 0.640      | 0.477        | 0.013 (0.004)    | 0.335 (0.102)    | 0 (0.000) |    15.22 | danss, djay, Nifty, scar, Snakes   |
|           28 |     5058 | 2024-03-05 | Mythic              | W   | 0.633      | 0.477        | 0.000 (0.000)    | 0.339 (0.102)    | 0 (0.000) |    11.27 | danss, djay, Nifty, scar, Snakes   |
|           27 |     5066 | 2024-03-05 | Mythic              | W   | 0.633      | 0.477        | 0.000 (0.000)    | 0.339 (0.102)    | 0 (0.000) |    11.90 | danss, djay, Nifty, scar, Snakes   |
|           26 |     5745 | 2024-02-23 | Wildcard Gaming     | L   | 0.560      | -            | -                | -                | -         |    -3.92 | danss, djay, Nifty, scar, Snakes   |
|           25 |     5786 | 2024-02-22 | Team Liquid         | L   | 0.553      | -            | -                | -                | -         |    -0.08 | danss, djay, Nifty, scar, Snakes   |
|           24 |     5791 | 2024-02-22 | Take Flyte          | W   | 0.552      | 0.143        | 0.006 (0.000)    | 0.354 (0.028)    | 0 (0.000) |    10.99 | danss, djay, Nifty, scar, Snakes   |
|           23 |     5839 | 2024-02-21 | Carpe Diem          | W   | 0.546      | 0.143        | -                | 0.243 (0.019)    | 0 (0.000) |     7.48 | danss, djay, Nifty, scar, Snakes   |
|           22 |     6140 | 2024-02-16 | Rocket              | L   | 0.512      | -            | -                | -                | -         |    -9.65 | danss, djay, Nifty, scar, Snakes   |
|           21 |     6191 | 2024-02-15 | Snakes Den Gaming   | W   | 0.506      | -            | -                | -                | 0 (0.000) |     4.71 | danss, djay, Nifty, scar, Snakes   |
|           20 |     7230 | 2024-01-26 | ex-CatEvil          | L   | 0.373      | -            | -                | -                | -         |    -7.24 | danss, djay, louie, Nifty, scar    |
|           19 |     7389 | 2024-01-23 | Wildcard Gaming     | L   | 0.353      | -            | -                | -                | -         |    -2.48 | CLASIA, danss, djay, Nifty, scar   |
|           18 |     7390 | 2024-01-23 | LOS                 | W   | 0.353      | -            | -                | -                | -         |     3.16 | CLASIA, danss, djay, Nifty, scar   |
|           17 |     7697 | 2024-01-18 | Wildcard Gaming     | L   | 0.319      | -            | -                | -                | -         |    -2.44 | danss, djay, Louie, Nifty, scar    |
|           16 |     7751 | 2024-01-17 | Party Astronauts    | W   | 0.313      | 0.143        | 0.031 (0.001)    | 0.545 (0.024)    | -         |     7.92 | danss, djay, Louie, Nifty, scar    |
|           15 |     7863 | 2024-01-16 | huge sweaty         | L   | 0.306      | -            | -                | -                | -         |    -7.24 | danss, djay, Louie, Nifty, scar    |
|           14 |     7948 | 2024-01-15 | Carpe Diem          | W   | 0.299      | 0.143        | -                | 0.243 (0.010)    | -         |     4.09 | danss, djay, Louie, Nifty, scar    |
|           13 |     8158 | 2024-01-11 | The Nomads          | L   | 0.273      | -            | -                | -                | -         |    -6.56 | danss, djay, Nifty, scar, stamina  |
|           12 |     8222 | 2024-01-10 | Zomblers            | W   | 0.267      | 0.143        | 0.003 (0.000)    | -                | -         |     3.75 | danss, djay, Nifty, scar, stamina  |
|           11 |     8681 | 2023-12-17 | Rocket              | W   | 0.107      | -            | -                | -                | -         |     0.97 | djay, Louie, Nifty, scar, stamina  |
|           10 |     8687 | 2023-12-17 | LAG Gaming          | W   | 0.106      | 0.143        | 0.013 (0.000)    | -                | -         |     2.73 | djay, Louie, Nifty, scar, stamina  |
|            9 |     8801 | 2023-12-16 | Pantsu              | W   | 0.099      | -            | -                | -                | -         |     1.26 | djay, Louie, Nifty, scar, stamina  |
|            8 |     8974 | 2023-12-15 | Bad News Bears      | L   | 0.093      | -            | -                | -                | -         |    -2.24 | djay, Louie, Nifty, scar, stamina  |
|            7 |     9208 | 2023-12-10 | Revenge Nation      | L   | 0.060      | -            | -                | -                | -         |    -0.84 | djay, Louie, Nifty, scar, stamina  |
|            6 |     9267 | 2023-12-09 | Villainous          | W   | 0.053      | -            | -                | -                | -         |     0.78 | djay, Louie, Nifty, scar, stamina  |
|            5 |     9343 | 2023-12-08 | regain              | W   | 0.047      | -            | -                | -                | -         |     0.61 | djay, Louie, Nifty, scar, stamina  |
|            4 |     9403 | 2023-12-07 | Zero MarksMen       | W   | 0.040      | -            | -                | -                | -         |     0.31 | djay, Louie, Nifty, scar, stamina  |
|            3 |     9469 | 2023-12-06 | LAG Gaming          | L   | 0.033      | -            | -                | -                | -         |    -0.19 | djay, Louie, Nifty, scar, stamina  |
|            2 |     9535 | 2023-12-05 | Spectre Tavius      | W   | 0.026      | -            | -                | -                | -         |     0.14 | djay, Louie, Nifty, scar, stamina  |
|            1 |     9707 | 2023-12-02 | Elevate             | L   | 0.006      | -            | -                | -                | -         |    -0.05 | danss, djay, Nifty, scar, stamina  |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($159.72)
- Divide that value by the 5th highest value among all rosters ($300,806.11)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
