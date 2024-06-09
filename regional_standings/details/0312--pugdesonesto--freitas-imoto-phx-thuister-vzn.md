### Roster Details<br />
Team Name: pugdesonesto<br />
Roster: freitas, imoto, phx, Thuister, vzn<br />
Region: [Americas]( ../standings_americas.md)<br />
<br />
Global Rank: [312](../standings_global.md)<br />
Regional Rank: [70]( ../standings_americas.md)<br />
Final Rank Value:  636.3<br />
<br />
Final Rank Value (636.3) = Starting Rank Value (646.4) + Head To Head Adjustments (-10.1)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.253[<sup>1</sup>](#table2)
- Bounty Collected: 0.222[<sup>2</sup>](#table1)
- Opponent Network: 0.010[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.121<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 646.4
- 400 + ( ( 0.121 - 0.000 ) / ( 0.787 - 0.000 ) ) * 1600 = 646.4


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
|           22 |      831 | 2024-05-18 | Peak Academy            | W   | 1.000      | 0.143        | 0.001 (0.000)    | 0.083 (0.012)    | 0 (0.000) |    16.53 | freitas, imoto, phx, Thuister, vzn         |
|           21 |      841 | 2024-05-18 | MX Team                 | W   | 1.000      | 0.143        | 0.000 (0.000)    | 0.076 (0.011)    | 0 (0.000) |    15.05 | freitas, imoto, phx, Thuister, vzn         |
|           20 |      852 | 2024-05-18 | phantom troupe          | W   | 1.000      | 0.143        | 0.000 (0.000)    | 0.111 (0.016)    | 0 (0.000) |    16.25 | freitas, imoto, phx, Thuister, vzn         |
|           19 |      863 | 2024-05-18 | Atrix Esports           | W   | 1.000      | 0.143        | 0.006 (0.001)    | 0.190 (0.027)    | 0 (0.000) |    19.41 | freitas, imoto, phx, Thuister, vzn         |
|           18 |     2188 | 2024-04-27 | Sharks Youngsters       | L   | 0.985      | -            | -                | -                | -         |   -13.76 | freitas, imoto, phx, Thuister, vzn         |
|           17 |     2191 | 2024-04-27 | MIBR Female             | W   | 0.984      | 0.143        | 0.015 (0.002)    | 0.227 (0.032)    | 0 (0.000) |    20.52 | freitas, imoto, phx, Thuister, vzn         |
|           16 |     2201 | 2024-04-27 | Atrix Esports           | L   | 0.984      | -            | -                | -                | -         |   -10.10 | freitas, imoto, phx, Thuister, vzn         |
|           15 |     2264 | 2024-04-26 | 2Game Esports           | L   | 0.979      | -            | -                | -                | -         |   -11.34 | freitas, imoto, phx, Thuister, vzn         |
|           14 |     4079 | 2024-03-23 | SoJoga                  | L   | 0.751      | -            | -                | -                | -         |   -10.25 | Farw, k1not1, Patoz1k, pkN, telezin        |
|           13 |     4089 | 2024-03-23 | eSports Recife          | L   | 0.751      | -            | -                | -                | -         |   -10.01 | freitas, imoto, kxr, protado, vzn          |
|           12 |     5663 | 2024-02-24 | SoJoga                  | L   | 0.565      | -            | -                | -                | -         |    -8.41 | freitas, Machado, ntx, Thuister, vzn       |
|           11 |     5682 | 2024-02-24 | phantom troupe          | L   | 0.564      | -            | -                | -                | -         |    -9.24 | freitas, Machado, ntx, Thuister, vzn       |
|           10 |     7025 | 2024-01-29 | Bombril 1001 Utilidades | L   | 0.392      | -            | -                | -                | -         |    -6.13 | heartless, lcf, Lich, MITHPUTTINI, spinnie |
|            9 |     7333 | 2024-01-24 | Sharks Youngsters       | L   | 0.358      | -            | -                | -                | -         |    -5.26 | freitas, imoto, kxr, N3blina, Thuister     |
|            8 |     7402 | 2024-01-23 | Corinthians Esports     | L   | 0.352      | -            | -                | -                | -         |    -5.99 | hazart, ph1, pooldolsk, rainny, zock9      |
|            7 |     7637 | 2024-01-19 | MIBR Academy            | L   | 0.325      | -            | -                | -                | -         |    -4.38 | freitas, imoto, kxr, N3blina, Thuister     |
|            6 |     8426 | 2024-01-08 | Corinthians Esports     | L   | 0.252      | -            | -                | -                | -         |    -4.31 | freitas, imoto, kxr, N3blina, Thuister     |
|            5 |     8617 | 2023-12-21 | SOLOVE                  | W   | 0.132      | 0.143        | 0.000 (0.000)    | 0.035 (0.001)    | 0 (0.000) |     1.85 | freitas, imoto, kxr, stormzyn, Thuister    |
|            4 |     8692 | 2023-12-17 | Corinthians Esports     | L   | 0.105      | -            | -                | -                | -         |    -1.88 | japinha, ph1, pooldolsk, rainny, zock9     |
|            3 |     8828 | 2023-12-16 | 9z Academy              | L   | 0.098      | -            | -                | -                | -         |    -1.45 | freitas, imoto, kxr, N3blina, Thuister     |
|            2 |     8838 | 2023-12-16 | phantom troupe          | W   | 0.098      | 0.143        | 0.000 (0.000)    | 0.032 (0.000)    | 0 (0.000) |     1.26 | FasteR, n0page, nth, redi, Riider          |
|            1 |     8861 | 2023-12-16 | Romanticos              | W   | 0.097      | 0.143        | 0.001 (0.000)    | 0.132 (0.002)    | 0 (0.000) |     1.52 | freitas, imoto, kxr, N3blina, Thuister     |

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
