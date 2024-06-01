### Roster Details<br />
Team Name: MIGHT<br />
Roster: djay, Fr3nk1e, Nifty, scar, Snakes<br />
Region: [Americas]( ../standings_americas.md)<br />
<br />
Global Rank: [329](../standings_global.md)<br />
Regional Rank: [78]( ../standings_americas.md)<br />
Final Rank Value:  621.0<br />
<br />
Final Rank Value (621.0) = Starting Rank Value (683.5) + Head To Head Adjustments (-62.5)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.234[<sup>1</sup>](#table2)
- Bounty Collected: 0.259[<sup>2</sup>](#table1)
- Opponent Network: 0.064[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.139<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 683.5
- 400 + ( ( 0.139 - 0.000 ) / ( 0.786 - 0.000 ) ) * 1600 = 683.5


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
|           56 |      427 | 2024-05-22 | Carpe Diem          | L   | 1.000      | -            | -                | -                | -         |   -10.81 | djay, Fr3nk1e, Nifty, scar, Snakes |
|           55 |      430 | 2024-05-22 | Carpe Diem          | L   | 1.000      | -            | -                | -                | -         |   -11.72 | djay, Fr3nk1e, Nifty, scar, Snakes |
|           54 |      629 | 2024-05-20 | One More Esports    | L   | 1.000      | -            | -                | -                | -         |   -13.86 | djay, Fr3nk1e, Nifty, scar, Snakes |
|           53 |      633 | 2024-05-20 | One More Esports    | W   | 1.000      | 0.477        | 0.005 (0.002)    | 0.166 (0.079)    | 0 (0.000) |    17.81 | djay, Fr3nk1e, Nifty, scar, Snakes |
|           52 |     1021 | 2024-05-16 | Legacy              | L   | 1.000      | -            | -                | -                | -         |    -2.30 | djay, Fr3nk1e, Nifty, scar, Snakes |
|           51 |     1028 | 2024-05-16 | Revenge Nation      | W   | 1.000      | 0.143        | 0.019 (0.003)    | 0.186 (0.027)    | 0 (0.000) |    20.45 | djay, Fr3nk1e, Nifty, scar, Snakes |
|           50 |     1035 | 2024-05-16 | Perseverance Gaming | W   | 1.000      | -            | -                | -                | 0 (0.000) |     7.07 | djay, Fr3nk1e, Nifty, scar, Snakes |
|           49 |     1110 | 2024-05-15 | FLUFFY AIMERS       | L   | 1.000      | -            | -                | -                | -         |    -6.87 | djay, Fr3nk1e, Nifty, scar, Snakes |
|           48 |     1123 | 2024-05-15 | FLUFFY AIMERS       | L   | 1.000      | -            | -                | -                | -         |    -7.31 | djay, Fr3nk1e, Nifty, scar, Snakes |
|           47 |     1218 | 2024-05-14 | BOSS                | L   | 1.000      | -            | -                | -                | -         |    -7.19 | djay, Fr3nk1e, Nifty, scar, Snakes |
|           46 |     1225 | 2024-05-14 | BOSS                | L   | 1.000      | -            | -                | -                | -         |    -7.66 | djay, Fr3nk1e, Nifty, scar, Snakes |
|           45 |     1544 | 2024-05-09 | Wildcard Gaming     | L   | 1.000      | -            | -                | -                | -         |    -5.03 | djay, Fr3nk1e, Nifty, scar, Snakes |
|           44 |     1545 | 2024-05-09 | Wildcard Gaming     | L   | 1.000      | -            | -                | -                | -         |    -5.28 | djay, Fr3nk1e, Nifty, scar, Snakes |
|           43 |     1587 | 2024-05-08 | Elevate             | L   | 1.000      | -            | -                | -                | -         |    -6.05 | djay, Fr3nk1e, Nifty, scar, Snakes |
|           42 |     1591 | 2024-05-08 | Elevate             | L   | 1.000      | -            | -                | -                | -         |    -6.40 | djay, Fr3nk1e, Nifty, scar, Snakes |
|           41 |     3138 | 2024-04-10 | Take Flyte          | W   | 0.873      | 0.477        | 0.006 (0.002)    | 0.354 (0.147)    | 0 (0.000) |    18.86 | danss, djay, Nifty, scar, Snakes   |
|           40 |     3143 | 2024-04-10 | Take Flyte          | L   | 0.873      | -            | -                | -                | -         |    -8.40 | danss, djay, Nifty, scar, Snakes   |
|           39 |     3213 | 2024-04-09 | Nouns Esports       | L   | 0.866      | -            | -                | -                | -         |    -4.24 | danss, djay, Nifty, scar, Snakes   |
|           38 |     3217 | 2024-04-09 | Nouns Esports       | L   | 0.866      | -            | -                | -                | -         |    -4.42 | danss, djay, Nifty, scar, Snakes   |
|           37 |     3462 | 2024-04-04 | Party Astronauts    | L   | 0.833      | -            | -                | -                | -         |    -3.75 | danss, djay, Nifty, scar, Snakes   |
|           36 |     3466 | 2024-04-04 | Party Astronauts    | L   | 0.833      | -            | -                | -                | -         |    -3.89 | danss, djay, Nifty, scar, Snakes   |
|           35 |     3761 | 2024-03-27 | Limitless           | L   | 0.780      | -            | -                | -                | -         |   -11.59 | danss, djay, Nifty, scar, Snakes   |
|           34 |     3765 | 2024-03-27 | Limitless           | L   | 0.780      | -            | -                | -                | -         |   -12.42 | danss, djay, Nifty, scar, Snakes   |
|           33 |     3837 | 2024-03-26 | NRG                 | L   | 0.773      | -            | -                | -                | -         |    -6.59 | danss, djay, Nifty, scar, Snakes   |
|           32 |     3842 | 2024-03-26 | NRG                 | L   | 0.773      | -            | -                | -                | -         |    -6.96 | danss, djay, Nifty, scar, Snakes   |
|           31 |     4532 | 2024-03-12 | Carpe Diem          | L   | 0.679      | -            | -                | -                | -         |   -12.62 | danss, djay, Nifty, scar, Snakes   |
|           30 |     4835 | 2024-03-06 | LAG Gaming          | L   | 0.640      | -            | -                | -                | -         |    -5.29 | danss, djay, Nifty, scar, Snakes   |
|           29 |     4837 | 2024-03-06 | LAG Gaming          | W   | 0.640      | 0.477        | 0.013 (0.004)    | 0.335 (0.102)    | 0 (0.000) |    15.23 | danss, djay, Nifty, scar, Snakes   |
|           28 |     4919 | 2024-03-05 | Mythic              | W   | 0.633      | 0.477        | 0.000 (0.000)    | 0.339 (0.102)    | 0 (0.000) |    11.10 | danss, djay, Nifty, scar, Snakes   |
|           27 |     4927 | 2024-03-05 | Mythic              | W   | 0.633      | 0.477        | 0.000 (0.000)    | 0.339 (0.102)    | 0 (0.000) |    11.72 | danss, djay, Nifty, scar, Snakes   |
|           26 |     5585 | 2024-02-23 | Wildcard Gaming     | L   | 0.560      | -            | -                | -                | -         |    -3.91 | danss, djay, Nifty, scar, Snakes   |
|           25 |     5626 | 2024-02-22 | Team Liquid         | L   | 0.553      | -            | -                | -                | -         |    -0.08 | danss, djay, Nifty, scar, Snakes   |
|           24 |     5631 | 2024-02-22 | Take Flyte          | W   | 0.552      | 0.143        | 0.006 (0.000)    | 0.354 (0.028)    | 0 (0.000) |    10.97 | danss, djay, Nifty, scar, Snakes   |
|           23 |     5678 | 2024-02-21 | Carpe Diem          | W   | 0.546      | 0.143        | -                | 0.243 (0.019)    | 0 (0.000) |     7.48 | danss, djay, Nifty, scar, Snakes   |
|           22 |     5967 | 2024-02-16 | Rocket              | L   | 0.512      | -            | -                | -                | -         |    -9.66 | danss, djay, Nifty, scar, Snakes   |
|           21 |     6015 | 2024-02-15 | Snakes Den Gaming   | W   | 0.506      | -            | -                | -                | 0 (0.000) |     4.70 | danss, djay, Nifty, scar, Snakes   |
|           20 |     7010 | 2024-01-26 | ex-CatEvil          | L   | 0.373      | -            | -                | -                | -         |    -7.24 | danss, djay, louie, Nifty, scar    |
|           19 |     7154 | 2024-01-23 | Wildcard Gaming     | L   | 0.353      | -            | -                | -                | -         |    -2.48 | CLASIA, danss, djay, Nifty, scar   |
|           18 |     7155 | 2024-01-23 | LOS                 | W   | 0.353      | -            | -                | -                | -         |     3.15 | CLASIA, danss, djay, Nifty, scar   |
|           17 |     7450 | 2024-01-18 | Wildcard Gaming     | L   | 0.319      | -            | -                | -                | -         |    -2.44 | danss, djay, Louie, Nifty, scar    |
|           16 |     7502 | 2024-01-17 | Party Astronauts    | W   | 0.313      | 0.143        | 0.031 (0.001)    | 0.545 (0.024)    | -         |     7.92 | danss, djay, Louie, Nifty, scar    |
|           15 |     7614 | 2024-01-16 | huge sweaty         | L   | 0.306      | -            | -                | -                | -         |    -7.25 | danss, djay, Louie, Nifty, scar    |
|           14 |     7699 | 2024-01-15 | Carpe Diem          | W   | 0.299      | 0.143        | -                | 0.243 (0.010)    | -         |     4.09 | danss, djay, Louie, Nifty, scar    |
|           13 |     7905 | 2024-01-11 | The Nomads          | L   | 0.273      | -            | -                | -                | -         |    -6.57 | danss, djay, Nifty, scar, stamina  |
|           12 |     7968 | 2024-01-10 | Zomblers            | W   | 0.267      | 0.143        | 0.003 (0.000)    | -                | -         |     3.75 | danss, djay, Nifty, scar, stamina  |
|           11 |     8424 | 2023-12-17 | Rocket              | W   | 0.107      | -            | -                | -                | -         |     0.97 | djay, Louie, Nifty, scar, stamina  |
|           10 |     8430 | 2023-12-17 | LAG Gaming          | W   | 0.106      | 0.143        | 0.013 (0.000)    | -                | -         |     2.73 | djay, Louie, Nifty, scar, stamina  |
|            9 |     8541 | 2023-12-16 | Pantsu              | W   | 0.099      | -            | -                | -                | -         |     1.26 | djay, Louie, Nifty, scar, stamina  |
|            8 |     8713 | 2023-12-15 | Bad News Bears      | L   | 0.093      | -            | -                | -                | -         |    -2.24 | djay, Louie, Nifty, scar, stamina  |
|            7 |     8942 | 2023-12-10 | Revenge Nation      | L   | 0.060      | -            | -                | -                | -         |    -0.84 | djay, Louie, Nifty, scar, stamina  |
|            6 |     9001 | 2023-12-09 | Villainous          | W   | 0.053      | -            | -                | -                | -         |     0.78 | djay, Louie, Nifty, scar, stamina  |
|            5 |     9076 | 2023-12-08 | regain              | W   | 0.047      | -            | -                | -                | -         |     0.60 | djay, Louie, Nifty, scar, stamina  |
|            4 |     9133 | 2023-12-07 | Zero MarksMen       | W   | 0.040      | -            | -                | -                | -         |     0.31 | djay, Louie, Nifty, scar, stamina  |
|            3 |     9196 | 2023-12-06 | LAG Gaming          | L   | 0.033      | -            | -                | -                | -         |    -0.19 | djay, Louie, Nifty, scar, stamina  |
|            2 |     9254 | 2023-12-05 | Spectre Tavius      | W   | 0.026      | -            | -                | -                | -         |     0.14 | djay, Louie, Nifty, scar, stamina  |
|            1 |     9425 | 2023-12-02 | Elevate             | L   | 0.006      | -            | -                | -                | -         |    -0.05 | danss, djay, Nifty, scar, stamina  |

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
