### Roster Details<br />
Team Name: G3 (Asian team)<br />
Roster: calamity, kralz, Laxiee, N20AmZ, obi<br />
Region: [Asia]( ../standings_asia.md)<br />
<br />
Global Rank: [150](../standings_global.md)<br />
Regional Rank: [23]( ../standings_asia.md)<br />
Final Rank Value:  774.6<br />
<br />
Final Rank Value (774.6) = Starting Rank Value (757.5) + Head To Head Adjustments (17.1)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.350[<sup>1</sup>](#table2)
- Bounty Collected: 0.255[<sup>2</sup>](#table1)
- Opponent Network: 0.019[<sup>2</sup>](#table1)
- LAN Wins: 0.097[<sup>2</sup>](#table1)

The average of these factors is 0.180<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 757.5
- 400 + ( ( 0.180 - 0.000 ) / ( 0.806 - 0.000 ) ) * 1600 = 757.5


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent                   | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                    |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           13 |      913 | 2024-04-17 | Team Liquid                | L   | 1.000      | -            | -                | -                | -         |    -0.85 | calamity, kralz, Laxiee, N20AmZ, obi      |
|           12 |      916 | 2024-04-17 | NRG                        | W   | 1.000      | 0.143        | 0.000 (0.000)    | 0.303 (0.043)    | 0 (0.000) |    15.46 | calamity, kralz, Laxiee, N20AmZ, obi      |
|           11 |      988 | 2024-04-16 | Party Astronauts           | W   | 1.000      | 0.143        | 0.036 (0.005)    | 0.374 (0.053)    | 0 (0.000) |    21.14 | calamity, kralz, Laxiee, N20AmZ, obi      |
|           10 |     2110 | 2024-03-17 | LAG Gaming (American team) | L   | 0.874      | -            | -                | -                | -         |    -7.84 | arviast, C4LLM3SU3, calamity, N20AmZ, obi |
|            9 |     2112 | 2024-03-17 | Xiaoma Gaming              | W   | 0.874      | 0.333        | 0.012 (0.004)    | 0.059 (0.017)    | 1 (0.874) |     9.40 | arviast, C4LLM3SU3, calamity, N20AmZ, obi |
|            8 |     3124 | 2024-02-24 | Wildcard Gaming            | L   | 0.727      | -            | -                | -                | -         |    -6.12 | C4LLM3SU3, calamity, N20AmZ, obi, tmk     |
|            7 |     3192 | 2024-02-23 | Take Flyte                 | W   | 0.721      | 0.143        | 0.004 (0.000)    | 0.279 (0.029)    | 0 (0.000) |    10.45 | C4LLM3SU3, calamity, N20AmZ, obi, tmk     |
|            6 |     3272 | 2024-02-21 | Take Flyte                 | L   | 0.707      | -            | -                | -                | -         |   -11.95 | C4LLM3SU3, calamity, Laxiee, N20AmZ, obi  |
|            5 |     3386 | 2024-02-19 | Mythic                     | L   | 0.694      | -            | -                | -                | -         |   -11.64 | C4LLM3SU3, calamity, Laxiee, N20AmZ, obi  |
|            4 |     3394 | 2024-02-19 | Party Astronauts           | L   | 0.693      | -            | -                | -                | -         |    -9.67 | C4LLM3SU3, calamity, Laxiee, N20AmZ, obi  |
|            3 |     3514 | 2024-02-16 | Rocket                     | L   | 0.674      | -            | -                | -                | -         |   -11.23 | C4LLM3SU3, calamity, N20AmZ, obi, tmk     |
|            2 |     3555 | 2024-02-15 | Limitless                  | W   | 0.667      | 0.143        | 0.001 (0.000)    | 0.177 (0.017)    | 0 (0.000) |     8.08 | C4LLM3SU3, calamity, N20AmZ, obi, tmk     |
|            1 |     3556 | 2024-02-15 | Elevate                    | W   | 0.667      | 0.143        | 0.030 (0.003)    | 0.268 (0.026)    | 0 (0.000) |    11.91 | C4LLM3SU3, calamity, N20AmZ, obi, tmk     |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($2,186.00)
- Divide that value by the 5th highest value among all rosters ($158,437.64)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
