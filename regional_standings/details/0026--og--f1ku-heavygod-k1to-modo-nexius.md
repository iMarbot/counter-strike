### Roster Details<br />
Team Name: OG<br />
Roster: F1KU, HeavyGod, k1to, MoDo, Nexius<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [26](../standings_global.md)<br />
Regional Rank: [19]( ../standings_europe.md)<br />
Final Rank Value:  1330.5<br />
<br />
Final Rank Value (1330.5) = Starting Rank Value (1338.7) + Head To Head Adjustments (-8.2)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.815[<sup>1</sup>](#table2)
- Bounty Collected: 0.551[<sup>2</sup>](#table1)
- Opponent Network: 0.226[<sup>2</sup>](#table1)
- LAN Wins: 0.300[<sup>2</sup>](#table1)

The average of these factors is 0.473<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1338.7
- 400 + ( ( 0.473 - 0.000 ) / ( 0.806 - 0.000 ) ) * 1600 = 1338.7


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent           | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins      | H2H Adj. | Roster                               |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           32 |      197 | 2024-05-01 | Insilio            | L   | 1.000      | -            | -                | -                | -             |   -27.91 | F1KU, HeavyGod, k1to, MoDo, Nexius   |
|           31 |      245 | 2024-04-30 | Sashi Esport       | L   | 1.000      | -            | -                | -                | -             |   -19.93 | F1KU, HeavyGod, k1to, MoDo, Nexius   |
|           30 |      738 | 2024-04-20 | MIBR               | L   | 1.000      | -            | -                | -                | -             |    -7.17 | F1KU, HeavyGod, k1to, MoDo, Nexius   |
|           29 |      789 | 2024-04-19 | 9z Team            | W   | 1.000      | 0.589        | 0.057 (0.033)    | 0.376 (0.221)    | true (1.000)  |     3.81 | F1KU, HeavyGod, k1to, MoDo, Nexius   |
|           28 |      803 | 2024-04-19 | Monte              | W   | 1.000      | 0.589        | 0.199 (0.117)    | 0.378 (0.223)    | true (1.000)  |    13.35 | F1KU, HeavyGod, k1to, MoDo, Nexius   |
|           27 |      865 | 2024-04-18 | MIBR               | L   | 1.000      | -            | -                | -                | -             |    -7.84 | F1KU, HeavyGod, k1to, MoDo, Nexius   |
|           26 |     1069 | 2024-04-14 | Aurora Gaming      | L   | 1.000      | -            | -                | -                | -             |    -9.98 | F1KU, HeavyGod, k1to, MoDo, Nexius   |
|           25 |     1096 | 2024-04-13 | BetBoom Team       | W   | 1.000      | 0.687        | 0.571 (0.392)    | 0.824 (0.566)    | false (0.000) |    16.02 | F1KU, HeavyGod, k1to, MoDo, Nexius   |
|           24 |     1118 | 2024-04-13 | BIG                | W   | 1.000      | 0.687        | 0.470 (0.323)    | 0.400 (0.275)    | false (0.000) |    18.04 | F1KU, HeavyGod, k1to, MoDo, Nexius   |
|           23 |     1146 | 2024-04-12 | Ninjas in Pyjamas  | W   | 1.000      | 0.687        | 0.241 (0.166)    | 0.376 (0.258)    | false (0.000) |     7.99 | F1KU, HeavyGod, k1to, MoDo, Nexius   |
|           22 |     1234 | 2024-04-10 | ENCE               | W   | 1.000      | 0.687        | 0.377 (0.259)    | 0.352 (0.242)    | false (0.000) |    20.65 | F1KU, HeavyGod, k1to, MoDo, Nexius   |
|           21 |     1327 | 2024-04-08 | Aurora Gaming      | L   | 1.000      | -            | -                | -                | -             |    -8.41 | F1KU, HeavyGod, k1to, MoDo, Nexius   |
|           20 |     2457 | 2024-03-10 | SAW                | L   | 0.825      | -            | -                | -                | -             |    -7.98 | F1KU, k1to, Nexius, regali, s0und    |
|           19 |     2502 | 2024-03-09 | HEROIC             | W   | 0.818      | 0.535        | 0.243 (0.106)    | 0.537 (0.235)    | false (0.000) |    22.74 | F1KU, HeavyGod, k1to, Nexius, regali |
|           18 |     2570 | 2024-03-07 | Complexity Gaming  | W   | 0.805      | 0.535        | 0.271 (0.117)    | 0.274 (0.118)    | false (0.000) |    18.88 | F1KU, HeavyGod, k1to, Nexius, regali |
|           17 |     3314 | 2024-02-21 | GamerLegion        | L   | 0.704      | -            | -                | -                | -             |    -3.96 | F1KU, HeavyGod, k1to, Nexius, regali |
|           16 |     3376 | 2024-02-20 | Gaimin Gladiators  | L   | 0.697      | -            | -                | -                | -             |    -9.18 | F1KU, HeavyGod, k1to, Nexius, regali |
|           15 |     3404 | 2024-02-19 | Preasy Esport      | W   | 0.692      | 0.143        | 0.106 (0.011)    | -                | true (0.692)  |     3.26 | F1KU, HeavyGod, k1to, Nexius, regali |
|           14 |     3422 | 2024-02-19 | Apeks              | L   | 0.690      | -            | -                | -                | -             |    -8.32 | F1KU, HeavyGod, k1to, Nexius, regali |
|           13 |     4423 | 2024-01-23 | Team Falcons       | L   | 0.512      | -            | -                | -                | -             |    -7.28 | F1KU, HeavyGod, k1to, Nexius, regali |
|           12 |     4477 | 2024-01-22 | Team Vitality      | L   | 0.505      | -            | -                | -                | -             |    -0.55 | F1KU, HeavyGod, k1to, Nexius, regali |
|           11 |     4543 | 2024-01-20 | Nexus Gaming       | W   | 0.492      | -            | -                | -                | false (0.000) |     1.70 | F1KU, HeavyGod, k1to, Nexius, regali |
|           10 |     4555 | 2024-01-20 | BetBoom Team       | L   | 0.491      | -            | -                | -                | -             |    -4.41 | F1KU, HeavyGod, k1to, Nexius, regali |
|            9 |     4607 | 2024-01-19 | 3DMAX              | W   | 0.484      | -            | -                | -                | -             |     1.75 | F1KU, HeavyGod, k1to, Nexius, regali |
|            8 |     4646 | 2024-01-18 | JANO Esports       | W   | 0.479      | -            | -                | -                | -             |     0.71 | F1KU, HeavyGod, k1to, Nexius, regali |
|            7 |     4669 | 2024-01-18 | Cloud9             | L   | 0.478      | -            | -                | -                | -             |    -1.07 | F1KU, HeavyGod, k1to, Nexius, regali |
|            6 |     4882 | 2024-01-13 | Gaimin Gladiators  | L   | 0.446      | -            | -                | -                | -             |    -5.48 | F1KU, HeavyGod, k1to, Nexius, regali |
|            5 |     4884 | 2024-01-13 | Permitta Esports   | W   | 0.445      | 0.143        | -                | 1.000 (0.064)    | -             |     1.90 | F1KU, HeavyGod, k1to, Nexius, regali |
|            4 |     4886 | 2024-01-13 | Ex-Anonymo Esports | W   | 0.445      | -            | -                | -                | -             |     0.72 | F1KU, HeavyGod, k1to, Nexius, regali |
|            3 |     4890 | 2024-01-13 | Nexus Gaming       | W   | 0.444      | -            | -                | -                | -             |     1.22 | F1KU, HeavyGod, k1to, Nexius, regali |
|            2 |     4934 | 2024-01-12 | Passion UA         | W   | 0.439      | 0.143        | 0.114 (0.007)    | 0.980 (0.061)    | -             |     1.82 | F1KU, HeavyGod, k1to, Nexius, regali |
|            1 |     5051 | 2024-01-10 | GRGECHI            | L   | 0.426      | -            | -                | -                | -             |   -13.25 | F1KU, HeavyGod, k1to, Nexius, regali |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($94,045.20)
- Divide that value by the 5th highest value among all rosters ($158,437.64)
- The final value (0.59) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-05-02 |      1.000 | $1,000.00      | $1,000.00       |
| 2024-04-20 |      1.000 | $10,000.00     | $10,000.00      |
| 2024-04-14 |      1.000 | $70,000.00     | $70,000.00      |
| 2024-03-10 |      0.826 | $12,500.00     | $10,319.73      |
| 2024-01-28 |      0.545 | $5,000.00      | $2,725.46       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
