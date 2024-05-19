### Roster Details<br />
Team Name: G2 Esports<br />
Roster: HooXi, huNter-, m0NESY, nexa, NiKo<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [6](../standings_global.md)<br />
Regional Rank: [6]( ../standings_europe.md)<br />
Final Rank Value:  1792.6<br />
<br />
Final Rank Value (1792.6) = Starting Rank Value (1899.8) + Head To Head Adjustments (-107.2)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.941[<sup>1</sup>](#table2)
- Bounty Collected: 0.659[<sup>2</sup>](#table1)
- Opponent Network: 0.424[<sup>2</sup>](#table1)
- LAN Wins: 1.000[<sup>2</sup>](#table1)

The average of these factors is 0.756<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1899.8
- 400 + ( ( 0.756 - 0.000 ) / ( 0.806 - 0.000 ) ) * 1600 = 1899.8


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent           | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins     | H2H Adj. | Roster                             |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           36 |      302 | 2024-04-28 | M80                | W   | 1.000      | 0.889        | 0.155 (0.138)    | 0.405 (0.360)    | true (1.000) |     1.93 | HooXi, huNter-, m0NESY, nexa, NiKo |
|           35 |      380 | 2024-04-27 | Team Falcons       | W   | 1.000      | 0.889        | 0.431 (0.383)    | -                | true (1.000) |     2.18 | HooXi, huNter-, m0NESY, nexa, NiKo |
|           34 |      442 | 2024-04-26 | M80                | L   | 1.000      | -            | -                | -                | -            |   -29.78 | HooXi, huNter-, m0NESY, nexa, NiKo |
|           33 |      490 | 2024-04-25 | The MongolZ        | L   | 1.000      | -            | -                | -                | -            |   -25.35 | HooXi, huNter-, m0NESY, nexa, NiKo |
|           32 |      547 | 2024-04-24 | TYLOO              | W   | 1.000      | 0.889        | -                | 0.592 (0.526)    | true (1.000) |     0.33 | HooXi, huNter-, m0NESY, nexa, NiKo |
|           31 |     1126 | 2024-04-13 | MOUZ               | L   | 1.000      | -            | -                | -                | -            |   -14.23 | HooXi, huNter-, m0NESY, nexa, NiKo |
|           30 |     1156 | 2024-04-12 | Virtus.pro         | W   | 1.000      | 0.624        | 0.454 (0.284)    | -                | true (1.000) |     9.15 | HooXi, huNter-, m0NESY, nexa, NiKo |
|           29 |     1244 | 2024-04-10 | HEROIC             | W   | 1.000      | 0.624        | 0.243 (0.152)    | 0.537 (0.335)    | true (1.000) |     7.72 | HooXi, huNter-, m0NESY, nexa, NiKo |
|           28 |     1308 | 2024-04-09 | Lynn Vision Gaming | W   | 1.000      | 0.624        | -                | 0.554 (0.346)    | true (1.000) |     1.01 | HooXi, huNter-, m0NESY, nexa, NiKo |
|           27 |     1349 | 2024-04-08 | Team Liquid        | L   | 1.000      | -            | -                | -                | -            |   -29.20 | HooXi, huNter-, m0NESY, nexa, NiKo |
|           26 |     1359 | 2024-04-07 | 9z Team            | W   | 1.000      | -            | -                | -                | true (1.000) |     0.25 | HooXi, huNter-, m0NESY, nexa, NiKo |
|           25 |     1630 | 2024-03-30 | Natus Vincere      | L   | 0.959      | -            | -                | -                | -            |   -13.02 | HooXi, huNter-, m0NESY, nexa, NiKo |
|           24 |     1658 | 2024-03-29 | MOUZ               | W   | 0.952      | 1.000        | 0.891 (0.849)    | 0.449 (0.428)    | true (0.952) |    15.21 | HooXi, huNter-, m0NESY, nexa, NiKo |
|           23 |     1863 | 2024-03-24 | Virtus.pro         | W   | 0.917      | 1.000        | 0.454 (0.417)    | 0.416 (0.382)    | true (0.917) |     9.03 | HooXi, huNter-, m0NESY, nexa, NiKo |
|           22 |     1913 | 2024-03-23 | Gaimin Gladiators  | W   | 0.911      | 1.000        | 0.194 (0.177)    | 0.989 (0.901)    | true (0.911) |     1.98 | HooXi, huNter-, m0NESY, nexa, NiKo |
|           21 |     1949 | 2024-03-22 | Cloud9             | L   | 0.904      | -            | -                | -                | -            |   -18.78 | HooXi, huNter-, m0NESY, nexa, NiKo |
|           20 |     1965 | 2024-03-21 | Natus Vincere      | L   | 0.899      | -            | -                | -                | -            |   -11.94 | HooXi, huNter-, m0NESY, nexa, NiKo |
|           19 |     1986 | 2024-03-21 | FURIA Esports      | W   | 0.898      | 1.000        | 0.384 (0.345)    | 0.361 (0.324)    | -            |     4.26 | HooXi, huNter-, m0NESY, nexa, NiKo |
|           18 |     3597 | 2024-02-15 | FaZe Clan          | W   | 0.664      | -            | -                | -                | -            |    13.41 | HooXi, huNter-, m0NESY, nexa, NiKo |
|           17 |     3620 | 2024-02-14 | Eternal Fire       | W   | 0.659      | -            | -                | -                | -            |     8.32 | HooXi, huNter-, m0NESY, nexa, NiKo |
|           16 |     3648 | 2024-02-14 | Into The Breach    | W   | 0.657      | -            | -                | -                | -            |     0.08 | HooXi, huNter-, m0NESY, nexa, NiKo |
|           15 |     3795 | 2024-02-09 | FaZe Clan          | L   | 0.624      | -            | -                | -                | -            |    -6.71 | HooXi, huNter-, m0NESY, nexa, NiKo |
|           14 |     3857 | 2024-02-06 | HEROIC             | W   | 0.605      | 1.000        | 0.243 (0.147)    | 0.537 (0.325)    | -            |     5.39 | HooXi, huNter-, m0NESY, nexa, NiKo |
|           13 |     3867 | 2024-02-06 | Monte              | W   | 0.604      | -            | -                | -                | -            |     1.23 | HooXi, huNter-, m0NESY, nexa, NiKo |
|           12 |     3903 | 2024-02-05 | ENCE               | L   | 0.598      | -            | -                | -                | -            |   -16.10 | HooXi, huNter-, m0NESY, nexa, NiKo |
|           11 |     3998 | 2024-02-03 | HEROIC             | W   | 0.584      | 1.000        | 0.243 (0.142)    | 0.537 (0.314)    | -            |     4.67 | HooXi, huNter-, m0NESY, nexa, NiKo |
|           10 |     4212 | 2024-01-28 | Team Liquid        | W   | 0.545      | -            | -                | -                | -            |     1.16 | HooXi, huNter-, m0NESY, nexa, NiKo |
|            9 |     4282 | 2024-01-27 | Natus Vincere      | L   | 0.538      | -            | -                | -                | -            |    -6.44 | HooXi, huNter-, m0NESY, nexa, NiKo |
|            8 |     4328 | 2024-01-26 | Ninjas in Pyjamas  | W   | 0.531      | -            | -                | -                | -            |     0.04 | HooXi, huNter-, m0NESY, nexa, NiKo |
|            7 |     4438 | 2024-01-23 | Natus Vincere      | L   | 0.510      | -            | -                | -                | -            |    -6.39 | HooXi, huNter-, m0NESY, nexa, NiKo |
|            6 |     4490 | 2024-01-22 | Ninjas in Pyjamas  | W   | 0.503      | -            | -                | -                | -            |     0.04 | HooXi, huNter-, m0NESY, nexa, NiKo |
|            5 |     5595 | 2023-12-15 | Natus Vincere      | L   | 0.250      | -            | -                | -                | -            |    -3.23 | HooXi, huNter-, m0NESY, nexa, NiKo |
|            4 |     5616 | 2023-12-14 | FaZe Clan          | L   | 0.244      | -            | -                | -                | -            |    -2.69 | HooXi, huNter-, m0NESY, nexa, NiKo |
|            3 |     5941 | 2023-12-06 | Guild Eagles       | L   | 0.191      | -            | -                | -                | -            |    -5.96 | HooXi, huNter-, m0NESY, nexa, NiKo |
|            2 |     5989 | 2023-12-05 | Aurora Gaming      | L   | 0.185      | -            | -                | -                | -            |    -4.80 | HooXi, huNter-, m0NESY, nexa, NiKo |
|            1 |     6222 | 2023-11-30 | Fluxo              | W   | 0.150      | -            | -                | -                | -            |     0.04 | HooXi, huNter-, m0NESY, nexa, NiKo |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($137,149.65)
- Divide that value by the 5th highest value among all rosters ($158,437.64)
- The final value (0.87) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-04-14 |      1.000 | $20,000.00     | $20,000.00      |
| 2024-03-31 |      0.965 | $80,000.00     | $77,218.52      |
| 2024-02-11 |      0.638 | $40,000.00     | $25,520.37      |
| 2024-01-28 |      0.545 | $12,500.00     | $6,813.66       |
| 2023-12-17 |      0.264 | $25,000.00     | $6,603.01       |
| 2023-12-07 |      0.199 | $5,000.00      | $994.10         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
