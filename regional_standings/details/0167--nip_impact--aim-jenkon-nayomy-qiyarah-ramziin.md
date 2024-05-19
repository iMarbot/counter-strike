### Roster Details<br />
Team Name: NIP Impact<br />
Roster: aiM, jenkon, Nayomy, Qiyarah, ramziiN<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [167](../standings_global.md)<br />
Regional Rank: [112]( ../standings_europe.md)<br />
Final Rank Value:  757.3<br />
<br />
Final Rank Value (757.3) = Starting Rank Value (734.4) + Head To Head Adjustments (22.9)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.340[<sup>1</sup>](#table2)
- Bounty Collected: 0.289[<sup>2</sup>](#table1)
- Opponent Network: 0.045[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.169<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 734.4
- 400 + ( ( 0.169 - 0.000 ) / ( 0.806 - 0.000 ) ) * 1600 = 734.4


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent              | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           22 |      365 | 2024-04-27 | Team Pigeons          | L   | 1.000      | -            | -                | -                | -         |    -7.88 | aiM, jenkon, Nayomy, Qiyarah, ramziiN |
|           21 |      369 | 2024-04-27 | ENCE Athena           | W   | 1.000      | 0.143        | 0.009 (0.001)    | 0.244 (0.035)    | 0 (0.000) |    13.65 | aiM, jenkon, Nayomy, Qiyarah, ramziiN |
|           20 |      376 | 2024-04-27 | Permitta W            | W   | 1.000      | 0.143        | 0.000 (0.000)    | 0.070 (0.010)    | 0 (0.000) |     6.64 | aiM, jenkon, Nayomy, Qiyarah, ramziiN |
|           19 |      384 | 2024-04-27 | AKA HERO Althea       | W   | 1.000      | -            | -                | -                | 0 (0.000) |     3.99 | aiM, jenkon, Nayomy, Qiyarah, ramziiN |
|           18 |      813 | 2024-04-19 | BIG EQUIPA            | L   | 1.000      | -            | -                | -                | -         |   -15.53 | aiM, jenkon, Nayomy, Qiyarah, ramziiN |
|           17 |     1043 | 2024-04-15 | NAVI Javelins         | L   | 1.000      | -            | -                | -                | -         |   -11.68 | aiM, jenkon, Nayomy, Qiyarah, ramziiN |
|           16 |     1066 | 2024-04-14 | Team Pigeons          | L   | 1.000      | -            | -                | -                | -         |    -8.50 | aiM, jenkon, Nayomy, Qiyarah, ramziiN |
|           15 |     1102 | 2024-04-13 | Astralis Women        | W   | 1.000      | 0.303        | 0.007 (0.002)    | 0.101 (0.031)    | 0 (0.000) |     9.34 | aiM, jenkon, Nayomy, Qiyarah, ramziiN |
|           14 |     1175 | 2024-04-11 | Let Her Cook          | W   | 1.000      | 0.303        | -                | 0.191 (0.058)    | 0 (0.000) |     8.62 | aiM, jenkon, Nayomy, Qiyarah, ramziiN |
|           13 |     1221 | 2024-04-10 | Guild Esports         | L   | 1.000      | -            | -                | -                | -         |   -16.89 | aiM, jenkon, Nayomy, Qiyarah, ramziiN |
|           12 |     1292 | 2024-04-09 | NAVI Javelins         | W   | 1.000      | 0.303        | 0.062 (0.019)    | 0.328 (0.099)    | 0 (0.000) |    19.74 | aiM, jenkon, Nayomy, Qiyarah, ramziiN |
|           11 |     1367 | 2024-04-07 | Team Pigeons          | L   | 1.000      | -            | -                | -                | -         |    -9.41 | aiM, jenkon, Nayomy, Qiyarah, ramziiN |
|           10 |     1374 | 2024-04-07 | Fearless Cheetahs     | W   | 1.000      | 0.262        | 0.014 (0.004)    | 0.199 (0.052)    | 0 (0.000) |    14.38 | aiM, jenkon, Nayomy, Qiyarah, ramziiN |
|            9 |     1412 | 2024-04-06 | Guild Esports         | W   | 1.000      | 0.262        | 0.010 (0.003)    | 0.194 (0.051)    | 0 (0.000) |    15.65 | aiM, jenkon, Nayomy, Qiyarah, ramziiN |
|            8 |     1422 | 2024-04-06 | Nemesis (Female team) | W   | 1.000      | 0.262        | 0.004 (0.001)    | -                | 0 (0.000) |     8.39 | aiM, jenkon, Nayomy, Qiyarah, ramziiN |
|            7 |     1532 | 2024-04-03 | Astralis Women        | W   | 0.985      | 0.331        | 0.007 (0.002)    | 0.101 (0.033)    | 0 (0.000) |    11.04 | aiM, jenkon, Nayomy, Qiyarah, ramziiN |
|            6 |     2020 | 2024-03-20 | ENCE Athena           | W   | 0.892      | 0.331        | 0.009 (0.003)    | 0.244 (0.072)    | -         |    14.41 | aiM, jenkon, Nayomy, Qiyarah, ramziiN |
|            5 |     2566 | 2024-03-07 | Team Pigeons          | L   | 0.805      | -            | -                | -                | -         |    -7.22 | aiM, jenkon, Nayomy, Qiyarah, ramziiN |
|            4 |     2810 | 2024-03-03 | BIG EQUIPA            | L   | 0.778      | -            | -                | -                | -         |   -11.86 | aiM, jenkon, Nayomy, Qiyarah, ramziiN |
|            3 |     2875 | 2024-03-02 | VIOLET                | W   | 0.771      | 0.250        | 0.001 (0.000)    | 0.056 (0.011)    | -         |     9.42 | aiM, jenkon, Nayomy, Qiyarah, ramziiN |
|            2 |     3177 | 2024-02-24 | Team Spirit Female    | L   | 0.723      | -            | -                | -                | -         |   -11.68 | aiM, jenkon, Nayomy, Qiyarah, ramziiN |
|            1 |     3956 | 2024-02-03 | VIOLET                | L   | 0.585      | -            | -                | -                | -         |   -11.68 | aiM, buhnny, jenkon, Nayomy, Qiyarah  |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($1,821.08)
- Divide that value by the 5th highest value among all rosters ($158,437.64)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-04-27 |      1.000 | $321.08        | $321.08         |
| 2024-04-21 |      1.000 | $1,250.00      | $1,250.00       |
| 2024-04-07 |      1.000 | $250.00        | $250.00         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
