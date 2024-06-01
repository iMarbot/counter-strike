### Roster Details<br />
Team Name: BIG<br />
Roster: JDC, Krimbo, prosus, syrsoN, tabseN<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [19](../standings_global.md)<br />
Regional Rank: [13]( ../standings_europe.md)<br />
Final Rank Value:  1389.6<br />
<br />
Final Rank Value (1389.6) = Starting Rank Value (1431.7) + Head To Head Adjustments (-42.1)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.614[<sup>1</sup>](#table2)
- Bounty Collected: 0.489[<sup>2</sup>](#table1)
- Opponent Network: 0.274[<sup>2</sup>](#table1)
- LAN Wins: 0.649[<sup>2</sup>](#table1)

The average of these factors is 0.507<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1431.7
- 400 + ( ( 0.507 - 0.000 ) / ( 0.786 - 0.000 ) ) * 1600 = 1431.7


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent         | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                              |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           42 |       34 | 2024-05-29 | HEROIC           | L   | 1.000      | -            | -                | -                | -         |    -6.69 | JDC, Krimbo, prosus, syrsoN, tabseN |
|           41 |       72 | 2024-05-29 | Virtus.pro       | W   | 1.000      | 0.624        | 0.271 (0.169)    | 0.331 (0.207)    | 1 (1.000) |    25.09 | JDC, Krimbo, prosus, syrsoN, tabseN |
|           40 |      109 | 2024-05-28 | FlyQuest         | W   | 1.000      | 0.624        | 0.114 (0.071)    | 0.419 (0.261)    | 1 (1.000) |    18.74 | JDC, Krimbo, prosus, syrsoN, tabseN |
|           39 |      156 | 2024-05-27 | Natus Vincere    | L   | 1.000      | -            | -                | -                | -         |    -1.85 | JDC, Krimbo, prosus, syrsoN, tabseN |
|           38 |      707 | 2024-05-20 | MIBR             | L   | 1.000      | -            | -                | -                | -         |    -8.64 | JDC, Krimbo, prosus, syrsoN, tabseN |
|           37 |      729 | 2024-05-19 | Astralis         | L   | 1.000      | -            | -                | -                | -         |    -4.05 | JDC, Krimbo, prosus, syrsoN, tabseN |
|           36 |     1683 | 2024-05-07 | G2 Esports       | L   | 1.000      | -            | -                | -                | -         |    -3.23 | JDC, Krimbo, prosus, syrsoN, tabseN |
|           35 |     1875 | 2024-05-03 | HEROIC           | W   | 1.000      | 0.889        | 0.322 (0.286)    | 0.463 (0.412)    | 1 (1.000) |    25.93 | JDC, Krimbo, prosus, syrsoN, tabseN |
|           34 |     1891 | 2024-05-03 | Pera Esports     | W   | 1.000      | 0.889        | -                | 0.574 (0.510)    | 1 (1.000) |     2.30 | JDC, Krimbo, prosus, syrsoN, tabseN |
|           33 |     1932 | 2024-05-02 | Natus Vincere    | L   | 1.000      | -            | -                | -                | -         |    -1.44 | JDC, Krimbo, prosus, syrsoN, tabseN |
|           32 |     1996 | 2024-05-01 | BOSS             | W   | 1.000      | 0.889        | -                | 0.315 (0.280)    | 1 (1.000) |     2.19 | JDC, Krimbo, prosus, syrsoN, tabseN |
|           31 |     2521 | 2024-04-21 | BLEED Esports    | L   | 0.942      | -            | -                | -                | -         |   -28.31 | JDC, Krimbo, prosus, syrsoN, tabseN |
|           30 |     2792 | 2024-04-18 | LEON Esports     | W   | 0.922      | 0.384        | -                | 0.564 (0.200)    | 0 (0.000) |     0.77 | JDC, Krimbo, prosus, syrsoN, tabseN |
|           29 |     3047 | 2024-04-13 | OG               | L   | 0.889      | -            | -                | -                | -         |   -19.30 | JDC, Krimbo, prosus, syrsoN, tabseN |
|           28 |     3075 | 2024-04-12 | FORZE Esports    | W   | 0.883      | 0.687        | 0.111 (0.068)    | 0.440 (0.267)    | 0 (0.000) |     4.31 | JDC, Krimbo, prosus, syrsoN, tabseN |
|           27 |     3176 | 2024-04-10 | Gods Reign       | W   | 0.870      | 0.687        | 0.086 (0.051)    | 0.461 (0.275)    | -         |     1.85 | JDC, Krimbo, prosus, syrsoN, tabseN |
|           26 |     3253 | 2024-04-09 | BetBoom Team     | L   | 0.863      | -            | -                | -                | -         |   -15.14 | JDC, Krimbo, prosus, syrsoN, tabseN |
|           25 |     3565 | 2024-04-03 | EYEBALLERS       | W   | 0.822      | 0.384        | -                | 0.508 (0.161)    | -         |     1.70 | JDC, Krimbo, prosus, syrsoN, tabseN |
|           24 |     4700 | 2024-03-09 | Team Spirit      | L   | 0.658      | -            | -                | -                | -         |    -1.03 | JDC, Krimbo, prosus, syrsoN, tabseN |
|           23 |     4751 | 2024-03-08 | GamerLegion      | W   | 0.650      | 0.535        | 0.075 (0.026)    | -                | -         |     6.42 | JDC, Krimbo, prosus, syrsoN, tabseN |
|           22 |     5066 | 2024-03-03 | Young Ninjas     | L   | 0.618      | -            | -                | -                | -         |   -18.21 | JDC, Krimbo, prosus, syrsoN, tabseN |
|           21 |     5244 | 2024-03-01 | AMKAL ESPORTS    | W   | 0.602      | 0.500        | 0.146 (0.044)    | 0.565 (0.170)    | -         |     4.30 | JDC, Krimbo, prosus, syrsoN, tabseN |
|           20 |     5338 | 2024-02-28 | BLEED Esports    | L   | 0.589      | -            | -                | -                | -         |   -14.27 | JDC, Krimbo, prosus, syrsoN, tabseN |
|           19 |     6588 | 2024-02-02 | Apeks            | L   | 0.418      | -            | -                | -                | -         |    -9.73 | Krimbo, mantuu, prosus, s1n, tabseN |
|           18 |     6700 | 2024-01-31 | HEROIC           | L   | 0.404      | -            | -                | -                | -         |    -1.92 | Krimbo, mantuu, prosus, s1n, tabseN |
|           17 |     6723 | 2024-01-31 | ENCE             | W   | 0.404      | 1.000        | 0.202 (0.081)    | -                | 1 (0.404) |     6.19 | Krimbo, mantuu, prosus, s1n, tabseN |
|           16 |     6881 | 2024-01-28 | Astralis         | L   | 0.383      | -            | -                | -                | -         |    -2.41 | Krimbo, mantuu, prosus, s1n, tabseN |
|           15 |     6942 | 2024-01-27 | Virtus.pro       | L   | 0.378      | -            | -                | -                | -         |    -2.12 | Krimbo, mantuu, prosus, s1n, tabseN |
|           14 |     7023 | 2024-01-26 | Cloud9           | W   | 0.371      | 0.581        | 0.187 (0.040)    | -                | 1 (0.371) |     7.17 | Krimbo, mantuu, prosus, s1n, tabseN |
|           13 |     7077 | 2024-01-25 | HEROIC           | W   | 0.364      | 0.581        | 0.322 (0.068)    | -                | 1 (0.364) |     9.90 | Krimbo, mantuu, prosus, s1n, tabseN |
|           12 |     7115 | 2024-01-24 | Virtus.pro       | L   | 0.357      | -            | -                | -                | -         |    -1.92 | Krimbo, mantuu, prosus, s1n, tabseN |
|           11 |     7359 | 2024-01-20 | Nexus Gaming     | L   | 0.329      | -            | -                | -                | -         |    -9.74 | Krimbo, mantuu, prosus, s1n, tabseN |
|           10 |     7414 | 2024-01-19 | Fnatic           | L   | 0.323      | -            | -                | -                | -         |    -8.64 | Krimbo, mantuu, prosus, s1n, tabseN |
|            9 |     7468 | 2024-01-18 | BetBoom Team     | L   | 0.317      | -            | -                | -                | -         |    -5.06 | Krimbo, mantuu, prosus, s1n, tabseN |
|            8 |     7481 | 2024-01-18 | Permitta Esports | W   | 0.317      | -            | -                | -                | -         |     0.65 | Krimbo, mantuu, prosus, s1n, tabseN |
|            7 |     8831 | 2023-12-13 | ENCE             | W   | 0.078      | -            | -                | -                | -         |     1.20 | Krimbo, mantuu, prosus, s1n, tabseN |
|            6 |     8845 | 2023-12-13 | Aurora Gaming    | W   | 0.077      | -            | -                | -                | -         |     1.42 | Krimbo, mantuu, prosus, s1n, tabseN |
|            5 |     8888 | 2023-12-12 | ex-Sprout        | W   | 0.070      | -            | -                | -                | -         |     0.02 | Krimbo, mantuu, prosus, s1n, tabseN |
|            4 |     9156 | 2023-12-07 | Aurora Gaming    | W   | 0.038      | -            | -                | -                | -         |     0.70 | Krimbo, mantuu, prosus, s1n, tabseN |
|            3 |     9227 | 2023-12-06 | Aurora Gaming    | W   | 0.030      | -            | -                | -                | -         |     0.56 | Krimbo, mantuu, prosus, s1n, tabseN |
|            2 |     9278 | 2023-12-05 | 9Pandas          | W   | 0.025      | -            | -                | -                | -         |     0.15 | Krimbo, mantuu, prosus, s1n, tabseN |
|            1 |     9362 | 2023-12-03 | ex-Guild Eagles  | W   | 0.011      | -            | -                | -                | -         |     0.02 | Krimbo, mantuu, prosus, s1n, tabseN |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($70,775.65)
- Divide that value by the 5th highest value among all rosters ($300,806.11)
- The final value (0.24) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-05-29 |      1.000 | $6,000.00      | $6,000.00       |
| 2024-05-12 |      1.000 | $17,500.00     | $17,500.00      |
| 2024-04-14 |      0.896 | $35,000.00     | $31,368.75      |
| 2024-03-10 |      0.665 | $7,500.00      | $4,983.85       |
| 2024-02-11 |      0.477 | $4,500.00      | $2,146.25       |
| 2024-01-28 |      0.384 | $10,500.00     | $4,032.29       |
| 2023-12-13 |      0.078 | $12,500.00     | $969.04         |
| 2023-12-07 |      0.038 | $100,000.00    | $3,775.46       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
