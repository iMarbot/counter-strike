### Roster Details<br />
Team Name: GR Gaming<br />
Roster: mediocrity, qqGOD, Runnin, SALO_MUX, weqt2<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [90](../standings_global.md)<br />
Regional Rank: [63]( ../standings_europe.md)<br />
Final Rank Value:  887.6<br />
<br />
Final Rank Value (887.6) = Starting Rank Value (782.8) + Head To Head Adjustments (104.8)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.315[<sup>1</sup>](#table2)
- Bounty Collected: 0.329[<sup>2</sup>](#table1)
- Opponent Network: 0.110[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.188<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 782.8
- 400 + ( ( 0.188 - 0.000 ) / ( 0.787 - 0.000 ) ) * 1600 = 782.8


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent           | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                       |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           61 |      724 | 2024-05-20 | ZEUSGG             | W   | 1.000      | -            | -                | -                | 0 (0.000) |     4.02 | mediocrity, qqGOD, Runnin, SALO_MUX, weqt2   |
|           60 |      727 | 2024-05-20 | ZEUSGG             | W   | 1.000      | -            | -                | -                | 0 (0.000) |     4.19 | mediocrity, qqGOD, Runnin, SALO_MUX, weqt2   |
|           59 |     1188 | 2024-05-15 | MIRAI Gaming       | W   | 1.000      | 0.417        | -                | 0.200 (0.083)    | 0 (0.000) |     9.45 | mediocrity, qqGOD, Runnin, SALO_MUX, weqt2   |
|           58 |     1199 | 2024-05-15 | MIRAI Gaming       | L   | 1.000      | -            | -                | -                | -         |   -22.55 | mediocrity, qqGOD, Runnin, SALO_MUX, weqt2   |
|           57 |     1342 | 2024-05-13 | Gods Reign         | W   | 1.000      | 0.417        | 0.086 (0.036)    | 0.461 (0.192)    | 0 (0.000) |    14.03 | mediocrity, qqGOD, Runnin, SALO_MUX, weqt2   |
|           56 |     2981 | 2024-04-16 | Sheer Conquer      | L   | 0.909      | -            | -                | -                | -         |   -18.26 | mediocrity, qqGOD, Runnin, SALO_MUX, weqt2   |
|           55 |     3333 | 2024-04-09 | -72C               | W   | 0.863      | 0.417        | -                | 0.252 (0.091)    | 0 (0.000) |     9.45 | mediocrity, qqGOD, Runnin, SALO_MUX, weqt2   |
|           54 |     3340 | 2024-04-09 | -72C               | W   | 0.862      | 0.417        | -                | 0.252 (0.091)    | 0 (0.000) |    10.14 | mediocrity, qqGOD, Runnin, SALO_MUX, weqt2   |
|           53 |     3755 | 2024-03-30 | aircoal            | W   | 0.800      | -            | -                | -                | 0 (0.000) |     3.18 | mediocrity, qqGOD, Runnin, SALO_MUX, weqt2   |
|           52 |     3775 | 2024-03-30 | Lynn Vision Gaming | W   | 0.796      | 0.417        | 0.063 (0.021)    | 0.431 (0.143)    | 0 (0.000) |    19.99 | mediocrity, qqGOD, Runnin, SALO_MUX, weqt2   |
|           51 |     3785 | 2024-03-30 | Lynn Vision Gaming | L   | 0.796      | -            | -                | -                | -         |    -4.87 | mediocrity, qqGOD, Runnin, SALO_MUX, weqt2   |
|           50 |     3805 | 2024-03-29 | TYLOO              | W   | 0.789      | 0.417        | 0.035 (0.012)    | 0.433 (0.142)    | 0 (0.000) |    13.49 | mediocrity, qqGOD, Runnin, SALO_MUX, weqt2   |
|           49 |     3808 | 2024-03-29 | TYLOO              | W   | 0.789      | 0.417        | 0.035 (0.012)    | 0.433 (0.142)    | 0 (0.000) |    14.45 | mediocrity, qqGOD, Runnin, SALO_MUX, weqt2   |
|           48 |     3999 | 2024-03-26 | aircoal            | W   | 0.769      | -            | -                | -                | -         |     3.90 | mediocrity, qqGOD, Runnin, SALO_MUX, weqt2   |
|           47 |     4404 | 2024-03-16 | pomawnim           | W   | 0.708      | -            | -                | -                | -         |     5.01 | mediocrity, qqGOD, Runnin, SALO_MUX, weqt2   |
|           46 |     4551 | 2024-03-14 | NewHappy           | L   | 0.690      | -            | -                | -                | -         |   -11.89 | mediocrity, qqGOD, Runnin, SALO_MUX, weqt2   |
|           45 |     4556 | 2024-03-14 | NewHappy           | W   | 0.689      | 0.417        | 0.020 (0.006)    | 0.231 (0.067)    | -         |     9.98 | mediocrity, qqGOD, Runnin, SALO_MUX, weqt2   |
|           44 |     4616 | 2024-03-13 | Clutch Gaming      | W   | 0.683      | -            | -                | -                | -         |     7.75 | mediocrity, qqGOD, Runnin, SALO_MUX, weqt2   |
|           43 |     4621 | 2024-03-13 | Clutch Gaming      | L   | 0.683      | -            | -                | -                | -         |   -14.13 | mediocrity, qqGOD, Runnin, SALO_MUX, weqt2   |
|           42 |     5118 | 2024-03-05 | LYG Gaming         | W   | 0.629      | 0.417        | -                | 0.275 (0.072)    | -         |     6.39 | mediocrity, qqGOD, Runnin, SALO_MUX, weqt2   |
|           41 |     5121 | 2024-03-05 | LYG Gaming         | W   | 0.629      | 0.417        | -                | 0.275 (0.072)    | -         |     6.71 | mediocrity, qqGOD, Runnin, SALO_MUX, weqt2   |
|           40 |     5533 | 2024-02-27 | The QUBE Esports   | W   | 0.583      | -            | -                | -                | -         |     5.79 | mediocrity, qqGOD, Runnin, SALO_MUX, weqt2   |
|           39 |     5537 | 2024-02-27 | The QUBE Esports   | W   | 0.583      | -            | -                | -                | -         |     6.05 | mediocrity, qqGOD, Runnin, SALO_MUX, weqt2   |
|           38 |     5706 | 2024-02-24 | Born In Far East   | W   | 0.563      | -            | -                | -                | -         |     6.00 | mediocrity, qqGOD, Runnin, SALO_MUX, weqt2   |
|           37 |     5716 | 2024-02-24 | Born In Far East   | W   | 0.563      | -            | -                | -                | -         |     6.28 | mediocrity, qqGOD, Runnin, SALO_MUX, weqt2   |
|           36 |     5941 | 2024-02-20 | ATOX Esports       | L   | 0.536      | -            | -                | -                | -         |    -1.28 | mediocrity, qqGOD, Runnin, SALO_MUX, weqt2   |
|           35 |     5949 | 2024-02-20 | ATOX Esports       | L   | 0.536      | -            | -                | -                | -         |    -1.30 | mediocrity, qqGOD, Runnin, SALO_MUX, weqt2   |
|           34 |     6136 | 2024-02-16 | FlyQuest           | L   | 0.514      | -            | -                | -                | -         |    -0.45 | mediocrity, qqGOD, Reminder, SALO_MUX, weqt2 |
|           33 |     6175 | 2024-02-16 | Myth Avenue Gaming | L   | 0.509      | -            | -                | -                | -         |    -9.50 | mediocrity, qqGOD, Reminder, SALO_MUX, weqt2 |
|           32 |     6184 | 2024-02-16 | NewHappy           | L   | 0.508      | -            | -                | -                | -         |    -8.99 | mediocrity, qqGOD, Reminder, SALO_MUX, weqt2 |
|           31 |     6246 | 2024-02-15 | The Huns Esports   | W   | 0.502      | -            | -                | -                | -         |     9.72 | mediocrity, qqGOD, Reminder, SALO_MUX, weqt2 |
|           30 |     6297 | 2024-02-14 | ZEUSGG             | W   | 0.496      | -            | -                | -                | -         |     3.33 | mediocrity, qqGOD, Reminder, SALO_MUX, weqt2 |
|           29 |     6305 | 2024-02-14 | Serenity Esports   | W   | 0.496      | -            | -                | -                | -         |     1.50 | mediocrity, qqGOD, Reminder, SALO_MUX, weqt2 |
|           28 |     6532 | 2024-02-08 | DEWA United        | W   | 0.455      | -            | -                | -                | -         |     3.85 | mediocrity, qqGOD, Reminder, SALO_MUX, weqt2 |
|           27 |     6642 | 2024-02-05 | Gods Reign         | W   | 0.435      | 0.310        | 0.004 (0.001)    | -                | -         |     5.24 | mediocrity, qqGOD, Reminder, SALO_MUX, weqt2 |
|           26 |     6841 | 2024-02-02 | Rare Atom          | L   | 0.416      | -            | -                | -                | -         |    -7.21 | mediocrity, qqGOD, Runnin, SALO_MUX, weqt2   |
|           25 |     6849 | 2024-02-01 | ATOX Esports       | W   | 0.414      | 0.143        | 0.047 (0.003)    | -                | -         |    12.13 | mediocrity, qqGOD, Runnin, SALO_MUX, weqt2   |
|           24 |     6891 | 2024-02-01 | NewHappy           | W   | 0.409      | -            | -                | -                | -         |     4.78 | mediocrity, qqGOD, Runnin, SALO_MUX, weqt2   |
|           23 |     6898 | 2024-02-01 | Steel Helmet       | W   | 0.409      | 0.143        | 0.012 (0.001)    | -                | -         |     4.75 | mediocrity, qqGOD, Runnin, SALO_MUX, weqt2   |
|           22 |     6906 | 2024-02-01 | TYLOO              | L   | 0.408      | -            | -                | -                | -         |    -5.30 | mediocrity, qqGOD, Runnin, SALO_MUX, weqt2   |
|           21 |     7320 | 2024-01-25 | Wings Up Gaming    | L   | 0.362      | -            | -                | -                | -         |    -7.03 | mediocrity, qqGOD, Reminder, SALO_MUX, weqt2 |
|           20 |     7360 | 2024-01-24 | -72C               | W   | 0.357      | -            | -                | -                | -         |     5.09 | mediocrity, qqGOD, Reminder, SALO_MUX, weqt2 |
|           19 |     7367 | 2024-01-24 | True Rippers       | W   | 0.356      | 0.143        | 0.025 (0.001)    | -                | -         |     5.44 | mediocrity, qqGOD, Reminder, SALO_MUX, weqt2 |
|           18 |     7436 | 2024-01-22 | Myth Avenue Gaming | W   | 0.348      | -            | -                | -                | -         |     4.24 | mediocrity, qqGOD, Reminder, SALO_MUX, weqt2 |
|           17 |     7437 | 2024-01-22 | NOBackstab         | W   | 0.347      | -            | -                | -                | -         |     1.20 | mediocrity, qqGOD, Reminder, SALO_MUX, weqt2 |
|           16 |     7483 | 2024-01-22 | Steel Helmet       | L   | 0.343      | -            | -                | -                | -         |    -6.82 | mediocrity, qqGOD, Reminder, SALO_MUX, weqt2 |
|           15 |     7488 | 2024-01-22 | Drippy Lab         | W   | 0.343      | -            | -                | -                | -         |     1.16 | mediocrity, qqGOD, Reminder, SALO_MUX, weqt2 |
|           14 |     7598 | 2024-01-20 | The Huns Esports   | L   | 0.329      | -            | -                | -                | -         |    -3.81 | mediocrity, qqGOD, Reminder, SALO_MUX, weqt2 |
|           13 |     7666 | 2024-01-19 | ATOX Esports       | L   | 0.322      | -            | -                | -                | -         |    -0.67 | mediocrity, qqGOD, Reminder, SALO_MUX, weqt2 |
|           12 |     7671 | 2024-01-19 | Eruption           | W   | 0.322      | -            | -                | -                | -         |     2.65 | mediocrity, qqGOD, Reminder, SALO_MUX, weqt2 |
|           11 |     7958 | 2024-01-15 | Fort Arena         | W   | 0.296      | -            | -                | -                | -         |     1.54 | mediocrity, qqGOD, Reminder, SALO_MUX, weqt2 |
|           10 |     7959 | 2024-01-15 | MungYu Esports     | L   | 0.296      | -            | -                | -                | -         |    -7.71 | mediocrity, qqGOD, Reminder, SALO_MUX, weqt2 |
|            9 |     7967 | 2024-01-15 | Chinggis Warriors  | W   | 0.295      | -            | -                | -                | -         |     0.98 | mediocrity, qqGOD, Reminder, SALO_MUX, weqt2 |
|            8 |     7982 | 2024-01-15 | -72C               | W   | 0.295      | -            | -                | -                | -         |     4.33 | mediocrity, qqGOD, Reminder, SALO_MUX, weqt2 |
|            7 |     8912 | 2023-12-16 | DEWA United        | L   | 0.095      | -            | -                | -                | -         |    -2.16 | mediocrity, qqGOD, Reminder, SALO_MUX, weqt2 |
|            6 |     9454 | 2023-12-07 | The MongolZ        | L   | 0.036      | -            | -                | -                | -         |    -0.01 | mediocrity, qqGOD, Reminder, SALO_MUX, weqt2 |
|            5 |     9519 | 2023-12-06 | Lynn Vision Gaming | L   | 0.029      | -            | -                | -                | -         |    -0.13 | mediocrity, qqGOD, Reminder, SALO_MUX, weqt2 |
|            4 |     9596 | 2023-12-05 | ATOX Esports       | W   | 0.022      | 0.417        | 0.047 (0.000)    | -                | -         |     0.67 | mediocrity, qqGOD, Reminder, SALO_MUX, weqt2 |
|            3 |     9784 | 2023-12-02 | MIRAI Gaming       | W   | 0.002      | -            | -                | -                | -         |     0.03 | mediocrity, qqGOD, Reminder, SALO_MUX, weqt2 |
|            2 |     9797 | 2023-12-02 | LYG Gaming         | W   | 0.002      | -            | -                | -                | -         |     0.02 | mediocrity, qqGOD, Reminder, SALO_MUX, weqt2 |
|            1 |     9800 | 2023-12-02 | Born In Far East   | W   | 0.001      | -            | -                | -                | -         |     0.02 | mediocrity, qqGOD, Reminder, SALO_MUX, weqt2 |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($2,005.80)
- Divide that value by the 5th highest value among all rosters ($300,806.11)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-03-30 |      0.800 | $1,080.09      | $863.77         |
| 2024-03-26 |      0.769 | $1,000.00      | $768.89         |
| 2024-02-17 |      0.519 | $500.00        | $259.72         |
| 2023-12-10 |      0.056 | $2,000.00      | $111.67         |
| 2023-12-02 |      0.002 | $750.00        | $1.75           |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
