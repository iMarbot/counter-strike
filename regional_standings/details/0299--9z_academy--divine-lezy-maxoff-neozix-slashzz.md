### Roster Details<br />
Team Name: 9z Academy<br />
Roster: divine, lezy, MaxOff, neozix, slashzz<br />
Region: [Americas]( ../standings_americas.md)<br />
<br />
Global Rank: [299](../standings_global.md)<br />
Regional Rank: [67]( ../standings_americas.md)<br />
Final Rank Value:  613.6<br />
<br />
Final Rank Value (613.6) = Starting Rank Value (660.1) + Head To Head Adjustments (-46.5)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.286[<sup>1</sup>](#table2)
- Bounty Collected: 0.224[<sup>2</sup>](#table1)
- Opponent Network: 0.014[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.131<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 660.1
- 400 + ( ( 0.131 - 0.000 ) / ( 0.806 - 0.000 ) ) * 1600 = 660.1


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent                         | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins      | H2H Adj. | Roster                                 |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           36 |      502 | 2024-04-24 | Hype E-Sports (Brazilian team)   | L   | 1.000      | -            | -                | -                | -             |   -20.01 | divine, lezy, MaxOff, neozix, slashzz  |
|           35 |      556 | 2024-04-23 | LaChampionsLiga                  | W   | 1.000      | 0.143        | -                | 0.070 (0.010)    | false (0.000) |    10.98 | divine, lezy, MaxOff, neozix, slashzz  |
|           34 |      861 | 2024-04-18 | Dusty Roots                      | L   | 1.000      | -            | -                | -                | -             |   -14.20 | divine, lezy, MaxOff, neozix, slashzz  |
|           33 |     1030 | 2024-04-15 | Sensei Team                      | L   | 1.000      | -            | -                | -                | -             |   -11.91 | divine, lezy, MaxOff, neozix, slashzz  |
|           32 |     1094 | 2024-04-13 | Dusty Roots                      | W   | 1.000      | 0.143        | 0.005 (0.001)    | 0.352 (0.050)    | false (0.000) |    15.51 | divine, lezy, MaxOff, neozix, slashzz  |
|           31 |     1131 | 2024-04-12 | ATECUBANOS (2024 Brazilian team) | W   | 1.000      | -            | -                | -                | false (0.000) |     6.71 | divine, lezy, MaxOff, neozix, slashzz  |
|           30 |     1596 | 2024-04-01 | Full House Gaming                | W   | 0.973      | 0.143        | 0.003 (0.000)    | 0.153 (0.021)    | false (0.000) |    16.22 | divine, lezy, MaxOff, neozix, slashzz  |
|           29 |     1797 | 2024-03-26 | Romanticos                       | L   | 0.932      | -            | -                | -                | -             |   -12.81 | divine, MaxOff, neozix, slashzz, wait  |
|           28 |     1837 | 2024-03-25 | Yawara E-Sports                  | L   | 0.926      | -            | -                | -                | -             |   -10.03 | divine, MaxOff, neozix, slashzz, wait  |
|           27 |     1970 | 2024-03-21 | Yawara E-Sports                  | L   | 0.899      | -            | -                | -                | -             |   -11.98 | divine, MaxOff, neozix, slashzz, wait  |
|           26 |     2045 | 2024-03-19 | NIGERIA 96                       | W   | 0.886      | 0.143        | 0.002 (0.000)    | 0.095 (0.012)    | false (0.000) |    14.12 | divine, MaxOff, neozix, slashzz, wait  |
|           25 |     2356 | 2024-03-12 | ODDIK                            | L   | 0.840      | -            | -                | -                | -             |    -4.83 | divine, MaxOff, neozix, slashzz, wait  |
|           24 |     2929 | 2024-02-29 | Romanticos                       | L   | 0.760      | -            | -                | -                | -             |   -10.78 | divine, MaxOff, neozix, slashzz, wait  |
|           23 |     2985 | 2024-02-28 | MIBR Academy                     | L   | 0.752      | -            | -                | -                | -             |    -8.26 | divine, MaxOff, neozix, slashzz, wait  |
|           22 |     3575 | 2024-02-15 | Galorys                          | L   | 0.665      | -            | -                | -                | -             |    -5.76 | divine, MaxOff, neozix, slashzz, wait  |
|           21 |     3665 | 2024-02-13 | Flamengo Esports                 | L   | 0.653      | -            | -                | -                | -             |   -13.74 | divine, MaxOff, neozix, slashzz, wait  |
|           20 |     3874 | 2024-02-05 | MIBR Academy                     | L   | 0.599      | -            | -                | -                | -             |    -7.47 | divine, MaxOff, neozix, slashzz, wait  |
|           19 |     4181 | 2024-01-29 | Yawara E-Sports                  | W   | 0.553      | 0.143        | 0.005 (0.000)    | 0.361 (0.028)    | false (0.000) |    10.19 | divine, MaxOff, neozix, perez, slashzz |
|           18 |     5293 | 2023-12-21 | CEBOLOS                          | W   | 0.294      | 0.143        | 0.001 (0.000)    | 0.048 (0.002)    | false (0.000) |     3.82 | divine, MaxOff, perez, slashzz, Tomate |
|           17 |     5452 | 2023-12-16 | CEBOLOS                          | W   | 0.259      | 0.143        | 0.001 (0.000)    | 0.048 (0.002)    | false (0.000) |     3.36 | divine, MaxOff, perez, slashzz, Tomate |
|           16 |     5459 | 2023-12-16 | Astral Aces Esports              | W   | 0.259      | -            | -                | -                | false (0.000) |     1.53 | divine, MaxOff, perez, slashzz, Tomate |
|           15 |     5473 | 2023-12-16 | Looking4Org (Brazilian team)     | W   | 0.258      | -            | -                | -                | false (0.000) |     1.52 | divine, MaxOff, perez, slashzz, Tomate |
|           14 |     6101 | 2023-12-02 | Arena Jogue Fácil Esports        | L   | 0.165      | -            | -                | -                | -             |    -2.62 | divine, MaxOff, perez, slashzz, Tomate |
|           13 |     6151 | 2023-12-01 | River Plate Gaming               | L   | 0.159      | -            | -                | -                | -             |    -2.87 | divine, MaxOff, perez, slashzz, Tomate |
|           12 |     6184 | 2023-11-30 | CEBOLOS                          | W   | 0.154      | 0.143        | 0.001 (0.000)    | -                | -             |     2.00 | divine, MaxOff, perez, slashzz, Tomate |
|           11 |     6188 | 2023-11-30 | Sharks Esports                   | W   | 0.153      | 0.143        | 0.063 (0.001)    | 0.343 (0.008)    | -             |     3.76 | divine, MaxOff, perez, slashzz, Tomate |
|           10 |     6203 | 2023-11-30 | Corinthians Esports              | L   | 0.152      | -            | -                | -                | -             |    -2.63 | divine, MaxOff, perez, slashzz, Tomate |
|            9 |     6238 | 2023-11-29 | WINDINGO                         | W   | 0.146      | 0.284        | 0.004 (0.000)    | 0.026 (0.001)    | -             |     2.29 | divine, MaxOff, perez, slashzz, Tomate |
|            8 |     6259 | 2023-11-29 | Romanticos                       | W   | 0.145      | 0.143        | 0.003 (0.000)    | 0.185 (0.004)    | -             |     2.33 | divine, MaxOff, perez, slashzz, Tomate |
|            7 |     6293 | 2023-11-28 | Astral Aces Esports              | W   | 0.140      | -            | -                | -                | -             |     0.84 | divine, MaxOff, perez, slashzz, Tomate |
|            6 |     6347 | 2023-11-27 | Dusty Roots                      | L   | 0.133      | -            | -                | -                | -             |    -1.95 | divine, MaxOff, perez, slashzz, Tomate |
|            5 |     7028 | 2023-11-11 | TIMACETA                         | W   | 0.027      | -            | -                | -                | -             |     0.42 | divine, MaxOff, perez, slashzz, Tomate |
|            4 |     7030 | 2023-11-11 | United E-sports                  | L   | 0.027      | -            | -                | -                | -             |    -0.47 | divine, MaxOff, perez, slashzz, Tomate |
|            3 |     7042 | 2023-11-11 | SOLOVE                           | W   | 0.027      | -            | -                | -                | -             |     0.39 | divine, MaxOff, perez, slashzz, Tomate |
|            2 |     7112 | 2023-11-09 | Patins da Ferrari                | L   | 0.014      | -            | -                | -                | -             |    -0.24 | divine, MaxOff, perez, slashzz, Tomate |
|            1 |     7117 | 2023-11-09 | Patrulha Canina                  | W   | 0.013      | -            | -                | -                | -             |     0.08 | divine, MaxOff, perez, slashzz, Tomate |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($506.73)
- Divide that value by the 5th highest value among all rosters ($158,437.64)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-05-01 |      1.000 | $288.72        | $288.72         |
| 2023-12-21 |      0.294 | $610.25        | $179.19         |
| 2023-12-01 |      0.159 | $203.04        | $32.25          |
| 2023-11-11 |      0.027 | $241.08        | $6.56           |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
