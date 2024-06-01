### Roster Details<br />
Team Name: Team NKT<br />
Roster: Bobosaur, cool4st, MAIROLLS, xerolte, XigN<br />
Region: [Asia]( ../standings_asia.md)<br />
<br />
Global Rank: [190](../standings_global.md)<br />
Regional Rank: [23]( ../standings_asia.md)<br />
Final Rank Value:  737.6<br />
<br />
Final Rank Value (737.6) = Starting Rank Value (726.1) + Head To Head Adjustments (11.5)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.310[<sup>1</sup>](#table2)
- Bounty Collected: 0.241[<sup>2</sup>](#table1)
- Opponent Network: 0.011[<sup>2</sup>](#table1)
- LAN Wins: 0.079[<sup>2</sup>](#table1)

The average of these factors is 0.160<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 726.1
- 400 + ( ( 0.160 - 0.000 ) / ( 0.786 - 0.000 ) ) * 1600 = 726.1


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent           | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                     |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           25 |     4386 | 2024-03-15 | The Huns Esports   | L   | 0.696      | -            | -                | -                | -         |    -7.08 | Bobosaur, cool4st, MAIROLLS, xerolte, XigN |
|           24 |     4507 | 2024-03-13 | BrodyyygiNR        | W   | 0.683      | 0.250        | 0.000 (0.000)    | 0.018 (0.003)    | 0 (0.000) |     2.80 | Bobosaur, cool4st, MAIROLLS, xerolte, XigN |
|           23 |     4627 | 2024-03-11 | Gotham Mafia       | W   | 0.669      | 0.250        | 0.000 (0.000)    | -                | 0 (0.000) |     2.70 | Bobosaur, cool4st, MAIROLLS, xerolte, XigN |
|           22 |     4762 | 2024-03-08 | Noobs But Diligent | L   | 0.649      | -            | -                | -                | -         |    -9.99 | Bobosaur, cool4st, MAIROLLS, xerolte, XigN |
|           21 |     4900 | 2024-03-06 | OneTwoThree        | W   | 0.636      | 0.250        | 0.000 (0.000)    | 0.018 (0.003)    | 0 (0.000) |     2.50 | Bobosaur, cool4st, MAIROLLS, xerolte, XigN |
|           20 |     6170 | 2024-02-13 | Myth Avenue Gaming | L   | 0.489      | -            | -                | -                | -         |    -8.79 | cool4st, fr0k, icyvlone, xerolte, XigN     |
|           19 |     6186 | 2024-02-12 | SEAW               | W   | 0.487      | 0.303        | 0.000 (0.000)    | 0.039 (0.006)    | 0 (0.000) |     2.65 | cool4st, fr0k, icyvlone, xerolte, XigN     |
|           18 |     6350 | 2024-02-07 | Drippy Lab         | W   | 0.454      | 0.303        | -                | 0.017 (0.002)    | 0 (0.000) |     1.70 | cool4st, fr0k, icyvlone, xerolte, XigN     |
|           17 |     6482 | 2024-02-03 | Grayfox Esports    | W   | 0.428      | 0.303        | 0.004 (0.001)    | 0.204 (0.026)    | 0 (0.000) |     5.51 | cool4st, fr0k, icyvlone, xerolte, XigN     |
|           16 |     6731 | 2024-01-31 | Rare Atom          | L   | 0.403      | -            | -                | -                | -         |    -6.44 | cool4st, fr0k, icyvlone, xerolte, XigN     |
|           15 |     6736 | 2024-01-31 | ATOX Esports       | L   | 0.402      | -            | -                | -                | -         |    -0.92 | cool4st, fr0k, icyvlone, xerolte, XigN     |
|           14 |     6742 | 2024-01-31 | Lynn Vision Gaming | W   | 0.401      | 0.143        | 0.063 (0.004)    | 0.414 (0.024)    | 0 (0.000) |    11.23 | cool4st, fr0k, icyvlone, xerolte, XigN     |
|           13 |     6890 | 2024-01-27 | The MongolZ        | L   | 0.381      | -            | -                | -                | -         |    -0.10 | cool4st, dobu, MiQ, xerolte, XigN          |
|           12 |     6994 | 2024-01-27 | E9 esports         | W   | 0.375      | 0.435        | 0.008 (0.001)    | 0.066 (0.011)    | 1 (0.375) |     5.54 | cool4st, dobu, MiQ, xerolte, XigN          |
|           11 |     7056 | 2024-01-26 | Lynn Vision Gaming | L   | 0.369      | -            | -                | -                | -         |    -1.26 | cool4st, dobu, MiQ, xerolte, XigN          |
|           10 |     7059 | 2024-01-26 | E9 esports         | W   | 0.369      | 0.435        | 0.008 (0.001)    | 0.066 (0.011)    | 1 (0.369) |     5.53 | cool4st, dobu, MiQ, xerolte, XigN          |
|            9 |     7097 | 2024-01-24 | The Huns Esports   | W   | 0.361      | 0.143        | 0.000 (0.000)    | 0.292 (0.015)    | 0 (0.000) |     8.24 | cool4st, fr0k, icyvlone, xerolte, XigN     |
|            8 |     7099 | 2024-01-24 | Myth Avenue Gaming | W   | 0.361      | 0.143        | 0.005 (0.000)    | 0.192 (0.010)    | -         |     5.12 | cool4st, fr0k, icyvlone, xerolte, XigN     |
|            7 |     7367 | 2024-01-20 | The Huns Esports   | L   | 0.328      | -            | -                | -                | -         |    -3.07 | cool4st, fr0k, icyvlone, xerolte, XigN     |
|            6 |     7428 | 2024-01-19 | The MongolZ        | L   | 0.322      | -            | -                | -                | -         |    -0.07 | cool4st, fr0k, icyvlone, xerolte, XigN     |
|            5 |     7711 | 2024-01-15 | Tseg Taslal        | W   | 0.296      | -            | -                | -                | -         |     1.33 | cool4st, fr0k, icyvlone, xerolte, XigN     |
|            4 |     7716 | 2024-01-15 | The Huns Esports   | L   | 0.295      | -            | -                | -                | -         |    -2.63 | cool4st, fr0k, icyvlone, xerolte, XigN     |
|            3 |     7724 | 2024-01-15 | SO5URUU            | W   | 0.295      | -            | -                | -                | -         |     1.31 | cool4st, fr0k, icyvlone, xerolte, XigN     |
|            2 |     8239 | 2024-01-03 | Wings Up Gaming    | L   | 0.221      | -            | -                | -                | -         |    -3.93 | cool4st, icyvlone, marsyA, xerolte, XigN   |
|            1 |     8294 | 2024-01-02 | ATOX Esports       | L   | 0.209      | -            | -                | -                | -         |    -0.38 | cool4st, icyvlone, marsyA, xerolte, XigN   |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($1,775.97)
- Divide that value by the 5th highest value among all rosters ($300,806.11)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-02-13 |      0.494 | $500.00        | $247.08         |
| 2024-01-28 |      0.382 | $4,000.00      | $1,528.89       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
