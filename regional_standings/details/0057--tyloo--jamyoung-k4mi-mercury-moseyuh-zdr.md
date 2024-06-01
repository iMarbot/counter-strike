### Roster Details<br />
Team Name: TYLOO<br />
Roster: JamYoung, k4Mi, Mercury, Moseyuh, zdr<br />
Region: [Asia]( ../standings_asia.md)<br />
<br />
Global Rank: [57](../standings_global.md)<br />
Regional Rank: [5]( ../standings_asia.md)<br />
Final Rank Value:  1016.1<br />
<br />
Final Rank Value (1016.1) = Starting Rank Value (914.8) + Head To Head Adjustments (101.3)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.408[<sup>1</sup>](#table2)
- Bounty Collected: 0.352[<sup>2</sup>](#table1)
- Opponent Network: 0.149[<sup>2</sup>](#table1)
- LAN Wins: 0.103[<sup>2</sup>](#table1)

The average of these factors is 0.253<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 914.8
- 400 + ( ( 0.253 - 0.000 ) / ( 0.786 - 0.000 ) ) * 1600 = 914.8


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent           | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                  |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           39 |      508 | 2024-05-22 | ATOX Esports       | W   | 1.000      | 0.417        | 0.047 (0.020)    | 0.601 (0.251)    | 0 (0.000) |    18.82 | JamYoung, k4Mi, Mercury, Moseyuh, zdr   |
|           38 |      514 | 2024-05-22 | ATOX Esports       | L   | 1.000      | -            | -                | -                | -         |   -12.41 | JamYoung, k4Mi, Mercury, Moseyuh, zdr   |
|           37 |      610 | 2024-05-21 | The QUBE Esports   | W   | 1.000      | -            | -                | -                | 0 (0.000) |     4.54 | JamYoung, k4Mi, Mercury, Moseyuh, zdr   |
|           36 |      617 | 2024-05-21 | The QUBE Esports   | W   | 1.000      | -            | -                | -                | 0 (0.000) |     4.75 | JamYoung, k4Mi, Mercury, Moseyuh, zdr   |
|           35 |      999 | 2024-05-17 | LYG Gaming         | W   | 1.000      | 0.417        | -                | 0.275 (0.115)    | 0 (0.000) |     6.51 | JamYoung, k4Mi, Mercury, Moseyuh, zdr   |
|           34 |     1008 | 2024-05-17 | LYG Gaming         | W   | 1.000      | 0.417        | -                | 0.275 (0.115)    | 0 (0.000) |     6.91 | JamYoung, k4Mi, Mercury, Moseyuh, zdr   |
|           33 |     1090 | 2024-05-16 | Clutch Gaming      | W   | 1.000      | -            | -                | -                | 0 (0.000) |     6.76 | JamYoung, k4Mi, Mercury, Moseyuh, zdr   |
|           32 |     1098 | 2024-05-16 | Clutch Gaming      | W   | 1.000      | -            | -                | -                | 0 (0.000) |     7.18 | JamYoung, k4Mi, Mercury, Moseyuh, zdr   |
|           31 |     1181 | 2024-05-15 | DEWA United        | W   | 1.000      | 0.417        | 0.002 (0.001)    | 0.185 (0.077)    | 0 (0.000) |     5.71 | JamYoung, k4Mi, Mercury, Moseyuh, zdr   |
|           30 |     1190 | 2024-05-15 | DEWA United        | W   | 1.000      | 0.417        | -                | 0.185 (0.077)    | 0 (0.000) |     6.02 | JamYoung, k4Mi, Mercury, Moseyuh, zdr   |
|           29 |     1281 | 2024-05-14 | Gods Reign         | W   | 1.000      | 0.417        | 0.086 (0.036)    | 0.461 (0.192)    | -         |    10.67 | JamYoung, k4Mi, Mercury, Moseyuh, zdr   |
|           28 |     1287 | 2024-05-14 | Gods Reign         | W   | 1.000      | 0.417        | 0.086 (0.036)    | 0.461 (0.192)    | -         |    11.56 | JamYoung, k4Mi, Mercury, Moseyuh, zdr   |
|           27 |     2184 | 2024-04-27 | M80                | L   | 0.983      | -            | -                | -                | -         |    -3.65 | advent, JamYoung, kaze, Mercury, zdr    |
|           26 |     2249 | 2024-04-26 | Sharks Esports     | W   | 0.977      | 0.889        | 0.031 (0.027)    | 0.365 (0.317)    | 1 (0.977) |    13.84 | advent, JamYoung, kaze, Mercury, zdr    |
|           25 |     2326 | 2024-04-25 | Team Falcons       | L   | 0.969      | -            | -                | -                | -         |    -1.72 | advent, JamYoung, kaze, Mercury, zdr    |
|           24 |     2389 | 2024-04-24 | G2 Esports         | L   | 0.962      | -            | -                | -                | -         |    -0.23 | advent, JamYoung, kaze, Mercury, zdr    |
|           23 |     2729 | 2024-04-19 | Rare Atom          | L   | 0.928      | -            | -                | -                | -         |   -17.95 | advent, JamYoung, kaze, Mercury, zdr    |
|           22 |     2775 | 2024-04-18 | The MongolZ        | L   | 0.923      | -            | -                | -                | -         |    -0.97 | advent, JamYoung, kaze, Mercury, zdr    |
|           21 |     2791 | 2024-04-18 | Lynn Vision Gaming | W   | 0.922      | 0.143        | 0.063 (0.008)    | -                | -         |    19.96 | advent, JamYoung, kaze, Mercury, zdr    |
|           20 |     2857 | 2024-04-17 | Sheer Conquer      | W   | 0.915      | 0.143        | 0.017 (0.002)    | -                | -         |     9.76 | advent, JamYoung, kaze, Mercury, zdr    |
|           19 |     2862 | 2024-04-17 | The Huns Esports   | W   | 0.915      | -            | -                | -                | -         |    12.32 | advent, JamYoung, kaze, Mercury, zdr    |
|           18 |     2921 | 2024-04-16 | Aravt              | W   | 0.909      | -            | -                | -                | -         |     1.58 | advent, JamYoung, kaze, Mercury, zdr    |
|           17 |     3307 | 2024-04-08 | Lynn Vision Gaming | L   | 0.856      | -            | -                | -                | -         |    -6.66 | advent, JamYoung, kaze, Mercury, zdr    |
|           16 |     3319 | 2024-04-07 | MOUZ               | L   | 0.854      | -            | -                | -                | -         |    -0.07 | advent, JamYoung, kaze, Mercury, zdr    |
|           15 |     3510 | 2024-04-04 | MIRAI Gaming       | W   | 0.829      | -            | -                | -                | -         |     5.58 | JamYoung, k4Mi, Mercury, Moseyuh, zdr   |
|           14 |     3514 | 2024-04-04 | MIRAI Gaming       | W   | 0.829      | -            | -                | -                | -         |     5.87 | JamYoung, k4Mi, Mercury, Moseyuh, zdr   |
|           13 |     3679 | 2024-03-30 | NewHappy           | W   | 0.796      | 0.417        | 0.020 (0.007)    | 0.231 (0.077)    | -         |     8.15 | JamYoung, k4Mi, Mercury, Moseyuh, zdr   |
|           12 |     3680 | 2024-03-30 | NewHappy           | W   | 0.796      | 0.417        | 0.020 (0.007)    | 0.231 (0.077)    | -         |     8.68 | JamYoung, k4Mi, Mercury, Moseyuh, zdr   |
|           11 |     3711 | 2024-03-29 | GR Gaming          | L   | 0.789      | -            | -                | -                | -         |   -13.82 | JamYoung, k4Mi, Mercury, Moseyuh, zdr   |
|           10 |     3714 | 2024-03-29 | GR Gaming          | L   | 0.789      | -            | -                | -                | -         |   -14.80 | JamYoung, k4Mi, Mercury, Moseyuh, zdr   |
|            9 |     3893 | 2024-03-26 | ZEUSGG             | W   | 0.770      | -            | -                | -                | -         |     2.47 | JamYoung, k4Mi, Mercury, Moseyuh, zdr   |
|            8 |     3897 | 2024-03-26 | ZEUSGG             | W   | 0.769      | -            | -                | -                | -         |     2.53 | JamYoung, k4Mi, Mercury, Moseyuh, zdr   |
|            7 |     4434 | 2024-03-14 | -72C               | W   | 0.690      | -            | -                | -                | -         |     7.48 | JamYoung, k4Mi, Mercury, Moseyuh, zdr   |
|            6 |     4439 | 2024-03-14 | -72C               | L   | 0.689      | -            | -                | -                | -         |   -14.62 | JamYoung, k4Mi, Mercury, Moseyuh, zdr   |
|            5 |     4511 | 2024-03-13 | LYG Gaming         | L   | 0.682      | -            | -                | -                | -         |   -16.26 | advent, JamYoung, lyrics3, Mercury, zdr |
|            4 |     4514 | 2024-03-13 | TyPuCTbl           | W   | 0.682      | -            | -                | -                | -         |     3.49 | advent, JamYoung, lyrics3, Mercury, zdr |
|            3 |     4570 | 2024-03-12 | Noobs But Diligent | W   | 0.676      | 0.143        | 0.014 (0.001)    | -                | -         |     6.10 | advent, JamYoung, lyrics3, Mercury, zdr |
|            2 |     4888 | 2024-03-06 | Born In Far East   | W   | 0.636      | -            | -                | -                | -         |     3.55 | JamYoung, k4Mi, Mercury, Moseyuh, zdr   |
|            1 |     4893 | 2024-03-06 | Born In Far East   | W   | 0.636      | -            | -                | -                | -         |     3.67 | JamYoung, k4Mi, Mercury, Moseyuh, zdr   |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($10,580.65)
- Divide that value by the 5th highest value among all rosters ($300,806.11)
- The final value (0.04) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-05-12 |      1.000 | $7,000.00      | $7,000.00       |
| 2024-04-14 |      0.895 | $4,000.00      | $3,580.65       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
