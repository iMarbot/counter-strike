### Roster Details<br />
Team Name: Hype Esports<br />
Roster: history, leo_drk, MaLLby, rainny, vinaabEAST<br />
Region: [Americas]( ../standings_americas.md)<br />
<br />
Global Rank: [231](../standings_global.md)<br />
Regional Rank: [49]( ../standings_americas.md)<br />
Final Rank Value:  700.8<br />
<br />
Final Rank Value (700.8) = Starting Rank Value (574.9) + Head To Head Adjustments (126.0)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.000[<sup>1</sup>](#table2)
- Bounty Collected: 0.263[<sup>2</sup>](#table1)
- Opponent Network: 0.081[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.086<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 574.9
- 400 + ( ( 0.086 - 0.000 ) / ( 0.786 - 0.000 ) ) * 1600 = 574.9


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
|           19 |       74 | 2024-05-29 | Sensei Team         | W   | 1.000      | 0.143        | 0.003 (0.000)    | 0.482 (0.069)    | 0 (0.000) |    17.57 | history, leo_drk, MaLLby, rainny, vinaabEAST |
|           18 |      107 | 2024-05-28 | eSports Recife      | L   | 1.000      | -            | -                | -                | -         |   -12.61 | history, leo_drk, MaLLby, rainny, vinaabEAST |
|           17 |      116 | 2024-05-28 | Corinthians Esports | W   | 1.000      | 0.384        | 0.002 (0.001)    | 0.553 (0.212)    | 0 (0.000) |    19.67 | history, leo_drk, MaLLby, rainny, vinaabEAST |
|           16 |      460 | 2024-05-22 | Corinthians Esports | L   | 1.000      | -            | -                | -                | -         |   -12.91 | Buddy, history, leo_drk, MaLLby, rainny      |
|           15 |      650 | 2024-05-20 | Sensei Team         | W   | 1.000      | 0.143        | 0.003 (0.000)    | 0.482 (0.069)    | 0 (0.000) |    17.53 | Buddy, history, leo_drk, MaLLby, rainny      |
|           14 |      957 | 2024-05-17 | Case Esports        | L   | 1.000      | -            | -                | -                | -         |    -7.66 | history, leo_drk, MaLLby, r1see, rainny      |
|           13 |     1062 | 2024-05-16 | Sharks Esports      | L   | 1.000      | -            | -                | -                | -         |    -6.61 | BALEROSTYLE, history, leo_drk, r1see, rainny |
|           12 |     1078 | 2024-05-16 | TIME DE PESO        | W   | 1.000      | 0.143        | 0.000 (0.000)    | 0.028 (0.004)    | 0 (0.000) |     7.02 | Buddy, history, leo_drk, MaLLby, rainny      |
|           11 |     1133 | 2024-05-15 | Galorys             | L   | 1.000      | -            | -                | -                | -         |    -9.00 | history, leo_drk, MaLLby, r1see, rainny      |
|           10 |     1154 | 2024-05-15 | BESTIA              | W   | 1.000      | 0.143        | 0.026 (0.004)    | 0.477 (0.068)    | 0 (0.000) |    24.53 | history, leo_drk, MaLLby, r1see, rainny      |
|            9 |     1266 | 2024-05-14 | Case Esports        | W   | 1.000      | 0.303        | 0.028 (0.009)    | 0.461 (0.140)    | 0 (0.000) |    23.01 | history, leo_drk, MaLLby, r1see, rainny      |
|            8 |     1318 | 2024-05-13 | Fluxo               | L   | 1.000      | -            | -                | -                | -         |    -2.21 | history, leo_drk, MaLLby, r1see, rainny      |
|            7 |     2222 | 2024-04-26 | Corinthians Esports | W   | 0.979      | 0.143        | 0.002 (0.000)    | 0.553 (0.077)    | 0 (0.000) |    17.45 | history, leo_drk, MaLLby, r1see, rainny      |
|            6 |     2225 | 2024-04-26 | Sharks Youngsters   | W   | 0.979      | 0.143        | 0.003 (0.000)    | 0.422 (0.059)    | 0 (0.000) |    15.66 | history, leo_drk, MaLLby, r1see, rainny      |
|            5 |     2233 | 2024-04-26 | Sensei Team         | W   | 0.978      | 0.143        | 0.003 (0.000)    | 0.482 (0.067)    | 0 (0.000) |    20.78 | history, leo_drk, MaLLby, r1see, rainny      |
|            4 |     2337 | 2024-04-24 | Intense Game        | L   | 0.965      | -            | -                | -                | -         |    -9.08 | history, leo_drk, MaLLby, r1see, rainny      |
|            3 |     2341 | 2024-04-24 | 9z Academy          | W   | 0.965      | 0.143        | 0.002 (0.000)    | 0.311 (0.043)    | 0 (0.000) |    16.56 | history, leo_drk, MaLLby, r1see, rainny      |
|            2 |     2397 | 2024-04-23 | fear of god         | W   | 0.959      | -            | -                | -                | -         |     8.05 | history, leo_drk, MaLLby, r1see, rainny      |
|            1 |     2893 | 2024-04-16 | Fluxo               | L   | 0.912      | -            | -                | -                | -         |    -1.78 | history, leo_drk, MaLLby, r1see, rainny      |

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
