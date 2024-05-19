### Roster Details<br />
Team Name: Lynn Vision Gaming<br />
Roster: EmiliaQAQ, Jee, Starry, westmelon, z4kr<br />
Region: [Asia]( ../standings_asia.md)<br />
<br />
Global Rank: [40](../standings_global.md)<br />
Regional Rank: [3]( ../standings_asia.md)<br />
Final Rank Value:  1143.0<br />
<br />
Final Rank Value (1143.0) = Starting Rank Value (1286.2) + Head To Head Adjustments (-143.2)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.553[<sup>1</sup>](#table2)
- Bounty Collected: 0.439[<sup>2</sup>](#table1)
- Opponent Network: 0.160[<sup>2</sup>](#table1)
- LAN Wins: 0.635[<sup>2</sup>](#table1)

The average of these factors is 0.447<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1286.2
- 400 + ( ( 0.447 - 0.000 ) / ( 0.806 - 0.000 ) ) * 1600 = 1286.2


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent                     | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                  |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           58 |      671 | 2024-04-21 | ATOX Esports                 | L   | 1.000      | -            | -                | -                | -         |   -18.99 | EmiliaQAQ, Jee, Starry, westmelon, z4kr |
|           57 |      741 | 2024-04-20 | The QUBE Esports             | W   | 1.000      | -            | -                | -                | 0 (0.000) |     2.55 | EmiliaQAQ, Jee, Starry, westmelon, z4kr |
|           56 |      754 | 2024-04-20 | The QUBE Esports             | W   | 1.000      | -            | -                | -                | -         |     2.62 | EmiliaQAQ, Jee, Starry, westmelon, z4kr |
|           55 |      776 | 2024-04-20 | Gen.G Esports                | W   | 1.000      | -            | -                | -                | -         |     0.98 | EmiliaQAQ, Jee, Starry, westmelon, z4kr |
|           54 |      887 | 2024-04-18 | Rare Atom                    | L   | 1.000      | -            | -                | -                | -         |   -26.16 | EmiliaQAQ, Jee, Starry, westmelon, z4kr |
|           53 |      903 | 2024-04-18 | TYLOO                        | L   | 1.000      | -            | -                | -                | -         |   -22.11 | EmiliaQAQ, Jee, Starry, westmelon, z4kr |
|           52 |      907 | 2024-04-18 | Rare Atom                    | L   | 1.000      | -            | -                | -                | -         |   -27.79 | EmiliaQAQ, Jee, Starry, westmelon, z4kr |
|           51 |      911 | 2024-04-17 | Gen.G Esports                | W   | 1.000      | -            | -                | -                | -         |     0.56 | EmiliaQAQ, Jee, Starry, westmelon, z4kr |
|           50 |     1308 | 2024-04-09 | G2 Esports                   | L   | 1.000      | -            | -                | -                | -         |    -1.01 | EmiliaQAQ, Jee, Starry, westmelon, z4kr |
|           49 |     1346 | 2024-04-08 | TYLOO                        | W   | 1.000      | 0.624        | 0.131 (0.082)    | 0.592 (0.369)    | 1 (1.000) |     7.27 | EmiliaQAQ, Jee, Starry, westmelon, z4kr |
|           48 |     1358 | 2024-04-07 | FURIA Esports                | L   | 1.000      | -            | -                | -                | -         |    -4.42 | EmiliaQAQ, Jee, Starry, westmelon, z4kr |
|           47 |     1546 | 2024-04-03 | The MongolZ                  | L   | 0.984      | -            | -                | -                | -         |    -4.59 | EmiliaQAQ, Jee, Starry, westmelon, z4kr |
|           46 |     1588 | 2024-04-02 | LYG Gaming                   | W   | 0.977      | -            | -                | -                | -         |     3.12 | EmiliaQAQ, Jee, Starry, westmelon, z4kr |
|           45 |     1594 | 2024-04-02 | ATOX Esports                 | W   | 0.976      | 0.143        | 0.112 (0.016)    | 0.769 (0.107)    | -         |     9.73 | EmiliaQAQ, Jee, Starry, westmelon, z4kr |
|           44 |     1644 | 2024-03-30 | GR Gaming                    | L   | 0.957      | -            | -                | -                | -         |   -25.88 | EmiliaQAQ, Jee, Starry, westmelon, z4kr |
|           43 |     1652 | 2024-03-30 | GR Gaming                    | W   | 0.957      | 0.417        | -                | 0.495 (0.198)    | -         |     3.88 | EmiliaQAQ, Jee, Starry, westmelon, z4kr |
|           42 |     1760 | 2024-03-27 | Clutch Gaming                | L   | 0.937      | -            | -                | -                | -         |   -27.78 | EmiliaQAQ, Jee, Starry, westmelon, z4kr |
|           41 |     1763 | 2024-03-27 | Clutch Gaming                | W   | 0.937      | 0.417        | -                | 0.216 (0.085)    | -         |     1.55 | EmiliaQAQ, Jee, Starry, westmelon, z4kr |
|           40 |     1826 | 2024-03-26 | MIRAI Gaming                 | W   | 0.931      | 0.417        | -                | 0.246 (0.095)    | -         |     1.21 | EmiliaQAQ, Jee, Starry, westmelon, z4kr |
|           39 |     1830 | 2024-03-26 | MIRAI Gaming                 | W   | 0.931      | 0.417        | -                | 0.246 (0.095)    | -         |     1.23 | EmiliaQAQ, Jee, Starry, westmelon, z4kr |
|           38 |     2068 | 2024-03-19 | The MongolZ                  | L   | 0.884      | -            | -                | -                | -         |    -3.76 | EmiliaQAQ, Jee, Starry, westmelon, z4KR |
|           37 |     2102 | 2024-03-18 | Gaimin Gladiators            | L   | 0.877      | -            | -                | -                | -         |   -10.97 | EmiliaQAQ, Jee, Starry, westmelon, z4KR |
|           36 |     2113 | 2024-03-17 | FURIA Esports                | W   | 0.873      | 1.000        | 0.384 (0.335)    | 0.361 (0.315)    | 1 (0.873) |    23.14 | EmiliaQAQ, Jee, Starry, westmelon, z4KR |
|           35 |     2143 | 2024-03-17 | HEROIC                       | L   | 0.871      | -            | -                | -                | -         |    -2.45 | EmiliaQAQ, Jee, Starry, westmelon, z4KR |
|           34 |     2632 | 2024-03-06 | -72C                         | W   | 0.797      | 0.417        | -                | 0.300 (0.100)    | -         |     1.77 | EmiliaQAQ, Jee, Starry, westmelon, z4kr |
|           33 |     2637 | 2024-03-06 | -72C                         | W   | 0.797      | 0.417        | -                | 0.300 (0.100)    | -         |     1.80 | EmiliaQAQ, Jee, Starry, westmelon, z4kr |
|           32 |     3008 | 2024-02-27 | FlyQuest                     | W   | 0.749      | 0.143        | 0.051 (0.005)    | -                | 1 (0.749) |    16.16 | EmiliaQAQ, Jee, Starry, westmelon, z4kr |
|           31 |     3010 | 2024-02-27 | The MongolZ                  | L   | 0.747      | -            | -                | -                | -         |    -2.48 | EmiliaQAQ, Jee, Starry, westmelon, z4kr |
|           30 |     3082 | 2024-02-25 | TYLOO                        | W   | 0.736      | 0.143        | 0.131 (0.014)    | -                | 1 (0.736) |     6.49 | EmiliaQAQ, Jee, Starry, westmelon, z4kr |
|           29 |     3085 | 2024-02-25 | Twisted Minds                | W   | 0.735      | -            | -                | -                | 1 (0.735) |     0.68 | EmiliaQAQ, Jee, Starry, westmelon, z4kr |
|           28 |     3316 | 2024-02-21 | Born In Far East             | W   | 0.704      | -            | -                | -                | -         |     1.09 | EmiliaQAQ, Jee, Starry, westmelon, z4kr |
|           27 |     3320 | 2024-02-21 | Born In Far East             | W   | 0.704      | -            | -                | -                | -         |     1.11 | EmiliaQAQ, Jee, Starry, westmelon, z4kr |
|           26 |     3359 | 2024-02-20 | High Five (Chinese team)     | W   | 0.697      | 0.417        | 0.045 (0.013)    | -                | -         |     2.31 | EmiliaQAQ, Jee, Starry, westmelon, z4kr |
|           25 |     3366 | 2024-02-20 | High Five (Chinese team)     | W   | 0.697      | 0.417        | 0.045 (0.013)    | -                | -         |     2.37 | EmiliaQAQ, Jee, Starry, westmelon, z4kr |
|           24 |     3501 | 2024-02-17 | High Five (Chinese team)     | L   | 0.677      | -            | -                | -                | -         |   -19.29 | EmiliaQAQ, Jee, Starry, westmelon, z4kr |
|           23 |     3553 | 2024-02-16 | Myth Avenue Gaming           | W   | 0.669      | -            | -                | -                | -         |     1.31 | EmiliaQAQ, Jee, Starry, westmelon, z4kr |
|           22 |     4123 | 2024-01-31 | Rare Atom                    | L   | 0.564      | -            | -                | -                | -         |   -16.53 | EmiliaQAQ, Jee, Starry, westmelon, z4kr |
|           21 |     4129 | 2024-01-31 | Team NKT                     | L   | 0.562      | -            | -                | -                | -         |   -16.52 | EmiliaQAQ, Jee, Starry, westmelon, z4kr |
|           20 |     4229 | 2024-01-28 | The MongolZ                  | L   | 0.543      | -            | -                | -                | -         |    -2.20 | EmiliaQAQ, Jee, Starry, westmelon, z4kr |
|           19 |     4234 | 2024-01-27 | TYLOO                        | W   | 0.541      | 0.435        | 0.131 (0.031)    | 0.592 (0.139)    | 1 (0.541) |     4.27 | EmiliaQAQ, Jee, Starry, westmelon, z4kr |
|           18 |     4335 | 2024-01-26 | Team NKT                     | W   | 0.530      | -            | -                | -                | 1 (0.530) |     1.05 | EmiliaQAQ, Jee, Starry, westmelon, z4kr |
|           17 |     4341 | 2024-01-26 | Những Chàng Trai Đeo Kính    | W   | 0.529      | -            | -                | -                | 1 (0.529) |     0.82 | EmiliaQAQ, Jee, Starry, westmelon, z4kr |
|           16 |     4522 | 2024-01-20 | TYLOO                        | W   | 0.495      | 0.143        | 0.131 (0.009)    | -                | -         |     3.60 | EmiliaQAQ, Jee, Starry, westmelon, z4kr |
|           15 |     4625 | 2024-01-19 | Wings Up Gaming              | W   | 0.482      | -            | -                | -                | -         |     0.77 | EmiliaQAQ, Jee, Starry, westmelon, z4kr |
|           14 |     4632 | 2024-01-18 | Nirvana Esports              | W   | 0.482      | -            | -                | -                | -         |     0.12 | EmiliaQAQ, Jee, Starry, westmelon, z4kr |
|           13 |     5262 | 2023-12-27 | NewHappy                     | L   | 0.330      | -            | -                | -                | -         |    -9.85 | EmiliaQAQ, Jee, Starry, westmelon, z4kr |
|           12 |     5268 | 2023-12-23 | TYLOO                        | W   | 0.308      | 0.143        | 0.131 (0.006)    | -                | -         |     2.18 | EmiliaQAQ, Jee, Starry, westmelon, z4kr |
|           11 |     5282 | 2023-12-22 | Rare Atom                    | W   | 0.302      | -            | -                | -                | -         |     0.48 | EmiliaQAQ, Jee, Starry, westmelon, z4kr |
|           10 |     5286 | 2023-12-22 | Secret (Chinese team)        | W   | 0.302      | -            | -                | -                | -         |     0.07 | EmiliaQAQ, Jee, Starry, westmelon, z4kr |
|            9 |     5780 | 2023-12-09 | The MongolZ                  | L   | 0.210      | -            | -                | -                | -         |    -0.73 | EmiliaQAQ, Jee, Starry, westmelon, z4kr |
|            8 |     5900 | 2023-12-07 | TYLOO                        | L   | 0.197      | -            | -                | -                | -         |    -4.87 | EmiliaQAQ, Jee, Starry, westmelon, z4kr |
|            7 |     5947 | 2023-12-06 | GR Gaming                    | W   | 0.190      | -            | -                | -                | -         |     0.43 | EmiliaQAQ, Jee, Starry, westmelon, z4kr |
|            6 |     6611 | 2023-11-20 | Octagonal Disposition Gaming | W   | 0.089      | -            | -                | -                | -         |     0.06 | EmiliaQAQ, Jee, Starry, westmelon, z4kr |
|            5 |     6846 | 2023-11-16 | The Huns Esports             | L   | 0.056      | -            | -                | -                | -         |    -1.57 | EmiliaQAQ, Jee, Starry, westmelon, z4kr |
|            4 |     6893 | 2023-11-15 | MungYu Esports               | W   | 0.050      | -            | -                | -                | -         |     0.02 | EmiliaQAQ, Jee, Starry, westmelon, z4kr |
|            3 |     7079 | 2023-11-10 | MOUZ                         | L   | 0.021      | -            | -                | -                | -         |    -0.02 | EmiliaQAQ, Jee, Starry, westmelon, z4kr |
|            2 |     7204 | 2023-11-08 | TYLOO                        | W   | 0.004      | -            | -                | -                | 1 (0.004) |     0.02 | EmiliaQAQ, Jee, Starry, westmelon, z4kr |
|            1 |     7217 | 2023-11-07 | Astralis                     | L   | 0.002      | -            | -                | -                | -         |    -0.06 | EmiliaQAQ, Jee, Starry, westmelon, z4kr |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($24,604.92)
- Divide that value by the 5th highest value among all rosters ($158,437.64)
- The final value (0.16) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-04-21 |      1.000 | $1,381.25      | $1,381.25       |
| 2024-04-14 |      1.000 | $5,000.00      | $5,000.00       |
| 2024-03-31 |      0.965 | $10,000.00     | $9,652.31       |
| 2024-01-28 |      0.543 | $12,000.00     | $6,519.44       |
| 2023-12-27 |      0.330 | $1,399.89      | $462.48         |
| 2023-12-10 |      0.217 | $5,000.00      | $1,084.49       |
| 2023-11-12 |      0.031 | $16,500.00     | $504.93         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
