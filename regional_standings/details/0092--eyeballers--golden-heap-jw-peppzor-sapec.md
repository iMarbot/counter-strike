### Roster Details<br />
Team Name: EYEBALLERS<br />
Roster: Golden, HEAP, JW, Peppzor, Sapec<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [92](../standings_global.md)<br />
Regional Rank: [65]( ../standings_europe.md)<br />
Final Rank Value:  885.5<br />
<br />
Final Rank Value (885.5) = Starting Rank Value (915.2) + Head To Head Adjustments (-29.7)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.344[<sup>1</sup>](#table2)
- Bounty Collected: 0.373[<sup>2</sup>](#table1)
- Opponent Network: 0.296[<sup>2</sup>](#table1)
- LAN Wins: 0.001[<sup>2</sup>](#table1)

The average of these factors is 0.254<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 915.2
- 400 + ( ( 0.254 - 0.000 ) / ( 0.787 - 0.000 ) ) * 1600 = 915.2


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
|           66 |      587 | 2024-05-21 | Pera Esports         | L   | 1.000      | -            | -                | -                | -         |   -13.10 | Golden, HEAP, JW, Peppzor, Sapec |
|           65 |      599 | 2024-05-21 | DMS                  | L   | 1.000      | -            | -                | -                | -         |   -14.14 | Golden, HEAP, JW, Peppzor, Sapec |
|           64 |      716 | 2024-05-20 | B8                   | L   | 1.000      | -            | -                | -                | -         |    -6.54 | Golden, HEAP, JW, Peppzor, Sapec |
|           63 |      976 | 2024-05-17 | ALTERNATE aTTaX      | W   | 1.000      | 0.435        | 0.052 (0.023)    | 0.735 (0.319)    | 0 (0.000) |    16.74 | Golden, HEAP, JW, Peppzor, Sapec |
|           62 |     1115 | 2024-05-16 | MASONIC              | L   | 1.000      | -            | -                | -                | -         |   -20.14 | Golden, HEAP, JW, Peppzor, Sapec |
|           61 |     1161 | 2024-05-15 | Permitta Esports     | W   | 1.000      | 0.435        | 0.025 (0.011)    | 1.000 (0.435)    | 0 (0.000) |    12.45 | Golden, HEAP, JW, Peppzor, Sapec |
|           60 |     1184 | 2024-05-15 | 9INE                 | W   | 1.000      | -            | -                | -                | 0 (0.000) |     5.29 | Golden, HEAP, JW, Peppzor, Sapec |
|           59 |     1215 | 2024-05-15 | Rhyno Esports        | L   | 1.000      | -            | -                | -                | -         |   -13.09 | Golden, HEAP, JW, Peppzor, Sapec |
|           58 |     1263 | 2024-05-14 | Team Space           | L   | 1.000      | -            | -                | -                | -         |   -19.09 | Golden, HEAP, JW, Peppzor, Sapec |
|           57 |     1335 | 2024-05-13 | Zero Tenacity        | L   | 1.000      | -            | -                | -                | -         |   -10.42 | Golden, HEAP, JW, Peppzor, Sapec |
|           56 |     1525 | 2024-05-10 | Metizport            | L   | 1.000      | -            | -                | -                | -         |   -10.57 | Golden, HEAP, JW, Peppzor, Sapec |
|           55 |     1895 | 2024-05-03 | Zero Tenacity        | W   | 1.000      | 0.435        | 0.147 (0.064)    | 1.000 (0.435)    | 0 (0.000) |    18.89 | Golden, HEAP, JW, Peppzor, Sapec |
|           54 |     1955 | 2024-05-02 | RUSH B               | W   | 1.000      | 0.435        | -                | 0.446 (0.194)    | 0 (0.000) |    11.69 | Golden, HEAP, JW, Peppzor, Sapec |
|           53 |     2021 | 2024-05-01 | BetBoom Team         | L   | 1.000      | -            | -                | -                | -         |    -2.80 | Golden, HEAP, JW, Peppzor, Sapec |
|           52 |     2060 | 2024-04-30 | ENTERPRISE esports   | W   | 1.000      | 0.435        | -                | 0.898 (0.390)    | 0 (0.000) |    12.74 | Golden, HEAP, JW, Peppzor, Sapec |
|           51 |     2070 | 2024-04-30 | HAVU Gaming          | L   | 1.000      | -            | -                | -                | -         |   -24.03 | Golden, HEAP, JW, Peppzor, Sapec |
|           50 |     2102 | 2024-04-29 | ex-Guild Eagles      | W   | 0.997      | 0.435        | -                | 0.475 (0.206)    | 0 (0.000) |    17.16 | Golden, HEAP, JW, Peppzor, Sapec |
|           49 |     2250 | 2024-04-27 | Illuminar Gaming     | W   | 0.982      | 0.435        | -                | 0.403 (0.172)    | 0 (0.000) |    11.49 | Golden, HEAP, JW, Peppzor, Sapec |
|           48 |     2342 | 2024-04-25 | HAVU Gaming          | W   | 0.970      | -            | -                | -                | -         |     6.84 | Golden, HEAP, JW, Peppzor, Sapec |
|           47 |     2366 | 2024-04-25 | Zero Tenacity        | W   | 0.969      | 0.384        | 0.147 (0.055)    | 1.000 (0.372)    | -         |    19.29 | Golden, HEAP, JW, Peppzor, Sapec |
|           46 |     2459 | 2024-04-23 | Insilio              | L   | 0.957      | -            | -                | -                | -         |   -13.36 | Golden, HEAP, JW, Peppzor, Sapec |
|           45 |     2513 | 2024-04-22 | MOUZ NXT             | L   | 0.949      | -            | -                | -                | -         |    -8.25 | Golden, HEAP, JW, Peppzor, Sapec |
|           44 |     2619 | 2024-04-20 | Pera Esports         | W   | 0.937      | 0.500        | 0.028 (0.013)    | 0.542 (0.254)    | -         |    13.23 | Golden, HEAP, JW, Peppzor, Sapec |
|           43 |     2819 | 2024-04-18 | DMS                  | L   | 0.923      | -            | -                | -                | -         |   -16.51 | Golden, HEAP, JW, Peppzor, Sapec |
|           42 |     2880 | 2024-04-17 | Rebels Gaming        | W   | 0.918      | 0.143        | 0.062 (0.008)    | -                | -         |    21.79 | Golden, HEAP, JW, Peppzor, Sapec |
|           41 |     2934 | 2024-04-17 | Endpoint             | L   | 0.915      | -            | -                | -                | -         |   -13.02 | Golden, HEAP, JW, Peppzor, Sapec |
|           40 |     3280 | 2024-04-10 | Permitta Esports     | L   | 0.868      | -            | -                | -                | -         |   -11.95 | Golden, HEAP, JW, Peppzor, Sapec |
|           39 |     3412 | 2024-04-07 | Metizport            | L   | 0.850      | -            | -                | -                | -         |    -7.13 | Golden, HEAP, JW, Peppzor, Sapec |
|           38 |     3429 | 2024-04-07 | Alliance             | W   | 0.849      | -            | -                | -                | -         |    11.74 | Golden, HEAP, JW, Peppzor, Sapec |
|           37 |     3466 | 2024-04-06 | onliners5            | W   | 0.843      | -            | -                | -                | -         |     4.17 | Golden, HEAP, JW, Peppzor, Sapec |
|           36 |     3577 | 2024-04-04 | Sangal Esports       | L   | 0.831      | -            | -                | -                | -         |   -10.56 | Golden, HEAP, JW, Peppzor, Sapec |
|           35 |     3639 | 2024-04-03 | 9Pandas              | L   | 0.824      | -            | -                | -                | -         |    -4.88 | Golden, HEAP, JW, Peppzor, Sapec |
|           34 |     3652 | 2024-04-03 | BIG                  | L   | 0.822      | -            | -                | -                | -         |    -1.79 | Golden, HEAP, JW, Peppzor, Sapec |
|           33 |     3839 | 2024-03-28 | KOI                  | W   | 0.783      | 0.500        | 0.027 (0.011)    | 0.455 (0.178)    | -         |    16.63 | Golden, HEAP, JW, Peppzor, Sapec |
|           32 |     3962 | 2024-03-26 | Natus Vincere Junior | L   | 0.771      | -            | -                | -                | -         |   -15.29 | Golden, HEAP, JW, Peppzor, Sapec |
|           31 |     4793 | 2024-03-10 | Alliance             | L   | 0.663      | -            | -                | -                | -         |   -12.09 | HEAP, JW, Peppzor, Sapec, SHiNE  |
|           30 |     4844 | 2024-03-09 | Metizport            | W   | 0.656      | 0.143        | 0.088 (0.008)    | -                | -         |    13.97 | HEAP, JW, Peppzor, Sapec, SHiNE  |
|           29 |     4849 | 2024-03-09 | onliners5            | W   | 0.656      | -            | -                | -                | -         |     1.13 | HEAP, JW, Peppzor, Sapec, SHiNE  |
|           28 |     4854 | 2024-03-09 | freakshow1           | W   | 0.656      | -            | -                | -                | -         |     1.07 | HEAP, JW, Peppzor, Sapec, SHiNE  |
|           27 |     4985 | 2024-03-06 | 9INE                 | W   | 0.638      | -            | -                | -                | -         |     3.84 | HEAP, JW, Peppzor, Sapec, SHiNE  |
|           26 |     6718 | 2024-02-03 | Sashi Esport         | L   | 0.424      | -            | -                | -                | -         |    -4.26 | HEAP, JW, Peppzor, Sapec, SHiNE  |
|           25 |     6728 | 2024-02-03 | Foxed Gaming         | W   | 0.424      | -            | -                | -                | -         |     1.13 | HEAP, JW, Peppzor, Sapec, SHiNE  |
|           24 |     6790 | 2024-02-02 | Metizport            | L   | 0.418      | -            | -                | -                | -         |    -5.43 | HEAP, JW, Peppzor, Sapec, SHiNE  |
|           23 |     6796 | 2024-02-02 | Sashi Esport         | W   | 0.417      | 0.143        | 0.154 (0.009)    | -                | -         |     9.21 | HEAP, JW, Peppzor, Sapec, SHiNE  |
|           22 |     6807 | 2024-02-02 | AURA                 | W   | 0.417      | -            | -                | -                | -         |     2.15 | HEAP, JW, Peppzor, Sapec, SHiNE  |
|           21 |     6814 | 2024-02-02 | Team Atlantic        | W   | 0.417      | -            | -                | -                | -         |     0.71 | HEAP, JW, Peppzor, Sapec, SHiNE  |
|           20 |     7644 | 2024-01-19 | Entropiq             | L   | 0.324      | -            | -                | -                | -         |    -8.20 | HEAP, JW, Peppzor, Sapec, SHiNE  |
|           19 |     7711 | 2024-01-18 | Pera Esports         | L   | 0.318      | -            | -                | -                | -         |    -5.09 | HEAP, JW, Peppzor, Sapec, SHiNE  |
|           18 |     7731 | 2024-01-18 | MOUZ                 | L   | 0.317      | -            | -                | -                | -         |    -0.03 | HEAP, JW, Peppzor, Sapec, SHiNE  |
|           17 |     7870 | 2024-01-16 | The Witchers         | W   | 0.305      | -            | -                | -                | -         |     2.36 | HEAP, JW, Peppzor, Sapec, SHiNE  |
|           16 |     7882 | 2024-01-16 | Sashi Esport         | W   | 0.305      | 0.143        | 0.154 (0.007)    | -                | -         |     6.60 | HEAP, JW, Peppzor, Sapec, SHiNE  |
|           15 |     7897 | 2024-01-16 | PARIVISION           | W   | 0.304      | -            | -                | -                | -         |     5.02 | HEAP, JW, Peppzor, Sapec, SHiNE  |
|           14 |     7911 | 2024-01-16 | Untouchabless        | W   | 0.304      | -            | -                | -                | -         |     0.53 | HEAP, JW, Peppzor, Sapec, SHiNE  |
|           13 |     8081 | 2024-01-12 | Insilio              | L   | 0.279      | -            | -                | -                | -         |    -4.60 | HEAP, JW, Peppzor, Sapec, SHiNE  |
|           12 |     8092 | 2024-01-12 | happyend1            | W   | 0.278      | -            | -                | -                | -         |     0.47 | HEAP, JW, Peppzor, Sapec, SHiNE  |
|           11 |     8356 | 2024-01-09 | Fnatic               | L   | 0.257      | -            | -                | -                | -         |    -1.98 | HEAP, JW, Peppzor, Sapec, SHiNE  |
|           10 |     8713 | 2023-12-17 | INGLORIOUS           | L   | 0.104      | -            | -                | -                | -         |    -2.35 | HEAP, JW, Peppzor, Sapec, SHiNE  |
|            9 |     8723 | 2023-12-17 | GenOne               | W   | 0.103      | -            | -                | -                | -         |     0.32 | HEAP, JW, Peppzor, Sapec, SHiNE  |
|            8 |     8841 | 2023-12-16 | GUN5 Esports         | W   | 0.098      | -            | -                | -                | -         |     0.31 | HEAP, JW, Peppzor, Sapec, SHiNE  |
|            7 |     8851 | 2023-12-16 | RUBY                 | W   | 0.098      | -            | -                | -                | -         |     1.46 | HEAP, JW, Peppzor, Sapec, SHiNE  |
|            6 |     9437 | 2023-12-07 | Apeks                | L   | 0.037      | -            | -                | -                | -         |    -0.17 | HEAP, JW, Peppzor, Sapec, SHiNE  |
|            5 |     9456 | 2023-12-07 | FORZE Esports        | L   | 0.036      | -            | -                | -                | -         |    -0.83 | HEAP, JW, Peppzor, Sapec, SHiNE  |
|            4 |     9499 | 2023-12-06 | ENCE                 | W   | 0.031      | -            | -                | -                | -         |     0.92 | HEAP, JW, Peppzor, Sapec, SHiNE  |
|            3 |     9598 | 2023-12-05 | Sashi Esport         | W   | 0.022      | -            | -                | -                | -         |     0.50 | HEAP, JW, Peppzor, Sapec, SHiNE  |
|            2 |     9638 | 2023-12-03 | GODSENT              | W   | 0.011      | -            | -                | -                | 1 (0.011) |     0.07 | HEAP, JW, Peppzor, Sapec, SHiNE  |
|            1 |     9768 | 2023-12-02 | Alliance             | W   | 0.003      | -            | -                | -                | 1 (0.003) |     0.04 | HEAP, JW, Peppzor, Sapec, SHiNE  |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($3,731.69)
- Divide that value by the 5th highest value among all rosters ($300,806.11)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-05-22 |      1.000 | $1,000.00      | $1,000.00       |
| 2024-04-07 |      0.850 | $2,341.48      | $1,990.91       |
| 2023-12-17 |      0.104 | $1,000.00      | $104.07         |
| 2023-12-10 |      0.058 | $6,500.00      | $373.75         |
| 2023-12-03 |      0.011 | $23,965.22     | $262.95         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
