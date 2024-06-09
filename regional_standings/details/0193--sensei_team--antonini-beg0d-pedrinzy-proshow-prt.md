### Roster Details<br />
Team Name: Sensei Team<br />
Roster: antonini, beg0d, pedrinzy, proSHOW, prt<br />
Region: [Americas]( ../standings_americas.md)<br />
<br />
Global Rank: [193](../standings_global.md)<br />
Regional Rank: [39]( ../standings_americas.md)<br />
Final Rank Value:  729.6<br />
<br />
Final Rank Value (729.6) = Starting Rank Value (693.9) + Head To Head Adjustments (35.7)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.284[<sup>1</sup>](#table2)
- Bounty Collected: 0.247[<sup>2</sup>](#table1)
- Opponent Network: 0.047[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.145<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 693.9
- 400 + ( ( 0.145 - 0.000 ) / ( 0.787 - 0.000 ) ) * 1600 = 693.9


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
|           34 |       44 | 2024-05-29 | Romanticos             | W   | 1.000      | -            | -                | -                | 0 (0.000) |     8.83 | antonini, beg0d, pedrinzy, proSHOW, prt    |
|           33 |       79 | 2024-05-29 | Hype Esports           | L   | 1.000      | -            | -                | -                | -         |   -17.65 | antonini, beg0d, pedrinzy, proSHOW, prt    |
|           32 |      119 | 2024-05-28 | eSports Recife         | L   | 1.000      | -            | -                | -                | -         |   -15.82 | antonini, beg0d, pedrinzy, proSHOW, prt    |
|           31 |      339 | 2024-05-24 | paiN Gaming Academy    | W   | 1.000      | 0.143        | 0.005 (0.001)    | 0.346 (0.049)    | 0 (0.000) |    12.84 | antonini, beg0d, pedrinzy, proSHOW, prt    |
|           30 |      389 | 2024-05-23 | eSports Recife         | W   | 1.000      | 0.143        | 0.002 (0.000)    | 0.441 (0.063)    | 0 (0.000) |    14.55 | antonini, beg0d, pedrinzy, proSHOW, prt    |
|           29 |      393 | 2024-05-23 | TIME DE PESO           | W   | 1.000      | -            | -                | -                | 0 (0.000) |     6.01 | antonini, beg0d, pedrinzy, proSHOW, prt    |
|           28 |      457 | 2024-05-22 | 9z Academy             | W   | 1.000      | 0.143        | 0.002 (0.000)    | 0.311 (0.044)    | 0 (0.000) |    12.79 | antonini, beg0d, pedrinzy, proSHOW, prt    |
|           27 |      661 | 2024-05-20 | Hype Esports           | L   | 1.000      | -            | -                | -                | -         |   -17.43 | antonini, beg0d, pedrinzy, proSHOW, prt    |
|           26 |     1056 | 2024-05-16 | OneMore eSports        | W   | 1.000      | -            | -                | -                | 0 (0.000) |    10.40 | antonini, beg0d, pedrinzy, proSHOW, prt    |
|           25 |     1060 | 2024-05-16 | Corinthians Esports    | L   | 1.000      | -            | -                | -                | -         |   -18.38 | antonini, beg0d, pedrinzy, proSHOW, prt    |
|           24 |     1609 | 2024-05-08 | ex-Martians            | W   | 1.000      | -            | -                | -                | 0 (0.000) |     9.78 | antonini, pedrinzy, proSHOW, prt, Straafer |
|           23 |     1993 | 2024-05-01 | Dusty Roots            | L   | 1.000      | -            | -                | -                | -         |   -17.43 | antonini, pedrinzy, ph1, proSHOW, prt      |
|           22 |     2125 | 2024-04-28 | eSports Recife         | L   | 0.991      | -            | -                | -                | -         |   -18.37 | antonini, pedrinzy, ph1, proSHOW, prt      |
|           21 |     2172 | 2024-04-27 | Sharks Youngsters      | W   | 0.986      | 0.143        | 0.003 (0.000)    | 0.407 (0.057)    | 0 (0.000) |    11.02 | antonini, pedrinzy, ph1, proSHOW, prt      |
|           20 |     2173 | 2024-04-27 | Smoke Gaming           | W   | 0.986      | -            | -                | -                | 0 (0.000) |     9.27 | antonini, pedrinzy, ph1, proSHOW, prt      |
|           19 |     2175 | 2024-04-27 | FURIA Esports Female   | W   | 0.985      | 0.143        | 0.018 (0.003)    | 0.159 (0.022)    | 0 (0.000) |    17.33 | antonini, pedrinzy, ph1, proSHOW, prt      |
|           18 |     2180 | 2024-04-27 | Floripa Stars          | W   | 0.985      | -            | -                | -                | -         |    12.32 | antonini, pedrinzy, ph1, proSHOW, prt      |
|           17 |     2190 | 2024-04-27 | Full House Gaming      | L   | 0.984      | -            | -                | -                | -         |   -18.23 | antonini, pedrinzy, ph1, proSHOW, prt      |
|           16 |     2203 | 2024-04-27 | United E-sports        | W   | 0.984      | -            | -                | -                | -         |    11.25 | antonini, pedrinzy, ph1, proSHOW, prt      |
|           15 |     2269 | 2024-04-26 | Hype Esports           | L   | 0.978      | -            | -                | -                | -         |   -20.83 | antonini, pedrinzy, ph1, proSHOW, prt      |
|           14 |     2590 | 2024-04-20 | inSanitY Sports        | L   | 0.939      | -            | -                | -                | -         |   -19.96 | antonini, pedrinzy, ph1, proSHOW, prt      |
|           13 |     2596 | 2024-04-20 | Yawara E-Sports        | W   | 0.938      | 0.143        | -                | 0.319 (0.043)    | -         |    12.62 | antonini, pedrinzy, ph1, proSHOW, prt      |
|           12 |     2997 | 2024-04-15 | 9z Academy             | W   | 0.905      | 0.143        | 0.002 (0.000)    | 0.311 (0.040)    | -         |    10.16 | antonini, pedrinzy, ph1, proSHOW, prt      |
|           11 |     3081 | 2024-04-13 | ODDIK Academy          | W   | 0.891      | -            | -                | -                | -         |     9.38 | antonini, pedrinzy, ph1, proSHOW, prt      |
|           10 |     3134 | 2024-04-12 | Smoke Gaming           | W   | 0.885      | -            | -                | -                | -         |     9.63 | antonini, pedrinzy, ph1, proSHOW, prt      |
|            9 |     3572 | 2024-04-04 | Bounty Hunters Esports | L   | 0.831      | -            | -                | -                | -         |   -18.48 | antonini, pedrinzy, ph1, proSHOW, prt      |
|            8 |     3676 | 2024-04-02 | paiN Gaming Academy    | W   | 0.818      | 0.143        | 0.005 (0.001)    | 0.346 (0.040)    | -         |    12.95 | antonini, pedrinzy, ph1, proSHOW, prt      |
|            7 |     3826 | 2024-03-28 | Intense Game           | L   | 0.784      | -            | -                | -                | -         |   -12.05 | antonini, pedrinzy, ph1, proSHOW, prt      |
|            6 |     4002 | 2024-03-25 | Rocket.GG              | W   | 0.766      | -            | -                | -                | -         |     9.29 | antonini, pedrinzy, ph1, proSHOW, prt      |
|            5 |     4013 | 2024-03-25 | Yawara E-Sports        | L   | 0.764      | -            | -                | -                | -         |   -12.01 | antonini, pedrinzy, ph1, proSHOW, prt      |
|            4 |     4065 | 2024-03-23 | w7m esports Female     | W   | 0.752      | 0.143        | 0.010 (0.001)    | -                | -         |    10.57 | antonini, pedrinzy, ph1, proSHOW, prt      |
|            3 |     4069 | 2024-03-23 | NIGERIA ACADEMY        | W   | 0.752      | -            | -                | -                | -         |     5.38 | antonini, pedrinzy, ph1, proSHOW, prt      |
|            2 |     4162 | 2024-03-21 | Galorys                | W   | 0.738      | 0.143        | 0.022 (0.002)    | 0.600 (0.063)    | -         |    14.24 | antonini, pedrinzy, ph1, proSHOW, prt      |
|            1 |     4176 | 2024-03-21 | MIBR Academy           | W   | 0.738      | 0.143        | 0.005 (0.000)    | 0.448 (0.047)    | -         |    11.75 | antonini, pedrinzy, ph1, proSHOW, prt      |

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
