### Roster Details<br />
Team Name: One More Esports<br />
Roster: cbass, Grave, jchancE, serv0, z0mb1e<br />
Region: [Americas]( ../standings_americas.md)<br />
<br />
Global Rank: [237](../standings_global.md)<br />
Regional Rank: [43]( ../standings_americas.md)<br />
Final Rank Value:  676.2<br />
<br />
Final Rank Value (676.2) = Starting Rank Value (711.2) + Head To Head Adjustments (-35.0)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.336[<sup>1</sup>](#table2)
- Bounty Collected: 0.248[<sup>2</sup>](#table1)
- Opponent Network: 0.043[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.157<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 711.2
- 400 + ( ( 0.157 - 0.000 ) / ( 0.806 - 0.000 ) ) * 1600 = 711.2


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent                     | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                       |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           21 |      554 | 2024-04-23 | Nouns Esports                | W   | 1.000      | 0.477        | 0.000 (0.000)    | 0.475 (0.226)    | 0 (0.000) |    22.99 | cbass, Grave, jchancE, serv0, z0mb1e         |
|           20 |      559 | 2024-04-23 | Nouns Esports                | L   | 1.000      | -            | -                | -                | -         |    -8.02 | cbass, Grave, jchancE, serv0, z0mb1e         |
|           19 |     1264 | 2024-04-09 | Party Astronauts             | L   | 1.000      | -            | -                | -                | -         |    -7.16 | cbass, Grave, jchancE, serv0, z0mb1e         |
|           18 |     1268 | 2024-04-09 | Party Astronauts             | L   | 1.000      | -            | -                | -                | -         |    -7.62 | cbass, Grave, jchancE, serv0, z0mb1e         |
|           17 |     1455 | 2024-04-04 | Limitless                    | W   | 0.994      | 0.477        | 0.001 (0.001)    | 0.177 (0.084)    | 0 (0.000) |    15.82 | cbass, Grave, jchancE, serv0, z0mb1e         |
|           16 |     1459 | 2024-04-04 | Limitless                    | L   | 0.994      | -            | -                | -                | -         |   -15.48 | cbass, Grave, jchancE, serv0, z0mb1e         |
|           15 |     2239 | 2024-03-14 | Mythic                       | L   | 0.854      | -            | -                | -                | -         |   -11.46 | cbass, Grave, jchancE, serv0, z0mb1e         |
|           14 |     2241 | 2024-03-14 | Mythic                       | L   | 0.854      | -            | -                | -                | -         |   -12.34 | cbass, Grave, jchancE, serv0, z0mb1e         |
|           13 |     2660 | 2024-03-05 | LAG Gaming (American team)   | L   | 0.794      | -            | -                | -                | -         |    -6.49 | cbass, Grave, jchancE, serv0, z0mb1e         |
|           12 |     2665 | 2024-03-05 | LAG Gaming (American team)   | L   | 0.794      | -            | -                | -                | -         |    -6.85 | cbass, Grave, jchancE, serv0, z0mb1e         |
|           11 |     3232 | 2024-02-22 | Party Astronauts             | L   | 0.713      | -            | -                | -                | -         |    -7.67 | cbass, Grave, jchancE, serv0, z0mb1e         |
|           10 |     3658 | 2024-02-13 | Take Flyte                   | W   | 0.654      | 0.477        | 0.004 (0.001)    | 0.279 (0.087)    | 0 (0.000) |    10.43 | cbass, Grave, jchancE, serv0, z0mb1e         |
|            9 |     3659 | 2024-02-13 | Take Flyte                   | L   | 0.654      | -            | -                | -                | -         |   -10.39 | cbass, Grave, jchancE, serv0, z0mb1e         |
|            8 |     4372 | 2024-01-24 | Wildcard Gaming              | L   | 0.520      | -            | -                | -                | -         |    -4.45 | cbass, Grave, jchancE, serv0, z0mb1e         |
|            7 |     4417 | 2024-01-23 | Revenge Nation               | W   | 0.514      | 0.143        | 0.043 (0.003)    | 0.123 (0.009)    | 0 (0.000) |     8.23 | HorizoN, MagiC, S0ph3R, TABEN, xam           |
|            6 |     4977 | 2024-01-11 | FLUFFY AIMERS                | L   | 0.434      | -            | -                | -                | -         |    -7.58 | cbass, Grave, jchancE, serv0, z0mb1e         |
|            5 |     5022 | 2024-01-10 | AURA Esports (American team) | W   | 0.428      | 0.143        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     1.90 | Caffrey, Malice, offaclaw, Russtbh, stattik  |
|            4 |     5625 | 2023-12-13 | Revenge Nation               | W   | 0.241      | 0.371        | 0.043 (0.004)    | 0.123 (0.011)    | 0 (0.000) |     3.99 | HorizoN, NIGHT666LADE, Rulik, S0ph3R, TABEN  |
|            3 |     5814 | 2023-12-08 | Pantsu                       | W   | 0.208      | 0.371        | 0.005 (0.000)    | 0.020 (0.002)    | 0 (0.000) |     2.80 | cbass, Grave, jchancE, serv0, z0mb1e         |
|            2 |     5861 | 2023-12-07 | Villainous                   | W   | 0.201      | 0.371        | 0.002 (0.000)    | 0.082 (0.006)    | 0 (0.000) |     2.06 | Beast, BiNoX, dopplahs, jsfeltner, TyRa      |
|            1 |     5955 | 2023-12-05 | CatEvil                      | W   | 0.188      | 0.371        | 0.001 (0.000)    | 0.034 (0.002)    | 0 (0.000) |     2.27 | Antuanette, BabyRage, SJR, tor1towOw, zockie |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($1,686.48)
- Divide that value by the 5th highest value among all rosters ($158,437.64)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
