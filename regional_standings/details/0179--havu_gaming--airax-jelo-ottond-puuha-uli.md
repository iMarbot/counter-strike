### Roster Details<br />
Team Name: HAVU Gaming<br />
Roster: airax, jelo, ottoNd, puuha, uli<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [179](../standings_global.md)<br />
Regional Rank: [122]( ../standings_europe.md)<br />
Final Rank Value:  744.6<br />
<br />
Final Rank Value (744.6) = Starting Rank Value (859.4) + Head To Head Adjustments (-114.8)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.381[<sup>1</sup>](#table2)
- Bounty Collected: 0.333[<sup>2</sup>](#table1)
- Opponent Network: 0.100[<sup>2</sup>](#table1)
- LAN Wins: 0.113[<sup>2</sup>](#table1)

The average of these factors is 0.232<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 859.4
- 400 + ( ( 0.232 - 0.000 ) / ( 0.806 - 0.000 ) ) * 1600 = 859.4


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent              | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                           |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           36 |       22 | 2024-05-05 | RUBY                  | L   | 1.000      | -            | -                | -                | -         |    -8.11 | airax, jelo, ottoNd, puuha, uli  |
|           35 |       59 | 2024-05-04 | RUSH B (Russian team) | L   | 1.000      | -            | -                | -                | -         |   -11.70 | airax, jelo, ottoNd, puuha, uli  |
|           34 |      146 | 2024-05-02 | Gaimin Gladiators     | L   | 1.000      | -            | -                | -                | -         |    -2.01 | airax, jelo, ottoNd, puuha, uli  |
|           33 |      162 | 2024-05-02 | Zero Tenacity         | L   | 1.000      | -            | -                | -                | -         |    -6.58 | airax, jelo, ottoNd, puuha, uli  |
|           32 |      249 | 2024-04-30 | EYEBALLERS            | W   | 1.000      | 0.384        | 0.051 (0.020)    | 0.533 (0.205)    | 0 (0.000) |    23.20 | airax, jelo, ottoNd, puuha, uli  |
|           31 |      286 | 2024-04-29 | Insilio               | W   | 1.000      | 0.435        | 0.020 (0.009)    | 0.875 (0.380)    | 0 (0.000) |    24.68 | airax, jelo, ottoNd, puuha, uli  |
|           30 |      465 | 2024-04-25 | EYEBALLERS            | L   | 1.000      | -            | -                | -                | -         |    -7.92 | airax, jelo, ottoNd, puuha, uli  |
|           29 |      493 | 2024-04-25 | TBA.ECF               | L   | 1.000      | -            | -                | -                | -         |   -14.07 | airax, jelo, ottoNd, puuha, uli  |
|           28 |      581 | 2024-04-23 | 1win                  | L   | 1.000      | -            | -                | -                | -         |   -13.67 | airax, jelo, ottoNd, puuha, uli  |
|           27 |      618 | 2024-04-22 | SINNERS Esports       | L   | 1.000      | -            | -                | -                | -         |    -6.61 | airax, jelo, ottoNd, puuha, uli  |
|           26 |      717 | 2024-04-20 | JANO Esports          | L   | 1.000      | -            | -                | -                | -         |   -17.17 | airax, jelo, ottoNd, puuha, uli  |
|           25 |      841 | 2024-04-19 | B8                    | L   | 1.000      | -            | -                | -                | -         |    -8.05 | airax, jelo, ottoNd, puuha, uli  |
|           24 |      895 | 2024-04-18 | ALTERNATE aTTaX       | W   | 1.000      | 0.384        | 0.110 (0.042)    | 0.723 (0.278)    | 0 (0.000) |    22.02 | airax, jelo, ottoNd, puuha, uli  |
|           23 |      936 | 2024-04-17 | PARIVISION            | L   | 1.000      | -            | -                | -                | -         |   -12.74 | airax, jelo, ottoNd, puuha, uli  |
|           22 |     1054 | 2024-04-15 | Alliance              | L   | 1.000      | -            | -                | -                | -         |   -12.46 | airax, jelo, ottoNd, puuha, uli  |
|           21 |     1302 | 2024-04-09 | BLEED Esports         | L   | 1.000      | -            | -                | -                | -         |    -5.56 | airax, jelo, ottoNd, puuha, uli  |
|           20 |     1343 | 2024-04-08 | Permitta Esports      | L   | 1.000      | -            | -                | -                | -         |   -11.08 | airax, jelo, ottoNd, puuha, uli  |
|           19 |     1500 | 2024-04-04 | Passion UA            | L   | 0.991      | -            | -                | -                | -         |   -10.98 | airax, jelo, ottoNd, puuha, uli  |
|           18 |     2719 | 2024-03-04 | Betera Esports        | L   | 0.786      | -            | -                | -                | -         |   -11.23 | airax, Banjo, ottoNd, puuha, uli |
|           17 |     2733 | 2024-03-04 | M1X                   | W   | 0.786      | 0.143        | 0.002 (0.000)    | 0.097 (0.011)    | 0 (0.000) |     6.22 | airax, Banjo, ottoNd, puuha, uli |
|           16 |     2899 | 2024-03-02 | Sangal Esports        | L   | 0.770      | -            | -                | -                | -         |   -15.60 | airax, Banjo, ottoNd, puuha, uli |
|           15 |     2964 | 2024-02-29 | KOI                   | L   | 0.758      | -            | -                | -                | -         |    -4.70 | airax, Banjo, ottoNd, puuha, uli |
|           14 |     2970 | 2024-02-29 | Aurora Gaming         | L   | 0.756      | -            | -                | -                | -         |    -0.55 | airax, Banjo, ottoNd, puuha, uli |
|           13 |     2997 | 2024-02-28 | Team Spirit Academy   | L   | 0.751      | -            | -                | -                | -         |   -11.87 | airax, Banjo, ottoNd, puuha, uli |
|           12 |     3137 | 2024-02-24 | ENCE Academy          | L   | 0.726      | -            | -                | -                | -         |   -11.89 | airax, Banjo, ottoNd, puuha, uli |
|           11 |     3158 | 2024-02-24 | RoundsGG              | W   | 0.725      | 0.143        | 0.000 (0.000)    | 0.170 (0.018)    | 1 (0.725) |     7.24 | airax, Banjo, ottoNd, puuha, uli |
|           10 |     4172 | 2024-01-29 | The Chosen Few        | L   | 0.553      | -            | -                | -                | -         |   -10.72 | airax, Banjo, ottoNd, sLowi, uli |
|            9 |     4942 | 2024-01-12 | Passion UA            | L   | 0.439      | -            | -                | -                | -         |    -4.92 | airax, Banjo, ottoNd, sLowi, uli |
|            8 |     5001 | 2024-01-11 | HEROIC                | L   | 0.431      | -            | -                | -                | -         |    -0.13 | airax, Banjo, ottoNd, sLowi, uli |
|            7 |     5033 | 2024-01-10 | TSM                   | W   | 0.426      | 0.143        | 0.013 (0.001)    | 0.183 (0.011)    | 0 (0.000) |     4.02 | airax, Banjo, ottoNd, sLowi, uli |
|            6 |     5043 | 2024-01-10 | HyperSpirit           | W   | 0.426      | 0.143        | 0.009 (0.001)    | 0.293 (0.018)    | 0 (0.000) |     4.26 | airax, Banjo, ottoNd, sLowi, uli |
|            5 |     5086 | 2024-01-09 | Fnatic                | L   | 0.418      | -            | -                | -                | -         |    -1.83 | airax, Banjo, ottoNd, sLowi, uli |
|            4 |     5098 | 2024-01-09 | Team Sampi            | W   | 0.418      | 0.143        | 0.108 (0.006)    | 0.709 (0.042)    | 0 (0.000) |     9.55 | airax, Banjo, ottoNd, sLowi, uli |
|            3 |     6107 | 2023-12-02 | FURIA Esports         | L   | 0.165      | -            | -                | -                | -         |    -0.06 | airax, Banjo, ottoNd, sLowi, uli |
|            2 |     6272 | 2023-11-29 | GamerLegion           | W   | 0.144      | 0.589        | 0.194 (0.016)    | 0.419 (0.036)    | 1 (0.144) |     4.47 | airax, Banjo, ottoNd, sLowi, uli |
|            1 |     6280 | 2023-11-29 | ENCE                  | W   | 0.143      | 0.589        | 0.041 (0.003)    | 0.011 (0.001)    | 1 (0.143) |     1.75 | airax, Banjo, ottoNd, sLowi, uli |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($3,745.45)
- Divide that value by the 5th highest value among all rosters ($158,437.64)
- The final value (0.02) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-02-24 |      0.726 | $1,625.05      | $1,179.48       |
| 2023-12-03 |      0.171 | $15,000.00     | $2,565.97       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
