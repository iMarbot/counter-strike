### Roster Details<br />
Team Name: RUBY<br />
Roster: dekz, Kaide, mo0n, Sowalio, w1nt3r<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [70](../standings_global.md)<br />
Regional Rank: [48]( ../standings_europe.md)<br />
Final Rank Value:  947.8<br />
<br />
Final Rank Value (947.8) = Starting Rank Value (907.3) + Head To Head Adjustments (40.5)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.341[<sup>1</sup>](#table2)
- Bounty Collected: 0.400[<sup>2</sup>](#table1)
- Opponent Network: 0.255[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.249<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 907.3
- 400 + ( ( 0.249 - 0.000 ) / ( 0.786 - 0.000 ) ) * 1600 = 907.3


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
|           70 |      128 | 2024-05-28 | MOUZ NXT            | L   | 1.000      | -            | -                | -                | -         |   -12.96 | dekz, Kaide, mo0n, Sowalio, w1nt3r           |
|           69 |      226 | 2024-05-26 | Zero Tenacity       | L   | 1.000      | -            | -                | -                | -         |   -11.59 | dekz, Kaide, mo0n, Sowalio, w1nt3r           |
|           68 |      254 | 2024-05-25 | B8                  | L   | 1.000      | -            | -                | -                | -         |    -6.81 | dekz, Kaide, mo0n, Sowalio, w1nt3r           |
|           67 |      413 | 2024-05-23 | Team PeeP           | W   | 1.000      | -            | -                | -                | 0 (0.000) |     4.32 | dekz, Kaide, mo0n, Sowalio, w1nt3r           |
|           66 |      511 | 2024-05-22 | FAVBET Team         | L   | 1.000      | -            | -                | -                | -         |   -14.35 | dekz, Kaide, mo0n, Sowalio, w1nt3r           |
|           65 |      624 | 2024-05-21 | Endpoint            | W   | 1.000      | 0.435        | 0.012 (0.005)    | 0.718 (0.312)    | 0 (0.000) |     9.87 | dekz, Kaide, mo0n, Sowalio, w1nt3r           |
|           64 |      672 | 2024-05-20 | LEON Esports        | W   | 1.000      | 0.372        | -                | 0.564 (0.210)    | 0 (0.000) |     6.29 | dekz, Kaide, mo0n, Sowalio, w1nt3r           |
|           63 |      728 | 2024-05-19 | LODIS               | W   | 1.000      | -            | -                | -                | 0 (0.000) |     3.11 | dekz, Kaide, mo0n, Sowalio, w1nt3r           |
|           62 |     1441 | 2024-05-11 | 9Pandas             | L   | 1.000      | -            | -                | -                | -         |   -11.20 | dekz, Kaide, mo0n, Sowalio, w1nt3r           |
|           61 |     1533 | 2024-05-10 | Nemiga Gaming       | W   | 1.000      | 0.435        | 0.366 (0.159)    | 0.830 (0.361)    | 0 (0.000) |    24.06 | dekz, Kaide, mo0n, Sowalio, w1nt3r           |
|           60 |     1643 | 2024-05-08 | GenOne              | W   | 1.000      | 0.372        | -                | 0.442 (0.165)    | 0 (0.000) |     5.61 | dekz, Kaide, mo0n, Sowalio, w1nt3r           |
|           59 |     1679 | 2024-05-07 | Insilio             | W   | 1.000      | 0.435        | 0.010 (0.004)    | 0.717 (0.312)    | 0 (0.000) |    17.04 | dekz, Kaide, mo0n, Sowalio, w1nt3r           |
|           58 |     1760 | 2024-05-05 | LEON Esports        | W   | 1.000      | -            | -                | -                | 0 (0.000) |     7.71 | dekz, Kaide, mo0n, Sowalio, w1nt3r           |
|           57 |     1774 | 2024-05-05 | HAVU Gaming         | W   | 1.000      | -            | -                | -                | 0 (0.000) |     7.38 | dekz, Kaide, mo0n, Sowalio, w1nt3r           |
|           56 |     1825 | 2024-05-04 | FORZE Youngsters    | W   | 1.000      | -            | -                | -                | 0 (0.000) |     1.54 | dekz, Kaide, mo0n, Sowalio, w1nt3r           |
|           55 |     1887 | 2024-05-03 | V1dar Gaming        | W   | 1.000      | 0.435        | -                | 0.567 (0.246)    | -         |     8.31 | dekz, Kaide, mo0n, Sowalio, w1nt3r           |
|           54 |     1972 | 2024-05-01 | DMS                 | L   | 1.000      | -            | -                | -                | -         |   -19.88 | dekz, Kaide, mo0n, Sowalio, w1nt3r           |
|           53 |     2003 | 2024-05-01 | GamerLegion Academy | L   | 1.000      | -            | -                | -                | -         |   -19.54 | dekz, Kaide, mo0n, Sowalio, w1nt3r           |
|           52 |     2061 | 2024-04-29 | RoundsGG            | W   | 0.997      | -            | -                | -                | -         |     3.73 | dekz, Kaide, mo0n, Sowalio, w1nt3r           |
|           51 |     2180 | 2024-04-27 | Astralis Talent     | W   | 0.983      | -            | -                | -                | -         |     1.40 | dekz, Kaide, mo0n, Sowalio, w1nt3r           |
|           50 |     2312 | 2024-04-25 | MOUZ NXT            | L   | 0.970      | -            | -                | -                | -         |   -11.55 | dekz, Kaide, mo0n, Sowalio, w1nt3r           |
|           49 |     2364 | 2024-04-24 | esmagaB             | L   | 0.964      | -            | -                | -                | -         |   -21.66 | dekz, Kaide, mo0n, Sowalio, w1nt3r           |
|           48 |     2418 | 2024-04-23 | GenOne              | W   | 0.956      | -            | -                | -                | -         |     4.42 | dekz, Kaide, mo0n, Sowalio, w1nt3r           |
|           47 |     2428 | 2024-04-23 | Permitta Esports    | W   | 0.956      | 0.372        | 0.029 (0.010)    | 1.000 (0.356)    | -         |    14.85 | dekz, Kaide, mo0n, Sowalio, w1nt3r           |
|           46 |     2470 | 2024-04-22 | GUN5 Esports        | W   | 0.948      | -            | -                | -                | -         |     4.73 | dekz, Kaide, mo0n, Sowalio, w1nt3r           |
|           45 |     2594 | 2024-04-20 | Zero Tenacity       | L   | 0.936      | -            | -                | -                | -         |   -13.71 | dekz, kaide, mo0n, Sowalio, w1nt3r           |
|           44 |     2754 | 2024-04-18 | Sashi Esport        | L   | 0.924      | -            | -                | -                | -         |   -10.11 | dekz, Kaide, mo0n, Sowalio, w1nt3r           |
|           43 |     2766 | 2024-04-18 | Aurora Gaming       | W   | 0.923      | 0.143        | 0.492 (0.065)    | -                | -         |    27.14 | dekz, Kaide, mo0n, Sowalio, w1nt3r           |
|           42 |     2773 | 2024-04-18 | NOM Esports         | W   | 0.923      | -            | -                | -                | -         |     5.06 | dekz, kaide, mo0n, Sowalio, w1nt3r           |
|           41 |     2829 | 2024-04-17 | Team Falcons        | W   | 0.918      | 0.143        | 0.355 (0.047)    | -                | -         |    27.49 | dekz, Kaide, mo0n, Sowalio, w1nt3r           |
|           40 |     2870 | 2024-04-17 | JANO Esports        | W   | 0.915      | -            | -                | -                | -         |     8.08 | dekz, kaide, mo0n, Sowalio, w1nt3r           |
|           39 |     3044 | 2024-04-13 | ARCRED              | L   | 0.889      | -            | -                | -                | -         |   -18.20 | dekz, Kaide, mo0n, Sowalio, w1nt3r           |
|           38 |     3345 | 2024-04-07 | Insilio             | W   | 0.849      | -            | -                | -                | -         |    15.11 | dekz, Kaide, mo0n, Sowalio, w1nt3r           |
|           37 |     3862 | 2024-03-26 | brazylijski luz     | L   | 0.771      | -            | -                | -                | -         |   -16.13 | dekz, Kaide, mo0n, Sowalio, w1nt3r           |
|           36 |     4168 | 2024-03-19 | Sashi Esport        | L   | 0.724      | -            | -                | -                | -         |    -8.25 | dekz, Kaide, mo0n, Sowalio, w1nt3r           |
|           35 |     4331 | 2024-03-16 | Permitta Esports    | W   | 0.703      | 0.371        | 0.029 (0.007)    | 1.000 (0.261)    | -         |    12.67 | dekz, Kaide, mo0n, Sowalio, w1nt3r           |
|           34 |     4616 | 2024-03-11 | Nexus Gaming        | L   | 0.671      | -            | -                | -                | -         |   -10.32 | dekz, Kaide, mo0n, Sowalio, w1nt3r           |
|           33 |     4709 | 2024-03-09 | Team Spirit Academy | W   | 0.657      | -            | -                | -                | -         |     7.17 | dekz, Kaide, mo0n, Sowalio, w1nt3r           |
|           32 |     4749 | 2024-03-08 | ARCRED              | W   | 0.651      | 0.371        | -                | 0.630 (0.152)    | -         |     6.83 | dekz, Kaide, mo0n, Sowalio, w1nt3r           |
|           31 |     5022 | 2024-03-04 | Johnny Speeds       | L   | 0.625      | -            | -                | -                | -         |    -7.67 | dekz, Kaide, mo0n, Sowalio, w1nt3r           |
|           30 |     5165 | 2024-03-02 | ILIN                | L   | 0.611      | -            | -                | -                | -         |   -16.90 | dekz, Kaide, mo0n, Sowalio, w1nt3r           |
|           29 |     5282 | 2024-02-29 | INGLORIOUS          | W   | 0.597      | -            | -                | -                | -         |     5.46 | dekz, Kaide, mo0n, Sowalio, w1nt3r           |
|           28 |     5307 | 2024-02-28 | Permitta Esports    | L   | 0.591      | -            | -                | -                | -         |    -8.81 | dekz, Kaide, mo0n, Sowalio, w1nt3r           |
|           27 |     5319 | 2024-02-28 | ENTERPRISE esports  | W   | 0.591      | 0.371        | -                | 0.809 (0.177)    | -         |     9.63 | dekz, Kaide, mo0n, Sowalio, w1nt3r           |
|           26 |     5358 | 2024-02-27 | Team Spirit Academy | L   | 0.584      | -            | -                | -                | -         |   -13.04 | dekz, Kaide, mo0n, Sowalio, w1nt3r           |
|           25 |     5370 | 2024-02-27 | ALTERNATE aTTaX     | W   | 0.584      | 0.143        | 0.052 (0.004)    | -                | -         |     9.96 | dekz, Kaide, mo0n, Sowalio, w1nt3r           |
|           24 |     5406 | 2024-02-26 | ThunderFlash        | W   | 0.578      | -            | -                | -                | -         |     6.45 | dekz, Kaide, mo0n, Sowalio, w1nt3r           |
|           23 |     5697 | 2024-02-21 | MOUZ NXT            | L   | 0.544      | -            | -                | -                | -         |    -4.98 | dekz, Kaide, mo0n, Sowalio, w1nt3r           |
|           22 |     5945 | 2024-02-17 | GenOne              | W   | 0.517      | -            | -                | -                | -         |     1.84 | dekz, Kaide, mo0n, Sowalio, w1nt3r           |
|           21 |     6147 | 2024-02-13 | Kappa Bar           | W   | 0.491      | -            | -                | -                | -         |     1.46 | dekz, Kaide, mo0n, Sowalio, w1nt3r           |
|           20 |     6206 | 2024-02-12 | DASH                | W   | 0.484      | -            | -                | -                | -         |     3.43 | dekz, Kaide, mo0n, Sowalio, w1nt3r           |
|           19 |     6305 | 2024-02-09 | FORZE Esports       | L   | 0.463      | -            | -                | -                | -         |    -6.24 | dekz, Kaide, mo0n, Sowalio, w1nt3r           |
|           18 |     6323 | 2024-02-08 | AMKAL ESPORTS       | L   | 0.458      | -            | -                | -                | -         |    -2.54 | dekz, Kaide, mo0n, Sowalio, w1nt3r           |
|           17 |     6337 | 2024-02-08 | ex-Guild Eagles     | W   | 0.457      | -            | -                | -                | -         |     8.01 | dekz, Kaide, mo0n, Sowalio, w1nt3r           |
|           16 |     6664 | 2024-02-01 | RoundsGG            | W   | 0.411      | -            | -                | -                | -         |     1.75 | dekz, Kaide, mo0n, Sowalio, w1nt3r           |
|           15 |     6707 | 2024-01-31 | Lilmix              | W   | 0.404      | -            | -                | -                | -         |     1.35 | dekz, Kaide, mo0n, Sowalio, w1nt3r           |
|           14 |     6716 | 2024-01-31 | GamerLegion Academy | W   | 0.404      | 0.371        | 0.018 (0.003)    | -                | -         |     4.60 | dekz, Kaide, mo0n, Sowalio, w1nt3r           |
|           13 |     6749 | 2024-01-30 | Nemiga Gaming       | L   | 0.398      | -            | -                | -                | -         |    -1.73 | dekz, Kaide, mo0n, Sowalio, w1nt3r           |
|           12 |     6754 | 2024-01-30 | Permitta Esports    | W   | 0.398      | -            | -                | -                | -         |     6.84 | dekz, Kaide, mo0n, Sowalio, w1nt3r           |
|           11 |     6759 | 2024-01-30 | ILLYRIANS           | W   | 0.397      | -            | -                | -                | -         |     3.31 | dekz, Kaide, mo0n, Sowalio, w1nt3r           |
|           10 |     6781 | 2024-01-29 | The Chosen Few      | W   | 0.392      | -            | -                | -                | -         |     3.69 | dekz, Kaide, mo0n, Sowalio, w1nt3r           |
|            9 |     6822 | 2024-01-29 | BLEED Esports       | W   | 0.392      | 0.143        | 0.248 (0.014)    | -                | -         |    10.55 | dekz, Kaide, mo0n, Sowalio, w1nt3r           |
|            8 |     7118 | 2024-01-24 | GUN5 Esports        | W   | 0.357      | -            | -                | -                | -         |     1.33 | dekz, Kaide, mo0n, Sowalio, w1nt3r           |
|            7 |     7219 | 2024-01-22 | Sashi Esport        | L   | 0.344      | -            | -                | -                | -         |    -3.40 | dekz, Kaide, mo0n, Sowalio, w1nt3r           |
|            6 |     7520 | 2024-01-17 | AMKAL ESPORTS       | L   | 0.312      | -            | -                | -                | -         |    -1.61 | dekz, Kaide, m1racle, Sowalio, w1nt3r        |
|            5 |     7534 | 2024-01-17 | ghoulsW             | W   | 0.311      | -            | -                | -                | -         |     0.96 | fostar, HS, KalubeR, kressy, kristou         |
|            4 |     7553 | 2024-01-17 | Twisted Minds       | W   | 0.311      | -            | -                | -                | -         |     1.44 | D0cC, day0s, KD69z, m4tthi, SpAwNnS          |
|            3 |     7640 | 2024-01-16 | Passion UA          | L   | 0.305      | -            | -                | -                | -         |    -3.59 | jackasmo, jambo, marat2k, s-chilla, zeRRoFIX |
|            2 |     7656 | 2024-01-16 | TSM                 | W   | 0.304      | -            | -                | -                | -         |     2.75 | dekz, Kaide, m1racle, Sowalio, w1nt3r        |
|            1 |     8591 | 2023-12-16 | EYEBALLERS          | L   | 0.098      | -            | -                | -                | -         |    -1.51 | Ao-, dekz, Kaide, Sowalio, YumsaN            |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($3,527.22)
- Divide that value by the 5th highest value among all rosters ($300,806.11)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-05-12 |      1.000 | $2,000.00      | $2,000.00       |
| 2024-03-25 |      0.764 | $2,000.00      | $1,527.22       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
