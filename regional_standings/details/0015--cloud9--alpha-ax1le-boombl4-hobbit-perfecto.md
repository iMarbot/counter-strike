### Roster Details<br />
Team Name: Cloud9<br />
Roster: alpha, Ax1Le, Boombl4, HObbit, Perfecto<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [15](../standings_global.md)<br />
Regional Rank: [11]( ../standings_europe.md)<br />
Final Rank Value:  1484.6<br />
<br />
Final Rank Value (1484.6) = Starting Rank Value (1494.6) + Head To Head Adjustments (-10.0)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.579[<sup>1</sup>](#table2)
- Bounty Collected: 0.570[<sup>2</sup>](#table1)
- Opponent Network: 0.284[<sup>2</sup>](#table1)
- LAN Wins: 0.722[<sup>2</sup>](#table1)

The average of these factors is 0.539<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1494.6
- 400 + ( ( 0.539 - 0.000 ) / ( 0.787 - 0.000 ) ) * 1600 = 1494.6


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent          | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                       |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           36 |     2656 | 2024-04-20 | Sashi Esport      | L   | 0.936      | -            | -                | -                | -         |   -26.07 | alpha, Ax1Le, Boombl4, HObbit, Perfecto      |
|           35 |     2745 | 2024-04-19 | BetBoom Team      | W   | 0.930      | 0.143        | 0.390 (0.052)    | -                | -         |     8.08 | alpha, Ax1Le, Boombl4, HObbit, Perfecto      |
|           34 |     2770 | 2024-04-19 | Sashi Esport      | L   | 0.929      | -            | -                | -                | -         |   -26.56 | alpha, Ax1Le, Boombl4, HObbit, Perfecto      |
|           33 |     3290 | 2024-04-09 | FaZe Clan         | L   | 0.867      | -            | -                | -                | -         |    -2.54 | Ax1Le, Boombl4, electroNic, HObbit, Perfecto |
|           32 |     3353 | 2024-04-08 | Wildcard Gaming   | W   | 0.860      | 0.624        | -                | 0.525 (0.282)    | 1 (0.860) |     0.97 | Ax1Le, Boombl4, electroNic, HObbit, Perfecto |
|           31 |     3399 | 2024-04-07 | FlyQuest          | L   | 0.854      | -            | -                | -                | -         |   -17.32 | Ax1Le, Boombl4, electroNic, HObbit, Perfecto |
|           30 |     3836 | 2024-03-28 | Team Vitality     | L   | 0.784      | -            | -                | -                | -         |    -4.41 | Ax1Le, Boombl4, electronic, Hobbit, Perfecto |
|           29 |     4084 | 2024-03-23 | Natus Vincere     | W   | 0.751      | 1.000        | 1.000 (0.751)    | 0.253 (0.190)    | 1 (0.751) |    20.12 | Ax1Le, Boombl4, electronic, Hobbit, Perfecto |
|           28 |     4142 | 2024-03-22 | G2 Esports        | W   | 0.743      | 1.000        | 0.468 (0.348)    | 0.392 (0.291)    | 1 (0.743) |    19.35 | Ax1Le, Boombl4, electronic, Hobbit, Perfecto |
|           27 |     4167 | 2024-03-21 | Gaimin Gladiators | W   | 0.738      | 1.000        | 0.092 (0.068)    | 0.727 (0.536)    | 1 (0.738) |     5.06 | Ax1Le, Boombl4, electronic, Hobbit, Perfecto |
|           26 |     4190 | 2024-03-21 | Team Spirit       | L   | 0.737      | -            | -                | -                | -         |    -2.10 | Ax1Le, Boombl4, electronic, Hobbit, Perfecto |
|           25 |     4315 | 2024-03-18 | SAW               | W   | 0.717      | 1.000        | 0.112 (0.080)    | 0.388 (0.278)    | 1 (0.717) |     7.93 | Ax1Le, Boombl4, electronic, Hobbit, Perfecto |
|           24 |     4343 | 2024-03-17 | Legacy            | W   | 0.711      | 1.000        | -                | 0.307 (0.219)    | 1 (0.711) |     2.00 | Ax1Le, Boombl4, electronic, Hobbit, Perfecto |
|           23 |     4392 | 2024-03-17 | Gaimin Gladiators | W   | 0.709      | 1.000        | 0.092 (0.065)    | 0.727 (0.515)    | 1 (0.709) |     4.32 | Ax1Le, Boombl4, electronic, Hobbit, Perfecto |
|           22 |     4872 | 2024-03-08 | SAW               | L   | 0.651      | -            | -                | -                | -         |   -13.89 | Ax1Le, Boombl4, electroNic, HObbit, Perfecto |
|           21 |     5015 | 2024-03-06 | Rare Atom         | W   | 0.637      | -            | -                | -                | -         |     0.31 | Ax1Le, Boombl4, electroNic, HObbit, Perfecto |
|           20 |     5946 | 2024-02-20 | Team Vitality     | W   | 0.536      | 0.143        | 0.696 (0.053)    | -                | 1 (0.536) |    14.59 | Ax1Le, Boombl4, electroNic, HObbit, Perfecto |
|           19 |     5994 | 2024-02-19 | Apeks             | W   | 0.531      | -            | -                | -                | 1 (0.531) |     3.31 | Ax1Le, Boombl4, electroNic, HObbit, Perfecto |
|           18 |     6014 | 2024-02-19 | Pera Esports      | W   | 0.530      | -            | -                | -                | 1 (0.530) |     0.72 | Ax1Le, Boombl4, electroNic, HObbit, Perfecto |
|           17 |     6637 | 2024-02-05 | Monte             | L   | 0.436      | -            | -                | -                | -         |   -10.16 | Ax1Le, Boombl4, electroNic, HObbit, Perfecto |
|           16 |     6675 | 2024-02-04 | MOUZ              | L   | 0.429      | -            | -                | -                | -         |    -0.93 | Ax1Le, Boombl4, electroNic, HObbit, Perfecto |
|           15 |     6823 | 2024-02-02 | Virtus.pro        | W   | 0.417      | 1.000        | 0.271 (0.113)    | 0.331 (0.138)    | -         |     9.82 | Ax1Le, Boombl4, electroNic, HObbit, Perfecto |
|           14 |     6882 | 2024-02-01 | BetBoom Team      | W   | 0.410      | 1.000        | 0.390 (0.160)    | 0.712 (0.292)    | -         |     5.50 | Ax1Le, Boombl4, electroNic, HObbit, Perfecto |
|           13 |     6934 | 2024-01-31 | Rebels Gaming     | L   | 0.404      | -            | -                | -                | -         |   -11.60 | Ax1Le, Boombl4, electroNic, HObbit, Perfecto |
|           12 |     7245 | 2024-01-26 | BIG               | L   | 0.371      | -            | -                | -                | -         |    -7.33 | Ax1Le, Boombl4, electroNic, HObbit, Perfecto |
|           11 |     7312 | 2024-01-25 | Virtus.pro        | L   | 0.363      | -            | -                | -                | -         |    -2.94 | Ax1Le, Boombl4, electroNic, HObbit, Perfecto |
|           10 |     7337 | 2024-01-24 | HEROIC            | W   | 0.358      | 0.581        | 0.322 (0.067)    | 0.463 (0.096)    | -         |     9.05 | Ax1Le, Boombl4, electroNic, HObbit, Perfecto |
|            9 |     7654 | 2024-01-19 | BetBoom Team      | W   | 0.324      | -            | -                | -                | -         |     4.28 | Ax1Le, Boombl4, electroNic, HObbit, Perfecto |
|            8 |     7715 | 2024-01-18 | 3DMAX             | W   | 0.317      | -            | -                | -                | -         |     0.45 | Ax1Le, Boombl4, electroNic, HObbit, Perfecto |
|            7 |     7737 | 2024-01-18 | OG                | W   | 0.317      | -            | -                | -                | -         |     1.55 | Ax1Le, Boombl4, electroNic, HObbit, Perfecto |
|            6 |     9022 | 2023-12-15 | MOUZ              | L   | 0.088      | -            | -                | -                | -         |    -0.17 | Ax1Le, Boombl4, electroNic, HObbit, Perfecto |
|            5 |     9057 | 2023-12-14 | Team Vitality     | L   | 0.082      | -            | -                | -                | -         |    -0.32 | Ax1Le, Boombl4, electroNic, HObbit, Perfecto |
|            4 |     9120 | 2023-12-12 | ENCE              | W   | 0.074      | -            | -                | -                | -         |     0.01 | Ax1Le, Boombl4, electroNic, HObbit, Perfecto |
|            3 |     9395 | 2023-12-08 | BetBoom Team      | L   | 0.042      | -            | -                | -                | -         |    -0.77 | Ax1Le, Boombl4, electroNic, HObbit, Perfecto |
|            2 |     9447 | 2023-12-07 | MIBR              | L   | 0.036      | -            | -                | -                | -         |    -0.40 | Ax1Le, Boombl4, electroNic, HObbit, Perfecto |
|            1 |     9600 | 2023-12-05 | GamerLegion       | W   | 0.022      | -            | -                | -                | -         |     0.12 | Ax1Le, Boombl4, electroNic, HObbit, Perfecto |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($56,244.73)
- Divide that value by the 5th highest value among all rosters ($300,806.11)
- The final value (0.19) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-04-14 |      0.895 | $5,000.00      | $4,475.81       |
| 2024-03-31 |      0.804 | $45,000.00     | $36,175.00      |
| 2024-03-10 |      0.665 | $7,500.00      | $4,983.85       |
| 2024-02-11 |      0.477 | $10,000.00     | $4,769.44       |
| 2024-01-28 |      0.384 | $8,500.00      | $3,264.24       |
| 2023-12-17 |      0.103 | $25,000.00     | $2,576.39       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
