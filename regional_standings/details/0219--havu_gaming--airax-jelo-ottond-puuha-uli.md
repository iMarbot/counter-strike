### Roster Details<br />
Team Name: HAVU Gaming<br />
Roster: airax, jelo, ottoNd, puuha, uli<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [219](../standings_global.md)<br />
Regional Rank: [148]( ../standings_europe.md)<br />
Final Rank Value:  708.4<br />
<br />
Final Rank Value (708.4) = Starting Rank Value (763.2) + Head To Head Adjustments (-54.9)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.290[<sup>1</sup>](#table2)
- Bounty Collected: 0.282[<sup>2</sup>](#table1)
- Opponent Network: 0.084[<sup>2</sup>](#table1)
- LAN Wins: 0.060[<sup>2</sup>](#table1)

The average of these factors is 0.179<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 763.2
- 400 + ( ( 0.179 - 0.000 ) / ( 0.787 - 0.000 ) ) * 1600 = 763.2


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent            | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                           |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           35 |     1797 | 2024-05-05 | RUBY                | L   | 1.000      | -            | -                | -                | -         |    -7.29 | airax, jelo, ottoNd, puuha, uli  |
|           34 |     1841 | 2024-05-04 | RUSH B              | L   | 1.000      | -            | -                | -                | -         |   -10.73 | airax, jelo, ottoNd, puuha, uli  |
|           33 |     1946 | 2024-05-02 | Gaimin Gladiators   | L   | 1.000      | -            | -                | -                | -         |    -2.43 | airax, jelo, ottoNd, puuha, uli  |
|           32 |     1964 | 2024-05-02 | Zero Tenacity       | L   | 1.000      | -            | -                | -                | -         |    -5.01 | airax, jelo, ottoNd, puuha, uli  |
|           31 |     2070 | 2024-04-30 | EYEBALLERS          | W   | 1.000      | 0.384        | 0.012 (0.005)    | 0.508 (0.195)    | 0 (0.000) |    24.03 | airax, jelo, ottoNd, puuha, uli  |
|           30 |     2113 | 2024-04-29 | Insilio             | W   | 0.996      | 0.435        | 0.007 (0.003)    | 0.717 (0.310)    | 0 (0.000) |    25.85 | airax, jelo, ottoNd, puuha, uli  |
|           29 |     2342 | 2024-04-25 | EYEBALLERS          | L   | 0.970      | -            | -                | -                | -         |    -6.84 | airax, jelo, ottoNd, puuha, uli  |
|           28 |     2372 | 2024-04-25 | kONO.ECF            | L   | 0.968      | -            | -                | -                | -         |    -6.76 | airax, jelo, ottoNd, puuha, uli  |
|           27 |     2472 | 2024-04-23 | 1win                | L   | 0.956      | -            | -                | -                | -         |    -4.60 | airax, jelo, ottoNd, puuha, uli  |
|           26 |     2518 | 2024-04-22 | SINNERS Esports     | L   | 0.949      | -            | -                | -                | -         |    -3.99 | airax, jelo, ottoNd, puuha, uli  |
|           25 |     2638 | 2024-04-20 | JANO Esports        | L   | 0.936      | -            | -                | -                | -         |   -13.10 | airax, jelo, ottoNd, puuha, uli  |
|           24 |     2776 | 2024-04-19 | B8                  | L   | 0.929      | -            | -                | -                | -         |    -3.82 | airax, jelo, ottoNd, puuha, uli  |
|           23 |     2839 | 2024-04-18 | ALTERNATE aTTaX     | W   | 0.922      | 0.384        | 0.052 (0.019)    | 0.735 (0.261)    | 0 (0.000) |    22.35 | airax, jelo, ottoNd, puuha, uli  |
|           22 |     2893 | 2024-04-17 | PARIVISION          | L   | 0.917      | -            | -                | -                | -         |    -7.95 | airax, jelo, ottoNd, puuha, uli  |
|           21 |     3025 | 2024-04-15 | Alliance            | L   | 0.902      | -            | -                | -                | -         |    -8.37 | airax, jelo, ottoNd, puuha, uli  |
|           20 |     3112 | 2024-04-13 | jefet               | L   | 0.889      | -            | -                | -                | -         |   -16.61 | airax, jelo, ottoNd, puuha, uli  |
|           19 |     3339 | 2024-04-09 | BLEED Esports       | L   | 0.862      | -            | -                | -                | -         |    -2.12 | airax, jelo, ottoNd, puuha, uli  |
|           18 |     3385 | 2024-04-08 | Permitta Esports    | L   | 0.856      | -            | -                | -                | -         |    -6.85 | airax, jelo, ottoNd, puuha, uli  |
|           17 |     3598 | 2024-04-04 | Passion UA          | L   | 0.829      | -            | -                | -                | -         |    -6.72 | airax, jelo, ottoNd, puuha, uli  |
|           16 |     5130 | 2024-03-04 | Betera Esports      | L   | 0.625      | -            | -                | -                | -         |    -7.13 | airax, Banjo, ottoNd, puuha, uli |
|           15 |     5147 | 2024-03-04 | M1X                 | W   | 0.625      | 0.143        | 0.000 (0.000)    | 0.066 (0.006)    | 0 (0.000) |     5.83 | airax, Banjo, ottoNd, puuha, uli |
|           14 |     5360 | 2024-03-02 | Sangal Esports      | L   | 0.609      | -            | -                | -                | -         |    -3.42 | airax, Banjo, ottoNd, puuha, uli |
|           13 |     5434 | 2024-02-29 | KOI                 | L   | 0.597      | -            | -                | -                | -         |    -3.66 | airax, Banjo, ottoNd, puuha, uli |
|           12 |     5443 | 2024-02-29 | Aurora Gaming       | L   | 0.595      | -            | -                | -                | -         |    -0.47 | airax, Banjo, ottoNd, puuha, uli |
|           11 |     5480 | 2024-02-28 | Team Spirit Academy | L   | 0.590      | -            | -                | -                | -         |    -8.24 | airax, Banjo, ottoNd, puuha, uli |
|           10 |     5664 | 2024-02-24 | ENCE Academy        | L   | 0.565      | -            | -                | -                | -         |    -7.28 | airax, Banjo, ottoNd, puuha, uli |
|            9 |     5699 | 2024-02-24 | RoundsGG            | W   | 0.563      | 0.143        | 0.000 (0.000)    | 0.251 (0.020)    | 1 (0.563) |     5.91 | airax, Banjo, ottoNd, puuha, uli |
|            8 |     7015 | 2024-01-29 | The Chosen Few      | L   | 0.392      | -            | -                | -                | -         |    -6.79 | airax, Banjo, ottoNd, sLowi, uli |
|            7 |     8118 | 2024-01-12 | Passion UA          | L   | 0.278      | -            | -                | -                | -         |    -1.82 | airax, Banjo, ottoNd, sLowi, uli |
|            6 |     8194 | 2024-01-11 | HEROIC              | L   | 0.270      | -            | -                | -                | -         |    -0.03 | airax, Banjo, ottoNd, sLowi, uli |
|            5 |     8243 | 2024-01-10 | TSM                 | W   | 0.265      | 0.143        | 0.011 (0.000)    | 0.170 (0.006)    | 0 (0.000) |     4.09 | airax, Banjo, ottoNd, sLowi, uli |
|            4 |     8255 | 2024-01-10 | HyperSpirit         | W   | 0.265      | 0.143        | 0.004 (0.000)    | 0.356 (0.013)    | 0 (0.000) |     4.01 | airax, Banjo, ottoNd, sLowi, uli |
|            3 |     8335 | 2024-01-09 | Fnatic              | L   | 0.257      | -            | -                | -                | -         |    -1.00 | airax, Banjo, ottoNd, sLowi, uli |
|            2 |     8349 | 2024-01-09 | Team Sampi          | W   | 0.257      | 0.143        | 0.039 (0.001)    | 0.677 (0.025)    | 0 (0.000) |     6.11 | airax, Banjo, ottoNd, sLowi, uli |
|            1 |     9752 | 2023-12-02 | FURIA Esports       | L   | 0.004      | -            | -                | -                | -         |    -0.00 | airax, Banjo, ottoNd, sLowi, uli |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($1,067.74)
- Divide that value by the 5th highest value among all rosters ($300,806.11)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-02-24 |      0.565 | $1,625.05      | $917.74         |
| 2023-12-03 |      0.010 | $15,000.00     | $150.00         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
