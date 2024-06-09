### Roster Details<br />
Team Name: B8<br />
Roster: alex666, cptkurtka023, esenthial, headtr1ck, npl<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [34](../standings_global.md)<br />
Regional Rank: [24]( ../standings_europe.md)<br />
Final Rank Value:  1183.0<br />
<br />
Final Rank Value (1183.0) = Starting Rank Value (1125.0) + Head To Head Adjustments (58.0)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.563[<sup>1</sup>](#table2)
- Bounty Collected: 0.476[<sup>2</sup>](#table1)
- Opponent Network: 0.388[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.357<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1125.0
- 400 + ( ( 0.357 - 0.000 ) / ( 0.787 - 0.000 ) ) * 1600 = 1125.0


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
|           77 |      238 | 2024-05-26 | MOUZ NXT            | L   | 1.000      | -            | -                | -                | -         |   -22.93 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           76 |      262 | 2024-05-25 | RUBY                | W   | 1.000      | -            | -                | -                | 0 (0.000) |     7.01 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           75 |      284 | 2024-05-25 | BetBoom Team        | W   | 1.000      | 0.435        | 0.390 (0.169)    | -                | 0 (0.000) |    21.99 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           74 |      350 | 2024-05-24 | Alliance            | W   | 1.000      | -            | -                | -                | 0 (0.000) |     4.84 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           73 |      422 | 2024-05-23 | DMS                 | W   | 1.000      | 0.435        | -                | 0.754 (0.327)    | 0 (0.000) |     6.88 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           72 |      582 | 2024-05-21 | Rhyno Esports       | W   | 1.000      | -            | -                | -                | 0 (0.000) |     6.63 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           71 |      716 | 2024-05-20 | EYEBALLERS          | W   | 1.000      | -            | -                | -                | 0 (0.000) |     6.54 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           70 |      808 | 2024-05-19 | Zero Tenacity       | L   | 1.000      | -            | -                | -                | -         |   -22.24 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           69 |      871 | 2024-05-18 | Sashi Esport        | W   | 1.000      | 0.384        | 0.154 (0.059)    | 1.000 (0.384)    | 0 (0.000) |    19.35 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           68 |      938 | 2024-05-18 | Rebels Gaming       | W   | 1.000      | 0.384        | 0.062 (0.024)    | -                | 0 (0.000) |    13.14 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           67 |     1016 | 2024-05-17 | 3DMAX               | W   | 1.000      | 0.500        | 0.106 (0.053)    | -                | 0 (0.000) |     8.46 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           66 |     1078 | 2024-05-16 | DMS                 | W   | 1.000      | 0.435        | -                | 0.754 (0.327)    | 0 (0.000) |     7.40 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           65 |     1112 | 2024-05-16 | Team Sampi          | W   | 1.000      | -            | -                | -                | -         |    10.52 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           64 |     1150 | 2024-05-15 | PARIVISION          | L   | 1.000      | -            | -                | -                | -         |   -24.28 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           63 |     1285 | 2024-05-14 | Verdant             | W   | 1.000      | 0.435        | -                | 1.000 (0.435)    | -         |     6.23 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           62 |     1303 | 2024-05-14 | MOUZ NXT            | W   | 1.000      | 0.384        | 0.157 (0.060)    | 0.977 (0.375)    | -         |    12.56 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           61 |     1367 | 2024-05-12 | BetBoom Team        | W   | 1.000      | 0.435        | 0.390 (0.169)    | -                | -         |    24.38 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           60 |     1409 | 2024-05-12 | MOUZ NXT            | W   | 1.000      | 0.435        | 0.157 (0.068)    | 0.977 (0.424)    | -         |    14.19 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           59 |     1441 | 2024-05-11 | FAVBET Team         | L   | 1.000      | -            | -                | -                | -         |   -20.53 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           58 |     1450 | 2024-05-11 | GenOne              | W   | 1.000      | -            | -                | -                | -         |     3.29 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           57 |     1458 | 2024-05-11 | ADEPTS              | W   | 1.000      | -            | -                | -                | -         |     3.37 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           56 |     1464 | 2024-05-11 | DASH                | W   | 1.000      | -            | -                | -                | -         |     3.25 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           55 |     1493 | 2024-05-11 | BLEED Esports       | W   | 1.000      | 0.435        | 0.248 (0.108)    | -                | -         |    20.26 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           54 |     1542 | 2024-05-10 | 1win                | L   | 1.000      | -            | -                | -                | -         |   -16.46 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           53 |     1597 | 2024-05-09 | KOI                 | W   | 1.000      | -            | -                | -                | -         |    13.57 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           52 |     1760 | 2024-05-06 | ENTERPRISE esports  | W   | 1.000      | 0.435        | -                | 0.898 (0.390)    | -         |     8.02 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           51 |     1857 | 2024-05-04 | GamerLegion Academy | W   | 1.000      | -            | -                | -                | -         |     6.51 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           50 |     1965 | 2024-05-02 | Permitta Esports    | W   | 1.000      | 0.384        | -                | 1.000 (0.384)    | -         |    10.88 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           49 |     1992 | 2024-05-01 | Nemiga Gaming       | L   | 1.000      | -            | -                | -                | -         |   -10.16 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           48 |     2014 | 2024-05-01 | V1dar Gaming        | W   | 1.000      | -            | -                | -                | -         |     4.35 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           47 |     2036 | 2024-05-01 | SINNERS Esports     | W   | 1.000      | -            | -                | -                | -         |    12.42 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           46 |     2069 | 2024-04-30 | Alliance            | W   | 1.000      | -            | -                | -                | -         |     9.55 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           45 |     2077 | 2024-04-30 | Zero Tenacity       | L   | 1.000      | -            | -                | -                | -         |   -17.02 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           44 |     2468 | 2024-04-23 | BLEED Esports       | L   | 0.956      | -            | -                | -                | -         |    -8.02 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           43 |     2491 | 2024-04-22 | Passion UA          | W   | 0.951      | 0.500        | 0.057 (0.027)    | 1.000 (0.475)    | -         |    11.27 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           42 |     2517 | 2024-04-22 | Alliance            | L   | 0.949      | -            | -                | -                | -         |   -21.74 | baz, cptkurtka023, esenthial, headtr1ck, npl     |
|           41 |     2567 | 2024-04-21 | PARIVISION          | W   | 0.942      | -            | -                | -                | -         |     7.37 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           40 |     2776 | 2024-04-19 | HAVU Gaming         | W   | 0.929      | -            | -                | -                | -         |     3.82 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           39 |     2851 | 2024-04-18 | Zero Tenacity       | W   | 0.921      | 0.384        | 0.147 (0.052)    | 1.000 (0.354)    | -         |    10.57 | baz, cptkurtka023, esenthial, headtr1ck, npl     |
|           38 |     2911 | 2024-04-17 | Zero Tenacity       | L   | 0.916      | -            | -                | -                | -         |   -18.45 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           37 |     2988 | 2024-04-16 | AMKAL ESPORTS       | L   | 0.908      | -            | -                | -                | -         |   -10.95 | baz, cptkurtka023, esenthial, headtr1ck, npl     |
|           36 |     3008 | 2024-04-15 | Sangal Esports      | L   | 0.904      | -            | -                | -                | -         |   -17.75 | baz, cptkurtka023, esenthial, headtr1ck, npl     |
|           35 |     3266 | 2024-04-10 | Nexus Gaming        | L   | 0.869      | -            | -                | -                | -         |   -19.02 | baz, cptkurtka023, esenthial, headtr1ck, npl     |
|           34 |     3314 | 2024-04-09 | Rebels Gaming       | L   | 0.864      | -            | -                | -                | -         |   -14.05 | baz, cptkurtka023, esenthial, headtr1ck, npl     |
|           33 |     3389 | 2024-04-08 | MOUZ NXT            | L   | 0.856      | -            | -                | -                | -         |   -15.41 | baz, cptkurtka023, esenthial, headtr1ck, npl     |
|           32 |     3684 | 2024-04-02 | Metizport           | L   | 0.817      | -            | -                | -                | -         |   -16.10 | baz, cptkurtka023, esenthial, npl, OWNER         |
|           31 |     3694 | 2024-04-02 | Apeks               | L   | 0.816      | -            | -                | -                | -         |   -10.37 | baz, cptkurtka023, esenthial, npl, OWNER         |
|           30 |     3748 | 2024-03-31 | Apeks               | W   | 0.802      | -            | -                | -                | -         |     1.25 | cptkurtka023, esenthial, npl, OWNER, r1nkle      |
|           29 |     3876 | 2024-03-27 | Rebels Gaming       | W   | 0.778      | -            | -                | -                | -         |    10.71 | baz, cptkurtka023, esenthial, npl, OWNER         |
|           28 |     3891 | 2024-03-27 | Team Sampi          | W   | 0.777      | -            | -                | -                | -         |     7.03 | baz, cptkurtka023, esenthial, npl, OWNER         |
|           27 |     3908 | 2024-03-27 | Gaimin Gladiators   | W   | 0.777      | -            | -                | -                | -         |    17.00 | baz, cptkurtka023, esenthial, npl, OWNER         |
|           26 |     3960 | 2024-03-26 | RUSH B              | W   | 0.771      | -            | -                | -                | -         |     3.03 | baz, cptkurtka023, esenthial, npl, OWNER         |
|           25 |     4019 | 2024-03-25 | FORZE Esports       | W   | 0.764      | -            | -                | -                | -         |     2.37 | cptkurtka023, esenthial, npl, OWNER, r1nkle      |
|           24 |     4203 | 2024-03-21 | BetBoom Team        | L   | 0.736      | -            | -                | -                | -         |    -5.08 | cptkurtka023, esenthial, npl, OWNER, r1nkle      |
|           23 |     4286 | 2024-03-19 | ex-Sprout           | W   | 0.722      | -            | -                | -                | -         |     1.56 | cptkurtka023, esenthial, npl, OWNER, r1nkle      |
|           22 |     4668 | 2024-03-12 | Metizport           | L   | 0.678      | -            | -                | -                | -         |   -12.18 | cptkurtka023, esenthial, npl, OWNER, r1nkle      |
|           21 |     4681 | 2024-03-12 | ENCE                | W   | 0.677      | -            | -                | -                | -         |    18.34 | cptkurtka023, esenthial, npl, OWNER, r1nkle      |
|           20 |     4718 | 2024-03-11 | KOI                 | W   | 0.671      | -            | -                | -                | -         |     8.64 | cptkurtka023, esenthial, npl, OWNER, r1nkle      |
|           19 |     4742 | 2024-03-11 | Virtus.pro          | L   | 0.670      | -            | -                | -                | -         |    -0.80 | cptkurtka023, esenthial, npl, OWNER, r1nkle      |
|           18 |     4879 | 2024-03-08 | PARIVISION          | L   | 0.650      | -            | -                | -                | -         |   -15.80 | cptkurtka023, esenthial, npl, OWNER, r1nkle      |
|           17 |     5081 | 2024-03-05 | Johnny Speeds       | W   | 0.631      | -            | -                | -                | -         |     7.27 | cptkurtka023, esenthial, npl, OWNER, r1nkle      |
|           16 |     5087 | 2024-03-05 | Passion UA          | W   | 0.631      | -            | -                | -                | -         |     5.48 | cptkurtka023, esenthial, npl, OWNER, r1nkle      |
|           15 |     5100 | 2024-03-05 | UGANDA              | W   | 0.631      | -            | -                | -                | -         |     0.75 | cptkurtka023, esenthial, npl, OWNER, r1nkle      |
|           14 |     5135 | 2024-03-04 | Gaimin Gladiators   | W   | 0.625      | -            | -                | -                | -         |    13.58 | cptkurtka023, esenthial, npl, OWNER, r1nkle      |
|           13 |     5174 | 2024-03-04 | Alliance            | W   | 0.625      | -            | -                | -                | -         |     3.64 | cptkurtka023, esenthial, npl, OWNER, r1nkle      |
|           12 |     5271 | 2024-03-02 | Fnatic              | L   | 0.612      | -            | -                | -                | -         |    -9.54 | cptkurtka023, esenthial, npl, OWNER, r1nkle      |
|           11 |     5287 | 2024-03-02 | Infinite Gaming     | W   | 0.611      | -            | -                | -                | -         |     0.62 | cptkurtka023, esenthial, npl, OWNER, r1nkle      |
|           10 |     5522 | 2024-02-27 | DMS                 | L   | 0.584      | -            | -                | -                | -         |   -16.44 | cptkurtka023, esenthial, npl, OWNER, r1nkle      |
|            9 |     5562 | 2024-02-26 | Sprout              | W   | 0.578      | -            | -                | -                | -         |     1.43 | cptkurtka023, esenthial, npl, OWNER, r1nkle      |
|            8 |     6059 | 2024-02-18 | Aurora Gaming       | L   | 0.523      | -            | -                | -                | -         |    -2.50 | cptkurtka023, esenthial, npl, OWNER, r1nkle      |
|            7 |     6158 | 2024-02-16 | 500                 | W   | 0.510      | -            | -                | -                | -         |     2.28 | cptkurtka023, esenthial, npl, OWNER, r1nkle      |
|            6 |     6172 | 2024-02-16 | Tropic              | W   | 0.509      | -            | -                | -                | -         |     0.52 | cptkurtka023, esenthial, npl, OWNER, r1nkle      |
|            5 |     6795 | 2024-02-02 | 9Pandas             | W   | 0.418      | -            | -                | -                | -         |     7.91 | cptkurtka023, esenthial, npl, OWNER, r1nkle      |
|            4 |     6803 | 2024-02-02 | Team Sampi          | W   | 0.417      | -            | -                | -                | -         |     3.58 | cptkurtka023, esenthial, npl, OWNER, r1nkle      |
|            3 |     6812 | 2024-02-02 | GYROCOPTER_UA       | W   | 0.417      | -            | -                | -                | -         |     0.91 | cptkurtka023, esenthial, npl, OWNER, r1nkle      |
|            2 |     6831 | 2024-02-02 | POVYDLO ESPORTS     | W   | 0.417      | -            | -                | -                | -         |     0.24 | cptkurtka023, esenthial, npl, OWNER, r1nkle      |
|            1 |     7017 | 2024-01-29 | Into The Breach     | L   | 0.392      | -            | -                | -                | -         |   -10.98 | cptkurtka023, esenthial, npl, OWNER, r1nkle      |

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
