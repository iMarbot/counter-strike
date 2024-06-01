### Roster Details<br />
Team Name: Fnatic<br />
Roster: afro, blameF, bodyy, KRIMZ, matys<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [37](../standings_global.md)<br />
Regional Rank: [27]( ../standings_europe.md)<br />
Final Rank Value:  1155.1<br />
<br />
Final Rank Value (1155.1) = Starting Rank Value (1115.2) + Head To Head Adjustments (39.9)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.546[<sup>1</sup>](#table2)
- Bounty Collected: 0.457[<sup>2</sup>](#table1)
- Opponent Network: 0.196[<sup>2</sup>](#table1)
- LAN Wins: 0.207[<sup>2</sup>](#table1)

The average of these factors is 0.351<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1115.2
- 400 + ( ( 0.351 - 0.000 ) / ( 0.786 - 0.000 ) ) * 1600 = 1115.2


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
|           55 |      890 | 2024-05-18 | ENCE                      | L   | 1.000      | -            | -                | -                | -         |    -9.70 | afro, blameF, bodyy, KRIMZ, matys   |
|           54 |      927 | 2024-05-18 | GamerLegion               | L   | 1.000      | -            | -                | -                | -         |   -11.51 | afro, blameF, bodyy, KRIMZ, matys   |
|           53 |      993 | 2024-05-17 | ENCE                      | W   | 1.000      | 0.769        | 0.202 (0.155)    | 0.280 (0.215)    | 0 (0.000) |    21.48 | afro, blameF, bodyy, KRIMZ, matys   |
|           52 |     1867 | 2024-05-03 | 9Pandas                   | L   | 1.000      | -            | -                | -                | -         |   -20.13 | afro, bodyy, KRIMZ, kyuubii, matys  |
|           51 |     1918 | 2024-05-02 | Sashi Esport              | L   | 1.000      | -            | -                | -                | -         |   -12.02 | afro, bodyy, KRIMZ, kyuubii, matys  |
|           50 |     1990 | 2024-05-01 | AMKAL ESPORTS             | W   | 1.000      | 0.384        | 0.146 (0.056)    | 0.565 (0.217)    | 0 (0.000) |    16.14 | afro, bodyy, KRIMZ, kyuubii, matys  |
|           49 |     2007 | 2024-05-01 | PARIVISION                | W   | 1.000      | 0.435        | -                | 0.329 (0.143)    | 0 (0.000) |     8.07 | afro, bodyy, KRIMZ, kyuubii, matys  |
|           48 |     2048 | 2024-04-30 | Nexus Gaming              | W   | 1.000      | 0.384        | -                | 0.825 (0.317)    | 0 (0.000) |     5.08 | afro, bodyy, KRIMZ, kyuubii, matys  |
|           47 |     2203 | 2024-04-27 | Virtus.pro                | L   | 0.982      | -            | -                | -                | -         |    -1.88 | afro, bodyy, KRIMZ, kyuubii, matys  |
|           46 |     2301 | 2024-04-25 | Eternal Fire              | L   | 0.971      | -            | -                | -                | -         |    -0.82 | afro, bodyy, KRIMZ, kyuubii, matys  |
|           45 |     2431 | 2024-04-23 | Virtus.pro                | W   | 0.955      | 0.889        | 0.271 (0.230)    | 0.331 (0.281)    | 1 (0.955) |    28.53 | afro, bodyy, KRIMZ, kyuubii, matys  |
|           44 |     2765 | 2024-04-18 | KOI                       | L   | 0.923      | -            | -                | -                | -         |   -18.08 | afro, bodyy, KRIMZ, kyuubii, matys  |
|           43 |     2824 | 2024-04-17 | Zero Tenacity             | W   | 0.918      | 0.143        | 0.147 (0.019)    | 1.000 (0.131)    | 0 (0.000) |     7.85 | afro, bodyy, KRIMZ, kyuubii, matys  |
|           42 |     3232 | 2024-04-09 | Apeks                     | L   | 0.864      | -            | -                | -                | -         |   -10.87 | afro, bodyy, KRIMZ, kyuubii, matys  |
|           41 |     3282 | 2024-04-08 | Apeks                     | W   | 0.857      | -            | -                | -                | 0 (0.000) |    16.30 | afro, bodyy, KRIMZ, kyuubii, matys  |
|           40 |     3296 | 2024-04-08 | KOI                       | W   | 0.856      | -            | -                | -                | 0 (0.000) |     9.85 | afro, bodyy, KRIMZ, kyuubii, matys  |
|           39 |     3883 | 2024-03-26 | esmagaB                   | L   | 0.771      | -            | -                | -                | -         |   -21.12 | afro, bodyy, KRIMZ, kyuubii, matys  |
|           38 |     4012 | 2024-03-23 | BetBoom Team              | L   | 0.749      | -            | -                | -                | -         |    -5.58 | afro, bodyy, KRIMZ, kyuubii, matys  |
|           37 |     4095 | 2024-03-21 | 3DMAX                     | W   | 0.736      | -            | -                | -                | -         |     5.59 | afro, bodyy, KRIMZ, kyuubii, matys  |
|           36 |     4880 | 2024-03-06 | BLEED Esports             | W   | 0.637      | 0.500        | 0.248 (0.079)    | 0.677 (0.216)    | -         |    12.17 | afro, bodyy, KRIMZ, kyuubii, matys  |
|           35 |     4964 | 2024-03-05 | Young Ninjas              | W   | 0.630      | 0.500        | -                | 0.372 (0.117)    | -         |     5.13 | afro, bodyy, KRIMZ, kyuubii, matys  |
|           34 |     4994 | 2024-03-04 | ILIN                      | W   | 0.625      | -            | -                | -                | -         |     1.11 | afro, bodyy, KRIMZ, kyuubii, matys  |
|           33 |     5020 | 2024-03-04 | PARIVISION                | W   | 0.625      | -            | -                | -                | -         |     4.42 | afro, bodyy, KRIMZ, kyuubii, matys  |
|           32 |     5049 | 2024-03-04 | 3DMAX                     | W   | 0.623      | 0.500        | 0.106 (0.033)    | -                | -         |     5.71 | afro, bodyy, KRIMZ, kyuubii, matys  |
|           31 |     5075 | 2024-03-03 | Gaimin Gladiators         | L   | 0.618      | -            | -                | -                | -         |    -5.87 | afro, bodyy, KRIMZ, kyuubii, matys  |
|           30 |     5082 | 2024-03-03 | AURA                      | W   | 0.617      | -            | -                | -                | -         |     1.61 | afro, bodyy, KRIMZ, kyuubii, matys  |
|           29 |     5105 | 2024-03-03 | ex-Preasy Esport          | W   | 0.616      | 0.500        | 0.052 (0.016)    | 0.381 (0.117)    | -         |     5.37 | afro, bodyy, KRIMZ, kyuubii, matys  |
|           28 |     5123 | 2024-03-02 | B8                        | W   | 0.612      | 0.143        | 0.168 (0.015)    | -                | -         |     9.53 | bodyy, FASHR, KRIMZ, kyuubii, matys |
|           27 |     5164 | 2024-03-02 | HOTU                      | W   | 0.611      | -            | -                | -                | -         |     3.25 | bodyy, FASHR, KRIMZ, kyuubii, matys |
|           26 |     5242 | 2024-03-01 | ALTERNATE aTTaX           | W   | 0.603      | 0.500        | 0.052 (0.016)    | 0.679 (0.205)    | -         |     6.00 | afro, bodyy, KRIMZ, kyuubii, matys  |
|           25 |     5299 | 2024-02-28 | ex-Preasy Esport          | L   | 0.591      | -            | -                | -                | -         |   -13.45 | afro, bodyy, KRIMZ, kyuubii, matys  |
|           24 |     5610 | 2024-02-23 | GamerLegion               | L   | 0.557      | -            | -                | -                | -         |    -5.48 | afro, bodyy, KRIMZ, kyuubii, matys  |
|           23 |     5949 | 2024-02-17 | SAW                       | L   | 0.517      | -            | -                | -                | -         |    -3.56 | afro, bodyy, KRIMZ, kyuubii, matys  |
|           22 |     6003 | 2024-02-16 | KOI                       | L   | 0.509      | -            | -                | -                | -         |   -10.86 | afro, bodyy, KRIMZ, kyuubii, matys  |
|           21 |     6060 | 2024-02-15 | AMKAL ESPORTS             | W   | 0.502      | -            | -                | -                | 1 (0.502) |     9.29 | afro, bodyy, KRIMZ, kyuubii, matys  |
|           20 |     6088 | 2024-02-14 | Virtus.pro                | L   | 0.498      | -            | -                | -                | -         |    -0.66 | afro, bodyy, KRIMZ, kyuubii, matys  |
|           19 |     6107 | 2024-02-14 | BetBoom Team              | W   | 0.496      | 0.143        | 0.390 (0.028)    | -                | 1 (0.496) |    13.01 | afro, bodyy, KRIMZ, kyuubii, matys  |
|           18 |     6296 | 2024-02-09 | 3DMAX                     | L   | 0.464      | -            | -                | -                | -         |   -10.56 | afro, bodyy, KRIMZ, kyuubii, matys  |
|           17 |     6302 | 2024-02-09 | Sprout                    | L   | 0.463      | -            | -                | -                | -         |   -13.61 | afro, bodyy, KRIMZ, kyuubii, matys  |
|           16 |     6308 | 2024-02-09 | Endpoint                  | W   | 0.463      | -            | -                | -                | -         |     3.86 | afro, bodyy, KRIMZ, kyuubii, matys  |
|           15 |     6753 | 2024-01-30 | Insilio                   | L   | 0.398      | -            | -                | -                | -         |    -9.41 | afro, bodyy, KRIMZ, kyuubii, matys  |
|           14 |     6764 | 2024-01-30 | 500                       | W   | 0.397      | -            | -                | -                | -         |     1.60 | afro, bodyy, KRIMZ, kyuubii, matys  |
|           13 |     6788 | 2024-01-29 | ARCRED                    | W   | 0.392      | -            | -                | -                | -         |     1.45 | afro, bodyy, KRIMZ, kyuubii, matys  |
|           12 |     6804 | 2024-01-29 | Lausanne-Sport Esports    | W   | 0.392      | -            | -                | -                | -         |     1.18 | afro, bodyy, KRIMZ, kyuubii, matys  |
|           11 |     7327 | 2024-01-20 | Gaimin Gladiators         | W   | 0.331      | -            | -                | -                | -         |     7.23 | afro, bodyy, KRIMZ, kyuubii, matys  |
|           10 |     7346 | 2024-01-20 | Virtus.pro                | L   | 0.330      | -            | -                | -                | -         |    -0.42 | afro, bodyy, KRIMZ, kyuubii, matys  |
|            9 |     7414 | 2024-01-19 | BIG                       | W   | 0.323      | -            | -                | -                | -         |     8.64 | afro, bodyy, KRIMZ, kyuubii, matys  |
|            8 |     7456 | 2024-01-18 | SINNERS Esports           | W   | 0.318      | -            | -                | -                | -         |     3.48 | afro, bodyy, KRIMZ, kyuubii, matys  |
|            7 |     7474 | 2024-01-18 | SAW                       | L   | 0.317      | -            | -                | -                | -         |    -2.03 | afro, bodyy, KRIMZ, kyuubii, matys  |
|            6 |     8051 | 2024-01-09 | Entropiq                  | W   | 0.259      | -            | -                | -                | -         |     0.59 | afro, bodyy, KRIMZ, kyuubii, matys  |
|            5 |     8055 | 2024-01-09 | ENTERPRISE esports        | L   | 0.259      | -            | -                | -                | -         |    -5.91 | afro, bodyy, KRIMZ, kyuubii, matys  |
|            4 |     8062 | 2024-01-09 | Gaimin Gladiators         | W   | 0.258      | -            | -                | -                | -         |     5.86 | afro, bodyy, KRIMZ, kyuubii, matys  |
|            3 |     8081 | 2024-01-09 | HAVU Gaming               | W   | 0.257      | -            | -                | -                | -         |     1.00 | afro, bodyy, KRIMZ, kyuubii, matys  |
|            2 |     8089 | 2024-01-09 | ex-Turów Zgorzelec Esport | W   | 0.257      | -            | -                | -                | -         |     1.01 | afro, bodyy, KRIMZ, kyuubii, matys  |
|            1 |     8102 | 2024-01-09 | EYEBALLERS                | W   | 0.257      | -            | -                | -                | -         |     1.97 | afro, bodyy, KRIMZ, kyuubii, matys  |

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
