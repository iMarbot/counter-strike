### Roster Details<br />
Team Name: Sashi Esport<br />
Roster: aizy, n1Xen, nut nut, PR1mE, Speedy<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [195](../standings_global.md)<br />
Regional Rank: [129]( ../standings_europe.md)<br />
Final Rank Value:  731.9<br />
<br />
Final Rank Value (731.9) = Starting Rank Value (720.9) + Head To Head Adjustments (11.0)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.347[<sup>1</sup>](#table2)
- Bounty Collected: 0.246[<sup>2</sup>](#table1)
- Opponent Network: 0.018[<sup>2</sup>](#table1)
- LAN Wins: 0.037[<sup>2</sup>](#table1)

The average of these factors is 0.162<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 720.9
- 400 + ( ( 0.162 - 0.000 ) / ( 0.806 - 0.000 ) ) * 1600 = 720.9


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent                    | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins      | H2H Adj. | Roster                              |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           25 |     5597 | 2023-12-15 | Nexus Gaming                | W   | 0.249      | 0.333        | 0.031 (0.003)    | 0.772 (0.064)    | false (0.000) |     6.04 | aizy, n1Xen, nut nut, PR1mE, Speedy |
|           24 |     5702 | 2023-12-11 | Kappa Bar                   | L   | 0.224      | -            | -                | -                | -             |    -4.05 | aizy, n1Xen, NutNut, PR1mE, Speedy  |
|           23 |     5725 | 2023-12-10 | GamerLegion Academy         | W   | 0.218      | 0.333        | 0.043 (0.003)    | 0.567 (0.041)    | false (0.000) |     4.77 | aizy, n1Xen, nut nut, PR1mE, Speedy |
|           22 |     5789 | 2023-12-09 | NOM Esports                 | L   | 0.209      | -            | -                | -                | -             |    -3.66 | aizy, n1Xen, NutNut, PR1mE, Speedy  |
|           21 |     5938 | 2023-12-06 | Natus Vincere Junior        | L   | 0.191      | -            | -                | -                | -             |    -2.05 | aizy, n1Xen, nut nut, PR1mE, Speedy |
|           20 |     5999 | 2023-12-05 | Kappa Bar                   | W   | 0.184      | 0.303        | 0.002 (0.000)    | 0.149 (0.008)    | false (0.000) |     2.47 | aizy, n1Xen, NutNut, PR1mE, Speedy  |
|           19 |     6093 | 2023-12-02 | WOPA Esport                 | W   | 0.165      | 0.143        | 0.009 (0.000)    | 0.485 (0.011)    | true (0.165)  |     2.98 | aizy, n1Xen, NutNut, PR1mE, Speedy  |
|           18 |     6123 | 2023-12-02 | Astralis Talent             | W   | 0.164      | 0.143        | 0.030 (0.001)    | 0.613 (0.014)    | true (0.164)  |     4.13 | aizy, n1Xen, NutNut, PR1mE, Speedy  |
|           17 |     6239 | 2023-11-29 | Inferus eSports             | L   | 0.146      | -            | -                | -                | -             |    -3.53 | aizy, n1Xen, NutNut, PR1mE, Speedy  |
|           16 |     6281 | 2023-11-29 | NOM Esports                 | W   | 0.143      | 0.303        | 0.003 (0.000)    | 0.068 (0.003)    | false (0.000) |     2.07 | aizy, n1Xen, NutNut, PR1mE, Speedy  |
|           15 |     6337 | 2023-11-28 | Illuminar Gaming            | W   | 0.136      | 0.303        | 0.010 (0.000)    | 0.243 (0.010)    | false (0.000) |     2.38 | aizy, n1Xen, NutNut, PR1mE, Speedy  |
|           14 |     6383 | 2023-11-27 | NOM Esports                 | L   | 0.129      | -            | -                | -                | -             |    -2.21 | aizy, n1Xen, NutNut, PR1mE, Speedy  |
|           13 |     6408 | 2023-11-26 | Illuminar Gaming            | W   | 0.123      | 0.303        | 0.010 (0.000)    | 0.243 (0.009)    | false (0.000) |     2.14 | aizy, n1Xen, NutNut, PR1mE, Speedy  |
|           12 |     6490 | 2023-11-24 | ILIN                        | L   | 0.111      | -            | -                | -                | -             |    -2.53 | aizy, n1Xen, NutNut, PR1mE, Speedy  |
|           11 |     6564 | 2023-11-22 | SHIPACHI                    | W   | 0.098      | -            | -                | -                | false (0.000) |     0.60 | aizy, n1Xen, NutNut, PR1mE, Speedy  |
|           10 |     6572 | 2023-11-22 | Natus Vincere Junior        | W   | 0.097      | 0.303        | 0.025 (0.001)    | 0.492 (0.014)    | false (0.000) |     2.07 | aizy, n1Xen, NutNut, PR1mE, Speedy  |
|            9 |     6666 | 2023-11-19 | Lazer Cats                  | W   | 0.078      | -            | -                | -                | -             |     0.92 | aizy, n1Xen, NutNut, PR1mE, Speedy  |
|            8 |     6820 | 2023-11-16 | POLET                       | L   | 0.058      | -            | -                | -                | -             |    -1.44 | aizy, n1Xen, NutNut, PR1mE, Speedy  |
|            7 |     6823 | 2023-11-16 | Team 7AM                    | L   | 0.058      | -            | -                | -                | -             |    -1.44 | aizy, n1Xen, NutNut, PR1mE, Speedy  |
|            6 |     6871 | 2023-11-15 | M1X                         | W   | 0.052      | -            | -                | -                | -             |     0.64 | aizy, n1Xen, NutNut, PR1mE, Speedy  |
|            5 |     6952 | 2023-11-13 | Team Atlantic               | W   | 0.039      | -            | -                | -                | -             |     0.17 | aizy, n1Xen, NutNut, PR1mE, Speedy  |
|            4 |     6966 | 2023-11-13 | Astralis Talent             | W   | 0.039      | 0.143        | 0.030 (0.000)    | 0.613 (0.003)    | -             |     0.98 | aizy, n1Xen, NutNut, PR1mE, Speedy  |
|            3 |     6991 | 2023-11-13 | ENCE Academy                | L   | 0.036      | -            | -                | -                | -             |    -0.37 | aizy, n1Xen, NutNut, PR1mE, Speedy  |
|            2 |     7148 | 2023-11-09 | UNiTY esports (Slovak team) | L   | 0.010      | -            | -                | -                | -             |    -0.06 | aizy, n1Xen, NutNut, PR1mE, Speedy  |
|            1 |     7187 | 2023-11-08 | TSM                         | L   | 0.005      | -            | -                | -                | -             |    -0.08 | aizy, n1Xen, NutNut, PR1mE, Speedy  |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($2,069.49)
- Divide that value by the 5th highest value among all rosters ($158,437.64)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2023-12-02 |      0.165 | $9,489.46      | $1,569.93       |
| 2023-11-29 |      0.143 | $3,500.00      | $499.56         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
