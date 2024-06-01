### Roster Details<br />
Team Name: LYG Gaming<br />
Roster: deffen, Haski4, Sange, Soundwave, ZinGY<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [215](../standings_global.md)<br />
Regional Rank: [145]( ../standings_europe.md)<br />
Final Rank Value:  713.0<br />
<br />
Final Rank Value (713.0) = Starting Rank Value (730.7) + Head To Head Adjustments (-17.7)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.253[<sup>1</sup>](#table2)
- Bounty Collected: 0.322[<sup>2</sup>](#table1)
- Opponent Network: 0.075[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.162<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 730.7
- 400 + ( ( 0.162 - 0.000 ) / ( 0.786 - 0.000 ) ) * 1600 = 730.7


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
|           45 |      955 | 2024-05-17 | Team PeeP          | L   | 1.000      | -            | -                | -                | -         |   -22.12 | deffen, Haski4, Sange, Soundwave, ZinGY        |
|           44 |      969 | 2024-05-17 | BAKS Esports       | L   | 1.000      | -            | -                | -                | -         |   -22.42 | deffen, Haski4, Sange, Soundwave, ZinGY        |
|           43 |      984 | 2024-05-17 | AntiAnimeClube     | W   | 1.000      | -            | -                | -                | 0 (0.000) |     3.75 | deffen, Haski4, Sange, Soundwave, ZinGY        |
|           42 |      999 | 2024-05-17 | TYLOO              | L   | 1.000      | -            | -                | -                | -         |    -6.51 | Haski4, retaler, Sange, Soundwave, ZinGY       |
|           41 |     1008 | 2024-05-17 | TYLOO              | L   | 1.000      | -            | -                | -                | -         |    -6.91 | Haski4, retaler, Sange, Soundwave, ZinGY       |
|           40 |     2610 | 2024-04-20 | NewHappy           | W   | 0.936      | 0.417        | 0.020 (0.008)    | 0.231 (0.090)    | 0 (0.000) |    13.18 | deffen, Haski4, Sange, Soundwave, ZinGY        |
|           39 |     2625 | 2024-04-20 | NewHappy           | W   | 0.936      | 0.417        | 0.020 (0.008)    | 0.231 (0.090)    | 0 (0.000) |    14.31 | deffen, Haski4, Sange, Soundwave, ZinGY        |
|           38 |     2867 | 2024-04-17 | Team NKT           | L   | 0.915      | -            | -                | -                | -         |   -22.24 | AceX, Haski4, Sange, Soundwave, ZinGY          |
|           37 |     2915 | 2024-04-16 | 2ez Gaming         | W   | 0.909      | -            | -                | -                | 0 (0.000) |     8.09 | AceX, Haski4, Sange, Soundwave, ZinGY          |
|           36 |     3189 | 2024-04-10 | Clutch Gaming      | L   | 0.869      | -            | -                | -                | -         |   -14.21 | deffen, Haski4, Sange, Soundwave, ZinGY        |
|           35 |     3194 | 2024-04-10 | Clutch Gaming      | L   | 0.869      | -            | -                | -                | -         |   -15.34 | deffen, Haski4, Sange, Soundwave, ZinGY        |
|           34 |     3256 | 2024-04-09 | The MongolZ        | L   | 0.862      | -            | -                | -                | -         |    -0.39 | deffen, Haski4, Sange, Soundwave, ZinGY        |
|           33 |     3259 | 2024-04-09 | The MongolZ        | L   | 0.862      | -            | -                | -                | -         |    -0.39 | deffen, Haski4, Sange, Soundwave, ZinGY        |
|           32 |     3579 | 2024-04-03 | The MongolZ        | L   | 0.821      | -            | -                | -                | -         |    -0.38 | AceX, Haski4, Sange, Soundwave, ZinGY          |
|           31 |     3610 | 2024-04-02 | Lynn Vision Gaming | L   | 0.816      | -            | -                | -                | -         |    -3.60 | AceX, Haski4, Sange, Soundwave, ZinGY          |
|           30 |     3615 | 2024-04-02 | The MongolZ        | W   | 0.815      | 0.143        | 0.192 (0.022)    | 0.619 (0.072)    | 0 (0.000) |    25.33 | AceX, Haski4, Sange, Soundwave, ZinGY          |
|           29 |     3706 | 2024-03-29 | The QUBE Esports   | W   | 0.790      | 0.417        | 0.001 (0.000)    | 0.120 (0.040)    | 0 (0.000) |    11.56 | deffen, Haski4, Sange, Soundwave, ZinGY        |
|           28 |     3708 | 2024-03-29 | The QUBE Esports   | W   | 0.789      | 0.417        | 0.001 (0.000)    | 0.120 (0.040)    | 0 (0.000) |    12.39 | deffen, Haski4, Sange, Soundwave, ZinGY        |
|           27 |     3818 | 2024-03-27 | ZEUSGG             | L   | 0.776      | -            | -                | -                | -         |   -19.11 | deffen, Haski4, Sange, Soundwave, ZinGY        |
|           26 |     3821 | 2024-03-27 | ZEUSGG             | W   | 0.776      | -            | -                | -                | 0 (0.000) |     5.16 | deffen, Haski4, Sange, Soundwave, ZinGY        |
|           25 |     4435 | 2024-03-14 | ATOX Esports       | L   | 0.690      | -            | -                | -                | -         |    -1.87 | deffen, Haski4, Sange, Soundwave, ZinGY        |
|           24 |     4440 | 2024-03-14 | ATOX Esports       | W   | 0.689      | 0.417        | 0.047 (0.014)    | 0.601 (0.173)    | 0 (0.000) |    20.08 | deffen, Haski4, Sange, Soundwave, ZinGY        |
|           23 |     4511 | 2024-03-13 | TYLOO              | W   | 0.682      | 0.143        | 0.035 (0.003)    | 0.433 (0.042)    | 0 (0.000) |    16.26 | AceX, Haski4, Sange, Soundwave, ZinGY          |
|           22 |     4515 | 2024-03-13 | The Huns Esports   | W   | 0.682      | 0.143        | -                | 0.292 (0.028)    | -         |    15.61 | AceX, Haski4, Sange, Soundwave, ZinGY          |
|           21 |     4568 | 2024-03-12 | Troublemakers      | W   | 0.676      | -            | -                | -                | -         |     3.32 | AceX, Haski4, Sange, Soundwave, ZinGY          |
|           20 |     4895 | 2024-03-06 | Gods Reign         | W   | 0.636      | 0.417        | 0.086 (0.023)    | 0.461 (0.122)    | -         |    15.31 | deffen, Haski4, Sange, Soundwave, ZinGY        |
|           19 |     4903 | 2024-03-06 | Gods Reign         | L   | 0.636      | -            | -                | -                | -         |    -4.67 | deffen, Haski4, Sange, Soundwave, ZinGY        |
|           18 |     4973 | 2024-03-05 | GR Gaming          | L   | 0.629      | -            | -                | -                | -         |    -6.33 | deffen, Haski4, Sange, Soundwave, ZinGY        |
|           17 |     4976 | 2024-03-05 | GR Gaming          | L   | 0.629      | -            | -                | -                | -         |    -6.65 | deffen, Haski4, Sange, Soundwave, ZinGY        |
|           16 |     5723 | 2024-02-21 | MIRAI Gaming       | L   | 0.543      | -            | -                | -                | -         |    -9.01 | deffen, Haski4, Sange, Soundwave, ZinGY        |
|           15 |     5729 | 2024-02-21 | MIRAI Gaming       | L   | 0.543      | -            | -                | -                | -         |    -9.45 | deffen, Haski4, Sange, Soundwave, ZinGY        |
|           14 |     5844 | 2024-02-19 | Born In Far East   | W   | 0.529      | 0.417        | 0.001 (0.000)    | -                | -         |     7.64 | deffen, Haski4, Sange, Soundwave, ZinGY        |
|           13 |     5847 | 2024-02-19 | Born In Far East   | W   | 0.529      | 0.417        | 0.001 (0.000)    | -                | -         |     8.00 | deffen, Haski4, Sange, Soundwave, ZinGY        |
|           12 |     5964 | 2024-02-16 | Arcade Esports     | L   | 0.513      | -            | -                | -                | -         |    -8.66 | AceX, Haski4, Sange, Soundwave, ZinGY          |
|           11 |     6123 | 2024-02-14 | Myth Avenue Gaming | L   | 0.496      | -            | -                | -                | -         |    -7.80 | AceX, Haski4, Sange, Soundwave, ZinGY          |
|           10 |     6161 | 2024-02-13 | -72C               | L   | 0.490      | -            | -                | -                | -         |    -7.41 | deffen, Haski4, Sange, Soundwave, ZinGY        |
|            9 |     6168 | 2024-02-13 | -72C               | W   | 0.489      | 0.417        | -                | 0.252 (0.051)    | -         |     8.20 | deffen, Haski4, Sange, Soundwave, ZinGY        |
|            8 |     7131 | 2024-01-24 | Wings Up Gaming    | L   | 0.356      | -            | -                | -                | -         |    -6.05 | AceX, Haski4, Sange, Soundwave, ZinGY          |
|            7 |     7136 | 2024-01-24 | Gods Reign         | W   | 0.356      | -            | -                | -                | -         |     5.27 | clouda, Crazy_Gamer, CycloneF, f1redup, Ph1NNN |
|            6 |     7249 | 2024-01-22 | Eruption           | L   | 0.343      | -            | -                | -                | -         |    -7.21 | fury5k, MagnumZ, NEUZ, ROUX, tamir             |
|            5 |     7722 | 2024-01-15 | The Huns Esports   | L   | 0.295      | -            | -                | -                | -         |    -2.74 | AceX, Haski4, Sange, Soundwave, ZinGY          |
|            4 |     9237 | 2023-12-06 | The MongolZ        | L   | 0.029      | -            | -                | -                | -         |    -0.01 | Haski4, Sange, Soundwave, zeins, ZinGY         |
|            3 |     9313 | 2023-12-05 | Clutch Gaming      | W   | 0.022      | -            | -                | -                | -         |     0.31 | Haski4, Sange, Soundwave, zeins, ZinGY         |
|            2 |     9515 | 2023-12-02 | GR Gaming          | L   | 0.002      | -            | -                | -                | -         |    -0.02 | AceX, Haski4, Sange, zeins, ZinGY              |
|            1 |     9519 | 2023-12-02 | EXO SIA            | W   | 0.001      | -            | -                | -                | -         |     0.01 | Chinits, craigy, Jaro, mikozu, P4P1CH1NO       |

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
