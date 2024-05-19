### Roster Details<br />
Team Name: MOUZ<br />
Roster: Brollan, Jimpphat, siuhy, torzsi, xertioN<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [4](../standings_global.md)<br />
Regional Rank: [4]( ../standings_europe.md)<br />
Final Rank Value:  1883.7<br />
<br />
Final Rank Value (1883.7) = Starting Rank Value (1871.5) + Head To Head Adjustments (12.2)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.952[<sup>1</sup>](#table2)
- Bounty Collected: 0.623[<sup>2</sup>](#table1)
- Opponent Network: 0.391[<sup>2</sup>](#table1)
- LAN Wins: 1.000[<sup>2</sup>](#table1)

The average of these factors is 0.742<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1871.5
- 400 + ( ( 0.742 - 0.000 ) / ( 0.806 - 0.000 ) ) * 1600 = 1871.5


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent           | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                    |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           31 |       45 | 2024-05-04 | Team Liquid        | W   | 1.000      | 0.889        | 0.125 (0.111)    | 0.546 (0.486)    | 1 (1.000) |     2.41 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|           30 |      207 | 2024-05-01 | GamerLegion        | W   | 1.000      | 0.889        | 0.194 (0.172)    | 0.419 (0.372)    | 1 (1.000) |     2.52 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|           29 |      251 | 2024-04-30 | Bad News Kangaroos | W   | 1.000      | -            | -                | -                | 1 (1.000) |     0.17 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|           28 |     1079 | 2024-04-14 | FaZe Clan          | L   | 1.000      | -            | -                | -                | -         |   -13.34 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|           27 |     1126 | 2024-04-13 | G2 Esports         | W   | 1.000      | 0.624        | 0.866 (0.540)    | 0.477 (0.298)    | 1 (1.000) |    14.23 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|           26 |     1257 | 2024-04-10 | Team Liquid        | W   | 1.000      | 0.624        | -                | 0.546 (0.341)    | 1 (1.000) |     2.22 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|           25 |     1345 | 2024-04-08 | FURIA Esports      | W   | 1.000      | 0.624        | 0.384 (0.240)    | -                | 1 (1.000) |     4.45 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|           24 |     1357 | 2024-04-07 | TYLOO              | W   | 1.000      | 0.624        | -                | 0.592 (0.369)    | 1 (1.000) |     0.26 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|           23 |     1658 | 2024-03-29 | G2 Esports         | L   | 0.952      | -            | -                | -                | -         |   -15.21 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|           22 |     1944 | 2024-03-22 | Complexity Gaming  | W   | 0.904      | 1.000        | 0.271 (0.245)    | 0.274 (0.248)    | 1 (0.904) |     3.09 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|           21 |     1982 | 2024-03-21 | Eternal Fire       | W   | 0.898      | 1.000        | 0.409 (0.368)    | 0.462 (0.415)    | 1 (0.898) |    10.91 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|           20 |     1994 | 2024-03-21 | Gaimin Gladiators  | W   | 0.897      | 1.000        | 0.194 (0.174)    | 0.989 (0.887)    | 1 (0.897) |     1.66 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|           19 |     3354 | 2024-02-20 | Team Spirit        | W   | 0.698      | -            | -                | -                | -         |    11.13 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|           18 |     3403 | 2024-02-19 | Gaimin Gladiators  | W   | 0.692      | -            | -                | -                | -         |     1.29 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|           17 |     3429 | 2024-02-19 | Guild Eagles       | W   | 0.690      | -            | -                | -                | -         |     0.23 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|           16 |     3775 | 2024-02-10 | FaZe Clan          | L   | 0.631      | -            | -                | -                | -         |    -6.55 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|           15 |     3856 | 2024-02-06 | ENCE               | W   | 0.605      | 1.000        | 0.377 (0.228)    | -                | -         |     3.05 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|           14 |     3904 | 2024-02-05 | GamerLegion        | W   | 0.598      | 1.000        | 0.194 (0.116)    | 0.419 (0.250)    | -         |     3.52 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|           13 |     3931 | 2024-02-04 | Cloud9             | W   | 0.590      | 1.000        | 0.487 (0.288)    | 0.419 (0.248)    | -         |     6.95 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|           12 |     4540 | 2024-01-20 | Preasy Esport      | W   | 0.492      | -            | -                | -                | -         |     0.12 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|           11 |     4558 | 2024-01-20 | Team Spirit        | L   | 0.491      | -            | -                | -                | -         |    -8.34 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|           10 |     4603 | 2024-01-19 | Eternal Fire       | L   | 0.485      | -            | -                | -                | -         |    -9.18 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|            9 |     4655 | 2024-01-18 | HEROIC             | W   | 0.478      | -            | -                | -                | -         |     4.46 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|            8 |     4670 | 2024-01-18 | EYEBALLERS         | W   | 0.478      | -            | -                | -                | -         |     0.10 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|            7 |     6160 | 2023-12-01 | FURIA Esports      | L   | 0.159      | -            | -                | -                | -         |    -3.81 | frozen, Jimpphat, siuhy, torzsi, xertioN  |
|            6 |     6202 | 2023-11-30 | Complexity Gaming  | W   | 0.152      | -            | -                | -                | -         |     0.65 | frozen, Jimpphat, siuhy, torzsi, xertioN  |
|            5 |     6220 | 2023-11-30 | Apeks              | L   | 0.150      | -            | -                | -                | -         |    -4.40 | frozen, Jimpphat, siuhy, torzsi, xertioN  |
|            4 |     7012 | 2023-11-12 | FaZe Clan          | L   | 0.031      | -            | -                | -                | -         |    -0.32 | frozen, Jimpphat, siuhy, torzsi, xertioN  |
|            3 |     7027 | 2023-11-11 | Astralis           | W   | 0.028      | -            | -                | -                | -         |     0.00 | frozen, Jimpphat, siuhy, torzsi, xertioN  |
|            2 |     7079 | 2023-11-10 | Lynn Vision Gaming | W   | 0.021      | -            | -                | -                | -         |     0.02 | frozen, Jimpphat, siuhy, torzsi, xertioN  |
|            1 |     7151 | 2023-11-09 | FaZe Clan          | L   | 0.009      | -            | -                | -                | -         |    -0.10 | frozen, Jimpphat, siuhy, torzsi, xertioN  |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($141,246.99)
- Divide that value by the 5th highest value among all rosters ($158,437.64)
- The final value (0.89) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-04-14 |      1.000 | $42,000.00     | $42,000.00      |
| 2024-03-31 |      0.965 | $45,000.00     | $43,435.42      |
| 2024-02-11 |      0.638 | $80,000.00     | $51,040.74      |
| 2023-12-03 |      0.171 | $10,000.00     | $1,710.65       |
| 2023-11-12 |      0.031 | $100,000.00    | $3,060.19       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
