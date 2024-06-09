### Roster Details<br />
Team Name: 9INE<br />
Roster: KEi, mynio, snatchie, Sobol, tomiko<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [349](../standings_global.md)<br />
Regional Rank: [209]( ../standings_europe.md)<br />
Final Rank Value:  608.9<br />
<br />
Final Rank Value (608.9) = Starting Rank Value (547.6) + Head To Head Adjustments (61.3)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.000[<sup>1</sup>](#table2)
- Bounty Collected: 0.254[<sup>2</sup>](#table1)
- Opponent Network: 0.036[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.073<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 547.6
- 400 + ( ( 0.073 - 0.000 ) / ( 0.787 - 0.000 ) ) * 1600 = 547.6


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent           | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                              |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           23 |     5120 | 2024-03-05 | Dynamo Eclot       | L   | 0.629      | -            | -                | -                | -         |    -1.13 | KEi, mynio, snatchie, Sobol, tomiko |
|           22 |     5131 | 2024-03-04 | Passion UA         | L   | 0.625      | -            | -                | -                | -         |    -2.65 | KEi, mynio, SaMey, Sobol, tomiko    |
|           21 |     5169 | 2024-03-04 | Lilmix             | W   | 0.625      | 0.143        | 0.006 (0.001)    | 0.593 (0.053)    | 0 (0.000) |    14.35 | KEi, mynio, SaMey, Sobol, tomiko    |
|           20 |     5232 | 2024-03-03 | ILIN               | L   | 0.617      | -            | -                | -                | -         |    -9.04 | KEi, mynio, snatchie, Sobol, tomiko |
|           19 |     5277 | 2024-03-02 | ARCRED             | W   | 0.612      | 0.143        | 0.000 (0.000)    | 0.630 (0.055)    | 0 (0.000) |    14.51 | KEi, mynio, snatchie, Sobol, tomiko |
|           18 |     5297 | 2024-03-02 | HyperSpirit        | W   | 0.611      | 0.143        | 0.004 (0.000)    | 0.356 (0.031)    | 0 (0.000) |    13.13 | KEi, mynio, snatchie, Sobol, tomiko |
|           17 |     5392 | 2024-03-01 | Alliance           | W   | 0.602      | 0.371        | 0.004 (0.001)    | 0.529 (0.118)    | 0 (0.000) |    15.74 | KEi, mynio, snatchie, Sobol, tomiko |
|           16 |     5579 | 2024-02-26 | Entropiq           | L   | 0.576      | -            | -                | -                | -         |    -5.62 | KEi, mynio, SaMey, Sobol, tomiko    |
|           15 |     6422 | 2024-02-11 | Lilmix             | L   | 0.477      | -            | -                | -                | -         |    -2.69 | Bambosh, KEi, mhL, mynio, tomiko    |
|           14 |     6427 | 2024-02-11 | KOMNATA            | W   | 0.477      | 0.143        | 0.000 (0.000)    | -                | 0 (0.000) |     4.18 | Bambosh, KEi, mhL, mynio, tomiko    |
|           13 |     6459 | 2024-02-10 | ILLYRIANS          | L   | 0.470      | -            | -                | -                | -         |    -4.22 | Bambosh, KEi, mhL, mynio, tomiko    |
|           12 |     6587 | 2024-02-06 | Alliance           | L   | 0.442      | -            | -                | -                | -         |    -2.81 | KEi, mynio, SaMey, Sobol, tomiko    |
|           11 |     6950 | 2024-01-31 | BLEED Esports      | L   | 0.402      | -            | -                | -                | -         |    -0.34 | KEi, mynio, SaMey, Sobol, tomiko    |
|           10 |     7090 | 2024-01-28 | ex-Anonymo Esports | L   | 0.383      | -            | -                | -                | -         |    -3.81 | Bambosh, KEi, mhL, mynio, tomiko    |
|            9 |     7173 | 2024-01-27 | Sprout             | L   | 0.377      | -            | -                | -                | -         |    -5.27 | Bambosh, KEi, mhL, mynio, tomiko    |
|            8 |     7180 | 2024-01-27 | Into The Breach    | W   | 0.377      | 0.143        | 0.002 (0.000)    | 0.103 (0.006)    | 0 (0.000) |     8.46 | Bambosh, KEi, mhL, mynio, tomiko    |
|            7 |     7182 | 2024-01-27 | ex-K10             | W   | 0.377      | 0.143        | 0.005 (0.000)    | 0.517 (0.028)    | 0 (0.000) |     9.96 | Bambosh, KEi, mhL, mynio, tomiko    |
|            6 |     7891 | 2024-01-16 | JANO Esports       | L   | 0.304      | -            | -                | -                | -         |    -5.66 | Bambosh, KEi, mhL, mynio, tomiko    |
|            5 |     7923 | 2024-01-16 | Metizport          | W   | 0.304      | 0.143        | 0.088 (0.004)    | 0.698 (0.030)    | 0 (0.000) |     8.65 | Bambosh, KEi, mhL, mynio, tomiko    |
|            4 |     8315 | 2024-01-09 | KOI                | L   | 0.258      | -            | -                | -                | -         |    -0.76 | Bambosh, KEi, mhL, mynio, tomiko    |
|            3 |     8337 | 2024-01-09 | Zero Tenacity      | W   | 0.257      | 0.143        | 0.147 (0.005)    | 1.000 (0.037)    | 0 (0.000) |     7.72 | Bambosh, KEi, mhL, mynio, tomiko    |
|            2 |     8348 | 2024-01-09 | naChille           | W   | 0.257      | 0.143        | 0.004 (0.000)    | 0.140 (0.005)    | 0 (0.000) |     5.17 | Bambosh, KEi, mhL, mynio, tomiko    |
|            1 |     8381 | 2024-01-09 | 00 Nation          | W   | 0.257      | 0.143        | -                | 0.031 (0.001)    | -         |     3.41 | Bambosh, KEi, mhL, mynio, tomiko    |

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
