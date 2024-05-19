### Roster Details<br />
Team Name: Team Solid<br />
Roster: ALLE, CSO, gbb, Lcm, xureba<br />
Region: [Americas]( ../standings_americas.md)<br />
<br />
Global Rank: [131](../standings_global.md)<br />
Regional Rank: [23]( ../standings_americas.md)<br />
Final Rank Value:  803.2<br />
<br />
Final Rank Value (803.2) = Starting Rank Value (891.8) + Head To Head Adjustments (-88.6)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.538[<sup>1</sup>](#table2)
- Bounty Collected: 0.364[<sup>2</sup>](#table1)
- Opponent Network: 0.090[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.248<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 891.8
- 400 + ( ( 0.248 - 0.000 ) / ( 0.806 - 0.000 ) ) * 1600 = 891.8


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent                  | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                       |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           51 |      919 | 2024-04-17 | Fluxo                     | L   | 1.000      | -            | -                | -                | -         |    -6.19 | ALLE, CSO, gbb, Lcm, xureba  |
|           50 |     1145 | 2024-04-12 | ODDIK                     | L   | 1.000      | -            | -                | -                | -         |   -13.10 | ALLE, CSO, gbb, Lcm, xureba  |
|           49 |     1337 | 2024-04-08 | LA RUGONETA               | W   | 1.000      | 0.435        | -                | 0.096 (0.042)    | 0 (0.000) |     6.59 | ALLE, CSO, gbb, Lcm, xureba  |
|           48 |     1388 | 2024-04-06 | Fluxo                     | L   | 1.000      | -            | -                | -                | -         |    -7.03 | ALLE, CSO, gbb, Lcm, xureba  |
|           47 |     2010 | 2024-03-20 | 2Game Esports             | L   | 0.893      | -            | -                | -                | -         |   -21.82 | ALLE, CSO, gbb, Lcm, xureba  |
|           46 |     2014 | 2024-03-20 | 2Game Esports             | W   | 0.893      | 0.450        | -                | 0.188 (0.076)    | 0 (0.000) |     5.97 | ALLE, CSO, gbb, Lcm, xureba  |
|           45 |     2253 | 2024-03-14 | RED Canids                | W   | 0.852      | 0.435        | 0.108 (0.040)    | 0.532 (0.197)    | 0 (0.000) |    18.57 | bnc, CSO, gbb, Lcm, xureba   |
|           44 |     2321 | 2024-03-13 | Fluxo                     | W   | 0.845      | 0.435        | 0.153 (0.056)    | 0.484 (0.178)    | 0 (0.000) |    20.57 | bnc, CSO, gbb, Lcm, xureba   |
|           43 |     2369 | 2024-03-12 | FURIA Academy             | L   | 0.839      | -            | -                | -                | -         |   -20.87 | bnc, CSO, gbb, Lcm, xureba   |
|           42 |     2454 | 2024-03-10 | ODDIK                     | L   | 0.825      | -            | -                | -                | -         |   -10.61 | bnc, CSO, gbb, Lcm, xureba   |
|           41 |     2492 | 2024-03-09 | VELOX Argentina           | W   | 0.818      | 0.435        | 0.002 (0.001)    | 0.030 (0.011)    | 0 (0.000) |     6.14 | bnc, CSO, gbb, Lcm, xureba   |
|           40 |     2597 | 2024-03-06 | Fluxo                     | W   | 0.800      | 0.450        | 0.153 (0.055)    | 0.484 (0.174)    | 0 (0.000) |    19.38 | ALLE, CSO, gbb, Lcm, xureba  |
|           39 |     2598 | 2024-03-06 | Fluxo                     | L   | 0.800      | -            | -                | -                | -         |    -5.61 | ALLE, CSO, gbb, Lcm, xureba  |
|           38 |     2680 | 2024-03-05 | Sharks Esports            | L   | 0.792      | -            | -                | -                | -         |    -8.46 | ALLE, CSO, gbb, Lcm, xureba  |
|           37 |     2689 | 2024-03-05 | Sharks Esports            | L   | 0.792      | -            | -                | -                | -         |    -9.01 | ALLE, CSO, gbb, Lcm, xureba  |
|           36 |     3271 | 2024-02-21 | Case Esports              | L   | 0.707      | -            | -                | -                | -         |   -11.72 | ALLE, CSO, gbb, Lcm, xureba  |
|           35 |     3278 | 2024-02-21 | Case Esports              | W   | 0.707      | 0.450        | 0.027 (0.009)    | 0.401 (0.128)    | 0 (0.000) |    10.73 | ALLE, CSO, gbb, Lcm, xureba  |
|           34 |     3298 | 2024-02-21 | Fluxo                     | L   | 0.705      | -            | -                | -                | -         |    -6.24 | bnc, CSO, gbb, Lcm, xureba   |
|           33 |     3333 | 2024-02-20 | 9z Team                   | L   | 0.700      | -            | -                | -                | -         |    -6.79 | bnc, CSO, gbb, Lcm, xureba   |
|           32 |     3335 | 2024-02-20 | Flamengo Esports          | W   | 0.700      | 0.143        | -                | 0.101 (0.010)    | 0 (0.000) |     4.04 | bnc, CSO, gbb, Lcm, xureba   |
|           31 |     3339 | 2024-02-20 | Fluxo                     | W   | 0.699      | 0.143        | 0.153 (0.015)    | 0.484 (0.048)    | 0 (0.000) |    16.18 | bnc, CSO, gbb, Lcm, xureba   |
|           30 |     3391 | 2024-02-19 | VELOX Argentina           | W   | 0.694      | -            | -                | -                | 0 (0.000) |     5.62 | bnc, CSO, gbb, Lcm, xureba   |
|           29 |     3406 | 2024-02-19 | Sharks Esports            | L   | 0.692      | -            | -                | -                | -         |    -8.81 | bnc, CSO, gbb, Lcm, xureba   |
|           28 |     3660 | 2024-02-13 | AdalYamigos               | L   | 0.654      | -            | -                | -                | -         |   -12.44 | ALLE, CSO, gbb, Lcm, xureba  |
|           27 |     3662 | 2024-02-13 | AdalYamigos               | L   | 0.653      | -            | -                | -                | -         |   -13.13 | ALLE, CSO, gbb, Lcm, xureba  |
|           26 |     4881 | 2024-01-13 | ODDIK                     | L   | 0.447      | -            | -                | -                | -         |    -6.15 | CSO, gbb, Lcm, nolkz, xureba |
|           25 |     4992 | 2024-01-11 | KRÜ Esports               | L   | 0.432      | -            | -                | -                | -         |    -9.73 | CSO, gbb, Lcm, nolkz, xureba |
|           24 |     5027 | 2024-01-10 | Os Guri da Net            | W   | 0.427      | -            | -                | -                | -         |     0.91 | CSO, gbb, Lcm, nolkz, xureba |
|           23 |     5144 | 2024-01-08 | O Plano                   | L   | 0.414      | -            | -                | -                | -         |   -11.43 | CSO, gbb, Lcm, nolkz, xureba |
|           22 |     5272 | 2023-12-23 | Case Esports              | L   | 0.304      | -            | -                | -                | -         |    -6.76 | CSO, gbb, Lcm, nolkz, xureba |
|           21 |     5294 | 2023-12-21 | ODDIK                     | L   | 0.293      | -            | -                | -                | -         |    -4.42 | CSO, gbb, Lcm, nolkz, xureba |
|           20 |     5325 | 2023-12-18 | ODDIK                     | W   | 0.273      | 0.303        | 0.015 (0.001)    | 0.402 (0.033)    | -         |     4.51 | CSO, gbb, Lcm, nolkz, xureba |
|           19 |     5338 | 2023-12-17 | Case Esports              | W   | 0.267      | 0.262        | 0.010 (0.001)    | -                | -         |     2.53 | CSO, gbb, Lcm, nolkz, xureba |
|           18 |     5437 | 2023-12-16 | WINDINGO                  | L   | 0.259      | -            | -                | -                | -         |    -6.44 | CSO, gbb, Lcm, nolkz, xureba |
|           17 |     5630 | 2023-12-13 | W7m esports               | L   | 0.240      | -            | -                | -                | -         |    -6.34 | CSO, gbb, Lcm, nolkz, xureba |
|           16 |     5633 | 2023-12-13 | WINDINGO                  | W   | 0.239      | -            | -                | -                | -         |     1.53 | CSO, gbb, Lcm, nolkz, xureba |
|           15 |     5668 | 2023-12-12 | Arena Jogue Fácil Esports | W   | 0.232      | -            | -                | -                | -         |     1.69 | CSO, gbb, Lcm, nolkz, xureba |
|           14 |     5827 | 2023-12-08 | Age Sports                | W   | 0.206      | -            | -                | -                | -         |     0.39 | CSO, gbb, Lcm, nolkz, xureba |
|           13 |     5917 | 2023-12-06 | Arena Jogue Fácil Esports | W   | 0.194      | -            | -                | -                | -         |     1.38 | CSO, gbb, Lcm, nolkz, xureba |
|           12 |     5963 | 2023-12-05 | Case Esports              | W   | 0.186      | 0.262        | 0.010 (0.000)    | -                | -         |     1.65 | CSO, gbb, Lcm, nolkz, xureba |
|           11 |     6083 | 2023-12-02 | Case Esports              | L   | 0.166      | -            | -                | -                | -         |    -3.79 | CSO, gbb, Lcm, nolkz, xureba |
|           10 |     6186 | 2023-11-30 | Arena Jogue Fácil Esports | L   | 0.153      | -            | -                | -                | -         |    -3.83 | CSO, gbb, Lcm, nolkz, xureba |
|            9 |     6190 | 2023-11-30 | Age Sports                | W   | 0.153      | -            | -                | -                | -         |     0.28 | CSO, gbb, Lcm, nolkz, xureba |
|            8 |     6233 | 2023-11-29 | Dusty Roots               | W   | 0.147      | -            | -                | -                | -         |     1.11 | CSO, gbb, Lcm, nolkz, xureba |
|            7 |     6307 | 2023-11-28 | Patins da Ferrari         | W   | 0.139      | -            | -                | -                | -         |     0.76 | CSO, gbb, Lcm, nolkz, xureba |
|            6 |     6537 | 2023-11-22 | Case Esports              | W   | 0.101      | -            | -                | -                | -         |     0.85 | CSO, gbb, Lcm, nolkz, xureba |
|            5 |     6580 | 2023-11-21 | WINDINGO                  | W   | 0.093      | -            | -                | -                | -         |     0.63 | CSO, gbb, Lcm, nolkz, xureba |
|            4 |     6694 | 2023-11-18 | Galorys                   | W   | 0.073      | 0.143        | 0.048 (0.001)    | -                | -         |     1.09 | CSO, gbb, Lcm, nolkz, xureba |
|            3 |     6861 | 2023-11-15 | Sharks Esports            | L   | 0.053      | -            | -                | -                | -         |    -0.83 | CSO, gbb, Lcm, nolkz, xureba |
|            2 |     7158 | 2023-11-08 | W7m esports               | L   | 0.007      | -            | -                | -                | -         |    -0.18 | CSO, gbb, Lcm, nolkz, xureba |
|            1 |     7160 | 2023-11-08 | Arena Jogue Fácil Esports | W   | 0.006      | -            | -                | -                | -         |     0.04 | CSO, gbb, Lcm, nolkz, xureba |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($21,939.37)
- Divide that value by the 5th highest value among all rosters ($158,437.64)
- The final value (0.14) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-03-14 |      0.852 | $25,000.00     | $21,311.34      |
| 2023-12-17 |      0.267 | $1,000.00      | $266.76         |
| 2023-12-16 |      0.259 | $1,089.86      | $282.71         |
| 2023-12-03 |      0.172 | $457.03        | $78.56          |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
