### Roster Details<br />
Team Name: Nouns.fe<br />
Roster: ashe, jesscas, katalyyst, lunari, raynee<br />
Region: [Americas]( ../standings_americas.md)<br />
<br />
Global Rank: [340](../standings_global.md)<br />
Regional Rank: [83]( ../standings_americas.md)<br />
Final Rank Value:  611.3<br />
<br />
Final Rank Value (611.3) = Starting Rank Value (670.2) + Head To Head Adjustments (-59.0)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.309[<sup>1</sup>](#table2)
- Bounty Collected: 0.219[<sup>2</sup>](#table1)
- Opponent Network: 0.003[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.133<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 670.2
- 400 + ( ( 0.133 - 0.000 ) / ( 0.786 - 0.000 ) ) * 1600 = 670.2


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent             | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                        |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           18 |      248 | 2024-05-25 | Limitless Angels     | L   | 1.000      | -            | -                | -                | -         |   -14.88 | ashe, jesscas, katalyyst, lunari, raynee      |
|           17 |     1792 | 2024-05-04 | Limitless Angels     | L   | 1.000      | -            | -                | -                | -         |   -14.81 | ashe, daria, katalyyst, lunari, toasty        |
|           16 |     2665 | 2024-04-19 | FlyQuest RED         | L   | 0.932      | -            | -                | -                | -         |    -6.91 | ashe, jesscas, katalyyst, lunari, tokkis      |
|           15 |     2999 | 2024-04-13 | TSM Shimmer          | L   | 0.892      | -            | -                | -                | -         |    -9.65 | ashe, katalyyst, Knopk@, lunari, toasty       |
|           14 |     3101 | 2024-04-11 | Limitless Angels     | L   | 0.879      | -            | -                | -                | -         |   -13.71 | ashe, jesscas, katalyyst, lunari, tokkis      |
|           13 |     3471 | 2024-04-04 | cleanup crew         | W   | 0.832      | 0.322        | 0.004 (0.001)    | 0.054 (0.014)    | 0 (0.000) |    12.43 | ashe, jesscas, katalyyst, lunari, tokkis      |
|           12 |     3768 | 2024-03-27 | Team Karma           | L   | 0.779      | -            | -                | -                | -         |   -11.85 | ashe, jesscas, katalyyst, lunari, tokkis      |
|           11 |     4053 | 2024-03-21 | COVEN                | W   | 0.739      | 0.322        | 0.003 (0.001)    | 0.014 (0.003)    | 0 (0.000) |     7.36 | ashe, jesscas, katalyyst, lunari, tokkis      |
|           10 |     4300 | 2024-03-16 | Radiant Rebels       | W   | 0.706      | 0.250        | 0.001 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     6.69 | ashe, jesscas, katalyyst, lunari, Rice        |
|            9 |     4404 | 2024-03-14 | TSM Shimmer          | L   | 0.693      | -            | -                | -                | -         |    -9.59 | ashe, jesscas, katalyyst, lunari, tokkis      |
|            8 |     4839 | 2024-03-06 | Wanted Goons Bandits | W   | 0.639      | 0.322        | 0.003 (0.001)    | 0.039 (0.008)    | 0 (0.000) |     9.71 | ashe, jesscas, katalyyst, lunari, tokkis      |
|            7 |     5114 | 2024-03-02 | FlyQuest RED         | L   | 0.613      | -            | -                | -                | -         |    -6.31 | ashe, jesscas, katalyyst, lunari, Rice        |
|            6 |     5472 | 2024-02-24 | FlyQuest RED         | L   | 0.566      | -            | -                | -                | -         |    -6.29 | ashe, katalyyst, lunari, raynee, Rice         |
|            5 |     6139 | 2024-02-13 | COVEN                | W   | 0.492      | 0.143        | 0.003 (0.000)    | 0.014 (0.001)    | 0 (0.000) |     5.21 | ashe, jesscas, katalyyst, lunari, Rice        |
|            4 |     6485 | 2024-02-03 | FlyQuest RED         | L   | 0.426      | -            | -                | -                | -         |    -4.94 | ashe, jesscas, katalyyst, lunari, Rice        |
|            3 |     8539 | 2023-12-16 | TSM Shimmer          | L   | 0.100      | -            | -                | -                | -         |    -1.33 | ARIANARCHIST, ashe, lunari, MegaGeese, raynee |
|            2 |     9349 | 2023-12-03 | TSM Shimmer          | L   | 0.012      | -            | -                | -                | -         |    -0.16 | ARIANARCHIST, ashe, lunari, raynee, Rice      |
|            1 |     9428 | 2023-12-02 | Wanted Goons Bandits | W   | 0.006      | 0.250        | 0.003 (0.000)    | 0.039 (0.000)    | 0 (0.000) |     0.09 | ARIANARCHIST, ashe, lunari, raynee, Rice      |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($1,744.63)
- Divide that value by the 5th highest value among all rosters ($300,806.11)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-04-19 |      0.932 | $1,300.00      | $1,211.89       |
| 2024-03-16 |      0.706 | $750.00        | $529.67         |
| 2023-12-03 |      0.012 | $250.00        | $3.07           |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
