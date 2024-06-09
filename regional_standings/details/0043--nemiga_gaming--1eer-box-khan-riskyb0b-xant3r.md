### Roster Details<br />
Team Name: Nemiga Gaming<br />
Roster: 1eeR, boX, khaN, riskyb0b, Xant3r<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [43](../standings_global.md)<br />
Regional Rank: [31]( ../standings_europe.md)<br />
Final Rank Value:  1084.0<br />
<br />
Final Rank Value (1084.0) = Starting Rank Value (1254.6) + Head To Head Adjustments (-170.6)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.692[<sup>1</sup>](#table2)
- Bounty Collected: 0.463[<sup>2</sup>](#table1)
- Opponent Network: 0.436[<sup>2</sup>](#table1)
- LAN Wins: 0.091[<sup>2</sup>](#table1)

The average of these factors is 0.420<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1254.6
- 400 + ( ( 0.420 - 0.000 ) / ( 0.787 - 0.000 ) ) * 1600 = 1254.6


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent                  | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           85 |      361 | 2024-05-24 | Endpoint                  | L   | 1.000      | -            | -                | -                | -         |   -23.44 | 1eeR, boX, khaN, riskyb0b, Xant3r     |
|           84 |      369 | 2024-05-24 | VP.Prodigy                | W   | 1.000      | -            | -                | -                | 0 (0.000) |     7.00 | 1eeR, boX, khaN, riskyb0b, Xant3r     |
|           83 |      627 | 2024-05-21 | CYBERSHOKE Esports        | W   | 1.000      | -            | -                | -                | 0 (0.000) |     3.76 | 1eeR, boX, khaN, riskyb0b, Xant3r     |
|           82 |      686 | 2024-05-20 | V1dar Gaming              | W   | 1.000      | -            | -                | -                | 0 (0.000) |     4.57 | 1eeR, boX, khaN, riskyb0b, Xant3r     |
|           81 |      912 | 2024-05-18 | GUN5 Esports              | L   | 1.000      | -            | -                | -                | -         |   -27.15 | 1eeR, khaN, riskyb0b, Xant3r, zweih   |
|           80 |      937 | 2024-05-18 | naChille                  | W   | 1.000      | -            | -                | -                | 0 (0.000) |     1.82 | 1eeR, khaN, riskyb0b, Xant3r, zweih   |
|           79 |     1096 | 2024-05-16 | Entropiq                  | L   | 1.000      | -            | -                | -                | -         |   -28.92 | 1eeR, boX, khaN, riskyb0b, Xant3r     |
|           78 |     1339 | 2024-05-13 | RUSH B                    | L   | 1.000      | -            | -                | -                | -         |   -27.00 | 1eeR, khaN, riskyb0b, Xant3r, zweih   |
|           77 |     1344 | 2024-05-13 | VP.Prodigy                | W   | 1.000      | -            | -                | -                | 0 (0.000) |     4.02 | 1eeR, khaN, riskyb0b, Xant3r, zweih   |
|           76 |     1548 | 2024-05-10 | RUBY                      | L   | 1.000      | -            | -                | -                | -         |   -24.08 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r  |
|           75 |     1642 | 2024-05-08 | ARCRED                    | W   | 1.000      | -            | -                | -                | 0 (0.000) |     4.97 | 1eeR, boX, khaN, riskyb0b, Xant3r     |
|           74 |     1648 | 2024-05-08 | ex-Turów Zgorzelec Esport | W   | 1.000      | -            | -                | -                | 0 (0.000) |     2.56 | 1eeR, boX, khaN, riskyb0b, Xant3r     |
|           73 |     1654 | 2024-05-08 | Rhyno Esports             | W   | 1.000      | -            | -                | -                | 0 (0.000) |     7.70 | 1eeR, boX, khaN, riskyb0b, Xant3r     |
|           72 |     1670 | 2024-05-08 | 1win                      | L   | 1.000      | -            | -                | -                | -         |   -21.87 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r  |
|           71 |     1714 | 2024-05-07 | SINNERS Esports           | W   | 1.000      | -            | -                | -                | 0 (0.000) |     7.00 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r  |
|           70 |     1741 | 2024-05-06 | LODIS                     | W   | 1.000      | -            | -                | -                | -         |     1.12 | 1eeR, boX, khaN, riskyb0b, Xant3r     |
|           69 |     1747 | 2024-05-06 | MOUZ NXT                  | L   | 1.000      | -            | -                | -                | -         |   -21.92 | 1eeR, boX, khaN, riskyb0b, Xant3r     |
|           68 |     1754 | 2024-05-06 | Team Spirit Academy       | W   | 1.000      | -            | -                | -                | -         |     1.97 | 1eeR, boX, khaN, riskyb0b, Xant3r     |
|           67 |     1786 | 2024-05-05 | VP.Prodigy                | W   | 1.000      | -            | -                | -                | -         |     3.02 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r  |
|           66 |     1906 | 2024-05-03 | MOUZ NXT                  | W   | 1.000      | 0.500        | 0.157 (0.079)    | 0.977 (0.488)    | -         |     9.94 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r  |
|           65 |     1948 | 2024-05-02 | Passion UA                | W   | 1.000      | 0.500        | 0.057 (0.028)    | 1.000 (0.500)    | -         |     6.22 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r  |
|           64 |     1992 | 2024-05-01 | B8                        | W   | 1.000      | 0.500        | 0.168 (0.084)    | 0.963 (0.482)    | -         |    10.16 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r  |
|           63 |     2089 | 2024-04-29 | MOUZ NXT                  | W   | 0.997      | 0.500        | 0.157 (0.078)    | 0.977 (0.487)    | -         |    10.90 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r  |
|           62 |     2165 | 2024-04-28 | Grannys Knockers          | L   | 0.988      | -            | -                | -                | -         |   -27.11 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r  |
|           61 |     2228 | 2024-04-27 | 1win                      | W   | 0.982      | 0.500        | -                | 0.898 (0.441)    | -         |     8.38 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r  |
|           60 |     2316 | 2024-04-26 | Sangal Esports            | L   | 0.975      | -            | -                | -                | -         |   -21.60 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r  |
|           59 |     2408 | 2024-04-24 | kONO.ECF                  | W   | 0.964      | -            | -                | -                | -         |     4.96 | 1eeR, boX, khaN, riskyb0b, Xant3r     |
|           58 |     2422 | 2024-04-24 | BLEED Esports             | W   | 0.963      | 0.500        | 0.248 (0.119)    | 0.714 (0.344)    | -         |    16.62 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r  |
|           57 |     2453 | 2024-04-23 | EXO Clan                  | L   | 0.957      | -            | -                | -                | -         |   -21.68 | 1eeR, boX, khaN, riskyb0b, Xant3r     |
|           56 |     2478 | 2024-04-23 | Zero Tenacity             | W   | 0.956      | 0.500        | 0.147 (0.070)    | 1.000 (0.478)    | -         |     7.22 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r  |
|           55 |     2523 | 2024-04-22 | MOUZ NXT                  | W   | 0.948      | 0.500        | 0.157 (0.074)    | 0.977 (0.463)    | -         |    10.04 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r  |
|           54 |     2557 | 2024-04-21 | Team PeeP                 | W   | 0.943      | -            | -                | -                | -         |     0.97 | 1eeR, khaN, riskyb0b, Xant3r, zweih   |
|           53 |     2572 | 2024-04-21 | 1win                      | W   | 0.942      | 0.435        | -                | 0.898 (0.367)    | -         |     7.87 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r  |
|           52 |     2696 | 2024-04-20 | Gaimin Gladiators         | L   | 0.935      | -            | -                | -                | -         |   -11.64 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r  |
|           51 |     2738 | 2024-04-19 | ex-KRC Genk Esports       | W   | 0.931      | -            | -                | -                | -         |     1.41 | 1eeR, boX, khaN, riskyb0b, Xant3r     |
|           50 |     2763 | 2024-04-19 | Sangal Esports            | W   | 0.930      | 0.500        | 0.166 (0.077)    | -                | -         |     8.52 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r  |
|           49 |     2825 | 2024-04-18 | Team Secret               | W   | 0.923      | -            | -                | -                | -         |     1.66 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r  |
|           48 |     2902 | 2024-04-17 | Alliance                  | W   | 0.916      | -            | -                | -                | -         |     4.09 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r  |
|           47 |     3289 | 2024-04-09 | FlyQuest                  | L   | 0.867      | -            | -                | -                | -         |    -5.23 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r  |
|           46 |     3350 | 2024-04-09 | Steel Helmet              | W   | 0.861      | -            | -                | -                | 1 (0.861) |     1.44 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r  |
|           45 |     3394 | 2024-04-08 | FaZe Clan                 | L   | 0.855      | -            | -                | -                | -         |    -0.35 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r  |
|           44 |     3725 | 2024-04-01 | Zero Tenacity             | W   | 0.808      | 0.384        | 0.147 (0.046)    | 1.000 (0.311)    | -         |     6.82 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r  |
|           43 |     3963 | 2024-03-26 | AURA                      | L   | 0.771      | -            | -                | -                | -         |   -22.93 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r  |
|           42 |     4130 | 2024-03-22 | Sashi Esport              | L   | 0.744      | -            | -                | -                | -         |   -16.52 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r  |
|           41 |     4677 | 2024-03-12 | Nexus Gaming              | L   | 0.677      | -            | -                | -                | -         |   -17.83 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r  |
|           40 |     4747 | 2024-03-11 | Sashi Esport              | W   | 0.670      | 0.371        | 0.154 (0.038)    | -                | -         |     5.09 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r  |
|           39 |     4789 | 2024-03-10 | Endpoint                  | W   | 0.664      | -            | -                | -                | -         |     3.32 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r  |
|           38 |     5086 | 2024-03-05 | KOI                       | L   | 0.631      | -            | -                | -                | -         |   -15.20 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r  |
|           37 |     5102 | 2024-03-05 | GUN5 Esports              | W   | 0.631      | -            | -                | -                | -         |     0.81 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r  |
|           36 |     5146 | 2024-03-04 | ENTERPRISE esports        | W   | 0.625      | -            | -                | -                | -         |     3.51 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r  |
|           35 |     5176 | 2024-03-04 | Aurora Young Blud         | W   | 0.625      | -            | -                | -                | -         |     1.35 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r  |
|           34 |     5306 | 2024-03-02 | kONO.ECF                  | L   | 0.611      | -            | -                | -                | -         |   -16.34 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r  |
|           33 |     5895 | 2024-02-21 | Insilio                   | W   | 0.543      | -            | -                | -                | -         |     2.66 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r  |
|           32 |     5943 | 2024-02-20 | NOM Esports               | W   | 0.536      | -            | -                | -                | -         |     0.50 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r  |
|           31 |     6000 | 2024-02-19 | FORZE Youngsters          | W   | 0.531      | -            | -                | -                | -         |     0.69 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r  |
|           30 |     6007 | 2024-02-19 | Endpoint                  | W   | 0.530      | -            | -                | -                | -         |     2.47 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r  |
|           29 |     6052 | 2024-02-18 | GUN5 Esports              | L   | 0.523      | -            | -                | -                | -         |   -16.05 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r  |
|           28 |     6343 | 2024-02-13 | 1win                      | W   | 0.490      | -            | -                | -                | -         |     2.36 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r  |
|           27 |     6396 | 2024-02-12 | Team Secret               | W   | 0.484      | -            | -                | -                | -         |     0.51 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r  |
|           26 |     6400 | 2024-02-12 | ILIN                      | W   | 0.484      | -            | -                | -                | -         |     0.27 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r  |
|           25 |     6441 | 2024-02-10 | Sashi Esport              | W   | 0.471      | -            | -                | -                | -         |     3.71 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r  |
|           24 |     6481 | 2024-02-09 | AMKAL ESPORTS             | W   | 0.464      | -            | -                | -                | -         |     6.67 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r  |
|           23 |     6510 | 2024-02-08 | Sashi Esport              | W   | 0.458      | -            | -                | -                | -         |     3.47 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r  |
|           22 |     6523 | 2024-02-08 | BetBoom Team              | W   | 0.457      | -            | -                | -                | -         |    10.68 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r  |
|           21 |     6623 | 2024-02-05 | Kappa Bar                 | W   | 0.437      | -            | -                | -                | -         |     0.25 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r  |
|           20 |     6657 | 2024-02-04 | 0to100                    | W   | 0.431      | -            | -                | -                | -         |     0.19 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r  |
|           19 |     6886 | 2024-02-01 | Lausanne-Sport Esports    | L   | 0.410      | -            | -                | -                | -         |   -12.07 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r  |
|           18 |     6962 | 2024-01-30 | RUBY                      | W   | 0.398      | -            | -                | -                | -         |     1.78 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r  |
|           17 |     6966 | 2024-01-30 | Sprout                    | W   | 0.398      | -            | -                | -                | -         |     0.47 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r  |
|           16 |     6974 | 2024-01-30 | 9Pandas                   | W   | 0.397      | -            | -                | -                | -         |     5.41 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r  |
|           15 |     7000 | 2024-01-29 | Aurora Gaming             | W   | 0.392      | -            | -                | -                | -         |     9.56 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r  |
|           14 |     7021 | 2024-01-29 | Endpoint                  | W   | 0.392      | -            | -                | -                | -         |     2.02 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r  |
|           13 |     7353 | 2024-01-24 | ex-Hot Headed Gaming      | W   | 0.357      | -            | -                | -                | -         |     0.20 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r  |
|           12 |     7356 | 2024-01-24 | ENTERPRISE esports        | L   | 0.357      | -            | -                | -                | -         |    -8.98 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r  |
|           11 |     7358 | 2024-01-24 | GODSENT                   | W   | 0.357      | -            | -                | -                | -         |     0.42 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r  |
|           10 |     7816 | 2024-01-17 | ex-Preasy Esport          | L   | 0.311      | -            | -                | -                | -         |    -8.44 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r  |
|            9 |     7890 | 2024-01-16 | samaloyod                 | L   | 0.305      | -            | -                | -                | -         |    -9.42 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r  |
|            8 |     7932 | 2024-01-16 | Betera Esports            | W   | 0.304      | -            | -                | -                | -         |     0.79 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r  |
|            7 |     8344 | 2024-01-09 | brazylijski luz           | L   | 0.257      | -            | -                | -                | -         |    -7.48 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r  |
|            6 |     8359 | 2024-01-09 | HEROIC                    | W   | 0.257      | -            | -                | -                | -         |     7.66 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r  |
|            5 |     8768 | 2023-12-17 | LF0                       | W   | 0.102      | -            | -                | -                | -         |     0.09 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r  |
|            4 |     8884 | 2023-12-16 | VP.Prodigy                | W   | 0.096      | -            | -                | -                | -         |     0.28 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r  |
|            3 |     8906 | 2023-12-16 | BAKS Esports              | W   | 0.095      | -            | -                | -                | -         |     0.09 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r  |
|            2 |     9495 | 2023-12-06 | ENTERPRISE esports        | L   | 0.031      | -            | -                | -                | -         |    -0.82 | 1eeR, almazer, FL4MUS, khaN, riskyb0b |
|            1 |     9515 | 2023-12-06 | MOUZ NXT                  | L   | 0.029      | -            | -                | -                | -         |    -0.63 | 1eeR, almazer, FL4MUS, khaN, riskyb0b |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($107,692.70)
- Divide that value by the 5th highest value among all rosters ($300,806.11)
- The final value (0.36) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-05-09 |      1.000 | $5,064.11      | $5,064.11       |
| 2024-05-03 |      1.000 | $50,000.00     | $50,000.00      |
| 2024-04-24 |      0.963 | $50,000.00     | $48,152.78      |
| 2024-04-14 |      0.895 | $5,000.00      | $4,475.81       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
