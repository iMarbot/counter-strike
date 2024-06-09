### Roster Details<br />
Team Name: Virtus.pro<br />
Roster: electroNic, fame, FL1T, Jame, n0rb3r7<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [11](../standings_global.md)<br />
Regional Rank: [10]( ../standings_europe.md)<br />
Final Rank Value:  1613.5<br />
<br />
Final Rank Value (1613.5) = Starting Rank Value (1693.4) + Head To Head Adjustments (-80.0)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.638[<sup>1</sup>](#table2)
- Bounty Collected: 0.575[<sup>2</sup>](#table1)
- Opponent Network: 0.340[<sup>2</sup>](#table1)
- LAN Wins: 0.993[<sup>2</sup>](#table1)

The average of these factors is 0.636<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1693.4
- 400 + ( ( 0.636 - 0.000 ) / ( 0.787 - 0.000 ) ) * 1600 = 1693.4


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent          | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           47 |       77 | 2024-05-29 | BIG               | L   | 1.000      | -            | -                | -                | -         |   -25.27 | electroNic, fame, FL1T, Jame, n0rb3r7 |
|           46 |      117 | 2024-05-28 | FaZe Clan         | L   | 1.000      | -            | -                | -                | -         |    -4.77 | electroNic, fame, FL1T, Jame, n0rb3r7 |
|           45 |      158 | 2024-05-27 | HEROIC            | W   | 1.000      | 0.624        | 0.322 (0.201)    | 0.463 (0.289)    | 1 (1.000) |    14.21 | electroNic, fame, FL1T, Jame, n0rb3r7 |
|           44 |     1017 | 2024-05-17 | Team Falcons      | L   | 1.000      | -            | -                | -                | -         |   -24.22 | electroNic, fame, FL1T, Jame, n0rb3r7 |
|           43 |     1111 | 2024-05-16 | MOUZ              | L   | 1.000      | -            | -                | -                | -         |    -4.24 | electroNic, fame, FL1T, Jame, n0rb3r7 |
|           42 |     1269 | 2024-05-14 | Team Falcons      | W   | 1.000      | 0.769        | 0.355 (0.273)    | -                | 1 (1.000) |     6.31 | electroNic, fame, FL1T, Jame, n0rb3r7 |
|           41 |     1587 | 2024-05-09 | Complexity Gaming | L   | 1.000      | -            | -                | -                | -         |   -18.34 | electroNic, fame, FL1T, Jame, n0rb3r7 |
|           40 |     1628 | 2024-05-08 | The MongolZ       | W   | 1.000      | 0.889        | 0.192 (0.171)    | 0.619 (0.550)    | 1 (1.000) |    11.84 | electroNic, fame, FL1T, Jame, n0rb3r7 |
|           39 |     1684 | 2024-05-07 | GamerLegion       | W   | 1.000      | 0.889        | 0.224 (0.199)    | 0.210 (0.187)    | 1 (1.000) |     2.97 | electroNic, fame, FL1T, Jame, n0rb3r7 |
|           38 |     2150 | 2024-04-28 | SAW               | W   | 0.990      | 0.889        | 0.112 (0.098)    | 0.388 (0.341)    | 1 (0.990) |     6.04 | electroNic, fame, FL1T, Jame, n0rb3r7 |
|           37 |     2238 | 2024-04-27 | Fnatic            | W   | 0.982      | 0.889        | 0.147 (0.129)    | 0.480 (0.419)    | 1 (0.982) |     1.89 | electroNic, fame, FL1T, Jame, n0rb3r7 |
|           36 |     2344 | 2024-04-25 | FaZe Clan         | L   | 0.970      | -            | -                | -                | -         |    -4.95 | electroNic, fame, FL1T, Jame, n0rb3r7 |
|           35 |     2425 | 2024-04-24 | SAW               | W   | 0.963      | 0.889        | 0.112 (0.095)    | 0.388 (0.332)    | 1 (0.963) |     4.91 | electroNic, fame, FL1T, Jame, n0rb3r7 |
|           34 |     2479 | 2024-04-23 | Fnatic            | L   | 0.955      | -            | -                | -                | -         |   -28.52 | electroNic, fame, FL1T, Jame, n0rb3r7 |
|           33 |     3159 | 2024-04-11 | G2 Esports        | L   | 0.881      | -            | -                | -                | -         |    -9.37 | fame, FL1T, Jame, mir, n0rb3r7        |
|           32 |     3285 | 2024-04-10 | Astralis          | L   | 0.868      | -            | -                | -                | -         |   -15.37 | fame, FL1T, Jame, mir, n0rb3r7        |
|           31 |     3354 | 2024-04-08 | FlyQuest          | W   | 0.860      | 0.624        | -                | 0.466 (0.250)    | 1 (0.860) |     5.25 | fame, FL1T, Jame, mir, n0rb3r7        |
|           30 |     3398 | 2024-04-07 | Wildcard Gaming   | W   | 0.854      | 0.624        | -                | 0.525 (0.280)    | 1 (0.854) |     0.39 | fame, FL1T, Jame, mir, n0rb3r7        |
|           29 |     4044 | 2024-03-24 | G2 Esports        | L   | 0.756      | -            | -                | -                | -         |    -8.90 | fame, FL1T, Jame, mir, n0rb3r7        |
|           28 |     4108 | 2024-03-23 | Eternal Fire      | L   | 0.749      | -            | -                | -                | -         |    -7.36 | fame, FL1T, Jame, mir, n0rb3r7        |
|           27 |     4141 | 2024-03-22 | HEROIC            | W   | 0.743      | 1.000        | 0.322 (0.239)    | 0.463 (0.344)    | 1 (0.743) |    12.49 | fame, FL1T, Jame, mir, n0rb3r7        |
|           26 |     4184 | 2024-03-21 | paiN Gaming       | W   | 0.738      | 1.000        | 0.463 (0.342)    | 0.547 (0.403)    | -         |     7.60 | fame, FL1T, Jame, mir, n0rb3r7        |
|           25 |     4197 | 2024-03-21 | Imperial Esports  | L   | 0.736      | -            | -                | -                | -         |   -17.91 | fame, FL1T, Jame, mir, n0rb3r7        |
|           24 |     4669 | 2024-03-12 | HEROIC            | W   | 0.678      | -            | -                | -                | -         |    11.15 | fame, FL1T, Jame, mir, n0rb3r7        |
|           23 |     4719 | 2024-03-11 | Apeks             | W   | 0.671      | -            | -                | -                | -         |     1.72 | fame, FL1T, Jame, mir, n0rb3r7        |
|           22 |     4742 | 2024-03-11 | B8                | W   | 0.670      | -            | -                | -                | -         |     0.80 | fame, FL1T, Jame, mir, n0rb3r7        |
|           21 |     6228 | 2024-02-15 | Natus Vincere     | W   | 0.503      | 0.143        | 1.000 (0.072)    | -                | -         |    11.51 | fame, FL1T, Jame, mir, n0rb3r7        |
|           20 |     6269 | 2024-02-14 | Fnatic            | W   | 0.498      | -            | -                | -                | -         |     0.66 | fame, FL1T, Jame, mir, n0rb3r7        |
|           19 |     6311 | 2024-02-14 | SAW               | W   | 0.496      | -            | -                | -                | -         |     2.20 | fame, FL1T, Jame, mir, n0rb3r7        |
|           18 |     6823 | 2024-02-02 | Cloud9            | L   | 0.417      | -            | -                | -                | -         |    -9.82 | fame, FL1T, Jame, mir, n0rb3r7        |
|           17 |     6895 | 2024-02-01 | GamerLegion       | L   | 0.409      | -            | -                | -                | -         |   -12.00 | fame, FL1T, Jame, mir, n0rb3r7        |
|           16 |     6921 | 2024-01-31 | Rooster           | W   | 0.404      | -            | -                | -                | -         |     0.08 | fame, FL1T, Jame, mir, n0rb3r7        |
|           15 |     7161 | 2024-01-27 | BIG               | W   | 0.378      | -            | -                | -                | -         |     2.02 | fame, FL1T, Jame, mir, n0rb3r7        |
|           14 |     7312 | 2024-01-25 | Cloud9            | W   | 0.363      | -            | -                | -                | -         |     2.94 | fame, FL1T, Jame, mir, n0rb3r7        |
|           13 |     7348 | 2024-01-24 | BIG               | W   | 0.357      | -            | -                | -                | -         |     1.82 | fame, FL1T, Jame, mir, n0rb3r7        |
|           12 |     7590 | 2024-01-20 | Fnatic            | W   | 0.330      | -            | -                | -                | -         |     0.42 | fame, FL1T, Jame, mir, n0rb3r7        |
|           11 |     7653 | 2024-01-19 | Natus Vincere     | L   | 0.324      | -            | -                | -                | -         |    -2.91 | fame, FL1T, Jame, mir, n0rb3r7        |
|           10 |     7713 | 2024-01-18 | SAW               | W   | 0.317      | -            | -                | -                | -         |     1.34 | fame, FL1T, Jame, mir, n0rb3r7        |
|            9 |     7735 | 2024-01-18 | SINNERS Esports   | W   | 0.317      | -            | -                | -                | -         |     0.23 | fame, FL1T, Jame, mir, n0rb3r7        |
|            8 |     8695 | 2023-12-17 | Apeks             | W   | 0.105      | -            | -                | -                | -         |     0.23 | fame, FL1T, Jame, mir, n0rb3r7        |
|            7 |     8733 | 2023-12-17 | The MongolZ       | W   | 0.103      | -            | -                | -                | -         |     1.25 | fame, FL1T, Jame, mir, n0rb3r7        |
|            6 |     8979 | 2023-12-15 | Monte             | W   | 0.092      | -            | -                | -                | -         |     0.32 | fame, FL1T, Jame, mir, n0rb3r7        |
|            5 |     9005 | 2023-12-15 | M80               | W   | 0.091      | -            | -                | -                | -         |     0.25 | fame, FL1T, Jame, mir, n0rb3r7        |
|            4 |     9254 | 2023-12-10 | Team Spirit       | L   | 0.056      | -            | -                | -                | -         |    -0.41 | fame, FL1T, Jame, mir, n0rb3r7        |
|            3 |     9315 | 2023-12-09 | BetBoom Team      | W   | 0.049      | -            | -                | -                | -         |     0.29 | fame, FL1T, Jame, mir, n0rb3r7        |
|            2 |     9462 | 2023-12-07 | Team Spirit       | W   | 0.035      | -            | -                | -                | -         |     0.84 | fame, FL1T, Jame, mir, n0rb3r7        |
|            1 |     9526 | 2023-12-06 | Astralis          | W   | 0.028      | -            | -                | -                | -         |     0.42 | fame, FL1T, Jame, mir, n0rb3r7        |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($81,404.00)
- Divide that value by the 5th highest value among all rosters ($300,806.11)
- The final value (0.27) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-05-29 |      1.000 | $5,000.00      | $5,000.00       |
| 2024-05-12 |      1.000 | $32,000.00     | $32,000.00      |
| 2024-04-14 |      0.895 | $10,000.00     | $8,951.62       |
| 2024-03-31 |      0.804 | $20,000.00     | $16,077.78      |
| 2024-02-11 |      0.477 | $4,500.00      | $2,146.25       |
| 2024-01-28 |      0.384 | $22,500.00     | $8,640.63       |
| 2023-12-17 |      0.105 | $50,000.00     | $5,255.79       |
| 2023-12-10 |      0.056 | $60,000.00     | $3,331.94       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
