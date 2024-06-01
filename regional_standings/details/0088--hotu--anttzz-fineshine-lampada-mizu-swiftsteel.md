### Roster Details<br />
Team Name: HOTU<br />
Roster: anttzz, fineshine, lampada, mizu, swiftsteel<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [88](../standings_global.md)<br />
Regional Rank: [61]( ../standings_europe.md)<br />
Final Rank Value:  894.0<br />
<br />
Final Rank Value (894.0) = Starting Rank Value (852.2) + Head To Head Adjustments (41.8)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.297[<sup>1</sup>](#table2)
- Bounty Collected: 0.349[<sup>2</sup>](#table1)
- Opponent Network: 0.242[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.222<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 852.2
- 400 + ( ( 0.222 - 0.000 ) / ( 0.786 - 0.000 ) ) * 1600 = 852.2


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
|           43 |       70 | 2024-05-29 | VP.Prodigy             | W   | 1.000      | 0.143        | 0.008 (0.001)    | -                | 0 (0.000) |    17.06 | anttzz, fineshine, lampada, mizu, swiftsteel |
|           42 |      338 | 2024-05-24 | Raptors Esports Club   | W   | 1.000      | 0.372        | 0.007 (0.003)    | 0.406 (0.151)    | 0 (0.000) |    13.11 | anttzz, fineshine, lampada, mizu, swiftsteel |
|           41 |      468 | 2024-05-22 | Verdant                | W   | 1.000      | 0.372        | 0.014 (0.005)    | 1.000 (0.372)    | 0 (0.000) |    18.52 | anttzz, fineshine, lampada, mizu, swiftsteel |
|           40 |      699 | 2024-05-20 | HyperSpirit            | W   | 1.000      | 0.372        | 0.004 (0.001)    | 0.356 (0.133)    | 0 (0.000) |    12.64 | anttzz, fineshine, lampada, mizu, swiftsteel |
|           39 |     1148 | 2024-05-15 | kONO.ECF               | W   | 1.000      | 0.372        | 0.013 (0.005)    | 0.778 (0.290)    | 0 (0.000) |    19.07 | anttzz, fineshine, lampada, mizu, swiftsteel |
|           38 |     1168 | 2024-05-15 | ARCRED                 | L   | 1.000      | -            | -                | -                | -         |   -12.51 | anttzz, fineshine, lampada, mizu, swiftsteel |
|           37 |     1238 | 2024-05-14 | LF0                    | W   | 1.000      | -            | -                | -                | 0 (0.000) |     2.46 | anttzz, fineshine, lampada, mizu, swiftsteel |
|           36 |     1258 | 2024-05-14 | V1dar Gaming           | L   | 1.000      | -            | -                | -                | -         |   -17.85 | anttzz, fineshine, lampada, mizu, swiftsteel |
|           35 |     1271 | 2024-05-14 | WAKIZASHI              | W   | 1.000      | -            | -                | -                | 0 (0.000) |     2.45 | anttzz, fineshine, lampada, mizu, swiftsteel |
|           34 |     1618 | 2024-05-08 | Passion UA             | L   | 1.000      | -            | -                | -                | -         |   -11.81 | anttzz, fineshine, lampada, mizu, swiftsteel |
|           33 |     1631 | 2024-05-08 | EXO Clan               | L   | 1.000      | -            | -                | -                | -         |   -12.85 | anttzz, fineshine, lampada, mizu, swiftsteel |
|           32 |     1681 | 2024-05-07 | MOUZ NXT               | W   | 1.000      | 0.372        | 0.157 (0.058)    | 0.950 (0.353)    | 0 (0.000) |    23.22 | anttzz, fineshine, lampada, mizu, swiftsteel |
|           31 |     1916 | 2024-05-02 | Team Spirit Academy    | L   | 1.000      | -            | -                | -                | -         |   -21.86 | anttzz, fineshine, lampada, mizu, swiftsteel |
|           30 |     1981 | 2024-05-01 | RoundsGG               | W   | 1.000      | -            | -                | -                | 0 (0.000) |     5.56 | anttzz, fineshine, lampada, mizu, swiftsteel |
|           29 |     2101 | 2024-04-28 | Zero Tenacity          | W   | 0.990      | 0.372        | 0.147 (0.054)    | 1.000 (0.369)    | 0 (0.000) |    23.05 | anttzz, fineshine, lampada, mizu, swiftsteel |
|           28 |     2314 | 2024-04-25 | LEON Esports           | L   | 0.970      | -            | -                | -                | -         |   -20.07 | anttzz, fineshine, lampada, mizu, swiftsteel |
|           27 |     2460 | 2024-04-22 | DASH                   | W   | 0.950      | -            | -                | -                | -         |     9.51 | anttzz, fineshine, lampada, mizu, swiftsteel |
|           26 |     2639 | 2024-04-20 | Rhyno Esports          | L   | 0.935      | -            | -                | -                | -         |   -11.10 | anttzz, fineshine, lampada, mizu, swiftsteel |
|           25 |     2706 | 2024-04-19 | VP.Prodigy             | W   | 0.930      | 0.333        | 0.008 (0.002)    | 0.752 (0.233)    | -         |    12.72 | anttzz, fineshine, lampada, mizu, swiftsteel |
|           24 |     2868 | 2024-04-17 | DMS                    | W   | 0.915      | 0.333        | -                | 0.751 (0.229)    | -         |    13.77 | anttzz, fineshine, lampada, mizu, swiftsteel |
|           23 |     3336 | 2024-04-07 | Lazer Cats             | W   | 0.850      | -            | -                | -                | -         |     9.61 | anttzz, fineshine, lampada, mizu, swiftsteel |
|           22 |     3339 | 2024-04-07 | esmagaB                | W   | 0.850      | -            | -                | -                | -         |    13.14 | anttzz, fineshine, lampada, mizu, swiftsteel |
|           21 |     3349 | 2024-04-07 | M1X                    | W   | 0.849      | -            | -                | -                | -         |     2.50 | anttzz, fineshine, lampada, mizu, swiftsteel |
|           20 |     3371 | 2024-04-06 | DMS                    | L   | 0.844      | -            | -                | -                | -         |   -13.60 | anttzz, fineshine, lampada, mizu, swiftsteel |
|           19 |     3391 | 2024-04-06 | The Agency Clan        | W   | 0.843      | -            | -                | -                | -         |     4.91 | anttzz, fineshine, lampada, mizu, swiftsteel |
|           18 |     3402 | 2024-04-06 | 5x404                  | W   | 0.842      | -            | -                | -                | -         |     3.76 | anttzz, fineshine, lampada, mizu, swiftsteel |
|           17 |     5003 | 2024-03-04 | RUSH B                 | L   | 0.625      | -            | -                | -                | -         |   -10.92 | anttzz, casE, mizu, swiftsteel, znxxX        |
|           16 |     5164 | 2024-03-02 | Fnatic                 | L   | 0.611      | -            | -                | -                | -         |    -3.25 | anttzz, casE, mizu, swiftsteel, znxxX        |
|           15 |     5232 | 2024-03-01 | ex-K10                 | L   | 0.604      | -            | -                | -                | -         |    -9.77 | anttzz, casE, mizu, swiftsteel, znxxX        |
|           14 |     5238 | 2024-03-01 | GenOne                 | L   | 0.603      | -            | -                | -                | -         |   -15.39 | anttzz, casE, mizu, swiftsteel, znxxX        |
|           13 |     5662 | 2024-02-22 | AURA                   | L   | 0.550      | -            | -                | -                | -         |   -13.43 | anttzz, casE, mizu, swiftsteel, znxxX        |
|           12 |     5667 | 2024-02-22 | DMS                    | W   | 0.549      | 0.371        | -                | 0.751 (0.153)    | -         |     5.46 | anttzz, casE, mizu, swiftsteel, znxxX        |
|           11 |     5976 | 2024-02-16 | Eternal Fire Academy   | W   | 0.511      | -            | -                | -                | -         |     4.04 | anttzz, casE, mizu, swiftsteel, znxxX        |
|           10 |     5988 | 2024-02-16 | Rhyno Esports          | W   | 0.510      | 0.371        | 0.029 (0.005)    | -                | -         |    11.19 | anttzz, casE, mizu, swiftsteel, znxxX        |
|            9 |     6035 | 2024-02-15 | Copenhagen Wolves      | W   | 0.504      | -            | -                | -                | -         |     3.68 | anttzz, casE, mizu, swiftsteel, znxxX        |
|            8 |     6101 | 2024-02-14 | The Chosen Few         | L   | 0.497      | -            | -                | -                | -         |    -9.18 | anttzz, casE, mizu, swiftsteel, znxxX        |
|            7 |     6152 | 2024-02-13 | Sashi Esport           | L   | 0.491      | -            | -                | -                | -         |    -3.46 | anttzz, casE, mizu, swiftsteel, znxxX        |
|            6 |     6210 | 2024-02-12 | NOM Esports            | W   | 0.484      | -            | -                | -                | -         |     3.33 | anttzz, casE, mizu, swiftsteel, znxxX        |
|            5 |     6295 | 2024-02-09 | ENTERPRISE esports     | W   | 0.464      | 0.371        | 0.010 (0.002)    | 0.809 (0.139)    | -         |     9.68 | anttzz, casE, mizu, swiftsteel, znxxX        |
|            4 |     6324 | 2024-02-08 | lajtbitexe             | W   | 0.458      | -            | -                | -                | -         |     3.12 | anttzz, casE, mizu, swiftsteel, znxxX        |
|            3 |     6721 | 2024-01-31 | Lausanne-Sport Esports | L   | 0.404      | -            | -                | -                | -         |    -8.16 | anttzz, casE, mizu, swiftsteel, znxxX        |
|            2 |     6755 | 2024-01-30 | Team Secret            | L   | 0.398      | -            | -                | -                | -         |    -9.84 | anttzz, casE, mizu, swiftsteel, znxxX        |
|            1 |     9121 | 2023-12-08 | VP.Prodigy             | L   | 0.042      | -            | -                | -                | -         |    -0.70 | anttzz, casE, mizu, nitzie, swiftsteel       |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($1,286.32)
- Divide that value by the 5th highest value among all rosters ($300,806.11)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-04-21 |      0.943 | $1,250.00      | $1,179.17       |
| 2023-12-09 |      0.049 | $2,170.26      | $107.16         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
