### Roster Details<br />
Team Name: Lynn Vision Gaming<br />
Roster: EmiliaQAQ, flying, Starry, westmelon, z4kr<br />
Region: [Asia]( ../standings_asia.md)<br />
<br />
Global Rank: [50](../standings_global.md)<br />
Regional Rank: [4]( ../standings_asia.md)<br />
Final Rank Value:  1055.0<br />
<br />
Final Rank Value (1055.0) = Starting Rank Value (1115.0) + Head To Head Adjustments (-60.0)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.454[<sup>1</sup>](#table2)
- Bounty Collected: 0.365[<sup>2</sup>](#table1)
- Opponent Network: 0.118[<sup>2</sup>](#table1)
- LAN Wins: 0.468[<sup>2</sup>](#table1)

The average of these factors is 0.351<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1115.0
- 400 + ( ( 0.351 - 0.000 ) / ( 0.786 - 0.000 ) ) * 1600 = 1115.0


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent                  | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                     |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           56 |      140 | 2024-05-27 | Aurora Gaming             | L   | 1.000      | -            | -                | -                | -         |    -4.79 | EmiliaQAQ, flying, Starry, westmelon, z4kr |
|           55 |      611 | 2024-05-21 | DEWA United               | W   | 1.000      | 0.417        | -                | 0.185 (0.077)    | 0 (0.000) |     3.80 | EmiliaQAQ, flying, Starry, westmelon, z4kr |
|           54 |      618 | 2024-05-21 | DEWA United               | W   | 1.000      | 0.417        | -                | 0.185 (0.077)    | 0 (0.000) |     3.94 | EmiliaQAQ, flying, Starry, westmelon, z4kr |
|           53 |     1645 | 2024-05-08 | Gods Reign                | W   | 1.000      | 0.417        | 0.086 (0.036)    | 0.461 (0.192)    | -         |     8.58 | EmiliaQAQ, flying, Starry, westmelon, z4kr |
|           52 |     2530 | 2024-04-21 | ATOX Esports              | L   | 0.941      | -            | -                | -                | -         |   -11.34 | EmiliaQAQ, Jee, Starry, westmelon, z4kr    |
|           51 |     2609 | 2024-04-20 | The QUBE Esports          | W   | 0.936      | -            | -                | -                | -         |     3.41 | EmiliaQAQ, Jee, Starry, westmelon, z4kr    |
|           50 |     2624 | 2024-04-20 | The QUBE Esports          | W   | 0.936      | -            | -                | -                | -         |     3.53 | EmiliaQAQ, Jee, Starry, westmelon, z4kr    |
|           49 |     2648 | 2024-04-20 | Gen.G Esports             | W   | 0.934      | -            | -                | -                | -         |     1.56 | EmiliaQAQ, Jee, Starry, westmelon, z4kr    |
|           48 |     2774 | 2024-04-18 | Rare Atom                 | L   | 0.923      | -            | -                | -                | -         |   -22.55 | EmiliaQAQ, Jee, Starry, westmelon, z4kr    |
|           47 |     2791 | 2024-04-18 | TYLOO                     | L   | 0.922      | -            | -                | -                | -         |   -19.96 | EmiliaQAQ, Jee, Starry, westmelon, z4kr    |
|           46 |     2796 | 2024-04-18 | Rare Atom                 | L   | 0.921      | -            | -                | -                | -         |   -24.20 | EmiliaQAQ, Jee, Starry, westmelon, z4kr    |
|           45 |     2800 | 2024-04-17 | Gen.G Esports             | W   | 0.920      | -            | -                | -                | -         |     0.95 | EmiliaQAQ, Jee, Starry, westmelon, z4kr    |
|           44 |     3266 | 2024-04-09 | G2 Esports                | L   | 0.862      | -            | -                | -                | -         |    -0.60 | EmiliaQAQ, Jee, Starry, westmelon, z4kr    |
|           43 |     3307 | 2024-04-08 | TYLOO                     | W   | 0.856      | 0.624        | 0.035 (0.019)    | 0.433 (0.231)    | 1 (0.856) |     6.66 | EmiliaQAQ, Jee, Starry, westmelon, z4kr    |
|           42 |     3320 | 2024-04-07 | FURIA Esports             | L   | 0.854      | -            | -                | -                | -         |    -4.24 | EmiliaQAQ, Jee, Starry, westmelon, z4kr    |
|           41 |     3564 | 2024-04-03 | The MongolZ               | L   | 0.822      | -            | -                | -                | -         |    -2.21 | EmiliaQAQ, Jee, Starry, westmelon, z4kr    |
|           40 |     3610 | 2024-04-02 | LYG Gaming                | W   | 0.816      | -            | -                | -                | -         |     3.60 | EmiliaQAQ, Jee, Starry, westmelon, z4kr    |
|           39 |     3616 | 2024-04-02 | ATOX Esports              | W   | 0.815      | 0.143        | 0.047 (0.006)    | 0.601 (0.070)    | -         |    15.49 | EmiliaQAQ, Jee, Starry, westmelon, z4kr    |
|           38 |     3682 | 2024-03-30 | GR Gaming                 | L   | 0.796      | -            | -                | -                | -         |   -19.92 | EmiliaQAQ, Jee, Starry, westmelon, z4kr    |
|           37 |     3692 | 2024-03-30 | GR Gaming                 | W   | 0.796      | 0.417        | 0.007 (0.002)    | 0.428 (0.142)    | -         |     4.93 | EmiliaQAQ, Jee, Starry, westmelon, z4kr    |
|           36 |     3819 | 2024-03-27 | Clutch Gaming             | L   | 0.776      | -            | -                | -                | -         |   -22.18 | EmiliaQAQ, Jee, Starry, westmelon, z4kr    |
|           35 |     3822 | 2024-03-27 | Clutch Gaming             | W   | 0.776      | -            | -                | -                | -         |     2.12 | EmiliaQAQ, Jee, Starry, westmelon, z4kr    |
|           34 |     3894 | 2024-03-26 | MIRAI Gaming              | W   | 0.770      | 0.417        | -                | 0.200 (0.064)    | -         |     2.01 | EmiliaQAQ, Jee, Starry, westmelon, z4kr    |
|           33 |     3898 | 2024-03-26 | MIRAI Gaming              | W   | 0.769      | -            | -                | -                | -         |     2.06 | EmiliaQAQ, Jee, Starry, westmelon, z4kr    |
|           32 |     4180 | 2024-03-19 | The MongolZ               | L   | 0.723      | -            | -                | -                | -         |    -1.71 | EmiliaQAQ, Jee, Starry, westmelon, z4KR    |
|           31 |     4219 | 2024-03-18 | Gaimin Gladiators         | L   | 0.716      | -            | -                | -                | -         |    -7.39 | EmiliaQAQ, Jee, Starry, westmelon, z4KR    |
|           30 |     4232 | 2024-03-17 | FURIA Esports             | W   | 0.712      | 1.000        | 0.138 (0.098)    | 0.267 (0.190)    | 1 (0.712) |    18.76 | EmiliaQAQ, Jee, Starry, westmelon, z4KR    |
|           29 |     4277 | 2024-03-17 | HEROIC                    | L   | 0.710      | -            | -                | -                | -         |    -0.77 | EmiliaQAQ, Jee, Starry, westmelon, z4KR    |
|           28 |     4887 | 2024-03-06 | -72C                      | W   | 0.636      | 0.417        | -                | 0.252 (0.067)    | -         |     2.51 | EmiliaQAQ, Jee, Starry, westmelon, z4kr    |
|           27 |     4892 | 2024-03-06 | -72C                      | W   | 0.636      | 0.417        | -                | 0.252 (0.067)    | -         |     2.57 | EmiliaQAQ, Jee, Starry, westmelon, z4kr    |
|           26 |     5342 | 2024-02-27 | FlyQuest                  | W   | 0.588      | 0.143        | 0.114 (0.010)    | -                | 1 (0.588) |    16.04 | EmiliaQAQ, Jee, Starry, westmelon, z4kr    |
|           25 |     5344 | 2024-02-27 | The MongolZ               | L   | 0.586      | -            | -                | -                | -         |    -1.06 | EmiliaQAQ, Jee, Starry, westmelon, z4kr    |
|           24 |     5427 | 2024-02-25 | TYLOO                     | W   | 0.574      | 0.143        | 0.017 (0.001)    | -                | 1 (0.574) |     3.63 | EmiliaQAQ, Jee, Starry, westmelon, z4kr    |
|           23 |     5430 | 2024-02-25 | Twisted Minds             | W   | 0.574      | -            | -                | -                | 1 (0.574) |     1.02 | EmiliaQAQ, Jee, Starry, westmelon, z4kr    |
|           22 |     5722 | 2024-02-21 | Born In Far East          | W   | 0.543      | -            | -                | -                | -         |     1.54 | EmiliaQAQ, Jee, Starry, westmelon, z4kr    |
|           21 |     5727 | 2024-02-21 | Born In Far East          | W   | 0.543      | -            | -                | -                | -         |     1.57 | EmiliaQAQ, Jee, Starry, westmelon, z4kr    |
|           20 |     5771 | 2024-02-20 | NewHappy                  | W   | 0.536      | 0.417        | 0.020 (0.004)    | -                | -         |     2.74 | EmiliaQAQ, Jee, Starry, westmelon, z4kr    |
|           19 |     5778 | 2024-02-20 | NewHappy                  | W   | 0.536      | 0.417        | 0.020 (0.004)    | -                | -         |     2.81 | EmiliaQAQ, Jee, Starry, westmelon, z4kr    |
|           18 |     5953 | 2024-02-17 | NewHappy                  | L   | 0.516      | -            | -                | -                | -         |   -13.78 | EmiliaQAQ, Jee, Starry, westmelon, z4kr    |
|           17 |     6007 | 2024-02-16 | Myth Avenue Gaming        | W   | 0.508      | -            | -                | -                | -         |     1.90 | EmiliaQAQ, Jee, Starry, westmelon, z4kr    |
|           16 |     6734 | 2024-01-31 | Rare Atom                 | L   | 0.403      | -            | -                | -                | -         |   -11.24 | EmiliaQAQ, Jee, Starry, westmelon, z4kr    |
|           15 |     6742 | 2024-01-31 | Team NKT                  | L   | 0.401      | -            | -                | -                | -         |   -11.23 | EmiliaQAQ, Jee, Starry, westmelon, z4kr    |
|           14 |     6886 | 2024-01-28 | The MongolZ               | L   | 0.382      | -            | -                | -                | -         |    -0.77 | EmiliaQAQ, Jee, Starry, westmelon, z4kr    |
|           13 |     6892 | 2024-01-27 | TYLOO                     | W   | 0.380      | 0.435        | 0.017 (0.003)    | -                | 1 (0.380) |     2.16 | EmiliaQAQ, Jee, Starry, westmelon, z4kr    |
|           12 |     7056 | 2024-01-26 | Team NKT                  | W   | 0.369      | -            | -                | -                | 1 (0.369) |     1.26 | EmiliaQAQ, Jee, Starry, westmelon, z4kr    |
|           11 |     7062 | 2024-01-26 | Những Chàng Trai Đeo Kính | W   | 0.368      | -            | -                | -                | 1 (0.368) |     0.77 | EmiliaQAQ, Jee, Starry, westmelon, z4kr    |
|           10 |     7298 | 2024-01-20 | TYLOO                     | W   | 0.334      | -            | -                | -                | -         |     1.68 | EmiliaQAQ, Jee, Starry, westmelon, z4kr    |
|            9 |     7432 | 2024-01-19 | Wings Up Gaming           | W   | 0.321      | -            | -                | -                | -         |     0.89 | EmiliaQAQ, Jee, Starry, westmelon, z4kr    |
|            8 |     7440 | 2024-01-18 | Nirvana Esports           | W   | 0.321      | -            | -                | -                | -         |     0.19 | EmiliaQAQ, Jee, Starry, westmelon, z4kr    |
|            7 |     8321 | 2023-12-27 | NewHappy                  | L   | 0.169      | -            | -                | -                | -         |    -4.89 | EmiliaQAQ, Jee, Starry, westmelon, z4kr    |
|            6 |     8327 | 2023-12-23 | TYLOO                     | W   | 0.147      | -            | -                | -                | -         |     0.68 | EmiliaQAQ, Jee, Starry, westmelon, z4kr    |
|            5 |     8341 | 2023-12-22 | Rare Atom                 | W   | 0.141      | -            | -                | -                | -         |     0.41 | EmiliaQAQ, Jee, Starry, westmelon, z4kr    |
|            4 |     8345 | 2023-12-22 | Secret                    | W   | 0.141      | -            | -                | -                | -         |     0.08 | EmiliaQAQ, Jee, Starry, westmelon, z4kr    |
|            3 |     9041 | 2023-12-09 | The MongolZ               | L   | 0.049      | -            | -                | -                | -         |    -0.09 | EmiliaQAQ, Jee, Starry, westmelon, z4kr    |
|            2 |     9182 | 2023-12-07 | TYLOO                     | L   | 0.036      | -            | -                | -                | -         |    -0.97 | EmiliaQAQ, Jee, Starry, westmelon, z4kr    |
|            1 |     9238 | 2023-12-06 | GR Gaming                 | W   | 0.029      | -            | -                | -                | -         |     0.12 | EmiliaQAQ, Jee, Starry, westmelon, z4kr    |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($18,918.99)
- Divide that value by the 5th highest value among all rosters ($300,806.11)
- The final value (0.06) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-04-21 |      0.942 | $1,381.25      | $1,301.45       |
| 2024-04-14 |      0.895 | $5,000.00      | $4,475.81       |
| 2024-03-31 |      0.804 | $10,000.00     | $8,038.89       |
| 2024-01-28 |      0.382 | $12,000.00     | $4,586.67       |
| 2023-12-27 |      0.169 | $1,399.89      | $237.01         |
| 2023-12-10 |      0.056 | $5,000.00      | $279.17         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
