### Roster Details<br />
Team Name: NIP Impact<br />
Roster: Nayomy, Qiyarah, ramziiN, spike, vilga<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [190](../standings_global.md)<br />
Regional Rank: [129]( ../standings_europe.md)<br />
Final Rank Value:  731.8<br />
<br />
Final Rank Value (731.8) = Starting Rank Value (713.3) + Head To Head Adjustments (18.5)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.314[<sup>1</sup>](#table2)
- Bounty Collected: 0.261[<sup>2</sup>](#table1)
- Opponent Network: 0.042[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.154<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 713.3
- 400 + ( ( 0.154 - 0.000 ) / ( 0.787 - 0.000 ) ) * 1600 = 713.3


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent           | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                 |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           30 |      211 | 2024-05-26 | Crescent           | L   | 1.000      | -            | -                | -                | -         |   -18.20 | Nayomy, Qiyarah, ramziiN, spike, vilga |
|           29 |      226 | 2024-05-26 | ex-FORZE Ladies    | W   | 1.000      | 0.250        | 0.005 (0.001)    | 0.164 (0.041)    | 0 (0.000) |    13.10 | Nayomy, Qiyarah, ramziiN, spike, vilga |
|           28 |      279 | 2024-05-25 | 5bites             | W   | 1.000      | -            | -                | -                | 0 (0.000) |     3.81 | Nayomy, Qiyarah, ramziiN, spike, vilga |
|           27 |      813 | 2024-05-19 | Team Pigeons       | L   | 1.000      | -            | -                | -                | -         |    -9.17 | aiM, Nayomy, Qiyarah, ramziiN, vilga   |
|           26 |      893 | 2024-05-18 | ex-Guild Esports   | W   | 1.000      | 0.281        | 0.005 (0.001)    | 0.166 (0.047)    | 0 (0.000) |    14.74 | aiM, Nayomy, Qiyarah, ramziiN, vilga   |
|           25 |      929 | 2024-05-18 | Let Her Cook       | W   | 1.000      | 0.281        | -                | 0.156 (0.044)    | 0 (0.000) |    10.85 | aiM, Nayomy, Qiyarah, ramziiN, vilga   |
|           24 |     2218 | 2024-04-27 | Team Pigeons       | L   | 0.983      | -            | -                | -                | -         |    -9.55 | aiM, jenkon, Nayomy, Qiyarah, ramziiN  |
|           23 |     2223 | 2024-04-27 | ENCE Athena        | W   | 0.983      | 0.143        | 0.004 (0.001)    | 0.215 (0.030)    | 0 (0.000) |    14.14 | aiM, jenkon, Nayomy, Qiyarah, ramziiN  |
|           22 |     2231 | 2024-04-27 | Permitta W         | W   | 0.982      | -            | -                | -                | 0 (0.000) |     7.44 | aiM, jenkon, Nayomy, Qiyarah, ramziiN  |
|           21 |     2242 | 2024-04-27 | AKA HERO Althea    | W   | 0.982      | -            | -                | -                | 0 (0.000) |     4.75 | aiM, jenkon, Nayomy, Qiyarah, ramziiN  |
|           20 |     2747 | 2024-04-19 | BIG EQUIPA         | L   | 0.930      | -            | -                | -                | -         |   -13.19 | aiM, jenkon, Nayomy, Qiyarah, ramziiN  |
|           19 |     3013 | 2024-04-15 | NAVI Javelins      | L   | 0.904      | -            | -                | -                | -         |   -11.08 | aiM, jenkon, Nayomy, Qiyarah, ramziiN  |
|           18 |     3042 | 2024-04-14 | Team Pigeons       | L   | 0.897      | -            | -                | -                | -         |    -9.52 | aiM, jenkon, Nayomy, Qiyarah, ramziiN  |
|           17 |     3088 | 2024-04-13 | Astralis Women     | W   | 0.890      | 0.303        | 0.003 (0.001)    | -                | 0 (0.000) |     9.16 | aiM, jenkon, Nayomy, Qiyarah, ramziiN  |
|           16 |     3185 | 2024-04-11 | Let Her Cook       | W   | 0.877      | 0.303        | -                | 0.156 (0.041)    | 0 (0.000) |     8.72 | aiM, jenkon, Nayomy, Qiyarah, ramziiN  |
|           15 |     3247 | 2024-04-10 | ex-Guild Esports   | L   | 0.870      | -            | -                | -                | -         |   -13.91 | aiM, jenkon, Nayomy, Qiyarah, ramziiN  |
|           14 |     3329 | 2024-04-09 | NAVI Javelins      | W   | 0.863      | 0.303        | 0.024 (0.006)    | 0.265 (0.069)    | 0 (0.000) |    16.61 | aiM, jenkon, Nayomy, Qiyarah, ramziiN  |
|           13 |     3421 | 2024-04-07 | Team Pigeons       | L   | 0.850      | -            | -                | -                | -         |   -10.14 | aiM, jenkon, Nayomy, Qiyarah, ramziiN  |
|           12 |     3435 | 2024-04-07 | Fearless Cheetahs  | W   | 0.849      | 0.262        | 0.006 (0.001)    | 0.149 (0.033)    | -         |    13.21 | aiM, jenkon, Nayomy, Qiyarah, ramziiN  |
|           11 |     3489 | 2024-04-06 | ex-Guild Esports   | W   | 0.842      | 0.262        | 0.005 (0.001)    | 0.166 (0.036)    | -         |    13.95 | aiM, jenkon, Nayomy, Qiyarah, ramziiN  |
|           10 |     3502 | 2024-04-06 | Nemesis            | W   | 0.841      | 0.262        | -                | 0.102 (0.023)    | -         |     6.86 | aiM, jenkon, Nayomy, Qiyarah, ramziiN  |
|            9 |     3637 | 2024-04-03 | Astralis Women     | W   | 0.824      | 0.331        | 0.003 (0.001)    | -                | -         |    10.06 | aiM, jenkon, Nayomy, Qiyarah, ramziiN  |
|            8 |     4228 | 2024-03-20 | ENCE Athena        | W   | 0.731      | 0.331        | 0.004 (0.001)    | 0.215 (0.052)    | -         |    12.33 | aiM, jenkon, Nayomy, Qiyarah, ramziiN  |
|            7 |     4931 | 2024-03-07 | Team Pigeons       | L   | 0.644      | -            | -                | -                | -         |    -7.92 | aiM, jenkon, Nayomy, Qiyarah, ramziiN  |
|            6 |     5245 | 2024-03-03 | BIG EQUIPA         | L   | 0.617      | -            | -                | -                | -         |    -8.73 | aiM, jenkon, Nayomy, Qiyarah, ramziiN  |
|            5 |     5329 | 2024-03-02 | VIOLET             | W   | 0.610      | 0.250        | 0.000 (0.000)    | -                | -         |     5.61 | aiM, jenkon, Nayomy, Qiyarah, ramziiN  |
|            4 |     5696 | 2024-02-24 | more whiskey       | L   | 0.564      | -            | -                | -                | -         |   -12.64 | aiM, jenkon, Nayomy, Qiyarah, ramziiN  |
|            3 |     5722 | 2024-02-24 | Team Spirit Female | L   | 0.562      | -            | -                | -                | -         |    -8.99 | aiM, jenkon, Nayomy, Qiyarah, ramziiN  |
|            2 |     7177 | 2024-01-27 | Questionmark       | L   | 0.377      | -            | -                | -                | -         |    -7.44 | aiM, jenkon, Nayomy, Qiyarah, ramziiN  |
|            1 |     7581 | 2024-01-20 | Nemesis            | L   | 0.330      | -            | -                | -                | -         |    -6.39 | aiM, jenkon, Nayomy, Qiyarah, ramziiN  |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($1,957.71)
- Divide that value by the 5th highest value among all rosters ($300,806.11)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-05-26 |      1.000 | $250.00        | $250.00         |
| 2024-04-27 |      0.983 | $321.08        | $315.62         |
| 2024-04-21 |      0.944 | $1,250.00      | $1,179.69       |
| 2024-04-07 |      0.850 | $250.00        | $212.40         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
