### Roster Details<br />
Team Name: INGLORIOUS<br />
Roster: Drobnyy, Esphirion, Jad0R1x, LAYM, V1<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [116](../standings_global.md)<br />
Regional Rank: [83]( ../standings_europe.md)<br />
Final Rank Value:  826.4<br />
<br />
Final Rank Value (826.4) = Starting Rank Value (786.4) + Head To Head Adjustments (40.0)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.303[<sup>1</sup>](#table2)
- Bounty Collected: 0.340[<sup>2</sup>](#table1)
- Opponent Network: 0.136[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.195<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 786.4
- 400 + ( ( 0.195 - 0.000 ) / ( 0.806 - 0.000 ) ) * 1600 = 786.4


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent                    | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins      | H2H Adj. | Roster                                |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           37 |     2323 | 2024-03-13 | Insilio                     | L   | 0.845      | -            | -                | -                | -             |    -7.79 | Drobnyy, Esphirion, Jad0R1x, LAYM, V1 |
|           36 |     2496 | 2024-03-09 | Nexus Gaming                | L   | 0.818      | -            | -                | -                | -             |    -9.57 | Drobnyy, Esphirion, Jad0R1x, LAYM, V1 |
|           35 |     2543 | 2024-03-08 | JANO Esports                | L   | 0.810      | -            | -                | -                | -             |   -15.55 | Drobnyy, Esphirion, Jad0R1x, LAYM, V1 |
|           34 |     2569 | 2024-03-07 | MOUZ NXT                    | W   | 0.805      | 0.371        | 0.215 (0.064)    | 1.000 (0.299)    | false (0.000) |    19.96 | Drobnyy, Esphirion, Jad0R1x, LAYM, V1 |
|           33 |     2627 | 2024-03-06 | ENTERPRISE esports          | W   | 0.798      | 0.371        | 0.039 (0.012)    | 0.476 (0.141)    | false (0.000) |    16.19 | Drobnyy, Esphirion, Jad0R1x, LAYM, V1 |
|           32 |     2900 | 2024-03-02 | Ex-sYnck                    | L   | 0.770      | -            | -                | -                | -             |   -19.54 | Drobnyy, Esphirion, Jad0R1x, LAYM, V1 |
|           31 |     2952 | 2024-02-29 | Nexus Gaming                | W   | 0.758      | 0.371        | 0.031 (0.009)    | 0.772 (0.217)    | false (0.000) |    14.59 | Drobnyy, Esphirion, Jad0R1x, LAYM, V1 |
|           30 |     2962 | 2024-02-29 | RUBY                        | L   | 0.758      | -            | -                | -                | -             |    -8.80 | Drobnyy, Esphirion, Jad0R1x, LAYM, V1 |
|           29 |     3005 | 2024-02-28 | Metizport                   | L   | 0.750      | -            | -                | -                | -             |    -5.14 | Drobnyy, Esphirion, Jad0R1x, LAYM, V1 |
|           28 |     3065 | 2024-02-26 | Team Space                  | W   | 0.739      | 0.143        | 0.008 (0.001)    | -                | false (0.000) |     8.71 | Drobnyy, Esphirion, Jad0R1x, LAYM, V1 |
|           27 |     3144 | 2024-02-24 | Verdant                     | W   | 0.726      | 0.371        | 0.027 (0.007)    | 0.662 (0.178)    | false (0.000) |    15.32 | Drobnyy, Esphirion, Jad0R1x, LAYM, V1 |
|           26 |     3153 | 2024-02-24 | DASH                        | W   | 0.725      | 0.371        | -                | 0.251 (0.068)    | false (0.000) |     9.52 | Drobnyy, Esphirion, Jad0R1x, LAYM, V1 |
|           25 |     3218 | 2024-02-23 | EsmagaB                     | W   | 0.718      | 0.371        | 0.016 (0.004)    | 0.559 (0.149)    | false (0.000) |    12.02 | Drobnyy, Esphirion, Jad0R1x, LAYM, V1 |
|           24 |     3236 | 2024-02-22 | NOM Esports                 | L   | 0.712      | -            | -                | -                | -             |   -16.36 | Drobnyy, Esphirion, Jad0R1x, LAYM, V1 |
|           23 |     3252 | 2024-02-22 | Copenhagen Wolves           | W   | 0.712      | 0.371        | -                | 0.417 (0.110)    | false (0.000) |     5.71 | Drobnyy, Esphirion, Jad0R1x, LAYM, V1 |
|           22 |     3713 | 2024-02-12 | ARCRED                      | L   | 0.646      | -            | -                | -                | -             |    -9.82 | Drobnyy, Esphirion, Jad0R1x, LAYM, V1 |
|           21 |     3742 | 2024-02-11 | Lilmix                      | W   | 0.639      | 0.143        | -                | 0.604 (0.055)    | false (0.000) |     5.17 | Drobnyy, Esphirion, Jad0R1x, LAYM, V1 |
|           20 |     3747 | 2024-02-11 | NOM Esports                 | W   | 0.639      | -            | -                | -                | false (0.000) |     5.59 | Drobnyy, Esphirion, Jad0R1x, LAYM, V1 |
|           19 |     3816 | 2024-02-08 | Lausanne-Sport Esports      | W   | 0.619      | 0.371        | 0.004 (0.001)    | 0.241 (0.055)    | -             |     8.67 | Drobnyy, Esphirion, Jad0R1x, LAYM, V1 |
|           18 |     4044 | 2024-02-02 | 9Pandas                     | L   | 0.578      | -            | -                | -                | -             |    -2.27 | Drobnyy, Esphirion, Jad0R1x, LAYM, V1 |
|           17 |     4078 | 2024-02-01 | Ex-Hot Headed Gaming        | W   | 0.571      | -            | -                | -                | -             |     3.06 | Drobnyy, Esphirion, Jad0R1x, LAYM, V1 |
|           16 |     4324 | 2024-01-26 | Rhyno Esports               | W   | 0.531      | 0.371        | 0.047 (0.009)    | 0.446 (0.088)    | -             |    11.26 | Drobnyy, Esphirion, Jad0R1x, LAYM, V1 |
|           15 |     4810 | 2024-01-16 | JANO Esports                | L   | 0.465      | -            | -                | -                | -             |    -7.84 | Drobnyy, Esphirion, Jad0R1x, LAYM, V1 |
|           14 |     5045 | 2024-01-10 | CYBERSHOKE Esports          | L   | 0.426      | -            | -                | -                | -             |    -7.88 | Drobnyy, Esphirion, Jad0R1x, LAYM, V1 |
|           13 |     5354 | 2023-12-17 | EYEBALLERS                  | W   | 0.265      | 0.294        | 0.051 (0.004)    | -                | -             |     5.92 | Drobnyy, Esphirion, Jad0R1x, LAYM, V1 |
|           12 |     5451 | 2023-12-16 | The Witchers                | W   | 0.259      | 0.294        | 0.035 (0.003)    | -                | -             |     4.02 | Drobnyy, Esphirion, Jad0R1x, LAYM, V1 |
|           11 |     5470 | 2023-12-16 | LEON Esports                | W   | 0.258      | -            | -                | -                | -             |     2.98 | Drobnyy, Esphirion, Jad0R1x, LAYM, V1 |
|           10 |     6242 | 2023-11-29 | GODSENT                     | L   | 0.146      | -            | -                | -                | -             |    -2.23 | Drobnyy, Esphirion, Jad0R1x, LAYM, V1 |
|            9 |     6543 | 2023-11-22 | Aurora Young Blud           | W   | 0.099      | -            | -                | -                | -             |     1.72 | Drobnyy, Esphirion, Jad0R1x, LAYM, V1 |
|            8 |     6585 | 2023-11-21 | Bleiz                       | W   | 0.092      | -            | -                | -                | -             |     0.41 | Drobnyy, Esphirion, Jad0R1x, LAYM, V1 |
|            7 |     6620 | 2023-11-20 | Nemiga Gaming               | L   | 0.086      | -            | -                | -                | -             |    -0.13 | Drobnyy, Esphirion, Jad0R1x, LAYM, V1 |
|            6 |     6783 | 2023-11-17 | XGOD                        | W   | 0.064      | -            | -                | -                | -             |     0.34 | Drobnyy, Esphirion, Jad0R1x, LAYM, V1 |
|            5 |     6825 | 2023-11-16 | RoundsGG                    | W   | 0.058      | -            | -                | -                | -             |     0.77 | Drobnyy, Esphirion, Jad0R1x, LAYM, V1 |
|            4 |     6865 | 2023-11-15 | For The Win Esports         | L   | 0.052      | -            | -                | -                | -             |    -1.08 | Drobnyy, Esphirion, Jad0R1x, LAYM, V1 |
|            3 |     6869 | 2023-11-15 | Into The Breach             | W   | 0.052      | -            | -                | -                | -             |     0.86 | Drobnyy, Esphirion, Jad0R1x, LAYM, V1 |
|            2 |     6877 | 2023-11-15 | UNiTY esports (Slovak team) | W   | 0.052      | -            | -                | -                | -             |     1.22 | Drobnyy, Esphirion, Jad0R1x, LAYM, V1 |
|            1 |     7201 | 2023-11-08 | Soda Gaming                 | W   | 0.004      | -            | -                | -                | -             |     0.06 | Drobnyy, Esphirion, Jad0R1x, LAYM, V1 |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($795.42)
- Divide that value by the 5th highest value among all rosters ($158,437.64)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
