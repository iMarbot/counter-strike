### Roster Details<br />
Team Name: HAVU Gaming<br />
Roster: airax, jelo, ottoNd, puuha, uli<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [221](../standings_global.md)<br />
Regional Rank: [148]( ../standings_europe.md)<br />
Final Rank Value:  707.8<br />
<br />
Final Rank Value (707.8) = Starting Rank Value (763.2) + Head To Head Adjustments (-55.4)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.290[<sup>1</sup>](#table2)
- Bounty Collected: 0.283[<sup>2</sup>](#table1)
- Opponent Network: 0.081[<sup>2</sup>](#table1)
- LAN Wins: 0.060[<sup>2</sup>](#table1)

The average of these factors is 0.178<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 763.2
- 400 + ( ( 0.178 - 0.000 ) / ( 0.786 - 0.000 ) ) * 1600 = 763.2


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
|           35 |     1774 | 2024-05-05 | RUBY                | L   | 1.000      | -            | -                | -                | -         |    -7.38 | airax, jelo, ottoNd, puuha, uli  |
|           34 |     1818 | 2024-05-04 | RUSH B              | L   | 1.000      | -            | -                | -                | -         |   -11.05 | airax, jelo, ottoNd, puuha, uli  |
|           33 |     1919 | 2024-05-02 | Gaimin Gladiators   | L   | 1.000      | -            | -                | -                | -         |    -2.47 | airax, jelo, ottoNd, puuha, uli  |
|           32 |     1937 | 2024-05-02 | Zero Tenacity       | L   | 1.000      | -            | -                | -                | -         |    -5.12 | airax, jelo, ottoNd, puuha, uli  |
|           31 |     2037 | 2024-04-30 | EYEBALLERS          | W   | 1.000      | 0.384        | 0.012 (0.005)    | 0.508 (0.195)    | 0 (0.000) |    24.48 | airax, jelo, ottoNd, puuha, uli  |
|           30 |     2078 | 2024-04-29 | Insilio             | W   | 0.996      | 0.435        | 0.010 (0.004)    | 0.717 (0.310)    | 0 (0.000) |    25.83 | airax, jelo, ottoNd, puuha, uli  |
|           29 |     2305 | 2024-04-25 | EYEBALLERS          | L   | 0.970      | -            | -                | -                | -         |    -6.35 | airax, jelo, ottoNd, puuha, uli  |
|           28 |     2331 | 2024-04-25 | kONO.ECF            | L   | 0.968      | -            | -                | -                | -         |    -6.94 | airax, jelo, ottoNd, puuha, uli  |
|           27 |     2424 | 2024-04-23 | 1win                | L   | 0.956      | -            | -                | -                | -         |    -4.39 | airax, jelo, ottoNd, puuha, uli  |
|           26 |     2466 | 2024-04-22 | SINNERS Esports     | L   | 0.949      | -            | -                | -                | -         |    -4.58 | airax, jelo, ottoNd, puuha, uli  |
|           25 |     2584 | 2024-04-20 | JANO Esports        | L   | 0.936      | -            | -                | -                | -         |   -13.15 | airax, jelo, ottoNd, puuha, uli  |
|           24 |     2720 | 2024-04-19 | B8                  | L   | 0.929      | -            | -                | -                | -         |    -3.46 | airax, jelo, ottoNd, puuha, uli  |
|           23 |     2783 | 2024-04-18 | ALTERNATE aTTaX     | W   | 0.922      | 0.384        | 0.052 (0.018)    | 0.679 (0.241)    | 0 (0.000) |    22.57 | airax, jelo, ottoNd, puuha, uli  |
|           22 |     2836 | 2024-04-17 | PARIVISION          | L   | 0.917      | -            | -                | -                | -         |    -7.74 | airax, jelo, ottoNd, puuha, uli  |
|           21 |     2961 | 2024-04-15 | Alliance            | L   | 0.902      | -            | -                | -                | -         |    -8.29 | airax, jelo, ottoNd, puuha, uli  |
|           20 |     3046 | 2024-04-13 | jefet               | L   | 0.889      | -            | -                | -                | -         |   -16.55 | airax, jelo, ottoNd, puuha, uli  |
|           19 |     3260 | 2024-04-09 | BLEED Esports       | L   | 0.862      | -            | -                | -                | -         |    -2.02 | airax, jelo, ottoNd, puuha, uli  |
|           18 |     3304 | 2024-04-08 | Permitta Esports    | L   | 0.856      | -            | -                | -                | -         |    -7.16 | airax, jelo, ottoNd, puuha, uli  |
|           17 |     3512 | 2024-04-04 | Passion UA          | L   | 0.829      | -            | -                | -                | -         |    -6.83 | airax, jelo, ottoNd, puuha, uli  |
|           16 |     4984 | 2024-03-04 | Betera Esports      | L   | 0.625      | -            | -                | -                | -         |    -7.19 | airax, Banjo, ottoNd, puuha, uli |
|           15 |     5001 | 2024-03-04 | M1X                 | W   | 0.625      | 0.143        | 0.000 (0.000)    | 0.066 (0.006)    | 0 (0.000) |     5.86 | airax, Banjo, ottoNd, puuha, uli |
|           14 |     5211 | 2024-03-02 | Sangal Esports      | L   | 0.609      | -            | -                | -                | -         |    -3.74 | airax, Banjo, ottoNd, puuha, uli |
|           13 |     5284 | 2024-02-29 | KOI                 | L   | 0.597      | -            | -                | -                | -         |    -3.73 | airax, Banjo, ottoNd, puuha, uli |
|           12 |     5293 | 2024-02-29 | Aurora Gaming       | L   | 0.595      | -            | -                | -                | -         |    -0.44 | airax, Banjo, ottoNd, puuha, uli |
|           11 |     5329 | 2024-02-28 | Team Spirit Academy | L   | 0.590      | -            | -                | -                | -         |    -8.32 | airax, Banjo, ottoNd, puuha, uli |
|           10 |     5504 | 2024-02-24 | ENCE Academy        | L   | 0.565      | -            | -                | -                | -         |    -7.31 | airax, Banjo, ottoNd, puuha, uli |
|            9 |     5539 | 2024-02-24 | RoundsGG            | W   | 0.563      | 0.143        | 0.000 (0.000)    | 0.202 (0.016)    | 1 (0.563) |     5.44 | airax, Banjo, ottoNd, puuha, uli |
|            8 |     6799 | 2024-01-29 | The Chosen Few      | L   | 0.392      | -            | -                | -                | -         |    -6.42 | airax, Banjo, ottoNd, sLowi, uli |
|            7 |     7865 | 2024-01-12 | Passion UA          | L   | 0.278      | -            | -                | -                | -         |    -1.89 | airax, Banjo, ottoNd, sLowi, uli |
|            6 |     7941 | 2024-01-11 | HEROIC              | L   | 0.270      | -            | -                | -                | -         |    -0.03 | airax, Banjo, ottoNd, sLowi, uli |
|            5 |     7989 | 2024-01-10 | TSM                 | W   | 0.265      | 0.143        | 0.011 (0.000)    | 0.146 (0.006)    | 0 (0.000) |     3.88 | airax, Banjo, ottoNd, sLowi, uli |
|            4 |     8001 | 2024-01-10 | HyperSpirit         | W   | 0.265      | 0.143        | 0.004 (0.000)    | 0.356 (0.013)    | 0 (0.000) |     4.04 | airax, Banjo, ottoNd, sLowi, uli |
|            3 |     8081 | 2024-01-09 | Fnatic              | L   | 0.257      | -            | -                | -                | -         |    -1.00 | airax, Banjo, ottoNd, sLowi, uli |
|            2 |     8095 | 2024-01-09 | Team Sampi          | W   | 0.257      | 0.143        | 0.039 (0.001)    | 0.665 (0.024)    | 0 (0.000) |     6.10 | airax, Banjo, ottoNd, sLowi, uli |
|            1 |     9470 | 2023-12-02 | FURIA Esports       | L   | 0.004      | -            | -                | -                | -         |    -0.00 | airax, Banjo, ottoNd, sLowi, uli |

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
