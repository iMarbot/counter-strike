### Roster Details<br />
Team Name: Hype Esports<br />
Roster: history, leo_drk, MaLLby, rainny, vinaabEAST<br />
Region: [Americas]( ../standings_americas.md)<br />
<br />
Global Rank: [239](../standings_global.md)<br />
Regional Rank: [51]( ../standings_americas.md)<br />
Final Rank Value:  695.3<br />
<br />
Final Rank Value (695.3) = Starting Rank Value (572.2) + Head To Head Adjustments (123.1)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.000[<sup>1</sup>](#table2)
- Bounty Collected: 0.263[<sup>2</sup>](#table1)
- Opponent Network: 0.076[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.085<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 572.2
- 400 + ( ( 0.085 - 0.000 ) / ( 0.787 - 0.000 ) ) * 1600 = 572.2


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent            | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                       |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           19 |       79 | 2024-05-29 | Sensei Team         | W   | 1.000      | 0.143        | 0.003 (0.000)    | 0.482 (0.069)    | 0 (0.000) |    17.65 | history, leo_drk, MaLLby, rainny, vinaabEAST |
|           18 |      114 | 2024-05-28 | eSports Recife      | L   | 1.000      | -            | -                | -                | -         |   -12.48 | history, leo_drk, MaLLby, rainny, vinaabEAST |
|           17 |      124 | 2024-05-28 | Corinthians Esports | W   | 1.000      | 0.384        | 0.002 (0.001)    | 0.458 (0.176)    | 0 (0.000) |    17.63 | history, leo_drk, MaLLby, rainny, vinaabEAST |
|           16 |      466 | 2024-05-22 | Corinthians Esports | L   | 1.000      | -            | -                | -                | -         |   -14.82 | Buddy, history, leo_drk, MaLLby, rainny      |
|           15 |      661 | 2024-05-20 | Sensei Team         | W   | 1.000      | 0.143        | 0.003 (0.000)    | 0.482 (0.069)    | 0 (0.000) |    17.43 | Buddy, history, leo_drk, MaLLby, rainny      |
|           14 |      969 | 2024-05-17 | Case Esports        | L   | 1.000      | -            | -                | -                | -         |    -7.74 | history, leo_drk, MaLLby, r1see, rainny      |
|           13 |     1072 | 2024-05-16 | Sharks Esports      | L   | 1.000      | -            | -                | -                | -         |    -5.47 | BALEROSTYLE, history, leo_drk, r1see, rainny |
|           12 |     1088 | 2024-05-16 | TIME DE PESO        | W   | 1.000      | 0.143        | 0.000 (0.000)    | 0.028 (0.004)    | 0 (0.000) |     7.09 | Buddy, history, leo_drk, MaLLby, rainny      |
|           11 |     1142 | 2024-05-15 | Galorys             | L   | 1.000      | -            | -                | -                | -         |    -8.73 | history, leo_drk, MaLLby, r1see, rainny      |
|           10 |     1163 | 2024-05-15 | BESTIA              | W   | 1.000      | 0.143        | 0.026 (0.004)    | 0.500 (0.071)    | 0 (0.000) |    24.47 | history, leo_drk, MaLLby, r1see, rainny      |
|            9 |     1277 | 2024-05-14 | Case Esports        | W   | 1.000      | 0.303        | 0.028 (0.009)    | 0.470 (0.143)    | 0 (0.000) |    23.05 | history, leo_drk, MaLLby, r1see, rainny      |
|            8 |     1330 | 2024-05-13 | Fluxo               | L   | 1.000      | -            | -                | -                | -         |    -2.17 | history, leo_drk, MaLLby, r1see, rainny      |
|            7 |     2258 | 2024-04-26 | Corinthians Esports | W   | 0.979      | 0.143        | 0.002 (0.000)    | 0.458 (0.064)    | 0 (0.000) |    17.17 | history, leo_drk, MaLLby, r1see, rainny      |
|            6 |     2261 | 2024-04-26 | Sharks Youngsters   | W   | 0.979      | 0.143        | 0.003 (0.000)    | 0.407 (0.057)    | 0 (0.000) |    15.29 | history, leo_drk, MaLLby, r1see, rainny      |
|            5 |     2269 | 2024-04-26 | Sensei Team         | W   | 0.978      | 0.143        | 0.003 (0.000)    | 0.482 (0.067)    | 0 (0.000) |    20.83 | history, leo_drk, MaLLby, r1see, rainny      |
|            4 |     2378 | 2024-04-24 | Intense Game        | L   | 0.965      | -            | -                | -                | -         |    -9.06 | history, leo_drk, MaLLby, r1see, rainny      |
|            3 |     2382 | 2024-04-24 | 9z Academy          | W   | 0.965      | 0.143        | 0.002 (0.000)    | 0.311 (0.043)    | 0 (0.000) |    16.61 | history, leo_drk, MaLLby, r1see, rainny      |
|            2 |     2442 | 2024-04-23 | fear of god         | W   | 0.959      | -            | -                | -                | -         |     8.13 | history, leo_drk, MaLLby, r1see, rainny      |
|            1 |     2951 | 2024-04-16 | Fluxo               | L   | 0.912      | -            | -                | -                | -         |    -1.74 | history, leo_drk, MaLLby, r1see, rainny      |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($0.00)
- Divide that value by the 5th highest value among all rosters ($300,806.11)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
