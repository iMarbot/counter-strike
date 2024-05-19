### Roster Details<br />
Team Name: EYEBALLERS<br />
Roster: Golden, HEAP, JW, Peppzor, Sapec<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [57](../standings_global.md)<br />
Regional Rank: [42]( ../standings_europe.md)<br />
Final Rank Value:  971.6<br />
<br />
Final Rank Value (971.6) = Starting Rank Value (942.5) + Head To Head Adjustments (29.1)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.437[<sup>1</sup>](#table2)
- Bounty Collected: 0.388[<sup>2</sup>](#table1)
- Opponent Network: 0.231[<sup>2</sup>](#table1)
- LAN Wins: 0.037[<sup>2</sup>](#table1)

The average of these factors is 0.273<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 942.5
- 400 + ( ( 0.273 - 0.000 ) / ( 0.806 - 0.000 ) ) * 1600 = 942.5


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
|           53 |       98 | 2024-05-03 | Zero Tenacity         | W   | 1.000      | 0.435        | 0.095 (0.041)    | 1.000 (0.435)    | 0 (0.000) |    17.42 | Golden, HEAP, JW, Peppzor, Sapec |
|           52 |      153 | 2024-05-02 | RUSH B (Russian team) | W   | 1.000      | 0.435        | -                | 0.471 (0.205)    | 0 (0.000) |    11.62 | Golden, HEAP, JW, Peppzor, Sapec |
|           51 |      209 | 2024-05-01 | BetBoom Team          | L   | 1.000      | -            | -                | -                | -         |    -2.37 | Golden, HEAP, JW, Peppzor, Sapec |
|           50 |      240 | 2024-04-30 | ENTERPRISE esports    | W   | 1.000      | 0.435        | 0.039 (0.017)    | 0.476 (0.207)    | 0 (0.000) |    12.20 | Golden, HEAP, JW, Peppzor, Sapec |
|           49 |      249 | 2024-04-30 | HAVU Gaming           | L   | 1.000      | -            | -                | -                | -         |   -23.20 | Golden, HEAP, JW, Peppzor, Sapec |
|           48 |      276 | 2024-04-29 | Guild Eagles          | W   | 1.000      | 0.435        | 0.037 (0.016)    | 0.586 (0.255)    | 0 (0.000) |    16.66 | Golden, HEAP, JW, Peppzor, Sapec |
|           47 |      389 | 2024-04-27 | Illuminar Gaming      | W   | 1.000      | 0.435        | -                | 0.433 (0.188)    | 0 (0.000) |    11.64 | Golden, HEAP, JW, Peppzor, Sapec |
|           46 |      465 | 2024-04-25 | HAVU Gaming           | W   | 1.000      | -            | -                | -                | 0 (0.000) |     7.92 | Golden, HEAP, JW, Peppzor, Sapec |
|           45 |      488 | 2024-04-25 | Zero Tenacity         | W   | 1.000      | 0.384        | 0.095 (0.036)    | 1.000 (0.384)    | 0 (0.000) |    17.78 | Golden, HEAP, JW, Peppzor, Sapec |
|           44 |      568 | 2024-04-23 | Insilio               | L   | 1.000      | -            | -                | -                | -         |   -14.96 | Golden, HEAP, JW, Peppzor, Sapec |
|           43 |      614 | 2024-04-22 | MOUZ NXT              | L   | 1.000      | -            | -                | -                | -         |   -10.21 | Golden, HEAP, JW, Peppzor, Sapec |
|           42 |      701 | 2024-04-20 | Pera Esports          | W   | 1.000      | 0.500        | 0.065 (0.033)    | 0.324 (0.162)    | 0 (0.000) |    14.32 | Golden, HEAP, JW, Peppzor, Sapec |
|           41 |      879 | 2024-04-18 | DMS                   | L   | 1.000      | -            | -                | -                | -         |   -21.17 | Golden, HEAP, JW, Peppzor, Sapec |
|           40 |      929 | 2024-04-17 | Rebels Gaming         | W   | 1.000      | 0.143        | 0.121 (0.017)    | -                | -         |    24.57 | Golden, HEAP, JW, Peppzor, Sapec |
|           39 |      977 | 2024-04-17 | Endpoint              | L   | 1.000      | -            | -                | -                | -         |   -17.68 | Golden, HEAP, JW, Peppzor, Sapec |
|           38 |     1251 | 2024-04-10 | Permitta Esports      | L   | 1.000      | -            | -                | -                | -         |   -16.78 | Golden, HEAP, JW, Peppzor, Sapec |
|           37 |     1364 | 2024-04-07 | Metizport             | L   | 1.000      | -            | -                | -                | -         |    -7.58 | Golden, HEAP, JW, Peppzor, Sapec |
|           36 |     1371 | 2024-04-07 | Alliance              | W   | 1.000      | 0.143        | -                | 0.729 (0.104)    | -         |    12.62 | Golden, HEAP, JW, Peppzor, Sapec |
|           35 |     1534 | 2024-04-03 | 9Pandas               | L   | 0.985      | -            | -                | -                | -         |    -7.25 | Golden, HEAP, JW, Peppzor, Sapec |
|           34 |     1547 | 2024-04-03 | BIG                   | L   | 0.984      | -            | -                | -                | -         |    -1.94 | Golden, HEAP, JW, Peppzor, Sapec |
|           33 |     1698 | 2024-03-28 | KOI                   | W   | 0.944      | 0.500        | 0.066 (0.031)    | 0.537 (0.254)    | -         |    21.05 | Golden, HEAP, JW, Peppzor, Sapec |
|           32 |     1802 | 2024-03-26 | Natus Vincere Junior  | L   | 0.932      | -            | -                | -                | -         |   -17.99 | Golden, HEAP, JW, Peppzor, Sapec |
|           31 |     2465 | 2024-03-10 | Alliance              | L   | 0.824      | -            | -                | -                | -         |   -15.07 | HEAP, JW, Peppzor, Sapec, SHiNE  |
|           30 |     2503 | 2024-03-09 | Metizport             | W   | 0.818      | 0.143        | 0.188 (0.022)    | 1.000 (0.117)    | -         |    18.64 | HEAP, JW, Peppzor, Sapec, SHiNE  |
|           29 |     3958 | 2024-02-03 | Sashi Esport          | L   | 0.585      | -            | -                | -                | -         |    -6.58 | HEAP, JW, Peppzor, Sapec, SHiNE  |
|           28 |     3966 | 2024-02-03 | Foxed Gaming          | W   | 0.585      | -            | -                | -                | -         |     0.83 | HEAP, JW, Peppzor, Sapec, SHiNE  |
|           27 |     4011 | 2024-02-02 | Metizport             | L   | 0.579      | -            | -                | -                | -         |    -7.40 | HEAP, JW, Peppzor, Sapec, SHiNE  |
|           26 |     4017 | 2024-02-02 | Sashi Esport          | W   | 0.579      | 0.143        | 0.193 (0.016)    | -                | -         |    12.08 | HEAP, JW, Peppzor, Sapec, SHiNE  |
|           25 |     4029 | 2024-02-02 | Team Atlantic         | W   | 0.578      | -            | -                | -                | -         |     0.83 | HEAP, JW, Peppzor, Sapec, SHiNE  |
|           24 |     4599 | 2024-01-19 | Entropiq              | L   | 0.486      | -            | -                | -                | -         |   -10.60 | HEAP, JW, Peppzor, Sapec, SHiNE  |
|           23 |     4649 | 2024-01-18 | Pera Esports          | L   | 0.479      | -            | -                | -                | -         |    -8.12 | HEAP, JW, Peppzor, Sapec, SHiNE  |
|           22 |     4670 | 2024-01-18 | MOUZ                  | L   | 0.478      | -            | -                | -                | -         |    -0.10 | HEAP, JW, Peppzor, Sapec, SHiNE  |
|           21 |     4776 | 2024-01-16 | The Witchers          | W   | 0.466      | -            | -                | -                | -         |     4.27 | HEAP, JW, Peppzor, Sapec, SHiNE  |
|           20 |     4785 | 2024-01-16 | Sashi Esport          | W   | 0.466      | -            | -                | -                | -         |     9.54 | HEAP, JW, Peppzor, Sapec, SHiNE  |
|           19 |     4794 | 2024-01-16 | PARIVISION            | W   | 0.466      | -            | -                | -                | -         |     5.96 | HEAP, JW, Peppzor, Sapec, SHiNE  |
|           18 |     4803 | 2024-01-16 | Untouchabless         | W   | 0.465      | -            | -                | -                | -         |     1.22 | HEAP, JW, Peppzor, Sapec, SHiNE  |
|           17 |     4920 | 2024-01-12 | Insilio               | L   | 0.440      | -            | -                | -                | -         |    -7.32 | HEAP, JW, Peppzor, Sapec, SHiNE  |
|           16 |     5103 | 2024-01-09 | Fnatic                | L   | 0.418      | -            | -                | -                | -         |    -2.62 | HEAP, JW, Peppzor, Sapec, SHiNE  |
|           15 |     5354 | 2023-12-17 | INGLORIOUS            | L   | 0.265      | -            | -                | -                | -         |    -5.92 | HEAP, JW, Peppzor, Sapec, SHiNE  |
|           14 |     5362 | 2023-12-17 | GenOne                | W   | 0.264      | -            | -                | -                | -         |     1.20 | HEAP, JW, Peppzor, Sapec, SHiNE  |
|           13 |     5453 | 2023-12-16 | GUN5 Esports          | W   | 0.259      | -            | -                | -                | -         |     1.24 | HEAP, JW, Peppzor, Sapec, SHiNE  |
|           12 |     5460 | 2023-12-16 | RUBY                  | W   | 0.259      | -            | -                | -                | -         |     3.13 | HEAP, JW, Peppzor, Sapec, SHiNE  |
|           11 |     5886 | 2023-12-07 | Apeks                 | L   | 0.199      | -            | -                | -                | -         |    -0.45 | HEAP, JW, Peppzor, Sapec, SHiNE  |
|           10 |     5897 | 2023-12-07 | FORZE Esports         | L   | 0.197      | -            | -                | -                | -         |    -4.42 | HEAP, JW, Peppzor, Sapec, SHiNE  |
|            9 |     5928 | 2023-12-06 | ENCE                  | W   | 0.192      | 0.500        | 0.377 (0.036)    | -                | -         |     5.84 | HEAP, JW, Peppzor, Sapec, SHiNE  |
|            8 |     6000 | 2023-12-05 | Sashi Esport          | W   | 0.184      | -            | -                | -                | -         |     3.97 | HEAP, JW, Peppzor, Sapec, SHiNE  |
|            7 |     6031 | 2023-12-03 | GODSENT               | W   | 0.172      | -            | -                | -                | 1 (0.172) |     1.74 | HEAP, JW, Peppzor, Sapec, SHiNE  |
|            6 |     6118 | 2023-12-02 | Alliance              | W   | 0.164      | -            | -                | -                | 1 (0.164) |     2.22 | HEAP, JW, Peppzor, Sapec, SHiNE  |
|            5 |     6327 | 2023-11-28 | Preasy Esport         | L   | 0.138      | -            | -                | -                | -         |    -2.09 | HEAP, JW, Peppzor, Sapec, SHiNE  |
|            4 |     6601 | 2023-11-21 | 00 Nation             | W   | 0.091      | -            | -                | -                | -         |     0.23 | HEAP, JW, Peppzor, Sapec, SHiNE  |
|            3 |     6827 | 2023-11-16 | Gaimin Gladiators     | L   | 0.058      | -            | -                | -                | -         |    -0.10 | HEAP, JW, Peppzor, Sapec, SHiNE  |
|            2 |     7051 | 2023-11-11 | FORZE Esports         | W   | 0.025      | -            | -                | -                | -         |     0.23 | HEAP, JW, Peppzor, Sapec, SHiNE  |
|            1 |     7208 | 2023-11-08 | TSM                   | W   | 0.004      | -            | -                | -                | -         |     0.02 | HEAP, JW, Peppzor, Sapec, SHiNE  |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($8,150.20)
- Divide that value by the 5th highest value among all rosters ($158,437.64)
- The final value (0.05) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-04-07 |      1.000 | $2,341.48      | $2,341.48       |
| 2023-12-17 |      0.265 | $1,000.00      | $265.14         |
| 2023-12-10 |      0.219 | $6,500.00      | $1,420.67       |
| 2023-12-03 |      0.172 | $23,965.22     | $4,122.91       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
