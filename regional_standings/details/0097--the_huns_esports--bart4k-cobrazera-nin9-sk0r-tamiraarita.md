### Roster Details<br />
Team Name: The Huns Esports<br />
Roster: Bart4k, cobrazera, nin9, sk0R, Tamiraarita<br />
Region: [Asia]( ../standings_asia.md)<br />
<br />
Global Rank: [97](../standings_global.md)<br />
Regional Rank: [10]( ../standings_asia.md)<br />
Final Rank Value:  866.2<br />
<br />
Final Rank Value (866.2) = Starting Rank Value (920.3) + Head To Head Adjustments (-54.2)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.271[<sup>1</sup>](#table2)
- Bounty Collected: 0.271[<sup>2</sup>](#table1)
- Opponent Network: 0.028[<sup>2</sup>](#table1)
- LAN Wins: 0.480[<sup>2</sup>](#table1)

The average of these factors is 0.262<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 920.3
- 400 + ( ( 0.262 - 0.000 ) / ( 0.806 - 0.000 ) ) * 1600 = 920.3


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent                    | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins      | H2H Adj. | Roster                                     |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           47 |      126 | 2024-05-03 | IHC Esports                 | L   | 1.000      | -            | -                | -                | -             |   -18.61 | Bart4k, cobrazera, nin9, sk0R, Tamiraarita |
|           46 |      158 | 2024-05-02 | Eruption 2024               | W   | 1.000      | -            | -                | -                | true (1.000)  |     2.78 | Bart4k, cobrazera, nin9, sk0R, Tamiraarita |
|           45 |      165 | 2024-05-02 | FAD3D Gaming                | W   | 1.000      | -            | -                | -                | true (1.000)  |     1.86 | Bart4k, cobrazera, nin9, sk0R, Tamiraarita |
|           44 |      961 | 2024-04-17 | TYLOO                       | L   | 1.000      | -            | -                | -                | -             |   -10.21 | Bart4k, cobrazera, H4wK, ncl, nin9         |
|           43 |     1340 | 2024-04-08 | IHC Esports                 | L   | 1.000      | -            | -                | -                | -             |   -18.29 | Bart4k, cobrazera, H4wK, nin9, sk0R        |
|           42 |     1378 | 2024-04-07 | The QUBE Esports            | W   | 1.000      | -            | -                | -                | true (1.000)  |     2.29 | Bart4k, cobrazera, H4wK, nin9, sk0R        |
|           41 |     1380 | 2024-04-06 | ATOX Esports                | L   | 1.000      | -            | -                | -                | -             |    -8.47 | Bart4k, cobrazera, H4wK, nin9, sk0R        |
|           40 |     1445 | 2024-04-05 | KnowHow                     | W   | 0.997      | -            | -                | -                | true (0.997)  |     1.67 | Bart4k, cobrazera, H4wK, nin9, sk0R        |
|           39 |     2067 | 2024-03-19 | TyPuCTbl                    | W   | 0.884      | 0.250        | -                | 0.140 (0.031)    | false (0.000) |     5.26 | Bart4k, ncl, nin9, sk0R, Tsogoo            |
|           38 |     2225 | 2024-03-15 | Team NKT                    | W   | 0.857      | 0.250        | 0.016 (0.003)    | 0.259 (0.056)    | false (0.000) |     9.55 | Bart4k, ncl, nin9, sk0R, Tsogoo            |
|           37 |     2340 | 2024-03-13 | LYG Gaming                  | L   | 0.843      | -            | -                | -                | -             |   -18.73 | Bart4k, ncl, nin9, sk0R, tsogoo            |
|           36 |     2379 | 2024-03-12 | KalekiXer                   | W   | 0.837      | -            | -                | -                | false (0.000) |     1.38 | Bart4k, ncl, nin9, sk0R, tsogoo            |
|           35 |     2641 | 2024-03-06 | Gotham Mafia                | W   | 0.797      | -            | -                | -                | false (0.000) |     1.33 | Bart4k, ncl, nin9, sk0R, Tsogoo            |
|           34 |     3605 | 2024-02-15 | GR Gaming                   | L   | 0.663      | -            | -                | -                | -             |   -12.57 | Bart4k, nin9, sk0R, Tsogoo, yAmi           |
|           33 |     3641 | 2024-02-14 | TyPuCTbl                    | W   | 0.657      | 0.143        | -                | 0.140 (0.013)    | -             |     3.33 | Bart4k, nin9, sk0R, Tsogoo, yAmi           |
|           32 |     3644 | 2024-02-14 | The QUBE Esports            | W   | 0.657      | 0.143        | 0.004 (0.000)    | 0.168 (0.016)    | -             |     7.31 | Bart4k, nin9, sk0R, Tsogoo, yAmi           |
|           31 |     4291 | 2024-01-27 | TYLOO                       | L   | 0.536      | -            | -                | -                | -             |    -5.19 | Bart4k, nin9, sk0R, tsogoo, yAmi           |
|           30 |     4333 | 2024-01-26 | Wings Up Gaming             | W   | 0.531      | 0.143        | 0.018 (0.001)    | 0.172 (0.013)    | -             |     5.21 | Bart4k, nin9, sk0R, tsogoo, yAmi           |
|           29 |     4339 | 2024-01-26 | The MongolZ                 | L   | 0.530      | -            | -                | -                | -             |    -0.29 | Bart4k, nin9, sk0R, tsogoo, yAmi           |
|           28 |     4369 | 2024-01-24 | Team NKT                    | L   | 0.522      | -            | -                | -                | -             |   -11.39 | Bart4k, nin9, sk0R, tsogoo, yAmi           |
|           27 |     4370 | 2024-01-24 | Aravt                       | W   | 0.522      | -            | -                | -                | -             |     2.05 | Bart4k, nin9, sk0R, tsogoo, yAmi           |
|           26 |     4437 | 2024-01-23 | Steel Helmet                | W   | 0.510      | 0.143        | 0.025 (0.002)    | -                | -             |     4.06 | Bart4k, nin9, sk0R, tsogoo, yAmi           |
|           25 |     4440 | 2024-01-23 | ATOX Esports                | W   | 0.510      | 0.143        | 0.112 (0.008)    | 0.769 (0.056)    | -             |    11.65 | Bart4k, nin9, sk0R, tsogoo, yAmi           |
|           24 |     4479 | 2024-01-22 | Wings Up Gaming             | W   | 0.504      | 0.143        | 0.018 (0.001)    | -                | -             |     4.66 | Bart4k, nin9, sk0R, tsogoo, yAmi           |
|           23 |     4488 | 2024-01-22 | Secret (Chinese team)       | W   | 0.504      | -            | -                | -                | -             |     0.91 | Bart4k, nin9, sk0R, tsogoo, yAmi           |
|           22 |     4509 | 2024-01-21 | ATOX Esports                | L   | 0.497      | -            | -                | -                | -             |    -4.25 | Bart4k, nin9, sk0R, tsogoo, yAmi           |
|           21 |     4513 | 2024-01-21 | Aravt                       | W   | 0.496      | -            | -                | -                | -             |     2.02 | Bart4k, nin9, sk0R, tsogoo, yAmi           |
|           20 |     4561 | 2024-01-20 | GR Gaming                   | W   | 0.490      | 0.143        | 0.006 (0.000)    | 0.495 (0.035)    | -             |     5.88 | Bart4k, nin9, sk0R, tsogoo, yAmi           |
|           19 |     4572 | 2024-01-20 | Team NKT                    | W   | 0.489      | 0.143        | 0.016 (0.001)    | 0.259 (0.018)    | -             |     5.15 | Bart4k, nin9, sk0R, tsogoo, yAmi           |
|           18 |     4616 | 2024-01-19 | MungYu Esports              | L   | 0.483      | -            | -                | -                | -             |   -13.44 | Bart4k, nin9, sk0R, tsogoo, yAmi           |
|           17 |     4832 | 2024-01-15 | MungYu Esports              | L   | 0.457      | -            | -                | -                | -             |   -12.94 | Bart4k, nin9, sk0R, tsogoo, yAmi           |
|           16 |     4834 | 2024-01-15 | Fort Arena                  | W   | 0.457      | -            | -                | -                | -             |     1.28 | Bart4k, nin9, sk0R, tsogoo, yAmi           |
|           15 |     4839 | 2024-01-15 | Team NKT                    | W   | 0.456      | 0.143        | 0.016 (0.001)    | 0.259 (0.017)    | -             |     4.50 | Bart4k, nin9, sk0R, tsogoo, yAmi           |
|           14 |     4844 | 2024-01-15 | LYG Gaming                  | W   | 0.456      | 0.143        | -                | 0.380 (0.025)    | -             |     4.74 | Bart4k, nin9, sk0R, tsogoo, yAmi           |
|           13 |     5242 | 2024-01-01 | Wings Up Gaming             | L   | 0.369      | -            | -                | -                | -             |    -8.79 | Bart4k, nin9, sk0R, Tsogoo, yAmi           |
|           12 |     6136 | 2023-12-02 | ATOX Esports                | L   | 0.163      | -            | -                | -                | -             |    -1.38 | Bart4k, ncl, nin9, sk0R, yAmi              |
|           11 |     6172 | 2023-12-01 | Aravt                       | W   | 0.156      | -            | -                | -                | true (0.156)  |     0.55 | Bart4k, ncl, nin9, sk0R, yAmi              |
|           10 |     6175 | 2023-11-30 | ATOX Esports                | L   | 0.155      | -            | -                | -                | -             |    -1.32 | Bart4k, ncl, nin9, sk0R, yAmi              |
|            9 |     6230 | 2023-11-29 | Aravt                       | W   | 0.149      | -            | -                | -                | true (0.149)  |     0.52 | Bart4k, ncl, nin9, sk0R, yAmi              |
|            8 |     6284 | 2023-11-28 | Old School (Mongolian team) | W   | 0.142      | -            | -                | -                | -             |     0.41 | Bart4k, ncl, nin9, sk0R, yAmi              |
|            7 |     6285 | 2023-11-28 | New Genes                   | W   | 0.142      | -            | -                | -                | -             |     0.23 | Bart4k, ncl, nin9, sk0R, yAmi              |
|            6 |     6409 | 2023-11-26 | The MongolZ                 | L   | 0.123      | -            | -                | -                | -             |    -0.06 | Bart4k, nin9, sk0R, Tsogoo, yAmi           |
|            5 |     6452 | 2023-11-25 | Aravt                       | W   | 0.116      | -            | -                | -                | -             |     0.40 | Bart4k, nin9, sk0R, Tsogoo, yAmi           |
|            4 |     6456 | 2023-11-24 | The MongolZ                 | L   | 0.115      | -            | -                | -                | -             |    -0.06 | Bart4k, nin9, sk0R, Tsogoo, yAmi           |
|            3 |     6841 | 2023-11-16 | NewHappy                    | L   | 0.057      | -            | -                | -                | -             |    -1.32 | Bart4k, nin9, sk0R, Tsogoo, yAmi           |
|            2 |     6846 | 2023-11-16 | Lynn Vision Gaming          | W   | 0.056      | 0.143        | 0.155 (0.001)    | -                | -             |     1.57 | Bart4k, nin9, sk0R, Tsogoo, yAmi           |
|            1 |     6894 | 2023-11-15 | GR Gaming                   | W   | 0.050      | -            | -                | -                | -             |     0.56 | Bart4k, nin9, sk0R, Tsogoo, yAmi           |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($324.27)
- Divide that value by the 5th highest value among all rosters ($158,437.64)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-03-19 |      0.884 | $100.00        | $88.37          |
| 2023-12-02 |      0.163 | $1,448.41      | $235.90         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
