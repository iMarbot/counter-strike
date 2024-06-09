### Roster Details<br />
Team Name: HyperSpirit<br />
Roster: ADRON, GEOHYPE, kritik, smekk, swiiffter<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [155](../standings_global.md)<br />
Regional Rank: [108]( ../standings_europe.md)<br />
Final Rank Value:  776.5<br />
<br />
Final Rank Value (776.5) = Starting Rank Value (755.6) + Head To Head Adjustments (20.9)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.292[<sup>1</sup>](#table2)
- Bounty Collected: 0.260[<sup>2</sup>](#table1)
- Opponent Network: 0.149[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.175<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 755.6
- 400 + ( ( 0.175 - 0.000 ) / ( 0.787 - 0.000 ) ) * 1600 = 755.6


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent             | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                      |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           40 |      355 | 2024-05-24 | Dynamo Eclot         | L   | 1.000      | -            | -                | -                | -         |   -10.96 | ADRON, GEOHYPE, kritik, smekk, swiiffter    |
|           39 |      500 | 2024-05-22 | NOM Esports          | W   | 1.000      | 0.372        | -                | 0.360 (0.134)    | 0 (0.000) |    10.99 | ADRON, GEOHYPE, kritik, smekk, swiiffter    |
|           38 |      618 | 2024-05-21 | WOPA Esport          | W   | 1.000      | 0.372        | 0.003 (0.001)    | 0.594 (0.221)    | 0 (0.000) |    15.49 | ADRON, GEOHYPE, kritik, smekk, swiiffter    |
|           37 |      711 | 2024-05-20 | HOTU                 | L   | 1.000      | -            | -                | -                | -         |   -12.11 | ADRON, GEOHYPE, kritik, smekk, swiiffter    |
|           36 |      994 | 2024-05-17 | Nexus Gaming         | L   | 1.000      | -            | -                | -                | -         |   -12.90 | ADRON, GEOHYPE, kritik, smekk, swiiffter    |
|           35 |     1171 | 2024-05-15 | Lemondogs            | W   | 1.000      | 0.372        | -                | 0.314 (0.117)    | 0 (0.000) |     9.92 | ADRON, GEOHYPE, kritik, smekk, swiiffter    |
|           34 |     1288 | 2024-05-14 | Young Ninjas         | L   | 1.000      | -            | -                | -                | -         |   -11.15 | ADRON, GEOHYPE, kritik, smekk, swiiffter    |
|           33 |     1336 | 2024-05-13 | Denial               | W   | 1.000      | -            | -                | -                | 0 (0.000) |     7.92 | ADRON, GEOHYPE, kritik, smekk, swiiffter    |
|           32 |     1517 | 2024-05-10 | 9Pandas              | L   | 1.000      | -            | -                | -                | -         |    -4.50 | ADRON, GEOHYPE, kritik, smekk, swiiffter    |
|           31 |     1524 | 2024-05-10 | 1win                 | W   | 1.000      | 0.143        | 0.050 (0.007)    | 0.898 (0.128)    | 0 (0.000) |    26.33 | ADRON, GEOHYPE, kritik, smekk, swiiffter    |
|           30 |     1538 | 2024-05-10 | Chroma               | W   | 1.000      | 0.143        | 0.000 (0.000)    | -                | 0 (0.000) |     8.54 | ADRON, GEOHYPE, kritik, smekk, swiiffter    |
|           29 |     1953 | 2024-05-02 | GenOne               | L   | 1.000      | -            | -                | -                | -         |   -19.41 | ADRON, GEOHYPE, kritik, smekk, swiiffter    |
|           28 |     2358 | 2024-04-25 | Team PeeP            | W   | 0.970      | 0.372        | -                | 0.247 (0.089)    | 0 (0.000) |     8.96 | ADRON, GEOHYPE, kritik, smekk, swiiffter    |
|           27 |     2424 | 2024-04-24 | Aurora Young Blud    | L   | 0.963      | -            | -                | -                | -         |   -14.32 | ADRON, GEOHYPE, kritik, smekk, swiiffter    |
|           26 |     3146 | 2024-04-12 | Nexus Gaming         | W   | 0.883      | 0.372        | 0.003 (0.001)    | 0.857 (0.282)    | 0 (0.000) |    20.94 | ADRON, GEOHYPE, kritik, smekk, swiiffter    |
|           25 |     3179 | 2024-04-11 | ThunderFlash         | L   | 0.877      | -            | -                | -                | -         |   -11.53 | ADRON, GEOHYPE, kritik, smekk, swiiffter    |
|           24 |     4169 | 2024-03-21 | Raptors Esports Club | L   | 0.738      | -            | -                | -                | -         |    -9.69 | ADRON, GEOHYPE, kritik, smekk, swiiffter    |
|           23 |     4237 | 2024-03-20 | WOPA Esport          | W   | 0.730      | 0.333        | 0.003 (0.001)    | 0.594 (0.145)    | 0 (0.000) |    12.64 | ADRON, kritik, smekk, starkiller, swiiffter |
|           22 |     4263 | 2024-03-19 | LEON Esports         | W   | 0.725      | 0.333        | 0.001 (0.000)    | 0.564 (0.136)    | 0 (0.000) |    11.36 | ADRON, GEOHYPE, kritik, smekk, swiiffter    |
|           21 |     4318 | 2024-03-18 | ADEPTS               | W   | 0.717      | 0.333        | 0.005 (0.001)    | 0.291 (0.070)    | -         |    14.33 | ADRON, GEOHYPE, kritik, smekk, swiiffter    |
|           20 |     4376 | 2024-03-17 | fragmatic            | W   | 0.710      | -            | -                | -                | -         |     5.89 | ADRON, GEOHYPE, kritik, smekk, swiiffter    |
|           19 |     4488 | 2024-03-15 | Preasy Esport        | W   | 0.697      | 0.333        | 0.008 (0.002)    | 0.705 (0.164)    | -         |    13.35 | ADRON, GEOHYPE, kritik, smekk, swiiffter    |
|           18 |     4610 | 2024-03-13 | Oxuji Esports        | W   | 0.684      | -            | -                | -                | -         |     5.32 | ADRON, GEOHYPE, kritik, smekk, swiiffter    |
|           17 |     4790 | 2024-03-10 | LEON Esports         | L   | 0.663      | -            | -                | -                | -         |    -9.38 | ADRON, GEOHYPE, kritik, smekk, swiiffter    |
|           16 |     4923 | 2024-03-07 | Part Timers          | W   | 0.645      | 0.333        | 0.001 (0.000)    | -                | -         |    11.26 | ADRON, GEOHYPE, kritik, smekk, swiiffter    |
|           15 |     5154 | 2024-03-04 | AMKAL ESPORTS        | L   | 0.625      | -            | -                | -                | -         |    -1.40 | ADRON, GEOHYPE, kritik, smekk, swiiffter    |
|           14 |     5297 | 2024-03-02 | 9INE                 | L   | 0.611      | -            | -                | -                | -         |   -13.13 | ADRON, GEOHYPE, kritik, smekk, swiiffter    |
|           13 |     6428 | 2024-02-11 | DASH                 | L   | 0.477      | -            | -                | -                | -         |    -7.72 | ADRON, GEOHYPE, kritik, smekk, swiiffter    |
|           12 |     6748 | 2024-02-03 | L&G                  | L   | 0.423      | -            | -                | -                | -         |   -10.26 | ADRON, GEOHYPE, kritik, smekk, swiiffter    |
|           11 |     7184 | 2024-01-27 | AIRLYA               | L   | 0.377      | -            | -                | -                | -         |    -9.37 | ADRON, GEOHYPE, kritik, smekk, swiiffter    |
|           10 |     7190 | 2024-01-27 | M1X                  | W   | 0.377      | -            | -                | -                | -         |     2.40 | ADRON, GEOHYPE, kritik, smekk, swiiffter    |
|            9 |     7271 | 2024-01-26 | 500                  | L   | 0.370      | -            | -                | -                | -         |    -5.32 | ADRON, GEOHYPE, kritik, smekk, swiiffter    |
|            8 |     7272 | 2024-01-26 | ILLYRIANS            | W   | 0.370      | 0.143        | 0.000 (0.000)    | -                | -         |     5.63 | ADRON, GEOHYPE, kritik, smekk, swiiffter    |
|            7 |     8083 | 2024-01-12 | Team Space           | L   | 0.278      | -            | -                | -                | -         |    -3.23 | ADRON, awks, GEOHYPE, kritik, swiiffter     |
|            6 |     8255 | 2024-01-10 | HAVU Gaming          | L   | 0.265      | -            | -                | -                | -         |    -4.01 | ADRON, awks, GEOHYPE, kritik, swiiffter     |
|            5 |     9149 | 2023-12-12 | Passion UA           | L   | 0.070      | -            | -                | -                | -         |    -0.40 | ADRON, awks, GEOHYPE, kritik, swiiffter     |
|            4 |     9195 | 2023-12-11 | TOOMUCHVIDEOGAMES    | W   | 0.064      | -            | -                | -                | -         |     0.40 | ADRON, awks, GEOHYPE, kritik, swiiffter     |
|            3 |     9278 | 2023-12-09 | Donstu Esports       | W   | 0.051      | -            | -                | -                | -         |     0.35 | ADRON, awks, GEOHYPE, kritik, swiiffter     |
|            2 |     9434 | 2023-12-07 | RUR Esports          | W   | 0.037      | -            | -                | -                | -         |     0.20 | ADRON, awks, GEOHYPE, kritik, swiiffter     |
|            1 |     9581 | 2023-12-05 | gbcxz                | L   | 0.024      | -            | -                | -                | -         |    -0.53 | ADRON, awks, GEOHYPE, kritik, swiiffter     |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($1,126.88)
- Divide that value by the 5th highest value among all rosters ($300,806.11)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
