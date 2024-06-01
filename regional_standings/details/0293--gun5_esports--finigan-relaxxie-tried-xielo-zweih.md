### Roster Details<br />
Team Name: GUN5 Esports<br />
Roster: FinigaN, relaxxie, tried, xiELO, zweih<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [293](../standings_global.md)<br />
Regional Rank: [179]( ../standings_europe.md)<br />
Final Rank Value:  646.6<br />
<br />
Final Rank Value (646.6) = Starting Rank Value (594.4) + Head To Head Adjustments (52.2)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.000[<sup>1</sup>](#table2)
- Bounty Collected: 0.320[<sup>2</sup>](#table1)
- Opponent Network: 0.062[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.096<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 594.4
- 400 + ( ( 0.096 - 0.000 ) / ( 0.786 - 0.000 ) ) * 1600 = 594.4


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
|           24 |     2436 | 2024-04-23 | 500                 | L   | 0.955      | -            | -                | -                | -         |    -7.85 | FinigaN, relaxxie, tried, xiELO, zweih |
|           23 |     2470 | 2024-04-22 | RUBY                | L   | 0.948      | -            | -                | -                | -         |    -4.73 | FinigaN, relaxxie, tried, xiELO, zweih |
|           22 |     2574 | 2024-04-20 | Runners             | L   | 0.937      | -            | -                | -                | -         |   -20.27 | FinigaN, m1QUSE, tried, xiELO, zweih   |
|           21 |     2640 | 2024-04-20 | RUSH B              | W   | 0.935      | 0.143        | 0.001 (0.000)    | 0.446 (0.060)    | 0 (0.000) |    20.59 | FinigaN, lov1kus, supra, tried, xiELO  |
|           20 |     3294 | 2024-04-08 | KOI                 | L   | 0.857      | -            | -                | -                | -         |    -3.06 | FinigaN, lov1kus, supra, tried, xiELO  |
|           19 |     3302 | 2024-04-08 | Apeks               | L   | 0.856      | -            | -                | -                | -         |    -1.11 | FinigaN, lov1kus, supra, tried, xiELO  |
|           18 |     3628 | 2024-04-01 | GamerLegion         | L   | 0.809      | -            | -                | -                | -         |    -0.93 | FinigaN, lov1kus, supra, tried, xiELO  |
|           17 |     3880 | 2024-03-26 | FORZE Esports       | L   | 0.771      | -            | -                | -                | -         |    -2.26 | FinigaN, lov1kus, supra, tried, xiELO  |
|           16 |     4178 | 2024-03-19 | 3DMAX               | L   | 0.723      | -            | -                | -                | -         |    -4.00 | FinigaN, lov1kus, supra, tried, xiELO  |
|           15 |     4959 | 2024-03-05 | Nemiga Gaming       | L   | 0.631      | -            | -                | -                | -         |    -0.75 | FinigaN, lov1kus, supra, tried, xiELO  |
|           14 |     4986 | 2024-03-04 | RUSH B              | W   | 0.625      | 0.143        | 0.001 (0.000)    | 0.446 (0.040)    | 0 (0.000) |    12.99 | FinigaN, lov1kus, supra, tried, xiELO  |
|           13 |     5029 | 2024-03-04 | ex-Guild Eagles     | W   | 0.625      | 0.143        | 0.015 (0.001)    | 0.475 (0.042)    | 0 (0.000) |    16.85 | FinigaN, lov1kus, supra, tried, xiELO  |
|           12 |     5128 | 2024-03-02 | Nexus Gaming        | L   | 0.612      | -            | -                | -                | -         |    -3.35 | FinigaN, lov1kus, supra, tried, xiELO  |
|           11 |     5143 | 2024-03-02 | Endpoint            | W   | 0.611      | 0.143        | 0.012 (0.001)    | 0.718 (0.063)    | 0 (0.000) |    16.03 | FinigaN, lov1kus, supra, tried, xiELO  |
|           10 |     5325 | 2024-02-28 | GenOne              | W   | 0.590      | 0.371        | 0.000 (0.000)    | 0.442 (0.097)    | 0 (0.000) |     9.55 | FinigaN, lov1kus, supra, tried, xiELO  |
|            9 |     5527 | 2024-02-24 | ex-KRC Genk Esports | W   | 0.564      | 0.371        | 0.000 (0.000)    | 0.120 (0.025)    | 0 (0.000) |     9.50 | FinigaN, lov1kus, supra, tried, xiELO  |
|            8 |     5608 | 2024-02-23 | V1dar Gaming        | L   | 0.557      | -            | -                | -                | -         |    -7.16 | FinigaN, lov1kus, supra, tried, xiELO  |
|            7 |     5654 | 2024-02-22 | Grindas             | L   | 0.551      | -            | -                | -                | -         |   -11.91 | FinigaN, lov1kus, supra, tried, xiELO  |
|            6 |     5705 | 2024-02-21 | RoundsGG            | L   | 0.544      | -            | -                | -                | -         |    -9.42 | FinigaN, lov1kus, supra, tried, xiELO  |
|            5 |     5713 | 2024-02-21 | VaselineWorms       | W   | 0.544      | 0.371        | 0.000 (0.000)    | 0.424 (0.086)    | 0 (0.000) |    10.12 | FinigaN, lov1kus, supra, tried, xiELO  |
|            4 |     5879 | 2024-02-18 | Nemiga Gaming       | W   | 0.523      | 0.371        | 0.366 (0.071)    | 0.830 (0.161)    | 0 (0.000) |    16.07 | FinigaN, lov1kus, supra, tried, xiELO  |
|            3 |     6762 | 2024-01-30 | FORZE Esports       | L   | 0.397      | -            | -                | -                | -         |    -4.47 | FinigaN, lov1kus, supra, tried, xiELO  |
|            2 |     6796 | 2024-01-29 | PARIVISION          | W   | 0.392      | 0.143        | 0.002 (0.000)    | 0.329 (0.018)    | 0 (0.000) |    10.57 | FinigaN, lov1kus, supra, tried, xiELO  |
|            1 |     6827 | 2024-01-29 | SINNERS Esports     | W   | 0.391      | 0.143        | 0.011 (0.001)    | 0.560 (0.031)    | 0 (0.000) |    11.19 | FinigaN, lov1kus, supra, tried, xiELO  |

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
