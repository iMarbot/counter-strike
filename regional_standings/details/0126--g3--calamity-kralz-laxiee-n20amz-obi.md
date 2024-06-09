### Roster Details<br />
Team Name: G3<br />
Roster: calamity, Kralz, Laxiee, N20AmZ, obi<br />
Region: [Asia]( ../standings_asia.md)<br />
<br />
Global Rank: [126](../standings_global.md)<br />
Regional Rank: [16]( ../standings_asia.md)<br />
Final Rank Value:  819.8<br />
<br />
Final Rank Value (819.8) = Starting Rank Value (814.5) + Head To Head Adjustments (5.4)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.310[<sup>1</sup>](#table2)
- Bounty Collected: 0.249[<sup>2</sup>](#table1)
- Opponent Network: 0.031[<sup>2</sup>](#table1)
- LAN Wins: 0.226[<sup>2</sup>](#table1)

The average of these factors is 0.204<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 814.5
- 400 + ( ( 0.204 - 0.000 ) / ( 0.787 - 0.000 ) ) * 1600 = 814.5


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
|           21 |        9 | 2024-05-29 | NRG               | L   | 1.000      | -            | -                | -                | -         |   -10.63 | calamity, Kralz, Laxiee, N20AmZ, obi      |
|           20 |       24 | 2024-05-29 | FRAUDS            | W   | 1.000      | 0.143        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     2.41 | dantemoren, Kralz, Laxiee, N20AmZ, obi    |
|           19 |      638 | 2024-05-20 | Party Astronauts  | L   | 1.000      | -            | -                | -                | -         |   -10.31 | calamity, Kralz, Laxiee, N20AmZ, obi      |
|           18 |     1030 | 2024-05-16 | regain            | L   | 1.000      | -            | -                | -                | -         |   -24.67 | calamity, Kralz, Laxiee, N20AmZ, obi      |
|           17 |     1034 | 2024-05-16 | Elevate           | W   | 1.000      | 0.143        | 0.012 (0.002)    | 0.480 (0.069)    | 0 (0.000) |    19.42 | calamity, Kralz, Laxiee, N20AmZ, obi      |
|           16 |     1039 | 2024-05-16 | Kinship           | W   | 1.000      | 0.143        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     2.42 | calamity, Kralz, Laxiee, N20AmZ, obi      |
|           15 |     2858 | 2024-04-17 | Team Liquid       | L   | 0.919      | -            | -                | -                | -         |    -0.35 | calamity, kralz, Laxiee, N20AmZ, obi      |
|           14 |     2862 | 2024-04-17 | NRG               | W   | 0.918      | 0.143        | 0.010 (0.001)    | 0.555 (0.073)    | 0 (0.000) |    17.57 | calamity, kralz, Laxiee, N20AmZ, obi      |
|           13 |     2947 | 2024-04-16 | Party Astronauts  | W   | 0.912      | 0.143        | 0.031 (0.004)    | 0.545 (0.071)    | 0 (0.000) |    20.94 | calamity, kralz, Laxiee, N20AmZ, obi      |
|           12 |     4332 | 2024-03-17 | LAG Gaming        | L   | 0.713      | -            | -                | -                | -         |    -7.65 | arviast, C4LLM3SU3, calamity, N20AmZ, obi |
|           11 |     4335 | 2024-03-17 | Xiaoma Gaming     | W   | 0.713      | 0.333        | 0.005 (0.001)    | 0.082 (0.020)    | 1 (0.713) |     9.58 | arviast, C4LLM3SU3, calamity, N20AmZ, obi |
|           10 |     4344 | 2024-03-17 | Snakes Den Gaming | W   | 0.711      | 0.333        | 0.000 (0.000)    | 0.020 (0.005)    | 1 (0.711) |     4.15 | arviast, C4LLM3SU3, calamity, N20AmZ, obi |
|            9 |     4388 | 2024-03-17 | boyfriend_peek9   | W   | 0.710      | -            | -                | -                | 1 (0.710) |     2.19 | arviast, C4LLM3SU3, calamity, N20AmZ, obi |
|            8 |     5645 | 2024-02-24 | Wildcard Gaming   | L   | 0.566      | -            | -                | -                | -         |    -6.00 | C4LLM3SU3, calamity, N20AmZ, obi, tmk     |
|            7 |     5744 | 2024-02-23 | Take Flyte        | W   | 0.560      | 0.143        | 0.006 (0.000)    | 0.354 (0.028)    | 0 (0.000) |     8.23 | C4LLM3SU3, calamity, N20AmZ, obi, tmk     |
|            6 |     5837 | 2024-02-21 | Take Flyte        | L   | 0.546      | -            | -                | -                | -         |    -9.12 | C4LLM3SU3, calamity, Laxiee, N20AmZ, obi  |
|            5 |     5974 | 2024-02-19 | Mythic            | L   | 0.533      | -            | -                | -                | -         |    -9.00 | C4LLM3SU3, calamity, Laxiee, N20AmZ, obi  |
|            4 |     5984 | 2024-02-19 | Party Astronauts  | L   | 0.532      | -            | -                | -                | -         |    -6.11 | C4LLM3SU3, calamity, Laxiee, N20AmZ, obi  |
|            3 |     6139 | 2024-02-16 | Rocket            | L   | 0.512      | -            | -                | -                | -         |   -12.26 | C4LLM3SU3, calamity, N20AmZ, obi, tmk     |
|            2 |     6186 | 2024-02-15 | Limitless         | W   | 0.506      | 0.143        | 0.001 (0.000)    | 0.123 (0.009)    | 0 (0.000) |     5.19 | C4LLM3SU3, calamity, N20AmZ, obi, tmk     |
|            1 |     6187 | 2024-02-15 | Elevate           | W   | 0.506      | 0.143        | 0.012 (0.001)    | 0.480 (0.035)    | -         |     9.36 | C4LLM3SU3, calamity, N20AmZ, obi, tmk     |

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
