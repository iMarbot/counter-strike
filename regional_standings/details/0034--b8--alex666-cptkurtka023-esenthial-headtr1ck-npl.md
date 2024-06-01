### Roster Details<br />
Team Name: B8<br />
Roster: alex666, cptkurtka023, esenthial, headtr1ck, npl<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [34](../standings_global.md)<br />
Regional Rank: [24]( ../standings_europe.md)<br />
Final Rank Value:  1185.8<br />
<br />
Final Rank Value (1185.8) = Starting Rank Value (1124.6) + Head To Head Adjustments (61.2)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.563[<sup>1</sup>](#table2)
- Bounty Collected: 0.479[<sup>2</sup>](#table1)
- Opponent Network: 0.381[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.356<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1124.6
- 400 + ( ( 0.356 - 0.000 ) / ( 0.786 - 0.000 ) ) * 1600 = 1124.6


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent            | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                           |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           75 |      230 | 2024-05-26 | MOUZ NXT            | L   | 1.000      | -            | -                | -                | -         |   -23.32 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           74 |      254 | 2024-05-25 | RUBY                | W   | 1.000      | -            | -                | -                | 0 (0.000) |     6.81 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           73 |      276 | 2024-05-25 | BetBoom Team        | W   | 1.000      | 0.435        | 0.390 (0.169)    | -                | 0 (0.000) |    21.88 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           72 |      341 | 2024-05-24 | Alliance            | W   | 1.000      | -            | -                | -                | 0 (0.000) |     4.74 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           71 |      414 | 2024-05-23 | DMS                 | W   | 1.000      | 0.435        | -                | 0.751 (0.326)    | 0 (0.000) |     6.59 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           70 |      571 | 2024-05-21 | Rhyno Esports       | W   | 1.000      | -            | -                | -                | 0 (0.000) |     6.21 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           69 |      704 | 2024-05-20 | EYEBALLERS          | W   | 1.000      | -            | -                | -                | 0 (0.000) |     6.60 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           68 |      796 | 2024-05-19 | Zero Tenacity       | L   | 1.000      | -            | -                | -                | -         |   -22.56 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           67 |      859 | 2024-05-18 | Sashi Esport        | W   | 1.000      | 0.384        | 0.172 (0.066)    | 1.000 (0.384)    | 0 (0.000) |    19.10 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           66 |      926 | 2024-05-18 | Rebels Gaming       | W   | 1.000      | -            | -                | -                | 0 (0.000) |    12.62 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           65 |     1004 | 2024-05-17 | 3DMAX               | W   | 1.000      | 0.500        | 0.106 (0.053)    | -                | 0 (0.000) |     7.83 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           64 |     1068 | 2024-05-16 | DMS                 | W   | 1.000      | 0.435        | -                | 0.751 (0.326)    | 0 (0.000) |     6.99 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           63 |     1102 | 2024-05-16 | Team Sampi          | W   | 1.000      | -            | -                | -                | -         |    10.15 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           62 |     1141 | 2024-05-15 | PARIVISION          | L   | 1.000      | -            | -                | -                | -         |   -24.51 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           61 |     1274 | 2024-05-14 | Verdant             | W   | 1.000      | 0.435        | -                | 1.000 (0.435)    | -         |     5.83 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           60 |     1292 | 2024-05-14 | MOUZ NXT            | W   | 1.000      | 0.384        | 0.157 (0.060)    | 0.950 (0.365)    | -         |    11.84 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           59 |     1355 | 2024-05-12 | BetBoom Team        | W   | 1.000      | 0.435        | 0.390 (0.169)    | -                | -         |    24.14 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           58 |     1396 | 2024-05-12 | MOUZ NXT            | W   | 1.000      | 0.435        | 0.157 (0.068)    | 0.950 (0.413)    | -         |    13.63 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           57 |     1428 | 2024-05-11 | FAVBET Team         | L   | 1.000      | -            | -                | -                | -         |   -20.26 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           56 |     1437 | 2024-05-11 | GenOne              | W   | 1.000      | -            | -                | -                | -         |     3.19 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           55 |     1445 | 2024-05-11 | ADEPTS              | W   | 1.000      | -            | -                | -                | -         |     3.57 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           54 |     1451 | 2024-05-11 | DASH                | W   | 1.000      | -            | -                | -                | -         |     2.65 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           53 |     1480 | 2024-05-11 | BLEED Esports       | W   | 1.000      | 0.435        | 0.248 (0.108)    | -                | -         |    19.95 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           52 |     1527 | 2024-05-10 | 1win                | L   | 1.000      | -            | -                | -                | -         |   -16.76 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           51 |     1581 | 2024-05-09 | KOI                 | W   | 1.000      | -            | -                | -                | -         |    12.68 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           50 |     1737 | 2024-05-06 | ENTERPRISE esports  | W   | 1.000      | 0.435        | -                | 0.809 (0.352)    | -         |     7.11 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           49 |     1834 | 2024-05-04 | GamerLegion Academy | W   | 1.000      | -            | -                | -                | -         |     6.62 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           48 |     1938 | 2024-05-02 | Permitta Esports    | W   | 1.000      | 0.384        | -                | 1.000 (0.384)    | -         |     9.32 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           47 |     1965 | 2024-05-01 | Nemiga Gaming       | L   | 1.000      | -            | -                | -                | -         |   -10.67 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           46 |     1985 | 2024-05-01 | V1dar Gaming        | W   | 1.000      | -            | -                | -                | -         |     3.86 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           45 |     2005 | 2024-05-01 | SINNERS Esports     | W   | 1.000      | -            | -                | -                | -         |    11.46 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           44 |     2036 | 2024-04-30 | Alliance            | W   | 1.000      | -            | -                | -                | -         |     8.95 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           43 |     2043 | 2024-04-30 | Zero Tenacity       | L   | 1.000      | -            | -                | -                | -         |   -17.88 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           42 |     2420 | 2024-04-23 | BLEED Esports       | L   | 0.956      | -            | -                | -                | -         |    -8.46 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           41 |     2443 | 2024-04-22 | Passion UA          | W   | 0.951      | 0.500        | 0.057 (0.027)    | 1.000 (0.475)    | -         |     9.96 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           40 |     2465 | 2024-04-22 | Alliance            | L   | 0.949      | -            | -                | -                | -         |   -22.35 | baz, cptkurtka023, esenthial, headtr1ck, npl     |
|           39 |     2514 | 2024-04-21 | PARIVISION          | W   | 0.942      | -            | -                | -                | -         |     6.96 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           38 |     2720 | 2024-04-19 | HAVU Gaming         | W   | 0.929      | -            | -                | -                | -         |     3.46 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           37 |     2795 | 2024-04-18 | Zero Tenacity       | W   | 0.921      | 0.384        | 0.147 (0.052)    | 1.000 (0.354)    | -         |    10.11 | baz, cptkurtka023, esenthial, headtr1ck, npl     |
|           36 |     2854 | 2024-04-17 | Zero Tenacity       | L   | 0.916      | -            | -                | -                | -         |   -18.92 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           35 |     2927 | 2024-04-16 | AMKAL ESPORTS       | L   | 0.908      | -            | -                | -                | -         |   -11.79 | baz, cptkurtka023, esenthial, headtr1ck, npl     |
|           34 |     3191 | 2024-04-10 | Nexus Gaming        | L   | 0.869      | -            | -                | -                | -         |   -19.36 | baz, cptkurtka023, esenthial, headtr1ck, npl     |
|           33 |     3235 | 2024-04-09 | Rebels Gaming       | L   | 0.864      | -            | -                | -                | -         |   -14.56 | baz, cptkurtka023, esenthial, headtr1ck, npl     |
|           32 |     3308 | 2024-04-08 | MOUZ NXT            | L   | 0.856      | -            | -                | -                | -         |   -16.03 | baz, cptkurtka023, esenthial, headtr1ck, npl     |
|           31 |     3595 | 2024-04-02 | Metizport           | L   | 0.817      | -            | -                | -                | -         |   -15.87 | baz, cptkurtka023, esenthial, npl, OWNER         |
|           30 |     3604 | 2024-04-02 | Apeks               | L   | 0.816      | -            | -                | -                | -         |   -10.47 | baz, cptkurtka023, esenthial, npl, OWNER         |
|           29 |     3655 | 2024-03-31 | Apeks               | W   | 0.802      | -            | -                | -                | -         |     1.26 | cptkurtka023, esenthial, npl, OWNER, r1nkle      |
|           28 |     3783 | 2024-03-27 | Rebels Gaming       | W   | 0.778      | -            | -                | -                | -         |    10.24 | baz, cptkurtka023, esenthial, npl, OWNER         |
|           27 |     3798 | 2024-03-27 | Team Sampi          | W   | 0.777      | -            | -                | -                | -         |     6.77 | baz, cptkurtka023, esenthial, npl, OWNER         |
|           26 |     3815 | 2024-03-27 | Gaimin Gladiators   | W   | 0.777      | -            | -                | -                | -         |    16.77 | baz, cptkurtka023, esenthial, npl, OWNER         |
|           25 |     3863 | 2024-03-26 | RUSH B              | W   | 0.771      | -            | -                | -                | -         |     2.93 | baz, cptkurtka023, esenthial, npl, OWNER         |
|           24 |     3923 | 2024-03-25 | FORZE Esports       | W   | 0.764      | 0.500        | 0.111 (0.043)    | -                | -         |    10.17 | cptkurtka023, esenthial, npl, OWNER, r1nkle      |
|           23 |     4103 | 2024-03-21 | BetBoom Team        | L   | 0.736      | -            | -                | -                | -         |    -5.11 | cptkurtka023, esenthial, npl, OWNER, r1nkle      |
|           22 |     4183 | 2024-03-19 | ex-Sprout           | W   | 0.722      | -            | -                | -                | -         |     1.58 | cptkurtka023, esenthial, npl, OWNER, r1nkle      |
|           21 |     4548 | 2024-03-12 | Metizport           | L   | 0.678      | -            | -                | -                | -         |   -12.20 | cptkurtka023, esenthial, npl, OWNER, r1nkle      |
|           20 |     4561 | 2024-03-12 | ENCE                | W   | 0.677      | -            | -                | -                | -         |    18.34 | cptkurtka023, esenthial, npl, OWNER, r1nkle      |
|           19 |     4596 | 2024-03-11 | KOI                 | W   | 0.671      | -            | -                | -                | -         |     8.59 | cptkurtka023, esenthial, npl, OWNER, r1nkle      |
|           18 |     4620 | 2024-03-11 | Virtus.pro          | L   | 0.670      | -            | -                | -                | -         |    -0.79 | cptkurtka023, esenthial, npl, OWNER, r1nkle      |
|           17 |     4752 | 2024-03-08 | PARIVISION          | L   | 0.650      | -            | -                | -                | -         |   -15.78 | cptkurtka023, esenthial, npl, OWNER, r1nkle      |
|           16 |     4942 | 2024-03-05 | Johnny Speeds       | W   | 0.631      | -            | -                | -                | -         |     7.27 | cptkurtka023, esenthial, npl, OWNER, r1nkle      |
|           15 |     4947 | 2024-03-05 | Passion UA          | W   | 0.631      | -            | -                | -                | -         |     5.39 | cptkurtka023, esenthial, npl, OWNER, r1nkle      |
|           14 |     4957 | 2024-03-05 | UGANDA              | W   | 0.631      | -            | -                | -                | -         |     0.76 | cptkurtka023, esenthial, npl, OWNER, r1nkle      |
|           13 |     4989 | 2024-03-04 | Gaimin Gladiators   | W   | 0.625      | -            | -                | -                | -         |    13.55 | cptkurtka023, esenthial, npl, OWNER, r1nkle      |
|           12 |     5028 | 2024-03-04 | Alliance            | W   | 0.625      | -            | -                | -                | -         |     3.62 | cptkurtka023, esenthial, npl, OWNER, r1nkle      |
|           11 |     5123 | 2024-03-02 | Fnatic              | L   | 0.612      | -            | -                | -                | -         |    -9.53 | cptkurtka023, esenthial, npl, OWNER, r1nkle      |
|           10 |     5139 | 2024-03-02 | Infinite Gaming     | W   | 0.611      | -            | -                | -                | -         |     0.63 | cptkurtka023, esenthial, npl, OWNER, r1nkle      |
|            9 |     5369 | 2024-02-27 | DMS                 | L   | 0.584      | -            | -                | -                | -         |   -16.54 | cptkurtka023, esenthial, npl, OWNER, r1nkle      |
|            8 |     5405 | 2024-02-26 | Sprout              | W   | 0.578      | -            | -                | -                | -         |     1.34 | cptkurtka023, esenthial, npl, OWNER, r1nkle      |
|            7 |     5886 | 2024-02-18 | Aurora Gaming       | L   | 0.523      | -            | -                | -                | -         |    -2.36 | cptkurtka023, esenthial, npl, OWNER, r1nkle      |
|            6 |     5985 | 2024-02-16 | 500                 | W   | 0.510      | -            | -                | -                | -         |     2.24 | cptkurtka023, esenthial, npl, OWNER, r1nkle      |
|            5 |     5997 | 2024-02-16 | Tropic              | W   | 0.509      | -            | -                | -                | -         |     0.53 | cptkurtka023, esenthial, npl, OWNER, r1nkle      |
|            4 |     6592 | 2024-02-02 | 9Pandas             | W   | 0.418      | -            | -                | -                | -         |     7.75 | cptkurtka023, esenthial, npl, OWNER, r1nkle      |
|            3 |     6600 | 2024-02-02 | Team Sampi          | W   | 0.417      | -            | -                | -                | -         |     3.53 | cptkurtka023, esenthial, npl, OWNER, r1nkle      |
|            2 |     6626 | 2024-02-02 | POVYDLO ESPORTS     | W   | 0.417      | -            | -                | -                | -         |     0.24 | cptkurtka023, esenthial, npl, OWNER, r1nkle      |
|            1 |     6801 | 2024-01-29 | Into The Breach     | L   | 0.392      | -            | -                | -                | -         |   -10.99 | cptkurtka023, esenthial, npl, OWNER, r1nkle      |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($50,538.19)
- Divide that value by the 5th highest value among all rosters ($300,806.11)
- The final value (0.17) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-05-26 |      1.000 | $5,000.00      | $5,000.00       |
| 2024-05-22 |      1.000 | $1,500.00      | $1,500.00       |
| 2024-05-18 |      1.000 | $10,000.00     | $10,000.00      |
| 2024-05-12 |      1.000 | $22,000.00     | $22,000.00      |
| 2024-04-24 |      0.963 | $12,500.00     | $12,038.19      |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
