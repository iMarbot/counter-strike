### Roster Details<br />
Team Name: Hawks<br />
Roster: guidimon, KUN, matinaso, pablek, pegin<br />
Region: [Americas]( ../standings_americas.md)<br />
<br />
Global Rank: [293](../standings_global.md)<br />
Regional Rank: [64]( ../standings_americas.md)<br />
Final Rank Value:  650.2<br />
<br />
Final Rank Value (650.2) = Starting Rank Value (640.3) + Head To Head Adjustments (9.9)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.254[<sup>1</sup>](#table2)
- Bounty Collected: 0.209[<sup>2</sup>](#table1)
- Opponent Network: 0.010[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.118<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 640.3
- 400 + ( ( 0.118 - 0.000 ) / ( 0.787 - 0.000 ) ) * 1600 = 640.3


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent                | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                  |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           12 |     4006 | 2024-03-25 | MIBR Academy            | L   | 0.765      | -            | -                | -                | -         |   -10.14 | guidimon, KUN, matinaso, pablek, pegin  |
|           11 |     4120 | 2024-03-22 | Bombril 1001 Utilidades | L   | 0.745      | -            | -                | -                | -         |   -11.04 | guidimon, KUN, matinaso, pablek, pegin  |
|           10 |     4218 | 2024-03-20 | Intense Game            | L   | 0.732      | -            | -                | -                | -         |   -10.10 | guidimon, KUN, matinaso, pablek, pegin  |
|            9 |     4226 | 2024-03-20 | Sharks Youngsters       | W   | 0.731      | 0.143        | 0.003 (0.000)    | 0.407 (0.043)    | 0 (0.000) |    10.17 | guidimon, KUN, matinaso, pablek, pegin  |
|            8 |     5498 | 2024-02-27 | NIGERIA 96              | W   | 0.585      | 0.143        | 0.001 (0.000)    | 0.140 (0.012)    | 0 (0.000) |     8.63 | guidimon, KUN, nacho, nasher, pablek    |
|            7 |     5603 | 2024-02-25 | SoJoga                  | W   | 0.571      | 0.143        | 0.000 (0.000)    | 0.138 (0.011)    | 0 (0.000) |     9.16 | Colt, k1not1, Patoz1k, pkN, telezin     |
|            6 |     5655 | 2024-02-24 | NIGERIA 96              | L   | 0.565      | -            | -                | -                | -         |    -9.46 | deemO, leozik4, nv1nJ, predict, t9mpest |
|            5 |     5662 | 2024-02-24 | Myth e-Sports           | W   | 0.565      | 0.143        | 0.000 (0.000)    | 0.041 (0.003)    | 0 (0.000) |     7.94 | guidimon, KUN, nacho, nasher, pablek    |
|            4 |     5668 | 2024-02-24 | SoJoga                  | W   | 0.564      | 0.143        | 0.000 (0.000)    | 0.138 (0.011)    | 0 (0.000) |     8.50 | guidimon, KUN, nacho, nasher, pablek    |
|            3 |     5681 | 2024-02-24 | MIBR Female             | W   | 0.564      | 0.143        | 0.015 (0.001)    | 0.227 (0.018)    | 0 (0.000) |    10.83 | Babs, dani, ferzy, khizha, REGIANE      |
|            2 |     5982 | 2024-02-19 | 9z Team                 | L   | 0.532      | -            | -                | -                | -         |    -0.54 | guidimon, KUN, nacho, nasher, pablek    |
|            1 |     6259 | 2024-02-14 | w7m esports             | L   | 0.499      | -            | -                | -                | -         |    -4.06 | guidimon, KUN, nacho, nasher, pablek    |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($352.54)
- Divide that value by the 5th highest value among all rosters ($300,806.11)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
