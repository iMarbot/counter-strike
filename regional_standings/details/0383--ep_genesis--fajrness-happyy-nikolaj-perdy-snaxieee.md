### Roster Details<br />
Team Name: EP Genesis<br />
Roster: fajrness, Happyy, NIKOLAJ, PerdY, Snaxieee<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [383](../standings_global.md)<br />
Regional Rank: [227]( ../standings_europe.md)<br />
Final Rank Value:  572.0<br />
<br />
Final Rank Value (572.0) = Starting Rank Value (525.0) + Head To Head Adjustments (47.0)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.000[<sup>1</sup>](#table2)
- Bounty Collected: 0.216[<sup>2</sup>](#table1)
- Opponent Network: 0.029[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.061<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 525.0
- 400 + ( ( 0.061 - 0.000 ) / ( 0.786 - 0.000 ) ) * 1600 = 525.0


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
|           23 |      741 | 2024-05-19 | SINNERS Esports       | L   | 1.000      | -            | -                | -                | -         |    -3.15 | fajrness, Happyy, NIKOLAJ, PerdY, Snaxieee |
|           22 |      977 | 2024-05-17 | Team Sampi            | L   | 1.000      | -            | -                | -                | -         |    -2.76 | fajrness, Happyy, NIKOLAJ, PerdY, Snaxieee |
|           21 |     1079 | 2024-05-16 | SINNERS Esports       | W   | 1.000      | 0.143        | 0.011 (0.002)    | 0.560 (0.080)    | 0 (0.000) |    28.66 | fajrness, Happyy, NIKOLAJ, PerdY, Snaxieee |
|           20 |     1359 | 2024-05-12 | Sampi NEXT            | W   | 1.000      | 0.143        | 0.000 (0.000)    | 0.055 (0.008)    | 0 (0.000) |    12.24 | fajrness, Happyy, NIKOLAJ, PerdY, Snaxieee |
|           19 |     1438 | 2024-05-11 | Lan Party Hotel       | W   | 1.000      | 0.143        | 0.000 (0.000)    | 0.016 (0.002)    | 0 (0.000) |     9.78 | fajrness, Happyy, NIKOLAJ, PerdY, Snaxieee |
|           18 |     1575 | 2024-05-09 | Sampi NEXT            | L   | 1.000      | -            | -                | -                | -         |   -18.61 | fajrness, Happyy, NIKOLAJ, PerdY, Snaxieee |
|           17 |     2064 | 2024-04-29 | L&G                   | L   | 0.997      | -            | -                | -                | -         |    -7.33 | fajrness, Happyy, NIKOLAJ, PerdY, Snaxieee |
|           16 |     2176 | 2024-04-27 | Lazer Cats            | L   | 0.984      | -            | -                | -                | -         |    -8.94 | fajrness, Happyy, NIKOLAJ, PerdY, Snaxieee |
|           15 |     2269 | 2024-04-26 | Dynamo Eclot Thunders | W   | 0.976      | 0.289        | 0.000 (0.000)    | 0.026 (0.007)    | 0 (0.000) |     8.40 | fajrness, Happyy, NIKOLAJ, PerdY, Snaxieee |
|           14 |     2413 | 2024-04-23 | BRUTE                 | W   | 0.957      | 0.289        | 0.000 (0.000)    | 0.157 (0.043)    | 0 (0.000) |    13.64 | fajrness, Happyy, NIKOLAJ, PerdY, Snaxieee |
|           13 |     3817 | 2024-03-27 | Apeks Rebels          | L   | 0.777      | -            | -                | -                | -         |   -12.55 | fajrness, Happyy, NIKOLAJ, PerdY, Snaxieee |
|           12 |     3995 | 2024-03-23 | ALTERNATE aTTaX Evo   | W   | 0.751      | 0.289        | 0.002 (0.000)    | 0.239 (0.052)    | 0 (0.000) |    16.58 | fajrness, Happyy, NIKOLAJ, PerdY, Snaxieee |
|           11 |     4175 | 2024-03-19 | Apeks Rebels          | L   | 0.723      | -            | -                | -                | -         |   -11.75 | fajrness, Happyy, NIKOLAJ, PerdY, Snaxieee |
|           10 |     4590 | 2024-03-11 | nomatter              | L   | 0.671      | -            | -                | -                | -         |   -12.04 | fajrness, Happyy, NIKOLAJ, PerdY, Snaxieee |
|            9 |     4699 | 2024-03-09 | Team LRP Poland       | W   | 0.658      | 0.333        | 0.001 (0.000)    | 0.056 (0.012)    | 0 (0.000) |    14.86 | fajrness, Happyy, NIKOLAJ, PerdY, Snaxieee |
|            8 |     4796 | 2024-03-07 | Gorillas              | L   | 0.645      | -            | -                | -                | -         |    -9.36 | fajrness, Happyy, NIKOLAJ, PerdY, Snaxieee |
|            7 |     4823 | 2024-03-07 | UNiTY esports         | L   | 0.643      | -            | -                | -                | -         |    -3.64 | fajrness, Happyy, NIKOLAJ, PerdY, Snaxieee |
|            6 |     4885 | 2024-03-06 | Lan Party Hotel       | W   | 0.636      | 0.143        | 0.000 (0.000)    | -                | 0 (0.000) |     6.15 | fajrness, Happyy, NIKOLAJ, PerdY, Snaxieee |
|            5 |     4949 | 2024-03-05 | Begrip Gaming         | W   | 0.631      | 0.333        | 0.000 (0.000)    | 0.317 (0.067)    | 0 (0.000) |    11.82 | fajrness, Happyy, NIKOLAJ, PerdY, Snaxieee |
|            4 |     5044 | 2024-03-04 | UNiTY esports         | L   | 0.623      | -            | -                | -                | -         |    -3.15 | fajrness, Happyy, NIKOLAJ, PerdY, Snaxieee |
|            3 |     5372 | 2024-02-27 | BRUTE                 | W   | 0.584      | 0.143        | -                | 0.157 (0.013)    | 0 (0.000) |     9.94 | fajrness, Happyy, NIKOLAJ, PerdY, Snaxieee |
|            2 |     5414 | 2024-02-26 | VENI VIDI VICI        | W   | 0.577      | 0.143        | 0.001 (0.000)    | 0.075 (0.006)    | -         |    11.49 | fajrness, Happyy, NIKOLAJ, PerdY, Snaxieee |
|            1 |     6550 | 2024-02-03 | ex-sYnck              | L   | 0.423      | -            | -                | -                | -         |    -3.27 | fajrness, Happyy, NIKOLAJ, PerdY, Snaxieee |

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
