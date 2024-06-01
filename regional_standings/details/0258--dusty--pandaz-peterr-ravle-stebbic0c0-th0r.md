### Roster Details<br />
Team Name: DUSTY<br />
Roster: PANDAZ, peterr, RavlE, StebbiC0C0, TH0R<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [258](../standings_global.md)<br />
Regional Rank: [165]( ../standings_europe.md)<br />
Final Rank Value:  677.2<br />
<br />
Final Rank Value (677.2) = Starting Rank Value (737.1) + Head To Head Adjustments (-59.9)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.314[<sup>1</sup>](#table2)
- Bounty Collected: 0.185[<sup>2</sup>](#table1)
- Opponent Network: 0.005[<sup>2</sup>](#table1)
- LAN Wins: 0.158[<sup>2</sup>](#table1)

The average of these factors is 0.166<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 737.1
- 400 + ( ( 0.166 - 0.000 ) / ( 0.786 - 0.000 ) ) * 1600 = 737.1


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
|           25 |     1409 | 2024-05-11 | Þór                     | W   | 1.000      | 0.143        | 0.000 (0.000)    | 0.034 (0.005)    | 0 (0.000) |     5.63 | PANDAZ, peterr, RavlE, StebbiC0C0, TH0R    |
|           24 |     2490 | 2024-04-21 | KUUSAMO.gg              | L   | 0.944      | -            | -                | -                | -         |   -11.63 | EddezeNNN, PANDAZ, RavlE, StebbiC0C0, TH0R |
|           23 |     2681 | 2024-04-19 | Heimo Esports           | L   | 0.931      | -            | -                | -                | -         |   -12.22 | EddezeNNN, PANDAZ, RavlE, StebbiC0C0, TH0R |
|           22 |     2687 | 2024-04-19 | RoundsGG                | W   | 0.930      | 0.143        | 0.000 (0.000)    | 0.202 (0.027)    | 0 (0.000) |    10.85 | EddezeNNN, PANDAZ, RavlE, StebbiC0C0, TH0R |
|           21 |     2838 | 2024-04-17 | SINNERS Academy         | L   | 0.917      | -            | -                | -                | -         |   -16.31 | EddezeNNN, PANDAZ, RavlE, StebbiC0C0, TH0R |
|           20 |     3873 | 2024-03-26 | Team Sampi              | L   | 0.771      | -            | -                | -                | -         |    -4.50 | EddezeNNN, PANDAZ, RavlE, StebbiC0C0, TH0R |
|           19 |     3978 | 2024-03-23 | SAGA Esports            | W   | 0.751      | 0.143        | 0.003 (0.000)    | 0.072 (0.008)    | 1 (0.751) |     8.20 | EddezeNNN, PANDAZ, RavlE, StebbiC0C0, TH0R |
|           18 |     4020 | 2024-03-22 | AURORA                  | W   | 0.745      | 0.143        | 0.000 (0.000)    | 0.020 (0.002)    | 1 (0.745) |     4.03 | EddezeNNN, PANDAZ, RavlE, StebbiC0C0, TH0R |
|           17 |     4247 | 2024-03-17 | Breiðablik              | W   | 0.711      | 0.143        | 0.000 (0.000)    | 0.059 (0.006)    | 0 (0.000) |     6.01 | EddezeNNN, PANDAZ, RavlE, StebbiC0C0, TH0R |
|           16 |     4950 | 2024-03-05 | TopTab Club             | L   | 0.631      | -            | -                | -                | -         |   -14.58 | EddezeNNN, PANDAZ, RavlE, StebbiC0C0, TH0R |
|           15 |     5154 | 2024-03-02 | SINNERS Esports         | L   | 0.611      | -            | -                | -                | -         |    -3.46 | EddezeNNN, PANDAZ, RavlE, StebbiC0C0, TH0R |
|           14 |     5922 | 2024-02-17 | Þór                     | L   | 0.518      | -            | -                | -                | -         |   -12.04 | EddezeNNN, PANDAZ, RavlE, StebbiC0C0, TH0R |
|           13 |     6372 | 2024-02-06 | Þór                     | W   | 0.445      | 0.143        | 0.000 (0.000)    | 0.034 (0.002)    | 0 (0.000) |     2.08 | EddezeNNN, PANDAZ, RavlE, StebbiC0C0, TH0R |
|           12 |     6477 | 2024-02-04 | Metizport               | L   | 0.429      | -            | -                | -                | -         |    -2.35 | EddezeNNN, PANDAZ, RavlE, StebbiC0C0, TH0R |
|           11 |     6653 | 2024-02-01 | Ármann                  | L   | 0.412      | -            | -                | -                | -         |   -10.12 | EddezeNNN, PANDAZ, RavlE, StebbiC0C0, TH0R |
|           10 |     6797 | 2024-01-29 | GODSENT                 | L   | 0.392      | -            | -                | -                | -         |    -7.54 | EddezeNNN, PANDAZ, RavlE, StebbiC0C0, TH0R |
|            9 |     6918 | 2024-01-27 | ex-Raptors Esports Club | L   | 0.379      | -            | -                | -                | -         |    -7.63 | EddezeNNN, PANDAZ, RavlE, StebbiC0C0, TH0R |
|            8 |     6921 | 2024-01-27 | PUGSTAR5                | W   | 0.378      | 0.143        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     1.53 | EddezeNNN, PANDAZ, RavlE, StebbiC0C0, TH0R |
|            7 |     7334 | 2024-01-20 | FH                      | W   | 0.331      | 0.143        | 0.000 (0.000)    | 0.021 (0.001)    | 0 (0.000) |     1.35 | EddezeNNN, PANDAZ, RavlE, StebbiC0C0, TH0R |
|            6 |     7453 | 2024-01-18 | ÍA Akranes              | W   | 0.318      | -            | -                | -                | 0 (0.000) |     1.28 | EddezeNNN, PANDAZ, RavlE, StebbiC0C0, TH0R |
|            5 |     7924 | 2024-01-11 | SAGA Esports            | W   | 0.271      | 0.143        | 0.003 (0.000)    | 0.072 (0.003)    | 0 (0.000) |     2.55 | EddezeNNN, PANDAZ, RavlE, StebbiC0C0, TH0R |
|            4 |     8573 | 2023-12-16 | 1win Academy            | L   | 0.098      | -            | -                | -                | -         |    -2.07 | EddezeNNN, PANDAZ, RavlE, StebbiC0C0, TH0R |
|            3 |     8782 | 2023-12-14 | CYBER.MD                | W   | 0.085      | 0.284        | 0.000 (0.000)    | 0.002 (0.000)    | -         |     0.55 | EddezeNNN, PANDAZ, RavlE, StebbiC0C0, TH0R |
|            2 |     8820 | 2023-12-13 | Enosis                  | W   | 0.078      | -            | -                | -                | -         |     0.32 | EddezeNNN, PANDAZ, RavlE, StebbiC0C0, TH0R |
|            1 |     9138 | 2023-12-07 | ÍBV Esports             | W   | 0.038      | -            | -                | -                | -         |     0.16 | EddezeNNN, PANDAZ, RavlE, StebbiC0C0, TH0R |

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
