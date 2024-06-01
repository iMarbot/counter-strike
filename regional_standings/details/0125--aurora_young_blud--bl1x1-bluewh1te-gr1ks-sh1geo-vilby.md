### Roster Details<br />
Team Name: Aurora Young Blud<br />
Roster: bl1x1, bluewh1te, gr1ks, sh1geo, VILBy<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [125](../standings_global.md)<br />
Regional Rank: [87]( ../standings_europe.md)<br />
Final Rank Value:  817.0<br />
<br />
Final Rank Value (817.0) = Starting Rank Value (793.0) + Head To Head Adjustments (24.0)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.325[<sup>1</sup>](#table2)
- Bounty Collected: 0.317[<sup>2</sup>](#table1)
- Opponent Network: 0.130[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.193<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 793.0
- 400 + ( ( 0.193 - 0.000 ) / ( 0.786 - 0.000 ) ) * 1600 = 793.0


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent             | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                 |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           53 |      120 | 2024-05-28 | ENCE Academy         | W   | 1.000      | 0.143        | 0.012 (0.002)    | -                | 0 (0.000) |    13.05 | bl1x1, bluewh1te, gr1ks, sh1geo, VILBy |
|           52 |      131 | 2024-05-28 | ZEROvariant          | W   | 1.000      | -            | -                | -                | 0 (0.000) |     6.12 | bl1x1, bluewh1te, gr1ks, sh1geo, VILBy |
|           51 |      184 | 2024-05-27 | TOR                  | W   | 1.000      | 0.143        | 0.014 (0.002)    | -                | 0 (0.000) |    15.20 | bl1x1, bluewh1te, gr1ks, sh1geo, VILBy |
|           50 |      190 | 2024-05-27 | Donstu Esports       | W   | 1.000      | -            | -                | -                | 0 (0.000) |     8.92 | bl1x1, bluewh1te, gr1ks, sh1geo, VILBy |
|           49 |      292 | 2024-05-25 | DOSKI                | W   | 1.000      | -            | -                | -                | 0 (0.000) |     3.92 | bl1x1, bluewh1te, gr1ks, sh1geo, VILBy |
|           48 |      356 | 2024-05-24 | polizej              | L   | 1.000      | -            | -                | -                | -         |   -25.52 | bl1x1, bluewh1te, gr1ks, sh1geo, VILBy |
|           47 |      381 | 2024-05-23 | TopTab Club          | W   | 1.000      | -            | -                | -                | 0 (0.000) |     4.52 | bl1x1, bluewh1te, gr1ks, sh1geo, VILBy |
|           46 |      477 | 2024-05-22 | RoundsGG             | W   | 1.000      | 0.372        | -                | 0.202 (0.075)    | 0 (0.000) |     7.29 | bl1x1, bluewh1te, gr1ks, sh1geo, VILBy |
|           45 |      747 | 2024-05-19 | ex-KRC Genk Esports  | W   | 1.000      | -            | -                | -                | 0 (0.000) |     9.46 | bl1x1, bluewh1te, Easy, sh1geo, VILBy  |
|           44 |     1616 | 2024-05-08 | AscendX Esports      | W   | 1.000      | -            | -                | -                | 0 (0.000) |     3.02 | bl1x1, bluewh1te, Easy, sh1geo, VILBy  |
|           43 |     1969 | 2024-05-01 | VaselineWorms        | L   | 1.000      | -            | -                | -                | -         |   -21.02 | bl1x1, bluewh1te, Easy, sh1geo, VILBy  |
|           42 |     2070 | 2024-04-29 | Verdant              | L   | 0.997      | -            | -                | -                | -         |   -13.06 | bl1x1, bluewh1te, Easy, sh1geo, VILBy  |
|           41 |     2359 | 2024-04-24 | ADEPTS               | W   | 0.964      | 0.372        | 0.005 (0.002)    | 0.291 (0.104)    | 0 (0.000) |    16.29 | bl1x1, bluewh1te, Easy, sh1geo, VILBy  |
|           40 |     2380 | 2024-04-24 | HyperSpirit          | W   | 0.963      | 0.372        | 0.004 (0.001)    | 0.356 (0.128)    | -         |    14.54 | bl1x1, bluewh1te, Easy, sh1geo, VILBy  |
|           39 |     2422 | 2024-04-23 | DASH                 | W   | 0.956      | 0.372        | -                | 0.358 (0.127)    | -         |    12.29 | bl1x1, bluewh1te, Easy, sh1geo, VILBy  |
|           38 |     2494 | 2024-04-21 | Rhyno Esports        | L   | 0.943      | -            | -                | -                | -         |    -7.29 | bl1x1, bluewh1te, Easy, sh1geo, VILBy  |
|           37 |     2581 | 2024-04-20 | Dynamo Eclot         | W   | 0.937      | 0.333        | 0.097 (0.030)    | 0.936 (0.292)    | -         |    23.80 | bl1x1, bluewh1te, Easy, sh1geo, VILBy  |
|           36 |     2787 | 2024-04-18 | Rhyno Esports        | W   | 0.922      | 0.333        | 0.029 (0.009)    | 0.518 (0.159)    | -         |    21.90 | bl1x1, bluewh1te, Easy, sh1geo, VILBy  |
|           35 |     2925 | 2024-04-16 | ALTERNATE aTTaX      | L   | 0.909      | -            | -                | -                | -         |    -6.75 | bl1x1, bluewh1te, Easy, sh1geo, VILBy  |
|           34 |     2943 | 2024-04-15 | FLuffy Gangsters     | L   | 0.904      | -            | -                | -                | -         |   -20.17 | bl1x1, bluewh1te, Easy, sh1geo, VILBy  |
|           33 |     2959 | 2024-04-15 | Sangal Esports       | L   | 0.903      | -            | -                | -                | -         |    -6.54 | bl1x1, bluewh1te, Easy, sh1geo, VILBy  |
|           32 |     3077 | 2024-04-12 | Zero Tenacity        | L   | 0.883      | -            | -                | -                | -         |    -7.15 | bl1x1, bluewh1te, Easy, sh1geo, VILBy  |
|           31 |     3125 | 2024-04-11 | VP.Prodigy           | L   | 0.876      | -            | -                | -                | -         |   -10.82 | bl1x1, bluewh1te, Easy, sh1geo, VILBy  |
|           30 |     3247 | 2024-04-09 | Lemondogs            | W   | 0.863      | 0.333        | -                | 0.274 (0.079)    | -         |     7.36 | bl1x1, bluewh1te, Easy, sh1geo, VILBy  |
|           29 |     3513 | 2024-04-04 | ENCE                 | L   | 0.829      | -            | -                | -                | -         |    -0.67 | bl1x1, bluewh1te, Easy, sh1geo, VILBy  |
|           28 |     5030 | 2024-03-04 | Nemiga Gaming        | L   | 0.625      | -            | -                | -                | -         |    -1.28 | bl1x1, bluewh1te, Easy, sh1geo, VILBy  |
|           27 |     5155 | 2024-03-02 | Nexus Gaming         | L   | 0.611      | -            | -                | -                | -         |    -5.98 | bl1x1, bluewh1te, Easy, sh1geo, VILBy  |
|           26 |     5288 | 2024-02-29 | ex-K10               | W   | 0.596      | 0.371        | 0.005 (0.001)    | 0.382 (0.085)    | -         |    10.86 | bl1x1, bluewh1te, Easy, sh1geo, VILBy  |
|           25 |     5323 | 2024-02-28 | Nexus Gaming         | L   | 0.590      | -            | -                | -                | -         |    -5.72 | bl1x1, bluewh1te, Easy, sh1geo, VILBy  |
|           24 |     5609 | 2024-02-23 | The Chosen Few       | L   | 0.557      | -            | -                | -                | -         |    -8.63 | bl1x1, bluewh1te, Easy, sh1geo, VILBy  |
|           23 |     5664 | 2024-02-22 | DMS                  | L   | 0.550      | -            | -                | -                | -         |   -10.30 | bl1x1, bluewh1te, Easy, sh1geo, VILBy  |
|           22 |     5694 | 2024-02-21 | Endpoint             | W   | 0.544      | 0.371        | 0.012 (0.002)    | 0.718 (0.145)    | -         |    11.92 | bl1x1, bluewh1te, Easy, sh1geo, VILBy  |
|           21 |     5822 | 2024-02-19 | FORZE Youngsters     | L   | 0.531      | -            | -                | -                | -         |   -11.27 | bl1x1, bluewh1te, Easy, sh1geo, VILBy  |
|           20 |     5831 | 2024-02-19 | Sashi Esport         | L   | 0.531      | -            | -                | -                | -         |    -2.67 | bl1x1, bluewh1te, Easy, sh1geo, VILBy  |
|           19 |     5987 | 2024-02-16 | Entropiq             | W   | 0.510      | -            | -                | -                | -         |     5.60 | bl1x1, bluewh1te, Easy, sh1geo, VILBy  |
|           18 |     6157 | 2024-02-13 | GenOne               | L   | 0.490      | -            | -                | -                | -         |   -12.33 | bl1x1, bluewh1te, Easy, sh1geo, VILBy  |
|           17 |     6333 | 2024-02-08 | ARCRED               | L   | 0.457      | -            | -                | -                | -         |    -7.85 | bl1x1, bluewh1te, Easy, sh1geo, VILBy  |
|           16 |     6426 | 2024-02-05 | Eternal Fire Academy | W   | 0.437      | -            | -                | -                | -         |     4.30 | bl1x1, bluewh1te, Easy, sh1geo, VILBy  |
|           15 |     7426 | 2024-01-19 | Permitta Esports     | L   | 0.322      | -            | -                | -                | -         |    -3.04 | bl1x1, bluewh1te, Easy, sh1geo, VILBy  |
|           14 |     7494 | 2024-01-18 | Zero Tenacity        | W   | 0.315      | 0.333        | 0.147 (0.015)    | 1.000 (0.105)    | -         |     8.15 | bl1x1, bluewh1te, Easy, sh1geo, VILBy  |
|           13 |     7591 | 2024-01-17 | MOUZ NXT             | L   | 0.308      | -            | -                | -                | -         |    -1.47 | bl1x1, bluewh1te, Easy, sh1geo, VILBy  |
|           12 |     7618 | 2024-01-16 | JANO Esports         | L   | 0.305      | -            | -                | -                | -         |    -8.01 | bl1x1, bluewh1te, Easy, sh1geo, VILBy  |
|           11 |     7634 | 2024-01-16 | esmagaB              | W   | 0.305      | -            | -                | -                | -         |     5.44 | bl1x1, bluewh1te, Easy, sh1geo, VILBy  |
|           10 |     7649 | 2024-01-16 | Lemondogs            | W   | 0.304      | -            | -                | -                | -         |     2.31 | bl1x1, bluewh1te, Easy, sh1geo, VILBy  |
|            9 |     7671 | 2024-01-16 | 500                  | W   | 0.304      | -            | -                | -                | -         |     4.54 | bl1x1, bluewh1te, Easy, sh1geo, VILBy  |
|            8 |     7713 | 2024-01-15 | Team Spirit Academy  | W   | 0.296      | -            | -                | -                | -         |     4.04 | bl1x1, bluewh1te, Easy, sh1geo, VILBy  |
|            7 |     7801 | 2024-01-13 | Lazer Cats           | W   | 0.282      | -            | -                | -                | -         |     1.41 | bl1x1, bluewh1te, Easy, sh1geo, VILBy  |
|            6 |     8019 | 2024-01-10 | esmagaB              | L   | 0.265      | -            | -                | -                | -         |    -3.48 | bl1x1, bluewh1te, Easy, sh1geo, VILBy  |
|            5 |     8182 | 2024-01-08 | Dynamo Eclot         | L   | 0.249      | -            | -                | -                | -         |    -1.19 | bl1x1, bluewh1te, Easy, sh1geo, VILBy  |
|            4 |     8234 | 2024-01-04 | Lazer Cats           | W   | 0.222      | -            | -                | -                | -         |     1.09 | bl1x1, bluewh1te, Easy, sh1geo, VILBy  |
|            3 |     8308 | 2023-12-29 | Metizport            | L   | 0.184      | -            | -                | -                | -         |    -1.57 | bl1x1, bluewh1te, Easy, sh1geo, VILBy  |
|            2 |     8312 | 2023-12-28 | The Witchers         | L   | 0.177      | -            | -                | -                | -         |    -3.44 | bl1x1, bluewh1te, Easy, sh1geo, VILBy  |
|            1 |     8317 | 2023-12-27 | Metizport            | W   | 0.170      | 0.371        | 0.088 (0.006)    | -                | -         |     3.90 | bl1x1, bluewh1te, Easy, sh1geo, VILBy  |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($2,525.83)
- Divide that value by the 5th highest value among all rosters ($300,806.11)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-04-21 |      0.943 | $2,500.00      | $2,358.33       |
| 2024-01-21 |      0.335 | $500.00        | $167.50         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
