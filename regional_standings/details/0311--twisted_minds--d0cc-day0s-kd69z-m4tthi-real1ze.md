### Roster Details<br />
Team Name: Twisted Minds<br />
Roster: D0cC, day0s, KD69z, m4tthi, REAL1ZE<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [311](../standings_global.md)<br />
Regional Rank: [189]( ../standings_europe.md)<br />
Final Rank Value:  600.5<br />
<br />
Final Rank Value (600.5) = Starting Rank Value (616.9) + Head To Head Adjustments (-16.5)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.251[<sup>1</sup>](#table2)
- Bounty Collected: 0.185[<sup>2</sup>](#table1)
- Opponent Network: 0.001[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.109<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 616.9
- 400 + ( ( 0.109 - 0.000 ) / ( 0.806 - 0.000 ) ) * 1600 = 616.9


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent                  | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins      | H2H Adj. | Roster                                        |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           11 |     3051 | 2024-02-26 | JiJieHao                  | L   | 0.741      | -            | -                | -                | -             |   -12.45 | D0cC, day0s, KD69z, m4tthi, REAL1ZE           |
|           10 |     3085 | 2024-02-25 | Lynn Vision Gaming        | L   | 0.735      | -            | -                | -                | -             |    -0.68 | D0cC, day0s, KD69z, m4tthi, REAL1ZE           |
|            9 |     4214 | 2024-01-28 | JiJieHao                  | L   | 0.545      | -            | -                | -                | -             |    -9.96 | D0cC, day0s, KD69z, m4tthi, SpAwNnS           |
|            8 |     4263 | 2024-01-27 | Bravado Gaming            | W   | 0.539      | 0.143        | 0.000 (0.000)    | 0.048 (0.004)    | false (0.000) |     8.37 | D0cC, day0s, KD69z, m4tthi, SpAwNnS           |
|            7 |     4273 | 2024-01-27 | Nixuh                     | W   | 0.538      | 0.143        | 0.004 (0.000)    | 0.115 (0.009)    | false (0.000) |     9.49 | D0cC, day0s, KD69z, m4tthi, SpAwNnS           |
|            6 |     4322 | 2024-01-26 | JiJieHao                  | L   | 0.531      | -            | -                | -                | -             |    -9.78 | D0cC, day0s, KD69z, m4tthi, SpAwNnS           |
|            5 |     4727 | 2024-01-17 | RUBY                      | L   | 0.472      | -            | -                | -                | -             |    -3.00 | D0cC, day0s, KD69z, m4tthi, SpAwNnS           |
|            4 |     5080 | 2024-01-09 | Major Abusers             | W   | 0.419      | 0.143        | 0.000 (0.000)    | 0.014 (0.001)    | false (0.000) |     4.29 | N0R1, REAL1ZE, Revol, Senpai, x1ron           |
|            3 |     5124 | 2024-01-09 | 15 Average Gaming         | L   | 0.418      | -            | -                | -                | -             |    -8.59 | Joker, Lambdacore, Maxwell, Qweall, Ruskovvvv |
|            2 |     5149 | 2024-01-08 | PLASMA RAPID              | W   | 0.412      | 0.143        | 0.000 (0.000)    | 0.000 (0.000)    | false (0.000) |     2.92 | B1zaaD, Djme1ster, ShizzleS, SoLiD, Zinou     |
|            1 |     5587 | 2023-12-15 | Nevermind (Algerian team) | W   | 0.251      | 0.249        | 0.001 (0.000)    | 0.000 (0.000)    | false (0.000) |     2.90 | D0cC, day0s, Fessor, KD69z, SpAwNnS           |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($163.10)
- Divide that value by the 5th highest value among all rosters ($158,437.64)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
