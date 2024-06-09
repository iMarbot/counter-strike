### Roster Details<br />
Team Name: Heimo Esports<br />
Roster: arvid, japE, oopee, Welho, ykis<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [182](../standings_global.md)<br />
Regional Rank: [126]( ../standings_europe.md)<br />
Final Rank Value:  745.6<br />
<br />
Final Rank Value (745.6) = Starting Rank Value (723.3) + Head To Head Adjustments (22.3)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.337[<sup>1</sup>](#table2)
- Bounty Collected: 0.257[<sup>2</sup>](#table1)
- Opponent Network: 0.043[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.159<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 723.3
- 400 + ( ( 0.159 - 0.000 ) / ( 0.787 - 0.000 ) ) * 1600 = 723.3


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
|           23 |       60 | 2024-05-29 | MASONIC             | W   | 1.000      | 0.333        | 0.018 (0.006)    | 0.182 (0.061)    | 0 (0.000) |    15.19 | arvid, japE, oopee, Welho, ykis    |
|           22 |     1304 | 2024-05-14 | NOM Esports         | L   | 1.000      | -            | -                | -                | -         |   -18.25 | arvid, japE, oopee, Welho, ykis    |
|           21 |     1341 | 2024-05-13 | DMS                 | L   | 1.000      | -            | -                | -                | -         |    -9.25 | arvid, japE, oopee, Welho, ykis    |
|           20 |     1712 | 2024-05-07 | Team Space          | L   | 1.000      | -            | -                | -                | -         |   -14.82 | arvid, japE, oopee, Welho, ykis    |
|           19 |     1743 | 2024-05-06 | EXO Clan            | L   | 1.000      | -            | -                | -                | -         |    -8.54 | arvid, japE, oopee, Welho, ykis    |
|           18 |     1787 | 2024-05-05 | ENCE Academy        | W   | 1.000      | 0.143        | 0.012 (0.002)    | 0.337 (0.048)    | 0 (0.000) |    16.73 | arvid, japE, oopee, Welho, ykis    |
|           17 |     1843 | 2024-05-04 | jefet               | W   | 1.000      | 0.143        | 0.002 (0.000)    | 0.101 (0.014)    | 0 (0.000) |    12.71 | arvid, japE, oopee, Welho, ykis    |
|           16 |     2160 | 2024-04-28 | ENCE Academy        | W   | 0.989      | 0.143        | 0.012 (0.002)    | 0.337 (0.048)    | 0 (0.000) |    18.97 | arvid, japE, oopee, Welho, ykis    |
|           15 |     2236 | 2024-04-27 | JANO Esports        | W   | 0.982      | 0.143        | 0.003 (0.000)    | 0.419 (0.059)    | 0 (0.000) |    15.45 | arvid, japE, oopee, Welho, ykis    |
|           14 |     2568 | 2024-04-21 | jefet               | L   | 0.942      | -            | -                | -                | -         |   -16.91 | arvid, japE, oopee, Welho, ykis    |
|           13 |     2732 | 2024-04-19 | Static              | L   | 0.931      | -            | -                | -                | -         |   -22.55 | arvid, japE, oopee, Welho, ykis    |
|           12 |     2735 | 2024-04-19 | DUSTY               | W   | 0.931      | 0.143        | 0.006 (0.001)    | 0.148 (0.020)    | 0 (0.000) |    11.74 | arvid, japE, oopee, Welho, ykis    |
|           11 |     2741 | 2024-04-19 | VELLAMO             | W   | 0.931      | 0.143        | 0.000 (0.000)    | -                | 0 (0.000) |     3.55 | arvid, japE, oopee, Welho, ykis    |
|           10 |     2872 | 2024-04-17 | ex-Guild Eagles     | L   | 0.918      | -            | -                | -                | -         |    -6.16 | arvid, japE, oopee, Welho, ykis    |
|            9 |     3054 | 2024-04-14 | JANO Esports        | W   | 0.896      | 0.143        | 0.003 (0.000)    | 0.419 (0.054)    | 0 (0.000) |    14.33 | arvid, japE, oopee, Welho, ykis    |
|            8 |     3462 | 2024-04-06 | Puhevika            | W   | 0.843      | -            | -                | -                | 0 (0.000) |     3.57 | arvid, japE, oopee, Welho, ykis    |
|            7 |     3905 | 2024-03-27 | ALTERNATE aTTaX     | L   | 0.777      | -            | -                | -                | -         |    -5.85 | arvid, japE, oopee, Welho, ykis    |
|            6 |     3968 | 2024-03-26 | ENTERPRISE esports  | W   | 0.771      | 0.143        | 0.010 (0.001)    | 0.898 (0.099)    | 0 (0.000) |    17.58 | arvid, japE, oopee, Welho, ykis    |
|            5 |     6704 | 2024-02-03 | TOOMUCHVIDEOGAMES   | L   | 0.424      | -            | -                | -                | -         |   -10.18 | arvid, japE, oopee, ottob, Tumppis |
|            4 |     6711 | 2024-02-03 | JANO Esports        | W   | 0.424      | 0.143        | 0.003 (0.000)    | 0.419 (0.025)    | -         |     7.86 | arvid, japE, oopee, ottob, Tumppis |
|            3 |     6722 | 2024-02-03 | UHKA eSports        | W   | 0.424      | 0.143        | -                | 0.018 (0.001)    | -         |     1.91 | arvid, japE, oopee, ottob, Tumppis |
|            2 |     7807 | 2024-01-17 | Team Spirit Academy | L   | 0.311      | -            | -                | -                | -         |    -4.63 | arvid, japE, oopee, ottob, Tumppis |
|            1 |     9654 | 2023-12-03 | ILLYRIANS           | L   | 0.010      | -            | -                | -                | -         |    -0.15 | arvid, japE, oopee, ottob, Tumppis |

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
