### Roster Details<br />
Team Name: Fnatic<br />
Roster: afro, bodyy, KRIMZ, kyuubii, matys<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [34](../standings_global.md)<br />
Regional Rank: [26]( ../standings_europe.md)<br />
Final Rank Value:  1213.7<br />
<br />
Final Rank Value (1213.7) = Starting Rank Value (1201.1) + Head To Head Adjustments (12.6)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.677[<sup>1</sup>](#table2)
- Bounty Collected: 0.472[<sup>2</sup>](#table1)
- Opponent Network: 0.207[<sup>2</sup>](#table1)
- LAN Wins: 0.259[<sup>2</sup>](#table1)

The average of these factors is 0.404<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1201.1
- 400 + ( ( 0.404 - 0.000 ) / ( 0.806 - 0.000 ) ) * 1600 = 1201.1


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent               | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                              |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           51 |       94 | 2024-05-03 | 9Pandas                | L   | 1.000      | -            | -                | -                | -         |   -22.68 | afro, bodyy, KRIMZ, kyuubii, matys  |
|           50 |      145 | 2024-05-02 | Sashi Esport           | L   | 1.000      | -            | -                | -                | -         |   -13.54 | afro, bodyy, KRIMZ, kyuubii, matys  |
|           49 |      208 | 2024-05-01 | AMKAL ESPORTS          | W   | 1.000      | 0.384        | 0.209 (0.080)    | 0.756 (0.291)    | 0 (0.000) |    14.51 | afro, bodyy, KRIMZ, kyuubii, matys  |
|           48 |      224 | 2024-05-01 | PARIVISION             | W   | 1.000      | 0.435        | -                | 0.374 (0.162)    | 0 (0.000) |     4.86 | afro, bodyy, KRIMZ, kyuubii, matys  |
|           47 |      260 | 2024-04-30 | Nexus Gaming           | W   | 1.000      | 0.384        | -                | 0.772 (0.297)    | 0 (0.000) |     4.22 | afro, bodyy, KRIMZ, kyuubii, matys  |
|           46 |      381 | 2024-04-27 | Virtus.pro             | L   | 1.000      | -            | -                | -                | -         |    -2.54 | afro, bodyy, KRIMZ, kyuubii, matys  |
|           45 |      463 | 2024-04-25 | Eternal Fire           | L   | 1.000      | -            | -                | -                | -         |    -1.52 | afro, bodyy, KRIMZ, kyuubii, matys  |
|           44 |      588 | 2024-04-23 | Virtus.pro             | W   | 1.000      | 0.889        | 0.454 (0.404)    | 0.416 (0.370)    | 1 (1.000) |    29.28 | afro, bodyy, KRIMZ, kyuubii, matys  |
|           43 |      880 | 2024-04-18 | KOI                    | L   | 1.000      | -            | -                | -                | -         |   -20.32 | afro, bodyy, KRIMZ, kyuubii, matys  |
|           42 |      930 | 2024-04-17 | Zero Tenacity          | W   | 1.000      | 0.143        | -                | 1.000 (0.143)    | 0 (0.000) |     4.69 | afro, bodyy, KRIMZ, kyuubii, matys  |
|           41 |     1279 | 2024-04-09 | Apeks                  | L   | 1.000      | -            | -                | -                | -         |   -11.47 | afro, bodyy, KRIMZ, kyuubii, matys  |
|           40 |     1322 | 2024-04-08 | Apeks                  | W   | 1.000      | 0.143        | 0.253 (0.036)    | -                | 0 (0.000) |    20.12 | afro, bodyy, KRIMZ, kyuubii, matys  |
|           39 |     1335 | 2024-04-08 | KOI                    | W   | 1.000      | -            | -                | -                | 0 (0.000) |    10.72 | afro, bodyy, KRIMZ, kyuubii, matys  |
|           38 |     1817 | 2024-03-26 | EsmagaB                | L   | 0.932      | -            | -                | -                | -         |   -26.53 | afro, bodyy, KRIMZ, kyuubii, matys  |
|           37 |     1920 | 2024-03-23 | BetBoom Team           | L   | 0.910      | -            | -                | -                | -         |    -6.92 | afro, bodyy, KRIMZ, kyuubii, matys  |
|           36 |     1989 | 2024-03-21 | 3DMAX                  | W   | 0.898      | -            | -                | -                | 0 (0.000) |     5.33 | afro, bodyy, KRIMZ, kyuubii, matys  |
|           35 |     2701 | 2024-03-05 | Young Ninjas           | W   | 0.791      | 0.500        | 0.074 (0.029)    | 0.338 (0.134)    | -         |     4.76 | afro, bodyy, KRIMZ, kyuubii, matys  |
|           34 |     2726 | 2024-03-04 | ILIN                   | W   | 0.786      | -            | -                | -                | -         |     1.11 | afro, bodyy, KRIMZ, kyuubii, matys  |
|           33 |     2745 | 2024-03-04 | PARIVISION             | W   | 0.786      | -            | -                | -                | -         |     3.12 | afro, bodyy, KRIMZ, kyuubii, matys  |
|           32 |     2768 | 2024-03-04 | 3DMAX                  | W   | 0.784      | 0.500        | 0.062 (0.024)    | 0.393 (0.154)    | -         |     5.08 | afro, bodyy, KRIMZ, kyuubii, matys  |
|           31 |     2792 | 2024-03-03 | Gaimin Gladiators      | L   | 0.779      | -            | -                | -                | -         |    -7.13 | afro, bodyy, KRIMZ, kyuubii, matys  |
|           30 |     2795 | 2024-03-03 | GODSENT                | W   | 0.778      | -            | -                | -                | -         |     2.46 | afro, bodyy, KRIMZ, kyuubii, matys  |
|           29 |     2815 | 2024-03-03 | Preasy Esport          | W   | 0.777      | 0.500        | 0.106 (0.041)    | 0.421 (0.164)    | -         |     6.07 | afro, bodyy, KRIMZ, kyuubii, matys  |
|           28 |     2829 | 2024-03-02 | B8                     | W   | 0.773      | -            | -                | -                | -         |     4.67 | bodyy, FASHR, KRIMZ, kyuubii, matys |
|           27 |     2863 | 2024-03-02 | HOTU                   | W   | 0.772      | -            | -                | -                | -         |     2.04 | bodyy, FASHR, KRIMZ, kyuubii, matys |
|           26 |     2924 | 2024-03-01 | ALTERNATE aTTaX        | W   | 0.764      | 0.500        | 0.110 (0.042)    | 0.723 (0.276)    | -         |     5.11 | afro, bodyy, KRIMZ, kyuubii, matys  |
|           25 |     2974 | 2024-02-28 | Preasy Esport          | L   | 0.752      | -            | -                | -                | -         |   -18.00 | afro, bodyy, KRIMZ, kyuubii, matys  |
|           24 |     3215 | 2024-02-23 | GamerLegion            | L   | 0.718      | -            | -                | -                | -         |    -2.77 | afro, bodyy, KRIMZ, kyuubii, matys  |
|           23 |     3499 | 2024-02-17 | SAW                    | L   | 0.678      | -            | -                | -                | -         |    -4.78 | afro, bodyy, KRIMZ, kyuubii, matys  |
|           22 |     3550 | 2024-02-16 | KOI                    | L   | 0.670      | -            | -                | -                | -         |   -14.34 | afro, bodyy, KRIMZ, kyuubii, matys  |
|           21 |     3600 | 2024-02-15 | AMKAL ESPORTS          | W   | 0.664      | 0.143        | 0.209 (0.020)    | -                | 1 (0.664) |     9.72 | afro, bodyy, KRIMZ, kyuubii, matys  |
|           20 |     3617 | 2024-02-14 | Virtus.pro             | L   | 0.659      | -            | -                | -                | -         |    -1.30 | afro, bodyy, KRIMZ, kyuubii, matys  |
|           19 |     3635 | 2024-02-14 | BetBoom Team           | W   | 0.658      | 0.143        | 0.571 (0.054)    | 0.824 (0.077)    | 1 (0.658) |    16.60 | afro, bodyy, KRIMZ, kyuubii, matys  |
|           18 |     3791 | 2024-02-09 | 3DMAX                  | L   | 0.625      | -            | -                | -                | -         |   -15.82 | afro, bodyy, KRIMZ, kyuubii, matys  |
|           17 |     3799 | 2024-02-09 | Endpoint               | W   | 0.624      | -            | -                | -                | -         |     2.37 | afro, bodyy, KRIMZ, kyuubii, matys  |
|           16 |     4139 | 2024-01-30 | Insilio                | L   | 0.559      | -            | -                | -                | -         |   -14.45 | afro, bodyy, KRIMZ, kyuubii, matys  |
|           15 |     4147 | 2024-01-30 | 500                    | W   | 0.558      | -            | -                | -                | -         |     1.67 | afro, bodyy, KRIMZ, kyuubii, matys  |
|           14 |     4164 | 2024-01-29 | ARCRED                 | W   | 0.553      | -            | -                | -                | -         |     1.60 | afro, bodyy, KRIMZ, kyuubii, matys  |
|           13 |     4177 | 2024-01-29 | Lausanne-Sport Esports | W   | 0.553      | -            | -                | -                | -         |     1.04 | afro, bodyy, KRIMZ, kyuubii, matys  |
|           12 |     4544 | 2024-01-20 | Gaimin Gladiators      | W   | 0.492      | -            | -                | -                | -         |    11.22 | afro, bodyy, KRIMZ, kyuubii, matys  |
|           11 |     4554 | 2024-01-20 | Virtus.pro             | L   | 0.491      | -            | -                | -                | -         |    -0.96 | afro, bodyy, KRIMZ, kyuubii, matys  |
|           10 |     4606 | 2024-01-19 | BIG                    | W   | 0.484      | 0.143        | 0.470 (0.033)    | -                | -         |    11.89 | afro, bodyy, KRIMZ, kyuubii, matys  |
|            9 |     4644 | 2024-01-18 | SINNERS Esports        | W   | 0.479      | -            | -                | -                | -         |     3.56 | afro, bodyy, KRIMZ, kyuubii, matys  |
|            8 |     4660 | 2024-01-18 | SAW                    | L   | 0.478      | -            | -                | -                | -         |    -2.82 | afro, bodyy, KRIMZ, kyuubii, matys  |
|            7 |     5067 | 2024-01-09 | Entropiq               | W   | 0.420      | -            | -                | -                | -         |     1.26 | afro, bodyy, KRIMZ, kyuubii, matys  |
|            6 |     5074 | 2024-01-09 | Gaimin Gladiators      | W   | 0.419      | -            | -                | -                | -         |    10.27 | afro, bodyy, KRIMZ, kyuubii, matys  |
|            5 |     5086 | 2024-01-09 | HAVU Gaming            | W   | 0.418      | -            | -                | -                | -         |     1.83 | afro, bodyy, KRIMZ, kyuubii, matys  |
|            4 |     5093 | 2024-01-09 | Turów Zgorzelec Esport | W   | 0.418      | -            | -                | -                | -         |     1.35 | afro, bodyy, KRIMZ, kyuubii, matys  |
|            3 |     5103 | 2024-01-09 | EYEBALLERS             | W   | 0.418      | -            | -                | -                | -         |     2.62 | afro, bodyy, KRIMZ, kyuubii, matys  |
|            2 |     6249 | 2023-11-29 | ENCE                   | L   | 0.145      | -            | -                | -                | -         |    -4.19 | afro, bodyy, KRIMZ, kyuubii, matys  |
|            1 |     6278 | 2023-11-29 | GamerLegion            | L   | 0.144      | -            | -                | -                | -         |    -0.46 | afro, bodyy, KRIMZ, kyuubii, matys  |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($52,922.45)
- Divide that value by the 5th highest value among all rosters ($158,437.64)
- The final value (0.33) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-05-05 |      1.000 | $7,000.00      | $7,000.00       |
| 2024-05-04 |      1.000 | $2,000.00      | $2,000.00       |
| 2024-05-02 |      1.000 | $3,500.00      | $3,500.00       |
| 2024-03-05 |      0.791 | $50,000.00     | $39,567.13      |
| 2023-12-03 |      0.171 | $5,000.00      | $855.32         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
