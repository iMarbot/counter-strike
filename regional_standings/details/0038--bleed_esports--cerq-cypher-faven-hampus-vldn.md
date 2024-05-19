### Roster Details<br />
Team Name: BLEED Esports<br />
Roster: CeRq, CYPHER, faveN, hampus, VLDN<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [38](../standings_global.md)<br />
Regional Rank: [29]( ../standings_europe.md)<br />
Final Rank Value:  1155.3<br />
<br />
Final Rank Value (1155.3) = Starting Rank Value (1120.7) + Head To Head Adjustments (34.6)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.647[<sup>1</sup>](#table2)
- Bounty Collected: 0.453[<sup>2</sup>](#table1)
- Opponent Network: 0.353[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.363<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1120.7
- 400 + ( ( 0.363 - 0.000 ) / ( 0.806 - 0.000 ) ) * 1600 = 1120.7


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent          | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                             |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           35 |      134 | 2024-05-02 | AMKAL ESPORTS     | L   | 1.000      | -            | -                | -                | -         |   -13.47 | CeRq, CYPHER, faveN, hampus, VLDN  |
|           34 |      213 | 2024-05-01 | MOUZ NXT          | L   | 1.000      | -            | -                | -                | -         |   -20.77 | CeRq, CYPHER, faveN, hampus, VLDN  |
|           33 |      257 | 2024-04-30 | Permitta Esports  | W   | 1.000      | 0.384        | 0.063 (0.024)    | 1.000 (0.384)    | 0 (0.000) |     5.24 | CeRq, CYPHER, faveN, hampus, VLDN  |
|           32 |      420 | 2024-04-26 | Guild Eagles      | W   | 1.000      | 0.435        | -                | 0.586 (0.255)    | 0 (0.000) |     8.31 | CeRq, CYPHER, faveN, hampus, VLDN  |
|           31 |      440 | 2024-04-26 | DMS               | W   | 1.000      | -            | -                | -                | 0 (0.000) |     3.56 | CeRq, CYPHER, faveN, hampus, VLDN  |
|           30 |      528 | 2024-04-24 | Permitta Esports  | W   | 1.000      | 0.435        | 0.063 (0.027)    | 1.000 (0.435)    | 0 (0.000) |     7.11 | CeRq, CYPHER, faveN, hampus, VLDN  |
|           29 |      535 | 2024-04-24 | Nemiga Gaming     | L   | 1.000      | -            | -                | -                | -         |   -13.40 | CeRq, CYPHER, faveN, hampus, VLDN  |
|           28 |      577 | 2024-04-23 | B8                | W   | 1.000      | 0.500        | 0.088 (0.044)    | 0.589 (0.294)    | 0 (0.000) |     8.69 | CeRq, CYPHER, faveN, hampus, VLDN  |
|           27 |      590 | 2024-04-23 | Sashi Esport      | L   | 1.000      | -            | -                | -                | -         |   -14.20 | CeRq, CYPHER, faveN, hampus, VLDN  |
|           26 |      612 | 2024-04-22 | Sangal Esports    | W   | 1.000      | -            | -                | -                | 0 (0.000) |     3.80 | CeRq, CYPHER, faveN, hampus, VLDN  |
|           25 |      615 | 2024-04-22 | Gaimin Gladiators | W   | 1.000      | 0.384        | 0.194 (0.075)    | 0.989 (0.380)    | 0 (0.000) |    23.92 | CeRq, CYPHER, faveN, hampus, VLDN  |
|           24 |      633 | 2024-04-21 | Illuminar Gaming  | W   | 1.000      | -            | -                | -                | 0 (0.000) |     4.59 | CeRq, CYPHER, faveN, hampus, VLDN  |
|           23 |      663 | 2024-04-21 | BIG               | W   | 1.000      | 0.384        | 0.470 (0.181)    | -                | 0 (0.000) |    25.38 | CeRq, faveN, hampus, RuStY, VLDN   |
|           22 |      716 | 2024-04-20 | MOUZ NXT          | W   | 1.000      | 0.500        | 0.215 (0.108)    | 1.000 (0.500)    | 0 (0.000) |    13.63 | CeRq, CYPHER, faveN, hampus, VLDN  |
|           21 |      849 | 2024-04-19 | Team Sampi        | W   | 1.000      | 0.384        | 0.108 (0.042)    | 0.709 (0.272)    | -         |    12.33 | CeRq, CYPHER, faveN, hampus, VLDN  |
|           20 |      906 | 2024-04-18 | ALTERNATE aTTaX   | W   | 1.000      | 0.500        | 0.110 (0.055)    | 0.723 (0.362)    | -         |     9.55 | CeRq, CYPHER, faveN, hampus, VLDN  |
|           19 |      968 | 2024-04-17 | 3DMAX             | L   | 1.000      | -            | -                | -                | -         |   -22.04 | CeRq, CYPHER, faveN, hampus, VLDN  |
|           18 |     1001 | 2024-04-16 | KOI               | W   | 1.000      | 0.384        | 0.066 (0.026)    | -                | -         |    15.64 | CeRq, CYPHER, faveN, hampus, VLDN  |
|           17 |     1023 | 2024-04-16 | SINNERS Esports   | W   | 1.000      | -            | -                | -                | -         |    13.87 | CeRq, CYPHER, faveN, hampus, VLDN  |
|           16 |     1289 | 2024-04-09 | Alliance          | W   | 1.000      | 0.384        | -                | 0.729 (0.280)    | -         |     7.28 | CeRq, CYPHER, faveN, hampus, VLDN  |
|           15 |     1302 | 2024-04-09 | HAVU Gaming       | W   | 1.000      | -            | -                | -                | -         |     5.56 | CeRq, CYPHER, faveN, hampus, VLDN  |
|           14 |     1441 | 2024-04-05 | BetBoom Team      | L   | 0.998      | -            | -                | -                | -         |    -4.51 | CeRq, CYPHER, faveN, hampus, VLDN  |
|           13 |     1446 | 2024-04-05 | Alliance          | W   | 0.997      | -            | -                | -                | -         |     7.93 | CeRq, CYPHER, faveN, hampus, VLDN  |
|           12 |     1490 | 2024-04-04 | BenchedHeroes     | W   | 0.991      | -            | -                | -                | -         |     0.72 | CeRq, CYPHER, faveN, hampus, VLDN  |
|           11 |     1497 | 2024-04-04 | BetBoom Team      | L   | 0.991      | -            | -                | -                | -         |    -4.52 | CeRq, CYPHER, faveN, hampus, VLDN  |
|           10 |     1578 | 2024-04-02 | Passion UA        | W   | 0.978      | 0.384        | 0.114 (0.043)    | 0.980 (0.368)    | -         |     9.66 | CeRq, CYPHER, faveN, hampus, RuStY |
|            9 |     4094 | 2024-02-01 | Into The Breach   | L   | 0.570      | -            | -                | -                | -         |   -13.99 | CeRq, CYPHER, faveN, hampus, lauNX |
|            8 |     4189 | 2024-01-29 | RUBY              | L   | 0.553      | -            | -                | -                | -         |   -13.51 | CeRq, CYPHER, faveN, hampus, lauNX |
|            7 |     4201 | 2024-01-29 | Metizport         | L   | 0.550      | -            | -                | -                | -         |   -11.22 | CeRq, CYPHER, faveN, hampus, lauNX |
|            6 |     4217 | 2024-01-28 | Into The Breach   | L   | 0.545      | -            | -                | -                | -         |   -14.38 | CeRq, CYPHER, faveN, hampus, lauNX |
|            5 |     4365 | 2024-01-25 | Into The Breach   | W   | 0.523      | -            | -                | -                | -         |     2.77 | CeRq, CYPHER, faveN, hampus, lauNX |
|            4 |     5076 | 2024-01-09 | Entropiq          | L   | 0.419      | -            | -                | -                | -         |   -11.28 | CeRq, CYPHER, faveN, hampus, lauNX |
|            3 |     5083 | 2024-01-09 | IKLA              | W   | 0.419      | -            | -                | -                | -         |     1.16 | CeRq, CYPHER, faveN, hampus, lauNX |
|            2 |     5089 | 2024-01-09 | Sangal Esports    | W   | 0.418      | -            | -                | -                | -         |     1.01 | CeRq, CYPHER, faveN, hampus, lauNX |
|            1 |     5117 | 2024-01-09 | NextUp            | W   | 0.418      | -            | -                | -                | -         |     0.23 | CeRq, CYPHER, faveN, hampus, lauNX |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($45,000.00)
- Divide that value by the 5th highest value among all rosters ($158,437.64)
- The final value (0.28) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-04-24 |      1.000 | $25,000.00     | $25,000.00      |
| 2024-04-22 |      1.000 | $20,000.00     | $20,000.00      |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
