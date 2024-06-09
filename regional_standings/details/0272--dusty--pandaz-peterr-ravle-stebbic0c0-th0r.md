### Roster Details<br />
Team Name: DUSTY<br />
Roster: PANDAZ, peterr, RavlE, StebbiC0C0, TH0R<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [272](../standings_global.md)<br />
Regional Rank: [175]( ../standings_europe.md)<br />
Final Rank Value:  666.9<br />
<br />
Final Rank Value (666.9) = Starting Rank Value (736.9) + Head To Head Adjustments (-70.0)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.314[<sup>1</sup>](#table2)
- Bounty Collected: 0.185[<sup>2</sup>](#table1)
- Opponent Network: 0.006[<sup>2</sup>](#table1)
- LAN Wins: 0.158[<sup>2</sup>](#table1)

The average of these factors is 0.166<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 736.9
- 400 + ( ( 0.166 - 0.000 ) / ( 0.787 - 0.000 ) ) * 1600 = 736.9


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
|           26 |     1422 | 2024-05-11 | Þór                     | W   | 1.000      | 0.143        | 0.000 (0.000)    | 0.034 (0.005)    | 0 (0.000) |     5.91 | PANDAZ, peterr, RavlE, StebbiC0C0, TH0R    |
|           25 |     2543 | 2024-04-21 | KUUSAMO.gg              | L   | 0.944      | -            | -                | -                | -         |   -11.20 | EddezeNNN, PANDAZ, RavlE, StebbiC0C0, TH0R |
|           24 |     2735 | 2024-04-19 | Heimo Esports           | L   | 0.931      | -            | -                | -                | -         |   -11.74 | EddezeNNN, PANDAZ, RavlE, StebbiC0C0, TH0R |
|           23 |     2743 | 2024-04-19 | RoundsGG                | W   | 0.930      | 0.143        | 0.000 (0.000)    | 0.251 (0.033)    | 0 (0.000) |    12.07 | EddezeNNN, PANDAZ, RavlE, StebbiC0C0, TH0R |
|           22 |     2895 | 2024-04-17 | SINNERS Academy         | L   | 0.917      | -            | -                | -                | -         |   -16.13 | EddezeNNN, PANDAZ, RavlE, StebbiC0C0, TH0R |
|           21 |     3970 | 2024-03-26 | Team Sampi              | L   | 0.771      | -            | -                | -                | -         |    -4.16 | EddezeNNN, PANDAZ, RavlE, StebbiC0C0, TH0R |
|           20 |     4076 | 2024-03-23 | SAGA Esports            | W   | 0.751      | 0.143        | 0.003 (0.000)    | 0.072 (0.008)    | 1 (0.751) |     8.60 | EddezeNNN, PANDAZ, RavlE, StebbiC0C0, TH0R |
|           19 |     4118 | 2024-03-22 | AURORA                  | W   | 0.745      | 0.143        | 0.000 (0.000)    | 0.020 (0.002)    | 1 (0.745) |     4.29 | EddezeNNN, PANDAZ, RavlE, StebbiC0C0, TH0R |
|           18 |     4352 | 2024-03-17 | Breiðablik              | W   | 0.711      | 0.143        | 0.000 (0.000)    | 0.059 (0.006)    | 0 (0.000) |     6.36 | EddezeNNN, PANDAZ, RavlE, StebbiC0C0, TH0R |
|           17 |     4768 | 2024-03-10 | Phantom Troupe          | L   | 0.665      | -            | -                | -                | -         |   -14.52 | EddezeNNN, PANDAZ, RavlE, StebbiC0C0, TH0R |
|           16 |     5090 | 2024-03-05 | TopTab Club             | L   | 0.631      | -            | -                | -                | -         |   -14.57 | EddezeNNN, PANDAZ, RavlE, StebbiC0C0, TH0R |
|           15 |     5302 | 2024-03-02 | SINNERS Esports         | L   | 0.611      | -            | -                | -                | -         |    -3.13 | EddezeNNN, PANDAZ, RavlE, StebbiC0C0, TH0R |
|           14 |     6095 | 2024-02-17 | Þór                     | L   | 0.518      | -            | -                | -                | -         |   -12.05 | EddezeNNN, PANDAZ, RavlE, StebbiC0C0, TH0R |
|           13 |     6567 | 2024-02-06 | Þór                     | W   | 0.445      | 0.143        | 0.000 (0.000)    | 0.034 (0.002)    | 0 (0.000) |     2.08 | EddezeNNN, PANDAZ, RavlE, StebbiC0C0, TH0R |
|           12 |     6680 | 2024-02-04 | Metizport               | L   | 0.429      | -            | -                | -                | -         |    -2.32 | EddezeNNN, PANDAZ, RavlE, StebbiC0C0, TH0R |
|           11 |     6858 | 2024-02-01 | Ármann                  | L   | 0.412      | -            | -                | -                | -         |   -10.12 | EddezeNNN, PANDAZ, RavlE, StebbiC0C0, TH0R |
|           10 |     7013 | 2024-01-29 | GODSENT                 | L   | 0.392      | -            | -                | -                | -         |    -7.40 | EddezeNNN, PANDAZ, RavlE, StebbiC0C0, TH0R |
|            9 |     7137 | 2024-01-27 | ex-Raptors Esports Club | L   | 0.379      | -            | -                | -                | -         |    -7.62 | EddezeNNN, PANDAZ, RavlE, StebbiC0C0, TH0R |
|            8 |     7140 | 2024-01-27 | PUGSTAR5                | W   | 0.378      | 0.143        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     1.53 | EddezeNNN, PANDAZ, RavlE, StebbiC0C0, TH0R |
|            7 |     7578 | 2024-01-20 | FH                      | W   | 0.331      | 0.143        | 0.000 (0.000)    | 0.021 (0.001)    | 0 (0.000) |     1.35 | EddezeNNN, PANDAZ, RavlE, StebbiC0C0, TH0R |
|            6 |     7701 | 2024-01-18 | ÍA Akranes              | W   | 0.318      | -            | -                | -                | 0 (0.000) |     1.28 | EddezeNNN, PANDAZ, RavlE, StebbiC0C0, TH0R |
|            5 |     8177 | 2024-01-11 | SAGA Esports            | W   | 0.271      | 0.143        | 0.003 (0.000)    | 0.072 (0.003)    | 0 (0.000) |     2.54 | EddezeNNN, PANDAZ, RavlE, StebbiC0C0, TH0R |
|            4 |     8833 | 2023-12-16 | 1win Academy            | L   | 0.098      | -            | -                | -                | -         |    -2.07 | EddezeNNN, PANDAZ, RavlE, StebbiC0C0, TH0R |
|            3 |     9045 | 2023-12-14 | CYBER.MD                | W   | 0.085      | 0.284        | 0.000 (0.000)    | 0.002 (0.000)    | -         |     0.55 | EddezeNNN, PANDAZ, RavlE, StebbiC0C0, TH0R |
|            2 |     9084 | 2023-12-13 | Enosis                  | W   | 0.078      | -            | -                | -                | -         |     0.32 | EddezeNNN, PANDAZ, RavlE, StebbiC0C0, TH0R |
|            1 |     9410 | 2023-12-07 | ÍBV Esports             | W   | 0.038      | -            | -                | -                | -         |     0.16 | EddezeNNN, PANDAZ, RavlE, StebbiC0C0, TH0R |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($1,945.20)
- Divide that value by the 5th highest value among all rosters ($300,806.11)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-03-23 |      0.751 | $2,540.09      | $1,908.60       |
| 2023-12-17 |      0.105 | $350.00        | $36.60          |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
