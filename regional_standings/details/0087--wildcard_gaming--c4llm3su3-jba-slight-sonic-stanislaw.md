### Roster Details<br />
Team Name: Wildcard Gaming<br />
Roster: C4LLM3SU3, JBa, SLIGHT, Sonic, stanislaw<br />
Region: [Americas]( ../standings_americas.md)<br />
<br />
Global Rank: [87](../standings_global.md)<br />
Regional Rank: [14]( ../standings_americas.md)<br />
Final Rank Value:  880.8<br />
<br />
Final Rank Value (880.8) = Starting Rank Value (849.8) + Head To Head Adjustments (31.0)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.385[<sup>1</sup>](#table2)
- Bounty Collected: 0.323[<sup>2</sup>](#table1)
- Opponent Network: 0.113[<sup>2</sup>](#table1)
- LAN Wins: 0.086[<sup>2</sup>](#table1)

The average of these factors is 0.227<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 849.8
- 400 + ( ( 0.227 - 0.000 ) / ( 0.806 - 0.000 ) ) * 1600 = 849.8


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent                   | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins      | H2H Adj. | Roster                                   |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           47 |      128 | 2024-05-02 | Party Astronauts           | W   | 1.000      | 0.477        | 0.036 (0.017)    | 0.374 (0.178)    | false (0.000) |    15.70 | C4LLM3SU3, JBa, SLIGHT, Sonic, stanislaw |
|           46 |      129 | 2024-05-02 | Party Astronauts           | L   | 1.000      | -            | -                | -                | -             |   -15.80 | C4LLM3SU3, JBa, SLIGHT, Sonic, stanislaw |
|           45 |      455 | 2024-04-25 | NRG                        | W   | 1.000      | 0.477        | -                | 0.303 (0.145)    | false (0.000) |    11.18 | C4LLM3SU3, JBa, SLIGHT, Sonic, stanislaw |
|           44 |      457 | 2024-04-25 | NRG                        | L   | 1.000      | -            | -                | -                | -             |   -20.72 | C4LLM3SU3, JBa, SLIGHT, Sonic, stanislaw |
|           43 |      553 | 2024-04-23 | Elevate                    | W   | 1.000      | 0.477        | 0.030 (0.014)    | 0.268 (0.128)    | false (0.000) |    13.49 | C4LLM3SU3, JBa, SLIGHT, Sonic, stanislaw |
|           42 |      558 | 2024-04-23 | Elevate                    | L   | 1.000      | -            | -                | -                | -             |   -18.22 | C4LLM3SU3, JBa, SLIGHT, Sonic, stanislaw |
|           41 |      917 | 2024-04-17 | Elevate                    | L   | 1.000      | -            | -                | -                | -             |   -20.29 | C4LLM3SU3, JBa, SLIGHT, Sonic, stanislaw |
|           40 |      989 | 2024-04-16 | Snakes Den Gaming          | W   | 1.000      | -            | -                | -                | false (0.000) |     1.66 | C4LLM3SU3, JBa, SLIGHT, Sonic, stanislaw |
|           39 |     1315 | 2024-04-08 | Cloud9                     | L   | 1.000      | -            | -                | -                | -             |    -0.31 | horvy, motm, SLIGHT, Sonic, stanislaw    |
|           38 |     1355 | 2024-04-08 | Virtus.pro                 | L   | 1.000      | -            | -                | -                | -             |    -0.35 | horvy, motm, SLIGHT, Sonic, stanislaw    |
|           37 |     1716 | 2024-03-27 | Mythic                     | W   | 0.941      | 0.477        | 0.003 (0.001)    | 0.380 (0.171)    | false (0.000) |     7.72 | C4LLM3SU3, JBa, SLIGHT, Sonic, stanislaw |
|           36 |     1720 | 2024-03-27 | Mythic                     | W   | 0.940      | 0.477        | -                | 0.380 (0.171)    | false (0.000) |     8.24 | C4LLM3SU3, JBa, SLIGHT, Sonic, stanislaw |
|           35 |     1781 | 2024-03-26 | LAG Gaming (American team) | W   | 0.934      | 0.477        | 0.033 (0.015)    | 0.405 (0.180)    | false (0.000) |    15.30 | C4LLM3SU3, JBa, SLIGHT, Sonic, stanislaw |
|           34 |     1785 | 2024-03-26 | LAG Gaming (American team) | L   | 0.934      | -            | -                | -                | -             |   -14.17 | C4LLM3SU3, JBa, SLIGHT, Sonic, stanislaw |
|           33 |     2351 | 2024-03-12 | Mythic                     | L   | 0.840      | -            | -                | -                | -             |   -19.63 | Infinite, JBa, SLIGHT, Sonic, stanislaw  |
|           32 |     2357 | 2024-03-12 | FPL Friends                | W   | 0.840      | -            | -                | -                | false (0.000) |     1.39 | Infinite, JBa, SLIGHT, Sonic, stanislaw  |
|           31 |     2803 | 2024-03-03 | M80                        | L   | 0.778      | -            | -                | -                | -             |    -2.93 | Infinite, JBa, SLIGHT, Sonic, stanislaw  |
|           30 |     2869 | 2024-03-02 | BESTIA                     | W   | 0.772      | 0.143        | 0.026 (0.003)    | 0.423 (0.047)    | true (0.772)  |     9.70 | Infinite, JBa, SLIGHT, Sonic, stanislaw  |
|           29 |     2905 | 2024-03-01 | RED Canids                 | L   | 0.766      | -            | -                | -                | -             |   -10.63 | Infinite, JBa, SLIGHT, Sonic, stanislaw  |
|           28 |     3087 | 2024-02-25 | Team Liquid                | L   | 0.734      | -            | -                | -                | -             |    -1.64 | Infinite, JBa, SLIGHT, Sonic, stanislaw  |
|           27 |     3090 | 2024-02-25 | BOSS                       | L   | 0.733      | -            | -                | -                | -             |   -12.62 | Infinite, JBa, SLIGHT, Sonic, stanislaw  |
|           26 |     3117 | 2024-02-24 | Party Astronauts           | W   | 0.727      | 0.143        | 0.036 (0.004)    | 0.374 (0.039)    | false (0.000) |     8.61 | Infinite, JBa, SLIGHT, Sonic, stanislaw  |
|           25 |     3124 | 2024-02-24 | G3 (Asian team)            | W   | 0.727      | 0.143        | 0.014 (0.001)    | -                | -             |     6.12 | Infinite, JBa, SLIGHT, Sonic, stanislaw  |
|           24 |     3193 | 2024-02-23 | MIGHT                      | W   | 0.721      | -            | -                | -                | -             |     6.41 | Infinite, JBa, SLIGHT, Sonic, stanislaw  |
|           23 |     3274 | 2024-02-21 | Xmplfy                     | W   | 0.707      | -            | -                | -                | -             |     1.19 | Infinite, JBa, motm, SLIGHT, stanislaw   |
|           22 |     3941 | 2024-02-03 | Nouns Esports              | W   | 0.587      | 0.143        | -                | 0.475 (0.040)    | -             |     4.11 | Infinite, JBa, motm, SLIGHT, stanislaw   |
|           21 |     4009 | 2024-02-02 | Carpe Diem                 | W   | 0.579      | -            | -                | -                | -             |     4.24 | Infinite, JBa, SLIGHT, Sonic, stanislaw  |
|           20 |     4372 | 2024-01-24 | One More Esports           | W   | 0.520      | -            | -                | -                | -             |     4.45 | Infinite, JBa, SLIGHT, Sonic, stanislaw  |
|           19 |     4413 | 2024-01-23 | MIGHT                      | W   | 0.515      | -            | -                | -                | -             |     4.90 | Infinite, JBa, SLIGHT, Sonic, stanislaw  |
|           18 |     4418 | 2024-01-23 | The Nomads                 | W   | 0.514      | -            | -                | -                | -             |     0.96 | Infinite, JBa, SLIGHT, Sonic, stanislaw  |
|           17 |     4529 | 2024-01-20 | M80                        | L   | 0.493      | -            | -                | -                | -             |    -1.61 | Infinite, JBa, SLIGHT, Sonic, stanislaw  |
|           16 |     4583 | 2024-01-19 | Team Liquid                | L   | 0.488      | -            | -                | -                | -             |    -0.93 | Infinite, JBa, SLIGHT, Sonic, stanislaw  |
|           15 |     4590 | 2024-01-19 | M80                        | W   | 0.486      | 0.143        | 0.155 (0.011)    | -                | -             |    13.87 | Infinite, JBa, SLIGHT, Sonic, stanislaw  |
|           14 |     4634 | 2024-01-18 | Nouns Esports              | W   | 0.481      | 0.143        | -                | 0.475 (0.033)    | -             |     3.49 | Infinite, JBa, SLIGHT, Sonic, stanislaw  |
|           13 |     4639 | 2024-01-18 | MIGHT                      | W   | 0.480      | -            | -                | -                | -             |     4.98 | Infinite, JBa, SLIGHT, Sonic, stanislaw  |
|           12 |     4685 | 2024-01-17 | Mythic                     | W   | 0.474      | -            | -                | -                | -             |     4.26 | Infinite, JBa, SLIGHT, Sonic, stanislaw  |
|           11 |     4772 | 2024-01-16 | Team Liquid                | L   | 0.467      | -            | -                | -                | -             |    -0.79 | Infinite, JBa, SLIGHT, Sonic, stanislaw  |
|           10 |     4824 | 2024-01-15 | CatEvil                    | W   | 0.460      | -            | -                | -                | -             |     3.01 | Infinite, JBa, SLIGHT, Sonic, stanislaw  |
|            9 |     4873 | 2024-01-13 | M80                        | W   | 0.447      | 0.143        | 0.155 (0.010)    | -                | -             |    13.01 | Infinite, JBa, SLIGHT, Sonic, stanislaw  |
|            8 |     4910 | 2024-01-12 | BOSS                       | W   | 0.442      | 0.143        | 0.051 (0.003)    | -                | -             |     8.08 | Infinite, JBa, SLIGHT, Sonic, stanislaw  |
|            7 |     5423 | 2023-12-16 | FPL Friends                | L   | 0.261      | -            | -                | -                | -             |    -6.06 | Infinite, JBa, SLIGHT, Sonic, stanislaw  |
|            6 |     5427 | 2023-12-16 | Tsunami Esports            | W   | 0.260      | -            | -                | -                | -             |     0.61 | Infinite, JBa, SLIGHT, Sonic, stanislaw  |
|            5 |     6074 | 2023-12-02 | M80                        | L   | 0.167      | -            | -                | -                | -             |    -0.40 | CLASIA, Infinite, JBa, SLIGHT, stanislaw |
|            4 |     6078 | 2023-12-02 | Gifted Moments             | W   | 0.167      | -            | -                | -                | -             |     0.39 | CLASIA, Infinite, JBa, SLIGHT, stanislaw |
|            3 |     6906 | 2023-11-14 | Limitless                  | W   | 0.047      | -            | -                | -                | -             |     0.42 | Infinite, JBa, SLIGHT, Sonic, stanislaw  |
|            2 |     6908 | 2023-11-14 | Carpe Diem                 | W   | 0.047      | -            | -                | -                | -             |     0.49 | Infinite, JBa, SLIGHT, Sonic, stanislaw  |
|            1 |     6947 | 2023-11-13 | Tsunami Esports            | W   | 0.041      | -            | -                | -                | -             |     0.10 | Infinite, JBa, SLIGHT, Sonic, stanislaw  |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($4,000.00)
- Divide that value by the 5th highest value among all rosters ($158,437.64)
- The final value (0.03) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
