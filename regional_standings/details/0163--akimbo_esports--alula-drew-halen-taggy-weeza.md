### Roster Details<br />
Team Name: Akimbo Esports<br />
Roster: alula, Drew, Halen, taggy, Weeza<br />
Region: [Americas]( ../standings_americas.md)<br />
<br />
Global Rank: [163](../standings_global.md)<br />
Regional Rank: [33]( ../standings_americas.md)<br />
Final Rank Value:  769.7<br />
<br />
Final Rank Value (769.7) = Starting Rank Value (768.6) + Head To Head Adjustments (1.1)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.320[<sup>1</sup>](#table2)
- Bounty Collected: 0.236[<sup>2</sup>](#table1)
- Opponent Network: 0.019[<sup>2</sup>](#table1)
- LAN Wins: 0.150[<sup>2</sup>](#table1)

The average of these factors is 0.181<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 768.6
- 400 + ( ( 0.181 - 0.000 ) / ( 0.787 - 0.000 ) ) * 1600 = 768.6


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent          | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                       |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           26 |        4 | 2024-05-29 | regain            | W   | 1.000      | 0.372        | 0.000 (0.000)    | 0.108 (0.040)    | 0 (0.000) |    10.03 | alula, Drew, Halen, taggy, Weeza             |
|           25 |     4251 | 2024-03-19 | Strife Esports    | L   | 0.726      | -            | -                | -                | -         |   -13.00 | alula, Drew, Ethex, taggy, Weeza             |
|           24 |     4334 | 2024-03-17 | Zomblers          | W   | 0.713      | 0.371        | 0.003 (0.001)    | 0.108 (0.029)    | 0 (0.000) |     7.93 | CAJUN, caustic, K4mr0, Marro, sam            |
|           23 |     4336 | 2024-03-17 | LAG Gaming        | L   | 0.712      | -            | -                | -                | -         |    -6.77 | alula, Drew, Ethex, taggy, Weeza             |
|           22 |     4341 | 2024-03-17 | Villainous        | W   | 0.711      | 0.333        | 0.000 (0.000)    | 0.093 (0.022)    | 1 (0.711) |     7.54 | Beast, Cyrix, dopplahs, TyRa, Zamgaa         |
|           21 |     4386 | 2024-03-17 | Detonate          | W   | 0.710      | 0.333        | 0.001 (0.000)    | 0.013 (0.003)    | 1 (0.710) |     7.25 | Enzo, FuuuZion, GibbyATL, Ravenzs, Tr1ck     |
|           20 |     4700 | 2024-03-11 | Revenge Nation    | L   | 0.673      | -            | -                | -                | -         |   -11.99 | alula, Drew, Ethex, taggy, Weeza             |
|           19 |     4811 | 2024-03-09 | Strife Esports    | W   | 0.660      | 0.371        | 0.011 (0.003)    | 0.204 (0.050)    | 0 (0.000) |     8.45 | alula, Drew, Ethex, taggy, Weeza             |
|           18 |     4903 | 2024-03-07 | Zomblers          | W   | 0.647      | 0.371        | 0.003 (0.001)    | 0.108 (0.026)    | 0 (0.000) |     6.91 | CAJUN, caustic, K4mr0, Marro, sam            |
|           17 |     7225 | 2024-01-26 | ex-CatEvil        | L   | 0.373      | -            | -                | -                | -         |    -8.23 | Antuanette, BabyRage, SJR, Slayerhz, zockie  |
|           16 |     7234 | 2024-01-26 | One Bullet Gaming | W   | 0.372      | -            | -                | -                | 0 (0.000) |     1.37 | fream4son, Orii, Seraph, TachoCV, zackfoster |
|           15 |     7391 | 2024-01-23 | One More Esports  | L   | 0.353      | -            | -                | -                | -         |    -5.75 | alula, Drew, Ethex, legacy, Weeza            |
|           14 |     7394 | 2024-01-23 | WICKED            | W   | 0.353      | 0.143        | 0.009 (0.000)    | 0.129 (0.007)    | 0 (0.000) |     4.84 | Andrew, Austin, Loagurt, mason, zeep         |
|           13 |     8005 | 2024-01-14 | Carpe Diem        | L   | 0.292      | -            | -                | -                | -         |    -6.23 | alula, Drew, Ethex, legacy, Weeza            |
|           12 |     8021 | 2024-01-13 | BOSS              | L   | 0.286      | -            | -                | -                | -         |    -3.47 | alula, Drew, Ethex, legacy, Weeza            |
|           11 |     8061 | 2024-01-12 | FLUFFY AIMERS     | W   | 0.281      | 0.143        | 0.001 (0.000)    | -                | 0 (0.000) |     2.73 | alula, Drew, Ethex, legacy, Weeza            |
|           10 |     8070 | 2024-01-12 | Party Astronauts  | L   | 0.280      | -            | -                | -                | -         |    -2.44 | alula, Drew, Ethex, legacy, Weeza            |
|            9 |     8290 | 2024-01-09 | NRG               | L   | 0.261      | -            | -                | -                | -         |    -3.41 | Brehze, daps, FaNg, HexT, oSee               |
|            8 |     8292 | 2024-01-09 | Revenge Nation    | W   | 0.260      | 0.143        | 0.019 (0.001)    | 0.186 (0.007)    | 0 (0.000) |     3.58 | alula, Drew, Ethex, legacy, Weeza            |
|            7 |     8297 | 2024-01-09 | Pryde             | W   | 0.260      | 0.143        | -                | 0.043 (0.002)    | -         |     1.37 | Freaky, FRIZZY, Redman, SweatyMcRib, TeMPeR  |
|            6 |     8405 | 2024-01-08 | Tempest Gaming    | W   | 0.254      | 0.143        | 0.000 (0.000)    | -                | -         |     1.44 | alula, Drew, Ethex, legacy, Weeza            |
|            5 |     9344 | 2023-12-08 | Revenge Nation    | L   | 0.047      | -            | -                | -                | -         |    -0.83 | HorizoN, NIGHT666LADE, Rulik, S0ph3R, TABEN  |
|            4 |     9400 | 2023-12-07 | Akimbo Esports    | W   | 0.040      | -            | -                | -                | -         |     0.21 | flixxy, Florence, Keiti, niise, Noxio        |
|            3 |     9470 | 2023-12-06 | One More Esports  | L   | 0.033      | -            | -                | -                | -         |    -0.55 | cbass, Grave, jchancE, serv0, z0mb1e         |
|            2 |     9531 | 2023-12-05 | regain            | W   | 0.027      | 0.371        | -                | 0.108 (0.001)    | -         |     0.25 | alula, Drew, Ethex, legacy, Weeza            |
|            1 |     9700 | 2023-12-02 | Party Astronauts  | L   | 0.006      | -            | -                | -                | -         |    -0.13 | alula, Drew, Ethex, legacy, Weeza            |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($2,278.78)
- Divide that value by the 5th highest value among all rosters ($300,806.11)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-03-23 |      0.753 | $2,000.00      | $1,505.56       |
| 2024-03-17 |      0.713 | $1,000.00      | $713.33         |
| 2023-12-13 |      0.080 | $750.00        | $59.90          |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
