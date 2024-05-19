### Roster Details<br />
Team Name: Team NKT<br />
Roster: Bobosaur, cool4st, MAIROLLS, xerolte, XigN<br />
Region: [Asia]( ../standings_asia.md)<br />
<br />
Global Rank: [138](../standings_global.md)<br />
Regional Rank: [18]( ../standings_asia.md)<br />
Final Rank Value:  789.4<br />
<br />
Final Rank Value (789.4) = Starting Rank Value (785.3) + Head To Head Adjustments (4.1)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.357[<sup>1</sup>](#table2)
- Bounty Collected: 0.278[<sup>2</sup>](#table1)
- Opponent Network: 0.024[<sup>2</sup>](#table1)
- LAN Wins: 0.119[<sup>2</sup>](#table1)

The average of these factors is 0.194<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 785.3
- 400 + ( ( 0.194 - 0.000 ) / ( 0.806 - 0.000 ) ) * 1600 = 785.3


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent           | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins      | H2H Adj. | Roster                                     |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           25 |     2225 | 2024-03-15 | The Huns Esports   | L   | 0.857      | -            | -                | -                | -             |    -9.55 | Bobosaur, cool4st, MAIROLLS, xerolte, XigN |
|           24 |     2333 | 2024-03-13 | BrodyyygiNR        | W   | 0.844      | 0.250        | 0.000 (0.000)    | 0.028 (0.006)    | false (0.000) |     2.66 | Bobosaur, cool4st, MAIROLLS, xerolte, XigN |
|           23 |     2431 | 2024-03-11 | Gotham Mafia       | W   | 0.830      | 0.250        | 0.000 (0.000)    | -                | false (0.000) |     2.55 | Bobosaur, cool4st, MAIROLLS, xerolte, XigN |
|           22 |     2540 | 2024-03-08 | Noobs But Diligent | L   | 0.810      | -            | -                | -                | -             |   -13.38 | Bobosaur, cool4st, MAIROLLS, xerolte, XigN |
|           21 |     2645 | 2024-03-06 | OneTwoThree        | W   | 0.797      | 0.250        | 0.000 (0.000)    | 0.028 (0.006)    | false (0.000) |     2.33 | Bobosaur, cool4st, MAIROLLS, xerolte, XigN |
|           20 |     3691 | 2024-02-13 | Myth Avenue Gaming | L   | 0.650      | -            | -                | -                | -             |   -12.62 | cool4st, fr0k, icyvlone, xerolte, XigN     |
|           19 |     3706 | 2024-02-12 | SEAW               | W   | 0.649      | 0.303        | 0.000 (0.000)    | 0.067 (0.013)    | false (0.000) |     2.70 | cool4st, fr0k, icyvlone, xerolte, XigN     |
|           18 |     3836 | 2024-02-07 | Drippy Lab         | W   | 0.616      | 0.303        | -                | 0.033 (0.006)    | false (0.000) |     1.71 | cool4st, fr0k, icyvlone, xerolte, XigN     |
|           17 |     3940 | 2024-02-03 | Grayfox Esports    | W   | 0.589      | 0.303        | 0.010 (0.002)    | 0.264 (0.047)    | false (0.000) |     6.58 | cool4st, fr0k, icyvlone, xerolte, XigN     |
|           16 |     4121 | 2024-01-31 | Rare Atom          | L   | 0.564      | -            | -                | -                | -             |    -8.98 | cool4st, fr0k, icyvlone, xerolte, XigN     |
|           15 |     4125 | 2024-01-31 | ATOX Esports       | L   | 0.563      | -            | -                | -                | -             |    -3.29 | cool4st, fr0k, icyvlone, xerolte, XigN     |
|           14 |     4129 | 2024-01-31 | Lynn Vision Gaming | W   | 0.562      | 0.143        | 0.155 (0.012)    | 0.554 (0.045)    | false (0.000) |    16.52 | cool4st, fr0k, icyvlone, xerolte, XigN     |
|           13 |     4232 | 2024-01-27 | The MongolZ        | L   | 0.542      | -            | -                | -                | -             |    -0.17 | cool4st, dobu, MiQ, xerolte, XigN          |
|           12 |     4290 | 2024-01-27 | E9 esports         | W   | 0.536      | 0.435        | 0.021 (0.005)    | 0.124 (0.029)    | true (0.536)  |     7.57 | cool4st, dobu, MiQ, xerolte, XigN          |
|           11 |     4335 | 2024-01-26 | Lynn Vision Gaming | L   | 0.530      | -            | -                | -                | -             |    -1.05 | cool4st, dobu, MiQ, xerolte, XigN          |
|           10 |     4338 | 2024-01-26 | E9 esports         | W   | 0.530      | 0.435        | 0.021 (0.005)    | 0.124 (0.029)    | true (0.530)  |     7.62 | cool4st, dobu, MiQ, xerolte, XigN          |
|            9 |     4369 | 2024-01-24 | The Huns Esports   | W   | 0.522      | 0.143        | 0.002 (0.000)    | 0.434 (0.032)    | false (0.000) |    11.39 | cool4st, fr0k, icyvlone, xerolte, XigN     |
|            8 |     4371 | 2024-01-24 | Myth Avenue Gaming | W   | 0.522      | 0.143        | 0.012 (0.001)    | 0.302 (0.023)    | -             |     6.92 | cool4st, fr0k, icyvlone, xerolte, XigN     |
|            7 |     4572 | 2024-01-20 | The Huns Esports   | L   | 0.489      | -            | -                | -                | -             |    -5.15 | cool4st, fr0k, icyvlone, xerolte, XigN     |
|            6 |     4620 | 2024-01-19 | The MongolZ        | L   | 0.483      | -            | -                | -                | -             |    -0.12 | cool4st, fr0k, icyvlone, xerolte, XigN     |
|            5 |     4835 | 2024-01-15 | Tseg Taslal        | W   | 0.457      | -            | -                | -                | -             |     1.59 | cool4st, fr0k, icyvlone, xerolte, XigN     |
|            4 |     4839 | 2024-01-15 | The Huns Esports   | L   | 0.456      | -            | -                | -                | -             |    -4.50 | cool4st, fr0k, icyvlone, xerolte, XigN     |
|            3 |     4846 | 2024-01-15 | SO5URUU            | W   | 0.456      | -            | -                | -                | -             |     1.55 | cool4st, fr0k, icyvlone, xerolte, XigN     |
|            2 |     5201 | 2024-01-03 | Wings Up Gaming    | L   | 0.382      | -            | -                | -                | -             |    -7.00 | cool4st, icyvlone, marsyA, xerolte, XigN   |
|            1 |     5241 | 2024-01-02 | ATOX Esports       | L   | 0.370      | -            | -                | -                | -             |    -1.75 | cool4st, icyvlone, marsyA, xerolte, XigN   |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($2,498.26)
- Divide that value by the 5th highest value among all rosters ($158,437.64)
- The final value (0.02) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-02-13 |      0.650 | $500.00        | $325.12         |
| 2024-01-28 |      0.543 | $4,000.00      | $2,173.15       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
