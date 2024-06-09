### Roster Details<br />
Team Name: Team Pigeons<br />
Roster: ANa, Kat, tory, twenty3, zAAz<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [93](../standings_global.md)<br />
Regional Rank: [66]( ../standings_europe.md)<br />
Final Rank Value:  884.0<br />
<br />
Final Rank Value (884.0) = Starting Rank Value (777.7) + Head To Head Adjustments (106.3)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.383[<sup>1</sup>](#table2)
- Bounty Collected: 0.272[<sup>2</sup>](#table1)
- Opponent Network: 0.067[<sup>2</sup>](#table1)
- LAN Wins: 0.022[<sup>2</sup>](#table1)

The average of these factors is 0.186<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 777.7
- 400 + ( ( 0.186 - 0.000 ) / ( 0.787 - 0.000 ) ) * 1600 = 777.7


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
|           35 |      775 | 2024-05-19 | NAVI Javelins      | L   | 1.000      | -            | -                | -                | -         |   -17.09 | ANa, Kat, tory, twenty3, zAAz            |
|           34 |      813 | 2024-05-19 | NIP Impact         | W   | 1.000      | 0.281        | 0.007 (0.002)    | 0.303 (0.085)    | 0 (0.000) |     9.17 | ANa, Kat, tory, twenty3, zAAz            |
|           33 |      879 | 2024-05-18 | Crescent           | W   | 1.000      | 0.281        | 0.007 (0.002)    | 0.228 (0.064)    | 0 (0.000) |     7.01 | ANa, Kat, tory, twenty3, zAAz            |
|           32 |      926 | 2024-05-18 | Insilio Female     | W   | 1.000      | -            | -                | -                | 0 (0.000) |     1.96 | ANa, Kat, tory, twenty3, zAAz            |
|           31 |     1792 | 2024-05-05 | Crescent           | W   | 1.000      | 0.250        | 0.007 (0.002)    | 0.228 (0.057)    | 0 (0.000) |     6.98 | ANa, Kat, tory, twenty3, zAAz            |
|           30 |     1838 | 2024-05-04 | Nemesis            | W   | 1.000      | -            | -                | -                | 0 (0.000) |     3.43 | ANa, Kat, tory, twenty3, zAAz            |
|           29 |     1844 | 2024-05-04 | YUME               | W   | 1.000      | -            | -                | -                | 0 (0.000) |     2.09 | ANa, Kat, tory, twenty3, zAAz            |
|           28 |     2218 | 2024-04-27 | NIP Impact         | W   | 0.983      | -            | -                | -                | -         |     9.55 | ANa, Kat, tory, twenty3, zAAz            |
|           27 |     2222 | 2024-04-27 | Team Spirit Female | W   | 0.983      | -            | -                | -                | -         |     7.51 | ANa, Kat, tory, twenty3, zAAz            |
|           26 |     2229 | 2024-04-27 | VIOLET             | W   | 0.982      | -            | -                | -                | -         |     4.02 | ANa, Kat, tory, twenty3, zAAz            |
|           25 |     2749 | 2024-04-19 | ex-Guild Esports   | W   | 0.930      | 0.331        | 0.005 (0.002)    | -                | -         |     9.82 | ANa, Kat, tory, twenty3, zAAz            |
|           24 |     2964 | 2024-04-16 | NAVI Javelins      | L   | 0.910      | -            | -                | -                | -         |   -15.75 | ANa, Kat, tory, twenty3, zAAz            |
|           23 |     3042 | 2024-04-14 | NIP Impact         | W   | 0.897      | 0.303        | 0.007 (0.002)    | 0.303 (0.082)    | -         |     9.52 | ANa, Kat, tory, twenty3, zAAz            |
|           22 |     3108 | 2024-04-13 | NAVI Javelins      | W   | 0.889      | 0.303        | 0.024 (0.007)    | 0.265 (0.071)    | -         |    12.27 | ANa, Kat, tory, twenty3, zAAz            |
|           21 |     3176 | 2024-04-11 | Astralis Women     | W   | 0.877      | -            | -                | -                | -         |     5.88 | ANa, Kat, tory, twenty3, zAAz            |
|           20 |     3250 | 2024-04-10 | Astralis Women     | W   | 0.870      | -            | -                | -                | -         |     6.15 | ANa, Kat, tory, twenty3, zAAz            |
|           19 |     3378 | 2024-04-08 | Crescent           | W   | 0.856      | 0.303        | 0.007 (0.002)    | 0.228 (0.059)    | -         |     8.54 | ANa, Kat, tory, twenty3, zAAz            |
|           18 |     3421 | 2024-04-07 | NIP Impact         | W   | 0.850      | 0.262        | 0.007 (0.001)    | 0.303 (0.067)    | -         |    10.14 | ANa, Kat, tory, twenty3, zAAz            |
|           17 |     3434 | 2024-04-07 | BIG EQUIPA         | W   | 0.849      | 0.262        | -                | 0.267 (0.059)    | -         |    11.39 | ANa, Kat, tory, twenty3, zAAz            |
|           16 |     3487 | 2024-04-06 | ENCE Athena        | W   | 0.842      | -            | -                | -                | -         |     9.29 | ANa, Kat, tory, twenty3, zAAz            |
|           15 |     3495 | 2024-04-06 | woof woof          | W   | 0.841      | -            | -                | -                | -         |     5.48 | ANa, Kat, tory, twenty3, zAAz            |
|           14 |     3882 | 2024-03-27 | ENCE Athena        | W   | 0.778      | 0.331        | 0.004 (0.001)    | -                | -         |     9.36 | ANa, Kat, tory, twenty3, zAAz            |
|           13 |     4534 | 2024-03-14 | BIG EQUIPA         | W   | 0.691      | 0.331        | -                | 0.267 (0.061)    | -         |    10.09 | ANa, Kat, tory, twenty3, zAAz            |
|           12 |     4931 | 2024-03-07 | NIP Impact         | W   | 0.644      | 0.331        | 0.007 (0.001)    | 0.303 (0.065)    | -         |     7.92 | ANa, Kat, tory, twenty3, zAAz            |
|           11 |     5581 | 2024-02-26 | 500                | L   | 0.576      | -            | -                | -                | -         |    -7.71 | ANa, Kat, tory, twenty3, zAAz            |
|           10 |     6634 | 2024-02-05 | Team Sampi         | L   | 0.436      | -            | -                | -                | -         |    -3.57 | ANa, hyskeee, Kat, tory, twenty3         |
|            9 |     6739 | 2024-02-03 | UNiTY esports      | L   | 0.424      | -            | -                | -                | -         |    -4.17 | Levi, luko, M1key, NIO, Pechyn           |
|            8 |     6750 | 2024-02-03 | M1X                | W   | 0.423      | -            | -                | -                | -         |     2.51 | ammar, kujtaa, Lewis, rosoneriii, tripey |
|            7 |     6825 | 2024-02-02 | GYROCOPTER_UA      | L   | 0.417      | -            | -                | -                | -         |    -8.80 | ANa, hyskeee, Kat, twenty3, zAAz         |
|            6 |     7058 | 2024-01-29 | Sprout             | L   | 0.389      | -            | -                | -                | -         |    -8.52 | ANa, hyskeee, Kat, tory, twenty3         |
|            5 |     9233 | 2023-12-10 | NAVI Javelins      | W   | 0.057      | -            | -                | -                | 1 (0.057) |     0.90 | ANa, Kat, tory, twenty3, vilga           |
|            4 |     9258 | 2023-12-10 | NOFEAR5            | W   | 0.055      | -            | -                | -                | 1 (0.055) |     0.57 | Elizabeth, f6tal, Ksu, t4tty, victoria   |
|            3 |     9294 | 2023-12-09 | HSG                | W   | 0.050      | -            | -                | -                | 1 (0.050) |     0.48 | Argent, GFi, Hazel, olga, XiaoWu         |
|            2 |     9375 | 2023-12-08 | Fluxo Demons       | L   | 0.044      | -            | -                | -                | -         |    -0.52 | goddess, julih, nani, poppins, yungher   |
|            1 |     9396 | 2023-12-08 | HSG                | W   | 0.042      | -            | -                | -                | 1 (0.042) |     0.40 | Argent, GFi, Hazel, olga, XiaoWu         |

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
