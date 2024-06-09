### Roster Details<br />
Team Name: Natus Vincere<br />
Roster: Aleksib, b1t, iM, jL, w0nderful<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [5](../standings_global.md)<br />
Regional Rank: [5]( ../standings_europe.md)<br />
Final Rank Value:  1813.1<br />
<br />
Final Rank Value (1813.1) = Starting Rank Value (1862.2) + Head To Head Adjustments (-49.2)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 1.000[<sup>1</sup>](#table2)
- Bounty Collected: 0.697[<sup>2</sup>](#table1)
- Opponent Network: 0.321[<sup>2</sup>](#table1)
- LAN Wins: 0.860[<sup>2</sup>](#table1)

The average of these factors is 0.719<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1862.2
- 400 + ( ( 0.719 - 0.000 ) / ( 0.787 - 0.000 ) ) * 1600 = 1862.2


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
|           33 |       76 | 2024-05-29 | HEROIC             | L   | 1.000      | -            | -                | -                | -         |   -24.23 | Aleksib, b1t, iM, jL, w0nderful |
|           32 |      127 | 2024-05-28 | Team Spirit        | L   | 1.000      | -            | -                | -                | -         |   -12.16 | Aleksib, b1t, iM, jL, w0nderful |
|           31 |      163 | 2024-05-27 | BIG                | W   | 1.000      | 0.624        | 0.215 (0.134)    | 0.304 (0.189)    | 1 (1.000) |     1.78 | Aleksib, b1t, iM, jL, w0nderful |
|           30 |     1626 | 2024-05-08 | FaZe Clan          | L   | 1.000      | -            | -                | -                | -         |   -11.14 | Aleksib, b1t, iM, jL, w0nderful |
|           29 |     1778 | 2024-05-05 | Complexity Gaming  | L   | 1.000      | -            | -                | -                | -         |   -26.41 | Aleksib, b1t, iM, jL, w0nderful |
|           28 |     1959 | 2024-05-02 | BIG                | W   | 1.000      | 0.889        | 0.215 (0.191)    | 0.304 (0.270)    | 1 (1.000) |     1.39 | Aleksib, b1t, iM, jL, w0nderful |
|           27 |     2027 | 2024-05-01 | FlyQuest           | W   | 1.000      | 0.889        | -                | 0.466 (0.414)    | 1 (1.000) |     2.50 | Aleksib, b1t, iM, jL, w0nderful |
|           26 |     3734 | 2024-03-31 | FaZe Clan          | W   | 0.804      | 1.000        | 1.000 (0.804)    | 0.457 (0.367)    | 1 (0.804) |    16.03 | Aleksib, b1t, iM, jL, w0nderful |
|           25 |     3758 | 2024-03-30 | G2 Esports         | W   | 0.798      | 1.000        | 0.468 (0.374)    | 0.392 (0.313)    | 1 (0.798) |    10.91 | Aleksib, b1t, iM, jL, w0nderful |
|           24 |     3798 | 2024-03-29 | Eternal Fire       | W   | 0.790      | 1.000        | 1.000 (0.790)    | 0.402 (0.318)    | 1 (0.790) |    12.53 | Aleksib, b1t, iM, jL, w0nderful |
|           23 |     4036 | 2024-03-24 | paiN Gaming        | W   | 0.757      | 1.000        | 0.463 (0.351)    | 0.547 (0.414)    | 1 (0.757) |     4.66 | Aleksib, b1t, iM, jL, w0nderful |
|           22 |     4084 | 2024-03-23 | Cloud9             | L   | 0.751      | -            | -                | -                | -         |   -20.12 | Aleksib, b1t, iM, jL, w0nderful |
|           21 |     4132 | 2024-03-22 | Team Spirit        | L   | 0.744      | -            | -                | -                | -         |    -9.61 | Aleksib, b1t, iM, jL, w0nderful |
|           20 |     4164 | 2024-03-21 | G2 Esports         | W   | 0.738      | 1.000        | 0.468 (0.346)    | 0.392 (0.289)    | 1 (0.738) |    10.10 | Aleksib, b1t, iM, jL, w0nderful |
|           19 |     4201 | 2024-03-21 | The MongolZ        | W   | 0.736      | 1.000        | 0.192 (0.141)    | 0.619 (0.455)    | 1 (0.736) |     3.98 | Aleksib, b1t, iM, jL, w0nderful |
|           18 |     6157 | 2024-02-16 | BetBoom Team       | W   | 0.510      | -            | -                | -                | 1 (0.510) |     1.15 | Aleksib, b1t, iM, jL, w0nderful |
|           17 |     6228 | 2024-02-15 | Virtus.pro         | L   | 0.503      | -            | -                | -                | -         |   -11.51 | Aleksib, b1t, iM, jL, w0nderful |
|           16 |     6268 | 2024-02-14 | ENTERPRISE esports | W   | 0.498      | -            | -                | -                | -         |     0.12 | Aleksib, b1t, iM, jL, w0nderful |
|           15 |     6299 | 2024-02-14 | KOI                | W   | 0.496      | -            | -                | -                | -         |     0.11 | Aleksib, b1t, iM, jL, w0nderful |
|           14 |     6577 | 2024-02-06 | Team Falcons       | L   | 0.443      | -            | -                | -                | -         |   -12.51 | Aleksib, b1t, iM, jL, w0nderful |
|           13 |     6608 | 2024-02-05 | Eternal Fire       | W   | 0.438      | 1.000        | 1.000 (0.438)    | 0.402 (0.176)    | -         |     6.46 | Aleksib, b1t, iM, jL, w0nderful |
|           12 |     6662 | 2024-02-04 | Apeks              | W   | 0.430      | -            | -                | -                | -         |     0.39 | Aleksib, b1t, iM, jL, w0nderful |
|           11 |     6730 | 2024-02-03 | Team Spirit        | L   | 0.424      | -            | -                | -                | -         |    -6.34 | Aleksib, b1t, iM, jL, w0nderful |
|           10 |     7203 | 2024-01-27 | G2 Esports         | W   | 0.377      | 0.581        | 0.468 (0.102)    | -                | -         |     4.72 | Aleksib, b1t, iM, jL, w0nderful |
|            9 |     7428 | 2024-01-23 | G2 Esports         | W   | 0.349      | -            | -                | -                | -         |     4.51 | Aleksib, b1t, iM, jL, w0nderful |
|            8 |     7486 | 2024-01-22 | Complexity Gaming  | W   | 0.343      | -            | -                | -                | -         |     1.67 | Aleksib, b1t, iM, jL, w0nderful |
|            7 |     7653 | 2024-01-19 | Virtus.pro         | W   | 0.324      | -            | -                | -                | -         |     2.91 | Aleksib, b1t, iM, jL, w0nderful |
|            6 |     7714 | 2024-01-18 | 9Pandas            | W   | 0.317      | -            | -                | -                | -         |     0.21 | Aleksib, b1t, iM, jL, w0nderful |
|            5 |     7736 | 2024-01-18 | Gaimin Gladiators  | W   | 0.317      | -            | -                | -                | -         |     0.38 | Aleksib, b1t, iM, jL, w0nderful |
|            4 |     8881 | 2023-12-16 | Team Vitality      | L   | 0.097      | -            | -                | -                | -         |    -1.59 | Aleksib, b1t, iM, jL, w0nderful |
|            3 |     9020 | 2023-12-15 | G2 Esports         | W   | 0.089      | -            | -                | -                | -         |     1.18 | Aleksib, b1t, iM, jL, w0nderful |
|            2 |     9060 | 2023-12-13 | ENCE               | W   | 0.081      | -            | -                | -                | -         |     0.00 | Aleksib, b1t, iM, jL, w0nderful |
|            1 |     9119 | 2023-12-13 | Team Vitality      | L   | 0.075      | -            | -                | -                | -         |    -1.24 | Aleksib, b1t, iM, jL, w0nderful |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($459,291.46)
- Divide that value by the 5th highest value among all rosters ($300,806.11)
- The final value (1.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-05-29 |      1.000 | $5,000.00      | $5,000.00       |
| 2024-05-12 |      1.000 | $23,500.00     | $23,500.00      |
| 2024-03-31 |      0.804 | $500,000.00    | $401,944.44     |
| 2024-02-11 |      0.477 | $24,000.00     | $11,446.67      |
| 2024-01-28 |      0.384 | $22,500.00     | $8,640.63       |
| 2023-12-17 |      0.103 | $85,000.00     | $8,759.72       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
