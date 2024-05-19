### Roster Details<br />
Team Name: LF0<br />
Roster: Akv1lon, HUckLer, JACKPOT, lesswill, SP1NT<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [298](../standings_global.md)<br />
Regional Rank: [182]( ../standings_europe.md)<br />
Final Rank Value:  614.6<br />
<br />
Final Rank Value (614.6) = Starting Rank Value (647.9) + Head To Head Adjustments (-33.3)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.309[<sup>1</sup>](#table2)
- Bounty Collected: 0.186[<sup>2</sup>](#table1)
- Opponent Network: 0.005[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.125<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 647.9
- 400 + ( ( 0.125 - 0.000 ) / ( 0.806 - 0.000 ) ) * 1600 = 647.9


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent                     | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins      | H2H Adj. | Roster                                        |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           15 |     2490 | 2024-03-09 | Oxuji Esports                | L   | 0.819      | -            | -                | -                | -             |   -17.13 | Akv1lon, HUckLer, JACKPOT, lesswill, SP1NT    |
|           14 |     2526 | 2024-03-08 | TEAM MAX (European mix-team) | L   | 0.812      | -            | -                | -                | -             |   -16.86 | Akv1lon, HUckLer, JACKPOT, lesswill, SP1NT    |
|           13 |     5328 | 2023-12-18 | VaselineWorms                | L   | 0.271      | -            | -                | -                | -             |    -4.12 | HUckLer, lesswill, SP1NT, SUROVIY666, Xerison |
|           12 |     5399 | 2023-12-17 | Nemiga Gaming                | L   | 0.263      | -            | -                | -                | -             |    -0.20 | HUckLer, lesswill, SP1NT, SUROVIY666, Xerison |
|           11 |     5485 | 2023-12-16 | XGOD                         | W   | 0.257      | 0.143        | 0.000 (0.000)    | 0.056 (0.002)    | false (0.000) |     2.47 | HUckLer, lesswill, SP1NT, SUROVIY666, Xerison |
|           10 |     5499 | 2023-12-16 | Lewandownskie                | W   | 0.256      | 0.143        | 0.004 (0.000)    | 0.181 (0.007)    | false (0.000) |     4.36 | HUckLer, lesswill, SP1NT, SUROVIY666, Xerison |
|            9 |     5775 | 2023-12-09 | VP.Prodigy                   | L   | 0.210      | -            | -                | -                | -             |    -1.83 | HUckLer, lesswill, SP1NT, SUROVIY666, Xerison |
|            8 |     6316 | 2023-11-28 | Endpoint                     | W   | 0.138      | 0.371        | 0.005 (0.000)    | 0.785 (0.040)    | false (0.000) |     3.32 | HUckLer, lesswill, SP1NT, SUROVIY666, Xerison |
|            7 |     6472 | 2023-11-24 | Ex-sYnck                     | L   | 0.112      | -            | -                | -                | -             |    -2.19 | HUckLer, lesswill, SP1NT, SUROVIY666, Xerison |
|            6 |     6486 | 2023-11-24 | Entropiq                     | L   | 0.111      | -            | -                | -                | -             |    -1.09 | HUckLer, lesswill, SP1NT, SUROVIY666, Xerison |
|            5 |     6735 | 2023-11-18 | BAKS Esports                 | W   | 0.070      | 0.143        | 0.003 (0.000)    | 0.084 (0.001)    | false (0.000) |     1.14 | HUckLer, lesswill, SP1NT, SUROVIY666, Xerison |
|            4 |     6779 | 2023-11-17 | V1dar Gaming                 | L   | 0.064      | -            | -                | -                | -             |    -1.21 | HUckLer, lesswill, SP1NT, SUROVIY666, Xerison |
|            3 |     7021 | 2023-11-12 | Linx Legacy Madagaskar       | W   | 0.029      | 0.143        | 0.000 (0.000)    | 0.028 (0.000)    | false (0.000) |     0.27 | HUckLer, lesswill, SP1NT, SUROVIY666, Xerison |
|            2 |     7099 | 2023-11-10 | Ex-Anonymo Esports           | L   | 0.018      | -            | -                | -                | -             |    -0.19 | HUckLer, lesswill, SP1NT, SUROVIY666, Xerison |
|            1 |     7198 | 2023-11-08 | CYBERSHOKE Esports           | L   | 0.004      | -            | -                | -                | -             |    -0.05 | HUckLer, lesswill, SP1NT, SUROVIY666, Xerison |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($913.42)
- Divide that value by the 5th highest value among all rosters ($158,437.64)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
