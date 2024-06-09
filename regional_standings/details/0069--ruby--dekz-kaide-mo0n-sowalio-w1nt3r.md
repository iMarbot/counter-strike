### Roster Details<br />
Team Name: RUBY<br />
Roster: dekz, Kaide, mo0n, Sowalio, w1nt3r<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [69](../standings_global.md)<br />
Regional Rank: [48]( ../standings_europe.md)<br />
Final Rank Value:  951.2<br />
<br />
Final Rank Value (951.2) = Starting Rank Value (897.0) + Head To Head Adjustments (54.2)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.315[<sup>1</sup>](#table2)
- Bounty Collected: 0.400[<sup>2</sup>](#table1)
- Opponent Network: 0.263[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.245<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 897.0
- 400 + ( ( 0.245 - 0.000 ) / ( 0.787 - 0.000 ) ) * 1600 = 897.0


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent            | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                       |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           71 |      135 | 2024-05-28 | MOUZ NXT            | L   | 1.000      | -            | -                | -                | -         |   -12.76 | dekz, Kaide, mo0n, Sowalio, w1nt3r           |
|           70 |      234 | 2024-05-26 | Zero Tenacity       | L   | 1.000      | -            | -                | -                | -         |   -11.51 | dekz, Kaide, mo0n, Sowalio, w1nt3r           |
|           69 |      262 | 2024-05-25 | B8                  | L   | 1.000      | -            | -                | -                | -         |    -7.01 | dekz, Kaide, mo0n, Sowalio, w1nt3r           |
|           68 |      421 | 2024-05-23 | Team PeeP           | W   | 1.000      | -            | -                | -                | 0 (0.000) |     4.29 | dekz, Kaide, mo0n, Sowalio, w1nt3r           |
|           67 |      518 | 2024-05-22 | FAVBET Team         | L   | 1.000      | -            | -                | -                | -         |   -14.92 | dekz, Kaide, mo0n, Sowalio, w1nt3r           |
|           66 |      635 | 2024-05-21 | Endpoint            | W   | 1.000      | 0.435        | 0.012 (0.005)    | 0.770 (0.335)    | 0 (0.000) |    10.30 | dekz, Kaide, mo0n, Sowalio, w1nt3r           |
|           65 |      683 | 2024-05-20 | LEON Esports        | W   | 1.000      | 0.372        | -                | 0.564 (0.210)    | 0 (0.000) |     6.33 | dekz, Kaide, mo0n, Sowalio, w1nt3r           |
|           64 |      740 | 2024-05-19 | LODIS               | W   | 1.000      | -            | -                | -                | 0 (0.000) |     3.25 | dekz, Kaide, mo0n, Sowalio, w1nt3r           |
|           63 |     1454 | 2024-05-11 | 9Pandas             | L   | 1.000      | -            | -                | -                | -         |   -10.88 | dekz, Kaide, mo0n, Sowalio, w1nt3r           |
|           62 |     1548 | 2024-05-10 | Nemiga Gaming       | W   | 1.000      | 0.435        | 0.358 (0.156)    | 0.895 (0.389)    | 0 (0.000) |    24.08 | dekz, Kaide, mo0n, Sowalio, w1nt3r           |
|           61 |     1661 | 2024-05-08 | GenOne              | W   | 1.000      | 0.372        | -                | 0.442 (0.165)    | 0 (0.000) |     5.47 | dekz, Kaide, mo0n, Sowalio, w1nt3r           |
|           60 |     1697 | 2024-05-07 | Insilio             | W   | 1.000      | 0.435        | 0.007 (0.003)    | 0.717 (0.312)    | 0 (0.000) |    17.00 | dekz, Kaide, mo0n, Sowalio, w1nt3r           |
|           59 |     1783 | 2024-05-05 | LEON Esports        | W   | 1.000      | -            | -                | -                | 0 (0.000) |     7.79 | dekz, Kaide, mo0n, Sowalio, w1nt3r           |
|           58 |     1797 | 2024-05-05 | HAVU Gaming         | W   | 1.000      | -            | -                | -                | 0 (0.000) |     7.29 | dekz, Kaide, mo0n, Sowalio, w1nt3r           |
|           57 |     1848 | 2024-05-04 | FORZE Youngsters    | W   | 1.000      | -            | -                | -                | 0 (0.000) |     1.52 | dekz, Kaide, mo0n, Sowalio, w1nt3r           |
|           56 |     1912 | 2024-05-03 | V1dar Gaming        | W   | 1.000      | 0.435        | -                | 0.595 (0.258)    | -         |     8.53 | dekz, Kaide, mo0n, Sowalio, w1nt3r           |
|           55 |     1999 | 2024-05-01 | DMS                 | L   | 1.000      | -            | -                | -                | -         |   -19.66 | dekz, Kaide, mo0n, Sowalio, w1nt3r           |
|           54 |     2034 | 2024-05-01 | GamerLegion Academy | L   | 1.000      | -            | -                | -                | -         |   -20.36 | dekz, Kaide, mo0n, Sowalio, w1nt3r           |
|           53 |     2095 | 2024-04-29 | RoundsGG            | W   | 0.997      | -            | -                | -                | -         |     4.39 | dekz, Kaide, mo0n, Sowalio, w1nt3r           |
|           52 |     2215 | 2024-04-27 | Astralis Talent     | W   | 0.983      | -            | -                | -                | -         |     1.38 | dekz, Kaide, mo0n, Sowalio, w1nt3r           |
|           51 |     2351 | 2024-04-25 | MOUZ NXT            | L   | 0.970      | -            | -                | -                | -         |   -11.40 | dekz, Kaide, mo0n, Sowalio, w1nt3r           |
|           50 |     2405 | 2024-04-24 | esmagaB             | L   | 0.964      | -            | -                | -                | -         |   -21.24 | dekz, Kaide, mo0n, Sowalio, w1nt3r           |
|           49 |     2466 | 2024-04-23 | GenOne              | W   | 0.956      | -            | -                | -                | -         |     4.45 | dekz, Kaide, mo0n, Sowalio, w1nt3r           |
|           48 |     2476 | 2024-04-23 | Permitta Esports    | W   | 0.956      | 0.372        | 0.025 (0.009)    | 1.000 (0.356)    | -         |    15.57 | dekz, Kaide, mo0n, Sowalio, w1nt3r           |
|           47 |     2522 | 2024-04-22 | GUN5 Esports        | W   | 0.948      | -            | -                | -                | -         |     4.86 | dekz, Kaide, mo0n, Sowalio, w1nt3r           |
|           46 |     2648 | 2024-04-20 | Zero Tenacity       | L   | 0.936      | -            | -                | -                | -         |   -14.09 | dekz, kaide, mo0n, Sowalio, w1nt3r           |
|           45 |     2810 | 2024-04-18 | Sashi Esport        | L   | 0.924      | -            | -                | -                | -         |   -10.27 | dekz, Kaide, mo0n, Sowalio, w1nt3r           |
|           44 |     2822 | 2024-04-18 | Aurora Gaming       | W   | 0.923      | 0.143        | 0.492 (0.065)    | -                | -         |    26.85 | dekz, Kaide, mo0n, Sowalio, w1nt3r           |
|           43 |     2829 | 2024-04-18 | NOM Esports         | W   | 0.923      | -            | -                | -                | -         |     5.05 | dekz, kaide, mo0n, Sowalio, w1nt3r           |
|           42 |     2886 | 2024-04-17 | Team Falcons        | W   | 0.918      | 0.143        | 0.355 (0.047)    | -                | -         |    27.46 | dekz, Kaide, mo0n, Sowalio, w1nt3r           |
|           41 |     2927 | 2024-04-17 | JANO Esports        | W   | 0.915      | -            | -                | -                | -         |     8.02 | dekz, kaide, mo0n, Sowalio, w1nt3r           |
|           40 |     3110 | 2024-04-13 | ARCRED              | L   | 0.889      | -            | -                | -                | -         |   -18.27 | dekz, Kaide, mo0n, Sowalio, w1nt3r           |
|           39 |     3426 | 2024-04-07 | Insilio             | W   | 0.849      | -            | -                | -                | -         |    14.96 | dekz, Kaide, mo0n, Sowalio, w1nt3r           |
|           38 |     3959 | 2024-03-26 | brazylijski luz     | L   | 0.771      | -            | -                | -                | -         |   -15.99 | dekz, Kaide, mo0n, Sowalio, w1nt3r           |
|           37 |     4271 | 2024-03-19 | Sashi Esport        | L   | 0.724      | -            | -                | -                | -         |    -8.07 | dekz, Kaide, mo0n, Sowalio, w1nt3r           |
|           36 |     4437 | 2024-03-16 | Permitta Esports    | W   | 0.703      | 0.371        | 0.025 (0.007)    | 1.000 (0.261)    | -         |    13.03 | dekz, Kaide, mo0n, Sowalio, w1nt3r           |
|           35 |     4738 | 2024-03-11 | Nexus Gaming        | L   | 0.671      | -            | -                | -                | -         |   -10.72 | dekz, Kaide, mo0n, Sowalio, w1nt3r           |
|           34 |     4834 | 2024-03-09 | Team Spirit Academy | W   | 0.657      | -            | -                | -                | -         |     7.20 | dekz, Kaide, mo0n, Sowalio, w1nt3r           |
|           33 |     4876 | 2024-03-08 | ARCRED              | W   | 0.651      | 0.371        | -                | 0.630 (0.152)    | -         |     6.76 | dekz, Kaide, mo0n, Sowalio, w1nt3r           |
|           32 |     5168 | 2024-03-04 | Johnny Speeds       | L   | 0.625      | -            | -                | -                | -         |    -7.68 | dekz, Kaide, mo0n, Sowalio, w1nt3r           |
|           31 |     5313 | 2024-03-02 | ILIN                | L   | 0.611      | -            | -                | -                | -         |   -16.75 | dekz, Kaide, mo0n, Sowalio, w1nt3r           |
|           30 |     5432 | 2024-02-29 | INGLORIOUS          | W   | 0.597      | -            | -                | -                | -         |     5.51 | dekz, Kaide, mo0n, Sowalio, w1nt3r           |
|           29 |     5458 | 2024-02-28 | Permitta Esports    | L   | 0.591      | -            | -                | -                | -         |    -8.64 | dekz, Kaide, mo0n, Sowalio, w1nt3r           |
|           28 |     5470 | 2024-02-28 | ENTERPRISE esports  | W   | 0.591      | 0.371        | -                | 0.898 (0.197)    | -         |    10.23 | dekz, Kaide, mo0n, Sowalio, w1nt3r           |
|           27 |     5511 | 2024-02-27 | Team Spirit Academy | L   | 0.584      | -            | -                | -                | -         |   -12.99 | dekz, Kaide, mo0n, Sowalio, w1nt3r           |
|           26 |     5523 | 2024-02-27 | ALTERNATE aTTaX     | W   | 0.584      | 0.143        | 0.052 (0.004)    | -                | -         |     9.45 | dekz, Kaide, mo0n, Sowalio, w1nt3r           |
|           25 |     5563 | 2024-02-26 | ThunderFlash        | W   | 0.578      | -            | -                | -                | -         |     6.47 | dekz, Kaide, mo0n, Sowalio, w1nt3r           |
|           24 |     5860 | 2024-02-21 | MOUZ NXT            | L   | 0.544      | -            | -                | -                | -         |    -4.80 | dekz, Kaide, mo0n, Sowalio, w1nt3r           |
|           23 |     6118 | 2024-02-17 | GenOne              | W   | 0.517      | -            | -                | -                | -         |     1.85 | dekz, Kaide, mo0n, Sowalio, w1nt3r           |
|           22 |     6331 | 2024-02-13 | Kappa Bar           | W   | 0.491      | -            | -                | -                | -         |     1.47 | dekz, Kaide, mo0n, Sowalio, w1nt3r           |
|           21 |     6393 | 2024-02-12 | DASH                | W   | 0.484      | -            | -                | -                | -         |     3.58 | dekz, Kaide, mo0n, Sowalio, w1nt3r           |
|           20 |     6493 | 2024-02-09 | FORZE Esports       | L   | 0.463      | -            | -                | -                | -         |    -6.56 | dekz, Kaide, mo0n, Sowalio, w1nt3r           |
|           19 |     6511 | 2024-02-08 | AMKAL ESPORTS       | L   | 0.458      | -            | -                | -                | -         |    -2.53 | dekz, Kaide, mo0n, Sowalio, w1nt3r           |
|           18 |     6525 | 2024-02-08 | ex-Guild Eagles     | W   | 0.457      | -            | -                | -                | -         |     8.13 | dekz, Kaide, mo0n, Sowalio, w1nt3r           |
|           17 |     6869 | 2024-02-01 | RoundsGG            | W   | 0.411      | -            | -                | -                | -         |     1.93 | dekz, Kaide, mo0n, Sowalio, w1nt3r           |
|           16 |     6918 | 2024-01-31 | Lilmix              | W   | 0.404      | -            | -                | -                | -         |     5.17 | dekz, Kaide, mo0n, Sowalio, w1nt3r           |
|           15 |     6928 | 2024-01-31 | GamerLegion Academy | W   | 0.404      | -            | -                | -                | -         |     4.57 | dekz, Kaide, mo0n, Sowalio, w1nt3r           |
|           14 |     6962 | 2024-01-30 | Nemiga Gaming       | L   | 0.398      | -            | -                | -                | -         |    -1.78 | dekz, Kaide, mo0n, Sowalio, w1nt3r           |
|           13 |     6968 | 2024-01-30 | Permitta Esports    | W   | 0.398      | -            | -                | -                | -         |     6.99 | dekz, Kaide, mo0n, Sowalio, w1nt3r           |
|           12 |     6975 | 2024-01-30 | ILLYRIANS           | W   | 0.397      | -            | -                | -                | -         |     3.36 | dekz, Kaide, mo0n, Sowalio, w1nt3r           |
|           11 |     6997 | 2024-01-29 | The Chosen Few      | W   | 0.392      | -            | -                | -                | -         |     3.42 | dekz, Kaide, mo0n, Sowalio, w1nt3r           |
|           10 |     7038 | 2024-01-29 | BLEED Esports       | W   | 0.392      | 0.143        | 0.248 (0.014)    | -                | -         |    10.60 | dekz, Kaide, mo0n, Sowalio, w1nt3r           |
|            9 |     7248 | 2024-01-26 | 1win                | W   | 0.371      | 0.371        | 0.050 (0.007)    | -                | -         |     7.20 | dekz, Kaide, mo0n, Sowalio, w1nt3r           |
|            8 |     7351 | 2024-01-24 | GUN5 Esports        | W   | 0.357      | -            | -                | -                | -         |     1.39 | dekz, Kaide, mo0n, Sowalio, w1nt3r           |
|            7 |     7461 | 2024-01-22 | Sashi Esport        | L   | 0.344      | -            | -                | -                | -         |    -3.28 | dekz, Kaide, mo0n, Sowalio, w1nt3r           |
|            6 |     7769 | 2024-01-17 | AMKAL ESPORTS       | L   | 0.312      | -            | -                | -                | -         |    -1.52 | dekz, Kaide, m1racle, Sowalio, w1nt3r        |
|            5 |     7783 | 2024-01-17 | ghoulsW             | W   | 0.311      | -            | -                | -                | -         |     1.00 | fostar, HS, KalubeR, kressy, kristou         |
|            4 |     7802 | 2024-01-17 | Twisted Minds       | W   | 0.311      | -            | -                | -                | -         |     1.51 | D0cC, day0s, KD69z, m4tthi, SpAwNnS          |
|            3 |     7889 | 2024-01-16 | Passion UA          | L   | 0.305      | -            | -                | -                | -         |    -3.35 | jackasmo, jambo, marat2k, s-chilla, zeRRoFIX |
|            2 |     7905 | 2024-01-16 | TSM                 | W   | 0.304      | -            | -                | -                | -         |     3.07 | dekz, Kaide, m1racle, Sowalio, w1nt3r        |
|            1 |     8851 | 2023-12-16 | EYEBALLERS          | L   | 0.098      | -            | -                | -                | -         |    -1.46 | Ao-, dekz, Kaide, Sowalio, YumsaN            |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($2,000.00)
- Divide that value by the 5th highest value among all rosters ($300,806.11)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
