### Roster Details<br />
Team Name: ENCE Academy<br />
Roster: 2high, HENU, millert, myltsi, teme<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [187](../standings_global.md)<br />
Regional Rank: [127]( ../standings_europe.md)<br />
Final Rank Value:  742.3<br />
<br />
Final Rank Value (742.3) = Starting Rank Value (841.3) + Head To Head Adjustments (-99.0)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.344[<sup>1</sup>](#table2)
- Bounty Collected: 0.281[<sup>2</sup>](#table1)
- Opponent Network: 0.123[<sup>2</sup>](#table1)
- LAN Wins: 0.119[<sup>2</sup>](#table1)

The average of these factors is 0.217<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 841.3
- 400 + ( ( 0.217 - 0.000 ) / ( 0.786 - 0.000 ) ) * 1600 = 841.3


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent             | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                             |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           39 |      120 | 2024-05-28 | Aurora Young Blud    | L   | 1.000      | -            | -                | -                | -         |   -13.05 | 2high, HENU, millert, myltsi, teme |
|           38 |      132 | 2024-05-28 | Copenhagen Wolves    | W   | 1.000      | 0.333        | -                | 0.330 (0.110)    | 0 (0.000) |    14.36 | 2high, HENU, millert, myltsi, teme |
|           37 |      170 | 2024-05-27 | EXO Clan             | W   | 1.000      | 0.143        | 0.013 (0.002)    | 0.510 (0.073)    | 0 (0.000) |    17.89 | 2high, HENU, millert, myltsi, teme |
|           36 |      361 | 2024-05-24 | Natus Vincere Junior | L   | 1.000      | -            | -                | -                | -         |   -12.77 | 2high, HENU, millert, myltsi, teme |
|           35 |      605 | 2024-05-21 | The Agency Clan      | W   | 1.000      | 0.333        | -                | 0.051 (0.017)    | 0 (0.000) |     6.92 | HENU, millert, myltsi, podi, teme  |
|           34 |      705 | 2024-05-20 | Permitta Esports     | L   | 1.000      | -            | -                | -                | -         |   -11.98 | HENU, millert, myltsi, podi, teme  |
|           33 |     1559 | 2024-05-09 | Preasy Esport        | L   | 1.000      | -            | -                | -                | -         |   -14.04 | 2high, HENU, myltsi, podi, teme    |
|           32 |     1622 | 2024-05-08 | V1dar Gaming         | L   | 1.000      | -            | -                | -                | -         |   -17.01 | 2high, HENU, myltsi, podi, teme    |
|           31 |     1742 | 2024-05-06 | Permitta Esports     | L   | 1.000      | -            | -                | -                | -         |   -10.92 | 2high, HENU, myltsi, podi, teme    |
|           30 |     1764 | 2024-05-05 | Heimo Esports        | L   | 1.000      | -            | -                | -                | -         |   -16.61 | 2high, HENU, myltsi, podi, teme    |
|           29 |     1776 | 2024-05-05 | jefet                | W   | 1.000      | 0.143        | 0.002 (0.000)    | -                | 0 (0.000) |    10.75 | 2high, HENU, myltsi, podi, teme    |
|           28 |     1840 | 2024-05-04 | TOOMUCHVIDEOGAMES    | W   | 1.000      | -            | -                | -                | 0 (0.000) |     6.15 | 2high, HENU, myltsi, podi, teme    |
|           27 |     1896 | 2024-05-03 | Nexus Gaming         | W   | 1.000      | 0.435        | 0.014 (0.006)    | 0.825 (0.358)    | 0 (0.000) |    18.19 | 2high, HENU, myltsi, podi, teme    |
|           26 |     1964 | 2024-05-01 | ENTERPRISE esports   | L   | 1.000      | -            | -                | -                | -         |   -12.89 | 2high, HENU, myltsi, podi, teme    |
|           25 |     2002 | 2024-05-01 | Team Sampi           | L   | 1.000      | -            | -                | -                | -         |    -7.45 | HENU, myltsi, podi, S1rva, teme    |
|           24 |     2034 | 2024-04-30 | Endpoint             | L   | 1.000      | -            | -                | -                | -         |    -9.95 | HENU, myltsi, podi, S1rva, teme    |
|           23 |     2052 | 2024-04-29 | RUSH B               | L   | 0.998      | -            | -                | -                | -         |   -14.54 | 2high, HENU, myltsi, podi, teme    |
|           22 |     2125 | 2024-04-28 | Heimo Esports        | L   | 0.989      | -            | -                | -                | -         |   -18.92 | 2high, HENU, myltsi, podi, teme    |
|           21 |     2468 | 2024-04-22 | ALTERNATE aTTaX      | L   | 0.948      | -            | -                | -                | -         |   -12.08 | HENU, myltsi, podi, S1rva, teme    |
|           20 |     2501 | 2024-04-21 | TOOMUCHVIDEOGAMES    | W   | 0.943      | -            | -                | -                | 0 (0.000) |     4.48 | 2high, HENU, myltsi, podi, teme    |
|           19 |     2622 | 2024-04-20 | SINNERS Esports      | W   | 0.936      | 0.371        | 0.011 (0.004)    | 0.560 (0.194)    | 0 (0.000) |    22.06 | HENU, myltsi, podi, S1rva, teme    |
|           18 |     2732 | 2024-04-19 | Viperio              | L   | 0.928      | -            | -                | -                | -         |   -17.25 | HENU, myltsi, podi, S1rva, teme    |
|           17 |     2786 | 2024-04-18 | MOUZ NXT             | L   | 0.922      | -            | -                | -                | -         |    -5.79 | HENU, myltsi, podi, S1rva, teme    |
|           16 |     2912 | 2024-04-16 | 1win                 | L   | 0.909      | -            | -                | -                | -         |    -8.03 | HENU, myltsi, podi, S1rva, teme    |
|           15 |     2958 | 2024-04-15 | Team Sampi           | W   | 0.903      | 0.371        | 0.039 (0.013)    | 0.665 (0.222)    | -         |    20.48 | HENU, myltsi, podi, S1rva, teme    |
|           14 |     2962 | 2024-04-15 | Viperio              | W   | 0.902      | 0.143        | 0.003 (0.000)    | 0.285 (0.037)    | -         |    11.87 | HENU, myltsi, podi, S1rva, teme    |
|           13 |     3030 | 2024-04-13 | smuuttikusilkki      | W   | 0.890      | -            | -                | -                | -         |     4.07 | 2high, HENU, myltsi, podi, teme    |
|           12 |     3132 | 2024-04-11 | Team Secret          | W   | 0.875      | 0.371        | -                | 0.230 (0.075)    | -         |     8.64 | HENU, myltsi, podi, S1rva, teme    |
|           11 |     4223 | 2024-03-18 | Sprout Academy       | L   | 0.715      | -            | -                | -                | -         |   -18.87 | Diviiii, HENU, myltsi, S1rva, teme |
|           10 |     4509 | 2024-03-13 | Natus Vincere Junior | L   | 0.682      | -            | -                | -                | -         |   -11.26 | Diviiii, HENU, myltsi, S1rva, teme |
|            9 |     4763 | 2024-03-08 | Astralis Talent      | L   | 0.649      | -            | -                | -                | -         |    -8.36 | HENU, myltsi, podi, S1rva, teme    |
|            8 |     5050 | 2024-03-04 | NOM Esports          | L   | 0.623      | -            | -                | -                | -         |   -14.57 | HENU, myltsi, podi, S1rva, teme    |
|            7 |     5107 | 2024-03-03 | ex-K10               | W   | 0.616      | 0.303        | 0.005 (0.001)    | 0.382 (0.071)    | -         |     9.09 | HENU, myltsi, podi, S1rva, teme    |
|            6 |     5294 | 2024-02-29 | Permitta Esports     | L   | 0.595      | -            | -                | -                | -         |    -6.23 | HENU, myltsi, podi, S1rva, teme    |
|            5 |     5374 | 2024-02-27 | ex-K10               | W   | 0.583      | 0.303        | 0.005 (0.001)    | 0.382 (0.068)    | -         |     8.94 | HENU, myltsi, podi, S1rva, teme    |
|            4 |     5504 | 2024-02-24 | HAVU Gaming          | W   | 0.565      | 0.143        | 0.004 (0.000)    | -                | 1 (0.565) |     7.31 | HENU, myltsi, podi, S1rva, teme    |
|            3 |     5568 | 2024-02-24 | ex-sYnck             | W   | 0.562      | 0.143        | 0.000 (0.000)    | -                | 1 (0.562) |     6.66 | HENU, myltsi, podi, S1rva, teme    |
|            2 |     6441 | 2024-02-05 | ROYALS               | L   | 0.435      | -            | -                | -                | -         |   -11.53 | HENU, myltsi, podi, S1rva, teme    |
|            1 |     6693 | 2024-02-01 | Sashi Esport         | L   | 0.409      | -            | -                | -                | -         |    -2.78 | HENU, myltsi, podi, S1rva, teme    |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($3,757.16)
- Divide that value by the 5th highest value among all rosters ($300,806.11)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-05-05 |      1.000 | $1,615.77      | $1,615.77       |
| 2024-02-24 |      0.565 | $3,791.78      | $2,141.39       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
