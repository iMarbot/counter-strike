### Roster Details<br />
Team Name: Sensei Team<br />
Roster: antonini, pedrinzy, ph1, proSHOW, prt<br />
Region: [Americas]( ../standings_americas.md)<br />
<br />
Global Rank: [176](../standings_global.md)<br />
Regional Rank: [32]( ../standings_americas.md)<br />
Final Rank Value:  750.0<br />
<br />
Final Rank Value (750.0) = Starting Rank Value (703.0) + Head To Head Adjustments (47.1)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.311[<sup>1</sup>](#table2)
- Bounty Collected: 0.265[<sup>2</sup>](#table1)
- Opponent Network: 0.035[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.153<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 703.0
- 400 + ( ( 0.153 - 0.000 ) / ( 0.806 - 0.000 ) ) * 1600 = 703.0


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent                       | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins      | H2H Adj. | Roster                                |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           19 |      187 | 2024-05-01 | Dusty Roots                    | L   | 1.000      | -            | -                | -                | -             |   -19.65 | antonini, pedrinzy, ph1, proSHOW, prt |
|           18 |      331 | 2024-04-27 | Sharks Youngsters              | W   | 1.000      | 0.143        | 0.004 (0.001)    | 0.211 (0.030)    | false (0.000) |     9.87 | antonini, pedrinzy, ph1, proSHOW, prt |
|           17 |      332 | 2024-04-27 | Smoke Gaming                   | W   | 1.000      | -            | -                | -                | false (0.000) |     9.78 | antonini, pedrinzy, ph1, proSHOW, prt |
|           16 |      334 | 2024-04-27 | FURIA Esports Female           | W   | 1.000      | 0.143        | 0.048 (0.007)    | 0.205 (0.029)    | false (0.000) |    17.24 | antonini, pedrinzy, ph1, proSHOW, prt |
|           15 |      338 | 2024-04-27 | Floripa Stars                  | W   | 1.000      | 0.143        | 0.001 (0.000)    | 0.181 (0.026)    | false (0.000) |    12.98 | antonini, pedrinzy, ph1, proSHOW, prt |
|           14 |      345 | 2024-04-27 | Full House Gaming              | L   | 1.000      | -            | -                | -                | -             |   -19.61 | antonini, pedrinzy, ph1, proSHOW, prt |
|           13 |      353 | 2024-04-27 | United E-sports                | W   | 1.000      | 0.143        | 0.002 (0.000)    | 0.053 (0.008)    | false (0.000) |    11.57 | antonini, pedrinzy, ph1, proSHOW, prt |
|           12 |      400 | 2024-04-26 | Hype E-Sports (Brazilian team) | L   | 1.000      | -            | -                | -                | -             |   -23.78 | antonini, pedrinzy, ph1, proSHOW, prt |
|           11 |      680 | 2024-04-20 | Yawara E-Sports                | W   | 1.000      | 0.143        | 0.005 (0.001)    | 0.361 (0.052)    | false (0.000) |    14.07 | antonini, pedrinzy, ph1, proSHOW, prt |
|           10 |     1030 | 2024-04-15 | 9z Academy                     | W   | 1.000      | 0.143        | 0.003 (0.000)    | 0.237 (0.034)    | false (0.000) |    11.91 | antonini, pedrinzy, ph1, proSHOW, prt |
|            9 |     1095 | 2024-04-13 | ODDIK Academy                  | W   | 1.000      | 0.143        | 0.002 (0.000)    | 0.160 (0.023)    | false (0.000) |    11.72 | antonini, pedrinzy, ph1, proSHOW, prt |
|            8 |     1133 | 2024-04-12 | Smoke Gaming                   | W   | 1.000      | -            | -                | -                | false (0.000) |    11.42 | antonini, pedrinzy, ph1, proSHOW, prt |
|            7 |     1476 | 2024-04-04 | Bounty Hunters Esports         | L   | 0.992      | -            | -                | -                | -             |   -21.18 | antonini, pedrinzy, ph1, proSHOW, prt |
|            6 |     1689 | 2024-03-28 | Intense Game                   | L   | 0.945      | -            | -                | -                | -             |   -14.02 | antonini, pedrinzy, ph1, proSHOW, prt |
|            5 |     1836 | 2024-03-25 | Rocket.GG                      | W   | 0.927      | 0.143        | 0.001 (0.000)    | 0.070 (0.009)    | false (0.000) |    11.15 | antonini, pedrinzy, ph1, proSHOW, prt |
|            4 |     1841 | 2024-03-25 | Yawara E-Sports                | L   | 0.925      | -            | -                | -                | -             |   -14.70 | antonini, pedrinzy, ph1, proSHOW, prt |
|            3 |     1882 | 2024-03-23 | NIGERIA ACADEMY                | W   | 0.913      | -            | -                | -                | -             |     6.23 | antonini, pedrinzy, ph1, proSHOW, prt |
|            2 |     1963 | 2024-03-21 | Galorys                        | W   | 0.899      | 0.143        | 0.048 (0.006)    | 0.598 (0.077)    | -             |    17.46 | antonini, pedrinzy, ph1, proSHOW, prt |
|            1 |     1974 | 2024-03-21 | MIBR Academy                   | W   | 0.899      | 0.143        | 0.011 (0.001)    | 0.455 (0.058)    | -             |    14.60 | antonini, pedrinzy, ph1, proSHOW, prt |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($963.28)
- Divide that value by the 5th highest value among all rosters ($158,437.64)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-05-01 |      1.000 | $481.20        | $481.20         |
| 2024-04-27 |      1.000 | $185.60        | $185.60         |
| 2024-03-25 |      0.927 | $319.85        | $296.47         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
