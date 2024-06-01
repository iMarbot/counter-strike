### Roster Details<br />
Team Name: G3<br />
Roster: calamity, Kralz, Laxiee, N20AmZ, obi<br />
Region: [Asia]( ../standings_asia.md)<br />
<br />
Global Rank: [138](../standings_global.md)<br />
Regional Rank: [15]( ../standings_asia.md)<br />
Final Rank Value:  795.3<br />
<br />
Final Rank Value (795.3) = Starting Rank Value (776.8) + Head To Head Adjustments (18.5)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.310[<sup>1</sup>](#table2)
- Bounty Collected: 0.249[<sup>2</sup>](#table1)
- Opponent Network: 0.031[<sup>2</sup>](#table1)
- LAN Wins: 0.151[<sup>2</sup>](#table1)

The average of these factors is 0.185<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 776.8
- 400 + ( ( 0.185 - 0.000 ) / ( 0.786 - 0.000 ) ) * 1600 = 776.8


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent          | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                    |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           20 |        9 | 2024-05-29 | NRG               | L   | 1.000      | -            | -                | -                | -         |    -9.68 | calamity, Kralz, Laxiee, N20AmZ, obi      |
|           19 |       24 | 2024-05-29 | FRAUDS            | W   | 1.000      | 0.143        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     2.75 | dantemoren, Kralz, Laxiee, N20AmZ, obi    |
|           18 |      627 | 2024-05-20 | Party Astronauts  | L   | 1.000      | -            | -                | -                | -         |    -9.34 | calamity, Kralz, Laxiee, N20AmZ, obi      |
|           17 |     1018 | 2024-05-16 | regain            | L   | 1.000      | -            | -                | -                | -         |   -23.82 | calamity, Kralz, Laxiee, N20AmZ, obi      |
|           16 |     1022 | 2024-05-16 | Elevate           | W   | 1.000      | 0.143        | 0.012 (0.002)    | 0.475 (0.068)    | 0 (0.000) |    20.62 | calamity, Kralz, Laxiee, N20AmZ, obi      |
|           15 |     1027 | 2024-05-16 | Kinship           | W   | 1.000      | 0.143        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     2.81 | calamity, Kralz, Laxiee, N20AmZ, obi      |
|           14 |     2802 | 2024-04-17 | Team Liquid       | L   | 0.919      | -            | -                | -                | -         |    -0.29 | calamity, kralz, Laxiee, N20AmZ, obi      |
|           13 |     2806 | 2024-04-17 | NRG               | W   | 0.918      | 0.143        | 0.010 (0.001)    | 0.555 (0.073)    | 0 (0.000) |    18.68 | calamity, kralz, Laxiee, N20AmZ, obi      |
|           12 |     2889 | 2024-04-16 | Party Astronauts  | W   | 0.912      | 0.143        | 0.031 (0.004)    | 0.545 (0.071)    | 0 (0.000) |    21.89 | calamity, kralz, Laxiee, N20AmZ, obi      |
|           11 |     4227 | 2024-03-17 | LAG Gaming        | L   | 0.713      | -            | -                | -                | -         |    -6.77 | arviast, C4LLM3SU3, calamity, N20AmZ, obi |
|           10 |     4230 | 2024-03-17 | Xiaoma Gaming     | W   | 0.713      | 0.333        | 0.005 (0.001)    | 0.075 (0.018)    | 1 (0.713) |    10.56 | arviast, C4LLM3SU3, calamity, N20AmZ, obi |
|            9 |     4239 | 2024-03-17 | Snakes Den Gaming | W   | 0.711      | 0.333        | 0.000 (0.000)    | 0.020 (0.005)    | 1 (0.711) |     4.83 | arviast, C4LLM3SU3, calamity, N20AmZ, obi |
|            8 |     5486 | 2024-02-24 | Wildcard Gaming   | L   | 0.566      | -            | -                | -                | -         |    -5.29 | C4LLM3SU3, calamity, N20AmZ, obi, tmk     |
|            7 |     5584 | 2024-02-23 | Take Flyte        | W   | 0.560      | 0.143        | 0.006 (0.000)    | 0.354 (0.028)    | 0 (0.000) |     9.03 | C4LLM3SU3, calamity, N20AmZ, obi, tmk     |
|            6 |     5676 | 2024-02-21 | Take Flyte        | L   | 0.546      | -            | -                | -                | -         |    -8.30 | C4LLM3SU3, calamity, Laxiee, N20AmZ, obi  |
|            5 |     5804 | 2024-02-19 | Mythic            | L   | 0.533      | -            | -                | -                | -         |    -8.34 | C4LLM3SU3, calamity, Laxiee, N20AmZ, obi  |
|            4 |     5814 | 2024-02-19 | Party Astronauts  | L   | 0.532      | -            | -                | -                | -         |    -5.36 | C4LLM3SU3, calamity, Laxiee, N20AmZ, obi  |
|            3 |     5966 | 2024-02-16 | Rocket            | L   | 0.512      | -            | -                | -                | -         |   -11.63 | C4LLM3SU3, calamity, N20AmZ, obi, tmk     |
|            2 |     6010 | 2024-02-15 | Limitless         | W   | 0.506      | 0.143        | 0.001 (0.000)    | 0.123 (0.009)    | 0 (0.000) |     5.94 | C4LLM3SU3, calamity, N20AmZ, obi, tmk     |
|            1 |     6011 | 2024-02-15 | Elevate           | W   | 0.506      | 0.143        | 0.012 (0.001)    | 0.475 (0.034)    | 0 (0.000) |    10.28 | C4LLM3SU3, calamity, N20AmZ, obi, tmk     |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($1,783.33)
- Divide that value by the 5th highest value among all rosters ($300,806.11)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
