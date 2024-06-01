### Roster Details<br />
Team Name: BetBoom Team<br />
Roster: KaiR0N-, Magnojez, nafany, s1ren, zorte<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [23](../standings_global.md)<br />
Regional Rank: [16]( ../standings_europe.md)<br />
Final Rank Value:  1326.7<br />
<br />
Final Rank Value (1326.7) = Starting Rank Value (1430.1) + Head To Head Adjustments (-103.4)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.710[<sup>1</sup>](#table2)
- Bounty Collected: 0.538[<sup>2</sup>](#table1)
- Opponent Network: 0.355[<sup>2</sup>](#table1)
- LAN Wins: 0.421[<sup>2</sup>](#table1)

The average of these factors is 0.506<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1430.1
- 400 + ( ( 0.506 - 0.000 ) / ( 0.786 - 0.000 ) ) * 1600 = 1430.1


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
|           75 |      276 | 2024-05-25 | B8                 | L   | 1.000      | -            | -                | -                | -         |   -21.88 | KaiR0N-, Magnojez, nafany, s1ren, zorte    |
|           74 |      369 | 2024-05-24 | DMS                | W   | 1.000      | 0.435        | -                | 0.751 (0.326)    | 0 (0.000) |     2.78 | KaiR0N-, Magnojez, nafany, s1ren, zorte    |
|           73 |      594 | 2024-05-21 | Eternal Fire       | L   | 1.000      | -            | -                | -                | -         |    -2.71 | KaiR0N-, Magnojez, nafany, s1ren, zorte    |
|           72 |      648 | 2024-05-20 | MIBR               | W   | 1.000      | 0.769        | 0.307 (0.236)    | 0.512 (0.393)    | 0 (0.000) |    23.38 | KaiR0N-, Magnojez, nafany, s1ren, zorte    |
|           71 |      686 | 2024-05-20 | Astralis           | L   | 1.000      | -            | -                | -                | -         |    -3.29 | KaiR0N-, Magnojez, nafany, s1ren, zorte    |
|           70 |      720 | 2024-05-20 | MIBR               | W   | 1.000      | 0.769        | 0.307 (0.236)    | 0.512 (0.393)    | 0 (0.000) |    24.54 | KaiR0N-, Magnojez, nafany, s1ren, zorte    |
|           69 |     1158 | 2024-05-15 | Team Falcons       | L   | 1.000      | -            | -                | -                | -         |   -11.39 | KaiR0N-, Magnojez, nafany, s1ren, zorte    |
|           68 |     1285 | 2024-05-14 | MOUZ               | L   | 1.000      | -            | -                | -                | -         |    -0.71 | KaiR0N-, Magnojez, nafany, s1ren, zorte    |
|           67 |     1355 | 2024-05-12 | B8                 | L   | 1.000      | -            | -                | -                | -         |   -24.14 | KaiR0N-, Magnojez, nafany, s1ren, zorte    |
|           66 |     1381 | 2024-05-12 | 9Pandas            | W   | 1.000      | 0.435        | 0.110 (0.048)    | 0.660 (0.287)    | -         |     6.15 | KaiR0N-, Magnojez, nafany, s1ren, zorte    |
|           65 |     1464 | 2024-05-11 | Metizport          | W   | 1.000      | 0.435        | -                | 0.698 (0.303)    | -         |     6.28 | KaiR0N-, Magnojez, nafany, s1ren, zorte    |
|           64 |     1529 | 2024-05-10 | ENTERPRISE esports | W   | 1.000      | 0.435        | -                | 0.809 (0.352)    | -         |     2.93 | KaiR0N-, Magnojez, nafany, s1ren, zorte    |
|           63 |     1684 | 2024-05-07 | FlyQuest           | L   | 1.000      | -            | -                | -                | -         |   -10.95 | KaiR0N-, Magnojez, nafany, s1ren, zorte    |
|           62 |     1811 | 2024-05-04 | AMKAL ESPORTS      | L   | 1.000      | -            | -                | -                | -         |   -20.68 | KaiR0N-, Magnojez, nafany, s1ren, zorte    |
|           61 |     1833 | 2024-05-04 | 9Pandas            | W   | 1.000      | 0.435        | 0.110 (0.048)    | 0.660 (0.287)    | -         |     5.36 | KaiR0N-, Magnojez, nafany, s1ren, zorte    |
|           60 |     1897 | 2024-05-03 | Insilio            | W   | 1.000      | 0.435        | -                | 0.717 (0.312)    | -         |     3.76 | KaiR0N-, Magnojez, nafany, s1ren, zorte    |
|           59 |     1991 | 2024-05-01 | EYEBALLERS         | W   | 1.000      | -            | -                | -                | -         |     2.97 | KaiR0N-, Magnojez, nafany, s1ren, zorte    |
|           58 |     2041 | 2024-04-30 | 3DMAX              | L   | 1.000      | -            | -                | -                | -         |   -28.57 | KaiR0N-, Magnojez, nafany, s1ren, zorte    |
|           57 |     2242 | 2024-04-26 | M80                | W   | 0.978      | 0.889        | 0.136 (0.118)    | 0.525 (0.456)    | 1 (0.978) |    12.79 | KaiR0N-, Magnojez, nafany, s1ren, zorte    |
|           56 |     2278 | 2024-04-26 | Team Falcons       | W   | 0.975      | 0.889        | 0.355 (0.308)    | -                | 1 (0.975) |    18.53 | KaiR0N-, Magnojez, nafany, s1ren, zorte    |
|           55 |     2321 | 2024-04-25 | Team Vitality      | L   | 0.970      | -            | -                | -                | -         |    -1.91 | KaiR0N-, Magnojez, nafany, s1ren, zorte    |
|           54 |     2410 | 2024-04-23 | M80                | W   | 0.957      | 0.889        | 0.136 (0.115)    | 0.525 (0.446)    | 1 (0.957) |    12.96 | KaiR0N-, Magnojez, nafany, s1ren, zorte    |
|           53 |     2689 | 2024-04-19 | Cloud9             | L   | 0.930      | -            | -                | -                | -         |    -8.11 | KaiR0N-, Magnojez, nafany, s1ren, zorte    |
|           52 |     2715 | 2024-04-19 | Eternal Fire       | L   | 0.929      | -            | -                | -                | -         |    -1.64 | KaiR0N-, Magnojez, nafany, s1ren, zorte    |
|           51 |     2748 | 2024-04-18 | Apeks              | W   | 0.924      | -            | -                | -                | -         |    10.03 | KaiR0N-, Magnojez, nafany, s1ren, zorte    |
|           50 |     2751 | 2024-04-18 | brazylijski luz    | W   | 0.924      | -            | -                | -                | -         |     1.70 | KaiR0N-, Magnojez, nafany, s1ren, zorte    |
|           49 |     2761 | 2024-04-18 | iNation            | W   | 0.923      | -            | -                | -                | -         |     0.78 | KaiR0N-, Magnojez, nafany, s1ren, zorte    |
|           48 |     2820 | 2024-04-17 | Verdant            | W   | 0.918      | -            | -                | -                | -         |     2.13 | KaiR0N-, Magnojez, nafany, s1ren, zorte    |
|           47 |     2986 | 2024-04-14 | 3DMAX              | W   | 0.896      | -            | -                | -                | -         |     3.08 | kaiR0N-, Magnojez, nafany, s1ren, zorte    |
|           46 |     3016 | 2024-04-13 | OG                 | L   | 0.890      | -            | -                | -                | -         |   -16.97 | KaiR0N-, Magnojez, nafany, s1ren, zorte    |
|           45 |     3028 | 2024-04-13 | Aurora Gaming      | L   | 0.890      | -            | -                | -                | -         |   -10.74 | KaiR0N-, Magnojez, nafany, s1ren, zorte    |
|           44 |     3051 | 2024-04-13 | Team Sampi         | W   | 0.888      | -            | -                | -                | -         |     3.72 | kaiR0N-, Magnojez, nafany, s1ren, zorte    |
|           43 |     3108 | 2024-04-11 | Aurora Gaming      | L   | 0.877      | -            | -                | -                | -         |   -11.47 | KaiR0N-, Magnojez, nafany, s1ren, zorte    |
|           42 |     3121 | 2024-04-11 | Ninjas in Pyjamas  | W   | 0.877      | 0.687        | 0.118 (0.071)    | -                | -         |     5.97 | KaiR0N-, Magnojez, nafany, s1ren, zorte    |
|           41 |     3130 | 2024-04-11 | AMKAL ESPORTS      | L   | 0.876      | -            | -                | -                | -         |   -21.36 | KaiR0N-, Magnojez, nafany, s1ren, zorte    |
|           40 |     3183 | 2024-04-10 | Aurora Gaming      | W   | 0.870      | 0.143        | 0.492 (0.061)    | -                | -         |    15.25 | KaiR0N-, Magnojez, nafany, s1ren, zorte    |
|           39 |     3253 | 2024-04-09 | BIG                | W   | 0.863      | 0.687        | 0.235 (0.139)    | -                | -         |    15.14 | KaiR0N-, Magnojez, nafany, s1ren, zorte    |
|           38 |     3398 | 2024-04-06 | Alliance           | W   | 0.843      | -            | -                | -                | -         |     1.75 | kaiR0N-, Magnojez, nafany, s1ren, zorte    |
|           37 |     3442 | 2024-04-05 | BLEED Esports      | W   | 0.837      | -            | -                | -                | -         |     7.97 | KaiR0N-, Magnojez, nafany, s1ren, zorte    |
|           36 |     3490 | 2024-04-04 | Alliance           | W   | 0.831      | -            | -                | -                | -         |     1.86 | KaiR0N-, Magnojez, nafany, s1ren, zorte    |
|           35 |     3509 | 2024-04-04 | BLEED Esports      | W   | 0.829      | -            | -                | -                | -         |     8.34 | KaiR0N-, Magnojez, nafany, s1ren, zorte    |
|           34 |     3795 | 2024-03-27 | FAVBET Team        | L   | 0.778      | -            | -                | -                | -         |   -22.70 | KaiR0N-, Magnojez, nafany, s1ren, zorte    |
|           33 |     3809 | 2024-03-27 | brazylijski luz    | W   | 0.777      | -            | -                | -                | -         |     1.17 | KaiR0N-, Magnojez, nafany, s1ren, zorte    |
|           32 |     3884 | 2024-03-26 | Infinite Gaming    | W   | 0.771      | -            | -                | -                | -         |     0.22 | KaiR0N-, Magnojez, nafany, s1ren, zorte    |
|           31 |     3952 | 2024-03-24 | FORZE Esports      | L   | 0.756      | -            | -                | -                | -         |   -19.89 | KaiR0N-, Magnojez, nafany, s1ren, zorte    |
|           30 |     4012 | 2024-03-23 | Fnatic             | W   | 0.749      | -            | -                | -                | -         |     5.58 | KaiR0N-, Magnojez, nafany, s1ren, zorte    |
|           29 |     4103 | 2024-03-21 | B8                 | W   | 0.736      | -            | -                | -                | -         |     5.11 | KaiR0N-, Magnojez, nafany, s1ren, zorte    |
|           28 |     4969 | 2024-03-05 | BLEED Esports      | L   | 0.629      | -            | -                | -                | -         |   -13.89 | danistzz, KaiR0N-, nafany, s1ren, zorte    |
|           27 |     5054 | 2024-03-04 | Gaimin Gladiators  | W   | 0.622      | -            | -                | -                | -         |     7.02 | danistzz, KaiR0N-, nafany, s1ren, zorte    |
|           26 |     5073 | 2024-03-03 | ex-Preasy Esport   | L   | 0.618      | -            | -                | -                | -         |   -17.70 | danistzz, KaiR0N-, nafany, s1ren, zorte    |
|           25 |     5080 | 2024-03-03 | ex-Sprout          | W   | 0.617      | -            | -                | -                | -         |     0.32 | danistzz, KaiR0N-, nafany, s1ren, zorte    |
|           24 |     5122 | 2024-03-02 | DASH               | W   | 0.612      | -            | -                | -                | -         |     0.46 | danistzz, KaiR0N-, nafany, s1ren, zorte    |
|           23 |     5144 | 2024-03-02 | GenOne             | W   | 0.611      | -            | -                | -                | -         |     0.24 | danistzz, KaiR0N-, nafany, s1ren, zorte    |
|           22 |     5225 | 2024-03-01 | ex-Preasy Esport   | W   | 0.604      | -            | -                | -                | -         |     1.58 | danistzz, KaiR0N-, nafany, s1ren, zorte    |
|           21 |     5333 | 2024-02-28 | ALTERNATE aTTaX    | W   | 0.589      | -            | -                | -                | -         |     1.72 | danistzz, KaiR0N-, nafany, s1ren, zorte    |
|           20 |     5617 | 2024-02-23 | ex-Guild Eagles    | L   | 0.556      | -            | -                | -                | -         |   -15.90 | danistzz, KaiR0N-, nafany, s1ren, zorte    |
|           19 |     5942 | 2024-02-17 | Eternal Fire       | L   | 0.517      | -            | -                | -                | -         |    -1.26 | danistzz, KaiR0N-, nafany, s1ren, zorte    |
|           18 |     5984 | 2024-02-16 | Natus Vincere      | L   | 0.510      | -            | -                | -                | -         |    -1.13 | danistzz, KaiR0N-, nafany, s1ren, zorte    |
|           17 |     6058 | 2024-02-15 | ENTERPRISE esports | W   | 0.503      | -            | -                | -                | 1 (0.503) |     1.32 | danistzz, KaiR0N-, nafany, s1ren, zorte    |
|           16 |     6102 | 2024-02-14 | Into The Breach    | W   | 0.497      | -            | -                | -                | 1 (0.497) |     0.50 | danistzz, KaiR0N-, nafany, s1ren, zorte    |
|           15 |     6107 | 2024-02-14 | Fnatic             | L   | 0.496      | -            | -                | -                | -         |   -13.01 | danistzz, KaiR0N-, nafany, s1ren, zorte    |
|           14 |     6320 | 2024-02-08 | FORZE Esports      | L   | 0.458      | -            | -                | -                | -         |   -13.26 | danistzz, KaiR0N-, nafany, s1ren, zorte    |
|           13 |     6335 | 2024-02-08 | Nemiga Gaming      | L   | 0.457      | -            | -                | -                | -         |   -10.51 | danistzz, KaiR0N-, nafany, s1ren, zorte    |
|           12 |     6673 | 2024-02-01 | Cloud9             | L   | 0.410      | -            | -                | -                | -         |    -5.45 | danistzz, KaiR0N-, nafany, s1ren, zorte    |
|           11 |     6728 | 2024-01-31 | Eternal Fire       | L   | 0.403      | -            | -                | -                | -         |    -1.11 | danistzz, KaiR0N-, nafany, s1ren, zorte    |
|           10 |     7347 | 2024-01-20 | OG                 | W   | 0.330      | -            | -                | -                | -         |     2.16 | danistzz, KaiR0N-, nafany, s1ren, zorte    |
|            9 |     7408 | 2024-01-19 | Cloud9             | L   | 0.324      | -            | -                | -                | -         |    -4.24 | danistzz, KaiR0N-, nafany, s1ren, zorte    |
|            8 |     7468 | 2024-01-18 | BIG                | W   | 0.317      | -            | -                | -                | -         |     5.06 | danistzz, KaiR0N-, nafany, s1ren, zorte    |
|            7 |     7479 | 2024-01-18 | Zero Tenacity      | W   | 0.317      | -            | -                | -                | -         |     1.14 | danistzz, KaiR0N-, nafany, s1ren, zorte    |
|            6 |     8850 | 2023-12-13 | ENCE               | L   | 0.076      | -            | -                | -                | -         |    -1.21 | danistzz, KaiR0N-, Magnojez, nafany, zorte |
|            5 |     8892 | 2023-12-12 | ex-Preasy Esport   | W   | 0.069      | -            | -                | -                | -         |     0.11 | danistzz, KaiR0N-, Magnojez, nafany, zorte |
|            4 |     9048 | 2023-12-09 | Virtus.pro         | L   | 0.049      | -            | -                | -                | -         |    -0.28 | danistzz, KaiR0N-, nafany, s1ren, zorte    |
|            3 |     9125 | 2023-12-08 | Cloud9             | W   | 0.042      | -            | -                | -                | 1 (0.042) |     0.78 | danistzz, KaiR0N-, nafany, s1ren, zorte    |
|            2 |     9223 | 2023-12-06 | GamerLegion        | W   | 0.031      | -            | -                | -                | 1 (0.031) |     0.23 | danistzz, KaiR0N-, nafany, s1ren, zorte    |
|            1 |     9305 | 2023-12-05 | MIBR               | L   | 0.023      | -            | -                | -                | -         |    -0.20 | danistzz, KaiR0N-, nafany, s1ren, zorte    |

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
