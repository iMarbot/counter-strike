### Roster Details<br />
Team Name: Heimo Esports<br />
Roster: arvid, japE, oopee, Welho, ykis<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [137](../standings_global.md)<br />
Regional Rank: [95]( ../standings_europe.md)<br />
Final Rank Value:  791.5<br />
<br />
Final Rank Value (791.5) = Starting Rank Value (732.5) + Head To Head Adjustments (59.0)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.372[<sup>1</sup>](#table2)
- Bounty Collected: 0.266[<sup>2</sup>](#table1)
- Opponent Network: 0.033[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.168<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 732.5
- 400 + ( ( 0.168 - 0.000 ) / ( 0.806 - 0.000 ) ) * 1600 = 732.5


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent            | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                             |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           17 |       13 | 2024-05-05 | ENCE Academy        | W   | 1.000      | 0.143        | 0.028 (0.004)    | 0.267 (0.038)    | 0 (0.000) |    15.87 | arvid, japE, oopee, Welho, ykis    |
|           16 |      321 | 2024-04-28 | ENCE Academy        | W   | 1.000      | 0.143        | 0.028 (0.004)    | 0.267 (0.038)    | 0 (0.000) |    18.13 | arvid, japE, oopee, Welho, ykis    |
|           15 |      379 | 2024-04-27 | JANO Esports        | W   | 1.000      | 0.143        | 0.006 (0.001)    | 0.407 (0.058)    | 0 (0.000) |    14.35 | arvid, japE, oopee, Welho, ykis    |
|           14 |      802 | 2024-04-19 | Static              | L   | 1.000      | -            | -                | -                | -         |   -25.02 | arvid, japE, oopee, Welho, ykis    |
|           13 |      804 | 2024-04-19 | DUSTY               | W   | 1.000      | 0.143        | 0.015 (0.002)    | 0.233 (0.033)    | 0 (0.000) |    13.78 | arvid, japE, oopee, Welho, ykis    |
|           12 |      807 | 2024-04-19 | VELLAMO             | W   | 1.000      | 0.143        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     3.63 | arvid, japE, oopee, Welho, ykis    |
|           11 |      922 | 2024-04-17 | Guild Eagles        | L   | 1.000      | -            | -                | -                | -         |    -5.61 | arvid, japE, oopee, Welho, ykis    |
|           10 |     1076 | 2024-04-14 | JANO Esports        | W   | 1.000      | 0.143        | 0.006 (0.001)    | 0.407 (0.058)    | 0 (0.000) |    15.36 | arvid, japE, oopee, Welho, ykis    |
|            9 |     1393 | 2024-04-06 | Puhevika            | W   | 1.000      | 0.143        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     4.06 | arvid, japE, oopee, Welho, ykis    |
|            8 |     1755 | 2024-03-27 | ALTERNATE aTTaX     | L   | 0.938      | -            | -                | -                | -         |    -7.21 | arvid, japE, oopee, Welho, ykis    |
|            7 |     1807 | 2024-03-26 | ENTERPRISE esports  | W   | 0.932      | 0.143        | 0.039 (0.005)    | 0.476 (0.063)    | 0 (0.000) |    21.57 | arvid, japE, oopee, Welho, ykis    |
|            6 |     3948 | 2024-02-03 | TOOMUCHVIDEOGAMES   | L   | 0.585      | -            | -                | -                | -         |   -13.86 | arvid, japE, oopee, ottob, Tumppis |
|            5 |     3953 | 2024-02-03 | JANO Esports        | W   | 0.585      | 0.143        | 0.006 (0.001)    | 0.407 (0.034)    | 0 (0.000) |    10.55 | arvid, japE, oopee, ottob, Tumppis |
|            4 |     3960 | 2024-02-03 | UHKA eSports        | W   | 0.585      | 0.143        | 0.000 (0.000)    | 0.029 (0.002)    | 0 (0.000) |     2.57 | arvid, japE, oopee, ottob, Tumppis |
|            3 |     4732 | 2024-01-17 | Team Spirit Academy | L   | 0.472      | -            | -                | -                | -         |    -5.51 | arvid, japE, oopee, ottob, Tumppis |
|            2 |     6043 | 2023-12-03 | ILLYRIANS           | L   | 0.171      | -            | -                | -                | -         |    -2.71 | arvid, japE, oopee, ottob, Tumppis |
|            1 |     6711 | 2023-11-18 | The Witchers        | L   | 0.072      | -            | -                | -                | -         |    -0.98 | arvid, japE, oopee, ottob, Tumppis |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($3,231.54)
- Divide that value by the 5th highest value among all rosters ($158,437.64)
- The final value (0.02) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
