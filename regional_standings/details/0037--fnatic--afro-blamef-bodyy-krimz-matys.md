### Roster Details<br />
Team Name: Fnatic<br />
Roster: afro, blameF, bodyy, KRIMZ, matys<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [37](../standings_global.md)<br />
Regional Rank: [27]( ../standings_europe.md)<br />
Final Rank Value:  1156.8<br />
<br />
Final Rank Value (1156.8) = Starting Rank Value (1116.2) + Head To Head Adjustments (40.6)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.546[<sup>1</sup>](#table2)
- Bounty Collected: 0.457[<sup>2</sup>](#table1)
- Opponent Network: 0.200[<sup>2</sup>](#table1)
- LAN Wins: 0.207[<sup>2</sup>](#table1)

The average of these factors is 0.352<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1116.2
- 400 + ( ( 0.352 - 0.000 ) / ( 0.787 - 0.000 ) ) * 1600 = 1116.2


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent                  | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                              |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           55 |      902 | 2024-05-18 | ENCE                      | L   | 1.000      | -            | -                | -                | -         |    -9.70 | afro, blameF, bodyy, KRIMZ, matys   |
|           54 |      939 | 2024-05-18 | GamerLegion               | L   | 1.000      | -            | -                | -                | -         |   -11.64 | afro, blameF, bodyy, KRIMZ, matys   |
|           53 |     1005 | 2024-05-17 | ENCE                      | W   | 1.000      | 0.769        | 0.202 (0.155)    | 0.280 (0.215)    | 0 (0.000) |    21.48 | afro, blameF, bodyy, KRIMZ, matys   |
|           52 |     1891 | 2024-05-03 | 9Pandas                   | L   | 1.000      | -            | -                | -                | -         |   -19.72 | afro, bodyy, KRIMZ, kyuubii, matys  |
|           51 |     1945 | 2024-05-02 | Sashi Esport              | L   | 1.000      | -            | -                | -                | -         |   -12.10 | afro, bodyy, KRIMZ, kyuubii, matys  |
|           50 |     2020 | 2024-05-01 | AMKAL ESPORTS             | W   | 1.000      | 0.384        | 0.146 (0.056)    | 0.565 (0.217)    | 0 (0.000) |    16.13 | afro, bodyy, KRIMZ, kyuubii, matys  |
|           49 |     2038 | 2024-05-01 | PARIVISION                | W   | 1.000      | 0.435        | -                | 0.329 (0.143)    | 0 (0.000) |     7.94 | afro, bodyy, KRIMZ, kyuubii, matys  |
|           48 |     2082 | 2024-04-30 | Nexus Gaming              | W   | 1.000      | 0.384        | -                | 0.857 (0.329)    | 0 (0.000) |     5.20 | afro, bodyy, KRIMZ, kyuubii, matys  |
|           47 |     2238 | 2024-04-27 | Virtus.pro                | L   | 0.982      | -            | -                | -                | -         |    -1.89 | afro, bodyy, KRIMZ, kyuubii, matys  |
|           46 |     2338 | 2024-04-25 | Eternal Fire              | L   | 0.971      | -            | -                | -                | -         |    -0.84 | afro, bodyy, KRIMZ, kyuubii, matys  |
|           45 |     2479 | 2024-04-23 | Virtus.pro                | W   | 0.955      | 0.889        | 0.271 (0.230)    | 0.331 (0.281)    | 1 (0.955) |    28.52 | afro, bodyy, KRIMZ, kyuubii, matys  |
|           44 |     2821 | 2024-04-18 | KOI                       | L   | 0.923      | -            | -                | -                | -         |   -17.69 | afro, bodyy, KRIMZ, kyuubii, matys  |
|           43 |     2881 | 2024-04-17 | Zero Tenacity             | W   | 0.918      | 0.143        | 0.147 (0.019)    | 1.000 (0.131)    | 0 (0.000) |     7.57 | afro, bodyy, KRIMZ, kyuubii, matys  |
|           42 |     3310 | 2024-04-09 | Apeks                     | L   | 0.864      | -            | -                | -                | -         |   -11.01 | afro, bodyy, KRIMZ, kyuubii, matys  |
|           41 |     3362 | 2024-04-08 | Apeks                     | W   | 0.857      | -            | -                | -                | 0 (0.000) |    16.14 | afro, bodyy, KRIMZ, kyuubii, matys  |
|           40 |     3377 | 2024-04-08 | KOI                       | W   | 0.856      | -            | -                | -                | 0 (0.000) |     9.92 | afro, bodyy, KRIMZ, kyuubii, matys  |
|           39 |     3980 | 2024-03-26 | esmagaB                   | L   | 0.771      | -            | -                | -                | -         |   -21.01 | afro, bodyy, KRIMZ, kyuubii, matys  |
|           38 |     4110 | 2024-03-23 | BetBoom Team              | L   | 0.749      | -            | -                | -                | -         |    -5.55 | afro, bodyy, KRIMZ, kyuubii, matys  |
|           37 |     4194 | 2024-03-21 | 3DMAX                     | W   | 0.736      | -            | -                | -                | -         |     5.61 | afro, bodyy, KRIMZ, kyuubii, matys  |
|           36 |     5011 | 2024-03-06 | BLEED Esports             | W   | 0.637      | 0.500        | 0.248 (0.079)    | 0.714 (0.227)    | -         |    12.24 | afro, bodyy, KRIMZ, kyuubii, matys  |
|           35 |     5107 | 2024-03-05 | Young Ninjas              | W   | 0.630      | 0.500        | -                | 0.372 (0.117)    | -         |     5.08 | afro, bodyy, KRIMZ, kyuubii, matys  |
|           34 |     5140 | 2024-03-04 | ILIN                      | W   | 0.625      | -            | -                | -                | -         |     1.18 | afro, bodyy, KRIMZ, kyuubii, matys  |
|           33 |     5166 | 2024-03-04 | PARIVISION                | W   | 0.625      | -            | -                | -                | -         |     4.40 | afro, bodyy, KRIMZ, kyuubii, matys  |
|           32 |     5195 | 2024-03-04 | 3DMAX                     | W   | 0.623      | 0.500        | 0.106 (0.033)    | -                | -         |     5.72 | afro, bodyy, KRIMZ, kyuubii, matys  |
|           31 |     5221 | 2024-03-03 | Gaimin Gladiators         | L   | 0.618      | -            | -                | -                | -         |    -5.85 | afro, bodyy, KRIMZ, kyuubii, matys  |
|           30 |     5228 | 2024-03-03 | AURA                      | W   | 0.617      | -            | -                | -                | -         |     1.64 | afro, bodyy, KRIMZ, kyuubii, matys  |
|           29 |     5253 | 2024-03-03 | ex-Preasy Esport          | W   | 0.616      | 0.500        | 0.052 (0.016)    | 0.381 (0.117)    | -         |     5.43 | afro, bodyy, KRIMZ, kyuubii, matys  |
|           28 |     5271 | 2024-03-02 | B8                        | W   | 0.612      | 0.143        | 0.168 (0.015)    | -                | -         |     9.54 | bodyy, FASHR, KRIMZ, kyuubii, matys |
|           27 |     5312 | 2024-03-02 | HOTU                      | W   | 0.611      | -            | -                | -                | -         |     3.37 | bodyy, FASHR, KRIMZ, kyuubii, matys |
|           26 |     5391 | 2024-03-01 | ALTERNATE aTTaX           | W   | 0.603      | 0.500        | 0.052 (0.016)    | 0.735 (0.222)    | -         |     5.58 | afro, bodyy, KRIMZ, kyuubii, matys  |
|           25 |     5450 | 2024-02-28 | ex-Preasy Esport          | L   | 0.591      | -            | -                | -                | -         |   -13.40 | afro, bodyy, KRIMZ, kyuubii, matys  |
|           24 |     5770 | 2024-02-23 | GamerLegion               | L   | 0.557      | -            | -                | -                | -         |    -5.53 | afro, bodyy, KRIMZ, kyuubii, matys  |
|           23 |     6122 | 2024-02-17 | SAW                       | L   | 0.517      | -            | -                | -                | -         |    -3.58 | afro, bodyy, KRIMZ, kyuubii, matys  |
|           22 |     6179 | 2024-02-16 | KOI                       | L   | 0.509      | -            | -                | -                | -         |   -10.80 | afro, bodyy, KRIMZ, kyuubii, matys  |
|           21 |     6241 | 2024-02-15 | AMKAL ESPORTS             | W   | 0.502      | -            | -                | -                | 1 (0.502) |     9.32 | afro, bodyy, KRIMZ, kyuubii, matys  |
|           20 |     6269 | 2024-02-14 | Virtus.pro                | L   | 0.498      | -            | -                | -                | -         |    -0.66 | afro, bodyy, KRIMZ, kyuubii, matys  |
|           19 |     6288 | 2024-02-14 | BetBoom Team              | W   | 0.496      | 0.143        | 0.390 (0.028)    | -                | 1 (0.496) |    13.03 | afro, bodyy, KRIMZ, kyuubii, matys  |
|           18 |     6484 | 2024-02-09 | 3DMAX                     | L   | 0.464      | -            | -                | -                | -         |   -10.56 | afro, bodyy, KRIMZ, kyuubii, matys  |
|           17 |     6490 | 2024-02-09 | Sprout                    | L   | 0.463      | -            | -                | -                | -         |   -13.55 | afro, bodyy, KRIMZ, kyuubii, matys  |
|           16 |     6496 | 2024-02-09 | Endpoint                  | W   | 0.463      | -            | -                | -                | -         |     3.91 | afro, bodyy, KRIMZ, kyuubii, matys  |
|           15 |     6967 | 2024-01-30 | Insilio                   | L   | 0.398      | -            | -                | -                | -         |    -9.51 | afro, bodyy, KRIMZ, kyuubii, matys  |
|           14 |     6980 | 2024-01-30 | 500                       | W   | 0.397      | -            | -                | -                | -         |     1.60 | afro, bodyy, KRIMZ, kyuubii, matys  |
|           13 |     7004 | 2024-01-29 | ARCRED                    | W   | 0.392      | -            | -                | -                | -         |     1.45 | afro, bodyy, KRIMZ, kyuubii, matys  |
|           12 |     7020 | 2024-01-29 | Lausanne-Sport Esports    | W   | 0.392      | -            | -                | -                | -         |     1.33 | afro, bodyy, KRIMZ, kyuubii, matys  |
|           11 |     7571 | 2024-01-20 | Gaimin Gladiators         | W   | 0.331      | -            | -                | -                | -         |     7.24 | afro, bodyy, KRIMZ, kyuubii, matys  |
|           10 |     7590 | 2024-01-20 | Virtus.pro                | L   | 0.330      | -            | -                | -                | -         |    -0.42 | afro, bodyy, KRIMZ, kyuubii, matys  |
|            9 |     7660 | 2024-01-19 | BIG                       | W   | 0.323      | -            | -                | -                | -         |     8.55 | afro, bodyy, KRIMZ, kyuubii, matys  |
|            8 |     7704 | 2024-01-18 | SINNERS Esports           | W   | 0.318      | -            | -                | -                | -         |     3.79 | afro, bodyy, KRIMZ, kyuubii, matys  |
|            7 |     7722 | 2024-01-18 | SAW                       | L   | 0.317      | -            | -                | -                | -         |    -2.05 | afro, bodyy, KRIMZ, kyuubii, matys  |
|            6 |     8305 | 2024-01-09 | Entropiq                  | W   | 0.259      | -            | -                | -                | -         |     0.59 | afro, bodyy, KRIMZ, kyuubii, matys  |
|            5 |     8309 | 2024-01-09 | ENTERPRISE esports        | L   | 0.259      | -            | -                | -                | -         |    -5.76 | afro, bodyy, KRIMZ, kyuubii, matys  |
|            4 |     8316 | 2024-01-09 | Gaimin Gladiators         | W   | 0.258      | -            | -                | -                | -         |     5.87 | afro, bodyy, KRIMZ, kyuubii, matys  |
|            3 |     8335 | 2024-01-09 | HAVU Gaming               | W   | 0.257      | -            | -                | -                | -         |     1.00 | afro, bodyy, KRIMZ, kyuubii, matys  |
|            2 |     8343 | 2024-01-09 | ex-Turów Zgorzelec Esport | W   | 0.257      | -            | -                | -                | -         |     1.12 | afro, bodyy, KRIMZ, kyuubii, matys  |
|            1 |     8356 | 2024-01-09 | EYEBALLERS                | W   | 0.257      | -            | -                | -                | -         |     1.98 | afro, bodyy, KRIMZ, kyuubii, matys  |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($44,347.22)
- Divide that value by the 5th highest value among all rosters ($300,806.11)
- The final value (0.15) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-05-12 |      1.000 | $7,000.00      | $7,000.00       |
| 2024-05-04 |      1.000 | $2,000.00      | $2,000.00       |
| 2024-05-02 |      1.000 | $3,500.00      | $3,500.00       |
| 2024-03-06 |      0.637 | $50,000.00     | $31,847.22      |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
