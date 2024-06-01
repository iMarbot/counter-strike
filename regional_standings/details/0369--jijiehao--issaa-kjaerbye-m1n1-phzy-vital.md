### Roster Details<br />
Team Name: JiJieHao<br />
Roster: ISSAA, Kjaerbye, m1N1, phzy, ViTaL<br />
Region: [Asia]( ../standings_asia.md)<br />
<br />
Global Rank: [369](../standings_global.md)<br />
Regional Rank: [57]( ../standings_asia.md)<br />
Final Rank Value:  590.4<br />
<br />
Final Rank Value (590.4) = Starting Rank Value (524.3) + Head To Head Adjustments (66.1)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.000[<sup>1</sup>](#table2)
- Bounty Collected: 0.179[<sup>2</sup>](#table1)
- Opponent Network: 0.004[<sup>2</sup>](#table1)
- LAN Wins: 0.061[<sup>2</sup>](#table1)

The average of these factors is 0.061<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 524.3
- 400 + ( ( 0.061 - 0.000 ) / ( 0.786 - 0.000 ) ) * 1600 = 524.3


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
|           13 |     2703 | 2024-04-19 | Onyx Ravens   | W   | 0.930      | 0.143        | 0.001 (0.000)    | 0.098 (0.013)    | 0 (0.000) |    16.99 | ISSAA, Kjaerbye, m1N1, phzy, ViTaL |
|           12 |     2719 | 2024-04-19 | VC esport     | W   | 0.929      | 0.143        | 0.000 (0.000)    | 0.051 (0.007)    | 0 (0.000) |    11.48 | ISSAA, Kjaerbye, m1N1, phzy, ViTaL |
|           11 |     2759 | 2024-04-18 | Onyx Ravens   | L   | 0.923      | -            | -                | -                | -         |   -11.65 | ISSAA, Kjaerbye, m1N1, phzy, ViTaL |
|           10 |     2778 | 2024-04-18 | VC esport     | W   | 0.922      | 0.143        | 0.000 (0.000)    | 0.051 (0.007)    | 0 (0.000) |    11.41 | ISSAA, Kjaerbye, m1N1, phzy, ViTaL |
|            9 |     2842 | 2024-04-17 | midnights     | W   | 0.916      | 0.143        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     8.32 | ISSAA, Kjaerbye, m1N1, phzy, ViTaL |
|            8 |     5385 | 2024-02-27 | FlyQuest      | L   | 0.582      | -            | -                | -                | -         |    -0.13 | DavCost, El1an, ISSAA, m1N1, ViTaL |
|            7 |     5388 | 2024-02-26 | Twisted Minds | W   | 0.580      | 0.143        | 0.000 (0.000)    | 0.037 (0.003)    | 1 (0.580) |    10.08 | DavCost, El1an, ISSAA, m1N1, ViTaL |
|            6 |     5429 | 2024-02-25 | TYLOO         | L   | 0.574      | -            | -                | -                | -         |    -2.85 | DavCost, El1an, ISSAA, m1N1, ViTaL |
|            5 |     6850 | 2024-01-28 | Onyx Ravens   | W   | 0.385      | 0.143        | 0.001 (0.000)    | 0.098 (0.005)    | 0 (0.000) |     7.53 | DavCost, El1an, ISSAA, m1N1, ViTaL |
|            4 |     6864 | 2024-01-28 | Twisted Minds | W   | 0.384      | 0.143        | 0.000 (0.000)    | 0.037 (0.002)    | 0 (0.000) |     7.05 | DavCost, El1an, ISSAA, m1N1, ViTaL |
|            3 |     6952 | 2024-01-27 | Team Shush    | W   | 0.378      | 0.143        | 0.000 (0.000)    | 0.017 (0.001)    | 0 (0.000) |     5.22 | DavCost, El1an, ISSAA, m1N1, ViTaL |
|            2 |     7033 | 2024-01-26 | Onyx Ravens   | L   | 0.371      | -            | -                | -                | -         |    -4.17 | DavCost, El1an, ISSAA, m1N1, ViTaL |
|            1 |     7042 | 2024-01-26 | Twisted Minds | W   | 0.370      | 0.143        | 0.000 (0.000)    | 0.037 (0.002)    | 0 (0.000) |     6.86 | DavCost, El1an, ISSAA, m1N1, ViTaL |

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
