### Roster Details<br />
Team Name: Aurora Gaming<br />
Roster: deko, KENSI, Lack1, Norwi, r3salt<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [16](../standings_global.md)<br />
Regional Rank: [13]( ../standings_europe.md)<br />
Final Rank Value:  1466.5<br />
<br />
Final Rank Value (1466.5) = Starting Rank Value (1627.3) + Head To Head Adjustments (-160.8)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 1.000[<sup>1</sup>](#table2)
- Bounty Collected: 0.571[<sup>2</sup>](#table1)
- Opponent Network: 0.275[<sup>2</sup>](#table1)
- LAN Wins: 0.628[<sup>2</sup>](#table1)

The average of these factors is 0.619<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1627.3
- 400 + ( ( 0.619 - 0.000 ) / ( 0.806 - 0.000 ) ) * 1600 = 1627.3


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
|           69 |      326 | 2024-04-28 | MIBR                | L   | 1.000      | -            | -                | -                | -         |   -10.85 | deko, KENSI, Lack1, Norwi, r3salt     |
|           68 |      329 | 2024-04-27 | Rebels Gaming       | W   | 1.000      | 0.500        | 0.121 (0.060)    | 0.376 (0.188)    | 1 (1.000) |     4.75 | deko, KENSI, Lack1, Norwi, r3salt     |
|           67 |      393 | 2024-04-27 | Party Astronauts    | W   | 1.000      | 0.500        | -                | 0.374 (0.187)    | 1 (1.000) |     1.01 | deko, KENSI, Lack1, Norwi, r3salt     |
|           66 |      452 | 2024-04-25 | Apeks               | L   | 1.000      | -            | -                | -                | -         |   -22.78 | deko, KENSI, Lack1, Norwi, r3salt     |
|           65 |      456 | 2024-04-25 | Party Astronauts    | W   | 1.000      | 0.500        | -                | 0.374 (0.187)    | 1 (1.000) |     0.91 | deko, KENSI, Lack1, Norwi, r3salt     |
|           64 |      881 | 2024-04-18 | RUBY                | L   | 1.000      | -            | -                | -                | -         |   -30.02 | deko, KENSI, Lack1, Norwi, r3salt     |
|           63 |      934 | 2024-04-17 | 9INE Academy        | W   | 1.000      | -            | -                | -                | 0 (0.000) |     0.27 | deko, KENSI, Lack1, Norwi, r3salt     |
|           62 |     1069 | 2024-04-14 | OG                  | W   | 1.000      | 0.687        | 0.594 (0.408)    | 0.390 (0.268)    | 0 (0.000) |     9.98 | deko, KENSI, Lack1, Norwi, r3salt     |
|           61 |     1107 | 2024-04-13 | BetBoom Team        | W   | 1.000      | 0.687        | 0.571 (0.392)    | 0.824 (0.566)    | 0 (0.000) |    11.05 | deko, KENSI, Lack1, Norwi, r3salt     |
|           60 |     1135 | 2024-04-12 | AMKAL ESPORTS       | W   | 1.000      | -            | -                | -                | -         |     4.34 | deko, KENSI, Lack1, Norwi, r3salt     |
|           59 |     1166 | 2024-04-11 | BetBoom Team        | W   | 1.000      | 0.143        | 0.571 (0.082)    | -                | -         |    12.02 | deko, KENSI, Lack1, Norwi, r3salt     |
|           58 |     1178 | 2024-04-11 | Apeks               | W   | 1.000      | -            | -                | -                | -         |     8.38 | deko, KENSI, Lack1, Norwi, r3salt     |
|           57 |     1183 | 2024-04-11 | FORZE Esports       | W   | 1.000      | 0.687        | 0.210 (0.144)    | 0.574 (0.394)    | -         |     4.36 | deko, KENSI, Lack1, Norwi, r3salt     |
|           56 |     1216 | 2024-04-10 | PARIVISION          | W   | 1.000      | 0.500        | -                | 0.374 (0.187)    | -         |     1.00 | deko, KENSI, Lack1, Norwi, r3salt     |
|           55 |     1230 | 2024-04-10 | BetBoom Team        | L   | 1.000      | -            | -                | -                | -         |   -18.36 | deko, KENSI, Lack1, Norwi, r3salt     |
|           54 |     1282 | 2024-04-09 | KOI                 | L   | 1.000      | -            | -                | -                | -         |   -28.71 | deko, KENSI, Lack1, Norwi, r3salt     |
|           53 |     1294 | 2024-04-09 | 1win                | W   | 1.000      | -            | -                | -                | -         |     0.40 | deko, KENSI, Lack1, Norwi, r3salt     |
|           52 |     1309 | 2024-04-09 | 9Pandas             | W   | 1.000      | -            | -                | -                | -         |     3.04 | deko, KENSI, Lack1, Norwi, r3salt     |
|           51 |     1319 | 2024-04-08 | Metizport           | W   | 1.000      | -            | -                | -                | -         |     3.43 | deko, KENSI, Lack1, Norwi, r3salt     |
|           50 |     1327 | 2024-04-08 | OG                  | W   | 1.000      | 0.687        | 0.594 (0.408)    | 0.390 (0.268)    | -         |     8.41 | deko, KENSI, Lack1, Norwi, r3salt     |
|           49 |     1342 | 2024-04-08 | 1win                | L   | 1.000      | -            | -                | -                | -         |   -31.19 | deko, KENSI, Lack1, Norwi, r3salt     |
|           48 |     1481 | 2024-04-04 | Ninjas in Pyjamas   | W   | 0.992      | -            | -                | -                | -         |     3.47 | deko, KENSI, Lack1, Norwi, r3salt     |
|           47 |     1531 | 2024-04-03 | Ninjas in Pyjamas   | W   | 0.985      | -            | -                | -                | -         |     3.30 | deko, KENSI, Lack1, Norwi, r3salt     |
|           46 |     1575 | 2024-04-02 | Apeks               | W   | 0.978      | -            | -                | -                | -         |     8.40 | deko, KENSI, Lack1, Norwi, r3salt     |
|           45 |     1582 | 2024-04-02 | Metizport           | W   | 0.977      | -            | -                | -                | -         |     3.10 | deko, KENSI, Lack1, Norwi, r3salt     |
|           44 |     1728 | 2024-03-27 | Metizport           | W   | 0.939      | -            | -                | -                | -         |     3.48 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|           43 |     1736 | 2024-03-27 | AURA (Swedish team) | W   | 0.939      | -            | -                | -                | -         |     0.21 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|           42 |     1748 | 2024-03-27 | DMS                 | W   | 0.938      | -            | -                | -                | -         |     0.37 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|           41 |     1793 | 2024-03-26 | Astralis Talent     | W   | 0.932      | -            | -                | -                | -         |     0.84 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|           40 |     1843 | 2024-03-25 | Rebels Gaming       | W   | 0.925      | 0.500        | 0.121 (0.056)    | -                | -         |     3.14 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|           39 |     1897 | 2024-03-23 | ALTERNATE aTTaX     | W   | 0.912      | 0.500        | -                | 0.723 (0.330)    | -         |     1.10 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|           38 |     2181 | 2024-03-16 | Gods Reign          | W   | 0.864      | 0.435        | 0.174 (0.065)    | 0.479 (0.180)    | 1 (0.864) |     0.74 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|           37 |     2230 | 2024-03-15 | Gods Reign          | W   | 0.856      | 0.435        | 0.174 (0.065)    | -                | 1 (0.856) |     0.68 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|           36 |     2289 | 2024-03-14 | Bad News Kangaroos  | W   | 0.849      | -            | -                | -                | 1 (0.849) |     1.14 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|           35 |     2762 | 2024-03-04 | Young Ninjas        | L   | 0.785      | -            | -                | -                | -         |   -23.66 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|           34 |     2879 | 2024-03-02 | Rebels Gaming       | W   | 0.771      | -            | -                | -                | -         |     2.41 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|           33 |     2912 | 2024-03-01 | FORZE Esports       | W   | 0.765      | -            | -                | -                | -         |     2.15 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|           32 |     2922 | 2024-03-01 | 9Pandas             | W   | 0.764      | -            | -                | -                | -         |     2.85 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|           31 |     2941 | 2024-02-29 | KOI                 | W   | 0.759      | -            | -                | -                | -         |     2.08 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|           30 |     2963 | 2024-02-29 | Team Spirit Academy | W   | 0.758      | -            | -                | -                | -         |     0.58 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|           29 |     2970 | 2024-02-29 | HAVU Gaming         | W   | 0.756      | -            | -                | -                | -         |     0.55 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|           28 |     2996 | 2024-02-28 | FORZE Esports       | L   | 0.751      | -            | -                | -                | -         |   -22.00 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|           27 |     3440 | 2024-02-18 | Monte               | L   | 0.686      | -            | -                | -                | -         |   -14.94 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|           26 |     3458 | 2024-02-18 | B8                  | W   | 0.684      | -            | -                | -                | -         |     0.79 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|           25 |     3493 | 2024-02-17 | Monte               | L   | 0.678      | -            | -                | -                | -         |   -15.55 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|           24 |     4161 | 2024-01-29 | Nemiga Gaming       | L   | 0.553      | -            | -                | -                | -         |   -14.40 | bl1x1, deko, KENSI, Lack1, Norwi      |
|           23 |     4182 | 2024-01-29 | ILIN                | W   | 0.553      | -            | -                | -                | -         |     0.06 | bl1x1, deko, KENSI, Lack1, Norwi      |
|           22 |     4600 | 2024-01-19 | FORZE Esports       | L   | 0.486      | -            | -                | -                | -         |   -15.10 | deko, KENSI, Lack1, Norwi, SELLTER    |
|           21 |     4664 | 2024-01-18 | IKLA                | L   | 0.478      | -            | -                | -                | -         |   -14.94 | deko, KENSI, Lack1, Norwi, SELLTER    |
|           20 |     5651 | 2023-12-13 | BIG                 | L   | 0.238      | -            | -                | -                | -         |    -5.47 | deko, KENSI, Lack1, Norwi, SELLTER    |
|           19 |     5671 | 2023-12-12 | Guild Eagles        | W   | 0.232      | -            | -                | -                | -         |     0.29 | deko, KENSI, Lack1, Norwi, SELLTER    |
|           18 |     5878 | 2023-12-07 | BIG                 | L   | 0.199      | -            | -                | -                | -         |    -4.64 | deko, KENSI, Lack1, Norwi, SELLTER    |
|           17 |     5891 | 2023-12-07 | Guild Eagles        | W   | 0.198      | -            | -                | -                | -         |     0.24 | deko, KENSI, Lack1, Norwi, SELLTER    |
|           16 |     5935 | 2023-12-06 | BIG                 | L   | 0.191      | -            | -                | -                | -         |    -4.52 | deko, KENSI, Lack1, Norwi, SELLTER    |
|           15 |     5989 | 2023-12-05 | G2 Esports          | W   | 0.185      | 0.589        | 0.866 (0.094)    | -                | -         |     4.80 | deko, KENSI, Lack1, Norwi, SELLTER    |
|           14 |     6046 | 2023-12-03 | SAW                 | W   | 0.171      | -            | -                | -                | -         |     1.73 | deko, KENSI, Lack1, Norwi, SELLTER    |
|           13 |     6154 | 2023-12-01 | ALTERNATE aTTaX     | W   | 0.159      | -            | -                | -                | -         |     0.22 | deko, KENSI, Lack1, Norwi, SELLTER    |
|           12 |     6632 | 2023-11-20 | MIBR                | L   | 0.085      | -            | -                | -                | -         |    -1.22 | deko, KENSI, Lack1, Norwi, SELLTER    |
|           11 |     6728 | 2023-11-18 | FURIA Esports       | L   | 0.071      | -            | -                | -                | -         |    -1.00 | deko, KENSI, Lack1, Norwi, SELLTER    |
|           10 |     6761 | 2023-11-17 | Fantazeri           | W   | 0.066      | -            | -                | -                | 1 (0.066) |     0.01 | deko, KENSI, Lack1, Norwi, SELLTER    |
|            9 |     6781 | 2023-11-17 | KOI                 | L   | 0.064      | -            | -                | -                | -         |    -1.95 | deko, KENSI, Lack1, Norwi, SELLTER    |
|            8 |     6805 | 2023-11-16 | FURIA Esports       | L   | 0.059      | -            | -                | -                | -         |    -0.84 | deko, KENSI, Lack1, Norwi, SELLTER    |
|            7 |     6831 | 2023-11-16 | Pompa Team          | W   | 0.058      | -            | -                | -                | -         |     0.00 | deko, KENSI, Lack1, Norwi, SELLTER    |
|            6 |     6872 | 2023-11-15 | IKLA                | W   | 0.052      | -            | -                | -                | -         |     0.01 | deko, KENSI, Lack1, Norwi, SELLTER    |
|            5 |     6934 | 2023-11-14 | ALTERNATE aTTaX     | L   | 0.044      | -            | -                | -                | -         |    -1.32 | deko, KENSI, Lack1, Norwi, SELLTER    |
|            4 |     6980 | 2023-11-13 | Apeks               | W   | 0.038      | -            | -                | -                | -         |     0.27 | deko, KENSI, Lack1, Norwi, SELLTER    |
|            3 |     7062 | 2023-11-11 | Eternal Fire        | W   | 0.024      | -            | -                | -                | -         |     0.56 | deko, KENSI, Lack1, Norwi, SELLTER    |
|            2 |     7180 | 2023-11-08 | Fantazeri           | L   | 0.005      | -            | -                | -                | -         |    -0.16 | deko, KENSI, Lack1, Norwi, SELLTER    |
|            1 |     7203 | 2023-11-08 | 9Pandas             | L   | 0.004      | -            | -                | -                | -         |    -0.11 | easy, KENSI, Lack1, Norwi, SELLTER    |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($158,437.64)
- Divide that value by the 5th highest value among all rosters ($158,437.64)
- The final value (1.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-04-28 |      1.000 | $20,000.00     | $20,000.00      |
| 2024-04-14 |      1.000 | $105,000.00    | $105,000.00     |
| 2024-03-16 |      0.864 | $28,500.00     | $24,611.60      |
| 2023-12-13 |      0.239 | $1,500.00      | $357.88         |
| 2023-12-10 |      0.219 | $2,250.00      | $491.77         |
| 2023-12-07 |      0.199 | $40,000.00     | $7,952.78       |
| 2023-11-09 |      0.012 | $2,000.00      | $23.61          |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
