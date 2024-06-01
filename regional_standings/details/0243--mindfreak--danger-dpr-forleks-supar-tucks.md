### Roster Details<br />
Team Name: Mindfreak<br />
Roster: dangeR, dpr, Forleks, supar, tucks<br />
Region: [Asia]( ../standings_asia.md)<br />
<br />
Global Rank: [243](../standings_global.md)<br />
Regional Rank: [33]( ../standings_asia.md)<br />
Final Rank Value:  690.9<br />
<br />
Final Rank Value (690.9) = Starting Rank Value (632.7) + Head To Head Adjustments (58.2)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.231[<sup>1</sup>](#table2)
- Bounty Collected: 0.217[<sup>2</sup>](#table1)
- Opponent Network: 0.009[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.114<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 632.7
- 400 + ( ( 0.114 - 0.000 ) / ( 0.786 - 0.000 ) ) * 1600 = 632.7


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent                 | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                             |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           25 |     7094 | 2024-01-25 | Rooster                  | L   | 0.361      | -            | -                | -                | -         |    -3.94 | dangeR, dpr, Forleks, supar, tucks |
|           24 |     7144 | 2024-01-24 | DXA Esports              | W   | 0.355      | 0.143        | 0.005 (0.000)    | 0.196 (0.010)    | 0 (0.000) |     6.06 | dangeR, dpr, Forleks, supar, tucks |
|           23 |     7149 | 2024-01-24 | EZ4ENCE                  | W   | 0.355      | -            | -                | -                | 0 (0.000) |     1.86 | dangeR, dpr, Forleks, supar, tucks |
|           22 |     7191 | 2024-01-23 | FlyQuest                 | L   | 0.349      | -            | -                | -                | -         |    -0.17 | dangeR, dpr, Forleks, supar, tucks |
|           21 |     7198 | 2024-01-22 | Rooster                  | W   | 0.347      | 0.143        | 0.014 (0.001)    | 0.229 (0.011)    | 0 (0.000) |     7.36 | dangeR, dpr, Forleks, supar, tucks |
|           20 |     7252 | 2024-01-22 | FlyQuest                 | L   | 0.342      | -            | -                | -                | -         |    -0.16 | dangeR, dpr, Forleks, supar, tucks |
|           19 |     7254 | 2024-01-21 | Rooster                  | W   | 0.341      | 0.143        | 0.014 (0.001)    | 0.229 (0.011)    | 0 (0.000) |     7.32 | dangeR, dpr, Forleks, supar, tucks |
|           18 |     7299 | 2024-01-20 | FlyQuest                 | L   | 0.333      | -            | -                | -                | -         |    -0.15 | dangeR, dpr, Forleks, supar, tucks |
|           17 |     7373 | 2024-01-20 | DXA Esports              | W   | 0.328      | -            | -                | -                | 0 (0.000) |     1.91 | dangeR, dpr, Forleks, supar, tucks |
|           16 |     7434 | 2024-01-19 | Rooster                  | L   | 0.321      | -            | -                | -                | -         |    -3.18 | dangeR, dpr, Forleks, supar, tucks |
|           15 |     7438 | 2024-01-18 | Vantage Esports          | W   | 0.321      | 0.143        | 0.000 (0.000)    | 0.226 (0.010)    | 0 (0.000) |     4.74 | dangeR, dpr, Forleks, supar, tucks |
|           14 |     7496 | 2024-01-18 | Arcade Esports           | W   | 0.315      | 0.143        | 0.006 (0.000)    | 0.264 (0.012)    | 0 (0.000) |     5.24 | dangeR, dpr, Forleks, supar, tucks |
|           13 |     7498 | 2024-01-17 | Vantage Esports          | W   | 0.314      | 0.143        | 0.000 (0.000)    | 0.226 (0.010)    | 0 (0.000) |     4.85 | dangeR, dpr, Forleks, supar, tucks |
|           12 |     7590 | 2024-01-17 | PatatiPatata             | W   | 0.308      | -            | -                | -                | 0 (0.000) |     1.91 | dangeR, dpr, Forleks, supar, tucks |
|           11 |     7605 | 2024-01-16 | TSLpeek                  | W   | 0.308      | -            | -                | -                | 0 (0.000) |     1.87 | dangeR, dpr, Forleks, supar, tucks |
|           10 |     7690 | 2024-01-15 | FlyQuest                 | L   | 0.301      | -            | -                | -                | -         |    -0.12 | dangeR, dpr, Forleks, supar, tucks |
|            9 |     7720 | 2024-01-15 | KZG                      | W   | 0.295      | 0.143        | 0.011 (0.000)    | 0.223 (0.009)    | -         |     5.74 | dangeR, dpr, Forleks, supar, tucks |
|            8 |     7732 | 2024-01-15 | Underground Esports Club | W   | 0.295      | 0.143        | 0.000 (0.000)    | 0.070 (0.003)    | -         |     3.78 | dangeR, dpr, Forleks, supar, tucks |
|            7 |     7799 | 2024-01-13 | TEAM RKON                | W   | 0.282      | -            | -                | -                | -         |     2.76 | dangeR, dpr, Forleks, supar, tucks |
|            6 |     7805 | 2024-01-12 | StevosFirstCS2           | W   | 0.281      | -            | -                | -                | -         |     2.74 | dangeR, dpr, Forleks, supar, tucks |
|            5 |     7810 | 2024-01-12 | 500x                     | W   | 0.281      | -            | -                | -                | -         |     2.81 | dangeR, dpr, Forleks, supar, tucks |
|            4 |     7886 | 2024-01-11 | Tuvalu Embassy           | W   | 0.274      | -            | -                | -                | -         |     1.82 | dangeR, dpr, Forleks, supar, tucks |
|            3 |     8512 | 2023-12-17 | Vantage Esports          | W   | 0.102      | 0.270        | 0.000 (0.000)    | 0.226 (0.006)    | -         |     1.69 | dangeR, dpr, Forleks, supar, tucks |
|            2 |     8937 | 2023-12-11 | DXA Esports              | W   | 0.062      | 0.270        | 0.005 (0.000)    | 0.196 (0.003)    | -         |     1.22 | dangeR, dpr, Forleks, supar, tucks |
|            1 |     9321 | 2023-12-05 | TEAM RKON                | W   | 0.022      | -            | -                | -                | -         |     0.21 | dangeR, dpr, Forleks, supar, tucks |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($142.33)
- Divide that value by the 5th highest value among all rosters ($300,806.11)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
