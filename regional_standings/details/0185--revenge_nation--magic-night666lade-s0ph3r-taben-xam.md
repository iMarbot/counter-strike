### Roster Details<br />
Team Name: Revenge Nation<br />
Roster: MagiC, NIGHT666LADE, S0ph3R, TABEN, xam<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [185](../standings_global.md)<br />
Regional Rank: [127]( ../standings_europe.md)<br />
Final Rank Value:  742.0<br />
<br />
Final Rank Value (742.0) = Starting Rank Value (722.7) + Head To Head Adjustments (19.3)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.366[<sup>1</sup>](#table2)
- Bounty Collected: 0.248[<sup>2</sup>](#table1)
- Opponent Network: 0.021[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.159<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 722.7
- 400 + ( ( 0.159 - 0.000 ) / ( 0.787 - 0.000 ) ) * 1600 = 722.7


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent            | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                      |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           27 |       11 | 2024-05-29 | Elevate             | L   | 1.000      | -            | -                | -                | -         |    -8.39 | MagiC, NIGHT666LADE, S0ph3R, TABEN, xam     |
|           26 |       31 | 2024-05-29 | LAG Gaming          | W   | 1.000      | 0.143        | 0.013 (0.002)    | 0.335 (0.048)    | 0 (0.000) |    19.82 | MagiC, NIGHT666LADE, S0ph3R, TABEN, xam     |
|           25 |     1040 | 2024-05-16 | MIGHT               | L   | 1.000      | -            | -                | -                | -         |   -20.45 | HorizoN, NIGHT666LADE, S0ph3R, TABEN, xam   |
|           24 |     1046 | 2024-05-16 | old mythic          | W   | 1.000      | -            | -                | -                | 0 (0.000) |     3.86 | HorizoN, NIGHT666LADE, S0ph3R, TABEN, xam   |
|           23 |     4059 | 2024-03-23 | Strife Esports      | W   | 0.753      | 0.371        | 0.011 (0.003)    | 0.204 (0.057)    | 0 (0.000) |    11.64 | HorizoN, MagiC, S0ph3R, TABEN, xam          |
|           22 |     4571 | 2024-03-13 | Final Form          | W   | 0.686      | 0.371        | 0.008 (0.002)    | 0.074 (0.019)    | 0 (0.000) |     9.96 | HorizoN, MagiC, S0ph3R, TABEN, xam          |
|           21 |     4700 | 2024-03-11 | Akimbo Esports      | W   | 0.673      | 0.371        | 0.008 (0.002)    | 0.155 (0.039)    | 0 (0.000) |    11.99 | HorizoN, MagiC, S0ph3R, TABEN, xam          |
|           20 |     4810 | 2024-03-09 | orbital vsat online | W   | 0.660      | 0.371        | -                | 0.035 (0.009)    | 0 (0.000) |     3.43 | HorizoN, MagiC, S0ph3R, TABEN, xam          |
|           19 |     4901 | 2024-03-07 | Villainous          | W   | 0.647      | 0.371        | 0.000 (0.000)    | 0.093 (0.022)    | 0 (0.000) |     8.70 | HorizoN, MagiC, S0ph3R, TABEN, xam          |
|           18 |     5059 | 2024-03-05 | LOSTHILLS           | W   | 0.633      | -            | -                | -                | 0 (0.000) |     3.13 | HorizoN, MagiC, S0ph3R, TABEN, xam          |
|           17 |     6188 | 2024-02-15 | FLUFFY AIMERS       | L   | 0.506      | -            | -                | -                | -         |    -3.54 | HorizoN, MagiC, S0ph3R, TABEN, xam          |
|           16 |     7227 | 2024-01-26 | LOS                 | L   | 0.373      | -            | -                | -                | -         |    -8.71 | HorizoN, MagiC, S0ph3R, TABEN, xam          |
|           15 |     7396 | 2024-01-23 | One More Esports    | L   | 0.353      | -            | -                | -                | -         |    -5.04 | HorizoN, MagiC, S0ph3R, TABEN, xam          |
|           14 |     8221 | 2024-01-10 | Rocket              | L   | 0.267      | -            | -                | -                | -         |    -6.27 | HorizoN, MagiC, S0ph3R, TABEN, xam          |
|           13 |     8292 | 2024-01-09 | Akimbo Esports      | L   | 0.260      | -            | -                | -                | -         |    -3.58 | alula, Drew, Ethex, legacy, Weeza           |
|           12 |     8296 | 2024-01-09 | MishMash Gaming     | W   | 0.260      | 0.143        | -                | 0.007 (0.000)    | 0 (0.000) |     1.70 | HorizoN, MagiC, Rulik, S0ph3R, TABEN        |
|           11 |     8402 | 2024-01-08 | Team Dennys         | W   | 0.254      | 0.143        | 0.000 (0.000)    | -                | 0 (0.000) |     1.84 | carN, MOOSELFLiES, mst, OrnateRope, Two-Six |
|           10 |     8794 | 2023-12-16 | Rocket              | L   | 0.100      | -            | -                | -                | -         |    -2.38 | HorizoN, NIGHT666LADE, Rulik, S0ph3R, TABEN |
|            9 |     8972 | 2023-12-15 | NRG                 | L   | 0.093      | -            | -                | -                | -         |    -1.05 | Brehze, daps, FaNg, HexT, oSee              |
|            8 |     9069 | 2023-12-13 | One More Esports    | L   | 0.080      | -            | -                | -                | -         |    -1.17 | HorizoN, NIGHT666LADE, Rulik, S0ph3R, TABEN |
|            7 |     9161 | 2023-12-11 | Pantsu              | W   | 0.067      | 0.371        | 0.001 (0.000)    | -                | -         |     0.73 | HorizoN, NIGHT666LADE, Rulik, S0ph3R, TABEN |
|            6 |     9208 | 2023-12-10 | MIGHT               | W   | 0.060      | 0.371        | 0.001 (0.000)    | 0.207 (0.005)    | -         |     0.84 | djay, Louie, Nifty, scar, stamina           |
|            5 |     9266 | 2023-12-09 | LAG Gaming          | W   | 0.053      | 0.371        | 0.013 (0.000)    | 0.335 (0.007)    | -         |     1.32 | HorizoN, NIGHT666LADE, Rulik, S0ph3R, TABEN |
|            4 |     9344 | 2023-12-08 | Akimbo Esports      | W   | 0.047      | 0.371        | 0.008 (0.000)    | 0.155 (0.003)    | -         |     0.83 | HorizoN, NIGHT666LADE, Rulik, S0ph3R, TABEN |
|            3 |     9401 | 2023-12-07 | Team Steve          | W   | 0.040      | -            | -                | -                | -         |     0.18 | HorizoN, NIGHT666LADE, Rulik, S0ph3R, TABEN |
|            2 |     9465 | 2023-12-06 | Spectre Tavius      | W   | 0.033      | -            | -                | -                | -         |     0.15 | Dante, jaay, oreosss, rayxts, YOSH1         |
|            1 |     9530 | 2023-12-05 | LAG Gaming          | L   | 0.027      | -            | -                | -                | -         |    -0.18 | based, Experative, Nyyx, ogwizard, X-23     |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($5,612.85)
- Divide that value by the 5th highest value among all rosters ($300,806.11)
- The final value (0.02) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-03-23 |      0.753 | $7,000.00      | $5,269.44       |
| 2023-12-13 |      0.080 | $4,300.00      | $343.40         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
