### Roster Details<br />
Team Name: One More Esports<br />
Roster: cbass, Grave, jchancE, serv0, z0mb1e<br />
Region: [Americas]( ../standings_americas.md)<br />
<br />
Global Rank: [265](../standings_global.md)<br />
Regional Rank: [57]( ../standings_americas.md)<br />
Final Rank Value:  673.7<br />
<br />
Final Rank Value (673.7) = Starting Rank Value (748.9) + Head To Head Adjustments (-75.2)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.299[<sup>1</sup>](#table2)
- Bounty Collected: 0.309[<sup>2</sup>](#table1)
- Opponent Network: 0.079[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.172<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 748.9
- 400 + ( ( 0.172 - 0.000 ) / ( 0.787 - 0.000 ) ) * 1600 = 748.9


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent         | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                       |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           40 |      429 | 2024-05-22 | Wildcard Gaming  | L   | 1.000      | -            | -                | -                | -         |    -4.77 | cbass, Grave, jchancE, serv0, z0mb1e         |
|           39 |      434 | 2024-05-22 | Wildcard Gaming  | L   | 1.000      | -            | -                | -                | -         |    -5.00 | cbass, Grave, jchancE, serv0, z0mb1e         |
|           38 |      538 | 2024-05-21 | Elevate          | L   | 1.000      | -            | -                | -                | -         |    -7.99 | cbass, Champ, jchancE, serv0, z0mb1e         |
|           37 |      541 | 2024-05-21 | Elevate          | L   | 1.000      | -            | -                | -                | -         |    -8.56 | cbass, Champ, jchancE, serv0, z0mb1e         |
|           36 |      640 | 2024-05-20 | MIGHT            | W   | 1.000      | 0.477        | 0.001 (0.000)    | 0.207 (0.099)    | 0 (0.000) |    13.86 | cbass, Grave, jchancE, serv0, z0mb1e         |
|           35 |      644 | 2024-05-20 | MIGHT            | L   | 1.000      | -            | -                | -                | -         |   -17.81 | cbass, Grave, jchancE, serv0, z0mb1e         |
|           34 |     1032 | 2024-05-16 | Carpe Diem       | L   | 1.000      | -            | -                | -                | -         |   -15.04 | cbass, Grave, jchancE, serv0, z0mb1e         |
|           33 |     1037 | 2024-05-16 | Carpe Diem       | L   | 1.000      | -            | -                | -                | -         |   -16.43 | cbass, Grave, jchancE, serv0, z0mb1e         |
|           32 |     1121 | 2024-05-15 | M80              | L   | 1.000      | -            | -                | -                | -         |    -1.24 | cbass, Grave, jchancE, serv0, z0mb1e         |
|           31 |     1127 | 2024-05-15 | M80              | L   | 1.000      | -            | -                | -                | -         |    -1.25 | cbass, Grave, jchancE, serv0, z0mb1e         |
|           30 |     1225 | 2024-05-14 | NRG              | L   | 1.000      | -            | -                | -                | -         |    -6.96 | cbass, Grave, jchancE, serv0, z0mb1e         |
|           29 |     1231 | 2024-05-14 | NRG              | L   | 1.000      | -            | -                | -                | -         |    -7.41 | cbass, Grave, jchancE, serv0, z0mb1e         |
|           28 |     2443 | 2024-04-23 | Nouns Esports    | W   | 0.959      | 0.477        | 0.071 (0.033)    | 0.507 (0.232)    | 0 (0.000) |    23.88 | cbass, Grave, jchancE, serv0, z0mb1e         |
|           27 |     2448 | 2024-04-23 | Nouns Esports    | L   | 0.959      | -            | -                | -                | -         |    -5.90 | cbass, Grave, jchancE, serv0, z0mb1e         |
|           26 |     3210 | 2024-04-10 | FLUFFY AIMERS    | W   | 0.873      | 0.477        | 0.030 (0.013)    | 0.384 (0.160)    | 0 (0.000) |    18.99 | cbass, Grave, jchancE, serv0, z0mb1e         |
|           25 |     3215 | 2024-04-10 | FLUFFY AIMERS    | L   | 0.873      | -            | -                | -                | -         |    -8.28 | cbass, Grave, jchancE, serv0, z0mb1e         |
|           24 |     3293 | 2024-04-09 | Party Astronauts | L   | 0.866      | -            | -                | -                | -         |    -4.96 | cbass, Grave, jchancE, serv0, z0mb1e         |
|           23 |     3297 | 2024-04-09 | Party Astronauts | L   | 0.866      | -            | -                | -                | -         |    -5.19 | cbass, Grave, jchancE, serv0, z0mb1e         |
|           22 |     3545 | 2024-04-04 | Limitless        | W   | 0.833      | 0.477        | 0.001 (0.001)    | 0.123 (0.049)    | 0 (0.000) |    11.94 | cbass, Grave, jchancE, serv0, z0mb1e         |
|           21 |     3549 | 2024-04-04 | Limitless        | L   | 0.833      | -            | -                | -                | -         |   -14.54 | cbass, Grave, jchancE, serv0, z0mb1e         |
|           20 |     3851 | 2024-03-27 | BOSS             | L   | 0.780      | -            | -                | -                | -         |    -9.64 | cbass, Grave, jchancE, serv0, z0mb1e         |
|           19 |     3855 | 2024-03-27 | BOSS             | W   | 0.780      | 0.477        | 0.016 (0.006)    | 0.315 (0.117)    | 0 (0.000) |    15.29 | cbass, Grave, jchancE, serv0, z0mb1e         |
|           18 |     4510 | 2024-03-14 | Mythic           | L   | 0.693      | -            | -                | -                | -         |   -10.06 | cbass, Grave, jchancE, serv0, z0mb1e         |
|           17 |     4512 | 2024-03-14 | Mythic           | L   | 0.693      | -            | -                | -                | -         |   -10.69 | cbass, Grave, jchancE, serv0, z0mb1e         |
|           16 |     5057 | 2024-03-05 | LAG Gaming       | L   | 0.633      | -            | -                | -                | -         |    -5.70 | cbass, Grave, jchancE, serv0, z0mb1e         |
|           15 |     5067 | 2024-03-05 | LAG Gaming       | L   | 0.633      | -            | -                | -                | -         |    -5.96 | cbass, Grave, jchancE, serv0, z0mb1e         |
|           14 |     5793 | 2024-02-22 | Party Astronauts | L   | 0.552      | -            | -                | -                | -         |    -4.93 | cbass, Grave, jchancE, serv0, z0mb1e         |
|           13 |     5844 | 2024-02-21 | FLUFFY AIMERS    | W   | 0.546      | 0.143        | 0.030 (0.002)    | 0.384 (0.030)    | 0 (0.000) |    12.26 | cbass, Grave, jchancE, serv0, z0mb1e         |
|           12 |     6315 | 2024-02-13 | Take Flyte       | W   | 0.493      | 0.477        | 0.006 (0.001)    | 0.354 (0.083)    | 0 (0.000) |     8.47 | cbass, Grave, jchancE, serv0, z0mb1e         |
|           11 |     6317 | 2024-02-13 | Take Flyte       | L   | 0.493      | -            | -                | -                | -         |    -7.21 | cbass, Grave, jchancE, serv0, z0mb1e         |
|           10 |     7329 | 2024-01-24 | Wildcard Gaming  | L   | 0.359      | -            | -                | -                | -         |    -3.31 | cbass, Grave, jchancE, serv0, z0mb1e         |
|            9 |     7391 | 2024-01-23 | Akimbo Esports   | W   | 0.353      | 0.143        | 0.008 (0.000)    | 0.155 (0.008)    | 0 (0.000) |     5.75 | alula, Drew, Ethex, legacy, Weeza            |
|            8 |     7396 | 2024-01-23 | Revenge Nation   | W   | 0.353      | 0.143        | 0.019 (0.001)    | 0.186 (0.009)    | 0 (0.000) |     5.04 | HorizoN, MagiC, S0ph3R, TABEN, xam           |
|            7 |     8160 | 2024-01-11 | FLUFFY AIMERS    | L   | 0.273      | -            | -                | -                | -         |    -5.83 | cbass, Grave, jchancE, serv0, z0mb1e         |
|            6 |     8224 | 2024-01-10 | AURA Esports     | W   | 0.267      | -            | -                | -                | 0 (0.000) |     1.03 | Caffrey, Malice, offaclaw, Russtbh, stattik  |
|            5 |     9069 | 2023-12-13 | Revenge Nation   | W   | 0.080      | 0.371        | 0.019 (0.001)    | 0.186 (0.006)    | -         |     1.17 | HorizoN, NIGHT666LADE, Rulik, S0ph3R, TABEN  |
|            4 |     9345 | 2023-12-08 | Pantsu           | W   | 0.047      | -            | -                | -                | -         |     0.47 | cbass, Grave, jchancE, serv0, z0mb1e         |
|            3 |     9404 | 2023-12-07 | Villainous       | W   | 0.040      | -            | -                | -                | -         |     0.47 | Beast, BiNoX, dopplahs, jsfeltner, TyRa      |
|            2 |     9470 | 2023-12-06 | Akimbo Esports   | W   | 0.033      | -            | -                | -                | -         |     0.55 | cbass, Grave, jchancE, serv0, z0mb1e         |
|            1 |     9532 | 2023-12-05 | ex-CatEvil       | W   | 0.027      | -            | -                | -                | -         |     0.26 | Antuanette, BabyRage, SJR, tor1towOw, zockie |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($1,359.03)
- Divide that value by the 5th highest value among all rosters ($300,806.11)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-05-22 |      1.000 | $800.00        | $800.00         |
| 2023-12-13 |      0.080 | $7,000.00      | $559.03         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
