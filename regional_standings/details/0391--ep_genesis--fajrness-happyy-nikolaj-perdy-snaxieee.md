### Roster Details<br />
Team Name: EP Genesis<br />
Roster: fajrness, Happyy, NIKOLAJ, PerdY, Snaxieee<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [391](../standings_global.md)<br />
Regional Rank: [234]( ../standings_europe.md)<br />
Final Rank Value:  572.3<br />
<br />
Final Rank Value (572.3) = Starting Rank Value (524.9) + Head To Head Adjustments (47.3)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.000[<sup>1</sup>](#table2)
- Bounty Collected: 0.216[<sup>2</sup>](#table1)
- Opponent Network: 0.029[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.061<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 524.9
- 400 + ( ( 0.061 - 0.000 ) / ( 0.787 - 0.000 ) ) * 1600 = 524.9


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent              | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                     |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           23 |      753 | 2024-05-19 | SINNERS Esports       | L   | 1.000      | -            | -                | -                | -         |    -3.03 | fajrness, Happyy, NIKOLAJ, PerdY, Snaxieee |
|           22 |      989 | 2024-05-17 | Team Sampi            | L   | 1.000      | -            | -                | -                | -         |    -2.73 | fajrness, Happyy, NIKOLAJ, PerdY, Snaxieee |
|           21 |     1089 | 2024-05-16 | SINNERS Esports       | W   | 1.000      | 0.143        | 0.011 (0.002)    | 0.582 (0.083)    | 0 (0.000) |    28.78 | fajrness, Happyy, NIKOLAJ, PerdY, Snaxieee |
|           20 |     1371 | 2024-05-12 | Sampi NEXT            | W   | 1.000      | 0.143        | 0.000 (0.000)    | 0.055 (0.008)    | 0 (0.000) |    12.23 | fajrness, Happyy, NIKOLAJ, PerdY, Snaxieee |
|           19 |     1451 | 2024-05-11 | Lan Party Hotel       | W   | 1.000      | 0.143        | 0.000 (0.000)    | 0.016 (0.002)    | 0 (0.000) |     9.80 | fajrness, Happyy, NIKOLAJ, PerdY, Snaxieee |
|           18 |     1591 | 2024-05-09 | Sampi NEXT            | L   | 1.000      | -            | -                | -                | -         |   -18.62 | fajrness, Happyy, NIKOLAJ, PerdY, Snaxieee |
|           17 |     2099 | 2024-04-29 | L&G                   | L   | 0.997      | -            | -                | -                | -         |    -7.24 | fajrness, Happyy, NIKOLAJ, PerdY, Snaxieee |
|           16 |     2211 | 2024-04-27 | Lazer Cats            | L   | 0.984      | -            | -                | -                | -         |    -8.92 | fajrness, Happyy, NIKOLAJ, PerdY, Snaxieee |
|           15 |     2305 | 2024-04-26 | Dynamo Eclot Thunders | W   | 0.976      | 0.289        | 0.000 (0.000)    | 0.026 (0.007)    | 0 (0.000) |     8.40 | fajrness, Happyy, NIKOLAJ, PerdY, Snaxieee |
|           14 |     2460 | 2024-04-23 | BRUTE                 | W   | 0.957      | 0.289        | 0.000 (0.000)    | 0.157 (0.043)    | 0 (0.000) |    13.72 | fajrness, Happyy, NIKOLAJ, PerdY, Snaxieee |
|           13 |     3910 | 2024-03-27 | Apeks Rebels          | L   | 0.777      | -            | -                | -                | -         |   -12.55 | fajrness, Happyy, NIKOLAJ, PerdY, Snaxieee |
|           12 |     4092 | 2024-03-23 | ALTERNATE aTTaX Evo   | W   | 0.751      | 0.289        | 0.002 (0.000)    | 0.239 (0.052)    | 0 (0.000) |    16.28 | fajrness, Happyy, NIKOLAJ, PerdY, Snaxieee |
|           11 |     4278 | 2024-03-19 | Apeks Rebels          | L   | 0.723      | -            | -                | -                | -         |   -11.76 | fajrness, Happyy, NIKOLAJ, PerdY, Snaxieee |
|           10 |     4712 | 2024-03-11 | nomatter              | L   | 0.671      | -            | -                | -                | -         |   -12.05 | fajrness, Happyy, NIKOLAJ, PerdY, Snaxieee |
|            9 |     4824 | 2024-03-09 | Team LRP Poland       | W   | 0.658      | 0.333        | 0.001 (0.000)    | 0.056 (0.012)    | 0 (0.000) |    14.85 | fajrness, Happyy, NIKOLAJ, PerdY, Snaxieee |
|            8 |     4925 | 2024-03-07 | Gorillas              | L   | 0.645      | -            | -                | -                | -         |    -9.54 | fajrness, Happyy, NIKOLAJ, PerdY, Snaxieee |
|            7 |     4952 | 2024-03-07 | UNiTY esports         | L   | 0.643      | -            | -                | -                | -         |    -3.69 | fajrness, Happyy, NIKOLAJ, PerdY, Snaxieee |
|            6 |     5016 | 2024-03-06 | Lan Party Hotel       | W   | 0.636      | 0.143        | 0.000 (0.000)    | -                | 0 (0.000) |     6.16 | fajrness, Happyy, NIKOLAJ, PerdY, Snaxieee |
|            5 |     5089 | 2024-03-05 | Begrip Gaming         | W   | 0.631      | 0.333        | 0.000 (0.000)    | 0.317 (0.067)    | 0 (0.000) |    11.84 | fajrness, Happyy, NIKOLAJ, PerdY, Snaxieee |
|            4 |     5190 | 2024-03-04 | UNiTY esports         | L   | 0.623      | -            | -                | -                | -         |    -3.19 | fajrness, Happyy, NIKOLAJ, PerdY, Snaxieee |
|            3 |     5525 | 2024-02-27 | BRUTE                 | W   | 0.584      | 0.143        | -                | 0.157 (0.013)    | 0 (0.000) |     9.94 | fajrness, Happyy, NIKOLAJ, PerdY, Snaxieee |
|            2 |     5571 | 2024-02-26 | VENI VIDI VICI        | W   | 0.577      | 0.143        | 0.001 (0.000)    | 0.075 (0.006)    | -         |    11.47 | fajrness, Happyy, NIKOLAJ, PerdY, Snaxieee |
|            1 |     6753 | 2024-02-03 | ex-sYnck              | L   | 0.423      | -            | -                | -                | -         |    -2.80 | fajrness, Happyy, NIKOLAJ, PerdY, Snaxieee |

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
