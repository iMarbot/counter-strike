### Roster Details<br />
Team Name: OG<br />
Roster: F1KU, HeavyGod, k1to, MoDo, Nexius<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [33](../standings_global.md)<br />
Regional Rank: [23]( ../standings_europe.md)<br />
Final Rank Value:  1201.6<br />
<br />
Final Rank Value (1201.6) = Starting Rank Value (1196.1) + Head To Head Adjustments (5.5)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.642[<sup>1</sup>](#table2)
- Bounty Collected: 0.492[<sup>2</sup>](#table1)
- Opponent Network: 0.179[<sup>2</sup>](#table1)
- LAN Wins: 0.253[<sup>2</sup>](#table1)

The average of these factors is 0.392<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1196.1
- 400 + ( ( 0.392 - 0.000 ) / ( 0.787 - 0.000 ) ) * 1600 = 1196.1


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent           | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                               |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           36 |      103 | 2024-05-28 | ATOX Esports       | L   | 1.000      | -            | -                | -                | -         |   -20.56 | F1KU, HeavyGod, k1to, MoDo, Nexius   |
|           35 |      817 | 2024-05-19 | paiN Gaming        | L   | 1.000      | -            | -                | -                | -         |    -6.43 | F1KU, HeavyGod, k1to, MoDo, Nexius   |
|           34 |      844 | 2024-05-18 | Team Liquid        | L   | 1.000      | -            | -                | -                | -         |    -3.36 | F1KU, HeavyGod, k1to, MoDo, Nexius   |
|           33 |     2004 | 2024-05-01 | Insilio            | L   | 1.000      | -            | -                | -                | -         |   -25.62 | F1KU, HeavyGod, k1to, MoDo, Nexius   |
|           32 |     2066 | 2024-04-30 | Sashi Esport       | L   | 1.000      | -            | -                | -                | -         |   -16.59 | F1KU, HeavyGod, k1to, MoDo, Nexius   |
|           31 |     2660 | 2024-04-20 | MIBR               | L   | 0.936      | -            | -                | -                | -         |    -4.10 | F1KU, HeavyGod, k1to, MoDo, Nexius   |
|           30 |     2717 | 2024-04-19 | 9z Team            | W   | 0.933      | 0.589        | 0.107 (0.059)    | 0.547 (0.300)    | 1 (0.933) |    13.60 | F1KU, HeavyGod, k1to, MoDo, Nexius   |
|           29 |     2734 | 2024-04-19 | Monte              | W   | 0.931      | 0.589        | 0.181 (0.099)    | 0.387 (0.212)    | 1 (0.931) |    13.97 | F1KU, HeavyGod, k1to, MoDo, Nexius   |
|           28 |     2802 | 2024-04-18 | MIBR               | L   | 0.925      | -            | -                | -                | -         |    -4.20 | F1KU, HeavyGod, k1to, MoDo, Nexius   |
|           27 |     3046 | 2024-04-14 | Aurora Gaming      | L   | 0.896      | -            | -                | -                | -         |    -8.34 | F1KU, HeavyGod, k1to, MoDo, Nexius   |
|           26 |     3082 | 2024-04-13 | BetBoom Team       | W   | 0.890      | 0.687        | 0.390 (0.238)    | 0.712 (0.435)    | 0 (0.000) |    17.00 | F1KU, HeavyGod, k1to, MoDo, Nexius   |
|           25 |     3113 | 2024-04-13 | BIG                | W   | 0.889      | 0.687        | 0.215 (0.131)    | 0.304 (0.185)    | 0 (0.000) |    19.08 | F1KU, HeavyGod, k1to, MoDo, Nexius   |
|           24 |     3149 | 2024-04-12 | Ninjas in Pyjamas  | W   | 0.883      | 0.687        | 0.118 (0.072)    | 0.285 (0.173)    | 0 (0.000) |     9.92 | F1KU, HeavyGod, k1to, MoDo, Nexius   |
|           23 |     3262 | 2024-04-10 | ENCE               | W   | 0.869      | 0.687        | 0.202 (0.120)    | 0.280 (0.167)    | 0 (0.000) |    20.09 | F1KU, HeavyGod, k1to, MoDo, Nexius   |
|           22 |     3369 | 2024-04-08 | Aurora Gaming      | L   | 0.857      | -            | -                | -                | -         |    -6.99 | F1KU, HeavyGod, k1to, MoDo, Nexius   |
|           21 |     4784 | 2024-03-10 | SAW                | L   | 0.664      | -            | -                | -                | -         |    -5.68 | F1KU, k1to, Nexius, regali, s0und    |
|           20 |     4843 | 2024-03-09 | HEROIC             | W   | 0.657      | 0.535        | 0.322 (0.113)    | 0.463 (0.163)    | 0 (0.000) |    19.69 | F1KU, HeavyGod, k1to, Nexius, regali |
|           19 |     4935 | 2024-03-07 | Complexity Gaming  | W   | 0.644      | 0.535        | 0.260 (0.090)    | 0.219 (0.075)    | 0 (0.000) |    17.88 | F1KU, HeavyGod, k1to, Nexius, regali |
|           18 |     5883 | 2024-02-21 | GamerLegion        | L   | 0.543      | -            | -                | -                | -         |    -6.79 | F1KU, HeavyGod, k1to, Nexius, regali |
|           17 |     5958 | 2024-02-20 | Gaimin Gladiators  | L   | 0.536      | -            | -                | -                | -         |    -6.75 | F1KU, HeavyGod, k1to, Nexius, regali |
|           16 |     5997 | 2024-02-19 | ex-Preasy Esport   | W   | 0.531      | 0.143        | 0.052 (0.004)    | -                | 1 (0.531) |     3.41 | F1KU, HeavyGod, k1to, Nexius, regali |
|           15 |     6017 | 2024-02-19 | Apeks              | L   | 0.529      | -            | -                | -                | -         |    -7.17 | F1KU, HeavyGod, k1to, Nexius, regali |
|           14 |     7408 | 2024-01-23 | Team Falcons       | L   | 0.351      | -            | -                | -                | -         |    -1.85 | F1KU, HeavyGod, k1to, Nexius, regali |
|           13 |     7479 | 2024-01-22 | Team Vitality      | L   | 0.343      | -            | -                | -                | -         |    -0.27 | F1KU, HeavyGod, k1to, Nexius, regali |
|           12 |     7570 | 2024-01-20 | Nexus Gaming       | W   | 0.331      | 0.143        | -                | 0.857 (0.041)    | 0 (0.000) |     1.92 | F1KU, HeavyGod, k1to, Nexius, regali |
|           11 |     7591 | 2024-01-20 | BetBoom Team       | L   | 0.330      | -            | -                | -                | -         |    -2.12 | F1KU, HeavyGod, k1to, Nexius, regali |
|           10 |     7661 | 2024-01-19 | 3DMAX              | W   | 0.323      | 0.143        | 0.106 (0.005)    | -                | -         |     2.08 | F1KU, HeavyGod, k1to, Nexius, regali |
|            9 |     7706 | 2024-01-18 | JANO Esports       | W   | 0.318      | -            | -                | -                | -         |     0.24 | F1KU, HeavyGod, k1to, Nexius, regali |
|            8 |     7737 | 2024-01-18 | Cloud9             | L   | 0.317      | -            | -                | -                | -         |    -1.55 | F1KU, HeavyGod, k1to, Nexius, regali |
|            7 |     8029 | 2024-01-13 | Gaimin Gladiators  | L   | 0.285      | -            | -                | -                | -         |    -3.42 | F1KU, HeavyGod, k1to, Nexius, regali |
|            6 |     8034 | 2024-01-13 | Permitta Esports   | W   | 0.284      | 0.143        | -                | 1.000 (0.041)    | -         |     1.94 | F1KU, HeavyGod, k1to, Nexius, regali |
|            5 |     8036 | 2024-01-13 | ex-Anonymo Esports | W   | 0.284      | -            | -                | -                | -         |     0.62 | F1KU, HeavyGod, k1to, Nexius, regali |
|            4 |     8041 | 2024-01-13 | Nexus Gaming       | W   | 0.283      | -            | -                | -                | -         |     1.43 | F1KU, HeavyGod, k1to, Nexius, regali |
|            3 |     8104 | 2024-01-12 | Passion UA         | W   | 0.278      | -            | -                | -                | -         |     2.42 | F1KU, HeavyGod, k1to, Nexius, regali |
|            2 |     8116 | 2024-01-12 | eternal premium    | W   | 0.278      | -            | -                | -                | -         |     0.10 | F1KU, HeavyGod, k1to, Nexius, regali |
|            1 |     8267 | 2024-01-10 | GRGECHI            | L   | 0.265      | -            | -                | -                | -         |    -8.14 | F1KU, HeavyGod, k1to, Nexius, regali |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($83,343.69)
- Divide that value by the 5th highest value among all rosters ($300,806.11)
- The final value (0.28) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-05-02 |      1.000 | $1,000.00      | $1,000.00       |
| 2024-04-20 |      0.938 | $10,000.00     | $9,379.63       |
| 2024-04-14 |      0.896 | $70,000.00     | $62,737.50      |
| 2024-03-10 |      0.665 | $12,500.00     | $8,306.42       |
| 2024-01-28 |      0.384 | $5,000.00      | $1,920.14       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
