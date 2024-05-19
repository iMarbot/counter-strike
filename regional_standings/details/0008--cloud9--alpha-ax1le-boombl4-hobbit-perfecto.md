### Roster Details<br />
Team Name: Cloud9<br />
Roster: alpha, Ax1Le, Boombl4, HObbit, Perfecto<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [8](../standings_global.md)<br />
Regional Rank: [8]( ../standings_europe.md)<br />
Final Rank Value:  1675.9<br />
<br />
Final Rank Value (1675.9) = Starting Rank Value (1794.3) + Head To Head Adjustments (-118.4)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.762[<sup>1</sup>](#table2)
- Bounty Collected: 0.664[<sup>2</sup>](#table1)
- Opponent Network: 0.447[<sup>2</sup>](#table1)
- LAN Wins: 0.938[<sup>2</sup>](#table1)

The average of these factors is 0.703<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1794.3
- 400 + ( ( 0.703 - 0.000 ) / ( 0.806 - 0.000 ) ) * 1600 = 1794.3


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent          | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins     | H2H Adj. | Roster                                       |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           39 |      735 | 2024-04-20 | Sashi Esport      | L   | 1.000      | -            | -                | -                | -            |   -29.99 | alpha, Ax1Le, Boombl4, HObbit, Perfecto      |
|           38 |      811 | 2024-04-19 | BetBoom Team      | W   | 1.000      | 0.143        | 0.571 (0.082)    | -                | -            |     4.61 | alpha, Ax1Le, Boombl4, HObbit, Perfecto      |
|           37 |      835 | 2024-04-19 | Sashi Esport      | L   | 1.000      | -            | -                | -                | -            |   -30.37 | alpha, Ax1Le, Boombl4, HObbit, Perfecto      |
|           36 |     1261 | 2024-04-09 | FaZe Clan         | L   | 1.000      | -            | -                | -                | -            |    -8.18 | Ax1Le, Boombl4, electroNic, HObbit, Perfecto |
|           35 |     1315 | 2024-04-08 | Wildcard Gaming   | W   | 1.000      | 0.624        | -                | 0.483 (0.302)    | true (1.000) |     0.31 | Ax1Le, Boombl4, electroNic, HObbit, Perfecto |
|           34 |     1356 | 2024-04-08 | FlyQuest          | L   | 1.000      | -            | -                | -                | -            |   -27.86 | Ax1Le, Boombl4, electroNic, HObbit, Perfecto |
|           33 |     1696 | 2024-03-28 | Team Vitality     | L   | 0.945      | -            | -                | -                | -            |   -10.74 | Ax1Le, Boombl4, electronic, Hobbit, Perfecto |
|           32 |     1896 | 2024-03-23 | Natus Vincere     | W   | 0.912      | 1.000        | 1.000 (0.912)    | 0.406 (0.371)    | true (0.912) |    20.13 | Ax1Le, Boombl4, electronic, Hobbit, Perfecto |
|           31 |     1949 | 2024-03-22 | G2 Esports        | W   | 0.904      | 1.000        | 0.866 (0.782)    | 0.477 (0.431)    | true (0.904) |    18.78 | Ax1Le, Boombl4, electronic, Hobbit, Perfecto |
|           30 |     1967 | 2024-03-21 | Gaimin Gladiators | W   | 0.899      | 1.000        | 0.194 (0.175)    | 0.989 (0.889)    | true (0.899) |     3.26 | Ax1Le, Boombl4, electronic, Hobbit, Perfecto |
|           29 |     1985 | 2024-03-21 | Team Spirit       | L   | 0.898      | -            | -                | -                | -            |    -9.13 | Ax1Le, Boombl4, electronic, Hobbit, Perfecto |
|           28 |     2093 | 2024-03-18 | SAW               | W   | 0.878      | 1.000        | 0.263 (0.231)    | 0.590 (0.518)    | true (0.878) |     5.73 | Ax1Le, Boombl4, electronic, Hobbit, Perfecto |
|           27 |     2118 | 2024-03-17 | Legacy            | W   | 0.873      | 1.000        | -                | 0.262 (0.229)    | true (0.873) |     1.06 | Ax1Le, Boombl4, electronic, Hobbit, Perfecto |
|           26 |     2150 | 2024-03-17 | Gaimin Gladiators | W   | 0.870      | 1.000        | 0.194 (0.169)    | 0.989 (0.860)    | true (0.870) |     2.49 | Ax1Le, Boombl4, electronic, Hobbit, Perfecto |
|           25 |     2525 | 2024-03-08 | SAW               | L   | 0.812      | -            | -                | -                | -            |   -21.23 | Ax1Le, Boombl4, electroNic, HObbit, Perfecto |
|           24 |     2629 | 2024-03-06 | Rare Atom         | W   | 0.798      | -            | -                | -                | -            |     0.15 | Ax1Le, Boombl4, electroNic, HObbit, Perfecto |
|           23 |     3365 | 2024-02-20 | Team Vitality     | W   | 0.697      | 0.143        | 1.000 (0.100)    | -                | true (0.697) |    14.93 | Ax1Le, Boombl4, electroNic, HObbit, Perfecto |
|           22 |     3402 | 2024-02-19 | Apeks             | W   | 0.692      | -            | -                | -                | true (0.692) |     2.88 | Ax1Le, Boombl4, electroNic, HObbit, Perfecto |
|           21 |     3419 | 2024-02-19 | Pera Esports      | W   | 0.691      | -            | -                | -                | true (0.691) |     0.28 | Ax1Le, Boombl4, electroNic, HObbit, Perfecto |
|           20 |     3907 | 2024-02-05 | Monte             | L   | 0.597      | -            | -                | -                | -            |   -16.79 | Ax1Le, Boombl4, electroNic, HObbit, Perfecto |
|           19 |     3931 | 2024-02-04 | MOUZ              | L   | 0.590      | -            | -                | -                | -            |    -6.95 | Ax1Le, Boombl4, electroNic, HObbit, Perfecto |
|           18 |     4035 | 2024-02-02 | Virtus.pro        | W   | 0.578      | 1.000        | 0.454 (0.263)    | 0.416 (0.240)    | -            |     7.99 | Ax1Le, Boombl4, electroNic, HObbit, Perfecto |
|           17 |     4076 | 2024-02-01 | BetBoom Team      | W   | 0.571      | 1.000        | 0.571 (0.326)    | 0.824 (0.470)    | -            |     3.36 | Ax1Le, Boombl4, electroNic, HObbit, Perfecto |
|           16 |     4113 | 2024-01-31 | Rebels Gaming     | L   | 0.565      | -            | -                | -                | -            |   -17.34 | Ax1Le, Boombl4, electroNic, HObbit, Perfecto |
|           15 |     4307 | 2024-01-26 | BIG               | L   | 0.532      | -            | -                | -                | -            |   -14.66 | Ax1Le, Boombl4, electroNic, HObbit, Perfecto |
|           14 |     4356 | 2024-01-25 | Virtus.pro        | L   | 0.525      | -            | -                | -                | -            |    -9.94 | Ax1Le, Boombl4, electroNic, HObbit, Perfecto |
|           13 |     4375 | 2024-01-24 | HEROIC            | W   | 0.519      | 0.581        | 0.243 (0.073)    | 0.537 (0.162)    | -            |     5.97 | Ax1Le, Boombl4, electroNic, HObbit, Perfecto |
|           12 |     4602 | 2024-01-19 | BetBoom Team      | W   | 0.485      | -            | -                | -                | -            |     2.46 | Ax1Le, Boombl4, electroNic, HObbit, Perfecto |
|           11 |     4653 | 2024-01-18 | 3DMAX             | W   | 0.478      | -            | -                | -                | -            |     0.15 | Ax1Le, Boombl4, electroNic, HObbit, Perfecto |
|           10 |     4669 | 2024-01-18 | OG                | W   | 0.478      | -            | -                | -                | -            |     1.07 | Ax1Le, Boombl4, electroNic, HObbit, Perfecto |
|            9 |     5617 | 2023-12-14 | Team Vitality     | L   | 0.243      | -            | -                | -                | -            |    -2.57 | Ax1Le, Boombl4, electroNic, HObbit, Perfecto |
|            8 |     5657 | 2023-12-12 | ENCE              | W   | 0.235      | -            | -                | -                | -            |     0.03 | Ax1Le, Boombl4, electroNic, HObbit, Perfecto |
|            7 |     5854 | 2023-12-08 | BetBoom Team      | L   | 0.203      | -            | -                | -                | -            |    -5.44 | Ax1Le, Boombl4, electroNic, HObbit, Perfecto |
|            6 |     5893 | 2023-12-07 | MIBR              | L   | 0.197      | -            | -                | -                | -            |    -4.22 | Ax1Le, Boombl4, electroNic, HObbit, Perfecto |
|            5 |     6006 | 2023-12-05 | GamerLegion       | W   | 0.183      | -            | -                | -                | -            |     1.35 | Ax1Le, Boombl4, electroNic, HObbit, Perfecto |
|            4 |     6435 | 2023-11-25 | Team Vitality     | L   | 0.118      | -            | -                | -                | -            |    -1.33 | Ax1Le, Boombl4, electroNic, HObbit, Perfecto |
|            3 |     6487 | 2023-11-24 | HEROIC            | W   | 0.111      | -            | -                | -                | -            |     0.00 | Ax1Le, Boombl4, electroNic, HObbit, Perfecto |
|            2 |     6532 | 2023-11-23 | FaZe Clan         | L   | 0.103      | -            | -                | -                | -            |    -0.79 | Ax1Le, Boombl4, electroNic, HObbit, Perfecto |
|            1 |     6575 | 2023-11-22 | Natus Vincere     | W   | 0.097      | -            | -                | -                | -            |     2.18 | Ax1Le, Boombl4, electroNic, HObbit, Perfecto |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($77,230.68)
- Divide that value by the 5th highest value among all rosters ($158,437.64)
- The final value (0.49) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-04-14 |      1.000 | $5,000.00      | $5,000.00       |
| 2024-03-31 |      0.965 | $45,000.00     | $43,435.42      |
| 2024-03-10 |      0.826 | $7,500.00      | $6,191.84       |
| 2024-02-11 |      0.638 | $10,000.00     | $6,380.09       |
| 2024-01-28 |      0.545 | $8,500.00      | $4,633.29       |
| 2023-12-17 |      0.264 | $25,000.00     | $6,603.01       |
| 2023-11-26 |      0.125 | $40,000.00     | $4,987.04       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
