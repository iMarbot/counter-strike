### Roster Details<br />
Team Name: GUN5 Esports<br />
Roster: FinigaN, relaxxie, tried, xiELO, zweih<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [287](../standings_global.md)<br />
Regional Rank: [182]( ../standings_europe.md)<br />
Final Rank Value:  653.9<br />
<br />
Final Rank Value (653.9) = Starting Rank Value (595.1) + Head To Head Adjustments (58.8)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.000[<sup>1</sup>](#table2)
- Bounty Collected: 0.319[<sup>2</sup>](#table1)
- Opponent Network: 0.065[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.096<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 595.1
- 400 + ( ( 0.096 - 0.000 ) / ( 0.787 - 0.000 ) ) * 1600 = 595.1


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent            | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                 |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           24 |     2484 | 2024-04-23 | 500                 | L   | 0.955      | -            | -                | -                | -         |    -7.90 | FinigaN, relaxxie, tried, xiELO, zweih |
|           23 |     2522 | 2024-04-22 | RUBY                | L   | 0.948      | -            | -                | -                | -         |    -4.86 | FinigaN, relaxxie, tried, xiELO, zweih |
|           22 |     2627 | 2024-04-20 | Runners             | L   | 0.937      | -            | -                | -                | -         |   -20.53 | FinigaN, m1QUSE, tried, xiELO, zweih   |
|           21 |     2694 | 2024-04-20 | RUSH B              | W   | 0.935      | 0.143        | 0.001 (0.000)    | 0.446 (0.060)    | 0 (0.000) |    20.66 | FinigaN, lov1kus, supra, tried, xiELO  |
|           20 |     3375 | 2024-04-08 | KOI                 | L   | 0.857      | -            | -                | -                | -         |    -3.12 | FinigaN, lov1kus, supra, tried, xiELO  |
|           19 |     3383 | 2024-04-08 | Apeks               | L   | 0.856      | -            | -                | -                | -         |    -1.17 | FinigaN, lov1kus, supra, tried, xiELO  |
|           18 |     3720 | 2024-04-01 | GamerLegion         | L   | 0.809      | -            | -                | -                | -         |    -0.98 | FinigaN, lov1kus, supra, tried, xiELO  |
|           17 |     3977 | 2024-03-26 | FORZE Esports       | L   | 0.771      | -            | -                | -                | -         |    -2.19 | FinigaN, lov1kus, supra, tried, xiELO  |
|           16 |     4281 | 2024-03-19 | 3DMAX               | L   | 0.723      | -            | -                | -                | -         |    -4.11 | FinigaN, lov1kus, supra, tried, xiELO  |
|           15 |     5102 | 2024-03-05 | Nemiga Gaming       | L   | 0.631      | -            | -                | -                | -         |    -0.81 | FinigaN, lov1kus, supra, tried, xiELO  |
|           14 |     5132 | 2024-03-04 | RUSH B              | W   | 0.625      | 0.143        | 0.001 (0.000)    | 0.446 (0.040)    | 0 (0.000) |    12.81 | FinigaN, lov1kus, supra, tried, xiELO  |
|           13 |     5175 | 2024-03-04 | ex-Guild Eagles     | W   | 0.625      | 0.143        | 0.015 (0.001)    | 0.475 (0.042)    | 0 (0.000) |    16.83 | FinigaN, lov1kus, supra, tried, xiELO  |
|           12 |     5276 | 2024-03-02 | Nexus Gaming        | L   | 0.612      | -            | -                | -                | -         |    -3.71 | FinigaN, lov1kus, supra, tried, xiELO  |
|           11 |     5291 | 2024-03-02 | Endpoint            | W   | 0.611      | 0.143        | 0.012 (0.001)    | 0.770 (0.067)    | 0 (0.000) |    15.93 | FinigaN, lov1kus, supra, tried, xiELO  |
|           10 |     5476 | 2024-02-28 | GenOne              | W   | 0.590      | 0.371        | 0.000 (0.000)    | 0.442 (0.097)    | 0 (0.000) |     9.42 | FinigaN, lov1kus, supra, tried, xiELO  |
|            9 |     5687 | 2024-02-24 | ex-KRC Genk Esports | W   | 0.564      | 0.371        | 0.000 (0.000)    | 0.173 (0.036)    | 0 (0.000) |    10.71 | FinigaN, lov1kus, supra, tried, xiELO  |
|            8 |     5768 | 2024-02-23 | V1dar Gaming        | L   | 0.557      | -            | -                | -                | -         |    -6.99 | FinigaN, lov1kus, supra, tried, xiELO  |
|            7 |     5814 | 2024-02-22 | Grannys Knockers    | L   | 0.551      | -            | -                | -                | -         |    -5.27 | FinigaN, lov1kus, supra, tried, xiELO  |
|            6 |     5868 | 2024-02-21 | RoundsGG            | L   | 0.544      | -            | -                | -                | -         |    -8.87 | FinigaN, lov1kus, supra, tried, xiELO  |
|            5 |     5876 | 2024-02-21 | VaselineWorms       | W   | 0.544      | 0.371        | 0.000 (0.000)    | 0.418 (0.084)    | 0 (0.000) |    10.04 | FinigaN, lov1kus, supra, tried, xiELO  |
|            4 |     6052 | 2024-02-18 | Nemiga Gaming       | W   | 0.523      | 0.371        | 0.358 (0.070)    | 0.895 (0.174)    | 0 (0.000) |    16.05 | FinigaN, lov1kus, supra, tried, xiELO  |
|            3 |     6978 | 2024-01-30 | FORZE Esports       | L   | 0.397      | -            | -                | -                | -         |    -5.02 | FinigaN, lov1kus, supra, tried, xiELO  |
|            2 |     7012 | 2024-01-29 | PARIVISION          | W   | 0.392      | 0.143        | 0.002 (0.000)    | 0.329 (0.018)    | 0 (0.000) |    10.56 | FinigaN, lov1kus, supra, tried, xiELO  |
|            1 |     7043 | 2024-01-29 | SINNERS Esports     | W   | 0.391      | 0.143        | 0.011 (0.001)    | 0.582 (0.033)    | 0 (0.000) |    11.31 | FinigaN, lov1kus, supra, tried, xiELO  |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($0.00)
- Divide that value by the 5th highest value among all rosters ($300,806.11)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
