### Roster Details<br />
Team Name: INGLORIOUS<br />
Roster: Drobnyy, Esphirion, Jad0R1x, LAYM, V1<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [143](../standings_global.md)<br />
Regional Rank: [100]( ../standings_europe.md)<br />
Final Rank Value:  786.4<br />
<br />
Final Rank Value (786.4) = Starting Rank Value (744.5) + Head To Head Adjustments (41.9)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.251[<sup>1</sup>](#table2)
- Bounty Collected: 0.306[<sup>2</sup>](#table1)
- Opponent Network: 0.120[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.169<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 744.5
- 400 + ( ( 0.169 - 0.000 ) / ( 0.786 - 0.000 ) ) * 1600 = 744.5


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent               | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           31 |     4496 | 2024-03-13 | Insilio                | L   | 0.684      | -            | -                | -                | -         |    -5.74 | Drobnyy, Esphirion, Jad0R1x, LAYM, V1 |
|           30 |     4710 | 2024-03-09 | Nexus Gaming           | L   | 0.657      | -            | -                | -                | -         |    -6.63 | Drobnyy, Esphirion, Jad0R1x, LAYM, V1 |
|           29 |     4766 | 2024-03-08 | JANO Esports           | L   | 0.649      | -            | -                | -                | -         |   -11.29 | Drobnyy, Esphirion, Jad0R1x, LAYM, V1 |
|           28 |     4805 | 2024-03-07 | MOUZ NXT               | W   | 0.644      | 0.371        | 0.157 (0.038)    | 0.950 (0.227)    | 0 (0.000) |    17.05 | Drobnyy, Esphirion, Jad0R1x, LAYM, V1 |
|           27 |     4882 | 2024-03-06 | ENTERPRISE esports     | W   | 0.637      | 0.371        | 0.010 (0.002)    | 0.809 (0.191)    | 0 (0.000) |    13.91 | Drobnyy, Esphirion, Jad0R1x, LAYM, V1 |
|           26 |     5212 | 2024-03-02 | ex-sYnck               | L   | 0.609      | -            | -                | -                | -         |   -11.02 | Drobnyy, Esphirion, Jad0R1x, LAYM, V1 |
|           25 |     5272 | 2024-02-29 | Nexus Gaming           | W   | 0.597      | 0.371        | 0.014 (0.003)    | 0.825 (0.183)    | 0 (0.000) |    12.74 | Drobnyy, Esphirion, Jad0R1x, LAYM, V1 |
|           24 |     5282 | 2024-02-29 | RUBY                   | L   | 0.597      | -            | -                | -                | -         |    -5.46 | Drobnyy, Esphirion, Jad0R1x, LAYM, V1 |
|           23 |     5339 | 2024-02-28 | Metizport              | L   | 0.589      | -            | -                | -                | -         |    -4.28 | Drobnyy, Esphirion, Jad0R1x, LAYM, V1 |
|           22 |     5368 | 2024-02-27 | kONO.ECF               | L   | 0.584      | -            | -                | -                | -         |    -5.79 | Drobnyy, Esphirion, Jad0R1x, LAYM, V1 |
|           21 |     5404 | 2024-02-26 | Team Space             | W   | 0.578      | 0.143        | 0.009 (0.001)    | -                | 0 (0.000) |    10.40 | Drobnyy, Esphirion, Jad0R1x, LAYM, V1 |
|           20 |     5514 | 2024-02-24 | Verdant                | W   | 0.564      | 0.371        | 0.014 (0.003)    | 1.000 (0.210)    | 0 (0.000) |    13.39 | Drobnyy, Esphirion, Jad0R1x, LAYM, V1 |
|           19 |     5532 | 2024-02-24 | DASH                   | W   | 0.564      | 0.371        | -                | 0.358 (0.075)    | 0 (0.000) |     7.68 | Drobnyy, Esphirion, Jad0R1x, LAYM, V1 |
|           18 |     5615 | 2024-02-23 | esmagaB                | W   | 0.557      | 0.371        | 0.008 (0.002)    | 0.460 (0.095)    | 0 (0.000) |    10.09 | Drobnyy, Esphirion, Jad0R1x, LAYM, V1 |
|           17 |     5637 | 2024-02-22 | NOM Esports            | L   | 0.551      | -            | -                | -                | -         |   -11.94 | Drobnyy, Esphirion, Jad0R1x, LAYM, V1 |
|           16 |     5655 | 2024-02-22 | Copenhagen Wolves      | W   | 0.551      | 0.371        | -                | 0.309 (0.063)    | 0 (0.000) |     5.29 | Drobnyy, Esphirion, Jad0R1x, LAYM, V1 |
|           15 |     6194 | 2024-02-12 | ARCRED                 | L   | 0.484      | -            | -                | -                | -         |    -7.34 | Drobnyy, Esphirion, Jad0R1x, LAYM, V1 |
|           14 |     6227 | 2024-02-11 | Lilmix                 | W   | 0.478      | 0.143        | 0.006 (0.000)    | 0.581 (0.040)    | 0 (0.000) |     9.55 | Drobnyy, Esphirion, Jad0R1x, LAYM, V1 |
|           13 |     6233 | 2024-02-11 | NOM Esports            | W   | 0.477      | -            | -                | -                | 0 (0.000) |     4.93 | Drobnyy, Esphirion, Jad0R1x, LAYM, V1 |
|           12 |     6236 | 2024-02-11 | ENRAGE                 | W   | 0.477      | -            | -                | -                | -         |     3.44 | Drobnyy, Esphirion, Jad0R1x, LAYM, V1 |
|           11 |     6325 | 2024-02-08 | Lausanne-Sport Esports | W   | 0.458      | 0.371        | -                | 0.257 (0.044)    | -         |     7.35 | Drobnyy, Esphirion, Jad0R1x, LAYM, V1 |
|           10 |     6551 | 2024-02-03 | team amster333         | L   | 0.423      | -            | -                | -                | -         |   -10.85 | Drobnyy, Esphirion, Jad0R1x, LAYM, V1 |
|            9 |     6628 | 2024-02-02 | 9Pandas                | L   | 0.417      | -            | -                | -                | -         |    -1.11 | Drobnyy, Esphirion, Jad0R1x, LAYM, V1 |
|            8 |     6675 | 2024-02-01 | ex-Hot Headed Gaming   | W   | 0.410      | -            | -                | -                | -         |     2.71 | Drobnyy, Esphirion, Jad0R1x, LAYM, V1 |
|            7 |     7044 | 2024-01-26 | Rhyno Esports          | W   | 0.370      | 0.371        | 0.029 (0.004)    | 0.518 (0.071)    | -         |     9.65 | Drobnyy, Esphirion, Jad0R1x, LAYM, V1 |
|            6 |     7675 | 2024-01-16 | JANO Esports           | L   | 0.304      | -            | -                | -                | -         |    -7.67 | Drobnyy, Esphirion, Jad0R1x, LAYM, V1 |
|            5 |     8004 | 2024-01-10 | CYBERSHOKE Esports     | L   | 0.265      | -            | -                | -                | -         |    -4.33 | Drobnyy, Esphirion, Jad0R1x, LAYM, V1 |
|            4 |     8454 | 2023-12-17 | EYEBALLERS             | W   | 0.104      | 0.294        | 0.012 (0.000)    | -                | -         |     2.35 | Drobnyy, Esphirion, Jad0R1x, LAYM, V1 |
|            3 |     8464 | 2023-12-17 | Betera Esports         | W   | 0.103      | 0.294        | 0.023 (0.001)    | -                | -         |     1.88 | Drobnyy, Esphirion, Jad0R1x, LAYM, V1 |
|            2 |     8579 | 2023-12-16 | The Witchers           | W   | 0.098      | -            | -                | -                | -         |     1.38 | Drobnyy, Esphirion, Jad0R1x, LAYM, V1 |
|            1 |     8605 | 2023-12-16 | LEON Esports           | W   | 0.097      | -            | -                | -                | -         |     1.56 | Drobnyy, Esphirion, Jad0R1x, LAYM, V1 |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($312.22)
- Divide that value by the 5th highest value among all rosters ($300,806.11)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
