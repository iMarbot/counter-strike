### Roster Details<br />
Team Name: Sashi Esport<br />
Roster: b0RUP, Fessor, n1Xen, niko, nut nut<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [370](../standings_global.md)<br />
Regional Rank: [221]( ../standings_europe.md)<br />
Final Rank Value:  595.8<br />
<br />
Final Rank Value (595.8) = Starting Rank Value (552.4) + Head To Head Adjustments (43.4)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.000[<sup>1</sup>](#table2)
- Bounty Collected: 0.261[<sup>2</sup>](#table1)
- Opponent Network: 0.039[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.075<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 552.4
- 400 + ( ( 0.075 - 0.000 ) / ( 0.787 - 0.000 ) ) * 1600 = 552.4


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
|           25 |     6240 | 2024-02-15 | Permitta Esports          | L   | 0.502      | -            | -                | -                | -         |    -1.83 | b0RUP, Fessor, n1Xen, niko, nut nut   |
|           24 |     6309 | 2024-02-14 | BIG Academy               | L   | 0.496      | -            | -                | -                | -         |    -4.48 | b0RUP, Fessor, n1Xen, niko, nut nut   |
|           23 |     6419 | 2024-02-11 | AURA                      | L   | 0.477      | -            | -                | -                | -         |    -7.19 | b0RUP, Fessor, n1Xen, niko, nut nut   |
|           22 |     6431 | 2024-02-11 | Kappa Borr                | W   | 0.477      | 0.143        | 0.000 (0.000)    | 0.127 (0.009)    | 0 (0.000) |     4.92 | b0RUP, Fessor, n1Xen, niko, nut nut   |
|           21 |     6436 | 2024-02-11 | Passion UA                | W   | 0.475      | 0.303        | 0.057 (0.008)    | 1.000 (0.144)    | 0 (0.000) |    13.34 | b0RUP, Fessor, n1Xen, niko, nut nut   |
|           20 |     6558 | 2024-02-07 | EXO Clan                  | W   | 0.449      | 0.303        | 0.013 (0.002)    | 0.579 (0.079)    | 0 (0.000) |    12.90 | b0RUP, Fessor, n1Xen, niko, nut nut   |
|           19 |     6703 | 2024-02-03 | showmakerz                | L   | 0.424      | -            | -                | -                | -         |    -6.78 | b0RUP, Fessor, n1Xen, niko, nut nut   |
|           18 |     6720 | 2024-02-03 | ex-Preasy Esport          | W   | 0.424      | 0.143        | 0.052 (0.003)    | 0.381 (0.023)    | 0 (0.000) |    11.66 | b0RUP, Fessor, n1Xen, niko, nut nut   |
|           17 |     6737 | 2024-02-03 | Kappa Bar                 | W   | 0.424      | 0.143        | 0.000 (0.000)    | 0.110 (0.007)    | 0 (0.000) |     5.87 | b0RUP, Fessor, n1Xen, niko, nut nut   |
|           16 |     6799 | 2024-02-02 | ex-Preasy Esport          | L   | 0.417      | -            | -                | -                | -         |    -1.56 | b0RUP, Fessor, n1Xen, niko, nut nut   |
|           15 |     6811 | 2024-02-02 | Lilmix                    | W   | 0.417      | 0.143        | 0.006 (0.000)    | 0.593 (0.035)    | 0 (0.000) |    11.02 | b0RUP, Fessor, n1Xen, niko, nut nut   |
|           14 |     7034 | 2024-01-29 | 1win                      | L   | 0.392      | -            | -                | -                | -         |    -1.08 | b0RUP, Fessor, n1Xen, niko, nut nut   |
|           13 |     7081 | 2024-01-28 | Into The Breach           | L   | 0.384      | -            | -                | -                | -         |    -3.19 | b0RUP, Fessor, n1Xen, niko, nut nut   |
|           12 |     7088 | 2024-01-28 | Preasy Esport             | W   | 0.383      | 0.143        | 0.008 (0.000)    | 0.705 (0.039)    | 0 (0.000) |    10.33 | b0RUP, Fessor, n1Xen, niko, nut nut   |
|           11 |     7806 | 2024-01-17 | Endpoint                  | L   | 0.311      | -            | -                | -                | -         |    -0.99 | b0RUP, Fessor, n1Xen, niko, nut nut   |
|           10 |     8385 | 2024-01-09 | ex-K10                    | L   | 0.257      | -            | -                | -                | -         |    -1.15 | b0RUP, Fessor, n1Xen, niko, nut nut   |
|            9 |     8640 | 2023-12-20 | Natus Vincere Junior      | L   | 0.123      | -            | -                | -                | -         |    -0.80 | Fessor, n1Xen, nut nut, PR1mE, Speedy |
|            8 |     8643 | 2023-12-20 | ex-Turów Zgorzelec Esport | W   | 0.122      | 0.333        | 0.006 (0.000)    | 0.491 (0.020)    | 0 (0.000) |     3.08 | Fessor, n1Xen, nut nut, PR1mE, Speedy |
|            7 |     8674 | 2023-12-18 | showmakerz                | L   | 0.109      | -            | -                | -                | -         |    -1.76 | Fessor, n1Xen, nut nut, PR1mE, Speedy |
|            6 |     8677 | 2023-12-18 | ARCRED                    | L   | 0.109      | -            | -                | -                | -         |    -0.76 | Fessor, n1Xen, nut nut, PR1mE, Speedy |
|            5 |     8771 | 2023-12-17 | ex-Anonymo Esports        | L   | 0.102      | -            | -                | -                | -         |    -0.99 | Fessor, n1Xen, nut nut, PR1mE, Speedy |
|            4 |     8847 | 2023-12-16 | The Witchers              | L   | 0.098      | -            | -                | -                | -         |    -0.92 | Fessor, n1Xen, nut nut, PR1mE, Speedy |
|            3 |     9023 | 2023-12-15 | Nexus Gaming              | W   | 0.088      | 0.333        | 0.003 (0.000)    | 0.857 (0.025)    | 0 (0.000) |     2.45 | Fessor, n1Xen, nut nut, PR1mE, Speedy |
|            2 |     9235 | 2023-12-10 | GamerLegion Academy       | W   | 0.057      | 0.333        | 0.018 (0.000)    | 0.691 (0.013)    | 0 (0.000) |     1.49 | Fessor, n1Xen, nut nut, PR1mE, Speedy |
|            1 |     9511 | 2023-12-06 | Natus Vincere Junior      | L   | 0.030      | -            | -                | -                | -         |    -0.19 | Fessor, n1Xen, nut nut, PR1mE, Speedy |

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
