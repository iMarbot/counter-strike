### Roster Details<br />
Team Name: BIG<br />
Roster: JDC, Krimbo, prosus, syrsoN, tabseN<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [22](../standings_global.md)<br />
Regional Rank: [15]( ../standings_europe.md)<br />
Final Rank Value:  1406.5<br />
<br />
Final Rank Value (1406.5) = Starting Rank Value (1431.4) + Head To Head Adjustments (-24.8)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.753[<sup>1</sup>](#table2)
- Bounty Collected: 0.533[<sup>2</sup>](#table1)
- Opponent Network: 0.278[<sup>2</sup>](#table1)
- LAN Wins: 0.515[<sup>2</sup>](#table1)

The average of these factors is 0.520<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1431.4
- 400 + ( ( 0.520 - 0.000 ) / ( 0.806 - 0.000 ) ) * 1600 = 1431.4


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
|           43 |      102 | 2024-05-03 | HEROIC           | W   | 1.000      | 0.889        | 0.243 (0.216)    | 0.537 (0.478)    | 1 (1.000) |    24.47 | JDC, Krimbo, prosus, syrsoN, tabseN |
|           42 |      119 | 2024-05-03 | Pera Esports     | W   | 1.000      | 0.889        | -                | 0.324 (0.288)    | 1 (1.000) |     2.03 | JDC, Krimbo, prosus, syrsoN, tabseN |
|           41 |      157 | 2024-05-02 | Natus Vincere    | L   | 1.000      | -            | -                | -                | -         |    -1.25 | JDC, Krimbo, prosus, syrsoN, tabseN |
|           40 |      214 | 2024-05-01 | BOSS             | W   | 1.000      | 0.889        | -                | 0.293 (0.260)    | 1 (1.000) |     1.84 | JDC, Krimbo, prosus, syrsoN, tabseN |
|           39 |      663 | 2024-04-21 | BLEED Esports    | L   | 1.000      | -            | -                | -                | -         |   -25.38 | JDC, Krimbo, prosus, syrsoN, tabseN |
|           38 |      904 | 2024-04-18 | LEON Esports     | W   | 1.000      | -            | -                | -                | 0 (0.000) |     0.59 | JDC, Krimbo, prosus, syrsoN, tabseN |
|           37 |     1118 | 2024-04-13 | OG               | L   | 1.000      | -            | -                | -                | -         |   -18.04 | JDC, Krimbo, prosus, syrsoN, tabseN |
|           36 |     1138 | 2024-04-12 | FORZE Esports    | W   | 1.000      | 0.687        | 0.210 (0.144)    | 0.574 (0.394)    | 0 (0.000) |     5.54 | JDC, Krimbo, prosus, syrsoN, tabseN |
|           35 |     1223 | 2024-04-10 | Gods Reign       | W   | 1.000      | 0.687        | 0.174 (0.120)    | 0.479 (0.329)    | 0 (0.000) |     1.57 | JDC, Krimbo, prosus, syrsoN, tabseN |
|           34 |     1295 | 2024-04-09 | BetBoom Team     | L   | 1.000      | -            | -                | -                | -         |   -16.60 | JDC, Krimbo, prosus, syrsoN, tabseN |
|           33 |     1547 | 2024-04-03 | EYEBALLERS       | W   | 0.984      | 0.384        | -                | 0.533 (0.202)    | 0 (0.000) |     1.94 | JDC, Krimbo, prosus, syrsoN, tabseN |
|           32 |     2486 | 2024-03-09 | Team Spirit      | L   | 0.819      | -            | -                | -                | -         |    -2.06 | JDC, Krimbo, prosus, syrsoN, tabseN |
|           31 |     2530 | 2024-03-08 | GamerLegion      | W   | 0.811      | 0.535        | 0.194 (0.084)    | 0.419 (0.182)    | -         |    17.03 | JDC, Krimbo, prosus, syrsoN, tabseN |
|           30 |     2784 | 2024-03-03 | Young Ninjas     | L   | 0.779      | -            | -                | -                | -         |   -23.04 | JDC, Krimbo, prosus, syrsoN, tabseN |
|           29 |     2926 | 2024-03-01 | AMKAL ESPORTS    | W   | 0.763      | 0.500        | 0.209 (0.080)    | 0.756 (0.288)    | -         |     5.11 | JDC, Krimbo, prosus, syrsoN, tabseN |
|           28 |     4012 | 2024-02-02 | Apeks            | L   | 0.579      | -            | -                | -                | -         |    -9.86 | Krimbo, mantuu, prosus, s1n, tabseN |
|           27 |     4099 | 2024-01-31 | HEROIC           | L   | 0.566      | -            | -                | -                | -         |    -3.79 | Krimbo, mantuu, prosus, s1n, tabseN |
|           26 |     4114 | 2024-01-31 | ENCE             | W   | 0.565      | 1.000        | 0.377 (0.213)    | 0.352 (0.199)    | 1 (0.565) |    10.91 | Krimbo, mantuu, prosus, s1n, tabseN |
|           25 |     4224 | 2024-01-28 | Astralis         | L   | 0.544      | -            | -                | -                | -         |    -6.10 | Krimbo, mantuu, prosus, s1n, tabseN |
|           24 |     4258 | 2024-01-27 | Virtus.pro       | L   | 0.539      | -            | -                | -                | -         |    -2.91 | Krimbo, mantuu, prosus, s1n, tabseN |
|           23 |     4307 | 2024-01-26 | Cloud9           | W   | 0.532      | 0.581        | 0.487 (0.151)    | -                | 1 (0.532) |    14.66 | Krimbo, mantuu, prosus, s1n, tabseN |
|           22 |     4351 | 2024-01-25 | HEROIC           | W   | 0.525      | 0.581        | -                | 0.537 (0.164)    | 1 (0.525) |    13.45 | Krimbo, mantuu, prosus, s1n, tabseN |
|           21 |     4381 | 2024-01-24 | Virtus.pro       | L   | 0.518      | -            | -                | -                | -         |    -2.64 | Krimbo, mantuu, prosus, s1n, tabseN |
|           20 |     4563 | 2024-01-20 | Nexus Gaming     | L   | 0.490      | -            | -                | -                | -         |   -14.52 | Krimbo, mantuu, prosus, s1n, tabseN |
|           19 |     4606 | 2024-01-19 | Fnatic           | L   | 0.484      | -            | -                | -                | -         |   -11.89 | Krimbo, mantuu, prosus, s1n, tabseN |
|           18 |     4654 | 2024-01-18 | BetBoom Team     | L   | 0.478      | -            | -                | -                | -         |    -6.79 | Krimbo, mantuu, prosus, s1n, tabseN |
|           17 |     4666 | 2024-01-18 | Permitta Esports | W   | 0.478      | -            | -                | -                | -         |     1.13 | Krimbo, mantuu, prosus, s1n, tabseN |
|           16 |     5644 | 2023-12-13 | ENCE             | W   | 0.239      | -            | -                | -                | -         |     4.75 | Krimbo, mantuu, prosus, s1n, tabseN |
|           15 |     5651 | 2023-12-13 | Aurora Gaming    | W   | 0.238      | 0.384        | 1.000 (0.091)    | -                | -         |     5.47 | Krimbo, mantuu, prosus, s1n, tabseN |
|           14 |     5677 | 2023-12-12 | Sprout           | W   | 0.231      | -            | -                | -                | -         |     0.11 | Krimbo, mantuu, prosus, s1n, tabseN |
|           13 |     5878 | 2023-12-07 | Aurora Gaming    | W   | 0.199      | 0.589        | 1.000 (0.117)    | -                | -         |     4.64 | Krimbo, mantuu, prosus, s1n, tabseN |
|           12 |     5935 | 2023-12-06 | Aurora Gaming    | W   | 0.191      | 0.589        | 1.000 (0.113)    | -                | -         |     4.52 | Krimbo, mantuu, prosus, s1n, tabseN |
|           11 |     5973 | 2023-12-05 | 9Pandas          | W   | 0.186      | -            | -                | -                | -         |     0.93 | Krimbo, mantuu, prosus, s1n, tabseN |
|           10 |     6036 | 2023-12-03 | Guild Eagles     | W   | 0.172      | -            | -                | -                | -         |     0.53 | Krimbo, mantuu, prosus, s1n, tabseN |
|            9 |     6207 | 2023-11-30 | Zero Tenacity    | W   | 0.151      | -            | -                | -                | -         |     0.33 | Krimbo, mantuu, prosus, s1n, tabseN |
|            8 |     6651 | 2023-11-20 | MIBR             | L   | 0.084      | -            | -                | -                | -         |    -0.58 | Krimbo, mantuu, prosus, s1n, tabseN |
|            7 |     6699 | 2023-11-18 | Into The Breach  | W   | 0.072      | -            | -                | -                | -         |     0.07 | Krimbo, mantuu, prosus, s1n, tabseN |
|            6 |     6747 | 2023-11-18 | SINNERS Esports  | W   | 0.070      | -            | -                | -                | -         |     0.17 | Krimbo, mantuu, prosus, s1n, tabseN |
|            5 |     6773 | 2023-11-17 | Preasy Esport    | L   | 0.065      | -            | -                | -                | -         |    -1.91 | Krimbo, mantuu, prosus, s1n, tabseN |
|            4 |     6900 | 2023-11-15 | 00 Nation        | W   | 0.050      | -            | -                | -                | -         |     0.01 | Krimbo, mantuu, prosus, s1n, tabseN |
|            3 |     6938 | 2023-11-14 | Eternal Fire     | W   | 0.044      | -            | -                | -                | -         |     1.22 | Krimbo, mantuu, prosus, s1n, tabseN |
|            2 |     6954 | 2023-11-13 | TSM              | W   | 0.039      | -            | -                | -                | -         |     0.02 | Krimbo, mantuu, prosus, s1n, tabseN |
|            1 |     7006 | 2023-11-12 | Apeks            | L   | 0.031      | -            | -                | -                | -         |    -0.53 | Krimbo, mantuu, prosus, s1n, tabseN |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($74,458.52)
- Divide that value by the 5th highest value among all rosters ($158,437.64)
- The final value (0.47) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-04-14 |      1.000 | $35,000.00     | $35,000.00      |
| 2024-03-10 |      0.826 | $7,500.00      | $6,191.84       |
| 2024-02-11 |      0.638 | $4,500.00      | $2,871.04       |
| 2024-01-28 |      0.545 | $10,500.00     | $5,723.47       |
| 2023-12-13 |      0.239 | $12,500.00     | $2,982.35       |
| 2023-12-07 |      0.199 | $100,000.00    | $19,881.94      |
| 2023-11-18 |      0.072 | $25,000.00     | $1,807.87       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
