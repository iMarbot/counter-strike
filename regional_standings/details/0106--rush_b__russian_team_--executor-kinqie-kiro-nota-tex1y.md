### Roster Details<br />
Team Name: RUSH B (Russian team)<br />
Roster: executoR, kinqie, Kiro, nota, tex1y<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [106](../standings_global.md)<br />
Regional Rank: [78]( ../standings_europe.md)<br />
Final Rank Value:  849.0<br />
<br />
Final Rank Value (849.0) = Starting Rank Value (783.0) + Head To Head Adjustments (65.9)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.313[<sup>1</sup>](#table2)
- Bounty Collected: 0.353[<sup>2</sup>](#table1)
- Opponent Network: 0.105[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.193<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 783.0
- 400 + ( ( 0.193 - 0.000 ) / ( 0.806 - 0.000 ) ) * 1600 = 783.0


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent       | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins      | H2H Adj. | Roster                              |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           34 |       11 | 2024-05-05 | Team Sampi     | L   | 1.000      | -            | -                | -                | -             |    -9.35 | executoR, kinqie, Kiro, nota, tex1y |
|           33 |       59 | 2024-05-04 | HAVU Gaming    | W   | 1.000      | 0.435        | 0.024 (0.010)    | 0.213 (0.093)    | false (0.000) |    11.70 | executoR, kinqie, Kiro, nota, tex1y |
|           32 |      153 | 2024-05-02 | EYEBALLERS     | L   | 1.000      | -            | -                | -                | -             |   -11.62 | executoR, kinqie, Kiro, nota, tex1y |
|           31 |      262 | 2024-04-29 | ENCE Academy   | W   | 1.000      | 0.435        | 0.028 (0.012)    | 0.267 (0.116)    | false (0.000) |    13.71 | executoR, kinqie, Kiro, nota, tex1y |
|           30 |      364 | 2024-04-27 | VP.Prodigy     | W   | 1.000      | 0.143        | 0.029 (0.004)    | 0.762 (0.109)    | false (0.000) |    12.95 | executoR, kinqie, Kiro, nota, tex1y |
|           29 |      686 | 2024-04-20 | Grindas        | L   | 1.000      | -            | -                | -                | -             |   -21.13 | executoR, kinqie, Kiro, nota, tex1y |
|           28 |      698 | 2024-04-20 | DMS            | W   | 1.000      | 0.143        | -                | 0.504 (0.072)    | false (0.000) |    13.64 | executoR, kinqie, Kiro, nota, tex1y |
|           27 |     1100 | 2024-04-13 | Team PeeP      | W   | 1.000      | -            | -                | -                | false (0.000) |     2.62 | executoR, kinqie, Kiro, nota, tex1y |
|           26 |     1218 | 2024-04-10 | KOI            | L   | 1.000      | -            | -                | -                | -             |    -5.73 | executoR, kinqie, Kiro, nota, tex1y |
|           25 |     1283 | 2024-04-09 | PARIVISION     | W   | 1.000      | 0.500        | 0.003 (0.002)    | 0.374 (0.187)    | false (0.000) |    17.47 | executoR, kinqie, Kiro, nota, tex1y |
|           24 |     1391 | 2024-04-06 | XGOD           | W   | 1.000      | -            | -                | -                | false (0.000) |     4.28 | executoR, kinqie, Kiro, nota, tex1y |
|           23 |     1602 | 2024-04-01 | Pera Esports   | L   | 0.971      | -            | -                | -                | -             |   -12.65 | executoR, kinqie, Kiro, nota, tex1y |
|           22 |     1619 | 2024-03-31 | Monte          | W   | 0.965      | 0.500        | 0.199 (0.096)    | 0.378 (0.183)    | false (0.000) |    28.85 | executoR, kinqie, Kiro, nota, tex1y |
|           21 |     1661 | 2024-03-29 | System5        | W   | 0.952      | -            | -                | -                | false (0.000) |     6.35 | executoR, kinqie, Kiro, nota, tex1y |
|           20 |     2309 | 2024-03-13 | Betera Esports | W   | 0.846      | 0.500        | 0.036 (0.015)    | 0.315 (0.133)    | false (0.000) |    15.77 | executoR, kinqie, Kiro, nota, tex1y |
|           19 |     2721 | 2024-03-04 | GUN5 Esports   | L   | 0.786      | -            | -                | -                | -             |   -15.90 | executoR, kinqie, Kiro, nota, tex1y |
|           18 |     2735 | 2024-03-04 | HOTU           | W   | 0.786      | 0.143        | 0.011 (0.001)    | 0.323 (0.036)    | -             |    11.71 | executoR, kinqie, Kiro, nota, tex1y |
|           17 |     2800 | 2024-03-03 | Metizport      | L   | 0.778      | -            | -                | -                | -             |    -3.74 | executoR, kinqie, Kiro, nota, tex1y |
|           16 |     2826 | 2024-03-02 | Guild Eagles   | W   | 0.773      | 0.143        | 0.037 (0.004)    | 0.586 (0.065)    | -             |    20.29 | executoR, kinqie, Kiro, nota, tex1y |
|           15 |     3068 | 2024-02-26 | SAW            | L   | 0.739      | -            | -                | -                | -             |    -0.51 | executoR, kinqie, Kiro, nota, tex1y |
|           14 |     4145 | 2024-01-30 | Sashi Esport   | L   | 0.558      | -            | -                | -                | -             |    -3.03 | executoR, kinqie, Kiro, nota, tex1y |
|           13 |     4184 | 2024-01-29 | Jake Bube      | W   | 0.553      | -            | -                | -                | -             |     1.92 | executoR, kinqie, Kiro, nota, tex1y |
|           12 |     4724 | 2024-01-17 | Rebels Gaming  | L   | 0.472      | -            | -                | -                | -             |    -1.51 | executoR, kinqie, Kiro, nota, tex1y |
|           11 |     4812 | 2024-01-16 | LEON Esports   | L   | 0.465      | -            | -                | -                | -             |    -9.13 | executoR, kinqie, Kiro, nota, tex1y |
|           10 |     4936 | 2024-01-12 | BAKS Esports   | L   | 0.439      | -            | -                | -                | -             |    -9.36 | executoR, kinqie, Kiro, nota, tex1y |
|            9 |     5007 | 2024-01-11 | ILIN           | L   | 0.431      | -            | -                | -                | -             |   -10.79 | executoR, kinqie, Kiro, nota, tex1y |
|            8 |     5050 | 2024-01-10 | Lewandownskie  | W   | 0.426      | -            | -                | -                | -             |     4.43 | executoR, kinqie, Kiro, nota, tex1y |
|            7 |     5465 | 2023-12-16 | TSM            | W   | 0.259      | -            | -                | -                | -             |     3.20 | executoR, kinqie, Kiro, nota, tex1y |
|            6 |     5583 | 2023-12-15 | IKLA           | W   | 0.252      | -            | -                | -                | -             |     2.83 | executoR, kinqie, Kiro, nota, tex1y |
|            5 |     5650 | 2023-12-13 | BIG Academy    | L   | 0.238      | -            | -                | -                | -             |    -3.31 | executoR, kinqie, Kiro, nota, tex1y |
|            4 |     5691 | 2023-12-11 | TSM            | W   | 0.225      | -            | -                | -                | -             |     2.82 | executoR, kinqie, Kiro, nota, tex1y |
|            3 |     5763 | 2023-12-09 | Endpoint       | W   | 0.212      | 0.371        | -                | 0.785 (0.062)    | -             |     3.92 | executoR, kinqie, Kiro, nota, tex1y |
|            2 |     5876 | 2023-12-07 | TY             | W   | 0.199      | 0.371        | 0.011 (0.001)    | -                | -             |     2.28 | executoR, kinqie, Kiro, nota, tex1y |
|            1 |     5991 | 2023-12-05 | The Witchers   | W   | 0.185      | 0.371        | 0.035 (0.002)    | -                | -             |     2.95 | executoR, kinqie, Kiro, nota, tex1y |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($1,023.44)
- Divide that value by the 5th highest value among all rosters ($158,437.64)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
