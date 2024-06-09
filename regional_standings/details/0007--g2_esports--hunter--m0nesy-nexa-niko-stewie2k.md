### Roster Details<br />
Team Name: G2 Esports<br />
Roster: huNter-, m0NESY, nexa, NiKo, Stewie2K<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [7](../standings_global.md)<br />
Regional Rank: [7]( ../standings_europe.md)<br />
Final Rank Value:  1775.8<br />
<br />
Final Rank Value (1775.8) = Starting Rank Value (1804.4) + Head To Head Adjustments (-28.6)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.752[<sup>1</sup>](#table2)
- Bounty Collected: 0.664[<sup>2</sup>](#table1)
- Opponent Network: 0.348[<sup>2</sup>](#table1)
- LAN Wins: 1.000[<sup>2</sup>](#table1)

The average of these factors is 0.691<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1804.4
- 400 + ( ( 0.691 - 0.000 ) / ( 0.787 - 0.000 ) ) * 1600 = 1804.4


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent           | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           44 |       33 | 2024-05-29 | Team Liquid        | W   | 1.000      | 0.624        | 0.493 (0.308)    | 0.621 (0.388)    | 1 (1.000) |     9.41 | huNter-, m0NESY, nexa, NiKo, Stewie2K |
|           43 |      106 | 2024-05-28 | MOUZ               | W   | 1.000      | 0.624        | 1.000 (0.624)    | 0.434 (0.271)    | 1 (1.000) |    24.14 | huNter-, m0NESY, nexa, NiKo, Stewie2K |
|           42 |      157 | 2024-05-27 | Team Vitality      | L   | 1.000      | -            | -                | -                | -         |   -11.23 | huNter-, m0NESY, nexa, NiKo, Stewie2K |
|           41 |      175 | 2024-05-27 | Team Falcons       | W   | 1.000      | 0.624        | 0.355 (0.221)    | -                | 1 (1.000) |     4.59 | huNter-, m0NESY, nexa, NiKo, Stewie2K |
|           40 |     1570 | 2024-05-09 | MOUZ               | L   | 1.000      | -            | -                | -                | -         |    -7.28 | HooXi, huNter-, m0NESY, nexa, NiKo    |
|           39 |     1656 | 2024-05-08 | 3DMAX              | W   | 1.000      | 0.889        | -                | 0.325 (0.289)    | 1 (1.000) |     0.40 | HooXi, huNter-, m0NESY, nexa, NiKo    |
|           38 |     1702 | 2024-05-07 | BIG                | W   | 1.000      | 0.889        | 0.215 (0.191)    | 0.304 (0.270)    | 1 (1.000) |     3.13 | HooXi, huNter-, m0NESY, nexa, NiKo    |
|           37 |     2133 | 2024-04-28 | M80                | W   | 0.990      | 0.889        | -                | 0.525 (0.462)    | 1 (0.990) |     2.21 | HooXi, huNter-, m0NESY, nexa, NiKo    |
|           36 |     2237 | 2024-04-27 | Team Falcons       | W   | 0.982      | 0.889        | 0.355 (0.310)    | -                | 1 (0.982) |     4.09 | HooXi, huNter-, m0NESY, nexa, NiKo    |
|           35 |     2314 | 2024-04-26 | M80                | L   | 0.975      | -            | -                | -                | -         |   -28.73 | HooXi, huNter-, m0NESY, nexa, NiKo    |
|           34 |     2368 | 2024-04-25 | The MongolZ        | L   | 0.969      | -            | -                | -                | -         |   -23.46 | HooXi, huNter-, m0NESY, nexa, NiKo    |
|           33 |     2434 | 2024-04-24 | TYLOO              | W   | 0.962      | 0.889        | -                | 0.433 (0.370)    | 1 (0.962) |     0.22 | HooXi, huNter-, m0NESY, nexa, NiKo    |
|           32 |     3121 | 2024-04-12 | MOUZ               | L   | 0.887      | -            | -                | -                | -         |    -7.89 | HooXi, huNter-, m0NESY, nexa, NiKo    |
|           31 |     3159 | 2024-04-11 | Virtus.pro         | W   | 0.881      | 0.624        | 0.271 (0.149)    | -                | 1 (0.881) |     9.37 | HooXi, huNter-, m0NESY, nexa, NiKo    |
|           30 |     3272 | 2024-04-10 | HEROIC             | W   | 0.869      | 0.624        | 0.322 (0.175)    | 0.463 (0.251)    | 1 (0.869) |     9.87 | HooXi, huNter-, m0NESY, nexa, NiKo    |
|           29 |     3345 | 2024-04-09 | Lynn Vision Gaming | W   | 0.862      | -            | -                | -                | -         |     0.61 | HooXi, huNter-, m0NESY, nexa, NiKo    |
|           28 |     3392 | 2024-04-08 | Team Liquid        | L   | 0.855      | -            | -                | -                | -         |   -19.62 | HooXi, huNter-, m0NESY, nexa, NiKo    |
|           27 |     3402 | 2024-04-07 | 9z Team            | W   | 0.853      | 0.624        | -                | 0.547 (0.291)    | -         |     1.09 | HooXi, huNter-, m0NESY, nexa, NiKo    |
|           26 |     3758 | 2024-03-30 | Natus Vincere      | L   | 0.798      | -            | -                | -                | -         |   -10.91 | HooXi, huNter-, m0NESY, nexa, NiKo    |
|           25 |     3791 | 2024-03-29 | MOUZ               | W   | 0.791      | 1.000        | 1.000 (0.791)    | 0.434 (0.343)    | -         |    17.90 | HooXi, huNter-, m0NESY, nexa, NiKo    |
|           24 |     4044 | 2024-03-24 | Virtus.pro         | W   | 0.756      | 1.000        | 0.271 (0.205)    | -                | -         |     8.90 | HooXi, huNter-, m0NESY, nexa, NiKo    |
|           23 |     4102 | 2024-03-23 | Gaimin Gladiators  | W   | 0.750      | 1.000        | -                | 0.727 (0.545)    | -         |     1.39 | HooXi, huNter-, m0NESY, nexa, NiKo    |
|           22 |     4142 | 2024-03-22 | Cloud9             | L   | 0.743      | -            | -                | -                | -         |   -19.35 | HooXi, huNter-, m0NESY, nexa, NiKo    |
|           21 |     4164 | 2024-03-21 | Natus Vincere      | L   | 0.738      | -            | -                | -                | -         |   -10.10 | HooXi, huNter-, m0NESY, nexa, NiKo    |
|           20 |     4191 | 2024-03-21 | FURIA Esports      | W   | 0.737      | -            | -                | -                | -         |     2.33 | HooXi, huNter-, m0NESY, nexa, NiKo    |
|           19 |     6238 | 2024-02-15 | FaZe Clan          | W   | 0.503      | -            | -                | -                | -         |    11.66 | HooXi, huNter-, m0NESY, nexa, NiKo    |
|           18 |     6272 | 2024-02-14 | Eternal Fire       | W   | 0.498      | -            | -                | -                | -         |     8.81 | HooXi, huNter-, m0NESY, nexa, NiKo    |
|           17 |     6302 | 2024-02-14 | Into The Breach    | W   | 0.496      | -            | -                | -                | -         |     0.05 | HooXi, huNter-, m0NESY, nexa, NiKo    |
|           16 |     6489 | 2024-02-09 | FaZe Clan          | L   | 0.463      | -            | -                | -                | -         |    -3.68 | HooXi, huNter-, m0NESY, nexa, NiKo    |
|           15 |     6570 | 2024-02-06 | HEROIC             | W   | 0.444      | 1.000        | 0.322 (0.143)    | -                | -         |     6.04 | HooXi, huNter-, m0NESY, nexa, NiKo    |
|           14 |     6583 | 2024-02-06 | Monte              | W   | 0.443      | -            | -                | -                | -         |     0.93 | HooXi, huNter-, m0NESY, nexa, NiKo    |
|           13 |     6631 | 2024-02-05 | ENCE               | L   | 0.437      | -            | -                | -                | -         |   -12.09 | HooXi, huNter-, m0NESY, nexa, NiKo    |
|           12 |     6770 | 2024-02-03 | HEROIC             | W   | 0.423      | -            | -                | -                | -         |     5.58 | HooXi, huNter-, m0NESY, nexa, NiKo    |
|           11 |     7079 | 2024-01-28 | Team Liquid        | W   | 0.384      | -            | -                | -                | -         |     3.85 | HooXi, huNter-, m0NESY, nexa, NiKo    |
|           10 |     7203 | 2024-01-27 | Natus Vincere      | L   | 0.377      | -            | -                | -                | -         |    -4.72 | HooXi, huNter-, m0NESY, nexa, NiKo    |
|            9 |     7273 | 2024-01-26 | Ninjas in Pyjamas  | W   | 0.370      | -            | -                | -                | -         |     0.04 | HooXi, huNter-, m0NESY, nexa, NiKo    |
|            8 |     7428 | 2024-01-23 | Natus Vincere      | L   | 0.349      | -            | -                | -                | -         |    -4.51 | HooXi, huNter-, m0NESY, nexa, NiKo    |
|            7 |     7493 | 2024-01-22 | Ninjas in Pyjamas  | W   | 0.342      | -            | -                | -                | -         |     0.03 | HooXi, huNter-, m0NESY, nexa, NiKo    |
|            6 |     9020 | 2023-12-15 | Natus Vincere      | L   | 0.089      | -            | -                | -                | -         |    -1.18 | HooXi, huNter-, m0NESY, nexa, NiKo    |
|            5 |     9055 | 2023-12-14 | FaZe Clan          | L   | 0.083      | -            | -                | -                | -         |    -0.66 | HooXi, huNter-, m0NESY, nexa, NiKo    |
|            4 |     9111 | 2023-12-13 | MOUZ               | W   | 0.076      | -            | -                | -                | -         |     1.75 | HooXi, huNter-, m0NESY, nexa, NiKo    |
|            3 |     9514 | 2023-12-06 | ex-Guild Eagles    | L   | 0.030      | -            | -                | -                | -         |    -0.92 | HooXi, huNter-, m0NESY, nexa, NiKo    |
|            2 |     9580 | 2023-12-05 | Aurora Gaming      | L   | 0.024      | -            | -                | -                | -         |    -0.64 | HooXi, huNter-, m0NESY, nexa, NiKo    |
|            1 |     9673 | 2023-12-03 | Sprout             | W   | 0.009      | -            | -                | -                | -         |     0.00 | HooXi, huNter-, m0NESY, nexa, NiKo    |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($140,857.64)
- Divide that value by the 5th highest value among all rosters ($300,806.11)
- The final value (0.47) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-05-12 |      1.000 | $32,000.00     | $32,000.00      |
| 2024-04-14 |      0.895 | $20,000.00     | $17,903.24      |
| 2024-03-31 |      0.804 | $80,000.00     | $64,311.11      |
| 2024-02-11 |      0.477 | $40,000.00     | $19,077.78      |
| 2024-01-28 |      0.384 | $12,500.00     | $4,800.35       |
| 2023-12-17 |      0.103 | $25,000.00     | $2,576.39       |
| 2023-12-07 |      0.038 | $5,000.00      | $188.77         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
