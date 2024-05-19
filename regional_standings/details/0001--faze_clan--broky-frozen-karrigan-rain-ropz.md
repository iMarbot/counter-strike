### Roster Details<br />
Team Name: FaZe Clan<br />
Roster: broky, frozen, karrigan, rain, ropz<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [1](../standings_global.md)<br />
Regional Rank: [1]( ../standings_europe.md)<br />
Final Rank Value:  1935.9<br />
<br />
Final Rank Value (1935.9) = Starting Rank Value (2000.0) + Head To Head Adjustments (-64.1)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 1.000[<sup>1</sup>](#table2)
- Bounty Collected: 0.817[<sup>2</sup>](#table1)
- Opponent Network: 0.409[<sup>2</sup>](#table1)
- LAN Wins: 1.000[<sup>2</sup>](#table1)

The average of these factors is 0.806<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 2000.0
- 400 + ( ( 0.806 - 0.000 ) / ( 0.806 - 0.000 ) ) * 1600 = 2000.0


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent          | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                               |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           43 |      427 | 2024-04-26 | Eternal Fire      | W   | 1.000      | 0.889        | 0.409 (0.364)    | 0.462 (0.411)    | 1 (1.000) |     8.67 | broky, frozen, karrigan, rain, ropz  |
|           42 |      467 | 2024-04-25 | Virtus.pro        | W   | 1.000      | 0.889        | 0.454 (0.404)    | 0.416 (0.370)    | 1 (1.000) |     5.94 | broky, frozen, karrigan, rain, ropz  |
|           41 |      527 | 2024-04-24 | Astralis          | L   | 1.000      | -            | -                | -                | -         |   -27.57 | broky, frozen, karrigan, rain, ropz  |
|           40 |      567 | 2024-04-23 | Imperial Esports  | W   | 1.000      | 0.889        | 0.674 (0.599)    | 0.549 (0.488)    | 1 (1.000) |     1.96 | broky, frozen, karrigan, rain, ropz  |
|           39 |     1079 | 2024-04-14 | MOUZ              | W   | 1.000      | 0.624        | 0.891 (0.556)    | -                | 1 (1.000) |    13.34 | broky, frozen, karrigan, rain, ropz  |
|           38 |     1120 | 2024-04-13 | Astralis          | W   | 1.000      | -            | -                | -                | 1 (1.000) |     3.37 | broky, frozen, karrigan, rain, ropz  |
|           37 |     1153 | 2024-04-12 | Team Liquid       | W   | 1.000      | 0.624        | -                | 0.546 (0.341)    | 1 (1.000) |     1.67 | broky, frozen, karrigan, rain, ropz  |
|           36 |     1243 | 2024-04-10 | FlyQuest          | W   | 1.000      | 0.624        | -                | 0.547 (0.341)    | 1 (1.000) |     1.63 | broky, frozen, karrigan, rain, ropz  |
|           35 |     1261 | 2024-04-09 | Cloud9            | W   | 1.000      | -            | -                | -                | 1 (1.000) |     8.18 | broky, frozen, karrigan, rain, ropz  |
|           34 |     1311 | 2024-04-09 | Astralis          | L   | 1.000      | -            | -                | -                | -         |   -28.73 | broky, frozen, karrigan, rain, ropz  |
|           33 |     1351 | 2024-04-08 | Nemiga Gaming     | W   | 1.000      | 0.624        | 0.680 (0.425)    | 0.910 (0.568)    | 1 (1.000) |     0.58 | broky, frozen, karrigan, rain, ropz  |
|           32 |     1614 | 2024-03-31 | Natus Vincere     | L   | 0.965      | -            | -                | -                | -         |   -15.87 | broky, frozen, karrigan, rain, ropz  |
|           31 |     1633 | 2024-03-30 | Team Vitality     | W   | 0.958      | 1.000        | 1.000 (0.958)    | 0.353 (0.338)    | 1 (0.958) |    11.70 | broky, frozen, karrigan, rain, ropz  |
|           30 |     1691 | 2024-03-28 | Team Spirit       | W   | 0.945      | 1.000        | 1.000 (0.945)    | 0.433 (0.410)    | -         |    12.71 | broky, frozen, karrigan, rain, ropz  |
|           29 |     1865 | 2024-03-24 | Complexity Gaming | W   | 0.917      | -            | -                | -                | -         |     2.33 | broky, frozen, karrigan, rain, ropz  |
|           28 |     1917 | 2024-03-23 | Imperial Esports  | W   | 0.910      | 1.000        | 0.674 (0.613)    | 0.549 (0.499)    | -         |     2.48 | broky, frozen, karrigan, rain, ropz  |
|           27 |     1946 | 2024-03-22 | Eternal Fire      | L   | 0.904      | -            | -                | -                | -         |   -19.82 | broky, frozen, karrigan, rain, ropz  |
|           26 |     1964 | 2024-03-21 | FURIA Esports     | W   | 0.899      | 1.000        | -                | 0.361 (0.325)    | -         |     3.01 | broky, frozen, karrigan, rain, ropz  |
|           25 |     1988 | 2024-03-21 | HEROIC            | L   | 0.898      | -            | -                | -                | -         |   -22.75 | broky, frozen, karrigan, rain, ropz  |
|           24 |     3542 | 2024-02-16 | Eternal Fire      | W   | 0.671      | -            | -                | -                | -         |     5.57 | broky, frozen, karrigan, rain, ropz  |
|           23 |     3597 | 2024-02-15 | G2 Esports        | L   | 0.664      | -            | -                | -                | -         |   -13.41 | broky, frozen, karrigan, rain, ropz  |
|           22 |     3622 | 2024-02-14 | Team Falcons      | W   | 0.658      | -            | -                | -                | -         |     0.81 | broky, frozen, karrigan, rain, ropz  |
|           21 |     3654 | 2024-02-14 | 9Pandas           | W   | 0.657      | -            | -                | -                | -         |     0.18 | broky, frozen, karrigan, rain, ropz  |
|           20 |     3755 | 2024-02-11 | Team Spirit       | L   | 0.638      | -            | -                | -                | -         |   -13.63 | broky, frozen, karrigan, rain, ropz  |
|           19 |     3775 | 2024-02-10 | MOUZ              | W   | 0.631      | 1.000        | 0.891 (0.563)    | -                | -         |     6.55 | broky, frozen, karrigan, rain, ropz  |
|           18 |     3795 | 2024-02-09 | G2 Esports        | W   | 0.624      | 1.000        | 0.866 (0.541)    | -                | -         |     6.71 | broky, frozen, karrigan, rain, ropz  |
|           17 |     3861 | 2024-02-06 | Team Spirit       | L   | 0.605      | -            | -                | -                | -         |   -13.27 | broky, frozen, karrigan, rain, ropz  |
|           16 |     3914 | 2024-02-04 | Eternal Fire      | W   | 0.592      | -            | -                | -                | -         |     4.84 | broky, frozen, karrigan, rain, ropz  |
|           15 |     3976 | 2024-02-03 | Rebels Gaming     | W   | 0.585      | -            | -                | -                | -         |     0.15 | broky, frozen, karrigan, rain, ropz  |
|           14 |     4267 | 2024-01-27 | Team Liquid       | W   | 0.538      | -            | -                | -                | -         |     0.61 | broky, frozen, karrigan, rain, ropz  |
|           13 |     4314 | 2024-01-26 | GamerLegion       | W   | 0.532      | -            | -                | -                | -         |     1.55 | broky, frozen, karrigan, rain, ropz  |
|           12 |     4358 | 2024-01-25 | Team Spirit       | W   | 0.524      | -            | -                | -                | -         |     4.71 | broky, frozen, karrigan, rain, ropz  |
|           11 |     4402 | 2024-01-24 | GamerLegion       | L   | 0.517      | -            | -                | -                | -         |   -14.80 | broky, frozen, karrigan, rain, ropz  |
|           10 |     5370 | 2023-12-17 | Team Vitality     | L   | 0.264      | -            | -                | -                | -         |    -5.14 | broky, frozen, karrigan, rain, ropz  |
|            9 |     5616 | 2023-12-14 | G2 Esports        | W   | 0.244      | -            | -                | -                | -         |     2.69 | broky, frozen, karrigan, rain, ropz  |
|            8 |     5653 | 2023-12-13 | HEROIC            | W   | 0.237      | -            | -                | -                | -         |     0.00 | broky, frozen, karrigan, rain, ropz  |
|            7 |     6391 | 2023-11-26 | Team Vitality     | L   | 0.125      | -            | -                | -                | -         |    -2.50 | broky, karrigan, rain, ropz, Twistzz |
|            6 |     6419 | 2023-11-25 | Complexity Gaming | W   | 0.119      | -            | -                | -                | -         |     0.26 | broky, karrigan, rain, ropz, Twistzz |
|            5 |     6532 | 2023-11-23 | Cloud9            | W   | 0.103      | -            | -                | -                | -         |     0.79 | broky, karrigan, rain, ropz, Twistzz |
|            4 |     6576 | 2023-11-22 | Ninjas in Pyjamas | W   | 0.096      | -            | -                | -                | -         |     0.00 | broky, karrigan, rain, ropz, Twistzz |
|            3 |     7012 | 2023-11-12 | MOUZ              | W   | 0.031      | -            | -                | -                | -         |     0.32 | broky, karrigan, rain, ropz, Twistzz |
|            2 |     7023 | 2023-11-12 | Team Falcons      | W   | 0.029      | -            | -                | -                | -         |     0.03 | broky, karrigan, rain, ropz, Twistzz |
|            1 |     7151 | 2023-11-09 | MOUZ              | W   | 0.009      | -            | -                | -                | -         |     0.10 | broky, karrigan, rain, ropz, Twistzz |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($475,473.61)
- Divide that value by the 5th highest value among all rosters ($158,437.64)
- The final value (1.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-04-14 |      1.000 | $100,000.00    | $100,000.00     |
| 2024-03-31 |      0.965 | $170,000.00    | $164,089.35     |
| 2024-02-11 |      0.638 | $180,000.00    | $114,841.67     |
| 2024-01-28 |      0.545 | $22,500.00     | $12,264.58      |
| 2023-12-17 |      0.264 | $250,000.00    | $66,030.09      |
| 2023-11-26 |      0.125 | $85,000.00     | $10,597.45      |
| 2023-11-12 |      0.031 | $250,000.00    | $7,650.46       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
