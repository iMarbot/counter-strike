### Roster Details<br />
Team Name: Viperio<br />
Roster: mAnGo, MMS, pandi7o, ReegaN, zodi<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [253](../standings_global.md)<br />
Regional Rank: [161]( ../standings_europe.md)<br />
Final Rank Value:  662.0<br />
<br />
Final Rank Value (662.0) = Starting Rank Value (610.9) + Head To Head Adjustments (51.1)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.000[<sup>1</sup>](#table2)
- Bounty Collected: 0.331[<sup>2</sup>](#table1)
- Opponent Network: 0.094[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.106<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 610.9
- 400 + ( ( 0.106 - 0.000 ) / ( 0.806 - 0.000 ) ) * 1600 = 610.9


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent                    | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins      | H2H Adj. | Roster                                      |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           55 |     1951 | 2024-03-22 | Sashi Esport                | L   | 0.903      | -            | -                | -                | -             |    -3.27 | mAnGo, MMS, pandi7o, ReegaN, zodi           |
|           54 |     1953 | 2024-03-22 | Astralis Talent             | L   | 0.903      | -            | -                | -                | -             |    -6.21 | mAnGo, MMS, pandi7o, ReegaN, zodi           |
|           53 |     2072 | 2024-03-19 | GamerLegion Academy         | L   | 0.883      | -            | -                | -                | -             |    -8.24 | mAnGo, MMS, pandi7o, ReegaN, zodi           |
|           52 |     2122 | 2024-03-17 | Turów Zgorzelec Esport      | L   | 0.872      | -            | -                | -                | -             |    -8.86 | mAnGo, MMS, pandi7o, ReegaN, zodi           |
|           51 |     2208 | 2024-03-15 | LEON Esports                | L   | 0.859      | -            | -                | -                | -             |   -13.05 | mAnGo, MMS, pandi7o, ReegaN, zodi           |
|           50 |     2232 | 2024-03-15 | Astralis Talent             | W   | 0.856      | 0.333        | 0.030 (0.009)    | 0.613 (0.175)    | false (0.000) |    20.37 | mAnGo, MMS, pandi7o, ReegaN, zodi           |
|           49 |     2399 | 2024-03-11 | Preasy Esport               | W   | 0.832      | 0.333        | -                | 0.525 (0.146)    | false (0.000) |    15.87 | mAnGo, MMS, pandi7o, ReegaN, zodi           |
|           48 |     2715 | 2024-03-05 | Alliance                    | L   | 0.789      | -            | -                | -                | -             |    -6.55 | mAnGo, MMS, pandi7o, ReegaN, zodi           |
|           47 |     2785 | 2024-03-03 | MOUZ NXT                    | L   | 0.779      | -            | -                | -                | -             |    -2.29 | mAnGo, MMS, pandi7o, ReegaN, zodi           |
|           46 |     2801 | 2024-03-03 | The Neighbours              | L   | 0.778      | -            | -                | -                | -             |   -11.55 | cryths, mAnGo, MMS, ReegaN, zodi            |
|           45 |     2927 | 2024-03-01 | Dynamo Eclot                | L   | 0.763      | -            | -                | -                | -             |    -1.60 | mAnGo, MMS, pandi7o, ReegaN, zodi           |
|           44 |     2930 | 2024-02-29 | Verdant                     | L   | 0.759      | -            | -                | -                | -             |    -5.96 | cryths, mAnGo, MMS, ReegaN, zodi            |
|           43 |     2931 | 2024-02-29 | Dreams To Legends           | W   | 0.759      | -            | -                | -                | false (0.000) |     3.76 | cryths, mAnGo, MMS, ReegaN, zodi            |
|           42 |     2969 | 2024-02-29 | Illuminar Gaming            | W   | 0.757      | 0.303        | 0.010 (0.002)    | 0.243 (0.056)    | false (0.000) |    15.38 | mAnGo, MMS, pandi7o, ReegaN, zodi           |
|           41 |     2972 | 2024-02-28 | The Last Resort             | L   | 0.753      | -            | -                | -                | -             |   -11.33 | cryths, mAnGo, MMS, ReegaN, zodi            |
|           40 |     3109 | 2024-02-25 | Natus Vincere Junior        | L   | 0.730      | -            | -                | -                | -             |    -6.91 | mAnGo, MMS, pandi7o, ReegaN, zodi           |
|           39 |     3427 | 2024-02-19 | Team Sampi                  | L   | 0.690      | -            | -                | -                | -             |    -3.30 | mAnGo, MMS, pandi7o, ReegaN, zodi           |
|           38 |     3431 | 2024-02-19 | Natus Vincere Junior        | L   | 0.689      | -            | -                | -                | -             |    -6.88 | mAnGo, MMS, pandi7o, ReegaN, zodi           |
|           37 |     3449 | 2024-02-18 | Sashi Esport                | W   | 0.685      | 0.333        | 0.055 (0.013)    | 0.256 (0.058)    | false (0.000) |    13.93 | mAnGo, MMS, pandi7o, ReegaN, zodi           |
|           36 |     3467 | 2024-02-18 | Passion UA                  | W   | 0.683      | 0.303        | 0.114 (0.024)    | 0.980 (0.203)    | false (0.000) |    17.46 | mAnGo, MMS, pandi7o, ReegaN, zodi           |
|           35 |     3504 | 2024-02-17 | Permitta Esports            | L   | 0.677      | -            | -                | -                | -             |    -3.27 | mAnGo, MMS, pandi7o, ReegaN, zodi           |
|           34 |     3568 | 2024-02-15 | Raptors Esports Club        | L   | 0.666      | -            | -                | -                | -             |    -5.71 | cryths, mAnGo, MMS, ReegaN, zodi            |
|           33 |     3608 | 2024-02-15 | Illuminar Gaming            | W   | 0.663      | 0.303        | -                | 0.243 (0.049)    | false (0.000) |    13.77 | mAnGo, MMS, pandi7o, ReegaN, zodi           |
|           32 |     3656 | 2024-02-14 | Team Sampi                  | L   | 0.656      | -            | -                | -                | -             |    -2.65 | mAnGo, MMS, pandi7o, ReegaN, zodi           |
|           31 |     3667 | 2024-02-13 | Souls-Land                  | W   | 0.652      | -            | -                | -                | false (0.000) |     4.43 | cryths, mAnGo, MMS, ReegaN, zodi            |
|           30 |     3753 | 2024-02-11 | NOM Esports                 | L   | 0.638      | -            | -                | -                | -             |   -11.19 | mAnGo, MMS, pandi7o, ReegaN, zodi           |
|           29 |     3765 | 2024-02-10 | Betera Esports              | L   | 0.632      | -            | -                | -                | -             |    -5.49 | mAnGo, MMS, pandi7o, ReegaN, zodi           |
|           28 |     3771 | 2024-02-10 | UNiTY esports (Slovak team) | W   | 0.631      | 0.143        | 0.055 (0.005)    | 0.727 (0.066)    | false (0.000) |    15.95 | mAnGo, MMS, pandi7o, ReegaN, zodi           |
|           27 |     3780 | 2024-02-10 | K10                         | W   | 0.629      | 0.303        | 0.015 (0.003)    | 0.418 (0.080)    | false (0.000) |    15.15 | mAnGo, MMS, pandi7o, ReegaN, zodi           |
|           26 |     3873 | 2024-02-06 | Young Ninjas                | W   | 0.603      | 0.303        | 0.062 (0.011)    | -                | -             |    13.35 | mAnGo, MMS, pandi7o, ReegaN, zodi           |
|           25 |     3969 | 2024-02-03 | Endpoint                    | L   | 0.585      | -            | -                | -                | -             |    -4.29 | mAnGo, MMS, pandi7o, ReegaN, zodi           |
|           24 |     3979 | 2024-02-03 | K10                         | W   | 0.584      | -            | -                | -                | -             |    14.76 | mAnGo, MMS, pandi7o, ReegaN, zodi           |
|           23 |     3990 | 2024-02-03 | Raptors Esports Club        | W   | 0.584      | -            | -                | -                | -             |    14.68 | mAnGo, MMS, pandi7o, ReegaN, zodi           |
|           22 |     4127 | 2024-01-31 | EsmagaB                     | L   | 0.563      | -            | -                | -                | -             |    -3.50 | mAnGo, MMS, pandi7o, ReegaN, zodi           |
|           21 |     4374 | 2024-01-24 | Pera Esports                | L   | 0.519      | -            | -                | -                | -             |    -2.04 | mAnGo, MMS, pandi7o, ReegaN, zodi           |
|           20 |     4429 | 2024-01-23 | Rebels Gaming               | W   | 0.512      | 0.143        | 0.121 (0.009)    | -                | -             |    15.28 | mAnGo, MMS, pandi7o, ReegaN, zodi           |
|           19 |     4434 | 2024-01-23 | Team Sampi                  | W   | 0.511      | 0.143        | 0.108 (0.008)    | 0.709 (0.052)    | -             |    14.89 | mAnGo, MMS, pandi7o, ReegaN, zodi           |
|           18 |     4456 | 2024-01-22 | ALTERNATE aTTaX             | L   | 0.506      | -            | -                | -                | -             |    -1.04 | mAnGo, MMS, pandi7o, ReegaN, zodi           |
|           17 |     4467 | 2024-01-22 | Guild Eagles                | L   | 0.505      | -            | -                | -                | -             |    -0.99 | mAnGo, MMS, pandi7o, ReegaN, zodi           |
|           16 |     4473 | 2024-01-22 | Pera Esports                | L   | 0.505      | -            | -                | -                | -             |    -2.02 | mAnGo, MMS, pandi7o, ReegaN, zodi           |
|           15 |     4935 | 2024-01-12 | The Witchers                | L   | 0.439      | -            | -                | -                | -             |    -3.44 | mAnGo, MMS, pandi7o, ReegaN, zodi           |
|           14 |     5042 | 2024-01-10 | 00 Nation                   | L   | 0.426      | -            | -                | -                | -             |    -8.58 | mAnGo, MMS, pandi7o, ReegaN, zodi           |
|           13 |     5056 | 2024-01-10 | Sashi Esport                | W   | 0.426      | 0.143        | 0.193 (0.012)    | 1.000 (0.061)    | -             |    12.59 | mAnGo, MMS, pandi7o, ReegaN, zodi           |
|           12 |     5166 | 2024-01-07 | Natus Vincere Junior        | L   | 0.404      | -            | -                | -                | -             |    -2.68 | mAnGo, MMS, pandi7o, ReegaN, zodi           |
|           11 |     5219 | 2024-01-03 | Lazer Cats                  | L   | 0.376      | -            | -                | -                | -             |    -7.57 | mAnGo, MMS, pandi7o, ReegaN, zodi           |
|           10 |     5295 | 2023-12-21 | Illuminar Gaming            | L   | 0.291      | -            | -                | -                | -             |    -2.50 | mAnGo, MMS, pandi7o, ReegaN, zodi           |
|            9 |     5762 | 2023-12-09 | Raptors Esports Club        | L   | 0.212      | -            | -                | -                | -             |    -1.25 | JAUSTERE, MMS, papp, ReegaN, zodi           |
|            8 |     5773 | 2023-12-09 | K10                         | L   | 0.211      | -            | -                | -                | -             |    -1.13 | JAUSTERE, MMS, papp, ReegaN, zodi           |
|            7 |     6350 | 2023-11-27 | Grindas                     | L   | 0.132      | -            | -                | -                | -             |    -1.54 | AwwEzz, BaGyZ, MAGILA, prochas, Sidivo      |
|            6 |     6371 | 2023-11-27 | ILIN                        | L   | 0.132      | -            | -                | -                | -             |    -2.41 | abiraju, aviva, fineshine, lampada, meteiru |
|            5 |     6508 | 2023-11-23 | The Chosen Few              | L   | 0.105      | -            | -                | -                | -             |    -0.81 | hybrid, Libido, shaiK, Skrimo, SPELLAN      |
|            4 |     6808 | 2023-11-16 | ARCRED                      | L   | 0.059      | -            | -                | -                | -             |    -0.43 | 1NVISIBLEE, DSSj, hurtslxrd, Ryujin, shg    |
|            3 |     7124 | 2023-11-09 | Team 7AM                    | W   | 0.012      | -            | -                | -                | -             |     0.13 | bevve, choiv7, dobbo, Duplicate, SENSEi     |
|            2 |     7170 | 2023-11-08 | For The Win Esports         | L   | 0.006      | -            | -                | -                | -             |    -0.07 | Ag1l, NOPEEj, pr, shr, stadodo              |
|            1 |     7191 | 2023-11-08 | Entropiq                    | L   | 0.005      | -            | -                | -                | -             |    -0.04 | c0llins, forsyy, Marix, Oxygen, tiziaN      |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($0.00)
- Divide that value by the 5th highest value among all rosters ($158,437.64)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
