### Roster Details<br />
Team Name: Into The Breach<br />
Roster: Bymas, CRUC1AL, misutaaa, rallen, Thomas<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [98](../standings_global.md)<br />
Regional Rank: [72]( ../standings_europe.md)<br />
Final Rank Value:  865.6<br />
<br />
Final Rank Value (865.6) = Starting Rank Value (805.5) + Head To Head Adjustments (60.1)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.376[<sup>1</sup>](#table2)
- Bounty Collected: 0.362[<sup>2</sup>](#table1)
- Opponent Network: 0.079[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.204<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 805.5
- 400 + ( ( 0.204 - 0.000 ) / ( 0.806 - 0.000 ) ) * 1600 = 805.5


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent           | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                    |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           36 |     3587 | 2024-02-15 | 3DMAX              | L   | 0.665      | -            | -                | -                | -         |    -7.48 | Bymas, CRUC1AL, misutaaa, rallen, Thomas  |
|           35 |     3630 | 2024-02-14 | BetBoom Team       | L   | 0.658      | -            | -                | -                | -         |    -0.76 | Bymas, CRUC1AL, misutaaa, rallen, Thomas  |
|           34 |     3648 | 2024-02-14 | G2 Esports         | L   | 0.657      | -            | -                | -                | -         |    -0.08 | Bymas, CRUC1AL, misutaaa, rallen, Thomas  |
|           33 |     3850 | 2024-02-07 | Preasy Esport      | L   | 0.609      | -            | -                | -                | -         |    -6.99 | Bymas, CRUC1AL, misutaaa, rallen, Thomas  |
|           32 |     3864 | 2024-02-06 | Metizport          | W   | 0.604      | 0.371        | 0.188 (0.042)    | 1.000 (0.224)    | 0 (0.000) |    13.46 | Bymas, CRUC1AL, misutaaa, rallen, Thomas  |
|           31 |     3935 | 2024-02-04 | SINNERS Esports    | W   | 0.590      | 0.371        | 0.038 (0.008)    | 0.534 (0.117)    | 0 (0.000) |    12.60 | Bymas, CRUC1AL, misutaaa, rallen, Thomas  |
|           30 |     4051 | 2024-02-02 | Gaimin Gladiators  | L   | 0.577      | -            | -                | -                | -         |    -0.92 | Bymas, CRUC1AL, misutaaa, rallen, Thomas  |
|           29 |     4094 | 2024-02-01 | BLEED Esports      | W   | 0.570      | 0.371        | 0.284 (0.060)    | 0.644 (0.136)    | 0 (0.000) |    13.99 | Bymas, CRUC1AL, misutaaa, rallen, Thomas  |
|           28 |     4156 | 2024-01-29 | EXO Clan           | L   | 0.553      | -            | -                | -                | -         |    -7.80 | Bymas, CRUC1AL, misutaaa, rallen, Thomas  |
|           27 |     4174 | 2024-01-29 | B8                 | W   | 0.553      | 0.143        | 0.088 (0.007)    | 0.589 (0.046)    | 0 (0.000) |    11.10 | Bymas, CRUC1AL, misutaaa, rallen, Thomas  |
|           26 |     4204 | 2024-01-29 | BIG Academy        | W   | 0.549      | 0.371        | 0.027 (0.005)    | 0.219 (0.045)    | 0 (0.000) |     8.68 | Bymas, CRUC1AL, misutaaa, rallen, Thomas  |
|           25 |     4213 | 2024-01-28 | Sashi Esport       | W   | 0.545      | -            | -                | -                | 0 (0.000) |     2.84 | Bymas, CRUC1AL, misutaaa, rallen, Thomas  |
|           24 |     4217 | 2024-01-28 | BLEED Esports      | W   | 0.545      | 0.143        | 0.284 (0.022)    | 0.644 (0.050)    | 0 (0.000) |    14.38 | Bymas, CRUC1AL, misutaaa, rallen, Thomas  |
|           23 |     4266 | 2024-01-27 | 9INE               | L   | 0.538      | -            | -                | -                | -         |   -12.89 | Bymas, CRUC1AL, misutaaa, rallen, Thomas  |
|           22 |     4365 | 2024-01-25 | BLEED Esports      | L   | 0.523      | -            | -                | -                | -         |    -2.77 | Bymas, CRUC1AL, misutaaa, rallen, Thomas  |
|           21 |     4691 | 2024-01-17 | Guild Eagles       | L   | 0.473      | -            | -                | -                | -         |    -3.22 | Bymas, CRUC1AL, misutaaa, rallen, Thomas  |
|           20 |     4696 | 2024-01-17 | Soda Gaming        | W   | 0.473      | -            | -                | -                | 0 (0.000) |     6.26 | Bymas, CRUC1AL, misutaaa, rallen, Thomas  |
|           19 |     4706 | 2024-01-17 | Entropiq           | W   | 0.473      | 0.143        | -                | 0.436 (0.029)    | 0 (0.000) |     7.27 | Bymas, CRUC1AL, misutaaa, rallen, Thomas  |
|           18 |     4729 | 2024-01-17 | Passion UA         | W   | 0.472      | 0.143        | 0.114 (0.008)    | 0.980 (0.066)    | 0 (0.000) |    10.81 | Bymas, CRUC1AL, misutaaa, rallen, Thomas  |
|           17 |     6015 | 2023-12-04 | Ex-Anonymo Esports | L   | 0.179      | -            | -                | -                | -         |    -3.12 | Bymas, CRUC1AL, misutaaa, rallen, tomiko  |
|           16 |     6029 | 2023-12-03 | 9Pandas            | L   | 0.172      | -            | -                | -                | -         |    -0.77 | Bymas, CRUC1AL, misutaaa, rallen, tomiko  |
|           15 |     6216 | 2023-11-30 | RED Canids         | W   | 0.151      | 0.589        | 0.108 (0.010)    | 0.532 (0.047)    | -         |     3.07 | Bymas, CRUC1AL, misutaaa, rallen, tomiko  |
|           14 |     6224 | 2023-11-30 | The Witchers       | L   | 0.149      | -            | -                | -                | -         |    -2.51 | Bymas, CRUC1AL, misutaaa, rallen, tomiko  |
|           13 |     6407 | 2023-11-26 | Endpoint           | L   | 0.123      | -            | -                | -                | -         |    -1.73 | Bymas, CRUC1AL, misutaaa, rallen, tomiko  |
|           12 |     6443 | 2023-11-25 | BetBoom Team       | L   | 0.117      | -            | -                | -                | -         |    -0.09 | Bymas, CRUC1AL, maxster, misutaaa, rallen |
|           11 |     6670 | 2023-11-19 | B8                 | W   | 0.078      | -            | -                | -                | -         |     0.69 | Bymas, CRUC1AL, maxster, misutaaa, rallen |
|           10 |     6699 | 2023-11-18 | BIG                | L   | 0.072      | -            | -                | -                | -         |    -0.07 | bodyy, Bymas, CRUC1AL, misutaaa, rallen   |
|            9 |     6727 | 2023-11-18 | Ex-Anonymo Esports | W   | 0.071      | -            | -                | -                | -         |     0.99 | bodyy, Bymas, CRUC1AL, misutaaa, rallen   |
|            8 |     6748 | 2023-11-18 | Gaimin Gladiators  | W   | 0.070      | 0.435        | 0.194 (0.006)    | 0.989 (0.030)    | -         |     2.14 | bodyy, Bymas, CRUC1AL, misutaaa, rallen   |
|            7 |     6768 | 2023-11-17 | Team Space         | W   | 0.065      | -            | -                | -                | -         |     0.84 | bodyy, Bymas, CRUC1AL, misutaaa, rallen   |
|            6 |     6789 | 2023-11-17 | ALTERNATE aTTaX    | W   | 0.063      | -            | -                | -                | -         |     1.65 | bodyy, Bymas, CRUC1AL, misutaaa, rallen   |
|            5 |     6822 | 2023-11-16 | 00 Nation          | W   | 0.058      | -            | -                | -                | -         |     0.28 | bodyy, Bymas, CRUC1AL, misutaaa, rallen   |
|            4 |     6837 | 2023-11-16 | Project G          | W   | 0.057      | -            | -                | -                | -         |     0.27 | bodyy, Bymas, CRUC1AL, misutaaa, rallen   |
|            3 |     6869 | 2023-11-15 | INGLORIOUS         | L   | 0.052      | -            | -                | -                | -         |    -0.86 | bodyy, Bymas, CRUC1AL, misutaaa, rallen   |
|            2 |     6940 | 2023-11-14 | MOUZ NXT           | W   | 0.043      | 0.589        | 0.215 (0.005)    | -                | -         |     1.14 | bodyy, Bymas, CRUC1AL, misutaaa, rallen   |
|            1 |     7004 | 2023-11-12 | 3DMAX              | L   | 0.031      | -            | -                | -                | -         |    -0.31 | bodyy, Bymas, CRUC1AL, misutaaa, rallen   |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($3,483.25)
- Divide that value by the 5th highest value among all rosters ($158,437.64)
- The final value (0.02) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-02-09 |      0.623 | $1,000.00      | $622.73         |
| 2023-11-26 |      0.124 | $1,957.16      | $242.92         |
| 2023-11-18 |      0.072 | $15,000.00     | $1,084.72       |
| 2023-11-18 |      0.070 | $22,000.00     | $1,532.87       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
