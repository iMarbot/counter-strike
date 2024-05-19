### Roster Details<br />
Team Name: HOTU<br />
Roster: anttzz, fineshine, lampada, mizu, swiftsteel<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [139](../standings_global.md)<br />
Regional Rank: [96]( ../standings_europe.md)<br />
Final Rank Value:  789.3<br />
<br />
Final Rank Value (789.3) = Starting Rank Value (798.4) + Head To Head Adjustments (-9.1)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.337[<sup>1</sup>](#table2)
- Bounty Collected: 0.317[<sup>2</sup>](#table1)
- Opponent Network: 0.150[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.201<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 798.4
- 400 + ( ( 0.201 - 0.000 ) / ( 0.806 - 0.000 ) ) * 1600 = 798.4


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent               | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                       |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           34 |      142 | 2024-05-02 | Team Spirit Academy    | L   | 1.000      | -            | -                | -                | -         |   -22.60 | anttzz, fineshine, lampada, mizu, swiftsteel |
|           33 |      201 | 2024-05-01 | RoundsGG               | W   | 1.000      | 0.371        | 0.000 (0.000)    | 0.170 (0.063)    | 0 (0.000) |     9.52 | anttzz, fineshine, lampada, mizu, swiftsteel |
|           32 |      305 | 2024-04-28 | Zero Tenacity          | W   | 1.000      | 0.371        | 0.095 (0.035)    | 1.000 (0.371)    | 0 (0.000) |    24.03 | anttzz, fineshine, lampada, mizu, swiftsteel |
|           31 |      475 | 2024-04-25 | LEON Esports           | L   | 1.000      | -            | -                | -                | -         |   -18.91 | anttzz, fineshine, lampada, mizu, swiftsteel |
|           30 |      613 | 2024-04-22 | DASH                   | W   | 1.000      | 0.371        | 0.000 (0.000)    | 0.251 (0.093)    | 0 (0.000) |    12.87 | anttzz, fineshine, lampada, mizu, swiftsteel |
|           29 |      768 | 2024-04-20 | Rhyno Esports          | L   | 1.000      | -            | -                | -                | -         |   -11.97 | anttzz, fineshine, lampada, mizu, swiftsteel |
|           28 |      826 | 2024-04-19 | VP.Prodigy             | W   | 1.000      | 0.333        | 0.029 (0.010)    | 0.762 (0.254)    | 0 (0.000) |    16.54 | anttzz, fineshine, lampada, mizu, swiftsteel |
|           27 |      967 | 2024-04-17 | DMS                    | W   | 1.000      | 0.333        | -                | 0.504 (0.168)    | 0 (0.000) |    15.32 | anttzz, fineshine, lampada, mizu, swiftsteel |
|           26 |     2735 | 2024-03-04 | RUSH B (Russian team)  | L   | 0.786      | -            | -                | -                | -         |   -11.71 | anttzz, casE, mizu, swiftsteel, znxxX        |
|           25 |     2863 | 2024-03-02 | Fnatic                 | L   | 0.772      | -            | -                | -                | -         |    -2.04 | anttzz, casE, mizu, swiftsteel, znxxX        |
|           24 |     2915 | 2024-03-01 | K10                    | L   | 0.765      | -            | -                | -                | -         |    -9.94 | anttzz, casE, mizu, swiftsteel, znxxX        |
|           23 |     2920 | 2024-03-01 | GenOne                 | L   | 0.764      | -            | -                | -                | -         |   -17.57 | anttzz, casE, mizu, swiftsteel, znxxX        |
|           22 |     3258 | 2024-02-22 | GODSENT                | L   | 0.711      | -            | -                | -                | -         |   -11.74 | anttzz, casE, mizu, swiftsteel, znxxX        |
|           21 |     3263 | 2024-02-22 | DMS                    | W   | 0.711      | 0.371        | -                | 0.504 (0.133)    | 0 (0.000) |     6.57 | anttzz, casE, mizu, swiftsteel, znxxX        |
|           20 |     3524 | 2024-02-16 | Eternal Fire Academy   | W   | 0.672      | 0.371        | 0.013 (0.003)    | -                | 0 (0.000) |     7.96 | anttzz, casE, mizu, swiftsteel, znxxX        |
|           19 |     3535 | 2024-02-16 | Rhyno Esports          | W   | 0.671      | 0.371        | 0.047 (0.012)    | 0.446 (0.111)    | 0 (0.000) |    13.98 | anttzz, casE, mizu, swiftsteel, znxxX        |
|           18 |     3577 | 2024-02-15 | Copenhagen Wolves      | W   | 0.665      | 0.371        | -                | 0.417 (0.103)    | 0 (0.000) |     6.22 | anttzz, casE, mizu, swiftsteel, znxxX        |
|           17 |     3629 | 2024-02-14 | The Chosen Few         | L   | 0.658      | -            | -                | -                | -         |    -9.82 | anttzz, casE, mizu, swiftsteel, znxxX        |
|           16 |     3674 | 2024-02-13 | Sashi Esport           | L   | 0.652      | -            | -                | -                | -         |    -3.74 | anttzz, casE, mizu, swiftsteel, znxxX        |
|           15 |     3728 | 2024-02-12 | NOM Esports            | W   | 0.645      | 0.371        | -                | 0.374 (0.090)    | 0 (0.000) |     5.87 | anttzz, casE, mizu, swiftsteel, znxxX        |
|           14 |     3790 | 2024-02-09 | ENTERPRISE esports     | W   | 0.625      | 0.371        | 0.039 (0.009)    | 0.476 (0.110)    | -         |    13.95 | anttzz, casE, mizu, swiftsteel, znxxX        |
|           13 |     3815 | 2024-02-08 | Lajtbitexe             | W   | 0.619      | -            | -                | -                | -         |     4.43 | anttzz, casE, mizu, swiftsteel, znxxX        |
|           12 |     4112 | 2024-01-31 | Lausanne-Sport Esports | L   | 0.565      | -            | -                | -                | -         |    -9.68 | anttzz, casE, mizu, swiftsteel, znxxX        |
|           11 |     4141 | 2024-01-30 | Team Secret            | L   | 0.559      | -            | -                | -                | -         |   -12.34 | anttzz, casE, mizu, swiftsteel, znxxX        |
|           10 |     5850 | 2023-12-08 | VP.Prodigy             | L   | 0.203      | -            | -                | -                | -         |    -3.03 | anttzz, casE, mizu, nitzie, swiftsteel       |
|            9 |     6246 | 2023-11-29 | Aurora Young Blud      | L   | 0.146      | -            | -                | -                | -         |    -2.15 | anttzz, casE, mizu, nitzie, swiftsteel       |
|            8 |     6467 | 2023-11-24 | Inferus eSports        | L   | 0.112      | -            | -                | -                | -         |    -2.97 | anttzz, casE, mizu, nitzie, swiftsteel       |
|            7 |     6479 | 2023-11-24 | DMS                    | W   | 0.111      | -            | -                | -                | -         |     1.05 | anttzz, casE, mizu, nitzie, swiftsteel       |
|            6 |     6491 | 2023-11-24 | Entropiq               | W   | 0.111      | 0.371        | 0.001 (0.000)    | -                | -         |     1.70 | anttzz, casE, mizu, nitzie, swiftsteel       |
|            5 |     6549 | 2023-11-22 | Dripmen                | W   | 0.099      | -            | -                | -                | -         |     0.30 | anttzz, casE, mizu, nitzie, swiftsteel       |
|            4 |     6962 | 2023-11-13 | ARCRED                 | W   | 0.039      | 0.371        | 0.004 (0.000)    | -                | -         |     0.66 | anttzz, casE, mizu, nitzie, swiftsteel       |
|            3 |     7075 | 2023-11-11 | Team QUAZAR            | W   | 0.023      | -            | -                | -                | -         |     0.07 | anttzz, casE, mizu, nitzie, swiftsteel       |
|            2 |     7163 | 2023-11-08 | ALTERNATE aTTaX        | L   | 0.006      | -            | -                | -                | -         |    -0.03 | anttzz, casE, mizu, nitzie, swiftsteel       |
|            1 |     7178 | 2023-11-08 | Turów Zgorzelec Esport | W   | 0.005      | 0.371        | 0.019 (0.000)    | -                | -         |     0.09 | anttzz, casE, mizu, nitzie, swiftsteel       |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($1,706.71)
- Divide that value by the 5th highest value among all rosters ($158,437.64)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-04-21 |      1.000 | $1,250.00      | $1,250.00       |
| 2023-12-09 |      0.210 | $2,170.26      | $456.71         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
