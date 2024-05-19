### Roster Details<br />
Team Name: Aurora Young Blud<br />
Roster: bl1x1, bluewh1te, gr1ks, sh1geo, VILBy<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [160](../standings_global.md)<br />
Regional Rank: [107]( ../standings_europe.md)<br />
Final Rank Value:  766.5<br />
<br />
Final Rank Value (766.5) = Starting Rank Value (824.8) + Head To Head Adjustments (-58.3)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.362[<sup>1</sup>](#table2)
- Bounty Collected: 0.348[<sup>2</sup>](#table1)
- Opponent Network: 0.147[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.214<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 824.8
- 400 + ( ( 0.214 - 0.000 ) / ( 0.806 - 0.000 ) ) * 1600 = 824.8


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent             | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                  |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           59 |      190 | 2024-05-01 | VaselineWorms        | L   | 1.000      | -            | -                | -                | -         |   -22.58 | bl1x1, bluewh1te, gr1ks, sh1geo, VILBy  |
|           58 |      279 | 2024-04-29 | Verdant              | L   | 1.000      | -            | -                | -                | -         |   -12.32 | bl1x1, bluewh1te, gr1ks, sh1geo, VILBy  |
|           57 |      516 | 2024-04-24 | ADEPTS               | W   | 1.000      | -            | -                | -                | 0 (0.000) |     9.88 | bl1x1, bluewh1te, gr1ks, sh1geo, VILBy  |
|           56 |      537 | 2024-04-24 | HyperSpirit          | W   | 1.000      | 0.371        | 0.009 (0.003)    | 0.293 (0.109)    | 0 (0.000) |    13.48 | bl1x1, bluewh1te, gr1ks, sh1geo, VILBy  |
|           55 |      579 | 2024-04-23 | DASH                 | W   | 1.000      | 0.371        | -                | 0.251 (0.093)    | 0 (0.000) |    13.14 | bl1x1, bluewh1te, gr1ks, sh1geo, VILBy  |
|           54 |      639 | 2024-04-21 | Rhyno Esports        | L   | 1.000      | -            | -                | -                | -         |    -9.88 | bl1x1, bluewh1te, Easy, sh1geo, VILBy   |
|           53 |      714 | 2024-04-20 | Dynamo Eclot         | W   | 1.000      | 0.333        | 0.189 (0.063)    | 0.953 (0.318)    | 0 (0.000) |    25.45 | bl1x1, bluewh1te, Easy, sh1geo, VILBy   |
|           52 |      899 | 2024-04-18 | Rhyno Esports        | W   | 1.000      | 0.333        | 0.047 (0.016)    | 0.446 (0.149)    | 0 (0.000) |    21.12 | bl1x1, bluewh1te, Easy, sh1geo, VILBy   |
|           51 |     1020 | 2024-04-16 | ALTERNATE aTTaX      | L   | 1.000      | -            | -                | -                | -         |    -7.50 | bl1x1, bluewh1te, Easy, sh1geo, VILBy   |
|           50 |     1036 | 2024-04-15 | FLuffy Gangsters     | L   | 1.000      | -            | -                | -                | -         |   -21.09 | bl1x1, bluewh1te, gr1ks, sh1geo, VILBy  |
|           49 |     1052 | 2024-04-15 | Sangal Esports       | L   | 1.000      | -            | -                | -                | -         |   -16.68 | bl1x1, bluewh1te, Easy, sh1geo, VILBy   |
|           48 |     1140 | 2024-04-12 | Zero Tenacity        | L   | 1.000      | -            | -                | -                | -         |   -11.03 | bl1x1, bluewh1te, gr1ks, sh1geo, VILBy  |
|           47 |     1180 | 2024-04-11 | VP.Prodigy           | L   | 1.000      | -            | -                | -                | -         |   -12.64 | bl1x1, bluewh1te, Easy, sh1geo, VILBy   |
|           46 |     1290 | 2024-04-09 | Lemondogs            | W   | 1.000      | 0.333        | -                | 0.252 (0.084)    | 0 (0.000) |     6.63 | bl1x1, bluewh1te, Easy, sh1geo, VILBy   |
|           45 |     1501 | 2024-04-04 | ENCE                 | L   | 0.990      | -            | -                | -                | -         |    -0.62 | bl1x1, bluewh1te, Easy, sh1geo, VILBy   |
|           44 |     2751 | 2024-03-04 | Nemiga Gaming        | L   | 0.786      | -            | -                | -                | -         |    -1.24 | bl1x1, bluewh1te, Easy, sh1geo, VILBy   |
|           43 |     2857 | 2024-03-02 | Nexus Gaming         | L   | 0.772      | -            | -                | -                | -         |    -8.15 | bl1x1, bluewh1te, Easy, sh1geo, VILBy   |
|           42 |     2967 | 2024-02-29 | K10                  | W   | 0.757      | 0.371        | 0.015 (0.004)    | 0.418 (0.118)    | 0 (0.000) |    14.00 | bl1x1, bluewh1te, Easy, sh1geo, VILBy   |
|           41 |     2992 | 2024-02-28 | Nexus Gaming         | L   | 0.751      | -            | -                | -                | -         |    -7.91 | bl1x1, bluewh1te, Easy, sh1geo, VILBy   |
|           40 |     3214 | 2024-02-23 | The Chosen Few       | L   | 0.718      | -            | -                | -                | -         |   -10.79 | bl1x1, bluewh1te, Easy, sh1geo, VILBy   |
|           39 |     3260 | 2024-02-22 | DMS                  | L   | 0.711      | -            | -                | -                | -         |   -15.85 | bl1x1, bluewh1te, Easy, sh1geo, VILBy   |
|           38 |     3290 | 2024-02-21 | Endpoint             | W   | 0.706      | 0.371        | 0.005 (0.001)    | 0.785 (0.206)    | 0 (0.000) |    12.39 | bl1x1, bluewh1te, Easy, sh1geo, VILBy   |
|           37 |     3401 | 2024-02-19 | FORZE Youngsters     | L   | 0.692      | -            | -                | -                | -         |   -14.27 | bl1x1, bluewh1te, Easy, sh1geo, VILBy   |
|           36 |     3409 | 2024-02-19 | Sashi Esport         | L   | 0.692      | -            | -                | -                | -         |    -4.20 | bl1x1, bluewh1te, Easy, sh1geo, VILBy   |
|           35 |     3534 | 2024-02-16 | Entropiq             | W   | 0.671      | 0.371        | -                | 0.436 (0.109)    | 0 (0.000) |     9.83 | bl1x1, bluewh1te, Easy, sh1geo, VILBy   |
|           34 |     3679 | 2024-02-13 | GenOne               | L   | 0.651      | -            | -                | -                | -         |   -16.51 | bl1x1, bluewh1te, Easy, sh1geo, VILBy   |
|           33 |     3824 | 2024-02-08 | ARCRED               | L   | 0.618      | -            | -                | -                | -         |   -10.31 | bl1x1, bluewh1te, Easy, sh1geo, VILBy   |
|           32 |     3899 | 2024-02-05 | Eternal Fire Academy | W   | 0.598      | 0.371        | 0.013 (0.003)    | -                | 0 (0.000) |     6.44 | bl1x1, bluewh1te, Easy, sh1geo, VILBy   |
|           31 |     4618 | 2024-01-19 | Permitta Esports     | L   | 0.483      | -            | -                | -                | -         |    -4.53 | bl1x1, bluewh1te, Easy, sh1geo, VILBy   |
|           30 |     4678 | 2024-01-18 | Zero Tenacity        | W   | 0.476      | 0.333        | 0.095 (0.015)    | 1.000 (0.159)    | -         |     9.66 | bl1x1, bluewh1te, Easy, sh1geo, VILBy   |
|           29 |     4757 | 2024-01-17 | MOUZ NXT             | L   | 0.469      | -            | -                | -                | -         |    -3.01 | bl1x1, bluewh1te, Easy, sh1geo, VILBy   |
|           28 |     4774 | 2024-01-16 | JANO Esports         | L   | 0.467      | -            | -                | -                | -         |    -8.48 | bl1x1, bluewh1te, Easy, sh1geo, VILBy   |
|           27 |     4786 | 2024-01-16 | EsmagaB              | W   | 0.466      | -            | -                | -                | -         |     7.92 | bl1x1, bluewh1te, Easy, sh1geo, VILBy   |
|           26 |     4795 | 2024-01-16 | Lemondogs            | W   | 0.466      | -            | -                | -                | -         |     2.87 | bl1x1, bluewh1te, Easy, sh1geo, VILBy   |
|           25 |     4808 | 2024-01-16 | 500                  | W   | 0.465      | -            | -                | -                | -         |     6.79 | bl1x1, bluewh1te, Easy, sh1geo, VILBy   |
|           24 |     4836 | 2024-01-15 | Team Spirit Academy  | W   | 0.457      | 0.333        | 0.021 (0.003)    | -                | -         |     7.30 | bl1x1, bluewh1te, Easy, sh1geo, VILBy   |
|           23 |     4900 | 2024-01-13 | Lazer Cats           | W   | 0.443      | -            | -                | -                | -         |     2.07 | bl1x1, bluewh1te, Easy, sh1geo, VILBy   |
|           22 |     5055 | 2024-01-10 | EsmagaB              | L   | 0.426      | -            | -                | -                | -         |    -5.88 | bl1x1, bluewh1te, Easy, sh1geo, VILBy   |
|           21 |     5155 | 2024-01-08 | Dynamo Eclot         | L   | 0.410      | -            | -                | -                | -         |    -1.54 | bl1x1, bluewh1te, Easy, sh1geo, VILBy   |
|           20 |     5196 | 2024-01-04 | Lazer Cats           | W   | 0.383      | -            | -                | -                | -         |     1.73 | bl1x1, bluewh1te, Easy, sh1geo, VILBy   |
|           19 |     5249 | 2023-12-29 | Metizport            | L   | 0.345      | -            | -                | -                | -         |    -2.88 | bl1x1, bluewh1te, Easy, sh1geo, VILBy   |
|           18 |     5253 | 2023-12-28 | The Witchers         | L   | 0.338      | -            | -                | -                | -         |    -5.99 | bl1x1, bluewh1te, Easy, sh1geo, VILBy   |
|           17 |     5258 | 2023-12-27 | Metizport            | W   | 0.331      | 0.371        | 0.188 (0.023)    | 1.000 (0.123)    | -         |     7.68 | bl1x1, bluewh1te, Easy, sh1geo, VILBy   |
|           16 |     6246 | 2023-11-29 | HOTU                 | W   | 0.146      | -            | -                | -                | -         |     2.15 | bl1x1, bluewh1te, Easy, sh1geo, VILBy   |
|           15 |     6355 | 2023-11-27 | GODSENT              | W   | 0.132      | 0.371        | 0.026 (0.001)    | -                | -         |     1.97 | bl1x1, bluewh1te, Easy, sh1geo, VILBy   |
|           14 |     6369 | 2023-11-27 | RoundsGG             | L   | 0.132      | -            | -                | -                | -         |    -2.61 | bl1x1, bluewh1te, Easy, sh1geo, VILBy   |
|           13 |     6543 | 2023-11-22 | INGLORIOUS           | L   | 0.099      | -            | -                | -                | -         |    -1.72 | bl1x1, bluewh1te, Easy, malinov, sh1geo |
|           12 |     6558 | 2023-11-22 | MASONIC Academy      | W   | 0.099      | -            | -                | -                | -         |     0.26 | bl1x1, bluewh1te, Easy, malinov, sh1geo |
|           11 |     6582 | 2023-11-21 | Dripmen              | W   | 0.092      | -            | -                | -                | -         |     0.25 | bl1x1, bluewh1te, Easy, malinov, sh1geo |
|           10 |     6588 | 2023-11-21 | SHIPACHI             | W   | 0.092      | -            | -                | -                | -         |     0.35 | bl1x1, bluewh1te, Easy, malinov, sh1geo |
|            9 |     6631 | 2023-11-20 | Grindas              | L   | 0.085      | -            | -                | -                | -         |    -1.79 | bl1x1, bluewh1te, Easy, malinov, sh1geo |
|            8 |     6968 | 2023-11-13 | Gaimin Gladiators    | L   | 0.038      | -            | -                | -                | -         |    -0.03 | bl1x1, bluewh1te, Easy, malinov, sh1geo |
|            7 |     7003 | 2023-11-12 | Entropiq             | L   | 0.032      | -            | -                | -                | -         |    -0.55 | bl1x1, bluewh1te, Easy, malinov, sh1geo |
|            6 |     7046 | 2023-11-11 | ARCRED               | W   | 0.026      | -            | -                | -                | -         |     0.41 | bl1x1, bluewh1te, Easy, malinov, sh1geo |
|            5 |     7066 | 2023-11-11 | Ex-Anonymo Esports   | W   | 0.024      | -            | -                | -                | -         |     0.32 | bl1x1, bluewh1te, Easy, malinov, sh1geo |
|            4 |     7094 | 2023-11-10 | ENCE Academy         | W   | 0.018      | -            | -                | -                | -         |     0.31 | bl1x1, bluewh1te, Easy, malinov, sh1geo |
|            3 |     7103 | 2023-11-10 | Entropiq             | L   | 0.017      | -            | -                | -                | -         |    -0.30 | bl1x1, bluewh1te, Easy, malinov, sh1geo |
|            2 |     7106 | 2023-11-10 | ILIN                 | W   | 0.017      | -            | -                | -                | -         |     0.09 | bl1x1, bluewh1te, Easy, malinov, sh1geo |
|            1 |     7153 | 2023-11-09 | Team Spirit Academy  | W   | 0.009      | -            | -                | -                | -         |     0.14 | bl1x1, bluewh1te, Easy, malinov, sh1geo |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($2,748.03)
- Divide that value by the 5th highest value among all rosters ($158,437.64)
- The final value (0.02) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-04-21 |      1.000 | $2,500.00      | $2,500.00       |
| 2024-01-21 |      0.496 | $500.00        | $248.03         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
