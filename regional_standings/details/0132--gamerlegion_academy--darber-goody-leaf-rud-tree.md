### Roster Details<br />
Team Name: GamerLegion Academy<br />
Roster: Darber, Goody, leaf, rud, Tree<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [132](../standings_global.md)<br />
Regional Rank: [92]( ../standings_europe.md)<br />
Final Rank Value:  809.2<br />
<br />
Final Rank Value (809.2) = Starting Rank Value (838.4) + Head To Head Adjustments (-29.2)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.365[<sup>1</sup>](#table2)
- Bounty Collected: 0.310[<sup>2</sup>](#table1)
- Opponent Network: 0.187[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.215<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 838.4
- 400 + ( ( 0.215 - 0.000 ) / ( 0.786 - 0.000 ) ) * 1600 = 838.4


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent             | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                           |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           70 |       82 | 2024-05-29 | ThunderFlash         | L   | 1.000      | -            | -                | -                | -         |   -11.99 | Darber, Goody, leaf, rud, Tree   |
|           69 |       93 | 2024-05-29 | Astralis Talent      | W   | 1.000      | -            | -                | -                | 0 (0.000) |    12.94 | Darber, Goody, leaf, rud, Tree   |
|           68 |      113 | 2024-05-28 | UNiTY esports        | W   | 1.000      | 0.143        | 0.021 (0.003)    | -                | 0 (0.000) |    17.76 | Darber, Goody, leaf, rud, Tree   |
|           67 |      258 | 2024-05-25 | NOM Esports          | W   | 1.000      | 0.372        | -                | 0.360 (0.134)    | 0 (0.000) |    10.10 | Darber, Goody, leaf, rud, Tree   |
|           66 |      331 | 2024-05-24 | ARROW                | W   | 1.000      | 0.372        | -                | 0.344 (0.128)    | 0 (0.000) |    14.74 | Darber, Goody, leaf, rud, Tree   |
|           65 |      343 | 2024-05-24 | Team PeeP            | L   | 1.000      | -            | -                | -                | -         |   -20.83 | Darber, Goody, leaf, rud, Tree   |
|           64 |      354 | 2024-05-24 | esmagaB              | L   | 1.000      | -            | -                | -                | -         |   -14.17 | Darber, Goody, leaf, rud, Tree   |
|           63 |      390 | 2024-05-23 | brazylijski luz      | L   | 1.000      | -            | -                | -                | -         |   -13.86 | Darber, Goody, leaf, rud, Tree   |
|           62 |      401 | 2024-05-23 | WOPA Esport          | L   | 1.000      | -            | -                | -                | -         |   -19.80 | Darber, Goody, leaf, rud, Tree   |
|           61 |      466 | 2024-05-22 | V1dar Gaming         | L   | 1.000      | -            | -                | -                | -         |   -17.45 | Darber, Goody, leaf, rud, Tree   |
|           60 |      486 | 2024-05-22 | Lilmix               | W   | 1.000      | 0.372        | -                | 0.581 (0.216)    | 0 (0.000) |    12.33 | Darber, Goody, leaf, rud, Tree   |
|           59 |      549 | 2024-05-21 | FLuffy Gangsters     | W   | 1.000      | 0.372        | -                | 0.315 (0.117)    | 0 (0.000) |     9.35 | Darber, Goody, leaf, rud, Tree   |
|           58 |      593 | 2024-05-21 | Grannys Knockers     | L   | 1.000      | -            | -                | -                | -         |   -17.43 | Darber, Goody, leaf, rud, Tree   |
|           57 |      691 | 2024-05-20 | kONO.ECF             | L   | 1.000      | -            | -                | -                | -         |   -13.64 | Darber, Goody, leaf, rud, Tree   |
|           56 |      973 | 2024-05-17 | Raptors Esports Club | W   | 1.000      | 0.372        | 0.007 (0.003)    | 0.406 (0.151)    | 0 (0.000) |    15.14 | Darber, Goody, leaf, rud, Tree   |
|           55 |     1094 | 2024-05-16 | scooby               | W   | 1.000      | -            | -                | -                | 0 (0.000) |     2.59 | Goody, leaf, n0te, rud, Tree60   |
|           54 |     1184 | 2024-05-15 | Sangrija             | W   | 1.000      | -            | -                | -                | 0 (0.000) |     4.79 | Darber, Goody, leaf, n0te, rud   |
|           53 |     1273 | 2024-05-14 | MASONIC              | W   | 1.000      | 0.354        | 0.018 (0.006)    | -                | 0 (0.000) |    15.79 | Darber, Goody, leaf, n0te, rud   |
|           52 |     1476 | 2024-05-11 | UNiTY esports        | L   | 1.000      | -            | -                | -                | -         |   -13.40 | Darber, eku, Goody, leaf, rud    |
|           51 |     1535 | 2024-05-10 | Verdant              | L   | 1.000      | -            | -                | -                | -         |   -12.99 | Darber, eku, Goody, leaf, rud    |
|           50 |     1649 | 2024-05-08 | ex-K10               | W   | 1.000      | 0.333        | -                | 0.382 (0.127)    | -         |    13.08 | Darber, eku, Goody, nestee, rud  |
|           49 |     1735 | 2024-05-06 | Copenhagen Wolves    | W   | 1.000      | -            | -                | -                | -         |     7.57 | Darber, eku, Goody, leaf, rud    |
|           48 |     1787 | 2024-05-05 | MOUZ NXT             | L   | 1.000      | -            | -                | -                | -         |    -7.64 | Darber, Goody, leaf, rud, shadiy |
|           47 |     1834 | 2024-05-04 | B8                   | L   | 1.000      | -            | -                | -                | -         |    -6.62 | Darber, Goody, leaf, rud, shadiy |
|           46 |     1894 | 2024-05-03 | Preasy Esport        | L   | 1.000      | -            | -                | -                | -         |   -18.66 | cryths, Darber, Goody, leaf, rud |
|           45 |     2003 | 2024-05-01 | RUBY                 | W   | 1.000      | 0.435        | 0.012 (0.005)    | 0.728 (0.316)    | -         |    19.54 | Darber, Goody, leaf, rud, shadiy |
|           44 |     2013 | 2024-04-30 | Team Sampi           | L   | 1.000      | -            | -                | -                | -         |   -10.09 | Darber, Goody, leaf, rud, shadiy |
|           43 |     2047 | 2024-04-30 | NOM Esports          | L   | 1.000      | -            | -                | -                | -         |   -23.06 | cryths, Darber, Goody, leaf, rud |
|           42 |     2218 | 2024-04-27 | EXO Clan             | W   | 0.981      | -            | -                | -                | -         |    21.22 | Darber, Goody, leaf, rud, sSen   |
|           41 |     2276 | 2024-04-26 | JANO Esports         | W   | 0.976      | -            | -                | -                | -         |    10.75 | Darber, Goody, leaf, rud, sSen   |
|           40 |     2287 | 2024-04-26 | EXO Clan             | W   | 0.974      | 0.333        | 0.013 (0.004)    | 0.510 (0.166)    | -         |    23.00 | cryths, Darber, Goody, leaf, rud |
|           39 |     2406 | 2024-04-23 | Viperio              | L   | 0.957      | -            | -                | -                | -         |   -17.27 | Darber, Goody, leaf, rud, sSen   |
|           38 |     2442 | 2024-04-22 | JANO Esports         | W   | 0.951      | -            | -                | -                | -         |    11.74 | Darber, Goody, leaf, rud, sSen   |
|           37 |     3198 | 2024-04-10 | Illuminar Gaming     | L   | 0.869      | -            | -                | -                | -         |   -14.68 | Darber, Goody, leaf, msN, rud    |
|           36 |     3284 | 2024-04-08 | LOG Esports          | L   | 0.857      | -            | -                | -                | -         |   -23.01 | Darber, Goody, leaf, rud, Tree   |
|           35 |     3316 | 2024-04-08 | Johnny Speeds        | L   | 0.854      | -            | -                | -                | -         |    -8.80 | Darber, Goody, leaf, msN, rud    |
|           34 |     3400 | 2024-04-06 | DMS                  | L   | 0.842      | -            | -                | -                | -         |   -17.11 | Darber, Goody, leaf, msN, rud    |
|           33 |     3519 | 2024-04-04 | Sashi Esport         | W   | 0.828      | 0.333        | 0.024 (0.007)    | -                | -         |    10.00 | Darber, Goody, leaf, msN, rud    |
|           32 |     3681 | 2024-03-30 | Natus Vincere Junior | W   | 0.796      | 0.333        | 0.010 (0.003)    | -                | -         |    12.83 | Darber, Goody, leaf, nestee, rud |
|           31 |     3752 | 2024-03-28 | Passion UA           | W   | 0.782      | 0.333        | 0.057 (0.015)    | 1.000 (0.261)    | -         |    15.98 | Darber, Goody, leaf, nestee, rud |
|           30 |     3900 | 2024-03-26 | Sashi Esport         | W   | 0.769      | 0.333        | 0.024 (0.006)    | -                | -         |    11.12 | Darber, Goody, leaf, nestee, rud |
|           29 |     3954 | 2024-03-24 | Permitta Esports     | W   | 0.755      | 0.333        | 0.029 (0.007)    | 1.000 (0.252)    | -         |    16.49 | Darber, Goody, leaf, nestee, rud |
|           28 |     4184 | 2024-03-19 | Viperio              | W   | 0.722      | -            | -                | -                | -         |     6.60 | Darber, Goody, leaf, nestee, rud |
|           27 |     4388 | 2024-03-15 | ROSOMAHA             | W   | 0.696      | -            | -                | -                | -         |     4.85 | Darber, Goody, leaf, nestee, rud |
|           26 |     4715 | 2024-03-09 | FAVBET Team          | L   | 0.657      | -            | -                | -                | -         |    -8.29 | Darber, Goody, leaf, nestee, rud |
|           25 |     4755 | 2024-03-08 | AVEZ                 | W   | 0.650      | -            | -                | -                | -         |    10.00 | Darber, Goody, leaf, nestee, rud |
|           24 |     4809 | 2024-03-07 | BRUTE                | W   | 0.644      | -            | -                | -                | -         |     4.31 | Darber, Goody, leaf, nestee, rud |
|           23 |     4886 | 2024-03-06 | SINNERS Academy      | W   | 0.636      | -            | -                | -                | -         |     5.83 | Darber, Goody, leaf, nestee, rud |
|           22 |     5045 | 2024-03-04 | Begrip Gaming        | W   | 0.623      | -            | -                | -                | -         |     5.33 | Darber, Goody, leaf, nestee, rud |
|           21 |     5153 | 2024-03-02 | ARCRED               | L   | 0.611      | -            | -                | -                | -         |    -9.82 | Darber, Goody, leaf, nestee, rud |
|           20 |     5256 | 2024-02-29 | ex-KRC Genk Esports  | W   | 0.598      | -            | -                | -                | -         |     5.39 | aNdu, Darber, leaf, nestee, rud  |
|           19 |     5269 | 2024-02-29 | 0to100               | W   | 0.597      | -            | -                | -                | -         |     1.71 | aNdu, Darber, leaf, nestee, rud  |
|           18 |     5692 | 2024-02-21 | lajtbitexe           | W   | 0.544      | -            | -                | -                | -         |     4.26 | aNdu, Darber, leaf, nestee, rud  |
|           17 |     5837 | 2024-02-19 | UNiTY esports        | L   | 0.530      | -            | -                | -                | -         |    -6.06 | aNdu, Darber, leaf, nestee, rud  |
|           16 |     6037 | 2024-02-15 | BAKS Esports         | W   | 0.504      | -            | -                | -                | -         |     4.35 | Darber, Goody, leaf, nestee, rud |
|           15 |     6051 | 2024-02-15 | ex-K10               | L   | 0.503      | -            | -                | -                | -         |    -7.90 | Darber, Goody, leaf, nestee, rud |
|           14 |     6298 | 2024-02-09 | Kappa Bar            | L   | 0.464      | -            | -                | -                | -         |   -12.18 | Darber, leaf, nestee, rud, Trax  |
|           13 |     6334 | 2024-02-08 | Rhyno Esports        | L   | 0.457      | -            | -                | -                | -         |    -3.81 | aNdu, Darber, leaf, nestee, rud  |
|           12 |     6668 | 2024-02-01 | DASH                 | L   | 0.411      | -            | -                | -                | -         |    -8.86 | aNdu, Darber, leaf, nestee, rud  |
|           11 |     6706 | 2024-01-31 | ALTERNATE aTTaX      | W   | 0.404      | -            | -                | -                | -         |     4.83 | aNdu, Darber, leaf, nestee, rud  |
|           10 |     6716 | 2024-01-31 | RUBY                 | L   | 0.404      | -            | -                | -                | -         |    -4.60 | aNdu, Darber, leaf, nestee, rud  |
|            9 |     7039 | 2024-01-26 | Nexus Gaming         | L   | 0.370      | -            | -                | -                | -         |    -4.08 | aNdu, Darber, leaf, nestee, rud  |
|            8 |     7082 | 2024-01-25 | Natus Vincere Junior | L   | 0.364      | -            | -                | -                | -         |    -6.88 | aNdu, Darber, leaf, nestee, rud  |
|            7 |     7176 | 2024-01-23 | Apeks Rebels         | W   | 0.351      | -            | -                | -                | -         |     1.68 | aNdu, Darber, leaf, nestee, rud  |
|            6 |     8969 | 2023-12-10 | Sashi Esport         | L   | 0.057      | -            | -                | -                | -         |    -1.49 | aNdu, Darber, leaf, nestee, rud  |
|            5 |     9100 | 2023-12-08 | Monte Gen            | L   | 0.044      | -            | -                | -                | -         |    -0.82 | aNdu, Darber, leaf, nestee, rud  |
|            4 |     9216 | 2023-12-06 | Nexus Gaming         | L   | 0.031      | -            | -                | -                | -         |    -0.36 | aNdu, Darber, leaf, nestee, rud  |
|            3 |     9231 | 2023-12-06 | Begrip Gaming        | W   | 0.030      | -            | -                | -                | -         |     0.21 | aNdu, Darber, leaf, nestee, rud  |
|            2 |     9335 | 2023-12-04 | Team LRP Poland      | W   | 0.018      | -            | -                | -                | -         |     0.19 | aNdu, Darber, leaf, nestee, rud  |
|            1 |     9484 | 2023-12-02 | Preasy Esport        | W   | 0.003      | -            | -                | -                | -         |     0.06 | aNdu, Darber, leaf, nestee, rud  |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($5,475.83)
- Divide that value by the 5th highest value among all rosters ($300,806.11)
- The final value (0.02) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-03-30 |      0.796 | $6,000.00      | $4,775.00       |
| 2024-03-09 |      0.657 | $1,000.00      | $656.67         |
| 2023-12-08 |      0.044 | $1,000.00      | $44.17          |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
