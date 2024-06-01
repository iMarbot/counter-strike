### Roster Details<br />
Team Name: VaselineWorms<br />
Roster: aliot, kashl1d, relaxxie, Twizell, XeeDo<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [189](../standings_global.md)<br />
Regional Rank: [128]( ../standings_europe.md)<br />
Final Rank Value:  738.9<br />
<br />
Final Rank Value (738.9) = Starting Rank Value (717.9) + Head To Head Adjustments (20.9)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.230[<sup>1</sup>](#table2)
- Bounty Collected: 0.259[<sup>2</sup>](#table1)
- Opponent Network: 0.136[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.156<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 717.9
- 400 + ( ( 0.156 - 0.000 ) / ( 0.786 - 0.000 ) ) * 1600 = 717.9


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
|           38 |       75 | 2024-05-29 | RUSH B               | L   | 1.000      | -            | -                | -                | -         |   -10.57 | aliot, kashl1d, relaxxie, Twizell, XeeDo   |
|           37 |      122 | 2024-05-28 | 5goblinz             | W   | 1.000      | -            | -                | -                | 0 (0.000) |     6.14 | aliot, kashl1d, relaxxie, Twizell, XeeDo   |
|           36 |      257 | 2024-05-25 | Team PeeP            | L   | 1.000      | -            | -                | -                | -         |   -19.96 | aliot, kashl1d, relaxxie, Twizell, zweih   |
|           35 |      265 | 2024-05-25 | Eternal Fire Academy | W   | 1.000      | 0.372        | -                | 0.136 (0.051)    | 0 (0.000) |     7.64 | aliot, kashl1d, relaxxie, Twizell, zweih   |
|           34 |      337 | 2024-05-24 | Verdant              | L   | 1.000      | -            | -                | -                | -         |    -9.16 | aliot, kashl1d, relaxxie, Twizell, zweih   |
|           33 |      348 | 2024-05-24 | polizej              | W   | 1.000      | -            | -                | -                | 0 (0.000) |     6.88 | aliot, kashl1d, relaxxie, Twizell, XeeDo   |
|           32 |      357 | 2024-05-24 | team reNIK           | W   | 1.000      | -            | -                | -                | 0 (0.000) |     3.74 | aliot, kashl1d, relaxxie, Twizell, XeeDo   |
|           31 |      469 | 2024-05-22 | WOPA Esport          | W   | 1.000      | 0.372        | 0.003 (0.001)    | 0.594 (0.221)    | 0 (0.000) |    15.60 | aliot, kashl1d, relaxxie, Twizell, zweih   |
|           30 |      478 | 2024-05-22 | Denial               | W   | 1.000      | 0.372        | -                | 0.138 (0.051)    | 0 (0.000) |    11.50 | aliot, kashl1d, relaxxie, Twizell, zweih   |
|           29 |      746 | 2024-05-19 | Nexus Gaming         | W   | 1.000      | 0.372        | 0.014 (0.005)    | 0.825 (0.307)    | 0 (0.000) |    21.64 | aliot, kashl1d, relaxxie, Twizell, zweih   |
|           28 |      987 | 2024-05-17 | 1win Academy         | L   | 1.000      | -            | -                | -                | -         |   -19.93 | aliot, kashl1d, relaxxie, Twizell, zweih   |
|           27 |     1138 | 2024-05-15 | ARROW                | W   | 1.000      | 0.372        | 0.002 (0.001)    | 0.344 (0.128)    | 0 (0.000) |    16.93 | aliot, kashl1d, relaxxie, Twizell, zweih   |
|           26 |     1261 | 2024-05-14 | ex-K10               | W   | 1.000      | 0.372        | 0.005 (0.002)    | 0.382 (0.142)    | 0 (0.000) |    18.89 | aliot, kashl1d, relaxxie, Twizell, zweih   |
|           25 |     1362 | 2024-05-12 | LEON Esports         | W   | 1.000      | 0.143        | 0.001 (0.000)    | 0.564 (0.081)    | 0 (0.000) |    16.89 | aliot, kashl1d, relaxxie, Twizell, zweih   |
|           24 |     1425 | 2024-05-11 | Team QUAZAR          | W   | 1.000      | -            | -                | -                | -         |     5.61 | aliot, kashl1d, relaxxie, Twizell, zweih   |
|           23 |     1627 | 2024-05-08 | JANO Esports         | W   | 1.000      | 0.372        | 0.003 (0.001)    | 0.392 (0.146)    | -         |    17.25 | aliot, kashl1d, relaxxie, Twizell, zweih   |
|           22 |     1732 | 2024-05-06 | Soda Gaming          | L   | 1.000      | -            | -                | -                | -         |   -18.33 | aliot, kashl1d, relaxxie, Twizell, zweih   |
|           21 |     1969 | 2024-05-01 | Aurora Young Blud    | W   | 1.000      | 0.372        | 0.008 (0.003)    | 0.506 (0.188)    | -         |    21.02 | aliot, kashl1d, relaxxie, Twizell, zweih   |
|           20 |     2313 | 2024-04-25 | Lemondogs            | L   | 0.970      | -            | -                | -                | -         |   -17.45 | aliot, kashl1d, relaxxie, Twizell, zweih   |
|           19 |     2768 | 2024-04-18 | Rustec               | L   | 0.923      | -            | -                | -                | -         |    -9.43 | aliot, kashl1d, relaxxie, Twizell, zweih   |
|           18 |     3185 | 2024-04-10 | GenOne               | L   | 0.869      | -            | -                | -                | -         |   -14.80 | aliot, kashl1d, relaxxie, Twizell, zweih   |
|           17 |     5277 | 2024-02-29 | Golden Sword         | W   | 0.597      | -            | -                | -                | -         |     2.81 | aliot, kashl1d, Muk0s, relaxxie, zweih     |
|           16 |     5456 | 2024-02-25 | 1win                 | L   | 0.570      | -            | -                | -                | -         |    -3.10 | aliot, kashl1d, Muk0s, relaxxie, zweih     |
|           15 |     5713 | 2024-02-21 | GUN5 Esports         | L   | 0.544      | -            | -                | -                | -         |   -10.12 | aliot, kashl1d, Muk0s, relaxxie, zweih     |
|           14 |     5725 | 2024-02-21 | ILIN                 | L   | 0.543      | -            | -                | -                | -         |   -11.78 | aliot, kashl1d, Muk0s, relaxxie, zweih     |
|           13 |     5836 | 2024-02-19 | RoundsGG             | W   | 0.530      | 0.371        | -                | 0.202 (0.040)    | -         |     5.82 | aliot, kashl1d, Muk0s, relaxxie, zweih     |
|           12 |     5857 | 2024-02-18 | unluckyday           | L   | 0.525      | -            | -                | -                | -         |    -9.46 | aliot, kashl1d, Muk0s, relaxxie, zweih     |
|           11 |     5862 | 2024-02-18 | Cerberus eSports     | W   | 0.525      | 0.284        | 0.000 (0.000)    | -                | -         |     3.97 | aliot, kashl1d, Muk0s, relaxxie, zweih     |
|           10 |     6821 | 2024-01-29 | Team Spirit Academy  | L   | 0.392      | -            | -                | -                | -         |    -5.66 | alpha, baz, keegaN, Magnojez, notineki     |
|            9 |     7532 | 2024-01-17 | GUN5 Esports         | L   | 0.311      | -            | -                | -                | -         |    -7.14 | FinigaN, lov1kus, supra, xiELO, znxxX      |
|            8 |     7564 | 2024-01-17 | 00 Nation            | W   | 0.311      | -            | -                | -                | -         |     2.21 | aliot, kashl1d, Muk0s, relaxxie, zweih     |
|            7 |     8414 | 2023-12-18 | LF0                  | W   | 0.110      | -            | -                | -                | -         |     1.25 | aliot, kashl1d, Muk0s, relaxxie, zweih     |
|            6 |     8421 | 2023-12-18 | TOR                  | W   | 0.109      | 0.143        | 0.014 (0.000)    | -                | -         |     2.16 | aliot, kashl1d, Muk0s, relaxxie, zweih     |
|            5 |     8481 | 2023-12-17 | Donstu Esports       | W   | 0.103      | -            | -                | -                | -         |     0.83 | aliot, kashl1d, Muk0s, relaxxie, zweih     |
|            4 |     8506 | 2023-12-17 | BAKS Esports         | W   | 0.102      | 0.143        | 0.001 (0.000)    | -                | -         |     1.22 | datet, elocurse, Middlesex, reyoz, twizell |
|            3 |     8644 | 2023-12-16 | VP.Prodigy           | L   | 0.095      | -            | -                | -                | -         |    -1.01 | aliot, kashl1d, Muk0s, relaxxie, zweih     |
|            2 |     9225 | 2023-12-06 | TY                   | L   | 0.031      | -            | -                | -                | -         |    -0.57 | aliot, kashl1d, Muk0s, relaxxie, zweih     |
|            1 |     9297 | 2023-12-05 | TUSTE CHOPAKI        | L   | 0.024      | -            | -                | -                | -         |    -0.60 | aliot, kashl1d, Muk0s, relaxxie, zweih     |

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
