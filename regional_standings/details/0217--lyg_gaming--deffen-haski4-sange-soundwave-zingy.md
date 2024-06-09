### Roster Details<br />
Team Name: LYG Gaming<br />
Roster: deffen, Haski4, Sange, Soundwave, ZinGY<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [217](../standings_global.md)<br />
Regional Rank: [146]( ../standings_europe.md)<br />
Final Rank Value:  709.5<br />
<br />
Final Rank Value (709.5) = Starting Rank Value (730.9) + Head To Head Adjustments (-21.4)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.253[<sup>1</sup>](#table2)
- Bounty Collected: 0.322[<sup>2</sup>](#table1)
- Opponent Network: 0.076[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.163<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 730.9
- 400 + ( ( 0.163 - 0.000 ) / ( 0.787 - 0.000 ) ) * 1600 = 730.9


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
|           45 |      967 | 2024-05-17 | Team PeeP          | L   | 1.000      | -            | -                | -                | -         |   -21.94 | deffen, Haski4, Sange, Soundwave, ZinGY        |
|           44 |      981 | 2024-05-17 | BAKS Esports       | L   | 1.000      | -            | -                | -                | -         |   -22.40 | deffen, Haski4, Sange, Soundwave, ZinGY        |
|           43 |      996 | 2024-05-17 | AntiAnimeClube     | W   | 1.000      | -            | -                | -                | 0 (0.000) |     3.82 | deffen, Haski4, Sange, Soundwave, ZinGY        |
|           42 |     1011 | 2024-05-17 | TYLOO              | L   | 1.000      | -            | -                | -                | -         |    -6.79 | Haski4, lame, retaler, Sange, ZinGY            |
|           41 |     1020 | 2024-05-17 | TYLOO              | L   | 1.000      | -            | -                | -                | -         |    -7.22 | Haski4, lame, retaler, Sange, ZinGY            |
|           40 |     2664 | 2024-04-20 | NewHappy           | W   | 0.936      | 0.417        | 0.020 (0.008)    | 0.231 (0.090)    | 0 (0.000) |    13.16 | deffen, Haski4, lame, Sange, ZinGY             |
|           39 |     2679 | 2024-04-20 | NewHappy           | W   | 0.936      | 0.417        | 0.020 (0.008)    | 0.231 (0.090)    | 0 (0.000) |    14.29 | deffen, Haski4, lame, Sange, ZinGY             |
|           38 |     2924 | 2024-04-17 | Team NKT           | L   | 0.915      | -            | -                | -                | -         |   -22.10 | AceX, Haski4, Sange, Soundwave, ZinGY          |
|           37 |     2976 | 2024-04-16 | 2ez Gaming         | W   | 0.909      | 0.143        | 0.001 (0.000)    | -                | 0 (0.000) |     8.17 | AceX, Haski4, Sange, Soundwave, ZinGY          |
|           36 |     3264 | 2024-04-10 | Clutch Gaming      | L   | 0.869      | -            | -                | -                | -         |   -14.10 | deffen, Haski4, lame, Sange, ZinGY             |
|           35 |     3269 | 2024-04-10 | Clutch Gaming      | L   | 0.869      | -            | -                | -                | -         |   -15.22 | deffen, Haski4, lame, Sange, ZinGY             |
|           34 |     3335 | 2024-04-09 | The MongolZ        | L   | 0.862      | -            | -                | -                | -         |    -0.38 | deffen, Haski4, lame, Sange, ZinGY             |
|           33 |     3338 | 2024-04-09 | The MongolZ        | L   | 0.862      | -            | -                | -                | -         |    -0.38 | deffen, Haski4, lame, Sange, ZinGY             |
|           32 |     3668 | 2024-04-03 | The MongolZ        | L   | 0.821      | -            | -                | -                | -         |    -0.38 | AceX, Haski4, Sange, Soundwave, ZinGY          |
|           31 |     3700 | 2024-04-02 | Lynn Vision Gaming | L   | 0.816      | -            | -                | -                | -         |    -3.51 | AceX, Haski4, Sange, Soundwave, ZinGY          |
|           30 |     3705 | 2024-04-02 | The MongolZ        | W   | 0.815      | 0.143        | 0.192 (0.022)    | 0.619 (0.072)    | 0 (0.000) |    25.33 | AceX, Haski4, Sange, Soundwave, ZinGY          |
|           29 |     3800 | 2024-03-29 | The QUBE Esports   | W   | 0.790      | 0.417        | -                | 0.138 (0.045)    | 0 (0.000) |     9.14 | deffen, Haski4, lame, Sange, ZinGY             |
|           28 |     3802 | 2024-03-29 | The QUBE Esports   | W   | 0.789      | 0.417        | -                | 0.138 (0.045)    | 0 (0.000) |     9.76 | deffen, Haski4, lame, Sange, ZinGY             |
|           27 |     3911 | 2024-03-27 | ZEUSGG             | L   | 0.776      | -            | -                | -                | -         |   -17.87 | deffen, Haski4, lame, Sange, ZinGY             |
|           26 |     3914 | 2024-03-27 | ZEUSGG             | W   | 0.776      | -            | -                | -                | 0 (0.000) |     6.43 | deffen, Haski4, lame, Sange, ZinGY             |
|           25 |     4549 | 2024-03-14 | ATOX Esports       | L   | 0.690      | -            | -                | -                | -         |    -1.54 | deffen, Haski4, lame, Sange, ZinGY             |
|           24 |     4554 | 2024-03-14 | ATOX Esports       | W   | 0.689      | 0.417        | 0.047 (0.014)    | 0.609 (0.175)    | 0 (0.000) |    20.37 | deffen, Haski4, lame, Sange, ZinGY             |
|           23 |     4627 | 2024-03-13 | TYLOO              | W   | 0.682      | 0.143        | 0.035 (0.003)    | 0.433 (0.042)    | 0 (0.000) |    15.95 | AceX, Haski4, Sange, Soundwave, ZinGY          |
|           22 |     4632 | 2024-03-13 | The Huns Esports   | W   | 0.682      | -            | -                | -                | -         |    15.18 | AceX, Haski4, Sange, Soundwave, ZinGY          |
|           21 |     4689 | 2024-03-12 | Troublemakers      | W   | 0.676      | -            | -                | -                | -         |     3.33 | AceX, Haski4, Sange, Soundwave, ZinGY          |
|           20 |     5029 | 2024-03-06 | Gods Reign         | W   | 0.636      | 0.417        | 0.086 (0.023)    | 0.461 (0.122)    | -         |    14.79 | deffen, Haski4, lame, Sange, ZinGY             |
|           19 |     5037 | 2024-03-06 | Gods Reign         | L   | 0.636      | -            | -                | -                | -         |    -5.20 | deffen, Haski4, lame, Sange, ZinGY             |
|           18 |     5118 | 2024-03-05 | GR Gaming          | L   | 0.629      | -            | -                | -                | -         |    -6.39 | deffen, Haski4, lame, Sange, ZinGY             |
|           17 |     5121 | 2024-03-05 | GR Gaming          | L   | 0.629      | -            | -                | -                | -         |    -6.71 | deffen, Haski4, lame, Sange, ZinGY             |
|           16 |     5887 | 2024-02-21 | MIRAI Gaming       | L   | 0.543      | -            | -                | -                | -         |    -9.13 | deffen, Haski4, lame, Sange, ZinGY             |
|           15 |     5894 | 2024-02-21 | MIRAI Gaming       | L   | 0.543      | -            | -                | -                | -         |    -9.57 | deffen, Haski4, lame, Sange, ZinGY             |
|           14 |     6016 | 2024-02-19 | Born In Far East   | W   | 0.529      | 0.417        | 0.001 (0.000)    | 0.139 (0.031)    | -         |     7.66 | deffen, Haski4, lame, Sange, ZinGY             |
|           13 |     6019 | 2024-02-19 | Born In Far East   | W   | 0.529      | 0.417        | 0.001 (0.000)    | -                | -         |     8.02 | deffen, Haski4, lame, Sange, ZinGY             |
|           12 |     6137 | 2024-02-16 | Arcade Esports     | L   | 0.513      | -            | -                | -                | -         |    -8.44 | AceX, Haski4, Sange, Soundwave, ZinGY          |
|           11 |     6304 | 2024-02-14 | Myth Avenue Gaming | L   | 0.496      | -            | -                | -                | -         |    -7.82 | AceX, Haski4, Sange, Soundwave, ZinGY          |
|           10 |     6346 | 2024-02-13 | -72C               | L   | 0.490      | -            | -                | -                | -         |    -7.41 | deffen, Haski4, lame, Sange, ZinGY             |
|            9 |     6353 | 2024-02-13 | -72C               | W   | 0.489      | 0.417        | -                | 0.252 (0.051)    | -         |     8.20 | deffen, Haski4, lame, Sange, ZinGY             |
|            8 |     7366 | 2024-01-24 | Wings Up Gaming    | L   | 0.356      | -            | -                | -                | -         |    -6.06 | AceX, Haski4, Sange, Soundwave, ZinGY          |
|            7 |     7371 | 2024-01-24 | Gods Reign         | W   | 0.356      | 0.143        | 0.004 (0.000)    | -                | -         |     5.26 | clouda, Crazy_Gamer, CycloneF, f1redup, Ph1NNN |
|            6 |     7492 | 2024-01-22 | Eruption           | L   | 0.343      | -            | -                | -                | -         |    -7.24 | fury5k, MagnumZ, NEUZ, ROUX, tamir             |
|            5 |     7974 | 2024-01-15 | The Huns Esports   | L   | 0.295      | -            | -                | -                | -         |    -2.74 | AceX, Haski4, Sange, Soundwave, ZinGY          |
|            4 |     9518 | 2023-12-06 | The MongolZ        | L   | 0.029      | -            | -                | -                | -         |    -0.01 | Haski4, Sange, Soundwave, zeins, ZinGY         |
|            3 |     9595 | 2023-12-05 | Clutch Gaming      | W   | 0.022      | -            | -                | -                | -         |     0.31 | Haski4, Sange, Soundwave, zeins, ZinGY         |
|            2 |     9797 | 2023-12-02 | GR Gaming          | L   | 0.002      | -            | -                | -                | -         |    -0.02 | AceX, Haski4, Sange, zeins, ZinGY              |
|            1 |     9801 | 2023-12-02 | EXO SIA            | W   | 0.001      | -            | -                | -                | -         |     0.01 | Chinits, craigy, Jaro, mikozu, P4P1CH1NO       |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($332.31)
- Divide that value by the 5th highest value among all rosters ($300,806.11)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-02-17 |      0.519 | $500.00        | $259.72         |
| 2023-12-10 |      0.056 | $1,300.00      | $72.58          |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
