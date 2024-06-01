### Roster Details<br />
Team Name: Sashi Esport<br />
Roster: b0RUP, Fessor, n1Xen, niko, nut nut<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [363](../standings_global.md)<br />
Regional Rank: [215]( ../standings_europe.md)<br />
Final Rank Value:  594.5<br />
<br />
Final Rank Value (594.5) = Starting Rank Value (552.0) + Head To Head Adjustments (42.5)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.000[<sup>1</sup>](#table2)
- Bounty Collected: 0.261[<sup>2</sup>](#table1)
- Opponent Network: 0.037[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.075<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 552.0
- 400 + ( ( 0.075 - 0.000 ) / ( 0.786 - 0.000 ) ) * 1600 = 552.0


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent                  | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           25 |     6059 | 2024-02-15 | Permitta Esports          | L   | 0.502      | -            | -                | -                | -         |    -1.91 | b0RUP, Fessor, n1Xen, niko, nut nut   |
|           24 |     6128 | 2024-02-14 | BIG Academy               | L   | 0.496      | -            | -                | -                | -         |    -4.79 | b0RUP, Fessor, n1Xen, niko, nut nut   |
|           23 |     6231 | 2024-02-11 | AURA                      | L   | 0.477      | -            | -                | -                | -         |    -7.31 | b0RUP, Fessor, n1Xen, niko, nut nut   |
|           22 |     6243 | 2024-02-11 | Kappa Borr                | W   | 0.477      | 0.143        | 0.000 (0.000)    | 0.127 (0.009)    | 0 (0.000) |     4.93 | b0RUP, Fessor, n1Xen, niko, nut nut   |
|           21 |     6248 | 2024-02-11 | Passion UA                | W   | 0.475      | 0.303        | 0.057 (0.008)    | 1.000 (0.144)    | 0 (0.000) |    13.27 | b0RUP, Fessor, n1Xen, niko, nut nut   |
|           20 |     6364 | 2024-02-07 | EXO Clan                  | W   | 0.449      | 0.303        | 0.013 (0.002)    | 0.510 (0.069)    | 0 (0.000) |    12.83 | b0RUP, Fessor, n1Xen, niko, nut nut   |
|           19 |     6500 | 2024-02-03 | showmakerz                | L   | 0.424      | -            | -                | -                | -         |    -6.87 | b0RUP, Fessor, n1Xen, niko, nut nut   |
|           18 |     6517 | 2024-02-03 | ex-Preasy Esport          | W   | 0.424      | 0.143        | 0.052 (0.003)    | 0.381 (0.023)    | 0 (0.000) |    11.64 | b0RUP, Fessor, n1Xen, niko, nut nut   |
|           17 |     6534 | 2024-02-03 | Kappa Bar                 | W   | 0.424      | 0.143        | 0.000 (0.000)    | 0.110 (0.007)    | 0 (0.000) |     5.86 | b0RUP, Fessor, n1Xen, niko, nut nut   |
|           16 |     6596 | 2024-02-02 | ex-Preasy Esport          | L   | 0.417      | -            | -                | -                | -         |    -1.58 | b0RUP, Fessor, n1Xen, niko, nut nut   |
|           15 |     6608 | 2024-02-02 | Lilmix                    | W   | 0.417      | 0.143        | 0.006 (0.000)    | 0.581 (0.035)    | 0 (0.000) |    11.18 | b0RUP, Fessor, n1Xen, niko, nut nut   |
|           14 |     6818 | 2024-01-29 | 1win                      | L   | 0.392      | -            | -                | -                | -         |    -1.07 | b0RUP, Fessor, n1Xen, niko, nut nut   |
|           13 |     6863 | 2024-01-28 | Into The Breach           | L   | 0.384      | -            | -                | -                | -         |    -3.19 | b0RUP, Fessor, n1Xen, niko, nut nut   |
|           12 |     6870 | 2024-01-28 | Preasy Esport             | W   | 0.383      | 0.143        | 0.008 (0.000)    | 0.642 (0.035)    | 0 (0.000) |    10.27 | b0RUP, Fessor, n1Xen, niko, nut nut   |
|           11 |     7557 | 2024-01-17 | Endpoint                  | L   | 0.311      | -            | -                | -                | -         |    -1.01 | b0RUP, Fessor, n1Xen, niko, nut nut   |
|           10 |     8131 | 2024-01-09 | ex-K10                    | L   | 0.257      | -            | -                | -                | -         |    -1.26 | b0RUP, Fessor, n1Xen, niko, nut nut   |
|            9 |     8383 | 2023-12-20 | Natus Vincere Junior      | L   | 0.123      | -            | -                | -                | -         |    -0.80 | Fessor, n1Xen, nut nut, PR1mE, Speedy |
|            8 |     8386 | 2023-12-20 | ex-Turów Zgorzelec Esport | W   | 0.122      | 0.333        | 0.006 (0.000)    | 0.375 (0.015)    | 0 (0.000) |     3.01 | Fessor, n1Xen, nut nut, PR1mE, Speedy |
|            7 |     8417 | 2023-12-18 | showmakerz                | L   | 0.109      | -            | -                | -                | -         |    -1.78 | Fessor, n1Xen, nut nut, PR1mE, Speedy |
|            6 |     8420 | 2023-12-18 | ARCRED                    | L   | 0.109      | -            | -                | -                | -         |    -0.76 | Fessor, n1Xen, nut nut, PR1mE, Speedy |
|            5 |     8511 | 2023-12-17 | ex-Anonymo Esports        | L   | 0.102      | -            | -                | -                | -         |    -0.99 | Fessor, n1Xen, nut nut, PR1mE, Speedy |
|            4 |     8587 | 2023-12-16 | The Witchers              | L   | 0.098      | -            | -                | -                | -         |    -0.92 | Fessor, n1Xen, nut nut, PR1mE, Speedy |
|            3 |     8761 | 2023-12-15 | Nexus Gaming              | W   | 0.088      | 0.333        | 0.014 (0.000)    | 0.825 (0.024)    | 0 (0.000) |     2.48 | Fessor, n1Xen, nut nut, PR1mE, Speedy |
|            2 |     8969 | 2023-12-10 | GamerLegion Academy       | W   | 0.057      | 0.333        | 0.018 (0.000)    | 0.691 (0.013)    | 0 (0.000) |     1.49 | Fessor, n1Xen, nut nut, PR1mE, Speedy |
|            1 |     9230 | 2023-12-06 | Natus Vincere Junior      | L   | 0.030      | -            | -                | -                | -         |    -0.19 | Fessor, n1Xen, nut nut, PR1mE, Speedy |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($0.00)
- Divide that value by the 5th highest value among all rosters ($300,806.11)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
