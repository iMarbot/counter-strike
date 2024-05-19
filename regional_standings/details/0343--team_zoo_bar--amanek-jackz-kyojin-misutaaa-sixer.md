### Roster Details<br />
Team Name: TEAM ZOO BAR<br />
Roster: AMANEK, JACKZ, Kyojin, misutaaa, SIXER<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [343](../standings_global.md)<br />
Regional Rank: [212]( ../standings_europe.md)<br />
Final Rank Value:  514.0<br />
<br />
Final Rank Value (514.0) = Starting Rank Value (502.2) + Head To Head Adjustments (11.8)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.000[<sup>1</sup>](#table2)
- Bounty Collected: 0.201[<sup>2</sup>](#table1)
- Opponent Network: 0.005[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.051<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 502.2
- 400 + ( ( 0.051 - 0.000 ) / ( 0.806 - 0.000 ) ) * 1600 = 502.2


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent             | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins      | H2H Adj. | Roster                                    |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           15 |     1366 | 2024-04-07 | GenOne               | L   | 1.000      | -            | -                | -                | -             |   -12.46 | AMANEK, JACKZ, Kyojin, misutaaa, SIXER    |
|           14 |     4927 | 2024-01-12 | Sprout               | W   | 0.439      | 0.143        | 0.000 (0.000)    | 0.065 (0.004)    | false (0.000) |     6.43 | AMANEK, devoduvek, drac, Kyojin, SIXER    |
|           13 |     4937 | 2024-01-12 | CYBERSHOKE Esports   | W   | 0.439      | 0.143        | 0.004 (0.000)    | 0.220 (0.014)    | false (0.000) |    10.75 | AMANEK, devoduvek, drac, Kyojin, SIXER    |
|           12 |     5108 | 2024-01-09 | Gaimin Gladiators    | L   | 0.418      | -            | -                | -                | -             |    -0.07 | AMANEK, devoduvek, drac, Kyojin, SIXER    |
|           11 |     6243 | 2023-11-29 | TUSTE CHOPAKI        | L   | 0.146      | -            | -                | -                | -             |    -2.42 | AMANEK, devoduvek, drac, Kyojin, SIXER    |
|           10 |     6303 | 2023-11-28 | TY                   | W   | 0.139      | 0.371        | 0.011 (0.001)    | 0.055 (0.003)    | false (0.000) |     3.25 | fierre, maty, spardaus, tooizera, yakuza  |
|            9 |     6314 | 2023-11-28 | Grindas              | W   | 0.138      | 0.371        | 0.002 (0.000)    | 0.332 (0.017)    | false (0.000) |     3.28 | AMANEK, devoduvek, drac, Kyojin, SIXER    |
|            8 |     6480 | 2023-11-24 | Ex-Hot Headed Gaming | W   | 0.111      | 0.371        | 0.000 (0.000)    | 0.117 (0.005)    | false (0.000) |     1.81 | AMANEK, devoduvek, drac, Kyojin, SIXER    |
|            7 |     6485 | 2023-11-24 | Nexus Gaming         | L   | 0.111      | -            | -                | -                | -             |    -0.27 | AMANEK, devoduvek, drac, Kyojin, SIXER    |
|            6 |     6509 | 2023-11-23 | Bleiz                | W   | 0.105      | 0.371        | 0.000 (0.000)    | 0.000 (0.000)    | false (0.000) |     1.48 | AMANEK, devoduvek, drac, Kyojin, SIXER    |
|            5 |     6513 | 2023-11-23 | Lilmix               | L   | 0.105      | -            | -                | -                | -             |    -0.80 | AMANEK, devoduvek, drac, Kyojin, SIXER    |
|            4 |     6771 | 2023-11-17 | BAKS Esports         | W   | 0.065      | 0.371        | 0.003 (0.000)    | 0.084 (0.002)    | false (0.000) |     1.44 | AMANEK, devoduvek, drac, Kyojin, SIXER    |
|            3 |     6776 | 2023-11-17 | CYBERSHOKE Esports   | L   | 0.064      | -            | -                | -                | -             |    -0.41 | fen2k, FenomeN, flamie, Re1GN, sh1nejezzz |
|            2 |     6878 | 2023-11-15 | Team Space           | L   | 0.052      | -            | -                | -                | -             |    -0.34 | AMANEK, devoduvek, drac, Kyojin, SIXER    |
|            1 |     7165 | 2023-11-08 | Verdant              | W   | 0.006      | 0.371        | 0.027 (0.000)    | 0.662 (0.001)    | false (0.000) |     0.16 | arTisT, Ducky, Extinct, Girafffe, Wolfie  |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($0.00)
- Divide that value by the 5th highest value among all rosters ($158,437.64)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
