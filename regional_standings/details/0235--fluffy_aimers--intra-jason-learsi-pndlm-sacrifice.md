### Roster Details<br />
Team Name: FLUFFY AIMERS<br />
Roster: intra, jason, LEARSI, PNDLM, sacrifice<br />
Region: [Americas]( ../standings_americas.md)<br />
<br />
Global Rank: [235](../standings_global.md)<br />
Regional Rank: [42]( ../standings_americas.md)<br />
Final Rank Value:  677.6<br />
<br />
Final Rank Value (677.6) = Starting Rank Value (673.9) + Head To Head Adjustments (3.7)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.296[<sup>1</sup>](#table2)
- Bounty Collected: 0.246[<sup>2</sup>](#table1)
- Opponent Network: 0.010[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.138<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 673.9
- 400 + ( ( 0.138 - 0.000 ) / ( 0.806 - 0.000 ) ) * 1600 = 673.9


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent                   | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins      | H2H Adj. | Roster                                  |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           16 |     3191 | 2024-02-23 | Limitless                  | L   | 0.721      | -            | -                | -                | -             |   -11.29 | intra, jason, LEARSI, PNDLM, sacrifice  |
|           15 |     3513 | 2024-02-16 | Mythic                     | L   | 0.674      | -            | -                | -                | -             |    -9.92 | intra, jason, LEARSI, PNDLM, sacrifice  |
|           14 |     3516 | 2024-02-16 | LAG Gaming (American team) | W   | 0.673      | 0.143        | 0.033 (0.003)    | 0.405 (0.039)    | false (0.000) |    16.56 | intra, jason, LEARSI, PNDLM, sacrifice  |
|           13 |     3557 | 2024-02-15 | Revenge Nation             | W   | 0.667      | 0.143        | 0.043 (0.004)    | 0.123 (0.012)    | false (0.000) |    11.33 | intra, jason, LEARSI, PNDLM, sacrifice  |
|           12 |     4682 | 2024-01-17 | Rocket                     | L   | 0.474      | -            | -                | -                | -             |    -6.67 | consti, intra, Jason, LEARSI, sacrifice |
|           11 |     4872 | 2024-01-13 | LOS                        | L   | 0.448      | -            | -                | -                | -             |   -10.03 | consti, intra, Jason, LEARSI, sacrifice |
|           10 |     4915 | 2024-01-12 | Complexity Gaming          | L   | 0.441      | -            | -                | -                | -             |    -0.12 | consti, intra, Jason, LEARSI, sacrifice |
|            9 |     4959 | 2024-01-11 | For Fun                    | L   | 0.436      | -            | -                | -                | -             |    -5.17 | consti, intra, Jason, LEARSI, sacrifice |
|            8 |     4974 | 2024-01-11 | Bad News Bears             | W   | 0.434      | 0.143        | 0.000 (0.000)    | 0.039 (0.002)    | false (0.000) |     3.42 | consti, intra, Jason, LEARSI, sacrifice |
|            7 |     4977 | 2024-01-11 | One More Esports           | W   | 0.434      | 0.143        | 0.011 (0.001)    | 0.147 (0.009)    | false (0.000) |     7.58 | consti, intra, Jason, LEARSI, sacrifice |
|            6 |     5021 | 2024-01-10 | CatEvil                    | W   | 0.428      | 0.143        | 0.001 (0.000)    | 0.034 (0.002)    | false (0.000) |     5.91 | consti, intra, Jason, LEARSI, sacrifice |
|            5 |     5913 | 2023-12-06 | Carpe Diem                 | L   | 0.194      | -            | -                | -                | -             |    -2.61 | dea, Jason, LEARSI, Peeping, sacrifice  |
|            4 |     5958 | 2023-12-05 | Take Flyte                 | W   | 0.187      | 0.500        | 0.004 (0.000)    | 0.279 (0.026)    | false (0.000) |     3.31 | dea, Jason, LEARSI, Peeping, sacrifice  |
|            3 |     6541 | 2023-11-22 | Rocket                     | W   | 0.100      | 0.500        | 0.002 (0.000)    | 0.246 (0.012)    | false (0.000) |     1.55 | dea, Jason, LEARSI, Peeping, sacrifice  |
|            2 |     7080 | 2023-11-10 | Party Astronauts           | L   | 0.021      | -            | -                | -                | -             |    -0.34 | dea, Jason, LEARSI, Peeping, sacrifice  |
|            1 |     7157 | 2023-11-08 | Elevate                    | W   | 0.007      | 0.500        | 0.030 (0.000)    | 0.268 (0.001)    | false (0.000) |     0.15 | dea, Jason, LEARSI, Peeping, sacrifice  |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($661.53)
- Divide that value by the 5th highest value among all rosters ($158,437.64)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
