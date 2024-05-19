### Roster Details<br />
Team Name: The QUBE Esports<br />
Roster: aNSeLMO, deadsh9t, Holy-_-Sanaa, hoolig4n, Randy<br />
Region: [Asia]( ../standings_asia.md)<br />
<br />
Global Rank: [198](../standings_global.md)<br />
Regional Rank: [32]( ../standings_asia.md)<br />
Final Rank Value:  725.7<br />
<br />
Final Rank Value (725.7) = Starting Rank Value (796.6) + Head To Head Adjustments (-71.0)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.293[<sup>1</sup>](#table2)
- Bounty Collected: 0.349[<sup>2</sup>](#table1)
- Opponent Network: 0.068[<sup>2</sup>](#table1)
- LAN Wins: 0.090[<sup>2</sup>](#table1)

The average of these factors is 0.200<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 796.6
- 400 + ( ( 0.200 - 0.000 ) / ( 0.806 - 0.000 ) ) * 1600 = 796.6


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent                 | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins      | H2H Adj. | Roster                                                |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           29 |      741 | 2024-04-20 | Lynn Vision Gaming       | L   | 1.000      | -            | -                | -                | -             |    -2.55 | aNSeLMO, deadsh9t, Holy-_-Sanaa, hoolig4n, Randy      |
|           28 |      754 | 2024-04-20 | Lynn Vision Gaming       | L   | 1.000      | -            | -                | -                | -             |    -2.62 | aNSeLMO, deadsh9t, Holy-_-Sanaa, hoolig4n, Randy      |
|           27 |     1300 | 2024-04-09 | Born In Far East         | L   | 1.000      | -            | -                | -                | -             |   -18.24 | aNSeLMO, deadsh9t, Holy-_-Sanaa, hoolig4n, Randy      |
|           26 |     1305 | 2024-04-09 | Born In Far East         | L   | 1.000      | -            | -                | -                | -             |   -19.85 | aNSeLMO, deadsh9t, Holy-_-Sanaa, hoolig4n, Randy      |
|           25 |     1544 | 2024-04-03 | High Five (Chinese team) | W   | 0.984      | 0.417        | 0.045 (0.019)    | 0.282 (0.116)    | false (0.000) |    17.49 | aNSeLMO, deadsh9t, Holy-_-Sanaa, hoolig4n, Randy      |
|           24 |     1548 | 2024-04-03 | High Five (Chinese team) | L   | 0.984      | -            | -                | -                | -             |   -13.34 | aNSeLMO, deadsh9t, Holy-_-Sanaa, hoolig4n, Randy      |
|           23 |     1665 | 2024-03-29 | LYG Gaming               | L   | 0.951      | -            | -                | -                | -             |   -13.51 | aNSeLMO, deadsh9t, Holy-_-Sanaa, hoolig4n, Randy      |
|           22 |     1667 | 2024-03-29 | LYG Gaming               | L   | 0.951      | -            | -                | -                | -             |   -14.69 | aNSeLMO, deadsh9t, Holy-_-Sanaa, hoolig4n, Randy      |
|           21 |     1765 | 2024-03-27 | ATOX Esports             | L   | 0.937      | -            | -                | -                | -             |    -4.74 | aNSeLMO, deadsh9t, Holy-_-Sanaa, hoolig4n, Randy      |
|           20 |     1769 | 2024-03-27 | ATOX Esports             | L   | 0.937      | -            | -                | -                | -             |    -4.96 | aNSeLMO, deadsh9t, Holy-_-Sanaa, hoolig4n, Randy      |
|           19 |     1827 | 2024-03-26 | Clutch Gaming            | L   | 0.931      | -            | -                | -                | -             |   -17.37 | aNSeLMO, deadsh9t, Holy-_-Sanaa, hoolig4n, Randy      |
|           18 |     1831 | 2024-03-26 | Clutch Gaming            | W   | 0.931      | 0.417        | 0.001 (0.000)    | 0.216 (0.084)    | false (0.000) |    11.81 | aNSeLMO, deadsh9t, Holy-_-Sanaa, hoolig4n, Randy      |
|           17 |     3040 | 2024-02-27 | GR Gaming                | L   | 0.744      | -            | -                | -                | -             |   -10.45 | aNSeLMO, deadsh9t, Holy-_-Sanaa, hoolig4n, Randy      |
|           16 |     3044 | 2024-02-27 | GR Gaming                | L   | 0.744      | -            | -                | -                | -             |   -11.16 | aNSeLMO, deadsh9t, Holy-_-Sanaa, hoolig4n, Randy      |
|           15 |     3369 | 2024-02-20 | Gods Reign               | W   | 0.697      | 0.417        | 0.174 (0.051)    | 0.479 (0.139)    | false (0.000) |    11.65 | aNSeLMO, deadsh9t, Holy-_-Sanaa, hoolig4n, Randy      |
|           14 |     3372 | 2024-02-20 | Gods Reign               | W   | 0.697      | 0.417        | 0.174 (0.051)    | 0.479 (0.139)    | false (0.000) |    12.39 | aNSeLMO, deadsh9t, Holy-_-Sanaa, hoolig4n, Randy      |
|           13 |     3644 | 2024-02-14 | The Huns Esports         | L   | 0.657      | -            | -                | -                | -             |    -7.31 | aNSeLMO, deadsh9t, hoolig4n, me1o, Randy              |
|           12 |     3685 | 2024-02-13 | MIRAI Gaming             | W   | 0.651      | 0.417        | 0.000 (0.000)    | 0.246 (0.067)    | false (0.000) |     6.96 | aNSeLMO, deadsh9t, Holy-_-Sanaa, hoolig4n, Randy      |
|           11 |     3688 | 2024-02-13 | MIRAI Gaming             | W   | 0.651      | 0.417        | 0.000 (0.000)    | 0.246 (0.067)    | false (0.000) |     7.33 | aNSeLMO, deadsh9t, Holy-_-Sanaa, hoolig4n, Randy      |
|           10 |     4848 | 2024-01-15 | Fort Arena               | L   | 0.456      | -            | -                | -                | -             |   -12.27 | cobrazera, deadsh9t, Holy-_-Sanaa, hoolig4n, Randyyyy |
|            9 |     5169 | 2024-01-07 | The MongolZ              | W   | 0.403      | 0.143        | 0.292 (0.017)    | 0.663 (0.038)    | true (0.403)  |    12.59 | cobrazera, deadsh9t, Holy-_-Sanaa, hoolig4n, Randyyyy |
|            8 |     5174 | 2024-01-06 | Team maaRaa              | W   | 0.402      | -            | -                | -                | true (0.402)  |     1.23 | cobrazera, deadsh9t, Holy-_-Sanaa, hoolig4n, Randyyyy |
|            7 |     5329 | 2023-12-18 | MIRAI Gaming             | W   | 0.270      | 0.143        | 0.000 (0.000)    | 0.246 (0.009)    | false (0.000) |     3.26 | aNSeLMO, deadsh9t, Holy-_-Sanaa, hoolig4n, soloooS    |
|            6 |     5379 | 2023-12-17 | Aravt                    | W   | 0.264      | 0.143        | -                | 0.143 (0.005)    | false (0.000) |     1.76 | aNSeLMO, deadsh9t, Holy-_-Sanaa, hoolig4n, soloooS    |
|            5 |     5489 | 2023-12-16 | Born In Far East         | L   | 0.257      | -            | -                | -                | -             |    -4.61 | aNSeLMO, deadsh9t, Holy-_-Sanaa, hoolig4n, soloooS    |
|            4 |     5591 | 2023-12-15 | Hyper5                   | W   | 0.250      | 0.143        | 0.002 (0.000)    | -                | -             |     2.84 | aNSeLMO, deadsh9t, Holy-_-Sanaa, hoolig4n, soloooS    |
|            3 |     5732 | 2023-12-10 | Aravt                    | L   | 0.217      | -            | -                | -                | -             |    -5.45 | aNSeLMO, deadsh9t, Holy-_-Sanaa, hoolig4n, soloooS    |
|            2 |     5895 | 2023-12-07 | MIRAI Gaming             | W   | 0.197      | 0.250        | 0.000 (0.000)    | 0.246 (0.012)    | -             |     2.28 | aNSeLMO, deadsh9t, Holy-_-Sanaa, hoolig4n, soloooS    |
|            1 |     5998 | 2023-12-05 | RAVENS (Japanese team)   | W   | 0.184      | -            | -                | -                | -             |     0.57 | aNSeLMO, deadsh9t, Holy-_-Sanaa, hoolig4n, soloooS    |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($611.06)
- Divide that value by the 5th highest value among all rosters ($158,437.64)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-01-07 |      0.403 | $1,462.14      | $589.36         |
| 2023-12-10 |      0.217 | $100.00        | $21.70          |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
