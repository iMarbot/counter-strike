### Roster Details<br />
Team Name: BESTIA<br />
Roster: luchov, meyern, naz, Noktse, tomaszin<br />
Region: [Americas]( ../standings_americas.md)<br />
<br />
Global Rank: [136](../standings_global.md)<br />
Regional Rank: [25]( ../standings_americas.md)<br />
Final Rank Value:  792.2<br />
<br />
Final Rank Value (792.2) = Starting Rank Value (812.0) + Head To Head Adjustments (-19.8)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.387[<sup>1</sup>](#table2)
- Bounty Collected: 0.362[<sup>2</sup>](#table1)
- Opponent Network: 0.082[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.208<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 812.0
- 400 + ( ( 0.208 - 0.000 ) / ( 0.806 - 0.000 ) ) * 1600 = 812.0


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent                  | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                 |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           49 |       90 | 2024-05-03 | KRÜ Esports               | L   | 1.000      | -            | -                | -                | -         |   -17.93 | luchov, meyern, naz, Noktse, tomaszin  |
|           48 |      132 | 2024-05-02 | KRÜ Esports               | W   | 1.000      | 0.143        | 0.006 (0.001)    | -                | 0 (0.000) |    13.05 | luchov, meyern, naz, Noktse, tomaszin  |
|           47 |      136 | 2024-05-02 | RJT                       | W   | 1.000      | -            | -                | -                | 0 (0.000) |     5.29 | luchov, meyern, naz, Noktse, tomaszin  |
|           46 |      167 | 2024-05-01 | W7m esports               | W   | 1.000      | -            | -                | -                | 0 (0.000) |     8.45 | luchov, meyern, naz, Noktse, tomaszin  |
|           45 |      171 | 2024-05-01 | InSanitY Sports           | W   | 1.000      | -            | -                | -                | 0 (0.000) |     3.30 | luchov, meyern, naz, Noktse, tomaszin  |
|           44 |      458 | 2024-04-25 | RED Canids                | L   | 1.000      | -            | -                | -                | -         |    -6.45 | luchov, meyern, naz, Noktse, tomaszin  |
|           43 |      459 | 2024-04-25 | RED Canids                | L   | 1.000      | -            | -                | -                | -         |    -6.84 | luchov, meyern, naz, Noktse, tomaszin  |
|           42 |      990 | 2024-04-16 | O Plano                   | L   | 1.000      | -            | -                | -                | -         |   -26.05 | luchov, meyern, naz, Noktse, tomaszin  |
|           41 |     1173 | 2024-04-11 | Galorys                   | L   | 1.000      | -            | -                | -                | -         |   -13.74 | luchov, meyern, naz, Noktse, tomaszin  |
|           40 |     1271 | 2024-04-09 | Galorys                   | L   | 1.000      | -            | -                | -                | -         |   -14.94 | luchov, meyern, naz, Noktse, tomaszin  |
|           39 |     1273 | 2024-04-09 | Galorys                   | W   | 1.000      | 0.450        | 0.048 (0.022)    | 0.598 (0.269)    | 0 (0.000) |    16.64 | luchov, meyern, naz, Noktse, tomaszin  |
|           38 |     1317 | 2024-04-08 | RED Canids                | L   | 1.000      | -            | -                | -                | -         |    -8.52 | luchov, meyern, naz, Noktse, tomaszin  |
|           37 |     1368 | 2024-04-07 | Sharks Esports            | L   | 1.000      | -            | -                | -                | -         |   -11.39 | luchov, meyern, naz, Noktse, tomaszin  |
|           36 |     1385 | 2024-04-06 | Fluxo                     | W   | 1.000      | 0.143        | 0.153 (0.022)    | 0.484 (0.069)    | 0 (0.000) |    23.59 | luchov, meyern, naz, Noktse, tomaszin  |
|           35 |     1463 | 2024-04-04 | AdalYamigos               | L   | 0.994      | -            | -                | -                | -         |   -16.19 | luchov, meyern, naz, Noktse, tomaszin  |
|           34 |     1469 | 2024-04-04 | AdalYamigos               | W   | 0.993      | 0.450        | -                | 0.174 (0.078)    | 0 (0.000) |    15.06 | luchov, meyern, naz, Noktse, tomaszin  |
|           33 |     1477 | 2024-04-04 | Imperial Esports          | L   | 0.992      | -            | -                | -                | -         |    -0.66 | luchov, meyern, naz, Noktse, tomaszin  |
|           32 |     1523 | 2024-04-03 | Fluxo                     | L   | 0.986      | -            | -                | -                | -         |    -8.23 | luchov, meyern, naz, Noktse, tomaszin  |
|           31 |     1565 | 2024-04-02 | Sharks Esports            | W   | 0.980      | 0.143        | 0.063 (0.009)    | 0.343 (0.048)    | 0 (0.000) |    19.67 | luchov, meyern, naz, Noktse, tomaszin  |
|           30 |     1570 | 2024-04-02 | Fluxo                     | L   | 0.979      | -            | -                | -                | -         |    -8.01 | luchov, meyern, naz, Noktse, tomaszin  |
|           29 |     1723 | 2024-03-27 | W7m esports               | L   | 0.940      | -            | -                | -                | -         |   -22.92 | luchov, meyern, naz, Noktse, tomaszin  |
|           28 |     1724 | 2024-03-27 | W7m esports               | W   | 0.940      | 0.450        | -                | 0.127 (0.054)    | 0 (0.000) |     6.29 | luchov, meyern, naz, Noktse, tomaszin  |
|           27 |     2393 | 2024-03-11 | FURIA Academy             | W   | 0.833      | 0.435        | -                | 0.189 (0.069)    | 0 (0.000) |     4.74 | deco, luchov, meyern, Noktse, tomaszin |
|           26 |     2523 | 2024-03-08 | FURIA Academy             | W   | 0.813      | 0.435        | -                | 0.189 (0.067)    | -         |     4.66 | deco, luchov, meyern, Noktse, tomaszin |
|           25 |     2869 | 2024-03-02 | Wildcard Gaming           | L   | 0.772      | -            | -                | -                | -         |    -9.70 | deco, luchov, meyern, Noktse, tomaszin |
|           24 |     2904 | 2024-03-01 | Team Liquid               | L   | 0.766      | -            | -                | -                | -         |    -1.12 | deco, luchov, meyern, Noktse, tomaszin |
|           23 |     3152 | 2024-02-24 | Imperial Esports          | L   | 0.725      | -            | -                | -                | -         |    -0.51 | deco, luchov, meyern, Noktse, tomaszin |
|           22 |     3204 | 2024-02-23 | 9z Team                   | L   | 0.719      | -            | -                | -                | -         |    -6.87 | deco, luchov, meyern, Noktse, tomaszin |
|           21 |     3229 | 2024-02-22 | Imperial Esports          | W   | 0.713      | 0.143        | 0.674 (0.069)    | 0.549 (0.056)    | -         |    22.03 | deco, luchov, meyern, Noktse, tomaszin |
|           20 |     3238 | 2024-02-22 | 9z Team                   | L   | 0.712      | -            | -                | -                | -         |    -6.56 | deco, luchov, meyern, Noktse, tomaszin |
|           19 |     3444 | 2024-02-18 | FURIA Academy             | W   | 0.685      | 0.435        | -                | 0.189 (0.056)    | -         |     4.04 | deco, luchov, meyern, Noktse, tomaszin |
|           18 |     3518 | 2024-02-16 | Case Esports              | L   | 0.673      | -            | -                | -                | -         |   -10.31 | deco, luchov, meyern, Noktse, tomaszin |
|           17 |     3707 | 2024-02-12 | FURIA Academy             | W   | 0.647      | 0.435        | -                | 0.189 (0.053)    | -         |     3.54 | deco, luchov, meyern, Noktse, tomaszin |
|           16 |     4004 | 2024-02-02 | Imperial Esports          | L   | 0.581      | -            | -                | -                | -         |    -0.36 | deco, luchov, meyern, Noktse, tomaszin |
|           15 |     4005 | 2024-02-02 | ODDIK                     | W   | 0.580      | 0.143        | 0.015 (0.001)    | -                | -         |    11.29 | deco, luchov, meyern, Noktse, tomaszin |
|           14 |     4008 | 2024-02-02 | Imperial Esports          | L   | 0.580      | -            | -                | -                | -         |    -0.31 | deco, luchov, meyern, Noktse, tomaszin |
|           13 |     4422 | 2024-01-23 | Imperial Esports          | L   | 0.513      | -            | -                | -                | -         |    -0.25 | deco, luchov, meyern, Noktse, tomaszin |
|           12 |     4449 | 2024-01-22 | Arena Jogue Fácil Esports | W   | 0.507      | 0.143        | 0.002 (0.000)    | -                | -         |     4.91 | deco, luchov, meyern, Noktse, tomaszin |
|           11 |     4533 | 2024-01-20 | MIBR                      | L   | 0.492      | -            | -                | -                | -         |    -0.16 | deco, luchov, meyern, Noktse, tomaszin |
|           10 |     4588 | 2024-01-19 | Imperial Esports          | W   | 0.487      | 0.143        | 0.674 (0.047)    | -                | -         |    15.13 | deco, luchov, meyern, Noktse, tomaszin |
|            9 |     4592 | 2024-01-19 | Flamengo Esports          | W   | 0.486      | -            | -                | -                | -         |     3.22 | deco, luchov, meyern, Noktse, tomaszin |
|            8 |     4828 | 2024-01-15 | TIMACETA                  | L   | 0.460      | -            | -                | -                | -         |    -9.84 | deco, luchov, meyern, Noktse, tomaszin |
|            7 |     4864 | 2024-01-14 | Sharks Esports            | L   | 0.453      | -            | -                | -                | -         |    -5.64 | deco, luchov, meyern, Noktse, tomaszin |
|            6 |     4880 | 2024-01-13 | Intense Game              | W   | 0.447      | 0.143        | 0.008 (0.001)    | -                | -         |     4.92 | deco, luchov, meyern, Noktse, tomaszin |
|            5 |     6290 | 2023-11-28 | LOS                       | W   | 0.140      | -            | -                | -                | -         |     0.69 | deco, luchov, meyern, Noktse, tomaszin |
|            4 |     6294 | 2023-11-28 | Maycam Evolve             | W   | 0.140      | -            | -                | -                | -         |     0.39 | deco, luchov, meyern, Noktse, tomaszin |
|            3 |     6414 | 2023-11-25 | Fluxo                     | L   | 0.120      | -            | -                | -                | -         |    -0.85 | deco, luchov, meyern, Noktse, tomaszin |
|            2 |     6458 | 2023-11-24 | 9z Team                   | W   | 0.114      | 0.143        | 0.057 (0.001)    | -                | -         |     2.37 | deco, luchov, meyern, Noktse, tomaszin |
|            1 |     6499 | 2023-11-23 | Case Esports              | W   | 0.106      | -            | -                | -                | -         |     1.22 | deco, luchov, meyern, Noktse, tomaszin |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($4,142.03)
- Divide that value by the 5th highest value among all rosters ($158,437.64)
- The final value (0.03) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-02-25 |      0.732 | $5,000.00      | $3,662.27       |
| 2023-11-26 |      0.125 | $3,824.65      | $479.76         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
