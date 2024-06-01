### Roster Details<br />
Team Name: Complexity Gaming<br />
Roster: EliGE, floppy, Grim, hallzerk, JT<br />
Region: [Americas]( ../standings_americas.md)<br />
<br />
Global Rank: [12](../standings_global.md)<br />
Regional Rank: [2]( ../standings_americas.md)<br />
Final Rank Value:  1591.8<br />
<br />
Final Rank Value (1591.8) = Starting Rank Value (1565.4) + Head To Head Adjustments (26.4)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.631[<sup>1</sup>](#table2)
- Bounty Collected: 0.596[<sup>2</sup>](#table1)
- Opponent Network: 0.244[<sup>2</sup>](#table1)
- LAN Wins: 0.819[<sup>2</sup>](#table1)

The average of these factors is 0.572<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1565.4
- 400 + ( ( 0.572 - 0.000 ) / ( 0.786 - 0.000 ) ) * 1600 = 1565.4


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent          | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                            |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           28 |      142 | 2024-05-27 | MOUZ              | L   | 1.000      | -            | -                | -                | -         |    -3.27 | EliGE, floppy, Grim, hallzerk, JT |
|           27 |      162 | 2024-05-27 | Team Liquid       | L   | 1.000      | -            | -                | -                | -         |   -14.12 | EliGE, floppy, Grim, hallzerk, JT |
|           26 |     1414 | 2024-05-11 | MOUZ              | L   | 1.000      | -            | -                | -                | -         |    -3.63 | EliGE, floppy, Grim, hallzerk, JT |
|           25 |     1571 | 2024-05-09 | Virtus.pro        | W   | 1.000      | 0.889        | 0.271 (0.241)    | 0.331 (0.294)    | 1 (1.000) |    18.24 | EliGE, floppy, Grim, hallzerk, JT |
|           24 |     1755 | 2024-05-05 | Natus Vincere     | W   | 1.000      | 0.889        | 1.000 (0.889)    | 0.253 (0.225)    | 1 (1.000) |    26.37 | EliGE, floppy, Grim, hallzerk, JT |
|           23 |     1922 | 2024-05-02 | HEROIC            | W   | 1.000      | 0.889        | 0.322 (0.286)    | 0.463 (0.412)    | 1 (1.000) |    19.55 | EliGE, floppy, Grim, hallzerk, JT |
|           22 |     2030 | 2024-04-30 | Pera Esports      | W   | 1.000      | 0.889        | 0.028 (0.025)    | 0.574 (0.510)    | 1 (1.000) |     0.68 | EliGE, floppy, Grim, hallzerk, JT |
|           21 |     3949 | 2024-03-24 | FaZe Clan         | L   | 0.756      | -            | -                | -                | -         |    -2.22 | EliGE, floppy, Grim, hallzerk, JT |
|           20 |     4000 | 2024-03-23 | Team Vitality     | L   | 0.750      | -            | -                | -                | -         |    -4.20 | EliGE, floppy, Grim, hallzerk, JT |
|           19 |     4039 | 2024-03-22 | MOUZ              | L   | 0.743      | -            | -                | -                | -         |    -1.99 | EliGE, floppy, Grim, hallzerk, JT |
|           18 |     4082 | 2024-03-21 | HEROIC            | W   | 0.738      | 1.000        | 0.322 (0.237)    | 0.463 (0.342)    | 1 (0.738) |    17.46 | EliGE, floppy, Grim, hallzerk, JT |
|           17 |     4096 | 2024-03-21 | paiN Gaming       | W   | 0.736      | 1.000        | 0.463 (0.341)    | 0.524 (0.386)    | 1 (0.736) |    13.08 | EliGE, floppy, Grim, hallzerk, JT |
|           16 |     4806 | 2024-03-07 | OG                | L   | 0.644      | -            | -                | -                | -         |   -17.90 | EliGE, floppy, Grim, hallzerk, JT |
|           15 |     4996 | 2024-03-04 | Team Liquid       | W   | 0.625      | 0.143        | 0.513 (0.046)    | 0.621 (0.055)    | 1 (0.625) |    12.26 | EliGE, floppy, Grim, hallzerk, JT |
|           14 |     5063 | 2024-03-03 | FURIA Esports     | L   | 0.618      | -            | -                | -                | -         |   -12.64 | EliGE, floppy, Grim, hallzerk, JT |
|           13 |     5184 | 2024-03-02 | BOSS              | W   | 0.610      | 0.143        | 0.016 (0.001)    | 0.315 (0.028)    | 1 (0.610) |     0.44 | EliGE, floppy, Grim, hallzerk, JT |
|           12 |     5224 | 2024-03-01 | Elevate           | W   | 0.604      | 0.143        | -                | 0.475 (0.041)    | 1 (0.604) |     0.43 | EliGE, floppy, Grim, hallzerk, JT |
|           11 |     6411 | 2024-02-05 | Team Falcons      | L   | 0.438      | -            | -                | -                | -         |    -8.20 | EliGE, floppy, Grim, hallzerk, JT |
|           10 |     6461 | 2024-02-04 | Team Spirit       | L   | 0.430      | -            | -                | -                | -         |    -1.70 | EliGE, floppy, Grim, hallzerk, JT |
|            9 |     6499 | 2024-02-03 | Apeks             | W   | 0.424      | 1.000        | 0.085 (0.036)    | 0.345 (0.146)    | 1 (0.424) |     2.05 | EliGE, floppy, Grim, hallzerk, JT |
|            8 |     7185 | 2024-01-23 | Ninjas in Pyjamas | L   | 0.350      | -            | -                | -                | -         |   -10.90 | EliGE, floppy, Grim, hallzerk, JT |
|            7 |     7243 | 2024-01-22 | Natus Vincere     | L   | 0.343      | -            | -                | -                | -         |    -1.69 | EliGE, floppy, Grim, hallzerk, JT |
|            6 |     7763 | 2024-01-13 | Party Astronauts  | W   | 0.286      | -            | -                | -                | -         |     0.28 | EliGE, floppy, Grim, hallzerk, JT |
|            5 |     7812 | 2024-01-12 | NRG               | W   | 0.281      | -            | -                | -                | -         |     0.15 | EliGE, floppy, Grim, hallzerk, JT |
|            4 |     7822 | 2024-01-12 | FLUFFY AIMERS     | W   | 0.280      | -            | -                | -                | -         |     0.05 | EliGE, floppy, Grim, hallzerk, JT |
|            3 |     8599 | 2023-12-16 | The MongolZ       | L   | 0.097      | -            | -                | -                | -         |    -1.33 | EliGE, floppy, Grim, hallzerk, JT |
|            2 |     8714 | 2023-12-15 | GamerLegion       | W   | 0.093      | 0.500        | 0.075 (0.003)    | -                | -         |     0.37 | EliGE, floppy, Grim, hallzerk, JT |
|            1 |     8726 | 2023-12-15 | The MongolZ       | L   | 0.091      | -            | -                | -                | -         |    -1.24 | EliGE, floppy, Grim, hallzerk, JT |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($78,266.94)
- Divide that value by the 5th highest value among all rosters ($300,806.11)
- The final value (0.26) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-05-29 |      1.000 | $4,000.00      | $4,000.00       |
| 2024-05-12 |      1.000 | $45,000.00     | $45,000.00      |
| 2024-03-31 |      0.804 | $20,000.00     | $16,077.78      |
| 2024-03-10 |      0.665 | $5,000.00      | $3,322.57       |
| 2024-02-11 |      0.477 | $16,000.00     | $7,631.11       |
| 2024-01-28 |      0.384 | $5,000.00      | $1,920.14       |
| 2023-12-17 |      0.105 | $3,000.00      | $315.35         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
