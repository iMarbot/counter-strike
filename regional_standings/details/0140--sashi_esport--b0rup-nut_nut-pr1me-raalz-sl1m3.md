### Roster Details<br />
Team Name: Sashi Esport<br />
Roster: b0RUP, nut nut, PR1mE, raalz, sL1m3<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [140](../standings_global.md)<br />
Regional Rank: [97]( ../standings_europe.md)<br />
Final Rank Value:  792.9<br />
<br />
Final Rank Value (792.9) = Starting Rank Value (773.2) + Head To Head Adjustments (19.8)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.382[<sup>1</sup>](#table2)
- Bounty Collected: 0.262[<sup>2</sup>](#table1)
- Opponent Network: 0.090[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.183<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 773.2
- 400 + ( ( 0.183 - 0.000 ) / ( 0.786 - 0.000 ) ) * 1600 = 773.2


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
|           31 |     3519 | 2024-04-04 | GamerLegion Academy  | L   | 0.828      | -            | -                | -                | -         |   -10.00 | b0RUP, nut nut, PR1mE, raalz, sL1m3 |
|           30 |     3721 | 2024-03-29 | Natus Vincere Junior | L   | 0.788      | -            | -                | -                | -         |   -10.54 | b0RUP, niko, nut nut, PR1mE, sL1m3  |
|           29 |     3834 | 2024-03-27 | UNiTY esports        | W   | 0.775      | 0.333        | 0.021 (0.006)    | 0.766 (0.198)    | 0 (0.000) |    13.86 | b0RUP, niko, nut nut, PR1mE, sL1m3  |
|           28 |     3870 | 2024-03-26 | ex-Guild Eagles      | L   | 0.771      | -            | -                | -                | -         |    -7.69 | b0RUP, niko, nut nut, PR1mE, sL1m3  |
|           27 |     3900 | 2024-03-26 | GamerLegion Academy  | L   | 0.769      | -            | -                | -                | -         |   -11.12 | b0RUP, niko, nut nut, PR1mE, sL1m3  |
|           26 |     3910 | 2024-03-25 | Astralis Talent      | W   | 0.765      | 0.143        | 0.012 (0.001)    | 0.452 (0.049)    | 0 (0.000) |    14.86 | b0RUP, niko, nut nut, PR1mE, sL1m3  |
|           25 |     3922 | 2024-03-25 | WOPA Esport          | W   | 0.764      | 0.143        | 0.003 (0.000)    | 0.594 (0.065)    | 0 (0.000) |    11.79 | b0RUP, niko, nut nut, PR1mE, sL1m3  |
|           24 |     3950 | 2024-03-24 | FAVBET Team          | W   | 0.756      | 0.333        | 0.008 (0.002)    | 0.666 (0.168)    | 0 (0.000) |    15.17 | b0RUP, niko, nut nut, PR1mE, sL1m3  |
|           23 |     4037 | 2024-03-22 | Sprout Academy       | W   | 0.743      | -            | -                | -                | 0 (0.000) |     4.76 | b0RUP, niko, nut nut, PR1mE, sL1m3  |
|           22 |     4296 | 2024-03-17 | Natus Vincere Junior | L   | 0.708      | -            | -                | -                | -         |    -9.86 | b0RUP, niko, nut nut, PR1mE, sL1m3  |
|           21 |     4520 | 2024-03-13 | Sprout Academy       | W   | 0.682      | -            | -                | -                | 0 (0.000) |     3.99 | b0RUP, niko, nut nut, PR1mE, sL1m3  |
|           20 |     4847 | 2024-03-06 | Preasy Esport        | W   | 0.638      | 0.143        | 0.008 (0.001)    | 0.642 (0.059)    | 0 (0.000) |    11.20 | b0RUP, niko, nut nut, PR1mE, sL1m3  |
|           19 |     4858 | 2024-03-06 | XI Esport            | W   | 0.638      | 0.143        | 0.001 (0.000)    | 0.277 (0.025)    | 0 (0.000) |     7.29 | b0RUP, niko, nut nut, PR1mE, sL1m3  |
|           18 |     5157 | 2024-03-02 | ENTERPRISE esports   | L   | 0.611      | -            | -                | -                | -         |    -5.07 | b0RUP, n1Xen, niko, nut nut, PR1mE  |
|           17 |     5197 | 2024-03-02 | Passion UA           | L   | 0.609      | -            | -                | -                | -         |    -5.92 | b0RUP, n1Xen, niko, nut nut, PR1mE  |
|           16 |     5308 | 2024-02-28 | Astralis Talent      | L   | 0.591      | -            | -                | -                | -         |    -5.72 | b0RUP, niko, nut nut, PR1mE, sL1m3  |
|           15 |     5315 | 2024-02-28 | Team Atlantic        | W   | 0.591      | -            | -                | -                | 0 (0.000) |     3.85 | b0RUP, niko, nut nut, PR1mE, sL1m3  |
|           14 |     5336 | 2024-02-28 | Verdant              | W   | 0.589      | 0.303        | 0.014 (0.003)    | 1.000 (0.178)    | 0 (0.000) |    13.75 | b0RUP, n1Xen, niko, nut nut, PR1mE  |
|           13 |     5394 | 2024-02-26 | Metizport            | L   | 0.578      | -            | -                | -                | -         |    -3.68 | b0RUP, n1Xen, niko, nut nut, PR1mE  |
|           12 |     5575 | 2024-02-24 | Passion UA           | L   | 0.562      | -            | -                | -                | -         |    -5.03 | b0RUP, n1Xen, niko, nut nut, PR1mE  |
|           11 |     5825 | 2024-02-19 | Copenhagen Wolves    | W   | 0.531      | -            | -                | -                | -         |     5.13 | b0RUP, niko, nut nut, PR1mE, sL1m3  |
|           10 |     5876 | 2024-02-18 | Viperio              | L   | 0.523      | -            | -                | -                | -         |   -10.81 | b0RUP, n1Xen, niko, nut nut, PR1mE  |
|            9 |     5888 | 2024-02-18 | Natus Vincere Junior | L   | 0.522      | -            | -                | -                | -         |    -7.79 | b0RUP, n1Xen, niko, nut nut, PR1mE  |
|            8 |     6000 | 2024-02-16 | brazylijski luz      | W   | 0.509      | 0.303        | 0.013 (0.002)    | 0.490 (0.076)    | -         |     8.33 | b0RUP, n1Xen, niko, nut nut, PR1mE  |
|            7 |     6377 | 2024-02-06 | WOPA Esport          | W   | 0.444      | 0.143        | 0.003 (0.000)    | 0.594 (0.038)    | -         |     7.59 | b0RUP, Fessor, niko, nut nut, sL1m3 |
|            6 |     6400 | 2024-02-05 | Team Atlantic        | L   | 0.438      | -            | -                | -                | -         |   -11.11 | b0RUP, Fessor, niko, nut nut, sL1m3 |
|            5 |     6408 | 2024-02-05 | Astralis Talent      | L   | 0.438      | -            | -                | -                | -         |    -4.18 | b0RUP, Fessor, niko, nut nut, sL1m3 |
|            4 |     6415 | 2024-02-05 | Preasy Esport        | W   | 0.438      | 0.143        | 0.008 (0.001)    | 0.642 (0.040)    | -         |     8.10 | b0RUP, Fessor, niko, nut nut, sL1m3 |
|            3 |     7208 | 2024-01-22 | Copenhagen Wolves    | L   | 0.345      | -            | -                | -                | -         |    -7.47 | b0RUP, Fessor, niko, nut nut, sL1m3 |
|            2 |     7217 | 2024-01-22 | IMMAPROBLEM          | W   | 0.344      | -            | -                | -                | -         |     2.11 | b0RUP, Fessor, niko, nut nut, sL1m3 |
|            1 |     7222 | 2024-01-22 | XI Esport            | W   | 0.344      | -            | -                | -                | -         |     3.99 | b0RUP, Fessor, niko, nut nut, sL1m3 |

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
