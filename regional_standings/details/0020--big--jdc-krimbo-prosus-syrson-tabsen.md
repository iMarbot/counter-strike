### Roster Details<br />
Team Name: BIG<br />
Roster: JDC, Krimbo, prosus, syrsoN, tabseN<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [20](../standings_global.md)<br />
Regional Rank: [14]( ../standings_europe.md)<br />
Final Rank Value:  1383.1<br />
<br />
Final Rank Value (1383.1) = Starting Rank Value (1420.4) + Head To Head Adjustments (-37.3)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.600[<sup>1</sup>](#table2)
- Bounty Collected: 0.489[<sup>2</sup>](#table1)
- Opponent Network: 0.270[<sup>2</sup>](#table1)
- LAN Wins: 0.649[<sup>2</sup>](#table1)

The average of these factors is 0.502<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1420.4
- 400 + ( ( 0.502 - 0.000 ) / ( 0.787 - 0.000 ) ) * 1600 = 1420.4


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
|           42 |       34 | 2024-05-29 | HEROIC           | L   | 1.000      | -            | -                | -                | -         |    -6.51 | JDC, Krimbo, prosus, syrsoN, tabseN |
|           41 |       77 | 2024-05-29 | Virtus.pro       | W   | 1.000      | 0.624        | 0.271 (0.169)    | 0.331 (0.207)    | 1 (1.000) |    25.27 | JDC, Krimbo, prosus, syrsoN, tabseN |
|           40 |      116 | 2024-05-28 | FlyQuest         | W   | 1.000      | 0.624        | 0.114 (0.071)    | 0.466 (0.291)    | 1 (1.000) |    19.25 | JDC, Krimbo, prosus, syrsoN, tabseN |
|           39 |      163 | 2024-05-27 | Natus Vincere    | L   | 1.000      | -            | -                | -                | -         |    -1.78 | JDC, Krimbo, prosus, syrsoN, tabseN |
|           38 |      719 | 2024-05-20 | MIBR             | L   | 1.000      | -            | -                | -                | -         |    -8.47 | JDC, Krimbo, prosus, syrsoN, tabseN |
|           37 |      741 | 2024-05-19 | Astralis         | L   | 1.000      | -            | -                | -                | -         |    -3.97 | JDC, Krimbo, prosus, syrsoN, tabseN |
|           36 |     1702 | 2024-05-07 | G2 Esports       | L   | 1.000      | -            | -                | -                | -         |    -3.13 | JDC, Krimbo, prosus, syrsoN, tabseN |
|           35 |     1899 | 2024-05-03 | HEROIC           | W   | 1.000      | 0.889        | 0.322 (0.286)    | 0.463 (0.412)    | 1 (1.000) |    26.14 | JDC, Krimbo, prosus, syrsoN, tabseN |
|           34 |     1916 | 2024-05-03 | Pera Esports     | W   | 1.000      | 0.889        | -                | 0.542 (0.482)    | 1 (1.000) |     2.28 | JDC, Krimbo, prosus, syrsoN, tabseN |
|           33 |     1959 | 2024-05-02 | Natus Vincere    | L   | 1.000      | -            | -                | -                | -         |    -1.39 | JDC, Krimbo, prosus, syrsoN, tabseN |
|           32 |     2026 | 2024-05-01 | BOSS             | W   | 1.000      | 0.889        | -                | 0.315 (0.280)    | 1 (1.000) |     2.28 | JDC, Krimbo, prosus, syrsoN, tabseN |
|           31 |     2574 | 2024-04-21 | BLEED Esports    | L   | 0.942      | -            | -                | -                | -         |   -28.27 | JDC, Krimbo, prosus, syrsoN, tabseN |
|           30 |     2848 | 2024-04-18 | LEON Esports     | W   | 0.922      | 0.384        | -                | 0.564 (0.200)    | 0 (0.000) |     0.81 | JDC, Krimbo, prosus, syrsoN, tabseN |
|           29 |     3113 | 2024-04-13 | OG               | L   | 0.889      | -            | -                | -                | -         |   -19.08 | JDC, Krimbo, prosus, syrsoN, tabseN |
|           28 |     3141 | 2024-04-12 | FORZE Esports    | W   | 0.883      | 0.687        | 0.101 (0.062)    | 0.372 (0.225)    | 0 (0.000) |     4.58 | JDC, Krimbo, prosus, syrsoN, tabseN |
|           27 |     3249 | 2024-04-10 | Gods Reign       | W   | 0.870      | 0.687        | 0.086 (0.051)    | 0.461 (0.275)    | -         |     1.76 | JDC, Krimbo, prosus, syrsoN, tabseN |
|           26 |     3332 | 2024-04-09 | BetBoom Team     | L   | 0.863      | -            | -                | -                | -         |   -14.73 | JDC, Krimbo, prosus, syrsoN, tabseN |
|           25 |     3652 | 2024-04-03 | EYEBALLERS       | W   | 0.822      | 0.384        | -                | 0.508 (0.161)    | -         |     1.79 | JDC, Krimbo, prosus, syrsoN, tabseN |
|           24 |     4825 | 2024-03-09 | Team Spirit      | L   | 0.658      | -            | -                | -                | -         |    -1.00 | JDC, Krimbo, prosus, syrsoN, tabseN |
|           23 |     4878 | 2024-03-08 | GamerLegion      | W   | 0.650      | 0.535        | 0.075 (0.026)    | -                | -         |     6.64 | JDC, Krimbo, prosus, syrsoN, tabseN |
|           22 |     5212 | 2024-03-03 | Young Ninjas     | L   | 0.618      | -            | -                | -                | -         |   -18.16 | JDC, Krimbo, prosus, syrsoN, tabseN |
|           21 |     5393 | 2024-03-01 | AMKAL ESPORTS    | W   | 0.602      | 0.500        | 0.146 (0.044)    | 0.565 (0.170)    | -         |     4.54 | JDC, Krimbo, prosus, syrsoN, tabseN |
|           20 |     5490 | 2024-02-28 | BLEED Esports    | L   | 0.589      | -            | -                | -                | -         |   -14.00 | JDC, Krimbo, prosus, syrsoN, tabseN |
|           19 |     6791 | 2024-02-02 | Apeks            | L   | 0.418      | -            | -                | -                | -         |    -9.63 | Krimbo, mantuu, prosus, s1n, tabseN |
|           18 |     6909 | 2024-01-31 | HEROIC           | L   | 0.404      | -            | -                | -                | -         |    -1.81 | Krimbo, mantuu, prosus, s1n, tabseN |
|           17 |     6935 | 2024-01-31 | ENCE             | W   | 0.404      | 1.000        | 0.202 (0.081)    | -                | 1 (0.404) |     6.42 | Krimbo, mantuu, prosus, s1n, tabseN |
|           16 |     7099 | 2024-01-28 | Astralis         | L   | 0.383      | -            | -                | -                | -         |    -2.35 | Krimbo, mantuu, prosus, s1n, tabseN |
|           15 |     7161 | 2024-01-27 | Virtus.pro       | L   | 0.378      | -            | -                | -                | -         |    -2.02 | Krimbo, mantuu, prosus, s1n, tabseN |
|           14 |     7245 | 2024-01-26 | Cloud9           | W   | 0.371      | 0.581        | 0.187 (0.040)    | -                | 1 (0.371) |     7.33 | Krimbo, mantuu, prosus, s1n, tabseN |
|           13 |     7303 | 2024-01-25 | HEROIC           | W   | 0.364      | 0.581        | 0.322 (0.068)    | -                | 1 (0.364) |     9.99 | Krimbo, mantuu, prosus, s1n, tabseN |
|           12 |     7348 | 2024-01-24 | Virtus.pro       | L   | 0.357      | -            | -                | -                | -         |    -1.82 | Krimbo, mantuu, prosus, s1n, tabseN |
|           11 |     7603 | 2024-01-20 | Nexus Gaming     | L   | 0.329      | -            | -                | -                | -         |    -9.76 | Krimbo, mantuu, prosus, s1n, tabseN |
|           10 |     7660 | 2024-01-19 | Fnatic           | L   | 0.323      | -            | -                | -                | -         |    -8.55 | Krimbo, mantuu, prosus, s1n, tabseN |
|            9 |     7716 | 2024-01-18 | BetBoom Team     | L   | 0.317      | -            | -                | -                | -         |    -4.85 | Krimbo, mantuu, prosus, s1n, tabseN |
|            8 |     7730 | 2024-01-18 | Permitta Esports | W   | 0.317      | -            | -                | -                | -         |     0.71 | Krimbo, mantuu, prosus, s1n, tabseN |
|            7 |     9095 | 2023-12-13 | ENCE             | W   | 0.078      | -            | -                | -                | -         |     1.25 | Krimbo, mantuu, prosus, s1n, tabseN |
|            6 |     9109 | 2023-12-13 | Aurora Gaming    | W   | 0.077      | -            | -                | -                | -         |     1.42 | Krimbo, mantuu, prosus, s1n, tabseN |
|            5 |     9152 | 2023-12-12 | ex-Sprout        | W   | 0.070      | -            | -                | -                | -         |     0.03 | Krimbo, mantuu, prosus, s1n, tabseN |
|            4 |     9429 | 2023-12-07 | Aurora Gaming    | W   | 0.038      | -            | -                | -                | -         |     0.70 | Krimbo, mantuu, prosus, s1n, tabseN |
|            3 |     9508 | 2023-12-06 | Aurora Gaming    | W   | 0.030      | -            | -                | -                | -         |     0.57 | Krimbo, mantuu, prosus, s1n, tabseN |
|            2 |     9560 | 2023-12-05 | 9Pandas          | W   | 0.025      | -            | -                | -                | -         |     0.16 | Krimbo, mantuu, prosus, s1n, tabseN |
|            1 |     9644 | 2023-12-03 | ex-Guild Eagles  | W   | 0.011      | -            | -                | -                | -         |     0.02 | Krimbo, mantuu, prosus, s1n, tabseN |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($64,775.65)
- Divide that value by the 5th highest value among all rosters ($300,806.11)
- The final value (0.22) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
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
