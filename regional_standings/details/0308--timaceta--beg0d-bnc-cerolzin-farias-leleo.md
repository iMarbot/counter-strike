### Roster Details<br />
Team Name: TIMACETA<br />
Roster: beg0d, bnc, cerolzin, farias, leleo<br />
Region: [Americas]( ../standings_americas.md)<br />
<br />
Global Rank: [308](../standings_global.md)<br />
Regional Rank: [68]( ../standings_americas.md)<br />
Final Rank Value:  639.4<br />
<br />
Final Rank Value (639.4) = Starting Rank Value (625.0) + Head To Head Adjustments (14.4)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.217[<sup>1</sup>](#table2)
- Bounty Collected: 0.220[<sup>2</sup>](#table1)
- Opponent Network: 0.006[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.111<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 625.0
- 400 + ( ( 0.111 - 0.000 ) / ( 0.787 - 0.000 ) ) * 1600 = 625.0


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent                  | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                  |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           25 |     7511 | 2024-01-21 | Flamengo Esports          | L   | 0.337      | -            | -                | -                | -         |    -6.65 | beg0d, bnc, cerolzin, farias, leleo     |
|           24 |     7562 | 2024-01-20 | w7m esports               | L   | 0.331      | -            | -                | -                | -         |    -3.43 | beg0d, bnc, cerolzin, farias, leleo     |
|           23 |     7629 | 2024-01-19 | MIBR                      | L   | 0.326      | -            | -                | -                | -         |    -0.05 | beg0d, bnc, cerolzin, farias, leleo     |
|           22 |     7633 | 2024-01-19 | Sharks Esports            | W   | 0.325      | 0.143        | 0.019 (0.001)    | 0.381 (0.018)    | 0 (0.000) |     8.41 | beg0d, bnc, cerolzin, farias, leleo     |
|           21 |     7873 | 2024-01-16 | w7m esports               | L   | 0.305      | -            | -                | -                | -         |    -3.16 | beg0d, bnc, cerolzin, farias, leleo     |
|           20 |     7952 | 2024-01-15 | BESTIA                    | W   | 0.299      | 0.143        | 0.026 (0.001)    | 0.500 (0.021)    | 0 (0.000) |     8.01 | beg0d, bnc, cerolzin, farias, leleo     |
|           19 |     8166 | 2024-01-11 | adalYamigos               | L   | 0.272      | -            | -                | -                | -         |    -4.22 | beg0d, bnc, cerolzin, farias, leleo     |
|           18 |     8173 | 2024-01-11 | KRÜ Esports               | W   | 0.271      | 0.143        | 0.019 (0.001)    | 0.272 (0.011)    | 0 (0.000) |     6.04 | beg0d, bnc, cerolzin, farias, leleo     |
|           17 |     8185 | 2024-01-11 | NIGERIA 96                | W   | 0.271      | 0.143        | 0.001 (0.000)    | 0.140 (0.005)    | 0 (0.000) |     4.11 | beg0d, bnc, cerolzin, farias, leleo     |
|           16 |     8240 | 2024-01-10 | VISH!                     | W   | 0.265      | -            | -                | -                | 0 (0.000) |     1.81 | beg0d, bnc, cerolzin, farias, leleo     |
|           15 |     8321 | 2024-01-09 | Corinthians Esports       | L   | 0.258      | -            | -                | -                | -         |    -4.18 | beg0d, bnc, cerolzin, farias, leleo     |
|           14 |     8420 | 2024-01-08 | VELOX Argentina           | W   | 0.253      | 0.143        | -                | 0.030 (0.001)    | 0 (0.000) |     3.40 | beg0d, bnc, cerolzin, farias, leleo     |
|           13 |     8634 | 2023-12-20 | Sharks Youngsters         | L   | 0.125      | -            | -                | -                | -         |    -2.14 | beg0d, bnc, cerolzin, farias, leleo     |
|           12 |     8650 | 2023-12-19 | Intense Game              | W   | 0.118      | 0.143        | 0.001 (0.000)    | 0.028 (0.000)    | 0 (0.000) |     1.76 | beg0d, bnc, cerolzin, farias, leleo     |
|           11 |     8693 | 2023-12-17 | Arena Jogue Fácil Esports | W   | 0.105      | 0.143        | 0.000 (0.000)    | 0.038 (0.001)    | 0 (0.000) |     1.55 | beg0d, bnc, cerolzin, farias, leleo     |
|           10 |     8982 | 2023-12-15 | paiN Gaming Academy       | W   | 0.092      | 0.143        | 0.000 (0.000)    | 0.064 (0.001)    | 0 (0.000) |     1.37 | beg0d, bnc, cerolzin, farias, leleo     |
|            9 |     9002 | 2023-12-15 | Myth e-Sports             | W   | 0.091      | 0.143        | -                | 0.041 (0.001)    | 0 (0.000) |     1.38 | beg0d, bnc, cerolzin, farias, leleo     |
|            8 |     9036 | 2023-12-14 | Case Esports              | L   | 0.085      | -            | -                | -                | -         |    -1.14 | beg0d, bnc, cerolzin, farias, leleo     |
|            7 |     9053 | 2023-12-14 | Intense Game              | W   | 0.084      | 0.143        | 0.001 (0.000)    | -                | -         |     1.26 | beg0d, bnc, cerolzin, farias, leleo     |
|            6 |     9075 | 2023-12-13 | SOLOVE                    | W   | 0.079      | 0.262        | 0.000 (0.000)    | 0.035 (0.001)    | -         |     1.18 | beg0d, bnc, cerolzin, farias, leleo     |
|            5 |     9106 | 2023-12-13 | Sharks Youngsters         | L   | 0.077      | -            | -                | -                | -         |    -1.31 | beg0d, bnc, cerolzin, farias, leleo     |
|            4 |     9168 | 2023-12-11 | WINDINGO                  | W   | 0.065      | 0.262        | 0.001 (0.000)    | -                | -         |     1.02 | beg0d, bnc, cerolzin, farias, leleo     |
|            3 |     9492 | 2023-12-06 | Vex Dragons               | L   | 0.031      | -            | -                | -                | -         |    -0.56 | crownzera, machado, sanc, void, wallz1k |
|            2 |     9545 | 2023-12-05 | MIBR Academy              | L   | 0.025      | -            | -                | -                | -         |    -0.33 | beg0d, bnc, cerolzin, farias, leleo     |
|            1 |     9607 | 2023-12-04 | Intense Game              | W   | 0.019      | -            | -                | -                | -         |     0.28 | beg0d, bnc, cerolzin, farias, leleo     |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($74.63)
- Divide that value by the 5th highest value among all rosters ($300,806.11)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2023-12-20 |      0.125 | $513.53        | $64.40          |
| 2023-12-05 |      0.025 | $404.47        | $10.22          |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
