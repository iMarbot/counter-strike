### Roster Details<br />
Team Name: INFURITY Gaming<br />
Roster: kk, murb, Nolv1n, sirius, Twinkey<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [353](../standings_global.md)<br />
Regional Rank: [220]( ../standings_europe.md)<br />
Final Rank Value:  480.2<br />
<br />
Final Rank Value (480.2) = Starting Rank Value (405.0) + Head To Head Adjustments (75.2)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.000[<sup>1</sup>](#table2)
- Bounty Collected: 0.000[<sup>2</sup>](#table1)
- Opponent Network: 0.010[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.003<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 405.0
- 400 + ( ( 0.003 - 0.000 ) / ( 0.806 - 0.000 ) ) * 1600 = 405.0


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent                        | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                             |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           15 |      308 | 2024-04-28 | Metizport X                     | L   | 1.000      | -            | -                | -                | -         |   -10.96 | kk, murb, Nolv1n, sirius, Twinkey  |
|           14 |      610 | 2024-04-22 | Nordix Esport                   | W   | 1.000      | 0.143        | 0.000 (0.000)    | 0.152 (0.022)    | 0 (0.000) |    14.12 | kk, murb, Nolv1n, sirius, Twinkey  |
|           13 |     1050 | 2024-04-15 | Foxed Gaming                    | W   | 1.000      | 0.143        | 0.000 (0.000)    | 0.114 (0.016)    | 0 (0.000) |    10.56 | kk, murb, Nolv1n, sirius, Twinkey  |
|           12 |     1332 | 2024-04-08 | Bitfix Gaming                   | W   | 1.000      | 0.143        | 0.000 (0.000)    | 0.031 (0.004)    | 0 (0.000) |    12.16 | kk, murb, Nolv1n, sirius, Twinkey  |
|           11 |     1801 | 2024-03-26 | 9z Team                         | L   | 0.932      | -            | -                | -                | -         |    -1.16 | kk, murb, Musashi, sirius, Twinkey |
|           10 |     2091 | 2024-03-18 | Wizard esports (Norwegian team) | W   | 0.878      | 0.143        | 0.000 (0.000)    | 0.122 (0.015)    | 0 (0.000) |    12.07 | kk, murb, Nolv1n, sirius, Twinkey  |
|            9 |     2126 | 2024-03-17 | 777 Esports                     | L   | 0.872      | -            | -                | -                | -         |    -3.96 | kk, Musashi, Pham, sirius, Twinkey |
|            8 |     2168 | 2024-03-16 | Center Gaming                   | W   | 0.865      | 0.143        | 0.000 (0.000)    | 0.028 (0.003)    | 0 (0.000) |    11.62 | kk, Musashi, Pham, sirius, Twinkey |
|            7 |     2318 | 2024-03-13 | Cashout Cavaliers               | W   | 0.845      | 0.143        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |    11.61 | kk, Nolv1n, Pham, sirius, Twinkey  |
|            6 |     2417 | 2024-03-11 | Static                          | L   | 0.832      | -            | -                | -                | -         |   -10.56 | kk, murb, Nolv1n, sirius, Twinkey  |
|            5 |     2489 | 2024-03-09 | Static                          | W   | 0.819      | 0.143        | 0.000 (0.000)    | 0.226 (0.026)    | 0 (0.000) |    15.73 | kk, Musashi, Pham, sirius, Twinkey |
|            4 |     2614 | 2024-03-06 | 777 Esports                     | L   | 0.799      | -            | -                | -                | -         |    -3.52 | kk, Musashi, Pham, sirius, Twinkey |
|            3 |     2759 | 2024-03-04 | Vanir                           | W   | 0.785      | 0.143        | 0.000 (0.000)    | 0.070 (0.008)    | 0 (0.000) |    11.16 | kk, murb, Nolv1n, sirius, Twinkey  |
|            2 |     3716 | 2024-02-12 | 777 Esports                     | L   | 0.645      | -            | -                | -                | -         |    -2.78 | Arob, kk, Nolv1n, sirius, Twinkey  |
|            1 |     3894 | 2024-02-05 | Apeks Legends                   | W   | 0.598      | 0.143        | 0.000 (0.000)    | 0.058 (0.005)    | 0 (0.000) |     9.18 | Arob, kk, Nolv1n, sirius, Twinkey  |

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
