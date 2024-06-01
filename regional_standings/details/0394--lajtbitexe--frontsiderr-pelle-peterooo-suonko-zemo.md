### Roster Details<br />
Team Name: lajtbitexe<br />
Roster: Frontsiderr, Pelle, PeTeRoOo, suonko, ZEMO<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [394](../standings_global.md)<br />
Regional Rank: [236]( ../standings_europe.md)<br />
Final Rank Value:  556.7<br />
<br />
Final Rank Value (556.7) = Starting Rank Value (612.4) + Head To Head Adjustments (-55.8)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.233[<sup>1</sup>](#table2)
- Bounty Collected: 0.178[<sup>2</sup>](#table1)
- Opponent Network: 0.007[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.104<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 612.4
- 400 + ( ( 0.104 - 0.000 ) / ( 0.786 - 0.000 ) ) * 1600 = 612.4


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
|           28 |     2074 | 2024-04-29 | Natus Vincere Junior | L   | 0.996      | -            | -                | -                | -         |    -7.80 | Frontsiderr, Pelle, PeTeRoOo, suonko, ZEMO     |
|           27 |     2186 | 2024-04-27 | SINNERS Academy      | L   | 0.983      | -            | -                | -                | -         |   -11.04 | Frontsiderr, karmazynsz, Pelle, PeTeRoOo, ZEMO |
|           26 |     2372 | 2024-04-24 | EPIC DUDES           | W   | 0.964      | 0.289        | 0.000 (0.000)    | 0.042 (0.012)    | 0 (0.000) |     8.85 | Frontsiderr, Pelle, PeTeRoOo, suonko, ZEMO     |
|           25 |     2637 | 2024-04-20 | L&G                  | L   | 0.935      | -            | -                | -                | -         |    -8.26 | Frontsiderr, Pelle, PeTeRoOo, suonko, ZEMO     |
|           24 |     5258 | 2024-02-29 | BAKS Esports         | L   | 0.598      | -            | -                | -                | -         |    -8.79 | baljs, eltrzzi, Frontsiderr, PeTeRoOo, suonko  |
|           23 |     5303 | 2024-02-28 | Lemondogs            | L   | 0.591      | -            | -                | -                | -         |    -9.33 | baljs, eltrzzi, Frontsiderr, PeTeRoOo, suonko  |
|           22 |     5692 | 2024-02-21 | GamerLegion Academy  | L   | 0.544      | -            | -                | -                | -         |    -4.26 | baljs, eltrzzi, Frontsiderr, PeTeRoOo, suonko  |
|           21 |     5706 | 2024-02-21 | los kogutos          | W   | 0.544      | 0.371        | 0.000 (0.000)    | 0.026 (0.005)    | 0 (0.000) |     7.51 | baljs, eltrzzi, Frontsiderr, PeTeRoOo, suonko  |
|           20 |     6159 | 2024-02-13 | ex-K10               | L   | 0.490      | -            | -                | -                | -         |    -3.38 | baljs, eltrzzi, Frontsiderr, PeTeRoOo, suonko  |
|           19 |     6191 | 2024-02-12 | ex-FLuffy Gangsters  | L   | 0.484      | -            | -                | -                | -         |    -9.14 | baljs, eltrzzi, Frontsiderr, PeTeRoOo, suonko  |
|           18 |     6324 | 2024-02-08 | HOTU                 | L   | 0.458      | -            | -                | -                | -         |    -3.12 | baljs, eltrzzi, Frontsiderr, PeTeRoOo, suonko  |
|           17 |     6330 | 2024-02-08 | Team Spirit Academy  | L   | 0.457      | -            | -                | -                | -         |    -4.40 | baljs, eltrzzi, Frontsiderr, PeTeRoOo, suonko  |
|           16 |     6418 | 2024-02-05 | GenOne               | W   | 0.437      | 0.371        | 0.000 (0.000)    | 0.089 (0.014)    | 0 (0.000) |     5.61 | baljs, eltrzzi, Frontsiderr, PeTeRoOo, suonko  |
|           15 |     6676 | 2024-02-01 | Soda Gaming          | L   | 0.410      | -            | -                | -                | -         |    -5.88 | baljs, eltrzzi, Frontsiderr, PeTeRoOo, suonko  |
|           14 |     6704 | 2024-01-31 | FAVBET Team          | L   | 0.404      | -            | -                | -                | -         |    -2.88 | baljs, eltrzzi, Frontsiderr, PeTeRoOo, suonko  |
|           13 |     6820 | 2024-01-29 | Gaimin Gladiators    | L   | 0.392      | -            | -                | -                | -         |    -0.29 | baljs, eltrzzi, Frontsiderr, PeTeRoOo, suonko  |
|           12 |     7119 | 2024-01-24 | Permitta Esports     | L   | 0.357      | -            | -                | -                | -         |    -1.47 | baljs, eltrzzi, Frontsiderr, PeTeRoOo, suonko  |
|           11 |     7712 | 2024-01-15 | MOUZ NXT             | L   | 0.296      | -            | -                | -                | -         |    -0.56 | baljs, eltrzzi, Frontsiderr, PeTeRoOo, suonko  |
|           10 |     7757 | 2024-01-14 | Natus Vincere Junior | L   | 0.289      | -            | -                | -                | -         |    -2.56 | baljs, eltrzzi, Frontsiderr, PeTeRoOo, suonko  |
|            9 |     8034 | 2024-01-10 | ROSOMAHA             | W   | 0.262      | 0.303        | 0.000 (0.000)    | 0.124 (0.010)    | 0 (0.000) |     4.00 | baljs, eltrzzi, Frontsiderr, PeTeRoOo, suonko  |
|            8 |     8130 | 2024-01-09 | Betera Esports       | L   | 0.257      | -            | -                | -                | -         |    -1.99 | baljs, eltrzzi, Frontsiderr, PeTeRoOo, suonko  |
|            7 |     8216 | 2024-01-06 | SINNERS Academy      | W   | 0.235      | 0.303        | 0.001 (0.000)    | 0.227 (0.016)    | 0 (0.000) |     4.20 | baljs, eltrzzi, Frontsiderr, PeTeRoOo, suonko  |
|            6 |     8738 | 2023-12-15 | B8                   | L   | 0.091      | -            | -                | -                | -         |    -1.85 | baljs, Frontsiderr, PeTeRoOo, suonko, TOAO     |
|            5 |     8970 | 2023-12-10 | RUSH B               | L   | 0.057      | -            | -                | -                | -         |    -0.54 | baljs, Frontsiderr, PeTeRoOo, suonko, TOAO     |
|            4 |     9032 | 2023-12-09 | ALTERNATE aTTaX      | W   | 0.050      | 0.371        | 0.004 (0.000)    | 0.103 (0.002)    | 0 (0.000) |     1.02 | baljs, Frontsiderr, PeTeRoOo, suonko, TOAO     |
|            3 |     9154 | 2023-12-07 | TSM                  | L   | 0.038      | -            | -                | -                | -         |    -0.55 | baljs, Frontsiderr, PeTeRoOo, suonko, TOAO     |
|            2 |     9215 | 2023-12-06 | RUSH B               | W   | 0.031      | 0.371        | 0.001 (0.000)    | 0.446 (0.005)    | 0 (0.000) |     0.68 | baljs, Frontsiderr, PeTeRoOo, suonko, TOAO     |
|            1 |     9292 | 2023-12-05 | ALTERNATE aTTaX      | W   | 0.024      | 0.371        | 0.004 (0.000)    | 0.103 (0.001)    | 0 (0.000) |     0.49 | baljs, Frontsiderr, PeTeRoOo, suonko, TOAO     |

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
