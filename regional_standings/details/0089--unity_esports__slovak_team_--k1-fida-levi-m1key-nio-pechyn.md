### Roster Details<br />
Team Name: UNiTY esports (Slovak team)<br />
Roster: K1-FiDa, Levi, M1key, NIO, Pechyn<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [89](../standings_global.md)<br />
Regional Rank: [66]( ../standings_europe.md)<br />
Final Rank Value:  876.1<br />
<br />
Final Rank Value (876.1) = Starting Rank Value (982.2) + Head To Head Adjustments (-106.1)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.443[<sup>1</sup>](#table2)
- Bounty Collected: 0.383[<sup>2</sup>](#table1)
- Opponent Network: 0.233[<sup>2</sup>](#table1)
- LAN Wins: 0.114[<sup>2</sup>](#table1)

The average of these factors is 0.293<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 982.2
- 400 + ( ( 0.293 - 0.000 ) / ( 0.806 - 0.000 ) ) * 1600 = 982.2


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent                 | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins      | H2H Adj. | Roster                            |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           80 |       36 | 2024-05-05 | Verdant                  | L   | 1.000      | -            | -                | -                | -             |   -16.54 | K1-FiDa, Levi, M1key, NIO, Pechyn |
|           79 |       81 | 2024-05-04 | WOPA Esport              | W   | 1.000      | 0.333        | -                | 0.485 (0.162)    | false (0.000) |    10.04 | K1-FiDa, Levi, M1key, NIO, Pechyn |
|           78 |      121 | 2024-05-03 | NOM Esports              | L   | 1.000      | -            | -                | -                | -             |   -22.43 | K1-FiDa, Levi, M1key, NIO, Pechyn |
|           77 |      292 | 2024-04-29 | Turów Zgorzelec Esport   | W   | 1.000      | 0.333        | 0.019 (0.006)    | 0.640 (0.213)    | false (0.000) |     9.86 | K1-FiDa, Levi, M1key, NIO, Pechyn |
|           76 |      323 | 2024-04-28 | WOPA Esport              | W   | 1.000      | -            | -                | -                | false (0.000) |    10.22 | K1-FiDa, Levi, M1key, NIO, Pechyn |
|           75 |      842 | 2024-04-19 | Rhyno Esports            | L   | 1.000      | -            | -                | -                | -             |   -17.09 | K1-FiDa, Levi, M1key, NIO, Pechyn |
|           74 |      900 | 2024-04-18 | Johnny Speeds            | L   | 1.000      | -            | -                | -                | -             |   -13.89 | K1-FiDa, Levi, M1key, NIO, Pechyn |
|           73 |      949 | 2024-04-17 | Lemondogs                | W   | 1.000      | -            | -                | -                | false (0.000) |     4.14 | K1-FiDa, Levi, M1key, NIO, Pechyn |
|           72 |      981 | 2024-04-17 | Viperio                  | W   | 1.000      | -            | -                | -                | false (0.000) |     9.67 | K1-FiDa, Levi, M1key, NIO, Pechyn |
|           71 |     1008 | 2024-04-16 | DMS                      | W   | 1.000      | 0.333        | -                | 0.504 (0.168)    | false (0.000) |    10.58 | K1-FiDa, Levi, M1key, NIO, Pechyn |
|           70 |     1024 | 2024-04-16 | Lilmix                   | W   | 1.000      | 0.333        | -                | 0.604 (0.201)    | -             |     9.00 | K1-FiDa, Levi, M1key, NIO, Pechyn |
|           69 |     1057 | 2024-04-15 | Verdant                  | W   | 1.000      | 0.333        | 0.027 (0.009)    | 0.662 (0.221)    | -             |    17.18 | K1-FiDa, Levi, M1key, NIO, Pechyn |
|           68 |     1119 | 2024-04-13 | K10                      | W   | 1.000      | -            | -                | -                | -             |    13.71 | K1-FiDa, Levi, M1key, NIO, Pechyn |
|           67 |     1150 | 2024-04-12 | Johnny Speeds            | L   | 1.000      | -            | -                | -                | -             |   -13.34 | K1-FiDa, Levi, M1key, NIO, Pechyn |
|           66 |     1187 | 2024-04-11 | Rhyno Esports            | L   | 1.000      | -            | -                | -                | -             |   -14.72 | K1-FiDa, Levi, M1key, NIO, Pechyn |
|           65 |     1229 | 2024-04-10 | Dynamo Eclot             | L   | 1.000      | -            | -                | -                | -             |   -11.13 | K1-FiDa, Levi, M1key, NIO, Pechyn |
|           64 |     1258 | 2024-04-10 | SINNERS Esports          | L   | 1.000      | -            | -                | -                | -             |    -9.77 | K1-FiDa, Levi, M1key, NIO, Pechyn |
|           63 |     1314 | 2024-04-09 | WOPA Esport              | W   | 1.000      | -            | -                | -                | -             |    10.35 | K1-FiDa, Levi, M1key, NIO, Pechyn |
|           62 |     1427 | 2024-04-06 | Sashi Esport             | L   | 1.000      | -            | -                | -                | -             |    -8.19 | K1-FiDa, Levi, M1key, NIO, Pechyn |
|           61 |     1447 | 2024-04-05 | Astralis Talent          | L   | 0.997      | -            | -                | -                | -             |   -16.71 | K1-FiDa, Levi, M1key, NIO, Pechyn |
|           60 |     1505 | 2024-04-04 | Sashi Esport             | L   | 0.990      | -            | -                | -                | -             |    -9.31 | K1-FiDa, Levi, M1key, NIO, Pechyn |
|           59 |     1590 | 2024-04-02 | Illuminar Gaming         | W   | 0.976      | -            | -                | -                | -             |    13.13 | K1-FiDa, Levi, M1key, NIO, Pechyn |
|           58 |     1605 | 2024-04-01 | WOPA Esport              | W   | 0.970      | -            | -                | -                | -             |     9.03 | K1-FiDa, Levi, M1key, NIO, Pechyn |
|           57 |     1628 | 2024-03-31 | Dynamo Eclot             | W   | 0.962      | 0.333        | 0.189 (0.061)    | 0.953 (0.306)    | -             |    21.91 | K1-FiDa, Levi, M1key, NIO, Pechyn |
|           56 |     1671 | 2024-03-29 | Lilmix                   | W   | 0.950      | 0.333        | -                | 0.604 (0.191)    | -             |     5.33 | K1-FiDa, Levi, M1key, NIO, Pechyn |
|           55 |     1699 | 2024-03-28 | Entropiq                 | W   | 0.944      | -            | -                | -                | -             |    11.47 | K1-FiDa, Levi, M1key, NIO, Pechyn |
|           54 |     1777 | 2024-03-27 | Sashi Esport             | L   | 0.936      | -            | -                | -                | -             |   -17.97 | K1-FiDa, Levi, M1key, NIO, Pechyn |
|           53 |     1850 | 2024-03-25 | Permitta Esports         | W   | 0.923      | 0.333        | 0.063 (0.019)    | 1.000 (0.308)    | -             |    18.95 | K1-FiDa, Levi, M1key, NIO, Pechyn |
|           52 |     1950 | 2024-03-22 | Dynamo Eclot             | W   | 0.904      | 0.333        | 0.189 (0.057)    | 0.953 (0.287)    | -             |    22.40 | K1-FiDa, Levi, M1key, NIO, Pechyn |
|           51 |     1999 | 2024-03-21 | Turów Zgorzelec Esport   | L   | 0.896      | -            | -                | -                | -             |   -16.80 | K1-FiDa, Levi, M1key, NIO, Pechyn |
|           50 |     2144 | 2024-03-17 | SINNERS Esports          | L   | 0.871      | -            | -                | -                | -             |    -8.13 | K1-FiDa, Levi, M1key, NIO, Pechyn |
|           49 |     2172 | 2024-03-16 | Dynamo Eclot             | L   | 0.865      | -            | -                | -                | -             |    -6.82 | K1-FiDa, Levi, M1key, NIO, Pechyn |
|           48 |     2184 | 2024-03-16 | Dynamo Eclot             | W   | 0.863      | 0.333        | 0.189 (0.054)    | 0.953 (0.274)    | -             |    20.88 | K1-FiDa, Levi, M1key, NIO, Pechyn |
|           47 |     2213 | 2024-03-15 | SINNERS Esports          | W   | 0.859      | -            | -                | -                | true (0.859)  |    19.51 | K1-FiDa, Levi, M1key, NIO, Pechyn |
|           46 |     2581 | 2024-03-07 | EP Genesis               | W   | 0.804      | -            | -                | -                | -             |     4.22 | K1-FiDa, Levi, M1key, NIO, Pechyn |
|           45 |     2703 | 2024-03-05 | Team Sampi               | L   | 0.791      | -            | -                | -                | -             |    -8.02 | K1-FiDa, Levi, M1key, NIO, Pechyn |
|           44 |     2734 | 2024-03-04 | Permitta Esports         | L   | 0.786      | -            | -                | -                | -             |    -7.19 | K1-FiDa, Levi, M1key, NIO, Pechyn |
|           43 |     2763 | 2024-03-04 | EP Genesis               | W   | 0.785      | -            | -                | -                | -             |     3.55 | K1-FiDa, Levi, M1key, NIO, Pechyn |
|           42 |     2830 | 2024-03-02 | GODSENT                  | L   | 0.773      | -            | -                | -                | -             |   -13.16 | K1-FiDa, Levi, M1key, NIO, Pechyn |
|           41 |     2843 | 2024-03-02 | Team Space               | W   | 0.772      | -            | -                | -                | -             |     8.49 | K1-FiDa, Levi, M1key, NIO, Pechyn |
|           40 |     2954 | 2024-02-29 | Copenhagen Wolves        | L   | 0.758      | -            | -                | -                | -             |   -18.54 | Levi, luko, M1key, NIO, Pechyn    |
|           39 |     2959 | 2024-02-29 | Team Secret              | W   | 0.758      | -            | -                | -                | -             |     6.70 | Levi, luko, M1key, NIO, Pechyn    |
|           38 |     2987 | 2024-02-28 | 1win                     | L   | 0.752      | -            | -                | -                | -             |   -14.60 | Levi, luko, M1key, NIO, Pechyn    |
|           37 |     2995 | 2024-02-28 | DMS                      | L   | 0.751      | -            | -                | -                | -             |   -17.39 | Levi, luko, M1key, NIO, Pechyn    |
|           36 |     3042 | 2024-02-27 | BLESSED (Ukrainian team) | L   | 0.744      | -            | -                | -                | -             |   -14.81 | Levi, luko, M1key, NIO, Pechyn    |
|           35 |     3219 | 2024-02-23 | Eternal Fire Academy     | W   | 0.718      | -            | -                | -                | -             |     5.98 | Levi, luko, M1key, NIO, Pechyn    |
|           34 |     3309 | 2024-02-21 | Lausanne-Sport Esports   | L   | 0.705      | -            | -                | -                | -             |   -16.29 | Levi, luko, M1key, NIO, Pechyn    |
|           33 |     3355 | 2024-02-20 | Entropiq                 | L   | 0.698      | -            | -                | -                | -             |   -14.14 | Levi, luko, M1key, NIO, Pechyn    |
|           32 |     3415 | 2024-02-19 | GamerLegion Academy      | W   | 0.691      | 0.371        | 0.043 (0.011)    | -                | -             |     7.43 | Levi, luko, M1key, NIO, Pechyn    |
|           31 |     3496 | 2024-02-17 | Rhyno Esports            | W   | 0.678      | 0.371        | 0.047 (0.012)    | -                | -             |    10.31 | Levi, luko, M1key, NIO, Pechyn    |
|           30 |     3771 | 2024-02-10 | Viperio                  | L   | 0.631      | -            | -                | -                | -             |   -15.95 | desty, Levi, M1key, NIO, Pechyn   |
|           29 |     3860 | 2024-02-06 | Endpoint                 | L   | 0.605      | -            | -                | -                | -             |   -11.46 | Levi, luko, M1key, NIO, Pechyn    |
|           28 |     3946 | 2024-02-03 | TBA.ECF                  | L   | 0.585      | -            | -                | -                | -             |   -15.11 | Levi, luko, M1key, NIO, Pechyn    |
|           27 |     3974 | 2024-02-03 | Team Pigeons             | W   | 0.585      | 0.143        | 0.094 (0.008)    | -                | -             |     7.65 | Levi, luko, M1key, NIO, Pechyn    |
|           26 |     3985 | 2024-02-03 | RUR Esports              | W   | 0.584      | -            | -                | -                | -             |     1.42 | Levi, luko, M1key, NIO, Pechyn    |
|           25 |     4037 | 2024-02-02 | Dynamo Eclot             | L   | 0.578      | -            | -                | -                | -             |    -4.37 | Levi, luko, M1key, NIO, Pechyn    |
|           24 |     4116 | 2024-01-31 | ARCRED                   | L   | 0.564      | -            | -                | -                | -             |   -11.86 | Levi, luko, M1key, NIO, Pechyn    |
|           23 |     4318 | 2024-01-26 | 9Pandas                  | L   | 0.531      | -            | -                | -                | -             |    -4.55 | Levi, luko, M1key, NIO, Pechyn    |
|           22 |     4703 | 2024-01-17 | Capcarap                 | L   | 0.473      | -            | -                | -                | -             |   -13.72 | Levi, luko, M1key, NIO, Pechyn    |
|           21 |     4716 | 2024-01-17 | Alliance                 | W   | 0.472      | -            | -                | -                | -             |     5.54 | Levi, luko, M1key, NIO, Pechyn    |
|           20 |     4893 | 2024-01-13 | Gaimin Gladiators        | L   | 0.444      | -            | -                | -                | -             |    -1.13 | Levi, luko, M1key, NIO, Pechyn    |
|           19 |     4925 | 2024-01-12 | BAKS Esports             | W   | 0.439      | -            | -                | -                | -             |     2.11 | Levi, luko, M1key, NIO, Pechyn    |
|           18 |     4932 | 2024-01-12 | MEHED                    | W   | 0.439      | -            | -                | -                | -             |     0.55 | Levi, luko, M1key, NIO, Pechyn    |
|           17 |     5110 | 2024-01-09 | TOOMUCHVIDEOGAMES        | W   | 0.418      | -            | -                | -                | -             |     0.94 | Levi, luko, M1key, NIO, Pechyn    |
|           16 |     5346 | 2023-12-17 | VP.Prodigy               | L   | 0.266      | -            | -                | -                | -             |    -5.67 | Levi, luko, M1key, NIO, Pechyn    |
|           15 |     5449 | 2023-12-16 | Rhyno Esports            | W   | 0.259      | -            | -                | -                | -             |     3.77 | Levi, luko, M1key, NIO, Pechyn    |
|           14 |     5578 | 2023-12-15 | VP.Prodigy               | L   | 0.252      | -            | -                | -                | -             |    -5.51 | Levi, luko, M1key, NIO, Pechyn    |
|           13 |     5692 | 2023-12-11 | Passion UA               | W   | 0.225      | 0.333        | 0.114 (0.009)    | -                | -             |     3.94 | Levi, luko, M1key, NIO, Pechyn    |
|           12 |     5872 | 2023-12-07 | The Dice                 | W   | 0.199      | -            | -                | -                | -             |     0.24 | Levi, luko, M1key, NIO, Pechyn    |
|           11 |     5890 | 2023-12-07 | Turów Zgorzelec Esport   | L   | 0.198      | -            | -                | -                | -             |    -4.38 | Levi, luko, M1key, NIO, Pechyn    |
|           10 |     5969 | 2023-12-05 | BebraFPL1                | W   | 0.186      | -            | -                | -                | -             |     0.42 | Levi, luko, M1key, NIO, Pechyn    |
|            9 |     6442 | 2023-11-25 | SINNERS Esports          | W   | 0.117      | -            | -                | -                | true (0.117)  |     1.92 | Levi, luko, M1key, NIO, Pechyn    |
|            8 |     6475 | 2023-11-24 | Dynamo Eclot             | L   | 0.112      | -            | -                | -                | -             |    -2.96 | Levi, luko, M1key, NIO, Pechyn    |
|            7 |     6709 | 2023-11-18 | XGOD                     | L   | 0.072      | -            | -                | -                | -             |    -2.12 | Levi, luko, M1key, NIO, Pechyn    |
|            6 |     6877 | 2023-11-15 | INGLORIOUS               | L   | 0.052      | -            | -                | -                | -             |    -1.22 | Levi, luko, M1key, NIO, Pechyn    |
|            5 |     6899 | 2023-11-15 | ENCE Academy             | L   | 0.050      | -            | -                | -                | -             |    -1.06 | Levi, luko, M1key, NIO, Pechyn    |
|            4 |     6986 | 2023-11-13 | Pompa Team               | L   | 0.037      | -            | -                | -                | -             |    -1.08 | Levi, luko, M1key, NIO, Pechyn    |
|            3 |     7048 | 2023-11-11 | SINNERS Esports          | W   | 0.026      | -            | -                | -                | true (0.026)  |     0.41 | Levi, luko, M1key, NIO, Pechyn    |
|            2 |     7058 | 2023-11-11 | Team Universe            | W   | 0.025      | -            | -                | -                | true (0.025)  |     0.08 | Levi, luko, M1key, NIO, Pechyn    |
|            1 |     7148 | 2023-11-09 | Sashi Esport             | W   | 0.010      | -            | -                | -                | -             |     0.06 | Levi, luko, M1key, NIO, Pechyn    |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($8,776.03)
- Divide that value by the 5th highest value among all rosters ($158,437.64)
- The final value (0.06) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-04-18 |      1.000 | $3,000.00      | $3,000.00       |
| 2024-04-06 |      1.000 | $3,000.00      | $3,000.00       |
| 2024-03-17 |      0.872 | $1,298.80      | $1,132.24       |
| 2023-12-17 |      0.266 | $2,200.00      | $584.43         |
| 2023-11-25 |      0.118 | $8,969.86      | $1,059.36       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
