### Roster Details<br />
Team Name: GR Gaming<br />
Roster: mediocrity, qqGOD, Runnin, SALO_MUX, weqt2<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [69](../standings_global.md)<br />
Regional Rank: [51]( ../standings_europe.md)<br />
Final Rank Value:  928.3<br />
<br />
Final Rank Value (928.3) = Starting Rank Value (814.2) + Head To Head Adjustments (114.1)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.308[<sup>1</sup>](#table2)
- Bounty Collected: 0.382[<sup>2</sup>](#table1)
- Opponent Network: 0.146[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.209<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 814.2
- 400 + ( ( 0.209 - 0.000 ) / ( 0.806 - 0.000 ) ) * 1600 = 814.2


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent                 | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins      | H2H Adj. | Roster                                       |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           54 |     1015 | 2024-04-16 | Sheer Conquer            | L   | 1.000      | -            | -                | -                | -             |   -20.56 | mediocrity, qqGOD, Runnin, SALO_MUX, weqt2   |
|           53 |     1296 | 2024-04-09 | -72C                     | W   | 1.000      | 0.417        | -                | 0.300 (0.125)    | false (0.000) |    10.22 | mediocrity, qqGOD, Runnin, SALO_MUX, weqt2   |
|           52 |     1303 | 2024-04-09 | -72C                     | W   | 1.000      | 0.417        | -                | 0.300 (0.125)    | false (0.000) |    11.06 | mediocrity, qqGOD, Runnin, SALO_MUX, weqt2   |
|           51 |     1644 | 2024-03-30 | Lynn Vision Gaming       | W   | 0.957      | 0.417        | 0.155 (0.062)    | 0.554 (0.221)    | false (0.000) |    25.88 | mediocrity, qqGOD, Runnin, SALO_MUX, weqt2   |
|           50 |     1652 | 2024-03-30 | Lynn Vision Gaming       | L   | 0.957      | -            | -                | -                | -             |    -3.88 | mediocrity, qqGOD, Runnin, SALO_MUX, weqt2   |
|           49 |     1670 | 2024-03-29 | TYLOO                    | W   | 0.950      | 0.417        | 0.131 (0.052)    | 0.592 (0.235)    | false (0.000) |    19.36 | mediocrity, qqGOD, Runnin, SALO_MUX, weqt2   |
|           48 |     1673 | 2024-03-29 | TYLOO                    | W   | 0.950      | 0.417        | 0.131 (0.052)    | 0.592 (0.234)    | false (0.000) |    20.84 | mediocrity, qqGOD, Runnin, SALO_MUX, weqt2   |
|           47 |     2275 | 2024-03-14 | High Five (Chinese team) | L   | 0.851      | -            | -                | -                | -             |   -14.67 | mediocrity, qqGOD, Runnin, SALO_MUX, weqt2   |
|           46 |     2280 | 2024-03-14 | High Five (Chinese team) | W   | 0.851      | 0.417        | 0.045 (0.016)    | 0.282 (0.100)    | false (0.000) |    12.19 | mediocrity, qqGOD, Runnin, SALO_MUX, weqt2   |
|           45 |     2327 | 2024-03-13 | Clutch Gaming            | W   | 0.844      | 0.417        | -                | 0.216 (0.076)    | false (0.000) |     9.39 | mediocrity, qqGOD, Runnin, SALO_MUX, weqt2   |
|           44 |     2332 | 2024-03-13 | Clutch Gaming            | L   | 0.844      | -            | -                | -                | -             |   -17.61 | mediocrity, qqGOD, Runnin, SALO_MUX, weqt2   |
|           43 |     2709 | 2024-03-05 | LYG Gaming               | W   | 0.790      | 0.417        | 0.004 (0.001)    | 0.380 (0.125)    | false (0.000) |     7.79 | mediocrity, qqGOD, Runnin, SALO_MUX, weqt2   |
|           42 |     2712 | 2024-03-05 | LYG Gaming               | W   | 0.790      | 0.417        | -                | 0.380 (0.125)    | false (0.000) |     8.28 | mediocrity, qqGOD, Runnin, SALO_MUX, weqt2   |
|           41 |     3040 | 2024-02-27 | The QUBE Esports         | W   | 0.744      | -            | -                | -                | false (0.000) |    10.45 | mediocrity, qqGOD, Runnin, SALO_MUX, weqt2   |
|           40 |     3044 | 2024-02-27 | The QUBE Esports         | W   | 0.744      | -            | -                | -                | -             |    11.16 | mediocrity, qqGOD, Runnin, SALO_MUX, weqt2   |
|           39 |     3163 | 2024-02-24 | Born In Far East         | W   | 0.724      | -            | -                | -                | -             |     7.23 | mediocrity, qqGOD, Runnin, SALO_MUX, weqt2   |
|           38 |     3171 | 2024-02-24 | Born In Far East         | W   | 0.724      | -            | -                | -                | -             |     7.64 | mediocrity, qqGOD, Runnin, SALO_MUX, weqt2   |
|           37 |     3360 | 2024-02-20 | ATOX Esports             | L   | 0.697      | -            | -                | -                | -             |    -4.28 | mediocrity, qqGOD, Runnin, SALO_MUX, weqt2   |
|           36 |     3367 | 2024-02-20 | ATOX Esports             | L   | 0.697      | -            | -                | -                | -             |    -4.45 | mediocrity, qqGOD, Runnin, SALO_MUX, weqt2   |
|           35 |     3511 | 2024-02-16 | FlyQuest                 | L   | 0.675      | -            | -                | -                | -             |    -0.93 | mediocrity, qqGOD, Reminder, SALO_MUX, weqt2 |
|           34 |     3546 | 2024-02-16 | Myth Avenue Gaming       | L   | 0.670      | -            | -                | -                | -             |   -12.75 | mediocrity, qqGOD, Reminder, SALO_MUX, weqt2 |
|           33 |     3554 | 2024-02-16 | High Five (Chinese team) | L   | 0.669      | -            | -                | -                | -             |   -11.59 | mediocrity, qqGOD, Reminder, SALO_MUX, weqt2 |
|           32 |     3605 | 2024-02-15 | The Huns Esports         | W   | 0.663      | -            | -                | -                | -             |    12.57 | mediocrity, qqGOD, Reminder, SALO_MUX, weqt2 |
|           31 |     3651 | 2024-02-14 | Serenity Esports         | W   | 0.657      | -            | -                | -                | -             |     1.59 | mediocrity, qqGOD, Reminder, SALO_MUX, weqt2 |
|           30 |     3909 | 2024-02-05 | Gods Reign               | W   | 0.596      | 0.310        | 0.174 (0.032)    | 0.479 (0.089)    | -             |    10.22 | mediocrity, qqGOD, Reminder, SALO_MUX, weqt2 |
|           29 |     4050 | 2024-02-02 | Rare Atom                | L   | 0.577      | -            | -                | -                | -             |    -9.27 | mediocrity, qqGOD, Runnin, SALO_MUX, weqt2   |
|           28 |     4057 | 2024-02-01 | ATOX Esports             | W   | 0.576      | 0.143        | 0.112 (0.009)    | -                | -             |    14.51 | mediocrity, qqGOD, Runnin, SALO_MUX, weqt2   |
|           27 |     4084 | 2024-02-01 | NewHappy                 | W   | 0.571      | -            | -                | -                | -             |     7.80 | mediocrity, qqGOD, Runnin, SALO_MUX, weqt2   |
|           26 |     4090 | 2024-02-01 | Steel Helmet             | W   | 0.570      | 0.143        | 0.025 (0.002)    | -                | -             |     6.40 | mediocrity, qqGOD, Runnin, SALO_MUX, weqt2   |
|           25 |     4097 | 2024-02-01 | TYLOO                    | L   | 0.569      | -            | -                | -                | -             |    -3.30 | mediocrity, qqGOD, Runnin, SALO_MUX, weqt2   |
|           24 |     4364 | 2024-01-25 | Wings Up Gaming          | L   | 0.523      | -            | -                | -                | -             |    -9.60 | mediocrity, qqGOD, Reminder, SALO_MUX, weqt2 |
|           23 |     4387 | 2024-01-24 | -72C                     | W   | 0.518      | -            | -                | -                | -             |     7.24 | mediocrity, qqGOD, Reminder, SALO_MUX, weqt2 |
|           22 |     4394 | 2024-01-24 | True Rippers             | W   | 0.517      | 0.143        | 0.059 (0.004)    | -                | -             |     9.24 | mediocrity, qqGOD, Reminder, SALO_MUX, weqt2 |
|           21 |     4444 | 2024-01-22 | Myth Avenue Gaming       | W   | 0.509      | -            | -                | -                | -             |     6.30 | mediocrity, qqGOD, Reminder, SALO_MUX, weqt2 |
|           20 |     4445 | 2024-01-22 | NOBackstab               | W   | 0.509      | -            | -                | -                | -             |     1.52 | mediocrity, qqGOD, Reminder, SALO_MUX, weqt2 |
|           19 |     4481 | 2024-01-22 | Steel Helmet             | L   | 0.504      | -            | -                | -                | -             |   -10.03 | mediocrity, qqGOD, Reminder, SALO_MUX, weqt2 |
|           18 |     4486 | 2024-01-22 | Drippy Lab               | W   | 0.504      | -            | -                | -                | -             |     1.46 | mediocrity, qqGOD, Reminder, SALO_MUX, weqt2 |
|           17 |     4561 | 2024-01-20 | The Huns Esports         | L   | 0.490      | -            | -                | -                | -             |    -5.88 | mediocrity, qqGOD, Reminder, SALO_MUX, weqt2 |
|           16 |     4614 | 2024-01-19 | ATOX Esports             | L   | 0.483      | -            | -                | -                | -             |    -2.84 | mediocrity, qqGOD, Reminder, SALO_MUX, weqt2 |
|           15 |     4617 | 2024-01-19 | Aravt                    | W   | 0.483      | -            | -                | -                | -             |     2.85 | mediocrity, qqGOD, Reminder, SALO_MUX, weqt2 |
|           14 |     4831 | 2024-01-15 | Fort Arena               | W   | 0.457      | -            | -                | -                | -             |     2.16 | mediocrity, qqGOD, Reminder, SALO_MUX, weqt2 |
|           13 |     4833 | 2024-01-15 | MungYu Esports           | L   | 0.457      | -            | -                | -                | -             |   -12.19 | mediocrity, qqGOD, Reminder, SALO_MUX, weqt2 |
|           12 |     4838 | 2024-01-15 | Chinggis Warriors        | W   | 0.456      | -            | -                | -                | -             |     1.26 | mediocrity, qqGOD, Reminder, SALO_MUX, weqt2 |
|           11 |     4851 | 2024-01-15 | -72C                     | W   | 0.456      | -            | -                | -                | -             |     6.56 | mediocrity, qqGOD, Reminder, SALO_MUX, weqt2 |
|           10 |     5506 | 2023-12-16 | LETUSWIN69               | L   | 0.256      | -            | -                | -                | -             |    -6.23 | mediocrity, qqGOD, Reminder, SALO_MUX, weqt2 |
|            9 |     5899 | 2023-12-07 | The MongolZ              | L   | 0.197      | -            | -                | -                | -             |    -0.06 | mediocrity, qqGOD, Reminder, SALO_MUX, weqt2 |
|            8 |     5947 | 2023-12-06 | Lynn Vision Gaming       | L   | 0.190      | -            | -                | -                | -             |    -0.43 | mediocrity, qqGOD, Reminder, SALO_MUX, weqt2 |
|            7 |     6003 | 2023-12-05 | ATOX Esports             | W   | 0.184      | 0.417        | 0.112 (0.009)    | -                | -             |     4.79 | mediocrity, qqGOD, Reminder, SALO_MUX, weqt2 |
|            6 |     6128 | 2023-12-02 | MIRAI Gaming             | W   | 0.163      | -            | -                | -                | -             |     1.76 | mediocrity, qqGOD, Reminder, SALO_MUX, weqt2 |
|            5 |     6141 | 2023-12-02 | LYG Gaming               | W   | 0.163      | -            | -                | -                | -             |     2.35 | mediocrity, qqGOD, Reminder, SALO_MUX, weqt2 |
|            4 |     6143 | 2023-12-02 | Born In Far East         | W   | 0.162      | -            | -                | -                | -             |     2.04 | mediocrity, qqGOD, Reminder, SALO_MUX, weqt2 |
|            3 |     6605 | 2023-11-21 | Clutch Gaming            | W   | 0.090      | -            | -                | -                | -             |     1.11 | mediocrity, qqGOD, Reminder, SALO_MUX, weqt2 |
|            2 |     6894 | 2023-11-15 | The Huns Esports         | L   | 0.050      | -            | -                | -                | -             |    -0.56 | mediocrity, qqGOD, Reminder, SALO_MUX, weqt2 |
|            1 |     7209 | 2023-11-08 | The MongolZ              | L   | 0.004      | -            | -                | -                | -             |    -0.00 | mediocrity, qqGOD, Reminder, SALO_MUX, weqt2 |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($896.60)
- Divide that value by the 5th highest value among all rosters ($158,437.64)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-02-17 |      0.681 | $500.00        | $340.25         |
| 2023-12-10 |      0.217 | $2,000.00      | $433.80         |
| 2023-12-02 |      0.163 | $750.00        | $122.55         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
