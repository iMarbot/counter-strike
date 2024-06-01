### Roster Details<br />
Team Name: OG<br />
Roster: F1KU, HeavyGod, k1to, MoDo, Nexius<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [33](../standings_global.md)<br />
Regional Rank: [23]( ../standings_europe.md)<br />
Final Rank Value:  1202.8<br />
<br />
Final Rank Value (1202.8) = Starting Rank Value (1197.4) + Head To Head Adjustments (5.3)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.642[<sup>1</sup>](#table2)
- Bounty Collected: 0.494[<sup>2</sup>](#table1)
- Opponent Network: 0.178[<sup>2</sup>](#table1)
- LAN Wins: 0.253[<sup>2</sup>](#table1)

The average of these factors is 0.392<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1197.4
- 400 + ( ( 0.392 - 0.000 ) / ( 0.786 - 0.000 ) ) * 1600 = 1197.4


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
|           36 |       96 | 2024-05-28 | ATOX Esports       | L   | 1.000      | -            | -                | -                | -         |   -21.46 | F1KU, HeavyGod, k1to, MoDo, Nexius   |
|           35 |      805 | 2024-05-19 | paiN Gaming        | L   | 1.000      | -            | -                | -                | -         |    -6.44 | F1KU, HeavyGod, k1to, MoDo, Nexius   |
|           34 |      832 | 2024-05-18 | Team Liquid        | L   | 1.000      | -            | -                | -                | -         |    -3.34 | F1KU, HeavyGod, k1to, MoDo, Nexius   |
|           33 |     1976 | 2024-05-01 | Insilio            | L   | 1.000      | -            | -                | -                | -         |   -25.72 | F1KU, HeavyGod, k1to, MoDo, Nexius   |
|           32 |     2033 | 2024-04-30 | Sashi Esport       | L   | 1.000      | -            | -                | -                | -         |   -16.65 | F1KU, HeavyGod, k1to, MoDo, Nexius   |
|           31 |     2606 | 2024-04-20 | MIBR               | L   | 0.936      | -            | -                | -                | -         |    -4.11 | F1KU, HeavyGod, k1to, MoDo, Nexius   |
|           30 |     2663 | 2024-04-19 | 9z Team            | W   | 0.933      | 0.589        | 0.107 (0.059)    | 0.547 (0.300)    | 1 (0.933) |    13.51 | F1KU, HeavyGod, k1to, MoDo, Nexius   |
|           29 |     2680 | 2024-04-19 | Monte              | W   | 0.931      | 0.589        | 0.181 (0.099)    | 0.363 (0.199)    | 1 (0.931) |    13.56 | F1KU, HeavyGod, k1to, MoDo, Nexius   |
|           28 |     2746 | 2024-04-18 | MIBR               | L   | 0.925      | -            | -                | -                | -         |    -4.22 | F1KU, HeavyGod, k1to, MoDo, Nexius   |
|           27 |     2981 | 2024-04-14 | Aurora Gaming      | L   | 0.896      | -            | -                | -                | -         |    -7.61 | F1KU, HeavyGod, k1to, MoDo, Nexius   |
|           26 |     3016 | 2024-04-13 | BetBoom Team       | W   | 0.890      | 0.687        | 0.390 (0.238)    | 0.712 (0.435)    | 0 (0.000) |    16.97 | F1KU, HeavyGod, k1to, MoDo, Nexius   |
|           25 |     3047 | 2024-04-13 | BIG                | W   | 0.889      | 0.687        | 0.235 (0.144)    | 0.304 (0.185)    | 0 (0.000) |    19.30 | F1KU, HeavyGod, k1to, MoDo, Nexius   |
|           24 |     3083 | 2024-04-12 | Ninjas in Pyjamas  | W   | 0.883      | 0.687        | 0.118 (0.072)    | 0.285 (0.173)    | 0 (0.000) |     9.87 | F1KU, HeavyGod, k1to, MoDo, Nexius   |
|           23 |     3187 | 2024-04-10 | ENCE               | W   | 0.869      | 0.687        | 0.202 (0.120)    | 0.280 (0.167)    | 0 (0.000) |    19.98 | F1KU, HeavyGod, k1to, MoDo, Nexius   |
|           22 |     3288 | 2024-04-08 | Aurora Gaming      | L   | 0.857      | -            | -                | -                | -         |    -6.09 | F1KU, HeavyGod, k1to, MoDo, Nexius   |
|           21 |     4659 | 2024-03-10 | SAW                | L   | 0.664      | -            | -                | -                | -         |    -5.71 | F1KU, k1to, Nexius, regali, s0und    |
|           20 |     4718 | 2024-03-09 | HEROIC             | W   | 0.657      | 0.535        | 0.322 (0.113)    | 0.463 (0.163)    | 0 (0.000) |    19.68 | F1KU, HeavyGod, k1to, Nexius, regali |
|           19 |     4806 | 2024-03-07 | Complexity Gaming  | W   | 0.644      | 0.535        | 0.260 (0.090)    | 0.219 (0.075)    | 0 (0.000) |    17.90 | F1KU, HeavyGod, k1to, Nexius, regali |
|           18 |     5720 | 2024-02-21 | GamerLegion        | L   | 0.543      | -            | -                | -                | -         |    -6.80 | F1KU, HeavyGod, k1to, Nexius, regali |
|           17 |     5788 | 2024-02-20 | Gaimin Gladiators  | L   | 0.536      | -            | -                | -                | -         |    -6.83 | F1KU, HeavyGod, k1to, Nexius, regali |
|           16 |     5826 | 2024-02-19 | ex-Preasy Esport   | W   | 0.531      | 0.143        | 0.052 (0.004)    | -                | 1 (0.531) |     3.33 | F1KU, HeavyGod, k1to, Nexius, regali |
|           15 |     5845 | 2024-02-19 | Apeks              | L   | 0.529      | -            | -                | -                | -         |    -7.14 | F1KU, HeavyGod, k1to, Nexius, regali |
|           14 |     7172 | 2024-01-23 | Team Falcons       | L   | 0.351      | -            | -                | -                | -         |    -1.85 | F1KU, HeavyGod, k1to, Nexius, regali |
|           13 |     7236 | 2024-01-22 | Team Vitality      | L   | 0.343      | -            | -                | -                | -         |    -0.25 | F1KU, HeavyGod, k1to, Nexius, regali |
|           12 |     7326 | 2024-01-20 | Nexus Gaming       | W   | 0.331      | -            | -                | -                | 0 (0.000) |     2.04 | F1KU, HeavyGod, k1to, Nexius, regali |
|           11 |     7347 | 2024-01-20 | BetBoom Team       | L   | 0.330      | -            | -                | -                | -         |    -2.16 | F1KU, HeavyGod, k1to, Nexius, regali |
|           10 |     7415 | 2024-01-19 | 3DMAX              | W   | 0.323      | 0.143        | 0.106 (0.005)    | -                | -         |     2.06 | F1KU, HeavyGod, k1to, Nexius, regali |
|            9 |     7458 | 2024-01-18 | JANO Esports       | W   | 0.318      | -            | -                | -                | -         |     0.23 | F1KU, HeavyGod, k1to, Nexius, regali |
|            8 |     7488 | 2024-01-18 | Cloud9             | L   | 0.317      | -            | -                | -                | -         |    -1.56 | F1KU, HeavyGod, k1to, Nexius, regali |
|            7 |     7776 | 2024-01-13 | Gaimin Gladiators  | L   | 0.285      | -            | -                | -                | -         |    -3.45 | F1KU, HeavyGod, k1to, Nexius, regali |
|            6 |     7781 | 2024-01-13 | Permitta Esports   | W   | 0.284      | 0.143        | -                | 1.000 (0.041)    | -         |     1.87 | F1KU, HeavyGod, k1to, Nexius, regali |
|            5 |     7783 | 2024-01-13 | ex-Anonymo Esports | W   | 0.284      | -            | -                | -                | -         |     0.62 | F1KU, HeavyGod, k1to, Nexius, regali |
|            4 |     7788 | 2024-01-13 | Nexus Gaming       | W   | 0.283      | -            | -                | -                | -         |     1.54 | F1KU, HeavyGod, k1to, Nexius, regali |
|            3 |     7851 | 2024-01-12 | Passion UA         | W   | 0.278      | 0.143        | -                | 1.000 (0.040)    | -         |     2.32 | F1KU, HeavyGod, k1to, Nexius, regali |
|            2 |     7863 | 2024-01-12 | eternal premium    | W   | 0.278      | -            | -                | -                | -         |     0.10 | F1KU, HeavyGod, k1to, Nexius, regali |
|            1 |     8013 | 2024-01-10 | GRGECHI            | L   | 0.265      | -            | -                | -                | -         |    -8.14 | F1KU, HeavyGod, k1to, Nexius, regali |

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
