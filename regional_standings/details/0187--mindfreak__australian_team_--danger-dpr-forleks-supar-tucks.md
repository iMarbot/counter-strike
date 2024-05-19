### Roster Details<br />
Team Name: Mindfreak (Australian team)<br />
Roster: dangeR, dpr, Forleks, supar, tucks<br />
Region: [Asia]( ../standings_asia.md)<br />
<br />
Global Rank: [187](../standings_global.md)<br />
Regional Rank: [30]( ../standings_asia.md)<br />
Final Rank Value:  738.3<br />
<br />
Final Rank Value (738.3) = Starting Rank Value (664.5) + Head To Head Adjustments (73.8)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.272[<sup>1</sup>](#table2)
- Bounty Collected: 0.244[<sup>2</sup>](#table1)
- Opponent Network: 0.017[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.133<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 664.5
- 400 + ( ( 0.133 - 0.000 ) / ( 0.806 - 0.000 ) ) * 1600 = 664.5


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent                 | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                               |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           30 |     4366 | 2024-01-25 | Rooster                  | L   | 0.522      | -            | -                | -                | -         |    -6.09 | dangeR, dpr, Forleks, supar, tucks   |
|           29 |     4406 | 2024-01-24 | DXA Esports              | W   | 0.516      | 0.143        | 0.010 (0.001)    | 0.266 (0.020)    | 0 (0.000) |     8.20 | dangeR, dpr, Forleks, supar, tucks   |
|           28 |     4409 | 2024-01-24 | EZ4ENCE                  | W   | 0.516      | -            | -                | -                | 0 (0.000) |     2.16 | dangeR, dpr, Forleks, supar, tucks   |
|           27 |     4441 | 2024-01-23 | FlyQuest                 | L   | 0.510      | -            | -                | -                | -         |    -0.41 | dangeR, dpr, Forleks, supar, tucks   |
|           26 |     4447 | 2024-01-22 | Rooster                  | W   | 0.508      | 0.143        | 0.031 (0.002)    | 0.312 (0.023)    | 0 (0.000) |    10.46 | dangeR, dpr, Forleks, supar, tucks   |
|           25 |     4491 | 2024-01-22 | FlyQuest                 | L   | 0.503      | -            | -                | -                | -         |    -0.39 | dangeR, dpr, Forleks, supar, tucks   |
|           24 |     4493 | 2024-01-21 | Rooster                  | W   | 0.502      | 0.143        | 0.031 (0.002)    | 0.312 (0.022)    | 0 (0.000) |    10.74 | dangeR, dpr, Forleks, supar, tucks   |
|           23 |     4523 | 2024-01-20 | FlyQuest                 | L   | 0.494      | -            | -                | -                | -         |    -0.36 | dangeR, dpr, Forleks, supar, tucks   |
|           22 |     4575 | 2024-01-20 | DXA Esports              | W   | 0.489      | -            | -                | -                | 0 (0.000) |     2.37 | dangeR, dpr, Forleks, supar, tucks   |
|           21 |     4624 | 2024-01-19 | Rooster                  | L   | 0.482      | -            | -                | -                | -         |    -4.86 | dangeR, dpr, Forleks, supar, tucks   |
|           20 |     4627 | 2024-01-18 | Vantage Esports          | W   | 0.482      | 0.143        | -                | 0.236 (0.016)    | 0 (0.000) |     4.71 | dangeR, dpr, Forleks, supar, tucks   |
|           19 |     4680 | 2024-01-18 | VexX Gaming              | W   | 0.476      | 0.143        | 0.010 (0.001)    | 0.390 (0.026)    | 0 (0.000) |     7.42 | dangeR, dpr, Forleks, supar, tucks   |
|           18 |     4681 | 2024-01-17 | Vantage Esports          | W   | 0.476      | 0.143        | -                | 0.236 (0.016)    | 0 (0.000) |     4.96 | dangeR, dpr, Forleks, supar, tucks   |
|           17 |     4756 | 2024-01-17 | PatatiPatata             | W   | 0.469      | -            | -                | -                | 0 (0.000) |     2.45 | dangeR, dpr, Forleks, supar, tucks   |
|           16 |     4766 | 2024-01-16 | TSLpeek                  | W   | 0.469      | -            | -                | -                | 0 (0.000) |     2.37 | dangeR, dpr, Forleks, supar, tucks   |
|           15 |     4820 | 2024-01-15 | FlyQuest                 | L   | 0.462      | -            | -                | -                | -         |    -0.31 | dangeR, dpr, Forleks, supar, tucks   |
|           14 |     4842 | 2024-01-15 | KZG                      | W   | 0.456      | 0.143        | 0.020 (0.001)    | 0.249 (0.016)    | -         |     8.25 | dangeR, dpr, Forleks, supar, tucks   |
|           13 |     4854 | 2024-01-15 | Underground Esports Club | W   | 0.456      | 0.143        | 0.000 (0.000)    | 0.112 (0.007)    | -         |     5.29 | dangeR, dpr, Forleks, supar, tucks   |
|           12 |     4899 | 2024-01-13 | TEAM RKON                | W   | 0.443      | 0.143        | -                | 0.092 (0.006)    | -         |     4.07 | dangeR, dpr, Forleks, supar, tucks   |
|           11 |     4904 | 2024-01-12 | StevosFirstCS2           | W   | 0.442      | -            | -                | -                | -         |     3.91 | dangeR, dpr, Forleks, supar, tucks   |
|           10 |     4907 | 2024-01-12 | 500x                     | W   | 0.442      | -            | -                | -                | -         |     4.06 | dangeR, dpr, Forleks, supar, tucks   |
|            9 |     4962 | 2024-01-11 | Tuvalu Embassy           | W   | 0.435      | -            | -                | -                | -         |     2.50 | dangeR, dpr, Forleks, supar, tucks   |
|            8 |     5704 | 2023-12-11 | DXA Esports              | W   | 0.223      | 0.270        | 0.010 (0.001)    | 0.266 (0.016)    | -         |     4.24 | dangeR, dpr, Forleks, supar, tucks   |
|            7 |     6009 | 2023-12-05 | TEAM RKON                | W   | 0.183      | -            | -                | -                | -         |     1.66 | dangeR, dpr, Forleks, supar, tucks   |
|            6 |     6226 | 2023-11-30 | MAKING HISTORY           | L   | 0.149      | -            | -                | -                | -         |    -3.44 | dangeR, dpr, Forleks, supar, tucks   |
|            5 |     6227 | 2023-11-30 | Altered Edge             | W   | 0.149      | 0.143        | 0.003 (0.000)    | -                | -         |     2.32 | dangeR, dpr, Forleks, supar, tucks   |
|            4 |     6342 | 2023-11-27 | MAKING HISTORY           | L   | 0.136      | -            | -                | -                | -         |    -3.14 | dangeR, dpr, Forleks, supar, tucks   |
|            3 |     6792 | 2023-11-17 | KZG                      | W   | 0.063      | 0.314        | 0.000 (0.000)    | -                | -         |     0.73 | cl0ver, coops, Forleks, supar, tucks |
|            2 |     7025 | 2023-11-11 | Rooster                  | L   | 0.029      | -            | -                | -                | -         |    -0.24 | cl0ver, coops, Forleks, supar, tucks |
|            1 |     7076 | 2023-11-10 | Stirlz's Angels          | W   | 0.022      | 0.314        | 0.000 (0.000)    | -                | -         |     0.19 | cl0ver, coops, Forleks, supar, tucks |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($336.38)
- Divide that value by the 5th highest value among all rosters ($158,437.64)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2023-12-11 |      0.223 | $1,400.00      | $312.02         |
| 2023-11-18 |      0.075 | $325.65        | $24.36          |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
