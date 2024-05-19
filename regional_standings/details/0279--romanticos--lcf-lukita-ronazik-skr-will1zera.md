### Roster Details<br />
Team Name: Romanticos<br />
Roster: lcf, Lukita, ronazik, Skr, will1ZERA<br />
Region: [Americas]( ../standings_americas.md)<br />
<br />
Global Rank: [279](../standings_global.md)<br />
Regional Rank: [59]( ../standings_americas.md)<br />
Final Rank Value:  631.7<br />
<br />
Final Rank Value (631.7) = Starting Rank Value (665.7) + Head To Head Adjustments (-34.0)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.284[<sup>1</sup>](#table2)
- Bounty Collected: 0.238[<sup>2</sup>](#table1)
- Opponent Network: 0.014[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.134<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 665.7
- 400 + ( ( 0.134 - 0.000 ) / ( 0.806 - 0.000 ) ) * 1600 = 665.7


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent                     | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins      | H2H Adj. | Roster                                     |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           23 |     1130 | 2024-04-12 | Looking4Org (Brazilian team) | L   | 1.000      | -            | -                | -                | -             |   -14.68 | lcf, Lukita, ronazik, Skr, will1ZERA       |
|           22 |     1660 | 2024-03-29 | Yawara E-Sports              | L   | 0.952      | -            | -                | -                | -             |   -11.41 | Lukita, ronazik, Skr, Tatu, will1ZERA      |
|           21 |     1732 | 2024-03-27 | MIBR Academy                 | L   | 0.939      | -            | -                | -                | -             |   -12.08 | Lukita, ronazik, Skr, Tatu, will1ZERA      |
|           20 |     1797 | 2024-03-26 | 9z Academy                   | W   | 0.932      | 0.143        | 0.003 (0.000)    | 0.237 (0.032)    | false (0.000) |    12.81 | Lukita, ronazik, Skr, Tatu, will1ZERA      |
|           19 |     1933 | 2024-03-22 | Yawara E-Sports              | L   | 0.906      | -            | -                | -                | -             |   -12.54 | Lukita, ronazik, Skr, Tatu, will1ZERA      |
|           18 |     2006 | 2024-03-20 | NIGERIA 96                   | W   | 0.894      | 0.143        | 0.002 (0.000)    | 0.095 (0.012)    | false (0.000) |    12.72 | Lukita, ronazik, Skr, Tatu, will1ZERA      |
|           17 |     2210 | 2024-03-15 | Bounty Hunters Esports       | L   | 0.859      | -            | -                | -                | -             |   -17.64 | Lukita, ronazik, Skr, Tatu, will1ZERA      |
|           16 |     2259 | 2024-03-14 | LA RUGONETA                  | W   | 0.852      | 0.262        | 0.000 (0.000)    | 0.096 (0.021)    | false (0.000) |    10.73 | Lukita, ronazik, Skr, Tatu, will1ZERA      |
|           15 |     2718 | 2024-03-04 | MIBR Academy                 | L   | 0.786      | -            | -                | -                | -             |    -9.05 | Lukita, ronazik, Skr, Tatu, will1ZERA      |
|           14 |     2865 | 2024-03-02 | Bombril 1001 Utilidades      | L   | 0.772      | -            | -                | -                | -             |   -11.91 | Lukita, ronazik, Skr, Tatu, will1ZERA      |
|           13 |     2929 | 2024-02-29 | 9z Academy                   | W   | 0.760      | 0.143        | 0.003 (0.000)    | 0.237 (0.026)    | false (0.000) |    10.78 | Lukita, ronazik, Skr, Tatu, will1ZERA      |
|           12 |     3016 | 2024-02-27 | MIBR Academy                 | L   | 0.746      | -            | -                | -                | -             |    -9.32 | Lukita, ronazik, Skr, Tatu, will1ZERA      |
|           11 |     4131 | 2024-01-30 | Yawara E-Sports              | L   | 0.560      | -            | -                | -                | -             |    -7.79 | Lukita, ronazik, Skr, Tatu, will1ZERA      |
|           10 |     4205 | 2024-01-28 | ODDIK Academy                | W   | 0.546      | 0.143        | 0.002 (0.000)    | 0.160 (0.012)    | false (0.000) |     7.88 | Lukita, ronazik, Skr, Tatu, will1ZERA      |
|            9 |     4236 | 2024-01-27 | TEAM ORUGA                   | W   | 0.540      | 0.143        | 0.001 (0.000)    | 0.108 (0.008)    | false (0.000) |     6.70 | gAtito, kissmyaug, pegin, rushardo, zLN    |
|            8 |     4251 | 2024-01-27 | Myth e-Sports                | W   | 0.539      | 0.143        | 0.000 (0.000)    | 0.070 (0.005)    | false (0.000) |     7.46 | crownzera, Farw, hellzaoo, MyRoN, nz1      |
|            7 |     4254 | 2024-01-27 | Yawara E-Sports              | L   | 0.539      | -            | -                | -                | -             |    -7.39 | j0w, lash, PremiuM, ritz, stAx             |
|            6 |     4261 | 2024-01-27 | Fluxo Demons                 | W   | 0.539      | 0.143        | 0.065 (0.005)    | 0.289 (0.022)    | false (0.000) |    13.85 | goddess, julih, nani, poppins, yungher     |
|            5 |     5439 | 2023-12-16 | Vex Dragons                  | L   | 0.259      | -            | -                | -                | -             |    -4.97 | Lukita, ronazik, Skr, Tatu, will1ZERA      |
|            4 |     5445 | 2023-12-16 | Looking4Org (Brazilian team) | W   | 0.259      | 0.143        | -                | 0.009 (0.000)    | false (0.000) |     1.51 | firstzera, Lukz, s1lent, Sorvet3, tormento |
|            3 |     6189 | 2023-11-30 | PAQ Gaming                   | W   | 0.153      | 0.143        | 0.000 (0.000)    | 0.000 (0.000)    | false (0.000) |     1.41 | aNgelo, bin96, bks, Black, JLK             |
|            2 |     6259 | 2023-11-29 | 9z Academy                   | L   | 0.145      | -            | -                | -                | -             |    -2.33 | divine, MaxOff, perez, slashzz, Tomate     |
|            1 |     6292 | 2023-11-28 | PAQ Gaming                   | W   | 0.140      | 0.143        | 0.000 (0.000)    | -                | -             |     1.29 | aNgelo, bin96, bks, Black, JLK             |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($474.11)
- Divide that value by the 5th highest value among all rosters ($158,437.64)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-03-31 |      0.967 | $130.39        | $126.05         |
| 2024-03-06 |      0.799 | $131.09        | $104.72         |
| 2024-01-30 |      0.560 | $323.13        | $180.85         |
| 2023-11-30 |      0.153 | $407.67        | $62.49          |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
