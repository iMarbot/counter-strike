### Roster Details<br />
Team Name: ENCE Athena<br />
Roster: Aida, Emmsan, miLo, Waldee, xia<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [209](../standings_global.md)<br />
Regional Rank: [140]( ../standings_europe.md)<br />
Final Rank Value:  703.6<br />
<br />
Final Rank Value (703.6) = Starting Rank Value (691.8) + Head To Head Adjustments (11.8)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.328[<sup>1</sup>](#table2)
- Bounty Collected: 0.247[<sup>2</sup>](#table1)
- Opponent Network: 0.014[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.147<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 691.8
- 400 + ( ( 0.147 - 0.000 ) / ( 0.806 - 0.000 ) ) * 1600 = 691.8


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent              | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins      | H2H Adj. | Roster                          |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           15 |      369 | 2024-04-27 | NIP Impact            | L   | 1.000      | -            | -                | -                | -             |   -13.65 | Aida, Emmsan, miLo, Waldee, xia |
|           14 |      377 | 2024-04-27 | Nemesis (Female team) | W   | 1.000      | 0.143        | 0.004 (0.001)    | 0.035 (0.005)    | false (0.000) |     9.04 | Aida, Emmsan, miLo, Waldee, xia |
|           13 |      814 | 2024-04-19 | Astralis Women        | W   | 1.000      | 0.331        | 0.007 (0.002)    | 0.101 (0.033)    | false (0.000) |    11.38 | Aida, Emmsan, miLo, Waldee, xia |
|           12 |     1394 | 2024-04-06 | MAVKY                 | W   | 1.000      | 0.250        | 0.000 (0.000)    | 0.000 (0.000)    | false (0.000) |     5.02 | Aida, Emmsan, miLo, Waldee, xia |
|           11 |     1410 | 2024-04-06 | Team Pigeons          | L   | 1.000      | -            | -                | -                | -             |    -7.77 | Aida, Emmsan, miLo, Waldee, xia |
|           10 |     1418 | 2024-04-06 | 1win Gang             | W   | 1.000      | 0.262        | 0.007 (0.002)    | 0.061 (0.016)    | false (0.000) |    12.35 | Aida, Emmsan, miLo, Waldee, xia |
|            9 |     1482 | 2024-04-04 | BIG EQUIPA            | L   | 0.992      | -            | -                | -                | -             |   -13.83 | Aida, Emmsan, miLo, Waldee, xia |
|            8 |     1734 | 2024-03-27 | Team Pigeons          | L   | 0.939      | -            | -                | -                | -             |    -7.85 | Aida, Emmsan, miLo, Waldee, xia |
|            7 |     2020 | 2024-03-20 | NIP Impact            | L   | 0.892      | -            | -                | -                | -             |   -14.41 | Aida, Emmsan, miLo, Waldee, xia |
|            6 |     2311 | 2024-03-13 | Guild Esports         | W   | 0.845      | 0.331        | 0.010 (0.003)    | 0.194 (0.054)    | false (0.000) |    13.64 | Aida, Emmsan, miLo, Waldee, xia |
|            5 |     3111 | 2024-02-25 | NAVI Javelins         | L   | 0.730      | -            | -                | -                | -             |    -7.02 | Aida, Emmsan, miLo, Waldee, xia |
|            4 |     3166 | 2024-02-24 | Team Spirit Female    | W   | 0.724      | 0.143        | 0.011 (0.001)    | 0.205 (0.021)    | false (0.000) |    11.51 | Aida, Emmsan, miLo, Waldee, xia |
|            3 |     3176 | 2024-02-24 | FORZE Ladies          | W   | 0.723      | 0.143        | 0.002 (0.000)    | 0.057 (0.006)    | false (0.000) |     9.37 | Aida, Emmsan, miLo, Waldee, xia |
|            2 |     3623 | 2024-02-14 | Nemesis (Female team) | W   | 0.658      | 0.143        | 0.000 (0.000)    | 0.051 (0.005)    | false (0.000) |     5.13 | Aida, Emmsan, miLo, Waldee, xia |
|            1 |     6716 | 2023-11-18 | Team Spirit Female    | L   | 0.071      | -            | -                | -                | -             |    -1.10 | Lina, miLo, oxycet, Waldee, xia |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($1,407.03)
- Divide that value by the 5th highest value among all rosters ($158,437.64)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-04-27 |      1.000 | $107.03        | $107.03         |
| 2024-04-21 |      1.000 | $1,050.00      | $1,050.00       |
| 2024-04-06 |      1.000 | $250.00        | $250.00         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
