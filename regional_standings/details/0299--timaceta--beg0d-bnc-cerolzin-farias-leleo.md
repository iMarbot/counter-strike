### Roster Details<br />
Team Name: TIMACETA<br />
Roster: beg0d, bnc, cerolzin, farias, leleo<br />
Region: [Americas]( ../standings_americas.md)<br />
<br />
Global Rank: [299](../standings_global.md)<br />
Regional Rank: [68]( ../standings_americas.md)<br />
Final Rank Value:  641.7<br />
<br />
Final Rank Value (641.7) = Starting Rank Value (627.2) + Head To Head Adjustments (14.5)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.217[<sup>1</sup>](#table2)
- Bounty Collected: 0.223[<sup>2</sup>](#table1)
- Opponent Network: 0.006[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.112<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 627.2
- 400 + ( ( 0.112 - 0.000 ) / ( 0.786 - 0.000 ) ) * 1600 = 627.2


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent                  | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                              |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           23 |     7268 | 2024-01-21 | Flamengo Esports          | L   | 0.337      | -            | -                | -                | -         |    -6.68 | beg0d, bnc, cerolzin, farias, leleo |
|           22 |     7319 | 2024-01-20 | w7m esports               | L   | 0.331      | -            | -                | -                | -         |    -3.41 | beg0d, bnc, cerolzin, farias, leleo |
|           21 |     7385 | 2024-01-19 | MIBR                      | L   | 0.326      | -            | -                | -                | -         |    -0.05 | beg0d, bnc, cerolzin, farias, leleo |
|           20 |     7389 | 2024-01-19 | Sharks Esports            | W   | 0.325      | 0.143        | 0.031 (0.001)    | 0.365 (0.017)    | 0 (0.000) |     8.39 | beg0d, bnc, cerolzin, farias, leleo |
|           19 |     7624 | 2024-01-16 | w7m esports               | L   | 0.305      | -            | -                | -                | -         |    -3.14 | beg0d, bnc, cerolzin, farias, leleo |
|           18 |     7703 | 2024-01-15 | BESTIA                    | W   | 0.299      | 0.143        | 0.026 (0.001)    | 0.477 (0.020)    | 0 (0.000) |     8.01 | beg0d, bnc, cerolzin, farias, leleo |
|           17 |     7913 | 2024-01-11 | adalYamigos               | L   | 0.272      | -            | -                | -                | -         |    -4.24 | beg0d, bnc, cerolzin, farias, leleo |
|           16 |     7920 | 2024-01-11 | KRÜ Esports               | W   | 0.271      | 0.143        | 0.019 (0.001)    | 0.272 (0.011)    | 0 (0.000) |     6.02 | beg0d, bnc, cerolzin, farias, leleo |
|           15 |     7932 | 2024-01-11 | NIGERIA 96                | W   | 0.271      | 0.143        | 0.001 (0.000)    | 0.140 (0.005)    | 0 (0.000) |     4.09 | beg0d, bnc, cerolzin, farias, leleo |
|           14 |     7986 | 2024-01-10 | VISH!                     | W   | 0.265      | -            | -                | -                | 0 (0.000) |     1.80 | beg0d, bnc, cerolzin, farias, leleo |
|           13 |     8067 | 2024-01-09 | Corinthians Esports       | L   | 0.258      | -            | -                | -                | -         |    -4.20 | beg0d, bnc, cerolzin, farias, leleo |
|           12 |     8166 | 2024-01-08 | VELOX Argentina           | W   | 0.253      | 0.143        | -                | 0.030 (0.001)    | 0 (0.000) |     3.38 | beg0d, bnc, cerolzin, farias, leleo |
|           11 |     8377 | 2023-12-20 | Sharks Youngsters         | L   | 0.125      | -            | -                | -                | -         |    -1.71 | beg0d, bnc, cerolzin, farias, leleo |
|           10 |     8393 | 2023-12-19 | Intense Game              | W   | 0.118      | 0.143        | 0.001 (0.000)    | 0.028 (0.000)    | 0 (0.000) |     1.76 | beg0d, bnc, cerolzin, farias, leleo |
|            9 |     8436 | 2023-12-17 | Arena Jogue Fácil Esports | W   | 0.105      | 0.143        | 0.000 (0.000)    | 0.038 (0.001)    | 0 (0.000) |     1.55 | beg0d, bnc, cerolzin, farias, leleo |
|            8 |     8721 | 2023-12-15 | paiN Gaming Academy       | W   | 0.092      | 0.143        | 0.000 (0.000)    | 0.064 (0.001)    | 0 (0.000) |     1.36 | beg0d, bnc, cerolzin, farias, leleo |
|            7 |     8740 | 2023-12-15 | Myth e-Sports             | W   | 0.091      | 0.143        | 0.000 (0.000)    | 0.041 (0.001)    | 0 (0.000) |     1.38 | beg0d, bnc, cerolzin, farias, leleo |
|            6 |     8773 | 2023-12-14 | Case Esports              | L   | 0.085      | -            | -                | -                | -         |    -1.14 | beg0d, bnc, cerolzin, farias, leleo |
|            5 |     8790 | 2023-12-14 | Intense Game              | W   | 0.084      | 0.143        | 0.001 (0.000)    | -                | -         |     1.26 | beg0d, bnc, cerolzin, farias, leleo |
|            4 |     8812 | 2023-12-13 | SOLOVE                    | W   | 0.079      | 0.262        | 0.000 (0.000)    | 0.035 (0.001)    | -         |     1.18 | beg0d, bnc, cerolzin, farias, leleo |
|            3 |     8842 | 2023-12-13 | Sharks Youngsters         | L   | 0.077      | -            | -                | -                | -         |    -1.03 | beg0d, bnc, cerolzin, farias, leleo |
|            2 |     9263 | 2023-12-05 | MIBR Academy              | L   | 0.025      | -            | -                | -                | -         |    -0.33 | beg0d, bnc, cerolzin, farias, leleo |
|            1 |     9325 | 2023-12-04 | Intense Game              | W   | 0.019      | -            | -                | -                | -         |     0.28 | beg0d, bnc, cerolzin, farias, leleo |

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
