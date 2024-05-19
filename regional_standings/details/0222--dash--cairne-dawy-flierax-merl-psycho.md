### Roster Details<br />
Team Name: DASH<br />
Roster: cairne, Dawy, Flierax, Merl, Psycho<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [222](../standings_global.md)<br />
Regional Rank: [146]( ../standings_europe.md)<br />
Final Rank Value:  693.9<br />
<br />
Final Rank Value (693.9) = Starting Rank Value (696.2) + Head To Head Adjustments (-2.4)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.227[<sup>1</sup>](#table2)
- Bounty Collected: 0.296[<sup>2</sup>](#table1)
- Opponent Network: 0.075[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.149<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 696.2
- 400 + ( ( 0.149 - 0.000 ) / ( 0.806 - 0.000 ) ) * 1600 = 696.2


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent            | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                 |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           24 |      536 | 2024-04-24 | DMS                 | L   | 1.000      | -            | -                | -                | -         |   -11.32 | cairne, Dawy, Flierax, Merl, Psycho    |
|           23 |      579 | 2024-04-23 | Aurora Young Blud   | L   | 1.000      | -            | -                | -                | -         |   -13.14 | cairne, Dawy, Flierax, Merl, Psycho    |
|           22 |      613 | 2024-04-22 | HOTU                | L   | 1.000      | -            | -                | -                | -         |   -12.87 | cairne, Dawy, Flierax, Merl, Psycho    |
|           21 |     1861 | 2024-03-24 | L&G                 | L   | 0.918      | -            | -                | -                | -         |   -15.57 | cairne, Dawy, esenthial, Flierax, Merl |
|           20 |     2108 | 2024-03-18 | TBA.ECF             | L   | 0.876      | -            | -                | -                | -         |   -13.94 | cairne, Flierax, kRyTouS, Merl, onic   |
|           19 |     2147 | 2024-03-17 | TBA.ECF             | W   | 0.871      | 0.143        | -                | 0.460 (0.057)    | 0 (0.000) |    13.18 | cairne, Flierax, kRyTouS, Merl, onic   |
|           18 |     2828 | 2024-03-02 | BetBoom Team        | L   | 0.773      | -            | -                | -                | -         |    -0.50 | cairne, Dawy, Flierax, kRyTouS, Merl   |
|           17 |     2840 | 2024-03-02 | ROSOMAHA            | W   | 0.772      | 0.143        | 0.000 (0.000)    | -                | 0 (0.000) |     7.73 | cairne, Dawy, Flierax, kRyTouS, Merl   |
|           16 |     3098 | 2024-02-25 | ENTERPRISE esports  | L   | 0.732      | -            | -                | -                | -         |    -5.61 | cairne, Dawy, Flierax, kRyTouS, Merl   |
|           15 |     3153 | 2024-02-24 | INGLORIOUS          | L   | 0.725      | -            | -                | -                | -         |    -9.52 | cairne, Dawy, Flierax, kRyTouS, Merl   |
|           14 |     3209 | 2024-02-23 | The Chosen Few      | W   | 0.719      | 0.371        | 0.007 (0.002)    | 0.457 (0.122)    | 0 (0.000) |    13.61 | cairne, Dawy, Flierax, kRyTouS, Merl   |
|           13 |     3248 | 2024-02-22 | TBA.ECF             | L   | 0.712      | -            | -                | -                | -         |   -11.56 | cairne, Dawy, Flierax, kRyTouS, Merl   |
|           12 |     3291 | 2024-02-21 | VP.Prodigy          | L   | 0.706      | -            | -                | -                | -         |    -8.72 | cairne, Dawy, Flierax, kRyTouS, Merl   |
|           11 |     3673 | 2024-02-13 | Soda Gaming         | W   | 0.652      | 0.371        | 0.009 (0.002)    | 0.182 (0.044)    | 0 (0.000) |     9.70 | cairne, Dawy, Flierax, kRyTouS, Merl   |
|           10 |     3724 | 2024-02-12 | RUBY                | L   | 0.645      | -            | -                | -                | -         |    -5.79 | cairne, Dawy, Flierax, kRyTouS, Merl   |
|            9 |     3741 | 2024-02-11 | GODSENT             | L   | 0.639      | -            | -                | -                | -         |    -9.24 | cairne, Dawy, Flierax, kRyTouS, Merl   |
|            8 |     3744 | 2024-02-11 | 500                 | W   | 0.639      | 0.143        | 0.003 (0.000)    | 0.660 (0.060)    | 0 (0.000) |    12.42 | cairne, Dawy, Flierax, kRyTouS, Merl   |
|            7 |     3752 | 2024-02-11 | HyperSpirit         | W   | 0.638      | 0.143        | 0.009 (0.001)    | 0.293 (0.027)    | 0 (0.000) |     8.69 | cairne, Dawy, Flierax, kRyTouS, Merl   |
|            6 |     3888 | 2024-02-05 | Ex-KRC Genk Esports | W   | 0.599      | 0.371        | 0.008 (0.002)    | 0.181 (0.040)    | 0 (0.000) |    10.83 | cairne, Dawy, Flierax, kRyTouS, Merl   |
|            5 |     3920 | 2024-02-04 | Passion UA          | W   | 0.592      | 0.371        | 0.114 (0.025)    | 0.980 (0.215)    | 0 (0.000) |    15.09 | cairne, Dawy, Flierax, kRyTouS, Merl   |
|            4 |     4026 | 2024-02-02 | LODIS               | W   | 0.578      | 0.371        | 0.002 (0.001)    | 0.139 (0.030)    | 0 (0.000) |     7.25 | cairne, Dawy, Flierax, kRyTouS, Merl   |
|            3 |     4072 | 2024-02-01 | GamerLegion Academy | W   | 0.572      | 0.371        | 0.043 (0.009)    | 0.567 (0.120)    | 0 (0.000) |    12.28 | cairne, Dawy, Flierax, kRyTouS, Merl   |
|            2 |     4457 | 2024-01-22 | RoundsGG            | W   | 0.506      | 0.371        | 0.000 (0.000)    | 0.170 (0.032)    | -         |     8.85 | cairne, Dawy, Flierax, kRyTouS, Merl   |
|            1 |     4470 | 2024-01-22 | EsmagaB             | L   | 0.505      | -            | -                | -                | -         |    -4.22 | cairne, Dawy, Flierax, kRyTouS, Merl   |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($61.52)
- Divide that value by the 5th highest value among all rosters ($158,437.64)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
