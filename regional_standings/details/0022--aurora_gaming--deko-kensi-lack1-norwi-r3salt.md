### Roster Details<br />
Team Name: Aurora Gaming<br />
Roster: deko, KENSI, Lack1, Norwi, r3salt<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [22](../standings_global.md)<br />
Regional Rank: [15]( ../standings_europe.md)<br />
Final Rank Value:  1359.2<br />
<br />
Final Rank Value (1359.2) = Starting Rank Value (1496.1) + Head To Head Adjustments (-136.9)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.765[<sup>1</sup>](#table2)
- Bounty Collected: 0.487[<sup>2</sup>](#table1)
- Opponent Network: 0.264[<sup>2</sup>](#table1)
- LAN Wins: 0.637[<sup>2</sup>](#table1)

The average of these factors is 0.538<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1496.1
- 400 + ( ( 0.538 - 0.000 ) / ( 0.786 - 0.000 ) ) * 1600 = 1496.1


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent            | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           70 |       92 | 2024-05-29 | The MongolZ         | L   | 1.000      | -            | -                | -                | -         |    -7.26 | deko, KENSI, Lack1, Norwi, r3salt     |
|           69 |      140 | 2024-05-27 | Lynn Vision Gaming  | W   | 1.000      | 0.500        | 0.063 (0.031)    | 0.414 (0.207)    | 1 (1.000) |     4.79 | deko, KENSI, Lack1, Norwi, r3salt     |
|           68 |      614 | 2024-05-21 | Astralis            | L   | 1.000      | -            | -                | -                | -         |    -3.88 | deko, KENSI, Lack1, Norwi, r3salt     |
|           67 |     1012 | 2024-05-17 | SAW                 | W   | 1.000      | 0.769        | 0.112 (0.086)    | 0.388 (0.298)    | 0 (0.000) |    17.45 | deko, KENSI, Lack1, Norwi, r3salt     |
|           66 |     1041 | 2024-05-16 | PARIVISION          | W   | 1.000      | 0.769        | -                | 0.329 (0.253)    | 0 (0.000) |     2.67 | deko, KENSI, Lack1, Norwi, r3salt     |
|           65 |     1067 | 2024-05-16 | MIBR                | L   | 1.000      | -            | -                | -                | -         |    -7.32 | deko, KENSI, Lack1, Norwi, r3salt     |
|           64 |     1103 | 2024-05-16 | SAW                 | L   | 1.000      | -            | -                | -                | -         |   -13.94 | deko, KENSI, Lack1, Norwi, r3salt     |
|           63 |     1199 | 2024-05-15 | Team Spirit         | L   | 1.000      | -            | -                | -                | -         |    -1.32 | deko, KENSI, Lack1, Norwi, r3salt     |
|           62 |     1494 | 2024-05-10 | MOUZ NXT            | L   | 1.000      | -            | -                | -                | -         |   -27.66 | deko, KENSI, Lack1, Norwi, r3salt     |
|           61 |     2132 | 2024-04-28 | MIBR                | L   | 0.988      | -            | -                | -                | -         |    -8.71 | deko, KENSI, Lack1, Norwi, r3salt     |
|           60 |     2135 | 2024-04-27 | Rebels Gaming       | W   | 0.987      | 0.500        | 0.062 (0.031)    | 0.418 (0.206)    | 1 (0.987) |     4.60 | deko, KENSI, Lack1, Norwi, r3salt     |
|           59 |     2219 | 2024-04-26 | Party Astronauts    | W   | 0.981      | 0.500        | -                | 0.545 (0.268)    | 1 (0.981) |     2.68 | deko, KENSI, Lack1, Norwi, r3salt     |
|           58 |     2289 | 2024-04-25 | Apeks               | L   | 0.974      | -            | -                | -                | -         |   -22.54 | deko, KENSI, Lack1, Norwi, r3salt     |
|           57 |     2293 | 2024-04-25 | Party Astronauts    | W   | 0.973      | 0.500        | -                | 0.545 (0.265)    | 1 (0.973) |     2.37 | deko, KENSI, Lack1, Norwi, r3salt     |
|           56 |     2766 | 2024-04-18 | RUBY                | L   | 0.923      | -            | -                | -                | -         |   -27.14 | deko, KENSI, Lack1, Norwi, r3salt     |
|           55 |     2830 | 2024-04-17 | 9INE                | W   | 0.918      | -            | -                | -                | 0 (0.000) |     0.35 | deko, KENSI, Lack1, Norwi, r3salt     |
|           54 |     2981 | 2024-04-14 | OG                  | W   | 0.896      | 0.687        | 0.277 (0.171)    | -                | -         |     7.61 | deko, KENSI, Lack1, Norwi, r3salt     |
|           53 |     3028 | 2024-04-13 | BetBoom Team        | W   | 0.890      | 0.687        | 0.390 (0.238)    | 0.712 (0.435)    | -         |    10.74 | deko, KENSI, Lack1, Norwi, r3salt     |
|           52 |     3071 | 2024-04-12 | AMKAL ESPORTS       | W   | 0.884      | -            | -                | -                | -         |     5.05 | deko, KENSI, Lack1, Norwi, r3salt     |
|           51 |     3108 | 2024-04-11 | BetBoom Team        | W   | 0.877      | 0.143        | 0.390 (0.049)    | -                | -         |    11.47 | deko, KENSI, Lack1, Norwi, r3salt     |
|           50 |     3122 | 2024-04-11 | Apeks               | W   | 0.877      | -            | -                | -                | -         |     6.84 | deko, KENSI, Lack1, Norwi, r3salt     |
|           49 |     3128 | 2024-04-11 | FORZE Esports       | W   | 0.876      | 0.687        | 0.111 (0.067)    | 0.440 (0.265)    | -         |     4.08 | deko, KENSI, Lack1, Norwi, r3salt     |
|           48 |     3167 | 2024-04-10 | PARIVISION          | W   | 0.871      | -            | -                | -                | -         |     1.64 | deko, KENSI, Lack1, Norwi, r3salt     |
|           47 |     3183 | 2024-04-10 | BetBoom Team        | L   | 0.870      | -            | -                | -                | -         |   -15.25 | deko, KENSI, Lack1, Norwi, r3salt     |
|           46 |     3236 | 2024-04-09 | KOI                 | L   | 0.864      | -            | -                | -                | -         |   -24.51 | deko, KENSI, Lack1, Norwi, r3salt     |
|           45 |     3252 | 2024-04-09 | 1win                | W   | 0.863      | -            | -                | -                | -         |     2.13 | deko, KENSI, Lack1, Norwi, r3salt     |
|           44 |     3267 | 2024-04-09 | 9Pandas             | W   | 0.862      | -            | -                | -                | -         |     4.37 | deko, KENSI, Lack1, Norwi, r3salt     |
|           43 |     3278 | 2024-04-08 | Metizport           | W   | 0.858      | -            | -                | -                | -         |     3.72 | deko, KENSI, Lack1, Norwi, r3salt     |
|           42 |     3288 | 2024-04-08 | OG                  | W   | 0.857      | 0.687        | 0.277 (0.163)    | -                | -         |     6.09 | deko, KENSI, Lack1, Norwi, r3salt     |
|           41 |     3303 | 2024-04-08 | 1win                | L   | 0.856      | -            | -                | -                | -         |   -25.18 | deko, KENSI, Lack1, Norwi, r3salt     |
|           40 |     3492 | 2024-04-04 | Ninjas in Pyjamas   | W   | 0.830      | -            | -                | -                | -         |     3.73 | deko, KENSI, Lack1, Norwi, r3salt     |
|           39 |     3549 | 2024-04-03 | Ninjas in Pyjamas   | W   | 0.824      | -            | -                | -                | -         |     3.61 | deko, KENSI, Lack1, Norwi, r3salt     |
|           38 |     3596 | 2024-04-02 | Apeks               | W   | 0.817      | -            | -                | -                | -         |     6.51 | deko, KENSI, Lack1, Norwi, r3salt     |
|           37 |     3605 | 2024-04-02 | Metizport           | W   | 0.816      | -            | -                | -                | -         |     3.00 | deko, KENSI, Lack1, Norwi, r3salt     |
|           36 |     3742 | 2024-03-28 | brazylijski luz     | W   | 0.784      | 0.500        | -                | 0.490 (0.192)    | -         |     0.75 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|           35 |     3780 | 2024-03-27 | Metizport           | W   | 0.778      | -            | -                | -                | -         |     3.23 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|           34 |     3791 | 2024-03-27 | AURA                | W   | 0.778      | -            | -                | -                | -         |     0.46 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|           33 |     3804 | 2024-03-27 | DMS                 | W   | 0.777      | -            | -                | -                | -         |     0.61 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|           32 |     3853 | 2024-03-26 | Astralis Talent     | W   | 0.771      | -            | -                | -                | -         |     1.14 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|           31 |     3917 | 2024-03-25 | Rebels Gaming       | W   | 0.764      | -            | -                | -                | -         |     3.33 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|           30 |     3987 | 2024-03-23 | ALTERNATE aTTaX     | W   | 0.751      | 0.500        | -                | 0.679 (0.255)    | -         |     1.43 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|           29 |     4334 | 2024-03-16 | Gods Reign          | W   | 0.703      | 0.435        | 0.086 (0.026)    | -                | 1 (0.703) |     1.17 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|           28 |     4391 | 2024-03-15 | Gods Reign          | W   | 0.695      | 0.435        | 0.086 (0.026)    | -                | 1 (0.695) |     1.10 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|           27 |     4451 | 2024-03-14 | Bad News Kangaroos  | W   | 0.688      | -            | -                | -                | 1 (0.688) |     1.18 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|           26 |     5043 | 2024-03-04 | Young Ninjas        | L   | 0.624      | -            | -                | -                | -         |   -18.42 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|           25 |     5186 | 2024-03-02 | Rebels Gaming       | W   | 0.610      | -            | -                | -                | -         |     2.56 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|           24 |     5227 | 2024-03-01 | FORZE Esports       | W   | 0.604      | -            | -                | -                | -         |     1.99 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|           23 |     5240 | 2024-03-01 | 9Pandas             | W   | 0.603      | -            | -                | -                | -         |     3.81 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|           22 |     5260 | 2024-02-29 | KOI                 | W   | 0.598      | -            | -                | -                | -         |     1.67 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|           21 |     5283 | 2024-02-29 | Team Spirit Academy | W   | 0.597      | -            | -                | -                | -         |     0.57 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|           20 |     5293 | 2024-02-29 | HAVU Gaming         | W   | 0.595      | -            | -                | -                | -         |     0.44 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|           19 |     5309 | 2024-02-28 | kONO.ECF            | W   | 0.591      | -            | -                | -                | -         |     1.13 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|           18 |     5328 | 2024-02-28 | FORZE Esports       | L   | 0.590      | -            | -                | -                | -         |   -16.98 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|           17 |     5865 | 2024-02-18 | Monte               | L   | 0.525      | -            | -                | -                | -         |   -10.82 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|           16 |     5886 | 2024-02-18 | B8                  | W   | 0.523      | -            | -                | -                | -         |     2.36 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|           15 |     5937 | 2024-02-17 | kONO.ECF            | W   | 0.517      | -            | -                | -                | -         |     0.76 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|           14 |     5943 | 2024-02-17 | Monte               | L   | 0.517      | -            | -                | -                | -         |   -11.08 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|           13 |     5950 | 2024-02-17 | kONO.ECF            | W   | 0.516      | -            | -                | -                | -         |     0.70 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|           12 |     6784 | 2024-01-29 | Nemiga Gaming       | L   | 0.392      | -            | -                | -                | -         |    -9.58 | bl1x1, deko, KENSI, Lack1, Norwi      |
|           11 |     6810 | 2024-01-29 | ILIN                | W   | 0.392      | -            | -                | -                | -         |     0.07 | bl1x1, deko, KENSI, Lack1, Norwi      |
|           10 |     7401 | 2024-01-19 | FORZE Esports       | L   | 0.324      | -            | -                | -                | -         |   -10.09 | deko, KENSI, Lack1, Norwi, SELLTER    |
|            9 |     7461 | 2024-01-18 | ENTERPRISE esports  | L   | 0.318      | -            | -                | -                | -         |    -9.51 | deko, KENSI, Lack1, Norwi, SELLTER    |
|            8 |     7477 | 2024-01-18 | IKLA                | L   | 0.317      | -            | -                | -                | -         |    -9.92 | deko, KENSI, Lack1, Norwi, SELLTER    |
|            7 |     8845 | 2023-12-13 | BIG                 | L   | 0.077      | -            | -                | -                | -         |    -1.42 | deko, KENSI, Lack1, Norwi, SELLTER    |
|            6 |     8881 | 2023-12-12 | ex-Guild Eagles     | W   | 0.071      | -            | -                | -                | -         |     0.11 | deko, KENSI, Lack1, Norwi, SELLTER    |
|            5 |     9156 | 2023-12-07 | BIG                 | L   | 0.038      | -            | -                | -                | -         |    -0.70 | deko, KENSI, Lack1, Norwi, SELLTER    |
|            4 |     9171 | 2023-12-07 | ex-Guild Eagles     | W   | 0.037      | -            | -                | -                | -         |     0.06 | deko, KENSI, Lack1, Norwi, SELLTER    |
|            3 |     9227 | 2023-12-06 | BIG                 | L   | 0.030      | -            | -                | -                | -         |    -0.56 | deko, KENSI, Lack1, Norwi, SELLTER    |
|            2 |     9298 | 2023-12-05 | G2 Esports          | W   | 0.024      | -            | -                | -                | -         |     0.64 | deko, KENSI, Lack1, Norwi, SELLTER    |
|            1 |     9376 | 2023-12-03 | SAW                 | W   | 0.010      | -            | -                | -                | -         |     0.10 | deko, KENSI, Lack1, Norwi, SELLTER    |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($148,016.01)
- Divide that value by the 5th highest value among all rosters ($300,806.11)
- The final value (0.49) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-05-23 |      1.000 | $12,500.00     | $12,500.00      |
| 2024-04-28 |      0.988 | $20,000.00     | $19,762.04      |
| 2024-04-14 |      0.896 | $105,000.00    | $94,106.25      |
| 2024-03-16 |      0.703 | $28,500.00     | $20,021.25      |
| 2023-12-13 |      0.078 | $1,500.00      | $116.28         |
| 2023-12-07 |      0.038 | $40,000.00     | $1,510.19       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
