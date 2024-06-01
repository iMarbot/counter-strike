### Roster Details<br />
Team Name: ex-CatEvil<br />
Roster: Antuanette, BabyRage, SJR, Slayerhz, zockie<br />
Region: [Americas]( ../standings_americas.md)<br />
<br />
Global Rank: [355](../standings_global.md)<br />
Regional Rank: [89]( ../standings_americas.md)<br />
Final Rank Value:  599.2<br />
<br />
Final Rank Value (599.2) = Starting Rank Value (605.0) + Head To Head Adjustments (-5.9)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.210[<sup>1</sup>](#table2)
- Bounty Collected: 0.188[<sup>2</sup>](#table1)
- Opponent Network: 0.005[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.101<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 605.0
- 400 + ( ( 0.101 - 0.000 ) / ( 0.786 - 0.000 ) ) * 1600 = 605.0


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent          | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                       |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           19 |     4684 | 2024-03-09 | Pryde             | L   | 0.660      | -            | -                | -                | -         |   -13.80 | Antuanette, BabyRage, SJR, Slayerhz, zockie  |
|           18 |     4926 | 2024-03-05 | Snakes Den Gaming | L   | 0.633      | -            | -                | -                | -         |    -9.88 | Antuanette, BabyRage, SJR, Slayerhz, zockie  |
|           17 |     5485 | 2024-02-24 | Party Astronauts  | L   | 0.566      | -            | -                | -                | -         |    -2.56 | Antuanette, BabyRage, SJR, Slayerhz, zockie  |
|           16 |     5583 | 2024-02-23 | Straight Gas      | W   | 0.560      | 0.143        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     3.92 | Antuanette, BabyRage, SJR, Slayerhz, zockie  |
|           15 |     5630 | 2024-02-22 | Team Liquid       | L   | 0.552      | -            | -                | -                | -         |    -0.05 | Antuanette, BabyRage, SJR, Slayerhz, zockie  |
|           14 |     5677 | 2024-02-21 | Mythic            | W   | 0.546      | 0.143        | 0.000 (0.000)    | 0.339 (0.026)    | 0 (0.000) |    12.23 | Antuanette, BabyRage, SJR, Slayerhz, zockie  |
|           13 |     6907 | 2024-01-27 | Carpe Diem        | L   | 0.379      | -            | -                | -                | -         |    -5.66 | Antuanette, BabyRage, SJR, Slayerhz, zockie  |
|           12 |     7005 | 2024-01-26 | Akimbo Esports    | W   | 0.373      | 0.143        | 0.008 (0.000)    | 0.155 (0.008)    | 0 (0.000) |     8.24 | Antuanette, BabyRage, SJR, Slayerhz, zockie  |
|           11 |     7010 | 2024-01-26 | MIGHT             | W   | 0.373      | 0.143        | 0.001 (0.000)    | 0.207 (0.011)    | 0 (0.000) |     7.24 | Antuanette, BabyRage, SJR, Slayerhz, zockie  |
|           10 |     7162 | 2024-01-23 | NRG               | L   | 0.353      | -            | -                | -                | -         |    -2.35 | Antuanette, BabyRage, SJR, Slayerhz, zockie  |
|            9 |     7698 | 2024-01-15 | Wildcard Gaming   | L   | 0.299      | -            | -                | -                | -         |    -1.60 | Antuanette, BabyRage, Knight, SJR, zockie    |
|            8 |     7969 | 2024-01-10 | FLUFFY AIMERS     | L   | 0.267      | -            | -                | -                | -         |    -4.11 | Antuanette, BabyRage, SJR, tor1towOw, zockie |
|            7 |     8442 | 2023-12-17 | Team Jaguar       | W   | 0.105      | 0.241        | 0.000 (0.000)    | 0.011 (0.000)    | 0 (0.000) |     1.65 | BRUNO, guepaRd, Knight, NotJuanjo, pacmanN   |
|            6 |     8857 | 2023-12-12 | Team Jaguar       | W   | 0.073      | 0.241        | 0.000 (0.000)    | 0.011 (0.000)    | 0 (0.000) |     1.15 | BRUNO, guepaRd, Knight, NotJuanjo, pacmanN   |
|            5 |     8899 | 2023-12-11 | Boogie Boyz       | W   | 0.066      | 0.241        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     0.50 | Ju4n, nex1, v1ko, vTR, WIDOW                 |
|            4 |     9193 | 2023-12-06 | regain            | L   | 0.033      | -            | -                | -                | -         |    -0.50 | Antuanette, BabyRage, SJR, tor1towOw, zockie |
|            3 |     9251 | 2023-12-05 | One More Esports  | L   | 0.027      | -            | -                | -                | -         |    -0.26 | Antuanette, BabyRage, SJR, tor1towOw, zockie |
|            2 |     9411 | 2023-12-02 | huge sweaty       | L   | 0.006      | -            | -                | -                | -         |    -0.14 | den1ed, Evan, Reaper, sava9e, twigs          |
|            1 |     9421 | 2023-12-02 | Nouns Esports     | W   | 0.006      | 0.294        | 0.002 (0.000)    | 0.014 (0.000)    | 0 (0.000) |     0.10 | Antuanette, BabyRage, SJR, tor1towOw, zockie |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($52.36)
- Divide that value by the 5th highest value among all rosters ($300,806.11)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
