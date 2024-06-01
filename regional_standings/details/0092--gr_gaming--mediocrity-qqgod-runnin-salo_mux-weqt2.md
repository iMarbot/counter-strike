### Roster Details<br />
Team Name: GR Gaming<br />
Roster: mediocrity, qqGOD, Runnin, SALO_MUX, weqt2<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [92](../standings_global.md)<br />
Regional Rank: [65]( ../standings_europe.md)<br />
Final Rank Value:  888.1<br />
<br />
Final Rank Value (888.1) = Starting Rank Value (783.1) + Head To Head Adjustments (105.0)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.315[<sup>1</sup>](#table2)
- Bounty Collected: 0.329[<sup>2</sup>](#table1)
- Opponent Network: 0.109[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.188<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 783.1
- 400 + ( ( 0.188 - 0.000 ) / ( 0.786 - 0.000 ) ) * 1600 = 783.1


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
|           61 |      712 | 2024-05-20 | ZEUSGG             | W   | 1.000      | -            | -                | -                | 0 (0.000) |     3.26 | mediocrity, qqGOD, Runnin, SALO_MUX, weqt2   |
|           60 |      715 | 2024-05-20 | ZEUSGG             | W   | 1.000      | -            | -                | -                | 0 (0.000) |     3.37 | mediocrity, qqGOD, Runnin, SALO_MUX, weqt2   |
|           59 |     1178 | 2024-05-15 | MIRAI Gaming       | W   | 1.000      | 0.417        | -                | 0.200 (0.083)    | 0 (0.000) |     9.35 | mediocrity, qqGOD, Runnin, SALO_MUX, weqt2   |
|           58 |     1189 | 2024-05-15 | MIRAI Gaming       | L   | 1.000      | -            | -                | -                | -         |   -22.65 | mediocrity, qqGOD, Runnin, SALO_MUX, weqt2   |
|           57 |     1330 | 2024-05-13 | Gods Reign         | W   | 1.000      | 0.417        | 0.086 (0.036)    | 0.461 (0.192)    | 0 (0.000) |    14.57 | mediocrity, qqGOD, Runnin, SALO_MUX, weqt2   |
|           56 |     2920 | 2024-04-16 | Sheer Conquer      | L   | 0.909      | -            | -                | -                | -         |   -18.30 | mediocrity, qqGOD, Runnin, SALO_MUX, weqt2   |
|           55 |     3254 | 2024-04-09 | -72C               | W   | 0.863      | 0.417        | -                | 0.252 (0.091)    | 0 (0.000) |     9.29 | mediocrity, qqGOD, Runnin, SALO_MUX, weqt2   |
|           54 |     3261 | 2024-04-09 | -72C               | W   | 0.862      | 0.417        | -                | 0.252 (0.091)    | 0 (0.000) |     9.96 | mediocrity, qqGOD, Runnin, SALO_MUX, weqt2   |
|           53 |     3662 | 2024-03-30 | aircoal            | W   | 0.800      | -            | -                | -                | 0 (0.000) |     3.15 | mediocrity, qqGOD, Runnin, SALO_MUX, weqt2   |
|           52 |     3682 | 2024-03-30 | Lynn Vision Gaming | W   | 0.796      | 0.417        | 0.063 (0.021)    | 0.414 (0.137)    | 0 (0.000) |    19.92 | mediocrity, qqGOD, Runnin, SALO_MUX, weqt2   |
|           51 |     3692 | 2024-03-30 | Lynn Vision Gaming | L   | 0.796      | -            | -                | -                | -         |    -4.93 | mediocrity, qqGOD, Runnin, SALO_MUX, weqt2   |
|           50 |     3711 | 2024-03-29 | TYLOO              | W   | 0.789      | 0.417        | 0.035 (0.012)    | 0.433 (0.142)    | 0 (0.000) |    13.82 | mediocrity, qqGOD, Runnin, SALO_MUX, weqt2   |
|           49 |     3714 | 2024-03-29 | TYLOO              | W   | 0.789      | 0.417        | 0.035 (0.012)    | 0.433 (0.142)    | 0 (0.000) |    14.80 | mediocrity, qqGOD, Runnin, SALO_MUX, weqt2   |
|           48 |     3902 | 2024-03-26 | aircoal            | W   | 0.769      | -            | -                | -                | -         |     3.87 | mediocrity, qqGOD, Runnin, SALO_MUX, weqt2   |
|           47 |     4298 | 2024-03-16 | pomawnim           | W   | 0.708      | -            | -                | -                | -         |     4.98 | mediocrity, qqGOD, Runnin, SALO_MUX, weqt2   |
|           46 |     4437 | 2024-03-14 | NewHappy           | L   | 0.690      | -            | -                | -                | -         |   -11.94 | mediocrity, qqGOD, Runnin, SALO_MUX, weqt2   |
|           45 |     4442 | 2024-03-14 | NewHappy           | W   | 0.689      | 0.417        | 0.020 (0.006)    | 0.231 (0.067)    | -         |     9.93 | mediocrity, qqGOD, Runnin, SALO_MUX, weqt2   |
|           44 |     4501 | 2024-03-13 | Clutch Gaming      | W   | 0.683      | -            | -                | -                | -         |     7.54 | mediocrity, qqGOD, Runnin, SALO_MUX, weqt2   |
|           43 |     4506 | 2024-03-13 | Clutch Gaming      | L   | 0.683      | -            | -                | -                | -         |   -14.35 | mediocrity, qqGOD, Runnin, SALO_MUX, weqt2   |
|           42 |     4973 | 2024-03-05 | LYG Gaming         | W   | 0.629      | 0.417        | -                | 0.275 (0.072)    | -         |     6.33 | mediocrity, qqGOD, Runnin, SALO_MUX, weqt2   |
|           41 |     4976 | 2024-03-05 | LYG Gaming         | W   | 0.629      | 0.417        | -                | 0.275 (0.072)    | -         |     6.65 | mediocrity, qqGOD, Runnin, SALO_MUX, weqt2   |
|           40 |     5379 | 2024-02-27 | The QUBE Esports   | W   | 0.583      | -            | -                | -                | -         |     7.83 | mediocrity, qqGOD, Runnin, SALO_MUX, weqt2   |
|           39 |     5383 | 2024-02-27 | The QUBE Esports   | W   | 0.583      | -            | -                | -                | -         |     8.23 | mediocrity, qqGOD, Runnin, SALO_MUX, weqt2   |
|           38 |     5546 | 2024-02-24 | Born In Far East   | W   | 0.563      | -            | -                | -                | -         |     5.75 | mediocrity, qqGOD, Runnin, SALO_MUX, weqt2   |
|           37 |     5556 | 2024-02-24 | Born In Far East   | W   | 0.563      | -            | -                | -                | -         |     6.01 | mediocrity, qqGOD, Runnin, SALO_MUX, weqt2   |
|           36 |     5772 | 2024-02-20 | ATOX Esports       | L   | 0.536      | -            | -                | -                | -         |    -1.57 | mediocrity, qqGOD, Runnin, SALO_MUX, weqt2   |
|           35 |     5779 | 2024-02-20 | ATOX Esports       | L   | 0.536      | -            | -                | -                | -         |    -1.59 | mediocrity, qqGOD, Runnin, SALO_MUX, weqt2   |
|           34 |     5963 | 2024-02-16 | FlyQuest           | L   | 0.514      | -            | -                | -                | -         |    -0.45 | mediocrity, qqGOD, Reminder, SALO_MUX, weqt2 |
|           33 |     5999 | 2024-02-16 | Myth Avenue Gaming | L   | 0.509      | -            | -                | -                | -         |    -9.47 | mediocrity, qqGOD, Reminder, SALO_MUX, weqt2 |
|           32 |     6008 | 2024-02-16 | NewHappy           | L   | 0.508      | -            | -                | -                | -         |    -8.97 | mediocrity, qqGOD, Reminder, SALO_MUX, weqt2 |
|           31 |     6065 | 2024-02-15 | The Huns Esports   | W   | 0.502      | -            | -                | -                | -         |     9.78 | mediocrity, qqGOD, Reminder, SALO_MUX, weqt2 |
|           30 |     6116 | 2024-02-14 | ZEUSGG             | W   | 0.496      | -            | -                | -                | -         |     2.55 | mediocrity, qqGOD, Reminder, SALO_MUX, weqt2 |
|           29 |     6124 | 2024-02-14 | Serenity Esports   | W   | 0.496      | -            | -                | -                | -         |     1.50 | mediocrity, qqGOD, Reminder, SALO_MUX, weqt2 |
|           28 |     6344 | 2024-02-08 | DEWA United        | W   | 0.455      | -            | -                | -                | -         |     3.75 | mediocrity, qqGOD, Reminder, SALO_MUX, weqt2 |
|           27 |     6440 | 2024-02-05 | Gods Reign         | W   | 0.435      | 0.310        | 0.004 (0.001)    | -                | -         |     5.25 | mediocrity, qqGOD, Reminder, SALO_MUX, weqt2 |
|           26 |     6636 | 2024-02-02 | Rare Atom          | L   | 0.416      | -            | -                | -                | -         |    -7.21 | mediocrity, qqGOD, Runnin, SALO_MUX, weqt2   |
|           25 |     6644 | 2024-02-01 | ATOX Esports       | W   | 0.414      | 0.143        | 0.047 (0.003)    | -                | -         |    11.90 | mediocrity, qqGOD, Runnin, SALO_MUX, weqt2   |
|           24 |     6682 | 2024-02-01 | NewHappy           | W   | 0.409      | -            | -                | -                | -         |     4.78 | mediocrity, qqGOD, Runnin, SALO_MUX, weqt2   |
|           23 |     6689 | 2024-02-01 | Steel Helmet       | W   | 0.409      | 0.143        | 0.012 (0.001)    | -                | -         |     4.76 | mediocrity, qqGOD, Runnin, SALO_MUX, weqt2   |
|           22 |     6697 | 2024-02-01 | TYLOO              | L   | 0.408      | -            | -                | -                | -         |    -5.29 | mediocrity, qqGOD, Runnin, SALO_MUX, weqt2   |
|           21 |     7091 | 2024-01-25 | Wings Up Gaming    | L   | 0.362      | -            | -                | -                | -         |    -7.02 | mediocrity, qqGOD, Reminder, SALO_MUX, weqt2 |
|           20 |     7125 | 2024-01-24 | -72C               | W   | 0.357      | -            | -                | -                | -         |     5.09 | mediocrity, qqGOD, Reminder, SALO_MUX, weqt2 |
|           19 |     7132 | 2024-01-24 | True Rippers       | W   | 0.356      | 0.143        | 0.025 (0.001)    | -                | -         |     5.45 | mediocrity, qqGOD, Reminder, SALO_MUX, weqt2 |
|           18 |     7195 | 2024-01-22 | Myth Avenue Gaming | W   | 0.348      | -            | -                | -                | -         |     4.25 | mediocrity, qqGOD, Reminder, SALO_MUX, weqt2 |
|           17 |     7196 | 2024-01-22 | NOBackstab         | W   | 0.347      | -            | -                | -                | -         |     1.20 | mediocrity, qqGOD, Reminder, SALO_MUX, weqt2 |
|           16 |     7240 | 2024-01-22 | Steel Helmet       | L   | 0.343      | -            | -                | -                | -         |    -6.81 | mediocrity, qqGOD, Reminder, SALO_MUX, weqt2 |
|           15 |     7245 | 2024-01-22 | Drippy Lab         | W   | 0.343      | -            | -                | -                | -         |     1.16 | mediocrity, qqGOD, Reminder, SALO_MUX, weqt2 |
|           14 |     7354 | 2024-01-20 | The Huns Esports   | L   | 0.329      | -            | -                | -                | -         |    -3.81 | mediocrity, qqGOD, Reminder, SALO_MUX, weqt2 |
|           13 |     7419 | 2024-01-19 | ATOX Esports       | L   | 0.322      | -            | -                | -                | -         |    -0.83 | mediocrity, qqGOD, Reminder, SALO_MUX, weqt2 |
|           12 |     7424 | 2024-01-19 | Eruption           | W   | 0.322      | -            | -                | -                | -         |     2.67 | mediocrity, qqGOD, Reminder, SALO_MUX, weqt2 |
|           11 |     7708 | 2024-01-15 | Fort Arena         | W   | 0.296      | -            | -                | -                | -         |     1.55 | mediocrity, qqGOD, Reminder, SALO_MUX, weqt2 |
|           10 |     7709 | 2024-01-15 | MungYu Esports     | L   | 0.296      | -            | -                | -                | -         |    -7.74 | mediocrity, qqGOD, Reminder, SALO_MUX, weqt2 |
|            9 |     7715 | 2024-01-15 | Chinggis Warriors  | W   | 0.295      | -            | -                | -                | -         |     0.98 | mediocrity, qqGOD, Reminder, SALO_MUX, weqt2 |
|            8 |     7729 | 2024-01-15 | -72C               | W   | 0.295      | -            | -                | -                | -         |     4.32 | mediocrity, qqGOD, Reminder, SALO_MUX, weqt2 |
|            7 |     8651 | 2023-12-16 | DEWA United        | L   | 0.095      | -            | -                | -                | -         |    -2.19 | mediocrity, qqGOD, Reminder, SALO_MUX, weqt2 |
|            6 |     9181 | 2023-12-07 | The MongolZ        | L   | 0.036      | -            | -                | -                | -         |    -0.01 | mediocrity, qqGOD, Reminder, SALO_MUX, weqt2 |
|            5 |     9238 | 2023-12-06 | Lynn Vision Gaming | L   | 0.029      | -            | -                | -                | -         |    -0.12 | mediocrity, qqGOD, Reminder, SALO_MUX, weqt2 |
|            4 |     9314 | 2023-12-05 | ATOX Esports       | W   | 0.022      | 0.417        | 0.047 (0.000)    | -                | -         |     0.65 | mediocrity, qqGOD, Reminder, SALO_MUX, weqt2 |
|            3 |     9502 | 2023-12-02 | MIRAI Gaming       | W   | 0.002      | -            | -                | -                | -         |     0.03 | mediocrity, qqGOD, Reminder, SALO_MUX, weqt2 |
|            2 |     9515 | 2023-12-02 | LYG Gaming         | W   | 0.002      | -            | -                | -                | -         |     0.02 | mediocrity, qqGOD, Reminder, SALO_MUX, weqt2 |
|            1 |     9518 | 2023-12-02 | Born In Far East   | W   | 0.001      | -            | -                | -                | -         |     0.02 | mediocrity, qqGOD, Reminder, SALO_MUX, weqt2 |

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
