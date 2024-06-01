### Roster Details<br />
Team Name: pugdesonesto<br />
Roster: freitas, imoto, phx, Thuister, vzn<br />
Region: [Americas]( ../standings_americas.md)<br />
<br />
Global Rank: [302](../standings_global.md)<br />
Regional Rank: [69]( ../standings_americas.md)<br />
Final Rank Value:  640.9<br />
<br />
Final Rank Value (640.9) = Starting Rank Value (646.7) + Head To Head Adjustments (-5.8)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.253[<sup>1</sup>](#table2)
- Bounty Collected: 0.222[<sup>2</sup>](#table1)
- Opponent Network: 0.010[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.121<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 646.7
- 400 + ( ( 0.121 - 0.000 ) / ( 0.786 - 0.000 ) ) * 1600 = 646.7


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent                | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                     |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           21 |      819 | 2024-05-18 | Peak Academy            | W   | 1.000      | 0.143        | 0.001 (0.000)    | 0.083 (0.012)    | 0 (0.000) |    16.40 | freitas, imoto, phx, Thuister, vzn         |
|           20 |      829 | 2024-05-18 | MX Team                 | W   | 1.000      | 0.143        | 0.000 (0.000)    | 0.076 (0.011)    | 0 (0.000) |    14.85 | freitas, imoto, phx, Thuister, vzn         |
|           19 |      840 | 2024-05-18 | phantom troupe          | W   | 1.000      | 0.143        | 0.000 (0.000)    | 0.111 (0.016)    | 0 (0.000) |    16.05 | freitas, imoto, phx, Thuister, vzn         |
|           18 |      851 | 2024-05-18 | Atrix Esports           | W   | 1.000      | 0.143        | 0.006 (0.001)    | 0.190 (0.027)    | 0 (0.000) |    19.22 | freitas, imoto, phx, Thuister, vzn         |
|           17 |     2153 | 2024-04-27 | Sharks Youngsters       | L   | 0.985      | -            | -                | -                | -         |   -13.55 | freitas, imoto, phx, Thuister, vzn         |
|           16 |     2156 | 2024-04-27 | MIBR Female             | W   | 0.984      | 0.143        | 0.015 (0.002)    | 0.217 (0.031)    | 0 (0.000) |    20.31 | freitas, imoto, phx, Thuister, vzn         |
|           15 |     2166 | 2024-04-27 | Atrix Esports           | L   | 0.984      | -            | -                | -                | -         |   -10.29 | freitas, imoto, phx, Thuister, vzn         |
|           14 |     2228 | 2024-04-26 | 2Game Esports           | L   | 0.979      | -            | -                | -                | -         |   -11.49 | freitas, imoto, phx, Thuister, vzn         |
|           13 |     3981 | 2024-03-23 | SoJoga                  | L   | 0.751      | -            | -                | -                | -         |   -10.40 | Farw, k1not1, Patoz1k, pkN, telezin        |
|           12 |     3992 | 2024-03-23 | eSports Recife          | L   | 0.751      | -            | -                | -                | -         |   -10.17 | freitas, imoto, kxr, protado, vzn          |
|           11 |     5503 | 2024-02-24 | SoJoga                  | L   | 0.565      | -            | -                | -                | -         |    -8.55 | freitas, Machado, ntx, Thuister, vzn       |
|           10 |     5522 | 2024-02-24 | phantom troupe          | L   | 0.564      | -            | -                | -                | -         |    -9.39 | freitas, Machado, ntx, Thuister, vzn       |
|            9 |     6809 | 2024-01-29 | Bombril 1001 Utilidades | L   | 0.392      | -            | -                | -                | -         |    -6.22 | heartless, lcf, Lich, MITHPUTTINI, spinnie |
|            8 |     7104 | 2024-01-24 | Sharks Youngsters       | L   | 0.358      | -            | -                | -                | -         |    -5.10 | freitas, imoto, kxr, N3blina, Thuister     |
|            7 |     7393 | 2024-01-19 | MIBR Academy            | L   | 0.325      | -            | -                | -                | -         |    -4.41 | freitas, imoto, kxr, N3blina, Thuister     |
|            6 |     8172 | 2024-01-08 | Corinthians Esports     | L   | 0.252      | -            | -                | -                | -         |    -4.31 | freitas, imoto, kxr, N3blina, Thuister     |
|            5 |     8360 | 2023-12-21 | SOLOVE                  | W   | 0.132      | 0.143        | 0.000 (0.000)    | 0.035 (0.001)    | 0 (0.000) |     1.85 | freitas, imoto, kxr, stormzyn, Thuister    |
|            4 |     8435 | 2023-12-17 | CEBOLOS                 | L   | 0.105      | -            | -                | -                | -         |    -1.95 | japinha, ph1, pooldolsk, rainny, zock9     |
|            3 |     8568 | 2023-12-16 | 9z Academy              | L   | 0.098      | -            | -                | -                | -         |    -1.44 | freitas, imoto, kxr, N3blina, Thuister     |
|            2 |     8578 | 2023-12-16 | phantom troupe          | W   | 0.098      | 0.143        | 0.000 (0.000)    | 0.032 (0.000)    | 0 (0.000) |     1.26 | FasteR, n0page, nth, redi, Riider          |
|            1 |     8600 | 2023-12-16 | Romanticos              | W   | 0.097      | 0.143        | 0.001 (0.000)    | 0.132 (0.002)    | 0 (0.000) |     1.52 | freitas, imoto, kxr, N3blina, Thuister     |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($339.06)
- Divide that value by the 5th highest value among all rosters ($300,806.11)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-05-19 |      1.000 | $313.44        | $313.44         |
| 2023-12-21 |      0.133 | $193.25        | $25.62          |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
