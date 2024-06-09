### Roster Details<br />
Team Name: VaselineWorms<br />
Roster: aliot, kashl1d, relaxxie, Twizell, XeeDo<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [191](../standings_global.md)<br />
Regional Rank: [130]( ../standings_europe.md)<br />
Final Rank Value:  731.7<br />
<br />
Final Rank Value (731.7) = Starting Rank Value (721.3) + Head To Head Adjustments (10.4)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.230[<sup>1</sup>](#table2)
- Bounty Collected: 0.255[<sup>2</sup>](#table1)
- Opponent Network: 0.148[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.158<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 721.3
- 400 + ( ( 0.158 - 0.000 ) / ( 0.787 - 0.000 ) ) * 1600 = 721.3


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent             | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                     |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           44 |       80 | 2024-05-29 | RUSH B               | L   | 1.000      | -            | -                | -                | -         |   -10.01 | aliot, kashl1d, relaxxie, Twizell, XeeDo   |
|           43 |      265 | 2024-05-25 | Team PeeP            | L   | 1.000      | -            | -                | -                | -         |   -19.83 | aliot, kashl1d, relaxxie, Twizell, zweih   |
|           42 |      273 | 2024-05-25 | Eternal Fire Academy | W   | 1.000      | -            | -                | -                | 0 (0.000) |     7.66 | aliot, kashl1d, relaxxie, Twizell, zweih   |
|           41 |      346 | 2024-05-24 | Verdant              | L   | 1.000      | -            | -                | -                | -         |    -8.89 | aliot, kashl1d, relaxxie, Twizell, zweih   |
|           40 |      357 | 2024-05-24 | polizej              | W   | 1.000      | -            | -                | -                | 0 (0.000) |     6.95 | aliot, kashl1d, relaxxie, Twizell, XeeDo   |
|           39 |      366 | 2024-05-24 | team reNIK           | W   | 1.000      | -            | -                | -                | 0 (0.000) |     3.78 | aliot, kashl1d, relaxxie, Twizell, XeeDo   |
|           38 |      475 | 2024-05-22 | WOPA Esport          | W   | 1.000      | 0.372        | 0.003 (0.001)    | 0.594 (0.221)    | 0 (0.000) |    15.06 | aliot, kashl1d, relaxxie, Twizell, zweih   |
|           37 |      484 | 2024-05-22 | Denial               | W   | 1.000      | 0.372        | -                | 0.138 (0.051)    | 0 (0.000) |    11.50 | aliot, kashl1d, relaxxie, Twizell, zweih   |
|           36 |      758 | 2024-05-19 | Nexus Gaming         | W   | 1.000      | 0.372        | 0.003 (0.001)    | 0.857 (0.319)    | 0 (0.000) |    21.46 | aliot, kashl1d, relaxxie, Twizell, zweih   |
|           35 |      999 | 2024-05-17 | 1win Academy         | L   | 1.000      | -            | -                | -                | -         |   -19.90 | aliot, kashl1d, relaxxie, Twizell, zweih   |
|           34 |     1147 | 2024-05-15 | ARROW                | W   | 1.000      | 0.372        | 0.002 (0.001)    | 0.344 (0.128)    | 0 (0.000) |    16.10 | aliot, kashl1d, relaxxie, Twizell, zweih   |
|           33 |     1271 | 2024-05-14 | ex-K10               | W   | 1.000      | 0.372        | 0.005 (0.002)    | 0.517 (0.193)    | 0 (0.000) |    18.69 | aliot, kashl1d, relaxxie, Twizell, zweih   |
|           32 |     1375 | 2024-05-12 | LEON Esports         | W   | 1.000      | 0.143        | 0.001 (0.000)    | 0.564 (0.081)    | 0 (0.000) |    17.14 | aliot, kashl1d, relaxxie, Twizell, zweih   |
|           31 |     1438 | 2024-05-11 | Team QUAZAR          | W   | 1.000      | -            | -                | -                | 0 (0.000) |     5.62 | aliot, kashl1d, relaxxie, Twizell, zweih   |
|           30 |     1644 | 2024-05-08 | JANO Esports         | W   | 1.000      | 0.372        | 0.003 (0.001)    | 0.419 (0.156)    | -         |    17.88 | aliot, kashl1d, relaxxie, Twizell, zweih   |
|           29 |     1755 | 2024-05-06 | Soda Gaming          | L   | 1.000      | -            | -                | -                | -         |   -17.58 | aliot, kashl1d, relaxxie, Twizell, zweih   |
|           28 |     1996 | 2024-05-01 | Aurora Young Blud    | W   | 1.000      | 0.372        | 0.008 (0.003)    | 0.506 (0.188)    | -         |    21.28 | aliot, kashl1d, relaxxie, Twizell, zweih   |
|           27 |     2352 | 2024-04-25 | Lemondogs            | L   | 0.970      | -            | -                | -                | -         |   -17.60 | aliot, kashl1d, relaxxie, Twizell, zweih   |
|           26 |     2824 | 2024-04-18 | Rustec               | L   | 0.923      | -            | -                | -                | -         |    -8.53 | aliot, kashl1d, relaxxie, Twizell, zweih   |
|           25 |     3260 | 2024-04-10 | GenOne               | L   | 0.869      | -            | -                | -                | -         |   -14.54 | aliot, kashl1d, relaxxie, Twizell, zweih   |
|           24 |     5427 | 2024-02-29 | Golden Sword         | W   | 0.597      | -            | -                | -                | -         |     2.87 | aliot, kashl1d, Muk0s, relaxxie, zweih     |
|           23 |     5614 | 2024-02-25 | 1win                 | L   | 0.570      | -            | -                | -                | -         |    -3.23 | aliot, kashl1d, Muk0s, relaxxie, zweih     |
|           22 |     5876 | 2024-02-21 | GUN5 Esports         | L   | 0.544      | -            | -                | -                | -         |   -10.04 | aliot, kashl1d, Muk0s, relaxxie, zweih     |
|           21 |     5889 | 2024-02-21 | ILIN                 | L   | 0.543      | -            | -                | -                | -         |   -11.35 | aliot, kashl1d, Muk0s, relaxxie, zweih     |
|           20 |     6008 | 2024-02-19 | RoundsGG             | W   | 0.530      | -            | -                | -                | -         |     6.43 | aliot, kashl1d, Muk0s, relaxxie, zweih     |
|           19 |     6029 | 2024-02-18 | unluckyday           | L   | 0.525      | -            | -                | -                | -         |    -9.35 | aliot, kashl1d, Muk0s, relaxxie, zweih     |
|           18 |     6034 | 2024-02-18 | Cerberus eSports     | W   | 0.525      | 0.284        | 0.000 (0.000)    | -                | -         |     4.04 | aliot, kashl1d, Muk0s, relaxxie, zweih     |
|           17 |     6161 | 2024-02-16 | FORZE Youngsters     | L   | 0.510      | -            | -                | -                | -         |    -8.72 | boN11, kelieN, matusik, spirit, sstiNiX    |
|           16 |     6220 | 2024-02-15 | ALTERNATE aTTaX      | L   | 0.504      | -            | -                | -                | -         |    -3.15 | aliot, kashl1d, Muk0s, relaxxie, zweih     |
|           15 |     6377 | 2024-02-12 | Lemondogs            | W   | 0.484      | 0.371        | -                | 0.314 (0.056)    | -         |     5.22 | aliot, kashl1d, Muk0s, relaxxie, zweih     |
|           14 |     6626 | 2024-02-05 | esmagaB              | L   | 0.437      | -            | -                | -                | -         |    -4.41 | Ag1l, aragornN, NOPEEj, pr, rafaxF         |
|           13 |     7037 | 2024-01-29 | Team Spirit Academy  | L   | 0.392      | -            | -                | -                | -         |    -5.74 | alpha, baz, keegaN, Magnojez, notineki     |
|           12 |     7276 | 2024-01-26 | Nexus Gaming         | L   | 0.370      | -            | -                | -                | -         |    -2.86 | aliot, kashl1d, Muk0s, relaxxie, zweih     |
|           11 |     7310 | 2024-01-25 | Gaimin Gladiators    | L   | 0.364      | -            | -                | -                | -         |    -0.51 | kraghen, Nodios, Patti, Queenix, salazar   |
|           10 |     7723 | 2024-01-18 | GamerLegion Academy  | W   | 0.317      | 0.371        | 0.018 (0.002)    | 0.691 (0.081)    | -         |     6.61 | aliot, kashl1d, Muk0s, relaxxie, zweih     |
|            9 |     7781 | 2024-01-17 | GUN5 Esports         | L   | 0.311      | -            | -                | -                | -         |    -7.14 | FinigaN, lov1kus, supra, xiELO, znxxX      |
|            8 |     7813 | 2024-01-17 | 00 Nation            | W   | 0.311      | -            | -                | -                | -         |     2.19 | aliot, kashl1d, Muk0s, relaxxie, zweih     |
|            7 |     8671 | 2023-12-18 | LF0                  | W   | 0.110      | -            | -                | -                | -         |     1.24 | aliot, kashl1d, Muk0s, relaxxie, zweih     |
|            6 |     8678 | 2023-12-18 | TOR                  | W   | 0.109      | 0.143        | 0.014 (0.000)    | -                | -         |     2.15 | aliot, kashl1d, Muk0s, relaxxie, zweih     |
|            5 |     8741 | 2023-12-17 | Donstu Esports       | W   | 0.103      | -            | -                | -                | -         |     0.82 | aliot, kashl1d, Muk0s, relaxxie, zweih     |
|            4 |     8766 | 2023-12-17 | BAKS Esports         | W   | 0.102      | -            | -                | -                | -         |     1.21 | datet, elocurse, Middlesex, reyoz, twizell |
|            3 |     8905 | 2023-12-16 | VP.Prodigy           | L   | 0.095      | -            | -                | -                | -         |    -0.99 | aliot, kashl1d, Muk0s, relaxxie, zweih     |
|            2 |     9506 | 2023-12-06 | TY                   | L   | 0.031      | -            | -                | -                | -         |    -0.57 | aliot, kashl1d, Muk0s, relaxxie, zweih     |
|            1 |     9579 | 2023-12-05 | TUSTE CHOPAKI        | L   | 0.024      | -            | -                | -                | -         |    -0.60 | aliot, kashl1d, Muk0s, relaxxie, zweih     |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($134.17)
- Divide that value by the 5th highest value among all rosters ($300,806.11)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
