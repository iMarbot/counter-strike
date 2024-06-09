### Roster Details<br />
Team Name: Sashi Esport<br />
Roster: b0RUP, nut nut, PR1mE, raalz, sL1m3<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [141](../standings_global.md)<br />
Regional Rank: [98]( ../standings_europe.md)<br />
Final Rank Value:  796.5<br />
<br />
Final Rank Value (796.5) = Starting Rank Value (775.7) + Head To Head Adjustments (20.8)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.382[<sup>1</sup>](#table2)
- Bounty Collected: 0.262[<sup>2</sup>](#table1)
- Opponent Network: 0.096[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.185<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 775.7
- 400 + ( ( 0.185 - 0.000 ) / ( 0.787 - 0.000 ) ) * 1600 = 775.7


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent             | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                              |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           31 |     3606 | 2024-04-04 | GamerLegion Academy  | L   | 0.828      | -            | -                | -                | -         |   -10.20 | b0RUP, nut nut, PR1mE, raalz, sL1m3 |
|           30 |     3815 | 2024-03-29 | Natus Vincere Junior | L   | 0.788      | -            | -                | -                | -         |   -10.61 | b0RUP, niko, nut nut, PR1mE, sL1m3  |
|           29 |     3931 | 2024-03-27 | UNiTY esports        | W   | 0.775      | 0.333        | 0.021 (0.006)    | 0.766 (0.198)    | 0 (0.000) |    13.72 | b0RUP, niko, nut nut, PR1mE, sL1m3  |
|           28 |     3967 | 2024-03-26 | ex-Guild Eagles      | L   | 0.771      | -            | -                | -                | -         |    -7.61 | b0RUP, niko, nut nut, PR1mE, sL1m3  |
|           27 |     3997 | 2024-03-26 | GamerLegion Academy  | L   | 0.769      | -            | -                | -                | -         |   -11.34 | b0RUP, niko, nut nut, PR1mE, sL1m3  |
|           26 |     4007 | 2024-03-25 | Astralis Talent      | W   | 0.765      | 0.143        | 0.012 (0.001)    | 0.452 (0.049)    | 0 (0.000) |    14.86 | b0RUP, niko, nut nut, PR1mE, sL1m3  |
|           25 |     4018 | 2024-03-25 | WOPA Esport          | W   | 0.764      | 0.143        | 0.003 (0.000)    | 0.594 (0.065)    | 0 (0.000) |    11.72 | b0RUP, niko, nut nut, PR1mE, sL1m3  |
|           24 |     4047 | 2024-03-24 | FAVBET Team          | W   | 0.756      | 0.333        | 0.008 (0.002)    | 0.845 (0.213)    | 0 (0.000) |    15.52 | b0RUP, niko, nut nut, PR1mE, sL1m3  |
|           23 |     4135 | 2024-03-22 | Sprout Academy       | W   | 0.743      | -            | -                | -                | 0 (0.000) |     4.67 | b0RUP, niko, nut nut, PR1mE, sL1m3  |
|           22 |     4402 | 2024-03-17 | Natus Vincere Junior | L   | 0.708      | -            | -                | -                | -         |    -9.92 | b0RUP, niko, nut nut, PR1mE, sL1m3  |
|           21 |     4639 | 2024-03-13 | Sprout Academy       | W   | 0.682      | -            | -                | -                | 0 (0.000) |     3.91 | b0RUP, niko, nut nut, PR1mE, sL1m3  |
|           20 |     4978 | 2024-03-06 | Preasy Esport        | W   | 0.638      | 0.143        | 0.008 (0.001)    | 0.705 (0.064)    | 0 (0.000) |    11.29 | b0RUP, niko, nut nut, PR1mE, sL1m3  |
|           19 |     4989 | 2024-03-06 | XI Esport            | W   | 0.638      | 0.143        | 0.001 (0.000)    | -                | 0 (0.000) |     7.24 | b0RUP, niko, nut nut, PR1mE, sL1m3  |
|           18 |     5305 | 2024-03-02 | ENTERPRISE esports   | L   | 0.611      | -            | -                | -                | -         |    -4.67 | b0RUP, n1Xen, niko, nut nut, PR1mE  |
|           17 |     5346 | 2024-03-02 | Passion UA           | L   | 0.609      | -            | -                | -                | -         |    -5.84 | b0RUP, n1Xen, niko, nut nut, PR1mE  |
|           16 |     5459 | 2024-02-28 | Astralis Talent      | L   | 0.591      | -            | -                | -                | -         |    -5.75 | b0RUP, niko, nut nut, PR1mE, sL1m3  |
|           15 |     5466 | 2024-02-28 | Team Atlantic        | W   | 0.591      | -            | -                | -                | 0 (0.000) |     3.80 | b0RUP, niko, nut nut, PR1mE, sL1m3  |
|           14 |     5488 | 2024-02-28 | Verdant              | W   | 0.589      | 0.303        | 0.014 (0.003)    | 1.000 (0.178)    | 0 (0.000) |    13.75 | b0RUP, n1Xen, niko, nut nut, PR1mE  |
|           13 |     5551 | 2024-02-26 | Metizport            | L   | 0.578      | -            | -                | -                | -         |    -3.69 | b0RUP, n1Xen, niko, nut nut, PR1mE  |
|           12 |     5735 | 2024-02-24 | Passion UA           | L   | 0.562      | -            | -                | -                | -         |    -4.94 | b0RUP, n1Xen, niko, nut nut, PR1mE  |
|           11 |     5996 | 2024-02-19 | Copenhagen Wolves    | W   | 0.531      | 0.143        | -                | 0.387 (0.029)    | -         |     5.51 | b0RUP, niko, nut nut, PR1mE, sL1m3  |
|           10 |     6049 | 2024-02-18 | Viperio              | L   | 0.523      | -            | -                | -                | -         |   -10.63 | b0RUP, n1Xen, niko, nut nut, PR1mE  |
|            9 |     6061 | 2024-02-18 | Natus Vincere Junior | L   | 0.522      | -            | -                | -                | -         |    -7.84 | b0RUP, n1Xen, niko, nut nut, PR1mE  |
|            8 |     6176 | 2024-02-16 | brazylijski luz      | W   | 0.509      | 0.303        | 0.013 (0.002)    | 0.514 (0.079)    | -         |     8.46 | b0RUP, n1Xen, niko, nut nut, PR1mE  |
|            7 |     6572 | 2024-02-06 | WOPA Esport          | W   | 0.444      | 0.143        | 0.003 (0.000)    | 0.594 (0.038)    | -         |     7.56 | b0RUP, Fessor, niko, nut nut, sL1m3 |
|            6 |     6596 | 2024-02-05 | Team Atlantic        | L   | 0.438      | -            | -                | -                | -         |   -11.14 | b0RUP, Fessor, niko, nut nut, sL1m3 |
|            5 |     6606 | 2024-02-05 | Astralis Talent      | L   | 0.438      | -            | -                | -                | -         |    -4.20 | b0RUP, Fessor, niko, nut nut, sL1m3 |
|            4 |     6613 | 2024-02-05 | Preasy Esport        | W   | 0.438      | 0.143        | 0.008 (0.001)    | 0.705 (0.044)    | -         |     8.20 | b0RUP, Fessor, niko, nut nut, sL1m3 |
|            3 |     7449 | 2024-01-22 | Copenhagen Wolves    | L   | 0.345      | -            | -                | -                | -         |    -7.15 | b0RUP, Fessor, niko, nut nut, sL1m3 |
|            2 |     7459 | 2024-01-22 | IMMAPROBLEM          | W   | 0.344      | -            | -                | -                | -         |     2.09 | b0RUP, Fessor, niko, nut nut, sL1m3 |
|            1 |     7465 | 2024-01-22 | XI Esport            | W   | 0.344      | -            | -                | -                | -         |     3.98 | b0RUP, Fessor, niko, nut nut, sL1m3 |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($7,198.90)
- Divide that value by the 5th highest value among all rosters ($300,806.11)
- The final value (0.02) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
