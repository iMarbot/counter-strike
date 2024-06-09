### Roster Details<br />
Team Name: BetBoom Team<br />
Roster: KaiR0N-, Magnojez, nafany, s1ren, zorte<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [23](../standings_global.md)<br />
Regional Rank: [16]( ../standings_europe.md)<br />
Final Rank Value:  1325.9<br />
<br />
Final Rank Value (1325.9) = Starting Rank Value (1433.6) + Head To Head Adjustments (-107.6)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.710[<sup>1</sup>](#table2)
- Bounty Collected: 0.537[<sup>2</sup>](#table1)
- Opponent Network: 0.367[<sup>2</sup>](#table1)
- LAN Wins: 0.421[<sup>2</sup>](#table1)

The average of these factors is 0.509<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1433.6
- 400 + ( ( 0.509 - 0.000 ) / ( 0.787 - 0.000 ) ) * 1600 = 1433.6


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent           | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                     |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           75 |      284 | 2024-05-25 | B8                 | L   | 1.000      | -            | -                | -                | -         |   -21.99 | KaiR0N-, Magnojez, nafany, s1ren, zorte    |
|           74 |      378 | 2024-05-24 | DMS                | W   | 1.000      | 0.435        | -                | 0.754 (0.327)    | 0 (0.000) |     2.87 | KaiR0N-, Magnojez, nafany, s1ren, zorte    |
|           73 |      605 | 2024-05-21 | Eternal Fire       | L   | 1.000      | -            | -                | -                | -         |    -2.72 | KaiR0N-, Magnojez, nafany, s1ren, zorte    |
|           72 |      659 | 2024-05-20 | MIBR               | W   | 1.000      | 0.769        | 0.307 (0.236)    | 0.531 (0.408)    | 0 (0.000) |    23.31 | KaiR0N-, Magnojez, nafany, s1ren, zorte    |
|           71 |      697 | 2024-05-20 | Astralis           | L   | 1.000      | -            | -                | -                | -         |    -3.34 | KaiR0N-, Magnojez, nafany, s1ren, zorte    |
|           70 |      732 | 2024-05-20 | MIBR               | W   | 1.000      | 0.769        | 0.307 (0.236)    | 0.531 (0.408)    | 0 (0.000) |    24.48 | KaiR0N-, Magnojez, nafany, s1ren, zorte    |
|           69 |     1167 | 2024-05-15 | Team Falcons       | L   | 1.000      | -            | -                | -                | -         |   -11.41 | KaiR0N-, Magnojez, nafany, s1ren, zorte    |
|           68 |     1296 | 2024-05-14 | MOUZ               | L   | 1.000      | -            | -                | -                | -         |    -0.72 | KaiR0N-, Magnojez, nafany, s1ren, zorte    |
|           67 |     1367 | 2024-05-12 | B8                 | L   | 1.000      | -            | -                | -                | -         |   -24.38 | KaiR0N-, Magnojez, nafany, s1ren, zorte    |
|           66 |     1394 | 2024-05-12 | 9Pandas            | W   | 1.000      | 0.435        | 0.110 (0.048)    | 0.710 (0.308)    | -         |     6.47 | KaiR0N-, Magnojez, nafany, s1ren, zorte    |
|           65 |     1477 | 2024-05-11 | Metizport          | W   | 1.000      | 0.435        | -                | 0.698 (0.303)    | -         |     6.14 | KaiR0N-, Magnojez, nafany, s1ren, zorte    |
|           64 |     1544 | 2024-05-10 | ENTERPRISE esports | W   | 1.000      | 0.435        | -                | 0.898 (0.390)    | -         |     3.20 | KaiR0N-, Magnojez, nafany, s1ren, zorte    |
|           63 |     1703 | 2024-05-07 | FlyQuest           | L   | 1.000      | -            | -                | -                | -         |   -10.69 | KaiR0N-, Magnojez, nafany, s1ren, zorte    |
|           62 |     1834 | 2024-05-04 | AMKAL ESPORTS      | L   | 1.000      | -            | -                | -                | -         |   -20.59 | KaiR0N-, Magnojez, nafany, s1ren, zorte    |
|           61 |     1856 | 2024-05-04 | 9Pandas            | W   | 1.000      | 0.435        | 0.110 (0.048)    | 0.710 (0.308)    | -         |     5.67 | KaiR0N-, Magnojez, nafany, s1ren, zorte    |
|           60 |     1922 | 2024-05-03 | Insilio            | W   | 1.000      | 0.435        | -                | 0.717 (0.312)    | -         |     3.81 | KaiR0N-, Magnojez, nafany, s1ren, zorte    |
|           59 |     2021 | 2024-05-01 | EYEBALLERS         | W   | 1.000      | -            | -                | -                | -         |     2.80 | KaiR0N-, Magnojez, nafany, s1ren, zorte    |
|           58 |     2075 | 2024-04-30 | 3DMAX              | L   | 1.000      | -            | -                | -                | -         |   -28.33 | KaiR0N-, Magnojez, nafany, s1ren, zorte    |
|           57 |     2278 | 2024-04-26 | M80                | W   | 0.978      | 0.889        | 0.136 (0.118)    | 0.525 (0.456)    | 1 (0.978) |    12.44 | KaiR0N-, Magnojez, nafany, s1ren, zorte    |
|           56 |     2315 | 2024-04-26 | Team Falcons       | W   | 0.975      | 0.889        | 0.355 (0.308)    | -                | 1 (0.975) |    18.54 | KaiR0N-, Magnojez, nafany, s1ren, zorte    |
|           55 |     2361 | 2024-04-25 | Team Vitality      | L   | 0.970      | -            | -                | -                | -         |    -1.97 | KaiR0N-, Magnojez, nafany, s1ren, zorte    |
|           54 |     2457 | 2024-04-23 | M80                | W   | 0.957      | 0.889        | 0.136 (0.115)    | 0.525 (0.446)    | 1 (0.957) |    12.66 | KaiR0N-, Magnojez, nafany, s1ren, zorte    |
|           53 |     2745 | 2024-04-19 | Cloud9             | L   | 0.930      | -            | -                | -                | -         |    -8.08 | KaiR0N-, Magnojez, nafany, s1ren, zorte    |
|           52 |     2771 | 2024-04-19 | Eternal Fire       | L   | 0.929      | -            | -                | -                | -         |    -1.65 | KaiR0N-, Magnojez, nafany, s1ren, zorte    |
|           51 |     2804 | 2024-04-18 | Apeks              | W   | 0.924      | -            | -                | -                | -         |     9.97 | KaiR0N-, Magnojez, nafany, s1ren, zorte    |
|           50 |     2807 | 2024-04-18 | brazylijski luz    | W   | 0.924      | -            | -                | -                | -         |     1.82 | KaiR0N-, Magnojez, nafany, s1ren, zorte    |
|           49 |     2817 | 2024-04-18 | iNation            | W   | 0.923      | -            | -                | -                | -         |     0.78 | KaiR0N-, Magnojez, nafany, s1ren, zorte    |
|           48 |     2877 | 2024-04-17 | Verdant            | W   | 0.918      | -            | -                | -                | -         |     2.29 | KaiR0N-, Magnojez, nafany, s1ren, zorte    |
|           47 |     3051 | 2024-04-14 | 3DMAX              | W   | 0.896      | -            | -                | -                | -         |     3.33 | kaiR0N-, Magnojez, nafany, s1ren, zorte    |
|           46 |     3082 | 2024-04-13 | OG                 | L   | 0.890      | -            | -                | -                | -         |   -17.00 | KaiR0N-, Magnojez, nafany, s1ren, zorte    |
|           45 |     3094 | 2024-04-13 | Aurora Gaming      | L   | 0.890      | -            | -                | -                | -         |   -11.69 | KaiR0N-, Magnojez, nafany, s1ren, zorte    |
|           44 |     3117 | 2024-04-13 | Team Sampi         | W   | 0.888      | -            | -                | -                | -         |     3.81 | kaiR0N-, Magnojez, nafany, s1ren, zorte    |
|           43 |     3174 | 2024-04-11 | Aurora Gaming      | L   | 0.877      | -            | -                | -                | -         |   -12.53 | KaiR0N-, Magnojez, nafany, s1ren, zorte    |
|           42 |     3189 | 2024-04-11 | Ninjas in Pyjamas  | W   | 0.877      | 0.687        | 0.118 (0.071)    | -                | -         |     5.94 | KaiR0N-, Magnojez, nafany, s1ren, zorte    |
|           41 |     3200 | 2024-04-11 | AMKAL ESPORTS      | L   | 0.876      | -            | -                | -                | -         |   -21.32 | KaiR0N-, Magnojez, nafany, s1ren, zorte    |
|           40 |     3257 | 2024-04-10 | Aurora Gaming      | W   | 0.870      | 0.143        | 0.492 (0.061)    | -                | -         |    14.03 | KaiR0N-, Magnojez, nafany, s1ren, zorte    |
|           39 |     3332 | 2024-04-09 | BIG                | W   | 0.863      | 0.687        | 0.215 (0.128)    | -                | -         |    14.73 | KaiR0N-, Magnojez, nafany, s1ren, zorte    |
|           38 |     3481 | 2024-04-06 | Alliance           | W   | 0.843      | -            | -                | -                | -         |     1.72 | kaiR0N-, Magnojez, nafany, s1ren, zorte    |
|           37 |     3526 | 2024-04-05 | BLEED Esports      | W   | 0.837      | -            | -                | -                | -         |     7.66 | KaiR0N-, Magnojez, nafany, s1ren, zorte    |
|           36 |     3575 | 2024-04-04 | Alliance           | W   | 0.831      | -            | -                | -                | -         |     1.83 | KaiR0N-, Magnojez, nafany, s1ren, zorte    |
|           35 |     3595 | 2024-04-04 | BLEED Esports      | W   | 0.829      | -            | -                | -                | -         |     7.99 | KaiR0N-, Magnojez, nafany, s1ren, zorte    |
|           34 |     3888 | 2024-03-27 | FAVBET Team        | L   | 0.778      | -            | -                | -                | -         |   -22.59 | KaiR0N-, Magnojez, nafany, s1ren, zorte    |
|           33 |     3902 | 2024-03-27 | brazylijski luz    | W   | 0.777      | -            | -                | -                | -         |     1.19 | KaiR0N-, Magnojez, nafany, s1ren, zorte    |
|           32 |     3981 | 2024-03-26 | Infinite Gaming    | W   | 0.771      | -            | -                | -                | -         |     0.21 | KaiR0N-, Magnojez, nafany, s1ren, zorte    |
|           31 |     4049 | 2024-03-24 | FORZE Esports      | L   | 0.756      | -            | -                | -                | -         |   -19.83 | KaiR0N-, Magnojez, nafany, s1ren, zorte    |
|           30 |     4110 | 2024-03-23 | Fnatic             | W   | 0.749      | -            | -                | -                | -         |     5.55 | KaiR0N-, Magnojez, nafany, s1ren, zorte    |
|           29 |     4203 | 2024-03-21 | B8                 | W   | 0.736      | -            | -                | -                | -         |     5.08 | KaiR0N-, Magnojez, nafany, s1ren, zorte    |
|           28 |     5113 | 2024-03-05 | BLEED Esports      | L   | 0.629      | -            | -                | -                | -         |   -13.86 | danistzz, KaiR0N-, nafany, s1ren, zorte    |
|           27 |     5200 | 2024-03-04 | Gaimin Gladiators  | W   | 0.622      | -            | -                | -                | -         |     7.02 | danistzz, KaiR0N-, nafany, s1ren, zorte    |
|           26 |     5219 | 2024-03-03 | ex-Preasy Esport   | L   | 0.618      | -            | -                | -                | -         |   -17.69 | danistzz, KaiR0N-, nafany, s1ren, zorte    |
|           25 |     5226 | 2024-03-03 | ex-Sprout          | W   | 0.617      | -            | -                | -                | -         |     0.32 | danistzz, KaiR0N-, nafany, s1ren, zorte    |
|           24 |     5270 | 2024-03-02 | DASH               | W   | 0.612      | -            | -                | -                | -         |     0.48 | danistzz, KaiR0N-, nafany, s1ren, zorte    |
|           23 |     5292 | 2024-03-02 | GenOne             | W   | 0.611      | -            | -                | -                | -         |     0.24 | danistzz, KaiR0N-, nafany, s1ren, zorte    |
|           22 |     5374 | 2024-03-01 | ex-Preasy Esport   | W   | 0.604      | -            | -                | -                | -         |     1.59 | danistzz, KaiR0N-, nafany, s1ren, zorte    |
|           21 |     5485 | 2024-02-28 | ALTERNATE aTTaX    | W   | 0.589      | -            | -                | -                | -         |     1.55 | danistzz, KaiR0N-, nafany, s1ren, zorte    |
|           20 |     5777 | 2024-02-23 | ex-Guild Eagles    | L   | 0.556      | -            | -                | -                | -         |   -15.86 | danistzz, KaiR0N-, nafany, s1ren, zorte    |
|           19 |     6115 | 2024-02-17 | Eternal Fire       | L   | 0.517      | -            | -                | -                | -         |    -1.29 | danistzz, KaiR0N-, nafany, s1ren, zorte    |
|           18 |     6157 | 2024-02-16 | Natus Vincere      | L   | 0.510      | -            | -                | -                | -         |    -1.15 | danistzz, KaiR0N-, nafany, s1ren, zorte    |
|           17 |     6239 | 2024-02-15 | ENTERPRISE esports | W   | 0.503      | -            | -                | -                | 1 (0.503) |     1.49 | danistzz, KaiR0N-, nafany, s1ren, zorte    |
|           16 |     6283 | 2024-02-14 | Into The Breach    | W   | 0.497      | -            | -                | -                | 1 (0.497) |     0.50 | danistzz, KaiR0N-, nafany, s1ren, zorte    |
|           15 |     6288 | 2024-02-14 | Fnatic             | L   | 0.496      | -            | -                | -                | -         |   -13.03 | danistzz, KaiR0N-, nafany, s1ren, zorte    |
|           14 |     6508 | 2024-02-08 | FORZE Esports      | L   | 0.458      | -            | -                | -                | -         |   -13.35 | danistzz, KaiR0N-, nafany, s1ren, zorte    |
|           13 |     6523 | 2024-02-08 | Nemiga Gaming      | L   | 0.457      | -            | -                | -                | -         |   -10.68 | danistzz, KaiR0N-, nafany, s1ren, zorte    |
|           12 |     6882 | 2024-02-01 | Cloud9             | L   | 0.410      | -            | -                | -                | -         |    -5.50 | danistzz, KaiR0N-, nafany, s1ren, zorte    |
|           11 |     6940 | 2024-01-31 | Eternal Fire       | L   | 0.403      | -            | -                | -                | -         |    -1.14 | danistzz, KaiR0N-, nafany, s1ren, zorte    |
|           10 |     7591 | 2024-01-20 | OG                 | W   | 0.330      | -            | -                | -                | -         |     2.12 | danistzz, KaiR0N-, nafany, s1ren, zorte    |
|            9 |     7654 | 2024-01-19 | Cloud9             | L   | 0.324      | -            | -                | -                | -         |    -4.28 | danistzz, KaiR0N-, nafany, s1ren, zorte    |
|            8 |     7716 | 2024-01-18 | BIG                | W   | 0.317      | -            | -                | -                | -         |     4.85 | danistzz, KaiR0N-, nafany, s1ren, zorte    |
|            7 |     7728 | 2024-01-18 | Zero Tenacity      | W   | 0.317      | -            | -                | -                | -         |     1.13 | danistzz, KaiR0N-, nafany, s1ren, zorte    |
|            6 |     9114 | 2023-12-13 | ENCE               | L   | 0.076      | -            | -                | -                | -         |    -1.21 | danistzz, KaiR0N-, Magnojez, nafany, zorte |
|            5 |     9156 | 2023-12-12 | ex-Preasy Esport   | W   | 0.069      | -            | -                | -                | -         |     0.11 | danistzz, KaiR0N-, Magnojez, nafany, zorte |
|            4 |     9315 | 2023-12-09 | Virtus.pro         | L   | 0.049      | -            | -                | -                | -         |    -0.29 | danistzz, KaiR0N-, nafany, s1ren, zorte    |
|            3 |     9395 | 2023-12-08 | Cloud9             | W   | 0.042      | -            | -                | -                | 1 (0.042) |     0.77 | danistzz, KaiR0N-, nafany, s1ren, zorte    |
|            2 |     9504 | 2023-12-06 | GamerLegion        | W   | 0.031      | -            | -                | -                | 1 (0.031) |     0.22 | danistzz, KaiR0N-, nafany, s1ren, zorte    |
|            1 |     9587 | 2023-12-05 | MIBR               | L   | 0.023      | -            | -                | -                | -         |    -0.20 | danistzz, KaiR0N-, nafany, s1ren, zorte    |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($117,188.23)
- Divide that value by the 5th highest value among all rosters ($300,806.11)
- The final value (0.39) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-05-26 |      1.000 | $2,000.00      | $2,000.00       |
| 2024-05-23 |      1.000 | $12,500.00     | $12,500.00      |
| 2024-05-12 |      1.000 | $10,000.00     | $10,000.00      |
| 2024-05-12 |      1.000 | $17,500.00     | $17,500.00      |
| 2024-05-04 |      1.000 | $10,000.00     | $10,000.00      |
| 2024-04-14 |      0.896 | $52,500.00     | $47,053.13      |
| 2024-04-14 |      0.896 | $8,165.54      | $7,314.96       |
| 2024-03-06 |      0.637 | $12,500.00     | $7,961.81       |
| 2024-02-11 |      0.477 | $2,500.00      | $1,192.36       |
| 2023-12-10 |      0.056 | $30,000.00     | $1,665.97       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
