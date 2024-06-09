### Roster Details<br />
Team Name: INGLORIOUS<br />
Roster: Drobnyy, Esphirion, Jad0R1x, LAYM, V1<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [146](../standings_global.md)<br />
Regional Rank: [103]( ../standings_europe.md)<br />
Final Rank Value:  791.2<br />
<br />
Final Rank Value (791.2) = Starting Rank Value (747.8) + Head To Head Adjustments (43.4)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.251[<sup>1</sup>](#table2)
- Bounty Collected: 0.304[<sup>2</sup>](#table1)
- Opponent Network: 0.129[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.171<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 747.8
- 400 + ( ( 0.171 - 0.000 ) / ( 0.787 - 0.000 ) ) * 1600 = 747.8


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
|           33 |     4611 | 2024-03-13 | Insilio                | L   | 0.684      | -            | -                | -                | -         |    -5.87 | Drobnyy, Esphirion, Jad0R1x, LAYM, V1 |
|           32 |     4835 | 2024-03-09 | Nexus Gaming           | L   | 0.657      | -            | -                | -                | -         |    -7.07 | Drobnyy, Esphirion, Jad0R1x, LAYM, V1 |
|           31 |     4894 | 2024-03-08 | JANO Esports           | L   | 0.649      | -            | -                | -                | -         |   -11.23 | Drobnyy, Esphirion, Jad0R1x, LAYM, V1 |
|           30 |     4934 | 2024-03-07 | MOUZ NXT               | W   | 0.644      | 0.371        | 0.157 (0.038)    | 0.977 (0.234)    | 0 (0.000) |    17.20 | Drobnyy, Esphirion, Jad0R1x, LAYM, V1 |
|           29 |     5013 | 2024-03-06 | ENTERPRISE esports     | W   | 0.637      | 0.371        | 0.010 (0.002)    | 0.898 (0.212)    | 0 (0.000) |    14.30 | Drobnyy, Esphirion, Jad0R1x, LAYM, V1 |
|           28 |     5361 | 2024-03-02 | ex-sYnck               | L   | 0.609      | -            | -                | -                | -         |   -10.59 | Drobnyy, Esphirion, Jad0R1x, LAYM, V1 |
|           27 |     5422 | 2024-02-29 | Nexus Gaming           | W   | 0.597      | 0.371        | 0.003 (0.001)    | 0.857 (0.190)    | 0 (0.000) |    12.28 | Drobnyy, Esphirion, Jad0R1x, LAYM, V1 |
|           26 |     5432 | 2024-02-29 | RUBY                   | L   | 0.597      | -            | -                | -                | -         |    -5.51 | Drobnyy, Esphirion, Jad0R1x, LAYM, V1 |
|           25 |     5491 | 2024-02-28 | Metizport              | L   | 0.589      | -            | -                | -                | -         |    -4.31 | Drobnyy, Esphirion, Jad0R1x, LAYM, V1 |
|           24 |     5521 | 2024-02-27 | kONO.ECF               | L   | 0.584      | -            | -                | -                | -         |    -5.38 | Drobnyy, Esphirion, Jad0R1x, LAYM, V1 |
|           23 |     5561 | 2024-02-26 | Team Space             | W   | 0.578      | 0.143        | 0.009 (0.001)    | -                | 0 (0.000) |    10.31 | Drobnyy, Esphirion, Jad0R1x, LAYM, V1 |
|           22 |     5674 | 2024-02-24 | Verdant                | W   | 0.564      | 0.371        | 0.014 (0.003)    | 1.000 (0.210)    | 0 (0.000) |    13.37 | Drobnyy, Esphirion, Jad0R1x, LAYM, V1 |
|           21 |     5692 | 2024-02-24 | DASH                   | W   | 0.564      | 0.371        | -                | 0.385 (0.081)    | 0 (0.000) |     7.85 | Drobnyy, Esphirion, Jad0R1x, LAYM, V1 |
|           20 |     5775 | 2024-02-23 | esmagaB                | W   | 0.557      | 0.371        | 0.008 (0.002)    | 0.564 (0.117)    | 0 (0.000) |    10.22 | Drobnyy, Esphirion, Jad0R1x, LAYM, V1 |
|           19 |     5797 | 2024-02-22 | NOM Esports            | L   | 0.551      | -            | -                | -                | -         |   -12.03 | Drobnyy, Esphirion, Jad0R1x, LAYM, V1 |
|           18 |     5815 | 2024-02-22 | Copenhagen Wolves      | W   | 0.551      | 0.371        | -                | 0.387 (0.079)    | 0 (0.000) |     5.66 | Drobnyy, Esphirion, Jad0R1x, LAYM, V1 |
|           17 |     6381 | 2024-02-12 | ARCRED                 | L   | 0.484      | -            | -                | -                | -         |    -7.39 | Drobnyy, Esphirion, Jad0R1x, LAYM, V1 |
|           16 |     6415 | 2024-02-11 | Lilmix                 | W   | 0.478      | 0.143        | 0.006 (0.000)    | 0.593 (0.041)    | 0 (0.000) |     9.21 | Drobnyy, Esphirion, Jad0R1x, LAYM, V1 |
|           15 |     6421 | 2024-02-11 | NOM Esports            | W   | 0.477      | -            | -                | -                | 0 (0.000) |     4.89 | Drobnyy, Esphirion, Jad0R1x, LAYM, V1 |
|           14 |     6424 | 2024-02-11 | ENRAGE                 | W   | 0.477      | -            | -                | -                | -         |     3.38 | Drobnyy, Esphirion, Jad0R1x, LAYM, V1 |
|           13 |     6513 | 2024-02-08 | Lausanne-Sport Esports | W   | 0.458      | 0.371        | -                | 0.306 (0.052)    | -         |     7.75 | Drobnyy, Esphirion, Jad0R1x, LAYM, V1 |
|           12 |     6754 | 2024-02-03 | team amster333         | L   | 0.423      | -            | -                | -                | -         |   -10.90 | Drobnyy, Esphirion, Jad0R1x, LAYM, V1 |
|           11 |     6833 | 2024-02-02 | 9Pandas                | L   | 0.417      | -            | -                | -                | -         |    -1.07 | Drobnyy, Esphirion, Jad0R1x, LAYM, V1 |
|           10 |     6884 | 2024-02-01 | ex-Hot Headed Gaming   | W   | 0.410      | -            | -                | -                | -         |     2.63 | Drobnyy, Esphirion, Jad0R1x, LAYM, V1 |
|            9 |     7268 | 2024-01-26 | Rhyno Esports          | W   | 0.370      | 0.371        | 0.029 (0.004)    | 0.567 (0.078)    | -         |     9.64 | Drobnyy, Esphirion, Jad0R1x, LAYM, V1 |
|            8 |     7415 | 2024-01-23 | ex-sYnck               | W   | 0.351      | -            | -                | -                | -         |     5.68 | Drobnyy, Esphirion, Jad0R1x, LAYM, V1 |
|            7 |     7700 | 2024-01-18 | kONO.ECF               | L   | 0.318      | -            | -                | -                | -         |    -3.30 | Drobnyy, Esphirion, Jad0R1x, LAYM, V1 |
|            6 |     7924 | 2024-01-16 | JANO Esports           | L   | 0.304      | -            | -                | -                | -         |    -7.68 | Drobnyy, Esphirion, Jad0R1x, LAYM, V1 |
|            5 |     8258 | 2024-01-10 | CYBERSHOKE Esports     | L   | 0.265      | -            | -                | -                | -         |    -5.83 | Drobnyy, Esphirion, Jad0R1x, LAYM, V1 |
|            4 |     8713 | 2023-12-17 | EYEBALLERS             | W   | 0.104      | 0.294        | 0.012 (0.000)    | -                | -         |     2.35 | Drobnyy, Esphirion, Jad0R1x, LAYM, V1 |
|            3 |     8724 | 2023-12-17 | Betera Esports         | W   | 0.103      | 0.294        | 0.023 (0.001)    | -                | -         |     1.86 | Drobnyy, Esphirion, Jad0R1x, LAYM, V1 |
|            2 |     8839 | 2023-12-16 | The Witchers           | W   | 0.098      | -            | -                | -                | -         |     1.37 | Drobnyy, Esphirion, Jad0R1x, LAYM, V1 |
|            1 |     8866 | 2023-12-16 | LEON Esports           | W   | 0.097      | -            | -                | -                | -         |     1.56 | Drobnyy, Esphirion, Jad0R1x, LAYM, V1 |

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
