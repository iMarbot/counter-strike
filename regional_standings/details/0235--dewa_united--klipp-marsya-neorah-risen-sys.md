### Roster Details<br />
Team Name: DEWA United<br />
Roster: klipp, marsyA, neorah, RiseN, Sys<br />
Region: [Asia]( ../standings_asia.md)<br />
<br />
Global Rank: [235](../standings_global.md)<br />
Regional Rank: [29]( ../standings_asia.md)<br />
Final Rank Value:  697.5<br />
<br />
Final Rank Value (697.5) = Starting Rank Value (711.5) + Head To Head Adjustments (-14.0)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.270[<sup>1</sup>](#table2)
- Bounty Collected: 0.302[<sup>2</sup>](#table1)
- Opponent Network: 0.042[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.153<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 711.5
- 400 + ( ( 0.153 - 0.000 ) / ( 0.787 - 0.000 ) ) * 1600 = 711.5


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent            | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                     |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           34 |      622 | 2024-05-21 | Lynn Vision Gaming  | L   | 1.000      | -            | -                | -                | -         |    -3.75 | klipp, marsyA, neorah, RiseN, Sys          |
|           33 |      629 | 2024-05-21 | Lynn Vision Gaming  | L   | 1.000      | -            | -                | -                | -         |    -3.89 | klipp, marsyA, neorah, RiseN, Sys          |
|           32 |      718 | 2024-05-20 | Gods Reign          | L   | 1.000      | -            | -                | -                | -         |   -10.90 | klipp, marsyA, neorah, RiseN, Sys          |
|           31 |      725 | 2024-05-20 | Gods Reign          | W   | 1.000      | 0.417        | 0.086 (0.036)    | 0.461 (0.192)    | 0 (0.000) |    21.02 | klipp, marsyA, neorah, RiseN, Sys          |
|           30 |     1191 | 2024-05-15 | TYLOO               | L   | 1.000      | -            | -                | -                | -         |    -6.03 | klipp, marsyA, neorah, RiseN, Sys          |
|           29 |     1200 | 2024-05-15 | TYLOO               | L   | 1.000      | -            | -                | -                | -         |    -6.38 | klipp, marsyA, neorah, RiseN, Sys          |
|           28 |     1293 | 2024-05-14 | Born In Far East    | W   | 1.000      | 0.417        | 0.001 (0.001)    | 0.139 (0.058)    | 0 (0.000) |    15.49 | klipp, marsyA, neorah, RiseN, Sys          |
|           27 |     1299 | 2024-05-14 | Born In Far East    | L   | 1.000      | -            | -                | -                | -         |   -16.04 | klipp, marsyA, neorah, RiseN, Sys          |
|           26 |     2909 | 2024-04-17 | The MongolZ         | L   | 0.916      | -            | -                | -                | -         |    -0.26 | klipp, marsyA, neorah, RiseN, Sys          |
|           25 |     2913 | 2024-04-17 | The MongolZ         | L   | 0.916      | -            | -                | -                | -         |    -0.26 | klipp, marsyA, neorah, RiseN, Sys          |
|           24 |     2922 | 2024-04-17 | Sheer Conquer       | L   | 0.915      | -            | -                | -                | -         |   -10.91 | klipp, marsyA, neorah, RiseN, Whis         |
|           23 |     2977 | 2024-04-16 | Gods Reign          | W   | 0.909      | 0.143        | 0.086 (0.011)    | 0.461 (0.060)    | 0 (0.000) |    20.91 | klipp, marsyA, neorah, RiseN, Whis         |
|           22 |     3535 | 2024-04-05 | ATOX Esports        | L   | 0.836      | -            | -                | -                | -         |    -1.50 | klipp, marsyA, neorah, RiseN, Sys          |
|           21 |     3536 | 2024-04-05 | ATOX Esports        | L   | 0.836      | -            | -                | -                | -         |    -1.52 | klipp, marsyA, neorah, RiseN, Sys          |
|           20 |     3597 | 2024-04-04 | Clutch Gaming       | W   | 0.829      | 0.417        | 0.000 (0.000)    | 0.167 (0.058)    | 0 (0.000) |    14.59 | klipp, marsyA, neorah, RiseN, Sys          |
|           19 |     3601 | 2024-04-04 | Clutch Gaming       | L   | 0.829      | -            | -                | -                | -         |   -11.58 | klipp, marsyA, neorah, RiseN, Sys          |
|           18 |     4893 | 2024-03-08 | Myth Avenue Gaming  | L   | 0.649      | -            | -                | -                | -         |    -9.29 | klipp, marsyA, RiseN, toastcito, Whis      |
|           17 |     5039 | 2024-03-06 | Jadeite             | W   | 0.636      | -            | -                | -                | 0 (0.000) |     2.75 | klipp, marsyA, RiseN, toastcito, Whis      |
|           16 |     5056 | 2024-03-05 | NewHappy            | L   | 0.634      | -            | -                | -                | -         |    -7.73 | klipp, marsyA, RiseN, toastcito, Whis      |
|           15 |     6314 | 2024-02-13 | Myth Avenue Gaming  | L   | 0.494      | -            | -                | -                | -         |    -7.96 | Hatred, klipp, neorah, RiseN, Whis         |
|           14 |     6411 | 2024-02-12 | Grayfox Esports     | W   | 0.481      | 0.303        | 0.004 (0.001)    | 0.204 (0.030)    | 0 (0.000) |     6.75 | Hatred, klipp, neorah, RiseN, Whis         |
|           13 |     6440 | 2024-02-10 | Myth Avenue Gaming  | L   | 0.474      | -            | -                | -                | -         |    -8.07 | Hatred, klipp, neorah, RiseN, Whis         |
|           12 |     6647 | 2024-02-04 | SEAW                | W   | 0.434      | 0.303        | -                | 0.039 (0.005)    | 0 (0.000) |     2.91 | Hatred, klipp, neorah, RiseN, Whis         |
|           11 |     6682 | 2024-02-04 | Jadeite             | W   | 0.428      | -            | -                | -                | 0 (0.000) |     1.87 | Hatred, klipp, neorah, RiseN, Whis         |
|           10 |     7207 | 2024-01-27 | Garuda Wisnu Voyage | W   | 0.376      | 0.143        | 0.006 (0.000)    | -                | 0 (0.000) |     3.39 | KillerKitten, klipp, MarsyA, neorah, RiseN |
|            9 |     7210 | 2024-01-27 | Persuwir            | W   | 0.376      | 0.143        | 0.000 (0.000)    | -                | 0 (0.000) |     3.91 | KillerKitten, klipp, MarsyA, neorah, RiseN |
|            8 |     7536 | 2024-01-20 | Troublemakers       | L   | 0.334      | -            | -                | -                | -         |    -6.09 | Hatred, klipp, neorah, RiseN, Whis         |
|            7 |     7607 | 2024-01-20 | 2ez Gaming          | W   | 0.329      | 0.143        | 0.001 (0.000)    | 0.095 (0.004)    | -         |     3.88 | Hatred, klipp, neorah, RiseN, Whis         |
|            6 |     7668 | 2024-01-19 | Myth Avenue Gaming  | L   | 0.322      | -            | -                | -                | -         |    -5.54 | Hatred, klipp, neorah, RiseN, Whis         |
|            5 |     7672 | 2024-01-19 | Troublemakers       | W   | 0.322      | 0.143        | 0.000 (0.000)    | 0.087 (0.004)    | -         |     4.29 | Hatred, klipp, neorah, RiseN, Whis         |
|            4 |     7823 | 2024-01-17 | SR Nacague          | W   | 0.310      | 0.143        | -                | 0.044 (0.002)    | -         |     2.24 | Hatred, klipp, neorah, RiseN, Whis         |
|            3 |     7831 | 2024-01-17 | Myth Avenue Gaming  | L   | 0.309      | -            | -                | -                | -         |    -5.33 | Hatred, klipp, neorah, RiseN, Whis         |
|            2 |     7836 | 2024-01-17 | 2ez Gaming          | W   | 0.309      | 0.143        | 0.001 (0.000)    | 0.095 (0.004)    | -         |     3.64 | Hatred, klipp, neorah, RiseN, Whis         |
|            1 |     7852 | 2024-01-17 | Moon Esports        | W   | 0.308      | -            | -                | -                | -         |     1.44 | Hatred, klipp, neorah, RiseN, Whis         |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($589.46)
- Divide that value by the 5th highest value among all rosters ($300,806.11)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-02-13 |      0.494 | $1,000.00      | $494.17         |
| 2024-01-27 |      0.376 | $253.56        | $95.30          |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
