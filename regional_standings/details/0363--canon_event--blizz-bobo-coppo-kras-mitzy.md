### Roster Details<br />
Team Name: Canon Event<br />
Roster: Blizz, BoBo, Coppo, Kras, mitzy<br />
Region: [Asia]( ../standings_asia.md)<br />
<br />
Global Rank: [363](../standings_global.md)<br />
Regional Rank: [59]( ../standings_asia.md)<br />
Final Rank Value:  373.2<br />
<br />
Final Rank Value (373.2) = Starting Rank Value (400.0) + Head To Head Adjustments (-26.8)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.000[<sup>1</sup>](#table2)
- Bounty Collected: 0.000[<sup>2</sup>](#table1)
- Opponent Network: 0.000[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.000<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 400.0
- 400 + ( ( 0.000 - 0.000 ) / ( 0.806 - 0.000 ) ) * 1600 = 400.0


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent                         | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                           |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           15 |      960 | 2024-04-17 | Rooster                          | L   | 1.000      | -            | -                | -                | -         |    -1.61 | Blizz, BoBo, Coppo, Kras, mitzy  |
|           14 |      973 | 2024-04-17 | Arcade Esports (Australian team) | W   | 1.000      | 0.143        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |    15.77 | Blizz, BoBo, Coppo, Kras, mitzy  |
|           13 |     1247 | 2024-04-10 | KZG                              | L   | 1.000      | -            | -                | -                | -         |    -4.36 | Blizz, BoBo, Coppo, Kras, mitzy  |
|           12 |     1253 | 2024-04-10 | KZG                              | L   | 1.000      | -            | -                | -                | -         |    -4.55 | Blizz, BoBo, Coppo, Kras, mitzy  |
|           11 |     1553 | 2024-04-03 | Mindfreak (Australian team)      | L   | 0.983      | -            | -                | -                | -         |    -3.66 | Blizz, BoBo, Coppo, Kras, mitzy  |
|           10 |     1557 | 2024-04-03 | Mindfreak (Australian team)      | L   | 0.983      | -            | -                | -                | -         |    -3.79 | Blizz, BoBo, Coppo, Kras, mitzy  |
|            9 |     1771 | 2024-03-27 | Vantage Esports                  | L   | 0.937      | -            | -                | -                | -         |    -6.23 | Blizz, BoBo, Coppo, Kras, mitzy  |
|            8 |     1775 | 2024-03-27 | Vantage Esports                  | L   | 0.936      | -            | -                | -                | -         |    -6.59 | Blizz, BoBo, Coppo, Kras, mitzy  |
|            7 |     2036 | 2024-03-20 | Bad News Kangaroos               | L   | 0.889      | -            | -                | -                | -         |    -1.24 | Blizz, BoBo, Coppo, Kras, mitzy  |
|            6 |     2037 | 2024-03-20 | Bad News Kangaroos               | L   | 0.889      | -            | -                | -                | -         |    -1.26 | Blizz, BoBo, Coppo, Kras, mitzy  |
|            5 |     3046 | 2024-02-27 | VexX Gaming                      | L   | 0.743      | -            | -                | -                | -         |    -2.98 | Blizz, BoBo, Coppo, Kras, mitzy  |
|            4 |     3049 | 2024-02-27 | VexX Gaming                      | L   | 0.743      | -            | -                | -                | -         |    -3.06 | Blizz, BoBo, Coppo, Kras, mitzy  |
|            3 |     3851 | 2024-02-07 | FlyQuest                         | L   | 0.609      | -            | -                | -                | -         |    -0.08 | Blizz, BoBo, Coppo, Kras, Redav  |
|            2 |     5852 | 2023-12-08 | TEAM RKON                        | L   | 0.203      | -            | -                | -                | -         |    -2.30 | Blizz, Coppo, Kras, LBoBo, Redav |
|            1 |     5902 | 2023-12-07 | DXA Esports                      | L   | 0.196      | -            | -                | -                | -         |    -0.81 | Blizz, Coppo, Kras, LBoBo, Redav |

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
