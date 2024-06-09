### Roster Details<br />
Team Name: ENCE Academy<br />
Roster: 2high, HENU, millert, myltsi, teme<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [180](../standings_global.md)<br />
Regional Rank: [125]( ../standings_europe.md)<br />
Final Rank Value:  748.7<br />
<br />
Final Rank Value (748.7) = Starting Rank Value (842.4) + Head To Head Adjustments (-93.6)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.344[<sup>1</sup>](#table2)
- Bounty Collected: 0.275[<sup>2</sup>](#table1)
- Opponent Network: 0.132[<sup>2</sup>](#table1)
- LAN Wins: 0.119[<sup>2</sup>](#table1)

The average of these factors is 0.218<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 842.4
- 400 + ( ( 0.218 - 0.000 ) / ( 0.787 - 0.000 ) ) * 1600 = 842.4


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
|           39 |      128 | 2024-05-28 | Aurora Young Blud    | L   | 1.000      | -            | -                | -                | -         |   -13.36 | 2high, HENU, millert, myltsi, teme |
|           38 |      139 | 2024-05-28 | Copenhagen Wolves    | W   | 1.000      | 0.333        | -                | 0.358 (0.119)    | 0 (0.000) |    15.50 | 2high, HENU, millert, myltsi, teme |
|           37 |      178 | 2024-05-27 | EXO Clan             | W   | 1.000      | 0.143        | 0.013 (0.002)    | 0.579 (0.083)    | 0 (0.000) |    17.98 | 2high, HENU, millert, myltsi, teme |
|           36 |      370 | 2024-05-24 | Natus Vincere Junior | L   | 1.000      | -            | -                | -                | -         |   -12.40 | 2high, HENU, millert, myltsi, teme |
|           35 |      616 | 2024-05-21 | The Agency Clan      | W   | 1.000      | -            | -                | -                | 0 (0.000) |     6.73 | HENU, millert, myltsi, podi, teme  |
|           34 |      717 | 2024-05-20 | Permitta Esports     | L   | 1.000      | -            | -                | -                | -         |   -11.49 | HENU, millert, myltsi, podi, teme  |
|           33 |     1574 | 2024-05-09 | Preasy Esport        | L   | 1.000      | -            | -                | -                | -         |   -14.14 | 2high, HENU, myltsi, podi, teme    |
|           32 |     1639 | 2024-05-08 | V1dar Gaming         | L   | 1.000      | -            | -                | -                | -         |   -16.82 | 2high, HENU, myltsi, podi, teme    |
|           31 |     1765 | 2024-05-06 | Permitta Esports     | L   | 1.000      | -            | -                | -                | -         |   -10.10 | 2high, HENU, myltsi, podi, teme    |
|           30 |     1787 | 2024-05-05 | Heimo Esports        | L   | 1.000      | -            | -                | -                | -         |   -16.73 | 2high, HENU, myltsi, podi, teme    |
|           29 |     1799 | 2024-05-05 | jefet                | W   | 1.000      | 0.143        | 0.002 (0.000)    | -                | 0 (0.000) |    10.59 | 2high, HENU, myltsi, podi, teme    |
|           28 |     1863 | 2024-05-04 | TOOMUCHVIDEOGAMES    | W   | 1.000      | -            | -                | -                | 0 (0.000) |     6.11 | 2high, HENU, myltsi, podi, teme    |
|           27 |     1921 | 2024-05-03 | Nexus Gaming         | W   | 1.000      | 0.435        | 0.003 (0.001)    | 0.857 (0.373)    | 0 (0.000) |    18.27 | 2high, HENU, myltsi, podi, teme    |
|           26 |     1991 | 2024-05-01 | ENTERPRISE esports   | L   | 1.000      | -            | -                | -                | -         |   -12.28 | 2high, HENU, myltsi, podi, teme    |
|           25 |     2033 | 2024-05-01 | Team Sampi           | L   | 1.000      | -            | -                | -                | -         |    -7.49 | HENU, myltsi, podi, S1rva, teme    |
|           24 |     2067 | 2024-04-30 | Endpoint             | L   | 1.000      | -            | -                | -                | -         |    -9.01 | HENU, myltsi, podi, S1rva, teme    |
|           23 |     2086 | 2024-04-29 | RUSH B               | L   | 0.998      | -            | -                | -                | -         |   -14.24 | 2high, HENU, myltsi, podi, teme    |
|           22 |     2160 | 2024-04-28 | Heimo Esports        | L   | 0.989      | -            | -                | -                | -         |   -18.97 | 2high, HENU, myltsi, podi, teme    |
|           21 |     2520 | 2024-04-22 | ALTERNATE aTTaX      | L   | 0.948      | -            | -                | -                | -         |   -12.33 | HENU, myltsi, podi, S1rva, teme    |
|           20 |     2554 | 2024-04-21 | TOOMUCHVIDEOGAMES    | W   | 0.943      | -            | -                | -                | 0 (0.000) |     4.46 | 2high, HENU, myltsi, podi, teme    |
|           19 |     2676 | 2024-04-20 | SINNERS Esports      | W   | 0.936      | 0.371        | 0.011 (0.004)    | 0.582 (0.202)    | 0 (0.000) |    22.90 | HENU, myltsi, podi, S1rva, teme    |
|           18 |     2788 | 2024-04-19 | Viperio              | L   | 0.928      | -            | -                | -                | -         |   -17.21 | HENU, myltsi, podi, S1rva, teme    |
|           17 |     2842 | 2024-04-18 | MOUZ NXT             | L   | 0.922      | -            | -                | -                | -         |    -5.59 | HENU, myltsi, podi, S1rva, teme    |
|           16 |     2973 | 2024-04-16 | 1win                 | L   | 0.909      | -            | -                | -                | -         |    -8.43 | HENU, myltsi, podi, S1rva, teme    |
|           15 |     3022 | 2024-04-15 | Team Sampi           | W   | 0.903      | 0.371        | 0.039 (0.013)    | 0.677 (0.226)    | -         |    20.56 | HENU, myltsi, podi, S1rva, teme    |
|           14 |     3027 | 2024-04-15 | Viperio              | W   | 0.902      | 0.143        | 0.003 (0.000)    | 0.285 (0.037)    | -         |    11.91 | HENU, myltsi, podi, S1rva, teme    |
|           13 |     3096 | 2024-04-13 | smuuttikusilkki      | W   | 0.890      | -            | -                | -                | -         |     4.03 | 2high, HENU, myltsi, podi, teme    |
|           12 |     3202 | 2024-04-11 | Team Secret          | W   | 0.875      | 0.371        | -                | 0.230 (0.075)    | -         |     8.64 | HENU, myltsi, podi, S1rva, teme    |
|           11 |     4328 | 2024-03-18 | Sprout Academy       | L   | 0.715      | -            | -                | -                | -         |   -18.91 | Diviiii, HENU, myltsi, S1rva, teme |
|           10 |     4625 | 2024-03-13 | Natus Vincere Junior | L   | 0.682      | -            | -                | -                | -         |   -11.26 | Diviiii, HENU, myltsi, S1rva, teme |
|            9 |     4891 | 2024-03-08 | Astralis Talent      | L   | 0.649      | -            | -                | -                | -         |    -8.35 | HENU, myltsi, podi, S1rva, teme    |
|            8 |     5196 | 2024-03-04 | NOM Esports          | L   | 0.623      | -            | -                | -                | -         |   -14.59 | HENU, myltsi, podi, S1rva, teme    |
|            7 |     5255 | 2024-03-03 | ex-K10               | W   | 0.616      | 0.303        | 0.005 (0.001)    | 0.517 (0.096)    | -         |     9.25 | HENU, myltsi, podi, S1rva, teme    |
|            6 |     5445 | 2024-02-29 | Permitta Esports     | L   | 0.595      | -            | -                | -                | -         |    -6.08 | HENU, myltsi, podi, S1rva, teme    |
|            5 |     5527 | 2024-02-27 | ex-K10               | W   | 0.583      | 0.303        | 0.005 (0.001)    | 0.517 (0.091)    | -         |     9.18 | HENU, myltsi, podi, S1rva, teme    |
|            4 |     5664 | 2024-02-24 | HAVU Gaming          | W   | 0.565      | 0.143        | 0.004 (0.000)    | -                | 1 (0.565) |     7.28 | HENU, myltsi, podi, S1rva, teme    |
|            3 |     5728 | 2024-02-24 | ex-sYnck             | W   | 0.562      | 0.143        | 0.000 (0.000)    | 0.255 (0.020)    | 1 (0.562) |     7.21 | HENU, myltsi, podi, S1rva, teme    |
|            2 |     6643 | 2024-02-05 | ROYALS               | L   | 0.435      | -            | -                | -                | -         |   -11.54 | HENU, myltsi, podi, S1rva, teme    |
|            1 |     6902 | 2024-02-01 | Sashi Esport         | L   | 0.409      | -            | -                | -                | -         |    -2.88 | HENU, myltsi, podi, S1rva, teme    |

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
