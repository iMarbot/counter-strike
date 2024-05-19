### Roster Details<br />
Team Name: Natus Vincere<br />
Roster: Aleksib, b1t, iM, jL, w0nderful<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [2](../standings_global.md)<br />
Regional Rank: [2]( ../standings_europe.md)<br />
Final Rank Value:  1921.9<br />
<br />
Final Rank Value (1921.9) = Starting Rank Value (1959.6) + Head To Head Adjustments (-37.7)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 1.000[<sup>1</sup>](#table2)
- Bounty Collected: 0.749[<sup>2</sup>](#table1)
- Opponent Network: 0.401[<sup>2</sup>](#table1)
- LAN Wins: 0.994[<sup>2</sup>](#table1)

The average of these factors is 0.786<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1959.6
- 400 + ( ( 0.786 - 0.000 ) / ( 0.806 - 0.000 ) ) * 1600 = 1959.6


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent           | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                          |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           32 |        6 | 2024-05-05 | Complexity Gaming  | L   | 1.000      | -            | -                | -                | -         |   -28.48 | Aleksib, b1t, iM, jL, w0nderful |
|           31 |      157 | 2024-05-02 | BIG                | W   | 1.000      | 0.889        | 0.470 (0.418)    | 0.400 (0.356)    | 1 (1.000) |     1.25 | Aleksib, b1t, iM, jL, w0nderful |
|           30 |      215 | 2024-05-01 | FlyQuest           | W   | 1.000      | 0.889        | -                | 0.547 (0.486)    | 1 (1.000) |     1.49 | Aleksib, b1t, iM, jL, w0nderful |
|           29 |     1614 | 2024-03-31 | FaZe Clan          | W   | 0.965      | 1.000        | 1.000 (0.965)    | 0.566 (0.547)    | 1 (0.965) |    15.87 | Aleksib, b1t, iM, jL, w0nderful |
|           28 |     1630 | 2024-03-30 | G2 Esports         | W   | 0.959      | 1.000        | 0.866 (0.830)    | 0.477 (0.458)    | 1 (0.959) |    13.02 | Aleksib, b1t, iM, jL, w0nderful |
|           27 |     1663 | 2024-03-29 | Eternal Fire       | W   | 0.951      | 1.000        | 0.409 (0.389)    | 0.462 (0.440)    | 1 (0.951) |    10.90 | Aleksib, b1t, iM, jL, w0nderful |
|           26 |     1857 | 2024-03-24 | PaiN Gaming        | W   | 0.919      | -            | -                | -                | 1 (0.919) |     0.40 | Aleksib, b1t, iM, jL, w0nderful |
|           25 |     1896 | 2024-03-23 | Cloud9             | L   | 0.912      | -            | -                | -                | -         |   -20.13 | Aleksib, b1t, iM, jL, w0nderful |
|           24 |     1939 | 2024-03-22 | Team Spirit        | L   | 0.905      | -            | -                | -                | -         |   -16.14 | Aleksib, b1t, iM, jL, w0nderful |
|           23 |     1965 | 2024-03-21 | G2 Esports         | W   | 0.899      | 1.000        | 0.866 (0.778)    | 0.477 (0.429)    | 1 (0.899) |    11.94 | Aleksib, b1t, iM, jL, w0nderful |
|           22 |     1995 | 2024-03-21 | The MongolZ        | W   | 0.897      | 1.000        | 0.292 (0.262)    | 0.663 (0.594)    | 1 (0.897) |     3.91 | Aleksib, b1t, iM, jL, w0nderful |
|           21 |     3532 | 2024-02-16 | BetBoom Team       | W   | 0.671      | -            | -                | -                | 1 (0.671) |     1.43 | Aleksib, b1t, iM, jL, w0nderful |
|           20 |     3588 | 2024-02-15 | Virtus.pro         | L   | 0.665      | -            | -                | -                | -         |   -16.20 | Aleksib, b1t, iM, jL, w0nderful |
|           19 |     3616 | 2024-02-14 | ENTERPRISE esports | W   | 0.659      | -            | -                | -                | 1 (0.659) |     0.08 | Aleksib, b1t, iM, jL, w0nderful |
|           18 |     3645 | 2024-02-14 | KOI                | W   | 0.657      | -            | -                | -                | -         |     0.16 | Aleksib, b1t, iM, jL, w0nderful |
|           17 |     3862 | 2024-02-06 | Team Falcons       | L   | 0.605      | -            | -                | -                | -         |   -18.30 | Aleksib, b1t, iM, jL, w0nderful |
|           16 |     3885 | 2024-02-05 | Eternal Fire       | W   | 0.599      | 1.000        | 0.409 (0.245)    | 0.462 (0.277)    | -         |     5.48 | Aleksib, b1t, iM, jL, w0nderful |
|           15 |     3921 | 2024-02-04 | Apeks              | W   | 0.591      | 1.000        | -                | 0.459 (0.272)    | -         |     0.85 | Aleksib, b1t, iM, jL, w0nderful |
|           14 |     3968 | 2024-02-03 | Team Spirit        | L   | 0.585      | -            | -                | -                | -         |   -12.60 | Aleksib, b1t, iM, jL, w0nderful |
|           13 |     4282 | 2024-01-27 | G2 Esports         | W   | 0.538      | 0.581        | 0.866 (0.270)    | 0.477 (0.149)    | -         |     6.44 | Aleksib, b1t, iM, jL, w0nderful |
|           12 |     4438 | 2024-01-23 | G2 Esports         | W   | 0.510      | 0.581        | 0.866 (0.256)    | -                | -         |     6.39 | Aleksib, b1t, iM, jL, w0nderful |
|           11 |     4484 | 2024-01-22 | Complexity Gaming  | W   | 0.504      | -            | -                | -                | -         |     1.35 | Aleksib, b1t, iM, jL, w0nderful |
|           10 |     4601 | 2024-01-19 | Virtus.pro         | W   | 0.485      | -            | -                | -                | -         |     3.20 | Aleksib, b1t, iM, jL, w0nderful |
|            9 |     4652 | 2024-01-18 | 9Pandas            | W   | 0.478      | -            | -                | -                | -         |     0.14 | Aleksib, b1t, iM, jL, w0nderful |
|            8 |     4668 | 2024-01-18 | Gaimin Gladiators  | W   | 0.478      | -            | -                | -                | -         |     0.72 | Aleksib, b1t, iM, jL, w0nderful |
|            7 |     5481 | 2023-12-16 | Team Vitality      | L   | 0.258      | -            | -                | -                | -         |    -4.54 | Aleksib, b1t, iM, jL, w0nderful |
|            6 |     5595 | 2023-12-15 | G2 Esports         | W   | 0.250      | 1.000        | 0.866 (0.216)    | -                | -         |     3.23 | Aleksib, b1t, iM, jL, w0nderful |
|            5 |     5620 | 2023-12-13 | ENCE               | W   | 0.242      | -            | -                | -                | -         |     0.01 | Aleksib, b1t, iM, jL, w0nderful |
|            4 |     5656 | 2023-12-13 | Team Vitality      | L   | 0.236      | -            | -                | -                | -         |    -4.24 | Aleksib, b1t, iM, jL, w0nderful |
|            3 |     6470 | 2023-11-24 | Complexity Gaming  | L   | 0.112      | -            | -                | -                | -         |    -3.22 | Aleksib, b1t, iM, jL, w0nderful |
|            2 |     6534 | 2023-11-23 | Ninjas in Pyjamas  | W   | 0.103      | -            | -                | -                | -         |     0.01 | Aleksib, b1t, iM, jL, w0nderful |
|            1 |     6575 | 2023-11-22 | Cloud9             | L   | 0.097      | -            | -                | -                | -         |    -2.18 | Aleksib, b1t, iM, jL, w0nderful |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($535,136.30)
- Divide that value by the 5th highest value among all rosters ($158,437.64)
- The final value (1.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-03-31 |      0.965 | $500,000.00    | $482,615.74     |
| 2024-02-11 |      0.638 | $24,000.00     | $15,312.22      |
| 2024-01-28 |      0.545 | $22,500.00     | $12,264.58      |
| 2023-12-17 |      0.264 | $85,000.00     | $22,450.23      |
| 2023-11-26 |      0.125 | $20,000.00     | $2,493.52       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
