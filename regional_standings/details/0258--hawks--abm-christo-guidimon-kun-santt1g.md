### Roster Details<br />
Team Name: Hawks<br />
Roster: ABM, christo, guidimon, KUN, santt1g<br />
Region: [Americas]( ../standings_americas.md)<br />
<br />
Global Rank: [258](../standings_global.md)<br />
Regional Rank: [55]( ../standings_americas.md)<br />
Final Rank Value:  677.4<br />
<br />
Final Rank Value (677.4) = Starting Rank Value (658.6) + Head To Head Adjustments (18.8)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.229[<sup>1</sup>](#table2)
- Bounty Collected: 0.253[<sup>2</sup>](#table1)
- Opponent Network: 0.027[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.127<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 658.6
- 400 + ( ( 0.127 - 0.000 ) / ( 0.787 - 0.000 ) ) * 1600 = 658.6


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent               | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                               |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           14 |      111 | 2024-05-28 | LaChampionsLiga        | W   | 1.000      | 0.284        | 0.000 (0.000)    | 0.080 (0.023)    | 0 (0.000) |    10.74 | ABM, christo, guidimon, KUN, santt1g |
|           13 |      151 | 2024-05-27 | Astral Aces Esports    | W   | 1.000      | 0.284        | 0.001 (0.000)    | 0.034 (0.010)    | 0 (0.000) |    13.12 | ABM, christo, guidimon, KUN, santt1g |
|           12 |      177 | 2024-05-27 | Case Esports           | W   | 1.000      | 0.384        | 0.028 (0.011)    | 0.470 (0.181)    | 0 (0.000) |    25.21 | ABM, christo, guidimon, KUN, santt1g |
|           11 |      825 | 2024-05-18 | Sharks Youngsters      | L   | 1.000      | -            | -                | -                | -         |   -14.56 | ABM, christo, KUN, peqexino, santt1g |
|           10 |      827 | 2024-05-18 | Floripa Stars          | W   | 1.000      | 0.143        | 0.001 (0.000)    | 0.144 (0.021)    | 0 (0.000) |    15.45 | ABM, christo, KUN, peqexino, santt1g |
|            9 |      830 | 2024-05-18 | SoJoga                 | W   | 1.000      | 0.143        | 0.000 (0.000)    | 0.138 (0.020)    | 0 (0.000) |    15.01 | ABM, christo, KUN, peqexino, santt1g |
|            8 |      843 | 2024-05-18 | phantom troupe         | W   | 1.000      | 0.143        | 0.000 (0.000)    | 0.111 (0.016)    | 0 (0.000) |    15.19 | ABM, christo, KUN, peqexino, santt1g |
|            7 |      847 | 2024-05-18 | CULTO JOVEM            | W   | 1.000      | 0.143        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     7.63 | ABM, christo, KUN, peqexino, santt1g |
|            6 |      856 | 2024-05-18 | Angels                 | L   | 1.000      | -            | -                | -                | -         |   -19.49 | ABM, christo, KUN, peqexino, santt1g |
|            5 |     2178 | 2024-04-27 | TEAM ORUGA             | L   | 0.985      | -            | -                | -                | -         |   -15.56 | ABM, christo, Gooden, guidimon, KUN  |
|            4 |     2183 | 2024-04-27 | BTH E-Sports           | W   | 0.985      | 0.143        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     6.87 | ABM, christo, Gooden, guidimon, KUN  |
|            3 |     2388 | 2024-04-24 | Bounty Hunters Esports | L   | 0.965      | -            | -                | -                | -         |   -15.85 | ABM, christo, Gooden, guidimon, KUN  |
|            2 |     2593 | 2024-04-20 | MIBR Academy           | L   | 0.938      | -            | -                | -                | -         |   -11.74 | ABM, christo, Gooden, guidimon, KUN  |
|            1 |     3708 | 2024-04-01 | ex-Martians            | L   | 0.812      | -            | -                | -                | -         |   -13.22 | ABM, christo, guidimon, KUN, pablek  |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($127.34)
- Divide that value by the 5th highest value among all rosters ($300,806.11)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
