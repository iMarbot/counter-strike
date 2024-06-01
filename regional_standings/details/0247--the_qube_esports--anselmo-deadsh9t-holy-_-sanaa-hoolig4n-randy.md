### Roster Details<br />
Team Name: The QUBE Esports<br />
Roster: aNSeLMO, deadsh9t, Holy-_-Sanaa, hoolig4n, Randy<br />
Region: [Asia]( ../standings_asia.md)<br />
<br />
Global Rank: [247](../standings_global.md)<br />
Regional Rank: [35]( ../standings_asia.md)<br />
Final Rank Value:  687.1<br />
<br />
Final Rank Value (687.1) = Starting Rank Value (738.9) + Head To Head Adjustments (-51.8)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.255[<sup>1</sup>](#table2)
- Bounty Collected: 0.305[<sup>2</sup>](#table1)
- Opponent Network: 0.055[<sup>2</sup>](#table1)
- LAN Wins: 0.051[<sup>2</sup>](#table1)

The average of these factors is 0.166<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 738.9
- 400 + ( ( 0.166 - 0.000 ) / ( 0.786 - 0.000 ) ) * 1600 = 738.9


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent           | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                                |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           35 |      610 | 2024-05-21 | TYLOO              | L   | 1.000      | -            | -                | -                | -         |    -4.54 | aNSeLMO, deadsh9t, Holy-_-Sanaa, hoolig4n, Randy      |
|           34 |      617 | 2024-05-21 | TYLOO              | L   | 1.000      | -            | -                | -                | -         |    -4.75 | aNSeLMO, deadsh9t, Holy-_-Sanaa, hoolig4n, Randy      |
|           33 |     1283 | 2024-05-14 | -72C               | L   | 1.000      | -            | -                | -                | -         |   -11.82 | aNSeLMO, deadsh9t, Holy-_-Sanaa, hoolig4n, Randy      |
|           32 |     1289 | 2024-05-14 | -72C               | W   | 1.000      | 0.417        | 0.000 (0.000)    | 0.252 (0.105)    | 0 (0.000) |    20.02 | aNSeLMO, deadsh9t, Holy-_-Sanaa, hoolig4n, Randy      |
|           31 |     2609 | 2024-04-20 | Lynn Vision Gaming | L   | 0.936      | -            | -                | -                | -         |    -3.41 | aNSeLMO, deadsh9t, Holy-_-Sanaa, hoolig4n, Randy      |
|           30 |     2624 | 2024-04-20 | Lynn Vision Gaming | L   | 0.936      | -            | -                | -                | -         |    -3.53 | aNSeLMO, deadsh9t, Holy-_-Sanaa, hoolig4n, Randy      |
|           29 |     3258 | 2024-04-09 | Born In Far East   | L   | 0.862      | -            | -                | -                | -         |   -15.34 | aNSeLMO, deadsh9t, Holy-_-Sanaa, hoolig4n, Randy      |
|           28 |     3263 | 2024-04-09 | Born In Far East   | L   | 0.862      | -            | -                | -                | -         |   -16.52 | aNSeLMO, deadsh9t, Holy-_-Sanaa, hoolig4n, Randy      |
|           27 |     3562 | 2024-04-03 | NewHappy           | W   | 0.823      | 0.417        | 0.020 (0.007)    | 0.231 (0.079)    | 0 (0.000) |    14.69 | aNSeLMO, deadsh9t, Holy-_-Sanaa, hoolig4n, Randy      |
|           26 |     3566 | 2024-04-03 | NewHappy           | L   | 0.822      | -            | -                | -                | -         |   -11.26 | aNSeLMO, deadsh9t, Holy-_-Sanaa, hoolig4n, Randy      |
|           25 |     3706 | 2024-03-29 | LYG Gaming         | L   | 0.790      | -            | -                | -                | -         |   -11.56 | aNSeLMO, deadsh9t, Holy-_-Sanaa, hoolig4n, Randy      |
|           24 |     3708 | 2024-03-29 | LYG Gaming         | L   | 0.789      | -            | -                | -                | -         |   -12.39 | aNSeLMO, deadsh9t, Holy-_-Sanaa, hoolig4n, Randy      |
|           23 |     3824 | 2024-03-27 | ATOX Esports       | L   | 0.776      | -            | -                | -                | -         |    -2.01 | aNSeLMO, deadsh9t, Holy-_-Sanaa, hoolig4n, Randy      |
|           22 |     3828 | 2024-03-27 | ATOX Esports       | L   | 0.776      | -            | -                | -                | -         |    -2.05 | aNSeLMO, deadsh9t, Holy-_-Sanaa, hoolig4n, Randy      |
|           21 |     3895 | 2024-03-26 | Clutch Gaming      | L   | 0.770      | -            | -                | -                | -         |   -14.12 | aNSeLMO, deadsh9t, Holy-_-Sanaa, hoolig4n, Randy      |
|           20 |     3899 | 2024-03-26 | Clutch Gaming      | W   | 0.769      | 0.417        | 0.000 (0.000)    | 0.167 (0.053)    | 0 (0.000) |    10.18 | aNSeLMO, deadsh9t, Holy-_-Sanaa, hoolig4n, Randy      |
|           19 |     5379 | 2024-02-27 | GR Gaming          | L   | 0.583      | -            | -                | -                | -         |    -7.83 | aNSeLMO, deadsh9t, Holy-_-Sanaa, hoolig4n, Randy      |
|           18 |     5383 | 2024-02-27 | GR Gaming          | L   | 0.583      | -            | -                | -                | -         |    -8.23 | aNSeLMO, deadsh9t, Holy-_-Sanaa, hoolig4n, Randy      |
|           17 |     5781 | 2024-02-20 | Gods Reign         | W   | 0.536      | 0.417        | 0.086 (0.019)    | 0.461 (0.103)    | 0 (0.000) |    11.19 | aNSeLMO, deadsh9t, Holy-_-Sanaa, hoolig4n, Randy      |
|           16 |     5784 | 2024-02-20 | Gods Reign         | W   | 0.536      | 0.417        | 0.086 (0.019)    | 0.461 (0.103)    | 0 (0.000) |    11.66 | aNSeLMO, deadsh9t, Holy-_-Sanaa, hoolig4n, Randy      |
|           15 |     6117 | 2024-02-14 | The Huns Esports   | L   | 0.496      | -            | -                | -                | -         |    -4.97 | aNSeLMO, deadsh9t, hoolig4n, me1o, Randy              |
|           14 |     6163 | 2024-02-13 | MIRAI Gaming       | W   | 0.490      | 0.417        | 0.000 (0.000)    | 0.200 (0.041)    | 0 (0.000) |     6.53 | aNSeLMO, deadsh9t, Holy-_-Sanaa, hoolig4n, Randy      |
|           13 |     6167 | 2024-02-13 | MIRAI Gaming       | W   | 0.489      | 0.417        | 0.000 (0.000)    | 0.200 (0.041)    | 0 (0.000) |     6.81 | aNSeLMO, deadsh9t, Holy-_-Sanaa, hoolig4n, Randy      |
|           12 |     7726 | 2024-01-15 | Fort Arena         | L   | 0.295      | -            | -                | -                | -         |    -7.57 | cobrazera, deadsh9t, Holy-_-Sanaa, hoolig4n, Randyyyy |
|           11 |     8197 | 2024-01-07 | The MongolZ        | W   | 0.242      | 0.143        | 0.192 (0.007)    | 0.619 (0.021)    | 1 (0.242) |     7.57 | cobrazera, deadsh9t, Holy-_-Sanaa, hoolig4n, Randyyyy |
|           10 |     8202 | 2024-01-06 | Team maaRaa        | W   | 0.241      | -            | -                | -                | 1 (0.241) |     0.99 | cobrazera, deadsh9t, Holy-_-Sanaa, hoolig4n, Randyyyy |
|            9 |     8418 | 2023-12-18 | MIRAI Gaming       | W   | 0.109      | 0.143        | 0.000 (0.000)    | 0.200 (0.003)    | 0 (0.000) |     1.58 | aNSeLMO, deadsh9t, Holy-_-Sanaa, hoolig4n, soloooS    |
|            8 |     8484 | 2023-12-17 | Eruption           | W   | 0.102      | -            | -                | -                | -         |     1.02 | aNSeLMO, deadsh9t, Holy-_-Sanaa, hoolig4n, soloooS    |
|            7 |     8631 | 2023-12-16 | Born In Far East   | L   | 0.096      | -            | -                | -                | -         |    -1.63 | aNSeLMO, deadsh9t, Holy-_-Sanaa, hoolig4n, soloooS    |
|            6 |     8752 | 2023-12-15 | Hyper5             | W   | 0.089      | 0.143        | 0.000 (0.000)    | -                | -         |     0.94 | aNSeLMO, deadsh9t, Holy-_-Sanaa, hoolig4n, soloooS    |
|            5 |     8890 | 2023-12-12 | DEWA United        | L   | 0.069      | -            | -                | -                | -         |    -1.17 | aNSeLMO, deadsh9t, Holy-_-Sanaa, hoolig4n, soloooS    |
|            4 |     8979 | 2023-12-10 | Eruption           | L   | 0.056      | -            | -                | -                | -         |    -1.21 | aNSeLMO, deadsh9t, Holy-_-Sanaa, hoolig4n, soloooS    |
|            3 |     9038 | 2023-12-09 | ZEUSGG             | W   | 0.049      | -            | -                | -                | -         |     0.33 | aNSeLMO, deadsh9t, Holy-_-Sanaa, hoolig4n, soloooS    |
|            2 |     9176 | 2023-12-07 | MIRAI Gaming       | W   | 0.036      | 0.250        | -                | 0.200 (0.002)    | -         |     0.52 | aNSeLMO, deadsh9t, Holy-_-Sanaa, hoolig4n, soloooS    |
|            1 |     9310 | 2023-12-05 | RAVENS             | W   | 0.023      | -            | -                | -                | -         |     0.09 | aNSeLMO, deadsh9t, Holy-_-Sanaa, hoolig4n, soloooS    |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($361.46)
- Divide that value by the 5th highest value among all rosters ($300,806.11)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-01-07 |      0.242 | $1,462.14      | $353.86         |
| 2023-12-13 |      0.076 | $100.00        | $7.60           |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
