### Roster Details<br />
Team Name: Rebels Gaming<br />
Roster: casey, Flayy, innocent, kisserek, olimp<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [36](../standings_global.md)<br />
Regional Rank: [27]( ../standings_europe.md)<br />
Final Rank Value:  1164.1<br />
<br />
Final Rank Value (1164.1) = Starting Rank Value (1178.0) + Head To Head Adjustments (-13.9)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.522[<sup>1</sup>](#table2)
- Bounty Collected: 0.484[<sup>2</sup>](#table1)
- Opponent Network: 0.212[<sup>2</sup>](#table1)
- LAN Wins: 0.350[<sup>2</sup>](#table1)

The average of these factors is 0.392<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1178.0
- 400 + ( ( 0.392 - 0.000 ) / ( 0.806 - 0.000 ) ) * 1600 = 1178.0


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent               | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                  |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           37 |      329 | 2024-04-27 | Aurora Gaming          | L   | 1.000      | -            | -                | -                | -         |    -4.75 | casey, Flayy, innocent, kisserek, olimp |
|           36 |      451 | 2024-04-26 | MIBR                   | W   | 1.000      | 0.500        | 0.654 (0.327)    | 0.616 (0.308)    | 1 (1.000) |    28.99 | casey, Flayy, innocent, kisserek, olimp |
|           35 |      453 | 2024-04-25 | Rooster                | W   | 1.000      | 0.500        | 0.031 (0.016)    | 0.312 (0.156)    | 1 (1.000) |     5.47 | casey, Flayy, innocent, kisserek, olimp |
|           34 |      929 | 2024-04-17 | EYEBALLERS             | L   | 1.000      | -            | -                | -                | -         |   -24.57 | casey, Flayy, innocent, kisserek, olimp |
|           33 |     1108 | 2024-04-13 | Monte                  | L   | 1.000      | -            | -                | -                | -         |    -9.18 | casey, Flayy, innocent, kisserek, olimp |
|           32 |     1281 | 2024-04-09 | B8                     | W   | 1.000      | 0.500        | 0.088 (0.044)    | 0.589 (0.294)    | 0 (0.000) |     9.99 | casey, Flayy, innocent, kisserek, olimp |
|           31 |     1492 | 2024-04-04 | ALTERNATE aTTaX        | W   | 0.991      | 0.500        | 0.110 (0.054)    | 0.723 (0.358)    | 0 (0.000) |     7.10 | casey, Flayy, innocent, kisserek, olimp |
|           30 |     1741 | 2024-03-27 | Sashi Esport           | W   | 0.939      | 0.143        | 0.193 (0.026)    | 1.000 (0.134)    | 0 (0.000) |    11.20 | casey, Flayy, innocent, kisserek, olimp |
|           29 |     1756 | 2024-03-27 | Passion UA             | W   | 0.938      | 0.143        | 0.114 (0.015)    | 0.980 (0.131)    | 0 (0.000) |     8.94 | casey, Flayy, innocent, kisserek, olimp |
|           28 |     1843 | 2024-03-25 | Aurora Gaming          | L   | 0.925      | -            | -                | -                | -         |    -3.14 | casey, Flayy, innocent, kisserek, olimp |
|           27 |     2805 | 2024-03-03 | Sangal Esports         | W   | 0.778      | 0.500        | -                | 0.350 (0.136)    | 0 (0.000) |     2.46 | casey, Flayy, kisserek, olimp, sNx      |
|           26 |     2879 | 2024-03-02 | Aurora Gaming          | L   | 0.771      | -            | -                | -                | -         |    -2.41 | casey, Flayy, kisserek, olimp, sNx      |
|           25 |     2955 | 2024-02-29 | Sangal Esports         | W   | 0.758      | 0.500        | -                | 0.350 (0.133)    | 0 (0.000) |     2.25 | casey, Flayy, kisserek, olimp, sNx      |
|           24 |     3916 | 2024-02-04 | Team Falcons           | L   | 0.592      | -            | -                | -                | -         |    -4.09 | casey, Flayy, kisserek, olimp, sNx      |
|           23 |     3976 | 2024-02-03 | FaZe Clan              | L   | 0.585      | -            | -                | -                | -         |    -0.15 | casey, Flayy, kisserek, olimp, sNx      |
|           22 |     4013 | 2024-02-02 | M80                    | W   | 0.579      | 1.000        | 0.155 (0.090)    | 0.405 (0.235)    | 1 (0.579) |    12.90 | casey, Flayy, kisserek, olimp, sNx      |
|           21 |     4098 | 2024-01-31 | Eternal Fire           | L   | 0.566      | -            | -                | -                | -         |    -0.39 | casey, Flayy, kisserek, olimp, sNx      |
|           20 |     4113 | 2024-01-31 | Cloud9                 | W   | 0.565      | 1.000        | 0.487 (0.275)    | 0.419 (0.237)    | 1 (0.565) |    17.34 | casey, Flayy, kisserek, olimp, sNx      |
|           19 |     4216 | 2024-01-28 | 9Pandas                | L   | 0.545      | -            | -                | -                | -         |    -7.81 | casey, Flayy, kisserek, olimp, sNx      |
|           18 |     4325 | 2024-01-26 | ILIN                   | W   | 0.531      | -            | -                | -                | -         |     0.77 | casey, Flayy, kisserek, olimp, sNx      |
|           17 |     4378 | 2024-01-24 | Grindas                | W   | 0.519      | -            | -                | -                | -         |     1.48 | casey, Flayy, kisserek, olimp, sNx      |
|           16 |     4429 | 2024-01-23 | Viperio                | L   | 0.512      | -            | -                | -                | -         |   -15.28 | casey, Flayy, kisserek, olimp, sNx      |
|           15 |     4432 | 2024-01-23 | Pera Esports           | L   | 0.511      | -            | -                | -                | -         |   -12.00 | casey, Flayy, kisserek, olimp, sNx      |
|           14 |     4455 | 2024-01-22 | Team Sampi             | L   | 0.506      | -            | -                | -                | -         |   -10.38 | casey, Flayy, kisserek, olimp, sNx      |
|           13 |     4468 | 2024-01-22 | ALTERNATE aTTaX        | W   | 0.505      | 0.143        | 0.110 (0.008)    | -                | -         |     6.24 | casey, Flayy, kisserek, olimp, sNx      |
|           12 |     4475 | 2024-01-22 | Guild Eagles           | L   | 0.505      | -            | -                | -                | -         |    -9.78 | casey, Flayy, kisserek, olimp, sNx      |
|           11 |     4701 | 2024-01-17 | Guild Eagles           | L   | 0.473      | -            | -                | -                | -         |    -9.64 | casey, Flayy, kisserek, olimp, sNx      |
|           10 |     4724 | 2024-01-17 | RUSH B (Russian team)  | W   | 0.472      | -            | -                | -                | -         |     1.51 | casey, Flayy, kisserek, olimp, sNx      |
|            9 |     4780 | 2024-01-16 | Passion UA             | L   | 0.466      | -            | -                | -                | -         |   -10.79 | casey, Flayy, kisserek, olimp, sNx      |
|            8 |     4788 | 2024-01-16 | Soda Gaming            | W   | 0.466      | -            | -                | -                | -         |     1.34 | casey, Flayy, kisserek, olimp, sNx      |
|            7 |     4800 | 2024-01-16 | Insilio                | W   | 0.465      | -            | -                | -                | -         |     3.01 | casey, Flayy, kisserek, olimp, sNx      |
|            6 |     5047 | 2024-01-10 | The Prodigies          | L   | 0.426      | -            | -                | -                | -         |   -12.87 | casey, Flayy, kisserek, olimp, sNx      |
|            5 |     6393 | 2023-11-26 | ENCE                   | W   | 0.125      | 0.143        | 0.377 (0.007)    | -                | -         |     3.51 | Goofy, hades, jcobbb, KEi, Kylar        |
|            4 |     6431 | 2023-11-25 | ENTERPRISE esports     | W   | 0.118      | -            | -                | -                | -         |     0.84 | Flayy, kisserek, moonwalk, olimp, sNx   |
|            3 |     6512 | 2023-11-23 | Turów Zgorzelec Esport | W   | 0.105      | -            | -                | -                | -         |     0.41 | Flayy, kisserek, moonwalk, olimp, sNx   |
|            2 |     6592 | 2023-11-21 | KOMNATA                | W   | 0.092      | -            | -                | -                | -         |     0.04 | eltrzzi, hypex, kirbie, misho, pendzel  |
|            1 |     6634 | 2023-11-20 | Ex-Anonymo Esports     | L   | 0.085      | -            | -                | -                | -         |    -2.43 | Flayy, kisserek, moonwalk, olimp, sNx   |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($19,160.38)
- Divide that value by the 5th highest value among all rosters ($158,437.64)
- The final value (0.12) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-04-28 |      1.000 | $10,000.00     | $10,000.00      |
| 2024-04-20 |      1.000 | $2,000.00      | $2,000.00       |
| 2024-02-11 |      0.638 | $10,000.00     | $6,380.09       |
| 2023-11-26 |      0.125 | $6,258.53      | $780.29         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
