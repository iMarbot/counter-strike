### Roster Details<br />
Team Name: Team Pigeons<br />
Roster: ANa, Kat, tory, twenty3, zAAz<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [86](../standings_global.md)<br />
Regional Rank: [60]( ../standings_europe.md)<br />
Final Rank Value:  895.2<br />
<br />
Final Rank Value (895.2) = Starting Rank Value (778.3) + Head To Head Adjustments (116.8)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.383[<sup>1</sup>](#table2)
- Bounty Collected: 0.272[<sup>2</sup>](#table1)
- Opponent Network: 0.067[<sup>2</sup>](#table1)
- LAN Wins: 0.022[<sup>2</sup>](#table1)

The average of these factors is 0.186<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 778.3
- 400 + ( ( 0.186 - 0.000 ) / ( 0.786 - 0.000 ) ) * 1600 = 778.3


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent           | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                   |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           32 |      763 | 2024-05-19 | NAVI Javelins      | L   | 1.000      | -            | -                | -                | -         |   -17.50 | ANa, Kat, tory, twenty3, zAAz            |
|           31 |      801 | 2024-05-19 | NIP Impact         | W   | 1.000      | 0.281        | 0.007 (0.002)    | 0.303 (0.085)    | 0 (0.000) |     8.79 | ANa, Kat, tory, twenty3, zAAz            |
|           30 |      867 | 2024-05-18 | Crescent           | W   | 1.000      | 0.281        | 0.007 (0.002)    | 0.228 (0.064)    | 0 (0.000) |     6.97 | ANa, Kat, tory, twenty3, zAAz            |
|           29 |      914 | 2024-05-18 | Insilio Female     | W   | 1.000      | -            | -                | -                | 0 (0.000) |     1.83 | ANa, Kat, tory, twenty3, zAAz            |
|           28 |     1769 | 2024-05-05 | Crescent           | W   | 1.000      | 0.250        | 0.007 (0.002)    | 0.228 (0.057)    | 0 (0.000) |     6.94 | ANa, Kat, tory, twenty3, zAAz            |
|           27 |     1815 | 2024-05-04 | Nemesis            | W   | 1.000      | -            | -                | -                | 0 (0.000) |     3.23 | ANa, Kat, tory, twenty3, zAAz            |
|           26 |     1821 | 2024-05-04 | YUME               | W   | 1.000      | -            | -                | -                | 0 (0.000) |     1.96 | ANa, Kat, tory, twenty3, zAAz            |
|           25 |     2183 | 2024-04-27 | NIP Impact         | W   | 0.983      | -            | -                | -                | -         |     9.13 | ANa, Kat, tory, twenty3, zAAz            |
|           24 |     2187 | 2024-04-27 | Team Spirit Female | W   | 0.983      | -            | -                | -                | -         |     7.12 | ANa, Kat, tory, twenty3, zAAz            |
|           23 |     2194 | 2024-04-27 | VIOLET             | W   | 0.982      | -            | -                | -                | -         |     3.77 | ANa, Kat, tory, twenty3, zAAz            |
|           22 |     2693 | 2024-04-19 | ex-Guild Esports   | W   | 0.930      | 0.331        | 0.005 (0.002)    | -                | -         |     9.34 | ANa, Kat, tory, twenty3, zAAz            |
|           21 |     2904 | 2024-04-16 | NAVI Javelins      | L   | 0.910      | -            | -                | -                | -         |   -16.28 | ANa, Kat, tory, twenty3, zAAz            |
|           20 |     2977 | 2024-04-14 | NIP Impact         | W   | 0.897      | 0.303        | 0.007 (0.002)    | 0.303 (0.082)    | -         |     9.03 | ANa, Kat, tory, twenty3, zAAz            |
|           19 |     3042 | 2024-04-13 | NAVI Javelins      | W   | 0.889      | 0.303        | 0.024 (0.007)    | 0.265 (0.071)    | -         |    11.70 | ANa, Kat, tory, twenty3, zAAz            |
|           18 |     3109 | 2024-04-11 | Astralis Women     | W   | 0.877      | -            | -                | -                | -         |     5.50 | ANa, Kat, tory, twenty3, zAAz            |
|           17 |     3177 | 2024-04-10 | Astralis Women     | W   | 0.870      | -            | -                | -                | -         |     5.74 | ANa, Kat, tory, twenty3, zAAz            |
|           16 |     3297 | 2024-04-08 | Crescent           | W   | 0.856      | 0.303        | 0.007 (0.002)    | 0.228 (0.059)    | -         |     8.47 | ANa, Kat, tory, twenty3, zAAz            |
|           15 |     3340 | 2024-04-07 | NIP Impact         | W   | 0.850      | 0.262        | 0.007 (0.001)    | 0.303 (0.067)    | -         |     9.57 | ANa, Kat, tory, twenty3, zAAz            |
|           14 |     3351 | 2024-04-07 | BIG EQUIPA         | W   | 0.849      | 0.262        | -                | 0.267 (0.059)    | -         |    10.80 | ANa, Kat, tory, twenty3, zAAz            |
|           13 |     3404 | 2024-04-06 | ENCE Athena        | W   | 0.842      | -            | -                | -                | -         |     8.73 | ANa, Kat, tory, twenty3, zAAz            |
|           12 |     3412 | 2024-04-06 | woof woof          | W   | 0.841      | -            | -                | -                | -         |     5.05 | ANa, Kat, tory, twenty3, zAAz            |
|           11 |     3789 | 2024-03-27 | ENCE Athena        | W   | 0.778      | 0.331        | 0.004 (0.001)    | -                | -         |     8.78 | ANa, Kat, tory, twenty3, zAAz            |
|           10 |     4420 | 2024-03-14 | BIG EQUIPA         | W   | 0.691      | 0.331        | -                | 0.267 (0.061)    | -         |     9.52 | ANa, Kat, tory, twenty3, zAAz            |
|            9 |     4802 | 2024-03-07 | NIP Impact         | W   | 0.644      | 0.331        | 0.007 (0.001)    | 0.303 (0.065)    | -         |     7.39 | ANa, Kat, tory, twenty3, zAAz            |
|            8 |     5423 | 2024-02-26 | 500                | L   | 0.576      | -            | -                | -                | -         |    -8.37 | ANa, Kat, tory, twenty3, zAAz            |
|            7 |     6536 | 2024-02-03 | UNiTY esports      | L   | 0.424      | -            | -                | -                | -         |    -4.46 | Levi, luko, M1key, NIO, Pechyn           |
|            6 |     6547 | 2024-02-03 | M1X                | W   | 0.423      | -            | -                | -                | -         |     2.31 | ammar, kujtaa, Lewis, rosoneriii, tripey |
|            5 |     8967 | 2023-12-10 | NAVI Javelins      | W   | 0.057      | -            | -                | -                | 1 (0.057) |     0.90 | ANa, Kat, tory, twenty3, vilga           |
|            4 |     8992 | 2023-12-10 | NOFEAR5            | W   | 0.055      | -            | -                | -                | 1 (0.055) |     0.57 | Elizabeth, f6tal, Ksu, t4tty, victoria   |
|            3 |     9028 | 2023-12-09 | HSG                | W   | 0.050      | -            | -                | -                | 1 (0.050) |     0.48 | Argent, GFi, Hazel, olga, XiaoWu         |
|            2 |     9107 | 2023-12-08 | Fluxo Demons       | L   | 0.044      | -            | -                | -                | -         |    -0.52 | goddess, julih, nani, poppins, yungher   |
|            1 |     9126 | 2023-12-08 | HSG                | W   | 0.042      | -            | -                | -                | 1 (0.042) |     0.40 | Argent, GFi, Hazel, olga, XiaoWu         |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($7,347.18)
- Divide that value by the 5th highest value among all rosters ($300,806.11)
- The final value (0.02) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-05-19 |      1.000 | $800.00        | $800.00         |
| 2024-05-05 |      1.000 | $750.00        | $750.00         |
| 2024-04-27 |      0.983 | $535.13        | $526.04         |
| 2024-04-16 |      0.910 | $1,500.00      | $1,365.42       |
| 2024-04-07 |      0.850 | $1,250.00      | $1,061.98       |
| 2023-12-10 |      0.057 | $50,000.00     | $2,843.75       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
