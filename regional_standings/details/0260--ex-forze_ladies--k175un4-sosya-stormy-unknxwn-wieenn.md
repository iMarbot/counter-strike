### Roster Details<br />
Team Name: ex-FORZE Ladies<br />
Roster: k175un4, sosya, Stormy, unknxwn, wieenn<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [260](../standings_global.md)<br />
Regional Rank: [167]( ../standings_europe.md)<br />
Final Rank Value:  677.1<br />
<br />
Final Rank Value (677.1) = Starting Rank Value (679.4) + Head To Head Adjustments (-2.3)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.302[<sup>1</sup>](#table2)
- Bounty Collected: 0.224[<sup>2</sup>](#table1)
- Opponent Network: 0.023[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.137<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 679.4
- 400 + ( ( 0.137 - 0.000 ) / ( 0.786 - 0.000 ) ) * 1600 = 679.4


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent           | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                         |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           24 |      218 | 2024-05-26 | NIP Impact         | L   | 1.000      | -            | -                | -                | -         |   -13.08 | k175un4, sosya, Stormy, unknxwn, wieenn        |
|           23 |      268 | 2024-05-25 | Nemesis            | W   | 1.000      | 0.250        | 0.000 (0.000)    | 0.102 (0.026)    | 0 (0.000) |     8.94 | k175un4, sosya, Stormy, unknxwn, wieenn        |
|           22 |      915 | 2024-05-18 | Crescent           | L   | 1.000      | -            | -                | -                | -         |   -16.57 | k175un4, sosya, Stormy, trigusha, wieenn       |
|           21 |     2982 | 2024-04-14 | Team Spirit Female | W   | 0.896      | 0.250        | 0.005 (0.001)    | 0.216 (0.048)    | 0 (0.000) |    12.96 | k175un4, sosya, Stormy, trigusha, wieenn       |
|           20 |     3024 | 2024-04-13 | Nemesis            | W   | 0.890      | 0.250        | 0.000 (0.000)    | 0.102 (0.023)    | 0 (0.000) |     7.83 | k175un4, sosya, Stormy, trigusha, wieenn       |
|           19 |     3034 | 2024-04-13 | 5bites             | W   | 0.890      | -            | -                | -                | 0 (0.000) |     4.70 | k175un4, sosya, Stormy, trigusha, wieenn       |
|           18 |     3328 | 2024-04-07 | ENCE Athena        | W   | 0.851      | 0.250        | 0.004 (0.001)    | 0.215 (0.046)    | 0 (0.000) |    13.90 | k175un4, sosya, Stormy, trigusha, wieenn       |
|           17 |     3343 | 2024-04-07 | Nemesis            | W   | 0.849      | 0.250        | -                | 0.102 (0.022)    | 0 (0.000) |     8.15 | k175un4, sosya, Stormy, trigusha, wieenn       |
|           16 |     3384 | 2024-04-06 | Permitta W         | W   | 0.843      | 0.250        | -                | 0.051 (0.011)    | 0 (0.000) |     8.16 | k175un4, sosya, Stormy, trigusha, wieenn       |
|           15 |     3414 | 2024-04-06 | BIG EQUIPA         | L   | 0.841      | -            | -                | -                | -         |   -10.19 | k175un4, sosya, Stormy, trigusha, wieenn       |
|           14 |     4327 | 2024-03-16 | 1win Gang          | L   | 0.704      | -            | -                | -                | -         |   -11.71 | Deylary, donotbesadd, miu_u, panifika, unknxwn |
|           13 |     5070 | 2024-03-03 | BIG EQUIPA         | L   | 0.618      | -            | -                | -                | -         |    -8.21 | JennyR, juliano, kyossa, pauliiee, Zana        |
|           12 |     5097 | 2024-03-03 | more whiskey       | W   | 0.617      | 0.250        | -                | 0.056 (0.009)    | 0 (0.000) |     6.40 | k175un4, sosya, Stormy, trigusha, wieenn       |
|           11 |     5179 | 2024-03-02 | Team Spirit Female | W   | 0.610      | 0.250        | 0.005 (0.001)    | 0.216 (0.033)    | 0 (0.000) |    10.36 | k175un4, sosya, Stormy, trigusha, wieenn       |
|           10 |     5561 | 2024-02-24 | ENCE Athena        | L   | 0.562      | -            | -                | -                | -         |    -8.35 | c0ldhurt, mikeri, sosya, Stormy, wieenn        |
|            9 |     5864 | 2024-02-18 | Astralis Women     | L   | 0.525      | -            | -                | -                | -         |    -9.13 | anja, aurora, Ismo, josefine, marie            |
|            8 |     5872 | 2024-02-18 | Crescent           | L   | 0.524      | -            | -                | -                | -         |    -7.96 | k175un4, mikeri, sosya, Stormy, wieenn         |
|            7 |     5928 | 2024-02-17 | Nemesis            | W   | 0.518      | 0.143        | 0.002 (0.000)    | 0.089 (0.007)    | 0 (0.000) |     7.09 | amyb, Emmy, Gaba, Lowlita, Monkey D. Julie     |
|            6 |     6956 | 2024-01-27 | BIG EQUIPA         | L   | 0.377      | -            | -                | -                | -         |    -5.72 | JennyR, juliano, kyossa, pauliiee, Zana        |
|            5 |     7275 | 2024-01-21 | ex-Guild Esports   | L   | 0.337      | -            | -                | -                | -         |    -5.07 | DeJaWoo, k175un4, sosya, Stormy, wieenn        |
|            4 |     7332 | 2024-01-20 | 1win Gang          | W   | 0.331      | 0.250        | 0.004 (0.000)    | 0.118 (0.010)    | -         |     4.85 | Deylary, f6tal, miu_u, Potya, unknxwn          |
|            3 |     9355 | 2023-12-03 | woof woof          | W   | 0.011      | 0.250        | 0.000 (0.000)    | -                | -         |     0.12 | DeJaWoo, k175un4, sosya, Stormy, wieenn        |
|            2 |     9369 | 2023-12-03 | Team Spirit Female | W   | 0.010      | 0.250        | 0.005 (0.000)    | -                | -         |     0.16 | AverOna, Jammie, Rony4ka, tenweri, uulis       |
|            1 |     9472 | 2023-12-02 | 1win Gang          | W   | 0.004      | 0.250        | 0.004 (0.000)    | -                | -         |     0.06 | DeJaWoo, k175un4, sosya, Stormy, wieenn        |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($1,472.86)
- Divide that value by the 5th highest value among all rosters ($300,806.11)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-04-14 |      0.896 | $750.00        | $672.08         |
| 2024-04-07 |      0.851 | $750.00        | $638.07         |
| 2024-03-03 |      0.618 | $250.00        | $154.43         |
| 2023-12-03 |      0.011 | $750.00        | $8.28           |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
