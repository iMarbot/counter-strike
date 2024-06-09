### Roster Details<br />
Team Name: Aurora Young Blud<br />
Roster: bl1x1, bluewh1te, gr1ks, sh1geo, VILBy<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [134](../standings_global.md)<br />
Regional Rank: [93]( ../standings_europe.md)<br />
Final Rank Value:  808.7<br />
<br />
Final Rank Value (808.7) = Starting Rank Value (797.3) + Head To Head Adjustments (11.4)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.325[<sup>1</sup>](#table2)
- Bounty Collected: 0.317[<sup>2</sup>](#table1)
- Opponent Network: 0.140[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.195<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 797.3
- 400 + ( ( 0.195 - 0.000 ) / ( 0.787 - 0.000 ) ) * 1600 = 797.3


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
|           55 |       84 | 2024-05-29 | FAVBET Team          | L   | 1.000      | -            | -                | -                | -         |    -8.03 | bl1x1, bluewh1te, gr1ks, sh1geo, VILBy |
|           54 |      128 | 2024-05-28 | ENCE Academy         | W   | 1.000      | 0.143        | 0.012 (0.002)    | -                | 0 (0.000) |    13.36 | bl1x1, bluewh1te, gr1ks, sh1geo, VILBy |
|           53 |      138 | 2024-05-28 | ZEROvariant          | W   | 1.000      | -            | -                | -                | 0 (0.000) |     6.13 | bl1x1, bluewh1te, gr1ks, sh1geo, VILBy |
|           52 |      192 | 2024-05-27 | TOR                  | W   | 1.000      | 0.143        | 0.014 (0.002)    | -                | 0 (0.000) |    15.23 | bl1x1, bluewh1te, gr1ks, sh1geo, VILBy |
|           51 |      198 | 2024-05-27 | Donstu Esports       | W   | 1.000      | -            | -                | -                | 0 (0.000) |     8.96 | bl1x1, bluewh1te, gr1ks, sh1geo, VILBy |
|           50 |      300 | 2024-05-25 | DOSKI                | W   | 1.000      | -            | -                | -                | 0 (0.000) |     3.94 | bl1x1, bluewh1te, gr1ks, sh1geo, VILBy |
|           49 |      365 | 2024-05-24 | polizej              | L   | 1.000      | -            | -                | -                | -         |   -25.50 | bl1x1, bluewh1te, gr1ks, sh1geo, VILBy |
|           48 |      390 | 2024-05-23 | TopTab Club          | W   | 1.000      | -            | -                | -                | 0 (0.000) |     4.57 | bl1x1, bluewh1te, gr1ks, sh1geo, VILBy |
|           47 |      483 | 2024-05-22 | RoundsGG             | W   | 1.000      | 0.372        | -                | 0.251 (0.094)    | 0 (0.000) |     8.18 | bl1x1, bluewh1te, gr1ks, sh1geo, VILBy |
|           46 |      759 | 2024-05-19 | ex-KRC Genk Esports  | W   | 1.000      | -            | -                | -                | 0 (0.000) |    12.25 | bl1x1, bluewh1te, Easy, sh1geo, VILBy  |
|           45 |     1630 | 2024-05-08 | AscendX Esports      | W   | 1.000      | -            | -                | -                | 0 (0.000) |     3.09 | bl1x1, bluewh1te, Easy, sh1geo, VILBy  |
|           44 |     1735 | 2024-05-06 | FAVBET Team          | L   | 1.000      | -            | -                | -                | -         |    -8.70 | bl1x1, bluewh1te, Easy, sh1geo, VILBy  |
|           43 |     1996 | 2024-05-01 | VaselineWorms        | L   | 1.000      | -            | -                | -                | -         |   -21.28 | bl1x1, bluewh1te, Easy, sh1geo, VILBy  |
|           42 |     2105 | 2024-04-29 | Verdant              | L   | 0.997      | -            | -                | -                | -         |   -12.71 | bl1x1, bluewh1te, Easy, sh1geo, VILBy  |
|           41 |     2400 | 2024-04-24 | ADEPTS               | W   | 0.964      | 0.372        | 0.005 (0.002)    | 0.291 (0.104)    | 0 (0.000) |    14.93 | bl1x1, bluewh1te, Easy, sh1geo, VILBy  |
|           40 |     2424 | 2024-04-24 | HyperSpirit          | W   | 0.963      | 0.372        | 0.004 (0.001)    | 0.356 (0.128)    | -         |    14.32 | bl1x1, bluewh1te, Easy, sh1geo, VILBy  |
|           39 |     2470 | 2024-04-23 | DASH                 | W   | 0.956      | 0.372        | -                | 0.385 (0.137)    | -         |    12.58 | bl1x1, bluewh1te, Easy, sh1geo, VILBy  |
|           38 |     2547 | 2024-04-21 | Rhyno Esports        | L   | 0.943      | -            | -                | -                | -         |    -7.01 | bl1x1, bluewh1te, Easy, sh1geo, VILBy  |
|           37 |     2634 | 2024-04-20 | Dynamo Eclot         | W   | 0.937      | 0.333        | 0.097 (0.030)    | 0.940 (0.294)    | -         |    23.71 | bl1x1, bluewh1te, Easy, sh1geo, VILBy  |
|           36 |     2843 | 2024-04-18 | Rhyno Esports        | W   | 0.922      | 0.333        | 0.029 (0.009)    | 0.567 (0.174)    | -         |    22.24 | bl1x1, bluewh1te, Easy, sh1geo, VILBy  |
|           35 |     2986 | 2024-04-16 | ALTERNATE aTTaX      | L   | 0.909      | -            | -                | -                | -         |    -6.89 | bl1x1, bluewh1te, Easy, sh1geo, VILBy  |
|           34 |     3004 | 2024-04-15 | FLuffy Gangsters     | L   | 0.904      | -            | -                | -                | -         |   -18.98 | bl1x1, bluewh1te, Easy, sh1geo, VILBy  |
|           33 |     3023 | 2024-04-15 | Sangal Esports       | L   | 0.903      | -            | -                | -                | -         |    -6.21 | bl1x1, bluewh1te, Easy, sh1geo, VILBy  |
|           32 |     3142 | 2024-04-12 | Zero Tenacity        | L   | 0.883      | -            | -                | -                | -         |    -7.55 | bl1x1, bluewh1te, Easy, sh1geo, VILBy  |
|           31 |     3195 | 2024-04-11 | VP.Prodigy           | L   | 0.876      | -            | -                | -                | -         |   -10.28 | bl1x1, bluewh1te, Easy, sh1geo, VILBy  |
|           30 |     3326 | 2024-04-09 | Lemondogs            | W   | 0.863      | 0.333        | -                | 0.314 (0.090)    | -         |     7.35 | bl1x1, bluewh1te, Easy, sh1geo, VILBy  |
|           29 |     3599 | 2024-04-04 | ENCE                 | L   | 0.829      | -            | -                | -                | -         |    -0.68 | bl1x1, bluewh1te, Easy, sh1geo, VILBy  |
|           28 |     5176 | 2024-03-04 | Nemiga Gaming        | L   | 0.625      | -            | -                | -                | -         |    -1.35 | bl1x1, bluewh1te, Easy, sh1geo, VILBy  |
|           27 |     5303 | 2024-03-02 | Nexus Gaming         | L   | 0.611      | -            | -                | -                | -         |    -6.40 | bl1x1, bluewh1te, Easy, sh1geo, VILBy  |
|           26 |     5438 | 2024-02-29 | ex-K10               | W   | 0.596      | 0.371        | 0.005 (0.001)    | 0.517 (0.115)    | -         |    11.04 | bl1x1, bluewh1te, Easy, sh1geo, VILBy  |
|           25 |     5474 | 2024-02-28 | Nexus Gaming         | L   | 0.590      | -            | -                | -                | -         |    -6.17 | bl1x1, bluewh1te, Easy, sh1geo, VILBy  |
|           24 |     5769 | 2024-02-23 | The Chosen Few       | L   | 0.557      | -            | -                | -                | -         |    -9.09 | bl1x1, bluewh1te, Easy, sh1geo, VILBy  |
|           23 |     5825 | 2024-02-22 | DMS                  | L   | 0.550      | -            | -                | -                | -         |   -10.13 | bl1x1, bluewh1te, Easy, sh1geo, VILBy  |
|           22 |     5857 | 2024-02-21 | Endpoint             | W   | 0.544      | 0.371        | 0.012 (0.002)    | 0.770 (0.156)    | -         |    11.88 | bl1x1, bluewh1te, Easy, sh1geo, VILBy  |
|           21 |     5993 | 2024-02-19 | FORZE Youngsters     | L   | 0.531      | -            | -                | -                | -         |   -10.63 | bl1x1, bluewh1te, Easy, sh1geo, VILBy  |
|           20 |     6002 | 2024-02-19 | Sashi Esport         | L   | 0.531      | -            | -                | -                | -         |    -2.78 | bl1x1, bluewh1te, Easy, sh1geo, VILBy  |
|           19 |     6160 | 2024-02-16 | Entropiq             | W   | 0.510      | -            | -                | -                | -         |     5.55 | bl1x1, bluewh1te, Easy, sh1geo, VILBy  |
|           18 |     6342 | 2024-02-13 | GenOne               | L   | 0.490      | -            | -                | -                | -         |   -12.33 | bl1x1, bluewh1te, Easy, sh1geo, VILBy  |
|           17 |     6521 | 2024-02-08 | ARCRED               | L   | 0.457      | -            | -                | -                | -         |    -7.90 | bl1x1, bluewh1te, Easy, sh1geo, VILBy  |
|           16 |     6625 | 2024-02-05 | Eternal Fire Academy | W   | 0.437      | -            | -                | -                | -         |     4.15 | bl1x1, bluewh1te, Easy, sh1geo, VILBy  |
|           15 |     7673 | 2024-01-19 | Permitta Esports     | L   | 0.322      | -            | -                | -                | -         |    -3.01 | bl1x1, bluewh1te, Easy, sh1geo, VILBy  |
|           14 |     7743 | 2024-01-18 | Zero Tenacity        | W   | 0.315      | 0.333        | 0.147 (0.015)    | 1.000 (0.105)    | -         |     8.14 | bl1x1, bluewh1te, Easy, sh1geo, VILBy  |
|           13 |     7840 | 2024-01-17 | MOUZ NXT             | L   | 0.308      | -            | -                | -                | -         |    -1.46 | bl1x1, bluewh1te, Easy, sh1geo, VILBy  |
|           12 |     7867 | 2024-01-16 | JANO Esports         | L   | 0.305      | -            | -                | -                | -         |    -8.04 | bl1x1, bluewh1te, Easy, sh1geo, VILBy  |
|           11 |     7883 | 2024-01-16 | esmagaB              | W   | 0.305      | -            | -                | -                | -         |     5.44 | bl1x1, bluewh1te, Easy, sh1geo, VILBy  |
|           10 |     7898 | 2024-01-16 | Lemondogs            | W   | 0.304      | -            | -                | -                | -         |     2.38 | bl1x1, bluewh1te, Easy, sh1geo, VILBy  |
|            9 |     7920 | 2024-01-16 | 500                  | W   | 0.304      | -            | -                | -                | -         |     4.49 | bl1x1, bluewh1te, Easy, sh1geo, VILBy  |
|            8 |     7964 | 2024-01-15 | Team Spirit Academy  | W   | 0.296      | -            | -                | -                | -         |     4.01 | bl1x1, bluewh1te, Easy, sh1geo, VILBy  |
|            7 |     8054 | 2024-01-13 | Lazer Cats           | W   | 0.282      | -            | -                | -                | -         |     1.38 | bl1x1, bluewh1te, Easy, sh1geo, VILBy  |
|            6 |     8273 | 2024-01-10 | esmagaB              | L   | 0.265      | -            | -                | -                | -         |    -3.48 | bl1x1, bluewh1te, Easy, sh1geo, VILBy  |
|            5 |     8437 | 2024-01-08 | Dynamo Eclot         | L   | 0.249      | -            | -                | -                | -         |    -1.19 | bl1x1, bluewh1te, Easy, sh1geo, VILBy  |
|            4 |     8490 | 2024-01-04 | Lazer Cats           | W   | 0.222      | -            | -                | -                | -         |     1.07 | bl1x1, bluewh1te, Easy, sh1geo, VILBy  |
|            3 |     8565 | 2023-12-29 | Metizport            | L   | 0.184      | -            | -                | -                | -         |    -1.58 | bl1x1, bluewh1te, Easy, sh1geo, VILBy  |
|            2 |     8569 | 2023-12-28 | The Witchers         | L   | 0.177      | -            | -                | -                | -         |    -3.47 | bl1x1, bluewh1te, Easy, sh1geo, VILBy  |
|            1 |     8574 | 2023-12-27 | Metizport            | W   | 0.170      | 0.371        | 0.088 (0.006)    | -                | -         |     3.89 | bl1x1, bluewh1te, Easy, sh1geo, VILBy  |

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
