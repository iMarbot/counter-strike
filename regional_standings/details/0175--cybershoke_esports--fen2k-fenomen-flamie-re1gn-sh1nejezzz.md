### Roster Details<br />
Team Name: CYBERSHOKE Esports<br />
Roster: fen2k, FenomeN, flamie, Re1GN, sh1nejezzz<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [175](../standings_global.md)<br />
Regional Rank: [119]( ../standings_europe.md)<br />
Final Rank Value:  750.6<br />
<br />
Final Rank Value (750.6) = Starting Rank Value (745.8) + Head To Head Adjustments (4.8)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.298[<sup>1</sup>](#table2)
- Bounty Collected: 0.291[<sup>2</sup>](#table1)
- Opponent Network: 0.109[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.174<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 745.8
- 400 + ( ( 0.174 - 0.000 ) / ( 0.806 - 0.000 ) ) * 1600 = 745.8


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent                 | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins      | H2H Adj. | Roster                                    |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           30 |     2215 | 2024-03-15 | Insilio                  | L   | 0.859      | -            | -                | -                | -             |    -5.55 | fen2k, FenomeN, flamie, Re1GN, sh1nejezzz |
|           29 |     2452 | 2024-03-10 | Zero Tenacity            | W   | 0.825      | 0.371        | 0.095 (0.029)    | 1.000 (0.306)    | false (0.000) |    19.98 | fen2k, FenomeN, flamie, Re1GN, sh1nejezzz |
|           28 |     2624 | 2024-03-06 | BLESSED (Ukrainian team) | L   | 0.798      | -            | -                | -                | -             |    -7.54 | fen2k, FenomeN, flamie, Re1GN, sh1nejezzz |
|           27 |     2883 | 2024-03-02 | 1win                     | L   | 0.771      | -            | -                | -                | -             |   -11.03 | fen2k, FenomeN, flamie, Re1GN, sh1nejezzz |
|           26 |     2918 | 2024-03-01 | K10                      | W   | 0.765      | 0.371        | 0.015 (0.004)    | 0.418 (0.119)    | false (0.000) |    15.58 | fen2k, FenomeN, flamie, Re1GN, sh1nejezzz |
|           25 |     3211 | 2024-02-23 | Lausanne-Sport Esports   | W   | 0.718      | 0.371        | 0.004 (0.001)    | 0.241 (0.064)    | false (0.000) |    11.32 | fen2k, FenomeN, flamie, Re1GN, sh1nejezzz |
|           24 |     3255 | 2024-02-22 | NOM Esports              | W   | 0.711      | 0.371        | 0.000 (0.000)    | 0.374 (0.099)    | false (0.000) |     8.48 | fen2k, FenomeN, flamie, Re1GN, sh1nejezzz |
|           23 |     3299 | 2024-02-21 | TBA.ECF                  | L   | 0.705      | -            | -                | -                | -             |   -11.10 | fen2k, FenomeN, flamie, Re1GN, sh1nejezzz |
|           22 |     3349 | 2024-02-20 | Kappa Bar                | W   | 0.698      | 0.371        | 0.002 (0.000)    | 0.149 (0.039)    | false (0.000) |     8.94 | fen2k, FenomeN, flamie, Re1GN, sh1nejezzz |
|           21 |     3410 | 2024-02-19 | Team Secret              | L   | 0.692      | -            | -                | -                | -             |   -11.94 | fen2k, FenomeN, flamie, Re1GN, sh1nejezzz |
|           20 |     3491 | 2024-02-17 | ARCRED                   | W   | 0.678      | 0.371        | 0.004 (0.001)    | 0.825 (0.208)    | false (0.000) |    13.74 | fen2k, FenomeN, flamie, Re1GN, sh1nejezzz |
|           19 |     3530 | 2024-02-16 | Endpoint                 | L   | 0.672      | -            | -                | -                | -             |    -6.85 | fen2k, FenomeN, flamie, Re1GN, sh1nejezzz |
|           18 |     3586 | 2024-02-15 | Entropiq                 | W   | 0.665      | 0.371        | 0.001 (0.000)    | 0.436 (0.108)    | false (0.000) |    13.05 | fen2k, FenomeN, flamie, Re1GN, sh1nejezzz |
|           17 |     3733 | 2024-02-12 | DMS                      | W   | 0.644      | 0.371        | 0.000 (0.000)    | 0.504 (0.121)    | false (0.000) |     8.39 | fen2k, FenomeN, flamie, Re1GN, sh1nejezzz |
|           16 |     4110 | 2024-01-31 | Ex-Anonymo Esports       | L   | 0.565      | -            | -                | -                | -             |    -6.72 | fen2k, FenomeN, flamie, Re1GN, sh1nejezzz |
|           15 |     4148 | 2024-01-30 | Eternal Fire Academy     | L   | 0.558      | -            | -                | -                | -             |    -8.46 | fen2k, FenomeN, flamie, Re1GN, sh1nejezzz |
|           14 |     4725 | 2024-01-17 | Ninjas in Pyjamas        | L   | 0.472      | -            | -                | -                | -             |    -5.88 | fen2k, FenomeN, flamie, Re1GN, sh1nejezzz |
|           13 |     4937 | 2024-01-12 | TEAM ZOO BAR             | L   | 0.439      | -            | -                | -                | -             |   -10.75 | fen2k, FenomeN, flamie, Re1GN, sh1nejezzz |
|           12 |     5036 | 2024-01-10 | Ex-Anonymo Esports       | L   | 0.426      | -            | -                | -                | -             |    -5.74 | fen2k, FenomeN, flamie, Re1GN, sh1nejezzz |
|           11 |     5045 | 2024-01-10 | INGLORIOUS               | W   | 0.426      | 0.143        | 0.005 (0.000)    | 0.358 (0.022)    | false (0.000) |     7.88 | fen2k, FenomeN, flamie, Re1GN, sh1nejezzz |
|           10 |     6209 | 2023-11-30 | TUSTE CHOPAKI            | L   | 0.151      | -            | -                | -                | -             |    -3.80 | fen2k, FenomeN, flamie, Re1GN, sh1nejezzz |
|            9 |     6252 | 2023-11-29 | Ex-Hot Headed Gaming     | L   | 0.145      | -            | -                | -                | -             |    -3.57 | fen2k, FenomeN, flamie, Re1GN, sh1nejezzz |
|            8 |     6311 | 2023-11-28 | L&G                      | L   | 0.139      | -            | -                | -                | -             |    -3.51 | fen2k, FenomeN, flamie, Re1GN, sh1nejezzz |
|            7 |     6776 | 2023-11-17 | TEAM ZOO BAR             | W   | 0.064      | 0.371        | -                | 0.051 (0.001)    | false (0.000) |     0.41 | fen2k, FenomeN, flamie, Re1GN, sh1nejezzz |
|            6 |     6816 | 2023-11-16 | ESCAPIST                 | W   | 0.059      | -            | -                | -                | -             |     0.45 | fen2k, FenomeN, flamie, Re1GN, sh1nejezzz |
|            5 |     6887 | 2023-11-15 | BIG Academy              | L   | 0.051      | -            | -                | -                | -             |    -0.66 | fen2k, FenomeN, flamie, Re1GN, sh1nejezzz |
|            4 |     7141 | 2023-11-09 | Team Spirit Academy      | L   | 0.011      | -            | -                | -                | -             |    -0.15 | fen2k, FenomeN, flamie, Re1GN, sh1nejezzz |
|            3 |     7147 | 2023-11-09 | GenOne                   | L   | 0.010      | -            | -                | -                | -             |    -0.21 | fen2k, FenomeN, flamie, Re1GN, sh1nejezzz |
|            2 |     7193 | 2023-11-08 | Wu-Tang Clan             | W   | 0.005      | -            | -                | -                | -             |     0.03 | fen2k, FenomeN, flamie, Re1GN, sh1nejezzz |
|            1 |     7198 | 2023-11-08 | LF0                      | W   | 0.004      | 0.371        | 0.006 (0.000)    | -                | -             |     0.05 | fen2k, FenomeN, flamie, Re1GN, sh1nejezzz |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($693.51)
- Divide that value by the 5th highest value among all rosters ($158,437.64)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
