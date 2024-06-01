### Roster Details<br />
Team Name: Sensei Team<br />
Roster: antonini, beg0d, pedrinzy, proSHOW, prt<br />
Region: [Americas]( ../standings_americas.md)<br />
<br />
Global Rank: [191](../standings_global.md)<br />
Regional Rank: [40]( ../standings_americas.md)<br />
Final Rank Value:  736.2<br />
<br />
Final Rank Value (736.2) = Starting Rank Value (694.8) + Head To Head Adjustments (41.5)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.284[<sup>1</sup>](#table2)
- Bounty Collected: 0.247[<sup>2</sup>](#table1)
- Opponent Network: 0.048[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.145<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 694.8
- 400 + ( ( 0.145 - 0.000 ) / ( 0.786 - 0.000 ) ) * 1600 = 694.8


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent               | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                     |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           34 |       44 | 2024-05-29 | Romanticos             | W   | 1.000      | -            | -                | -                | 0 (0.000) |    11.70 | antonini, beg0d, pedrinzy, proSHOW, prt    |
|           33 |       74 | 2024-05-29 | Hype Esports           | L   | 1.000      | -            | -                | -                | -         |   -17.57 | antonini, beg0d, pedrinzy, proSHOW, prt    |
|           32 |      111 | 2024-05-28 | eSports Recife         | L   | 1.000      | -            | -                | -                | -         |   -15.86 | antonini, beg0d, pedrinzy, proSHOW, prt    |
|           31 |      330 | 2024-05-24 | paiN Gaming Academy    | W   | 1.000      | 0.143        | 0.005 (0.001)    | 0.374 (0.053)    | 0 (0.000) |    12.80 | antonini, beg0d, pedrinzy, proSHOW, prt    |
|           30 |      380 | 2024-05-23 | eSports Recife         | W   | 1.000      | 0.143        | 0.002 (0.000)    | 0.441 (0.063)    | 0 (0.000) |    14.49 | antonini, beg0d, pedrinzy, proSHOW, prt    |
|           29 |      384 | 2024-05-23 | TIME DE PESO           | W   | 1.000      | -            | -                | -                | 0 (0.000) |     5.93 | antonini, pedrinzy, ph1, proSHOW, prt      |
|           28 |      451 | 2024-05-22 | 9z Academy             | W   | 1.000      | 0.143        | 0.002 (0.000)    | 0.311 (0.044)    | 0 (0.000) |    12.73 | antonini, beg0d, pedrinzy, proSHOW, prt    |
|           27 |      650 | 2024-05-20 | Hype Esports           | L   | 1.000      | -            | -                | -                | -         |   -17.53 | antonini, pedrinzy, ph1, proSHOW, prt      |
|           26 |     1045 | 2024-05-16 | OneMore eSports        | W   | 1.000      | -            | -                | -                | 0 (0.000) |    10.26 | antonini, pedrinzy, ph1, proSHOW, prt      |
|           25 |     1049 | 2024-05-16 | Corinthians Esports    | L   | 1.000      | -            | -                | -                | -         |   -15.95 | antonini, pedrinzy, ph1, proSHOW, prt      |
|           24 |     1593 | 2024-05-08 | ex-Martians            | W   | 1.000      | -            | -                | -                | 0 (0.000) |     9.93 | antonini, pedrinzy, proSHOW, prt, Straafer |
|           23 |     1966 | 2024-05-01 | Dusty Roots            | L   | 1.000      | -            | -                | -                | -         |   -17.42 | antonini, pedrinzy, ph1, proSHOW, prt      |
|           22 |     2090 | 2024-04-28 | eSports Recife         | L   | 0.991      | -            | -                | -                | -         |   -18.36 | antonini, pedrinzy, ph1, proSHOW, prt      |
|           21 |     2137 | 2024-04-27 | Sharks Youngsters      | W   | 0.986      | 0.143        | 0.003 (0.000)    | 0.422 (0.059)    | 0 (0.000) |    11.32 | antonini, pedrinzy, ph1, proSHOW, prt      |
|           20 |     2138 | 2024-04-27 | Smoke Gaming           | W   | 0.986      | -            | -                | -                | 0 (0.000) |     9.29 | antonini, pedrinzy, ph1, proSHOW, prt      |
|           19 |     2140 | 2024-04-27 | FURIA Esports Female   | W   | 0.985      | 0.143        | 0.018 (0.003)    | 0.159 (0.022)    | 0 (0.000) |    17.31 | antonini, pedrinzy, ph1, proSHOW, prt      |
|           18 |     2145 | 2024-04-27 | Floripa Stars          | W   | 0.985      | -            | -                | -                | -         |    12.30 | antonini, pedrinzy, ph1, proSHOW, prt      |
|           17 |     2155 | 2024-04-27 | Full House Gaming      | L   | 0.984      | -            | -                | -                | -         |   -18.12 | antonini, pedrinzy, ph1, proSHOW, prt      |
|           16 |     2168 | 2024-04-27 | United E-sports        | W   | 0.984      | -            | -                | -                | -         |    11.21 | antonini, pedrinzy, ph1, proSHOW, prt      |
|           15 |     2233 | 2024-04-26 | Hype Esports           | L   | 0.978      | -            | -                | -                | -         |   -20.78 | antonini, pedrinzy, ph1, proSHOW, prt      |
|           14 |     2537 | 2024-04-20 | inSanitY Sports        | L   | 0.939      | -            | -                | -                | -         |   -20.01 | antonini, pedrinzy, ph1, proSHOW, prt      |
|           13 |     2543 | 2024-04-20 | Yawara E-Sports        | W   | 0.938      | 0.143        | -                | 0.319 (0.043)    | -         |    12.60 | antonini, pedrinzy, ph1, proSHOW, prt      |
|           12 |     2936 | 2024-04-15 | 9z Academy             | W   | 0.905      | 0.143        | 0.002 (0.000)    | 0.311 (0.040)    | -         |    10.16 | antonini, pedrinzy, ph1, proSHOW, prt      |
|           11 |     3015 | 2024-04-13 | ODDIK Academy          | W   | 0.891      | -            | -                | -                | -         |     9.41 | antonini, pedrinzy, ph1, proSHOW, prt      |
|           10 |     3068 | 2024-04-12 | Smoke Gaming           | W   | 0.885      | -            | -                | -                | -         |     9.64 | antonini, pedrinzy, ph1, proSHOW, prt      |
|            9 |     3487 | 2024-04-04 | Bounty Hunters Esports | L   | 0.831      | -            | -                | -                | -         |   -18.49 | antonini, pedrinzy, ph1, proSHOW, prt      |
|            8 |     3587 | 2024-04-02 | paiN Gaming Academy    | W   | 0.818      | 0.143        | 0.005 (0.001)    | 0.374 (0.044)    | -         |    12.99 | antonini, pedrinzy, ph1, proSHOW, prt      |
|            7 |     3732 | 2024-03-28 | Intense Game           | L   | 0.784      | -            | -                | -                | -         |   -12.05 | antonini, pedrinzy, ph1, proSHOW, prt      |
|            6 |     3905 | 2024-03-25 | Rocket.GG              | W   | 0.766      | -            | -                | -                | -         |     9.27 | antonini, pedrinzy, ph1, proSHOW, prt      |
|            5 |     3916 | 2024-03-25 | Yawara E-Sports        | L   | 0.764      | -            | -                | -                | -         |   -12.03 | antonini, pedrinzy, ph1, proSHOW, prt      |
|            4 |     3967 | 2024-03-23 | w7m esports Female     | W   | 0.752      | 0.143        | 0.010 (0.001)    | -                | -         |    10.54 | antonini, pedrinzy, ph1, proSHOW, prt      |
|            3 |     3971 | 2024-03-23 | NIGERIA ACADEMY        | W   | 0.752      | -            | -                | -                | -         |     5.36 | antonini, pedrinzy, ph1, proSHOW, prt      |
|            2 |     4064 | 2024-03-21 | Galorys                | W   | 0.738      | 0.143        | 0.022 (0.002)    | 0.585 (0.062)    | -         |    14.65 | antonini, pedrinzy, ph1, proSHOW, prt      |
|            1 |     4078 | 2024-03-21 | MIBR Academy           | W   | 0.738      | 0.143        | 0.005 (0.000)    | 0.439 (0.046)    | -         |    11.74 | antonini, pedrinzy, ph1, proSHOW, prt      |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($911.76)
- Divide that value by the 5th highest value among all rosters ($300,806.11)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-05-01 |      1.000 | $481.20        | $481.20         |
| 2024-04-30 |      1.000 | $185.60        | $185.60         |
| 2024-03-25 |      0.766 | $319.85        | $244.95         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
