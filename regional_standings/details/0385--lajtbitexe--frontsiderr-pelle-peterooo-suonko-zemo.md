### Roster Details<br />
Team Name: lajtbitexe<br />
Roster: Frontsiderr, Pelle, PeTeRoOo, suonko, ZEMO<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [385](../standings_global.md)<br />
Regional Rank: [231]( ../standings_europe.md)<br />
Final Rank Value:  578.0<br />
<br />
Final Rank Value (578.0) = Starting Rank Value (630.6) + Head To Head Adjustments (-52.6)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.233[<sup>1</sup>](#table2)
- Bounty Collected: 0.208[<sup>2</sup>](#table1)
- Opponent Network: 0.013[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.113<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 630.6
- 400 + ( ( 0.113 - 0.000 ) / ( 0.787 - 0.000 ) ) * 1600 = 630.6


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent             | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                         |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           30 |     2109 | 2024-04-29 | Natus Vincere Junior | L   | 0.996      | -            | -                | -                | -         |    -7.99 | Frontsiderr, Pelle, PeTeRoOo, suonko, ZEMO     |
|           29 |     2221 | 2024-04-27 | SINNERS Academy      | L   | 0.983      | -            | -                | -                | -         |   -12.23 | Frontsiderr, karmazynsz, Pelle, PeTeRoOo, ZEMO |
|           28 |     2415 | 2024-04-24 | EPIC DUDES           | W   | 0.964      | 0.289        | 0.000 (0.000)    | 0.042 (0.012)    | 0 (0.000) |     7.99 | Frontsiderr, Pelle, PeTeRoOo, suonko, ZEMO     |
|           27 |     2691 | 2024-04-20 | L&G                  | L   | 0.935      | -            | -                | -                | -         |    -8.97 | Frontsiderr, Pelle, PeTeRoOo, suonko, ZEMO     |
|           26 |     5407 | 2024-02-29 | BAKS Esports         | L   | 0.598      | -            | -                | -                | -         |    -9.55 | baljs, eltrzzi, Frontsiderr, PeTeRoOo, suonko  |
|           25 |     5454 | 2024-02-28 | Lemondogs            | L   | 0.591      | -            | -                | -                | -         |    -9.91 | baljs, eltrzzi, Frontsiderr, PeTeRoOo, suonko  |
|           24 |     5855 | 2024-02-21 | GamerLegion Academy  | L   | 0.544      | -            | -                | -                | -         |    -4.73 | baljs, eltrzzi, Frontsiderr, PeTeRoOo, suonko  |
|           23 |     5869 | 2024-02-21 | los kogutos          | W   | 0.544      | 0.371        | 0.000 (0.000)    | 0.026 (0.005)    | 0 (0.000) |     6.88 | baljs, eltrzzi, Frontsiderr, PeTeRoOo, suonko  |
|           22 |     6344 | 2024-02-13 | ex-K10               | L   | 0.490      | -            | -                | -                | -         |    -3.68 | baljs, eltrzzi, Frontsiderr, PeTeRoOo, suonko  |
|           21 |     6376 | 2024-02-12 | FLuffy Gangsters     | L   | 0.484      | -            | -                | -                | -         |    -8.28 | baljs, eltrzzi, Frontsiderr, PeTeRoOo, suonko  |
|           20 |     6512 | 2024-02-08 | HOTU                 | L   | 0.458      | -            | -                | -                | -         |    -3.35 | baljs, eltrzzi, Frontsiderr, PeTeRoOo, suonko  |
|           19 |     6518 | 2024-02-08 | Team Spirit Academy  | L   | 0.457      | -            | -                | -                | -         |    -4.82 | baljs, eltrzzi, Frontsiderr, PeTeRoOo, suonko  |
|           18 |     6542 | 2024-02-07 | ex-sYnck             | W   | 0.451      | 0.371        | 0.000 (0.000)    | 0.255 (0.043)    | 0 (0.000) |     9.51 | baljs, eltrzzi, Frontsiderr, PeTeRoOo, suonko  |
|           17 |     6617 | 2024-02-05 | GenOne               | W   | 0.437      | 0.371        | 0.000 (0.000)    | 0.089 (0.014)    | 0 (0.000) |     5.35 | baljs, eltrzzi, Frontsiderr, PeTeRoOo, suonko  |
|           16 |     6885 | 2024-02-01 | Soda Gaming          | L   | 0.410      | -            | -                | -                | -         |    -5.71 | baljs, eltrzzi, Frontsiderr, PeTeRoOo, suonko  |
|           15 |     6913 | 2024-01-31 | FAVBET Team          | L   | 0.404      | -            | -                | -                | -         |    -3.05 | baljs, eltrzzi, Frontsiderr, PeTeRoOo, suonko  |
|           14 |     7036 | 2024-01-29 | Gaimin Gladiators    | L   | 0.392      | -            | -                | -                | -         |    -0.32 | baljs, eltrzzi, Frontsiderr, PeTeRoOo, suonko  |
|           13 |     7352 | 2024-01-24 | Permitta Esports     | L   | 0.357      | -            | -                | -                | -         |    -1.56 | baljs, eltrzzi, Frontsiderr, PeTeRoOo, suonko  |
|           12 |     7963 | 2024-01-15 | MOUZ NXT             | L   | 0.296      | -            | -                | -                | -         |    -0.60 | baljs, eltrzzi, Frontsiderr, PeTeRoOo, suonko  |
|           11 |     8010 | 2024-01-14 | Natus Vincere Junior | L   | 0.289      | -            | -                | -                | -         |    -2.75 | baljs, eltrzzi, Frontsiderr, PeTeRoOo, suonko  |
|           10 |     8288 | 2024-01-10 | ROSOMAHA             | W   | 0.262      | 0.303        | 0.000 (0.000)    | 0.145 (0.011)    | 0 (0.000) |     3.79 | baljs, eltrzzi, Frontsiderr, PeTeRoOo, suonko  |
|            9 |     8384 | 2024-01-09 | Betera Esports       | L   | 0.257      | -            | -                | -                | -         |    -2.14 | baljs, eltrzzi, Frontsiderr, PeTeRoOo, suonko  |
|            8 |     8471 | 2024-01-06 | SINNERS Academy      | W   | 0.235      | 0.303        | 0.001 (0.000)    | 0.227 (0.016)    | 0 (0.000) |     4.01 | baljs, eltrzzi, Frontsiderr, PeTeRoOo, suonko  |
|            7 |     8854 | 2023-12-16 | Rebels Gaming        | L   | 0.098      | -            | -                | -                | -         |    -0.18 | baljs, Frontsiderr, PeTeRoOo, suonko, TOAO     |
|            6 |     8999 | 2023-12-15 | B8                   | L   | 0.091      | -            | -                | -                | -         |    -1.92 | baljs, Frontsiderr, PeTeRoOo, suonko, TOAO     |
|            5 |     9236 | 2023-12-10 | RUSH B               | L   | 0.057      | -            | -                | -                | -         |    -0.58 | baljs, Frontsiderr, PeTeRoOo, suonko, TOAO     |
|            4 |     9298 | 2023-12-09 | ALTERNATE aTTaX      | W   | 0.050      | 0.371        | 0.052 (0.001)    | 0.735 (0.014)    | 0 (0.000) |     1.42 | baljs, Frontsiderr, PeTeRoOo, suonko, TOAO     |
|            3 |     9427 | 2023-12-07 | TSM                  | L   | 0.038      | -            | -                | -                | -         |    -0.58 | baljs, Frontsiderr, PeTeRoOo, suonko, TOAO     |
|            2 |     9496 | 2023-12-06 | RUSH B               | W   | 0.031      | 0.371        | 0.001 (0.000)    | 0.446 (0.005)    | 0 (0.000) |     0.66 | baljs, Frontsiderr, PeTeRoOo, suonko, TOAO     |
|            1 |     9574 | 2023-12-05 | ALTERNATE aTTaX      | W   | 0.024      | 0.371        | 0.052 (0.000)    | 0.735 (0.007)    | 0 (0.000) |     0.69 | baljs, Frontsiderr, PeTeRoOo, suonko, TOAO     |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($153.89)
- Divide that value by the 5th highest value among all rosters ($300,806.11)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
