### Roster Details<br />
Team Name: KZG<br />
Roster: Estate, Hassie, JiNxZiE, Mingovi, Samuukxs<br />
Region: [Asia]( ../standings_asia.md)<br />
<br />
Global Rank: [268](../standings_global.md)<br />
Regional Rank: [40]( ../standings_asia.md)<br />
Final Rank Value:  672.6<br />
<br />
Final Rank Value (672.6) = Starting Rank Value (745.2) + Head To Head Adjustments (-72.6)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.339[<sup>1</sup>](#table2)
- Bounty Collected: 0.236[<sup>2</sup>](#table1)
- Opponent Network: 0.025[<sup>2</sup>](#table1)
- LAN Wins: 0.079[<sup>2</sup>](#table1)

The average of these factors is 0.170<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 745.2
- 400 + ( ( 0.170 - 0.000 ) / ( 0.787 - 0.000 ) ) * 1600 = 745.2


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent                 | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                        |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           42 |      525 | 2024-05-22 | Bad News Kangaroos       | L   | 1.000      | -            | -                | -                | -         |    -7.24 | Estate, Hassie, JiNxZiE, Mingovi, Samuukxs    |
|           41 |      531 | 2024-05-22 | Bad News Kangaroos       | L   | 1.000      | -            | -                | -                | -         |    -7.72 | Estate, Hassie, JiNxZiE, Mingovi, Samuukxs    |
|           40 |     1213 | 2024-05-15 | DXA Esports              | W   | 1.000      | 0.333        | 0.005 (0.002)    | 0.196 (0.065)    | 0 (0.000) |    13.88 | Estate, Hassie, JiNxZiE, Mingovi, Samuukxs    |
|           39 |     1218 | 2024-05-15 | DXA Esports              | W   | 1.000      | 0.333        | 0.005 (0.002)    | 0.196 (0.065)    | 0 (0.000) |    15.15 | Estate, Hassie, JiNxZiE, Mingovi, Samuukxs    |
|           38 |     1668 | 2024-05-08 | Rooster                  | L   | 1.000      | -            | -                | -                | -         |    -8.17 | Estate, Hassie, JiNxZiE, Mingovi, Samuukxs    |
|           37 |     1672 | 2024-05-08 | Rooster                  | L   | 1.000      | -            | -                | -                | -         |    -8.76 | Estate, Hassie, JiNxZiE, Mingovi, Samuukxs    |
|           36 |     2321 | 2024-04-26 | Rooster                  | L   | 0.975      | -            | -                | -                | -         |    -9.15 | Estate, Hassie, KRAXYT, Mingovi, Samuukxs     |
|           35 |     2328 | 2024-04-25 | MIBR                     | L   | 0.973      | -            | -                | -                | -         |    -0.20 | Estate, Hassie, KRAXYT, Mingovi, Samuukxs     |
|           34 |     2917 | 2024-04-17 | Mindfreak                | L   | 0.915      | -            | -                | -                | -         |   -11.68 | Hassie, Jynx, KRAXYT, Mingovi, Samuukxs       |
|           33 |     2938 | 2024-04-17 | Altered Edge             | W   | 0.915      | 0.143        | 0.002 (0.000)    | 0.086 (0.011)    | 0 (0.000) |    11.89 | Hassie, Jynx, KRAXYT, Mingovi, Samuukxs       |
|           32 |     3276 | 2024-04-10 | Canon Event              | W   | 0.868      | 0.333        | 0.000 (0.000)    | 0.025 (0.007)    | 0 (0.000) |     6.32 | Estate, Hassie, Mingovi, pain, Samuukxs       |
|           31 |     3282 | 2024-04-10 | Canon Event              | W   | 0.868      | 0.333        | 0.000 (0.000)    | 0.025 (0.007)    | 0 (0.000) |     6.68 | Estate, Hassie, Mingovi, pain, Samuukxs       |
|           30 |     3657 | 2024-04-03 | Vantage Esports          | L   | 0.822      | -            | -                | -                | -         |   -12.14 | Estate, Hassie, Mingovi, pain, Samuukxs       |
|           29 |     3666 | 2024-04-03 | Vantage Esports          | L   | 0.821      | -            | -                | -                | -         |   -13.05 | Estate, Hassie, Mingovi, pain, Samuukxs       |
|           28 |     3926 | 2024-03-27 | FlyQuest                 | L   | 0.775      | -            | -                | -                | -         |    -0.40 | Estate, Hassie, Mingovi, pain, Samuukxs       |
|           27 |     3929 | 2024-03-27 | FlyQuest                 | L   | 0.775      | -            | -                | -                | -         |    -0.41 | Estate, Hassie, Mingovi, pain, Samuukxs       |
|           26 |     4112 | 2024-03-23 | Arcade Esports           | W   | 0.748      | 0.143        | 0.006 (0.001)    | 0.280 (0.030)    | 1 (0.748) |    13.41 | Hassie, KRAXYT, KZXL, Mingovi, Samuukxs       |
|           25 |     4114 | 2024-03-23 | DXA Esports              | L   | 0.748      | -            | -                | -                | -         |   -12.07 | Hassie, KRAXYT, KZXL, Mingovi, Samuukxs       |
|           24 |     4331 | 2024-03-18 | Arcade Esports           | W   | 0.715      | 0.143        | 0.006 (0.001)    | 0.280 (0.029)    | 0 (0.000) |    13.49 | Hassie, KRAXYT, KZXL, Mingovi, Samuukxs       |
|           23 |     4507 | 2024-03-15 | Arcade Esports           | L   | 0.694      | -            | -                | -                | -         |    -9.02 | Hassie, KRAXYT, KZXL, Mingovi, Samuukxs       |
|           22 |     4562 | 2024-03-14 | LE-LUX Esports           | W   | 0.688      | 0.143        | 0.000 (0.000)    | 0.072 (0.007)    | 0 (0.000) |     8.01 | Hassie, KRAXYT, KZXL, Mingovi, Samuukxs       |
|           21 |     5041 | 2024-03-06 | Arcade Esports           | L   | 0.636      | -            | -                | -                | -         |    -8.68 | Estate, Hassie, Mingovi, pain, Samuukxs       |
|           20 |     5047 | 2024-03-06 | Arcade Esports           | L   | 0.635      | -            | -                | -                | -         |    -9.17 | Estate, Hassie, Mingovi, pain, Samuukxs       |
|           19 |     5899 | 2024-02-21 | Mindfreak                | L   | 0.542      | -            | -                | -                | -         |    -8.47 | Estate, Hassie, Mingovi, pain, Samuukxs       |
|           18 |     5904 | 2024-02-21 | Mindfreak                | L   | 0.542      | -            | -                | -                | -         |    -8.88 | Estate, Hassie, Mingovi, pain, Samuukxs       |
|           17 |     5964 | 2024-02-20 | Altered Edge             | L   | 0.535      | -            | -                | -                | -         |   -10.51 | dpr, Hassie, KZXL, Mingovi, Samuukxs          |
|           16 |     5970 | 2024-02-19 | Underground Esports Club | W   | 0.535      | 0.143        | -                | 0.070 (0.005)    | 0 (0.000) |     4.84 | dpr, Hassie, KZXL, Mingovi, Samuukxs          |
|           15 |     6073 | 2024-02-18 | Arcade Esports           | L   | 0.522      | -            | -                | -                | -         |    -8.75 | dpr, Hassie, Lexon, Mingovi, Samuukxs         |
|           14 |     6086 | 2024-02-17 | douji feva               | W   | 0.521      | -            | -                | -                | 0 (0.000) |     2.21 | dpr, Hassie, Lexon, Mingovi, Samuukxs         |
|           13 |     6180 | 2024-02-16 | sunday school            | L   | 0.509      | -            | -                | -                | -         |    -9.41 | Hassie, KZXL, Mingovi, pain, Samuukxs         |
|           12 |     6248 | 2024-02-15 | sunday school            | W   | 0.502      | 0.143        | 0.007 (0.000)    | -                | -         |     6.54 | Hassie, KZXL, Mingovi, pain, Samuukxs         |
|           11 |     6252 | 2024-02-14 | Vantage Esports          | W   | 0.501      | -            | -                | -                | -         |     3.30 | Hassie, KZXL, Mingovi, pain, Samuukxs         |
|           10 |     6313 | 2024-02-13 | Mindfreak                | W   | 0.494      | 0.143        | 0.000 (0.000)    | 0.306 (0.022)    | -         |     7.13 | Hassie, KZXL, Mingovi, pain, Samuukxs         |
|            9 |     6360 | 2024-02-13 | TEAM RKON                | W   | 0.488      | -            | -                | -                | -         |     3.27 | Hassie, KZXL, Mingovi, pain, Samuukxs         |
|            8 |     6367 | 2024-02-12 | Golf Club                | W   | 0.488      | -            | -                | -                | -         |     3.11 | Hassie, KZXL, Mingovi, pain, Samuukxs         |
|            7 |     6438 | 2024-02-11 | Mindfreak                | L   | 0.475      | -            | -                | -                | -         |    -8.09 | Hassie, KZXL, Mingovi, pain, Samuukxs         |
|            6 |     7377 | 2024-01-24 | Vantage Esports          | L   | 0.355      | -            | -                | -                | -         |    -6.69 | Hassie, KZXL, Mingovi, pain, Samuukxs         |
|            5 |     7381 | 2024-01-24 | really normal            | W   | 0.355      | -            | -                | -                | -         |     1.51 | Hassie, KZXL, Mingovi, pain, Samuukxs         |
|            4 |     7972 | 2024-01-15 | Mindfreak                | L   | 0.295      | -            | -                | -                | -         |    -5.73 | constantinos, Hassie, Mingovi, pain, Samuukxs |
|            3 |     8144 | 2024-01-11 | 500x                     | L   | 0.274      | -            | -                | -                | -         |    -6.90 | Hassie, KZXL, Mingovi, pain, Samuukxs         |
|            2 |     8937 | 2023-12-15 | The Art of War           | L   | 0.094      | -            | -                | -                | -         |    -2.08 | constantinos, Hassie, KZXL, Mingovi, Samuukxs |
|            1 |     9805 | 2023-12-01 | Rooster                  | L   | 0.001      | -            | -                | -                | -         |    -0.01 | Hassie, KZXL, Mingovi, Omichella, Samuukxs    |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($3,375.85)
- Divide that value by the 5th highest value among all rosters ($300,806.11)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-05-22 |      1.000 | $450.00        | $450.00         |
| 2024-04-28 |      0.988 | $2,000.00      | $1,976.20       |
| 2024-03-23 |      0.748 | $977.39        | $731.48         |
| 2024-03-18 |      0.715 | $304.91        | $217.92         |
| 2023-12-01 |      0.001 | $250.00        | $0.24           |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
