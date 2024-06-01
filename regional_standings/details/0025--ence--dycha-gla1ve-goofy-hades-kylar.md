### Roster Details<br />
Team Name: ENCE<br />
Roster: dycha, gla1ve, Goofy, hades, Kylar<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [25](../standings_global.md)<br />
Regional Rank: [17]( ../standings_europe.md)<br />
Final Rank Value:  1304.7<br />
<br />
Final Rank Value (1304.7) = Starting Rank Value (1428.2) + Head To Head Adjustments (-123.5)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.590[<sup>1</sup>](#table2)
- Bounty Collected: 0.517[<sup>2</sup>](#table1)
- Opponent Network: 0.277[<sup>2</sup>](#table1)
- LAN Wins: 0.636[<sup>2</sup>](#table1)

The average of these factors is 0.505<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1428.2
- 400 + ( ( 0.505 - 0.000 ) / ( 0.786 - 0.000 ) ) * 1600 = 1428.2


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent           | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                   |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           39 |      621 | 2024-05-21 | Team Liquid        | L   | 1.000      | -            | -                | -                | -         |    -4.64 | dycha, gla1ve, Goofy, hades, Kylar       |
|           38 |      890 | 2024-05-18 | Fnatic             | W   | 1.000      | 0.769        | 0.147 (0.113)    | 0.480 (0.369)    | -         |     9.70 | dycha, gla1ve, Goofy, hades, Kylar       |
|           37 |      949 | 2024-05-17 | Gaimin Gladiators  | W   | 1.000      | 0.769        | 0.092 (0.071)    | 0.711 (0.546)    | -         |     9.13 | dycha, gla1ve, Goofy, hades, Kylar       |
|           36 |      993 | 2024-05-17 | Fnatic             | L   | 1.000      | -            | -                | -                | -         |   -21.48 | dycha, gla1ve, Goofy, hades, Kylar       |
|           35 |     1823 | 2024-05-04 | FURIA Esports      | L   | 1.000      | -            | -                | -                | -         |   -14.04 | dycha, gla1ve, Goofy, hades, Kylar       |
|           34 |     1883 | 2024-05-03 | GamerLegion        | L   | 1.000      | -            | -                | -                | -         |   -19.66 | dycha, gla1ve, Goofy, hades, Kylar       |
|           33 |     1912 | 2024-05-02 | Monte              | W   | 1.000      | 0.889        | 0.181 (0.161)    | 0.363 (0.322)    | 1 (1.000) |    10.88 | dycha, gla1ve, Goofy, hades, Kylar       |
|           32 |     1988 | 2024-05-01 | Bad News Kangaroos | W   | 1.000      | 0.889        | 0.031 (0.028)    | 0.241 (0.214)    | 1 (1.000) |     2.66 | dycha, gla1ve, Goofy, hades, Kylar       |
|           31 |     2038 | 2024-04-30 | GamerLegion        | L   | 1.000      | -            | -                | -                | -         |   -21.15 | dycha, gla1ve, Goofy, hades, Kylar       |
|           30 |     2712 | 2024-04-19 | AMKAL ESPORTS      | L   | 0.929      | -            | -                | -                | -         |   -21.99 | dycha, gla1ve, Goofy, hades, Kylar       |
|           29 |     2853 | 2024-04-17 | ENTERPRISE esports | W   | 0.916      | 0.384        | -                | 0.809 (0.285)    | -         |     1.84 | dycha, gla1ve, Goofy, hades, Kylar       |
|           28 |     3187 | 2024-04-10 | OG                 | L   | 0.869      | -            | -                | -                | -         |   -19.98 | dycha, gla1ve, Goofy, hades, Kylar       |
|           27 |     3300 | 2024-04-08 | FORZE Esports      | L   | 0.856      | -            | -                | -                | -         |   -23.48 | dycha, gla1ve, Goofy, hades, Kylar       |
|           26 |     3513 | 2024-04-04 | Aurora Young Blud  | W   | 0.829      | 0.384        | -                | 0.506 (0.161)    | -         |     0.67 | dycha, gla1ve, Goofy, hades, Kylar       |
|           25 |     4169 | 2024-03-19 | FURIA Esports      | L   | 0.724      | -            | -                | -                | -         |   -11.93 | dycha, gla1ve, Goofy, hades, Kylar       |
|           24 |     4221 | 2024-03-18 | paiN Gaming        | L   | 0.716      | -            | -                | -                | -         |    -7.12 | dycha, gla1ve, Goofy, hades, Kylar       |
|           23 |     4235 | 2024-03-17 | KOI                | W   | 0.712      | 1.000        | 0.027 (0.020)    | 0.430 (0.306)    | 1 (0.712) |     2.34 | dycha, gla1ve, Goofy, hades, Kylar       |
|           22 |     4284 | 2024-03-17 | Imperial Esports   | L   | 0.710      | -            | -                | -                | -         |    -9.76 | dycha, gla1ve, Goofy, hades, Kylar       |
|           21 |     4561 | 2024-03-12 | B8                 | L   | 0.677      | -            | -                | -                | -         |   -18.34 | dycha, gla1ve, Goofy, hades, Kylar       |
|           20 |     4601 | 2024-03-11 | HEROIC             | L   | 0.671      | -            | -                | -                | -         |    -4.11 | dycha, gla1ve, Goofy, hades, Kylar       |
|           19 |     4623 | 2024-03-11 | Metizport          | W   | 0.670      | -            | -                | -                | -         |     1.99 | dycha, gla1ve, Goofy, hades, Kylar       |
|           18 |     5669 | 2024-02-22 | Astralis           | W   | 0.549      | 0.143        | 0.395 (0.031)    | -                | 1 (0.549) |    12.95 | dycha, gla1ve, Goofy, hades, Kylar       |
|           17 |     5718 | 2024-02-21 | Team Vitality      | L   | 0.543      | -            | -                | -                | -         |    -1.87 | dycha, gla1ve, Goofy, hades, Kylar       |
|           16 |     5783 | 2024-02-20 | GamerLegion        | W   | 0.536      | -            | -                | -                | 1 (0.536) |     4.24 | dycha, gla1ve, Goofy, hades, Kylar       |
|           15 |     5833 | 2024-02-19 | ex-Guild Eagles    | W   | 0.530      | -            | -                | -                | 1 (0.530) |     1.04 | dycha, gla1ve, Goofy, hades, Kylar       |
|           14 |     5849 | 2024-02-19 | Team Spirit        | L   | 0.529      | -            | -                | -                | -         |    -1.10 | dycha, gla1ve, Goofy, hades, Kylar       |
|           13 |     6294 | 2024-02-09 | Team Falcons       | L   | 0.464      | -            | -                | -                | -         |    -6.33 | dycha, gla1ve, Goofy, hades, Kylar       |
|           12 |     6374 | 2024-02-06 | MOUZ               | L   | 0.444      | -            | -                | -                | -         |    -0.74 | dycha, gla1ve, Goofy, hades, Kylar       |
|           11 |     6431 | 2024-02-05 | G2 Esports         | W   | 0.437      | 1.000        | 0.468 (0.205)    | 0.392 (0.171)    | 1 (0.437) |    12.12 | dycha, gla1ve, Goofy, hades, Kylar       |
|           10 |     6494 | 2024-02-03 | Team Vitality      | W   | 0.425      | 1.000        | 0.696 (0.295)    | 0.320 (0.136)    | 1 (0.425) |    12.21 | dycha, gla1ve, Goofy, hades, Kylar       |
|            9 |     6620 | 2024-02-02 | The MongolZ        | W   | 0.417      | 1.000        | 0.192 (0.080)    | 0.619 (0.258)    | 1 (0.417) |     9.52 | dycha, gla1ve, Goofy, hades, Kylar       |
|            8 |     6658 | 2024-02-01 | Astralis           | W   | 0.411      | 1.000        | 0.395 (0.163)    | -                | 1 (0.411) |    10.45 | dycha, gla1ve, Goofy, hades, Kylar       |
|            7 |     6723 | 2024-01-31 | BIG                | L   | 0.404      | -            | -                | -                | -         |    -6.19 | dycha, gla1ve, Goofy, hades, Kylar       |
|            6 |     7554 | 2024-01-17 | ENTERPRISE esports | L   | 0.311      | -            | -                | -                | -         |    -9.74 | dycha, gla1ve, Goofy, hades, Kylar       |
|            5 |     8831 | 2023-12-13 | BIG                | L   | 0.078      | -            | -                | -                | -         |    -1.20 | Krimbo, mantuu, prosus, s1n, tabseN      |
|            4 |     8850 | 2023-12-13 | BetBoom Team       | W   | 0.076      | -            | -                | -                | -         |     1.21 | Goofy, hades, jcobbb, KEi, Kylar         |
|            3 |     8895 | 2023-12-12 | FORZE Esports      | W   | 0.068      | -            | -                | -                | -         |     0.04 | gokushima, kelieN, r3salt, shalfey, tN1R |
|            2 |     9218 | 2023-12-06 | EYEBALLERS         | L   | 0.031      | -            | -                | -                | -         |    -0.92 | HEAP, JW, Peppzor, Sapec, SHiNE          |
|            1 |     9289 | 2023-12-05 | SINNERS Esports    | L   | 0.024      | -            | -                | -                | -         |    -0.70 | beastik, KWERTZZ, oskar, SHOCK, ZEDKO    |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($60,676.75)
- Divide that value by the 5th highest value among all rosters ($300,806.11)
- The final value (0.20) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-05-23 |      1.000 | $12,500.00     | $12,500.00      |
| 2024-05-12 |      1.000 | $7,000.00      | $7,000.00       |
| 2024-04-14 |      0.896 | $15,000.00     | $13,443.75      |
| 2024-03-31 |      0.804 | $10,000.00     | $8,038.89       |
| 2024-02-11 |      0.477 | $40,000.00     | $19,077.78      |
| 2023-12-13 |      0.078 | $3,500.00      | $271.33         |
| 2023-12-10 |      0.058 | $6,000.00      | $345.00         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
