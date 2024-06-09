### Roster Details<br />
Team Name: Sprout<br />
Roster: Anlelele, Buzz, cej0t, raalz, sL1m3<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [259](../standings_global.md)<br />
Regional Rank: [168]( ../standings_europe.md)<br />
Final Rank Value:  677.2<br />
<br />
Final Rank Value (677.2) = Starting Rank Value (572.1) + Head To Head Adjustments (105.1)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.000[<sup>1</sup>](#table2)
- Bounty Collected: 0.301[<sup>2</sup>](#table1)
- Opponent Network: 0.038[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.085<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 572.1
- 400 + ( ( 0.085 - 0.000 ) / ( 0.787 - 0.000 ) ) * 1600 = 572.1


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent            | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           31 |     4956 | 2024-03-07 | Alliance            | L   | 0.642      | -            | -                | -                | -         |    -5.92 | Anlelele, Buzz, cej0t, raalz, sL1m3   |
|           30 |     5538 | 2024-02-27 | Permitta Esports    | L   | 0.582      | -            | -                | -                | -         |    -2.80 | Anlelele, Buzz, cej0t, raalz, sL1m3   |
|           29 |     5562 | 2024-02-26 | B8                  | L   | 0.578      | -            | -                | -                | -         |    -1.43 | Anlelele, Buzz, cej0t, raalz, sL1m3   |
|           28 |     6490 | 2024-02-09 | Fnatic              | W   | 0.463      | 0.143        | 0.147 (0.010)    | 0.480 (0.032)    | 0 (0.000) |    13.55 | Anlelele, cej0t, raalz, Sdaim, sL1m3  |
|           27 |     6495 | 2024-02-09 | 3DMAX               | W   | 0.463      | 0.143        | 0.106 (0.007)    | 0.325 (0.021)    | 0 (0.000) |    12.13 | Anlelele, cej0t, raalz, Sdaim, sL1m3  |
|           26 |     6555 | 2024-02-07 | Metizport           | L   | 0.450      | -            | -                | -                | -         |    -2.16 | Anlelele, Buzz, cej0t, raalz, sL1m3   |
|           25 |     6966 | 2024-01-30 | Nemiga Gaming       | L   | 0.398      | -            | -                | -                | -         |    -0.47 | Anlelele, cej0t, raalz, Sdaim, sL1m3  |
|           24 |     6973 | 2024-01-30 | Dynamo Eclot        | W   | 0.397      | 0.143        | 0.097 (0.005)    | 0.940 (0.053)    | 0 (0.000) |    11.50 | Anlelele, cej0t, raalz, Sdaim, sL1m3  |
|           23 |     6988 | 2024-01-30 | ALTERNATE aTTaX     | L   | 0.396      | -            | -                | -                | -         |    -1.61 | Anlelele, cej0t, raalz, Sdaim, sL1m3  |
|           22 |     6995 | 2024-01-29 | Team Spirit Academy | W   | 0.392      | 0.143        | 0.004 (0.000)    | -                | 0 (0.000) |     7.88 | Anlelele, cej0t, raalz, Sdaim, sL1m3  |
|           21 |     7011 | 2024-01-29 | ex-K10              | W   | 0.392      | 0.143        | 0.005 (0.000)    | 0.517 (0.029)    | 0 (0.000) |     9.48 | Anlelele, cej0t, raalz, Sdaim, sL1m3  |
|           20 |     7058 | 2024-01-29 | Team Pigeons        | W   | 0.389      | 0.384        | 0.024 (0.004)    | 0.350 (0.052)    | 0 (0.000) |     8.52 | Anlelele, Buzz, cej0t, raalz, sL1m3   |
|           19 |     7173 | 2024-01-27 | 9INE                | W   | 0.377      | -            | -                | -                | 0 (0.000) |     5.27 | Anlelele, cej0t, raalz, Sdaim, sL1m3  |
|           18 |     7183 | 2024-01-27 | Verdant             | W   | 0.377      | 0.143        | 0.014 (0.001)    | 1.000 (0.054)    | 0 (0.000) |    10.79 | Anlelele, cej0t, raalz, Sdaim, sL1m3  |
|           17 |     7189 | 2024-01-27 | BLEED Esports       | W   | 0.377      | 0.143        | 0.248 (0.013)    | 0.714 (0.038)    | 0 (0.000) |    11.57 | Anlelele, cej0t, raalz, Sdaim, sL1m3  |
|           16 |     7289 | 2024-01-26 | ex-Preasy Esport    | W   | 0.368      | 0.371        | 0.052 (0.007)    | 0.381 (0.052)    | 0 (0.000) |    10.07 | Anlelele, cej0t, raalz, Sdaim, sL1m3  |
|           15 |     7742 | 2024-01-18 | ex-Guild Eagles     | L   | 0.316      | -            | -                | -                | -         |    -1.05 | Anlelele, cej0t, raalz, sL1m3, Zyphon |
|           14 |     7758 | 2024-01-17 | 500                 | W   | 0.312      | 0.143        | -                | 0.479 (0.021)    | -         |     7.43 | Anlelele, cej0t, raalz, sL1m3, Zyphon |
|           13 |     7766 | 2024-01-17 | GUN5 Esports        | W   | 0.312      | -            | -                | -                | -         |     4.56 | Anlelele, cej0t, raalz, sL1m3, Zyphon |
|           12 |     7780 | 2024-01-17 | ROSOMAHA            | W   | 0.311      | -            | -                | -                | -         |     5.31 | Anlelele, cej0t, raalz, sL1m3, Zyphon |
|           11 |     7808 | 2024-01-17 | shovel              | W   | 0.311      | -            | -                | -                | -         |     2.70 | Anlelele, cej0t, raalz, sL1m3, Zyphon |
|           10 |     8095 | 2024-01-12 | LOADING             | L   | 0.278      | -            | -                | -                | -         |    -6.32 | Anlelele, cej0t, raalz, sL1m3, Zyphon |
|            9 |     8113 | 2024-01-12 | Balkan Bears        | W   | 0.278      | -            | -                | -                | -         |     2.37 | Anlelele, cej0t, raalz, sL1m3, Zyphon |
|            8 |     8645 | 2023-12-20 | Pera Esports        | L   | 0.122      | -            | -                | -                | -         |    -0.50 | Anlelele, cej0t, raalz, sL1m3, spooke |
|            7 |     8673 | 2023-12-18 | ARCRED              | W   | 0.109      | 0.333        | -                | 0.630 (0.023)    | -         |     2.61 | Anlelele, cej0t, raalz, sL1m3, spooke |
|            6 |     8676 | 2023-12-18 | showmakerz          | W   | 0.109      | -            | -                | -                | -         |     1.59 | Anlelele, cej0t, raalz, sL1m3, spooke |
|            5 |     9318 | 2023-12-09 | TSM                 | L   | 0.048      | -            | -                | -                | -         |    -0.62 | Anlelele, cej0t, raalz, sL1m3, spooke |
|            4 |     9388 | 2023-12-08 | ALTERNATE aTTaX     | L   | 0.042      | -            | -                | -                | -         |    -0.10 | Anlelele, cej0t, raalz, sL1m3, spooke |
|            3 |     9528 | 2023-12-06 | Endpoint            | W   | 0.028      | 0.371        | 0.012 (0.000)    | -                | -         |     0.80 | Anlelele, cej0t, raalz, sL1m3, spooke |
|            2 |     9618 | 2023-12-04 | RED Canids          | L   | 0.017      | -            | -                | -                | -         |    -0.05 | Anlelele, cej0t, raalz, sL1m3, spooke |
|            1 |     9673 | 2023-12-03 | G2 Esports          | L   | 0.009      | -            | -                | -                | -         |     0.00 | Anlelele, cej0t, raalz, sL1m3, spooke |

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
