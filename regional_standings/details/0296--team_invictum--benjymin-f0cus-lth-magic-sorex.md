### Roster Details<br />
Team Name: Team Invictum<br />
Roster: BENJYMIN, f0cus, LTH, Magic, Sorex<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [296](../standings_global.md)<br />
Regional Rank: [186]( ../standings_europe.md)<br />
Final Rank Value:  648.3<br />
<br />
Final Rank Value (648.3) = Starting Rank Value (662.7) + Head To Head Adjustments (-14.4)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.216[<sup>1</sup>](#table2)
- Bounty Collected: 0.221[<sup>2</sup>](#table1)
- Opponent Network: 0.020[<sup>2</sup>](#table1)
- LAN Wins: 0.059[<sup>2</sup>](#table1)

The average of these factors is 0.129<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 662.7
- 400 + ( ( 0.129 - 0.000 ) / ( 0.787 - 0.000 ) ) * 1600 = 662.7


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent             | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           16 |      570 | 2024-05-21 | Part Timers          | L   | 1.000      | -            | -                | -                | -         |   -14.53 | BENJYMIN, f0cus, LTH, Magic, Sorex    |
|           15 |      977 | 2024-05-17 | FearFerox            | L   | 1.000      | -            | -                | -                | -         |   -16.85 | BENJYMIN, f0cus, LTH, Magic, Sorex    |
|           14 |     1065 | 2024-05-16 | ex-K10               | W   | 1.000      | 0.143        | 0.005 (0.001)    | 0.517 (0.074)    | 0 (0.000) |    19.23 | BENJYMIN, f0cus, LTH, Magic, Sorex    |
|           13 |     1253 | 2024-05-14 | Verdant              | L   | 1.000      | -            | -                | -                | -         |    -7.02 | BENJYMIN, f0cus, LTH, Magic, Sorex    |
|           12 |     1566 | 2024-05-09 | Halal5               | L   | 1.000      | -            | -                | -                | -         |   -17.21 | BENJYMIN, f0cus, LTH, Magic, Sorex    |
|           11 |     1568 | 2024-05-09 | EXO Clan             | W   | 1.000      | 0.143        | 0.013 (0.002)    | 0.579 (0.083)    | 0 (0.000) |    25.28 | BENJYMIN, f0cus, LTH, Magic, Sorex    |
|           10 |     2048 | 2024-04-30 | The Last Resort      | L   | 1.000      | -            | -                | -                | -         |   -15.33 | BENJYMIN, f0cus, LTH, Magic, Sorex    |
|            9 |     2131 | 2024-04-28 | ROYALS               | W   | 0.991      | 0.143        | 0.003 (0.000)    | 0.143 (0.020)    | 0 (0.000) |    17.44 | BENJYMIN, f0cus, LTH, Magic, Sorex    |
|            8 |     2450 | 2024-04-23 | Raptors Esports Club | L   | 0.958      | -            | -                | -                | -         |    -7.11 | BENJYMIN, f0cus, LTH, Magic, Sorex    |
|            7 |     2600 | 2024-04-20 | Souls-Land           | W   | 0.938      | 0.143        | 0.000 (0.000)    | 0.079 (0.011)    | 0 (0.000) |     9.77 | BENJYMIN, f0cus, LTH, Magic, Sorex    |
|            6 |     2602 | 2024-04-20 | Team Sodality        | W   | 0.938      | 0.143        | 0.000 (0.000)    | 0.081 (0.011)    | 0 (0.000) |     9.47 | BENJYMIN, f0cus, LTH, Magic, Sorex    |
|            5 |     2726 | 2024-04-19 | Souls-Land           | L   | 0.931      | -            | -                | -                | -         |   -19.73 | BENJYMIN, f0cus, LTH, Magic, Sorex    |
|            4 |     2730 | 2024-04-19 | BLUEJAYS Royal       | W   | 0.931      | 0.143        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     5.43 | BENJYMIN, f0cus, LTH, Magic, Sorex    |
|            3 |     5688 | 2024-02-24 | Part Timers          | L   | 0.564      | -            | -                | -                | -         |    -6.65 | CYPHER, ifan, JackB, JAUSTERE, Yoshwa |
|            2 |     5714 | 2024-02-24 | EXO Clan             | L   | 0.563      | -            | -                | -                | -         |    -2.48 | BENJYMIN, Jc-KicA, LTH, Magic, Sorex  |
|            1 |     5755 | 2024-02-23 | Anita Max Wynn       | W   | 0.558      | 0.143        | 0.000 (0.000)    | 0.018 (0.001)    | 1 (0.558) |     5.86 | BENJYMIN, Jc-KicA, LTH, Magic, Sorex  |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($72.24)
- Divide that value by the 5th highest value among all rosters ($300,806.11)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
