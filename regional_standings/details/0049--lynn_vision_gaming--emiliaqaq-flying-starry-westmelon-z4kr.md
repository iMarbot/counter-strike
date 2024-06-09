### Roster Details<br />
Team Name: Lynn Vision Gaming<br />
Roster: EmiliaQAQ, flying, Starry, westmelon, z4kr<br />
Region: [Asia]( ../standings_asia.md)<br />
<br />
Global Rank: [49](../standings_global.md)<br />
Regional Rank: [4]( ../standings_asia.md)<br />
Final Rank Value:  1053.7<br />
<br />
Final Rank Value (1053.7) = Starting Rank Value (1113.6) + Head To Head Adjustments (-59.9)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.454[<sup>1</sup>](#table2)
- Bounty Collected: 0.365[<sup>2</sup>](#table1)
- Opponent Network: 0.117[<sup>2</sup>](#table1)
- LAN Wins: 0.468[<sup>2</sup>](#table1)

The average of these factors is 0.351<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1113.6
- 400 + ( ( 0.351 - 0.000 ) / ( 0.787 - 0.000 ) ) * 1600 = 1113.6


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
|           58 |      147 | 2024-05-27 | Aurora Gaming             | L   | 1.000      | -            | -                | -                | -         |    -5.19 | EmiliaQAQ, flying, Starry, westmelon, z4kr |
|           57 |      622 | 2024-05-21 | DEWA United               | W   | 1.000      | 0.417        | -                | 0.176 (0.073)    | 0 (0.000) |     3.75 | EmiliaQAQ, flying, Starry, westmelon, z4kr |
|           56 |      629 | 2024-05-21 | DEWA United               | W   | 1.000      | 0.417        | -                | 0.176 (0.073)    | 0 (0.000) |     3.89 | EmiliaQAQ, flying, Starry, westmelon, z4kr |
|           55 |     1663 | 2024-05-08 | Gods Reign                | W   | 1.000      | 0.417        | 0.086 (0.036)    | 0.461 (0.192)    | -         |     8.09 | EmiliaQAQ, flying, Starry, westmelon, z4kr |
|           54 |     2583 | 2024-04-21 | ATOX Esports              | L   | 0.941      | -            | -                | -                | -         |   -10.18 | EmiliaQAQ, Jee, Starry, westmelon, z4kr    |
|           53 |     2663 | 2024-04-20 | The QUBE Esports          | W   | 0.936      | -            | -                | -                | -         |     2.29 | EmiliaQAQ, flying, Starry, westmelon, z4kr |
|           52 |     2678 | 2024-04-20 | The QUBE Esports          | W   | 0.936      | -            | -                | -                | -         |     2.34 | EmiliaQAQ, flying, Starry, westmelon, z4kr |
|           51 |     2702 | 2024-04-20 | Gen.G Esports             | W   | 0.934      | -            | -                | -                | -         |     1.56 | EmiliaQAQ, Jee, Starry, westmelon, z4kr    |
|           50 |     2830 | 2024-04-18 | Rare Atom                 | L   | 0.923      | -            | -                | -                | -         |   -22.56 | EmiliaQAQ, Jee, Starry, westmelon, z4kr    |
|           49 |     2847 | 2024-04-18 | TYLOO                     | L   | 0.922      | -            | -                | -                | -         |   -20.35 | EmiliaQAQ, Jee, Starry, westmelon, z4kr    |
|           48 |     2852 | 2024-04-18 | Rare Atom                 | L   | 0.921      | -            | -                | -                | -         |   -24.22 | EmiliaQAQ, Jee, Starry, westmelon, z4kr    |
|           47 |     2856 | 2024-04-17 | Gen.G Esports             | W   | 0.920      | -            | -                | -                | -         |     0.94 | EmiliaQAQ, Jee, Starry, westmelon, z4kr    |
|           46 |     3345 | 2024-04-09 | G2 Esports                | L   | 0.862      | -            | -                | -                | -         |    -0.61 | EmiliaQAQ, Jee, Starry, westmelon, z4kr    |
|           45 |     3388 | 2024-04-08 | TYLOO                     | W   | 0.856      | 0.624        | 0.035 (0.019)    | 0.433 (0.231)    | 1 (0.856) |     6.34 | EmiliaQAQ, Jee, Starry, westmelon, z4kr    |
|           44 |     3401 | 2024-04-07 | FURIA Esports             | L   | 0.854      | -            | -                | -                | -         |    -4.27 | EmiliaQAQ, Jee, Starry, westmelon, z4kr    |
|           43 |     3651 | 2024-04-03 | The MongolZ               | L   | 0.822      | -            | -                | -                | -         |    -2.24 | EmiliaQAQ, Jee, Starry, westmelon, z4kr    |
|           42 |     3700 | 2024-04-02 | LYG Gaming                | W   | 0.816      | -            | -                | -                | -         |     3.51 | EmiliaQAQ, Jee, Starry, westmelon, z4kr    |
|           41 |     3706 | 2024-04-02 | ATOX Esports              | W   | 0.815      | 0.143        | 0.047 (0.006)    | 0.609 (0.071)    | -         |    16.58 | EmiliaQAQ, Jee, Starry, westmelon, z4kr    |
|           40 |     3775 | 2024-03-30 | GR Gaming                 | L   | 0.796      | -            | -                | -                | -         |   -19.99 | EmiliaQAQ, flying, Starry, westmelon, z4kr |
|           39 |     3785 | 2024-03-30 | GR Gaming                 | W   | 0.796      | 0.417        | 0.007 (0.002)    | 0.428 (0.142)    | -         |     4.87 | EmiliaQAQ, flying, Starry, westmelon, z4kr |
|           38 |     3912 | 2024-03-27 | Clutch Gaming             | L   | 0.776      | -            | -                | -                | -         |   -22.19 | EmiliaQAQ, flying, Starry, westmelon, z4kr |
|           37 |     3915 | 2024-03-27 | Clutch Gaming             | W   | 0.776      | -            | -                | -                | -         |     2.11 | EmiliaQAQ, flying, Starry, westmelon, z4kr |
|           36 |     3991 | 2024-03-26 | MIRAI Gaming              | W   | 0.770      | 0.417        | -                | 0.200 (0.064)    | -         |     1.97 | EmiliaQAQ, flying, Starry, westmelon, z4kr |
|           35 |     3995 | 2024-03-26 | MIRAI Gaming              | W   | 0.769      | -            | -                | -                | -         |     2.01 | EmiliaQAQ, flying, Starry, westmelon, z4kr |
|           34 |     4283 | 2024-03-19 | The MongolZ               | L   | 0.723      | -            | -                | -                | -         |    -1.73 | EmiliaQAQ, Jee, Starry, westmelon, z4KR    |
|           33 |     4324 | 2024-03-18 | Gaimin Gladiators         | L   | 0.716      | -            | -                | -                | -         |    -7.34 | EmiliaQAQ, Jee, Starry, westmelon, z4KR    |
|           32 |     4337 | 2024-03-17 | FURIA Esports             | W   | 0.712      | 1.000        | 0.138 (0.098)    | 0.267 (0.190)    | 1 (0.712) |    18.73 | EmiliaQAQ, Jee, Starry, westmelon, z4KR    |
|           31 |     4382 | 2024-03-17 | HEROIC                    | L   | 0.710      | -            | -                | -                | -         |    -0.77 | EmiliaQAQ, Jee, Starry, westmelon, z4KR    |
|           30 |     5019 | 2024-03-06 | -72C                      | W   | 0.636      | 0.417        | -                | 0.252 (0.067)    | -         |     2.51 | EmiliaQAQ, flying, Starry, westmelon, z4kr |
|           29 |     5026 | 2024-03-06 | -72C                      | W   | 0.636      | 0.417        | -                | 0.252 (0.067)    | -         |     2.57 | EmiliaQAQ, flying, Starry, westmelon, z4kr |
|           28 |     5110 | 2024-03-05 | ZEUSGG                    | W   | 0.630      | -            | -                | -                | -         |     0.91 | EmiliaQAQ, flying, Starry, westmelon, z4kr |
|           27 |     5116 | 2024-03-05 | ZEUSGG                    | W   | 0.629      | -            | -                | -                | -         |     0.91 | EmiliaQAQ, flying, Starry, westmelon, z4kr |
|           26 |     5494 | 2024-02-27 | FlyQuest                  | W   | 0.588      | 0.143        | 0.114 (0.010)    | -                | 1 (0.588) |    16.09 | EmiliaQAQ, Jee, Starry, westmelon, z4kr    |
|           25 |     5496 | 2024-02-27 | The MongolZ               | L   | 0.586      | -            | -                | -                | -         |    -1.06 | EmiliaQAQ, Jee, Starry, westmelon, z4kr    |
|           24 |     5585 | 2024-02-25 | TYLOO                     | W   | 0.574      | 0.143        | 0.017 (0.001)    | -                | 1 (0.574) |     3.64 | EmiliaQAQ, Jee, Starry, westmelon, z4kr    |
|           23 |     5588 | 2024-02-25 | Twisted Minds             | W   | 0.574      | -            | -                | -                | 1 (0.574) |     1.02 | EmiliaQAQ, Jee, Starry, westmelon, z4kr    |
|           22 |     5886 | 2024-02-21 | Born In Far East          | W   | 0.543      | -            | -                | -                | -         |     1.66 | EmiliaQAQ, flying, Starry, westmelon, z4kr |
|           21 |     5892 | 2024-02-21 | Born In Far East          | W   | 0.543      | -            | -                | -                | -         |     1.69 | EmiliaQAQ, flying, Starry, westmelon, z4kr |
|           20 |     5940 | 2024-02-20 | NewHappy                  | W   | 0.536      | 0.417        | 0.020 (0.004)    | -                | -         |     2.75 | EmiliaQAQ, flying, Starry, westmelon, z4kr |
|           19 |     5948 | 2024-02-20 | NewHappy                  | W   | 0.536      | 0.417        | 0.020 (0.004)    | -                | -         |     2.83 | EmiliaQAQ, flying, Starry, westmelon, z4kr |
|           18 |     6126 | 2024-02-17 | NewHappy                  | L   | 0.516      | -            | -                | -                | -         |   -13.77 | EmiliaQAQ, Jee, Starry, westmelon, z4kr    |
|           17 |     6183 | 2024-02-16 | Myth Avenue Gaming        | W   | 0.508      | -            | -                | -                | -         |     1.90 | EmiliaQAQ, Jee, Starry, westmelon, z4kr    |
|           16 |     6947 | 2024-01-31 | Rare Atom                 | L   | 0.403      | -            | -                | -                | -         |   -11.23 | EmiliaQAQ, Jee, Starry, westmelon, z4kr    |
|           15 |     6955 | 2024-01-31 | Team NKT                  | L   | 0.401      | -            | -                | -                | -         |   -11.20 | EmiliaQAQ, Jee, Starry, westmelon, z4kr    |
|           14 |     7104 | 2024-01-28 | The MongolZ               | L   | 0.382      | -            | -                | -                | -         |    -0.77 | EmiliaQAQ, Jee, Starry, westmelon, z4kr    |
|           13 |     7110 | 2024-01-27 | TYLOO                     | W   | 0.380      | 0.435        | 0.017 (0.003)    | -                | 1 (0.380) |     2.17 | EmiliaQAQ, Jee, Starry, westmelon, z4kr    |
|           12 |     7282 | 2024-01-26 | Team NKT                  | W   | 0.369      | -            | -                | -                | 1 (0.369) |     1.28 | EmiliaQAQ, Jee, Starry, westmelon, z4kr    |
|           11 |     7288 | 2024-01-26 | Những Chàng Trai Đeo Kính | W   | 0.368      | -            | -                | -                | 1 (0.368) |     0.77 | EmiliaQAQ, Jee, Starry, westmelon, z4kr    |
|           10 |     7541 | 2024-01-20 | TYLOO                     | W   | 0.334      | -            | -                | -                | -         |     1.69 | EmiliaQAQ, Jee, Starry, westmelon, z4kr    |
|            9 |     7679 | 2024-01-19 | Wings Up Gaming           | W   | 0.321      | -            | -                | -                | -         |     0.89 | EmiliaQAQ, Jee, Starry, westmelon, z4kr    |
|            8 |     7687 | 2024-01-18 | Nirvana Esports           | W   | 0.321      | -            | -                | -                | -         |     0.19 | EmiliaQAQ, Jee, Starry, westmelon, z4kr    |
|            7 |     8578 | 2023-12-27 | NewHappy                  | L   | 0.169      | -            | -                | -                | -         |    -4.89 | EmiliaQAQ, Jee, Starry, westmelon, z4kr    |
|            6 |     8584 | 2023-12-23 | TYLOO                     | W   | 0.147      | -            | -                | -                | -         |     0.68 | EmiliaQAQ, Jee, Starry, westmelon, z4kr    |
|            5 |     8598 | 2023-12-22 | Rare Atom                 | W   | 0.141      | -            | -                | -                | -         |     0.42 | EmiliaQAQ, Jee, Starry, westmelon, z4kr    |
|            4 |     8602 | 2023-12-22 | Secret                    | W   | 0.141      | -            | -                | -                | -         |     0.08 | EmiliaQAQ, Jee, Starry, westmelon, z4kr    |
|            3 |     9308 | 2023-12-09 | The MongolZ               | L   | 0.049      | -            | -                | -                | -         |    -0.09 | EmiliaQAQ, Jee, Starry, westmelon, z4kr    |
|            2 |     9455 | 2023-12-07 | TYLOO                     | L   | 0.036      | -            | -                | -                | -         |    -0.97 | EmiliaQAQ, Jee, Starry, westmelon, z4kr    |
|            1 |     9519 | 2023-12-06 | GR Gaming                 | W   | 0.029      | -            | -                | -                | -         |     0.13 | EmiliaQAQ, Jee, Starry, westmelon, z4kr    |

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
