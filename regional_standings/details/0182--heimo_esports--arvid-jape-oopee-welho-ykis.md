### Roster Details<br />
Team Name: Heimo Esports<br />
Roster: arvid, japE, oopee, Welho, ykis<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [182](../standings_global.md)<br />
Regional Rank: [124]( ../standings_europe.md)<br />
Final Rank Value:  743.8<br />
<br />
Final Rank Value (743.8) = Starting Rank Value (722.9) + Head To Head Adjustments (20.9)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.337[<sup>1</sup>](#table2)
- Bounty Collected: 0.257[<sup>2</sup>](#table1)
- Opponent Network: 0.041[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.159<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 722.9
- 400 + ( ( 0.159 - 0.000 ) / ( 0.786 - 0.000 ) ) * 1600 = 722.9


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
|           23 |       58 | 2024-05-29 | MASONIC             | W   | 1.000      | 0.333        | 0.018 (0.006)    | 0.182 (0.061)    | 0 (0.000) |    15.22 | arvid, japE, oopee, Welho, ykis    |
|           22 |     1293 | 2024-05-14 | NOM Esports         | L   | 1.000      | -            | -                | -                | -         |   -18.19 | arvid, japE, oopee, Welho, ykis    |
|           21 |     1329 | 2024-05-13 | DMS                 | L   | 1.000      | -            | -                | -                | -         |    -9.44 | arvid, japE, oopee, Welho, ykis    |
|           20 |     1692 | 2024-05-07 | Team Space          | L   | 1.000      | -            | -                | -                | -         |   -14.76 | arvid, japE, oopee, Welho, ykis    |
|           19 |     1721 | 2024-05-06 | EXO Clan            | L   | 1.000      | -            | -                | -                | -         |    -9.02 | arvid, japE, oopee, Welho, ykis    |
|           18 |     1764 | 2024-05-05 | ENCE Academy        | W   | 1.000      | 0.143        | 0.012 (0.002)    | 0.337 (0.048)    | 0 (0.000) |    16.61 | arvid, japE, oopee, Welho, ykis    |
|           17 |     1820 | 2024-05-04 | jefet               | W   | 1.000      | 0.143        | 0.002 (0.000)    | 0.101 (0.014)    | 0 (0.000) |    12.77 | arvid, japE, oopee, Welho, ykis    |
|           16 |     2125 | 2024-04-28 | ENCE Academy        | W   | 0.989      | 0.143        | 0.012 (0.002)    | 0.337 (0.048)    | 0 (0.000) |    18.92 | arvid, japE, oopee, Welho, ykis    |
|           15 |     2201 | 2024-04-27 | JANO Esports        | W   | 0.982      | 0.143        | 0.003 (0.000)    | 0.392 (0.055)    | 0 (0.000) |    14.87 | arvid, japE, oopee, Welho, ykis    |
|           14 |     2515 | 2024-04-21 | jefet               | L   | 0.942      | -            | -                | -                | -         |   -16.87 | arvid, japE, oopee, Welho, ykis    |
|           13 |     2678 | 2024-04-19 | Static              | L   | 0.931      | -            | -                | -                | -         |   -22.52 | arvid, japE, oopee, Welho, ykis    |
|           12 |     2681 | 2024-04-19 | DUSTY               | W   | 0.931      | 0.143        | 0.006 (0.001)    | 0.148 (0.020)    | 0 (0.000) |    12.22 | arvid, japE, oopee, Welho, ykis    |
|           11 |     2685 | 2024-04-19 | VELLAMO             | W   | 0.931      | 0.143        | 0.000 (0.000)    | -                | 0 (0.000) |     3.57 | arvid, japE, oopee, Welho, ykis    |
|           10 |     2815 | 2024-04-17 | ex-Guild Eagles     | L   | 0.918      | -            | -                | -                | -         |    -6.27 | arvid, japE, oopee, Welho, ykis    |
|            9 |     2989 | 2024-04-14 | JANO Esports        | W   | 0.896      | 0.143        | 0.003 (0.000)    | 0.392 (0.050)    | 0 (0.000) |    14.40 | arvid, japE, oopee, Welho, ykis    |
|            8 |     3379 | 2024-04-06 | Puhevika            | W   | 0.843      | -            | -                | -                | 0 (0.000) |     3.58 | arvid, japE, oopee, Welho, ykis    |
|            7 |     3812 | 2024-03-27 | ALTERNATE aTTaX     | L   | 0.777      | -            | -                | -                | -         |    -5.87 | arvid, japE, oopee, Welho, ykis    |
|            6 |     3871 | 2024-03-26 | ENTERPRISE esports  | W   | 0.771      | 0.143        | 0.010 (0.001)    | 0.809 (0.089)    | 0 (0.000) |    17.09 | arvid, japE, oopee, Welho, ykis    |
|            5 |     6501 | 2024-02-03 | TOOMUCHVIDEOGAMES   | L   | 0.424      | -            | -                | -                | -         |   -10.19 | arvid, japE, oopee, ottob, Tumppis |
|            4 |     6508 | 2024-02-03 | JANO Esports        | W   | 0.424      | 0.143        | 0.003 (0.000)    | 0.392 (0.024)    | -         |     7.67 | arvid, japE, oopee, ottob, Tumppis |
|            3 |     6519 | 2024-02-03 | UHKA eSports        | W   | 0.424      | 0.143        | -                | 0.018 (0.001)    | -         |     1.92 | arvid, japE, oopee, ottob, Tumppis |
|            2 |     7558 | 2024-01-17 | Team Spirit Academy | L   | 0.311      | -            | -                | -                | -         |    -4.65 | arvid, japE, oopee, ottob, Tumppis |
|            1 |     9372 | 2023-12-03 | ILLYRIANS           | L   | 0.010      | -            | -                | -                | -         |    -0.15 | arvid, japE, oopee, ottob, Tumppis |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($3,231.54)
- Divide that value by the 5th highest value among all rosters ($300,806.11)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
