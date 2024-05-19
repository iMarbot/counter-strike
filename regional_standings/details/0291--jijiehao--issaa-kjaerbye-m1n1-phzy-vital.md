### Roster Details<br />
Team Name: JiJieHao<br />
Roster: ISSAA, Kjaerbye, m1N1, phzy, ViTaL<br />
Region: [Asia]( ../standings_asia.md)<br />
<br />
Global Rank: [291](../standings_global.md)<br />
Regional Rank: [49]( ../standings_asia.md)<br />
Final Rank Value:  622.9<br />
<br />
Final Rank Value (622.9) = Starting Rank Value (549.1) + Head To Head Adjustments (73.8)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.000[<sup>1</sup>](#table2)
- Bounty Collected: 0.211[<sup>2</sup>](#table1)
- Opponent Network: 0.007[<sup>2</sup>](#table1)
- LAN Wins: 0.083[<sup>2</sup>](#table1)

The average of these factors is 0.075<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 549.1
- 400 + ( ( 0.075 - 0.000 ) / ( 0.806 - 0.000 ) ) * 1600 = 549.1


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent      | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                             |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           12 |      824 | 2024-04-19 | Onyx Ravens   | W   | 1.000      | 0.143        | 0.007 (0.001)    | 0.140 (0.020)    | 0 (0.000) |    19.03 | ISSAA, Kjaerbye, m1N1, phzy, ViTaL |
|           11 |      840 | 2024-04-19 | VC esport     | W   | 1.000      | 0.143        | 0.000 (0.000)    | 0.070 (0.010)    | 0 (0.000) |    11.72 | ISSAA, Kjaerbye, m1N1, phzy, ViTaL |
|           10 |      876 | 2024-04-18 | Onyx Ravens   | L   | 1.000      | -            | -                | -                | -         |   -11.69 | ISSAA, Kjaerbye, m1N1, phzy, ViTaL |
|            9 |      890 | 2024-04-18 | VC esport     | W   | 1.000      | 0.143        | 0.000 (0.000)    | 0.070 (0.010)    | 0 (0.000) |    11.60 | ISSAA, Kjaerbye, m1N1, phzy, ViTaL |
|            8 |     3047 | 2024-02-27 | FlyQuest      | L   | 0.743      | -            | -                | -                | -         |    -0.27 | DavCost, El1an, ISSAA, m1N1, ViTaL |
|            7 |     3051 | 2024-02-26 | Twisted Minds | W   | 0.741      | 0.143        | 0.001 (0.000)    | 0.076 (0.008)    | 1 (0.741) |    12.45 | DavCost, El1an, ISSAA, m1N1, ViTaL |
|            6 |     3084 | 2024-02-25 | TYLOO         | L   | 0.735      | -            | -                | -                | -         |    -1.39 | DavCost, El1an, ISSAA, m1N1, ViTaL |
|            5 |     4206 | 2024-01-28 | Onyx Ravens   | W   | 0.546      | 0.143        | 0.007 (0.001)    | 0.140 (0.011)    | 0 (0.000) |    11.13 | DavCost, El1an, ISSAA, m1N1, ViTaL |
|            4 |     4214 | 2024-01-28 | Twisted Minds | W   | 0.545      | 0.143        | 0.001 (0.000)    | 0.076 (0.006)    | 0 (0.000) |     9.96 | DavCost, El1an, ISSAA, m1N1, ViTaL |
|            3 |     4264 | 2024-01-27 | Team Shush    | W   | 0.539      | 0.143        | 0.000 (0.000)    | 0.019 (0.001)    | 0 (0.000) |     6.88 | DavCost, El1an, ISSAA, m1N1, ViTaL |
|            2 |     4313 | 2024-01-26 | Onyx Ravens   | L   | 0.532      | -            | -                | -                | -         |    -5.34 | DavCost, El1an, ISSAA, m1N1, ViTaL |
|            1 |     4322 | 2024-01-26 | Twisted Minds | W   | 0.531      | 0.143        | 0.001 (0.000)    | 0.076 (0.006)    | 0 (0.000) |     9.78 | DavCost, El1an, ISSAA, m1N1, ViTaL |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($0.00)
- Divide that value by the 5th highest value among all rosters ($158,437.64)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
