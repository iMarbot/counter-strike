### Roster Details<br />
Team Name: The MongolZ<br />
Roster: 910, bLitz, mzinho, Senzu, Techno4K<br />
Region: [Asia]( ../standings_asia.md)<br />
<br />
Global Rank: [13](../standings_global.md)<br />
Regional Rank: [1]( ../standings_asia.md)<br />
Final Rank Value:  1581.6<br />
<br />
Final Rank Value (1581.6) = Starting Rank Value (1614.8) + Head To Head Adjustments (-33.3)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.582[<sup>1</sup>](#table2)
- Bounty Collected: 0.530[<sup>2</sup>](#table1)
- Opponent Network: 0.275[<sup>2</sup>](#table1)
- LAN Wins: 1.000[<sup>2</sup>](#table1)

The average of these factors is 0.597<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1614.8
- 400 + ( ( 0.597 - 0.000 ) / ( 0.786 - 0.000 ) ) * 1600 = 1614.8


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent           | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           71 |       92 | 2024-05-29 | Aurora Gaming      | W   | 1.000      | 0.500        | 0.492 (0.246)    | 0.616 (0.308)    | 1 (1.000) |     7.26 | 910, bLitz, mzinho, Senzu, Techno4K   |
|           70 |      137 | 2024-05-28 | Gaimin Gladiators  | W   | 1.000      | 0.500        | 0.092 (0.046)    | 0.711 (0.355)    | 1 (1.000) |     2.42 | 910, bLitz, mzinho, Senzu, Techno4K   |
|           69 |      931 | 2024-05-18 | ATOX Esports       | W   | 1.000      | -            | -                | -                | 1 (1.000) |     2.42 | 910, bLitz, mzinho, Senzu, Techno4K   |
|           68 |     1017 | 2024-05-16 | Chinggis Warriors  | W   | 1.000      | -            | -                | -                | 1 (1.000) |     0.44 | 910, bLitz, mzinho, Senzu, Techno4K   |
|           67 |     1108 | 2024-05-15 | IHC Esports        | W   | 1.000      | -            | -                | -                | 1 (1.000) |     0.36 | 910, bLitz, mzinho, Senzu, Techno4K   |
|           66 |     1109 | 2024-05-15 | The Huns Esports   | W   | 1.000      | -            | -                | -                | 1 (1.000) |     0.53 | 910, bLitz, mzinho, Senzu, Techno4K   |
|           65 |     1179 | 2024-05-15 | Gods Reign         | W   | 1.000      | 0.417        | 0.086 (0.036)    | 0.461 (0.192)    | -         |     0.50 | 910, bLitz, mzinho, Senzu, Techno4K   |
|           64 |     1191 | 2024-05-15 | Gods Reign         | W   | 1.000      | 0.417        | 0.086 (0.036)    | 0.461 (0.192)    | -         |     0.50 | 910, bLitz, mzinho, Senzu, Techno4K   |
|           63 |     1284 | 2024-05-14 | MIRAI Gaming       | W   | 1.000      | -            | -                | -                | -         |     0.25 | 910, bLitz, mzinho, Senzu, Techno4K   |
|           62 |     1290 | 2024-05-14 | MIRAI Gaming       | W   | 1.000      | -            | -                | -                | -         |     0.25 | 910, bLitz, mzinho, Senzu, Techno4K   |
|           61 |     1614 | 2024-05-08 | Virtus.pro         | L   | 1.000      | -            | -                | -                | -         |   -11.81 | 910, bLitz, mzinho, Senzu, Techno4K   |
|           60 |     2126 | 2024-04-28 | Team Vitality      | L   | 0.989      | -            | -                | -                | -         |    -6.19 | 910, bLitz, mzinho, Senzu, Techno4K   |
|           59 |     2327 | 2024-04-25 | G2 Esports         | W   | 0.969      | 0.889        | 0.468 (0.403)    | 0.392 (0.337)    | 1 (0.969) |    23.52 | 910, bLitz, mzinho, Senzu, Techno4K   |
|           58 |     2388 | 2024-04-24 | Team Falcons       | W   | 0.962      | 0.889        | 0.355 (0.303)    | -                | 1 (0.962) |    10.32 | 910, bLitz, mzinho, Senzu, Techno4K   |
|           57 |     2716 | 2024-04-19 | Rare Atom          | W   | 0.929      | -            | -                | -                | -         |     0.62 | 910, bLitz, mzinho, Senzu, Techno4K   |
|           56 |     2775 | 2024-04-18 | TYLOO              | W   | 0.923      | -            | -                | -                | -         |     0.97 | 910, bLitz, mzinho, Senzu, Techno4K   |
|           55 |     2790 | 2024-04-18 | Rare Atom          | W   | 0.922      | -            | -                | -                | -         |     0.50 | 910, bLitz, mzinho, Senzu, Techno4K   |
|           54 |     2852 | 2024-04-17 | DEWA United        | W   | 0.916      | -            | -                | -                | -         |     0.26 | 910, bLitz, mzinho, Senzu, Techno4K   |
|           53 |     2856 | 2024-04-17 | DEWA United        | W   | 0.916      | -            | -                | -                | -         |     0.26 | 910, bLitz, mzinho, Senzu, Techno4K   |
|           52 |     2988 | 2024-04-14 | ATOX Esports       | W   | 0.896      | -            | -                | -                | 1 (0.896) |     2.66 | 910, bLitz, mzinho, Senzu, Techno4K   |
|           51 |     3086 | 2024-04-12 | ZEUSGG             | W   | 0.882      | -            | -                | -                | -         |     0.10 | 910, bLitz, mzinho, Senzu, Techno4K   |
|           50 |     3088 | 2024-04-12 | ZEUSGG             | W   | 0.882      | -            | -                | -                | -         |     0.10 | 910, bLitz, mzinho, Senzu, Techno4K   |
|           49 |     3188 | 2024-04-10 | ATOX Esports       | W   | 0.869      | 0.417        | -                | 0.601 (0.218)    | -         |     2.61 | 910, bLitz, mzinho, Senzu, Techno4K   |
|           48 |     3193 | 2024-04-10 | ATOX Esports       | W   | 0.869      | 0.417        | -                | 0.601 (0.218)    | -         |     2.68 | 910, bLitz, mzinho, Senzu, Techno4K   |
|           47 |     3256 | 2024-04-09 | LYG Gaming         | W   | 0.862      | -            | -                | -                | -         |     0.39 | 910, bLitz, mzinho, Senzu, Techno4K   |
|           46 |     3259 | 2024-04-09 | LYG Gaming         | W   | 0.862      | -            | -                | -                | -         |     0.39 | 910, bLitz, mzinho, Senzu, Techno4K   |
|           45 |     3309 | 2024-04-08 | ATOX Esports       | W   | 0.855      | -            | -                | -                | 1 (0.855) |     3.04 | 910, bLitz, mzinho, Senzu, Techno4K   |
|           44 |     3429 | 2024-04-05 | Born to Win        | W   | 0.840      | -            | -                | -                | -         |     0.06 | 910, kaz, mzinho, Senzu, Techno4K     |
|           43 |     3518 | 2024-04-04 | Nitromethane       | W   | 0.828      | -            | -                | -                | -         |     0.04 | 910, kaz, mzinho, Senzu, Techno4K     |
|           42 |     3564 | 2024-04-03 | Lynn Vision Gaming | W   | 0.822      | -            | -                | -                | -         |     2.21 | 910, bLitz, mzinho, Senzu, Techno4K   |
|           41 |     3579 | 2024-04-03 | LYG Gaming         | W   | 0.821      | -            | -                | -                | -         |     0.38 | 910, bLitz, mzinho, Senzu, Techno4K   |
|           40 |     3609 | 2024-04-02 | ATOX Esports       | W   | 0.816      | -            | -                | -                | -         |     2.91 | 910, bLitz, mzinho, Senzu, Techno4K   |
|           39 |     3615 | 2024-04-02 | LYG Gaming         | L   | 0.815      | -            | -                | -                | -         |   -25.33 | 910, bLitz, mzinho, Senzu, Techno4K   |
|           38 |     4038 | 2024-03-22 | paiN Gaming        | L   | 0.743      | -            | -                | -                | -         |   -11.65 | 910, bLitz, mzinho, Senzu, Techno4K   |
|           37 |     4089 | 2024-03-21 | Team Vitality      | L   | 0.737      | -            | -                | -                | -         |    -4.64 | 910, bLitz, mzinho, Senzu, Techno4K   |
|           36 |     4101 | 2024-03-21 | Natus Vincere      | L   | 0.736      | -            | -                | -                | -         |    -4.00 | 910, bLitz, mzinho, Senzu, Techno4K   |
|           35 |     4140 | 2024-03-20 | Legacy             | W   | 0.729      | 1.000        | 0.027 (0.019)    | 0.307 (0.224)    | -         |     1.46 | 910, bLitz, mzinho, Senzu, Techno4K   |
|           34 |     4180 | 2024-03-19 | Lynn Vision Gaming | W   | 0.723      | 1.000        | 0.063 (0.045)    | 0.414 (0.299)    | -         |     1.71 | 910, bLitz, mzinho, Senzu, Techno4K   |
|           33 |     4217 | 2024-03-18 | AMKAL ESPORTS      | W   | 0.716      | 1.000        | 0.146 (0.105)    | 0.565 (0.405)    | -         |     1.90 | 910, bLitz, mzinho, Senzu, Techno4K   |
|           32 |     4254 | 2024-03-17 | Gaimin Gladiators  | L   | 0.711      | -            | -                | -                | -         |   -19.49 | 910, bLitz, mzinho, Senzu, Techno4K   |
|           31 |     4287 | 2024-03-17 | Eternal Fire       | L   | 0.709      | -            | -                | -                | -         |    -4.57 | 910, bLitz, mzinho, Senzu, Techno4K   |
|           30 |     4502 | 2024-03-13 | Born In Far East   | W   | 0.683      | -            | -                | -                | -         |     0.10 | 910, bLitz, mzinho, Senzu, Techno4K   |
|           29 |     4504 | 2024-03-13 | Born In Far East   | W   | 0.683      | -            | -                | -                | -         |     0.10 | 910, bLitz, mzinho, Senzu, Techno4K   |
|           28 |     5344 | 2024-02-27 | Lynn Vision Gaming | W   | 0.586      | -            | -                | -                | -         |     1.06 | 910, bLitz, mzinho, Senzu, Techno4K   |
|           27 |     5428 | 2024-02-25 | FlyQuest           | W   | 0.574      | -            | -                | -                | -         |     5.38 | 910, bLitz, mzinho, Senzu, Techno4K   |
|           26 |     5434 | 2024-02-25 | Myth Avenue Gaming | W   | 0.573      | -            | -                | -                | -         |     0.02 | 910, bLitz, mzinho, Senzu, Techno4K   |
|           25 |     6620 | 2024-02-02 | ENCE               | L   | 0.417      | -            | -                | -                | -         |    -9.52 | 910, bLitz, mzinho, Senzu, Techno4K   |
|           24 |     6685 | 2024-02-01 | Team Spirit        | L   | 0.409      | -            | -                | -                | -         |    -2.11 | 910, bLitz, mzinho, Senzu, Techno4K   |
|           23 |     6714 | 2024-01-31 | FURIA Esports      | W   | 0.404      | 1.000        | 0.138 (0.056)    | -                | -         |     3.83 | 910, bLitz, mzinho, Senzu, Techno4K   |
|           22 |     6886 | 2024-01-28 | Lynn Vision Gaming | W   | 0.382      | -            | -                | -                | -         |     0.77 | 910, bLitz, mzinho, Senzu, Techno4K   |
|           21 |     6890 | 2024-01-27 | Team NKT           | W   | 0.381      | -            | -                | -                | -         |     0.10 | 910, bLitz, mzinho, Senzu, Techno4K   |
|           20 |     6984 | 2024-01-27 | TYLOO              | L   | 0.376      | -            | -                | -                | -         |   -11.69 | 910, bLitz, mzinho, Senzu, Techno4K   |
|           19 |     7052 | 2024-01-26 | TYLOO              | W   | 0.370      | -            | -                | -                | -         |     0.14 | 910, bLitz, mzinho, Senzu, Techno4K   |
|           18 |     7060 | 2024-01-26 | The Huns Esports   | W   | 0.368      | -            | -                | -                | -         |     0.21 | 910, bLitz, mzinho, Senzu, Techno4K   |
|           17 |     7065 | 2024-01-25 | TYLOO              | W   | 0.368      | -            | -                | -                | -         |     0.14 | 910, bLitz, mzinho, Senzu, Techno4K   |
|           16 |     7066 | 2024-01-25 | ACME               | W   | 0.367      | -            | -                | -                | -         |     0.05 | 910, bLitz, mzinho, Senzu, Techno4K   |
|           15 |     7292 | 2024-01-20 | ATOX Esports       | W   | 0.334      | -            | -                | -                | -         |     1.06 | 910, bLitz, mzinho, Senzu, Techno4K   |
|           14 |     7418 | 2024-01-19 | MungYu Esports     | W   | 0.322      | -            | -                | -                | -         |     0.02 | 910, bLitz, mzinho, Senzu, Techno4K   |
|           13 |     7428 | 2024-01-19 | Team NKT           | W   | 0.322      | -            | -                | -                | -         |     0.07 | 910, bLitz, mzinho, Senzu, Techno4K   |
|           12 |     8197 | 2024-01-07 | The QUBE Esports   | L   | 0.242      | -            | -                | -                | -         |    -7.57 | 910, bLitz, darkis, hasteka, Techno4K |
|           11 |     8201 | 2024-01-06 | Team mzinho        | W   | 0.241      | -            | -                | -                | -         |     0.02 | 910, bLitz, darkis, hasteka, Techno4K |
|           10 |     8473 | 2023-12-17 | Virtus.pro         | L   | 0.103      | -            | -                | -                | -         |    -1.26 | 910, bLitz, mzinho, Senzu, Techno4K   |
|            9 |     8599 | 2023-12-16 | Complexity Gaming  | W   | 0.097      | -            | -                | -                | -         |     1.33 | 910, bLitz, mzinho, Senzu, Techno4K   |
|            8 |     8717 | 2023-12-15 | Apeks              | L   | 0.092      | -            | -                | -                | -         |    -2.60 | 910, bLitz, mzinho, Senzu, Techno4K   |
|            7 |     8726 | 2023-12-15 | Complexity Gaming  | W   | 0.091      | -            | -                | -                | -         |     1.24 | 910, bLitz, mzinho, Senzu, Techno4K   |
|            6 |     8985 | 2023-12-10 | TYLOO              | W   | 0.056      | -            | -                | -                | -         |     0.02 | 910, bLitz, mzinho, Senzu, Techno4K   |
|            5 |     9041 | 2023-12-09 | Lynn Vision Gaming | W   | 0.049      | -            | -                | -                | -         |     0.09 | 910, bLitz, mzinho, Senzu, Techno4K   |
|            4 |     9118 | 2023-12-08 | NewHappy           | W   | 0.043      | -            | -                | -                | -         |     0.01 | 910, bLitz, mzinho, Senzu, Techno4K   |
|            3 |     9181 | 2023-12-07 | GR Gaming          | W   | 0.036      | -            | -                | -                | -         |     0.01 | 910, bLitz, mzinho, Senzu, Techno4K   |
|            2 |     9237 | 2023-12-06 | LYG Gaming         | W   | 0.029      | -            | -                | -                | -         |     0.01 | 910, bLitz, mzinho, Senzu, Techno4K   |
|            1 |     9315 | 2023-12-05 | NewHappy           | L   | 0.022      | -            | -                | -                | -         |    -0.70 | 910, bLitz, mzinho, Senzu, Techno4K   |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($57,703.91)
- Divide that value by the 5th highest value among all rosters ($300,806.11)
- The final value (0.19) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-05-22 |      1.000 | $500.00        | $500.00         |
| 2024-05-12 |      1.000 | $23,500.00     | $23,500.00      |
| 2024-04-14 |      0.896 | $4,347.83      | $3,894.12       |
| 2024-03-31 |      0.804 | $20,000.00     | $16,077.78      |
| 2024-02-11 |      0.477 | $4,500.00      | $2,146.25       |
| 2024-01-28 |      0.382 | $25,000.00     | $9,555.56       |
| 2024-01-07 |      0.242 | $584.86        | $141.54         |
| 2023-12-17 |      0.105 | $10,000.00     | $1,051.16       |
| 2023-12-10 |      0.056 | $15,000.00     | $837.50         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
