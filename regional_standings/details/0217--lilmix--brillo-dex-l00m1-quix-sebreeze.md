### Roster Details<br />
Team Name: Lilmix<br />
Roster: Brillo, dex, L00m1, quix, SeBreeZe<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [217](../standings_global.md)<br />
Regional Rank: [143]( ../standings_europe.md)<br />
Final Rank Value:  697.4<br />
<br />
Final Rank Value (697.4) = Starting Rank Value (708.9) + Head To Head Adjustments (-11.5)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.208[<sup>1</sup>](#table2)
- Bounty Collected: 0.264[<sup>2</sup>](#table1)
- Opponent Network: 0.020[<sup>2</sup>](#table1)
- LAN Wins: 0.131[<sup>2</sup>](#table1)

The average of these factors is 0.156<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 708.9
- 400 + ( ( 0.156 - 0.000 ) / ( 0.806 - 0.000 ) ) * 1600 = 708.9


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent            | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins      | H2H Adj. | Roster                                 |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           32 |     4743 | 2024-01-17 | Copenhagen Wolves   | L   | 0.472      | -            | -                | -                | -             |    -8.79 | Brillo, dex, L00m1, quix, SeBreeZe     |
|           31 |     4938 | 2024-01-12 | Permitta Esports    | L   | 0.439      | -            | -                | -                | -             |    -2.36 | Brillo, dex, L00m1, quix, SeBreeZe     |
|           30 |     4949 | 2024-01-12 | Permitta Esports    | L   | 0.437      | -            | -                | -                | -             |    -2.40 | Brillo, dex, L00m1, quix, SeBreeZe     |
|           29 |     4996 | 2024-01-11 | ALTERNATE aTTaX     | W   | 0.431      | 0.143        | 0.110 (0.007)    | 0.723 (0.045)    | true (0.431)  |    12.04 | Brillo, dex, L00m1, quix, SeBreeZe     |
|           28 |     5000 | 2024-01-11 | Momenta             | W   | 0.431      | 0.143        | 0.000 (0.000)    | 0.013 (0.001)    | true (0.431)  |     2.22 | Brillo, dex, L00m1, quix, SeBreeZe     |
|           27 |     5010 | 2024-01-11 | Team Spirit Academy | L   | 0.430      | -            | -                | -                | -             |    -4.51 | Brillo, dex, L00m1, quix, SeBreeZe     |
|           26 |     5115 | 2024-01-09 | Ex-Anonymo Esports  | L   | 0.418      | -            | -                | -                | -             |    -4.93 | Brillo, dex, L00m1, quix, SeBreeZe     |
|           25 |     5167 | 2024-01-07 | Permitta Esports    | W   | 0.403      | 0.333        | 0.063 (0.008)    | 1.000 (0.134)    | false (0.000) |    10.71 | Brillo, dex, L00m1, quix, SeBreeZe     |
|           24 |     5179 | 2024-01-06 | ROSOMAHA            | L   | 0.397      | -            | -                | -                | -             |    -7.81 | Brillo, dex, L00m1, quix, treckiz      |
|           23 |     5205 | 2024-01-03 | Begrip Gaming       | W   | 0.379      | 0.143        | 0.001 (0.000)    | 0.196 (0.011)    | false (0.000) |     5.14 | Brillo, Chawzyyy, dex, L00m1, quix     |
|           22 |     5212 | 2024-01-03 | RawkAndRawl         | W   | 0.379      | 0.143        | 0.000 (0.000)    | 0.013 (0.001)    | false (0.000) |     1.97 | Brillo, Chawzyyy, dex, L00m1, quix     |
|           21 |     5351 | 2023-12-17 | Metizport           | L   | 0.265      | -            | -                | -                | -             |    -1.24 | Brillo, dex, L00m1, quix, SeBreeZe     |
|           20 |     5365 | 2023-12-17 | Alliance            | L   | 0.264      | -            | -                | -                | -             |    -2.17 | Brillo, dex, L00m1, quix, SeBreeZe     |
|           19 |     5383 | 2023-12-17 | Uruguay3            | W   | 0.263      | 0.143        | 0.000 (0.000)    | -                | true (0.263)  |     1.33 | Brillo, dex, L00m1, quix, SeBreeZe     |
|           18 |     5641 | 2023-12-13 | Kappa Bar           | L   | 0.239      | -            | -                | -                | -             |    -3.98 | Brillo, dex, L00m1, quix, SeBreeZe     |
|           17 |     5646 | 2023-12-13 | G-Units             | W   | 0.239      | 0.143        | -                | 0.009 (0.000)    | false (0.000) |     1.16 | Brillo, dex, L00m1, quix, SeBreeZe     |
|           16 |     6198 | 2023-11-30 | ARCRED              | L   | 0.152      | -            | -                | -                | -             |    -1.57 | dex, L00m1, melonhead, quix, SeBreeZe  |
|           15 |     6313 | 2023-11-28 | TY                  | L   | 0.138      | -            | -                | -                | -             |    -2.23 | dex, L00m1, melonhead, quix, SeBreeZe  |
|           14 |     6362 | 2023-11-27 | V1dar Gaming        | L   | 0.132      | -            | -                | -                | -             |    -2.76 | dex, L00m1, melonhead, quix, SeBreeZe  |
|           13 |     6513 | 2023-11-23 | TEAM ZOO BAR        | W   | 0.105      | 0.371        | -                | 0.051 (0.002)    | false (0.000) |     0.80 | dex, L00m1, melonhead, quix, SeBreeZe  |
|           12 |     6562 | 2023-11-22 | Kappa Bar           | L   | 0.098      | -            | -                | -                | -             |    -2.03 | dex, L00m1, melonhead, quix, SeBreeZe  |
|           11 |     6593 | 2023-11-21 | For The Win Esports | L   | 0.092      | -            | -                | -                | -             |    -1.58 | dex, L00m1, melonhead, quix, SeBreeZe  |
|           10 |     6667 | 2023-11-19 | Lemondogs           | W   | 0.078      | 0.143        | -                | 0.252 (0.003)    | -             |     0.80 | dex, L00m1, melonhead, quix, SeBreeZe  |
|            9 |     6772 | 2023-11-17 | ENTERPRISE esports  | L   | 0.065      | -            | -                | -                | -             |    -0.42 | dex, L00m1, melonhead, quix, SeBreeZe  |
|            8 |     6961 | 2023-11-13 | Zero Tenacity       | L   | 0.039      | -            | -                | -                | -             |    -0.23 | dex, L00m1, melonhead, quix, SeBreeZe  |
|            7 |     7040 | 2023-11-11 | Alliance            | L   | 0.027      | -            | -                | -                | -             |    -0.23 | L00m1, melonhead, quix, SeBreeZe, susp |
|            6 |     7047 | 2023-11-11 | Metizport           | W   | 0.026      | 0.143        | 0.188 (0.001)    | 1.000 (0.004)    | true (0.026)  |     0.69 | L00m1, melonhead, quix, SeBreeZe, susp |
|            5 |     7056 | 2023-11-11 | GODSENT             | W   | 0.025      | 0.143        | 0.026 (0.000)    | 0.423 (0.001)    | true (0.025)  |     0.49 | L00m1, melonhead, quix, SeBreeZe, susp |
|            4 |     7135 | 2023-11-09 | Kappa Bar           | W   | 0.012      | 0.143        | 0.002 (0.000)    | -                | -             |     0.17 | dex, L00m1, melonhead, quix, SeBreeZe  |
|            3 |     7144 | 2023-11-09 | TSM                 | W   | 0.011      | 0.371        | 0.008 (0.000)    | -                | -             |     0.17 | dex, L00m1, melonhead, quix, SeBreeZe  |
|            2 |     7169 | 2023-11-08 | SHIPACHI            | W   | 0.006      | -            | -                | -                | -             |     0.04 | dex, L00m1, melonhead, quix, SeBreeZe  |
|            1 |     7185 | 2023-11-08 | Curlews             | W   | 0.005      | -            | -                | -                | -             |     0.02 | dex, L00m1, melonhead, quix, SeBreeZe  |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($24.66)
- Divide that value by the 5th highest value among all rosters ($158,437.64)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
