### Roster Details<br />
Team Name: Aurora Gaming<br />
Roster: deko, KENSI, Lack1, Norwi, r3salt<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [22](../standings_global.md)<br />
Regional Rank: [15]( ../standings_europe.md)<br />
Final Rank Value:  1341.9<br />
<br />
Final Rank Value (1341.9) = Starting Rank Value (1485.1) + Head To Head Adjustments (-143.2)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.765[<sup>1</sup>](#table2)
- Bounty Collected: 0.487[<sup>2</sup>](#table1)
- Opponent Network: 0.247[<sup>2</sup>](#table1)
- LAN Wins: 0.637[<sup>2</sup>](#table1)

The average of these factors is 0.534<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1485.1
- 400 + ( ( 0.534 - 0.000 ) / ( 0.787 - 0.000 ) ) * 1600 = 1485.1


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
|           68 |       99 | 2024-05-29 | The MongolZ         | L   | 1.000      | -            | -                | -                | -         |    -6.70 | deko, KENSI, Lack1, Norwi, r3salt     |
|           67 |      147 | 2024-05-27 | Lynn Vision Gaming  | W   | 1.000      | 0.500        | 0.063 (0.031)    | 0.431 (0.216)    | 1 (1.000) |     5.19 | deko, KENSI, Lack1, Norwi, r3salt     |
|           66 |      625 | 2024-05-21 | Astralis            | L   | 1.000      | -            | -                | -                | -         |    -3.61 | deko, KENSI, Lack1, Norwi, r3salt     |
|           65 |     1024 | 2024-05-17 | SAW                 | W   | 1.000      | 0.769        | 0.112 (0.086)    | 0.388 (0.298)    | 0 (0.000) |    18.23 | deko, KENSI, Lack1, Norwi, r3salt     |
|           64 |     1053 | 2024-05-16 | PARIVISION          | W   | 1.000      | 0.769        | -                | 0.329 (0.253)    | 0 (0.000) |     2.95 | deko, KENSI, Lack1, Norwi, r3salt     |
|           63 |     1077 | 2024-05-16 | MIBR                | L   | 1.000      | -            | -                | -                | -         |    -6.78 | deko, KENSI, Lack1, Norwi, r3salt     |
|           62 |     1113 | 2024-05-16 | SAW                 | L   | 1.000      | -            | -                | -                | -         |   -13.05 | deko, KENSI, Lack1, Norwi, r3salt     |
|           61 |     1209 | 2024-05-15 | Team Spirit         | L   | 1.000      | -            | -                | -                | -         |    -1.20 | deko, KENSI, Lack1, Norwi, r3salt     |
|           60 |     1507 | 2024-05-10 | MOUZ NXT            | L   | 1.000      | -            | -                | -                | -         |   -27.15 | deko, KENSI, Lack1, Norwi, r3salt     |
|           59 |     2167 | 2024-04-28 | MIBR                | L   | 0.988      | -            | -                | -                | -         |    -8.02 | deko, KENSI, Lack1, Norwi, r3salt     |
|           58 |     2170 | 2024-04-27 | Rebels Gaming       | W   | 0.987      | 0.500        | 0.062 (0.031)    | 0.411 (0.203)    | 1 (0.987) |     5.31 | deko, KENSI, Lack1, Norwi, r3salt     |
|           57 |     2255 | 2024-04-26 | Party Astronauts    | W   | 0.981      | 0.500        | -                | 0.545 (0.268)    | 1 (0.981) |     3.01 | deko, KENSI, Lack1, Norwi, r3salt     |
|           56 |     2326 | 2024-04-25 | Apeks               | L   | 0.974      | -            | -                | -                | -         |   -21.82 | deko, KENSI, Lack1, Norwi, r3salt     |
|           55 |     2330 | 2024-04-25 | Party Astronauts    | W   | 0.973      | 0.500        | -                | 0.545 (0.265)    | 1 (0.973) |     2.69 | deko, KENSI, Lack1, Norwi, r3salt     |
|           54 |     2822 | 2024-04-18 | RUBY                | L   | 0.923      | -            | -                | -                | -         |   -26.85 | deko, KENSI, Lack1, Norwi, r3salt     |
|           53 |     2887 | 2024-04-17 | 9INE                | W   | 0.918      | -            | -                | -                | 0 (0.000) |     0.40 | deko, KENSI, Lack1, Norwi, r3salt     |
|           52 |     3046 | 2024-04-14 | OG                  | W   | 0.896      | 0.687        | 0.277 (0.171)    | 0.257 (0.158)    | -         |     8.34 | deko, KENSI, Lack1, Norwi, r3salt     |
|           51 |     3094 | 2024-04-13 | BetBoom Team        | W   | 0.890      | 0.687        | 0.390 (0.238)    | 0.712 (0.435)    | -         |    11.69 | deko, KENSI, Lack1, Norwi, r3salt     |
|           50 |     3137 | 2024-04-12 | AMKAL ESPORTS       | W   | 0.884      | -            | -                | -                | -         |     5.75 | deko, KENSI, Lack1, Norwi, r3salt     |
|           49 |     3174 | 2024-04-11 | BetBoom Team        | W   | 0.877      | 0.143        | 0.390 (0.049)    | -                | -         |    12.53 | deko, KENSI, Lack1, Norwi, r3salt     |
|           48 |     3190 | 2024-04-11 | Apeks               | W   | 0.877      | -            | -                | -                | -         |     7.62 | deko, KENSI, Lack1, Norwi, r3salt     |
|           47 |     3198 | 2024-04-11 | FORZE Esports       | W   | 0.876      | 0.687        | 0.101 (0.061)    | 0.372 (0.224)    | -         |     4.79 | deko, KENSI, Lack1, Norwi, r3salt     |
|           46 |     3240 | 2024-04-10 | PARIVISION          | W   | 0.871      | -            | -                | -                | -         |     1.85 | deko, KENSI, Lack1, Norwi, r3salt     |
|           45 |     3257 | 2024-04-10 | BetBoom Team        | L   | 0.870      | -            | -                | -                | -         |   -14.03 | deko, KENSI, Lack1, Norwi, r3salt     |
|           44 |     3315 | 2024-04-09 | KOI                 | L   | 0.864      | -            | -                | -                | -         |   -23.99 | deko, KENSI, Lack1, Norwi, r3salt     |
|           43 |     3331 | 2024-04-09 | 1win                | W   | 0.863      | -            | -                | -                | -         |     2.37 | deko, KENSI, Lack1, Norwi, r3salt     |
|           42 |     3346 | 2024-04-09 | 9Pandas             | W   | 0.862      | -            | -                | -                | -         |     5.38 | deko, KENSI, Lack1, Norwi, r3salt     |
|           41 |     3358 | 2024-04-08 | Metizport           | W   | 0.858      | -            | -                | -                | -         |     4.18 | deko, KENSI, Lack1, Norwi, r3salt     |
|           40 |     3369 | 2024-04-08 | OG                  | W   | 0.857      | 0.687        | 0.277 (0.163)    | 0.257 (0.151)    | -         |     6.99 | deko, KENSI, Lack1, Norwi, r3salt     |
|           39 |     3384 | 2024-04-08 | 1win                | L   | 0.856      | -            | -                | -                | -         |   -24.96 | deko, KENSI, Lack1, Norwi, r3salt     |
|           38 |     3578 | 2024-04-04 | Ninjas in Pyjamas   | W   | 0.830      | -            | -                | -                | -         |     4.41 | deko, KENSI, Lack1, Norwi, r3salt     |
|           37 |     3636 | 2024-04-03 | Ninjas in Pyjamas   | W   | 0.824      | -            | -                | -                | -         |     4.31 | deko, KENSI, Lack1, Norwi, r3salt     |
|           36 |     3685 | 2024-04-02 | Apeks               | W   | 0.817      | -            | -                | -                | -         |     7.48 | deko, KENSI, Lack1, Norwi, r3salt     |
|           35 |     3695 | 2024-04-02 | Metizport           | W   | 0.816      | -            | -                | -                | -         |     3.40 | deko, KENSI, Lack1, Norwi, r3salt     |
|           34 |     3714 | 2024-04-01 | SINNERS Esports     | L   | 0.811      | -            | -                | -                | -         |   -22.98 | deko, KENSI, L3rich, Lack1, Norwi     |
|           33 |     3873 | 2024-03-27 | Metizport           | W   | 0.778      | -            | -                | -                | -         |     3.26 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|           32 |     3884 | 2024-03-27 | AURA                | W   | 0.778      | -            | -                | -                | -         |     0.51 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|           31 |     3897 | 2024-03-27 | DMS                 | W   | 0.777      | -            | -                | -                | -         |     0.70 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|           30 |     3950 | 2024-03-26 | Astralis Talent     | W   | 0.771      | -            | -                | -                | -         |     1.25 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|           29 |     4440 | 2024-03-16 | Gods Reign          | W   | 0.703      | 0.435        | 0.086 (0.026)    | -                | 1 (0.703) |     1.08 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|           28 |     4501 | 2024-03-15 | Gods Reign          | W   | 0.695      | 0.435        | 0.086 (0.026)    | -                | 1 (0.695) |     1.01 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|           27 |     4565 | 2024-03-14 | Bad News Kangaroos  | W   | 0.688      | -            | -                | -                | 1 (0.688) |     1.23 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|           26 |     5189 | 2024-03-04 | Young Ninjas        | L   | 0.624      | -            | -                | -                | -         |   -18.37 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|           25 |     5334 | 2024-03-02 | Rebels Gaming       | W   | 0.610      | -            | -                | -                | -         |     2.75 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|           24 |     5376 | 2024-03-01 | FORZE Esports       | W   | 0.604      | -            | -                | -                | -         |     1.97 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|           23 |     5389 | 2024-03-01 | 9Pandas             | W   | 0.603      | -            | -                | -                | -         |     4.13 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|           22 |     5409 | 2024-02-29 | KOI                 | W   | 0.598      | -            | -                | -                | -         |     1.80 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|           21 |     5433 | 2024-02-29 | Team Spirit Academy | W   | 0.597      | -            | -                | -                | -         |     0.62 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|           20 |     5443 | 2024-02-29 | HAVU Gaming         | W   | 0.595      | -            | -                | -                | -         |     0.47 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|           19 |     5460 | 2024-02-28 | kONO.ECF            | W   | 0.591      | -            | -                | -                | -         |     1.33 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|           18 |     5479 | 2024-02-28 | FORZE Esports       | L   | 0.590      | -            | -                | -                | -         |   -16.99 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|           17 |     6037 | 2024-02-18 | Monte               | L   | 0.525      | -            | -                | -                | -         |   -10.51 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|           16 |     6059 | 2024-02-18 | B8                  | W   | 0.523      | -            | -                | -                | -         |     2.50 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|           15 |     6110 | 2024-02-17 | kONO.ECF            | W   | 0.517      | -            | -                | -                | -         |     0.90 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|           14 |     6116 | 2024-02-17 | Monte               | L   | 0.517      | -            | -                | -                | -         |   -10.78 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|           13 |     6123 | 2024-02-17 | kONO.ECF            | W   | 0.516      | -            | -                | -                | -         |     0.84 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|           12 |     7000 | 2024-01-29 | Nemiga Gaming       | L   | 0.392      | -            | -                | -                | -         |    -9.56 | bl1x1, deko, KENSI, Lack1, Norwi      |
|           11 |     7026 | 2024-01-29 | ILIN                | W   | 0.392      | -            | -                | -                | -         |     0.08 | bl1x1, deko, KENSI, Lack1, Norwi      |
|           10 |     7645 | 2024-01-19 | FORZE Esports       | L   | 0.324      | -            | -                | -                | -         |   -10.05 | deko, KENSI, Lack1, Norwi, SELLTER    |
|            9 |     7709 | 2024-01-18 | ENTERPRISE esports  | L   | 0.318      | -            | -                | -                | -         |    -9.43 | deko, KENSI, Lack1, Norwi, SELLTER    |
|            8 |     7726 | 2024-01-18 | IKLA                | L   | 0.317      | -            | -                | -                | -         |    -9.91 | deko, KENSI, Lack1, Norwi, SELLTER    |
|            7 |     9109 | 2023-12-13 | BIG                 | L   | 0.077      | -            | -                | -                | -         |    -1.42 | deko, KENSI, Lack1, Norwi, SELLTER    |
|            6 |     9145 | 2023-12-12 | ex-Guild Eagles     | W   | 0.071      | -            | -                | -                | -         |     0.11 | deko, KENSI, Lack1, Norwi, SELLTER    |
|            5 |     9429 | 2023-12-07 | BIG                 | L   | 0.038      | -            | -                | -                | -         |    -0.70 | deko, KENSI, Lack1, Norwi, SELLTER    |
|            4 |     9444 | 2023-12-07 | ex-Guild Eagles     | W   | 0.037      | -            | -                | -                | -         |     0.06 | deko, KENSI, Lack1, Norwi, SELLTER    |
|            3 |     9508 | 2023-12-06 | BIG                 | L   | 0.030      | -            | -                | -                | -         |    -0.57 | deko, KENSI, Lack1, Norwi, SELLTER    |
|            2 |     9580 | 2023-12-05 | G2 Esports          | W   | 0.024      | -            | -                | -                | -         |     0.64 | deko, KENSI, Lack1, Norwi, SELLTER    |
|            1 |     9658 | 2023-12-03 | SAW                 | W   | 0.010      | -            | -                | -                | -         |     0.10 | deko, KENSI, Lack1, Norwi, SELLTER    |

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
