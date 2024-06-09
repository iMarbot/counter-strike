### Roster Details<br />
Team Name: 1win<br />
Roster: buster, Jyo, lattykk, neaLaN, Ryujin<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [51](../standings_global.md)<br />
Regional Rank: [36]( ../standings_europe.md)<br />
Final Rank Value:  1049.0<br />
<br />
Final Rank Value (1049.0) = Starting Rank Value (981.6) + Head To Head Adjustments (67.4)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.435[<sup>1</sup>](#table2)
- Bounty Collected: 0.407[<sup>2</sup>](#table1)
- Opponent Network: 0.302[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.286<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 981.6
- 400 + ( ( 0.286 - 0.000 ) / ( 0.787 - 0.000 ) ) * 1600 = 981.6


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent            | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                    |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           64 |      232 | 2024-05-26 | 9Pandas             | L   | 1.000      | -            | -                | -                | -         |   -12.84 | buster, Jyo, lattykk, neaLaN, Ryujin      |
|           63 |      298 | 2024-05-25 | FURIA Esports       | W   | 1.000      | 0.435        | 0.138 (0.060)    | -                | 0 (0.000) |    26.24 | buster, Jyo, lattykk, neaLaN, Ryujin      |
|           62 |      401 | 2024-05-23 | ECSTATIC            | W   | 1.000      | -            | -                | -                | 0 (0.000) |     0.86 | buster, Jyo, lattykk, neaLaN, Ryujin      |
|           61 |      414 | 2024-05-23 | ENTERPRISE esports  | W   | 1.000      | 0.372        | -                | 0.898 (0.334)    | 0 (0.000) |     9.58 | buster, Jyo, lattykk, neaLaN, Ryujin      |
|           60 |      458 | 2024-05-22 | Zero Tenacity       | L   | 1.000      | -            | -                | -                | -         |   -13.95 | buster, Jyo, lattykk, neaLaN, Ryujin      |
|           59 |      503 | 2024-05-22 | CYBERSHOKE Esports  | W   | 1.000      | 0.372        | -                | 0.468 (0.174)    | 0 (0.000) |     5.43 | buster, Jyo, lattykk, neaLaN, Ryujin      |
|           58 |      512 | 2024-05-22 | Team Spirit Academy | W   | 1.000      | -            | -                | -                | 0 (0.000) |     7.10 | buster, Jyo, lattykk, neaLaN, Ryujin      |
|           57 |      610 | 2024-05-21 | Endpoint            | L   | 1.000      | -            | -                | -                | -         |   -23.38 | buster, Jyo, lattykk, neaLaN, Ryujin      |
|           56 |      987 | 2024-05-17 | Pera Esports        | W   | 1.000      | -            | -                | -                | 0 (0.000) |    11.22 | buster, Jyo, lattykk, neaLaN, Ryujin      |
|           55 |      990 | 2024-05-17 | ENTERPRISE esports  | W   | 1.000      | -            | -                | -                | 0 (0.000) |    11.46 | buster, Jyo, lattykk, neaLaN, Ryujin      |
|           54 |      995 | 2024-05-17 | KOMNATA             | W   | 1.000      | -            | -                | -                | 0 (0.000) |     0.99 | buster, Jyo, lattykk, neaLaN, Ryujin      |
|           53 |     1006 | 2024-05-17 | Entropiq            | W   | 1.000      | -            | -                | -                | 0 (0.000) |     4.89 | buster, Jyo, lattykk, neaLaN, Ryujin      |
|           52 |     1022 | 2024-05-17 | GUN5 Esports        | W   | 1.000      | -            | -                | -                | 0 (0.000) |     6.26 | buster, Jyo, lattykk, neaLaN, Ryujin      |
|           51 |     1109 | 2024-05-16 | Zero Tenacity       | W   | 1.000      | 0.435        | 0.147 (0.064)    | 1.000 (0.435)    | -         |    17.06 | buster, Jyo, lattykk, neaLaN, Ryujin      |
|           50 |     1149 | 2024-05-15 | Rustec              | L   | 1.000      | -            | -                | -                | -         |   -22.34 | buster, Jyo, lattykk, neaLaN, Ryujin      |
|           49 |     1328 | 2024-05-13 | Permitta Esports    | W   | 1.000      | 0.435        | 0.025 (0.011)    | 1.000 (0.435)    | -         |    10.51 | buster, Jyo, lattykk, neaLaN, Ryujin      |
|           48 |     1338 | 2024-05-13 | Entropiq            | W   | 1.000      | -            | -                | -                | -         |     4.05 | buster, Jyo, lattykk, neaLaN, Ryujin      |
|           47 |     1390 | 2024-05-12 | brazylijski luz     | L   | 1.000      | -            | -                | -                | -         |   -21.95 | buster, Jyo, lattykk, neaLaN, Ryujin      |
|           46 |     1459 | 2024-05-11 | FAVBET Team         | L   | 1.000      | -            | -                | -                | -         |   -19.73 | buster, Jyo, lattykk, neaLaN, Ryujin      |
|           45 |     1467 | 2024-05-11 | Token Gaming        | W   | 1.000      | -            | -                | -                | -         |     0.82 | buster, Jyo, lattykk, neaLaN, Ryujin      |
|           44 |     1524 | 2024-05-10 | HyperSpirit         | L   | 1.000      | -            | -                | -                | -         |   -26.33 | buster, Jyo, lattykk, neaLaN, Ryujin      |
|           43 |     1542 | 2024-05-10 | B8                  | W   | 1.000      | 0.143        | 0.168 (0.024)    | -                | -         |    16.46 | buster, Jyo, lattykk, neaLaN, Ryujin      |
|           42 |     1593 | 2024-05-09 | Sashi Esport        | L   | 1.000      | -            | -                | -                | -         |    -8.13 | buster, Jyo, lattykk, neaLaN, Ryujin      |
|           41 |     1636 | 2024-05-08 | EXO Clan            | W   | 1.000      | 0.372        | -                | 0.579 (0.216)    | -         |    10.64 | buster, Jyo, lattykk, neaLaN, Ryujin      |
|           40 |     1670 | 2024-05-08 | Nemiga Gaming       | W   | 1.000      | 0.143        | 0.358 (0.051)    | -                | -         |    21.87 | buster, Jyo, lattykk, neaLaN, Ryujin      |
|           39 |     1695 | 2024-05-07 | BLEED Esports       | W   | 1.000      | 0.143        | 0.248 (0.035)    | -                | -         |    23.13 | buster, Jyo, lattykk, neaLaN, Ryujin      |
|           38 |     1805 | 2024-05-05 | ex-Guild Eagles     | W   | 1.000      | -            | -                | -                | -         |    13.50 | buster, Jyo, lattykk, neaLaN, Ryujin      |
|           37 |     1835 | 2024-05-04 | NOM Esports         | W   | 1.000      | -            | -                | -                | -         |     5.57 | buster, Jyo, lattykk, neaLaN, Ryujin      |
|           36 |     1942 | 2024-05-02 | Soda Gaming         | W   | 1.000      | -            | -                | -                | -         |     3.75 | buster, Jyo, lattykk, neaLaN, Ryujin      |
|           35 |     1985 | 2024-05-01 | V1dar Gaming        | W   | 1.000      | 0.372        | -                | 0.595 (0.221)    | -         |     6.03 | buster, Jyo, lattykk, neaLaN, Ryujin      |
|           34 |     2098 | 2024-04-29 | Passion UA          | W   | 0.997      | 0.372        | 0.057 (0.021)    | 1.000 (0.371)    | -         |    13.24 | buster, Jyo, lattykk, neaLaN, Ryujin      |
|           33 |     2108 | 2024-04-29 | Dynamo Eclot        | L   | 0.996      | -            | -                | -                | -         |   -15.90 | buster, Jyo, lattykk, neaLaN, Ryujin      |
|           32 |     2111 | 2024-04-29 | SINNERS Esports     | L   | 0.996      | -            | -                | -                | -         |   -16.57 | buster, Jyo, lattykk, neaLaN, Ryujin      |
|           31 |     2143 | 2024-04-28 | Sangal Esports      | L   | 0.990      | -            | -                | -                | -         |   -13.86 | buster, Jyo, lattykk, neaLaN, Ryujin      |
|           30 |     2228 | 2024-04-27 | Nemiga Gaming       | L   | 0.982      | -            | -                | -                | -         |    -8.38 | buster, Jyo, lattykk, neaLaN, Ryujin      |
|           29 |     2359 | 2024-04-25 | Permitta Esports    | W   | 0.970      | 0.435        | 0.025 (0.011)    | 1.000 (0.421)    | -         |    13.50 | buster, Jyo, lattykk, neaLaN, Ryujin      |
|           28 |     2472 | 2024-04-23 | HAVU Gaming         | W   | 0.956      | -            | -                | -                | -         |     4.60 | buster, Jyo, lattykk, neaLaN, Ryujin      |
|           27 |     2572 | 2024-04-21 | Nemiga Gaming       | L   | 0.942      | -            | -                | -                | -         |    -7.87 | buster, Jyo, lattykk, neaLaN, Ryujin      |
|           26 |     2630 | 2024-04-20 | esmagaB             | W   | 0.937      | -            | -                | -                | -         |     7.85 | buster, Jyo, lattykk, neaLaN, Ryujin      |
|           25 |     2973 | 2024-04-16 | ENCE Academy        | W   | 0.909      | -            | -                | -                | -         |     8.43 | buster, Jyo, lattykk, neaLaN, Ryujin      |
|           24 |     3024 | 2024-04-15 | ARCRED              | W   | 0.902      | 0.372        | -                | 0.630 (0.212)    | -         |     7.77 | buster, Jyo, lattykk, neaLaN, Ryujin      |
|           23 |     3031 | 2024-04-15 | Lazer Cats          | W   | 0.901      | -            | -                | -                | -         |     5.07 | buster, Jyo, lattykk, neaLaN, Ryujin      |
|           22 |     3331 | 2024-04-09 | Aurora Gaming       | L   | 0.863      | -            | -                | -                | -         |    -2.37 | buster, Jyo, lattykk, neaLaN, Ryujin      |
|           21 |     3366 | 2024-04-08 | 9Pandas             | W   | 0.857      | 0.143        | 0.110 (0.013)    | -                | -         |    20.09 | buster, Jyo, lattykk, neaLaN, Ryujin      |
|           20 |     3384 | 2024-04-08 | Aurora Gaming       | W   | 0.856      | 0.143        | 0.492 (0.060)    | -                | -         |    24.96 | buster, Jyo, lattykk, neaLaN, Ryujin      |
|           19 |     4741 | 2024-03-11 | Insilio             | L   | 0.670      | -            | -                | -                | -         |   -10.10 | buster, cronuss, lattykk, oz1k, Ryujin    |
|           18 |     4791 | 2024-03-10 | VP.Prodigy          | W   | 0.663      | 0.371        | -                | 0.829 (0.204)    | -         |     8.10 | buster, lattykk, neaLaN, oz1k, Ryujin     |
|           17 |     5078 | 2024-03-05 | ARCRED              | L   | 0.631      | -            | -                | -                | -         |   -14.13 | buster, lattykk, neaLaN, oz1k, Ryujin     |
|           16 |     5338 | 2024-03-02 | CYBERSHOKE Esports  | W   | 0.610      | -            | -                | -                | -         |     2.93 | buster, lattykk, neaLaN, oz1k, Ryujin     |
|           15 |     5415 | 2024-02-29 | FAVBET Team         | L   | 0.598      | -            | -                | -                | -         |   -11.73 | buster, lattykk, neaLaN, oz1k, Ryujin     |
|           14 |     5469 | 2024-02-28 | UNiTY esports       | W   | 0.591      | -            | -                | -                | -         |     6.59 | buster, lattykk, neaLaN, oz1k, Ryujin     |
|           13 |     5614 | 2024-02-25 | VaselineWorms       | W   | 0.570      | -            | -                | -                | -         |     3.23 | buster, lattykk, neaLaN, oz1k, Ryujin     |
|           12 |     5863 | 2024-02-21 | Golden Sword        | W   | 0.544      | -            | -                | -                | -         |     0.69 | buster, lattykk, neaLaN, oz1k, Ryujin     |
|           11 |     5929 | 2024-02-20 | los kogutos         | L   | 0.537      | -            | -                | -                | -         |   -15.51 | buster, lattykk, neaLaN, oz1k, Ryujin     |
|           10 |     5992 | 2024-02-19 | ALTERNATE aTTaX     | W   | 0.531      | -            | -                | -                | -         |     8.22 | buster, lattykk, neaLaN, oz1k, Ryujin     |
|            9 |     6209 | 2024-02-15 | Copenhagen Wolves   | W   | 0.504      | -            | -                | -                | -         |     2.31 | buster, lattykk, neaLaN, oz1k, Ryujin     |
|            8 |     6219 | 2024-02-15 | Lemondogs           | W   | 0.504      | -            | -                | -                | -         |     1.82 | buster, lattykk, neaLaN, oz1k, Ryujin     |
|            7 |     6339 | 2024-02-13 | V1dar Gaming        | W   | 0.491      | -            | -                | -                | -         |     2.69 | buster, lattykk, neaLaN, oz1k, Ryujin     |
|            6 |     6343 | 2024-02-13 | Nemiga Gaming       | L   | 0.490      | -            | -                | -                | -         |    -2.36 | buster, lattykk, neaLaN, oz1k, Ryujin     |
|            5 |     6878 | 2024-02-01 | Soda Gaming         | L   | 0.411      | -            | -                | -                | -         |   -10.81 | 2high, aidKiT, Ciocardau, shadiy, soulfly |
|            4 |     7001 | 2024-01-29 | RUSH B              | L   | 0.392      | -            | -                | -                | -         |    -9.58 | executoR, kinqie, Kiro, nota, tex1y       |
|            3 |     7034 | 2024-01-29 | Sashi Esport        | W   | 0.392      | -            | -                | -                | -         |     1.08 | b0RUP, Fessor, n1Xen, niko, nut nut       |
|            2 |     7175 | 2024-01-27 | FORZE Youngsters    | W   | 0.377      | -            | -                | -                | -         |     1.82 | boN11, kelieN, matusik, spirit, sstiNiX   |
|            1 |     7248 | 2024-01-26 | RUBY                | L   | 0.371      | -            | -                | -                | -         |    -7.20 | buster, lattykk, neaLaN, oz1k, Ryujin     |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($15,128.22)
- Divide that value by the 5th highest value among all rosters ($300,806.11)
- The final value (0.05) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-05-26 |      1.000 | $5,000.00      | $5,000.00       |
| 2024-05-09 |      1.000 | $10,128.22     | $10,128.22      |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
